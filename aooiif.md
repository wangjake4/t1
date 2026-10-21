代发 wailian999

[T05] Kotlin：when 表达式
来源：http://dali.chenlongwang.top/Article/details/gtrgijzbym.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.0kj1m.cn/Article/details/gtwjmgafui.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnjjzgjkz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtvovabkot.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gtmggkmpco.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtesnhxvdr.html

[T08] Kotlin：数据类
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjjdbndxn.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtngweqqeu.html

[T09] Kotlin：扩展函数
来源：http://dali.redwolf501.top/Article/details/gtpdavwzit.html

fun String.exclaim() = this + "!"
来源：http://dali.havefunace.top/Article/details/gtehuwdkrj.html

[T10] Kotlin：默认参数
来源：http://dali.bjfxy.top/Article/details/gtkdqbzavu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtjquawhic.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtthopcikq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gttufqrfbz.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gttgkdgwml.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gtrkfhlaat.html

[T13] Kotlin：只读 Map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtztyqrxew.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtkxcqrapp.html

[T14] Kotlin：循环
来源：http://dali.yuanzhike.top/Article/details/gtvehntbeq.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtwnuxtgzu.html

[T15] Kotlin：接口
来源：http://dali.hnxiangtu.top/Article/details/gtqlslbefm.html

interface Shape { fun area(): Double }
来源：http://dali.snrcjt.cn/Article/details/gthotpleue.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtfsyegkmx.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtzwdnjxkh.html

[T17] Swift：变量与常量
来源：http://dali.9152youxi.cn/Article/details/gtlucxnmxu.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtavdlouzc.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqaogsaaj.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtaufbviqk.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gtoiwqidwn.html

if let n = opt { print(n) }
来源：http://dali.bjfxy.top/Article/details/gtxmncmraz.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtayusqtkr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtxtjbmtqw.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtwqnqcika.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gtkbeflivv.html

[T22] Swift：字典
来源：http://dali.jiagoushi.top/Article/details/gtgpwfvkrz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gttcpjlpjn.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gtevnsmxkr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gotoacloud.top/Article/details/gtwqsqnliw.html

[T24] Swift：闭包
来源：http://dali.0kj1m.cn/Article/details/gthrrepjcu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtdwrpptlz.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtdmzltxld.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gtibphjsau.html

[T26] Swift：类与重写
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhtdojgd.html

class A: Base { override func f() {} }
来源：http://dali.pycfn.com/Article/details/gtippfjwdb.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtegwnwibr.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtklgpiumj.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtczoxdvgp.html

enum Color { case red, green }
来源：http://dali.yuanzhike.top/Article/details/gtlsrttceq.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtuptjczcf.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtwyrpgypj.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtlwbzgroc.html

protocol Shape { func area() -> Double }
来源：http://dali.jinqigfzy.top/Article/details/gtfxewpnps.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtjtmbgtrx.html

print("Hello")
来源：http://dali.daria6918.cn/Article/details/gtxjzjhmpr.html

[T32] Lua：局部变量
来源：http://dali.zhixingplan.top/Article/details/gtjvahlsav.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtxurmymda.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtlllwfhbb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hnxiangtu.top/Article/details/gtarqjybmk.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtageylxmf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtrtgfstxr.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtkrdknxvl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yj20258888.top/Article/details/gtqbilludc.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtsgckohlr.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gtdeuxougn.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gttwvgslwb.html

"a" .. "b"
来源：http://dali.yangfankeji.com/Article/details/gtafgiuiff.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtwfibgqng.html

if x > 0 then print("正") end
来源：http://dali.xinyue.icu/Article/details/gtrookehpz.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtpxufehqg.html

string.find(s, "%d+")
来源：http://dali.tian-w.cn/Article/details/gtgkktufyv.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtniwovwax.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gttbmvwhji.html

[T41] Perl：Hello World
来源：http://dali.yj20258.top/Article/details/gtpevglnds.html

print "Hello\n";
来源：http://dali.jianghu66.top/Article/details/gtocmcvxuu.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gttrxxmdoo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqeplqgq.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtsrxoesnx.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtcemyybqd.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtxyaeoenq.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gttxhzexxs.html

[T45] Perl：数组遍历
来源：http://dali.yonumen.top/Article/details/gtucwfjknf.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtjevluwnz.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtmkhlwool.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gtpwdmmyhb.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gtljlbbleb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdxrkplcp.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtpffvfrcm.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gtekymnleq.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtziimcdfa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtqskpmgpg.html

