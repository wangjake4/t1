代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gt2dmiysxfv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cdnleiting.top/Article/details/gt2jrcgxzbk.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gt2dgfcxtaf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gt2xedaxngl.html

[T07] Kotlin：集合过滤
来源：http://dali.jyoumei.cn/Article/details/gt2veaweboo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gt2wznphwnz.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2sdvzuhzn.html

data class User(val name: String, val age: Int)
来源：http://dali.nanxinkj.top/Article/details/gt2wmoouwun.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2mogrydeo.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gt2hxrthire.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2hmwsrlzb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhengqikj.top/Article/details/gt2lbteavta.html

[T11] Kotlin：协程
来源：http://dali.cdnleiting.top/Article/details/gt2wbwunwec.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.c1oappe.top/Article/details/gt2ggksgewg.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2fqypmvnh.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2mapidjan.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gt2mthhtfnn.html

val m = mapOf("a" to 1)
来源：http://dali.daxiang520.top/Article/details/gt2xbixzydj.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gt2ehacluxh.html

for (i in 1..10) println(i)
来源：http://dali.hfpthk.cn/Article/details/gt2xifnkatn.html

[T15] Kotlin：接口
来源：http://dali.andypj.xyz/Article/details/gt2hcynpwwx.html

interface Shape { fun area(): Double }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vtgchmmi.html

[T16] Swift：Hello World
来源：http://dali.zycfv.cn/Article/details/gt2gfrsfxid.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2zazfhadq.html

[T17] Swift：变量与常量
来源：http://dali.bjfxy.top/Article/details/gt2mayqrwaj.html

var a = 1;  let b = 2
来源：http://dali.yuxming.cn/Article/details/gt2oaiekust.html

[T18] Swift：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2rpodejht.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2ktmvlqcn.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hojwkluc.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gt2wdpdcfzt.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gt2athdjwmc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfdbmjbl.html

[T21] Swift：遍历
来源：http://dali.yongpay.top/Article/details/gt2bjqowszj.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gt2vvasnmrk.html

[T22] Swift：字典
来源：http://dali.gzhubu.top/Article/details/gt2gefekdbp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gt2gveggdhh.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2zedzeeea.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jiagoushi.top/Article/details/gt2wtepgski.html

[T24] Swift：闭包
来源：http://dali.hfpthk.cn/Article/details/gt2hwrvfhis.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhiwuduotai.top/Article/details/gt2lpyfictj.html

[T25] Swift：结构体
来源：http://dali.ybcxt.top/Article/details/gt2nhsrryxh.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gt2lpgedomc.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2dtjrxnnk.html

class A: Base { override func f() {} }
来源：http://dali.tian-w.cn/Article/details/gt2tcmdsolp.html

[T27] Swift：错误处理
来源：http://dali.yuanzhike.top/Article/details/gt2udzjnhxm.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gt2lsoceudu.html

[T28] Swift：枚举
来源：http://dali.yj202588.top/Article/details/gt2kqldlaae.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gt2rsuxirll.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qfdbewgu.html

guard let x = opt else { return }
来源：http://dali.meibo888.top/Article/details/gt2irxeeoqb.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gt2jpfforze.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gt2cwoirhzs.html

[T31] Lua：Hello World
来源：http://dali.hywenlv.cn/Article/details/gt2udwtviws.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2zznhjynl.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gt2fdustbfz.html

local a = 1
来源：http://dali.vqdsnc.cn/Article/details/gt2fosjavkv.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gt2edqnutru.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gt2zeixlpes.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gt2hrznrmqz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.cdnleiting.top/Article/details/gt2htbexicm.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gt2epvsmfww.html

local d = { a = 1 };  d.b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2tnwzwsoa.html

[T36] Lua：函数
来源：http://dali.wangdashe.top/Article/details/gt2brlljdmn.html

function add(a, b) return a + b end
来源：http://dali.vqdsnc.cn/Article/details/gt2gulxjtel.html

[T37] Lua：字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gt2xsompcwx.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gt2jeigjolu.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gt2hwykxmua.html

if x > 0 then print("正") end
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqjfctds.html

[T39] Lua：模式匹配
来源：http://dali.nwbrower.top/Article/details/gt2tzpfpzob.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gt2sflchtxz.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gt2ghylxgsi.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gt2fqymrbjk.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ehjsswxt.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gt2lhyvgzzs.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gt2xvnsnikh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gt2xtkbcqmk.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2xdhwhjfz.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qvzsjmio.html

[T44] Perl：条件
来源：http://dali.yonumen.top/Article/details/gt2dwrdgknc.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2tymeutvl.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gt2jrqmvrmt.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gt2plgvujvg.html

