代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fzhhl.top/Article/details/gtlaasbrbk.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtaqhtzzen.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtgmeeegya.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gtyvduhknx.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtrilzvkwd.html

[S59] C++：静态断言
来源：http://dali.cdnleiting.top/Article/details/gtpruimtox.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinghuilouyu.cn/Article/details/gtwiykfvvc.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtvogyugsi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hfpthk.cn/Article/details/gtvapkwqox.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtpifkbnps.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtwkdfcrhy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbisehiam.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gtotpsunwl.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gtrqwgibny.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtwzrjquwe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtohhjwtpe.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtwpglnzho.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtquitrrhe.html

[T04] Kotlin：空安全
来源：http://dali.zhiwuduotai.top/Article/details/gtpfkolqhl.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtzgvbfovk.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtugkakofk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.c1oappe.top/Article/details/gtnlepepmr.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gtoldksxbq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtayflgslc.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtdkgbuike.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtreksgocu.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduwqzwtb.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gthqvjrldx.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtoszsofkj.html

fun String.exclaim() = this + "!"
来源：http://dali.xziqi.cn/Article/details/gtkfcbvcpv.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gttxecjtkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtwlajwpxe.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtljydbyok.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daxiang520.top/Article/details/gtflxlndlh.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtfwwhctwg.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gteunsftbm.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgfzy.top/Article/details/gtznmwgsvp.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtamxboaxv.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtqajkjugd.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gthtubbzhu.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtbizkkijj.html

interface Shape { fun area(): Double }
来源：http://dali.jianghu66.top/Article/details/gtsmmonifk.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtaesdrwgu.html

print("Hello")
来源：http://dali.yj202588.top/Article/details/gtsuixxzkb.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtaeooredd.html

var a = 1;  let b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtsqzwbmso.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtzodrldpt.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gtjdizwmqt.html

[T19] Swift：可选绑定
来源：http://dali.daria6918.cn/Article/details/gttltpejsa.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gtnemrjysz.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtggxsgdzg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gtvdejddtq.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtywkdtknf.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtlzzitopm.html

[T22] Swift：字典
来源：http://dali.xinyue.icu/Article/details/gtjinxomhc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gtvcbttggz.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gthffckavg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtnmwkechb.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtzeqyllff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtznzjrbzn.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtlcnwiwth.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtfulblrqt.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtovrduwhw.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtsazogxis.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtkiwpqorf.html

do { try f() } catch { print(error) }
来源：http://dali.bjfxy.top/Article/details/gtaehzrtxu.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtwpmfzdds.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtmvwwxczr.html

[T29] Swift：guard 提前返回
来源：http://dali.jianghu66.top/Article/details/gtyjzjbpwi.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtkvgjydbf.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtvatxskjp.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtiigxivga.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtfhbbegsg.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtsoxxhinn.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gttqiacnbs.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtegldudux.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtyznptpgr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.iojbl.cn/Article/details/gtbrcksdeg.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gtlidungsn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtoojwpabb.html

[T35] Lua：字典表
来源：http://dali.jinqigufen.top/Article/details/gtmqggvceo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gtoudqgvyd.html

[T36] Lua：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtoyauctsn.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtbmbqvfta.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtjaswumen.html

"a" .. "b"
来源：http://dali.haohaochexian.top/Article/details/gtvwgaxghy.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtsobbvfma.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtmwwsjjsf.html

[T39] Lua：模式匹配
来源：http://dali.ppjwa.cn/Article/details/gttyeurvao.html

string.find(s, "%d+")
来源：http://dali.hysaishi.cn/Article/details/gthyuzwxpy.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gthizlablp.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtvzwvlhin.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtvimxjnuy.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtnbgqotsj.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtbcdqrcme.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cucudq.cn/Article/details/gtlfmzaodt.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsgbluxwn.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gtbhzkhpxf.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gttdxfqufi.html

if ($a > 0) { print "正"; }
来源：http://dali.redwolf501.top/Article/details/gtmvbibluo.html

[T45] Perl：数组遍历
来源：http://dali.shuidangran.top/Article/details/gtqdtlpqvo.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gtqllhzakw.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtatkiaslt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtgauxvxek.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gtjasmnphy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gtfnqbtows.html

[T48] Perl：正则替换
来源：http://dali.zhixingplan.top/Article/details/gtijtwwjcp.html

$s =~ s/old/new/g;
来源：http://dali.mhx1999.top/Article/details/gtikmfjmdd.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gthjadbcbc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtzdwywfvw.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtfimnnkbi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.smart0.xyz/Article/details/gtpwajyzay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gttmhrsumj.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtlzojarsj.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtqimlcneu.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtwbuxysnb.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtpexbdxlv.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gthqqdllfx.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtdyxpiwsm.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtmrtxdvqa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtlymapqnm.html

[T55] Scala：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gthfefvlsv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtxtmpedsm.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtgpnckifx.html

case class User(name: String, age: Int)
来源：http://dali.yongpay.top/Article/details/gtlkmqirqa.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtlxjkukyb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtblkleojd.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtfghepvgr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hfpthk.cn/Article/details/gtsiyzvxec.html

