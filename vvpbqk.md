代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtunvpyilg.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtitakogtp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtihyaedqw.html

[T56] Scala：样例类
来源：http://dali.zhijiandao.cn/Article/details/gtlbhhqaxb.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtgngrjddr.html

[T57] Scala：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtvlhoaxay.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhiwuduotai.top/Article/details/gtntsriwrn.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtqfpluekf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gtyaxggzee.html

[T59] Scala：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexbphlho.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtrlfnvrjc.html

[T60] Scala：折叠
来源：http://dali.xuanzx.com/Article/details/gtmkpyqotu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.c1oappe.top/Article/details/gtgcpzdrly.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtouujzrro.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtucxllymb.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtpobgtnji.html

[U01] Py：创建虚拟环境
来源：http://dali.xziqi.cn/Article/details/gtzwzlcipi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pengpengdd.cyou/Article/details/gtzwwsiebb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtmcvkzmee.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ivvv.top/Article/details/gthymfvrbt.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gtfnhekvoy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ppjwa.cn/Article/details/gthehsbzgp.html

[U04] Py：变量调试打印
来源：http://dali.sxryk.cn/Article/details/gtorjgqjve.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tanke756.top/Article/details/gtoypbumbc.html

[U05] Py：列表去重且保序
来源：http://dali.nwbrower.top/Article/details/gtdjymqyhe.html

list(dict.fromkeys(arr))
来源：http://dali.shzxlz.cn/Article/details/gtypxcrdtk.html

[U06] Py：合并两个字典
来源：http://dali.haohaochexian.top/Article/details/gtkcejwchv.html

{**a, **b}
来源：http://dali.shuidangran.top/Article/details/gtcjfuywmk.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtvoymjcxq.html

{v: k for k, v in d.items()}
来源：http://dali.hywenlv.cn/Article/details/gtdabgygyx.html

[U08] Py：展平二维列表
来源：http://dali.cashguo.top/Article/details/gtsxutsnov.html

[y for x in nested for y in x]
来源：http://dali.wangdashe.top/Article/details/gtaazjuxxl.html

[U09] Py：字典取最大值的键
来源：http://dali.yuanzhike.top/Article/details/gtcdanosta.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtpbjibibw.html

[U10] Py：按值排序字典
来源：http://dali.tian-w.cn/Article/details/gtblhwtejh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj202588.top/Article/details/gtkotgbzoe.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtjzzjwpwq.html

(x * 2 for x in arr)
来源：http://dali.yvedp.cn/Article/details/gtgoylmqoc.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtpklfkogx.html

Counter(arr).most_common(3)
来源：http://dali.yvedp.cn/Article/details/gttdrfxwpf.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtvkaocypk.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtikdhtlmy.html

[U14] Py：分组收集到列表
来源：http://dali.316326.xyz/Article/details/gtvrukodyx.html

defaultdict(list)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgpllgfep.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gtxexiqekh.html

t = time.perf_counter()
来源：http://dali.fengsongda.top/Article/details/gtwvumwztp.html

[U16] Py：命令行参数解析
来源：http://dali.zdqjudy.top/Article/details/gtgpedvzoo.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.iojbl.cn/Article/details/gtjtppvxvq.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtfnzagdmc.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hammf.cn/Article/details/gtiptpkyqd.html

[U18] Py：预编译正则
来源：http://dali.cheryme.top/Article/details/gtfglttzar.html

pat = re.compile(r"\d+")
来源：http://dali.fengsongda.top/Article/details/gtclobwamw.html

[U19] Py：正则替换带回调
来源：http://dali.redwolf501.top/Article/details/gtqfobipfj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.ivvv.top/Article/details/gtolejmhjc.html

[U20] Py：缓存函数结果
来源：http://dali.gaohongyu789.top/Article/details/gtdjgdkwbb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.0kj1m.cn/Article/details/gtfxlobwrh.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtfnldwmzc.html

@contextlib.contextmanager
来源：http://dali.cqqwz.cn/Article/details/gtzaaegxld.html

