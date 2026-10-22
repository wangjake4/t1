代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gt2lrnxuqal.html

for my $x (@arr) { print $x; }
来源：http://dali.yueranfly.top/Article/details/gt2dclxzhxj.html

[T46] Perl：哈希操作
来源：http://dali.xziqi.cn/Article/details/gt2ppubefao.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2bkhknvks.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zarqsyqm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.guannengcc.top/Article/details/gt2piiwbvdf.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gt2qezrvbwp.html

$s =~ s/old/new/g;
来源：http://dali.yj20258888.top/Article/details/gt2cqcrtxft.html

[T49] Perl：函数
来源：http://dali.jinqigufen.top/Article/details/gt2sqbmrijf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gt2hhrgosoa.html

[T50] Perl：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eftpusjz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gt2dlsskcdx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sufxvd.cn/Article/details/gt2wmlildks.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2eacnczuy.html

println("Hello")
来源：http://dali.yangfankeji.com/Article/details/gt2svtobgdd.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2ezrtmobv.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gt2swexobjz.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2obdzqrdo.html

s"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gt2mrifpxmf.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gt2benimjjb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shzxlz.cn/Article/details/gt2cdwghidx.html

[T55] Scala：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2tmkovdur.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hoxlykmn.html

[T56] Scala：样例类
来源：http://dali.cashguo.top/Article/details/gt2nuaymkrh.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gt2ewlwbffv.html

[T57] Scala：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gt2ojfvnwry.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yongpay.top/Article/details/gt2pccstpof.html

[T58] Scala：函数定义
来源：http://dali.hongshengwenyu.top/Article/details/gt2ygzjewfk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gt2ylqbkcsu.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2awiizkqa.html

for (i <- 1 to 10) println(i)
来源：http://dali.meibo888.top/Article/details/gt2udmhrtsi.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gt2ljqauuqn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2ztmvtics.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2fyvzcabd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gt2dbvqwdbq.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2hivlohac.html

[U01] Py：创建虚拟环境
来源：http://dali.xinyue.icu/Article/details/gt2kaoyeiuu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aibaodan.cn/Article/details/gt2sgbwcmlb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nanxuanxn.top/Article/details/gt2fhopjrko.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gt2lysspyib.html

[U03] Py：加载 .env 配置
来源：http://dali.zycfv.cn/Article/details/gt2rvxnyfaz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gt2nnwucvkq.html

[U04] Py：变量调试打印
来源：http://dali.0kj1m.cn/Article/details/gt2ananssie.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxinkj.top/Article/details/gt2mxdilynu.html

[U05] Py：列表去重且保序
来源：http://dali.zhongyouzk.top/Article/details/gt2gmqfmucf.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2xfwarnef.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gt2tfygdtxy.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gt2msgfvnfg.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gt2hvoetjwd.html

{v: k for k, v in d.items()}
来源：http://dali.tanke756.top/Article/details/gt2ffjsyvns.html

[U08] Py：展平二维列表
来源：http://dali.tian-w.cn/Article/details/gt2cymaswwj.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gt2bxantwla.html

[U09] Py：字典取最大值的键
来源：http://dali.jqgfzy.top/Article/details/gt2rdyqmysj.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gt2olwywyea.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gt2jyrgzgll.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.meibo888.top/Article/details/gt2alcgwuhb.html

[U11] Py：生成器表达式
来源：http://dali.xziqi.cn/Article/details/gt2wuunejhf.html

(x * 2 for x in arr)
来源：http://dali.tanke756.top/Article/details/gt2chnkipmg.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xwgheutq.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gt2fpedyblr.html

[U13] Py：固定长度队列
来源：http://dali.guowangkeji.top/Article/details/gt2saexcohd.html

deque(maxlen=10)
来源：http://dali.yangfankeji.com/Article/details/gt2uwgarecl.html

[U14] Py：分组收集到列表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hskokvpc.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gt2yjbbrjud.html

[U15] Py：高精度计时
来源：http://dali.hnqzz.top/Article/details/gt2mzapnvqk.html

t = time.perf_counter()
来源：http://dali.gaohongyu789.top/Article/details/gt2masrnruu.html

[U16] Py：命令行参数解析
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2reiopjpc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhijiandao.cn/Article/details/gt2zqplietr.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gt2sulruxdr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gt2umpjscbo.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gt2zozqskog.html

pat = re.compile(r"\d+")
来源：http://dali.chenlongwang.top/Article/details/gt2pnchmurq.html

[U19] Py：正则替换带回调
来源：http://dali.wangdashe.top/Article/details/gt2xhmnsopi.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zclftcak.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gt2vtnmdwhg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.tian-w.cn/Article/details/gt2wyeaquqn.html

