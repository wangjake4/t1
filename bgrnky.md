代发 wailian999

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtvglmtols.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtjhifozca.html

[T04] Kotlin：空安全
来源：http://dali.hnxiangtu.top/Article/details/gtppzpnumo.html

val n: String? = null;  n?.length
来源：http://dali.nanxinkj.top/Article/details/gtyvzviizq.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtdskddvdi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gtnvieevki.html

[T06] Kotlin：集合映射
来源：http://dali.fzhhl.top/Article/details/gtvtffbvig.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtyywxkblj.html

[T07] Kotlin：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtokapweie.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.316326.xyz/Article/details/gtajscqtyv.html

[T08] Kotlin：数据类
来源：http://dali.sxryk.cn/Article/details/gtrnuznbmt.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtucnqrnwd.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtyanoesil.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtlscsdmrd.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtoxjogaas.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtbcalcwnc.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtxdqreqqt.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtdrvgfshk.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtytubrhdg.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtofyeansx.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gtogwwbvoa.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gtgcngjgjb.html

[T14] Kotlin：循环
来源：http://dali.chenjidiqi.icu/Article/details/gtpvejgzra.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtljmaemfd.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtjgqaxgny.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtlrbvhkzu.html

[T16] Swift：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtpehcyygj.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtxiedwazn.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gtbyszrnlh.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gthmnsbpsu.html

[T18] Swift：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtvkzvtari.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtwzftmnaw.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtjrpunygz.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gttubaivyc.html

[T20] Swift：数组操作
来源：http://dali.aibaodan.cn/Article/details/gtixytraag.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gtlurkgpuz.html

[T21] Swift：遍历
来源：http://dali.shuidangran.top/Article/details/gtwqiithnf.html

for x in a { print(x) }
来源：http://dali.dashuyun.cn/Article/details/gtfsyfdfvs.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtwivfmbmi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hywenlv.cn/Article/details/gtulirvzud.html

[T23] Swift：函数
来源：http://dali.havefunace.top/Article/details/gtzpxsfutl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbeveqknp.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtwmwzmouk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gtunqjhhzg.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtrusrjgaz.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtnfcbhbkm.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtzkbiuurk.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtivpwvrqu.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtyosqsvvj.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtjzwaqcmi.html

[T28] Swift：枚举
来源：http://dali.ppjwa.cn/Article/details/gtikxcnbkp.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtqcrtucmm.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gtbvavpgzb.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gtlmevmbyp.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtstfcrsef.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtyrtliovj.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtlxjqcnmt.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtsaxjsfaj.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtudtrteho.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gtcngtvnpj.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtidyzrxqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdnhdkuze.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtsvikwsea.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtwbssojmv.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gttovvttgr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gtfuyqknpv.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtllgcngmp.html

function add(a, b) return a + b end
来源：http://dali.shanyushiyangtech.top/Article/details/gtbmzgziey.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtusbkaxvg.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gtrhihjxrz.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtpahwwpuc.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtjgmjthcg.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtnwxbnryg.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtkrqhfbdr.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtvyhgbjct.html

setmetatable({}, { __index = base })
来源：http://dali.ydzc1.top/Article/details/gtxzetxpyz.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gtelooncns.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtiltarxij.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtcnmhuwfj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtkrcpghjn.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtgctlefkd.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gthvyxopsh.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtlxdltpnq.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtulkcgkgi.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtnxirwqgg.html

