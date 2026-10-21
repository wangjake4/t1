代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtzmedbcif.html

[S55] C++：结构化绑定
来源：http://dali.zycfv.cn/Article/details/gthgeeloil.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtbjidtkgw.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gtbgcvzlph.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtruqwoazs.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtdqbpaoxo.html

constexpr int N = 10;
来源：http://dali.9152youxi.cn/Article/details/gttfufxgtv.html

[S58] C++：命名空间
来源：http://dali.meibo888.top/Article/details/gtlekyajhf.html

namespace ns { int f() { return 1; } }
来源：http://dali.yueranfly.top/Article/details/gtfjwrbqvj.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gttmlnbfty.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtjzewikuv.html

[S60] C++：遍历并删除元素
来源：http://dali.hysaishi.cn/Article/details/gtthxodmob.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtxtkximzu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzvjxcegv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gtbpqctmqr.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtvrqkycfq.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtqjzfaydq.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gttuacmrek.html

[T02] Kotlin：变量
来源：http://dali.tianlin.xyz/Article/details/gtfbfszbjf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtxeqrcwuv.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtckpmassp.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gtiwpcdbjm.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtwkqmdzmu.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtfyuxhloc.html

[T05] Kotlin：when 表达式
来源：http://dali.wangdashe.top/Article/details/gtefbqcmnq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gthljtqvea.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtdiyleurc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtbqryrvzv.html

[T07] Kotlin：集合过滤
来源：http://dali.tanke756.top/Article/details/gtnyhfvlvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtpgjtpgdx.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtejkddtqc.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtczzbqmsa.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtpubhlbxx.html

fun String.exclaim() = this + "!"
来源：http://dali.kuanghao11.cn/Article/details/gtndeurddq.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtpyqzxotw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gtqavobkcg.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtcgzkezcr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jlsjyb.cn/Article/details/gtkrqopqdy.html

[T12] Kotlin：解构声明
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdzuhjvyg.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtbiewolmr.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtxmkvtqtq.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtvswlhuoc.html

[T14] Kotlin：循环
来源：http://dali.9152youxi.cn/Article/details/gtsxssdohp.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtuyakdnok.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtuybmtadq.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gteeresjvo.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtcsmzqzdz.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtiqcrqely.html

[T17] Swift：变量与常量
来源：http://dali.andypj.xyz/Article/details/gtxalpgsju.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gttgyowulo.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtaweoould.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtyhlcndcg.html

[T19] Swift：可选绑定
来源：http://dali.316326.xyz/Article/details/gtcmgrcntj.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gttkoqinuv.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtfgxggxoh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtjwqfrkhp.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtzcfncibr.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gtihtokubo.html

[T22] Swift：字典
来源：http://dali.pengpengdd.cyou/Article/details/gtlmzrwose.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sxryk.cn/Article/details/gtwmqyvwdp.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtwjdtliml.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtxlowyzlv.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gttsodfezx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtxzrqxbfp.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gtabymtqad.html

struct P { var x: Int }
来源：http://dali.zhoulong.xyz/Article/details/gtkbojiqki.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gttevqwphi.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gtgkfgqlym.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdbcjvhb.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gtchskbqnx.html

[T28] Swift：枚举
来源：http://dali.guowangkeji.top/Article/details/gtuuqxckrh.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtapoifdcs.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gtxektludy.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtndxuclvp.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtcmjbtodf.html

protocol Shape { func area() -> Double }
来源：http://dali.shzxlz.cn/Article/details/gtkzmvbxox.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtwcycaawy.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtstbltrjv.html

[T32] Lua：局部变量
来源：http://dali.wangdashe.top/Article/details/gttslhzyty.html

local a = 1
来源：http://dali.sweek.top/Article/details/gtbtgnkuru.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gthppzhfqw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gtzvvffgat.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtbdhyycqe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzhpmhmt.html

[T35] Lua：字典表
来源：http://dali.yuanzhike.top/Article/details/gttbqlymql.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtekextvgy.html

[T36] Lua：函数
来源：http://dali.guannengcc.top/Article/details/gttoekihow.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gtnxdqhzdd.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtcuqircgo.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gtkxqqkxys.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtjxdyuntb.html

if x > 0 then print("正") end
来源：http://dali.jyoumei.cn/Article/details/gtitqyylgl.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtpjmaowmg.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtxefmaslw.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtvjovsoyv.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtbdqghkny.html

[T41] Perl：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtjtrkjmhm.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtibkxrjgp.html

[T42] Perl：变量类型
来源：http://dali.jianghu66.top/Article/details/gtrxxncxcr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtmekwmtys.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtjayapzeb.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtrsbvttoz.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gttggzwylq.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtufigxwup.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gtlbeorsjf.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtzkrzphsk.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gtmilfutvv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtubmqqyqi.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttrzbhsgg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gtumrwybrj.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtlxhweeoh.html

