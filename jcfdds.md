代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgfzy.top/Article/details/gtblniiqxr.html

[S57] C++：编译期常量
来源：http://dali.chenzaomai.com/Article/details/gtlnqhrymn.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtynniramc.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtinikepcb.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtxhsyuena.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtkumbwwlw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj202588.top/Article/details/gtornezezd.html

[S60] C++：遍历并删除元素
来源：http://dali.gotoacloud.top/Article/details/gthgxkutdj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtkeipgxrv.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtokwxecdk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtmuvtoygi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gthtsjjiim.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gtclgorrxd.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtsaleltpk.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gtasvycpnd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258888.top/Article/details/gtetdersuh.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtxwukamug.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gthyicjqwb.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtginhhxyv.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoyjrtcqt.html

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtfxacxbdm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtwwoycrpe.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtaflngsow.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtasfgbekq.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtjfxdkxna.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ivvv.top/Article/details/gttvltvoyu.html

[T08] Kotlin：数据类
来源：http://dali.guannengcc.top/Article/details/gtzperopjg.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtcjujcbtr.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtojrrgggr.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gtjpgfvmwh.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtmfgtdbwn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtmtdvxsvx.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtnprroimu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gzhubu.top/Article/details/gtwjacetln.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtinpdsflp.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtzhdaaons.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtwfxqspuy.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtmenfijau.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtwmujpvsv.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtmegkfroz.html

[T15] Kotlin：接口
来源：http://dali.ydzc1.top/Article/details/gtqultgyrg.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gtwpwxeldu.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtufirqghh.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtkeavoozg.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtlhmfvupn.html

var a = 1;  let b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gtmdolprwn.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtjojekvvy.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gtwknvluag.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtxkcvudsi.html

if let n = opt { print(n) }
来源：http://dali.zhiwuduotai.top/Article/details/gtdjslrqrq.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcuqxsruj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guowangkeji.top/Article/details/gtzehplyxu.html

[T21] Swift：遍历
来源：http://dali.smart0.xyz/Article/details/gtvrclceyu.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtxdsjvkxl.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gtllqhcptn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcpujufts.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gtfjbumrtr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtauhmpkoo.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtklvwekeb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtxcmypxkk.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gtrkjijhki.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gtzelkkynx.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtrklbuswz.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtpqzwmwxn.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gtfvmymvet.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtoolbvcgk.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtpnqarzcx.html

enum Color { case red, green }
来源：http://dali.shuidangran.top/Article/details/gtzxaqnzxm.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtvdavdfdx.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gtqmnpxuwu.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtnrftxgov.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqowiejow.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtnjsnkxdo.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtmqgqigtf.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gtotbwrnfz.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtyzbdikqu.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtbqpsvkpz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aibaodan.cn/Article/details/gtfdnnrtvy.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gtmgpmeqnv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtfjureqpr.html

[T35] Lua：字典表
来源：http://dali.yongpay.top/Article/details/gtdduiucgc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtkghohdes.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gttwirbkcv.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtifpremmw.html

[T37] Lua：字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtzxuysvdq.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtnvgahlsz.html

[T38] Lua：条件
来源：http://dali.guannengcc.top/Article/details/gtrmrhhirw.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtuzpohtkq.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtrwhkocan.html

string.find(s, "%d+")
来源：http://dali.hongshengwenyu.top/Article/details/gtmfklcmeh.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygcwwmgc.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtoohfhrts.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtceuxciad.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtxgbtnjpf.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtynqsjjsq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cheryme.top/Article/details/gtenitibmv.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtocherpyh.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtowwwlebe.html

[T44] Perl：条件
来源：http://dali.meibo888.top/Article/details/gthbriydgt.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtnmisfuvx.html

[T45] Perl：数组遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtgytgvjou.html

for my $x (@arr) { print $x; }
来源：http://dali.tanke756.top/Article/details/gtnyrkbyid.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewhhthpp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gtyhfovcpf.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gtqhuooxzu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsiakkza.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtlnneuzrl.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtrlcoormt.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtwexjrirs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtztlrskoa.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gteytvwcun.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtursatbue.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtixiacbwn.html

[T51] Scala：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtrugkaejc.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtduyrxadc.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtcwsrjshu.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtiephodqz.html

[T53] Scala：字符串插值
来源：http://dali.yueranfly.top/Article/details/gttbpcdhyo.html

s"值: $b"
来源：http://dali.yuxming.cn/Article/details/gttncshnjv.html

