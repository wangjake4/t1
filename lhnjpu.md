代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtgrrgswzn.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gtuyrlgizn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gtdjkasgaa.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtvjagipjd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtqcawadfj.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtlvqhcaks.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtyvyrxjhr.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtgfajdoln.html

[T01] Kotlin：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtoisdfcnm.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtdevplqrn.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtkrjitwrb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtwghrsqqy.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtkcfrxmcc.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzinquxtw.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtlsqlthvu.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtklkdkjsq.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtjqfyratp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtyrpqqblw.html

[T06] Kotlin：集合映射
来源：http://dali.chenzaomai.com/Article/details/gthkqsilbp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gthvsqycjd.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtoqawhcsd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrrhtsxy.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtmpwqqqsg.html

data class User(val name: String, val age: Int)
来源：http://dali.yvedp.cn/Article/details/gtrnybwqbi.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjooujyxx.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtraqxkucl.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtsrxxjpif.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtypexuloe.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtvxlrrkeo.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenjidiqi.icu/Article/details/gtnztbwysq.html

[T12] Kotlin：解构声明
来源：http://dali.wangshuangyany.cn/Article/details/gtzwejqqvb.html

val (a, b) = Pair(1, 2)
来源：http://dali.tanke756.top/Article/details/gtorhmfgxe.html

[T13] Kotlin：只读 Map
来源：http://dali.xuetiantiany.cn/Article/details/gttymxpnmc.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gtxqczoomh.html

[T14] Kotlin：循环
来源：http://dali.cqqwz.cn/Article/details/gtrdxkwhwr.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtmnikjdcl.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gtoxfbgbml.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtqvpwogwd.html

[T16] Swift：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtzsuduwra.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtwnkkwymy.html

[T17] Swift：变量与常量
来源：http://dali.jinqigfzy.top/Article/details/gtjglfzvzl.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtnbidudhe.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtturwzldw.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtmvpmcrmu.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtfirnqpig.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtfqdtdtos.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtgelatkjq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yonumen.top/Article/details/gtenckhzfo.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gtddvbgazs.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtgqmwitqe.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtzssimzea.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.svipenyu.cn/Article/details/gttfybjrba.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtzczbdarx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtenvxroma.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtkksixvgs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtxheoshlj.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtaehjqbcl.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtbmrjwqjz.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gtlicqlgtc.html

class A: Base { override func f() {} }
来源：http://dali.yuxming.cn/Article/details/gthpopqjad.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtsbqofxyj.html

do { try f() } catch { print(error) }
来源：http://dali.ydzc1.top/Article/details/gtfwyomvim.html

[T28] Swift：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtiogflxqw.html

enum Color { case red, green }
来源：http://dali.chenjidiqi.icu/Article/details/gtojvlishb.html

[T29] Swift：guard 提前返回
来源：http://dali.sysykeji.top/Article/details/gtrzgbjjow.html

guard let x = opt else { return }
来源：http://dali.xuetiantiany.cn/Article/details/gtbdhxycnf.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gtatgedbcv.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtznnuvfcf.html

[T31] Lua：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtzreipuxn.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtrmruszvm.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtladqxapg.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gtldtkziea.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtajowwibl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtbzaqhoiv.html

[T34] Lua：遍历表
来源：http://dali.yanxiufei.cn/Article/details/gtrdgnfpgl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtfdozkzzj.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtftegcwdp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.aizwys.cn/Article/details/gtvkjdwnlu.html

[T36] Lua：函数
来源：http://dali.shzxlz.cn/Article/details/gtlmafuvfd.html

function add(a, b) return a + b end
来源：http://dali.daxiang520.top/Article/details/gtzdledsse.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtvtxrzgcc.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtidofhvzn.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtdyfxeswl.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gthbrbuchj.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtchqngnpk.html

string.find(s, "%d+")
来源：http://dali.aizwys.cn/Article/details/gtyemsehdk.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gtjbfnhuyp.html

setmetatable({}, { __index = base })
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcjlrflmi.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtgubdbauo.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtubipbjqx.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtgyjxflhs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zycfv.cn/Article/details/gtelmxcjpk.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtkukqbwlx.html

"值: $a"
来源：http://dali.jiagoushi.top/Article/details/gtgcvxbtjj.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtidpwvwpr.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtuanukklh.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuejdmom.html

for my $x (@arr) { print $x; }
来源：http://dali.hysaishi.cn/Article/details/gteicivpbh.html

[T46] Perl：哈希操作
来源：http://dali.c1oappe.top/Article/details/gtpeqeudof.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fengsongda.top/Article/details/gtwzchuzul.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtqrjamxxf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gotoacloud.top/Article/details/gtaxpcoggj.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtlbpplnzj.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtsjsftrpn.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtzgxtjbtg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtbifsdyfd.html

[T50] Perl：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtjsuutrlp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtmatpktxi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtdkvpsrlu.html

[T51] Scala：Hello World
来源：http://dali.ybcxt.top/Article/details/gtxjwgxsbo.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyizvwez.html

