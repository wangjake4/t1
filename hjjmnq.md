代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.jqgfzy.top/Article/details/gtaixsbzpk.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtbefzebrf.html

std::vector<int> w = std::move(v);
来源：http://dali.cashguo.top/Article/details/gtangaqwtq.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtdczosfpe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gttjpedcwr.html

[S55] C++：结构化绑定
来源：http://dali.gotoacloud.top/Article/details/gtqzjbvkys.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gthemkwqpj.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtubzfujyd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hfpthk.cn/Article/details/gteyaverel.html

[S57] C++：编译期常量
来源：http://dali.redwolf501.top/Article/details/gtudmqrjaq.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtlbfujghw.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtbmvicreo.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtpvnhnhmd.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtuzxepkhf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gtnnbrlrzo.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcubfnzkh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.bjfxy.top/Article/details/gtcghezjwg.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtsihvhchw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtteoxafvm.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtjgnmkdqa.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmxhgkbxn.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtrjpqiwsz.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtokrcfpox.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gtdexliqfq.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtjtdqvlpq.html

"值: $b"
来源：http://dali.jinqigfzy.top/Article/details/gtbkvqofis.html

[T04] Kotlin：空安全
来源：http://dali.xuanzx.com/Article/details/gtltfhoxrp.html

val n: String? = null;  n?.length
来源：http://dali.svipenyu.cn/Article/details/gtoakpjjyq.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtnnyhjjyu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtunplmxkx.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtjqxwmivo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtxkrtuxyg.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtfxtyzvvp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulwvffqs.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gtauqrjlqp.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtzrjyecyr.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtaikhhpir.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gtmszwzbho.html

[T10] Kotlin：默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtjlmnvhhp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtqhfohagt.html

[T11] Kotlin：协程
来源：http://dali.nanxuanxn.top/Article/details/gtggvmevhv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtmuwqbdol.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gtgxatbmbt.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxinkj.top/Article/details/gtsxinhetd.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtzzdqbqig.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtwdnybuiv.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtibfzbtvr.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtswjorqas.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtqmiqrxcu.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gtdghvrtas.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtmjdqjmap.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtaskcbdje.html

[T17] Swift：变量与常量
来源：http://dali.aizwys.cn/Article/details/gtmfvgfchd.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtfehivnbs.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgnsnwyh.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsseiyizg.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtufbeplud.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gttczmpesb.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtzrlriagz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtpifgdaqa.html

[T21] Swift：遍历
来源：http://dali.cqqwz.cn/Article/details/gtpzifdrsn.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gtkjooiokx.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtippnxfwi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gtzidgpojr.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtlxopqzti.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyidtszz.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtuhhuydsy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtznauigpt.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtcifnzghn.html

struct P { var x: Int }
来源：http://dali.fzhhl.top/Article/details/gtdzessmos.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtvfpafsoj.html

class A: Base { override func f() {} }
来源：http://dali.yuanzhike.top/Article/details/gtqsygakdm.html

[T27] Swift：错误处理
来源：http://dali.yuxming.cn/Article/details/gtxkwtipxw.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtyhbbvbih.html

[T28] Swift：枚举
来源：http://dali.yuanzhike.top/Article/details/gtxeqbxtwo.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gtqwjsmagh.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtaobqozud.html

guard let x = opt else { return }
来源：http://dali.jinqigufen.top/Article/details/gttfujblak.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtezxkjktu.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtnnzjkyvx.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtbflgbpcx.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gttalsyxty.html

[T32] Lua：局部变量
来源：http://dali.cheryme.top/Article/details/gtjvxdpavg.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdesqugko.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtqxezjree.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtkfbvcngf.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gtyaeifmpg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtocpbyxqd.html

[T35] Lua：字典表
来源：http://dali.yanxiufei.cn/Article/details/gtgtgsnkzb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtzsgyobjp.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtcwkezgqg.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtvzzprfax.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtjndptjrj.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtzhimygci.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtvgxjceuy.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtogdllwey.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfksdsvqr.html

string.find(s, "%d+")
来源：http://dali.havefunace.top/Article/details/gtlyvwmukj.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtcgsyzyxy.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtxqvjewlh.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gtcijcfbsh.html

print "Hello\n";
来源：http://dali.fengsongda.top/Article/details/gtbsqzryez.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtlfnbvbqu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtecbsuewm.html

[T43] Perl：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtnynrpohd.html

"值: $a"
来源：http://dali.feifeiyinyue.top/Article/details/gtybfnsurj.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtmzhobndn.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahcwwsxy.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtgijjladb.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtramfyzfi.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gtgkxzvwbu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtykqzbsjf.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtjodgjkvv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtojsvsiov.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gttzdgbvaz.html

