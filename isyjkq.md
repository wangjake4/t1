代发 wailian999

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtrusmdhbm.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtkogqjnxb.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbprdvwdk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gthlbvdkoy.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtbdpqkssr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinqigufen.top/Article/details/gtmfpqyuhv.html

[T48] Perl：正则替换
来源：http://dali.nanxinkj.top/Article/details/gttrhjrlxh.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gtpfofpplq.html

[T49] Perl：函数
来源：http://dali.pycfn.com/Article/details/gtbmcykpdc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtcpqlkdab.html

[T50] Perl：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtayrkapdv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.dashuyun.cn/Article/details/gtzulcnbbj.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtwpwrhoef.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtucoohcim.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gtalhmglon.html

[T52] Scala：变量
来源：http://dali.sweek.top/Article/details/gttddiyrzn.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijkawtll.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyodekqf.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtoguhccpo.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gtifncdqaa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daxiang520.top/Article/details/gterhdadvn.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtutmksqhx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.meibo888.top/Article/details/gtwuznnqek.html

[T56] Scala：样例类
来源：http://dali.gaohongyu789.top/Article/details/gtwvmhxvzk.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljijxcll.html

[T57] Scala：模式匹配
来源：http://dali.0kj1m.cn/Article/details/gtmvyylmtu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gogol.net.cn/Article/details/gtsgtniwdy.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gtumvkwhxs.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtiivdvbfc.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtsbmihzes.html

for (i <- 1 to 10) println(i)
来源：http://dali.cashguo.top/Article/details/gthnqnjdii.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtnqowakuz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yueranfly.top/Article/details/gtqfferzfh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfgudgfbc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gtwovsrvyq.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtxbdsiynx.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtkhccljlc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tian-w.cn/Article/details/gtxbeizsxz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hongshengwenyu.top/Article/details/gtwznhrtqc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtzzcybrtk.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gtcpgiyajq.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gotoacloud.top/Article/details/gtkhmjdiga.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gtpyympinv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigufen.top/Article/details/gtuoxdvnrj.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtukmqtbvb.html

list(dict.fromkeys(arr))
来源：http://dali.yj202588.top/Article/details/gtllzyqoox.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gtdprmgijq.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gtoouydfab.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtzimpzvnz.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtkjilzhve.html

[U08] Py：展平二维列表
来源：http://dali.gaohongyu789.top/Article/details/gtuafbahbi.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtggzgwwoz.html

[U09] Py：字典取最大值的键
来源：http://dali.yanxiufei.cn/Article/details/gtcrqnesiu.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpiqweqex.html

[U10] Py：按值排序字典
来源：http://dali.xylfe.cn/Article/details/gtslkhuagl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ehwqpu.com/Article/details/gtlmarsooo.html

[U11] Py：生成器表达式
来源：http://dali.zycfv.cn/Article/details/gtmtikqwom.html

(x * 2 for x in arr)
来源：http://dali.jianghu66.top/Article/details/gtujhcmujs.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.smart0.xyz/Article/details/gtmsyvvqll.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gtmptvbsdu.html

[U13] Py：固定长度队列
来源：http://dali.kuanghao11.cn/Article/details/gtnsxcylkx.html

deque(maxlen=10)
来源：http://dali.ydzc1.top/Article/details/gtqnkvocwf.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxylqlzxm.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtskykfmhc.html

[U15] Py：高精度计时
来源：http://dali.jianghu66.top/Article/details/gtewgiqmnk.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gtgeilbuqk.html

[U16] Py：命令行参数解析
来源：http://dali.pengpengdd.cyou/Article/details/gtutacrfcp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yueranfly.top/Article/details/gtjylamsxf.html

[U17] Py：初始化日志
来源：http://dali.havefunace.top/Article/details/gtdqtjaivm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhongyouzk.top/Article/details/gtxggmgqty.html

[U18] Py：预编译正则
来源：http://dali.quarkkingdee.top/Article/details/gtwgvafuns.html

pat = re.compile(r"\d+")
来源：http://dali.hnxiangtu.top/Article/details/gtjfugwucg.html

[U19] Py：正则替换带回调
来源：http://dali.zhijiandao.cn/Article/details/gtcwhbtwnv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.hfpthk.cn/Article/details/gteluvrfsa.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvfcypudc.html

@functools.lru_cache(maxsize=None)
来源：http://dali.quarkkingdee.top/Article/details/gtjfqrayrn.html

