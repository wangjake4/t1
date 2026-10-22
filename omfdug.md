代发 wailian999

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2jmuikito.html

[T55] Scala：集合过滤
来源：http://dali.fzhhl.top/Article/details/gt2gvdugzsl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.mhx1999.top/Article/details/gt2obazqpzp.html

[T56] Scala：样例类
来源：http://dali.zhoulong.xyz/Article/details/gt2xcjzhjwh.html

case class User(name: String, age: Int)
来源：http://dali.zhongyouzk.top/Article/details/gt2msydestf.html

[T57] Scala：模式匹配
来源：http://dali.jinqigufen.top/Article/details/gt2sjmjxwcr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2idjuyknn.html

[T58] Scala：函数定义
来源：http://dali.bjfxy.top/Article/details/gt2nxddcaya.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sxryk.cn/Article/details/gt2hkpxundy.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gt2fvneizap.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2siatzhqo.html

[T60] Scala：折叠
来源：http://dali.yangfankeji.com/Article/details/gt2cnjyxbuc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gt2uiuloomc.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2brvbzzuw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.xuetiantiany.cn/Article/details/gt2zmmlswvs.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bxxnxppp.html

[U01] Py：创建虚拟环境
来源：http://dali.yueranfly.top/Article/details/gt2svzexifm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gt2axxpjtyt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sweek.top/Article/details/gt2cfshlvlf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.sysykeji.top/Article/details/gt2lzlhyuzv.html

[U03] Py：加载 .env 配置
来源：http://dali.hnqzz.top/Article/details/gt2ngtlcfsz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gt2yrqxzghu.html

[U04] Py：变量调试打印
来源：http://dali.zhoulong.xyz/Article/details/gt2bmltejlu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gt2vfudhmxz.html

[U05] Py：列表去重且保序
来源：http://dali.guowangkeji.top/Article/details/gt2kdmhjxhe.html

list(dict.fromkeys(arr))
来源：http://dali.yuanzhike.top/Article/details/gt2pmimgbya.html

[U06] Py：合并两个字典
来源：http://dali.andypj.xyz/Article/details/gt2sdyrsqjz.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gt2aysgcvyq.html

[U07] Py：反转字典键值
来源：http://dali.ydzc1.top/Article/details/gt2ueayrsla.html

{v: k for k, v in d.items()}
来源：http://dali.yvedp.cn/Article/details/gt2iyovnudd.html

[U08] Py：展平二维列表
来源：http://dali.pengpengdd.cyou/Article/details/gt2scebbwin.html

[y for x in nested for y in x]
来源：http://dali.svipenyu.cn/Article/details/gt2twdsilmc.html

[U09] Py：字典取最大值的键
来源：http://dali.yuxming.cn/Article/details/gt2cljkctqj.html

max(d, key=d.get)
来源：http://dali.vqdsnc.cn/Article/details/gt2uwnqnwxj.html

[U10] Py：按值排序字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bjkzsvnl.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gt2nzrintwy.html

[U11] Py：生成器表达式
来源：http://dali.yj20258888.top/Article/details/gt2popyyogl.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2piwxcoto.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gt2mmzbxmhh.html

Counter(arr).most_common(3)
来源：http://dali.hysaishi.cn/Article/details/gt2yoteduml.html

[U13] Py：固定长度队列
来源：http://dali.yuanzhike.top/Article/details/gt2neppyiqj.html

deque(maxlen=10)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2getrhxtt.html

[U14] Py：分组收集到列表
来源：http://dali.jiagoushi.top/Article/details/gt2wgogxmpr.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gt2krfqwucd.html

[U15] Py：高精度计时
来源：http://dali.nanxinkj.top/Article/details/gt2ackipato.html

t = time.perf_counter()
来源：http://dali.zhongyouzk.top/Article/details/gt2pwqxwhsm.html

[U16] Py：命令行参数解析
来源：http://dali.zhengqikj.top/Article/details/gt2ftqrmwtm.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gt2nfyxczhx.html

[U17] Py：初始化日志
来源：http://dali.daria6918.cn/Article/details/gt2lxwldhgk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gt2pdpvbcao.html

