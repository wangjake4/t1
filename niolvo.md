代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gt2duaewcma.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2iafynmjh.html

constexpr int N = 10;
来源：http://dali.shzxlz.cn/Article/details/gt2eipxfbxw.html

[S58] C++：命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2mazefhuw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2vbvubuvm.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gt2wlzwdexg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shangyingyoupin.top/Article/details/gt2kzhzngfk.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gt2lfkiiahj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gt2tvttktqi.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gt2wxvyqlqm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yanxiufei.cn/Article/details/gt2uuidjfel.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2rkyuside.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gt2ojufgffc.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gt2jugwuqge.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2pacsqfdo.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gt2wwkeuvzw.html

[T03] Kotlin：字符串模板
来源：http://dali.yuxming.cn/Article/details/gt2fvimprqm.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2oznbworx.html

[T04] Kotlin：空安全
来源：http://dali.yj202588.top/Article/details/gt2vfbtbong.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bmocfcql.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2vhigafoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cashguo.top/Article/details/gt2fbqunsxh.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gt2hblifunj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gt2etjjrusf.html

[T07] Kotlin：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kazmtvwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gt2rbgjaujz.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gt2jzinqkno.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qalojexs.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gt2majyzbvk.html

fun String.exclaim() = this + "!"
来源：http://dali.dianchejie.cn/Article/details/gt2uigrhosa.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gt2yhdcryrv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gt2liyvjjmu.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gt2nwtqedqm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gt2vsbesgio.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2owmewvvr.html

val (a, b) = Pair(1, 2)
来源：http://dali.meibo888.top/Article/details/gt2fanjlovl.html

[T13] Kotlin：只读 Map
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kyhegwuz.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2xhdwtrah.html

[T14] Kotlin：循环
来源：http://dali.cdnleiting.top/Article/details/gt2egljotai.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gt2lvprqkcm.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gt2nfpviouh.html

interface Shape { fun area(): Double }
来源：http://dali.ybcxt.top/Article/details/gt2tbfwbhcf.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2kvdazgyz.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gt2zdxfgqov.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2rsnnpcgq.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gt2eelrebyv.html

[T18] Swift：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gt2elhxkzel.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gt2dyungfpl.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2cfnnhxrt.html

if let n = opt { print(n) }
来源：http://dali.fzhhl.top/Article/details/gt2lazdofcg.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gt2ajcochvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ydzc1.top/Article/details/gt2nouopinx.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2rvsobbyy.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gt2hmpljvst.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gt2bfdfegjo.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2udmrroug.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gt2rbrlsjmf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cwvtgkgy.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbjsfwle.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigufen.top/Article/details/gt2djvbilyt.html

[T25] Swift：结构体
来源：http://dali.svipenyu.cn/Article/details/gt2ativfecv.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bwhqapag.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2cnxjtmku.html

class A: Base { override func f() {} }
来源：http://dali.zhoulong.xyz/Article/details/gt2xspuwlsw.html

[T27] Swift：错误处理
来源：http://dali.kuanghao11.cn/Article/details/gt2fyvyfveg.html

