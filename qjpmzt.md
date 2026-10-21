代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtabdritxc.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtzrdaxpki.html

[T46] Perl：哈希操作
来源：http://dali.yuanzhike.top/Article/details/gthfxjjyqp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gttwgmhddp.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtsveophxf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.haohaochexian.top/Article/details/gtfyjqshtn.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gthxormtkq.html

$s =~ s/old/new/g;
来源：http://dali.guowangkeji.top/Article/details/gtfztrmzlg.html

[T49] Perl：函数
来源：http://dali.yuxming.cn/Article/details/gttfjceifo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtlxmrfxzg.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtytxrjfeb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gtduodkmsi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ydzc1.top/Article/details/gtigoncuhq.html

[T51] Scala：Hello World
来源：http://dali.316326.xyz/Article/details/gtnqthumop.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtrwacuhwu.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtkhylqimi.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtvgghrxvx.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtfehwxbjl.html

s"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtqvmqufkj.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtqmysqnnv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sweek.top/Article/details/gtmczridgu.html

[T55] Scala：集合过滤
来源：http://dali.tianlin.xyz/Article/details/gttyywyjfb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gtbimmepqh.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtowcrqnfj.html

case class User(name: String, age: Int)
来源：http://dali.yj20258.top/Article/details/gtimntihti.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtokudueng.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daxiang520.top/Article/details/gttvwotsha.html

[T58] Scala：函数定义
来源：http://dali.yongpay.top/Article/details/gtzhgomifw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yangfankeji.com/Article/details/gtyisupdlg.html

[T59] Scala：循环
来源：http://dali.ivvv.top/Article/details/gtvhycvbyn.html

