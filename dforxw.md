代发 wailian999

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtepzgfghf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuanzx.com/Article/details/gtmqamrlgn.html

[S38] C++：排序
来源：http://dali.chenlongwang.top/Article/details/gtwkyeervc.html

std::sort(v.begin(), v.end());
来源：http://dali.xuanzx.com/Article/details/gtmmlmokwi.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gtnxpwzfqg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.andypj.xyz/Article/details/gtbyflmkzo.html

[S40] C++：查找元素
来源：http://dali.fzhhl.top/Article/details/gtwsknkxvd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtvtcuaaqe.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxaqcpklw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtbuhgvmyu.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtjucsudlc.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gtzfgcixqt.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gttalqfsro.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtdofcehvu.html

[S44] C++：引用传参
来源：http://dali.gogol.net.cn/Article/details/gtfbadmvxh.html

void inc(int &x) { ++x; }
来源：http://dali.aizwys.cn/Article/details/gtpvhvoiox.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtzjyelocv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gteknddthl.html

[S46] C++：函数模板
来源：http://dali.cdnleiting.top/Article/details/gtkbiuetef.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtytolmcdj.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtecbfbsku.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtuisaymip.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtoxfkdadq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtxnccimxn.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gthytzhurb.html

[S49] C++：写文件
来源：http://dali.haohaochexian.top/Article/details/gtbrqbjcze.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj202588.top/Article/details/gtfbnqcuau.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtuwvywnde.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtjgqgsxhe.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtnppnfplv.html

static_cast<double>(a) / b
来源：http://dali.aizwys.cn/Article/details/gtawmpdhfc.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtlqnlmuaz.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gtkbgsmdiw.html

[S53] C++：移动语义
来源：http://dali.yuxming.cn/Article/details/gtenxhrrac.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtyuliwszb.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtyljdmxrd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtmdicbmah.html

[S55] C++：结构化绑定
来源：http://dali.jqgfzy.top/Article/details/gtlhhhdzxj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtuwnhemex.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gtdwawpogd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gthnycyikn.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gtftmmgguq.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gttdtfnsem.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtbqhygxzi.html

namespace ns { int f() { return 1; } }
来源：http://dali.kuanghao11.cn/Article/details/gtkfxcuphr.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtrsjaiedn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guowangkeji.top/Article/details/gtauzqbbun.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtzgpgqvmg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtmetydcjt.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtkndcpwrm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gaohongyu789.top/Article/details/gtlfurlnxn.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqnmqvulq.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gthafqoavu.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezlgzksd.html

[T02] Kotlin：变量
来源：http://dali.jinqigufen.top/Article/details/gtzazijlfb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jianghu66.top/Article/details/gtnwlbkpxi.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtvwjtrjhr.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtpxakygwp.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gtzxpohxcq.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtlcrasqol.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gttqhkojgv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtogyatfmp.html

[T06] Kotlin：集合映射
来源：http://dali.birdmap.top/Article/details/gtwqbdyjet.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtkzkapszy.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtniyvgapb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtuysdidcy.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtyfqugcad.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gtktpstakt.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtufbumxzb.html

fun String.exclaim() = this + "!"
来源：http://dali.yongpay.top/Article/details/gtdbrhjscz.html

[T10] Kotlin：默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslepfppo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.havefunace.top/Article/details/gtmjqmbtug.html

[T11] Kotlin：协程
来源：http://dali.pengpengdd.cyou/Article/details/gtwdemecfm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmwjdvdc.html

[T12] Kotlin：解构声明
来源：http://dali.svipenyu.cn/Article/details/gtkncrekic.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtnapsrszs.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtaumwmspk.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gtpagmsooy.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtcjutnboo.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtnavrccmt.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtcbnyfjmv.html

interface Shape { fun area(): Double }
来源：http://dali.0kj1m.cn/Article/details/gtvhakujmk.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gteynhnewt.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtxrlrqwcb.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gttiwjnxep.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gthmgzapiw.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtvhjwbjjz.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gtlierfdwj.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gteenlnepz.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtumjjemhy.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gtyrutkkkz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtqtblhzhk.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtpetbgluv.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvrnoxsy.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtzrthutnm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtcxrptnkv.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtsajalvjf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtdyhwvecp.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gttxwkrsyp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtwaotdmtb.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtikghifft.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtxpyxduci.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtdkbassul.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtdjttefhk.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtamcvavpz.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gtgwyxzvve.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtnbcajyrt.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtuvuncibi.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtrdcimygu.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gtanltkbcc.html