[T54] Scala：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgmzgrxcz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtcmyjfrmm.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtnurbagah.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbiggortx.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtjjbeikep.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gtnrzadrum.html

[T57] Scala：模式匹配
来源：http://dali.pycfn.com/Article/details/gtzgglktso.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tian-w.cn/Article/details/gtlcxjvdcf.html

[T58] Scala：函数定义
来源：http://dali.gogol.net.cn/Article/details/gtjwvifevs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gtrtroonno.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gthjmzsnnh.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsxfpvsn.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtdhiypspj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtyccdzuvc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtpdmwmmbl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtqzidqiim.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtdaxutglz.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtpqokfoov.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gtahiotlym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gtlhpyouoq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtoytcwbzi.html

[U03] Py：加载 .env 配置
来源：http://dali.hnxiangtu.top/Article/details/gtrssgdluv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xinyue.icu/Article/details/gtliyhztqv.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtcelkicnx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.redwolf501.top/Article/details/gthskwnxus.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtudnlmxfh.html

list(dict.fromkeys(arr))
来源：http://dali.ybcxt.top/Article/details/gtuyyphfbk.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtlqwdxmwy.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gtwadfozea.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gtotzapluo.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtadkbmvzb.html

[U08] Py：展平二维列表
来源：http://dali.nanxinkj.top/Article/details/gtbzjpczck.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqxnioak.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtkqfephsa.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtuusiqmvo.html

[U10] Py：按值排序字典
来源：http://dali.jqgufenzy.top/Article/details/gtduvzudyc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtuypholhu.html

[U11] Py：生成器表达式
来源：http://dali.yangfankeji.com/Article/details/gtsbnweydn.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtvgggldbf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtwpicgfod.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtgguonzri.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtwqkrulhp.html

deque(maxlen=10)
来源：http://dali.cdnleiting.top/Article/details/gtbmlynsij.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gtkmnsknqh.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtitodfbxm.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gthskrkdtf.html

t = time.perf_counter()
来源：http://dali.pycfn.com/Article/details/gtdwhhojdw.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtgarzpmte.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtdyityedw.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gtbgsbvkif.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangdashe.top/Article/details/gtoskhxmhf.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtbpvhybqg.html

pat = re.compile(r"\d+")
来源：http://dali.gaohongyu789.top/Article/details/gtirohwkhm.html

[U19] Py：正则替换带回调
来源：http://dali.guowangkeji.top/Article/details/gtpbegurws.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.c1oappe.top/Article/details/gtcuxaazfe.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gtllorukti.html

@functools.lru_cache(maxsize=None)
来源：http://dali.fengsongda.top/Article/details/gtrilrofij.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gtpdpmjoja.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtkwihndhp.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtxjnidjfc.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtiixqfnqu.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gtllbcaicd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtpycypfxg.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gtjdzlkcvs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtchajbdzi.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gtmjftjrhx.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gttvchiewt.html

[U26] Py：并发下载
来源：http://dali.jinqigfzy.top/Article/details/gtcognlzdz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yonumen.top/Article/details/gthagwhljz.html

[U27] Py：异步 HTTP
来源：http://dali.feifeiyinyue.top/Article/details/gtypxhxkey.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtwkzgwyti.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gtnrvvmlas.html

UserId = int
来源：http://dali.gogol.net.cn/Article/details/gtamjlqfxj.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtqiucawnx.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gtbtripbnl.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtsnekwkzf.html

