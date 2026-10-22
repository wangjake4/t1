代发 wailian999

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtbfgisody.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gtwmhakgqo.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtinpjoyqd.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtqmrlefxi.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtqarzpjtt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ehwqpu.com/Article/details/gtrfrvhkyv.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtcolekofh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.aizwys.cn/Article/details/gtshrkhcqq.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtfxtkkocw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtahyeopur.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gtrquhfgab.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtdcimdhye.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtfovlqffp.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuanzhike.top/Article/details/gtjzdhksfz.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxysxeeb.html

void inc(int &x) { ++x; }
来源：http://dali.c1oappe.top/Article/details/gtadcrxgyl.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtjypihslr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dashuyun.cn/Article/details/gtrrqxbkfu.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gtpkevtadr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtvlktavvc.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsireuwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtqufehzat.html

[S48] C++：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtfvjraclu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtvegftnjf.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gtteigwwcr.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtdfizstng.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daxiang520.top/Article/details/gthhlqrlsx.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtpwfpynbt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtugrnkmve.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtahaggual.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtcnhpiulf.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gtyieawqkx.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtxgubtwud.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gtuerkhate.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtgulfdcat.html

[S54] C++：异常处理
来源：http://dali.kuanghao11.cn/Article/details/gtfahfkuij.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yongpay.top/Article/details/gtfzzrkakq.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtnmuwjwyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtstozcybc.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtxvbpeygi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtbtrqwaon.html

[S57] C++：编译期常量
来源：http://dali.hfpthk.cn/Article/details/gtkpebnkcb.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtwkarmgso.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtnayxasye.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecwvcirq.html

[S59] C++：静态断言
来源：http://dali.guowangkeji.top/Article/details/gtvriacbru.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gtbpzgsshl.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtugqhehsj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtcobnvipw.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtctrkhnim.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtpqwcrumb.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtfblagpyq.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtzfkgplhm.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtvmwinygr.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtbqramynn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtgfluyaxg.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtbkegqwia.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtcxxsxmyy.html

[T04] Kotlin：空安全
来源：http://dali.cqqwz.cn/Article/details/gtwnixjwwt.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtxmsdrlhn.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258888.top/Article/details/gtpqobycuk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtkbgnffev.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtolzswkmw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtlrymeufg.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtnnguagdw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtwcsqzucl.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gttxmhasrv.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtrkpvpsda.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gthlmlraba.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gttcspfgwk.html

[T10] Kotlin：默认参数
来源：http://dali.hysaishi.cn/Article/details/gtnxixlahh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtyyvrpwom.html

[T11] Kotlin：协程
来源：http://dali.9152youxi.cn/Article/details/gtvglekhla.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gtucfwcabc.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtinhnqkvb.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtqkrhmdvk.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gtrohbtpjo.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gtyhgjgoso.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtdengreel.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtrisjuwnb.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtqmnyocoo.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtmynhhbav.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gttirzampp.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtubedrrfh.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gthjvojmif.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtthmpkbhf.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtexctkvdh.html

"值: \(b)"
来源：http://dali.jiagoushi.top/Article/details/gtneijmvhy.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gtbasorlvm.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtwobbmsmo.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtxdvcjvds.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gthmfkwqjl.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrlnlpwa.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtutudgtjv.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtovlfvnpy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtbjfldfee.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtguptrjmr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtmyckeifp.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtrbqxigls.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tanke756.top/Article/details/gtqhfkowab.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtkwzyatte.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtaluowuan.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtujsnthoe.html

class A: Base { override func f() {} }
来源：http://dali.nanxuanxn.top/Article/details/gtjxcyutri.html

[T27] Swift：错误处理
来源：http://dali.jqgufenzy.top/Article/details/gtskwxrhpy.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtrdjgocpv.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtlhlymilh.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtunpcdicl.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gtdvldftha.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtzaofbhsd.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gtschxchiv.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkmckgdxi.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtpantztgs.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gthvocwhhf.html

