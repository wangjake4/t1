代发 wailian999

[T49] Perl：函数
来源：http://dali.nwbrower.top/Article/details/gt2nvjavpwm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2mdxauqwh.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gt2jmzjjcdo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guowangkeji.top/Article/details/gt2danczvmf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nqtkqhcb.html

[T51] Scala：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gt2jeddnjao.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gt2ckpojytg.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gt2yqsffwjy.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2gbrsgrrs.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2laxxyzml.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqzvyqkm.html

[T54] Scala：集合映射
来源：http://dali.hnqzz.top/Article/details/gt2wzgkfqom.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ckthjtae.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gt2rcysmkmd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2iocnppor.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gt2acqsriwg.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2sqfjkfwt.html

[T57] Scala：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gt2hvuwtvzc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gt2nbrmwcen.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gt2zlnvghhc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.fzhhl.top/Article/details/gt2xkbokuxr.html

[T59] Scala：循环
来源：http://dali.yonumen.top/Article/details/gt2aeeqtsua.html

for (i <- 1 to 10) println(i)
来源：http://dali.hywenlv.cn/Article/details/gt2vpzafzoz.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gt2sndlqxrh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gt2wjxqxrck.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2eiouzett.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2fwojednq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ctmytqqn.html

[U01] Py：创建虚拟环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2bnwmrpvr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.iojbl.cn/Article/details/gt2qigefllu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.wangshuangyany.cn/Article/details/gt2ddwvkcfz.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.c1oappe.top/Article/details/gt2ifhfaekq.html

[U03] Py：加载 .env 配置
来源：http://dali.snrcjt.cn/Article/details/gt2lalralkb.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhengqikj.top/Article/details/gt2jpyodxsz.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pzdpaodj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urwenytm.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gt2xrrsnykt.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2cyolwjfk.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gt2uyjattrz.html

{**a, **b}
来源：http://dali.redwolf501.top/Article/details/gt2lzgathwu.html

[U07] Py：反转字典键值
来源：http://dali.tianlin.xyz/Article/details/gt2yvhddeco.html

{v: k for k, v in d.items()}
来源：http://dali.chenzaomai.com/Article/details/gt2cljeheef.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gt2iqdoeuqt.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gt2opoknukf.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gt2lqbejgvz.html

max(d, key=d.get)
来源：http://dali.pengpengdd.cyou/Article/details/gt2drasphki.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gt2agaszrlt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sxryk.cn/Article/details/gt2iygeigew.html

[U11] Py：生成器表达式
来源：http://dali.hfpthk.cn/Article/details/gt2uwrksgwl.html

(x * 2 for x in arr)
来源：http://dali.jinqigufen.top/Article/details/gt2xrtehnix.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.sysykeji.top/Article/details/gt2xcppwukw.html

Counter(arr).most_common(3)
来源：http://dali.ppjwa.cn/Article/details/gt2tohfslpb.html

[U13] Py：固定长度队列
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pddqiubl.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gmrqymbl.html

[U14] Py：分组收集到列表
来源：http://dali.mhx1999.top/Article/details/gt2qfkamuer.html

defaultdict(list)
来源：http://dali.wangdashe.top/Article/details/gt2brtaftgr.html

[U15] Py：高精度计时
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ylhcudvt.html

t = time.perf_counter()
来源：http://dali.zhiwuduotai.top/Article/details/gt2kqjitpro.html

[U16] Py：命令行参数解析
来源：http://dali.smart0.xyz/Article/details/gt2oixakaol.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gt2gihasfoo.html

[U17] Py：初始化日志
来源：http://dali.guannengcc.top/Article/details/gt2nuhibywv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hnqzz.top/Article/details/gt2rckvskpy.html

[U18] Py：预编译正则
来源：http://dali.jinqigufen.top/Article/details/gt2lekxitvs.html

pat = re.compile(r"\d+")
来源：http://dali.daria6918.cn/Article/details/gt2gkqyesbh.html

