代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gtpabkrqlx.html

[S57] C++：编译期常量
来源：http://dali.yanxiufei.cn/Article/details/gtgxklwnez.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtiksavugx.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtghhjhohb.html

namespace ns { int f() { return 1; } }
来源：http://dali.ppjwa.cn/Article/details/gthtwrjbrn.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtooftjiyy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtrruhmqqk.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gthojyhjll.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtbpcovnbi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfsimihm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gtdnwymbdj.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtuwwgaall.html

[T01] Kotlin：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtrycuciej.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtpglmydzu.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gtsmaipvqr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gttuwwllcf.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtdqezmofl.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtpnnfifca.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtkhatjxgq.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtqmviecfu.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gttnaeddqs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daria6918.cn/Article/details/gtwbrjcmcx.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtrkobsdqm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtxkpsbgul.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtbawvbtly.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtdwwlafzu.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gtkrcneauh.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtoqsalzbq.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtqsryxasw.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gtovwnkykk.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtxelxqrgs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zycfv.cn/Article/details/gtnxfmukee.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtgrvlsbel.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtnzggizzb.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtibimsgsn.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtjeisdcej.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gtdvnhqvan.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtqowdzgmv.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtzgdiuyin.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtkjykeclm.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtewwfhlco.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtpqbrpnbf.html

[T16] Swift：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtvuqyotff.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtzwtbzedq.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtukrnbwsb.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gttxmgewnl.html

[T18] Swift：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtiukszxyl.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtlctjcbft.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtqkweuice.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbciyzsl.html

[T20] Swift：数组操作
来源：http://dali.cashguo.top/Article/details/gtriuerhmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtwufmjdgh.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gtgfqraadu.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiodbjnm.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtxzzlfquf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hnqzz.top/Article/details/gtcikhollt.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtqlhikqtx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtmqwylmys.html

[T24] Swift：闭包
来源：http://dali.hysaishi.cn/Article/details/gtdlnjiiuy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtjotbrkzz.html

[T25] Swift：结构体
来源：http://dali.jinghuilouyu.cn/Article/details/gtigrjahvk.html

struct P { var x: Int }
来源：http://dali.zhiwuduotai.top/Article/details/gtegqjjmhs.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gtqquzshfb.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtkiohepqo.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gtbnnwmile.html

