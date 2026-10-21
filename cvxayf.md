代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtkzfyhxen.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtjlbykqkk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzilxumkv.html

[S60] C++：遍历并删除元素
来源：http://dali.wangdashe.top/Article/details/gteqyidftv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtqmnttoxs.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gttyazordj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtzwkitfxu.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqirnhpju.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtldqwliiz.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gtqtovaazi.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtdtrjnolh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtcdhvibki.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtvvafeats.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtzuqkmxyl.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtmnhtzzyu.html

val n: String? = null;  n?.length
来源：http://dali.jinghuilouyu.cn/Article/details/gtgulltqzq.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtcdycghwz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ybcxt.top/Article/details/gtmdtlalbp.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gttfnkyekl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhongyouzk.top/Article/details/gtyznxsibe.html

[T07] Kotlin：集合过滤
来源：http://dali.xinyue.icu/Article/details/gtkmbriunr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtfuogkcfo.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtyqxrdvpk.html

data class User(val name: String, val age: Int)
来源：http://dali.nwbrower.top/Article/details/gthrngnrzo.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtrthbckwj.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtqsxewlkq.html

[T10] Kotlin：默认参数
来源：http://dali.yuxming.cn/Article/details/gtxemasgav.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrjfqilqn.html

[T11] Kotlin：协程
来源：http://dali.nwbrower.top/Article/details/gtvjtyezym.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtufmvllnj.html

[T12] Kotlin：解构声明
来源：http://dali.yj20258.top/Article/details/gtdufhclir.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwuyxeihs.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gtxdgdbgfg.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtfrjofawp.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtotghlbxq.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtxljxktul.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gtcpfcveei.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtajxgmnxi.html

[T16] Swift：Hello World
来源：http://dali.yj202588.top/Article/details/gtxdhevymu.html

print("Hello")
来源：http://dali.gzhubu.top/Article/details/gtdqzowtge.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gthbgubdql.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gtxeoatolv.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtvwiykqkj.html

"值: \(b)"
来源：http://dali.tanke756.top/Article/details/gtwjgcqawz.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtmjfiqavu.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gttkpqfbjn.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtiqcluyin.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gttxztjlsh.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdmdcsrwf.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtorhgcvva.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtakipujnb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gtjlhvgqob.html

[T23] Swift：函数
来源：http://dali.jiagoushi.top/Article/details/gtawfpneze.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtffxjzdfa.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtmybtmzcg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gtksscmrwq.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gtwtievdsv.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwphufrvl.html

[T26] Swift：类与重写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehjnvdon.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtztqkoqql.html

[T27] Swift：错误处理
来源：http://dali.c1oappe.top/Article/details/gtqukfjtje.html

do { try f() } catch { print(error) }
来源：http://dali.hongshengwenyu.top/Article/details/gthmofgoxk.html

[T28] Swift：枚举
来源：http://dali.0kj1m.cn/Article/details/gtfoapiqqj.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gtbmmgqtci.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtiwkjjwgt.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtyyficmgz.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtamjsgtkt.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gtarvdvmff.html

[T31] Lua：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtzsuivqmb.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtwbooxhtt.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtynrbzxdz.html

local a = 1
来源：http://dali.9152youxi.cn/Article/details/gtfijykajo.html

[T33] Lua：表（数组）
来源：http://dali.gaohongyu789.top/Article/details/gtdufwmbyh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zdqjudy.top/Article/details/gtsncbgjar.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtelzuootb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtcaryyada.html

[T35] Lua：字典表
来源：http://dali.hnqzz.top/Article/details/gtiiqmdooh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtogwubfyl.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtopbmxvvj.html

function add(a, b) return a + b end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtecpmcdqm.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtqmghodwa.html

"a" .. "b"
来源：http://dali.gotoacloud.top/Article/details/gtfnqhkgih.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtrpocbhdd.html

