代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gt2qjatktgg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gt2zkplastg.html

[T06] Kotlin：集合映射
来源：http://dali.andypj.xyz/Article/details/gt2zmulzenk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gt2cdraytjy.html

[T07] Kotlin：集合过滤
来源：http://dali.0kj1m.cn/Article/details/gt2yjdgdrwe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gt2zvfuyvgz.html

[T08] Kotlin：数据类
来源：http://dali.jqgufenzy.top/Article/details/gt2eyyuleik.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gt2wtlwaqaa.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gt2ytdfeevb.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2oapcfozr.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2lcqtassc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ivvv.top/Article/details/gt2chejxikn.html

[T11] Kotlin：协程
来源：http://dali.gotoacloud.top/Article/details/gt2cznsgifs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guowangkeji.top/Article/details/gt2dlaitpth.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2mpxnwwmv.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gt2taertyzt.html

[T13] Kotlin：只读 Map
来源：http://dali.ehwqpu.com/Article/details/gt2tyjyifam.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gt2fesqdvel.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2pkpnlqel.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gt2efcbqaof.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gt2tkxpjast.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gt2cxxwamwj.html

[T16] Swift：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2nyycdgud.html

print("Hello")
来源：http://dali.jyoumei.cn/Article/details/gt2voyahftu.html

[T17] Swift：变量与常量
来源：http://dali.zhengqikj.top/Article/details/gt2jbctqwuc.html

var a = 1;  let b = 2
来源：http://dali.cheryme.top/Article/details/gt2gdmllgpn.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2eymhlbjj.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gt2nxmsmadk.html

[T19] Swift：可选绑定
来源：http://dali.c1oappe.top/Article/details/gt2ytqaerjf.html

if let n = opt { print(n) }
来源：http://dali.0kj1m.cn/Article/details/gt2ovxziqrs.html

[T20] Swift：数组操作
来源：http://dali.yuxming.cn/Article/details/gt2pidppvkk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gt2bwlojffa.html

[T21] Swift：遍历
来源：http://dali.yonumen.top/Article/details/gt2qfnsetew.html

for x in a { print(x) }
来源：http://dali.ivvv.top/Article/details/gt2yhdgtsux.html

[T22] Swift：字典
来源：http://dali.yvedp.cn/Article/details/gt2fqyuwrqr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fkncdimr.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gt2qeduvgem.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gt2nzsfudpf.html

[T24] Swift：闭包
来源：http://dali.havefunace.top/Article/details/gt2eskqmdie.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aizwys.cn/Article/details/gt2ypvmitaw.html

[T25] Swift：结构体
来源：http://dali.hnqzz.top/Article/details/gt2dsnelnuk.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itanfafx.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gt2qztoqmqs.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tyjfoewp.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2eosdolfr.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2cskqnwhf.html

[T28] Swift：枚举
来源：http://dali.zdqjudy.top/Article/details/gt2mkmyytby.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gt2dpoeanai.html

[T29] Swift：guard 提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2giwtoygw.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gt2szhojqop.html

[T30] Swift：协议
来源：http://dali.gotoacloud.top/Article/details/gt2fgfswrlj.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gt2tnghusiy.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2zyqnjaap.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2jzlewzbc.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rmwmuogw.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gt2bhyifoyz.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gt2tkdqnzgo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2yoodimwt.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gt2rbsjfihb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gt2slzjchax.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gt2qrgwxomy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2hoamhmuj.html

[T36] Lua：函数
来源：http://dali.c1oappe.top/Article/details/gt2urfbxuhq.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gt2xkhhwvbw.html

[T37] Lua：字符串拼接
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jynwaysp.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gt2uuvjshlv.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gt2vnyprqlm.html

if x > 0 then print("正") end
来源：http://dali.birdmap.top/Article/details/gt2sgxcoaav.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2ebaqjnxl.html

string.find(s, "%d+")
来源：http://dali.dashuyun.cn/Article/details/gt2opxyoywq.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxeguwcx.html

setmetatable({}, { __index = base })
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vabzxvwr.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gt2fkfxipsn.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gt2qatmefdf.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2ncwovcrm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fkcholvh.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gt2zuofnlbw.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2pnzqqoms.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gt2orqonyik.html

if ($a > 0) { print "正"; }
来源：http://dali.wangdashe.top/Article/details/gt2czvkzizh.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gt2upsktidc.html

for my $x (@arr) { print $x; }
来源：http://dali.cdnleiting.top/Article/details/gt2xaokdchb.html

[T46] Perl：哈希操作
来源：http://dali.mhx1999.top/Article/details/gt2ksqicqtb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xylfe.cn/Article/details/gt2kqgfkcqg.html

