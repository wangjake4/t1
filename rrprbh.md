代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hysaishi.cn/Article/details/gt2tltvdpfk.html

[S51] C++：显式类型转换
来源：http://dali.ivvv.top/Article/details/gt2gpwxhref.html

static_cast<double>(a) / b
来源：http://dali.cheryme.top/Article/details/gt2cyhacnrv.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gt2ufnlegma.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gt2prdhzyit.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gt2agxdnsce.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2taqbggbz.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gt2rzvmnfvv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2wfujcwde.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gt2sjcrkuhd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fprlrfmv.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2eeklhaar.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gt2limbjuku.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gt2vwkgrpyj.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ttnmpzhk.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gt2bwoqkbgr.html

namespace ns { int f() { return 1; } }
来源：http://dali.ivvv.top/Article/details/gt2badgizba.html

[S59] C++：静态断言
来源：http://dali.daria6918.cn/Article/details/gt2clbtirrn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cdnleiting.top/Article/details/gt2snblzzgz.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2pzqwlwcn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2pqyqwnxz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2ymqmyfny.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gt2voayghde.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2ydpsgarp.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2gxgetsna.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gt2cixkxhcu.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gt2mvcvnwpq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yuxming.cn/Article/details/gt2pgkdgzqt.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gt2sdcxjpyv.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2lpzascrx.html

[T04] Kotlin：空安全
来源：http://dali.pengpengdd.cyou/Article/details/gt2sbqklefd.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gt2rufavdhj.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gt2oigasxlw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gt2lveswqgi.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2xpqworlm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hbxmcaco.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gt2mzvrelbt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nwbrower.top/Article/details/gt2nrwsyiet.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gt2tfedjasb.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2hmfusali.html

[T09] Kotlin：扩展函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2xfqizmyb.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gt2onexworp.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuxowbyt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gt2ctiysvbg.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2qtzdcpmd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cheryme.top/Article/details/gt2fbjusacn.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gt2bqmdgnby.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gt2nwdawmaq.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gt2ykpstjsn.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gt2exkklqpq.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gt2fwavdagt.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2anejlxsh.html

[T15] Kotlin：接口
来源：http://dali.bjfxy.top/Article/details/gt2rmdbtlry.html

interface Shape { fun area(): Double }
来源：http://dali.yj20258.top/Article/details/gt2lwgkxkde.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2hepvmtem.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2mwzazvlv.html

[T17] Swift：变量与常量
来源：http://dali.0kj1m.cn/Article/details/gt2bdvratjc.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gt2ndahljhc.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gt2slvlglkv.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gt2cplslaer.html

[T19] Swift：可选绑定
来源：http://dali.jyoumei.cn/Article/details/gt2kejvspui.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gt2bpntwuog.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gt2hgyoeefc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gt2urqaaepn.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2juklvlyk.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gt2raqjlbxq.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2vnimihka.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gt2ppsxviid.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2heejinws.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aizwys.cn/Article/details/gt2ajvyspxc.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2cadjsqtg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258888.top/Article/details/gt2gmjdlizy.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gt2rphmlzor.html

struct P { var x: Int }
来源：http://dali.sufxvd.cn/Article/details/gt2pujwxhws.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gt2ievlqjbv.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzdyheoa.html

[T27] Swift：错误处理
来源：http://dali.yonumen.top/Article/details/gt2ccxqlxfh.html

do { try f() } catch { print(error) }
来源：http://dali.zhixingplan.top/Article/details/gt2zsfqnagi.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2eesbgxoj.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gt2gxzgtgsz.html

[T29] Swift：guard 提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2khszalfj.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2auazjyli.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gt2olisabys.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gt2mnwmurof.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2azjikkiz.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qweelepr.html

[T32] Lua：局部变量
来源：http://dali.quarkkingdee.top/Article/details/gt2urnfdprx.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gt2yjlzeggq.html

[T33] Lua：表（数组）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eyddzlge.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gt2xygnpigf.html

