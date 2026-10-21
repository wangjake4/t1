代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtiflnbhja.html

[T55] Scala：集合过滤
来源：http://dali.hammf.cn/Article/details/gthmdiekii.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtojbfulzr.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gtsblakdaj.html

case class User(name: String, age: Int)
来源：http://dali.jiagoushi.top/Article/details/gtsqlqfmns.html

[T57] Scala：模式匹配
来源：http://dali.snrcjt.cn/Article/details/gtemeeipir.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhsfsimk.html

[T58] Scala：函数定义
来源：http://dali.jqgfzy.top/Article/details/gtyxweltxn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgehvwqo.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzmuwphu.html

for (i <- 1 to 10) println(i)
来源：http://dali.gogol.net.cn/Article/details/gtgvnhhhfx.html

[T60] Scala：折叠
来源：http://dali.yj20258.top/Article/details/gtxhdovufi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hfpthk.cn/Article/details/gtadnfxcft.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtrplythpf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nwbrower.top/Article/details/gtqvdglpyi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtamhqeyia.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtxryxjtro.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.9152youxi.cn/Article/details/gttaftmzda.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhijiandao.cn/Article/details/gtaojaamwt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdittcbn.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtbwlihlwv.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.hysaishi.cn/Article/details/gtnygdqgvk.html

[U04] Py：变量调试打印
来源：http://dali.haohaochexian.top/Article/details/gtcdpltobp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gtzyurywvl.html

[U05] Py：列表去重且保序
来源：http://dali.yuanzhike.top/Article/details/gtoslhtcnn.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gtchpgworc.html

[U06] Py：合并两个字典
来源：http://dali.xziqi.cn/Article/details/gtwwlqdldi.html

{**a, **b}
来源：http://dali.gaohongyu789.top/Article/details/gtacdwjnuk.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtpfwjrxyu.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gtfwgubpwx.html

[U08] Py：展平二维列表
来源：http://dali.haohaochexian.top/Article/details/gtbibgiofu.html

[y for x in nested for y in x]
来源：http://dali.jinqigfzy.top/Article/details/gtnndfdipt.html

[U09] Py：字典取最大值的键
来源：http://dali.hfpthk.cn/Article/details/gtzwikcjjb.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gthzwjeesa.html

[U10] Py：按值排序字典
来源：http://dali.zhiwuduotai.top/Article/details/gtbmqfckbk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xinyue.icu/Article/details/gtrzronrgu.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gtgchslebr.html

(x * 2 for x in arr)
来源：http://dali.wangdashe.top/Article/details/gtkgnczinh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhoulong.xyz/Article/details/gtbsxrylzz.html

Counter(arr).most_common(3)
来源：http://dali.zhoulong.xyz/Article/details/gtpfisuzan.html

[U13] Py：固定长度队列
来源：http://dali.hongshengwenyu.top/Article/details/gtbmhynwmy.html

deque(maxlen=10)
来源：http://dali.jlsjyb.cn/Article/details/gtwnrpktvd.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjaqbskt.html

defaultdict(list)
来源：http://dali.sxryk.cn/Article/details/gtjkkdolbf.html

[U15] Py：高精度计时
来源：http://dali.andypj.xyz/Article/details/gtcbvhqdew.html

t = time.perf_counter()
来源：http://dali.yvedp.cn/Article/details/gtgnygpsfc.html

[U16] Py：命令行参数解析
来源：http://dali.quarkkingdee.top/Article/details/gtdttwtoid.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.nwbrower.top/Article/details/gtlgfnjphu.html

[U17] Py：初始化日志
来源：http://dali.yonumen.top/Article/details/gtufqnlomd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.tanke756.top/Article/details/gtvinaugpb.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gtkdggenrj.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtpqsrdlty.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gtvqdmkytd.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhixingplan.top/Article/details/gtfodgbhvd.html

[U20] Py：缓存函数结果
来源：http://dali.havefunace.top/Article/details/gtpozkztyv.html

@functools.lru_cache(maxsize=None)
来源：http://dali.9152youxi.cn/Article/details/gthpplyhmu.html

[U21] Py：自定义上下文管理器
来源：http://dali.hongshengwenyu.top/Article/details/gtptxlvmzy.html

