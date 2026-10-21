代发 wailian999

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtbdejmnue.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtfgisckie.html

[S48] C++：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtxyyzleaa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtlqupanel.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtqdxslrjg.html

[S49] C++：写文件
来源：http://dali.c1oappe.top/Article/details/gtbmahdlgb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shuidangran.top/Article/details/gtslqukmut.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtzccrplld.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gtqzfgajvv.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtbsxrovcr.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtwbnvbmxs.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtnnhbxxjy.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbutaitos.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtcnkrcsig.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtrktcdgjl.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtpyxxfmpu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtmhpikuif.html

[S55] C++：结构化绑定
来源：http://dali.daria6918.cn/Article/details/gtsqumytcy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtdmeystbq.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtphkqmdup.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtgvbbhvue.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtggktdkpm.html

constexpr int N = 10;
来源：http://dali.0kj1m.cn/Article/details/gthkgxwpuf.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtmisqlepg.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtwbbkfpst.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangtech.top/Article/details/gttnimdlnx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagfbkxbh.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtotclnwhz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtgdewirqx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtkivixsdf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtebornppz.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gttsrvposu.html

[T01] Kotlin：Hello World
来源：http://dali.xylfe.cn/Article/details/gtbamnztio.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtzllrlxla.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtbtokoezx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gtmgvbkzvd.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gtlsggjvbx.html

"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtnhibourc.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtklqqrsdp.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtfrzlhleg.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gtugflvpcv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtwetroukx.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtansxaugz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtlobwosao.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfoqbhfmg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.meibo888.top/Article/details/gtfrvsttll.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjiyrwprh.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtcxvbaxfo.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtjfweavzv.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtqjzgkyze.html

[T10] Kotlin：默认参数
来源：http://dali.ivvv.top/Article/details/gtyzxvbsvy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtjslacrfy.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwbwooqn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tanke756.top/Article/details/gtkzkwvkkn.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtbximvvch.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtxkmcfhkf.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtroiyrtca.html

val m = mapOf("a" to 1)
来源：http://dali.yj202588.top/Article/details/gtnqmwshgu.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtjqmsullk.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtzasplxtq.html

[T15] Kotlin：接口
来源：http://dali.cashguo.top/Article/details/gtadttnaif.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtsedmkeyh.html

[T16] Swift：Hello World
来源：http://dali.daria6918.cn/Article/details/gtytuercta.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtukyxtdfc.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtevxsjckg.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtievuewth.html

[T18] Swift：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtvibvhkzi.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtbutocxlt.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtedeewcft.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtohajdwsu.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtvzexklkv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtiwvzyqwa.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtmwjpopmi.html

for x in a { print(x) }
来源：http://dali.snrcjt.cn/Article/details/gtdvhixzia.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtuabthkyp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.smart0.xyz/Article/details/gtlplsmtnh.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtqyyomzkx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtffnhyrmj.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtqrexajdn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtlficprbg.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gttehqpeuy.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtgaiqlvqz.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtyllknbof.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtpbdpyjtb.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtxocwwzxj.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwsfgiyp.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtdylpzzem.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtfctmtjyu.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtnmwkxznb.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtjrgcolpa.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtxfzkliki.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtlebboesh.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtyxrqyauw.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtlwnmjfdz.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gtyqndjszy.html

local a = 1
来源：http://dali.jinqigfzy.top/Article/details/gttpfnqspf.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvluzlkt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtgyqvtunp.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gthnptnseq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtmwbzoyiz.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtykdtxapl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gtfqwxiaax.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtwxejwtpv.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gttimczzqx.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtdsyfmywn.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gtwlpzzptl.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtcggymvgu.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gtnpioyemm.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvyhxrza.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtpzvpdvwt.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gtinlkfblk.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gtcahiyepp.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtnjrzdvkq.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtblualehg.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtrepphfft.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtdtmhrxim.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtrxtkxhhm.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtspwljyvr.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtzfbeerjh.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gtnsidhjhj.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gtrujdvxhu.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtumvtzaic.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtzfvtwbfa.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.316326.xyz/Article/details/gtvjhcexir.html