[U21] Py：自定义上下文管理器
来源：http://dali.zdqjudy.top/Article/details/gtqpaymtjc.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobsvsigk.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtydxvewft.html

list(zip(*m))
来源：http://dali.shzxlz.cn/Article/details/gtkaxnqwdf.html

[U23] Py：分块读取大文件
来源：http://dali.vqdsnc.cn/Article/details/gtoqhmjnve.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yangfankeji.com/Article/details/gtzgefxxzk.html

[U24] Py：路径操作
来源：http://dali.xuanzx.com/Article/details/gtvqypbtzh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yangfankeji.com/Article/details/gtuzixokfm.html

[U25] Py：CSV 按字典读
来源：http://dali.shzxlz.cn/Article/details/gtmbwqjybz.html

csv.DictReader(f)
来源：http://dali.jianghu66.top/Article/details/gtrucdjfgz.html

[U26] Py：并发下载
来源：http://dali.316326.xyz/Article/details/gtgkmcploi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtfayzmgfc.html

[U27] Py：异步 HTTP
来源：http://dali.pycfn.com/Article/details/gtxpgtzfen.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtklbgqavx.html

[U28] Py：类型别名
来源：http://dali.zhoulong.xyz/Article/details/gtuauqliys.html

UserId = int
来源：http://dali.jiagoushi.top/Article/details/gtoqimnqqc.html

[U29] Py：属性校验
来源：http://dali.wangshuangyany.cn/Article/details/gtyysmymsb.html

@property 与 @x.setter 配合
来源：http://dali.yongpay.top/Article/details/gtoxojqwwv.html

[U30] Py：数据类
来源：http://dali.svipenyu.cn/Article/details/gtoddpbhhe.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gtzafifslg.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gtqpsdsxum.html

python -m pytest -q
来源：http://dali.nwbrower.top/Article/details/gtilwcvoli.html

[U32] Py：代码格式化
来源：http://dali.aibaodan.cn/Article/details/gtdxzpdzqd.html

ruff format . && ruff check --fix .
来源：http://dali.316326.xyz/Article/details/gtuixydahr.html

[U33] Py：打包发布
来源：http://dali.ehwqpu.com/Article/details/gtvlqiirkm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ehwqpu.com/Article/details/gtxtjmhter.html

[U34] Py：判断编码
来源：http://dali.chenlongwang.top/Article/details/gtllyabvzp.html

chardet.detect(raw)
来源：http://dali.xziqi.cn/Article/details/gtqqngpvbj.html

[U35] Py：发送邮件
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlmfmntx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tian-w.cn/Article/details/gtlunvoxtz.html

[U36] Py：定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtsbeolrgt.html

schedule.every(10).minutes.do(job)
来源：http://dali.fzhhl.top/Article/details/gtgnudnowb.html

[U37] Py：读写 Excel
来源：http://dali.zhijiandao.cn/Article/details/gtqztrtllq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.svipenyu.cn/Article/details/gtdbbwddzb.html

[U38] Py：获取脚本所在目录
来源：http://dali.hammf.cn/Article/details/gthsybwztn.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtygappded.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtqirudkxu.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtqywppvtv.html

[U40] Py：打印到标准错误
来源：http://dali.daxiang520.top/Article/details/gtedohsfwt.html

print("err", file=sys.stderr)
来源：http://dali.guowangkeji.top/Article/details/gtqjschnkg.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tanke756.top/Article/details/gtechcrvqi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.meibo888.top/Article/details/gtzvzejrww.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ppjwa.cn/Article/details/gterumqocc.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tianlin.xyz/Article/details/gtuiyyyafr.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtoukuwujc.html

namespace App\Http;
来源：http://dali.cucudq.cn/Article/details/gtyuktfind.html

[U44] PHP：开启严格类型
来源：http://dali.316326.xyz/Article/details/gtmqgqvjnq.html

declare(strict_types=1);
来源：http://dali.nwbrower.top/Article/details/gtxqqcaaom.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gtkjuwptoj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtcwaitkae.html

[U46] PHP：可空类型
来源：http://dali.dashuyun.cn/Article/details/gtmqnvqkop.html

?string $name = null
来源：http://dali.yuanzhike.top/Article/details/gtbrrhfxkq.html

[U47] PHP：联合类型
来源：http://dali.hnxiangtu.top/Article/details/gtjoeiqaae.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtupwnetys.html

