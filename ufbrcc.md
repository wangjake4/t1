代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gt2dqrcxnon.html

[S53] C++：移动语义
来源：http://dali.cdnleiting.top/Article/details/gt2auvuqeof.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2eqangvbe.html

[S54] C++：异常处理
来源：http://dali.sysykeji.top/Article/details/gt2gssvrdbr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gt2igwelfnf.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gt2apnohbem.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gt2jzmuqvem.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gt2xozsayfy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj202588.top/Article/details/gt2ykjhfqcd.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gt2bcbwzbgq.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gt2jhfypjiv.html

[S58] C++：命名空间
来源：http://dali.smart0.xyz/Article/details/gt2ukhuyqqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gt2wrwueqox.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2nbtnrmjl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gt2igredwxq.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gt2fuxczksx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zzglebcs.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ephtbiqq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigfzy.top/Article/details/gt2wzjngxcm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2xzfmanlr.html

[T01] Kotlin：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2ezximkdz.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2eupiuddr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oomiyfhk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gt2jvibnyze.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gt2ufysxejw.html

"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gt2vlfszevw.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2cbylktjn.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2kcsmbwgg.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gt2zyqehlsg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2zxixudbe.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2yjbghyss.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gt2gvvavuly.html

[T07] Kotlin：集合过滤
来源：http://dali.hammf.cn/Article/details/gt2hgltmojv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.bjfxy.top/Article/details/gt2vlcmzknz.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ruzdhkvb.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2tgyuisua.html

[T09] Kotlin：扩展函数
来源：http://dali.nwbrower.top/Article/details/gt2evhcburx.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gt2gthngigi.html

[T10] Kotlin：默认参数
来源：http://dali.yongpay.top/Article/details/gt2ortffcfz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gt2usbdipxv.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2rxaswcjm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2fwkcoogr.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dqsfippr.html

val (a, b) = Pair(1, 2)
来源：http://dali.nwbrower.top/Article/details/gt2geyblylp.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gt2vaydkavt.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2rfrshsmg.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2huksdzlx.html

for (i in 1..10) println(i)
来源：http://dali.sweek.top/Article/details/gt2tikvqrkn.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gt2eerqflae.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gt2brpkjcsb.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2agibspga.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gt2vqqbecrx.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gt2wjwtsbac.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2gpfcwspm.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2uwnwfjwk.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwkqjavw.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gt2kjfwxybc.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gt2gbspkpmj.html

[T20] Swift：数组操作
来源：http://dali.gaohongyu789.top/Article/details/gt2vteuhvdn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gt2ckjnoaon.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2bgvjznpk.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gt2jxqktone.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2yxhervik.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gt2iakjgsgf.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2gauzkazo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gt2hmtertci.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2vemqsxdz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcymbmgs.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gt2laatrccw.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gt2zvlgmdet.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gt2sktaijxz.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2myigxjjy.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gt2zhxbzzaw.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2hngnbzpy.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2etezqyhq.html

enum Color { case red, green }
来源：http://dali.hongshengwenyu.top/Article/details/gt2regunexk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2npnzntdw.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gt2kwbwfwfh.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gt2wvwewdgr.html

protocol Shape { func area() -> Double }
来源：http://dali.yuanzhike.top/Article/details/gt2xgcnxsge.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2axmxapfq.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2plpdnczt.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gt2vzulfflk.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gt2tzliyizx.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gt2kpwuapvb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqmhbsqf.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gt2cktnhkpt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2mvedqzxh.html

[T35] Lua：字典表
来源：http://dali.havefunace.top/Article/details/gt2wrqcfrpj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gt2leuckcin.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gt2xqswgyrz.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gt2hwidsczc.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2huehozxg.html

"a" .. "b"
来源：http://dali.guannengcc.top/Article/details/gt2khwkudnd.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2cqffqayj.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ohqiusnj.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gt2nhgtzggb.html

string.find(s, "%d+")
来源：http://dali.sxryk.cn/Article/details/gt2mxsgmekg.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gt2ebcymfln.html

setmetatable({}, { __index = base })
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtscldqh.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2rpiansac.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gt2odbpvzop.html

