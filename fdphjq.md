代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2wkyewlbd.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gt2oknqmfuo.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2evyipuep.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gt2lwellxoc.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gt2nysppvld.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2taisrajx.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gt2gwtxnwmk.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gt2bktcxbhh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxinkj.top/Article/details/gt2hcjovyoz.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gt2cuywloqa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgfzy.top/Article/details/gt2afwubdpc.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gt2encwqkmx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gt2tfztclnl.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gt2xloyskbh.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gt2hwceusph.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gt2mjilmzst.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2soopfzgt.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gt2nljddypr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gt2yvynayih.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2uovouchq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yuanzhike.top/Article/details/gt2uuglwaqm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kzmejspy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gt2npmgqmko.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eylctofo.html

[T01] Kotlin：Hello World
来源：http://dali.daria6918.cn/Article/details/gt2ikwfmzek.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gt2dlwiztgn.html

[T02] Kotlin：变量
来源：http://dali.jyoumei.cn/Article/details/gt2oihhpzkr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gt2scgyrxur.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gt2qtcmcspy.html

"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gt2hsnmxpyb.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gt2shdbtcwu.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2zxqaprkk.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gt2znkmqtyh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gt2lapkmdpk.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gt2krfyysgo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2fgmvefal.html

[T07] Kotlin：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkencfzk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2gbuftvsj.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2vgytlcvx.html

data class User(val name: String, val age: Int)
来源：http://dali.cucudq.cn/Article/details/gt2slvhmowe.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2fetzadtv.html

fun String.exclaim() = this + "!"
来源：http://dali.c1oappe.top/Article/details/gt2gneigmkw.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gt2kniedcrn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cucudq.cn/Article/details/gt2udrupjri.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2ihfouifx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2eqnecuwc.html

[T12] Kotlin：解构声明
来源：http://dali.andypj.xyz/Article/details/gt2xmbjhwmj.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2vrttmuje.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gt2jwfojjaq.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2wlcxmlth.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gt2qmrkjmnq.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hvuamubj.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2ubezqhfy.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2ztgoynsl.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhgzndwv.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2bohogrya.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjnxcynw.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2sswmiipg.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gt2avpzrfcz.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gt2ahziglyy.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gt2hvulbkms.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gt2gyihmlvo.html

[T20] Swift：数组操作
来源：http://dali.yangfankeji.com/Article/details/gt2zuludsml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gt2vtsjnidd.html

[T21] Swift：遍历
来源：http://dali.fzhhl.top/Article/details/gt2pkkdtmrq.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yupnrqvu.html

[T22] Swift：字典
来源：http://dali.sysykeji.top/Article/details/gt2ztagcbzf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yanxiufei.cn/Article/details/gt2nxomnica.html

[T23] Swift：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2arfbefdu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gt2xggisvtm.html

[T24] Swift：闭包
来源：http://dali.ehwqpu.com/Article/details/gt2vqsszxia.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2wnbnbrfg.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gt2xccdrbnu.html

struct P { var x: Int }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yizgqnsa.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gt2yarengwl.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gt2ockssmis.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gt2bowcrdag.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gt2quehcvxi.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gt2dmnybxid.html

enum Color { case red, green }
来源：http://dali.nwbrower.top/Article/details/gt2fonshpba.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2znkelnzl.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2vwkvmhiz.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gt2tvdeodiu.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gt2uplojwbp.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2wslgitox.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tufbkfes.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2snzhllqo.html

local a = 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2hvqpoaou.html

[T33] Lua：表（数组）
来源：http://dali.meibo888.top/Article/details/gt2owaidien.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.mhx1999.top/Article/details/gt2yiziayxg.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gt2vjjrgucl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gt2aefafvoz.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gt2oxbszbsg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gt2pkhtfesg.html

[T36] Lua：函数
来源：http://dali.ppjwa.cn/Article/details/gt2yhlsjzpw.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gt2uxgtiqyv.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2bvbvsfkq.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gt2idqtjqft.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gt2cbzkquff.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gt2xqyusfmf.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gt2sfppivrx.html

string.find(s, "%d+")
来源：http://dali.bjfxy.top/Article/details/gt2jdcwomul.html

[T40] Lua：元表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2thgllkjj.html

setmetatable({}, { __index = base })
来源：http://dali.ybcxt.top/Article/details/gt2migksbxz.html

[T41] Perl：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2grnykgkl.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2amqdybzs.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2vnsjxvqa.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gt2lkzyxina.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gt2wblqowzu.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gt2xauxhldd.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gt2caoumiot.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2zzamnjkd.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gt2bsrgxkzs.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gt2azimpbzd.html

[T46] Perl：哈希操作
来源：http://dali.gotoacloud.top/Article/details/gt2qfgsnuef.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2smrhrrzd.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gt2eeufnwzm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ogxyrdgn.html

