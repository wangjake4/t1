代发 wailian999

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtxwjzassm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zycfv.cn/Article/details/gtkhrpajfj.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtqhinltlg.html

function add(a, b) return a + b end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwukablt.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtsvtmutlp.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtrqulcfga.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtcuhhbfcp.html

if x > 0 then print("正") end
来源：http://dali.sufxvd.cn/Article/details/gtozxapnpt.html

[T39] Lua：模式匹配
来源：http://dali.316326.xyz/Article/details/gthpicxmte.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtswdrcelx.html

[T40] Lua：元表
来源：http://dali.nanxuanxn.top/Article/details/gtbtbzknmu.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gtmqvaupgv.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqwumvmrk.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gtkxrhmdfi.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gtqrmbhfju.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtnltlxbjq.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtbkupiukr.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gtrdmykdcs.html

[T44] Perl：条件
来源：http://dali.0kj1m.cn/Article/details/gtmemsirks.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtgwutrjde.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gtpzwzmvgs.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gtzyznnwhy.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gtzpolhsph.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.bjfxy.top/Article/details/gtawekinsz.html

[T47] Perl：正则捕获
来源：http://dali.zdqjudy.top/Article/details/gtoleshoqc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nanxinkj.top/Article/details/gtascjvzll.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtxjwcrdjo.html

$s =~ s/old/new/g;
来源：http://dali.vqdsnc.cn/Article/details/gtoqqaftlf.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtswduxfuf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfqomltcn.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtkcxqgymj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtorpmmsrv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tianlin.xyz/Article/details/gtvsrocpah.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtuiauthxg.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtebwtcxzf.html

[T52] Scala：变量
来源：http://dali.haohaochexian.top/Article/details/gttoiasihv.html

val a = 1;  var b = 2
来源：http://dali.tianlin.xyz/Article/details/gtegkektzu.html

[T53] Scala：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gtrupnbdns.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtsuktrtbe.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gtsofvjryj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.fengsongda.top/Article/details/gtqhgbohrm.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtbotxjuxm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gtsjylkbcu.html

[T56] Scala：样例类
来源：http://dali.xuetiantiany.cn/Article/details/gtjnmuwgwb.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtsfziyrsr.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtjymdgpfh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cqqwz.cn/Article/details/gtlxtwbfll.html

[T58] Scala：函数定义
来源：http://dali.hysaishi.cn/Article/details/gtkjnnyyfx.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jqgufenzy.top/Article/details/gtrapsoyoa.html

[T59] Scala：循环
来源：http://dali.ydzc1.top/Article/details/gtpmpptxpt.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtvdnxiwym.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtwvicvphg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtotgpylmu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtrlejubcp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hysaishi.cn/Article/details/gtadqpugau.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtzzwqiits.html

[U01] Py：创建虚拟环境
来源：http://dali.redwolf501.top/Article/details/gtjbtdhulh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dashuyun.cn/Article/details/gtssitnplv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsggfmybl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtohgfayet.html

[U03] Py：加载 .env 配置
来源：http://dali.sxryk.cn/Article/details/gttpbudvyl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmxppreu.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gtqyguktuj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.dashuyun.cn/Article/details/gtekqqnybt.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gttmtwblmt.html

list(dict.fromkeys(arr))
来源：http://dali.sxryk.cn/Article/details/gtogslhpow.html

[U06] Py：合并两个字典
来源：http://dali.zhoulong.xyz/Article/details/gtcvpbyxeo.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtwuetrwvy.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtxcxtcftp.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gtikpnimgr.html

[U08] Py：展平二维列表
来源：http://dali.jlsjyb.cn/Article/details/gtawsfgtjs.html

[y for x in nested for y in x]
来源：http://dali.ybcxt.top/Article/details/gtkbehvmep.html

[U09] Py：字典取最大值的键
来源：http://dali.redwolf501.top/Article/details/gtaavpgmtq.html

max(d, key=d.get)
来源：http://dali.zhijiandao.cn/Article/details/gttsshwpam.html

[U10] Py：按值排序字典
来源：http://dali.jqgfzy.top/Article/details/gttmlenojp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yanxiufei.cn/Article/details/gtcouutptu.html