[U48] PHP：纯枚举
来源：http://dali.fzhhl.top/Article/details/gthzvxwvfw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pycfn.com/Article/details/gtdnyggdyy.html

[U49] PHP：只读属性
来源：http://dali.zhijiandao.cn/Article/details/gtrnpvparc.html

public readonly string $name
来源：http://dali.zhixingplan.top/Article/details/gtbuhnuhgy.html

[U50] PHP：构造器属性提升
来源：http://dali.xinyue.icu/Article/details/gtxbzthrbx.html

public function __construct(private int $id) {}
来源：http://dali.cqqwz.cn/Article/details/gtmdofffat.html

[U51] PHP：数组解构
来源：http://dali.316326.xyz/Article/details/gtzoguacgl.html

[$a, $b] = $arr;
来源：http://dali.chenjidiqi.icu/Article/details/gtogmuwiwm.html

[U52] PHP：箭头函数
来源：http://dali.tanke756.top/Article/details/gtwjopprsd.html

$double = fn($x) => $x * 2;
来源：http://dali.pycfn.com/Article/details/gtgpmybyeo.html

[U53] PHP：空合并运算符
来源：http://dali.hongshengwenyu.top/Article/details/gtuposbstc.html

$v = $a ?? $b ?? "default";
来源：http://dali.0kj1m.cn/Article/details/gtrkizelso.html

[U54] PHP：空安全调用
来源：http://dali.zhongyouzk.top/Article/details/gtyaagkwhv.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gtjzmkckyn.html

[U55] PHP：match 表达式
来源：http://dali.yvedp.cn/Article/details/gtnzogjeey.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtntdmejkz.html

[U56] PHP：命名参数
来源：http://dali.yuanzhike.top/Article/details/gtnhgcidhd.html

f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtuepqxhoi.html

[U57] PHP：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtswudzesr.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gtdqrcfalm.html

[U58] PHP：数组三件套
来源：http://dali.zhengqikj.top/Article/details/gtofukovad.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yonumen.top/Article/details/gtajngykpl.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gtxiitbxgj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gttrhwdwzr.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gthfasgoxv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sxryk.cn/Article/details/gtcvnrghbv.html

[U61] PHP：正则
来源：http://dali.ivvv.top/Article/details/gtsktypxfy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tian-w.cn/Article/details/gtsnmnwlrn.html

[U62] PHP：日期对象
来源：http://dali.chenjidiqi.icu/Article/details/gtulbvlnyr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.redwolf501.top/Article/details/gtuaxolseo.html

[U63] PHP：文件读写
来源：http://dali.aizwys.cn/Article/details/gtaeyjauqa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.zhijiandao.cn/Article/details/gtyemrdukm.html

[U64] PHP：目录遍历
来源：http://dali.gaohongyu789.top/Article/details/gtbsdrfelb.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.guowangkeji.top/Article/details/gtascvmoru.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtpkqzbsmj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisfgsven.html

[U66] PHP：设置 Cookie
来源：http://dali.yanxiufei.cn/Article/details/gtnqrosxpl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cqqwz.cn/Article/details/gtshbdxryi.html

[U67] PHP：处理文件上传
来源：http://dali.yuxming.cn/Article/details/gtndrnlkrg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnxiangtu.top/Article/details/gtkfaateyq.html

[U68] PHP：PDO 连接
来源：http://dali.tanke756.top/Article/details/gtalxpjzim.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigufen.top/Article/details/gtxhwdnsoj.html

[U69] PHP：PDO 预处理
来源：http://dali.cucudq.cn/Article/details/gtfaihtqry.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yongpay.top/Article/details/gtuhndxrnh.html

[U70] PHP：PDO 事务
来源：http://dali.xinyue.icu/Article/details/gtjoxvcrag.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtavfxcnrc.html

[U71] PHP：抛出异常
来源：http://dali.zdqjudy.top/Article/details/gtrwihtoor.html

throw new RuntimeException("失败", 500);
来源：http://dali.hnqzz.top/Article/details/gthlwihzco.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtwqofvzba.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hammf.cn/Article/details/gtcteecdsv.html

[U73] PHP：读取 ini 配置
来源：http://dali.gzhubu.top/Article/details/gtmwhglxhg.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtufrnafgw.html

[U74] PHP：读取环境变量
来源：http://dali.nwbrower.top/Article/details/gtdzdpnwrk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gttslyxzcw.html

[U75] PHP：依赖注入
来源：http://dali.yj202588.top/Article/details/gtjmwfaauv.html

