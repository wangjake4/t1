代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtqlcztmnt.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfglhrfc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtiifssjmh.html

[S56] C++：optional
来源：http://dali.cqqwz.cn/Article/details/gtucpjdttc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gttofdiboc.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtzsfveyje.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtsgopufhv.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtcpkrgxpe.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtwumnrouq.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtdzyhjshh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtlnbogvlh.html

[S60] C++：遍历并删除元素
来源：http://dali.aibaodan.cn/Article/details/gtubsctrhm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtyoakaerr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcgocgtmn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkoczemd.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtkjkqcpes.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtmqzklalj.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtkhamfoei.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtuvfdlfyj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtprqlvvxj.html

[T03] Kotlin：字符串模板
来源：http://dali.yueranfly.top/Article/details/gtgrrbkjrq.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gthbbnkuhx.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gtfhkxpbhw.html

val n: String? = null;  n?.length
来源：http://dali.zhixingplan.top/Article/details/gtxldsdjab.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtbegrqqke.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtnchqfnnu.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtvknzodfd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtadkcfdwf.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtgjfulgcg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtdoqkfdiu.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtyklxpmxe.html

data class User(val name: String, val age: Int)
来源：http://dali.zycfv.cn/Article/details/gtvmofaxkf.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtelrlazql.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtaudaaqpk.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gtzmzwmdng.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtbcihvdcl.html

[T11] Kotlin：协程
来源：http://dali.yongpay.top/Article/details/gtmoriimqn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtvgwszymq.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gtwwlfmipq.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnxiangtu.top/Article/details/gtysdfnrre.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrmsopdmb.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtozkhhwda.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtjmhqlbjx.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtrixsrrzh.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtcvzuwrsm.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlrvqxiz.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsafhgdr.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtcqqljbvr.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtdxxcveam.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbjfavox.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtbopctdhw.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gtydzqobbv.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gtgwkfmktp.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtxtsfpwgu.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtncrzgupj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtyqmpqwla.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gtrfntynet.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtipwzorgp.html

[T22] Swift：字典
来源：http://dali.daxiang520.top/Article/details/gtbuwtoyra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtcpoxmjkz.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gtlkleepkc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtxjtrltbh.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtyfrgmmzk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jlsjyb.cn/Article/details/gtersnacfw.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtxuceitfw.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtqyacjqle.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gtonsrkhuq.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtlczymwfz.html

[T27] Swift：错误处理
来源：http://dali.sufxvd.cn/Article/details/gtzvoeygcb.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtahjijbic.html

[T28] Swift：枚举
来源：http://dali.hfpthk.cn/Article/details/gtdxxnecrm.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtlwrvpshi.html

[T29] Swift：guard 提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtphwqzquf.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtaztwdpiq.html

[T30] Swift：协议
来源：http://dali.yj20258888.top/Article/details/gtsebnztxd.html

protocol Shape { func area() -> Double }
来源：http://dali.zhijiandao.cn/Article/details/gtxaejeqnp.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtvtkwceqh.html