[U21] Py：自定义上下文管理器
来源：http://dali.ydzc1.top/Article/details/gt2fqimuicf.html

@contextlib.contextmanager
来源：http://dali.yongpay.top/Article/details/gt2vmmadhso.html

[U22] Py：矩阵转置
来源：http://dali.guannengcc.top/Article/details/gt2zdvdflhj.html

list(zip(*m))
来源：http://dali.gogol.net.cn/Article/details/gt2bfvqpomu.html

[U23] Py：分块读取大文件
来源：http://dali.pycfn.com/Article/details/gt2jxpsqsum.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jianghu66.top/Article/details/gt2jktqflas.html

[U24] Py：路径操作
来源：http://dali.yangfankeji.com/Article/details/gt2ccdxyqpe.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.redwolf501.top/Article/details/gt2qeccaezd.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gt2zanbyamc.html

csv.DictReader(f)
来源：http://dali.ydzc1.top/Article/details/gt2cofmmkdb.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2hamzhiur.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2frblgfrj.html

[U27] Py：异步 HTTP
来源：http://dali.ydzc1.top/Article/details/gt2rnjhscvy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gt2bxdgmvnv.html

[U28] Py：类型别名
来源：http://dali.shangyingyoupin.top/Article/details/gt2nbqnjagk.html

UserId = int
来源：http://dali.quarkkingdee.top/Article/details/gt2kgndkiqf.html

[U29] Py：属性校验
来源：http://dali.jlsjyb.cn/Article/details/gt2fjftwkwo.html

@property 与 @x.setter 配合
来源：http://dali.andypj.xyz/Article/details/gt2lqlbvjhl.html

[U30] Py：数据类
来源：http://dali.andypj.xyz/Article/details/gt2sgsbupqx.html

@dataclass(slots=True)
来源：http://dali.316326.xyz/Article/details/gt2tqocqaig.html

[U31] Py：单测
来源：http://dali.tianlin.xyz/Article/details/gt2atgnciab.html

python -m pytest -q
来源：http://dali.cdnleiting.top/Article/details/gt2ffxiknle.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gt2evjgiatj.html

ruff format . && ruff check --fix .
来源：http://dali.snrcjt.cn/Article/details/gt2bedptkhs.html

[U33] Py：打包发布
来源：http://dali.shuidangran.top/Article/details/gt2ghopprmg.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.birdmap.top/Article/details/gt2cvorfkgf.html

[U34] Py：判断编码
来源：http://dali.zdqjudy.top/Article/details/gt2fiykazsz.html

chardet.detect(raw)
来源：http://dali.gotoacloud.top/Article/details/gt2jehkqlli.html

[U35] Py：发送邮件
来源：http://dali.wangdashe.top/Article/details/gt2byhwdmxg.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cqqwz.cn/Article/details/gt2ugfxmgtd.html

[U36] Py：定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2ddolnxkq.html

schedule.every(10).minutes.do(job)
来源：http://dali.xuanzx.com/Article/details/gt2blfyxuzm.html

[U37] Py：读写 Excel
来源：http://dali.316326.xyz/Article/details/gt2fbahkwrf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2qnajgnnq.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcfsrvle.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gt2bdzmmxzi.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2otxiuxku.html

sys.stdout.isatty()
来源：http://dali.aibaodan.cn/Article/details/gt2pcffdrpu.html

[U40] Py：打印到标准错误
来源：http://dali.nwbrower.top/Article/details/gt2okxptnub.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gt2bbdvkjbz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.c1oappe.top/Article/details/gt2rjwplefn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yj202588.top/Article/details/gt2hismiain.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jiagoushi.top/Article/details/gt2zgrllfut.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnxiangtu.top/Article/details/gt2wxmpsdbw.html

[U43] PHP：声明命名空间
来源：http://dali.xylfe.cn/Article/details/gt2bjlmrcvk.html

namespace App\Http;
来源：http://dali.shangyingyoupin.top/Article/details/gt2dmpsdiwm.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gt2fyvnhkxs.html

declare(strict_types=1);
来源：http://dali.gogol.net.cn/Article/details/gt2gwannpvu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.dashuyun.cn/Article/details/gt2xoqqnqkq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2obqbnkef.html

[U46] PHP：可空类型
来源：http://dali.daria6918.cn/Article/details/gt2uymqqtnp.html

?string $name = null
来源：http://dali.shzxlz.cn/Article/details/gt2wjztnfzf.html

[U47] PHP：联合类型
来源：http://dali.pengpengdd.cyou/Article/details/gt2rrorbhze.html

