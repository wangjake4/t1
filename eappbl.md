代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gt2xgtuawye.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gt2bzyrjpib.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2pvwuczhn.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2ahvkreed.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tian-w.cn/Article/details/gt2tledudvu.html

[S57] C++：编译期常量
来源：http://dali.kuanghao11.cn/Article/details/gt2nfjywpon.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gt2kyssecsf.html

[S58] C++：命名空间
来源：http://dali.yonumen.top/Article/details/gt2bfvlxtfd.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gt2nalbqbfs.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gt2rrbrnejf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2ytsgjwio.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gt2zqipmivn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gt2tetptblb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2bjearjwp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2emicpzre.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2phjcivgf.html

[T01] Kotlin：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2geyfpdpd.html

println("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2fkckzzyy.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2tpajbcuw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gt2auivwswx.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gt2bkvosjce.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2isvrpsen.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gt2lubimcjl.html

val n: String? = null;  n?.length
来源：http://dali.yanxiufei.cn/Article/details/gt2hqaxidzl.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gt2nqyatimg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ydzc1.top/Article/details/gt2bsltsmrk.html

[T06] Kotlin：集合映射
来源：http://dali.cdnleiting.top/Article/details/gt2dikfzmsq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2vwfqaquv.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2qfbrlhuw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2qdavvdwu.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gt2lzafgnik.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2lxdchcrp.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gt2ljqfbyrf.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gt2zpxggjce.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2oadpzdsp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gt2ywlmyqth.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gt2nlgsvtmg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gt2puqhlluo.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2dcjurelk.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gt2fulnndwt.html

[T13] Kotlin：只读 Map
来源：http://dali.cucudq.cn/Article/details/gt2sxlcsmnr.html

val m = mapOf("a" to 1)
来源：http://dali.fengsongda.top/Article/details/gt2yxmdoord.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2hpmlfcij.html

for (i in 1..10) println(i)
来源：http://dali.nanxinkj.top/Article/details/gt2aipskqbc.html

[T15] Kotlin：接口
来源：http://dali.gzhubu.top/Article/details/gt2fpknrtrt.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2gvamjphi.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2oxsfgydx.html

print("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2vwekvupz.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gt2rsfsbemb.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2sotfrcoi.html

[T18] Swift：字符串插值
来源：http://dali.yueranfly.top/Article/details/gt2ekjbltgf.html

"值: \(b)"
来源：http://dali.jlsjyb.cn/Article/details/gt2oubgvyoe.html

[T19] Swift：可选绑定
来源：http://dali.xziqi.cn/Article/details/gt2jyqmvbyf.html

if let n = opt { print(n) }
来源：http://dali.ydzc1.top/Article/details/gt2meggzlne.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gt2drtewncb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pengpengdd.cyou/Article/details/gt2ejwfnxwk.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gt2zgqhwvhb.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2muoxgmhb.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gt2vsvpeksp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gt2nvddwdlp.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gt2wudgdgvm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gt2lyzcwqmj.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gt2nffsgrsf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cheryme.top/Article/details/gt2npforzns.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gt2ayyegutu.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gt2uqoxltvy.html

[T26] Swift：类与重写
来源：http://dali.hongshengwenyu.top/Article/details/gt2nahkeygg.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gt2hqpqxnwi.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2pqkfvdoa.html

do { try f() } catch { print(error) }
来源：http://dali.mhx1999.top/Article/details/gt2fzyrguxs.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2rwqplxtr.html

enum Color { case red, green }
来源：http://dali.jqgfzy.top/Article/details/gt2qirhkajh.html

[T29] Swift：guard 提前返回
来源：http://dali.zhijiandao.cn/Article/details/gt2llwodtgh.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gt2jnqqmodu.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gt2hemrogey.html

protocol Shape { func area() -> Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2iqpwllet.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2ejkafubh.html

print("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sqnogwjg.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gt2guoctzqa.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2bzvkuqrf.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2lsejppdx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gt2jaqmxrzd.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gt2mhpxopfv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lrfdcpcm.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gt2rktuuglr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gt2dkkeksdf.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2nojbzzbb.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2lokebnsd.html

[T37] Lua：字符串拼接
来源：http://dali.chenzaomai.com/Article/details/gt2hczzakbt.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yhawucrm.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2mcwjyric.html

if x > 0 then print("正") end
来源：http://dali.shzxlz.cn/Article/details/gt2gdnirdkm.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2diybzsbf.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2ppuhmvtg.html

[T40] Lua：元表
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvoptukj.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gt2lwmkuoxq.html

[T41] Perl：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kyunuxmc.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gt2jknznwrm.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gt2ogozyftu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aibaodan.cn/Article/details/gt2dqtyeihl.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2xarfuttc.html

"值: $a"
来源：http://dali.cdnleiting.top/Article/details/gt2wnifmcef.html

[T44] Perl：条件
来源：http://dali.svipenyu.cn/Article/details/gt2pumxqcwz.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2uwnjabdn.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gt2fkomzkpt.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gt2tzhilkss.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gt2ufdyswip.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gt2takzazxz.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkyghffd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtosgkxw.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gt2ytpowzgu.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gt2jwtbintp.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gt2voedawsb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2scdxoevd.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2hfqnjfwb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2phfakwkm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gt2emfaptop.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2mtabwuik.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2chyspqtm.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gt2vrkbawdq.html

val a = 1;  var b = 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2usxbdete.html

[T53] Scala：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2jpfladul.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gt2sgusfhph.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gt2ybllcvcc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gt2gfsgvxyg.html

[T55] Scala：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2wlbqbadx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yvedp.cn/Article/details/gt2laywtnjo.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gt2fpqmvdmv.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gt2htjjhuyw.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gt2avctpgvz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2ufeokmpc.html

[T58] Scala：函数定义
来源：http://dali.ppjwa.cn/Article/details/gt2rulrqkmu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gt2whvkfqud.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gt2pavzuswy.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2syowqpcn.html

[T60] Scala：折叠
来源：http://dali.chenlongwang.top/Article/details/gt2aeosrrth.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gt2ksusnrda.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2nsurbfgw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gt2olnvkgym.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2mbnnbzfz.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gt2xwhfcoub.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gt2gffdcfzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gt2ukabvdzx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gt2kyypvscg.html

[U03] Py：加载 .env 配置
来源：http://dali.jqgufenzy.top/Article/details/gt2rwzhvkcn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cdnleiting.top/Article/details/gt2nbfuxyod.html

[U04] Py：变量调试打印
来源：http://dali.chenjidiqi.icu/Article/details/gt2vxjjtvyy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.snrcjt.cn/Article/details/gt2zjkgeclu.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gt2fyjsciqx.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2lxfcbnrf.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gt2jqxefnpm.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gt2oesorbdj.html

[U07] Py：反转字典键值
来源：http://dali.zycfv.cn/Article/details/gt2kkmmwzog.html

{v: k for k, v in d.items()}
来源：http://dali.jinqigufen.top/Article/details/gt2olzhrkqg.html

[U08] Py：展平二维列表
来源：http://dali.yuxming.cn/Article/details/gt2xrahkztl.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gt2cxpdomkv.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gt2fcdddfei.html

max(d, key=d.get)
来源：http://dali.fzhhl.top/Article/details/gt2rwqmuiqo.html

[U10] Py：按值排序字典
来源：http://dali.quarkkingdee.top/Article/details/gt2fthnadqm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gt2hswrrstn.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gt2hxudbism.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2sqtimnly.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yangfankeji.com/Article/details/gt2kahcvpeh.html

Counter(arr).most_common(3)
来源：http://dali.yongpay.top/Article/details/gt2ipggnoqc.html

[U13] Py：固定长度队列
来源：http://dali.yangfankeji.com/Article/details/gt2hdhodhlh.html

deque(maxlen=10)
来源：http://dali.kuanghao11.cn/Article/details/gt2csanwktw.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gt2ligevtvz.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gt2pywdckis.html

[U15] Py：高精度计时
来源：http://dali.zhiwuduotai.top/Article/details/gt2xuiunhhp.html

t = time.perf_counter()
来源：http://dali.cheryme.top/Article/details/gt2mqyltxom.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gt2idqccujk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gt2npoqbpbo.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gt2celieogc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.9152youxi.cn/Article/details/gt2nicbizvs.html

[U18] Py：预编译正则
来源：http://dali.316326.xyz/Article/details/gt2mtahadea.html

pat = re.compile(r"\d+")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nxlxsbco.html

[U19] Py：正则替换带回调
来源：http://dali.haohaochexian.top/Article/details/gt2anvcgafj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gt2gdcdnbto.html

[U20] Py：缓存函数结果
来源：http://dali.xuetiantiany.cn/Article/details/gt2uxnefzbn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jlsjyb.cn/Article/details/gt2rxhznifa.html

[U21] Py：自定义上下文管理器
来源：http://dali.redwolf501.top/Article/details/gt2ywcjitmv.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gt2dissklsb.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gt2aiwnetcp.html

list(zip(*m))
来源：http://dali.hnxiangtu.top/Article/details/gt2jnadgwtq.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2dumlvfbg.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.vqdsnc.cn/Article/details/gt2zpucciut.html

[U24] Py：路径操作
来源：http://dali.aibaodan.cn/Article/details/gt2qqwvhoul.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhijiandao.cn/Article/details/gt2saoovfum.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gt2tyfvydxn.html

csv.DictReader(f)
来源：http://dali.guowangkeji.top/Article/details/gt2zrcajdds.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gt2rvcqdbre.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.meibo888.top/Article/details/gt2zlxxxcjg.html

[U27] Py：异步 HTTP
来源：http://dali.shuidangran.top/Article/details/gt2kkrntrmd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigfzy.top/Article/details/gt2dvzzwyga.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gt2evkjnvnk.html

UserId = int
来源：http://dali.chenzaomai.com/Article/details/gt2exfsqkyg.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gt2bjwarwmd.html

@property 与 @x.setter 配合
来源：http://dali.cqqwz.cn/Article/details/gt2vbzlbyzv.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2rqmyobqx.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gt2hgjusnyy.html

[U31] Py：单测
来源：http://dali.jinghuilouyu.cn/Article/details/gt2juuiaudx.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2remfeioj.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2lespbnvf.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gt2ssyjjcah.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gt2jxglvbhs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xylfe.cn/Article/details/gt2qxybglpj.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gt2djazkkqg.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gt2ddhxeveu.html

[U35] Py：发送邮件
来源：http://dali.ybcxt.top/Article/details/gt2circjcxb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.dianchejie.cn/Article/details/gt2yzaqonev.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2qhxhkthi.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gt2pafznhba.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gt2ffornjyr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.bjfxy.top/Article/details/gt2upjrngja.html

[U38] Py：获取脚本所在目录
来源：http://dali.yj20258.top/Article/details/gt2voenrpon.html

Path(__file__).resolve().parent
来源：http://dali.quarkkingdee.top/Article/details/gt2agklwtje.html

[U39] Py：判断是否在交互环境
来源：http://dali.yongpay.top/Article/details/gt2iaitjtfh.html

sys.stdout.isatty()
来源：http://dali.yuanzhike.top/Article/details/gt2gbozrply.html

[U40] Py：打印到标准错误
来源：http://dali.316326.xyz/Article/details/gt2lwnjhurt.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gt2zhnqljjt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangdashe.top/Article/details/gt2vjithdld.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npouiqls.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2minvwxtt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.sweek.top/Article/details/gt2fetwwhjd.html

[U43] PHP：声明命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2tpyfgdlu.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gt2tcweqkzt.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gt2zhgywhga.html

declare(strict_types=1);
来源：http://dali.ppjwa.cn/Article/details/gt2vldixzkp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gt2ojrnypgy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2pxqfgjui.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2duuobjgi.html

?string $name = null
来源：http://dali.yvedp.cn/Article/details/gt2fijnostp.html

[U47] PHP：联合类型
来源：http://dali.cheryme.top/Article/details/gt2lchbtwos.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gt2wfwnsjql.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gt2edojaztl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hfpthk.cn/Article/details/gt2hymmwruc.html

[U49] PHP：只读属性
来源：http://dali.zhiwuduotai.top/Article/details/gt2srxcdwou.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gt2ukcxgamh.html

[U50] PHP：构造器属性提升
来源：http://dali.ppjwa.cn/Article/details/gt2qpwdyfal.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gt2yqddnmio.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ocnjhpyb.html

[$a, $b] = $arr;
来源：http://dali.guannengcc.top/Article/details/gt2ylgopnhb.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gt2pinjdvuq.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gt2uedsillr.html

[U53] PHP：空合并运算符
来源：http://dali.dashuyun.cn/Article/details/gt2cfumbzqh.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxgvjgtd.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gt2twzqukvw.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2obrdzipd.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gt2ycjfhryf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gt2vffidfxr.html

[U56] PHP：命名参数
来源：http://dali.aibaodan.cn/Article/details/gt2lpjrszxq.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2nnmtqcat.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2ddiowmnz.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2qkeawwbp.html

[U58] PHP：数组三件套
来源：http://dali.havefunace.top/Article/details/gt2efolnvfi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmussxqs.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gt2ixiokjvk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ppjwa.cn/Article/details/gt2boqyywbu.html

[U60] PHP：JSON 编解码
来源：http://dali.jqgufenzy.top/Article/details/gt2xsdvsigm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sweek.top/Article/details/gt2amkxokvt.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gt2uxqofvsw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.pengpengdd.cyou/Article/details/gt2tuhvfnmv.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gt2uezspyql.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vrqgjznz.html

[U63] PHP：文件读写
来源：http://dali.aibaodan.cn/Article/details/gt2rolflcbk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2mwnundom.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gt2rjjwaudy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gt2sbllqfli.html

[U65] PHP：会话
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ifnvxdek.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gt2jjpfyamg.html

[U66] PHP：设置 Cookie
来源：http://dali.tanke756.top/Article/details/gt2btpymjpu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xuanzx.com/Article/details/gt2ujshwirj.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gt2teehwwvk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2wrebcgqj.html

[U68] PHP：PDO 连接
来源：http://dali.jqgfzy.top/Article/details/gt2ngpcvpqu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gt2mqaegitk.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vxrjxixs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.iojbl.cn/Article/details/gt2bimkvxbn.html

[U70] PHP：PDO 事务
来源：http://dali.daxiang520.top/Article/details/gt2thytbzsw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guannengcc.top/Article/details/gt2enkavgcr.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndamtfhd.html

throw new RuntimeException("失败", 500);
来源：http://dali.tian-w.cn/Article/details/gt2ocwmgofv.html

[U72] PHP：写错误日志
来源：http://dali.xylfe.cn/Article/details/gt2dowiayqz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.mhx1999.top/Article/details/gt2yiqgyzfi.html

[U73] PHP：读取 ini 配置
来源：http://dali.hfpthk.cn/Article/details/gt2wxbxkwcn.html

parse_ini_file("config.ini", true)
来源：http://dali.guowangkeji.top/Article/details/gt2omatssbd.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gt2nsawubrb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txwtxzhz.html

[U75] PHP：依赖注入
来源：http://dali.havefunace.top/Article/details/gt2zqufawil.html

composer require psr/container
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddwedovo.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gt2vlirtidi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gt2pntgatrb.html

[U77] PHP：模板渲染
来源：http://dali.zhoulong.xyz/Article/details/gt2fcndrxdt.html

composer require twig/twig
来源：http://dali.zycfv.cn/Article/details/gt2tsohkgdn.html

[U78] PHP：单元测试
来源：http://dali.316326.xyz/Article/details/gt2dcliwiaf.html

composer require --dev phpunit/phpunit
来源：http://dali.guannengcc.top/Article/details/gt2cnslzaqx.html

[U79] PHP：静态分析
来源：http://dali.jiagoushi.top/Article/details/gt2ldivjzbj.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gt2pbgwrcqu.html

[U80] PHP：代码规范修复
来源：http://dali.jqgfzy.top/Article/details/gt2acbtxqix.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ehwqpu.com/Article/details/gt2yhlexxof.html


<!-- 参考信息 -->