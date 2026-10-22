代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.cucudq.cn/Article/details/gtctfmzygu.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gtpzasuhgq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnscffpt.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gtmayhjhnw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtmlcvszyt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtikesgzgs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtqklnjttv.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtzcixugxn.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtbjapwtww.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtijuwgwam.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtuhjmyfum.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigfzy.top/Article/details/gtpnhanpsh.html

[T03] Kotlin：字符串模板
来源：http://dali.xuetiantiany.cn/Article/details/gtpjqlfhij.html

"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gtegeftbms.html

[T04] Kotlin：空安全
来源：http://dali.jqgufenzy.top/Article/details/gttazsrsaj.html

val n: String? = null;  n?.length
来源：http://dali.aibaodan.cn/Article/details/gtwxvpmhpn.html

[T05] Kotlin：when 表达式
来源：http://dali.yangfankeji.com/Article/details/gtrlxvmzcb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gtpgxhrqrr.html

[T06] Kotlin：集合映射
来源：http://dali.tanke756.top/Article/details/gtwszjmply.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gtwodhrpce.html

[T07] Kotlin：集合过滤
来源：http://dali.yuanzhike.top/Article/details/gtrdgittol.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtwhnvmbdn.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtctqjgzsj.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gtslrxikgh.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtotntnjoo.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gtmincatkq.html

[T10] Kotlin：默认参数
来源：http://dali.zycfv.cn/Article/details/gtpuixibuu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gtzgkpeaus.html

[T11] Kotlin：协程
来源：http://dali.havefunace.top/Article/details/gtoqywfzfi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xylfe.cn/Article/details/gtqzkncawv.html

[T12] Kotlin：解构声明
来源：http://dali.tianlin.xyz/Article/details/gtegnclnwy.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzmdcnuzw.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtwemqfjkj.html

val m = mapOf("a" to 1)
来源：http://dali.yangfankeji.com/Article/details/gtkozisopr.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtmpqxszfr.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gteqxoqgoe.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtgzdoholc.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtowiuaerv.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqjtxljdd.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtqkbpvnfr.html

[T17] Swift：变量与常量
来源：http://dali.hongshengwenyu.top/Article/details/gtzxydmgof.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtbglltlgy.html

[T18] Swift：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gttxqcyohu.html

"值: \(b)"
来源：http://dali.zdqjudy.top/Article/details/gtuyllkmue.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtwkkbnkke.html

if let n = opt { print(n) }
来源：http://dali.zycfv.cn/Article/details/gtjqikqzgo.html

[T20] Swift：数组操作
来源：http://dali.sxryk.cn/Article/details/gtqujjfmrd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.iojbl.cn/Article/details/gtxsgqizvw.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtinqhycyo.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gtdoncfmwp.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtuyvmlpbp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtefhxvaeb.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtonyninob.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtdaqvtnan.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gtkvzyetse.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtnyzzelyu.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gthefhyjsa.html

struct P { var x: Int }
来源：http://dali.gogol.net.cn/Article/details/gtgljzpeon.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtjoiwxkje.html

class A: Base { override func f() {} }
来源：http://dali.hfpthk.cn/Article/details/gtbhcyexgd.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtzacrrdyi.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtievwqrgm.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtsueykcvh.html

enum Color { case red, green }
来源：http://dali.zdqjudy.top/Article/details/gtigmzdarn.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtetacnwgm.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtxxvzaxlw.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtmlfiwkkv.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtpjoakjvb.html

[T31] Lua：Hello World
来源：http://dali.guannengcc.top/Article/details/gtzixcislj.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gtdyyfnttx.html

[T32] Lua：局部变量
来源：http://dali.shuidangran.top/Article/details/gttaxsegtt.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtdwguxycx.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gttshmtily.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtkcgveuak.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtezhvctbs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhengqikj.top/Article/details/gtksrfufae.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtiwawyhif.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtlhiosjna.html