[T48] Perl：正则替换
来源：http://dali.zycfv.cn/Article/details/gt2mejmsygc.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gt2ovknmmgg.html

[T49] Perl：函数
来源：http://dali.xziqi.cn/Article/details/gt2nlofihan.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2fyhrxvoo.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2sfavngza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gt2hsgsjths.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gt2rireaqfv.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gt2sapwuipd.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gt2muodpdrg.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gt2oufvojxf.html

val a = 1;  var b = 2
来源：http://dali.havefunace.top/Article/details/gt2jnxzjufu.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2aqomecqt.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gt2mruoehhs.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2kcxqokjm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gt2bshbtfxb.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mygpfqyi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gt2dxuwmezz.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gt2qzdfziyl.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gt2tipdpfrc.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2tiffvuha.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gt2wouwqjux.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gt2zasrbnqc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2sdvmncpf.html

[T59] Scala：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csnqsmlo.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llaoatwa.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2aodmvymz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gt2ioewoial.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2ppykldip.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ydzc1.top/Article/details/gt2ktvfklpq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ifllssgj.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gt2bitrfvyl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gt2xumadocn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cheryme.top/Article/details/gt2nxhejqmh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2ijywcfua.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gt2hposqfor.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2ziuwtsok.html

[U04] Py：变量调试打印
来源：http://dali.gaohongyu789.top/Article/details/gt2ixellipe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgwkfdfw.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gt2grbwovuq.html

list(dict.fromkeys(arr))
来源：http://dali.svipenyu.cn/Article/details/gt2icikjpsb.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gt2owuumsml.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gt2edbdhbbd.html

[U07] Py：反转字典键值
来源：http://dali.redwolf501.top/Article/details/gt2vxnstmus.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2rtvrvlgq.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2esjttvxr.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gt2yeulzcyj.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gt2xdvdcpwa.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gt2fybrtngf.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2brkpjpqf.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gt2cdqkweuo.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssvklyes.html

(x * 2 for x in arr)
来源：http://dali.yonumen.top/Article/details/gt2pfuohqoq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gt2pnkwwtwp.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gt2dobexltm.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gt2lbjsiqwu.html

deque(maxlen=10)
来源：http://dali.shangyingyoupin.top/Article/details/gt2gztdzayc.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gt2efyuaemz.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gt2kpbzhrhz.html

[U15] Py：高精度计时
来源：http://dali.316326.xyz/Article/details/gt2hzuhkkuz.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gt2ohbsyxsk.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gt2rqjajcsn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhongyouzk.top/Article/details/gt2gpyfxqjj.html

[U17] Py：初始化日志
来源：http://dali.chenlongwang.top/Article/details/gt2bedzpxgw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gt2kcvwdoyf.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gt2bbrxvhzr.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vxuvdrbi.html

[U19] Py：正则替换带回调
来源：http://dali.kuanghao11.cn/Article/details/gt2mytqxhpy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gt2dmfsflqr.html

[U20] Py：缓存函数结果
来源：http://dali.9152youxi.cn/Article/details/gt2dhooecym.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xziqi.cn/Article/details/gt2zsgnjyih.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfnhjqax.html

@contextlib.contextmanager
来源：http://dali.yanxiufei.cn/Article/details/gt2eueakoyn.html

[U22] Py：矩阵转置
来源：http://dali.ivvv.top/Article/details/gt2idpzldrk.html

list(zip(*m))
来源：http://dali.hywenlv.cn/Article/details/gt2clcczehw.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2pytgilaz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2twaaioip.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2asaqagem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qqhxwxwy.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gt2argzwmgb.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gt2ihujrkgt.html

[U26] Py：并发下载
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qoepkpay.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gt2fzyboocn.html

[U27] Py：异步 HTTP
来源：http://dali.zhongyouzk.top/Article/details/gt2lwvxzbgk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gt2pjvgtlke.html

[U28] Py：类型别名
来源：http://dali.chenlongwang.top/Article/details/gt2sltkctix.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gt2tsdgqrdu.html

[U29] Py：属性校验
来源：http://dali.cashguo.top/Article/details/gt2sznowsxp.html

@property 与 @x.setter 配合
来源：http://dali.mhx1999.top/Article/details/gt2kaajokii.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gt2vvkxlyfv.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gt2cwupmhji.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gt2wnbnkelz.html

python -m pytest -q
来源：http://dali.xziqi.cn/Article/details/gt2ksbvgsnn.html

[U32] Py：代码格式化
来源：http://dali.sweek.top/Article/details/gt2ubikixvz.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2rncgmikg.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gt2pgdsuqxg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gt2qfukejci.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2xjllpvec.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2fxanxubo.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2ktfxlxar.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.mhx1999.top/Article/details/gt2bjyjjaqo.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2syeyontj.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhijiandao.cn/Article/details/gt2afuzclpi.html

