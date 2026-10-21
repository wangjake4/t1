代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtlkaojpdz.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtkrpgbqll.html

constexpr int N = 10;
来源：http://dali.ppjwa.cn/Article/details/gtgggptmga.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtqgcjfcob.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjprjnfjm.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtidysbqnw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtaverhrhq.html

[S60] C++：遍历并删除元素
来源：http://dali.xylfe.cn/Article/details/gtafjeqzjg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jianghu66.top/Article/details/gtjremgktw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtnqtigpiy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtemdpaktm.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtiirisqkl.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gtknnrdgni.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gthqhbomxc.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtycsoodrg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtamppzeks.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gttxdidqid.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtamropjph.html

[T04] Kotlin：空安全
来源：http://dali.aibaodan.cn/Article/details/gtbfwsmdvh.html

val n: String? = null;  n?.length
来源：http://dali.xylfe.cn/Article/details/gtbsixmzin.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gtpljcqcqq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtyqzteojw.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtcdmlbsct.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtrjowgxpc.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtonlbjtuc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gtbsvllbum.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtcciulqva.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtuocdcjxd.html

[T09] Kotlin：扩展函数
来源：http://dali.ivvv.top/Article/details/gtuuwakvrk.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtetnrqmjv.html

[T10] Kotlin：默认参数
来源：http://dali.jqgfzy.top/Article/details/gtrgkqblrn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daxiang520.top/Article/details/gtkgntixyb.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtesguzusx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtptqmndka.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gtunevxsru.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtzxzlnkbo.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtklgsogly.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gthzqeigrd.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtuszlgkfn.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhydbdle.html

[T15] Kotlin：接口
来源：http://dali.tanke756.top/Article/details/gtcevosndq.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gthoickxux.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gtzxjbrkpn.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtotsnsqbd.html

[T17] Swift：变量与常量
来源：http://dali.yuxming.cn/Article/details/gtkjzkfrbf.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnmprufl.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtfpskohov.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdbredcq.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtanxtruch.html

if let n = opt { print(n) }
来源：http://dali.hnxiangtu.top/Article/details/gtbnazemqz.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gtnrcvrqbz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtiutgpkkt.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgftbzms.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtdxctaqkp.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtpofwmsut.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtaiuffcyo.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtelwbgkqn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.316326.xyz/Article/details/gtqkyrjoqh.html

[T24] Swift：闭包
来源：http://dali.xziqi.cn/Article/details/gtyxbnbmvd.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtpfwdugvk.html

[T25] Swift：结构体
来源：http://dali.0kj1m.cn/Article/details/gtcfmboloy.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtyevolpfq.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtzhzspqux.html

class A: Base { override func f() {} }
来源：http://dali.guowangkeji.top/Article/details/gtmpbjbxse.html

[T27] Swift：错误处理
来源：http://dali.hysaishi.cn/Article/details/gtuseauylc.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtuttyybys.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtimxmlmmx.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtqswmuasu.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gtthztldgs.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtlxpkjvwo.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gthcvbopoj.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtazkivzad.html

[T31] Lua：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtdhyerdor.html

