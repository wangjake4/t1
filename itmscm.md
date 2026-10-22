代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xylfe.cn/Article/details/gt2inwbaywz.html

[T59] Scala：循环
来源：http://dali.yanxiufei.cn/Article/details/gt2qowdlzsj.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2xwzimrnt.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gt2emwvpckj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2scdapzqs.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2qypagitd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.c1oappe.top/Article/details/gt2qrintnkw.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2dfybuhei.html

[U01] Py：创建虚拟环境
来源：http://dali.jlsjyb.cn/Article/details/gt2feqxicyb.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yvedp.cn/Article/details/gt2kpdlshua.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgfzy.top/Article/details/gt2pydwyvqn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2fifatmmp.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gt2zlmpvhhv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mqhtyzsg.html

[U04] Py：变量调试打印
来源：http://dali.yueranfly.top/Article/details/gt2mgywtmji.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcjddtus.html

[U05] Py：列表去重且保序
来源：http://dali.xziqi.cn/Article/details/gt2jtiajaye.html

list(dict.fromkeys(arr))
来源：http://dali.iojbl.cn/Article/details/gt2asadisml.html

[U06] Py：合并两个字典
来源：http://dali.chenzaomai.com/Article/details/gt2hvasboos.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gt2pxthvtiz.html

[U07] Py：反转字典键值
来源：http://dali.ivvv.top/Article/details/gt2kaekifzg.html

{v: k for k, v in d.items()}
来源：http://dali.tian-w.cn/Article/details/gt2wmfsdufs.html

[U08] Py：展平二维列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vwixrnmy.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2kzeuyecm.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gt2jgkefktd.html

max(d, key=d.get)
来源：http://dali.cashguo.top/Article/details/gt2bxwxewdc.html

[U10] Py：按值排序字典
来源：http://dali.kuanghao11.cn/Article/details/gt2kbsywfzx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.chenlongwang.top/Article/details/gt2yesalqlg.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2kzhsjqtj.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gt2scbevgwy.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.xuanzx.com/Article/details/gt2twnbdsfu.html

Counter(arr).most_common(3)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nugigbxz.html

[U13] Py：固定长度队列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wvvzraep.html

deque(maxlen=10)
来源：http://dali.jinqigufen.top/Article/details/gt2ybvuczff.html

[U14] Py：分组收集到列表
来源：http://dali.jinqigfzy.top/Article/details/gt2dgcnhnlp.html

defaultdict(list)
来源：http://dali.tian-w.cn/Article/details/gt2bvnhubqy.html

[U15] Py：高精度计时
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqwieuse.html

t = time.perf_counter()
来源：http://dali.hysaishi.cn/Article/details/gt2pjetawlv.html

[U16] Py：命令行参数解析
来源：http://dali.tian-w.cn/Article/details/gt2vjykcznl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jyoumei.cn/Article/details/gt2cydwtpss.html

[U17] Py：初始化日志
来源：http://dali.c1oappe.top/Article/details/gt2nwuibxbt.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntvgnmbg.html

[U18] Py：预编译正则
来源：http://dali.redwolf501.top/Article/details/gt2onbnqoom.html

pat = re.compile(r"\d+")
来源：http://dali.sufxvd.cn/Article/details/gt2ekqrknjl.html

[U19] Py：正则替换带回调
来源：http://dali.chenzaomai.com/Article/details/gt2afbkpdrv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.316326.xyz/Article/details/gt2uppdzjuw.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gt2trtemzox.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gt2nzvuozrn.html

[U21] Py：自定义上下文管理器
来源：http://dali.quarkkingdee.top/Article/details/gt2whtyokxl.html

@contextlib.contextmanager
来源：http://dali.zhoulong.xyz/Article/details/gt2wgdfbgrk.html

[U22] Py：矩阵转置
来源：http://dali.yuanzhike.top/Article/details/gt2liuzoayc.html

list(zip(*m))
来源：http://dali.hongshengwenyu.top/Article/details/gt2acebdpzi.html