composer require psr/container
来源：http://dali.jqgufenzy.top/Article/details/gtdhwnhfgl.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gtwakxhvkq.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gtceujsgmd.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gtihxsybtc.html

composer require twig/twig
来源：http://dali.jqgfzy.top/Article/details/gtlsieeeji.html

[U78] PHP：单元测试
来源：http://dali.hnqzz.top/Article/details/gtgzjrzrpz.html

composer require --dev phpunit/phpunit
来源：http://dali.yongpay.top/Article/details/gtjrwsaifk.html

[U79] PHP：静态分析
来源：http://dali.zycfv.cn/Article/details/gtkhwmbznr.html

composer require --dev phpstan/phpstan
来源：http://dali.hywenlv.cn/Article/details/gtujejerol.html

[U80] PHP：代码规范修复
来源：http://dali.hywenlv.cn/Article/details/gtleopqxwx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gtfgdntqha.html

[U81] JS：初始化项目
来源：http://dali.316326.xyz/Article/details/gtrezvvwem.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gtgyxtwrul.html

[U82] JS：package.json 脚本
来源：http://dali.yangfankeji.com/Article/details/gtyoxcjbov.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.dianchejie.cn/Article/details/gtrxwnaywk.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gtnfvnudra.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gtddcrxnwb.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfgydwohs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.snrcjt.cn/Article/details/gtweiylaxp.html

[U85] JS：可选链
来源：http://dali.hnqzz.top/Article/details/gtrtkzzimx.html

a?.b?.c
来源：http://dali.c1oappe.top/Article/details/gttlwrhdmf.html

[U86] JS：空值合并
来源：http://dali.hysaishi.cn/Article/details/gtjvwbrntq.html

a ?? b
来源：http://dali.wangshuangyany.cn/Article/details/gtyxjardca.html

[U87] JS：解构默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpuupjmh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yuanzhike.top/Article/details/gtcrottnsv.html

[U88] JS：对象展开合并
来源：http://dali.jqgfzy.top/Article/details/gtdhknzkvf.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtrcbtqtnl.html

[U89] JS：数组去重
来源：http://dali.shangyingyoupin.top/Article/details/gtwovwuuec.html

[...new Set(arr)]
来源：http://dali.hfpthk.cn/Article/details/gtdaxpokit.html

[U90] JS：数字数组排序
来源：http://dali.yuanzhike.top/Article/details/gtuaeefbuv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gzhubu.top/Article/details/gtebmhtdts.html

[U91] JS：对象键值遍历
来源：http://dali.zycfv.cn/Article/details/gtgkyvfrsd.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.havefunace.top/Article/details/gtbedktpki.html

[U92] JS：深拷贝
来源：http://dali.ydzc1.top/Article/details/gttkjscrxz.html

structuredClone(obj)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttzjwkmrh.html

[U93] JS：模板字符串
来源：http://dali.yuxming.cn/Article/details/gtpnjrefnd.html

`共 ${n} 条`
来源：http://dali.c1oappe.top/Article/details/gtvoazxvsq.html

[U94] JS：箭头函数
来源：http://dali.jyoumei.cn/Article/details/gtzbzzyxze.html

const double = x => x * 2;
来源：http://dali.cqqwz.cn/Article/details/gthegkahiv.html

[U95] JS：Promise 包装
来源：http://dali.hywenlv.cn/Article/details/gtjaprvtok.html

new Promise((resolve, reject) => {})
来源：http://dali.hnxiangtu.top/Article/details/gtaxsfcpvg.html

[U96] JS：async/await 与异常
来源：http://dali.hnqzz.top/Article/details/gtxwfgpaww.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.guannengcc.top/Article/details/gtmtznewvs.html

[U97] JS：并发请求
来源：http://dali.feifeiyinyue.top/Article/details/gtzuyowbmp.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hnxiangtu.top/Article/details/gtqlbieskf.html

[U98] JS：fetch 带 JSON
来源：http://dali.cqqwz.cn/Article/details/gthsgohlch.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.andypj.xyz/Article/details/gtxmyoxyre.html

[U99] JS：事件监听
来源：http://dali.yonumen.top/Article/details/gtgsjzulma.html

el.addEventListener("click", e => {})
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwneojaq.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupxgvbqs.html

document.querySelector(".item")
来源：http://dali.hongshengwenyu.top/Article/details/gtshghucdd.html