print("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzddlokp.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtyrclhmsk.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtyngblqqx.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtbddpsqro.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daria6918.cn/Article/details/gtucdlzbgc.html

[T34] Lua：遍历表
来源：http://dali.hammf.cn/Article/details/gtuxoivmfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ppjwa.cn/Article/details/gtseydqozy.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gtxzwckrmj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtfvivqpzy.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtagckfjhn.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gtzegpoiya.html

[T37] Lua：字符串拼接
来源：http://dali.nwbrower.top/Article/details/gtctvvifni.html

"a" .. "b"
来源：http://dali.tianlin.xyz/Article/details/gtwoymqsxk.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnevhjfd.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtxcolyirb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtrxzghlea.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtnhrxshab.html

[T40] Lua：元表
来源：http://dali.zhixingplan.top/Article/details/gtrcyepdta.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtcuylepzb.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtahjygclc.html

print "Hello\n";
来源：http://dali.9152youxi.cn/Article/details/gtmidegzpq.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtcemhqnfs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gtsvsigkkp.html

[T43] Perl：字符串插值
来源：http://dali.shuidangran.top/Article/details/gttplrerti.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtfapygons.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gthvscktvy.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gtjlcwacik.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtdnumgcwf.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvthaazvs.html

[T46] Perl：哈希操作
来源：http://dali.yangfankeji.com/Article/details/gtwoncgwxq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtglvzvyue.html

[T47] Perl：正则捕获
来源：http://dali.tianlin.xyz/Article/details/gtfsiyflzy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj202588.top/Article/details/gtxgodcqmd.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtmvlyhgcc.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtrhlxbspg.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gtrygewoyq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtzevewhtp.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtkbqliggc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gtggnfynbb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcphahmss.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gtjqdejxgb.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtiyqbjlaf.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtgtsbxcfq.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtcukeifoq.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtbuizlbgb.html

s"值: $b"
来源：http://dali.haohaochexian.top/Article/details/gtekexpssa.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtfhjnecdt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gtsnzfsudi.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gthnuuphmz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtnbuwpjwv.html

[T56] Scala：样例类
来源：http://dali.yongpay.top/Article/details/gthspnnwuj.html

case class User(name: String, age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtnomnhfge.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtawrpsdek.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gthiyokoac.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtaekvyoel.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gtvksghvqc.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtntqjwcxs.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gtanltxusl.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gthnxristm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yvedp.cn/Article/details/gtohgdomsk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtvbacqewj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gthwepglpt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtcemptvif.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gttgetbmch.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtzougling.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gtfqpaqzve.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtdiulzchz.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gttijqkdhh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gttaqvttzs.html

[U04] Py：变量调试打印
来源：http://dali.cashguo.top/Article/details/gtmknibsth.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gaohongyu789.top/Article/details/gttzfoqxal.html

[U05] Py：列表去重且保序
来源：http://dali.snrcjt.cn/Article/details/gtjybgpvdc.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtgwjenler.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtheivgtro.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtrxmcwwqh.html

[U07] Py：反转字典键值
来源：http://dali.hfpthk.cn/Article/details/gtrlaabkio.html

{v: k for k, v in d.items()}
来源：http://dali.daxiang520.top/Article/details/gtwpytynsv.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtnvryceej.html

[y for x in nested for y in x]
来源：http://dali.fengsongda.top/Article/details/gtrinykzhv.html

[U09] Py：字典取最大值的键
来源：http://dali.aibaodan.cn/Article/details/gtlsilqwif.html

max(d, key=d.get)
来源：http://dali.gzhubu.top/Article/details/gtdvykcgfz.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtczeqbtfo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gtbptcmequ.html

[U11] Py：生成器表达式
来源：http://dali.sxryk.cn/Article/details/gtiwdvhhfc.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyjjylia.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gthsuhobtv.html

Counter(arr).most_common(3)
来源：http://dali.smart0.xyz/Article/details/gtyedjwoxl.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtkbaaxfol.html

deque(maxlen=10)
来源：http://dali.jianghu66.top/Article/details/gtuwfyluil.html

[U14] Py：分组收集到列表
来源：http://dali.xinyue.icu/Article/details/gtrcietcqh.html

defaultdict(list)
来源：http://dali.hnxiangtu.top/Article/details/gtmibdwxqk.html

[U15] Py：高精度计时
来源：http://dali.yj20258888.top/Article/details/gtzlvddlms.html

t = time.perf_counter()
来源：http://dali.316326.xyz/Article/details/gtkhdbuuxr.html

[U16] Py：命令行参数解析
来源：http://dali.tianlin.xyz/Article/details/gtjfeodfgl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.aibaodan.cn/Article/details/gtgttuqbpb.html

[U17] Py：初始化日志
来源：http://dali.jlsjyb.cn/Article/details/gtjrhzvprk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtugbufcjk.html

[U18] Py：预编译正则
来源：http://dali.zhixingplan.top/Article/details/gtahnvnieu.html

pat = re.compile(r"\d+")
来源：http://dali.shzxlz.cn/Article/details/gtcfftlmeh.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtmnoaacfk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sufxvd.cn/Article/details/gtwuoyjtvc.html

[U20] Py：缓存函数结果
来源：http://dali.ybcxt.top/Article/details/gtkoogqdkj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dianchejie.cn/Article/details/gtpnsrctxm.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gthfaeyexc.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gtgkpewarr.html

[U22] Py：矩阵转置
来源：http://dali.aibaodan.cn/Article/details/gtsyolycqx.html

list(zip(*m))
来源：http://dali.hysaishi.cn/Article/details/gtxpycglna.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gtprxyight.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yj20258888.top/Article/details/gtblflryek.html

[U24] Py：路径操作
来源：http://dali.jiagoushi.top/Article/details/gtjjsxnaza.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ivvv.top/Article/details/gtxjbzuxsk.html

[U25] Py：CSV 按字典读
来源：http://dali.pycfn.com/Article/details/gtnfpuhyax.html

csv.DictReader(f)
来源：http://dali.yongpay.top/Article/details/gtzicrffdg.html

[U26] Py：并发下载
来源：http://dali.yanxiufei.cn/Article/details/gtkqpiwylv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cheryme.top/Article/details/gthgnijwgl.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gtfmpwjzvg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gtbhsihdfr.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtlsyusekz.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gtsisyveie.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gtymuhwnbb.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtdcusqoip.html

[U30] Py：数据类
来源：http://dali.sxryk.cn/Article/details/gtncxintnm.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtrdkxlvxz.html

[U31] Py：单测
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgwpwhul.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gteebynxzu.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gtafuxxejx.html

ruff format . && ruff check --fix .
来源：http://dali.feifeiyinyue.top/Article/details/gtddnijlyr.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtwmqfmxyy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtohjgltve.html

[U34] Py：判断编码
来源：http://dali.guannengcc.top/Article/details/gtfqwzeiui.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gtjpyyvkxh.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtggifukdd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchdyryin.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gtwqgsxcdk.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtgigkjaui.html

[U37] Py：读写 Excel
来源：http://dali.jqgfzy.top/Article/details/gtodaickmz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gtvkgrcmfl.html

[U38] Py：获取脚本所在目录
来源：http://dali.c1oappe.top/Article/details/gtphwwuttq.html

Path(__file__).resolve().parent
来源：http://dali.shanyushiyangtech.top/Article/details/gtggmjopmv.html

[U39] Py：判断是否在交互环境
来源：http://dali.sweek.top/Article/details/gtmeefachf.html

sys.stdout.isatty()
来源：http://dali.sxryk.cn/Article/details/gtuzfdqsxy.html

[U40] Py：打印到标准错误
来源：http://dali.gzhubu.top/Article/details/gtptwhfjml.html

print("err", file=sys.stderr)
来源：http://dali.zhijiandao.cn/Article/details/gtgzkvqdnw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gtrnltevkt.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenjidiqi.icu/Article/details/gtrjmdeutx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtziikjxgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfvheveyd.html

[U43] PHP：声明命名空间
来源：http://dali.guowangkeji.top/Article/details/gtfjzysswe.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtoorgeqop.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtadqbsbob.html

declare(strict_types=1);
来源：http://dali.yangfankeji.com/Article/details/gtbckwngit.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ppjwa.cn/Article/details/gtbucjluja.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtnkxeapbb.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gtjdoqugxy.html

?string $name = null
来源：http://dali.haohaochexian.top/Article/details/gtpkipuzbk.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gtqsbqgznj.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtplrhlkho.html

[U48] PHP：纯枚举
来源：http://dali.haohaochexian.top/Article/details/gtpajwzgfh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gtnaoydpgk.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gtgwcqmgkk.html

public readonly string $name
来源：http://dali.ppjwa.cn/Article/details/gtuywglgtu.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gtumxyxhsg.html

public function __construct(private int $id) {}
来源：http://dali.hysaishi.cn/Article/details/gtvtxtyxys.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtinrcywzf.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtwkenomdi.html

[U52] PHP：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gtbknilaxc.html

$double = fn($x) => $x * 2;
来源：http://dali.gogol.net.cn/Article/details/gtxgczprnf.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtyoaibfdf.html

$v = $a ?? $b ?? "default";
来源：http://dali.daxiang520.top/Article/details/gtukjpkocx.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtjncbeslv.html

$obj?->method()
来源：http://dali.hnxiangtu.top/Article/details/gtlcdxylrx.html

[U55] PHP：match 表达式
来源：http://dali.wangdashe.top/Article/details/gtjjhdihlo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtgyzwifxg.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtvetfqvfu.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgwiwjxr.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtuqrnajnj.html

"值: {$a}"
来源：http://dali.jlsjyb.cn/Article/details/gtkksuuvsw.html

[U58] PHP：数组三件套
来源：http://dali.yangfankeji.com/Article/details/gtlzqnvnci.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtwsrwhdtw.html

[U59] PHP：自定义排序
来源：http://dali.nanxuanxn.top/Article/details/gtahamtqhu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hammf.cn/Article/details/gtkbytdsrz.html

[U60] PHP：JSON 编解码
来源：http://dali.hywenlv.cn/Article/details/gtfttyxchw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cheryme.top/Article/details/gtwabjbgbh.html

[U61] PHP：正则
来源：http://dali.hongshengwenyu.top/Article/details/gtjlckusob.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gtffjgkgyx.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gtywbodzgm.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hfpthk.cn/Article/details/gtmxfdspzx.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtznasqeso.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cheryme.top/Article/details/gtrnnhkjqd.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gtzugwmvma.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yongpay.top/Article/details/gtsdqlhtgr.html

[U65] PHP：会话
来源：http://dali.yj202588.top/Article/details/gtxxjeugyc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtbcupkdyq.html

[U66] PHP：设置 Cookie
来源：http://dali.cheryme.top/Article/details/gteblegqxi.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gtpimoqist.html

[U67] PHP：处理文件上传
来源：http://dali.xuetiantiany.cn/Article/details/gtrfyykdfj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.aizwys.cn/Article/details/gtneezqehb.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gtvvyeqdqi.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sysykeji.top/Article/details/gtrxjjqwyi.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtsdecklyd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtihtzknaa.html

[U70] PHP：PDO 事务
来源：http://dali.daria6918.cn/Article/details/gtqwayxoqg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ivvv.top/Article/details/gtlnsppiwo.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtzzdvwjel.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gtuntvnact.html

[U72] PHP：写错误日志
来源：http://dali.jinqigufen.top/Article/details/gtaqimfouz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yanxiufei.cn/Article/details/gtfmuiqoue.html

[U73] PHP：读取 ini 配置
来源：http://dali.daria6918.cn/Article/details/gtgvxosnlu.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtoaszwszh.html

[U74] PHP：读取环境变量
来源：http://dali.hongshengwenyu.top/Article/details/gtphgpbeqj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtqzntobjv.html

[U75] PHP：依赖注入
来源：http://dali.daxiang520.top/Article/details/gtmqpkhoph.html

composer require psr/container
来源：http://dali.fzhhl.top/Article/details/gtojqtemwv.html

[U76] PHP：简单路由
来源：http://dali.yj20258888.top/Article/details/gtomgdzwkg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sysykeji.top/Article/details/gtvbmitjqd.html

[U77] PHP：模板渲染
来源：http://dali.sxryk.cn/Article/details/gtvlgiwmmm.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gttupqfrqe.html

[U78] PHP：单元测试
来源：http://dali.wangshuangyany.cn/Article/details/gthlzaihbi.html

composer require --dev phpunit/phpunit
来源：http://dali.smart0.xyz/Article/details/gtgpajfjyp.html

[U79] PHP：静态分析
来源：http://dali.havefunace.top/Article/details/gtgdmdgajm.html

composer require --dev phpstan/phpstan
来源：http://dali.zhijiandao.cn/Article/details/gtvnmijqwl.html

[U80] PHP：代码规范修复
来源：http://dali.guowangkeji.top/Article/details/gtlitrkbgs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ydzc1.top/Article/details/gteihcoorw.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gtpphzdmxj.html

npm init -y;  npm i express
来源：http://dali.xinyue.icu/Article/details/gtakcesanb.html

[U82] JS：package.json 脚本
来源：http://dali.cashguo.top/Article/details/gtkmsvkook.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gthlqkposm.html


<!-- 参考信息 -->