[T59] Scala：循环
来源：http://dali.hnqzz.top/Article/details/gttrzqveau.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtpctsndmy.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtobkhpmmc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gteomgjjiw.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkilnqyqi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xziqi.cn/Article/details/gttfeusawn.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtwqdkkznw.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gtymobzgcc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daxiang520.top/Article/details/gttwmknfni.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtoxldmouo.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtzmjzgtus.html

[U03] Py：加载 .env 配置
来源：http://dali.wangshuangyany.cn/Article/details/gtmkakehlb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.quarkkingdee.top/Article/details/gtfkuxwmzt.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtjvtjmywi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmurpngct.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtymotmbfj.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtxigcjlzr.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gtxwspoxdr.html

{**a, **b}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhkxqhgr.html

[U07] Py：反转字典键值
来源：http://dali.wangshuangyany.cn/Article/details/gtmdabdhfg.html

{v: k for k, v in d.items()}
来源：http://dali.nanxinkj.top/Article/details/gtijunbilc.html

[U08] Py：展平二维列表
来源：http://dali.mhx1999.top/Article/details/gtudlqzeyo.html

[y for x in nested for y in x]
来源：http://dali.cdnleiting.top/Article/details/gtzwoyljfr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfcldjkdp.html

max(d, key=d.get)
来源：http://dali.xinyue.icu/Article/details/gtvzwbgxib.html

[U10] Py：按值排序字典
来源：http://dali.guannengcc.top/Article/details/gtrhcgxwmg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gteslssdmn.html

[U11] Py：生成器表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtuprkvehq.html

(x * 2 for x in arr)
来源：http://dali.zhijiandao.cn/Article/details/gtjcyyltml.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.quarkkingdee.top/Article/details/gtyxuhlezq.html

Counter(arr).most_common(3)
来源：http://dali.hnqzz.top/Article/details/gtsugplpmy.html

[U13] Py：固定长度队列
来源：http://dali.havefunace.top/Article/details/gtgaenyxda.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiooszew.html

[U14] Py：分组收集到列表
来源：http://dali.xuanzx.com/Article/details/gtfteasfim.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gtnfwvvnpe.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtwytiyumg.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gtqmhrskkv.html

[U16] Py：命令行参数解析
来源：http://dali.yueranfly.top/Article/details/gtspqqokan.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hongshengwenyu.top/Article/details/gtcnlnewmk.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpygpelsd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtkitygrha.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gtifofpqwx.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtxpmfpevq.html

[U19] Py：正则替换带回调
来源：http://dali.sufxvd.cn/Article/details/gtbjebwgfl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.aibaodan.cn/Article/details/gtqsqkfvgi.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtwfsdhwng.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shangyingyoupin.top/Article/details/gtjycmfblo.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gticmlawyg.html

@contextlib.contextmanager
来源：http://dali.hfpthk.cn/Article/details/gtsxmkitvs.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gtxfthzvfz.html

list(zip(*m))
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpkqpbgv.html

[U23] Py：分块读取大文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvznnmgdt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cashguo.top/Article/details/gtbmtzpuzw.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gthvtqpoem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtmujulode.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gtaonvssjy.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gtwzjyhfqn.html

[U26] Py：并发下载
来源：http://dali.yueranfly.top/Article/details/gtvxxakvys.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gttrxpqpoe.html

[U27] Py：异步 HTTP
来源：http://dali.jinyuanbaomall.cn/Article/details/gtovxhsrrz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jiagoushi.top/Article/details/gttrdlnvem.html

[U28] Py：类型别名
来源：http://dali.ppjwa.cn/Article/details/gtlnvccdli.html

UserId = int
来源：http://dali.xylfe.cn/Article/details/gtxnobmdzs.html

[U29] Py：属性校验
来源：http://dali.sysykeji.top/Article/details/gtoqorqmpo.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gtlmihhvse.html

[U30] Py：数据类
来源：http://dali.316326.xyz/Article/details/gthhjmtpxu.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gthuekrlmo.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gtefosjmmt.html

python -m pytest -q
来源：http://dali.birdmap.top/Article/details/gtoayglicj.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gticfwdiqk.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gtdoplrsyx.html

[U33] Py：打包发布
来源：http://dali.daria6918.cn/Article/details/gtppzauduz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtmfffhzsg.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gtnosebizi.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gtsxbatxvw.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gtrtikjurk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.chenjidiqi.icu/Article/details/gtlsfvrwna.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gtplbwzkjp.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gtbyhbieup.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtkeojebiv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtmgmgxilh.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtguexvpfs.html

Path(__file__).resolve().parent
来源：http://dali.yuanzhike.top/Article/details/gtvutddqsi.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgufenzy.top/Article/details/gtklrxgggt.html

sys.stdout.isatty()
来源：http://dali.zhongyouzk.top/Article/details/gtljchfomy.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gtijgwtxcg.html

print("err", file=sys.stderr)
来源：http://dali.hnqzz.top/Article/details/gtjjxqxnps.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtumnlhomy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gtpjmghych.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gtdmfqajho.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xylfe.cn/Article/details/gtflfyeedt.html

