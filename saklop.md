代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtrfumodvs.html

[S57] C++：编译期常量
来源：http://dali.yvedp.cn/Article/details/gtaenbfccd.html

constexpr int N = 10;
来源：http://dali.svipenyu.cn/Article/details/gterrjcgqs.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gtxgksebvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gtkxqnjtfg.html

[S59] C++：静态断言
来源：http://dali.gogol.net.cn/Article/details/gtosofniqk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtvaodkssx.html

[S60] C++：遍历并删除元素
来源：http://dali.daria6918.cn/Article/details/gtzxajyqav.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtyoboadge.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtznnkbein.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.haohaochexian.top/Article/details/gtxukuimik.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpjbvfnzz.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtovrrcnvg.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtkgihkgdr.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtcwsasbmd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtrjycchxl.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtzrxerjvl.html

"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtjucwzvjj.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gteqwgqbvz.html

val n: String? = null;  n?.length
来源：http://dali.jqgufenzy.top/Article/details/gtbkyqhals.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoejpgecz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtcoaejzcj.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtwhcadwau.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtfonojvju.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtyvtkyemq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtokoiphuq.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtwbvhvplp.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdfsateri.html

[T09] Kotlin：扩展函数
来源：http://dali.316326.xyz/Article/details/gtlljqqskg.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtlblpbhsn.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gtoqyvhhgd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtcdniwcnc.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gtxsgsqzma.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtiuazjxys.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtyopmbhkn.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gthyftzbxw.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtoarrdfgw.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gtiuvwhyxa.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtmqphnxfx.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gthtcduoua.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtjvvfniwg.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtsqykgwrj.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtqalpyrsq.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtkjwcdyrv.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtacagyfed.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gtwzjftaql.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gttvcbiige.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtntzbdkkt.html

[T19] Swift：可选绑定
来源：http://dali.jiagoushi.top/Article/details/gtwybtynls.html

if let n = opt { print(n) }
来源：http://dali.jinqigufen.top/Article/details/gtprddtbyu.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gttwumtzyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtxpbffxfb.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtqpshrsic.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtexlrlruf.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtbwtvxvdo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtgirsapxa.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtllxavslj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gtbrvfyuqq.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtasisxbfm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangdashe.top/Article/details/gtmdyqcvvd.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gtgkazewwj.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtzkvdkjpt.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtfqocygxr.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtndwjfycb.html

[T27] Swift：错误处理
来源：http://dali.gotoacloud.top/Article/details/gttxfayhdt.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gtwuvogdic.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtcvzumfuh.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtkstvaxzp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtczsplwhl.html

guard let x = opt else { return }
来源：http://dali.jiagoushi.top/Article/details/gtpaqcggoj.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtcwxyawpg.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtfjvpgess.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gtxrvnequt.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtwxijtrux.html

[T32] Lua：局部变量
来源：http://dali.chenzaomai.com/Article/details/gtmcarafuq.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtdfogbwmd.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtvcchmgkv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gtjripdkeq.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtkdedljxz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtwgrhauiw.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtfwtmivae.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtmspuvzwv.html

[T36] Lua：函数
来源：http://dali.0kj1m.cn/Article/details/gtblqhxehj.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gtafqqpicn.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtypwzhdla.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtjrpqixzs.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gteeoxlqpv.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtkherjdnq.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtkltjrtic.html

string.find(s, "%d+")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthvtzkafm.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtnbmqqvyj.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gtzzyfqruc.html

[T41] Perl：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtehhzznno.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtixpajzue.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtiqtmzzxu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gtrpwexxfg.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtjgrdcgud.html

"值: $a"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtujwcrvph.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtwathzppr.html

