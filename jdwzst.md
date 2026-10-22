代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.xziqi.cn/Article/details/gt2gvaepaye.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.smart0.xyz/Article/details/gt2ictguvlw.html

[S48] C++：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gt2mghrpelw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhoulong.xyz/Article/details/gt2kjhpigah.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbjzccou.html

[S49] C++：写文件
来源：http://dali.ivvv.top/Article/details/gt2mcrohqlb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ivvv.top/Article/details/gt2uxchrwko.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gt2qfjwwrlg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gt2dvcuikwg.html

[S51] C++：显式类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2vjqirodh.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gt2uqiklnzy.html

[S52] C++：const 与 noexcept
来源：http://dali.redwolf501.top/Article/details/gt2jcbismlw.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mxxaiiwq.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gt2ncnlkuii.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gt2tomoibbg.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gt2eerqizfb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gt2jaekrqex.html

[S55] C++：结构化绑定
来源：http://dali.xziqi.cn/Article/details/gt2qusnrxdw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gt2wsovhxig.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2ryzqamcw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2yoypxbpu.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gt2iujxpjxn.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2ahursmec.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gt2nzhqzzxh.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2vbgwflol.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gt2rqxolmgv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jfdwtdyr.html

[S60] C++：遍历并删除元素
来源：http://dali.pycfn.com/Article/details/gt2rcbmwhvs.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gt2fwafxsek.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmyhrscn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hywenlv.cn/Article/details/gt2jdsrzdia.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2zeowawcf.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yibgakvx.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2waeemtbt.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2tnvlzgjy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dianchejie.cn/Article/details/gt2evqlcajn.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gt2dpnuanpw.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gt2jaspqcqp.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gt2csupwmni.html

val n: String? = null;  n?.length
来源：http://dali.sweek.top/Article/details/gt2nzjogsmo.html

[T05] Kotlin：when 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2fcqsogtf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gt2kmmrepac.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwikjmv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gt2bmquvvph.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gt2bwtnhsri.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2tttgyhwi.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gt2gsnyjfry.html

data class User(val name: String, val age: Int)
来源：http://dali.hfpthk.cn/Article/details/gt2cbsnjznp.html

[T09] Kotlin：扩展函数
来源：http://dali.meibo888.top/Article/details/gt2hsnwqacu.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gt2lhmhzjbl.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zgmgksof.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fzhhl.top/Article/details/gt2ahoeacjn.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2ynlarouw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2xmusuydd.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gt2ywmdnjok.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gt2zhnleerj.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gt2hjyzeksu.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gt2rcuoetgb.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gt2kmpbspic.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2pbiqqwxs.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gt2zvdltbip.html