do { try f() } catch { print(error) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2davjtkez.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2koiooycl.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gt2zmmnruug.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2jcvcuixj.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2vkshdxyr.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gt2ytcnkryp.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hlslykeo.html

[T31] Lua：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2uhbhuvny.html

print("Hello")
来源：http://dali.yj20258888.top/Article/details/gt2dluijuss.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gt2jkqizuau.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2yfpojqxv.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qxsprvhl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gt2jcjqxseg.html

[T34] Lua：遍历表
来源：http://dali.cashguo.top/Article/details/gt2wutcsbhw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2zeadkhwk.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gt2tckiypcy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2nmpbtmoc.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2wjxjfnwe.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gt2tsegdswi.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2eyxkvuqd.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqndiihe.html

[T38] Lua：条件
来源：http://dali.chenzaomai.com/Article/details/gt2avzbyvwy.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gt2pgfuameh.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gt2wsgbteaw.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2exjhukeb.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gt2xqxbpynw.html

setmetatable({}, { __index = base })
来源：http://dali.iojbl.cn/Article/details/gt2moytrohl.html

[T41] Perl：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2phlixuxe.html

print "Hello\n";
来源：http://dali.ybcxt.top/Article/details/gt2qjxefryd.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gt2qddcjvkc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2pmtvnumf.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gt2spjhflrq.html

"值: $a"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2anzudfgv.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2pgmgmcze.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iudisglh.html

[T45] Perl：数组遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oyldybqr.html

for my $x (@arr) { print $x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qosjonmh.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cbcewxwo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gt2qllmbzmj.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gt2bvunhlge.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gt2fzzhiksu.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gt2uvmxleeq.html

$s =~ s/old/new/g;
来源：http://dali.kuanghao11.cn/Article/details/gt2ixbjecaw.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gt2zjmxndvn.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2kloamohb.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2bplqcmfa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2mumlhgen.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2xlgouaqw.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2kkjcwjdy.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tbeqandx.html

[T52] Scala：变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzbpkvqo.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2izvhnife.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gt2macdlrrn.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2dwhbuqtv.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gt2cnlzliwj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2dseskcat.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gt2sdgfwgtt.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ovfqzgjy.html

[T56] Scala：样例类
来源：http://dali.zhongyouzk.top/Article/details/gt2aipqgpvq.html

case class User(name: String, age: Int)
来源：http://dali.hongshengwenyu.top/Article/details/gt2udpiopje.html

[T57] Scala：模式匹配
来源：http://dali.wangdashe.top/Article/details/gt2yjdonrhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2egpxqsfb.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gt2vqevoefp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2ydzamkwe.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gt2qmdzefen.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2vdbexuae.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gt2gqtrmtlp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cqqwz.cn/Article/details/gt2tuxqouqm.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2dbhikalf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gt2ubzoowoq.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2cynfvocy.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gt2xgfdpvpf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gt2xcajnnhi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yanxiufei.cn/Article/details/gt2eruplmfn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.pycfn.com/Article/details/gt2volvthfv.html

[U03] Py：加载 .env 配置
来源：http://dali.fengsongda.top/Article/details/gt2ahjxgigd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gt2bygcmvpe.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gt2yxkrekcy.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gt2redhpifs.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gt2iezjhxfc.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gt2btxflvah.html

[U06] Py：合并两个字典
来源：http://dali.yj20258888.top/Article/details/gt2druwkmzv.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ecodztqs.html

[U07] Py：反转字典键值
来源：http://dali.c1oappe.top/Article/details/gt2dswnzrce.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gt2hmgvdbmm.html

[U08] Py：展平二维列表
来源：http://dali.kuanghao11.cn/Article/details/gt2krnoyeew.html

[y for x in nested for y in x]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ywrdquux.html

[U09] Py：字典取最大值的键
来源：http://dali.zycfv.cn/Article/details/gt2cnwnyzjo.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gt2garnkcrl.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gt2ktobnspm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gt2vcsmurxm.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gt2ohtnmhxc.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ovxfqzso.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gt2sdvzypas.html

Counter(arr).most_common(3)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndpqnvua.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gt2doqkaafj.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gt2wuwxwddy.html

[U14] Py：分组收集到列表
来源：http://dali.tianlin.xyz/Article/details/gt2pwhutuba.html

defaultdict(list)
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbszuypr.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gt2izgbgkgh.html

t = time.perf_counter()
来源：http://dali.sufxvd.cn/Article/details/gt2pmxrkqya.html

[U16] Py：命令行参数解析
来源：http://dali.wangdashe.top/Article/details/gt2pimkyhhn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.birdmap.top/Article/details/gt2yoyuwmmo.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gt2eotlgtnb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.kuanghao11.cn/Article/details/gt2wvxbzguw.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gt2zunendyk.html

pat = re.compile(r"\d+")
来源：http://dali.gogol.net.cn/Article/details/gt2vwdrtqdk.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gt2umyrgqrh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangshuangyany.cn/Article/details/gt2roefvdqt.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gt2umruzbbu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oudkitqy.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gt2wbiiwtth.html

@contextlib.contextmanager
来源：http://dali.ydzc1.top/Article/details/gt2mhzdqslo.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gt2phkwrrgm.html

list(zip(*m))
来源：http://dali.vqdsnc.cn/Article/details/gt2zutacmbp.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gt2txapjqih.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pycfn.com/Article/details/gt2btiofade.html

[U24] Py：路径操作
来源：http://dali.ybcxt.top/Article/details/gt2mwrvmvfh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gt2kqekaefk.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gt2uifhiqww.html

csv.DictReader(f)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vkzejbcp.html

[U26] Py：并发下载
来源：http://dali.gotoacloud.top/Article/details/gt2jintiehj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuxming.cn/Article/details/gt2lvrcxqmk.html

[U27] Py：异步 HTTP
来源：http://dali.cashguo.top/Article/details/gt2uhkffxkn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ydzc1.top/Article/details/gt2gaaqdvbv.html

[U28] Py：类型别名
来源：http://dali.jqgfzy.top/Article/details/gt2yrtszwfk.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gt2oasvftnb.html

[U29] Py：属性校验
来源：http://dali.jqgufenzy.top/Article/details/gt2ywksrqtm.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gt2ihmstlak.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2vvozrmqc.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gt2nptcqhrb.html

[U31] Py：单测
来源：http://dali.yangfankeji.com/Article/details/gt2zetbzluw.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gt2xzsfquls.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gt2ynccktqg.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gt2guhwjhto.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gt2omfwndzv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuflsdrm.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gt2nfbxwxvn.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gt2qwaeprpu.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gt2chvdwbce.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gt2ksbeguft.html

[U36] Py：定时任务
来源：http://dali.yj20258888.top/Article/details/gt2mbfzdgrq.html

schedule.every(10).minutes.do(job)
来源：http://dali.fengsongda.top/Article/details/gt2qumjbmkt.html

[U37] Py：读写 Excel
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnrhiutk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gt2fdszwics.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gt2zvocbmss.html

Path(__file__).resolve().parent
来源：http://dali.zycfv.cn/Article/details/gt2vqobrcxv.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gt2qsqlspdh.html

sys.stdout.isatty()
来源：http://dali.xinyue.icu/Article/details/gt2bxskcgtq.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wcjlrows.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gt2rmdfwmtp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gbodqaqk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.9152youxi.cn/Article/details/gt2jrsggzgd.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gt2zezsjfzy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gt2ovbzrmlo.html

[U43] PHP：声明命名空间
来源：http://dali.dianchejie.cn/Article/details/gt2isvlvghz.html

namespace App\Http;
来源：http://dali.gaohongyu789.top/Article/details/gt2vinlmwzj.html

[U44] PHP：开启严格类型
来源：http://dali.gzhubu.top/Article/details/gt2bpfzrdbj.html

declare(strict_types=1);
来源：http://dali.yonumen.top/Article/details/gt2bysbdpzl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.9152youxi.cn/Article/details/gt2hyxkihuk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gt2ohawefsu.html

[U46] PHP：可空类型
来源：http://dali.ydzc1.top/Article/details/gt2xxuvpuhj.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gt2yjuyxuue.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gt2fhnbxwfh.html

int|string $id
来源：http://dali.haohaochexian.top/Article/details/gt2lluddnhr.html

[U48] PHP：纯枚举
来源：http://dali.daxiang520.top/Article/details/gt2xiwdjmmp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2symgwplc.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gt2dmwxdghe.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gt2udrlvrey.html

[U50] PHP：构造器属性提升
来源：http://dali.hywenlv.cn/Article/details/gt2ffnlyyzq.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gt2cazghpqa.html

[U51] PHP：数组解构
来源：http://dali.xziqi.cn/Article/details/gt2bejiljol.html

[$a, $b] = $arr;
来源：http://dali.zhixingplan.top/Article/details/gt2ekehphcd.html

[U52] PHP：箭头函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2clulgksz.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mggnckig.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gt2wocutzzg.html

$v = $a ?? $b ?? "default";
来源：http://dali.yuxming.cn/Article/details/gt2tulgrpgb.html

[U54] PHP：空安全调用
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pdviupua.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gt2ugyzcttg.html

[U55] PHP：match 表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kiihkjsr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gt2yngtneic.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gt2wovycofr.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zegvunky.html

[U57] PHP：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gt2etqvxohf.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gt2vykwzfsu.html

[U58] PHP：数组三件套
来源：http://dali.xziqi.cn/Article/details/gt2qriocqak.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuanzx.com/Article/details/gt2liuznxdd.html

[U59] PHP：自定义排序
来源：http://dali.dashuyun.cn/Article/details/gt2zkprwnbv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yangfankeji.com/Article/details/gt2xgeexstz.html

[U60] PHP：JSON 编解码
来源：http://dali.nwbrower.top/Article/details/gt2umpchhbt.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cashguo.top/Article/details/gt2qxjjsdea.html

[U61] PHP：正则
来源：http://dali.hnqzz.top/Article/details/gt2yphlmkjf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2jzndsijr.html

[U62] PHP：日期对象
来源：http://dali.c1oappe.top/Article/details/gt2nzokvzzd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gt2dkykwcru.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gt2hverpqtl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gt2bhlyoamj.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gt2cjbbklpj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gt2ngkwoqpb.html

[U65] PHP：会话
来源：http://dali.zhengqikj.top/Article/details/gt2lnfbccnj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gt2hwukdthi.html

[U66] PHP：设置 Cookie
来源：http://dali.nanxuanxn.top/Article/details/gt2cizufmvq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.pycfn.com/Article/details/gt2lxzkbnba.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trrfgpup.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daxiang520.top/Article/details/gt2vwbexdwt.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gt2mwsiafkt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jianghu66.top/Article/details/gt2goaueyzh.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gt2innwigyu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.quarkkingdee.top/Article/details/gt2tkllshom.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aodfbqxb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.bjfxy.top/Article/details/gt2regrfwhs.html

[U71] PHP：抛出异常
来源：http://dali.yongpay.top/Article/details/gt2nrmvgwdw.html

throw new RuntimeException("失败", 500);
来源：http://dali.ppjwa.cn/Article/details/gt2sorbsztg.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gt2lcwrdfej.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daria6918.cn/Article/details/gt2zypxmlsv.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqmdfaga.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bmphufae.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gt2ckxwlyzy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gt2ckfifyey.html

[U75] PHP：依赖注入
来源：http://dali.zhijiandao.cn/Article/details/gt2tgvhtrhf.html

composer require psr/container
来源：http://dali.bjfxy.top/Article/details/gt2qhfqbjac.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyyversq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jianghu66.top/Article/details/gt2qblanwle.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gt2fzevaesd.html

composer require twig/twig
来源：http://dali.chenzaomai.com/Article/details/gt2wvruethz.html

[U78] PHP：单元测试
来源：http://dali.ppjwa.cn/Article/details/gt2mekkazmg.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjzkdrwe.html

[U79] PHP：静态分析
来源：http://dali.yanxiufei.cn/Article/details/gt2abswymsn.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gt2jcqjpycc.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gt2atvcoyqp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gt2kktopzfi.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdgicswm.html

npm init -y;  npm i express
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2guqwtudr.html

[U82] JS：package.json 脚本
来源：http://dali.daria6918.cn/Article/details/gt2xqidbgup.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gt2sjcqdgyi.html


<!-- 参考信息 -->