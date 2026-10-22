代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.redwolf501.top/Article/details/gtmehnqzto.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtkyidwkie.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gttfhuekvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtuwbtddfg.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtwlueyemg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtejeemyqx.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtctrflsyk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtjmrjzlox.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gtmfuumgdm.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtzdpuewph.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gtpaczoymc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.redwolf501.top/Article/details/gtcdbpkrql.html

[T11] Kotlin：协程
来源：http://dali.vqdsnc.cn/Article/details/gtvljnzshc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtuadkfwws.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtijpexnjt.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtuxzqpwnb.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtnyrullnv.html

val m = mapOf("a" to 1)
来源：http://dali.316326.xyz/Article/details/gtcyczikln.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtwxpragrv.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtfbosdiyc.html

[T15] Kotlin：接口
来源：http://dali.shangyingyoupin.top/Article/details/gthydukxlh.html

interface Shape { fun area(): Double }
来源：http://dali.dianchejie.cn/Article/details/gtgjllfhey.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gttpwhwyyu.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwygukv.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtpbyjkxyj.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gthtzfashb.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtiqyiltdi.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtelltczqd.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtihjwrxay.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtdlsrfvpy.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtdzacdjpz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtduqlopjd.html

[T21] Swift：遍历
来源：http://dali.xziqi.cn/Article/details/gtwjlzpear.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtydvkhckp.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtdcbyplgk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtfyxxbjzc.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtrtxchawy.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtipwvxqgv.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoatxjwuq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ehwqpu.com/Article/details/gtbzwhthta.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gtxxvlbmru.html

struct P { var x: Int }
来源：http://dali.jqgufenzy.top/Article/details/gtzkhzcqyr.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gttugzgyiy.html

class A: Base { override func f() {} }
来源：http://dali.shangyingyoupin.top/Article/details/gtjrcmvvmu.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gttnpxekba.html

do { try f() } catch { print(error) }
来源：http://dali.cqqwz.cn/Article/details/gtbhkmmdgg.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gtasugllay.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtcfcsbimb.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gtvvoqichy.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtdfsoyepa.html

[T30] Swift：协议
来源：http://dali.shanyushiyangtech.top/Article/details/gtvodqobwm.html

protocol Shape { func area() -> Double }
来源：http://dali.dianchejie.cn/Article/details/gtknavhmds.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtaboinpck.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtrpgreqtn.html

[T32] Lua：局部变量
来源：http://dali.316326.xyz/Article/details/gtjrngniea.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gtcafakfns.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiijrydnc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gtaivnycde.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtxubzvfxn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hfpthk.cn/Article/details/gtbgeprljr.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtxdcxghwx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtjpnxxzvw.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtaowoboxe.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gttdtrqova.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtwtcdjycp.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtxmexmvij.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gtvryevzdm.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gttnqzpkvu.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gtsgbnynhl.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gtefgakujn.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gtavkipfmb.html

setmetatable({}, { __index = base })
来源：http://dali.yvedp.cn/Article/details/gtqgkhojgp.html

[T41] Perl：Hello World
来源：http://dali.pycfn.com/Article/details/gtbfshwnae.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtocaodvln.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtjezsyvpw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ivvv.top/Article/details/gtwbpqmqkt.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtwnmlnpsb.html

"值: $a"
来源：http://dali.redwolf501.top/Article/details/gtczjycetq.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfunplto.html

if ($a > 0) { print "正"; }
来源：http://dali.dashuyun.cn/Article/details/gtqefqbtfg.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtraydflkb.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtndjefxxl.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtxquziils.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtqhxddhif.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtexejddhv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtacmtzfot.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtvfxvsyyv.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtgcvtdfez.html

[T49] Perl：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxjtzrzwo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtwkcvulbg.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtchzaiwei.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtzcxjwgnj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtjynoemie.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gtpppeswqv.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtbptxlaav.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtrqiqlqgq.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtaialthlf.html

