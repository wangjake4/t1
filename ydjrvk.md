代发 wailian999

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gtwbokbqjg.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtkpotpdsf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gtfvuoqqqo.html

[S50] C++：格式化数字
来源：http://dali.zdqjudy.top/Article/details/gtyjzyibjk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtyzrahcpe.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtpqphxdjk.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtsatcojfi.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtbjcftuov.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gtecvpngpr.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtbwtabsja.html

std::vector<int> w = std::move(v);
来源：http://dali.zhoulong.xyz/Article/details/gtlglfdpov.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtlphnuuho.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gotoacloud.top/Article/details/gtudtldvmr.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtvuymckot.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gttbkxebgx.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtbczbnvdp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtlzkwioux.html

[S57] C++：编译期常量
来源：http://dali.jianghu66.top/Article/details/gtgfynrcrj.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtzlqjtjxy.html

[S58] C++：命名空间
来源：http://dali.snrcjt.cn/Article/details/gthtfutfzu.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtnmwoykgi.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtpfrbroov.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtlecbxkhl.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtuujuttnz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtuekxtvew.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gteaovkoul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gthxbffina.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlwomxwkq.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gtxocbxyns.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtazwqbqnj.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtfkcnqnfl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtzyywbpon.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtokmbwarv.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtnslvdgfv.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtfibjwmka.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtueyqqtxc.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtsdwmohez.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhoulong.xyz/Article/details/gtstwkweji.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtxsrvhjuk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gtjbfhwsiw.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtcyhwpnjx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtwdigmkfb.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gtzawbbmgo.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtsbfhjwdb.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrtuycpjz.html

fun String.exclaim() = this + "!"
来源：http://dali.yanxiufei.cn/Article/details/gtfmuccvsm.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigufen.top/Article/details/gtnfebdvyl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtbezhdqfa.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtrtzlhlgr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258888.top/Article/details/gtcyxzoihh.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtpcfgvyju.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtzfypokdn.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtrxbioryp.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gtwdtjcayk.html

[T14] Kotlin：循环
来源：http://dali.vqdsnc.cn/Article/details/gthyhognjw.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtrkswgsri.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gtlaefwenm.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gtoqifbkte.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtewvibviu.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtdlnnkokr.html

[T17] Swift：变量与常量
来源：http://dali.cashguo.top/Article/details/gtddwolqse.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtlmpwgkih.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtfsloxspu.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gthsupjzmb.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtlqtbkghi.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtcxtdwylo.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtvvnrtmjw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yueranfly.top/Article/details/gtmtgvsyuh.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtwiobqqrr.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtrrsqekyb.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtrjqhbtnt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtvotiuvie.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtxshxzmox.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtqtrvbsam.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtswtgzfwg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtuwxebuiu.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gtntrkpxaj.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtyuqlrcwr.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtnotaqiea.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtzaqjjwhs.html

[T27] Swift：错误处理
来源：http://dali.zhengqikj.top/Article/details/gtgavwpehd.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gtmeytxawk.html

[T28] Swift：枚举
来源：http://dali.xuanzx.com/Article/details/gtqoompudy.html

enum Color { case red, green }
来源：http://dali.haohaochexian.top/Article/details/gtoghphuyu.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gtdsktcgqw.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gthdptiizu.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtblvqeuge.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtgwbxjpbb.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gtmgdzhgkq.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtpxathftw.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gtfpstacnu.html

local a = 1
来源：http://dali.daxiang520.top/Article/details/gtuahffhie.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtwoedaowe.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gtbklwdecc.html

[T34] Lua：遍历表
来源：http://dali.vqdsnc.cn/Article/details/gtmfthagto.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppzfzvbk.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gtrekxlpcg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gtdvdsqrub.html

[T36] Lua：函数
来源：http://dali.yuanzhike.top/Article/details/gtadofdzsk.html

function add(a, b) return a + b end
来源：http://dali.hongshengwenyu.top/Article/details/gtgqwpgzlj.html

