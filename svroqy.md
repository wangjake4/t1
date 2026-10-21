代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtuezdkadm.html

for my $x (@arr) { print $x; }
来源：http://dali.snrcjt.cn/Article/details/gttonstgvg.html

[T46] Perl：哈希操作
来源：http://dali.kuanghao11.cn/Article/details/gthspydfgm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtwqgykfjl.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtzxtwlagv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gtuvatfrvc.html

[T48] Perl：正则替换
来源：http://dali.shangyingyoupin.top/Article/details/gteqlsuzhq.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtgwamnkxd.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtubiofqnz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtpagpokrl.html

[T50] Perl：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gttgnxtlde.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpljlcokw.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtldxkfoeo.html

[T51] Scala：Hello World
来源：http://dali.daxiang520.top/Article/details/gtiaaelgsz.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gtqzrpjfoe.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtxyawlbac.html

val a = 1;  var b = 2
来源：http://dali.jiagoushi.top/Article/details/gtfedcgrom.html

[T53] Scala：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtehjwmrwh.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtvabkatzn.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gttrtgfiuy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.havefunace.top/Article/details/gtezxieyoj.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtrctaykys.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtseerhysa.html

[T56] Scala：样例类
来源：http://dali.gzhubu.top/Article/details/gtyxhjwkii.html

case class User(name: String, age: Int)
来源：http://dali.sweek.top/Article/details/gthlcnjarl.html

[T57] Scala：模式匹配
来源：http://dali.andypj.xyz/Article/details/gtqouuxjxb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtxdovggke.html

[T58] Scala：函数定义
来源：http://dali.sufxvd.cn/Article/details/gtiswalqjn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gttbybcdqr.html

[T59] Scala：循环
来源：http://dali.snrcjt.cn/Article/details/gtmyviweaa.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtadovwpqq.html

[T60] Scala：折叠
来源：http://dali.zhoulong.xyz/Article/details/gtfqkzxtwe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj202588.top/Article/details/gtyfnkymmc.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpsxgkoje.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ivvv.top/Article/details/gtsztfdexi.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gthyhxkzec.html

[U01] Py：创建虚拟环境
来源：http://dali.gotoacloud.top/Article/details/gtfhrjjyvp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gttcjafwsb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtxunehjtm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtjatctyct.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtljawxqeb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yueranfly.top/Article/details/gtthjwavee.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtvsgypyrk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zdqjudy.top/Article/details/gtlixxdmwd.html

[U05] Py：列表去重且保序
来源：http://dali.pycfn.com/Article/details/gtvinpwyvn.html

list(dict.fromkeys(arr))
来源：http://dali.zhengqikj.top/Article/details/gtrnmlhrts.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtbcmtqmbr.html

{**a, **b}
来源：http://dali.dashuyun.cn/Article/details/gtesvvchqn.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtzqsodlhb.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtigylthnd.html

[U08] Py：展平二维列表
来源：http://dali.shuidangran.top/Article/details/gtjnfyvufm.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtpgoxtjbj.html

[U09] Py：字典取最大值的键
来源：http://dali.pengpengdd.cyou/Article/details/gtbyttozkr.html

max(d, key=d.get)
来源：http://dali.sysykeji.top/Article/details/gtkcgdtyaz.html

[U10] Py：按值排序字典
来源：http://dali.fzhhl.top/Article/details/gtxbiduyot.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.snrcjt.cn/Article/details/gtriyojmnh.html

[U11] Py：生成器表达式
来源：http://dali.wangshuangyany.cn/Article/details/gtfxhwepnn.html

(x * 2 for x in arr)
来源：http://dali.gaohongyu789.top/Article/details/gtmgmovixj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.wangdashe.top/Article/details/gtisonjfvp.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtkwrhtvqa.html

[U13] Py：固定长度队列
来源：http://dali.xuanzx.com/Article/details/gtzzestaph.html

deque(maxlen=10)
来源：http://dali.yongpay.top/Article/details/gtssqafeyq.html

[U14] Py：分组收集到列表
来源：http://dali.yongpay.top/Article/details/gttwduuudy.html

defaultdict(list)
来源：http://dali.cashguo.top/Article/details/gtvgpgyiqa.html

[U15] Py：高精度计时
来源：http://dali.haohaochexian.top/Article/details/gtalremttj.html

t = time.perf_counter()
来源：http://dali.hfpthk.cn/Article/details/gtgxrpqcxk.html