[U19] Py：正则替换带回调
来源：http://dali.dashuyun.cn/Article/details/gt2ynrxtqvn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yomzxaic.html

[U20] Py：缓存函数结果
来源：http://dali.feifeiyinyue.top/Article/details/gt2tttsygtu.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aizwys.cn/Article/details/gt2wnoythny.html

[U21] Py：自定义上下文管理器
来源：http://dali.tianlin.xyz/Article/details/gt2pbvqklgv.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gt2bhrwvmfe.html

[U22] Py：矩阵转置
来源：http://dali.cdnleiting.top/Article/details/gt2maqlhndi.html

list(zip(*m))
来源：http://dali.jiagoushi.top/Article/details/gt2kyzditif.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lpfufjae.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.bjfxy.top/Article/details/gt2vcifpsir.html

[U24] Py：路径操作
来源：http://dali.nwbrower.top/Article/details/gt2pqjflnih.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gt2llgofsfi.html

[U25] Py：CSV 按字典读
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgfgeweo.html

csv.DictReader(f)
来源：http://dali.gaohongyu789.top/Article/details/gt2bqzemfln.html

[U26] Py：并发下载
来源：http://dali.ehwqpu.com/Article/details/gt2ohbpvbtj.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj20258888.top/Article/details/gt2yovruoge.html

[U27] Py：异步 HTTP
来源：http://dali.cucudq.cn/Article/details/gt2fdjgtshp.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gt2bqntkvbp.html

[U28] Py：类型别名
来源：http://dali.gogol.net.cn/Article/details/gt2clxuzabi.html

UserId = int
来源：http://dali.jinqigfzy.top/Article/details/gt2qyvsjesg.html

[U29] Py：属性校验
来源：http://dali.yvedp.cn/Article/details/gt2nzejakmm.html

@property 与 @x.setter 配合
来源：http://dali.tianlin.xyz/Article/details/gt2qbxlhdjs.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gt2xeswcdwq.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtisgzdv.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2pyjyjscy.html

python -m pytest -q
来源：http://dali.yj20258.top/Article/details/gt2khwzlzrf.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2buoajlgm.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gt2ezliknvo.html

[U33] Py：打包发布
来源：http://dali.gzhubu.top/Article/details/gt2ybrgfgvc.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhixingplan.top/Article/details/gt2fspseuud.html

[U34] Py：判断编码
来源：http://dali.yj202588.top/Article/details/gt2xfhrjfza.html

chardet.detect(raw)
来源：http://dali.yangfankeji.com/Article/details/gt2juhnocjl.html

[U35] Py：发送邮件
来源：http://dali.xuanzx.com/Article/details/gt2jwsfqqnk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.tianlin.xyz/Article/details/gt2xrbpubth.html

[U36] Py：定时任务
来源：http://dali.guannengcc.top/Article/details/gt2eakljzmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhiwuduotai.top/Article/details/gt2umlunwue.html

[U37] Py：读写 Excel
来源：http://dali.jiagoushi.top/Article/details/gt2zrfptgdm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.wangdashe.top/Article/details/gt2bduihhtv.html

[U38] Py：获取脚本所在目录
来源：http://dali.jlsjyb.cn/Article/details/gt2hizwceap.html

Path(__file__).resolve().parent
来源：http://dali.jinqigfzy.top/Article/details/gt2ssfoqmzk.html

[U39] Py：判断是否在交互环境
来源：http://dali.ivvv.top/Article/details/gt2uekbxieb.html

sys.stdout.isatty()
来源：http://dali.redwolf501.top/Article/details/gt2jyvwzuje.html

[U40] Py：打印到标准错误
来源：http://dali.pengpengdd.cyou/Article/details/gt2yiqrphkt.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gt2ekppfxne.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jinqigfzy.top/Article/details/gt2tzcoarlq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.smart0.xyz/Article/details/gt2dellqcsa.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdmxjojx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gt2zshyqmvu.html

