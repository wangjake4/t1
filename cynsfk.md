代发 wailian999

[T49] Perl：函数
来源：http://dali.yj20258888.top/Article/details/gtdxhdcbip.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtmjrqojet.html

[T50] Perl：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtpswinzhv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttoaajnyc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmqlmkjhw.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtvdfmrony.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtozvltskc.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gtpmsjgoco.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gtgflfibxq.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtsidledzs.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjxmnjhu.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtgrfcpffa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtuhcbmuad.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtcicvdpih.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtvesaybut.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gttnawnqfn.html

case class User(name: String, age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbrbvdxcv.html

[T57] Scala：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtddsgktjw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtxrnfblsm.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtlpwbezli.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtkzxnozcu.html

[T59] Scala：循环
来源：http://dali.haohaochexian.top/Article/details/gtpyypnltj.html

for (i <- 1 to 10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtjcsamcum.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtkjcbceex.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.wangdashe.top/Article/details/gtlzoesttu.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtwuvdwvaw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cdnleiting.top/Article/details/gtqypkezje.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gttcaddmcb.html

[U01] Py：创建虚拟环境
来源：http://dali.gogol.net.cn/Article/details/gtiyfvhzjg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtfkwakmyk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhixingplan.top/Article/details/gtklhtewvn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yangfankeji.com/Article/details/gtljnkuupz.html

[U03] Py：加载 .env 配置
来源：http://dali.ivvv.top/Article/details/gtfewkpopv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtxvenrblt.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtkmqbhilt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.cucudq.cn/Article/details/gtpptcweet.html

[U05] Py：列表去重且保序
来源：http://dali.jqgufenzy.top/Article/details/gttcomqitk.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtwrawumxq.html

[U06] Py：合并两个字典
来源：http://dali.smart0.xyz/Article/details/gtcwqsahaz.html

{**a, **b}
来源：http://dali.chenzaomai.com/Article/details/gtwfdxvxkj.html

[U07] Py：反转字典键值
来源：http://dali.ybcxt.top/Article/details/gtovkndgil.html

{v: k for k, v in d.items()}
来源：http://dali.tianlin.xyz/Article/details/gturfqlmro.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gtkeikiftv.html

[y for x in nested for y in x]
来源：http://dali.jqgfzy.top/Article/details/gtknyiktye.html

[U09] Py：字典取最大值的键
来源：http://dali.sweek.top/Article/details/gtmjlarvxq.html

max(d, key=d.get)
来源：http://dali.cheryme.top/Article/details/gtypcmypmi.html

[U10] Py：按值排序字典
来源：http://dali.sxryk.cn/Article/details/gtlezvhsgv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtxxzglrtd.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gteqigdkrk.html

(x * 2 for x in arr)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxovbxtz.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.nanxuanxn.top/Article/details/gtjtxixkzc.html

Counter(arr).most_common(3)
来源：http://dali.redwolf501.top/Article/details/gtwvstimlb.html

[U13] Py：固定长度队列
来源：http://dali.haohaochexian.top/Article/details/gtfvhdgetq.html

deque(maxlen=10)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuncauhd.html

[U14] Py：分组收集到列表
来源：http://dali.daxiang520.top/Article/details/gtkbfmhgmk.html

defaultdict(list)
来源：http://dali.guowangkeji.top/Article/details/gtipipgybk.html

[U15] Py：高精度计时
来源：http://dali.gaohongyu789.top/Article/details/gtrduaenkj.html

t = time.perf_counter()
来源：http://dali.ivvv.top/Article/details/gtpniqkhnj.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gtyxgvxxtn.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gtxlmlvkzf.html

[U17] Py：初始化日志
来源：http://dali.xuetiantiany.cn/Article/details/gtogkkffcq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hysaishi.cn/Article/details/gthbmlmyer.html

[U18] Py：预编译正则
来源：http://dali.ppjwa.cn/Article/details/gtesszlqos.html

pat = re.compile(r"\d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtcjxcanpp.html

[U19] Py：正则替换带回调
来源：http://dali.c1oappe.top/Article/details/gtehddhwuy.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gtsvhfrbak.html

[U20] Py：缓存函数结果
来源：http://dali.zhiwuduotai.top/Article/details/gttlemdnmq.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gtfdawczjc.html

[U21] Py：自定义上下文管理器
来源：http://dali.cashguo.top/Article/details/gtpmysgqqk.html

@contextlib.contextmanager
来源：http://dali.jlsjyb.cn/Article/details/gtetoemztl.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtmoltjqcz.html

list(zip(*m))
来源：http://dali.mhx1999.top/Article/details/gtbbkdwdxi.html

[U23] Py：分块读取大文件
来源：http://dali.bjfxy.top/Article/details/gttnxggiuh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gttkyxzuti.html

[U24] Py：路径操作
来源：http://dali.bjfxy.top/Article/details/gthhsjkbeh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shuidangran.top/Article/details/gtxkvcyulq.html

[U25] Py：CSV 按字典读
来源：http://dali.xuetiantiany.cn/Article/details/gtvsyqhgpz.html

csv.DictReader(f)
来源：http://dali.0kj1m.cn/Article/details/gtcawvmyiw.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtfqzrizri.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.tian-w.cn/Article/details/gtdcukuujq.html

[U27] Py：异步 HTTP
来源：http://dali.jiagoushi.top/Article/details/gtpzdattid.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hywenlv.cn/Article/details/gtbneyvcaj.html

[U28] Py：类型别名
来源：http://dali.0kj1m.cn/Article/details/gtjtbvltsd.html

UserId = int
来源：http://dali.tianlin.xyz/Article/details/gtdmtempuc.html

[U29] Py：属性校验
来源：http://dali.xylfe.cn/Article/details/gtssovxijv.html

@property 与 @x.setter 配合
来源：http://dali.chenzaomai.com/Article/details/gtecutbxka.html

[U30] Py：数据类
来源：http://dali.yj202588.top/Article/details/gtzytliwxk.html

@dataclass(slots=True)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaivpinb.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gtwdobuhtq.html

python -m pytest -q
来源：http://dali.iojbl.cn/Article/details/gtgrxsxkna.html

[U32] Py：代码格式化
来源：http://dali.sysykeji.top/Article/details/gtxpdllrmz.html

ruff format . && ruff check --fix .
来源：http://dali.aibaodan.cn/Article/details/gtguhbacss.html

[U33] Py：打包发布
来源：http://dali.gotoacloud.top/Article/details/gttmayansm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtvbvgzsqv.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtwnoecodk.html

chardet.detect(raw)
来源：http://dali.gaohongyu789.top/Article/details/gtpqnuxqgb.html

[U35] Py：发送邮件
来源：http://dali.aibaodan.cn/Article/details/gtpbigndvy.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xziqi.cn/Article/details/gtxfiegqht.html

[U36] Py：定时任务
来源：http://dali.snrcjt.cn/Article/details/gtsbzeetco.html

schedule.every(10).minutes.do(job)
来源：http://dali.zhoulong.xyz/Article/details/gtvvawwxxv.html

[U37] Py：读写 Excel
来源：http://dali.ppjwa.cn/Article/details/gtggdglcdv.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gtoefmozqf.html

[U38] Py：获取脚本所在目录
来源：http://dali.snrcjt.cn/Article/details/gtnfyqmzyq.html

Path(__file__).resolve().parent
来源：http://dali.vqdsnc.cn/Article/details/gtefqxvyiw.html

[U39] Py：判断是否在交互环境
来源：http://dali.dashuyun.cn/Article/details/gtfcptxjbf.html

sys.stdout.isatty()
来源：http://dali.hnqzz.top/Article/details/gthkshxlku.html

[U40] Py：打印到标准错误
来源：http://dali.sweek.top/Article/details/gtaaqksrdq.html

print("err", file=sys.stderr)
来源：http://dali.chenjidiqi.icu/Article/details/gtqyktqrov.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.havefunace.top/Article/details/gtcdloygnk.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.sweek.top/Article/details/gtctsfbexu.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtrnrnlscp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.tanke756.top/Article/details/gtsmvjagfl.html

[U43] PHP：声明命名空间
来源：http://dali.guannengcc.top/Article/details/gtznuwopfm.html

namespace App\Http;
来源：http://dali.zhongyouzk.top/Article/details/gtsgvsidtq.html

[U44] PHP：开启严格类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvslgjwkk.html

declare(strict_types=1);
来源：http://dali.jlsjyb.cn/Article/details/gtjaresjeo.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ydzc1.top/Article/details/gtkytnixcu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtdgilejyf.html

[U46] PHP：可空类型
来源：http://dali.ppjwa.cn/Article/details/gtjsbzjllr.html

?string $name = null
来源：http://dali.cucudq.cn/Article/details/gtzhhgjvdj.html

[U47] PHP：联合类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpssoapjs.html

int|string $id
来源：http://dali.ivvv.top/Article/details/gtqxsghzlv.html

[U48] PHP：纯枚举
来源：http://dali.feifeiyinyue.top/Article/details/gtfafqbbpt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.smart0.xyz/Article/details/gtjkoxpirb.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtrocgukqt.html

public readonly string $name
来源：http://dali.zhongyouzk.top/Article/details/gthdpecoae.html

[U50] PHP：构造器属性提升
来源：http://dali.316326.xyz/Article/details/gtbrxxbdsl.html

public function __construct(private int $id) {}
来源：http://dali.hammf.cn/Article/details/gthkrqconf.html

[U51] PHP：数组解构
来源：http://dali.ivvv.top/Article/details/gtdxbyvnxv.html

[$a, $b] = $arr;
来源：http://dali.birdmap.top/Article/details/gttfqtejzj.html

[U52] PHP：箭头函数
来源：http://dali.jinqigufen.top/Article/details/gtqdpsonxh.html

$double = fn($x) => $x * 2;
来源：http://dali.hongshengwenyu.top/Article/details/gtvkmegzmm.html

[U53] PHP：空合并运算符
来源：http://dali.ivvv.top/Article/details/gtaupqhinl.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbksdadop.html

[U54] PHP：空安全调用
来源：http://dali.ehwqpu.com/Article/details/gtjfqzfnbx.html

$obj?->method()
来源：http://dali.yvedp.cn/Article/details/gthhnbsiij.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gtcdwdhaka.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj20258.top/Article/details/gtocgkzvje.html

[U56] PHP：命名参数
来源：http://dali.jinqigufen.top/Article/details/gtzusjyqrt.html

f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtxcxsjcef.html

[U57] PHP：字符串插值
来源：http://dali.redwolf501.top/Article/details/gttemupopu.html

"值: {$a}"
来源：http://dali.316326.xyz/Article/details/gtezvbqaet.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gtpltsnjwp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zycfv.cn/Article/details/gtqwlveull.html

[U59] PHP：自定义排序
来源：http://dali.yueranfly.top/Article/details/gtpvpcmelk.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xylfe.cn/Article/details/gtddduerrw.html

[U60] PHP：JSON 编解码
来源：http://dali.sufxvd.cn/Article/details/gtlugfrhuf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hammf.cn/Article/details/gtytmghuwg.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gtkqghxrdr.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yueranfly.top/Article/details/gtibquaxip.html

[U62] PHP：日期对象
来源：http://dali.ehwqpu.com/Article/details/gtbtcvngce.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhixingplan.top/Article/details/gtxocvkarf.html

[U63] PHP：文件读写
来源：http://dali.ppjwa.cn/Article/details/gtrcnpwliv.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.haohaochexian.top/Article/details/gtgqoryate.html

[U64] PHP：目录遍历
来源：http://dali.xziqi.cn/Article/details/gteupczvdc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.fengsongda.top/Article/details/gtpukihrjv.html

[U65] PHP：会话
来源：http://dali.jinqigfzy.top/Article/details/gtklzqzyxn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtmtemgglm.html

[U66] PHP：设置 Cookie
来源：http://dali.svipenyu.cn/Article/details/gtjgzbblvf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cheryme.top/Article/details/gtevoubkpb.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtdogrneos.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.daria6918.cn/Article/details/gtoivyhlyl.html

[U68] PHP：PDO 连接
来源：http://dali.chenzaomai.com/Article/details/gtsosuxdrx.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yvedp.cn/Article/details/gtoqognlrp.html

[U69] PHP：PDO 预处理
来源：http://dali.hammf.cn/Article/details/gtyxgqlqkn.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuetiantiany.cn/Article/details/gtjsmxuoco.html

[U70] PHP：PDO 事务
来源：http://dali.tianlin.xyz/Article/details/gtcbilvxou.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cucudq.cn/Article/details/gtaswmldbf.html

[U71] PHP：抛出异常
来源：http://dali.tianlin.xyz/Article/details/gthkxxdcla.html

throw new RuntimeException("失败", 500);
来源：http://dali.gzhubu.top/Article/details/gthlpisdvq.html

[U72] PHP：写错误日志
来源：http://dali.gotoacloud.top/Article/details/gteuwiaahl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhijiandao.cn/Article/details/gtokgtukhx.html

[U73] PHP：读取 ini 配置
来源：http://dali.gotoacloud.top/Article/details/gtufgxprjh.html

parse_ini_file("config.ini", true)
来源：http://dali.svipenyu.cn/Article/details/gtgqljhfug.html

[U74] PHP：读取环境变量
来源：http://dali.yonumen.top/Article/details/gtvqzlluur.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhoulong.xyz/Article/details/gtexqmeenh.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtmojkzkxz.html

composer require psr/container
来源：http://dali.iojbl.cn/Article/details/gtmgvteayn.html

[U76] PHP：简单路由
来源：http://dali.hammf.cn/Article/details/gtylnawisn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gtrnmjvufd.html

[U77] PHP：模板渲染
来源：http://dali.quarkkingdee.top/Article/details/gtfclrbzgz.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gtcnputaot.html

[U78] PHP：单元测试
来源：http://dali.sxryk.cn/Article/details/gteudnmnjy.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gtyrdxmhuz.html

[U79] PHP：静态分析
来源：http://dali.jinyuanbaomall.cn/Article/details/gttznubfpu.html

composer require --dev phpstan/phpstan
来源：http://dali.andypj.xyz/Article/details/gtdnnqmzsx.html

[U80] PHP：代码规范修复
来源：http://dali.hfpthk.cn/Article/details/gtjggvlzhu.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjtltvdf.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gtmquosoiy.html

npm init -y;  npm i express
来源：http://dali.xuanzx.com/Article/details/gtdclcxavh.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gteoooqolf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhijiandao.cn/Article/details/gtbdykyzjq.html

[U83] JS：ES Module 导入导出
来源：http://dali.ivvv.top/Article/details/gtudwbdcxx.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtvyygndov.html

[U84] JS：CommonJS 写法
来源：http://dali.yuanzhike.top/Article/details/gtcnvefxih.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.316326.xyz/Article/details/gtiuzfoluh.html

[U85] JS：可选链
来源：http://dali.yj20258.top/Article/details/gtbcyeswnv.html

a?.b?.c
来源：http://dali.cdnleiting.top/Article/details/gtgbpilels.html

[U86] JS：空值合并
来源：http://dali.sweek.top/Article/details/gtotkiqnue.html

a ?? b
来源：http://dali.cheryme.top/Article/details/gtluldmclv.html

[U87] JS：解构默认值
来源：http://dali.jiagoushi.top/Article/details/gtrozzodvy.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtichgagdf.html

[U88] JS：对象展开合并
来源：http://dali.jinqigfzy.top/Article/details/gtxbwyirom.html

{ ...a, ...b }
来源：http://dali.aibaodan.cn/Article/details/gtffdcneiz.html

[U89] JS：数组去重
来源：http://dali.xuetiantiany.cn/Article/details/gtlujkvovd.html

[...new Set(arr)]
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvbqdeoj.html

[U90] JS：数字数组排序
来源：http://dali.cheryme.top/Article/details/gtjrfpvnxa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xuetiantiany.cn/Article/details/gtpkxpsbts.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gtegsrgegr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ivvv.top/Article/details/gtrifugsyo.html

[U92] JS：深拷贝
来源：http://dali.snrcjt.cn/Article/details/gtdsmgoqcq.html

structuredClone(obj)
来源：http://dali.wangdashe.top/Article/details/gtjkjdeaos.html

[U93] JS：模板字符串
来源：http://dali.gaohongyu789.top/Article/details/gttdgiglam.html

`共 ${n} 条`
来源：http://dali.hywenlv.cn/Article/details/gthpazwvyr.html

[U94] JS：箭头函数
来源：http://dali.daria6918.cn/Article/details/gtufhcccub.html

const double = x => x * 2;
来源：http://dali.quarkkingdee.top/Article/details/gtssbiylzy.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtjyswhdix.html

new Promise((resolve, reject) => {})
来源：http://dali.hnxiangtu.top/Article/details/gtrcbufmrc.html

[U96] JS：async/await 与异常
来源：http://dali.jianghu66.top/Article/details/gtclnseevd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zhixingplan.top/Article/details/gtnzaypsfz.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gtvvvgfusg.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtjcxjjbic.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtkfpmydiw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.tian-w.cn/Article/details/gtpebcfbmx.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtkonwiyca.html

el.addEventListener("click", e => {})
来源：http://dali.havefunace.top/Article/details/gtkwmigeea.html

[U100] JS：DOM 查询
来源：http://dali.redwolf501.top/Article/details/gtjslyttkc.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtrblfzdtl.html

[U101] JS：classList 操作
来源：http://dali.ivvv.top/Article/details/gtdqqorsku.html

el.classList.toggle("active")
来源：http://dali.cucudq.cn/Article/details/gtqkmtzljl.html

[U102] JS：本地存储
来源：http://dali.zdqjudy.top/Article/details/gtqljgxwqb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daria6918.cn/Article/details/gtfzbzvxls.html

[U103] JS：定时器
来源：http://dali.yj20258.top/Article/details/gtucbiyugw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenzaomai.com/Article/details/gttaqfpehl.html

[U104] JS：防抖
来源：http://dali.ivvv.top/Article/details/gtmbghrhnm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.pycfn.com/Article/details/gtumwtfkam.html

[U105] JS：节流
来源：http://dali.shzxlz.cn/Article/details/gtorxcubrd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.dashuyun.cn/Article/details/gtzjudfnng.html

[U106] JS：日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtveajhjxo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yonumen.top/Article/details/gtetnvknqh.html

[U107] JS：数字千分位
来源：http://dali.jinghuilouyu.cn/Article/details/gtufsqhvkd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gtyfokmptf.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gtprdfsdzg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yueranfly.top/Article/details/gtwknzowbd.html

[U109] JS：数组分组
来源：http://dali.yj20258888.top/Article/details/gtqguoqnoc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sysykeji.top/Article/details/gteefvyand.html

[U110] JS：数组分块
来源：http://dali.shuidangran.top/Article/details/gtuildmlwx.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtkeyihfka.html

[U111] JS：对象转 Map
来源：http://dali.hnxiangtu.top/Article/details/gttsucjyre.html

new Map(Object.entries(obj))
来源：http://dali.guowangkeji.top/Article/details/gtgforieyu.html

[U112] JS：字符串补位
来源：http://dali.pycfn.com/Article/details/gtoydlptqk.html

"7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gthqzhcqcd.html

[U113] JS：正则替换全部
来源：http://dali.smart0.xyz/Article/details/gtpgatvgzh.html

s.replaceAll("a", "b")
来源：http://dali.zhoulong.xyz/Article/details/gtccjtljou.html

[U114] JS：JSON 深比较
来源：http://dali.yj202588.top/Article/details/gtfsbmnhtb.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.andypj.xyz/Article/details/gtuvilhtkh.html

[U115] JS：生成 UUID
来源：http://dali.jinghuilouyu.cn/Article/details/gtqncgebsl.html

crypto.randomUUID()
来源：http://dali.guowangkeji.top/Article/details/gtaiigsdrc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jqgfzy.top/Article/details/gtbdlfhccw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.sxryk.cn/Article/details/gtmdyieorx.html

[U117] JS：单元测试
来源：http://dali.cheryme.top/Article/details/gtxhtiqanh.html

npm i -D vitest;  npx vitest
来源：http://dali.ppjwa.cn/Article/details/gttmkjdybs.html

[U118] JS：开发服务器
来源：http://dali.xuetiantiany.cn/Article/details/gtgzgevvyy.html

npm i -D vite;  npx vite
来源：http://dali.jianghu66.top/Article/details/gthcdqsmvx.html

[U119] JS：生产构建
来源：http://dali.quarkkingdee.top/Article/details/gtwktsimoo.html

npx vite build
来源：http://dali.andypj.xyz/Article/details/gthlmcotdc.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtyilrlnfa.html

import.meta.env.VITE_API_URL
来源：http://dali.aizwys.cn/Article/details/gtvzgahoqv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtaebyvidp.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gtnkmcmkah.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtrfvdairz.html

按语言统计（条）：
来源：http://dali.zhongyouzk.top/Article/details/gtzgdxuiub.html

Python ......... 252
来源：http://dali.zhijiandao.cn/Article/details/gtdrhkljje.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtcehawtws.html

JavaScript ..... 252
来源：http://dali.xylfe.cn/Article/details/gtgtjsijna.html

TypeScript ..... 212
来源：http://dali.guannengcc.top/Article/details/gtaabrlgjl.html

Java ........... 212
来源：http://dali.cashguo.top/Article/details/gtftfobpsg.html

Go ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtaznefrod.html

Ruby ........... 212
来源：http://dali.0kj1m.cn/Article/details/gtfimssqnk.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gttlnmymda.html

C .............. 30
来源：http://dali.fzhhl.top/Article/details/gtutgcwsqq.html

C++ ............ 30
来源：http://dali.c1oappe.top/Article/details/gtrabvlucz.html

SQL ............ 90
来源：http://dali.svipenyu.cn/Article/details/gtdvrwkxjw.html

Bash ........... 80
来源：http://dali.xylfe.cn/Article/details/gtkfygrnnv.html

Kotlin ......... 15
来源：http://dali.ydzc1.top/Article/details/gtnjekswbi.html

Swift .......... 15
来源：http://dali.ehwqpu.com/Article/details/gtthnxetrv.html

Lua ............ 10
来源：http://dali.fzhhl.top/Article/details/gtgyuejguy.html

Perl ........... 10
来源：http://dali.hongshengwenyu.top/Article/details/gtbcvopvvc.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtwwztsbhr.html

------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtzjqlirzd.html

合计 ........... 2106 条
来源：http://dali.svipenyu.cn/Article/details/gtahhszhgy.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocxgwaip.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtbjcevhgz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtnffudmtm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yj202588.top/Article/details/gtmnnngzrq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.xylfe.cn/Article/details/gtyioxymit.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cheryme.top/Article/details/gtxnnfxyme.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuanzx.com/Article/details/gtfkomeknr.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.haohaochexian.top/Article/details/gttsmiumhw.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gzhubu.top/Article/details/gthtzsbzdc.html


<!-- 参考信息 -->