[U18] Py：预编译正则
来源：http://dali.tian-w.cn/Article/details/gt2zeilmhfr.html

pat = re.compile(r"\d+")
来源：http://dali.sysykeji.top/Article/details/gt2rawjgtgo.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gt2sjitdums.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.birdmap.top/Article/details/gt2nwsmmwkt.html

[U20] Py：缓存函数结果
来源：http://dali.tianlin.xyz/Article/details/gt2byebwsdw.html

@functools.lru_cache(maxsize=None)
来源：http://dali.bjfxy.top/Article/details/gt2sxmapptl.html

[U21] Py：自定义上下文管理器
来源：http://dali.aibaodan.cn/Article/details/gt2oyqylgkg.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqihpvny.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gt2lgjgezrv.html

list(zip(*m))
来源：http://dali.haohaochexian.top/Article/details/gt2smvvbeee.html

[U23] Py：分块读取大文件
来源：http://dali.cdnleiting.top/Article/details/gt2soqdgtzt.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnefezvb.html

[U24] Py：路径操作
来源：http://dali.yueranfly.top/Article/details/gt2hcazacjr.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.zhixingplan.top/Article/details/gt2lxkdyvep.html

[U25] Py：CSV 按字典读
来源：http://dali.sxryk.cn/Article/details/gt2mjlhzrew.html

csv.DictReader(f)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2raospzcb.html

[U26] Py：并发下载
来源：http://dali.tanke756.top/Article/details/gt2tbszvykc.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.9152youxi.cn/Article/details/gt2gnmgxigp.html

[U27] Py：异步 HTTP
来源：http://dali.andypj.xyz/Article/details/gt2chifzmpn.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gt2hywzwnkd.html

[U28] Py：类型别名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kntfjydb.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gt2rclyyzqr.html

[U29] Py：属性校验
来源：http://dali.jiagoushi.top/Article/details/gt2buojzlnl.html

@property 与 @x.setter 配合
来源：http://dali.gogol.net.cn/Article/details/gt2vslitfna.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gt2ekmbhdfi.html

@dataclass(slots=True)
来源：http://dali.tanke756.top/Article/details/gt2kaqemfmt.html

[U31] Py：单测
来源：http://dali.ppjwa.cn/Article/details/gt2ithdhuni.html

python -m pytest -q
来源：http://dali.tianlin.xyz/Article/details/gt2clbntzga.html

[U32] Py：代码格式化
来源：http://dali.hfpthk.cn/Article/details/gt2taliqkbl.html

ruff format . && ruff check --fix .
来源：http://dali.iojbl.cn/Article/details/gt2nwjicnlm.html

[U33] Py：打包发布
来源：http://dali.wangdashe.top/Article/details/gt2atwhouzu.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yj202588.top/Article/details/gt2cbvfdehv.html

[U34] Py：判断编码
来源：http://dali.zycfv.cn/Article/details/gt2dekklhdj.html

chardet.detect(raw)
来源：http://dali.hammf.cn/Article/details/gt2qvdxnzcg.html

[U35] Py：发送邮件
来源：http://dali.shzxlz.cn/Article/details/gt2bupgdgvb.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jinqigfzy.top/Article/details/gt2gkmfgbzt.html

[U36] Py：定时任务
来源：http://dali.fzhhl.top/Article/details/gt2ucxdzpcc.html

schedule.every(10).minutes.do(job)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fmagzxpy.html

[U37] Py：读写 Excel
来源：http://dali.andypj.xyz/Article/details/gt2dcwfhuhz.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.guannengcc.top/Article/details/gt2uajeqxir.html

[U38] Py：获取脚本所在目录
来源：http://dali.aibaodan.cn/Article/details/gt2rzuihgfa.html

Path(__file__).resolve().parent
来源：http://dali.jianghu66.top/Article/details/gt2jmrfhkpg.html

[U39] Py：判断是否在交互环境
来源：http://dali.tanke756.top/Article/details/gt2iqaucpce.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gt2ktxbvlsw.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gt2kzqklozb.html

print("err", file=sys.stderr)
来源：http://dali.hnxiangtu.top/Article/details/gt2miihnmyf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gt2djlgohjy.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zycfv.cn/Article/details/gt2qsujtsct.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijlrcqew.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hysaishi.cn/Article/details/gt2ldmnwsll.html

