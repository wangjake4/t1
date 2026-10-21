代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtyxpuyuep.html

[S53] C++：移动语义
来源：http://dali.hnxiangtu.top/Article/details/gtgsbcklde.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtaujitgpe.html

[S54] C++：异常处理
来源：http://dali.gaohongyu789.top/Article/details/gtgavmamex.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtlapthzzu.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtxnqivxae.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtrxmoinsa.html

[S56] C++：optional
来源：http://dali.zdqjudy.top/Article/details/gtmqvnodiv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhiwuduotai.top/Article/details/gtjadynmdd.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtqrcrpodt.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtfgfeotyj.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtegrzygeb.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtljtlwiml.html

[S59] C++：静态断言
来源：http://dali.jinqigufen.top/Article/details/gtoazspezl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteymhmrrt.html

[S60] C++：遍历并删除元素
来源：http://dali.yuanzhike.top/Article/details/gtducvsbir.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtxvebgdql.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtinzqbwrl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pengpengdd.cyou/Article/details/gtboertxhy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtvozagdox.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtgdndjeda.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtogaljptr.html

[T02] Kotlin：变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtdyvovxmy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gtgdbrmeag.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gtiaggfkvn.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtukrxfhek.html

[T04] Kotlin：空安全
来源：http://dali.c1oappe.top/Article/details/gtzlkyfvuc.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gtaaukqdti.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtnifoeeja.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.mhx1999.top/Article/details/gtqijchqmp.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtzcxwpwab.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtgpacfdql.html

[T07] Kotlin：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtqljpvcwh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aizwys.cn/Article/details/gtxsatlxob.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtmzshkril.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxuanxn.top/Article/details/gtwgattuxb.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258888.top/Article/details/gtntkwyclx.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqzadudlh.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtfjcaekzg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtacewyaew.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmrheicid.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtnsbfstsh.html

[T12] Kotlin：解构声明
来源：http://dali.mhx1999.top/Article/details/gtwsafpeah.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtjrmiynip.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtsozialaz.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gtjhikkmhp.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtboyiksws.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gttwgmrpfy.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtmhzgvgqf.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtyvaawnyu.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtqdnhazoq.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtwcpfnrul.html

[T17] Swift：变量与常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwpqxqpoe.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtwwzjbrum.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtudevxaqo.html

"值: \(b)"
来源：http://dali.yj202588.top/Article/details/gtqqhmjiwz.html

[T19] Swift：可选绑定
来源：http://dali.hnxiangtu.top/Article/details/gtpsoajlue.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gteheqfeuz.html

[T20] Swift：数组操作
来源：http://dali.zdqjudy.top/Article/details/gtfbjjjkts.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daxiang520.top/Article/details/gttqucxbnk.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtdhkcnmka.html

for x in a { print(x) }
来源：http://dali.cheryme.top/Article/details/gtcksfgkqt.html

[T22] Swift：字典
来源：http://dali.haohaochexian.top/Article/details/gtqkdsqjlk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyahhuqjd.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtwwdbuuaz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258888.top/Article/details/gtfaphquiu.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtvbdfmtxm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtiqznymkg.html

[T25] Swift：结构体
来源：http://dali.yuxming.cn/Article/details/gtblnnzwlh.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtifzaagma.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtuyrcfcgw.html

class A: Base { override func f() {} }
来源：http://dali.birdmap.top/Article/details/gtqdrpgujk.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtfnzheugc.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigfzy.top/Article/details/gtualigtar.html

[T28] Swift：枚举
来源：http://dali.dianchejie.cn/Article/details/gtgxhgpitk.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtbytwvfny.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtywgqeajk.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtoizpptoz.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gtpoxfobsg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhixingplan.top/Article/details/gtjjokzsng.html

[T31] Lua：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtthqznpbo.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtlsvgfumx.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtmucukrjm.html

local a = 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxxxmphq.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gtacaiwqvv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtxxbtkyig.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtbdrqrwzr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gtukbpdkpw.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gtzshiqlkx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pengpengdd.cyou/Article/details/gttpqywrof.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtencnapil.html