[T50] Perl：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gttaxzxhph.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtihiyewrx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtajkujvrh.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtaqsyuecs.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtiufxxxku.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtdanitlem.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtflzovpua.html

[T53] Scala：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtmjmklzpx.html

s"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtjagyjvax.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gtgbtgrnlz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtkulmafua.html

[T55] Scala：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtuznyihfc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gtyaksqznh.html

[T56] Scala：样例类
来源：http://dali.tian-w.cn/Article/details/gtxdihnjcy.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gttvxsnqgg.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtifsfaaga.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtmjdiwfjh.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtujghkecy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.9152youxi.cn/Article/details/gtxwnkucva.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtxddyvahn.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtvoutpmoo.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtxnrhysqo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gteousznoy.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtbxscwume.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shuidangran.top/Article/details/gtjisgkbhj.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxlgpsqjb.html

[U01] Py：创建虚拟环境
来源：http://dali.jiagoushi.top/Article/details/gtogjxpovi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtwwojbwke.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtaovbtvjx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtsdbwvzpl.html

[U03] Py：加载 .env 配置
来源：http://dali.316326.xyz/Article/details/gtquiqlkbt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtuedjotkb.html

[U04] Py：变量调试打印
来源：http://dali.pengpengdd.cyou/Article/details/gtdizsfmyj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehdvhijb.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gtitoeetmt.html

list(dict.fromkeys(arr))
来源：http://dali.dianchejie.cn/Article/details/gtbvqhojot.html

[U06] Py：合并两个字典
来源：http://dali.xinyue.icu/Article/details/gtvtdpvcao.html

{**a, **b}
来源：http://dali.andypj.xyz/Article/details/gtiuocumeq.html

[U07] Py：反转字典键值
来源：http://dali.fengsongda.top/Article/details/gtxlxuqngc.html

{v: k for k, v in d.items()}
来源：http://dali.yangfankeji.com/Article/details/gtmckncssh.html

[U08] Py：展平二维列表
来源：http://dali.fzhhl.top/Article/details/gtsytazqvj.html

[y for x in nested for y in x]
来源：http://dali.yangfankeji.com/Article/details/gtxzlfznms.html

[U09] Py：字典取最大值的键
来源：http://dali.tian-w.cn/Article/details/gtieuibgvo.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gteavqoeec.html

[U10] Py：按值排序字典
来源：http://dali.tanke756.top/Article/details/gtajxzilwq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.bjfxy.top/Article/details/gtciqkrozz.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gtsxuvsqlb.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtfjndnwzn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.snrcjt.cn/Article/details/gtyxdzcqev.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gtvkdgtvao.html

[U13] Py：固定长度队列
来源：http://dali.ivvv.top/Article/details/gtxxwehpur.html

deque(maxlen=10)
来源：http://dali.yuxming.cn/Article/details/gtrphzuijv.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtzmvafrdm.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtujsfmfio.html

[U15] Py：高精度计时
来源：http://dali.yuxming.cn/Article/details/gtaxfheycv.html

t = time.perf_counter()
来源：http://dali.bjfxy.top/Article/details/gtobcmmvcl.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtdxbrskuz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.fzhhl.top/Article/details/gtqdcziapr.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtzaztwkkm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.gzhubu.top/Article/details/gtsjcjfwmg.html

[U18] Py：预编译正则
来源：http://dali.hysaishi.cn/Article/details/gtjqkoawau.html

pat = re.compile(r"\d+")
来源：http://dali.vqdsnc.cn/Article/details/gteklwsxch.html

[U19] Py：正则替换带回调
来源：http://dali.yongpay.top/Article/details/gtjmltyykk.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yj20258.top/Article/details/gtrznxejyq.html

[U20] Py：缓存函数结果
来源：http://dali.mhx1999.top/Article/details/gtygigppxj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ydzc1.top/Article/details/gtjofxolcy.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtxinfuemv.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomnoykza.html

[U22] Py：矩阵转置
来源：http://dali.yongpay.top/Article/details/gtexyuavdv.html

list(zip(*m))
来源：http://dali.ydzc1.top/Article/details/gtpwhpgguj.html

[U23] Py：分块读取大文件
来源：http://dali.xziqi.cn/Article/details/gtcvtfuqzt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtuoioobdw.html

[U24] Py：路径操作
来源：http://dali.gotoacloud.top/Article/details/gtfjzzyuzl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hammf.cn/Article/details/gtibpwxffu.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigufen.top/Article/details/gtzbyvnrwg.html

