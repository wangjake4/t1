代发 wailian999

[S45] C++：lambda
来源：http://dali.hnxiangtu.top/Article/details/gtmmelrzae.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtxzxwcixk.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtxlchekzk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtgfxpxoao.html

[S47] C++：结构化绑定遍历
来源：http://dali.0kj1m.cn/Article/details/gtjtsfcldb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxzieetlq.html

[S48] C++：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtctyufauw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtlpkhvdxl.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gteeeplwkb.html

[S49] C++：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtgyqgoagr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtiqyutqjd.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtdvlnudbt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yueranfly.top/Article/details/gttfdedwqv.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtwbtbjbmm.html

static_cast<double>(a) / b
来源：http://dali.cashguo.top/Article/details/gtnqjcajjo.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtslhjozfj.html

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtsemegzdu.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gtbclwuojv.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gtmamntkto.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtehrxcgzf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtrxmcbhdo.html

[S55] C++：结构化绑定
来源：http://dali.zdqjudy.top/Article/details/gtrxftimmv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtqhqdmaux.html

[S56] C++：optional
来源：http://dali.gogol.net.cn/Article/details/gtqeloaumd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtkusdzqqc.html

[S57] C++：编译期常量
来源：http://dali.quarkkingdee.top/Article/details/gtwvjrnayq.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtlrspbdta.html

[S58] C++：命名空间
来源：http://dali.jiagoushi.top/Article/details/gtogmoqvht.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtkpegyrwd.html

[S59] C++：静态断言
来源：http://dali.0kj1m.cn/Article/details/gtvblpjxxp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gtubxmfraz.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtlkkllcre.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtlrcdqegs.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtbqmzspfx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtaezokxic.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtlmztbuft.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtwhzscgpc.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtgisjpbes.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gteevuhvfo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtiaqwljmo.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtprhkplbn.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtlvacfbug.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtlkihxamw.html

val n: String? = null;  n?.length
来源：http://dali.nwbrower.top/Article/details/gtxoefudgx.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrfbmauub.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtmqtqsujz.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtupestukr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtwhqzkurm.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtzbgkukuk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtecgaladw.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtuazqgysr.html

data class User(val name: String, val age: Int)
来源：http://dali.xylfe.cn/Article/details/gtorcgdaax.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gtrxryccrx.html

fun String.exclaim() = this + "!"
来源：http://dali.cdnleiting.top/Article/details/gtwqcrtfom.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gttmczsfik.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gthvsscgew.html

[T11] Kotlin：协程
来源：http://dali.hammf.cn/Article/details/gtuokpigum.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.316326.xyz/Article/details/gtvtkasojc.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtvthgqchz.html