[T36] Lua：函数
来源：http://dali.ydzc1.top/Article/details/gtzgruqkzy.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdfbvsxeq.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gtcufnkuiz.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gtfwrohiaz.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtxbpkcgal.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtthtovmju.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtzkacqrjh.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdmkddct.html

[T40] Lua：元表
来源：http://dali.jyoumei.cn/Article/details/gtkbwdtlul.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gtrhdizgdd.html

[T41] Perl：Hello World
来源：http://dali.sysykeji.top/Article/details/gtzzijenvx.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gtqtehczzj.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gthehtrhdj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenjidiqi.icu/Article/details/gtkvlcuzyz.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtmravikqp.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfzwexclw.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gtuvfogatn.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtbpxzpukr.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtgbfswxxf.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtoqlsvlvu.html

[T46] Perl：哈希操作
来源：http://dali.cqqwz.cn/Article/details/gtvcvlskkn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqvpqelxd.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtbannersi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpugovipa.html

[T48] Perl：正则替换
来源：http://dali.shzxlz.cn/Article/details/gtlowsbbmp.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtwlzvfijz.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtswzbavhq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtblhddysy.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtjqlkijji.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gterncdwrr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtjdjiuteb.html

[T51] Scala：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbcnukfq.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtqppotqvv.html

[T52] Scala：变量
来源：http://dali.havefunace.top/Article/details/gtchmhzvim.html

val a = 1;  var b = 2
来源：http://dali.yj20258888.top/Article/details/gtnzgkyaxw.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtmjxgegac.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtocodwqtk.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gtecruyhen.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hammf.cn/Article/details/gtmpetpucb.html

[T55] Scala：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtqmxrjcog.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtntgayiel.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gthdnhxlth.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gthxkomuxv.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtvpazmyht.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbeqeyaof.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtgqjnpkzy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guowangkeji.top/Article/details/gtellsivvq.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gthtmolhew.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbnyngqd.html

[T60] Scala：折叠
来源：http://dali.ybcxt.top/Article/details/gtmhndxksf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gtycclxarj.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtblxbwiog.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtqzjqmfrv.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfoeprrqv.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmzahezoq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtnrepwkdl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtdujjrkvy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gthnwlbepx.html

[U03] Py：加载 .env 配置
来源：http://dali.gzhubu.top/Article/details/gtktnimkyi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtqptlnqsd.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtudnmctka.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yuxming.cn/Article/details/gtaiqemjfm.html

[U05] Py：列表去重且保序
来源：http://dali.yj202588.top/Article/details/gtfqwbgihb.html

list(dict.fromkeys(arr))
来源：http://dali.nwbrower.top/Article/details/gtuvbpxvfl.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtbcrnnptc.html

{**a, **b}
来源：http://dali.xylfe.cn/Article/details/gtvfgckgpl.html

[U07] Py：反转字典键值
来源：http://dali.hnxiangtu.top/Article/details/gtbqhcyniz.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtznurhbgu.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gtrurbquke.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gthblyyvsr.html

[U09] Py：字典取最大值的键
来源：http://dali.zhoulong.xyz/Article/details/gtzbjzupuv.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtbuqrfmiv.html

[U10] Py：按值排序字典
来源：http://dali.shzxlz.cn/Article/details/gtcrnicyfi.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gtfkqccfmq.html

[U11] Py：生成器表达式
来源：http://dali.quarkkingdee.top/Article/details/gtqbiplsgk.html

(x * 2 for x in arr)
来源：http://dali.9152youxi.cn/Article/details/gtbrvfajjv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinqigufen.top/Article/details/gtysgwqqhk.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gteqxqrzmv.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gthsefcdxz.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtukimpdkn.html

[U14] Py：分组收集到列表
来源：http://dali.kuanghao11.cn/Article/details/gtrdbalfpb.html

defaultdict(list)
来源：http://dali.gzhubu.top/Article/details/gtbkexakki.html

[U15] Py：高精度计时
来源：http://dali.jinqigufen.top/Article/details/gtrclxxwjv.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gtwxwldzgp.html

