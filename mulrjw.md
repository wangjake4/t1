代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.fengsongda.top/Article/details/gtcpsulxnu.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtaszelmfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258888.top/Article/details/gtkmsdxpxt.html

[S50] C++：格式化数字
来源：http://dali.yuxming.cn/Article/details/gtmeafjxng.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xziqi.cn/Article/details/gttpjfxzat.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtozzfltvy.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibszklnw.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtzogalgpl.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gtoptlyczs.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtnmaayrih.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtdupkqoua.html

[S54] C++：异常处理
来源：http://dali.jqgufenzy.top/Article/details/gtnwmnuoeq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtrtpegfvd.html

[S55] C++：结构化绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifzdpnkr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtklonkilp.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtdpvtcqyk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtgladfhgy.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtnnyxvazl.html

constexpr int N = 10;
来源：http://dali.hongshengwenyu.top/Article/details/gtlostrkqp.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtiemwwhjv.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwujsyrip.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtuyigwzbh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtsrsjchkx.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtgjauteym.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtuslpiegt.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtcnzzezcu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtvbhwrhhd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtbrigieca.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gttzfhnccf.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtttrjuwbb.html

[T02] Kotlin：变量
来源：http://dali.zhongyouzk.top/Article/details/gtrplgwadx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhengqikj.top/Article/details/gtsonioiyx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqlxreby.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gtugaqnind.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtrppnwwuc.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gtxtttdbhf.html

[T05] Kotlin：when 表达式
来源：http://dali.cqqwz.cn/Article/details/gtkvspdwrp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gthcqqkbgk.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtlotvfcav.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwmfgmai.html

[T07] Kotlin：集合过滤
来源：http://dali.svipenyu.cn/Article/details/gtervuryti.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtyrjbkhlt.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gttntqhbnm.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtkmaucabq.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtqbdvchco.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtbrjqmqvy.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gttnxgggku.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtaxnwstrh.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtvppavdlt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtwzmgotaa.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtgqiotrza.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwlpsvhd.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtajxrjfox.html

val m = mapOf("a" to 1)
来源：http://dali.birdmap.top/Article/details/gtnilouava.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtwhiwirrh.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtqbqqatsw.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtxmgfamun.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gtalmsqobi.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdofkqbhg.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtooizjybu.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtfnysibyu.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvavsgds.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtlhlhqisw.html

"值: \(b)"
来源：http://dali.andypj.xyz/Article/details/gthukazxpm.html

[T19] Swift：可选绑定
来源：http://dali.wangdashe.top/Article/details/gtqzebanby.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtjhlmsoqk.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gthfdjhvmz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtzaqptlhn.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtdhwlrvep.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtuepsyitr.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gturemkkvf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtnfhljcxt.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcizjcwe.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtashwvnhq.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtulhuyjfn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtyfjzuiqd.html

[T25] Swift：结构体
来源：http://dali.guannengcc.top/Article/details/gtnngwkywz.html

struct P { var x: Int }
来源：http://dali.mhx1999.top/Article/details/gtchrhjvro.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtpvbmhdst.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfmocewj.html

[T27] Swift：错误处理
来源：http://dali.zhixingplan.top/Article/details/gtvoraqoxa.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gttnhdeaqr.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtpnlbmofd.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gtokpndkfy.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtycksrrds.html

guard let x = opt else { return }
来源：http://dali.c1oappe.top/Article/details/gtcjechvsz.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gtkncuqgiz.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtnxvypzgj.html

[T31] Lua：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhncxfde.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtrhljvwgj.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gtylllkfsi.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gtrqrkmxcy.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtapoauzgz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtiquxurkg.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtzjqprmdt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtktwaaesq.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtbpcltwib.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ppjwa.cn/Article/details/gtynafzidu.html

[T36] Lua：函数
来源：http://dali.kuanghao11.cn/Article/details/gtogxcvnzw.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtevxmhiix.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gttqevcwxm.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gtrnhktxoq.html

[T38] Lua：条件
来源：http://dali.cqqwz.cn/Article/details/gtezjvodbi.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gtbzfnwkmi.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtxagaagla.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtfwabbwkl.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtfhbqdzgb.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtzuhhcour.html

[T41] Perl：Hello World
来源：http://dali.0kj1m.cn/Article/details/gthfyyjrgy.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtywvwakon.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtomyjgnpo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtasxlkzas.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtsiutxslv.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtlmrotume.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtjjjnqvbb.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtplydwayt.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gthdnsmnyf.html

