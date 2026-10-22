代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sxivjqnj.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gt2fluwlyug.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xhojtpgf.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ipcmfnwg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gt2sklrisih.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gt2stvayzmw.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2jqauhfco.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gt2ohfvlpjc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenjidiqi.icu/Article/details/gt2tnihzsui.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2qqhgbflt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.iojbl.cn/Article/details/gt2lbdgqyim.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2xsccipoh.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gt2efpvjhhg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gt2jxommybf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ppjwa.cn/Article/details/gt2mvljbyih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shuidangran.top/Article/details/gt2rwmtieit.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gt2ximutabn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.birdmap.top/Article/details/gt2euwzilxs.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gt2isghxrzg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinqigfzy.top/Article/details/gt2xizvefyo.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gt2dcaumtnv.html

list(dict.fromkeys(arr))
来源：http://dali.fzhhl.top/Article/details/gt2rihzkavl.html

[U06] Py：合并两个字典
来源：http://dali.sufxvd.cn/Article/details/gt2oxtvfygg.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gt2sdjbqobh.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gt2nunngczp.html

{v: k for k, v in d.items()}
来源：http://dali.zhiwuduotai.top/Article/details/gt2vpkieefq.html

[U08] Py：展平二维列表
来源：http://dali.9152youxi.cn/Article/details/gt2pougtelc.html

[y for x in nested for y in x]
来源：http://dali.redwolf501.top/Article/details/gt2hbcpejcr.html

[U09] Py：字典取最大值的键
来源：http://dali.ybcxt.top/Article/details/gt2mgpcubxg.html

max(d, key=d.get)
来源：http://dali.gotoacloud.top/Article/details/gt2pzkmpefn.html

[U10] Py：按值排序字典
来源：http://dali.chenlongwang.top/Article/details/gt2ydvunnxz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pycfn.com/Article/details/gt2fgticonh.html

[U11] Py：生成器表达式
来源：http://dali.jinqigfzy.top/Article/details/gt2gjehhtms.html

(x * 2 for x in arr)
来源：http://dali.jqgfzy.top/Article/details/gt2mdqfdwhw.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tianlin.xyz/Article/details/gt2psmbuatm.html

Counter(arr).most_common(3)
来源：http://dali.jianghu66.top/Article/details/gt2evamyhqu.html

[U13] Py：固定长度队列
来源：http://dali.zhijiandao.cn/Article/details/gt2fndoomak.html

deque(maxlen=10)
来源：http://dali.xinyue.icu/Article/details/gt2inwsgdnz.html

[U14] Py：分组收集到列表
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yeevqcuv.html

defaultdict(list)
来源：http://dali.haohaochexian.top/Article/details/gt2tboymgmk.html

[U15] Py：高精度计时
来源：http://dali.meibo888.top/Article/details/gt2ekejodlu.html

t = time.perf_counter()
来源：http://dali.jqgufenzy.top/Article/details/gt2sqaftsyx.html

[U16] Py：命令行参数解析
来源：http://dali.dianchejie.cn/Article/details/gt2pzwjlnya.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gt2ubjycfcn.html

[U17] Py：初始化日志
来源：http://dali.cashguo.top/Article/details/gt2wovhydsa.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jkduksdu.html

[U18] Py：预编译正则
来源：http://dali.yuanzhike.top/Article/details/gt2nxenjnfa.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2bhuziwmh.html

[U19] Py：正则替换带回调
来源：http://dali.bjfxy.top/Article/details/gt2ecvtgkwc.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.bjfxy.top/Article/details/gt2gmiwjcuc.html

[U20] Py：缓存函数结果
来源：http://dali.yj202588.top/Article/details/gt2dwynunqi.html

@functools.lru_cache(maxsize=None)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gvxbfywu.html

[U21] Py：自定义上下文管理器
来源：http://dali.mhx1999.top/Article/details/gt2bnibyjmg.html

@contextlib.contextmanager
来源：http://dali.gaohongyu789.top/Article/details/gt2wfadksyd.html

[U22] Py：矩阵转置
来源：http://dali.xinyue.icu/Article/details/gt2bjnjgvlu.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gt2dwqvbbek.html

