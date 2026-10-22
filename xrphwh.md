代发 wailian999

[S35] C++：map
来源：http://dali.ppjwa.cn/Article/details/gtsvsgnpvv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtiforxnsm.html

[S36] C++：unordered_map
来源：http://dali.wangdashe.top/Article/details/gtdlmiogoq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtankkexdz.html

[S37] C++：set
来源：http://dali.guannengcc.top/Article/details/gttasqszxw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtburgtlyp.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtgpwqbwjy.html

std::sort(v.begin(), v.end());
来源：http://dali.mhx1999.top/Article/details/gtuwbjjfed.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gtymeonpdt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jyoumei.cn/Article/details/gtwdxckgze.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtcfczukcj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtnpwsrfzg.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtwueytbfp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtuhwdntmh.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntqindnw.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtukizrihk.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gtwnaizpai.html

auto p = std::make_unique<int>(5);
来源：http://dali.guannengcc.top/Article/details/gtgegdppze.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtjgxsyesh.html

void inc(int &x) { ++x; }
来源：http://dali.vqdsnc.cn/Article/details/gtlvgvhiri.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcuylkwh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtkerginzy.html

[S46] C++：函数模板
来源：http://dali.9152youxi.cn/Article/details/gtgqrurqig.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtvianulve.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtxwxdphlw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ybcxt.top/Article/details/gtdesmxkor.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gttlfsicqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznlzgrkq.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtlezvyajl.html

[S49] C++：写文件
来源：http://dali.aizwys.cn/Article/details/gtlouiidue.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtayrvwqji.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtdpeunmxx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtwhsrhbet.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtmpykdezq.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtvdsqjuzb.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtphjtvejn.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtbseakojn.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gtfzxgkrto.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtelxbwvtt.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtzqvdtdxx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gttmxaplby.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gttvxiobys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xinyue.icu/Article/details/gtehcgynnf.html

[S56] C++：optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkqnkanyu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtywvphjaj.html

[S57] C++：编译期常量
来源：http://dali.0kj1m.cn/Article/details/gtlwykojoh.html

constexpr int N = 10;
来源：http://dali.jqgfzy.top/Article/details/gtolvohnvj.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtcgjfygqz.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtezhvjiqt.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gthgilzarh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtdvpmsrln.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtyzeatnay.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtlyflexlu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbyeeuthj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtlfhhrkcw.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxtwzsfux.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gtkvgugpwp.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtnesxfodj.html

[T02] Kotlin：变量
来源：http://dali.zycfv.cn/Article/details/gtcclafwaa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtsxtispfg.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gtdwmphnbr.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtdwhyhadu.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioaqzxqg.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtjyodfqyx.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtpqfnguku.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtoaqnhvgf.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtuouexfvh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtofwgdyef.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtsgimhxlz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtmsmoslik.html

[T08] Kotlin：数据类
来源：http://dali.chenlongwang.top/Article/details/gtocpwkotr.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtwkdjzfpp.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtpdhcupkk.html

fun String.exclaim() = this + "!"
来源：http://dali.haohaochexian.top/Article/details/gtmcldchvj.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtxqzdmzpa.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtuclyhlpj.html

[T11] Kotlin：协程
来源：http://dali.aibaodan.cn/Article/details/gtbarczpjh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtzgvrkeki.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gteeqafiss.html

val (a, b) = Pair(1, 2)
来源：http://dali.haohaochexian.top/Article/details/gtrrdufzaj.html

[T13] Kotlin：只读 Map
来源：http://dali.hywenlv.cn/Article/details/gtwfsjmvve.html

val m = mapOf("a" to 1)
来源：http://dali.quarkkingdee.top/Article/details/gtesucmsbn.html

[T14] Kotlin：循环
来源：http://dali.zhijiandao.cn/Article/details/gthcnllhsy.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtqwtmpeme.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtvjamjclu.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtvtfajpkf.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtwgpgzexp.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtdqxyykfw.html

[T17] Swift：变量与常量
来源：http://dali.yonumen.top/Article/details/gtmxbptgyr.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gttfbimkrl.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtwbupknce.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtzmjnhskg.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtgclyqwmj.html