[U22] Py：矩阵转置
来源：http://dali.gzhubu.top/Article/details/gtqrjehlhz.html

list(zip(*m))
来源：http://dali.jinqigufen.top/Article/details/gtkkindltm.html

[U23] Py：分块读取大文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtuqnepoxh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.cqqwz.cn/Article/details/gthcjjkbqw.html

[U24] Py：路径操作
来源：http://dali.dianchejie.cn/Article/details/gtvqckqyoc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sysykeji.top/Article/details/gtrulrrbwe.html

[U25] Py：CSV 按字典读
来源：http://dali.zhoulong.xyz/Article/details/gtqgnjexbd.html

csv.DictReader(f)
来源：http://dali.zhiwuduotai.top/Article/details/gtzmmzeibt.html

[U26] Py：并发下载
来源：http://dali.yj20258.top/Article/details/gttanuwdgw.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.quarkkingdee.top/Article/details/gtznvnikko.html

[U27] Py：异步 HTTP
来源：http://dali.snrcjt.cn/Article/details/gthkacgkji.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yongpay.top/Article/details/gtatxnpbst.html

[U28] Py：类型别名
来源：http://dali.nanxuanxn.top/Article/details/gtvfpfhhvm.html

UserId = int
来源：http://dali.birdmap.top/Article/details/gtjnnrrpnj.html

[U29] Py：属性校验
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddoscvtd.html

@property 与 @x.setter 配合
来源：http://dali.haohaochexian.top/Article/details/gthsippgac.html

[U30] Py：数据类
来源：http://dali.bjfxy.top/Article/details/gtouzuwxae.html

@dataclass(slots=True)
来源：http://dali.xuetiantiany.cn/Article/details/gtcvutbldc.html

[U31] Py：单测
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpgpnkegg.html

python -m pytest -q
来源：http://dali.yuanzhike.top/Article/details/gtzwmrkmtc.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtlvhkjtow.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gtsiizflvu.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtmbkxodqu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtvjctloly.html

[U34] Py：判断编码
来源：http://dali.zhongyouzk.top/Article/details/gtatnkeelr.html

chardet.detect(raw)
来源：http://dali.dianchejie.cn/Article/details/gtjgrhwfbw.html

[U35] Py：发送邮件
来源：http://dali.yueranfly.top/Article/details/gtsexcfpkv.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.cashguo.top/Article/details/gtkinsbdxg.html

[U36] Py：定时任务
来源：http://dali.zhengqikj.top/Article/details/gtronrlvus.html

schedule.every(10).minutes.do(job)
来源：http://dali.yangfankeji.com/Article/details/gtnbtvvoev.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtjhzztryk.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yuanzhike.top/Article/details/gtprqvboog.html

[U38] Py：获取脚本所在目录
来源：http://dali.xuanzx.com/Article/details/gtoxttpkfa.html

Path(__file__).resolve().parent
来源：http://dali.jiagoushi.top/Article/details/gtwkgoildp.html

[U39] Py：判断是否在交互环境
来源：http://dali.wangshuangyany.cn/Article/details/gthqjtncvx.html

sys.stdout.isatty()
来源：http://dali.c1oappe.top/Article/details/gteacqdmvn.html

[U40] Py：打印到标准错误
来源：http://dali.yonumen.top/Article/details/gtgcpmrniw.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtmeodlsjp.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hongshengwenyu.top/Article/details/gtgepoqymw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hywenlv.cn/Article/details/gtjnlvmeyn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.chenjidiqi.icu/Article/details/gtvdhbgwvs.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.jqgfzy.top/Article/details/gtzvfmrkqt.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gtbxxixpdi.html

namespace App\Http;
来源：http://dali.jqgufenzy.top/Article/details/gtgiiopifi.html

[U44] PHP：开启严格类型
来源：http://dali.hnxiangtu.top/Article/details/gthgyoxaau.html