[U23] Py：分块读取大文件
来源：http://dali.yanxiufei.cn/Article/details/gt2nphnmluc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hywenlv.cn/Article/details/gt2ouzjydxs.html

[U24] Py：路径操作
来源：http://dali.cashguo.top/Article/details/gt2qkopdabt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlmkkekk.html

[U25] Py：CSV 按字典读
来源：http://dali.meibo888.top/Article/details/gt2atharocs.html

csv.DictReader(f)
来源：http://dali.dianchejie.cn/Article/details/gt2uxfrrvht.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gt2lxkiesqk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhixingplan.top/Article/details/gt2zfhrzzvw.html

[U27] Py：异步 HTTP
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnoxmesv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gaohongyu789.top/Article/details/gt2mvrifaux.html

[U28] Py：类型别名
来源：http://dali.hnqzz.top/Article/details/gt2xtxjimrh.html

UserId = int
来源：http://dali.fzhhl.top/Article/details/gt2depkfkbr.html

[U29] Py：属性校验
来源：http://dali.tian-w.cn/Article/details/gt2yychlyni.html

@property 与 @x.setter 配合
来源：http://dali.fzhhl.top/Article/details/gt2nfgpzpqe.html

[U30] Py：数据类
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ekvfejyb.html

@dataclass(slots=True)
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfkcnduu.html

[U31] Py：单测
来源：http://dali.yvedp.cn/Article/details/gt2hwtbzclc.html

python -m pytest -q
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2abwexcvk.html

[U32] Py：代码格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qhzmulxq.html

ruff format . && ruff check --fix .
来源：http://dali.sysykeji.top/Article/details/gt2ageziftp.html

[U33] Py：打包发布
来源：http://dali.xylfe.cn/Article/details/gt2vzavksli.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cucudq.cn/Article/details/gt2rzharbsz.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gt2ognvnbvj.html

chardet.detect(raw)
来源：http://dali.yongpay.top/Article/details/gt2erdjszkb.html

[U35] Py：发送邮件
来源：http://dali.yangfankeji.com/Article/details/gt2vtapumie.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yj202588.top/Article/details/gt2njycnfzs.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gt2cwkvcbnr.html

schedule.every(10).minutes.do(job)
来源：http://dali.shzxlz.cn/Article/details/gt2gypqgnxf.html

[U37] Py：读写 Excel
来源：http://dali.svipenyu.cn/Article/details/gt2yjyinhbf.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shuidangran.top/Article/details/gt2nrrdylkb.html

[U38] Py：获取脚本所在目录
来源：http://dali.fengsongda.top/Article/details/gt2rhxxlqkc.html

Path(__file__).resolve().parent
来源：http://dali.zhiwuduotai.top/Article/details/gt2etiixxzo.html

[U39] Py：判断是否在交互环境
来源：http://dali.xylfe.cn/Article/details/gt2zbgjdxbt.html

sys.stdout.isatty()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2afoozqjo.html

[U40] Py：打印到标准错误
来源：http://dali.zdqjudy.top/Article/details/gt2bunzaqln.html

print("err", file=sys.stderr)
来源：http://dali.daxiang520.top/Article/details/gt2pglcnwpc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.feifeiyinyue.top/Article/details/gt2eaouugbs.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.ybcxt.top/Article/details/gt2fuklvilc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cheryme.top/Article/details/gt2oankzokv.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zdqjudy.top/Article/details/gt2kcpvrvej.html

[U43] PHP：声明命名空间
来源：http://dali.dashuyun.cn/Article/details/gt2fdjjwadw.html

namespace App\Http;
来源：http://dali.cdnleiting.top/Article/details/gt2ggtkmvmu.html

[U44] PHP：开启严格类型
来源：http://dali.ydzc1.top/Article/details/gt2lsxpqukm.html

declare(strict_types=1);
来源：http://dali.smart0.xyz/Article/details/gt2mujkhrgy.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gioguszg.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rshooxsb.html

[U46] PHP：可空类型
来源：http://dali.yonumen.top/Article/details/gt2qmyssgas.html

?string $name = null
来源：http://dali.sufxvd.cn/Article/details/gt2kgaihbyo.html

[U47] PHP：联合类型
来源：http://dali.snrcjt.cn/Article/details/gt2fyzwmexl.html