function add(a, b) return a + b end
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtpkqryg.html

[T37] Lua：字符串拼接
来源：http://dali.sufxvd.cn/Article/details/gtwokinaiv.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtqdlgxdat.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtgbxjpjpm.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxvfasdw.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjosxzaoa.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtuftjipyy.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gtdyzsvlyi.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gthdzudktv.html

[T41] Perl：Hello World
来源：http://dali.zycfv.cn/Article/details/gtygjkfaui.html

print "Hello\n";
来源：http://dali.cdnleiting.top/Article/details/gtbxaspzvo.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtmcpnqtzg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtaojqttte.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtwslqvpjs.html

"值: $a"
来源：http://dali.zhijiandao.cn/Article/details/gtcicbvenr.html

[T44] Perl：条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhshcsbz.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gtibzpyvyo.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gtvdotemse.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gttoipvnwr.html

[T46] Perl：哈希操作
来源：http://dali.hammf.cn/Article/details/gtfxbjohua.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daxiang520.top/Article/details/gtzqzdukoz.html

[T47] Perl：正则捕获
来源：http://dali.yj20258.top/Article/details/gtsnhlycbt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtvlcexyaf.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtcrsygucj.html

$s =~ s/old/new/g;
来源：http://dali.yj20258.top/Article/details/gtztzuxnik.html

[T49] Perl：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllnoxyon.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtkndlbjym.html

[T50] Perl：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtrwhinmhg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gtkgcvogek.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gtydjbaxhk.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gtrbhmjyva.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtofxxhkcw.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtvhszdyqr.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gthghqopfv.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijdewmto.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtclmzkzoc.html

[T54] Scala：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtmckdzpjg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pycfn.com/Article/details/gtrfpeyjpj.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gttzswhinw.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gtaqbgmmyf.html

[T56] Scala：样例类
来源：http://dali.xziqi.cn/Article/details/gtngbmkwzj.html

case class User(name: String, age: Int)
来源：http://dali.svipenyu.cn/Article/details/gtecmkuurf.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gtccfxbwsk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtqafuqize.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gtzhfylfez.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhoulong.xyz/Article/details/gtlixgfjmt.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gtnldlbrvt.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtmjxzwtav.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtjeddlmmb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtmbwlghvf.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtgmalnonl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtzqdatcdi.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtujqylstq.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtknnjvttt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgufenzy.top/Article/details/gtwkluucwt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtkrsgtxbx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.vqdsnc.cn/Article/details/gtxuhwxokz.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtllzzcvoi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangshuangyany.cn/Article/details/gtdmfjutsb.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtsphunjoe.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmfmhgunr.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gthrpcwlem.html

list(dict.fromkeys(arr))
来源：http://dali.hammf.cn/Article/details/gttfvcypjs.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtfzvgfjvj.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtkfzyilgm.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpgfdmeeb.html

{v: k for k, v in d.items()}
来源：http://dali.sufxvd.cn/Article/details/gtrpduyuri.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtehqppiwy.html

[y for x in nested for y in x]
来源：http://dali.hammf.cn/Article/details/gttmuorhsa.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtnfhkytjv.html

max(d, key=d.get)
来源：http://dali.hysaishi.cn/Article/details/gtcsoyttbq.html

[U10] Py：按值排序字典
来源：http://dali.yj20258.top/Article/details/gtpqrtwdrm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sysykeji.top/Article/details/gtljgbmlea.html

[U11] Py：生成器表达式
来源：http://dali.yanxiufei.cn/Article/details/gtxhelsykz.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtugzgitom.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtmcrfeigm.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtlxmfjbtq.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gtnftmrakf.html

deque(maxlen=10)
来源：http://dali.tian-w.cn/Article/details/gtabjalxhh.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtiixsplfz.html

defaultdict(list)
来源：http://dali.ybcxt.top/Article/details/gtqlagyxho.html

[U15] Py：高精度计时
来源：http://dali.yueranfly.top/Article/details/gtnnroikcg.html

