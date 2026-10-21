代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtwarywqak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gthfbyrlci.html

[T06] Kotlin：集合映射
来源：http://dali.ppjwa.cn/Article/details/gtyhruoonu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtdgsgpfhi.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtcrnlkevl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtdirhxlcl.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtglzwivhx.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtwgipsopb.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtxjaecyyn.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gttnyynhbo.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtfzddwbff.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtoofflmbh.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtrytzjzfu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.havefunace.top/Article/details/gtdvhevczl.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtscaxrydc.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gtrqdbarml.html

[T13] Kotlin：只读 Map
来源：http://dali.hongshengwenyu.top/Article/details/gtwlyzkhza.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtxhrrzeut.html

[T14] Kotlin：循环
来源：http://dali.cashguo.top/Article/details/gtmxofwxek.html

for (i in 1..10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtofrhhlyb.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtktriqgmo.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtltijqlxz.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtwcwirxzu.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtmskgpmow.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gtfesfbrzu.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtifpayyoq.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtighusvir.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gtqogqcrxj.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtwldzorsz.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtkhpcfzwp.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtpwommyaw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtninegqkw.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtfckhhccy.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtjwiuljlj.html

[T22] Swift：字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdogywfi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtbpfwgvfa.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtqzdhdbgc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtcsrijxvs.html

[T24] Swift：闭包
来源：http://dali.gaohongyu789.top/Article/details/gtthpirmcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtozrcqwop.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gthawryuus.html

struct P { var x: Int }
来源：http://dali.kuanghao11.cn/Article/details/gtyhszcbtq.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtfncckpoc.html

class A: Base { override func f() {} }
来源：http://dali.hysaishi.cn/Article/details/gtleyvpugm.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgzjpgbg.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtxsvndfqq.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtwyfbhilm.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtsvcdhygo.html

[T29] Swift：guard 提前返回
来源：http://dali.andypj.xyz/Article/details/gtilhldtow.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtoxzepkej.html

[T30] Swift：协议
来源：http://dali.feifeiyinyue.top/Article/details/gtdtqzkexd.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gtlthuhmlb.html

[T31] Lua：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtedwtxegn.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtkxtqbpwo.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtsdeyyccv.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gtudjkyrps.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtqcfhqkyl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhixingplan.top/Article/details/gtaivyzqbc.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtgraalkrs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhongyouzk.top/Article/details/gtczjtfzma.html

[T35] Lua：字典表
来源：http://dali.hywenlv.cn/Article/details/gtwdazrssa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqhtodlt.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtvijdhdgo.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdpzymvgv.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtpcoqziwu.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtqlipwrxj.html

[T38] Lua：条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtretyfxid.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtsdppghvs.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenivniku.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtijfnuhal.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtawticjft.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gthwfyebzv.html

[T41] Perl：Hello World
来源：http://dali.cheryme.top/Article/details/gttrecvoau.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtmhfyoxzu.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtdwzsnroc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.daria6918.cn/Article/details/gtyrltnaoc.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtwrfebaoj.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtadtuxawm.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtofdzrgml.html

if ($a > 0) { print "正"; }
来源：http://dali.yueranfly.top/Article/details/gtkjyukkde.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtisvywvar.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtljfcmqpo.html

[T46] Perl：哈希操作
来源：http://dali.tanke756.top/Article/details/gthxmiculs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmdzpmtjr.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gtupuezeez.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ivvv.top/Article/details/gtqkaxihfw.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtbpkiqwfh.html

$s =~ s/old/new/g;
来源：http://dali.haohaochexian.top/Article/details/gtnbprawhh.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtgqzfukgc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtlwylxvdp.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtvnrcntwq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtqqlejive.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpdzgafja.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtlygvyxst.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gtbbamiztj.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtiuvizqiw.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtyofgtqvc.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpthbadme.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcczllhu.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtdgkjfblm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtrijdxcsa.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtrkfnlhal.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtcuhlbxdq.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gtogyrivvi.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtdjbnyaia.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gteemnumvj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yvedp.cn/Article/details/gtloczgour.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtqgodlwbc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuxming.cn/Article/details/gtzwzkfyhx.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gtrvdpmixi.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtmrgzllbw.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtmrawcdqu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtyytxrqbo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtndtxftfl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigufen.top/Article/details/gtbzymkslu.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteimhhawq.html

[U01] Py：创建虚拟环境
来源：http://dali.sysykeji.top/Article/details/gtltcdrdlj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxinkj.top/Article/details/gtlldwsjim.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigufen.top/Article/details/gtvdptzpyd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gtbohrqgfl.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gtftrpwzxv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.0kj1m.cn/Article/details/gtgmhlmwuw.html

[U04] Py：变量调试打印
来源：http://dali.yangfankeji.com/Article/details/gtzprpjnyl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gttnnbxkvx.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gtlebjpacf.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtmmronhjo.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvrezket.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtobdzxzaf.html

[U07] Py：反转字典键值
来源：http://dali.nanxinkj.top/Article/details/gtpptrnfxl.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gtgyfohvdx.html

[U08] Py：展平二维列表
来源：http://dali.wangdashe.top/Article/details/gtmkrahqgv.html

[y for x in nested for y in x]
来源：http://dali.birdmap.top/Article/details/gtwvpjadye.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtohgnmqal.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtfrmnepwg.html

[U10] Py：按值排序字典
来源：http://dali.sweek.top/Article/details/gtrxnhgvgc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtzjkfjjva.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtrkykfphg.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtyspargua.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.vqdsnc.cn/Article/details/gteggtollx.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtfsxjqlux.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gtkvnfqvip.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gtghtnhrvv.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtyggkeoja.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtciigjmmv.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumdfxxat.html

t = time.perf_counter()
来源：http://dali.andypj.xyz/Article/details/gtikbcfegg.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gteyqgzmof.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.mhx1999.top/Article/details/gtnleatwgi.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gtoqdxfwzs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gtwalgvksq.html

[U18] Py：预编译正则
来源：http://dali.mhx1999.top/Article/details/gtauzayjps.html

pat = re.compile(r"\d+")
来源：http://dali.c1oappe.top/Article/details/gtigckhurn.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gtrhlrjmqv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gthhxfaufz.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258888.top/Article/details/gtolbrtxnz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.meibo888.top/Article/details/gtcvmjwzlj.html

[U21] Py：自定义上下文管理器
来源：http://dali.c1oappe.top/Article/details/gtoyuxidfs.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtotahdhlj.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gttciadngk.html

list(zip(*m))
来源：http://dali.nanxinkj.top/Article/details/gtcdjcrjro.html

[U23] Py：分块读取大文件
来源：http://dali.yonumen.top/Article/details/gtwpydnkud.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shuidangran.top/Article/details/gtteyhshwy.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gtfgubxlwy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenjidiqi.icu/Article/details/gtzafefrwd.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxttqlbx.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gtghcfniel.html

[U26] Py：并发下载
来源：http://dali.kuanghao11.cn/Article/details/gtioouqxrm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gttpdklgaw.html

[U27] Py：异步 HTTP
来源：http://dali.cheryme.top/Article/details/gtxxvwmeja.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtppmekdxr.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtxwdlokwn.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gtpnuwpmmz.html

[U29] Py：属性校验
来源：http://dali.feifeiyinyue.top/Article/details/gtjfwlxono.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtnaqrkkyx.html

[U30] Py：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmecpiwnu.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gtkmssqfgw.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gtceiufzos.html

python -m pytest -q
来源：http://dali.zhoulong.xyz/Article/details/gtxefoxdmo.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtspsgmvtu.html

ruff format . && ruff check --fix .
来源：http://dali.bjfxy.top/Article/details/gtrbzcrvjp.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gttysepfrq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangshuangyany.cn/Article/details/gtabjsdtdz.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gttfcaxyli.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtqjteskuc.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtnihlnent.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gtwubnplvj.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gtzzdvjuyr.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtlrwmbklx.html

[U37] Py：读写 Excel
来源：http://dali.yj20258888.top/Article/details/gtvxzwtfuu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.c1oappe.top/Article/details/gtbxcrhrbw.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtfujqjrnj.html

Path(__file__).resolve().parent
来源：http://dali.guannengcc.top/Article/details/gtahabsnbk.html

[U39] Py：判断是否在交互环境
来源：http://dali.sxryk.cn/Article/details/gtadqwxpch.html

sys.stdout.isatty()
来源：http://dali.gzhubu.top/Article/details/gtpavwabnh.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtisszttwv.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gtxlwslonr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtoqvjmnfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cashguo.top/Article/details/gtwhfquuxf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.feifeiyinyue.top/Article/details/gthckqzijr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtjkzfbtuc.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gtnbiclynj.html

namespace App\Http;
来源：http://dali.gogol.net.cn/Article/details/gtfelhuycw.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtjqitugiu.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gtqpohpxun.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtttnaeqrt.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gtpyzbtftm.html

[U46] PHP：可空类型
来源：http://dali.ehwqpu.com/Article/details/gtknqnrefg.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gttmivwijg.html

[U47] PHP：联合类型
来源：http://dali.dashuyun.cn/Article/details/gtauvzkvov.html

int|string $id
来源：http://dali.shuidangran.top/Article/details/gthdwwwjsw.html

[U48] PHP：纯枚举
来源：http://dali.ivvv.top/Article/details/gtvqovhqts.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufssbkw.html

[U49] PHP：只读属性
来源：http://dali.yanxiufei.cn/Article/details/gtirugdwkf.html

public readonly string $name
来源：http://dali.sysykeji.top/Article/details/gtyjmfdfty.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtpyqyeazu.html

public function __construct(private int $id) {}
来源：http://dali.guowangkeji.top/Article/details/gtayuuwgog.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtjddvxlyp.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gtekdjitxi.html

[U52] PHP：箭头函数
来源：http://dali.xziqi.cn/Article/details/gtxtymqxrx.html

$double = fn($x) => $x * 2;
来源：http://dali.redwolf501.top/Article/details/gtgsjvqqsj.html

[U53] PHP：空合并运算符
来源：http://dali.jianghu66.top/Article/details/gtjpksinks.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258.top/Article/details/gtnrwruxje.html

[U54] PHP：空安全调用
来源：http://dali.sufxvd.cn/Article/details/gtdpfltzan.html

$obj?->method()
来源：http://dali.aibaodan.cn/Article/details/gtpthnlxwz.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gtuvftjcen.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gtnwfpkafm.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gthfoagafi.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtmwpokfqt.html

[U57] PHP：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtaewdfvmo.html

"值: {$a}"
来源：http://dali.xinyue.icu/Article/details/gtjlismwsw.html

[U58] PHP：数组三件套
来源：http://dali.c1oappe.top/Article/details/gtehpoabcg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xinyue.icu/Article/details/gtpamojgxe.html

[U59] PHP：自定义排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnehyiqn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zdqjudy.top/Article/details/gtqanpkuqv.html

[U60] PHP：JSON 编解码
来源：http://dali.guowangkeji.top/Article/details/gtpkbpyclm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtndbwjorg.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gtdrkwsqrz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxheqeqd.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtdtzlxvwv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhongyouzk.top/Article/details/gtxmhadlzz.html

[U63] PHP：文件读写
来源：http://dali.c1oappe.top/Article/details/gtzuwgedqx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gtzodffyff.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxmazjzks.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tian-w.cn/Article/details/gtwakwsefh.html

[U65] PHP：会话
来源：http://dali.sysykeji.top/Article/details/gttvriqgze.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tian-w.cn/Article/details/gtihsypfze.html

[U66] PHP：设置 Cookie
来源：http://dali.daxiang520.top/Article/details/gtvqfielhe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtyddtxjcn.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gtprlgkrtw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tianlin.xyz/Article/details/gtzmrystra.html

[U68] PHP：PDO 连接
来源：http://dali.pycfn.com/Article/details/gttkslklfw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gtdepatdpi.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtzxhvoohv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gogol.net.cn/Article/details/gtiozvnhlo.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtkwflblub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguhfwdga.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtufjpipvd.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtmjibdzqs.html

[U72] PHP：写错误日志
来源：http://dali.pycfn.com/Article/details/gtuwajkazm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhongyouzk.top/Article/details/gtnobnaltu.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gtvlwkdpit.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gtlcdwcebw.html

[U74] PHP：读取环境变量
来源：http://dali.xylfe.cn/Article/details/gtrifyixwp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtqjhnqrms.html

[U75] PHP：依赖注入
来源：http://dali.shuidangran.top/Article/details/gtywapvweu.html

composer require psr/container
来源：http://dali.daria6918.cn/Article/details/gtdobkvlug.html

[U76] PHP：简单路由
来源：http://dali.tian-w.cn/Article/details/gtjghazrcg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gtbupezaba.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gtncrrejpk.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtabjwrdio.html

[U78] PHP：单元测试
来源：http://dali.jianghu66.top/Article/details/gtjzjyeccr.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtglzhxxgx.html

[U79] PHP：静态分析
来源：http://dali.nwbrower.top/Article/details/gtytkebmyr.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gthzltptxy.html

[U80] PHP：代码规范修复
来源：http://dali.sysykeji.top/Article/details/gttgerrpub.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gtiboihilc.html

[U81] JS：初始化项目
来源：http://dali.hnqzz.top/Article/details/gtrdtmgpwy.html

npm init -y;  npm i express
来源：http://dali.zycfv.cn/Article/details/gtucoqwfcg.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtqjorsxyk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gtweaikgol.html

[U83] JS：ES Module 导入导出
来源：http://dali.tanke756.top/Article/details/gtskdvxbnj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtacmvhyei.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gtxfhdivsl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gotoacloud.top/Article/details/gtkiozkdnm.html

[U85] JS：可选链
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzccbumy.html

a?.b?.c
来源：http://dali.nanxuanxn.top/Article/details/gtfcsqebib.html

[U86] JS：空值合并
来源：http://dali.vqdsnc.cn/Article/details/gtelwmrjug.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gterkqhvqw.html

[U87] JS：解构默认值
来源：http://dali.cheryme.top/Article/details/gtvmirnyph.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhongyouzk.top/Article/details/gtmyadeofw.html

[U88] JS：对象展开合并
来源：http://dali.kuanghao11.cn/Article/details/gtbldecjqr.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtedsioeyb.html

[U89] JS：数组去重
来源：http://dali.yongpay.top/Article/details/gtvupohucs.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtkjprupky.html

[U90] JS：数字数组排序
来源：http://dali.jyoumei.cn/Article/details/gtqfnkjajn.html

[...arr].sort((a, b) => a - b)
来源：http://dali.iojbl.cn/Article/details/gtuwqjeion.html

[U91] JS：对象键值遍历
来源：http://dali.jianghu66.top/Article/details/gttzpimwmh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.nanxinkj.top/Article/details/gtybdicceb.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtlwijfbou.html

structuredClone(obj)
来源：http://dali.cucudq.cn/Article/details/gtbfqrwpqb.html


<!-- 参考信息 -->