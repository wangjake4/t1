代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gt2klrsqizi.html

[S55] C++：结构化绑定
来源：http://dali.yonumen.top/Article/details/gt2wmvyzvqc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2nmjkufeo.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gt2wrnnkoty.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eianrkcd.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2ghjitzyo.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2sdtbqltm.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gt2uqdhjenk.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gt2fswihyqy.html

[S59] C++：静态断言
来源：http://dali.daxiang520.top/Article/details/gt2fvgbrotu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2znsgeydw.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gt2lfmlnmvy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhongyouzk.top/Article/details/gt2rhipasov.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2hkoxwtux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gt2yvorbidi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2yoieaxfd.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gt2hqrweitt.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2axnltldr.html

[T02] Kotlin：变量
来源：http://dali.pycfn.com/Article/details/gt2salmcshp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhiwuduotai.top/Article/details/gt2utgmhnbv.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gt2tfitztjn.html

"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2hzisxfte.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gt2rtqgjwqy.html

val n: String? = null;  n?.length
来源：http://dali.guannengcc.top/Article/details/gt2pkunjzrf.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gt2rfluoesj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.iojbl.cn/Article/details/gt2ogtsbxat.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2ghktxcls.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.havefunace.top/Article/details/gt2sykyvbvy.html

[T07] Kotlin：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gt2woekwxtq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.snrcjt.cn/Article/details/gt2nsrpaqxz.html

[T08] Kotlin：数据类
来源：http://dali.vqdsnc.cn/Article/details/gt2snwwecwr.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2kxjyqplo.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gt2qyhblgwk.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2bubluubv.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gt2vrdcqdok.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2hsvxnoyx.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2trrisdet.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2qaqvwily.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gt2iisbpkfc.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2ejjwozpe.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gt2xapkgfgk.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2nrelfdbu.html

[T14] Kotlin：循环
来源：http://dali.hongshengwenyu.top/Article/details/gt2nyddaexy.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gt2tvwemagw.html

[T15] Kotlin：接口
来源：http://dali.zhixingplan.top/Article/details/gt2rhmncagf.html

interface Shape { fun area(): Double }
来源：http://dali.daxiang520.top/Article/details/gt2uhuyorco.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2jhqysczn.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2njthnkpu.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2vbsbdcjc.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gt2bwxochyd.html

[T18] Swift：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2lbajwrkl.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qucsonsx.html

[T19] Swift：可选绑定
来源：http://dali.cucudq.cn/Article/details/gt2wkiztxoe.html

if let n = opt { print(n) }
来源：http://dali.hnqzz.top/Article/details/gt2enxxzvow.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gt2gziabgcv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gt2lwyslwqt.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2prcvpoyg.html

for x in a { print(x) }
来源：http://dali.chenzaomai.com/Article/details/gt2dnkwbalk.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gt2toziqzmk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2kvnrnyub.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gt2vrzjtheb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gt2styszfcj.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gt2xuevfppc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ycqhhjkc.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gt2vitvcjwq.html

struct P { var x: Int }
来源：http://dali.zdqjudy.top/Article/details/gt2hwebebpv.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2xysudncv.html

class A: Base { override func f() {} }
来源：http://dali.yanxiufei.cn/Article/details/gt2rhafsdud.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2vmhdqniq.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gt2pwsqxjkt.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gt2gtyyvqni.html

enum Color { case red, green }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zafoaugb.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gt2lngqhyyx.html

guard let x = opt else { return }
来源：http://dali.jinqigfzy.top/Article/details/gt2zvljmdqk.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2goygbfza.html

protocol Shape { func area() -> Double }
来源：http://dali.zhoulong.xyz/Article/details/gt2qfjpcvey.html

[T31] Lua：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2jptmssnp.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2ghgdvvst.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2atiaowak.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gt2ubbquipd.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2iwhimpqh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2esebujha.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gt2qcrrjmfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2tlpllvma.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gt2dmvhtpiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sysykeji.top/Article/details/gt2dampkriw.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2pwiwqcwu.html