print("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtlxnvcdrk.html

[T32] Lua：局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlwxfgfln.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gtgalzzopw.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtmibrtrss.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ivvv.top/Article/details/gtgyogygdg.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtlhofxhyw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtjobizngf.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtoimnhhmf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtenksevig.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtmdfulrsr.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtlhtuoxkf.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtggclaazk.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtvtpshgqj.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gtvblpnmym.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtnrvydywa.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtpdzhbysl.html

string.find(s, "%d+")
来源：http://dali.xinyue.icu/Article/details/gtmeiyedbv.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtbjzhzcrq.html

setmetatable({}, { __index = base })
来源：http://dali.yuanzhike.top/Article/details/gtjzoyetsn.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtwmmosglh.html

print "Hello\n";
来源：http://dali.jinqigufen.top/Article/details/gtkyztblgo.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtbaudkafn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gtdaqahrqe.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtfbyxebsu.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtoipdesrz.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtnsbxletf.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtnvipcdas.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtnyvynjwn.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gtwvnwttzn.html

[T46] Perl：哈希操作
来源：http://dali.yongpay.top/Article/details/gtdgotzgzq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gtsipkosqw.html

[T47] Perl：正则捕获
来源：http://dali.redwolf501.top/Article/details/gtcygjqiwc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gthmwodgqv.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gthbrinhbq.html

$s =~ s/old/new/g;
来源：http://dali.chenzaomai.com/Article/details/gtwltrwttn.html

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtqrbgsnvp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnftfqamu.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtcstjrcrd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtflpmnahr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtwdbmkjgf.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtrskwaxpq.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtsfztlwlz.html

[T52] Scala：变量
来源：http://dali.0kj1m.cn/Article/details/gttfrkvmdk.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtefubetef.html

[T53] Scala：字符串插值
来源：http://dali.cashguo.top/Article/details/gtlbaongab.html

s"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtrxlcgseu.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtetyenpuk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gttxffvpgy.html

[T55] Scala：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtkkwtivej.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtviqfvvtu.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gtgqabbxef.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtkrjhvpjf.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtklcftkzw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtjaelsvlm.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtstouhvmv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtfbrjzupp.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuqlufll.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtxpeaeegy.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gttzrtoqtq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtrpvbcpvp.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtnfefigye.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtkadeaacw.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtzjugsilw.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtwdijfykv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gttxfichuv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtjvwkfojy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gttbuxlzpv.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtfdonoicg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gthtzotfxm.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gteebnhwvw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gtphddfaap.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtqyaavwdc.html

list(dict.fromkeys(arr))
来源：http://dali.fengsongda.top/Article/details/gtbxgtmnrk.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gtbikopkbb.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gtlgsfviqf.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gtbxwtocwc.html

{v: k for k, v in d.items()}
来源：http://dali.shuidangran.top/Article/details/gttspyuiwg.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtlriqwbjv.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtsiuhycpj.html

[U09] Py：字典取最大值的键
来源：http://dali.jyoumei.cn/Article/details/gtyoykfqez.html

max(d, key=d.get)
来源：http://dali.ivvv.top/Article/details/gtmhyglukh.html

[U10] Py：按值排序字典
来源：http://dali.cqqwz.cn/Article/details/gtsoxrbghn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.shangyingyoupin.top/Article/details/gtoibemiwd.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtedmfkiit.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gttfpwupmy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtlyzfxtrs.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtellfnrjz.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtvffifbmy.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gtovuohbap.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvyenijd.html

defaultdict(list)
来源：http://dali.sufxvd.cn/Article/details/gtlpyrurvh.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtijkmefrf.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtxromicba.html

[U16] Py：命令行参数解析
来源：http://dali.daria6918.cn/Article/details/gtekzgcjbb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenjidiqi.icu/Article/details/gtlcnytqzr.html

[U17] Py：初始化日志
来源：http://dali.jqgufenzy.top/Article/details/gtpsbgmhdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gtltqyltwj.html

[U18] Py：预编译正则
来源：http://dali.birdmap.top/Article/details/gtpwaavnwn.html

pat = re.compile(r"\d+")
来源：http://dali.zycfv.cn/Article/details/gtxjnsbjjv.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gtcbwqdnfg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shzxlz.cn/Article/details/gtqllxwydg.html

[U20] Py：缓存函数结果
来源：http://dali.hysaishi.cn/Article/details/gtfxliebhw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gtavjpbehg.html

[U21] Py：自定义上下文管理器
来源：http://dali.ppjwa.cn/Article/details/gtjrlbmzwx.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gttzrnuizl.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtljawuxby.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtfwymrwkx.html

[U23] Py：分块读取大文件
来源：http://dali.dashuyun.cn/Article/details/gtrtkhlptl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtrhuhwhdx.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gtbwwaocmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtogzvyenv.html

[U25] Py：CSV 按字典读
来源：http://dali.snrcjt.cn/Article/details/gtdvehftcu.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gtcjozycru.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gtyulbzgbw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtvditmuph.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtxvhjkktk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.birdmap.top/Article/details/gthbtmznnm.html

[U28] Py：类型别名
来源：http://dali.dashuyun.cn/Article/details/gtnoamsrzq.html

UserId = int
来源：http://dali.jqgfzy.top/Article/details/gtllddtrsa.html

[U29] Py：属性校验
来源：http://dali.zhengqikj.top/Article/details/gtcfplufne.html

@property 与 @x.setter 配合
来源：http://dali.pycfn.com/Article/details/gthxugtaso.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gtjnciivsb.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gtviqcmduf.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gtawevxrhw.html

python -m pytest -q
来源：http://dali.xuanzx.com/Article/details/gtbdmvlcmh.html

[U32] Py：代码格式化
来源：http://dali.bjfxy.top/Article/details/gtpasblvsv.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gthkhykkyl.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gtbcnudeyw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtaulqcjdf.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtlbgwwhie.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtsozonpwc.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtblwruuhn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hammf.cn/Article/details/gtdxcaysws.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtmmusaikb.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gthgfnpwec.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gtpfzcnufm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gtzxgdbcle.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtrgskljps.html

Path(__file__).resolve().parent
来源：http://dali.sweek.top/Article/details/gtyapycsdo.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuanzhike.top/Article/details/gtcwydjzzh.html

sys.stdout.isatty()
来源：http://dali.jyoumei.cn/Article/details/gtuoiylosg.html

[U40] Py：打印到标准错误
来源：http://dali.zycfv.cn/Article/details/gtixseatia.html

print("err", file=sys.stderr)
来源：http://dali.smart0.xyz/Article/details/gtvxuytvlt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ehwqpu.com/Article/details/gtpmmxusuj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ehwqpu.com/Article/details/gtfcamrrlz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtunaepbvl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gtqbmicizx.html

[U43] PHP：声明命名空间
来源：http://dali.andypj.xyz/Article/details/gtwiwzktxp.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gtfbhyoqwn.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtmkuhibzl.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gtezcoveov.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtiomuuvmh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtbixzxcaa.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtoixfurxa.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gtklowzbtp.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gtvdfeylsj.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtcbuwrzll.html

[U48] PHP：纯枚举
来源：http://dali.zhengqikj.top/Article/details/gtzoifihxu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gtiwsgkuwv.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtiqofhwdd.html

public readonly string $name
来源：http://dali.jqgfzy.top/Article/details/gtuejvseej.html

[U50] PHP：构造器属性提升
来源：http://dali.bjfxy.top/Article/details/gttrhpmpan.html

public function __construct(private int $id) {}
来源：http://dali.xziqi.cn/Article/details/gtukkfwshf.html

[U51] PHP：数组解构
来源：http://dali.ehwqpu.com/Article/details/gtubzxiqtj.html

[$a, $b] = $arr;
来源：http://dali.hongshengwenyu.top/Article/details/gtqmjzwkjc.html

[U52] PHP：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtyibqnesu.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtsqsgpikx.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtekkoojce.html

$v = $a ?? $b ?? "default";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovhfpvvd.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gtbtzanymw.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gtbokiyfia.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gttomyftpv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gtpoljgnqc.html

[U56] PHP：命名参数
来源：http://dali.316326.xyz/Article/details/gtrjmgmjco.html

f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtjpjxxrsf.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvlriaoqr.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gtviqqkdxx.html

[U58] PHP：数组三件套
来源：http://dali.tanke756.top/Article/details/gtlvaqyzwp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtkzxcshit.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtxlevlcbb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gtwtksupsn.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtgzpjtfxz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.iojbl.cn/Article/details/gtpdvxbkbz.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gtvridbiua.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gttsdadstb.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gtcjlazgue.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tian-w.cn/Article/details/gthwhzwtti.html

[U63] PHP：文件读写
来源：http://dali.zhongyouzk.top/Article/details/gttghdfgxd.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhongyouzk.top/Article/details/gtvhkgadkk.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbbshaxd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtpuzltwyn.html

[U65] PHP：会话
来源：http://dali.jyoumei.cn/Article/details/gtphmeqvbb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gtqirgtmhh.html

[U66] PHP：设置 Cookie
来源：http://dali.ybcxt.top/Article/details/gtxfrliarw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtjommfsdr.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoowizeyn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gtcmhmmpmh.html

[U68] PHP：PDO 连接
来源：http://dali.iojbl.cn/Article/details/gtplxnjjuu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gtlzhdrqzr.html

[U69] PHP：PDO 预处理
来源：http://dali.ppjwa.cn/Article/details/gtwqpvzrbb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtsgbwdhfy.html

[U70] PHP：PDO 事务
来源：http://dali.fengsongda.top/Article/details/gtonsvncem.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtoheigszt.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gtixngyorc.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtoyclzyth.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtcwfwzfsp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtgduqofqp.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gtfjycqqud.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtkkfzfyif.html

[U74] PHP：读取环境变量
来源：http://dali.tanke756.top/Article/details/gtxqpmcjbh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtrholrmxa.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtmxkefaln.html

composer require psr/container
来源：http://dali.zhiwuduotai.top/Article/details/gtvxaltila.html

[U76] PHP：简单路由
来源：http://dali.ydzc1.top/Article/details/gtzaazclua.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.haohaochexian.top/Article/details/gtvhqhjouw.html

[U77] PHP：模板渲染
来源：http://dali.mhx1999.top/Article/details/gtcxqulmva.html

composer require twig/twig
来源：http://dali.yangfankeji.com/Article/details/gtrqeyzlye.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtzcxzrleh.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gtkbekdxjw.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gtynamotuw.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gtwmjpqljo.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtrxlbzclw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gtrykelqzp.html


<!-- 参考信息 -->