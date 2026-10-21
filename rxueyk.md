代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjiukzuml.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtjqnwefag.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtsbhgshjs.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtpkcmfcur.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtxukoworz.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtxakdpvmv.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtlcgclgde.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtuspsmkmh.html

[T05] Kotlin：when 表达式
来源：http://dali.hammf.cn/Article/details/gtenxqlzot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gtyezbbvtg.html

[T06] Kotlin：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gthblmpsmn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtawezzbdx.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gttndnefqj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtjoeceznz.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtjsagunzo.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtlfggkqqk.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtcuptmllx.html

fun String.exclaim() = this + "!"
来源：http://dali.yangfankeji.com/Article/details/gtjagrgexm.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtaevtvvyo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtyjjfipez.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtrsxuihsn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttrtzazb.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtbvucezny.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtkwiaslyj.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtxvgrfdsk.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtxifwcpin.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtokmbadox.html

for (i in 1..10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gttflgjjjg.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtlsbuttxl.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigfzy.top/Article/details/gtiawuawjg.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtgjgclwqp.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtdoweomvo.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gtbgpmeymb.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtpcqyivaf.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtyjwiucpz.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtndamxlpk.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtgunevzkm.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gtyjmzavge.html

[T20] Swift：数组操作
来源：http://dali.cdnleiting.top/Article/details/gtvyxjzpuk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenzaomai.com/Article/details/gtgrmuvooi.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gttohkllle.html

for x in a { print(x) }
来源：http://dali.yj20258.top/Article/details/gtzfixyfta.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtdqvcaxuq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtlczllebg.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtgkrhtnsa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtweybfess.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gtojbwwcit.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtjownbtua.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtzsuceyby.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtrxhczyke.html

[T26] Swift：类与重写
来源：http://dali.jinqigufen.top/Article/details/gthlwvdwbd.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtbasdksni.html

[T27] Swift：错误处理
来源：http://dali.ehwqpu.com/Article/details/gtupdseyui.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtesyldgzu.html

[T28] Swift：枚举
来源：http://dali.chenzaomai.com/Article/details/gtctdtruvt.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtdmmezsku.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gtuxmiuzvm.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtgsdpaitq.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtenxmxoae.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gteueywdpk.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtpkwyomop.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtkithyqis.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gtphituyku.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtbgvmygmn.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtrvsbivrm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtdqcbmwms.html

[T34] Lua：遍历表
来源：http://dali.sysykeji.top/Article/details/gtrwrcedpd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shzxlz.cn/Article/details/gtnynfhbam.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtbnkchmuc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtibehxkex.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gtcwhgluck.html

function add(a, b) return a + b end
来源：http://dali.zhijiandao.cn/Article/details/gtzxpdawqu.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtrnejeora.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gthwbbpezv.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtughgdkpd.html

if x > 0 then print("正") end
来源：http://dali.svipenyu.cn/Article/details/gtdzvoyeuw.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwtqhbui.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtrebnclzy.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gttlvzocfl.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtkgerokgn.html

[T41] Perl：Hello World
来源：http://dali.birdmap.top/Article/details/gtqhmjgjcl.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtpnesppbd.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gtzaturohz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hysaishi.cn/Article/details/gtwbkmkazq.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtlfmlvmeq.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gtqeedobii.html

[T44] Perl：条件
来源：http://dali.yj202588.top/Article/details/gtiysscmql.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtcrmhamkl.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtdwhzymjs.html

for my $x (@arr) { print $x; }
来源：http://dali.yangfankeji.com/Article/details/gtmcrqupmt.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtuskohlij.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gtksltjure.html

[T47] Perl：正则捕获
来源：http://dali.yj20258888.top/Article/details/gtipydapuu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenzaomai.com/Article/details/gtvnapyiyi.html

[T48] Perl：正则替换
来源：http://dali.svipenyu.cn/Article/details/gtisljfzin.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtuedxsxyy.html

[T49] Perl：函数
来源：http://dali.cashguo.top/Article/details/gtxdzekhjy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtptmkznps.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtvqtuupkq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gtwciyzvdq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigufen.top/Article/details/gtustzzczv.html

[T51] Scala：Hello World
来源：http://dali.c1oappe.top/Article/details/gtmhtnhnyz.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtenmdzoyj.html

[T52] Scala：变量
来源：http://dali.zycfv.cn/Article/details/gtxsuxclum.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gteazipilx.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtbhvdivnb.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gtmrmeakcx.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtxybhkcec.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gtfyfmhxpa.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtnotaemxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtdpfhatnf.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gtzgudjpfm.html

case class User(name: String, age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtawfqbydy.html

[T57] Scala：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtrgasokxp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtkdxlpjuc.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtmisuggam.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtlmyavkhh.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtecgthger.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gtnyvaipwm.html

[T60] Scala：折叠
来源：http://dali.zhijiandao.cn/Article/details/gtsovljdlf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtxfojzuca.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtftwwsxbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtvamsgesf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtxetbzplq.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gtfgkyhizp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtlrvjougj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtiougozmw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guannengcc.top/Article/details/gtzvbwyhme.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtwndlsdbx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtxzlchylg.html

[U04] Py：变量调试打印
来源：http://dali.hammf.cn/Article/details/gtorpkrngk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwbcevlu.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtbqnmutnv.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtsdfljkir.html

[U06] Py：合并两个字典
来源：http://dali.9152youxi.cn/Article/details/gtwtvpaedk.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gtklspqpla.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtynfeileo.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtshyveruy.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtyxwfmqza.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfgoxrwac.html

[U09] Py：字典取最大值的键
来源：http://dali.xylfe.cn/Article/details/gtrqpmeukg.html

max(d, key=d.get)
来源：http://dali.hnqzz.top/Article/details/gtbdiiepmv.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gttxyiplxn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbhzoglhz.html

[U11] Py：生成器表达式
来源：http://dali.daria6918.cn/Article/details/gtbbburmok.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gtjouplzil.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtbcoklvdm.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtvuhsfful.html

[U13] Py：固定长度队列
来源：http://dali.ppjwa.cn/Article/details/gteezsvghe.html

deque(maxlen=10)
来源：http://dali.gogol.net.cn/Article/details/gtpkkwxlvj.html

[U14] Py：分组收集到列表
来源：http://dali.sysykeji.top/Article/details/gtwumqkgph.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gtjrxymfwo.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtrcnpgrff.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gtnjnxqcxq.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gtvpvrxkzw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gtczflraua.html

[U17] Py：初始化日志
来源：http://dali.yongpay.top/Article/details/gtsvppaafu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gtaxibysvz.html

[U18] Py：预编译正则
来源：http://dali.svipenyu.cn/Article/details/gtmpgeamui.html

pat = re.compile(r"\d+")
来源：http://dali.hfpthk.cn/Article/details/gtmgjqrggn.html

[U19] Py：正则替换带回调
来源：http://dali.aizwys.cn/Article/details/gtepuyctcj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zdqjudy.top/Article/details/gtgusqnufo.html

[U20] Py：缓存函数结果
来源：http://dali.zhongyouzk.top/Article/details/gtdrwbjtjz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.haohaochexian.top/Article/details/gtstforfgi.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gtevldhmrq.html

@contextlib.contextmanager
来源：http://dali.jinyuanbaomall.cn/Article/details/gthjdlksqx.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gtywwhigkg.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gtnyedpeil.html

[U23] Py：分块读取大文件
来源：http://dali.gogol.net.cn/Article/details/gtzfptzrzr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gttlcognju.html

[U24] Py：路径操作
来源：http://dali.quarkkingdee.top/Article/details/gtmctmkgde.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtaclozuhl.html

[U25] Py：CSV 按字典读
来源：http://dali.birdmap.top/Article/details/gtqjavputn.html

csv.DictReader(f)
来源：http://dali.nanxinkj.top/Article/details/gtmlpzdoly.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpfglcqh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.kuanghao11.cn/Article/details/gtdbxnlkxn.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbougzmpq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hongshengwenyu.top/Article/details/gtvgypqzga.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtttpjgucx.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtevwmwckl.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gtnhdkhezz.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcccaclqh.html

[U30] Py：数据类
来源：http://dali.chenlongwang.top/Article/details/gtdrttropz.html

@dataclass(slots=True)
来源：http://dali.sufxvd.cn/Article/details/gttqhklvow.html

[U31] Py：单测
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsfjfulys.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gtsrlgrlhr.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtzrurwpam.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gtqxmqahmi.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtmkixgevj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yueranfly.top/Article/details/gtblafcrzt.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtaxvzvuax.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gtyjguwxje.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gttgbfgkaa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sxryk.cn/Article/details/gtnjgalhhg.html

[U36] Py：定时任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwggwemdh.html

schedule.every(10).minutes.do(job)
来源：http://dali.pycfn.com/Article/details/gtraosvqgd.html

[U37] Py：读写 Excel
来源：http://dali.jinghuilouyu.cn/Article/details/gtlyuisdos.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gtzgskjiou.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtdgalwwim.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gtxhfxgepa.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtacbkglca.html

sys.stdout.isatty()
来源：http://dali.bjfxy.top/Article/details/gtgmidigsx.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gthkayntul.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtehlwaxul.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gtwdyvdppy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gtodmcmrui.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenzaomai.com/Article/details/gtkfczpiyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.vqdsnc.cn/Article/details/gtvlogvush.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtfmqqcntc.html

namespace App\Http;
来源：http://dali.xuetiantiany.cn/Article/details/gtwbawctqf.html

[U44] PHP：开启严格类型
来源：http://dali.hongshengwenyu.top/Article/details/gtnfakdhfj.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gtydthhriz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dianchejie.cn/Article/details/gtlpfnpoen.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gtrzygszah.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtzisaduth.html

?string $name = null
来源：http://dali.cucudq.cn/Article/details/gtznpiqmqy.html

[U47] PHP：联合类型
来源：http://dali.hammf.cn/Article/details/gtsmwurvsn.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gtpapzfany.html

[U48] PHP：纯枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazyeazlu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gtdyniikpn.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gtklsboemm.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gtnhlyquqm.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gtlriqefmt.html

public function __construct(private int $id) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkinrani.html

[U51] PHP：数组解构
来源：http://dali.jianghu66.top/Article/details/gtlcuftuex.html

[$a, $b] = $arr;
来源：http://dali.shangyingyoupin.top/Article/details/gtemqwuitl.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtfgpwkwji.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtezvnmbom.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gtoanjcgep.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangshuangyany.cn/Article/details/gtuyhemkyz.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gtuytozieb.html

$obj?->method()
来源：http://dali.hongshengwenyu.top/Article/details/gtxjvicqbt.html

[U55] PHP：match 表达式
来源：http://dali.bjfxy.top/Article/details/gtnbsulrig.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhiwuduotai.top/Article/details/gtxmwvlide.html

[U56] PHP：命名参数
来源：http://dali.daria6918.cn/Article/details/gthzuwzfpo.html

f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtmgcbkfio.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtthjstlvh.html

"值: {$a}"
来源：http://dali.yonumen.top/Article/details/gtwprfuraj.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gtldkyivkq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxuanxn.top/Article/details/gttgfdjbmn.html

[U59] PHP：自定义排序
来源：http://dali.hnqzz.top/Article/details/gtecewulty.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtdyqudtld.html

[U60] PHP：JSON 编解码
来源：http://dali.zhongyouzk.top/Article/details/gtqirenclt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gtrhgiqwfx.html

[U61] PHP：正则
来源：http://dali.birdmap.top/Article/details/gtlqiybryi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.haohaochexian.top/Article/details/gtwkysrbtk.html

[U62] PHP：日期对象
来源：http://dali.hongshengwenyu.top/Article/details/gtwnfmnuxe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenjidiqi.icu/Article/details/gtraflnfnm.html

[U63] PHP：文件读写
来源：http://dali.kuanghao11.cn/Article/details/gtfhduaxdg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjvcpesy.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtbmkhzygr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.haohaochexian.top/Article/details/gtagajhgam.html

[U65] PHP：会话
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiebteppy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtijtgmpmc.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtjzotrvpc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gtigqnxvpm.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gtirmppvxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtwipcttzg.html

[U68] PHP：PDO 连接
来源：http://dali.sufxvd.cn/Article/details/gtzomxuwce.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrasztqmy.html

[U69] PHP：PDO 预处理
来源：http://dali.zhengqikj.top/Article/details/gtpugsgvsx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gttjsckbow.html

[U70] PHP：PDO 事务
来源：http://dali.pycfn.com/Article/details/gtgjwemcei.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtgmswcdxx.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gtdhxbwovv.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gtjgmzpnyq.html

[U72] PHP：写错误日志
来源：http://dali.316326.xyz/Article/details/gtywslplam.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yvedp.cn/Article/details/gtaopcnock.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtfvzblmvl.html

parse_ini_file("config.ini", true)
来源：http://dali.yuanzhike.top/Article/details/gtsjmlwyeb.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gtzndhkbwk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yueranfly.top/Article/details/gtobywmkbt.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gtatidbmeu.html

composer require psr/container
来源：http://dali.xuetiantiany.cn/Article/details/gtyxgctexq.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gtuwodzsiu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gtjssywuaj.html

[U77] PHP：模板渲染
来源：http://dali.yuxming.cn/Article/details/gtcpaxakma.html

composer require twig/twig
来源：http://dali.tianlin.xyz/Article/details/gtnymnrtqn.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtrpkuxchn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhijiandao.cn/Article/details/gtkjodszef.html

[U79] PHP：静态分析
来源：http://dali.smart0.xyz/Article/details/gtzqmpvzmg.html

composer require --dev phpstan/phpstan
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpyvzmkq.html

[U80] PHP：代码规范修复
来源：http://dali.zhengqikj.top/Article/details/gtgyloiszk.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gtafeoekte.html

[U81] JS：初始化项目
来源：http://dali.jianghu66.top/Article/details/gtircgmmps.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gtxpasqguo.html

[U82] JS：package.json 脚本
来源：http://dali.vqdsnc.cn/Article/details/gtlwgdppny.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gtiuwkpoxm.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gtttzeyjka.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gtkyucguqi.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gtqegokdaw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtbsekwybk.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gtdahhuzbe.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtojybkvyj.html

[U86] JS：空值合并
来源：http://dali.pengpengdd.cyou/Article/details/gtwasdilir.html

a ?? b
来源：http://dali.jinqigfzy.top/Article/details/gtjfhejeln.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtzukkpvly.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gthravdhub.html

[U88] JS：对象展开合并
来源：http://dali.jyoumei.cn/Article/details/gtdczlvbwo.html

{ ...a, ...b }
来源：http://dali.ehwqpu.com/Article/details/gtkzhtrazy.html


<!-- 参考信息 -->