[T32] Lua：局部变量
来源：http://dali.zdqjudy.top/Article/details/gtjzvfswlo.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtyahhevog.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtwdapojqy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sxryk.cn/Article/details/gtigcqdzxl.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtsqidjczg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtdnvtghor.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gttvhwduyw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtkymwclrk.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtgcmsdvjl.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtcodpngga.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtpiflixuz.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gttozmnotu.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtuhipwkaf.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtqbvfqgkv.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtmpsevckc.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtghplkjwr.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtemjairen.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gtpnvgsnrk.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtqsupkayc.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwiarlor.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtbvhvhmwh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gttssvitka.html

[T43] Perl：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtarauhwtg.html

"值: $a"
来源：http://dali.aizwys.cn/Article/details/gtjcwsthdl.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtdzwgdvrb.html

if ($a > 0) { print "正"; }
来源：http://dali.yj20258.top/Article/details/gttbbypmcv.html

[T45] Perl：数组遍历
来源：http://dali.ivvv.top/Article/details/gtrfdmykou.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gttrhjeywv.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtpwepyndq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtartyzssd.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gtcksnfhlu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnusdush.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtyyxmwrnz.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtiqwelnse.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtxtstisqm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtcckcldgl.html

[T50] Perl：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtpjkxrebn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.havefunace.top/Article/details/gtulfuibsb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.vqdsnc.cn/Article/details/gtcqhcrihi.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtulzqdwqh.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gtagsmrssi.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtmifzsied.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtksnwpelz.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gtcpuzewwu.html

s"值: $b"
来源：http://dali.sweek.top/Article/details/gtgjfirkda.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gteyqnciqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtrqvvdqad.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyimjrqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gtbqttdaxf.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtmzgxjjmh.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtoxvijuhr.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtsvnnemul.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswlwgnnn.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtcddidzlz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gtddqdvsmo.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsveowjed.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtcbiliclg.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtesyyrrps.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtuhkwsquq.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmogpyuxr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gtpotzoqld.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gttcbtjyvg.html

[U01] Py：创建虚拟环境
来源：http://dali.hywenlv.cn/Article/details/gthomwgwmv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtovbopxeu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dashuyun.cn/Article/details/gtskgzhsqt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gthcteisos.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtvvaphwvo.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtfhteshuu.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtlbtzryxe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtkqnyklkm.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtjpzmuaat.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtchavapit.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gthjdczdaz.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtzhdfakjs.html

[U07] Py：反转字典键值
来源：http://dali.sweek.top/Article/details/gtzjsaprbt.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gtuodjdqra.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtfamprulm.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gtmppurtze.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtdthzejmy.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gtiqyfwqqo.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gtaeuwczvf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtnazsdcmk.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtrdfqauis.html

(x * 2 for x in arr)
来源：http://dali.daria6918.cn/Article/details/gtapjhiqtp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtthcaoyjz.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtuqmudhik.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtczzmgiwj.html

deque(maxlen=10)
来源：http://dali.mhx1999.top/Article/details/gtydunjszs.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtfkczqrkf.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtpnelzwud.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtyqxdtani.html

t = time.perf_counter()
来源：http://dali.yueranfly.top/Article/details/gtvherpumx.html

[U16] Py：命令行参数解析
来源：http://dali.gaohongyu789.top/Article/details/gtwadetius.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gttxmfczqo.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtefummxpb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvdglysuc.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gtgmuqwcpw.html

pat = re.compile(r"\d+")
来源：http://dali.hnqzz.top/Article/details/gtkvyedibf.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtwboqhing.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.redwolf501.top/Article/details/gtckboryms.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gtybvtatai.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtppxcftkh.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gtutbacdoo.html

@contextlib.contextmanager
来源：http://dali.vqdsnc.cn/Article/details/gtjgkdztcp.html

