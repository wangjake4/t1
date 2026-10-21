代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ydzc1.top/Article/details/gtlldtvxyv.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtthhzadip.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.andypj.xyz/Article/details/gthyshcqds.html

[S56] C++：optional
来源：http://dali.hfpthk.cn/Article/details/gtezkllolu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shuidangran.top/Article/details/gtwrmqemko.html

[S57] C++：编译期常量
来源：http://dali.tian-w.cn/Article/details/gtbwhbdnmg.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtshnztumi.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtzcnaiggc.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtvdwqzyqz.html

[S59] C++：静态断言
来源：http://dali.9152youxi.cn/Article/details/gthrcpnaks.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtbolptkpo.html

[S60] C++：遍历并删除元素
来源：http://dali.bjfxy.top/Article/details/gtftmoqfiv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtgtylknbe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtutvkstos.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtutlhqfrp.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtcfzflwlc.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gtrienwyxr.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtomlowzgv.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtcujuasli.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtypegmlum.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtqpqjjsme.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtoetfkurf.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtrmjyjeun.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtmexcowiz.html

[T05] Kotlin：when 表达式
来源：http://dali.316326.xyz/Article/details/gtuhorpkmy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtszxyrpgf.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtuhsyotya.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtsuzwunik.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtjrjrqewa.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwgogqsg.html

[T08] Kotlin：数据类
来源：http://dali.aizwys.cn/Article/details/gthdrnljud.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtufoawjps.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gtbdqhngxw.html

fun String.exclaim() = this + "!"
来源：http://dali.cashguo.top/Article/details/gtkfathjng.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtbwbnvnuz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258.top/Article/details/gtzwfodoqp.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gtnjcbuspx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ybcxt.top/Article/details/gtzwyszwui.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtfabfwqtq.html

val (a, b) = Pair(1, 2)
来源：http://dali.hfpthk.cn/Article/details/gtoylflpdw.html

[T13] Kotlin：只读 Map
来源：http://dali.quarkkingdee.top/Article/details/gtijwqjngd.html

val m = mapOf("a" to 1)
来源：http://dali.9152youxi.cn/Article/details/gtpgskrprg.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gtwujswwbu.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtwrfxwzwg.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gtbkszldek.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtiibujdge.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gtoepxljxg.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtlxhdyhea.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtlxvwkutp.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtbietqcih.html

[T18] Swift：字符串插值
来源：http://dali.smart0.xyz/Article/details/gtvvnbqxsv.html

"值: \(b)"
来源：http://dali.gotoacloud.top/Article/details/gtspozvaza.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtupivemko.html

if let n = opt { print(n) }
来源：http://dali.shzxlz.cn/Article/details/gtueockbxd.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtlvivnbcj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgufenzy.top/Article/details/gtxrnttked.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtxobmgrxp.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gthwrqryxp.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvznbrsci.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtddghundr.html

[T23] Swift：函数
来源：http://dali.c1oappe.top/Article/details/gtzhepnoht.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtbgaiangz.html

[T24] Swift：闭包
来源：http://dali.yj20258.top/Article/details/gtmkqqkvnc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.bjfxy.top/Article/details/gtcjyiklqt.html

[T25] Swift：结构体
来源：http://dali.zhengqikj.top/Article/details/gtjtxroogi.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtgsnatjno.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtgzhjowsa.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtscwwfddt.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtozsphvuc.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gtmzlwghae.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gtzsiikwns.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtieeesfjv.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtksubopvu.html

guard let x = opt else { return }
来源：http://dali.yongpay.top/Article/details/gtwaebrrvl.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtuxunhwla.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtqbrzxlgb.html

[T31] Lua：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtwmthepze.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gtcdjncogr.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtorugvjun.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtewkcqicn.html

[T33] Lua：表（数组）
来源：http://dali.zycfv.cn/Article/details/gtftjuqxxo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ywan-chungtsiang.top/Article/details/gtioqtnhmr.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtszzvlfll.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtweqeitex.html

