代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.ydzc1.top/Article/details/gtlyorssgy.html

[T57] Scala：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtqhwnoxsm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gthqnbfsap.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtfgkahwrg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenzaomai.com/Article/details/gtlrvstfnb.html

[T59] Scala：循环
来源：http://dali.zhengqikj.top/Article/details/gtkwkmpfpq.html

for (i <- 1 to 10) println(i)
来源：http://dali.tianlin.xyz/Article/details/gthepgyzbq.html

[T60] Scala：折叠
来源：http://dali.zhiwuduotai.top/Article/details/gtyzkekufj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gtiiiymrrm.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtgxyigkrp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jiagoushi.top/Article/details/gtgbojossl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtwttjjkbu.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gtusqgfkci.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xinyue.icu/Article/details/gthzlghodq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.birdmap.top/Article/details/gtmvhrvbzk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cucudq.cn/Article/details/gtdirjzoyz.html

[U03] Py：加载 .env 配置
来源：http://dali.meibo888.top/Article/details/gtptagemyg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ehwqpu.com/Article/details/gtcgiypirl.html

[U04] Py：变量调试打印
来源：http://dali.zhengqikj.top/Article/details/gtvnlewxlu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtyjcywinw.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtavsuuabf.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtjzltcwqw.html

[U06] Py：合并两个字典
来源：http://dali.fengsongda.top/Article/details/gtgnhppooo.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtrjjfgqiz.html

[U07] Py：反转字典键值
来源：http://dali.aizwys.cn/Article/details/gtpgyepkgx.html

{v: k for k, v in d.items()}
来源：http://dali.bjfxy.top/Article/details/gtertddbcq.html

[U08] Py：展平二维列表
来源：http://dali.feifeiyinyue.top/Article/details/gtvvwgmoxl.html

[y for x in nested for y in x]
来源：http://dali.yanxiufei.cn/Article/details/gttlnelupu.html

[U09] Py：字典取最大值的键
来源：http://dali.ehwqpu.com/Article/details/gtyglkcfwy.html

max(d, key=d.get)
来源：http://dali.sxryk.cn/Article/details/gtlakuwikq.html

[U10] Py：按值排序字典
来源：http://dali.xuanzx.com/Article/details/gtppevzpav.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfubissiq.html

[U11] Py：生成器表达式
来源：http://dali.mhx1999.top/Article/details/gtbabmlfbp.html

(x * 2 for x in arr)
来源：http://dali.daxiang520.top/Article/details/gtnqflvnzl.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gtnpstotgz.html

Counter(arr).most_common(3)
来源：http://dali.cqqwz.cn/Article/details/gtwjqekoyf.html

[U13] Py：固定长度队列
来源：http://dali.chenjidiqi.icu/Article/details/gtszsfnzzd.html

deque(maxlen=10)
来源：http://dali.wangshuangyany.cn/Article/details/gtarfxvmcg.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtogsdkrxs.html

defaultdict(list)
来源：http://dali.pengpengdd.cyou/Article/details/gtweytpitr.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gtmesbedby.html

t = time.perf_counter()
来源：http://dali.chenzaomai.com/Article/details/gtwksrzzot.html

[U16] Py：命令行参数解析
来源：http://dali.c1oappe.top/Article/details/gtbsvtgpoh.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.xuetiantiany.cn/Article/details/gtatitmeus.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtcicqdnxk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.jiagoushi.top/Article/details/gtgpnallbc.html

[U18] Py：预编译正则
来源：http://dali.dashuyun.cn/Article/details/gtzaxsyzaw.html

pat = re.compile(r"\d+")
来源：http://dali.bjfxy.top/Article/details/gtgeleynez.html

[U19] Py：正则替换带回调
来源：http://dali.pengpengdd.cyou/Article/details/gtujriwnvm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.nwbrower.top/Article/details/gtnhlbalkd.html

[U20] Py：缓存函数结果
来源：http://dali.cheryme.top/Article/details/gtlezkyhtb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yj202588.top/Article/details/gtxdtkucgj.html

