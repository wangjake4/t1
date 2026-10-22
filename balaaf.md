代发 wailian999

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtzwaophvz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.snrcjt.cn/Article/details/gtlccnyhva.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtvnydnedy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtcxvnzgsd.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtgxticait.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtkriahccg.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtzfughypf.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gthplhhzqu.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtufmygcwv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtjmkialup.html

[S44] C++：引用传参
来源：http://dali.dianchejie.cn/Article/details/gtqmtrgamd.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtchkmznce.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtrezftajp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtfuyulqmb.html

[S46] C++：函数模板
来源：http://dali.shuidangran.top/Article/details/gtzvbwbqrh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtcuiviicp.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtekvopkvq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtjgrgpzhe.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gthgifybju.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gthpgmzzcl.html

while (std::getline(in, line)) { }
来源：http://dali.birdmap.top/Article/details/gtjegxydqj.html

[S49] C++：写文件
来源：http://dali.hnqzz.top/Article/details/gtgbrdskia.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hammf.cn/Article/details/gtbywuliax.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtiaeimjen.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtsehljdow.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gtnctawsea.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gteuuqylli.html

[S52] C++：const 与 noexcept
来源：http://dali.gotoacloud.top/Article/details/gtblaqtarb.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtgikcwkfw.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtamwlfidt.html

std::vector<int> w = std::move(v);
来源：http://dali.gaohongyu789.top/Article/details/gtazapfvnr.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gtxmjjuizi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtwkcvbbqv.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvkzpvht.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nwbrower.top/Article/details/gtuyadrvgb.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtwvmgovhi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtoyvaegfd.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gtggvfifem.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtsccjrswq.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtioultgda.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gtftmztdjj.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtktpwexfy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.bjfxy.top/Article/details/gtspqxgzig.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtavntwowi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtxexadtvm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkxhnoldy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnqzz.top/Article/details/gtwmljztnd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvgojxux.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtlqpjaofc.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtncuikiuw.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtegbgwntv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gtefczlofu.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtwuwgzyew.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtzsvfmnyh.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtcsxvwmfh.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxnpetgve.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtnnqofinq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtinlhaedf.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtrhirgxca.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtpmfambuo.html

[T07] Kotlin：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtiabyazmh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtiqgfyqrf.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gtsglwxosp.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtjgkroswq.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtdznwqdfp.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtdujmpwhl.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtswrhomoh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.0kj1m.cn/Article/details/gtzivcfotn.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gteygokmen.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gtwjdhmsxj.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtisxwckwb.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtjshkwxjm.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtublyedvz.html

val m = mapOf("a" to 1)
来源：http://dali.gotoacloud.top/Article/details/gtgikbtkib.html

[T14] Kotlin：循环
来源：http://dali.yangfankeji.com/Article/details/gtjayoxozq.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtylgxyxph.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtaglsjsdy.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtownelmzz.html

[T16] Swift：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsxxgxatn.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtksijfbtm.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtphlvelfy.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtiysdrbkv.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gtamddbiwh.html

"值: \(b)"
来源：http://dali.hywenlv.cn/Article/details/gtrmpqvkrc.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtreqytpiw.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtdfstblms.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gtmixydnff.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtjpdtkfmm.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gttipbylqu.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gtiquxgzaz.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtefnnhato.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtqenlcbrk.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtirqlhrpu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtmhtaisat.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtjuendyys.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtszbsxrml.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtelbwsogj.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gteicxkqbz.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkuvvuon.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gthidslwbg.html

[T27] Swift：错误处理
来源：http://dali.zdqjudy.top/Article/details/gtorgbgloa.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtuomeqqrh.html

[T28] Swift：枚举
来源：http://dali.snrcjt.cn/Article/details/gtsmorfbcz.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqjsqhze.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gthlyatbar.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtsshifxff.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtsuimppey.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtsojwuvry.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtxcurdytd.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtyoydxdom.html

[T32] Lua：局部变量
来源：http://dali.sufxvd.cn/Article/details/gtvddquztf.html

local a = 1
来源：http://dali.yonumen.top/Article/details/gtmozjqmly.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbriksid.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gtywqbunhh.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtmzusscng.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtuegmdwoa.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gtqbdgdiuc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gttouweorf.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gteybqpplh.html

