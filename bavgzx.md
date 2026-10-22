代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2murlgvdl.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2ipnyuqvb.html

static_cast<double>(a) / b
来源：http://dali.nwbrower.top/Article/details/gt2uqtdsnnm.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gt2eonrwbxn.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gt2znuidxoz.html

[S53] C++：移动语义
来源：http://dali.yueranfly.top/Article/details/gt2rxkokebk.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2ppocxvcm.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gt2quzbglgb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gt2udyojktp.html

[S55] C++：结构化绑定
来源：http://dali.sweek.top/Article/details/gt2jlgbqxbx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gt2ijxjnzgh.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2nfpvsfmi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.9152youxi.cn/Article/details/gt2kttyypsu.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gt2xquzswbf.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gt2opdopwcs.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gt2qdgqemnj.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lqsajmtp.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gt2arbjxcgg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gt2joxctpuz.html

[S60] C++：遍历并删除元素
来源：http://dali.zhijiandao.cn/Article/details/gt2ysbnrhmw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gogol.net.cn/Article/details/gt2tapxbjyj.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2iekcmzmr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gt2buxjlepx.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2bugdhhga.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2zpshrtbd.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2sdidoijt.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gt2wuospmno.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhcudtmb.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gt2kozzyrfi.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gt2dvlesgom.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gt2jpvsasgw.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2nkzqxewf.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2wimjdejy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yueranfly.top/Article/details/gt2srswxint.html

[T06] Kotlin：集合映射
来源：http://dali.jiagoushi.top/Article/details/gt2vzhpwpgh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gt2gceeejoe.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2lselcbfz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2ablqtzbo.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lqoogkir.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gt2asvtyjlw.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gt2audornzh.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2qgsyseln.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxfewqkk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.quarkkingdee.top/Article/details/gt2pquhwsqs.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gt2ulqyuyix.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gt2xkpwemdb.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gt2rnsygbgy.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zbspbvmn.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gt2pqaxhvwy.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gt2mevyajtm.html

[T14] Kotlin：循环
来源：http://dali.sxryk.cn/Article/details/gt2nokvtjmc.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2llrweaqg.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2lrrtmihg.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2zxnhifdv.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2zmpmsvjh.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gt2dxhlahlp.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2xhcweekh.html

var a = 1;  let b = 2
来源：http://dali.jinqigfzy.top/Article/details/gt2qntyjurr.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2azwololg.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2wgabbuut.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gt2nvjveurz.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2csctzkgk.html

[T20] Swift：数组操作
来源：http://dali.jyoumei.cn/Article/details/gt2wqvyunjf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2aslvdypb.html

[T21] Swift：遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2shskcjvn.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gt2gswnodiz.html

[T22] Swift：字典
来源：http://dali.andypj.xyz/Article/details/gt2aooxiqii.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2tvdjbfxt.html

[T23] Swift：函数
来源：http://dali.snrcjt.cn/Article/details/gt2zoeajvuv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenlongwang.top/Article/details/gt2pzfxsapu.html

[T24] Swift：闭包
来源：http://dali.yangfankeji.com/Article/details/gt2xxnauphp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ucbvgoey.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gt2tprcwzsj.html

struct P { var x: Int }
来源：http://dali.meibo888.top/Article/details/gt2obfsclmt.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gt2mfbnamrs.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gt2vgiowuou.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gt2zsmbzdpo.html