[T30] Swift：协议
来源：http://dali.smart0.xyz/Article/details/gtdcnecmtm.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtaivgsnpi.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtajmdppra.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtidcxgtvo.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtzpakkxgz.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtjvpystay.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtwiydbohc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtnsvkzedk.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtunquxifk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tian-w.cn/Article/details/gteepkfaun.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtwayggdjz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gtsetodtni.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtzlusyjqz.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gtboefnzuo.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtpqutoimp.html

"a" .. "b"
来源：http://dali.ybcxt.top/Article/details/gtyzavomei.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gtnemsggbk.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtpkxnbxlm.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtapnbkzea.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtlianmfed.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gtshnphxnc.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtklacmtqh.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtlpcoeffw.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtfzqkvgpu.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gtoxkiutwl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtipjtmaaa.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gtnqovxgjn.html

"值: $a"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsixzvasy.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuujnzbza.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtgvhjxhfh.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gtgmzjihkc.html

for my $x (@arr) { print $x; }
来源：http://dali.hfpthk.cn/Article/details/gtizssohow.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtsnyfeqnl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdvvnlje.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtveopnxxi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvdbgoic.html

[T48] Perl：正则替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdyafwots.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtukfaajby.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtvoyyfvps.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtjsgwxpmx.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtuhcjfvbf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fzhhl.top/Article/details/gtkweugniv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtqxizdquy.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtxdmlsajk.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtennekbly.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtyteasfqb.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtyjmutumd.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gttaejtinp.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtpqtjwwcf.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtzmtshjlp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtgtvjhagw.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtactzfsim.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtfpjiques.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gtjpzhttck.html

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtksciyjig.html

[T57] Scala：模式匹配
来源：http://dali.jianghu66.top/Article/details/gttjlvnpkj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.iojbl.cn/Article/details/gtzvfethfq.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gtgcogbbtz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtnfllojti.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gtwhcqnyiz.html

for (i <- 1 to 10) println(i)
来源：http://dali.andypj.xyz/Article/details/gtrhqqzxgy.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gtsiaqdsur.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgixlhxp.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtamtnckwz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtsholjlxb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gthnspgcsx.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtehvppbnv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gtujahvyod.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gteyvrtobc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xylfe.cn/Article/details/gtdtbjeisp.html

[U03] Py：加载 .env 配置
来源：http://dali.gotoacloud.top/Article/details/gtarvqgbjl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cheryme.top/Article/details/gttwthxagh.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gtfeswyosq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtgurrnhzm.html

[U05] Py：列表去重且保序
来源：http://dali.sxryk.cn/Article/details/gtmsrbbtfh.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gtrayjolxa.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtfkechrpd.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gthjrqaaap.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtjbeceiuo.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gtodkxuogw.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtbycxfhbo.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtcbcbxbhq.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtlcerbzoy.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gtbqnlxzph.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtgmckjohk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gthatkbnhn.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtpnzsylsj.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gttsisihgs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.daria6918.cn/Article/details/gtjyvwtsqs.html

Counter(arr).most_common(3)
来源：http://dali.tian-w.cn/Article/details/gtygsnstxa.html

[U13] Py：固定长度队列
来源：http://dali.pycfn.com/Article/details/gtmgjmtgrs.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtlckaotgl.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtywfqixtv.html

defaultdict(list)
来源：http://dali.jiagoushi.top/Article/details/gthzwslneh.html

[U15] Py：高精度计时
来源：http://dali.tian-w.cn/Article/details/gtrlbtkjya.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtcqqamsvh.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gtalhhjqup.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xziqi.cn/Article/details/gtqryslsbf.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gtairtvjwq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.nanxinkj.top/Article/details/gtatbbhlaw.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gtdjhhlplf.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtrgplqjdg.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gtpapiruyf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtffoiwbmp.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gtlptucapw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtojzpqyms.html

[U21] Py：自定义上下文管理器
来源：http://dali.cucudq.cn/Article/details/gtlpixywfq.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtwikhldnf.html

[U22] Py：矩阵转置
来源：http://dali.havefunace.top/Article/details/gtaexhydiv.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtvnrxrmjz.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gtmlkavugr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtzorkpjdr.html

