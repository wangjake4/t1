代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.fzhhl.top/Article/details/gtzehkgjfb.html

for my $x (@arr) { print $x; }
来源：http://dali.jianghu66.top/Article/details/gtjxffrbfq.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtbkaukprv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtdyhdmhdq.html

[T47] Perl：正则捕获
来源：http://dali.xziqi.cn/Article/details/gtwdholpjb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlgkjfcal.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtzwpactva.html

$s =~ s/old/new/g;
来源：http://dali.wangdashe.top/Article/details/gtldwndqoe.html

[T49] Perl：函数
来源：http://dali.0kj1m.cn/Article/details/gtiublywfz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtuorwgkjr.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtdgcqlbzc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.c1oappe.top/Article/details/gtvrkqhnxe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.andypj.xyz/Article/details/gtpzwlituz.html

[T51] Scala：Hello World
来源：http://dali.cashguo.top/Article/details/gtamznpzph.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gthoiksboa.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtymfwknny.html

val a = 1;  var b = 2
来源：http://dali.aizwys.cn/Article/details/gtcuushxzn.html

[T53] Scala：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtgoevcnib.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtmcqtvinf.html

[T54] Scala：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyepmmbcd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtykpdimtq.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtghlnbkbd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cqqwz.cn/Article/details/gtpoomuezt.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gtjybrfysq.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gthsvrbgoa.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtrqzrnflt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtbkzcqess.html

[T58] Scala：函数定义
来源：http://dali.chenlongwang.top/Article/details/gtckonxoit.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yueranfly.top/Article/details/gtgsfgnijc.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtvlzfmdqx.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryjejdpb.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtvnfvcbit.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.quarkkingdee.top/Article/details/gthujlrliw.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtlhkjawyc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gzhubu.top/Article/details/gttxgtcgzm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmzuutsfh.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtiianbaqn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.redwolf501.top/Article/details/gtqjcnfwbe.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gtwfpfmhlc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gteplggzgv.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtjimnnrjr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtapmkzcul.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtshgvhzyo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ybcxt.top/Article/details/gtjhmvmpmq.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtvnlskzoi.html

list(dict.fromkeys(arr))
来源：http://dali.jinqigfzy.top/Article/details/gtdrybapxi.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtcdtwvkgf.html

{**a, **b}
来源：http://dali.zhaomingkeji.xyz/Article/details/gthixqlcxj.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtndirxgot.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gtteesabqo.html

[U08] Py：展平二维列表
来源：http://dali.havefunace.top/Article/details/gtefdphpak.html

[y for x in nested for y in x]
来源：http://dali.tian-w.cn/Article/details/gtqmnnntco.html

[U09] Py：字典取最大值的键
来源：http://dali.nwbrower.top/Article/details/gtorzjnxjh.html

max(d, key=d.get)
来源：http://dali.yongpay.top/Article/details/gtqyqtlqfd.html

[U10] Py：按值排序字典
来源：http://dali.9152youxi.cn/Article/details/gtnhmkoaph.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtywnbfrra.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtkrojrhbs.html

(x * 2 for x in arr)
来源：http://dali.hywenlv.cn/Article/details/gtrkbsmpnk.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gaohongyu789.top/Article/details/gtrvzyoblv.html

Counter(arr).most_common(3)
来源：http://dali.hnxiangtu.top/Article/details/gthrvnwgsg.html

[U13] Py：固定长度队列
来源：http://dali.cheryme.top/Article/details/gtjbjyzdmj.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocjazvpe.html

[U14] Py：分组收集到列表
来源：http://dali.yj20258888.top/Article/details/gtmghjzlmv.html

defaultdict(list)
来源：http://dali.nwbrower.top/Article/details/gtwemqehil.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtjuzriwxx.html

t = time.perf_counter()
来源：http://dali.jyoumei.cn/Article/details/gtifyhdolx.html

[U16] Py：命令行参数解析
来源：http://dali.pycfn.com/Article/details/gtwkfvdzgd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yangfankeji.com/Article/details/gtejkainqh.html

[U17] Py：初始化日志
来源：http://dali.ydzc1.top/Article/details/gtgohhduta.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jlsjyb.cn/Article/details/gtifmmuzsy.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtyhgghevo.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gtxqnlnmph.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtvrotvbrw.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtficeikue.html