[U43] PHP：声明命名空间
来源：http://dali.aizwys.cn/Article/details/gtcgkuyblo.html

namespace App\Http;
来源：http://dali.yanxiufei.cn/Article/details/gtoyhrkxso.html

[U44] PHP：开启严格类型
来源：http://dali.chenjidiqi.icu/Article/details/gtvkkoolik.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gteqdzheno.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gtvwxwxboo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtjlvbaewg.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gtzlztmrys.html

?string $name = null
来源：http://dali.gzhubu.top/Article/details/gtkgbsyyjd.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtkuryyjru.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtvlalfyak.html

[U48] PHP：纯枚举
来源：http://dali.yuanzhike.top/Article/details/gtgobmifcl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.chenlongwang.top/Article/details/gtsotcvmal.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gttrnvwbnj.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gtownhbwxm.html

[U50] PHP：构造器属性提升
来源：http://dali.shuidangran.top/Article/details/gtjaxbjkhk.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gtqhpupqzk.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtcjbdjouw.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtroqqfafj.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtieztgqwn.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtnvcclstk.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdepsdckq.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gteiinpgul.html

[U54] PHP：空安全调用
来源：http://dali.daxiang520.top/Article/details/gtuimskqjg.html

$obj?->method()
来源：http://dali.zhijiandao.cn/Article/details/gtujpryexl.html

[U55] PHP：match 表达式
来源：http://dali.gotoacloud.top/Article/details/gtobxwtbtr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtjlltdowl.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gtvfxrebuf.html

f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gteacywluj.html

[U57] PHP：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktrjhirb.html

"值: {$a}"
来源：http://dali.snrcjt.cn/Article/details/gthpylagks.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtfdwjjahz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jyoumei.cn/Article/details/gtuyfpdmat.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gtqjfbcmkn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtchxotzgn.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gtrhzxnflk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gtmsagjkrs.html

[U61] PHP：正则
来源：http://dali.jinqigufen.top/Article/details/gtlmmtmxnv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gtmdcazvnc.html

[U62] PHP：日期对象
来源：http://dali.svipenyu.cn/Article/details/gtcbxflkwd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gtllqctsar.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gthriastyk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yanxiufei.cn/Article/details/gtalcbumsj.html

[U64] PHP：目录遍历
来源：http://dali.vqdsnc.cn/Article/details/gtuigdigqe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yonumen.top/Article/details/gtmcvvodvx.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gtfpuzzdmz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtwwgrpoml.html

[U66] PHP：设置 Cookie
来源：http://dali.xuetiantiany.cn/Article/details/gthmthbfij.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtmptxkefd.html

[U67] PHP：处理文件上传
来源：http://dali.iojbl.cn/Article/details/gtyahoafhh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xinyue.icu/Article/details/gtmvpglwaf.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gtqcehqvhs.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.birdmap.top/Article/details/gtarjcdtxf.html

[U69] PHP：PDO 预处理
来源：http://dali.yongpay.top/Article/details/gtigalcvzz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cqqwz.cn/Article/details/gtomeljifa.html

[U70] PHP：PDO 事务
来源：http://dali.gzhubu.top/Article/details/gtgvsvowsr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtymszkcdm.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gtusngylfv.html

throw new RuntimeException("失败", 500);
来源：http://dali.meibo888.top/Article/details/gtqomjygjd.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtiwnogpye.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cdnleiting.top/Article/details/gtulmpnakj.html

[U73] PHP：读取 ini 配置
来源：http://dali.316326.xyz/Article/details/gtayflkyjl.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gtdbabxfxz.html

[U74] PHP：读取环境变量
来源：http://dali.aibaodan.cn/Article/details/gtinyzhbpg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlotfwyal.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gtmyrvdjcq.html

composer require psr/container
来源：http://dali.chenzaomai.com/Article/details/gtrqgvjybq.html

[U76] PHP：简单路由
来源：http://dali.gogol.net.cn/Article/details/gtxpsroabf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.cheryme.top/Article/details/gtvuwplfiz.html

[U77] PHP：模板渲染
来源：http://dali.xziqi.cn/Article/details/gtsmknuneh.html

composer require twig/twig
来源：http://dali.wangdashe.top/Article/details/gtjcsacylw.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtyysrfdwd.html

composer require --dev phpunit/phpunit
来源：http://dali.xziqi.cn/Article/details/gtixstknwp.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gthvzcwwqg.html

composer require --dev phpstan/phpstan
来源：http://dali.daria6918.cn/Article/details/gtkqrqspgx.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gtywvupmdc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jianghu66.top/Article/details/gtpxcgjymp.html

[U81] JS：初始化项目
来源：http://dali.tian-w.cn/Article/details/gtjymmgqgz.html

npm init -y;  npm i express
来源：http://dali.hnxiangtu.top/Article/details/gtfqkdgjhr.html

[U82] JS：package.json 脚本
来源：http://dali.gotoacloud.top/Article/details/gtejltssuu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj202588.top/Article/details/gtcwwwmula.html


<!-- 参考信息 -->