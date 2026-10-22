代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gt2nvkyrnxw.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2htbicoyi.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gt2uiaobqdu.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2yeyyouqk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhxfbckd.html

[S55] C++：结构化绑定
来源：http://dali.iojbl.cn/Article/details/gt2rztxjiew.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2bddwcvwr.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2hsqfvvlg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2dnygquow.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gt2ghkqmltw.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gt2otaiokce.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gt2tajrhond.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gt2xighajbf.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2phsxyljb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2rckmmref.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gt2modmvtpz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gt2qsbanpeb.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2uyzeeads.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gt2oectdyni.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2ymfqxrku.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2wsagqged.html

println("Hello")
来源：http://dali.cheryme.top/Article/details/gt2tmuahder.html

[T02] Kotlin：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2oazxnspw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.kuanghao11.cn/Article/details/gt2coiuqwpn.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gt2etjnzasd.html

"值: $b"
来源：http://dali.xylfe.cn/Article/details/gt2erphgfvt.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2cbiiydyj.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gt2cvdbhlfg.html

[T05] Kotlin：when 表达式
来源：http://dali.hnqzz.top/Article/details/gt2gyjaaydo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gt2xhbfglmu.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gt2zqldembl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gt2gaeitwlp.html

[T07] Kotlin：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2ukyaalpq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2eqobyhok.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gt2bekworfc.html

