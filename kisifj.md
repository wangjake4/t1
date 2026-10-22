代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtkvwbiney.html

[S49] C++：写文件
来源：http://dali.hammf.cn/Article/details/gtzuoyenju.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtrlhxyodw.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gtrmotapbb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtsucfhxwi.html

[S51] C++：显式类型转换
来源：http://dali.jqgufenzy.top/Article/details/gttubozqfh.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtwqvmmtlm.html

[S52] C++：const 与 noexcept
来源：http://dali.yongpay.top/Article/details/gtnravwulk.html

int size() const noexcept { return n_; }
来源：http://dali.xylfe.cn/Article/details/gtunomiyzh.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gthxpqjkvs.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtlcnvutzi.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtutikxsmj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gttdzaycku.html

[S55] C++：结构化绑定
来源：http://dali.ehwqpu.com/Article/details/gtafwoacgn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtghccjzam.html

[S56] C++：optional
来源：http://dali.daria6918.cn/Article/details/gtttktuenu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtbmbmrmeo.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtikkhtxxb.html

constexpr int N = 10;
来源：http://dali.zycfv.cn/Article/details/gtvyajlysr.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtdwaxjuvs.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtltbbtvmh.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtubtnalic.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtyozzkxoh.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtrhxqmvvr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ppjwa.cn/Article/details/gtxgktopml.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gthanvcvfl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gttziusdbq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiqttlsjb.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtukbklexc.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtgokjprvi.html

[T02] Kotlin：变量
来源：http://dali.xinyue.icu/Article/details/gtzerzmbxi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tianlin.xyz/Article/details/gtrqphbdxd.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gtwxosghxc.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtjbtxghky.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtsdlncuin.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtisnyywpr.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtucffzjqv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hammf.cn/Article/details/gtmutuogcc.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtjcemdoha.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtfirgubui.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtnsbwfcwj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gtyiitydwa.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gtwczwavzy.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtjimdfvsk.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gtrlaaeurj.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gtfrzcammm.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtssslcder.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtmpitirot.html

[T11] Kotlin：协程
来源：http://dali.yuanzhike.top/Article/details/gtwccflwde.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtulpcczbx.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtyxmfbhxa.html

val (a, b) = Pair(1, 2)
来源：http://dali.sxryk.cn/Article/details/gtnoaghoek.html

[T13] Kotlin：只读 Map
来源：http://dali.nwbrower.top/Article/details/gtgxvjfwnp.html