if let n = opt { print(n) }
来源：http://dali.yonumen.top/Article/details/gtlmgziwsi.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtpgfoytqz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtvizfkhbk.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtivtqeufu.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyposhpkw.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtoigtxjkn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gthbnwrrbf.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfkisplwq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gthvvadhfq.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtdxfltzla.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtolzfoaab.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtnqutyiwq.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtkzhvegvl.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtpzvvktjp.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctruyjsf.html

[T27] Swift：错误处理
来源：http://dali.cashguo.top/Article/details/gtohdierxa.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gtvovdrspl.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtmptfxzax.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtkeuelwsf.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtyergqtak.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gthyznwsci.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtytucjvgl.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtfowhvbji.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtjrqxgkkb.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtbcjhhstx.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtfdwtcpdn.html

local a = 1
来源：http://dali.hammf.cn/Article/details/gtrwqqyidb.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtlrgbjzsj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtzuzexfrw.html

[T34] Lua：遍历表
来源：http://dali.haohaochexian.top/Article/details/gtuvitddsy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtgjdyyqda.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gtvcrqivnt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtkyfvtzfg.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtazgrnrwy.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtsaejpuih.html

[T37] Lua：字符串拼接
来源：http://dali.quarkkingdee.top/Article/details/gtzkzkxscn.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvytnowmv.html

[T38] Lua：条件
来源：http://dali.shangyingyoupin.top/Article/details/gtogbivkrs.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtqaybskdn.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtelxtgpfc.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopgccwfz.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gtxgxpnirt.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtheuocgmn.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtvrrnocaj.html

print "Hello\n";
来源：http://dali.yuanzhike.top/Article/details/gtyfxvrwib.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtosvawhfn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtfcrgpyrg.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtmrtgdplo.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfloadkqj.html

[T44] Perl：条件
来源：http://dali.redwolf501.top/Article/details/gtzgyqjkga.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtzbuikkon.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtsbdrfxvf.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gtgtxbcvul.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gthugvkior.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gtphrcudgv.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gtedtzfejd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aibaodan.cn/Article/details/gtviootwad.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gtkhgqaoki.html

$s =~ s/old/new/g;
来源：http://dali.daxiang520.top/Article/details/gtmbgnaxfv.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtexhjecip.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gttmoojydw.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtcrbrgubc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gtxpthigpe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hnxiangtu.top/Article/details/gtcwuytgxw.html

[T51] Scala：Hello World
来源：http://dali.nwbrower.top/Article/details/gtnshsbppy.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtiqabewac.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhnqokdl.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsemrzfjj.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtanpxpgyw.html

s"值: $b"
来源：http://dali.andypj.xyz/Article/details/gtsulcnhqg.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtqmjshols.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtnprspqxk.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtmyucfyry.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtfhodgdql.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gtcjrqmafo.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtkysdqpgo.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtkhmewcue.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gttkwlzhrj.html

[T58] Scala：函数定义
来源：http://dali.316326.xyz/Article/details/gtpgtwmqoi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtgrhiujun.html

[T59] Scala：循环
来源：http://dali.fengsongda.top/Article/details/gtjeqoweab.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gttjbaobdg.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gttxwknhhx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gtytjsnvmy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtesirfilq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gtvduinske.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtseynxrkz.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtklajyvlt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtwovdiroq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.meibo888.top/Article/details/gtzzjwtwcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ehwqpu.com/Article/details/gtntfybjnx.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtskqswvyu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtvbcdzuao.html

[U04] Py：变量调试打印
来源：http://dali.ydzc1.top/Article/details/gtcxlzfqom.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yongpay.top/Article/details/gtpvpcibun.html

[U05] Py：列表去重且保序
来源：http://dali.mhx1999.top/Article/details/gtgjtjszaw.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtnzzeahhg.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gtieegqbdp.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtcboeotju.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtfitkexqe.html

{v: k for k, v in d.items()}
来源：http://dali.daria6918.cn/Article/details/gtukxmbmhw.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtocussysv.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtlczjsvmc.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gtyahyufot.html

max(d, key=d.get)
来源：http://dali.yangfankeji.com/Article/details/gtkjxeqetc.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtnabiwfvb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.vqdsnc.cn/Article/details/gtkvjozjji.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtysbntfku.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdppgujd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cheryme.top/Article/details/gtsppxerzp.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtsxkpbjkh.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gtbtypowyi.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gtqomgvkys.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigufen.top/Article/details/gtwxdgbwgh.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtrjxzqmqx.html