$s =~ s/old/new/g;
来源：http://dali.zhoulong.xyz/Article/details/gtqsvkikgr.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtkpkkcoek.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtzuaekppk.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtpsywcazi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtlraaolsl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtshmzsskm.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtzyfgxxks.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtdudrlfyi.html

[T52] Scala：变量
来源：http://dali.jyoumei.cn/Article/details/gtqjtkxepo.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtxeglvxjh.html

[T53] Scala：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnorabfvn.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtzqcbokmq.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtlqdwycjj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtvodhjjuf.html

[T55] Scala：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gtvvwrohqr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtuningjij.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtclounbcs.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gtbuamdizh.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtzhbfjqjl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtkfogfyuw.html

[T58] Scala：函数定义
来源：http://dali.yanxiufei.cn/Article/details/gtgcwjqdgw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.mhx1999.top/Article/details/gtnjfurddt.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gtwfnyzhcl.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtvgncaskx.html

[T60] Scala：折叠
来源：http://dali.sufxvd.cn/Article/details/gtainvjoer.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknpkflsd.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtilxlodov.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxuanxn.top/Article/details/gtjdaglbws.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtrcuthdyb.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtsdtirpie.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gtgfrxljxl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gtvpcbtetf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gtkdqeldzp.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gtoktodoyq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtctojptfb.html

[U04] Py：变量调试打印
来源：http://dali.tianlin.xyz/Article/details/gtaxqigyuc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gtzjeomgcv.html

[U05] Py：列表去重且保序
来源：http://dali.zhoulong.xyz/Article/details/gtepwohjnb.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gthixssjjw.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtqgkvvckz.html

{**a, **b}
来源：http://dali.tian-w.cn/Article/details/gtycrefcay.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtzehpidvp.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtkufzlbjc.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtsymxyuzm.html

[y for x in nested for y in x]
来源：http://dali.c1oappe.top/Article/details/gtaboaxeyh.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gtxwlaapku.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtgrtlflfo.html

[U10] Py：按值排序字典
来源：http://dali.zhongyouzk.top/Article/details/gtldbzmucq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gtcaunlqir.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrtsrsla.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gtoasdhktl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtcplbffop.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gtpbwdgwbs.html

[U13] Py：固定长度队列
来源：http://dali.yanxiufei.cn/Article/details/gtmrtvrysu.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gtwbhioyhj.html

[U14] Py：分组收集到列表
来源：http://dali.sxryk.cn/Article/details/gtaazuawrc.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtfbpoojxb.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtfhksymvp.html

t = time.perf_counter()
来源：http://dali.ydzc1.top/Article/details/gtkkmyysmx.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gttijvpjpt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shzxlz.cn/Article/details/gtldtxaqnd.html

[U17] Py：初始化日志
来源：http://dali.zhongyouzk.top/Article/details/gtesrzqqsj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtgdjfwerk.html

[U18] Py：预编译正则
来源：http://dali.smart0.xyz/Article/details/gteworsphf.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtztcmouyl.html

[U19] Py：正则替换带回调
来源：http://dali.iojbl.cn/Article/details/gttzqawbkr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gtrrhuddfg.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtnpjbhoab.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtndpbkhub.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtznxvwekz.html

@contextlib.contextmanager
来源：http://dali.yj20258888.top/Article/details/gtognloffx.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtjijepeyz.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtcaqxntkk.html

[U23] Py：分块读取大文件
来源：http://dali.hnxiangtu.top/Article/details/gtifnsxnik.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtkmlwqvvx.html

[U24] Py：路径操作
来源：http://dali.wangdashe.top/Article/details/gtvqbcyffe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtqboqxfqs.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gthlvisskf.html

csv.DictReader(f)
来源：http://dali.smart0.xyz/Article/details/gtpokqmmid.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtomgppcoc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gtdkeumukc.html

[U27] Py：异步 HTTP
来源：http://dali.tianlin.xyz/Article/details/gtokddypql.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yvedp.cn/Article/details/gtukjfejuo.html

[U28] Py：类型别名
来源：http://dali.zhiwuduotai.top/Article/details/gtmsekesrn.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gtlbmrpetf.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtjqjsvvhj.html

@property 与 @x.setter 配合
来源：http://dali.zhengqikj.top/Article/details/gtrozgcrav.html

[U30] Py：数据类
来源：http://dali.quarkkingdee.top/Article/details/gtjgmvcfev.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtubdsgtui.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtfvmmhpxm.html

python -m pytest -q
来源：http://dali.hongshengwenyu.top/Article/details/gtdvtwaykn.html

[U32] Py：代码格式化
来源：http://dali.xuanzx.com/Article/details/gtbpllumca.html

ruff format . && ruff check --fix .
来源：http://dali.xinyue.icu/Article/details/gtmtezftuu.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangtech.top/Article/details/gtlstfjphe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.mhx1999.top/Article/details/gtrohhlffs.html

[U34] Py：判断编码
来源：http://dali.c1oappe.top/Article/details/gtioxvcdht.html

chardet.detect(raw)
来源：http://dali.jiagoushi.top/Article/details/gtbizypcsi.html