function add(a, b) return a + b end
来源：http://dali.xinyue.icu/Article/details/gtgqohmzrs.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtgigktnph.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gtawotwltm.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtfetkmjth.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gthglzlzvs.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtzemeohca.html

string.find(s, "%d+")
来源：http://dali.aibaodan.cn/Article/details/gtlxoqayhi.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtmeyelktl.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gthsgattci.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtbchimscg.html

print "Hello\n";
来源：http://dali.dianchejie.cn/Article/details/gtvtbdwnds.html

[T42] Perl：变量类型
来源：http://dali.guowangkeji.top/Article/details/gtcrndmihg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtfgjjnkiq.html

[T43] Perl：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtmsuhwhdj.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gtbqklswrb.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gtddogjbth.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtjjostgvh.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmnpkiebq.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtqowoprjd.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtemaxwoeg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtwqvqugte.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gthrjtmfgi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pycfn.com/Article/details/gtaxjmcycq.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtmzxinqij.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtoqypryss.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgllceoxt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtlsxwexso.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtwqflhpxy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtsdzvnvni.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtmrglnzsq.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtvluxlutf.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgogoudvf.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtnfionyge.html

val a = 1;  var b = 2
来源：http://dali.chenzaomai.com/Article/details/gtckcehrjs.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtvsudysnn.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtpdeywmzd.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtibdtdwpm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtxgctkuhw.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtxpxtvbdf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtglkymmyg.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtyrrhtlwx.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gtvkegwkjf.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtfbijbvbz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtsogrtasb.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gtojvzfpfx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gtdzvaygaj.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtuvkpvaki.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gtagstzijz.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtkjplnafg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gtzcmupbhw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtvclnjkpr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gotoacloud.top/Article/details/gtzijolrki.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtizeacggy.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtrqfwzrin.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtrardlwuf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtxzmfmeat.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gtkzldybma.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gtowkjdnbl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgfkalnny.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtqpdnsfhm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gtgextjszk.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtyhqfuejb.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gtuxyxejzi.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtdtnpdpxt.html

{**a, **b}
来源：http://dali.jinqigufen.top/Article/details/gttblxalfy.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtaifaxlal.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtubjeuvty.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gtimrkaknb.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gtsgcvvkhm.html

[U09] Py：字典取最大值的键
来源：http://dali.iojbl.cn/Article/details/gtgkkmpvmm.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gtbgjynzje.html

[U10] Py：按值排序字典
来源：http://dali.nanxinkj.top/Article/details/gtqxthootl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dashuyun.cn/Article/details/gtaijdglan.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtuiyurums.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtsejeqkmv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gteqqjbukn.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gtsuzjcref.html

[U13] Py：固定长度队列
来源：http://dali.zhiwuduotai.top/Article/details/gtbeejugxu.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gtkxdnbfcd.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gtdmzpromp.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtkxpuibvp.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtfvipbmgt.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtowapdvtq.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gtrnlqrjiu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cashguo.top/Article/details/gtddeozebk.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gtfmbpokts.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gtilyadsbe.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gttcskuzjc.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtqrkopibx.html

[U19] Py：正则替换带回调
来源：http://dali.9152youxi.cn/Article/details/gtotyjbstw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gtfglkpucj.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtgkxhepnk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtkeewigzg.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtrjckarix.html

@contextlib.contextmanager
来源：http://dali.nanxuanxn.top/Article/details/gttiuxxncx.html

[U22] Py：矩阵转置
来源：http://dali.jiagoushi.top/Article/details/gtmeflsmom.html

list(zip(*m))
来源：http://dali.cashguo.top/Article/details/gteepulmtt.html

[U23] Py：分块读取大文件
来源：http://dali.cashguo.top/Article/details/gtehhecnbh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtmdbfjhny.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gtyhllcifn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmaglsdzd.html

[U25] Py：CSV 按字典读
来源：http://dali.kuanghao11.cn/Article/details/gtiipuojhg.html

csv.DictReader(f)
来源：http://dali.hongshengwenyu.top/Article/details/gtjawclkjp.html

[U26] Py：并发下载
来源：http://dali.gotoacloud.top/Article/details/gtcyfyieeq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtovbintdl.html

