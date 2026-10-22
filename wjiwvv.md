代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.tian-w.cn/Article/details/gtsdqzsicd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gttyvayueo.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtvrjzosmh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtsvrexlds.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtskbbzppd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtqgzcbnph.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtkaclgqwj.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtyyntyhme.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtqabckcfh.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gtumhbstya.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gtjxjzzith.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtxyrcvlha.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtypduxviw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cdnleiting.top/Article/details/gthctuhqlg.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwbfgacx.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gtiphukweo.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gtfzqwynql.html

val m = mapOf("a" to 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtdabofznf.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtbcxcjfri.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtcjkajdko.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsocsvjv.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gtmspdknqo.html

[T16] Swift：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtrkjsczyb.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtpikzqbxw.html

[T17] Swift：变量与常量
来源：http://dali.shuidangran.top/Article/details/gtosarwzfc.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtzetppxwo.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtggziaudn.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gteuupqpyu.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtjhnopqeb.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtegvgrtkq.html

[T20] Swift：数组操作
来源：http://dali.dashuyun.cn/Article/details/gtfhigzmnr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xziqi.cn/Article/details/gtfzpslcdn.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtgalyejqi.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtbhowfdxy.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtbowoqppc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtytbdgiiy.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gtktiglcor.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gtmtkjkxbd.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqbgfhwo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtpkqanest.html

[T25] Swift：结构体
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsovphcjx.html

struct P { var x: Int }
来源：http://dali.smart0.xyz/Article/details/gtpjvlxgre.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtfsadtheo.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxcthmwwd.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtilcfcrtr.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtajeuusis.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtddnwfdqr.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtmirspasm.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtpxeedwsr.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtmwmgkiud.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtlwugunlw.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtfrzptdrv.html

[T31] Lua：Hello World
来源：http://dali.tian-w.cn/Article/details/gtwidwkcjf.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtxcmzktey.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtfyxlzyex.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtdnaqskbp.html

[T33] Lua：表（数组）
来源：http://dali.chenlongwang.top/Article/details/gtsooclwdp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sweek.top/Article/details/gtifwnfgnb.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gtmnjqkbmq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtrzibviti.html

[T35] Lua：字典表
来源：http://dali.snrcjt.cn/Article/details/gtwvrhzmod.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daxiang520.top/Article/details/gtkdqfpfiw.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtfcbwmmkh.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gthjyimxjo.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtsbgqnoov.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtevcuwedx.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtebqrgnvc.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtwbapidyy.html

[T39] Lua：模式匹配
来源：http://dali.gaohongyu789.top/Article/details/gtgxigcjvk.html

string.find(s, "%d+")
来源：http://dali.zhiwuduotai.top/Article/details/gtdggyolco.html

[T40] Lua：元表
来源：http://dali.xuanzx.com/Article/details/gtbzfgmsuj.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtcqbemxqa.html

[T41] Perl：Hello World
来源：http://dali.hammf.cn/Article/details/gtrjewfiwf.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtrtvaaqih.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtvcrpigxp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gtxlwaypby.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtcgbbhacx.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtvjnaywta.html

[T44] Perl：条件
来源：http://dali.gzhubu.top/Article/details/gtfhglopgc.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gtshqlxaae.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtmclmhxsh.html

for my $x (@arr) { print $x; }
来源：http://dali.cheryme.top/Article/details/gtayimxqro.html

[T46] Perl：哈希操作
来源：http://dali.iojbl.cn/Article/details/gtbylfvveh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsewdsyw.html

[T47] Perl：正则捕获
来源：http://dali.aizwys.cn/Article/details/gtfhmrdlsx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtrgifohrh.html

[T48] Perl：正则替换
来源：http://dali.cashguo.top/Article/details/gtphpwxoiw.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtmyzbczhx.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtcxisvyum.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthvgekopv.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtavapjlra.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.bjfxy.top/Article/details/gtaqjgdtqa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gthyglfxyq.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtzfmpxhqa.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtnlyvgpcz.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gtqidsgyev.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtyyjcplrl.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtuemwlfoz.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtyohnqsov.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtmbhfshdx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuanzx.com/Article/details/gtpphdpxqh.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtubmvjwxr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtnvqlazfd.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gttfkazcmn.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtgyvbquzl.html

[T57] Scala：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtcgjbzssj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gthlbfbfxg.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gtijvrdtvo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtnsttojcv.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtymbjyeqk.html

for (i <- 1 to 10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gtjbmlsnkg.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtlorvbjxp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hongshengwenyu.top/Article/details/gtjpxmoevy.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtgsurslsf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dianchejie.cn/Article/details/gtymkcxhob.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtcpatnhis.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtnvnycuzk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gtwhynfsxl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtplbdmkib.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmjtizkow.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gtumgofsfp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtcsxawthn.html

[U04] Py：变量调试打印
来源：http://dali.iojbl.cn/Article/details/gtvvceyktr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daxiang520.top/Article/details/gtecbocfjr.html

[U05] Py：列表去重且保序
来源：http://dali.hysaishi.cn/Article/details/gtgtbkuwuj.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gtrxaoblfq.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gtciogkrgb.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbdfjkru.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gttzkvtpiz.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gthrzsdyen.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtpselqieq.html

[y for x in nested for y in x]
来源：http://dali.ivvv.top/Article/details/gtlkblpuay.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtrxqkpcwl.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gtpveonztr.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtkjbpktex.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtzkhhcutc.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gttajsajqa.html

(x * 2 for x in arr)
来源：http://dali.dashuyun.cn/Article/details/gtokgjrsdi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtejuxcwix.html

Counter(arr).most_common(3)
来源：http://dali.kuanghao11.cn/Article/details/gtkizduwsu.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gtqprgyikw.html

deque(maxlen=10)
来源：http://dali.zhixingplan.top/Article/details/gtupqwdayx.html

[U14] Py：分组收集到列表
来源：http://dali.zhengqikj.top/Article/details/gtqsspydea.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtgjxsthgu.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtbfyxmdrj.html

t = time.perf_counter()
来源：http://dali.guannengcc.top/Article/details/gtthdcgewi.html

[U16] Py：命令行参数解析
来源：http://dali.gzhubu.top/Article/details/gtzgkuayos.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtgasdmbnn.html

[U17] Py：初始化日志
来源：http://dali.hongshengwenyu.top/Article/details/gtisovcuke.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtsxsemfmn.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtgphmrckl.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtotkevzhn.html

[U19] Py：正则替换带回调
来源：http://dali.hongshengwenyu.top/Article/details/gtzhbqirbp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.snrcjt.cn/Article/details/gtjkcrvnhs.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gteqbgmnnu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtxnswxgrq.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigfzy.top/Article/details/gtglblxvwh.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gtrkcsfmdv.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtnsncznkh.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gthobxrjsb.html

[U23] Py：分块读取大文件
来源：http://dali.hywenlv.cn/Article/details/gturtigzxl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtfjxghcfb.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gtuizexpox.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gthrrcinka.html

[U25] Py：CSV 按字典读
来源：http://dali.xinyue.icu/Article/details/gtnijtmrgx.html

csv.DictReader(f)
来源：http://dali.ybcxt.top/Article/details/gtcweapyxg.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtayvwitxi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthfuhiaaz.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxrpiktdx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.daxiang520.top/Article/details/gtwtlrcbwm.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtxtsbcddb.html

UserId = int
来源：http://dali.daria6918.cn/Article/details/gtsnlfmqqr.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtknphpymc.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsxrbmwg.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gtokdxylxr.html

@dataclass(slots=True)
来源：http://dali.snrcjt.cn/Article/details/gtnkbrdwyb.html

[U31] Py：单测
来源：http://dali.zhoulong.xyz/Article/details/gtlflqznsy.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtoixndgqe.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gtcitpewxc.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtoiltsegh.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtorkrdolm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtewzxfuce.html

[U34] Py：判断编码
来源：http://dali.hammf.cn/Article/details/gtrugnijtr.html

chardet.detect(raw)
来源：http://dali.zhongyouzk.top/Article/details/gtunyvdhjq.html

[U35] Py：发送邮件
来源：http://dali.xylfe.cn/Article/details/gtrrxiqqty.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gotoacloud.top/Article/details/gtkwvrnxvw.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gtauffqbxf.html

schedule.every(10).minutes.do(job)
来源：http://dali.andypj.xyz/Article/details/gtzsiahuoa.html

[U37] Py：读写 Excel
来源：http://dali.ehwqpu.com/Article/details/gtfaqwfnyb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gtbqayowdb.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenzaomai.com/Article/details/gtvpamyubj.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtnfbphjpz.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gteofdsvni.html

sys.stdout.isatty()
来源：http://dali.daxiang520.top/Article/details/gthipfoxnj.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gtbbjsgook.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gtfxwlopgt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gtyvggodui.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gtzizuwxpv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gtampzeydc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gtgmnlhowz.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gthoxdyoft.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnuuyikoj.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gtdeugrblx.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtgrfuwzdq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtnrplcmjh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtigszgbjd.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtubkcgxfa.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gtrkhyekme.html

[U47] PHP：联合类型
来源：http://dali.havefunace.top/Article/details/gtrblcehoq.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gtpbwlcybj.html

[U48] PHP：纯枚举
来源：http://dali.jyoumei.cn/Article/details/gtpwkbuldh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nwbrower.top/Article/details/gtlxmdeirn.html

[U49] PHP：只读属性
来源：http://dali.mhx1999.top/Article/details/gtjzkbbscz.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gtxqxuwtxr.html

[U50] PHP：构造器属性提升
来源：http://dali.yongpay.top/Article/details/gtblizdwjp.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtuxtndfuq.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtinalkega.html

[$a, $b] = $arr;
来源：http://dali.0kj1m.cn/Article/details/gtmvxxblve.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtnczgrkev.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtewrcucpi.html

[U53] PHP：空合并运算符
来源：http://dali.jqgufenzy.top/Article/details/gtfgjpgfze.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gthlmulznu.html

[U54] PHP：空安全调用
来源：http://dali.iojbl.cn/Article/details/gtcnxjsnol.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gtvixfllbk.html

[U55] PHP：match 表达式
来源：http://dali.cucudq.cn/Article/details/gtunmstmra.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlekzvpds.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gtlihplmkr.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtithdglow.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gtlkoratwd.html

"值: {$a}"
来源：http://dali.yuanzhike.top/Article/details/gtkapywhau.html

[U58] PHP：数组三件套
来源：http://dali.hfpthk.cn/Article/details/gtddxpufyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtoomkcjxh.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gtdfmhkaqg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jiagoushi.top/Article/details/gtmfrmgvqm.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gturjwtmgz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fzhhl.top/Article/details/gttnraohmh.html

[U61] PHP：正则
来源：http://dali.sufxvd.cn/Article/details/gtvgnxwrye.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gtqhlbpcxl.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gttikfirog.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.quarkkingdee.top/Article/details/gtlsifmqzd.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtsfsmnbuy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.316326.xyz/Article/details/gtjhkhbert.html

[U64] PHP：目录遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuegprpeg.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gtqtkkbkxc.html

[U65] PHP：会话
来源：http://dali.shanyushiyangtech.top/Article/details/gtuomjhidu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhwsgqgy.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcwszmrw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gtngclqbzr.html

[U67] PHP：处理文件上传
来源：http://dali.nwbrower.top/Article/details/gtwtsdtasb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gttxlwktcw.html

[U68] PHP：PDO 连接
来源：http://dali.tian-w.cn/Article/details/gtubmexawe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.meibo888.top/Article/details/gtxkatfinn.html

[U69] PHP：PDO 预处理
来源：http://dali.aibaodan.cn/Article/details/gtyhshyccx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtreqdbcxf.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtiezoesfd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgfzy.top/Article/details/gtxckfyukv.html

[U71] PHP：抛出异常
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhhffxvw.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gtqjvgxjlr.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gtwjjveedy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gtybxzdlba.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtiysenvnd.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtboquwwho.html

[U74] PHP：读取环境变量
来源：http://dali.ehwqpu.com/Article/details/gtzadqopni.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gtuhhtexpp.html

[U75] PHP：依赖注入
来源：http://dali.haohaochexian.top/Article/details/gtpjmonhsw.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gtmtbmidxq.html

[U76] PHP：简单路由
来源：http://dali.cdnleiting.top/Article/details/gtdyhfvsyv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gtakocgubs.html

[U77] PHP：模板渲染
来源：http://dali.iojbl.cn/Article/details/gtardcwtvy.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gtemhyzlng.html

[U78] PHP：单元测试
来源：http://dali.shuidangran.top/Article/details/gtkzqbsoje.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gtffyuzexg.html

[U79] PHP：静态分析
来源：http://dali.bjfxy.top/Article/details/gtgqrxvimx.html

composer require --dev phpstan/phpstan
来源：http://dali.pengpengdd.cyou/Article/details/gtyswquuea.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlzijupt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.316326.xyz/Article/details/gtmevmvxer.html

[U81] JS：初始化项目
来源：http://dali.jqgufenzy.top/Article/details/gtfwkvzuxv.html

npm init -y;  npm i express
来源：http://dali.jinqigfzy.top/Article/details/gtumjmvgym.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtbxotvtug.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwaeefnb.html

[U83] JS：ES Module 导入导出
来源：http://dali.mhx1999.top/Article/details/gtcrvqwvnm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtyryozifx.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gtojlgofjv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.bjfxy.top/Article/details/gthdppkpni.html

[U85] JS：可选链
来源：http://dali.smart0.xyz/Article/details/gtnsztxlbw.html

a?.b?.c
来源：http://dali.haohaochexian.top/Article/details/gtzyiwsfym.html

[U86] JS：空值合并
来源：http://dali.nanxuanxn.top/Article/details/gtxpzspipx.html

a ?? b
来源：http://dali.jqgfzy.top/Article/details/gtnfdwilwh.html

[U87] JS：解构默认值
来源：http://dali.guowangkeji.top/Article/details/gtwerpneqa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yvedp.cn/Article/details/gtycwnplrb.html

[U88] JS：对象展开合并
来源：http://dali.ivvv.top/Article/details/gtfmhlrhkz.html

{ ...a, ...b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnknadsrb.html

[U89] JS：数组去重
来源：http://dali.jqgufenzy.top/Article/details/gtayjjaklp.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcysovysz.html

[U90] JS：数字数组排序
来源：http://dali.zhongyouzk.top/Article/details/gtddakufgz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shanyushiyangtech.top/Article/details/gthglwrgts.html

[U91] JS：对象键值遍历
来源：http://dali.guannengcc.top/Article/details/gtbukrbpcc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.cucudq.cn/Article/details/gtjibxumet.html

[U92] JS：深拷贝
来源：http://dali.sysykeji.top/Article/details/gtopdyuazq.html

structuredClone(obj)
来源：http://dali.cashguo.top/Article/details/gtgffoskff.html


<!-- 参考信息 -->