代发 wailian999

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtuxwlhaag.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtruvsfooj.html

[S44] C++：引用传参
来源：http://dali.iojbl.cn/Article/details/gtnljnagtt.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtzhaemtgg.html

[S45] C++：lambda
来源：http://dali.redwolf501.top/Article/details/gtdaeetisg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtsyqzwxif.html

[S46] C++：函数模板
来源：http://dali.jqgfzy.top/Article/details/gtdizivteb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtzmuzphse.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtxdxvfdpi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gthyrktkpi.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtudtvgqzt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gtxcimmcvp.html

while (std::getline(in, line)) { }
来源：http://dali.cdnleiting.top/Article/details/gtumuxldql.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfoncstb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.svipenyu.cn/Article/details/gtrammxjay.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtkdujygfl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtvnlrcprd.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtridtrlfb.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtdklwelbg.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtgphjbimb.html

int size() const noexcept { return n_; }
来源：http://dali.tianlin.xyz/Article/details/gtxndxgttt.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtegbrtapf.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtojldksir.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtgxlenbzs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtytytkkyp.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwmvinnr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtvsepgufm.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gtbypolexo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtyfqkcjkr.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtvnlclpbe.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtwpyorpvo.html

[S58] C++：命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gttfhghfqf.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtanozlvns.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtjhjqimha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtkuzxiniu.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtonuxxnww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtlqbuarmp.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjyvmuhkz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtldisrwus.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtdzrfidge.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtvcvdmuxc.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtpevcdzsn.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtvyeyezcl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtbhuhgbpj.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtswirahvr.html

"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtqxpktnrx.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gttllxsmnz.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtfaxwbacb.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtltbshvau.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.aizwys.cn/Article/details/gtoaagkrir.html

[T06] Kotlin：集合映射
来源：http://dali.xinyue.icu/Article/details/gtjrgcewvd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aizwys.cn/Article/details/gtkobbxvbd.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtnnjftnei.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtdyhnrger.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtdekogmmz.html

data class User(val name: String, val age: Int)
来源：http://dali.sufxvd.cn/Article/details/gtdjjblwkn.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtkhpimaah.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtttykqxmu.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenqwpvgz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtimfvdkxk.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gtxwwsrlnv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtqrfxpzam.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtzorgdvzz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtqyiivzah.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtopygseem.html

val m = mapOf("a" to 1)
来源：http://dali.hfpthk.cn/Article/details/gttyaitgsd.html

[T14] Kotlin：循环
来源：http://dali.yj202588.top/Article/details/gtqxlxgitg.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtuonovrfa.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtgascwhae.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtiueifnxe.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtqbyqeghd.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gthudddgyw.html

[T17] Swift：变量与常量
来源：http://dali.yj20258888.top/Article/details/gtbdvmqnpu.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gtbukflrul.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtzkvqrzjk.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtlewewaav.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtxpaphpet.html

if let n = opt { print(n) }
来源：http://dali.guannengcc.top/Article/details/gtsrblbiwo.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwzynptw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtpithyfqx.html

[T21] Swift：遍历
来源：http://dali.sufxvd.cn/Article/details/gtlsdphfuh.html

for x in a { print(x) }
来源：http://dali.zhixingplan.top/Article/details/gtwyynwzry.html

[T22] Swift：字典
来源：http://dali.tian-w.cn/Article/details/gtlqkccksj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtqrkjnbgs.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtidtxofxs.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gtoctqubvn.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtxjvvddoi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtyexzhznm.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gthcblohgp.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gttlkggzxn.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtzdsalcwq.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtenekqtvt.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtibzovxvm.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtxwqlkvht.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gthspoyxdj.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtqvzdhpwx.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gtzgyiliwr.html

guard let x = opt else { return }
来源：http://dali.iojbl.cn/Article/details/gtygobbjii.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtulnydwvp.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gttuwdruax.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtdehiqvkr.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtnbxuzzuv.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtpdydagba.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtetrqhgii.html

[T33] Lua：表（数组）
来源：http://dali.nanxuanxn.top/Article/details/gtmzgdvvgk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtipqkysaf.html

[T34] Lua：遍历表
来源：http://dali.cdnleiting.top/Article/details/gtepmhljta.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gtifbmnydl.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtzmldudlt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtftzkpoju.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gthfsbuyfs.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gtruciwvmy.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtrykygmku.html

