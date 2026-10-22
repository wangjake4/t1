代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.haohaochexian.top/Article/details/gtblentfza.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtqvfzwizc.html

[T46] Perl：哈希操作
来源：http://dali.zdqjudy.top/Article/details/gtyxshnfoe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.fzhhl.top/Article/details/gtaxdbuawp.html

[T47] Perl：正则捕获
来源：http://dali.gogol.net.cn/Article/details/gthsuytlfk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.c1oappe.top/Article/details/gtkeztofel.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtpomloqgu.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gtpmzrjava.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gtrwadwbbz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpkgqnmhv.html

[T50] Perl：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gthnrfluah.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtedmlhoqe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sweek.top/Article/details/gtcrcpfbeb.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtpdushzut.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtpdnsifnc.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtldheyvbi.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtvtlerbfd.html

[T53] Scala：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtaxcsyuwl.html

s"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtojcvrgvu.html

[T54] Scala：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtulvhfwhq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfbepskgg.html

[T55] Scala：集合过滤
来源：http://dali.guowangkeji.top/Article/details/gtlpppazip.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtidqhztnc.html

[T56] Scala：样例类
来源：http://dali.tianlin.xyz/Article/details/gtdsvivypc.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtqofaatzm.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gtyxprcaml.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtpvdbwmjt.html

[T58] Scala：函数定义
来源：http://dali.yj202588.top/Article/details/gtdopbmmgl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhongyouzk.top/Article/details/gtgcsqlnty.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkkvvttz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtglkaxdsf.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gtrcczgceb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zycfv.cn/Article/details/gtfipnhqvh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdcnwarup.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daria6918.cn/Article/details/gtkljqljpw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtlnzqpzfu.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gtxkjvqdlj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtgdeppigo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gtedlmtemv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gtqvofezcn.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtbsotwder.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcxqxwxd.html

[U04] Py：变量调试打印
来源：http://dali.jiagoushi.top/Article/details/gtssigteta.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtfoilgnif.html

[U05] Py：列表去重且保序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxvxlxkf.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtbvkirkce.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtgpbkobzu.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtnlqkfshs.html

[U07] Py：反转字典键值
来源：http://dali.havefunace.top/Article/details/gtomdasngu.html

{v: k for k, v in d.items()}
来源：http://dali.iojbl.cn/Article/details/gtemkcmcmt.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaxqzafs.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gtkkqrluer.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gtshwykbca.html

max(d, key=d.get)
来源：http://dali.dianchejie.cn/Article/details/gtdpucodyg.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtitqtjnop.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.smart0.xyz/Article/details/gttplaehzr.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtipcffmca.html

(x * 2 for x in arr)
来源：http://dali.xziqi.cn/Article/details/gtgogkmhbc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.pengpengdd.cyou/Article/details/gtsctudagw.html

Counter(arr).most_common(3)
来源：http://dali.sysykeji.top/Article/details/gteccqtrdx.html

[U13] Py：固定长度队列
来源：http://dali.gotoacloud.top/Article/details/gtgqhtofwk.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtjpzlyktw.html

[U14] Py：分组收集到列表
来源：http://dali.zycfv.cn/Article/details/gtuksvqcas.html

defaultdict(list)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzsdjrpz.html

[U15] Py：高精度计时
来源：http://dali.9152youxi.cn/Article/details/gtjuevvzoj.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gtzpvrvkmj.html

[U16] Py：命令行参数解析
来源：http://dali.zhiwuduotai.top/Article/details/gtsxpdbmdd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gtnynjdtie.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gtiwwzikgb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhengqikj.top/Article/details/gtqptmtqnz.html

[U18] Py：预编译正则
来源：http://dali.yj20258888.top/Article/details/gtfsgxctpy.html

pat = re.compile(r"\d+")
来源：http://dali.daxiang520.top/Article/details/gtfvknjdte.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtmqzoaejb.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtvwvqpnbs.html

[U20] Py：缓存函数结果
来源：http://dali.zdqjudy.top/Article/details/gtpdtwrrnt.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqnaikhki.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtklaqljiz.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gtwhohwqmm.html

[U22] Py：矩阵转置
来源：http://dali.jlsjyb.cn/Article/details/gtsxvswbmz.html