[T42] Perl：变量类型
来源：http://dali.sweek.top/Article/details/gt2rnuyxdnd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gt2jrctjyoo.html

[T43] Perl：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gt2skcrupvv.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gt2xxnimajz.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nawlofzx.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2gulymqwi.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2sbpmkfkj.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvgrdvzr.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvtwuvxl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yvedp.cn/Article/details/gt2zkrmgmvd.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gt2cvkqaqoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2epsgsfoa.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hdownpgg.html

$s =~ s/old/new/g;
来源：http://dali.shuidangran.top/Article/details/gt2iasenibv.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2zvbctvss.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2cnseyefa.html

[T50] Perl：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2tbofdkqs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gt2qicajrnl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhixingplan.top/Article/details/gt2oxpdpcgv.html

[T51] Scala：Hello World
来源：http://dali.aizwys.cn/Article/details/gt2aiukkgbk.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2icwghmsv.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cgwwimgd.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gt2rfuojygg.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hursnpwf.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2aygxlxcv.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gt2jdqeeime.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gt2eoqevzqd.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gt2rbgmfqfr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jqgufenzy.top/Article/details/gt2ajncgdqi.html

[T56] Scala：样例类
来源：http://dali.smart0.xyz/Article/details/gt2kkfhrrmz.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gt2swpcpolu.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2rzvbiwhk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2tiwvpzmm.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gt2sekvpbrw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gt2enpyhhfl.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gt2rcmdwirw.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gt2kvtjczvx.html

[T60] Scala：折叠
来源：http://dali.fengsongda.top/Article/details/gt2nhcbalis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gt2rwhfzxdb.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2worlqbtn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.birdmap.top/Article/details/gt2rkzqftsi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tehsflzp.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gt2uizunahr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2ixfovcej.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yonumen.top/Article/details/gt2xrogztwd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xziqi.cn/Article/details/gt2fzftckct.html

[U03] Py：加载 .env 配置
来源：http://dali.redwolf501.top/Article/details/gt2mvesilfb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gt2exzfwdhm.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gt2zughvbnr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2drnqktdp.html

[U05] Py：列表去重且保序
来源：http://dali.zycfv.cn/Article/details/gt2rncqoynf.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2kazmvkhw.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gt2oedvsvgl.html

{**a, **b}
来源：http://dali.cashguo.top/Article/details/gt2boajdquh.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2rtxvrchb.html

{v: k for k, v in d.items()}
来源：http://dali.0kj1m.cn/Article/details/gt2emnykgpy.html

[U08] Py：展平二维列表
来源：http://dali.zhongyouzk.top/Article/details/gt2cukmzsfc.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gt2okbosvvs.html

[U09] Py：字典取最大值的键
来源：http://dali.cucudq.cn/Article/details/gt2zvuvoabh.html

max(d, key=d.get)
来源：http://dali.yanxiufei.cn/Article/details/gt2lsmswdwj.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbticowz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tian-w.cn/Article/details/gt2jrywmtig.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2cizgiqbx.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2fnbtrzfx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gt2jdwplyah.html

Counter(arr).most_common(3)
来源：http://dali.jyoumei.cn/Article/details/gt2jcxuaqql.html

[U13] Py：固定长度队列
来源：http://dali.shzxlz.cn/Article/details/gt2qswgihym.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gt2gykkebfu.html

[U14] Py：分组收集到列表
来源：http://dali.0kj1m.cn/Article/details/gt2yrhnkaah.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gt2jtnxlvxt.html

[U15] Py：高精度计时
来源：http://dali.ivvv.top/Article/details/gt2xiiwzdbj.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gt2ikfmyuip.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gt2wuijttsb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuxming.cn/Article/details/gt2odfodijr.html

[U17] Py：初始化日志
来源：http://dali.daxiang520.top/Article/details/gt2evdhudqx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gt2glexcyzf.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gt2zzmjdidj.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gt2hamnifgw.html

[U19] Py：正则替换带回调
来源：http://dali.feifeiyinyue.top/Article/details/gt2oznziall.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2krtotqck.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gt2pissxtzj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gt2mftwkbjm.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2quobocgl.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gt2uwamvjji.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gt2bvihtkjd.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gt2kjmrytby.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gt2wrsdirkn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gt2eqeqizhx.html

