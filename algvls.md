代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.svipenyu.cn/Article/details/gtaetgvoen.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtzpnfnbqm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gtyksrjbll.html

[T56] Scala：样例类
来源：http://dali.hnxiangtu.top/Article/details/gtojpkunyd.html

case class User(name: String, age: Int)
来源：http://dali.cheryme.top/Article/details/gtdujotcvr.html

[T57] Scala：模式匹配
来源：http://dali.zhixingplan.top/Article/details/gtsuzusmou.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xinyue.icu/Article/details/gtzgosgcla.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtvysvashh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtgdtauega.html

[T59] Scala：循环
来源：http://dali.yongpay.top/Article/details/gtfjmkgoiy.html

for (i <- 1 to 10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtoxaldxix.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtdhszhhoe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.pengpengdd.cyou/Article/details/gtxsjoouns.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtrcluccwh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zycfv.cn/Article/details/gteuvsaybo.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtuvwpkqsy.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtzwibxgcy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxkuvbzrb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.chenzaomai.com/Article/details/gtwqgqnvzt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuxming.cn/Article/details/gtucjcooog.html

[U03] Py：加载 .env 配置
来源：http://dali.yuanzhike.top/Article/details/gtosrriqij.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yongpay.top/Article/details/gtrbdotanm.html

[U04] Py：变量调试打印
来源：http://dali.zdqjudy.top/Article/details/gtszqvmqvl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlenujgkn.html

[U05] Py：列表去重且保序
来源：http://dali.zhixingplan.top/Article/details/gtnqiodosv.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258888.top/Article/details/gtaownkejb.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtajwzexpv.html

{**a, **b}
来源：http://dali.zhoulong.xyz/Article/details/gtuvuqfjux.html

[U07] Py：反转字典键值
来源：http://dali.xinyue.icu/Article/details/gtmcscetua.html

{v: k for k, v in d.items()}
来源：http://dali.jqgufenzy.top/Article/details/gtnivmdktf.html

[U08] Py：展平二维列表
来源：http://dali.jiagoushi.top/Article/details/gtdlilddec.html

[y for x in nested for y in x]
来源：http://dali.shangyingyoupin.top/Article/details/gtcijpwnfm.html

[U09] Py：字典取最大值的键
来源：http://dali.dashuyun.cn/Article/details/gtxfxzlvpf.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtuoafnwxs.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtxicyvpdz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.kuanghao11.cn/Article/details/gtfybhlidp.html

[U11] Py：生成器表达式
来源：http://dali.zhijiandao.cn/Article/details/gtwqnjvwwv.html

(x * 2 for x in arr)
来源：http://dali.sysykeji.top/Article/details/gtpdztnjzn.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jlsjyb.cn/Article/details/gtdfsudpth.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfcvgxskc.html

[U13] Py：固定长度队列
来源：http://dali.feifeiyinyue.top/Article/details/gtvmerojdt.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gtvtvzpspt.html

[U14] Py：分组收集到列表
来源：http://dali.hammf.cn/Article/details/gtewyzkzju.html

defaultdict(list)
来源：http://dali.pycfn.com/Article/details/gtmkahorbb.html

[U15] Py：高精度计时
来源：http://dali.redwolf501.top/Article/details/gtoqtjbgud.html

t = time.perf_counter()
来源：http://dali.aizwys.cn/Article/details/gtfrcebqac.html

[U16] Py：命令行参数解析
来源：http://dali.9152youxi.cn/Article/details/gtvxgpuooz.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.gotoacloud.top/Article/details/gtwiwddgdb.html

[U17] Py：初始化日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacwfszfs.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.daria6918.cn/Article/details/gtjhjzgcze.html

[U18] Py：预编译正则
来源：http://dali.zhijiandao.cn/Article/details/gtgslsnzim.html

pat = re.compile(r"\d+")
来源：http://dali.tanke756.top/Article/details/gtixdkjgoh.html

[U19] Py：正则替换带回调
来源：http://dali.zhixingplan.top/Article/details/gtojadkaie.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhengqikj.top/Article/details/gtlvkpjzlp.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtkvxehraw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gaohongyu789.top/Article/details/gtsswhgngg.html

[U21] Py：自定义上下文管理器
来源：http://dali.ehwqpu.com/Article/details/gtieiskdgr.html

@contextlib.contextmanager
来源：http://dali.hnqzz.top/Article/details/gtldqhuwxw.html

[U22] Py：矩阵转置
来源：http://dali.guowangkeji.top/Article/details/gtdphqrutw.html

list(zip(*m))
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjaptaec.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtufunargl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhoulong.xyz/Article/details/gtaybmtzrx.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtjuyloizu.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.gogol.net.cn/Article/details/gtyctidpdj.html

[U25] Py：CSV 按字典读
来源：http://dali.wangdashe.top/Article/details/gtadqvmadm.html

csv.DictReader(f)
来源：http://dali.tianlin.xyz/Article/details/gtbxkmswzx.html

[U26] Py：并发下载
来源：http://dali.yangfankeji.com/Article/details/gtsrulctna.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.cdnleiting.top/Article/details/gtvxjnwdbl.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gthamqychw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenjidiqi.icu/Article/details/gtzyftansa.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gtrqtsgxeb.html

UserId = int
来源：http://dali.chenlongwang.top/Article/details/gttzfkzsys.html

[U29] Py：属性校验
来源：http://dali.shzxlz.cn/Article/details/gtkmklypve.html

@property 与 @x.setter 配合
来源：http://dali.hfpthk.cn/Article/details/gtszjicoqp.html

[U30] Py：数据类
来源：http://dali.aibaodan.cn/Article/details/gttfqwaabl.html

@dataclass(slots=True)
来源：http://dali.zhijiandao.cn/Article/details/gtbwlxezwf.html

[U31] Py：单测
来源：http://dali.yongpay.top/Article/details/gtgifviioc.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gtohblhgyd.html

[U32] Py：代码格式化
来源：http://dali.c1oappe.top/Article/details/gtyjyqfler.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gtmltagbij.html

[U33] Py：打包发布
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnzqdpivi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yuanzhike.top/Article/details/gtsnhxzwds.html

[U34] Py：判断编码
来源：http://dali.zhijiandao.cn/Article/details/gtkcongmnh.html

chardet.detect(raw)
来源：http://dali.hnqzz.top/Article/details/gtiggkgqav.html

[U35] Py：发送邮件
来源：http://dali.yonumen.top/Article/details/gtkeeooonv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.shuidangran.top/Article/details/gtvstzjwuk.html

[U36] Py：定时任务
来源：http://dali.svipenyu.cn/Article/details/gtgbrxihyc.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtpibtgarl.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gtwmjthbin.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.tanke756.top/Article/details/gtjyekwbdf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhengqikj.top/Article/details/gthjacrdja.html

Path(__file__).resolve().parent
来源：http://dali.gzhubu.top/Article/details/gtpmpfdmfp.html

[U39] Py：判断是否在交互环境
来源：http://dali.cheryme.top/Article/details/gtpcftljhj.html

sys.stdout.isatty()
来源：http://dali.yanxiufei.cn/Article/details/gtxazidroh.html

[U40] Py：打印到标准错误
来源：http://dali.zhengqikj.top/Article/details/gtjsjrcuym.html

print("err", file=sys.stderr)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgpqebiv.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.nanxuanxn.top/Article/details/gtxmkjhjtm.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhengqikj.top/Article/details/gtafqvxcqv.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jyoumei.cn/Article/details/gthxvxzqmx.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.0kj1m.cn/Article/details/gtaaoemqnj.html

[U43] PHP：声明命名空间
来源：http://dali.havefunace.top/Article/details/gtwvycnwgy.html

namespace App\Http;
来源：http://dali.zycfv.cn/Article/details/gtkbqarzes.html

[U44] PHP：开启严格类型
来源：http://dali.yonumen.top/Article/details/gteqncjnlv.html

declare(strict_types=1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjzqwzuv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtmwzotqbn.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtrqzxgnwb.html

[U46] PHP：可空类型
来源：http://dali.guannengcc.top/Article/details/gtiizmmjnf.html

?string $name = null
来源：http://dali.gaohongyu789.top/Article/details/gtsfgnvupb.html

[U47] PHP：联合类型
来源：http://dali.ppjwa.cn/Article/details/gttpzolskj.html

int|string $id
来源：http://dali.yj202588.top/Article/details/gttgwwwdnj.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gtiixgqbbn.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtlibqgimv.html

[U49] PHP：只读属性
来源：http://dali.jinqigufen.top/Article/details/gtwnjyinsk.html

public readonly string $name
来源：http://dali.hnqzz.top/Article/details/gtrrctrvbe.html

[U50] PHP：构造器属性提升
来源：http://dali.gogol.net.cn/Article/details/gtfwflhgrt.html

public function __construct(private int $id) {}
来源：http://dali.yongpay.top/Article/details/gttrxvwssp.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtzalxyxdm.html

[$a, $b] = $arr;
来源：http://dali.gogol.net.cn/Article/details/gtaxupzeji.html

[U52] PHP：箭头函数
来源：http://dali.yongpay.top/Article/details/gtuebkcwqq.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gtexdaeghp.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gtfkgucjrk.html

$v = $a ?? $b ?? "default";
来源：http://dali.yongpay.top/Article/details/gtkqqcofoh.html

[U54] PHP：空安全调用
来源：http://dali.nwbrower.top/Article/details/gtqaduzaqp.html

$obj?->method()
来源：http://dali.yuanzhike.top/Article/details/gtctvgufmk.html

[U55] PHP：match 表达式
来源：http://dali.meibo888.top/Article/details/gtiljgfiro.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtqyzhmicv.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtpkumargj.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtzsjmbwfz.html

[U57] PHP：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtmjmjhusy.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gttojarjfl.html

[U58] PHP：数组三件套
来源：http://dali.smart0.xyz/Article/details/gttjmzbcrn.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtriigbpvd.html

[U59] PHP：自定义排序
来源：http://dali.iojbl.cn/Article/details/gtugggvglb.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gtvqacusdg.html

[U60] PHP：JSON 编解码
来源：http://dali.cucudq.cn/Article/details/gtazeydsia.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jyoumei.cn/Article/details/gtfmcyttht.html

[U61] PHP：正则
来源：http://dali.ppjwa.cn/Article/details/gtfxjcprbk.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ivvv.top/Article/details/gtilduawcl.html

[U62] PHP：日期对象
来源：http://dali.shangyingyoupin.top/Article/details/gtfalehmfu.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gtejrnjtim.html

[U63] PHP：文件读写
来源：http://dali.haohaochexian.top/Article/details/gtpsbgcnfk.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gttwklxiwc.html

[U64] PHP：目录遍历
来源：http://dali.tanke756.top/Article/details/gtruxbcqms.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gtutsjciag.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gtcazifegl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.daxiang520.top/Article/details/gtuynvvkqz.html

[U66] PHP：设置 Cookie
来源：http://dali.hywenlv.cn/Article/details/gtciufdmug.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tanke756.top/Article/details/gtlogcmeia.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtdjmddvaz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj20258888.top/Article/details/gtmzeduxxp.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gtysoveepy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ybcxt.top/Article/details/gtrwvfmklu.html

[U69] PHP：PDO 预处理
来源：http://dali.zhiwuduotai.top/Article/details/gtdlhcpodr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xylfe.cn/Article/details/gtiyzrekcs.html

[U70] PHP：PDO 事务
来源：http://dali.hywenlv.cn/Article/details/gtgwqqysvg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gtpmagntpv.html

[U71] PHP：抛出异常
来源：http://dali.guannengcc.top/Article/details/gticrndtcb.html

throw new RuntimeException("失败", 500);
来源：http://dali.zhijiandao.cn/Article/details/gtooyqywvf.html

[U72] PHP：写错误日志
来源：http://dali.jqgfzy.top/Article/details/gtlnsxspyb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.chenjidiqi.icu/Article/details/gtlrgvgrbd.html

[U73] PHP：读取 ini 配置
来源：http://dali.zhoulong.xyz/Article/details/gtmnnnisvu.html

parse_ini_file("config.ini", true)
来源：http://dali.cheryme.top/Article/details/gtizdvrvij.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gtgjfvmqdz.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yvedp.cn/Article/details/gtmowccmmt.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtceeusiyz.html

composer require psr/container
来源：http://dali.svipenyu.cn/Article/details/gtfuzrebis.html

[U76] PHP：简单路由
来源：http://dali.zhiwuduotai.top/Article/details/gtlhrbqwyh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shanyushiyangtech.top/Article/details/gtngxkaavh.html

[U77] PHP：模板渲染
来源：http://dali.svipenyu.cn/Article/details/gtljnzyatp.html

composer require twig/twig
来源：http://dali.shuidangran.top/Article/details/gtshchkgib.html

[U78] PHP：单元测试
来源：http://dali.yuxming.cn/Article/details/gtiqprmvpx.html

composer require --dev phpunit/phpunit
来源：http://dali.shuidangran.top/Article/details/gtmhtotzjv.html

[U79] PHP：静态分析
来源：http://dali.snrcjt.cn/Article/details/gtcwvtjcix.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gtumftbwfb.html

[U80] PHP：代码规范修复
来源：http://dali.ppjwa.cn/Article/details/gtsflpqhkb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.gogol.net.cn/Article/details/gtrjimyoyf.html

[U81] JS：初始化项目
来源：http://dali.zhengqikj.top/Article/details/gtgnjfuqih.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtzslkxquy.html

[U82] JS：package.json 脚本
来源：http://dali.svipenyu.cn/Article/details/gtfqmthtkv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtbacapnts.html

[U83] JS：ES Module 导入导出
来源：http://dali.0kj1m.cn/Article/details/gttszqwsay.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtsyqyrson.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gtiijjzcbu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yj20258.top/Article/details/gtkrizuocy.html

[U85] JS：可选链
来源：http://dali.xylfe.cn/Article/details/gtaqetucme.html

a?.b?.c
来源：http://dali.guannengcc.top/Article/details/gtctcruove.html

[U86] JS：空值合并
来源：http://dali.cqqwz.cn/Article/details/gtjxlhlnjz.html

a ?? b
来源：http://dali.hongshengwenyu.top/Article/details/gthwafmheb.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtegenbpai.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwoemlhx.html

[U88] JS：对象展开合并
来源：http://dali.zhoulong.xyz/Article/details/gtpztpteyv.html

{ ...a, ...b }
来源：http://dali.ydzc1.top/Article/details/gtarxkwcgg.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gtfqeuttza.html

[...new Set(arr)]
来源：http://dali.iojbl.cn/Article/details/gtiupqguui.html

[U90] JS：数字数组排序
来源：http://dali.shangyingyoupin.top/Article/details/gtswksiwbv.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrrtyklgj.html

[U91] JS：对象键值遍历
来源：http://dali.sweek.top/Article/details/gtxsqqilkj.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtkslbkmhd.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtirxmwqaj.html

structuredClone(obj)
来源：http://dali.hnxiangtu.top/Article/details/gtssvqmraj.html

[U93] JS：模板字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gttggcnyvb.html

`共 ${n} 条`
来源：http://dali.ehwqpu.com/Article/details/gtwxnqncpy.html

[U94] JS：箭头函数
来源：http://dali.quarkkingdee.top/Article/details/gtmncpluxs.html

const double = x => x * 2;
来源：http://dali.havefunace.top/Article/details/gtzjkvensg.html

[U95] JS：Promise 包装
来源：http://dali.yonumen.top/Article/details/gtsnrwcrju.html

new Promise((resolve, reject) => {})
来源：http://dali.redwolf501.top/Article/details/gtrufopgqc.html

[U96] JS：async/await 与异常
来源：http://dali.jlsjyb.cn/Article/details/gttankhmky.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.chenlongwang.top/Article/details/gtzxbpgdbn.html

[U97] JS：并发请求
来源：http://dali.jqgufenzy.top/Article/details/gtbdydomra.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xinyue.icu/Article/details/gtpxfdrkez.html

[U98] JS：fetch 带 JSON
来源：http://dali.jinqigufen.top/Article/details/gtqhjscykq.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.nwbrower.top/Article/details/gtpszedgwq.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gttunpcoho.html

el.addEventListener("click", e => {})
来源：http://dali.jqgfzy.top/Article/details/gtraaijpjt.html

[U100] JS：DOM 查询
来源：http://dali.guannengcc.top/Article/details/gtglbircec.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtguuvrots.html

[U101] JS：classList 操作
来源：http://dali.smart0.xyz/Article/details/gtnbwzjbxr.html

el.classList.toggle("active")
来源：http://dali.yj20258.top/Article/details/gtuxghhbqs.html

[U102] JS：本地存储
来源：http://dali.wangdashe.top/Article/details/gtfaoykvrj.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.gaohongyu789.top/Article/details/gttgbmucgq.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtjsjdtvth.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtizqccuiu.html

[U104] JS：防抖
来源：http://dali.xuanzx.com/Article/details/gtqzlsrzuw.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tianlin.xyz/Article/details/gtzguzhbuq.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gttcdashxk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hfpthk.cn/Article/details/gtsauqrjgd.html

[U106] JS：日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtmrexpmet.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.haohaochexian.top/Article/details/gtlzpodvkw.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gtmerapctn.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yueranfly.top/Article/details/gtuynijcqb.html

[U108] JS：随机整数
来源：http://dali.ydzc1.top/Article/details/gtwajdykkk.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.feifeiyinyue.top/Article/details/gtijhmusls.html

[U109] JS：数组分组
来源：http://dali.fengsongda.top/Article/details/gtpsqpejxc.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtkozwkacb.html

[U110] JS：数组分块
来源：http://dali.chenlongwang.top/Article/details/gtiyixenzv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.fengsongda.top/Article/details/gtgkezxryn.html

[U111] JS：对象转 Map
来源：http://dali.zhoulong.xyz/Article/details/gtljzkhgmm.html

new Map(Object.entries(obj))
来源：http://dali.shzxlz.cn/Article/details/gtitgnutpa.html

[U112] JS：字符串补位
来源：http://dali.nanxinkj.top/Article/details/gtopvfnpnm.html

"7".padStart(3, "0")
来源：http://dali.0kj1m.cn/Article/details/gtdfhljxja.html

[U113] JS：正则替换全部
来源：http://dali.quarkkingdee.top/Article/details/gtvognoflp.html

s.replaceAll("a", "b")
来源：http://dali.hnxiangtu.top/Article/details/gtoiveqxxj.html

[U114] JS：JSON 深比较
来源：http://dali.zycfv.cn/Article/details/gtsqohmaxh.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhixingplan.top/Article/details/gthjhrlpto.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtvcflexgg.html

crypto.randomUUID()
来源：http://dali.xuetiantiany.cn/Article/details/gtbkaiqyxp.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shzxlz.cn/Article/details/gtyjrauqdm.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ivvv.top/Article/details/gtqujgeefe.html

[U117] JS：单元测试
来源：http://dali.cqqwz.cn/Article/details/gtrzfoqioi.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzunqcava.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gtiotpnlia.html

npm i -D vite;  npx vite
来源：http://dali.yongpay.top/Article/details/gtajtautbm.html

[U119] JS：生产构建
来源：http://dali.iojbl.cn/Article/details/gtjnpujgii.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gtbdmjmufr.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhiwuduotai.top/Article/details/gtjbzeiuhx.html

import.meta.env.VITE_API_URL
来源：http://dali.jyoumei.cn/Article/details/gtpwthztkf.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtfyrlscxg.html

统计汇总
来源：http://dali.sxryk.cn/Article/details/gtecbholfa.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtyhszcgcy.html

按语言统计（条）：
来源：http://dali.zhixingplan.top/Article/details/gtzojhjydh.html

Python ......... 252
来源：http://dali.tianlin.xyz/Article/details/gtvqbhyzbs.html

PHP ............ 252
来源：http://dali.0kj1m.cn/Article/details/gtmhswpggu.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtrdmynqtz.html

TypeScript ..... 212
来源：http://dali.nwbrower.top/Article/details/gtzwnicojb.html

Java ........... 212
来源：http://dali.shanyushiyangtech.top/Article/details/gthsqhuwvs.html

Go ............. 212
来源：http://dali.guowangkeji.top/Article/details/gtrztgfvck.html

Ruby ........... 212
来源：http://dali.fengsongda.top/Article/details/gtdhuiyihl.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gtwmlaktkw.html

C .............. 30
来源：http://dali.jinghuilouyu.cn/Article/details/gtxshthzwu.html

C++ ............ 30
来源：http://dali.meibo888.top/Article/details/gtnelbcicx.html

SQL ............ 90
来源：http://dali.ydzc1.top/Article/details/gtbjjxpycn.html

Bash ........... 80
来源：http://dali.nwbrower.top/Article/details/gtwujbzbkb.html

Kotlin ......... 15
来源：http://dali.daria6918.cn/Article/details/gtolrmpipn.html

Swift .......... 15
来源：http://dali.andypj.xyz/Article/details/gtznbxtlgy.html

Lua ............ 10
来源：http://dali.andypj.xyz/Article/details/gtxeozdsod.html

Perl ........... 10
来源：http://dali.ybcxt.top/Article/details/gtsjbpmdip.html

Scala .......... 10
来源：http://dali.yonumen.top/Article/details/gtkiosoxph.html

------------------------------------
来源：http://dali.dashuyun.cn/Article/details/gtzstcmsdx.html

合计 ........... 2106 条
来源：http://dali.0kj1m.cn/Article/details/gtjzdksxoh.html

按章节统计：
来源：http://dali.svipenyu.cn/Article/details/gtbxowbaqg.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sysykeji.top/Article/details/gtzqaexxdy.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.havefunace.top/Article/details/gthqxejnbw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtzykfnyhu.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tianlin.xyz/Article/details/gtsdlfithd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gtafhgdzvo.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.iojbl.cn/Article/details/gthjqzssra.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yj20258888.top/Article/details/gtlvzqmdts.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.redwolf501.top/Article/details/gtmhlflqtn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gtdkmjvhwv.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.birdmap.top/Article/details/gttiiutmpu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jinqigufen.top/Article/details/gtkriwtroh.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gttshfluoy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gtzhyfxqth.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.havefunace.top/Article/details/gtpyhyexli.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.fengsongda.top/Article/details/gtylpfwpex.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtadjuetxf.html

Q SQL 专题                              90
来源：http://dali.zhixingplan.top/Article/details/gtunhogthi.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtitesizov.html

S C / C++ 专题                          60
来源：http://dali.nanxuanxn.top/Article/details/gtprqerlfo.html

T 其他语言补充                          60
来源：http://dali.chenlongwang.top/Article/details/gtqlcbqwpb.html


<!-- 参考信息 -->