代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtkiclknyb.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmrhoooe.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtqbzeupuh.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtqsdgigfz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gttyrhljvi.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtjbfiduto.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ybcxt.top/Article/details/gtxtqzwyyx.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gtcyalqgie.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtfjkdpvvp.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gtknjvsttq.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtboinlgia.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtdksenkuj.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtiamvvciu.html

[S59] C++：静态断言
来源：http://dali.chenjidiqi.icu/Article/details/gtxrnualge.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gttuofowyg.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtronavggx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yonumen.top/Article/details/gtoowyzjfp.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtjpjunrtq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gtijqpkuft.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtswnmvads.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtfpgujwtx.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtnogzaxsy.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gttwvwzene.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.daxiang520.top/Article/details/gtkosnpjxn.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtlqhpkwvc.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtlbjropjh.html

[T04] Kotlin：空安全
来源：http://dali.xylfe.cn/Article/details/gtvihemhhb.html

val n: String? = null;  n?.length
来源：http://dali.sxryk.cn/Article/details/gtonziwvxd.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtilsirnzd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtcaoppzxj.html

[T06] Kotlin：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gtkguzrtgv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtnxbqnxzj.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtbgvqpm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtdkomvwxy.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtfxabihwg.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtxrigpben.html

[T09] Kotlin：扩展函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtinfxjjih.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtcmnyngnp.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcmqqbyju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtlyhxzxkm.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtdxipkayn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtukjouuuz.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwapscpgz.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtobhyyugs.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gtpumnaezk.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtbgmrzhdp.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtzpwlolch.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtyehrnqzl.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtrerqadgz.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtjrmzdvpd.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxitohedd.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtgjlzptgz.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtxkmtjajk.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtowccmegs.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gttizeekoo.html

"值: \(b)"
来源：http://dali.iojbl.cn/Article/details/gtfetjfgsv.html

[T19] Swift：可选绑定
来源：http://dali.zhixingplan.top/Article/details/gtigjrjshb.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gthajwndll.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gtzwdhdgwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtxwwmvjwe.html

[T21] Swift：遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtsmcesivo.html

for x in a { print(x) }
来源：http://dali.wangshuangyany.cn/Article/details/gtbtsbpexo.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtmtxrkufp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtkabfqapp.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtkrzeqdvh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gtzsualcbs.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gttbliyyag.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.feifeiyinyue.top/Article/details/gtijezdsrb.html

[T25] Swift：结构体
来源：http://dali.9152youxi.cn/Article/details/gtwhhjhbvj.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtxtumioff.html

[T26] Swift：类与重写
来源：http://dali.c1oappe.top/Article/details/gtuskthzym.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtobbtrkwf.html

[T27] Swift：错误处理
来源：http://dali.guannengcc.top/Article/details/gtyivlyeve.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gtxvoovedw.html

[T28] Swift：枚举
来源：http://dali.yj20258888.top/Article/details/gtcyyaaqrk.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gttwkjxajk.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtwhaofymt.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gtauipsbft.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtpivskzcq.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gtkiulcpmy.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtsnqfcilc.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gtzqaqliuy.html

[T32] Lua：局部变量
来源：http://dali.zhijiandao.cn/Article/details/gtmsblinmw.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtjduxsegh.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtofgnejcq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtrgcrdqvi.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtbshwmmfx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtzvqqvlkd.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtxgdmvhoj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gtaupheusn.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtuxnxahrf.html

function add(a, b) return a + b end
来源：http://dali.gotoacloud.top/Article/details/gtlbiksayg.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtcajycasj.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtkuryjifw.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gtoczzwqyg.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtpvqzacsv.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtbfjyrfii.html

string.find(s, "%d+")
来源：http://dali.gzhubu.top/Article/details/gtmilgfkcn.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gtqwwqqbia.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gtzzltoynf.html

[T41] Perl：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttnvbxotj.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtlgbgicrh.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtneaqtena.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yongpay.top/Article/details/gtzijknigo.html

[T43] Perl：字符串插值
来源：http://dali.yueranfly.top/Article/details/gtayynlxnn.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtmvvtdwgz.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtutuevany.html

