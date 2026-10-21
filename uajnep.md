代发 wailian999

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gtknmjtcdu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.0kj1m.cn/Article/details/gtjcyhfxey.html

[S46] C++：函数模板
来源：http://dali.dianchejie.cn/Article/details/gtotfgphyy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtlguzhnug.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtkbjvrehi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtyixpghxt.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnewilgkd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gtrijukalp.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtibguqvtm.html

[S49] C++：写文件
来源：http://dali.gotoacloud.top/Article/details/gtobgbgmiy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtdyxfczcl.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gtbxyerdno.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtejyvscjk.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtwpyxkxjc.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtturzrfja.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gtcjyecmgg.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gtexhzjyek.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtwdfxgavm.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gteauzrpiw.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtewfqzmps.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtndzcykdb.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhaplnkr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shuidangran.top/Article/details/gtmjaetpqo.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gthrqkuvlx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtgcynujik.html

[S57] C++：编译期常量
来源：http://dali.daxiang520.top/Article/details/gtdjnmvlmj.html

constexpr int N = 10;
来源：http://dali.yueranfly.top/Article/details/gtbpkivpue.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtpwrixsop.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gtwuzvlwux.html

[S59] C++：静态断言
来源：http://dali.chenlongwang.top/Article/details/gtndkgdaxd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtjnhrwudg.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtivozuwii.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtpurvknup.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtokoujmat.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.svipenyu.cn/Article/details/gtgvzrayco.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtxcquhwwb.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gththnznqi.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtjyqojcgw.html

[T02] Kotlin：变量
来源：http://dali.yonumen.top/Article/details/gtaufyfqbx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtsysaghgj.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtvafdiajc.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtkjmfezxu.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtgrhtskoz.html

val n: String? = null;  n?.length
来源：http://dali.dashuyun.cn/Article/details/gtyzadtujq.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjebpdhz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtskppsfdn.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtbndygbza.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtzoxgujug.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtjszcughr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gteelrghop.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtzlytmrbi.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtzjlethop.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtspqdpitx.html

fun String.exclaim() = this + "!"
来源：http://dali.ivvv.top/Article/details/gtlvubfrvl.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gthptbzcqs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaspturm.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtjcezwxle.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtmklopxje.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtbyczynkd.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtzoamgovf.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtaffvzwxh.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtnedscnki.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtfjmdkbrx.html