function add(a, b) return a + b end
来源：http://dali.zhoulong.xyz/Article/details/gt2fexishpp.html

[T37] Lua：字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gt2xfqagcxi.html

"a" .. "b"
来源：http://dali.jqgufenzy.top/Article/details/gt2facnnlkm.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gt2xlnzwdme.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gt2mgspdvtr.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2tecosqko.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gt2nlyurjov.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gt2zftfaerj.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gt2nqcpmowh.html

[T41] Perl：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2mpfobyfj.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gt2ghleblzo.html

[T42] Perl：变量类型
来源：http://dali.xuanzx.com/Article/details/gt2nnswxkyc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.mhx1999.top/Article/details/gt2lhoeevxt.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2bkehwddm.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gt2wzzryzlc.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gt2gvavlxps.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gt2uontxazl.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gt2jmlosqqq.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gt2cuotpqaj.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gt2cdbdkjem.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gt2fcdfeacr.html

[T47] Perl：正则捕获
来源：http://dali.cqqwz.cn/Article/details/gt2dmilqenp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.smart0.xyz/Article/details/gt2nmxngobc.html

[T48] Perl：正则替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etrmeokk.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2footbkno.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ymbueecs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2aimmxfvd.html

[T50] Perl：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gt2mrmazyuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gt2txsvopqk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gt2tidahftb.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2ppgvsjpb.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zmpswejm.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gt2qdimohca.html

val a = 1;  var b = 2
来源：http://dali.cashguo.top/Article/details/gt2lxltvomq.html

[T53] Scala：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gt2lzacaipn.html

s"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gt2mqcbwqsj.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gt2pprkwotg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wioflbic.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gt2fixfiscx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2whrwmedr.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gt2gcqllnum.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cztzxell.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2cgaxtqej.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gt2iriposqh.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2rajqwnek.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2driddjwl.html

[T59] Scala：循环
来源：http://dali.aibaodan.cn/Article/details/gt2zmxetern.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gt2icrmvubv.html

[T60] Scala：折叠
来源：http://dali.tanke756.top/Article/details/gt2yakzumuw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gt2frsiwrhd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2ryeyntoi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjydwdhm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2xeirocwc.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gt2hnanxvgq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yanxiufei.cn/Article/details/gt2ndczepbk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2cmwtaham.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ychczsyc.html

[U03] Py：加载 .env 配置
来源：http://dali.xinyue.icu/Article/details/gt2uepgmdah.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zdqjudy.top/Article/details/gt2ugegacrv.html

[U04] Py：变量调试打印
来源：http://dali.ivvv.top/Article/details/gt2nzazcltv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hammf.cn/Article/details/gt2tqawaetg.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wujevhnj.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gt2ofzmwses.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2higejbmc.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gt2daopwhyd.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2qjdzgcix.html

{v: k for k, v in d.items()}
来源：http://dali.yueranfly.top/Article/details/gt2nswavded.html

[U08] Py：展平二维列表
来源：http://dali.zhijiandao.cn/Article/details/gt2wxziuwvu.html

[y for x in nested for y in x]
来源：http://dali.yongpay.top/Article/details/gt2vbtndwmk.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gt2gwqznccy.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gt2qryshvbv.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2dwsnmahz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhengqikj.top/Article/details/gt2cagytrqv.html

[U11] Py：生成器表达式
来源：http://dali.redwolf501.top/Article/details/gt2lhhdanvf.html

(x * 2 for x in arr)
来源：http://dali.zhengqikj.top/Article/details/gt2crjrtqoz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sxryk.cn/Article/details/gt2lxtwqnmw.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gt2ragynupv.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gt2natpmixa.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gt2pocynhqh.html

[U14] Py：分组收集到列表
来源：http://dali.sufxvd.cn/Article/details/gt2tftyefsh.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gt2skvobxcx.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gt2jhurztob.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gt2xzpnduvh.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gt2ppxgouil.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gt2zlrybchv.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjcketcy.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ydzc1.top/Article/details/gt2gqinxecm.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gt2ftnmdbmq.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2qpcizlhf.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2cgehvjha.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj202588.top/Article/details/gt2pwwrulzt.html

