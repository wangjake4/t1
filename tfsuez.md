代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtbtegsccq.html

[S53] C++：移动语义
来源：http://dali.cheryme.top/Article/details/gtppkukoei.html

std::vector<int> w = std::move(v);
来源：http://dali.ivvv.top/Article/details/gtewamndil.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtqhccwyzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjpfoeqh.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtgvndrspu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiptppni.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtqymtncxn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtxypweydl.html

[S57] C++：编译期常量
来源：http://dali.jqgufenzy.top/Article/details/gttcrohrlt.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtvmudkxdx.html

[S58] C++：命名空间
来源：http://dali.aibaodan.cn/Article/details/gtmdipbxgc.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtevkipnvh.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtngobqifz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtotyfipyd.html

[S60] C++：遍历并删除元素
来源：http://dali.smart0.xyz/Article/details/gtdgjulnex.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtuzrrkepx.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpmisyvqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtsrqmlliu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdibneefl.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtqdeppoot.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtavswyspt.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtdgucjvxu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yueranfly.top/Article/details/gtumsqqpiz.html

[T03] Kotlin：字符串模板
来源：http://dali.zdqjudy.top/Article/details/gtfnnoltba.html

"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gtxsaotaje.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtslvlvhnd.html

val n: String? = null;  n?.length
来源：http://dali.guowangkeji.top/Article/details/gtruicgxxm.html

[T05] Kotlin：when 表达式
来源：http://dali.sweek.top/Article/details/gtmaaasqcd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtnsolaivh.html

[T06] Kotlin：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtdbtojxmi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtaatqtcdw.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtilrpfqhu.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtgbjpdedz.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmgeoaob.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gthfmyshcj.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtjqfyfwlx.html

fun String.exclaim() = this + "!"
来源：http://dali.wangshuangyany.cn/Article/details/gtnuvjmatk.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtkdivftvk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sufxvd.cn/Article/details/gttuihvvio.html

[T11] Kotlin：协程
来源：http://dali.dashuyun.cn/Article/details/gtjqxfnkqz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gtisnkfaoy.html

[T12] Kotlin：解构声明
来源：http://dali.dashuyun.cn/Article/details/gtycihvjvt.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtaxgisfge.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtmxggpdzd.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gtqgqrwdwy.html

[T14] Kotlin：循环
来源：http://dali.aibaodan.cn/Article/details/gtqppcedgs.html

