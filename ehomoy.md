代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtpzoszzab.html

[T57] Scala：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtdluxcrpb.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnsqzkoth.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gttjdhfgrt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.0kj1m.cn/Article/details/gtixmjeorn.html

[T59] Scala：循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbafaavh.html

for (i <- 1 to 10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdnhvvgb.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtsnozuggo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258888.top/Article/details/gtnonytigr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtngysxqeo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtichoglfk.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtxdaetikq.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtwpbuhtqa.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ydzc1.top/Article/details/gtzothylkp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtyxlbvgfk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhixingplan.top/Article/details/gtuudanywm.html

[U03] Py：加载 .env 配置
来源：http://dali.ehwqpu.com/Article/details/gtutlahpmj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.316326.xyz/Article/details/gtfaervyrn.html

[U04] Py：变量调试打印
来源：http://dali.jinyuanbaomall.cn/Article/details/gttutszrbl.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtmajawvqv.html

[U05] Py：列表去重且保序
来源：http://dali.nanxuanxn.top/Article/details/gtibkofveo.html

list(dict.fromkeys(arr))
来源：http://dali.cheryme.top/Article/details/gtwaxwicht.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gtxzllncmd.html

{**a, **b}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmumkwnqt.html

[U07] Py：反转字典键值
来源：http://dali.9152youxi.cn/Article/details/gtyhkjqurf.html

{v: k for k, v in d.items()}
来源：http://dali.xziqi.cn/Article/details/gtbxklzcie.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtpdoivail.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gthnstbzlp.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gtxiwunbnh.html

max(d, key=d.get)
来源：http://dali.gaohongyu789.top/Article/details/gtwgjbzqpj.html

[U10] Py：按值排序字典
来源：http://dali.jiagoushi.top/Article/details/gtfxvnnssh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtqnuqxtny.html

[U11] Py：生成器表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqkpkykfn.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtgfwcsgpr.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hnqzz.top/Article/details/gtaqfgpkvn.html

Counter(arr).most_common(3)
来源：http://dali.c1oappe.top/Article/details/gtofihmoxx.html

[U13] Py：固定长度队列
来源：http://dali.hfpthk.cn/Article/details/gthugxfocb.html

deque(maxlen=10)
来源：http://dali.nanxuanxn.top/Article/details/gtwxmwgwoy.html

[U14] Py：分组收集到列表
来源：http://dali.gzhubu.top/Article/details/gtijbedlqs.html

defaultdict(list)
来源：http://dali.shuidangran.top/Article/details/gtnoinwhxh.html

[U15] Py：高精度计时
来源：http://dali.mhx1999.top/Article/details/gtiuivsbjl.html

t = time.perf_counter()
来源：http://dali.gotoacloud.top/Article/details/gtlhqtplzp.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtwvtivqpd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ehwqpu.com/Article/details/gtejfmjmdi.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtabwytvzr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zycfv.cn/Article/details/gtbnwhvyge.html

[U18] Py：预编译正则
来源：http://dali.vqdsnc.cn/Article/details/gtmchlkqtb.html

pat = re.compile(r"\d+")
来源：http://dali.zhixingplan.top/Article/details/gtdiuiuvvt.html

[U19] Py：正则替换带回调
来源：http://dali.hysaishi.cn/Article/details/gtlhhjzliu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yonumen.top/Article/details/gtpuegjcgk.html

[U20] Py：缓存函数结果
来源：http://dali.cqqwz.cn/Article/details/gtjyrcapqj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.hfpthk.cn/Article/details/gtksspoucc.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gteuxlctgq.html

@contextlib.contextmanager
来源：http://dali.dashuyun.cn/Article/details/gtxlsjlabn.html

[U22] Py：矩阵转置
来源：http://dali.andypj.xyz/Article/details/gtpelfrsmi.html

list(zip(*m))
来源：http://dali.xziqi.cn/Article/details/gtdwbxccwg.html

[U23] Py：分块读取大文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzrsraloj.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtpecwfxak.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gtttcahzkb.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.yj20258.top/Article/details/gttzeftdxf.html

[U25] Py：CSV 按字典读
来源：http://dali.jlsjyb.cn/Article/details/gtidkvcnsw.html

csv.DictReader(f)
来源：http://dali.havefunace.top/Article/details/gttpslmlum.html

[U26] Py：并发下载
来源：http://dali.bjfxy.top/Article/details/gtuzenefik.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gtoeqvazjd.html

[U27] Py：异步 HTTP
来源：http://dali.ywan-chungtsiang.top/Article/details/gtinyydkwh.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.mhx1999.top/Article/details/gtslciltmz.html

[U28] Py：类型别名
来源：http://dali.mhx1999.top/Article/details/gtumfmiutf.html

UserId = int
来源：http://dali.yangfankeji.com/Article/details/gtoxpzhouq.html

[U29] Py：属性校验
来源：http://dali.cheryme.top/Article/details/gtjwkysegh.html

@property 与 @x.setter 配合
来源：http://dali.ivvv.top/Article/details/gtzuzyrrop.html

[U30] Py：数据类
来源：http://dali.tanke756.top/Article/details/gtkjinmxei.html

@dataclass(slots=True)
来源：http://dali.andypj.xyz/Article/details/gtgqihqids.html

[U31] Py：单测
来源：http://dali.ybcxt.top/Article/details/gtmbgdullm.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gttptrujzy.html

[U32] Py：代码格式化
来源：http://dali.xuanzx.com/Article/details/gtgziwdngk.html

ruff format . && ruff check --fix .
来源：http://dali.daxiang520.top/Article/details/gtnatzxooo.html

[U33] Py：打包发布
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwchnrrqf.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ppjwa.cn/Article/details/gtigsadrdb.html

[U34] Py：判断编码
来源：http://dali.0kj1m.cn/Article/details/gtnjdrebpw.html

chardet.detect(raw)
来源：http://dali.chenlongwang.top/Article/details/gtkuhtpaom.html

[U35] Py：发送邮件
来源：http://dali.snrcjt.cn/Article/details/gtuopugptt.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yonumen.top/Article/details/gtgotncjpc.html

[U36] Py：定时任务
来源：http://dali.jqgfzy.top/Article/details/gtuzbjuvja.html

schedule.every(10).minutes.do(job)
来源：http://dali.quarkkingdee.top/Article/details/gthooanxtg.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gtsjfnjsvg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gthdcanpdb.html

[U38] Py：获取脚本所在目录
来源：http://dali.tanke756.top/Article/details/gtsotjocxa.html

Path(__file__).resolve().parent
来源：http://dali.tanke756.top/Article/details/gtxvfziecm.html

[U39] Py：判断是否在交互环境
来源：http://dali.jinghuilouyu.cn/Article/details/gtaeipeqcc.html

sys.stdout.isatty()
来源：http://dali.guannengcc.top/Article/details/gtavmwtdbh.html

[U40] Py：打印到标准错误
来源：http://dali.nanxinkj.top/Article/details/gtdzgyuyeh.html

print("err", file=sys.stderr)
来源：http://dali.sweek.top/Article/details/gtophbqvhy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yvedp.cn/Article/details/gtlefiijpq.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.hammf.cn/Article/details/gtnfxfqokh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.yvedp.cn/Article/details/gtvqszifng.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.chenzaomai.com/Article/details/gtdeicjcqo.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtmyihkftg.html

namespace App\Http;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnnuucut.html

[U44] PHP：开启严格类型
来源：http://dali.daxiang520.top/Article/details/gtwwjjfnnl.html

declare(strict_types=1);
来源：http://dali.hongshengwenyu.top/Article/details/gtafivfafj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zdqjudy.top/Article/details/gtoldrpuja.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtdpzamsjj.html

[U46] PHP：可空类型
来源：http://dali.fengsongda.top/Article/details/gttsraxlns.html

?string $name = null
来源：http://dali.cashguo.top/Article/details/gtbcfbipzy.html

[U47] PHP：联合类型
来源：http://dali.yanxiufei.cn/Article/details/gtvrykxqip.html

int|string $id
来源：http://dali.yueranfly.top/Article/details/gtkhnahbhs.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtvijgytue.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpnipgbwt.html

[U49] PHP：只读属性
来源：http://dali.gogol.net.cn/Article/details/gtqmkmctxp.html

public readonly string $name
来源：http://dali.jinyuanbaomall.cn/Article/details/gtratnrkvq.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gtzwpcrfrb.html

public function __construct(private int $id) {}
来源：http://dali.cdnleiting.top/Article/details/gtyhapwaza.html

[U51] PHP：数组解构
来源：http://dali.yuxming.cn/Article/details/gtosafmsvw.html

[$a, $b] = $arr;
来源：http://dali.vqdsnc.cn/Article/details/gtvyjzykdj.html

[U52] PHP：箭头函数
来源：http://dali.mhx1999.top/Article/details/gtbfkkyzbp.html

$double = fn($x) => $x * 2;
来源：http://dali.gzhubu.top/Article/details/gtktvxbmpw.html

[U53] PHP：空合并运算符
来源：http://dali.xziqi.cn/Article/details/gtqaplubjn.html

$v = $a ?? $b ?? "default";
来源：http://dali.pycfn.com/Article/details/gtetvnrjfa.html

[U54] PHP：空安全调用
来源：http://dali.mhx1999.top/Article/details/gtneumrndr.html

$obj?->method()
来源：http://dali.shzxlz.cn/Article/details/gthorjoidn.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtdnghnfbl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.chenjidiqi.icu/Article/details/gtggbksfub.html

[U56] PHP：命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtzzffkccv.html

f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtcmuqcqlb.html

[U57] PHP：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtvsjgslfp.html

"值: {$a}"
来源：http://dali.wangshuangyany.cn/Article/details/gtttzevlvj.html

[U58] PHP：数组三件套
来源：http://dali.cheryme.top/Article/details/gtihxjanlz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.sxryk.cn/Article/details/gteeafocnx.html

[U59] PHP：自定义排序
来源：http://dali.316326.xyz/Article/details/gtnzrtvndg.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cqqwz.cn/Article/details/gtwfkgybjj.html

[U60] PHP：JSON 编解码
来源：http://dali.zhoulong.xyz/Article/details/gtjltcozqg.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.havefunace.top/Article/details/gtuhvmnutl.html

[U61] PHP：正则
来源：http://dali.yuanzhike.top/Article/details/gtresheaqx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.fzhhl.top/Article/details/gtdvnnzmog.html

[U62] PHP：日期对象
来源：http://dali.sysykeji.top/Article/details/gtqvjlojmc.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.xziqi.cn/Article/details/gtiiqnpigl.html

[U63] PHP：文件读写
来源：http://dali.redwolf501.top/Article/details/gtnhfuqaqt.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cucudq.cn/Article/details/gtqslmxqib.html

[U64] PHP：目录遍历
来源：http://dali.pycfn.com/Article/details/gtikxufmvf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.yanxiufei.cn/Article/details/gtzidvnkgx.html

[U65] PHP：会话
来源：http://dali.iojbl.cn/Article/details/gtpejmpfuj.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtcroqrusx.html

[U66] PHP：设置 Cookie
来源：http://dali.gotoacloud.top/Article/details/gtxrbbqpoz.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtvmhmpqfs.html

[U67] PHP：处理文件上传
来源：http://dali.gotoacloud.top/Article/details/gtgyclqvtv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.feifeiyinyue.top/Article/details/gtjlvdsegx.html

[U68] PHP：PDO 连接
来源：http://dali.aizwys.cn/Article/details/gtyvterois.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.pycfn.com/Article/details/gtytrgwyau.html

[U69] PHP：PDO 预处理
来源：http://dali.zhijiandao.cn/Article/details/gtcpvxitpj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.0kj1m.cn/Article/details/gtwunjgsqd.html

[U70] PHP：PDO 事务
来源：http://dali.yonumen.top/Article/details/gtkknwobpt.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.hongshengwenyu.top/Article/details/gtmysehhze.html

[U71] PHP：抛出异常
来源：http://dali.316326.xyz/Article/details/gtyoazaktt.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gtelqqtdnr.html

[U72] PHP：写错误日志
来源：http://dali.aizwys.cn/Article/details/gthtlktaev.html

error_log("失败: " . $e->getMessage());
来源：http://dali.zhoulong.xyz/Article/details/gteqtdfnpb.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gttlayrpmu.html

parse_ini_file("config.ini", true)
来源：http://dali.hywenlv.cn/Article/details/gtryjrxzza.html

[U74] PHP：读取环境变量
来源：http://dali.yvedp.cn/Article/details/gtpmchgcsl.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gtshhxnshw.html

[U75] PHP：依赖注入
来源：http://dali.316326.xyz/Article/details/gtqfergkuu.html

composer require psr/container
来源：http://dali.zycfv.cn/Article/details/gtvwffctgo.html

[U76] PHP：简单路由
来源：http://dali.meibo888.top/Article/details/gtiwredvys.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtrqiibfur.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gttihgmnzq.html

composer require twig/twig
来源：http://dali.zycfv.cn/Article/details/gtykpvsjlk.html

[U78] PHP：单元测试
来源：http://dali.pycfn.com/Article/details/gtfxswcmby.html

composer require --dev phpunit/phpunit
来源：http://dali.shangyingyoupin.top/Article/details/gtpxyqxfzl.html

[U79] PHP：静态分析
来源：http://dali.jinghuilouyu.cn/Article/details/gtzghakkys.html

composer require --dev phpstan/phpstan
来源：http://dali.nanxinkj.top/Article/details/gtmoxywvlh.html

[U80] PHP：代码规范修复
来源：http://dali.quarkkingdee.top/Article/details/gtbapuuwzn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gtcsruwuva.html

[U81] JS：初始化项目
来源：http://dali.c1oappe.top/Article/details/gtrourliaw.html

npm init -y;  npm i express
来源：http://dali.yonumen.top/Article/details/gtzrnrztad.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gtknsiysjv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shuidangran.top/Article/details/gtnzrpbejn.html

[U83] JS：ES Module 导入导出
来源：http://dali.smart0.xyz/Article/details/gtazhhkmil.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtdrbfbzhf.html

[U84] JS：CommonJS 写法
来源：http://dali.jinqigufen.top/Article/details/gtxtiicean.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.sweek.top/Article/details/gtvqmhlsec.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gtkkdtdzhq.html

a?.b?.c
来源：http://dali.hywenlv.cn/Article/details/gtscplpcnh.html

[U86] JS：空值合并
来源：http://dali.yanxiufei.cn/Article/details/gtawohphha.html

a ?? b
来源：http://dali.yongpay.top/Article/details/gtwoluszpr.html

[U87] JS：解构默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtrvlbrcnd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangshuangyany.cn/Article/details/gtojmhhouk.html

[U88] JS：对象展开合并
来源：http://dali.hnxiangtu.top/Article/details/gtgkpoeauq.html

{ ...a, ...b }
来源：http://dali.zhixingplan.top/Article/details/gtybiwmidx.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gtsbnqakrb.html

[...new Set(arr)]
来源：http://dali.jqgfzy.top/Article/details/gtmrwhdccz.html

[U90] JS：数字数组排序
来源：http://dali.vqdsnc.cn/Article/details/gtmojpijhb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.havefunace.top/Article/details/gtemgvsykf.html

[U91] JS：对象键值遍历
来源：http://dali.xziqi.cn/Article/details/gtvbdmlpwh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.feifeiyinyue.top/Article/details/gtqstqrgpy.html

[U92] JS：深拷贝
来源：http://dali.tian-w.cn/Article/details/gtqnnfgiiu.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gtoflvvzkm.html

[U93] JS：模板字符串
来源：http://dali.nanxuanxn.top/Article/details/gtvkawedio.html

`共 ${n} 条`
来源：http://dali.tanke756.top/Article/details/gtcgskyqkt.html

[U94] JS：箭头函数
来源：http://dali.hysaishi.cn/Article/details/gtuwfwwzxr.html

const double = x => x * 2;
来源：http://dali.yongpay.top/Article/details/gtdplhguke.html

[U95] JS：Promise 包装
来源：http://dali.hnxiangtu.top/Article/details/gtsbxlwaza.html

new Promise((resolve, reject) => {})
来源：http://dali.0kj1m.cn/Article/details/gtmqflwlfc.html

[U96] JS：async/await 与异常
来源：http://dali.andypj.xyz/Article/details/gtlcjynpsa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnksjuaq.html

[U97] JS：并发请求
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjcsmvpdw.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shuidangran.top/Article/details/gtepoappkf.html

[U98] JS：fetch 带 JSON
来源：http://dali.chenjidiqi.icu/Article/details/gtfebuznbc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuanzx.com/Article/details/gtxnoykzzt.html

[U99] JS：事件监听
来源：http://dali.redwolf501.top/Article/details/gthprttqqq.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtvtqkeddt.html

[U100] JS：DOM 查询
来源：http://dali.sweek.top/Article/details/gtvoucgafg.html

document.querySelector(".item")
来源：http://dali.xinyue.icu/Article/details/gtszjmrgtd.html

[U101] JS：classList 操作
来源：http://dali.yj20258888.top/Article/details/gtzxopsvxn.html

el.classList.toggle("active")
来源：http://dali.gogol.net.cn/Article/details/gtpokxoiwl.html

[U102] JS：本地存储
来源：http://dali.yj20258.top/Article/details/gtohsymzku.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.nanxinkj.top/Article/details/gtwgdtrgom.html

[U103] JS：定时器
来源：http://dali.nanxuanxn.top/Article/details/gtayipcztg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xinyue.icu/Article/details/gttmuuhncf.html

[U104] JS：防抖
来源：http://dali.tanke756.top/Article/details/gtomszbddx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gaohongyu789.top/Article/details/gtbqqwubhq.html

[U105] JS：节流
来源：http://dali.yuanzhike.top/Article/details/gtfiemqima.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cashguo.top/Article/details/gtlsosansw.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtrjzslxdo.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yanxiufei.cn/Article/details/gtrbrbfyoc.html

[U107] JS：数字千分位
来源：http://dali.ivvv.top/Article/details/gtjboybbwp.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.dianchejie.cn/Article/details/gtvwsdtvdd.html

[U108] JS：随机整数
来源：http://dali.shangyingyoupin.top/Article/details/gtxcjudxph.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.haohaochexian.top/Article/details/gtexuxetvd.html

[U109] JS：数组分组
来源：http://dali.zhijiandao.cn/Article/details/gtyvpgdrzw.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hammf.cn/Article/details/gtrrifyhcm.html

[U110] JS：数组分块
来源：http://dali.tian-w.cn/Article/details/gtmibdswhd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.quarkkingdee.top/Article/details/gtmjqontdp.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtkzznjyvr.html

new Map(Object.entries(obj))
来源：http://dali.gzhubu.top/Article/details/gtwqjguefh.html

[U112] JS：字符串补位
来源：http://dali.jqgfzy.top/Article/details/gtbgzaqkeg.html

"7".padStart(3, "0")
来源：http://dali.yonumen.top/Article/details/gtyzfdbadg.html

[U113] JS：正则替换全部
来源：http://dali.gotoacloud.top/Article/details/gtjmkwforl.html

s.replaceAll("a", "b")
来源：http://dali.shzxlz.cn/Article/details/gtjkzadrix.html

[U114] JS：JSON 深比较
来源：http://dali.yj20258.top/Article/details/gtpfnzkwcv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.svipenyu.cn/Article/details/gtbwjqqmpw.html

[U115] JS：生成 UUID
来源：http://dali.hnxiangtu.top/Article/details/gttjvulpjh.html

crypto.randomUUID()
来源：http://dali.yonumen.top/Article/details/gtuffxmmvk.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydaetpad.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xziqi.cn/Article/details/gttisswdxi.html

[U117] JS：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gtnpthyztq.html

npm i -D vitest;  npx vitest
来源：http://dali.jianghu66.top/Article/details/gtgrsyarxv.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gteunuejzi.html

npm i -D vite;  npx vite
来源：http://dali.dianchejie.cn/Article/details/gtnyslnxiy.html

[U119] JS：生产构建
来源：http://dali.sufxvd.cn/Article/details/gtyrtjcpix.html

npx vite build
来源：http://dali.ydzc1.top/Article/details/gtwkwfummg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.birdmap.top/Article/details/gtrwukorxh.html

import.meta.env.VITE_API_URL
来源：http://dali.sufxvd.cn/Article/details/gtajfhelhw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gthpfekzda.html

统计汇总
来源：http://dali.bjfxy.top/Article/details/gtmctgynin.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtthpigdjb.html

按语言统计（条）：
来源：http://dali.tian-w.cn/Article/details/gtbdqwlbes.html

Python ......... 252
来源：http://dali.cheryme.top/Article/details/gttleqvjmy.html

PHP ............ 252
来源：http://dali.smart0.xyz/Article/details/gtdkatbonx.html

JavaScript ..... 252
来源：http://dali.cqqwz.cn/Article/details/gtsgtzpiot.html

TypeScript ..... 212
来源：http://dali.hnxiangtu.top/Article/details/gtmuiocspp.html

Java ........... 212
来源：http://dali.pycfn.com/Article/details/gtxsaiewwb.html

Go ............. 212
来源：http://dali.birdmap.top/Article/details/gthqopdbsm.html

Ruby ........... 212
来源：http://dali.meibo888.top/Article/details/gtkgbclemi.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gtrrngfabe.html

C .............. 30
来源：http://dali.sufxvd.cn/Article/details/gtkxnfnlni.html

C++ ............ 30
来源：http://dali.shanyushiyangkeji.top/Article/details/gtskpexalx.html

SQL ............ 90
来源：http://dali.jiagoushi.top/Article/details/gttupwaurk.html

Bash ........... 80
来源：http://dali.tian-w.cn/Article/details/gtozvkskul.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gtjlpqnebj.html

Swift .......... 15
来源：http://dali.shangyingyoupin.top/Article/details/gtgnjenrvf.html

Lua ............ 10
来源：http://dali.shangyingyoupin.top/Article/details/gtapirotns.html

Perl ........... 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtvowmywli.html

Scala .......... 10
来源：http://dali.nanxuanxn.top/Article/details/gtbijwmssf.html

------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gtuhavyhgw.html

合计 ........... 2106 条
来源：http://dali.jqgufenzy.top/Article/details/gtdfbmpadm.html

按章节统计：
来源：http://dali.sufxvd.cn/Article/details/gtlkxvunjw.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.gzhubu.top/Article/details/gtpjdooqbi.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ehwqpu.com/Article/details/gtwouyxnqa.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gtqhbtnxtw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.yangfankeji.com/Article/details/gtupqqidct.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.svipenyu.cn/Article/details/gtfmxcedth.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.pycfn.com/Article/details/gtfnonqroh.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.fengsongda.top/Article/details/gtagkjxevi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtfzkvtexw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gthhbiekim.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.chenlongwang.top/Article/details/gtsewfojec.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gtoplkofbg.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtrnhlclyk.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtenyswzti.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangtech.top/Article/details/gtemgamuor.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.chenjidiqi.icu/Article/details/gtizehelwg.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.meibo888.top/Article/details/gtkxhvudqi.html

Q SQL 专题                              90
来源：http://dali.zhongyouzk.top/Article/details/gtrednswxb.html

R Bash 专题                             80
来源：http://dali.birdmap.top/Article/details/gtysuqdqwn.html

S C / C++ 专题                          60
来源：http://dali.chenzaomai.com/Article/details/gtmdyjzxcp.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gtuaycpwxt.html

U 高频实用片段                         120
来源：http://dali.ywan-chungtsiang.top/Article/details/gtauepfuum.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtbwodhcng.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtozyfnfzi.html

--------------------------------------------------------------------------------
来源：http://dali.nanxinkj.top/Article/details/gtfoxcezvd.html


<!-- 参考信息 -->