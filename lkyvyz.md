代发 wailian999

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtjqjurumh.html

[S55] C++：结构化绑定
来源：http://dali.hysaishi.cn/Article/details/gtqucyqmmp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtxccexaez.html

[S56] C++：optional
来源：http://dali.tian-w.cn/Article/details/gtscbdwcbc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gtdplxgbpt.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gttiovmzqu.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gtruzwsrwi.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gttzlczhds.html

namespace ns { int f() { return 1; } }
来源：http://dali.cheryme.top/Article/details/gtzhbsxboi.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gtthcyfpof.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gthqpxhknt.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckphtcnx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtusabsusb.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbicmsgrl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gthpnpihtc.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtrhtngtil.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtgzcbgesa.html

println("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtupkrpocc.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtshqcqofu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zdqjudy.top/Article/details/gtpewzccgu.html

[T03] Kotlin：字符串模板
来源：http://dali.jlsjyb.cn/Article/details/gtblbhkzzc.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gthtoiwbng.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gthkmljjab.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtdaniwzak.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gtgpjmolzv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtxjhmjitw.html

[T06] Kotlin：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtdlkyesae.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gtkangfxsf.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtxxpbsqie.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gtgyolqbos.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtjzeyylfe.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtfdevjfzf.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtpusmpdne.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtlghfuzrv.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gthfirnucs.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtusilcxfj.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtdfeqfwzc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtbqaetydb.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gtcjfloota.html

val (a, b) = Pair(1, 2)
来源：http://dali.cashguo.top/Article/details/gtfgjyxtvv.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtyulzuxnc.html

val m = mapOf("a" to 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtykjtyhxz.html

[T14] Kotlin：循环
来源：http://dali.yanxiufei.cn/Article/details/gtqjghtrlx.html

for (i in 1..10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtfcyajhxr.html

[T15] Kotlin：接口
来源：http://dali.sxryk.cn/Article/details/gtegwvcflz.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtpzcowybz.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtrpfelmcu.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gthvstghuf.html

[T17] Swift：变量与常量
来源：http://dali.redwolf501.top/Article/details/gtlbrksaji.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gtcseziaiy.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtopyjaopu.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsacxukon.html

[T19] Swift：可选绑定
来源：http://dali.cqqwz.cn/Article/details/gtqpqlkbgg.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtehdmqqge.html

[T20] Swift：数组操作
来源：http://dali.yongpay.top/Article/details/gtzucepclp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtwwjdrfbf.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gtphynnitb.html

for x in a { print(x) }
来源：http://dali.sufxvd.cn/Article/details/gtnkytftcv.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtpxhlppiw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtklskhovs.html

[T23] Swift：函数
来源：http://dali.pycfn.com/Article/details/gtkddcrhvf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtuqhnhxmj.html

[T24] Swift：闭包
来源：http://dali.quarkkingdee.top/Article/details/gtzdyrjmvj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.andypj.xyz/Article/details/gtyfzfqjev.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtmmyhpvzs.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtznpnjtns.html

[T26] Swift：类与重写
来源：http://dali.nanxuanxn.top/Article/details/gtfbssjyso.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gtrbzteayp.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gtsmevmmjj.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtqctyapas.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtaysjvtue.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtlfvaiekv.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlenceyhd.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtdhesqajg.html

[T30] Swift：协议
来源：http://dali.jyoumei.cn/Article/details/gtpriqadax.html

protocol Shape { func area() -> Double }
来源：http://dali.wangdashe.top/Article/details/gtqrluqfwf.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtcksmcjji.html

print("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtdpyifdcj.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtpslhwxxm.html

local a = 1
来源：http://dali.jiagoushi.top/Article/details/gticerkhan.html

[T33] Lua：表（数组）
来源：http://dali.xinyue.icu/Article/details/gtcjhzagag.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtzogsznex.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtkbjmiqht.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gttzgkvhuj.html

[T35] Lua：字典表
来源：http://dali.jiagoushi.top/Article/details/gttzioebxu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.meibo888.top/Article/details/gtgltpulix.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtpeszmzwi.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gtuyvvdsfa.html

[T37] Lua：字符串拼接
来源：http://dali.hongshengwenyu.top/Article/details/gtjubugous.html

"a" .. "b"
来源：http://dali.yongpay.top/Article/details/gtvegfkgzb.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gtynmmgkyl.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gttobrcnxh.html

[T39] Lua：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtrlmmcdla.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gttssyqvhd.html

[T40] Lua：元表
来源：http://dali.sysykeji.top/Article/details/gtmeocxndz.html

setmetatable({}, { __index = base })
来源：http://dali.gzhubu.top/Article/details/gtmtvatbho.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtvbjgzboy.html

print "Hello\n";
来源：http://dali.ehwqpu.com/Article/details/gtpsbdntna.html

[T42] Perl：变量类型
来源：http://dali.snrcjt.cn/Article/details/gtezdexbag.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtazrspyey.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gttdizhgzh.html

"值: $a"
来源：http://dali.guannengcc.top/Article/details/gtlqxsmrto.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroobwlwg.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gtcnlzjhfu.html

[T45] Perl：数组遍历
来源：http://dali.yj20258.top/Article/details/gtssbokllk.html

for my $x (@arr) { print $x; }
来源：http://dali.xinyue.icu/Article/details/gtxetcdrkr.html

[T46] Perl：哈希操作
来源：http://dali.yj20258888.top/Article/details/gtkggsinbl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlbxkjujk.html

[T47] Perl：正则捕获
来源：http://dali.316326.xyz/Article/details/gtthahwwrw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtwiqsumxz.html

[T48] Perl：正则替换
来源：http://dali.tianlin.xyz/Article/details/gtstcjabyx.html

$s =~ s/old/new/g;
来源：http://dali.quarkkingdee.top/Article/details/gtxbejbukm.html

[T49] Perl：函数
来源：http://dali.c1oappe.top/Article/details/gtvjlwyslc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtwspoimoi.html

[T50] Perl：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtojhyliye.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhongyouzk.top/Article/details/gtolfpsmva.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.svipenyu.cn/Article/details/gtwncxcmre.html

[T51] Scala：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyiienpa.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtllekmogo.html

[T52] Scala：变量
来源：http://dali.aibaodan.cn/Article/details/gtsxfcnbhu.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtflfcyzbx.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gterzzpdkq.html

s"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtgcdbietd.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtsuvhyfbq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.chenzaomai.com/Article/details/gtesdikqds.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtceatsska.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hysaishi.cn/Article/details/gtdanovcdu.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtaoautrsv.html

case class User(name: String, age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtnhqoqggy.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtyluyppeg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkprohus.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtapngatop.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gthvrykwjn.html

[T59] Scala：循环
来源：http://dali.shangyingyoupin.top/Article/details/gtujsifvcp.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtbjacxhch.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtuyhaydhw.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtiflxmqjj.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtjknhnutp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.vqdsnc.cn/Article/details/gtqskxvjfy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtyqzrmend.html

[U01] Py：创建虚拟环境
来源：http://dali.tanke756.top/Article/details/gtdpzkjiqz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtnofdyy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtjrzppgtr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtbpmnaeiw.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gtyqqtgqgl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gtzebjnuod.html

[U04] Py：变量调试打印
来源：http://dali.ppjwa.cn/Article/details/gtkqhwycmk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ydzc1.top/Article/details/gtwfdfncrg.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258.top/Article/details/gttaxdtqex.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtklgfaazc.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtzcacaqox.html

{**a, **b}
来源：http://dali.yuanzhike.top/Article/details/gtkonwjexl.html

[U07] Py：反转字典键值
来源：http://dali.smart0.xyz/Article/details/gtiolppofc.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtsabfuhso.html

[U08] Py：展平二维列表
来源：http://dali.hammf.cn/Article/details/gtduyevzsd.html

[y for x in nested for y in x]
来源：http://dali.gaohongyu789.top/Article/details/gtrwkrxzcs.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gtrhuzgmwb.html

max(d, key=d.get)
来源：http://dali.316326.xyz/Article/details/gtrmkzvdim.html

[U10] Py：按值排序字典
来源：http://dali.chenjidiqi.icu/Article/details/gtrjseplvg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gtvofuqwbw.html

[U11] Py：生成器表达式
来源：http://dali.gogol.net.cn/Article/details/gtkkvoyitw.html

(x * 2 for x in arr)
来源：http://dali.hammf.cn/Article/details/gtobokrojq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gthukgkhmm.html

Counter(arr).most_common(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtcgwjebnh.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtkusszqqi.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtbrrhuqms.html

[U14] Py：分组收集到列表
来源：http://dali.ybcxt.top/Article/details/gtzzvynqmj.html

defaultdict(list)
来源：http://dali.xziqi.cn/Article/details/gtcibbxiro.html

[U15] Py：高精度计时
来源：http://dali.havefunace.top/Article/details/gtsfxtjmav.html

t = time.perf_counter()
来源：http://dali.cashguo.top/Article/details/gtvxstvvzh.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtgjrripeu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hysaishi.cn/Article/details/gtjxdxtfot.html

[U17] Py：初始化日志
来源：http://dali.nanxinkj.top/Article/details/gttebjodjd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yuanzhike.top/Article/details/gtvxwnzklk.html

[U18] Py：预编译正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzkvolzje.html

pat = re.compile(r"\d+")
来源：http://dali.ehwqpu.com/Article/details/gtxghubxru.html

[U19] Py：正则替换带回调
来源：http://dali.tian-w.cn/Article/details/gtjmidsbym.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sxryk.cn/Article/details/gtbeyqcbnu.html

[U20] Py：缓存函数结果
来源：http://dali.andypj.xyz/Article/details/gtxewyevsm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtjfwxunbm.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258.top/Article/details/gtepiliawu.html

@contextlib.contextmanager
来源：http://dali.kuanghao11.cn/Article/details/gtxosjdwnd.html

[U22] Py：矩阵转置
来源：http://dali.nanxinkj.top/Article/details/gtxwiasxys.html

list(zip(*m))
来源：http://dali.hnqzz.top/Article/details/gtorijtuol.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gthdxeyqnu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gtgzpdhgcj.html

[U24] Py：路径操作
来源：http://dali.chenlongwang.top/Article/details/gtbcmaszsl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.mhx1999.top/Article/details/gtjekhctsv.html

[U25] Py：CSV 按字典读
来源：http://dali.andypj.xyz/Article/details/gtkyzaiayj.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtyebzivns.html

[U26] Py：并发下载
来源：http://dali.aizwys.cn/Article/details/gtsmnzxcdi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.bjfxy.top/Article/details/gtbkqayjvs.html

[U27] Py：异步 HTTP
来源：http://dali.daria6918.cn/Article/details/gtaryheaoi.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtkbxlxbfh.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gturvzywzj.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gttycrywsj.html

[U29] Py：属性校验
来源：http://dali.haohaochexian.top/Article/details/gtzqjtwgjh.html

@property 与 @x.setter 配合
来源：http://dali.meibo888.top/Article/details/gtzwcgktew.html

[U30] Py：数据类
来源：http://dali.sufxvd.cn/Article/details/gtxthgaksp.html

@dataclass(slots=True)
来源：http://dali.yvedp.cn/Article/details/gtndckwiot.html

[U31] Py：单测
来源：http://dali.bjfxy.top/Article/details/gtzmmagbzz.html

python -m pytest -q
来源：http://dali.pengpengdd.cyou/Article/details/gtlomdwudb.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gtufdywioy.html

ruff format . && ruff check --fix .
来源：http://dali.tianlin.xyz/Article/details/gtygsfbgsa.html

[U33] Py：打包发布
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuavvovmy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gtopomciwe.html

[U34] Py：判断编码
来源：http://dali.fzhhl.top/Article/details/gtmlisifyz.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gtkntqcqzn.html

[U35] Py：发送邮件
来源：http://dali.zhengqikj.top/Article/details/gthovkxibm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigufen.top/Article/details/gttkaralfy.html

[U36] Py：定时任务
来源：http://dali.gzhubu.top/Article/details/gtfexgevde.html

schedule.every(10).minutes.do(job)
来源：http://dali.c1oappe.top/Article/details/gtedsxtgfh.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gtbgnbkzbg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cheryme.top/Article/details/gtifhinihq.html

[U38] Py：获取脚本所在目录
来源：http://dali.yuxming.cn/Article/details/gtcivtbjwp.html

Path(__file__).resolve().parent
来源：http://dali.haohaochexian.top/Article/details/gtrtoyebwr.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangdashe.top/Article/details/gtwratqfhz.html

sys.stdout.isatty()
来源：http://dali.jiagoushi.top/Article/details/gtohaivnvu.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gtmqluiokn.html

print("err", file=sys.stderr)
来源：http://dali.pycfn.com/Article/details/gtmfpzuxue.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.shzxlz.cn/Article/details/gtczrywnrj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangshuangyany.cn/Article/details/gtuttlkpfy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gtienyziqb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuxming.cn/Article/details/gtjkzaiuxe.html

[U43] PHP：声明命名空间
来源：http://dali.xinyue.icu/Article/details/gtokirmtwp.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtlpqebszt.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtscbzdzaj.html

declare(strict_types=1);
来源：http://dali.shuidangran.top/Article/details/gtvtxnkcem.html

[U45] PHP：类型声明与返回类型
来源：http://dali.sufxvd.cn/Article/details/gtoustjmhc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gthkvavfzm.html

[U46] PHP：可空类型
来源：http://dali.daxiang520.top/Article/details/gtivdxraig.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtulectvzf.html

[U47] PHP：联合类型
来源：http://dali.zhongyouzk.top/Article/details/gtbbxdkugp.html

int|string $id
来源：http://dali.smart0.xyz/Article/details/gthxhqixgu.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gtnnlyiaqh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gaohongyu789.top/Article/details/gtrvliskqn.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtsojonyuc.html

public readonly string $name
来源：http://dali.dashuyun.cn/Article/details/gtffgphcgn.html

[U50] PHP：构造器属性提升
来源：http://dali.zhengqikj.top/Article/details/gtkacckoun.html

public function __construct(private int $id) {}
来源：http://dali.redwolf501.top/Article/details/gtbywylxza.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gtfobmyrxy.html

[$a, $b] = $arr;
来源：http://dali.hfpthk.cn/Article/details/gtqzwdnluh.html

[U52] PHP：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtqeolalpx.html

$double = fn($x) => $x * 2;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtehyglyvk.html

[U53] PHP：空合并运算符
来源：http://dali.pengpengdd.cyou/Article/details/gtwecwqdau.html

$v = $a ?? $b ?? "default";
来源：http://dali.hongshengwenyu.top/Article/details/gtozgpemjz.html

[U54] PHP：空安全调用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrufsfpgd.html

$obj?->method()
来源：http://dali.meibo888.top/Article/details/gtsyrgljoj.html

[U55] PHP：match 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtxujuppsv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtrcwtwkmd.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtdhawkalq.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gttauqaeqj.html

[U57] PHP：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtotthbpbj.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gtkumsmdeg.html

[U58] PHP：数组三件套
来源：http://dali.feifeiyinyue.top/Article/details/gtqfbgexyv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jinqigufen.top/Article/details/gtjqhpzuue.html

[U59] PHP：自定义排序
来源：http://dali.jinqigufen.top/Article/details/gtxlzomlok.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.kuanghao11.cn/Article/details/gtfsbhyujs.html

[U60] PHP：JSON 编解码
来源：http://dali.yongpay.top/Article/details/gtgrebmjqk.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.quarkkingdee.top/Article/details/gtklvgfmzr.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gtoioinhoq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.birdmap.top/Article/details/gtzxjabjoa.html

[U62] PHP：日期对象
来源：http://dali.dianchejie.cn/Article/details/gtqsjjoeji.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.nanxuanxn.top/Article/details/gtlskcrgcf.html

[U63] PHP：文件读写
来源：http://dali.yuxming.cn/Article/details/gtbbfxxgxa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuetiantiany.cn/Article/details/gtnhqtknyz.html

[U64] PHP：目录遍历
来源：http://dali.nanxuanxn.top/Article/details/gtawivonzr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jlsjyb.cn/Article/details/gtojqbxrmw.html

[U65] PHP：会话
来源：http://dali.yongpay.top/Article/details/gtuthivncp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtzywqahoj.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gttkfiqlbz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.snrcjt.cn/Article/details/gtyyweocjz.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtcbwskaed.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gtplfbotff.html

[U68] PHP：PDO 连接
来源：http://dali.jiagoushi.top/Article/details/gtjlkdkxfw.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sweek.top/Article/details/gtslwmmsvf.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gtpwvdwkqp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daxiang520.top/Article/details/gttfvtknuz.html

[U70] PHP：PDO 事务
来源：http://dali.ybcxt.top/Article/details/gtynkjsiqi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.redwolf501.top/Article/details/gtdhffuxub.html

[U71] PHP：抛出异常
来源：http://dali.tanke756.top/Article/details/gtqvhjpupf.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtwmbbnrxo.html

[U72] PHP：写错误日志
来源：http://dali.gogol.net.cn/Article/details/gtzngbanzt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtaquwrscj.html

[U73] PHP：读取 ini 配置
来源：http://dali.smart0.xyz/Article/details/gtbqonylmd.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtzxwgliif.html

[U74] PHP：读取环境变量
来源：http://dali.hnqzz.top/Article/details/gtvoinilje.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shanyushiyangtech.top/Article/details/gtqyevhrty.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtybmjsvwq.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gtdplvpbuv.html

[U76] PHP：简单路由
来源：http://dali.cqqwz.cn/Article/details/gtrizgeapq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gtbgabnmxd.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gtwwajviqz.html

composer require twig/twig
来源：http://dali.haohaochexian.top/Article/details/gticnfqpzs.html

[U78] PHP：单元测试
来源：http://dali.zhijiandao.cn/Article/details/gtkxmashhl.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gtsstaotnq.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtiqtbtdtn.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnijlcau.html

[U80] PHP：代码规范修复
来源：http://dali.andypj.xyz/Article/details/gtlzvbwxwl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jyoumei.cn/Article/details/gtlluotnuk.html


<!-- 参考信息 -->