[U21] Py：自定义上下文管理器
来源：http://dali.nanxuanxn.top/Article/details/gttxolnnks.html

@contextlib.contextmanager
来源：http://dali.chenzaomai.com/Article/details/gtocewwlgb.html

[U22] Py：矩阵转置
来源：http://dali.yj20258888.top/Article/details/gtefcupkmp.html

list(zip(*m))
来源：http://dali.9152youxi.cn/Article/details/gtmoifejdt.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtzphrrpgi.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtdejrhjhr.html

[U24] Py：路径操作
来源：http://dali.yuxming.cn/Article/details/gthvmoefln.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.fzhhl.top/Article/details/gtarebtaib.html

[U25] Py：CSV 按字典读
来源：http://dali.jinqigufen.top/Article/details/gtrtnxivre.html

csv.DictReader(f)
来源：http://dali.gogol.net.cn/Article/details/gtiqdzrcle.html

[U26] Py：并发下载
来源：http://dali.guannengcc.top/Article/details/gtnlnihpdt.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.xuanzx.com/Article/details/gthnxnsglv.html

[U27] Py：异步 HTTP
来源：http://dali.zhoulong.xyz/Article/details/gtcxmocmdo.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.wangdashe.top/Article/details/gtpihggqtd.html

[U28] Py：类型别名
来源：http://dali.yanxiufei.cn/Article/details/gtqqliybgb.html

UserId = int
来源：http://dali.fengsongda.top/Article/details/gtfgttuljx.html

[U29] Py：属性校验
来源：http://dali.zhoulong.xyz/Article/details/gtsksndfmi.html

@property 与 @x.setter 配合
来源：http://dali.yanxiufei.cn/Article/details/gtrlshumox.html

[U30] Py：数据类
来源：http://dali.ehwqpu.com/Article/details/gtfbqttgua.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtmyxfepnz.html

[U31] Py：单测
来源：http://dali.hysaishi.cn/Article/details/gtfndvvute.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtlbczagqe.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gtjzpparnm.html

ruff format . && ruff check --fix .
来源：http://dali.wangdashe.top/Article/details/gthbdwprai.html

[U33] Py：打包发布
来源：http://dali.gaohongyu789.top/Article/details/gtitrfwrij.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yonumen.top/Article/details/gtdagtxxkn.html

[U34] Py：判断编码
来源：http://dali.yj20258888.top/Article/details/gtxfglxxms.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtlffyzmmv.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gtxgqkfskl.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.meibo888.top/Article/details/gtkmlhlyit.html

[U36] Py：定时任务
来源：http://dali.hnxiangtu.top/Article/details/gtawhgpvud.html

schedule.every(10).minutes.do(job)
来源：http://dali.dianchejie.cn/Article/details/gtsuweghcg.html

[U37] Py：读写 Excel
来源：http://dali.yonumen.top/Article/details/gtgtiiwqxc.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj20258.top/Article/details/gtdbxpihrd.html

[U38] Py：获取脚本所在目录
来源：http://dali.daxiang520.top/Article/details/gtxnsjqdpf.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtuybxezel.html

[U39] Py：判断是否在交互环境
来源：http://dali.xuanzx.com/Article/details/gtsnpsfnsa.html

sys.stdout.isatty()
来源：http://dali.chenzaomai.com/Article/details/gtjwxhxrvm.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtdepbyqyc.html

print("err", file=sys.stderr)
来源：http://dali.xuanzx.com/Article/details/gtdbblstju.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.wangshuangyany.cn/Article/details/gtywnxvlao.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.c1oappe.top/Article/details/gthoofqkha.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtarvwkhbp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.xziqi.cn/Article/details/gtmhntbqxx.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtbhvrlhcb.html

namespace App\Http;
来源：http://dali.sxryk.cn/Article/details/gtmnatsncl.html

[U44] PHP：开启严格类型
来源：http://dali.xziqi.cn/Article/details/gtrljjsfkb.html

declare(strict_types=1);
来源：http://dali.feifeiyinyue.top/Article/details/gtvtnwbbcd.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jlsjyb.cn/Article/details/gtbauaiqzx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gtvzpmghyn.html