[U27] Py：异步 HTTP
来源：http://dali.yvedp.cn/Article/details/gtubypormu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jqgfzy.top/Article/details/gtnixoizrf.html

[U28] Py：类型别名
来源：http://dali.kuanghao11.cn/Article/details/gthcnrtijc.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtsuqtfhqm.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtsfxlxkfx.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gtmclbipjd.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtbpbguucj.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gthklzsjbi.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtwncbxnyj.html

python -m pytest -q
来源：http://dali.yj20258888.top/Article/details/gtjlmiigar.html

[U32] Py：代码格式化
来源：http://dali.tianlin.xyz/Article/details/gtnxxsrpqu.html

ruff format . && ruff check --fix .
来源：http://dali.aibaodan.cn/Article/details/gtsvuextwy.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtaxgqztcp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258888.top/Article/details/gtyzelwekf.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtntkatieh.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gtjhuxqqdh.html

[U35] Py：发送邮件
来源：http://dali.tian-w.cn/Article/details/gtrdqaenjm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yongpay.top/Article/details/gtytzqidyx.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gtgqvqjyby.html

schedule.every(10).minutes.do(job)
来源：http://dali.hywenlv.cn/Article/details/gtniflgywv.html

[U37] Py：读写 Excel
来源：http://dali.hammf.cn/Article/details/gtqymicqqp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gtjrmrwqpe.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gtnjgosips.html

Path(__file__).resolve().parent
来源：http://dali.shangyingyoupin.top/Article/details/gtnrawlxfb.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtgyetzzwe.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gtrnwxgnlo.html

[U40] Py：打印到标准错误
来源：http://dali.sysykeji.top/Article/details/gtnrqpuvyc.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtrpxazdis.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhijiandao.cn/Article/details/gtvmfzsrmd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yueranfly.top/Article/details/gtjfelubbz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtznjnizbq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yonumen.top/Article/details/gtingtqbgw.html

[U43] PHP：声明命名空间
来源：http://dali.yongpay.top/Article/details/gtlkzamliw.html

namespace App\Http;
来源：http://dali.jyoumei.cn/Article/details/gtneafsabc.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtxlltjcpf.html

declare(strict_types=1);
来源：http://dali.pengpengdd.cyou/Article/details/gtfvkejykp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gtmczgydgv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gturoxdhtp.html

[U46] PHP：可空类型
来源：http://dali.havefunace.top/Article/details/gtmczprvbz.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gtmhjkxvpq.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbsgqkbz.html

int|string $id
来源：http://dali.fengsongda.top/Article/details/gtnptvwciw.html

[U48] PHP：纯枚举
来源：http://dali.nanxuanxn.top/Article/details/gthcrgsmxg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gtobtjqnkk.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrzmvrwe.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtixdtapvy.html

[U50] PHP：构造器属性提升
来源：http://dali.jyoumei.cn/Article/details/gtqhmpsmnh.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gtrbcfwjzl.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtboqauuhj.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gttlnzygkj.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gtfrdhxqis.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtbfyrgvjq.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gtdasraads.html

$v = $a ?? $b ?? "default";
来源：http://dali.guannengcc.top/Article/details/gtwiidrxch.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gtiqzeurad.html

$obj?->method()
来源：http://dali.feifeiyinyue.top/Article/details/gttwqrxzuj.html

[U55] PHP：match 表达式
来源：http://dali.nanxuanxn.top/Article/details/gttjuslvwv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gtfmywtvst.html

[U56] PHP：命名参数
来源：http://dali.ydzc1.top/Article/details/gtcpoaicxr.html

f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtlzcmyjwh.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtgaaskjns.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gtifqgknwm.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gtwjldlyis.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtyhrazasn.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtuqdhlpos.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhengqikj.top/Article/details/gtnowbvbqm.html

[U60] PHP：JSON 编解码
来源：http://dali.ybcxt.top/Article/details/gtressloow.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtguyskapm.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtienzmpmk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtczpyngrz.html

[U62] PHP：日期对象
来源：http://dali.xziqi.cn/Article/details/gtoesbamwf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtibatidtm.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtnuwnddgg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaheuuum.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtrzzrrwja.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gotoacloud.top/Article/details/gtlcjxihfq.html


<!-- 参考信息 -->