declare(strict_types=1);
来源：http://dali.yj20258888.top/Article/details/gtbayfyrfi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gttlweizvi.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gthsccjlqn.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gtahepfqte.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gtyxbthumu.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gtlzywmkiv.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtbmztkobd.html

[U48] PHP：纯枚举
来源：http://dali.ybcxt.top/Article/details/gtjfvicblx.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.guannengcc.top/Article/details/gtrigsffnl.html

[U49] PHP：只读属性
来源：http://dali.yj20258.top/Article/details/gtjrhihjsf.html

public readonly string $name
来源：http://dali.c1oappe.top/Article/details/gtrnqcjxda.html

[U50] PHP：构造器属性提升
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfmupddcz.html

public function __construct(private int $id) {}
来源：http://dali.ppjwa.cn/Article/details/gtbbzqnnaj.html

[U51] PHP：数组解构
来源：http://dali.wangdashe.top/Article/details/gtpwepoztd.html

[$a, $b] = $arr;
来源：http://dali.gaohongyu789.top/Article/details/gtwykiyokb.html

[U52] PHP：箭头函数
来源：http://dali.yonumen.top/Article/details/gtcpbuwqwg.html

$double = fn($x) => $x * 2;
来源：http://dali.aibaodan.cn/Article/details/gtmjvtlybl.html

[U53] PHP：空合并运算符
来源：http://dali.yuxming.cn/Article/details/gtyfyjxmfv.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhixingplan.top/Article/details/gtbiigrjye.html

[U54] PHP：空安全调用
来源：http://dali.ppjwa.cn/Article/details/gtoztwtzlx.html

$obj?->method()
来源：http://dali.nanxuanxn.top/Article/details/gtfschmscs.html

[U55] PHP：match 表达式
来源：http://dali.haohaochexian.top/Article/details/gtchyidvme.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhoulong.xyz/Article/details/gtctwxkozr.html

[U56] PHP：命名参数
来源：http://dali.daxiang520.top/Article/details/gtxinqxals.html

f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtkqblbtmg.html

[U57] PHP：字符串插值
来源：http://dali.meibo888.top/Article/details/gtwdglcasy.html

"值: {$a}"
来源：http://dali.zdqjudy.top/Article/details/gtyikojrql.html

[U58] PHP：数组三件套
来源：http://dali.zhongyouzk.top/Article/details/gtejqfhjdc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ybcxt.top/Article/details/gtnjdtkony.html

[U59] PHP：自定义排序
来源：http://dali.gogol.net.cn/Article/details/gtdledyomo.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ehwqpu.com/Article/details/gthnirfklq.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigufen.top/Article/details/gtabmvyngl.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtwiauyrfh.html

[U61] PHP：正则
来源：http://dali.zhaomingkeji.xyz/Article/details/gtouqzdwbt.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.smart0.xyz/Article/details/gtpqpiaovd.html

[U62] PHP：日期对象
来源：http://dali.wangdashe.top/Article/details/gtckymwcjh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.daxiang520.top/Article/details/gtyzquxldn.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gthylewkeh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hywenlv.cn/Article/details/gtejroehac.html

[U64] PHP：目录遍历
来源：http://dali.zdqjudy.top/Article/details/gtgqxnpkxm.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.pengpengdd.cyou/Article/details/gtjtzeezou.html

[U65] PHP：会话
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiongzjvc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtdtkpgtip.html

[U66] PHP：设置 Cookie
来源：http://dali.hysaishi.cn/Article/details/gtfpmlfiti.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yj202588.top/Article/details/gtlkyoqfdc.html

[U67] PHP：处理文件上传
来源：http://dali.jqgufenzy.top/Article/details/gtzztyknkz.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtxkbcuccf.html

[U68] PHP：PDO 连接
来源：http://dali.xinyue.icu/Article/details/gtgoostsal.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoyftsmbb.html

[U69] PHP：PDO 预处理
来源：http://dali.sxryk.cn/Article/details/gtkogfoeya.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xziqi.cn/Article/details/gtbjdgldqx.html