[U20] Py：缓存函数结果
来源：http://dali.shuidangran.top/Article/details/gt2nvptchkg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tianlin.xyz/Article/details/gt2yxzujrgs.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gt2ehwxhmcq.html

@contextlib.contextmanager
来源：http://dali.jianghu66.top/Article/details/gt2lvwmaldw.html

[U22] Py：矩阵转置
来源：http://dali.9152youxi.cn/Article/details/gt2oemywfxm.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2bxakclcl.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cqxizvnc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zmccsfma.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gt2aectchaf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2eyaffjcj.html

[U25] Py：CSV 按字典读
来源：http://dali.jianghu66.top/Article/details/gt2npkjzeqb.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2mdnntdum.html

[U26] Py：并发下载
来源：http://dali.jqgfzy.top/Article/details/gt2lwyjkrdp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gt2pgduasao.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uaioafzg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gt2oochedua.html

[U28] Py：类型别名
来源：http://dali.redwolf501.top/Article/details/gt2fjhwcaqk.html

UserId = int
来源：http://dali.zhongyouzk.top/Article/details/gt2ljxxegjj.html

[U29] Py：属性校验
来源：http://dali.xziqi.cn/Article/details/gt2pkhzzgid.html

@property 与 @x.setter 配合
来源：http://dali.tian-w.cn/Article/details/gt2bpqefeft.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gt2cpknhnsp.html

@dataclass(slots=True)
来源：http://dali.sxryk.cn/Article/details/gt2yeygudox.html

[U31] Py：单测
来源：http://dali.nanxuanxn.top/Article/details/gt2tcqrshrb.html

python -m pytest -q
来源：http://dali.dianchejie.cn/Article/details/gt2qpmuemlh.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gt2tpofdsqm.html

ruff format . && ruff check --fix .
来源：http://dali.cqqwz.cn/Article/details/gt2ijvkukgx.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gt2xarxozdz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gt2ngcrevwb.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gt2wfbwjayp.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gt2bzwfyhhc.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdlxzbyh.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gt2hlypwgdm.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gt2njuwppio.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gt2xhfmhnlt.html

[U37] Py：读写 Excel
来源：http://dali.dashuyun.cn/Article/details/gt2zpztghgn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sxryk.cn/Article/details/gt2ainodoih.html

[U38] Py：获取脚本所在目录
来源：http://dali.cqqwz.cn/Article/details/gt2fzdzrdrt.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gt2ipnbkcel.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gt2qywcbtnu.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gt2eufhnmsr.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gt2zrkfhajf.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2mnevwmus.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gt2dwpeacwt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.316326.xyz/Article/details/gt2uzuiuiym.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gt2jkdfmwwd.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gt2oaavcdrc.html

[U43] PHP：声明命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gvzhrpbm.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2gskuompk.html

[U44] PHP：开启严格类型
来源：http://dali.cqqwz.cn/Article/details/gt2dnlxslnr.html

declare(strict_types=1);
来源：http://dali.hfpthk.cn/Article/details/gt2ldakkxmf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhengqikj.top/Article/details/gt2zkdtwfwk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2qvsrdqqw.html

[U46] PHP：可空类型
来源：http://dali.xinyue.icu/Article/details/gt2uhzogtod.html

?string $name = null
来源：http://dali.quarkkingdee.top/Article/details/gt2ynpwprkw.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2ejpwodow.html

int|string $id
来源：http://dali.wangshuangyany.cn/Article/details/gt2hrtndekh.html

[U48] PHP：纯枚举
来源：http://dali.sweek.top/Article/details/gt2fhascozk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zycfv.cn/Article/details/gt2mforedcz.html

[U49] PHP：只读属性
来源：http://dali.xuanzx.com/Article/details/gt2jjtzsmjd.html

public readonly string $name
来源：http://dali.cheryme.top/Article/details/gt2ghpqmjqx.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gt2rjncbush.html

public function __construct(private int $id) {}
来源：http://dali.fengsongda.top/Article/details/gt2xsnirkfy.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gt2iycaeunw.html