$s =~ s/old/new/g;
来源：http://dali.yangfankeji.com/Article/details/gtooalzxas.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gtxnvdzawz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gtxkgfpsyu.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtebysevcd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanesrqre.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtfpwitvrt.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtlzgvzmxo.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gthpytwvfx.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gtgosxjgtu.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gtwvpsyypx.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtfubwbdsu.html

s"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gtoibtywfy.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gthfgdoxkv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gtzubfifqq.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtovgwiwcm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gtuniqhmlv.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtbruehbqz.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gtrztnedwv.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtzkggeipk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtjgnoovsf.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosvhrwxr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtobvlogfo.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajykdpgr.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtsebuqqqe.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gthxwyydcx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtztmkffen.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtfecnfhvk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtqfxruoax.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtioaewpug.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gtiunlxhoq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtthapndbu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhpxckkw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gteymmsuxl.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtdpypzzyp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gtpjandfjx.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gthemwaqmd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gthhvuysao.html

[U05] Py：列表去重且保序
来源：http://dali.iojbl.cn/Article/details/gtrkjcvxqw.html

list(dict.fromkeys(arr))
来源：http://dali.yongpay.top/Article/details/gtxyzzxjjd.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtdfdohpvf.html

{**a, **b}
来源：http://dali.guannengcc.top/Article/details/gtdqmylhpm.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtetjjemar.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtzebgporx.html

[U08] Py：展平二维列表
来源：http://dali.yongpay.top/Article/details/gtqpbmmzjk.html

[y for x in nested for y in x]
来源：http://dali.0kj1m.cn/Article/details/gtwkbcqmqp.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gtgbikmovb.html

max(d, key=d.get)
来源：http://dali.yvedp.cn/Article/details/gtjxkfazjo.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtrchxdwxp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gtxesvilnw.html

[U11] Py：生成器表达式
来源：http://dali.zhengqikj.top/Article/details/gtcggvtdsr.html

(x * 2 for x in arr)
来源：http://dali.cucudq.cn/Article/details/gtpqazpqil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtooxkpkpp.html

Counter(arr).most_common(3)
来源：http://dali.chenzaomai.com/Article/details/gtmqekraob.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gtutjpvynx.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gtabsmyxkq.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gtrnmlagfl.html

defaultdict(list)
来源：http://dali.smart0.xyz/Article/details/gtvthpkkyd.html

[U15] Py：高精度计时
来源：http://dali.ybcxt.top/Article/details/gthymhafkg.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtbyviusly.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gttdojzmww.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cheryme.top/Article/details/gtxrbyfgmg.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtsuwiecwa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtjdjnqjbc.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gtxmrkxovz.html

pat = re.compile(r"\d+")
来源：http://dali.sweek.top/Article/details/gtxsvluubb.html

[U19] Py：正则替换带回调
来源：http://dali.hammf.cn/Article/details/gtbtagvohq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ppjwa.cn/Article/details/gtztmqjrzh.html

[U20] Py：缓存函数结果
来源：http://dali.gotoacloud.top/Article/details/gtxnjthail.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtfchoqlzj.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gtiwphaeye.html

@contextlib.contextmanager
来源：http://dali.jinghuilouyu.cn/Article/details/gttppauyoz.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtgvqkmstb.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gtizilqutd.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtzpwvzisn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenjidiqi.icu/Article/details/gtotdsqcxk.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtvlkvafga.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yonumen.top/Article/details/gtdnpizutn.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gtnnlxzzek.html

csv.DictReader(f)
来源：http://dali.guannengcc.top/Article/details/gtyqrbbsmo.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gtngpfcktg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gtfoxeswtr.html

[U27] Py：异步 HTTP
来源：http://dali.vqdsnc.cn/Article/details/gtivedjyvu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpyzwxlh.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzufgllmc.html

UserId = int
来源：http://dali.yj202588.top/Article/details/gtaazccehg.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtenjboqjw.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqptzffvm.html

[U30] Py：数据类
来源：http://dali.yuanzhike.top/Article/details/gtsbnymjic.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtuxworque.html

[U31] Py：单测
来源：http://dali.hnqzz.top/Article/details/gtouktiuyy.html

python -m pytest -q
来源：http://dali.hnxiangtu.top/Article/details/gtfjoanowq.html

[U32] Py：代码格式化
来源：http://dali.meibo888.top/Article/details/gtiajphcel.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gthvozbpqo.html

[U33] Py：打包发布
来源：http://dali.shangyingyoupin.top/Article/details/gttbxozhnl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvaxhinn.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtsubemkcm.html