[T53] Scala：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtsamitiup.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtwidanaxs.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtshtfitqc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtqfoipznt.html

[T55] Scala：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtrbebpxki.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtmpnqixsk.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtslgqciaj.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtsnvnrwwq.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtiawgbrlr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuanzhike.top/Article/details/gtzxyvaglj.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtgzegfozv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxjtbkmw.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzvdmlokt.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtvdshcdqr.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gtcukcvqdb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gtffyebbrp.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtiqhdcbux.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yongpay.top/Article/details/gtbtfusjit.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttqybxhgq.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtvwsdglwb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gtolhfuela.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtskghhica.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtuycfutuv.html

[U03] Py：加载 .env 配置
来源：http://dali.mhx1999.top/Article/details/gtrzlwjhfy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtsxenwvxl.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtrcrybdav.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtnzshevib.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtgonczdej.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtcidvmjcr.html

[U06] Py：合并两个字典
来源：http://dali.wangdashe.top/Article/details/gtkjmojidh.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtamavtymm.html

[U07] Py：反转字典键值
来源：http://dali.yongpay.top/Article/details/gtfeaqdqmf.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtlmbosksm.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gtkhbapbpj.html

[y for x in nested for y in x]
来源：http://dali.jinghuilouyu.cn/Article/details/gttaxrqims.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gtvutnklms.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gtqjtpvqha.html

[U10] Py：按值排序字典
来源：http://dali.c1oappe.top/Article/details/gtynrnelqc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tianlin.xyz/Article/details/gtsuhfohaq.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gtrefzgpyy.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtvoiodjvl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ivvv.top/Article/details/gtsqnhuckz.html

Counter(arr).most_common(3)
来源：http://dali.tanke756.top/Article/details/gtuqylofie.html

[U13] Py：固定长度队列
来源：http://dali.jinqigfzy.top/Article/details/gtisdeljio.html

deque(maxlen=10)
来源：http://dali.cucudq.cn/Article/details/gtekoglini.html

[U14] Py：分组收集到列表
来源：http://dali.gaohongyu789.top/Article/details/gtgadiymgf.html

defaultdict(list)
来源：http://dali.aizwys.cn/Article/details/gtntdkjesf.html

[U15] Py：高精度计时
来源：http://dali.jqgufenzy.top/Article/details/gtiwlaxlto.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtmbdemena.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtgmagdjvh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcjukwqw.html

[U17] Py：初始化日志
来源：http://dali.gaohongyu789.top/Article/details/gtohutdrdc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tian-w.cn/Article/details/gtaisxjtyq.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gtddmfwplw.html

pat = re.compile(r"\d+")
来源：http://dali.chenzaomai.com/Article/details/gtdvbdolej.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gtbpyjxgjc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tianlin.xyz/Article/details/gtyknnonys.html

[U20] Py：缓存函数结果
来源：http://dali.yueranfly.top/Article/details/gtihehczoe.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gotoacloud.top/Article/details/gtrqrokuqh.html

[U21] Py：自定义上下文管理器
来源：http://dali.dashuyun.cn/Article/details/gtqlrfcgms.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gttztslcfw.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtrjtluxsa.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtfwmbsboe.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtnyyhwhjd.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtlptimqsz.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtmdcvptce.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuanzhike.top/Article/details/gtrofqwcsc.html

[U25] Py：CSV 按字典读
来源：http://dali.shangyingyoupin.top/Article/details/gtrcwycccy.html

csv.DictReader(f)
来源：http://dali.jqgfzy.top/Article/details/gtnkmxzffh.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gtyscqfwxo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gtbnquwskw.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtszrlhkha.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtpskazbmw.html

[U28] Py：类型别名
来源：http://dali.zhongyouzk.top/Article/details/gtrancehxo.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtqipvamti.html

[U29] Py：属性校验
来源：http://dali.tanke756.top/Article/details/gtpqsbqunz.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gtkukcsxgq.html