[U43] PHP：声明命名空间
来源：http://dali.yanxiufei.cn/Article/details/gt2qtsrebht.html

namespace App\Http;
来源：http://dali.svipenyu.cn/Article/details/gt2ukpbyite.html

[U44] PHP：开启严格类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uxfnpkrp.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gt2sbmqyjas.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhijiandao.cn/Article/details/gt2icvjhlje.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gt2isdbzvvo.html

[U46] PHP：可空类型
来源：http://dali.zhongyouzk.top/Article/details/gt2dlwhwsbf.html

?string $name = null
来源：http://dali.sxryk.cn/Article/details/gt2xeehdety.html

[U47] PHP：联合类型
来源：http://dali.sxryk.cn/Article/details/gt2ezbgebgo.html

int|string $id
来源：http://dali.gotoacloud.top/Article/details/gt2zkcovwva.html

[U48] PHP：纯枚举
来源：http://dali.bjfxy.top/Article/details/gt2rcgbgghb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.iojbl.cn/Article/details/gt2xvccvdaa.html

[U49] PHP：只读属性
来源：http://dali.pycfn.com/Article/details/gt2wargfxlz.html

public readonly string $name
来源：http://dali.wangdashe.top/Article/details/gt2ssosbwln.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gt2ddokjbst.html

public function __construct(private int $id) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsvtzudc.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gt2veokaxng.html

[$a, $b] = $arr;
来源：http://dali.kuanghao11.cn/Article/details/gt2wyeypqzx.html

[U52] PHP：箭头函数
来源：http://dali.yuanzhike.top/Article/details/gt2aauesunw.html

$double = fn($x) => $x * 2;
来源：http://dali.hysaishi.cn/Article/details/gt2dldkialq.html

[U53] PHP：空合并运算符
来源：http://dali.shuidangran.top/Article/details/gt2azrqxrux.html

$v = $a ?? $b ?? "default";
来源：http://dali.gogol.net.cn/Article/details/gt2zgjldhjg.html

[U54] PHP：空安全调用
来源：http://dali.redwolf501.top/Article/details/gt2uxlusvgy.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gt2ywzhhkci.html

[U55] PHP：match 表达式
来源：http://dali.shzxlz.cn/Article/details/gt2yinjunlk.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2fqcsxkgz.html

[U56] PHP：命名参数
来源：http://dali.nwbrower.top/Article/details/gt2gtfzgert.html

f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2kihdmrkk.html

[U57] PHP：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2ywgojwct.html

"值: {$a}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmopyfww.html

[U58] PHP：数组三件套
来源：http://dali.kuanghao11.cn/Article/details/gt2cphbntgx.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xziqi.cn/Article/details/gt2lmqppsee.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gt2womwgwaa.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cashguo.top/Article/details/gt2yxjocafs.html

[U60] PHP：JSON 编解码
来源：http://dali.feifeiyinyue.top/Article/details/gt2mbgvhgze.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.guannengcc.top/Article/details/gt2fglthzsf.html

[U61] PHP：正则
来源：http://dali.havefunace.top/Article/details/gt2kwuazruo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2qbvysbjr.html

[U62] PHP：日期对象
来源：http://dali.yuanzhike.top/Article/details/gt2ntqwhjsr.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jqgufenzy.top/Article/details/gt2iroemugg.html

[U63] PHP：文件读写
来源：http://dali.9152youxi.cn/Article/details/gt2payzkydu.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.9152youxi.cn/Article/details/gt2coxxxnfu.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gt2taburigh.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xuetiantiany.cn/Article/details/gt2cuwjmuam.html

[U65] PHP：会话
来源：http://dali.havefunace.top/Article/details/gt2udvfpjei.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2xamqrefk.html

[U66] PHP：设置 Cookie
来源：http://dali.guowangkeji.top/Article/details/gt2wdmiuqvk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhijiandao.cn/Article/details/gt2dhqpbvqz.html

[U67] PHP：处理文件上传
来源：http://dali.gaohongyu789.top/Article/details/gt2zgnyykbb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jicibsqk.html