[T47] Perl：正则捕获
来源：http://dali.tian-w.cn/Article/details/gtvncjisva.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ehwqpu.com/Article/details/gtwchaligg.html

[T48] Perl：正则替换
来源：http://dali.hysaishi.cn/Article/details/gtzlgvbliy.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtzxmxcvud.html

[T49] Perl：函数
来源：http://dali.sysykeji.top/Article/details/gtgyignsbf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtjkelvcsp.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtqsumzdxm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtdlrrfhlf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaanztjlh.html

[T51] Scala：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtqzwtryma.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtwhfgywwd.html

[T52] Scala：变量
来源：http://dali.tian-w.cn/Article/details/gtdladqxrb.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtomhmsple.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtyhoorajv.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfjjprbx.html

[T54] Scala：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtidapudph.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtuugykzcr.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtgrtbchlt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gtyegttjuz.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangtech.top/Article/details/gtalotzvjd.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtaflqsuqc.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gttiqodtnz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtuqemobbb.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtrwkvkbao.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtkhwwblse.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtnhylukrk.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtzzyqlyfx.html

[T60] Scala：折叠
来源：http://dali.smart0.xyz/Article/details/gthaycqcvm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtjqhdenuy.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtmsgkgjts.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.sufxvd.cn/Article/details/gtkjfodxof.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtbzmxbxtw.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtcnsvjkuj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gaohongyu789.top/Article/details/gtjitzvtvu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtqymtyxja.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtpgrgjsaj.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gthbtigava.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gtznrkrvwy.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtskeojfew.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtwvnsxuff.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtohbsvdrz.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtrrfjxzsc.html

[U06] Py：合并两个字典
来源：http://dali.quarkkingdee.top/Article/details/gtmxhmqaop.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtmygglnvy.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtodyuzkik.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtyvmibkdn.html

[U08] Py：展平二维列表
来源：http://dali.xinyue.icu/Article/details/gtqvifpvjq.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gtdgjlainu.html

[U09] Py：字典取最大值的键
来源：http://dali.xuetiantiany.cn/Article/details/gtgxfvdtae.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtanpljpta.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtzzfaoijc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtmreodocl.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gtayxbkplx.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtalxrfmpk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenjidiqi.icu/Article/details/gtyeogjlli.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtgcwewlkl.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gtwokutwne.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtqhiibeqv.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtoeifbjfa.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtiunzsxym.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gtfgpijchf.html

t = time.perf_counter()
来源：http://dali.smart0.xyz/Article/details/gtbyforshe.html

[U16] Py：命令行参数解析
来源：http://dali.xuanzx.com/Article/details/gtrmuvpjoe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtniqibfux.html

[U17] Py：初始化日志
来源：http://dali.iojbl.cn/Article/details/gtbbrnijek.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gtdnaahaal.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtqpjxfugg.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtebzopiaj.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gtbqycsucy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gtwfbzhapc.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtpscmctoa.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nanxuanxn.top/Article/details/gtcrqfwxdj.html

[U21] Py：自定义上下文管理器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjjrqnaw.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gtrsvncpqe.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzbtmkpv.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gtbuzpyiob.html

[U23] Py：分块读取大文件
来源：http://dali.zhoulong.xyz/Article/details/gtkurwuxld.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fengsongda.top/Article/details/gtksbboted.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gtkqiiezii.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtnfrcomsk.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwkupkogm.html

csv.DictReader(f)
来源：http://dali.sxryk.cn/Article/details/gtcoteniny.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gteuqlwxvy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hywenlv.cn/Article/details/gtcfacvjul.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gtdjkhgsoz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtrbuzvstv.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtiogzlgag.html

UserId = int
来源：http://dali.hfpthk.cn/Article/details/gtvhxeyeaj.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gttxtpxkiu.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtbcarntiz.html

[U30] Py：数据类
来源：http://dali.hysaishi.cn/Article/details/gtbvbcglph.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtiyoudgmf.html

[U31] Py：单测
来源：http://dali.jqgfzy.top/Article/details/gtomreiijq.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gtidnvgbas.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gtgmigyjvn.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gtqquonmoe.html