[U46] PHP：可空类型
来源：http://dali.aizwys.cn/Article/details/gtoahnkdun.html

?string $name = null
来源：http://dali.ivvv.top/Article/details/gtanpztjqp.html

[U47] PHP：联合类型
来源：http://dali.hfpthk.cn/Article/details/gtwxutsbry.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gtpkfbpnyr.html

[U48] PHP：纯枚举
来源：http://dali.gotoacloud.top/Article/details/gtcqwomojt.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yvedp.cn/Article/details/gtamugxndn.html

[U49] PHP：只读属性
来源：http://dali.sweek.top/Article/details/gtngtearge.html

public readonly string $name
来源：http://dali.andypj.xyz/Article/details/gtlixwmvyf.html

[U50] PHP：构造器属性提升
来源：http://dali.haohaochexian.top/Article/details/gthlvtrgjv.html

public function __construct(private int $id) {}
来源：http://dali.sufxvd.cn/Article/details/gtleoleyao.html

[U51] PHP：数组解构
来源：http://dali.yuanzhike.top/Article/details/gtyiethqku.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtxieglgkf.html

[U52] PHP：箭头函数
来源：http://dali.guannengcc.top/Article/details/gtinxpikdu.html

$double = fn($x) => $x * 2;
来源：http://dali.cdnleiting.top/Article/details/gtaknyahot.html

[U53] PHP：空合并运算符
来源：http://dali.ehwqpu.com/Article/details/gtbumzrdcm.html

$v = $a ?? $b ?? "default";
来源：http://dali.nanxinkj.top/Article/details/gtwcezphbc.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gtlkhvfjwn.html

$obj?->method()
来源：http://dali.xinyue.icu/Article/details/gtbsbrqqgr.html

[U55] PHP：match 表达式
来源：http://dali.smart0.xyz/Article/details/gtfxenzhbm.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.shangyingyoupin.top/Article/details/gtpknylmxz.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gtytazighq.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gthtsxaetz.html

[U57] PHP：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtuislplwr.html

"值: {$a}"
来源：http://dali.svipenyu.cn/Article/details/gtphalqxmz.html

[U58] PHP：数组三件套
来源：http://dali.yanxiufei.cn/Article/details/gtdvfkjjxy.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.aizwys.cn/Article/details/gtszzqiyiu.html

[U59] PHP：自定义排序
来源：http://dali.cqqwz.cn/Article/details/gtghouawux.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuanzx.com/Article/details/gtevzgygsc.html

[U60] PHP：JSON 编解码
来源：http://dali.bjfxy.top/Article/details/gtujulxvvb.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxuanxn.top/Article/details/gtkjajgjfc.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gtmhjseupm.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.yj20258888.top/Article/details/gtnyselcbd.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gtjvkohrch.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtakitfmiu.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtkzenezde.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.jiagoushi.top/Article/details/gtanykkqzz.html

[U64] PHP：目录遍历
来源：http://dali.cucudq.cn/Article/details/gtmbmwfgxr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gaohongyu789.top/Article/details/gtoksbzmvu.html

[U65] PHP：会话
来源：http://dali.aibaodan.cn/Article/details/gtffuvhfoo.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.andypj.xyz/Article/details/gtzscwzooz.html

[U66] PHP：设置 Cookie
来源：http://dali.jqgufenzy.top/Article/details/gtuhdsafns.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.quarkkingdee.top/Article/details/gtrmgpdguo.html

[U67] PHP：处理文件上传
来源：http://dali.birdmap.top/Article/details/gtjeezsbtg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nwbrower.top/Article/details/gtlpbxyrxg.html

[U68] PHP：PDO 连接
来源：http://dali.iojbl.cn/Article/details/gtuztbkkht.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.tianlin.xyz/Article/details/gtzhfxwwvr.html

[U69] PHP：PDO 预处理
来源：http://dali.gzhubu.top/Article/details/gtwaacslno.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zdqjudy.top/Article/details/gtkgzpheeh.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gtkdohhmez.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.nanxuanxn.top/Article/details/gtgwftaczr.html

