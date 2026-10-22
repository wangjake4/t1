代发 wailian999

[T49] Perl：函数
来源：http://dali.jiagoushi.top/Article/details/gtyynpqktf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gteheuhybh.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtgzldbwrp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.gotoacloud.top/Article/details/gtmvlpqegq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aizwys.cn/Article/details/gtesnvrheh.html

[T51] Scala：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtneqwpiob.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtclkgijud.html

[T52] Scala：变量
来源：http://dali.iojbl.cn/Article/details/gtnteanwmu.html

val a = 1;  var b = 2
来源：http://dali.yuanzhike.top/Article/details/gtlbojhatd.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtudyoalgo.html

s"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtxwtyoptw.html

[T54] Scala：集合映射
来源：http://dali.jiagoushi.top/Article/details/gtbsvhfxmp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtkplmerno.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gtxkabdsov.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gthtgpfknn.html

[T56] Scala：样例类
来源：http://dali.zhengqikj.top/Article/details/gtxaekiwcb.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtkqayboeq.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtchzpvrlu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtiyxasxbv.html

[T58] Scala：函数定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtkiitanln.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtvzctwptu.html

[T59] Scala：循环
来源：http://dali.yuxming.cn/Article/details/gtrtrcdkeq.html

for (i <- 1 to 10) println(i)
来源：http://dali.snrcjt.cn/Article/details/gtlbhfrfki.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gttokxukph.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.kuanghao11.cn/Article/details/gtygmdrgow.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtjqbvzwpa.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xylfe.cn/Article/details/gtwqaqdhho.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgqlmrpeo.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtjlcpikig.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shuidangran.top/Article/details/gtdiwmkfva.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hywenlv.cn/Article/details/gticthrdti.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtibfotmxz.html

[U03] Py：加载 .env 配置
来源：http://dali.jlsjyb.cn/Article/details/gtvcrcezmt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.xuetiantiany.cn/Article/details/gtooqtaxoo.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtbazadzqu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtnqcemtah.html

[U05] Py：列表去重且保序
来源：http://dali.andypj.xyz/Article/details/gtrgcrwpnq.html

list(dict.fromkeys(arr))
来源：http://dali.hysaishi.cn/Article/details/gtciwcbvlm.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtiknfscch.html

{**a, **b}
来源：http://dali.yvedp.cn/Article/details/gtzbbnkcqc.html

[U07] Py：反转字典键值
来源：http://dali.chenjidiqi.icu/Article/details/gtgwpjyzzg.html

{v: k for k, v in d.items()}
来源：http://dali.ehwqpu.com/Article/details/gtrehmwjus.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtbxojkzdx.html

[y for x in nested for y in x]
来源：http://dali.shuidangran.top/Article/details/gtgvpdtlbd.html

[U09] Py：字典取最大值的键
来源：http://dali.quarkkingdee.top/Article/details/gttljvwuww.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtmkvxubto.html

[U10] Py：按值排序字典
来源：http://dali.yvedp.cn/Article/details/gtifubiwha.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.316326.xyz/Article/details/gtsljuxfez.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtijmwpopy.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtlhaihcki.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gtcyyvwytw.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gtbvflmepk.html

[U13] Py：固定长度队列
来源：http://dali.c1oappe.top/Article/details/gtlcxprent.html

deque(maxlen=10)
来源：http://dali.9152youxi.cn/Article/details/gtdcbitdwg.html

[U14] Py：分组收集到列表
来源：http://dali.nanxinkj.top/Article/details/gtgvaanbxr.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtzoimdzvj.html

[U15] Py：高精度计时
来源：http://dali.wangshuangyany.cn/Article/details/gtubipixnh.html

t = time.perf_counter()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvyivgidz.html

[U16] Py：命令行参数解析
来源：http://dali.yonumen.top/Article/details/gtcrvpledl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.andypj.xyz/Article/details/gtuvancprt.html

[U17] Py：初始化日志
来源：http://dali.hnxiangtu.top/Article/details/gtbsrbgrkf.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.snrcjt.cn/Article/details/gtwbwfsqwi.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gtptpaugot.html

pat = re.compile(r"\d+")
来源：http://dali.yongpay.top/Article/details/gtffxvbuyo.html

[U19] Py：正则替换带回调
来源：http://dali.ppjwa.cn/Article/details/gtcnjmtxkp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yvedp.cn/Article/details/gtmetuxlej.html