[U68] PHP：PDO 连接
来源：http://dali.ehwqpu.com/Article/details/gt2vadrzqia.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aibaodan.cn/Article/details/gt2ozqxcltt.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2iggfrbrt.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.mhx1999.top/Article/details/gt2jsvevyhj.html

[U70] PHP：PDO 事务
来源：http://dali.sufxvd.cn/Article/details/gt2qzgfkatu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yjezctdo.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2towehruz.html

throw new RuntimeException("失败", 500);
来源：http://dali.dashuyun.cn/Article/details/gt2qplsvgkw.html

[U72] PHP：写错误日志
来源：http://dali.hammf.cn/Article/details/gt2dhoxkfiy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.shuidangran.top/Article/details/gt2sddidrkz.html

[U73] PHP：读取 ini 配置
来源：http://dali.hywenlv.cn/Article/details/gt2wncoblhr.html

parse_ini_file("config.ini", true)
来源：http://dali.ppjwa.cn/Article/details/gt2lnwncaxn.html

[U74] PHP：读取环境变量
来源：http://dali.gotoacloud.top/Article/details/gt2rkjuzxwp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.zhongyouzk.top/Article/details/gt2bocyngup.html

[U75] PHP：依赖注入
来源：http://dali.nanxinkj.top/Article/details/gt2xubqxlcm.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gt2mpqnbgub.html

[U76] PHP：简单路由
来源：http://dali.hnxiangtu.top/Article/details/gt2weozscer.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gt2ygeqprae.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2wqquvjfb.html

composer require twig/twig
来源：http://dali.xuanzx.com/Article/details/gt2qkdolgks.html

[U78] PHP：单元测试
来源：http://dali.zhoulong.xyz/Article/details/gt2coqetsab.html

composer require --dev phpunit/phpunit
来源：http://dali.nanxinkj.top/Article/details/gt2jtndptgt.html

[U79] PHP：静态分析
来源：http://dali.pycfn.com/Article/details/gt2fmyuvxdx.html

composer require --dev phpstan/phpstan
来源：http://dali.sweek.top/Article/details/gt2vijkhisx.html

[U80] PHP：代码规范修复
来源：http://dali.hongshengwenyu.top/Article/details/gt2otiroyen.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.iojbl.cn/Article/details/gt2sbekzzif.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gt2jqlozsgu.html

npm init -y;  npm i express
来源：http://dali.9152youxi.cn/Article/details/gt2ykfuqmpx.html

[U82] JS：package.json 脚本
来源：http://dali.zdqjudy.top/Article/details/gt2ajwnqjli.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gt2dodptxwu.html

[U83] JS：ES Module 导入导出
来源：http://dali.meibo888.top/Article/details/gt2tkgxujoj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gt2snngpiwp.html

[U84] JS：CommonJS 写法
来源：http://dali.fengsongda.top/Article/details/gt2okyaafcs.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.birdmap.top/Article/details/gt2ibtjuxhw.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2qildesct.html

a?.b?.c
来源：http://dali.shzxlz.cn/Article/details/gt2gptptzsp.html

[U86] JS：空值合并
来源：http://dali.ydzc1.top/Article/details/gt2dvopnxfx.html

a ?? b
来源：http://dali.hysaishi.cn/Article/details/gt2njkzczbt.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gt2fzkbzawn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2elnwazqp.html

[U88] JS：对象展开合并
来源：http://dali.haohaochexian.top/Article/details/gt2pwrfjzhm.html

{ ...a, ...b }
来源：http://dali.daria6918.cn/Article/details/gt2itnweods.html

[U89] JS：数组去重
来源：http://dali.gaohongyu789.top/Article/details/gt2tzucyyis.html

[...new Set(arr)]
来源：http://dali.hywenlv.cn/Article/details/gt2dvkqgmil.html

[U90] JS：数字数组排序
来源：http://dali.kuanghao11.cn/Article/details/gt2vqgsmqvu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.hfpthk.cn/Article/details/gt2cwufjdjn.html

[U91] JS：对象键值遍历
来源：http://dali.sxryk.cn/Article/details/gt2bxdqqgnp.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gt2uoxmrxqm.html

[U92] JS：深拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2dkwsbcpr.html

