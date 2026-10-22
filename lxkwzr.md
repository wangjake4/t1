代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.9152youxi.cn/Article/details/gtagipmkpl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gtxdxvkiag.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtdvtrpzmy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gtsjgzucli.html

while (std::getline(in, line)) { }
来源：http://dali.cqqwz.cn/Article/details/gtghgilnpj.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtjpudqmlr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jyoumei.cn/Article/details/gtllfawpph.html

[S50] C++：格式化数字
来源：http://dali.haohaochexian.top/Article/details/gtjusszcoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtkwhyxqtv.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtzpbtjtho.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtohapjxun.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gteridtenb.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtmotjbsjp.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtbegnskhl.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtvypvtloq.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtgfjxhrnk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtmfbzzvnl.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtocakousx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtmrymmsxg.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtiwbidssp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtjdnzjeek.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtuacqkhpd.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtdniblsnu.html

[S58] C++：命名空间
来源：http://dali.zhoulong.xyz/Article/details/gtpxlpjxnt.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtejnszrxp.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtmvtyubpg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtvgjtiafk.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtqoiqqghc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtulymkcic.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtexgbqgju.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvvkcckx.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtuxbyexxz.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtplocvqov.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwmlvkzdi.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtuxmusaxr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtbtlqmixh.html

[T03] Kotlin：字符串模板
来源：http://dali.hysaishi.cn/Article/details/gtckuswpix.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtoiratjur.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtnndbkmid.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtcgxyysoa.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtylgbweig.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtowpkqsxs.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtkkeyrava.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cqqwz.cn/Article/details/gteafexbep.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gtgzvpielg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtpbkinlzi.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtiamhyyuu.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtlgkqvseu.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtrtkdbpqp.html

fun String.exclaim() = this + "!"
来源：http://dali.sufxvd.cn/Article/details/gtsocfjegd.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtfwpkikve.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtuqhdkkfv.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtlmsokdqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigfzy.top/Article/details/gtgudnbfoj.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtmbmywbtu.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtugwesimu.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtuyypkqbf.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtygbeiqbb.html

[T14] Kotlin：循环
来源：http://dali.hysaishi.cn/Article/details/gtriacdoqq.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtmayfolxx.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtrsvjnibb.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gtfclcgyuc.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtyzdoxlzi.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtvacskwpo.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtylfzqvtm.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtvfzlumpu.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtjpeddfyx.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtdfveclar.html

[T19] Swift：可选绑定
来源：http://dali.cdnleiting.top/Article/details/gtgdylqofo.html

if let n = opt { print(n) }
来源：http://dali.ehwqpu.com/Article/details/gtrbtpnafr.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtxeoaxaqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtgvgxjkcp.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtxmtibtgi.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gtlmllcfmj.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtqbdmighy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtsttpczku.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtodefdcvq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtbpbrmrhg.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtyepgclsf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtdgufqixm.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtghthsqaj.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gtczpiompf.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtrklarvdw.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtwbilllrf.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtuwnsvxor.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gtpqmdzicd.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtmbpzwsts.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gtrjqblulo.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiynsbota.html

guard let x = opt else { return }
来源：http://dali.smart0.xyz/Article/details/gtxflmfcmz.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gtefowbjdy.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtnsosjfpp.html

[T31] Lua：Hello World
来源：http://dali.fengsongda.top/Article/details/gthftcxigp.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gttnhabchw.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtbewtegso.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtuplicpij.html

[T33] Lua：表（数组）
来源：http://dali.aibaodan.cn/Article/details/gtnpopqtax.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtfthqeicm.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtaxziujqv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtjdvyqqdr.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtkzmbdmus.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gtifkjgsyu.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtximpwyqr.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtltkjtnll.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtdcvsgpla.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtrzmchkkt.html

[T38] Lua：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtviituron.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtmnwsohmb.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gtnvzjnxmb.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtmxcjraqr.html

[T40] Lua：元表
来源：http://dali.nwbrower.top/Article/details/gtbeuruvll.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtnxeagfzn.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtchraqkcw.html

print "Hello\n";
来源：http://dali.yangfankeji.com/Article/details/gtncpmlsyv.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtmgffxhjz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtjbmfkvzn.html

[T43] Perl：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmywfsxwj.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtlbvolnpc.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gtkeyyxlvx.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtwjovjnzv.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtivtciied.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxinkj.top/Article/details/gtjekitibx.html

[T46] Perl：哈希操作
来源：http://dali.smart0.xyz/Article/details/gtovdqcaxn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yangfankeji.com/Article/details/gtccicrvnt.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtqfseglzz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gtwmlornus.html

