代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gt2vnlmvtdp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhengqikj.top/Article/details/gt2lmzxxulo.html

[T06] Kotlin：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2bexbgpyf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2prjdnnlh.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2ctoyybpo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gt2hnwsalor.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gt2pjxqucjm.html

data class User(val name: String, val age: Int)
来源：http://dali.yongpay.top/Article/details/gt2qavzfhik.html

[T09] Kotlin：扩展函数
来源：http://dali.ehwqpu.com/Article/details/gt2bixtajsf.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gt2airpowsk.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gt2nfgkoygm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2mqklveny.html

[T11] Kotlin：协程
来源：http://dali.ehwqpu.com/Article/details/gt2zlcwddwe.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gt2ijtyrcbm.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gt2woedrxok.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2svzdrcuo.html

[T13] Kotlin：只读 Map
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzrnfdqo.html

val m = mapOf("a" to 1)
来源：http://dali.andypj.xyz/Article/details/gt2btubhfse.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gt2cgjdewjp.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gt2zxntpsou.html

[T15] Kotlin：接口
来源：http://dali.hammf.cn/Article/details/gt2eflsqqha.html

interface Shape { fun area(): Double }
来源：http://dali.zhixingplan.top/Article/details/gt2sjuwycqf.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gt2xklpmrkm.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jgxqyrqk.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2yguavplo.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2wihcbzki.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gt2cskzbekf.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gt2pfkabbpi.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2fdynpjbd.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gt2kpbhmarb.html

[T20] Swift：数组操作
来源：http://dali.gotoacloud.top/Article/details/gt2bjngmrsp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gt2jnerdalq.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2xgqjohui.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gt2ajimkivd.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gt2syagutpr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2ierohcvp.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2wgsgmjwv.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2mbnknxbd.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gt2zpceucjh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gt2vlojmvxd.html

[T25] Swift：结构体
来源：http://dali.fengsongda.top/Article/details/gt2zuppqype.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gt2msnevxlf.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gt2lytqwpjz.html

class A: Base { override func f() {} }
来源：http://dali.dianchejie.cn/Article/details/gt2matmsmkn.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gt2qcbstzfs.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gt2thgqqyaw.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gt2oepbwjdv.html

enum Color { case red, green }
来源：http://dali.nanxuanxn.top/Article/details/gt2ayhbnmfh.html

[T29] Swift：guard 提前返回
来源：http://dali.meibo888.top/Article/details/gt2rmiamirz.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gt2gkoimgor.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2sexffozb.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gt2ypxpekvo.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2autpezxs.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2monkyccx.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2sttagqeh.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gt2vmkniogz.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gt2dkzquins.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cqqwz.cn/Article/details/gt2pqpcvwdx.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gt2ohzovkoe.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2lmaayazd.html

[T35] Lua：字典表
来源：http://dali.ivvv.top/Article/details/gt2jdrucstr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ydzc1.top/Article/details/gt2yqiwrpqu.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gt2vbunnrut.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2ijydqruh.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2smlxlmgs.html

"a" .. "b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dafemnlz.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2ttbvglgw.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2isgczvut.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gt2zerilxfk.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gt2isiuezhb.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gt2bvxactgg.html

setmetatable({}, { __index = base })
来源：http://dali.sufxvd.cn/Article/details/gt2oryluhga.html

[T41] Perl：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2nibuuqvn.html

print "Hello\n";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gmxmiauo.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2xasezvmd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gt2wczrnvrc.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gt2kuvejnmq.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gt2savrtkqu.html

[T44] Perl：条件
来源：http://dali.jinqigufen.top/Article/details/gt2hjdzgdrm.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gt2erwvuect.html

[T45] Perl：数组遍历
来源：http://dali.xuetiantiany.cn/Article/details/gt2oslgybft.html

for my $x (@arr) { print $x; }
来源：http://dali.jyoumei.cn/Article/details/gt2guvfrmou.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gt2uherseaj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wmvsljpj.html

[T47] Perl：正则捕获
来源：http://dali.jiagoushi.top/Article/details/gt2tajuhjgn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gt2aczdfioa.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2clckslvu.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gt2ttyswaho.html

[T49] Perl：函数
来源：http://dali.9152youxi.cn/Article/details/gt2tyrkdooo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2wuxlywpd.html

[T50] Perl：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2zvazfprn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gt2lzmtflvh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.snrcjt.cn/Article/details/gt2aezznpjx.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2hazsanju.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alkxyztb.html

[T52] Scala：变量
来源：http://dali.yonumen.top/Article/details/gt2ptqlibbq.html

val a = 1;  var b = 2
来源：http://dali.daria6918.cn/Article/details/gt2zfuchgau.html

