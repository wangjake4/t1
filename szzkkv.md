代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.nanxuanxn.top/Article/details/gtrhbhzgwa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yonumen.top/Article/details/gtozvfabey.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gtrabrovkm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.tanke756.top/Article/details/gtpudxrosa.html

[U03] Py：加载 .env 配置
来源：http://dali.zhengqikj.top/Article/details/gtrtjahosi.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsysztjrf.html

[U04] Py：变量调试打印
来源：http://dali.yongpay.top/Article/details/gtokyjjeab.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtmsprzvmg.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtbbclthhh.html

list(dict.fromkeys(arr))
来源：http://dali.bjfxy.top/Article/details/gtyiryfsbr.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtmswtrgrp.html

{**a, **b}
来源：http://dali.wangshuangyany.cn/Article/details/gtwyaitjtz.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gthgiimirc.html

{v: k for k, v in d.items()}
来源：http://dali.yongpay.top/Article/details/gteaekgdqh.html

[U08] Py：展平二维列表
来源：http://dali.hfpthk.cn/Article/details/gtymxxjozh.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtwpdhlbzi.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gttvvhsazw.html

max(d, key=d.get)
来源：http://dali.nanxinkj.top/Article/details/gtwkbsdvrj.html

[U10] Py：按值排序字典
来源：http://dali.0kj1m.cn/Article/details/gtezkpepfo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.redwolf501.top/Article/details/gtqpiyakur.html

[U11] Py：生成器表达式
来源：http://dali.nanxuanxn.top/Article/details/gtisfengey.html

