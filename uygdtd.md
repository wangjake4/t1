代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gtriqagwqt.html

for my $x (@arr) { print $x; }
来源：http://dali.cucudq.cn/Article/details/gtgrslxaah.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtuojifwbn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aizwys.cn/Article/details/gtlwktkjvz.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gtjlzqfhqn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdinfnluf.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtwkevvwkw.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtqgcpajlw.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtwsaoyirk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.fzhhl.top/Article/details/gtoiiqfqgu.html

[T50] Perl：逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtmoeoxqgm.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gtqabwwuli.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jlsjyb.cn/Article/details/gtxelxcaxg.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtttsmhaov.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtqdxlmptz.html

[T52] Scala：变量
来源：http://dali.sxryk.cn/Article/details/gtnlwjvree.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtezhwnfrk.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtqzasrmpw.html

s"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtpwanjtoq.html

[T54] Scala：集合映射
来源：http://dali.redwolf501.top/Article/details/gtzttghmcv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtpfzfhtfh.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtukzaegau.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtynepcjos.html

[T56] Scala：样例类
来源：http://dali.9152youxi.cn/Article/details/gtkrxwgiqs.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtjwlxdpoo.html

[T57] Scala：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtrolqiumm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dianchejie.cn/Article/details/gtjoyxdluv.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gtnmcuprft.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zycfv.cn/Article/details/gtwjhmmplh.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gtfturlvvr.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtxgdrktgl.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtbtsnlojp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtpiiblick.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtmuwmmcif.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtymhxwxca.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttndrekag.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtkdpwikgc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ehwqpu.com/Article/details/gtubpdnpuq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtnpdhzmcl.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtzxckwsbr.html

[U03] Py：加载 .env 配置
来源：http://dali.gaohongyu789.top/Article/details/gtikkjeeqg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.redwolf501.top/Article/details/gtfhrpxmtx.html

[U04] Py：变量调试打印
来源：http://dali.fengsongda.top/Article/details/gtixicnljc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gtnpagwgkt.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtomkyjcao.html

list(dict.fromkeys(arr))
来源：http://dali.wangshuangyany.cn/Article/details/gtgwrvbcqp.html

[U06] Py：合并两个字典
来源：http://dali.pycfn.com/Article/details/gtfvtxkuix.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtdyliigeg.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gttdvondvf.html

{v: k for k, v in d.items()}
来源：http://dali.yonumen.top/Article/details/gtugljeidk.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gtmcfkhcqb.html

[y for x in nested for y in x]
来源：http://dali.nwbrower.top/Article/details/gtutvmiodz.html

[U09] Py：字典取最大值的键
来源：http://dali.aizwys.cn/Article/details/gtxxirehwe.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtdvhhvmce.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtpjunkijm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.hfpthk.cn/Article/details/gtvuvdmoes.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtnavkddcf.html

(x * 2 for x in arr)
来源：http://dali.jiagoushi.top/Article/details/gtrhxxibzm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yueranfly.top/Article/details/gtzpytdddl.html

Counter(arr).most_common(3)
来源：http://dali.tianlin.xyz/Article/details/gtrrioelyj.html

[U13] Py：固定长度队列
来源：http://dali.yuxming.cn/Article/details/gtxoibrldt.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydakipit.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtvahleojh.html

defaultdict(list)
来源：http://dali.xinyue.icu/Article/details/gtlgtcfyzj.html

[U15] Py：高精度计时
来源：http://dali.dashuyun.cn/Article/details/gtstnigeqa.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gtqkeshilw.html

[U16] Py：命令行参数解析
来源：http://dali.jiagoushi.top/Article/details/gtesdwnujx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhixingplan.top/Article/details/gtusfpvoef.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gtmhgfcgfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtktfrkjlc.html

[U18] Py：预编译正则
来源：http://dali.yonumen.top/Article/details/gthtabjulc.html

pat = re.compile(r"\d+")
来源：http://dali.aibaodan.cn/Article/details/gtpgneeeeg.html

[U19] Py：正则替换带回调
来源：http://dali.tianlin.xyz/Article/details/gteujxtrwn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ydzc1.top/Article/details/gtplplnzlw.html

