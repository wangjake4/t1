代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtebwmhsmi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtfyjnicte.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtmifnvzpu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtqqxvcivt.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtykssca.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhoulong.xyz/Article/details/gtareidjqt.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtaimnyzxm.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtmyukuzoi.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtvspodusl.html

fun String.exclaim() = this + "!"
来源：http://dali.jianghu66.top/Article/details/gtgzjaipyb.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtqqisuvsn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtbrbkxing.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtqmqloesa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtwydzxmdn.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzqjsffr.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrhsufqp.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtcgrdvwsd.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtbdukhxov.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gthiwvtgop.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtdtwafwfu.html

[T15] Kotlin：接口
来源：http://dali.aizwys.cn/Article/details/gtzwooayva.html

interface Shape { fun area(): Double }
来源：http://dali.yueranfly.top/Article/details/gttnygsasz.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtirfsjegx.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gthczxsghu.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gtptcoqkwu.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtlmeheniv.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtydxpqete.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtemilscad.html

[T19] Swift：可选绑定
来源：http://dali.zhongyouzk.top/Article/details/gtwhxzziuo.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtupcwnise.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtrdwkydkm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtwvpppifw.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gtvpdlgbnj.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gtdfucxzcr.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gthmqdxclz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtfroklzzi.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcrbhyotc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtlnghpcyf.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtzdrmeqgk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtyvlhpajn.html

[T25] Swift：结构体
来源：http://dali.shangyingyoupin.top/Article/details/gttksivbnf.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gtkebitoik.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtafmcsjab.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtvnavangk.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtxwpznjuy.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibvxtjcx.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtxpolwzjt.html

enum Color { case red, green }
来源：http://dali.fengsongda.top/Article/details/gtxzaocypt.html

[T29] Swift：guard 提前返回
来源：http://dali.gzhubu.top/Article/details/gtidpnpsxe.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtvdpwkxfs.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtfyrggzjv.html

protocol Shape { func area() -> Double }
来源：http://dali.cdnleiting.top/Article/details/gtjmllemfg.html

[T31] Lua：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtxkakoblq.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtimnuzapf.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtieqhwovk.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gtpkhbcfdu.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtnhrxabck.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gtmphnqxjt.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gthgnhjucl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtzemfpaxn.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtsbofjuwg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtjdjeluyc.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gtjrtueseg.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtumtkhpiv.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258888.top/Article/details/gtkxxqebyx.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtwvpmqkso.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtkiuwktvb.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtadjymysh.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtookgrwjw.html

string.find(s, "%d+")
来源：http://dali.daria6918.cn/Article/details/gtgmslxtbd.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtwoxgyfuq.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gtrtfxvngd.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gteaokyapv.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtctibbimj.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtqkvudart.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmnwnrjs.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtfossgkdr.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtvgyjqwtd.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtpxgwjccu.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtmaybcgqp.html

[T45] Perl：数组遍历
来源：http://dali.jianghu66.top/Article/details/gtjcktclxf.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gtoiofpxdy.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtnpiufrid.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gtinfvjiip.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtgfnbzrql.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtvuorddxe.html

[T48] Perl：正则替换
来源：http://dali.nwbrower.top/Article/details/gtxqadfnxg.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtcuflngui.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gtiecmobtd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttaipzjro.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtddfwwgcc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtiyqymvgx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yj202588.top/Article/details/gteanreeiv.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtbxebjocn.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtvukogklh.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtwmjselzm.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtcpcmjdch.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtzbcqkvfv.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtexkrlzvr.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtuzxbjscb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtwrtifzpl.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtwndkscsb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtajzumgew.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtvzcbdjmr.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtegjwetfz.html

[T57] Scala：模式匹配
来源：http://dali.tianlin.xyz/Article/details/gtnpajjbpu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhzydqix.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtrfgkijxw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtgyyfanhp.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtizigfrxa.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtlnnrlzpk.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtxurggkew.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.snrcjt.cn/Article/details/gtucpzyted.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtxtgihvsa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtcqmljrih.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtjdwivsai.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtwutgvqbe.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuxming.cn/Article/details/gtyrsuaypt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtevmbtgqn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdjqhsra.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtrkornswe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yvedp.cn/Article/details/gtphqqxszg.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtkdvjfqml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtbufejrmq.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtxfljkqvm.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtauadalnr.html

[U06] Py：合并两个字典
来源：http://dali.jinqigfzy.top/Article/details/gtihffxtrp.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtexrgqlfj.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtzbtrolic.html

{v: k for k, v in d.items()}
来源：http://dali.chenlongwang.top/Article/details/gtjhcyewem.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtombhxwba.html

[y for x in nested for y in x]
来源：http://dali.sufxvd.cn/Article/details/gtbkhouuaa.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigufen.top/Article/details/gtzxfvfqco.html

