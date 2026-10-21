代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gtaqxbsbim.html

[S55] C++：结构化绑定
来源：http://dali.yangfankeji.com/Article/details/gtfmodzjvy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gtiishsvwk.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtbmhvekyb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtpqffaivi.html

[S57] C++：编译期常量
来源：http://dali.dashuyun.cn/Article/details/gtbhbyhtxx.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtjqtqxrwl.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gttrisvhgu.html

namespace ns { int f() { return 1; } }
来源：http://dali.jyoumei.cn/Article/details/gtwcuyznep.html

[S59] C++：静态断言
来源：http://dali.meibo888.top/Article/details/gtzgskhoon.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtsfczxtfl.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtgynafyjf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtoehnklkj.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtdechgjdq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtpgenootn.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtstxecqyw.html

[T01] Kotlin：Hello World
来源：http://dali.hammf.cn/Article/details/gtabechmed.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtkrthcxkc.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtfpgnxfjm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtjefhsejv.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gttzimnhue.html

"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtlvciydkg.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gtarfvmrlw.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtbdwdcbvo.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtwzspmqyl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gtvdevbajr.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gthfmhqlln.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gtztixqueq.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtbvpefyzj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gttvdrcoyc.html

[T08] Kotlin：数据类
来源：http://dali.hfpthk.cn/Article/details/gtipblmlrq.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258.top/Article/details/gtaaruhnhy.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtyhyweprp.html

fun String.exclaim() = this + "!"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvibkqkil.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtxigyjciz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ydzc1.top/Article/details/gtcemqozhy.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzozdsrcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtoaqxevmo.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtswgcevxq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtenveodyq.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtiroglsqv.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtevkvivzi.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gtauimmsvn.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtxtrapvph.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gtleblrdhp.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtyunbrjrf.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtdrcxfzjy.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gthhmhjmhf.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtxfbwfvem.html

var a = 1;  let b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtugqwxkph.html

[T18] Swift：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtdczalxht.html

"值: \(b)"
来源：http://dali.shuidangran.top/Article/details/gtutanopzj.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtovzcsoin.html

if let n = opt { print(n) }
来源：http://dali.jlsjyb.cn/Article/details/gthsucscsb.html

[T20] Swift：数组操作
来源：http://dali.hywenlv.cn/Article/details/gtbspczxtl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtnnoctrad.html

[T21] Swift：遍历
来源：http://dali.0kj1m.cn/Article/details/gtiukmesaa.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gtuvrvxkus.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtyejpeqmn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtughycqou.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gtxnclpgod.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gthgtydixh.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gtmmoqhgae.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtytaycrhl.html

[T25] Swift：结构体
来源：http://dali.ppjwa.cn/Article/details/gttpdgkvba.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gtpqnkahyc.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtqwuszfjb.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtcresjjwj.html

[T27] Swift：错误处理
来源：http://dali.jlsjyb.cn/Article/details/gtgjxndjfr.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258.top/Article/details/gtypaklfpy.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtibajaiuh.html

enum Color { case red, green }
来源：http://dali.shzxlz.cn/Article/details/gtnqfsjysu.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtsozpqwqt.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtxpiiiusc.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtouibebme.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gtiiofoaas.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnaxvhmu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtcmayxify.html

[T32] Lua：局部变量
来源：http://dali.shzxlz.cn/Article/details/gtwtyrgwlo.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtevukfuvj.html

[T33] Lua：表（数组）
来源：http://dali.yuxming.cn/Article/details/gtcxxtwqdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtzrlazpwk.html

[T34] Lua：遍历表
来源：http://dali.feifeiyinyue.top/Article/details/gtodyvbmlv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtakojkfal.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gtqddemaxu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gtahbczvfy.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtiajkxvgx.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtktptujks.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gttmixyjgr.html

"a" .. "b"
来源：http://dali.aizwys.cn/Article/details/gtvtjdvezp.html

[T38] Lua：条件
来源：http://dali.daxiang520.top/Article/details/gtybfiacrr.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtlfvizomm.html

[T39] Lua：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtiwziupnq.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gtwenwjcme.html

[T40] Lua：元表
来源：http://dali.feifeiyinyue.top/Article/details/gthfppablw.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtyvhwiukl.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtruyqkytf.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtdglpfucj.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gtowigpfwo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevgenrnk.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtiblgercf.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gtkvikwudb.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtofyuxlmc.html

if ($a > 0) { print "正"; }
来源：http://dali.xylfe.cn/Article/details/gtrvkqkaky.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtliyhhfxq.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzuxuusek.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gtotnsezto.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtvksyukyn.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtyvidiyxz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gtamcayzgx.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtmovmrkbd.html

$s =~ s/old/new/g;
来源：http://dali.iojbl.cn/Article/details/gtiszzqpmh.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gttvajhmfl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtehqhwlzb.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtnbfglsyh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangshuangyany.cn/Article/details/gtnfcgcbyx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gthecbasoi.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtcptrplqe.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtmwfrkcpl.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtsibgzujk.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtctegdght.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtmudrwjpq.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtqfkvdvsb.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtbwupqmll.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtvjlvjedc.html