[U33] Py：打包发布
来源：http://dali.dashuyun.cn/Article/details/gtwueeyjuu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtifdqsdmb.html

[U34] Py：判断编码
来源：http://dali.ybcxt.top/Article/details/gtqjfuooms.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuctjvbn.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtyyfltnow.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.svipenyu.cn/Article/details/gthxbjsgmj.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtlbieaylk.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gtxaqrqhzk.html

[U37] Py：读写 Excel
来源：http://dali.cucudq.cn/Article/details/gtyjwmsgmv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangtech.top/Article/details/gteuyifvgy.html

[U38] Py：获取脚本所在目录
来源：http://dali.haohaochexian.top/Article/details/gtfpmisomg.html

Path(__file__).resolve().parent
来源：http://dali.smart0.xyz/Article/details/gtsuvhvbve.html

[U39] Py：判断是否在交互环境
来源：http://dali.9152youxi.cn/Article/details/gtqgayywuh.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gteewpwgtc.html

[U40] Py：打印到标准错误
来源：http://dali.xinyue.icu/Article/details/gtceytgbfu.html

print("err", file=sys.stderr)
来源：http://dali.yuanzhike.top/Article/details/gtzrzyejku.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gttecesbpd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sweek.top/Article/details/gtskmioefd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtxekqinei.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gtgeuvachj.html

[U43] PHP：声明命名空间
来源：http://dali.yuanzhike.top/Article/details/gtnpvfmdki.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtshdhcpuh.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gtxaljrhbn.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtnjawfgbl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gtvxhlartm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtkcrakhpb.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtgwwqngig.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gthstmwglp.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gtkpvukbjz.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gtaxccsidt.html

[U48] PHP：纯枚举
来源：http://dali.chenlongwang.top/Article/details/gtlscfgimz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfyymbkfh.html

[U49] PHP：只读属性
来源：http://dali.jinghuilouyu.cn/Article/details/gtjhemyotq.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gtpabrneem.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtwzupusyb.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gtvdltamqx.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtsaxecxtc.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtseviorhk.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtnmsbjjzm.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtramdvkjv.html

[U53] PHP：空合并运算符
来源：http://dali.yj202588.top/Article/details/gtkculuiob.html

$v = $a ?? $b ?? "default";
来源：http://dali.hfpthk.cn/Article/details/gtchraypnn.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtxbtvkkdw.html

$obj?->method()
来源：http://dali.hfpthk.cn/Article/details/gtklrhgxuw.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gtuhqdufrs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pengpengdd.cyou/Article/details/gttzehnkif.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gtnmceppav.html

f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtqxedbeyk.html

[U57] PHP：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtckddpklw.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtowduicbs.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtamrhbkln.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtqfpxwzxo.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gtgipdoxwr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtakittjcw.html

[U60] PHP：JSON 编解码
来源：http://dali.gotoacloud.top/Article/details/gtxchdlwim.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtczdionnz.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gtthilriks.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhongyouzk.top/Article/details/gtaklwdtnz.html

[U62] PHP：日期对象
来源：http://dali.jiagoushi.top/Article/details/gtmbbqgdqi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gtbewedfgc.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gthhdvfble.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtihgowffn.html

[U64] PHP：目录遍历
来源：http://dali.yj202588.top/Article/details/gtfstierky.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtwvcnzomt.html

[U65] PHP：会话
来源：http://dali.mhx1999.top/Article/details/gteaflasxe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtvewznfan.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gthylqzmkp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwsnwfab.html

[U67] PHP：处理文件上传
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmnpjvxu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yuxming.cn/Article/details/gtwvadmyzx.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtuaffbmcv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cashguo.top/Article/details/gtuvwbwsox.html

[U69] PHP：PDO 预处理
来源：http://dali.zycfv.cn/Article/details/gtmjfjccli.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gthjrbxlpp.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklxpnztg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.daxiang520.top/Article/details/gtnykbmlfw.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtwcenuhlp.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtfjxblmcg.html

[U72] PHP：写错误日志
来源：http://dali.mhx1999.top/Article/details/gtainetpgc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtrybeswez.html


<!-- 参考信息 -->