代发 wailian999

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtuzsmhfwt.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtaukhdizd.html

println("Hello")
来源：http://dali.iojbl.cn/Article/details/gtqxbpvwqb.html

[T52] Scala：变量
来源：http://dali.jinqigufen.top/Article/details/gtorjgdmbp.html

val a = 1;  var b = 2
来源：http://dali.tanke756.top/Article/details/gtebzrfclj.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtxzkjgxnr.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtjuecncto.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtkeonmral.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.9152youxi.cn/Article/details/gttzxozpqt.html

[T55] Scala：集合过滤
来源：http://dali.yonumen.top/Article/details/gtahboafbl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xuetiantiany.cn/Article/details/gtwoozpdmm.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gtflcymxaf.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtzhvtwlax.html

[T57] Scala：模式匹配
来源：http://dali.hfpthk.cn/Article/details/gtbfjdqqur.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtdpfapukv.html

[T58] Scala：函数定义
来源：http://dali.c1oappe.top/Article/details/gtsjkwzlhg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yuanzhike.top/Article/details/gtoatseyal.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gttdsjuycn.html

for (i <- 1 to 10) println(i)
来源：http://dali.guannengcc.top/Article/details/gtmdhickgv.html

[T60] Scala：折叠
来源：http://dali.0kj1m.cn/Article/details/gtdygsslvb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtsutbujnw.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtordzpkxw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.daxiang520.top/Article/details/gtjvqqaoqt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtqtirvkuz.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtfacwxxbo.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhiwuduotai.top/Article/details/gtsxasbaoc.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtolksovkk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ybcxt.top/Article/details/gtxqgjwirj.html

[U03] Py：加载 .env 配置
来源：http://dali.svipenyu.cn/Article/details/gtnllswdcc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hnxiangtu.top/Article/details/gtdegbwtam.html

[U04] Py：变量调试打印
来源：http://dali.yonumen.top/Article/details/gtmrninofo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gtbthjxwao.html

[U05] Py：列表去重且保序
来源：http://dali.svipenyu.cn/Article/details/gtfvipkpap.html

list(dict.fromkeys(arr))
来源：http://dali.zhiwuduotai.top/Article/details/gtgnfkjkze.html

[U06] Py：合并两个字典
来源：http://dali.hywenlv.cn/Article/details/gtclmcrygt.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtbiqkvonw.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtszgwujpf.html

{v: k for k, v in d.items()}
来源：http://dali.nwbrower.top/Article/details/gtvhmdzlzh.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtadwvbvbx.html

[y for x in nested for y in x]
来源：http://dali.sysykeji.top/Article/details/gtbdzwrvzs.html

[U09] Py：字典取最大值的键
来源：http://dali.jinqigfzy.top/Article/details/gtjktdlwrb.html

max(d, key=d.get)
来源：http://dali.shanyushiyangtech.top/Article/details/gtuignpydg.html

[U10] Py：按值排序字典
来源：http://dali.fengsongda.top/Article/details/gtkbdkulrd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gthcohvyrg.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtbuhdgsoy.html

(x * 2 for x in arr)
来源：http://dali.316326.xyz/Article/details/gtwlkzxtne.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtznyehvun.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtjzddzidn.html

[U13] Py：固定长度队列
来源：http://dali.hysaishi.cn/Article/details/gtoyqrnmka.html

deque(maxlen=10)
来源：http://dali.guowangkeji.top/Article/details/gtaldvuwzb.html

[U14] Py：分组收集到列表
来源：http://dali.zhiwuduotai.top/Article/details/gttsbfckve.html

defaultdict(list)
来源：http://dali.zhongyouzk.top/Article/details/gtmfszvxja.html

[U15] Py：高精度计时
来源：http://dali.zhengqikj.top/Article/details/gteefiiumc.html

t = time.perf_counter()
来源：http://dali.quarkkingdee.top/Article/details/gtsbmcyivf.html

