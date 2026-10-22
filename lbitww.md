代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2unguyrkg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gt2mfzweukx.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gt2tgtphugr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2xdciatqg.html

[T07] Kotlin：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2nctuvumw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2oyxzvpvd.html

[T08] Kotlin：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gt2cwtvynpa.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2jsjskxtl.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gt2aworgpfy.html

fun String.exclaim() = this + "!"
来源：http://dali.tian-w.cn/Article/details/gt2qjngiawr.html

[T10] Kotlin：默认参数
来源：http://dali.sysykeji.top/Article/details/gt2yfrhgios.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2hahzcrjr.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2uzlvlxni.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gt2avguzbtl.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gt2ddqglkvl.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gt2ymwmeruw.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gt2cinbmtkz.html

val m = mapOf("a" to 1)
来源：http://dali.jiagoushi.top/Article/details/gt2zopngeaw.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2cazejdnl.html

for (i in 1..10) println(i)
来源：http://dali.ydzc1.top/Article/details/gt2loleqryi.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gt2erqbwnga.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2buthkwzq.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2flknrbqy.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gt2vtondpwt.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2yghxwsyg.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2zupkrwij.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gt2kkekksbq.html

"值: \(b)"
来源：http://dali.sxryk.cn/Article/details/gt2xwemxend.html

[T19] Swift：可选绑定
来源：http://dali.guowangkeji.top/Article/details/gt2broivypg.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gt2jkppbdet.html

[T20] Swift：数组操作
来源：http://dali.kuanghao11.cn/Article/details/gt2yirqrwdg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yurcqqam.html

[T21] Swift：遍历
来源：http://dali.xinyue.icu/Article/details/gt2rajbyrtr.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gt2idwjdflq.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gt2jxjkcerp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xylfe.cn/Article/details/gt2rtnobnpi.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gt2ivfcrrgt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2blejjmum.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gt2trkjopgm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gt2ylkvjzmy.html

[T25] Swift：结构体
来源：http://dali.zhixingplan.top/Article/details/gt2osgjfjug.html

struct P { var x: Int }
来源：http://dali.xziqi.cn/Article/details/gt2mzeswkxs.html

[T26] Swift：类与重写
来源：http://dali.aizwys.cn/Article/details/gt2axgerccr.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gt2umlbtaqy.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2gglppihu.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2yvcdfovn.html

[T28] Swift：枚举
来源：http://dali.sxryk.cn/Article/details/gt2ffdfkfbp.html

enum Color { case red, green }
来源：http://dali.jlsjyb.cn/Article/details/gt2scaqrqob.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pzquebwy.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gt2erqcuqes.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2aalksjzu.html

protocol Shape { func area() -> Double }
来源：http://dali.ehwqpu.com/Article/details/gt2trknrvxg.html

[T31] Lua：Hello World
来源：http://dali.cashguo.top/Article/details/gt2tjghmtrl.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2ocrtojjq.html

[T32] Lua：局部变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wnxqftij.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aqetpvtr.html

[T33] Lua：表（数组）
来源：http://dali.zhengqikj.top/Article/details/gt2eugcryaa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2qlutvdlb.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gt2peluudqm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2njicsigu.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hakdzjrt.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gt2seeidelh.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2nnqkbxnp.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gt2sufzxsof.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gt2heavhnij.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gt2awqugdwb.html

[T38] Lua：条件
来源：http://dali.jyoumei.cn/Article/details/gt2bujbzpsd.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gt2wsdswuum.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqsjeaud.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gt2nwttblep.html

[T40] Lua：元表
来源：http://dali.316326.xyz/Article/details/gt2qjzaudtm.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmgvikhf.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wynauvwn.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2uidalcmw.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gt2mhsgpjap.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.fengsongda.top/Article/details/gt2mbwtzbel.html

[T43] Perl：字符串插值
来源：http://dali.yonumen.top/Article/details/gt2kygqqvse.html

"值: $a"
来源：http://dali.yj20258.top/Article/details/gt2eehbjcrp.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gt2lakzalce.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gt2ewemzlhg.html

[T45] Perl：数组遍历
来源：http://dali.quarkkingdee.top/Article/details/gt2pdprzynf.html