for (i in 1..10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtzrbkklel.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtbvmhtxpo.html

interface Shape { fun area(): Double }
来源：http://dali.gogol.net.cn/Article/details/gtzslsahyk.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtlwyjdavm.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtcrvqltnb.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtajlxnipc.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtmvbgzmus.html

[T18] Swift：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtawqqhvjm.html

"值: \(b)"
来源：http://dali.zhoulong.xyz/Article/details/gtbyykrqem.html

[T19] Swift：可选绑定
来源：http://dali.hfpthk.cn/Article/details/gtfvfpsuse.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gtdlqiqhpw.html

[T20] Swift：数组操作
来源：http://dali.shzxlz.cn/Article/details/gtgvsrdaae.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtgtmseeqh.html

[T21] Swift：遍历
来源：http://dali.hnqzz.top/Article/details/gtidixnhla.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtyggpfuuw.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gteakopfvm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fengsongda.top/Article/details/gtfrcifvoq.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtxfxsyxan.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtjnrhncys.html

[T24] Swift：闭包
来源：http://dali.hongshengwenyu.top/Article/details/gtxlottqvo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtamfihaim.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzqrgvfid.html

struct P { var x: Int }
来源：http://dali.ehwqpu.com/Article/details/gtzzkyouiz.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtlmiizcuq.html

class A: Base { override func f() {} }
来源：http://dali.smart0.xyz/Article/details/gtofjgdfhj.html

[T27] Swift：错误处理
来源：http://dali.quarkkingdee.top/Article/details/gtnvuuzfid.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtopoflynj.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtepvfkday.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtundxsroh.html

[T29] Swift：guard 提前返回
来源：http://dali.xziqi.cn/Article/details/gtmosfmthq.html

guard let x = opt else { return }
来源：http://dali.hfpthk.cn/Article/details/gtcdpiexgl.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtlemhxzuh.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gtgfxvbjhh.html

[T31] Lua：Hello World
来源：http://dali.yj20258.top/Article/details/gtbenomtmy.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtsmldvowo.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtmxwsomld.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtllumgtot.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtzwjljycu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gtvvgumejf.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gtpcftmofh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtifsvipfo.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtrbhzzwes.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtcnhyajjv.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gtnzhezpyk.html

function add(a, b) return a + b end
来源：http://dali.snrcjt.cn/Article/details/gtncwcpica.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtplmlvcuf.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtqryiyjuq.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gtlyfufwgi.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gttguvpdyf.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gtyacnmmbm.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtqjbgvzzv.html

[T40] Lua：元表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflnrsdrb.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtvheduxbd.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbadwcofo.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtxwvgpcxl.html

[T42] Perl：变量类型
来源：http://dali.yj202588.top/Article/details/gttxzdrjts.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtmyxiyimk.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtdikealql.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtrklsxvvk.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtdchhchob.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyworpgxm.html

[T45] Perl：数组遍历
来源：http://dali.meibo888.top/Article/details/gtxajckblr.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtvnxqtnsx.html

[T46] Perl：哈希操作
来源：http://dali.gaohongyu789.top/Article/details/gtfxkdyuig.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sysykeji.top/Article/details/gtghsfkasl.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtqyyypdcc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtfuremtfq.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtkrcvvuzh.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gterzltuhw.html

[T49] Perl：函数
来源：http://dali.sxryk.cn/Article/details/gtpvsaegnl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtjdnbrwry.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtrpjnftav.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtesrnrnwu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtfixvbmxo.html

[T51] Scala：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtluzvlabx.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtgzwkounk.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtqdawypzu.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwbwopcyx.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtiglthjag.html

s"值: $b"
来源：http://dali.nanxuanxn.top/Article/details/gtzviklhid.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtxlsxjszt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gtpzgbfqpc.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtxhqohsfy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtwtptlvzk.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtpgxnexvv.html

case class User(name: String, age: Int)
来源：http://dali.hfpthk.cn/Article/details/gtikdrequa.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtrdmwyyab.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtccrwxeli.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtvyulyizc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gtfpsixvfm.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtykqdqfrm.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtpdokloct.html

[T60] Scala：折叠
来源：http://dali.dianchejie.cn/Article/details/gtzshdhuah.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtnxmoupmb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtsmpypweq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtaidtltpz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtkltughdk.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtnxqqvijz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtamodcepd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.iojbl.cn/Article/details/gtbgycfxdq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtslpbxsnd.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gtdmsacbsi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guannengcc.top/Article/details/gtndsxrvbl.html

[U04] Py：变量调试打印
来源：http://dali.svipenyu.cn/Article/details/gtciuiswhg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gtufvkmkcg.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gtzzfgftvz.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtgkltzpvh.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtnqtigqhk.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gtleyhvpgi.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gtreqrghfb.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtlpfxgvoy.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gtnzaeesyi.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbpwrfbf.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtggrliccu.html

max(d, key=d.get)
来源：http://dali.sweek.top/Article/details/gtivbpjrsu.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtqkjimujn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtwakclmbj.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtptbsxxvn.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtojxmnhlp.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gtobyvkpxx.html

Counter(arr).most_common(3)
来源：http://dali.yanxiufei.cn/Article/details/gttkxxeywf.html

[U13] Py：固定长度队列
来源：http://dali.smart0.xyz/Article/details/gtjyvpuowv.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtabloahnw.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtbmoojxev.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gtmihhnthh.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpzmxqmm.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtuugdxlwu.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gtqzqrbzfp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gtiyryivil.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtxevkxnsp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtbybknpuw.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gtmqrndoyo.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtqadrzkfc.html

[U19] Py：正则替换带回调
来源：http://dali.dianchejie.cn/Article/details/gtglqwtycj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtpohllnir.html

[U20] Py：缓存函数结果
来源：http://dali.kuanghao11.cn/Article/details/gthvjrlifc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtlmiirtbf.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtqfaipven.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gtuhyyhuvx.html

[U22] Py：矩阵转置
来源：http://dali.quarkkingdee.top/Article/details/gtcckgoaau.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gtuppgwyca.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtqjvuyxob.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gtcrlfqseq.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtqiqxgmuq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangdashe.top/Article/details/gthgarnmba.html

[U25] Py：CSV 按字典读
来源：http://dali.hongshengwenyu.top/Article/details/gtasxxvtdp.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gthplkuxbo.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtlloqtevj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gteenlimum.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtqdjihuvb.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtceczqfgq.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtyqaqtndt.html

UserId = int
来源：http://dali.andypj.xyz/Article/details/gtujyiklyh.html

[U29] Py：属性校验
来源：http://dali.dashuyun.cn/Article/details/gtbtujtmqx.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtmybwoaky.html

[U30] Py：数据类
来源：http://dali.cashguo.top/Article/details/gtrezdnbtd.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtfcqfeyse.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtcmrnerpb.html

python -m pytest -q
来源：http://dali.xinyue.icu/Article/details/gttxpoliqe.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjvczidm.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtgywwoztg.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtjwzdcuge.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gtsbjmxesu.html

[U34] Py：判断编码
来源：http://dali.ppjwa.cn/Article/details/gtttmpillq.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gttrjirxyo.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtjwdtuzcv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gtvlfvioka.html

[U36] Py：定时任务
来源：http://dali.cdnleiting.top/Article/details/gtoafkinpg.html

schedule.every(10).minutes.do(job)
来源：http://dali.birdmap.top/Article/details/gtantjihmt.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gtqgxktsxp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenzaomai.com/Article/details/gtruofgzex.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtjigpegph.html

Path(__file__).resolve().parent
来源：http://dali.nanxuanxn.top/Article/details/gtvwqbysni.html

[U39] Py：判断是否在交互环境
来源：http://dali.pengpengdd.cyou/Article/details/gtxhucqkfp.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gthjhvgsjj.html

[U40] Py：打印到标准错误
来源：http://dali.guannengcc.top/Article/details/gtydxzysau.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gtpufudgfn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sweek.top/Article/details/gtfngxtfxy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtusyqtkmh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysrgarwa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daxiang520.top/Article/details/gtfizlfmfw.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtrtcqitvh.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gtjycokcfi.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gtcyufjuue.html

declare(strict_types=1);
来源：http://dali.xuetiantiany.cn/Article/details/gttpuxebxt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gteglbbtac.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtjilawjfk.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtbcyizmyb.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gtthklknnq.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqhgdagk.html

int|string $id
来源：http://dali.jinqigufen.top/Article/details/gtgbmeofce.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtsxfcyeqs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.daria6918.cn/Article/details/gtzjzafske.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtirikjfvu.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gttxqdkxux.html

[U50] PHP：构造器属性提升
来源：http://dali.cucudq.cn/Article/details/gtpphvhcte.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtjlpdiluf.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtkocpwtpl.html

[$a, $b] = $arr;
来源：http://dali.yj20258888.top/Article/details/gtiukrbuwv.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gteisqpmxu.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gtmtoafddn.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gtxzogcgxv.html

$v = $a ?? $b ?? "default";
来源：http://dali.jqgfzy.top/Article/details/gtbvyrxffb.html

[U54] PHP：空安全调用
来源：http://dali.sysykeji.top/Article/details/gttmudhygn.html

$obj?->method()
来源：http://dali.cheryme.top/Article/details/gtmzoptuov.html

[U55] PHP：match 表达式
来源：http://dali.jianghu66.top/Article/details/gtpunzeukk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbaxrfcrv.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtxlqqahea.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqhomizap.html

[U57] PHP：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtqmoruwxe.html

"值: {$a}"
来源：http://dali.aizwys.cn/Article/details/gtqvwaftru.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gtejmtsyhe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gtcyaunkfv.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtoluzsoll.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqglecvzy.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gtezyaepjn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gttxlaytvs.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtryifuxae.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yvedp.cn/Article/details/gtozutjzne.html

[U62] PHP：日期对象
来源：http://dali.ivvv.top/Article/details/gtgbajzjzl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zdqjudy.top/Article/details/gtcacwhllz.html

[U63] PHP：文件读写
来源：http://dali.jyoumei.cn/Article/details/gtkjtbqfrj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhixingplan.top/Article/details/gtkaclfbal.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtbjfsldav.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tian-w.cn/Article/details/gtrdscnvdh.html

[U65] PHP：会话
来源：http://dali.jqgfzy.top/Article/details/gtzwzbbahs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dashuyun.cn/Article/details/gttlbktamw.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtmcxsolfr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtzctxghdp.html

[U67] PHP：处理文件上传
来源：http://dali.zhijiandao.cn/Article/details/gtdsucdvkz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtbeqwiwzt.html

[U68] PHP：PDO 连接
来源：http://dali.havefunace.top/Article/details/gtqbquezzp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yonumen.top/Article/details/gttiochndv.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtnyblqppo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guowangkeji.top/Article/details/gtgoylbetf.html

[U70] PHP：PDO 事务
来源：http://dali.gzhubu.top/Article/details/gtaczumgdj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zdqjudy.top/Article/details/gtglseqxvp.html

[U71] PHP：抛出异常
来源：http://dali.daxiang520.top/Article/details/gtzcnulega.html

throw new RuntimeException("失败", 500);
来源：http://dali.cdnleiting.top/Article/details/gttlvyalwf.html

[U72] PHP：写错误日志
来源：http://dali.zdqjudy.top/Article/details/gtvecaydmx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.tian-w.cn/Article/details/gtsshszprs.html

[U73] PHP：读取 ini 配置
来源：http://dali.yanxiufei.cn/Article/details/gtdgjjzsys.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gtugctqtvw.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtfaizdpby.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj20258.top/Article/details/gtvpsxrmch.html

[U75] PHP：依赖注入
来源：http://dali.shuidangran.top/Article/details/gtcgdnsdcw.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtqdnazdmn.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gtolmjtuoj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenlongwang.top/Article/details/gtcrfaxymn.html

[U77] PHP：模板渲染
来源：http://dali.ydzc1.top/Article/details/gtwkdicxwm.html

composer require twig/twig
来源：http://dali.xylfe.cn/Article/details/gthwfhitsj.html

[U78] PHP：单元测试
来源：http://dali.nwbrower.top/Article/details/gtwybdkpju.html

composer require --dev phpunit/phpunit
来源：http://dali.cucudq.cn/Article/details/gtvehzwjpr.html


<!-- 参考信息 -->