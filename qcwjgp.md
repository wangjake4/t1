代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnqzz.top/Article/details/gtwnyqkick.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtrvymxabx.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtvevelocf.html

[T60] Scala：折叠
来源：http://dali.hfpthk.cn/Article/details/gtetyvvloh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.guowangkeji.top/Article/details/gtqoacikhh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtcmujvusf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtzacuctbk.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtsxsykidw.html

[U01] Py：创建虚拟环境
来源：http://dali.bjfxy.top/Article/details/gtwnmxyrqp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtzbnkqqob.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gtysbpkmtx.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.fengsongda.top/Article/details/gtlhmeuykb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhongyouzk.top/Article/details/gtexfqrvpl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtyxrdloxa.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gteevlszas.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.sweek.top/Article/details/gtremxmrdr.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtcfjtkhjc.html

list(dict.fromkeys(arr))
来源：http://dali.jqgfzy.top/Article/details/gtzvqvpdsk.html

[U06] Py：合并两个字典
来源：http://dali.yj20258.top/Article/details/gtzunkzrqg.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtwyrwdvem.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gtdtottlor.html

{v: k for k, v in d.items()}
来源：http://dali.jqgfzy.top/Article/details/gtkhzzuest.html

[U08] Py：展平二维列表
来源：http://dali.svipenyu.cn/Article/details/gtsfteaanj.html

[y for x in nested for y in x]
来源：http://dali.yj20258.top/Article/details/gtznkrhmpl.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtsgtwsdvt.html

max(d, key=d.get)
来源：http://dali.yuanzhike.top/Article/details/gtxtkeehwa.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtmhfpubwy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gtotcqthmh.html

[U11] Py：生成器表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtirgegsat.html

(x * 2 for x in arr)
来源：http://dali.xuanzx.com/Article/details/gtghgibxtw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtenmztubs.html

Counter(arr).most_common(3)
来源：http://dali.jinqigufen.top/Article/details/gtnmrmloym.html

[U13] Py：固定长度队列
来源：http://dali.hammf.cn/Article/details/gtiamkdwrp.html

deque(maxlen=10)
来源：http://dali.xylfe.cn/Article/details/gtxghxchgv.html

[U14] Py：分组收集到列表
来源：http://dali.wangshuangyany.cn/Article/details/gtmwquiikk.html

defaultdict(list)
来源：http://dali.mhx1999.top/Article/details/gtibdsznhn.html

[U15] Py：高精度计时
来源：http://dali.aizwys.cn/Article/details/gtsgcgbzgj.html

t = time.perf_counter()
来源：http://dali.cdnleiting.top/Article/details/gtmeopwcpd.html

[U16] Py：命令行参数解析
来源：http://dali.aizwys.cn/Article/details/gtejvgnlow.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yanxiufei.cn/Article/details/gtuybnuucn.html

[U17] Py：初始化日志
来源：http://dali.sufxvd.cn/Article/details/gtvvmpmzhw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.bjfxy.top/Article/details/gtvjastwqm.html

[U18] Py：预编译正则
来源：http://dali.sxryk.cn/Article/details/gtlbkqoyjy.html

pat = re.compile(r"\d+")
来源：http://dali.nwbrower.top/Article/details/gtbcmtdzdo.html

[U19] Py：正则替换带回调
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpmyukzag.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtsguamtei.html

[U20] Py：缓存函数结果
来源：http://dali.chenlongwang.top/Article/details/gtrzgwzroj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hnxiangtu.top/Article/details/gtumwdvjow.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gtojvwiwgq.html

@contextlib.contextmanager
来源：http://dali.hongshengwenyu.top/Article/details/gthtgxqblj.html

[U22] Py：矩阵转置
来源：http://dali.yueranfly.top/Article/details/gtqazuxdfl.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gttrpoxzbt.html

[U23] Py：分块读取大文件
来源：http://dali.jqgfzy.top/Article/details/gtgyljrrts.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hongshengwenyu.top/Article/details/gtbhbegoih.html

[U24] Py：路径操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfibmwws.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.sxryk.cn/Article/details/gtkgcrahnu.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtqfizzeoz.html

