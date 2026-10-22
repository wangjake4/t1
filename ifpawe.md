代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gtcnwuqyoa.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtvzbjcesl.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtvmuihajr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywhdfnwz.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtotyjhnlz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuanzx.com/Article/details/gtyfqbytsw.html

[T48] Perl：正则替换
来源：http://dali.dianchejie.cn/Article/details/gtzfpnatpk.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtqcmpmwvm.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtsdsdhrsf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gtmlshwdpg.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtmyczkofn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gtlnzswsfa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xinyue.icu/Article/details/gtkdzjjoid.html

[T51] Scala：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtwdbedaxg.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtapbaopmb.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtucbjfrzy.html

val a = 1;  var b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtxunmvmac.html

[T53] Scala：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtumsrjdac.html

s"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtoesffrzk.html

[T54] Scala：集合映射
来源：http://dali.zhongyouzk.top/Article/details/gthdyktnyp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtbzzondtx.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtaytpbmbe.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aibaodan.cn/Article/details/gtmxmnuzyr.html

[T56] Scala：样例类
来源：http://dali.zycfv.cn/Article/details/gtiafnqift.html

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gthieyupoy.html

[T57] Scala：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhhvjycy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtpxzvajrl.html

[T58] Scala：函数定义
来源：http://dali.tianlin.xyz/Article/details/gtpqdiygku.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gtecapaolt.html

[T59] Scala：循环
来源：http://dali.vqdsnc.cn/Article/details/gtozpfwixc.html

