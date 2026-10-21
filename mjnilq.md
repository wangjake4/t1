代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.cashguo.top/Article/details/gtnamtmrqa.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtumxbseto.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtylpffbsp.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtknqxgcrb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.havefunace.top/Article/details/gtcvuesahc.html

[S51] C++：显式类型转换
来源：http://dali.sxryk.cn/Article/details/gtvraupsio.html

static_cast<double>(a) / b
来源：http://dali.tian-w.cn/Article/details/gtcfbxboks.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gtiqezzhup.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtqdugeohp.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gtbqbhdlup.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtspnkbrqr.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtcxxxahsh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gttlptfmbb.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gtkcfsueeg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtldvnampc.html

[S56] C++：optional
来源：http://dali.zhijiandao.cn/Article/details/gtmcfduiwi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtlqxxxbog.html

[S57] C++：编译期常量
来源：http://dali.hnqzz.top/Article/details/gtnkbvwpwq.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gttxhtwash.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtkecmauns.html

namespace ns { int f() { return 1; } }
来源：http://dali.9152youxi.cn/Article/details/gttznwvcih.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtznkytnct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtimcdfzbe.html

[S60] C++：遍历并删除元素
来源：http://dali.havefunace.top/Article/details/gtczdczira.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtenddjluq.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gthkqbruib.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtujtvatih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmrhqptbo.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtmfdipifp.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtmyntvhso.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvwqyqio.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtupowibvg.html

[T03] Kotlin：字符串模板
来源：http://dali.hnqzz.top/Article/details/gtgwbjsdnq.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtpskuvijn.html

[T04] Kotlin：空安全
来源：http://dali.gzhubu.top/Article/details/gtgtsrvdev.html

val n: String? = null;  n?.length
来源：http://dali.mhx1999.top/Article/details/gthznsmjss.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtfwvnndbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtukoprald.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtonskpagn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtdrwbwohj.html

[T07] Kotlin：集合过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkwxcqlpa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gtgcsjfcjt.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtjphloipb.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtdbejudhg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhijiandao.cn/Article/details/gtmwwpssfm.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtwdcrficq.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtpbbezfza.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gtkisvouph.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gtwpzrhaxy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gtcapotjtl.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtiqeftlwh.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtybgfrkxo.html

[T13] Kotlin：只读 Map
来源：http://dali.zhiwuduotai.top/Article/details/gtgqutbxig.html

val m = mapOf("a" to 1)
来源：http://dali.gzhubu.top/Article/details/gtsqdlkwpl.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gttckcknve.html

for (i in 1..10) println(i)
来源：http://dali.haohaochexian.top/Article/details/gteijgpvcu.html

[T15] Kotlin：接口
来源：http://dali.sysykeji.top/Article/details/gtvhbdmvci.html

interface Shape { fun area(): Double }
来源：http://dali.iojbl.cn/Article/details/gtradxbtih.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtlljulbcp.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtxcdgjzdj.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtffxlhzxa.html

var a = 1;  let b = 2
来源：http://dali.ehwqpu.com/Article/details/gtdtckgugc.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gteolwpupu.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtimjboyql.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtwpjydrpo.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtjvjoquwn.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtzzzycmdi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gttxzgwzei.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtxwunscnv.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtovrubekg.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtvuvzxdok.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtembqdpnv.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gtynreddyv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gtboolxpcs.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gteoxsgxvw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtbwdnvism.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gtqaubkcvg.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtuqfpqgnv.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gtstjacywo.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirleqbxo.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtguuwegmt.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtvsoybtmh.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gtzepdztcw.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtfpvxhype.html

[T29] Swift：guard 提前返回
来源：http://dali.sweek.top/Article/details/gtzktyfvad.html

guard let x = opt else { return }
来源：http://dali.tian-w.cn/Article/details/gtsgireqci.html

[T30] Swift：协议
来源：http://dali.fengsongda.top/Article/details/gtrfpsnknt.html

protocol Shape { func area() -> Double }
来源：http://dali.vqdsnc.cn/Article/details/gtdfdsyagb.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtdcjvkptd.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtbtwkyekj.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtznldrqvl.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtikzslaoi.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gtqflqhmdl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtqjcbylnl.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtcmzcljjo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenzaomai.com/Article/details/gtldjhkcsz.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtbdeyfywe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtemkxstuj.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtgdsjaqxr.html