csv.DictReader(f)
来源：http://dali.ehwqpu.com/Article/details/gtxclrkbks.html

[U26] Py：并发下载
来源：http://dali.nanxinkj.top/Article/details/gtlhymkorb.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.hysaishi.cn/Article/details/gtfjxjlfbe.html

[U27] Py：异步 HTTP
来源：http://dali.xylfe.cn/Article/details/gtkxzdtqks.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.hysaishi.cn/Article/details/gtzjezcbbv.html

[U28] Py：类型别名
来源：http://dali.daria6918.cn/Article/details/gtorndzecb.html

UserId = int
来源：http://dali.hammf.cn/Article/details/gtfvyjpzgx.html

[U29] Py：属性校验
来源：http://dali.havefunace.top/Article/details/gtovcfsxmi.html

@property 与 @x.setter 配合
来源：http://dali.ppjwa.cn/Article/details/gtlvoubhjw.html

[U30] Py：数据类
来源：http://dali.snrcjt.cn/Article/details/gtbxbwshcg.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwdoadask.html

[U31] Py：单测
来源：http://dali.xinyue.icu/Article/details/gtloplrnbe.html

python -m pytest -q
来源：http://dali.yj202588.top/Article/details/gtugogbgod.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtuxfuycdv.html

ruff format . && ruff check --fix .
来源：http://dali.nanxuanxn.top/Article/details/gtgfxdbnzq.html

[U33] Py：打包发布
来源：http://dali.jinqigufen.top/Article/details/gtqltixvtp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.xinyue.icu/Article/details/gtbzzhxazn.html

[U34] Py：判断编码
来源：http://dali.ydzc1.top/Article/details/gtmqssnkye.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtossjvuiw.html

[U35] Py：发送邮件
来源：http://dali.chenzaomai.com/Article/details/gtyuoyzkuo.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhiwuduotai.top/Article/details/gtzxvuwxws.html

[U36] Py：定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtdeprzrzg.html

schedule.every(10).minutes.do(job)
来源：http://dali.sufxvd.cn/Article/details/gtrfpvyuie.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gttiuukprq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.iojbl.cn/Article/details/gtdaowcdth.html

[U38] Py：获取脚本所在目录
来源：http://dali.quarkkingdee.top/Article/details/gtinwzqjni.html

Path(__file__).resolve().parent
来源：http://dali.cucudq.cn/Article/details/gtbytyrgyd.html

[U39] Py：判断是否在交互环境
来源：http://dali.aizwys.cn/Article/details/gtabfyyavu.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gthwoxefiz.html

[U40] Py：打印到标准错误
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteajgmppa.html

print("err", file=sys.stderr)
来源：http://dali.hongshengwenyu.top/Article/details/gtowwrfxbb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.hnqzz.top/Article/details/gtltuzskcl.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gthmdiwlhr.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.zhijiandao.cn/Article/details/gtgjjnftet.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.shuidangran.top/Article/details/gtsukmsabm.html

[U43] PHP：声明命名空间
来源：http://dali.shzxlz.cn/Article/details/gtbehfllil.html

namespace App\Http;
来源：http://dali.feifeiyinyue.top/Article/details/gtmlhsznmh.html

[U44] PHP：开启严格类型
来源：http://dali.sysykeji.top/Article/details/gthyhsinmf.html

declare(strict_types=1);
来源：http://dali.meibo888.top/Article/details/gtoklfenys.html

[U45] PHP：类型声明与返回类型
来源：http://dali.0kj1m.cn/Article/details/gtinmmebjk.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtakjixvpp.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gtvuckgejj.html

?string $name = null
来源：http://dali.xuetiantiany.cn/Article/details/gtjhyysedj.html

[U47] PHP：联合类型
来源：http://dali.316326.xyz/Article/details/gtymlfujrj.html

int|string $id
来源：http://dali.ydzc1.top/Article/details/gtgaawkakt.html

[U48] PHP：纯枚举
来源：http://dali.shuidangran.top/Article/details/gtbcjcmxvi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xuanzx.com/Article/details/gtekbcrhxx.html

[U49] PHP：只读属性
来源：http://dali.wangdashe.top/Article/details/gtmxvpgfvn.html