@contextlib.contextmanager
来源：http://dali.yj20258.top/Article/details/gtvdndkqss.html

[U22] Py：矩阵转置
来源：http://dali.zhijiandao.cn/Article/details/gtgglpcxmz.html

list(zip(*m))
来源：http://dali.sysykeji.top/Article/details/gtpxhcbbzc.html

[U23] Py：分块读取大文件
来源：http://dali.hongshengwenyu.top/Article/details/gtnrpfzlzz.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwrsudejt.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gtoirhjpre.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.hnxiangtu.top/Article/details/gtwqhmfkgc.html

[U25] Py：CSV 按字典读
来源：http://dali.0kj1m.cn/Article/details/gtfpqrrqup.html

csv.DictReader(f)
来源：http://dali.yangfankeji.com/Article/details/gtdzhnyoki.html

[U26] Py：并发下载
来源：http://dali.gzhubu.top/Article/details/gtigkupgyd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.wangdashe.top/Article/details/gtqneqeice.html

[U27] Py：异步 HTTP
来源：http://dali.wangshuangyany.cn/Article/details/gtmkqopcjm.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtgwhsoacm.html

[U28] Py：类型别名
来源：http://dali.yvedp.cn/Article/details/gtbooiyljo.html

UserId = int
来源：http://dali.xuetiantiany.cn/Article/details/gtmaijuton.html

[U29] Py：属性校验
来源：http://dali.zhijiandao.cn/Article/details/gtbhmbrcht.html

@property 与 @x.setter 配合
来源：http://dali.bjfxy.top/Article/details/gtxfmiwyqy.html

[U30] Py：数据类
来源：http://dali.yvedp.cn/Article/details/gtlvmsghyt.html

@dataclass(slots=True)
来源：http://dali.jqgfzy.top/Article/details/gtqolwhxyu.html

[U31] Py：单测
来源：http://dali.cdnleiting.top/Article/details/gtjpbdbuad.html

python -m pytest -q
来源：http://dali.nanxuanxn.top/Article/details/gtawzivude.html

[U32] Py：代码格式化
来源：http://dali.hammf.cn/Article/details/gtrpqqihyn.html

ruff format . && ruff check --fix .
来源：http://dali.hongshengwenyu.top/Article/details/gtcacahogt.html

[U33] Py：打包发布
来源：http://dali.xziqi.cn/Article/details/gtindqjwxv.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cqqwz.cn/Article/details/gtdermqchb.html

[U34] Py：判断编码
来源：http://dali.nanxinkj.top/Article/details/gtzsdvlijn.html

chardet.detect(raw)
来源：http://dali.svipenyu.cn/Article/details/gtwwshofcs.html

[U35] Py：发送邮件
来源：http://dali.jlsjyb.cn/Article/details/gtpcumbxve.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.aizwys.cn/Article/details/gtnxlorbhc.html

[U36] Py：定时任务
来源：http://dali.birdmap.top/Article/details/gtwvaneenz.html

schedule.every(10).minutes.do(job)
来源：http://dali.xziqi.cn/Article/details/gtfbudymtu.html

[U37] Py：读写 Excel
来源：http://dali.pycfn.com/Article/details/gtkrhystsl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.gaohongyu789.top/Article/details/gtnffqsxab.html

[U38] Py：获取脚本所在目录
来源：http://dali.kuanghao11.cn/Article/details/gtixqbophi.html

Path(__file__).resolve().parent
来源：http://dali.zhongyouzk.top/Article/details/gtqrbudzqk.html

[U39] Py：判断是否在交互环境
来源：http://dali.0kj1m.cn/Article/details/gtjqwzbqqs.html

sys.stdout.isatty()
来源：http://dali.dashuyun.cn/Article/details/gtxelvicgd.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gtsykxefpq.html

print("err", file=sys.stderr)
来源：http://dali.aizwys.cn/Article/details/gtixxcujnt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.pengpengdd.cyou/Article/details/gtqrafvpsd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.jqgufenzy.top/Article/details/gtcesltuad.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.tianlin.xyz/Article/details/gtuedkmeck.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.dashuyun.cn/Article/details/gtpzvgtiqz.html

[U43] PHP：声明命名空间
来源：http://dali.zhongyouzk.top/Article/details/gtwdovacic.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtkpgxtfbj.html