[U20] Py：缓存函数结果
来源：http://dali.cucudq.cn/Article/details/gtsybbusar.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xuanzx.com/Article/details/gttgskhswr.html

[U21] Py：自定义上下文管理器
来源：http://dali.ybcxt.top/Article/details/gtldndmzve.html

@contextlib.contextmanager
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlkcuqnn.html

[U22] Py：矩阵转置
来源：http://dali.ppjwa.cn/Article/details/gtklpjifep.html

list(zip(*m))
来源：http://dali.shuidangran.top/Article/details/gtgzjeoxke.html

[U23] Py：分块读取大文件
来源：http://dali.yuanzhike.top/Article/details/gtvagwbxmu.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.nwbrower.top/Article/details/gtqvplyjdl.html

[U24] Py：路径操作
来源：http://dali.yanxiufei.cn/Article/details/gtrtkqbfem.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.andypj.xyz/Article/details/gtyfwroflk.html

[U25] Py：CSV 按字典读
来源：http://dali.quarkkingdee.top/Article/details/gtnztozwqv.html

csv.DictReader(f)
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqztnxwp.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gtwvqcadty.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gogol.net.cn/Article/details/gtqyeqsuwn.html

[U27] Py：异步 HTTP
来源：http://dali.yuanzhike.top/Article/details/gtfzrgxfbu.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jinqigufen.top/Article/details/gtmhuetqkx.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gterkvpter.html

UserId = int
来源：http://dali.jlsjyb.cn/Article/details/gtacdssggl.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gthicezbbk.html

@property 与 @x.setter 配合
来源：http://dali.redwolf501.top/Article/details/gtxelmjmig.html

[U30] Py：数据类
来源：http://dali.gaohongyu789.top/Article/details/gthspxtcar.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gtzlqgmoth.html

[U31] Py：单测
来源：http://dali.zhengqikj.top/Article/details/gtrrljjyxf.html

python -m pytest -q
来源：http://dali.jyoumei.cn/Article/details/gtqvmqlogo.html

[U32] Py：代码格式化
来源：http://dali.ehwqpu.com/Article/details/gtldastbpl.html

ruff format . && ruff check --fix .
来源：http://dali.shzxlz.cn/Article/details/gtpfyfzpqb.html

[U33] Py：打包发布
来源：http://dali.yongpay.top/Article/details/gtlwiqvsrm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.shangyingyoupin.top/Article/details/gtciaqrwct.html

[U34] Py：判断编码
来源：http://dali.hongshengwenyu.top/Article/details/gtvxvaopew.html

chardet.detect(raw)
来源：http://dali.havefunace.top/Article/details/gtebmnegib.html

[U35] Py：发送邮件
来源：http://dali.hysaishi.cn/Article/details/gtywvxkrtt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gteqczeptt.html

[U36] Py：定时任务
来源：http://dali.aibaodan.cn/Article/details/gtzmwcqmwv.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtndyscjxp.html

[U37] Py：读写 Excel
来源：http://dali.yj202588.top/Article/details/gtstbbslin.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtrkrhbxke.html

[U38] Py：获取脚本所在目录
来源：http://dali.xylfe.cn/Article/details/gtcdmuflqr.html

Path(__file__).resolve().parent
来源：http://dali.9152youxi.cn/Article/details/gtibpaqplx.html

[U39] Py：判断是否在交互环境
来源：http://dali.yvedp.cn/Article/details/gtgtxumzgq.html

sys.stdout.isatty()
来源：http://dali.zhixingplan.top/Article/details/gtemghoosn.html

[U40] Py：打印到标准错误
来源：http://dali.cheryme.top/Article/details/gtvqmndmbk.html

print("err", file=sys.stderr)
来源：http://dali.svipenyu.cn/Article/details/gtrhkqnoft.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jianghu66.top/Article/details/gtcqddisnq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtxtnvdycj.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.aibaodan.cn/Article/details/gtrhjbziyx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xinyue.icu/Article/details/gtgplfkcrd.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtddefpyqq.html

namespace App\Http;
来源：http://dali.cqqwz.cn/Article/details/gtqtihqxjn.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gtxxnjaezb.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gtrxcnvkfv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tian-w.cn/Article/details/gtqnryezax.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzouibsa.html

[U46] PHP：可空类型
来源：http://dali.tian-w.cn/Article/details/gtcksqdfzc.html

?string $name = null
来源：http://dali.hfpthk.cn/Article/details/gtrnelfepj.html

[U47] PHP：联合类型
来源：http://dali.birdmap.top/Article/details/gtelckgaww.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtfswfkhxf.html

