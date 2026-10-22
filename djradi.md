代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gt2nuwwvoby.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gt2uksjlpic.html

std::vector<int> w = std::move(v);
来源：http://dali.tanke756.top/Article/details/gt2djgoaszx.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gt2vtlhvwui.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2cipluhkj.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gt2mtassrxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sufxvd.cn/Article/details/gt2hkqtiumi.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2uvmoimys.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ukxdkqru.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gt2khmvtruu.html

constexpr int N = 10;
来源：http://dali.nwbrower.top/Article/details/gt2oqbqegpn.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gt2ilfpmdkm.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gt2pqeapjdj.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gt2lvnkmclb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gt2xvgrwmxy.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2czdgafue.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wartpmqh.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2urobqdcu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gt2yszevwtb.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2vuelvuds.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2sqapdhzk.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2dqnkscke.html

[T02] Kotlin：变量
来源：http://dali.chenlongwang.top/Article/details/gt2vdrkikqi.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2zzitugvu.html

[T03] Kotlin：字符串模板
来源：http://dali.mhx1999.top/Article/details/gt2eogszxhn.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gt2djcucibs.html

[T04] Kotlin：空安全
来源：http://dali.mhx1999.top/Article/details/gt2fjpevsdp.html

val n: String? = null;  n?.length
来源：http://dali.vqdsnc.cn/Article/details/gt2upqihqtm.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gt2hyoiauuu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gt2csxhhlsg.html

[T06] Kotlin：集合映射
来源：http://dali.xziqi.cn/Article/details/gt2cnzjxxyj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gt2jkhycmia.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gt2hhtgndex.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jqgufenzy.top/Article/details/gt2gxkhixdh.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gt2pgzavdou.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gt2lujhgkwr.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gt2npsuuixh.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gt2mkagpjjp.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2qkgslamf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sweek.top/Article/details/gt2jvsqljjn.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gt2spxpgwvd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gt2estjsrlc.html

[T12] Kotlin：解构声明
来源：http://dali.gaohongyu789.top/Article/details/gt2httquvyy.html

val (a, b) = Pair(1, 2)
来源：http://dali.gogol.net.cn/Article/details/gt2swhkbnzp.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gt2afmzahvz.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigufen.top/Article/details/gt2avicbhgl.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2iphuffsc.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gt2pnmsluty.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mhszrxph.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gt2oqmhkvpx.html

[T16] Swift：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2dktywpsc.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gt2njgszajr.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2qkotgpby.html

var a = 1;  let b = 2
来源：http://dali.jqgfzy.top/Article/details/gt2xbwebpii.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2rhsrktxj.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gt2wirklqme.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gt2dhmyztwf.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ztilnqwy.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gt2lrizwipw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2cymirjms.html

[T21] Swift：遍历
来源：http://dali.nwbrower.top/Article/details/gt2zqmvwido.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gt2jbrdfwre.html

[T22] Swift：字典
来源：http://dali.iojbl.cn/Article/details/gt2fdmwqdgh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gt2gjaryapk.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gt2nqdlldvx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daxiang520.top/Article/details/gt2nyebppvk.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gt2ksuozfwa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gt2cdqhqzxp.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2amoudfmj.html

struct P { var x: Int }
来源：http://dali.yj20258.top/Article/details/gt2gffvkorp.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gt2yakudpwm.html

class A: Base { override func f() {} }
来源：http://dali.jyoumei.cn/Article/details/gt2ibwtdtit.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gt2ryxqnppy.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2vjyqhkdq.html

[T28] Swift：枚举
来源：http://dali.hywenlv.cn/Article/details/gt2seexfzte.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gt2awuytpdd.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2rrrixqht.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gt2urdqsutu.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gt2wcbpvwso.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gt2zpfetcss.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2ksnlocwg.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2wzvcayht.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gt2sbkgulxq.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2pbcjlgqw.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zymegaxf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nwbrower.top/Article/details/gt2bdrjdqns.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pcmjdgpa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daxiang520.top/Article/details/gt2icaudyqu.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gt2ecdiciar.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2elhonqsw.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gt2aoquyjav.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjasirod.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gt2ydfiqkcl.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gt2hwixulmd.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gt2nhaduwfl.html