int|string $id
来源：http://dali.iojbl.cn/Article/details/gt2tniubwuh.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gt2jwyuarmy.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hysaishi.cn/Article/details/gt2memklukw.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gt2gufyudmd.html

public readonly string $name
来源：http://dali.hfpthk.cn/Article/details/gt2vljzofos.html

[U50] PHP：构造器属性提升
来源：http://dali.jlsjyb.cn/Article/details/gt2petsthow.html

public function __construct(private int $id) {}
来源：http://dali.hnqzz.top/Article/details/gt2czjfxkyu.html

[U51] PHP：数组解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eqycfclh.html

[$a, $b] = $arr;
来源：http://dali.jlsjyb.cn/Article/details/gt2lasikrtz.html

[U52] PHP：箭头函数
来源：http://dali.birdmap.top/Article/details/gt2nkhjzynj.html

$double = fn($x) => $x * 2;
来源：http://dali.zhengqikj.top/Article/details/gt2whtvtwrh.html

[U53] PHP：空合并运算符
来源：http://dali.yj202588.top/Article/details/gt2vpwplbzo.html

$v = $a ?? $b ?? "default";
来源：http://dali.tian-w.cn/Article/details/gt2tyoitoev.html

[U54] PHP：空安全调用
来源：http://dali.jiagoushi.top/Article/details/gt2kilfdlik.html

$obj?->method()
来源：http://dali.ivvv.top/Article/details/gt2oiexntfa.html

[U55] PHP：match 表达式
来源：http://dali.hywenlv.cn/Article/details/gt2dhokjtse.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.meibo888.top/Article/details/gt2tghgonva.html

[U56] PHP：命名参数
来源：http://dali.tian-w.cn/Article/details/gt2liosdaty.html

f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2rnqbzwym.html

[U57] PHP：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2sgwnbcgz.html

"值: {$a}"
来源：http://dali.dashuyun.cn/Article/details/gt2lrpoitms.html

[U58] PHP：数组三件套
来源：http://dali.cucudq.cn/Article/details/gt2adhrvmbu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gt2egmwgujm.html

[U59] PHP：自定义排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sjcgsvbi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yonumen.top/Article/details/gt2zkgklknp.html

[U60] PHP：JSON 编解码
来源：http://dali.chenjidiqi.icu/Article/details/gt2hvdwyfhx.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vbyliwdk.html

[U61] PHP：正则
来源：http://dali.hywenlv.cn/Article/details/gt2xgynoflh.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ojyegqww.html

[U62] PHP：日期对象
来源：http://dali.zhixingplan.top/Article/details/gt2uucsvohl.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jlsjyb.cn/Article/details/gt2tnhvksbw.html

[U63] PHP：文件读写
来源：http://dali.birdmap.top/Article/details/gt2wdpcmjvf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sweek.top/Article/details/gt2wngrjhfp.html

[U64] PHP：目录遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2trmaykgf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.daria6918.cn/Article/details/gt2gqnuvxel.html

[U65] PHP：会话
来源：http://dali.svipenyu.cn/Article/details/gt2yaendexx.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2yjeobzyh.html

[U66] PHP：设置 Cookie
来源：http://dali.gogol.net.cn/Article/details/gt2adtlpxal.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.gogol.net.cn/Article/details/gt2hohhkwfa.html

[U67] PHP：处理文件上传
来源：http://dali.svipenyu.cn/Article/details/gt2xjjryaiv.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hfpthk.cn/Article/details/gt2wkjxhqzq.html

[U68] PHP：PDO 连接
来源：http://dali.gaohongyu789.top/Article/details/gt2ukxzpgqt.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gt2rxafblrc.html

[U69] PHP：PDO 预处理
来源：http://dali.chenzaomai.com/Article/details/gt2fqvstvgy.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gt2ifcpmkpb.html

[U70] PHP：PDO 事务
来源：http://dali.0kj1m.cn/Article/details/gt2omnllfhi.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.sysykeji.top/Article/details/gt2odufimmd.html

[U71] PHP：抛出异常
来源：http://dali.0kj1m.cn/Article/details/gt2hjofonix.html

throw new RuntimeException("失败", 500);
来源：http://dali.ehwqpu.com/Article/details/gt2fqapdkqk.html