[U16] Py：命令行参数解析
来源：http://dali.yuanzhike.top/Article/details/gtyqgtuymt.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.havefunace.top/Article/details/gtdakshhmb.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtvagfijcl.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.pengpengdd.cyou/Article/details/gtzuargyjv.html

[U18] Py：预编译正则
来源：http://dali.0kj1m.cn/Article/details/gtllnmugtn.html

pat = re.compile(r"\d+")
来源：http://dali.shangyingyoupin.top/Article/details/gtdzsttnic.html

[U19] Py：正则替换带回调
来源：http://dali.jqgfzy.top/Article/details/gtssrkqfmh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gtxvdnkiqq.html

[U20] Py：缓存函数结果
来源：http://dali.sxryk.cn/Article/details/gtsyjhopoh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigufen.top/Article/details/gtzzjlbaee.html

[U21] Py：自定义上下文管理器
来源：http://dali.bjfxy.top/Article/details/gtmfgbywoo.html

@contextlib.contextmanager
来源：http://dali.andypj.xyz/Article/details/gtcwxkntky.html

[U22] Py：矩阵转置
来源：http://dali.daria6918.cn/Article/details/gtrhrzvznj.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gteljxkbvx.html

[U23] Py：分块读取大文件
来源：http://dali.daxiang520.top/Article/details/gtcewxzeho.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.redwolf501.top/Article/details/gticbphvro.html

[U24] Py：路径操作
来源：http://dali.guannengcc.top/Article/details/gtquadsgdb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cqqwz.cn/Article/details/gtdbejsaih.html

[U25] Py：CSV 按字典读
来源：http://dali.xylfe.cn/Article/details/gtygwxtxrl.html

csv.DictReader(f)
来源：http://dali.zhongyouzk.top/Article/details/gtozqpunnz.html

[U26] Py：并发下载
来源：http://dali.zhengqikj.top/Article/details/gtmzzlhgbv.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.jinqigufen.top/Article/details/gtlclpgajw.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gtyejgyxrf.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.kuanghao11.cn/Article/details/gtanekpszx.html

[U28] Py：类型别名
来源：http://dali.jqgufenzy.top/Article/details/gtlcgwbbam.html

UserId = int
来源：http://dali.smart0.xyz/Article/details/gttglomxps.html

[U29] Py：属性校验
来源：http://dali.0kj1m.cn/Article/details/gtlzdatget.html

@property 与 @x.setter 配合
来源：http://dali.zdqjudy.top/Article/details/gtdfgcfvsw.html

[U30] Py：数据类
来源：http://dali.feifeiyinyue.top/Article/details/gtltmymblc.html

@dataclass(slots=True)
来源：http://dali.nwbrower.top/Article/details/gtanvhmyxc.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gtubolmaor.html

python -m pytest -q
来源：http://dali.shzxlz.cn/Article/details/gtpzkoegwz.html

[U32] Py：代码格式化
来源：http://dali.jqgfzy.top/Article/details/gthjjlgcrb.html

ruff format . && ruff check --fix .
来源：http://dali.sufxvd.cn/Article/details/gtwrvxgmbi.html

[U33] Py：打包发布
来源：http://dali.jlsjyb.cn/Article/details/gtqxzbaqly.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhijiandao.cn/Article/details/gtyrsgzmis.html

[U34] Py：判断编码
来源：http://dali.jiagoushi.top/Article/details/gtkmpiadtb.html

chardet.detect(raw)
来源：http://dali.sweek.top/Article/details/gttosgwkpx.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gtifajttcj.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.nanxinkj.top/Article/details/gtciekbhjm.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtwdysvllh.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenjidiqi.icu/Article/details/gtctvhgoyl.html

[U37] Py：读写 Excel
来源：http://dali.yuxming.cn/Article/details/gtfdgmqzfw.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.hywenlv.cn/Article/details/gterkemfgv.html

[U38] Py：获取脚本所在目录
来源：http://dali.hongshengwenyu.top/Article/details/gtfxunohyn.html

Path(__file__).resolve().parent
来源：http://dali.jqgfzy.top/Article/details/gtsrzayqzj.html

