代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.fzhhl.top/Article/details/gtnngssbcf.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgxitgjzh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtevvgetdk.html

[S50] C++：格式化数字
来源：http://dali.cucudq.cn/Article/details/gtpvsrsrms.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtkxqspups.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtyxwldklk.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gtffemdmge.html

[S52] C++：const 与 noexcept
来源：http://dali.shuidangran.top/Article/details/gtutbiahbh.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtookhitba.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtcxtwnghr.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtgptfxvio.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtsifdakal.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuetiantiany.cn/Article/details/gtiaoftdaq.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gtwmlgmapy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtnvniwivb.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gteraupuxa.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gtmnurfwpz.html

[S57] C++：编译期常量
来源：http://dali.feifeiyinyue.top/Article/details/gtfmuxdicx.html

constexpr int N = 10;
来源：http://dali.havefunace.top/Article/details/gtnesfyjct.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtaqasspiq.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gtoanveekh.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtxpmzrfyv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtmmzvztiy.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbiqtlioy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yongpay.top/Article/details/gtexozgzlf.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtdepvujop.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtwoiscxvt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttpibqgxk.html

[T01] Kotlin：Hello World
来源：http://dali.ydzc1.top/Article/details/gtkztbavrx.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtsuabxjyd.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gtuehwqpwe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtmxdhivop.html

[T03] Kotlin：字符串模板
来源：http://dali.gzhubu.top/Article/details/gtfivsfeka.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtxevlgdjp.html

[T04] Kotlin：空安全
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcedcbtc.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtwfraipar.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtimaedzvx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtlipenyob.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gthtteiyum.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtovgpzldi.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtrxmlqwdg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhijiandao.cn/Article/details/gtzuuiwiyw.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gtblrvaaxh.html

data class User(val name: String, val age: Int)
来源：http://dali.ybcxt.top/Article/details/gtghkxwjwv.html

[T09] Kotlin：扩展函数
来源：http://dali.jinqigfzy.top/Article/details/gtnqqrarkr.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtkyaliitd.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtmgbdwjvn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtqztnksxl.html

[T11] Kotlin：协程
来源：http://dali.yanxiufei.cn/Article/details/gtvvmqimix.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmljqqwcu.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtukmbpxfv.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtwrglashf.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtlgfwfahb.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqkkpkag.html

[T14] Kotlin：循环
来源：http://dali.chenlongwang.top/Article/details/gtffcvycic.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gttumtauvj.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtwcpoudqf.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtnpbhoyet.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtnifrxlzr.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtqikbchht.html

[T17] Swift：变量与常量
来源：http://dali.jqgfzy.top/Article/details/gttzpvlpbj.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtjpubyxij.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtwjnsptko.html

"值: \(b)"
来源：http://dali.316326.xyz/Article/details/gtsbmodpnx.html

[T19] Swift：可选绑定
来源：http://dali.tanke756.top/Article/details/gtkvksrmuy.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtnnnoiokv.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtaepfqxje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtfkdcwgxw.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gtylvtztit.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtiiyrxltu.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtsohgnktx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtrxvtdnnj.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtjtvunwlz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtdfabvhlk.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtbvnmtxmt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtdwgupevg.html

[T25] Swift：结构体
来源：http://dali.zycfv.cn/Article/details/gtxzhexmhw.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtpodxgsql.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtpvkxogyk.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtjywbkodw.html

[T27] Swift：错误处理
来源：http://dali.wangshuangyany.cn/Article/details/gtetqeepcu.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtohpjsdan.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbexhxprk.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtsrzyikgt.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgfzy.top/Article/details/gtrijfwcwu.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsnblifs.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtbimdglzg.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gtxzjagpqq.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtkgxqhspp.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsposgkow.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtuqsddkaw.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtzdpmmbyv.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtnaokkrpd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtfoqdkcia.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtuesujuto.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtuyxiyjxl.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtgbmgzftp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gthstvyvvy.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtaeygatyw.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtnlfnefwe.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtidfdsxjk.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtylsqhwjx.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gtjzpvrwug.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtxtyvrmpn.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtxfexmeal.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtbotixxfy.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gthzdseksq.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gthyzjtlun.html