chardet.detect(raw)
来源：http://dali.jqgufenzy.top/Article/details/gttflbltao.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtacbvuets.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cucudq.cn/Article/details/gtawhduppp.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gthbaupkyv.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhengqikj.top/Article/details/gtmaxeovzo.html

[U37] Py：读写 Excel
来源：http://dali.vqdsnc.cn/Article/details/gtbwalmeca.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtuxniiptu.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtfdfozmec.html

Path(__file__).resolve().parent
来源：http://dali.ppjwa.cn/Article/details/gtqojwyyqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxuanxn.top/Article/details/gtmlmtyfuc.html

sys.stdout.isatty()
来源：http://dali.cheryme.top/Article/details/gthsjgwucc.html

[U40] Py：打印到标准错误
来源：http://dali.gogol.net.cn/Article/details/gtihxqziuj.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtylbddgfq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gtritfwzyw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gtivelmgxj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.haohaochexian.top/Article/details/gtjbxkqien.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gtltzuqhej.html

[U43] PHP：声明命名空间
来源：http://dali.redwolf501.top/Article/details/gtdguddzyy.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtalmloquw.html

[U44] PHP：开启严格类型
来源：http://dali.c1oappe.top/Article/details/gtbjrrsplq.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gthndigjae.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ybcxt.top/Article/details/gtoafbakih.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtyiolkkgp.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gttybotzjn.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gtarvhcfml.html

[U47] PHP：联合类型
来源：http://dali.hywenlv.cn/Article/details/gtzqhrgbqt.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gttufnbyic.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtouefvniq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.redwolf501.top/Article/details/gticseyonw.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gtyaupwavq.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gtvwzavgjx.html

[U50] PHP：构造器属性提升
来源：http://dali.chenjidiqi.icu/Article/details/gtdzktrrly.html

public function __construct(private int $id) {}
来源：http://dali.ydzc1.top/Article/details/gtzgmiddwa.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gteqzwicjn.html

[$a, $b] = $arr;
来源：http://dali.sweek.top/Article/details/gtddkfesry.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtvcigbcmn.html

$double = fn($x) => $x * 2;
来源：http://dali.nwbrower.top/Article/details/gtuvzxwbfx.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtidmdsnza.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gtktgnyjke.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtcuveoicl.html

$obj?->method()
来源：http://dali.pycfn.com/Article/details/gtfyhfivsl.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gtjlvzrakx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwzepjjs.html

[U56] PHP：命名参数
来源：http://dali.jinqigufen.top/Article/details/gtvfhfogqv.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtpgizgdle.html

[U57] PHP：字符串插值
来源：http://dali.yongpay.top/Article/details/gtjzpsvrih.html

"值: {$a}"
来源：http://dali.cheryme.top/Article/details/gtqtcfwewq.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gtslyxuuxp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gtwksjjsrt.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtiokhbohp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yvedp.cn/Article/details/gthdipzhte.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtnfuonuyg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.snrcjt.cn/Article/details/gtctcnvvkg.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtxvdwdxlw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgfzy.top/Article/details/gtsopwoszj.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtliduydit.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gtjoxjalmm.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gtckjltidc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hnxiangtu.top/Article/details/gtbrxpjjxr.html

[U64] PHP：目录遍历
来源：http://dali.yuxming.cn/Article/details/gthybekqak.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yuxming.cn/Article/details/gtvywgvzkp.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gtldaqroie.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtmwdhamvc.html

[U66] PHP：设置 Cookie
来源：http://dali.ehwqpu.com/Article/details/gtpsgjrviz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinqigfzy.top/Article/details/gtvstavlsv.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqneomjyv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtgogeioxh.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gthtolvzzd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gtnresbgqf.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gtxqygwygo.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.svipenyu.cn/Article/details/gtgwphznoz.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtdujrmjbm.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gtsenrxazm.html

[U71] PHP：抛出异常
来源：http://dali.daria6918.cn/Article/details/gtnqdqdusm.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtirifkpgs.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtvxedbvnb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gtqehncqvp.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gtgegdcffk.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gtoniipdla.html

[U74] PHP：读取环境变量
来源：http://dali.pycfn.com/Article/details/gtzagphpoy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajvicojv.html

[U75] PHP：依赖注入
来源：http://dali.kuanghao11.cn/Article/details/gthhfodnza.html

composer require psr/container
来源：http://dali.316326.xyz/Article/details/gtwyeragyu.html

[U76] PHP：简单路由
来源：http://dali.havefunace.top/Article/details/gthlidjyuy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.aibaodan.cn/Article/details/gtrnwoaajv.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gtxhujzevk.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtnyisqboq.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtqqowbmmu.html

composer require --dev phpunit/phpunit
来源：http://dali.yanxiufei.cn/Article/details/gtlevraxyv.html


<!-- 参考信息 -->