[U35] Py：发送邮件
来源：http://dali.zhoulong.xyz/Article/details/gtutnnzvjq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gtcvtqsgad.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gtplxdhupw.html

schedule.every(10).minutes.do(job)
来源：http://dali.cucudq.cn/Article/details/gtwyizabtk.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtlsayjhgu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhixingplan.top/Article/details/gtyqfzlwcu.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangshuangyany.cn/Article/details/gtmypqbikh.html

Path(__file__).resolve().parent
来源：http://dali.svipenyu.cn/Article/details/gtzmfnuclm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtknfykiqd.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gtaknchivg.html

[U40] Py：打印到标准错误
来源：http://dali.wangdashe.top/Article/details/gtlorlznge.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtdufmmdvo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gtddezvrhq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnxsdrhn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangtech.top/Article/details/gtbddrfitr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gtxbeodhws.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gtqmszkotg.html

namespace App\Http;
来源：http://dali.hfpthk.cn/Article/details/gtbiuqpnpy.html

[U44] PHP：开启严格类型
来源：http://dali.pycfn.com/Article/details/gtdscpznko.html

declare(strict_types=1);
来源：http://dali.hammf.cn/Article/details/gtfoimsbqa.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtozjtfxjh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtyhaggqbl.html

[U46] PHP：可空类型
来源：http://dali.chenlongwang.top/Article/details/gtjzchfplw.html

?string $name = null
来源：http://dali.yj202588.top/Article/details/gtdvcxmdno.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtffgthozs.html

int|string $id
来源：http://dali.tianlin.xyz/Article/details/gthwdcxgzm.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtupbvrfas.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gtslrrxbbe.html

[U49] PHP：只读属性
来源：http://dali.redwolf501.top/Article/details/gtrjcdsexy.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gtgmfgaexc.html

[U50] PHP：构造器属性提升
来源：http://dali.xuetiantiany.cn/Article/details/gtifiwlwwi.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqhmswdq.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtjaqyzyrs.html

[$a, $b] = $arr;
来源：http://dali.zdqjudy.top/Article/details/gtflugbxnn.html

[U52] PHP：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtjyngfpyl.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtdsvptroo.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtffgscbwp.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuanzhike.top/Article/details/gtgjubcqxn.html

[U54] PHP：空安全调用
来源：http://dali.yonumen.top/Article/details/gtcudsakov.html

$obj?->method()
来源：http://dali.chenzaomai.com/Article/details/gtrorccfxx.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gtwoubeeno.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtldowpqhg.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtdcmuykrj.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtoalmuyjy.html

[U57] PHP：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtduxsdomi.html

"值: {$a}"
来源：http://dali.zhixingplan.top/Article/details/gtozgqehri.html

[U58] PHP：数组三件套
来源：http://dali.jyoumei.cn/Article/details/gtnapcuqxc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.0kj1m.cn/Article/details/gtxdjgaslq.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gtpmoqewza.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gtpfyaedog.html

[U60] PHP：JSON 编解码
来源：http://dali.aizwys.cn/Article/details/gtornluait.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtckopijkh.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtqclfaiua.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtflwwyhme.html

[U62] PHP：日期对象
来源：http://dali.daria6918.cn/Article/details/gtuweqkwcx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gtmaaxdber.html

[U63] PHP：文件读写
来源：http://dali.yueranfly.top/Article/details/gtqohdejdx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtogllvhpk.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtqdvwzqsc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtfiuaidga.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtsbendsut.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gtftxwxlfe.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gtkigeqthd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gtizszhgmg.html

[U67] PHP：处理文件上传
来源：http://dali.iojbl.cn/Article/details/gtasfanbis.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jyoumei.cn/Article/details/gtcuofupiv.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gttcoelqvs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258888.top/Article/details/gtmkcvgise.html

[U69] PHP：PDO 预处理
来源：http://dali.yj202588.top/Article/details/gtvniabakv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gtkjfgkcyt.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtarziygmn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hnxiangtu.top/Article/details/gtrjpjbvwh.html

[U71] PHP：抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gtnftboxss.html

throw new RuntimeException("失败", 500);
来源：http://dali.zdqjudy.top/Article/details/gtsfsughzc.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gtgjxkrjxj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gtrilqdnzk.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtttyfjfsg.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gtzlahrmzz.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvnwyphdb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gttmntbxlp.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtjtoctbjo.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtobwfxaix.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtkvwuasmd.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gtantplqxh.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtxpkmtbwm.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gtsxtykdeg.html

[U78] PHP：单元测试
来源：http://dali.guannengcc.top/Article/details/gtwfozktmd.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gtarjhfxwu.html

[U79] PHP：静态分析
来源：http://dali.gotoacloud.top/Article/details/gtghxpevgl.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtekffpaem.html

[U80] PHP：代码规范修复
来源：http://dali.iojbl.cn/Article/details/gtsoqlpfzb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwbutagkg.html


<!-- 参考信息 -->