int|string $id
来源：http://dali.cucudq.cn/Article/details/gt2csvjjark.html

[U48] PHP：纯枚举
来源：http://dali.ppjwa.cn/Article/details/gt2gyoffszw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.cheryme.top/Article/details/gt2vlmfidpi.html

[U49] PHP：只读属性
来源：http://dali.guannengcc.top/Article/details/gt2gqwqwqzb.html

public readonly string $name
来源：http://dali.sweek.top/Article/details/gt2yiwmckww.html

[U50] PHP：构造器属性提升
来源：http://dali.mhx1999.top/Article/details/gt2ywxmgugz.html

public function __construct(private int $id) {}
来源：http://dali.tian-w.cn/Article/details/gt2iwtwflwj.html

[U51] PHP：数组解构
来源：http://dali.nanxuanxn.top/Article/details/gt2liaejecy.html

[$a, $b] = $arr;
来源：http://dali.chenlongwang.top/Article/details/gt2ulrfoskp.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2yykqofhz.html

$double = fn($x) => $x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2zcopoepl.html

[U53] PHP：空合并运算符
来源：http://dali.sxryk.cn/Article/details/gt2dupwbmtb.html

$v = $a ?? $b ?? "default";
来源：http://dali.yj20258888.top/Article/details/gt2fkqdqbdi.html

[U54] PHP：空安全调用
来源：http://dali.hnxiangtu.top/Article/details/gt2mchzxabg.html

$obj?->method()
来源：http://dali.hysaishi.cn/Article/details/gt2dllwpayh.html

[U55] PHP：match 表达式
来源：http://dali.andypj.xyz/Article/details/gt2hipwipbg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2rgkuhdjc.html

[U56] PHP：命名参数
来源：http://dali.hammf.cn/Article/details/gt2flfljjwd.html

f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2lvnkscvi.html

[U57] PHP：字符串插值
来源：http://dali.havefunace.top/Article/details/gt2euoxdoeq.html

"值: {$a}"
来源：http://dali.yangfankeji.com/Article/details/gt2pcvanpjd.html

[U58] PHP：数组三件套
来源：http://dali.yuanzhike.top/Article/details/gt2wjoptkgz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.dashuyun.cn/Article/details/gt2ohnbthlb.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gt2fxzmzysh.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gt2anbhvsvz.html

[U60] PHP：JSON 编解码
来源：http://dali.hammf.cn/Article/details/gt2lopkfeft.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.bjfxy.top/Article/details/gt2prpyxoqr.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gt2jbwsuhlf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gt2eryzsywy.html

[U62] PHP：日期对象
来源：http://dali.cqqwz.cn/Article/details/gt2cbijjrob.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yongpay.top/Article/details/gt2hsiyakpc.html

[U63] PHP：文件读写
来源：http://dali.hfpthk.cn/Article/details/gt2atpfnhko.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwjajmhk.html

[U64] PHP：目录遍历
来源：http://dali.daxiang520.top/Article/details/gt2ambaesan.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhengqikj.top/Article/details/gt2gnwrgsqf.html

[U65] PHP：会话
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txslgbtr.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gt2jfpxqbnq.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2zihthbij.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jqgfzy.top/Article/details/gt2rukywaaz.html

[U67] PHP：处理文件上传
来源：http://dali.hammf.cn/Article/details/gt2ibkqkash.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ehwqpu.com/Article/details/gt2nbfxbmyw.html

[U68] PHP：PDO 连接
来源：http://dali.shuidangran.top/Article/details/gt2dgrlopnn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhongyouzk.top/Article/details/gt2cqpkcrpx.html

[U69] PHP：PDO 预处理
来源：http://dali.daria6918.cn/Article/details/gt2epsgpskd.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gt2mxwufgyl.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gt2usujstjk.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fengsongda.top/Article/details/gt2zfflqcgu.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gt2ncospqcb.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigfzy.top/Article/details/gt2tvgrsfok.html

[U72] PHP：写错误日志
来源：http://dali.daxiang520.top/Article/details/gt2dpkemhde.html

error_log("失败: " . $e->getMessage());
来源：http://dali.9152youxi.cn/Article/details/gt2xwbnarbj.html

[U73] PHP：读取 ini 配置
来源：http://dali.aibaodan.cn/Article/details/gt2qipmzbug.html

