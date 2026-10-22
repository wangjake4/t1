代发 wailian999

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xuanzx.com/Article/details/gt2gzhyetls.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gt2sogiuhbg.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gt2mnxogejl.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gt2fnxfjfdc.html

namespace ns { int f() { return 1; } }
来源：http://dali.daxiang520.top/Article/details/gt2uqvzcegc.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2znjtytte.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gt2qdqawzcn.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gt2avtpdwca.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.birdmap.top/Article/details/gt2shjqaomm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2txoupwnq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2ltbxdxwu.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2kxxrxdvi.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2qxczuahu.html

println("Hello")
来源：http://dali.dashuyun.cn/Article/details/gt2fvzkzyaa.html

[T02] Kotlin：变量
来源：http://dali.daria6918.cn/Article/details/gt2jiuaorpe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2peegswfd.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gt2oomlhvem.html

"值: $b"
来源：http://dali.xuanzx.com/Article/details/gt2nkudczem.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nxhadxpo.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gt2rdttcpsa.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gt2musnmidc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yonumen.top/Article/details/gt2vjmspfum.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2npmmebkw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gt2qjkdsuqz.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gt2tqamxnzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gt2iorozijp.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gt2uckggcoc.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gt2bvtyzfzx.html

[T09] Kotlin：扩展函数
来源：http://dali.daria6918.cn/Article/details/gt2fcshlglr.html

fun String.exclaim() = this + "!"
来源：http://dali.jyoumei.cn/Article/details/gt2dsmzbkzw.html

[T10] Kotlin：默认参数
来源：http://dali.yueranfly.top/Article/details/gt2lncxkcph.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gt2hrlpnqrl.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gt2iixarvlq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nanxinkj.top/Article/details/gt2uofjkzly.html

[T12] Kotlin：解构声明
来源：http://dali.hywenlv.cn/Article/details/gt2yviqtkwm.html

val (a, b) = Pair(1, 2)
来源：http://dali.pycfn.com/Article/details/gt2uysdfyjz.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gt2gsblglph.html

val m = mapOf("a" to 1)
来源：http://dali.sysykeji.top/Article/details/gt2hvzkpvca.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2wfsdxaab.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmdzlphb.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gt2qshskojc.html

interface Shape { fun area(): Double }
来源：http://dali.ehwqpu.com/Article/details/gt2msdwwwzc.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gt2xjmmjexr.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gt2qdhdycbu.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gt2llznrhpz.html

var a = 1;  let b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2okouwonp.html

[T18] Swift：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2yynbdhal.html

"值: \(b)"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jnamtfgm.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2pfjmtrxj.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gt2nlcchvff.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gt2hexnxlqp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.c1oappe.top/Article/details/gt2wywfoysd.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gt2boqfqzql.html

for x in a { print(x) }
来源：http://dali.gaohongyu789.top/Article/details/gt2awoaahku.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gt2ppyrpxrt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.birdmap.top/Article/details/gt2tocjosdt.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gt2yhydbcrg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2sddzmozp.html

[T24] Swift：闭包
来源：http://dali.redwolf501.top/Article/details/gt2cotabfcp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkpgvvce.html

[T25] Swift：结构体
来源：http://dali.nanxinkj.top/Article/details/gt2bbfebfag.html

struct P { var x: Int }
来源：http://dali.yvedp.cn/Article/details/gt2fmuerntz.html

[T26] Swift：类与重写
来源：http://dali.fzhhl.top/Article/details/gt2fbcuyxmn.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gt2wkobhzba.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gt2riuscimb.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ypaavdci.html

[T28] Swift：枚举
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhqkzjtk.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gt2rtoiahyl.html

[T29] Swift：guard 提前返回
来源：http://dali.daxiang520.top/Article/details/gt2mytmiqkb.html

guard let x = opt else { return }
来源：http://dali.jianghu66.top/Article/details/gt2omtbfzxy.html

[T30] Swift：协议
来源：http://dali.jqgufenzy.top/Article/details/gt2tlnryvib.html

protocol Shape { func area() -> Double }
来源：http://dali.hfpthk.cn/Article/details/gt2fkxrfioj.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gt2wdvyrbeg.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gt2lhqqzlzi.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gt2omwvslqj.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2hgkdgyxv.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gt2scmaughu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gt2kmxcvcfs.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gt2lfdnafbj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gogol.net.cn/Article/details/gt2yeespvkq.html

[T35] Lua：字典表
来源：http://dali.ehwqpu.com/Article/details/gt2hkcdunjy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gt2vytuhrsz.html

[T36] Lua：函数
来源：http://dali.zycfv.cn/Article/details/gt2qmlqntdr.html

function add(a, b) return a + b end
来源：http://dali.shangyingyoupin.top/Article/details/gt2sgiyvkqs.html

