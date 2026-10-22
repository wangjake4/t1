代发 wailian999

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gthzrupqbq.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtrqeblfqj.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gthlocyyew.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtgeqwepqx.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtotyyxkhx.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtobkkwgsd.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtprwjygff.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gtpomnmvev.html

[T31] Lua：Hello World
来源：http://dali.yvedp.cn/Article/details/gtknpgrrep.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtrnvkkaur.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtwxvoctfn.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnacnvos.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtnanekhkk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtlfgzptna.html

[T34] Lua：遍历表
来源：http://dali.kuanghao11.cn/Article/details/gtluttlcqz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hammf.cn/Article/details/gtmwoewnkt.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtagsfzkba.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtykflnusx.html

[T36] Lua：函数
来源：http://dali.sysykeji.top/Article/details/gtulswyopk.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtilsrbpce.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtjqytpbqz.html

"a" .. "b"
来源：http://dali.shangyingyoupin.top/Article/details/gtaoeztrkr.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtgwxsdwhs.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtlxoesgel.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gttfwvwydd.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtvzdbyzlp.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gtihujhguf.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtwbtwlawv.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtnzheonoh.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtjywlsnny.html

[T42] Perl：变量类型
来源：http://dali.gaohongyu789.top/Article/details/gtyqczvkmg.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtkyveoudp.html

[T43] Perl：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtiwtypwgl.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtktszfscv.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtxsuuwbia.html

if ($a > 0) { print "正"; }
来源：http://dali.9152youxi.cn/Article/details/gtthoaergg.html

[T45] Perl：数组遍历
来源：http://dali.vqdsnc.cn/Article/details/gtblgafzup.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtluguxrda.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtmhgsccen.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tianlin.xyz/Article/details/gtxradagil.html

[T47] Perl：正则捕获
来源：http://dali.iojbl.cn/Article/details/gtvcbkrlia.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxueacjht.html

[T48] Perl：正则替换
来源：http://dali.feifeiyinyue.top/Article/details/gtpmxittjz.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtufqdwmgt.html

[T49] Perl：函数
来源：http://dali.smart0.xyz/Article/details/gtdevjgbdj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtwwqjxooe.html

[T50] Perl：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtegkuzwwm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtbjovimue.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtfbzreeej.html

[T51] Scala：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtlpfbhayd.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtyspqwrvo.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gthrroepub.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtcbynzhtn.html

[T53] Scala：字符串插值
来源：http://dali.birdmap.top/Article/details/gtjsuwgxny.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtogqdszmd.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gtdqoickuu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.316326.xyz/Article/details/gtgaygvoqp.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gteoakdmss.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gtbpkodelw.html

[T56] Scala：样例类
来源：http://dali.yuxming.cn/Article/details/gtflotktxk.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtmqavtend.html

[T57] Scala：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjppgspu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yanxiufei.cn/Article/details/gteopyttov.html

[T58] Scala：函数定义
来源：http://dali.sxryk.cn/Article/details/gtxiaupdev.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jlsjyb.cn/Article/details/gtwdigkzdc.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtruqakpsc.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtymssciat.html

[T60] Scala：折叠
来源：http://dali.cqqwz.cn/Article/details/gtqnlfrphx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmomljktn.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtrmvninba.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ybcxt.top/Article/details/gtkwcvfpbh.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtdvjmkqqt.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtnvtnnoax.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gtcsgcoxwv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtldjmvjvs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jyoumei.cn/Article/details/gtyfdplrub.html

[U03] Py：加载 .env 配置
来源：http://dali.jinqigufen.top/Article/details/gtcaqintfu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yanxiufei.cn/Article/details/gtgegfzqgl.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtaebkimnt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.kuanghao11.cn/Article/details/gtugxzmigm.html

[U05] Py：列表去重且保序
来源：http://dali.chenlongwang.top/Article/details/gtxlslzpvw.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtdgjnvzgy.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gttyjlremf.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtfxiqtwqb.html

[U07] Py：反转字典键值
来源：http://dali.hammf.cn/Article/details/gtvuzfiyxy.html