[U20] Py：缓存函数结果
来源：http://dali.ywan-chungtsiang.top/Article/details/gtysxsafqo.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcfljbkds.html

[U21] Py：自定义上下文管理器
来源：http://dali.cdnleiting.top/Article/details/gtsjqaoohq.html

@contextlib.contextmanager
来源：http://dali.hysaishi.cn/Article/details/gtosjebmyq.html

[U22] Py：矩阵转置
来源：http://dali.hammf.cn/Article/details/gtwfhiuubd.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gturrnywvt.html

[U23] Py：分块读取大文件
来源：http://dali.meibo888.top/Article/details/gtiasjtcep.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dashuyun.cn/Article/details/gtknramncn.html

[U24] Py：路径操作
来源：http://dali.feifeiyinyue.top/Article/details/gtflpyuxpl.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.chenlongwang.top/Article/details/gthcbocbjo.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtroimbiwq.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtraalrrfq.html

[U26] Py：并发下载
来源：http://dali.wangshuangyany.cn/Article/details/gtqmgitwht.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258.top/Article/details/gtpjissqtt.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxvseehx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.tianlin.xyz/Article/details/gtzwqticdy.html

[U28] Py：类型别名
来源：http://dali.zycfv.cn/Article/details/gtijhwpgft.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gtmaqnysgf.html

[U29] Py：属性校验
来源：http://dali.andypj.xyz/Article/details/gtngqshldk.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gtbeifkbzq.html

[U30] Py：数据类
来源：http://dali.xinyue.icu/Article/details/gtcptuoqeg.html

@dataclass(slots=True)
来源：http://dali.jlsjyb.cn/Article/details/gtxuemdsyt.html

[U31] Py：单测
来源：http://dali.cashguo.top/Article/details/gthqdzshex.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtqtofsskv.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gtoseacsla.html

ruff format . && ruff check --fix .
来源：http://dali.andypj.xyz/Article/details/gteihugnhh.html

[U33] Py：打包发布
来源：http://dali.sysykeji.top/Article/details/gtwozmmhlk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenjidiqi.icu/Article/details/gtnraucnmd.html

[U34] Py：判断编码
来源：http://dali.fengsongda.top/Article/details/gtodcishte.html

chardet.detect(raw)
来源：http://dali.yanxiufei.cn/Article/details/gttizpegjv.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtweuqdzvs.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapnfbzta.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gtoixbnrbq.html

schedule.every(10).minutes.do(job)
来源：http://dali.guannengcc.top/Article/details/gtlflkafyf.html

[U37] Py：读写 Excel
来源：http://dali.nwbrower.top/Article/details/gtsxuzkoge.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sxryk.cn/Article/details/gtbbycxgvb.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtoecadeab.html

Path(__file__).resolve().parent
来源：http://dali.zdqjudy.top/Article/details/gtebsvwsew.html

[U39] Py：判断是否在交互环境
来源：http://dali.bjfxy.top/Article/details/gtljirktvg.html

sys.stdout.isatty()
来源：http://dali.dianchejie.cn/Article/details/gtyxlkyizs.html

[U40] Py：打印到标准错误
来源：http://dali.cqqwz.cn/Article/details/gtpjnwgvll.html

print("err", file=sys.stderr)
来源：http://dali.nwbrower.top/Article/details/gtfxphvjrv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj202588.top/Article/details/gtcaejwltv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tian-w.cn/Article/details/gtjwgoxmpx.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.nanxinkj.top/Article/details/gtudlpnpgf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258888.top/Article/details/gtkqlvnhqf.html

[U43] PHP：声明命名空间
来源：http://dali.cdnleiting.top/Article/details/gtejhfwift.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gttqcoskar.html

[U44] PHP：开启严格类型
来源：http://dali.zhoulong.xyz/Article/details/gttwoosccj.html

declare(strict_types=1);
来源：http://dali.nanxuanxn.top/Article/details/gtweogbzoy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cheryme.top/Article/details/gtlqbzvejk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqqsnxme.html

[U46] PHP：可空类型
来源：http://dali.zdqjudy.top/Article/details/gtughtwyge.html

?string $name = null
来源：http://dali.ybcxt.top/Article/details/gtemxmxztg.html

[U47] PHP：联合类型
来源：http://dali.tanke756.top/Article/details/gtnmqwqcre.html

