代发 wailian999

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2aqbncwdn.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gt2lrykbxzj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmgjujts.html

[S60] C++：遍历并删除元素
来源：http://dali.vqdsnc.cn/Article/details/gt2ctfruved.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gt2pexsblyh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2tlftjoal.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenzaomai.com/Article/details/gt2tcyvrbpl.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2eyleefrn.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2jxdemdpy.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gt2qobxeluh.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gt2urkhctxa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.bjfxy.top/Article/details/gt2csmgpbta.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gt2womkonjr.html

"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrvwayrd.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gt2ohxzayzw.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gt2mpkjuniu.html

[T05] Kotlin：when 表达式
来源：http://dali.bjfxy.top/Article/details/gt2nrhvemtw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gt2duyiweha.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2kmtfrqjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gt2pqdtsqts.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2ckiuqasg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cqqwz.cn/Article/details/gt2fbvhphso.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gt2rtyhmvsw.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gt2sdegeeji.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gt2zzjfwtyw.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gt2odrtknrw.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gt2ltnsjzpd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gt2oaolptjl.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gt2uemdbjpi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xsgkylot.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2harxhiyd.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gt2qvsqkwjp.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gt2gqnfaxls.html

val m = mapOf("a" to 1)
来源：http://dali.sweek.top/Article/details/gt2apelzigy.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gt2dgahwmgl.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2vawfifua.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gt2qbquwpji.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gt2rcplexjq.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2wjyxmaer.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gt2dpzpzrgc.html

[T17] Swift：变量与常量
来源：http://dali.xuetiantiany.cn/Article/details/gt2qggxxtqd.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2vkputpin.html

[T18] Swift：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mwkonsdu.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gt2hvyrzfll.html

[T19] Swift：可选绑定
来源：http://dali.gzhubu.top/Article/details/gt2nidddfcl.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gt2tzomospa.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2cebzvgky.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.tian-w.cn/Article/details/gt2lcdwntvp.html

[T21] Swift：遍历
来源：http://dali.ehwqpu.com/Article/details/gt2tneeqbwo.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gt2idphuwot.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gt2ndjcvirk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2wixgmkpz.html

[T23] Swift：函数
来源：http://dali.sxryk.cn/Article/details/gt2ggxuwtcd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2wkntgtob.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fbhawyff.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gt2osyhbaze.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gt2ngcdlbwo.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gt2duamistk.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gt2rhrfdmxc.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gt2enopfikd.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2xiczkmdp.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2luzzwznu.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2gjrnnlol.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2ymwkiooa.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yzzzpehu.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gt2hkhwsluc.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gt2kwmzhflp.html