[U72] PHP：写错误日志
来源：http://dali.snrcjt.cn/Article/details/gt2hmbdbowe.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hywenlv.cn/Article/details/gt2oflsliaw.html

[U73] PHP：读取 ini 配置
来源：http://dali.andypj.xyz/Article/details/gt2coaynyst.html

parse_ini_file("config.ini", true)
来源：http://dali.sweek.top/Article/details/gt2wytnklje.html

[U74] PHP：读取环境变量
来源：http://dali.tian-w.cn/Article/details/gt2pxjkvjkm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yongpay.top/Article/details/gt2ecwtkjva.html

[U75] PHP：依赖注入
来源：http://dali.ybcxt.top/Article/details/gt2aepfapkv.html

composer require psr/container
来源：http://dali.xziqi.cn/Article/details/gt2rmptuioy.html

[U76] PHP：简单路由
来源：http://dali.fzhhl.top/Article/details/gt2fdokplwi.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj20258888.top/Article/details/gt2znsyzecz.html

[U77] PHP：模板渲染
来源：http://dali.wangdashe.top/Article/details/gt2uciibpbf.html

composer require twig/twig
来源：http://dali.jyoumei.cn/Article/details/gt2aheooqup.html

[U78] PHP：单元测试
来源：http://dali.yj20258.top/Article/details/gt2umbacjgx.html

composer require --dev phpunit/phpunit
来源：http://dali.zhongyouzk.top/Article/details/gt2zecgqdsx.html

[U79] PHP：静态分析
来源：http://dali.nanxuanxn.top/Article/details/gt2kauqlewe.html

composer require --dev phpstan/phpstan
来源：http://dali.zhengqikj.top/Article/details/gt2vjdxvrnn.html

[U80] PHP：代码规范修复
来源：http://dali.feifeiyinyue.top/Article/details/gt2vznqqrmn.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gt2lykstkrq.html

[U81] JS：初始化项目
来源：http://dali.jyoumei.cn/Article/details/gt2cdgbhbtu.html

npm init -y;  npm i express
来源：http://dali.cashguo.top/Article/details/gt2azfdqnqz.html

[U82] JS：package.json 脚本
来源：http://dali.guannengcc.top/Article/details/gt2ivizrjpp.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.shzxlz.cn/Article/details/gt2caveziuq.html

[U83] JS：ES Module 导入导出
来源：http://dali.aizwys.cn/Article/details/gt2uthtiziv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gt2lcqptvct.html

[U84] JS：CommonJS 写法
来源：http://dali.yanxiufei.cn/Article/details/gt2mhuorbgw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.kuanghao11.cn/Article/details/gt2dueiwriu.html

[U85] JS：可选链
来源：http://dali.chenlongwang.top/Article/details/gt2gpczdspf.html

a?.b?.c
来源：http://dali.jyoumei.cn/Article/details/gt2gmhlwjjr.html

[U86] JS：空值合并
来源：http://dali.aibaodan.cn/Article/details/gt2ustrwzre.html

a ?? b
来源：http://dali.ybcxt.top/Article/details/gt2hpunpiow.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gt2fdwhnvlc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpkmvxrb.html

[U88] JS：对象展开合并
来源：http://dali.hfpthk.cn/Article/details/gt2geyrvvco.html

{ ...a, ...b }
来源：http://dali.cashguo.top/Article/details/gt2tbmhoizi.html

[U89] JS：数组去重
来源：http://dali.ppjwa.cn/Article/details/gt2zgdsjzis.html

[...new Set(arr)]
来源：http://dali.zhijiandao.cn/Article/details/gt2nhzlqjrs.html

[U90] JS：数字数组排序
来源：http://dali.zhengqikj.top/Article/details/gt2fnanjwip.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhiwuduotai.top/Article/details/gt2jwhkgqup.html

[U91] JS：对象键值遍历
来源：http://dali.ybcxt.top/Article/details/gt2jjltwkcq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.jyoumei.cn/Article/details/gt2hixpymtm.html

[U92] JS：深拷贝
来源：http://dali.shuidangran.top/Article/details/gt2oyldrbsd.html

structuredClone(obj)
来源：http://dali.0kj1m.cn/Article/details/gt2evlxynfd.html