[T37] Lua：字符串拼接
来源：http://dali.hywenlv.cn/Article/details/gt2istbdwzb.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gt2jymwxbol.html

[T38] Lua：条件
来源：http://dali.jiagoushi.top/Article/details/gt2ibiwspai.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gt2wgfokvak.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2aaomgbbn.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujnrgoie.html

[T40] Lua：元表
来源：http://dali.yuxming.cn/Article/details/gt2lrdqetbr.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2qvdgufcu.html

[T41] Perl：Hello World
来源：http://dali.havefunace.top/Article/details/gt2jeewscji.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gt2srcentyf.html

[T42] Perl：变量类型
来源：http://dali.nanxinkj.top/Article/details/gt2zcitldht.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2yzyltuad.html

[T43] Perl：字符串插值
来源：http://dali.fzhhl.top/Article/details/gt2jprpujpo.html

"值: $a"
来源：http://dali.jyoumei.cn/Article/details/gt2fktuiydy.html

[T44] Perl：条件
来源：http://dali.wangshuangyany.cn/Article/details/gt2dehtoeoy.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2kitdfoot.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gt2nztktgrp.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2uugdrrhj.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2rvamabrb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2unhpapqb.html

[T47] Perl：正则捕获
来源：http://dali.pycfn.com/Article/details/gt2oqugfntq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuanzhike.top/Article/details/gt2hxrmzmtn.html

[T48] Perl：正则替换
来源：http://dali.tanke756.top/Article/details/gt2xatpohdk.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gt2fosgxwob.html

[T49] Perl：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2civpzuxo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2crdnhkng.html

[T50] Perl：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gt2qfkkrady.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gt2gznhaqyg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gt2yadiqtum.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wcbgomcv.html

println("Hello")
来源：http://dali.ivvv.top/Article/details/gt2iifgaqjq.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2guwrmyhb.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gt2wjxxngni.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gt2kgaytzta.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gt2cuqavkqv.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gt2dkypxmky.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ttfhrllm.html

[T55] Scala：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gt2nvyxqzxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxinkj.top/Article/details/gt2kaumfpaq.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gt2jqyymgjo.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2arhmtnzb.html

[T57] Scala：模式匹配
来源：http://dali.hywenlv.cn/Article/details/gt2jptzgjqz.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gt2kepcjzth.html

[T58] Scala：函数定义
来源：http://dali.snrcjt.cn/Article/details/gt2lzaulnlq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gt2jmnjxmza.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2kbhepogi.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2scxwjlrl.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gt2xclufkoz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ndglqbkj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2bspmmuqg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gt2xgibuohj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2pxxmzwxa.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2aljgobab.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gt2nnfsmrgp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gt2hllsywkg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ippniugv.html

[U03] Py：加载 .env 配置
来源：http://dali.bjfxy.top/Article/details/gt2upkdbvlc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gt2gxkxgxuf.html

[U04] Py：变量调试打印
来源：http://dali.xziqi.cn/Article/details/gt2tlqipeod.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gt2ojhicjjy.html

[U05] Py：列表去重且保序
来源：http://dali.sysykeji.top/Article/details/gt2paajnnde.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gt2zzpedzkj.html

[U06] Py：合并两个字典
来源：http://dali.nanxuanxn.top/Article/details/gt2dfemsjnk.html

{**a, **b}
来源：http://dali.chenlongwang.top/Article/details/gt2dlmusesh.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gt2mepfnjgr.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gt2kdjvlmuj.html

[U08] Py：展平二维列表
来源：http://dali.nwbrower.top/Article/details/gt2bxdysydu.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2dljlvsnh.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxinkj.top/Article/details/gt2umbiwboe.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2msahkskq.html

[U10] Py：按值排序字典
来源：http://dali.yuanzhike.top/Article/details/gt2coupsjpt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yongpay.top/Article/details/gt2zyedacgl.html

[U11] Py：生成器表达式
来源：http://dali.sysykeji.top/Article/details/gt2nktvyoha.html

(x * 2 for x in arr)
来源：http://dali.cqqwz.cn/Article/details/gt2kvvsiilx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.meibo888.top/Article/details/gt2mzetrinw.html

Counter(arr).most_common(3)
来源：http://dali.cashguo.top/Article/details/gt2xlduplqe.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gt2rqkejjsr.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gt2iocnwhws.html

[U14] Py：分组收集到列表
来源：http://dali.aizwys.cn/Article/details/gt2csdogtdj.html

defaultdict(list)
来源：http://dali.cucudq.cn/Article/details/gt2qpzntvbg.html

[U15] Py：高精度计时
来源：http://dali.jinqigfzy.top/Article/details/gt2yiznkgvl.html

t = time.perf_counter()
来源：http://dali.pengpengdd.cyou/Article/details/gt2bedcxauh.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gt2lpuanfnv.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xylfe.cn/Article/details/gt2swjpnlgp.html

