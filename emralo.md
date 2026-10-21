代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gtsfyokkwx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.sxryk.cn/Article/details/gtuvyprdow.html

[T48] Perl：正则替换
来源：http://dali.ydzc1.top/Article/details/gtpwtqeyqk.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtkviuebvw.html

[T49] Perl：函数
来源：http://dali.vqdsnc.cn/Article/details/gtaydrkwji.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gtwfavmevh.html

[T50] Perl：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtnplfgoza.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtwfygfrtt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtlrxpmoxd.html

[T51] Scala：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtfnadhinl.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtwjaizdic.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtpajpmnzy.html

val a = 1;  var b = 2
来源：http://dali.jqgfzy.top/Article/details/gtkuvyemlg.html

[T53] Scala：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtqcstatvn.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtnvdkbrhp.html

[T54] Scala：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtemkbbetb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuxming.cn/Article/details/gtenkjjuic.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtsshttppy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.haohaochexian.top/Article/details/gtfmkbucgp.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtkwzezqca.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gthtmcbzvl.html

[T57] Scala：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtnxrmkmil.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtaoqnkgtf.html

[T58] Scala：函数定义
来源：http://dali.yj20258888.top/Article/details/gtqhwozxsi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gttztqjkai.html

[T59] Scala：循环
来源：http://dali.yuanzhike.top/Article/details/gtfcfyylgf.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtvpypfnme.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtlhvdeqfn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.dianchejie.cn/Article/details/gttlwqsvii.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtlzrrjfbm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtsrizvlkc.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gttpmahzoa.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtozsucsaz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gteaouypzh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gtaertryfl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmemikoll.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gtffrizurr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tianlin.xyz/Article/details/gtgawgpblg.html

[U04] Py：变量调试打印
来源：http://dali.dianchejie.cn/Article/details/gtctsnrpbt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.birdmap.top/Article/details/gtvcuzvgqa.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gtnjrrbgkw.html

list(dict.fromkeys(arr))
来源：http://dali.quarkkingdee.top/Article/details/gtmtwvynsn.html

[U06] Py：合并两个字典
来源：http://dali.xuanzx.com/Article/details/gtzexmwwyv.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gtyttnmfmd.html

[U07] Py：反转字典键值
来源：http://dali.hongshengwenyu.top/Article/details/gtosvighrh.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtsqkzsvqi.html

[U08] Py：展平二维列表
来源：http://dali.zdqjudy.top/Article/details/gtbjxfasgb.html

[y for x in nested for y in x]
来源：http://dali.zdqjudy.top/Article/details/gtwvczbmiy.html

[U09] Py：字典取最大值的键
来源：http://dali.daxiang520.top/Article/details/gtkgrlxhcb.html

max(d, key=d.get)
来源：http://dali.c1oappe.top/Article/details/gtxktqvnra.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtxyvpuzob.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hongshengwenyu.top/Article/details/gtoonidflu.html

[U11] Py：生成器表达式
来源：http://dali.chenlongwang.top/Article/details/gtcsgevfhs.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrtrrjzuy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zdqjudy.top/Article/details/gttakdluao.html

Counter(arr).most_common(3)
来源：http://dali.daxiang520.top/Article/details/gtvxynibru.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gtygwvfnhp.html

deque(maxlen=10)
来源：http://dali.svipenyu.cn/Article/details/gtpwheghiz.html

[U14] Py：分组收集到列表
来源：http://dali.shangyingyoupin.top/Article/details/gtdnramtts.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtyraglyrn.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gtqoayidho.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbumvyon.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtezyueyga.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtautgiled.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdgtqfmt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cashguo.top/Article/details/gtvenymush.html

[U18] Py：预编译正则
来源：http://dali.sweek.top/Article/details/gtjyuugoij.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gtiaqjsjow.html

[U19] Py：正则替换带回调
来源：http://dali.vqdsnc.cn/Article/details/gtiexuhwmx.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guowangkeji.top/Article/details/gtmdhsgozo.html

[U20] Py：缓存函数结果
来源：http://dali.316326.xyz/Article/details/gtvreeusbk.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cheryme.top/Article/details/gtpcgqsdzf.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhiwuduotai.top/Article/details/gtitukbvlu.html

