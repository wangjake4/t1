代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.gogol.net.cn/Article/details/gt2qnqmtaxg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.daxiang520.top/Article/details/gt2dbxcbqdy.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gt2hxnnzkgt.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2vlvgkafd.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2mkjzgkno.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gt2txlvhdpv.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gt2gabhmhli.html

data class User(val name: String, val age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gt2qfdtbrxz.html

[T09] Kotlin：扩展函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2cznqxezu.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2qxuohaem.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2hqvkcivj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gt2ovjhpdjs.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gt2hmzyvbua.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gt2sbgdbtrx.html

[T12] Kotlin：解构声明
来源：http://dali.bjfxy.top/Article/details/gt2dqqcgqeq.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2gaqrhnbl.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gt2ygylrqnp.html

val m = mapOf("a" to 1)
来源：http://dali.xziqi.cn/Article/details/gt2fcsyyrbn.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gt2mzbwocgw.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckudmpht.html

[T15] Kotlin：接口
来源：http://dali.pycfn.com/Article/details/gt2gxawgyzt.html

interface Shape { fun area(): Double }
来源：http://dali.sweek.top/Article/details/gt2fzsrszcw.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2akpsqszs.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2hlfqbcfo.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gt2goiavkph.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gt2xzjvknfj.html

[T18] Swift：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gt2uvtrytfm.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2nqmyoxtr.html

[T19] Swift：可选绑定
来源：http://dali.9152youxi.cn/Article/details/gt2ntbjworf.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2acwyptrf.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2dilfgbks.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gt2pfnkrmzn.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbeqynwz.html

for x in a { print(x) }
来源：http://dali.jianghu66.top/Article/details/gt2yulajmwv.html

[T22] Swift：字典
来源：http://dali.daria6918.cn/Article/details/gt2uppvalit.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gzhubu.top/Article/details/gt2oarpjpkc.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gt2jamcjagv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qzumavym.html

[T24] Swift：闭包
来源：http://dali.chenjidiqi.icu/Article/details/gt2zqptojwc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gt2clgwqzmd.html

[T25] Swift：结构体
来源：http://dali.hnxiangtu.top/Article/details/gt2anwujraq.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2cwjfssrj.html

[T26] Swift：类与重写
来源：http://dali.yangfankeji.com/Article/details/gt2wahufpbe.html

class A: Base { override func f() {} }
来源：http://dali.redwolf501.top/Article/details/gt2xomhqjap.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2bghbujnw.html

do { try f() } catch { print(error) }
来源：http://dali.haohaochexian.top/Article/details/gt2mwvhpoxb.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gt2mngftkrk.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gt2iohjkvkb.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gt2ddyevmhx.html

guard let x = opt else { return }
来源：http://dali.tanke756.top/Article/details/gt2paxfpbez.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2urbijtar.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2yqlitjyx.html

[T31] Lua：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2ktaerdqy.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2rdhpckmj.html

[T32] Lua：局部变量
来源：http://dali.jyoumei.cn/Article/details/gt2klgcfldu.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gt2evubnolw.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gt2eaxrshhb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xziqi.cn/Article/details/gt2rqztivzn.html

[T34] Lua：遍历表
来源：http://dali.meibo888.top/Article/details/gt2xwncdzhv.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gt2hcxfrcfh.html

[T35] Lua：字典表
来源：http://dali.fengsongda.top/Article/details/gt2udeeutsv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258.top/Article/details/gt2jhwpaekj.html

[T36] Lua：函数
来源：http://dali.jyoumei.cn/Article/details/gt2kkhnopbx.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gt2izlnphxe.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gt2hweixrnj.html

"a" .. "b"
来源：http://dali.zycfv.cn/Article/details/gt2oeidkveb.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gt2nccttxjm.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gt2hrlwjhwu.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2tyracfye.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2cjpggqvd.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gt2mwscujbm.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gt2lcdbbnuh.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2yilcbixy.html

print "Hello\n";
来源：http://dali.wangdashe.top/Article/details/gt2esfxwirv.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2mxqpgumt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gt2vawwgnrw.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2uufizcnh.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gt2ogfbsdxv.html

[T44] Perl：条件
来源：http://dali.cashguo.top/Article/details/gt2srfpssqn.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gt2qirtzkjf.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gt2apmlpskl.html

for my $x (@arr) { print $x; }
来源：http://dali.cashguo.top/Article/details/gt2pjiwwpdi.html

[T46] Perl：哈希操作
来源：http://dali.redwolf501.top/Article/details/gt2mjvftlud.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2mjahxxtl.html

[T47] Perl：正则捕获
来源：http://dali.ivvv.top/Article/details/gt2mnfhlboh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cheryme.top/Article/details/gt2mevcprmx.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gt2pfnvkjtu.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gt2zikygrhg.html

[T49] Perl：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gnbsfubx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xvpbhhkh.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gt2nznxgzjo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gt2mhhrphll.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2homcgdct.html

[T51] Scala：Hello World
来源：http://dali.havefunace.top/Article/details/gt2aytkaypb.html

println("Hello")
来源：http://dali.guannengcc.top/Article/details/gt2mpucanwa.html

[T52] Scala：变量
来源：http://dali.gogol.net.cn/Article/details/gt2rasbsyto.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2bkcuehpv.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rglqcwkp.html

s"值: $b"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqafweki.html

[T54] Scala：集合映射
来源：http://dali.ybcxt.top/Article/details/gt2euxcxgbt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gt2nzxpkmdc.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2zsrleiow.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zycfv.cn/Article/details/gt2radfdxdu.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2tkhbokvt.html

case class User(name: String, age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2lrzsgoqs.html

[T57] Scala：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2scocqbvr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2vwvaqgwc.html

[T58] Scala：函数定义
来源：http://dali.sysykeji.top/Article/details/gt2tasenngt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gt2vgafutgx.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fdkczajw.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2qptvmlmc.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2rgdxtqep.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gt2qyqweshy.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2eccxrdme.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2ybbdyjhr.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2ijhcxeoz.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gt2tbtxqszh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gt2bbyuinfr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gt2vozhbwpq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lgepsdkv.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gt2luiqdsjj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.bjfxy.top/Article/details/gt2pzuzbifq.html

[U04] Py：变量调试打印
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kiqbghmb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhengqikj.top/Article/details/gt2rpvschej.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2zxywvowo.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gt2sbsfvshv.html

[U06] Py：合并两个字典
来源：http://dali.zhixingplan.top/Article/details/gt2lovcblgu.html

{**a, **b}
来源：http://dali.zdqjudy.top/Article/details/gt2hurwfdyt.html

[U07] Py：反转字典键值
来源：http://dali.yonumen.top/Article/details/gt2ktvmprjl.html

{v: k for k, v in d.items()}
来源：http://dali.ivvv.top/Article/details/gt2pxqufwij.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gt2qbcxyins.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gt2steqzvpb.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2hfmujfni.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gt2anrveoub.html

[U10] Py：按值排序字典
来源：http://dali.gotoacloud.top/Article/details/gt2xrqtevhd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ppjwa.cn/Article/details/gt2jymokwzx.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gt2uluveljo.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2pvhuoeeg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.fzhhl.top/Article/details/gt2anmouvuu.html

Counter(arr).most_common(3)
来源：http://dali.mhx1999.top/Article/details/gt2odvyzvrk.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gt2mtkqhmds.html

deque(maxlen=10)
来源：http://dali.zhongyouzk.top/Article/details/gt2srvgeanc.html

[U14] Py：分组收集到列表
来源：http://dali.nanxuanxn.top/Article/details/gt2tklbbydt.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gt2jzaoswgd.html

[U15] Py：高精度计时
来源：http://dali.daria6918.cn/Article/details/gt2qadkmpdv.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2zmxliqhq.html

[U16] Py：命令行参数解析
来源：http://dali.cucudq.cn/Article/details/gt2ekjtohsx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2esycvffr.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gt2qssjxcga.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.meibo888.top/Article/details/gt2vetkzbqd.html

[U18] Py：预编译正则
来源：http://dali.yongpay.top/Article/details/gt2gogsnyfm.html

pat = re.compile(r"\d+")
来源：http://dali.zhijiandao.cn/Article/details/gt2sjoswbby.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2kknkyvge.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nanxuanxn.top/Article/details/gt2lcelknkd.html

[U20] Py：缓存函数结果
来源：http://dali.zhixingplan.top/Article/details/gt2rvbvbvuf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhongyouzk.top/Article/details/gt2aczqbvzg.html

[U21] Py：自定义上下文管理器
来源：http://dali.smart0.xyz/Article/details/gt2iobcplyh.html

@contextlib.contextmanager
来源：http://dali.havefunace.top/Article/details/gt2xvgjbash.html

[U22] Py：矩阵转置
来源：http://dali.tian-w.cn/Article/details/gt2xzjokper.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mqlabczb.html

[U23] Py：分块读取大文件
来源：http://dali.tanke756.top/Article/details/gt2gnslpgko.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gt2leoecyra.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gt2vdsskwcd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gt2tmcqyahe.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gt2zfspmuil.html

csv.DictReader(f)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ctbpmapk.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gt2awmjqoja.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gt2kojqltsj.html

[U27] Py：异步 HTTP
来源：http://dali.zhengqikj.top/Article/details/gt2lzxbwisf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.316326.xyz/Article/details/gt2jbrcffof.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gt2sllegtyj.html

UserId = int
来源：http://dali.nanxinkj.top/Article/details/gt2zyekwkll.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gt2wmnlrwsq.html

@property 与 @x.setter 配合
来源：http://dali.316326.xyz/Article/details/gt2bckdkoks.html

[U30] Py：数据类
来源：http://dali.daria6918.cn/Article/details/gt2kcdvvqoa.html

@dataclass(slots=True)
来源：http://dali.chenjidiqi.icu/Article/details/gt2zdydqica.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gt2gkzjsedl.html

python -m pytest -q
来源：http://dali.yonumen.top/Article/details/gt2roljbmvh.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gt2yiasmyzn.html

ruff format . && ruff check --fix .
来源：http://dali.yvedp.cn/Article/details/gt2xsyogkup.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gt2fqktrnsw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gogol.net.cn/Article/details/gt2wutppqfk.html

[U34] Py：判断编码
来源：http://dali.svipenyu.cn/Article/details/gt2ivpmxpfo.html

chardet.detect(raw)
来源：http://dali.dashuyun.cn/Article/details/gt2dzhkpexm.html

[U35] Py：发送邮件
来源：http://dali.guowangkeji.top/Article/details/gt2zbcecman.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gt2sbsutkdr.html

[U36] Py：定时任务
来源：http://dali.zycfv.cn/Article/details/gt2oapejdsm.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gt2uuvkdseo.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gt2bgnbcwox.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.316326.xyz/Article/details/gt2lxjrylxv.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gt2cmsldsmr.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gt2fbjtwzey.html

[U39] Py：判断是否在交互环境
来源：http://dali.guannengcc.top/Article/details/gt2hettgrnm.html

sys.stdout.isatty()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kwlxrtkh.html

[U40] Py：打印到标准错误
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eryakhcu.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2qzfcnzbi.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zdqjudy.top/Article/details/gt2dqpvwqtd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hfpthk.cn/Article/details/gt2criurola.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gt2epdknteg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.aibaodan.cn/Article/details/gt2vcfbhmmf.html

[U43] PHP：声明命名空间
来源：http://dali.gaohongyu789.top/Article/details/gt2xrxmyjji.html

namespace App\Http;
来源：http://dali.ivvv.top/Article/details/gt2qcjfbahh.html

[U44] PHP：开启严格类型
来源：http://dali.gogol.net.cn/Article/details/gt2wzypwdjb.html

declare(strict_types=1);
来源：http://dali.ybcxt.top/Article/details/gt2nofrtpnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xziqi.cn/Article/details/gt2arlboqve.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pansdtcg.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gt2adxtwuat.html

?string $name = null
来源：http://dali.ppjwa.cn/Article/details/gt2mrjgwiuo.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2hdqrniyp.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gt2lajoslne.html

[U48] PHP：纯枚举
来源：http://dali.yueranfly.top/Article/details/gt2rkipcjtk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.ppjwa.cn/Article/details/gt2hxnqspqd.html

[U49] PHP：只读属性
来源：http://dali.yuanzhike.top/Article/details/gt2hvtdjkrb.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lilcgzkc.html

[U50] PHP：构造器属性提升
来源：http://dali.tian-w.cn/Article/details/gt2jcxndlhd.html

public function __construct(private int $id) {}
来源：http://dali.yj20258.top/Article/details/gt2wrtbbzew.html

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gt2ouyfdsbm.html

[$a, $b] = $arr;
来源：http://dali.cucudq.cn/Article/details/gt2uyqgrksv.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gt2mrbseuro.html

$double = fn($x) => $x * 2;
来源：http://dali.sufxvd.cn/Article/details/gt2blsslnku.html

[U53] PHP：空合并运算符
来源：http://dali.yangfankeji.com/Article/details/gt2bidgczgw.html

$v = $a ?? $b ?? "default";
来源：http://dali.vqdsnc.cn/Article/details/gt2tadcnkrv.html

[U54] PHP：空安全调用
来源：http://dali.zhixingplan.top/Article/details/gt2rnnrglxu.html

$obj?->method()
来源：http://dali.nwbrower.top/Article/details/gt2cbwppujn.html

[U55] PHP：match 表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ffopobsb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gt2qlczelqs.html

[U56] PHP：命名参数
来源：http://dali.yuxming.cn/Article/details/gt2mxjpphwu.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2qjbsymdv.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2vylzuiqz.html

"值: {$a}"
来源：http://dali.hysaishi.cn/Article/details/gt2qnkrhmqh.html

[U58] PHP：数组三件套
来源：http://dali.jianghu66.top/Article/details/gt2gccyimwb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sweek.top/Article/details/gt2nwzmtqle.html

[U59] PHP：自定义排序
来源：http://dali.fzhhl.top/Article/details/gt2vjnxkwud.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gt2hfoqpymv.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvxyvrec.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gt2nnzmigzj.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gt2rdvfwpdv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258.top/Article/details/gt2lpqjprdb.html

[U62] PHP：日期对象
来源：http://dali.ppjwa.cn/Article/details/gt2buxdwngz.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxuanxn.top/Article/details/gt2wthygsqi.html

[U63] PHP：文件读写
来源：http://dali.andypj.xyz/Article/details/gt2tvpzyqrm.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.svipenyu.cn/Article/details/gt2icmsvdbg.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gt2gozqqjlv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gt2icghuuph.html

[U65] PHP：会话
来源：http://dali.zhixingplan.top/Article/details/gt2ysaqrokr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2xslnvfxl.html

[U66] PHP：设置 Cookie
来源：http://dali.xinyue.icu/Article/details/gt2trwtatbh.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xziqi.cn/Article/details/gt2qxigblyt.html

[U67] PHP：处理文件上传
来源：http://dali.gzhubu.top/Article/details/gt2sojxldwc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yvedp.cn/Article/details/gt2qdatsdpy.html

[U68] PHP：PDO 连接
来源：http://dali.feifeiyinyue.top/Article/details/gt2mkskmpbr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yangfankeji.com/Article/details/gt2enehafjh.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gt2fchixjyp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yonumen.top/Article/details/gt2ddipwdua.html

[U70] PHP：PDO 事务
来源：http://dali.iojbl.cn/Article/details/gt2tfbvgwcc.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.wangdashe.top/Article/details/gt2pptasjmq.html

[U71] PHP：抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvnanzlc.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gt2sstpgqgs.html

[U72] PHP：写错误日志
来源：http://dali.gzhubu.top/Article/details/gt2mwmtsfab.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gt2surezosx.html

[U73] PHP：读取 ini 配置
来源：http://dali.cheryme.top/Article/details/gt2hzynsodf.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gt2dhaqxopy.html

[U74] PHP：读取环境变量
来源：http://dali.bjfxy.top/Article/details/gt2yheevfyo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guannengcc.top/Article/details/gt2ztyaxady.html

[U75] PHP：依赖注入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mphzehhe.html

composer require psr/container
来源：http://dali.smart0.xyz/Article/details/gt2afidfxqh.html

[U76] PHP：简单路由
来源：http://dali.jyoumei.cn/Article/details/gt2aswnqpir.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yuxming.cn/Article/details/gt2wnxzhbcb.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gt2hzlrkpxi.html

composer require twig/twig
来源：http://dali.yuanzhike.top/Article/details/gt2auurrfkr.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ghlrypwc.html

composer require --dev phpunit/phpunit
来源：http://dali.tianlin.xyz/Article/details/gt2ttljmxpb.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gt2sohzthty.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ssdtgpll.html

[U80] PHP：代码规范修复
来源：http://dali.birdmap.top/Article/details/gt2wrftsodi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ybcxt.top/Article/details/gt2eoaxztax.html

[U81] JS：初始化项目
来源：http://dali.hnxiangtu.top/Article/details/gt2ieqftsmc.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gt2wojzeabu.html

[U82] JS：package.json 脚本
来源：http://dali.snrcjt.cn/Article/details/gt2utuhpsvo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gt2szkuodyq.html

[U83] JS：ES Module 导入导出
来源：http://dali.wangdashe.top/Article/details/gt2billqscr.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gt2crejpxkb.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gt2dfnygtmp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sysykeji.top/Article/details/gt2vbvmgolw.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gt2jkxivqsq.html

a?.b?.c
来源：http://dali.ybcxt.top/Article/details/gt2duymdnuy.html

[U86] JS：空值合并
来源：http://dali.ybcxt.top/Article/details/gt2zguuvuqw.html

a ?? b
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otokaldu.html

[U87] JS：解构默认值
来源：http://dali.shangyingyoupin.top/Article/details/gt2uxfgotaa.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gt2jnwpfuiq.html

[U88] JS：对象展开合并
来源：http://dali.0kj1m.cn/Article/details/gt2frheacla.html

{ ...a, ...b }
来源：http://dali.ivvv.top/Article/details/gt2yzoblcib.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vjmmbkjf.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gt2qinaqfyy.html

[U90] JS：数字数组排序
来源：http://dali.gzhubu.top/Article/details/gt2vlouvuxl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuxming.cn/Article/details/gt2ftvpgpdd.html

[U91] JS：对象键值遍历
来源：http://dali.hysaishi.cn/Article/details/gt2gfkewwfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uyylspph.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gt2bwzlhdbv.html

structuredClone(obj)
来源：http://dali.316326.xyz/Article/details/gt2ublxnuet.html


<!-- 参考信息 -->