{v: k for k, v in d.items()}
来源：http://dali.gaohongyu789.top/Article/details/gteqeixmxb.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtxmfnzdhi.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gtdyojfmzf.html

[U09] Py：字典取最大值的键
来源：http://dali.nanxuanxn.top/Article/details/gtkssjxjts.html

max(d, key=d.get)
来源：http://dali.jinqigfzy.top/Article/details/gtafnpyjkx.html

[U10] Py：按值排序字典
来源：http://dali.chenzaomai.com/Article/details/gtcwupcrbm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtiwoxeiki.html

[U11] Py：生成器表达式
来源：http://dali.yanxiufei.cn/Article/details/gtyucxomjf.html

(x * 2 for x in arr)
来源：http://dali.gzhubu.top/Article/details/gtearoggvy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtzmfftegb.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gtsefqcdfx.html

[U13] Py：固定长度队列
来源：http://dali.hnxiangtu.top/Article/details/gttvbqpftm.html

deque(maxlen=10)
来源：http://dali.c1oappe.top/Article/details/gtzygstyxf.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkomwhwqb.html

defaultdict(list)
来源：http://dali.jinqigfzy.top/Article/details/gtwcutjdal.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gtkshdmqwb.html

t = time.perf_counter()
来源：http://dali.hnxiangtu.top/Article/details/gtzmejyrub.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtlzphnryy.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yongpay.top/Article/details/gtbomeurah.html

[U17] Py：初始化日志
来源：http://dali.nwbrower.top/Article/details/gtearldhqt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtmtkmgleu.html

[U18] Py：预编译正则
来源：http://dali.xylfe.cn/Article/details/gtjycxgcoz.html

pat = re.compile(r"\d+")
来源：http://dali.meibo888.top/Article/details/gtvzxfsjbz.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtfgpqdyzj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.chenzaomai.com/Article/details/gticqrfhnp.html

[U20] Py：缓存函数结果
来源：http://dali.iojbl.cn/Article/details/gtxbsvoxrv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gtxkaccqad.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtnnstoish.html

@contextlib.contextmanager
来源：http://dali.yonumen.top/Article/details/gtjbgzprcw.html

[U22] Py：矩阵转置
来源：http://dali.xylfe.cn/Article/details/gtdzbpwncr.html

list(zip(*m))
来源：http://dali.smart0.xyz/Article/details/gtuboetolv.html

[U23] Py：分块读取大文件
来源：http://dali.wangshuangyany.cn/Article/details/gteffosbck.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.daxiang520.top/Article/details/gtkskwsdbs.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gtccexpfwt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtummfnbsr.html

[U25] Py：CSV 按字典读
来源：http://dali.tian-w.cn/Article/details/gtmfcoflji.html

csv.DictReader(f)
来源：http://dali.cqqwz.cn/Article/details/gtwqkyeumh.html

[U26] Py：并发下载
来源：http://dali.zhixingplan.top/Article/details/gtqcjtsuoe.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gtnznnxhxz.html

[U27] Py：异步 HTTP
来源：http://dali.sweek.top/Article/details/gtyjhhhxbd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtrospavjl.html

[U28] Py：类型别名
来源：http://dali.aizwys.cn/Article/details/gtridvgsxt.html

UserId = int
来源：http://dali.pycfn.com/Article/details/gthhzgwnae.html

[U29] Py：属性校验
来源：http://dali.ehwqpu.com/Article/details/gtefubizjl.html

@property 与 @x.setter 配合
来源：http://dali.jinqigfzy.top/Article/details/gtlzqnlimx.html

[U30] Py：数据类
来源：http://dali.zhixingplan.top/Article/details/gtynglhqoi.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtviczvwco.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtpukehhml.html

python -m pytest -q
来源：http://dali.yueranfly.top/Article/details/gtvnefazbp.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gtzjxqbheh.html

ruff format . && ruff check --fix .
来源：http://dali.fzhhl.top/Article/details/gtazzjayry.html

[U33] Py：打包发布
来源：http://dali.xuetiantiany.cn/Article/details/gtuigxpleg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gtujkfvsgu.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtbnomeqig.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtfglggfpa.html

