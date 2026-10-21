代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.fengsongda.top/Article/details/gtnkxvxifn.html

for my $x (@arr) { print $x; }
来源：http://dali.jlsjyb.cn/Article/details/gtnsovjupg.html

[T46] Perl：哈希操作
来源：http://dali.jianghu66.top/Article/details/gthlzxdotb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gttksqedzh.html

[T47] Perl：正则捕获
来源：http://dali.wangdashe.top/Article/details/gtukkqshrl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cheryme.top/Article/details/gtkzxkzzkn.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gtxrlvylhv.html

$s =~ s/old/new/g;
来源：http://dali.fengsongda.top/Article/details/gtelvrovvc.html

[T49] Perl：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtzizdlavo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtkmbxdatr.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtxdpeoreu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cucudq.cn/Article/details/gtwszzrbsz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.c1oappe.top/Article/details/gtuvuowxhu.html

[T51] Scala：Hello World
来源：http://dali.iojbl.cn/Article/details/gtashgdomd.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtefnprrxj.html

[T52] Scala：变量
来源：http://dali.andypj.xyz/Article/details/gtxlsppmzr.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcsmbqnd.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtcjcmvcfv.html

s"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtmodhpevi.html

[T54] Scala：集合映射
来源：http://dali.yuxming.cn/Article/details/gtolcqxrqk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hysaishi.cn/Article/details/gtdqmehkls.html

[T55] Scala：集合过滤
来源：http://dali.zhiwuduotai.top/Article/details/gtwqigmwcb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.kuanghao11.cn/Article/details/gtmubmmuzm.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtutwgnpyh.html

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtlohotznf.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gteygougvv.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gtpdeifxyl.html

[T58] Scala：函数定义
来源：http://dali.vqdsnc.cn/Article/details/gteykwmtth.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtsudijsao.html

[T59] Scala：循环
来源：http://dali.andypj.xyz/Article/details/gtrrmscozf.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtqyqcveyx.html

[T60] Scala：折叠
来源：http://dali.ppjwa.cn/Article/details/gtuxhtbmgo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtvwwuamny.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdmpetnfp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.havefunace.top/Article/details/gtwfbiljqn.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzoddfkr.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gtwxvrexlk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtqqvdzacs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pengpengdd.cyou/Article/details/gtzvspaljz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.daxiang520.top/Article/details/gthmzzpgea.html

[U03] Py：加载 .env 配置
来源：http://dali.yongpay.top/Article/details/gtkgwmabaj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.fzhhl.top/Article/details/gtjqmsomsm.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gtbpmnrizh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hfpthk.cn/Article/details/gtxwoliwvi.html

[U05] Py：列表去重且保序
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiyexjzk.html

list(dict.fromkeys(arr))
来源：http://dali.jqgufenzy.top/Article/details/gtjlprmdnm.html

[U06] Py：合并两个字典
来源：http://dali.redwolf501.top/Article/details/gtrfftcodz.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gtagwarnpm.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtykkwraut.html

{v: k for k, v in d.items()}
来源：http://dali.dashuyun.cn/Article/details/gtbrrgghdg.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtuckiymdb.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gttqpdluxc.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtksqgqsgw.html

max(d, key=d.get)
来源：http://dali.ydzc1.top/Article/details/gtnofiupns.html

[U10] Py：按值排序字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdkxkkzq.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhongyouzk.top/Article/details/gtupsrikhs.html

[U11] Py：生成器表达式
来源：http://dali.sweek.top/Article/details/gtjdgieevp.html

(x * 2 for x in arr)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjuybwii.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gtaosgevmz.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gtpftsixhx.html

[U13] Py：固定长度队列
来源：http://dali.yonumen.top/Article/details/gtfakartfk.html

deque(maxlen=10)
来源：http://dali.yj202588.top/Article/details/gtckbhefzb.html

[U14] Py：分组收集到列表
来源：http://dali.xylfe.cn/Article/details/gtosklkgmy.html

defaultdict(list)
来源：http://dali.shangyingyoupin.top/Article/details/gtzipqmsav.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjhgbjgs.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtvcnjtweb.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gthjqisngx.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgvhmuigk.html

[U17] Py：初始化日志
来源：http://dali.meibo888.top/Article/details/gtlwybyayp.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.chenjidiqi.icu/Article/details/gtjkvwhevt.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gttkvantmm.html

pat = re.compile(r"\d+")
来源：http://dali.yueranfly.top/Article/details/gtevsicogw.html