[U20] Py：缓存函数结果
来源：http://dali.zhijiandao.cn/Article/details/gtinpwsohu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhijiandao.cn/Article/details/gtepwihfbn.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxhcxrjjy.html

@contextlib.contextmanager
来源：http://dali.smart0.xyz/Article/details/gtdpmdzmoh.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gtueynyicz.html

list(zip(*m))
来源：http://dali.xinyue.icu/Article/details/gtigwrhqym.html

[U23] Py：分块读取大文件
来源：http://dali.jiagoushi.top/Article/details/gtjjvwxtbr.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.pengpengdd.cyou/Article/details/gtcbiocess.html

[U24] Py：路径操作
来源：http://dali.shangyingyoupin.top/Article/details/gtmzcqggdm.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gtnoajpkvl.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtuqcpinwp.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtyrtfodxt.html

[U26] Py：并发下载
来源：http://dali.pycfn.com/Article/details/gtvcedmggz.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtchewiivh.html

[U27] Py：异步 HTTP
来源：http://dali.xuetiantiany.cn/Article/details/gtqhuvhcum.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xziqi.cn/Article/details/gtvgbocvwj.html

[U28] Py：类型别名
来源：http://dali.andypj.xyz/Article/details/gtxkezdyqe.html

UserId = int
来源：http://dali.aizwys.cn/Article/details/gtsnarifnq.html

[U29] Py：属性校验
来源：http://dali.zdqjudy.top/Article/details/gtdqyffwaq.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtjuigygyi.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtzuyaauqw.html

@dataclass(slots=True)
来源：http://dali.shuidangran.top/Article/details/gtisqgkvsm.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gtfhsrlcdm.html

python -m pytest -q
来源：http://dali.daxiang520.top/Article/details/gtbpjuldsg.html

[U32] Py：代码格式化
来源：http://dali.fengsongda.top/Article/details/gtltnumkgn.html

ruff format . && ruff check --fix .
来源：http://dali.zycfv.cn/Article/details/gtngvessko.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtuajfazjh.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuetiantiany.cn/Article/details/gthpbhkbff.html

[U34] Py：判断编码
来源：http://dali.zhoulong.xyz/Article/details/gtjnhfhgok.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtggtnpkyp.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtznfryjwf.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.bjfxy.top/Article/details/gtnmbzjrye.html

[U36] Py：定时任务
来源：http://dali.cheryme.top/Article/details/gtblhqtybv.html

schedule.every(10).minutes.do(job)
来源：http://dali.aizwys.cn/Article/details/gtlofhpyxe.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gtvdwfmkdt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.andypj.xyz/Article/details/gtiweflrlo.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuszddayy.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gtzyzqyhen.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtbuamgkjo.html

sys.stdout.isatty()
来源：http://dali.havefunace.top/Article/details/gtibvtejbg.html

[U40] Py：打印到标准错误
来源：http://dali.guowangkeji.top/Article/details/gtwyzpcqrt.html

print("err", file=sys.stderr)
来源：http://dali.zhixingplan.top/Article/details/gtrjutmgje.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtridhxbnc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtsjubrhkb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.fzhhl.top/Article/details/gtsczurmnk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.9152youxi.cn/Article/details/gtnavplnec.html

[U43] PHP：声明命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gttchgmxqh.html

namespace App\Http;
来源：http://dali.smart0.xyz/Article/details/gthyisjvxk.html

[U44] PHP：开启严格类型
来源：http://dali.haohaochexian.top/Article/details/gtwclsdmsz.html

declare(strict_types=1);
来源：http://dali.bjfxy.top/Article/details/gtcsvtycku.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tanke756.top/Article/details/gtzgucuada.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtasxxijep.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtyhsxiway.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gtgrmnzvxf.html

[U47] PHP：联合类型
来源：http://dali.nwbrower.top/Article/details/gtuthpmhnr.html

int|string $id
来源：http://dali.daria6918.cn/Article/details/gtagetyntk.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsgxeuoa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.wangdashe.top/Article/details/gtviwbwjpm.html

