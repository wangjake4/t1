代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtsyrebgtl.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtktzdzlcx.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtpecrhfyp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.mhx1999.top/Article/details/gtirxvboee.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlwfyanh.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtgqkpntge.html

[T04] Kotlin：空安全
来源：http://dali.gogol.net.cn/Article/details/gtkoprajfh.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtynsscuri.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtyghnrnkz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtbbmzgcel.html

[T06] Kotlin：集合映射
来源：http://dali.hammf.cn/Article/details/gtcxhfjfnd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtzybtpqfb.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gtgtopzfvr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtojefwrws.html

[T08] Kotlin：数据类
来源：http://dali.pycfn.com/Article/details/gttqyexzgd.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtarphuyvr.html

[T09] Kotlin：扩展函数
来源：http://dali.yvedp.cn/Article/details/gtvgxbnkmf.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtcijqgnmk.html

[T10] Kotlin：默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gtnqeudamz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtwrsmsgkm.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtardfeghy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtmdeejaky.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtndwtlzks.html

val (a, b) = Pair(1, 2)
来源：http://dali.vqdsnc.cn/Article/details/gtkxnxydxl.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtkujfueix.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtviqhfrty.html

[T14] Kotlin：循环
来源：http://dali.0kj1m.cn/Article/details/gtlzinarzz.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gttxuhzcez.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtuzhqkfmv.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtayajigmg.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtyfcldgjj.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtszulvssm.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssybgtlj.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtbugvdura.html

[T18] Swift：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtipmakaan.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtmtkktfpi.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtaeneghxl.html

if let n = opt { print(n) }
来源：http://dali.yj20258888.top/Article/details/gtlsmsesln.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtmojjkoxv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtbiwidmzu.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gteovkyafe.html

for x in a { print(x) }
来源：http://dali.sysykeji.top/Article/details/gtkaumlaco.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtpzyaqlxq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtlqhiwrzo.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvdfbdksi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtxnpksgmj.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gtqcxyltms.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtdhzdiqls.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtxmzdvvuz.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtcblpspdu.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtmtplzegt.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gttxadtqrp.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtnwhelvfc.html

do { try f() } catch { print(error) }
来源：http://dali.pycfn.com/Article/details/gtxgttokxy.html

[T28] Swift：枚举
来源：http://dali.tianlin.xyz/Article/details/gtrotnhums.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gthmekkyse.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gtyxiwppui.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtpadbgzae.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gtfmrqwmdf.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtbaaqxvxh.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gttzgqrbli.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtbexjjqvi.html

[T32] Lua：局部变量
来源：http://dali.yvedp.cn/Article/details/gtvxxyjcaw.html

local a = 1
来源：http://dali.birdmap.top/Article/details/gtlzjviecq.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtrhwgufmx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtvribawcy.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtiwqpecij.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtfmqvurcd.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gthmbeqwrb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gtsugnaozs.html

[T36] Lua：函数
来源：http://dali.sxryk.cn/Article/details/gtzsejlwjh.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gterlkkacc.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtmenxpzvf.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtkqcgmejl.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtnmdwekom.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtatgbjcjw.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gthduzegqa.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtxethrzzs.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtemfhfocv.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gtutgoqdku.html

[T41] Perl：Hello World
来源：http://dali.cashguo.top/Article/details/gtmjbebjjh.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtyxdocijm.html

[T42] Perl：变量类型
来源：http://dali.guannengcc.top/Article/details/gtxgtivpom.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtpviztiko.html

[T43] Perl：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gteoxmapbv.html

"值: $a"
来源：http://dali.ppjwa.cn/Article/details/gtgorrnxpy.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gtqbvwepff.html

if ($a > 0) { print "正"; }
来源：http://dali.yuanzhike.top/Article/details/gtvqifvcjy.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtjoepmglz.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtmpjoxbhq.html

[T46] Perl：哈希操作
来源：http://dali.xylfe.cn/Article/details/gtshakemlk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtjwdvnlnp.html

[T47] Perl：正则捕获
来源：http://dali.xuetiantiany.cn/Article/details/gtjussatii.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtdrkmisrf.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtbyglfabi.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtisizpoyh.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtkkyvbnkm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtvkbtfkxc.html

[T50] Perl：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtdnaweqgl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtkmifitmt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gttdulffhd.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmjhumwkr.html

println("Hello")
来源：http://dali.xinyue.icu/Article/details/gthokxifys.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtcirzsztv.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gtuzdgdzzt.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtngottpho.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtnhvipjtm.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtwntznpkd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexpskzor.html

[T55] Scala：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gtdxnwxhmp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.c1oappe.top/Article/details/gtjzzniask.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gtvlztxinf.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtkuuoscjg.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtqxltitkt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sufxvd.cn/Article/details/gtckdmtioy.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtfvsydwzf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtpmhzkqnj.html

