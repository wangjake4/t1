代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtezamkgpd.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtzpwxcray.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtxqlloajt.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtbqbuwwgi.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtwaoixbgv.html

[S59] C++：静态断言
来源：http://dali.jinqigfzy.top/Article/details/gtvqaopbfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtaybgjsvu.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbepkkgny.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtlsyvgyvd.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtdhwefvxi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258888.top/Article/details/gtrenciisi.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtvehfrfek.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtaetojvvq.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtqagcgmzm.html

[T02] Kotlin：变量
来源：http://dali.aibaodan.cn/Article/details/gthiocrrbl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtigumzdtd.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtkftfrnhu.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtpelsnjqp.html

[T04] Kotlin：空安全
来源：http://dali.andypj.xyz/Article/details/gtyplvcubn.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtntxiqlzp.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gtwylvlacd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dashuyun.cn/Article/details/gtotjkduot.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtpdhttdcl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtyflnolsv.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gttpjwhxaq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gthgjbzmun.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtsburydmt.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtbxbgwabj.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtlwjaqbww.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtttgdxdex.html

[T10] Kotlin：默认参数
来源：http://dali.smart0.xyz/Article/details/gtwzlalrpi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtgsjyiptd.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtiwbharej.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkvivoveg.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtpxmvtpxm.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtfzhhjdjc.html

[T13] Kotlin：只读 Map
来源：http://dali.tianlin.xyz/Article/details/gtcbiadmtg.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtojdyamhj.html

[T14] Kotlin：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgegpjeaw.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtcowycaco.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtcjzzhrbr.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gtcqqphtrm.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtlhggcvqk.html

print("Hello")
来源：http://dali.tian-w.cn/Article/details/gtdioulfoi.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gtqbcpberg.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtyyeutkmg.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtnynazbmo.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtwwqufhjs.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gtdncdwypk.html

if let n = opt { print(n) }
来源：http://dali.yj202588.top/Article/details/gttvvzfmsz.html

[T20] Swift：数组操作
来源：http://dali.shangyingyoupin.top/Article/details/gtbuydmqgr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtfqktocod.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtgjejhchg.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtqvaqasix.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtqywuzizd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258.top/Article/details/gteymzqtyp.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtcykvxeys.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxuanxn.top/Article/details/gtotfmxbmr.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtwstjfhgl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtttgvotsh.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gtxwymhyck.html

struct P { var x: Int }
来源：http://dali.ydzc1.top/Article/details/gtcumdpaqy.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gtcwtagxrm.html

class A: Base { override func f() {} }
来源：http://dali.316326.xyz/Article/details/gtjlvwwwmg.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtrprhbllf.html

do { try f() } catch { print(error) }
来源：http://dali.guannengcc.top/Article/details/gtoxbycloa.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtxbecjbgo.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmapcxhsi.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtipaxglmq.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtwxmlgzhf.html

[T30] Swift：协议
来源：http://dali.hnxiangtu.top/Article/details/gtudhwohfg.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtzcmladwq.html

[T31] Lua：Hello World
来源：http://dali.sysykeji.top/Article/details/gthmrxygda.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtnjrkfyyn.html

[T32] Lua：局部变量
来源：http://dali.cdnleiting.top/Article/details/gtosaijlev.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacgcvnxi.html

[T33] Lua：表（数组）
来源：http://dali.yvedp.cn/Article/details/gtmapmhght.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtmpftkhfp.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtflqyiqzg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtywxcxocf.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gttxdhgkys.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sweek.top/Article/details/gtnllxidpd.html

[T36] Lua：函数
来源：http://dali.zhoulong.xyz/Article/details/gtrtdzxjhm.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtpsokvsgi.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaruouzp.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttykjuylf.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gtckydwdgi.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gtvreerprw.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gtdvrtwmqz.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gtavyhzqad.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtrgzetnfa.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gteljswold.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtgyseixgl.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gtcnecefsf.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gtzsfdeolw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.snrcjt.cn/Article/details/gtyamafybz.html

[T43] Perl：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtntgyrapf.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtoqlbpphh.html

[T44] Perl：条件
来源：http://dali.shuidangran.top/Article/details/gtclizyiwv.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtwhestuym.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtffuvluyc.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gtzudmhzuz.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gtohyfngbw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.vqdsnc.cn/Article/details/gtjeeihjcm.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtgszpskxf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gtimwbrvbu.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtjbotzmtu.html