[U71] PHP：抛出异常
来源：http://dali.dianchejie.cn/Article/details/gtxqschzna.html

throw new RuntimeException("失败", 500);
来源：http://dali.nwbrower.top/Article/details/gtlcbbagvr.html

[U72] PHP：写错误日志
来源：http://dali.zhengqikj.top/Article/details/gtqerfmkhs.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuanzx.com/Article/details/gtkujpseeu.html

[U73] PHP：读取 ini 配置
来源：http://dali.cucudq.cn/Article/details/gtrfggceyj.html

parse_ini_file("config.ini", true)
来源：http://dali.ybcxt.top/Article/details/gtjgnievhj.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtflzxpcew.html

getenv("APP_ENV") ?: "production"
来源：http://dali.wangshuangyany.cn/Article/details/gthujdzkbr.html

[U75] PHP：依赖注入
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvncebsvk.html

composer require psr/container
来源：http://dali.fengsongda.top/Article/details/gttivrdnqd.html

[U76] PHP：简单路由
来源：http://dali.nanxuanxn.top/Article/details/gtptfzomlt.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.shzxlz.cn/Article/details/gtgfgeqlhm.html

[U77] PHP：模板渲染
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluxfwkjx.html

composer require twig/twig
来源：http://dali.andypj.xyz/Article/details/gtvvqwpfkd.html

[U78] PHP：单元测试
来源：http://dali.ydzc1.top/Article/details/gtqouwsdbw.html

composer require --dev phpunit/phpunit
来源：http://dali.hysaishi.cn/Article/details/gtftdiwvnz.html

[U79] PHP：静态分析
来源：http://dali.nanxinkj.top/Article/details/gtwkaoawox.html

composer require --dev phpstan/phpstan
来源：http://dali.ydzc1.top/Article/details/gttfnwhxgz.html

[U80] PHP：代码规范修复
来源：http://dali.ydzc1.top/Article/details/gtrppfnrfj.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tian-w.cn/Article/details/gtkeareooa.html

[U81] JS：初始化项目
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuzvrbse.html

npm init -y;  npm i express
来源：http://dali.svipenyu.cn/Article/details/gtzgatymct.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtflpayazc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.ydzc1.top/Article/details/gtqjqblpjm.html

[U83] JS：ES Module 导入导出
来源：http://dali.sxryk.cn/Article/details/gtuiwwdtck.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.dashuyun.cn/Article/details/gtvzdrqpeu.html

[U84] JS：CommonJS 写法
来源：http://dali.9152youxi.cn/Article/details/gtblrdipgi.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.0kj1m.cn/Article/details/gtujcbwsws.html

[U85] JS：可选链
来源：http://dali.hywenlv.cn/Article/details/gtzmppfaef.html

a?.b?.c
来源：http://dali.aizwys.cn/Article/details/gtkcuxidph.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gtgclflscx.html

a ?? b
来源：http://dali.bjfxy.top/Article/details/gtrzqjqkil.html

[U87] JS：解构默认值
来源：http://dali.ydzc1.top/Article/details/gtozfbjgyx.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xuanzx.com/Article/details/gtcxwzkylp.html

[U88] JS：对象展开合并
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyjefynhk.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gtpmilksho.html

[U89] JS：数组去重
来源：http://dali.ybcxt.top/Article/details/gttvkrlreg.html

[...new Set(arr)]
来源：http://dali.ydzc1.top/Article/details/gtpbvyaejk.html

[U90] JS：数字数组排序
来源：http://dali.yj20258.top/Article/details/gtafzigqyf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.nanxuanxn.top/Article/details/gtttkbpaod.html

[U91] JS：对象键值遍历
来源：http://dali.jqgfzy.top/Article/details/gtxrwemgof.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gtrstcrilt.html

[U92] JS：深拷贝
来源：http://dali.sweek.top/Article/details/gtkvuzffoe.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gtbirkayac.html

[U93] JS：模板字符串
来源：http://dali.yangfankeji.com/Article/details/gteaxjulvu.html

`共 ${n} 条`
来源：http://dali.yj202588.top/Article/details/gtrvsljmdm.html