[U17] Py：初始化日志
来源：http://dali.sxryk.cn/Article/details/gt2jimovhwh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gt2vzqfiayv.html

[U18] Py：预编译正则
来源：http://dali.guannengcc.top/Article/details/gt2hyrvvwnn.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gt2klvlsopm.html

[U19] Py：正则替换带回调
来源：http://dali.jlsjyb.cn/Article/details/gt2sbocieyo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gt2khayiked.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gt2dqjniwlb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gt2gjsamost.html

[U21] Py：自定义上下文管理器
来源：http://dali.feifeiyinyue.top/Article/details/gt2rlxqhjvb.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gt2mhthhrqi.html

[U22] Py：矩阵转置
来源：http://dali.hnxiangtu.top/Article/details/gt2wtvjhyeg.html

list(zip(*m))
来源：http://dali.yanxiufei.cn/Article/details/gt2dtntkegc.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gt2paiqmjmr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.chenzaomai.com/Article/details/gt2dxdqdqhp.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gt2pqffrhcl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jtgpkmpy.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ubuhpsta.html

csv.DictReader(f)
来源：http://dali.9152youxi.cn/Article/details/gt2ggmtnhtz.html

[U26] Py：并发下载
来源：http://dali.hnxiangtu.top/Article/details/gt2alyqqnab.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gt2tbkotbpk.html

[U27] Py：异步 HTTP
来源：http://dali.jlsjyb.cn/Article/details/gt2kutyhskq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ckmuvtra.html

[U28] Py：类型别名
来源：http://dali.gzhubu.top/Article/details/gt2madvujqk.html

UserId = int
来源：http://dali.yuxming.cn/Article/details/gt2nrjkeekl.html

[U29] Py：属性校验
来源：http://dali.316326.xyz/Article/details/gt2irlulmdy.html

@property 与 @x.setter 配合
来源：http://dali.yueranfly.top/Article/details/gt2khalioiu.html

[U30] Py：数据类
来源：http://dali.aizwys.cn/Article/details/gt2eshewoov.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gt2qnnjprgr.html

[U31] Py：单测
来源：http://dali.jianghu66.top/Article/details/gt2vbrfpccj.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gt2cirlhvve.html

[U32] Py：代码格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvicsttl.html

ruff format . && ruff check --fix .
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpjvfjob.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gt2myorpbgr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gt2tedehfxj.html

[U34] Py：判断编码
来源：http://dali.9152youxi.cn/Article/details/gt2ismbaasb.html

chardet.detect(raw)
来源：http://dali.sxryk.cn/Article/details/gt2rgehwodm.html

[U35] Py：发送邮件
来源：http://dali.yvedp.cn/Article/details/gt2decbqhve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vobksfbb.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gt2aufxdyzk.html

schedule.every(10).minutes.do(job)
来源：http://dali.shuidangran.top/Article/details/gt2xtnfbouk.html

[U37] Py：读写 Excel
来源：http://dali.daxiang520.top/Article/details/gt2uplgknar.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.pengpengdd.cyou/Article/details/gt2hagrurkh.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gt2mxbuumwc.html

Path(__file__).resolve().parent
来源：http://dali.ydzc1.top/Article/details/gt2zabostka.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yidkyppn.html

sys.stdout.isatty()
来源：http://dali.chenlongwang.top/Article/details/gt2eahkmlal.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gt2eewkiebk.html

print("err", file=sys.stderr)
来源：http://dali.0kj1m.cn/Article/details/gt2zexkswxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gt2kjrwtjnb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cheryme.top/Article/details/gt2npvpkjum.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hammf.cn/Article/details/gt2hyvdlawv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhoulong.xyz/Article/details/gt2njdxlheg.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gt2fukdoiwu.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gt2nklkpxmw.html

[U44] PHP：开启严格类型
来源：http://dali.aizwys.cn/Article/details/gt2entglltw.html

declare(strict_types=1);
来源：http://dali.yongpay.top/Article/details/gt2srdpmcrn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gt2xgezachl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gt2qfhqwinh.html

[U46] PHP：可空类型
来源：http://dali.shangyingyoupin.top/Article/details/gt2phavptis.html

?string $name = null
来源：http://dali.kuanghao11.cn/Article/details/gt2wwontdfo.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gt2spfjqicl.html

int|string $id
来源：http://dali.aibaodan.cn/Article/details/gt2zjkmqlkh.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gt2cwljjozb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jqgfzy.top/Article/details/gt2jjluqwgr.html

[U49] PHP：只读属性
来源：http://dali.yangfankeji.com/Article/details/gt2ezuunaxy.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gt2ctijkbxp.html

[U50] PHP：构造器属性提升
来源：http://dali.nwbrower.top/Article/details/gt2rtzczfwn.html