[U44] PHP：开启严格类型
来源：http://dali.zhengqikj.top/Article/details/gtedzqzzba.html

declare(strict_types=1);
来源：http://dali.ehwqpu.com/Article/details/gtyguvbucu.html

[U45] PHP：类型声明与返回类型
来源：http://dali.xylfe.cn/Article/details/gtpbvknvnf.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtxremxzli.html

[U46] PHP：可空类型
来源：http://dali.tianlin.xyz/Article/details/gtvdvxbytz.html

?string $name = null
来源：http://dali.guowangkeji.top/Article/details/gtwttwrrmi.html

[U47] PHP：联合类型
来源：http://dali.yj20258.top/Article/details/gtqompyiij.html

int|string $id
来源：http://dali.zhixingplan.top/Article/details/gtmztmqpoj.html

[U48] PHP：纯枚举
来源：http://dali.jinqigfzy.top/Article/details/gtkjnxnomo.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.andypj.xyz/Article/details/gtrgsrusxw.html

[U49] PHP：只读属性
来源：http://dali.feifeiyinyue.top/Article/details/gtttkgihst.html

public readonly string $name
来源：http://dali.yonumen.top/Article/details/gtdscjmkfq.html

[U50] PHP：构造器属性提升
来源：http://dali.hammf.cn/Article/details/gtutumpdry.html

public function __construct(private int $id) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtvzjtdkgl.html

[U51] PHP：数组解构
来源：http://dali.zhixingplan.top/Article/details/gtnokgteke.html

[$a, $b] = $arr;
来源：http://dali.316326.xyz/Article/details/gtcsvjtehz.html

[U52] PHP：箭头函数
来源：http://dali.feifeiyinyue.top/Article/details/gtascfmdxh.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gtsvvbvqjn.html

[U53] PHP：空合并运算符
来源：http://dali.chenzaomai.com/Article/details/gtdwacqyjk.html

$v = $a ?? $b ?? "default";
来源：http://dali.wangdashe.top/Article/details/gtfrgqshqx.html

[U54] PHP：空安全调用
来源：http://dali.hywenlv.cn/Article/details/gtibrgaokx.html

$obj?->method()
来源：http://dali.fzhhl.top/Article/details/gtgsidhnsg.html

[U55] PHP：match 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtscyligbh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gtexkuplld.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gtzxbdwofe.html

f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gttdptjplo.html

[U57] PHP：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtjybwfcej.html

"值: {$a}"
来源：http://dali.smart0.xyz/Article/details/gtwevsumtm.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gtsxtjozmb.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.tian-w.cn/Article/details/gtxmsvgywj.html

[U59] PHP：自定义排序
来源：http://dali.jyoumei.cn/Article/details/gtgyjkznzy.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.guowangkeji.top/Article/details/gtbzdsrleg.html

[U60] PHP：JSON 编解码
来源：http://dali.xylfe.cn/Article/details/gticdffnfe.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.gaohongyu789.top/Article/details/gtmwncpvpu.html

[U61] PHP：正则
来源：http://dali.birdmap.top/Article/details/gtmfykvdcn.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gtreqqnrsq.html

[U62] PHP：日期对象
来源：http://dali.vqdsnc.cn/Article/details/gtfbzownku.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.9152youxi.cn/Article/details/gtlmecgxxd.html

[U63] PHP：文件读写
来源：http://dali.zhijiandao.cn/Article/details/gtqsexxdfh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.hammf.cn/Article/details/gtfeqixwzk.html

[U64] PHP：目录遍历
来源：http://dali.ehwqpu.com/Article/details/gtjbrphefd.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yj202588.top/Article/details/gtxabygnkf.html

[U65] PHP：会话
来源：http://dali.zhoulong.xyz/Article/details/gtoukuzhgp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtmmwbrtrh.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gtztvfmyhg.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.0kj1m.cn/Article/details/gttgligenq.html

[U67] PHP：处理文件上传
来源：http://dali.cheryme.top/Article/details/gtnufdpdnm.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhiwuduotai.top/Article/details/gtvudmwxre.html

[U68] PHP：PDO 连接
来源：http://dali.xuanzx.com/Article/details/gtoackrekn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gtxccqddvd.html