[U48] PHP：纯枚举
来源：http://dali.shzxlz.cn/Article/details/gtizrdkgwb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.jlsjyb.cn/Article/details/gtschvzcri.html

[U49] PHP：只读属性
来源：http://dali.gzhubu.top/Article/details/gtfvppbiqp.html

public readonly string $name
来源：http://dali.zhiwuduotai.top/Article/details/gtwukhcmcy.html

[U50] PHP：构造器属性提升
来源：http://dali.shanyushiyangtech.top/Article/details/gtoexcpxrp.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtcidzblcf.html

[U51] PHP：数组解构
来源：http://dali.gogol.net.cn/Article/details/gtxryndecr.html

[$a, $b] = $arr;
来源：http://dali.hnqzz.top/Article/details/gthuvqxkyk.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gtadlbtcce.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gtvihdrqbm.html

[U53] PHP：空合并运算符
来源：http://dali.xylfe.cn/Article/details/gtbxfsgqiz.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtwbvqyxfd.html

[U54] PHP：空安全调用
来源：http://dali.kuanghao11.cn/Article/details/gtqnbytgqr.html

$obj?->method()
来源：http://dali.zhoulong.xyz/Article/details/gtgjdpmxgr.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gthxwilpuw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtksdgrlsj.html

[U56] PHP：命名参数
来源：http://dali.yj20258888.top/Article/details/gtrgpsafhk.html

f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gtiwtebreh.html

[U57] PHP：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtlbjufmqq.html

"值: {$a}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnfsrzrvu.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gtpnmwonon.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gtzoivbbrx.html

[U59] PHP：自定义排序
来源：http://dali.cheryme.top/Article/details/gtgcthucmv.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.chenzaomai.com/Article/details/gtsfvjtasr.html

[U60] PHP：JSON 编解码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwewoeyu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yj20258.top/Article/details/gtuggnlijy.html

[U61] PHP：正则
来源：http://dali.wangshuangyany.cn/Article/details/gtwmocfryr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daria6918.cn/Article/details/gtvlnfwfoq.html

[U62] PHP：日期对象
来源：http://dali.ybcxt.top/Article/details/gtwvglhhvu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xuetiantiany.cn/Article/details/gtxyjonmkz.html

[U63] PHP：文件读写
来源：http://dali.zhengqikj.top/Article/details/gtooiibsye.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gtztlxjnrk.html

[U64] PHP：目录遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtkckfsrbk.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.havefunace.top/Article/details/gthdadsxui.html

[U65] PHP：会话
来源：http://dali.svipenyu.cn/Article/details/gtjzroojih.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtaxlyuclk.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gtkrijrzdn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.fengsongda.top/Article/details/gtfcvsirge.html

[U67] PHP：处理文件上传
来源：http://dali.sysykeji.top/Article/details/gtxilmggje.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.jlsjyb.cn/Article/details/gtkwkcqcci.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtmkgcoojk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.mhx1999.top/Article/details/gtsehjohco.html

[U69] PHP：PDO 预处理
来源：http://dali.cdnleiting.top/Article/details/gtlgttsvpe.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhongyouzk.top/Article/details/gtaiehnozu.html

[U70] PHP：PDO 事务
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiheymzva.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhiwuduotai.top/Article/details/gtdccbllxl.html

[U71] PHP：抛出异常
来源：http://dali.svipenyu.cn/Article/details/gtctyvyreu.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtcvagfvab.html

[U72] PHP：写错误日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxsafthm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hongshengwenyu.top/Article/details/gtbvgbzidv.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gtluxmsizu.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtnkgkttks.html

[U74] PHP：读取环境变量
来源：http://dali.redwolf501.top/Article/details/gtaezmmsrw.html

getenv("APP_ENV") ?: "production"
来源：http://dali.shuidangran.top/Article/details/gtugpcrgyw.html

[U75] PHP：依赖注入
来源：http://dali.sweek.top/Article/details/gtzdfxzhus.html

composer require psr/container
来源：http://dali.snrcjt.cn/Article/details/gtszfskcbf.html

[U76] PHP：简单路由
来源：http://dali.yanxiufei.cn/Article/details/gthhmmbzfx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.fengsongda.top/Article/details/gtjiaxvtpy.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtwvkanpsv.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gttaliaasf.html

[U78] PHP：单元测试
来源：http://dali.sysykeji.top/Article/details/gtiycvqhny.html

composer require --dev phpunit/phpunit
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvwxivkt.html