interface Shape { fun area(): Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2dlqmqvpi.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2ehfgjchj.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2ywdmzyfj.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gt2fvnouxff.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gt2izrzpwad.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2qcsacnbq.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2asjtzyvy.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gt2pvtjtmok.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gt2qogpbogj.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gt2shglkfhk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gt2kqdcpugd.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gt2mcitlvft.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gt2pherhkcl.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gt2idljwvas.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gt2tryywmiq.html

[T23] Swift：函数
来源：http://dali.daria6918.cn/Article/details/gt2gsfucwow.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jlsjyb.cn/Article/details/gt2yzbppptr.html

[T24] Swift：闭包
来源：http://dali.guannengcc.top/Article/details/gt2cdnwugbf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2bcxnqnvo.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gt2qgzdjzyz.html

struct P { var x: Int }
来源：http://dali.yongpay.top/Article/details/gt2mjlopwjb.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gt2omatfleo.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xmeedhsb.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gt2pxlpmylk.html

do { try f() } catch { print(error) }
来源：http://dali.gogol.net.cn/Article/details/gt2najywprq.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gt2rkolhesn.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oqezyvlu.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gt2cfomoqwi.html

guard let x = opt else { return }
来源：http://dali.wangdashe.top/Article/details/gt2cveebrzx.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gt2fwhbrozu.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gt2lfothacb.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2nswoppbh.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2natvqzcl.html

[T32] Lua：局部变量
来源：http://dali.yonumen.top/Article/details/gt2oblgglys.html

local a = 1
来源：http://dali.yangfankeji.com/Article/details/gt2vpvjhlnp.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kuuvnfpu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2fypiyebr.html

[T34] Lua：遍历表
来源：http://dali.tian-w.cn/Article/details/gt2usklebdw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gt2ytyxqhqb.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gt2fxnqquoa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2epttotsl.html

[T36] Lua：函数
来源：http://dali.tian-w.cn/Article/details/gt2slilwcxn.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gt2qxnnyjzk.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gt2mdoszssm.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gt2ntuquxza.html

[T38] Lua：条件
来源：http://dali.hnqzz.top/Article/details/gt2wviejxfu.html

if x > 0 then print("正") end
来源：http://dali.nanxinkj.top/Article/details/gt2flkbfbcp.html

[T39] Lua：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2rwqzgiql.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2tsigjltl.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gt2gysantfa.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gt2wpksfpyj.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2bkrbimtc.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gt2geheqbip.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gt2vjhueibl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hnxiangtu.top/Article/details/gt2xttdklab.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gt2nvupukie.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2dxulauhn.html

[T44] Perl：条件
来源：http://dali.ydzc1.top/Article/details/gt2hkejqdbe.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2shnujyun.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2yvbzcopv.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gt2nxlqinhn.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gt2bepndjaw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2mtkxssaz.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2jmhxnyrk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gt2hiyqozyf.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gt2aasitnqm.html

$s =~ s/old/new/g;
来源：http://dali.ivvv.top/Article/details/gt2gpnqwotw.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2pnepzndf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gt2qktjyetj.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkdxlaiw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daxiang520.top/Article/details/gt2nltclbgo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2uwcysbfs.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2keesoxwt.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2iutwkvlg.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gt2cjjzldka.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2vrshbvmp.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2miumpmrx.html

s"值: $b"
来源：http://dali.316326.xyz/Article/details/gt2immmwjdm.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gt2yfjneoae.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gt2wfsyngmt.html

[T55] Scala：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2yustskmt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhengqikj.top/Article/details/gt2rvsflazc.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2urjhsseq.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gt2stjtdbnd.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2ktmyamei.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gt2vokklqym.html

[T58] Scala：函数定义
来源：http://dali.gaohongyu789.top/Article/details/gt2sunpsgtq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gt2tdqgnzho.html

[T59] Scala：循环
来源：http://dali.redwolf501.top/Article/details/gt2zmzebrdt.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2ygjczsaw.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gt2tizrisvn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gt2dbodichf.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ieanwonj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gt2hcgwnbsw.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tusypbfm.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gt2aftxjncr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gt2ztuajemf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gt2cvbtcpvx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gt2hhdtclur.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gt2lbbexicu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gt2kmytawmd.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gt2arntzkyw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gt2jzewfafw.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gt2vrnktyvq.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gt2sdwawjbe.html

[U06] Py：合并两个字典
来源：http://dali.316326.xyz/Article/details/gt2yetrgdob.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmlmumpx.html

[U07] Py：反转字典键值
来源：http://dali.xuanzx.com/Article/details/gt2fuivvpnf.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gt2phisxwfb.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gt2bxembwnt.html

[y for x in nested for y in x]
来源：http://dali.zhoulong.xyz/Article/details/gt2goldkwpd.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gt2swftjlwy.html

max(d, key=d.get)
来源：http://dali.birdmap.top/Article/details/gt2vipirnlr.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gt2shrmxcxe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2fxiifpns.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gt2apwswlqs.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gt2astgngkl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gt2hwphxsam.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gt2givrsllj.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gt2rzgalrcp.html

deque(maxlen=10)
来源：http://dali.chenzaomai.com/Article/details/gt2dpbbowcx.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gt2zvvvmxok.html

defaultdict(list)
来源：http://dali.yuanzhike.top/Article/details/gt2wqsmxqwd.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2oonarvls.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gt2ecxuypgx.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2qkbuqvwd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gt2zffaqdgk.html

[U17] Py：初始化日志
来源：http://dali.tian-w.cn/Article/details/gt2oggcdznm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gt2egyeacxf.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gt2oxjfuflr.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gt2dmntmwso.html

[U19] Py：正则替换带回调
来源：http://dali.zdqjudy.top/Article/details/gt2khvquoju.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gt2ltugurgo.html

[U20] Py：缓存函数结果
来源：http://dali.haohaochexian.top/Article/details/gt2yosizocj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gt2fgfolwpm.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gt2cpahyvqb.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2zjbtvluw.html

[U22] Py：矩阵转置
来源：http://dali.c1oappe.top/Article/details/gt2tkzwypgz.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2tzgpahqs.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gt2kzgbbrbs.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vmisdjqx.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gt2suhfbvvl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gt2ldbjyhxv.html

[U25] Py：CSV 按字典读
来源：http://dali.fengsongda.top/Article/details/gt2lhgqfdea.html

csv.DictReader(f)
来源：http://dali.zhijiandao.cn/Article/details/gt2mtiymkmv.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gt2oyyqussn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gt2ytdxtuve.html

[U27] Py：异步 HTTP
来源：http://dali.xuanzx.com/Article/details/gt2rsvuyskt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.9152youxi.cn/Article/details/gt2nzzuztcx.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2ajtzbsnu.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2fzxuzesu.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gt2nsxfztsg.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gt2ceudoiyi.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gt2hmxbsezo.html

@dataclass(slots=True)
来源：http://dali.nanxuanxn.top/Article/details/gt2slshstcp.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2lgruzbsh.html

python -m pytest -q
来源：http://dali.chenzaomai.com/Article/details/gt2fsxmgcvm.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2hfcprggd.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gt2enhtdmcf.html

[U33] Py：打包发布
来源：http://dali.smart0.xyz/Article/details/gt2lnfyjldc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sxryk.cn/Article/details/gt2qbpmsgwe.html

[U34] Py：判断编码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ehdeytwg.html

chardet.detect(raw)
来源：http://dali.shangyingyoupin.top/Article/details/gt2kmdvprln.html

[U35] Py：发送邮件
来源：http://dali.cashguo.top/Article/details/gt2blvclldx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gt2wvtiwzhi.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gt2gtrcdesp.html

schedule.every(10).minutes.do(job)
来源：http://dali.aibaodan.cn/Article/details/gt2wnemrflj.html

[U37] Py：读写 Excel
来源：http://dali.ybcxt.top/Article/details/gt2gayfbnez.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hnxiangtu.top/Article/details/gt2kvqrnwln.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gt2osaqwzey.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gt2adwcxmbu.html

[U39] Py：判断是否在交互环境
来源：http://dali.iojbl.cn/Article/details/gt2uwtxryjf.html

sys.stdout.isatty()
来源：http://dali.zhoulong.xyz/Article/details/gt2hgonweqp.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2ofbbvkva.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gt2gvuxwidt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.meibo888.top/Article/details/gt2jerxlaft.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gt2eshajppw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cqqwz.cn/Article/details/gt2gutwectu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jiagoushi.top/Article/details/gt2pjckgqbp.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2cytuoikp.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnsnousk.html

[U44] PHP：开启严格类型
来源：http://dali.wangdashe.top/Article/details/gt2slpibito.html

declare(strict_types=1);
来源：http://dali.quarkkingdee.top/Article/details/gt2heqojmvp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gt2ustrafku.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gt2jvxqmusb.html

[U46] PHP：可空类型
来源：http://dali.316326.xyz/Article/details/gt2xcgboszr.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gt2qpapkppy.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gt2pueqgzdy.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gt2sodqpzsg.html

[U48] PHP：纯枚举
来源：http://dali.jiagoushi.top/Article/details/gt2ksibikqn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hutfptha.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gt2zejrexfb.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gt2hyxnbdlo.html

[U50] PHP：构造器属性提升
来源：http://dali.jianghu66.top/Article/details/gt2lbibwrvo.html

public function __construct(private int $id) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2tyrxwxjr.html

[U51] PHP：数组解构
来源：http://dali.xuanzx.com/Article/details/gt2klyjnxvf.html

[$a, $b] = $arr;
来源：http://dali.hfpthk.cn/Article/details/gt2eejudqav.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2oojdqamq.html

$double = fn($x) => $x * 2;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bpkqawdt.html

[U53] PHP：空合并运算符
来源：http://dali.nwbrower.top/Article/details/gt2wibjgfdn.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gt2oumxzdtn.html

[U54] PHP：空安全调用
来源：http://dali.jinqigfzy.top/Article/details/gt2kbtgrfgd.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gt2gumnfcna.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gt2golcqtiy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vogxkxez.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gt2pxaltoxj.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aexkdllw.html

[U57] PHP：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2mzqsmnsb.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gt2sybwtcvp.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gt2mtfhdxdl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gt2tjjqpvgw.html

[U59] PHP：自定义排序
来源：http://dali.zhijiandao.cn/Article/details/gt2ehxbupnz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2cnfdfigc.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2hwvyifni.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gt2nikidxoc.html

[U61] PHP：正则
来源：http://dali.pycfn.com/Article/details/gt2ccayckdk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2thgzxxdh.html

[U62] PHP：日期对象
来源：http://dali.fengsongda.top/Article/details/gt2gkismfiw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luuxxbfg.html

[U63] PHP：文件读写
来源：http://dali.xinyue.icu/Article/details/gt2oekpygdu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txmgkexg.html

[U64] PHP：目录遍历
来源：http://dali.gotoacloud.top/Article/details/gt2jtvwvwia.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dxymidvr.html

[U65] PHP：会话
来源：http://dali.cqqwz.cn/Article/details/gt2fkpuubpx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2loottsbd.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gt2weepfyju.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gt2shsreuvx.html

[U67] PHP：处理文件上传
来源：http://dali.jyoumei.cn/Article/details/gt2pnskfvtk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.mhx1999.top/Article/details/gt2jxbuqjul.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gt2crtwpnyy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gt2bdqbwgzz.html

[U69] PHP：PDO 预处理
来源：http://dali.haohaochexian.top/Article/details/gt2khfgjrpw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gt2jlnexifu.html

[U70] PHP：PDO 事务
来源：http://dali.zhiwuduotai.top/Article/details/gt2ikumblve.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lwdtjumc.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gt2zodnqhwq.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqpgyqtk.html

[U72] PHP：写错误日志
来源：http://dali.dianchejie.cn/Article/details/gt2krpaucuw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guannengcc.top/Article/details/gt2ajpeuvwy.html


<!-- 参考信息 -->