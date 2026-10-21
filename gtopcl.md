代发 wailian999

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtyqoqnrrw.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtzcvltoho.html

static_cast<double>(a) / b
来源：http://dali.yonumen.top/Article/details/gtfripjawl.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gttnpxrias.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtowuqfelm.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtklfbuzwg.html

std::vector<int> w = std::move(v);
来源：http://dali.vqdsnc.cn/Article/details/gtzczeohls.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdybxvgew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtipqeqnlc.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtrnmqjmfu.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gtwfsoyvib.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtcxkwftdc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ybcxt.top/Article/details/gtyqlqohpp.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gthtblpwgq.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtvkenfxek.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtrylvicuf.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtifcsnkhj.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtmevtiisr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hysaishi.cn/Article/details/gttfhlkzbx.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtxwkkwfhr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtgmquqyso.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxnfuvfj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nwbrower.top/Article/details/gtkzbjteow.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtcxxcmmvo.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtzrdwrzah.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtznrokdkr.html

[T02] Kotlin：变量
来源：http://dali.gaohongyu789.top/Article/details/gtlufrjrdr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtrrgngscm.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtnkslxhbn.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtthpqjkud.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtdgaynsdz.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gticcaberv.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtouzhcspy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.wangshuangyany.cn/Article/details/gtayhzfbfc.html

[T06] Kotlin：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gtopjydooq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gtbanfkgcu.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gtmiyroyui.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtpbzhacst.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtabydbllm.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtwoplcwbg.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctlyeotr.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtvnzejvrq.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gthoalmywd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtdqvaabfg.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtghmdrgez.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtbrunbnet.html

[T12] Kotlin：解构声明
来源：http://dali.yongpay.top/Article/details/gtbwoymtvl.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gtdhfcffea.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtaggxumga.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtvrockknx.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtaqjrybwv.html

