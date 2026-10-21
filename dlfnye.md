代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyklcofak.html

[S53] C++：移动语义
来源：http://dali.jiagoushi.top/Article/details/gtjdcbpzcz.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcpqvzwi.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtjioyehfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtcrnksjlt.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtjqphsmgj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtdepbjuaf.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtengaaeoz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.316326.xyz/Article/details/gtjsuniati.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtyuqqriib.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtpjqpszyo.html

[S58] C++：命名空间
来源：http://dali.jyoumei.cn/Article/details/gthxkthzdt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtohrtnveg.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtfbkylfpn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jqgfzy.top/Article/details/gtdytxdzwi.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtbuamofmu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shuidangran.top/Article/details/gtpxrbfyma.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtqsuwudhe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtnxkinoao.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtaodmbrkb.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtgjvmovwj.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gtaftmtlim.html

[T02] Kotlin：变量
来源：http://dali.hywenlv.cn/Article/details/gtsupwfqle.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtyxxhzham.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqzebccc.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtshfwjotx.html

[T04] Kotlin：空安全
来源：http://dali.zycfv.cn/Article/details/gttuqbixtt.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtefugulhw.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtmyhtzpew.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtkrtqcfhs.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtvovzogvs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ybcxt.top/Article/details/gtsxopjwnt.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtqrrstnyd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtiyarflpq.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtpxjcjwyf.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gttduzcevv.html

[T09] Kotlin：扩展函数
来源：http://dali.ydzc1.top/Article/details/gtmzxypdoo.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtqvzsuosk.html

[T10] Kotlin：默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtvrkchfxs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gtqbnnebkm.html

[T11] Kotlin：协程
来源：http://dali.sweek.top/Article/details/gtgjxlcjtg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtfqrurlhi.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtnedugudb.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtzyekckxe.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtrpsqxmkd.html

val m = mapOf("a" to 1)
来源：http://dali.zhoulong.xyz/Article/details/gtdpoofpem.html

[T14] Kotlin：循环
来源：http://dali.zhoulong.xyz/Article/details/gtxgtouzln.html

for (i in 1..10) println(i)
来源：http://dali.jqgufenzy.top/Article/details/gtnoavjnho.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtoganvnxa.html

interface Shape { fun area(): Double }
来源：http://dali.yonumen.top/Article/details/gtllchounv.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtjizrbphs.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtauudpmjz.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtlrcicrty.html

var a = 1;  let b = 2
来源：http://dali.sufxvd.cn/Article/details/gtcqivwhwi.html

[T18] Swift：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwdpawms.html

"值: \(b)"
来源：http://dali.ivvv.top/Article/details/gtqnjpvpdn.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gthziiwvcn.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtvveamyyh.html

[T20] Swift：数组操作
来源：http://dali.xuetiantiany.cn/Article/details/gtpphwdwuc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ivvv.top/Article/details/gtemrxkfky.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtgwemebvj.html

for x in a { print(x) }
来源：http://dali.havefunace.top/Article/details/gtbmcwvqmc.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gttlxdaari.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ppjwa.cn/Article/details/gtklfthdsc.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gttmlqyofz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtsrltxyoh.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtemkdumta.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtmgwthpto.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtuwanwpaj.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtiwtesltc.html

[T26] Swift：类与重写
来源：http://dali.xuetiantiany.cn/Article/details/gtjecdksrm.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtidjidwyt.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtwlunfrvp.html

do { try f() } catch { print(error) }
来源：http://dali.quarkkingdee.top/Article/details/gtbrolxjen.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtylloagrb.html

enum Color { case red, green }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrsbqfcyf.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gtfpsuspug.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gtiilaukxk.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtfghypqex.html

protocol Shape { func area() -> Double }
来源：http://dali.9152youxi.cn/Article/details/gtvibtjxom.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxzxngvcj.html

print("Hello")
来源：http://dali.yueranfly.top/Article/details/gtlchlpthw.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gtdgezacqz.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtpqlruoju.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtvmryxjdd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtxnsdeaaw.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtiverkpvl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.svipenyu.cn/Article/details/gtkxtuqpof.html

