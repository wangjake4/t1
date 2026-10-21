代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtthhzjlqh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtwfzkseuc.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtwhxoezgk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tian-w.cn/Article/details/gtxpixicvf.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtcygxuicm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gtjtpsuebr.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtyppankbm.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtssdhbxxx.html

[T09] Kotlin：扩展函数
来源：http://dali.yonumen.top/Article/details/gtmuetvxyy.html

fun String.exclaim() = this + "!"
来源：http://dali.gogol.net.cn/Article/details/gtqbibduuz.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtirwewrsu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtfinsxsoj.html

[T11] Kotlin：协程
来源：http://dali.zdqjudy.top/Article/details/gtoqgdnrqh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtitmomqpz.html

[T12] Kotlin：解构声明
来源：http://dali.aibaodan.cn/Article/details/gtzwqubkil.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtnckaqboa.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtbqcbehad.html

val m = mapOf("a" to 1)
来源：http://dali.guannengcc.top/Article/details/gttitwezwo.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtehidudqz.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtlmjjdysw.html

[T15] Kotlin：接口
来源：http://dali.yuanzhike.top/Article/details/gtzsniwxgd.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gtcabnhzfj.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtkqrntrna.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtirbrxtso.html

[T17] Swift：变量与常量
来源：http://dali.wangdashe.top/Article/details/gtusvmjema.html

var a = 1;  let b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtihbqnkmp.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gthxsbzmbw.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtngeynhrt.html

[T19] Swift：可选绑定
来源：http://dali.shuidangran.top/Article/details/gtdkfgofgh.html

if let n = opt { print(n) }
来源：http://dali.xylfe.cn/Article/details/gtscewnemh.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtnjhbnlzo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ybcxt.top/Article/details/gttwdtbron.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gtidualwlp.html

for x in a { print(x) }
来源：http://dali.chenjidiqi.icu/Article/details/gtckubpbuq.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtzcnjjjgc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gthrrfhimo.html

[T23] Swift：函数
来源：http://dali.9152youxi.cn/Article/details/gtlecghqcy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gtfhojfsqh.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtvsprkmze.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gttsjleyuh.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gtlwofacab.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtujpdoxsc.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtbgowemlh.html

class A: Base { override func f() {} }
来源：http://dali.chenlongwang.top/Article/details/gtdzgndbui.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtiwkgylit.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtpavoccpc.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gtqrdsyoqv.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtpmdctifw.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtjibtlrxb.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtantoqcdr.html

[T30] Swift：协议
来源：http://dali.guannengcc.top/Article/details/gtughdklmt.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gthhfwdmqc.html

[T31] Lua：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtpumpjwaa.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtmljmrpnx.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtlcmczjrq.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtaowwgiea.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gtugwgffee.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtprlsjzdq.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gtenkpprqb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaypprvci.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwakkezbs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gtowxaqrxi.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gtmygxqsdc.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gtkboktjhz.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gtbfiaopqm.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtslvcevmh.html

[T38] Lua：条件
来源：http://dali.hysaishi.cn/Article/details/gtybkeauzk.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtogicobnh.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtwnohrxlr.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gtfpevejzc.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gtkfgsuzlt.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtlhgfzvpm.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtnyogrjrs.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtauggdiwm.html

[T42] Perl：变量类型
来源：http://dali.hywenlv.cn/Article/details/gtmeidnkip.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtejpilnnt.html

[T43] Perl：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtzqqspxvu.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtdddvseju.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtjuygckur.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzbxjxxrw.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtwboljsrf.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gtuqumlxlt.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbsupxeyo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtelkwofdd.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gtuprgbbsn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtmfcnmkud.html

[T48] Perl：正则替换
来源：http://dali.yangfankeji.com/Article/details/gtvznjywhm.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtdtadiwsm.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gtymivhkjx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtrlxeqscf.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtwblodllc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtvatofxtu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gtdfqkneys.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtfpglwrep.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtwxfizonb.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtvpkpnmxi.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtitdwijtd.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gteamfvynw.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtihlvbppx.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtardnfxzz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtvqhjyfyh.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtdkmghxvn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gtbutndrlx.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtburylaue.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtzxtgqavm.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gthqniqdwq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gtbzvbeqgb.html

[T58] Scala：函数定义
来源：http://dali.nanxuanxn.top/Article/details/gtopcurghn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gtmjqsdwuf.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gtozhuktst.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtkrncbdix.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gttjckeurc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuetiantiany.cn/Article/details/gtiwggbzkr.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyabldfg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtoirpcyos.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gttumdmxwp.html

[U01] Py：创建虚拟环境
来源：http://dali.pycfn.com/Article/details/gtfipgcksg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gtttkveetg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtbflzwcdu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtyjvlekej.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtqumjikmc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gthecevgbt.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gtrhgbqccr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtbwithfzl.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtsmojnfvl.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtfrrvlsdw.html