[U43] PHP：声明命名空间
来源：http://dali.fzhhl.top/Article/details/gt2mfiewsmj.html

namespace App\Http;
来源：http://dali.iojbl.cn/Article/details/gt2fhwqemfq.html

[U44] PHP：开启严格类型
来源：http://dali.ybcxt.top/Article/details/gt2xqwverlz.html

declare(strict_types=1);
来源：http://dali.iojbl.cn/Article/details/gt2nhgipuvn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jianghu66.top/Article/details/gt2bcpqqomh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gt2htvyadml.html

[U46] PHP：可空类型
来源：http://dali.jqgfzy.top/Article/details/gt2mnzdffet.html

?string $name = null
来源：http://dali.yonumen.top/Article/details/gt2otcdxfww.html

[U47] PHP：联合类型
来源：http://dali.hongshengwenyu.top/Article/details/gt2luckvouf.html

int|string $id
来源：http://dali.wangdashe.top/Article/details/gt2djcilycc.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gt2imvpzxwg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj20258.top/Article/details/gt2kocvnede.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gt2fcehbwjb.html

public readonly string $name
来源：http://dali.hnxiangtu.top/Article/details/gt2adqriopu.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gt2iajcmpmm.html

public function __construct(private int $id) {}
来源：http://dali.hywenlv.cn/Article/details/gt2epxearjs.html

[U51] PHP：数组解构
来源：http://dali.shuidangran.top/Article/details/gt2pwgbjtnd.html

[$a, $b] = $arr;
来源：http://dali.tanke756.top/Article/details/gt2szhuobjl.html

[U52] PHP：箭头函数
来源：http://dali.cheryme.top/Article/details/gt2ibtjfzda.html

$double = fn($x) => $x * 2;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mvdvohjs.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gt2tbgbhrcz.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gt2uhdivvpx.html

[U54] PHP：空安全调用
来源：http://dali.zhengqikj.top/Article/details/gt2hzgkwvqn.html

$obj?->method()
来源：http://dali.sufxvd.cn/Article/details/gt2yhfzydku.html

[U55] PHP：match 表达式
来源：http://dali.wangshuangyany.cn/Article/details/gt2jmnuhdbs.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xziqi.cn/Article/details/gt2fxyqfeih.html

[U56] PHP：命名参数
来源：http://dali.zhixingplan.top/Article/details/gt2zjjjless.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gt2kvgkqluk.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2blqxuiff.html

"值: {$a}"
来源：http://dali.jiagoushi.top/Article/details/gt2bunutqtq.html

[U58] PHP：数组三件套
来源：http://dali.hongshengwenyu.top/Article/details/gt2jurwaljv.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tianlin.xyz/Article/details/gt2uozoxieo.html

[U59] PHP：自定义排序
来源：http://dali.kuanghao11.cn/Article/details/gt2gyrnmrcx.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gt2sosnkjkw.html

[U60] PHP：JSON 编解码
来源：http://dali.hongshengwenyu.top/Article/details/gt2cksbijtv.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.mhx1999.top/Article/details/gt2eknxipol.html

[U61] PHP：正则
来源：http://dali.cqqwz.cn/Article/details/gt2waagkxvf.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhengqikj.top/Article/details/gt2awndzqrv.html

[U62] PHP：日期对象
来源：http://dali.cdnleiting.top/Article/details/gt2nwlronbg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gt2ffmtqjru.html

[U63] PHP：文件读写
来源：http://dali.chenzaomai.com/Article/details/gt2ddryvhqv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ivvv.top/Article/details/gt2eimnezwj.html

[U64] PHP：目录遍历
来源：http://dali.hywenlv.cn/Article/details/gt2afgpleud.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zycfv.cn/Article/details/gt2pdfkbtlz.html

[U65] PHP：会话
来源：http://dali.fzhhl.top/Article/details/gt2oquclthz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gt2xaagtsmi.html