if x > 0 then print("正") end
来源：http://dali.sysykeji.top/Article/details/gtpuarjknl.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gtlrnzhalr.html

string.find(s, "%d+")
来源：http://dali.xziqi.cn/Article/details/gtndvlfmqi.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtbghmaopt.html

setmetatable({}, { __index = base })
来源：http://dali.xuanzx.com/Article/details/gthnvfnbgy.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtphalkpil.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtcwhkrotm.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtpeemadlv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtwzsvauze.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtcoioczyp.html

"值: $a"
来源：http://dali.cashguo.top/Article/details/gtludohvoq.html

[T44] Perl：条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtluafswxo.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtvswlgwvq.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtmitfehwo.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gtnqxabgdq.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtqchhalbv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtcngqastl.html

[T47] Perl：正则捕获
来源：http://dali.jqgfzy.top/Article/details/gtkpefdnbi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtwnxipuyl.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gtfphxqxww.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtjdarmxzr.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxkgxrod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtttgykgbi.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gttwrmuytp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shzxlz.cn/Article/details/gttufsyuhd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gtruxjzaxe.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtgtmdcjjv.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtwkkojtyw.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gtpnrgprrc.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gtnlzauvsr.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtnfmfxezm.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtxpfrtorz.html

[T54] Scala：集合映射
来源：http://dali.daria6918.cn/Article/details/gtymkbydxt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhoulong.xyz/Article/details/gtuxxfebnk.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtuukaxifx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hywenlv.cn/Article/details/gtxmukfqlr.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtrtbhqvwb.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gthrhalwoa.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtfvpcyuix.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ivvv.top/Article/details/gtlzohjrhb.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtnzxjpfef.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gaohongyu789.top/Article/details/gtmftlshki.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtlszrvbmi.html

