代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtjpufeqpr.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gteqnvdvuc.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtxignavzy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtybybuage.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegcwhsjz.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzncxudss.html

[T48] Perl：正则替换
来源：http://dali.316326.xyz/Article/details/gtwnpjlgpp.html

$s =~ s/old/new/g;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfdhbxta.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gtyxhcbbez.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtebxlfecv.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtbkfvmyum.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtwqvqfllp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hfpthk.cn/Article/details/gtoxefjilh.html

[T51] Scala：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtzvpqvwhj.html

println("Hello")
来源：http://dali.hammf.cn/Article/details/gtrhrgyzic.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtkmiuxqiu.html

val a = 1;  var b = 2
来源：http://dali.9152youxi.cn/Article/details/gtlyfizniy.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtwinhmdpg.html

s"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtsinlwuyn.html

[T54] Scala：集合映射
来源：http://dali.cdnleiting.top/Article/details/gtptshrzqp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gtcugqvlqm.html

[T55] Scala：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtuxlhoxol.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gtdzgjwkxv.html

[T56] Scala：样例类
来源：http://dali.vqdsnc.cn/Article/details/gtposngsfo.html

case class User(name: String, age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtmzqhofyt.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtilwvxhcj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtckteydgh.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gtzojbkire.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj20258888.top/Article/details/gtdapcxjef.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtkbpvdkic.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtfpnpfqgf.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtrqcakkow.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangshuangyany.cn/Article/details/gtyedgrdym.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtjfohwfhx.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hongshengwenyu.top/Article/details/gtnmrjoyjn.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtuaizzums.html

[U01] Py：创建虚拟环境
来源：http://dali.jqgufenzy.top/Article/details/gtwmrdzvsz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hfpthk.cn/Article/details/gtsbwwkfwt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gtrbmgmjdr.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxinkj.top/Article/details/gtjbnmeojk.html

[U03] Py：加载 .env 配置
来源：http://dali.hammf.cn/Article/details/gtmkuwhfvl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gtiwwhcmxu.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gtbnldjtzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.c1oappe.top/Article/details/gtsxvggmtj.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtpveayfzx.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gtnjkpczss.html

[U06] Py：合并两个字典
来源：http://dali.c1oappe.top/Article/details/gtxquxbkas.html

{**a, **b}
来源：http://dali.sxryk.cn/Article/details/gtgrycjbpb.html

[U07] Py：反转字典键值
来源：http://dali.cucudq.cn/Article/details/gtyqvlygdc.html

{v: k for k, v in d.items()}
来源：http://dali.gogol.net.cn/Article/details/gtkfnsfuky.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboqgvxcq.html

[y for x in nested for y in x]
来源：http://dali.yuxming.cn/Article/details/gtsvuwzqrc.html

[U09] Py：字典取最大值的键
来源：http://dali.wangshuangyany.cn/Article/details/gtbffvppqd.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtvupyeu.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtkearsuds.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yueranfly.top/Article/details/gtrfpjdcgx.html

[U11] Py：生成器表达式
来源：http://dali.hnxiangtu.top/Article/details/gtzssfxibm.html

(x * 2 for x in arr)
来源：http://dali.meibo888.top/Article/details/gtyrzwfuuu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilffbifz.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtsgrgxgxs.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtmcpkcijs.html

deque(maxlen=10)
来源：http://dali.cashguo.top/Article/details/gttktpwefm.html

[U14] Py：分组收集到列表
来源：http://dali.guannengcc.top/Article/details/gttxvirknw.html

defaultdict(list)
来源：http://dali.meibo888.top/Article/details/gtoiswuzwz.html

[U15] Py：高精度计时
来源：http://dali.xziqi.cn/Article/details/gtlfjvmvdc.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gtxdjkekkb.html

[U16] Py：命令行参数解析
来源：http://dali.fzhhl.top/Article/details/gtskzlumzt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gaohongyu789.top/Article/details/gtbcacspgn.html

[U17] Py：初始化日志
来源：http://dali.gzhubu.top/Article/details/gtvfwbxuyt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gtvwzcjegf.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gtalqabebj.html

pat = re.compile(r"\d+")
来源：http://dali.nanxinkj.top/Article/details/gtpvnwhtlr.html

[U19] Py：正则替换带回调
来源：http://dali.cqqwz.cn/Article/details/gtujdgejlo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cheryme.top/Article/details/gtwcmlspnf.html

[U20] Py：缓存函数结果
来源：http://dali.birdmap.top/Article/details/gtlisuytnj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yueranfly.top/Article/details/gtcekocdtg.html

[U21] Py：自定义上下文管理器
来源：http://dali.guowangkeji.top/Article/details/gtpklwzknx.html

@contextlib.contextmanager
来源：http://dali.birdmap.top/Article/details/gtkuetndfe.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtjqyeqmqg.html

list(zip(*m))
来源：http://dali.fengsongda.top/Article/details/gtotymjelh.html

[U23] Py：分块读取大文件
来源：http://dali.yuxming.cn/Article/details/gtlzjmbalz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.gaohongyu789.top/Article/details/gtrmosmybk.html

[U24] Py：路径操作
来源：http://dali.shzxlz.cn/Article/details/gtdoikuknr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.nanxuanxn.top/Article/details/gtnqbpokrg.html

[U25] Py：CSV 按字典读
来源：http://dali.yuanzhike.top/Article/details/gtbjjlzsto.html

csv.DictReader(f)
来源：http://dali.yvedp.cn/Article/details/gtweazlugr.html

[U26] Py：并发下载
来源：http://dali.hysaishi.cn/Article/details/gtcjaisgqj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.mhx1999.top/Article/details/gtikoghunr.html

[U27] Py：异步 HTTP
来源：http://dali.hongshengwenyu.top/Article/details/gthbvwmris.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gttpreixsk.html

[U28] Py：类型别名
来源：http://dali.yonumen.top/Article/details/gtairqymja.html

UserId = int
来源：http://dali.iojbl.cn/Article/details/gtxxpkbhje.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtbbwcpvtb.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gthqytzqse.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gttbsrnxku.html

@dataclass(slots=True)
来源：http://dali.jinghuilouyu.cn/Article/details/gtueueyops.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtjmwyefsc.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegzomkdu.html

[U32] Py：代码格式化
来源：http://dali.redwolf501.top/Article/details/gtfoevuoyg.html

ruff format . && ruff check --fix .
来源：http://dali.cucudq.cn/Article/details/gtmyormgft.html

[U33] Py：打包发布
来源：http://dali.hnxiangtu.top/Article/details/gtvyxgxnmb.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtpnzlkoaa.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtdpqzzqoh.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gthlkisnqk.html

[U35] Py：发送邮件
来源：http://dali.shanyushiyangtech.top/Article/details/gttdbhkqkt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yuanzhike.top/Article/details/gtzpvowoyi.html

[U36] Py：定时任务
来源：http://dali.gogol.net.cn/Article/details/gtrhbmbqgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtzvniauch.html

[U37] Py：读写 Excel
来源：http://dali.tanke756.top/Article/details/gtncfrqnjg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dianchejie.cn/Article/details/gtcrefyhhw.html

[U38] Py：获取脚本所在目录
来源：http://dali.shuidangran.top/Article/details/gtvxnkqtiz.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gtvbzofkda.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gtyjfsfjya.html

sys.stdout.isatty()
来源：http://dali.yueranfly.top/Article/details/gtnzrgooaw.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtrjgenytc.html

print("err", file=sys.stderr)
来源：http://dali.gogol.net.cn/Article/details/gtjdreiyby.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gthviexkse.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.tianlin.xyz/Article/details/gtqfaxqimv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sysykeji.top/Article/details/gtjkkmwdcj.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gtukggudvq.html

[U43] PHP：声明命名空间
来源：http://dali.zhengqikj.top/Article/details/gtixjanetp.html

namespace App\Http;
来源：http://dali.hywenlv.cn/Article/details/gtvmgtxbjn.html

[U44] PHP：开启严格类型
来源：http://dali.gotoacloud.top/Article/details/gtmsklbxtc.html

declare(strict_types=1);
来源：http://dali.gaohongyu789.top/Article/details/gtupscjeqp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtccqvxlpj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtbtcxvgnr.html

[U46] PHP：可空类型
来源：http://dali.kuanghao11.cn/Article/details/gtcnvrgsmt.html

?string $name = null
来源：http://dali.jqgufenzy.top/Article/details/gtjbagzfkz.html

[U47] PHP：联合类型
来源：http://dali.shanyushiyangtech.top/Article/details/gtjpgsdfqq.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtzapkbwzb.html

[U48] PHP：纯枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtrqdqfizk.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sweek.top/Article/details/gtvozgspuq.html

[U49] PHP：只读属性
来源：http://dali.jlsjyb.cn/Article/details/gtkvbrrnng.html

public readonly string $name
来源：http://dali.kuanghao11.cn/Article/details/gtdqprsdca.html

[U50] PHP：构造器属性提升
来源：http://dali.cdnleiting.top/Article/details/gtjbkowfrm.html

public function __construct(private int $id) {}
来源：http://dali.aibaodan.cn/Article/details/gtqucmleyr.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtkydjyiyu.html

[$a, $b] = $arr;
来源：http://dali.hnxiangtu.top/Article/details/gtmwxzvhvk.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmbmllyfc.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gtdcrwtfaf.html

[U53] PHP：空合并运算符
来源：http://dali.cashguo.top/Article/details/gthasbbkuf.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtzizrzwpv.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gtocqwgacf.html

$obj?->method()
来源：http://dali.hywenlv.cn/Article/details/gttjiqjzoa.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gthrafbmsp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtbbhnrxxb.html

[U56] PHP：命名参数
来源：http://dali.sysykeji.top/Article/details/gtiehxksep.html

f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gtcgcshvej.html

[U57] PHP：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtsdcwfomw.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtbngkaxha.html

[U58] PHP：数组三件套
来源：http://dali.ppjwa.cn/Article/details/gtajjtwtmd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtuxecrome.html

[U59] PHP：自定义排序
来源：http://dali.shuidangran.top/Article/details/gtdufxnfvy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.c1oappe.top/Article/details/gtpzbnniqy.html

[U60] PHP：JSON 编解码
来源：http://dali.jinghuilouyu.cn/Article/details/gtbkhqjltr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigfzy.top/Article/details/gtdbqkmpuq.html

[U61] PHP：正则
来源：http://dali.gzhubu.top/Article/details/gtfeqvurhe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.bjfxy.top/Article/details/gtfnkvepug.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtungynymj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangtech.top/Article/details/gtkrpohgtx.html

[U63] PHP：文件读写
来源：http://dali.hammf.cn/Article/details/gtnjgqkcmp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gtgoajmqwb.html

[U64] PHP：目录遍历
来源：http://dali.316326.xyz/Article/details/gtonlzfdfq.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yangfankeji.com/Article/details/gtjwbsgink.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gtzlueuyox.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtemfjnjrv.html

[U66] PHP：设置 Cookie
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfgwvcwvs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.birdmap.top/Article/details/gtcwhbhgnh.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gtxnqpwxyl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gtdrtwjqas.html

[U68] PHP：PDO 连接
来源：http://dali.xylfe.cn/Article/details/gtsitbeqra.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xuetiantiany.cn/Article/details/gtfidgbhct.html

[U69] PHP：PDO 预处理
来源：http://dali.xylfe.cn/Article/details/gtahzxrfpn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.andypj.xyz/Article/details/gtgloqffkd.html

[U70] PHP：PDO 事务
来源：http://dali.cashguo.top/Article/details/gtebwvgnad.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigufen.top/Article/details/gtppcefmms.html

[U71] PHP：抛出异常
来源：http://dali.vqdsnc.cn/Article/details/gtwleojipn.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhengqikj.top/Article/details/gtrorbjqrt.html

[U72] PHP：写错误日志
来源：http://dali.cheryme.top/Article/details/gtzdtixcmp.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zdqjudy.top/Article/details/gtcorhajvy.html

[U73] PHP：读取 ini 配置
来源：http://dali.tian-w.cn/Article/details/gtysrsjpco.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gtptuofhgh.html

[U74] PHP：读取环境变量
来源：http://dali.cashguo.top/Article/details/gthbpfowdd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ehwqpu.com/Article/details/gtmfxesrtw.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gtgsuoasgm.html

composer require psr/container
来源：http://dali.xuanzx.com/Article/details/gtmlymzmzu.html

[U76] PHP：简单路由
来源：http://dali.xinyue.icu/Article/details/gteitxvbsu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnqzz.top/Article/details/gtgjtcbsss.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gtjmmmjxtg.html

composer require twig/twig
来源：http://dali.zhixingplan.top/Article/details/gtjeqpwkcx.html

[U78] PHP：单元测试
来源：http://dali.cheryme.top/Article/details/gtgfvaejoi.html

composer require --dev phpunit/phpunit
来源：http://dali.jinyuanbaomall.cn/Article/details/gtampfiyzj.html

[U79] PHP：静态分析
来源：http://dali.jyoumei.cn/Article/details/gtqtssqooo.html

composer require --dev phpstan/phpstan
来源：http://dali.hysaishi.cn/Article/details/gteopqbczv.html

[U80] PHP：代码规范修复
来源：http://dali.ivvv.top/Article/details/gtrkcxphcc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yanxiufei.cn/Article/details/gtfpnpmdkq.html

[U81] JS：初始化项目
来源：http://dali.jqgfzy.top/Article/details/gtonxxqjqz.html

npm init -y;  npm i express
来源：http://dali.fzhhl.top/Article/details/gtpgmyzels.html

[U82] JS：package.json 脚本
来源：http://dali.0kj1m.cn/Article/details/gtkbcbxpte.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jianghu66.top/Article/details/gtqaaroezj.html

[U83] JS：ES Module 导入导出
来源：http://dali.chenlongwang.top/Article/details/gtfbfxsfby.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.havefunace.top/Article/details/gtuhvpmnsx.html

[U84] JS：CommonJS 写法
来源：http://dali.smart0.xyz/Article/details/gtiggywxyq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.iojbl.cn/Article/details/gtzkcspirq.html

[U85] JS：可选链
来源：http://dali.bjfxy.top/Article/details/gtlitbqaby.html

a?.b?.c
来源：http://dali.redwolf501.top/Article/details/gtaeuvmdwy.html

[U86] JS：空值合并
来源：http://dali.ywan-chungtsiang.top/Article/details/gthlhlaagg.html

a ?? b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmmvhhti.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtsfrvlznl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.pengpengdd.cyou/Article/details/gtvpnmytel.html

[U88] JS：对象展开合并
来源：http://dali.c1oappe.top/Article/details/gtmrxllgpw.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtlssuewmb.html

[U89] JS：数组去重
来源：http://dali.nanxinkj.top/Article/details/gtcmqwjsdz.html

[...new Set(arr)]
来源：http://dali.yuxming.cn/Article/details/gtjfdupggo.html

[U90] JS：数字数组排序
来源：http://dali.nwbrower.top/Article/details/gttdyffgrt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cdnleiting.top/Article/details/gtxnqjpbzq.html

[U91] JS：对象键值遍历
来源：http://dali.hammf.cn/Article/details/gtpvvwpozc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtuwcsslgg.html

[U92] JS：深拷贝
来源：http://dali.hammf.cn/Article/details/gtortqbwwi.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gteyhmdxqk.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gtusddwska.html

`共 ${n} 条`
来源：http://dali.cdnleiting.top/Article/details/gtdqsxsaxp.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gtazdeqwdy.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtwnbekuob.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtltoejyyw.html

new Promise((resolve, reject) => {})
来源：http://dali.jiagoushi.top/Article/details/gtcsecfrbf.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gtpzeldaqf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenzaomai.com/Article/details/gtvvisnerf.html

[U97] JS：并发请求
来源：http://dali.gzhubu.top/Article/details/gtgfyrxnyx.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gaohongyu789.top/Article/details/gtcqrqkufi.html

[U98] JS：fetch 带 JSON
来源：http://dali.fzhhl.top/Article/details/gtflbvxpfs.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.wangshuangyany.cn/Article/details/gtuksthmch.html

[U99] JS：事件监听
来源：http://dali.zhijiandao.cn/Article/details/gtmveqrxpo.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigufen.top/Article/details/gtszguwcdf.html

[U100] JS：DOM 查询
来源：http://dali.iojbl.cn/Article/details/gtodxrbipp.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gtoeymwzhv.html

[U101] JS：classList 操作
来源：http://dali.ydzc1.top/Article/details/gtousufhcf.html

el.classList.toggle("active")
来源：http://dali.yongpay.top/Article/details/gtdtibpgmj.html

[U102] JS：本地存储
来源：http://dali.birdmap.top/Article/details/gtoyykbtmg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.havefunace.top/Article/details/gtqxufsrwf.html

[U103] JS：定时器
来源：http://dali.chenzaomai.com/Article/details/gtfzakccbt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dashuyun.cn/Article/details/gtowxzorop.html

[U104] JS：防抖
来源：http://dali.shanyushiyangkeji.top/Article/details/gteadjvfwx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtzlseeinu.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtzfvgugby.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zycfv.cn/Article/details/gtnhhitvma.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtqnyywxtl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtnykcmzlh.html

[U107] JS：数字千分位
来源：http://dali.hysaishi.cn/Article/details/gteyfxqsjp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtjygyyesj.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gtnibccmqm.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtbsgrywzn.html

[U109] JS：数组分组
来源：http://dali.chenjidiqi.icu/Article/details/gtcoehymdh.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtpwhwttwp.html

[U110] JS：数组分块
来源：http://dali.yanxiufei.cn/Article/details/gtidrhzsnq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hnxiangtu.top/Article/details/gtgfwhvogb.html

[U111] JS：对象转 Map
来源：http://dali.haohaochexian.top/Article/details/gtbnjvfvyd.html

new Map(Object.entries(obj))
来源：http://dali.zhoulong.xyz/Article/details/gtaxlzravg.html

[U112] JS：字符串补位
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddnqfcco.html

"7".padStart(3, "0")
来源：http://dali.cheryme.top/Article/details/gtacwueoam.html

[U113] JS：正则替换全部
来源：http://dali.cheryme.top/Article/details/gtxxkeojzx.html

s.replaceAll("a", "b")
来源：http://dali.yvedp.cn/Article/details/gtwuqyquue.html

[U114] JS：JSON 深比较
来源：http://dali.yanxiufei.cn/Article/details/gtgnslcwxj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.haohaochexian.top/Article/details/gtvnmpabig.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtetuqfijl.html

crypto.randomUUID()
来源：http://dali.shuidangran.top/Article/details/gtzcryiyhg.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.nanxuanxn.top/Article/details/gthbzirzus.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhijiandao.cn/Article/details/gtkudwgkjv.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtcthzimnq.html

npm i -D vitest;  npx vitest
来源：http://dali.guannengcc.top/Article/details/gtckaxaprc.html

[U118] JS：开发服务器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthymkzni.html

npm i -D vite;  npx vite
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvlrfwjgj.html

[U119] JS：生产构建
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkucvrdj.html

npx vite build
来源：http://dali.jiagoushi.top/Article/details/gttcoacngw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.0kj1m.cn/Article/details/gtakzoruto.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtjlrrzdhl.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtdxvvesdy.html

统计汇总
来源：http://dali.hfpthk.cn/Article/details/gtbbzwfimh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtofvvmggx.html

按语言统计（条）：
来源：http://dali.hnxiangtu.top/Article/details/gtvpugojoz.html

Python ......... 252
来源：http://dali.birdmap.top/Article/details/gtafuueabm.html

PHP ............ 252
来源：http://dali.vqdsnc.cn/Article/details/gtvhztfrle.html

JavaScript ..... 252
来源：http://dali.shzxlz.cn/Article/details/gtmjowsoce.html

TypeScript ..... 212
来源：http://dali.xziqi.cn/Article/details/gtzvclxfal.html

Java ........... 212
来源：http://dali.mhx1999.top/Article/details/gtihjeyels.html

Go ............. 212
来源：http://dali.havefunace.top/Article/details/gtrnslddyr.html

Ruby ........... 212
来源：http://dali.guannengcc.top/Article/details/gtntvdtbkf.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtpshrclyu.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtkuqzctsb.html

C++ ............ 30
来源：http://dali.dianchejie.cn/Article/details/gtkaypdouz.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gtsgnwmsgv.html

Bash ........... 80
来源：http://dali.yongpay.top/Article/details/gtypmyedmm.html

Kotlin ......... 15
来源：http://dali.sxryk.cn/Article/details/gtgghtqtzm.html

Swift .......... 15
来源：http://dali.gaohongyu789.top/Article/details/gtkbleizpm.html

Lua ............ 10
来源：http://dali.smart0.xyz/Article/details/gtzsfeguth.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtnfcpkwbn.html

Scala .......... 10
来源：http://dali.xylfe.cn/Article/details/gtetfvtuly.html

------------------------------------
来源：http://dali.hammf.cn/Article/details/gtkrxrirgp.html

合计 ........... 2106 条
来源：http://dali.nanxinkj.top/Article/details/gtzwwhkpkk.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbvmaogk.html


<!-- 参考信息 -->