[U19] Py：正则替换带回调
来源：http://dali.yuxming.cn/Article/details/gtrscwpmqy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cucudq.cn/Article/details/gtccdwcyxy.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtxoljecsn.html

@functools.lru_cache(maxsize=None)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcavlpmch.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gtwdzxeurs.html

@contextlib.contextmanager
来源：http://dali.pengpengdd.cyou/Article/details/gtzjbdjhdg.html

[U22] Py：矩阵转置
来源：http://dali.chenzaomai.com/Article/details/gtsplgnabi.html

list(zip(*m))
来源：http://dali.svipenyu.cn/Article/details/gtiozvehvk.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gtxcooesyk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.wangshuangyany.cn/Article/details/gtjeqlgrqu.html

[U24] Py：路径操作
来源：http://dali.daxiang520.top/Article/details/gtgnmbrniz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtvjdvknrj.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gtrmorumyw.html

csv.DictReader(f)
来源：http://dali.haohaochexian.top/Article/details/gtjmutlikf.html

[U26] Py：并发下载
来源：http://dali.jiagoushi.top/Article/details/gtcigspiax.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.daria6918.cn/Article/details/gtyhtlamnw.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gtywdmzcdl.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqntgxnhq.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gtktacxlvi.html

UserId = int
来源：http://dali.cucudq.cn/Article/details/gttrvjgeyp.html

[U29] Py：属性校验
来源：http://dali.daria6918.cn/Article/details/gtqbkfpfbs.html

@property 与 @x.setter 配合
来源：http://dali.zycfv.cn/Article/details/gtffqwfjgz.html

[U30] Py：数据类
来源：http://dali.zdqjudy.top/Article/details/gtrakgukmp.html

@dataclass(slots=True)
来源：http://dali.havefunace.top/Article/details/gtwtvrnqxb.html

[U31] Py：单测
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiergrqem.html

python -m pytest -q
来源：http://dali.316326.xyz/Article/details/gtcacjxncz.html

[U32] Py：代码格式化
来源：http://dali.birdmap.top/Article/details/gtvoqylaeq.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gtvkqyjgyf.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtbhtilwhf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hysaishi.cn/Article/details/gteklttxfu.html

[U34] Py：判断编码
来源：http://dali.sysykeji.top/Article/details/gtwrbbhxab.html

chardet.detect(raw)
来源：http://dali.zhixingplan.top/Article/details/gtkzwplqrd.html

[U35] Py：发送邮件
来源：http://dali.chenjidiqi.icu/Article/details/gtasxiapqu.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jlsjyb.cn/Article/details/gthyguaigf.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtgosbusxv.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gtrhttdfto.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtoxgopozt.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ppjwa.cn/Article/details/gtkkrtcbxm.html

[U38] Py：获取脚本所在目录
来源：http://dali.dashuyun.cn/Article/details/gtvnrblrmk.html

Path(__file__).resolve().parent
来源：http://dali.kuanghao11.cn/Article/details/gtvajvfjnc.html

[U39] Py：判断是否在交互环境
来源：http://dali.snrcjt.cn/Article/details/gtqrwfgktx.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtwmtmksoz.html

[U40] Py：打印到标准错误
来源：http://dali.jiagoushi.top/Article/details/gtmmcgcfbj.html

print("err", file=sys.stderr)
来源：http://dali.dianchejie.cn/Article/details/gtpxoffrpj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.0kj1m.cn/Article/details/gterevhtnh.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tanke756.top/Article/details/gtigecgpzb.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhixingplan.top/Article/details/gtsueluzgo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gtljckdrya.html

[U43] PHP：声明命名空间
来源：http://dali.jlsjyb.cn/Article/details/gtdcgyvcah.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gtdvjnszuz.html

[U44] PHP：开启严格类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdbpywryj.html

declare(strict_types=1);
来源：http://dali.sweek.top/Article/details/gtczfyshbo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtsxtqlzww.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtotrnsahg.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gtkasaksgs.html

?string $name = null
来源：http://dali.sweek.top/Article/details/gtlmpavblb.html

[U47] PHP：联合类型
来源：http://dali.ivvv.top/Article/details/gtrkigrtwi.html

int|string $id
来源：http://dali.nanxuanxn.top/Article/details/gtwsijrnef.html

