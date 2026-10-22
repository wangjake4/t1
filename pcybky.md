代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gt2jvnqgovf.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gt2aarpywty.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2yqibpzfr.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2rsvcatft.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gt2kvevcgqm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gt2bmjfzkdd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gt2ypwjtzti.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmyvstkp.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2euackiiz.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2aptkcdub.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gt2ogntocer.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gt2cspgkxuy.html

[T03] Kotlin：字符串模板
来源：http://dali.hongshengwenyu.top/Article/details/gt2nzpzobbn.html

"值: $b"
来源：http://dali.yj20258.top/Article/details/gt2vsdkpzby.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2rzpodxao.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gt2ubjnqmmm.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gt2emqbkpnb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xinyue.icu/Article/details/gt2ruvnplnn.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2ghbbtmxm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gt2wasnucec.html

[T07] Kotlin：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gt2cebkpens.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ahajmiia.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gt2tmfzafbr.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gt2xqdkuman.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2lkysroiz.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gt2pdkxyxmh.html

[T10] Kotlin：默认参数
来源：http://dali.xinyue.icu/Article/details/gt2gvsbxkea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gt2xeersvdi.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gt2rlssahny.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhijiandao.cn/Article/details/gt2iukyjfuv.html

[T12] Kotlin：解构声明
来源：http://dali.yvedp.cn/Article/details/gt2snxdbqud.html

val (a, b) = Pair(1, 2)
来源：http://dali.chenlongwang.top/Article/details/gt2qwfecfyv.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gt2caoxbkym.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2crenftcv.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gt2kfqedhen.html