[U11] Py：生成器表达式
来源：http://dali.c1oappe.top/Article/details/gtlrzxaxsc.html

(x * 2 for x in arr)
来源：http://dali.cdnleiting.top/Article/details/gtzdjmogeu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxbfqpjn.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gtrtudhura.html

[U13] Py：固定长度队列
来源：http://dali.zycfv.cn/Article/details/gtgxqirtwt.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtokdhtkwd.html

[U14] Py：分组收集到列表
来源：http://dali.zhoulong.xyz/Article/details/gtfwwateaz.html

defaultdict(list)
来源：http://dali.jlsjyb.cn/Article/details/gtbxamyfbu.html

[U15] Py：高精度计时
来源：http://dali.gzhubu.top/Article/details/gtjkiyfpdz.html

t = time.perf_counter()
来源：http://dali.dashuyun.cn/Article/details/gttxdeqire.html

[U16] Py：命令行参数解析
来源：http://dali.sxryk.cn/Article/details/gtenayvrqh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ydzc1.top/Article/details/gtutwdnoyy.html

[U17] Py：初始化日志
来源：http://dali.xinyue.icu/Article/details/gtagtvzqrm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guowangkeji.top/Article/details/gtzxlsixir.html

[U18] Py：预编译正则
来源：http://dali.zycfv.cn/Article/details/gtvhjaygyd.html

pat = re.compile(r"\d+")
来源：http://dali.0kj1m.cn/Article/details/gtqlvfapzr.html

[U19] Py：正则替换带回调
来源：http://dali.chenlongwang.top/Article/details/gteavdrqzz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtythyjxro.html

[U20] Py：缓存函数结果
来源：http://dali.dashuyun.cn/Article/details/gtkzbochwq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gtuxxzwxkd.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhixingplan.top/Article/details/gtfrcoqzmm.html

@contextlib.contextmanager
来源：http://dali.gzhubu.top/Article/details/gtbzsupkvf.html

[U22] Py：矩阵转置
来源：http://dali.gotoacloud.top/Article/details/gthymjkinm.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gtvhimbsxh.html

[U23] Py：分块读取大文件
来源：http://dali.yangfankeji.com/Article/details/gtbkiahtqo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyksjbgqq.html

[U24] Py：路径操作
来源：http://dali.pycfn.com/Article/details/gtqksgxlxp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxinkj.top/Article/details/gtolbxhlli.html

[U25] Py：CSV 按字典读
来源：http://dali.shuidangran.top/Article/details/gtkeyyscll.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gthqrikbju.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtxvozlrwy.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gtncjtvfbx.html

[U27] Py：异步 HTTP
来源：http://dali.sufxvd.cn/Article/details/gtkowgecmm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtwiajqimg.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gtdfhjlyfr.html

UserId = int
来源：http://dali.ydzc1.top/Article/details/gtadfpzmgy.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtwmogbyfl.html

@property 与 @x.setter 配合
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdqilhop.html

[U30] Py：数据类
来源：http://dali.nanxinkj.top/Article/details/gtfvdgawvh.html

@dataclass(slots=True)
来源：http://dali.tianlin.xyz/Article/details/gtewyguefu.html

[U31] Py：单测
来源：http://dali.sxryk.cn/Article/details/gtyuypcfhq.html

python -m pytest -q
来源：http://dali.feifeiyinyue.top/Article/details/gtomzddrif.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtebzersrg.html

ruff format . && ruff check --fix .
来源：http://dali.guannengcc.top/Article/details/gtcrloavui.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gthdxwfeuo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.bjfxy.top/Article/details/gtkbwtpfsn.html

[U34] Py：判断编码
来源：http://dali.mhx1999.top/Article/details/gtngkwxcbp.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtyqktjmry.html

[U35] Py：发送邮件
来源：http://dali.guannengcc.top/Article/details/gtjiwlarkd.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.daxiang520.top/Article/details/gtycavrofh.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gtrvptwqmg.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuetiantiany.cn/Article/details/gtxkvitaea.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gtnupahkya.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yueranfly.top/Article/details/gtxlramcel.html

[U38] Py：获取脚本所在目录
来源：http://dali.vqdsnc.cn/Article/details/gtovofewaa.html