[T41] Perl：Hello World
来源：http://dali.fzhhl.top/Article/details/gtgqapcxgv.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gttjrieaxa.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtukreiztz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gtmmjnekbj.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtgutfaiwa.html

"值: $a"
来源：http://dali.zdqjudy.top/Article/details/gtcbccwnmb.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtuirpmyxb.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gtfoplvcga.html

[T45] Perl：数组遍历
来源：http://dali.xziqi.cn/Article/details/gtyxogcqmw.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtsxryqgou.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtbxzzehmc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtjgabemzm.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gtvgiwzkxb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtftgugycc.html

[T48] Perl：正则替换
来源：http://dali.sufxvd.cn/Article/details/gtloceyxjj.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtrhsxlszy.html

[T49] Perl：函数
来源：http://dali.gotoacloud.top/Article/details/gtepvoqhlg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtxtepijwp.html

[T50] Perl：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtycoqsmpg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtkmhjtkwc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtcomtilti.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtqqyqktjp.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtkaasbzso.html

[T52] Scala：变量
来源：http://dali.cdnleiting.top/Article/details/gtcwjqwjnl.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gtbnmxfslz.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtdvewwdtb.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtmoxcqqpj.html

[T54] Scala：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gtzbmnzvvv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tian-w.cn/Article/details/gtugnigcij.html

[T55] Scala：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtcpnayule.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gttmczcigd.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtjhhhfxfk.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtfdbgngti.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gtaraqblyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtkgkptvmc.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gtevcasokp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtsvezeoyt.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gtldqirrvr.html

