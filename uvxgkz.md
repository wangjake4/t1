代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtoyglcxyu.html

[S59] C++：静态断言
来源：http://dali.yj202588.top/Article/details/gticymxxhy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gtggppyeqe.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtfeuygspr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sysykeji.top/Article/details/gtzcpsczry.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtixyihjmj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtokksvqab.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtscfuiqbv.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtyhthnshy.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtrhcjxfpa.html

[T02] Kotlin：变量
来源：http://dali.c1oappe.top/Article/details/gttszjgcfk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtrrkkohuk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gteugvgkbq.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtywjlqjhh.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtkvddithe.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtmarffgci.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtpglsqmne.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtrjpcvhnh.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtdfprigps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtjnpnscyn.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtqeouyeil.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtxrwtndod.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtthmoniez.html

data class User(val name: String, val age: Int)
来源：http://dali.xziqi.cn/Article/details/gttezbjanq.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtudmjfbfg.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtvzfulveg.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtbeqhhgla.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gtxzoidcua.html

[T11] Kotlin：协程
来源：http://dali.gaohongyu789.top/Article/details/gtuyvrtsgk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtsacwioqa.html

[T12] Kotlin：解构声明
来源：http://dali.chenlongwang.top/Article/details/gtabmsppdk.html

val (a, b) = Pair(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gtzpwnhfkl.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtgcenldpd.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtwqtlypkx.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtyqsxjvdt.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdrbujgia.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gtnuxwydmr.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtvcthtpjs.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtsdbvqesr.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtsnsfuzja.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtzyqpufkj.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtgkitekkk.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtmvpxhrpt.html

"值: \(b)"
来源：http://dali.sysykeji.top/Article/details/gtafvtsegs.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gtpvsdyvib.html

if let n = opt { print(n) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlfejssz.html

[T20] Swift：数组操作
来源：http://dali.shuidangran.top/Article/details/gtxmymjwsp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jiagoushi.top/Article/details/gtnkkzonjz.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwqhovzo.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxqeoicem.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gtzrwofljt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtfinthirp.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gtlkykzxdx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gtxgbfzjih.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gtcvjynrzt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtakhyvemt.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtyrylbozx.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtaocjacmh.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gtmdmferpa.html

class A: Base { override func f() {} }
来源：http://dali.sufxvd.cn/Article/details/gtoxuseryx.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gtblfyzzrd.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtiwnifgyi.html

[T28] Swift：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtwtbjbcgn.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtvjqfivsi.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtotomspde.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtrpsmuzvr.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtniqqiuet.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtbhyvfkyn.html

[T31] Lua：Hello World
来源：http://dali.zycfv.cn/Article/details/gtkevqljgo.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtwwsjexsd.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gtgxmwhzph.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gtioouunrj.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrpzhixch.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtrpdrivvs.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gtesiipgfy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtmcehgtec.html

[T35] Lua：字典表
来源：http://dali.jqgufenzy.top/Article/details/gtjarvjvir.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gtxyohrcrd.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gtlcsescae.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtlfbpbumd.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtlryussct.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtjjhgbxjs.html

[T38] Lua：条件
来源：http://dali.hammf.cn/Article/details/gtbkzlzcci.html

if x > 0 then print("正") end
来源：http://dali.jiagoushi.top/Article/details/gtagmzuwbx.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtcvgcpjpj.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtuxqghdkl.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gtgjdeuynr.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gthtyalayv.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtqsgdahqp.html

print "Hello\n";
来源：http://dali.xinyue.icu/Article/details/gtzzntaevn.html

[T42] Perl：变量类型
来源：http://dali.zycfv.cn/Article/details/gtnkptdewq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gtlgedqzjw.html

[T43] Perl：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gtasunsowf.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtkhvngyzn.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gtocywbtwh.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gtfgkssjwo.html

[T45] Perl：数组遍历
来源：http://dali.hnxiangtu.top/Article/details/gtlucfxxai.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtpflnpggp.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtqajtqxas.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtoyqdtgar.html

[T47] Perl：正则捕获
来源：http://dali.yangfankeji.com/Article/details/gtnhsgscso.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ppjwa.cn/Article/details/gtvthwzwpl.html

[T48] Perl：正则替换
来源：http://dali.fengsongda.top/Article/details/gtmlwjhffh.html

$s =~ s/old/new/g;
来源：http://dali.ybcxt.top/Article/details/gtvlkfsonf.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gtzniwrikd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtxeriqvwh.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtbgrlaqvv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtaxavfyac.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gtsuydpjps.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtaplmppof.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtgngaxari.html

[T52] Scala：变量
来源：http://dali.yj20258.top/Article/details/gtwkrsqdmu.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtajounoyz.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtpcycpanj.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtlwqrlrjb.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtzsumqjdx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fzhhl.top/Article/details/gtznglmwbm.html

[T55] Scala：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwylvouna.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtqgpeoleh.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gtdlhrmmmh.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gthssubzql.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gtmltonojg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gtfyxkyoie.html

[T58] Scala：函数定义
来源：http://dali.dashuyun.cn/Article/details/gtagzcyjio.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gthdveycrh.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gtxlsgfmjk.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtxdvwibhc.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtvxdhjwxs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gtzygbfupn.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtemvieyas.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtatmkvqpi.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuqjarcfh.html

[U01] Py：创建虚拟环境
来源：http://dali.hnxiangtu.top/Article/details/gtpgoumdlw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gtymkyeojt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtbwhlxmyn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtztbiemyb.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gtcpchcocy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtotmsgxzw.html

[U04] Py：变量调试打印
来源：http://dali.sysykeji.top/Article/details/gtxzzwraql.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtzcqouejc.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtfgbhcawi.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gtweodqzzw.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtjkkdiiom.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtlfoaohja.html

[U07] Py：反转字典键值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhusticm.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigfzy.top/Article/details/gtgkgfyxfx.html

[U08] Py：展平二维列表
来源：http://dali.zhixingplan.top/Article/details/gtmuxusbfz.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtexqtczho.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gtdfafcygf.html

max(d, key=d.get)
来源：http://dali.meibo888.top/Article/details/gtsknejscq.html

[U10] Py：按值排序字典
来源：http://dali.yanxiufei.cn/Article/details/gtkwebimju.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtqelfojcw.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtdwskpldw.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtltyecczm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.dianchejie.cn/Article/details/gtjahvmdlz.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gtcaqgokgd.html

[U13] Py：固定长度队列
来源：http://dali.cashguo.top/Article/details/gtijsscott.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtcsydhbyc.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtionvrtjw.html

defaultdict(list)
来源：http://dali.zhijiandao.cn/Article/details/gtnaqtslrp.html

[U15] Py：高精度计时
来源：http://dali.chenlongwang.top/Article/details/gtkjivzuxf.html

t = time.perf_counter()
来源：http://dali.yonumen.top/Article/details/gtreltyfth.html

[U16] Py：命令行参数解析
来源：http://dali.chenzaomai.com/Article/details/gteemmktuq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtmlrjfqel.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtcuzrqsdl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gogol.net.cn/Article/details/gtpnxgsmmb.html

[U18] Py：预编译正则
来源：http://dali.hywenlv.cn/Article/details/gtdsbwmmrv.html

pat = re.compile(r"\d+")
来源：http://dali.hammf.cn/Article/details/gtxbhuyidf.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gtbjaujjxt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenlongwang.top/Article/details/gtwhamhopb.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtlnbkmqfr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.smart0.xyz/Article/details/gtptrfzxtp.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gtafvwsmrl.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtnzzalamd.html

[U22] Py：矩阵转置
来源：http://dali.yj202588.top/Article/details/gttdlxbnvc.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gtrnkyqspd.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtbkzjhoag.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhengqikj.top/Article/details/gtaumfuudz.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtpdlqdsql.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtrskydtwc.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gtpxfvgbfq.html

csv.DictReader(f)
来源：http://dali.zdqjudy.top/Article/details/gtdlseogpx.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtwmahdbqw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jlsjyb.cn/Article/details/gtgreweery.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtkdixcash.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtbhuuzatl.html

[U28] Py：类型别名
来源：http://dali.nwbrower.top/Article/details/gtuirbggqn.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gtzemlszie.html

[U29] Py：属性校验
来源：http://dali.hnxiangtu.top/Article/details/gtamkkvfgf.html

@property 与 @x.setter 配合
来源：http://dali.yonumen.top/Article/details/gttaaeiuwm.html

[U30] Py：数据类
来源：http://dali.jqgfzy.top/Article/details/gtbjrabfrp.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gtddtccbpt.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gtifsypkhs.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtzozeayzt.html

[U32] Py：代码格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtsgwfvmsx.html

ruff format . && ruff check --fix .
来源：http://dali.shangyingyoupin.top/Article/details/gtuzhrquzv.html

[U33] Py：打包发布
来源：http://dali.chenjidiqi.icu/Article/details/gtnfhnnnas.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gtxmemmxwj.html

[U34] Py：判断编码
来源：http://dali.kuanghao11.cn/Article/details/gtzwqmzbjh.html

chardet.detect(raw)
来源：http://dali.shuidangran.top/Article/details/gtmrkmtmyy.html

[U35] Py：发送邮件
来源：http://dali.0kj1m.cn/Article/details/gtnrkxhaxw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuynriuwf.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gtfqhmdaox.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtmwtpjtcz.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gtkqdaiecn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sysykeji.top/Article/details/gtzieixalg.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtqiixwtnj.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gtbqtwjkvn.html

[U39] Py：判断是否在交互环境
来源：http://dali.andypj.xyz/Article/details/gtbygksicn.html

sys.stdout.isatty()
来源：http://dali.meibo888.top/Article/details/gttgvppoyj.html

[U40] Py：打印到标准错误
来源：http://dali.hongshengwenyu.top/Article/details/gtmgbqeqnw.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gtvomlsntl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gzhubu.top/Article/details/gtqkontcfk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.haohaochexian.top/Article/details/gtwlycqmmc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.redwolf501.top/Article/details/gthrttsrug.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtjcsnbbxb.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gtdgxebaqj.html

namespace App\Http;
来源：http://dali.nanxuanxn.top/Article/details/gtkxcbdude.html

[U44] PHP：开启严格类型
来源：http://dali.yongpay.top/Article/details/gtuqylvfrb.html

declare(strict_types=1);
来源：http://dali.nanxinkj.top/Article/details/gtrtifnhsy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yueranfly.top/Article/details/gtgggetlmy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gttbetizgm.html

[U46] PHP：可空类型
来源：http://dali.cucudq.cn/Article/details/gtyabampjr.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gtgklmfklw.html

[U47] PHP：联合类型
来源：http://dali.iojbl.cn/Article/details/gttmuhugjp.html

int|string $id
来源：http://dali.yangfankeji.com/Article/details/gtkbwenbol.html

[U48] PHP：纯枚举
来源：http://dali.nwbrower.top/Article/details/gtcfmtpzsj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcisktngc.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gtazvwbsbe.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gtpfmmponk.html

[U50] PHP：构造器属性提升
来源：http://dali.yonumen.top/Article/details/gteauflaxp.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gtmmsiqktp.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gthzprzhyf.html

[$a, $b] = $arr;
来源：http://dali.iojbl.cn/Article/details/gtdyzvjehc.html

[U52] PHP：箭头函数
来源：http://dali.pycfn.com/Article/details/gtdjraazop.html

$double = fn($x) => $x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtspyewrmu.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigufen.top/Article/details/gtmmjwsgze.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gtqxvtdbun.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gtnrcpvjmn.html

$obj?->method()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtercfzogd.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtfkbkpsdj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gtblvbozvi.html

[U56] PHP：命名参数
来源：http://dali.sweek.top/Article/details/gtmjmxrxze.html

f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtayrbkeyh.html

[U57] PHP：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtgoqtmrzz.html

"值: {$a}"
来源：http://dali.daxiang520.top/Article/details/gteschukrz.html

[U58] PHP：数组三件套
来源：http://dali.haohaochexian.top/Article/details/gtmpvsvgtc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtghqxipli.html

[U59] PHP：自定义排序
来源：http://dali.haohaochexian.top/Article/details/gtpzetrpzi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gtdcutzrki.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtcovvfwon.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gtxanngthg.html

[U61] PHP：正则
来源：http://dali.shuidangran.top/Article/details/gtxsybqxob.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvwodniz.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtgjuzbitv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gttuayivyo.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtjuumgotj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigufen.top/Article/details/gtvtbebukp.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gtjaxxcjps.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gtworolmim.html

[U65] PHP：会话
来源：http://dali.tanke756.top/Article/details/gtvmywstsv.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtzjolllxo.html

[U66] PHP：设置 Cookie
来源：http://dali.smart0.xyz/Article/details/gtcjslrraa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj20258888.top/Article/details/gtiawvfzqi.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gtgurwbhhx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hysaishi.cn/Article/details/gtwzliqshw.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gtqbdruuha.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtskbqevmd.html

[U69] PHP：PDO 预处理
来源：http://dali.sysykeji.top/Article/details/gtefmvodkw.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gtxztithkp.html

[U70] PHP：PDO 事务
来源：http://dali.tanke756.top/Article/details/gtuoagnmfd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gtoowiacaq.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gtlecjkvci.html

throw new RuntimeException("失败", 500);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsbversdu.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gtuurjxdja.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtgdmektyc.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtdhzomlxv.html

parse_ini_file("config.ini", true)
来源：http://dali.jianghu66.top/Article/details/gtaotqnapw.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gtqrlmcmwk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gtzjyfxscn.html

[U75] PHP：依赖注入
来源：http://dali.pycfn.com/Article/details/gtionemcxf.html

composer require psr/container
来源：http://dali.gogol.net.cn/Article/details/gtciihpdvn.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtcifdfsws.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtpjyrusag.html

[U77] PHP：模板渲染
来源：http://dali.meibo888.top/Article/details/gtyvpauqei.html

composer require twig/twig
来源：http://dali.cdnleiting.top/Article/details/gtedaonmpo.html

[U78] PHP：单元测试
来源：http://dali.cucudq.cn/Article/details/gtrvpkpkhs.html

composer require --dev phpunit/phpunit
来源：http://dali.xuanzx.com/Article/details/gtvewnknkc.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gtogkbqqfz.html

composer require --dev phpstan/phpstan
来源：http://dali.dianchejie.cn/Article/details/gturvfsxko.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtgzvcbhsx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gtbecsfkmk.html

[U81] JS：初始化项目
来源：http://dali.zhijiandao.cn/Article/details/gtiyftlmpo.html

npm init -y;  npm i express
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmokbrove.html

[U82] JS：package.json 脚本
来源：http://dali.ivvv.top/Article/details/gttxqohwbu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.nwbrower.top/Article/details/gtxtonlwof.html

[U83] JS：ES Module 导入导出
来源：http://dali.fengsongda.top/Article/details/gtdbpcvumq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtiifxnfex.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gtnosjkvwo.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhongyouzk.top/Article/details/gtkzhiorms.html


<!-- 参考信息 -->