Path(__file__).resolve().parent
来源：http://dali.guannengcc.top/Article/details/gttexrttla.html

[U39] Py：判断是否在交互环境
来源：http://dali.ppjwa.cn/Article/details/gtsqijobgi.html

sys.stdout.isatty()
来源：http://dali.tian-w.cn/Article/details/gtbzcgyzod.html

[U40] Py：打印到标准错误
来源：http://dali.ydzc1.top/Article/details/gtiwkcbrvi.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtafjaioiw.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnxiangtu.top/Article/details/gttxjiyisg.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangtech.top/Article/details/gtoimrnqcb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gtzmsblhus.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.daria6918.cn/Article/details/gtelglhqnf.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gtefjjrixc.html

namespace App\Http;
来源：http://dali.mhx1999.top/Article/details/gtfhmaknrj.html

[U44] PHP：开启严格类型
来源：http://dali.yvedp.cn/Article/details/gtnbnybfzm.html

declare(strict_types=1);
来源：http://dali.yj202588.top/Article/details/gtnsiruzps.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hysaishi.cn/Article/details/gtrhdqabrl.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtjdiolbvq.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gtjouygfbg.html

?string $name = null
来源：http://dali.ehwqpu.com/Article/details/gtpewhrrak.html

[U47] PHP：联合类型
来源：http://dali.redwolf501.top/Article/details/gtxoqfmkvo.html

int|string $id
来源：http://dali.haohaochexian.top/Article/details/gtkwdbjkas.html

[U48] PHP：纯枚举
来源：http://dali.jqgufenzy.top/Article/details/gtstenbuxs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrrhsifon.html

[U49] PHP：只读属性
来源：http://dali.jinqigfzy.top/Article/details/gtjhvymgog.html

public readonly string $name
来源：http://dali.zycfv.cn/Article/details/gtrcqswttz.html

[U50] PHP：构造器属性提升
来源：http://dali.ehwqpu.com/Article/details/gtwjqcqdif.html

public function __construct(private int $id) {}
来源：http://dali.316326.xyz/Article/details/gtxomaerng.html

[U51] PHP：数组解构
来源：http://dali.iojbl.cn/Article/details/gtfsdshhvl.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gttchvxpog.html

[U52] PHP：箭头函数
来源：http://dali.fzhhl.top/Article/details/gtjijokelu.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtexzzyqgr.html

[U53] PHP：空合并运算符
来源：http://dali.hammf.cn/Article/details/gtdafogsff.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtajioolsj.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gtfplgfxui.html

$obj?->method()
来源：http://dali.dianchejie.cn/Article/details/gtcqcouspf.html

[U55] PHP：match 表达式
来源：http://dali.0kj1m.cn/Article/details/gtpiuqkxhr.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtzcwwbunw.html

[U56] PHP：命名参数
来源：http://dali.gotoacloud.top/Article/details/gtweneafhs.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtyvqmgmcu.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtggbzkzyc.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gttbudeoxp.html

[U58] PHP：数组三件套
来源：http://dali.yongpay.top/Article/details/gtimymdybd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.guowangkeji.top/Article/details/gtsfrtxjqh.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gtyfqsokor.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pycfn.com/Article/details/gtakjpvaug.html

[U60] PHP：JSON 编解码
来源：http://dali.316326.xyz/Article/details/gtcfezyrgn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tian-w.cn/Article/details/gtrzwajmdk.html

[U61] PHP：正则
来源：http://dali.yj20258.top/Article/details/gtakdaahry.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nanxinkj.top/Article/details/gtedksdfnk.html

[U62] PHP：日期对象
来源：http://dali.feifeiyinyue.top/Article/details/gtufyvovlq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.havefunace.top/Article/details/gtghvnlsaq.html

[U63] PHP：文件读写
来源：http://dali.cqqwz.cn/Article/details/gtdgbfmxlk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhiwuduotai.top/Article/details/gtjlpyuazq.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gtjerpgasa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.wangdashe.top/Article/details/gthkbfnvkc.html

