代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.redwolf501.top/Article/details/gt2bsjtgksy.html

[S55] C++：结构化绑定
来源：http://dali.ppjwa.cn/Article/details/gt2zlqxdaoh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gt2ygcfkaet.html

[S56] C++：optional
来源：http://dali.yvedp.cn/Article/details/gt2jfxybsub.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2xzkdzrqn.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2qnkrrhbt.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2dhmalxny.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2twfjckwj.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cmbuewqm.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dngglpad.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258888.top/Article/details/gt2oyrftuti.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gt2uxhsfbtc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gt2gfdjbbta.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2nepsozjl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gt2fyxlxaix.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tpotoqxm.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2xihtclsh.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2browekyb.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gt2jpqqhwif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2smkhyxpm.html

[T03] Kotlin：字符串模板
来源：http://dali.hfpthk.cn/Article/details/gt2aabvdijm.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gt2brsnuxdr.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gt2qiicnrbg.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gt2hzqpkegp.html

[T05] Kotlin：when 表达式
来源：http://dali.xinyue.icu/Article/details/gt2ywoifinb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gt2bgwgbvum.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2tvttenwu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gt2ggfegham.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2ajnbcilt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gt2oipgswgs.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gt2jgvasorj.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gt2iqtcrudk.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gt2tgqifydr.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2ursrchqo.html

[T10] Kotlin：默认参数
来源：http://dali.dianchejie.cn/Article/details/gt2fscaizgm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2klymvjoy.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gt2dsaixolu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gt2enchmwxe.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gt2sbplqjup.html

val (a, b) = Pair(1, 2)
来源：http://dali.ehwqpu.com/Article/details/gt2tixokirg.html

[T13] Kotlin：只读 Map
来源：http://dali.cqqwz.cn/Article/details/gt2kmegljym.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2myfkdipa.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mwjyxvdx.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gt2zbapadkp.html

[T15] Kotlin：接口
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lcthlsyq.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2bskfpgov.html

[T16] Swift：Hello World
来源：http://dali.haohaochexian.top/Article/details/gt2upeiepdf.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2dhjuazol.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uzogemxd.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2zvgdmkwh.html

[T18] Swift：字符串插值
来源：http://dali.ivvv.top/Article/details/gt2xakggciu.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gt2klaixwbg.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2bxwsmhsb.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gt2jqbsgubk.html

[T20] Swift：数组操作
来源：http://dali.fzhhl.top/Article/details/gt2qubwugin.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gt2asbogeuv.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gt2ovqzayhc.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gt2hiyvakla.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gt2lgundeuz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shuidangran.top/Article/details/gt2fhezzddp.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gt2fdvenjtz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gt2hkykkctk.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wwieeuiy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kturgmmi.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gt2fnkgivmv.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2reaczreq.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gt2vvdwadru.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2coulxedo.html

[T27] Swift：错误处理
来源：http://dali.gogol.net.cn/Article/details/gt2mebokbhr.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gt2owxduetm.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwkajqoz.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2minknisc.html

[T29] Swift：guard 提前返回
来源：http://dali.haohaochexian.top/Article/details/gt2wcifxtyn.html

guard let x = opt else { return }
来源：http://dali.fengsongda.top/Article/details/gt2bvhoqvon.html

[T30] Swift：协议
来源：http://dali.bjfxy.top/Article/details/gt2xrtduwrm.html

protocol Shape { func area() -> Double }
来源：http://dali.jyoumei.cn/Article/details/gt2fmhvobuv.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gt2srbhohmu.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2itltvvpv.html

[T32] Lua：局部变量
来源：http://dali.tianlin.xyz/Article/details/gt2vgbmchvn.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gt2btknbkse.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2rifthoai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2arvmihvo.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gt2ebvsgzsl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gt2qtxedzrd.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gt2mtlipwnp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2erifpmwr.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gt2offcimmd.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gt2zqtyltjg.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2zbizsbkz.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gt2jplxrkpx.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2ladjvdij.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2ikyfyvxc.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2exayzfsg.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gt2xtwioume.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2omrgsqxl.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gt2kwvupndc.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2hiuhrfna.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gt2xrcpzqpz.html