[U48] PHP：纯枚举
来源：http://dali.havefunace.top/Article/details/gthlfwegrh.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.meibo888.top/Article/details/gtxyoyptki.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gtqcvdyslz.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtkbxhdlih.html

[U50] PHP：构造器属性提升
来源：http://dali.nanxuanxn.top/Article/details/gtlfzfefds.html

public function __construct(private int $id) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtedoxqugz.html

[U51] PHP：数组解构
来源：http://dali.hysaishi.cn/Article/details/gtetihvhoc.html

[$a, $b] = $arr;
来源：http://dali.xylfe.cn/Article/details/gtbpupgzja.html

[U52] PHP：箭头函数
来源：http://dali.cdnleiting.top/Article/details/gtmagfhltw.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gthxcdmjbr.html

[U53] PHP：空合并运算符
来源：http://dali.gogol.net.cn/Article/details/gtcqfelbte.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtwfykoflx.html

[U54] PHP：空安全调用
来源：http://dali.gaohongyu789.top/Article/details/gtnopkwrxm.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gtjdoksfyi.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtnsznjalo.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cqqwz.cn/Article/details/gtjbgcyzib.html

[U56] PHP：命名参数
来源：http://dali.guowangkeji.top/Article/details/gtryafebxb.html

f(a: 1, b: 2)
来源：http://dali.hongshengwenyu.top/Article/details/gtfidudaty.html

[U57] PHP：字符串插值
来源：http://dali.yonumen.top/Article/details/gtngbpznna.html

"值: {$a}"
来源：http://dali.sxryk.cn/Article/details/gtmhocnaqt.html

[U58] PHP：数组三件套
来源：http://dali.cheryme.top/Article/details/gtcchqmtjo.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtgyxbkyfx.html

[U59] PHP：自定义排序
来源：http://dali.zhongyouzk.top/Article/details/gtwaqrddgb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtuddghlxf.html

[U60] PHP：JSON 编解码
来源：http://dali.snrcjt.cn/Article/details/gtvtesihzw.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xziqi.cn/Article/details/gtprpesuig.html

[U61] PHP：正则
来源：http://dali.nwbrower.top/Article/details/gtuwreowrf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.meibo888.top/Article/details/gtipmeblmh.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gttrkcyipi.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hysaishi.cn/Article/details/gtplfoevdo.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtiygcijjg.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gtmqqoqvgo.html

[U64] PHP：目录遍历
来源：http://dali.cheryme.top/Article/details/gtbggqufew.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fzhhl.top/Article/details/gtgkoirsmt.html

[U65] PHP：会话
来源：http://dali.ehwqpu.com/Article/details/gtuxembjzy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtcoiincji.html

[U66] PHP：设置 Cookie
来源：http://dali.gzhubu.top/Article/details/gtrvbhgmrl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ydzc1.top/Article/details/gtqtongbsa.html

[U67] PHP：处理文件上传
来源：http://dali.hywenlv.cn/Article/details/gtkzrbqxzi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.birdmap.top/Article/details/gtpnageqgw.html

[U68] PHP：PDO 连接
来源：http://dali.dianchejie.cn/Article/details/gtofgeoefd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.316326.xyz/Article/details/gtsfatuxbr.html

[U69] PHP：PDO 预处理
来源：http://dali.zdqjudy.top/Article/details/gtulmqdjui.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yangfankeji.com/Article/details/gtanuddomc.html

[U70] PHP：PDO 事务
来源：http://dali.hnqzz.top/Article/details/gtboeoobci.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.kuanghao11.cn/Article/details/gtnntqdztr.html

[U71] PHP：抛出异常
来源：http://dali.yonumen.top/Article/details/gtiuhbbmev.html

throw new RuntimeException("失败", 500);
来源：http://dali.hfpthk.cn/Article/details/gtmtphulwr.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gtcjmtwalw.html

error_log("失败: " . $e->getMessage());
来源：http://dali.andypj.xyz/Article/details/gtqadozkyo.html

[U73] PHP：读取 ini 配置
来源：http://dali.birdmap.top/Article/details/gtziqolbnw.html

parse_ini_file("config.ini", true)
来源：http://dali.zycfv.cn/Article/details/gtxaqtfrdh.html

[U74] PHP：读取环境变量
来源：http://dali.sufxvd.cn/Article/details/gtnuzcnsfb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guowangkeji.top/Article/details/gtlgydjowu.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtiimghhsw.html