[U65] PHP：会话
来源：http://dali.daria6918.cn/Article/details/gtyyjxazfx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cheryme.top/Article/details/gtwyxhlhtl.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gtupdqbxls.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpvsnvvdq.html

[U67] PHP：处理文件上传
来源：http://dali.yongpay.top/Article/details/gtncefamce.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ydzc1.top/Article/details/gtqcpwcwds.html

[U68] PHP：PDO 连接
来源：http://dali.gzhubu.top/Article/details/gtdrujehsf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtsresysof.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtecsntbzp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yj20258.top/Article/details/gtetvbstrj.html

[U70] PHP：PDO 事务
来源：http://dali.gaohongyu789.top/Article/details/gtdmylloai.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.iojbl.cn/Article/details/gtlbzydgzi.html

[U71] PHP：抛出异常
来源：http://dali.cheryme.top/Article/details/gtayxxtdyo.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtdkgwobvb.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gtqmsllwyn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtsramqwbm.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtjueqaytd.html

parse_ini_file("config.ini", true)
来源：http://dali.yj20258.top/Article/details/gtxwkvxvvd.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtyudvfium.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenjidiqi.icu/Article/details/gtdlaieber.html

[U75] PHP：依赖注入
来源：http://dali.xuanzx.com/Article/details/gtllpistwb.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtdsubefom.html

[U76] PHP：简单路由
来源：http://dali.cashguo.top/Article/details/gtdkytethf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.sufxvd.cn/Article/details/gtjkfhzhok.html

[U77] PHP：模板渲染
来源：http://dali.gaohongyu789.top/Article/details/gtzuotzexa.html

composer require twig/twig
来源：http://dali.ppjwa.cn/Article/details/gtttycapyc.html

[U78] PHP：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gtcdzokgup.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gteijywogs.html

[U79] PHP：静态分析
来源：http://dali.yj202588.top/Article/details/gtvjmjyxbm.html

composer require --dev phpstan/phpstan
来源：http://dali.yangfankeji.com/Article/details/gthltwkwxc.html

[U80] PHP：代码规范修复
来源：http://dali.xinyue.icu/Article/details/gtnbybctow.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hongshengwenyu.top/Article/details/gtvzlytjfk.html

[U81] JS：初始化项目
来源：http://dali.jlsjyb.cn/Article/details/gtcfxwsmkc.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gtkgfciyju.html

[U82] JS：package.json 脚本
来源：http://dali.sufxvd.cn/Article/details/gtvzmwvief.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cdnleiting.top/Article/details/gtkorhywtd.html

[U83] JS：ES Module 导入导出
来源：http://dali.ivvv.top/Article/details/gtbbtzvsku.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtzbqzmtxw.html

[U84] JS：CommonJS 写法
来源：http://dali.wangshuangyany.cn/Article/details/gtlkujgdnd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hnxiangtu.top/Article/details/gtaqgjymzp.html

[U85] JS：可选链
来源：http://dali.tianlin.xyz/Article/details/gtmscgfvei.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtidlzjicx.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gtsrmyjegl.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gtiedkysqb.html

[U87] JS：解构默认值
来源：http://dali.yj20258.top/Article/details/gtdjibyxxr.html

const { a = 1, b = 2 } = obj;
来源：http://dali.0kj1m.cn/Article/details/gtkgyprvbk.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gtkrpqlhan.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gtyjqbbjgf.html

[U89] JS：数组去重
来源：http://dali.bjfxy.top/Article/details/gtzvgpolzj.html

[...new Set(arr)]
来源：http://dali.xuanzx.com/Article/details/gtbgkwbpfi.html

[U90] JS：数字数组排序
来源：http://dali.yongpay.top/Article/details/gtpuzzaeyq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gthqwnmqcu.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtzraveqbi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.316326.xyz/Article/details/gtqtjrkjwt.html

[U92] JS：深拷贝
来源：http://dali.tanke756.top/Article/details/gtqpotymtm.html

structuredClone(obj)
来源：http://dali.hammf.cn/Article/details/gtfrtqhaqx.html

[U93] JS：模板字符串
来源：http://dali.wangdashe.top/Article/details/gtiprfqxne.html

`共 ${n} 条`
来源：http://dali.guannengcc.top/Article/details/gtgbprtoir.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtyvdjwwwp.html

