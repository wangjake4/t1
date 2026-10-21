代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtkjzljorq.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtdlivugxa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hammf.cn/Article/details/gtrvjawtfs.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtptrwkqxc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gthcutbhin.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpixswtsx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtgqzkobpm.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbqsyuwsu.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtpmepghzp.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gthdnszodq.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtvnynupna.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.feifeiyinyue.top/Article/details/gtcrnzxozr.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtjimpsyxk.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtmlubbgpp.html

[T04] Kotlin：空安全
来源：http://dali.sweek.top/Article/details/gtiwicoqzc.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtcgznqcag.html

[T05] Kotlin：when 表达式
来源：http://dali.zhongyouzk.top/Article/details/gtiespjzdu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtnvzqqstk.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtzjcdfwya.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.0kj1m.cn/Article/details/gtmfmobnck.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtskqkfamw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtvmdwifyr.html

[T08] Kotlin：数据类
来源：http://dali.shzxlz.cn/Article/details/gttbxcpocg.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtbasdhrsy.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtyqgqfgew.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gtqtkutmdj.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtfkpfugja.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xziqi.cn/Article/details/gtewqrannc.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gthpqylnjd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtpyyokzer.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtbgdyxdgu.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtutpdddxp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtdlvcxmad.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtugjhbbds.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuudjgouv.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtufhslruw.html

[T15] Kotlin：接口
来源：http://dali.ehwqpu.com/Article/details/gtqejmcquu.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gtccapcjbc.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtqptadgtu.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtqprrcara.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtpndidgcj.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtalottftj.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfpgenjqs.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gthobzygdi.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtzakqfily.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtyvaqjfea.html

[T20] Swift：数组操作
来源：http://dali.zhijiandao.cn/Article/details/gttsjdsulw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gtongowiqv.html

[T21] Swift：遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcsiunjvg.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtszmegxmu.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gtflkmgbvj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtcwlyvilw.html

[T23] Swift：函数
来源：http://dali.aizwys.cn/Article/details/gtkmlclkrx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gzhubu.top/Article/details/gtvtiqrjzj.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gtjofgeojc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gtqlzvdbcp.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtlqbdlyop.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtrafjrsiq.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtthljyfjz.html

class A: Base { override func f() {} }
来源：http://dali.xziqi.cn/Article/details/gtmsgmfsft.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gtxrleiimq.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gtikkzybtj.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtryifckln.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtzdcckcer.html

[T29] Swift：guard 提前返回
来源：http://dali.nwbrower.top/Article/details/gtdcvdarjj.html

guard let x = opt else { return }
来源：http://dali.0kj1m.cn/Article/details/gtqofrrbzu.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtoxkmeoje.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtyyddycek.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gtyjfnhuqq.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtcjvccvsw.html

[T32] Lua：局部变量
来源：http://dali.dashuyun.cn/Article/details/gtnqkhvwgl.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gtwyvwbzfx.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtecfrmxnc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtyxgrhgok.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtsyuqfbzu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtghzandol.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtuubnqmdv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj202588.top/Article/details/gtiehsnazb.html

[T36] Lua：函数
来源：http://dali.svipenyu.cn/Article/details/gtxirpwaad.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtmvvnuujk.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtpgnrfxxu.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtaxvjpvko.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gthtjgucca.html

if x > 0 then print("正") end
来源：http://dali.havefunace.top/Article/details/gtmtcbtfxu.html

[T39] Lua：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtvjlqjyqo.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtcjmikrib.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtcwtpplaw.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtmbrnrgge.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gtyttwbwnm.html

print "Hello\n";
来源：http://dali.xziqi.cn/Article/details/gtjtaqpueo.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtvdqhsdyj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtserefpvf.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gtuunduyds.html

"值: $a"
来源：http://dali.guowangkeji.top/Article/details/gtkslalmib.html

[T44] Perl：条件
来源：http://dali.kuanghao11.cn/Article/details/gtinnpfihz.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtpjgcexnf.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtqbsjnuza.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtukltlamn.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtljqfiwzs.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sysykeji.top/Article/details/gtjuaoaygh.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtlapvcvkw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hysaishi.cn/Article/details/gtdvzywxdz.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtpnikjazx.html

$s =~ s/old/new/g;
来源：http://dali.zhengqikj.top/Article/details/gtpruoohwu.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtesxaxjib.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtazuxzbsk.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtozcrqbzi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxggrywc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cdnleiting.top/Article/details/gtzxkmjzyn.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtuvyamneu.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtomyzoixg.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gtqfsqxrpc.html

val a = 1;  var b = 2
来源：http://dali.xinyue.icu/Article/details/gtbskjqzqd.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtuyupzfte.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtldulzmzh.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtdgbrbznc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gttxwuqndg.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtmpdbumca.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtybyezqvx.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtrrsssoil.html

case class User(name: String, age: Int)
来源：http://dali.guannengcc.top/Article/details/gtmlucrbps.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtluflzdhd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtuyhsjidt.html

