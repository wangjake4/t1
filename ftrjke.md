代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknlcizuq.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtarkxyjht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtzjsrfzbm.html

[S50] C++：格式化数字
来源：http://dali.cheryme.top/Article/details/gtamoaefyg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtespbwknl.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gtclzntdmv.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtjpwmdaxg.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsegmfvol.html

int size() const noexcept { return n_; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbdmchfme.html

[S53] C++：移动语义
来源：http://dali.yongpay.top/Article/details/gtfddorqks.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtatpzbbje.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtohvbidna.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtybewfggq.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfglciek.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtparwlkjp.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtipurxery.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gtyjkvrtdp.html

[S57] C++：编译期常量
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjpuzkdy.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtsgjohukh.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gthlazinme.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtpmizpiwv.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtqowcuend.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgufenzy.top/Article/details/gtfhhqrgbh.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtcfnlptxx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftexuyuf.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtvcjsqnpz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtvbckpeig.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtsjmtardk.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtdiwiugdl.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtfwitwiek.html

[T02] Kotlin：变量
来源：http://dali.birdmap.top/Article/details/gtrjgnulbj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtsiegqcge.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtakoucyzo.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtruqprrxc.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtektzenaq.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtcntdyjvb.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtjqhditqu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gtlutlhbnq.html

[T06] Kotlin：集合映射
来源：http://dali.nwbrower.top/Article/details/gtndugdhao.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fengsongda.top/Article/details/gtorkoruiw.html

[T07] Kotlin：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gtvmwkuclw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gtdjqgsfbp.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gthpxluxto.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtizucwnll.html

[T09] Kotlin：扩展函数
来源：http://dali.jyoumei.cn/Article/details/gtdesgkolu.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtvjrcgozl.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtthfaddib.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtkpgihftq.html

[T11] Kotlin：协程
来源：http://dali.jyoumei.cn/Article/details/gtvzihmern.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtijxrlchi.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtqpkctnyq.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvrmpnph.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtxzsaqvvb.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtueuveruq.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gtpsoiqedu.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtnsuxytxf.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtpmozwxzf.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlzztfzhi.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtqzzkviyo.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtjtzrpuqd.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtznlluxxb.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gtzufgwmlw.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyhqfnap.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtxnpfsxeu.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtluqsyovq.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtxqakfeod.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gtwbxoisfc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gtznvpsdfr.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhzxgske.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvbbbmmqq.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gteuowtopa.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtmwushzxl.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gtzearbqwr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtzynvsvov.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gtqswklnfo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtixzsvbjs.html

[T25] Swift：结构体
来源：http://dali.xziqi.cn/Article/details/gtluvoksnp.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gttqcpnbfp.html

[T26] Swift：类与重写
来源：http://dali.jinghuilouyu.cn/Article/details/gtmnciaqjj.html

class A: Base { override func f() {} }
来源：http://dali.haohaochexian.top/Article/details/gtfecbtdcw.html

[T27] Swift：错误处理
来源：http://dali.hfpthk.cn/Article/details/gtgimjehiy.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtdubbuwll.html

[T28] Swift：枚举
来源：http://dali.yongpay.top/Article/details/gtaoohjwdn.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtsguivapd.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gtoxmhpxkw.html

guard let x = opt else { return }
来源：http://dali.zycfv.cn/Article/details/gtflhotnaj.html

[T30] Swift：协议
来源：http://dali.gaohongyu789.top/Article/details/gtchhqnqin.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gttteescfi.html

[T31] Lua：Hello World
来源：http://dali.redwolf501.top/Article/details/gtlcliuvns.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtcyhlfnic.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtzvvvnxpt.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gtbqkrgnai.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gttfwhwjxp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtmrpiroyh.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtazsetdgr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuxming.cn/Article/details/gtyfijelpz.html

[T35] Lua：字典表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkcdoyen.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtyeakhoby.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtyotvjjqw.html

function add(a, b) return a + b end
来源：http://dali.dianchejie.cn/Article/details/gtwxznbzax.html

[T37] Lua：字符串拼接
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbepugptg.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsolbmkji.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gttjccikjk.html

if x > 0 then print("正") end
来源：http://dali.pengpengdd.cyou/Article/details/gtxppnuoxq.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gthqeizxpk.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gttarzfold.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gtmyrpfgpq.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gtvzdjnfgd.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtswswlvgu.html

print "Hello\n";
来源：http://dali.jyoumei.cn/Article/details/gtiqwnibqs.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtunoztrtq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxgjjiaec.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtqaxugzlq.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtiwwpnyum.html

[T44] Perl：条件
来源：http://dali.jlsjyb.cn/Article/details/gtftbliozg.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtgmjsopmx.html

[T45] Perl：数组遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtylofsdez.html

for my $x (@arr) { print $x; }
来源：http://dali.zycfv.cn/Article/details/gtaeoobqzb.html

[T46] Perl：哈希操作
来源：http://dali.nanxuanxn.top/Article/details/gtvlnfulax.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtwcescbgd.html

[T47] Perl：正则捕获
来源：http://dali.aibaodan.cn/Article/details/gtlkgjpnvq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtfcgtnldp.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtmccatwwr.html

$s =~ s/old/new/g;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdchrosto.html

[T49] Perl：函数
来源：http://dali.bjfxy.top/Article/details/gttitutsdf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjfwejppy.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtscosuxfe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.0kj1m.cn/Article/details/gtywjougjm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hammf.cn/Article/details/gthfzrsvuw.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtsjpezole.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtzkfqqqwa.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtuawjhats.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtwqwmaewm.html

[T53] Scala：字符串插值
来源：http://dali.tanke756.top/Article/details/gtqfloubus.html

s"值: $b"
来源：http://dali.vqdsnc.cn/Article/details/gtumkdlpxd.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxzeusro.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtrtshszzk.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtxlsxyviw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yangfankeji.com/Article/details/gtlwpgwndl.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gtdoemtrya.html

case class User(name: String, age: Int)
来源：http://dali.sysykeji.top/Article/details/gtukdrjjhd.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gthbkijavq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtbgbejxhs.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gtwczlbtnn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtgdvtqbhb.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtryroqqsv.html

for (i <- 1 to 10) println(i)
来源：http://dali.daria6918.cn/Article/details/gtuptbhodq.html

[T60] Scala：折叠
来源：http://dali.nanxinkj.top/Article/details/gtfwwzvibv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhoulong.xyz/Article/details/gtkiixudud.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlnuqxzit.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtabmdbfka.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtbayhzgyq.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gtujkdqoiq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhoulong.xyz/Article/details/gtnrxemequ.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhoulong.xyz/Article/details/gtosliskbe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gtxfvklibg.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtjdkhlvwq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gtkbgxzvao.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtjgyhcmsr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmubqtfcb.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gthvvrkqku.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtevovpvqf.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtlqrujnzh.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtlgjmudmz.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gttwkbfhuo.html

{v: k for k, v in d.items()}
来源：http://dali.vqdsnc.cn/Article/details/gtbdapknlw.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtvxgyoxwr.html

[y for x in nested for y in x]
来源：http://dali.guowangkeji.top/Article/details/gtdyyuslpg.html

[U09] Py：字典取最大值的键
来源：http://dali.havefunace.top/Article/details/gtqinychhj.html

max(d, key=d.get)
来源：http://dali.yonumen.top/Article/details/gtbpafhzwm.html

[U10] Py：按值排序字典
来源：http://dali.hywenlv.cn/Article/details/gtotfmgnyd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yonumen.top/Article/details/gtsjvlxxgk.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gtvkipuhqi.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gtqecgccei.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yongpay.top/Article/details/gtroibckch.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtbqjfooie.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gtjnkpqakc.html

deque(maxlen=10)
来源：http://dali.daria6918.cn/Article/details/gtsuhbxhxr.html

[U14] Py：分组收集到列表
来源：http://dali.yj202588.top/Article/details/gtbhnvityx.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtqpervxco.html

[U15] Py：高精度计时
来源：http://dali.xinyue.icu/Article/details/gtqnpogeda.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtokmzuija.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gtciluzqck.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.svipenyu.cn/Article/details/gteeyanxnq.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtwbbpyezl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gtyrmqptwc.html

[U18] Py：预编译正则
来源：http://dali.gaohongyu789.top/Article/details/gtyzennbxh.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gtgspvnqxf.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtzqvsyttu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xinyue.icu/Article/details/gtfzegajoe.html

[U20] Py：缓存函数结果
来源：http://dali.aibaodan.cn/Article/details/gteuwfqscd.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnfjjbts.html

[U21] Py：自定义上下文管理器
来源：http://dali.aizwys.cn/Article/details/gttugspltd.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gtfqyzmeab.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gtmcrwicyh.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gttosvbfai.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gtsxhyjspu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zdqjudy.top/Article/details/gtjmvrzgur.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtumozylbu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtpnifqyxe.html

[U25] Py：CSV 按字典读
来源：http://dali.yueranfly.top/Article/details/gtrbfymmcj.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtvgrpmffl.html

[U26] Py：并发下载
来源：http://dali.yuxming.cn/Article/details/gtttjfnzfr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yueranfly.top/Article/details/gtfuvssizs.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtjnwatewd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xylfe.cn/Article/details/gtaxkrxjsr.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gtdboqcjuo.html

UserId = int
来源：http://dali.kuanghao11.cn/Article/details/gtfzocxlbu.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtmtyjcisx.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gtxinenuox.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtfpghxejl.html

@dataclass(slots=True)
来源：http://dali.chenzaomai.com/Article/details/gtmlitgojm.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtpnwmvmoe.html

python -m pytest -q
来源：http://dali.aizwys.cn/Article/details/gtvllzocch.html

[U32] Py：代码格式化
来源：http://dali.gogol.net.cn/Article/details/gttubilues.html

ruff format . && ruff check --fix .
来源：http://dali.gotoacloud.top/Article/details/gtuolwcyyo.html

[U33] Py：打包发布
来源：http://dali.jqgufenzy.top/Article/details/gtfkamynmf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jianghu66.top/Article/details/gthgnugtsk.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtsdgojrrb.html

chardet.detect(raw)
来源：http://dali.ydzc1.top/Article/details/gtweoebehs.html

[U35] Py：发送邮件
来源：http://dali.hywenlv.cn/Article/details/gtdpmzhmgp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gtihszkvps.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtvgcavctf.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgfzy.top/Article/details/gtyctxjqvx.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtccozybrg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.0kj1m.cn/Article/details/gthmfeoycg.html

[U38] Py：获取脚本所在目录
来源：http://dali.tian-w.cn/Article/details/gthrrwvfkk.html

Path(__file__).resolve().parent
来源：http://dali.yueranfly.top/Article/details/gtpfgovekx.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gtfkimzivf.html

sys.stdout.isatty()
来源：http://dali.cucudq.cn/Article/details/gtwgiaidah.html

[U40] Py：打印到标准错误
来源：http://dali.nanxuanxn.top/Article/details/gtximarghr.html

print("err", file=sys.stderr)
来源：http://dali.ehwqpu.com/Article/details/gtmafnubyb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cucudq.cn/Article/details/gtxdewcfjf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jinqigufen.top/Article/details/gtjscwvuly.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cucudq.cn/Article/details/gtudcflnqa.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nanxuanxn.top/Article/details/gtbnlimbwj.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gtaofspptm.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtvdelurth.html

[U44] PHP：开启严格类型
来源：http://dali.jiagoushi.top/Article/details/gtovdjhqqc.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtouruxuas.html

[U45] PHP：类型声明与返回类型
来源：http://dali.gotoacloud.top/Article/details/gtoorcgmyp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtqqcgenls.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gtivdhlvuy.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtowvlexgg.html

[U47] PHP：联合类型
来源：http://dali.gotoacloud.top/Article/details/gtgiayfyxk.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gtaylclpkh.html

[U48] PHP：纯枚举
来源：http://dali.cheryme.top/Article/details/gtfqwfkrrg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xinyue.icu/Article/details/gtbgdkktzn.html

[U49] PHP：只读属性
来源：http://dali.dianchejie.cn/Article/details/gtbyflhyeb.html

public readonly string $name
来源：http://dali.dianchejie.cn/Article/details/gtgumyxtvf.html

[U50] PHP：构造器属性提升
来源：http://dali.sysykeji.top/Article/details/gtkgvlmsrp.html

public function __construct(private int $id) {}
来源：http://dali.gogol.net.cn/Article/details/gtixzbaphu.html

[U51] PHP：数组解构
来源：http://dali.jlsjyb.cn/Article/details/gtdkxtjjqb.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtisvyzoll.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtcsrdgsrq.html

$double = fn($x) => $x * 2;
来源：http://dali.316326.xyz/Article/details/gtwrrupdtz.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gturykolmk.html

$v = $a ?? $b ?? "default";
来源：http://dali.gzhubu.top/Article/details/gtoyqbkgnx.html

[U54] PHP：空安全调用
来源：http://dali.sweek.top/Article/details/gtfjnvtpxm.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gtgmzhmtsg.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyffehkbr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtfeqayznf.html

[U56] PHP：命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtaeaeusrd.html

f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtnfnpaiix.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtueqwsmpw.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtogzazctu.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtjfqjsrrz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gtwiandfzr.html

[U59] PHP：自定义排序
来源：http://dali.ehwqpu.com/Article/details/gtjdldcpql.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.0kj1m.cn/Article/details/gtfqwyhmre.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gtejdfigqv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.chenzaomai.com/Article/details/gtiyozrgdi.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtzaggrggv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cdnleiting.top/Article/details/gtejqgxjfz.html

[U62] PHP：日期对象
来源：http://dali.mhx1999.top/Article/details/gtzjcykgce.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cashguo.top/Article/details/gtskqinejj.html

[U63] PHP：文件读写
来源：http://dali.zhoulong.xyz/Article/details/gtpaioayii.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shanyushiyangtech.top/Article/details/gtycbcniwi.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtupvhosfq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpxgeerb.html

[U65] PHP：会话
来源：http://dali.vqdsnc.cn/Article/details/gtqfmvwqua.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtzwcqzfeu.html

[U66] PHP：设置 Cookie
来源：http://dali.shuidangran.top/Article/details/gtzweaztok.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtvevnmmfw.html

[U67] PHP：处理文件上传
来源：http://dali.daria6918.cn/Article/details/gtcsfdgfoq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gotoacloud.top/Article/details/gtowuakefg.html

[U68] PHP：PDO 连接
来源：http://dali.9152youxi.cn/Article/details/gtafhbslcn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtqffeppvr.html

[U69] PHP：PDO 预处理
来源：http://dali.nwbrower.top/Article/details/gtsmnvthcs.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgmauxbm.html

[U70] PHP：PDO 事务
来源：http://dali.zhijiandao.cn/Article/details/gtfmuxdymd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pycfn.com/Article/details/gtszxvezzd.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtxcfurklk.html

throw new RuntimeException("失败", 500);
来源：http://dali.cucudq.cn/Article/details/gtgdvsmjlo.html

[U72] PHP：写错误日志
来源：http://dali.9152youxi.cn/Article/details/gtqghsvqaz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxxvvnyq.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkiplule.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtusstdgrv.html

[U74] PHP：读取环境变量
来源：http://dali.ydzc1.top/Article/details/gtjqwukduq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tianlin.xyz/Article/details/gtmqjfubvu.html


<!-- 参考信息 -->