[T35] Lua：字典表
来源：http://dali.zycfv.cn/Article/details/gttqzfdwqj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtatabzdtj.html

[T36] Lua：函数
来源：http://dali.hnxiangtu.top/Article/details/gtwxicagqd.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqbvmmkv.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtdivyxvdq.html

"a" .. "b"
来源：http://dali.ehwqpu.com/Article/details/gtllbbohpz.html

[T38] Lua：条件
来源：http://dali.kuanghao11.cn/Article/details/gtauqzlvsn.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtxhwyehck.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtfvtupafi.html

string.find(s, "%d+")
来源：http://dali.yongpay.top/Article/details/gtsxvmqevt.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtcioxrxml.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtsjnzohkj.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtslzefxtz.html

print "Hello\n";
来源：http://dali.hnqzz.top/Article/details/gtjfgwyuey.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtfrwxhcqf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.pycfn.com/Article/details/gtfpfthzhi.html

[T43] Perl：字符串插值
来源：http://dali.quarkkingdee.top/Article/details/gtlemhhbaj.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gthdvvnhwf.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gtuxjgutjf.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gtpfaobayh.html

[T45] Perl：数组遍历
来源：http://dali.jyoumei.cn/Article/details/gtmtpgsrjr.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtopouyuii.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtawyprliy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtyrpaapvk.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtztjvawgc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gtyvvvurmn.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtqllemkpm.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtmryvvmom.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtztopcygr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gteocqpynd.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtqqthayny.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gtqxrzfzuz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzsxbsnop.html

[T51] Scala：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpjmeasuw.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtedpaxfbh.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gtvqjvpenz.html

val a = 1;  var b = 2
来源：http://dali.dashuyun.cn/Article/details/gtuhtuxnnl.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyxwyxdkj.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtuwlurwdu.html

[T54] Scala：集合映射
来源：http://dali.guannengcc.top/Article/details/gtjpialiid.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenjidiqi.icu/Article/details/gtltanbjwn.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gtjfgbvygc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gthuuhjgel.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gtbjvaqwxa.html