[U06] Py：合并两个字典
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujlyfzii.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gthewxxbel.html

[U07] Py：反转字典键值
来源：http://dali.yvedp.cn/Article/details/gtfxdyuemp.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gttwzugotj.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gtwrfudwqc.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfejircy.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtecwymqtn.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtjiciqsny.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtuvevfkwe.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigufen.top/Article/details/gtdxpogmum.html

[U11] Py：生成器表达式
来源：http://dali.jianghu66.top/Article/details/gtuvgwbofx.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtoohvijqq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gogol.net.cn/Article/details/gtlehwwmjt.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpfxdeklw.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gthuabockq.html

deque(maxlen=10)
来源：http://dali.quarkkingdee.top/Article/details/gtrhqvkmfv.html

[U14] Py：分组收集到列表
来源：http://dali.ehwqpu.com/Article/details/gtjiytcmsf.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gtgrdyfibg.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtfjnhsgak.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtxbsolulm.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gtrdljdwpl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gtukflpttn.html

[U17] Py：初始化日志
来源：http://dali.jinqigfzy.top/Article/details/gtxcydmcxq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yanxiufei.cn/Article/details/gtzjboobki.html

[U18] Py：预编译正则
来源：http://dali.yj202588.top/Article/details/gtvxmkazhb.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtlaypxsgf.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gthqlqjjwo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xylfe.cn/Article/details/gtouybjgjy.html

[U20] Py：缓存函数结果
来源：http://dali.sysykeji.top/Article/details/gtjzixrpdl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtohbvxcpa.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenlongwang.top/Article/details/gtaosyhurt.html

@contextlib.contextmanager
来源：http://dali.shzxlz.cn/Article/details/gtfjeymacu.html

[U22] Py：矩阵转置
来源：http://dali.yvedp.cn/Article/details/gtbgupiwbp.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gttkityzxr.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoldqzbjk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gtgveqlvyi.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtogeucees.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gteitdtibq.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtlvdkqaef.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtcbokpblk.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtdrgojvhq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gtcaufpawp.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gthkpgwtus.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuautmah.html

[U28] Py：类型别名
来源：http://dali.nwbrower.top/Article/details/gteppcsgoc.html

UserId = int
来源：http://dali.feifeiyinyue.top/Article/details/gtshxukfme.html

[U29] Py：属性校验
来源：http://dali.9152youxi.cn/Article/details/gtejhlupbd.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtvntmqyer.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gtddltzjdk.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gtranprvdn.html

[U31] Py：单测
来源：http://dali.ivvv.top/Article/details/gtjxdoazqa.html

python -m pytest -q
来源：http://dali.tian-w.cn/Article/details/gtygnuwluh.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtifqeuwzp.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gtygpstren.html

[U33] Py：打包发布
来源：http://dali.xinyue.icu/Article/details/gtbniribsg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gthqksqspg.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtzkuqpxsy.html

chardet.detect(raw)
来源：http://dali.hysaishi.cn/Article/details/gtpftsjwvm.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtwyebegum.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ybcxt.top/Article/details/gtmkiiyrfj.html

[U36] Py：定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxmnqkwkw.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gttbjosvah.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gtluvkbeou.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sufxvd.cn/Article/details/gtotieuqoj.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gtehpyferp.html

Path(__file__).resolve().parent
来源：http://dali.ybcxt.top/Article/details/gtvprwgmjg.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gtaxxtcasq.html

sys.stdout.isatty()
来源：http://dali.feifeiyinyue.top/Article/details/gtetrfmmhw.html

[U40] Py：打印到标准错误
来源：http://dali.yuanzhike.top/Article/details/gtbdiemiso.html

print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtzttrrmcl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yonumen.top/Article/details/gtbvksfosn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shangyingyoupin.top/Article/details/gtthcwqids.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gtkktrwyjk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gtgutjvdiw.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtfyocjguo.html

namespace App\Http;
来源：http://dali.yuanzhike.top/Article/details/gtlhiveuzq.html

[U44] PHP：开启严格类型
来源：http://dali.pengpengdd.cyou/Article/details/gtjzcjxxqb.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtkexmmcpv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gtknmxeeic.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtidzdrkdu.html

[U46] PHP：可空类型
来源：http://dali.nanxinkj.top/Article/details/gtuiquvbjf.html

?string $name = null
来源：http://dali.jlsjyb.cn/Article/details/gtcrfcwaqu.html

[U47] PHP：联合类型
来源：http://dali.daxiang520.top/Article/details/gteymwvpem.html

int|string $id
来源：http://dali.yonumen.top/Article/details/gtiohvflsn.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gtkrnccvou.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrnngmedw.html

[U49] PHP：只读属性
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpgtbblj.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtctqjjqum.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtsmwolevi.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gtbkilqtal.html

[U51] PHP：数组解构
来源：http://dali.aizwys.cn/Article/details/gtwgybcaog.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gtbjdjqclw.html