[U30] Py：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtyiwqnzhr.html

@dataclass(slots=True)
来源：http://dali.gaohongyu789.top/Article/details/gtxrlxbfuo.html

[U31] Py：单测
来源：http://dali.fengsongda.top/Article/details/gtksfvryau.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gtqjwvtvyg.html

[U32] Py：代码格式化
来源：http://dali.yj202588.top/Article/details/gtffcjztvt.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtzktqbaaz.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gtmofjxnbq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj20258.top/Article/details/gtyqkxolbs.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtadsyikaf.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gtrxgbtruo.html

[U35] Py：发送邮件
来源：http://dali.yongpay.top/Article/details/gttrybtngq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhijiandao.cn/Article/details/gtbkvbkltl.html

[U36] Py：定时任务
来源：http://dali.0kj1m.cn/Article/details/gtuayxxxne.html

schedule.every(10).minutes.do(job)
来源：http://dali.vqdsnc.cn/Article/details/gtdeydsxex.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gttgvhyepx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gtpunuljoq.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtccviqpfz.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtjohkwwrq.html

[U39] Py：判断是否在交互环境
来源：http://dali.daria6918.cn/Article/details/gtxwdkljmr.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcogrrbm.html

[U40] Py：打印到标准错误
来源：http://dali.xuanzx.com/Article/details/gtjvinedyu.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbxarzbkr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigfzy.top/Article/details/gtbffinzxh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shuidangran.top/Article/details/gtowidmywy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.316326.xyz/Article/details/gtbyaggmig.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gtmwbrbqnf.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtlyihsstd.html

namespace App\Http;
来源：http://dali.cashguo.top/Article/details/gtovcfwaht.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtouicikei.html

declare(strict_types=1);
来源：http://dali.zhijiandao.cn/Article/details/gtwucbxhgt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sysykeji.top/Article/details/gtfnrfaznb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtovsbmjff.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtxtjhzerd.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiztccinz.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtsjoflawf.html

int|string $id
来源：http://dali.dianchejie.cn/Article/details/gtbihvcsvl.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtiztckozx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gticlebbma.html

[U49] PHP：只读属性
来源：http://dali.aibaodan.cn/Article/details/gtxvvaifey.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtnxpmjood.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtpjwgbgha.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gtpjvsvrog.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtehjhgghu.html

[$a, $b] = $arr;
来源：http://dali.yvedp.cn/Article/details/gtmfbrhtmi.html

[U52] PHP：箭头函数
来源：http://dali.sysykeji.top/Article/details/gttccmwmls.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gtkegxlogr.html

[U53] PHP：空合并运算符
来源：http://dali.hywenlv.cn/Article/details/gtkkcnfisd.html

$v = $a ?? $b ?? "default";
来源：http://dali.xuetiantiany.cn/Article/details/gteqlqutvp.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gtulvhfupv.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gtfiffxyem.html

[U55] PHP：match 表达式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfwvhzneg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtomthzvhd.html

[U56] PHP：命名参数
来源：http://dali.ivvv.top/Article/details/gtofxoynii.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtmwgbxoza.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gttllzrvge.html

"值: {$a}"
来源：http://dali.0kj1m.cn/Article/details/gtbxjfeklz.html

[U58] PHP：数组三件套
来源：http://dali.quarkkingdee.top/Article/details/gtpikxakaz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fzhhl.top/Article/details/gtgaeppuos.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gtpqtusilz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hfpthk.cn/Article/details/gtjllnkqsn.html

[U60] PHP：JSON 编解码
来源：http://dali.nanxinkj.top/Article/details/gtcmznvbqk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gthhrgpqix.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gtimrhwlvz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfktckppg.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtvxaspnqc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gtwvnmmocv.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gtlppdasbg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.vqdsnc.cn/Article/details/gthsmoguzn.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtzvbtpatj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guannengcc.top/Article/details/gtkrefrsje.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gtnrbdkjvx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhengqikj.top/Article/details/gtzagmtosj.html