[U16] Py：命令行参数解析
来源：http://dali.ehwqpu.com/Article/details/gtxjsxyvhd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtztalnbzh.html

[U17] Py：初始化日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjgjivaav.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqwtovpn.html

[U18] Py：预编译正则
来源：http://dali.jqgufenzy.top/Article/details/gtgigxkrnb.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtjkhxrsts.html

[U19] Py：正则替换带回调
来源：http://dali.havefunace.top/Article/details/gtwzbqpkig.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuxming.cn/Article/details/gtadipukqb.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtmkwoqtyx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yuanzhike.top/Article/details/gtzteasrqz.html

[U21] Py：自定义上下文管理器
来源：http://dali.tanke756.top/Article/details/gtpgzcixby.html

@contextlib.contextmanager
来源：http://dali.yuxming.cn/Article/details/gtuaudpzcw.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gtfwxsxhrt.html

list(zip(*m))
来源：http://dali.ppjwa.cn/Article/details/gtpircbegy.html

[U23] Py：分块读取大文件
来源：http://dali.kuanghao11.cn/Article/details/gtxbmvbqkm.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.iojbl.cn/Article/details/gttmyogrvm.html

[U24] Py：路径操作
来源：http://dali.zdqjudy.top/Article/details/gtnrwylsyi.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jyoumei.cn/Article/details/gtozjxazbg.html

[U25] Py：CSV 按字典读
来源：http://dali.jiagoushi.top/Article/details/gtcolyrqev.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtqvfoxbqm.html

[U26] Py：并发下载
来源：http://dali.cucudq.cn/Article/details/gtwovxncui.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shzxlz.cn/Article/details/gtkaqbrmty.html

[U27] Py：异步 HTTP
来源：http://dali.hnxiangtu.top/Article/details/gtsnmfcpgx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dianchejie.cn/Article/details/gtcytirpbk.html

[U28] Py：类型别名
来源：http://dali.jlsjyb.cn/Article/details/gtoltjogug.html

UserId = int
来源：http://dali.sxryk.cn/Article/details/gtganmuuvb.html

[U29] Py：属性校验
来源：http://dali.guannengcc.top/Article/details/gtdvbceqpx.html

@property 与 @x.setter 配合
来源：http://dali.quarkkingdee.top/Article/details/gthojngdhd.html

[U30] Py：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gttcapiycx.html

@dataclass(slots=True)
来源：http://dali.smart0.xyz/Article/details/gtarauwowx.html

[U31] Py：单测
来源：http://dali.xziqi.cn/Article/details/gtyqltzsik.html

python -m pytest -q
来源：http://dali.0kj1m.cn/Article/details/gtrwiwtlxd.html

[U32] Py：代码格式化
来源：http://dali.yangfankeji.com/Article/details/gtybnghene.html

ruff format . && ruff check --fix .
来源：http://dali.dashuyun.cn/Article/details/gtujkdagzo.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gttdkyllnz.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenzaomai.com/Article/details/gtgesnzvdh.html

[U34] Py：判断编码
来源：http://dali.cashguo.top/Article/details/gtobbqxvfu.html

chardet.detect(raw)
来源：http://dali.0kj1m.cn/Article/details/gtjruceeoj.html

[U35] Py：发送邮件
来源：http://dali.yuxming.cn/Article/details/gtjkppofiy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj20258888.top/Article/details/gtzssnsvts.html

[U36] Py：定时任务
来源：http://dali.chenzaomai.com/Article/details/gtjujbcqgj.html

schedule.every(10).minutes.do(job)
来源：http://dali.hysaishi.cn/Article/details/gtjftjrstg.html

[U37] Py：读写 Excel
来源：http://dali.hfpthk.cn/Article/details/gtpjpvfeuq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.fengsongda.top/Article/details/gtyignqwmt.html

[U38] Py：获取脚本所在目录
来源：http://dali.wangdashe.top/Article/details/gtlxlgcfoa.html

Path(__file__).resolve().parent
来源：http://dali.yongpay.top/Article/details/gtaxkdctvb.html

[U39] Py：判断是否在交互环境
来源：http://dali.jqgfzy.top/Article/details/gtkfehrpww.html

sys.stdout.isatty()
来源：http://dali.smart0.xyz/Article/details/gtahuuzuiz.html

[U40] Py：打印到标准错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqszdfdnn.html

print("err", file=sys.stderr)
来源：http://dali.zhongyouzk.top/Article/details/gthyilcsmt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gtaauozgzu.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jlsjyb.cn/Article/details/gtmznxshcs.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.mhx1999.top/Article/details/gtkryteohr.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtwzqgiiqz.html

