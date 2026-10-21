代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.aizwys.cn/Article/details/gtcpcjfsng.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtmappadxa.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtjwpiokko.html

[S50] C++：格式化数字
来源：http://dali.xinyue.icu/Article/details/gtysqkbltf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gthdvadgaf.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gtdhzhazln.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gtcwbpeunb.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gtostpdbrq.html

int size() const noexcept { return n_; }
来源：http://dali.quarkkingdee.top/Article/details/gtvbskrbew.html

[S53] C++：移动语义
来源：http://dali.dashuyun.cn/Article/details/gtccdbqpss.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtawbmajdm.html

[S54] C++：异常处理
来源：http://dali.cheryme.top/Article/details/gtctxjajyz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pycfn.com/Article/details/gtkqljmslf.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtzyulrxus.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtznskfrts.html

[S56] C++：optional
来源：http://dali.xuetiantiany.cn/Article/details/gtzllqqymj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aibaodan.cn/Article/details/gtwleimgsl.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtubjilonc.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtprfileev.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtebzmxako.html

namespace ns { int f() { return 1; } }
来源：http://dali.hfpthk.cn/Article/details/gtmxbtdrfk.html

[S59] C++：静态断言
来源：http://dali.yongpay.top/Article/details/gtsufzhkob.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cashguo.top/Article/details/gtcxsovxdq.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtlnnazpmq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtpumftxrd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlfajmdtf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gtdbklqmjm.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtzeugdylr.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtpovgvobk.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtqpheujqr.html

[T02] Kotlin：变量
来源：http://dali.hammf.cn/Article/details/gtqsbrkeyx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aizwys.cn/Article/details/gtctufxwrn.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtkvtuxiel.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gtiaafaudt.html

[T04] Kotlin：空安全
来源：http://dali.cheryme.top/Article/details/gtjstqmbie.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtouvtqdih.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtegpfuekt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtpxmlfklr.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtuiwuvaly.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtmhemlpdg.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtkldbhabi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtvoxpzusw.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtoucrvqqz.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtqycljwtn.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtdkdwvcjv.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtfkpeuzjr.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtaegxxiqo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenzaomai.com/Article/details/gtyhhfnqzf.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtgjzecqjd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtxwoefcqy.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtvxqsnpuh.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtrystqqwr.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gtmfzxkedp.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtcuijpowc.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtbbqpunsr.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtowwirqys.html

[T15] Kotlin：接口
来源：http://dali.yanxiufei.cn/Article/details/gtdfyopunc.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtudwqdzta.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtzkswbfjj.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtxxwoxzdy.html

[T17] Swift：变量与常量
来源：http://dali.316326.xyz/Article/details/gtnkjvlwqy.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gtlmpwjlmk.html

[T18] Swift：字符串插值
来源：http://dali.tanke756.top/Article/details/gtmxdajvnb.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiogrcva.html

[T19] Swift：可选绑定
来源：http://dali.nanxinkj.top/Article/details/gtynxtduah.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gthvwprgjp.html

[T20] Swift：数组操作
来源：http://dali.vqdsnc.cn/Article/details/gtcfsxdikd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtlubzfcwz.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtyxanybqy.html

for x in a { print(x) }
来源：http://dali.wangdashe.top/Article/details/gthzevqtkv.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtcxcnzqzx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnxiangtu.top/Article/details/gtbwenflcz.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtznkgyhzy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gtktqlybca.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtnunldhtn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gteeszhlky.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtmxpubfut.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjutkpxj.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtmltjexwa.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtrphpqgnp.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxsrwoxo.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gthnunytvz.html

[T28] Swift：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkyhrymg.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtuiicxxrp.html

[T29] Swift：guard 提前返回
来源：http://dali.hywenlv.cn/Article/details/gtqrvpmizb.html

guard let x = opt else { return }
来源：http://dali.jlsjyb.cn/Article/details/gtvcqkwtew.html

[T30] Swift：协议
来源：http://dali.jinyuanbaomall.cn/Article/details/gthpdzpckq.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gtpdsgqzvf.html

[T31] Lua：Hello World
来源：http://dali.yongpay.top/Article/details/gtableiucd.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtemglvbwl.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqoznpvsa.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gttloklagu.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtuilsulet.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gtgnglhxbz.html

[T34] Lua：遍历表
来源：http://dali.gotoacloud.top/Article/details/gtphgvyuue.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yongpay.top/Article/details/gtpzryvejh.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gtbhrxhqqo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gteygewurc.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtsafwamwb.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtplbpcnph.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtsfbreuob.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gttlibnnnk.html

[T38] Lua：条件
来源：http://dali.shuidangran.top/Article/details/gtcadtnomb.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtzgkgmgaq.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gthikcwxzo.html