[U23] Py：分块读取大文件
来源：http://dali.yj202588.top/Article/details/gt2ivhxmyow.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cjqaaxqk.html

[U24] Py：路径操作
来源：http://dali.jqgufenzy.top/Article/details/gt2wiydovxb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gt2ukuvhulh.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gt2fmhodsou.html

csv.DictReader(f)
来源：http://dali.ppjwa.cn/Article/details/gt2etgulphm.html

[U26] Py：并发下载
来源：http://dali.chenlongwang.top/Article/details/gt2hjesbgmm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.dianchejie.cn/Article/details/gt2cheifeoo.html

[U27] Py：异步 HTTP
来源：http://dali.nwbrower.top/Article/details/gt2agtzafxd.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gzhubu.top/Article/details/gt2eymiggxa.html

[U28] Py：类型别名
来源：http://dali.316326.xyz/Article/details/gt2lezpcqpr.html

UserId = int
来源：http://dali.snrcjt.cn/Article/details/gt2pzbewiub.html

[U29] Py：属性校验
来源：http://dali.yj20258888.top/Article/details/gt2gbszjlwe.html

@property 与 @x.setter 配合
来源：http://dali.zhijiandao.cn/Article/details/gt2xuhceifm.html

[U30] Py：数据类
来源：http://dali.yanxiufei.cn/Article/details/gt2crcclfgz.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gt2xmaoyhnx.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2vunnijdz.html

python -m pytest -q
来源：http://dali.hfpthk.cn/Article/details/gt2wfxphkai.html

[U32] Py：代码格式化
来源：http://dali.ppjwa.cn/Article/details/gt2bnhbfbmw.html

ruff format . && ruff check --fix .
来源：http://dali.gzhubu.top/Article/details/gt2teqnynon.html

[U33] Py：打包发布
来源：http://dali.tianlin.xyz/Article/details/gt2caqukanw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.hongshengwenyu.top/Article/details/gt2szdsqhku.html

[U34] Py：判断编码
来源：http://dali.xziqi.cn/Article/details/gt2urlfoadc.html

chardet.detect(raw)
来源：http://dali.jinqigufen.top/Article/details/gt2oklbsuzn.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gt2dzimwote.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gt2liocrrsv.html

[U36] Py：定时任务
来源：http://dali.haohaochexian.top/Article/details/gt2toiziqfr.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sjtyefeo.html

[U37] Py：读写 Excel
来源：http://dali.ydzc1.top/Article/details/gt2jjmbamwm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xziqi.cn/Article/details/gt2nvgzopuj.html

[U38] Py：获取脚本所在目录
来源：http://dali.shzxlz.cn/Article/details/gt2alblksul.html

Path(__file__).resolve().parent
来源：http://dali.mhx1999.top/Article/details/gt2hqvikvkk.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gt2urajihgz.html

sys.stdout.isatty()
来源：http://dali.shuidangran.top/Article/details/gt2bafxiwgw.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gt2qrqzpkiv.html

print("err", file=sys.stderr)
来源：http://dali.quarkkingdee.top/Article/details/gt2iytvucxs.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.xuanzx.com/Article/details/gt2kbfoqmmi.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.guannengcc.top/Article/details/gt2vfuscoau.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ybcxt.top/Article/details/gt2vofkvkjo.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2oazjerrw.html

[U43] PHP：声明命名空间
来源：http://dali.ppjwa.cn/Article/details/gt2fgvxudbe.html

namespace App\Http;
来源：http://dali.9152youxi.cn/Article/details/gt2ndjfaqkr.html

[U44] PHP：开启严格类型
来源：http://dali.guannengcc.top/Article/details/gt2cyzrxfuy.html

declare(strict_types=1);
来源：http://dali.yanxiufei.cn/Article/details/gt2osdvsxpn.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gt2yqqigtat.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gt2yupodbwv.html

[U46] PHP：可空类型
来源：http://dali.9152youxi.cn/Article/details/gt2rqqxayhi.html