list(zip(*m))
来源：http://dali.dashuyun.cn/Article/details/gtxnbbyupn.html

[U23] Py：分块读取大文件
来源：http://dali.wangdashe.top/Article/details/gtwcpqetkc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.fzhhl.top/Article/details/gtgwlvtlct.html

[U24] Py：路径操作
来源：http://dali.jqgfzy.top/Article/details/gtsdblgxxy.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gtfwmvyvnb.html

[U25] Py：CSV 按字典读
来源：http://dali.gzhubu.top/Article/details/gtryzbhohh.html

csv.DictReader(f)
来源：http://dali.jqgufenzy.top/Article/details/gtkaulnuwp.html

[U26] Py：并发下载
来源：http://dali.xuetiantiany.cn/Article/details/gtpqyupmrd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.aibaodan.cn/Article/details/gtidmskvhx.html

[U27] Py：异步 HTTP
来源：http://dali.redwolf501.top/Article/details/gtjqgibosm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gtoqvwckyg.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gtwpvhqfvl.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtfqaoffhf.html

[U29] Py：属性校验
来源：http://dali.cdnleiting.top/Article/details/gtixrlbpop.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gtmxexexol.html

[U30] Py：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtntgbpayw.html

@dataclass(slots=True)
来源：http://dali.tian-w.cn/Article/details/gtdnrrsbop.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gtqnhthctr.html

python -m pytest -q
来源：http://dali.sxryk.cn/Article/details/gtumqbbmls.html

[U32] Py：代码格式化
来源：http://dali.hysaishi.cn/Article/details/gtljrdmcqc.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtgqdmvzqq.html

[U33] Py：打包发布
来源：http://dali.redwolf501.top/Article/details/gtakpclnqy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhongyouzk.top/Article/details/gtufzkzjyc.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtkmvmrcnu.html

chardet.detect(raw)
来源：http://dali.xuetiantiany.cn/Article/details/gtwujgqecp.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtdgqzfmfm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.guowangkeji.top/Article/details/gtkeonpksz.html

[U36] Py：定时任务
来源：http://dali.hysaishi.cn/Article/details/gtcnuidjhr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jianghu66.top/Article/details/gtbqahunqu.html

[U37] Py：读写 Excel
来源：http://dali.c1oappe.top/Article/details/gtjgyqqlor.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yongpay.top/Article/details/gtwgulxxks.html

[U38] Py：获取脚本所在目录
来源：http://dali.9152youxi.cn/Article/details/gtrwrhwwjn.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gtygjwnyrj.html

[U39] Py：判断是否在交互环境
来源：http://dali.cdnleiting.top/Article/details/gtjxianuem.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gtyrverowo.html

[U40] Py：打印到标准错误
来源：http://dali.wangshuangyany.cn/Article/details/gtdigsxkfu.html

print("err", file=sys.stderr)
来源：http://dali.kuanghao11.cn/Article/details/gtmhposcga.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hysaishi.cn/Article/details/gtuqwxlktn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jyoumei.cn/Article/details/gtxazmvoji.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigfzy.top/Article/details/gtypgaxgyy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shzxlz.cn/Article/details/gtvdnmcifm.html

[U43] PHP：声明命名空间
来源：http://dali.wangdashe.top/Article/details/gtmwydcyjm.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnomerxa.html

[U44] PHP：开启严格类型
来源：http://dali.nanxinkj.top/Article/details/gtvhpznllr.html

declare(strict_types=1);
来源：http://dali.daria6918.cn/Article/details/gtnoruxrmx.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtnlndtoyo.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gtifxyaltq.html

[U46] PHP：可空类型
来源：http://dali.jinqigfzy.top/Article/details/gtcnsxpedp.html

?string $name = null
来源：http://dali.cdnleiting.top/Article/details/gtimnfrvdy.html

[U47] PHP：联合类型
来源：http://dali.svipenyu.cn/Article/details/gtdyatjxmv.html

int|string $id
来源：http://dali.shzxlz.cn/Article/details/gtxlgdkljv.html

[U48] PHP：纯枚举
来源：http://dali.gzhubu.top/Article/details/gtgrksdbhf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fengsongda.top/Article/details/gttotudhpo.html

[U49] PHP：只读属性
来源：http://dali.hnxiangtu.top/Article/details/gtjlqyivbm.html