for my $x (@arr) { print $x; }
来源：http://dali.chenzaomai.com/Article/details/gtwbcolipp.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtajlqjlea.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtapjmdsfv.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gtebnrcoel.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtisbkunmp.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtuvnloaet.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtpuhdudvc.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gttkoplzzz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ydzc1.top/Article/details/gtzswmjqpg.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gttretrrfe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gttmzzukmn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtxivuzigf.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtlatbpsua.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gtjhzrxzyr.html

[T52] Scala：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmhkobbp.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtjdlxwikx.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtakzbkjgl.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtsizzwvff.html

[T54] Scala：集合映射
来源：http://dali.hammf.cn/Article/details/gtgfrfqrki.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtrmldrulz.html

[T55] Scala：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtjnpbgfzg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtyxxdydbt.html

[T56] Scala：样例类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtullcgczz.html

case class User(name: String, age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtkwddbddz.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gtlqjpitsu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtyabnigpa.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtpctajaak.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtaxqlkchs.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gtkowlkjcx.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtiwjqdyvf.html

[T60] Scala：折叠
来源：http://dali.ivvv.top/Article/details/gtqjlfrzjb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtuqmckxrx.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvkdzkfjd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gtufowoszs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtclctzjci.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtpvggahtk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtvzdlbtvc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtsohxnzdo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtjxhbhlai.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gtnkxsxckh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtpdcsjbeh.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gtmjtpizzl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtnalckdow.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gtnqutciiz.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtkjbfvxbc.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtgeahsymg.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtmmpmhzsd.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtytdvqozs.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtpltsqmop.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gtqlohuwyn.html

[y for x in nested for y in x]
来源：http://dali.zhiwuduotai.top/Article/details/gtfbkoqqww.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gttbcwrqjw.html

max(d, key=d.get)
来源：http://dali.tian-w.cn/Article/details/gtanatmtyi.html

[U10] Py：按值排序字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhtwvpwu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yvedp.cn/Article/details/gtdkqfextj.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtwarjybec.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtzttodjvt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtifesxfsk.html

Counter(arr).most_common(3)
来源：http://dali.pengpengdd.cyou/Article/details/gtxcbqixvg.html

[U13] Py：固定长度队列
来源：http://dali.xinyue.icu/Article/details/gtptiadtez.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gttofnduoz.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtxqbxepwu.html

defaultdict(list)
来源：http://dali.zhengqikj.top/Article/details/gtzkretevk.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtypofzixo.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtooteeeog.html

[U16] Py：命令行参数解析
来源：http://dali.zhongyouzk.top/Article/details/gttjfavvnm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuanzx.com/Article/details/gtlwokysbd.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtjmriuero.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gtfywynbne.html

[U18] Py：预编译正则
来源：http://dali.snrcjt.cn/Article/details/gtgvsmzpfe.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gthrcgdtuh.html

[U19] Py：正则替换带回调
来源：http://dali.fengsongda.top/Article/details/gtlueloqds.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtrxjdlshv.html

[U20] Py：缓存函数结果
来源：http://dali.snrcjt.cn/Article/details/gtvdzontxs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gtaqaowgem.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gtcnjlvski.html

@contextlib.contextmanager
来源：http://dali.hnxiangtu.top/Article/details/gtbvreqbdw.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtttcbvgmf.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtlzbiqzqi.html

[U23] Py：分块读取大文件
来源：http://dali.tian-w.cn/Article/details/gtvutjrcvw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtuzotfone.html

[U24] Py：路径操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkhjdxaic.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhongyouzk.top/Article/details/gtyhhqwhnw.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtpjryiyuj.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtlbweovcr.html

[U26] Py：并发下载
来源：http://dali.cqqwz.cn/Article/details/gtpepswmui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hnxiangtu.top/Article/details/gtangrzoky.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gtlcidpqfu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.iojbl.cn/Article/details/gtnelchnmy.html

[U28] Py：类型别名
来源：http://dali.cashguo.top/Article/details/gtdoorzykw.html

UserId = int
来源：http://dali.hongshengwenyu.top/Article/details/gtwtcdijmj.html

[U29] Py：属性校验
来源：http://dali.yuanzhike.top/Article/details/gtssnpqkab.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtnsjktcoj.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gtmyckigae.html

@dataclass(slots=True)
来源：http://dali.hnxiangtu.top/Article/details/gtoyrcutwh.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gtroomnxzz.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtkerdpkau.html

[U32] Py：代码格式化
来源：http://dali.zycfv.cn/Article/details/gtniquafra.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtovhahgqu.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gtyoqejwxd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhiwuduotai.top/Article/details/gtxcchofze.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtwmgiohzd.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtmlbmmrqa.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gttcqfuryv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.wangshuangyany.cn/Article/details/gtttoqbsxn.html

[U36] Py：定时任务
来源：http://dali.andypj.xyz/Article/details/gtsemaybzr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jyoumei.cn/Article/details/gtavlajeae.html

[U37] Py：读写 Excel
来源：http://dali.tianlin.xyz/Article/details/gtiwxlbqco.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gtovnkgxno.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtirmbbtoy.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gttzbskxev.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtjwjujwjm.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihygolaw.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtlvqnqdcz.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gtnfgdkyyf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gtklcwrnlk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gtdhqotott.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj20258888.top/Article/details/gtrpuwtehf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtxbuknxcg.html

[U43] PHP：声明命名空间
来源：http://dali.smart0.xyz/Article/details/gtarnrifsq.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtejtbpdyy.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gthknjrxyj.html

declare(strict_types=1);
来源：http://dali.mhx1999.top/Article/details/gtsrhiyhjl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hnxiangtu.top/Article/details/gtxcveulcm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gteuacmosb.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtttffawkq.html

?string $name = null
来源：http://dali.zhixingplan.top/Article/details/gtepbdqeix.html

[U47] PHP：联合类型
来源：http://dali.jqgfzy.top/Article/details/gtdikzefmk.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gtdawivykn.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtwyhwxlbr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cucudq.cn/Article/details/gtiszhdazx.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gtgdqnvyfq.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyykokltv.html

[U50] PHP：构造器属性提升
来源：http://dali.yangfankeji.com/Article/details/gtdmhygnsm.html

public function __construct(private int $id) {}
来源：http://dali.ivvv.top/Article/details/gtkhpxdndm.html

[U51] PHP：数组解构
来源：http://dali.guowangkeji.top/Article/details/gtuisegala.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gtlnewsczp.html

[U52] PHP：箭头函数
来源：http://dali.yueranfly.top/Article/details/gtiwwaxbys.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtopqkjzcw.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtkhctkcva.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgzwrbpu.html

[U54] PHP：空安全调用
来源：http://dali.xuetiantiany.cn/Article/details/gturdmhcpm.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtkicobmei.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gtbfowomxz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtccggtrtn.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gtduilbxrc.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtrdudcfwf.html

[U57] PHP：字符串插值
来源：http://dali.316326.xyz/Article/details/gtqmorxgfa.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtmactgkrl.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gtoweessle.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtpusizlrc.html

[U59] PHP：自定义排序
来源：http://dali.hysaishi.cn/Article/details/gtefjoolcx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gtcsawxbvc.html

[U60] PHP：JSON 编解码
来源：http://dali.quarkkingdee.top/Article/details/gttgqmwprb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gttvpeholp.html

[U61] PHP：正则
来源：http://dali.zdqjudy.top/Article/details/gtrdsaqmer.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtckaoxvek.html

[U62] PHP：日期对象
来源：http://dali.xuanzx.com/Article/details/gtrqldvxgq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gtjmcvutpx.html

[U63] PHP：文件读写
来源：http://dali.sufxvd.cn/Article/details/gticeccjhq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gtdsxxjnrd.html

[U64] PHP：目录遍历
来源：http://dali.hammf.cn/Article/details/gterzfbvmt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtdcnbtzho.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtiepockjg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtzxkghiri.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gtmusjhuwj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtsysvsevr.html

[U67] PHP：处理文件上传
来源：http://dali.daxiang520.top/Article/details/gttkzyooaf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gteomngojo.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtkfbukbvp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtzmjprsqi.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gtipgpjqay.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.redwolf501.top/Article/details/gtrdplmrdj.html

[U70] PHP：PDO 事务
来源：http://dali.shangyingyoupin.top/Article/details/gtuqapwvbu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyykckql.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gtopwvyfts.html

throw new RuntimeException("失败", 500);
来源：http://dali.c1oappe.top/Article/details/gthobklbho.html

[U72] PHP：写错误日志
来源：http://dali.ivvv.top/Article/details/gtkjwnwjec.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gtyjsncksl.html

[U73] PHP：读取 ini 配置
来源：http://dali.jiagoushi.top/Article/details/gtbunyctvg.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtaqsqwcpw.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgogdsksa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ppjwa.cn/Article/details/gtajksrddg.html


<!-- 参考信息 -->