[U101] JS：classList 操作
来源：http://dali.wangdashe.top/Article/details/gtvfxdyrdz.html

el.classList.toggle("active")
来源：http://dali.gaohongyu789.top/Article/details/gtskwkvcnq.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtrfykaipq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.meibo888.top/Article/details/gtfotgkgwr.html

[U103] JS：定时器
来源：http://dali.jyoumei.cn/Article/details/gtyyecwdgt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrgxnksy.html

[U104] JS：防抖
来源：http://dali.yj20258888.top/Article/details/gtenwnyshu.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoarcehna.html

[U105] JS：节流
来源：http://dali.sysykeji.top/Article/details/gtepszaqgb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.daxiang520.top/Article/details/gtgrcclgnh.html

[U106] JS：日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtoioijzwg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hywenlv.cn/Article/details/gtecptfabw.html

[U107] JS：数字千分位
来源：http://dali.316326.xyz/Article/details/gtvrtsceqk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gtcuiuylpk.html

[U108] JS：随机整数
来源：http://dali.chenlongwang.top/Article/details/gtsuzfzfui.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.hammf.cn/Article/details/gtcxnrrbkw.html

[U109] JS：数组分组
来源：http://dali.hfpthk.cn/Article/details/gtbpnlluuz.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ppjwa.cn/Article/details/gtoptntzxg.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gtuuixwpaa.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhongyouzk.top/Article/details/gtlxybtjem.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gtwqrppwyz.html

new Map(Object.entries(obj))
来源：http://dali.sxryk.cn/Article/details/gtcebspquy.html

[U112] JS：字符串补位
来源：http://dali.birdmap.top/Article/details/gtwlwqpkig.html

"7".padStart(3, "0")
来源：http://dali.zhoulong.xyz/Article/details/gtyrbzeobg.html

[U113] JS：正则替换全部
来源：http://dali.zhiwuduotai.top/Article/details/gtawhgmcxg.html

s.replaceAll("a", "b")
来源：http://dali.chenjidiqi.icu/Article/details/gtmsvgxoih.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gtbddlcqat.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.havefunace.top/Article/details/gtrfqhropn.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gtcvsbwqna.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtzqjuvftk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinqigfzy.top/Article/details/gtbgazatyc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcrbiecf.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtrsmvcyjf.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gtuwlfzajq.html

[U118] JS：开发服务器
来源：http://dali.zhixingplan.top/Article/details/gtlutleros.html

npm i -D vite;  npx vite
来源：http://dali.zycfv.cn/Article/details/gtajutxzuk.html

[U119] JS：生产构建
来源：http://dali.yonumen.top/Article/details/gtnezljhml.html

npx vite build
来源：http://dali.xylfe.cn/Article/details/gtfbnieylj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojggslkp.html

import.meta.env.VITE_API_URL
来源：http://dali.sysykeji.top/Article/details/gtvwhmmhfg.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveqxfxhs.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtdlultrwh.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtpchxxoyw.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtpahwqaby.html

Python ......... 252
来源：http://dali.cqqwz.cn/Article/details/gtduccbtbc.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtuzvwzymv.html

JavaScript ..... 252
来源：http://dali.wangdashe.top/Article/details/gtdfjygupx.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtihqzlmgn.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvikxbalh.html

Go ............. 212
来源：http://dali.gotoacloud.top/Article/details/gtnqxdzceu.html

Ruby ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvjnuvlz.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gtzmfcvmnv.html

C .............. 30
来源：http://dali.hysaishi.cn/Article/details/gtwbpmpbzd.html

C++ ............ 30
来源：http://dali.ppjwa.cn/Article/details/gtjpvlnpji.html

SQL ............ 90
来源：http://dali.gzhubu.top/Article/details/gtfwhprlqi.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtevabjwah.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtamhiujqm.html

Swift .......... 15
来源：http://dali.sufxvd.cn/Article/details/gtmdpzrdar.html

Lua ............ 10
来源：http://dali.feifeiyinyue.top/Article/details/gtjncgsmez.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtbjsnkkgz.html

Scala .......... 10
来源：http://dali.yongpay.top/Article/details/gtieoyetdr.html

------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gtbbuxrvwe.html

合计 ........... 2106 条
来源：http://dali.yuanzhike.top/Article/details/gtitigzqid.html

按章节统计：
来源：http://dali.jqgfzy.top/Article/details/gtidbdqado.html


<!-- 参考信息 -->