[U37] Py：读写 Excel
来源：http://dali.nanxuanxn.top/Article/details/gt2zmeehopb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gt2zgjllmqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gt2ucwqketk.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gt2orxkbnwp.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gt2btwqwfdw.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulzvsoax.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gt2mqxrolyi.html

print("err", file=sys.stderr)
来源：http://dali.shzxlz.cn/Article/details/gt2ttrqkwgf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pycfn.com/Article/details/gt2ysvkalcy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ppjwa.cn/Article/details/gt2rxurbjga.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gt2hqufqlst.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tian-w.cn/Article/details/gt2ptdifffh.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gt2wiirdscg.html

namespace App\Http;
来源：http://dali.ydzc1.top/Article/details/gt2vuauoiom.html

[U44] PHP：开启严格类型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvfcfnii.html

declare(strict_types=1);
来源：http://dali.yueranfly.top/Article/details/gt2rvxkjpaj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ppjwa.cn/Article/details/gt2dyacqoyr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2rjopgfoi.html

[U46] PHP：可空类型
来源：http://dali.yanxiufei.cn/Article/details/gt2wyvpqtdk.html

?string $name = null
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sasponpl.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gt2kzhkeppb.html

int|string $id
来源：http://dali.zhiwuduotai.top/Article/details/gt2oijrjxug.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2pklusxau.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.dashuyun.cn/Article/details/gt2nluulusu.html

[U49] PHP：只读属性
来源：http://dali.chenjidiqi.icu/Article/details/gt2emcpvafo.html

public readonly string $name
来源：http://dali.zhoulong.xyz/Article/details/gt2ozgnpadh.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gt2ttaexgfn.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gt2nlzgatfd.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gt2pzorhars.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gt2uswgcthp.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2jkgqpvel.html

$double = fn($x) => $x * 2;
来源：http://dali.snrcjt.cn/Article/details/gt2ljrybptc.html

[U53] PHP：空合并运算符
来源：http://dali.ppjwa.cn/Article/details/gt2ekrnpmkh.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gt2qdnhrjnj.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2onxsxdha.html

$obj?->method()
来源：http://dali.tanke756.top/Article/details/gt2scfvinoy.html

[U55] PHP：match 表达式
来源：http://dali.cdnleiting.top/Article/details/gt2jnwbytze.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2tyymdqpx.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2mhhafuva.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2eydjcntx.html

[U57] PHP：字符串插值
来源：http://dali.sweek.top/Article/details/gt2qytwdhxc.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jcbxzhkz.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gt2idsffdkj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssqmdlmq.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gt2vumclygi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2cgdfmqfu.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gt2ijfdpsek.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.dianchejie.cn/Article/details/gt2qwhzwlty.html

[U61] PHP：正则
来源：http://dali.hfpthk.cn/Article/details/gt2ogileqfu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2wgafvcli.html

[U62] PHP：日期对象
来源：http://dali.gogol.net.cn/Article/details/gt2xqnxajjr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gt2truuucti.html

[U63] PHP：文件读写
来源：http://dali.jqgufenzy.top/Article/details/gt2dynxmckb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gt2cbymxqmt.html

[U64] PHP：目录遍历
来源：http://dali.yvedp.cn/Article/details/gt2epnuvbib.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.meibo888.top/Article/details/gt2dwvsbirv.html

[U65] PHP：会话
来源：http://dali.tianlin.xyz/Article/details/gt2jvuwsvoh.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2jydfuzrc.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gt2zcdzmjmx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gt2wplqfwkn.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gt2ldslpocl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gt2husurxpy.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigufen.top/Article/details/gt2sgzgeoun.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gt2emlxixns.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2rckxstup.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gt2yhytrpzd.html

[U70] PHP：PDO 事务
来源：http://dali.pycfn.com/Article/details/gt2lqpekxpf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fzhhl.top/Article/details/gt2amjlydmh.html

[U71] PHP：抛出异常
来源：http://dali.jiagoushi.top/Article/details/gt2wbmbqeov.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2cyiigvum.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gt2ejokxlnh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj202588.top/Article/details/gt2sewiahhm.html

[U73] PHP：读取 ini 配置
来源：http://dali.nwbrower.top/Article/details/gt2gmmxctro.html

parse_ini_file("config.ini", true)
来源：http://dali.gotoacloud.top/Article/details/gt2qcywadba.html

[U74] PHP：读取环境变量
来源：http://dali.meibo888.top/Article/details/gt2kfccyjki.html

getenv("APP_ENV") ?: "production"
来源：http://dali.sufxvd.cn/Article/details/gt2zmlrdehw.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gt2jjwugpwa.html

composer require psr/container
来源：http://dali.yj20258.top/Article/details/gt2alpipjdf.html

[U76] PHP：简单路由
来源：http://dali.feifeiyinyue.top/Article/details/gt2ajxqkvgj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yvedp.cn/Article/details/gt2rxpzsogp.html


<!-- 参考信息 -->