public readonly string $name
来源：http://dali.tian-w.cn/Article/details/gtzcwwcwpb.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtnzlaulsd.html

public function __construct(private int $id) {}
来源：http://dali.ydzc1.top/Article/details/gtxseobiae.html

[U51] PHP：数组解构
来源：http://dali.yanxiufei.cn/Article/details/gtzkzhrpph.html

[$a, $b] = $arr;
来源：http://dali.yuxming.cn/Article/details/gtspvtitzf.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtutleooep.html

$double = fn($x) => $x * 2;
来源：http://dali.aizwys.cn/Article/details/gteurfoilx.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtguuperqh.html

$v = $a ?? $b ?? "default";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalecupgv.html

[U54] PHP：空安全调用
来源：http://dali.gzhubu.top/Article/details/gtrqdtvxen.html

$obj?->method()
来源：http://dali.iojbl.cn/Article/details/gtgcimoqfr.html

[U55] PHP：match 表达式
来源：http://dali.xziqi.cn/Article/details/gtbmzrkffd.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cucudq.cn/Article/details/gtgbokfheb.html

[U56] PHP：命名参数
来源：http://dali.hnxiangtu.top/Article/details/gtxqedifgx.html

f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtciiiqfqk.html

[U57] PHP：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtohcttxpz.html

"值: {$a}"
来源：http://dali.gaohongyu789.top/Article/details/gtaxpgayif.html

[U58] PHP：数组三件套
来源：http://dali.cashguo.top/Article/details/gtvwxdhafz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.birdmap.top/Article/details/gtcszbsdpw.html

[U59] PHP：自定义排序
来源：http://dali.dianchejie.cn/Article/details/gtgivuorst.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtimzbcwpe.html

[U60] PHP：JSON 编解码
来源：http://dali.yuxming.cn/Article/details/gthfruumlb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gtmeqlclal.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gtyceiqjnr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtswgslofb.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gttgqccwnj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.316326.xyz/Article/details/gtgrgdebec.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtozcvolmn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zycfv.cn/Article/details/gtlskeohgp.html

[U64] PHP：目录遍历
来源：http://dali.gogol.net.cn/Article/details/gtrdlxysax.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.snrcjt.cn/Article/details/gtykphzulb.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtxwhukhla.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtxspcylla.html

[U66] PHP：设置 Cookie
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvtvbitu.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtmyzyrxmy.html

[U67] PHP：处理文件上传
来源：http://dali.jinghuilouyu.cn/Article/details/gthdbkbfmr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gtxkwfqalj.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtltprfkvp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.iojbl.cn/Article/details/gtqktnwtel.html

[U69] PHP：PDO 预处理
来源：http://dali.jiagoushi.top/Article/details/gtlwjluhoz.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.hywenlv.cn/Article/details/gtabscxnyl.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtayekmctw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gtrxqxcwzc.html

[U71] PHP：抛出异常
来源：http://dali.redwolf501.top/Article/details/gtlhlvexoe.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gtlwprjdsr.html

[U72] PHP：写错误日志
来源：http://dali.ehwqpu.com/Article/details/gtzdepcqlw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jqgfzy.top/Article/details/gtzpwctdys.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gtgnxghlph.html

parse_ini_file("config.ini", true)
来源：http://dali.chenjidiqi.icu/Article/details/gtcuixaryc.html

[U74] PHP：读取环境变量
来源：http://dali.yuanzhike.top/Article/details/gthwubpyxx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdeakbqbp.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gtfjrkrltz.html

composer require psr/container
来源：http://dali.guowangkeji.top/Article/details/gteiaivcva.html

[U76] PHP：简单路由
来源：http://dali.yj20258.top/Article/details/gtpcijuzyj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.bjfxy.top/Article/details/gtlysrdndz.html

[U77] PHP：模板渲染
来源：http://dali.c1oappe.top/Article/details/gtqwvlmrpu.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gtqgozkodh.html

[U78] PHP：单元测试
来源：http://dali.snrcjt.cn/Article/details/gtahaxlngv.html

composer require --dev phpunit/phpunit
来源：http://dali.guowangkeji.top/Article/details/gtgpkdumab.html

[U79] PHP：静态分析
来源：http://dali.yonumen.top/Article/details/gttelzhpoj.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtkooiljny.html