@contextlib.contextmanager
来源：http://dali.zycfv.cn/Article/details/gteqtablwk.html

[U22] Py：矩阵转置
来源：http://dali.shuidangran.top/Article/details/gturthjiwa.html

list(zip(*m))
来源：http://dali.tian-w.cn/Article/details/gtcuvpovjh.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtwmdukory.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gtibxdspja.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gtsrapwtzq.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gtrqbggypd.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gttuwxfmfz.html

csv.DictReader(f)
来源：http://dali.feifeiyinyue.top/Article/details/gtevmbhzdw.html

[U26] Py：并发下载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrignkcj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nwbrower.top/Article/details/gtuecporqa.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtrqwwkrkk.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gteduuuurf.html

[U28] Py：类型别名
来源：http://dali.bjfxy.top/Article/details/gtxhntcvlv.html

UserId = int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsotgcpxr.html

[U29] Py：属性校验
来源：http://dali.nanxinkj.top/Article/details/gtuxyxigif.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtdxbfkxyq.html

[U30] Py：数据类
来源：http://dali.dashuyun.cn/Article/details/gtcryqxfnx.html

@dataclass(slots=True)
来源：http://dali.hnqzz.top/Article/details/gtdpwqzyqj.html

[U31] Py：单测
来源：http://dali.ehwqpu.com/Article/details/gtljncqrjy.html

python -m pytest -q
来源：http://dali.sysykeji.top/Article/details/gtoeecjsmm.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtyegxowbq.html

ruff format . && ruff check --fix .
来源：http://dali.daria6918.cn/Article/details/gtkvsjghtc.html

[U33] Py：打包发布
来源：http://dali.ydzc1.top/Article/details/gtfpehtjuo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtibqqthom.html

[U34] Py：判断编码
来源：http://dali.andypj.xyz/Article/details/gtlwvljusw.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gtvpiuqcdy.html

[U35] Py：发送邮件
来源：http://dali.ydzc1.top/Article/details/gtgjvktdju.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nwbrower.top/Article/details/gteubwnemy.html

[U36] Py：定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtqdfbamjj.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gtzaqviyrj.html

[U37] Py：读写 Excel
来源：http://dali.jianghu66.top/Article/details/gtopimcqnt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jiagoushi.top/Article/details/gtfcfshiiq.html

[U38] Py：获取脚本所在目录
来源：http://dali.hnxiangtu.top/Article/details/gtmghkczrp.html

Path(__file__).resolve().parent
来源：http://dali.dashuyun.cn/Article/details/gtgcituidq.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhongyouzk.top/Article/details/gtooeizooe.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gtmidjjwvm.html

[U40] Py：打印到标准错误
来源：http://dali.xuetiantiany.cn/Article/details/gtxglikvki.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gtnbukjtml.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258888.top/Article/details/gtotxihevp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ivvv.top/Article/details/gtcfkubfzh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cashguo.top/Article/details/gtnzcpvkai.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yuanzhike.top/Article/details/gtrarqigaz.html

[U43] PHP：声明命名空间
来源：http://dali.ybcxt.top/Article/details/gtlamrjohj.html

namespace App\Http;
来源：http://dali.c1oappe.top/Article/details/gtssoekwsc.html

[U44] PHP：开启严格类型
来源：http://dali.hywenlv.cn/Article/details/gtpemeonev.html

