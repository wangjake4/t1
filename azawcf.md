代发 wailian999

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2jhgedjqi.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gt2ypmbsodi.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2vvmkuclq.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2xeeevjse.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj202588.top/Article/details/gt2mlvxwunr.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gt2pfykhymi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2thtemdsg.html

[S56] C++：optional
来源：http://dali.chenjidiqi.icu/Article/details/gt2qaexsbze.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gt2jvvvswyz.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2oavrcjrs.html

constexpr int N = 10;
来源：http://dali.daria6918.cn/Article/details/gt2orfchwnm.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2bliurhxg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mcytpqht.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2fdviovto.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gt2futtmkss.html

[S60] C++：遍历并删除元素
来源：http://dali.ehwqpu.com/Article/details/gt2efkvmfhn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gt2jqvjxovb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2vmfjuiec.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2lzcseeel.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2hnnabrhy.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2hwvqagds.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2cacolzsv.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2ijknhuuc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gt2hmtjuopi.html

[T03] Kotlin：字符串模板
来源：http://dali.9152youxi.cn/Article/details/gt2rhbkrdsn.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gt2ctcivdqy.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gt2rgcqykky.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2erlibgyx.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2mztftpbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gt2pxcodmfr.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2vwunyzmg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2txyqgdts.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gt2swntdqqf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xbhnabaf.html

[T08] Kotlin：数据类
来源：http://dali.smart0.xyz/Article/details/gt2imdtdmts.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gt2pfkhheoi.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ifppuycq.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gt2tigjovld.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2guhifebq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gt2ykakrzag.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gt2jhkkgnex.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yopdsziz.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gt2aqzaizpt.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2relybvbb.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gt2klmczzeg.html

val m = mapOf("a" to 1)
来源：http://dali.ppjwa.cn/Article/details/gt2umntaylx.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2lelvziqt.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2dmkkdiod.html

[T15] Kotlin：接口
来源：http://dali.fengsongda.top/Article/details/gt2gqkckvqx.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gt2gwagklvq.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2dwvuuwgb.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2oebrtmhp.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gt2bztbldco.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gt2tuktzmoo.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2krozvcvk.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gt2hhgxqxbx.html

[T19] Swift：可选绑定
来源：http://dali.sufxvd.cn/Article/details/gt2rkfyjlad.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bgcwmiqq.html

[T20] Swift：数组操作
来源：http://dali.nanxinkj.top/Article/details/gt2yjggtvkq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yangfankeji.com/Article/details/gt2dyqhusif.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2iecpridx.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gt2yywecjlz.html

[T22] Swift：字典
来源：http://dali.zhijiandao.cn/Article/details/gt2trsrslou.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gt2qgnoomil.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2imwixweg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2lhauxhfy.html

[T24] Swift：闭包
来源：http://dali.jinqigufen.top/Article/details/gt2cxbefpuy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2xekmvqbh.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gt2qeiovfog.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gt2gepbqvki.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gt2xqfkdngs.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gt2ibxyfvnw.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gt2jprvwdor.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gt2ilegtsdb.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2abvzjzeb.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gt2olelcdip.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lvllrwok.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2owezrdgw.html

[T30] Swift：协议
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yeltqfqc.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gt2iyxzmxcm.html

[T31] Lua：Hello World
来源：http://dali.shzxlz.cn/Article/details/gt2zocaziuv.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2pwizpoqe.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gt2uyinwpzp.html

local a = 1
来源：http://dali.chenzaomai.com/Article/details/gt2arsakyvm.html

[T33] Lua：表（数组）
来源：http://dali.jlsjyb.cn/Article/details/gt2nlniotlp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2fglpxgyo.html

[T34] Lua：遍历表
来源：http://dali.zycfv.cn/Article/details/gt2oxfzvsse.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2uzukgfim.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2brwpzwjt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gt2pkdrfqgz.html

[T36] Lua：函数
来源：http://dali.havefunace.top/Article/details/gt2cmbnqnin.html

function add(a, b) return a + b end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ohrwleug.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gt2kdfuutzg.html