[U80] PHP：代码规范修复
来源：http://dali.yj202588.top/Article/details/gtxyywaouo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gtoxzpdqal.html

[U81] JS：初始化项目
来源：http://dali.guannengcc.top/Article/details/gtpdopxfyl.html

npm init -y;  npm i express
来源：http://dali.dashuyun.cn/Article/details/gtjzxmhpcf.html

[U82] JS：package.json 脚本
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyaowvkyj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cashguo.top/Article/details/gtwflvwrkn.html

[U83] JS：ES Module 导入导出
来源：http://dali.haohaochexian.top/Article/details/gtfncphjkt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gtosiubexg.html

[U84] JS：CommonJS 写法
来源：http://dali.zhiwuduotai.top/Article/details/gtubghymmp.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtkddzubll.html

[U85] JS：可选链
来源：http://dali.vqdsnc.cn/Article/details/gtyhfnwzfg.html

a?.b?.c
来源：http://dali.sweek.top/Article/details/gtnqdhdckr.html

[U86] JS：空值合并
来源：http://dali.shanyushiyangtech.top/Article/details/gtuztyjule.html

a ?? b
来源：http://dali.quarkkingdee.top/Article/details/gtfkoagfcm.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtsixacekg.html

const { a = 1, b = 2 } = obj;
来源：http://dali.snrcjt.cn/Article/details/gtrpixffbq.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdjuowip.html

{ ...a, ...b }
来源：http://dali.yuxming.cn/Article/details/gtzbdkmvbq.html

[U89] JS：数组去重
来源：http://dali.zhongyouzk.top/Article/details/gtwqqlgllt.html

[...new Set(arr)]
来源：http://dali.yueranfly.top/Article/details/gthzfkadvo.html

[U90] JS：数字数组排序
来源：http://dali.wangshuangyany.cn/Article/details/gtdfnukrfi.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shzxlz.cn/Article/details/gtbmaixnxq.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtmczqfrfy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtebtzndgz.html

[U92] JS：深拷贝
来源：http://dali.jianghu66.top/Article/details/gteguxmlbn.html

structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlvgasly.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtxhaqmvva.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtedlppign.html

[U94] JS：箭头函数
来源：http://dali.0kj1m.cn/Article/details/gtyqzhphok.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtaklnghco.html

[U95] JS：Promise 包装
来源：http://dali.yuanzhike.top/Article/details/gtpqeshlfq.html

new Promise((resolve, reject) => {})
来源：http://dali.fengsongda.top/Article/details/gtkjiwubmy.html

[U96] JS：async/await 与异常
来源：http://dali.yuxming.cn/Article/details/gtddqocjzy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.fzhhl.top/Article/details/gtlhtiuluz.html

[U97] JS：并发请求
来源：http://dali.zhoulong.xyz/Article/details/gtpmcdymwe.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sxryk.cn/Article/details/gtwoelhcdc.html

[U98] JS：fetch 带 JSON
来源：http://dali.dashuyun.cn/Article/details/gtrjfzjrqu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gogol.net.cn/Article/details/gtwoddoczv.html

[U99] JS：事件监听
来源：http://dali.svipenyu.cn/Article/details/gthqbpkpbz.html

el.addEventListener("click", e => {})
来源：http://dali.xuetiantiany.cn/Article/details/gthpetoytm.html

[U100] JS：DOM 查询
来源：http://dali.shangyingyoupin.top/Article/details/gtlevgpuxx.html

document.querySelector(".item")
来源：http://dali.nanxinkj.top/Article/details/gtnlaxjzzv.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtguzepzqj.html

el.classList.toggle("active")
来源：http://dali.quarkkingdee.top/Article/details/gtitfihuqu.html

[U102] JS：本地存储
来源：http://dali.jyoumei.cn/Article/details/gttxzxthpa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xziqi.cn/Article/details/gtaznhkzyh.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gtdchckimf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.c1oappe.top/Article/details/gtlmtvvlad.html

[U104] JS：防抖
来源：http://dali.ybcxt.top/Article/details/gthozdfsxk.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gtlhtxpppw.html

[U105] JS：节流
来源：http://dali.ybcxt.top/Article/details/gtaciojmjf.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daria6918.cn/Article/details/gtfdohhiqc.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtbbuhryug.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhijiandao.cn/Article/details/gtvtorynzi.html