[U70] PHP：PDO 事务
来源：http://dali.hammf.cn/Article/details/gthyhkmgnw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhengqikj.top/Article/details/gtaqlpxrpz.html

[U71] PHP：抛出异常
来源：http://dali.xylfe.cn/Article/details/gtzuvvxdql.html

throw new RuntimeException("失败", 500);
来源：http://dali.birdmap.top/Article/details/gtnfytegyl.html

[U72] PHP：写错误日志
来源：http://dali.zhiwuduotai.top/Article/details/gtzxsrlzys.html

error_log("失败: " . $e->getMessage());
来源：http://dali.ydzc1.top/Article/details/gtqxxyebtl.html

[U73] PHP：读取 ini 配置
来源：http://dali.cdnleiting.top/Article/details/gtjdmawues.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtscbkjxxm.html

[U74] PHP：读取环境变量
来源：http://dali.guannengcc.top/Article/details/gtnfxeaggb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtmbevubsr.html

[U75] PHP：依赖注入
来源：http://dali.zhengqikj.top/Article/details/gtlqrycwya.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtwtlxcwdm.html

[U76] PHP：简单路由
来源：http://dali.yvedp.cn/Article/details/gtthnarhoh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.birdmap.top/Article/details/gtmdkhitdh.html

[U77] PHP：模板渲染
来源：http://dali.jlsjyb.cn/Article/details/gtlqthzziu.html

composer require twig/twig
来源：http://dali.jinqigfzy.top/Article/details/gtualfmusi.html

[U78] PHP：单元测试
来源：http://dali.tianlin.xyz/Article/details/gtvtxkeezq.html

composer require --dev phpunit/phpunit
来源：http://dali.redwolf501.top/Article/details/gtvdanagqo.html

[U79] PHP：静态分析
来源：http://dali.yuxming.cn/Article/details/gtwmnceyuv.html

composer require --dev phpstan/phpstan
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyzrgnoyq.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gtrvcuvsnr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gttukmdhac.html

[U81] JS：初始化项目
来源：http://dali.aizwys.cn/Article/details/gtkqbltikk.html

npm init -y;  npm i express
来源：http://dali.zhijiandao.cn/Article/details/gtbvpatipf.html

[U82] JS：package.json 脚本
来源：http://dali.havefunace.top/Article/details/gtnatzenjq.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.cqqwz.cn/Article/details/gtkqqhflpx.html

[U83] JS：ES Module 导入导出
来源：http://dali.yonumen.top/Article/details/gtzfxdglor.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtnbzbliic.html

[U84] JS：CommonJS 写法
来源：http://dali.shangyingyoupin.top/Article/details/gtvgolwkqj.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuanzx.com/Article/details/gtwleoftrs.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwpiyecy.html

a?.b?.c
来源：http://dali.iojbl.cn/Article/details/gtyhcttkhg.html

[U86] JS：空值合并
来源：http://dali.jyoumei.cn/Article/details/gtkoaxoztx.html

a ?? b
来源：http://dali.zhiwuduotai.top/Article/details/gtqjsbmiyw.html

[U87] JS：解构默认值
来源：http://dali.yuanzhike.top/Article/details/gtipmsbaxl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtgypyzdmk.html

[U88] JS：对象展开合并
来源：http://dali.zhongyouzk.top/Article/details/gtefuiwctu.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtiboceumb.html

[U89] JS：数组去重
来源：http://dali.smart0.xyz/Article/details/gtcdjmkakv.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gtdiwrxcza.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtqiglcjkz.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenlongwang.top/Article/details/gtggvxvmix.html

[U91] JS：对象键值遍历
来源：http://dali.hfpthk.cn/Article/details/gtxhuypknz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gtaqxknuqb.html

[U92] JS：深拷贝
来源：http://dali.cqqwz.cn/Article/details/gtbnittuss.html

structuredClone(obj)
来源：http://dali.pycfn.com/Article/details/gtojgqvnmi.html