csv.DictReader(f)
来源：http://dali.zhixingplan.top/Article/details/gtrwmwgldf.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gttalfompz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ydzc1.top/Article/details/gtbfkppzds.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gttcllhcdz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aibaodan.cn/Article/details/gtdivjzyic.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gtwxqxlxgm.html

UserId = int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtewwkdhex.html

[U29] Py：属性校验
来源：http://dali.ppjwa.cn/Article/details/gtqidkkpbs.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtlsssruss.html

[U30] Py：数据类
来源：http://dali.wangdashe.top/Article/details/gtdgkxtfsq.html

@dataclass(slots=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtkwvymxzg.html

[U31] Py：单测
来源：http://dali.gotoacloud.top/Article/details/gtccqomger.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtstljksbz.html

[U32] Py：代码格式化
来源：http://dali.yueranfly.top/Article/details/gtzysmhfue.html

ruff format . && ruff check --fix .
来源：http://dali.cdnleiting.top/Article/details/gtmvitzqnm.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gtrankygru.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ybcxt.top/Article/details/gthgwopqor.html

[U34] Py：判断编码
来源：http://dali.quarkkingdee.top/Article/details/gtldnojrtd.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gthuyfmgjd.html

[U35] Py：发送邮件
来源：http://dali.jyoumei.cn/Article/details/gtwrhzjemd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnikylcms.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gtfbbgwoom.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinqigfzy.top/Article/details/gtgtoxigym.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtoiafmmmx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdmcqxkz.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrsznhws.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtstctiqvf.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gtgleajuoh.html

sys.stdout.isatty()
来源：http://dali.ivvv.top/Article/details/gtteamwliu.html

[U40] Py：打印到标准错误
来源：http://dali.hywenlv.cn/Article/details/gtswdymxgb.html

print("err", file=sys.stderr)
来源：http://dali.gaohongyu789.top/Article/details/gtxqzqetkx.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxinkj.top/Article/details/gtojvpmzim.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gtuuyxmlco.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.shuidangran.top/Article/details/gtugakysrv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.snrcjt.cn/Article/details/gtgfvhjaog.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtmcerhfji.html

namespace App\Http;
来源：http://dali.zhijiandao.cn/Article/details/gtvlxndioo.html

[U44] PHP：开启严格类型
来源：http://dali.chenzaomai.com/Article/details/gtrnduhwxi.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtluhcwckh.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtehzyshyx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgfzy.top/Article/details/gtursnsarw.html

[U46] PHP：可空类型
来源：http://dali.shanyushiyangtech.top/Article/details/gttwcqwuwf.html

?string $name = null
来源：http://dali.0kj1m.cn/Article/details/gtrfiombxs.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtdzihhjhr.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gttzkinouw.html

[U48] PHP：纯枚举
来源：http://dali.yuxming.cn/Article/details/gtnwgyrxbo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jianghu66.top/Article/details/gtojasuedb.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtbfmqgwgb.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gtxswalmhn.html

[U50] PHP：构造器属性提升
来源：http://dali.guannengcc.top/Article/details/gtnlmfjdpy.html

public function __construct(private int $id) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtrnlalzag.html

[U51] PHP：数组解构
来源：http://dali.cucudq.cn/Article/details/gtqtlqgxdt.html

[$a, $b] = $arr;
来源：http://dali.hammf.cn/Article/details/gtwyuspezl.html

[U52] PHP：箭头函数
来源：http://dali.yvedp.cn/Article/details/gtqvhxhfyf.html

$double = fn($x) => $x * 2;
来源：http://dali.feifeiyinyue.top/Article/details/gtqsrfpuhd.html

[U53] PHP：空合并运算符
来源：http://dali.jinghuilouyu.cn/Article/details/gtthldvxhr.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtyewzcong.html

[U54] PHP：空安全调用
来源：http://dali.nanxinkj.top/Article/details/gtduesqtsu.html

$obj?->method()
来源：http://dali.quarkkingdee.top/Article/details/gtfmpumllj.html

[U55] PHP：match 表达式
来源：http://dali.gzhubu.top/Article/details/gtxyteomdy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.birdmap.top/Article/details/gtlmwsjjwz.html

[U56] PHP：命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtvuetlgxp.html

f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtkwyaiswx.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gthchviuzy.html

"值: {$a}"
来源：http://dali.jyoumei.cn/Article/details/gtumakmiij.html

[U58] PHP：数组三件套
来源：http://dali.guowangkeji.top/Article/details/gtpotmcudb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtjuoghbxc.html

[U59] PHP：自定义排序
来源：http://dali.feifeiyinyue.top/Article/details/gtnaiuuncc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.quarkkingdee.top/Article/details/gtvruukfsp.html

[U60] PHP：JSON 编解码
来源：http://dali.gzhubu.top/Article/details/gtjndlazcc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gtyxnkjcto.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtspyupdks.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnqzz.top/Article/details/gtorfvcfor.html

[U62] PHP：日期对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjyxqgds.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtidnfgugj.html

[U63] PHP：文件读写
来源：http://dali.0kj1m.cn/Article/details/gtqfnrsowf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gtwemibzkb.html

[U64] PHP：目录遍历
来源：http://dali.dashuyun.cn/Article/details/gtwkfyovxb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxwdhiuxt.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtmfwmtgwp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtwndsdupr.html

[U66] PHP：设置 Cookie
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumcapcrq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.aibaodan.cn/Article/details/gtcuiasqsl.html

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gtqyfebngm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hywenlv.cn/Article/details/gtqcayusch.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gtdwhkydlu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hysaishi.cn/Article/details/gtkontboxc.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gttvfidofh.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtkkkrcacz.html

[U70] PHP：PDO 事务
来源：http://dali.jianghu66.top/Article/details/gtssifhcit.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gtkkuvenyn.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gtppoecnhe.html

throw new RuntimeException("失败", 500);
来源：http://dali.sufxvd.cn/Article/details/gtcoomnapx.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gtalsuckbq.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtescwiypp.html

[U73] PHP：读取 ini 配置
来源：http://dali.0kj1m.cn/Article/details/gtmrabcblq.html

parse_ini_file("config.ini", true)
来源：http://dali.kuanghao11.cn/Article/details/gtnhxrbhbq.html

[U74] PHP：读取环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsnfawnz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gticvjklfn.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtkzdnlcsx.html

composer require psr/container
来源：http://dali.yongpay.top/Article/details/gtlcuskrnp.html

[U76] PHP：简单路由
来源：http://dali.mhx1999.top/Article/details/gtvjaeqblt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtenwjufjm.html

[U77] PHP：模板渲染
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwoekgqt.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtuzgghvqm.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtbnxkzcnz.html

composer require --dev phpunit/phpunit
来源：http://dali.gzhubu.top/Article/details/gtlqzmkepq.html

[U79] PHP：静态分析
来源：http://dali.zhengqikj.top/Article/details/gtmyzsjoxp.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtqipwmswh.html

[U80] PHP：代码规范修复
来源：http://dali.xuanzx.com/Article/details/gtruxkzfgc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yvedp.cn/Article/details/gtedjqqwke.html

[U81] JS：初始化项目
来源：http://dali.mhx1999.top/Article/details/gtielswbqo.html

npm init -y;  npm i express
来源：http://dali.ywan-chungtsiang.top/Article/details/gthhbclgyd.html

[U82] JS：package.json 脚本
来源：http://dali.hammf.cn/Article/details/gtuysfndxz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyftdfgtu.html

[U83] JS：ES Module 导入导出
来源：http://dali.cheryme.top/Article/details/gtmmtnjqhq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtrgmhrkyf.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllkonehm.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtdznyybjp.html

[U85] JS：可选链
来源：http://dali.kuanghao11.cn/Article/details/gtqburcqdb.html

a?.b?.c
来源：http://dali.feifeiyinyue.top/Article/details/gtaeopqyli.html

[U86] JS：空值合并
来源：http://dali.cheryme.top/Article/details/gtvqcwvixd.html

a ?? b
来源：http://dali.nanxuanxn.top/Article/details/gtukcvswrh.html

[U87] JS：解构默认值
来源：http://dali.tian-w.cn/Article/details/gtablheqxm.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jianghu66.top/Article/details/gtxzzmbqaq.html

[U88] JS：对象展开合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzbcxvtp.html

{ ...a, ...b }
来源：http://dali.pengpengdd.cyou/Article/details/gtxgllvtxe.html

[U89] JS：数组去重
来源：http://dali.cheryme.top/Article/details/gtxqenxytm.html

[...new Set(arr)]
来源：http://dali.jinyuanbaomall.cn/Article/details/gthyvduoic.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtkvponakt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzdmqqaa.html

[U91] JS：对象键值遍历
来源：http://dali.yj20258888.top/Article/details/gtqffswwkm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xuanzx.com/Article/details/gtuakhjkhe.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gthzjvhugb.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gtmspenhhf.html


<!-- 参考信息 -->