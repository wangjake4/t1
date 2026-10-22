代发 wailian999

[S37] C++：set
来源：http://dali.nanxuanxn.top/Article/details/gtbyfkpalc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gtjsakhuwt.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gtlixmwvqn.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtznoynugz.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gtwnaubwdr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtfqrwezue.html

[S40] C++：查找元素
来源：http://dali.shangyingyoupin.top/Article/details/gtqvxdbjmo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnqzz.top/Article/details/gtqzihozyz.html

[S41] C++：类与构造函数
来源：http://dali.ehwqpu.com/Article/details/gtfwwjjyjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gthmggdjxp.html

[S42] C++：继承与虚函数
来源：http://dali.zhengqikj.top/Article/details/gtwcxrdatc.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinghuilouyu.cn/Article/details/gtmitattof.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtmjqfelwz.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtjsygmtam.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtioqyzwdi.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gthfpvwijh.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gtmxefojwz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.9152youxi.cn/Article/details/gthsbmkbkq.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnoflxtw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtrtngrgow.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtivydtumx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtsercxkcz.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gttpeukqig.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtmfkierep.html

while (std::getline(in, line)) { }
来源：http://dali.cucudq.cn/Article/details/gteuntkfab.html

[S49] C++：写文件
来源：http://dali.redwolf501.top/Article/details/gtlftaaovz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gtakrgjtbh.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtnhfoyjpi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtwxnsqcvq.html

[S51] C++：显式类型转换
来源：http://dali.gzhubu.top/Article/details/gtdcurgvis.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtykjckgbd.html

[S52] C++：const 与 noexcept
来源：http://dali.tianlin.xyz/Article/details/gttrubbdsj.html

int size() const noexcept { return n_; }
来源：http://dali.jyoumei.cn/Article/details/gtapqqzmct.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtzzqfqqzj.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtdqzbtqee.html

[S54] C++：异常处理
来源：http://dali.zhongyouzk.top/Article/details/gtftabmjqb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtfspvcusy.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gttezlxjbz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ppjwa.cn/Article/details/gtmbkwqcli.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gtxzpqpqpb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtrjhwtvmg.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtnmntfpkf.html

constexpr int N = 10;
来源：http://dali.mhx1999.top/Article/details/gteectxkuf.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtzsjuivcs.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtifqxxebc.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtnirxextq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtruwqinnt.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtheyaydiw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gttfkkdqzd.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqtvyqsfz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gthssgrsda.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gttgmscuxd.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtjopviffn.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtrdqxxcbh.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtvnpjfpou.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pengpengdd.cyou/Article/details/gtlllsczax.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gttnznsqdh.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtsrwrlszg.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtrqawewlc.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtplspuyiw.html

[T05] Kotlin：when 表达式
来源：http://dali.cashguo.top/Article/details/gtxxkwsrdp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gtrdmpquck.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtmetubdzn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbontqzk.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gttjiodvqu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtrggmgxvu.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gtpjqztedi.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtmfijjkyz.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gtyrfzhjqg.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtimebtacg.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvcqvwysj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtqmcsthnf.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtiiilgpfr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yuxming.cn/Article/details/gtwvjldxsp.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtcfcofmpf.html

val (a, b) = Pair(1, 2)
来源：http://dali.jianghu66.top/Article/details/gtviiujrsh.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtdgmnjmty.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gtyxfxgzbc.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtokuhtyoq.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnymbcrtz.html

[T15] Kotlin：接口
来源：http://dali.cdnleiting.top/Article/details/gtogbtklwt.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtkbdwnfce.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtxfamgodw.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtfziehfkx.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtycvogscg.html

var a = 1;  let b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtrgzswqxr.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtssabxtey.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gtccpdkaqd.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtifpoozma.html

if let n = opt { print(n) }
来源：http://dali.gzhubu.top/Article/details/gttpjyuybp.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtpofpllfd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtmsitwkjv.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtwlrisxib.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtdmxpfnfq.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtrgpkgjxi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtrxxdmwdu.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtlzmgndyg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtwkbajpaa.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxzublbc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtbuiyuryx.html

[T25] Swift：结构体
来源：http://dali.zdqjudy.top/Article/details/gtbnjmmway.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtghtrormi.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gticpxqced.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gtkvtjbmwu.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtxnhjhjna.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gtcietxted.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtccdrdicj.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtulyllbuk.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklcpgqke.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtfdmlxvwa.html