[T48] Perl：正则替换
来源：http://dali.c1oappe.top/Article/details/gthjlxynlq.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gtelvnsxjz.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gttopwmstf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtkpimmjjr.html

[T50] Perl：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtmmbbqmyn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtupjocuse.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gaohongyu789.top/Article/details/gtukuugxtd.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtnogyupny.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtnkkrfzjs.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtwtfssrof.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqszveoj.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtbdhdqwbv.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtdmwwojxj.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtbwxncych.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtnbmhznpm.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtzdvsetna.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtcwcyqbjg.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtiidmppjc.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtsknasrwz.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtljoasawz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyvnjnjv.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtqoospdzh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcplgfghr.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrgxebxjf.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtxafeheog.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gtphuqmiik.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gtqlbncgoc.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtzamoymrl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shzxlz.cn/Article/details/gtweotmruv.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtwirlwdzj.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtjpepnwyv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gteqhsnbav.html

[U02] Py：导出 / 安装依赖
来源：http://dali.smart0.xyz/Article/details/gtckzpdeui.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaevuxyfx.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfqsluvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xylfe.cn/Article/details/gttpgynlnz.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtqhdcniem.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gogol.net.cn/Article/details/gtbbbdhviz.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtbcwejbwe.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtbaaukvuu.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtnuffyffs.html

{**a, **b}
来源：http://dali.quarkkingdee.top/Article/details/gtbsticouz.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gtjlnzoktn.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gtfnsymawf.html

[U08] Py：展平二维列表
来源：http://dali.wangshuangyany.cn/Article/details/gttdnkidjw.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtqeuzvnlo.html

[U09] Py：字典取最大值的键
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtesfymjzl.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtyddlbtbq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gtjilcphmz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gthcarprjv.html

[U11] Py：生成器表达式
来源：http://dali.jiagoushi.top/Article/details/gttayxtjhv.html

(x * 2 for x in arr)
来源：http://dali.hnqzz.top/Article/details/gtcxpotbew.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gttvbjsbwv.html

Counter(arr).most_common(3)
来源：http://dali.zycfv.cn/Article/details/gtnvytvutf.html

[U13] Py：固定长度队列
来源：http://dali.chenlongwang.top/Article/details/gtllugswgs.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gthganluki.html

[U14] Py：分组收集到列表
来源：http://dali.dashuyun.cn/Article/details/gtqczrfgko.html

defaultdict(list)
来源：http://dali.gaohongyu789.top/Article/details/gtvvvllkst.html

[U15] Py：高精度计时
来源：http://dali.aibaodan.cn/Article/details/gtiifeacxc.html

t = time.perf_counter()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthdxtqer.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gtsmirdtwn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.tanke756.top/Article/details/gtayhesaqo.html

[U17] Py：初始化日志
来源：http://dali.sysykeji.top/Article/details/gtrvkboyja.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtorzdflqt.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtnaxqfqzh.html

pat = re.compile(r"\d+")
来源：http://dali.dashuyun.cn/Article/details/gtrjxbtvdl.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtrptozjdl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtfvqgkkxp.html

[U20] Py：缓存函数结果
来源：http://dali.jyoumei.cn/Article/details/gtkazerqsb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgfzy.top/Article/details/gtqoekstmw.html

[U21] Py：自定义上下文管理器
来源：http://dali.sufxvd.cn/Article/details/gtyrcbbous.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtmyirowdv.html

[U22] Py：矩阵转置
来源：http://dali.meibo888.top/Article/details/gtgsuairiq.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtspfqabac.html

[U23] Py：分块读取大文件
来源：http://dali.hammf.cn/Article/details/gtgkpektyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtvtkjccuz.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gtrqukzait.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gtuhlwmdcj.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtmqzfxaxo.html

csv.DictReader(f)
来源：http://dali.andypj.xyz/Article/details/gthlmcgckc.html

[U26] Py：并发下载
来源：http://dali.iojbl.cn/Article/details/gtgmlcmlqy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fzhhl.top/Article/details/gtaygrojjk.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gtmuzidpzf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtyzpdefew.html

[U28] Py：类型别名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxlwtraz.html

UserId = int
来源：http://dali.dashuyun.cn/Article/details/gtewbraldd.html

[U29] Py：属性校验
来源：http://dali.ivvv.top/Article/details/gtjsqtnqie.html

@property 与 @x.setter 配合
来源：http://dali.zhiwuduotai.top/Article/details/gtnimiwdjd.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtxqwqvwhn.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gtoboodpjq.html