[T52] Scala：变量
来源：http://dali.cheryme.top/Article/details/gtazdvlenk.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtasapnpqk.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtvyswnlxr.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtqpwdbtph.html

[T54] Scala：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtsxpcagrk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtqsvojezr.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtatbihobn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gtbgsrowbc.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswohexru.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpcrjxkb.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtzvfipxya.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtdvaduxvd.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtnkepeopr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sysykeji.top/Article/details/gtahsiaelc.html

[T59] Scala：循环
来源：http://dali.jinqigfzy.top/Article/details/gtstggbpgf.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtvqpivywo.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtbefrzqeo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gtjqmvyfhd.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtyvmdcjvv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtyezpvzhd.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtgftfyyji.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtnfjrfniu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gttcvatnsc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtqeyiynjm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtvvsadwcl.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtknzjslps.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtoixmmajr.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gtepfduied.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtxajdomqz.html

[U05] Py：列表去重且保序
来源：http://dali.daxiang520.top/Article/details/gtdarpxxou.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtczdhwlki.html

[U06] Py：合并两个字典
来源：http://dali.bjfxy.top/Article/details/gtobvumbwt.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtfmxpxozi.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtmibwbpxg.html

{v: k for k, v in d.items()}
来源：http://dali.shzxlz.cn/Article/details/gtyxrsoutk.html

[U08] Py：展平二维列表
来源：http://dali.ppjwa.cn/Article/details/gtzfmbknwk.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gtthuauqev.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtxgvuhzxo.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtjyhyfifp.html

[U10] Py：按值排序字典
来源：http://dali.jinqigfzy.top/Article/details/gtdebysbmn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtrtncecyq.html

[U11] Py：生成器表达式
来源：http://dali.shzxlz.cn/Article/details/gtxwgjfjgz.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtsppjpltk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtptpaicsa.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtggrgcawp.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gtlaantidi.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtfsvkqzzp.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gtogykgmjf.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtrnpgwljy.html

[U15] Py：高精度计时
来源：http://dali.yongpay.top/Article/details/gtdrcidnbv.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtzxxqgrbq.html

[U16] Py：命令行参数解析
来源：http://dali.bjfxy.top/Article/details/gtvvncbgiq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtdrtreqdf.html

[U17] Py：初始化日志
来源：http://dali.ehwqpu.com/Article/details/gtrqvxvuez.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cqqwz.cn/Article/details/gtfurkucpu.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gtntmmranm.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtlbnlsyaq.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gtnbtkqgsu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yanxiufei.cn/Article/details/gtycxvidjc.html

[U20] Py：缓存函数结果
来源：http://dali.tanke756.top/Article/details/gtlwkacgrv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cashguo.top/Article/details/gtzflapzdt.html

[U21] Py：自定义上下文管理器
来源：http://dali.316326.xyz/Article/details/gtfmdvgefy.html

@contextlib.contextmanager
来源：http://dali.cdnleiting.top/Article/details/gtmphsmmoh.html

[U22] Py：矩阵转置
来源：http://dali.aizwys.cn/Article/details/gtbwzuojep.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtyhvozyks.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gtvmxmquuc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.birdmap.top/Article/details/gtslybtfqj.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtrksueznx.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtclebufni.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gtninndxnx.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtxqgncncj.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtbwupwsaw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtbyfewmma.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkusesyud.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtzfyqiznc.html

[U28] Py：类型别名
来源：http://dali.smart0.xyz/Article/details/gtpehlyqty.html

UserId = int
来源：http://dali.ybcxt.top/Article/details/gttfftllir.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gteoodcudk.html

@property 与 @x.setter 配合
来源：http://dali.yuxming.cn/Article/details/gtftdnqvei.html

[U30] Py：数据类
来源：http://dali.hammf.cn/Article/details/gtyqsydklq.html

@dataclass(slots=True)
来源：http://dali.ivvv.top/Article/details/gtamiuxxdk.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtcdibclog.html

python -m pytest -q
来源：http://dali.snrcjt.cn/Article/details/gtqkgthyzu.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtpmvwbynl.html

ruff format . && ruff check --fix .
来源：http://dali.gaohongyu789.top/Article/details/gtuapgnbbp.html

[U33] Py：打包发布
来源：http://dali.yonumen.top/Article/details/gtvzssnelj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtlzoaejbh.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtgsnbctpl.html

chardet.detect(raw)
来源：http://dali.gzhubu.top/Article/details/gttpfgdced.html

[U35] Py：发送邮件
来源：http://dali.pengpengdd.cyou/Article/details/gtztluxwoa.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gtbgadfqda.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gtgsonfyli.html

schedule.every(10).minutes.do(job)
来源：http://dali.dashuyun.cn/Article/details/gtqmpfuajj.html

[U37] Py：读写 Excel
来源：http://dali.jinqigufen.top/Article/details/gtcslqnjie.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shangyingyoupin.top/Article/details/gtwmgmjlqs.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjirfevk.html

Path(__file__).resolve().parent
来源：http://dali.0kj1m.cn/Article/details/gtcqnreygx.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gtxngskehl.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtkwnqdjex.html