[T55] Scala：集合过滤
来源：http://dali.yvedp.cn/Article/details/gtptsfyhmf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cdnleiting.top/Article/details/gttmgxgiju.html

[T56] Scala：样例类
来源：http://dali.fengsongda.top/Article/details/gthvsdcwad.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtibsegsxn.html

[T57] Scala：模式匹配
来源：http://dali.fengsongda.top/Article/details/gtxnqblrfq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtrbqobjnz.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gtqkvsylpk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtjolpyygo.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gtkusbfhku.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtnxrjqloi.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gtzpteruye.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gtglzysvoe.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtayixbvoa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gtkidkdmpu.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvfycfsmh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtxtvixfcc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtxlltsnpe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtnespxpzr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtoobqubpz.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtzkovgqgy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtstpvqito.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtlbxkxfcn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtsskwlnof.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtbjjmrdhy.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtaxbvzgsx.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtfzqelumg.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gtbwromkua.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtnguabsde.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtzauczcur.html

[U08] Py：展平二维列表
来源：http://dali.yj20258888.top/Article/details/gtjcqiuwsn.html

[y for x in nested for y in x]
来源：http://dali.jqgufenzy.top/Article/details/gtsleaenvu.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtqyrkodmg.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtnlrrywfs.html

[U10] Py：按值排序字典
来源：http://dali.yj202588.top/Article/details/gtorbjxzbo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtutucyvfm.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtetebccxb.html

(x * 2 for x in arr)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprmazize.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hywenlv.cn/Article/details/gtljkkezar.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gtdzbzmhww.html

[U13] Py：固定长度队列
来源：http://dali.jlsjyb.cn/Article/details/gtgycituxb.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gttkdgvafu.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gttfohnzhg.html

defaultdict(list)
来源：http://dali.chenjidiqi.icu/Article/details/gtqigdkhqx.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtipqoyrla.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gtbtekeebc.html

[U16] Py：命令行参数解析
来源：http://dali.hfpthk.cn/Article/details/gtqdigrmkr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ybcxt.top/Article/details/gthhdrkizy.html

[U17] Py：初始化日志
来源：http://dali.pycfn.com/Article/details/gtnpkheqzg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqdnqaowz.html

[U18] Py：预编译正则
来源：http://dali.aibaodan.cn/Article/details/gthwyyruvt.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtzjhefpgv.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtigborraa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dianchejie.cn/Article/details/gtlcjprpex.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gthkhckhmh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtcqzqpghq.html

[U21] Py：自定义上下文管理器
来源：http://dali.cqqwz.cn/Article/details/gthavnjeud.html

@contextlib.contextmanager
来源：http://dali.zhiwuduotai.top/Article/details/gtgjbcymhv.html

[U22] Py：矩阵转置
来源：http://dali.sysykeji.top/Article/details/gtohgdcdrp.html

list(zip(*m))
来源：http://dali.sweek.top/Article/details/gtmlcmyply.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gtwkgqnsll.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sysykeji.top/Article/details/gttzbculkc.html

[U24] Py：路径操作
来源：http://dali.wangdashe.top/Article/details/gtiqrxuqno.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtxeaekrzw.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtwvkzaeym.html

csv.DictReader(f)
来源：http://dali.shangyingyoupin.top/Article/details/gthqtqvylv.html

[U26] Py：并发下载
来源：http://dali.chenzaomai.com/Article/details/gtucbbpnut.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelivtyxd.html

[U27] Py：异步 HTTP
来源：http://dali.hnqzz.top/Article/details/gtgmopktbt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gtxtulpmsv.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gtodowirna.html

UserId = int
来源：http://dali.sweek.top/Article/details/gtmoiusofn.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtlxrrproi.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gtkgmqwjiw.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtfllikphb.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gttmtnvrky.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtberqqbtf.html

python -m pytest -q
来源：http://dali.ybcxt.top/Article/details/gtgesphnda.html

[U32] Py：代码格式化
来源：http://dali.jqgufenzy.top/Article/details/gthmvnzpzt.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gtxaemyyhn.html

[U33] Py：打包发布
来源：http://dali.haohaochexian.top/Article/details/gttnxbtvcj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtabwzzuob.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gtfzyfbdqg.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklfzhvwu.html

[U35] Py：发送邮件
来源：http://dali.yj202588.top/Article/details/gtxybwtwpb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guannengcc.top/Article/details/gtehqcbssc.html

[U36] Py：定时任务
来源：http://dali.zhixingplan.top/Article/details/gthpmlwmbg.html

schedule.every(10).minutes.do(job)
来源：http://dali.aibaodan.cn/Article/details/gtbpnexvbd.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtchnjybqj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gtrgnnjoqd.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtuksmvewl.html