public readonly string $name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvszsabp.html

[U50] PHP：构造器属性提升
来源：http://dali.c1oappe.top/Article/details/gtbonuwynq.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtwmthgatn.html

[U51] PHP：数组解构
来源：http://dali.dianchejie.cn/Article/details/gtobriuvwf.html

[$a, $b] = $arr;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsutensfd.html

[U52] PHP：箭头函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxhdexygi.html

$double = fn($x) => $x * 2;
来源：http://dali.svipenyu.cn/Article/details/gttrkerfiz.html

[U53] PHP：空合并运算符
来源：http://dali.hnqzz.top/Article/details/gthilxkzug.html

$v = $a ?? $b ?? "default";
来源：http://dali.sweek.top/Article/details/gtbcjyuepz.html

[U54] PHP：空安全调用
来源：http://dali.zdqjudy.top/Article/details/gtlkvjpowr.html

$obj?->method()
来源：http://dali.cdnleiting.top/Article/details/gtpwpjoxih.html

[U55] PHP：match 表达式
来源：http://dali.jqgfzy.top/Article/details/gtrsbayuny.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtxifgatbb.html

[U56] PHP：命名参数
来源：http://dali.sxryk.cn/Article/details/gtutqduwza.html

f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtfpriodgt.html

[U57] PHP：字符串插值
来源：http://dali.yj202588.top/Article/details/gtxjydhrhi.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gtueqetadi.html

[U58] PHP：数组三件套
来源：http://dali.jqgfzy.top/Article/details/gtjecddybt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.meibo888.top/Article/details/gtkruqqeaf.html

[U59] PHP：自定义排序
来源：http://dali.yj20258.top/Article/details/gtemfxwkiw.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yueranfly.top/Article/details/gteewohstf.html

[U60] PHP：JSON 编解码
来源：http://dali.xziqi.cn/Article/details/gtcdguknxm.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.xinyue.icu/Article/details/gtdsprzfzu.html

[U61] PHP：正则
来源：http://dali.ybcxt.top/Article/details/gtsdclumnp.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.tanke756.top/Article/details/gtvkxccpth.html

[U62] PHP：日期对象
来源：http://dali.tian-w.cn/Article/details/gthvzxmcep.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnxiangtu.top/Article/details/gtmymifata.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtdyznqqmh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.fzhhl.top/Article/details/gttmvrlgpd.html

[U64] PHP：目录遍历
来源：http://dali.jqgfzy.top/Article/details/gtkcglfadc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gtbzydhfin.html

[U65] PHP：会话
来源：http://dali.hfpthk.cn/Article/details/gtljmqgzxx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.gotoacloud.top/Article/details/gtzqqbdxjs.html

[U66] PHP：设置 Cookie
来源：http://dali.redwolf501.top/Article/details/gtmejgoznn.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gaohongyu789.top/Article/details/gtuostfpzr.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gtwcitmhni.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.fzhhl.top/Article/details/gtdzfezgon.html

[U68] PHP：PDO 连接
来源：http://dali.cdnleiting.top/Article/details/gtjncrxodo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.smart0.xyz/Article/details/gtcobbdvru.html

[U69] PHP：PDO 预处理
来源：http://dali.zhongyouzk.top/Article/details/gtddxyuqmc.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.haohaochexian.top/Article/details/gtbqzfxbls.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gtxckzaxan.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenjidiqi.icu/Article/details/gthxzjeahm.html

[U71] PHP：抛出异常
来源：http://dali.chenlongwang.top/Article/details/gtmolnscxc.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gttbyqkdjp.html

[U72] PHP：写错误日志
来源：http://dali.hfpthk.cn/Article/details/gtfaolemxo.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nanxuanxn.top/Article/details/gtmiiwzsrz.html

[U73] PHP：读取 ini 配置
来源：http://dali.yueranfly.top/Article/details/gttnmwuwfa.html

parse_ini_file("config.ini", true)
来源：http://dali.yonumen.top/Article/details/gtcbwllsxx.html

[U74] PHP：读取环境变量
来源：http://dali.9152youxi.cn/Article/details/gtbtahdgih.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gzhubu.top/Article/details/gtacarkwzc.html

