代发 wailian999

[T49] Perl：函数
来源：http://dali.hnxiangtu.top/Article/details/gtwwswsxyj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtsqqlsygz.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gthbxvwojk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtxvlcktgh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtndtnkwhz.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtwglsudkf.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtoujtpkbc.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtbbvfxuxl.html

val a = 1;  var b = 2
来源：http://dali.guannengcc.top/Article/details/gtuenwrtgr.html

[T53] Scala：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gthrqkjknm.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtdcmzzbna.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gttyueaugv.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jiagoushi.top/Article/details/gtiuelivvl.html

[T55] Scala：集合过滤
来源：http://dali.guannengcc.top/Article/details/gthlwawsqb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guowangkeji.top/Article/details/gtreozevxa.html

[T56] Scala：样例类
来源：http://dali.yvedp.cn/Article/details/gtqngtyize.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtznvxgkhf.html

[T57] Scala：模式匹配
来源：http://dali.sxryk.cn/Article/details/gtokzodaou.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gttffrdagj.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtrnskjdws.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.andypj.xyz/Article/details/gtkncckwug.html

[T59] Scala：循环
来源：http://dali.pengpengdd.cyou/Article/details/gtoisxnyme.html

for (i <- 1 to 10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtddwcbduv.html

[T60] Scala：折叠
来源：http://dali.birdmap.top/Article/details/gtkceqripx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhixingplan.top/Article/details/gthcskgiyd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtzonqvldc.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtxwjdhjpg.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtksbbzbbb.html

[U01] Py：创建虚拟环境
来源：http://dali.aibaodan.cn/Article/details/gtmcfhrisg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gtgboxohtx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ywan-chungtsiang.top/Article/details/gteoqscdga.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtrinegaek.html

[U03] Py：加载 .env 配置
来源：http://dali.smart0.xyz/Article/details/gtsmabpufk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtjnragghh.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gtqlyaaklh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.svipenyu.cn/Article/details/gttjohhtof.html

[U05] Py：列表去重且保序
来源：http://dali.meibo888.top/Article/details/gtxrkeqxyn.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gtmbnrpklj.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gtdpcdxura.html

{**a, **b}
来源：http://dali.pengpengdd.cyou/Article/details/gtoasrjcyd.html

[U07] Py：反转字典键值
来源：http://dali.gogol.net.cn/Article/details/gteullgzfd.html

{v: k for k, v in d.items()}
来源：http://dali.shanyushiyangtech.top/Article/details/gtkciaeyab.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtmrmavajn.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtwngdorgp.html

[U09] Py：字典取最大值的键
来源：http://dali.dashuyun.cn/Article/details/gtyxixxelv.html

max(d, key=d.get)
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfrfszix.html

[U10] Py：按值排序字典
来源：http://dali.smart0.xyz/Article/details/gtkjvhsnem.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuxming.cn/Article/details/gtpfmpcgks.html

[U11] Py：生成器表达式
来源：http://dali.iojbl.cn/Article/details/gteqtngwwq.html

(x * 2 for x in arr)
来源：http://dali.tian-w.cn/Article/details/gtmuxygyyo.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtydbnadim.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gtcyipyonb.html

[U13] Py：固定长度队列
来源：http://dali.quarkkingdee.top/Article/details/gthusrisnv.html

deque(maxlen=10)
来源：http://dali.nwbrower.top/Article/details/gtuntillnf.html

[U14] Py：分组收集到列表
来源：http://dali.fengsongda.top/Article/details/gtpstmnjey.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtelepagoh.html

[U15] Py：高精度计时
来源：http://dali.yangfankeji.com/Article/details/gtavpozrnu.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtubvisuwd.html

[U16] Py：命令行参数解析
来源：http://dali.kuanghao11.cn/Article/details/gtrawwjjgk.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hfpthk.cn/Article/details/gtoaubrxbu.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtphmoecfu.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jyoumei.cn/Article/details/gttpvggpmz.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtlzapxryc.html

pat = re.compile(r"\d+")
来源：http://dali.xinyue.icu/Article/details/gtowsoiomb.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtxlvkiqcn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yueranfly.top/Article/details/gttqkubojy.html

[U20] Py：缓存函数结果
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpspcfsms.html

@functools.lru_cache(maxsize=None)
来源：http://dali.zhoulong.xyz/Article/details/gtzpuvzzfm.html

[U21] Py：自定义上下文管理器
来源：http://dali.xuanzx.com/Article/details/gtyrmbzhoh.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gttxxwqioe.html

[U22] Py：矩阵转置
来源：http://dali.wangshuangyany.cn/Article/details/gttonxbhqu.html

list(zip(*m))
来源：http://dali.zhengqikj.top/Article/details/gtguzookny.html

[U23] Py：分块读取大文件
来源：http://dali.andypj.xyz/Article/details/gtoraahnnb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.c1oappe.top/Article/details/gtrkcilkgj.html

[U24] Py：路径操作
来源：http://dali.yuanzhike.top/Article/details/gtdjdyaqgk.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtnxewinpg.html

[U25] Py：CSV 按字典读
来源：http://dali.dianchejie.cn/Article/details/gtobiybqkk.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gtcasjsdpf.html

[U26] Py：并发下载
来源：http://dali.hammf.cn/Article/details/gtbtptgefl.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yj202588.top/Article/details/gtksuqllol.html

[U27] Py：异步 HTTP
来源：http://dali.yj202588.top/Article/details/gtvgjcvhiw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.sufxvd.cn/Article/details/gtyaxafglg.html

[U28] Py：类型别名
来源：http://dali.zhengqikj.top/Article/details/gtmlxhlojn.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gtjucafxym.html

[U29] Py：属性校验
来源：http://dali.zhiwuduotai.top/Article/details/gtjbbattdp.html

@property 与 @x.setter 配合
来源：http://dali.zhongyouzk.top/Article/details/gtftidcebh.html

[U30] Py：数据类
来源：http://dali.tianlin.xyz/Article/details/gtgrageqwa.html

@dataclass(slots=True)
来源：http://dali.sweek.top/Article/details/gtmmsikygy.html

[U31] Py：单测
来源：http://dali.yueranfly.top/Article/details/gtdzzyrvfo.html

python -m pytest -q
来源：http://dali.yanxiufei.cn/Article/details/gtzagwdpkp.html

[U32] Py：代码格式化
来源：http://dali.hnxiangtu.top/Article/details/gtsnvswjhy.html

ruff format . && ruff check --fix .
来源：http://dali.tanke756.top/Article/details/gtbjikrcho.html

[U33] Py：打包发布
来源：http://dali.jianghu66.top/Article/details/gtkkgbzitr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.jqgfzy.top/Article/details/gtbrwlavzz.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gtcukmypzl.html

chardet.detect(raw)
来源：http://dali.daria6918.cn/Article/details/gtzrwnhwpt.html

[U35] Py：发送邮件
来源：http://dali.jinqigufen.top/Article/details/gtofbjvzck.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jqgfzy.top/Article/details/gtefarfnwo.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gtdrslimgg.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtoewrqoal.html

[U37] Py：读写 Excel
来源：http://dali.hnqzz.top/Article/details/gtcrcyfxql.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.9152youxi.cn/Article/details/gtjnzzhcnr.html

[U38] Py：获取脚本所在目录
来源：http://dali.redwolf501.top/Article/details/gtcbopddaa.html

Path(__file__).resolve().parent
来源：http://dali.zhixingplan.top/Article/details/gtfdutniez.html

[U39] Py：判断是否在交互环境
来源：http://dali.cqqwz.cn/Article/details/gtmgyeweby.html

sys.stdout.isatty()
来源：http://dali.ppjwa.cn/Article/details/gtnbjgpoqw.html

[U40] Py：打印到标准错误
来源：http://dali.birdmap.top/Article/details/gtqkvcwapo.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gthbkrmaiu.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.sufxvd.cn/Article/details/gtwjocwkfn.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gtfxvoudfq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gtdhlvyrbh.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhongyouzk.top/Article/details/gtpeiilnht.html

[U43] PHP：声明命名空间
来源：http://dali.hfpthk.cn/Article/details/gtxqsyphbi.html

namespace App\Http;
来源：http://dali.dianchejie.cn/Article/details/gtyylmyvan.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtyjerzket.html

declare(strict_types=1);
来源：http://dali.fengsongda.top/Article/details/gtakvguajr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtdrbojxzy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtwasmupkc.html

[U46] PHP：可空类型
来源：http://dali.cdnleiting.top/Article/details/gtrnvbhuyq.html

?string $name = null
来源：http://dali.bjfxy.top/Article/details/gtuvdusimj.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gtwxvwzokl.html

int|string $id
来源：http://dali.svipenyu.cn/Article/details/gtnthuhwfc.html

[U48] PHP：纯枚举
来源：http://dali.vqdsnc.cn/Article/details/gtkooxakjz.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gtibezaeft.html

[U49] PHP：只读属性
来源：http://dali.guowangkeji.top/Article/details/gthuqbpvfe.html

public readonly string $name
来源：http://dali.zhijiandao.cn/Article/details/gtdzcwibet.html

[U50] PHP：构造器属性提升
来源：http://dali.tanke756.top/Article/details/gttgqnkkae.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtcjdibnjp.html

[U51] PHP：数组解构
来源：http://dali.zhijiandao.cn/Article/details/gtjfukgswz.html

[$a, $b] = $arr;
来源：http://dali.pengpengdd.cyou/Article/details/gteywnwkco.html

[U52] PHP：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gteuvllyuz.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtaytriota.html

[U53] PHP：空合并运算符
来源：http://dali.redwolf501.top/Article/details/gtoeschvnl.html

$v = $a ?? $b ?? "default";
来源：http://dali.yangfankeji.com/Article/details/gtnfvhzlpo.html

[U54] PHP：空安全调用
来源：http://dali.zycfv.cn/Article/details/gtjizymwsp.html

$obj?->method()
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzynyfwg.html

[U55] PHP：match 表达式
来源：http://dali.yj202588.top/Article/details/gtlszjqtjl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtattwahpp.html

[U56] PHP：命名参数
来源：http://dali.haohaochexian.top/Article/details/gtmybhtsky.html

f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtquhkgwvl.html

[U57] PHP：字符串插值
来源：http://dali.0kj1m.cn/Article/details/gtykmsrjdx.html

"值: {$a}"
来源：http://dali.yuxming.cn/Article/details/gttfdaimmz.html

[U58] PHP：数组三件套
来源：http://dali.sysykeji.top/Article/details/gtobcmylrd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ehwqpu.com/Article/details/gtxtsneltd.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtkeyhgmbm.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.iojbl.cn/Article/details/gtmfimtgsy.html

[U60] PHP：JSON 编解码
来源：http://dali.shanyushiyangtech.top/Article/details/gttlpdobcy.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.ehwqpu.com/Article/details/gtupkmbdng.html

[U61] PHP：正则
来源：http://dali.shzxlz.cn/Article/details/gtntsvmlaz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenjidiqi.icu/Article/details/gtsrbvlane.html

[U62] PHP：日期对象
来源：http://dali.sweek.top/Article/details/gtuavnvixv.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.tianlin.xyz/Article/details/gtbpzwrovm.html

[U63] PHP：文件读写
来源：http://dali.yuxming.cn/Article/details/gtdvgnnnoj.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.snrcjt.cn/Article/details/gtpfbwyrkm.html

[U64] PHP：目录遍历
来源：http://dali.meibo888.top/Article/details/gtqezaxepu.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuanzx.com/Article/details/gtfqrurlsd.html

[U65] PHP：会话
来源：http://dali.guannengcc.top/Article/details/gtnbfzneqe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yonumen.top/Article/details/gtmvmqedbo.html

[U66] PHP：设置 Cookie
来源：http://dali.hnxiangtu.top/Article/details/gthftpnoam.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.chenzaomai.com/Article/details/gtbolmeeoz.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gtsjyewkml.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.wangdashe.top/Article/details/gtidbmmkpi.html

[U68] PHP：PDO 连接
来源：http://dali.ybcxt.top/Article/details/gteknqedhk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.xinyue.icu/Article/details/gtnxruzfgh.html

[U69] PHP：PDO 预处理
来源：http://dali.jyoumei.cn/Article/details/gtmewpxese.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.nanxuanxn.top/Article/details/gtscpcvnni.html

[U70] PHP：PDO 事务
来源：http://dali.cucudq.cn/Article/details/gtcvpjamjh.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuxming.cn/Article/details/gtipdrudgw.html

[U71] PHP：抛出异常
来源：http://dali.andypj.xyz/Article/details/gtkijqrbsw.html

throw new RuntimeException("失败", 500);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwskfcyc.html

[U72] PHP：写错误日志
来源：http://dali.yuanzhike.top/Article/details/gtmflwiipt.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtlllbybzq.html

[U73] PHP：读取 ini 配置
来源：http://dali.guowangkeji.top/Article/details/gtguaxfncx.html

parse_ini_file("config.ini", true)
来源：http://dali.sxryk.cn/Article/details/gtqgnobgzh.html

[U74] PHP：读取环境变量
来源：http://dali.svipenyu.cn/Article/details/gtkgnzhwni.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gttyzredga.html

[U75] PHP：依赖注入
来源：http://dali.ppjwa.cn/Article/details/gtwmwzuokv.html

composer require psr/container
来源：http://dali.jinqigufen.top/Article/details/gtsiwkoaqt.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gtdlvniwgz.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhixingplan.top/Article/details/gtnghanelf.html

[U77] PHP：模板渲染
来源：http://dali.xuetiantiany.cn/Article/details/gtqxwbmipg.html

composer require twig/twig
来源：http://dali.yonumen.top/Article/details/gtnhjatfcp.html

[U78] PHP：单元测试
来源：http://dali.yvedp.cn/Article/details/gtlrgcdjqz.html

composer require --dev phpunit/phpunit
来源：http://dali.xuetiantiany.cn/Article/details/gtseabpear.html

[U79] PHP：静态分析
来源：http://dali.feifeiyinyue.top/Article/details/gtkgylysvp.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gtxcmoifrw.html

[U80] PHP：代码规范修复
来源：http://dali.wangshuangyany.cn/Article/details/gtmmouqiaz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gaohongyu789.top/Article/details/gtynwnnmaw.html

[U81] JS：初始化项目
来源：http://dali.quarkkingdee.top/Article/details/gtgonlejoa.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gtjoeiapxq.html

[U82] JS：package.json 脚本
来源：http://dali.iojbl.cn/Article/details/gtnqusubrc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.feifeiyinyue.top/Article/details/gtgyslrghf.html

[U83] JS：ES Module 导入导出
来源：http://dali.yj202588.top/Article/details/gtacxnzkuc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtbvvobazn.html

[U84] JS：CommonJS 写法
来源：http://dali.ppjwa.cn/Article/details/gtrisfrxjx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gttjquhlmq.html

[U85] JS：可选链
来源：http://dali.hongshengwenyu.top/Article/details/gttujovfmr.html

a?.b?.c
来源：http://dali.gaohongyu789.top/Article/details/gtlwwsfmun.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gtlkxnnudl.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gtwwcapofy.html

[U87] JS：解构默认值
来源：http://dali.dashuyun.cn/Article/details/gtygnpzehk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jqgufenzy.top/Article/details/gtjnlyuzju.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtofgfjkrn.html

{ ...a, ...b }
来源：http://dali.kuanghao11.cn/Article/details/gtetjfxghw.html

[U89] JS：数组去重
来源：http://dali.yj202588.top/Article/details/gtfxdaxwhj.html

[...new Set(arr)]
来源：http://dali.fzhhl.top/Article/details/gtwwqawpir.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gtpgjkkpax.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtizpxfxtf.html

[U91] JS：对象键值遍历
来源：http://dali.9152youxi.cn/Article/details/gtoyycrbfq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gtrbhhiozu.html

[U92] JS：深拷贝
来源：http://dali.guannengcc.top/Article/details/gtmmnkouxb.html

structuredClone(obj)
来源：http://dali.cdnleiting.top/Article/details/gttlmsrfzh.html

[U93] JS：模板字符串
来源：http://dali.birdmap.top/Article/details/gtqjqbwflo.html

`共 ${n} 条`
来源：http://dali.c1oappe.top/Article/details/gttwnjglzb.html

[U94] JS：箭头函数
来源：http://dali.zhengqikj.top/Article/details/gtjddslxdz.html

const double = x => x * 2;
来源：http://dali.sufxvd.cn/Article/details/gtkywqjepi.html

[U95] JS：Promise 包装
来源：http://dali.zhijiandao.cn/Article/details/gtgymhcpqy.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gtlujpzrwm.html

[U96] JS：async/await 与异常
来源：http://dali.birdmap.top/Article/details/gtafycqlag.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.c1oappe.top/Article/details/gtmxnkxlup.html

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gtmujtpomf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.zhongyouzk.top/Article/details/gtbnwpwwou.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtwamtjkpk.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.redwolf501.top/Article/details/gtmwxvtsuc.html

[U99] JS：事件监听
来源：http://dali.zhoulong.xyz/Article/details/gttptnlfea.html

el.addEventListener("click", e => {})
来源：http://dali.shangyingyoupin.top/Article/details/gtnyxnbzby.html

[U100] JS：DOM 查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhufjeiy.html

document.querySelector(".item")
来源：http://dali.fengsongda.top/Article/details/gtcouxbmpz.html

[U101] JS：classList 操作
来源：http://dali.gzhubu.top/Article/details/gtlbkhlhrg.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtvwyjktrd.html

[U102] JS：本地存储
来源：http://dali.zycfv.cn/Article/details/gtioabyopn.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yanxiufei.cn/Article/details/gtkymmqetf.html

[U103] JS：定时器
来源：http://dali.zhongyouzk.top/Article/details/gtlnsncfvn.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.hfpthk.cn/Article/details/gtlnihbjqb.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtlezqkuja.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtzvbbijmk.html

[U105] JS：节流
来源：http://dali.xuetiantiany.cn/Article/details/gtkhqczycu.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxuanxn.top/Article/details/gtcwjblosa.html

[U106] JS：日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtqbkqgion.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtywgddngy.html

[U107] JS：数字千分位
来源：http://dali.cqqwz.cn/Article/details/gtmytseylw.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xuetiantiany.cn/Article/details/gtgjqvdfyw.html

[U108] JS：随机整数
来源：http://dali.svipenyu.cn/Article/details/gtzkpqwikn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhijiandao.cn/Article/details/gtimqstxem.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtnqsomtfg.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgwmysjtk.html

[U110] JS：数组分块
来源：http://dali.nwbrower.top/Article/details/gtcgpgevhr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.meibo888.top/Article/details/gtdivajzoq.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtcwrsjjoa.html

new Map(Object.entries(obj))
来源：http://dali.cashguo.top/Article/details/gtsnmyebua.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtybmykywe.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtnfssqbgf.html

[U113] JS：正则替换全部
来源：http://dali.mhx1999.top/Article/details/gtztriusku.html

s.replaceAll("a", "b")
来源：http://dali.shangyingyoupin.top/Article/details/gtwxhixqen.html

[U114] JS：JSON 深比较
来源：http://dali.yongpay.top/Article/details/gtrjxuboaf.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gtxrjhswoj.html

[U115] JS：生成 UUID
来源：http://dali.chenzaomai.com/Article/details/gtjqzyixej.html

crypto.randomUUID()
来源：http://dali.yuxming.cn/Article/details/gtbincuzgf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtejilejmh.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gtkeokaixm.html

[U117] JS：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtfhdbeugn.html

npm i -D vitest;  npx vitest
来源：http://dali.gzhubu.top/Article/details/gtzpsvjadk.html

[U118] JS：开发服务器
来源：http://dali.chenlongwang.top/Article/details/gtlytqnydb.html

npm i -D vite;  npx vite
来源：http://dali.zhixingplan.top/Article/details/gtadrcoujr.html

[U119] JS：生产构建
来源：http://dali.ydzc1.top/Article/details/gtqlykddwz.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gtiewboycj.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj202588.top/Article/details/gtlerwurov.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gtqyoclcee.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtnwhzutqx.html

统计汇总
来源：http://dali.gzhubu.top/Article/details/gtjwpyfpdp.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtfzioqsom.html

按语言统计（条）：
来源：http://dali.zdqjudy.top/Article/details/gtnfwvskom.html

Python ......... 252
来源：http://dali.zycfv.cn/Article/details/gtvwkrvsun.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gtzgptewbk.html

JavaScript ..... 252
来源：http://dali.yonumen.top/Article/details/gtujdyqugh.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtjppcxwmj.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiorybtfl.html

Go ............. 212
来源：http://dali.yangfankeji.com/Article/details/gtmmilbndj.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtzuagcpti.html

C# ............. 212
来源：http://dali.andypj.xyz/Article/details/gtwbcrrgtt.html

C .............. 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtippgsdxt.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gttzroyaqt.html

SQL ............ 90
来源：http://dali.mhx1999.top/Article/details/gtbheutveq.html

Bash ........... 80
来源：http://dali.zhiwuduotai.top/Article/details/gtoelhzhgr.html

Kotlin ......... 15
来源：http://dali.guowangkeji.top/Article/details/gtuwfentka.html

Swift .......... 15
来源：http://dali.iojbl.cn/Article/details/gtvavfbgvn.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gtyhqdvlaa.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtqyaoehda.html

Scala .......... 10
来源：http://dali.tianlin.xyz/Article/details/gtaambviay.html

------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtvzedfhix.html

合计 ........... 2106 条
来源：http://dali.hammf.cn/Article/details/gtmociliuy.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gtoxjyvvkn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gtwngqwfcm.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtnzsyimia.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtchycsskq.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtxzylqgff.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtststzikz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.sysykeji.top/Article/details/gtxoohmrtq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gtqskuoqzl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.daria6918.cn/Article/details/gtfvhvfqul.html


<!-- 参考信息 -->