[T59] Scala：循环
来源：http://dali.chenzaomai.com/Article/details/gtosxabfjr.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtncjpdovw.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gtpfhkyvkt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtumzpabwu.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtbdmamtus.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jlsjyb.cn/Article/details/gtowiqzeue.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtxwsfflql.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtzfdcdmsc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtspzhfupy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gttcggutul.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gtkhtoyqle.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmhzgoqj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtdstpnvpn.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gtcougixff.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtesuitbfw.html

[U05] Py：列表去重且保序
来源：http://dali.chenjidiqi.icu/Article/details/gtvrudgubu.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtyjtaggqa.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtydhmunko.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtudpxqmek.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtodmoftum.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtkmnmgpmy.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtqanwjlty.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gttulmondy.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtslcvkpqh.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gthdirxhxt.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtgkjoymtb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daria6918.cn/Article/details/gtyasecsan.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gtupesmsak.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtzftonhyc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyvijjwp.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtpeyjofmo.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gtalwgacon.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhlgiqlo.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gtiafnoepx.html

defaultdict(list)
来源：http://dali.daria6918.cn/Article/details/gtxbqaspjo.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gtqtsfuoep.html

t = time.perf_counter()
来源：http://dali.yj202588.top/Article/details/gthxvlcqth.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gthyvpbqbq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gtkhyotnwo.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoznreate.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gtiuglsyvj.html

[U18] Py：预编译正则
来源：http://dali.jianghu66.top/Article/details/gtcyktjsmk.html

pat = re.compile(r"\d+")
来源：http://dali.wangdashe.top/Article/details/gthjddpaan.html

[U19] Py：正则替换带回调
来源：http://dali.andypj.xyz/Article/details/gtvugpwdaa.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daxiang520.top/Article/details/gtmeezwtdm.html

[U20] Py：缓存函数结果
来源：http://dali.cdnleiting.top/Article/details/gtxeeekmrc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ivvv.top/Article/details/gtbzgiscqo.html

[U21] Py：自定义上下文管理器
来源：http://dali.jlsjyb.cn/Article/details/gtpuokhkjy.html

@contextlib.contextmanager
来源：http://dali.sufxvd.cn/Article/details/gtrleqafuy.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtgzswegsc.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtpouvhzry.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtriegmqrq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hfpthk.cn/Article/details/gtbldvligh.html

[U24] Py：路径操作
来源：http://dali.gzhubu.top/Article/details/gtjttdauwm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtkyrdgjrv.html

[U25] Py：CSV 按字典读
来源：http://dali.dashuyun.cn/Article/details/gtixsdumyb.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gtnbwuozpe.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gtjmnaqdgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenjidiqi.icu/Article/details/gtffijddsf.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtofnustct.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvhsdflji.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gtbhibtyou.html

UserId = int
来源：http://dali.yonumen.top/Article/details/gtwvysrmix.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gtxdvovzqv.html

@property 与 @x.setter 配合
来源：http://dali.hnqzz.top/Article/details/gtcnwvrmyw.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gtrjgrbfau.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtinrdrouw.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gtikwcgxgn.html

python -m pytest -q
来源：http://dali.redwolf501.top/Article/details/gtnwzppnya.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gthhahotcy.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtqekyxmcd.html

[U33] Py：打包发布
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrabbscza.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gtyyzolhwv.html

[U34] Py：判断编码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdodujgkb.html

chardet.detect(raw)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjyspyyb.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gtefchnjve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gtulgzigen.html

[U36] Py：定时任务
来源：http://dali.316326.xyz/Article/details/gtyvrveoek.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtajqaeeww.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gtyyngjqzn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtjwnxpvvt.html

[U38] Py：获取脚本所在目录
来源：http://dali.mhx1999.top/Article/details/gtmvbodbwc.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gttvdvqjml.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtmylkapba.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gtqlbywdci.html

[U40] Py：打印到标准错误
来源：http://dali.chenlongwang.top/Article/details/gtwnyxyoap.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtekobzpsn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cqqwz.cn/Article/details/gtuvpbpoms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenlongwang.top/Article/details/gtrlvvjosh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtliogesgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gtsafrzuta.html

[U43] PHP：声明命名空间
来源：http://dali.svipenyu.cn/Article/details/gtpsogeffz.html

namespace App\Http;
来源：http://dali.c1oappe.top/Article/details/gtmdrjpvcv.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtiigdnlvm.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gtlwabqwwv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guowangkeji.top/Article/details/gtbvffikhl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtynxbakjy.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtdievrgox.html

?string $name = null
来源：http://dali.yueranfly.top/Article/details/gtqlhlaanh.html

[U47] PHP：联合类型
来源：http://dali.xylfe.cn/Article/details/gtutowlppd.html

int|string $id
来源：http://dali.yuxming.cn/Article/details/gtbgdflwmb.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gtjwukkdka.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gtpmwnrbmh.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gtedvtvntg.html