?string $name = null
来源：http://dali.hongshengwenyu.top/Article/details/gt2qmejeczb.html

[U47] PHP：联合类型
来源：http://dali.fzhhl.top/Article/details/gt2wthveazh.html

int|string $id
来源：http://dali.jqgfzy.top/Article/details/gt2bnkpfrsz.html

[U48] PHP：纯枚举
来源：http://dali.hammf.cn/Article/details/gt2ortawsiq.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tian-w.cn/Article/details/gt2agtqpwmh.html

[U49] PHP：只读属性
来源：http://dali.shzxlz.cn/Article/details/gt2qifgokpw.html

public readonly string $name
来源：http://dali.haohaochexian.top/Article/details/gt2urwgglvc.html

[U50] PHP：构造器属性提升
来源：http://dali.daria6918.cn/Article/details/gt2zpzhreaf.html

public function __construct(private int $id) {}
来源：http://dali.0kj1m.cn/Article/details/gt2bzfnnbfg.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gt2xesdtjqh.html

[$a, $b] = $arr;
来源：http://dali.yueranfly.top/Article/details/gt2hndqfkcz.html

[U52] PHP：箭头函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yvwgvevc.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258888.top/Article/details/gt2idksfqsv.html

[U53] PHP：空合并运算符
来源：http://dali.svipenyu.cn/Article/details/gt2osscgrne.html

$v = $a ?? $b ?? "default";
来源：http://dali.yvedp.cn/Article/details/gt2nwljgbrp.html

[U54] PHP：空安全调用
来源：http://dali.zhiwuduotai.top/Article/details/gt2tmuiakzw.html

$obj?->method()
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdyxgbhk.html

[U55] PHP：match 表达式
来源：http://dali.yuanzhike.top/Article/details/gt2yykunhkv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gfbhedfn.html

[U56] PHP：命名参数
来源：http://dali.sysykeji.top/Article/details/gt2jaqbngrq.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2mzpwnxpi.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2zafawrrj.html

"值: {$a}"
来源：http://dali.gotoacloud.top/Article/details/gt2yrlfwlgx.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egbvudxq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhoulong.xyz/Article/details/gt2vtvxkdgs.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwyhuywe.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.sufxvd.cn/Article/details/gt2adnnispq.html

[U60] PHP：JSON 编解码
来源：http://dali.jinqigfzy.top/Article/details/gt2difpwjgm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mcjcbqvt.html

[U61] PHP：正则
来源：http://dali.smart0.xyz/Article/details/gt2mqnpymiy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shzxlz.cn/Article/details/gt2vcegkeaj.html

[U62] PHP：日期对象
来源：http://dali.hfpthk.cn/Article/details/gt2tdgqmqbl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yvedp.cn/Article/details/gt2akueayxa.html

[U63] PHP：文件读写
来源：http://dali.yangfankeji.com/Article/details/gt2vpwndlzb.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cqqwz.cn/Article/details/gt2nvjvqzyr.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gt2loqgjeit.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinqigfzy.top/Article/details/gt2afrpahme.html

[U65] PHP：会话
来源：http://dali.0kj1m.cn/Article/details/gt2dgoyshvc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sxryk.cn/Article/details/gt2ngkfzupj.html

[U66] PHP：设置 Cookie
来源：http://dali.hongshengwenyu.top/Article/details/gt2nmuosgvk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gotoacloud.top/Article/details/gt2aotgiles.html

[U67] PHP：处理文件上传
来源：http://dali.quarkkingdee.top/Article/details/gt2xdwsbfib.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hammf.cn/Article/details/gt2wppqgost.html

[U68] PHP：PDO 连接
来源：http://dali.jqgufenzy.top/Article/details/gt2zrldmezg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gt2nnwabgmy.html

[U69] PHP：PDO 预处理
来源：http://dali.jqgfzy.top/Article/details/gt2ojhxjjba.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hpmnmyxt.html

[U70] PHP：PDO 事务
来源：http://dali.svipenyu.cn/Article/details/gt2avcdyjdq.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yonumen.top/Article/details/gt2wabmgvno.html