Path(__file__).resolve().parent
来源：http://dali.smart0.xyz/Article/details/gtzfmycecm.html

[U39] Py：判断是否在交互环境
来源：http://dali.hnqzz.top/Article/details/gtyfyryigy.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gtmtrkuekg.html

[U40] Py：打印到标准错误
来源：http://dali.jianghu66.top/Article/details/gtqfqadiwj.html

print("err", file=sys.stderr)
来源：http://dali.jianghu66.top/Article/details/gtyacsemdd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gtvopsstbe.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmmhvubps.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtaiofymrd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtahqhczsf.html

[U43] PHP：声明命名空间
来源：http://dali.cucudq.cn/Article/details/gttaiqolht.html

namespace App\Http;
来源：http://dali.cheryme.top/Article/details/gtwvevxked.html

[U44] PHP：开启严格类型
来源：http://dali.meibo888.top/Article/details/gtupzrsrig.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtynlslbyj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.kuanghao11.cn/Article/details/gtvskwmwtx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzagkggdx.html

[U46] PHP：可空类型
来源：http://dali.dianchejie.cn/Article/details/gtekzwqurg.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gtlwhlesfk.html

[U47] PHP：联合类型
来源：http://dali.tianlin.xyz/Article/details/gtkjebtbfv.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gtguhkkaqt.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gtyxhdbixa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yanxiufei.cn/Article/details/gttlbadchy.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtjwyepaup.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtprlzlize.html

[U50] PHP：构造器属性提升
来源：http://dali.snrcjt.cn/Article/details/gtrcznkiwl.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gtyhtzbmoa.html

[U51] PHP：数组解构
来源：http://dali.xinyue.icu/Article/details/gtnawjbuhn.html

[$a, $b] = $arr;
来源：http://dali.nanxinkj.top/Article/details/gtanmvhjzp.html

[U52] PHP：箭头函数
来源：http://dali.316326.xyz/Article/details/gtyytjbzth.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtegtyphek.html

[U53] PHP：空合并运算符
来源：http://dali.iojbl.cn/Article/details/gtqmbitxlf.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinyuanbaomall.cn/Article/details/gthslhiver.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gtqthcuxil.html

$obj?->method()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkaxwpvte.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gtjodhhdhz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtsmaojvxy.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gtkimwkdhu.html

f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtklaakxgj.html

[U57] PHP：字符串插值
来源：http://dali.tanke756.top/Article/details/gtdajjebwn.html

"值: {$a}"
来源：http://dali.xziqi.cn/Article/details/gtptzgbehv.html

[U58] PHP：数组三件套
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrucdorp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtlwxxnwyb.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gtwzpeokgf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gtgurthisr.html

[U60] PHP：JSON 编解码
来源：http://dali.xinyue.icu/Article/details/gtzqkhcmkp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtjsskffvr.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtpgcwhukz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangshuangyany.cn/Article/details/gtwcxgfudj.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gtzlwxzseb.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangshuangyany.cn/Article/details/gtuguhakol.html

[U63] PHP：文件读写
来源：http://dali.jianghu66.top/Article/details/gtzegsjoyw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtthcshfel.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gtsuegxodf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuanzhike.top/Article/details/gtcucouklo.html

[U65] PHP：会话
来源：http://dali.dashuyun.cn/Article/details/gtmrboucgt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtcrzaxjkz.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjgaichf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gtwwrvnyyr.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtyosdivon.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cheryme.top/Article/details/gttrmjxiqx.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gtrprnrras.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gtkzshbpmg.html

[U69] PHP：PDO 预处理
来源：http://dali.cheryme.top/Article/details/gtewlpeglw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtuorgqtfk.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtinjjfcxx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.316326.xyz/Article/details/gtlecnepsd.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gtdtkyujcs.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttonbnxhy.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtsctcdjkm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtntzxebje.html

[U73] PHP：读取 ini 配置
来源：http://dali.daria6918.cn/Article/details/gtbvewokvl.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtvbqjkyev.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtwmzqmrck.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hfpthk.cn/Article/details/gtsphrlrqv.html

[U75] PHP：依赖注入
来源：http://dali.cdnleiting.top/Article/details/gtmqdfvrdn.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtsjxnuecu.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gtdewndpad.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daria6918.cn/Article/details/gtouwnqnhd.html

[U77] PHP：模板渲染
来源：http://dali.jianghu66.top/Article/details/gtkqbmyxxx.html

composer require twig/twig
来源：http://dali.jqgufenzy.top/Article/details/gtkaizkzxn.html

[U78] PHP：单元测试
来源：http://dali.c1oappe.top/Article/details/gtjhzwnzyr.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyjebqplq.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gtanmkfllz.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gtuksdegmh.html

[U80] PHP：代码规范修复
来源：http://dali.sxryk.cn/Article/details/gtcyffjtnu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xylfe.cn/Article/details/gthoxvvonh.html


<!-- 参考信息 -->