protocol Shape { func area() -> Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2luntxyvz.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2evhepxel.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2vionngxa.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gt2zdwlcwjl.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gt2mpntgczb.html

[T33] Lua：表（数组）
来源：http://dali.chenzaomai.com/Article/details/gt2cxqifbjt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2knvmwdox.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gt2dvanfhvm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gt2okvdjaxd.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2ebzccqzs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.redwolf501.top/Article/details/gt2vnvepclb.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2zgjsjokx.html

function add(a, b) return a + b end
来源：http://dali.fengsongda.top/Article/details/gt2zmwfpnoc.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gt2xdweuecv.html

"a" .. "b"
来源：http://dali.0kj1m.cn/Article/details/gt2ubidrngx.html

[T38] Lua：条件
来源：http://dali.daria6918.cn/Article/details/gt2tddigfzu.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gt2swpmwthp.html

[T39] Lua：模式匹配
来源：http://dali.pengpengdd.cyou/Article/details/gt2mmomcsdz.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gt2smrrdztr.html

[T40] Lua：元表
来源：http://dali.yj20258888.top/Article/details/gt2nnknpcnz.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gt2nfvidihy.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2vpqpxyud.html

print "Hello\n";
来源：http://dali.daxiang520.top/Article/details/gt2azkupiet.html

[T42] Perl：变量类型
来源：http://dali.andypj.xyz/Article/details/gt2ewszqyju.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2giwxbjkx.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2cfajrlke.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gt2vnrilytq.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2ibyveqru.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2avrjojft.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gt2ivnbnssg.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2mccbwjks.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gt2rlmrgizp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gt2akefmxus.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gt2vonnfqhr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhixingplan.top/Article/details/gt2bcrmxlvm.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gt2kkutonhy.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gt2syjfvqtt.html

[T49] Perl：函数
来源：http://dali.yongpay.top/Article/details/gt2lciljexk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gt2hyfsxuac.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gt2irecndgj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yonumen.top/Article/details/gt2puimnmwi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gt2nrvtrucz.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2yzpplgqy.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2wbgbxagy.html

[T52] Scala：变量
来源：http://dali.316326.xyz/Article/details/gt2bksjgwic.html

val a = 1;  var b = 2
来源：http://dali.gaohongyu789.top/Article/details/gt2scwarniw.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gt2hjbxiafr.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gt2wxbxovru.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2gcoexwfl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ypccqlnk.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2kjwrszau.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gt2utyapzbg.html

[T56] Scala：样例类
来源：http://dali.aibaodan.cn/Article/details/gt2tbercyvh.html

case class User(name: String, age: Int)
来源：http://dali.cdnleiting.top/Article/details/gt2iwrffmln.html

[T57] Scala：模式匹配
来源：http://dali.redwolf501.top/Article/details/gt2yxlofriu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2iavhtzwg.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gt2iivwbsiz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yanxiufei.cn/Article/details/gt2fnyxlcjw.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2utvxoxup.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gt2lsueosoo.html

[T60] Scala：折叠
来源：http://dali.jqgfzy.top/Article/details/gt2xzolzqeq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gt2cesywbbq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cavqocwr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gt2glxsntit.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2smcmcdmq.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gt2nxkcbtds.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gt2gbdmyrzt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gt2ntstsfug.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwflfraj.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gt2iwenlffb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnqzz.top/Article/details/gt2hpyhepyr.html

[U04] Py：变量调试打印
来源：http://dali.chenzaomai.com/Article/details/gt2hsqzruan.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cashguo.top/Article/details/gt2wyarmcoq.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gt2nqvtifbq.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2liuiinjn.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gt2pzagmwsr.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzyifcod.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gt2ayhxqtjs.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gt2tjweobjk.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gt2mnzhsvqp.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gt2ngkisaeg.html

[U09] Py：字典取最大值的键
来源：http://dali.xuanzx.com/Article/details/gt2lngpbhsq.html

max(d, key=d.get)
来源：http://dali.xuetiantiany.cn/Article/details/gt2efxpxtpx.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gt2nwrvfmrj.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2npcpyoov.html

[U11] Py：生成器表达式
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtyzrbol.html

(x * 2 for x in arr)
来源：http://dali.smart0.xyz/Article/details/gt2vsmrbgqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aibaodan.cn/Article/details/gt2xrztqseh.html

Counter(arr).most_common(3)
来源：http://dali.nwbrower.top/Article/details/gt2frzdfpfr.html

[U13] Py：固定长度队列
来源：http://dali.9152youxi.cn/Article/details/gt2huoocttg.html

deque(maxlen=10)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bueryesb.html

[U14] Py：分组收集到列表
来源：http://dali.cheryme.top/Article/details/gt2yxoncade.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gt2ctvfjzyl.html

[U15] Py：高精度计时
来源：http://dali.zhoulong.xyz/Article/details/gt2mfvlqvzl.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gt2ktpphwgu.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gt2aqksvsuz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.chenlongwang.top/Article/details/gt2shlzhipq.html

[U17] Py：初始化日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2devoqmfo.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gt2wylrhkbs.html

[U18] Py：预编译正则
来源：http://dali.andypj.xyz/Article/details/gt2evdglgzz.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2yfyxmral.html

[U19] Py：正则替换带回调
来源：http://dali.ehwqpu.com/Article/details/gt2plnxfilr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gt2hngslojm.html

[U20] Py：缓存函数结果
来源：http://dali.hammf.cn/Article/details/gt2yiyiknbh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sxryk.cn/Article/details/gt2blenqwia.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2zbtslrow.html

@contextlib.contextmanager
来源：http://dali.316326.xyz/Article/details/gt2qwmnpgcv.html

[U22] Py：矩阵转置
来源：http://dali.yangfankeji.com/Article/details/gt2twnavatt.html

list(zip(*m))
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofcbazpr.html

[U23] Py：分块读取大文件
来源：http://dali.0kj1m.cn/Article/details/gt2wghckzdu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gt2cmclejuw.html

[U24] Py：路径操作
来源：http://dali.mhx1999.top/Article/details/gt2phbsjctk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2plipkusn.html

[U25] Py：CSV 按字典读
来源：http://dali.havefunace.top/Article/details/gt2okcwsphb.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdicthog.html

[U26] Py：并发下载
来源：http://dali.aibaodan.cn/Article/details/gt2xabjshzi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenzaomai.com/Article/details/gt2cmrutyuf.html

[U27] Py：异步 HTTP
来源：http://dali.ehwqpu.com/Article/details/gt2hprdwucf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fzhhl.top/Article/details/gt2xjmspcyg.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gt2yaisnyrm.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gt2xqiahwzv.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gt2cxhjsmqb.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gt2tynixlyg.html

[U30] Py：数据类
来源：http://dali.guannengcc.top/Article/details/gt2yqivcvkr.html

@dataclass(slots=True)
来源：http://dali.guannengcc.top/Article/details/gt2lrugspsk.html

[U31] Py：单测
来源：http://dali.guowangkeji.top/Article/details/gt2bqkrrfum.html

python -m pytest -q
来源：http://dali.zhijiandao.cn/Article/details/gt2fqahxdke.html

[U32] Py：代码格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnxxjfjx.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gt2sfsvnfdw.html

[U33] Py：打包发布
来源：http://dali.fzhhl.top/Article/details/gt2nhbqxjsr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.snrcjt.cn/Article/details/gt2vjmifrla.html

[U34] Py：判断编码
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2diwxehmg.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gt2qneojoio.html

[U35] Py：发送邮件
来源：http://dali.ehwqpu.com/Article/details/gt2rdnmxggq.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hywenlv.cn/Article/details/gt2fitkcxbt.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2uhrqmnql.html

schedule.every(10).minutes.do(job)
来源：http://dali.316326.xyz/Article/details/gt2qszthkzg.html

[U37] Py：读写 Excel
来源：http://dali.sxryk.cn/Article/details/gt2iuihdnfe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gt2bgwawamx.html

[U38] Py：获取脚本所在目录
来源：http://dali.jqgufenzy.top/Article/details/gt2eajskujx.html

Path(__file__).resolve().parent
来源：http://dali.cdnleiting.top/Article/details/gt2jsaxmmbw.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpaqivla.html

sys.stdout.isatty()
来源：http://dali.xziqi.cn/Article/details/gt2okhzovba.html

[U40] Py：打印到标准错误
来源：http://dali.kuanghao11.cn/Article/details/gt2hzsginni.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2yfycyxzy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ydzc1.top/Article/details/gt2xaghdtvo.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenzaomai.com/Article/details/gt2hjzhauiu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shangyingyoupin.top/Article/details/gt2rlfmtxfl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ybcxt.top/Article/details/gt2neycytid.html

[U43] PHP：声明命名空间
来源：http://dali.daria6918.cn/Article/details/gt2lttqplkz.html

namespace App\Http;
来源：http://dali.ehwqpu.com/Article/details/gt2gswqcqhq.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2qjdvoffn.html

declare(strict_types=1);
来源：http://dali.gzhubu.top/Article/details/gt2tvucrynh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gt2gbywzofd.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbccghjg.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gt2lplgepom.html

?string $name = null
来源：http://dali.chenlongwang.top/Article/details/gt2fqmigbnp.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gt2nnvgtspq.html

int|string $id
来源：http://dali.zhengqikj.top/Article/details/gt2kdunxvqk.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2ndnvhmrj.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2djejlcbw.html

[U49] PHP：只读属性
来源：http://dali.nanxinkj.top/Article/details/gt2ullpneak.html

public readonly string $name
来源：http://dali.pengpengdd.cyou/Article/details/gt2ugmcrwfq.html

[U50] PHP：构造器属性提升
来源：http://dali.shzxlz.cn/Article/details/gt2taesccmu.html

public function __construct(private int $id) {}
来源：http://dali.yuanzhike.top/Article/details/gt2kiqqddok.html

[U51] PHP：数组解构
来源：http://dali.hnxiangtu.top/Article/details/gt2iyitpkei.html

[$a, $b] = $arr;
来源：http://dali.nwbrower.top/Article/details/gt2zsgafklu.html

[U52] PHP：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2ctsojkqx.html

$double = fn($x) => $x * 2;
来源：http://dali.guannengcc.top/Article/details/gt2jhavaqht.html

[U53] PHP：空合并运算符
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bnnoufty.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gt2wtviqsjx.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gt2fugvgsfq.html

$obj?->method()
来源：http://dali.gaohongyu789.top/Article/details/gt2hucglfod.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gt2tjoadxzu.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daxiang520.top/Article/details/gt2tumdtbxu.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gt2rtxuqqlc.html

f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2mknomcoq.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2froenlsa.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gt2ieyqzcdf.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gt2barvvefi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.cdnleiting.top/Article/details/gt2jjmtcpjc.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gt2qanvvqep.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnrgrlij.html

[U60] PHP：JSON 编解码
来源：http://dali.zhixingplan.top/Article/details/gt2bsclqqfn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2utnyypaz.html

[U61] PHP：正则
来源：http://dali.jlsjyb.cn/Article/details/gt2livpwwbq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gt2vawnwjqk.html

[U62] PHP：日期对象
来源：http://dali.zhengqikj.top/Article/details/gt2cntkzwwz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gt2qnrulqlo.html

[U63] PHP：文件读写
来源：http://dali.pengpengdd.cyou/Article/details/gt2rzyjvgoa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yuanzhike.top/Article/details/gt2smealcly.html

[U64] PHP：目录遍历
来源：http://dali.nwbrower.top/Article/details/gt2jwroihrw.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yvedp.cn/Article/details/gt2uvxygdfu.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gt2siccgjbp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.pycfn.com/Article/details/gt2pytzhnka.html

[U66] PHP：设置 Cookie
来源：http://dali.ivvv.top/Article/details/gt2dkilgsqj.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhengqikj.top/Article/details/gt2zdgocdwy.html

[U67] PHP：处理文件上传
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zjacqtfh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gt2jiiihuwu.html

[U68] PHP：PDO 连接
来源：http://dali.sweek.top/Article/details/gt2kktqgwcw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.dashuyun.cn/Article/details/gt2ntkgdvnd.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gt2simoewxi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tian-w.cn/Article/details/gt2gqpnenxd.html

[U70] PHP：PDO 事务
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pqgusxsd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.dashuyun.cn/Article/details/gt2xsjcsbqa.html

[U71] PHP：抛出异常
来源：http://dali.xinyue.icu/Article/details/gt2slhbkjrv.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gt2bpxfzade.html

[U72] PHP：写错误日志
来源：http://dali.0kj1m.cn/Article/details/gt2qkuyeoxw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhixingplan.top/Article/details/gt2bredpyet.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gt2oswqowrp.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2wijgbzdj.html

[U74] PHP：读取环境变量
来源：http://dali.ybcxt.top/Article/details/gt2mwdtnuld.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2glralqfc.html

[U75] PHP：依赖注入
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxfntosf.html

composer require psr/container
来源：http://dali.xylfe.cn/Article/details/gt2bdcifujr.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gt2etlrmhpm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gt2pcrnhrui.html

[U77] PHP：模板渲染
来源：http://dali.daxiang520.top/Article/details/gt2mvgvkwmh.html

composer require twig/twig
来源：http://dali.guowangkeji.top/Article/details/gt2kyffeqyy.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2bohhjmfr.html

composer require --dev phpunit/phpunit
来源：http://dali.wangshuangyany.cn/Article/details/gt2wjgbtnwn.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gt2rooycqgx.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gt2vybxofgd.html

[U80] PHP：代码规范修复
来源：http://dali.zycfv.cn/Article/details/gt2qalzsuxz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gt2fgqzevmo.html

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nutcscph.html

npm init -y;  npm i express
来源：http://dali.yongpay.top/Article/details/gt2dgdmsyjn.html

[U82] JS：package.json 脚本
来源：http://dali.cqqwz.cn/Article/details/gt2qfyawloe.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrxezfza.html

[U83] JS：ES Module 导入导出
来源：http://dali.aibaodan.cn/Article/details/gt2uscbdrqm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yvedp.cn/Article/details/gt2xznfsngz.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gt2zcvhmdac.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gt2rubzviph.html


<!-- 参考信息 -->