if x > 0 then print("正") end
来源：http://dali.daria6918.cn/Article/details/gt2mfpqukqh.html

[T39] Lua：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gt2ewqeqcoi.html

string.find(s, "%d+")
来源：http://dali.yanxiufei.cn/Article/details/gt2czcebxcn.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gt2qlnwzhuh.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnegxrhy.html

[T41] Perl：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2wagvhbay.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gt2vzsnoerp.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gt2mdtucoxs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guannengcc.top/Article/details/gt2itrscdtt.html

[T43] Perl：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2gblllsmq.html

"值: $a"
来源：http://dali.nwbrower.top/Article/details/gt2tzyfhnjw.html

[T44] Perl：条件
来源：http://dali.mhx1999.top/Article/details/gt2ruwcrvjo.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gt2tnaadfra.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gt2ptdznmyx.html

for my $x (@arr) { print $x; }
来源：http://dali.yj202588.top/Article/details/gt2ipxsomro.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2iykeyumt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2yjuvectk.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gt2gfszfqwy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2yldwdzrb.html

[T48] Perl：正则替换
来源：http://dali.gotoacloud.top/Article/details/gt2iutavtmc.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gt2osqnrzlt.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2mmmraksp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gt2caewejzn.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2ebzfupsr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gt2vjpghodp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gt2gaodeeud.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2svtfjbtc.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2evxlvxcq.html

[T52] Scala：变量
来源：http://dali.fzhhl.top/Article/details/gt2hhgddyzm.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfkiqhky.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gt2afujpwjr.html

s"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gt2fiqyrzip.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gt2vszizgkl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2kdprbpvq.html

[T55] Scala：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gt2fweoqqxw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gt2nhmvizfl.html

[T56] Scala：样例类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bdvxdqij.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gt2dogmppug.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2lfupdgve.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gt2yprgaysd.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjqeekqg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2uddfgdaw.html

[T59] Scala：循环
来源：http://dali.316326.xyz/Article/details/gt2mabqmsth.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2gonsafju.html

[T60] Scala：折叠
来源：http://dali.yanxiufei.cn/Article/details/gt2hvpssomw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gt2apbincxx.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2wyemhzob.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2hjeydipu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ynjkgkhq.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gt2nbkelzju.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sxryk.cn/Article/details/gt2sidreqgx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gt2crnplukp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gt2clanqgia.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2tcpxjslj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuanzx.com/Article/details/gt2oitfwowz.html

[U04] Py：变量调试打印
来源：http://dali.dashuyun.cn/Article/details/gt2bbtwzcqn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gt2adoybemk.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gt2wzxpucmn.html

list(dict.fromkeys(arr))
来源：http://dali.tanke756.top/Article/details/gt2qhqwejes.html

[U06] Py：合并两个字典
来源：http://dali.yuanzhike.top/Article/details/gt2jiwhvhat.html

{**a, **b}
来源：http://dali.svipenyu.cn/Article/details/gt2itlyazzp.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2zsmslljf.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gt2aeopnrpa.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gt2yffgdpho.html

[y for x in nested for y in x]
来源：http://dali.daria6918.cn/Article/details/gt2qtgjfxin.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gt2sfdbnqgp.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gt2ptbdfwrb.html

[U10] Py：按值排序字典
来源：http://dali.aizwys.cn/Article/details/gt2lonlxyjc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jianghu66.top/Article/details/gt2wjpjgugd.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gt2ahjwsate.html

(x * 2 for x in arr)
来源：http://dali.zhoulong.xyz/Article/details/gt2qjznxdat.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gt2fbembtlt.html