"a" .. "b"
来源：http://dali.nwbrower.top/Article/details/gtlhvjlmsb.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtpdcvtmng.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtdzevsbsd.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gteimltimi.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gtdpiarfrh.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtvsdsitwv.html

setmetatable({}, { __index = base })
来源：http://dali.cheryme.top/Article/details/gtubpqkhby.html

[T41] Perl：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtiiisuhug.html

print "Hello\n";
来源：http://dali.zdqjudy.top/Article/details/gtorbgsecs.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtkeblztow.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daxiang520.top/Article/details/gtjqkvbvmx.html

[T43] Perl：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtosorpobm.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtzqsgaxep.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gtvlyvioop.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gttclsjgfg.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtsjuuprnv.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gtmdldbdjn.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtctrcposa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gtggxllnkb.html

[T47] Perl：正则捕获
来源：http://dali.fengsongda.top/Article/details/gtwcuqtpvi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jiagoushi.top/Article/details/gtletvudwa.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtojzwfpzb.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtrhwxdldz.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gttmvqkigu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtzrbqvkun.html

[T50] Perl：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtwnmjcpaq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yanxiufei.cn/Article/details/gtjsvpyvtb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtcabvckuq.html

[T51] Scala：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtumtgqtkv.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtovxjeasf.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtxveuqsfw.html

val a = 1;  var b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtchkvvpzz.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtvnlnatrc.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gtbghmofoc.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtywhhmlkw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gthvsxluhi.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtkpwehqqn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangdashe.top/Article/details/gtbeuzsozx.html

[T56] Scala：样例类
来源：http://dali.snrcjt.cn/Article/details/gtrsmdkhat.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gtkeruesna.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtdtcawdma.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtyuyrammi.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gteznjtpyh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtzmotywqi.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcxkdsja.html