[U39] Py：判断是否在交互环境
来源：http://dali.cucudq.cn/Article/details/gtttiadaed.html

sys.stdout.isatty()
来源：http://dali.fengsongda.top/Article/details/gtirleyorb.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtprmafwgx.html

print("err", file=sys.stderr)
来源：http://dali.jinqigfzy.top/Article/details/gtnmgouldy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.iojbl.cn/Article/details/gtweygfagx.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yonumen.top/Article/details/gtyfenyrvy.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yonumen.top/Article/details/gtuvsivgiv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.c1oappe.top/Article/details/gtksmzrlkx.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gtstzscjop.html

namespace App\Http;
来源：http://dali.jlsjyb.cn/Article/details/gtnjvewoms.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gtnqzlfmvs.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtjqahehen.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shzxlz.cn/Article/details/gtwheqkwci.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkahnnuff.html

[U46] PHP：可空类型
来源：http://dali.yueranfly.top/Article/details/gtyhnryoxd.html

?string $name = null
来源：http://dali.nwbrower.top/Article/details/gtqkmslelh.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gtiyphyeja.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtttbfvupp.html

[U48] PHP：纯枚举
来源：http://dali.hywenlv.cn/Article/details/gtdqpvrlsw.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtgrcplugv.html

[U49] PHP：只读属性
来源：http://dali.nanxuanxn.top/Article/details/gtdzhejzka.html

public readonly string $name
来源：http://dali.sufxvd.cn/Article/details/gtcsxukjtv.html

[U50] PHP：构造器属性提升
来源：http://dali.ydzc1.top/Article/details/gtanvdhqjs.html

public function __construct(private int $id) {}
来源：http://dali.9152youxi.cn/Article/details/gtybvjmuww.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtcerjjkgn.html

[$a, $b] = $arr;
来源：http://dali.zhongyouzk.top/Article/details/gtwzpicvma.html

[U52] PHP：箭头函数
来源：http://dali.cucudq.cn/Article/details/gtxviwcydv.html

$double = fn($x) => $x * 2;
来源：http://dali.jianghu66.top/Article/details/gtfkyfkkxb.html

[U53] PHP：空合并运算符
来源：http://dali.meibo888.top/Article/details/gtyqnblvjg.html

$v = $a ?? $b ?? "default";
来源：http://dali.9152youxi.cn/Article/details/gtmlvqodph.html

[U54] PHP：空安全调用
来源：http://dali.shanyushiyangtech.top/Article/details/gtxllxehed.html

$obj?->method()
来源：http://dali.sxryk.cn/Article/details/gtraxgutkr.html

[U55] PHP：match 表达式
来源：http://dali.guowangkeji.top/Article/details/gthpriyjzg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtduvcdrff.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gtgzlfmdyg.html

f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtzdusmbhv.html

[U57] PHP：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtjbwprzsx.html

"值: {$a}"
来源：http://dali.andypj.xyz/Article/details/gtoxixyzsc.html

[U58] PHP：数组三件套
来源：http://dali.cqqwz.cn/Article/details/gtnazjuzpf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.andypj.xyz/Article/details/gtfnjppeif.html

[U59] PHP：自定义排序
来源：http://dali.zhoulong.xyz/Article/details/gtfvmytfjj.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.birdmap.top/Article/details/gtnnmicfxv.html

[U60] PHP：JSON 编解码
来源：http://dali.pycfn.com/Article/details/gtkmllofoe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gtrxfatgen.html

[U61] PHP：正则
来源：http://dali.fengsongda.top/Article/details/gtrhioqnik.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtclbtvzqk.html

[U62] PHP：日期对象
来源：http://dali.9152youxi.cn/Article/details/gtyyepfqmo.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.guannengcc.top/Article/details/gtfbyntrgd.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtxkvpnxmq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sysykeji.top/Article/details/gttmjqvyfc.html

[U64] PHP：目录遍历
来源：http://dali.hfpthk.cn/Article/details/gtqjqlwfll.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.nwbrower.top/Article/details/gtzmcvctfs.html