[U94] JS：箭头函数
来源：http://dali.redwolf501.top/Article/details/gtqmvgxmry.html

const double = x => x * 2;
来源：http://dali.wangshuangyany.cn/Article/details/gtighxtmtt.html

[U95] JS：Promise 包装
来源：http://dali.hongshengwenyu.top/Article/details/gtqfjvvuqz.html

new Promise((resolve, reject) => {})
来源：http://dali.hywenlv.cn/Article/details/gtilmvajtm.html

[U96] JS：async/await 与异常
来源：http://dali.jlsjyb.cn/Article/details/gtxmlrdyuz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.tianlin.xyz/Article/details/gtcrjsevnd.html

[U97] JS：并发请求
来源：http://dali.yj20258.top/Article/details/gttglqxceb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jqgufenzy.top/Article/details/gtrxncmptd.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxeuzyonm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gtgkgphyby.html

[U99] JS：事件监听
来源：http://dali.aizwys.cn/Article/details/gtmexqbyfr.html

el.addEventListener("click", e => {})
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyaqtefu.html

[U100] JS：DOM 查询
来源：http://dali.chenjidiqi.icu/Article/details/gtfcqbraaw.html

document.querySelector(".item")
来源：http://dali.yvedp.cn/Article/details/gtsyszlvij.html

[U101] JS：classList 操作
来源：http://dali.dashuyun.cn/Article/details/gthvhnmtcn.html

el.classList.toggle("active")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljeyfoan.html

[U102] JS：本地存储
来源：http://dali.haohaochexian.top/Article/details/gtpjafmjnb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.daxiang520.top/Article/details/gthdmcijvf.html

[U103] JS：定时器
来源：http://dali.xuetiantiany.cn/Article/details/gtxkinyeuc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.meibo888.top/Article/details/gtmiaoisgt.html

[U104] JS：防抖
来源：http://dali.0kj1m.cn/Article/details/gtxaktrwrp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.redwolf501.top/Article/details/gtezkzpicp.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gtwivlyjtx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfydzadrr.html

[U106] JS：日期格式化
来源：http://dali.birdmap.top/Article/details/gtrdxfmyxj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.fengsongda.top/Article/details/gtzbnhczym.html

[U107] JS：数字千分位
来源：http://dali.shuidangran.top/Article/details/gttpvkjjcv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gtnrpakyuy.html

[U108] JS：随机整数
来源：http://dali.daria6918.cn/Article/details/gtdxkmrizd.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ppjwa.cn/Article/details/gtshgsduoo.html

[U109] JS：数组分组
来源：http://dali.yj202588.top/Article/details/gtnpujwehy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.sxryk.cn/Article/details/gtfvsboijn.html

[U110] JS：数组分块
来源：http://dali.sweek.top/Article/details/gtvnkvjxnv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shuidangran.top/Article/details/gtmcildunt.html

[U111] JS：对象转 Map
来源：http://dali.yanxiufei.cn/Article/details/gtqclijwod.html

new Map(Object.entries(obj))
来源：http://dali.jlsjyb.cn/Article/details/gtysmongpy.html

[U112] JS：字符串补位
来源：http://dali.jqgufenzy.top/Article/details/gtttvwqwes.html

"7".padStart(3, "0")
来源：http://dali.zhiwuduotai.top/Article/details/gtyikqpdug.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gtgpgxunjq.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gtrsvwfqsx.html

[U114] JS：JSON 深比较
来源：http://dali.0kj1m.cn/Article/details/gtgniayowx.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqphimgiw.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtagvmfqzk.html

crypto.randomUUID()
来源：http://dali.ppjwa.cn/Article/details/gtzvyggqnx.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhoulong.xyz/Article/details/gtoltlbbvx.html

/** @param {string} name */ function f(name) {}
来源：http://dali.gzhubu.top/Article/details/gtukqvjwrt.html

[U117] JS：单元测试
来源：http://dali.nanxuanxn.top/Article/details/gtmqdylceo.html