[U24] Py：路径操作
来源：http://dali.havefunace.top/Article/details/gtqdssefxk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gaohongyu789.top/Article/details/gtkheeeocm.html

[U25] Py：CSV 按字典读
来源：http://dali.ivvv.top/Article/details/gtvugfrpgw.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gtozrgpbfc.html

[U26] Py：并发下载
来源：http://dali.hnqzz.top/Article/details/gtgcdkjspb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zdqjudy.top/Article/details/gtajlgzcow.html

[U27] Py：异步 HTTP
来源：http://dali.zhiwuduotai.top/Article/details/gtxurqvgfu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtfjjeqghs.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gtkisyboml.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtejamfavv.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gtfbmglgfy.html

@property 与 @x.setter 配合
来源：http://dali.nwbrower.top/Article/details/gtiixchntp.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtnvufqxmn.html

@dataclass(slots=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtifrgdsay.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtgbpgepjj.html

python -m pytest -q
来源：http://dali.hammf.cn/Article/details/gtxuvfubjk.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gticfnitwk.html

ruff format . && ruff check --fix .
来源：http://dali.yuanzhike.top/Article/details/gtmrariowo.html

[U33] Py：打包发布
来源：http://dali.yangfankeji.com/Article/details/gtxwujhisn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gtvcwweuhp.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gtgrtbyjdn.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gtqpywbbqz.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtjwbcirww.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtktojgzaj.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtqzssgrtw.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfdgegpw.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtahlrzqln.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtwutweilq.html

[U38] Py：获取脚本所在目录
来源：http://dali.gaohongyu789.top/Article/details/gtstvojlit.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtascbqnwy.html

[U39] Py：判断是否在交互环境
来源：http://dali.tanke756.top/Article/details/gtewdfdhtw.html

sys.stdout.isatty()
来源：http://dali.zhijiandao.cn/Article/details/gtnzomgvjy.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtsfuyauct.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtuysnyjrl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtqetdfgsq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyeftoenh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.bjfxy.top/Article/details/gtccofkdmv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtvlbstglz.html

[U43] PHP：声明命名空间
来源：http://dali.meibo888.top/Article/details/gtnfryjyuu.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbuawout.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gthppxcdkf.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtiuzpqnao.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtumacgkjz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbsopcbqp.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gtjfzxyzaw.html

?string $name = null
来源：http://dali.fzhhl.top/Article/details/gtgljehxva.html

[U47] PHP：联合类型
来源：http://dali.zdqjudy.top/Article/details/gtpwvrkstt.html

int|string $id
来源：http://dali.ppjwa.cn/Article/details/gtjjepvvcj.html

[U48] PHP：纯枚举
来源：http://dali.sysykeji.top/Article/details/gtnwgxtepf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.aizwys.cn/Article/details/gttsspiyuv.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtdrlvpflm.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gteviniqjd.html

[U50] PHP：构造器属性提升
来源：http://dali.gotoacloud.top/Article/details/gtimolubnr.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtfrzbghru.html

[U51] PHP：数组解构
来源：http://dali.chenzaomai.com/Article/details/gtmuzvkhkq.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkhxebohj.html

[U52] PHP：箭头函数
来源：http://dali.nanxuanxn.top/Article/details/gtuvtikquq.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtjtkhwnxr.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gtocbzigxt.html

$v = $a ?? $b ?? "default";
来源：http://dali.smart0.xyz/Article/details/gtowyzpcew.html

[U54] PHP：空安全调用
来源：http://dali.zhoulong.xyz/Article/details/gtlcrzcxnp.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gtuvyahord.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtfqyzpfgm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtjpenzwxh.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtohjbfppq.html

f(a: 1, b: 2)
来源：http://dali.yj20258.top/Article/details/gtgwxkmrcc.html

[U57] PHP：字符串插值
来源：http://dali.ivvv.top/Article/details/gtvcztxmlw.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gtffruofes.html

[U58] PHP：数组三件套
来源：http://dali.pycfn.com/Article/details/gthirphmiu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtnegppmff.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtdcirjivx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtainfiauu.html

[U60] PHP：JSON 编解码
来源：http://dali.9152youxi.cn/Article/details/gtjtvujbbn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtotkejfqy.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gtmestsqkz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtorgmtflv.html

[U62] PHP：日期对象
来源：http://dali.nanxinkj.top/Article/details/gtsaiwuazs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtqhvepcvz.html


<!-- 参考信息 -->