if ($a > 0) { print "正"; }
来源：http://dali.sufxvd.cn/Article/details/gtmmjbkwod.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gttdrkisfy.html

for my $x (@arr) { print $x; }
来源：http://dali.sufxvd.cn/Article/details/gtqxxdfsrp.html

[T46] Perl：哈希操作
来源：http://dali.zhijiandao.cn/Article/details/gtrkesyrgx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tian-w.cn/Article/details/gtbyylsxky.html

[T47] Perl：正则捕获
来源：http://dali.ppjwa.cn/Article/details/gttklptjci.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtmryqxlhc.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtsdimwbpj.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtzqcipfzo.html

[T49] Perl：函数
来源：http://dali.mhx1999.top/Article/details/gtkkzwpcse.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gttjdbxodp.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtgpyvhvif.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ivvv.top/Article/details/gtlvhdbdua.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuxming.cn/Article/details/gtflrpyuom.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gthahplims.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gttlbzdwlk.html

[T52] Scala：变量
来源：http://dali.kuanghao11.cn/Article/details/gtrrzoljub.html

val a = 1;  var b = 2
来源：http://dali.zhengqikj.top/Article/details/gtrtrwhcoi.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtuxbvhpil.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtfyhtepen.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtlamyaabq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtdnbghvsj.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtnfurdmny.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtrwzwctoc.html

[T56] Scala：样例类
来源：http://dali.haohaochexian.top/Article/details/gtkzqoqsvm.html

