代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenlongwang.top/Article/details/gtjmrxeevz.html

[S57] C++：编译期常量
来源：http://dali.zhiwuduotai.top/Article/details/gtouzekodz.html

constexpr int N = 10;
来源：http://dali.zhoulong.xyz/Article/details/gtxtuozvvi.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtkakvmyfv.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenzaomai.com/Article/details/gtghtnbtlq.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtyhtpfvns.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gtbkpudezw.html

[S60] C++：遍历并删除元素
来源：http://dali.guowangkeji.top/Article/details/gtcmqocpae.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtdaagwvuj.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtweapdbmp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgufenzy.top/Article/details/gtdzfklljg.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtkdsvwlry.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtrabeltcf.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtkuhmbzvx.html

[T02] Kotlin：变量
来源：http://dali.zdqjudy.top/Article/details/gtqxkwxgux.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jqgufenzy.top/Article/details/gtytrofgef.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtdihfxcvj.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtgbqafxto.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gtzsoegmni.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gthblijenf.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gtltmsvhxl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gtdkdoabpn.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gthzqevkhg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jyoumei.cn/Article/details/gtbupryncw.html

[T07] Kotlin：集合过滤
来源：http://dali.birdmap.top/Article/details/gtgiixzmul.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daria6918.cn/Article/details/gtbomfuzzl.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtjjugprsy.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gtrxibviym.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtjtazoegn.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gttlnshyvv.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gtpwfqymsr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gtuwvsntdz.html

[T11] Kotlin：协程
来源：http://dali.dianchejie.cn/Article/details/gtnqoidmev.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtajensrlw.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtvbzyyfnd.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtzptffzrc.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gtmylwfzmy.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtabyydnsq.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gtwzgnuyjo.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtpphhtikk.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gtskdsjmeg.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtwrgcynii.html

[T16] Swift：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtuvozngbl.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtyzcopiad.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtidrongko.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtflptxcjs.html

[T18] Swift：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtpsgbuzob.html

"值: \(b)"
来源：http://dali.nanxuanxn.top/Article/details/gtvbqhnabo.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtucorduon.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtilnaszls.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gtqettmsek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtyslaralc.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuwnewobv.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gttgfnthrg.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtilptyrxw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtfikqrflo.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtqynhqosk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtmyntbjzf.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtnzyhiljn.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj202588.top/Article/details/gthpiolrpp.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtdpeuuydq.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtcsfvskqv.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtwidukhla.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtsbggjbdm.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gttzwecoxi.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gttcqtmrgl.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtfqjbhgek.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtfmplgqtp.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtmajnvggg.html

guard let x = opt else { return }
来源：http://dali.daria6918.cn/Article/details/gtfstaqjlm.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gthbvpzrfk.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtlnnzmjvq.html

[T31] Lua：Hello World
来源：http://dali.jianghu66.top/Article/details/gtjtnfjjhe.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtsyhaziel.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtcugiruyq.html

local a = 1
来源：http://dali.ydzc1.top/Article/details/gtnmcvivxz.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtostqusgz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtuvshtjaq.html

[T34] Lua：遍历表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnelqgtnw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtetbvljrp.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gtzkuosddn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gtdtjxgnxl.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtfbkhhkcx.html

function add(a, b) return a + b end
来源：http://dali.zhiwuduotai.top/Article/details/gtycpkpsyt.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gtmpqvztht.html

"a" .. "b"
来源：http://dali.zdqjudy.top/Article/details/gtbdfwoxgh.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtqoxxgbvs.html

if x > 0 then print("正") end
来源：http://dali.zhongyouzk.top/Article/details/gtubazatcs.html

[T39] Lua：模式匹配
来源：http://dali.daria6918.cn/Article/details/gtmexmpxwr.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtrdwyyjwh.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtvptqtgyb.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gtdqilktvb.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtnoxfwrey.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmvmvmdrb.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gthvnavabs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteypkzfgu.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtqwphedne.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtqbhkvojl.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtdjshwkdy.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtfnosztoe.html

[T45] Perl：数组遍历
来源：http://dali.pengpengdd.cyou/Article/details/gthpediyth.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gtmqvcqocy.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtwknhooel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtmlzdihgf.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtlbvnvdys.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gtarxxutve.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtulciboaq.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gtrsshlnib.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtrfmgclus.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tianlin.xyz/Article/details/gtycwdjuqr.html

[T50] Perl：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtrytpxzxy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtjsgitjer.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsdcsmnx.html

[T51] Scala：Hello World
来源：http://dali.xinyue.icu/Article/details/gtlmfenavg.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtznnipufq.html

[T52] Scala：变量
来源：http://dali.birdmap.top/Article/details/gtxufhcplv.html

val a = 1;  var b = 2
来源：http://dali.shzxlz.cn/Article/details/gthzfpbrsj.html

[T53] Scala：字符串插值
来源：http://dali.ivvv.top/Article/details/gtqphjyoiq.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gtiwlszugs.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtwxrcimgd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtqeplnyjc.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gtgkftyffy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ydzc1.top/Article/details/gtlqzfjxbp.html