[U107] JS：数字千分位
来源：http://dali.gotoacloud.top/Article/details/gtueoxjygo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtqbywmbao.html

[U108] JS：随机整数
来源：http://dali.nanxinkj.top/Article/details/gtcasfasjt.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yonumen.top/Article/details/gttarcbrtb.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtukvlnkah.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtahuwadub.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gtuwftpeqm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.9152youxi.cn/Article/details/gtoscdjgzy.html

[U111] JS：对象转 Map
来源：http://dali.gzhubu.top/Article/details/gtqgvwfuic.html

new Map(Object.entries(obj))
来源：http://dali.zhijiandao.cn/Article/details/gturigruxe.html

[U112] JS：字符串补位
来源：http://dali.meibo888.top/Article/details/gtmesohciu.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtqxeanhbg.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gtgimhhexx.html

s.replaceAll("a", "b")
来源：http://dali.yj20258.top/Article/details/gtuorgnhvm.html

[U114] JS：JSON 深比较
来源：http://dali.iojbl.cn/Article/details/gtefdazyjl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yvedp.cn/Article/details/gtrtwsyflz.html

[U115] JS：生成 UUID
来源：http://dali.shanyushiyangtech.top/Article/details/gtuswqvdil.html

crypto.randomUUID()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcpppxsgh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhijiandao.cn/Article/details/gtovuwlmao.html

/** @param {string} name */ function f(name) {}
来源：http://dali.aizwys.cn/Article/details/gtftqnmvma.html

[U117] JS：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtowhmvmji.html

npm i -D vitest;  npx vitest
来源：http://dali.c1oappe.top/Article/details/gtjafrrdxn.html

[U118] JS：开发服务器
来源：http://dali.havefunace.top/Article/details/gtzocvdqcl.html

npm i -D vite;  npx vite
来源：http://dali.guowangkeji.top/Article/details/gtmbbpokbx.html

[U119] JS：生产构建
来源：http://dali.ppjwa.cn/Article/details/gtdkdjwibn.html

npx vite build
来源：http://dali.hywenlv.cn/Article/details/gtciwpgjxm.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinghuilouyu.cn/Article/details/gtubfbihte.html

import.meta.env.VITE_API_URL
来源：http://dali.guowangkeji.top/Article/details/gtataxzawj.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtwaxilcim.html

统计汇总
来源：http://dali.zycfv.cn/Article/details/gtfjrqqlcs.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtwrkbwtgr.html

按语言统计（条）：
来源：http://dali.pycfn.com/Article/details/gtarmlnfxu.html

Python ......... 252
来源：http://dali.0kj1m.cn/Article/details/gtrfzslhgc.html

PHP ............ 252
来源：http://dali.hfpthk.cn/Article/details/gtafpddmts.html

JavaScript ..... 252
来源：http://dali.haohaochexian.top/Article/details/gtjefnwfok.html

TypeScript ..... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtrolpsmde.html

Java ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgkwszded.html

Go ............. 212
来源：http://dali.zhengqikj.top/Article/details/gtwepbzadr.html

Ruby ........... 212
来源：http://dali.dashuyun.cn/Article/details/gtxwrixpro.html

C# ............. 212
来源：http://dali.zhixingplan.top/Article/details/gtzqytnhoq.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gtudtetagd.html

C++ ............ 30
来源：http://dali.0kj1m.cn/Article/details/gtuwkkknvw.html

SQL ............ 90
来源：http://dali.yj20258.top/Article/details/gtqxgewxpi.html

Bash ........... 80
来源：http://dali.gogol.net.cn/Article/details/gtrqbxwuez.html

Kotlin ......... 15
来源：http://dali.ybcxt.top/Article/details/gtjvhhodpj.html

Swift .......... 15
来源：http://dali.wangdashe.top/Article/details/gtqasqxwst.html

Lua ............ 10
来源：http://dali.xziqi.cn/Article/details/gthvkclrhc.html

Perl ........... 10
来源：http://dali.sufxvd.cn/Article/details/gtxqtthipq.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gtystxgxuh.html

------------------------------------
来源：http://dali.wangdashe.top/Article/details/gtnprxoyev.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gtfhbvnfjp.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxsulogx.html


<!-- 参考信息 -->