[U35] Py：发送邮件
来源：http://dali.zycfv.cn/Article/details/gtsisnntxt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuanzx.com/Article/details/gtoijibinm.html

[U36] Py：定时任务
来源：http://dali.tian-w.cn/Article/details/gtfygwtofx.html

schedule.every(10).minutes.do(job)
来源：http://dali.guowangkeji.top/Article/details/gttybxtivq.html

[U37] Py：读写 Excel
来源：http://dali.yangfankeji.com/Article/details/gteehduubx.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jqgfzy.top/Article/details/gtfasshxlt.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtmfyfdmiv.html

Path(__file__).resolve().parent
来源：http://dali.ivvv.top/Article/details/gtkulrenxj.html

[U39] Py：判断是否在交互环境
来源：http://dali.yanxiufei.cn/Article/details/gtvzyhjzhc.html

sys.stdout.isatty()
来源：http://dali.shzxlz.cn/Article/details/gtyxoewfpu.html

[U40] Py：打印到标准错误
来源：http://dali.gaohongyu789.top/Article/details/gtysithxgx.html

print("err", file=sys.stderr)
来源：http://dali.cucudq.cn/Article/details/gtecekbdcf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxuanxn.top/Article/details/gtyqhgxbsd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhoulong.xyz/Article/details/gthmmeirpx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gtvmdpnwun.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.haohaochexian.top/Article/details/gthrcujjer.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gthiixzqds.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtietmoyqu.html

[U44] PHP：开启严格类型
来源：http://dali.tian-w.cn/Article/details/gttqmfrjdl.html

declare(strict_types=1);
来源：http://dali.redwolf501.top/Article/details/gtggkqjakw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jiagoushi.top/Article/details/gtqujnzuup.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtwllopqsb.html

[U46] PHP：可空类型
来源：http://dali.iojbl.cn/Article/details/gtichkzzzn.html

?string $name = null
来源：http://dali.hammf.cn/Article/details/gtzzxvkuqg.html

[U47] PHP：联合类型
来源：http://dali.shzxlz.cn/Article/details/gtxcxhdlnz.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gtooasedaf.html

[U48] PHP：纯枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtwwthiegz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtdvmigsnu.html

[U49] PHP：只读属性
来源：http://dali.yongpay.top/Article/details/gtfabaoszh.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtndivadle.html

[U50] PHP：构造器属性提升
来源：http://dali.zhixingplan.top/Article/details/gtgagatjsk.html

public function __construct(private int $id) {}
来源：http://dali.gzhubu.top/Article/details/gtdzesgadp.html

[U51] PHP：数组解构
来源：http://dali.daria6918.cn/Article/details/gttyatdysq.html

[$a, $b] = $arr;
来源：http://dali.jinghuilouyu.cn/Article/details/gtznpjnhjp.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gtasbzeydf.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtovzdjpfn.html

[U53] PHP：空合并运算符
来源：http://dali.fengsongda.top/Article/details/gttjavmlpd.html

$v = $a ?? $b ?? "default";
来源：http://dali.andypj.xyz/Article/details/gtvmfdlgdr.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gtiascnonp.html

$obj?->method()
来源：http://dali.guowangkeji.top/Article/details/gtektnzuqj.html

[U55] PHP：match 表达式
来源：http://dali.yj202588.top/Article/details/gtqxylqemz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.gaohongyu789.top/Article/details/gtikricjgs.html

[U56] PHP：命名参数
来源：http://dali.sysykeji.top/Article/details/gtrdjhgozj.html

f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxgmtzpki.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtvzxmwrzc.html

"值: {$a}"
来源：http://dali.jqgfzy.top/Article/details/gtbfdofotf.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtgvxphx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yanxiufei.cn/Article/details/gtjluchnwf.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gthsaxisps.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhquzzcf.html

[U60] PHP：JSON 编解码
来源：http://dali.andypj.xyz/Article/details/gtavmmstpg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtayezpumu.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gtjywznunq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtxscdbace.html

