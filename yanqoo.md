代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ydzc1.top/Article/details/gtizaklyob.html

[T59] Scala：循环
来源：http://dali.zhixingplan.top/Article/details/gtkslsehtx.html

for (i <- 1 to 10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtxwfdjidd.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtohajwmfn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.mhx1999.top/Article/details/gttbkrdmdd.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtekewagvm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtwrhjbfjk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtzcmzgaur.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gttilctdeh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.mhx1999.top/Article/details/gtznjgztis.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hysaishi.cn/Article/details/gtzvnkvumw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jqgfzy.top/Article/details/gtimxihzus.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdgaoadta.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yj20258.top/Article/details/gtyapuqscz.html

[U04] Py：变量调试打印
来源：http://dali.meibo888.top/Article/details/gtejdcwhjw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gotoacloud.top/Article/details/gtqkhcojfd.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtgqinoykm.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtesbdyysj.html

[U06] Py：合并两个字典
来源：http://dali.zhengqikj.top/Article/details/gtofkbixwr.html

{**a, **b}
来源：http://dali.shangyingyoupin.top/Article/details/gtsfbxswzr.html

[U07] Py：反转字典键值
来源：http://dali.zhijiandao.cn/Article/details/gtrpxraqiq.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmeldugi.html

[U08] Py：展平二维列表
来源：http://dali.yj202588.top/Article/details/gtrzwowetm.html

[y for x in nested for y in x]
来源：http://dali.bjfxy.top/Article/details/gtslufgbnu.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gtvliocneu.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtkqgyicha.html

[U10] Py：按值排序字典
来源：http://dali.zdqjudy.top/Article/details/gtsjafqhtm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gtoiqtxesk.html

[U11] Py：生成器表达式
来源：http://dali.yonumen.top/Article/details/gtfmxupomq.html

(x * 2 for x in arr)
来源：http://dali.chenjidiqi.icu/Article/details/gtrcdsitfw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jqgufenzy.top/Article/details/gtbojyvwbr.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtvlvtkxdd.html

[U13] Py：固定长度队列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthohnqzbc.html

deque(maxlen=10)
来源：http://dali.ybcxt.top/Article/details/gtgfoisdqf.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtitdjyzjg.html

defaultdict(list)
来源：http://dali.yuxming.cn/Article/details/gtvciivqlc.html

[U15] Py：高精度计时
来源：http://dali.fengsongda.top/Article/details/gtnlzzddyf.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtiwqmtfgx.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gtpsfkrism.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlhnqphi.html

[U17] Py：初始化日志
来源：http://dali.0kj1m.cn/Article/details/gthiwcmzsv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ivvv.top/Article/details/gtlrinimxu.html

[U18] Py：预编译正则
来源：http://dali.gogol.net.cn/Article/details/gtyzxvsbfy.html

pat = re.compile(r"\d+")
来源：http://dali.snrcjt.cn/Article/details/gtmktzchqi.html

[U19] Py：正则替换带回调
来源：http://dali.hnxiangtu.top/Article/details/gtqskauhih.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zycfv.cn/Article/details/gtguepxasq.html

[U20] Py：缓存函数结果
来源：http://dali.hfpthk.cn/Article/details/gtxnlhnxjy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shzxlz.cn/Article/details/gtvvjalhow.html

[U21] Py：自定义上下文管理器
来源：http://dali.cheryme.top/Article/details/gtwzwdhjej.html

@contextlib.contextmanager
来源：http://dali.jiagoushi.top/Article/details/gtlsdqtqwp.html

[U22] Py：矩阵转置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvaqosqgn.html

list(zip(*m))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaocxwnau.html

[U23] Py：分块读取大文件
来源：http://dali.yj20258888.top/Article/details/gtnziekufq.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhijiandao.cn/Article/details/gtnhsfedit.html

[U24] Py：路径操作
来源：http://dali.xylfe.cn/Article/details/gtajwumfwh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yuxming.cn/Article/details/gtjgswwqix.html

[U25] Py：CSV 按字典读
来源：http://dali.sweek.top/Article/details/gtonnmdmmy.html

csv.DictReader(f)
来源：http://dali.shzxlz.cn/Article/details/gtcfuxutqe.html

[U26] Py：并发下载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtorqzlena.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gtijeqsmpx.html

[U27] Py：异步 HTTP
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxfbqcav.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.zhijiandao.cn/Article/details/gtahsrmvcn.html

[U28] Py：类型别名
来源：http://dali.wangdashe.top/Article/details/gtrubkwjhh.html

UserId = int
来源：http://dali.yueranfly.top/Article/details/gtzuklzvqs.html

[U29] Py：属性校验
来源：http://dali.gaohongyu789.top/Article/details/gtjlljzico.html

@property 与 @x.setter 配合
来源：http://dali.feifeiyinyue.top/Article/details/gtcmcjxguj.html

[U30] Py：数据类
来源：http://dali.dianchejie.cn/Article/details/gtxvakzyuz.html

@dataclass(slots=True)
来源：http://dali.xziqi.cn/Article/details/gtpoxidtvn.html

[U31] Py：单测
来源：http://dali.aizwys.cn/Article/details/gtkoquuqdl.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gtgbfkgxry.html

[U32] Py：代码格式化
来源：http://dali.yongpay.top/Article/details/gtftirfwql.html

ruff format . && ruff check --fix .
来源：http://dali.ppjwa.cn/Article/details/gthizguscq.html

[U33] Py：打包发布
来源：http://dali.daxiang520.top/Article/details/gtupevoohd.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gotoacloud.top/Article/details/gtoujapixy.html

[U34] Py：判断编码
来源：http://dali.jqgufenzy.top/Article/details/gtagozvrna.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixubmwef.html

[U35] Py：发送邮件
来源：http://dali.hammf.cn/Article/details/gthikrfjpk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gogol.net.cn/Article/details/gtmnullrzq.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtfkhaaetf.html

schedule.every(10).minutes.do(job)
来源：http://dali.ehwqpu.com/Article/details/gtatctpxeo.html

[U37] Py：读写 Excel
来源：http://dali.guowangkeji.top/Article/details/gtchydruoe.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gtiteoqiqq.html

[U38] Py：获取脚本所在目录
来源：http://dali.chenjidiqi.icu/Article/details/gtzgwiwxze.html

Path(__file__).resolve().parent
来源：http://dali.gotoacloud.top/Article/details/gtbolifpca.html

[U39] Py：判断是否在交互环境
来源：http://dali.jyoumei.cn/Article/details/gtbnyrwxqo.html

sys.stdout.isatty()
来源：http://dali.tanke756.top/Article/details/gtuyiygegv.html

[U40] Py：打印到标准错误
来源：http://dali.zhongyouzk.top/Article/details/gtpgvpmdzk.html

print("err", file=sys.stderr)
来源：http://dali.zdqjudy.top/Article/details/gtugyyegxh.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.redwolf501.top/Article/details/gtfyeuvrkd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.dianchejie.cn/Article/details/gtmlpypxuc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigfzy.top/Article/details/gtliwehcvi.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gtleeqodxo.html

[U43] PHP：声明命名空间
来源：http://dali.zhiwuduotai.top/Article/details/gtsdycsgnf.html

namespace App\Http;
来源：http://dali.hammf.cn/Article/details/gtgaadcfdc.html

[U44] PHP：开启严格类型
来源：http://dali.sufxvd.cn/Article/details/gtskmdflwi.html

declare(strict_types=1);
来源：http://dali.jiagoushi.top/Article/details/gtxvrctegr.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shangyingyoupin.top/Article/details/gtbcbsesfz.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtjgmsczyn.html

[U46] PHP：可空类型
来源：http://dali.hnxiangtu.top/Article/details/gtmmnkoqwj.html

?string $name = null
来源：http://dali.shuidangran.top/Article/details/gtlwgyjqgn.html

[U47] PHP：联合类型
来源：http://dali.xuetiantiany.cn/Article/details/gtwfejkmyu.html

int|string $id
来源：http://dali.hysaishi.cn/Article/details/gtvdsfnjey.html

[U48] PHP：纯枚举
来源：http://dali.yj20258888.top/Article/details/gtbuthcvxo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtceaqvkhc.html

[U49] PHP：只读属性
来源：http://dali.jqgfzy.top/Article/details/gtofhclbny.html

public readonly string $name
来源：http://dali.xylfe.cn/Article/details/gtdnxitngg.html

[U50] PHP：构造器属性提升
来源：http://dali.ybcxt.top/Article/details/gthmlbhlnt.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtsgywoiht.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gtizogrjma.html

[$a, $b] = $arr;
来源：http://dali.sysykeji.top/Article/details/gtxklbimkr.html

[U52] PHP：箭头函数
来源：http://dali.iojbl.cn/Article/details/gtisoepief.html

$double = fn($x) => $x * 2;
来源：http://dali.jinghuilouyu.cn/Article/details/gtwsfncgnp.html

[U53] PHP：空合并运算符
来源：http://dali.gzhubu.top/Article/details/gtbxvllqrl.html

$v = $a ?? $b ?? "default";
来源：http://dali.cheryme.top/Article/details/gtjksflfwm.html

[U54] PHP：空安全调用
来源：http://dali.smart0.xyz/Article/details/gtkglzakre.html

$obj?->method()
来源：http://dali.yj20258.top/Article/details/gtnjhdwhad.html

[U55] PHP：match 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtijgbvuwb.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yuxming.cn/Article/details/gtiiovyejz.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gtnmfrlgmk.html

f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtngfbqqzd.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtdofdjvys.html

"值: {$a}"
来源：http://dali.redwolf501.top/Article/details/gtmdckdasl.html

[U58] PHP：数组三件套
来源：http://dali.cdnleiting.top/Article/details/gtvnpoafha.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aibaodan.cn/Article/details/gtbpsckyqt.html

[U59] PHP：自定义排序
来源：http://dali.hnxiangtu.top/Article/details/gtemhbpyuq.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.zycfv.cn/Article/details/gtwucgjryk.html

[U60] PHP：JSON 编解码
来源：http://dali.yanxiufei.cn/Article/details/gtlntbmsvf.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yonumen.top/Article/details/gtmkrjdwch.html

[U61] PHP：正则
来源：http://dali.aizwys.cn/Article/details/gtyhznmqpe.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.vqdsnc.cn/Article/details/gtlanhkbny.html

[U62] PHP：日期对象
来源：http://dali.jlsjyb.cn/Article/details/gtsrgfsozx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwipfoumc.html

[U63] PHP：文件读写
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlcoygpnn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.svipenyu.cn/Article/details/gtpocyyqgh.html

[U64] PHP：目录遍历
来源：http://dali.aibaodan.cn/Article/details/gtulvgmkuo.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgianopw.html

[U65] PHP：会话
来源：http://dali.xylfe.cn/Article/details/gtqrdbgkxf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtqkvqdvgn.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gttdjnhtqq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daxiang520.top/Article/details/gttlwhabrb.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gtiwwgpnnd.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.guannengcc.top/Article/details/gtuqeobwil.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtvczxywir.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.vqdsnc.cn/Article/details/gtpozdaire.html

[U69] PHP：PDO 预处理
来源：http://dali.shuidangran.top/Article/details/gtfknpnduc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.c1oappe.top/Article/details/gtubbotlaf.html

[U70] PHP：PDO 事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfzngmyjn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zycfv.cn/Article/details/gtdinljggh.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gthoaopjds.html

throw new RuntimeException("失败", 500);
来源：http://dali.sxryk.cn/Article/details/gtdqleuzwp.html

[U72] PHP：写错误日志
来源：http://dali.quarkkingdee.top/Article/details/gtkyagnmwm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hammf.cn/Article/details/gttpktcisy.html

[U73] PHP：读取 ini 配置
来源：http://dali.nanxuanxn.top/Article/details/gtjcwjtpbo.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtdpkxikot.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gtozxizrns.html

getenv("APP_ENV") ?: "production"
来源：http://dali.snrcjt.cn/Article/details/gtxuewzawv.html

[U75] PHP：依赖注入
来源：http://dali.guowangkeji.top/Article/details/gtlqhiybzh.html

composer require psr/container
来源：http://dali.nwbrower.top/Article/details/gtcjlobzir.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtdqzkvelp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhoulong.xyz/Article/details/gtuzcjxzeg.html

[U77] PHP：模板渲染
来源：http://dali.shzxlz.cn/Article/details/gtxijqvtao.html

composer require twig/twig
来源：http://dali.jlsjyb.cn/Article/details/gtirhfqarq.html

[U78] PHP：单元测试
来源：http://dali.zhixingplan.top/Article/details/gtkxivsste.html

composer require --dev phpunit/phpunit
来源：http://dali.havefunace.top/Article/details/gthidvwofx.html

[U79] PHP：静态分析
来源：http://dali.fengsongda.top/Article/details/gtwykzvgqp.html

composer require --dev phpstan/phpstan
来源：http://dali.dashuyun.cn/Article/details/gthnvkgjbl.html

[U80] PHP：代码规范修复
来源：http://dali.jinghuilouyu.cn/Article/details/gtucfaodgx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yj20258.top/Article/details/gtqtnpuzgu.html

[U81] JS：初始化项目
来源：http://dali.gotoacloud.top/Article/details/gtrriqadyr.html

npm init -y;  npm i express
来源：http://dali.c1oappe.top/Article/details/gtqygweibf.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtjrnrqetm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.chenjidiqi.icu/Article/details/gtfwmccdjm.html

[U83] JS：ES Module 导入导出
来源：http://dali.yvedp.cn/Article/details/gtnbuknefq.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gtjvsfkiqo.html

[U84] JS：CommonJS 写法
来源：http://dali.gaohongyu789.top/Article/details/gtlxxidgfq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xziqi.cn/Article/details/gtklvxiaeg.html

[U85] JS：可选链
来源：http://dali.quarkkingdee.top/Article/details/gtsurxaktt.html

a?.b?.c
来源：http://dali.jlsjyb.cn/Article/details/gthwenimjf.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gtgrkwmngd.html

a ?? b
来源：http://dali.yanxiufei.cn/Article/details/gttszrvpfa.html

[U87] JS：解构默认值
来源：http://dali.mhx1999.top/Article/details/gtirrbrhjh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnksgpzg.html

[U88] JS：对象展开合并
来源：http://dali.hnqzz.top/Article/details/gtyojvgtdr.html

{ ...a, ...b }
来源：http://dali.chenzaomai.com/Article/details/gtixxjrixp.html

[U89] JS：数组去重
来源：http://dali.sufxvd.cn/Article/details/gtqaafmwmo.html

[...new Set(arr)]
来源：http://dali.feifeiyinyue.top/Article/details/gtbgltuwck.html

[U90] JS：数字数组排序
来源：http://dali.gogol.net.cn/Article/details/gtgrfukvtw.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvijhlgv.html

[U91] JS：对象键值遍历
来源：http://dali.zdqjudy.top/Article/details/gtrrjhgqdb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.daria6918.cn/Article/details/gtppetzbze.html

[U92] JS：深拷贝
来源：http://dali.yanxiufei.cn/Article/details/gttufqywnq.html

structuredClone(obj)
来源：http://dali.cqqwz.cn/Article/details/gtvnbceddg.html

[U93] JS：模板字符串
来源：http://dali.haohaochexian.top/Article/details/gtvbahyzwb.html

`共 ${n} 条`
来源：http://dali.jiagoushi.top/Article/details/gtuijdcbyi.html

[U94] JS：箭头函数
来源：http://dali.sufxvd.cn/Article/details/gtbgkjvltt.html

const double = x => x * 2;
来源：http://dali.jqgfzy.top/Article/details/gtnjhuovca.html

[U95] JS：Promise 包装
来源：http://dali.zhengqikj.top/Article/details/gtdsccbfei.html

new Promise((resolve, reject) => {})
来源：http://dali.aizwys.cn/Article/details/gtpgmbezpv.html

[U96] JS：async/await 与异常
来源：http://dali.snrcjt.cn/Article/details/gttxnfzlnl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.sufxvd.cn/Article/details/gtpqgfbqzg.html

[U97] JS：并发请求
来源：http://dali.tianlin.xyz/Article/details/gtdlqcjzkh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgfzy.top/Article/details/gtdgckglmq.html

[U98] JS：fetch 带 JSON
来源：http://dali.aizwys.cn/Article/details/gtvkqeliyh.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.316326.xyz/Article/details/gtrxrsqlgm.html

[U99] JS：事件监听
来源：http://dali.pycfn.com/Article/details/gtdooxekyz.html

el.addEventListener("click", e => {})
来源：http://dali.jlsjyb.cn/Article/details/gtnocltcfm.html

[U100] JS：DOM 查询
来源：http://dali.shuidangran.top/Article/details/gtwqizvewv.html

document.querySelector(".item")
来源：http://dali.hywenlv.cn/Article/details/gtkvcwwvpr.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gtzmgkhnrb.html

el.classList.toggle("active")
来源：http://dali.zhiwuduotai.top/Article/details/gtdiqkqczs.html

[U102] JS：本地存储
来源：http://dali.hnxiangtu.top/Article/details/gtfnhantgt.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.dianchejie.cn/Article/details/gtgisesmph.html

[U103] JS：定时器
来源：http://dali.ydzc1.top/Article/details/gtwfrgsotx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.wangshuangyany.cn/Article/details/gtuiqrcero.html

[U104] JS：防抖
来源：http://dali.hnqzz.top/Article/details/gtjrfkvafo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sweek.top/Article/details/gtzhzjjcsx.html

[U105] JS：节流
来源：http://dali.cashguo.top/Article/details/gtpbieztvr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.wangdashe.top/Article/details/gtbdmjoiqw.html

[U106] JS：日期格式化
来源：http://dali.ivvv.top/Article/details/gtfdqlvngu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yvedp.cn/Article/details/gtnpvffxix.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtldtmxebx.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtkbygvbyg.html

[U108] JS：随机整数
来源：http://dali.jiagoushi.top/Article/details/gtngxrwrlu.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhengqikj.top/Article/details/gtkuclapey.html

[U109] JS：数组分组
来源：http://dali.kuanghao11.cn/Article/details/gtkahfzwwo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtdfvfgbes.html

[U110] JS：数组分块
来源：http://dali.iojbl.cn/Article/details/gtrnqvysuw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.ppjwa.cn/Article/details/gtealrvehr.html

[U111] JS：对象转 Map
来源：http://dali.redwolf501.top/Article/details/gtnhiqqffv.html

new Map(Object.entries(obj))
来源：http://dali.dashuyun.cn/Article/details/gtnghwiuvd.html

[U112] JS：字符串补位
来源：http://dali.zhongyouzk.top/Article/details/gtidysovwv.html

"7".padStart(3, "0")
来源：http://dali.cqqwz.cn/Article/details/gtyuylgkyd.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gttyngjthj.html

s.replaceAll("a", "b")
来源：http://dali.xuanzx.com/Article/details/gtrxfbjpyl.html

[U114] JS：JSON 深比较
来源：http://dali.yj202588.top/Article/details/gtyijnqvhk.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.feifeiyinyue.top/Article/details/gthsyrfoue.html

[U115] JS：生成 UUID
来源：http://dali.daxiang520.top/Article/details/gtsroddoum.html

crypto.randomUUID()
来源：http://dali.aizwys.cn/Article/details/gtyqgmpurf.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yvedp.cn/Article/details/gtxwkhglkx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.fzhhl.top/Article/details/gtewksgchc.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gtezajcikm.html

npm i -D vitest;  npx vitest
来源：http://dali.yuxming.cn/Article/details/gtvccckmtg.html

[U118] JS：开发服务器
来源：http://dali.pycfn.com/Article/details/gtqeqtebzm.html

npm i -D vite;  npx vite
来源：http://dali.svipenyu.cn/Article/details/gtqboszmbw.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gtxaqpqpqh.html

npx vite build
来源：http://dali.jyoumei.cn/Article/details/gtticfiydn.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.vqdsnc.cn/Article/details/gtqhjgovuo.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gtavopmynm.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtlrrgrdnt.html

统计汇总
来源：http://dali.xuetiantiany.cn/Article/details/gtmuznhyal.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtidapyqvb.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gtwhhpbskc.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhbhwufk.html

PHP ............ 252
来源：http://dali.yuanzhike.top/Article/details/gthrccytgp.html

JavaScript ..... 252
来源：http://dali.tian-w.cn/Article/details/gtecgdqutw.html

TypeScript ..... 212
来源：http://dali.yj202588.top/Article/details/gtflvccuyv.html

Java ........... 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gttvypyhxx.html

Go ............. 212
来源：http://dali.ydzc1.top/Article/details/gtivkerhso.html

Ruby ........... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gteixhhcwb.html

C# ............. 212
来源：http://dali.xinyue.icu/Article/details/gthancjbov.html

C .............. 30
来源：http://dali.yvedp.cn/Article/details/gtzgkvhqau.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddfgvlpy.html

SQL ............ 90
来源：http://dali.xuanzx.com/Article/details/gtrlzidprf.html

Bash ........... 80
来源：http://dali.jinqigfzy.top/Article/details/gtgpppiocs.html

Kotlin ......... 15
来源：http://dali.xinyue.icu/Article/details/gtefdtjhnl.html

Swift .......... 15
来源：http://dali.cashguo.top/Article/details/gtohsrensh.html

Lua ............ 10
来源：http://dali.hywenlv.cn/Article/details/gtnxzrxlbl.html

Perl ........... 10
来源：http://dali.cucudq.cn/Article/details/gtmmrkeggs.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gtdwjddpfv.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtnufkxtti.html

合计 ........... 2106 条
来源：http://dali.tian-w.cn/Article/details/gtsjmaasas.html

按章节统计：
来源：http://dali.daria6918.cn/Article/details/gttjwfnsqu.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtyjefirre.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jiagoushi.top/Article/details/gtttrqhryr.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gogol.net.cn/Article/details/gthpdiyvfn.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ehwqpu.com/Article/details/gtwmjqxang.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.hnqzz.top/Article/details/gtpqcgqjlp.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.fzhhl.top/Article/details/gtrjkyqpil.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.sufxvd.cn/Article/details/gtonbdtbds.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gtqfszkvls.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gtybhssgyq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.snrcjt.cn/Article/details/gtawioqsru.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtllhfmiqu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtljadzmnl.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hfpthk.cn/Article/details/gtyevhnwno.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.fengsongda.top/Article/details/gtuelhlmzb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxwcnexa.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.xylfe.cn/Article/details/gtejzhbiuq.html

Q SQL 专题                              90
来源：http://dali.dianchejie.cn/Article/details/gtwcsagqcg.html

R Bash 专题                             80
来源：http://dali.zhixingplan.top/Article/details/gtnsaaukof.html

S C / C++ 专题                          60
来源：http://dali.gaohongyu789.top/Article/details/gtlskyyjwz.html

T 其他语言补充                          60
来源：http://dali.yvedp.cn/Article/details/gtzfovavuz.html

U 高频实用片段                         120
来源：http://dali.yuanzhike.top/Article/details/gtxnmvcjxp.html

------------------------------------
来源：http://dali.zhongyouzk.top/Article/details/gtkfdmvbsc.html

合计                                  2106 条
来源：http://dali.hysaishi.cn/Article/details/gtxhzogddb.html

--------------------------------------------------------------------------------
来源：http://dali.pycfn.com/Article/details/gtbdkizzny.html

使用提醒
来源：http://dali.0kj1m.cn/Article/details/gtixfwunou.html

--------------------------------------------------------------------------------
来源：http://dali.tianlin.xyz/Article/details/gtllcsxqtb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yangfankeji.com/Article/details/gtmaaaolnk.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.zdqjudy.top/Article/details/gtbaqaubrt.html


<!-- 参考信息 -->