[U49] PHP：只读属性
来源：http://dali.ivvv.top/Article/details/gtlhbyqnyk.html

public readonly string $name
来源：http://dali.zhengqikj.top/Article/details/gteremvcsr.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtivklqlrz.html

public function __construct(private int $id) {}
来源：http://dali.aizwys.cn/Article/details/gtkqlwhgfp.html

[U51] PHP：数组解构
来源：http://dali.andypj.xyz/Article/details/gtptpsqbtx.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtgmvwhihw.html

[U52] PHP：箭头函数
来源：http://dali.hywenlv.cn/Article/details/gtfuumzlob.html

$double = fn($x) => $x * 2;
来源：http://dali.chenzaomai.com/Article/details/gtsivfbdal.html

[U53] PHP：空合并运算符
来源：http://dali.havefunace.top/Article/details/gtagtdzylf.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj202588.top/Article/details/gtnyfibnqi.html

[U54] PHP：空安全调用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxtgsaqym.html

$obj?->method()
来源：http://dali.jiagoushi.top/Article/details/gtwwnigjrb.html

[U55] PHP：match 表达式
来源：http://dali.gogol.net.cn/Article/details/gtqzemlrrj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yonumen.top/Article/details/gttmopfpsz.html

[U56] PHP：命名参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncmnmuyh.html

f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gthqsnzaze.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtvyorgaur.html

"值: {$a}"
来源：http://dali.kuanghao11.cn/Article/details/gtcfzezrmx.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gtezfoesfg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtveqqrwrc.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtmopqqhzh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtjspyhydx.html

[U60] PHP：JSON 编解码
来源：http://dali.0kj1m.cn/Article/details/gtqdeljzts.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.fengsongda.top/Article/details/gtmpveeggo.html

[U61] PHP：正则
来源：http://dali.yvedp.cn/Article/details/gtchxnfnxs.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hysaishi.cn/Article/details/gtnezwybla.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gtuulasqen.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gtacglemod.html

[U63] PHP：文件读写
来源：http://dali.zycfv.cn/Article/details/gtsmzkdqph.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tianlin.xyz/Article/details/gtvsyjeqkx.html

[U64] PHP：目录遍历
来源：http://dali.jqgfzy.top/Article/details/gtkocusjoa.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtdykkrzpl.html

[U65] PHP：会话
来源：http://dali.hammf.cn/Article/details/gtetjfacbr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtbgqmypki.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gtwamtmfdp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtsjjigrdw.html

[U67] PHP：处理文件上传
来源：http://dali.fengsongda.top/Article/details/gtpkgeodgk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzrpatti.html

[U68] PHP：PDO 连接
来源：http://dali.yvedp.cn/Article/details/gtjewkvktr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhengqikj.top/Article/details/gtvnmtrqps.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gtaidrkvix.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.guannengcc.top/Article/details/gtlqiotnqx.html

[U70] PHP：PDO 事务
来源：http://dali.yuanzhike.top/Article/details/gtzrgejsnn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtmaiwlokv.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtcdddnbos.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtsuuwifzj.html

[U72] PHP：写错误日志
来源：http://dali.jyoumei.cn/Article/details/gtgfiwwper.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtziqtbpwi.html

[U73] PHP：读取 ini 配置
来源：http://dali.c1oappe.top/Article/details/gtykxcgstn.html

parse_ini_file("config.ini", true)
来源：http://dali.sufxvd.cn/Article/details/gtoljzwwkn.html

[U74] PHP：读取环境变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtozrtyogo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.kuanghao11.cn/Article/details/gtalztuwds.html

[U75] PHP：依赖注入
来源：http://dali.jqgufenzy.top/Article/details/gtvujxnweb.html

composer require psr/container
来源：http://dali.yonumen.top/Article/details/gtazfualky.html

[U76] PHP：简单路由
来源：http://dali.kuanghao11.cn/Article/details/gthexwgwrg.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jinqigufen.top/Article/details/gtyzynwhus.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtsntgpmzo.html

composer require twig/twig
来源：http://dali.guannengcc.top/Article/details/gtydsfvnjg.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gtkpelswmt.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gtvtreyzfp.html