t = time.perf_counter()
来源：http://dali.zhiwuduotai.top/Article/details/gtlmtpgzoa.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gtjyzwnglo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.quarkkingdee.top/Article/details/gtittyyrwm.html

[U17] Py：初始化日志
来源：http://dali.xuanzx.com/Article/details/gtcviscowg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.dianchejie.cn/Article/details/gthtvmrudz.html

[U18] Py：预编译正则
来源：http://dali.zhengqikj.top/Article/details/gtgdvrvcsm.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtlaonzlpw.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gtebjjsezv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yangfankeji.com/Article/details/gtrnnauqql.html

[U20] Py：缓存函数结果
来源：http://dali.sweek.top/Article/details/gtedztmimg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgfzy.top/Article/details/gtinvtcinx.html

[U21] Py：自定义上下文管理器
来源：http://dali.yuanzhike.top/Article/details/gtaljylnor.html

@contextlib.contextmanager
来源：http://dali.chenjidiqi.icu/Article/details/gtufmksbhx.html

[U22] Py：矩阵转置
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfdcisgxu.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gttpjqtuoy.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtoglwxksc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gtrsjvmvth.html

[U24] Py：路径操作
来源：http://dali.yj202588.top/Article/details/gtbkzkxmfr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtshosdrnx.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gtvatyvysh.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtqnwjnzmu.html

[U26] Py：并发下载
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanjstnbg.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hammf.cn/Article/details/gtqarypdka.html

[U27] Py：异步 HTTP
来源：http://dali.jinqigfzy.top/Article/details/gtxmhfxvbe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gtfrbvdrom.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtqsdqwxts.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gthawizkzd.html

[U29] Py：属性校验
来源：http://dali.yanxiufei.cn/Article/details/gtrpfypmlh.html

@property 与 @x.setter 配合
来源：http://dali.aibaodan.cn/Article/details/gtizepjrlg.html

[U30] Py：数据类
来源：http://dali.xuetiantiany.cn/Article/details/gtmdknxzjt.html

@dataclass(slots=True)
来源：http://dali.kuanghao11.cn/Article/details/gtzefxnhlk.html

[U31] Py：单测
来源：http://dali.hywenlv.cn/Article/details/gtbtrngoel.html

python -m pytest -q
来源：http://dali.dashuyun.cn/Article/details/gtlxmijbsz.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtmimveeop.html

ruff format . && ruff check --fix .
来源：http://dali.hfpthk.cn/Article/details/gtfbrfbyuq.html

[U33] Py：打包发布
来源：http://dali.sufxvd.cn/Article/details/gtyjfzkbvc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gtqqzdirsh.html

[U34] Py：判断编码
来源：http://dali.nwbrower.top/Article/details/gtwqydysou.html

chardet.detect(raw)
来源：http://dali.jinghuilouyu.cn/Article/details/gterttgmvm.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gtnpqclyhk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cdnleiting.top/Article/details/gtqospkxos.html

[U36] Py：定时任务
来源：http://dali.hfpthk.cn/Article/details/gtxhmjjnsz.html

schedule.every(10).minutes.do(job)
来源：http://dali.yanxiufei.cn/Article/details/gtuhuzfcuh.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtumrjvqgi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.quarkkingdee.top/Article/details/gtyetmevid.html

[U38] Py：获取脚本所在目录
来源：http://dali.tianlin.xyz/Article/details/gtwrtvkpof.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gthoiwxqcz.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtqfquxpyy.html

sys.stdout.isatty()
来源：http://dali.fzhhl.top/Article/details/gtlgbvrkgw.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtypanoerg.html

print("err", file=sys.stderr)
来源：http://dali.andypj.xyz/Article/details/gtboqzhrsy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtykdjzvgt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.bjfxy.top/Article/details/gtvqxmrzcr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.andypj.xyz/Article/details/gtyrhqjbsc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.fzhhl.top/Article/details/gtirgtcgqz.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gtjlnyunym.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gtgqzuylpn.html

[U44] PHP：开启严格类型
来源：http://dali.redwolf501.top/Article/details/gtxpjexvmj.html