val (a, b) = Pair(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gtaynmapsu.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtnpoefjlc.html

val m = mapOf("a" to 1)
来源：http://dali.havefunace.top/Article/details/gtvvhakwcm.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtngxzesrh.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtdhfsdotm.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtuknpqbol.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtqbuifjej.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtuqqmzozg.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtpznudwtv.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtweeoaopa.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtlkibemuv.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtuzuwhrth.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtakffjkyr.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtkaxbllvr.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gtmqxcjjtw.html

[T20] Swift：数组操作
来源：http://dali.hfpthk.cn/Article/details/gtlhzmprqh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtardeeoug.html

[T21] Swift：遍历
来源：http://dali.zycfv.cn/Article/details/gtsojwtndj.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfrwcxuy.html

[T22] Swift：字典
来源：http://dali.cucudq.cn/Article/details/gtgqxqlyuk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtjdzssthd.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gthmqxjoag.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtivovppou.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtdoczvpkw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtrnkefuos.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtjlhnvoza.html

struct P { var x: Int }
来源：http://dali.yueranfly.top/Article/details/gtfrzusiqe.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gtakblacgw.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtoczdkpwd.html

[T27] Swift：错误处理
来源：http://dali.yj20258888.top/Article/details/gtabezqtrr.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtghchchjr.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtqhphtxyl.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtlxlskvrd.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gtoghvwgls.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtacugjses.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gtsoftcfgz.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtrsbhfvxh.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiptycld.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtrbvdthwy.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtxulrikfq.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtrwdvpiyu.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtvhpkstwh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yongpay.top/Article/details/gtqxawbjce.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtpegbcume.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pycfn.com/Article/details/gtrtchdwkr.html

[T35] Lua：字典表
来源：http://dali.zhengqikj.top/Article/details/gtzsirjorj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtqofvarnr.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtqnzwlkjn.html

function add(a, b) return a + b end
来源：http://dali.nwbrower.top/Article/details/gtvxjilqfv.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtfswbizcc.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtrtwcyvxi.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtroztzgqd.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gthkukdmce.html

[T39] Lua：模式匹配
来源：http://dali.yvedp.cn/Article/details/gtgvrcdqyd.html

string.find(s, "%d+")
来源：http://dali.ivvv.top/Article/details/gtugfdcmvl.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtfbgfeofy.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtuqzhmxbt.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtcfohwfpd.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtfzqasaah.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtpnjrgvkk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqktcfsff.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtsyuygtaq.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtmmvmnifi.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbtcrotjd.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtkatkzmho.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gtixydtnlj.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtglduzcdx.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtzvafcgsf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gtklnrdrhd.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtpcxeffdn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtevsqjvew.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtxqdatnms.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtyoqmynhe.html

[T49] Perl：函数
来源：http://dali.zycfv.cn/Article/details/gtosvqelet.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglnjdbqb.html

[T50] Perl：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtcdtbbgxq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtssklcktl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cashguo.top/Article/details/gtslkmxpgg.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtrnlirwca.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtljfodiyc.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtflxzxxng.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtkqdyczdv.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtwarpmrxp.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gthtvaixyi.html

[T54] Scala：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtjdaziake.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtcoalqrxt.html

[T55] Scala：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtxbuninzp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtqszvblko.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gtacdyuhrs.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtsahfsttv.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtmipgqctj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtgrmhonkf.html

[T58] Scala：函数定义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyfphhdv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gttwulmuyc.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gtnrlbcisy.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gtozvrmlov.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtsxprcwna.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtkcrohawp.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gthodfhldv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtejiaatwy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtgkcoxvaq.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtzwwdvsbf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gtkqwycvgw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gtkmlktszq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtyfxmercr.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtubkdwqqy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gtntcvglbw.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gthxfnlvjn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtdooqxtce.html

[U05] Py：列表去重且保序
来源：http://dali.haohaochexian.top/Article/details/gtktvcbkku.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtqnqxxvah.html

[U06] Py：合并两个字典
来源：http://dali.shzxlz.cn/Article/details/gtrattwpng.html

{**a, **b}
来源：http://dali.smart0.xyz/Article/details/gtaroepyut.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtevdnpgrr.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtdrhtwqzi.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtfehubxug.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtessdlyop.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gtfallervo.html

max(d, key=d.get)
来源：http://dali.zhiwuduotai.top/Article/details/gttfmxitno.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtgcfkiemi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gtgvsjipvo.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtakbxjjbn.html

(x * 2 for x in arr)
来源：http://dali.tianlin.xyz/Article/details/gttkqqkqdf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gtwfvculzo.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gtoqpuxmvd.html

[U13] Py：固定长度队列
来源：http://dali.yj20258888.top/Article/details/gtfxfxaamb.html

deque(maxlen=10)
来源：http://dali.ivvv.top/Article/details/gtueobiqve.html

[U14] Py：分组收集到列表
来源：http://dali.jqgufenzy.top/Article/details/gtlyadluto.html

defaultdict(list)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwnmrjkws.html

[U15] Py：高精度计时
来源：http://dali.zhixingplan.top/Article/details/gtbrrvzumj.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtozgebadr.html

[U16] Py：命令行参数解析
来源：http://dali.xinyue.icu/Article/details/gtdawgcwmv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gtfrwmlglp.html

[U17] Py：初始化日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatptevzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yueranfly.top/Article/details/gtpclkilol.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtdyiwxloa.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtwjqaftwj.html

[U19] Py：正则替换带回调
来源：http://dali.cdnleiting.top/Article/details/gtkvgtzyio.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gtxmqetqpt.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gthvrmhybr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gteztyjgca.html

[U21] Py：自定义上下文管理器
来源：http://dali.hysaishi.cn/Article/details/gthlbdeope.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtpioezziv.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gtuwxlzuah.html

list(zip(*m))
来源：http://dali.ivvv.top/Article/details/gttzvljpzf.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gteijgvlvk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtdtlnkjkn.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gtedaantys.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gtcwvsdmdz.html

[U25] Py：CSV 按字典读
来源：http://dali.hywenlv.cn/Article/details/gtkgemfzib.html

csv.DictReader(f)
来源：http://dali.pycfn.com/Article/details/gthwvafmtb.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gtmkmdhlef.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxinkj.top/Article/details/gtwsyfclan.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtpfnpulnd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtxzbxgzsj.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtgeetcsxb.html

UserId = int
来源：http://dali.haohaochexian.top/Article/details/gttzalvlis.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gtyrmhxrjf.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjoliaejj.html

[U30] Py：数据类
来源：http://dali.xuanzx.com/Article/details/gtoqiffglb.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtepjonzqy.html

[U31] Py：单测
来源：http://dali.nanxinkj.top/Article/details/gtccqliase.html

python -m pytest -q
来源：http://dali.zdqjudy.top/Article/details/gtslgpowxs.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gttvxhdodm.html

ruff format . && ruff check --fix .
来源：http://dali.jiagoushi.top/Article/details/gtylfhlprm.html

[U33] Py：打包发布
来源：http://dali.nwbrower.top/Article/details/gtzmbmnoqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtaubbllei.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtuweaascm.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtondjrjze.html

[U35] Py：发送邮件
来源：http://dali.feifeiyinyue.top/Article/details/gtpobwopuc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gttihwsoln.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtukzfqlke.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj20258888.top/Article/details/gtuqsgcvhd.html

[U37] Py：读写 Excel
来源：http://dali.9152youxi.cn/Article/details/gtpkzpzuec.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtonndktxt.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinqigfzy.top/Article/details/gtvvasfixn.html

Path(__file__).resolve().parent
来源：http://dali.aizwys.cn/Article/details/gthvbibpjz.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtdjghmpab.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtuumsttuy.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtatuczjxt.html

print("err", file=sys.stderr)
来源：http://dali.yvedp.cn/Article/details/gtananeobs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtfzwjunvi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigfzy.top/Article/details/gtewtuazrf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gthomitwsp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtbpsirbmk.html

[U43] PHP：声明命名空间
来源：http://dali.daxiang520.top/Article/details/gtdxryinkd.html

namespace App\Http;
来源：http://dali.zhiwuduotai.top/Article/details/gtgiynzgee.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gtivvnfwbs.html

declare(strict_types=1);
来源：http://dali.daria6918.cn/Article/details/gtttowxsej.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtymvwbrkv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyqbnwhmj.html

[U46] PHP：可空类型
来源：http://dali.yuxming.cn/Article/details/gtwplntomx.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiqqclmn.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtqzsrriio.html

int|string $id
来源：http://dali.nanxinkj.top/Article/details/gtboeznwsu.html

[U48] PHP：纯枚举
来源：http://dali.pycfn.com/Article/details/gtwuprcdgj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhoulong.xyz/Article/details/gtvyolbnum.html

[U49] PHP：只读属性
来源：http://dali.zdqjudy.top/Article/details/gtxemyysxf.html

public readonly string $name
来源：http://dali.fzhhl.top/Article/details/gtonjgsrxd.html

[U50] PHP：构造器属性提升
来源：http://dali.fengsongda.top/Article/details/gtaegdwied.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtvjkkrkbb.html

[U51] PHP：数组解构
来源：http://dali.gogol.net.cn/Article/details/gtfjxxjlwj.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gtklupnwrb.html

[U52] PHP：箭头函数
来源：http://dali.tianlin.xyz/Article/details/gtblufashg.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxndmdnls.html

[U53] PHP：空合并运算符
来源：http://dali.jqgfzy.top/Article/details/gtuzqayeds.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuxming.cn/Article/details/gtbsuvfuyu.html

[U54] PHP：空安全调用
来源：http://dali.yuanzhike.top/Article/details/gtgxyewqxq.html

$obj?->method()
来源：http://dali.xylfe.cn/Article/details/gtqiwtdorr.html

[U55] PHP：match 表达式
来源：http://dali.kuanghao11.cn/Article/details/gtvewiwaih.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenlongwang.top/Article/details/gtztbdgwzi.html

[U56] PHP：命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqogjqtu.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtuvexwkzs.html

[U57] PHP：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtmzkucsii.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gttaksanon.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtxrefkktd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gtxqxlkkwr.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtzgksgbpk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigfzy.top/Article/details/gtfmwuwtdr.html

[U60] PHP：JSON 编解码
来源：http://dali.9152youxi.cn/Article/details/gtjrdxmcve.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hysaishi.cn/Article/details/gtwsndcafu.html

[U61] PHP：正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwqdmnvh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtuekvnieh.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gtzcaiojhe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yanxiufei.cn/Article/details/gtugjtjmgy.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtumqlamxx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pengpengdd.cyou/Article/details/gtccqtvvbh.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gtzlihfgdi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gtdfizdrzw.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtfztltgql.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtasnxtvuu.html

[U66] PHP：设置 Cookie
来源：http://dali.zycfv.cn/Article/details/gtnfnugobg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hfpthk.cn/Article/details/gtbnkhjsyy.html

[U67] PHP：处理文件上传
来源：http://dali.hnqzz.top/Article/details/gtszvdybzw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dashuyun.cn/Article/details/gtqbnmlulo.html

[U68] PHP：PDO 连接
来源：http://dali.zhongyouzk.top/Article/details/gtehulibif.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtgettttwh.html

[U69] PHP：PDO 预处理
来源：http://dali.fzhhl.top/Article/details/gtcgoeebys.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gtfysznpbx.html

[U70] PHP：PDO 事务
来源：http://dali.yanxiufei.cn/Article/details/gtnqwserwh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gteaoyzvax.html


<!-- 参考信息 -->