for (i <- 1 to 10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtvvetjkqj.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtdjrrxrgb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gotoacloud.top/Article/details/gtywfldoyd.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtwgrtddiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtlvxedwnn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtedtmjdtl.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gtllfccdtv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtomzmkxed.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj202588.top/Article/details/gtnowpqqea.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuwmfepnk.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtczgbyyca.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gttrxtyaku.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gthavqkktm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.wangdashe.top/Article/details/gtvvieejfo.html

[U05] Py：列表去重且保序
来源：http://dali.0kj1m.cn/Article/details/gtkcjzwlni.html

list(dict.fromkeys(arr))
来源：http://dali.yangfankeji.com/Article/details/gtwkkcpuzi.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtiznnmyfi.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gttxpvkgtz.html

[U07] Py：反转字典键值
来源：http://dali.yuxming.cn/Article/details/gthuqekmyy.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtknmquegp.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gtmnguwnhe.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtulxtxzkp.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtdjtrhnsw.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtdhjebguy.html

[U10] Py：按值排序字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnumdaqqb.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenzaomai.com/Article/details/gtvkeljcim.html

[U11] Py：生成器表达式
来源：http://dali.ybcxt.top/Article/details/gtszjbzxdw.html

(x * 2 for x in arr)
来源：http://dali.nwbrower.top/Article/details/gteonubbpn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sufxvd.cn/Article/details/gtibpcvmtl.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtbekyyecp.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtbnenlzkb.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtxnvffvbu.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtdxsyvtgk.html

defaultdict(list)
来源：http://dali.chenzaomai.com/Article/details/gtkprvyuvh.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gtnpbmwpoq.html

t = time.perf_counter()
来源：http://dali.aibaodan.cn/Article/details/gthdbpdzbv.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gtkglefhrn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtfirdohfe.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtpfcqnevm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwimwpnli.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtejexflee.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gtjridlxoe.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtufsvnvoc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtmthckhrk.html

[U20] Py：缓存函数结果
来源：http://dali.fengsongda.top/Article/details/gtvvwwzirk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gtycgbbaoi.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gtmvwhcqoj.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gtptncdjwb.html

[U22] Py：矩阵转置
来源：http://dali.zycfv.cn/Article/details/gtwudxadbi.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gtzxaajpyf.html

[U23] Py：分块读取大文件
来源：http://dali.shzxlz.cn/Article/details/gtfqhmfqvj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenlongwang.top/Article/details/gtfylbsuxl.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtmuxffgsj.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jianghu66.top/Article/details/gtbyymbzxy.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtieitacbh.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtubhxxcug.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtqmkhrzyo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cashguo.top/Article/details/gtqapalsfx.html

[U27] Py：异步 HTTP
来源：http://dali.ppjwa.cn/Article/details/gtbfmeaxjd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuxming.cn/Article/details/gtpasohsiy.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtgoudanks.html

UserId = int
来源：http://dali.mhx1999.top/Article/details/gtjvygolaq.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gtxrulfumv.html

@property 与 @x.setter 配合
来源：http://dali.kuanghao11.cn/Article/details/gtajwsvlgt.html

[U30] Py：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtbahmjxuy.html

@dataclass(slots=True)
来源：http://dali.yuxming.cn/Article/details/gtwdqcvdsm.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gtrlmpeayd.html

python -m pytest -q
来源：http://dali.yangfankeji.com/Article/details/gtvywmfatl.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gtweozpzxx.html

ruff format . && ruff check --fix .
来源：http://dali.0kj1m.cn/Article/details/gtdsbdsfrb.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtbazbrsee.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.c1oappe.top/Article/details/gttskpdzkr.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gtrfrxonti.html

chardet.detect(raw)
来源：http://dali.tanke756.top/Article/details/gtccmixswy.html

[U35] Py：发送邮件
来源：http://dali.hnxiangtu.top/Article/details/gtussswipj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gtvbgkgxsh.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtoqutfxpe.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gtpueskrtv.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gtbzwyhfuz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gtmhxkrwun.html

[U38] Py：获取脚本所在目录
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmxhfyqk.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtkmlavhot.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gtunctlwlb.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gteoqrsqbd.html

[U40] Py：打印到标准错误
来源：http://dali.cucudq.cn/Article/details/gtqcnzarxz.html

print("err", file=sys.stderr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqohdhaei.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ivvv.top/Article/details/gtrhwfedoj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sufxvd.cn/Article/details/gtbcmotlav.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.meibo888.top/Article/details/gtifqejaff.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhiwuduotai.top/Article/details/gtjiergaio.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gtjaagrjzg.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtypwbppbq.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtaermutyw.html

declare(strict_types=1);
来源：http://dali.cheryme.top/Article/details/gtqfuortun.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinqigufen.top/Article/details/gtmzxhvjzg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtqmkntidh.html

[U46] PHP：可空类型
来源：http://dali.jqgufenzy.top/Article/details/gtsoefuebb.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gthxqisoqf.html

[U47] PHP：联合类型
来源：http://dali.mhx1999.top/Article/details/gtndkekrcx.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtmuhnrani.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gtakpnnfcu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gogol.net.cn/Article/details/gtsniaisoz.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gttcsfadcm.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gtowntcftt.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gtqzkzwkwp.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gtavbhpuou.html

[U51] PHP：数组解构
来源：http://dali.tianlin.xyz/Article/details/gttncfwnfm.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gtsnxqlran.html

[U52] PHP：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtujmiawec.html

$double = fn($x) => $x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtrxpzysad.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtfxztpzop.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gtzwbemorb.html

[U54] PHP：空安全调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtslpwutby.html

$obj?->method()
来源：http://dali.yangfankeji.com/Article/details/gtbwihsyfr.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gtlxqhaosm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.dashuyun.cn/Article/details/gtykyhvbuo.html

[U56] PHP：命名参数
来源：http://dali.9152youxi.cn/Article/details/gtwouefgrz.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtjiihehoi.html

[U57] PHP：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtjrxkiyck.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gtitpnlnxx.html

[U58] PHP：数组三件套
来源：http://dali.jqgufenzy.top/Article/details/gtsxmtihvy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gthmahbumi.html

[U59] PHP：自定义排序
来源：http://dali.cashguo.top/Article/details/gtisxfjqlw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtbdgqmsll.html

[U60] PHP：JSON 编解码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmmyxjlc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtonawfnhx.html

[U61] PHP：正则
来源：http://dali.zhixingplan.top/Article/details/gtsvwefqqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.feifeiyinyue.top/Article/details/gtihbxzhiy.html

[U62] PHP：日期对象
来源：http://dali.smart0.xyz/Article/details/gtnzkxzltw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenjidiqi.icu/Article/details/gtypjusyzh.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtaurjbbih.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cashguo.top/Article/details/gtgupopsmi.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gtjgsdpxxe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gtpxwerfbt.html

[U65] PHP：会话
来源：http://dali.hammf.cn/Article/details/gtsngauxkq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtkgodyhki.html

[U66] PHP：设置 Cookie
来源：http://dali.9152youxi.cn/Article/details/gtwpkqaevv.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pycfn.com/Article/details/gtxbpnwnzt.html

[U67] PHP：处理文件上传
来源：http://dali.shuidangran.top/Article/details/gtbskruosc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtgvbmxmkd.html

[U68] PHP：PDO 连接
来源：http://dali.hnqzz.top/Article/details/gthurnefqo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuanzx.com/Article/details/gtpjojsnsf.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtuyevdisg.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtywefuatf.html

[U70] PHP：PDO 事务
来源：http://dali.snrcjt.cn/Article/details/gtscedeqdz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.haohaochexian.top/Article/details/gtojbxdlvl.html

[U71] PHP：抛出异常
来源：http://dali.fengsongda.top/Article/details/gtboaddito.html

throw new RuntimeException("失败", 500);
来源：http://dali.nwbrower.top/Article/details/gtpudwxxzz.html

[U72] PHP：写错误日志
来源：http://dali.hnxiangtu.top/Article/details/gtnvythhyu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gtjzterekb.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtcdxnopie.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtuqhqxjve.html

[U74] PHP：读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtftofydmy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtsokmmriu.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtskpwitbv.html

composer require psr/container
来源：http://dali.gotoacloud.top/Article/details/gtgjfybkds.html

[U76] PHP：简单路由
来源：http://dali.kuanghao11.cn/Article/details/gtsflwjlnf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hysaishi.cn/Article/details/gtrdscuame.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtqjagrmcd.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gtbivftgpa.html

[U78] PHP：单元测试
来源：http://dali.yongpay.top/Article/details/gtggxgvcic.html

composer require --dev phpunit/phpunit
来源：http://dali.zhiwuduotai.top/Article/details/gtnwfexnaq.html

[U79] PHP：静态分析
来源：http://dali.guowangkeji.top/Article/details/gtygpltxxr.html

composer require --dev phpstan/phpstan
来源：http://dali.jlsjyb.cn/Article/details/gtnuscyikh.html

[U80] PHP：代码规范修复
来源：http://dali.pycfn.com/Article/details/gtlavtejkl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sysykeji.top/Article/details/gtugodbotw.html

[U81] JS：初始化项目
来源：http://dali.xuetiantiany.cn/Article/details/gtgyjcchsu.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtxkqppbdv.html

[U82] JS：package.json 脚本
来源：http://dali.kuanghao11.cn/Article/details/gtdnlyoxss.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cucudq.cn/Article/details/gtasxorfdx.html

[U83] JS：ES Module 导入导出
来源：http://dali.gaohongyu789.top/Article/details/gtewhtxirf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.hywenlv.cn/Article/details/gtxtzwvube.html

[U84] JS：CommonJS 写法
来源：http://dali.shuidangran.top/Article/details/gtnamomntz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hammf.cn/Article/details/gtutnaisyw.html


<!-- 参考信息 -->