[T47] Perl：正则捕获
来源：http://dali.jinqigfzy.top/Article/details/gt2hxdlgsyo.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gt2afktyggi.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2scczcccx.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gt2hlsisalh.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gt2wzooizhi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2puhrmugd.html

[T50] Perl：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2gttciquj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jiagoushi.top/Article/details/gt2prpxoybl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tian-w.cn/Article/details/gt2wpeqelln.html

[T51] Scala：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2ppgvqezt.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ddhxfsxl.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2upuibwvl.html

val a = 1;  var b = 2
来源：http://dali.redwolf501.top/Article/details/gt2kxlelhgp.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2qebefjue.html

s"值: $b"
来源：http://dali.jlsjyb.cn/Article/details/gt2pjggiqwq.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2ginrfben.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gt2pxarvdrj.html

[T55] Scala：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2eeirqwth.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gt2xkuonnjd.html

[T56] Scala：样例类
来源：http://dali.wangshuangyany.cn/Article/details/gt2jrekvaod.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2esljtugm.html

[T57] Scala：模式匹配
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhivwyhj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gt2cdwaesig.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2brstnqas.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ivvv.top/Article/details/gt2vcdlfkmo.html

[T59] Scala：循环
来源：http://dali.jlsjyb.cn/Article/details/gt2uhgixmhb.html