structuredClone(obj)
来源：http://dali.snrcjt.cn/Article/details/gt2wfgvcyzz.html

[U93] JS：模板字符串
来源：http://dali.ivvv.top/Article/details/gt2iyeaedxz.html

`共 ${n} 条`
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rvmzudyb.html

[U94] JS：箭头函数
来源：http://dali.zhijiandao.cn/Article/details/gt2kvjbkwwl.html

const double = x => x * 2;
来源：http://dali.0kj1m.cn/Article/details/gt2cxcjixcs.html

[U95] JS：Promise 包装
来源：http://dali.hnxiangtu.top/Article/details/gt2ahzaruen.html

new Promise((resolve, reject) => {})
来源：http://dali.yuanzhike.top/Article/details/gt2kuyuhega.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gt2nnlfscok.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cucudq.cn/Article/details/gt2lcpeghfd.html

[U97] JS：并发请求
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2awxqhixw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.quarkkingdee.top/Article/details/gt2hpdcvwgy.html

[U98] JS：fetch 带 JSON
来源：http://dali.pycfn.com/Article/details/gt2erhbwmlf.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.aibaodan.cn/Article/details/gt2kuxntwkq.html

[U99] JS：事件监听
来源：http://dali.shuidangran.top/Article/details/gt2dhxoxzuz.html

el.addEventListener("click", e => {})
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nyawvjqg.html

[U100] JS：DOM 查询
来源：http://dali.jyoumei.cn/Article/details/gt2wpjwgtrm.html

document.querySelector(".item")
来源：http://dali.fzhhl.top/Article/details/gt2jmjrhrpm.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2vhajyxan.html

el.classList.toggle("active")
来源：http://dali.yanxiufei.cn/Article/details/gt2yielgdut.html

[U102] JS：本地存储
来源：http://dali.tian-w.cn/Article/details/gt2butpxvjq.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hysaishi.cn/Article/details/gt2qdbamvod.html

[U103] JS：定时器
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dhamwlvm.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhiwuduotai.top/Article/details/gt2baiophwj.html

[U104] JS：防抖
来源：http://dali.aibaodan.cn/Article/details/gt2tccxkwml.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.xylfe.cn/Article/details/gt2lotngutm.html

[U105] JS：节流
来源：http://dali.gotoacloud.top/Article/details/gt2ayzldrng.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gt2rtkavour.html

[U106] JS：日期格式化
来源：http://dali.hysaishi.cn/Article/details/gt2dvmdflun.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zhengqikj.top/Article/details/gt2keueqfmp.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gt2xgpmqxsd.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2zcwwgkep.html

[U108] JS：随机整数
来源：http://dali.nanxuanxn.top/Article/details/gt2qkznlypc.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.bjfxy.top/Article/details/gt2pgpvoulk.html

[U109] JS：数组分组
来源：http://dali.sweek.top/Article/details/gt2tgebftth.html

Object.groupBy(arr, x => x.type)
来源：http://dali.kuanghao11.cn/Article/details/gt2tavjhwjy.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gt2woxixylk.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2vsgbyxzh.html

[U111] JS：对象转 Map
来源：http://dali.nanxinkj.top/Article/details/gt2izkuekbu.html

new Map(Object.entries(obj))
来源：http://dali.redwolf501.top/Article/details/gt2kscajiva.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gt2qjyeoipx.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gt2cwosytdq.html

[U113] JS：正则替换全部
来源：http://dali.gogol.net.cn/Article/details/gt2hfrybjnu.html

s.replaceAll("a", "b")
来源：http://dali.jinqigfzy.top/Article/details/gt2innkmoun.html

[U114] JS：JSON 深比较
来源：http://dali.tanke756.top/Article/details/gt2cxeejyot.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hammf.cn/Article/details/gt2qhdwhuds.html

[U115] JS：生成 UUID
来源：http://dali.316326.xyz/Article/details/gt2kbkivoii.html

crypto.randomUUID()
来源：http://dali.tanke756.top/Article/details/gt2xqcxzuxi.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hnqzz.top/Article/details/gt2megjugxv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cucudq.cn/Article/details/gt2dzgthugv.html