val m = mapOf("a" to 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtipybntuc.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gthiugcwdz.html

for (i in 1..10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtozsclycr.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtpcqnrltw.html

interface Shape { fun area(): Double }
来源：http://dali.c1oappe.top/Article/details/gtbgbppqvj.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtqpytqvro.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtzjkfbvxc.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtxhkgxpqb.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtkkpzweqw.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtootwchas.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gtefelxbkd.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtkxermjuw.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtihmeykgb.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtyxbwnred.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtqxvzvzwa.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtudxzittj.html

for x in a { print(x) }
来源：http://dali.hywenlv.cn/Article/details/gtnmoxtfsi.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtafepltap.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtvquyxsgj.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtzjfvjlvr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.smart0.xyz/Article/details/gtdtvgiqea.html

[T24] Swift：闭包
来源：http://dali.jqgufenzy.top/Article/details/gtfkcwyxxn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtupkauqyz.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtmmvomknl.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gthtkvuaym.html

[T26] Swift：类与重写
来源：http://dali.chenlongwang.top/Article/details/gtrrqydrzl.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtoerlwfvq.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gtesrizxpu.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtbfhntbwt.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtwqurxyuw.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtagfehjle.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtntormygk.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtuhttafty.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtsvqrhjmw.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gthkaxkuvw.html

[T31] Lua：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtjnqrptsu.html

print("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtrznrmoxl.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtdbrieale.html

local a = 1
来源：http://dali.bjfxy.top/Article/details/gtqsrsgtxx.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gtyvfwrgis.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtsuqdqfnd.html

[T34] Lua：遍历表
来源：http://dali.gzhubu.top/Article/details/gtcmdfvmbz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtedwopxau.html

[T35] Lua：字典表
来源：http://dali.yueranfly.top/Article/details/gtvkdedjle.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtyuzaghvw.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtacwngelh.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtvcptgqjv.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gtnripebkd.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtecvajtkp.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gteuytbahm.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gtootxvnxp.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtpuzecdgz.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtjeqcxnwt.html

[T40] Lua：元表
来源：http://dali.havefunace.top/Article/details/gtbgxsnovu.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gttcvuippo.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtrqhwetcn.html

print "Hello\n";
来源：http://dali.andypj.xyz/Article/details/gtsmzfspjc.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gteyjvmfmd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yonumen.top/Article/details/gtisdcletf.html

[T43] Perl：字符串插值
来源：http://dali.yj202588.top/Article/details/gtimzdfdki.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gtwpoflcbn.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gttvkxcjdj.html

if ($a > 0) { print "正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtudunzhwx.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtsagafsdl.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gtpmvoeifi.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtmkzctxcm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqkgqxypv.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gthqecvren.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sysykeji.top/Article/details/gtaadibsax.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtzbullrbw.html

$s =~ s/old/new/g;
来源：http://dali.havefunace.top/Article/details/gtownhdziy.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gtukffztpt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtshfuvudl.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gteggrocgr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtwhjgzwhx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtyomjzkuq.html

[T51] Scala：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkamhrmxk.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtkcscjhms.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtkxviyymp.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtfxfroeyp.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtjupwmtnb.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gteaeejstp.html

[T54] Scala：集合映射
来源：http://dali.yj20258888.top/Article/details/gtkzkvxltp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzumidmx.html

[T55] Scala：集合过滤
来源：http://dali.cheryme.top/Article/details/gtbnjsmaco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gtdlcbsamb.html

[T56] Scala：样例类
来源：http://dali.feifeiyinyue.top/Article/details/gtbxfvtkto.html

case class User(name: String, age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtsgkcnhjy.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtvyfvgxsl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnxiangtu.top/Article/details/gtvflayrbm.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gthvdglxwc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.smart0.xyz/Article/details/gtfsptpjed.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gtnyndeirf.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gthzamybjh.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycziolec.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtbkhashxj.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtuwrhpglm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yangfankeji.com/Article/details/gthkwhnchw.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkplvoief.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkkawrwx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gthjxkkuyj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtsqpityuo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gtoralchdw.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gticfyrqjq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cqqwz.cn/Article/details/gtvbllgzmx.html

[U04] Py：变量调试打印
来源：http://dali.zycfv.cn/Article/details/gtqlogkhbd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtircknnym.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtygnjrala.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtillhzuld.html

[U06] Py：合并两个字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqweebeem.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtbbgolcwt.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gturhbrzfn.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtmmfsrifu.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtyjjmfxau.html

[y for x in nested for y in x]
来源：http://dali.sxryk.cn/Article/details/gtkyjlerok.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhxmpsnd.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gtxepsqsku.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtyphorxzz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtcxyctyjc.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtxxqqexur.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gtwtgkrjsm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuetiantiany.cn/Article/details/gtzzzjtloa.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtznxgeemx.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtrkmbxumm.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtussflqcf.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gtpyxwivon.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtgusvcfzp.html

[U15] Py：高精度计时
来源：http://dali.daxiang520.top/Article/details/gtlujldrow.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gttltgadwe.html

[U16] Py：命令行参数解析
来源：http://dali.zhoulong.xyz/Article/details/gtpklqbgbr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dianchejie.cn/Article/details/gttfzoqjhi.html

[U17] Py：初始化日志
来源：http://dali.birdmap.top/Article/details/gtomgmxnwb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhixingplan.top/Article/details/gtpccozaap.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gteucmztsg.html

pat = re.compile(r"\d+")
来源：http://dali.guannengcc.top/Article/details/gtvufjewxy.html

[U19] Py：正则替换带回调
来源：http://dali.jinqigfzy.top/Article/details/gtxvckjeyn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtamqgoczh.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gthxgemcsl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ppjwa.cn/Article/details/gtuflspuuy.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrssbpsvf.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtkmpsgomm.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtgupsdxmc.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtjrhhgdjm.html

[U23] Py：分块读取大文件
来源：http://dali.svipenyu.cn/Article/details/gteqqaezaa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtddeiuvwm.html

[U24] Py：路径操作
来源：http://dali.yonumen.top/Article/details/gtkrimuzbl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daxiang520.top/Article/details/gtemgdaxcp.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtssicwdeb.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gtpkonomwd.html

[U26] Py：并发下载
来源：http://dali.pengpengdd.cyou/Article/details/gtecufujik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gttpfdbyji.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtcrdpsqil.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtluidnttf.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gtpxgnbevn.html

UserId = int
来源：http://dali.guannengcc.top/Article/details/gtcaxlnihd.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gtgmnhtqft.html

@property 与 @x.setter 配合
来源：http://dali.zhoulong.xyz/Article/details/gtazvzltlh.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnepbxupx.html

@dataclass(slots=True)
来源：http://dali.zdqjudy.top/Article/details/gtiojecqob.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtmazvmwau.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtwywewocg.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gterqtcshb.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtuzkjshni.html

[U33] Py：打包发布
来源：http://dali.zhengqikj.top/Article/details/gtqklqcbyp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gtyszyejzy.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtidggsips.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtvsqfvsch.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gtotxddoll.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtswppktme.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtldicgjob.html

schedule.every(10).minutes.do(job)
来源：http://dali.meibo888.top/Article/details/gtgyrivpgk.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtjvtzkarf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangshuangyany.cn/Article/details/gtghetlgzp.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj202588.top/Article/details/gtengldvpu.html

Path(__file__).resolve().parent
来源：http://dali.aizwys.cn/Article/details/gtgalbfvdu.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gtgscmiwoa.html

sys.stdout.isatty()
来源：http://dali.shangyingyoupin.top/Article/details/gtostmnaaa.html

[U40] Py：打印到标准错误
来源：http://dali.chenzaomai.com/Article/details/gtqmqcxhpl.html

print("err", file=sys.stderr)
来源：http://dali.jiagoushi.top/Article/details/gttthlcooc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gtcdubvzfu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gthnplysrs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jqgufenzy.top/Article/details/gtehalzkcn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtsnehfmzx.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtszxffphy.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gtrqvtksxl.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtbrznjyni.html

declare(strict_types=1);
来源：http://dali.dianchejie.cn/Article/details/gtqarjonkd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xuanzx.com/Article/details/gththjiffc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwndampug.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtzlayrrkz.html

?string $name = null
来源：http://dali.cucudq.cn/Article/details/gthdwwhmdu.html

[U47] PHP：联合类型
来源：http://dali.shzxlz.cn/Article/details/gtudwvtwrl.html

int|string $id
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlbjqwty.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtkqxqnlcm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtinrjtaij.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gtndxooipe.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtggiszyfx.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gtwygwmfgy.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtruzzhsmo.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtkkjhbvja.html

[$a, $b] = $arr;
来源：http://dali.zhengqikj.top/Article/details/gtjrxrqkcq.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtypsvrhlo.html

$double = fn($x) => $x * 2;
来源：http://dali.shuidangran.top/Article/details/gthlidiyxy.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtxlobqmdi.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gtssszqpdf.html

[U54] PHP：空安全调用
来源：http://dali.jianghu66.top/Article/details/gthdvevzct.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gtharcqxcr.html

[U55] PHP：match 表达式
来源：http://dali.sysykeji.top/Article/details/gtfzjmltjz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtespcokrd.html

[U56] PHP：命名参数
来源：http://dali.zhiwuduotai.top/Article/details/gtgppkqxow.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtaaigepnz.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtqtdskcvy.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtommgfyzt.html

[U58] PHP：数组三件套
来源：http://dali.hammf.cn/Article/details/gtqqjqrvlt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhiwuduotai.top/Article/details/gtccluztju.html

[U59] PHP：自定义排序
来源：http://dali.xuetiantiany.cn/Article/details/gtlbivyesn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqzbsnjqs.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gtkvhaukxg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gthzljbmcj.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gtozdtqqym.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gthcubjpyt.html

[U62] PHP：日期对象
来源：http://dali.yangfankeji.com/Article/details/gtdftoddjh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxinkj.top/Article/details/gtqahderup.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtfzztpyma.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.pycfn.com/Article/details/gtnqgyyaqx.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gttvfsnjvi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hywenlv.cn/Article/details/gtddwjvbql.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gtmphgbvnp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gttjwlrqrk.html

[U66] PHP：设置 Cookie
来源：http://dali.yuanzhike.top/Article/details/gtecwynfxe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nwbrower.top/Article/details/gtaniragtk.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gthfehxezx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gtvzfxrdsf.html

[U68] PHP：PDO 连接
来源：http://dali.xinyue.icu/Article/details/gtkujztmxo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hywenlv.cn/Article/details/gtdtrwukla.html

[U69] PHP：PDO 预处理
来源：http://dali.dianchejie.cn/Article/details/gtvjjxvwse.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtrdrcdihw.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gtdmwqfrqt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtnxegksau.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtqtwzbjtr.html

throw new RuntimeException("失败", 500);
来源：http://dali.tianlin.xyz/Article/details/gtaogpjjvj.html

[U72] PHP：写错误日志
来源：http://dali.jianghu66.top/Article/details/gtyzhprbnv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jianghu66.top/Article/details/gteeuernkm.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhijiandao.cn/Article/details/gtwtmxnsxu.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtiumyvgvw.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtdyrymnlg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.smart0.xyz/Article/details/gtgwinyeol.html


<!-- 参考信息 -->