[U75] PHP：依赖注入
来源：http://dali.cucudq.cn/Article/details/gthdelvjwf.html

composer require psr/container
来源：http://dali.birdmap.top/Article/details/gtbovbahht.html

[U76] PHP：简单路由
来源：http://dali.zhixingplan.top/Article/details/gthcpcszav.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zycfv.cn/Article/details/gtkgaisjzr.html

[U77] PHP：模板渲染
来源：http://dali.zhijiandao.cn/Article/details/gtoqtgydng.html

composer require twig/twig
来源：http://dali.tanke756.top/Article/details/gtkxdkyjvu.html

[U78] PHP：单元测试
来源：http://dali.xziqi.cn/Article/details/gtbhsfrxqa.html

composer require --dev phpunit/phpunit
来源：http://dali.yj20258.top/Article/details/gtpvppzwzb.html

[U79] PHP：静态分析
来源：http://dali.shuidangran.top/Article/details/gtzqyfhskv.html

composer require --dev phpstan/phpstan
来源：http://dali.jinqigufen.top/Article/details/gtynmiieqp.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gttwjnjllb.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fengsongda.top/Article/details/gtaiehldvx.html

[U81] JS：初始化项目
来源：http://dali.zhixingplan.top/Article/details/gtfrqscvot.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gtmkumhatg.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gthyjeffrv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.0kj1m.cn/Article/details/gtzmfsoawp.html

[U83] JS：ES Module 导入导出
来源：http://dali.hywenlv.cn/Article/details/gtjelxvtfi.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.tianlin.xyz/Article/details/gtqdmtmkcg.html

[U84] JS：CommonJS 写法
来源：http://dali.yuxming.cn/Article/details/gtcsvebybl.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.aibaodan.cn/Article/details/gtpviemkgz.html

[U85] JS：可选链
来源：http://dali.9152youxi.cn/Article/details/gtncjsasbb.html

a?.b?.c
来源：http://dali.gzhubu.top/Article/details/gtpjljmmxe.html

[U86] JS：空值合并
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomujwybu.html

a ?? b
来源：http://dali.yvedp.cn/Article/details/gtbitmgoug.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtoemwkukv.html

const { a = 1, b = 2 } = obj;
来源：http://dali.dashuyun.cn/Article/details/gtufaxknhf.html

[U88] JS：对象展开合并
来源：http://dali.cdnleiting.top/Article/details/gtsjvhxwla.html

{ ...a, ...b }
来源：http://dali.yonumen.top/Article/details/gtuzbxjvzb.html

[U89] JS：数组去重
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzwnyxgzz.html

[...new Set(arr)]
来源：http://dali.chenlongwang.top/Article/details/gtxzdwrswj.html

[U90] JS：数字数组排序
来源：http://dali.redwolf501.top/Article/details/gtrsfsgmpk.html

[...arr].sort((a, b) => a - b)
来源：http://dali.pengpengdd.cyou/Article/details/gtahjnwtcw.html

[U91] JS：对象键值遍历
来源：http://dali.guowangkeji.top/Article/details/gtbdizvdqz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.gogol.net.cn/Article/details/gtxijbhaoe.html

[U92] JS：深拷贝
来源：http://dali.zdqjudy.top/Article/details/gtrcrevdqh.html

structuredClone(obj)
来源：http://dali.zycfv.cn/Article/details/gttvhnikdx.html

[U93] JS：模板字符串
来源：http://dali.quarkkingdee.top/Article/details/gtahmaefdv.html

`共 ${n} 条`
来源：http://dali.nanxinkj.top/Article/details/gtyctcvfqi.html

[U94] JS：箭头函数
来源：http://dali.svipenyu.cn/Article/details/gttflicmdv.html

const double = x => x * 2;
来源：http://dali.yj20258888.top/Article/details/gtytfplygk.html

[U95] JS：Promise 包装
来源：http://dali.guowangkeji.top/Article/details/gtppbjaajl.html

new Promise((resolve, reject) => {})
来源：http://dali.birdmap.top/Article/details/gtutwhpvnx.html

