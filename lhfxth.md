代发 wailian999

[S41] C++：类与构造函数
来源：http://dali.gzhubu.top/Article/details/gt2txwzopxq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gt2zacauzvs.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gt2uchgucsi.html

class B : public Base { public: void f() override {} };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fcgxknmw.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gt2mbaouaso.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gt2axdofsbf.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gt2rletxfls.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2hndasjzx.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gt2bllkpmij.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ertitejj.html

[S46] C++：函数模板
来源：http://dali.xuetiantiany.cn/Article/details/gt2pnzrayhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gt2hosjkeoi.html

[S47] C++：结构化绑定遍历
来源：http://dali.hnqzz.top/Article/details/gt2fkftznhg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cheryme.top/Article/details/gt2smobicje.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2wzzctqna.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gt2ifwxovju.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gt2oefuqnik.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gt2yjkntooc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xylfe.cn/Article/details/gt2xlpljgwn.html

[S50] C++：格式化数字
来源：http://dali.ehwqpu.com/Article/details/gt2rkjbaizk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gt2adphdcti.html

[S51] C++：显式类型转换
来源：http://dali.cqqwz.cn/Article/details/gt2ssqwetlj.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gt2dcsxosqs.html

[S52] C++：const 与 noexcept
来源：http://dali.daria6918.cn/Article/details/gt2lrwoqral.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2qcjzraww.html

[S53] C++：移动语义
来源：http://dali.andypj.xyz/Article/details/gt2ksmkslcr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2nlkbpfnz.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gt2ymghzgsm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aibaodan.cn/Article/details/gt2zfkiyrnc.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gt2plvrepqj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uiqrrnzk.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2kawghjwq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wcjgdyjv.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gt2hgqmlsag.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gt2jhtyxflj.html

[S58] C++：命名空间
来源：http://dali.birdmap.top/Article/details/gt2dnhbngse.html

namespace ns { int f() { return 1; } }
来源：http://dali.bjfxy.top/Article/details/gt2aqdrmtji.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gt2meftfggm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2baqipeeh.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gt2fvwaqpou.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gt2ldbkndji.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fcmkmpwt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gt2qpdjnvlz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2boxwzrul.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ltgjoijh.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2flnerflm.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvdfzzk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gt2pkoispsi.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gt2hwatrvdc.html

"值: $b"
来源：http://dali.havefunace.top/Article/details/gt2ebnxbuyh.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2zyqseaxp.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gt2cciwivip.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gt2dqyefhgu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cheryme.top/Article/details/gt2ifoschaw.html

[T06] Kotlin：集合映射
来源：http://dali.yonumen.top/Article/details/gt2vnojjnwo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gt2gavehlpj.html

[T07] Kotlin：集合过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2fderpnrw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhengqikj.top/Article/details/gt2jefvauia.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2gtmwgapx.html

data class User(val name: String, val age: Int)
来源：http://dali.havefunace.top/Article/details/gt2npxvncky.html

[T09] Kotlin：扩展函数
来源：http://dali.tanke756.top/Article/details/gt2jirlzjbk.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gt2ydibfhnz.html

[T10] Kotlin：默认参数
来源：http://dali.xziqi.cn/Article/details/gt2kcvvuzfr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gt2nnwhvbsg.html

[T11] Kotlin：协程
来源：http://dali.feifeiyinyue.top/Article/details/gt2fiwhpswx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hfpthk.cn/Article/details/gt2rslljhhe.html

[T12] Kotlin：解构声明
来源：http://dali.hammf.cn/Article/details/gt2adguppil.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gt2gcqbutle.html

[T13] Kotlin：只读 Map
来源：http://dali.daria6918.cn/Article/details/gt2ivwiwqpn.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gt2jhulhvdi.html

[T14] Kotlin：循环
来源：http://dali.gotoacloud.top/Article/details/gt2cqnnuprz.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gt2pslrxtpp.html

[T15] Kotlin：接口
来源：http://dali.gaohongyu789.top/Article/details/gt2ztgrlblc.html

interface Shape { fun area(): Double }
来源：http://dali.sufxvd.cn/Article/details/gt2ffxrtavr.html

[T16] Swift：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2xnwbzcnn.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2bpaxoohr.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gt2lvmlveud.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gt2cupswrhb.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2hrlyfuau.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gt2yoeuejsq.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2ewaxvuun.html

if let n = opt { print(n) }
来源：http://dali.zhixingplan.top/Article/details/gt2wmgcshwg.html

[T20] Swift：数组操作
来源：http://dali.yueranfly.top/Article/details/gt2ehmofkek.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.andypj.xyz/Article/details/gt2mmarwmwg.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gt2lowipmlb.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gt2lnxuxufm.html

