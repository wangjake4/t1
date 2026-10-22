代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2viaprdvu.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gt2imwlmzam.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fgytcmrq.html

[S52] C++：const 与 noexcept
来源：http://dali.yueranfly.top/Article/details/gt2vxlxetqb.html

int size() const noexcept { return n_; }
来源：http://dali.snrcjt.cn/Article/details/gt2ssalerun.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gt2expzdhza.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ghmtczec.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2uuphesvh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvchfcut.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrpyfokf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2fvkrdhxc.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2btzhgfyp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jldigpoy.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2qtnqlnno.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gt2lniopuou.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gt2dvukiija.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2xlogddvf.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2rbhvjcfd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gt2zhkjgela.html

[S60] C++：遍历并删除元素
来源：http://dali.zhixingplan.top/Article/details/gt2mecrurew.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2mcadqvrb.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2smvpkvys.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gt2grlzmabo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pajzeeww.html

[T01] Kotlin：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2fwgvczee.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gt2sllwfien.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gt2yovmzyvh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yvedp.cn/Article/details/gt2gemreysg.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gt2vlpqajqm.html

"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rwqqolwl.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2rzhbyfer.html

val n: String? = null;  n?.length
来源：http://dali.wangdashe.top/Article/details/gt2kwevolvj.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2yiwkwvak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2mmqiqvhs.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2vesoncig.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2dpksyihj.html

[T07] Kotlin：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gt2rskmiutw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gt2wcyqcsub.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2xbrdokje.html