[T53] Scala：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2klejqxvb.html

s"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2dblspojp.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gt2ouwwfpgq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gt2aeksebxy.html

[T55] Scala：集合过滤
来源：http://dali.daria6918.cn/Article/details/gt2uqjepshu.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gt2wiqgsrop.html

[T56] Scala：样例类
来源：http://dali.hammf.cn/Article/details/gt2kcpcuwqi.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gt2omrygfuz.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gt2zggmwpee.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ccpbrkck.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gt2zatgibci.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dszbnnth.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2blyeryug.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gt2eheamvra.html

[T60] Scala：折叠
来源：http://dali.xziqi.cn/Article/details/gt2aqynpkka.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gt2xgarghjs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2flnnzktc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aibaodan.cn/Article/details/gt2hdtombae.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kpygmosp.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gt2bqlupmbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gt2snqcsobw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gt2qxoqwdcq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ssxeycfe.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gt2rjzhzjmm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gt2svfficyb.html

[U04] Py：变量调试打印
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybtbmiss.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gt2ljzrwjgs.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gt2tiyyczju.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gt2elyvhchm.html

[U06] Py：合并两个字典
来源：http://dali.vqdsnc.cn/Article/details/gt2khxdxoru.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gt2kwazffsw.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gt2wzeqliou.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gt2sdyzyshy.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gt2vfhnntql.html

[y for x in nested for y in x]
来源：http://dali.xziqi.cn/Article/details/gt2lcpdjeic.html

[U09] Py：字典取最大值的键
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ehvzrsvk.html

max(d, key=d.get)
来源：http://dali.zhixingplan.top/Article/details/gt2fngdpqcg.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gt2ffpflxei.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cqqwz.cn/Article/details/gt2wyjgrrds.html

[U11] Py：生成器表达式
来源：http://dali.tanke756.top/Article/details/gt2mozlhvha.html

(x * 2 for x in arr)
来源：http://dali.aibaodan.cn/Article/details/gt2gsqkblbg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gotoacloud.top/Article/details/gt2sajsdhsb.html