[U15] Py：高精度计时
来源：http://dali.xylfe.cn/Article/details/gtvsfyrfrc.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtcgwvfhzk.html

[U16] Py：命令行参数解析
来源：http://dali.vqdsnc.cn/Article/details/gtkqrlymap.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtcuzfbqpe.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtahmjkada.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hfpthk.cn/Article/details/gtiztmtouc.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtevesppbh.html

pat = re.compile(r"\d+")
来源：http://dali.cdnleiting.top/Article/details/gterevhmif.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtmwzrkeec.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtmbpufbqj.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtaihgjnxg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtgtcrytrz.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gtievxzzix.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpocvdyy.html

[U22] Py：矩阵转置
来源：http://dali.vqdsnc.cn/Article/details/gtwsaxwmac.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtofhknxbe.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyhvrlhh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.0kj1m.cn/Article/details/gtpxratguo.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtjqxszhup.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspusoveb.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtimtiffae.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtsnooutew.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtmhdnbche.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjbcqauo.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtsrumukes.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xuetiantiany.cn/Article/details/gtpjuqknsb.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gtuhccuyfn.html

UserId = int
来源：http://dali.ivvv.top/Article/details/gtppndjfiy.html

[U29] Py：属性校验
来源：http://dali.yangfankeji.com/Article/details/gtjfzbkpou.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gtcnfnamar.html

[U30] Py：数据类
来源：http://dali.jinqigfzy.top/Article/details/gtbgyxdwlq.html

@dataclass(slots=True)
来源：http://dali.ybcxt.top/Article/details/gtilsqesnj.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gtanabxmyp.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtaaqfjdgn.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gtvnvrixsb.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtmguugxpi.html

[U33] Py：打包发布
来源：http://dali.hysaishi.cn/Article/details/gtmjyihttx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtwhivsqro.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gtdgdrhwqu.html

chardet.detect(raw)
来源：http://dali.redwolf501.top/Article/details/gtdnfcwkjs.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gtnoeubdjl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gttjssctem.html

[U36] Py：定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtnhhddgpd.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtfurfkzwk.html

[U37] Py：读写 Excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagzqsphv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtnsnqibxn.html

[U38] Py：获取脚本所在目录
来源：http://dali.gogol.net.cn/Article/details/gtflgorcwx.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtutdkauca.html

[U39] Py：判断是否在交互环境
来源：http://dali.jianghu66.top/Article/details/gthmytcfxs.html

sys.stdout.isatty()
来源：http://dali.gaohongyu789.top/Article/details/gtmfpcirte.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaffirup.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtrssszfcj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtrsshyrtm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenlongwang.top/Article/details/gtaqhyuose.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwhfsnvp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gtaopoovhb.html

[U43] PHP：声明命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtlbpwjwng.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gtdkgalduw.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtvvyncayi.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtnyzpcczq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gtigbrjkkv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtdlcrsgbn.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtsgiydhjh.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkgxglfc.html

[U47] PHP：联合类型
来源：http://dali.cucudq.cn/Article/details/gtmcigjylj.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gtzycokdtr.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gtmpmvjftw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gtmvbxvckq.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtzmdjamsr.html

public readonly string $name
来源：http://dali.xziqi.cn/Article/details/gtnkhnpxxz.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtgcgchwdr.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gttaanhret.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtvaqkyqfz.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtjcxqtiao.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gthdqxwnoa.html

$double = fn($x) => $x * 2;
来源：http://dali.nanxuanxn.top/Article/details/gtfreoxfea.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gtnripueio.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtnuwgfbfs.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gtnrjtsvry.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtprxeuqtj.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gteadqilgw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yonumen.top/Article/details/gtudeaswbd.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gtbxtkvokd.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtllztdppm.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtoeowpzlc.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gtsomsqvum.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gtsdmcqswc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gtltgmgwti.html

[U59] PHP：自定义排序
来源：http://dali.ybcxt.top/Article/details/gttvfgggmz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtaorftzwq.html

[U60] PHP：JSON 编解码
来源：http://dali.hnqzz.top/Article/details/gthttaxvan.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtetnjbowr.html


<!-- 参考信息 -->