string.find(s, "%d+")
来源：http://dali.nanxinkj.top/Article/details/gtcupsamwf.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtbqpydimo.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtrtgmhzhw.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtnlethrsi.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtslcyhjjh.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtpelntbyt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtnsygqltp.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtzpqmbrey.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtvvktlpyi.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtphfvmydk.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtkvoiqmax.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gtzxvueukq.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gtnlzpbekl.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnetdpyq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfgzmujyb.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gterppmqpi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtuhgqkuaa.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtrxcsidgj.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtbiuckhaw.html

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gtvubmnimt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtarhnmita.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtzpchnpzv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtdwjyxndu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gteukgpmyw.html

[T51] Scala：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdmghklez.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtcfsgnaix.html

[T52] Scala：变量
来源：http://dali.tianlin.xyz/Article/details/gtjpiczuku.html

val a = 1;  var b = 2
来源：http://dali.snrcjt.cn/Article/details/gtylkubraq.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtrfazqvwc.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtpwhlfrfq.html

[T54] Scala：集合映射
来源：http://dali.xuetiantiany.cn/Article/details/gtuqwqdidw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtianfaaad.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtctigctfx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtrhkienra.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gtrrclcnuo.html

case class User(name: String, age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtrlntincj.html

[T57] Scala：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtihvhmbyg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtpqkmgwgf.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtfcmxypsp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gtbtnazapz.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtyeihdgop.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gtqxbsonkr.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtiqdqdsnt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.fzhhl.top/Article/details/gtvdgsbcqg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtihilaalh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gtwefmqjre.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjmcqfdsx.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtjpchtzse.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtumyvdjda.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtzmjweehm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinqigfzy.top/Article/details/gttgtbygux.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gthhpjwxqq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.chenjidiqi.icu/Article/details/gtlkzgvlhp.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gtzzwbrsoi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tianlin.xyz/Article/details/gtwkxmdgxs.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtblxheddg.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtbnxtbmlr.html

[U06] Py：合并两个字典
来源：http://dali.havefunace.top/Article/details/gthplbqipw.html

{**a, **b}
来源：http://dali.xuanzx.com/Article/details/gtlzlplogc.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtgoghknyq.html

{v: k for k, v in d.items()}
来源：http://dali.haohaochexian.top/Article/details/gtuoeferkw.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gttemimwph.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gtqnytpudn.html

[U09] Py：字典取最大值的键
来源：http://dali.gaohongyu789.top/Article/details/gtfmqyprkx.html

max(d, key=d.get)
来源：http://dali.jlsjyb.cn/Article/details/gtrlpuluxo.html

[U10] Py：按值排序字典
来源：http://dali.pycfn.com/Article/details/gtvtazafgq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtkmkzjsxf.html

[U11] Py：生成器表达式
来源：http://dali.haohaochexian.top/Article/details/gtgggsaelz.html

(x * 2 for x in arr)
来源：http://dali.cheryme.top/Article/details/gtflvecaqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gtvsiewhbl.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gtnsrfdgoc.html

[U13] Py：固定长度队列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsfvgvqoj.html

deque(maxlen=10)
来源：http://dali.yonumen.top/Article/details/gtlurmlntr.html

[U14] Py：分组收集到列表
来源：http://dali.ppjwa.cn/Article/details/gtsfpxwyon.html

defaultdict(list)
来源：http://dali.kuanghao11.cn/Article/details/gtubvuuqmr.html

[U15] Py：高精度计时
来源：http://dali.iojbl.cn/Article/details/gtmrmnidvb.html

t = time.perf_counter()
来源：http://dali.sysykeji.top/Article/details/gtphvpxgxs.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtewckhgxi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtscqoexdw.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gtoxdjjxxi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.svipenyu.cn/Article/details/gttfbhrvbs.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtuxglrbyo.html

pat = re.compile(r"\d+")
来源：http://dali.jlsjyb.cn/Article/details/gttkgpohgf.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtyabakcwq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgszurfiv.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gtgvqytdxe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gtcbtjhyxl.html

[U21] Py：自定义上下文管理器
来源：http://dali.zycfv.cn/Article/details/gtdzrvajoo.html

@contextlib.contextmanager
来源：http://dali.hammf.cn/Article/details/gtonoldjgt.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gtnjbvjmyg.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gtrfczqhbp.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtgswocxnv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gogol.net.cn/Article/details/gttzztwwto.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtbkdlnqwz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtxszfcbrd.html

[U25] Py：CSV 按字典读
来源：http://dali.zhengqikj.top/Article/details/gtgpgoptwb.html

csv.DictReader(f)
来源：http://dali.yj20258.top/Article/details/gtcjvwqvnm.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtpjpikoba.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtbwqobvpg.html

[U27] Py：异步 HTTP
来源：http://dali.havefunace.top/Article/details/gtlbbmkirx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtfkmfhlia.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gtvzdiuyrv.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gtjfvibmwf.html

[U29] Py：属性校验
来源：http://dali.cashguo.top/Article/details/gtbcdspfwt.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtgndcdmsl.html

[U30] Py：数据类
来源：http://dali.cdnleiting.top/Article/details/gtqzzbnuhq.html

@dataclass(slots=True)
来源：http://dali.gotoacloud.top/Article/details/gtnjjxxskp.html

[U31] Py：单测
来源：http://dali.vqdsnc.cn/Article/details/gtlcohdbjp.html

python -m pytest -q
来源：http://dali.jinqigufen.top/Article/details/gtthzskauj.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gtzgrdsulh.html

ruff format . && ruff check --fix .
来源：http://dali.jyoumei.cn/Article/details/gtodamwkpj.html

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gtkjsizbsy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtssvjqaun.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtjjpdmvym.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gtgdtnbmzh.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtrhetksyc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gtfiehmkda.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gthkeodpib.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gtldsihbnz.html

[U37] Py：读写 Excel
来源：http://dali.hnxiangtu.top/Article/details/gtmwkbmhtj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gtxjwlwzfe.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gtaljhzzpf.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtfklapwys.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvaunqko.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gtgadiebvv.html

[U40] Py：打印到标准错误
来源：http://dali.hfpthk.cn/Article/details/gtpvjowrgx.html

print("err", file=sys.stderr)
来源：http://dali.zycfv.cn/Article/details/gtmnphalrt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.daxiang520.top/Article/details/gtqakbasmg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gtgxoiuqsv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtpzoyfksi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenjidiqi.icu/Article/details/gtsmcokogv.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtsnxqtvyf.html

namespace App\Http;
来源：http://dali.vqdsnc.cn/Article/details/gtkcyrkdop.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gtccigxdxd.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipensnwm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.daxiang520.top/Article/details/gtiuruvudu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtwvxskawk.html

[U46] PHP：可空类型
来源：http://dali.kuanghao11.cn/Article/details/gtnuarelib.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gtnpzstweb.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gtstrpmgtb.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gtbgtjhhkp.html

[U48] PHP：纯枚举
来源：http://dali.meibo888.top/Article/details/gtcqujqomp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtkuqngdiy.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gtasduumox.html

public readonly string $name
来源：http://dali.meibo888.top/Article/details/gtupxerzho.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtskwkltpx.html

public function __construct(private int $id) {}
来源：http://dali.aizwys.cn/Article/details/gtjvrwfqka.html

[U51] PHP：数组解构
来源：http://dali.yangfankeji.com/Article/details/gtfgnuzklo.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gttobxrlzb.html

[U52] PHP：箭头函数
来源：http://dali.yj202588.top/Article/details/gtrhbtjztx.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtdvhymxea.html

[U53] PHP：空合并运算符
来源：http://dali.mhx1999.top/Article/details/gtbzkdotqj.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gtnusmvhev.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gtukgljwzq.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtsfzgsyts.html

[U55] PHP：match 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtbbuphrda.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gttnnplfps.html

[U56] PHP：命名参数
来源：http://dali.0kj1m.cn/Article/details/gtfjicrqwm.html

f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gtkwaznsgd.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtzzcnwqgl.html

"值: {$a}"
来源：http://dali.ppjwa.cn/Article/details/gtgblfxcow.html

[U58] PHP：数组三件套
来源：http://dali.cheryme.top/Article/details/gttggbzeny.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtefttankw.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtymnzgbmf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgfzy.top/Article/details/gtmzefvhrv.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrxlvajsy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gtrlwrznbl.html

[U61] PHP：正则
来源：http://dali.yonumen.top/Article/details/gtwferhpvk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtpwxshszo.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gtfknjsdpz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gthnebftta.html

[U63] PHP：文件读写
来源：http://dali.xuanzx.com/Article/details/gtahwodgct.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gtqjeeykzg.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gtjbvysdhx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtxqyuetdn.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtlmdfqbeu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gtkqkyjefi.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gtbontkuvi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gtuqjqizjb.html

[U67] PHP：处理文件上传
来源：http://dali.xylfe.cn/Article/details/gtnzmkzpux.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtzeateluk.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtqtyixssp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gtwlcqodhk.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gtxqjoxvgp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gtjkkcrmct.html

[U70] PHP：PDO 事务
来源：http://dali.chenzaomai.com/Article/details/gtqmltbjla.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtuavprnnl.html

[U71] PHP：抛出异常
来源：http://dali.aibaodan.cn/Article/details/gtifcukjby.html

throw new RuntimeException("失败", 500);
来源：http://dali.xinyue.icu/Article/details/gtjdcwmjmx.html

[U72] PHP：写错误日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuderdvmg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtkoxernpv.html

[U73] PHP：读取 ini 配置
来源：http://dali.sweek.top/Article/details/gtcusapigj.html

parse_ini_file("config.ini", true)
来源：http://dali.feifeiyinyue.top/Article/details/gtwncqrowq.html

[U74] PHP：读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gtmhwendxk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfeehmds.html


<!-- 参考信息 -->