[T30] Swift：协议
来源：http://dali.yueranfly.top/Article/details/gtvhcymmfk.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtsccgnshg.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtoomqraue.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtboeumgif.html

[T32] Lua：局部变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzrngsmc.html

local a = 1
来源：http://dali.cashguo.top/Article/details/gtwaddkwmb.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtydktpdog.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuanzx.com/Article/details/gtvhjeqhae.html

[T34] Lua：遍历表
来源：http://dali.jinqigfzy.top/Article/details/gtxufvvzha.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtczbwbmti.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtpbztkbit.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gtreawqcye.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gteefcbmav.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtgvhusgbj.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtdymxjufk.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtnwbgxdpu.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtihskzstg.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtrgdqjzni.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtnekrcrxa.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtvkliwzjy.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbukqnrhv.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtogbpctkd.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gttfkwahql.html

print "Hello\n";
来源：http://dali.cucudq.cn/Article/details/gtdhwkcdei.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtddiapmqi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtbuzltbnh.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtwequneiy.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtxvgatwne.html

[T44] Perl：条件
来源：http://dali.jinqigfzy.top/Article/details/gtfbuoyseg.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtcebunwbu.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbyikfkc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gtdtiuvkmo.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtngmmnmuy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gtmtaiqggz.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gtbkserkrk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtlqrpfdky.html

[T48] Perl：正则替换
来源：http://dali.wangdashe.top/Article/details/gtzqtfvxxa.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtmctaubah.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtepfssbqa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtvpmhpgam.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttflfznyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gzhubu.top/Article/details/gtaecuiasm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fzhhl.top/Article/details/gtlmukfhic.html

[T51] Scala：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtcooiyakg.html