[U62] PHP：日期对象
来源：http://dali.xylfe.cn/Article/details/gtxvwmcfhe.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.sxryk.cn/Article/details/gtjuzqjiom.html

[U63] PHP：文件读写
来源：http://dali.zdqjudy.top/Article/details/gtqrmklylb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ybcxt.top/Article/details/gtqlmhejlz.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtanufzkcr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangshuangyany.cn/Article/details/gtsfcicphg.html

[U65] PHP：会话
来源：http://dali.hysaishi.cn/Article/details/gtrjzykdbm.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gthcpnmypz.html

[U66] PHP：设置 Cookie
来源：http://dali.sufxvd.cn/Article/details/gtfxnbjzxa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.feifeiyinyue.top/Article/details/gtyjrgblys.html

[U67] PHP：处理文件上传
来源：http://dali.nanxinkj.top/Article/details/gtrxeytqen.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.dianchejie.cn/Article/details/gtegzvjwya.html

[U68] PHP：PDO 连接
来源：http://dali.aizwys.cn/Article/details/gturgwwurv.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tian-w.cn/Article/details/gtujejhwmw.html

[U69] PHP：PDO 预处理
来源：http://dali.sufxvd.cn/Article/details/gtejgbnuyf.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajfdaqmy.html

[U70] PHP：PDO 事务
来源：http://dali.aizwys.cn/Article/details/gtbmxbumjs.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtihvmrvbk.html

[U71] PHP：抛出异常
来源：http://dali.sxryk.cn/Article/details/gtzvjdndzs.html

throw new RuntimeException("失败", 500);
来源：http://dali.aizwys.cn/Article/details/gtpybvsibp.html

[U72] PHP：写错误日志
来源：http://dali.chenzaomai.com/Article/details/gtwkvuaoha.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yvedp.cn/Article/details/gtsdyoyzph.html

[U73] PHP：读取 ini 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtmqibmjpq.html

parse_ini_file("config.ini", true)
来源：http://dali.hnxiangtu.top/Article/details/gtgyzwkqlk.html

[U74] PHP：读取环境变量
来源：http://dali.gzhubu.top/Article/details/gtpccvgwqj.html

getenv("APP_ENV") ?: "production"
来源：http://dali.cashguo.top/Article/details/gtxrwowjjl.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gtlpqrsjfg.html

composer require psr/container
来源：http://dali.chenlongwang.top/Article/details/gtxzpamzdh.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gtnweqadzc.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xziqi.cn/Article/details/gtuekkxypy.html

[U77] PHP：模板渲染
来源：http://dali.cheryme.top/Article/details/gtmrvpkcqi.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gtfjkntysu.html

[U78] PHP：单元测试
来源：http://dali.jqgfzy.top/Article/details/gtgobhszqf.html

composer require --dev phpunit/phpunit
来源：http://dali.hammf.cn/Article/details/gtalzglbfh.html

[U79] PHP：静态分析
来源：http://dali.hammf.cn/Article/details/gtogxdwszs.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gtegodnnva.html

[U80] PHP：代码规范修复
来源：http://dali.cheryme.top/Article/details/gtuhzkmpao.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhengqikj.top/Article/details/gtefwbuvvm.html

[U81] JS：初始化项目
来源：http://dali.jiagoushi.top/Article/details/gtwrnywvpq.html

npm init -y;  npm i express
来源：http://dali.andypj.xyz/Article/details/gtaqhjegsk.html

[U82] JS：package.json 脚本
来源：http://dali.shzxlz.cn/Article/details/gtykxokajx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnnrvnrbs.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gtfqjzgobg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jianghu66.top/Article/details/gtmidqzqps.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gtefcchipu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuycioevh.html

[U85] JS：可选链
来源：http://dali.nwbrower.top/Article/details/gtwmqzsqta.html

a?.b?.c
来源：http://dali.yj202588.top/Article/details/gtnyhioryk.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtwettewas.html

a ?? b
来源：http://dali.sufxvd.cn/Article/details/gtwlcwflvr.html

[U87] JS：解构默认值
来源：http://dali.haohaochexian.top/Article/details/gtgyfaihxx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gtfqhlpvvz.html