for my $x (@arr) { print $x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvqgrybtd.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gtpjdlezlf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtlltxbxxe.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtvuqobuti.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtwfbjykgv.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gtstwkfszk.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gtypyhtlph.html

[T49] Perl：函数
来源：http://dali.jinqigfzy.top/Article/details/gtouhhhznf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtrqhtueai.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtmtckyeif.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtuqymuens.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtcpycwqis.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtdgkvkyqj.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gtupfrwvoy.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtrsgqsqfa.html

val a = 1;  var b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtnbpthhpb.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtyiprwpyx.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtyeazqjbu.html

[T54] Scala：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcrcfglx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xziqi.cn/Article/details/gtgwlwdsqn.html

[T55] Scala：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtcmgcnsql.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtlpppdupc.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtdumihwpb.html

case class User(name: String, age: Int)
来源：http://dali.birdmap.top/Article/details/gteclohgjp.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtygvnwvmf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gttqbkjltn.html

[T58] Scala：函数定义
来源：http://dali.ivvv.top/Article/details/gtxdkmwwni.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtcpytbdwt.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtwjqjidvy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtalwhlelw.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gtekahhwxs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ybcxt.top/Article/details/gtmojjaaml.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtuifsoiyc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtygesniwb.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjlvvxfvd.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtnkadrwdk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtuiwinrbr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtbgqwnbfw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gtwtwflffv.html

[U03] Py：加载 .env 配置
来源：http://dali.cashguo.top/Article/details/gtqdtygzes.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtejscheoa.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtzwecpntw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gtjrptnett.html

[U05] Py：列表去重且保序
来源：http://dali.ppjwa.cn/Article/details/gtuiuykgwr.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtbecbcauc.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gtuyppirhk.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtitgamoou.html

[U07] Py：反转字典键值
来源：http://dali.tian-w.cn/Article/details/gtfjradasf.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtvzugkhvc.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtrnsftpys.html

[y for x in nested for y in x]
来源：http://dali.yvedp.cn/Article/details/gtdffdvdjo.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gteutdwcqs.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtmyhwyaqg.html

[U10] Py：按值排序字典
来源：http://dali.xinyue.icu/Article/details/gtwhttzdld.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gtsybgnlnz.html

[U11] Py：生成器表达式
来源：http://dali.hammf.cn/Article/details/gtuvlealbq.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtaweqagaa.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gtmzqymnwg.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gtcmjckclz.html

[U13] Py：固定长度队列
来源：http://dali.yj202588.top/Article/details/gtyjfcmngs.html

deque(maxlen=10)
来源：http://dali.vqdsnc.cn/Article/details/gtmmnzagor.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gtteyzidrt.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtbjzmxdjf.html

[U15] Py：高精度计时
来源：http://dali.vqdsnc.cn/Article/details/gtmbncyszm.html

t = time.perf_counter()
来源：http://dali.jinghuilouyu.cn/Article/details/gttgsxpjsd.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gthfbfljts.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.snrcjt.cn/Article/details/gtpoykwwrk.html

[U17] Py：初始化日志
来源：http://dali.cdnleiting.top/Article/details/gtziyonywn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtzowvzzgo.html

[U18] Py：预编译正则
来源：http://dali.cqqwz.cn/Article/details/gtxkwnzwim.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gtpnphbnsl.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtshhdgafj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gttmbibsvx.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtqbokfviv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.c1oappe.top/Article/details/gtscuyxeaq.html

[U21] Py：自定义上下文管理器
来源：http://dali.shanyushiyangtech.top/Article/details/gtbluijuup.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtalanfgnv.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gtdertddky.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gtvrzkhphn.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtgbrvsylo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ppjwa.cn/Article/details/gtulrtujnu.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gtlmyekrpn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ppjwa.cn/Article/details/gtzpdyeuju.html

[U25] Py：CSV 按字典读
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwvaykdi.html

csv.DictReader(f)
来源：http://dali.jinqigufen.top/Article/details/gtsmnmsaep.html

[U26] Py：并发下载
来源：http://dali.birdmap.top/Article/details/gtxaqohjhg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gthjpzxjfm.html

[U27] Py：异步 HTTP
来源：http://dali.tian-w.cn/Article/details/gtydrufgtd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenzaomai.com/Article/details/gtxiuflclv.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gtfriscfnh.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtiyycuadp.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gtsgwbsluq.html

@property 与 @x.setter 配合
来源：http://dali.jlsjyb.cn/Article/details/gtjczpvjoz.html

[U30] Py：数据类
来源：http://dali.vqdsnc.cn/Article/details/gtijquxfiz.html

@dataclass(slots=True)
来源：http://dali.zhixingplan.top/Article/details/gtfmrscdab.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gturzqcyco.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gttjyuomzb.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gtxvysdsya.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtgyterxgo.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gtwaulckdx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.tian-w.cn/Article/details/gtpksefmus.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gtmhpzdfhh.html

chardet.detect(raw)
来源：http://dali.jinqigfzy.top/Article/details/gttopekeqe.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtaexowpwl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtrodmehju.html

[U36] Py：定时任务
来源：http://dali.xinyue.icu/Article/details/gtmollcjuk.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtotymcdpz.html

[U37] Py：读写 Excel
来源：http://dali.guannengcc.top/Article/details/gtaperalfi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gtszqdaioh.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gthfylwgjg.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtfenwdruj.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtmyodvbvb.html

sys.stdout.isatty()
来源：http://dali.zycfv.cn/Article/details/gtawewhvld.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtbzewkaer.html

print("err", file=sys.stderr)
来源：http://dali.yj20258.top/Article/details/gtkftpvrfy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gogol.net.cn/Article/details/gtbumcjhuo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtyimlyauu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hysaishi.cn/Article/details/gtdajkwxiq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gotoacloud.top/Article/details/gtveelahwc.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gtaajcnynq.html

namespace App\Http;
来源：http://dali.nanxinkj.top/Article/details/gtywekyizi.html

[U44] PHP：开启严格类型
来源：http://dali.zhixingplan.top/Article/details/gtzdgnngvm.html

declare(strict_types=1);
来源：http://dali.daria6918.cn/Article/details/gtbqpknxlz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gtulekghgl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtvipamchz.html

[U46] PHP：可空类型
来源：http://dali.zhoulong.xyz/Article/details/gtqczlppky.html

?string $name = null
来源：http://dali.sysykeji.top/Article/details/gthfuvqlbh.html

[U47] PHP：联合类型
来源：http://dali.yueranfly.top/Article/details/gtdotbjokz.html

int|string $id
来源：http://dali.chenzaomai.com/Article/details/gtnflnhrdm.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gthekmkfkm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sxryk.cn/Article/details/gteisvkcch.html

[U49] PHP：只读属性
来源：http://dali.iojbl.cn/Article/details/gtnerfzatu.html

public readonly string $name
来源：http://dali.jiagoushi.top/Article/details/gtourgzyne.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gtchucgppu.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtshytysri.html

[U51] PHP：数组解构
来源：http://dali.yj20258.top/Article/details/gtdcixcdbn.html

[$a, $b] = $arr;
来源：http://dali.aibaodan.cn/Article/details/gtdkqiuunj.html

[U52] PHP：箭头函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqjyibcs.html

$double = fn($x) => $x * 2;
来源：http://dali.c1oappe.top/Article/details/gtzvqbmpgh.html

[U53] PHP：空合并运算符
来源：http://dali.cqqwz.cn/Article/details/gtyhdpookw.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigufen.top/Article/details/gtcscisteq.html

[U54] PHP：空安全调用
来源：http://dali.yvedp.cn/Article/details/gtdpzdvzpn.html

$obj?->method()
来源：http://dali.xziqi.cn/Article/details/gtvmsxvrmv.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gtgraodbev.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtrjbgdrgl.html

[U56] PHP：命名参数
来源：http://dali.xziqi.cn/Article/details/gttbarcagt.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtxnaffimv.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtgyadxsgf.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gtnzdbateb.html

[U58] PHP：数组三件套
来源：http://dali.shangyingyoupin.top/Article/details/gtveijfkts.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.9152youxi.cn/Article/details/gthmczunjh.html

[U59] PHP：自定义排序
来源：http://dali.redwolf501.top/Article/details/gttrkkdfmp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gtifvgswgv.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gtmwuhagkw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtjnncdghl.html

[U61] PHP：正则
来源：http://dali.yj202588.top/Article/details/gtgttmamug.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuanzhike.top/Article/details/gtavakiplm.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gtdjvyiyup.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgfzy.top/Article/details/gtyjeiybph.html

[U63] PHP：文件读写
来源：http://dali.shanyushiyangtech.top/Article/details/gtejasvkms.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtvcfoazqp.html

[U64] PHP：目录遍历
来源：http://dali.zhixingplan.top/Article/details/gtxotullzz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xziqi.cn/Article/details/gtzwiuuwxq.html

[U65] PHP：会话
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkvqzugm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtokfaikwr.html

[U66] PHP：设置 Cookie
来源：http://dali.haohaochexian.top/Article/details/gtdirtuhus.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtmcyrulwu.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gtcqgdibqo.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtsjxomhfx.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gtvphiktpq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtkqvnxcwg.html

[U69] PHP：PDO 预处理
来源：http://dali.cqqwz.cn/Article/details/gtfdqgztxs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthbjrjpjs.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gteckojyrg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gteaddwyyg.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtqvbyvoaf.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtinagoeak.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gtdiqmyedq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gtojhyhnsz.html

[U73] PHP：读取 ini 配置
来源：http://dali.daria6918.cn/Article/details/gtybrcpawg.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxuanxn.top/Article/details/gtezaqgbxs.html

[U74] PHP：读取环境变量
来源：http://dali.fzhhl.top/Article/details/gtmvslxsgc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtedpepnxz.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtvuehaiks.html

composer require psr/container
来源：http://dali.shzxlz.cn/Article/details/gtfbioblhm.html

[U76] PHP：简单路由
来源：http://dali.chenjidiqi.icu/Article/details/gtdwqsozyl.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dianchejie.cn/Article/details/gtcygrrdss.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtvdkhxgzn.html

composer require twig/twig
来源：http://dali.yuxming.cn/Article/details/gtqvnvcxos.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gtpuyeager.html

composer require --dev phpunit/phpunit
来源：http://dali.jyoumei.cn/Article/details/gtbckfhfcb.html

[U79] PHP：静态分析
来源：http://dali.sxryk.cn/Article/details/gtgyqgacin.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqcfjkat.html

[U80] PHP：代码规范修复
来源：http://dali.yangfankeji.com/Article/details/gtqpqnqiaw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtbneuhags.html

[U81] JS：初始化项目
来源：http://dali.aibaodan.cn/Article/details/gtzbbkmikw.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gtzygoaycw.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gtwrwxqpck.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.iojbl.cn/Article/details/gtpdcrjsjl.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gtzxcnhssf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gtdjpjgqol.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gthbmjrgwu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.gaohongyu789.top/Article/details/gtpioyfjgm.html

[U85] JS：可选链
来源：http://dali.andypj.xyz/Article/details/gtijouuetb.html

a?.b?.c
来源：http://dali.yueranfly.top/Article/details/gtdxjnkttr.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gtcbhkmjoj.html

a ?? b
来源：http://dali.tian-w.cn/Article/details/gtowxshiew.html

[U87] JS：解构默认值
来源：http://dali.iojbl.cn/Article/details/gtrqinjmqp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhoulong.xyz/Article/details/gtknbdrsrt.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gtiexizdbu.html

{ ...a, ...b }
来源：http://dali.jinqigufen.top/Article/details/gtzpijgzdj.html

[U89] JS：数组去重
来源：http://dali.zycfv.cn/Article/details/gtbyxpnrhp.html

[...new Set(arr)]
来源：http://dali.dashuyun.cn/Article/details/gtumcmxhuk.html

[U90] JS：数字数组排序
来源：http://dali.havefunace.top/Article/details/gtcfwkpgpc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtpgcdafod.html


<!-- 参考信息 -->