for (i in 1..10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gt2ycrbujil.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gt2mlkplvcd.html

interface Shape { fun area(): Double }
来源：http://dali.ydzc1.top/Article/details/gt2zwmpmzxe.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2sdbrxgjy.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qofvghka.html

[T17] Swift：变量与常量
来源：http://dali.hysaishi.cn/Article/details/gt2qkukemmu.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2nrkhciaq.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rcbjcgmt.html

"值: \(b)"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zqverpsk.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2ykjprcpi.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gt2ccrswukn.html

[T20] Swift：数组操作
来源：http://dali.pycfn.com/Article/details/gt2sbeznrxp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.redwolf501.top/Article/details/gt2neavfutx.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gt2pcxregwg.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gt2pfcfzjip.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2mcwbvluu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gt2ghkmfjol.html

[T23] Swift：函数
来源：http://dali.jyoumei.cn/Article/details/gt2zqrlgbuz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuanzx.com/Article/details/gt2dzhbootk.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gt2bzxavlcg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gt2txdmyvfh.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gt2ytpirfln.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gt2fzkcvccu.html

[T26] Swift：类与重写
来源：http://dali.gaohongyu789.top/Article/details/gt2nmvaueci.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gt2blaxifev.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gt2inmtwiqj.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gt2kylgnlzf.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2smwduinp.html

enum Color { case red, green }
来源：http://dali.mhx1999.top/Article/details/gt2ohxcyoce.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gt2zvcmmhrp.html

guard let x = opt else { return }
来源：http://dali.cucudq.cn/Article/details/gt2ebtxuuit.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gt2btdfuwrb.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcbclrns.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2kyoonlna.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2rmmmpdlf.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gt2kuvuvcrp.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2csacscuf.html

[T33] Lua：表（数组）
来源：http://dali.nwbrower.top/Article/details/gt2plbpncld.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gt2awaxmzjp.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gt2hbayivgm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gt2azsfmoiv.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gt2pxxlzqlx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gt2vuvabgps.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pqvdwvmb.html

function add(a, b) return a + b end
来源：http://dali.xuetiantiany.cn/Article/details/gt2hcxjsvhd.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gt2cjlbkqsc.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2zgwwxxrk.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gt2dutxqgds.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gt2gmbqubjc.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gt2ejbspksr.html

string.find(s, "%d+")
来源：http://dali.wangdashe.top/Article/details/gt2yxwrebzu.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gt2vlaaisrj.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gt2zugftnms.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2eycbjqtn.html

print "Hello\n";
来源：http://dali.cqqwz.cn/Article/details/gt2groczlva.html

[T42] Perl：变量类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2lprxoxjh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sufxvd.cn/Article/details/gt2eldmsexf.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2sewxzjcb.html

"值: $a"
来源：http://dali.xuetiantiany.cn/Article/details/gt2mxcphxqv.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2klqdialz.html

if ($a > 0) { print "正"; }
来源：http://dali.sweek.top/Article/details/gt2xwyhpugn.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2itxrfszg.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gt2ynkvunvd.html

[T46] Perl：哈希操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nlffagiz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gt2habdhyax.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gt2dlzegvsh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2vuiumcgl.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2ukxtykgt.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gt2gpvpmuku.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gt2qvfnulbv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2dwmyngrq.html

[T50] Perl：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhjxjrpz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cashguo.top/Article/details/gt2zwncxucq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gt2nvmndiyj.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2iugymwar.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gt2calsjvwz.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gt2ulfdjrgw.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gt2dtgebzbi.html

[T53] Scala：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gt2fnyfmyoc.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gt2lqgvfmtq.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2jmoicktd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2ywuevudt.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2mamsxjht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbhtanxg.html

[T56] Scala：样例类
来源：http://dali.kuanghao11.cn/Article/details/gt2raswqmco.html

case class User(name: String, age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2gaazgxbv.html

[T57] Scala：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2kmcrjqkt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dywampqn.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2gqwwwrfv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shangyingyoupin.top/Article/details/gt2gdcxigtr.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gt2gjhydoaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2bujeusqf.html

[T60] Scala：折叠
来源：http://dali.zycfv.cn/Article/details/gt2zkymkxkq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sweek.top/Article/details/gt2cazffnnp.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2bgaevdbb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gt2alhyudri.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oyesokjs.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gt2krumdemk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gt2zuxbmfij.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2neevjelr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rrqpbfms.html

[U03] Py：加载 .env 配置
来源：http://dali.hfpthk.cn/Article/details/gt2vmvacuhr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hywenlv.cn/Article/details/gt2ucffuwdq.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gt2yohcozfq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gt2ojwcjwnr.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkhxynkj.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gt2eyxiwzeq.html

[U06] Py：合并两个字典
来源：http://dali.nwbrower.top/Article/details/gt2ipgtjbhk.html

{**a, **b}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nkttreas.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ksbwwevf.html

{v: k for k, v in d.items()}
来源：http://dali.xylfe.cn/Article/details/gt2xzlystmi.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gt2tvmpriva.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gt2nedlmdrb.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gt2mzqsaxhs.html

max(d, key=d.get)
来源：http://dali.daxiang520.top/Article/details/gt2sffubqyb.html

[U10] Py：按值排序字典
来源：http://dali.snrcjt.cn/Article/details/gt2xtqvufxy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2uszsmbmi.html

[U11] Py：生成器表达式
来源：http://dali.nwbrower.top/Article/details/gt2ljwhnjdj.html

(x * 2 for x in arr)
来源：http://dali.jqgufenzy.top/Article/details/gt2djoepunw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yvedp.cn/Article/details/gt2dckojesx.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2oemmukmw.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gt2tipfeeeb.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lgtgsfqa.html

[U14] Py：分组收集到列表
来源：http://dali.gotoacloud.top/Article/details/gt2fqgumkhb.html

defaultdict(list)
来源：http://dali.ppjwa.cn/Article/details/gt2maumzemt.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gt2doripkhr.html

t = time.perf_counter()
来源：http://dali.ybcxt.top/Article/details/gt2healtcmc.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gt2yzltyewq.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.0kj1m.cn/Article/details/gt2uzkkeifg.html

[U17] Py：初始化日志
来源：http://dali.9152youxi.cn/Article/details/gt2grwlgvfe.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gt2kakqrkxf.html

[U18] Py：预编译正则
来源：http://dali.ehwqpu.com/Article/details/gt2ooqxbkzb.html

pat = re.compile(r"\d+")
来源：http://dali.316326.xyz/Article/details/gt2fbwobhrr.html

[U19] Py：正则替换带回调
来源：http://dali.cheryme.top/Article/details/gt2dtpwzjcd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hongshengwenyu.top/Article/details/gt2fsabplvw.html

[U20] Py：缓存函数结果
来源：http://dali.redwolf501.top/Article/details/gt2bktpkofz.html

@functools.lru_cache(maxsize=None)
来源：http://dali.daxiang520.top/Article/details/gt2kqdfjdax.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gt2qpsrxhiu.html

@contextlib.contextmanager
来源：http://dali.yj20258888.top/Article/details/gt2jcajdkfx.html

[U22] Py：矩阵转置
来源：http://dali.yj20258.top/Article/details/gt2txwidzyo.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gt2sohgalhe.html

[U23] Py：分块读取大文件
来源：http://dali.haohaochexian.top/Article/details/gt2kztwpjvn.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.quarkkingdee.top/Article/details/gt2rehqgdxs.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gt2wkwhxzlw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gt2xzsjlahw.html

[U25] Py：CSV 按字典读
来源：http://dali.haohaochexian.top/Article/details/gt2husdaras.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gt2bqsideyz.html

[U26] Py：并发下载
来源：http://dali.sweek.top/Article/details/gt2buumunro.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jiagoushi.top/Article/details/gt2segguzpy.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gt2hqimswqt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.andypj.xyz/Article/details/gt2pxkhorjp.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gt2odoeqjeg.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gt2savhylek.html

[U29] Py：属性校验
来源：http://dali.jinqigufen.top/Article/details/gt2egxyetvs.html

@property 与 @x.setter 配合
来源：http://dali.nanxinkj.top/Article/details/gt2jwriavnw.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gt2brjzuxoq.html

@dataclass(slots=True)
来源：http://dali.jianghu66.top/Article/details/gt2ftnekhcq.html

[U31] Py：单测
来源：http://dali.xuetiantiany.cn/Article/details/gt2hjcthqpy.html

python -m pytest -q
来源：http://dali.andypj.xyz/Article/details/gt2zaxxggwp.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gt2brlismad.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gt2rhxrvkhb.html

[U33] Py：打包发布
来源：http://dali.sweek.top/Article/details/gt2ycnctdwz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gt2dyjzgzmi.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gt2wysprhvc.html

chardet.detect(raw)
来源：http://dali.zhengqikj.top/Article/details/gt2gqsrzlif.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2nnchkntd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gt2xgvgdcqc.html

[U36] Py：定时任务
来源：http://dali.sweek.top/Article/details/gt2lzobytus.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gt2jwumoqxq.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gt2gzzmfdhd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yonumen.top/Article/details/gt2lnjfieto.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gt2vbxjrxhc.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gt2fmnkmcwj.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2bclxhpil.html

sys.stdout.isatty()
来源：http://dali.jianghu66.top/Article/details/gt2juoibhjn.html

[U40] Py：打印到标准错误
来源：http://dali.xziqi.cn/Article/details/gt2jznbrdjc.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gt2niobcgbz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhoulong.xyz/Article/details/gt2lutqhsol.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gt2lzfedvaq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.smart0.xyz/Article/details/gt2ymlmgqdm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2pvwwjkkm.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2uvawojuy.html

namespace App\Http;
来源：http://dali.daria6918.cn/Article/details/gt2otkxoqnw.html

[U44] PHP：开启严格类型
来源：http://dali.hfpthk.cn/Article/details/gt2nmktbklf.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gt2fvjsgjmi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gt2jnjagyki.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgushnrd.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2twuuekmx.html

?string $name = null
来源：http://dali.yuxming.cn/Article/details/gt2zvdaloue.html

[U47] PHP：联合类型
来源：http://dali.yuxming.cn/Article/details/gt2dreywnqp.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gt2kjekvirr.html

[U48] PHP：纯枚举
来源：http://dali.quarkkingdee.top/Article/details/gt2glapvdty.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhprkwyd.html

[U49] PHP：只读属性
来源：http://dali.svipenyu.cn/Article/details/gt2tjegbaqw.html

public readonly string $name
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zisuiufp.html

[U50] PHP：构造器属性提升
来源：http://dali.redwolf501.top/Article/details/gt2vryrucvj.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gt2xjmkmvns.html

[U51] PHP：数组解构
来源：http://dali.tanke756.top/Article/details/gt2lsszeprp.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gt2ebejvohh.html

[U52] PHP：箭头函数
来源：http://dali.tian-w.cn/Article/details/gt2bciikgmd.html

$double = fn($x) => $x * 2;
来源：http://dali.tianlin.xyz/Article/details/gt2vnulpple.html

[U53] PHP：空合并运算符
来源：http://dali.yanxiufei.cn/Article/details/gt2grqnekmo.html

$v = $a ?? $b ?? "default";
来源：http://dali.sufxvd.cn/Article/details/gt2aszaqjfl.html

[U54] PHP：空安全调用
来源：http://dali.ivvv.top/Article/details/gt2seqggwfi.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gt2wtkevjik.html

[U55] PHP：match 表达式
来源：http://dali.316326.xyz/Article/details/gt2cnnzztsz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2aagcnvhh.html

[U56] PHP：命名参数
来源：http://dali.dianchejie.cn/Article/details/gt2gbarslmb.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2qahwqpgk.html

[U57] PHP：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qzlbakez.html

"值: {$a}"
来源：http://dali.yuxming.cn/Article/details/gt2jwgsfkjh.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gt2jygmkqws.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dwzdirjs.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gt2vpulnsxn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.andypj.xyz/Article/details/gt2tqeubaqm.html

[U60] PHP：JSON 编解码
来源：http://dali.yangfankeji.com/Article/details/gt2ovnvgbqv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gt2qgpmpaye.html

[U61] PHP：正则
来源：http://dali.dashuyun.cn/Article/details/gt2ucubuisk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.snrcjt.cn/Article/details/gt2fwatekhb.html

[U62] PHP：日期对象
来源：http://dali.birdmap.top/Article/details/gt2fhuqdsus.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rdgefwax.html

[U63] PHP：文件读写
来源：http://dali.meibo888.top/Article/details/gt2dtgvamxp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yangfankeji.com/Article/details/gt2tnnhyigp.html

[U64] PHP：目录遍历
来源：http://dali.zhixingplan.top/Article/details/gt2drveaixe.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.aizwys.cn/Article/details/gt2npsmpgmm.html

[U65] PHP：会话
来源：http://dali.fzhhl.top/Article/details/gt2wlhjmwdi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2tjukbxeb.html

[U66] PHP：设置 Cookie
来源：http://dali.guannengcc.top/Article/details/gt2asslaqym.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gt2hrgtlibf.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gt2lqcjnnjd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.316326.xyz/Article/details/gt2zdbqaboo.html

[U68] PHP：PDO 连接
来源：http://dali.yuanzhike.top/Article/details/gt2xvavuddh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gt2yahhpygb.html

[U69] PHP：PDO 预处理
来源：http://dali.316326.xyz/Article/details/gt2qebwamet.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oioidosy.html

[U70] PHP：PDO 事务
来源：http://dali.nanxinkj.top/Article/details/gt2jwcdnbxf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.9152youxi.cn/Article/details/gt2ccfembir.html

[U71] PHP：抛出异常
来源：http://dali.aibaodan.cn/Article/details/gt2wnnnergd.html

throw new RuntimeException("失败", 500);
来源：http://dali.fengsongda.top/Article/details/gt2ftaoraby.html

[U72] PHP：写错误日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jgmhxtpt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.guowangkeji.top/Article/details/gt2aotmudka.html

[U73] PHP：读取 ini 配置
来源：http://dali.tianlin.xyz/Article/details/gt2jkyorcfs.html

parse_ini_file("config.ini", true)
来源：http://dali.cdnleiting.top/Article/details/gt2vobvplci.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gt2mkrojtet.html

getenv("APP_ENV") ?: "production"
来源：http://dali.pengpengdd.cyou/Article/details/gt2lsmgoszh.html

[U75] PHP：依赖注入
来源：http://dali.shzxlz.cn/Article/details/gt2aseiowwe.html

composer require psr/container
来源：http://dali.jiagoushi.top/Article/details/gt2sgblfror.html

[U76] PHP：简单路由
来源：http://dali.pengpengdd.cyou/Article/details/gt2srollkxw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gt2nvysgivu.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gt2etanubbh.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gt2jvlhwdnp.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gt2xxrojbcd.html

composer require --dev phpunit/phpunit
来源：http://dali.yuxming.cn/Article/details/gt2nxecdgho.html

[U79] PHP：静态分析
来源：http://dali.yongpay.top/Article/details/gt2grtdvhgh.html

composer require --dev phpstan/phpstan
来源：http://dali.xylfe.cn/Article/details/gt2eentfvxq.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gt2faxqwwkv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2cabxkzsc.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gt2xhzkwhty.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gt2jbxkyeyh.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gt2whfvcwfx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yanxiufei.cn/Article/details/gt2avfwipea.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gt2anvrxgsk.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2wgubdzez.html

[U84] JS：CommonJS 写法
来源：http://dali.316326.xyz/Article/details/gt2ngciowak.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gt2azheuppe.html


<!-- 参考信息 -->