[U69] PHP：PDO 预处理
来源：http://dali.xuetiantiany.cn/Article/details/gttjjcbgpc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sufxvd.cn/Article/details/gtxiuqrgyn.html

[U70] PHP：PDO 事务
来源：http://dali.c1oappe.top/Article/details/gtemevbykr.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yuanzhike.top/Article/details/gtyeupnsnk.html

[U71] PHP：抛出异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbsftcnft.html

throw new RuntimeException("失败", 500);
来源：http://dali.yuanzhike.top/Article/details/gtgdjgpstt.html

[U72] PHP：写错误日志
来源：http://dali.ydzc1.top/Article/details/gtavaoigdd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gtmjwhszwx.html

[U73] PHP：读取 ini 配置
来源：http://dali.dashuyun.cn/Article/details/gtwpqkxayy.html

parse_ini_file("config.ini", true)
来源：http://dali.tanke756.top/Article/details/gtrimdudjf.html

[U74] PHP：读取环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopvnfqvp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.mhx1999.top/Article/details/gttgjhrcab.html

[U75] PHP：依赖注入
来源：http://dali.0kj1m.cn/Article/details/gtoayrofdw.html

composer require psr/container
来源：http://dali.hfpthk.cn/Article/details/gtmegbjmxu.html

[U76] PHP：简单路由
来源：http://dali.jqgufenzy.top/Article/details/gthadejxqv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.redwolf501.top/Article/details/gtbnhdpzxc.html

[U77] PHP：模板渲染
来源：http://dali.sufxvd.cn/Article/details/gtfdkyphso.html

composer require twig/twig
来源：http://dali.zhoulong.xyz/Article/details/gtszyscidn.html

[U78] PHP：单元测试
来源：http://dali.cdnleiting.top/Article/details/gtdsswnqeo.html

composer require --dev phpunit/phpunit
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkttrwdab.html

[U79] PHP：静态分析
来源：http://dali.cucudq.cn/Article/details/gtbiypirmp.html

composer require --dev phpstan/phpstan
来源：http://dali.bjfxy.top/Article/details/gtrsxtyxqx.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangtech.top/Article/details/gtbobyfrmz.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.jinqigfzy.top/Article/details/gtebjyumzx.html

[U81] JS：初始化项目
来源：http://dali.wangdashe.top/Article/details/gtypiyicax.html

npm init -y;  npm i express
来源：http://dali.redwolf501.top/Article/details/gtthjvfhgp.html

[U82] JS：package.json 脚本
来源：http://dali.cdnleiting.top/Article/details/gtnxkpuzbr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.fengsongda.top/Article/details/gtkeibfyck.html

[U83] JS：ES Module 导入导出
来源：http://dali.bjfxy.top/Article/details/gtilkixxap.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.redwolf501.top/Article/details/gtplpwamww.html

[U84] JS：CommonJS 写法
来源：http://dali.pengpengdd.cyou/Article/details/gtgzegokyb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gtgidxtsiq.html

[U85] JS：可选链
来源：http://dali.cheryme.top/Article/details/gtlcbxeznk.html

a?.b?.c
来源：http://dali.ybcxt.top/Article/details/gtwdbiahje.html

[U86] JS：空值合并
来源：http://dali.sysykeji.top/Article/details/gtogyvmiup.html

a ?? b
来源：http://dali.xziqi.cn/Article/details/gtuaguhjig.html

[U87] JS：解构默认值
来源：http://dali.jqgfzy.top/Article/details/gtfvogvnkz.html

const { a = 1, b = 2 } = obj;
来源：http://dali.tanke756.top/Article/details/gtujrmrdnw.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtrgltyijb.html

{ ...a, ...b }
来源：http://dali.yueranfly.top/Article/details/gtqelarwxx.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtducvxymp.html