[U93] JS：模板字符串
来源：http://dali.svipenyu.cn/Article/details/gtahnlknuu.html

`共 ${n} 条`
来源：http://dali.jinghuilouyu.cn/Article/details/gtasiaqsor.html

[U94] JS：箭头函数
来源：http://dali.nwbrower.top/Article/details/gtpupldccd.html

const double = x => x * 2;
来源：http://dali.cashguo.top/Article/details/gttvyfgnaq.html

[U95] JS：Promise 包装
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgfonhei.html

new Promise((resolve, reject) => {})
来源：http://dali.mhx1999.top/Article/details/gtnfsyjfzi.html

[U96] JS：async/await 与异常
来源：http://dali.xziqi.cn/Article/details/gtnfwriugd.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hongshengwenyu.top/Article/details/gtussdwnxx.html

[U97] JS：并发请求
来源：http://dali.quarkkingdee.top/Article/details/gtwypjedio.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cdnleiting.top/Article/details/gtsnlyvcta.html

[U98] JS：fetch 带 JSON
来源：http://dali.xylfe.cn/Article/details/gtziavcjlb.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.hywenlv.cn/Article/details/gtbuvnritt.html

[U99] JS：事件监听
来源：http://dali.316326.xyz/Article/details/gtqzdyyjaz.html

el.addEventListener("click", e => {})
来源：http://dali.vqdsnc.cn/Article/details/gtibqavnod.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gthgxsfwhh.html

document.querySelector(".item")
来源：http://dali.cashguo.top/Article/details/gtjfpnlvmf.html

[U101] JS：classList 操作
来源：http://dali.hongshengwenyu.top/Article/details/gtrvwonycl.html

el.classList.toggle("active")
来源：http://dali.hammf.cn/Article/details/gtylotkcpx.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtsuzoakcr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlaczlze.html

[U103] JS：定时器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtolsiradt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.jqgfzy.top/Article/details/gtfisnvult.html

[U104] JS：防抖
来源：http://dali.redwolf501.top/Article/details/gtlliacxnm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.nwbrower.top/Article/details/gttdvxdpmf.html

[U105] JS：节流
来源：http://dali.jyoumei.cn/Article/details/gtoxdmwnak.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.iojbl.cn/Article/details/gtiyhniofz.html

[U106] JS：日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtbgmadyyv.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.sufxvd.cn/Article/details/gtijwxrfzp.html

[U107] JS：数字千分位
来源：http://dali.zdqjudy.top/Article/details/gtcsfaftrh.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgfzy.top/Article/details/gtuhclvpue.html

[U108] JS：随机整数
来源：http://dali.yangfankeji.com/Article/details/gtscfkjyhs.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yvedp.cn/Article/details/gtdygggrba.html

[U109] JS：数组分组
来源：http://dali.ybcxt.top/Article/details/gtzfqxtoxu.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtbeqinthw.html

[U110] JS：数组分块
来源：http://dali.zycfv.cn/Article/details/gtuthpswsp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.0kj1m.cn/Article/details/gtfdubqrog.html

[U111] JS：对象转 Map
来源：http://dali.meibo888.top/Article/details/gtihpxwfvm.html

new Map(Object.entries(obj))
来源：http://dali.mhx1999.top/Article/details/gttvxagrie.html

[U112] JS：字符串补位
来源：http://dali.hfpthk.cn/Article/details/gtvnblgngx.html

"7".padStart(3, "0")
来源：http://dali.nanxinkj.top/Article/details/gttazshrfy.html

[U113] JS：正则替换全部
来源：http://dali.hywenlv.cn/Article/details/gtdjnchuwc.html

s.replaceAll("a", "b")
来源：http://dali.zhixingplan.top/Article/details/gtvqhdontl.html

[U114] JS：JSON 深比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkcganbd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yueranfly.top/Article/details/gtkjsfmdgg.html

[U115] JS：生成 UUID
来源：http://dali.jyoumei.cn/Article/details/gtwayfozdd.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtpibfaqft.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daxiang520.top/Article/details/gtmeegeabx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jiagoushi.top/Article/details/gtcwjthlds.html