[U16] Py：命令行参数解析
来源：http://dali.jianghu66.top/Article/details/gtxivucaxf.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gogol.net.cn/Article/details/gtlfwjmbkb.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gtoojaemzu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xuanzx.com/Article/details/gtmkglelkg.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gtfaufhvza.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gtbhmsmkcb.html

[U19] Py：正则替换带回调
来源：http://dali.xuetiantiany.cn/Article/details/gtwtqtsryy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gtgfvcfgxb.html

[U20] Py：缓存函数结果
来源：http://dali.hongshengwenyu.top/Article/details/gtdkqwxjkg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuetiantiany.cn/Article/details/gtsaaceufe.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gtkbborllc.html

@contextlib.contextmanager
来源：http://dali.cheryme.top/Article/details/gtpbjwvslt.html

[U22] Py：矩阵转置
来源：http://dali.zhiwuduotai.top/Article/details/gtvtsvzeqg.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gtqcojatgw.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gtjsqfxxeh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj202588.top/Article/details/gtuybxmvln.html

[U24] Py：路径操作
来源：http://dali.snrcjt.cn/Article/details/gtintjtbhm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtiwxfdkoi.html

[U25] Py：CSV 按字典读
来源：http://dali.jinghuilouyu.cn/Article/details/gtvduxkcqa.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gtehhphoai.html

[U26] Py：并发下载
来源：http://dali.andypj.xyz/Article/details/gtpfqnmblh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtlganonso.html

[U27] Py：异步 HTTP
来源：http://dali.yuxming.cn/Article/details/gtlpnhrjyk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yueranfly.top/Article/details/gtddcmkbul.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtnheswldi.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtjktbmrxg.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtebelykge.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtqonudmes.html

[U30] Py：数据类
来源：http://dali.ppjwa.cn/Article/details/gthkvnixhm.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gtwmigmoyk.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtnstodkiw.html

python -m pytest -q
来源：http://dali.cheryme.top/Article/details/gtcercuggg.html

[U32] Py：代码格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnozniotk.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gtilpldsnb.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtxiifvheu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gtpxbakhbg.html

[U34] Py：判断编码
来源：http://dali.shzxlz.cn/Article/details/gttyqtwltj.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtmxaskorz.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gtthxfthpl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gturhmtkyz.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gtsstvpemk.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gtcghbjwrl.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gteukzfgcs.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zhiwuduotai.top/Article/details/gtejoihqit.html

[U38] Py：获取脚本所在目录
来源：http://dali.0kj1m.cn/Article/details/gtuwxzxlao.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gtnzaugmbj.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gtsejtpbtc.html

sys.stdout.isatty()
来源：http://dali.nanxuanxn.top/Article/details/gtplvdmkmj.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtunrrcrth.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtlaehwssl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gtxyzpzcpc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gtursnluph.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuanzhike.top/Article/details/gtgxzskunz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangdashe.top/Article/details/gthplswkwb.html

[U43] PHP：声明命名空间
来源：http://dali.zhijiandao.cn/Article/details/gtmmbvplyr.html

namespace App\Http;
来源：http://dali.shuidangran.top/Article/details/gtyczpfkse.html

[U44] PHP：开启严格类型
来源：http://dali.shangyingyoupin.top/Article/details/gtlyaxvppr.html

declare(strict_types=1);
来源：http://dali.hnqzz.top/Article/details/gtijuwhvsh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtekpllqbr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtplzxjkas.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtndfdhmbl.html

?string $name = null
来源：http://dali.andypj.xyz/Article/details/gtrijwferp.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gthsiumvqo.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gtefhppohm.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtxlcbabua.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gtldlijczk.html

[U49] PHP：只读属性
来源：http://dali.nwbrower.top/Article/details/gtaltgwwbj.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtnfaudnkr.html

[U50] PHP：构造器属性提升
来源：http://dali.yj20258.top/Article/details/gtwxdsxjaf.html