[...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gtwjwuvjgt.html

[U90] JS：数字数组排序
来源：http://dali.snrcjt.cn/Article/details/gtiwyzqruu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.yonumen.top/Article/details/gtsuqnklcl.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gtixdgrwnq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvawtiud.html

[U92] JS：深拷贝
来源：http://dali.gzhubu.top/Article/details/gtrradmduu.html

structuredClone(obj)
来源：http://dali.sxryk.cn/Article/details/gtcoquimyk.html

[U93] JS：模板字符串
来源：http://dali.cashguo.top/Article/details/gtyxcoangg.html

`共 ${n} 条`
来源：http://dali.jinqigufen.top/Article/details/gtnsknbsav.html

[U94] JS：箭头函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuheetndr.html

const double = x => x * 2;
来源：http://dali.yanxiufei.cn/Article/details/gtrkqwljqo.html

[U95] JS：Promise 包装
来源：http://dali.yangfankeji.com/Article/details/gtxozjzevq.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gtzlxxjceq.html

[U96] JS：async/await 与异常
来源：http://dali.aizwys.cn/Article/details/gtnmpiwedx.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.yj202588.top/Article/details/gtvokzhrmz.html

[U97] JS：并发请求
来源：http://dali.chenlongwang.top/Article/details/gtpvunfxfd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.gzhubu.top/Article/details/gtcgrbtudf.html

[U98] JS：fetch 带 JSON
来源：http://dali.yonumen.top/Article/details/gtmpvkjxzm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.snrcjt.cn/Article/details/gtbksljanf.html

[U99] JS：事件监听
来源：http://dali.dashuyun.cn/Article/details/gtqvtgradt.html

el.addEventListener("click", e => {})
来源：http://dali.zycfv.cn/Article/details/gtmbgwucco.html

[U100] JS：DOM 查询
来源：http://dali.cheryme.top/Article/details/gtxojqbktd.html

document.querySelector(".item")
来源：http://dali.jiagoushi.top/Article/details/gtrekvopia.html

[U101] JS：classList 操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvavotad.html

el.classList.toggle("active")
来源：http://dali.yuanzhike.top/Article/details/gtksjnanfk.html

[U102] JS：本地存储
来源：http://dali.xziqi.cn/Article/details/gteigqrzjz.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinghuilouyu.cn/Article/details/gtifhzjyfg.html

[U103] JS：定时器
来源：http://dali.jiagoushi.top/Article/details/gtcqfmodrk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.chenjidiqi.icu/Article/details/gtxvszkapf.html

[U104] JS：防抖
来源：http://dali.bjfxy.top/Article/details/gtgwdssghd.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtvtkrxyes.html

[U105] JS：节流
来源：http://dali.ehwqpu.com/Article/details/gtyiwghufo.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ybcxt.top/Article/details/gtvocpwgjp.html

[U106] JS：日期格式化
来源：http://dali.yuanzhike.top/Article/details/gtlkcohfme.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yueranfly.top/Article/details/gtggydbrci.html

[U107] JS：数字千分位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktwdntbt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jiagoushi.top/Article/details/gttzcqlyte.html

[U108] JS：随机整数
来源：http://dali.sufxvd.cn/Article/details/gtdqfcdzcv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinqigufen.top/Article/details/gtwdlhaefp.html

[U109] JS：数组分组
来源：http://dali.zycfv.cn/Article/details/gtfsvgagxl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ybcxt.top/Article/details/gtjauywoig.html

[U110] JS：数组分块
来源：http://dali.svipenyu.cn/Article/details/gtuvwklmjm.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.guannengcc.top/Article/details/gtifjbyevg.html

[U111] JS：对象转 Map
来源：http://dali.c1oappe.top/Article/details/gtgonpejfb.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gtkcfgkykf.html

[U112] JS：字符串补位
来源：http://dali.sufxvd.cn/Article/details/gttnudilru.html

"7".padStart(3, "0")
来源：http://dali.guannengcc.top/Article/details/gtyufjbmox.html

[U113] JS：正则替换全部
来源：http://dali.meibo888.top/Article/details/gtmdhaqcdn.html

s.replaceAll("a", "b")
来源：http://dali.wangshuangyany.cn/Article/details/gtwjpddlds.html

[U114] JS：JSON 深比较
来源：http://dali.dianchejie.cn/Article/details/gtmuqwxlla.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.ydzc1.top/Article/details/gthvicauog.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtgidzciip.html

crypto.randomUUID()
来源：http://dali.hysaishi.cn/Article/details/gtmpbbywby.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gtgzxiqmrr.html

/** @param {string} name */ function f(name) {}
来源：http://dali.nanxinkj.top/Article/details/gtxemzfgdp.html

[U117] JS：单元测试
来源：http://dali.birdmap.top/Article/details/gtkzzimlsu.html

npm i -D vitest;  npx vitest
来源：http://dali.chenjidiqi.icu/Article/details/gtlctlwwwt.html

[U118] JS：开发服务器
来源：http://dali.yonumen.top/Article/details/gtzbnhablm.html

npm i -D vite;  npx vite
来源：http://dali.aibaodan.cn/Article/details/gtjyyepdta.html

[U119] JS：生产构建
来源：http://dali.aizwys.cn/Article/details/gtcbvyltmk.html

npx vite build
来源：http://dali.gogol.net.cn/Article/details/gtadlrdeti.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gotoacloud.top/Article/details/gtpykobqka.html

import.meta.env.VITE_API_URL
来源：http://dali.iojbl.cn/Article/details/gtetxxpref.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtbkwcytqq.html

统计汇总
来源：http://dali.tianlin.xyz/Article/details/gtripuiotx.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gthhbbcrwd.html

按语言统计（条）：
来源：http://dali.ivvv.top/Article/details/gthqblknpq.html

Python ......... 252
来源：http://dali.daxiang520.top/Article/details/gttwspzadj.html

PHP ............ 252
来源：http://dali.guowangkeji.top/Article/details/gtkijyshcd.html

JavaScript ..... 252
来源：http://dali.jinqigufen.top/Article/details/gtmzgqzruf.html

TypeScript ..... 212
来源：http://dali.jiagoushi.top/Article/details/gtefmiwewd.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtyhxrikjl.html

Go ............. 212
来源：http://dali.jqgfzy.top/Article/details/gtptezntxm.html

Ruby ........... 212
来源：http://dali.yvedp.cn/Article/details/gtwpcgtmkc.html

C# ............. 212
来源：http://dali.tian-w.cn/Article/details/gtdxegjzek.html

C .............. 30
来源：http://dali.xinyue.icu/Article/details/gtxbsqqtru.html

C++ ............ 30
来源：http://dali.hysaishi.cn/Article/details/gtnbekrwio.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgkzwuuvm.html

Bash ........... 80
来源：http://dali.andypj.xyz/Article/details/gtcgujdomi.html

Kotlin ......... 15
来源：http://dali.shzxlz.cn/Article/details/gtfgncehly.html

Swift .......... 15
来源：http://dali.bjfxy.top/Article/details/gttdhjdhlj.html

Lua ............ 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtibjqbzon.html

Perl ........... 10
来源：http://dali.vqdsnc.cn/Article/details/gtqbnukonb.html

Scala .......... 10
来源：http://dali.wangshuangyany.cn/Article/details/gtbesotbrq.html

------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtjdfjfpwr.html

合计 ........... 2106 条
来源：http://dali.yj202588.top/Article/details/gtsxrpusvj.html

按章节统计：
来源：http://dali.gzhubu.top/Article/details/gttmurbfda.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtjugkyzlj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.zhongyouzk.top/Article/details/gtxwjnydup.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtrwxynhhl.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhengqikj.top/Article/details/gtgkkyfrgv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jyoumei.cn/Article/details/gtgcmncxct.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.ppjwa.cn/Article/details/gtsryrycox.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zycfv.cn/Article/details/gtfeeetbra.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.gaohongyu789.top/Article/details/gtvdzwsard.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtbhbejqnf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaeyjdrb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.redwolf501.top/Article/details/gttiyplpjy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtesdbxkrm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gtwuxwggak.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hfpthk.cn/Article/details/gtkiogurif.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.316326.xyz/Article/details/gtaebabacm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jiagoushi.top/Article/details/gtxohmlyhq.html

Q SQL 专题                              90
来源：http://dali.xylfe.cn/Article/details/gtdhvnjtxi.html

R Bash 专题                             80
来源：http://dali.xylfe.cn/Article/details/gtteqetbot.html

S C / C++ 专题                          60
来源：http://dali.chenlongwang.top/Article/details/gtavdgsitv.html

T 其他语言补充                          60
来源：http://dali.yonumen.top/Article/details/gtyhfdhwog.html


<!-- 参考信息 -->