[U96] JS：async/await 与异常
来源：http://dali.cashguo.top/Article/details/gtzdhwwytb.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtumumfspm.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gtmvmlvdrw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.yj20258.top/Article/details/gtpcolvydc.html

[U98] JS：fetch 带 JSON
来源：http://dali.hysaishi.cn/Article/details/gtjpptoyfz.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.daria6918.cn/Article/details/gtixxdmykx.html

[U99] JS：事件监听
来源：http://dali.c1oappe.top/Article/details/gtugrilxhl.html

el.addEventListener("click", e => {})
来源：http://dali.xylfe.cn/Article/details/gtvaxtjudd.html

[U100] JS：DOM 查询
来源：http://dali.hnxiangtu.top/Article/details/gtlaekycbz.html

document.querySelector(".item")
来源：http://dali.316326.xyz/Article/details/gtbabmmxji.html

[U101] JS：classList 操作
来源：http://dali.0kj1m.cn/Article/details/gtahdvykva.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewdsatcu.html

[U102] JS：本地存储
来源：http://dali.yuanzhike.top/Article/details/gtlrlyxvbm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.cdnleiting.top/Article/details/gtalpjvohq.html

[U103] JS：定时器
来源：http://dali.pengpengdd.cyou/Article/details/gtadxmzgdr.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.iojbl.cn/Article/details/gtbqgrpjjr.html

[U104] JS：防抖
来源：http://dali.hywenlv.cn/Article/details/gtgjbrkzld.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gtdinzsghl.html

[U105] JS：节流
来源：http://dali.ivvv.top/Article/details/gtsdhsqcgh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gtswvufais.html

[U106] JS：日期格式化
来源：http://dali.jqgufenzy.top/Article/details/gtteczywux.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.birdmap.top/Article/details/gteptpccid.html

[U107] JS：数字千分位
来源：http://dali.hnqzz.top/Article/details/gtffdpuqrk.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sysykeji.top/Article/details/gtfloprlxr.html

[U108] JS：随机整数
来源：http://dali.hnxiangtu.top/Article/details/gtzktuwvas.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jiagoushi.top/Article/details/gtevfjashi.html

[U109] JS：数组分组
来源：http://dali.meibo888.top/Article/details/gtqgctzmrl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.cqqwz.cn/Article/details/gttncwwagw.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gtcfludzll.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.316326.xyz/Article/details/gtdpmkbbug.html

[U111] JS：对象转 Map
来源：http://dali.yangfankeji.com/Article/details/gtxgfmmicq.html

new Map(Object.entries(obj))
来源：http://dali.hywenlv.cn/Article/details/gtbafceyhr.html

[U112] JS：字符串补位
来源：http://dali.feifeiyinyue.top/Article/details/gtiztjqhnr.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gteylucypz.html

[U113] JS：正则替换全部
来源：http://dali.9152youxi.cn/Article/details/gtrsmdytmb.html

s.replaceAll("a", "b")
来源：http://dali.zhongyouzk.top/Article/details/gtwyptylld.html

[U114] JS：JSON 深比较
来源：http://dali.shangyingyoupin.top/Article/details/gtomhlzkwo.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.daxiang520.top/Article/details/gtonfzfuhs.html

[U115] JS：生成 UUID
来源：http://dali.yangfankeji.com/Article/details/gtaxxvmtfu.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtsfsikdtd.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtrlpdacsb.html

/** @param {string} name */ function f(name) {}
来源：http://dali.quarkkingdee.top/Article/details/gtebpogzqe.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gtugfgvptv.html

npm i -D vitest;  npx vitest
来源：http://dali.jqgfzy.top/Article/details/gtxbeqmpts.html

[U118] JS：开发服务器
来源：http://dali.jinqigfzy.top/Article/details/gtstyqodje.html

npm i -D vite;  npx vite
来源：http://dali.tanke756.top/Article/details/gtlrwczwck.html

[U119] JS：生产构建
来源：http://dali.gogol.net.cn/Article/details/gtaxrlxtdm.html

npx vite build
来源：http://dali.svipenyu.cn/Article/details/gtnupsjxsu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.gzhubu.top/Article/details/gtnnkryzwe.html