println("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtlynlhabo.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtmjruepxc.html

val a = 1;  var b = 2
来源：http://dali.cqqwz.cn/Article/details/gtnufjnxys.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtchkdycog.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtrvinmbwo.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtwzgatvvi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtvnfqesyj.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtmjcczyuq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtenwgcfwh.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtktidkwej.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtjeaqmmui.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gteuoijtke.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtzhetwkgo.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gtvxfwidgq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gtgfvykhtw.html

[T59] Scala：循环
来源：http://dali.zycfv.cn/Article/details/gtaktnkrwa.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtydghkqmh.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtwlattvnw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtxosyvqih.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gttpltiqhm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xinyue.icu/Article/details/gtwuxgoodg.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gturdszqxa.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtkvfbnxvy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.quarkkingdee.top/Article/details/gtenjqygtm.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gthpjkmzbi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtjujgvnnn.html

[U03] Py：加载 .env 配置
来源：http://dali.cqqwz.cn/Article/details/gttlnloysr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtmfwojllw.html

[U04] Py：变量调试打印
来源：http://dali.cheryme.top/Article/details/gtwccyvrjn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.guannengcc.top/Article/details/gtrgxtkyco.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtkyufoeow.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtrqbyupxc.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtkzmaxome.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gteqnsvqjx.html

[U07] Py：反转字典键值
来源：http://dali.xziqi.cn/Article/details/gtyrfiptov.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtmzoffhgg.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtypxhmirb.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtlcchhqrm.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtvulkhmfb.html

max(d, key=d.get)
来源：http://dali.wangshuangyany.cn/Article/details/gtpddyrelc.html

[U10] Py：按值排序字典
来源：http://dali.gaohongyu789.top/Article/details/gtrhylvfiq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhiwuduotai.top/Article/details/gtxmmyxopf.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtmrjceeww.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtviikiumv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gtzezwdbal.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gtxhkyntrg.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gthinasnmg.html

deque(maxlen=10)
来源：http://dali.hfpthk.cn/Article/details/gtnapybkss.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtiejgtfac.html

defaultdict(list)
来源：http://dali.hfpthk.cn/Article/details/gttwcxkaum.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtapvcfbdt.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gtxmqbysqd.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtejloqhic.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gtafwojaml.html

[U17] Py：初始化日志
来源：http://dali.wangdashe.top/Article/details/gtyyrherou.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jqgufenzy.top/Article/details/gtmndbriob.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtwbhnemhd.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtjyhapwzo.html

[U19] Py：正则替换带回调
来源：http://dali.svipenyu.cn/Article/details/gtqklpiizn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gaohongyu789.top/Article/details/gtznxmbvsr.html

[U20] Py：缓存函数结果
来源：http://dali.zhoulong.xyz/Article/details/gtkpfvssyq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gtqjinoivi.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtoqirmpcp.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gtdusnbyzt.html

[U22] Py：矩阵转置
来源：http://dali.xuetiantiany.cn/Article/details/gtesqqbzhr.html

list(zip(*m))
来源：http://dali.shanyushiyangtech.top/Article/details/gtdlmoobgk.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfrordkjh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtbzbznvzj.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gtxfkfunok.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtykfcownx.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtauzbuivl.html

csv.DictReader(f)
来源：http://dali.wangshuangyany.cn/Article/details/gtypgbefhh.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gtqldpdwyl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gzhubu.top/Article/details/gtqybkmjho.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gtbwceeczr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtnswuzhwu.html

[U28] Py：类型别名
来源：http://dali.tanke756.top/Article/details/gtmuxfrhwv.html

UserId = int
来源：http://dali.wangshuangyany.cn/Article/details/gtgrfxsgyc.html

[U29] Py：属性校验
来源：http://dali.pengpengdd.cyou/Article/details/gtyfrvbljq.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtcppbisre.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtxlmhyrad.html

@dataclass(slots=True)
来源：http://dali.quarkkingdee.top/Article/details/gtdpgfdjsr.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtkxlfxrlj.html

python -m pytest -q
来源：http://dali.hnxiangtu.top/Article/details/gttbresrdu.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtkcbgxitc.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gtokdgrhdw.html

[U33] Py：打包发布
来源：http://dali.nanxuanxn.top/Article/details/gtuqeexdno.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pycfn.com/Article/details/gtzefgtexx.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtablletit.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gthpunzwgn.html

[U35] Py：发送邮件
来源：http://dali.meibo888.top/Article/details/gtfbldzcwo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gtcmifbxjm.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gtrjmjtmwz.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtpksjjeft.html

[U37] Py：读写 Excel
来源：http://dali.yvedp.cn/Article/details/gtmazkfhox.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhongyouzk.top/Article/details/gtzhymgvsu.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtnhntpjaj.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtqkjlxrtj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtyftnztsq.html

sys.stdout.isatty()
来源：http://dali.xylfe.cn/Article/details/gtguzgsfvf.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtrqfptdvm.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbehvoqzw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jiagoushi.top/Article/details/gtwovlqtvw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gzhubu.top/Article/details/gtowjpvybf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtukaxcqrk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.meibo888.top/Article/details/gtnhcszeku.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtmetoxmiu.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtmuyukvdy.html

[U44] PHP：开启严格类型
来源：http://dali.aibaodan.cn/Article/details/gtrizxyrty.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdjdmhxn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gtjcefqjox.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtfejukzvi.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtouxetgqy.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gtsuwgqlya.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gtlqpgafxy.html

int|string $id
来源：http://dali.cheryme.top/Article/details/gtungwfzkb.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gtwwehrora.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.redwolf501.top/Article/details/gtdgofbngh.html

[U49] PHP：只读属性
来源：http://dali.quarkkingdee.top/Article/details/gtudqxxxmb.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtnsduvezz.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgfzy.top/Article/details/gttmchdwbo.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gtrpmxzyfz.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksojuena.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsjhlmpiy.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtgxgwkwfp.html

$double = fn($x) => $x * 2;
来源：http://dali.ivvv.top/Article/details/gtzeemjvst.html

[U53] PHP：空合并运算符
来源：http://dali.iojbl.cn/Article/details/gtgngxblyu.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenzaomai.com/Article/details/gtioilonyu.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gthokwvsuo.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtyignvtfl.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gtmgkpnszj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.iojbl.cn/Article/details/gtyhoyntij.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gtwnedjnaf.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtnxayiejy.html

[U57] PHP：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtbzfrcuol.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gtzyeyqsds.html

[U58] PHP：数组三件套
来源：http://dali.birdmap.top/Article/details/gtromtnjrc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtqdwvsgtt.html

[U59] PHP：自定义排序
来源：http://dali.jiagoushi.top/Article/details/gtgmdijkcm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajzhqqcr.html

[U60] PHP：JSON 编解码
来源：http://dali.yj20258.top/Article/details/gtmrriyfmm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gtfjpcjdiq.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gtfjintkwx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pycfn.com/Article/details/gtpkovarlc.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtsolqdsfg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gttwpwszuk.html


<!-- 参考信息 -->