[U24] Py：路径操作
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygqypjfu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.snrcjt.cn/Article/details/gt2ggvytgfk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhongyouzk.top/Article/details/gt2obwxnjoy.html

csv.DictReader(f)
来源：http://dali.fzhhl.top/Article/details/gt2vlukyvqi.html

[U26] Py：并发下载
来源：http://dali.dashuyun.cn/Article/details/gt2ngpyfugx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gaohongyu789.top/Article/details/gt2sykmfbdj.html

[U27] Py：异步 HTTP
来源：http://dali.gzhubu.top/Article/details/gt2tfachyix.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhixingplan.top/Article/details/gt2pirpvlyg.html

[U28] Py：类型别名
来源：http://dali.quarkkingdee.top/Article/details/gt2ymtbhzgh.html

UserId = int
来源：http://dali.shangyingyoupin.top/Article/details/gt2ihwjeugj.html

[U29] Py：属性校验
来源：http://dali.daxiang520.top/Article/details/gt2ltvfgboe.html

@property 与 @x.setter 配合
来源：http://dali.hongshengwenyu.top/Article/details/gt2zyssdift.html

[U30] Py：数据类
来源：http://dali.cheryme.top/Article/details/gt2qoihwqhn.html

@dataclass(slots=True)
来源：http://dali.zycfv.cn/Article/details/gt2ahlkmuzc.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gt2fnjltvxc.html

python -m pytest -q
来源：http://dali.smart0.xyz/Article/details/gt2qukofauk.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gt2svvwqnlb.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gt2rnfutbma.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gt2msmhgmnl.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.meibo888.top/Article/details/gt2eysrzclx.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gt2jikrivvk.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gt2uuhqoqsl.html

[U35] Py：发送邮件
来源：http://dali.shangyingyoupin.top/Article/details/gt2gntpoghm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.sysykeji.top/Article/details/gt2pfzmacsk.html

[U36] Py：定时任务
来源：http://dali.mhx1999.top/Article/details/gt2sucskwlv.html

schedule.every(10).minutes.do(job)
来源：http://dali.redwolf501.top/Article/details/gt2uexijrwy.html

[U37] Py：读写 Excel
来源：http://dali.yongpay.top/Article/details/gt2gtfufixd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gt2cieffdim.html

[U38] Py：获取脚本所在目录
来源：http://dali.meibo888.top/Article/details/gt2vsobolnk.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gt2bpvyjwnd.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gt2ntsqdwta.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gt2cfaepukm.html

[U40] Py：打印到标准错误
来源：http://dali.ybcxt.top/Article/details/gt2wydldbys.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lfxqijjv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gaohongyu789.top/Article/details/gt2xwpaxksj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.nanxuanxn.top/Article/details/gt2glmgckis.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxzepygs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aizwys.cn/Article/details/gt2bnwyeolb.html

[U43] PHP：声明命名空间
来源：http://dali.iojbl.cn/Article/details/gt2eovhwjxk.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gt2wlazzfuj.html

[U44] PHP：开启严格类型
来源：http://dali.snrcjt.cn/Article/details/gt2pxzaywys.html

declare(strict_types=1);
来源：http://dali.xinyue.icu/Article/details/gt2mufrclip.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gt2qgvdiyxm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2kfrieawl.html

[U46] PHP：可空类型
来源：http://dali.cqqwz.cn/Article/details/gt2dpweyhjy.html

?string $name = null
来源：http://dali.ydzc1.top/Article/details/gt2pxffoydd.html

[U47] PHP：联合类型
来源：http://dali.haohaochexian.top/Article/details/gt2viskareq.html

int|string $id
来源：http://dali.cashguo.top/Article/details/gt2mntazpos.html

[U48] PHP：纯枚举
来源：http://dali.yj20258.top/Article/details/gt2ksneobbh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gt2uklcfjmg.html

[U49] PHP：只读属性
来源：http://dali.yuxming.cn/Article/details/gt2gdbqiinw.html

public readonly string $name
来源：http://dali.gotoacloud.top/Article/details/gt2qauamxag.html