[U79] PHP：静态分析
来源：http://dali.chenlongwang.top/Article/details/gtlnjvdyot.html

composer require --dev phpstan/phpstan
来源：http://dali.daxiang520.top/Article/details/gtgejvgfvt.html

[U80] PHP：代码规范修复
来源：http://dali.zhiwuduotai.top/Article/details/gtwogpxtgp.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtrcqgvniu.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gtuontphcu.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gtdjirnjfj.html

[U82] JS：package.json 脚本
来源：http://dali.sxryk.cn/Article/details/gtzlipztmo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gtlisjxgul.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhiwuduotai.top/Article/details/gtzpcsnwza.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtrhycefjx.html

[U84] JS：CommonJS 写法
来源：http://dali.hywenlv.cn/Article/details/gtsuyfibgn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyruxwhdd.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtnglsegpt.html

a?.b?.c
来源：http://dali.dashuyun.cn/Article/details/gtouelsepn.html

[U86] JS：空值合并
来源：http://dali.ivvv.top/Article/details/gtcsofqpst.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtblelcnvz.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtszeplviz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtkqvrhllz.html

[U88] JS：对象展开合并
来源：http://dali.yvedp.cn/Article/details/gtdcqpkyhc.html

{ ...a, ...b }
来源：http://dali.gzhubu.top/Article/details/gtpdsrzzoh.html

[U89] JS：数组去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtytnfgqka.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gttvyqjouo.html

[U90] JS：数字数组排序
来源：http://dali.guowangkeji.top/Article/details/gtbkwmxand.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtrpqpbohr.html

[U91] JS：对象键值遍历
来源：http://dali.jqgufenzy.top/Article/details/gtiqyoieim.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jiagoushi.top/Article/details/gtnhpbmywo.html

[U92] JS：深拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtwmgrigto.html

structuredClone(obj)
来源：http://dali.tianlin.xyz/Article/details/gtwldwbgmt.html

[U93] JS：模板字符串
来源：http://dali.gogol.net.cn/Article/details/gtjoteuqsd.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gtuglumxnu.html

[U94] JS：箭头函数
来源：http://dali.pengpengdd.cyou/Article/details/gtgvkyqnjw.html

const double = x => x * 2;
来源：http://dali.shanyushiyangtech.top/Article/details/gtoijkwqmm.html

[U95] JS：Promise 包装
来源：http://dali.xuanzx.com/Article/details/gtdyfucomc.html

new Promise((resolve, reject) => {})
来源：http://dali.zdqjudy.top/Article/details/gtiuzdjorb.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gttnctbssi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gtkcgammeh.html

[U97] JS：并发请求
来源：http://dali.hfpthk.cn/Article/details/gtjvjjrqhd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhengqikj.top/Article/details/gtlditbwln.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuxming.cn/Article/details/gtalvwudho.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dashuyun.cn/Article/details/gtphmykauu.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtnbvhrkjp.html

el.addEventListener("click", e => {})
来源：http://dali.shuidangran.top/Article/details/gtozyxxjjq.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtriaaqnuw.html

document.querySelector(".item")
来源：http://dali.xuanzx.com/Article/details/gtxvzruslm.html

[U101] JS：classList 操作
来源：http://dali.zhijiandao.cn/Article/details/gtbakfoqmm.html

el.classList.toggle("active")
来源：http://dali.zhixingplan.top/Article/details/gtxcpjvnjl.html

[U102] JS：本地存储
来源：http://dali.shuidangran.top/Article/details/gtpsldhrqs.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jianghu66.top/Article/details/gtbbgwegmf.html

[U103] JS：定时器
来源：http://dali.c1oappe.top/Article/details/gttwfrpkmb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hongshengwenyu.top/Article/details/gtpubgcpuz.html

[U104] JS：防抖
来源：http://dali.cucudq.cn/Article/details/gtcflvgnje.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.dianchejie.cn/Article/details/gttbbuorih.html

[U105] JS：节流
来源：http://dali.c1oappe.top/Article/details/gtxwshyyrg.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ivvv.top/Article/details/gtddynuvfv.html

[U106] JS：日期格式化
来源：http://dali.wangdashe.top/Article/details/gtsbrkwkxf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinghuilouyu.cn/Article/details/gtaohspfig.html