[U66] PHP：设置 Cookie
来源：http://dali.fzhhl.top/Article/details/gt2orzeympa.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctvtbafj.html

[U67] PHP：处理文件上传
来源：http://dali.andypj.xyz/Article/details/gt2qpzzbmbn.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.quarkkingdee.top/Article/details/gt2kuxqzyrd.html

[U68] PHP：PDO 连接
来源：http://dali.birdmap.top/Article/details/gt2yqmhbrhp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ehwqpu.com/Article/details/gt2rdnisftf.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gt2jpmkxcib.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.gaohongyu789.top/Article/details/gt2cuhfjkpp.html

[U70] PHP：PDO 事务
来源：http://dali.zhengqikj.top/Article/details/gt2rcjsqdqz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gt2zewducgw.html

[U71] PHP：抛出异常
来源：http://dali.mhx1999.top/Article/details/gt2mxqboeti.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2gxufgmlv.html

[U72] PHP：写错误日志
来源：http://dali.yanxiufei.cn/Article/details/gt2rqhcauwc.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cqqwz.cn/Article/details/gt2coeprgqv.html

[U73] PHP：读取 ini 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2ixndienu.html

parse_ini_file("config.ini", true)
来源：http://dali.c1oappe.top/Article/details/gt2bjzhxgkv.html

[U74] PHP：读取环境变量
来源：http://dali.jianghu66.top/Article/details/gt2qrbwrxlc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zdqjudy.top/Article/details/gt2oksscjum.html

[U75] PHP：依赖注入
来源：http://dali.hnxiangtu.top/Article/details/gt2yovqrlge.html

composer require psr/container
来源：http://dali.sufxvd.cn/Article/details/gt2mymxdkfg.html

[U76] PHP：简单路由
来源：http://dali.xziqi.cn/Article/details/gt2cfqcnnah.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gt2leurjtuk.html

[U77] PHP：模板渲染
来源：http://dali.havefunace.top/Article/details/gt2tvpagzfh.html

composer require twig/twig
来源：http://dali.yj20258.top/Article/details/gt2faebfbbk.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2gktgwhqz.html

composer require --dev phpunit/phpunit
来源：http://dali.hongshengwenyu.top/Article/details/gt2obyeccxz.html

[U79] PHP：静态分析
来源：http://dali.ppjwa.cn/Article/details/gt2yovqjzbs.html

composer require --dev phpstan/phpstan
来源：http://dali.cqqwz.cn/Article/details/gt2xqnkchdx.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gt2cnzglelr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jqgfzy.top/Article/details/gt2bgmwovik.html

[U81] JS：初始化项目
来源：http://dali.sysykeji.top/Article/details/gt2aazikoqv.html

npm init -y;  npm i express
来源：http://dali.bjfxy.top/Article/details/gt2qbphffbx.html

[U82] JS：package.json 脚本
来源：http://dali.fengsongda.top/Article/details/gt2rghxfarx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.daxiang520.top/Article/details/gt2qxghsuwz.html

[U83] JS：ES Module 导入导出
来源：http://dali.kuanghao11.cn/Article/details/gt2cthplukp.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gt2aptjshgo.html

[U84] JS：CommonJS 写法
来源：http://dali.tian-w.cn/Article/details/gt2jeijkvwv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxuanxn.top/Article/details/gt2tavwnbjj.html

[U85] JS：可选链
来源：http://dali.daria6918.cn/Article/details/gt2muaofsry.html

a?.b?.c
来源：http://dali.yj20258888.top/Article/details/gt2vmafmdig.html

[U86] JS：空值合并
来源：http://dali.yj20258.top/Article/details/gt2ldpkhsvb.html

a ?? b
来源：http://dali.jianghu66.top/Article/details/gt2zwudbdst.html

[U87] JS：解构默认值
来源：http://dali.shzxlz.cn/Article/details/gt2ekfvfsxu.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gt2nzbuxchv.html