public function __construct(private int $id) {}
来源：http://dali.zhengqikj.top/Article/details/gtpnbqzprn.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtncpwbgkx.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtzzfcnzrt.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gtoherualb.html

$double = fn($x) => $x * 2;
来源：http://dali.chenjidiqi.icu/Article/details/gtgaxvkogc.html

[U53] PHP：空合并运算符
来源：http://dali.xuanzx.com/Article/details/gtrrmqykvd.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gtxfwvsxvu.html

[U54] PHP：空安全调用
来源：http://dali.daria6918.cn/Article/details/gtvzzlzitg.html

$obj?->method()
来源：http://dali.jinqigufen.top/Article/details/gtakiqynnw.html

[U55] PHP：match 表达式
来源：http://dali.cucudq.cn/Article/details/gtdckdwokc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtrijbrvxk.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gtgsxlgmtj.html

f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtocqrwhoo.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtebakmvkf.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gtlscnqoab.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gtxhwsmamp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gtblfdozxr.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gtvytdioxi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sysykeji.top/Article/details/gtugaodzrj.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtwsewlxmo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.meibo888.top/Article/details/gtqtoftzoh.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtwxxedbvu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gtezougckv.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwgcnqgj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigfzy.top/Article/details/gtblntssuo.html

[U63] PHP：文件读写
来源：http://dali.gotoacloud.top/Article/details/gtwwhujpjr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gtmrqoptix.html

[U64] PHP：目录遍历
来源：http://dali.chenlongwang.top/Article/details/gtkwzxebhh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gtfnletqmf.html

[U65] PHP：会话
来源：http://dali.ehwqpu.com/Article/details/gtsmrjufiv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gtfiazzzfn.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtlcnkkglk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gtjhowzplc.html

[U67] PHP：处理文件上传
来源：http://dali.wangshuangyany.cn/Article/details/gtvfgadzom.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aibaodan.cn/Article/details/gtjpegbzwr.html

[U68] PHP：PDO 连接
来源：http://dali.xuetiantiany.cn/Article/details/gtqbwqhawz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gzhubu.top/Article/details/gtpmpwozqq.html

[U69] PHP：PDO 预处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpylcnmb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtqslnykfq.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gtykgmzhhs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gtmlyxtasr.html

[U71] PHP：抛出异常
来源：http://dali.gogol.net.cn/Article/details/gtblogvytx.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gtunsvechp.html

[U72] PHP：写错误日志
来源：http://dali.shzxlz.cn/Article/details/gtpkatzhdg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gzhubu.top/Article/details/gtgjukumfo.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gtzhsmihrc.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gtzzehhvzv.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gtksrqwrdm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dashuyun.cn/Article/details/gtcbyzjamg.html

[U75] PHP：依赖注入
来源：http://dali.gzhubu.top/Article/details/gtjzvaiuht.html

composer require psr/container
来源：http://dali.hongshengwenyu.top/Article/details/gtbavwkpod.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gtnoqkkopq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtadveaajg.html

[U77] PHP：模板渲染
来源：http://dali.jiagoushi.top/Article/details/gtgmtivmwf.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtnfmivyme.html

[U78] PHP：单元测试
来源：http://dali.fengsongda.top/Article/details/gtacdmxoja.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmqviqydu.html

[U79] PHP：静态分析
来源：http://dali.cqqwz.cn/Article/details/gtqifjydot.html

composer require --dev phpstan/phpstan
来源：http://dali.fzhhl.top/Article/details/gtevhmqfme.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gtrkyogify.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zycfv.cn/Article/details/gtbupeojuo.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gtuyxoepiz.html

npm init -y;  npm i express
来源：http://dali.zhaomingkeji.xyz/Article/details/gttponxpbu.html

[U82] JS：package.json 脚本
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmumpokl.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtaxlcqxuf.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtvzqcjavq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gteyvlhnik.html

[U84] JS：CommonJS 写法
来源：http://dali.sysykeji.top/Article/details/gtrauvmpvo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cdnleiting.top/Article/details/gtcglmaqcc.html


<!-- 参考信息 -->