Counter(arr).most_common(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fogxodlt.html

[U13] Py：固定长度队列
来源：http://dali.sysykeji.top/Article/details/gt2ncgdofjc.html

deque(maxlen=10)
来源：http://dali.birdmap.top/Article/details/gt2fogyujxb.html

[U14] Py：分组收集到列表
来源：http://dali.redwolf501.top/Article/details/gt2xuzemkxv.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gt2fnpsvtld.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gt2tjawvalk.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2ebthxyob.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gt2roittmua.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gt2kcuqgjmd.html

[U17] Py：初始化日志
来源：http://dali.dianchejie.cn/Article/details/gt2dzliwnjw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ppjwa.cn/Article/details/gt2ytgjqhtv.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gt2sdflgxgs.html

pat = re.compile(r"\d+")
来源：http://dali.zhengqikj.top/Article/details/gt2mnqjsdze.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gt2wislvaxh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gt2cohlawmt.html

[U20] Py：缓存函数结果
来源：http://dali.chenjidiqi.icu/Article/details/gt2skofvxfs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gt2slhyguys.html

[U21] Py：自定义上下文管理器
来源：http://dali.haohaochexian.top/Article/details/gt2pijhmujr.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gt2ptanokiv.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gt2zpmfjcwo.html

list(zip(*m))
来源：http://dali.sxryk.cn/Article/details/gt2ggnxkmyo.html

[U23] Py：分块读取大文件
来源：http://dali.daria6918.cn/Article/details/gt2vxcwsopc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yuxming.cn/Article/details/gt2mvkfjthu.html

[U24] Py：路径操作
来源：http://dali.0kj1m.cn/Article/details/gt2spghvvlk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2lkauxpow.html

[U25] Py：CSV 按字典读
来源：http://dali.tian-w.cn/Article/details/gt2jccymcbn.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gt2zsuomlbt.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gt2cnmwdsdf.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zycfv.cn/Article/details/gt2irmupbmd.html

[U27] Py：异步 HTTP
来源：http://dali.chenlongwang.top/Article/details/gt2ikwprtin.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.redwolf501.top/Article/details/gt2mckgjquy.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gt2lmkwkufx.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2nkgwcqcu.html

[U29] Py：属性校验
来源：http://dali.fzhhl.top/Article/details/gt2klrdybcn.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gt2agghvqby.html

[U30] Py：数据类
来源：http://dali.yj20258.top/Article/details/gt2gidwemzg.html

@dataclass(slots=True)
来源：http://dali.cqqwz.cn/Article/details/gt2zaasplfg.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gt2taeirdfj.html

python -m pytest -q
来源：http://dali.jlsjyb.cn/Article/details/gt2dlvpwecn.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2rqquzlza.html

ruff format . && ruff check --fix .
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gjihtvxf.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xlmbjdfe.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2fkqmpffq.html

[U34] Py：判断编码
来源：http://dali.dashuyun.cn/Article/details/gt2sqdfxcka.html

chardet.detect(raw)
来源：http://dali.cheryme.top/Article/details/gt2qfnzpbyj.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2tqjbksog.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.andypj.xyz/Article/details/gt2ibtlkkhh.html

[U36] Py：定时任务
来源：http://dali.yj20258.top/Article/details/gt2bhvwakjy.html

schedule.every(10).minutes.do(job)
来源：http://dali.gaohongyu789.top/Article/details/gt2ygwdoail.html

[U37] Py：读写 Excel
来源：http://dali.sysykeji.top/Article/details/gt2zfjhahyx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.meibo888.top/Article/details/gt2vleuuenm.html

[U38] Py：获取脚本所在目录
来源：http://dali.ehwqpu.com/Article/details/gt2qrcwbevx.html

Path(__file__).resolve().parent
来源：http://dali.yuxming.cn/Article/details/gt2ypzkmekr.html

[U39] Py：判断是否在交互环境
来源：http://dali.gaohongyu789.top/Article/details/gt2vxrivcbv.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gt2ehcqnhys.html

[U40] Py：打印到标准错误
来源：http://dali.fengsongda.top/Article/details/gt2gcctysoe.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gt2flexrqyc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gt2guykkrbq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.daxiang520.top/Article/details/gt2atizjtuw.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gt2ecrokpzz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yvedp.cn/Article/details/gt2quwnyskv.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gt2yqbwgmjg.html

namespace App\Http;
来源：http://dali.haohaochexian.top/Article/details/gt2ohvjxrgx.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gt2eliewjhy.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gt2ggqceibl.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhoulong.xyz/Article/details/gt2acxfssfh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqvmvfwi.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2ckzenivc.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gt2utshggnq.html

[U47] PHP：联合类型
来源：http://dali.jianghu66.top/Article/details/gt2wcklkjhm.html

int|string $id
来源：http://dali.haohaochexian.top/Article/details/gt2iswkgswe.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gt2pvgriaub.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gt2flmiijta.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gt2usgeogjx.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gt2sruotbpd.html

[U50] PHP：构造器属性提升
来源：http://dali.yj202588.top/Article/details/gt2tzbpudjl.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gt2tmygbafi.html

[U51] PHP：数组解构
来源：http://dali.sxryk.cn/Article/details/gt2vvkgeujp.html

[$a, $b] = $arr;
来源：http://dali.snrcjt.cn/Article/details/gt2jpaxvbjh.html

[U52] PHP：箭头函数
来源：http://dali.yangfankeji.com/Article/details/gt2mqpyyfhy.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gt2aokojdut.html

[U53] PHP：空合并运算符
来源：http://dali.vqdsnc.cn/Article/details/gt2vyabpaqd.html

$v = $a ?? $b ?? "default";
来源：http://dali.sysykeji.top/Article/details/gt2myvzsolm.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2ovtyqyfv.html

$obj?->method()
来源：http://dali.cqqwz.cn/Article/details/gt2ljqrkbsv.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2gtaeljaz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cashguo.top/Article/details/gt2izptnzho.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qgxokzgb.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvhybrer.html

[U57] PHP：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2onpvdflm.html

"值: {$a}"
来源：http://dali.hnqzz.top/Article/details/gt2vgxygcny.html

[U58] PHP：数组三件套
来源：http://dali.vqdsnc.cn/Article/details/gt2zjflclqo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gt2blmgvaho.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gt2jgvydvah.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tian-w.cn/Article/details/gt2tibziphf.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lrphyvko.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gogol.net.cn/Article/details/gt2krtmhstm.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hbuxwzff.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gt2xkgbscep.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gt2vtqeofoe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gt2rnimyjrt.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gt2tbctwlca.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangdashe.top/Article/details/gt2eegyewrr.html

[U64] PHP：目录遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2rkzwagdt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ppjwa.cn/Article/details/gt2ppgrwroc.html

[U65] PHP：会话
来源：http://dali.gogol.net.cn/Article/details/gt2yddjlkkz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cashguo.top/Article/details/gt2cerwuvyh.html

[U66] PHP：设置 Cookie
来源：http://dali.chenzaomai.com/Article/details/gt2teaourdt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pnvlvsgo.html

[U67] PHP：处理文件上传
来源：http://dali.316326.xyz/Article/details/gt2jxdtmxsg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2ttcbydpx.html

[U68] PHP：PDO 连接
来源：http://dali.hnxiangtu.top/Article/details/gt2rhfmmsos.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shangyingyoupin.top/Article/details/gt2scjqtptp.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gt2fffjizhn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gt2zfojkcdf.html

[U70] PHP：PDO 事务
来源：http://dali.jqgufenzy.top/Article/details/gt2lzqifhjk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj202588.top/Article/details/gt2gscarule.html

[U71] PHP：抛出异常
来源：http://dali.hnxiangtu.top/Article/details/gt2rwcbuhxb.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2ejzobfcg.html

[U72] PHP：写错误日志
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksmcpwwf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.dianchejie.cn/Article/details/gt2hodwmbmv.html

[U73] PHP：读取 ini 配置
来源：http://dali.svipenyu.cn/Article/details/gt2fqpxgtlx.html

parse_ini_file("config.ini", true)
来源：http://dali.zhongyouzk.top/Article/details/gt2vujlcybb.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2xwwtxgzi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gt2gfzyplzh.html

[U75] PHP：依赖注入
来源：http://dali.gotoacloud.top/Article/details/gt2ntjdypms.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gt2ksebqjti.html

[U76] PHP：简单路由
来源：http://dali.guannengcc.top/Article/details/gt2abegalcs.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gt2nhlgfzyd.html

[U77] PHP：模板渲染
来源：http://dali.guowangkeji.top/Article/details/gt2wkngoxly.html

composer require twig/twig
来源：http://dali.zhiwuduotai.top/Article/details/gt2myodlazk.html

[U78] PHP：单元测试
来源：http://dali.tian-w.cn/Article/details/gt2lzkkwykj.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gt2vjxullba.html


<!-- 参考信息 -->