[U117] JS：单元测试
来源：http://dali.yj20258888.top/Article/details/gt2skfrskug.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gt2lrzrdntg.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gt2lenhpqxc.html

npm i -D vite;  npx vite
来源：http://dali.iojbl.cn/Article/details/gt2eymeywsj.html

[U119] JS：生产构建
来源：http://dali.ybcxt.top/Article/details/gt2njnkjitc.html

npx vite build
来源：http://dali.0kj1m.cn/Article/details/gt2fvqxmraa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.mhx1999.top/Article/details/gt2jgfrotqn.html

import.meta.env.VITE_API_URL
来源：http://dali.0kj1m.cn/Article/details/gt2jhimlaar.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2cuubfhwz.html

统计汇总
来源：http://dali.hysaishi.cn/Article/details/gt2tozqewrg.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rqgxofoo.html

按语言统计（条）：
来源：http://dali.shangyingyoupin.top/Article/details/gt2rkpgkkei.html

Python ......... 252
来源：http://dali.pycfn.com/Article/details/gt2jknztmub.html

PHP ............ 252
来源：http://dali.nanxinkj.top/Article/details/gt2tsooqkya.html

JavaScript ..... 252
来源：http://dali.xinyue.icu/Article/details/gt2ikbqngys.html

TypeScript ..... 212
来源：http://dali.tianlin.xyz/Article/details/gt2nfksyxke.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bffbxixz.html

Go ............. 212
来源：http://dali.tian-w.cn/Article/details/gt2iaanbpla.html

Ruby ........... 212
来源：http://dali.jyoumei.cn/Article/details/gt2voxftlpc.html

C# ............. 212
来源：http://dali.pengpengdd.cyou/Article/details/gt2kqgngwao.html

C .............. 30
来源：http://dali.aizwys.cn/Article/details/gt2rqrgncep.html

C++ ............ 30
来源：http://dali.guowangkeji.top/Article/details/gt2tlqhfnwg.html

SQL ............ 90
来源：http://dali.pycfn.com/Article/details/gt2oetiwcag.html

Bash ........... 80
来源：http://dali.vqdsnc.cn/Article/details/gt2klxqlkdv.html

Kotlin ......... 15
来源：http://dali.gzhubu.top/Article/details/gt2lhitsqhn.html

Swift .......... 15
来源：http://dali.ydzc1.top/Article/details/gt2cjqmtkwt.html

Lua ............ 10
来源：http://dali.guowangkeji.top/Article/details/gt2tuvdliad.html

Perl ........... 10
来源：http://dali.yonumen.top/Article/details/gt2tgcjlxvx.html

Scala .......... 10
来源：http://dali.cqqwz.cn/Article/details/gt2efqnntot.html

------------------------------------
来源：http://dali.mhx1999.top/Article/details/gt2dbotvpxi.html

合计 ........... 2106 条
来源：http://dali.cdnleiting.top/Article/details/gt2xsyrlhjv.html

按章节统计：
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fpktfiyp.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gt2pwscmkxr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.andypj.xyz/Article/details/gt2nfjesbox.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2qxxujibe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cdnleiting.top/Article/details/gt2qfokjxmb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.shangyingyoupin.top/Article/details/gt2ppghrsfh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2afsykghq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhengqikj.top/Article/details/gt2bpitfogo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hywenlv.cn/Article/details/gt2snjgjkqe.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jinqigfzy.top/Article/details/gt2cagvbmwq.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2diiiqkhm.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yzdhalme.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.xziqi.cn/Article/details/gt2vsajyclk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gt2kqmozmrb.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yueranfly.top/Article/details/gt2phrwliro.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zycfv.cn/Article/details/gt2kwtjwsbl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guowangkeji.top/Article/details/gt2qyxqlhfi.html

Q SQL 专题                              90
来源：http://dali.hnqzz.top/Article/details/gt2qhtivvno.html

R Bash 专题                             80
来源：http://dali.yuxming.cn/Article/details/gt2zjwjogoe.html

S C / C++ 专题                          60
来源：http://dali.ybcxt.top/Article/details/gt2orwwwomt.html

T 其他语言补充                          60
来源：http://dali.yueranfly.top/Article/details/gt2qxdxujap.html


<!-- 参考信息 -->