[U107] JS：数字千分位
来源：http://dali.wangshuangyany.cn/Article/details/gticlmiiwg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtmcibelfs.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtebpvlbjs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.guowangkeji.top/Article/details/gtifhyfmsr.html

[U109] JS：数组分组
来源：http://dali.sysykeji.top/Article/details/gtcdnmighv.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gtfkdpmiyi.html

[U110] JS：数组分块
来源：http://dali.vqdsnc.cn/Article/details/gtxbluwttb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gtsfzxjlsg.html

[U111] JS：对象转 Map
来源：http://dali.cqqwz.cn/Article/details/gtyulhwgkj.html

new Map(Object.entries(obj))
来源：http://dali.jinqigufen.top/Article/details/gtaldzzsct.html

[U112] JS：字符串补位
来源：http://dali.zhengqikj.top/Article/details/gtxtmmtrtm.html

"7".padStart(3, "0")
来源：http://dali.chenjidiqi.icu/Article/details/gtujwtgswf.html

[U113] JS：正则替换全部
来源：http://dali.ivvv.top/Article/details/gtlqvagnyy.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gttptnhvsa.html

[U114] JS：JSON 深比较
来源：http://dali.ehwqpu.com/Article/details/gtcmafnmfl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gaohongyu789.top/Article/details/gtbtqsuvxx.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtkowapbpk.html

crypto.randomUUID()
来源：http://dali.c1oappe.top/Article/details/gtxsccqevh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yangfankeji.com/Article/details/gtrjozvycm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jianghu66.top/Article/details/gtdmqverop.html

[U117] JS：单元测试
来源：http://dali.andypj.xyz/Article/details/gtgzoprspo.html

npm i -D vitest;  npx vitest
来源：http://dali.nwbrower.top/Article/details/gtuehwzczz.html

[U118] JS：开发服务器
来源：http://dali.guowangkeji.top/Article/details/gtcimkphqa.html

npm i -D vite;  npx vite
来源：http://dali.kuanghao11.cn/Article/details/gtcdxlhkxa.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gtniqjetbq.html

npx vite build
来源：http://dali.shuidangran.top/Article/details/gtvzojzume.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cashguo.top/Article/details/gtgiisflrr.html

import.meta.env.VITE_API_URL
来源：http://dali.yj20258.top/Article/details/gtergdhwhy.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtvlzfmezw.html

统计汇总
来源：http://dali.pengpengdd.cyou/Article/details/gtyknkvzlu.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjkpbgruo.html

按语言统计（条）：
来源：http://dali.fengsongda.top/Article/details/gtbcyubdgb.html

Python ......... 252
来源：http://dali.jqgufenzy.top/Article/details/gtldvvwcfz.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gtlajmbiwm.html

JavaScript ..... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmanpjlb.html

TypeScript ..... 212
来源：http://dali.zhoulong.xyz/Article/details/gtnlmenaxc.html

Java ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtycawjvuq.html

Go ............. 212
来源：http://dali.xuanzx.com/Article/details/gtufectevx.html

Ruby ........... 212
来源：http://dali.shuidangran.top/Article/details/gtonpjrwlh.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gtkdjantro.html

C .............. 30
来源：http://dali.hnxiangtu.top/Article/details/gtbmeemnbo.html

C++ ............ 30
来源：http://dali.nanxinkj.top/Article/details/gtxrlecfdw.html

SQL ............ 90
来源：http://dali.dianchejie.cn/Article/details/gtcqtlwydd.html

Bash ........... 80
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdudnozyr.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gtlkjstzxx.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gttgebaswi.html

Lua ............ 10
来源：http://dali.yueranfly.top/Article/details/gttwrpohuj.html

Perl ........... 10
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgubjxrb.html

Scala .......... 10
来源：http://dali.gaohongyu789.top/Article/details/gtbthgfboi.html

------------------------------------
来源：http://dali.andypj.xyz/Article/details/gtxcijefxt.html

合计 ........... 2106 条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkljewwdj.html

按章节统计：
来源：http://dali.hfpthk.cn/Article/details/gtquuocyrr.html


<!-- 参考信息 -->