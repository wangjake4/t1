代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.svipenyu.cn/Article/details/gtsfswdvav.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fzhhl.top/Article/details/gtmsusxrrw.html

[T48] Perl：正则替换
来源：http://dali.gaohongyu789.top/Article/details/gtohveryyn.html

$s =~ s/old/new/g;
来源：http://dali.cheryme.top/Article/details/gtpkpgekhb.html

[T49] Perl：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtczcwhjhy.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtufpoasgg.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtydperyhc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtfxbozbjv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtowzhifwn.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtbqtsjssz.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtjycuotkd.html

[T52] Scala：变量
来源：http://dali.jinqigfzy.top/Article/details/gtmwcxknix.html

val a = 1;  var b = 2
来源：http://dali.guowangkeji.top/Article/details/gtwkaloiri.html

[T53] Scala：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtsehyzhfc.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtqnltuzmz.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtrdkkudqu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtgzrrbtnw.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gtreabqjvz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtaavqxaxl.html

[T56] Scala：样例类
来源：http://dali.sysykeji.top/Article/details/gtdjriyyyq.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtwycbwtzd.html

[T57] Scala：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtocmwbhwg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtgajopwvf.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtrgjfpwjr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jianghu66.top/Article/details/gttdbezuta.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtcwwnjzxz.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gtbfvdnvvp.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtjswrokqc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtfaugwhzs.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtuqcbemne.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.chenjidiqi.icu/Article/details/gthnfbrhtm.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtibwvlmrc.html

[U01] Py：创建虚拟环境
来源：http://dali.sweek.top/Article/details/gtsjxkdvnu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtvsvubhjg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtkuvthqth.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtmkqqwqcu.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtdkyhyzko.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinqigufen.top/Article/details/gtyexkoatv.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gtycugiqat.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gtljtrqqav.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gttvxjkftb.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gtnkekqrco.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtxcajkysq.html

{**a, **b}
来源：http://dali.xziqi.cn/Article/details/gtmyspmaxa.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtzigjpzxm.html

{v: k for k, v in d.items()}
来源：http://dali.wangshuangyany.cn/Article/details/gtrdxebuuo.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtfuhjkhsw.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtbskipbse.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtiriojqsv.html

max(d, key=d.get)
来源：http://dali.daria6918.cn/Article/details/gtapewjfap.html

[U10] Py：按值排序字典
来源：http://dali.sysykeji.top/Article/details/gtfrixstyy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xuanzx.com/Article/details/gtrkheplei.html

[U11] Py：生成器表达式
来源：http://dali.tian-w.cn/Article/details/gtkpmggrfu.html

(x * 2 for x in arr)
来源：http://dali.ivvv.top/Article/details/gtvshjcvtv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gttluwxsid.html