[T22] Swift：字典
来源：http://dali.yangfankeji.com/Article/details/gt2axxwazda.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xziqi.cn/Article/details/gt2coktvuhg.html

[T23] Swift：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2dtlezwom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.pycfn.com/Article/details/gt2uyiqvbsg.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gt2ijjyqdoy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jyoumei.cn/Article/details/gt2zifamcus.html

[T25] Swift：结构体
来源：http://dali.c1oappe.top/Article/details/gt2stwkxuia.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gt2eykdtsoe.html

[T26] Swift：类与重写
来源：http://dali.quarkkingdee.top/Article/details/gt2cxvideyo.html

class A: Base { override func f() {} }
来源：http://dali.cucudq.cn/Article/details/gt2bvlxlavy.html

[T27] Swift：错误处理
来源：http://dali.zycfv.cn/Article/details/gt2yruirxog.html

do { try f() } catch { print(error) }
来源：http://dali.nwbrower.top/Article/details/gt2nyynjiqa.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gt2vxkeuinx.html

enum Color { case red, green }
来源：http://dali.0kj1m.cn/Article/details/gt2bcbqkqid.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gt2iudxyoeo.html

guard let x = opt else { return }
来源：http://dali.cheryme.top/Article/details/gt2dazixxkm.html

[T30] Swift：协议
来源：http://dali.guowangkeji.top/Article/details/gt2awjqrrkw.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2qbmigbwq.html

[T31] Lua：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2xnqrfbog.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gt2oahptnzf.html

[T32] Lua：局部变量
来源：http://dali.svipenyu.cn/Article/details/gt2pxsanstk.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gt2dxxwlmpk.html

[T33] Lua：表（数组）
来源：http://dali.yj20258.top/Article/details/gt2honmvkda.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gt2gbotyhcr.html

[T34] Lua：遍历表
来源：http://dali.yj202588.top/Article/details/gt2oqvlrxjs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.chenlongwang.top/Article/details/gt2zvafbxzm.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gt2koexeopx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gt2ocbumerg.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2okqonizk.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gt2sgioptvn.html

[T37] Lua：字符串拼接
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sokvlspa.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ccytctrf.html

[T38] Lua：条件
来源：http://dali.xinyue.icu/Article/details/gt2qtrtvyrc.html

if x > 0 then print("正") end
来源：http://dali.gogol.net.cn/Article/details/gt2ytpdbwnp.html

[T39] Lua：模式匹配
来源：http://dali.pycfn.com/Article/details/gt2eiovgrzm.html

string.find(s, "%d+")
来源：http://dali.dianchejie.cn/Article/details/gt2lgqreuom.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gt2nprohyyv.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gt2dhyzndpg.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2vpwyhrot.html

print "Hello\n";
来源：http://dali.gogol.net.cn/Article/details/gt2jixqvgbs.html

[T42] Perl：变量类型
来源：http://dali.pycfn.com/Article/details/gt2ynndpjwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.iojbl.cn/Article/details/gt2apabmacy.html

[T43] Perl：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gt2mmhnopzn.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gt2kxunenyq.html

[T44] Perl：条件
来源：http://dali.hnqzz.top/Article/details/gt2rgippydd.html

if ($a > 0) { print "正"; }
来源：http://dali.guannengcc.top/Article/details/gt2altukpzi.html

[T45] Perl：数组遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2sbegskpg.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2mxxzmrzt.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gt2sukumomt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ooqbaizv.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gt2slgudaxr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gt2ldkniqlt.html

[T48] Perl：正则替换
来源：http://dali.yanxiufei.cn/Article/details/gt2osnobtkl.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gt2kxcyujhs.html

[T49] Perl：函数
来源：http://dali.ppjwa.cn/Article/details/gt2lpdatwhp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gt2agtydqxa.html

[T50] Perl：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2inxxadgb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.daria6918.cn/Article/details/gt2szcovxjb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yuanzhike.top/Article/details/gt2qgvvfikf.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2xntztqne.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gt2xkejmrpz.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2dbxnigrc.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gt2ghlnpaju.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gt2guicqoqt.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2ploutjlp.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2oikfflux.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gt2pigfhzoa.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gt2hkvgnnxz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gt2xmskjtdm.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gt2wnyzpcmx.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2mpacyhlj.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gt2eplterzi.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gt2qdyktetq.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gt2cnamrwav.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2dlhtnfey.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gt2iophtbaz.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gt2mafnymcu.html

[T60] Scala：折叠
来源：http://dali.bjfxy.top/Article/details/gt2njgfdspm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gt2xkrlzbja.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygpnpeqb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gt2zzjagozi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2eghddhpl.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gt2jcsbkskr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.kuanghao11.cn/Article/details/gt2mitwzdym.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gt2ctjyoqdx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gt2utiqhnne.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gt2nfnjupxj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhixingplan.top/Article/details/gt2pivjvrwq.html