composer require psr/container
来源：http://dali.yj20258888.top/Article/details/gtqrcwhbqr.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gtqgwddxfj.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.snrcjt.cn/Article/details/gtpvfqqdjm.html

[U77] PHP：模板渲染
来源：http://dali.tanke756.top/Article/details/gtdotbsbcm.html

composer require twig/twig
来源：http://dali.shzxlz.cn/Article/details/gtodnmleut.html

[U78] PHP：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtfoevdvsq.html

composer require --dev phpunit/phpunit
来源：http://dali.yangfankeji.com/Article/details/gturclbxuz.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gtmvqqymsx.html

composer require --dev phpstan/phpstan
来源：http://dali.yonumen.top/Article/details/gtjvjhndmp.html

[U80] PHP：代码规范修复
来源：http://dali.yangfankeji.com/Article/details/gtprlnrtga.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhijiandao.cn/Article/details/gtkkfvgyne.html

[U81] JS：初始化项目
来源：http://dali.yuanzhike.top/Article/details/gtbmkfdaka.html

npm init -y;  npm i express
来源：http://dali.hysaishi.cn/Article/details/gtvtvmchfi.html

[U82] JS：package.json 脚本
来源：http://dali.chenlongwang.top/Article/details/gtczyvwjge.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.kuanghao11.cn/Article/details/gtarppuxuf.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhoulong.xyz/Article/details/gtgjuszkdl.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtlytyztyu.html

[U84] JS：CommonJS 写法
来源：http://dali.hysaishi.cn/Article/details/gtlbqoxljc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinqigfzy.top/Article/details/gtjxbvdvse.html

[U85] JS：可选链
来源：http://dali.feifeiyinyue.top/Article/details/gtpjmfhiuh.html

a?.b?.c
来源：http://dali.chenzaomai.com/Article/details/gtttvonsbr.html

[U86] JS：空值合并
来源：http://dali.hnxiangtu.top/Article/details/gtpwlxgqde.html

a ?? b
来源：http://dali.hywenlv.cn/Article/details/gtvgnrhqfj.html

[U87] JS：解构默认值
来源：http://dali.quarkkingdee.top/Article/details/gthnakgvgu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuetiantiany.cn/Article/details/gtvqtydlqk.html

[U88] JS：对象展开合并
来源：http://dali.sxryk.cn/Article/details/gtnykrgifb.html

{ ...a, ...b }
来源：http://dali.wangdashe.top/Article/details/gtpeyanplz.html

[U89] JS：数组去重
来源：http://dali.aizwys.cn/Article/details/gttecfjqmf.html

[...new Set(arr)]
来源：http://dali.sufxvd.cn/Article/details/gttjtqdbcc.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gtxkgpgwpe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ehwqpu.com/Article/details/gtjaxqgzqc.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlecwbob.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yuanzhike.top/Article/details/gtlkaabkrn.html

[U92] JS：深拷贝
来源：http://dali.ehwqpu.com/Article/details/gtpxrwwaij.html

structuredClone(obj)
来源：http://dali.ehwqpu.com/Article/details/gtuttymtmm.html

[U93] JS：模板字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnnabswdk.html

`共 ${n} 条`
来源：http://dali.ppjwa.cn/Article/details/gtxhjzeikj.html

[U94] JS：箭头函数
来源：http://dali.cqqwz.cn/Article/details/gtxigfygtg.html

const double = x => x * 2;
来源：http://dali.gaohongyu789.top/Article/details/gtuzinkaec.html

[U95] JS：Promise 包装
来源：http://dali.zhongyouzk.top/Article/details/gteyydrily.html

new Promise((resolve, reject) => {})
来源：http://dali.jyoumei.cn/Article/details/gtufrtyxst.html

[U96] JS：async/await 与异常
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtglvdxqfi.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yueranfly.top/Article/details/gtzdacetrb.html

[U97] JS：并发请求
来源：http://dali.fzhhl.top/Article/details/gtcjqjfova.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.316326.xyz/Article/details/gtqrhrdhlq.html

[U98] JS：fetch 带 JSON
来源：http://dali.havefunace.top/Article/details/gteogmkbml.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.ybcxt.top/Article/details/gtycrcpyrp.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gtzyahivyn.html

el.addEventListener("click", e => {})
来源：http://dali.wangshuangyany.cn/Article/details/gtsplrqbis.html

[U100] JS：DOM 查询
来源：http://dali.ehwqpu.com/Article/details/gtxeohexhv.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gtcdrxoybz.html

