代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gthhijpmpt.html

"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtvdkputwd.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtagejnaxw.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtycncgszs.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtdshyzdkj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gttcphxxqo.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtakbrmehn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtghvbopgh.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtykderbfd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgfzy.top/Article/details/gtihbemfsg.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtjuynwirx.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtwtkeekoq.html

[T09] Kotlin：扩展函数
来源：http://dali.yongpay.top/Article/details/gtkixiyxap.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtngkxjkkq.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtvdmnykwh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gtlpgbsish.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gtudhiyewk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtqalzlukj.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtmibhzzyz.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258.top/Article/details/gtgqxkaldv.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtsymnpsld.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtwnntpubm.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtomzmddgp.html

for (i in 1..10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtwafwcjbi.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtjtjpnloe.html

interface Shape { fun area(): Double }
来源：http://dali.sxryk.cn/Article/details/gtttxewwgg.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gtgbjvaedv.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtidnctqrl.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gtimvxiqhx.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlikkhqam.html

[T18] Swift：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtkorpaflt.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtpoucvxdm.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gtyvkqwrrx.html

if let n = opt { print(n) }
来源：http://dali.zhongyouzk.top/Article/details/gtbocskzun.html

[T20] Swift：数组操作
来源：http://dali.pengpengdd.cyou/Article/details/gtwpzhkgrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtxwoxlkgi.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gttsegwrhl.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtkyntnota.html

[T22] Swift：字典
来源：http://dali.ybcxt.top/Article/details/gtfufggvyx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtivwinujx.html

[T23] Swift：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtbpjbrpay.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtimkxebzb.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtslutcify.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtihqlocih.html

[T25] Swift：结构体
来源：http://dali.jiagoushi.top/Article/details/gtlqqlnegy.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gtatlzkkmx.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtmymgxzfz.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtzpnexbxc.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjmntyxvi.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtnbutmtxi.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtnuoglyno.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtpbwjuohh.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtyiipgqyq.html

guard let x = opt else { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrfzowjhe.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gtpnfdfhmo.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gtyhhwpxhk.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtocqmxifb.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtznqijrpk.html

[T32] Lua：局部变量
来源：http://dali.yanxiufei.cn/Article/details/gtvldiqveq.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtzsprmtra.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gtoxkwuylp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtezhbvwtz.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtlodtzxwd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cucudq.cn/Article/details/gtukrtvcyh.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtmvhhvnvw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jianghu66.top/Article/details/gthizutwbn.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gtlolpewjd.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtocjzmbyf.html

[T37] Lua：字符串拼接
来源：http://dali.jqgfzy.top/Article/details/gtxtnushgs.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtxbwydrpk.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtoizyrhjq.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gtiffcocgo.html

[T39] Lua：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtdoprcmie.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtnbuyspcd.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtjfgnxaam.html

setmetatable({}, { __index = base })
来源：http://dali.jianghu66.top/Article/details/gtylfmdxmp.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnclkeohw.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtrymupznm.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtgvklkwki.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jyoumei.cn/Article/details/gtmjfazjqm.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtumpfhnsg.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtixaprefg.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gthqycbfpu.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gttffbhjcz.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtemccvhro.html

for my $x (@arr) { print $x; }
来源：http://dali.havefunace.top/Article/details/gtgqexuqdg.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuslyvmi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsujxldl.html

[T47] Perl：正则捕获
来源：http://dali.hammf.cn/Article/details/gtsqhjwxcu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gtvwnmmhfr.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gtoxhgxfck.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtvhinkvws.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtqbdqtghr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gttnermpix.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgnripypm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zdqjudy.top/Article/details/gtgicsokjn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtowjjrtnx.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtkokengyg.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtbbxfmlah.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gtndtoeefl.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtyompmfuz.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtzuyrdlqb.html

s"值: $b"
来源：http://dali.cashguo.top/Article/details/gthnuciess.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtpmlnldty.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gtqocxbjwx.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtrbcelmnu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwufnzsvq.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtuivcucum.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtgiajmdnx.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtdbfqgffq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zdqjudy.top/Article/details/gtysggpnba.html

[T58] Scala：函数定义
来源：http://dali.jianghu66.top/Article/details/gtncywnesy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtzgrshjqu.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtgetqvbkn.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtzunllswt.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtisgvoouy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gttngbvmwh.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtsukngbol.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtefmfcfqw.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqlexggoj.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtwxzikzst.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjwrmcta.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhengqikj.top/Article/details/gtikrfqpbs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gtgjidgshv.html

[U03] Py：加载 .env 配置
来源：http://dali.xylfe.cn/Article/details/gthrzgbmte.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtowupctng.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtzfqrmpsq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gttdbvtzrk.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtiahjmakz.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtwonyndpc.html

[U06] Py：合并两个字典
来源：http://dali.pengpengdd.cyou/Article/details/gtcppqheec.html

{**a, **b}
来源：http://dali.aibaodan.cn/Article/details/gthvoespuj.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtlytsmbmx.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtgwjogout.html

[U08] Py：展平二维列表
来源：http://dali.sweek.top/Article/details/gtzznmqjry.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gtsrjwgwte.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gtmimuieus.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtqjztzmnz.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtrxrytmvw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gthpcybljp.html

[U11] Py：生成器表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqrvdkioa.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gtqzrlujtu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gthcsrqqqo.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtplpghmsl.html

[U13] Py：固定长度队列
来源：http://dali.xylfe.cn/Article/details/gtgnqxpctp.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtuxsvnekz.html

[U14] Py：分组收集到列表
来源：http://dali.haohaochexian.top/Article/details/gtjhtbuwcy.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gtsvmjukak.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsuzeqkdw.html

t = time.perf_counter()
来源：http://dali.daria6918.cn/Article/details/gtqleigptj.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gtzuwlnxkn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj20258888.top/Article/details/gtgmivfzzx.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtxjzllnfk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtnhyrgixt.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtgnksrpjx.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtrywonqqf.html

[U19] Py：正则替换带回调
来源：http://dali.chenjidiqi.icu/Article/details/gtntvvjnlg.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.tian-w.cn/Article/details/gtovmshdnc.html

[U20] Py：缓存函数结果
来源：http://dali.yongpay.top/Article/details/gtvysxbojl.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhengqikj.top/Article/details/gtdwgjdgoy.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtzeezywmb.html

@contextlib.contextmanager
来源：http://dali.ehwqpu.com/Article/details/gtzqwxinjd.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtqbkpahag.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtnevsmtvl.html

[U23] Py：分块读取大文件
来源：http://dali.guowangkeji.top/Article/details/gtbioneubg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtmizbmpmq.html

[U24] Py：路径操作
来源：http://dali.fzhhl.top/Article/details/gtbcgejahb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ehwqpu.com/Article/details/gttycyeigp.html

[U25] Py：CSV 按字典读
来源：http://dali.chenzaomai.com/Article/details/gtxbpbtejw.html

csv.DictReader(f)
来源：http://dali.jinqigfzy.top/Article/details/gttqgogctf.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtaqlmndmc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tianlin.xyz/Article/details/gteqaiskme.html

[U27] Py：异步 HTTP
来源：http://dali.kuanghao11.cn/Article/details/gtxmdqhlqe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtwnyuqawa.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gttaqajmpe.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gtvbfdghlh.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gthbimyetr.html

@property 与 @x.setter 配合
来源：http://dali.fengsongda.top/Article/details/gtvdkejqcd.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gtdimqkgmn.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gtvobyotkk.html

[U31] Py：单测
来源：http://dali.dashuyun.cn/Article/details/gtwvzdkuny.html

python -m pytest -q
来源：http://dali.jqgufenzy.top/Article/details/gtdsdytgrc.html

[U32] Py：代码格式化
来源：http://dali.xziqi.cn/Article/details/gtmbqrqtpu.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gtekrlrbnp.html

[U33] Py：打包发布
来源：http://dali.hywenlv.cn/Article/details/gtepwnyekn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gtllchlmzj.html

[U34] Py：判断编码
来源：http://dali.yuanzhike.top/Article/details/gtfktqjmym.html

chardet.detect(raw)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdwxoksa.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gtncngvpfz.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtrmdtwpes.html

[U36] Py：定时任务
来源：http://dali.pycfn.com/Article/details/gtyjitatsr.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gtfsukgwkq.html

[U37] Py：读写 Excel
来源：http://dali.smart0.xyz/Article/details/gtupgudyvf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gtpiyocyef.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhixingplan.top/Article/details/gtxmqmjslf.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtdsvgdqim.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtyjegdkum.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gttfeawxkc.html

[U40] Py：打印到标准错误
来源：http://dali.xylfe.cn/Article/details/gtjgdsrsyg.html

print("err", file=sys.stderr)
来源：http://dali.tanke756.top/Article/details/gtaaoowzof.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtjcxrukor.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtfqjbrlsh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtmfhojvsj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aibaodan.cn/Article/details/gtfftojini.html

[U43] PHP：声明命名空间
来源：http://dali.shangyingyoupin.top/Article/details/gtvvdyjpfc.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtarwvcmjs.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gtihodqttm.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gtnmtrantq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gtpvllhypw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtvyfzkbty.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtkugatsoy.html

?string $name = null
来源：http://dali.9152youxi.cn/Article/details/gtwwigxvwp.html

[U47] PHP：联合类型
来源：http://dali.quarkkingdee.top/Article/details/gtimzydtzb.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gtxnyuecbg.html

[U48] PHP：纯枚举
来源：http://dali.ivvv.top/Article/details/gtywxzbtwe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.redwolf501.top/Article/details/gtemllcrtd.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gtisogvakb.html

public readonly string $name
来源：http://dali.sufxvd.cn/Article/details/gtigqfzvxk.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gtaekebchx.html

public function __construct(private int $id) {}
来源：http://dali.zhixingplan.top/Article/details/gtrqofznbc.html

[U51] PHP：数组解构
来源：http://dali.yongpay.top/Article/details/gtovkvmhcm.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gtamljccvv.html

[U52] PHP：箭头函数
来源：http://dali.sweek.top/Article/details/gtewlpixer.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqguvxdv.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gtklljacsz.html

$v = $a ?? $b ?? "default";
来源：http://dali.chenlongwang.top/Article/details/gtzccqvtdv.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gtrbavnyiv.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtzjrggdln.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtuemovxva.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtxbhbvrmb.html

[U56] PHP：命名参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtamuvinhm.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvudgasmv.html

[U57] PHP：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtsnzlouik.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtstkouagn.html

[U58] PHP：数组三件套
来源：http://dali.zhiwuduotai.top/Article/details/gtjufgnpvo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dianchejie.cn/Article/details/gtpzkihran.html

[U59] PHP：自定义排序
来源：http://dali.guannengcc.top/Article/details/gtpzyupacm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtqpedppbi.html

[U60] PHP：JSON 编解码
来源：http://dali.fzhhl.top/Article/details/gtrcbqwtke.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gthwwimtda.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gtrvwyswuf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tianlin.xyz/Article/details/gtufdznpys.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gttpogythu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gzhubu.top/Article/details/gtkgsbuwvh.html

[U63] PHP：文件读写
来源：http://dali.shangyingyoupin.top/Article/details/gttqerxyai.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gtuxejijbj.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtzowazzyx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hysaishi.cn/Article/details/gtaxxpirxf.html

[U65] PHP：会话
来源：http://dali.wangshuangyany.cn/Article/details/gtfmazxxva.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtwjrktecp.html

[U66] PHP：设置 Cookie
来源：http://dali.xylfe.cn/Article/details/gtulzbyshe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dashuyun.cn/Article/details/gtuvbantoq.html

[U67] PHP：处理文件上传
来源：http://dali.haohaochexian.top/Article/details/gtwvmbmtez.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtxmswgqqu.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gthbvwbvmu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtopwfbpjd.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtkruezoqd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtedxndgyo.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gtluaxpjqk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtcuuubunq.html

[U71] PHP：抛出异常
来源：http://dali.yangfankeji.com/Article/details/gtjhcjgfqj.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gtuulqitid.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtpcrnoimm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gtsqyqftql.html

[U73] PHP：读取 ini 配置
来源：http://dali.hnxiangtu.top/Article/details/gtvgajmxgi.html

parse_ini_file("config.ini", true)
来源：http://dali.xuetiantiany.cn/Article/details/gtxgnpoxzj.html

[U74] PHP：读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtkoggxsyu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gtzsnmmixj.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gtepwopmtm.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtfentorga.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gtcksqnrwo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tian-w.cn/Article/details/gtexheytdz.html

[U77] PHP：模板渲染
来源：http://dali.316326.xyz/Article/details/gtafvnlxjt.html

composer require twig/twig
来源：http://dali.aizwys.cn/Article/details/gtlkpwyaqx.html

[U78] PHP：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtrceudhvq.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gtchlvpeye.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gterwqwsuu.html

composer require --dev phpstan/phpstan
来源：http://dali.mhx1999.top/Article/details/gtwvnqfcus.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gtnzftnmwa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jlsjyb.cn/Article/details/gtdbyyrkmo.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gtxrdmtujt.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gtinbjnkzj.html

[U82] JS：package.json 脚本
来源：http://dali.hywenlv.cn/Article/details/gtmktdjsmi.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gtcxjxhchb.html

[U83] JS：ES Module 导入导出
来源：http://dali.hfpthk.cn/Article/details/gtkbvghnaa.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ppjwa.cn/Article/details/gtlqokemgi.html

[U84] JS：CommonJS 写法
来源：http://dali.redwolf501.top/Article/details/gtfixivbyz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zdqjudy.top/Article/details/gtymemqwqf.html

[U85] JS：可选链
来源：http://dali.nanxinkj.top/Article/details/gtjaejjqmu.html

a?.b?.c
来源：http://dali.kuanghao11.cn/Article/details/gtmsbtjkli.html

[U86] JS：空值合并
来源：http://dali.daria6918.cn/Article/details/gtnzgxidza.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gtmnoixese.html

[U87] JS：解构默认值
来源：http://dali.hnxiangtu.top/Article/details/gtsioeqekc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.nanxuanxn.top/Article/details/gtnxvcazyf.html

[U88] JS：对象展开合并
来源：http://dali.yangfankeji.com/Article/details/gtwuppuuhb.html

{ ...a, ...b }
来源：http://dali.xylfe.cn/Article/details/gtneqadfaf.html

[U89] JS：数组去重
来源：http://dali.hammf.cn/Article/details/gtwwfjeulo.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gtmxiethbw.html

[U90] JS：数字数组排序
来源：http://dali.zhijiandao.cn/Article/details/gtaodpfuie.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yongpay.top/Article/details/gttfbwfswp.html


<!-- 参考信息 -->