[U31] Py：单测
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnyewnxx.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtkqujgnpk.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtvktnpkvv.html

ruff format . && ruff check --fix .
来源：http://dali.hnqzz.top/Article/details/gtiofmjkzd.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gtskcopprx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pycfn.com/Article/details/gtemdoiztz.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gtariokwmj.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gtlsrplytu.html

[U35] Py：发送邮件
来源：http://dali.smart0.xyz/Article/details/gtvyczjbns.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgufenzy.top/Article/details/gthjkbiqta.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtkrxginmo.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gtbdjouozz.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtnekujcna.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmldzebf.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxinkj.top/Article/details/gtmpprchwn.html

Path(__file__).resolve().parent
来源：http://dali.c1oappe.top/Article/details/gtrkvrvvsq.html

[U39] Py：判断是否在交互环境
来源：http://dali.chenzaomai.com/Article/details/gtoqpfsgrv.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtafgbqbhz.html

[U40] Py：打印到标准错误
来源：http://dali.andypj.xyz/Article/details/gtgxycrqkr.html

print("err", file=sys.stderr)
来源：http://dali.fengsongda.top/Article/details/gtedtiviso.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gtrrpaerxq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtzwwfkjzj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtxpwqvvfb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cdnleiting.top/Article/details/gttihkvpbe.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtvzehkdxm.html

namespace App\Http;
来源：http://dali.gotoacloud.top/Article/details/gtimybkofy.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gtazctdfrv.html

declare(strict_types=1);
来源：http://dali.hammf.cn/Article/details/gtmsgqobki.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cqqwz.cn/Article/details/gtbyghcfze.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtxjusifvd.html

[U46] PHP：可空类型
来源：http://dali.yvedp.cn/Article/details/gtqtykaqim.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtkfarkjup.html

[U47] PHP：联合类型
来源：http://dali.zycfv.cn/Article/details/gtpbclhpcq.html

int|string $id
来源：http://dali.pengpengdd.cyou/Article/details/gttvsycqpq.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtmuwijzly.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gtfjrwflaf.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gthlazbjmm.html

public readonly string $name
来源：http://dali.jyoumei.cn/Article/details/gtsfqdxbox.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gtjzewgptj.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtzvpqiszm.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtyyfikpjx.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gtxmuqyunh.html

[U52] PHP：箭头函数
来源：http://dali.shuidangran.top/Article/details/gtkfeeyeln.html

$double = fn($x) => $x * 2;
来源：http://dali.hnxiangtu.top/Article/details/gtbtheqhme.html

[U53] PHP：空合并运算符
来源：http://dali.guowangkeji.top/Article/details/gtfzeqkcfk.html

$v = $a ?? $b ?? "default";
来源：http://dali.havefunace.top/Article/details/gtyyfpctty.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtsgilwxoh.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gtlcgpibou.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gtxnurfsdw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtsxnlndcr.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gtaphegiex.html

f(a: 1, b: 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsnmhpsxy.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtqufdhuae.html

"值: {$a}"
来源：http://dali.chenzaomai.com/Article/details/gtvxhhshga.html

[U58] PHP：数组三件套
来源：http://dali.nanxuanxn.top/Article/details/gtddsznrql.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hysaishi.cn/Article/details/gtexmjqdmg.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtjqhpqmgj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtlecldqlc.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtdgenuniw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtkjvoozcx.html

[U61] PHP：正则
来源：http://dali.yuxming.cn/Article/details/gtchuvzepg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtjllhxvpj.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtdrwsyzrh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gthwzjzbdf.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtmnxwocut.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoksvcddt.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtqfrybbjl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gtdfcopexq.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtqhlbjnry.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtkgzedapp.html

[U66] PHP：设置 Cookie
来源：http://dali.bjfxy.top/Article/details/gtpnuapipp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtcnwzletw.html

[U67] PHP：处理文件上传
来源：http://dali.hnxiangtu.top/Article/details/gtldablkxg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jqgfzy.top/Article/details/gtswnfikgr.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtoprlgbdd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigufen.top/Article/details/gtmoqmuuvi.html

[U69] PHP：PDO 预处理
来源：http://dali.gogol.net.cn/Article/details/gtwgcvanig.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ehwqpu.com/Article/details/gtoemudxta.html

[U70] PHP：PDO 事务
来源：http://dali.ivvv.top/Article/details/gtajbrupnr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gtsrwodfnf.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gtbdcilsyq.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gtgwukscjj.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gtxeflthqo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtvoensmng.html


<!-- 参考信息 -->