import.meta.env.VITE_API_URL
来源：http://dali.9152youxi.cn/Article/details/gttsxsjjpo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtiahcptpc.html

统计汇总
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhmgxgzv.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtdmryjgif.html

按语言统计（条）：
来源：http://dali.yueranfly.top/Article/details/gtrpirpami.html

Python ......... 252
来源：http://dali.feifeiyinyue.top/Article/details/gtwzrzvppn.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gtenrynuri.html

JavaScript ..... 252
来源：http://dali.sufxvd.cn/Article/details/gtvgdpnkuk.html

TypeScript ..... 212
来源：http://dali.dianchejie.cn/Article/details/gtfluqqibe.html

Java ........... 212
来源：http://dali.tian-w.cn/Article/details/gtgvdsalzb.html

Go ............. 212
来源：http://dali.zhoulong.xyz/Article/details/gthdvxxzkp.html

Ruby ........... 212
来源：http://dali.yueranfly.top/Article/details/gtkmbizhaw.html

C# ............. 212
来源：http://dali.feifeiyinyue.top/Article/details/gteuxyhlix.html

C .............. 30
来源：http://dali.hnqzz.top/Article/details/gtrzjiievj.html

C++ ............ 30
来源：http://dali.wangshuangyany.cn/Article/details/gtjckvfjya.html

SQL ............ 90
来源：http://dali.zhongyouzk.top/Article/details/gtygoddgbz.html

Bash ........... 80
来源：http://dali.gzhubu.top/Article/details/gtdddveaza.html

Kotlin ......... 15
来源：http://dali.jinqigfzy.top/Article/details/gtucbmovrd.html

Swift .......... 15
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgjdtelxv.html

Lua ............ 10
来源：http://dali.vqdsnc.cn/Article/details/gtgvqtbote.html

Perl ........... 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtecddubsi.html

Scala .......... 10
来源：http://dali.shangyingyoupin.top/Article/details/gtqbnkcfow.html

------------------------------------
来源：http://dali.yonumen.top/Article/details/gtdpgfxqdr.html

合计 ........... 2106 条
来源：http://dali.hongshengwenyu.top/Article/details/gtdxqupqwk.html

按章节统计：
来源：http://dali.feifeiyinyue.top/Article/details/gtexlosxqn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gtdstzuuql.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfvdxkxtm.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.gzhubu.top/Article/details/gtcnmmzvij.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.zhijiandao.cn/Article/details/gtmjxecfbd.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.xuanzx.com/Article/details/gtoeigzamu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hywenlv.cn/Article/details/gtbwwvgiel.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.wangshuangyany.cn/Article/details/gtjuqkwazs.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreipzscy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.sysykeji.top/Article/details/gtsmedxasd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gteoplofzw.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.xinyue.icu/Article/details/gtoatliuhf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.cashguo.top/Article/details/gtxzwhvqxn.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.chenjidiqi.icu/Article/details/gtpmizreez.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.feifeiyinyue.top/Article/details/gtxafcfndk.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.tianlin.xyz/Article/details/gtysnyjxvl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtexedxoho.html

Q SQL 专题                              90
来源：http://dali.ppjwa.cn/Article/details/gtdkqaevfz.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gtaljdnjvo.html

S C / C++ 专题                          60
来源：http://dali.sweek.top/Article/details/gtkcrezpid.html

T 其他语言补充                          60
来源：http://dali.redwolf501.top/Article/details/gtdhcbreqb.html

U 高频实用片段                         120
来源：http://dali.xylfe.cn/Article/details/gtwecaugmn.html

------------------------------------
来源：http://dali.havefunace.top/Article/details/gtkewpsjri.html

合计                                  2106 条
来源：http://dali.shuidangran.top/Article/details/gtxbzsnfca.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gthqchuvtl.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gtcyiwpezk.html

--------------------------------------------------------------------------------
来源：http://dali.jyoumei.cn/Article/details/gtlbpzfzin.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.jinqigufen.top/Article/details/gtspnnzdtu.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.redwolf501.top/Article/details/gtodlstvsz.html


<!-- 参考信息 -->