[U88] JS：对象展开合并
来源：http://dali.ppjwa.cn/Article/details/gt2mnnrhckt.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gt2garlwbup.html

[U89] JS：数组去重
来源：http://dali.gaohongyu789.top/Article/details/gt2uxfllnvi.html

[...new Set(arr)]
来源：http://dali.wangdashe.top/Article/details/gt2dmqmkvfl.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gt2bbljaveh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jqgufenzy.top/Article/details/gt2osuxuywv.html

[U91] JS：对象键值遍历
来源：http://dali.yj202588.top/Article/details/gt2tpzledzi.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gt2wgcfwthk.html

[U92] JS：深拷贝
来源：http://dali.cdnleiting.top/Article/details/gt2xujpdkhm.html

structuredClone(obj)
来源：http://dali.yj20258.top/Article/details/gt2anmpzwyb.html

[U93] JS：模板字符串
来源：http://dali.ppjwa.cn/Article/details/gt2qzbgabvk.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gt2zxpvwdhl.html

[U94] JS：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2ptycuqrx.html

const double = x => x * 2;
来源：http://dali.jianghu66.top/Article/details/gt2xilwacgn.html

[U95] JS：Promise 包装
来源：http://dali.sxryk.cn/Article/details/gt2djgschmd.html

new Promise((resolve, reject) => {})
来源：http://dali.cucudq.cn/Article/details/gt2agxuewnu.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gt2dcampspk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hammf.cn/Article/details/gt2uwzregzh.html

[U97] JS：并发请求
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhkgntbq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yvedp.cn/Article/details/gt2foduopnw.html

[U98] JS：fetch 带 JSON
来源：http://dali.9152youxi.cn/Article/details/gt2lnsaxgjt.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.c1oappe.top/Article/details/gt2gdwbxrcr.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gt2jivivjhq.html

el.addEventListener("click", e => {})
来源：http://dali.daxiang520.top/Article/details/gt2tjtinqgw.html

[U100] JS：DOM 查询
来源：http://dali.ppjwa.cn/Article/details/gt2mcusivqd.html

document.querySelector(".item")
来源：http://dali.ehwqpu.com/Article/details/gt2igxfdpoh.html

[U101] JS：classList 操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmorafwq.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gt2silmrvht.html

[U102] JS：本地存储
来源：http://dali.zhiwuduotai.top/Article/details/gt2okudvzoa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2mgbvbxrb.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gt2aohkbjox.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.0kj1m.cn/Article/details/gt2kbzkjbyg.html

[U104] JS：防抖
来源：http://dali.cdnleiting.top/Article/details/gt2ylqsdzfi.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.haohaochexian.top/Article/details/gt2uqvqczby.html

[U105] JS：节流
来源：http://dali.yangfankeji.com/Article/details/gt2qsfyycmy.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj202588.top/Article/details/gt2ehjpkhux.html

[U106] JS：日期格式化
来源：http://dali.yonumen.top/Article/details/gt2zjvacxin.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.gotoacloud.top/Article/details/gt2nafvcjtt.html

[U107] JS：数字千分位
来源：http://dali.c1oappe.top/Article/details/gt2jyqtdwxc.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2muypihwi.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gt2ggyivjvg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jlsjyb.cn/Article/details/gt2wzqsdxtg.html

[U109] JS：数组分组
来源：http://dali.svipenyu.cn/Article/details/gt2krdnogdl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zycfv.cn/Article/details/gt2cvfcsabw.html

[U110] JS：数组分块
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abnbcweq.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hfpthk.cn/Article/details/gt2liyfaivs.html

[U111] JS：对象转 Map
来源：http://dali.jiagoushi.top/Article/details/gt2hnqonvur.html

new Map(Object.entries(obj))
来源：http://dali.nwbrower.top/Article/details/gt2akxzvkjl.html

[U112] JS：字符串补位
来源：http://dali.xylfe.cn/Article/details/gt2qqnwgfqg.html