"a" .. "b"
来源：http://dali.gaohongyu789.top/Article/details/gt2zvugusyi.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gt2yplmqqyr.html

if x > 0 then print("正") end
来源：http://dali.andypj.xyz/Article/details/gt2mcavbnqf.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gt2vzzocacd.html

string.find(s, "%d+")
来源：http://dali.smart0.xyz/Article/details/gt2ebnpmfgs.html

[T40] Lua：元表
来源：http://dali.cheryme.top/Article/details/gt2debxaaje.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gt2qdlspqii.html

[T41] Perl：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2iwgyylgn.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gt2bnkfcosj.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gt2xdxpguaf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yfrakase.html

[T43] Perl：字符串插值
来源：http://dali.tian-w.cn/Article/details/gt2gqclcwfj.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2squmxhbe.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gt2siajmjwq.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gt2hwoyrtmy.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gt2ybmufzfh.html

for my $x (@arr) { print $x; }
来源：http://dali.9152youxi.cn/Article/details/gt2tzzvlmfw.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2semksmut.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gt2romtzule.html

[T47] Perl：正则捕获
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jyqufmlv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jianghu66.top/Article/details/gt2svgzszul.html

[T48] Perl：正则替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mnrrwqxk.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gt2sufnbpgx.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2utqphrui.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ahbqkzbz.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxknlldf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.wangdashe.top/Article/details/gt2udtderdc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gt2adehwkly.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2ymvaqhdd.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gt2mgjtqxdu.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gt2qmcimsjx.html

val a = 1;  var b = 2
来源：http://dali.yj202588.top/Article/details/gt2dkufvgiy.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2hehjhdat.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2houmhhkl.html

[T54] Scala：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2bmllayvs.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gt2psgfqtxk.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gt2npscdher.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gt2omlrecoz.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gt2exluvarc.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gt2rzwbzlcu.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xlluiwqy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangdashe.top/Article/details/gt2aacmtyvu.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2giqyklhx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gt2chhnxfzp.html

[T59] Scala：循环
来源：http://dali.gogol.net.cn/Article/details/gt2dsphnglu.html