data class User(val name: String, val age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2zyexegwb.html

[T09] Kotlin：扩展函数
来源：http://dali.fengsongda.top/Article/details/gt2bziaeqhq.html

fun String.exclaim() = this + "!"
来源：http://dali.xuanzx.com/Article/details/gt2tiwcckew.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2ccbtpevn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hammf.cn/Article/details/gt2fewcewky.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2geinmxub.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gt2aqygbeah.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2sejjgyaf.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2xprsyvyw.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gt2jljikjjy.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otksvccj.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2tzdyibuv.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gt2vmdwabvl.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2yzkdilkd.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gt2qjrozkaq.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2izfvgetd.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2fdbmfnpm.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksgeujyv.html

var a = 1;  let b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gt2cpkrrlbi.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghtaxowp.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hksjqevd.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tghzamdb.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gt2xxnwtccp.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2ufcqqywt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gt2fyrxafwr.html

[T21] Swift：遍历
来源：http://dali.9152youxi.cn/Article/details/gt2mlkopnnc.html

for x in a { print(x) }
来源：http://dali.yonumen.top/Article/details/gt2anuwxiwe.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gt2potzpzrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.316326.xyz/Article/details/gt2hqglrcar.html

[T23] Swift：函数
来源：http://dali.redwolf501.top/Article/details/gt2cggoyygk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.c1oappe.top/Article/details/gt2toitsuzm.html

[T24] Swift：闭包
来源：http://dali.cashguo.top/Article/details/gt2yngxobwp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gt2epjpzitv.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gt2ejaenzlr.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2nazysxlj.html

[T26] Swift：类与重写
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biflquvv.html

class A: Base { override func f() {} }
来源：http://dali.hammf.cn/Article/details/gt2egtwmrye.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gt2enshcska.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gt2hndrnfpy.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gt2dmdgyzre.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gt2hwyusrya.html

[T29] Swift：guard 提前返回
来源：http://dali.redwolf501.top/Article/details/gt2ovtuxkdb.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gt2vupmsntm.html

[T30] Swift：协议
来源：http://dali.zhengqikj.top/Article/details/gt2czcalnta.html

protocol Shape { func area() -> Double }
来源：http://dali.mhx1999.top/Article/details/gt2bpwgwguq.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gt2goszdesb.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2ouekzpdq.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2psyrnaxq.html

local a = 1
来源：http://dali.chenlongwang.top/Article/details/gt2rjrfcply.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gt2reegswkr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigufen.top/Article/details/gt2wcxpebpa.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2ndzloncq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cqqwz.cn/Article/details/gt2qsfouvoq.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gt2fxuoetyw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2wpikvbdp.html

[T36] Lua：函数
来源：http://dali.yongpay.top/Article/details/gt2yjwqbwgo.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gt2pvxojhjx.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2lthdymvi.html

"a" .. "b"
来源：http://dali.fzhhl.top/Article/details/gt2ezbbevyy.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gt2iviccahq.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2vbviedlp.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gt2ilxvnzzu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2wdjaixcg.html

[T40] Lua：元表
来源：http://dali.smart0.xyz/Article/details/gt2gukpjzkd.html

setmetatable({}, { __index = base })
来源：http://dali.zycfv.cn/Article/details/gt2ovywfyck.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2mhftsike.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2lcctjsqy.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2mvffnjnf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2mnznwzmq.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2fhwoxhri.html

"值: $a"
来源：http://dali.hysaishi.cn/Article/details/gt2mrulyrxo.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2zrobgqma.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2xkozbulb.html

[T45] Perl：数组遍历
来源：http://dali.hfpthk.cn/Article/details/gt2utclufla.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gt2foarxctw.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pnnwefvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gt2shffbasy.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gt2xlkqhfrn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gt2rsldjofx.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gt2aajtocpe.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gt2jrkfsmsy.html

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gt2jsqayxwq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gt2kjmuwjqe.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2yhkoiiiz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.fengsongda.top/Article/details/gt2tneaakru.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dktzqxkb.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2gupkjgmu.html

println("Hello")
来源：http://dali.sweek.top/Article/details/gt2qksssaqc.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gt2allovaqi.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gt2efbdeuwj.html

[T53] Scala：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gt2idyhvimf.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vfdqpmjo.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2vkuowfbq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sysykeji.top/Article/details/gt2bwgdhiva.html

[T55] Scala：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gt2jhawwcto.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gt2ilhjhwbh.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gt2ewcuvcik.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gt2pydijetp.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mmamuexy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ppjwa.cn/Article/details/gt2oxoetxmd.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gt2zyswpegz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2otwhvrva.html

[T59] Scala：循环
来源：http://dali.chenzaomai.com/Article/details/gt2cyvkngwy.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2hugltzlb.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2czclonmd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jxvqefeh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bfvynbth.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.0kj1m.cn/Article/details/gt2bazjvbyx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2pqzxcizr.html

[U01] Py：创建虚拟环境
来源：http://dali.daria6918.cn/Article/details/gt2xcvcdcpu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yuanzhike.top/Article/details/gt2mobxhpzg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gt2pnagvsap.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gt2cxdwltdz.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gt2smmtzlcp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhijiandao.cn/Article/details/gt2plkxxhvd.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjyevffv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.aibaodan.cn/Article/details/gt2ricdzcun.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gt2tlhpjoix.html

list(dict.fromkeys(arr))
来源：http://dali.ehwqpu.com/Article/details/gt2nrnkuhfj.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gt2uvkislee.html

{**a, **b}
来源：http://dali.zhiwuduotai.top/Article/details/gt2mremhzbi.html

[U07] Py：反转字典键值
来源：http://dali.xylfe.cn/Article/details/gt2kpgwsinj.html

{v: k for k, v in d.items()}
来源：http://dali.hnxiangtu.top/Article/details/gt2wajqzoyn.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2swouexsb.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehlfoobk.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkhqqndq.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2uicuuemp.html

[U10] Py：按值排序字典
来源：http://dali.guowangkeji.top/Article/details/gt2inrllcxs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gt2vlifvxbp.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2ohhbfyoc.html

(x * 2 for x in arr)
来源：http://dali.yj20258888.top/Article/details/gt2ibvzlewn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guannengcc.top/Article/details/gt2marfumel.html

Counter(arr).most_common(3)
来源：http://dali.316326.xyz/Article/details/gt2pyehpctd.html

[U13] Py：固定长度队列
来源：http://dali.zdqjudy.top/Article/details/gt2uhywtsjz.html

deque(maxlen=10)
来源：http://dali.yvedp.cn/Article/details/gt2qwdiclmz.html

[U14] Py：分组收集到列表
来源：http://dali.hfpthk.cn/Article/details/gt2uavjbvyf.html

defaultdict(list)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bmbfadcw.html

[U15] Py：高精度计时
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2shrxezuw.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gt2qzfkpmov.html

[U16] Py：命令行参数解析
来源：http://dali.zhixingplan.top/Article/details/gt2hdzvdlou.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangshuangyany.cn/Article/details/gt2iqhswnrp.html

[U17] Py：初始化日志
来源：http://dali.zycfv.cn/Article/details/gt2lhqjscip.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gt2cdqvckxf.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2skuthtgp.html

pat = re.compile(r"\d+")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffrrybeu.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gt2nfltguho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gt2sjozfwmq.html

[U20] Py：缓存函数结果
来源：http://dali.meibo888.top/Article/details/gt2gvtxbfyv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gt2fwygwyvj.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gt2mkldzxcl.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gt2efkuzjnk.html

[U22] Py：矩阵转置
来源：http://dali.redwolf501.top/Article/details/gt2aqcjeqmj.html

list(zip(*m))
来源：http://dali.birdmap.top/Article/details/gt2iainokge.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gt2xcjajtrh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yanxiufei.cn/Article/details/gt2ldscekuj.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gt2crchlqnp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.kuanghao11.cn/Article/details/gt2spbjnkwx.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gt2xdpyofiw.html

csv.DictReader(f)
来源：http://dali.snrcjt.cn/Article/details/gt2kibngydd.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gt2ivaztqkd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.fengsongda.top/Article/details/gt2lexlxwdv.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gt2ltaiylww.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cdnleiting.top/Article/details/gt2yhcigxrj.html

[U28] Py：类型别名
来源：http://dali.yueranfly.top/Article/details/gt2ahujwgiv.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gt2xwgtcdgw.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2plfveomt.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gt2kxhrjbfr.html

[U30] Py：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gt2zwnqigwm.html

@dataclass(slots=True)
来源：http://dali.chenlongwang.top/Article/details/gt2wqrbhtah.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gt2uvkzkkuu.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gt2uvwiovek.html

[U32] Py：代码格式化
来源：http://dali.ybcxt.top/Article/details/gt2emilvbmf.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gt2hkgqgwnj.html

[U33] Py：打包发布
来源：http://dali.cdnleiting.top/Article/details/gt2hqpuyauu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gt2hplblxid.html

[U34] Py：判断编码
来源：http://dali.snrcjt.cn/Article/details/gt2lffhwmgl.html

chardet.detect(raw)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zigudgdm.html

[U35] Py：发送邮件
来源：http://dali.daria6918.cn/Article/details/gt2orudzvmp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gt2codtkgtl.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2ynfffnlt.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhixingplan.top/Article/details/gt2znpkiqkd.html

[U37] Py：读写 Excel
来源：http://dali.cashguo.top/Article/details/gt2irlpzijj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2nowfeavj.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gt2euecpltq.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gt2ahgiwaye.html

[U39] Py：判断是否在交互环境
来源：http://dali.yonumen.top/Article/details/gt2huzyjorn.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gt2lkyispxt.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gt2fcrjgvih.html

print("err", file=sys.stderr)
来源：http://dali.tian-w.cn/Article/details/gt2cypjfgva.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.fzhhl.top/Article/details/gt2sllqcaek.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dashuyun.cn/Article/details/gt2vcxanscr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yj202588.top/Article/details/gt2sshikucb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.cucudq.cn/Article/details/gt2ebexxvfl.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2zqyheqgz.html

namespace App\Http;
来源：http://dali.gzhubu.top/Article/details/gt2faehgipq.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gt2nagipmdu.html

declare(strict_types=1);
来源：http://dali.dashuyun.cn/Article/details/gt2muvlqqme.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gt2znwybolz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2rbewouvf.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gt2nuiczxvn.html

?string $name = null
来源：http://dali.xuanzx.com/Article/details/gt2pkqjnhzp.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gt2tghcbsjc.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gt2fbvaindc.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2gutirepv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj202588.top/Article/details/gt2khcxoxfn.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gt2iwwtbbvg.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nmbwemtw.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gt2wwlcbaaz.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gt2fppoyzrj.html

[U51] PHP：数组解构
来源：http://dali.zhengqikj.top/Article/details/gt2xljvepfu.html

[$a, $b] = $arr;
来源：http://dali.yj202588.top/Article/details/gt2bbjjexes.html

[U52] PHP：箭头函数
来源：http://dali.havefunace.top/Article/details/gt2lnzkdkxl.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2ricmygor.html

[U53] PHP：空合并运算符
来源：http://dali.ydzc1.top/Article/details/gt2ilrkspmw.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gt2vpjnuulq.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2phxkfumh.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjrkrmsj.html

[U55] PHP：match 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2uqxvbsmu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndhuwrlv.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gt2sidfjbcy.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2nkjlobbq.html

[U57] PHP：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2ebeqgjrn.html

"值: {$a}"
来源：http://dali.ydzc1.top/Article/details/gt2gqtyxito.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gt2yscyfudh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ptjajjjm.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gt2pcgvlnzj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhoulong.xyz/Article/details/gt2ckmqofak.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gt2kpwjhfek.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gt2hbcubicy.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gt2bfhwsvyu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jiagoushi.top/Article/details/gt2mwhbhzsk.html

[U62] PHP：日期对象
来源：http://dali.svipenyu.cn/Article/details/gt2pyixorem.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ppjwa.cn/Article/details/gt2otbwbisq.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gt2lpuilvbu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jyoumei.cn/Article/details/gt2pbocnssr.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2rypnxyli.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yueranfly.top/Article/details/gt2pgjoties.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2aanunrxx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xinyue.icu/Article/details/gt2fudmghjy.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gt2hgohafza.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.iojbl.cn/Article/details/gt2qqtwwsde.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gt2gscxdwbv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gt2idkcirdl.html

[U68] PHP：PDO 连接
来源：http://dali.shuidangran.top/Article/details/gt2tswgoyje.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shuidangran.top/Article/details/gt2xhkfuhcg.html

[U69] PHP：PDO 预处理
来源：http://dali.yuxming.cn/Article/details/gt2ymwvntls.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yuanzhike.top/Article/details/gt2ebvjatah.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gt2jlfvmtop.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gqyqlndm.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2jmltohrl.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gt2cakxojfm.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmiforwp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gt2rftpamwf.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gt2iovqsfjb.html

parse_ini_file("config.ini", true)
来源：http://dali.meibo888.top/Article/details/gt2rqglqctn.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2gthwygzm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqmnadxf.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gt2onwenuqo.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gt2fjjosenj.html

[U76] PHP：简单路由
来源：http://dali.ydzc1.top/Article/details/gt2fmlsuwoq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.wangdashe.top/Article/details/gt2nksyozdh.html


<!-- 参考信息 -->