for (i <- 1 to 10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gtxciuyoau.html

[T60] Scala：折叠
来源：http://dali.c1oappe.top/Article/details/gtsjcgeqof.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gtadldkvsm.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtkrtticoq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtmklozwmf.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtudlvvsow.html

[U01] Py：创建虚拟环境
来源：http://dali.guowangkeji.top/Article/details/gtbkulbpds.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.vqdsnc.cn/Article/details/gtmcnudvtf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gogol.net.cn/Article/details/gtwuvwkvpq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sxryk.cn/Article/details/gtzqeyuxms.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtvvoajyqq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hongshengwenyu.top/Article/details/gtqcxtebba.html

[U04] Py：变量调试打印
来源：http://dali.daria6918.cn/Article/details/gtvhtrgivn.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtuzybrggu.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gtxyepucmg.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtljdjscvp.html

[U06] Py：合并两个字典
来源：http://dali.shangyingyoupin.top/Article/details/gtuxcnxrco.html

{**a, **b}
来源：http://dali.aizwys.cn/Article/details/gtlpmcxzzm.html

[U07] Py：反转字典键值
来源：http://dali.jinqigfzy.top/Article/details/gtxwoupzwy.html

{v: k for k, v in d.items()}
来源：http://dali.aibaodan.cn/Article/details/gtzdohbpmm.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gteqviodlk.html

[y for x in nested for y in x]
来源：http://dali.meibo888.top/Article/details/gtvukbgrlx.html

[U09] Py：字典取最大值的键
来源：http://dali.yj202588.top/Article/details/gtglugfdcp.html

max(d, key=d.get)
来源：http://dali.jinqigufen.top/Article/details/gtixykvlth.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gtpvwamait.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.havefunace.top/Article/details/gtzbzanoig.html

[U11] Py：生成器表达式
来源：http://dali.ydzc1.top/Article/details/gtletxkpdn.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtwesoifrb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hysaishi.cn/Article/details/gtlsitmqci.html

Counter(arr).most_common(3)
来源：http://dali.xuetiantiany.cn/Article/details/gtcnqjkeln.html

[U13] Py：固定长度队列
来源：http://dali.jqgfzy.top/Article/details/gtqzkyfrmx.html

deque(maxlen=10)
来源：http://dali.gotoacloud.top/Article/details/gttdyeenyn.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdujigdrg.html

defaultdict(list)
来源：http://dali.yj202588.top/Article/details/gtuoxaiylh.html

[U15] Py：高精度计时
来源：http://dali.jiagoushi.top/Article/details/gtnfisiych.html

t = time.perf_counter()
来源：http://dali.yj20258888.top/Article/details/gtbttzaxhb.html

[U16] Py：命令行参数解析
来源：http://dali.hammf.cn/Article/details/gtrgaxabia.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.daria6918.cn/Article/details/gtfszilmws.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gtkmouccjd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtzzouaoka.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gtlqaubyec.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gthvsobxqy.html

[U19] Py：正则替换带回调
来源：http://dali.gogol.net.cn/Article/details/gtvdmxolwf.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gttymvnfsp.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gtihatgbkf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.vqdsnc.cn/Article/details/gtkjaspyiz.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtbrmvoarb.html

@contextlib.contextmanager
来源：http://dali.xuanzx.com/Article/details/gtqklpxxcn.html

[U22] Py：矩阵转置
来源：http://dali.tianlin.xyz/Article/details/gtrvkvsccn.html

list(zip(*m))
来源：http://dali.yueranfly.top/Article/details/gtqqiyrunv.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopfcqnye.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtytgcqilk.html

[U24] Py：路径操作
来源：http://dali.vqdsnc.cn/Article/details/gtlijrrujs.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhiwuduotai.top/Article/details/gthfbkunhk.html

[U25] Py：CSV 按字典读
来源：http://dali.cdnleiting.top/Article/details/gtyufvhenq.html

csv.DictReader(f)
来源：http://dali.yj20258888.top/Article/details/gtqwtaauln.html

[U26] Py：并发下载
来源：http://dali.snrcjt.cn/Article/details/gtgbkcubwo.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.chenlongwang.top/Article/details/gtulhjlhgp.html

[U27] Py：异步 HTTP
来源：http://dali.xinyue.icu/Article/details/gtldxkiwzx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gtldhhaknl.html

[U28] Py：类型别名
来源：http://dali.svipenyu.cn/Article/details/gtoxtqpsgd.html

UserId = int
来源：http://dali.xziqi.cn/Article/details/gtsqzzepce.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtqcepkvrp.html

@property 与 @x.setter 配合
来源：http://dali.snrcjt.cn/Article/details/gtsqxjalwo.html

[U30] Py：数据类
来源：http://dali.ybcxt.top/Article/details/gttmfztxwj.html

@dataclass(slots=True)
来源：http://dali.quarkkingdee.top/Article/details/gtldzpegdw.html

[U31] Py：单测
来源：http://dali.pengpengdd.cyou/Article/details/gtrpdrdkbn.html

python -m pytest -q
来源：http://dali.zycfv.cn/Article/details/gtwgbkzjmz.html

[U32] Py：代码格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtwlbuxaov.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gtrhfrpbur.html

[U33] Py：打包发布
来源：http://dali.tian-w.cn/Article/details/gtduilhxst.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.smart0.xyz/Article/details/gtwkvajehc.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gtslnsrhix.html

chardet.detect(raw)
来源：http://dali.sufxvd.cn/Article/details/gtlurzrfpy.html

[U35] Py：发送邮件
来源：http://dali.cqqwz.cn/Article/details/gtmvhhncdj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.kuanghao11.cn/Article/details/gtlrypxfxi.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtglepsmxq.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gtlpsoqute.html

[U37] Py：读写 Excel
来源：http://dali.xylfe.cn/Article/details/gtqxxlefhp.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtvluhkfbb.html

[U38] Py：获取脚本所在目录
来源：http://dali.sweek.top/Article/details/gtasptiinv.html

Path(__file__).resolve().parent
来源：http://dali.gaohongyu789.top/Article/details/gtmvuorkwg.html

[U39] Py：判断是否在交互环境
来源：http://dali.xziqi.cn/Article/details/gtmqeyvpqb.html

sys.stdout.isatty()
来源：http://dali.316326.xyz/Article/details/gtvdankghx.html

[U40] Py：打印到标准错误
来源：http://dali.redwolf501.top/Article/details/gtsmwykzpi.html

print("err", file=sys.stderr)
来源：http://dali.fzhhl.top/Article/details/gtxmabmqdz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hammf.cn/Article/details/gtppgykkmf.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtsmsehtoe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxuanxn.top/Article/details/gthnppwpxb.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.ydzc1.top/Article/details/gtjxnmdtnd.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gtengljpjr.html

namespace App\Http;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrnodkifl.html

[U44] PHP：开启严格类型
来源：http://dali.cashguo.top/Article/details/gtlwjtqfkr.html

declare(strict_types=1);
来源：http://dali.gotoacloud.top/Article/details/gtmeneyykn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.iojbl.cn/Article/details/gtxyozivhh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtudogenzk.html

[U46] PHP：可空类型
来源：http://dali.yj20258888.top/Article/details/gtfptopcpd.html

?string $name = null
来源：http://dali.tianlin.xyz/Article/details/gtvieydjnh.html

[U47] PHP：联合类型
来源：http://dali.jyoumei.cn/Article/details/gtribjzfbm.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtnrgfzwnv.html

[U48] PHP：纯枚举
来源：http://dali.andypj.xyz/Article/details/gtcojhkgxc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yongpay.top/Article/details/gtvicytepm.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gtzmqdlslr.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtmryejfwv.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gtsnlqfggk.html

public function __construct(private int $id) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtslqotbzv.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gtadicuqtt.html

[$a, $b] = $arr;
来源：http://dali.cdnleiting.top/Article/details/gthrlmiyqq.html

[U52] PHP：箭头函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjcfrhcv.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtkvwoapte.html

[U53] PHP：空合并运算符
来源：http://dali.shangyingyoupin.top/Article/details/gtwhtigxoo.html

$v = $a ?? $b ?? "default";
来源：http://dali.quarkkingdee.top/Article/details/gthkgouygf.html

[U54] PHP：空安全调用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbbogxjr.html

$obj?->method()
来源：http://dali.ydzc1.top/Article/details/gtqozyfrud.html

[U55] PHP：match 表达式
来源：http://dali.yongpay.top/Article/details/gtryydjwkc.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtudzledfy.html

[U56] PHP：命名参数
来源：http://dali.mhx1999.top/Article/details/gtujfowewo.html

f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtbpsfryvg.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtesttdcgo.html

"值: {$a}"
来源：http://dali.yj20258888.top/Article/details/gtvckmnqhf.html

[U58] PHP：数组三件套
来源：http://dali.gogol.net.cn/Article/details/gtggnggrwx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.quarkkingdee.top/Article/details/gtcjeyuvqd.html

[U59] PHP：自定义排序
来源：http://dali.jinqigfzy.top/Article/details/gtvwjudgcu.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.fzhhl.top/Article/details/gtxgebxboy.html

[U60] PHP：JSON 编解码
来源：http://dali.quarkkingdee.top/Article/details/gtpjbhnrsg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.tianlin.xyz/Article/details/gtrwcdialy.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtxrudckom.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yangfankeji.com/Article/details/gtbbtuelgy.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gtdnncpqcv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gthbegysfa.html

[U63] PHP：文件读写
来源：http://dali.316326.xyz/Article/details/gtztvopidx.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.guannengcc.top/Article/details/gtlsffqbsm.html

[U64] PHP：目录遍历
来源：http://dali.hysaishi.cn/Article/details/gththszicj.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gtmokcurtv.html

[U65] PHP：会话
来源：http://dali.yangfankeji.com/Article/details/gtuytotiel.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtjpykhqed.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtiwsbkegm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cheryme.top/Article/details/gtcnazywep.html

[U67] PHP：处理文件上传
来源：http://dali.yvedp.cn/Article/details/gtqmzedqih.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtbvxdtbtl.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gtubayonti.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzefevvu.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gtaoxhxrdu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yanxiufei.cn/Article/details/gttqcswuui.html

[U70] PHP：PDO 事务
来源：http://dali.316326.xyz/Article/details/gtxgaobmrd.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hammf.cn/Article/details/gtnqenzjtz.html

[U71] PHP：抛出异常
来源：http://dali.yanxiufei.cn/Article/details/gtqxcgfibd.html

throw new RuntimeException("失败", 500);
来源：http://dali.mhx1999.top/Article/details/gtsevrfkbn.html

[U72] PHP：写错误日志
来源：http://dali.gaohongyu789.top/Article/details/gtfeldwmqx.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sweek.top/Article/details/gtmakswmyo.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgeklhqx.html

parse_ini_file("config.ini", true)
来源：http://dali.yuanzhike.top/Article/details/gtwdiobwrj.html

[U74] PHP：读取环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtngmuizak.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gtrsagtztz.html

[U75] PHP：依赖注入
来源：http://dali.zycfv.cn/Article/details/gtzfuebeux.html

composer require psr/container
来源：http://dali.shuidangran.top/Article/details/gtxihfdolc.html

[U76] PHP：简单路由
来源：http://dali.aizwys.cn/Article/details/gtlfeeusji.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.svipenyu.cn/Article/details/gtxnrepkit.html

[U77] PHP：模板渲染
来源：http://dali.nwbrower.top/Article/details/gtsflokjbb.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gtqaiiashi.html

[U78] PHP：单元测试
来源：http://dali.aibaodan.cn/Article/details/gthwnrxzoy.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtcpgmzdds.html

[U79] PHP：静态分析
来源：http://dali.wangdashe.top/Article/details/gtrertdgrj.html

composer require --dev phpstan/phpstan
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvuwkgug.html

[U80] PHP：代码规范修复
来源：http://dali.jyoumei.cn/Article/details/gtxaipgzel.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gtlpvxypxf.html

[U81] JS：初始化项目
来源：http://dali.zhiwuduotai.top/Article/details/gtosurgext.html

npm init -y;  npm i express
来源：http://dali.shangyingyoupin.top/Article/details/gtblcbunon.html

[U82] JS：package.json 脚本
来源：http://dali.nanxuanxn.top/Article/details/gtanzerkyg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zdqjudy.top/Article/details/gtdvvvshgl.html

[U83] JS：ES Module 导入导出
来源：http://dali.gzhubu.top/Article/details/gtvfkcrusc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ydzc1.top/Article/details/gtceczqkic.html

[U84] JS：CommonJS 写法
来源：http://dali.cheryme.top/Article/details/gturpbdphe.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhixingplan.top/Article/details/gtddrwifjq.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtggssrdvo.html

a?.b?.c
来源：http://dali.9152youxi.cn/Article/details/gtyqywjpch.html

[U86] JS：空值合并
来源：http://dali.pengpengdd.cyou/Article/details/gtmyslyzme.html

a ?? b
来源：http://dali.gaohongyu789.top/Article/details/gttvqmvdqy.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtarsxwqhz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gtpfewspsc.html

[U88] JS：对象展开合并
来源：http://dali.xuetiantiany.cn/Article/details/gtdbvaspyo.html

{ ...a, ...b }
来源：http://dali.chenzaomai.com/Article/details/gtfcmqhkvt.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtpcgrafqr.html

[...new Set(arr)]
来源：http://dali.guannengcc.top/Article/details/gttisnznhb.html

[U90] JS：数字数组排序
来源：http://dali.cdnleiting.top/Article/details/gtalhnxkrk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hywenlv.cn/Article/details/gtjaesbloc.html

[U91] JS：对象键值遍历
来源：http://dali.havefunace.top/Article/details/gtuyvbpbqy.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhongyouzk.top/Article/details/gtnsllduat.html

[U92] JS：深拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtkfuudinq.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtgmeqgbnc.html

[U93] JS：模板字符串
来源：http://dali.jqgufenzy.top/Article/details/gturgkyspl.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtnvxnupuw.html

[U94] JS：箭头函数
来源：http://dali.sysykeji.top/Article/details/gtjstpcmkj.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gtcswqcqnr.html

[U95] JS：Promise 包装
来源：http://dali.svipenyu.cn/Article/details/gtjqbsxztv.html

new Promise((resolve, reject) => {})
来源：http://dali.ehwqpu.com/Article/details/gteiiqdszh.html

[U96] JS：async/await 与异常
来源：http://dali.gzhubu.top/Article/details/gtiuqgwyyy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhongyouzk.top/Article/details/gtminwtaym.html

[U97] JS：并发请求
来源：http://dali.xylfe.cn/Article/details/gtrwsomaoa.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.dianchejie.cn/Article/details/gthrwgcvjl.html

[U98] JS：fetch 带 JSON
来源：http://dali.cucudq.cn/Article/details/gtrcxparmf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yueranfly.top/Article/details/gtiogwjqqa.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtdaazipmu.html

el.addEventListener("click", e => {})
来源：http://dali.pengpengdd.cyou/Article/details/gtetuknqph.html

[U100] JS：DOM 查询
来源：http://dali.yangfankeji.com/Article/details/gtdjqiknzc.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gteisvytrb.html

[U101] JS：classList 操作
来源：http://dali.mhx1999.top/Article/details/gtipvcpyqc.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtkibfuqtg.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gtclfezjed.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.redwolf501.top/Article/details/gtaahjohss.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gtcipaewwm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtibqsupif.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gtxiuvcziy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gtvdggnxst.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gtwlzvshhi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yonumen.top/Article/details/gtsuepgpqi.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtcrjwwvdg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zycfv.cn/Article/details/gtdfdjgjbx.html

[U107] JS：数字千分位
来源：http://dali.fzhhl.top/Article/details/gtkymqcjmn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhongyouzk.top/Article/details/gtmxkirglc.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gtndwnxgzg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yangfankeji.com/Article/details/gteoxbauxk.html

[U109] JS：数组分组
来源：http://dali.zhixingplan.top/Article/details/gtxzfmsehz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tianlin.xyz/Article/details/gtvgrcrsgz.html

[U110] JS：数组分块
来源：http://dali.hysaishi.cn/Article/details/gthdqwrlzp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtedjnhrhi.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtbqwtsmta.html

new Map(Object.entries(obj))
来源：http://dali.fzhhl.top/Article/details/gtqwiucxet.html

[U112] JS：字符串补位
来源：http://dali.zhixingplan.top/Article/details/gtywcsmtrk.html

"7".padStart(3, "0")
来源：http://dali.xuanzx.com/Article/details/gtqotdvbud.html

[U113] JS：正则替换全部
来源：http://dali.dianchejie.cn/Article/details/gthqthoxgi.html

s.replaceAll("a", "b")
来源：http://dali.daxiang520.top/Article/details/gtozpjpkye.html

[U114] JS：JSON 深比较
来源：http://dali.guannengcc.top/Article/details/gtpsextdfa.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.fzhhl.top/Article/details/gtgllvjxpv.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtvouzlszw.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gtohyxmddw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.sweek.top/Article/details/gtaholwwpc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.svipenyu.cn/Article/details/gtrrmqmnzb.html

[U117] JS：单元测试
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfxfsfbna.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gtpmvqlqql.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpdqndfyj.html

npm i -D vite;  npx vite
来源：http://dali.hammf.cn/Article/details/gtfvocgsog.html

[U119] JS：生产构建
来源：http://dali.yueranfly.top/Article/details/gtuxvflplq.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gtulrxrlii.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xinyue.icu/Article/details/gtrlcjeeel.html

import.meta.env.VITE_API_URL
来源：http://dali.yangfankeji.com/Article/details/gtqhlgfbsh.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtueszhlho.html

统计汇总
来源：http://dali.zhixingplan.top/Article/details/gtwpzbqzsl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoykuizlj.html

按语言统计（条）：
来源：http://dali.cashguo.top/Article/details/gtfhujxmgx.html

Python ......... 252
来源：http://dali.yanxiufei.cn/Article/details/gthmwodwbq.html

PHP ............ 252
来源：http://dali.xziqi.cn/Article/details/gtuaovnsdb.html

JavaScript ..... 252
来源：http://dali.jyoumei.cn/Article/details/gtvdfitbhd.html

TypeScript ..... 212
来源：http://dali.hammf.cn/Article/details/gtpneanjys.html

Java ........... 212
来源：http://dali.meibo888.top/Article/details/gtkokoadju.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gtdswlatlb.html

Ruby ........... 212
来源：http://dali.wangdashe.top/Article/details/gtfstgmmmx.html

C# ............. 212
来源：http://dali.xziqi.cn/Article/details/gtsedtsugj.html

C .............. 30
来源：http://dali.yuxming.cn/Article/details/gtpxkuzwkp.html

C++ ............ 30
来源：http://dali.daxiang520.top/Article/details/gtwnmzqrnw.html

SQL ............ 90
来源：http://dali.wangdashe.top/Article/details/gtawythxlo.html

Bash ........... 80
来源：http://dali.wangshuangyany.cn/Article/details/gtucugfsjc.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtmgkkykud.html

Swift .......... 15
来源：http://dali.c1oappe.top/Article/details/gtcxzwytvc.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gtcrifsett.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtnezpdkcu.html

Scala .......... 10
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhrlemgy.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtsbrahvod.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtdvyfidlr.html

按章节统计：
来源：http://dali.sxryk.cn/Article/details/gtcfcqvucs.html


<!-- 参考信息 -->