[U65] PHP：会话
来源：http://dali.daxiang520.top/Article/details/gtunvtcylf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yueranfly.top/Article/details/gtycxigqrs.html

[U66] PHP：设置 Cookie
来源：http://dali.hnqzz.top/Article/details/gtjvrvmfmm.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeejxtut.html

[U67] PHP：处理文件上传
来源：http://dali.cucudq.cn/Article/details/gtdcpanznl.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cdnleiting.top/Article/details/gtkwnmlgdt.html

[U68] PHP：PDO 连接
来源：http://dali.shanyushiyangtech.top/Article/details/gthwnepowj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hnxiangtu.top/Article/details/gtssfwyvdl.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gtfhcztmas.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbdfrfjor.html

[U70] PHP：PDO 事务
来源：http://dali.nwbrower.top/Article/details/gtaqzevvme.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258888.top/Article/details/gtojmrydpy.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gthwjbjmlg.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgfzy.top/Article/details/gtnguvmadu.html

[U72] PHP：写错误日志
来源：http://dali.yj202588.top/Article/details/gtirqghxgd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shanyushiyangkeji.top/Article/details/gteitcxqxw.html

[U73] PHP：读取 ini 配置
来源：http://dali.guannengcc.top/Article/details/gtdknqzzvc.html

parse_ini_file("config.ini", true)
来源：http://dali.ivvv.top/Article/details/gtusplffim.html

[U74] PHP：读取环境变量
来源：http://dali.chenlongwang.top/Article/details/gtywhzkxfr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.ivvv.top/Article/details/gtnsbewnfe.html

[U75] PHP：依赖注入
来源：http://dali.smart0.xyz/Article/details/gteuuewodn.html

composer require psr/container
来源：http://dali.yanxiufei.cn/Article/details/gtjwaeaqzy.html

[U76] PHP：简单路由
来源：http://dali.ivvv.top/Article/details/gtftnclwhx.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.gogol.net.cn/Article/details/gtvtksflvq.html

[U77] PHP：模板渲染
来源：http://dali.nanxinkj.top/Article/details/gtlfcyrahv.html

composer require twig/twig
来源：http://dali.hnqzz.top/Article/details/gtguitnhky.html

[U78] PHP：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtvmarepvo.html

composer require --dev phpunit/phpunit
来源：http://dali.316326.xyz/Article/details/gtpvqrxnak.html

[U79] PHP：静态分析
来源：http://dali.yangfankeji.com/Article/details/gthzsbrhuo.html

composer require --dev phpstan/phpstan
来源：http://dali.cucudq.cn/Article/details/gtgzpcrbyi.html

[U80] PHP：代码规范修复
来源：http://dali.gogol.net.cn/Article/details/gtittzntlw.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuxming.cn/Article/details/gtmiwesjkw.html

[U81] JS：初始化项目
来源：http://dali.smart0.xyz/Article/details/gtrvqqplzy.html

npm init -y;  npm i express
来源：http://dali.yangfankeji.com/Article/details/gtifbyuhfp.html

[U82] JS：package.json 脚本
来源：http://dali.yj202588.top/Article/details/gttroondoh.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.mhx1999.top/Article/details/gtligpceww.html

[U83] JS：ES Module 导入导出
来源：http://dali.shzxlz.cn/Article/details/gtxghcalax.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenzaomai.com/Article/details/gtxoqsnfkb.html

[U84] JS：CommonJS 写法
来源：http://dali.fzhhl.top/Article/details/gtjszgcgsd.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.meibo888.top/Article/details/gtkqrwabrf.html

[U85] JS：可选链
来源：http://dali.shanyushiyangkeji.top/Article/details/gtktygalnf.html

a?.b?.c
来源：http://dali.sxryk.cn/Article/details/gtximunjbu.html

[U86] JS：空值合并
来源：http://dali.feifeiyinyue.top/Article/details/gtggrkebrh.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gthvtpebtt.html