if ($a > 0) { print "正"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxjaqvho.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtbqukcsrz.html

for my $x (@arr) { print $x; }
来源：http://dali.gotoacloud.top/Article/details/gtkrddezmb.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtstjagifm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtnmgwlqlo.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtgkqsqngw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtyukpkagw.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtchnrabsg.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtejrbzrhg.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtejuhcwdr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtwmyjjhoi.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtixsimglx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtrednhpif.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtoaoaumtn.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtaeqofslj.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtnqlwylsk.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gttdagrlzu.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gtvckzsxsi.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtqlqvhlyt.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtviitpcbr.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtnfhhbeic.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtltwuppsl.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqjlmcjp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtcmaunrdx.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtnbrhilmf.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtssaphkbv.html

[T57] Scala：模式匹配
来源：http://dali.yonumen.top/Article/details/gtmhoxuevh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtqpmrmaxm.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtelwxewiu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gthgtjdsep.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gtyjdhddbw.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtszoqwehv.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtnwslgrlt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqwgwumg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjvaubpug.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cqqwz.cn/Article/details/gtnkqokjfz.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gthiqioqgu.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtqfpreobr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtxxhddvxy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gtjjriuoog.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gtjuefevvy.html

[U03] Py：加载 .env 配置
来源：http://dali.jianghu66.top/Article/details/gtxlmckxma.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cucudq.cn/Article/details/gtuhsvcsel.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gtmziehqjf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aizwys.cn/Article/details/gtinbmywnr.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtlvdtzqqg.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtjyevzdyj.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtmwddyncv.html

{**a, **b}
来源：http://dali.snrcjt.cn/Article/details/gtbzktqvzk.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahsqaiwx.html

{v: k for k, v in d.items()}
来源：http://dali.yj202588.top/Article/details/gtmjbaccpe.html

[U08] Py：展平二维列表
来源：http://dali.jyoumei.cn/Article/details/gttufmjomi.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gtnwrhtmfg.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtripmclra.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtbbmolzxy.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtsodeeubh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtphxwtgph.html

[U11] Py：生成器表达式
来源：http://dali.chenjidiqi.icu/Article/details/gtlvtcazfk.html

(x * 2 for x in arr)
来源：http://dali.hysaishi.cn/Article/details/gtfinonsyn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gtmscoojby.html

Counter(arr).most_common(3)
来源：http://dali.xuanzx.com/Article/details/gtixuasfwv.html

[U13] Py：固定长度队列
来源：http://dali.jiagoushi.top/Article/details/gtbbcpshwj.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtlamxzldg.html

[U14] Py：分组收集到列表
来源：http://dali.cqqwz.cn/Article/details/gtqnvrzahn.html

defaultdict(list)
来源：http://dali.vqdsnc.cn/Article/details/gtckrptjyl.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtnmvmyxms.html

t = time.perf_counter()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiipjmkh.html

[U16] Py：命令行参数解析
来源：http://dali.gotoacloud.top/Article/details/gtpuaxetfr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtldgweszr.html

[U17] Py：初始化日志
来源：http://dali.gotoacloud.top/Article/details/gtpewrciyi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtwjqxduas.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gtgwtecnxd.html

pat = re.compile(r"\d+")
来源：http://dali.jqgufenzy.top/Article/details/gtcddtvprh.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtuviotaoh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtpslzkwia.html

[U20] Py：缓存函数结果
来源：http://dali.daria6918.cn/Article/details/gtgfhrsafe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ehwqpu.com/Article/details/gtjgnnddwu.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gtkjjwjnap.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtwostjgho.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtgfmvcnen.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtwvwuedjg.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucekkxlb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gthudzxqmx.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucaaskkh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpbldwvrj.html

[U25] Py：CSV 按字典读
来源：http://dali.yongpay.top/Article/details/gtxbifhiuf.html

csv.DictReader(f)
来源：http://dali.hfpthk.cn/Article/details/gtsuyfajix.html

[U26] Py：并发下载
来源：http://dali.yongpay.top/Article/details/gtbmwhukjb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gttrdmienc.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtxkhkxyjv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gtkkbwyyku.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtictzokaq.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtfyenpqmc.html

[U29] Py：属性校验
来源：http://dali.hammf.cn/Article/details/gtuoetmroq.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtwpkxlcbh.html

[U30] Py：数据类
来源：http://dali.c1oappe.top/Article/details/gtmmulljbb.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtztlppgjv.html

[U31] Py：单测
来源：http://dali.tanke756.top/Article/details/gtuzpqhsoe.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gtrsaesdop.html

[U32] Py：代码格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjymakrof.html

ruff format . && ruff check --fix .
来源：http://dali.chenlongwang.top/Article/details/gtxnwzwhnp.html

[U33] Py：打包发布
来源：http://dali.zhongyouzk.top/Article/details/gtenkryuxq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jinqigfzy.top/Article/details/gtdgfrnida.html

[U34] Py：判断编码
来源：http://dali.pengpengdd.cyou/Article/details/gtmjivpgde.html

chardet.detect(raw)
来源：http://dali.hysaishi.cn/Article/details/gtwiihyqsn.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtuippmdqf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.smart0.xyz/Article/details/gtaorxxnum.html

[U36] Py：定时任务
来源：http://dali.sysykeji.top/Article/details/gtrbthtuza.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtdeelpjag.html

[U37] Py：读写 Excel
来源：http://dali.yanxiufei.cn/Article/details/gtcbtcorkz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ehwqpu.com/Article/details/gtylfcajtx.html

[U38] Py：获取脚本所在目录
来源：http://dali.316326.xyz/Article/details/gtahdtobco.html

Path(__file__).resolve().parent
来源：http://dali.jinghuilouyu.cn/Article/details/gtclqafefz.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gtcqgqmeob.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtgkvliaxb.html

[U40] Py：打印到标准错误
来源：http://dali.jinqigufen.top/Article/details/gttxvsiqyu.html

print("err", file=sys.stderr)
来源：http://dali.jqgfzy.top/Article/details/gttexmwpoi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuetiantiany.cn/Article/details/gtnfzllunq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtvuedagga.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangdashe.top/Article/details/gtauavvnuh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtlivcsmwd.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtmcvbckwc.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtlqghteum.html

[U44] PHP：开启严格类型
来源：http://dali.zdqjudy.top/Article/details/gtjuonzxik.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtnviywhln.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtwfequmko.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gthblzkvtm.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gtvxiiucku.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcbxtybou.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbbejifzq.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gtbgwidcpl.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtztjjimdh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtryreloxv.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtxgavlquu.html

public readonly string $name
来源：http://dali.jyoumei.cn/Article/details/gtpuukgqce.html

[U50] PHP：构造器属性提升
来源：http://dali.yanxiufei.cn/Article/details/gtpeyejfju.html

public function __construct(private int $id) {}
来源：http://dali.wangdashe.top/Article/details/gtahqyfvpr.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gtlcargint.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gtuyymdyif.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gthiujkinl.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtpvlwmgky.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtrevxzpsq.html

$v = $a ?? $b ?? "default";
来源：http://dali.gzhubu.top/Article/details/gtbtjbfcld.html

[U54] PHP：空安全调用
来源：http://dali.birdmap.top/Article/details/gtvjagxror.html

$obj?->method()
来源：http://dali.shuidangran.top/Article/details/gtjalijpsx.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gtukydhhke.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtrabpcnyz.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gtqabojjzo.html

f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtixqkpiqv.html

[U57] PHP：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtefhjleoh.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtebefnmag.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtpyppbgyl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtrtbqkgfz.html

[U59] PHP：自定义排序
来源：http://dali.c1oappe.top/Article/details/gtxeepftrl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sweek.top/Article/details/gtfzplinut.html

[U60] PHP：JSON 编解码
来源：http://dali.gaohongyu789.top/Article/details/gtwzkdtmeq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtegygxjdl.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gtqegdbyhi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhixingplan.top/Article/details/gtcgnlyhvw.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtfcyrifju.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sysykeji.top/Article/details/gtcunwqyos.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtohiizrnu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hammf.cn/Article/details/gtyljxnmfs.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gtxevthwqr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gtbysjvbje.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gtibwiwvyi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcjawogdm.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gtdynhnblg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtdfpqvnig.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gttysbssnm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydxxnjwa.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gtapdrnpzm.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gtpzppnnzz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhixingplan.top/Article/details/gtotwbaert.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gtxmucmijv.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfzcsuew.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gtbsvopddd.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gtlxmgmptn.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtugngkzan.html

[U72] PHP：写错误日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdldabyku.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtpqrlmhdw.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gttkguqrmg.html

parse_ini_file("config.ini", true)
来源：http://dali.birdmap.top/Article/details/gtbjcyskuz.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtvsemapgw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gtuexoptli.html

[U75] PHP：依赖注入
来源：http://dali.yonumen.top/Article/details/gtittmmgsq.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtedudywom.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtetmmls.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigfzy.top/Article/details/gtacpgnnyh.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gtssbwxuzq.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gtshegnprq.html

[U78] PHP：单元测试
来源：http://dali.fzhhl.top/Article/details/gtwihycajn.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gtsujogxjo.html

[U79] PHP：静态分析
来源：http://dali.dashuyun.cn/Article/details/gtpiuxglnl.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtschmstbf.html

[U80] PHP：代码规范修复
来源：http://dali.yvedp.cn/Article/details/gtxnstfnzb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aizwys.cn/Article/details/gthhskbekd.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljtnfeyr.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gtbodsppyj.html

[U82] JS：package.json 脚本
来源：http://dali.daxiang520.top/Article/details/gtnznrkksm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqvofpsb.html


<!-- 参考信息 -->