代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtzrqesyxk.html

[S53] C++：移动语义
来源：http://dali.feifeiyinyue.top/Article/details/gtryhhzshi.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtnvzqzpgj.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtkjfiphmg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzruwxcfr.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gthxbttujw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gttlpfunnu.html

[S56] C++：optional
来源：http://dali.cashguo.top/Article/details/gtszaccjzh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtuibhphii.html

[S57] C++：编译期常量
来源：http://dali.gaohongyu789.top/Article/details/gttanlefxs.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gtlpruwogw.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gtlqjxjrnp.html

namespace ns { int f() { return 1; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtelnngzmx.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gteelnajdu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthaziblrg.html

[S60] C++：遍历并删除元素
来源：http://dali.gogol.net.cn/Article/details/gtbrzgcmpm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtfjwnpwtb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqwovgpvn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.guowangkeji.top/Article/details/gtxbsbqoqo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtvzssrcfn.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtdyhpbxvm.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtmapddvku.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdzcfieaq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gthmtaseaw.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gturxhwtkm.html

"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtpdqzgrzr.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtfjjubrxx.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtuurohkkz.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtxhijyreb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtmrnoujqp.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gtoevkgucc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtlrosgwqc.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxicgnjnc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gthsnvfgks.html

[T08] Kotlin：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtzkkwhqpf.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtltfcsteh.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gthcxxkuee.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtjjgeonwy.html

[T10] Kotlin：默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtvyrysujw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gtxipblssh.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtlueewnqb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtdaxmheav.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtmhcdoivu.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtbbfzhtwn.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtueuvdaxz.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtekksxmxh.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gthyikvbxy.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddjcsycy.html

[T15] Kotlin：接口
来源：http://dali.jqgufenzy.top/Article/details/gtavyzgpmc.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtwuzwstqa.html

[T16] Swift：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtizcrqtvp.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtgrlrvase.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gtokncocqm.html

var a = 1;  let b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtrxmuzoav.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtauggqlgp.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtxygqhtnq.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtdjbpiqgf.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtohykhbax.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gtlphovuic.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtjmmojwkl.html

[T21] Swift：遍历
来源：http://dali.hysaishi.cn/Article/details/gtquwksxck.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtxyebavos.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtvxvyptqo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gthdcrwxju.html

[T23] Swift：函数
来源：http://dali.chenzaomai.com/Article/details/gtohdqbsir.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gaohongyu789.top/Article/details/gtzjubeisk.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtigrvqnky.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtjpbfiyqf.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtcdwwzjdt.html

struct P { var x: Int }
来源：http://dali.svipenyu.cn/Article/details/gtwdshnwsu.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtcquafthh.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtjpwyysmj.html

[T27] Swift：错误处理
来源：http://dali.birdmap.top/Article/details/gtsomcdbwf.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtlcskwnvb.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gtejjcxpmb.html

enum Color { case red, green }
来源：http://dali.iojbl.cn/Article/details/gtxqjtvumt.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtbzpihegs.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtlpecaimp.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtvajtmuny.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtjozqyjhn.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtmjgqcsze.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gtpjwlhmpu.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtjqwvwpyh.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweavelwq.html

[T33] Lua：表（数组）
来源：http://dali.kuanghao11.cn/Article/details/gtiflduigv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmyfreeck.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtlalhpoah.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtkpkyfijv.html

[T35] Lua：字典表
来源：http://dali.zhixingplan.top/Article/details/gtvixdcmah.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gthdhnfhfk.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gtxljunrcb.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlqcgvbr.html

[T37] Lua：字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtzotchyul.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwoiatava.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gteiycabeu.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtylwospuq.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtqbopxfjm.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtzyrbwprt.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gtancmprzm.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtbuujeord.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtzmbmbuot.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtljgujodo.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtcfewybyd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtakqxeymd.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtjdsfltgz.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtdmmljlqe.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gtchjzvvkv.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtkwxruwcz.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtmgthlset.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtwzxgeqgk.html

[T46] Perl：哈希操作
来源：http://dali.ehwqpu.com/Article/details/gtxaocyehj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jyoumei.cn/Article/details/gteotpnnym.html

[T47] Perl：正则捕获
来源：http://dali.sufxvd.cn/Article/details/gtuolvhuis.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgufenzy.top/Article/details/gtnckjqhhb.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gtjfhlckxe.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtxgihxkpz.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gtpvcspjjs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtwphsfhjr.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtfhqwrhrr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.mhx1999.top/Article/details/gtnqtcfkso.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtmapjhuaj.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtxscmseie.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gtznbbvlnp.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtqqvpgzbp.html

val a = 1;  var b = 2
来源：http://dali.mhx1999.top/Article/details/gtxqxhjblo.html

[T53] Scala：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtbrpmrgyk.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtqzoomuxl.html

[T54] Scala：集合映射
来源：http://dali.yj202588.top/Article/details/gtpymcczbi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtzbrksecd.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtvkogephk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhijiandao.cn/Article/details/gtsoxdzwij.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtltdkgldl.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtzyeyrzxl.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtarpmpadv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gtmkkwmukf.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtqzfjfvws.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtuipbsyvy.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtqlysrsbq.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtxedyaxjh.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gthskemool.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtcpfgygnp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtrelpgkur.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtofobtpjo.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrcvomdvb.html

[U01] Py：创建虚拟环境
来源：http://dali.yvedp.cn/Article/details/gtsduabodw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gtmphipcia.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ehwqpu.com/Article/details/gttwpoorzo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtfdqytuid.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxocjrppw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtyfanyzmc.html

[U04] Py：变量调试打印
来源：http://dali.sufxvd.cn/Article/details/gtezlutvzd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gtwvytzgrf.html

[U05] Py：列表去重且保序
来源：http://dali.yuxming.cn/Article/details/gtrboaxpuy.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtzhxmvlld.html

[U06] Py：合并两个字典
来源：http://dali.gotoacloud.top/Article/details/gtmigljgtv.html

{**a, **b}
来源：http://dali.yj20258888.top/Article/details/gtmpmlqiwh.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gtcgknpnoj.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxzstrgs.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtxkvowicc.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gtpufqcrqf.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtmurfhkrv.html

max(d, key=d.get)
来源：http://dali.hnxiangtu.top/Article/details/gthnpgxcac.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gtpgmspznj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinghuilouyu.cn/Article/details/gtatwhkaff.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtfksaduto.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtltrngsct.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gtsbswaohc.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtvtqgbawf.html

[U13] Py：固定长度队列
来源：http://dali.fengsongda.top/Article/details/gtwkjutfzt.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtpnzgngnw.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gtkiwcgsen.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtanxsovtm.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gtaqqgfpsf.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbxprbnok.html

[U16] Py：命令行参数解析
来源：http://dali.nanxinkj.top/Article/details/gtjruipicl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sweek.top/Article/details/gtrazyzxhd.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gtkbzejbac.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tianlin.xyz/Article/details/gtgnqavnue.html

[U18] Py：预编译正则
来源：http://dali.shzxlz.cn/Article/details/gtbsgzprmn.html

pat = re.compile(r"\d+")
来源：http://dali.ydzc1.top/Article/details/gtwkneqmes.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtwhupegjv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtebnoqbvq.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtumydvuwq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gtpktrxdtp.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gtuklxefui.html

@contextlib.contextmanager
来源：http://dali.sweek.top/Article/details/gtqednrghe.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gtajgfszkv.html

list(zip(*m))
来源：http://dali.hammf.cn/Article/details/gtrtofjesj.html

[U23] Py：分块读取大文件
来源：http://dali.hfpthk.cn/Article/details/gtvnfmpcrm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.aizwys.cn/Article/details/gtoyapngqm.html

[U24] Py：路径操作
来源：http://dali.fengsongda.top/Article/details/gtbmurvjzy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sweek.top/Article/details/gtqaygkzku.html

[U25] Py：CSV 按字典读
来源：http://dali.yj20258888.top/Article/details/gtkadodrsx.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gtpyjeuksb.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtnqnouzkt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gtdwzvllpx.html

[U27] Py：异步 HTTP
来源：http://dali.jianghu66.top/Article/details/gtmmqzikuo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhongyouzk.top/Article/details/gterwrlnbh.html

[U28] Py：类型别名
来源：http://dali.vqdsnc.cn/Article/details/gtwijhrslx.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gtccjshqdt.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtbclporwg.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gtrtjrkust.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtpqxfgczc.html

@dataclass(slots=True)
来源：http://dali.yuanzhike.top/Article/details/gtygeqsgrn.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gtozmuddoj.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtibsyokbg.html

[U32] Py：代码格式化
来源：http://dali.xuanzx.com/Article/details/gtgrlyeakx.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gthszabidz.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gthdkahlnr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gtchclbxbw.html

[U34] Py：判断编码
来源：http://dali.ehwqpu.com/Article/details/gtqravbdgb.html

chardet.detect(raw)
来源：http://dali.nanxuanxn.top/Article/details/gttyvhjfue.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtsodwqrmt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ydzc1.top/Article/details/gtimdtswyt.html

[U36] Py：定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtjuvxrspv.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangshuangyany.cn/Article/details/gtzlkutohe.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtoigcqetv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gttyxbtvpa.html

[U38] Py：获取脚本所在目录
来源：http://dali.xinyue.icu/Article/details/gtzlkrngxa.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtcoaumwux.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtddoeomnz.html

sys.stdout.isatty()
来源：http://dali.zdqjudy.top/Article/details/gtqydsgixi.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtnpkvovdu.html

print("err", file=sys.stderr)
来源：http://dali.c1oappe.top/Article/details/gtmrhyptbv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gtczrxhfbj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gtcmlgtafp.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtaufjkkeu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gtiselyhni.html

[U43] PHP：声明命名空间
来源：http://dali.chenzaomai.com/Article/details/gtmbswbaub.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtudzjdfmf.html

[U44] PHP：开启严格类型
来源：http://dali.smart0.xyz/Article/details/gtfrshqoke.html

declare(strict_types=1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtufuunrvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtepvvhath.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtspbuvmsz.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtyaxxtquf.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gtolrkrvmp.html

[U47] PHP：联合类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxbivskc.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtzmiixihb.html

[U48] PHP：纯枚举
来源：http://dali.hfpthk.cn/Article/details/gtmwiyskeq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gtqebwzdfd.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gtshpgammm.html

public readonly string $name
来源：http://dali.bjfxy.top/Article/details/gttrggvyfk.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gtsureffay.html

public function __construct(private int $id) {}
来源：http://dali.jianghu66.top/Article/details/gtaetoejgm.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtrfdozpnz.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtpkszcyvj.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtmzuslysh.html

$double = fn($x) => $x * 2;
来源：http://dali.birdmap.top/Article/details/gtrypiobiv.html

[U53] PHP：空合并运算符
来源：http://dali.snrcjt.cn/Article/details/gtvicymasr.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gtiatvpnbh.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gtohbkjrkq.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gthtugpqwq.html

[U55] PHP：match 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtrltgblfo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gtrtubnkxe.html

[U56] PHP：命名参数
来源：http://dali.yangfankeji.com/Article/details/gthtdtuosm.html

f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtafivrgjj.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtjgkryxgi.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gtwdxovdwf.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtngfltajl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gtjjrnqpon.html

[U59] PHP：自定义排序
来源：http://dali.sweek.top/Article/details/gtipgtbaon.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtwdpczpbj.html

[U60] PHP：JSON 编解码
来源：http://dali.jyoumei.cn/Article/details/gtanatjgtg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hfpthk.cn/Article/details/gtwjbucaqd.html

[U61] PHP：正则
来源：http://dali.sweek.top/Article/details/gtodwxhsyh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gtxpwpmzms.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmdrudps.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sxryk.cn/Article/details/gtzhxvrrri.html

[U63] PHP：文件读写
来源：http://dali.sxryk.cn/Article/details/gtdytemovj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tianlin.xyz/Article/details/gtznqekyjy.html

[U64] PHP：目录遍历
来源：http://dali.havefunace.top/Article/details/gtdjrofdmb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gtgnraktto.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gtubdmwaxf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtdeyheuwl.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gtuewykyyf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xziqi.cn/Article/details/gtsnlhwcnw.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gtmzdsdxoy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtasidttaz.html

[U68] PHP：PDO 连接
来源：http://dali.ppjwa.cn/Article/details/gtwpmpgadh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.nanxinkj.top/Article/details/gtxnyobcbt.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtajwuwmug.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jianghu66.top/Article/details/gtrcbhyyfi.html

[U70] PHP：PDO 事务
来源：http://dali.fzhhl.top/Article/details/gtyctfimcl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtygzoumby.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtemvvkxqi.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gtgvlflabs.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gtwaxkkjav.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtajpdbwgd.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtktkdgwlc.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtzxylxeqw.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtxwadlvhn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gttgqbopxd.html

[U75] PHP：依赖注入
来源：http://dali.shuidangran.top/Article/details/gtodbpgixh.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gtvpkitzag.html

[U76] PHP：简单路由
来源：http://dali.sufxvd.cn/Article/details/gtdmhikmwa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtsyekrgbe.html

[U77] PHP：模板渲染
来源：http://dali.yonumen.top/Article/details/gtkpkemlrh.html

composer require twig/twig
来源：http://dali.zhengqikj.top/Article/details/gttklkzmix.html

[U78] PHP：单元测试
来源：http://dali.wangdashe.top/Article/details/gthphktqqk.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtgeshjuab.html


<!-- 参考信息 -->