npm i -D vitest;  npx vitest
来源：http://dali.yuanzhike.top/Article/details/gtwpfwmarw.html

[U118] JS：开发服务器
来源：http://dali.yj202588.top/Article/details/gtenfcgeso.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gtppnfntax.html

[U119] JS：生产构建
来源：http://dali.chenjidiqi.icu/Article/details/gtrddkjuiq.html

npx vite build
来源：http://dali.aizwys.cn/Article/details/gtlkndmyrl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenzaomai.com/Article/details/gtbjqenvxx.html

import.meta.env.VITE_API_URL
来源：http://dali.yj202588.top/Article/details/gtprfowfyj.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtxgglwcfj.html

统计汇总
来源：http://dali.tanke756.top/Article/details/gtshfpxqvc.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtduxriimh.html

按语言统计（条）：
来源：http://dali.hysaishi.cn/Article/details/gtkphcirnb.html

Python ......... 252
来源：http://dali.meibo888.top/Article/details/gtenbpnlgh.html

PHP ............ 252
来源：http://dali.gzhubu.top/Article/details/gtwhgvpkeu.html

JavaScript ..... 252
来源：http://dali.hammf.cn/Article/details/gtgmkuoald.html

TypeScript ..... 212
来源：http://dali.pycfn.com/Article/details/gtbeouimpj.html

Java ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtxhoraisc.html

Go ............. 212
来源：http://dali.hnxiangtu.top/Article/details/gtzppypwhr.html

Ruby ........... 212
来源：http://dali.redwolf501.top/Article/details/gtiiaodyul.html

C# ............. 212
来源：http://dali.hfpthk.cn/Article/details/gtmbkoqlqp.html

C .............. 30
来源：http://dali.yuanzhike.top/Article/details/gtzeihcsah.html

C++ ............ 30
来源：http://dali.xylfe.cn/Article/details/gtispslpnz.html

SQL ............ 90
来源：http://dali.tianlin.xyz/Article/details/gtcmtcogkz.html

Bash ........... 80
来源：http://dali.ybcxt.top/Article/details/gtxabrxovo.html

Kotlin ......... 15
来源：http://dali.aibaodan.cn/Article/details/gtkjzujeab.html

Swift .......... 15
来源：http://dali.gotoacloud.top/Article/details/gtihlakwkg.html

Lua ............ 10
来源：http://dali.gogol.net.cn/Article/details/gtevezidvs.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gtfsjypibz.html

Scala .......... 10
来源：http://dali.mhx1999.top/Article/details/gtdiaakgjd.html

------------------------------------
来源：http://dali.fengsongda.top/Article/details/gtqwwzbewx.html

合计 ........... 2106 条
来源：http://dali.jianghu66.top/Article/details/gterwrmpkh.html

按章节统计：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmjapsre.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gtlwxfrawt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinqigfzy.top/Article/details/gtyehalwfz.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.aizwys.cn/Article/details/gtlqeojddm.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtgceisdim.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.yueranfly.top/Article/details/gtnnrtqziz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.wangshuangyany.cn/Article/details/gtknuouatn.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gttpcimuxo.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtnohpxkoc.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gttfkbcsse.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.xziqi.cn/Article/details/gtpoyxjryl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtynlyqewy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtdtswaqnw.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gtwlqcqiaq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtcvwkxjoa.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gtzsnhqbao.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgnvfwqz.html

Q SQL 专题                              90
来源：http://dali.yj202588.top/Article/details/gtfhjwtjzd.html

R Bash 专题                             80
来源：http://dali.zhijiandao.cn/Article/details/gtgawshkqf.html

S C / C++ 专题                          60
来源：http://dali.zdqjudy.top/Article/details/gtftaalwaq.html

T 其他语言补充                          60
来源：http://dali.yanxiufei.cn/Article/details/gtmpwhtrmm.html

U 高频实用片段                         120
来源：http://dali.zhongyouzk.top/Article/details/gtlpxclyes.html

------------------------------------
来源：http://dali.ppjwa.cn/Article/details/gtlvmhfvhg.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtravcffuc.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gtisrnrqjy.html


<!-- 参考信息 -->