data class User(val name: String, val age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2uyxhmlvx.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gt2xnkikuah.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gt2idoprprl.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2bxsqxsgf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jqgufenzy.top/Article/details/gt2ylwwferr.html

[T11] Kotlin：协程
来源：http://dali.shuidangran.top/Article/details/gt2jnhdetea.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gt2gupmnubg.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gt2utxgostj.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwhkmnaf.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2xrbkrums.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gt2icfuzqwt.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2wwysqjoi.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2rlyiufai.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2rqgzxwpe.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gt2fazzzxip.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2icbcydgu.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2kwytpmwr.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gt2dmmanbbi.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gt2orbyhnun.html

[T18] Swift：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2rceikemp.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2zcrnjzkq.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gt2ffeicntp.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gt2ofithvys.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2vubpicrv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2fcuitame.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gt2tkjumehz.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gt2tvvzqnoq.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gt2aqaqetzd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2eghpzody.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gt2gklltcdf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gt2kdricrku.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gt2fcyzkmgr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gt2rqtcviix.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gt2wnwartua.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gt2cjghxcaq.html

[T26] Swift：类与重写
来源：http://dali.cucudq.cn/Article/details/gt2scqjxajo.html

class A: Base { override func f() {} }
来源：http://dali.tanke756.top/Article/details/gt2lhpvwmqv.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gt2mqctyfti.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2qlflywns.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gt2ekbozwft.html

enum Color { case red, green }
来源：http://dali.snrcjt.cn/Article/details/gt2eidzfjcm.html

[T29] Swift：guard 提前返回
来源：http://dali.hfpthk.cn/Article/details/gt2mxibxqca.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2hjowhgzv.html

[T30] Swift：协议
来源：http://dali.redwolf501.top/Article/details/gt2wananxay.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gt2aogemznm.html

[T31] Lua：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2hxadacmv.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2vcvditkk.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gt2zorqfgvi.html

local a = 1
来源：http://dali.tanke756.top/Article/details/gt2wfvttosh.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2whcgptks.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.vqdsnc.cn/Article/details/gt2hrbovgpp.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2wbucttso.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xylfe.cn/Article/details/gt2udifiagj.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gt2hiyegqgy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2xhylrjjo.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gt2wcnsuqmm.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gt2qtsaggbz.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gt2zocgcyki.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gt2vuqxcpiz.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2leuvoekz.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gt2arzakbcr.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2eximbrxr.html

string.find(s, "%d+")
来源：http://dali.meibo888.top/Article/details/gt2vbqnnzic.html

[T40] Lua：元表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kmowlwqx.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gt2canojlbl.html

[T41] Perl：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2kfayscke.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gt2jfwpoybz.html

[T42] Perl：变量类型
来源：http://dali.mhx1999.top/Article/details/gt2utbyvgov.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gt2sumvfeyt.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2cmtxkkuy.html

"值: $a"
来源：http://dali.andypj.xyz/Article/details/gt2igweedaz.html

[T44] Perl：条件
来源：http://dali.fengsongda.top/Article/details/gt2zhayhidj.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dgihecxo.html

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gt2bqngxpkg.html

for my $x (@arr) { print $x; }
来源：http://dali.wangdashe.top/Article/details/gt2cilmjxde.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gt2oxxnkwvb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gt2sxauopib.html

[T47] Perl：正则捕获
来源：http://dali.c1oappe.top/Article/details/gt2kxfxwerf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gt2olyvfmgv.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gt2zsxjxylc.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gt2lnrwdyfv.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2krvzbgxr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gt2aretxlxh.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2tqpgcrpz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gt2cuizggoi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gt2eiezahmy.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2trtwzlwe.html

println("Hello")
来源：http://dali.meibo888.top/Article/details/gt2gyeuyedm.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gt2wdserycb.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gt2mmrzmtil.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2aenztafu.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2qwbbleoq.html

[T54] Scala：集合映射
来源：http://dali.ppjwa.cn/Article/details/gt2vgrpcgkf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gt2odboqsiy.html

[T55] Scala：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gt2xkdjigbm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oztnnwsj.html

[T56] Scala：样例类
来源：http://dali.nwbrower.top/Article/details/gt2mnwfcvgw.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ljnyksjf.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2okjdnlux.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gt2yogorqoy.html

[T58] Scala：函数定义
来源：http://dali.ybcxt.top/Article/details/gt2rqtqjeeg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gt2wmtijyxd.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gt2bpunvgzi.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2ctrtukau.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gt2pdtpscsh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xuanzx.com/Article/details/gt2xubfouus.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2cwuqecku.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gt2hteddtlx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2chpyzkvj.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gt2fgwbsfsg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eposavgw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cdnleiting.top/Article/details/gt2gtknuklg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.smart0.xyz/Article/details/gt2mqorzrhx.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2ftmbdacp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gt2ncxfkjue.html

[U04] Py：变量调试打印
来源：http://dali.wangdashe.top/Article/details/gt2gtmmseol.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gt2reuzttpo.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gt2ysrdpatg.html

list(dict.fromkeys(arr))
来源：http://dali.tianlin.xyz/Article/details/gt2iyhgmedi.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2fzmilogy.html

{**a, **b}
来源：http://dali.fzhhl.top/Article/details/gt2peocakqg.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gt2wxixkjfv.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gt2uobcfxaa.html

[U08] Py：展平二维列表
来源：http://dali.shzxlz.cn/Article/details/gt2rbzxamro.html

[y for x in nested for y in x]
来源：http://dali.andypj.xyz/Article/details/gt2jxpvdhki.html

[U09] Py：字典取最大值的键
来源：http://dali.zhengqikj.top/Article/details/gt2cwfgrifq.html

max(d, key=d.get)
来源：http://dali.ehwqpu.com/Article/details/gt2ovyvebyz.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2avantpjc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gt2aworreap.html

[U11] Py：生成器表达式
来源：http://dali.aibaodan.cn/Article/details/gt2ofilbjtm.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gt2cambjwcb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gt2kohtrgzv.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gt2lfouobll.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2gajnmego.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vcqpvwvq.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cuzobixh.html

defaultdict(list)
来源：http://dali.gotoacloud.top/Article/details/gt2tfmuphuy.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gt2uculojew.html

t = time.perf_counter()
来源：http://dali.zdqjudy.top/Article/details/gt2fgmnpfxm.html

[U16] Py：命令行参数解析
来源：http://dali.shuidangran.top/Article/details/gt2epphvqxj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gt2exlkceof.html

[U17] Py：初始化日志
来源：http://dali.hfpthk.cn/Article/details/gt2uqprbknd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.aibaodan.cn/Article/details/gt2ooheglip.html

[U18] Py：预编译正则
来源：http://dali.cucudq.cn/Article/details/gt2uaqghqxk.html

pat = re.compile(r"\d+")
来源：http://dali.sxryk.cn/Article/details/gt2lbkkmmpx.html

[U19] Py：正则替换带回调
来源：http://dali.gzhubu.top/Article/details/gt2axpiqudj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfoxhjhk.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gt2bxpohlrs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gzhubu.top/Article/details/gt2zsctnnbf.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnxiangtu.top/Article/details/gt2jmjyplhv.html

@contextlib.contextmanager
来源：http://dali.pycfn.com/Article/details/gt2sfwtrdet.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gt2jeqhzsen.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2nfltejym.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2tzxgkzkb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nanxuanxn.top/Article/details/gt2atfspgls.html

[U24] Py：路径操作
来源：http://dali.xziqi.cn/Article/details/gt2swgszgmn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2dbvjnwti.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gt2yvtqemku.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gt2yrvaitmf.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gt2bkbjkcvw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tanke756.top/Article/details/gt2fbxuvyqb.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gt2mbbuxnai.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2uosteikl.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gt2kfhdfgoq.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gt2hmzwuxyp.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gt2whcsgrcs.html

@property 与 @x.setter 配合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtjcjprv.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gt2dtozdseg.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gt2uemlysfy.html

[U31] Py：单测
来源：http://dali.redwolf501.top/Article/details/gt2pxgdmyuy.html

python -m pytest -q
来源：http://dali.bjfxy.top/Article/details/gt2zwrqzacr.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gt2lqhkmcac.html

ruff format . && ruff check --fix .
来源：http://dali.pengpengdd.cyou/Article/details/gt2yrdjfcjg.html

[U33] Py：打包发布
来源：http://dali.andypj.xyz/Article/details/gt2ysuzkgqs.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jlsjyb.cn/Article/details/gt2bgkepfzq.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gt2llmnunsx.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gt2uhmgkgln.html

[U35] Py：发送邮件
来源：http://dali.jqgfzy.top/Article/details/gt2ysedgjrt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.havefunace.top/Article/details/gt2ciixprqb.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gt2evrchsbx.html

schedule.every(10).minutes.do(job)
来源：http://dali.nwbrower.top/Article/details/gt2kdlpggjo.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gt2gpdpheqn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gogol.net.cn/Article/details/gt2mgssquie.html

[U38] Py：获取脚本所在目录
来源：http://dali.yanxiufei.cn/Article/details/gt2qzmzzhan.html

Path(__file__).resolve().parent
来源：http://dali.xinyue.icu/Article/details/gt2hxojbqhm.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2tyktutid.html

sys.stdout.isatty()
来源：http://dali.yvedp.cn/Article/details/gt2xroerpgy.html

[U40] Py：打印到标准错误
来源：http://dali.feifeiyinyue.top/Article/details/gt2bahxphlj.html

print("err", file=sys.stderr)
来源：http://dali.9152youxi.cn/Article/details/gt2rplgawaw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gt2pshuhgsd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yuxming.cn/Article/details/gt2qrpvcrmk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gotoacloud.top/Article/details/gt2kgqflqaz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gt2sbewonrx.html

[U43] PHP：声明命名空间
来源：http://dali.mhx1999.top/Article/details/gt2nhhokkyc.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gt2xxufbebn.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gt2smaqobpf.html

declare(strict_types=1);
来源：http://dali.jqgufenzy.top/Article/details/gt2uupttrjj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cashguo.top/Article/details/gt2ckaleooc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2lcpupekv.html

[U46] PHP：可空类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2epgynhvl.html

?string $name = null
来源：http://dali.meibo888.top/Article/details/gt2jkbknjxq.html

[U47] PHP：联合类型
来源：http://dali.wangdashe.top/Article/details/gt2hbcuptyd.html

int|string $id
来源：http://dali.fzhhl.top/Article/details/gt2imcszahd.html

[U48] PHP：纯枚举
来源：http://dali.tian-w.cn/Article/details/gt2qtaomhbu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2qdhiaheq.html

[U49] PHP：只读属性
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2comadkpr.html

public readonly string $name
来源：http://dali.jlsjyb.cn/Article/details/gt2bwvwnzlw.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gt2rbhkfjpd.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gt2sytrwigo.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkgdnpxs.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gt2tvlejrbe.html

[U52] PHP：箭头函数
来源：http://dali.zdqjudy.top/Article/details/gt2awgbjvtf.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nuwvrpdq.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gt2imbychfz.html

$v = $a ?? $b ?? "default";
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhqvqwhk.html

[U54] PHP：空安全调用
来源：http://dali.9152youxi.cn/Article/details/gt2lltrytyw.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gt2gouscwqk.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2puyzcjwt.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.andypj.xyz/Article/details/gt2mdxpdqil.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2ygxgezly.html

f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2ekvrcufi.html

[U57] PHP：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2jeqptfzu.html

"值: {$a}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2zcljpgnv.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gt2okopsqvf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yongpay.top/Article/details/gt2eynoeklr.html

[U59] PHP：自定义排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2mbixtpbm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guannengcc.top/Article/details/gt2gfpomero.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gt2dcutftty.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.0kj1m.cn/Article/details/gt2uqpqpbec.html

[U61] PHP：正则
来源：http://dali.sxryk.cn/Article/details/gt2hpsbeuum.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gt2mbfdoemm.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gt2tgabexjc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gt2zwkpbjka.html

[U63] PHP：文件读写
来源：http://dali.yuxming.cn/Article/details/gt2bmbaabrv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jinqigfzy.top/Article/details/gt2szszudrp.html

[U64] PHP：目录遍历
来源：http://dali.guowangkeji.top/Article/details/gt2vapatrrd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gt2glkuowqq.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gt2toylwvai.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2otkdifxi.html

[U66] PHP：设置 Cookie
来源：http://dali.aizwys.cn/Article/details/gt2eadopvmq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gt2qfmjiaqc.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gt2ogiahdkd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gt2chyovvet.html

[U68] PHP：PDO 连接
来源：http://dali.gotoacloud.top/Article/details/gt2filzvuyy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxjrkhhs.html

[U69] PHP：PDO 预处理
来源：http://dali.sweek.top/Article/details/gt2vefmcslr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gt2cyrobkvk.html

[U70] PHP：PDO 事务
来源：http://dali.ppjwa.cn/Article/details/gt2edykpxoi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gt2iwtyscvl.html

[U71] PHP：抛出异常
来源：http://dali.quarkkingdee.top/Article/details/gt2pacuknal.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gt2zcwgzvrn.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gt2cteprmby.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jyoumei.cn/Article/details/gt2gjqmyvfu.html

[U73] PHP：读取 ini 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wwxexwlc.html

parse_ini_file("config.ini", true)
来源：http://dali.gaohongyu789.top/Article/details/gt2txcyssgz.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2vwudfbva.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvhoqhpp.html

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gt2lwncwxad.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2jtjjduwi.html

[U76] PHP：简单路由
来源：http://dali.hfpthk.cn/Article/details/gt2cprekzyw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gt2njxwsvko.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gt2lcjkgkfy.html

composer require twig/twig
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrjzymqf.html

[U78] PHP：单元测试
来源：http://dali.shangyingyoupin.top/Article/details/gt2fnsqfdvz.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gt2bqrnkbbh.html


<!-- 参考信息 -->