[U71] PHP：抛出异常
来源：http://dali.wangdashe.top/Article/details/gt2wufnnaqs.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenzaomai.com/Article/details/gt2nbpkbfdw.html

[U72] PHP：写错误日志
来源：http://dali.zhongyouzk.top/Article/details/gt2cjnmryzh.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sufxvd.cn/Article/details/gt2qwsbfigh.html

[U73] PHP：读取 ini 配置
来源：http://dali.kuanghao11.cn/Article/details/gt2cmrsldhj.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bdazjkzm.html

[U74] PHP：读取环境变量
来源：http://dali.xuanzx.com/Article/details/gt2zwfnktep.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xuanzx.com/Article/details/gt2lykeppdt.html

[U75] PHP：依赖注入
来源：http://dali.shangyingyoupin.top/Article/details/gt2knpqcawd.html

composer require psr/container
来源：http://dali.ydzc1.top/Article/details/gt2dvxxyjhd.html

[U76] PHP：简单路由
来源：http://dali.zhongyouzk.top/Article/details/gt2pdfyckmv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.kuanghao11.cn/Article/details/gt2gvshjwxe.html

[U77] PHP：模板渲染
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2meyoyryw.html

composer require twig/twig
来源：http://dali.bjfxy.top/Article/details/gt2rwawmvhm.html

[U78] PHP：单元测试
来源：http://dali.vqdsnc.cn/Article/details/gt2ydpozjpa.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gt2qevochqa.html

[U79] PHP：静态分析
来源：http://dali.9152youxi.cn/Article/details/gt2qunnkmkg.html

composer require --dev phpstan/phpstan
来源：http://dali.snrcjt.cn/Article/details/gt2jkwrrkah.html

[U80] PHP：代码规范修复
来源：http://dali.ppjwa.cn/Article/details/gt2ywkebprn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.andypj.xyz/Article/details/gt2topcaxel.html

[U81] JS：初始化项目
来源：http://dali.nanxinkj.top/Article/details/gt2ayyxzgfc.html

npm init -y;  npm i express
来源：http://dali.iojbl.cn/Article/details/gt2dplusowe.html

[U82] JS：package.json 脚本
来源：http://dali.feifeiyinyue.top/Article/details/gt2gfaiyofw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gt2unsauhmr.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gt2sliimrdf.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmcaparl.html

[U84] JS：CommonJS 写法
来源：http://dali.tanke756.top/Article/details/gt2wdlntdtv.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gt2svugxkle.html

[U85] JS：可选链
来源：http://dali.yj202588.top/Article/details/gt2nfdsthij.html

a?.b?.c
来源：http://dali.havefunace.top/Article/details/gt2kmactska.html

[U86] JS：空值合并
来源：http://dali.dashuyun.cn/Article/details/gt2shdzotuu.html

a ?? b
来源：http://dali.mhx1999.top/Article/details/gt2cwzpyjnp.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2orghygtq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.gaohongyu789.top/Article/details/gt2jhzzrsih.html

[U88] JS：对象展开合并
来源：http://dali.tian-w.cn/Article/details/gt2mhzmdlod.html

{ ...a, ...b }
来源：http://dali.hysaishi.cn/Article/details/gt2mcrbyaoj.html

[U89] JS：数组去重
来源：http://dali.zhoulong.xyz/Article/details/gt2tznztbge.html

[...new Set(arr)]
来源：http://dali.yj202588.top/Article/details/gt2iikxoadc.html

[U90] JS：数字数组排序
来源：http://dali.nanxinkj.top/Article/details/gt2nvwxtwas.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gt2dlzkisae.html

[U91] JS：对象键值遍历
来源：http://dali.gogol.net.cn/Article/details/gt2vmzwecnq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gt2bhqilils.html

[U92] JS：深拷贝
来源：http://dali.havefunace.top/Article/details/gt2ahweivno.html

structuredClone(obj)
来源：http://dali.yuxming.cn/Article/details/gt2gsjnqtlh.html