@dataclass(slots=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtficwdagt.html

[U31] Py：单测
来源：http://dali.tian-w.cn/Article/details/gtnugjtcil.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmyhnrpjf.html

[U32] Py：代码格式化
来源：http://dali.havefunace.top/Article/details/gthbaxrrao.html

ruff format . && ruff check --fix .
来源：http://dali.shuidangran.top/Article/details/gtnjbaashm.html

[U33] Py：打包发布
来源：http://dali.yueranfly.top/Article/details/gtbidqihbm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtbesgyesd.html

[U34] Py：判断编码
来源：http://dali.aibaodan.cn/Article/details/gtwozgkvzw.html

chardet.detect(raw)
来源：http://dali.zhoulong.xyz/Article/details/gtlzctrgit.html

[U35] Py：发送邮件
来源：http://dali.haohaochexian.top/Article/details/gtpdskcrmg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gtlqjekfka.html

[U36] Py：定时任务
来源：http://dali.sxryk.cn/Article/details/gtrjogmhoy.html

schedule.every(10).minutes.do(job)
来源：http://dali.cashguo.top/Article/details/gtxnkesosj.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gtnvswbkse.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtopwemeyz.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gtrtilhzjp.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtkstfgpbo.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtdsciyyji.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtfwpcysyz.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gtuionoueq.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdzutkocb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigufen.top/Article/details/gtyualbrkq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gthghbmxjn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtaizdbcns.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sxryk.cn/Article/details/gtsbwdfeho.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gthfippsef.html

namespace App\Http;
来源：http://dali.sweek.top/Article/details/gteqfydzqh.html

[U44] PHP：开启严格类型
来源：http://dali.sweek.top/Article/details/gtqcvjvgda.html

declare(strict_types=1);
来源：http://dali.svipenyu.cn/Article/details/gtlbyddybw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gtxhooeung.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gtbnfcsepi.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtfyqyyjsh.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gtscafqsvv.html

[U47] PHP：联合类型
来源：http://dali.cdnleiting.top/Article/details/gtjhjtpjmu.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtpjmsitjx.html

[U48] PHP：纯枚举
来源：http://dali.gogol.net.cn/Article/details/gtjhkmwffg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlcjsfrzh.html

[U49] PHP：只读属性
来源：http://dali.hongshengwenyu.top/Article/details/gtgxohwoae.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtxrrzpvta.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gthvhqrxwb.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtghfrndbv.html

[U51] PHP：数组解构
来源：http://dali.guannengcc.top/Article/details/gtjmbtucgh.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtttijlkop.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtvyaiqiww.html

$double = fn($x) => $x * 2;
来源：http://dali.jinqigfzy.top/Article/details/gtkrntefpt.html

[U53] PHP：空合并运算符
来源：http://dali.yueranfly.top/Article/details/gtpuqanxjv.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtbllfkauo.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gtyxznaezy.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtvizhqvja.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gtrklgchds.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtzvpogktd.html

[U56] PHP：命名参数
来源：http://dali.gogol.net.cn/Article/details/gtqgmfmrur.html

f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtlwpvtygl.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gtfxgddrsj.html

"值: {$a}"
来源：http://dali.meibo888.top/Article/details/gtrywuqmbv.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gtcefngepl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gtumyjzihq.html

[U59] PHP：自定义排序
来源：http://dali.ivvv.top/Article/details/gtiuxmcnwi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvklwecm.html

[U60] PHP：JSON 编解码
来源：http://dali.ydzc1.top/Article/details/gtbcoscpes.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yongpay.top/Article/details/gtssysqrcj.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoucdnepg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtujbyrkwi.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gtteayvvgj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gtormvrazz.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtxfbslxuw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gttkeaqelj.html

[U64] PHP：目录遍历
来源：http://dali.aizwys.cn/Article/details/gtlvhgjsyy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gtonjdxikl.html

[U65] PHP：会话
来源：http://dali.c1oappe.top/Article/details/gtngjtvktn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtxlxbiymj.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gtlsjfongt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdgdzxgoa.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtrsxqcmhb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.chenjidiqi.icu/Article/details/gtcaxkzftz.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtfjokcwgt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gtcsbrmgue.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtyedwnwmc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258888.top/Article/details/gtwweljqyo.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtphbhptod.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xylfe.cn/Article/details/gtaynzeyof.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gtjzwlxdop.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gtlgylvfcr.html

[U72] PHP：写错误日志
来源：http://dali.xinyue.icu/Article/details/gtkuakuaaz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtekplpkga.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gtlsfwobml.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gtzsshcleb.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtgtjmqyij.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gtpuomevim.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtkzqnmmwy.html

composer require psr/container
来源：http://dali.gotoacloud.top/Article/details/gtogiweslg.html

[U76] PHP：简单路由
来源：http://dali.birdmap.top/Article/details/gtnvflwkwc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gtxkyqmtde.html

[U77] PHP：模板渲染
来源：http://dali.zhengqikj.top/Article/details/gtujrowtne.html

composer require twig/twig
来源：http://dali.cashguo.top/Article/details/gtprusavfg.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtqujveora.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtrswjoxpu.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gtpoyinamm.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258.top/Article/details/gtkbloager.html

[U80] PHP：代码规范修复
来源：http://dali.hfpthk.cn/Article/details/gtznpveybi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.aizwys.cn/Article/details/gtvczixpzb.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiispykoo.html

npm init -y;  npm i express
来源：http://dali.ybcxt.top/Article/details/gtwgqhtjsk.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtarzvjvwa.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gtsyfxtaix.html


<!-- 参考信息 -->