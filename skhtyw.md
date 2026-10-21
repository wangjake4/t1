代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gthcnjekns.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtfzlqwswr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gtmonenczc.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtcyuigrxd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinqigufen.top/Article/details/gtwnlnipxm.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtlzddvrdw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtmlbfhrio.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmljkbua.html

[T01] Kotlin：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtticcjldi.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtpdhehimz.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtfiybabde.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gtorqqfbzt.html

[T03] Kotlin：字符串模板
来源：http://dali.chenjidiqi.icu/Article/details/gtbjmcltta.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtpdlviuqv.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtigfedzpu.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gtdatbkwxp.html

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gtesqoniwd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gtgekrrzkz.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtnjmcqpka.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtggafrjkc.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzwzgcqrk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ydzc1.top/Article/details/gtwpgkumho.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtggowojgz.html

data class User(val name: String, val age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtutujrzwb.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtcvjxnnbs.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtebpgnqoj.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gtavvtftqy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtitsiltsq.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtetnzfnyq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gtclgyftec.html

[T12] Kotlin：解构声明
来源：http://dali.pycfn.com/Article/details/gtqhlofirx.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gtesdicgay.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtlcssuwed.html

val m = mapOf("a" to 1)
来源：http://dali.zdqjudy.top/Article/details/gtcmguzekc.html

[T14] Kotlin：循环
来源：http://dali.jiagoushi.top/Article/details/gtfxwyuygg.html

for (i in 1..10) println(i)
来源：http://dali.meibo888.top/Article/details/gtqbcrscqq.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gtcwhvvcil.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gthntedtzo.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtnnpjfuxq.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtiaaemzah.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtrefvvjft.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtxuduqtka.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtifnzsaup.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gtyyyetovl.html

[T19] Swift：可选绑定
来源：http://dali.daxiang520.top/Article/details/gtgnbprhsg.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtawqeqlve.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtsfifowgd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtkvbmaott.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtwnnzkuqg.html

for x in a { print(x) }
来源：http://dali.guowangkeji.top/Article/details/gtgtesbpva.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtuxxggycx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.havefunace.top/Article/details/gtdfizirex.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtgqmdcwbo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtbkdnturh.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtzvrbuvjc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtpxqmzfpn.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtslsfhvuc.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtbrjppduc.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtsmjvuhyq.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtpbslgsyf.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gtazjdntjm.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtkbqygbzm.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtbpmxcfhk.html

enum Color { case red, green }
来源：http://dali.yvedp.cn/Article/details/gtskjjjmpj.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmbmcrxxm.html

guard let x = opt else { return }
来源：http://dali.hammf.cn/Article/details/gtlkmhrpes.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtaygmvoxp.html

protocol Shape { func area() -> Double }
来源：http://dali.xylfe.cn/Article/details/gtebrjmloc.html

[T31] Lua：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtpzsyxdum.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtmhmiyqez.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtbcjfqavo.html

local a = 1
来源：http://dali.yvedp.cn/Article/details/gtzkoebhho.html

[T33] Lua：表（数组）
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfblsxrz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gttryghqdq.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezmlhxvq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtradwyfnt.html

[T35] Lua：字典表
来源：http://dali.cheryme.top/Article/details/gtyyqwihgl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtboopbsdu.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gteshqsprc.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtxpkehrkq.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtrguzxofh.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtccjryqac.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtplrwsyfo.html

if x > 0 then print("正") end
来源：http://dali.kuanghao11.cn/Article/details/gtsrmhgect.html

[T39] Lua：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gthoatxzue.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtlsativyy.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejyxalip.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtahwbgqos.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtzalqzmca.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtdrhmexpz.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gtyeliejea.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtshnxtgja.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtgicfcemo.html

"值: $a"
来源：http://dali.iojbl.cn/Article/details/gtwiavseua.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvtxwtzlf.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtgwdheomz.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtlaspasuy.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtdkmpggry.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtdrqnbmnf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuxming.cn/Article/details/gtebjeylun.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gtmsopnecz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtxadhclpa.html

[T48] Perl：正则替换
来源：http://dali.ybcxt.top/Article/details/gtdcfciwen.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtqdtaqhrd.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gttysnzfvg.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtuymebjch.html

[T50] Perl：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtpbxdxomb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtvwxmzwvj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.iojbl.cn/Article/details/gtixpdvibe.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gtuwivypwm.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtrxwzkwpy.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gtnxmkuofb.html

val a = 1;  var b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtvyughwnp.html

[T53] Scala：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtquyqgrfq.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtjjfwphto.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcctikdfc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gtfgqsqwdv.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtvjaahvot.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yonumen.top/Article/details/gtolsmikav.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gtctgfotka.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtfpucuafh.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtsnwsrjwe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pycfn.com/Article/details/gtggwsdiic.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtlbdoupsf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtcjqrtyvx.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtzlavukbd.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtkbduoceh.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsxvhljle.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtpufpakke.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtpgefukhd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtpfoveozp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtelxjecys.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gtmdvazjty.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtjondtwji.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gtxmebwowl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtlubwiizb.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtmuwlutkt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtkofkcjyd.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtquuuusun.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pycfn.com/Article/details/gtzgcmcsvq.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtkryfvugw.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrgljiow.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtlnvglacp.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtynrsmnza.html

[U07] Py：反转字典键值
来源：http://dali.sxryk.cn/Article/details/gtfsdapehu.html

{v: k for k, v in d.items()}
来源：http://dali.hongshengwenyu.top/Article/details/gtewurgvez.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtgrgdirah.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gtkhamtdgy.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gthjfoyacn.html

max(d, key=d.get)
来源：http://dali.0kj1m.cn/Article/details/gtkcflqhpy.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtljriaxyk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtsiyyyakr.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gtczryqasy.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gtqxobyhpz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.redwolf501.top/Article/details/gtysbgqwbf.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtbmazhffa.html

[U13] Py：固定长度队列
来源：http://dali.daxiang520.top/Article/details/gttiztwwxk.html

deque(maxlen=10)
来源：http://dali.yj20258.top/Article/details/gtvpdoknij.html

[U14] Py：分组收集到列表
来源：http://dali.yonumen.top/Article/details/gtdzfizwns.html

defaultdict(list)
来源：http://dali.jqgfzy.top/Article/details/gtvedajjxh.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gtjooabykc.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtbynrpzpa.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtxdaybzhc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sysykeji.top/Article/details/gtseyrpaoa.html

[U17] Py：初始化日志
来源：http://dali.shangyingyoupin.top/Article/details/gtjmandmxr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtdvwxcvpd.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxiplqno.html

pat = re.compile(r"\d+")
来源：http://dali.mhx1999.top/Article/details/gtoquihrjq.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtzvwgbdrq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtwubquauw.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gtmxwuabns.html

@functools.lru_cache(maxsize=None)
来源：http://dali.nwbrower.top/Article/details/gtkhuvgizf.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtmrareoje.html

@contextlib.contextmanager
来源：http://dali.gotoacloud.top/Article/details/gtgnungmjb.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gtoriuqdhm.html

list(zip(*m))
来源：http://dali.havefunace.top/Article/details/gtxtsrgkzf.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gtyqkadsjv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gzhubu.top/Article/details/gtnjxvlyzs.html

[U24] Py：路径操作
来源：http://dali.sxryk.cn/Article/details/gtzsefdtex.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtplawmwpi.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtxdtsssen.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtorfrwxog.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gtndphlyzs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.andypj.xyz/Article/details/gtgrefsvon.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gtmeadgsbs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tian-w.cn/Article/details/gtdqdurbfr.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtqzdjctzl.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gthzijtedd.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtfcepnlez.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtpekveaat.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtqrwzpmnh.html

@dataclass(slots=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsazkeag.html

[U31] Py：单测
来源：http://dali.yonumen.top/Article/details/gtsxmsnrki.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gtotdfpjtz.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctydrmsg.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtwwrqjwaa.html

[U33] Py：打包发布
来源：http://dali.jiagoushi.top/Article/details/gtnrwrxqhq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gtlrilpzjs.html

[U34] Py：判断编码
来源：http://dali.iojbl.cn/Article/details/gtdeylqfno.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtvvpctycn.html

[U35] Py：发送邮件
来源：http://dali.bjfxy.top/Article/details/gtmsigxeit.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gttjbnzcjm.html

[U36] Py：定时任务
来源：http://dali.yj202588.top/Article/details/gttahnwhdp.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtqapchkre.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtgdffchwu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gtjzrryezw.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtarfdnims.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtwpfgaujj.html

[U39] Py：判断是否在交互环境
来源：http://dali.sufxvd.cn/Article/details/gtmxpydhww.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gtygezrxzf.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gtsezeoetj.html

print("err", file=sys.stderr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzfyqsbuu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aizwys.cn/Article/details/gtcdxnrffk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sxryk.cn/Article/details/gtpgwjzgoi.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yangfankeji.com/Article/details/gtgoewgyya.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtikamokui.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gtrnhqreum.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gttmhnnrar.html

[U44] PHP：开启严格类型
来源：http://dali.wangshuangyany.cn/Article/details/gtlgkpkbxd.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gthtspspcm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jyoumei.cn/Article/details/gtjyayziod.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtbaocempm.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gtlnxgqypg.html

?string $name = null
来源：http://dali.pengpengdd.cyou/Article/details/gtwogegqlb.html

[U47] PHP：联合类型
来源：http://dali.sufxvd.cn/Article/details/gtrmnwtgvl.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtskthokku.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtwselsunc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gtpursmpnk.html

[U49] PHP：只读属性
来源：http://dali.cdnleiting.top/Article/details/gtfahprsin.html

public readonly string $name
来源：http://dali.yuxming.cn/Article/details/gtzyowtwhc.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtpwolsssb.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gtlzaxhnaq.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtokesewpx.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gtdnwokfwa.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtzduiznil.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gtivqpwrur.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtsxjgfgra.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsdeldnu.html

[U54] PHP：空安全调用
来源：http://dali.shangyingyoupin.top/Article/details/gtazoxxerv.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthligdekk.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gtdpuvvgbj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtmbbtnkxe.html

[U56] PHP：命名参数
来源：http://dali.ppjwa.cn/Article/details/gtbfayuozf.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtyqmrkfnf.html

[U57] PHP：字符串插值
来源：http://dali.cqqwz.cn/Article/details/gtqnbcvczk.html

"值: {$a}"
来源：http://dali.zhengqikj.top/Article/details/gttjfqacki.html

[U58] PHP：数组三件套
来源：http://dali.aibaodan.cn/Article/details/gtnfbzysrr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtywlkgbwm.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gtpbgfmqiv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hysaishi.cn/Article/details/gtxwxrmyec.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtagycbveq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtghrwiitc.html

[U61] PHP：正则
来源：http://dali.sysykeji.top/Article/details/gtjiexxtuj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtjbcfhskn.html

[U62] PHP：日期对象
来源：http://dali.zdqjudy.top/Article/details/gtovpfpoir.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtpxzxzwbr.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtnjrnditx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yvedp.cn/Article/details/gtezzbigfj.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gtzuypcbhu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gtedcthaui.html

[U65] PHP：会话
来源：http://dali.meibo888.top/Article/details/gtamvmcfai.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtfgqksdun.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gtsriqmbfe.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aizwys.cn/Article/details/gtirbuzrui.html

[U67] PHP：处理文件上传
来源：http://dali.feifeiyinyue.top/Article/details/gtjlfyzixr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gthodlrtnk.html

[U68] PHP：PDO 连接
来源：http://dali.nwbrower.top/Article/details/gthwzglnll.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttnbdaxq.html

[U69] PHP：PDO 预处理
来源：http://dali.zhengqikj.top/Article/details/gtorctishy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dianchejie.cn/Article/details/gtpsidrvix.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gtuktwiwex.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtvhdudmbf.html

[U71] PHP：抛出异常
来源：http://dali.jlsjyb.cn/Article/details/gtukxqbqyp.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gtuqenwasv.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gtkuzxjwju.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gtjtgdtyra.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenzaomai.com/Article/details/gtqdyqerkh.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gtthkoqfdw.html

[U74] PHP：读取环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtamjuxmxt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzyiovvx.html

[U75] PHP：依赖注入
来源：http://dali.yuanzhike.top/Article/details/gtlzqcztce.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtvwoerisf.html

[U76] PHP：简单路由
来源：http://dali.xylfe.cn/Article/details/gtnyditajo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtrdretibh.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtqdqkfgrc.html

composer require twig/twig
来源：http://dali.iojbl.cn/Article/details/gtjenyeufw.html

[U78] PHP：单元测试
来源：http://dali.nanxinkj.top/Article/details/gtkjroflkf.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gtdkmroomy.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gtzmsvcald.html

composer require --dev phpstan/phpstan
来源：http://dali.zhixingplan.top/Article/details/gtgdslfude.html

[U80] PHP：代码规范修复
来源：http://dali.yuanzhike.top/Article/details/gtywtkluka.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavobufwt.html

[U81] JS：初始化项目
来源：http://dali.meibo888.top/Article/details/gtjpyrhavl.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtdvdlkvwb.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gtxwxbdbye.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cheryme.top/Article/details/gtkqiskgky.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gtqvnxqcek.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yj20258.top/Article/details/gtewdzyhjq.html

[U84] JS：CommonJS 写法
来源：http://dali.nanxinkj.top/Article/details/gtqoorhcra.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtsrflqlje.html


<!-- 参考信息 -->