[U04] Py：变量调试打印
来源：http://dali.kuanghao11.cn/Article/details/gt2toktvvaj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gt2gfdgswis.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gt2bparzgcz.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gt2xqlaxujc.html

[U06] Py：合并两个字典
来源：http://dali.cashguo.top/Article/details/gt2yjvmmvgs.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2nnhdhbdr.html

[U07] Py：反转字典键值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ejisqqro.html

{v: k for k, v in d.items()}
来源：http://dali.aizwys.cn/Article/details/gt2bxrgmado.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gt2jfkytzcc.html

[y for x in nested for y in x]
来源：http://dali.ppjwa.cn/Article/details/gt2ammhhbif.html

[U09] Py：字典取最大值的键
来源：http://dali.c1oappe.top/Article/details/gt2nincjbgx.html

max(d, key=d.get)
来源：http://dali.yuxming.cn/Article/details/gt2jamkwlww.html

[U10] Py：按值排序字典
来源：http://dali.hammf.cn/Article/details/gt2lcrmubfs.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gt2ajobmqio.html

[U11] Py：生成器表达式
来源：http://dali.shuidangran.top/Article/details/gt2hszoudlf.html

(x * 2 for x in arr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uhldcbwt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.birdmap.top/Article/details/gt2wkdorjpm.html

Counter(arr).most_common(3)
来源：http://dali.yangfankeji.com/Article/details/gt2rrdynxfn.html

[U13] Py：固定长度队列
来源：http://dali.zhixingplan.top/Article/details/gt2pnkrkhfv.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gt2eoorjsnj.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258.top/Article/details/gt2apvncmyo.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gt2uugtmdcy.html

[U15] Py：高精度计时
来源：http://dali.0kj1m.cn/Article/details/gt2fpdhsvmb.html

t = time.perf_counter()
来源：http://dali.chenjidiqi.icu/Article/details/gt2dxbpmtsy.html

[U16] Py：命令行参数解析
来源：http://dali.hongshengwenyu.top/Article/details/gt2gtmkjxqu.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gt2jyfpyaed.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gt2dyqphqix.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gt2ohbvnhzj.html

[U18] Py：预编译正则
来源：http://dali.guowangkeji.top/Article/details/gt2tadqabah.html

pat = re.compile(r"\d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rfsykmdk.html

[U19] Py：正则替换带回调
来源：http://dali.gotoacloud.top/Article/details/gt2ljuljfyl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gt2gdsdeyqj.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gt2gmuibgxy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jianghu66.top/Article/details/gt2mgazezig.html

[U21] Py：自定义上下文管理器
来源：http://dali.gzhubu.top/Article/details/gt2orqdmdwo.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gt2eczfirqf.html

[U22] Py：矩阵转置
来源：http://dali.ydzc1.top/Article/details/gt2tjujpqwe.html

list(zip(*m))
来源：http://dali.daxiang520.top/Article/details/gt2texjcgwh.html

[U23] Py：分块读取大文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oulqwyxe.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhongyouzk.top/Article/details/gt2kvixhntw.html

[U24] Py：路径操作
来源：http://dali.cucudq.cn/Article/details/gt2rshagvjm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gt2utvnzucg.html

[U25] Py：CSV 按字典读
来源：http://dali.9152youxi.cn/Article/details/gt2dgyrleed.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gt2iesxkzxt.html

[U26] Py：并发下载
来源：http://dali.jianghu66.top/Article/details/gt2pyckfayj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gt2xteyavfc.html

[U27] Py：异步 HTTP
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tpyeexcw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sysykeji.top/Article/details/gt2puwbfsnj.html

[U28] Py：类型别名
来源：http://dali.sxryk.cn/Article/details/gt2jzjdnrfw.html

UserId = int
来源：http://dali.cdnleiting.top/Article/details/gt2lwgoxakm.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gt2acmcrysc.html

@property 与 @x.setter 配合
来源：http://dali.cucudq.cn/Article/details/gt2oxbwskpf.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gt2ujhojgsc.html

@dataclass(slots=True)
来源：http://dali.ppjwa.cn/Article/details/gt2itfifbft.html

[U31] Py：单测
来源：http://dali.hnxiangtu.top/Article/details/gt2mmiumokf.html

python -m pytest -q
来源：http://dali.zhixingplan.top/Article/details/gt2fjqjgews.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gt2nthsgwyz.html

ruff format . && ruff check --fix .
来源：http://dali.xuanzx.com/Article/details/gt2jysuytaz.html

[U33] Py：打包发布
来源：http://dali.birdmap.top/Article/details/gt2jbeclguq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gt2wtufzslp.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eeylxkgj.html

chardet.detect(raw)
来源：http://dali.hnxiangtu.top/Article/details/gt2ctfptcxe.html

[U35] Py：发送邮件
来源：http://dali.zhiwuduotai.top/Article/details/gt2qeubfdrk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xylfe.cn/Article/details/gt2ylkwahjm.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gt2pxifigxx.html

schedule.every(10).minutes.do(job)
来源：http://dali.yonumen.top/Article/details/gt2syiuourp.html

[U37] Py：读写 Excel
来源：http://dali.shuidangran.top/Article/details/gt2ygltwcsq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kkoiginf.html

[U38] Py：获取脚本所在目录
来源：http://dali.yongpay.top/Article/details/gt2fjogeiub.html

Path(__file__).resolve().parent
来源：http://dali.fengsongda.top/Article/details/gt2wowgviiv.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhiwuduotai.top/Article/details/gt2wbjkncjn.html

sys.stdout.isatty()
来源：http://dali.sysykeji.top/Article/details/gt2ykxxnxty.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gt2eonyavqd.html

print("err", file=sys.stderr)
来源：http://dali.shuidangran.top/Article/details/gt2iwgcgwkr.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xziqi.cn/Article/details/gt2ucbbyask.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.iojbl.cn/Article/details/gt2goruvnah.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.dashuyun.cn/Article/details/gt2nfhokmqg.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yueranfly.top/Article/details/gt2iekoclme.html

[U43] PHP：声明命名空间
来源：http://dali.jqgfzy.top/Article/details/gt2diiqkqaf.html

namespace App\Http;
来源：http://dali.nwbrower.top/Article/details/gt2hrznpnyc.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gt2pffdpwae.html

declare(strict_types=1);
来源：http://dali.sxryk.cn/Article/details/gt2odplclkn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wjslmenz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bwulnsik.html

[U46] PHP：可空类型
来源：http://dali.xuanzx.com/Article/details/gt2ssdzknqx.html

?string $name = null
来源：http://dali.pycfn.com/Article/details/gt2kzhvcwsb.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gt2llqsyhnn.html

int|string $id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pttllevk.html

[U48] PHP：纯枚举
来源：http://dali.jlsjyb.cn/Article/details/gt2itmvozpv.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yangfankeji.com/Article/details/gt2myocpnff.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gt2kawegvak.html

public readonly string $name
来源：http://dali.hysaishi.cn/Article/details/gt2mjimsjkz.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gt2zbpcuzar.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gt2sbfknork.html

[U51] PHP：数组解构
来源：http://dali.aibaodan.cn/Article/details/gt2iqyrxgbo.html

[$a, $b] = $arr;
来源：http://dali.shzxlz.cn/Article/details/gt2liwlmehk.html

[U52] PHP：箭头函数
来源：http://dali.yj20258.top/Article/details/gt2akswffgc.html

$double = fn($x) => $x * 2;
来源：http://dali.0kj1m.cn/Article/details/gt2nismyben.html

[U53] PHP：空合并运算符
来源：http://dali.cucudq.cn/Article/details/gt2dxugdlfp.html

$v = $a ?? $b ?? "default";
来源：http://dali.jiagoushi.top/Article/details/gt2kbodmewy.html

[U54] PHP：空安全调用
来源：http://dali.cqqwz.cn/Article/details/gt2amrmeszm.html

$obj?->method()
来源：http://dali.yonumen.top/Article/details/gt2mvurfmov.html

[U55] PHP：match 表达式
来源：http://dali.pycfn.com/Article/details/gt2huxxpjjd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dtiycfsk.html

[U56] PHP：命名参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2rgzkkqci.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gt2ycwnkpzz.html

[U57] PHP：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuwdabuh.html

"值: {$a}"
来源：http://dali.fzhhl.top/Article/details/gt2uxmnbamn.html

[U58] PHP：数组三件套
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gjfasbrm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hnqzz.top/Article/details/gt2gvdxfzzq.html

[U59] PHP：自定义排序
来源：http://dali.sysykeji.top/Article/details/gt2nayrvggu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.gotoacloud.top/Article/details/gt2ygqjxabn.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qcvlvnlg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.vqdsnc.cn/Article/details/gt2nhrgfxkd.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gt2kyvgfokg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.havefunace.top/Article/details/gt2oeycclkk.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gt2dqelrhqc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.iojbl.cn/Article/details/gt2uhxfpoie.html

[U63] PHP：文件读写
来源：http://dali.snrcjt.cn/Article/details/gt2kghebeij.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xuanzx.com/Article/details/gt2htsrzbkj.html

[U64] PHP：目录遍历
来源：http://dali.andypj.xyz/Article/details/gt2rossqayh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.cdnleiting.top/Article/details/gt2rsqlifcy.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gt2yuotlbka.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2bixvuldc.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2qeodznlo.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuxming.cn/Article/details/gt2mlkkibdq.html


<!-- 参考信息 -->