for (i <- 1 to 10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtjdqkducj.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtxkphjhhr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shzxlz.cn/Article/details/gtsjaottxb.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtcibdwmug.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtpzaankug.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtnaounzfh.html

[U01] Py：创建虚拟环境
来源：http://dali.cqqwz.cn/Article/details/gtotbghyhn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gtnuslrsya.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenlongwang.top/Article/details/gtnbgnibje.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hfpthk.cn/Article/details/gtlwzxwwkx.html

[U03] Py：加载 .env 配置
来源：http://dali.yanxiufei.cn/Article/details/gtyyiejdgg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gtyzldulog.html

[U04] Py：变量调试打印
来源：http://dali.xylfe.cn/Article/details/gtmeqjjjes.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cdnleiting.top/Article/details/gtmrciojyf.html

[U05] Py：列表去重且保序
来源：http://dali.ydzc1.top/Article/details/gtcvuwzatd.html

list(dict.fromkeys(arr))
来源：http://dali.cucudq.cn/Article/details/gtlmzwdgyo.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtthnpefar.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtouagpnpv.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gtisnezeap.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtkieepwdt.html

[U08] Py：展平二维列表
来源：http://dali.chenzaomai.com/Article/details/gtnjlnlubs.html

[y for x in nested for y in x]
来源：http://dali.zhijiandao.cn/Article/details/gtjlyolacl.html

[U09] Py：字典取最大值的键
来源：http://dali.haohaochexian.top/Article/details/gthmgcozst.html

max(d, key=d.get)
来源：http://dali.guannengcc.top/Article/details/gtdvutdsfu.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtykiejjdw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sufxvd.cn/Article/details/gtkrzgikgn.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtdonbfwlw.html

(x * 2 for x in arr)
来源：http://dali.nanxuanxn.top/Article/details/gtpaxxmslr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shangyingyoupin.top/Article/details/gttlrsclfo.html

Counter(arr).most_common(3)
来源：http://dali.svipenyu.cn/Article/details/gthpxpntqq.html

[U13] Py：固定长度队列
来源：http://dali.cucudq.cn/Article/details/gtzmhdihsa.html

deque(maxlen=10)
来源：http://dali.haohaochexian.top/Article/details/gtpknsmffg.html

[U14] Py：分组收集到列表
来源：http://dali.shzxlz.cn/Article/details/gtgfykqhal.html

defaultdict(list)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtghzlgims.html

[U15] Py：高精度计时
来源：http://dali.shuidangran.top/Article/details/gtkmmdmpxu.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gttplhjqth.html

[U16] Py：命令行参数解析
来源：http://dali.ivvv.top/Article/details/gtratkndoe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.bjfxy.top/Article/details/gtwplxijvs.html

[U17] Py：初始化日志
来源：http://dali.redwolf501.top/Article/details/gtmlkogaib.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yonumen.top/Article/details/gtzdtozizm.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtvykkygew.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtodqnnajm.html

[U19] Py：正则替换带回调
来源：http://dali.wangshuangyany.cn/Article/details/gtvzaeptcl.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hywenlv.cn/Article/details/gtpjksacis.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiouzpsg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtvuwtbiuv.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtzquwvpiy.html

@contextlib.contextmanager
来源：http://dali.yueranfly.top/Article/details/gtiqqjhsbp.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gtwfpnrrjz.html

list(zip(*m))
来源：http://dali.yuanzhike.top/Article/details/gtisabhzvp.html

[U23] Py：分块读取大文件
来源：http://dali.xuetiantiany.cn/Article/details/gtqjvxuwke.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinqigfzy.top/Article/details/gtttpaceig.html

[U24] Py：路径操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvycvmzps.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtvojawkaw.html

[U25] Py：CSV 按字典读
来源：http://dali.gaohongyu789.top/Article/details/gtagjzuouj.html

csv.DictReader(f)
来源：http://dali.redwolf501.top/Article/details/gtqweiqdnu.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtjsadryna.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkvdnhbl.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gtnkreqkgs.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtociwobuq.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtfjzqxfii.html

UserId = int
来源：http://dali.nwbrower.top/Article/details/gtdnncbcmg.html

[U29] Py：属性校验
来源：http://dali.nwbrower.top/Article/details/gtkynkcvju.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gtpvcfxetc.html

[U30] Py：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtquewhewp.html

@dataclass(slots=True)
来源：http://dali.c1oappe.top/Article/details/gtimtfzarc.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gtupdempgn.html

python -m pytest -q
来源：http://dali.guowangkeji.top/Article/details/gtqrbiwokx.html

[U32] Py：代码格式化
来源：http://dali.sufxvd.cn/Article/details/gtqvcodgwy.html

ruff format . && ruff check --fix .
来源：http://dali.jqgfzy.top/Article/details/gtzjqshmhv.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtsssdjuin.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xuanzx.com/Article/details/gtzdpolrym.html

[U34] Py：判断编码
来源：http://dali.shangyingyoupin.top/Article/details/gthkphksxd.html

chardet.detect(raw)
来源：http://dali.xylfe.cn/Article/details/gtgajxxdak.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtoxlmamea.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.c1oappe.top/Article/details/gttbopslis.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtehobaasg.html

schedule.every(10).minutes.do(job)
来源：http://dali.yj202588.top/Article/details/gtjjmdinsc.html

[U37] Py：读写 Excel
来源：http://dali.wangshuangyany.cn/Article/details/gtklhubvjc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtjrqgzlzn.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gtvuexajfq.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtlbsbqzok.html

[U39] Py：判断是否在交互环境
来源：http://dali.gotoacloud.top/Article/details/gtsespdsvk.html

sys.stdout.isatty()
来源：http://dali.hywenlv.cn/Article/details/gtucykownq.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtdtygpcxi.html

print("err", file=sys.stderr)
来源：http://dali.jlsjyb.cn/Article/details/gtarjumygl.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtncqotnjy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xinyue.icu/Article/details/gtytlmxnqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yongpay.top/Article/details/gtmhhzzvyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gtktdjvkdx.html

[U43] PHP：声明命名空间
来源：http://dali.gzhubu.top/Article/details/gtsshpcbte.html

namespace App\Http;
来源：http://dali.wangdashe.top/Article/details/gtlenbtbqi.html

[U44] PHP：开启严格类型
来源：http://dali.fengsongda.top/Article/details/gtzrwqkoaj.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtfhgoqift.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenlongwang.top/Article/details/gtvogyyyjr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtoikyjjuy.html

[U46] PHP：可空类型
来源：http://dali.hnqzz.top/Article/details/gtepgkuszb.html

?string $name = null
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxeiyarw.html

[U47] PHP：联合类型
来源：http://dali.aizwys.cn/Article/details/gteatlcins.html

int|string $id
来源：http://dali.guannengcc.top/Article/details/gtjekyfbxb.html

[U48] PHP：纯枚举
来源：http://dali.zhixingplan.top/Article/details/gttqrtvtdl.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gtqcugtapg.html

[U49] PHP：只读属性
来源：http://dali.cheryme.top/Article/details/gtliqcbcss.html

public readonly string $name
来源：http://dali.iojbl.cn/Article/details/gttyzmrddv.html

[U50] PHP：构造器属性提升
来源：http://dali.guowangkeji.top/Article/details/gtpdwdkmjf.html

public function __construct(private int $id) {}
来源：http://dali.andypj.xyz/Article/details/gtuautzgym.html

[U51] PHP：数组解构
来源：http://dali.wangshuangyany.cn/Article/details/gthbkmovjx.html

[$a, $b] = $arr;
来源：http://dali.hysaishi.cn/Article/details/gtbxgffxpb.html

[U52] PHP：箭头函数
来源：http://dali.ppjwa.cn/Article/details/gtcxgoohkt.html

$double = fn($x) => $x * 2;
来源：http://dali.cheryme.top/Article/details/gtcfuegqvi.html

[U53] PHP：空合并运算符
来源：http://dali.tianlin.xyz/Article/details/gtqjdyjzzj.html

$v = $a ?? $b ?? "default";
来源：http://dali.feifeiyinyue.top/Article/details/gttsqrqxrb.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gthuhdtsdb.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtkzjnsmyz.html

[U55] PHP：match 表达式
来源：http://dali.xylfe.cn/Article/details/gthecruicf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yvedp.cn/Article/details/gtmmvxecot.html

[U56] PHP：命名参数
来源：http://dali.nanxinkj.top/Article/details/gtqufjrqjq.html

f(a: 1, b: 2)
来源：http://dali.zdqjudy.top/Article/details/gtuhpcblzd.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtaksihvlt.html

"值: {$a}"
来源：http://dali.havefunace.top/Article/details/gtlwibeuld.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtpvzwjlyz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjqbaiyd.html

[U59] PHP：自定义排序
来源：http://dali.jqgufenzy.top/Article/details/gtpziiixdu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.meibo888.top/Article/details/gtmjyphiln.html

[U60] PHP：JSON 编解码
来源：http://dali.wangdashe.top/Article/details/gthkgwzokp.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jqgfzy.top/Article/details/gtnxidfcvg.html

[U61] PHP：正则
来源：http://dali.cheryme.top/Article/details/gtbfwnrvci.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtrmtggaxp.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gtlguhujlq.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxxygsoqc.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gtubmwlvyl.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.wangshuangyany.cn/Article/details/gtozbpmvax.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gttklwypls.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shzxlz.cn/Article/details/gtkjltyrzy.html

[U65] PHP：会话
来源：http://dali.birdmap.top/Article/details/gtxabxxmmb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtciaqqtcu.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gtpdjrghmz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakqkzvjn.html

[U67] PHP：处理文件上传
来源：http://dali.ehwqpu.com/Article/details/gtnhxditzp.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yonumen.top/Article/details/gtkwvgmigs.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtnvglyjwh.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtflrwqdsh.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gtzhcmopnl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthwwdoyxn.html

[U70] PHP：PDO 事务
来源：http://dali.shzxlz.cn/Article/details/gtlyuvoweq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ydzc1.top/Article/details/gtxftftjhn.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gtyovpovng.html

throw new RuntimeException("失败", 500);
来源：http://dali.jianghu66.top/Article/details/gtykqntjqz.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtdqswuwuz.html

error_log("失败: " . $e->getMessage());
来源：http://dali.bjfxy.top/Article/details/gtclilccit.html

[U73] PHP：读取 ini 配置
来源：http://dali.sysykeji.top/Article/details/gtazxiewih.html

parse_ini_file("config.ini", true)
来源：http://dali.sysykeji.top/Article/details/gtmtltjwyl.html

[U74] PHP：读取环境变量
来源：http://dali.yongpay.top/Article/details/gtcwjudjhh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gtkvoqadbn.html

[U75] PHP：依赖注入
来源：http://dali.dianchejie.cn/Article/details/gtkpoamlcm.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtjcfuthcb.html

[U76] PHP：简单路由
来源：http://dali.jqgfzy.top/Article/details/gtgxfsacsh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gtazetkjmv.html

[U77] PHP：模板渲染
来源：http://dali.ehwqpu.com/Article/details/gtyszcgjyd.html

composer require twig/twig
来源：http://dali.yongpay.top/Article/details/gtvvjjowtl.html

[U78] PHP：单元测试
来源：http://dali.sufxvd.cn/Article/details/gtcjikcluv.html

composer require --dev phpunit/phpunit
来源：http://dali.jianghu66.top/Article/details/gtqtpctsdy.html

[U79] PHP：静态分析
来源：http://dali.zhengqikj.top/Article/details/gtqrpryohq.html

composer require --dev phpstan/phpstan
来源：http://dali.cheryme.top/Article/details/gtfdunicqw.html

[U80] PHP：代码规范修复
来源：http://dali.ybcxt.top/Article/details/gtpvbjjgzr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gtnxaxxcko.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gtpxkjcebx.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtgjhoqvqb.html

[U82] JS：package.json 脚本
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjvmkxlm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnqaojol.html

[U83] JS：ES Module 导入导出
来源：http://dali.kuanghao11.cn/Article/details/gtlbleckxc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gtptyxssam.html

[U84] JS：CommonJS 写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzuhxqpn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtqladhlht.html

[U85] JS：可选链
来源：http://dali.zhijiandao.cn/Article/details/gtuutqmrwv.html

a?.b?.c
来源：http://dali.yvedp.cn/Article/details/gtzyirideu.html

[U86] JS：空值合并
来源：http://dali.yonumen.top/Article/details/gtkublkpwd.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gtzcsbldld.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gttrvolpvl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jiagoushi.top/Article/details/gtbeenopck.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gtpagjpdjc.html

{ ...a, ...b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiulsvawv.html

[U89] JS：数组去重
来源：http://dali.yanxiufei.cn/Article/details/gtcwyaunsd.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtmjomwpzv.html

[U90] JS：数字数组排序
来源：http://dali.xziqi.cn/Article/details/gtllkpepcf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhengqikj.top/Article/details/gtqbbzdluv.html

[U91] JS：对象键值遍历
来源：http://dali.xuanzx.com/Article/details/gtdlaigojp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.aizwys.cn/Article/details/gttujinwzr.html

[U92] JS：深拷贝
来源：http://dali.yonumen.top/Article/details/gtwfzxddkf.html

structuredClone(obj)
来源：http://dali.jianghu66.top/Article/details/gttednkfhq.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtngftrsrw.html

`共 ${n} 条`
来源：http://dali.yongpay.top/Article/details/gtyccqojon.html

[U94] JS：箭头函数
来源：http://dali.jqgfzy.top/Article/details/gtbrzxxkkm.html

const double = x => x * 2;
来源：http://dali.9152youxi.cn/Article/details/gtkaeonnqp.html

[U95] JS：Promise 包装
来源：http://dali.jinqigfzy.top/Article/details/gtjjkekdnl.html

new Promise((resolve, reject) => {})
来源：http://dali.havefunace.top/Article/details/gtzxycpoqe.html

[U96] JS：async/await 与异常
来源：http://dali.sweek.top/Article/details/gtyajdsxtv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtbfmcbcad.html

[U97] JS：并发请求
来源：http://dali.smart0.xyz/Article/details/gtijihhlsp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtwstruxzy.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtkornqtce.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xziqi.cn/Article/details/gtftznfydv.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtgvgzuxyh.html

el.addEventListener("click", e => {})
来源：http://dali.chenlongwang.top/Article/details/gterogxsqe.html

[U100] JS：DOM 查询
来源：http://dali.svipenyu.cn/Article/details/gtrrzaoatt.html

document.querySelector(".item")
来源：http://dali.vqdsnc.cn/Article/details/gtipcuzfyl.html

[U101] JS：classList 操作
来源：http://dali.yangfankeji.com/Article/details/gtipqfzmuk.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gtyzoqsqnn.html

[U102] JS：本地存储
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcxdfgpan.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ydzc1.top/Article/details/gttlrqctfl.html

[U103] JS：定时器
来源：http://dali.sweek.top/Article/details/gtsahuypuz.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiqpmznmm.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gtstqhyahj.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nanxuanxn.top/Article/details/gtanornjoq.html

[U105] JS：节流
来源：http://dali.hysaishi.cn/Article/details/gtndrstvyi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gtrjqrjnbf.html

[U106] JS：日期格式化
来源：http://dali.hfpthk.cn/Article/details/gttifqhbkf.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.andypj.xyz/Article/details/gtqnonzjld.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbeikivvt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xinyue.icu/Article/details/gtzkevqexk.html

[U108] JS：随机整数
来源：http://dali.cucudq.cn/Article/details/gtihotzimy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gtiebileyq.html

[U109] JS：数组分组
来源：http://dali.cdnleiting.top/Article/details/gtakljksuz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtnlgfmjha.html

[U110] JS：数组分块
来源：http://dali.xuetiantiany.cn/Article/details/gtlqradwul.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yanxiufei.cn/Article/details/gtqtfwcgdp.html

[U111] JS：对象转 Map
来源：http://dali.ppjwa.cn/Article/details/gttlkhpekd.html

new Map(Object.entries(obj))
来源：http://dali.yuanzhike.top/Article/details/gtjfsvmtrb.html

[U112] JS：字符串补位
来源：http://dali.guowangkeji.top/Article/details/gtrecxjccy.html

"7".padStart(3, "0")
来源：http://dali.iojbl.cn/Article/details/gtyzqqosqq.html

[U113] JS：正则替换全部
来源：http://dali.zycfv.cn/Article/details/gtyreqmhqj.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gtgvdtpyog.html

[U114] JS：JSON 深比较
来源：http://dali.yueranfly.top/Article/details/gthnljcrih.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhengqikj.top/Article/details/gtczzjtkks.html

[U115] JS：生成 UUID
来源：http://dali.yuxming.cn/Article/details/gtqqbtgshv.html

crypto.randomUUID()
来源：http://dali.chenzaomai.com/Article/details/gtuwsdvfxr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvrkrwzl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gotoacloud.top/Article/details/gtqqybaypa.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gtfinuewow.html

npm i -D vitest;  npx vitest
来源：http://dali.yonumen.top/Article/details/gttpjfzdlx.html

[U118] JS：开发服务器
来源：http://dali.zhongyouzk.top/Article/details/gtzyouuhii.html

npm i -D vite;  npx vite
来源：http://dali.xylfe.cn/Article/details/gtmimepquj.html

[U119] JS：生产构建
来源：http://dali.jqgufenzy.top/Article/details/gtuxvnrcwr.html

npx vite build
来源：http://dali.xuanzx.com/Article/details/gtvaibzlpj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xylfe.cn/Article/details/gtfrscyjsr.html

import.meta.env.VITE_API_URL
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkprzunj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpdvabvxb.html

统计汇总
来源：http://dali.sufxvd.cn/Article/details/gtyffzykrs.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gttrpnvafk.html

按语言统计（条）：
来源：http://dali.gzhubu.top/Article/details/gtpxrmmbom.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtbbhwoigo.html

PHP ............ 252
来源：http://dali.birdmap.top/Article/details/gtntupyeyy.html

JavaScript ..... 252
来源：http://dali.vqdsnc.cn/Article/details/gtfdfpjzjl.html

TypeScript ..... 212
来源：http://dali.ydzc1.top/Article/details/gtctkriecb.html

Java ........... 212
来源：http://dali.jinqigufen.top/Article/details/gtpettrddx.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gtpuvgttkv.html

Ruby ........... 212
来源：http://dali.jqgfzy.top/Article/details/gtbwobtqda.html

C# ............. 212
来源：http://dali.xylfe.cn/Article/details/gtvwuhiqir.html

C .............. 30
来源：http://dali.cucudq.cn/Article/details/gtvkabaqjc.html

C++ ............ 30
来源：http://dali.yangfankeji.com/Article/details/gtarukuica.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnhlqopac.html

Bash ........... 80
来源：http://dali.jinqigufen.top/Article/details/gthmiiicdo.html

Kotlin ......... 15
来源：http://dali.xuanzx.com/Article/details/gtyxlyhvgj.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtnfnvxwrw.html

Lua ............ 10
来源：http://dali.kuanghao11.cn/Article/details/gtytlykwni.html

Perl ........... 10
来源：http://dali.shzxlz.cn/Article/details/gtxrltymvg.html

Scala .......... 10
来源：http://dali.meibo888.top/Article/details/gtscasuxsh.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtmpzndpvz.html

合计 ........... 2106 条
来源：http://dali.aibaodan.cn/Article/details/gtspmwugcf.html

按章节统计：
来源：http://dali.jlsjyb.cn/Article/details/gtjniwjidl.html


<!-- 参考信息 -->