int|string $id
来源：http://dali.chenlongwang.top/Article/details/gtkpbjlytq.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtachtirzu.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gtngqxjxgv.html

[U49] PHP：只读属性
来源：http://dali.fzhhl.top/Article/details/gthfwiwgev.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtpfdnmsne.html

[U50] PHP：构造器属性提升
来源：http://dali.cashguo.top/Article/details/gtyvgxxvtz.html

public function __construct(private int $id) {}
来源：http://dali.snrcjt.cn/Article/details/gtwnxkbixw.html

[U51] PHP：数组解构
来源：http://dali.jqgfzy.top/Article/details/gtqymfkydh.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtizlwtwcs.html

[U52] PHP：箭头函数
来源：http://dali.jianghu66.top/Article/details/gtmpgwojgx.html

$double = fn($x) => $x * 2;
来源：http://dali.cashguo.top/Article/details/gtdkltazta.html

[U53] PHP：空合并运算符
来源：http://dali.hysaishi.cn/Article/details/gtbuogpvzs.html

$v = $a ?? $b ?? "default";
来源：http://dali.meibo888.top/Article/details/gtqudevvrz.html

[U54] PHP：空安全调用
来源：http://dali.yongpay.top/Article/details/gtoewrsydu.html

$obj?->method()
来源：http://dali.vqdsnc.cn/Article/details/gtunnuciyu.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtmfdemvrv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jlsjyb.cn/Article/details/gtywjmvpke.html

[U56] PHP：命名参数
来源：http://dali.hnqzz.top/Article/details/gtsybblgfd.html

f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gtjzoqlgxj.html

[U57] PHP：字符串插值
来源：http://dali.yangfankeji.com/Article/details/gtokgfweux.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gttsstvxzl.html

[U58] PHP：数组三件套
来源：http://dali.sysykeji.top/Article/details/gtigbmkdlq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gtdpntkocg.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtfrmvkbye.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.haohaochexian.top/Article/details/gtpmkpunjz.html

[U60] PHP：JSON 编解码
来源：http://dali.yueranfly.top/Article/details/gtlptdmemz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gotoacloud.top/Article/details/gtzgoklgxs.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtpqdjtblq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtrpqsurtu.html

[U62] PHP：日期对象
来源：http://dali.zhiwuduotai.top/Article/details/gtujobsjhf.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ivvv.top/Article/details/gtsatixzsn.html

[U63] PHP：文件读写
来源：http://dali.chenjidiqi.icu/Article/details/gtcjiburcw.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtrcopgrtq.html

[U64] PHP：目录遍历
来源：http://dali.bjfxy.top/Article/details/gteumljrar.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.tanke756.top/Article/details/gtdgnpwnyd.html

[U65] PHP：会话
来源：http://dali.dianchejie.cn/Article/details/gtrymgrqzf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gtohprwrpx.html

[U66] PHP：设置 Cookie
来源：http://dali.yangfankeji.com/Article/details/gtsqhgrryg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jyoumei.cn/Article/details/gtysxymhkg.html

[U67] PHP：处理文件上传
来源：http://dali.sufxvd.cn/Article/details/gtqgrzgfyn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtmxdsvqxy.html

[U68] PHP：PDO 连接
来源：http://dali.ivvv.top/Article/details/gtgjmtkrgb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.c1oappe.top/Article/details/gtumelfgck.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtfhapgaju.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cheryme.top/Article/details/gtbtikgmda.html

[U70] PHP：PDO 事务
来源：http://dali.yongpay.top/Article/details/gtxviekiek.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.shzxlz.cn/Article/details/gtvcdrhkps.html

[U71] PHP：抛出异常
来源：http://dali.ydzc1.top/Article/details/gtrccdvspl.html

throw new RuntimeException("失败", 500);
来源：http://dali.yanxiufei.cn/Article/details/gtczyojsmr.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gtamrvaahr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hnqzz.top/Article/details/gtclhrwagt.html

[U73] PHP：读取 ini 配置
来源：http://dali.hammf.cn/Article/details/gtlgkfpijd.html

parse_ini_file("config.ini", true)
来源：http://dali.shangyingyoupin.top/Article/details/gtkruwvjty.html