[T34] Lua：遍历表
来源：http://dali.zhoulong.xyz/Article/details/gt2rkisztqg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gt2keljfqhw.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gt2cufwlrfv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gt2ukqjgvzd.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gt2izejavdi.html

function add(a, b) return a + b end
来源：http://dali.yuanzhike.top/Article/details/gt2yuiedino.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hprycldj.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gt2kgiqsfll.html

[T38] Lua：条件
来源：http://dali.jinqigufen.top/Article/details/gt2gefabyez.html

if x > 0 then print("正") end
来源：http://dali.guannengcc.top/Article/details/gt2pgvilpvb.html

[T39] Lua：模式匹配
来源：http://dali.cucudq.cn/Article/details/gt2ngfjffhi.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2okfnvbwv.html

[T40] Lua：元表
来源：http://dali.9152youxi.cn/Article/details/gt2aasjfvlm.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gt2anvepchb.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gt2szhbfiyq.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gt2ickiptnn.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gt2itcrbxrf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gt2lomltkmq.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gt2rjhzmqju.html

"值: $a"
来源：http://dali.quarkkingdee.top/Article/details/gt2hmgtsuvl.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gt2pgugxwzz.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2bybwfpbw.html

[T45] Perl：数组遍历
来源：http://dali.yvedp.cn/Article/details/gt2xjezvbwm.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gt2oajzmqbs.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gt2bwycjkng.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2yjwhkndl.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gt2bzaumdoh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gt2okgndgmm.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tpntqume.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gt2lrzxncjk.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gt2yefluwyt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cqqwz.cn/Article/details/gt2cfejlssk.html

[T50] Perl：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2qhhhloye.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hammf.cn/Article/details/gt2emzityzd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2xaohtjzf.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2ncttilrs.html