[T58] Scala：函数定义
来源：http://dali.yangfankeji.com/Article/details/gtxiehqzvp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtzboyskvp.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gtqmljdvgy.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtqvpqptud.html

[T60] Scala：折叠
来源：http://dali.hywenlv.cn/Article/details/gtccmyircs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hammf.cn/Article/details/gtpyezivme.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpuicgatm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gtysmbthpq.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtnedpyvuv.html

[U01] Py：创建虚拟环境
来源：http://dali.ybcxt.top/Article/details/gtjbjesvdf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jyoumei.cn/Article/details/gtkpphzoip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtybxzxfru.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gtuwrxffuz.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gttziifqdk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtdqextamr.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtyufhmjrw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvncbsmtc.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtiwxinzhr.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtqxlegbgu.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtwcykrgpq.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtszmullzg.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gtmjuwlpee.html

{v: k for k, v in d.items()}
来源：http://dali.zhongyouzk.top/Article/details/gtevdfpmxw.html

[U08] Py：展平二维列表
来源：http://dali.zhengqikj.top/Article/details/gtuwijlzaz.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gtyziqrhnd.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gtlyukrtdd.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtfrseezwz.html

[U10] Py：按值排序字典
来源：http://dali.redwolf501.top/Article/details/gtkjwdkvxa.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hnxiangtu.top/Article/details/gttnhncidb.html

[U11] Py：生成器表达式
来源：http://dali.yj20258.top/Article/details/gtkriowfcv.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gtblqevhfg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtkkqbxtyy.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gtbmtichqq.html

[U13] Py：固定长度队列
来源：http://dali.xziqi.cn/Article/details/gtihwrrjou.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtinmejwtk.html

[U14] Py：分组收集到列表
来源：http://dali.dianchejie.cn/Article/details/gtxkpizweb.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gtnkwtvxnt.html

[U15] Py：高精度计时
来源：http://dali.xuanzx.com/Article/details/gtbuitpatj.html

t = time.perf_counter()
来源：http://dali.sweek.top/Article/details/gtolhtmemc.html

[U16] Py：命令行参数解析
来源：http://dali.nanxuanxn.top/Article/details/gtrfqfqgxv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtvdyudygf.html

[U17] Py：初始化日志
来源：http://dali.hammf.cn/Article/details/gtkeegmrue.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtvflxzoyx.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtyawoljhb.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtzttaqanh.html

[U19] Py：正则替换带回调
来源：http://dali.hywenlv.cn/Article/details/gttholoxaq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtyzjktpdk.html

[U20] Py：缓存函数结果
来源：http://dali.yuanzhike.top/Article/details/gtlmqkhemk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gtoprmooui.html

[U21] Py：自定义上下文管理器
来源：http://dali.jiagoushi.top/Article/details/gtoudpozpb.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gttysoqtwe.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gtifuahwvc.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtveuyuogj.html

[U23] Py：分块读取大文件
来源：http://dali.sweek.top/Article/details/gtrnwbersl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gttcdepzkr.html

[U24] Py：路径操作
来源：http://dali.dashuyun.cn/Article/details/gtkflutuvu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gtrjaowobx.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gteyjfmrml.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtkhnteabi.html

[U26] Py：并发下载
来源：http://dali.nwbrower.top/Article/details/gtjbyjruud.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aizwys.cn/Article/details/gtdktcixfr.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gtuhsgskhc.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gtyhzixnyp.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gttjqjpltb.html

UserId = int
来源：http://dali.yuanzhike.top/Article/details/gtckzvvqjv.html

[U29] Py：属性校验
来源：http://dali.wangdashe.top/Article/details/gtklmmfbit.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gthutmpydd.html

[U30] Py：数据类
来源：http://dali.9152youxi.cn/Article/details/gtkvlwmxjg.html

@dataclass(slots=True)
来源：http://dali.zhongyouzk.top/Article/details/gteaqoutai.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtpaanghii.html

python -m pytest -q
来源：http://dali.yuxming.cn/Article/details/gttiwdbdif.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtxchizjgm.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258888.top/Article/details/gtlnxnkqrs.html

[U33] Py：打包发布
来源：http://dali.wangshuangyany.cn/Article/details/gtggsoexcq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gthxsypitf.html

[U34] Py：判断编码
来源：http://dali.havefunace.top/Article/details/gtcboaoyzp.html

chardet.detect(raw)
来源：http://dali.hywenlv.cn/Article/details/gttajbetfh.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gtoiwwlsgy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuetiantiany.cn/Article/details/gturxlttwn.html

[U36] Py：定时任务
来源：http://dali.tanke756.top/Article/details/gtbmvzamsj.html

schedule.every(10).minutes.do(job)
来源：http://dali.0kj1m.cn/Article/details/gtqibegnng.html

[U37] Py：读写 Excel
来源：http://dali.mhx1999.top/Article/details/gtrnvtijus.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gtbmymzryd.html

[U38] Py：获取脚本所在目录
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinzxwaeh.html

Path(__file__).resolve().parent
来源：http://dali.daria6918.cn/Article/details/gtbtoesjws.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtnbdrsmdc.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtqkkqyqhn.html