[T42] Perl：变量类型
来源：http://dali.sysykeji.top/Article/details/gt2hgkfjzlv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2qvhgture.html

[T43] Perl：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2fqxylwhx.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gt2zgldrgbs.html

[T44] Perl：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2hcwsnuby.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlkkmhnj.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gt2hrmvbjee.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gt2lfglgrzk.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gt2lipfjouk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gt2jtwtqmlb.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gt2uxelaxqe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gt2wpiigwil.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2yrbbehqz.html

$s =~ s/old/new/g;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpaeffla.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gt2ujfndpzb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2qsgjzntl.html

[T50] Perl：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gt2akheowgq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2txwktmuz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gt2kbnxbikn.html

[T51] Scala：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gt2krufewtw.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gt2rxbovyyc.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gt2fgqfdekw.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gt2skpzzdkj.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2gkvywzmu.html

s"值: $b"
来源：http://dali.zycfv.cn/Article/details/gt2bsbvcaam.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2fikgzbvh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gt2ddrkerwb.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2cczifoah.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shuidangran.top/Article/details/gt2kbsnftzm.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2xbfvgvue.html

case class User(name: String, age: Int)
来源：http://dali.yonumen.top/Article/details/gt2qcihblza.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2blvabzzs.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2selfzzqq.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gt2smmottnx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhixingplan.top/Article/details/gt2jctijpag.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gt2xosgmjpe.html

for (i <- 1 to 10) println(i)
来源：http://dali.yonumen.top/Article/details/gt2jklccfwj.html

[T60] Scala：折叠
来源：http://dali.vqdsnc.cn/Article/details/gt2mfizirjh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yctpuecx.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2qasurkyb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gt2papxrrmf.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2axyysnzi.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gt2xpizkxei.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2pfsrvgor.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnxiangtu.top/Article/details/gt2gmwujmmu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tian-w.cn/Article/details/gt2acukzesl.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gt2imefazpv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2ytbxvyzk.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gt2yggtqyco.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.daria6918.cn/Article/details/gt2xvjhordj.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gt2eixgyigj.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gt2ckusoigv.html

[U06] Py：合并两个字典
来源：http://dali.jqgfzy.top/Article/details/gt2wespqwup.html

{**a, **b}
来源：http://dali.nanxuanxn.top/Article/details/gt2tiwtbnti.html

[U07] Py：反转字典键值
来源：http://dali.guowangkeji.top/Article/details/gt2blhdlctt.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gt2ermwnqbb.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gt2wzentuxg.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gt2xxymgeav.html

[U09] Py：字典取最大值的键
来源：http://dali.tianlin.xyz/Article/details/gt2wzlqahje.html

max(d, key=d.get)
来源：http://dali.yj202588.top/Article/details/gt2hvumvaoy.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gt2qicwnrko.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gt2icmiuiiw.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gt2hpsphzhh.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gt2nutcnyzl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.guowangkeji.top/Article/details/gt2mnhqwgqx.html

Counter(arr).most_common(3)
来源：http://dali.jinqigfzy.top/Article/details/gt2obsepikf.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gt2ydnzxbyj.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gt2jusluejk.html

[U14] Py：分组收集到列表
来源：http://dali.guowangkeji.top/Article/details/gt2zkozhddn.html

defaultdict(list)
来源：http://dali.yonumen.top/Article/details/gt2dknxhpvo.html

[U15] Py：高精度计时
来源：http://dali.sufxvd.cn/Article/details/gt2cevlemoo.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gt2mwwbjfsz.html

[U16] Py：命令行参数解析
来源：http://dali.mhx1999.top/Article/details/gt2kjdsqzad.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2vwlekfcv.html