function add(a, b) return a + b end
来源：http://dali.hnqzz.top/Article/details/gtjkrjbbct.html

[T37] Lua：字符串拼接
来源：http://dali.havefunace.top/Article/details/gtmzjfxrxs.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtxjaeurqt.html

[T38] Lua：条件
来源：http://dali.sxryk.cn/Article/details/gtrjfytapv.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gtpyinhdqs.html

[T39] Lua：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gteimvnaeb.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtdifwrqih.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtuhxepahl.html

setmetatable({}, { __index = base })
来源：http://dali.9152youxi.cn/Article/details/gtxqcrdppz.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtdigtbewt.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtnxjsjqng.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtevicqaoz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtbdjkffod.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gttpdajune.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtojyekukc.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gtoibylcpr.html

if ($a > 0) { print "正"; }
来源：http://dali.tian-w.cn/Article/details/gtalcyqjsz.html

[T45] Perl：数组遍历
来源：http://dali.havefunace.top/Article/details/gthzzrmown.html

for my $x (@arr) { print $x; }
来源：http://dali.c1oappe.top/Article/details/gtqvxholvw.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtsorvvjcd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxysifnus.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gtqkwfxowy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtbarwzstt.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gtpjcpaski.html

$s =~ s/old/new/g;
来源：http://dali.shangyingyoupin.top/Article/details/gtuwpnsmfs.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtfarzblfh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxtylymty.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtesskhwft.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jyoumei.cn/Article/details/gtgaulnber.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shuidangran.top/Article/details/gtkjjpqwcl.html

[T51] Scala：Hello World
来源：http://dali.shuidangran.top/Article/details/gtfkshklao.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtgmgjmxmd.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gteddoacwr.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtoaaevajo.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtpgmjseko.html

s"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtzhlztdlb.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtwgrvcvhs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenlongwang.top/Article/details/gtckmuevwj.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gtqhmhozpj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.316326.xyz/Article/details/gtxtqqvlsg.html

[T56] Scala：样例类
来源：http://dali.shzxlz.cn/Article/details/gtpxssnwto.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsgjujfgi.html

[T57] Scala：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtooyrllzr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtwuoycmvu.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gttohqjnzt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gtyxsjdmae.html

[T59] Scala：循环
来源：http://dali.gotoacloud.top/Article/details/gtjmltvrif.html

