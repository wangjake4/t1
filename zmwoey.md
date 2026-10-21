代发 wailian999

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtylfvlalb.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtkqweklqu.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtwnxyezjt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hfpthk.cn/Article/details/gtiyxvgqax.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxuanxn.top/Article/details/gtiqvtwkdz.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtzxiqgdxv.html

[T04] Kotlin：空安全
来源：http://dali.hammf.cn/Article/details/gtbypxairz.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtadpefhbe.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtwnjfnhen.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.redwolf501.top/Article/details/gtzssnazmq.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtiiengfhx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtvqqaxwrw.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtyzpdliny.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gtglbbygyk.html

[T08] Kotlin：数据类
来源：http://dali.yj20258888.top/Article/details/gtxcfttzbb.html

data class User(val name: String, val age: Int)
来源：http://dali.tanke756.top/Article/details/gtcqlcbqxb.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtbvtauktp.html

fun String.exclaim() = this + "!"
来源：http://dali.shzxlz.cn/Article/details/gtqezpmifa.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgwdriymt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtqkzgdxgc.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtgxnrllhi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yanxiufei.cn/Article/details/gtjdrazpny.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtevauwbrh.html

val (a, b) = Pair(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtlpjcauud.html

[T13] Kotlin：只读 Map
来源：http://dali.fzhhl.top/Article/details/gtwwcgtawp.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtjnkqnicj.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtcuvnzvel.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtfopcipfo.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gtkxrkyynr.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gtqhnrmovy.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtkwcqnbmk.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtkzmjqtfw.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtpilwwoto.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtubrstkbj.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtgflecnoh.html

"值: \(b)"
来源：http://dali.bjfxy.top/Article/details/gtsrursodv.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtdarfkazu.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gttweqyicy.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtfsgdprpa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtpcuuwjyb.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtspnwbrmr.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtzjatymvy.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtozvoknvg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenlongwang.top/Article/details/gthggncnmk.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gthjrfzcyp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtythmoimj.html

[T24] Swift：闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqmisuej.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuanzx.com/Article/details/gtvwgmjbuk.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gthscakwmq.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtbtzwbvgr.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtbhubdzlc.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoionhtpy.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtdafaadei.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtdivfhbhn.html

[T28] Swift：枚举
来源：http://dali.nanxuanxn.top/Article/details/gtpxixrtbm.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtxbaiyiys.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtkbonlaen.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gtpdhefesw.html

[T30] Swift：协议
来源：http://dali.ydzc1.top/Article/details/gtuwxusvsg.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtzkzodpdw.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gthmcgmjhp.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtjwlzjbqr.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gteghohbkc.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtvhorabtb.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtvjrozbue.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gtawbfbgks.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtqpztedzo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.dashuyun.cn/Article/details/gtqnjkfczg.html

[T35] Lua：字典表
来源：http://dali.hysaishi.cn/Article/details/gtezsscorj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtlnlzxbku.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtbdqzfxmw.html

function add(a, b) return a + b end
来源：http://dali.yj202588.top/Article/details/gtvsneuzlk.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gthnapymft.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtoqzgxdod.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gtqduphvpz.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtvpkxphze.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gthxtqshvx.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtlqkebrpe.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtlldfkuzd.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigfzy.top/Article/details/gtfjwkpnwi.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtwiqnsvhr.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtmnfzqmgn.html

[T42] Perl：变量类型
来源：http://dali.birdmap.top/Article/details/gtftpempug.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.c1oappe.top/Article/details/gtpsdsotrz.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtcilwznux.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtbsswibsq.html

[T44] Perl：条件
来源：http://dali.zhongyouzk.top/Article/details/gtedksnseg.html

if ($a > 0) { print "正"; }
来源：http://dali.tanke756.top/Article/details/gtayvofxzz.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gtkzpbcbyh.html

for my $x (@arr) { print $x; }
来源：http://dali.xziqi.cn/Article/details/gtnigzlvzv.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtzbjlxqru.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjqrsbwnj.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gtoxbpjpvn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmzmngohz.html

[T48] Perl：正则替换
来源：http://dali.ppjwa.cn/Article/details/gtdanmgzui.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtphwxiind.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gthbzxulsl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtqsdykgdj.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtoykeajpa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrhioylh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zhijiandao.cn/Article/details/gtpwxpmxvx.html

[T51] Scala：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtyshxcdek.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtnvkanzqg.html

[T52] Scala：变量
来源：http://dali.9152youxi.cn/Article/details/gtsvriybak.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtrdntqpyw.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaupweyof.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtepnlzjjp.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtinemjxkp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtwxxpdppv.html

[T55] Scala：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtzrclbcqs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtbznqvuab.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtlrscjlry.html

case class User(name: String, age: Int)
来源：http://dali.yj20258888.top/Article/details/gtigaholdm.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtlntifjxv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtakmqdvuc.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtemywkuyx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gtpwsastvo.html

[T59] Scala：循环
来源：http://dali.xylfe.cn/Article/details/gtnrlrwobl.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtloxavsuh.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtbarcxdnw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shangyingyoupin.top/Article/details/gtbpnqpber.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdwriunzz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtmimbpsru.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuoqzihid.html

[U01] Py：创建虚拟环境
来源：http://dali.zhiwuduotai.top/Article/details/gtoevqvswl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gtavmeggwc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.daria6918.cn/Article/details/gtebivobkv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtirahmoht.html

[U03] Py：加载 .env 配置
来源：http://dali.feifeiyinyue.top/Article/details/gtjebcmhle.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gtpnpvvczw.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtuilmxivp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtbsuagtpe.html

[U05] Py：列表去重且保序
来源：http://dali.cashguo.top/Article/details/gtiwhlbvje.html

list(dict.fromkeys(arr))
来源：http://dali.birdmap.top/Article/details/gtamsivqps.html

[U06] Py：合并两个字典
来源：http://dali.wangshuangyany.cn/Article/details/gtdahsxeoj.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gtrushwvbb.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gthmacnfsn.html

{v: k for k, v in d.items()}
来源：http://dali.havefunace.top/Article/details/gtfmxsjcug.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtvdzwwxbf.html

[y for x in nested for y in x]
来源：http://dali.quarkkingdee.top/Article/details/gtkcimkzvt.html

[U09] Py：字典取最大值的键
来源：http://dali.zhiwuduotai.top/Article/details/gtmiotkvid.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtolcpevye.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gthqyiatwg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gtvufilfzr.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtkuehfowl.html

(x * 2 for x in arr)
来源：http://dali.guannengcc.top/Article/details/gtcqxvmohj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258888.top/Article/details/gtdftdkwjg.html

Counter(arr).most_common(3)
来源：http://dali.zhixingplan.top/Article/details/gtuxpockxv.html

[U13] Py：固定长度队列
来源：http://dali.andypj.xyz/Article/details/gtpbujxuzx.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtputgsfgv.html

[U14] Py：分组收集到列表
来源：http://dali.9152youxi.cn/Article/details/gtzkmxhoab.html

defaultdict(list)
来源：http://dali.snrcjt.cn/Article/details/gtmvmzclys.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtnxkdihut.html

t = time.perf_counter()
来源：http://dali.9152youxi.cn/Article/details/gtjaudzfpp.html

[U16] Py：命令行参数解析
来源：http://dali.aibaodan.cn/Article/details/gtlthlrtic.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.9152youxi.cn/Article/details/gttgeeiazq.html

[U17] Py：初始化日志
来源：http://dali.smart0.xyz/Article/details/gtxjtfdhii.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuvgmlxk.html

[U18] Py：预编译正则
来源：http://dali.zhoulong.xyz/Article/details/gtvfwifxov.html

pat = re.compile(r"\d+")
来源：http://dali.tianlin.xyz/Article/details/gtyygqbxni.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gthaflylpe.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinqigfzy.top/Article/details/gtjzdeyril.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gtlolfyfal.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtspxwypen.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtjpplgekb.html

@contextlib.contextmanager
来源：http://dali.wangdashe.top/Article/details/gtirwdfkoq.html

[U22] Py：矩阵转置
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsjlblfu.html

list(zip(*m))
来源：http://dali.guannengcc.top/Article/details/gtdxjlnbkh.html

[U23] Py：分块读取大文件
来源：http://dali.yueranfly.top/Article/details/gtuaprboyi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtouzcfear.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gtfrslaxmb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtsmfklogg.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtlqqnqdba.html

csv.DictReader(f)
来源：http://dali.xziqi.cn/Article/details/gtiwcwbqki.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtagqmduke.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dashuyun.cn/Article/details/gthbcnmyrs.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gtermltsft.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtuedmkhfn.html

[U28] Py：类型别名
来源：http://dali.gotoacloud.top/Article/details/gtnmjroyof.html

UserId = int
来源：http://dali.hnxiangtu.top/Article/details/gtqgyayhmt.html

[U29] Py：属性校验
来源：http://dali.zdqjudy.top/Article/details/gtzumslzoq.html

@property 与 @x.setter 配合
来源：http://dali.chenjidiqi.icu/Article/details/gtwdpvagsw.html

[U30] Py：数据类
来源：http://dali.xylfe.cn/Article/details/gtxysnczin.html

@dataclass(slots=True)
来源：http://dali.zhoulong.xyz/Article/details/gtfofqrsut.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtnjpbpojr.html

python -m pytest -q
来源：http://dali.jiagoushi.top/Article/details/gtlmcqerft.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtcddhtyog.html

ruff format . && ruff check --fix .
来源：http://dali.ehwqpu.com/Article/details/gtnzuxehxl.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtuvxghvrn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gtefnnedaj.html

[U34] Py：判断编码
来源：http://dali.tianlin.xyz/Article/details/gtffurpygd.html

chardet.detect(raw)
来源：http://dali.andypj.xyz/Article/details/gtmbrinzev.html

[U35] Py：发送邮件
来源：http://dali.iojbl.cn/Article/details/gtclkhvera.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.iojbl.cn/Article/details/gtmqcvjnff.html

[U36] Py：定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtoaukhohd.html

schedule.every(10).minutes.do(job)
来源：http://dali.hfpthk.cn/Article/details/gtqhjwthsr.html

[U37] Py：读写 Excel
来源：http://dali.hysaishi.cn/Article/details/gtdctygiwr.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrffetfvf.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtfzmkpgim.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gthooavikg.html

[U39] Py：判断是否在交互环境
来源：http://dali.shzxlz.cn/Article/details/gtcqyxjjaa.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtgsomodol.html

[U40] Py：打印到标准错误
来源：http://dali.mhx1999.top/Article/details/gteeltltcw.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtqeucllim.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.haohaochexian.top/Article/details/gtdtfhmrcz.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtdbwgvify.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zdqjudy.top/Article/details/gtistpklhq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtelxzquwl.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtuqswqufi.html

namespace App\Http;
来源：http://dali.0kj1m.cn/Article/details/gtmhanmqfe.html

[U44] PHP：开启严格类型
来源：http://dali.dashuyun.cn/Article/details/gtcsridbpd.html

declare(strict_types=1);
来源：http://dali.yj20258.top/Article/details/gtljnqxssg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.feifeiyinyue.top/Article/details/gtqtjlmgln.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gttvyeusrt.html

[U46] PHP：可空类型
来源：http://dali.sweek.top/Article/details/gtyxkelvcn.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtzutgdrhm.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gtvqclfejp.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtfajdvgtl.html

[U48] PHP：纯枚举
来源：http://dali.cdnleiting.top/Article/details/gtuinubfbd.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlxxhpzpr.html

[U49] PHP：只读属性
来源：http://dali.0kj1m.cn/Article/details/gtpmdiznpr.html

public readonly string $name
来源：http://dali.yuanzhike.top/Article/details/gtnpxobjle.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrmmtykn.html

public function __construct(private int $id) {}
来源：http://dali.zhijiandao.cn/Article/details/gtwnzazhan.html

[U51] PHP：数组解构
来源：http://dali.sysykeji.top/Article/details/gtykbhirel.html

[$a, $b] = $arr;
来源：http://dali.hywenlv.cn/Article/details/gtnffchngn.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gthzavosfa.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwrsifhuj.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gtipxjrgdp.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtgbapmofi.html

[U54] PHP：空安全调用
来源：http://dali.hammf.cn/Article/details/gtfpupacyz.html

$obj?->method()
来源：http://dali.ppjwa.cn/Article/details/gttlegfcxm.html

[U55] PHP：match 表达式
来源：http://dali.yueranfly.top/Article/details/gtirxlthug.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtjhwinizz.html

[U56] PHP：命名参数
来源：http://dali.iojbl.cn/Article/details/gtfgstocwl.html

f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtefgeknrw.html

[U57] PHP：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtlppsiyww.html

"值: {$a}"
来源：http://dali.kuanghao11.cn/Article/details/gtmnyonuxc.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgcmbufaw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgasxnet.html

[U59] PHP：自定义排序
来源：http://dali.meibo888.top/Article/details/gtnzjlrsxz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.shangyingyoupin.top/Article/details/gtzxxluatr.html

[U60] PHP：JSON 编解码
来源：http://dali.yuanzhike.top/Article/details/gteexzkxlj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hywenlv.cn/Article/details/gtsmokjdgi.html

[U61] PHP：正则
来源：http://dali.mhx1999.top/Article/details/gtmgsvbcej.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jinqigufen.top/Article/details/gtswdhpiog.html

[U62] PHP：日期对象
来源：http://dali.svipenyu.cn/Article/details/gtwzxfcekv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.svipenyu.cn/Article/details/gtrrtpvocg.html

[U63] PHP：文件读写
来源：http://dali.sweek.top/Article/details/gtzdoziwbb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258888.top/Article/details/gtrebommof.html

[U64] PHP：目录遍历
来源：http://dali.gzhubu.top/Article/details/gtxnxwatyz.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhongyouzk.top/Article/details/gtutprmhnk.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtlbgyayus.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtiqtjtvkq.html

[U66] PHP：设置 Cookie
来源：http://dali.zhixingplan.top/Article/details/gtmimvcnnm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhoulong.xyz/Article/details/gtucxienpu.html

[U67] PHP：处理文件上传
来源：http://dali.c1oappe.top/Article/details/gtvrrdfhuk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gthuxivulc.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrtkpjrw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtgfmsmsgp.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gtkhrvgvub.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.pengpengdd.cyou/Article/details/gtbpamoahb.html

[U70] PHP：PDO 事务
来源：http://dali.sweek.top/Article/details/gtthhsodsg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.andypj.xyz/Article/details/gtegtpvuhp.html

[U71] PHP：抛出异常
来源：http://dali.yueranfly.top/Article/details/gttezaluxe.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtxsnubysg.html

[U72] PHP：写错误日志
来源：http://dali.yangfankeji.com/Article/details/gtdxogzkiw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ybcxt.top/Article/details/gtuldfqybu.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhixingplan.top/Article/details/gtugrawrxl.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gtujfrtikq.html

[U74] PHP：读取环境变量
来源：http://dali.andypj.xyz/Article/details/gtwvuojtrs.html

getenv("APP_ENV") ?: "production"
来源：http://dali.nanxuanxn.top/Article/details/gtifxmqngv.html

[U75] PHP：依赖注入
来源：http://dali.yueranfly.top/Article/details/gtafdwplgs.html

composer require psr/container
来源：http://dali.zhixingplan.top/Article/details/gtnzpkrmpi.html

[U76] PHP：简单路由
来源：http://dali.nwbrower.top/Article/details/gtyofftykb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.chenjidiqi.icu/Article/details/gtebtzhyip.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gtedtcqesa.html

composer require twig/twig
来源：http://dali.dashuyun.cn/Article/details/gtqxcevela.html

[U78] PHP：单元测试
来源：http://dali.quarkkingdee.top/Article/details/gtzsqnekdc.html

composer require --dev phpunit/phpunit
来源：http://dali.aizwys.cn/Article/details/gtlvlgxtqd.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gtzmrcdner.html

composer require --dev phpstan/phpstan
来源：http://dali.yuxming.cn/Article/details/gttqvmtcye.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gtdfnzpvoe.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtxiyexjyi.html

[U81] JS：初始化项目
来源：http://dali.ehwqpu.com/Article/details/gtlvbnyuym.html

npm init -y;  npm i express
来源：http://dali.jiagoushi.top/Article/details/gtpycotwme.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtbbouaqdr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gtnqzubbbt.html

[U83] JS：ES Module 导入导出
来源：http://dali.gogol.net.cn/Article/details/gtwgtohdib.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.shanyushiyangtech.top/Article/details/gttqrcztrd.html

[U84] JS：CommonJS 写法
来源：http://dali.cucudq.cn/Article/details/gtmgpmzkge.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yonumen.top/Article/details/gtbhafopge.html

[U85] JS：可选链
来源：http://dali.gaohongyu789.top/Article/details/gtonycxwhx.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gtujjjfaxl.html

[U86] JS：空值合并
来源：http://dali.jiagoushi.top/Article/details/gttvpcblnc.html

a ?? b
来源：http://dali.316326.xyz/Article/details/gtskczpwbv.html

[U87] JS：解构默认值
来源：http://dali.zhiwuduotai.top/Article/details/gtikpnyzbb.html

const { a = 1, b = 2 } = obj;
来源：http://dali.sxryk.cn/Article/details/gteandefal.html

[U88] JS：对象展开合并
来源：http://dali.zhixingplan.top/Article/details/gtcbkxogxs.html

{ ...a, ...b }
来源：http://dali.ybcxt.top/Article/details/gtmormkhrw.html


<!-- 参考信息 -->