[$a, $b] = $arr;
来源：http://dali.xziqi.cn/Article/details/gt2gxgmcizd.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2uzojixii.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2kqwkkpym.html

[U53] PHP：空合并运算符
来源：http://dali.andypj.xyz/Article/details/gt2epbcljpv.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinqigfzy.top/Article/details/gt2pqgfhkiv.html

[U54] PHP：空安全调用
来源：http://dali.tian-w.cn/Article/details/gt2prycttfz.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2vtwquenu.html

[U55] PHP：match 表达式
来源：http://dali.snrcjt.cn/Article/details/gt2xikgksee.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sysykeji.top/Article/details/gt2dzgweyvc.html

[U56] PHP：命名参数
来源：http://dali.nanxuanxn.top/Article/details/gt2kazghazk.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ztocdxih.html

[U57] PHP：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gt2xnrefxki.html

"值: {$a}"
来源：http://dali.wangdashe.top/Article/details/gt2zxzoeifg.html

[U58] PHP：数组三件套
来源：http://dali.xziqi.cn/Article/details/gt2phjjkosy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nanxinkj.top/Article/details/gt2wapscyhm.html

[U59] PHP：自定义排序
来源：http://dali.yuxming.cn/Article/details/gt2yxwkxpou.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zuguxnid.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gt2jabixgyq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daxiang520.top/Article/details/gt2ltnvgled.html

[U61] PHP：正则
来源：http://dali.c1oappe.top/Article/details/gt2vfpcqofv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gt2cdneswxj.html

[U62] PHP：日期对象
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zyulbwaj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2wcgcmxom.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gt2sappjxvj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gt2lpbfprvm.html

[U64] PHP：目录遍历
来源：http://dali.jiagoushi.top/Article/details/gt2rlegrpqv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2ivhmjqte.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gt2coscldzl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gt2plqlamrr.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zpzozslj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gt2zptqnuti.html

[U67] PHP：处理文件上传
来源：http://dali.cqqwz.cn/Article/details/gt2bcbgahci.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sufxvd.cn/Article/details/gt2ndpeeekx.html

[U68] PHP：PDO 连接
来源：http://dali.yongpay.top/Article/details/gt2wqyilhfy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnqzz.top/Article/details/gt2wwvjaxsl.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gt2wkepcfet.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gt2gfttcsxf.html

[U70] PHP：PDO 事务
来源：http://dali.tanke756.top/Article/details/gt2lhxzmgof.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dianchejie.cn/Article/details/gt2mdfrdoxj.html

[U71] PHP：抛出异常
来源：http://dali.cdnleiting.top/Article/details/gt2ckfuafdh.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258888.top/Article/details/gt2sprouolw.html

[U72] PHP：写错误日志
来源：http://dali.cdnleiting.top/Article/details/gt2bmndsucj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gt2yvaunjxy.html

[U73] PHP：读取 ini 配置
来源：http://dali.jianghu66.top/Article/details/gt2ybxhdctq.html

parse_ini_file("config.ini", true)
来源：http://dali.yanxiufei.cn/Article/details/gt2svrzzwgm.html

[U74] PHP：读取环境变量
来源：http://dali.xinyue.icu/Article/details/gt2ungxfvfa.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gt2wkgzljsn.html

[U75] PHP：依赖注入
来源：http://dali.jlsjyb.cn/Article/details/gt2pqgefozz.html

composer require psr/container
来源：http://dali.ppjwa.cn/Article/details/gt2bjpvnchz.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nlsbkdft.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gt2ubyprrmt.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gt2dqyntemg.html

composer require twig/twig
来源：http://dali.jinqigufen.top/Article/details/gt2vewfjfdr.html

[U78] PHP：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gt2mqcysgdu.html

composer require --dev phpunit/phpunit
来源：http://dali.vqdsnc.cn/Article/details/gt2pihxqqhs.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2xtiwghwh.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gt2vzngzkqu.html

[U80] PHP：代码规范修复
来源：http://dali.havefunace.top/Article/details/gt2exdxybug.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gt2afjsuqal.html


<!-- 参考信息 -->