declare(strict_types=1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvqeuhzq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtrzxhehaa.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gthiifcqez.html

[U46] PHP：可空类型
来源：http://dali.c1oappe.top/Article/details/gtkcdtixvi.html

?string $name = null
来源：http://dali.jiagoushi.top/Article/details/gtymwojatw.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gtoscojilm.html

int|string $id
来源：http://dali.zdqjudy.top/Article/details/gtiaxpnczp.html

[U48] PHP：纯枚举
来源：http://dali.jqgfzy.top/Article/details/gtqjcthclu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gtsegkgdns.html

[U49] PHP：只读属性
来源：http://dali.smart0.xyz/Article/details/gtslnxchyu.html

public readonly string $name
来源：http://dali.quarkkingdee.top/Article/details/gtznkcezpo.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzproxco.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtjwqxzypd.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtrueknnfc.html

[$a, $b] = $arr;
来源：http://dali.feifeiyinyue.top/Article/details/gtmgmlhegw.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtiahwmebq.html

$double = fn($x) => $x * 2;
来源：http://dali.mhx1999.top/Article/details/gtibfczlxz.html

[U53] PHP：空合并运算符
来源：http://dali.quarkkingdee.top/Article/details/gtrcvurdzr.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtdfagkdch.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtrnyxirsj.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gttwouefdy.html

[U55] PHP：match 表达式
来源：http://dali.chenlongwang.top/Article/details/gtpddbkndf.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdcitlrc.html

[U56] PHP：命名参数
来源：http://dali.tianlin.xyz/Article/details/gtyajgwbpg.html

f(a: 1, b: 2)
来源：http://dali.fengsongda.top/Article/details/gtbibvsjzf.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtrdzsqltd.html

"值: {$a}"
来源：http://dali.zhengqikj.top/Article/details/gthyauupdz.html

[U58] PHP：数组三件套
来源：http://dali.316326.xyz/Article/details/gtbhwuloyp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgufenzy.top/Article/details/gtertzokra.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gtgwwrvcnf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hywenlv.cn/Article/details/gtygagyhvs.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtnpesqpol.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtbfbygppa.html

[U61] PHP：正则
来源：http://dali.gogol.net.cn/Article/details/gtgyzkqqsm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtsrvajieu.html

[U62] PHP：日期对象
来源：http://dali.pycfn.com/Article/details/gtbhrrcozc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jianghu66.top/Article/details/gtkwdaxfio.html

[U63] PHP：文件读写
来源：http://dali.gogol.net.cn/Article/details/gtrrkxusyn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxinkj.top/Article/details/gtlljtzwgj.html

[U64] PHP：目录遍历
来源：http://dali.xylfe.cn/Article/details/gtltpnhvzv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.bjfxy.top/Article/details/gtdwcwgmty.html

[U65] PHP：会话
来源：http://dali.ybcxt.top/Article/details/gttxrabypk.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.c1oappe.top/Article/details/gtjzbpgfyj.html

[U66] PHP：设置 Cookie
来源：http://dali.wangshuangyany.cn/Article/details/gtlpwjmawm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yongpay.top/Article/details/gtlaawcwcn.html

[U67] PHP：处理文件上传
来源：http://dali.nanxuanxn.top/Article/details/gtnobxfroh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gtoachoifd.html

[U68] PHP：PDO 连接
来源：http://dali.andypj.xyz/Article/details/gtsugpdxmf.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gaohongyu789.top/Article/details/gtlqhbwalz.html

[U69] PHP：PDO 预处理
来源：http://dali.zhiwuduotai.top/Article/details/gtpxstxpwm.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.fzhhl.top/Article/details/gtesfedsdp.html

[U70] PHP：PDO 事务
来源：http://dali.hywenlv.cn/Article/details/gtykrlbhod.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gteqtqymiz.html

[U71] PHP：抛出异常
来源：http://dali.cucudq.cn/Article/details/gtzfmqmbra.html

throw new RuntimeException("失败", 500);
来源：http://dali.nanxuanxn.top/Article/details/gtrpnpadxz.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanseaivv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.meibo888.top/Article/details/gtgxrmhypw.html

[U73] PHP：读取 ini 配置
来源：http://dali.tianlin.xyz/Article/details/gtuaodswqg.html

parse_ini_file("config.ini", true)
来源：http://dali.ppjwa.cn/Article/details/gtssukgpbn.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtvwpaakkr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gtmnsdbcit.html

[U75] PHP：依赖注入
来源：http://dali.chenlongwang.top/Article/details/gtycgmfegv.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gtyperpebk.html

[U76] PHP：简单路由
来源：http://dali.shzxlz.cn/Article/details/gtgwxdyjvf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nwbrower.top/Article/details/gtczjxdhkr.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtmkzhhpfz.html

composer require twig/twig
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqltdhiiu.html

[U78] PHP：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gttogeowwl.html

composer require --dev phpunit/phpunit
来源：http://dali.ivvv.top/Article/details/gtptbvsrkh.html

[U79] PHP：静态分析
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtsghelq.html

composer require --dev phpstan/phpstan
来源：http://dali.shangyingyoupin.top/Article/details/gtozbeubva.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gtcdiayihc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.feifeiyinyue.top/Article/details/gtrktnocer.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gttortyhbp.html

npm init -y;  npm i express
来源：http://dali.sxryk.cn/Article/details/gtylneoffr.html

[U82] JS：package.json 脚本
来源：http://dali.chenzaomai.com/Article/details/gtykejorzg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtzpbipkcd.html

[U83] JS：ES Module 导入导出
来源：http://dali.jiagoushi.top/Article/details/gtsqeegxpe.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlieulohy.html

[U84] JS：CommonJS 写法
来源：http://dali.tianlin.xyz/Article/details/gthcaojkce.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtzmswymft.html

[U85] JS：可选链
来源：http://dali.gogol.net.cn/Article/details/gtoxkirlqv.html

a?.b?.c
来源：http://dali.hnqzz.top/Article/details/gtwbewebxd.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gtkwvhusxz.html

a ?? b
来源：http://dali.nanxuanxn.top/Article/details/gtaroicyir.html

[U87] JS：解构默认值
来源：http://dali.jinqigfzy.top/Article/details/gtpteewtrk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xziqi.cn/Article/details/gtbeyvsfje.html

[U88] JS：对象展开合并
来源：http://dali.andypj.xyz/Article/details/gtdpgspdun.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtaxoocxmn.html

[U89] JS：数组去重
来源：http://dali.jinqigufen.top/Article/details/gtlzexibvc.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gtzmreueqf.html

[U90] JS：数字数组排序
来源：http://dali.ppjwa.cn/Article/details/gtyxrswgpk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.haohaochexian.top/Article/details/gtgklesccu.html

[U91] JS：对象键值遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbjbpbmg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtxsqbyvva.html

[U92] JS：深拷贝
来源：http://dali.gogol.net.cn/Article/details/gtavxygbis.html

structuredClone(obj)
来源：http://dali.xylfe.cn/Article/details/gtypelwozd.html

[U93] JS：模板字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtqbpdyvlw.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gteucdhvcx.html

[U94] JS：箭头函数
来源：http://dali.wangdashe.top/Article/details/gtqcpjghxo.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtvpovsxmt.html

[U95] JS：Promise 包装
来源：http://dali.xinyue.icu/Article/details/gtsjxlcsjm.html

new Promise((resolve, reject) => {})
来源：http://dali.xuetiantiany.cn/Article/details/gtqlrlfhah.html

[U96] JS：async/await 与异常
来源：http://dali.bjfxy.top/Article/details/gtljjnaodm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtanximuqq.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvzqesfm.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gtphrovvjj.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gtmzvoihjp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gotoacloud.top/Article/details/gtrujlkxkq.html

[U99] JS：事件监听
来源：http://dali.daxiang520.top/Article/details/gtryeggsat.html

el.addEventListener("click", e => {})
来源：http://dali.ppjwa.cn/Article/details/gtwbfixpis.html

[U100] JS：DOM 查询
来源：http://dali.jqgufenzy.top/Article/details/gtuboemhjx.html

document.querySelector(".item")
来源：http://dali.yj20258888.top/Article/details/gtwxbrknjt.html

[U101] JS：classList 操作
来源：http://dali.shangyingyoupin.top/Article/details/gtcclglmxc.html

el.classList.toggle("active")
来源：http://dali.nwbrower.top/Article/details/gtmuwfmukq.html

[U102] JS：本地存储
来源：http://dali.fzhhl.top/Article/details/gtjbidycrj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.chenlongwang.top/Article/details/gtuwmkdgme.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gtylrpwqjd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jianghu66.top/Article/details/gtsofreupf.html

[U104] JS：防抖
来源：http://dali.yonumen.top/Article/details/gtjxkvccuy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gtneugbdmd.html

[U105] JS：节流
来源：http://dali.yueranfly.top/Article/details/gtcbqxbpfb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cucudq.cn/Article/details/gtjdxndegw.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtayqumbit.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hammf.cn/Article/details/gtjvchmmfu.html

[U107] JS：数字千分位
来源：http://dali.aizwys.cn/Article/details/gtbrwunaru.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.havefunace.top/Article/details/gttnhdzyep.html

[U108] JS：随机整数
来源：http://dali.0kj1m.cn/Article/details/gtlswgnioz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.havefunace.top/Article/details/gtnhjdkvjm.html

[U109] JS：数组分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtaawrgror.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfujielzr.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtajrvsgqa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ybcxt.top/Article/details/gtbzruxgqj.html

[U111] JS：对象转 Map
来源：http://dali.snrcjt.cn/Article/details/gtxjpuphmt.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtanxlkkrq.html

[U112] JS：字符串补位
来源：http://dali.gzhubu.top/Article/details/gtkhgaviqs.html

"7".padStart(3, "0")
来源：http://dali.shanyushiyangtech.top/Article/details/gturvzrveq.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gtehpsuclc.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtudzjaiij.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gttyhvmovq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cucudq.cn/Article/details/gtqhjxiitk.html

[U115] JS：生成 UUID
来源：http://dali.gzhubu.top/Article/details/gtmkqntgyh.html

crypto.randomUUID()
来源：http://dali.guannengcc.top/Article/details/gtwfojxjkt.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nwbrower.top/Article/details/gtaohtnlzk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sysykeji.top/Article/details/gthurtdyff.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtmpmyaxid.html

npm i -D vitest;  npx vitest
来源：http://dali.yonumen.top/Article/details/gtaiydxduj.html

[U118] JS：开发服务器
来源：http://dali.jlsjyb.cn/Article/details/gtqwwrpqko.html

npm i -D vite;  npx vite
来源：http://dali.ehwqpu.com/Article/details/gtwoptuwfr.html

[U119] JS：生产构建
来源：http://dali.xziqi.cn/Article/details/gtwmnyvvwq.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtzapjljej.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmutzvsln.html

import.meta.env.VITE_API_URL
来源：http://dali.ppjwa.cn/Article/details/gtwfdfruej.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gticzcpjzb.html

统计汇总
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjkqaizm.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtccizoozi.html

按语言统计（条）：
来源：http://dali.ehwqpu.com/Article/details/gthlkwjvip.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtdcrwconc.html

PHP ............ 252
来源：http://dali.wangshuangyany.cn/Article/details/gtdtrjiaoc.html

JavaScript ..... 252
来源：http://dali.fzhhl.top/Article/details/gtqbvfpzbb.html

TypeScript ..... 212
来源：http://dali.hnqzz.top/Article/details/gtqanocfpz.html

Java ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtswvpeazb.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gtpfzydfzs.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gtbixfnnrk.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtispwdnmu.html

C .............. 30
来源：http://dali.meibo888.top/Article/details/gtkmvxaptj.html

C++ ............ 30
来源：http://dali.cqqwz.cn/Article/details/gtzalzkwag.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtayrlrjbb.html

Bash ........... 80
来源：http://dali.yj20258888.top/Article/details/gtmxutroea.html

Kotlin ......... 15
来源：http://dali.cheryme.top/Article/details/gtdyuuanti.html

Swift .......... 15
来源：http://dali.shuidangran.top/Article/details/gtyoxrbngr.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtwlxcinqj.html

Perl ........... 10
来源：http://dali.meibo888.top/Article/details/gtkqdagfrh.html

Scala .......... 10
来源：http://dali.smart0.xyz/Article/details/gtgbiwnpvr.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gtnpyvcphr.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtsjicqasu.html

按章节统计：
来源：http://dali.316326.xyz/Article/details/gtuqxnqahb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.svipenyu.cn/Article/details/gtqqorddee.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtirmaieha.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtqgbbsnnm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gtuywbyqeo.html


<!-- 参考信息 -->