[U50] PHP：构造器属性提升
来源：http://dali.meibo888.top/Article/details/gt2wqfhkror.html

public function __construct(private int $id) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjonzevs.html

[U51] PHP：数组解构
来源：http://dali.tian-w.cn/Article/details/gt2baafcbuh.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gt2doemipnt.html

[U52] PHP：箭头函数
来源：http://dali.hnqzz.top/Article/details/gt2oxqkpemm.html

$double = fn($x) => $x * 2;
来源：http://dali.ydzc1.top/Article/details/gt2xxzqpiej.html

[U53] PHP：空合并运算符
来源：http://dali.hnqzz.top/Article/details/gt2zqcfdxkw.html

$v = $a ?? $b ?? "default";
来源：http://dali.daria6918.cn/Article/details/gt2wtqtzyti.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gt2yzdznpzk.html

$obj?->method()
来源：http://dali.shzxlz.cn/Article/details/gt2desptctj.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gt2njfqzhnu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2rtktetax.html

[U56] PHP：命名参数
来源：http://dali.sweek.top/Article/details/gt2vxnrdazo.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2aabfdvii.html

[U57] PHP：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gt2laxjhgtb.html

"值: {$a}"
来源：http://dali.tanke756.top/Article/details/gt2mojjyvhx.html

[U58] PHP：数组三件套
来源：http://dali.guannengcc.top/Article/details/gt2rulhswep.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gt2isqhncid.html

[U59] PHP：自定义排序
来源：http://dali.nanxinkj.top/Article/details/gt2puunsltm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuxming.cn/Article/details/gt2urwexieg.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ynovncra.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sufxvd.cn/Article/details/gt2upmvnaqv.html

[U61] PHP：正则
来源：http://dali.ydzc1.top/Article/details/gt2dtpostbq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fengsongda.top/Article/details/gt2dridsecz.html

[U62] PHP：日期对象
来源：http://dali.chenlongwang.top/Article/details/gt2uignghpw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nwbrower.top/Article/details/gt2lpqaralv.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gt2fryvdckx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gt2gkzcrwmg.html

[U64] PHP：目录遍历
来源：http://dali.cdnleiting.top/Article/details/gt2tjkhimcn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.vqdsnc.cn/Article/details/gt2tacjsdih.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2oejavmzj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2wellqjtw.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258.top/Article/details/gt2bekzeted.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2mikuaqbb.html

[U67] PHP：处理文件上传
来源：http://dali.xuanzx.com/Article/details/gt2crgotkei.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gt2poypvzev.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gt2xpyrbzsa.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lrmmkhhw.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gt2nhonxplk.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2euavwpen.html

[U70] PHP：PDO 事务
来源：http://dali.jlsjyb.cn/Article/details/gt2qkxgptou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yanxiufei.cn/Article/details/gt2lggietvf.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2jeqgshzt.html

throw new RuntimeException("失败", 500);
来源：http://dali.xylfe.cn/Article/details/gt2ndvyvert.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2wfkjfhbe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenzaomai.com/Article/details/gt2agubzrcx.html

[U73] PHP：读取 ini 配置
来源：http://dali.ehwqpu.com/Article/details/gt2flfroecc.html

parse_ini_file("config.ini", true)
来源：http://dali.fzhhl.top/Article/details/gt2endnjkod.html

[U74] PHP：读取环境变量
来源：http://dali.hammf.cn/Article/details/gt2hgsiwenf.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gt2kqjmufsc.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gt2ixwyvmls.html

composer require psr/container
来源：http://dali.yvedp.cn/Article/details/gt2mmkchabn.html

[U76] PHP：简单路由
来源：http://dali.jlsjyb.cn/Article/details/gt2vjbdngmn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hammf.cn/Article/details/gt2xtdtmrfd.html

[U77] PHP：模板渲染
来源：http://dali.jqgufenzy.top/Article/details/gt2gzifogey.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gt2mucrqqru.html

[U78] PHP：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcpgotnk.html

composer require --dev phpunit/phpunit
来源：http://dali.jiagoushi.top/Article/details/gt2lemfmmkp.html


<!-- 参考信息 -->