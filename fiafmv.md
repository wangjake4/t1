代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2sabhdbfc.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gt2ibiufjxc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hfpthk.cn/Article/details/gt2btzexwac.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2wlqxwdjj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2kafheeya.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2skfmyltn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yonumen.top/Article/details/gt2ohjnukwm.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2eavhmnzg.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2tcvtgemp.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2flstpyxh.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2bqwoqriw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gt2hnbkkpxk.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gt2smxzufcp.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gt2ruehzswm.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gt2sapjqefi.html

val n: String? = null;  n?.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjrtvewj.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gt2tebnvehf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gt2tpcvekml.html

[T06] Kotlin：集合映射
来源：http://dali.yvedp.cn/Article/details/gt2ipardlnp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dsbsurdj.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gt2ypyubcvi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gt2bzeanbau.html

[T08] Kotlin：数据类
来源：http://dali.zycfv.cn/Article/details/gt2okokkilo.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2neetobuj.html

[T09] Kotlin：扩展函数
来源：http://dali.sysykeji.top/Article/details/gt2xwhgfbda.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gt2gdajopis.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gt2tdexgyno.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuxming.cn/Article/details/gt2ayarlkqh.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gt2ytvzqzmv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jyoumei.cn/Article/details/gt2welaqyso.html

[T12] Kotlin：解构声明
来源：http://dali.vqdsnc.cn/Article/details/gt2enwtbkbe.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gt2ewzwqxfn.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gt2dbcffgja.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gt2blmhzelg.html

[T14] Kotlin：循环
来源：http://dali.guowangkeji.top/Article/details/gt2fqwwhouz.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gt2fdxngdhl.html

[T15] Kotlin：接口
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qzintnro.html

interface Shape { fun area(): Double }
来源：http://dali.yanxiufei.cn/Article/details/gt2wipvplvo.html

[T16] Swift：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ifofonbz.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2ojntxblu.html

[T17] Swift：变量与常量
来源：http://dali.zhoulong.xyz/Article/details/gt2xwztwvcy.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gt2vnteupzm.html

[T18] Swift：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2iuhgjwco.html

"值: \(b)"
来源：http://dali.gzhubu.top/Article/details/gt2cyvolaiw.html

[T19] Swift：可选绑定
来源：http://dali.ydzc1.top/Article/details/gt2goexkbbj.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnxmlkbb.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gt2zlhwxsvn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sweek.top/Article/details/gt2pbfacwqf.html

[T21] Swift：遍历
来源：http://dali.jinqigfzy.top/Article/details/gt2tvskckyv.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gt2plmojxgu.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gt2ewywoxkl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gt2nnwcvggv.html

[T23] Swift：函数
来源：http://dali.hywenlv.cn/Article/details/gt2pzdcnfrg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.snrcjt.cn/Article/details/gt2nzrehnhj.html

[T24] Swift：闭包
来源：http://dali.shuidangran.top/Article/details/gt2grsacvhm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2lezvvduw.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gt2apyfpuav.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gt2ulaukhhu.html

[T26] Swift：类与重写
来源：http://dali.jyoumei.cn/Article/details/gt2titblhzp.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gt2actmlkdk.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2ynxuwdhb.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gt2bthvszjq.html

[T28] Swift：枚举
来源：http://dali.jiagoushi.top/Article/details/gt2cwmmrjgz.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gt2kikkwrwz.html

[T29] Swift：guard 提前返回
来源：http://dali.wangdashe.top/Article/details/gt2zqoxwdzw.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jtzkyrvh.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gt2ayjhchvj.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gt2ryhpkmaf.html

[T31] Lua：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2gahlckzr.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gt2jrrxicss.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gt2badtzbmz.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gt2atdxrinm.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gt2pkessris.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gt2doahhxyd.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gt2nxtuaxjp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gt2jyttcpmj.html

[T35] Lua：字典表
来源：http://dali.wangshuangyany.cn/Article/details/gt2szuvcitq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gt2bjmqpqwo.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2uigmxzoc.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gt2zsyttsma.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2flguvgqm.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gt2zakeeing.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2uifcsabn.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dynspkyh.html

[T39] Lua：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gt2imszydnm.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gt2hcjxrskk.html