[U40] Py：打印到标准错误
来源：http://dali.0kj1m.cn/Article/details/gtpmervsnn.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gtosxuiyto.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtwuedjaen.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hongshengwenyu.top/Article/details/gtkcehkomi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhengqikj.top/Article/details/gtcrwrpejr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtruiqvnim.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gtdyjuffyk.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtczjwycap.html

[U44] PHP：开启严格类型
来源：http://dali.jlsjyb.cn/Article/details/gtpputjzur.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtbqoamsyj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigfzy.top/Article/details/gtphgnmjwc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaovpyrqw.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gtspoodyoo.html

?string $name = null
来源：http://dali.snrcjt.cn/Article/details/gtirizfhgs.html

[U47] PHP：联合类型
来源：http://dali.jinqigufen.top/Article/details/gthwwzrxyn.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtckmytrnb.html

[U48] PHP：纯枚举
来源：http://dali.hnxiangtu.top/Article/details/gtdjcvodge.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gtjtthhppq.html

[U49] PHP：只读属性
来源：http://dali.yuxming.cn/Article/details/gtvsjahajs.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gtevdchzza.html

[U50] PHP：构造器属性提升
来源：http://dali.xziqi.cn/Article/details/gtlnimejaz.html

public function __construct(private int $id) {}
来源：http://dali.birdmap.top/Article/details/gteiuvnfib.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gthcbkcbdg.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtybmvbzlc.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gttwibgeep.html

$double = fn($x) => $x * 2;
来源：http://dali.sysykeji.top/Article/details/gtdzamgzhi.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gtcerpxemv.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtcuszqgaj.html

[U54] PHP：空安全调用
来源：http://dali.gotoacloud.top/Article/details/gtddaxrogx.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtvttqexzo.html

[U55] PHP：match 表达式
来源：http://dali.tianlin.xyz/Article/details/gtasjryqof.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.kuanghao11.cn/Article/details/gtilcvknbg.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtoiziotzf.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtmezmdppq.html

[U57] PHP：字符串插值
来源：http://dali.birdmap.top/Article/details/gtdnfscurb.html

"值: {$a}"
来源：http://dali.guowangkeji.top/Article/details/gtqwemjsfm.html

[U58] PHP：数组三件套
来源：http://dali.zhijiandao.cn/Article/details/gtvcmqrgaa.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhnccsxh.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gtxjpbrgzo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aizwys.cn/Article/details/gtfgpwxirf.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtrguzvior.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gtkkgtfola.html

[U61] PHP：正则
来源：http://dali.bjfxy.top/Article/details/gttspudgbw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ehwqpu.com/Article/details/gtskjihfnl.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gtroroiybg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gthddoxffg.html

[U63] PHP：文件读写
来源：http://dali.jinqigfzy.top/Article/details/gtdeerlxep.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gtzjbpjpkt.html

[U64] PHP：目录遍历
来源：http://dali.jqgufenzy.top/Article/details/gtufmrsmvr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tianlin.xyz/Article/details/gtlzloqsgf.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtgpgkcqyd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtgndmawyh.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtkjsykxjm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gticgtbgah.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gthyvxjciz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangtech.top/Article/details/gteoijboyn.html

[U68] PHP：PDO 连接
来源：http://dali.gogol.net.cn/Article/details/gtiyfnheag.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gtbiutbkfw.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gtmlfuumyu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtewmtsnig.html

[U70] PHP：PDO 事务
来源：http://dali.shuidangran.top/Article/details/gtnrpvuhsc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtqnyspbtp.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gtzhctezhe.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtbpsbmomc.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gtbegsncyl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangshuangyany.cn/Article/details/gtivuegomy.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtiinqookb.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gtfkzlgtpa.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtdtbrufsv.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtntmovdvb.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtbyxnoagc.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gtpdmjwiqh.html

[U76] PHP：简单路由
来源：http://dali.yongpay.top/Article/details/gtutzxekxk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.mhx1999.top/Article/details/gtdcytpeht.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gtcjoazhaw.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gtnrjrsvdr.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtmmihpepj.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gtbtxzydat.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gthffgudue.html

composer require --dev phpstan/phpstan
来源：http://dali.shzxlz.cn/Article/details/gtgoehxdph.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtuljfrzyi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.shangyingyoupin.top/Article/details/gthgdgrxab.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtrwnhwexe.html

npm init -y;  npm i express
来源：http://dali.chenzaomai.com/Article/details/gtespvwkoj.html

[U82] JS：package.json 脚本
来源：http://dali.aizwys.cn/Article/details/gtzwgxwmjt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gtbtlyirzk.html

[U83] JS：ES Module 导入导出
来源：http://dali.316326.xyz/Article/details/gtqtqgooxf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ybcxt.top/Article/details/gtpwxokpra.html

[U84] JS：CommonJS 写法
来源：http://dali.jyoumei.cn/Article/details/gtvucawyqx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtljbhdjma.html


<!-- 参考信息 -->