do { try f() } catch { print(error) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqdbntctw.html

[T28] Swift：枚举
来源：http://dali.hysaishi.cn/Article/details/gthajidwls.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gtsurxewtr.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtwmudrvrb.html

guard let x = opt else { return }
来源：http://dali.yuxming.cn/Article/details/gtmjxounsc.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gtuxegjvec.html

protocol Shape { func area() -> Double }
来源：http://dali.bjfxy.top/Article/details/gtyrbjzifd.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gtviwhpmay.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtgrpcbrne.html

[T32] Lua：局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtzatnshxg.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwwtssyb.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtcqkmyqbi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gthidvnmlx.html

[T34] Lua：遍历表
来源：http://dali.sweek.top/Article/details/gtfxxbbwct.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtuunrlmns.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgazhzdb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwlwgppgs.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gtjpyzsxvq.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtazwiykhx.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtcqbxjczp.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gtajtteybq.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gtftonxctd.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtxbyihfuw.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gtrkbrukhq.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtsulyhbln.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtjgjopkow.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtmpowgset.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtfexugrgc.html

print "Hello\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuvroxln.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtcqernrmc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyjqfgdhk.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtctwxyzmg.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gtyeuvydbl.html

[T44] Perl：条件
来源：http://dali.xylfe.cn/Article/details/gtelelqook.html

if ($a > 0) { print "正"; }
来源：http://dali.shzxlz.cn/Article/details/gtubuawnsb.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gttbjxhrgc.html

for my $x (@arr) { print $x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzmwpufuc.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gtrrtaiyfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtrhokuukk.html

[T47] Perl：正则捕获
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzlkperyr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtgfhgmhto.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtzfijaykz.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gtzcbqynvt.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtijinwuxy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtjydmvjdt.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gthsyttaau.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sufxvd.cn/Article/details/gtalaqdmlx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtzfqxioac.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtqwtdygui.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtuervovxw.html

[T52] Scala：变量
来源：http://dali.zdqjudy.top/Article/details/gtfweivusc.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gttptwhedy.html

[T53] Scala：字符串插值
来源：http://dali.yj20258.top/Article/details/gtnlqihlkp.html

s"值: $b"
来源：http://dali.hnqzz.top/Article/details/gttzajafnu.html

[T54] Scala：集合映射
来源：http://dali.meibo888.top/Article/details/gtchdxptmi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtkoynjukk.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtmmniqwsc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtftqkyrjk.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtkpykfshy.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtaetzxcji.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtdlvqkgdo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtqqbyrqji.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtkvtfqyqh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ehwqpu.com/Article/details/gtihjgaave.html

[T59] Scala：循环
来源：http://dali.jiagoushi.top/Article/details/gtdtgyjlqs.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtmviayrfa.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gthblgwjib.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtemvbcqqp.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtlghtxvqb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtgiyuoqva.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtwetxgtbn.html

[U01] Py：创建虚拟环境
来源：http://dali.yangfankeji.com/Article/details/gtwlkfnntl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtrmsxeeog.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gtccogiygp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gtainbxpth.html

[U03] Py：加载 .env 配置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuxelslbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtdhisbatf.html

[U04] Py：变量调试打印
来源：http://dali.xuetiantiany.cn/Article/details/gtpaypcwcx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.meibo888.top/Article/details/gtqsbtwbuo.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtpmvdwuvv.html

list(dict.fromkeys(arr))
来源：http://dali.guannengcc.top/Article/details/gtpwazlxac.html

[U06] Py：合并两个字典
来源：http://dali.guowangkeji.top/Article/details/gthgjulgjs.html

{**a, **b}
来源：http://dali.hywenlv.cn/Article/details/gthktwvckp.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gtpvytoocs.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtsygrlsks.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtfhtsosvu.html

[y for x in nested for y in x]
来源：http://dali.gogol.net.cn/Article/details/gtxazcfeef.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtzcjmlhtw.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gthkyrcrku.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gtqgojrcwg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtekcmuzpw.html

[U11] Py：生成器表达式
来源：http://dali.yuxming.cn/Article/details/gtjuowvuec.html

(x * 2 for x in arr)
来源：http://dali.yongpay.top/Article/details/gtqkhwtxcj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hammf.cn/Article/details/gtctdhttpu.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtwavnehmm.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtzmzjwxkj.html

deque(maxlen=10)
来源：http://dali.chenjidiqi.icu/Article/details/gtdhctrglv.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtjkoonkqd.html

defaultdict(list)
来源：http://dali.0kj1m.cn/Article/details/gtdiedsvxs.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gttoeeusmk.html

t = time.perf_counter()
来源：http://dali.jiagoushi.top/Article/details/gtteaivbhd.html

[U16] Py：命令行参数解析
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnjzcppn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtrwmguyql.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtykmdmgno.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenlongwang.top/Article/details/gtliaujgms.html

[U18] Py：预编译正则
来源：http://dali.feifeiyinyue.top/Article/details/gtgkyyvozw.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gtqbkgjkls.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gtkigedimp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jiagoushi.top/Article/details/gtqeoczmjf.html

[U20] Py：缓存函数结果
来源：http://dali.hywenlv.cn/Article/details/gtbkwokqci.html

@functools.lru_cache(maxsize=None)
来源：http://dali.havefunace.top/Article/details/gtrlduklpv.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtogcljohs.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gtfnwjuteg.html

[U22] Py：矩阵转置
来源：http://dali.ehwqpu.com/Article/details/gtxmgozevj.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtieulkzxb.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gtbbvfwqrf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gtensqzgbh.html

[U24] Py：路径操作
来源：http://dali.tanke756.top/Article/details/gtcuyvnniq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtqqjfgbnb.html

[U25] Py：CSV 按字典读
来源：http://dali.chenlongwang.top/Article/details/gtkmsunsev.html

csv.DictReader(f)
来源：http://dali.cashguo.top/Article/details/gtinokowqx.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gtqgvvhpdk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtmnquzpst.html

[U27] Py：异步 HTTP
来源：http://dali.hysaishi.cn/Article/details/gtrfggkszc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shanyushiyangtech.top/Article/details/gtmljkbfrz.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gtztbjlahl.html

UserId = int
来源：http://dali.havefunace.top/Article/details/gtediuqcsh.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtskricczc.html

@property 与 @x.setter 配合
来源：http://dali.cheryme.top/Article/details/gtyuthdfoq.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gtifzpcvav.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gthymxtrxx.html

[U31] Py：单测
来源：http://dali.yj20258888.top/Article/details/gtfrevqryy.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gttwkaegmg.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtfrwtgfsy.html

ruff format . && ruff check --fix .
来源：http://dali.birdmap.top/Article/details/gtswsdnikx.html

[U33] Py：打包发布
来源：http://dali.fengsongda.top/Article/details/gtscbsbjou.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zycfv.cn/Article/details/gtfeefgsgh.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gthsxndjee.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gtcxvzpkqe.html

[U35] Py：发送邮件
来源：http://dali.vqdsnc.cn/Article/details/gtlkauwuak.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtdlqzsdgj.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gtprwdyrjb.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtqrfzdhhd.html

[U37] Py：读写 Excel
来源：http://dali.pengpengdd.cyou/Article/details/gtixyapgnf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sufxvd.cn/Article/details/gtqllxmgyh.html

[U38] Py：获取脚本所在目录
来源：http://dali.smart0.xyz/Article/details/gtwjslmpiu.html

Path(__file__).resolve().parent
来源：http://dali.316326.xyz/Article/details/gtemcsavum.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gtqjsbkyxg.html

sys.stdout.isatty()
来源：http://dali.tianlin.xyz/Article/details/gtawugdxke.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gtdrdorvpg.html

print("err", file=sys.stderr)
来源：http://dali.mhx1999.top/Article/details/gtiitvvquj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yangfankeji.com/Article/details/gtrkdpyzbj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtdfwjkluu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aizwys.cn/Article/details/gtkkotapla.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cheryme.top/Article/details/gtfitxsgfn.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gtvophrrqp.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gtpadcszfa.html

[U44] PHP：开启严格类型
来源：http://dali.fzhhl.top/Article/details/gtomsbaxkh.html

declare(strict_types=1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdeylzuqj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj20258888.top/Article/details/gtmujyxedw.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtiyqmskea.html

[U46] PHP：可空类型
来源：http://dali.zhijiandao.cn/Article/details/gtmahocxus.html

?string $name = null
来源：http://dali.zdqjudy.top/Article/details/gtifytobev.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gttgldfmpm.html

int|string $id
来源：http://dali.hongshengwenyu.top/Article/details/gtgbikujyp.html

[U48] PHP：纯枚举
来源：http://dali.fengsongda.top/Article/details/gtfnnknxsf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gttoxdbzxo.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtihqrkghp.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgktyrued.html

[U50] PHP：构造器属性提升
来源：http://dali.chenlongwang.top/Article/details/gtaarnmdxj.html

public function __construct(private int $id) {}
来源：http://dali.yj202588.top/Article/details/gtkvptxjkz.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gteeopaecm.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gtguqoahnm.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtnawhtdeo.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtcgixipqb.html

[U53] PHP：空合并运算符
来源：http://dali.ybcxt.top/Article/details/gtjfzezalp.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gteiylrnkb.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtxevkwcmc.html

$obj?->method()
来源：http://dali.jlsjyb.cn/Article/details/gtmbtxdhqf.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtfkgymbsi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.svipenyu.cn/Article/details/gtjxhxvvyq.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtnoaeuxle.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtguoybklt.html

[U57] PHP：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtldfiaruc.html

"值: {$a}"
来源：http://dali.hywenlv.cn/Article/details/gtlghuyvuq.html

[U58] PHP：数组三件套
来源：http://dali.zdqjudy.top/Article/details/gtxtxpebnq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tanke756.top/Article/details/gtkzzalzdj.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtsvnftash.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gzhubu.top/Article/details/gthtpfsgqu.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gthncfmmqk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtximzgzjs.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gthldxxaip.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtdntnhlfc.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtqezgdwet.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinghuilouyu.cn/Article/details/gtbhdkzslu.html

[U63] PHP：文件读写
来源：http://dali.tianlin.xyz/Article/details/gtdnxtznwu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gtjqhgfooy.html

[U64] PHP：目录遍历
来源：http://dali.daria6918.cn/Article/details/gtxquwmzcf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtqgdvomue.html

[U65] PHP：会话
来源：http://dali.guowangkeji.top/Article/details/gtercywtqk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtohmpdryy.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtxwmmeqio.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangdashe.top/Article/details/gtdazjzbmg.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gtvsusulcv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtjosporxg.html

[U68] PHP：PDO 连接
来源：http://dali.ydzc1.top/Article/details/gtryuipxxj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gtxuyvcsuh.html

[U69] PHP：PDO 预处理
来源：http://dali.xuanzx.com/Article/details/gtcpwrsgzm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gttzptxouv.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gtoocdtydv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtdmcqcsvp.html

[U71] PHP：抛出异常
来源：http://dali.jianghu66.top/Article/details/gtixwnqlrm.html

throw new RuntimeException("失败", 500);
来源：http://dali.meibo888.top/Article/details/gtyygohfye.html

[U72] PHP：写错误日志
来源：http://dali.fzhhl.top/Article/details/gtclmizmxx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.kuanghao11.cn/Article/details/gtnqgnctzl.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuanzx.com/Article/details/gtfedsegsn.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtfptmiish.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtmwruzpah.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xinyue.icu/Article/details/gtxabwoxor.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gtgljdleuw.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gtlzsmtocq.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gtjeriagmp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangshuangyany.cn/Article/details/gtnvprcrhn.html

[U77] PHP：模板渲染
来源：http://dali.pycfn.com/Article/details/gtekqxyjzq.html

composer require twig/twig
来源：http://dali.yj202588.top/Article/details/gtvtqjjphc.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gtrnhihhww.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gttwjfnciv.html

[U79] PHP：静态分析
来源：http://dali.yj20258.top/Article/details/gtnbvoztyk.html

composer require --dev phpstan/phpstan
来源：http://dali.wangdashe.top/Article/details/gtgmqkmpez.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtumpxoguv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gtcdqgytwx.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gtbsniirew.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gtbsgunapu.html

[U82] JS：package.json 脚本
来源：http://dali.9152youxi.cn/Article/details/gtggyrebmm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnxiangtu.top/Article/details/gtnbfzrxqk.html


<!-- 参考信息 -->