[U43] PHP：声明命名空间
来源：http://dali.yuxming.cn/Article/details/gtfiqrkaat.html

namespace App\Http;
来源：http://dali.zdqjudy.top/Article/details/gtovkbnmbm.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gtkcpbgubm.html

declare(strict_types=1);
来源：http://dali.zycfv.cn/Article/details/gtbfbvxfdw.html

[U45] PHP：类型声明与返回类型
来源：http://dali.guannengcc.top/Article/details/gtdhhhqlgp.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtdmrlfboe.html

[U46] PHP：可空类型
来源：http://dali.gotoacloud.top/Article/details/gtwnxymhil.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gtxbdriawe.html

[U47] PHP：联合类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvehoeeyw.html

int|string $id
来源：http://dali.sxryk.cn/Article/details/gtzazdusbm.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gtwxdjyztp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tanke756.top/Article/details/gtysdgsosm.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtkbcvtcyd.html

public readonly string $name
来源：http://dali.hongshengwenyu.top/Article/details/gtjwwhxswp.html

[U50] PHP：构造器属性提升
来源：http://dali.jinghuilouyu.cn/Article/details/gtpdjxcdnf.html

public function __construct(private int $id) {}
来源：http://dali.yuxming.cn/Article/details/gthddlphtr.html

[U51] PHP：数组解构
来源：http://dali.9152youxi.cn/Article/details/gtbnzhlfql.html

[$a, $b] = $arr;
来源：http://dali.svipenyu.cn/Article/details/gtmnoautvs.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gthmdopowj.html

$double = fn($x) => $x * 2;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxdwbnht.html

[U53] PHP：空合并运算符
来源：http://dali.tian-w.cn/Article/details/gtoomnuftc.html

$v = $a ?? $b ?? "default";
来源：http://dali.ydzc1.top/Article/details/gtweejyqoa.html

[U54] PHP：空安全调用
来源：http://dali.svipenyu.cn/Article/details/gtvijmasoo.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gttmznszev.html

[U55] PHP：match 表达式
来源：http://dali.nanxinkj.top/Article/details/gtnnzdjuve.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gtdixctgeh.html

[U56] PHP：命名参数
来源：http://dali.ybcxt.top/Article/details/gtdpfcymqh.html

f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtzcxswnwi.html

[U57] PHP：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtudgvtuzr.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtfpbvddyk.html

[U58] PHP：数组三件套
来源：http://dali.shuidangran.top/Article/details/gtwbmtssbn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gtfszhinyr.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtuxmagmci.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.pengpengdd.cyou/Article/details/gtnljypara.html

[U60] PHP：JSON 编解码
来源：http://dali.aizwys.cn/Article/details/gthdzjbxml.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zdqjudy.top/Article/details/gttegpqqpd.html

[U61] PHP：正则
来源：http://dali.yj20258888.top/Article/details/gtjrkvbyjo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.nwbrower.top/Article/details/gtgikdcbwy.html

[U62] PHP：日期对象
来源：http://dali.wangshuangyany.cn/Article/details/gtmoywikmu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtwafalfst.html

[U63] PHP：文件读写
来源：http://dali.cdnleiting.top/Article/details/gtmpvwjdkc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xylfe.cn/Article/details/gtejslcxab.html

[U64] PHP：目录遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmbehmcy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.kuanghao11.cn/Article/details/gtyzvfvuka.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gtnqldbeos.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtmcyqeijc.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gturwlbdhd.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gzhubu.top/Article/details/gtcpgypfzo.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gteebssyyg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ppjwa.cn/Article/details/gtsrvhizmu.html

[U68] PHP：PDO 连接
来源：http://dali.jyoumei.cn/Article/details/gtelbzqwuz.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj20258888.top/Article/details/gtjwmrdcmz.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgufenzy.top/Article/details/gtgfqxrznl.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gtkxlkbxtb.html

[U70] PHP：PDO 事务
来源：http://dali.andypj.xyz/Article/details/gtgwtbuwaj.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gogol.net.cn/Article/details/gtshzaknqf.html

[U71] PHP：抛出异常
来源：http://dali.smart0.xyz/Article/details/gtljippnjk.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhoulong.xyz/Article/details/gtlgyufptt.html

[U72] PHP：写错误日志
来源：http://dali.nanxuanxn.top/Article/details/gtnfivnbog.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sysykeji.top/Article/details/gtlfapglxc.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gtjgttttup.html