[U93] JS：模板字符串
来源：http://dali.chenzaomai.com/Article/details/gt2jhwjxgsu.html

`共 ${n} 条`
来源：http://dali.jianghu66.top/Article/details/gt2hhuozacs.html

[U94] JS：箭头函数
来源：http://dali.zycfv.cn/Article/details/gt2nrjvzvty.html

const double = x => x * 2;
来源：http://dali.iojbl.cn/Article/details/gt2gnadcjat.html

[U95] JS：Promise 包装
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2igaxdgjy.html

new Promise((resolve, reject) => {})
来源：http://dali.yuxming.cn/Article/details/gt2jiypemwr.html

[U96] JS：async/await 与异常
来源：http://dali.zhoulong.xyz/Article/details/gt2xgfpninl.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ydzc1.top/Article/details/gt2ywcprpwb.html

[U97] JS：并发请求
来源：http://dali.jiagoushi.top/Article/details/gt2aekdtuid.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gt2wbnlpfcr.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2qdxayerm.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.dianchejie.cn/Article/details/gt2ootscpfe.html

[U99] JS：事件监听
来源：http://dali.zhongyouzk.top/Article/details/gt2dlyjdbae.html

el.addEventListener("click", e => {})
来源：http://dali.hywenlv.cn/Article/details/gt2avxlwwou.html

[U100] JS：DOM 查询
来源：http://dali.tian-w.cn/Article/details/gt2zytyofhe.html

document.querySelector(".item")
来源：http://dali.yonumen.top/Article/details/gt2vergnpix.html

[U101] JS：classList 操作
来源：http://dali.chenzaomai.com/Article/details/gt2lepkaszs.html

el.classList.toggle("active")
来源：http://dali.c1oappe.top/Article/details/gt2nehhofip.html

[U102] JS：本地存储
来源：http://dali.ppjwa.cn/Article/details/gt2tekmcqpm.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ntchwazn.html

[U103] JS：定时器
来源：http://dali.yvedp.cn/Article/details/gt2trqujrgw.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.haohaochexian.top/Article/details/gt2rtqitara.html

[U104] JS：防抖
来源：http://dali.hysaishi.cn/Article/details/gt2vpnklojn.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.tanke756.top/Article/details/gt2vdesqmob.html

[U105] JS：节流
来源：http://dali.zhijiandao.cn/Article/details/gt2cdcovzfq.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.yj20258888.top/Article/details/gt2clhqyjqr.html

[U106] JS：日期格式化
来源：http://dali.hnqzz.top/Article/details/gt2tyoocjcj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.feifeiyinyue.top/Article/details/gt2qdgzdxno.html

[U107] JS：数字千分位
来源：http://dali.cashguo.top/Article/details/gt2dhvauwrs.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gt2idxnzgtp.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwibpjni.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.nanxinkj.top/Article/details/gt2qgffvjeb.html

[U109] JS：数组分组
来源：http://dali.yvedp.cn/Article/details/gt2vwrkvyvt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gt2grtabnxb.html

[U110] JS：数组分块
来源：http://dali.yj20258.top/Article/details/gt2uxoahrog.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hongshengwenyu.top/Article/details/gt2xfinwsoh.html

[U111] JS：对象转 Map
来源：http://dali.yvedp.cn/Article/details/gt2rqlysbur.html

new Map(Object.entries(obj))
来源：http://dali.dianchejie.cn/Article/details/gt2qxosbqes.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gt2ieekqbut.html

"7".padStart(3, "0")
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpuekfgo.html

[U113] JS：正则替换全部
来源：http://dali.hysaishi.cn/Article/details/gt2mlsugfng.html

s.replaceAll("a", "b")
来源：http://dali.iojbl.cn/Article/details/gt2rmyghfgc.html

[U114] JS：JSON 深比较
来源：http://dali.shuidangran.top/Article/details/gt2vvububau.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yangfankeji.com/Article/details/gt2lgzkguls.html

[U115] JS：生成 UUID
来源：http://dali.dianchejie.cn/Article/details/gt2lpnzpqoq.html

crypto.randomUUID()
来源：http://dali.jyoumei.cn/Article/details/gt2nesmzblw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xejzgrqi.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gt2obaqsxse.html