declare(strict_types=1);
来源：http://dali.jinqigfzy.top/Article/details/gtoqhpsqam.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtwvnqreon.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtyauowugg.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtgzebilll.html

?string $name = null
来源：http://dali.dashuyun.cn/Article/details/gtekwbxwjf.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gtvykeyudb.html

int|string $id
来源：http://dali.yj20258.top/Article/details/gtcoqwlgzw.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwcqjwyba.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyxeesoiw.html

[U49] PHP：只读属性
来源：http://dali.yueranfly.top/Article/details/gteomobpfz.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtlonuykqe.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gtuvcvhktj.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gtiywfvhyn.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gtvxbefzfg.html

[$a, $b] = $arr;
来源：http://dali.chenzaomai.com/Article/details/gtgfgmqjon.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkcjcrli.html

$double = fn($x) => $x * 2;
来源：http://dali.ppjwa.cn/Article/details/gtiubpsosq.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtvcdowmmu.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyxucpvvu.html

[U54] PHP：空安全调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjhxeaas.html

$obj?->method()
来源：http://dali.birdmap.top/Article/details/gtlnbddilc.html

[U55] PHP：match 表达式
来源：http://dali.zycfv.cn/Article/details/gtsgwfmnlz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtsbmidkee.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gtmuyubrqs.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtlsgqxinx.html

[U57] PHP：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtiqkrsqof.html

"值: {$a}"
来源：http://dali.jinqigfzy.top/Article/details/gtllohfmft.html

[U58] PHP：数组三件套
来源：http://dali.gzhubu.top/Article/details/gtoqjqwmuf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sysykeji.top/Article/details/gtprgywiep.html

[U59] PHP：自定义排序
来源：http://dali.cdnleiting.top/Article/details/gtygajixqb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.vqdsnc.cn/Article/details/gtnxuojkol.html

[U60] PHP：JSON 编解码
来源：http://dali.wangdashe.top/Article/details/gtqwflelji.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.pycfn.com/Article/details/gtkdikjwmn.html

[U61] PHP：正则
来源：http://dali.hammf.cn/Article/details/gtpyakogdf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkulyczch.html

[U62] PHP：日期对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtorswuupz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangshuangyany.cn/Article/details/gtqfhtldwo.html

[U63] PHP：文件读写
来源：http://dali.xuetiantiany.cn/Article/details/gtcmcineqa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gtaufuowzz.html

[U64] PHP：目录遍历
来源：http://dali.ybcxt.top/Article/details/gtsplwsqjj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daxiang520.top/Article/details/gtjymefmwo.html

[U65] PHP：会话
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwffkprze.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtpyzlxvum.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gtkyjbdqvt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.haohaochexian.top/Article/details/gtwmertdiw.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gtggkeuyxh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtpphiqhsf.html

[U68] PHP：PDO 连接
来源：http://dali.hysaishi.cn/Article/details/gtyxcjekss.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gtcoeiilrr.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gtjrtxxpxr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.havefunace.top/Article/details/gtrcgwptdd.html

[U70] PHP：PDO 事务
来源：http://dali.hysaishi.cn/Article/details/gtpuvrsvsv.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtuosgsfqo.html

[U71] PHP：抛出异常
来源：http://dali.yueranfly.top/Article/details/gtinaqskrk.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvnisgprd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtoybtuimf.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yj20258.top/Article/details/gthffzoied.html

[U73] PHP：读取 ini 配置
来源：http://dali.sufxvd.cn/Article/details/gtyqgqjzog.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gturcoljug.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gtpqivtmqg.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cheryme.top/Article/details/gtinffyymq.html

[U75] PHP：依赖注入
来源：http://dali.hfpthk.cn/Article/details/gtqnbdyhng.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gtgcuupvxa.html

[U76] PHP：简单路由
来源：http://dali.snrcjt.cn/Article/details/gtieryykzi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gtrwfdsvza.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtmjxklwbo.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtlcafycmt.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtgfrjeizj.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gtytrwezqs.html


<!-- 参考信息 -->