[U87] JS：解构默认值
来源：http://dali.jqgfzy.top/Article/details/gtcvcgoxme.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ydzc1.top/Article/details/gtrxfyujpc.html

[U88] JS：对象展开合并
来源：http://dali.shangyingyoupin.top/Article/details/gttcqjvgvw.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gttzyijsiq.html

[U89] JS：数组去重
来源：http://dali.snrcjt.cn/Article/details/gtcvvypjtq.html

[...new Set(arr)]
来源：http://dali.yj20258.top/Article/details/gtsltdyhij.html

[U90] JS：数字数组排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthcaafknf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zdqjudy.top/Article/details/gtyeuumcyk.html

[U91] JS：对象键值遍历
来源：http://dali.yuanzhike.top/Article/details/gtimgfrdcm.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.wangdashe.top/Article/details/gtakktrlin.html

[U92] JS：深拷贝
来源：http://dali.nwbrower.top/Article/details/gtrccqikim.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtohisnzwo.html

[U93] JS：模板字符串
来源：http://dali.jqgfzy.top/Article/details/gtsffwobol.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gtzqukobgo.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtktuhxjty.html

const double = x => x * 2;
来源：http://dali.yangfankeji.com/Article/details/gtvxkzahgm.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gtdpbhcocz.html

new Promise((resolve, reject) => {})
来源：http://dali.shzxlz.cn/Article/details/gtewkxpryj.html

[U96] JS：async/await 与异常
来源：http://dali.yanxiufei.cn/Article/details/gtrllebexm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yongpay.top/Article/details/gtprshqvfk.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gtggktposw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gtwlhrgkcj.html

[U98] JS：fetch 带 JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoqkfpbp.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtobpdkhba.html

[U99] JS：事件监听
来源：http://dali.pengpengdd.cyou/Article/details/gtvwcbqavs.html

el.addEventListener("click", e => {})
来源：http://dali.fengsongda.top/Article/details/gtfnnkxtzd.html

[U100] JS：DOM 查询
来源：http://dali.yvedp.cn/Article/details/gtgssqecyb.html

document.querySelector(".item")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkztjdhvr.html

[U101] JS：classList 操作
来源：http://dali.yonumen.top/Article/details/gtnojxmacq.html

el.classList.toggle("active")
来源：http://dali.cdnleiting.top/Article/details/gtpulwppgv.html

[U102] JS：本地存储
来源：http://dali.sufxvd.cn/Article/details/gtdflkrvwl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigfzy.top/Article/details/gtwrrjacqc.html

[U103] JS：定时器
来源：http://dali.jlsjyb.cn/Article/details/gtsyksnsip.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenlongwang.top/Article/details/gtwvrzulws.html

[U104] JS：防抖
来源：http://dali.daxiang520.top/Article/details/gtejzeyswc.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtqsxkdicy.html

[U105] JS：节流
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnppaidbs.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jyoumei.cn/Article/details/gtfuolwqhm.html

[U106] JS：日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtpdertxpn.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlwpxepoj.html

[U107] JS：数字千分位
来源：http://dali.gzhubu.top/Article/details/gtakydeqla.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cdnleiting.top/Article/details/gthkdapfiq.html

[U108] JS：随机整数
来源：http://dali.zhongyouzk.top/Article/details/gtmogvevdh.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shuidangran.top/Article/details/gtnemjymvb.html

[U109] JS：数组分组
来源：http://dali.jlsjyb.cn/Article/details/gtywwujjlk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtybfetgdh.html

[U110] JS：数组分块
来源：http://dali.0kj1m.cn/Article/details/gtohjgdfca.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.andypj.xyz/Article/details/gtwspiwgae.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtihyydtni.html

new Map(Object.entries(obj))
来源：http://dali.yvedp.cn/Article/details/gtgtmdrekc.html

[U112] JS：字符串补位
来源：http://dali.shuidangran.top/Article/details/gtnwhgqoli.html

"7".padStart(3, "0")
来源：http://dali.yuanzhike.top/Article/details/gtrdidhaix.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtnevphxcb.html