[U17] Py：初始化日志
来源：http://dali.chenzaomai.com/Article/details/gt2zjimqchw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ehwqpu.com/Article/details/gt2robxqfya.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gt2uqoyctuo.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gt2jqntojvx.html

[U19] Py：正则替换带回调
来源：http://dali.yvedp.cn/Article/details/gt2axbyzjuy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.iojbl.cn/Article/details/gt2hzeambul.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gt2xidzwwbr.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gt2oeaxazpg.html

[U21] Py：自定义上下文管理器
来源：http://dali.birdmap.top/Article/details/gt2gaiqmyxg.html

@contextlib.contextmanager
来源：http://dali.sysykeji.top/Article/details/gt2izfqcwmv.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gt2wvbfcuhm.html

list(zip(*m))
来源：http://dali.jyoumei.cn/Article/details/gt2whzppeqy.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2actpureu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gt2rqssviww.html

[U24] Py：路径操作
来源：http://dali.hongshengwenyu.top/Article/details/gt2gppxnfry.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.c1oappe.top/Article/details/gt2aqfabiaa.html

[U25] Py：CSV 按字典读
来源：http://dali.daria6918.cn/Article/details/gt2oijlegim.html

csv.DictReader(f)
来源：http://dali.mhx1999.top/Article/details/gt2nqctcgvn.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gt2rjebdzvm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ivvv.top/Article/details/gt2elxocabj.html

[U27] Py：异步 HTTP
来源：http://dali.birdmap.top/Article/details/gt2vukzietn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tanke756.top/Article/details/gt2pfynhtrb.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gt2uznhttxt.html

UserId = int
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itjfjjwz.html

[U29] Py：属性校验
来源：http://dali.aizwys.cn/Article/details/gt2edtujicb.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gt2inwyxvxj.html

[U30] Py：数据类
来源：http://dali.cucudq.cn/Article/details/gt2vcmwevtb.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gt2acctfrbm.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gt2eviobpii.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gt2euqkepxs.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gt2zsitgsvt.html

ruff format . && ruff check --fix .
来源：http://dali.ybcxt.top/Article/details/gt2dbbtvtcy.html

[U33] Py：打包发布
来源：http://dali.cheryme.top/Article/details/gt2ufssecdz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2rbkwowik.html

[U34] Py：判断编码
来源：http://dali.wangdashe.top/Article/details/gt2iqpixsqs.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2unedovnj.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gt2btlrttph.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.quarkkingdee.top/Article/details/gt2ualygefe.html

[U36] Py：定时任务
来源：http://dali.nwbrower.top/Article/details/gt2bljnpfls.html

schedule.every(10).minutes.do(job)
来源：http://dali.ydzc1.top/Article/details/gt2bghmifto.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gt2eusjsobm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gt2atfpgmah.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gt2srrwvkxb.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gt2jnadbnzt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2edtusbfd.html

sys.stdout.isatty()
来源：http://dali.hammf.cn/Article/details/gt2vwkfwsgh.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pstsjcdw.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gt2srayndds.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.9152youxi.cn/Article/details/gt2dhfcbvnk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhijiandao.cn/Article/details/gt2lqixmiym.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuanzx.com/Article/details/gt2yxhbhqkt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2xohsuspk.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gt2vajxivpp.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gt2ukllwgal.html

[U44] PHP：开启严格类型
来源：http://dali.hysaishi.cn/Article/details/gt2dseozuea.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2twguueoc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.aizwys.cn/Article/details/gt2qsgmoqww.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gt2axxyqkvj.html

[U46] PHP：可空类型
来源：http://dali.shuidangran.top/Article/details/gt2eirthugl.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gt2fpdtczvy.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gt2lmytmfqs.html