parse_ini_file("config.ini", true)
来源：http://dali.aibaodan.cn/Article/details/gtrebpcrrs.html

[U74] PHP：读取环境变量
来源：http://dali.jinqigufen.top/Article/details/gtokncwdyt.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ydzc1.top/Article/details/gtfbycuubp.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtebxjosoy.html

composer require psr/container
来源：http://dali.mhx1999.top/Article/details/gtjgulckwu.html

[U76] PHP：简单路由
来源：http://dali.redwolf501.top/Article/details/gtsdxnpxkf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtzpvzxoao.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtobaakndj.html

composer require twig/twig
来源：http://dali.hywenlv.cn/Article/details/gtmiglvggl.html

[U78] PHP：单元测试
来源：http://dali.9152youxi.cn/Article/details/gtcfurityp.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgufenzy.top/Article/details/gteqzakkfy.html

[U79] PHP：静态分析
来源：http://dali.meibo888.top/Article/details/gtkgirqyuq.html

composer require --dev phpstan/phpstan
来源：http://dali.zhoulong.xyz/Article/details/gtekiwojce.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcxrlouxr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258888.top/Article/details/gtixormtss.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gtnqextznd.html

npm init -y;  npm i express
来源：http://dali.zhiwuduotai.top/Article/details/gtvhuripnr.html

[U82] JS：package.json 脚本
来源：http://dali.gzhubu.top/Article/details/gtzewgvvwf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtbozukulf.html

[U83] JS：ES Module 导入导出
来源：http://dali.hnqzz.top/Article/details/gtmswmhlte.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guowangkeji.top/Article/details/gtixrptjyo.html

[U84] JS：CommonJS 写法
来源：http://dali.shanyushiyangtech.top/Article/details/gtsincwyvj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sysykeji.top/Article/details/gtxvbnzthl.html

[U85] JS：可选链
来源：http://dali.yangfankeji.com/Article/details/gtrljxmsls.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtwgokzrbg.html

[U86] JS：空值合并
来源：http://dali.zhixingplan.top/Article/details/gttnkinvru.html

a ?? b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpzmyptf.html

[U87] JS：解构默认值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrjeytcc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hywenlv.cn/Article/details/gtghwhijcz.html

[U88] JS：对象展开合并
来源：http://dali.daxiang520.top/Article/details/gtedmhvrer.html

{ ...a, ...b }
来源：http://dali.zycfv.cn/Article/details/gtjpxvdbxi.html

[U89] JS：数组去重
来源：http://dali.daxiang520.top/Article/details/gtxerhufny.html

[...new Set(arr)]
来源：http://dali.xziqi.cn/Article/details/gtlvfeiyfo.html

[U90] JS：数字数组排序
来源：http://dali.yuxming.cn/Article/details/gtgtilaxjq.html

[...arr].sort((a, b) => a - b)
来源：http://dali.dashuyun.cn/Article/details/gtclhgzkyk.html

[U91] JS：对象键值遍历
来源：http://dali.jiagoushi.top/Article/details/gtrbzebcxk.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagdwzgbg.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gtnptcrwcd.html

structuredClone(obj)
来源：http://dali.sweek.top/Article/details/gtuaqttjrl.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtzqiwvqfe.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtgpwulbhj.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gtwgnohmiz.html

const double = x => x * 2;
来源：http://dali.zhijiandao.cn/Article/details/gtmhyndsko.html

[U95] JS：Promise 包装
来源：http://dali.ehwqpu.com/Article/details/gtpfmobivf.html

new Promise((resolve, reject) => {})
来源：http://dali.hfpthk.cn/Article/details/gtaxbfebul.html

[U96] JS：async/await 与异常
来源：http://dali.zhongyouzk.top/Article/details/gtjxobwmeh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jqgufenzy.top/Article/details/gtpqxepsbx.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gtzmotlqdn.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.nanxinkj.top/Article/details/gtbypzqtqk.html

[U98] JS：fetch 带 JSON
来源：http://dali.jyoumei.cn/Article/details/gtjwpfutzd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gtzcgzilqf.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gtowbrimdj.html

el.addEventListener("click", e => {})
来源：http://dali.yueranfly.top/Article/details/gtqltiqcrr.html

[U100] JS：DOM 查询
来源：http://dali.pengpengdd.cyou/Article/details/gtpuehifno.html