for (i <- 1 to 10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtzltankkv.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtqqxmgrqy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gtbhfjsuob.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwzauhukx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhixingplan.top/Article/details/gtpgwkgzxz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtedwqiysi.html

[U01] Py：创建虚拟环境
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlszpumxx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtmkgxysqn.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtxlqdwbij.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tianlin.xyz/Article/details/gtyydufzlw.html

[U03] Py：加载 .env 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakyyfamf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtzerrehuq.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtblmfdrnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtgpyrgtjk.html

[U05] Py：列表去重且保序
来源：http://dali.nanxinkj.top/Article/details/gtkvvbcndx.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gtytzorrqn.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtbychcxuo.html

{**a, **b}
来源：http://dali.yongpay.top/Article/details/gtzoorkdfh.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gteadhfjzl.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gtyjitvpzz.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtprjbjnqj.html

[y for x in nested for y in x]
来源：http://dali.tianlin.xyz/Article/details/gtrjunbrkg.html

[U09] Py：字典取最大值的键
来源：http://dali.ivvv.top/Article/details/gtdrugoksv.html

max(d, key=d.get)
来源：http://dali.shzxlz.cn/Article/details/gtbofkwtln.html

[U10] Py：按值排序字典
来源：http://dali.nanxuanxn.top/Article/details/gtshrbvkju.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xylfe.cn/Article/details/gtkaxpujyg.html

[U11] Py：生成器表达式
来源：http://dali.birdmap.top/Article/details/gttpusjhbm.html

(x * 2 for x in arr)
来源：http://dali.ydzc1.top/Article/details/gtunpmovru.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtdepsxoof.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gteghfugbg.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gtchrkhbrt.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtuwlwdhew.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtbhupumjp.html

defaultdict(list)
来源：http://dali.aibaodan.cn/Article/details/gtbdistwcd.html

[U15] Py：高精度计时
来源：http://dali.quarkkingdee.top/Article/details/gtnczaxzlq.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gtjslkaqkx.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gtqgfddasr.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtnfxdlqja.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gtrlacqjxd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtoscislfb.html

[U18] Py：预编译正则
来源：http://dali.hammf.cn/Article/details/gtclzqolil.html

pat = re.compile(r"\d+")
来源：http://dali.havefunace.top/Article/details/gtkwnjqmtj.html

[U19] Py：正则替换带回调
来源：http://dali.yangfankeji.com/Article/details/gtuulxfppq.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxinkj.top/Article/details/gtqatcuqlc.html

[U20] Py：缓存函数结果
来源：http://dali.gogol.net.cn/Article/details/gtznjpiymc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gttuyhjidm.html

[U21] Py：自定义上下文管理器
来源：http://dali.ivvv.top/Article/details/gtagfoymhx.html

@contextlib.contextmanager
来源：http://dali.sweek.top/Article/details/gtmtfvjlbb.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gthumclprh.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gtgbgmtjtm.html

[U23] Py：分块读取大文件
来源：http://dali.havefunace.top/Article/details/gteutiuoqx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gtbxydgyqv.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gtaqsioekb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tianlin.xyz/Article/details/gtrbyedudu.html

[U25] Py：CSV 按字典读
来源：http://dali.gotoacloud.top/Article/details/gtbpzpoecv.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtgqtalcba.html

[U26] Py：并发下载
来源：http://dali.yj202588.top/Article/details/gtogvnldiq.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtapxzzkhe.html

[U27] Py：异步 HTTP
来源：http://dali.haohaochexian.top/Article/details/gtxnsjjllh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtduaaqmer.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gtyvtyejmk.html

UserId = int
来源：http://dali.9152youxi.cn/Article/details/gtolmqouyl.html

[U29] Py：属性校验
来源：http://dali.yueranfly.top/Article/details/gtcfdxisde.html

@property 与 @x.setter 配合
来源：http://dali.9152youxi.cn/Article/details/gtadvtmkuz.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtihbiezad.html

@dataclass(slots=True)
来源：http://dali.zhiwuduotai.top/Article/details/gtqsptspja.html

[U31] Py：单测
来源：http://dali.jinqigfzy.top/Article/details/gthorykidu.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gtjhvyhtok.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtyuamkmlv.html

ruff format . && ruff check --fix .
来源：http://dali.guowangkeji.top/Article/details/gtuxadhzrf.html

[U33] Py：打包发布
来源：http://dali.iojbl.cn/Article/details/gtteggctbp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.guannengcc.top/Article/details/gtcxujcahb.html

[U34] Py：判断编码
来源：http://dali.sxryk.cn/Article/details/gtkplykrui.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtyfzmmkgz.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gttejrynqd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cheryme.top/Article/details/gtrndmquji.html

[U36] Py：定时任务
来源：http://dali.sufxvd.cn/Article/details/gtedhaxuit.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtfgeyqvvl.html

[U37] Py：读写 Excel
来源：http://dali.jlsjyb.cn/Article/details/gtjhtwimfh.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gtcltsoyfw.html

[U38] Py：获取脚本所在目录
来源：http://dali.jianghu66.top/Article/details/gtolvlnhiu.html

Path(__file__).resolve().parent
来源：http://dali.hnxiangtu.top/Article/details/gtjbmtqopp.html

[U39] Py：判断是否在交互环境
来源：http://dali.xinyue.icu/Article/details/gtyegjtmrz.html

sys.stdout.isatty()
来源：http://dali.iojbl.cn/Article/details/gtwcroflfk.html

[U40] Py：打印到标准错误
来源：http://dali.tanke756.top/Article/details/gtvgfcwiaf.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtvdkljlql.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gtuygqlpdl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.havefunace.top/Article/details/gtjeqwnmen.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhiwuduotai.top/Article/details/gtivpnfads.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtfkgkwabm.html

[U43] PHP：声明命名空间
来源：http://dali.snrcjt.cn/Article/details/gtuwvqrxzh.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtwyghevos.html

[U44] PHP：开启严格类型
来源：http://dali.mhx1999.top/Article/details/gtppbehdiq.html

declare(strict_types=1);
来源：http://dali.hywenlv.cn/Article/details/gtokvhcpbz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwkgjmel.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtiiiicqvh.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gtuigzonod.html

?string $name = null
来源：http://dali.chenlongwang.top/Article/details/gtfkpkkkpo.html

[U47] PHP：联合类型
来源：http://dali.vqdsnc.cn/Article/details/gtcjspsdwh.html

int|string $id
来源：http://dali.jinqigfzy.top/Article/details/gtrxgnychi.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gtlxpknhqz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigufen.top/Article/details/gtleyiewtc.html

[U49] PHP：只读属性
来源：http://dali.tian-w.cn/Article/details/gtakqksndm.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtqnvwkmxi.html

[U50] PHP：构造器属性提升
来源：http://dali.fengsongda.top/Article/details/gtbgyywzcr.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gtxjbtukab.html

[U51] PHP：数组解构
来源：http://dali.redwolf501.top/Article/details/gtodeelvre.html

[$a, $b] = $arr;
来源：http://dali.jqgfzy.top/Article/details/gtsvwwvxup.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtmzyjvhkh.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtqlzebbjy.html

[U53] PHP：空合并运算符
来源：http://dali.yj20258888.top/Article/details/gthpjpzuga.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtfkfnntlk.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gttvbywxvp.html

$obj?->method()
来源：http://dali.yanxiufei.cn/Article/details/gtaxbnkgdd.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtvvlvsvvj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.9152youxi.cn/Article/details/gtqjlrsglz.html

[U56] PHP：命名参数
来源：http://dali.yueranfly.top/Article/details/gtxceubepo.html

f(a: 1, b: 2)
来源：http://dali.jqgufenzy.top/Article/details/gtmgysindc.html

[U57] PHP：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtgyfvuogu.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtoadkbqlv.html

[U58] PHP：数组三件套
来源：http://dali.aizwys.cn/Article/details/gtipcxhbqe.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gthgvcabpm.html

[U59] PHP：自定义排序
来源：http://dali.yvedp.cn/Article/details/gtjtguaepi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gtjtevjsdf.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtplhumskj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gtmdelxchw.html

[U61] PHP：正则
来源：http://dali.daxiang520.top/Article/details/gtkolutuqg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gtamsjgoot.html

[U62] PHP：日期对象
来源：http://dali.zhongyouzk.top/Article/details/gtzavaglcw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.smart0.xyz/Article/details/gtanrrwztf.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gtdmdnfrjg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gthhzrloyu.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkyypxzsi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.chenlongwang.top/Article/details/gtgcjyuxhr.html

[U65] PHP：会话
来源：http://dali.jinqigufen.top/Article/details/gtyolmyxdn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtozcwkwxu.html

[U66] PHP：设置 Cookie
来源：http://dali.0kj1m.cn/Article/details/gtepbnjdoa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ppjwa.cn/Article/details/gtkumkawvr.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcdwatosi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gtrflgtnat.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gtltmvxcil.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gtnoqtdwtm.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtbkllvchp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gtuylmdsez.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gteiowcnez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gtwsfxpcpz.html

[U71] PHP：抛出异常
来源：http://dali.yvedp.cn/Article/details/gtoxpryric.html

throw new RuntimeException("失败", 500);
来源：http://dali.snrcjt.cn/Article/details/gtdfwapism.html

[U72] PHP：写错误日志
来源：http://dali.cashguo.top/Article/details/gtfplnkwwo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aizwys.cn/Article/details/gtozdomwuf.html

[U73] PHP：读取 ini 配置
来源：http://dali.redwolf501.top/Article/details/gtfbhyupcw.html

parse_ini_file("config.ini", true)
来源：http://dali.fengsongda.top/Article/details/gtesjszhjl.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtzgbgttys.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ybcxt.top/Article/details/gtbdtvrvtm.html


<!-- 参考信息 -->