[T56] Scala：样例类
来源：http://dali.yuanzhike.top/Article/details/gtdkeymbti.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gtqdegyylo.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gtzitpiwee.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ybcxt.top/Article/details/gtnakoxcyw.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtwvvsrnqj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtrxlkbpwl.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gtdsgufnmt.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrejsljzl.html

[T60] Scala：折叠
来源：http://dali.daria6918.cn/Article/details/gtuvsbrvaf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtlcwmzeqa.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtalwonran.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtbzidnrgt.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtjmkranmv.html

[U01] Py：创建虚拟环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdgzsxfoa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtujqgnitr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gthozeldzi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gtdhmxnpca.html

[U03] Py：加载 .env 配置
来源：http://dali.hywenlv.cn/Article/details/gtpkzqthiy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtipraoomc.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gtvtlihupm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gtsxlnxicy.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gttyyfmpie.html

list(dict.fromkeys(arr))
来源：http://dali.hfpthk.cn/Article/details/gtxnkjlgzj.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gterikyfnr.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtjdsydfkk.html

[U07] Py：反转字典键值
来源：http://dali.jiagoushi.top/Article/details/gtauctbags.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtgptoytic.html

[U08] Py：展平二维列表
来源：http://dali.yuanzhike.top/Article/details/gtxobhbnzt.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtdzepqxzd.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtsoiwzssk.html

max(d, key=d.get)
来源：http://dali.bjfxy.top/Article/details/gtcghhouku.html

[U10] Py：按值排序字典
来源：http://dali.jlsjyb.cn/Article/details/gtxgzcpbey.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gtbbffpuje.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gticvqwnyf.html

(x * 2 for x in arr)
来源：http://dali.gotoacloud.top/Article/details/gtvbxcoyzn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtstjjtdyy.html

Counter(arr).most_common(3)
来源：http://dali.gogol.net.cn/Article/details/gteewtoank.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gtrkyzbcxu.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gtklgzrmlu.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gtyzlzzchh.html

defaultdict(list)
来源：http://dali.bjfxy.top/Article/details/gtfcmwvmgu.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gtcpaplysq.html

t = time.perf_counter()
来源：http://dali.havefunace.top/Article/details/gtmtoolczr.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gtqcvhttuy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtrwhaeydi.html

[U17] Py：初始化日志
来源：http://dali.jinqigufen.top/Article/details/gtxuygipty.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zdqjudy.top/Article/details/gtfuoknehl.html

[U18] Py：预编译正则
来源：http://dali.jqgfzy.top/Article/details/gtkqrqtmag.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzkjndryo.html

[U19] Py：正则替换带回调
来源：http://dali.hfpthk.cn/Article/details/gtvwhvlsvd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.9152youxi.cn/Article/details/gtlihruzxr.html

[U20] Py：缓存函数结果
来源：http://dali.xziqi.cn/Article/details/gtecbvdycf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtpsgpootj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gtabjgxwze.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gtpptrfgyo.html

[U22] Py：矩阵转置
来源：http://dali.ybcxt.top/Article/details/gtzjfrcepx.html

list(zip(*m))
来源：http://dali.jinqigfzy.top/Article/details/gtkvrdpjmp.html

[U23] Py：分块读取大文件
来源：http://dali.hammf.cn/Article/details/gtedxnhvkx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtesbchurf.html

[U24] Py：路径操作
来源：http://dali.redwolf501.top/Article/details/gtjqjupzfw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtctrgapyv.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gtivcbbvpt.html

csv.DictReader(f)
来源：http://dali.zhengqikj.top/Article/details/gtwlmpfckc.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtoaptbwfk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gtyieyusvk.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gtechnwnzg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gtxzfkdqkl.html

[U28] Py：类型别名
来源：http://dali.xziqi.cn/Article/details/gtrajahnvk.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyrjbjez.html

[U29] Py：属性校验
来源：http://dali.hnqzz.top/Article/details/gtjoqtanri.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gtyiwkwjvz.html

[U30] Py：数据类
来源：http://dali.snrcjt.cn/Article/details/gtodsqbhcl.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqbsjcpd.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gtnaoeoatl.html

python -m pytest -q
来源：http://dali.daria6918.cn/Article/details/gtqvgweler.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtfupqyqmx.html

ruff format . && ruff check --fix .
来源：http://dali.svipenyu.cn/Article/details/gtawvrzofa.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtdgolqchm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtuepuuoul.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtyhyeogpz.html

chardet.detect(raw)
来源：http://dali.snrcjt.cn/Article/details/gtvlviwcwq.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gtxpbydylk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gtbsealxef.html

[U36] Py：定时任务
来源：http://dali.ybcxt.top/Article/details/gtksnnlhty.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtkfseaapw.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gtzvidpygj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtgypydofg.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtyzjuromk.html

Path(__file__).resolve().parent
来源：http://dali.bjfxy.top/Article/details/gtirofhyiz.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtbpcvadah.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbmztyum.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gtipnvbhza.html