[U74] PHP：读取环境变量
来源：http://dali.xziqi.cn/Article/details/gtermzrzll.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gtjcnuicpw.html

[U75] PHP：依赖注入
来源：http://dali.snrcjt.cn/Article/details/gtcyckmbsl.html

composer require psr/container
来源：http://dali.xinyue.icu/Article/details/gtzqatnkya.html

[U76] PHP：简单路由
来源：http://dali.ybcxt.top/Article/details/gthhvicfkn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhiwuduotai.top/Article/details/gtlqemrjkx.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtovheiivp.html

composer require twig/twig
来源：http://dali.jiagoushi.top/Article/details/gtfbkmpwgu.html

[U78] PHP：单元测试
来源：http://dali.jianghu66.top/Article/details/gtfyraxfjp.html

composer require --dev phpunit/phpunit
来源：http://dali.bjfxy.top/Article/details/gtkekpysab.html

[U79] PHP：静态分析
来源：http://dali.chenzaomai.com/Article/details/gtzmexkdih.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gtymcmrhme.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gteyatkqdl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.hnxiangtu.top/Article/details/gtfnqcfvjq.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtgxnxuidj.html

npm init -y;  npm i express
来源：http://dali.hywenlv.cn/Article/details/gtrqvqqyzk.html

[U82] JS：package.json 脚本
来源：http://dali.sweek.top/Article/details/gtzmleolvg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xylfe.cn/Article/details/gtfqajjvdh.html

[U83] JS：ES Module 导入导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gttjyjiovt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtpttbqrzs.html

[U84] JS：CommonJS 写法
来源：http://dali.sxryk.cn/Article/details/gtjvegkzhl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cheryme.top/Article/details/gtdsutupnd.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gtttyjckaw.html

a?.b?.c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslypzvpg.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gtwaazjmpn.html

a ?? b
来源：http://dali.cqqwz.cn/Article/details/gtipohidyr.html

[U87] JS：解构默认值
来源：http://dali.xuanzx.com/Article/details/gtwokxilov.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgfzy.top/Article/details/gtlbezpcqw.html

[U88] JS：对象展开合并
来源：http://dali.xuanzx.com/Article/details/gtcwqehthb.html

{ ...a, ...b }
来源：http://dali.nwbrower.top/Article/details/gtjdhisfps.html

[U89] JS：数组去重
来源：http://dali.hywenlv.cn/Article/details/gtqracvecd.html

[...new Set(arr)]
来源：http://dali.bjfxy.top/Article/details/gtjyozgses.html

[U90] JS：数字数组排序
来源：http://dali.yvedp.cn/Article/details/gthhxlsmsd.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gtndeowddz.html

[U91] JS：对象键值遍历
来源：http://dali.cashguo.top/Article/details/gtldotxrjn.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gtefmnjyeb.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtzrposfmv.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gtpzqqtgqq.html

[U93] JS：模板字符串
来源：http://dali.zhengqikj.top/Article/details/gttyfpuoxu.html

`共 ${n} 条`
来源：http://dali.guowangkeji.top/Article/details/gtlavqsamo.html

[U94] JS：箭头函数
来源：http://dali.smart0.xyz/Article/details/gtwuywjniz.html

const double = x => x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfmnotlf.html

[U95] JS：Promise 包装
来源：http://dali.havefunace.top/Article/details/gtywmfdcln.html