Counter(arr).most_common(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2beesvcrb.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gt2yvlrzaou.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gt2qttqpwmb.html

[U14] Py：分组收集到列表
来源：http://dali.jlsjyb.cn/Article/details/gt2ccmvxlpi.html

defaultdict(list)
来源：http://dali.nanxuanxn.top/Article/details/gt2ycfspvzu.html

[U15] Py：高精度计时
来源：http://dali.xuetiantiany.cn/Article/details/gt2ufyuqeiw.html

t = time.perf_counter()
来源：http://dali.yuanzhike.top/Article/details/gt2mcnsgfns.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gt2jhdkkcbp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pengpengdd.cyou/Article/details/gt2fkfqqoku.html

[U17] Py：初始化日志
来源：http://dali.xylfe.cn/Article/details/gt2twlcakdf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jinqigufen.top/Article/details/gt2opyoazfd.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gt2swyrvrtp.html

pat = re.compile(r"\d+")
来源：http://dali.pengpengdd.cyou/Article/details/gt2crfldpgv.html

[U19] Py：正则替换带回调
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnhfuogu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.smart0.xyz/Article/details/gt2wgdgbltx.html

[U20] Py：缓存函数结果
来源：http://dali.nanxinkj.top/Article/details/gt2uehhbhke.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yongpay.top/Article/details/gt2nzjtqyvv.html

[U21] Py：自定义上下文管理器
来源：http://dali.jqgfzy.top/Article/details/gt2locdjsci.html

@contextlib.contextmanager
来源：http://dali.haohaochexian.top/Article/details/gt2odrequpv.html

[U22] Py：矩阵转置
来源：http://dali.shzxlz.cn/Article/details/gt2vbxiwloo.html

list(zip(*m))
来源：http://dali.xuanzx.com/Article/details/gt2qidtllfx.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2obwlpgqc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.andypj.xyz/Article/details/gt2gfljapho.html

[U24] Py：路径操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyuhvlyn.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jqvkbsle.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2rjsgmfvx.html

csv.DictReader(f)
来源：http://dali.chenlongwang.top/Article/details/gt2eyqyjyvd.html

[U26] Py：并发下载
来源：http://dali.zhiwuduotai.top/Article/details/gt2xxpcwczb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gt2uolfsjaz.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gt2sprefbjk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hnqzz.top/Article/details/gt2qbaxwmru.html

[U28] Py：类型别名
来源：http://dali.meibo888.top/Article/details/gt2plzebpqz.html

UserId = int
来源：http://dali.chenzaomai.com/Article/details/gt2cpnzzpnq.html

[U29] Py：属性校验
来源：http://dali.cqqwz.cn/Article/details/gt2xlrqqbhr.html

@property 与 @x.setter 配合
来源：http://dali.jianghu66.top/Article/details/gt2thylijzf.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gt2sxliplwz.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bosflexs.html

[U31] Py：单测
来源：http://dali.jlsjyb.cn/Article/details/gt2qkqbslkt.html

python -m pytest -q
来源：http://dali.sufxvd.cn/Article/details/gt2dhbwazar.html

[U32] Py：代码格式化
来源：http://dali.cqqwz.cn/Article/details/gt2zqrmsqlg.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gt2wieutiox.html

[U33] Py：打包发布
来源：http://dali.shzxlz.cn/Article/details/gt2gutpzisn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gaohongyu789.top/Article/details/gt2yblbapgv.html

[U34] Py：判断编码
来源：http://dali.sufxvd.cn/Article/details/gt2koydlbjf.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gt2zsekzchz.html

[U35] Py：发送邮件
来源：http://dali.hnqzz.top/Article/details/gt2znulsiyf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gt2cxjejgmr.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gt2fxsaldbm.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigufen.top/Article/details/gt2ttyiaxmx.html

[U37] Py：读写 Excel
来源：http://dali.ivvv.top/Article/details/gt2nphltmpd.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ydzc1.top/Article/details/gt2ctstkyoi.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnqzz.top/Article/details/gt2kutsiodl.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gt2eiiazomp.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gt2ckglbczu.html

sys.stdout.isatty()
来源：http://dali.yj20258888.top/Article/details/gt2wvywsidn.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gt2bhjhzixk.html

print("err", file=sys.stderr)
来源：http://dali.nanxinkj.top/Article/details/gt2oolnzqmz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2vrqoigns.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gt2asxfcqpr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tanke756.top/Article/details/gt2kiixsmab.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jianghu66.top/Article/details/gt2tlxuirpz.html

[U43] PHP：声明命名空间
来源：http://dali.yj20258888.top/Article/details/gt2uszeemvj.html

namespace App\Http;
来源：http://dali.yvedp.cn/Article/details/gt2lfqqxcgl.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gt2thtgwktk.html

declare(strict_types=1);
来源：http://dali.yuxming.cn/Article/details/gt2jqcbzwgw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.nwbrower.top/Article/details/gt2hehzlgjf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gt2horsylny.html

[U46] PHP：可空类型
来源：http://dali.snrcjt.cn/Article/details/gt2ogqnexll.html

?string $name = null
来源：http://dali.gogol.net.cn/Article/details/gt2yfcuoego.html

[U47] PHP：联合类型
来源：http://dali.nwbrower.top/Article/details/gt2eugfvpyp.html

int|string $id
来源：http://dali.xuetiantiany.cn/Article/details/gt2iquwudhu.html

[U48] PHP：纯枚举
来源：http://dali.chenzaomai.com/Article/details/gt2jonwnhyc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gt2paxrjnll.html

[U49] PHP：只读属性
来源：http://dali.gotoacloud.top/Article/details/gt2yzzrwmck.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gt2hupvvyry.html

[U50] PHP：构造器属性提升
来源：http://dali.shangyingyoupin.top/Article/details/gt2rnobdyiu.html

public function __construct(private int $id) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2isfjovmk.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gt2lnhwvehp.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gt2tfvqxbps.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gt2rwrkjfkx.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gt2nxqvddvc.html

[U53] PHP：空合并运算符
来源：http://dali.smart0.xyz/Article/details/gt2atlzjxux.html

$v = $a ?? $b ?? "default";
来源：http://dali.ydzc1.top/Article/details/gt2gdhlhdoz.html

[U54] PHP：空安全调用
来源：http://dali.jqgfzy.top/Article/details/gt2oogfdsnx.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gt2kaosexuz.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gt2eetfulcy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2apoqyfgx.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gt2akvgatzt.html

f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gt2zpvpornm.html

[U57] PHP：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2jegbtjav.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gt2ukfkfewi.html

[U58] PHP：数组三件套
来源：http://dali.birdmap.top/Article/details/gt2bguqcjyu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2egfkbtfu.html

[U59] PHP：自定义排序
来源：http://dali.aibaodan.cn/Article/details/gt2dbevqruw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsrsetok.html

[U60] PHP：JSON 编解码
来源：http://dali.sysykeji.top/Article/details/gt2tpvjxwmh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hongshengwenyu.top/Article/details/gt2lveifqgq.html

[U61] PHP：正则
来源：http://dali.aibaodan.cn/Article/details/gt2zrygmxdy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gt2typzjafc.html

[U62] PHP：日期对象
来源：http://dali.meibo888.top/Article/details/gt2jskorgkk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhijiandao.cn/Article/details/gt2haiyipwq.html

[U63] PHP：文件读写
来源：http://dali.mhx1999.top/Article/details/gt2ghtfkqse.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.meibo888.top/Article/details/gt2uvoehnim.html

[U64] PHP：目录遍历
来源：http://dali.pengpengdd.cyou/Article/details/gt2zsbmkguy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2melkmgzq.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gt2kdepoebd.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fpqwnoou.html

[U66] PHP：设置 Cookie
来源：http://dali.ydzc1.top/Article/details/gt2dwbrkvfa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuxming.cn/Article/details/gt2rdsiogof.html

[U67] PHP：处理文件上传
来源：http://dali.yongpay.top/Article/details/gt2xqwygrim.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhengqikj.top/Article/details/gt2qlfzgjbx.html

[U68] PHP：PDO 连接
来源：http://dali.haohaochexian.top/Article/details/gt2gvocraqe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hammf.cn/Article/details/gt2odbdjffu.html

[U69] PHP：PDO 预处理
来源：http://dali.gotoacloud.top/Article/details/gt2ubzkgcgp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gt2drhwjsuo.html

[U70] PHP：PDO 事务
来源：http://dali.jiagoushi.top/Article/details/gt2abflqnxk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cdnleiting.top/Article/details/gt2vljltxui.html

[U71] PHP：抛出异常
来源：http://dali.xuetiantiany.cn/Article/details/gt2napjkhpu.html

throw new RuntimeException("失败", 500);
来源：http://dali.andypj.xyz/Article/details/gt2eegjixmy.html

[U72] PHP：写错误日志
来源：http://dali.xziqi.cn/Article/details/gt2ypdzhifw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gt2lgbzjhhh.html

[U73] PHP：读取 ini 配置
来源：http://dali.316326.xyz/Article/details/gt2dutgmrnk.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258888.top/Article/details/gt2ahawwpwd.html

[U74] PHP：读取环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2unuouqbi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgufenzy.top/Article/details/gt2pulagdnk.html

[U75] PHP：依赖注入
来源：http://dali.jqgufenzy.top/Article/details/gt2eonwpkok.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qytcnzok.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gt2bowpgjww.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenzaomai.com/Article/details/gt2fgrfdecx.html

[U77] PHP：模板渲染
来源：http://dali.nanxuanxn.top/Article/details/gt2tbubbzes.html

composer require twig/twig
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uejxepjz.html

[U78] PHP：单元测试
来源：http://dali.xuetiantiany.cn/Article/details/gt2vafbjnkn.html

composer require --dev phpunit/phpunit
来源：http://dali.zhixingplan.top/Article/details/gt2bbxftulx.html

[U79] PHP：静态分析
来源：http://dali.jlsjyb.cn/Article/details/gt2npuxzkct.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jqnubudz.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnsmybhh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxinkj.top/Article/details/gt2omwkfscg.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gt2gffscwld.html

npm init -y;  npm i express
来源：http://dali.sufxvd.cn/Article/details/gt2uthewsuz.html

[U82] JS：package.json 脚本
来源：http://dali.hnxiangtu.top/Article/details/gt2spwzjhll.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guannengcc.top/Article/details/gt2mgvlfsvc.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gt2wbesszbm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.nanxinkj.top/Article/details/gt2fwnixnlu.html

[U84] JS：CommonJS 写法
来源：http://dali.mhx1999.top/Article/details/gt2znanjdql.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwyndrnj.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gt2usnikwha.html

a?.b?.c
来源：http://dali.yangfankeji.com/Article/details/gt2cyufriyh.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gt2yejgypwl.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gt2dvekfycu.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gt2vnjcszus.html

const { a = 1, b = 2 } = obj;
来源：http://dali.feifeiyinyue.top/Article/details/gt2asrjbben.html

[U88] JS：对象展开合并
来源：http://dali.snrcjt.cn/Article/details/gt2noanoock.html

{ ...a, ...b }
来源：http://dali.jianghu66.top/Article/details/gt2hzidjkjx.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gt2hpxgwhuc.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gt2cwmmfnud.html

[U90] JS：数字数组排序
来源：http://dali.iojbl.cn/Article/details/gt2towtbfwk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gt2mpceulav.html

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gt2xergbmeg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yangfankeji.com/Article/details/gt2hikpqcox.html

[U92] JS：深拷贝
来源：http://dali.dashuyun.cn/Article/details/gt2icrfcilz.html

structuredClone(obj)
来源：http://dali.ydzc1.top/Article/details/gt2bkaznyln.html


<!-- 参考信息 -->