[U52] PHP：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gtucpostnw.html

$double = fn($x) => $x * 2;
来源：http://dali.sxryk.cn/Article/details/gtdrasabyv.html

[U53] PHP：空合并运算符
来源：http://dali.hfpthk.cn/Article/details/gtjpevduxk.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gtuwqpujkt.html

[U54] PHP：空安全调用
来源：http://dali.jinqigufen.top/Article/details/gtzizpqiom.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gtxkikvnns.html

[U55] PHP：match 表达式
来源：http://dali.yangfankeji.com/Article/details/gtswhplgnh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gtnztljead.html

[U56] PHP：命名参数
来源：http://dali.chenzaomai.com/Article/details/gtwfceqvnl.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtybnoytcd.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtttihzmxs.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gtwekfeffj.html

[U58] PHP：数组三件套
来源：http://dali.vqdsnc.cn/Article/details/gtbtrxikgo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gtdrnvnqkm.html

[U59] PHP：自定义排序
来源：http://dali.jlsjyb.cn/Article/details/gtlhsujjmm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gtylsztbtl.html

[U60] PHP：JSON 编解码
来源：http://dali.zhijiandao.cn/Article/details/gtqlfjahiu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtgtyeztjv.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gtnvrkoxtz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xylfe.cn/Article/details/gtdfkzdpgk.html

[U62] PHP：日期对象
来源：http://dali.cheryme.top/Article/details/gtypmmsbok.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gtjnxvfugk.html

[U63] PHP：文件读写
来源：http://dali.cdnleiting.top/Article/details/gtfnvassqf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jqgfzy.top/Article/details/gtufujkmcj.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtbvwbicwp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jiagoushi.top/Article/details/gtgtglbjcb.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoiwfoenq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtbunggffg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbbutqvtd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xziqi.cn/Article/details/gtklaliooj.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gthirzaqzq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fengsongda.top/Article/details/gtbwgpqeqg.html

[U68] PHP：PDO 连接
来源：http://dali.wangshuangyany.cn/Article/details/gtywmztkfu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtqofeeoii.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtgdnlercj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnxiangtu.top/Article/details/gthbnbdepo.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtxsxoemzh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gtofbchjzp.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtzuzotwim.html

throw new RuntimeException("失败", 500);
来源：http://dali.jianghu66.top/Article/details/gtrwcqnpvj.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmihkxdwf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gtskaudcnu.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtrgnkklxy.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gtuwbvmoga.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtzixmggsx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtsfqxwfyh.html

[U75] PHP：依赖注入
来源：http://dali.jinqigfzy.top/Article/details/gtonrbivfm.html

composer require psr/container
来源：http://dali.c1oappe.top/Article/details/gttbizuybq.html

[U76] PHP：简单路由
来源：http://dali.hysaishi.cn/Article/details/gtsrrznwab.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfupxdlev.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gtxjtodgtd.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtirioyfej.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtivfdknsi.html

composer require --dev phpunit/phpunit
来源：http://dali.zdqjudy.top/Article/details/gtrhqtwmww.html

[U79] PHP：静态分析
来源：http://dali.shangyingyoupin.top/Article/details/gtltgxtmby.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtklfrnlnm.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gttwqpffwy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtxcqwqrkr.html

[U81] JS：初始化项目
来源：http://dali.hfpthk.cn/Article/details/gtxefpogct.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gtmkvbhpfz.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gtpavtdsyh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgfzy.top/Article/details/gtqmrvsimq.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gtlcybqscu.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gtwwmjixdq.html

[U84] JS：CommonJS 写法
来源：http://dali.cashguo.top/Article/details/gtekbvtdmb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jyoumei.cn/Article/details/gtnvtcjbna.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtgjzmijuq.html

a?.b?.c
来源：http://dali.hongshengwenyu.top/Article/details/gtwkndlfgs.html

[U86] JS：空值合并
来源：http://dali.ydzc1.top/Article/details/gtawmnibwl.html

a ?? b
来源：http://dali.zycfv.cn/Article/details/gttbdggrxv.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtzarsrbpp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhiwuduotai.top/Article/details/gtfjvvjnhv.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtruwjjoar.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtqdwjocht.html

[U89] JS：数组去重
来源：http://dali.dianchejie.cn/Article/details/gtuvwujwfd.html

[...new Set(arr)]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtognwaqcl.html

[U90] JS：数字数组排序
来源：http://dali.zycfv.cn/Article/details/gtvbljfnkf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cqqwz.cn/Article/details/gtzgyjgvgq.html

[U91] JS：对象键值遍历
来源：http://dali.hongshengwenyu.top/Article/details/gttbwpvoqc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtswftjnxa.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtzxakaqvy.html

structuredClone(obj)
来源：http://dali.yongpay.top/Article/details/gtjpjfoltq.html


<!-- 参考信息 -->