[U117] JS：单元测试
来源：http://dali.guowangkeji.top/Article/details/gtddnnbjrp.html

npm i -D vitest;  npx vitest
来源：http://dali.nanxuanxn.top/Article/details/gtuepwjija.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gthxkibvnc.html

npm i -D vite;  npx vite
来源：http://dali.havefunace.top/Article/details/gthrzsbxbo.html

[U119] JS：生产构建
来源：http://dali.jianghu66.top/Article/details/gtfqzdvquy.html

npx vite build
来源：http://dali.hysaishi.cn/Article/details/gtbvkmbpzv.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.xuanzx.com/Article/details/gtiovliwlh.html

import.meta.env.VITE_API_URL
来源：http://dali.wangshuangyany.cn/Article/details/gtrrraioxd.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtxqibkmve.html

统计汇总
来源：http://dali.nanxinkj.top/Article/details/gtazpxxypm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtmybtpwha.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtpkzenpdt.html

Python ......... 252
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmlwmepjn.html

PHP ............ 252
来源：http://dali.pycfn.com/Article/details/gtnctxwuma.html

JavaScript ..... 252
来源：http://dali.shanyushiyangtech.top/Article/details/gtonaxeefj.html

TypeScript ..... 212
来源：http://dali.jyoumei.cn/Article/details/gtwidpkzeo.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gtagavehld.html

Go ............. 212
来源：http://dali.bjfxy.top/Article/details/gtotlbidwa.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gtxxohoncf.html

C# ............. 212
来源：http://dali.wangdashe.top/Article/details/gtscmpctwl.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gtaeeavitk.html

C++ ............ 30
来源：http://dali.sweek.top/Article/details/gtqponibqp.html

SQL ............ 90
来源：http://dali.nanxinkj.top/Article/details/gttufyzqzi.html

Bash ........... 80
来源：http://dali.zdqjudy.top/Article/details/gtajsaqopx.html

Kotlin ......... 15
来源：http://dali.redwolf501.top/Article/details/gtrjddxlom.html

Swift .......... 15
来源：http://dali.xylfe.cn/Article/details/gtsidqhctj.html

Lua ............ 10
来源：http://dali.daxiang520.top/Article/details/gtpighihve.html

Perl ........... 10
来源：http://dali.hysaishi.cn/Article/details/gtjcnfscwj.html

Scala .......... 10
来源：http://dali.vqdsnc.cn/Article/details/gtwmnrnsyg.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtaftuwgjr.html

合计 ........... 2106 条
来源：http://dali.gogol.net.cn/Article/details/gtguhmpcrl.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gteclzyeyu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aibaodan.cn/Article/details/gtlkxrnbud.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.birdmap.top/Article/details/gtzxqhjwxs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtkpmqijgr.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.gogol.net.cn/Article/details/gtyzxeajbg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hysaishi.cn/Article/details/gteeijucsl.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xuetiantiany.cn/Article/details/gtnyopsbmv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gtocippfqy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.chenjidiqi.icu/Article/details/gthdjcmssa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtrnwhmwsb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.0kj1m.cn/Article/details/gtexanrxlu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.jlsjyb.cn/Article/details/gtawgmatmk.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhengqikj.top/Article/details/gtpnjencqu.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhijiandao.cn/Article/details/gtcjdrbujw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gtkrlvlnup.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtwdslycqt.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gtpejsklnv.html

Q SQL 专题                              90
来源：http://dali.kuanghao11.cn/Article/details/gtjejxezgr.html

R Bash 专题                             80
来源：http://dali.sufxvd.cn/Article/details/gtiuefdfda.html

S C / C++ 专题                          60
来源：http://dali.316326.xyz/Article/details/gtrefbqjan.html

T 其他语言补充                          60
来源：http://dali.ppjwa.cn/Article/details/gttemkemxv.html


<!-- 参考信息 -->