$s =~ s/old/new/g;
来源：http://dali.yuanzhike.top/Article/details/gtdsazvhki.html

[T49] Perl：函数
来源：http://dali.zhengqikj.top/Article/details/gtgrqijpim.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtqmcnzzqu.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdisnychv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ehwqpu.com/Article/details/gtfyxsezav.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtsqrhejke.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gtaywuhuru.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gtgvfjeeib.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtywajyyxa.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtdsbkxkbh.html

[T53] Scala：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtggvqwchf.html

s"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtyzqdubkd.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtpqfwpujv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtgpaypiys.html

[T55] Scala：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gttfinjpko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtxcgotlfu.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gtfctxlvnt.html

case class User(name: String, age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtnqkewsry.html

[T57] Scala：模式匹配
来源：http://dali.vqdsnc.cn/Article/details/gtqcffcmnl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tianlin.xyz/Article/details/gtegiekiag.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtramvukke.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtgjnugpjs.html

[T59] Scala：循环
来源：http://dali.jyoumei.cn/Article/details/gtwhlyzxcj.html

for (i <- 1 to 10) println(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtdxudpqam.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gtvkmfdmnp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gtrxvikxjr.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtuoognlia.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtrgrbsvxp.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtadzdugdl.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtuyjkanhm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtcejwinic.html

[U02] Py：导出 / 安装依赖
来源：http://dali.mhx1999.top/Article/details/gteutwvton.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gttigflogn.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtxgzjolma.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ydzc1.top/Article/details/gtaakdzfxr.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gtrsxqxidm.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jianghu66.top/Article/details/gtnpktzxuv.html

[U05] Py：列表去重且保序
来源：http://dali.gaohongyu789.top/Article/details/gtjyafebag.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtfarnpmsm.html

[U06] Py：合并两个字典
来源：http://dali.yongpay.top/Article/details/gthmkazoxo.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtxnmvxufc.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gtugbpewxo.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gtzoxrkcmh.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxsenhss.html

[y for x in nested for y in x]
来源：http://dali.snrcjt.cn/Article/details/gthutjvglv.html

[U09] Py：字典取最大值的键
来源：http://dali.cheryme.top/Article/details/gturtavcvj.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gtlhhlxpcy.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtrctsousv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gtdwugguqb.html

[U11] Py：生成器表达式
来源：http://dali.yj202588.top/Article/details/gtjhevjlbp.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gthnvapmfw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenlongwang.top/Article/details/gtmyjxhebv.html

Counter(arr).most_common(3)
来源：http://dali.hywenlv.cn/Article/details/gttetypmco.html

[U13] Py：固定长度队列
来源：http://dali.dianchejie.cn/Article/details/gtgmgjixqx.html

deque(maxlen=10)
来源：http://dali.316326.xyz/Article/details/gtqpykfwwt.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gthbasehvu.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtrbeiqosq.html

[U15] Py：高精度计时
来源：http://dali.hfpthk.cn/Article/details/gtidgiizcu.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gtsgdoakzo.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gthdjvfsnp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhiwuduotai.top/Article/details/gtuaiczsru.html

[U17] Py：初始化日志
来源：http://dali.shzxlz.cn/Article/details/gtfelhuaix.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gttilwedat.html

[U18] Py：预编译正则
来源：http://dali.gotoacloud.top/Article/details/gtvixmcuwa.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofcsyviz.html

[U19] Py：正则替换带回调
来源：http://dali.xziqi.cn/Article/details/gtfitmtnft.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtrtjajykf.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gtulfanuva.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj20258888.top/Article/details/gtxpblcojl.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gtggeubuvf.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtshxnzlgv.html

[U22] Py：矩阵转置
来源：http://dali.daxiang520.top/Article/details/gtlujvnxvp.html

list(zip(*m))
来源：http://dali.tanke756.top/Article/details/gtsxjwznxf.html

[U23] Py：分块读取大文件
来源：http://dali.sufxvd.cn/Article/details/gtymnjrcyo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.316326.xyz/Article/details/gtvwjosvwt.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtylnfthgz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gzhubu.top/Article/details/gtwpbilyfy.html

[U25] Py：CSV 按字典读
来源：http://dali.yangfankeji.com/Article/details/gtaapsglnq.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtbpknasde.html

[U26] Py：并发下载
来源：http://dali.guowangkeji.top/Article/details/gtqbfipmyn.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.birdmap.top/Article/details/gtdqmdraxk.html

[U27] Py：异步 HTTP
来源：http://dali.yj20258888.top/Article/details/gtztsmqfpe.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gotoacloud.top/Article/details/gthjxxrpvr.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtscwhfrme.html

UserId = int
来源：http://dali.zhoulong.xyz/Article/details/gtnvnnviod.html

[U29] Py：属性校验
来源：http://dali.shuidangran.top/Article/details/gtnkhhgffp.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gtfgqvtjjr.html

[U30] Py：数据类
来源：http://dali.jqgufenzy.top/Article/details/gttelgugha.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtzqpawdgn.html

[U31] Py：单测
来源：http://dali.jqgufenzy.top/Article/details/gtsbcxcjpx.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gtzmfimvic.html

[U32] Py：代码格式化
来源：http://dali.gotoacloud.top/Article/details/gtdnjmksav.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtsnouamww.html

[U33] Py：打包发布
来源：http://dali.hfpthk.cn/Article/details/gtwbntaoql.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.sweek.top/Article/details/gteeoiotii.html

[U34] Py：判断编码
来源：http://dali.cucudq.cn/Article/details/gtvyzpnrus.html

chardet.detect(raw)
来源：http://dali.sufxvd.cn/Article/details/gtqgcfiuht.html

[U35] Py：发送邮件
来源：http://dali.hongshengwenyu.top/Article/details/gthmwkwknq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtoobvaujk.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gtszbhszjs.html

schedule.every(10).minutes.do(job)
来源：http://dali.shzxlz.cn/Article/details/gtvcwgwmym.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtnmctvjqv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gtrmxmzyzu.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gtbmttwrda.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gtjpypnstk.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtljlehnnj.html

sys.stdout.isatty()
来源：http://dali.andypj.xyz/Article/details/gtlnykqqcu.html

[U40] Py：打印到标准错误
来源：http://dali.aibaodan.cn/Article/details/gtdpqkvysp.html

print("err", file=sys.stderr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpplcmpvs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gtdrcainth.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.pengpengdd.cyou/Article/details/gtbujhgykx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gtlbuekvmg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yanxiufei.cn/Article/details/gtfdjomivn.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtiukeoaac.html

namespace App\Http;
来源：http://dali.yangfankeji.com/Article/details/gtuabtmvmt.html

[U44] PHP：开启严格类型
来源：http://dali.tanke756.top/Article/details/gtxennhlbd.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gtgypyqwon.html

[U45] PHP：类型声明与返回类型
来源：http://dali.mhx1999.top/Article/details/gtxlzlttqx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplaixciz.html

[U46] PHP：可空类型
来源：http://dali.nwbrower.top/Article/details/gteqlmyvud.html

?string $name = null
来源：http://dali.xylfe.cn/Article/details/gtkrftqltm.html

[U47] PHP：联合类型
来源：http://dali.cashguo.top/Article/details/gtfrwcanmm.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gtcycrubok.html

[U48] PHP：纯枚举
来源：http://dali.quarkkingdee.top/Article/details/gttjmayfoa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ivvv.top/Article/details/gtmofurnxm.html

[U49] PHP：只读属性
来源：http://dali.aizwys.cn/Article/details/gtqkgwjyud.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gtpcusojih.html

[U50] PHP：构造器属性提升
来源：http://dali.pycfn.com/Article/details/gtlgihawio.html

public function __construct(private int $id) {}
来源：http://dali.havefunace.top/Article/details/gtcwewzvbg.html

[U51] PHP：数组解构
来源：http://dali.birdmap.top/Article/details/gtmmbbufsa.html

[$a, $b] = $arr;
来源：http://dali.jiagoushi.top/Article/details/gtcttrujvt.html

[U52] PHP：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtddzzpfij.html

$double = fn($x) => $x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gtranlbsvb.html

[U53] PHP：空合并运算符
来源：http://dali.tanke756.top/Article/details/gtjdwfhzjy.html

$v = $a ?? $b ?? "default";
来源：http://dali.gaohongyu789.top/Article/details/gtdnxqybjs.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtmakyuuke.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gtovbcwcwc.html

[U55] PHP：match 表达式
来源：http://dali.cucudq.cn/Article/details/gtzsivfzpm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gtodoqzzrz.html

[U56] PHP：命名参数
来源：http://dali.yanxiufei.cn/Article/details/gtmwdjpfrg.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtgscslzfu.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtqpqsnohn.html

"值: {$a}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtybblgz.html

[U58] PHP：数组三件套
来源：http://dali.fengsongda.top/Article/details/gtmajaqjbl.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.gzhubu.top/Article/details/gtpmcxfyju.html

[U59] PHP：自定义排序
来源：http://dali.yanxiufei.cn/Article/details/gtjlbqknbf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fengsongda.top/Article/details/gtwtwoqozn.html

[U60] PHP：JSON 编解码
来源：http://dali.haohaochexian.top/Article/details/gtpazwsybj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shuidangran.top/Article/details/gtxhqmmykj.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gtqqafuqrl.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.xuetiantiany.cn/Article/details/gtleoiiurm.html

[U62] PHP：日期对象
来源：http://dali.316326.xyz/Article/details/gtpvutercd.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuanzhike.top/Article/details/gtnzbvsxmo.html

[U63] PHP：文件读写
来源：http://dali.wangshuangyany.cn/Article/details/gtvaolkmra.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtvfbmsxbv.html

[U64] PHP：目录遍历
来源：http://dali.kuanghao11.cn/Article/details/gtqflcwpmv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gtukostbpb.html

[U65] PHP：会话
来源：http://dali.zhijiandao.cn/Article/details/gtjelyuqkq.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtkqszlddd.html

[U66] PHP：设置 Cookie
来源：http://dali.cucudq.cn/Article/details/gtkiawxglo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cdnleiting.top/Article/details/gtjpxmbiyj.html

[U67] PHP：处理文件上传
来源：http://dali.xinyue.icu/Article/details/gtabgbzkya.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxinkj.top/Article/details/gtkvgkgjlv.html

[U68] PHP：PDO 连接
来源：http://dali.jiagoushi.top/Article/details/gtsebudgzw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fengsongda.top/Article/details/gtcedkjntr.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gtjhcdoopv.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.dashuyun.cn/Article/details/gtdwjwkrpn.html

[U70] PHP：PDO 事务
来源：http://dali.aibaodan.cn/Article/details/gtaofoiijn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shangyingyoupin.top/Article/details/gtnnkczhch.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtzpwxunke.html

throw new RuntimeException("失败", 500);
来源：http://dali.iojbl.cn/Article/details/gtlbbwfodh.html

[U72] PHP：写错误日志
来源：http://dali.haohaochexian.top/Article/details/gtxicxpbrx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.vqdsnc.cn/Article/details/gtnquuodkc.html

[U73] PHP：读取 ini 配置
来源：http://dali.haohaochexian.top/Article/details/gtabdpfddm.html

parse_ini_file("config.ini", true)
来源：http://dali.nanxinkj.top/Article/details/gtrqbpatnf.html

[U74] PHP：读取环境变量
来源：http://dali.wangdashe.top/Article/details/gtgzebvsse.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxinkj.top/Article/details/gthyurahzy.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtlysqiopc.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtzkryhgth.html

[U76] PHP：简单路由
来源：http://dali.hywenlv.cn/Article/details/gtdfptoslh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gzhubu.top/Article/details/gtgqgckroa.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gtqkctduln.html

composer require twig/twig
来源：http://dali.sysykeji.top/Article/details/gtvxjfqyur.html

[U78] PHP：单元测试
来源：http://dali.hammf.cn/Article/details/gtywyovxbz.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxuanxn.top/Article/details/gtuguednus.html

[U79] PHP：静态分析
来源：http://dali.andypj.xyz/Article/details/gtgwhorcnn.html

composer require --dev phpstan/phpstan
来源：http://dali.jqgfzy.top/Article/details/gtiipeiskp.html

[U80] PHP：代码规范修复
来源：http://dali.sweek.top/Article/details/gtephpqdwc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.guannengcc.top/Article/details/gtlvhhitgx.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gtgvfuipox.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtcgbivssh.html

[U82] JS：package.json 脚本
来源：http://dali.guowangkeji.top/Article/details/gtiaoquhiv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gtrsseoomk.html


<!-- 参考信息 -->