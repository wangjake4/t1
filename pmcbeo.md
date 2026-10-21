代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtnkzrlenu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtbrqydovc.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gteqsoioko.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtsubhknkl.html

while (std::getline(in, line)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtutwpwnyv.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtaayvpaen.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtobdnjefp.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtneixgssb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtcgbnhygl.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtupnamvhv.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtothxrchc.html

[S52] C++：const 与 noexcept
来源：http://dali.jlsjyb.cn/Article/details/gthddluyay.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtpmnbfqca.html

[S53] C++：移动语义
来源：http://dali.daria6918.cn/Article/details/gtdljqyyow.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgzafclr.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtmwioitvl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtbwafklek.html

[S55] C++：结构化绑定
来源：http://dali.snrcjt.cn/Article/details/gtkwsxusbp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gthcdwbysw.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtszolqkpo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtrryiehcp.html

[S57] C++：编译期常量
来源：http://dali.zdqjudy.top/Article/details/gtngipnzyb.html

constexpr int N = 10;
来源：http://dali.yvedp.cn/Article/details/gtrlskekqx.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthviviehr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbimjvgy.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtgrulnmye.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shzxlz.cn/Article/details/gtjydhwbrp.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtexraxsrz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtylwhffgq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtqopclyei.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpihlvmo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtfomiaxlj.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbgjfljaq.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtvvheyqrq.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gtyxkxmdoq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtvuelgthk.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gtfjihzpmx.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcfbvvaaq.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtxgebntih.html

val n: String? = null;  n?.length
来源：http://dali.xuanzx.com/Article/details/gtxtaqtvnd.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtekvmhhjt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gtbogwdtbg.html

[T06] Kotlin：集合映射
来源：http://dali.c1oappe.top/Article/details/gtjlbyecbd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtwmkxokgb.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gtnvbrurvs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258888.top/Article/details/gtiupbrvvt.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtvpdjtfyz.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gthqwsmvww.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gteghmmtqq.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtupnownva.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtfxiuefie.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gthmiemuog.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gtjlhtsltq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtzaarjxgr.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtaofmokwt.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtlfiwdvma.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtlmphbrxt.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtisbefndt.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtuubwltks.html

for (i in 1..10) println(i)
来源：http://dali.zhoulong.xyz/Article/details/gthrlcudtb.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtfvljxewf.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gthvkaiomj.html

[T16] Swift：Hello World
来源：http://dali.yj20258.top/Article/details/gtzzdsidwr.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtsiktxvmg.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtsxtplwym.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtwcryzsgf.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtummvdyqc.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtcwdtpvan.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtgwmklfgx.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtxflrxerv.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtfqjyfpje.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gtbmqycqis.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtadyrjzjk.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtbflhhuhq.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gtfsygraur.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gtrghxjpmr.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtykcqlake.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtfhgurgiy.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtldsiyovx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtzhvpxmno.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtcunektgk.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gtnrcaihbj.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gtrkthewow.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtyvngebpj.html

[T27] Swift：错误处理
来源：http://dali.hywenlv.cn/Article/details/gtinrwnbbw.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtyoeffxhr.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtudxlabsl.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyvollncu.html

[T29] Swift：guard 提前返回
来源：http://dali.xylfe.cn/Article/details/gtfoljdwzc.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtnggnplgm.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtavdsludu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gtgtwgjkhg.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtwinxjbsi.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtydstjfjl.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtbvceqhxt.html

local a = 1
来源：http://dali.ivvv.top/Article/details/gtkbkrpnrd.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtyxxvxrxy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtnmdmfkim.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtrodwbfzk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtsbpgcuds.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gtojzutqjp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gtkvsdjsos.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtufdcyziy.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gthnqxecjk.html

[T37] Lua：字符串拼接
来源：http://dali.ybcxt.top/Article/details/gtuxhbrcyg.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtnjsrmyda.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtgnrqpdcs.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtscdhjxdr.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtyiaymogz.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gtpmavurbm.html

[T40] Lua：元表
来源：http://dali.shanyushiyangtech.top/Article/details/gteqolkxek.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtjdsdepih.html

[T41] Perl：Hello World
来源：http://dali.yonumen.top/Article/details/gtpyvtealg.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gttemugjza.html

[T42] Perl：变量类型
来源：http://dali.yuanzhike.top/Article/details/gtvqaitpec.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtfxipevei.html

[T43] Perl：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gthwzpytza.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gttcablukt.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsztalic.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtpjgaacfa.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtlvyabuke.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtkmbinvva.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtlhxkmznr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtkudieeqs.html

[T47] Perl：正则捕获
来源：http://dali.hnqzz.top/Article/details/gteplmesyv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gtktjlsmky.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtdjipulbn.html

$s =~ s/old/new/g;
来源：http://dali.guannengcc.top/Article/details/gtnzqqywaz.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gttfmzdnzl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtwyofacvw.html

[T50] Perl：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtkefwhxze.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtpubnywxp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfayjbovv.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtujlrwzrj.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtphlyeelg.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gtsvjepctu.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtmugsbfcs.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtxxzmoimr.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gttznouohb.html

[T54] Scala：集合映射
来源：http://dali.yj20258.top/Article/details/gtjkogevpv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gtakohpiof.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtbcxwpxsf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtkejxrdey.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtzrahnklu.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtfqczeqfi.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtwkxdsakj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtptprifjz.html

[T58] Scala：函数定义
来源：http://dali.jinqigfzy.top/Article/details/gtcmkmmsfm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtiuhcplap.html

[T59] Scala：循环
来源：http://dali.nanxinkj.top/Article/details/gtzufbiorl.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gtzhdhlefi.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gtqwvrjanh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gteuaiemfo.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtdmuqryfb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtspfbvaqu.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtcksatqep.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesvoocpe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtrqxbygrc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gotoacloud.top/Article/details/gtkrmnahrk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hammf.cn/Article/details/gtpwcdyzue.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gtvuoyhodf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtpnhptkuw.html

[U04] Py：变量调试打印
来源：http://dali.316326.xyz/Article/details/gtzxlbnvfw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnxiangtu.top/Article/details/gtuuodebsv.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gtujneqycn.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtsqcuizzi.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtufmrflxt.html

{**a, **b}
来源：http://dali.meibo888.top/Article/details/gtzaybhexx.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gtxhuprpjb.html

{v: k for k, v in d.items()}
来源：http://dali.zhoulong.xyz/Article/details/gtvzdstkyl.html

[U08] Py：展平二维列表
来源：http://dali.meibo888.top/Article/details/gtdmidnnww.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtjtdbbzcc.html

[U09] Py：字典取最大值的键
来源：http://dali.yvedp.cn/Article/details/gtpekwlysy.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gtrrxwzdtg.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gtlydteemm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangshuangyany.cn/Article/details/gtvbpisbxw.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtsqbhacyg.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtcssxauxz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gtggspbbzi.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gteutggqrn.html

[U13] Py：固定长度队列
来源：http://dali.yongpay.top/Article/details/gtgieyvwgf.html

deque(maxlen=10)
来源：http://dali.hnqzz.top/Article/details/gtvlrvspcg.html

[U14] Py：分组收集到列表
来源：http://dali.jqgfzy.top/Article/details/gtsjehhncu.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtzzagmsna.html

[U15] Py：高精度计时
来源：http://dali.gogol.net.cn/Article/details/gtxaztqzmm.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtenvnnvko.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtlmziolff.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gtcimtfrew.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gtafuueywv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ehwqpu.com/Article/details/gtnontcypn.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtfgeregab.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtbrfgxzga.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gtjaxptjlp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gttmzeaylj.html

[U20] Py：缓存函数结果
来源：http://dali.aizwys.cn/Article/details/gtnxrnqtdw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtdthnwkrb.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtdiyofnlh.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtdpndnotw.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtlvnigtxu.html

list(zip(*m))
来源：http://dali.redwolf501.top/Article/details/gtkgapbsnn.html

[U23] Py：分块读取大文件
来源：http://dali.ppjwa.cn/Article/details/gtjffisnjb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjaowyijk.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gtnzfuqonm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gtunebmhba.html

[U25] Py：CSV 按字典读
来源：http://dali.fzhhl.top/Article/details/gtaptpaxig.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtubbpquoy.html

[U26] Py：并发下载
来源：http://dali.fzhhl.top/Article/details/gtiyyzegms.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtslxhyfve.html

[U27] Py：异步 HTTP
来源：http://dali.xuanzx.com/Article/details/gtpuabdjtc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gthmoqeqou.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gtcsgvxoeh.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtwouioxlb.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtykefmcej.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtecyzkvue.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gtcfsgkbem.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gtufxijxdh.html

[U31] Py：单测
来源：http://dali.pycfn.com/Article/details/gtwihrcyof.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gtxvcjpyuz.html

[U32] Py：代码格式化
来源：http://dali.jiagoushi.top/Article/details/gtnibhroqh.html

ruff format . && ruff check --fix .
来源：http://dali.zhixingplan.top/Article/details/gtgcjkbtev.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtubggayjv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aibaodan.cn/Article/details/gtakrnrtwy.html

[U34] Py：判断编码
来源：http://dali.jqgfzy.top/Article/details/gtusgcexjh.html

chardet.detect(raw)
来源：http://dali.hfpthk.cn/Article/details/gtxupfkxrp.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtquksuice.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtxnfxovcj.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gtaadlcsbd.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gtdnbodkhf.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gtykwrbpll.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gthgtcgxzh.html

[U38] Py：获取脚本所在目录
来源：http://dali.sxryk.cn/Article/details/gtewgfezah.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtzcgxfgiv.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtbzxszfeh.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgasrhsv.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gtvpsjwpfq.html

print("err", file=sys.stderr)
来源：http://dali.ydzc1.top/Article/details/gtparlxger.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbzdybzmn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuetiantiany.cn/Article/details/gtceiokoak.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnqzz.top/Article/details/gtkbtclwag.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gtapefyhla.html

[U43] PHP：声明命名空间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnfhxhir.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gtjhgocvbd.html

[U44] PHP：开启严格类型
来源：http://dali.zhongyouzk.top/Article/details/gtwwivzvht.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtxsajjahn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258.top/Article/details/gtgaxgenob.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtkxwtnxea.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gtokzeqjsq.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gtcxtuxbeb.html

[U47] PHP：联合类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhpiedie.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gthaovfdlf.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtnldkyoih.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtsemqimcn.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtimynntcd.html

public readonly string $name
来源：http://dali.yueranfly.top/Article/details/gtqdlhdist.html

[U50] PHP：构造器属性提升
来源：http://dali.xylfe.cn/Article/details/gtzxbordcw.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtjhvsdbfg.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gtxtdgnwtx.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gtoerxuegr.html

[U52] PHP：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gthjrthiza.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gthqebtiky.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtleeureeu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtvrnguifh.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gttluphpoa.html

$obj?->method()
来源：http://dali.ehwqpu.com/Article/details/gtfbgkupch.html

[U55] PHP：match 表达式
来源：http://dali.cqqwz.cn/Article/details/gtgihjuvek.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtpjazhvyi.html

[U56] PHP：命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjfvgifng.html

f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtelzfmyzd.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtntadmbxz.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtoppoaslq.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gtmfgszkca.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtvpdmjayu.html

[U59] PHP：自定义排序
来源：http://dali.yuanzhike.top/Article/details/gtejbdtvrs.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtnihxpddp.html

[U60] PHP：JSON 编解码
来源：http://dali.guannengcc.top/Article/details/gtpbmlkizb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnxiangtu.top/Article/details/gtfcfkfsus.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtqpbihtpj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.c1oappe.top/Article/details/gttflgtymb.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtmjfnkouf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtqagjeqty.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gtzfirzfib.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gtmfspowfc.html

[U64] PHP：目录遍历
来源：http://dali.chenjidiqi.icu/Article/details/gttwcigskf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtydozecxu.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gtyukuhdxq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtqbdfbrhw.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gtqtpkrapf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxizmxpp.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gtijwygqcb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ybcxt.top/Article/details/gtpnzbeugg.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtlgbnoucu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gtowdcswrx.html

[U69] PHP：PDO 预处理
来源：http://dali.tanke756.top/Article/details/gtknksbqnn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gtzypbxllf.html

[U70] PHP：PDO 事务
来源：http://dali.yangfankeji.com/Article/details/gtucgmeaey.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gtxovfhrze.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gthipyalsn.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gttougtmmb.html

[U72] PHP：写错误日志
来源：http://dali.vqdsnc.cn/Article/details/gtqlxiutgy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnxiangtu.top/Article/details/gtzzinrpkw.html


<!-- 参考信息 -->