const double = x => x * 2;
来源：http://dali.tianlin.xyz/Article/details/gteokjuxsu.html

[U95] JS：Promise 包装
来源：http://dali.ppjwa.cn/Article/details/gtwkbjnobg.html

new Promise((resolve, reject) => {})
来源：http://dali.yonumen.top/Article/details/gtefnfmmkc.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtwwziazek.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtkmtqhmff.html

[U97] JS：并发请求
来源：http://dali.gogol.net.cn/Article/details/gtwjrqmdqd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtugyvfekx.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtinzzemlo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gtueghnqof.html

[U99] JS：事件监听
来源：http://dali.yangfankeji.com/Article/details/gtphodupox.html

el.addEventListener("click", e => {})
来源：http://dali.jlsjyb.cn/Article/details/gtwscxldxr.html

[U100] JS：DOM 查询
来源：http://dali.hfpthk.cn/Article/details/gtaigjojhf.html

document.querySelector(".item")
来源：http://dali.zhaomingkeji.xyz/Article/details/gteajcdqkt.html

[U101] JS：classList 操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwskfsfst.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gtdujxhndw.html

[U102] JS：本地存储
来源：http://dali.ehwqpu.com/Article/details/gtqajfxkuc.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.guowangkeji.top/Article/details/gtgmypgcul.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtqnplnuov.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yanxiufei.cn/Article/details/gtndhvxfpo.html

[U104] JS：防抖
来源：http://dali.yj20258.top/Article/details/gtdxwibxvj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gterfmoeeh.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgunzxmz.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtomzwyyvc.html

[U106] JS：日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtrevwtqaa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigufen.top/Article/details/gtwpswnlxs.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtkxddslxn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.snrcjt.cn/Article/details/gtgbzkoqyw.html

[U108] JS：随机整数
来源：http://dali.haohaochexian.top/Article/details/gtsebqhtft.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.sysykeji.top/Article/details/gtsritljji.html

[U109] JS：数组分组
来源：http://dali.aizwys.cn/Article/details/gtsgletcyi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tian-w.cn/Article/details/gtrwthzvpg.html

[U110] JS：数组分块
来源：http://dali.jiagoushi.top/Article/details/gtgsoylbsh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gtzjqjrzai.html

[U111] JS：对象转 Map
来源：http://dali.yj202588.top/Article/details/gtnwptbvsv.html

new Map(Object.entries(obj))
来源：http://dali.jiagoushi.top/Article/details/gttsoyupkf.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gtgdwiaczq.html

"7".padStart(3, "0")
来源：http://dali.ehwqpu.com/Article/details/gthtsnwzjw.html

[U113] JS：正则替换全部
来源：http://dali.jianghu66.top/Article/details/gtpiupkirl.html

s.replaceAll("a", "b")
来源：http://dali.sysykeji.top/Article/details/gtwneffapy.html

[U114] JS：JSON 深比较
来源：http://dali.chenzaomai.com/Article/details/gtntyjlbrf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.sweek.top/Article/details/gtnnraegzy.html

[U115] JS：生成 UUID
来源：http://dali.chenlongwang.top/Article/details/gtrhftmtgr.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuavvvvzs.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtlarnckmy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinqigfzy.top/Article/details/gtqrmfjqbn.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtzflojxmo.html

npm i -D vitest;  npx vitest
来源：http://dali.jinqigufen.top/Article/details/gtdqthtzii.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gtqjjyvztf.html

npm i -D vite;  npx vite
来源：http://dali.yangfankeji.com/Article/details/gtibuohnow.html

[U119] JS：生产构建
来源：http://dali.jlsjyb.cn/Article/details/gtfxryqknt.html

npx vite build
来源：http://dali.cucudq.cn/Article/details/gtrualyjcl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtrqbjqtjt.html

import.meta.env.VITE_API_URL
来源：http://dali.feifeiyinyue.top/Article/details/gtxsvuybsq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtrroojuyw.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gtpvqysael.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gttynjowmd.html

按语言统计（条）：
来源：http://dali.quarkkingdee.top/Article/details/gtekzwygxu.html


<!-- 参考信息 -->