[T40] Lua：元表
来源：http://dali.mhx1999.top/Article/details/gt2kxxkrmak.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gt2aecfcpok.html

[T41] Perl：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2qjtyxdtu.html

print "Hello\n";
来源：http://dali.hfpthk.cn/Article/details/gt2grsazekr.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gt2ksxkzcwd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cdnleiting.top/Article/details/gt2trljmcye.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gt2hjificby.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbmfbtqd.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gt2nraohjio.html

if ($a > 0) { print "正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rlizfmop.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gt2gouokdbl.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2qzbafwkj.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txjxdztx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gt2pqlgyefh.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gt2wnjbzxma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2filkqwwn.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gt2gzorwklc.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nmpavxja.html

[T49] Perl：函数
来源：http://dali.hammf.cn/Article/details/gt2vxdkdhvb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gt2udsyvrad.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2znimlxfm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gt2mtvdknqi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2twzwruee.html

[T51] Scala：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2altzsjlq.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2uyesucln.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2cfgwmlhb.html

val a = 1;  var b = 2
来源：http://dali.daxiang520.top/Article/details/gt2vvcmlqvn.html

[T53] Scala：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2ipzribrl.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2nbeicxym.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2guvdulgn.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxinkj.top/Article/details/gt2aqktuvwq.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gt2djopytuy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yj202588.top/Article/details/gt2msmymhkf.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gt2vpyaqerj.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2qrarglfm.html

[T57] Scala：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2spkxsdkd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2lusfgyww.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gt2hwwecybt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2ijztlgoe.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gt2ilvcekbl.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2pnvpsrzi.html

[T60] Scala：折叠
来源：http://dali.chenjidiqi.icu/Article/details/gt2uznhpmty.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gt2elepgeas.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2owqnjtqq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2vjqsvjbo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2cyhrokne.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2suujlrny.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2wyvwyaqu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shzxlz.cn/Article/details/gt2oinbkikb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.kuanghao11.cn/Article/details/gt2gpfqmehl.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gt2ywnluxdp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gt2omfltywp.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gt2mzufpfcc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.havefunace.top/Article/details/gt2xavsjlsn.html

[U05] Py：列表去重且保序
来源：http://dali.sweek.top/Article/details/gt2iiyyioyc.html

list(dict.fromkeys(arr))
来源：http://dali.yvedp.cn/Article/details/gt2ursdtftp.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gt2naqujnih.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vscddvfl.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xihkehhw.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gt2zyacjkjj.html

[U08] Py：展平二维列表
来源：http://dali.sufxvd.cn/Article/details/gt2okfctfse.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gt2cobhktio.html

[U09] Py：字典取最大值的键
来源：http://dali.daria6918.cn/Article/details/gt2bqvcdslz.html

max(d, key=d.get)
来源：http://dali.aizwys.cn/Article/details/gt2gbpsltkn.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gt2hschqqny.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinqigfzy.top/Article/details/gt2otkaeklv.html

[U11] Py：生成器表达式
来源：http://dali.cdnleiting.top/Article/details/gt2luydeivv.html

(x * 2 for x in arr)
来源：http://dali.pengpengdd.cyou/Article/details/gt2aqageaje.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gt2uhjtfkeu.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gt2mslofgxd.html

[U13] Py：固定长度队列
来源：http://dali.wangdashe.top/Article/details/gt2ziygpkdy.html

deque(maxlen=10)
来源：http://dali.dashuyun.cn/Article/details/gt2tinjyqtm.html

[U14] Py：分组收集到列表
来源：http://dali.jianghu66.top/Article/details/gt2buawknzq.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2waegwazr.html

[U15] Py：高精度计时
来源：http://dali.316326.xyz/Article/details/gt2fczesfzk.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2qlpbzwsi.html

[U16] Py：命令行参数解析
来源：http://dali.ppjwa.cn/Article/details/gt2yslydibi.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2myxviilb.html

[U17] Py：初始化日志
来源：http://dali.dashuyun.cn/Article/details/gt2ixchtceh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yj20258.top/Article/details/gt2mryilcoe.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gt2tufpbvsp.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gt2pijommmb.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gt2grkugcxw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigufen.top/Article/details/gt2vwepnsfe.html

[U20] Py：缓存函数结果
来源：http://dali.zhengqikj.top/Article/details/gt2bsmczjql.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ybcxt.top/Article/details/gt2hwcekxtj.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gt2vsxirntd.html

@contextlib.contextmanager
来源：http://dali.hywenlv.cn/Article/details/gt2rqehqqao.html

[U22] Py：矩阵转置
来源：http://dali.0kj1m.cn/Article/details/gt2jqjpyvwf.html

list(zip(*m))
来源：http://dali.cashguo.top/Article/details/gt2ardioimn.html

[U23] Py：分块读取大文件
来源：http://dali.nanxinkj.top/Article/details/gt2tcyhmksv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gvcshzbj.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gt2efndmpey.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2bzsxwbif.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gt2cxlebzct.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lxxlqinp.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gt2gdohocfr.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.sweek.top/Article/details/gt2jxfxztkz.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gt2sjtuqbwa.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gt2eymjawjx.html

[U28] Py：类型别名
来源：http://dali.chenzaomai.com/Article/details/gt2nycuqkkq.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gt2kfpcbcix.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gt2bcophxxi.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gt2tzhzriza.html

[U30] Py：数据类
来源：http://dali.mhx1999.top/Article/details/gt2dpiwtkxy.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ebbsgwoc.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gt2xpsfsiwv.html

python -m pytest -q
来源：http://dali.cashguo.top/Article/details/gt2lskrzpsb.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gt2joclrhsg.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gt2ptgkhkke.html

[U33] Py：打包发布
来源：http://dali.hnqzz.top/Article/details/gt2hpqjmcvn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.pengpengdd.cyou/Article/details/gt2orwadzji.html

[U34] Py：判断编码
来源：http://dali.jyoumei.cn/Article/details/gt2eeygdarc.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gt2sdtoqelp.html

[U35] Py：发送邮件
来源：http://dali.ivvv.top/Article/details/gt2btuhdqpb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.birdmap.top/Article/details/gt2kwlkdgxl.html

[U36] Py：定时任务
来源：http://dali.wangdashe.top/Article/details/gt2nggggjoi.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gt2xnoorgrq.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gt2fppoxzzx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xinyue.icu/Article/details/gt2giztqggv.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gt2txlxqkvb.html

Path(__file__).resolve().parent
来源：http://dali.yj20258888.top/Article/details/gt2lsuahirt.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhijiandao.cn/Article/details/gt2hymijyfj.html

sys.stdout.isatty()
来源：http://dali.pengpengdd.cyou/Article/details/gt2efcdewde.html

[U40] Py：打印到标准错误
来源：http://dali.quarkkingdee.top/Article/details/gt2ydidtpsk.html

print("err", file=sys.stderr)
来源：http://dali.hfpthk.cn/Article/details/gt2dcbsviuz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nwbrower.top/Article/details/gt2inmwbeng.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.vqdsnc.cn/Article/details/gt2sqwkyrow.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xuetiantiany.cn/Article/details/gt2hzckiimv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2gdbhkqvh.html

[U43] PHP：声明命名空间
来源：http://dali.hywenlv.cn/Article/details/gt2fyvxinnk.html

namespace App\Http;
来源：http://dali.fzhhl.top/Article/details/gt2unqfqrks.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gt2oeptbegk.html

declare(strict_types=1);
来源：http://dali.chenlongwang.top/Article/details/gt2cebzzzoq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxuanxn.top/Article/details/gt2vabasigd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gvplzdkp.html

[U46] PHP：可空类型
来源：http://dali.gaohongyu789.top/Article/details/gt2unrrubuw.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gt2qtnopxer.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gt2fkzzzxns.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xoxkmyvh.html

[U48] PHP：纯枚举
来源：http://dali.hammf.cn/Article/details/gt2unzixwoy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tohjcezd.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gt2ktdqligi.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gt2fzywywyc.html

[U50] PHP：构造器属性提升
来源：http://dali.gzhubu.top/Article/details/gt2gqvborqk.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gt2pwdsekba.html

[U51] PHP：数组解构
来源：http://dali.ydzc1.top/Article/details/gt2yqyzqifh.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2trecpwsz.html

[U52] PHP：箭头函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2uebybhff.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gt2ncinffyq.html

[U53] PHP：空合并运算符
来源：http://dali.jinqigfzy.top/Article/details/gt2hcxziwmd.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gt2mugfejlw.html

[U54] PHP：空安全调用
来源：http://dali.xuanzx.com/Article/details/gt2lcdggazs.html

$obj?->method()
来源：http://dali.fzhhl.top/Article/details/gt2itotmxrt.html

[U55] PHP：match 表达式
来源：http://dali.ybcxt.top/Article/details/gt2kjzbueit.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gt2xuvdfwzg.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2fbyqrgfz.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gt2dsazutmw.html

[U57] PHP：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ggljgtfu.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gt2eduxctax.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gt2uhcvgtex.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnxiangtu.top/Article/details/gt2lrnlnste.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2egribiub.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yj20258.top/Article/details/gt2ejbmdtrk.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gt2xjpnmtit.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ivvv.top/Article/details/gt2boaspysv.html

[U61] PHP：正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yhqrusqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yuxming.cn/Article/details/gt2qzqyxfuz.html

[U62] PHP：日期对象
来源：http://dali.yj20258888.top/Article/details/gt2iuydkdnu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sufxvd.cn/Article/details/gt2hnlhlpua.html

[U63] PHP：文件读写
来源：http://dali.feifeiyinyue.top/Article/details/gt2hizxokps.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gt2rpayxkob.html

[U64] PHP：目录遍历
来源：http://dali.yongpay.top/Article/details/gt2ipjmonxb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gt2xfeehnru.html

[U65] PHP：会话
来源：http://dali.cucudq.cn/Article/details/gt2koahzqnz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2yrpbgvib.html

[U66] PHP：设置 Cookie
来源：http://dali.cashguo.top/Article/details/gt2cuundimn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gt2qvwxpset.html

[U67] PHP：处理文件上传
来源：http://dali.kuanghao11.cn/Article/details/gt2tvcufdqb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gaohongyu789.top/Article/details/gt2qpyvzznj.html

[U68] PHP：PDO 连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2kavvyiqd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gt2xdxcixqw.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gt2zdeqglvd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgfzy.top/Article/details/gt2ximrsiav.html

[U70] PHP：PDO 事务
来源：http://dali.zdqjudy.top/Article/details/gt2xiuilqln.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gt2wyfgtwlr.html

[U71] PHP：抛出异常
来源：http://dali.xylfe.cn/Article/details/gt2hjmehvwu.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gt2wzkypfci.html

[U72] PHP：写错误日志
来源：http://dali.yueranfly.top/Article/details/gt2zjqcduxb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2krpcxdot.html

[U73] PHP：读取 ini 配置
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrbuwunf.html

parse_ini_file("config.ini", true)
来源：http://dali.tianlin.xyz/Article/details/gt2zegdbftj.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2cbwhwgop.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xziqi.cn/Article/details/gt2vfhjphnp.html

[U75] PHP：依赖注入
来源：http://dali.hysaishi.cn/Article/details/gt2gbqpzrqo.html

composer require psr/container
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ftppskme.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gt2mqiainuk.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gt2hgxczeud.html

[U77] PHP：模板渲染
来源：http://dali.zycfv.cn/Article/details/gt2azirhojs.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gt2tfozgdxx.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gt2mafhztjq.html

composer require --dev phpunit/phpunit
来源：http://dali.hnxiangtu.top/Article/details/gt2ahefzwrt.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gt2bhtekgod.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258.top/Article/details/gt2hsgmziiz.html

[U80] PHP：代码规范修复
来源：http://dali.jqgufenzy.top/Article/details/gt2cfldwgiw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gt2dzqilqwu.html

[U81] JS：初始化项目
来源：http://dali.yj202588.top/Article/details/gt2npvhwbdx.html

npm init -y;  npm i express
来源：http://dali.tian-w.cn/Article/details/gt2xxlnqqhi.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gt2qqrcggbu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenlongwang.top/Article/details/gt2uzrhgcrg.html

[U83] JS：ES Module 导入导出
来源：http://dali.jinqigfzy.top/Article/details/gt2mxffzkpr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.xziqi.cn/Article/details/gt2ekevhdkw.html

[U84] JS：CommonJS 写法
来源：http://dali.jianghu66.top/Article/details/gt2prgvlinq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gt2gzgkpfuz.html


<!-- 参考信息 -->