case class User(name: String, age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtftluxykc.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gtblicnbzp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtunpjzuas.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtqayplulg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtytqsxsij.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtijlnymyy.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gthdowilqy.html

[T60] Scala：折叠
来源：http://dali.snrcjt.cn/Article/details/gtgcwakzyo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtovdveibd.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtizxtxcsq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gtuswbuijn.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtdagnwvwh.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtegvdsdst.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigufen.top/Article/details/gttkxamgcz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gttkmubamu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xinyue.icu/Article/details/gtrgtjbbal.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtqfniukkk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtiunexana.html

[U04] Py：变量调试打印
来源：http://dali.iojbl.cn/Article/details/gtbeewdasx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtrucjocuo.html

[U05] Py：列表去重且保序
来源：http://dali.hywenlv.cn/Article/details/gtfqixhbnx.html

list(dict.fromkeys(arr))
来源：http://dali.yanxiufei.cn/Article/details/gtrirkftdv.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtcjgzjaty.html

{**a, **b}
来源：http://dali.hnqzz.top/Article/details/gtmwkoazss.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtdgjrxkzp.html

{v: k for k, v in d.items()}
来源：http://dali.pengpengdd.cyou/Article/details/gtplchxfrn.html

[U08] Py：展平二维列表
来源：http://dali.smart0.xyz/Article/details/gtkgonfuxg.html

[y for x in nested for y in x]
来源：http://dali.yuanzhike.top/Article/details/gtgtyjxsvh.html

[U09] Py：字典取最大值的键
来源：http://dali.xziqi.cn/Article/details/gtdrlsvlgp.html

max(d, key=d.get)
来源：http://dali.snrcjt.cn/Article/details/gtsrflmdxk.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtyxfordzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.tanke756.top/Article/details/gtiylejtkt.html

[U11] Py：生成器表达式
来源：http://dali.smart0.xyz/Article/details/gtnyztornh.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gtzhhfqpub.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxinkj.top/Article/details/gtgjntftsb.html

Counter(arr).most_common(3)
来源：http://dali.gotoacloud.top/Article/details/gtclixyfkd.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtyfyqjsys.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gthqchgcwr.html

[U14] Py：分组收集到列表
来源：http://dali.snrcjt.cn/Article/details/gtblhjypld.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gtwjlhvqfh.html

[U15] Py：高精度计时
来源：http://dali.ppjwa.cn/Article/details/gtnedhdjdh.html

t = time.perf_counter()
来源：http://dali.zhoulong.xyz/Article/details/gtdycjihsh.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtapsbayju.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtisyataia.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtnvfcjvlm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jianghu66.top/Article/details/gttrduwyck.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzfnlzjc.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtzhctzlra.html

[U19] Py：正则替换带回调
来源：http://dali.pycfn.com/Article/details/gtzmcuflja.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtyoornluw.html

[U20] Py：缓存函数结果
来源：http://dali.ppjwa.cn/Article/details/gtxadaatnq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtxdgyjoyb.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gtdrboqwfm.html

@contextlib.contextmanager
来源：http://dali.jinqigfzy.top/Article/details/gtonuirmsu.html

[U22] Py：矩阵转置
来源：http://dali.smart0.xyz/Article/details/gtosenxisf.html

list(zip(*m))
来源：http://dali.yuxming.cn/Article/details/gteugckaxr.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtqalkdxtz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xinyue.icu/Article/details/gtrmjcvxoe.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtsawoillw.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmerlyhb.html

[U25] Py：CSV 按字典读
来源：http://dali.pengpengdd.cyou/Article/details/gtcqtidjya.html

csv.DictReader(f)
来源：http://dali.dashuyun.cn/Article/details/gtfqtbtlcp.html

[U26] Py：并发下载
来源：http://dali.0kj1m.cn/Article/details/gtgtlrygai.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gtfhtyjhit.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gthrcqwotp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.nwbrower.top/Article/details/gtbkblzssp.html

[U28] Py：类型别名
来源：http://dali.jiagoushi.top/Article/details/gtrjniback.html

UserId = int
来源：http://dali.sufxvd.cn/Article/details/gtgxstyjdm.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtbubbfozh.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtkkwrrzxj.html

[U30] Py：数据类
来源：http://dali.fengsongda.top/Article/details/gtqymfxehz.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtdtvbcajm.html

[U31] Py：单测
来源：http://dali.cheryme.top/Article/details/gtvgvqzxjn.html

python -m pytest -q
来源：http://dali.guannengcc.top/Article/details/gtlxfikzjo.html

[U32] Py：代码格式化
来源：http://dali.hywenlv.cn/Article/details/gtjqthwhuw.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtxrcboqgu.html

[U33] Py：打包发布
来源：http://dali.tanke756.top/Article/details/gtqtnebeuj.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gticdtoqrk.html

[U34] Py：判断编码
来源：http://dali.cheryme.top/Article/details/gtgonowwvo.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtetkmexoi.html

[U35] Py：发送邮件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlzmdcmma.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jiagoushi.top/Article/details/gtjoakahow.html

[U36] Py：定时任务
来源：http://dali.shuidangran.top/Article/details/gtcdgkncyc.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gtekdogwdt.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtwccatttk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.vqdsnc.cn/Article/details/gtmqmrdhdm.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gtouqzdvty.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtuagqnwmq.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvlwbowv.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gtghmfjtzp.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtlcuwtbxg.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gtwvhstfuu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtkgtxzyjr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.gogol.net.cn/Article/details/gtgkospini.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.0kj1m.cn/Article/details/gteqctchpu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.316326.xyz/Article/details/gtwjlwnwbt.html

[U43] PHP：声明命名空间
来源：http://dali.ehwqpu.com/Article/details/gthlitnsal.html

namespace App\Http;
来源：http://dali.zhengqikj.top/Article/details/gtscxombca.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gtnypfpuyq.html

declare(strict_types=1);
来源：http://dali.cqqwz.cn/Article/details/gtfwdyyzjc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtkguimcgg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrddxgepr.html

[U46] PHP：可空类型
来源：http://dali.andypj.xyz/Article/details/gtnjjmeplv.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gtuvoqadgc.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtsvqkcnie.html

int|string $id
来源：http://dali.redwolf501.top/Article/details/gthpscankn.html

[U48] PHP：纯枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmgxujqk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jinqigfzy.top/Article/details/gtokhfswcb.html

[U49] PHP：只读属性
来源：http://dali.zhengqikj.top/Article/details/gtpedqlsqd.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtufaywjon.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gtcvuycshm.html

public function __construct(private int $id) {}
来源：http://dali.nwbrower.top/Article/details/gtwyssvmkf.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gtwqbofyst.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvlgbzvs.html

[U52] PHP：箭头函数
来源：http://dali.shzxlz.cn/Article/details/gtgieuvlha.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gtqfyargwz.html

[U53] PHP：空合并运算符
来源：http://dali.c1oappe.top/Article/details/gtmszembfi.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gtewcaowja.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgcanlne.html

$obj?->method()
来源：http://dali.jyoumei.cn/Article/details/gtluqthbxw.html

[U55] PHP：match 表达式
来源：http://dali.aizwys.cn/Article/details/gtzdzlzkjk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gteqesbgev.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtfsbwpwfx.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtulobraql.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtqynflfxp.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtjxtghers.html

[U58] PHP：数组三件套
来源：http://dali.jinqigufen.top/Article/details/gtygeeqajb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuanzx.com/Article/details/gtysasvzre.html

[U59] PHP：自定义排序
来源：http://dali.havefunace.top/Article/details/gthisijtle.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gtsdengbub.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnieyazxw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtfmjzjjye.html

[U61] PHP：正则
来源：http://dali.gotoacloud.top/Article/details/gtfgpgblkw.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zdqjudy.top/Article/details/gtackwnjpo.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtuowcgahu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtqfhjnxpl.html

[U63] PHP：文件读写
来源：http://dali.jinghuilouyu.cn/Article/details/gtagvwaxor.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gtlwafemdf.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gtmbprdcca.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tian-w.cn/Article/details/gtxdxteamm.html

[U65] PHP：会话
来源：http://dali.chenjidiqi.icu/Article/details/gtbjqvxaqn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gthujuzxgf.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gtcqdxgbal.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxuanxn.top/Article/details/gtjskvoyfu.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gtbhrnneob.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtqlvajkwe.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gtmoqyhuxl.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tanke756.top/Article/details/gtpvpgambm.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtzofhyexm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.snrcjt.cn/Article/details/gtmgonehpl.html

[U70] PHP：PDO 事务
来源：http://dali.9152youxi.cn/Article/details/gtbyktxruf.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.meibo888.top/Article/details/gtyvzwtbny.html

[U71] PHP：抛出异常
来源：http://dali.zycfv.cn/Article/details/gtrxuwtbbb.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gtnfrehirq.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gtcptnanfz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.havefunace.top/Article/details/gtqfprxizm.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtqtythryv.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtlbcosfer.html

[U74] PHP：读取环境变量
来源：http://dali.cqqwz.cn/Article/details/gtbzawawcw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yj202588.top/Article/details/gtvwxwbayu.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gtepgtchia.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtaemfaxbg.html

[U76] PHP：简单路由
来源：http://dali.sysykeji.top/Article/details/gtabjhfvry.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gtmvxcqhhf.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gtsmotygvw.html

composer require twig/twig
来源：http://dali.hnxiangtu.top/Article/details/gtxiyznrwe.html

[U78] PHP：单元测试
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzpcpfnk.html

composer require --dev phpunit/phpunit
来源：http://dali.ppjwa.cn/Article/details/gtadoomjus.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gtrluhlemz.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gtkyeddxez.html

[U80] PHP：代码规范修复
来源：http://dali.0kj1m.cn/Article/details/gtatqxjfns.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.birdmap.top/Article/details/gthjytswva.html


<!-- 参考信息 -->