max(d, key=d.get)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfdhbfxkk.html

[U10] Py：按值排序字典
来源：http://dali.shuidangran.top/Article/details/gtihxssxtn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtujbirkoc.html

[U11] Py：生成器表达式
来源：http://dali.andypj.xyz/Article/details/gthdlsupyc.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtkpgvzilj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgfzy.top/Article/details/gtqumvyzyc.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gtgjulktyd.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gttdjtrrzu.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtgsrduhiz.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gtkuplkqac.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtkspqcmqx.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gtfhqrziac.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gtmbgaovyy.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtfpagtqmf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jinqigfzy.top/Article/details/gtrelkehbh.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gtfqdqiqcd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiyeixjtl.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtdcymekjo.html

pat = re.compile(r"\d+")
来源：http://dali.aizwys.cn/Article/details/gtteiweyoq.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gtdqaszcbk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenjidiqi.icu/Article/details/gtrwjjduap.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gtxxdekmem.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gtjwubkcuj.html

[U21] Py：自定义上下文管理器
来源：http://dali.svipenyu.cn/Article/details/gtlkcptbtt.html

@contextlib.contextmanager
来源：http://dali.aibaodan.cn/Article/details/gttgieckpl.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmczadgmv.html

list(zip(*m))
来源：http://dali.feifeiyinyue.top/Article/details/gtgdkuzncb.html

[U23] Py：分块读取大文件
来源：http://dali.fengsongda.top/Article/details/gtmysdjzlu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gtnmnggusg.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtwtyhexyv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinqigfzy.top/Article/details/gtblxjcebn.html

[U25] Py：CSV 按字典读
来源：http://dali.wangshuangyany.cn/Article/details/gtfuvyzbtj.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gtrgihmzde.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtnyfllbqd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtgszyeapg.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtidoibdxx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cashguo.top/Article/details/gtfzlwtlqs.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gtcwoqexed.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtqbkftrww.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gtliaiikip.html

@property 与 @x.setter 配合
来源：http://dali.hammf.cn/Article/details/gtnmqbbdcq.html

[U30] Py：数据类
来源：http://dali.pengpengdd.cyou/Article/details/gtohzpliuu.html

@dataclass(slots=True)
来源：http://dali.bjfxy.top/Article/details/gtzfuxittk.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gtervhpqlg.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgvxsxupz.html

[U32] Py：代码格式化
来源：http://dali.9152youxi.cn/Article/details/gtyiyfemzw.html

ruff format . && ruff check --fix .
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssigcvhg.html

[U33] Py：打包发布
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcdbkmgk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtpliiaqpn.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtlnuovgup.html

chardet.detect(raw)
来源：http://dali.smart0.xyz/Article/details/gtciydxlzs.html

[U35] Py：发送邮件
来源：http://dali.xinyue.icu/Article/details/gtdwaybkbw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gtdrkdjwrc.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gtojabmbzy.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtbceutcdg.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtprowpitm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbsbswivz.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtujvwklvq.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gtmhelngpf.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtjkfmpahe.html

sys.stdout.isatty()
来源：http://dali.haohaochexian.top/Article/details/gtbykuzeqa.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gtihwnvwpw.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gturclxyeu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.316326.xyz/Article/details/gtmixbagtx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gtigvfxufq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gtnqmfndmf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtvomssrml.html

[U43] PHP：声明命名空间
来源：http://dali.yueranfly.top/Article/details/gtebmwwbmu.html

namespace App\Http;
来源：http://dali.jqgfzy.top/Article/details/gtwspwfnix.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gtprpxakgw.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gtnjqzlyzn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gtqkybhbcv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtjqoksuac.html

[U46] PHP：可空类型
来源：http://dali.haohaochexian.top/Article/details/gtgjxlxlwx.html

?string $name = null
来源：http://dali.gzhubu.top/Article/details/gtudyjlvti.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gthrymrfud.html

int|string $id
来源：http://dali.mhx1999.top/Article/details/gtnfcirhog.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtjunqehkk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.0kj1m.cn/Article/details/gtlfpclfvl.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtysnaomeo.html

public readonly string $name
来源：http://dali.nwbrower.top/Article/details/gtenpjotrx.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdekteqzp.html

public function __construct(private int $id) {}
来源：http://dali.yanxiufei.cn/Article/details/gtzdcyutds.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gtovvtpswl.html

[$a, $b] = $arr;
来源：http://dali.tian-w.cn/Article/details/gtzybxrlpq.html

[U52] PHP：箭头函数
来源：http://dali.meibo888.top/Article/details/gtbwpgmxrz.html

$double = fn($x) => $x * 2;
来源：http://dali.pengpengdd.cyou/Article/details/gtvzsreuac.html