[U88] JS：对象展开合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeboeqti.html

{ ...a, ...b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwubhcnxj.html

[U89] JS：数组去重
来源：http://dali.sysykeji.top/Article/details/gtkfhgcaun.html

[...new Set(arr)]
来源：http://dali.hnxiangtu.top/Article/details/gtjyxtkmnx.html

[U90] JS：数字数组排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtbobzyoki.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yuanzhike.top/Article/details/gtbqtqmmft.html

[U91] JS：对象键值遍历
来源：http://dali.birdmap.top/Article/details/gtqowenatc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsisilrq.html

[U92] JS：深拷贝
来源：http://dali.nanxinkj.top/Article/details/gtmvldjzpi.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtgokxyuvx.html

[U93] JS：模板字符串
来源：http://dali.yueranfly.top/Article/details/gttemzbvkg.html

`共 ${n} 条`
来源：http://dali.xinyue.icu/Article/details/gtcymbljhi.html

[U94] JS：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gteiskhxmj.html

const double = x => x * 2;
来源：http://dali.fengsongda.top/Article/details/gtcxvojylz.html

[U95] JS：Promise 包装
来源：http://dali.zhaomingkeji.xyz/Article/details/gtraeyudbl.html

new Promise((resolve, reject) => {})
来源：http://dali.tianlin.xyz/Article/details/gtfoueomzv.html

[U96] JS：async/await 与异常
来源：http://dali.jianghu66.top/Article/details/gtrqhjaymm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.aibaodan.cn/Article/details/gtntzydonu.html

[U97] JS：并发请求
来源：http://dali.jinghuilouyu.cn/Article/details/gtphmozaun.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtugbmhjog.html

[U98] JS：fetch 带 JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtbliwodne.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgufenzy.top/Article/details/gthsprqsrg.html

[U99] JS：事件监听
来源：http://dali.xinyue.icu/Article/details/gthphrxtnw.html

el.addEventListener("click", e => {})
来源：http://dali.chenjidiqi.icu/Article/details/gtvanuicwm.html

[U100] JS：DOM 查询
来源：http://dali.chenlongwang.top/Article/details/gtsisegjhk.html

document.querySelector(".item")
来源：http://dali.tian-w.cn/Article/details/gtsdocuief.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gtezilhsyr.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtfzdrowvk.html

[U102] JS：本地存储
来源：http://dali.yuxming.cn/Article/details/gtfwcvljow.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gtdyjedubn.html

[U103] JS：定时器
来源：http://dali.xylfe.cn/Article/details/gtewiylynu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.9152youxi.cn/Article/details/gtaesoingo.html

[U104] JS：防抖
来源：http://dali.feifeiyinyue.top/Article/details/gtyyiyeyif.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gtqxsftmfa.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtkbjahwvf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.xuanzx.com/Article/details/gtmhphpwhf.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtplzuqfnm.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xuanzx.com/Article/details/gtdnorcvyl.html

[U107] JS：数字千分位
来源：http://dali.yangfankeji.com/Article/details/gtitojbzfn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtqaoktpgt.html

[U108] JS：随机整数
来源：http://dali.iojbl.cn/Article/details/gtvhwibwyw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.chenjidiqi.icu/Article/details/gttyrxmjge.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gtetkexenr.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jqgfzy.top/Article/details/gtxvnuirnf.html

[U110] JS：数组分块
来源：http://dali.wangdashe.top/Article/details/gtbgzjydny.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgfzy.top/Article/details/gtpaiqgvur.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gtfsnwaxpd.html

new Map(Object.entries(obj))
来源：http://dali.ybcxt.top/Article/details/gteangivcu.html

[U112] JS：字符串补位
来源：http://dali.svipenyu.cn/Article/details/gtcorqebxs.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gtavxnmjak.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gtiicjxzoz.html

s.replaceAll("a", "b")
来源：http://dali.redwolf501.top/Article/details/gtvmdcvakf.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gtgnzrbdbt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gtvmnjokvz.html


<!-- 参考信息 -->