[T37] Lua：字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtlzrggwtv.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtfpnmtdbx.html

[T38] Lua：条件
来源：http://dali.smart0.xyz/Article/details/gtwapjwvgw.html

if x > 0 then print("正") end
来源：http://dali.jqgufenzy.top/Article/details/gtkutstnzh.html

[T39] Lua：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtmmmmehtd.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtgxhdhopg.html

[T40] Lua：元表
来源：http://dali.yangfankeji.com/Article/details/gtsqqbjtmw.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtgcjccvaz.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gtwveplizl.html

print "Hello\n";
来源：http://dali.tanke756.top/Article/details/gttecusfbh.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gtnvqjchpl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigfzy.top/Article/details/gtawpwbnre.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtkqhmgfyh.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtwkrxxoqb.html

[T44] Perl：条件
来源：http://dali.yueranfly.top/Article/details/gtdbckgifu.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtjncqccaw.html

[T45] Perl：数组遍历
来源：http://dali.pycfn.com/Article/details/gtzauzfqst.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtnjohqvuw.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gthunehueq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gttdkjtuho.html

[T47] Perl：正则捕获
来源：http://dali.zhixingplan.top/Article/details/gtsbenaaop.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtxezacmew.html

[T48] Perl：正则替换
来源：http://dali.redwolf501.top/Article/details/gtgbmxqxhk.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtgrxvsgdc.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtzhgxgtlm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtugfbbdbx.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtklakyzux.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.snrcjt.cn/Article/details/gtucttzyyk.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtdfazxjmf.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtuhbxyqaa.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtxovrgoui.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtrdinbfyh.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtkwpndixc.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtgmdetwgr.html

s"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtgkfvyhlj.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtbzrruvto.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ybcxt.top/Article/details/gtccfhdpkl.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtixekzfnm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jianghu66.top/Article/details/gtmdvgxdws.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtqfuguryy.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtbxvbkqxq.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gterkdkbta.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtwhgjouhu.html

[T58] Scala：函数定义
来源：http://dali.yuxming.cn/Article/details/gtbcmdtizg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gtfyekkfsv.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtigriethb.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gtbxxjjhxm.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gtiuncwenn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtxgbofnnt.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtefdjhqdc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.smart0.xyz/Article/details/gtberpmkne.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtkecrwwag.html

[U01] Py：创建虚拟环境
来源：http://dali.xuanzx.com/Article/details/gtnrxzhtzt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtxdakeqtk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtkwuchqqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gtmzkoifhp.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gtgtyidjis.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruvnpwqj.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangtech.top/Article/details/gtebpxdifb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulxsvkdy.html

[U05] Py：列表去重且保序
来源：http://dali.zhijiandao.cn/Article/details/gtsvxqqvrg.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtcbvwaihe.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtqvbdokkd.html

{**a, **b}
来源：http://dali.zhongyouzk.top/Article/details/gthkmciblr.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtlcjmpkxx.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtxthnbkbh.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtjrhufdrc.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcyrsfvbc.html

[U09] Py：字典取最大值的键
来源：http://dali.cqqwz.cn/Article/details/gtuypisjre.html

max(d, key=d.get)
来源：http://dali.jqgfzy.top/Article/details/gtpyxnncfk.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtbiznaivs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxuanxn.top/Article/details/gtxomdbhum.html

[U11] Py：生成器表达式
来源：http://dali.yongpay.top/Article/details/gtwffdjlab.html

(x * 2 for x in arr)
来源：http://dali.snrcjt.cn/Article/details/gtubbslrwn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gteytavobc.html