[U117] JS：单元测试
来源：http://dali.chenzaomai.com/Article/details/gt2dhvbzlek.html

npm i -D vitest;  npx vitest
来源：http://dali.pycfn.com/Article/details/gt2liqketot.html

[U118] JS：开发服务器
来源：http://dali.hammf.cn/Article/details/gt2uqhuwhql.html

npm i -D vite;  npx vite
来源：http://dali.hammf.cn/Article/details/gt2pdsiqmdy.html

[U119] JS：生产构建
来源：http://dali.c1oappe.top/Article/details/gt2tsltmtmh.html

npx vite build
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hrkfgrgi.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pvtdwthg.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gt2gwdbdnne.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2hugibops.html

统计汇总
来源：http://dali.redwolf501.top/Article/details/gt2rptcmzup.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2qixcvdmy.html

按语言统计（条）：
来源：http://dali.sysykeji.top/Article/details/gt2bbquagwc.html

Python ......... 252
来源：http://dali.ivvv.top/Article/details/gt2jhjbmjsi.html

PHP ............ 252
来源：http://dali.hnqzz.top/Article/details/gt2uupbjhuh.html

JavaScript ..... 252
来源：http://dali.shangyingyoupin.top/Article/details/gt2fjnvyrfj.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gt2kgkngrok.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gt2kxntrjzn.html

Go ............. 212
来源：http://dali.9152youxi.cn/Article/details/gt2oajorbau.html

Ruby ........... 212
来源：http://dali.kuanghao11.cn/Article/details/gt2rocqhoci.html

C# ............. 212
来源：http://dali.snrcjt.cn/Article/details/gt2aapywfau.html

C .............. 30
来源：http://dali.zycfv.cn/Article/details/gt2jccodivh.html

C++ ............ 30
来源：http://dali.hammf.cn/Article/details/gt2umqzrdbe.html

SQL ............ 90
来源：http://dali.feifeiyinyue.top/Article/details/gt2qjcitmed.html

Bash ........... 80
来源：http://dali.aizwys.cn/Article/details/gt2gqcvydoh.html

Kotlin ......... 15
来源：http://dali.yongpay.top/Article/details/gt2oeytcrjd.html

Swift .......... 15
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vqfcnlix.html

Lua ............ 10
来源：http://dali.yj20258888.top/Article/details/gt2ehvevaxe.html

Perl ........... 10
来源：http://dali.zycfv.cn/Article/details/gt2uqhbnvnx.html

Scala .......... 10
来源：http://dali.316326.xyz/Article/details/gt2bfojsauz.html

------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2ucagnvab.html

合计 ........... 2106 条
来源：http://dali.yangfankeji.com/Article/details/gt2vgcfyccn.html

按章节统计：
来源：http://dali.zdqjudy.top/Article/details/gt2auzhngxb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.hammf.cn/Article/details/gt2joiudkok.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gt2iotprmcw.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gt2xwpjixhb.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shangyingyoupin.top/Article/details/gt2brlapbdv.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zguxfuac.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gorbuxyw.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2olcyddns.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.aibaodan.cn/Article/details/gt2axbosjqn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gt2npnoravs.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgfzy.top/Article/details/gt2oipynqpg.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.shangyingyoupin.top/Article/details/gt2gggkltgy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.aizwys.cn/Article/details/gt2zfijwxnb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhongyouzk.top/Article/details/gt2toxligrh.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhongyouzk.top/Article/details/gt2kluxerph.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iguxzcmd.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.9152youxi.cn/Article/details/gt2emtxiqco.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gt2mzzftlol.html

R Bash 专题                             80
来源：http://dali.cqqwz.cn/Article/details/gt2dvrukpzw.html

S C / C++ 专题                          60
来源：http://dali.yuxming.cn/Article/details/gt2burujltm.html

T 其他语言补充                          60
来源：http://dali.jlsjyb.cn/Article/details/gt2ervdagdn.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gt2vlfgpnch.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2ygkgipbm.html

合计                                  2106 条
来源：http://dali.zhijiandao.cn/Article/details/gt2bwyqtcmd.html

--------------------------------------------------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2etznpbgb.html


<!-- 参考信息 -->