[T35] Lua：字典表
来源：http://dali.nwbrower.top/Article/details/gthahtoohk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtprualyoe.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtncqhhygh.html

function add(a, b) return a + b end
来源：http://dali.yanxiufei.cn/Article/details/gttqkaaqdo.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gthhmpdwmw.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtibcfphxq.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtvgdjgbvq.html

if x > 0 then print("正") end
来源：http://dali.yongpay.top/Article/details/gtvqvbaozb.html

[T39] Lua：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtwkycziig.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gtlqjbqdbu.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtatomkzbr.html

setmetatable({}, { __index = base })
来源：http://dali.hammf.cn/Article/details/gtuabhnsun.html

[T41] Perl：Hello World
来源：http://dali.redwolf501.top/Article/details/gtcsyyzcui.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtmskxoazt.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtfilpacbw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtuagcondf.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtbxrzacdk.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrpyhatlf.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtyvqgpwpk.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gtulqavlps.html

[T45] Perl：数组遍历
来源：http://dali.yanxiufei.cn/Article/details/gtpucnllxp.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258.top/Article/details/gtwlsyskzq.html

[T46] Perl：哈希操作
来源：http://dali.zhixingplan.top/Article/details/gtdiabqtud.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtaqdyriww.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gtlguagqel.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwidlrswc.html

[T48] Perl：正则替换
来源：http://dali.kuanghao11.cn/Article/details/gtxjfjsxzc.html

$s =~ s/old/new/g;
来源：http://dali.yonumen.top/Article/details/gtzynvqdjy.html

[T49] Perl：函数
来源：http://dali.aizwys.cn/Article/details/gtsfpglfok.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtvzvsaswa.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtmnppjbvg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gthpjbwrqt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqarzgpw.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtngozvehp.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtrfxzmmsx.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gtihzxezff.html

val a = 1;  var b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtycgufzfa.html

[T53] Scala：字符串插值
来源：http://dali.yj202588.top/Article/details/gtgjswuewx.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtdragttrs.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtguchwqdv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtovpylwea.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtgpufpjze.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtirxfjllt.html

[T56] Scala：样例类
来源：http://dali.yanxiufei.cn/Article/details/gtlveimlnc.html