[T46] Perl：哈希操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2rkeuxmwo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sxryk.cn/Article/details/gt2rmrfohtz.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gt2qlwmawoj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ybcxt.top/Article/details/gt2tpgrphtw.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2mrlgqzwz.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gt2ziadkjuy.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gt2xazzwkqr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2daepxtjh.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gt2jqsnaaxy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.aibaodan.cn/Article/details/gt2cpznectu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gt2kymjamom.html

[T51] Scala：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2zhjneyqe.html

println("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gt2rciqtapq.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gt2xsjjbgku.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2fzrdjmuu.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2irtmoseh.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gt2nfhcubxb.html

[T54] Scala：集合映射
来源：http://dali.zhoulong.xyz/Article/details/gt2bcluvqdw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2hedwxvxb.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2ggafguyy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gt2tcudgnep.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gt2gxoxrqet.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2buygdmhe.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gt2vesxkjra.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gt2cufjvacu.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gt2bforulrr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhengqikj.top/Article/details/gt2zjzszofp.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gt2oyucpkhc.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gt2sncluilr.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gt2rpqetgzz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nanxuanxn.top/Article/details/gt2ryjrbuqf.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2mrlvizgr.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gt2pkqmljoh.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2cofsouio.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2lwocxjna.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nowfsfsu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gt2fuqmwqkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fzhhl.top/Article/details/gt2rbvlzmuw.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gt2vygdmewm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ehosvqjq.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gt2aebvrtwo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.quarkkingdee.top/Article/details/gt2wgvzpnxt.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2wagwpeve.html

list(dict.fromkeys(arr))
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wodcknlx.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gt2macznpzh.html

{**a, **b}
来源：http://dali.cucudq.cn/Article/details/gt2qglxwodp.html

[U07] Py：反转字典键值
来源：http://dali.zhengqikj.top/Article/details/gt2mcsciunu.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gt2coannunt.html

[U08] Py：展平二维列表
来源：http://dali.ybcxt.top/Article/details/gt2dwrylfza.html

[y for x in nested for y in x]
来源：http://dali.tanke756.top/Article/details/gt2ofbxlttq.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gt2hoifivce.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gt2uwqmsdxx.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2wzvvixqr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.feifeiyinyue.top/Article/details/gt2mfawpfta.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aappggaw.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gt2rjrjqnwk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2pgwirybd.html

Counter(arr).most_common(3)
来源：http://dali.dianchejie.cn/Article/details/gt2ojvjodyn.html

[U13] Py：固定长度队列
来源：http://dali.tanke756.top/Article/details/gt2dvsifzay.html

deque(maxlen=10)
来源：http://dali.xuanzx.com/Article/details/gt2tkbccdoe.html

[U14] Py：分组收集到列表
来源：http://dali.aibaodan.cn/Article/details/gt2rzawhyir.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gt2czdsokjw.html

[U15] Py：高精度计时
来源：http://dali.sysykeji.top/Article/details/gt2uveqhgev.html

t = time.perf_counter()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbiqekgl.html

[U16] Py：命令行参数解析
来源：http://dali.ydzc1.top/Article/details/gt2sltqpkag.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gt2osftzwaf.html

[U17] Py：初始化日志
来源：http://dali.jianghu66.top/Article/details/gt2vcdsyuex.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnxiangtu.top/Article/details/gt2nxstcrxd.html

[U18] Py：预编译正则
来源：http://dali.iojbl.cn/Article/details/gt2gciuanpj.html

pat = re.compile(r"\d+")
来源：http://dali.gzhubu.top/Article/details/gt2fdsgnlxk.html

[U19] Py：正则替换带回调
来源：http://dali.gaohongyu789.top/Article/details/gt2qrnptjti.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sweek.top/Article/details/gt2kxxygxpo.html

[U20] Py：缓存函数结果
来源：http://dali.ydzc1.top/Article/details/gt2hguxnkbs.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gt2ctbcujvg.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2nbrpjxbp.html

@contextlib.contextmanager
来源：http://dali.shangyingyoupin.top/Article/details/gt2hsunshup.html

[U22] Py：矩阵转置
来源：http://dali.bjfxy.top/Article/details/gt2xpjyqvkk.html

list(zip(*m))
来源：http://dali.zhiwuduotai.top/Article/details/gt2zxqxxzsd.html

[U23] Py：分块读取大文件
来源：http://dali.sysykeji.top/Article/details/gt2nokadscv.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gt2axucyhhx.html

[U24] Py：路径操作
来源：http://dali.chenzaomai.com/Article/details/gt2ttrrsxjz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2jdcplsqz.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gt2maquiggp.html

csv.DictReader(f)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nunbqmot.html

[U26] Py：并发下载
来源：http://dali.sxryk.cn/Article/details/gt2ckscqsrm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yanxiufei.cn/Article/details/gt2uwgizzbt.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wffguxma.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hfpthk.cn/Article/details/gt2jahwnoaf.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gt2joufufwy.html

UserId = int
来源：http://dali.daxiang520.top/Article/details/gt2tdsctztg.html

[U29] Py：属性校验
来源：http://dali.pycfn.com/Article/details/gt2nwtbxtlh.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gt2gpwiowcj.html

[U30] Py：数据类
来源：http://dali.hnqzz.top/Article/details/gt2gwhzukyh.html

@dataclass(slots=True)
来源：http://dali.xinyue.icu/Article/details/gt2xvrnufgi.html

[U31] Py：单测
来源：http://dali.quarkkingdee.top/Article/details/gt2woisnpui.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gt2ksdubpgs.html

[U32] Py：代码格式化
来源：http://dali.yj202588.top/Article/details/gt2mstxjskw.html

ruff format . && ruff check --fix .
来源：http://dali.jqgufenzy.top/Article/details/gt2csphgmnd.html

[U33] Py：打包发布
来源：http://dali.mhx1999.top/Article/details/gt2fvldgzzu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shzxlz.cn/Article/details/gt2hluhakkv.html

[U34] Py：判断编码
来源：http://dali.hnqzz.top/Article/details/gt2vupqzfvx.html

chardet.detect(raw)
来源：http://dali.jyoumei.cn/Article/details/gt2pklzmfbq.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gt2wbzffhat.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gt2guorieyd.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gt2ndvfcrkc.html

schedule.every(10).minutes.do(job)
来源：http://dali.gotoacloud.top/Article/details/gt2szdrinmb.html

[U37] Py：读写 Excel
来源：http://dali.xuanzx.com/Article/details/gt2clxjfabr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.mhx1999.top/Article/details/gt2drtmumsb.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gt2aqpdbaxz.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gt2oypxetnd.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gt2fzairnjf.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gt2jsaeyjui.html

[U40] Py：打印到标准错误
来源：http://dali.zhixingplan.top/Article/details/gt2merukibg.html

print("err", file=sys.stderr)
来源：http://dali.hywenlv.cn/Article/details/gt2ogmueryj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.cdnleiting.top/Article/details/gt2fmlwytqa.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.quarkkingdee.top/Article/details/gt2gkbfomuo.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.c1oappe.top/Article/details/gt2dyoufcvt.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gt2zpkvevub.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gt2ymyaleny.html

namespace App\Http;
来源：http://dali.kuanghao11.cn/Article/details/gt2yofsbijp.html

[U44] PHP：开启严格类型
来源：http://dali.cucudq.cn/Article/details/gt2obtaxeki.html

declare(strict_types=1);
来源：http://dali.zhongyouzk.top/Article/details/gt2nstfsqco.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hammf.cn/Article/details/gt2mrcogzco.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2qirexyyb.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gt2vhrsyruz.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gt2ebcpsxta.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2pvgqjazx.html

int|string $id
来源：http://dali.tian-w.cn/Article/details/gt2cmfhdqzl.html

[U48] PHP：纯枚举
来源：http://dali.hongshengwenyu.top/Article/details/gt2okodzlbf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gt2eibvvlnd.html

[U49] PHP：只读属性
来源：http://dali.hysaishi.cn/Article/details/gt2lzyfrluc.html

public readonly string $name
来源：http://dali.zdqjudy.top/Article/details/gt2yqoxltqw.html

[U50] PHP：构造器属性提升
来源：http://dali.ivvv.top/Article/details/gt2lobzqply.html

public function __construct(private int $id) {}
来源：http://dali.jinqigufen.top/Article/details/gt2dqcpuplz.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gt2mevibfxm.html

[$a, $b] = $arr;
来源：http://dali.haohaochexian.top/Article/details/gt2ytfrakty.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zciaazts.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gt2vsgzbwwy.html

[U53] PHP：空合并运算符
来源：http://dali.yongpay.top/Article/details/gt2tslwdpmp.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gt2wflddxgj.html

[U54] PHP：空安全调用
来源：http://dali.daria6918.cn/Article/details/gt2vcpnnwvn.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gt2vxnskzmf.html

[U55] PHP：match 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gt2hsqlpida.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2jakdjemk.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2qqsfgjzj.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2agtlbuzy.html

[U57] PHP：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2notyjxui.html

"值: {$a}"
来源：http://dali.yanxiufei.cn/Article/details/gt2vmzsdlgl.html

[U58] PHP：数组三件套
来源：http://dali.0kj1m.cn/Article/details/gt2qvtvtttj.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gt2ruoibndr.html

[U59] PHP：自定义排序
来源：http://dali.gzhubu.top/Article/details/gt2hbsrknew.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cdnleiting.top/Article/details/gt2amkyfxoe.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gt2waexfhtp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2yhjdtqep.html

[U61] PHP：正则
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qeeqjeve.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.aibaodan.cn/Article/details/gt2ooxbcvqv.html

[U62] PHP：日期对象
来源：http://dali.jyoumei.cn/Article/details/gt2jmsokzck.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gt2tjesqbku.html

[U63] PHP：文件读写
来源：http://dali.nanxuanxn.top/Article/details/gt2dybufzmb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gt2bdnwjhut.html

[U64] PHP：目录遍历
来源：http://dali.yonumen.top/Article/details/gt2voiqktif.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhijiandao.cn/Article/details/gt2mtqwbjav.html

[U65] PHP：会话
来源：http://dali.jyoumei.cn/Article/details/gt2mhrwgcwu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2qnnmnayn.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gt2crsgdpbl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2jvhuicuv.html

[U67] PHP：处理文件上传
来源：http://dali.ppjwa.cn/Article/details/gt2ihzdhjbq.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.smart0.xyz/Article/details/gt2ziiiktcz.html

[U68] PHP：PDO 连接
来源：http://dali.guannengcc.top/Article/details/gt2rntxvtrz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.cheryme.top/Article/details/gt2rdozhmkt.html

[U69] PHP：PDO 预处理
来源：http://dali.chenlongwang.top/Article/details/gt2iypbkaux.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangdashe.top/Article/details/gt2omawxvel.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nwnstnab.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lndajipf.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gt2iwmudhib.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gt2igqywcpd.html

[U72] PHP：写错误日志
来源：http://dali.cucudq.cn/Article/details/gt2murykznu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgufenzy.top/Article/details/gt2rdkqipsm.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2cakfyjry.html

parse_ini_file("config.ini", true)
来源：http://dali.cashguo.top/Article/details/gt2okdylcqy.html

[U74] PHP：读取环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2pfsdeagz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daxiang520.top/Article/details/gt2oouzjxut.html

[U75] PHP：依赖注入
来源：http://dali.ydzc1.top/Article/details/gt2amapqktc.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gt2jkgoasho.html

[U76] PHP：简单路由
来源：http://dali.chenzaomai.com/Article/details/gt2rdbbubcw.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jiagoushi.top/Article/details/gt2ptadxpao.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gt2pwikkynt.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2nxvgxfim.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gt2lbiwytyb.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gt2jqsaaqcj.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2adixzhyc.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gt2yjjakrcf.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gt2nlfkycpd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yongpay.top/Article/details/gt2pgtrevui.html

[U81] JS：初始化项目
来源：http://dali.kuanghao11.cn/Article/details/gt2aibmlfqs.html

npm init -y;  npm i express
来源：http://dali.316326.xyz/Article/details/gt2nomsvyis.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gt2lfxkunrm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gt2amjvvyjz.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gt2qgbaknax.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gt2flimnyyt.html

[U84] JS：CommonJS 写法
来源：http://dali.yangfankeji.com/Article/details/gt2fzqvwxsm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.havefunace.top/Article/details/gt2sjzrqjxl.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bsvyscih.html

a?.b?.c
来源：http://dali.fengsongda.top/Article/details/gt2lwtvdqeu.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gt2kjlfqkca.html

a ?? b
来源：http://dali.xylfe.cn/Article/details/gt2dwodabex.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2lsbmxqut.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gt2puctvydy.html

[U88] JS：对象展开合并
来源：http://dali.bjfxy.top/Article/details/gt2fegtqsmq.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gt2oixdojah.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gt2yekzluqq.html

[...new Set(arr)]
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyqwbrnc.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gt2rydxtzce.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ppjwa.cn/Article/details/gt2ugtnuaby.html

[U91] JS：对象键值遍历
来源：http://dali.zhengqikj.top/Article/details/gt2prqlvxue.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gt2rvlmtynm.html

[U92] JS：深拷贝
来源：http://dali.svipenyu.cn/Article/details/gt2qbwalxxv.html

structuredClone(obj)
来源：http://dali.nwbrower.top/Article/details/gt2trruurms.html


<!-- 参考信息 -->