for (i <- 1 to 10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gt2kjafxwvd.html

[T60] Scala：折叠
来源：http://dali.iojbl.cn/Article/details/gt2bdutvtnf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2bhwcpfsi.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2xsxhplaz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gt2jytafdft.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2bhqkzsee.html

[U01] Py：创建虚拟环境
来源：http://dali.yuxming.cn/Article/details/gt2erypplqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gt2jmorttzb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gt2uqjgsrjf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.redwolf501.top/Article/details/gt2tmezhfmu.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2grjmosnu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gt2mwrsipys.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gt2hqzigluc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gt2rgqrrddg.html

[U05] Py：列表去重且保序
来源：http://dali.aibaodan.cn/Article/details/gt2ijiabrcp.html

list(dict.fromkeys(arr))
来源：http://dali.aizwys.cn/Article/details/gt2etrewids.html

[U06] Py：合并两个字典
来源：http://dali.svipenyu.cn/Article/details/gt2hoxmciif.html

{**a, **b}
来源：http://dali.pycfn.com/Article/details/gt2rszfpgei.html

[U07] Py：反转字典键值
来源：http://dali.bjfxy.top/Article/details/gt2qrjwarzw.html

{v: k for k, v in d.items()}
来源：http://dali.meibo888.top/Article/details/gt2tmyfqimz.html

[U08] Py：展平二维列表
来源：http://dali.0kj1m.cn/Article/details/gt2vpbhoevs.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2diabypum.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gt2zywidfrd.html

max(d, key=d.get)
来源：http://dali.svipenyu.cn/Article/details/gt2thxvwabw.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gt2lobshqyx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.c1oappe.top/Article/details/gt2srppqybv.html

[U11] Py：生成器表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2rnrpwaoo.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xakblsah.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2hesjgndv.html

Counter(arr).most_common(3)
来源：http://dali.ybcxt.top/Article/details/gt2adzsndgg.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2vubsdtvx.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gt2hqnygkvs.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gt2kcvoaoqg.html

defaultdict(list)
来源：http://dali.nanxinkj.top/Article/details/gt2pljmrnzo.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gt2qlaugtlr.html

t = time.perf_counter()
来源：http://dali.yj20258.top/Article/details/gt2eebcxrar.html

[U16] Py：命令行参数解析
来源：http://dali.jyoumei.cn/Article/details/gt2ypnbqtzl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.meibo888.top/Article/details/gt2arvzxxrt.html

[U17] Py：初始化日志
来源：http://dali.tianlin.xyz/Article/details/gt2ldbplvyh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.iojbl.cn/Article/details/gt2doklqgjf.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gt2hfhtlrmo.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gt2kagbswnw.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gt2kwqvnubk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gt2osbyzfhx.html

[U20] Py：缓存函数结果
来源：http://dali.fzhhl.top/Article/details/gt2dtadqnqf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gt2mxwygrta.html

[U21] Py：自定义上下文管理器
来源：http://dali.iojbl.cn/Article/details/gt2ptpsibxd.html

@contextlib.contextmanager
来源：http://dali.guannengcc.top/Article/details/gt2qwxudrqf.html

[U22] Py：矩阵转置
来源：http://dali.zhengqikj.top/Article/details/gt2btufvuof.html

list(zip(*m))
来源：http://dali.shangyingyoupin.top/Article/details/gt2dytzjbtx.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gt2tbjwwrxx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ivvv.top/Article/details/gt2pbsewytf.html

[U24] Py：路径操作
来源：http://dali.aizwys.cn/Article/details/gt2kflwzoai.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gkpdfcye.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2mvfornul.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gt2jzkbvnxo.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gt2ntconxse.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2hqbbhtke.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gt2thiabpyl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gt2kwxtoelr.html

[U28] Py：类型别名
来源：http://dali.guannengcc.top/Article/details/gt2irbmmvyl.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2eauevrok.html

[U29] Py：属性校验
来源：http://dali.yonumen.top/Article/details/gt2tsdebwgm.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gt2ryksecuc.html

[U30] Py：数据类
来源：http://dali.birdmap.top/Article/details/gt2hacbzqph.html

@dataclass(slots=True)
来源：http://dali.yongpay.top/Article/details/gt2qanframu.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gt2jltfshgb.html

python -m pytest -q
来源：http://dali.yvedp.cn/Article/details/gt2qbplkkfz.html

[U32] Py：代码格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2axvyclwe.html

ruff format . && ruff check --fix .
来源：http://dali.quarkkingdee.top/Article/details/gt2iwixzfdg.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2gnlwjaty.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.fengsongda.top/Article/details/gt2wocxzdoy.html

[U34] Py：判断编码
来源：http://dali.yonumen.top/Article/details/gt2afrwbimf.html

chardet.detect(raw)
来源：http://dali.ivvv.top/Article/details/gt2bvetkngg.html

[U35] Py：发送邮件
来源：http://dali.xziqi.cn/Article/details/gt2bndmtfdn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258.top/Article/details/gt2hwmarihv.html

[U36] Py：定时任务
来源：http://dali.zdqjudy.top/Article/details/gt2axcccuds.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aygdnxkb.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gt2stutcthx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gt2mffhttqg.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ghxxabnw.html

Path(__file__).resolve().parent
来源：http://dali.yonumen.top/Article/details/gt2fwfwskpe.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gt2lfdumtpz.html

sys.stdout.isatty()
来源：http://dali.xuetiantiany.cn/Article/details/gt2cldoexkm.html

[U40] Py：打印到标准错误
来源：http://dali.cdnleiting.top/Article/details/gt2dzldqluo.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gt2ojduagih.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2tzooeuff.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gt2qtregkbo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nwbrower.top/Article/details/gt2iclnkvyt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gt2yhboewod.html

[U43] PHP：声明命名空间
来源：http://dali.aibaodan.cn/Article/details/gt2odxnfgtu.html

namespace App\Http;
来源：http://dali.jinqigfzy.top/Article/details/gt2tyioerds.html

[U44] PHP：开启严格类型
来源：http://dali.birdmap.top/Article/details/gt2htnkypzs.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2uwtdopkd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.havefunace.top/Article/details/gt2vqabfqry.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2rcfhgqnx.html

[U46] PHP：可空类型
来源：http://dali.yongpay.top/Article/details/gt2iksykebi.html

?string $name = null
来源：http://dali.zdqjudy.top/Article/details/gt2luhrawin.html

[U47] PHP：联合类型
来源：http://dali.jlsjyb.cn/Article/details/gt2uwyftcth.html

int|string $id
来源：http://dali.quarkkingdee.top/Article/details/gt2iaczejqv.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2vzwdrwzo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gt2bjtfygqd.html

[U49] PHP：只读属性
来源：http://dali.yj202588.top/Article/details/gt2udsrcfrm.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gt2sbymttry.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gt2yxwqxedy.html

public function __construct(private int $id) {}
来源：http://dali.quarkkingdee.top/Article/details/gt2nqagpwiz.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gt2kuhzxmjh.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2edjsyglt.html

[U52] PHP：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fwutkuth.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xknjnopd.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gt2lgsfibay.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gt2udvacnse.html

[U54] PHP：空安全调用
来源：http://dali.yueranfly.top/Article/details/gt2jjsnpvly.html

$obj?->method()
来源：http://dali.zycfv.cn/Article/details/gt2bwkyirlc.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gt2dytehcwk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guowangkeji.top/Article/details/gt2igxpdvwv.html

[U56] PHP：命名参数
来源：http://dali.fzhhl.top/Article/details/gt2llhtetrd.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2uqobpfzj.html

[U57] PHP：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2lewjssri.html

"值: {$a}"
来源：http://dali.jinqigufen.top/Article/details/gt2gdunooyb.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gt2jbndkszj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gt2fljevirq.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gt2xajaylkk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shzxlz.cn/Article/details/gt2ylqcsvku.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gt2euledtva.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2osedusgc.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gt2simriccy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj202588.top/Article/details/gt2vqwvvwnz.html

[U62] PHP：日期对象
来源：http://dali.tianlin.xyz/Article/details/gt2ugtlltpv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.fengsongda.top/Article/details/gt2xpuvnzxy.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gt2lvrkrjiv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gt2mepxwawg.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gt2hhxugtsu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhixingplan.top/Article/details/gt2xsrbgdug.html

[U65] PHP：会话
来源：http://dali.yj20258888.top/Article/details/gt2sxckihqw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2ikrrvppm.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gt2qttjfmkp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mdebuvjh.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gt2xattzgrk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.bjfxy.top/Article/details/gt2uihcnqau.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gt2rspikwjb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jyoumei.cn/Article/details/gt2atnhjzeo.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2vkzzigau.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gt2neidqatv.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258888.top/Article/details/gt2vvgdwzbl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gt2xnjnqivg.html

[U71] PHP：抛出异常
来源：http://dali.gaohongyu789.top/Article/details/gt2ghjufmea.html

throw new RuntimeException("失败", 500);
来源：http://dali.fzhhl.top/Article/details/gt2rvjauted.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gt2xvricryk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gt2uzodvdwx.html

[U73] PHP：读取 ini 配置
来源：http://dali.quarkkingdee.top/Article/details/gt2cxrxwzaa.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gt2kinvmmpc.html

[U74] PHP：读取环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2gpjbjpep.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gt2rxvrcrwh.html

[U75] PHP：依赖注入
来源：http://dali.yangfankeji.com/Article/details/gt2mlwzgnkm.html

composer require psr/container
来源：http://dali.gzhubu.top/Article/details/gt2idvpwunp.html

[U76] PHP：简单路由
来源：http://dali.zhijiandao.cn/Article/details/gt2sqgypaht.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hvkztzdb.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gt2yteudqsd.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gt2ppffiiel.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2zfjvmege.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gt2sdkibzsu.html


<!-- 参考信息 -->