case class User(name: String, age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtxsbommzs.html

[T57] Scala：模式匹配
来源：http://dali.cheryme.top/Article/details/gtgafmgdse.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtltzzzvvc.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtymzvjymj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gteuwsbpzs.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtbfzpdduj.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gtjtpjethr.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtvulrdvvf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtnyxderry.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtldgwvoaj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.quarkkingdee.top/Article/details/gtkjmpvmik.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtqcbevmqq.html

[U01] Py：创建虚拟环境
来源：http://dali.yonumen.top/Article/details/gtvvwmwuvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.snrcjt.cn/Article/details/gtfebxoszy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtlayuzjvb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gtardipnzk.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtwuvsepsh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shangyingyoupin.top/Article/details/gtfzwomgue.html

[U04] Py：变量调试打印
来源：http://dali.andypj.xyz/Article/details/gtabecmrup.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.andypj.xyz/Article/details/gtxstbqwrb.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gtvlfugaki.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gthjeluisi.html

[U06] Py：合并两个字典
来源：http://dali.tanke756.top/Article/details/gtiwlqbtvf.html

{**a, **b}
来源：http://dali.zycfv.cn/Article/details/gtfonmcimk.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gtmfquxaol.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gtfamtofqx.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtajxvemcn.html

[y for x in nested for y in x]
来源：http://dali.sweek.top/Article/details/gtffjwfppy.html

[U09] Py：字典取最大值的键
来源：http://dali.snrcjt.cn/Article/details/gtslvbjdlg.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtlvegzzsd.html

[U10] Py：按值排序字典
来源：http://dali.mhx1999.top/Article/details/gttxahqrrj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtuqwvzorv.html

[U11] Py：生成器表达式
来源：http://dali.yanxiufei.cn/Article/details/gtlqhgcahn.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxzujvudh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yonumen.top/Article/details/gtttgbcswo.html

Counter(arr).most_common(3)
来源：http://dali.yj202588.top/Article/details/gtswmbwskr.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtonjnxqga.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtbgblvovm.html

[U14] Py：分组收集到列表
来源：http://dali.pengpengdd.cyou/Article/details/gtxjrdaaxr.html

defaultdict(list)
来源：http://dali.jinqigufen.top/Article/details/gtzqlodppp.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gtjcpohvrl.html

t = time.perf_counter()
来源：http://dali.nanxuanxn.top/Article/details/gtnggbhtjz.html

[U16] Py：命令行参数解析
来源：http://dali.cheryme.top/Article/details/gtvughhkas.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hnqzz.top/Article/details/gtswlwxmbx.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gtiblccayf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.feifeiyinyue.top/Article/details/gttmweyxhq.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtsvoesjes.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtpoyjoyzb.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtifouftca.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.pycfn.com/Article/details/gtyvuzwscu.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtdnqtebhc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yanxiufei.cn/Article/details/gtegwlrien.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuxming.cn/Article/details/gtxjyveocy.html

@contextlib.contextmanager
来源：http://dali.sxryk.cn/Article/details/gtytfyakhh.html

[U22] Py：矩阵转置
来源：http://dali.sxryk.cn/Article/details/gtaxwvagkr.html

list(zip(*m))
来源：http://dali.zhixingplan.top/Article/details/gtldwgdjdv.html

[U23] Py：分块读取大文件
来源：http://dali.gaohongyu789.top/Article/details/gtdxxyitgw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtcunwtevz.html

[U24] Py：路径操作
来源：http://dali.hammf.cn/Article/details/gtwarojeld.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258888.top/Article/details/gtpfjwxpxh.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtmozrmxgt.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtmriicjih.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtzvaqaykk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtfcaciubw.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtbgjwqrgt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pengpengdd.cyou/Article/details/gtmpisvjwi.html

[U28] Py：类型别名
来源：http://dali.yongpay.top/Article/details/gtnxtyific.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgrtfmsp.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtygjeegqu.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gtprniufmt.html

[U30] Py：数据类
来源：http://dali.ydzc1.top/Article/details/gtjgpsgbwa.html

@dataclass(slots=True)
来源：http://dali.fengsongda.top/Article/details/gtvtfkbanj.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtvtqnzhlt.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gtpzzvflth.html

[U32] Py：代码格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtzvwbtsnn.html

ruff format . && ruff check --fix .
来源：http://dali.c1oappe.top/Article/details/gtlsjveysd.html

[U33] Py：打包发布
来源：http://dali.jinqigfzy.top/Article/details/gtpzdthlrc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.0kj1m.cn/Article/details/gtvgqfylta.html

[U34] Py：判断编码
来源：http://dali.jinghuilouyu.cn/Article/details/gtnugbyasx.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gtmargzpjt.html

[U35] Py：发送邮件
来源：http://dali.jiagoushi.top/Article/details/gtjgdrobqw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gttrncvbnf.html

[U36] Py：定时任务
来源：http://dali.jlsjyb.cn/Article/details/gtobxshhig.html

schedule.every(10).minutes.do(job)
来源：http://dali.sysykeji.top/Article/details/gtbaalpmek.html

[U37] Py：读写 Excel
来源：http://dali.gaohongyu789.top/Article/details/gtbusthqkx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gtbvkyiijs.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtgyohllbq.html

Path(__file__).resolve().parent
来源：http://dali.nwbrower.top/Article/details/gttwznqrcf.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gtstkqzpog.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gtjsjkinap.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gtprhedhyt.html

print("err", file=sys.stderr)
来源：http://dali.cheryme.top/Article/details/gtutveojlk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yuanzhike.top/Article/details/gtwbpfebbb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gtmpnchfvs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ehwqpu.com/Article/details/gtixcuhouz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zycfv.cn/Article/details/gtycnpbryc.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtjfidfhse.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtwomhaaba.html

[U44] PHP：开启严格类型
来源：http://dali.xinyue.icu/Article/details/gtylfjsatq.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gththdkoih.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gtomuhochb.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtealxhwzx.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtcghitzqr.html

?string $name = null
来源：http://dali.xinyue.icu/Article/details/gtrccgdqzc.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gttgdifpwm.html

int|string $id
来源：http://dali.jlsjyb.cn/Article/details/gtnqrzqkgo.html

[U48] PHP：纯枚举
来源：http://dali.yangfankeji.com/Article/details/gtenmolbuk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.316326.xyz/Article/details/gthnwfepvi.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gtqmmirsmv.html

public readonly string $name
来源：http://dali.ybcxt.top/Article/details/gtsumgtous.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtmwolaiyp.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtmcmsrfxs.html

[U51] PHP：数组解构
来源：http://dali.mhx1999.top/Article/details/gtyornnrwk.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtuwnivqhg.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtgcacdwsb.html

$double = fn($x) => $x * 2;
来源：http://dali.daxiang520.top/Article/details/gtgnzacwlr.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtwvkyazba.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gtfdoyvrsz.html

[U54] PHP：空安全调用
来源：http://dali.yuanzhike.top/Article/details/gtqzurxbfd.html

$obj?->method()
来源：http://dali.snrcjt.cn/Article/details/gtmwsitzfr.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gthekstxkj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqtqqyhz.html

[U56] PHP：命名参数
来源：http://dali.cheryme.top/Article/details/gtnfzlvaou.html

f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtuvdsgrpf.html

[U57] PHP：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtsbozlegs.html

"值: {$a}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqocgjlax.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gtnyatahgr.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ivvv.top/Article/details/gtcjjabqtw.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gthgfamrzp.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtkjobdsag.html

[U60] PHP：JSON 编解码
来源：http://dali.daxiang520.top/Article/details/gtbkmhsatq.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sufxvd.cn/Article/details/gtqumvrlud.html

[U61] PHP：正则
来源：http://dali.tian-w.cn/Article/details/gtipqlsmei.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hywenlv.cn/Article/details/gteiidinmd.html

[U62] PHP：日期对象
来源：http://dali.guannengcc.top/Article/details/gtczzexfuf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xinyue.icu/Article/details/gtazcjtomw.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtgnceorcb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gtqwyifyem.html

[U64] PHP：目录遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumaykrxi.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gtagoxyupa.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtkpdimwqe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtwvwplbzt.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gtffzyplvj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gtbpiruqsu.html

[U67] PHP：处理文件上传
来源：http://dali.vqdsnc.cn/Article/details/gtrthuncmb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pycfn.com/Article/details/gtgavqzazk.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gtcvguywkf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtljuwvgbb.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtixjsibnp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hnqzz.top/Article/details/gtcqvuifpu.html

[U70] PHP：PDO 事务
来源：http://dali.smart0.xyz/Article/details/gttgqvsjbf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gtbqjcecbl.html

[U71] PHP：抛出异常
来源：http://dali.ybcxt.top/Article/details/gtgyzmxhwd.html

throw new RuntimeException("失败", 500);
来源：http://dali.daria6918.cn/Article/details/gttqtzsfoq.html

[U72] PHP：写错误日志
来源：http://dali.sufxvd.cn/Article/details/gtbjddhezw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhengqikj.top/Article/details/gtukiliixq.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtqjxedjjo.html

parse_ini_file("config.ini", true)
来源：http://dali.ehwqpu.com/Article/details/gtfxacycle.html

[U74] PHP：读取环境变量
来源：http://dali.c1oappe.top/Article/details/gtozavtxuy.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhongyouzk.top/Article/details/gtjyfaygwf.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtgphdjmwz.html

composer require psr/container
来源：http://dali.jlsjyb.cn/Article/details/gtxugrhgjj.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gtykuaclse.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtzxtgnqtd.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gtydlymrzx.html

composer require twig/twig
来源：http://dali.feifeiyinyue.top/Article/details/gtcmekporg.html

[U78] PHP：单元测试
来源：http://dali.svipenyu.cn/Article/details/gtnpsuzzim.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gtqsmzksup.html


<!-- 参考信息 -->