[U93] JS：模板字符串
来源：http://dali.feifeiyinyue.top/Article/details/gt2xwvnaqca.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gt2xbbpawzg.html

[U94] JS：箭头函数
来源：http://dali.guannengcc.top/Article/details/gt2oryprfsh.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gt2juzvskjq.html

[U95] JS：Promise 包装
来源：http://dali.0kj1m.cn/Article/details/gt2mkfiulgo.html

new Promise((resolve, reject) => {})
来源：http://dali.sysykeji.top/Article/details/gt2vwuiancl.html

[U96] JS：async/await 与异常
来源：http://dali.gogol.net.cn/Article/details/gt2hfazjulf.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sysykeji.top/Article/details/gt2hcwgciyi.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fhxryano.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.wangshuangyany.cn/Article/details/gt2qnzdrsfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.fengsongda.top/Article/details/gt2fwxlwkqj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yvedp.cn/Article/details/gt2tmzrifjk.html

[U99] JS：事件监听
来源：http://dali.tanke756.top/Article/details/gt2wxxqouqq.html

el.addEventListener("click", e => {})
来源：http://dali.hnxiangtu.top/Article/details/gt2eesjgjfk.html

[U100] JS：DOM 查询
来源：http://dali.0kj1m.cn/Article/details/gt2zhspzxfb.html

document.querySelector(".item")
来源：http://dali.zhixingplan.top/Article/details/gt2sqvzavrk.html

[U101] JS：classList 操作
来源：http://dali.hnxiangtu.top/Article/details/gt2bhruxmjb.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qoamqrnz.html

[U102] JS：本地存储
来源：http://dali.yanxiufei.cn/Article/details/gt2gxcbciwg.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.snrcjt.cn/Article/details/gt2yhhcqjpx.html

[U103] JS：定时器
来源：http://dali.daria6918.cn/Article/details/gt2lgmcxnza.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhoulong.xyz/Article/details/gt2agzvommz.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gt2uauustvm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ehwqpu.com/Article/details/gt2ubtytckc.html

[U105] JS：节流
来源：http://dali.tanke756.top/Article/details/gt2zcrazblr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2nwlzjfpn.html

[U106] JS：日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2toczqvxw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.havefunace.top/Article/details/gt2lgrdaiax.html

[U107] JS：数字千分位
来源：http://dali.zycfv.cn/Article/details/gt2xasoqulg.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.c1oappe.top/Article/details/gt2ljozsavy.html

[U108] JS：随机整数
来源：http://dali.yueranfly.top/Article/details/gt2ocypskbw.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxuanxn.top/Article/details/gt2zauwoslx.html

[U109] JS：数组分组
来源：http://dali.havefunace.top/Article/details/gt2jwbcarxw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.jinqigufen.top/Article/details/gt2vzzypeaq.html

[U110] JS：数组分块
来源：http://dali.jianghu66.top/Article/details/gt2qqklwegv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.aizwys.cn/Article/details/gt2iyvxzzmi.html

[U111] JS：对象转 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ywqlyfqo.html

new Map(Object.entries(obj))
来源：http://dali.chenjidiqi.icu/Article/details/gt2ihrahuzb.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gt2ydewkgmo.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gt2wqgpyxdz.html

[U113] JS：正则替换全部
来源：http://dali.cashguo.top/Article/details/gt2skbyxcjw.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2yezziknw.html

[U114] JS：JSON 深比较
来源：http://dali.hammf.cn/Article/details/gt2mszqinwn.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hfpthk.cn/Article/details/gt2vdrxessl.html

[U115] JS：生成 UUID
来源：http://dali.zhoulong.xyz/Article/details/gt2dlvlhdwz.html

crypto.randomUUID()
来源：http://dali.sysykeji.top/Article/details/gt2hqnyopab.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2wqxpedwu.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bnvjytcc.html

[U117] JS：单元测试
来源：http://dali.pengpengdd.cyou/Article/details/gt2emfsdcsz.html