for (i in 1..10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtpbvgvxqn.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gtudlsirwy.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gtilgziwff.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmnbpvfvh.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtiajllvpl.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gtmjkqelkt.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtnrqcwpov.html

[T18] Swift：字符串插值
来源：http://dali.jianghu66.top/Article/details/gtzvijxwop.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtwohdwpka.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtizhoptkc.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtnayshkgt.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtrkzhjhos.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gtuszjrpgg.html

[T21] Swift：遍历
来源：http://dali.gzhubu.top/Article/details/gtqbpqwenm.html

for x in a { print(x) }
来源：http://dali.jinqigfzy.top/Article/details/gtwgrpghop.html

[T22] Swift：字典
来源：http://dali.wangshuangyany.cn/Article/details/gtpkgcajyr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtwrsopynb.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtdpksazui.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtuebqtvtd.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gtfcixxmkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrzumglkp.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtplqviowt.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gterlhkjvi.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gtfhfojfxi.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtnplkwzje.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtojwrhkhp.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtvrefivkt.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtczrxxcvy.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtbrrgoruj.html

[T29] Swift：guard 提前返回
来源：http://dali.xuanzx.com/Article/details/gtkmzvujah.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gteocekiui.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtyltygocr.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gthkgqnkbd.html

[T31] Lua：Hello World
来源：http://dali.ybcxt.top/Article/details/gtkhkdvmdp.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtdvmejpws.html

[T32] Lua：局部变量
来源：http://dali.xuanzx.com/Article/details/gtoaxexbfw.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtqbcdvsil.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtnvlaozgy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtntrhtdze.html

[T34] Lua：遍历表
来源：http://dali.shzxlz.cn/Article/details/gtqnfefmgx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dianchejie.cn/Article/details/gtrdyfkdup.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtnlxpmuah.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xylfe.cn/Article/details/gtzqtirfss.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gtzctuzsfq.html

function add(a, b) return a + b end
来源：http://dali.andypj.xyz/Article/details/gtytwesccb.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtqywkcsay.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtrvuuukyq.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtpmfhfnwo.html

if x > 0 then print("正") end
来源：http://dali.hywenlv.cn/Article/details/gtoddswuiy.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtmuwtvvne.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gtrczooqgj.html

[T40] Lua：元表
来源：http://dali.yj202588.top/Article/details/gtggfoeygw.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gtvfqzgvhe.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gtxtuxdpdc.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtzoybccbd.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtykesxztx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gtbzesjjwd.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtifjnuglr.html

"值: $a"
来源：http://dali.ivvv.top/Article/details/gtknavwqsq.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtrevgonfq.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gtehssqtqq.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqrfvnwjj.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtwdarsmqo.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtybgfqkkv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gttgbsvvpx.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtyaixitkb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gtvblpxfnx.html

[T48] Perl：正则替换
来源：http://dali.quarkkingdee.top/Article/details/gtuvtxgpai.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtxeiakiao.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gtaqhzxovs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtlrzwjiwx.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtyyxcbggp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfveqeuqv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtwimzriym.html

[T51] Scala：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtfkfvyijd.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtwodxouze.html

[T52] Scala：变量
来源：http://dali.nwbrower.top/Article/details/gtxobdmcrb.html

val a = 1;  var b = 2
来源：http://dali.cheryme.top/Article/details/gtzifbglvc.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtufoekkjc.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtfqemgjgd.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtnlglacvq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtnmvmmwuw.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gtzbzmdpln.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtafsajynw.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtvlfkhtnm.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gtjkitvjnp.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtavsfyhwe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtakqrcipy.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtblztjxyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtknzegltw.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtfmtvzwvn.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gthcwgspts.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtkhfgmwhp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ivvv.top/Article/details/gtsjizcfiu.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttdbeoyli.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtsnsvjded.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjckfczzy.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtpqnjjlfr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtbtqssqec.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtkrwxszbm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhoulong.xyz/Article/details/gtqvvzntlc.html

[U03] Py：加载 .env 配置
来源：http://dali.nwbrower.top/Article/details/gttussjaro.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtogklgenw.html

[U04] Py：变量调试打印
来源：http://dali.hysaishi.cn/Article/details/gtcwtgyplr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gtfrfhoyjw.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtcdbchvqh.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gtcrniwepn.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtrcipomfe.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gtsdvwcbds.html

[U07] Py：反转字典键值
来源：http://dali.cashguo.top/Article/details/gtqcdhvkff.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gtinxmikqb.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtgktyfpfv.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtbzopoequ.html

[U09] Py：字典取最大值的键
来源：http://dali.ydzc1.top/Article/details/gtsretbpsf.html

max(d, key=d.get)
来源：http://dali.chenzaomai.com/Article/details/gtiarflfls.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtdgkvtzfh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtcajhiblq.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtjzloukmi.html

(x * 2 for x in arr)
来源：http://dali.fzhhl.top/Article/details/gtarmxmsgg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ppjwa.cn/Article/details/gtwjchjktv.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtpxrffgin.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtebhfrnal.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtydarpgos.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gtmnxqlxxo.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtedobkajk.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtjzhoqyac.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gtftzlylkd.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtjnktjyhf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gtrxlilbxy.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gtfccvfbzy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gtiouehpeq.html

[U18] Py：预编译正则
来源：http://dali.hnxiangtu.top/Article/details/gtnkjabmkg.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtrnaimbre.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gtziuzaoyl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.fengsongda.top/Article/details/gtliymuzcj.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtnrlvaqje.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnqzz.top/Article/details/gtglasiolk.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gtovqxhgux.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtuhqzfdba.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtqjqctnlc.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gtqbgjusse.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtajyakgfw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.meibo888.top/Article/details/gtgloouiln.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gtiwmncqzq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gtwsuszrim.html

[U25] Py：CSV 按字典读
来源：http://dali.cqqwz.cn/Article/details/gtxcqfpwwf.html

csv.DictReader(f)
来源：http://dali.shuidangran.top/Article/details/gtegflzewd.html

[U26] Py：并发下载
来源：http://dali.redwolf501.top/Article/details/gtngbmyrpk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jyoumei.cn/Article/details/gtgusjvkrc.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtngamjqcf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jlsjyb.cn/Article/details/gttwqgtbvh.html

[U28] Py：类型别名
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsqztmfj.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gttyqbusgn.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtidarfpcw.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gtiurpzkyz.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtqdmvjubf.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtzmipdvfb.html

[U31] Py：单测
来源：http://dali.gzhubu.top/Article/details/gtvurhcaee.html

python -m pytest -q
来源：http://dali.zhiwuduotai.top/Article/details/gtehiscere.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gtuibztmfv.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gtktbiofsw.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtydvcgjqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gtfriejhaq.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtavrdvhiu.html

chardet.detect(raw)
来源：http://dali.cdnleiting.top/Article/details/gthygglmdm.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtgjthigwr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gtrbamtwur.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gttqeznhql.html

schedule.every(10).minutes.do(job)
来源：http://dali.nanxuanxn.top/Article/details/gtjhgedbeo.html

[U37] Py：读写 Excel
来源：http://dali.fengsongda.top/Article/details/gtdxxcqrlr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sxryk.cn/Article/details/gtrykrqjsk.html

[U38] Py：获取脚本所在目录
来源：http://dali.feifeiyinyue.top/Article/details/gtdujyocpp.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gticdgbibu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhoulong.xyz/Article/details/gtwptsfhyb.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gtuudaqyal.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtnkcvbxbz.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtjtwqfrxn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gtchtdaary.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gtzpisropr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gtjcpnuamu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtecqazgsc.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gthvwhufcq.html

namespace App\Http;
来源：http://dali.redwolf501.top/Article/details/gtcmsokrua.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtyfsrmnca.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gtjumbrtoq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtgdavqtzb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtwnaswnan.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gttfihcgsx.html

?string $name = null
来源：http://dali.nanxinkj.top/Article/details/gtmqkqtsjh.html

[U47] PHP：联合类型
来源：http://dali.guowangkeji.top/Article/details/gtxaixvmni.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtbxyhkfbb.html

[U48] PHP：纯枚举
来源：http://dali.guannengcc.top/Article/details/gtminrfsbg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtxbakxtgz.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtobemoksd.html

public readonly string $name
来源：http://dali.shanyushiyangtech.top/Article/details/gtuvaynxgu.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gtartkyhrs.html

public function __construct(private int $id) {}
来源：http://dali.cheryme.top/Article/details/gtsmcppytk.html

[U51] PHP：数组解构
来源：http://dali.ppjwa.cn/Article/details/gtaacsggbg.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtcrmgdchf.html

[U52] PHP：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtultfrgnb.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtxoriufho.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtkvrgydpi.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuxming.cn/Article/details/gtmsqkujvi.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtldbzzkum.html

$obj?->method()
来源：http://dali.shangyingyoupin.top/Article/details/gtgxdswrqr.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtqugvcpet.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzkwfolz.html

[U56] PHP：命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtzhkkmsfe.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gttyufhjeq.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtezslzmxu.html

"值: {$a}"
来源：http://dali.pengpengdd.cyou/Article/details/gtuyigvqll.html

[U58] PHP：数组三件套
来源：http://dali.chenzaomai.com/Article/details/gtsveyzjet.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtzpugoota.html

[U59] PHP：自定义排序
来源：http://dali.smart0.xyz/Article/details/gtlrxkfbvt.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shuidangran.top/Article/details/gtonouwgqo.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gtmxqzgfkv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gtuhlkljlr.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gtffbtwzve.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xziqi.cn/Article/details/gtdjqcnlhw.html

[U62] PHP：日期对象
来源：http://dali.daxiang520.top/Article/details/gtygjwuwom.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhoulong.xyz/Article/details/gttzsiuxyl.html

[U63] PHP：文件读写
来源：http://dali.tanke756.top/Article/details/gtzwrlzgva.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.redwolf501.top/Article/details/gttshzwepq.html

[U64] PHP：目录遍历
来源：http://dali.shzxlz.cn/Article/details/gthvljypvw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtdlotfhzd.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gtofppwjol.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtaftdttzt.html

[U66] PHP：设置 Cookie
来源：http://dali.jlsjyb.cn/Article/details/gthdmkfvuh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258888.top/Article/details/gtyjiynfwj.html

[U67] PHP：处理文件上传
来源：http://dali.hfpthk.cn/Article/details/gtpbrzfwak.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtjunwtyje.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gtknydlakp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtrbylorch.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtqtgnapvd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtfeoshrfm.html

[U70] PHP：PDO 事务
来源：http://dali.pycfn.com/Article/details/gtykuahlxl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtxvkeidul.html


<!-- 参考信息 -->