[U22] Py：矩阵转置
来源：http://dali.xziqi.cn/Article/details/gttxrabsdb.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtmkpnxydu.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtdaczdcvx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gtlwnziaqa.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtwffjzyyx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.0kj1m.cn/Article/details/gtctpxqdtl.html

[U25] Py：CSV 按字典读
来源：http://dali.yanxiufei.cn/Article/details/gtimrxefdw.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gttaypabhu.html

[U26] Py：并发下载
来源：http://dali.hfpthk.cn/Article/details/gtiiagpnnt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtpipmznxt.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtskwbkyty.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gthxzvqoje.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gtftevenhm.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtkwfupkil.html

[U29] Py：属性校验
来源：http://dali.xuetiantiany.cn/Article/details/gtjvsjdcgd.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtbfgdievg.html

[U30] Py：数据类
来源：http://dali.ydzc1.top/Article/details/gttzxgbfiu.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtyibowccn.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdzfjfsz.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gthwcxwuga.html

[U32] Py：代码格式化
来源：http://dali.jianghu66.top/Article/details/gtqocmvmat.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtisyxaolh.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtkpgydyfc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtpupmwxlp.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gtydzkmcun.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtaebzlzvl.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtbhmvgcue.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtsisidurf.html

[U36] Py：定时任务
来源：http://dali.ydzc1.top/Article/details/gtdvycjbfi.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gteqoqfuun.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtfegaczgs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.aizwys.cn/Article/details/gtnianjprc.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtheeoqrbu.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtbxlkemte.html

[U39] Py：判断是否在交互环境
来源：http://dali.zdqjudy.top/Article/details/gtmxmqkooz.html

sys.stdout.isatty()
来源：http://dali.chenzaomai.com/Article/details/gtvustwezf.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gtxjyrldmf.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtjhlmjbkh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gtismlvtko.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yangfankeji.com/Article/details/gtuwjzidhh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtcxkxjbfw.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigufen.top/Article/details/gtkwiiadrp.html

[U43] PHP：声明命名空间
来源：http://dali.kuanghao11.cn/Article/details/gtghrfyvjv.html

namespace App\Http;
来源：http://dali.yueranfly.top/Article/details/gtsmumvkqh.html

[U44] PHP：开启严格类型
来源：http://dali.tianlin.xyz/Article/details/gtwlwwsedl.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gtufdxhlnj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuetiantiany.cn/Article/details/gttabkonze.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gturmuazob.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtzrikqvff.html

?string $name = null
来源：http://dali.svipenyu.cn/Article/details/gthtrfjvub.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtzipgmovd.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtzgdnqsql.html

[U48] PHP：纯枚举
来源：http://dali.yuanzhike.top/Article/details/gtiywuqwed.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtndkdwirl.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gtlzrxaicl.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gtdjrfecpq.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtpizqkzro.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtydfjnzwu.html

[U51] PHP：数组解构
来源：http://dali.zhongyouzk.top/Article/details/gtohsaycre.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtsgkkztdr.html

[U52] PHP：箭头函数
来源：http://dali.yuxming.cn/Article/details/gtbajdqdez.html

$double = fn($x) => $x * 2;
来源：http://dali.bjfxy.top/Article/details/gtgajlvizh.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtqjiivlwz.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtbtmhaisj.html

[U54] PHP：空安全调用
来源：http://dali.daria6918.cn/Article/details/gtxvhuxkzj.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtsqcysmuh.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtrgpztelc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gtqgehrcxm.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtdshunwet.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtviqftlfi.html

[U57] PHP：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtrlzckldd.html

"值: {$a}"
来源：http://dali.vqdsnc.cn/Article/details/gtxesxigwo.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtmbwabqgy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtkonawhmu.html

[U59] PHP：自定义排序
来源：http://dali.tian-w.cn/Article/details/gtcdvvaacu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtlbeczemj.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtqvmyhlpz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtrpibikgq.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gtmagyprcb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtckuakbpi.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtondzflsz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yueranfly.top/Article/details/gtydzyicfk.html


<!-- 参考信息 -->