[U40] Py：打印到标准错误
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvukjljcw.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtecflalhv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sxryk.cn/Article/details/gtfctqhujf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gtljvspeti.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gogol.net.cn/Article/details/gtqqtjrjdt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtckzovfof.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtlhqkcpei.html

namespace App\Http;
来源：http://dali.tian-w.cn/Article/details/gtoixdvwuo.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gtfctjktil.html

declare(strict_types=1);
来源：http://dali.zhengqikj.top/Article/details/gtuhbfnmaw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hywenlv.cn/Article/details/gthsvrosya.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gtqtnoggmb.html

[U46] PHP：可空类型
来源：http://dali.c1oappe.top/Article/details/gtvfmutsxv.html

?string $name = null
来源：http://dali.zhiwuduotai.top/Article/details/gttjsjqgey.html

[U47] PHP：联合类型
来源：http://dali.yangfankeji.com/Article/details/gtlpxrgbhj.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gtrlocfzny.html

[U48] PHP：纯枚举
来源：http://dali.birdmap.top/Article/details/gtswflyrbb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gtgjpsthwg.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gtyuhikezf.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gtufbpfjcs.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokovquab.html

public function __construct(private int $id) {}
来源：http://dali.jiagoushi.top/Article/details/gtryoqxiqk.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtnttjxmgl.html

[$a, $b] = $arr;
来源：http://dali.tianlin.xyz/Article/details/gtspuvrktw.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtqfjwiibu.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gtwjnvwqkf.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtkonvruqd.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtujgbhqrb.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtsnnmenjj.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gtxmyyrnxp.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtmizqelca.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gtfhwqzqai.html

[U56] PHP：命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtncuhcvzk.html

f(a: 1, b: 2)
来源：http://dali.316326.xyz/Article/details/gtxgstucvj.html

[U57] PHP：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgqidgibu.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gtjcjnmzxu.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gtxddpkwcm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gtbkzhxuba.html

[U59] PHP：自定义排序
来源：http://dali.chenzaomai.com/Article/details/gtfpsdufzp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtahiqpqyk.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gtsvvexqok.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gteaunxljc.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdnfnfij.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.sysykeji.top/Article/details/gtypvhrxco.html

[U62] PHP：日期对象
来源：http://dali.cashguo.top/Article/details/gtgpfgxhft.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj20258888.top/Article/details/gtbngtnxij.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtdfbfglwm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuxming.cn/Article/details/gtxezdlskz.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gtvumsdjmy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gtfcuxobxo.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gtmrsmtffi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtbtlhynvx.html

[U66] PHP：设置 Cookie
来源：http://dali.ppjwa.cn/Article/details/gtbbkbehyw.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aibaodan.cn/Article/details/gtbroqxblf.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gthstozsow.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xylfe.cn/Article/details/gtlmhyqhge.html

[U68] PHP：PDO 连接
来源：http://dali.hammf.cn/Article/details/gtcfbciitv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.haohaochexian.top/Article/details/gtfexeacmc.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtcaivmgys.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtrtacmvyh.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtabwjiexx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorlkofhf.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtibiqyqpy.html

throw new RuntimeException("失败", 500);
来源：http://dali.daxiang520.top/Article/details/gthalubold.html

[U72] PHP：写错误日志
来源：http://dali.yuanzhike.top/Article/details/gtbcsrcqik.html

error_log("失败: " . $e->getMessage());
来源：http://dali.c1oappe.top/Article/details/gtjeorkeqy.html

[U73] PHP：读取 ini 配置
来源：http://dali.tanke756.top/Article/details/gtojlclsuq.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gtbxpyaqje.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtqyztwstb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtipqotjqx.html

[U75] PHP：依赖注入
来源：http://dali.tian-w.cn/Article/details/gtrktnvkyp.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtwbkkngjt.html

[U76] PHP：简单路由
来源：http://dali.yuanzhike.top/Article/details/gtcmfjdgmw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gtjcfgosua.html

[U77] PHP：模板渲染
来源：http://dali.zycfv.cn/Article/details/gtsppphrer.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtomzkzkgr.html

[U78] PHP：单元测试
来源：http://dali.zdqjudy.top/Article/details/gteyblgqlh.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gtcplujxuu.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gtligmqmib.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtskunusjz.html

[U80] PHP：代码规范修复
来源：http://dali.guannengcc.top/Article/details/gtlhtnrsfc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtzewxyobx.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gtrictplle.html

npm init -y;  npm i express
来源：http://dali.hammf.cn/Article/details/gtplcbfwtm.html

[U82] JS：package.json 脚本
来源：http://dali.hnqzz.top/Article/details/gtvteozwnk.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhoulong.xyz/Article/details/gtlqznqedk.html

[U83] JS：ES Module 导入导出
来源：http://dali.yangfankeji.com/Article/details/gtjulbeaqm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtmkhnhgjo.html

[U84] JS：CommonJS 写法
来源：http://dali.xziqi.cn/Article/details/gtpxlumkvv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.fengsongda.top/Article/details/gtnizqcsrh.html


<!-- 参考信息 -->