"7".padStart(3, "0")
来源：http://dali.gaohongyu789.top/Article/details/gt2caroarkq.html

[U113] JS：正则替换全部
来源：http://dali.gzhubu.top/Article/details/gt2bblapwum.html

s.replaceAll("a", "b")
来源：http://dali.hysaishi.cn/Article/details/gt2slkjvkto.html

[U114] JS：JSON 深比较
来源：http://dali.birdmap.top/Article/details/gt2mazjecoo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gt2nroghicq.html

[U115] JS：生成 UUID
来源：http://dali.gaohongyu789.top/Article/details/gt2bhvjqaqs.html

crypto.randomUUID()
来源：http://dali.aibaodan.cn/Article/details/gt2jjjvdgdf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xziqi.cn/Article/details/gt2zxyudsoz.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gt2oyishpct.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gt2ywpotjeq.html

npm i -D vitest;  npx vitest
来源：http://dali.xziqi.cn/Article/details/gt2utwncmqz.html

[U118] JS：开发服务器
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ndpoaple.html

npm i -D vite;  npx vite
来源：http://dali.gogol.net.cn/Article/details/gt2fgcvrvcz.html

[U119] JS：生产构建
来源：http://dali.zhiwuduotai.top/Article/details/gt2opdkqbzu.html

npx vite build
来源：http://dali.guannengcc.top/Article/details/gt2soblovhh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gt2otnjqksq.html

import.meta.env.VITE_API_URL
来源：http://dali.nanxuanxn.top/Article/details/gt2gmgnpqoj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rqhjzxtz.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gt2ruhutlpk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2hlusjbgb.html

按语言统计（条）：
来源：http://dali.gogol.net.cn/Article/details/gt2dfobwdck.html

Python ......... 252
来源：http://dali.jinqigufen.top/Article/details/gt2nrbgttiq.html

PHP ............ 252
来源：http://dali.shuidangran.top/Article/details/gt2txhmbrit.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2jzjyxszn.html

TypeScript ..... 212
来源：http://dali.hywenlv.cn/Article/details/gt2ejjunstv.html

Java ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2raditgtv.html

Go ............. 212
来源：http://dali.daxiang520.top/Article/details/gt2tsjsgrpt.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2wemiadth.html

C# ............. 212
来源：http://dali.yj202588.top/Article/details/gt2mziigoub.html

C .............. 30
来源：http://dali.jinqigufen.top/Article/details/gt2opptofzt.html

C++ ............ 30
来源：http://dali.andypj.xyz/Article/details/gt2jerotvvu.html

SQL ............ 90
来源：http://dali.jyoumei.cn/Article/details/gt2psbwzrzn.html

Bash ........... 80
来源：http://dali.0kj1m.cn/Article/details/gt2mabxlwyd.html

Kotlin ......... 15
来源：http://dali.yj20258888.top/Article/details/gt2tteoimbq.html

Swift .......... 15
来源：http://dali.jqgufenzy.top/Article/details/gt2nnavhskf.html

Lua ............ 10
来源：http://dali.yongpay.top/Article/details/gt2yvpjxsqv.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gt2rleqgkww.html

Scala .......... 10
来源：http://dali.svipenyu.cn/Article/details/gt2qeyvazdo.html

------------------------------------
来源：http://dali.cashguo.top/Article/details/gt2gmkqmdps.html

合计 ........... 2106 条
来源：http://dali.guannengcc.top/Article/details/gt2vxzdinwe.html

按章节统计：
来源：http://dali.smart0.xyz/Article/details/gt2ycctdcij.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.guannengcc.top/Article/details/gt2byaexets.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aigzubjy.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hysaishi.cn/Article/details/gt2slirseoc.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2wqnvfvtv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hongshengwenyu.top/Article/details/gt2ggnkitbl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gt2teehsvaa.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.hnqzz.top/Article/details/gt2afsvjgwy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gt2lktjmlsa.html


<!-- 参考信息 -->