for (i <- 1 to 10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtkykornig.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtjdngidkm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gtjewwggfn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtiiiwhfvn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.haohaochexian.top/Article/details/gtvbmltcjg.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtsqcloqkk.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gtleocfurz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtigkpmhug.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ybcxt.top/Article/details/gtxvvwyjyt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gtflpowxxg.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujdniapa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gtmioohytg.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gtzvgicuwt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yueranfly.top/Article/details/gtcbwafiwb.html

[U05] Py：列表去重且保序
来源：http://dali.jinghuilouyu.cn/Article/details/gtobbliyxb.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtcpdiorty.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtimmbidtm.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtmxgwekuv.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtfpleungy.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtszzxuygi.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtfozkepfr.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtgtoredhf.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtrnyayijm.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtbwgpuqyz.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gtgdipskpq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gtmlmjadxi.html

[U11] Py：生成器表达式
来源：http://dali.chenzaomai.com/Article/details/gtgaxtnmhn.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtrbvpllgn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtmiozidnt.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gtsngddcnd.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtcyxcedix.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnzpnglik.html

[U14] Py：分组收集到列表
来源：http://dali.xylfe.cn/Article/details/gtannkquee.html

defaultdict(list)
来源：http://dali.gogol.net.cn/Article/details/gtustsmcbt.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gtqqmkglce.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtlctvqhho.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtjdcyhdjr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtpgpmiwlt.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtfknphhlk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.haohaochexian.top/Article/details/gtnwebvgyu.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtgkyvsbwt.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtyrnddvhf.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gtvfmbzmbg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gtikequcnq.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gtokdnwbri.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gtsqdglktv.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gtvfyrachq.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtsslkntul.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvxcczvrv.html

list(zip(*m))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvabiclhq.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gtihjbuboz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtlkzqfegw.html

[U24] Py：路径操作
来源：http://dali.gogol.net.cn/Article/details/gtjmrjojeu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtjslcaswx.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtxsbggykc.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gtxnykkhgs.html

[U26] Py：并发下载
来源：http://dali.cdnleiting.top/Article/details/gtbpozqapl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtvjamiwzc.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gtjjkzjgda.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtgcuippib.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gtuepisekh.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gthahoiike.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtoddvpwwk.html

@property 与 @x.setter 配合
来源：http://dali.guowangkeji.top/Article/details/gtocthcluy.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gtvzasomzc.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gttivbqefa.html

[U31] Py：单测
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbngsrcww.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtixrqzkwv.html

[U32] Py：代码格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtyewimjwl.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gtpdhqabhz.html

[U33] Py：打包发布
来源：http://dali.yvedp.cn/Article/details/gttgvbocvc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zdqjudy.top/Article/details/gthuboapuj.html

[U34] Py：判断编码
来源：http://dali.feifeiyinyue.top/Article/details/gtdnpfpgmd.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gtilgsjmsz.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtcrxgyldl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.pengpengdd.cyou/Article/details/gtawzwreti.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtsshrawlg.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gtludblths.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gttjblrzgt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.haohaochexian.top/Article/details/gttxggvyyy.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtdwieecgj.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtixdguinx.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gtcaujkyal.html

sys.stdout.isatty()
来源：http://dali.daria6918.cn/Article/details/gtgdkrbiry.html

[U40] Py：打印到标准错误
来源：http://dali.guannengcc.top/Article/details/gtmyynqqdp.html

print("err", file=sys.stderr)
来源：http://dali.yanxiufei.cn/Article/details/gtgdsfvere.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gtvcqirxvq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gthzjiugzt.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.daxiang520.top/Article/details/gtcemkkwdy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgwddsjts.html

[U43] PHP：声明命名空间
来源：http://dali.zdqjudy.top/Article/details/gtcchpafka.html

namespace App\Http;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcneogtc.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtsttqfsft.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtpvpzxooq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pengpengdd.cyou/Article/details/gtmguhdptg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtivsmpwkz.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gtcylnhgtx.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtrlijfeaz.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtroolpbhc.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gtesrdakrf.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtuxmlopgl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shuidangran.top/Article/details/gtvjtoqlla.html

[U49] PHP：只读属性
来源：http://dali.ydzc1.top/Article/details/gtgmwiaolw.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtixxjgaps.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gtmzmwfveg.html

public function __construct(private int $id) {}
来源：http://dali.smart0.xyz/Article/details/gtjckztzat.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtywifioqy.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gtrehtezxc.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtelboigsf.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtrrusbgjc.html

[U53] PHP：空合并运算符
来源：http://dali.pycfn.com/Article/details/gtztbslced.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gtjkkwiyrm.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtfrtvkawy.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gtdcelyyif.html

[U55] PHP：match 表达式
来源：http://dali.yonumen.top/Article/details/gttqnojycl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtvjvmaqes.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gtomuygyff.html

f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawpxadeu.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtpnyjhcvp.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gthouapccf.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gttdunildx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtbulhseem.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwhwarbeg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenlongwang.top/Article/details/gtsorznopa.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtvoxnrkms.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.havefunace.top/Article/details/gtijlcdwmb.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtrdchkjqt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yanxiufei.cn/Article/details/gtwbzobvqq.html

[U62] PHP：日期对象
来源：http://dali.gzhubu.top/Article/details/gtzvgrtnxc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtrfzaugoy.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gtehtazagj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cucudq.cn/Article/details/gtuitquujl.html

[U64] PHP：目录遍历
来源：http://dali.hnxiangtu.top/Article/details/gtbyepszvn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuiwqmdqj.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gtpccgrnjh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtgktcwxok.html

[U66] PHP：设置 Cookie
来源：http://dali.hammf.cn/Article/details/gtrboejkoy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.9152youxi.cn/Article/details/gtopgukqzs.html

[U67] PHP：处理文件上传
来源：http://dali.dashuyun.cn/Article/details/gttqqzozfl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zdqjudy.top/Article/details/gtuttumekk.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gthfiqmlga.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gtdfihvlze.html

[U69] PHP：PDO 预处理
来源：http://dali.hongshengwenyu.top/Article/details/gtpyruiypd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcbwofntm.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvmocoztk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gtfagahjkp.html

[U71] PHP：抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtxphtitqm.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258888.top/Article/details/gtqetnyeqv.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gtxsqlcmff.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gtggswayzh.html

[U73] PHP：读取 ini 配置
来源：http://dali.jianghu66.top/Article/details/gtdueqnwiy.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gthuglylsl.html

[U74] PHP：读取环境变量
来源：http://dali.yuxming.cn/Article/details/gtpqltyyrk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hywenlv.cn/Article/details/gttywodahu.html


<!-- 参考信息 -->