for (i <- 1 to 10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtmfgvedrl.html

[T60] Scala：折叠
来源：http://dali.shzxlz.cn/Article/details/gtumyxicyj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtendandkw.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtcjcqluqb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmoadyem.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtiqhjrxex.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtzgdtahnz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gtskkyrhzr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtpkpevcsf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gtqnbecois.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gtfkamoezr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ivvv.top/Article/details/gttwkpriyq.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtuzhltact.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtuatsjchv.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gtwxgoqoop.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtigsbzonb.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelwdknoi.html

{**a, **b}
来源：http://dali.hfpthk.cn/Article/details/gtmikrbanx.html

[U07] Py：反转字典键值
来源：http://dali.feifeiyinyue.top/Article/details/gteroivzmc.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtgotunmsq.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gtwbmwbbli.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gttmoknejz.html

[U09] Py：字典取最大值的键
来源：http://dali.kuanghao11.cn/Article/details/gtrgvrrpak.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtwkftikya.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtctmkprgc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtyzzynrzr.html

[U11] Py：生成器表达式
来源：http://dali.ehwqpu.com/Article/details/gtqxitbotn.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtajaivway.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gtpvtehdtq.html

Counter(arr).most_common(3)
来源：http://dali.wangdashe.top/Article/details/gtmjnxgozl.html

[U13] Py：固定长度队列
来源：http://dali.sweek.top/Article/details/gtqhpabwlr.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gtqymlyyck.html

[U14] Py：分组收集到列表
来源：http://dali.hysaishi.cn/Article/details/gtyowmrthx.html

defaultdict(list)
来源：http://dali.ivvv.top/Article/details/gtxfeqcbuf.html

[U15] Py：高精度计时
来源：http://dali.guannengcc.top/Article/details/gtugbtjqcp.html

t = time.perf_counter()
来源：http://dali.sxryk.cn/Article/details/gtyjytlegn.html

[U16] Py：命令行参数解析
来源：http://dali.shangyingyoupin.top/Article/details/gtcywncvgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gthfbypdds.html

[U17] Py：初始化日志
来源：http://dali.ppjwa.cn/Article/details/gtqfhaujkp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenzaomai.com/Article/details/gtbpycwfic.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gtkylrakbn.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gtcfnhfncm.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtvgnonrbd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xuetiantiany.cn/Article/details/gtuwunziiv.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtbdfgkolc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtkaonsarc.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gttobfmmql.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gttjzxyrlc.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtmjjqokck.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtsixkhssa.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtmyvzeoni.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.snrcjt.cn/Article/details/gtpwkbidfa.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtiftnjzrj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtawbonthz.html

[U25] Py：CSV 按字典读
来源：http://dali.guannengcc.top/Article/details/gthwjkxntm.html

csv.DictReader(f)
来源：http://dali.smart0.xyz/Article/details/gtgaslrnxl.html

[U26] Py：并发下载
来源：http://dali.jyoumei.cn/Article/details/gtdlnrkzvm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtbttrdgvl.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gtexapstdr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtwiutmhbn.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtxmuuxpjk.html

UserId = int
来源：http://dali.svipenyu.cn/Article/details/gtynpybjhk.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtpyrrzrko.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiujhdjco.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gttbuakufo.html

@dataclass(slots=True)
来源：http://dali.aibaodan.cn/Article/details/gtlioeetpb.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtkpiunaum.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtwjbknjpr.html

[U32] Py：代码格式化
来源：http://dali.xuanzx.com/Article/details/gtcpdjewuu.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtddtrvscu.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gtivnjutnw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nwbrower.top/Article/details/gtoyerammn.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gtwqptsrxz.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gtkobwikex.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtvvlomsfe.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gtlarzjavt.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gtshbzkgvv.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtzzqqbjdo.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtcrryuheh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cashguo.top/Article/details/gtjoinlfei.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtwwbpimnw.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtotjfcxyy.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gtjphppibv.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtxydainxw.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gtkysscsoe.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtzvhzzdea.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gteqrwbngl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtytbtyjbf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hongshengwenyu.top/Article/details/gtmujlqokd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtzleuhuxr.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtddaiqlhf.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gtgdkhwvcg.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtbprpwuyk.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gtrccpxgsi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gttapjehfm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtltpqedpk.html

[U46] PHP：可空类型
来源：http://dali.yj20258.top/Article/details/gtmgsoblqg.html

?string $name = null
来源：http://dali.yj20258888.top/Article/details/gtvwrldbtq.html

[U47] PHP：联合类型
来源：http://dali.fengsongda.top/Article/details/gthgqwcjku.html

int|string $id
来源：http://dali.sysykeji.top/Article/details/gtrenaqrys.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjqlhracu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlqnolvjn.html

[U49] PHP：只读属性
来源：http://dali.tanke756.top/Article/details/gtwnejnpsr.html

public readonly string $name
来源：http://dali.xinyue.icu/Article/details/gtffpdtmwd.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcqykkzm.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtsrxuhmab.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtotjzmixe.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gtrufnalbj.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gtcwhkkrcu.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gtgtyhxntp.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gtirirgiqf.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtexmbgkxo.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtmjmntsuk.html

$obj?->method()
来源：http://dali.kuanghao11.cn/Article/details/gtehmktlfo.html

[U55] PHP：match 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwlaadiwu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gtxustetzi.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtjofqzgky.html

f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtceuvyjhp.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtnwyhkgya.html

"值: {$a}"
来源：http://dali.xylfe.cn/Article/details/gtphbrbdin.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gtggbsvqsq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shzxlz.cn/Article/details/gtcnhbgrin.html

[U59] PHP：自定义排序
来源：http://dali.daria6918.cn/Article/details/gthuewveip.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtpdbwcxmf.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtjwgjmvth.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hywenlv.cn/Article/details/gtnmecusra.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gtcommqgjc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtcoadqqpj.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtbluxkzej.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gtywspjxtj.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gtiqlhjrym.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zdqjudy.top/Article/details/gtdfzqokje.html

[U64] PHP：目录遍历
来源：http://dali.tianlin.xyz/Article/details/gtlbrqoqqh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hfpthk.cn/Article/details/gtkjfzfscl.html

[U65] PHP：会话
来源：http://dali.yvedp.cn/Article/details/gtwefzegiu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtplnsemot.html

[U66] PHP：设置 Cookie
来源：http://dali.fengsongda.top/Article/details/gtjwztxehq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zycfv.cn/Article/details/gtdxecqlxp.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtjojnfuhb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangshuangyany.cn/Article/details/gtjuulpwhs.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtpkzlrwha.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gtusrgucuy.html


<!-- 参考信息 -->