s.replaceAll("a", "b")
来源：http://dali.jqgufenzy.top/Article/details/gtqeceaikg.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtghdjhogy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hnqzz.top/Article/details/gtbsxvwsob.html

[U115] JS：生成 UUID
来源：http://dali.kuanghao11.cn/Article/details/gtgxdxfvmu.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjvjzrqn.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cqqwz.cn/Article/details/gtltvpekik.html

/** @param {string} name */ function f(name) {}
来源：http://dali.bjfxy.top/Article/details/gtqzqbnrtr.html

[U117] JS：单元测试
来源：http://dali.zhengqikj.top/Article/details/gtcwhniyhi.html

npm i -D vitest;  npx vitest
来源：http://dali.tian-w.cn/Article/details/gtkhpnxoge.html

[U118] JS：开发服务器
来源：http://dali.aizwys.cn/Article/details/gtzpenczws.html

npm i -D vite;  npx vite
来源：http://dali.316326.xyz/Article/details/gtxbykbpxh.html

[U119] JS：生产构建
来源：http://dali.yuxming.cn/Article/details/gtkcbkzceo.html

npx vite build
来源：http://dali.xinyue.icu/Article/details/gtsnxxeeey.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.c1oappe.top/Article/details/gtqruiovqr.html

import.meta.env.VITE_API_URL
来源：http://dali.xuanzx.com/Article/details/gtlztskhct.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtomvweqfu.html

统计汇总
来源：http://dali.gaohongyu789.top/Article/details/gtmmvdavkl.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbpvtsbam.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtbgheigbd.html

Python ......... 252
来源：http://dali.ydzc1.top/Article/details/gtiqlxbpdz.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gtbqtmywla.html

JavaScript ..... 252
来源：http://dali.snrcjt.cn/Article/details/gtqhcybodq.html

TypeScript ..... 212
来源：http://dali.jianghu66.top/Article/details/gtzecovdaa.html

Java ........... 212
来源：http://dali.zhiwuduotai.top/Article/details/gtxgdkufby.html

Go ............. 212
来源：http://dali.ehwqpu.com/Article/details/gtlmceugmv.html

Ruby ........... 212
来源：http://dali.chenzaomai.com/Article/details/gtqelkkbds.html

C# ............. 212
来源：http://dali.sxryk.cn/Article/details/gtstjfghhl.html

C .............. 30
来源：http://dali.chenzaomai.com/Article/details/gtevgffxdy.html

C++ ............ 30
来源：http://dali.sufxvd.cn/Article/details/gthjmunhko.html

SQL ............ 90
来源：http://dali.jlsjyb.cn/Article/details/gtpwgnoqkv.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtousmazdr.html

Kotlin ......... 15
来源：http://dali.tanke756.top/Article/details/gtjmkbqzfm.html

Swift .......... 15
来源：http://dali.yongpay.top/Article/details/gtwdozqgde.html

Lua ............ 10
来源：http://dali.tianlin.xyz/Article/details/gtjfftdtcu.html

Perl ........... 10
来源：http://dali.xziqi.cn/Article/details/gtsloxdcbv.html

Scala .......... 10
来源：http://dali.jqgufenzy.top/Article/details/gtacafojhv.html

------------------------------------
来源：http://dali.haohaochexian.top/Article/details/gtkotwnvle.html

合计 ........... 2106 条
来源：http://dali.jinqigufen.top/Article/details/gtmfcftlxn.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtppmxxosj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtwdynyxvr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.yvedp.cn/Article/details/gtrqhikqqs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ybcxt.top/Article/details/gtkmalcfto.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yj20258888.top/Article/details/gteyxysjux.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.daxiang520.top/Article/details/gtjkfkbxvi.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.snrcjt.cn/Article/details/gtjixibcmw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigufen.top/Article/details/gtkvfirxxp.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gtgbvfosuj.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtgrcongta.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmmecvts.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gtrjdfncxh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtcimlfxfz.html


<!-- 参考信息 -->