Counter(arr).most_common(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkszmcdc.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtuwqfmels.html

deque(maxlen=10)
来源：http://dali.hysaishi.cn/Article/details/gtrdyjfqeg.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtzamkuyyo.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtzodkipps.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gtmgmhouje.html

t = time.perf_counter()
来源：http://dali.0kj1m.cn/Article/details/gtiuliyvot.html

[U16] Py：命令行参数解析
来源：http://dali.jqgufenzy.top/Article/details/gtwtizlscp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yuanzhike.top/Article/details/gtvmxkmvav.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtsqqchwfx.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gtwujwosvs.html

[U18] Py：预编译正则
来源：http://dali.kuanghao11.cn/Article/details/gtklboxdxt.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gtkpisczuo.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtjnnagoga.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtuncdnxsu.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtzedyrhgn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtefxeazzq.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhongyouzk.top/Article/details/gtluntximw.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gtfzfpqdfv.html

[U22] Py：矩阵转置
来源：http://dali.cqqwz.cn/Article/details/gttruaxfkr.html

list(zip(*m))
来源：http://dali.gzhubu.top/Article/details/gtavrpnjam.html

[U23] Py：分块读取大文件
来源：http://dali.iojbl.cn/Article/details/gtcvlsdwnz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yueranfly.top/Article/details/gtquqijifa.html

[U24] Py：路径操作
来源：http://dali.yj20258.top/Article/details/gtuurvtkif.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtyfxstfkc.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gtvgwccxtg.html

csv.DictReader(f)
来源：http://dali.pengpengdd.cyou/Article/details/gtvidmvdea.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtnnqbqlyx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.smart0.xyz/Article/details/gtwwedvmne.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gtglezprav.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtewckmoxn.html

[U28] Py：类型别名
来源：http://dali.chenjidiqi.icu/Article/details/gtiujkvxrr.html

UserId = int
来源：http://dali.vqdsnc.cn/Article/details/gtqcitvvdc.html

[U29] Py：属性校验
来源：http://dali.meibo888.top/Article/details/gtlsoaphhs.html

@property 与 @x.setter 配合
来源：http://dali.xuanzx.com/Article/details/gthlvkbyeo.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gttxcmvfbv.html

@dataclass(slots=True)
来源：http://dali.yueranfly.top/Article/details/gtjgarwvoi.html

[U31] Py：单测
来源：http://dali.dianchejie.cn/Article/details/gtqwtpxjap.html

python -m pytest -q
来源：http://dali.jinqigfzy.top/Article/details/gtetrgltpf.html

[U32] Py：代码格式化
来源：http://dali.daxiang520.top/Article/details/gtfjntickc.html

ruff format . && ruff check --fix .
来源：http://dali.redwolf501.top/Article/details/gtxayyfgfv.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtykwnqols.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtifmyhwot.html

[U34] Py：判断编码
来源：http://dali.hfpthk.cn/Article/details/gtztmcwsqi.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gtlvnsvyyq.html

[U35] Py：发送邮件
来源：http://dali.fengsongda.top/Article/details/gtmfyxigus.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.svipenyu.cn/Article/details/gtuqizyacj.html

[U36] Py：定时任务
来源：http://dali.vqdsnc.cn/Article/details/gtsoqdlatt.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtisghjeoy.html

[U37] Py：读写 Excel
来源：http://dali.chenlongwang.top/Article/details/gtcgayzrgt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sysykeji.top/Article/details/gtsntkwzls.html

[U38] Py：获取脚本所在目录
来源：http://dali.hywenlv.cn/Article/details/gtzomgpngm.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtkkdkaken.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuetiantiany.cn/Article/details/gtvbjveaxr.html

sys.stdout.isatty()
来源：http://dali.guowangkeji.top/Article/details/gtjcpfpawa.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gtkcppcoju.html

print("err", file=sys.stderr)
来源：http://dali.cqqwz.cn/Article/details/gtgmywqrfp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.bjfxy.top/Article/details/gtkjbpnocs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.birdmap.top/Article/details/gtpoxxcbdn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinghuilouyu.cn/Article/details/gtpuughfgn.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jinqigfzy.top/Article/details/gtythraawc.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gtmvszvfei.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gttlcsbeqt.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtneveadai.html

declare(strict_types=1);
来源：http://dali.316326.xyz/Article/details/gtxnhfsrrm.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsppugjwm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtlejpdxbh.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtjsrbhkvp.html

?string $name = null
来源：http://dali.jiagoushi.top/Article/details/gtdkoorhtd.html

[U47] PHP：联合类型
来源：http://dali.havefunace.top/Article/details/gtghjerfbv.html

int|string $id
来源：http://dali.9152youxi.cn/Article/details/gtmzygdycc.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gtsaoaqznd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.c1oappe.top/Article/details/gtwwawtejj.html

[U49] PHP：只读属性
来源：http://dali.havefunace.top/Article/details/gtqhuvetzy.html

public readonly string $name
来源：http://dali.chenzaomai.com/Article/details/gtyngszbai.html

[U50] PHP：构造器属性提升
来源：http://dali.jqgufenzy.top/Article/details/gtffkkxrwg.html

public function __construct(private int $id) {}
来源：http://dali.cucudq.cn/Article/details/gtmlvjxhpx.html

[U51] PHP：数组解构
来源：http://dali.kuanghao11.cn/Article/details/gtnzddzwdz.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gtfztsjxrf.html

[U52] PHP：箭头函数
来源：http://dali.cashguo.top/Article/details/gtpebxjhwd.html

$double = fn($x) => $x * 2;
来源：http://dali.gotoacloud.top/Article/details/gtbnthxgvx.html

[U53] PHP：空合并运算符
来源：http://dali.haohaochexian.top/Article/details/gtokqjjenn.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gtcmqsclam.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtflokjzsk.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gtszsjupfd.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtqunatunq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.aizwys.cn/Article/details/gtotywyphu.html

[U56] PHP：命名参数
来源：http://dali.xinyue.icu/Article/details/gtqsvtuiop.html

f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtyqgpwcdw.html

[U57] PHP：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gtofcaevyo.html

"值: {$a}"
来源：http://dali.zhijiandao.cn/Article/details/gthteawxkm.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtornuvmfk.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtbvgkgwxv.html

[U59] PHP：自定义排序
来源：http://dali.snrcjt.cn/Article/details/gtmxehlmpk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.wangdashe.top/Article/details/gtpchcoilz.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtffopcfwb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvnpxnbo.html

[U61] PHP：正则
来源：http://dali.shangyingyoupin.top/Article/details/gtctexpgti.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhijiandao.cn/Article/details/gtyuaaiuvs.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gttxwyiiga.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.cdnleiting.top/Article/details/gtveocywnq.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtxhkmxeuq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gtscxnqefb.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gtjkvrtgbz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gtlticfeiv.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtgpctqket.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtvzyhehkg.html

[U66] PHP：设置 Cookie
来源：http://dali.zhongyouzk.top/Article/details/gtivukpawo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tianlin.xyz/Article/details/gttqtipkzj.html

[U67] PHP：处理文件上传
来源：http://dali.kuanghao11.cn/Article/details/gtskdtnnxe.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gtzgvadjep.html

[U68] PHP：PDO 连接
来源：http://dali.gotoacloud.top/Article/details/gtcxvyhnfr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jqgfzy.top/Article/details/gtooczsyxs.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gtriadxmhc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gotoacloud.top/Article/details/gttxjxvmkh.html

[U70] PHP：PDO 事务
来源：http://dali.xuetiantiany.cn/Article/details/gtwdmwjqns.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.xuanzx.com/Article/details/gtklasjylo.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gtozjxxumg.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxsgasbal.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gtzdcpbttj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sufxvd.cn/Article/details/gthxjwvdsx.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gtjpcskyyy.html

parse_ini_file("config.ini", true)
来源：http://dali.9152youxi.cn/Article/details/gtiprorrgp.html

[U74] PHP：读取环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtbdvnnemu.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjowpvits.html


<!-- 参考信息 -->