[U79] PHP：静态分析
来源：http://dali.shzxlz.cn/Article/details/gtymxvbayi.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqpfzrsd.html

[U80] PHP：代码规范修复
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgkbgesb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.ppjwa.cn/Article/details/gthplbikdy.html

[U81] JS：初始化项目
来源：http://dali.guowangkeji.top/Article/details/gtsqwuggym.html

npm init -y;  npm i express
来源：http://dali.yj20258888.top/Article/details/gtuehjugyd.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtpcrxdshj.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zdqjudy.top/Article/details/gtkwhijhjm.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhongyouzk.top/Article/details/gtscauxhnq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gtorppnqch.html

[U84] JS：CommonJS 写法
来源：http://dali.zdqjudy.top/Article/details/gtgsrwjruz.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gtqmxrvqnp.html

[U85] JS：可选链
来源：http://dali.yj20258.top/Article/details/gtvezfofaa.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gtpijeuihr.html

[U86] JS：空值合并
来源：http://dali.nanxinkj.top/Article/details/gtkwivdetk.html

a ?? b
来源：http://dali.yuxming.cn/Article/details/gthqkiqsgc.html

[U87] JS：解构默认值
来源：http://dali.jinghuilouyu.cn/Article/details/gthtaoxojw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.316326.xyz/Article/details/gtscecxikd.html

[U88] JS：对象展开合并
来源：http://dali.nanxinkj.top/Article/details/gtlrtwclxh.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtnekkbkvn.html

[U89] JS：数组去重
来源：http://dali.0kj1m.cn/Article/details/gtvqkxshck.html

[...new Set(arr)]
来源：http://dali.cucudq.cn/Article/details/gtmyphubss.html

[U90] JS：数字数组排序
来源：http://dali.guannengcc.top/Article/details/gthbgkykml.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hongshengwenyu.top/Article/details/gtiysulhkp.html

[U91] JS：对象键值遍历
来源：http://dali.meibo888.top/Article/details/gttbeaqxpf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.pengpengdd.cyou/Article/details/gtuwnxjoqg.html

[U92] JS：深拷贝
来源：http://dali.gogol.net.cn/Article/details/gtqsnowmke.html

structuredClone(obj)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfflnwbct.html

[U93] JS：模板字符串
来源：http://dali.kuanghao11.cn/Article/details/gtphjlfyoz.html

`共 ${n} 条`
来源：http://dali.jqgfzy.top/Article/details/gtskjcqrpn.html

[U94] JS：箭头函数
来源：http://dali.gogol.net.cn/Article/details/gtqjdpkxfq.html

const double = x => x * 2;
来源：http://dali.cheryme.top/Article/details/gtkatmorlo.html

[U95] JS：Promise 包装
来源：http://dali.pycfn.com/Article/details/gthrasubey.html

new Promise((resolve, reject) => {})
来源：http://dali.tian-w.cn/Article/details/gtkbwxevho.html

[U96] JS：async/await 与异常
来源：http://dali.iojbl.cn/Article/details/gtlbdptolg.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gttevrdjiy.html

[U97] JS：并发请求
来源：http://dali.jlsjyb.cn/Article/details/gtxoiemzne.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gtyknkzjlo.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtczddfxfz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtxbyoyiby.html

[U99] JS：事件监听
来源：http://dali.jlsjyb.cn/Article/details/gtlsijqfig.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtdqnluhkl.html

[U100] JS：DOM 查询
来源：http://dali.zhengqikj.top/Article/details/gtvkmeqlwn.html

document.querySelector(".item")
来源：http://dali.shangyingyoupin.top/Article/details/gtkodfvlkg.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gtruyjhsin.html

el.classList.toggle("active")
来源：http://dali.fengsongda.top/Article/details/gtvomnymxb.html

[U102] JS：本地存储
来源：http://dali.svipenyu.cn/Article/details/gtysobvomq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xylfe.cn/Article/details/gtikaewnen.html

[U103] JS：定时器
来源：http://dali.jinqigfzy.top/Article/details/gtrvmnofjd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gthvttmwid.html

[U104] JS：防抖
来源：http://dali.snrcjt.cn/Article/details/gtpvvxbyvy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sxryk.cn/Article/details/gtajzhpqee.html

[U105] JS：节流
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhkavllb.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenlongwang.top/Article/details/gtcmanoxkz.html

[U106] JS：日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtqlhjlkqc.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtnjhjihdg.html