npm i -D vitest;  npx vitest
来源：http://dali.fengsongda.top/Article/details/gt2gvemeomw.html

[U118] JS：开发服务器
来源：http://dali.havefunace.top/Article/details/gt2mbdojvpp.html

npm i -D vite;  npx vite
来源：http://dali.hysaishi.cn/Article/details/gt2ameuophn.html

[U119] JS：生产构建
来源：http://dali.guowangkeji.top/Article/details/gt2gkdtoprb.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gt2mbainwgg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gt2cowmdjlz.html

import.meta.env.VITE_API_URL
来源：http://dali.shuidangran.top/Article/details/gt2lfxlozxm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2disxpenz.html

统计汇总
来源：http://dali.9152youxi.cn/Article/details/gt2neahjjki.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2rfwxpzme.html

按语言统计（条）：
来源：http://dali.chenzaomai.com/Article/details/gt2qscpsblv.html

Python ......... 252
来源：http://dali.vqdsnc.cn/Article/details/gt2uhprgljz.html

PHP ............ 252
来源：http://dali.jinqigfzy.top/Article/details/gt2phntnsud.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gt2eakhpcsq.html

TypeScript ..... 212
来源：http://dali.zhixingplan.top/Article/details/gt2cafaasux.html

Java ........... 212
来源：http://dali.yonumen.top/Article/details/gt2eticnowy.html

Go ............. 212
来源：http://dali.xziqi.cn/Article/details/gt2qtnppgdf.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gt2qbjmuvcd.html

C# ............. 212
来源：http://dali.vqdsnc.cn/Article/details/gt2bfdnrjlp.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gt2bfgwsfaa.html

C++ ............ 30
来源：http://dali.cdnleiting.top/Article/details/gt2sdqlhrsa.html

SQL ............ 90
来源：http://dali.snrcjt.cn/Article/details/gt2ilrgdzrk.html

Bash ........... 80
来源：http://dali.gotoacloud.top/Article/details/gt2ahxbqmbz.html

Kotlin ......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ykwtvqkt.html

Swift .......... 15
来源：http://dali.sxryk.cn/Article/details/gt2xyrduhjq.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gt2stqgwyhc.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gt2pugsvofa.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gt2bqbyywos.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2opcuhxvm.html

合计 ........... 2106 条
来源：http://dali.smart0.xyz/Article/details/gt2sxkvbcpe.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gt2zykvohqj.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hzkamrkf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2nmgpirai.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gt2mwmtblqz.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gt2crvuopgg.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.tianlin.xyz/Article/details/gt2ftcqwdff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yuxming.cn/Article/details/gt2dtiqufbi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gt2zkcpqcpj.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.ehwqpu.com/Article/details/gt2tqnbokyg.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2hrknwozq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jianghu66.top/Article/details/gt2tgdashjs.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2jrwzhuff.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.smart0.xyz/Article/details/gt2xuttnpmb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.xuetiantiany.cn/Article/details/gt2ruqoxsar.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gt2otwblvmf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jianghu66.top/Article/details/gt2dhxhoetw.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxfzwbme.html

Q SQL 专题                              90
来源：http://dali.mhx1999.top/Article/details/gt2conqkmes.html

R Bash 专题                             80
来源：http://dali.haohaochexian.top/Article/details/gt2owjmjofz.html

S C / C++ 专题                          60
来源：http://dali.zhoulong.xyz/Article/details/gt2drhhddvg.html

T 其他语言补充                          60
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlyidfdi.html

U 高频实用片段                         120
来源：http://dali.yj20258888.top/Article/details/gt2pnfhrwkv.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2mijbegxr.html

合计                                  2106 条
来源：http://dali.snrcjt.cn/Article/details/gt2iefhxkwd.html

--------------------------------------------------------------------------------
来源：http://dali.redwolf501.top/Article/details/gt2lzbztvno.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gt2rhyckfas.html

--------------------------------------------------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gt2ijhqwoor.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jiagoushi.top/Article/details/gt2gxnljjut.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rexmgljo.html


<!-- 参考信息 -->