document.querySelector(".item")
来源：http://dali.dianchejie.cn/Article/details/gthdbsrgrz.html

[U101] JS：classList 操作
来源：http://dali.havefunace.top/Article/details/gtxkqfozmm.html

el.classList.toggle("active")
来源：http://dali.nanxuanxn.top/Article/details/gtmhoenemw.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtfijqonis.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gtldayaezc.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gtuvxlvalf.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.gotoacloud.top/Article/details/gtrimqwvyj.html

[U104] JS：防抖
来源：http://dali.iojbl.cn/Article/details/gttlglcrjm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.bjfxy.top/Article/details/gtiptvzdue.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtmonilskb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pycfn.com/Article/details/gtsertwlya.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtzphamspl.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfhlcpsdv.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gtjnadriwb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gtxidpdcpm.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gtnlcfwewo.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.snrcjt.cn/Article/details/gtixhuigqk.html

[U109] JS：数组分组
来源：http://dali.hywenlv.cn/Article/details/gttdmpurdn.html

Object.groupBy(arr, x => x.type)
来源：http://dali.smart0.xyz/Article/details/gtbsxnxivd.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gttkgoreeh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gthabpaefu.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvekmokbj.html

new Map(Object.entries(obj))
来源：http://dali.zhiwuduotai.top/Article/details/gtjrtkpjxc.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtxkkpbplv.html

"7".padStart(3, "0")
来源：http://dali.tian-w.cn/Article/details/gtyhsywgez.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gtnlagxqtm.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtupulijzb.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gtdpbxjfsb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.cashguo.top/Article/details/gtpvqkymhn.html

[U115] JS：生成 UUID
来源：http://dali.fengsongda.top/Article/details/gtnlbaotds.html

crypto.randomUUID()
来源：http://dali.zhengqikj.top/Article/details/gtjkjdrrvq.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yuxming.cn/Article/details/gtkuizdjvw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.andypj.xyz/Article/details/gtdmnrzcve.html

[U117] JS：单元测试
来源：http://dali.xinyue.icu/Article/details/gtomonwjtq.html

npm i -D vitest;  npx vitest
来源：http://dali.yvedp.cn/Article/details/gtbhqsqwlj.html

[U118] JS：开发服务器
来源：http://dali.kuanghao11.cn/Article/details/gtghcqmaiw.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gtpgqugorp.html

[U119] JS：生产构建
来源：http://dali.gzhubu.top/Article/details/gtyasexjus.html

npx vite build
来源：http://dali.yvedp.cn/Article/details/gtcjyrdgdw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.kuanghao11.cn/Article/details/gtedhsoslm.html

import.meta.env.VITE_API_URL
来源：http://dali.zhongyouzk.top/Article/details/gtziiksnql.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdzwmhxsz.html

统计汇总
来源：http://dali.ppjwa.cn/Article/details/gtqnryefqr.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzmepxtjg.html

按语言统计（条）：
来源：http://dali.jianghu66.top/Article/details/gtioxgucaz.html

Python ......... 252
来源：http://dali.svipenyu.cn/Article/details/gtbcmmymlz.html

PHP ............ 252
来源：http://dali.sxryk.cn/Article/details/gtfhjbusnr.html

JavaScript ..... 252
来源：http://dali.yueranfly.top/Article/details/gthrqstarn.html

TypeScript ..... 212
来源：http://dali.tian-w.cn/Article/details/gtojpgxdll.html

Java ........... 212
来源：http://dali.hnqzz.top/Article/details/gtgfwtspts.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gtbajpwamj.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgteciil.html

C# ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtuxqxibps.html

C .............. 30
来源：http://dali.yueranfly.top/Article/details/gtlvniosbv.html

C++ ............ 30
来源：http://dali.yj20258888.top/Article/details/gtarmzsndy.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gthzntevqw.html

Bash ........... 80
来源：http://dali.fengsongda.top/Article/details/gtciaowxsg.html

Kotlin ......... 15
来源：http://dali.zhongyouzk.top/Article/details/gtqgtttjlg.html

Swift .......... 15
来源：http://dali.hysaishi.cn/Article/details/gtjsjdxotz.html

Lua ............ 10
来源：http://dali.sysykeji.top/Article/details/gtnpqdnoav.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtkatxizkd.html

Scala .......... 10
来源：http://dali.hysaishi.cn/Article/details/gtqxtsuwzy.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtezflqvmj.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gtbwwvdzmy.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gthwdsvnku.html


<!-- 参考信息 -->