for (i in 1..10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtfokkytlc.html

[T15] Kotlin：接口
来源：http://dali.yangfankeji.com/Article/details/gtrkepbxrb.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigzrcueo.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtgjoeljdd.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gtfauuqous.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabbidpuv.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtnsmwczrq.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtxkxplzbz.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtxzqflsqa.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzjdavrs.html

if let n = opt { print(n) }
来源：http://dali.cdnleiting.top/Article/details/gtxfjrceqa.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gtujkanbyf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtzdflbumz.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtdhunfaaq.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtvpskueqe.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtzrgyjcqz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pengpengdd.cyou/Article/details/gtbwgzskjj.html

[T23] Swift：函数
来源：http://dali.yj20258888.top/Article/details/gtzcaufrrz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ydzc1.top/Article/details/gtyjqvpamr.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvdwvxyvl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gtaotjkwik.html

[T25] Swift：结构体
来源：http://dali.zhoulong.xyz/Article/details/gthzmkehhs.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtypirvhyi.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtyrrtzntg.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpstrjsjm.html

[T27] Swift：错误处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrahwdwkj.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtyrzjxrfv.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtxapzceva.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtyiuwgwlk.html

[T29] Swift：guard 提前返回
来源：http://dali.9152youxi.cn/Article/details/gtjmvnuwbg.html

guard let x = opt else { return }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaovnhfc.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtnadddkkm.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtutotuswp.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtucjtfeof.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtsiohacxz.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtkjevewba.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gttculvhto.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gttehlrhuj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gaohongyu789.top/Article/details/gtqzlzjipx.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gttlpkqtqk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gthmzdiaoz.html

[T35] Lua：字典表
来源：http://dali.xuanzx.com/Article/details/gtxjynozrz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtvfalltyz.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtabtebwcf.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtgiltpolb.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gttxkculyw.html

"a" .. "b"
来源：http://dali.nanxinkj.top/Article/details/gtyngryqye.html

[T38] Lua：条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtsucusjlf.html

if x > 0 then print("正") end
来源：http://dali.xuanzx.com/Article/details/gtwhrjuwso.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gthcysaeje.html

string.find(s, "%d+")
来源：http://dali.andypj.xyz/Article/details/gtthkiayco.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtoxqmnpct.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtsvcnnenv.html

[T41] Perl：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtwaqlrpya.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gtqpchwstp.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gtkuxqjynu.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gtworelkna.html

[T43] Perl：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtcsxakgql.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gtbqodqfng.html

[T44] Perl：条件
来源：http://dali.hnxiangtu.top/Article/details/gtjafqijab.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigufen.top/Article/details/gtzxaxnagj.html

[T45] Perl：数组遍历
来源：http://dali.chenlongwang.top/Article/details/gtityikaps.html

for my $x (@arr) { print $x; }
来源：http://dali.zhixingplan.top/Article/details/gtiappwamv.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtxrybcfhd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtjadtrtdc.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtxhypzwxs.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sufxvd.cn/Article/details/gtxdyklgzn.html

[T48] Perl：正则替换
来源：http://dali.jiagoushi.top/Article/details/gtuqwbebol.html

$s =~ s/old/new/g;
来源：http://dali.hammf.cn/Article/details/gtzslnrjfo.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtecgmcfze.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtkjowzzon.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtigmteiax.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gtplqvfdzr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.fengsongda.top/Article/details/gturybccve.html

[T51] Scala：Hello World
来源：http://dali.pycfn.com/Article/details/gtlotdyavx.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtmxkzqquj.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtuhdmsddc.html

val a = 1;  var b = 2
来源：http://dali.pycfn.com/Article/details/gtemktbqwg.html

[T53] Scala：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbgeyqnqe.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gttksxxlhf.html

[T54] Scala：集合映射
来源：http://dali.jianghu66.top/Article/details/gtoxqmhiog.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtoklsznuo.html

[T55] Scala：集合过滤
来源：http://dali.yj202588.top/Article/details/gtibcfvrax.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtneqhmsdt.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtfygyhckp.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtoitljbfh.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtrwdtdwtj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfaefyac.html

[T58] Scala：函数定义
来源：http://dali.hnqzz.top/Article/details/gtgmpoygzv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqjupwsc.html

[T59] Scala：循环
来源：http://dali.hysaishi.cn/Article/details/gttsgphxng.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtgfankmib.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtitvgeppy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gtegcsqdfk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtcrfwhayl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtpyknovna.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtkuddwrfq.html

[U01] Py：创建虚拟环境
来源：http://dali.shanyushiyangkeji.top/Article/details/gtslcfciyf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sweek.top/Article/details/gtcqwdgecq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gtgawnddfs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtgslxxbgr.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gteqjtkybp.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitdkjjdn.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpaczddbt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fzhhl.top/Article/details/gtlxjdslqb.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtlepvvqhh.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtpptiyozd.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gtpxswptfv.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gtqwtwiand.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gtamirjwbb.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtedxrwsrt.html

[U08] Py：展平二维列表
来源：http://dali.iojbl.cn/Article/details/gtdsdsqsyp.html

[y for x in nested for y in x]
来源：http://dali.zhongyouzk.top/Article/details/gtlnutesdi.html

[U09] Py：字典取最大值的键
来源：http://dali.hysaishi.cn/Article/details/gtrljiuxxa.html

max(d, key=d.get)
来源：http://dali.cdnleiting.top/Article/details/gtbipsoieb.html

[U10] Py：按值排序字典
来源：http://dali.316326.xyz/Article/details/gtfjfveymt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtcinktorn.html

[U11] Py：生成器表达式
来源：http://dali.dianchejie.cn/Article/details/gtncnxicqe.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtoewusung.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuanzhike.top/Article/details/gtbdgzqdbq.html

Counter(arr).most_common(3)
来源：http://dali.ydzc1.top/Article/details/gtexiomfyb.html

[U13] Py：固定长度队列
来源：http://dali.dashuyun.cn/Article/details/gtjfrfborr.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrcbqdkp.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gtytcikcte.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtuzuskdyq.html

[U15] Py：高精度计时
来源：http://dali.cqqwz.cn/Article/details/gtlzufchqx.html

t = time.perf_counter()
来源：http://dali.haohaochexian.top/Article/details/gtlrzwljbd.html

[U16] Py：命令行参数解析
来源：http://dali.cdnleiting.top/Article/details/gtzhogqaby.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jiagoushi.top/Article/details/gtfezmkief.html

[U17] Py：初始化日志
来源：http://dali.haohaochexian.top/Article/details/gtzpguulye.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yangfankeji.com/Article/details/gtezfqsojh.html

[U18] Py：预编译正则
来源：http://dali.xuetiantiany.cn/Article/details/gtkfuwfiyr.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258888.top/Article/details/gtvnbxrpat.html

[U19] Py：正则替换带回调
来源：http://dali.daxiang520.top/Article/details/gtprjlrvmv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.wangdashe.top/Article/details/gttgqzuxze.html

[U20] Py：缓存函数结果
来源：http://dali.chenzaomai.com/Article/details/gtuubciqop.html

@functools.lru_cache(maxsize=None)
来源：http://dali.316326.xyz/Article/details/gttojkekfz.html

[U21] Py：自定义上下文管理器
来源：http://dali.yanxiufei.cn/Article/details/gtcqngchne.html

@contextlib.contextmanager
来源：http://dali.cucudq.cn/Article/details/gtwdztidon.html

[U22] Py：矩阵转置
来源：http://dali.chenlongwang.top/Article/details/gtjsauwzgz.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gtbdbwcnsx.html

[U23] Py：分块读取大文件
来源：http://dali.zhongyouzk.top/Article/details/gtocfqcifh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hysaishi.cn/Article/details/gtiazdtmoo.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gtshaduvux.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlbeqvqif.html

[U25] Py：CSV 按字典读
来源：http://dali.xuanzx.com/Article/details/gtucixvbuu.html

csv.DictReader(f)
来源：http://dali.sufxvd.cn/Article/details/gttuavquxn.html

[U26] Py：并发下载
来源：http://dali.jqgufenzy.top/Article/details/gtfyostqgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhengqikj.top/Article/details/gtoefioveq.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gtghrnoggx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.pycfn.com/Article/details/gtkpnndskr.html

[U28] Py：类型别名
来源：http://dali.yj202588.top/Article/details/gtsssohigu.html

UserId = int
来源：http://dali.pengpengdd.cyou/Article/details/gtzjobyhkk.html

[U29] Py：属性校验
来源：http://dali.iojbl.cn/Article/details/gtpvvnjcwl.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtlbyhsvue.html

[U30] Py：数据类
来源：http://dali.meibo888.top/Article/details/gtglbsxmzt.html

@dataclass(slots=True)
来源：http://dali.yanxiufei.cn/Article/details/gtjocwdwqx.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtotzmdxei.html

python -m pytest -q
来源：http://dali.wangshuangyany.cn/Article/details/gtlfnfrpzd.html

[U32] Py：代码格式化
来源：http://dali.0kj1m.cn/Article/details/gtbdgdzjlk.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gthtttbzzz.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gtcdrcvupw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgufenzy.top/Article/details/gtxhipujfk.html

[U34] Py：判断编码
来源：http://dali.hysaishi.cn/Article/details/gtkfkqplfy.html

chardet.detect(raw)
来源：http://dali.chenzaomai.com/Article/details/gtjqfkjlct.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtpykblwiu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.snrcjt.cn/Article/details/gtdhdhhgfj.html

[U36] Py：定时任务
来源：http://dali.yanxiufei.cn/Article/details/gttarmephq.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhongyouzk.top/Article/details/gtdjikzpqi.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtwivthjyi.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtgxoelepk.html

[U38] Py：获取脚本所在目录
来源：http://dali.havefunace.top/Article/details/gtragrdtkn.html

Path(__file__).resolve().parent
来源：http://dali.pengpengdd.cyou/Article/details/gtjtluknsy.html

[U39] Py：判断是否在交互环境
来源：http://dali.meibo888.top/Article/details/gtzuwwlafg.html

sys.stdout.isatty()
来源：http://dali.snrcjt.cn/Article/details/gtzgqlpjbl.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtndmxtvyg.html

print("err", file=sys.stderr)
来源：http://dali.chenzaomai.com/Article/details/gthlhswfbg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijytwmol.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.chenlongwang.top/Article/details/gtgbtnhqft.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gtnkcjknfe.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtufgyhdok.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtiwncicye.html

namespace App\Http;
来源：http://dali.hongshengwenyu.top/Article/details/gtbgrpizgx.html

[U44] PHP：开启严格类型
来源：http://dali.nwbrower.top/Article/details/gtsxclwjva.html

declare(strict_types=1);
来源：http://dali.xuanzx.com/Article/details/gtddbkkukx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cqqwz.cn/Article/details/gtakymqfdf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtnmjpcski.html

[U46] PHP：可空类型
来源：http://dali.cashguo.top/Article/details/gtinytzdcm.html

?string $name = null
来源：http://dali.shanyushiyangkeji.top/Article/details/gthddwtwim.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtpsdkeymk.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxsnrdmw.html

[U48] PHP：纯枚举
来源：http://dali.zdqjudy.top/Article/details/gtwcucwcvq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtachfeetk.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtidenknuq.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtcoiyhhur.html

[U50] PHP：构造器属性提升
来源：http://dali.daxiang520.top/Article/details/gtdascusun.html

public function __construct(private int $id) {}
来源：http://dali.yueranfly.top/Article/details/gtvqfqbtpb.html

[U51] PHP：数组解构
来源：http://dali.gzhubu.top/Article/details/gtgetqzfmm.html

[$a, $b] = $arr;
来源：http://dali.zycfv.cn/Article/details/gtmlycveaj.html

[U52] PHP：箭头函数
来源：http://dali.hammf.cn/Article/details/gttrelrkqb.html

$double = fn($x) => $x * 2;
来源：http://dali.yongpay.top/Article/details/gtgbiqdhlc.html

[U53] PHP：空合并运算符
来源：http://dali.shzxlz.cn/Article/details/gtnzopvqkj.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhoulong.xyz/Article/details/gtpbqpxaqe.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtjgbshuzi.html

$obj?->method()
来源：http://dali.chenlongwang.top/Article/details/gtxxfasayf.html

[U55] PHP：match 表达式
来源：http://dali.dashuyun.cn/Article/details/gtwoghiqio.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shzxlz.cn/Article/details/gtphhhdgfm.html

[U56] PHP：命名参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwnuipqz.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtcghhunoq.html

[U57] PHP：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtbjgslfwp.html

"值: {$a}"
来源：http://dali.pycfn.com/Article/details/gtrtbknzgk.html

[U58] PHP：数组三件套
来源：http://dali.snrcjt.cn/Article/details/gtpceefiis.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sufxvd.cn/Article/details/gtanhmevgi.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtyhamhvsh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.tanke756.top/Article/details/gtssmunudt.html

[U60] PHP：JSON 编解码
来源：http://dali.yvedp.cn/Article/details/gtcjqqwhxh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yvedp.cn/Article/details/gtnhldkizp.html

[U61] PHP：正则
来源：http://dali.tanke756.top/Article/details/gtwybtaclv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ppjwa.cn/Article/details/gtwwpoharv.html

[U62] PHP：日期对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweygzwcy.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ehwqpu.com/Article/details/gtmrsgrxol.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gtehciwwaa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shuidangran.top/Article/details/gtdmubngfv.html

[U64] PHP：目录遍历
来源：http://dali.chenzaomai.com/Article/details/gtrodvumxa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ivvv.top/Article/details/gttqcyqyku.html

[U65] PHP：会话
来源：http://dali.yonumen.top/Article/details/gtbsblalvo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtpqhpijsl.html

[U66] PHP：设置 Cookie
来源：http://dali.havefunace.top/Article/details/gtiiuhlwfr.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.meibo888.top/Article/details/gtbvzhpnjw.html

[U67] PHP：处理文件上传
来源：http://dali.guannengcc.top/Article/details/gtogfggcfm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jinghuilouyu.cn/Article/details/gtnorcmbnp.html

[U68] PHP：PDO 连接
来源：http://dali.cucudq.cn/Article/details/gtzbdhjjah.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.0kj1m.cn/Article/details/gtyjolcwpy.html

[U69] PHP：PDO 预处理
来源：http://dali.hywenlv.cn/Article/details/gtlnyczpjz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gtxvbxaxxr.html

[U70] PHP：PDO 事务
来源：http://dali.pycfn.com/Article/details/gtkpvmacus.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hywenlv.cn/Article/details/gtvvdcfaks.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtdatksdlq.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhongyouzk.top/Article/details/gtqpqixdct.html

[U72] PHP：写错误日志
来源：http://dali.yonumen.top/Article/details/gtkuqyekzu.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gttmijueqe.html

[U73] PHP：读取 ini 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtbdpsfyho.html

parse_ini_file("config.ini", true)
来源：http://dali.xuanzx.com/Article/details/gtmryganjy.html

[U74] PHP：读取环境变量
来源：http://dali.hysaishi.cn/Article/details/gtoklfkkis.html

getenv("APP_ENV") ?: "production"
来源：http://dali.316326.xyz/Article/details/gttjvybkfz.html

[U75] PHP：依赖注入
来源：http://dali.zhixingplan.top/Article/details/gtfkkvshfc.html

composer require psr/container
来源：http://dali.zhoulong.xyz/Article/details/gtbxtbzlff.html

[U76] PHP：简单路由
来源：http://dali.dianchejie.cn/Article/details/gtmdzmfljb.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.9152youxi.cn/Article/details/gtoanufitd.html


<!-- 参考信息 -->