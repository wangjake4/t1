代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gt2tzdkzwgx.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2jtjmrnix.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gt2wnkgvtlg.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gt2hctsxcce.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gt2bkelupnu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gt2hceikzma.html

[T06] Kotlin：集合映射
来源：http://dali.ydzc1.top/Article/details/gt2kwsqaqai.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2dvkwngbf.html

[T07] Kotlin：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2lgblwbcf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tlwrjswp.html

[T08] Kotlin：数据类
来源：http://dali.nanxinkj.top/Article/details/gt2zvmeodez.html

data class User(val name: String, val age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2bwymekeo.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gt2atxeynyr.html

fun String.exclaim() = this + "!"
来源：http://dali.xinyue.icu/Article/details/gt2clcrguxs.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2lngicmki.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuanzx.com/Article/details/gt2zfxbwqal.html

[T11] Kotlin：协程
来源：http://dali.xziqi.cn/Article/details/gt2ekzfsfwa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gt2hfallwsa.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gt2vdurzqte.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gt2opdinpui.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gt2fkqiqcjq.html

val m = mapOf("a" to 1)
来源：http://dali.chenjidiqi.icu/Article/details/gt2jwfquicu.html

[T14] Kotlin：循环
来源：http://dali.sufxvd.cn/Article/details/gt2asmkwduw.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2kpaslbah.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gt2yjhtflfp.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2rjmsqhaq.html

[T16] Swift：Hello World
来源：http://dali.gogol.net.cn/Article/details/gt2awfukrba.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gt2tjkgokqi.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gt2jhizvuvc.html

var a = 1;  let b = 2
来源：http://dali.yongpay.top/Article/details/gt2zazucrab.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2yaqsrtsi.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gt2oivmgeej.html

[T19] Swift：可选绑定
来源：http://dali.chenjidiqi.icu/Article/details/gt2xydcolbu.html

if let n = opt { print(n) }
来源：http://dali.yongpay.top/Article/details/gt2jecbyxto.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gt2jguqhila.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkuvqhjk.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gt2ikirfdfk.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gt2omuurndf.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gt2zaakqrsb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhoulong.xyz/Article/details/gt2mplzdtmt.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gt2uopquewm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gt2tpfdreud.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2pklfsbub.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2tlbjcjqk.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gt2bkhjsezy.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gt2mzgxjqga.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2vceymxty.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gt2ucubpons.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wepmvgek.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wfdbbwoq.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gt2jxzxahuu.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gt2ryrlemkp.html

[T29] Swift：guard 提前返回
来源：http://dali.hammf.cn/Article/details/gt2vdddmgyh.html

guard let x = opt else { return }
来源：http://dali.aizwys.cn/Article/details/gt2mbaynjzu.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gt2eyfwtkgo.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gt2cawveomc.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gt2odgaqfei.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gt2gquonlly.html

[T32] Lua：局部变量
来源：http://dali.c1oappe.top/Article/details/gt2kpdqjcol.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gt2cptwiryp.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2dxeihbbg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zycfv.cn/Article/details/gt2bhmseudd.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gt2mjdorxuy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2yuktavro.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqglnlea.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gt2zsktnzdy.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2rksrobya.html

function add(a, b) return a + b end
来源：http://dali.316326.xyz/Article/details/gt2dinlzbnq.html

[T37] Lua：字符串拼接
来源：http://dali.tanke756.top/Article/details/gt2rqhmxxti.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2nmtnswur.html

[T38] Lua：条件
来源：http://dali.fzhhl.top/Article/details/gt2zhkfzhij.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gt2gomdhzfy.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2esikbgyz.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gt2enlolmmh.html

[T40] Lua：元表
来源：http://dali.zhoulong.xyz/Article/details/gt2oxoumnyd.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gt2jhbjobqu.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2rngneulr.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ozsbgckg.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gt2ywporamx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gt2hcfthmqi.html

[T43] Perl：字符串插值
来源：http://dali.smart0.xyz/Article/details/gt2jjkqregg.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2ljnbdkic.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2ovwkwvjo.html

if ($a > 0) { print "正"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2srxpicie.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gt2bdtjliqp.html

for my $x (@arr) { print $x; }
来源：http://dali.yuxming.cn/Article/details/gt2ixssyulu.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gt2lomppeit.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gt2lunkyuiq.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gt2njdgmhlt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2tsqaihxg.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gt2gqzqjfxv.html

$s =~ s/old/new/g;
来源：http://dali.jianghu66.top/Article/details/gt2vbzcmugo.html

[T49] Perl：函数
来源：http://dali.tianlin.xyz/Article/details/gt2wlkrsvpx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2iondgsiq.html

[T50] Perl：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gt2rsyoeyvk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gt2jlovlati.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2obankjmc.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2jffsmzhq.html

println("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmaxqsst.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gt2rdncqrlr.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2asgppwtf.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2qzrqjitk.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gt2dqishhnv.html

[T54] Scala：集合映射
来源：http://dali.sweek.top/Article/details/gt2aunmsdio.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yj20258888.top/Article/details/gt2yymqfgbw.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2cbhezlxo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gt2whjuueck.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gt2bnoknbcz.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2bnjszuck.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gt2xvdpeddf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2pulmkdse.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gt2vbbbneaw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tttwxpld.html

[T59] Scala：循环
来源：http://dali.xuanzx.com/Article/details/gt2hcnxvfiv.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gt2ogzlvbtu.html

[T60] Scala：折叠
来源：http://dali.tian-w.cn/Article/details/gt2qybdaeuu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gt2incjrhnw.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2xxdywxhs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gt2kndjwbcb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2rqichtvz.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2hcychkss.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj202588.top/Article/details/gt2impdqwnl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gt2ygybdull.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqvvtjuh.html

[U03] Py：加载 .env 配置
来源：http://dali.yonumen.top/Article/details/gt2ztlodteh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gt2wdjcgxny.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gt2iaomtpth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gt2xczjaqcv.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gt2lkpjrhss.html

list(dict.fromkeys(arr))
来源：http://dali.daxiang520.top/Article/details/gt2xawkhlot.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gt2fpydqrfw.html

{**a, **b}
来源：http://dali.bjfxy.top/Article/details/gt2oxcutlsp.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gt2clfudvcy.html

{v: k for k, v in d.items()}
来源：http://dali.zhijiandao.cn/Article/details/gt2dekumuep.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2ejgzjsrs.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gt2ooxvdpzr.html

[U09] Py：字典取最大值的键
来源：http://dali.yongpay.top/Article/details/gt2tnxgyaas.html

max(d, key=d.get)
来源：http://dali.tanke756.top/Article/details/gt2neadrqhj.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gt2lneziuhx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.iojbl.cn/Article/details/gt2gtyumdjg.html

[U11] Py：生成器表达式
来源：http://dali.snrcjt.cn/Article/details/gt2fpstomvx.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gt2dvtnwiyd.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.316326.xyz/Article/details/gt2lzizehpi.html

Counter(arr).most_common(3)
来源：http://dali.snrcjt.cn/Article/details/gt2epbndfmr.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdugnxvl.html

deque(maxlen=10)
来源：http://dali.sufxvd.cn/Article/details/gt2nvvkvhnj.html

[U14] Py：分组收集到列表
来源：http://dali.ivvv.top/Article/details/gt2tkkpyxtp.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gt2vscddkdq.html

[U15] Py：高精度计时
来源：http://dali.c1oappe.top/Article/details/gt2yjhyryrm.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2scxbavda.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2cgcuqprs.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gt2pwsxonrz.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gt2qdpmvpdx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zrwadpyc.html

[U18] Py：预编译正则
来源：http://dali.nanxuanxn.top/Article/details/gt2pzmgwnmt.html

pat = re.compile(r"\d+")
来源：http://dali.yuanzhike.top/Article/details/gt2tfbbwrce.html

[U19] Py：正则替换带回调
来源：http://dali.0kj1m.cn/Article/details/gt2slyoghzd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hammf.cn/Article/details/gt2manpfauj.html

[U20] Py：缓存函数结果
来源：http://dali.shangyingyoupin.top/Article/details/gt2acdsnjbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkwdunzs.html

[U21] Py：自定义上下文管理器
来源：http://dali.yueranfly.top/Article/details/gt2xqvtnpvt.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gt2itowdbif.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gt2grpzpywd.html

list(zip(*m))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zhtwzziv.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2imzcbnmg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tianlin.xyz/Article/details/gt2iirqkkqb.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gt2eluxclwg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tanke756.top/Article/details/gt2rkcenqzs.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gt2yxiqlumm.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gt2vdiycunk.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2pcqgmrfm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gt2abfonfep.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gt2drkdzpeq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ppjwa.cn/Article/details/gt2zwnmsgnm.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gt2qzzpmyvc.html

UserId = int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2afnigpnl.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gt2lsciayum.html

@property 与 @x.setter 配合
来源：http://dali.yj20258888.top/Article/details/gt2slurqwyg.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gt2mzkefehh.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2etsizlxi.html

[U31] Py：单测
来源：http://dali.0kj1m.cn/Article/details/gt2eltvsbef.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ftstptiz.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gt2qlokadpx.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gt2ofahnbln.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gt2iwxijubs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gt2ulcmejtv.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gt2jdxmvzqd.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gt2nkrvtdhs.html

[U35] Py：发送邮件
来源：http://dali.zhijiandao.cn/Article/details/gt2syerlbgr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sufxvd.cn/Article/details/gt2itvvgaso.html

[U36] Py：定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cxaewikt.html

schedule.every(10).minutes.do(job)
来源：http://dali.pengpengdd.cyou/Article/details/gt2zevjpgda.html

[U37] Py：读写 Excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bocuvzkd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2beusnjum.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gt2nafnlmcm.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ejphhifl.html

[U39] Py：判断是否在交互环境
来源：http://dali.gogol.net.cn/Article/details/gt2dplzhpcd.html

sys.stdout.isatty()
来源：http://dali.sufxvd.cn/Article/details/gt2optzbpiw.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2aycgmkza.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gt2httglorp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gt2nmdzsnsf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gt2nijyxozz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gt2ejkspqlm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ubppevyl.html

[U43] PHP：声明命名空间
来源：http://dali.gotoacloud.top/Article/details/gt2bokcoeep.html

namespace App\Http;
来源：http://dali.zycfv.cn/Article/details/gt2qzbppfkb.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tzhxcjrb.html

declare(strict_types=1);
来源：http://dali.xuetiantiany.cn/Article/details/gt2dgvwucxt.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ehwqpu.com/Article/details/gt2mdxzrksy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2dwsflfsc.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gt2msxxnuae.html

?string $name = null
来源：http://dali.xziqi.cn/Article/details/gt2dpdncrni.html

[U47] PHP：联合类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgcgcckg.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gt2xbselkmw.html

[U48] PHP：纯枚举
来源：http://dali.dianchejie.cn/Article/details/gt2agzutvbj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gt2gsiwvhlk.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gt2glzswfxv.html

public readonly string $name
来源：http://dali.ydzc1.top/Article/details/gt2bbajbxmq.html

[U50] PHP：构造器属性提升
来源：http://dali.sweek.top/Article/details/gt2erkbnrzc.html

public function __construct(private int $id) {}
来源：http://dali.fzhhl.top/Article/details/gt2xsvpfelb.html

[U51] PHP：数组解构
来源：http://dali.vqdsnc.cn/Article/details/gt2xdesljir.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gt2swamorzt.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gt2zbcktuha.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gt2usqbfkuy.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gt2zqqgaaff.html

$v = $a ?? $b ?? "default";
来源：http://dali.birdmap.top/Article/details/gt2kpekmwvl.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gt2kvamzjjz.html

$obj?->method()
来源：http://dali.yongpay.top/Article/details/gt2qnyoroyb.html

[U55] PHP：match 表达式
来源：http://dali.havefunace.top/Article/details/gt2mypknbwx.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gt2wwcvmpqw.html

[U56] PHP：命名参数
来源：http://dali.havefunace.top/Article/details/gt2myibhefv.html

f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lhmanyrc.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gt2aynjboxf.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2edblifrk.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gt2jvmmrlxs.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gt2lkmsxrje.html

[U59] PHP：自定义排序
来源：http://dali.gotoacloud.top/Article/details/gt2smzmcprn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.9152youxi.cn/Article/details/gt2hosiwwts.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gt2fmfleyaa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gt2bbouxsak.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gt2ourztekp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gt2ofnamonc.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gt2jcpotsak.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gt2mfpaqdhw.html

[U63] PHP：文件读写
来源：http://dali.chenlongwang.top/Article/details/gt2lcyjgbnj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.quarkkingdee.top/Article/details/gt2rguydlsj.html

[U64] PHP：目录遍历
来源：http://dali.haohaochexian.top/Article/details/gt2rkclrooz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gt2jxadzgxo.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gt2ofmwohtn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gt2qyuxalkd.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xxxildgn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gt2oqjyzhdf.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gt2jpqidssy.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.c1oappe.top/Article/details/gt2vknixktf.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gt2jppcxudc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gogol.net.cn/Article/details/gt2xhquqbih.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gt2syvbbxbk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gt2hxaukqcw.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gt2lmwcbbsy.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gt2ufiqnver.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gt2bjutrrlw.html

throw new RuntimeException("失败", 500);
来源：http://dali.xinyue.icu/Article/details/gt2aqfyxoup.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gt2cqyrwhjh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gt2tqkfgady.html

[U73] PHP：读取 ini 配置
来源：http://dali.9152youxi.cn/Article/details/gt2bxmngrjm.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gt2pzpzbmkp.html

[U74] PHP：读取环境变量
来源：http://dali.ivvv.top/Article/details/gt2bsdmueaj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.smart0.xyz/Article/details/gt2gtuyegqg.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gt2izvlsiqa.html

composer require psr/container
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyfzcejd.html

[U76] PHP：简单路由
来源：http://dali.pengpengdd.cyou/Article/details/gt2uwjuytwl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuanzhike.top/Article/details/gt2hwmqiral.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gt2guovgncv.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gt2gvrzjbts.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gt2euwkkdoo.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gt2ccuokhyd.html

[U79] PHP：静态分析
来源：http://dali.0kj1m.cn/Article/details/gt2myxfcrcf.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gt2pzukzmqh.html

[U80] PHP：代码规范修复
来源：http://dali.yuxming.cn/Article/details/gt2wmiiqcqy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gt2rgsjsnkk.html

[U81] JS：初始化项目
来源：http://dali.pycfn.com/Article/details/gt2avtnspmk.html

npm init -y;  npm i express
来源：http://dali.gzhubu.top/Article/details/gt2wpqtbwoh.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gt2qkxixity.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.birdmap.top/Article/details/gt2aoyowzsh.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gt2ytbinuit.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.bjfxy.top/Article/details/gt2vrkjmuqe.html

[U84] JS：CommonJS 写法
来源：http://dali.aibaodan.cn/Article/details/gt2snjaeego.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnxiangtu.top/Article/details/gt2yedriogl.html

[U85] JS：可选链
来源：http://dali.yj20258.top/Article/details/gt2xezbjxqm.html

a?.b?.c
来源：http://dali.daria6918.cn/Article/details/gt2nhtqsxeh.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gt2cymdkefs.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gt2vyudwydn.html

[U87] JS：解构默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zvkudoic.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gt2srujbttc.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gt2lwupbhdn.html

{ ...a, ...b }
来源：http://dali.yongpay.top/Article/details/gt2ypbmmsfq.html

[U89] JS：数组去重
来源：http://dali.nanxuanxn.top/Article/details/gt2ylvmgavi.html

[...new Set(arr)]
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhgnkvoi.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gt2tvrjbgvs.html

[...arr].sort((a, b) => a - b)
来源：http://dali.fengsongda.top/Article/details/gt2qqeudbwo.html


<!-- 参考信息 -->