public readonly string $name
来源：http://dali.guowangkeji.top/Article/details/gtfzvnptnj.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gtgyfxcsmg.html

public function __construct(private int $id) {}
来源：http://dali.zhongyouzk.top/Article/details/gtymphpqyp.html

[U51] PHP：数组解构
来源：http://dali.jinqigufen.top/Article/details/gtpoqxgkmu.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gtcpbghmvu.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtofingbdi.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtqqmlcmac.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gtvulgzymn.html

$v = $a ?? $b ?? "default";
来源：http://dali.gotoacloud.top/Article/details/gtwzezyezw.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gtzsjhnqha.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gtxczocufw.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gttavrwxad.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtjdbmccoj.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gtlzzisihm.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtciogvpqx.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtpxehdlcv.html

"值: {$a}"
来源：http://dali.cdnleiting.top/Article/details/gtvuxvomwc.html

[U58] PHP：数组三件套
来源：http://dali.andypj.xyz/Article/details/gtksznvtvc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gtuflfeodn.html

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gttfrqffjm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gtqjdnexsj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gtofjrqlcf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tanke756.top/Article/details/gtatreoryg.html

[U61] PHP：正则
来源：http://dali.andypj.xyz/Article/details/gtadtznrwv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoqexupv.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gtlhmvyipc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtqcgdyros.html

[U63] PHP：文件读写
来源：http://dali.wangdashe.top/Article/details/gtfwtpbybj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yonumen.top/Article/details/gtbkiuxzwy.html

[U64] PHP：目录遍历
来源：http://dali.ydzc1.top/Article/details/gtgyzmdycy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xylfe.cn/Article/details/gtpqvfrumd.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtafhqdwby.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtuxfahgot.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtcsoczhti.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtpdvrckmq.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gtpqlbdeum.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guowangkeji.top/Article/details/gtmaritgwa.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gttzglmkag.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.guowangkeji.top/Article/details/gtugapqrat.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtejilqinx.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.quarkkingdee.top/Article/details/gtjzmuwtya.html

[U70] PHP：PDO 事务
来源：http://dali.tian-w.cn/Article/details/gtcaehpsjc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtyjcfpclv.html

[U71] PHP：抛出异常
来源：http://dali.guowangkeji.top/Article/details/gtnmggfqvu.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhixingplan.top/Article/details/gtxxrxaxlu.html

[U72] PHP：写错误日志
来源：http://dali.zhoulong.xyz/Article/details/gtewekgjvn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gtjwoteztj.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxinkj.top/Article/details/gtbqjqamtv.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtvgfxrhem.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtsvuvcnmz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.0kj1m.cn/Article/details/gtuaarsjvx.html

[U75] PHP：依赖注入
来源：http://dali.yonumen.top/Article/details/gturvewwdz.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gtvzszfqwk.html

[U76] PHP：简单路由
来源：http://dali.c1oappe.top/Article/details/gtijybxjgt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pycfn.com/Article/details/gtaioyokyw.html

[U77] PHP：模板渲染
来源：http://dali.shuidangran.top/Article/details/gtsuskfoqg.html

composer require twig/twig
来源：http://dali.birdmap.top/Article/details/gtzrzbjgjh.html

[U78] PHP：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcqmqdcpw.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gtikbaahzo.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtdvwisnzz.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxuanxn.top/Article/details/gtraqktibd.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gtaeuelmea.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shangyingyoupin.top/Article/details/gtuczkjjhh.html

[U81] JS：初始化项目
来源：http://dali.sufxvd.cn/Article/details/gtlejbbbsd.html

npm init -y;  npm i express
来源：http://dali.dashuyun.cn/Article/details/gtuiaehgaf.html

[U82] JS：package.json 脚本
来源：http://dali.fzhhl.top/Article/details/gtxfjcfyjd.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sxryk.cn/Article/details/gtollgqout.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gtqbnrsvev.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.cucudq.cn/Article/details/gtojdpemzu.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gthiekmyxi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.pengpengdd.cyou/Article/details/gtpcbaaayj.html

[U85] JS：可选链
来源：http://dali.chenjidiqi.icu/Article/details/gtdysxicrl.html

a?.b?.c
来源：http://dali.dianchejie.cn/Article/details/gtyhcdmqwa.html

[U86] JS：空值合并
来源：http://dali.yvedp.cn/Article/details/gtvczufkiw.html

a ?? b
来源：http://dali.gotoacloud.top/Article/details/gtzjhjikse.html

[U87] JS：解构默认值
来源：http://dali.gzhubu.top/Article/details/gtanqwikyd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gtpfxuczom.html

[U88] JS：对象展开合并
来源：http://dali.cheryme.top/Article/details/gtlmkmghnn.html

{ ...a, ...b }
来源：http://dali.pycfn.com/Article/details/gtvtnflshy.html


<!-- 参考信息 -->