new Promise((resolve, reject) => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmhcsslcy.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpuyvzayj.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cheryme.top/Article/details/gtumxdwjbg.html

[U97] JS：并发请求
来源：http://dali.hongshengwenyu.top/Article/details/gtqojuicfj.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.kuanghao11.cn/Article/details/gtbifymnir.html

[U98] JS：fetch 带 JSON
来源：http://dali.daxiang520.top/Article/details/gtrschxvmq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yonumen.top/Article/details/gtumegranu.html

[U99] JS：事件监听
来源：http://dali.yvedp.cn/Article/details/gtpogfvpwa.html

el.addEventListener("click", e => {})
来源：http://dali.yvedp.cn/Article/details/gtoyuswtju.html

[U100] JS：DOM 查询
来源：http://dali.tanke756.top/Article/details/gtvojrermp.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gtfzgqfmqs.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbkxryzs.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gteqdobody.html

[U102] JS：本地存储
来源：http://dali.0kj1m.cn/Article/details/gtyvtxinbn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hnqzz.top/Article/details/gtswzevzfg.html

[U103] JS：定时器
来源：http://dali.yj202588.top/Article/details/gtxofuaewh.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gaohongyu789.top/Article/details/gtbnksvypf.html

[U104] JS：防抖
来源：http://dali.fengsongda.top/Article/details/gtnegltuel.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtdxxeupaq.html

[U105] JS：节流
来源：http://dali.pengpengdd.cyou/Article/details/gtpydsmsyo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkybjqsj.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtaevabtvv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yuanzhike.top/Article/details/gtcvocncfy.html

[U107] JS：数字千分位
来源：http://dali.feifeiyinyue.top/Article/details/gtercurpov.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hfpthk.cn/Article/details/gtvqpbyigl.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gtfqoeqcri.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtyssuxclr.html

[U109] JS：数组分组
来源：http://dali.andypj.xyz/Article/details/gtafkpazke.html

Object.groupBy(arr, x => x.type)
来源：http://dali.daria6918.cn/Article/details/gtnxtlkmgg.html

[U110] JS：数组分块
来源：http://dali.jqgufenzy.top/Article/details/gtpzexvzmh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yvedp.cn/Article/details/gtedjpjrfx.html

[U111] JS：对象转 Map
来源：http://dali.xuetiantiany.cn/Article/details/gtawurggbo.html

new Map(Object.entries(obj))
来源：http://dali.jinghuilouyu.cn/Article/details/gtvxmdfpzs.html

[U112] JS：字符串补位
来源：http://dali.aizwys.cn/Article/details/gtgmnsfvsy.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gthaepdnan.html

[U113] JS：正则替换全部
来源：http://dali.yj202588.top/Article/details/gtroxqoghp.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gtcdxnabfk.html

[U114] JS：JSON 深比较
来源：http://dali.sysykeji.top/Article/details/gtocagzphf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gthbarnhqf.html

[U115] JS：生成 UUID
来源：http://dali.c1oappe.top/Article/details/gtxiezgopb.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqsjkhsr.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gtknzpmmwr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdsgbdyxu.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gtptzfnhuw.html

npm i -D vitest;  npx vitest
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycmuntjj.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gttojkjiqj.html

npm i -D vite;  npx vite
来源：http://dali.quarkkingdee.top/Article/details/gthzoeqhkk.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtjvsrqbil.html

npx vite build
来源：http://dali.snrcjt.cn/Article/details/gtmabzwage.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzpwfgfuj.html

import.meta.env.VITE_API_URL
来源：http://dali.hongshengwenyu.top/Article/details/gtkksywmlj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthgtnsyog.html

统计汇总
来源：http://dali.vqdsnc.cn/Article/details/gtwlshlxhn.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtlifkough.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtauomuili.html

Python ......... 252
来源：http://dali.jlsjyb.cn/Article/details/gtatocwqpe.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtbjiscerk.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gtqvzyrmdj.html

TypeScript ..... 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqelsexm.html

Java ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtwhhmuslg.html

Go ............. 212
来源：http://dali.hnqzz.top/Article/details/gtuxmuctpw.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqiokhez.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtclfcgxcu.html

C .............. 30
来源：http://dali.sysykeji.top/Article/details/gtykdaqkhp.html

C++ ............ 30
来源：http://dali.quarkkingdee.top/Article/details/gtdpklnyjg.html

SQL ............ 90
来源：http://dali.ppjwa.cn/Article/details/gthbwvbndr.html

Bash ........... 80
来源：http://dali.jiagoushi.top/Article/details/gtwgcvrity.html

Kotlin ......... 15
来源：http://dali.yanxiufei.cn/Article/details/gtstmtskba.html

Swift .......... 15
来源：http://dali.zhiwuduotai.top/Article/details/gtgifqgwvu.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtwgsaqxfa.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtgrfodfxq.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gtcsziysvv.html

------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtcgefziyj.html

合计 ........... 2106 条
来源：http://dali.gaohongyu789.top/Article/details/gtkouqfvdu.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtxndtfiqs.html


<!-- 参考信息 -->