Counter(arr).most_common(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjeciqgzo.html

[U13] Py：固定长度队列
来源：http://dali.zhengqikj.top/Article/details/gtcjrravcm.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gtcfsmepdc.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsqarwcg.html

defaultdict(list)
来源：http://dali.tanke756.top/Article/details/gtlfjwuxad.html

[U15] Py：高精度计时
来源：http://dali.jqgfzy.top/Article/details/gtodbpsigp.html

t = time.perf_counter()
来源：http://dali.svipenyu.cn/Article/details/gtfxtyntth.html

[U16] Py：命令行参数解析
来源：http://dali.jlsjyb.cn/Article/details/gttyyxhzxb.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.sxryk.cn/Article/details/gtjrdoaqaa.html

[U17] Py：初始化日志
来源：http://dali.jinqigfzy.top/Article/details/gtxsyyjevh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shuidangran.top/Article/details/gtsnfruriu.html

[U18] Py：预编译正则
来源：http://dali.daria6918.cn/Article/details/gtxebpsrkp.html

pat = re.compile(r"\d+")
来源：http://dali.redwolf501.top/Article/details/gthlnplcsx.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtjmxjcyku.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.andypj.xyz/Article/details/gtswohsene.html

[U20] Py：缓存函数结果
来源：http://dali.pengpengdd.cyou/Article/details/gtbuwjzudu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.feifeiyinyue.top/Article/details/gtcamewzqc.html

[U21] Py：自定义上下文管理器
来源：http://dali.tian-w.cn/Article/details/gtvfplfhwe.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtdnhtogqi.html

[U22] Py：矩阵转置
来源：http://dali.fzhhl.top/Article/details/gthehtgxwt.html

list(zip(*m))
来源：http://dali.nwbrower.top/Article/details/gtkzhwtqmj.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gtgdckoxms.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.havefunace.top/Article/details/gtgqkdgmwk.html

[U24] Py：路径操作
来源：http://dali.gaohongyu789.top/Article/details/gtzdsnsild.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zdqjudy.top/Article/details/gtonbcotlf.html

[U25] Py：CSV 按字典读
来源：http://dali.hnqzz.top/Article/details/gtzrrsqqna.html

csv.DictReader(f)
来源：http://dali.c1oappe.top/Article/details/gtjtmtbooj.html

[U26] Py：并发下载
来源：http://dali.shanyushiyangtech.top/Article/details/gtwkzjbbtl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xinyue.icu/Article/details/gtyxmdtpmt.html

[U27] Py：异步 HTTP
来源：http://dali.fengsongda.top/Article/details/gtakdkydak.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangshuangyany.cn/Article/details/gtjnmbiejg.html

[U28] Py：类型别名
来源：http://dali.xziqi.cn/Article/details/gtvprcidxj.html

UserId = int
来源：http://dali.gzhubu.top/Article/details/gtrpnwafya.html

[U29] Py：属性校验
来源：http://dali.ybcxt.top/Article/details/gtkftqydtw.html

@property 与 @x.setter 配合
来源：http://dali.yangfankeji.com/Article/details/gtbpuotyya.html

[U30] Py：数据类
来源：http://dali.haohaochexian.top/Article/details/gttoyoirae.html

@dataclass(slots=True)
来源：http://dali.meibo888.top/Article/details/gtryrtbycs.html

[U31] Py：单测
来源：http://dali.yanxiufei.cn/Article/details/gtofxkievr.html

python -m pytest -q
来源：http://dali.ehwqpu.com/Article/details/gtyrpmfkon.html

[U32] Py：代码格式化
来源：http://dali.guannengcc.top/Article/details/gtrwhmnwvx.html

ruff format . && ruff check --fix .
来源：http://dali.ydzc1.top/Article/details/gtvkqvsvhy.html

[U33] Py：打包发布
来源：http://dali.bjfxy.top/Article/details/gtypvkfwyk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.andypj.xyz/Article/details/gtignelgnd.html

[U34] Py：判断编码
来源：http://dali.guowangkeji.top/Article/details/gtckndboho.html

chardet.detect(raw)
来源：http://dali.yonumen.top/Article/details/gtvzudaexb.html

[U35] Py：发送邮件
来源：http://dali.yj20258.top/Article/details/gtxumuskjr.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shangyingyoupin.top/Article/details/gtvlhmaxaf.html

[U36] Py：定时任务
来源：http://dali.meibo888.top/Article/details/gtplxyacoh.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtbttiatwx.html

[U37] Py：读写 Excel
来源：http://dali.shzxlz.cn/Article/details/gtcdgpgrnk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yanxiufei.cn/Article/details/gtqjgunvnw.html

[U38] Py：获取脚本所在目录
来源：http://dali.zdqjudy.top/Article/details/gtvdxzxnwb.html

Path(__file__).resolve().parent
来源：http://dali.yonumen.top/Article/details/gtoxpqjkev.html

[U39] Py：判断是否在交互环境
来源：http://dali.yj20258.top/Article/details/gtiplwjboe.html

sys.stdout.isatty()
来源：http://dali.0kj1m.cn/Article/details/gtpnvunxrs.html

[U40] Py：打印到标准错误
来源：http://dali.havefunace.top/Article/details/gtwjamdelr.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtjuanenwy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.guowangkeji.top/Article/details/gtbcfzknrx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yanxiufei.cn/Article/details/gtcsfnpvkq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yuanzhike.top/Article/details/gtfvjayuff.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhijiandao.cn/Article/details/gtohfmkjqn.html

[U43] PHP：声明命名空间
来源：http://dali.cqqwz.cn/Article/details/gtnncwegub.html

namespace App\Http;
来源：http://dali.dashuyun.cn/Article/details/gtweehsgna.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtzrkyjbkq.html

declare(strict_types=1);
来源：http://dali.kuanghao11.cn/Article/details/gtfskzmzby.html

[U45] PHP：类型声明与返回类型
来源：http://dali.fzhhl.top/Article/details/gtbgvytojx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoseedkwj.html

[U46] PHP：可空类型
来源：http://dali.jlsjyb.cn/Article/details/gtjkdduquf.html

?string $name = null
来源：http://dali.yanxiufei.cn/Article/details/gtxnfalvvj.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtechjnrln.html

int|string $id
来源：http://dali.kuanghao11.cn/Article/details/gtutrkkphq.html

[U48] PHP：纯枚举
来源：http://dali.zhoulong.xyz/Article/details/gtwgunrbud.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqdykrydk.html

[U49] PHP：只读属性
来源：http://dali.gaohongyu789.top/Article/details/gtiwgbtqut.html

public readonly string $name
来源：http://dali.9152youxi.cn/Article/details/gtlxpkknjc.html

[U50] PHP：构造器属性提升
来源：http://dali.hfpthk.cn/Article/details/gtvgptajbl.html

public function __construct(private int $id) {}
来源：http://dali.xinyue.icu/Article/details/gtftmpuecu.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtbysmsnpb.html

[$a, $b] = $arr;
来源：http://dali.yueranfly.top/Article/details/gtkqewcjej.html

[U52] PHP：箭头函数
来源：http://dali.zhoulong.xyz/Article/details/gtzskcmwwd.html

$double = fn($x) => $x * 2;
来源：http://dali.kuanghao11.cn/Article/details/gtvjeitexz.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtukmhjitz.html

$v = $a ?? $b ?? "default";
来源：http://dali.snrcjt.cn/Article/details/gtzsvrfwyv.html

[U54] PHP：空安全调用
来源：http://dali.chenjidiqi.icu/Article/details/gtopbcwawh.html

$obj?->method()
来源：http://dali.gzhubu.top/Article/details/gtgjcxgqhp.html

[U55] PHP：match 表达式
来源：http://dali.cqqwz.cn/Article/details/gtuxezxatm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtjjyjehba.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gtlprcpxxm.html

f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtdasiwwsh.html

[U57] PHP：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtxsccsspa.html

"值: {$a}"
来源：http://dali.ybcxt.top/Article/details/gtjsdgjvwk.html

[U58] PHP：数组三件套
来源：http://dali.svipenyu.cn/Article/details/gtsjxbyfpm.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gttabndust.html

[U59] PHP：自定义排序
来源：http://dali.nwbrower.top/Article/details/gthxnjvfrx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.daxiang520.top/Article/details/gtltunkswo.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gttoegcocr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.aibaodan.cn/Article/details/gtmrhlyplk.html

[U61] PHP：正则
来源：http://dali.shzxlz.cn/Article/details/gtmvbxyxxu.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.svipenyu.cn/Article/details/gtpmzsyehw.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gtnljnihcx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xylfe.cn/Article/details/gtgowtyule.html

[U63] PHP：文件读写
来源：http://dali.yanxiufei.cn/Article/details/gtulgslkfn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gotoacloud.top/Article/details/gtakjimffx.html

[U64] PHP：目录遍历
来源：http://dali.guannengcc.top/Article/details/gthqxuzqhx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnqzz.top/Article/details/gtreleahuf.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gtlzosdznb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtinwlxzhv.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gttvftkmbs.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jiagoushi.top/Article/details/gtyybcugpa.html

[U67] PHP：处理文件上传
来源：http://dali.yonumen.top/Article/details/gtetziueuh.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nwbrower.top/Article/details/gtzzoxxzxk.html

[U68] PHP：PDO 连接
来源：http://dali.nanxuanxn.top/Article/details/gtngbtfasr.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.bjfxy.top/Article/details/gtxfzowqvs.html

[U69] PHP：PDO 预处理
来源：http://dali.tanke756.top/Article/details/gtqweeyhov.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.chenjidiqi.icu/Article/details/gtwetdweyj.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gtcofzzbzb.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gotoacloud.top/Article/details/gtvutundbv.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtsbcbavza.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuxming.cn/Article/details/gtuqvofdiu.html

[U72] PHP：写错误日志
来源：http://dali.guannengcc.top/Article/details/gtdxstgscn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.gotoacloud.top/Article/details/gtiyvttkjz.html

[U73] PHP：读取 ini 配置
来源：http://dali.yangfankeji.com/Article/details/gtyewqgvgi.html

parse_ini_file("config.ini", true)
来源：http://dali.zdqjudy.top/Article/details/gtnomenvra.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gtykrdyjan.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuetiantiany.cn/Article/details/gtkzkzynot.html

[U75] PHP：依赖注入
来源：http://dali.ehwqpu.com/Article/details/gtymhslxon.html

composer require psr/container
来源：http://dali.9152youxi.cn/Article/details/gtiobjaans.html

[U76] PHP：简单路由
来源：http://dali.guowangkeji.top/Article/details/gtlfxahqpm.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgfzy.top/Article/details/gtpnjzpfjl.html

[U77] PHP：模板渲染
来源：http://dali.dianchejie.cn/Article/details/gtnqurjzyd.html

composer require twig/twig
来源：http://dali.chenjidiqi.icu/Article/details/gtikqoefrz.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtlieikplj.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gttwgykcju.html

[U79] PHP：静态分析
来源：http://dali.aibaodan.cn/Article/details/gttgjttxvd.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtqznyyaei.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtwnnzpdgd.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.chenjidiqi.icu/Article/details/gteciapfxr.html

[U81] JS：初始化项目
来源：http://dali.bjfxy.top/Article/details/gtdugrkqxa.html

npm init -y;  npm i express
来源：http://dali.yj202588.top/Article/details/gtzeamzhgc.html

[U82] JS：package.json 脚本
来源：http://dali.shuidangran.top/Article/details/gtfromitcu.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tian-w.cn/Article/details/gtpblvquza.html

[U83] JS：ES Module 导入导出
来源：http://dali.yongpay.top/Article/details/gtnszzlcjv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.iojbl.cn/Article/details/gtuwwohovv.html

[U84] JS：CommonJS 写法
来源：http://dali.daria6918.cn/Article/details/gtmeqicffc.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.chenjidiqi.icu/Article/details/gtcttutlwt.html

[U85] JS：可选链
来源：http://dali.cqqwz.cn/Article/details/gtiwedwpny.html

a?.b?.c
来源：http://dali.yuxming.cn/Article/details/gtwieurbbb.html

[U86] JS：空值合并
来源：http://dali.ehwqpu.com/Article/details/gtmssajwuc.html

a ?? b
来源：http://dali.wangdashe.top/Article/details/gtdhzjrfnk.html

[U87] JS：解构默认值
来源：http://dali.redwolf501.top/Article/details/gtcjugoqgf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yongpay.top/Article/details/gtgyjzuoxs.html

[U88] JS：对象展开合并
来源：http://dali.dashuyun.cn/Article/details/gtbsbchzrn.html

{ ...a, ...b }
来源：http://dali.shuidangran.top/Article/details/gtywzcolzd.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gtmqzzvtax.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkczuphlf.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyklhfprl.html

[...arr].sort((a, b) => a - b)
来源：http://dali.shangyingyoupin.top/Article/details/gtdjdwibjd.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtxcenmhml.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.hysaishi.cn/Article/details/gtqmipseiy.html

[U92] JS：深拷贝
来源：http://dali.sxryk.cn/Article/details/gtrjadxirb.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtyvutyltt.html

[U93] JS：模板字符串
来源：http://dali.fengsongda.top/Article/details/gtirssaznm.html

`共 ${n} 条`
来源：http://dali.zdqjudy.top/Article/details/gtvoyfrsrj.html

[U94] JS：箭头函数
来源：http://dali.zhongyouzk.top/Article/details/gtkmomhcis.html

const double = x => x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnzxzejps.html

[U95] JS：Promise 包装
来源：http://dali.zhixingplan.top/Article/details/gtvlwwzfff.html

new Promise((resolve, reject) => {})
来源：http://dali.ppjwa.cn/Article/details/gtbdercjau.html

[U96] JS：async/await 与异常
来源：http://dali.shanyushiyangtech.top/Article/details/gtmwtiyoyb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.nanxinkj.top/Article/details/gtquevvnru.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtyafvqhpu.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj202588.top/Article/details/gtxmacrmfk.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gtwqaruhsl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.birdmap.top/Article/details/gtdvfdduqk.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gtzygnfugx.html

el.addEventListener("click", e => {})
来源：http://dali.tianlin.xyz/Article/details/gtnnxdesdq.html

[U100] JS：DOM 查询
来源：http://dali.wangdashe.top/Article/details/gtnxofgrog.html

document.querySelector(".item")
来源：http://dali.yj20258.top/Article/details/gtevodyspq.html

[U101] JS：classList 操作
来源：http://dali.nanxuanxn.top/Article/details/gthkjdadgt.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtzdxmcylj.html

[U102] JS：本地存储
来源：http://dali.jinghuilouyu.cn/Article/details/gtjukdtluv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gtkqsbeugf.html

[U103] JS：定时器
来源：http://dali.cdnleiting.top/Article/details/gtsfoxgkvb.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtrootatpq.html

[U104] JS：防抖
来源：http://dali.zhijiandao.cn/Article/details/gtwwrtusor.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yuanzhike.top/Article/details/gtcizzfkoq.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtlkgdkzcl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aizwys.cn/Article/details/gtjobrajin.html

[U106] JS：日期格式化
来源：http://dali.cqqwz.cn/Article/details/gtsjmmngve.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jlsjyb.cn/Article/details/gtrujnpalr.html

[U107] JS：数字千分位
来源：http://dali.pycfn.com/Article/details/gtnbhxsldu.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yongpay.top/Article/details/gtkiggpvqt.html

[U108] JS：随机整数
来源：http://dali.jyoumei.cn/Article/details/gtouechfdj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqtgjric.html

[U109] JS：数组分组
来源：http://dali.chenzaomai.com/Article/details/gtvlyiiuxy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.gzhubu.top/Article/details/gtbioleugp.html

[U110] JS：数组分块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtazgxzmkh.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xuanzx.com/Article/details/gtcuyfdats.html

[U111] JS：对象转 Map
来源：http://dali.cheryme.top/Article/details/gtruuyyuks.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gteenekowp.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtibsbjxqa.html

"7".padStart(3, "0")
来源：http://dali.feifeiyinyue.top/Article/details/gtznocciqn.html

[U113] JS：正则替换全部
来源：http://dali.sysykeji.top/Article/details/gtwxymynwn.html

s.replaceAll("a", "b")
来源：http://dali.yangfankeji.com/Article/details/gtqekfyife.html

[U114] JS：JSON 深比较
来源：http://dali.dashuyun.cn/Article/details/gtctrspncq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yanxiufei.cn/Article/details/gtyydxckhu.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gttydexlnf.html

crypto.randomUUID()
来源：http://dali.fengsongda.top/Article/details/gtqatkelpd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.iojbl.cn/Article/details/gttktjpdjp.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ehwqpu.com/Article/details/gtpyylsyaj.html

[U117] JS：单元测试
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigezpbyw.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxinkj.top/Article/details/gtohiifpsm.html

[U118] JS：开发服务器
来源：http://dali.zhijiandao.cn/Article/details/gtgejbojnr.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtcrxvknsm.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gtdvgjwhrb.html

npx vite build
来源：http://dali.kuanghao11.cn/Article/details/gtjghdcool.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jqgufenzy.top/Article/details/gtqvttlvdq.html

import.meta.env.VITE_API_URL
来源：http://dali.xziqi.cn/Article/details/gtzeqmhqoa.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtsnpzduwn.html

统计汇总
来源：http://dali.ivvv.top/Article/details/gtbcjpzdnf.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthkggofvo.html

按语言统计（条）：
来源：http://dali.yanxiufei.cn/Article/details/gttnquzuoh.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtnyxpqjja.html

PHP ............ 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtmxwogmcb.html

JavaScript ..... 252
来源：http://dali.yuanzhike.top/Article/details/gtzbfshknl.html

TypeScript ..... 212
来源：http://dali.cdnleiting.top/Article/details/gtfuenycrz.html

Java ........... 212
来源：http://dali.svipenyu.cn/Article/details/gtngumpfkc.html

Go ............. 212
来源：http://dali.dashuyun.cn/Article/details/gtizafxlwf.html

Ruby ........... 212
来源：http://dali.nanxuanxn.top/Article/details/gtwpbtirwm.html

C# ............. 212
来源：http://dali.xuetiantiany.cn/Article/details/gtmsydvksw.html

C .............. 30
来源：http://dali.xuetiantiany.cn/Article/details/gtlxrvhqgh.html

C++ ............ 30
来源：http://dali.yanxiufei.cn/Article/details/gtawrbgwwp.html

SQL ............ 90
来源：http://dali.jqgufenzy.top/Article/details/gtszmukhqf.html

Bash ........... 80
来源：http://dali.zhongyouzk.top/Article/details/gtctookoik.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gtnzeqwhgj.html

Swift .......... 15
来源：http://dali.svipenyu.cn/Article/details/gtlsdxbxdk.html

Lua ............ 10
来源：http://dali.yanxiufei.cn/Article/details/gtdksktsyo.html

Perl ........... 10
来源：http://dali.tian-w.cn/Article/details/gtrvifsnao.html

Scala .......... 10
来源：http://dali.nanxinkj.top/Article/details/gtfpkuzqix.html

------------------------------------
来源：http://dali.ybcxt.top/Article/details/gtpeowgduc.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gtlpnkczsk.html

按章节统计：
来源：http://dali.pengpengdd.cyou/Article/details/gtqhfhjetz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtnfuluxqd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtmciwpvmi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.cucudq.cn/Article/details/gtjgovtplm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gtexbfkyoe.html


<!-- 参考信息 -->