(x * 2 for x in arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmxetgml.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.andypj.xyz/Article/details/gttyhfkvtv.html

Counter(arr).most_common(3)
来源：http://dali.nanxinkj.top/Article/details/gttnctzzdd.html

[U13] Py：固定长度队列
来源：http://dali.guannengcc.top/Article/details/gtuovkfzpl.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gtaguodfim.html

[U14] Py：分组收集到列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkagcqbk.html

defaultdict(list)
来源：http://dali.xylfe.cn/Article/details/gtcwfgxoaz.html

[U15] Py：高精度计时
来源：http://dali.dianchejie.cn/Article/details/gtvecislwa.html

t = time.perf_counter()
来源：http://dali.jlsjyb.cn/Article/details/gtliqzzhzw.html

[U16] Py：命令行参数解析
来源：http://dali.andypj.xyz/Article/details/gtwlzlabba.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zycfv.cn/Article/details/gtapifbxlo.html

[U17] Py：初始化日志
来源：http://dali.bjfxy.top/Article/details/gtahxeqswi.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.xinyue.icu/Article/details/gttksdljuw.html

[U18] Py：预编译正则
来源：http://dali.bjfxy.top/Article/details/gtvocgfegu.html

pat = re.compile(r"\d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtiyebbxyk.html

[U19] Py：正则替换带回调
来源：http://dali.quarkkingdee.top/Article/details/gtqnmyjprz.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaiwktmle.html

[U20] Py：缓存函数结果
来源：http://dali.yj20258.top/Article/details/gtimfuuwvx.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jinqigfzy.top/Article/details/gtnnworsak.html

[U21] Py：自定义上下文管理器
来源：http://dali.snrcjt.cn/Article/details/gtyjogqpcg.html

@contextlib.contextmanager
来源：http://dali.ybcxt.top/Article/details/gtleffjpup.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gthwzimjtb.html

list(zip(*m))
来源：http://dali.cqqwz.cn/Article/details/gthtcpanom.html

[U23] Py：分块读取大文件
来源：http://dali.mhx1999.top/Article/details/gtulmbvuyy.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgufenzy.top/Article/details/gtwfjlzbju.html

[U24] Py：路径操作
来源：http://dali.ivvv.top/Article/details/gtjossdtbh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwkbogpad.html

[U25] Py：CSV 按字典读
来源：http://dali.sufxvd.cn/Article/details/gtqkutwgxu.html

csv.DictReader(f)
来源：http://dali.xuanzx.com/Article/details/gtcyotmoey.html

[U26] Py：并发下载
来源：http://dali.wangdashe.top/Article/details/gtixvyhtue.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.shanyushiyangtech.top/Article/details/gtqbapobua.html

[U27] Py：异步 HTTP
来源：http://dali.zycfv.cn/Article/details/gtwbgezlmh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gtlypqbtzm.html

[U28] Py：类型别名
来源：http://dali.zdqjudy.top/Article/details/gtxrbrpyes.html

UserId = int
来源：http://dali.316326.xyz/Article/details/gtqrivjapq.html

[U29] Py：属性校验
来源：http://dali.ydzc1.top/Article/details/gtqalahejh.html

@property 与 @x.setter 配合
来源：http://dali.wangshuangyany.cn/Article/details/gteubzsqqi.html

[U30] Py：数据类
来源：http://dali.hongshengwenyu.top/Article/details/gtybgouujd.html

@dataclass(slots=True)
来源：http://dali.yj20258888.top/Article/details/gtjnivwuhm.html

[U31] Py：单测
来源：http://dali.cqqwz.cn/Article/details/gtvfcdepvt.html

python -m pytest -q
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdaastcvg.html

[U32] Py：代码格式化
来源：http://dali.cucudq.cn/Article/details/gtlinscdtz.html

ruff format . && ruff check --fix .
来源：http://dali.zhengqikj.top/Article/details/gtxlkzyxhz.html

[U33] Py：打包发布
来源：http://dali.meibo888.top/Article/details/gtsmavrdwx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.zhoulong.xyz/Article/details/gtqshqhkls.html

[U34] Py：判断编码
来源：http://dali.gogol.net.cn/Article/details/gtjambrkoy.html

chardet.detect(raw)
来源：http://dali.zdqjudy.top/Article/details/gtwpzeauub.html

[U35] Py：发送邮件
来源：http://dali.dashuyun.cn/Article/details/gtzhttetib.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.feifeiyinyue.top/Article/details/gtrbhufttx.html

[U36] Py：定时任务
来源：http://dali.guowangkeji.top/Article/details/gtktcekqgf.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtcqwqubdi.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtewwsjpgl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkfqkfxu.html

[U38] Py：获取脚本所在目录
来源：http://dali.sysykeji.top/Article/details/gttingnvkj.html

Path(__file__).resolve().parent
来源：http://dali.snrcjt.cn/Article/details/gtwtprmskd.html

[U39] Py：判断是否在交互环境
来源：http://dali.vqdsnc.cn/Article/details/gtfrwfdqid.html

sys.stdout.isatty()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbhcdrsfm.html

[U40] Py：打印到标准错误
来源：http://dali.yj202588.top/Article/details/gthoqirrgk.html

print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtdtxdefvq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gtokkcaiht.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.svipenyu.cn/Article/details/gtiibddacc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hfpthk.cn/Article/details/gtvcwigatm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtiltjpqyu.html

[U43] PHP：声明命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtrkmbvbrb.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtktqjpjkc.html

[U44] PHP：开启严格类型
来源：http://dali.dianchejie.cn/Article/details/gtefsnmdqu.html

declare(strict_types=1);
来源：http://dali.zhoulong.xyz/Article/details/gtjpsereyc.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yangfankeji.com/Article/details/gtdlzxdqsg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gtvyoprneu.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gtoixcjhmb.html

?string $name = null
来源：http://dali.shanyushiyangtech.top/Article/details/gteetyysue.html

[U47] PHP：联合类型
来源：http://dali.gogol.net.cn/Article/details/gthucopmjn.html

int|string $id
来源：http://dali.hnxiangtu.top/Article/details/gtpyscsgjz.html

[U48] PHP：纯枚举
来源：http://dali.ivvv.top/Article/details/gtwnjuzcje.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.birdmap.top/Article/details/gthqegcygt.html

[U49] PHP：只读属性
来源：http://dali.hnqzz.top/Article/details/gtdxxqotbt.html

public readonly string $name
来源：http://dali.yongpay.top/Article/details/gtovjpeuqb.html

[U50] PHP：构造器属性提升
来源：http://dali.hnqzz.top/Article/details/gtpuipvlps.html

public function __construct(private int $id) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtuvchownv.html

[U51] PHP：数组解构
来源：http://dali.fzhhl.top/Article/details/gtqcwnbdva.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gthvbndalb.html

[U52] PHP：箭头函数
来源：http://dali.haohaochexian.top/Article/details/gtfwbsshee.html

$double = fn($x) => $x * 2;
来源：http://dali.dashuyun.cn/Article/details/gtespjocpm.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtgyygqsjc.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwnwzrgo.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gtzrefzayv.html

$obj?->method()
来源：http://dali.jqgfzy.top/Article/details/gtybsmrfjb.html

[U55] PHP：match 表达式
来源：http://dali.guannengcc.top/Article/details/gtkuoqupoh.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.ybcxt.top/Article/details/gtnngzoyjh.html

[U56] PHP：命名参数
来源：http://dali.cucudq.cn/Article/details/gtcyjrkewm.html

f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtklqfxmqi.html

[U57] PHP：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtmpfygpab.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gtdnfspzdy.html

[U58] PHP：数组三件套
来源：http://dali.yj202588.top/Article/details/gtfndbllfd.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ppjwa.cn/Article/details/gtjnelmsbr.html

[U59] PHP：自定义排序
来源：http://dali.vqdsnc.cn/Article/details/gtwjsplfuz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.bjfxy.top/Article/details/gtbjzbsnpn.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gtrcyduxiu.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xylfe.cn/Article/details/gtvoxaridl.html

[U61] PHP：正则
来源：http://dali.guowangkeji.top/Article/details/gtbpvxlvhd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.quarkkingdee.top/Article/details/gtmqrxsctn.html

[U62] PHP：日期对象
来源：http://dali.havefunace.top/Article/details/gtlvbgswuw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.aibaodan.cn/Article/details/gtepvelfkc.html

[U63] PHP：文件读写
来源：http://dali.guowangkeji.top/Article/details/gttynvewsn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtbavkyssc.html

[U64] PHP：目录遍历
来源：http://dali.ivvv.top/Article/details/gtivzohxag.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuvfzcvnl.html

[U65] PHP：会话
来源：http://dali.ppjwa.cn/Article/details/gtymlzuepz.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtchwlmdfn.html

[U66] PHP：设置 Cookie
来源：http://dali.meibo888.top/Article/details/gtikgpstld.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrszczerb.html

[U67] PHP：处理文件上传
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhudcjyk.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.cucudq.cn/Article/details/gtnkmkifnn.html

[U68] PHP：PDO 连接
来源：http://dali.yanxiufei.cn/Article/details/gtbypwpnyb.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunhrygfn.html

[U69] PHP：PDO 预处理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmdyxeblq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.xuanzx.com/Article/details/gtklidfmlr.html

[U70] PHP：PDO 事务
来源：http://dali.dashuyun.cn/Article/details/gtdapxovri.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tian-w.cn/Article/details/gtolpauxas.html

[U71] PHP：抛出异常
来源：http://dali.gzhubu.top/Article/details/gttisuvmlr.html

throw new RuntimeException("失败", 500);
来源：http://dali.gogol.net.cn/Article/details/gtiyyubzot.html

[U72] PHP：写错误日志
来源：http://dali.ybcxt.top/Article/details/gtwjjlnfhs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhnjyuou.html

[U73] PHP：读取 ini 配置
来源：http://dali.jinqigfzy.top/Article/details/gtcntrgwov.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtkxwauggz.html

[U74] PHP：读取环境变量
来源：http://dali.hnxiangtu.top/Article/details/gtswwsfkzh.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gttweqznki.html

[U75] PHP：依赖注入
来源：http://dali.feifeiyinyue.top/Article/details/gtucwygffm.html

composer require psr/container
来源：http://dali.cucudq.cn/Article/details/gtlijeimcd.html

[U76] PHP：简单路由
来源：http://dali.yuxming.cn/Article/details/gtaiyfnjxy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.jqgufenzy.top/Article/details/gtwjrlqtyw.html

[U77] PHP：模板渲染
来源：http://dali.haohaochexian.top/Article/details/gtrlejhhif.html

composer require twig/twig
来源：http://dali.fengsongda.top/Article/details/gtabrphkzt.html

[U78] PHP：单元测试
来源：http://dali.zhiwuduotai.top/Article/details/gtpimsuojn.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtyjsuaovp.html

[U79] PHP：静态分析
来源：http://dali.yj20258888.top/Article/details/gtbowdvogw.html

composer require --dev phpstan/phpstan
来源：http://dali.birdmap.top/Article/details/gtwvylbhuu.html

[U80] PHP：代码规范修复
来源：http://dali.tianlin.xyz/Article/details/gtrtyrpkci.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtgcvnzfuo.html

[U81] JS：初始化项目
来源：http://dali.yj20258.top/Article/details/gtdqksfece.html

npm init -y;  npm i express
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkhsghhy.html

[U82] JS：package.json 脚本
来源：http://dali.ydzc1.top/Article/details/gtkrfylbfx.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.guowangkeji.top/Article/details/gtfoszzteh.html

[U83] JS：ES Module 导入导出
来源：http://dali.guannengcc.top/Article/details/gtbmtjnbax.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.feifeiyinyue.top/Article/details/gtoersfalb.html

[U84] JS：CommonJS 写法
来源：http://dali.ivvv.top/Article/details/gtcizodpau.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jyoumei.cn/Article/details/gtjvxpqrxy.html

[U85] JS：可选链
来源：http://dali.havefunace.top/Article/details/gttqjmwcup.html

a?.b?.c
来源：http://dali.shuidangran.top/Article/details/gtxzofbfid.html

[U86] JS：空值合并
来源：http://dali.yj20258888.top/Article/details/gtgteysrir.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gtbkrgevwn.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gtsxtfvagh.html

const { a = 1, b = 2 } = obj;
来源：http://dali.fengsongda.top/Article/details/gtlkqxhpft.html

[U88] JS：对象展开合并
来源：http://dali.sufxvd.cn/Article/details/gtymqagatf.html

{ ...a, ...b }
来源：http://dali.xuanzx.com/Article/details/gtzexfhqmp.html

[U89] JS：数组去重
来源：http://dali.hnqzz.top/Article/details/gtbqdctpet.html

[...new Set(arr)]
来源：http://dali.birdmap.top/Article/details/gtwstlcmik.html

[U90] JS：数字数组排序
来源：http://dali.ehwqpu.com/Article/details/gtrchrcddk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gotoacloud.top/Article/details/gtsuwsmlpu.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtsbfhimpe.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhixingplan.top/Article/details/gtsggozgyv.html

[U92] JS：深拷贝
来源：http://dali.fzhhl.top/Article/details/gttcxvavjf.html

structuredClone(obj)
来源：http://dali.jlsjyb.cn/Article/details/gtvlkjuvmu.html

[U93] JS：模板字符串
来源：http://dali.hysaishi.cn/Article/details/gtjjishmvp.html

`共 ${n} 条`
来源：http://dali.zhoulong.xyz/Article/details/gtevaftgdw.html

[U94] JS：箭头函数
来源：http://dali.9152youxi.cn/Article/details/gtzfquthbp.html

const double = x => x * 2;
来源：http://dali.zhiwuduotai.top/Article/details/gtlhvjnstm.html

[U95] JS：Promise 包装
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqsrczny.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtyexjvcyn.html

[U96] JS：async/await 与异常
来源：http://dali.guannengcc.top/Article/details/gtpscjytaq.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.shzxlz.cn/Article/details/gtndbvdedg.html

[U97] JS：并发请求
来源：http://dali.sweek.top/Article/details/gtjzkznsqq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.havefunace.top/Article/details/gtnntmmxfr.html

[U98] JS：fetch 带 JSON
来源：http://dali.yueranfly.top/Article/details/gthfixpoqe.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.quarkkingdee.top/Article/details/gtvxkguewr.html

[U99] JS：事件监听
来源：http://dali.yj20258888.top/Article/details/gtdvlybgif.html

el.addEventListener("click", e => {})
来源：http://dali.guannengcc.top/Article/details/gtigeaguas.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtvmrlqlse.html

document.querySelector(".item")
来源：http://dali.xylfe.cn/Article/details/gtumljddwb.html

[U101] JS：classList 操作
来源：http://dali.316326.xyz/Article/details/gtnkopajmd.html

el.classList.toggle("active")
来源：http://dali.meibo888.top/Article/details/gtoxemrktu.html

[U102] JS：本地存储
来源：http://dali.sxryk.cn/Article/details/gtsnkfizjv.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.xuanzx.com/Article/details/gtacfvrsch.html

[U103] JS：定时器
来源：http://dali.shuidangran.top/Article/details/gtbsssemap.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.vqdsnc.cn/Article/details/gthhojxddm.html

[U104] JS：防抖
来源：http://dali.quarkkingdee.top/Article/details/gtlfdnvdxo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.iojbl.cn/Article/details/gtzjuekztu.html

[U105] JS：节流
来源：http://dali.daxiang520.top/Article/details/gtzauvuwko.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hnqzz.top/Article/details/gtvbnwmgbl.html

[U106] JS：日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtmuzejtlt.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fzhhl.top/Article/details/gtxclprzcw.html

[U107] JS：数字千分位
来源：http://dali.shangyingyoupin.top/Article/details/gtzsrolxwt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gtcezdwwhe.html

[U108] JS：随机整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthmmdvlue.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.daxiang520.top/Article/details/gtpsrwfzcx.html

[U109] JS：数组分组
来源：http://dali.gaohongyu789.top/Article/details/gtfdjedkjp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtuqeochkt.html

[U110] JS：数组分块
来源：http://dali.dianchejie.cn/Article/details/gtvypsrjje.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gtsdkhgfrl.html

[U111] JS：对象转 Map
来源：http://dali.yueranfly.top/Article/details/gtooxeahvu.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gtbmavozat.html

[U112] JS：字符串补位
来源：http://dali.yongpay.top/Article/details/gtmlyjebgt.html

"7".padStart(3, "0")
来源：http://dali.wangshuangyany.cn/Article/details/gtcwicjlnm.html

[U113] JS：正则替换全部
来源：http://dali.yuanzhike.top/Article/details/gtdeajskai.html

s.replaceAll("a", "b")
来源：http://dali.ehwqpu.com/Article/details/gtzfpodlgj.html

[U114] JS：JSON 深比较
来源：http://dali.fzhhl.top/Article/details/gtjximqzxm.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhijiandao.cn/Article/details/gtdzjspsij.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtvmyjdyxn.html

crypto.randomUUID()
来源：http://dali.snrcjt.cn/Article/details/gtwoudqwvm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gogol.net.cn/Article/details/gtbyiwrryw.html

/** @param {string} name */ function f(name) {}
来源：http://dali.daxiang520.top/Article/details/gtdprjmfif.html

[U117] JS：单元测试
来源：http://dali.hysaishi.cn/Article/details/gthylivqwp.html

npm i -D vitest;  npx vitest
来源：http://dali.yj202588.top/Article/details/gtqyyauloa.html

[U118] JS：开发服务器
来源：http://dali.sxryk.cn/Article/details/gtyawedpep.html

npm i -D vite;  npx vite
来源：http://dali.jlsjyb.cn/Article/details/gtfqlmvofh.html

[U119] JS：生产构建
来源：http://dali.cqqwz.cn/Article/details/gtaqcftmsw.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gtljoatnes.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtequuqole.html

import.meta.env.VITE_API_URL
来源：http://dali.yueranfly.top/Article/details/gtndoxxvwc.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtnhuwowav.html

统计汇总
来源：http://dali.sysykeji.top/Article/details/gttagqdxiu.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtagopgdxy.html

按语言统计（条）：
来源：http://dali.bjfxy.top/Article/details/gtpsqsqsrc.html

Python ......... 252
来源：http://dali.dianchejie.cn/Article/details/gtzwequznf.html

PHP ............ 252
来源：http://dali.mhx1999.top/Article/details/gtvjuflsal.html

JavaScript ..... 252
来源：http://dali.nanxuanxn.top/Article/details/gtzrxgbsno.html

TypeScript ..... 212
来源：http://dali.gogol.net.cn/Article/details/gterncafev.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gthbviahnm.html

Go ............. 212
来源：http://dali.cdnleiting.top/Article/details/gtmlewioka.html

Ruby ........... 212
来源：http://dali.wangshuangyany.cn/Article/details/gtfaiuaklf.html

C# ............. 212
来源：http://dali.zhengqikj.top/Article/details/gttdhquibt.html

C .............. 30
来源：http://dali.pengpengdd.cyou/Article/details/gtjukvbsnr.html

C++ ............ 30
来源：http://dali.yj202588.top/Article/details/gttmuwubbd.html

SQL ............ 90
来源：http://dali.yj20258888.top/Article/details/gtuxomihpn.html

Bash ........... 80
来源：http://dali.ppjwa.cn/Article/details/gthuabbhkg.html

Kotlin ......... 15
来源：http://dali.hnqzz.top/Article/details/gtzgszsqqe.html

Swift .......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtxgdsglbt.html

Lua ............ 10
来源：http://dali.dianchejie.cn/Article/details/gttbgnneme.html

Perl ........... 10
来源：http://dali.ppjwa.cn/Article/details/gtgbxszvlk.html

Scala .......... 10
来源：http://dali.wangdashe.top/Article/details/gtrjfoiaqd.html

------------------------------------
来源：http://dali.pengpengdd.cyou/Article/details/gturlhjtgg.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gtkvpyguga.html

按章节统计：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtveazwvpo.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.birdmap.top/Article/details/gthnnlrvhd.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.wangdashe.top/Article/details/gtzyiuxlkc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtevglkojv.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cqqwz.cn/Article/details/gtawuuhurc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jqgfzy.top/Article/details/gtamzljyen.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yj20258.top/Article/details/gtvykbuwsq.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuetiantiany.cn/Article/details/gtxxxoxwxy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.meibo888.top/Article/details/gtgjzmoynl.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gthgaotccg.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtqnzqifvq.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.havefunace.top/Article/details/gtckdabewc.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.fzhhl.top/Article/details/gtnfxpapzf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gtigcajgiu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtbzephvmv.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.yongpay.top/Article/details/gtqdzbqvhz.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yongpay.top/Article/details/gtujhfucfy.html

Q SQL 专题                              90
来源：http://dali.zhijiandao.cn/Article/details/gtnyubyckp.html

R Bash 专题                             80
来源：http://dali.sweek.top/Article/details/gtvswisupo.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gtrjiaaxjf.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gtuksagynf.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtylhsacmj.html

------------------------------------
来源：http://dali.bjfxy.top/Article/details/gtdnesifox.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gtlesqqdtk.html

--------------------------------------------------------------------------------
来源：http://dali.zycfv.cn/Article/details/gtnxamvfvn.html

使用提醒
来源：http://dali.dianchejie.cn/Article/details/gtdfjjlggn.html

--------------------------------------------------------------------------------
来源：http://dali.shuidangran.top/Article/details/gtfljeahwg.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xuanzx.com/Article/details/gtmalsrvnr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hongshengwenyu.top/Article/details/gtjxuvmgkr.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.shangyingyoupin.top/Article/details/gtbuxdmxwm.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.aizwys.cn/Article/details/gtzznpusge.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.guowangkeji.top/Article/details/gtskcajwio.html

—— 文件结束 ——
来源：http://dali.hywenlv.cn/Article/details/gtzjubswzj.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtiohmmstz.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.zhiwuduotai.top/Article/details/gtqhintfrh.html

Common Programming Examples Cheat Book
来源：http://dali.xinyue.icu/Article/details/gtvnlzegnl.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtypchzzkt.html


<!-- 参考信息 -->