parse_ini_file("config.ini", true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkhmvxkc.html

[U74] PHP：读取环境变量
来源：http://dali.guowangkeji.top/Article/details/gt2vbrsxivx.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jlsjyb.cn/Article/details/gt2vfdcqdlc.html

[U75] PHP：依赖注入
来源：http://dali.cqqwz.cn/Article/details/gt2ogzistdu.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gt2jralytmz.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gt2cramxyuf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hfpthk.cn/Article/details/gt2hdsvgjgv.html

[U77] PHP：模板渲染
来源：http://dali.yvedp.cn/Article/details/gt2pjbghgva.html

composer require twig/twig
来源：http://dali.xinyue.icu/Article/details/gt2txaefrzg.html

[U78] PHP：单元测试
来源：http://dali.aizwys.cn/Article/details/gt2ckebhtrm.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gt2sscphegu.html

[U79] PHP：静态分析
来源：http://dali.quarkkingdee.top/Article/details/gt2psqedbuo.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gt2tqcdhhmh.html

[U80] PHP：代码规范修复
来源：http://dali.gaohongyu789.top/Article/details/gt2pgqzpeqy.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nanxuanxn.top/Article/details/gt2mrhamicd.html

[U81] JS：初始化项目
来源：http://dali.gaohongyu789.top/Article/details/gt2rwoqslde.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxzgsoye.html

[U82] JS：package.json 脚本
来源：http://dali.dianchejie.cn/Article/details/gt2erftchwr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ehwqpu.com/Article/details/gt2avtvsgsb.html

[U83] JS：ES Module 导入导出
来源：http://dali.ppjwa.cn/Article/details/gt2sbzytrtz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.kuanghao11.cn/Article/details/gt2nmvllbiw.html

[U84] JS：CommonJS 写法
来源：http://dali.sufxvd.cn/Article/details/gt2fbshuxhx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yanxiufei.cn/Article/details/gt2rjpjdstc.html

[U85] JS：可选链
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gxqvmnwe.html

a?.b?.c
来源：http://dali.cdnleiting.top/Article/details/gt2zhbthuyp.html

[U86] JS：空值合并
来源：http://dali.tian-w.cn/Article/details/gt2etzbcrnv.html

a ?? b
来源：http://dali.xuanzx.com/Article/details/gt2qpnhhpee.html

[U87] JS：解构默认值
来源：http://dali.0kj1m.cn/Article/details/gt2lrqjwdkl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.cheryme.top/Article/details/gt2odmxegmv.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gt2swutlstl.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gt2xrjjyjvy.html

[U89] JS：数组去重
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eplsjzcf.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gt2uegmgnra.html

[U90] JS：数字数组排序
来源：http://dali.svipenyu.cn/Article/details/gt2biuhyhxc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.316326.xyz/Article/details/gt2rhrqjeds.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gt2lcqisaoo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gt2cipanqut.html

[U92] JS：深拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2vkrswaxx.html

structuredClone(obj)
来源：http://dali.c1oappe.top/Article/details/gt2jgmzcmvf.html

[U93] JS：模板字符串
来源：http://dali.meibo888.top/Article/details/gt2wqqdyguc.html

`共 ${n} 条`
来源：http://dali.0kj1m.cn/Article/details/gt2hawckmsb.html

[U94] JS：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2cseuwaed.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gt2pkwwpgpd.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gt2nmqzikvx.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gt2npsptfdz.html

[U96] JS：async/await 与异常
来源：http://dali.yonumen.top/Article/details/gt2fyljpkia.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxuanxn.top/Article/details/gt2bcaqihdm.html

[U97] JS：并发请求
来源：http://dali.kuanghao11.cn/Article/details/gt2zhvcbhhu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ppjwa.cn/Article/details/gt2vzpexrll.html

[U98] JS：fetch 带 JSON
来源：http://dali.nanxinkj.top/Article/details/gt2zndsewqu.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yongpay.top/Article/details/gt2xzkyqxoc.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gt2fulqrfqo.html

el.addEventListener("click", e => {})
来源：http://dali.smart0.xyz/Article/details/gt2gsyuyhxh.html

[U100] JS：DOM 查询
来源：http://dali.cucudq.cn/Article/details/gt2tvuyhrgo.html

document.querySelector(".item")
来源：http://dali.mhx1999.top/Article/details/gt2uhlcnhjq.html

[U101] JS：classList 操作
来源：http://dali.tian-w.cn/Article/details/gt2otuxwkta.html

el.classList.toggle("active")
来源：http://dali.snrcjt.cn/Article/details/gt2snakwjxc.html

[U102] JS：本地存储
来源：http://dali.pengpengdd.cyou/Article/details/gt2uynxooqu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxuanxn.top/Article/details/gt2gajubzpv.html

[U103] JS：定时器
来源：http://dali.yanxiufei.cn/Article/details/gt2opyqhacj.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ppjwa.cn/Article/details/gt2ztfhjxcz.html

[U104] JS：防抖
来源：http://dali.yongpay.top/Article/details/gt2vsmpavis.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shzxlz.cn/Article/details/gt2doajrgll.html

[U105] JS：节流
来源：http://dali.jinqigfzy.top/Article/details/gt2svvrfnmu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2iataduus.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gt2eridoowx.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinqigfzy.top/Article/details/gt2sewtznus.html

[U107] JS：数字千分位
来源：http://dali.jyoumei.cn/Article/details/gt2neejxfew.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.gaohongyu789.top/Article/details/gt2edzuzadx.html

[U108] JS：随机整数
来源：http://dali.hywenlv.cn/Article/details/gt2efyakatw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.gaohongyu789.top/Article/details/gt2rkoaasgw.html

[U109] JS：数组分组
来源：http://dali.wangshuangyany.cn/Article/details/gt2dswxlmoy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yangfankeji.com/Article/details/gt2beyabhhw.html

[U110] JS：数组分块
来源：http://dali.chenjidiqi.icu/Article/details/gt2xmkubsbi.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jqgufenzy.top/Article/details/gt2hzomvbvm.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gt2ltbkqaiy.html

new Map(Object.entries(obj))
来源：http://dali.xuanzx.com/Article/details/gt2jcwgjfqm.html

[U112] JS：字符串补位
来源：http://dali.ybcxt.top/Article/details/gt2fuodcetv.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2fsuleqld.html

[U113] JS：正则替换全部
来源：http://dali.guowangkeji.top/Article/details/gt2yabglzmf.html

s.replaceAll("a", "b")
来源：http://dali.cheryme.top/Article/details/gt2vszbpgcf.html

[U114] JS：JSON 深比较
来源：http://dali.haohaochexian.top/Article/details/gt2gpsvbuky.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.iojbl.cn/Article/details/gt2gddrdmpk.html

[U115] JS：生成 UUID
来源：http://dali.xylfe.cn/Article/details/gt2afyoidmj.html

crypto.randomUUID()
来源：http://dali.wangshuangyany.cn/Article/details/gt2wfgypgqk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gt2dbwizgmd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yangfankeji.com/Article/details/gt2zmcqkxbf.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gt2hixuteag.html

npm i -D vitest;  npx vitest
来源：http://dali.shzxlz.cn/Article/details/gt2vsiilldh.html

[U118] JS：开发服务器
来源：http://dali.birdmap.top/Article/details/gt2odkoiatg.html

npm i -D vite;  npx vite
来源：http://dali.yj202588.top/Article/details/gt2nazkawnn.html

[U119] JS：生产构建
来源：http://dali.meibo888.top/Article/details/gt2givzyvxl.html

npx vite build
来源：http://dali.jianghu66.top/Article/details/gt2dsbsmduq.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.wangshuangyany.cn/Article/details/gt2pfanganc.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgufenzy.top/Article/details/gt2vpcvvbjd.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gbimljey.html

统计汇总
来源：http://dali.jinqigfzy.top/Article/details/gt2uvrcntxn.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whfurztt.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2pbumcbpr.html

Python ......... 252
来源：http://dali.hnxiangtu.top/Article/details/gt2zbhnenqs.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gt2likenyqt.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gt2bgwehzth.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gt2abryrhub.html

Java ........... 212
来源：http://dali.yanxiufei.cn/Article/details/gt2prhvftxi.html

Go ............. 212
来源：http://dali.jqgufenzy.top/Article/details/gt2cyrvhwwi.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2vloymnqj.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2xxaddfxw.html

C .............. 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vasemrtt.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2mdiehavg.html

SQL ............ 90
来源：http://dali.kuanghao11.cn/Article/details/gt2jsmojqzj.html

Bash ........... 80
来源：http://dali.cheryme.top/Article/details/gt2ytaidfay.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gt2qbkgzxmc.html

Swift .......... 15
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rfpzkxuz.html

Lua ............ 10
来源：http://dali.yj202588.top/Article/details/gt2aeglkcat.html

Perl ........... 10
来源：http://dali.9152youxi.cn/Article/details/gt2szwvntsr.html

Scala .......... 10
来源：http://dali.jqgufenzy.top/Article/details/gt2vsgmatxs.html

------------------------------------
来源：http://dali.fzhhl.top/Article/details/gt2zctvlfjm.html

合计 ........... 2106 条
来源：http://dali.redwolf501.top/Article/details/gt2pzrrndzu.html

按章节统计：
来源：http://dali.xuetiantiany.cn/Article/details/gt2vjhtxkxh.html


<!-- 参考信息 -->