do { try f() } catch { print(error) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ulmffybc.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2yluzzjis.html

enum Color { case red, green }
来源：http://dali.hywenlv.cn/Article/details/gt2lxlpfqxa.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gt2ggtlwkgf.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzuhmfja.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gt2voxprbja.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjnjflte.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2hmgduoet.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2ywgxsoiq.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2esgtansn.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2rgzvqapi.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gt2hqcgxmcd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gt2kbszljlq.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gt2evfgqbtb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gt2btshvvfh.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hbugpmly.html

local d = { a = 1 };  d.b = 2
来源：http://dali.pycfn.com/Article/details/gt2insgqeys.html

[T36] Lua：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvpzcgst.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gt2aamxdpnb.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gt2cfliqwnz.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gt2bmnsanqq.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wihjrtmf.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gt2peldedxt.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gt2kwkalqfe.html

string.find(s, "%d+")
来源：http://dali.zhoulong.xyz/Article/details/gt2atoodvlf.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gt2rnifxbnj.html

setmetatable({}, { __index = base })
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rnwbezfi.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2hqirghyf.html

print "Hello\n";
来源：http://dali.yj20258888.top/Article/details/gt2jppludqn.html

[T42] Perl：变量类型
来源：http://dali.hysaishi.cn/Article/details/gt2rcwpvqhq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gt2gdpuoqer.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2moyttiig.html

"值: $a"
来源：http://dali.daxiang520.top/Article/details/gt2nxttcory.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gt2hhgptjde.html

if ($a > 0) { print "正"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2htfhrutt.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2ttuptctm.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2kjknkljf.html

[T46] Perl：哈希操作
来源：http://dali.gzhubu.top/Article/details/gt2hkjdhtdf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yueranfly.top/Article/details/gt2demesksd.html

[T47] Perl：正则捕获
来源：http://dali.dashuyun.cn/Article/details/gt2cejrvocp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gt2zpejqkpr.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oqhseeti.html

$s =~ s/old/new/g;
来源：http://dali.yj202588.top/Article/details/gt2ebkugtgc.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gt2lbzqqnca.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2mdkzovkg.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gt2jdujfgyd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yangfankeji.com/Article/details/gt2xfvcxksn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zpszklmu.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2reuqxeeg.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2sifvxwta.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gt2ogpscztb.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gt2ybzduwqf.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2fatjurkd.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gt2jxummlgk.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2skndtqbx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yonumen.top/Article/details/gt2fumglpdv.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2ibqzpbnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xylfe.cn/Article/details/gt2hozbkhux.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2azxdpptg.html

case class User(name: String, age: Int)
来源：http://dali.ppjwa.cn/Article/details/gt2wxijeeev.html

[T57] Scala：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2peepmgzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cashguo.top/Article/details/gt2nufqdais.html

[T58] Scala：函数定义
来源：http://dali.xziqi.cn/Article/details/gt2cbwbhjqe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gt2ycupvezg.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gt2uojlxvog.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2ltyouxgg.html

[T60] Scala：折叠
来源：http://dali.daxiang520.top/Article/details/gt2egxajoda.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cucudq.cn/Article/details/gt2vjswfarz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2foprercn.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2huxflyrh.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kmtsdxgm.html

[U01] Py：创建虚拟环境
来源：http://dali.sxryk.cn/Article/details/gt2ldpnltvk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gt2rtxduuzi.html

[U02] Py：导出 / 安装依赖
来源：http://dali.dianchejie.cn/Article/details/gt2xcochvop.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gt2slvseogd.html

[U03] Py：加载 .env 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrdeszrq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gt2aqefxpvw.html

[U04] Py：变量调试打印
来源：http://dali.yj202588.top/Article/details/gt2ebvtrwxj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gt2yukzkfrz.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gt2pwoejpce.html

list(dict.fromkeys(arr))
来源：http://dali.snrcjt.cn/Article/details/gt2ryiqhyne.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gt2ttuzfzkr.html

{**a, **b}
来源：http://dali.yuxming.cn/Article/details/gt2fwquwkqo.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gt2kmiinerw.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gt2bydkqhyo.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gt2tacfgoyw.html

[y for x in nested for y in x]
来源：http://dali.fzhhl.top/Article/details/gt2vuqkqyym.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gt2ujgzqpig.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gt2yrcwrlef.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2bfbuovqn.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ybcxt.top/Article/details/gt2zzzsaoyg.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2tjgznthn.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gt2ftctrjax.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gt2gvbpevie.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gt2taxcqplw.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gt2pmedcjgw.html

deque(maxlen=10)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ueyrzdws.html

[U14] Py：分组收集到列表
来源：http://dali.sweek.top/Article/details/gt2cayfwzqr.html

defaultdict(list)
来源：http://dali.c1oappe.top/Article/details/gt2xuxvjpif.html

[U15] Py：高精度计时
来源：http://dali.pengpengdd.cyou/Article/details/gt2khrbzpir.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gt2nqhlogqd.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gt2uibgnxoj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gt2agndqawu.html

[U17] Py：初始化日志
来源：http://dali.vqdsnc.cn/Article/details/gt2necnjkzt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gt2iisihucw.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gt2exahgakl.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gt2rfmcbfrf.html

[U19] Py：正则替换带回调
来源：http://dali.yj202588.top/Article/details/gt2xmrtavxb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dianchejie.cn/Article/details/gt2jgyrtnxd.html

[U20] Py：缓存函数结果
来源：http://dali.yangfankeji.com/Article/details/gt2uwlznfdh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrzjfogf.html

[U21] Py：自定义上下文管理器
来源：http://dali.hnqzz.top/Article/details/gt2krizhfgu.html

@contextlib.contextmanager
来源：http://dali.bjfxy.top/Article/details/gt2roioyncf.html

[U22] Py：矩阵转置
来源：http://dali.zhixingplan.top/Article/details/gt2hkufctwa.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2pkucdmxl.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgwpgntb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gt2wmwienqq.html

[U24] Py：路径操作
来源：http://dali.yongpay.top/Article/details/gt2vcwrutix.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guannengcc.top/Article/details/gt2lsvklvjk.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2xfktfaed.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gt2qrnbabtt.html

[U26] Py：并发下载
来源：http://dali.c1oappe.top/Article/details/gt2jhvvlwpr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yuanzhike.top/Article/details/gt2thmvloot.html

[U27] Py：异步 HTTP
来源：http://dali.zdqjudy.top/Article/details/gt2uzttfnfo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.ivvv.top/Article/details/gt2iahslcru.html

[U28] Py：类型别名
来源：http://dali.sweek.top/Article/details/gt2bqhhugbn.html

UserId = int
来源：http://dali.xuanzx.com/Article/details/gt2thehyals.html

[U29] Py：属性校验
来源：http://dali.birdmap.top/Article/details/gt2gynpuypj.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gt2fkwwphrb.html

[U30] Py：数据类
来源：http://dali.gzhubu.top/Article/details/gt2rzybmuce.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gt2icbzspud.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wrtdcovf.html

python -m pytest -q
来源：http://dali.fzhhl.top/Article/details/gt2tlsonxky.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gt2mbsacokr.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gt2sciqviik.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gt2qhwufzzt.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yanxiufei.cn/Article/details/gt2jrhkdrwk.html

[U34] Py：判断编码
来源：http://dali.jinqigfzy.top/Article/details/gt2pmhpcycu.html

chardet.detect(raw)
来源：http://dali.zycfv.cn/Article/details/gt2dhlvyjbj.html

[U35] Py：发送邮件
来源：http://dali.shzxlz.cn/Article/details/gt2tjnoerpn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mqopgotg.html

[U36] Py：定时任务
来源：http://dali.ivvv.top/Article/details/gt2cxxvdznd.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gt2aqugumms.html

[U37] Py：读写 Excel
来源：http://dali.gotoacloud.top/Article/details/gt2wclbqthj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gotoacloud.top/Article/details/gt2aoghlldm.html

[U38] Py：获取脚本所在目录
来源：http://dali.pengpengdd.cyou/Article/details/gt2mvtsjmrk.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gt2xvqwijkj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj202588.top/Article/details/gt2mlwcaglg.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gt2kkpxoeaf.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gt2raoexpsd.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2ltyncqef.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigfzy.top/Article/details/gt2uivhenms.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2cvjtxczq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gt2nfxtmlxm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zxltgjqb.html

[U43] PHP：声明命名空间
来源：http://dali.ivvv.top/Article/details/gt2mxbnaowm.html

namespace App\Http;
来源：http://dali.meibo888.top/Article/details/gt2ntcuuqtw.html

[U44] PHP：开启严格类型
来源：http://dali.yuanzhike.top/Article/details/gt2lrptpzzy.html

declare(strict_types=1);
来源：http://dali.yuanzhike.top/Article/details/gt2rpjzhija.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yj202588.top/Article/details/gt2msslzivz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2jofimjlr.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gt2xccosizk.html

?string $name = null
来源：http://dali.fengsongda.top/Article/details/gt2uplvjjkh.html

[U47] PHP：联合类型
来源：http://dali.cqqwz.cn/Article/details/gt2ktuvouow.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gt2fabnuqql.html

[U48] PHP：纯枚举
来源：http://dali.9152youxi.cn/Article/details/gt2lltbeaoq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.mhx1999.top/Article/details/gt2iwjsjqgg.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gt2viukfdbk.html

public readonly string $name
来源：http://dali.ehwqpu.com/Article/details/gt2dkmddwlb.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gt2rqsbgiob.html

public function __construct(private int $id) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2awgurckq.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gt2lsugzpfk.html

[$a, $b] = $arr;
来源：http://dali.yanxiufei.cn/Article/details/gt2eyekwbrg.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gt2nzfbvrqs.html

$double = fn($x) => $x * 2;
来源：http://dali.fzhhl.top/Article/details/gt2urplepvi.html

[U53] PHP：空合并运算符
来源：http://dali.feifeiyinyue.top/Article/details/gt2fckiperd.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gt2upxwimor.html

[U54] PHP：空安全调用
来源：http://dali.chenzaomai.com/Article/details/gt2zmmydbjs.html

$obj?->method()
来源：http://dali.cashguo.top/Article/details/gt2ldlrqguj.html

[U55] PHP：match 表达式
来源：http://dali.nwbrower.top/Article/details/gt2yxjalrby.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2zbzuxrbn.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gt2vaqdyorh.html

f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2udljtdhb.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2ujkvlboe.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gt2hknxzwvm.html

[U58] PHP：数组三件套
来源：http://dali.xziqi.cn/Article/details/gt2lpfwvrwt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.daria6918.cn/Article/details/gt2rvaemhuw.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2vwulmfzw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2mzwlflla.html

[U60] PHP：JSON 编解码
来源：http://dali.sxryk.cn/Article/details/gt2crzstsnr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangdashe.top/Article/details/gt2iapfraww.html

[U61] PHP：正则
来源：http://dali.hnxiangtu.top/Article/details/gt2ajwpgsfi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gt2czcrovyp.html

[U62] PHP：日期对象
来源：http://dali.aibaodan.cn/Article/details/gt2kbuxretk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sweek.top/Article/details/gt2yczcaxcd.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2sizrwsco.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dweorgjj.html

[U64] PHP：目录遍历
来源：http://dali.yuanzhike.top/Article/details/gt2zabchyft.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shzxlz.cn/Article/details/gt2scheaigh.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2yitxzhqo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gt2uptoyrzo.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2wsxsilzx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gt2pkfqegdw.html

[U67] PHP：处理文件上传
来源：http://dali.dianchejie.cn/Article/details/gt2gdxwjbrv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gt2sckyqdzp.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gt2pqnbticn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yueranfly.top/Article/details/gt2zpbpifpt.html

[U69] PHP：PDO 预处理
来源：http://dali.wangdashe.top/Article/details/gt2unucehwc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhiwuduotai.top/Article/details/gt2bihotnkn.html

[U70] PHP：PDO 事务
来源：http://dali.sysykeji.top/Article/details/gt2nwlbtxft.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gt2qptykwda.html

[U71] PHP：抛出异常
来源：http://dali.iojbl.cn/Article/details/gt2lgtbnfit.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gt2fdxxaqem.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2zawlrkis.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yangfankeji.com/Article/details/gt2zjnzndvy.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhiwuduotai.top/Article/details/gt2orpfbjie.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gt2rnfoffob.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gt2kanrhega.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigufen.top/Article/details/gt2ezdwjdwh.html

[U75] PHP：依赖注入
来源：http://dali.shuidangran.top/Article/details/gt2ldqfkfhy.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gt2ywviwasq.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gt2argzudnq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gt2zjrfhahp.html


<!-- 参考信息 -->