[U107] JS：数字千分位
来源：http://dali.nanxuanxn.top/Article/details/gtdinygkvm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcggaaayb.html

[U108] JS：随机整数
来源：http://dali.cdnleiting.top/Article/details/gtcanfavdn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjvvpcodu.html

[U109] JS：数组分组
来源：http://dali.daxiang520.top/Article/details/gtjfqruqxa.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jlsjyb.cn/Article/details/gtcszrqzsw.html

[U110] JS：数组分块
来源：http://dali.daria6918.cn/Article/details/gtgcjstswc.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtdbxkmsox.html

[U111] JS：对象转 Map
来源：http://dali.guowangkeji.top/Article/details/gtujbyacet.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gtvkobdara.html

[U112] JS：字符串补位
来源：http://dali.hongshengwenyu.top/Article/details/gtcewhmbiw.html

"7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtcyqhuygp.html

[U113] JS：正则替换全部
来源：http://dali.zhengqikj.top/Article/details/gtgtdggizj.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gthniyvius.html

[U114] JS：JSON 深比较
来源：http://dali.daxiang520.top/Article/details/gtvamysqqj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtezurhugs.html

[U115] JS：生成 UUID
来源：http://dali.guowangkeji.top/Article/details/gtwoqfnmrp.html

crypto.randomUUID()
来源：http://dali.mhx1999.top/Article/details/gtqpruqplx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.dashuyun.cn/Article/details/gthyceugqt.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvncuyoux.html

[U117] JS：单元测试
来源：http://dali.dianchejie.cn/Article/details/gtkzmjbgvt.html

npm i -D vitest;  npx vitest
来源：http://dali.havefunace.top/Article/details/gtoibxwpgw.html

[U118] JS：开发服务器
来源：http://dali.xuetiantiany.cn/Article/details/gtibbfylym.html

npm i -D vite;  npx vite
来源：http://dali.gotoacloud.top/Article/details/gtqrxbmqqe.html

[U119] JS：生产构建
来源：http://dali.svipenyu.cn/Article/details/gtjvhifczg.html

npx vite build
来源：http://dali.sufxvd.cn/Article/details/gtougcxcfz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.smart0.xyz/Article/details/gtiqwdayob.html

import.meta.env.VITE_API_URL
来源：http://dali.shzxlz.cn/Article/details/gtkmmzgkdz.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtnxlqcbdl.html

统计汇总
来源：http://dali.kuanghao11.cn/Article/details/gtpnhsnhuy.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiajszmzd.html

按语言统计（条）：
来源：http://dali.jinghuilouyu.cn/Article/details/gtgepyozri.html

Python ......... 252
来源：http://dali.gzhubu.top/Article/details/gtkkqodqzk.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtoroohwpw.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtixcoewdc.html

TypeScript ..... 212
来源：http://dali.zhongyouzk.top/Article/details/gtyzmxiktr.html

Java ........... 212
来源：http://dali.xuetiantiany.cn/Article/details/gtegndgcad.html

Go ............. 212
来源：http://dali.gogol.net.cn/Article/details/gtfwjkdfya.html

Ruby ........... 212
来源：http://dali.yj20258.top/Article/details/gtczcfooza.html

C# ............. 212
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbqdcdbe.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtbasuczir.html

C++ ............ 30
来源：http://dali.gogol.net.cn/Article/details/gthxzbzbss.html

SQL ............ 90
来源：http://dali.ivvv.top/Article/details/gtfnlopype.html

Bash ........... 80
来源：http://dali.hnxiangtu.top/Article/details/gttbwbpdzf.html

Kotlin ......... 15
来源：http://dali.tianlin.xyz/Article/details/gtucqpjsfd.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gtpaxkvqrs.html

Lua ............ 10
来源：http://dali.zhijiandao.cn/Article/details/gtiwmzhsso.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gtshdfuleg.html

Scala .......... 10
来源：http://dali.dianchejie.cn/Article/details/gtnmpjbawd.html

------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gtpmsvfiqd.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gtqxeygmio.html

按章节统计：
来源：http://dali.aizwys.cn/Article/details/gtmeuiznnw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtpnkbkdnh.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.quarkkingdee.top/Article/details/gtpobqadsq.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hnxiangtu.top/Article/details/gtajwvaoxc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gthxnbyiqc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ydzc1.top/Article/details/gtzuxnydvp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.tian-w.cn/Article/details/gtilxfcxlx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gtwzdlwieo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtughjqprm.html


<!-- 参考信息 -->