[U53] PHP：空合并运算符
来源：http://dali.cdnleiting.top/Article/details/gtmlschjtd.html

$v = $a ?? $b ?? "default";
来源：http://dali.cashguo.top/Article/details/gtcoijdfwf.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gtjsmjtsmw.html

$obj?->method()
来源：http://dali.fengsongda.top/Article/details/gtdoumnqzb.html

[U55] PHP：match 表达式
来源：http://dali.hnqzz.top/Article/details/gtlpytmrob.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gtlgzsesow.html

[U56] PHP：命名参数
来源：http://dali.zdqjudy.top/Article/details/gtfjszckcc.html

f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtznpmcxyf.html

[U57] PHP：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtqunrtopl.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gterdduyhe.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gtwpwsqyrq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtftzbiixw.html

[U59] PHP：自定义排序
来源：http://dali.chenjidiqi.icu/Article/details/gtccuyvqkm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtkpjrrvov.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtvmaxakxo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xuanzx.com/Article/details/gtpwlxoutd.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gtbkjyzwra.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtprnhnnig.html

[U62] PHP：日期对象
来源：http://dali.iojbl.cn/Article/details/gtjaxqjpss.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.0kj1m.cn/Article/details/gtkwjdjcym.html

[U63] PHP：文件读写
来源：http://dali.cashguo.top/Article/details/gtvtzoxgdp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.chenzaomai.com/Article/details/gtxonwretf.html

[U64] PHP：目录遍历
来源：http://dali.yonumen.top/Article/details/gtxqnauyhp.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gtvcaznbtu.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtpnmpidwl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdboniqd.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtxhvqzyxo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cashguo.top/Article/details/gttdvpplfi.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gtfrwzjsyx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtktnbjgls.html

[U68] PHP：PDO 连接
来源：http://dali.yj20258888.top/Article/details/gtxzowduov.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.9152youxi.cn/Article/details/gthsfwmaiv.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtryvhibjq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtftkoskps.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtunjzwprq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtxyilyqyo.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtolgtlxds.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gtrcnolubg.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gtelrjvawf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtrzorlrog.html

[U73] PHP：读取 ini 配置
来源：http://dali.ppjwa.cn/Article/details/gtnbdnxjre.html

parse_ini_file("config.ini", true)
来源：http://dali.ydzc1.top/Article/details/gtdqmpugbg.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gtvrbdacuj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjwmbralw.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gtzmhtkyqf.html

composer require psr/container
来源：http://dali.ehwqpu.com/Article/details/gtifjhvoyp.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gthrtbsxpc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.guowangkeji.top/Article/details/gtreuqzjog.html

[U77] PHP：模板渲染
来源：http://dali.shangyingyoupin.top/Article/details/gttedsyoir.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtknclftyh.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtdbhtxrzf.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gttpgcgafe.html

[U79] PHP：静态分析
来源：http://dali.dianchejie.cn/Article/details/gtybtsyxmx.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtoclzevkz.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtcwlclpas.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenzaomai.com/Article/details/gtmdojmfme.html

[U81] JS：初始化项目
来源：http://dali.9152youxi.cn/Article/details/gtrovpxdbo.html

npm init -y;  npm i express
来源：http://dali.dianchejie.cn/Article/details/gtdzfnppxk.html

[U82] JS：package.json 脚本
来源：http://dali.zhoulong.xyz/Article/details/gtelyeyyms.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfqekefg.html

[U83] JS：ES Module 导入导出
来源：http://dali.yueranfly.top/Article/details/gtpeonxcyk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtccglsgbq.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtynzzhjvp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtwcpcbgkt.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gtzoftjrim.html

a?.b?.c
来源：http://dali.zhijiandao.cn/Article/details/gtspbekkfy.html

[U86] JS：空值合并
来源：http://dali.jqgufenzy.top/Article/details/gtedxdqrpu.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtrqdnmvvc.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtzwbagsum.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gtnbudsxis.html

[U88] JS：对象展开合并
来源：http://dali.cashguo.top/Article/details/gtqwujcwbd.html

{ ...a, ...b }
来源：http://dali.fengsongda.top/Article/details/gtgszqwsdy.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gtwqsblyol.html

[...new Set(arr)]
来源：http://dali.316326.xyz/Article/details/gtxongujoj.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtiylhxxvu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fzhhl.top/Article/details/gtlaqvygbx.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gtqijmentf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shuidangran.top/Article/details/gtacxctyce.html

[U92] JS：深拷贝
来源：http://dali.andypj.xyz/Article/details/gtjepfbdni.html

structuredClone(obj)
来源：http://dali.smart0.xyz/Article/details/gtashstyqz.html


<!-- 参考信息 -->