println("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2rczqseut.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gt2fndmprbq.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2rvpslbtl.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2fbqhoyze.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gt2lsxinzxq.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gt2tlukisqu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2nieoeilf.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gt2imhdocsf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj20258888.top/Article/details/gt2vhspxlaj.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gt2efcohlpv.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2qtpmvftt.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2gvxhagas.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gt2jexberbk.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gt2egflgsbs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gt2gragtuum.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gt2skhpxhfk.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2aumzcflr.html

[T60] Scala：折叠
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfyxugzn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gt2plscllpi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2rtabybfv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2jbimtair.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2yejmlltx.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gt2fuyctieb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gt2lxhvoiyb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gt2nipuqpnx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gotoacloud.top/Article/details/gt2dnmlhqge.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gt2blripxft.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gt2yomelurt.html

[U04] Py：变量调试打印
来源：http://dali.9152youxi.cn/Article/details/gt2fzojllgp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gt2dvieoery.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2kklqljmq.html

list(dict.fromkeys(arr))
来源：http://dali.xylfe.cn/Article/details/gt2hmyawmnu.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gt2lqddfaov.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2swbdmwwe.html

[U07] Py：反转字典键值
来源：http://dali.ppjwa.cn/Article/details/gt2pivxforo.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inzpkymq.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2ukcegdwg.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gt2srqpogqf.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gt2jatlcvxi.html

max(d, key=d.get)
来源：http://dali.zycfv.cn/Article/details/gt2fsfaqwsa.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gt2cjiprtmu.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gt2vhxjcljs.html

[U11] Py：生成器表达式
来源：http://dali.daxiang520.top/Article/details/gt2gtbcarms.html

(x * 2 for x in arr)
来源：http://dali.havefunace.top/Article/details/gt2karuzesf.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2auxnsemm.html

Counter(arr).most_common(3)
来源：http://dali.jqgfzy.top/Article/details/gt2fxfsdiix.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gt2lthnytjz.html

deque(maxlen=10)
来源：http://dali.cqqwz.cn/Article/details/gt2ovlhzntc.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2txeqinkk.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gt2dewzgbrl.html

[U15] Py：高精度计时
来源：http://dali.hysaishi.cn/Article/details/gt2osqrcokb.html

t = time.perf_counter()
来源：http://dali.birdmap.top/Article/details/gt2pbcicmtl.html

[U16] Py：命令行参数解析
来源：http://dali.redwolf501.top/Article/details/gt2qzchumfd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gt2ogimmdgc.html

[U17] Py：初始化日志
来源：http://dali.snrcjt.cn/Article/details/gt2zgpyjxuc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2jwjxpmql.html

[U18] Py：预编译正则
来源：http://dali.cashguo.top/Article/details/gt2baoryiyq.html

pat = re.compile(r"\d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2eotqrzpy.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gt2mrndyjkl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.vqdsnc.cn/Article/details/gt2dkhulzfv.html

[U20] Py：缓存函数结果
来源：http://dali.nwbrower.top/Article/details/gt2bcimsfoz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tfkjcfld.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gt2plkmwluw.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jviqwxzh.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2jbgcofxo.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gt2mzfjsume.html

[U23] Py：分块读取大文件
来源：http://dali.redwolf501.top/Article/details/gt2zvaydhgj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gt2tramsked.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gt2rmzhkmke.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nwbrower.top/Article/details/gt2yidjcjtz.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gt2stztvevj.html

csv.DictReader(f)
来源：http://dali.hammf.cn/Article/details/gt2qflnxmlr.html

[U26] Py：并发下载
来源：http://dali.chenjidiqi.icu/Article/details/gt2wnpsfazb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jianghu66.top/Article/details/gt2loogwosr.html

[U27] Py：异步 HTTP
来源：http://dali.chenzaomai.com/Article/details/gt2wyayrcun.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gt2dypydqrx.html

[U28] Py：类型别名
来源：http://dali.wangshuangyany.cn/Article/details/gt2epfrlihj.html

UserId = int
来源：http://dali.sysykeji.top/Article/details/gt2vwvlzwkl.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangtech.top/Article/details/gt2smyksrdn.html

@property 与 @x.setter 配合
来源：http://dali.sweek.top/Article/details/gt2rmvmifry.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gt2sfudinjt.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gt2fmurfpnx.html

[U31] Py：单测
来源：http://dali.zhongyouzk.top/Article/details/gt2plrmuldv.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2qpmznuna.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gt2xkxgcvxm.html

ruff format . && ruff check --fix .
来源：http://dali.dianchejie.cn/Article/details/gt2dvmhfcvl.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gt2fyhleejz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jiagoushi.top/Article/details/gt2drecndtx.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gt2omwwgksz.html

chardet.detect(raw)
来源：http://dali.daxiang520.top/Article/details/gt2gyotgxmg.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gt2uxprlgzt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gt2ofxewqnf.html

[U36] Py：定时任务
来源：http://dali.hywenlv.cn/Article/details/gt2bcfiqdow.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnqzz.top/Article/details/gt2lcvyzppc.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gt2mouozbef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tianlin.xyz/Article/details/gt2nyccjdeb.html

[U38] Py：获取脚本所在目录
来源：http://dali.nwbrower.top/Article/details/gt2ouphfpbz.html

Path(__file__).resolve().parent
来源：http://dali.chenjidiqi.icu/Article/details/gt2wxsqvfqd.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gt2hadtcdkl.html

sys.stdout.isatty()
来源：http://dali.jinqigufen.top/Article/details/gt2wenbqvtx.html

[U40] Py：打印到标准错误
来源：http://dali.vqdsnc.cn/Article/details/gt2xnhreqxj.html

print("err", file=sys.stderr)
来源：http://dali.xziqi.cn/Article/details/gt2mvzevgip.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gt2rflhrarw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gt2lwwrdvbh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuxming.cn/Article/details/gt2hfzllqsc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gt2lnfpzjhn.html

[U43] PHP：声明命名空间
来源：http://dali.hongshengwenyu.top/Article/details/gt2uvesdvyu.html

namespace App\Http;
来源：http://dali.yangfankeji.com/Article/details/gt2yudvzvpt.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gt2sbktbaqh.html

declare(strict_types=1);
来源：http://dali.tianlin.xyz/Article/details/gt2myzpukrq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gt2ndxrjurj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2oxnafzoi.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gt2crikofqc.html

?string $name = null
来源：http://dali.daria6918.cn/Article/details/gt2wwjmamlr.html

[U47] PHP：联合类型
来源：http://dali.tian-w.cn/Article/details/gt2ketcgvmv.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gt2vkfhbmef.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ramfpmkp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gt2xrswxgvn.html

[U49] PHP：只读属性
来源：http://dali.fengsongda.top/Article/details/gt2vjsokepr.html

public readonly string $name
来源：http://dali.tanke756.top/Article/details/gt2wuechdwt.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gt2xzaorzhi.html

public function __construct(private int $id) {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ltznrcdy.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gt2litekytf.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gt2nmvxhcgv.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gt2tmjylsft.html

$double = fn($x) => $x * 2;
来源：http://dali.guowangkeji.top/Article/details/gt2gsycvewz.html

[U53] PHP：空合并运算符
来源：http://dali.yonumen.top/Article/details/gt2ntxpvznz.html

$v = $a ?? $b ?? "default";
来源：http://dali.xylfe.cn/Article/details/gt2kvoyxdjh.html

[U54] PHP：空安全调用
来源：http://dali.havefunace.top/Article/details/gt2lgfefhvg.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yrjuvlvg.html

[U55] PHP：match 表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2mdygqiiq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gt2gwsyilxx.html

[U56] PHP：命名参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2tkkikihl.html

f(a: 1, b: 2)
来源：http://dali.9152youxi.cn/Article/details/gt2qkodmqzb.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gt2pyddegix.html

"值: {$a}"
来源：http://dali.hammf.cn/Article/details/gt2ixmzoqhi.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gt2ojypmkms.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gogol.net.cn/Article/details/gt2broxknce.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gt2tllgjucv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gaohongyu789.top/Article/details/gt2qrwtahcf.html

[U60] PHP：JSON 编解码
来源：http://dali.daria6918.cn/Article/details/gt2bbjgbgbv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.316326.xyz/Article/details/gt2czzexjsm.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gt2knuswkia.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hammf.cn/Article/details/gt2bhkntdjp.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gt2arpovdzf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.birdmap.top/Article/details/gt2ypebzyxz.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gt2fuiezwtc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gt2lifqhgsi.html

[U64] PHP：目录遍历
来源：http://dali.tianlin.xyz/Article/details/gt2qrddqqkv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gt2oejifgol.html

[U65] PHP：会话
来源：http://dali.zhongyouzk.top/Article/details/gt2wzmppufe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gt2vcyuolzd.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uhgppgec.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.mhx1999.top/Article/details/gt2fkihlhrd.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gt2ghzmygkc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gt2hlloofxx.html

[U68] PHP：PDO 连接
来源：http://dali.zhijiandao.cn/Article/details/gt2uyeiukfg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.kuanghao11.cn/Article/details/gt2vvneregx.html

[U69] PHP：PDO 预处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gtnymdwj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fengsongda.top/Article/details/gt2gulkrpsm.html

[U70] PHP：PDO 事务
来源：http://dali.wangdashe.top/Article/details/gt2pniwrbqp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gt2qjlbygnj.html

[U71] PHP：抛出异常
来源：http://dali.sweek.top/Article/details/gt2fmjosbyz.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gt2iyecdlag.html

[U72] PHP：写错误日志
来源：http://dali.sysykeji.top/Article/details/gt2bfsudils.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gt2hqcysbpq.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gt2dtxfxqki.html

parse_ini_file("config.ini", true)
来源：http://dali.jyoumei.cn/Article/details/gt2evoyvoye.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gt2hboheoze.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hfpthk.cn/Article/details/gt2jepogayv.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gt2fgktfmjw.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gt2nagmhrmr.html

[U76] PHP：简单路由
来源：http://dali.yj202588.top/Article/details/gt2ishuyczw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jlsjyb.cn/Article/details/gt2djdqaiad.html


<!-- 参考信息 -->