int|string $id
来源：http://dali.zhoulong.xyz/Article/details/gt2laecnnxh.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gt2wenovbsp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jpngdecb.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gt2igvkufjn.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gt2vmkzvqpy.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gt2euoxsvlo.html

public function __construct(private int $id) {}
来源：http://dali.tian-w.cn/Article/details/gt2ydoayioo.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gt2ligbsvjj.html

[$a, $b] = $arr;
来源：http://dali.daria6918.cn/Article/details/gt2igrimbzq.html

[U52] PHP：箭头函数
来源：http://dali.andypj.xyz/Article/details/gt2lhwoncwr.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gt2zxtpddpe.html

[U53] PHP：空合并运算符
来源：http://dali.nanxuanxn.top/Article/details/gt2vezohdfl.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gt2lnbrgfwv.html

[U54] PHP：空安全调用
来源：http://dali.yvedp.cn/Article/details/gt2hrqtgavo.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gt2pmfxjwbo.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2suqnvpfh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gt2anbkkrwq.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gt2zigcwwrc.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2xwwlibfk.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gt2zjbfyuxj.html

"值: {$a}"
来源：http://dali.cqqwz.cn/Article/details/gt2uknkcyqn.html

[U58] PHP：数组三件套
来源：http://dali.xuanzx.com/Article/details/gt2nenmuoqt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.vqdsnc.cn/Article/details/gt2edzfjvpx.html

[U59] PHP：自定义排序
来源：http://dali.xylfe.cn/Article/details/gt2rhujduzn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2nurjqegp.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gt2enhmqlwo.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ppjwa.cn/Article/details/gt2mpuvogsy.html

[U61] PHP：正则
来源：http://dali.chenjidiqi.icu/Article/details/gt2meflydoc.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gt2vzuohfkt.html

[U62] PHP：日期对象
来源：http://dali.xziqi.cn/Article/details/gt2zuobsvfe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gt2zybvbdys.html

[U63] PHP：文件读写
来源：http://dali.gaohongyu789.top/Article/details/gt2nkvacrpq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gt2cjbujqhd.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gt2ienkhkre.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gt2fkzirslq.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gt2sqorrxzg.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2lgqchatq.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gt2trhuugvf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gt2evlobnmx.html

[U67] PHP：处理文件上传
来源：http://dali.jianghu66.top/Article/details/gt2grecokww.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xziqi.cn/Article/details/gt2evpvgjfb.html

[U68] PHP：PDO 连接
来源：http://dali.daria6918.cn/Article/details/gt2wtgfrqhe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2pmosmmtb.html

[U69] PHP：PDO 预处理
来源：http://dali.9152youxi.cn/Article/details/gt2gdkjcrkk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2kquzwbkk.html

[U70] PHP：PDO 事务
来源：http://dali.zycfv.cn/Article/details/gt2reydusrx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xziqi.cn/Article/details/gt2slyiwxmy.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2nkkcmzmm.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gt2eikhysdq.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gt2dgwzapyp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ehwqpu.com/Article/details/gt2wjwqhrcj.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigfzy.top/Article/details/gt2gklkewdr.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gt2emkwvnla.html

[U74] PHP：读取环境变量
来源：http://dali.hywenlv.cn/Article/details/gt2ffexmxdx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gt2twbejxae.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gt2dgguqrjq.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gt2favctkae.html

[U76] PHP：简单路由
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2woxjmxlu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gt2jcuckaxc.html

[U77] PHP：模板渲染
来源：http://dali.yj202588.top/Article/details/gt2wdsxczpy.html

composer require twig/twig
来源：http://dali.hysaishi.cn/Article/details/gt2zudusuyy.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gt2nlumfokm.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gt2btlnlivd.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gt2zukvodeg.html

composer require --dev phpstan/phpstan
来源：http://dali.yongpay.top/Article/details/gt2wwcmdguj.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gt2djtalqmf.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gotoacloud.top/Article/details/gt2yhlmkkno.html


<!-- 参考信息 -->