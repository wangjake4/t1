代发 wailian999

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtmopuzdln.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtmtnkigeb.html

[T50] Perl：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gthhpiwpuf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtgvfyvhww.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxinkj.top/Article/details/gtnielpzww.html

[T51] Scala：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtnlwkgdjf.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsxyxieq.html

[T52] Scala：变量
来源：http://dali.shzxlz.cn/Article/details/gtbbvecnmi.html

val a = 1;  var b = 2
来源：http://dali.iojbl.cn/Article/details/gtmkovblpd.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxmbizfk.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtraqhupha.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtehjcvpas.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zycfv.cn/Article/details/gtfigibrjf.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtzgemjulj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtpwrjffci.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtmnssieqb.html

case class User(name: String, age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtobwgltix.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtcvoecbxf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gttzftamhq.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtwgcnulsi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtuafdxobb.html

[T59] Scala：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmglgotlz.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtlyzgkwif.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gtcydckgvm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtughzavvv.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtcesswgcq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtfhwlufyx.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmvzlzsiu.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtipbqrjqy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtyykzkomj.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtaknkxmhq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gtjfkkdeso.html

[U03] Py：加载 .env 配置
来源：http://dali.yvedp.cn/Article/details/gtknjlevuq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtzjzlumyc.html

[U04] Py：变量调试打印
来源：http://dali.aibaodan.cn/Article/details/gtdpazjcqp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhongyouzk.top/Article/details/gtzcfdqtaw.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigfzy.top/Article/details/gtphmemitf.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtcvbzazdd.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtvkvwzxgs.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtkjytatxh.html

[U07] Py：反转字典键值
来源：http://dali.gotoacloud.top/Article/details/gtqpahvrgs.html

{v: k for k, v in d.items()}
来源：http://dali.sxryk.cn/Article/details/gtkpokqklp.html

[U08] Py：展平二维列表
来源：http://dali.chenjidiqi.icu/Article/details/gtomutcfem.html

[y for x in nested for y in x]
来源：http://dali.gotoacloud.top/Article/details/gtdbeqpzny.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtzkrgwgcy.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gtzqjjfznb.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gttsbfotgv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.daxiang520.top/Article/details/gtxqrmxtga.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtmhhizfxd.html

(x * 2 for x in arr)
来源：http://dali.c1oappe.top/Article/details/gtkuvqhkhx.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.aizwys.cn/Article/details/gtsyiaecay.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gtpbbipxzw.html

[U13] Py：固定长度队列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhfpprpa.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gtivsxeyqp.html

[U14] Py：分组收集到列表
来源：http://dali.andypj.xyz/Article/details/gttbtpysjs.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtltkvxcjh.html

[U15] Py：高精度计时
来源：http://dali.jinghuilouyu.cn/Article/details/gtdiklpogm.html

t = time.perf_counter()
来源：http://dali.jqgfzy.top/Article/details/gtiimpgiet.html

[U16] Py：命令行参数解析
来源：http://dali.yuxming.cn/Article/details/gtqyrphlys.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtnzrzlmne.html

[U17] Py：初始化日志
来源：http://dali.316326.xyz/Article/details/gtbticlllj.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.c1oappe.top/Article/details/gtwctyxcsb.html

[U18] Py：预编译正则
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpoxzvrks.html

pat = re.compile(r"\d+")
来源：http://dali.guowangkeji.top/Article/details/gtelowjcas.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gtklbbqoxs.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtspsjmitg.html

[U20] Py：缓存函数结果
来源：http://dali.yvedp.cn/Article/details/gtjedpbtge.html

@functools.lru_cache(maxsize=None)
来源：http://dali.feifeiyinyue.top/Article/details/gtdrspggya.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtgkkgoicp.html

@contextlib.contextmanager
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjdsucwlw.html

[U22] Py：矩阵转置
来源：http://dali.dianchejie.cn/Article/details/gtuiwkgwiz.html

list(zip(*m))
来源：http://dali.zhijiandao.cn/Article/details/gtvqqnpzjh.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gtdyxyyzvb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtbkjyxwdj.html

[U24] Py：路径操作
来源：http://dali.tianlin.xyz/Article/details/gtoycizfml.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zycfv.cn/Article/details/gtzknnizke.html

[U25] Py：CSV 按字典读
来源：http://dali.zhixingplan.top/Article/details/gtwltitwsb.html

csv.DictReader(f)
来源：http://dali.daria6918.cn/Article/details/gtdzvzehhz.html

[U26] Py：并发下载
来源：http://dali.hongshengwenyu.top/Article/details/gtfclvhckx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtveyneysr.html

[U27] Py：异步 HTTP
来源：http://dali.iojbl.cn/Article/details/gtfahuqyyz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.haohaochexian.top/Article/details/gtrtsttmea.html

[U28] Py：类型别名
来源：http://dali.xinyue.icu/Article/details/gtydetcgzh.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gtjrslzqxc.html

[U29] Py：属性校验
来源：http://dali.jinqigfzy.top/Article/details/gtezoiknnt.html

@property 与 @x.setter 配合
来源：http://dali.yvedp.cn/Article/details/gtdbpvhkek.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gtwitxbwoo.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtmanebvsm.html

[U31] Py：单测
来源：http://dali.fengsongda.top/Article/details/gtfvfsvumx.html

python -m pytest -q
来源：http://dali.chenlongwang.top/Article/details/gtqthssjrn.html

[U32] Py：代码格式化
来源：http://dali.tanke756.top/Article/details/gtczqfbyug.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtwuwmpzbr.html

[U33] Py：打包发布
来源：http://dali.svipenyu.cn/Article/details/gtdvegpepz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gtqnshavhj.html

[U34] Py：判断编码
来源：http://dali.jianghu66.top/Article/details/gtftcjmrfq.html

chardet.detect(raw)
来源：http://dali.c1oappe.top/Article/details/gtouqdwszx.html

[U35] Py：发送邮件
来源：http://dali.sysykeji.top/Article/details/gtjqxblhvm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.hongshengwenyu.top/Article/details/gtfjvpikjy.html

[U36] Py：定时任务
来源：http://dali.ppjwa.cn/Article/details/gtjfqtesbo.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenlongwang.top/Article/details/gtyuvaitmj.html

[U37] Py：读写 Excel
来源：http://dali.hywenlv.cn/Article/details/gtmqaqtehq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hfpthk.cn/Article/details/gtyfighnse.html

[U38] Py：获取脚本所在目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiolqysnz.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtwonibehe.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtpnaldewr.html

sys.stdout.isatty()
来源：http://dali.cashguo.top/Article/details/gtlarxzjys.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtexvvdhxp.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtzhyssfug.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gtyldginsm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtggeokeli.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhoulong.xyz/Article/details/gtuhuainwp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.gogol.net.cn/Article/details/gteuzqzopo.html

[U43] PHP：声明命名空间
来源：http://dali.ydzc1.top/Article/details/gtoewxartl.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtesuljpty.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtcyvepzcx.html

declare(strict_types=1);
来源：http://dali.guannengcc.top/Article/details/gtzpneznxf.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cucudq.cn/Article/details/gtckvxtebf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gttcxoxjrd.html

[U46] PHP：可空类型
来源：http://dali.vqdsnc.cn/Article/details/gtkplqawps.html

?string $name = null
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbhsdwzm.html

[U47] PHP：联合类型
来源：http://dali.gzhubu.top/Article/details/gtgzzedudq.html

int|string $id
来源：http://dali.aizwys.cn/Article/details/gtapquwkoh.html

[U48] PHP：纯枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtpzwpgvsw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sufxvd.cn/Article/details/gtyynvozsf.html

[U49] PHP：只读属性
来源：http://dali.xinyue.icu/Article/details/gtabztipxb.html

public readonly string $name
来源：http://dali.pycfn.com/Article/details/gtqfdacvjh.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gtftiwhqes.html

public function __construct(private int $id) {}
来源：http://dali.nanxinkj.top/Article/details/gtqzxeqbxs.html

[U51] PHP：数组解构
来源：http://dali.chenjidiqi.icu/Article/details/gtzrvavvts.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtgulnsnez.html

[U52] PHP：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtvwjysvtn.html

$double = fn($x) => $x * 2;
来源：http://dali.jqgufenzy.top/Article/details/gtgtmceblm.html

[U53] PHP：空合并运算符
来源：http://dali.yvedp.cn/Article/details/gtqhhlcbju.html

$v = $a ?? $b ?? "default";
来源：http://dali.redwolf501.top/Article/details/gthavrkoen.html

[U54] PHP：空安全调用
来源：http://dali.sxryk.cn/Article/details/gtoodfbhna.html

$obj?->method()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwtedsjhy.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gtblwfuobk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtyrehwycq.html

[U56] PHP：命名参数
来源：http://dali.chenlongwang.top/Article/details/gtkhdslaqj.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtpnkgrnha.html

[U57] PHP：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtembiuvdb.html

"值: {$a}"
来源：http://dali.zhongyouzk.top/Article/details/gtriqdkesr.html

[U58] PHP：数组三件套
来源：http://dali.jqgufenzy.top/Article/details/gtyebrpjfu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtixaxqytd.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gthywqshil.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.nwbrower.top/Article/details/gtcpjbluln.html

[U60] PHP：JSON 编解码
来源：http://dali.iojbl.cn/Article/details/gtkpkuvolx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.haohaochexian.top/Article/details/gtcdwucggm.html

[U61] PHP：正则
来源：http://dali.jqgufenzy.top/Article/details/gtsgzydocb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.guowangkeji.top/Article/details/gticqwwnhh.html

[U62] PHP：日期对象
来源：http://dali.zhongyouzk.top/Article/details/gtmpvutilx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.meibo888.top/Article/details/gtobktuwxo.html

[U63] PHP：文件读写
来源：http://dali.hnxiangtu.top/Article/details/gtfcchrtuk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj202588.top/Article/details/gtxqrretjt.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtkgupjytd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hfpthk.cn/Article/details/gtmzivqdfw.html

[U65] PHP：会话
来源：http://dali.yuxming.cn/Article/details/gtkrdalrvp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtqucoiomq.html

[U66] PHP：设置 Cookie
来源：http://dali.pycfn.com/Article/details/gtwvxvtmux.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xinyue.icu/Article/details/gtbtffvwlv.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gtqkjizwvc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoftrlmqw.html

[U68] PHP：PDO 连接
来源：http://dali.chenjidiqi.icu/Article/details/gtahgyttag.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xinyue.icu/Article/details/gtdzcwmsck.html

[U69] PHP：PDO 预处理
来源：http://dali.guannengcc.top/Article/details/gtszpgxdps.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenlongwang.top/Article/details/gtsnsebyuv.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gtglscidal.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.feifeiyinyue.top/Article/details/gtycaowmrf.html

[U71] PHP：抛出异常
来源：http://dali.yj20258888.top/Article/details/gtegggxztl.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gtmeobvmlk.html

[U72] PHP：写错误日志
来源：http://dali.hywenlv.cn/Article/details/gtdpfgghyp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ivvv.top/Article/details/gtnjuwnobj.html

[U73] PHP：读取 ini 配置
来源：http://dali.chenlongwang.top/Article/details/gtwmklpeat.html

parse_ini_file("config.ini", true)
来源：http://dali.shuidangran.top/Article/details/gtdscliugb.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtpstbuzzc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.daria6918.cn/Article/details/gtlrgyeksh.html

[U75] PHP：依赖注入
来源：http://dali.gaohongyu789.top/Article/details/gtecegklkx.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gtpzwwpusk.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtzkqkjvux.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmkhfkbrt.html

[U77] PHP：模板渲染
来源：http://dali.yj20258888.top/Article/details/gtceofdbdi.html

composer require twig/twig
来源：http://dali.cucudq.cn/Article/details/gtqlxcinqy.html

[U78] PHP：单元测试
来源：http://dali.jinqigufen.top/Article/details/gtyttvpojd.html

composer require --dev phpunit/phpunit
来源：http://dali.c1oappe.top/Article/details/gtqrerkpac.html

[U79] PHP：静态分析
来源：http://dali.mhx1999.top/Article/details/gtmrgxqyau.html

composer require --dev phpstan/phpstan
来源：http://dali.sxryk.cn/Article/details/gttwhlfbkn.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtqknqgema.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gtdppqvubn.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkcbfpyvn.html

npm init -y;  npm i express
来源：http://dali.birdmap.top/Article/details/gtuivyuujf.html

[U82] JS：package.json 脚本
来源：http://dali.pycfn.com/Article/details/gtnnntdxge.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hnqzz.top/Article/details/gtwwfshvkq.html

[U83] JS：ES Module 导入导出
来源：http://dali.gotoacloud.top/Article/details/gtqknouaaq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gtjzircovw.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gtlggapwlf.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.hongshengwenyu.top/Article/details/gttcknzijw.html

[U85] JS：可选链
来源：http://dali.fzhhl.top/Article/details/gtokmprpuw.html

a?.b?.c
来源：http://dali.fzhhl.top/Article/details/gtjyvctlid.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtlywcvtec.html

a ?? b
来源：http://dali.jlsjyb.cn/Article/details/gtjqlhiupp.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtunnpvqvh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aibaodan.cn/Article/details/gtukhcxubl.html

[U88] JS：对象展开合并
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzfkqygm.html

{ ...a, ...b }
来源：http://dali.nanxinkj.top/Article/details/gtjoptfpie.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtntlbkpil.html

[...new Set(arr)]
来源：http://dali.havefunace.top/Article/details/gtiidrthvq.html

[U90] JS：数字数组排序
来源：http://dali.meibo888.top/Article/details/gtjixzamjq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtwtdljwis.html

[U91] JS：对象键值遍历
来源：http://dali.feifeiyinyue.top/Article/details/gttnatiuds.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zdqjudy.top/Article/details/gtnxurewjl.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gtoujetxgi.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkqbyxjid.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtnntrhyrw.html

`共 ${n} 条`
来源：http://dali.andypj.xyz/Article/details/gtvckycipi.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtaxqhhtpy.html

const double = x => x * 2;
来源：http://dali.bjfxy.top/Article/details/gtievvsqkd.html

[U95] JS：Promise 包装
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywruiwol.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtayjjkptz.html

[U96] JS：async/await 与异常
来源：http://dali.daxiang520.top/Article/details/gthnlznkoj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gtirokxfnp.html

[U97] JS：并发请求
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivdmntrw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtwkfpbklk.html

[U98] JS：fetch 带 JSON
来源：http://dali.gotoacloud.top/Article/details/gtpwufimoc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ehwqpu.com/Article/details/gtlblhambq.html

[U99] JS：事件监听
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrcglkuin.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gttsyjgsby.html

[U100] JS：DOM 查询
来源：http://dali.jlsjyb.cn/Article/details/gtphspdrji.html

document.querySelector(".item")
来源：http://dali.zhengqikj.top/Article/details/gtiwsockxk.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtagymyqrh.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gtllxkqyxo.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtelgfbggm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.iojbl.cn/Article/details/gtzllnjpoa.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtkcywhjsd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gtbvqugqee.html

[U104] JS：防抖
来源：http://dali.daria6918.cn/Article/details/gtfnfrlftw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtgonafxnv.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtfsznnljp.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.svipenyu.cn/Article/details/gtgwnbmbba.html

[U106] JS：日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtqfzbwvui.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gtnoqykswu.html

[U107] JS：数字千分位
来源：http://dali.zhixingplan.top/Article/details/gtmzwwaivs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj20258.top/Article/details/gtebplciyi.html

[U108] JS：随机整数
来源：http://dali.hammf.cn/Article/details/gtfthgqvgp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhongyouzk.top/Article/details/gtzqqgllrk.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtozxwnetq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtarnajvmm.html

[U110] JS：数组分块
来源：http://dali.jinqigfzy.top/Article/details/gtajppkknh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtnkbxpeda.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gtijabqctx.html

new Map(Object.entries(obj))
来源：http://dali.vqdsnc.cn/Article/details/gttjeuucoo.html

[U112] JS：字符串补位
来源：http://dali.c1oappe.top/Article/details/gtyjytjpjs.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtrmmrfgbw.html

[U113] JS：正则替换全部
来源：http://dali.sysykeji.top/Article/details/gtfdefsgcd.html

s.replaceAll("a", "b")
来源：http://dali.jianghu66.top/Article/details/gtrtbyhged.html

[U114] JS：JSON 深比较
来源：http://dali.jqgfzy.top/Article/details/gtnryjsdef.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gtgifjxewx.html

[U115] JS：生成 UUID
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkawgfnal.html

crypto.randomUUID()
来源：http://dali.tianlin.xyz/Article/details/gtdguzarlb.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtivvvzivl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.guowangkeji.top/Article/details/gtqhwvqxil.html

[U117] JS：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjsgqdlz.html

npm i -D vitest;  npx vitest
来源：http://dali.zycfv.cn/Article/details/gtbphlofrg.html

[U118] JS：开发服务器
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiqdnsqb.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtvkkktqce.html

[U119] JS：生产构建
来源：http://dali.kuanghao11.cn/Article/details/gtgjwfuacp.html

npx vite build
来源：http://dali.tanke756.top/Article/details/gteecyusve.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuetiantiany.cn/Article/details/gteixsjqys.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gtuzvpwhgl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthkuilbfy.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gtxooqhsqt.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtyfezzwqd.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtcuojxvdg.html

Python ......... 252
来源：http://dali.gaohongyu789.top/Article/details/gtvttmyomk.html

PHP ............ 252
来源：http://dali.yonumen.top/Article/details/gtbrdejgfx.html

JavaScript ..... 252
来源：http://dali.cdnleiting.top/Article/details/gthkszradx.html

TypeScript ..... 212
来源：http://dali.birdmap.top/Article/details/gtjwniykgy.html

Java ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtpdolxbzg.html

Go ............. 212
来源：http://dali.gzhubu.top/Article/details/gtufveeuus.html

Ruby ........... 212
来源：http://dali.cdnleiting.top/Article/details/gtzqanbfad.html

C# ............. 212
来源：http://dali.guannengcc.top/Article/details/gtagfozfxq.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtnomeoaca.html

C++ ............ 30
来源：http://dali.zhixingplan.top/Article/details/gtnseapkvz.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtkfrxaves.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtclgaqlyj.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gtiwgqtybc.html

Swift .......... 15
来源：http://dali.hnqzz.top/Article/details/gtuvmviyft.html

Lua ............ 10
来源：http://dali.fengsongda.top/Article/details/gttpgfwhpe.html

Perl ........... 10
来源：http://dali.wangdashe.top/Article/details/gtukywbgel.html

Scala .......... 10
来源：http://dali.quarkkingdee.top/Article/details/gtvqdpgdeo.html

------------------------------------
来源：http://dali.zhiwuduotai.top/Article/details/gteqdudmeo.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtjizxtxcz.html

按章节统计：
来源：http://dali.hammf.cn/Article/details/gtusdtilhk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gtmpietbda.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtfdsitubd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtfvxvqamk.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtwdfrxwbo.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gtnetqvmjb.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxbhjhgt.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yueranfly.top/Article/details/gtelaehque.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfyncokfm.html


<!-- 参考信息 -->