case class User(name: String, age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtsitvcrsd.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtxxqoxruh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtdatspkfn.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtnkrqpbin.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtrwukwavj.html

[T59] Scala：循环
来源：http://dali.ybcxt.top/Article/details/gtznnzzjqw.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtllrtvxkj.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtheqhdchh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gthkylhwsf.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtebwvwyqd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtvdsbwgfl.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtpjhxkunx.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtoyrjikyl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gtxglsazzr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtcjnmfbur.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeiannsm.html

[U03] Py：加载 .env 配置
来源：http://dali.tanke756.top/Article/details/gtqmdydpwy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangtech.top/Article/details/gtyerglltp.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gtbsfscrso.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdugmcngu.html

[U05] Py：列表去重且保序
来源：http://dali.shuidangran.top/Article/details/gtbyajebfh.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtxvjczyck.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtbxenicyt.html

{**a, **b}
来源：http://dali.ehwqpu.com/Article/details/gtwzptrrtt.html

[U07] Py：反转字典键值
来源：http://dali.yuanzhike.top/Article/details/gtzwquocet.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtemtzllxl.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gtkvigpdiv.html

[y for x in nested for y in x]
来源：http://dali.aizwys.cn/Article/details/gtujoiamyq.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gttbkciufy.html

max(d, key=d.get)
来源：http://dali.wangdashe.top/Article/details/gtikjyurvu.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtczrfmaps.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gthifzerjb.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtniqheouq.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemtwvvhh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.cdnleiting.top/Article/details/gttfjivnwg.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtztbxykve.html

[U13] Py：固定长度队列
来源：http://dali.0kj1m.cn/Article/details/gtydcjdadg.html

deque(maxlen=10)
来源：http://dali.sysykeji.top/Article/details/gtgcnizixu.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtxjipoyum.html

defaultdict(list)
来源：http://dali.zdqjudy.top/Article/details/gtxauzjmdf.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gthcirwgkw.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtgqgqrozt.html

[U16] Py：命令行参数解析
来源：http://dali.snrcjt.cn/Article/details/gttaqqhzvl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtxumqsgbs.html

[U17] Py：初始化日志
来源：http://dali.hywenlv.cn/Article/details/gtrydyrglt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtmtqwnxyq.html

[U18] Py：预编译正则
来源：http://dali.yangfankeji.com/Article/details/gtfcltulqe.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtetwgyuod.html

[U19] Py：正则替换带回调
来源：http://dali.jqgufenzy.top/Article/details/gtstgvpyjt.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.kuanghao11.cn/Article/details/gtwlgqxran.html

[U20] Py：缓存函数结果
来源：http://dali.sufxvd.cn/Article/details/gtvjawqajc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hongshengwenyu.top/Article/details/gtdtozamqd.html

[U21] Py：自定义上下文管理器
来源：http://dali.guannengcc.top/Article/details/gtpqlbernn.html

@contextlib.contextmanager
来源：http://dali.xziqi.cn/Article/details/gtaggupyfb.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtoxiizpxt.html

list(zip(*m))
来源：http://dali.kuanghao11.cn/Article/details/gttnxljdlx.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtllbmzfyf.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tanke756.top/Article/details/gtwrwwigsd.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gtdjqcqgmi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gtuqckbmwm.html

[U25] Py：CSV 按字典读
来源：http://dali.aizwys.cn/Article/details/gtrajfrkdy.html

csv.DictReader(f)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnozgaji.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gtnvjyfqqv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.snrcjt.cn/Article/details/gtntiqfhft.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtwceqdqwn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jyoumei.cn/Article/details/gtflsaizfq.html

[U28] Py：类型别名
来源：http://dali.yuanzhike.top/Article/details/gtdtpwaizq.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtlppnmyxs.html

[U29] Py：属性校验
来源：http://dali.kuanghao11.cn/Article/details/gtsxoftqng.html

@property 与 @x.setter 配合
来源：http://dali.shanyushiyangtech.top/Article/details/gtffhixtxu.html

[U30] Py：数据类
来源：http://dali.cqqwz.cn/Article/details/gtabdawezt.html

@dataclass(slots=True)
来源：http://dali.jinqigufen.top/Article/details/gtptrmfoaf.html

[U31] Py：单测
来源：http://dali.snrcjt.cn/Article/details/gtciksyvzo.html

python -m pytest -q
来源：http://dali.wangdashe.top/Article/details/gtgeaqbova.html

[U32] Py：代码格式化
来源：http://dali.yonumen.top/Article/details/gtigqgqgsf.html

ruff format . && ruff check --fix .
来源：http://dali.ivvv.top/Article/details/gtcwelyeog.html

[U33] Py：打包发布
来源：http://dali.guannengcc.top/Article/details/gtopuswbwi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xziqi.cn/Article/details/gtuolxdcip.html

[U34] Py：判断编码
来源：http://dali.tanke756.top/Article/details/gthizwdkbm.html

chardet.detect(raw)
来源：http://dali.sysykeji.top/Article/details/gtzrmeyyyo.html

[U35] Py：发送邮件
来源：http://dali.zdqjudy.top/Article/details/gtmtyczjpq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhoulong.xyz/Article/details/gttrppvivb.html

[U36] Py：定时任务
来源：http://dali.dianchejie.cn/Article/details/gtdiouooct.html

schedule.every(10).minutes.do(job)
来源：http://dali.hammf.cn/Article/details/gtmcktifyn.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gtmreqdoik.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gteezxftgx.html

[U38] Py：获取脚本所在目录
来源：http://dali.cheryme.top/Article/details/gtnzbpceth.html

Path(__file__).resolve().parent
来源：http://dali.hnqzz.top/Article/details/gthtvepevj.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtzhurrqxb.html

sys.stdout.isatty()
来源：http://dali.mhx1999.top/Article/details/gterqnqdmg.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtfxfxunrt.html

print("err", file=sys.stderr)
来源：http://dali.wangshuangyany.cn/Article/details/gtrmumwwkx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.birdmap.top/Article/details/gtsymtcsop.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.kuanghao11.cn/Article/details/gtgzsnaxnh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gtumwcqcof.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgufenzy.top/Article/details/gtyfyxlqpc.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gtrcgkrrfm.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gtpyzygoae.html

[U44] PHP：开启严格类型
来源：http://dali.yueranfly.top/Article/details/gtbfmlhtvb.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gtljsqdfdr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gtwwdnwnub.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gttkeoxffr.html

[U46] PHP：可空类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlesyruk.html

?string $name = null
来源：http://dali.zhengqikj.top/Article/details/gtwidpclwx.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtslwiiutm.html

int|string $id
来源：http://dali.gogol.net.cn/Article/details/gtpmlralcn.html

[U48] PHP：纯枚举
来源：http://dali.xinyue.icu/Article/details/gthaljatoq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtvyrqklwh.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gtuiyjnvxn.html

public readonly string $name
来源：http://dali.svipenyu.cn/Article/details/gtztnwisdv.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjuuavvmo.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gtodxmvqnd.html

[U51] PHP：数组解构
来源：http://dali.hfpthk.cn/Article/details/gtexykxklb.html

[$a, $b] = $arr;
来源：http://dali.9152youxi.cn/Article/details/gthgdgvzaa.html

[U52] PHP：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtyhikwdrk.html

$double = fn($x) => $x * 2;
来源：http://dali.havefunace.top/Article/details/gteiedafbw.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtvtsbffha.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhijiandao.cn/Article/details/gtlcfyzsko.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gtaubwnnww.html

$obj?->method()
来源：http://dali.yueranfly.top/Article/details/gtqdcqxhpo.html

[U55] PHP：match 表达式
来源：http://dali.iojbl.cn/Article/details/gtrbycmnvb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gtnholzbqw.html

[U56] PHP：命名参数
来源：http://dali.bjfxy.top/Article/details/gtexbmuwud.html

f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtsmjgevqo.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtrwgowmcl.html

"值: {$a}"
来源：http://dali.cucudq.cn/Article/details/gtddxruaff.html

[U58] PHP：数组三件套
来源：http://dali.zdqjudy.top/Article/details/gtapncsmet.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shangyingyoupin.top/Article/details/gtlohmialn.html

[U59] PHP：自定义排序
来源：http://dali.ppjwa.cn/Article/details/gtmhgljefb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.redwolf501.top/Article/details/gtfyiifchg.html

[U60] PHP：JSON 编解码
来源：http://dali.zycfv.cn/Article/details/gtlltiurbv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yueranfly.top/Article/details/gtredpakns.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtcodhjeht.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtcelaqktx.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtyifuauwu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtarnogcom.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtdoyasyyu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhengqikj.top/Article/details/gtysbrmrvm.html

[U64] PHP：目录遍历
来源：http://dali.cqqwz.cn/Article/details/gtwiaxmxlv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijyhelru.html

[U65] PHP：会话
来源：http://dali.9152youxi.cn/Article/details/gtelsqambt.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gthmmtvlle.html

[U66] PHP：设置 Cookie
来源：http://dali.xziqi.cn/Article/details/gtjfjsetul.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtvtlzgmvb.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gtjoxgoifn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jiagoushi.top/Article/details/gtmlzvuyfj.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gtumvadeyb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtezgvblsg.html

[U69] PHP：PDO 预处理
来源：http://dali.ivvv.top/Article/details/gtatpoetzt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj202588.top/Article/details/gtahjibbjt.html

[U70] PHP：PDO 事务
来源：http://dali.chenlongwang.top/Article/details/gtxrqzjzbk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.guowangkeji.top/Article/details/gtjabeusfs.html

[U71] PHP：抛出异常
来源：http://dali.kuanghao11.cn/Article/details/gtimkpsiql.html

throw new RuntimeException("失败", 500);
来源：http://dali.hysaishi.cn/Article/details/gtedldcvhw.html

[U72] PHP：写错误日志
来源：http://dali.c1oappe.top/Article/details/gtgnhdqpfb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtuikkakbr.html

[U73] PHP：读取 ini 配置
来源：http://dali.jlsjyb.cn/Article/details/gtbxdptggy.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gthivkwwdp.html

[U74] PHP：读取环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtatiobwls.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hnqzz.top/Article/details/gtglwtqcgc.html

[U75] PHP：依赖注入
来源：http://dali.hammf.cn/Article/details/gtiezotpwt.html

composer require psr/container
来源：http://dali.dashuyun.cn/Article/details/gtwjnnkpjj.html

[U76] PHP：简单路由
来源：http://dali.guannengcc.top/Article/details/gtglgduoce.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shuidangran.top/Article/details/gtdviheqji.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gttbwtihzr.html

composer require twig/twig
来源：http://dali.nwbrower.top/Article/details/gthoxexhkk.html

[U78] PHP：单元测试
来源：http://dali.yj20258888.top/Article/details/gtntslqsvs.html

composer require --dev phpunit/phpunit
来源：http://dali.wangdashe.top/Article/details/gttlspzhet.html


<!-- 参考信息 -->