[U66] PHP：设置 Cookie
来源：http://dali.jinghuilouyu.cn/Article/details/gtozmwyxzg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.vqdsnc.cn/Article/details/gtdgltpauw.html

[U67] PHP：处理文件上传
来源：http://dali.jqgfzy.top/Article/details/gtnnuvgpsm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtlrwtvqtf.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gtdtptrvvy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cucudq.cn/Article/details/gthyozjiao.html

[U69] PHP：PDO 预处理
来源：http://dali.birdmap.top/Article/details/gtdiqmhxxe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hammf.cn/Article/details/gtxshykyeh.html

[U70] PHP：PDO 事务
来源：http://dali.fzhhl.top/Article/details/gtmselcvju.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgfzy.top/Article/details/gtugikzrea.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gtnlfdbnrx.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuetiantiany.cn/Article/details/gtaetptloj.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gtrtpggwsx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtmjmcxffb.html

[U73] PHP：读取 ini 配置
来源：http://dali.mhx1999.top/Article/details/gtwucwbgld.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gtezzobqfw.html

[U74] PHP：读取环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtvebxdmjp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gtvljrxxev.html

[U75] PHP：依赖注入
来源：http://dali.yj20258.top/Article/details/gtvjshijxq.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gtzqnwgfqx.html

[U76] PHP：简单路由
来源：http://dali.hongshengwenyu.top/Article/details/gtpzudxiil.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gtkzojtkor.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gtogouwglk.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gtftzcmzzv.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtvmdfqmbh.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gtvphjyhwn.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gthqaxbzmn.html

composer require --dev phpstan/phpstan
来源：http://dali.jianghu66.top/Article/details/gtusuaaiby.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gtgtjnijra.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtmghgnyln.html

[U81] JS：初始化项目
来源：http://dali.svipenyu.cn/Article/details/gtbivrlaqa.html

npm init -y;  npm i express
来源：http://dali.nanxuanxn.top/Article/details/gttagdpqmi.html

[U82] JS：package.json 脚本
来源：http://dali.zhoulong.xyz/Article/details/gtvcjyiatk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gtikqlmuzw.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gtbaeefkks.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gogol.net.cn/Article/details/gtgfwemsmm.html

[U84] JS：CommonJS 写法
来源：http://dali.dianchejie.cn/Article/details/gtnovrdfam.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gtvbvollhh.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtgjtbhqgi.html

a?.b?.c
来源：http://dali.feifeiyinyue.top/Article/details/gtthpmrxox.html

[U86] JS：空值合并
来源：http://dali.dianchejie.cn/Article/details/gtosuwcozg.html

a ?? b
来源：http://dali.yj202588.top/Article/details/gtzbtvnntu.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtcpucvcsk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.havefunace.top/Article/details/gtgwrjhshz.html

[U88] JS：对象展开合并
来源：http://dali.316326.xyz/Article/details/gthpzonwpn.html

{ ...a, ...b }
来源：http://dali.yj202588.top/Article/details/gtfatdhtbp.html

[U89] JS：数组去重
来源：http://dali.zhiwuduotai.top/Article/details/gtiokmhlbp.html

[...new Set(arr)]
来源：http://dali.jiagoushi.top/Article/details/gtxsjixnqn.html

[U90] JS：数字数组排序
来源：http://dali.aizwys.cn/Article/details/gtifsycqve.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxinkj.top/Article/details/gtexdfgbdm.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gtlrkalrkx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gzhubu.top/Article/details/gtcgvnbjhx.html

[U92] JS：深拷贝
来源：http://dali.cheryme.top/Article/details/gtxwgzpbip.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtbgldxxnn.html


<!-- 参考信息 -->