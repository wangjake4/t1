代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xylfe.cn/Article/details/gtzjgnaklz.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtpwjgcdru.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtymydntpw.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtkaowqsic.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtzkenaafo.html

[S59] C++：静态断言
来源：http://dali.dianchejie.cn/Article/details/gtzebbfgme.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhengqikj.top/Article/details/gtzdovhszx.html

[S60] C++：遍历并删除元素
来源：http://dali.tanke756.top/Article/details/gtemhzqthz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvhegqkj.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtyhybutvx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtgrbeongr.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrcdbhnni.html

[T01] Kotlin：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gttndjzanh.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtijwanlvc.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtvlvrkjlv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtccfvotgq.html

[T03] Kotlin：字符串模板
来源：http://dali.sxryk.cn/Article/details/gtynbktytr.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtmlxnkyzc.html

[T04] Kotlin：空安全
来源：http://dali.yuxming.cn/Article/details/gtifhvlyde.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gteiqnrchn.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtvhvwdudx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtnghiiukh.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtvgxsvvre.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zdqjudy.top/Article/details/gtmkmecqyi.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtyttocdfk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtouewjmjh.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gtyoxfttyt.html

data class User(val name: String, val age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtgqjvmdkg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtwpbdtzqq.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtfryauvpv.html

[T10] Kotlin：默认参数
来源：http://dali.sufxvd.cn/Article/details/gtnmzuulzx.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtsumftwdw.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtwydbgohh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyiphsvix.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtahdmuyhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.sweek.top/Article/details/gtezuvcbgy.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtkjwdwlgb.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtixfuioru.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtvhssqatr.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtjdcfhgqj.html

[T15] Kotlin：接口
来源：http://dali.haohaochexian.top/Article/details/gtoqpovlfi.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtzwyvzafk.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtlxbvqqjx.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtbynllafd.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtcybaulmo.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gteiolovon.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gthonjromx.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gtmnceagru.html

[T19] Swift：可选绑定
来源：http://dali.xuanzx.com/Article/details/gtrhtxsbqk.html

if let n = opt { print(n) }
来源：http://dali.meibo888.top/Article/details/gtlyqnuxjy.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gttjzrcvvw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtfutfgune.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtntcoohkq.html

for x in a { print(x) }
来源：http://dali.yj20258888.top/Article/details/gtkqzuhwlc.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtvfoxuxiw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtaburqimj.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtowqyjmxm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtihpqljph.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtzslmcowa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xylfe.cn/Article/details/gtgjkplrfr.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gtdbzcqock.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gthscsufle.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtnflszxge.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxgnepbxr.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtosqdihlj.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gtphlkppzy.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtgoxxpryi.html

enum Color { case red, green }
来源：http://dali.jiagoushi.top/Article/details/gthohzvuyg.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtmymgubjk.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtgkvczirm.html

[T30] Swift：协议
来源：http://dali.jianghu66.top/Article/details/gticjppkld.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtywjnnvco.html

[T31] Lua：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtxkqgymnt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtvdxmsrsh.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtjrfqhzwj.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gttpwpovha.html

[T33] Lua：表（数组）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaunolyyu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtekmolcqb.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gtzutqfpcu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj202588.top/Article/details/gtkdjndqju.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtguwjjfpo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtstttbhpm.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtideyqmyi.html

function add(a, b) return a + b end
来源：http://dali.aizwys.cn/Article/details/gtneakklss.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtxygdgvrf.html

"a" .. "b"
来源：http://dali.hywenlv.cn/Article/details/gtgditjxsx.html

[T38] Lua：条件
来源：http://dali.shzxlz.cn/Article/details/gtnecovtmx.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtlgqrinsk.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gtxxotrvzh.html

string.find(s, "%d+")
来源：http://dali.redwolf501.top/Article/details/gteonquunl.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtyskkhqid.html

setmetatable({}, { __index = base })
来源：http://dali.316326.xyz/Article/details/gttuskcujn.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtkwvuqgpr.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtkebagdmn.html

[T42] Perl：变量类型
来源：http://dali.yongpay.top/Article/details/gtyaiqwdad.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtidpheskh.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtgfegcnno.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gthnzdtruj.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcdceztln.html

if ($a > 0) { print "正"; }
来源：http://dali.yuxming.cn/Article/details/gtfaojodwb.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gtvxuteelo.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gttkjykltr.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtgoeomnxs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtlhpcbovb.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtuikdhwye.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.aizwys.cn/Article/details/gtnheuxgtm.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtwukcpmdx.html

$s =~ s/old/new/g;
来源：http://dali.zhiwuduotai.top/Article/details/gtpxwubbie.html

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtmhonvzpi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtxjhfzlre.html

[T50] Perl：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtqlgvgcar.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gtunjbezmq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xziqi.cn/Article/details/gtorseyfra.html

[T51] Scala：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpucjueug.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtwrnozkqs.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtamdsnksh.html

val a = 1;  var b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtdmrqkciv.html

[T53] Scala：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtmctijnoo.html

s"值: $b"
来源：http://dali.pycfn.com/Article/details/gtnesgadff.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtpsboaqwt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtzeeovodt.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtsjplnxvl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtmabfhdbk.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtfrdzpdsf.html

case class User(name: String, age: Int)
来源：http://dali.xinyue.icu/Article/details/gtlzchujnk.html

[T57] Scala：模式匹配
来源：http://dali.yj202588.top/Article/details/gtrvxvvmdk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtqspeptoy.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtelezdskk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtuppcozfi.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtdduxdvhp.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtfxeuimlp.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtgfdcrfsq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yanxiufei.cn/Article/details/gtfmsinarb.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtluvettzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gtyvrjgsfz.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtoeqzravz.html

[U01] Py：创建虚拟环境
来源：http://dali.dianchejie.cn/Article/details/gtvzfrnhop.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhijiandao.cn/Article/details/gtyfmxevwe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuanzx.com/Article/details/gthcnszvfz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtuoaiysiq.html

[U03] Py：加载 .env 配置
来源：http://dali.chenlongwang.top/Article/details/gtfynolukk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gtqsrlskbj.html

[U04] Py：变量调试打印
来源：http://dali.jyoumei.cn/Article/details/gtmttltrjf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.haohaochexian.top/Article/details/gtolutwdvd.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gtodhxdiiy.html

list(dict.fromkeys(arr))
来源：http://dali.pycfn.com/Article/details/gtijbbhmfx.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtwxcekbow.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtkzbwlfqr.html

[U07] Py：反转字典键值
来源：http://dali.chenlongwang.top/Article/details/gtusrjdosm.html

{v: k for k, v in d.items()}
来源：http://dali.svipenyu.cn/Article/details/gtbhopkqnd.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtpaqbncoa.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwmoldsu.html

[U09] Py：字典取最大值的键
来源：http://dali.pycfn.com/Article/details/gthpjqiwlo.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtcddirwpe.html

[U10] Py：按值排序字典
来源：http://dali.svipenyu.cn/Article/details/gtsuqxpyod.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnqzz.top/Article/details/gtjkwwowgq.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtkgywlcsp.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtdspncrdq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtzrcyjjbm.html

Counter(arr).most_common(3)
来源：http://dali.shzxlz.cn/Article/details/gtuwvwjoqe.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gtqqwyesgw.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gtsvgnjclb.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpeebyfhe.html

defaultdict(list)
来源：http://dali.ydzc1.top/Article/details/gtskypyndu.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtsetlciwd.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gtxqsdwbjs.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtuzilesns.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sufxvd.cn/Article/details/gtixsnfjlq.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtvqxnwbzz.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.mhx1999.top/Article/details/gtfpvxhwsi.html

[U18] Py：预编译正则
来源：http://dali.jlsjyb.cn/Article/details/gthccwrbhq.html

pat = re.compile(r"\d+")
来源：http://dali.svipenyu.cn/Article/details/gtjgigqbqn.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtqtfrjakx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gtyblisqhu.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gtoqxtmnnb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gttthxztjh.html

[U21] Py：自定义上下文管理器
来源：http://dali.havefunace.top/Article/details/gthqtnutvj.html

@contextlib.contextmanager
来源：http://dali.yvedp.cn/Article/details/gtaorceczz.html

[U22] Py：矩阵转置
来源：http://dali.jinqigufen.top/Article/details/gtqknpmoeo.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtretjaife.html

[U23] Py：分块读取大文件
来源：http://dali.yongpay.top/Article/details/gtzgluqtrt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtyajoajfz.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvghcdpxg.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gttgqlgxtr.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtytpzokcl.html

csv.DictReader(f)
来源：http://dali.smart0.xyz/Article/details/gtalsnflsk.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtghhhphek.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hongshengwenyu.top/Article/details/gtclozedmn.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtxkmkzsko.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gtmghmrssl.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gtixsisznm.html

UserId = int
来源：http://dali.gaohongyu789.top/Article/details/gthxrirqjo.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gtajiwltqt.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gttskxiwup.html

[U30] Py：数据类
来源：http://dali.gogol.net.cn/Article/details/gtmkyhahlq.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtwrypqrdv.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gtbjxugqyj.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtncjvasct.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gtugjmisus.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gtfhtginyf.html

[U33] Py：打包发布
来源：http://dali.zdqjudy.top/Article/details/gtlcfmhips.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shuidangran.top/Article/details/gtpvrfzixz.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gtabydosmz.html

chardet.detect(raw)
来源：http://dali.pengpengdd.cyou/Article/details/gtimrkicxg.html

[U35] Py：发送邮件
来源：http://dali.cdnleiting.top/Article/details/gtxxyexyku.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hfpthk.cn/Article/details/gthvmyevlf.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gtbopqzmxe.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gtcoprwgfz.html

[U37] Py：读写 Excel
来源：http://dali.snrcjt.cn/Article/details/gtvhaqhezi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gtkohhldyw.html

[U38] Py：获取脚本所在目录
来源：http://dali.ydzc1.top/Article/details/gtwobfszlz.html

Path(__file__).resolve().parent
来源：http://dali.dianchejie.cn/Article/details/gtwrybndab.html

[U39] Py：判断是否在交互环境
来源：http://dali.yueranfly.top/Article/details/gtgloelnai.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtyndbxymu.html

[U40] Py：打印到标准错误
来源：http://dali.sxryk.cn/Article/details/gtzkjvtwym.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtnviwtbto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtbzsxozgz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gtjfakbqna.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gtfmdovvzl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.iojbl.cn/Article/details/gtddswabjk.html

[U43] PHP：声明命名空间
来源：http://dali.hnqzz.top/Article/details/gtebxosbpu.html

namespace App\Http;
来源：http://dali.sufxvd.cn/Article/details/gtabyzwqbw.html

[U44] PHP：开启严格类型
来源：http://dali.tian-w.cn/Article/details/gtenumwops.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtzragcbjn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhixingplan.top/Article/details/gtchjmhxyd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtargdixrd.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtzyusgcvf.html

?string $name = null
来源：http://dali.jinqigfzy.top/Article/details/gtgoissqhh.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gtfqnuzgge.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtknkujzrf.html

[U48] PHP：纯枚举
来源：http://dali.xylfe.cn/Article/details/gtrxydoogd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yuxming.cn/Article/details/gtpxtmdnpf.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtfnvtnbzd.html

public readonly string $name
来源：http://dali.yvedp.cn/Article/details/gtkdkwxbda.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbapgjfd.html

public function __construct(private int $id) {}
来源：http://dali.ybcxt.top/Article/details/gtlrfqshsy.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtqwdlxzna.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtdtjkkgkd.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gtrxwtsgqq.html

$double = fn($x) => $x * 2;
来源：http://dali.daria6918.cn/Article/details/gtzeekrdsm.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtvvpvgeuw.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmrupvds.html

[U54] PHP：空安全调用
来源：http://dali.shzxlz.cn/Article/details/gtflhfpolm.html

$obj?->method()
来源：http://dali.birdmap.top/Article/details/gtmyxpcfos.html

[U55] PHP：match 表达式
来源：http://dali.sweek.top/Article/details/gtyqxiadjy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtdlvuyboi.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtqjwmjolv.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtkjtqffzg.html

[U57] PHP：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtcujqxhnd.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtqfisqfqx.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gtdcjgxgme.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.smart0.xyz/Article/details/gtvklslbyl.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtezncvlsf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sxryk.cn/Article/details/gtvetitsfj.html

[U60] PHP：JSON 编解码
来源：http://dali.hysaishi.cn/Article/details/gtdokkaufl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gthxfrmvgv.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtabzmagvf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiofwbid.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gtpsudzzfa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtaxzydvso.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtalrvwzdv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gtqsvbldos.html

[U64] PHP：目录遍历
来源：http://dali.jinqigufen.top/Article/details/gtglpmxrxk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gtijybylry.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidppuqfh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtwiqoktxo.html

[U66] PHP：设置 Cookie
来源：http://dali.feifeiyinyue.top/Article/details/gtoipoukib.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.hywenlv.cn/Article/details/gtccyfrour.html

[U67] PHP：处理文件上传
来源：http://dali.snrcjt.cn/Article/details/gthzebuerz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gttqzzdtlo.html

[U68] PHP：PDO 连接
来源：http://dali.tianlin.xyz/Article/details/gtrfyntyqa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ivvv.top/Article/details/gtmgdwhtwz.html

[U69] PHP：PDO 预处理
来源：http://dali.smart0.xyz/Article/details/gtmruunexy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gtntvrvipu.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gtbtwkasmv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtensvxbys.html

[U71] PHP：抛出异常
来源：http://dali.meibo888.top/Article/details/gtluauzxha.html

throw new RuntimeException("失败", 500);
来源：http://dali.wangdashe.top/Article/details/gtnygoergl.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gtmaxcrson.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xziqi.cn/Article/details/gtarsdascs.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gtuxtrlfep.html

parse_ini_file("config.ini", true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzhaimmh.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtwndsygxq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.svipenyu.cn/Article/details/gttdnusrou.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtdwaeldtf.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gtragtullt.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gthqckeuxm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zdqjudy.top/Article/details/gtfigbdspy.html

[U77] PHP：模板渲染
来源：http://dali.dashuyun.cn/Article/details/gtsvyzhgtw.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtgbieikmy.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtypwwvxhs.html

composer require --dev phpunit/phpunit
来源：http://dali.yj202588.top/Article/details/gtwasqljcr.html

[U79] PHP：静态分析
来源：http://dali.jqgfzy.top/Article/details/gtzvcdivlg.html

composer require --dev phpstan/phpstan
来源：http://dali.vqdsnc.cn/Article/details/gtrcfdwvaq.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtzcszxkxw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtvyrfgser.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtdipsfxhy.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtbxwjdsjm.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtnfufxkjv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sysykeji.top/Article/details/gtgagmusqf.html


<!-- 参考信息 -->