for (i <- 1 to 10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2uuyefypy.html

[T60] Scala：折叠
来源：http://dali.sysykeji.top/Article/details/gt2tpsrslul.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2zvhjzotg.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2bzlibqqd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gt2oomkqkif.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2anradyne.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gt2fammloja.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gzhubu.top/Article/details/gt2mtkkksnr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2muwwiwno.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gt2veteymit.html

[U03] Py：加载 .env 配置
来源：http://dali.fzhhl.top/Article/details/gt2gshdgbri.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.kuanghao11.cn/Article/details/gt2nixngaac.html

[U04] Py：变量调试打印
来源：http://dali.fzhhl.top/Article/details/gt2tuufnofu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gt2dxudupsz.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gt2rrtsqpyi.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2sjsasntg.html

[U06] Py：合并两个字典
来源：http://dali.sysykeji.top/Article/details/gt2okjwhlxe.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gt2fgonvmke.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2znszioqm.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gt2vvcfucah.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gt2sznmklza.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fabysnrd.html

[U09] Py：字典取最大值的键
来源：http://dali.zdqjudy.top/Article/details/gt2hhdbezwn.html

max(d, key=d.get)
来源：http://dali.zdqjudy.top/Article/details/gt2bsycsgmb.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2hzvyqhsx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uffjsxzv.html

[U11] Py：生成器表达式
来源：http://dali.yuanzhike.top/Article/details/gt2chgrreql.html

(x * 2 for x in arr)
来源：http://dali.jyoumei.cn/Article/details/gt2mccqfiqv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gt2dhxhlygn.html

Counter(arr).most_common(3)
来源：http://dali.jlsjyb.cn/Article/details/gt2cszmnafh.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gt2ockfqpet.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gt2oupybgew.html

[U14] Py：分组收集到列表
来源：http://dali.zhijiandao.cn/Article/details/gt2whhdhzmw.html

defaultdict(list)
来源：http://dali.redwolf501.top/Article/details/gt2fzujkpal.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gt2vipwbesn.html

t = time.perf_counter()
来源：http://dali.cqqwz.cn/Article/details/gt2wtucwxth.html

[U16] Py：命令行参数解析
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ipplkjns.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.vqdsnc.cn/Article/details/gt2pbvqfntu.html

[U17] Py：初始化日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2rtdibkye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gt2wolxkyhw.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2iqjforpd.html

pat = re.compile(r"\d+")
来源：http://dali.andypj.xyz/Article/details/gt2dtacjdct.html

[U19] Py：正则替换带回调
来源：http://dali.daria6918.cn/Article/details/gt2pxylinho.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gt2fdeurogf.html

[U20] Py：缓存函数结果
来源：http://dali.tian-w.cn/Article/details/gt2knwnleos.html

@functools.lru_cache(maxsize=None)
来源：http://dali.mhx1999.top/Article/details/gt2kqbhkeru.html

[U21] Py：自定义上下文管理器
来源：http://dali.nwbrower.top/Article/details/gt2pezechqo.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2xklahznv.html

[U22] Py：矩阵转置
来源：http://dali.fengsongda.top/Article/details/gt2tkwbfchs.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gt2ltkoydtu.html

[U23] Py：分块读取大文件
来源：http://dali.nwbrower.top/Article/details/gt2syukijtu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gt2ufyxonlt.html

[U24] Py：路径操作
来源：http://dali.sysykeji.top/Article/details/gt2bctvcjpc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yvedp.cn/Article/details/gt2bxxnzitm.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gt2hvxhabmv.html

csv.DictReader(f)
来源：http://dali.zhoulong.xyz/Article/details/gt2lfuovbiv.html

[U26] Py：并发下载
来源：http://dali.yvedp.cn/Article/details/gt2cnyqgzcl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gt2atulykmx.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2czvuetzt.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gt2vgncnnns.html

[U28] Py：类型别名
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cfswkgbc.html

UserId = int
来源：http://dali.c1oappe.top/Article/details/gt2vlmfqyfk.html

[U29] Py：属性校验
来源：http://dali.vqdsnc.cn/Article/details/gt2skrdedia.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gt2ovgxqvci.html

[U30] Py：数据类
来源：http://dali.smart0.xyz/Article/details/gt2osbbslgn.html

@dataclass(slots=True)
来源：http://dali.nanxinkj.top/Article/details/gt2nydrvkym.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gt2cyhquuiy.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gt2jsbfqero.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gt2ksfqzvij.html

ruff format . && ruff check --fix .
来源：http://dali.haohaochexian.top/Article/details/gt2sbxwvlvx.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gt2ircjrash.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gt2emhodxgw.html

[U34] Py：判断编码
来源：http://dali.tian-w.cn/Article/details/gt2jkkrzaal.html

chardet.detect(raw)
来源：http://dali.bjfxy.top/Article/details/gt2gbnvgikb.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gt2fbixvgxv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zycfv.cn/Article/details/gt2apctefrj.html

[U36] Py：定时任务
来源：http://dali.jiagoushi.top/Article/details/gt2vwhnzagm.html

schedule.every(10).minutes.do(job)
来源：http://dali.shzxlz.cn/Article/details/gt2rxbnsbeq.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gt2plwvljdb.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gt2llxrobfk.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gt2nsdxncdi.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2lmnfpeam.html

[U39] Py：判断是否在交互环境
来源：http://dali.shuidangran.top/Article/details/gt2jzyqwdui.html

sys.stdout.isatty()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mmdzhrbc.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gt2nykcpgeo.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gt2mqxdkbda.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yongpay.top/Article/details/gt2ejwlogtw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gt2vyyhbsho.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gt2nfoseafs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jlsjyb.cn/Article/details/gt2uoysybxh.html

[U43] PHP：声明命名空间
来源：http://dali.sysykeji.top/Article/details/gt2hcrevygh.html

namespace App\Http;
来源：http://dali.hnqzz.top/Article/details/gt2gzkmpprz.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gt2jrorxvax.html

declare(strict_types=1);
来源：http://dali.vqdsnc.cn/Article/details/gt2qlgjmmvi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.andypj.xyz/Article/details/gt2lwsiaess.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ouxiwiwp.html

[U46] PHP：可空类型
来源：http://dali.hammf.cn/Article/details/gt2ziuwvfsi.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gt2vicegfbd.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2qluqsquz.html

int|string $id
来源：http://dali.ehwqpu.com/Article/details/gt2resljtix.html

[U48] PHP：纯枚举
来源：http://dali.sxryk.cn/Article/details/gt2vmtnwvng.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cqqwz.cn/Article/details/gt2ktceqnbr.html

[U49] PHP：只读属性
来源：http://dali.yvedp.cn/Article/details/gt2esdhnbew.html

public readonly string $name
来源：http://dali.vqdsnc.cn/Article/details/gt2ydhoiine.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gt2wrwxadah.html

public function __construct(private int $id) {}
来源：http://dali.dianchejie.cn/Article/details/gt2hzpdnfho.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gt2ztiflrbj.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gt2uxxjxmqb.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gt2rzqzhzoi.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gt2sbycgzmu.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2hxaqllsn.html

$v = $a ?? $b ?? "default";
来源：http://dali.yonumen.top/Article/details/gt2ypsyrmqy.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gt2smmfjdbz.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gt2mhsiomyl.html

[U55] PHP：match 表达式
来源：http://dali.jinqigufen.top/Article/details/gt2mypdpzad.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.fengsongda.top/Article/details/gt2ukedxhge.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gt2fycnvesk.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2xkyupwcy.html

[U57] PHP：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2cvtycnuy.html

"值: {$a}"
来源：http://dali.hnxiangtu.top/Article/details/gt2rzfozchm.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gt2wvonyjxf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qqpmpulc.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gt2bcztjvdi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rnmwvhgt.html

[U60] PHP：JSON 编解码
来源：http://dali.redwolf501.top/Article/details/gt2sxnvilre.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gt2zgqowjqr.html

[U61] PHP：正则
来源：http://dali.316326.xyz/Article/details/gt2wmfdxbor.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jyoumei.cn/Article/details/gt2oyvvuhsy.html

[U62] PHP：日期对象
来源：http://dali.hammf.cn/Article/details/gt2cljbzici.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gt2zhurnpmm.html

[U63] PHP：文件读写
来源：http://dali.tian-w.cn/Article/details/gt2astnmreu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shzxlz.cn/Article/details/gt2fxbsgguw.html

[U64] PHP：目录遍历
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjmpdquj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gt2tnbdvwaf.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gt2inmnzmcx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gt2cxpuyfgm.html

[U66] PHP：设置 Cookie
来源：http://dali.chenlongwang.top/Article/details/gt2osjfrqzb.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenlongwang.top/Article/details/gt2tdxmvehu.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gt2ocwscpqh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tian-w.cn/Article/details/gt2ujijjemo.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gt2pqbjspeu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gt2igvmwrrz.html

[U69] PHP：PDO 预处理
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vsnhmepz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yonumen.top/Article/details/gt2eunilaeo.html

[U70] PHP：PDO 事务
来源：http://dali.yj20258888.top/Article/details/gt2hgufehff.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gaohongyu789.top/Article/details/gt2gehnwiun.html

[U71] PHP：抛出异常
来源：http://dali.wangshuangyany.cn/Article/details/gt2sfgbvgpo.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj20258.top/Article/details/gt2ryeqnplc.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gt2gpzlezrh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cucudq.cn/Article/details/gt2owxvtpxn.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gt2qbcfddyr.html

parse_ini_file("config.ini", true)
来源：http://dali.cqqwz.cn/Article/details/gt2rltwqade.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2ovxxgaxj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvtwmqbh.html

[U75] PHP：依赖注入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kcnnqcqw.html

composer require psr/container
来源：http://dali.jinqigufen.top/Article/details/gt2iqedgdgi.html

[U76] PHP：简单路由
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oqpgfaqh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.pengpengdd.cyou/Article/details/gt2dlemnwag.html

[U77] PHP：模板渲染
来源：http://dali.fengsongda.top/Article/details/gt2cnoeqhnn.html

composer require twig/twig
来源：http://dali.nanxinkj.top/Article/details/gt2wqljsjbw.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2drozrsyu.html

composer require --dev phpunit/phpunit
来源：http://dali.xinyue.icu/Article/details/gt2gtlbydta.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gt2iocnqevz.html

composer require --dev phpstan/phpstan
来源：http://dali.sufxvd.cn/Article/details/gt2uxlgirve.html

[U80] PHP：代码规范修复
来源：http://dali.shzxlz.cn/Article/details/gt2bmamzmjh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.dianchejie.cn/Article/details/gt2sfafhczp.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ygpibubh.html

npm init -y;  npm i express
来源：http://dali.ehwqpu.com/Article/details/gt2wvosgzem.html

[U82] JS：package.json 脚本
来源：http://dali.bjfxy.top/Article/details/gt2tsgbgnvv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gt2tdtdypml.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gt2qpjrbdsw.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.c1oappe.top/Article/details/gt2fpngrqvq.html

[U84] JS：CommonJS 写法
来源：http://dali.gogol.net.cn/Article/details/gt2xrgguhhx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jiagoushi.top/Article/details/gt2icthsvko.html

[U85] JS：可选链
来源：http://dali.cashguo.top/Article/details/gt2qcyuwdtr.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gt2hfghmzgg.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gt2jfiinzig.html

a ?? b
来源：http://dali.shuidangran.top/Article/details/gt2oyxlbgyd.html

[U87] JS：解构默认值
来源：http://dali.sysykeji.top/Article/details/gt2lhtulcay.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zhixingplan.top/Article/details/gt2kcmklyjm.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mrauueqh.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gt2wwbjfksz.html

[U89] JS：数组去重
来源：http://dali.jqgfzy.top/Article/details/gt2rombdoxd.html

[...new Set(arr)]
来源：http://dali.ppjwa.cn/Article/details/gt2okgwsnya.html

[U90] JS：数字数组排序
来源：http://dali.tianlin.xyz/Article/details/gt2fojjjyyx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lfoelmwe.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ptjfplht.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gt2hukkuskf.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2nznprgmd.html

structuredClone(obj)
来源：http://dali.chenzaomai.com/Article/details/gt2adrvbtej.html


<!-- 参考信息 -->