for my $x (@arr) { print $x; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gwhjxdzq.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gt2bodezmca.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gt2bnxhmcav.html

[T47] Perl：正则捕获
来源：http://dali.nanxinkj.top/Article/details/gt2gandgovc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gt2lhjlljdl.html

[T48] Perl：正则替换
来源：http://dali.vqdsnc.cn/Article/details/gt2wurslvxe.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gt2kiknsjai.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gt2lpgclpjm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gt2zpcoqxub.html

[T50] Perl：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gt2lvxeuiuw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuanzx.com/Article/details/gt2jxqnrqjm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hysaishi.cn/Article/details/gt2nepxnurn.html

[T51] Scala：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2dbkytaxy.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2wwpltiov.html

[T52] Scala：变量
来源：http://dali.cucudq.cn/Article/details/gt2pzezsrjd.html

val a = 1;  var b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qcofthcb.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gt2qedlleod.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gt2ujfurvtu.html

[T54] Scala：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gt2mfbeyfrx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2tufkqndi.html

[T55] Scala：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2ettasqey.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2swruyzli.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gt2lqkyrsla.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2zwnpljst.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2mchfsgmh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gt2hwfyjpfp.html

[T58] Scala：函数定义
来源：http://dali.redwolf501.top/Article/details/gt2cbuivqnf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gt2obfahuyj.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gt2pfquwoyo.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gt2qbpcixay.html

[T60] Scala：折叠
来源：http://dali.svipenyu.cn/Article/details/gt2akplnybd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gt2qotvrmzv.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2lowlmmwr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.snrcjt.cn/Article/details/gt2wigvktdn.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2gshbubpf.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2knaivbqt.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jiagoushi.top/Article/details/gt2lfhuphbk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gt2jbgetqwa.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gt2jfrjzond.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gt2splfzlcx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gt2xqvfmgzw.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gt2bvzepqeh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhixingplan.top/Article/details/gt2mwwqvtmc.html

[U05] Py：列表去重且保序
来源：http://dali.shzxlz.cn/Article/details/gt2mnynxxhc.html

list(dict.fromkeys(arr))
来源：http://dali.gzhubu.top/Article/details/gt2dqktvpej.html

[U06] Py：合并两个字典
来源：http://dali.cqqwz.cn/Article/details/gt2kuwknrbd.html

{**a, **b}
来源：http://dali.daxiang520.top/Article/details/gt2axiykqcx.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2siyqjlpu.html

{v: k for k, v in d.items()}
来源：http://dali.gzhubu.top/Article/details/gt2imgrzbjj.html

[U08] Py：展平二维列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdrsqilq.html

[y for x in nested for y in x]
来源：http://dali.yueranfly.top/Article/details/gt2ihlujhso.html

[U09] Py：字典取最大值的键
来源：http://dali.bjfxy.top/Article/details/gt2cfmhschn.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2xldvxrae.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gt2dhewbehq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jlsjyb.cn/Article/details/gt2pjrxwhoe.html

[U11] Py：生成器表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ssjjhayf.html

(x * 2 for x in arr)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnuswfoi.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zdqjudy.top/Article/details/gt2bngckdlo.html

Counter(arr).most_common(3)
来源：http://dali.guowangkeji.top/Article/details/gt2rcoqkwvl.html

[U13] Py：固定长度队列
来源：http://dali.birdmap.top/Article/details/gt2amhdiqpa.html

deque(maxlen=10)
来源：http://dali.hnxiangtu.top/Article/details/gt2fjpkmgmg.html

[U14] Py：分组收集到列表
来源：http://dali.chenjidiqi.icu/Article/details/gt2dirpizuc.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gt2ginxiaft.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gt2hwmhqses.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gt2pyspdrdn.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gt2kblevzcj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shuidangran.top/Article/details/gt2vxhbglhp.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gt2ffnpfnrf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ggtkvkjz.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gt2ponjryac.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gt2sgevwbra.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gt2lssjosut.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vqgyeixg.html

[U20] Py：缓存函数结果
来源：http://dali.jqgufenzy.top/Article/details/gt2nnrfgloj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2teqwahpt.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj202588.top/Article/details/gt2qansbazd.html

@contextlib.contextmanager
来源：http://dali.xylfe.cn/Article/details/gt2pkegodxk.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2kasvobyz.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gt2itctgsql.html

[U23] Py：分块读取大文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnjlsadb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.feifeiyinyue.top/Article/details/gt2komlizul.html

[U24] Py：路径操作
来源：http://dali.zycfv.cn/Article/details/gt2jmeecgcd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yueranfly.top/Article/details/gt2grvsfxjd.html

[U25] Py：CSV 按字典读
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aurjxpse.html

csv.DictReader(f)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfegcmqk.html

[U26] Py：并发下载
来源：http://dali.shuidangran.top/Article/details/gt2kzyfyclj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yyrqvesc.html

[U27] Py：异步 HTTP
来源：http://dali.xuanzx.com/Article/details/gt2lvzjjbgr.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yonumen.top/Article/details/gt2wqfjzmyw.html

[U28] Py：类型别名
来源：http://dali.gaohongyu789.top/Article/details/gt2crgyyubp.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2yszpglna.html

[U29] Py：属性校验
来源：http://dali.shangyingyoupin.top/Article/details/gt2nlaejpiy.html

@property 与 @x.setter 配合
来源：http://dali.cashguo.top/Article/details/gt2qsodvsde.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gt2mmyisdej.html

@dataclass(slots=True)
来源：http://dali.ydzc1.top/Article/details/gt2nynqcnjt.html

[U31] Py：单测
来源：http://dali.yuxming.cn/Article/details/gt2vijopmnl.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gt2iqrjbpiw.html

[U32] Py：代码格式化
来源：http://dali.gaohongyu789.top/Article/details/gt2ypfktjif.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gt2sbdqwbwe.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gt2bjncltue.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hnxiangtu.top/Article/details/gt2hcvulwtj.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gt2sbfcyqfs.html

chardet.detect(raw)
来源：http://dali.ehwqpu.com/Article/details/gt2pqigvgbp.html

[U35] Py：发送邮件
来源：http://dali.sufxvd.cn/Article/details/gt2xarhhkqu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yueranfly.top/Article/details/gt2czcmsnqz.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2btxqexdr.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gt2bobvrtaf.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gt2ejzucgwn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.kuanghao11.cn/Article/details/gt2yxdhdjjm.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2mwgnagik.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2xuufpbkx.html

[U39] Py：判断是否在交互环境
来源：http://dali.redwolf501.top/Article/details/gt2xicbpliw.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vhgzzept.html

[U40] Py：打印到标准错误
来源：http://dali.svipenyu.cn/Article/details/gt2gmtnbmvk.html

print("err", file=sys.stderr)
来源：http://dali.sxryk.cn/Article/details/gt2sfeqadwj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.birdmap.top/Article/details/gt2nmygbuef.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gt2sddjetht.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cwpadmzk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shuidangran.top/Article/details/gt2xmurhwrq.html

[U43] PHP：声明命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2phapltxp.html

namespace App\Http;
来源：http://dali.sufxvd.cn/Article/details/gt2ckcdgzda.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gt2vbtzbywz.html

declare(strict_types=1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xobqspvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nanxinkj.top/Article/details/gt2cdpztnvp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ixkdbcpu.html

[U46] PHP：可空类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2mogqwiet.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gt2lvbrjaih.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2fgptilsi.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gt2cqegixsu.html

[U48] PHP：纯枚举
来源：http://dali.svipenyu.cn/Article/details/gt2rrdhusyu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gt2oyohtgtx.html

[U49] PHP：只读属性
来源：http://dali.shangyingyoupin.top/Article/details/gt2eyalmiky.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gt2incwykxh.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gt2pzlctmst.html

public function __construct(private int $id) {}
来源：http://dali.svipenyu.cn/Article/details/gt2pixdewfr.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gt2uaclaohs.html

[$a, $b] = $arr;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ypyugbmg.html

[U52] PHP：箭头函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhtypnip.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gt2wpwltyte.html

[U53] PHP：空合并运算符
来源：http://dali.zhoulong.xyz/Article/details/gt2qjgfmzgb.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dciporob.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gt2wxzohqgi.html

$obj?->method()
来源：http://dali.jianghu66.top/Article/details/gt2icqozfdj.html

[U55] PHP：match 表达式
来源：http://dali.zhongyouzk.top/Article/details/gt2ytbhgzhs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2nvxtjhsc.html

[U56] PHP：命名参数
来源：http://dali.hywenlv.cn/Article/details/gt2rwxlubec.html

f(a: 1, b: 2)
来源：http://dali.redwolf501.top/Article/details/gt2bzssqqvy.html

[U57] PHP：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2ixmfybaj.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gt2rekuntfn.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gt2jtneoqki.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gt2uazjhjla.html

[U59] PHP：自定义排序
来源：http://dali.0kj1m.cn/Article/details/gt2tcqlsvjx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnxiangtu.top/Article/details/gt2vpfmbnyd.html

[U60] PHP：JSON 编解码
来源：http://dali.xuetiantiany.cn/Article/details/gt2fmiytnqa.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gt2dqhofuef.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gt2sedqmbiw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gt2vayuopov.html

[U62] PHP：日期对象
来源：http://dali.bjfxy.top/Article/details/gt2chaabsak.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jiagoushi.top/Article/details/gt2mizamwaq.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gt2jpswxzoc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jlsjyb.cn/Article/details/gt2idnimpax.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gt2fhqymusl.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gt2dqepaspl.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gt2cfqospon.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gt2inplidnf.html

[U66] PHP：设置 Cookie
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fmlafmbm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yangfankeji.com/Article/details/gt2ntjgcrsb.html

[U67] PHP：处理文件上传
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvngyzfx.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gzhubu.top/Article/details/gt2vjxvmicw.html

[U68] PHP：PDO 连接
来源：http://dali.hfpthk.cn/Article/details/gt2qjtdxmgz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gt2iialqcla.html

[U69] PHP：PDO 预处理
来源：http://dali.gaohongyu789.top/Article/details/gt2kbdhzgdz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daxiang520.top/Article/details/gt2cejzybpq.html

[U70] PHP：PDO 事务
来源：http://dali.wangshuangyany.cn/Article/details/gt2gxkimfaj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfumvexd.html

[U71] PHP：抛出异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2xrdovyzl.html

throw new RuntimeException("失败", 500);
来源：http://dali.gaohongyu789.top/Article/details/gt2erpucdim.html

[U72] PHP：写错误日志
来源：http://dali.yuxming.cn/Article/details/gt2xyxosnyw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gt2wuqydqmy.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gt2pqrejvfz.html

parse_ini_file("config.ini", true)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tnbonnej.html

[U74] PHP：读取环境变量
来源：http://dali.birdmap.top/Article/details/gt2qihlxtha.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hammf.cn/Article/details/gt2ogulbamt.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gt2dgkyqwlt.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gt2pokmaumb.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gt2emzxxres.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sxryk.cn/Article/details/gt2becywycb.html

[U77] PHP：模板渲染
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jwszduly.html

composer require twig/twig
来源：http://dali.gzhubu.top/Article/details/gt2wzccgjld.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2tmpalpfh.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gt2izrykcod.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gt2lzvnnflv.html

composer require --dev phpstan/phpstan
来源：http://dali.xuetiantiany.cn/Article/details/gt2wteawkgu.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gt2jtrtrkvs.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvhzjcci.html

[U81] JS：初始化项目
来源：http://dali.cheryme.top/Article/details/gt2vyptavvp.html

npm init -y;  npm i express
来源：http://dali.sweek.top/Article/details/gt2iobtlpib.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gt2gxstwjds.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.aizwys.cn/Article/details/gt2vkczjgdf.html

[U83] JS：ES Module 导入导出
来源：http://dali.sufxvd.cn/Article/details/gt2smyzepma.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gt2qicniowt.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gt2abyqoqpj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xziqi.cn/Article/details/gt2wpwdcvqj.html

[U85] JS：可选链
来源：http://dali.xinyue.icu/Article/details/gt2hdsuibix.html

a?.b?.c
来源：http://dali.nanxinkj.top/Article/details/gt2loxdiaog.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2cfvfglot.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gt2plxiabpc.html

[U87] JS：解构默认值
来源：http://dali.sweek.top/Article/details/gt2opuuprbt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gt2perafdzo.html

[U88] JS：对象展开合并
来源：http://dali.yj20258.top/Article/details/gt2unglvxzh.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gt2ltgiypcg.html

[U89] JS：数组去重
来源：http://dali.kuanghao11.cn/Article/details/gt2sdfxbixv.html

[...new Set(arr)]
来源：http://dali.zdqjudy.top/Article/details/gt2trelinoz.html

[U90] JS：数字数组排序
来源：http://dali.hammf.cn/Article/details/gt2bzwawudg.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hnxiangtu.top/Article/details/gt2ulvglbhj.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gt2trirnwpw.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gaohongyu789.top/Article/details/gt2rppymdmw.html

[U92] JS：深拷贝
来源：http://dali.yj202588.top/Article/details/gt2xjsdpeee.html

structuredClone(obj)
来源：http://dali.jyoumei.cn/Article/details/gt2xrfnmfti.html


<!-- 参考信息 -->