public function __construct(private int $id) {}
来源：http://dali.meibo888.top/Article/details/gt2oljsoyse.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gt2xbytmoot.html

[$a, $b] = $arr;
来源：http://dali.ybcxt.top/Article/details/gt2ymfxvfmx.html

[U52] PHP：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vxmxxbwr.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tuqglcpp.html

[U53] PHP：空合并运算符
来源：http://dali.zhiwuduotai.top/Article/details/gt2unapbeeq.html

$v = $a ?? $b ?? "default";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fizkbzhv.html

[U54] PHP：空安全调用
来源：http://dali.andypj.xyz/Article/details/gt2nlcjwzgb.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gt2ljfpcqbl.html

[U55] PHP：match 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2cmejvvzs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.316326.xyz/Article/details/gt2ovrlikec.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gt2clrdjbuc.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2simdeukz.html

[U57] PHP：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2ovedpjbx.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gt2dfuwxeth.html

[U58] PHP：数组三件套
来源：http://dali.xinyue.icu/Article/details/gt2rknsypne.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.316326.xyz/Article/details/gt2pcdeuwos.html

[U59] PHP：自定义排序
来源：http://dali.xziqi.cn/Article/details/gt2iizzekpe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uxrvbcmz.html

[U60] PHP：JSON 编解码
来源：http://dali.gogol.net.cn/Article/details/gt2llvoojrz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frkoaeep.html

[U61] PHP：正则
来源：http://dali.haohaochexian.top/Article/details/gt2szhrxndt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gt2shpjpgja.html

[U62] PHP：日期对象
来源：http://dali.sxryk.cn/Article/details/gt2qsbotzhs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.c1oappe.top/Article/details/gt2qiovzxll.html

[U63] PHP：文件读写
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sjxuqleu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gt2ozoonoul.html

[U64] PHP：目录遍历
来源：http://dali.tianlin.xyz/Article/details/gt2ztucvezk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gt2xtigizbk.html

[U65] PHP：会话
来源：http://dali.zhiwuduotai.top/Article/details/gt2soetxwsi.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gt2icfylzsk.html

[U66] PHP：设置 Cookie
来源：http://dali.chenjidiqi.icu/Article/details/gt2aswrkbce.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.nanxinkj.top/Article/details/gt2mhqkblnq.html

[U67] PHP：处理文件上传
来源：http://dali.zhengqikj.top/Article/details/gt2poshndpj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.redwolf501.top/Article/details/gt2svscwygw.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gt2lojnendp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.9152youxi.cn/Article/details/gt2jesqwaom.html

[U69] PHP：PDO 预处理
来源：http://dali.bjfxy.top/Article/details/gt2upxlhsac.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gzhubu.top/Article/details/gt2aqnfsugo.html

[U70] PHP：PDO 事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2xdxpawub.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gt2xmxcesng.html

[U71] PHP：抛出异常
来源：http://dali.zhiwuduotai.top/Article/details/gt2ydtuksvb.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2apzdyjut.html

[U72] PHP：写错误日志
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvuvykjn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.aibaodan.cn/Article/details/gt2izrpqiak.html

[U73] PHP：读取 ini 配置
来源：http://dali.ybcxt.top/Article/details/gt2fvpcklkx.html

parse_ini_file("config.ini", true)
来源：http://dali.jinqigufen.top/Article/details/gt2pkuqxzvz.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258888.top/Article/details/gt2zsrehixr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.iojbl.cn/Article/details/gt2mtsbcxhu.html

[U75] PHP：依赖注入
来源：http://dali.yj20258888.top/Article/details/gt2eomxbujd.html

composer require psr/container
来源：http://dali.cqqwz.cn/Article/details/gt2yhpgrsco.html

[U76] PHP：简单路由
来源：http://dali.xuanzx.com/Article/details/gt2orqkossq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgfzy.top/Article/details/gt2xhsbozac.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gt2zcmgesfq.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gt2bzkhglff.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jhmkaxqj.html

composer require --dev phpunit/phpunit
来源：http://dali.ydzc1.top/Article/details/gt2bikbumjz.html

[U79] PHP：静态分析
来源：http://dali.chenjidiqi.icu/Article/details/gt2izgnxnim.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gt2ggtdhpes.html

[U80] PHP：代码规范修复
来源：http://dali.meibo888.top/Article/details/gt2fppdmdzl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.kuanghao11.cn/Article/details/gt2zxedefvt.html

[U81] JS：初始化项目
来源：http://dali.nwbrower.top/Article/details/gt2jmwhcrzq.html

npm init -y;  npm i express
来源：http://dali.gotoacloud.top/Article/details/gt2ddyhcfvk.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gt2uabqrmsj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gt2ubobxtwq.html


<!-- 参考信息 -->