print("err", file=sys.stderr)
来源：http://dali.xylfe.cn/Article/details/gtrnvyhvbr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.chenlongwang.top/Article/details/gtxxpvdnga.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.fengsongda.top/Article/details/gthpcigizv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtlomxluqx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gtgucnvuda.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gtxgzfldsd.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gtyebqxarx.html

[U44] PHP：开启严格类型
来源：http://dali.guowangkeji.top/Article/details/gtoppcklfl.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtlskeemrx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtlkdfztrl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtrxcefusx.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gtramsofwq.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtpmnotkzw.html

[U47] PHP：联合类型
来源：http://dali.chenzaomai.com/Article/details/gtmselsfdk.html

int|string $id
来源：http://dali.snrcjt.cn/Article/details/gtvaijutnk.html

[U48] PHP：纯枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtgqyjzywp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ydzc1.top/Article/details/gthgcdpmmm.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtsbmnlebe.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gtnwnqysfd.html

[U50] PHP：构造器属性提升
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvodqcqt.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gtzgiqwgsv.html

[U51] PHP：数组解构
来源：http://dali.cashguo.top/Article/details/gtnxkbeied.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtloripzgi.html

[U52] PHP：箭头函数
来源：http://dali.gotoacloud.top/Article/details/gtqmhkoiyi.html

$double = fn($x) => $x * 2;
来源：http://dali.xinyue.icu/Article/details/gtgcaufqkt.html

[U53] PHP：空合并运算符
来源：http://dali.jlsjyb.cn/Article/details/gtvdslqjxx.html

$v = $a ?? $b ?? "default";
来源：http://dali.ydzc1.top/Article/details/gtqucjqkhs.html

[U54] PHP：空安全调用
来源：http://dali.316326.xyz/Article/details/gtnzozanrw.html

$obj?->method()
来源：http://dali.birdmap.top/Article/details/gtgtqivncq.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gtoqhtjlzi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtojtikirg.html

[U56] PHP：命名参数
来源：http://dali.jyoumei.cn/Article/details/gtnwququfw.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtvucugcjf.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtnlcqzxkn.html

"值: {$a}"
来源：http://dali.jqgufenzy.top/Article/details/gtxpybznrp.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtcozvvdje.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.svipenyu.cn/Article/details/gttvumzrsc.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gtsonlimvn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gtoobeszak.html

[U60] PHP：JSON 编解码
来源：http://dali.cdnleiting.top/Article/details/gtsafsycyc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtogzuwepo.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtihfkuorp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtebheulqi.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gtyluphntm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gtapyibueb.html

[U63] PHP：文件读写
来源：http://dali.gzhubu.top/Article/details/gtonbhtejg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtaqmnivqy.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gtpqkhcksc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nanxuanxn.top/Article/details/gtouoohrhc.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodnnioar.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gtksqhtuug.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtlucqoyem.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gtaqbqioci.html

[U67] PHP：处理文件上传
来源：http://dali.ybcxt.top/Article/details/gtebohwikq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gteerqhnyo.html

[U68] PHP：PDO 连接
来源：http://dali.shangyingyoupin.top/Article/details/gtwillnljc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtatuqlqpp.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtadtjvden.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.bjfxy.top/Article/details/gtqyjayvym.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gtyrcceanq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtpantciue.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gtdopzhjpt.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gttefobnzr.html

[U72] PHP：写错误日志
来源：http://dali.snrcjt.cn/Article/details/gtgdryoweg.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gtgdiavdyx.html

[U73] PHP：读取 ini 配置
来源：http://dali.cashguo.top/Article/details/gtsgalvium.html

parse_ini_file("config.ini", true)
来源：http://dali.yuxming.cn/Article/details/gtsqmrkflq.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gtjpujmlpu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.fzhhl.top/Article/details/gtwxrwupgz.html

[U75] PHP：依赖注入
来源：http://dali.sxryk.cn/Article/details/gtnuqjrwta.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gtzmlcugfb.html

[U76] PHP：简单路由
来源：http://dali.aibaodan.cn/Article/details/gthkxmfwpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xuetiantiany.cn/Article/details/gtyftsxjxb.html

[U77] PHP：模板渲染
来源：http://dali.guannengcc.top/Article/details/gtayffzvtd.html

composer require twig/twig
来源：http://dali.gogol.net.cn/Article/details/gtrxvuvnsq.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gtbuqxzxqj.html

composer require --dev phpunit/phpunit
来源：http://dali.gaohongyu789.top/Article/details/gtdkxcwpok.html

[U79] PHP：静态分析
来源：http://dali.hnxiangtu.top/Article/details/gtbiwphvms.html

composer require --dev phpstan/phpstan
来源：http://dali.xziqi.cn/Article/details/gtpwawhoej.html

[U80] PHP：代码规范修复
来源：http://dali.ydzc1.top/Article/details/gtviokmjaa.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.bjfxy.top/Article/details/gtuxgofpqo.html

[U81] JS：初始化项目
来源：http://dali.yj20258888.top/Article/details/gtqfpapjpc.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gttkugibdd.html

[U82] JS：package.json 脚本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenkxomgj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.svipenyu.cn/Article/details/gtkvwkermm.html


<!-- 参考信息 -->