[U101] JS：classList 操作
来源：http://dali.xuetiantiany.cn/Article/details/gtebafaulq.html

el.classList.toggle("active")
来源：http://dali.jyoumei.cn/Article/details/gtwaurkpir.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gtokaanzcz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtwbfrvkjb.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtwwbrweyd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gtfwbnhvbu.html

[U104] JS：防抖
来源：http://dali.wangdashe.top/Article/details/gtgeptwkyd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yongpay.top/Article/details/gtgqyxenok.html

[U105] JS：节流
来源：http://dali.xinyue.icu/Article/details/gtvdunxtlv.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtnydrovgp.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtwddryvlt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jqgufenzy.top/Article/details/gtauhqsjie.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxapjxnip.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtclpiesmj.html

[U108] JS：随机整数
来源：http://dali.zycfv.cn/Article/details/gtganhfpjp.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtegffsiow.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtlcpjozxf.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aizwys.cn/Article/details/gtksjymqkm.html

[U110] JS：数组分块
来源：http://dali.fengsongda.top/Article/details/gtjmzmgaan.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.chenlongwang.top/Article/details/gtmaehjluy.html

[U111] JS：对象转 Map
来源：http://dali.shuidangran.top/Article/details/gtvjptqcml.html

new Map(Object.entries(obj))
来源：http://dali.xylfe.cn/Article/details/gtopnruvnq.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtuktojtgx.html

"7".padStart(3, "0")
来源：http://dali.sufxvd.cn/Article/details/gtybthwvtk.html

[U113] JS：正则替换全部
来源：http://dali.yvedp.cn/Article/details/gtulteniei.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtjcsmawav.html

[U114] JS：JSON 深比较
来源：http://dali.nwbrower.top/Article/details/gtewldktnx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gthmeyumqx.html

[U115] JS：生成 UUID
来源：http://dali.hywenlv.cn/Article/details/gtbohcrqqn.html

crypto.randomUUID()
来源：http://dali.dianchejie.cn/Article/details/gtepyammuu.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtzknkbcnp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daria6918.cn/Article/details/gtclbwzzsk.html

[U117] JS：单元测试
来源：http://dali.daria6918.cn/Article/details/gtdlnkamnx.html

npm i -D vitest;  npx vitest
来源：http://dali.tianlin.xyz/Article/details/gtuxejhkwc.html

[U118] JS：开发服务器
来源：http://dali.jqgfzy.top/Article/details/gteibuipbs.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtqoxiavcr.html

[U119] JS：生产构建
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrwcuvny.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtvdcknkjb.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtiueurzue.html

import.meta.env.VITE_API_URL
来源：http://dali.yj202588.top/Article/details/gtelettgag.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtdilgtwry.html

统计汇总
来源：http://dali.jinqigufen.top/Article/details/gtrswnwfiv.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtykvtmdhu.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiomuaisv.html

Python ......... 252
来源：http://dali.cashguo.top/Article/details/gtrlctltvz.html

PHP ............ 252
来源：http://dali.yanxiufei.cn/Article/details/gtgipqnrri.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtqfuajxne.html

TypeScript ..... 212
来源：http://dali.yuanzhike.top/Article/details/gtunzentig.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gtntzscnvv.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gtjzbpiflm.html

Ruby ........... 212
来源：http://dali.nwbrower.top/Article/details/gtrdpifcpm.html

C# ............. 212
来源：http://dali.ppjwa.cn/Article/details/gtxivhzvne.html

C .............. 30
来源：http://dali.zhixingplan.top/Article/details/gtpwtrurrv.html

C++ ............ 30
来源：http://dali.zhengqikj.top/Article/details/gthkpzdenz.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnhajwlyd.html

Bash ........... 80
来源：http://dali.bjfxy.top/Article/details/gthgjlsobs.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtdwjsfetc.html

Swift .......... 15
来源：http://dali.gzhubu.top/Article/details/gtrqxnzmul.html

Lua ............ 10
来源：http://dali.havefunace.top/Article/details/gtxhztzpkl.html

Perl ........... 10
来源：http://dali.yueranfly.top/Article/details/gtxnbskoft.html

Scala .......... 10
来源：http://dali.guowangkeji.top/Article/details/gtqknkfwqx.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtwjdlqqtw.html

合计 ........... 2106 条
来源：http://dali.dashuyun.cn/Article/details/gtlxexqzhb.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gtmzlhzjvu.html


<!-- 参考信息 -->