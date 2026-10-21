代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hysaishi.cn/Article/details/gtsnekbkdx.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtaxxvpneg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtywzaqxwh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gteygvauru.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gtzvylphzh.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gtapfxsmkx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yueranfly.top/Article/details/gtealfdcfj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.0kj1m.cn/Article/details/gtkxefuryi.html

[U03] Py：加载 .env 配置
来源：http://dali.0kj1m.cn/Article/details/gtejibmqif.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangshuangyany.cn/Article/details/gtrgsykpam.html

[U04] Py：变量调试打印
来源：http://dali.tian-w.cn/Article/details/gthluhmwws.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xuanzx.com/Article/details/gtmisfowyn.html

[U05] Py：列表去重且保序
来源：http://dali.fzhhl.top/Article/details/gtptkntrbv.html

list(dict.fromkeys(arr))
来源：http://dali.andypj.xyz/Article/details/gtzlxpstde.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtzubwemme.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtovpvpeqk.html

[U07] Py：反转字典键值
来源：http://dali.jqgfzy.top/Article/details/gtgntmkrig.html

{v: k for k, v in d.items()}
来源：http://dali.fzhhl.top/Article/details/gtaocdumjh.html

[U08] Py：展平二维列表
来源：http://dali.yvedp.cn/Article/details/gtgctvewvo.html

[y for x in nested for y in x]
来源：http://dali.yj20258888.top/Article/details/gtnupxpdug.html

[U09] Py：字典取最大值的键
来源：http://dali.sufxvd.cn/Article/details/gtowinhgoi.html

max(d, key=d.get)
来源：http://dali.xylfe.cn/Article/details/gtjchqkehk.html

[U10] Py：按值排序字典
来源：http://dali.yangfankeji.com/Article/details/gtadzrzgpx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.guowangkeji.top/Article/details/gtowucjipk.html

[U11] Py：生成器表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtrsqxesab.html

(x * 2 for x in arr)
来源：http://dali.fengsongda.top/Article/details/gtskansedm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yuxming.cn/Article/details/gttzjyvnxw.html

Counter(arr).most_common(3)
来源：http://dali.yuanzhike.top/Article/details/gtsrpsglvf.html

[U13] Py：固定长度队列
来源：http://dali.hnqzz.top/Article/details/gtakqblgvg.html

deque(maxlen=10)
来源：http://dali.snrcjt.cn/Article/details/gtxhqurtoz.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtoytowlyf.html

defaultdict(list)
来源：http://dali.hysaishi.cn/Article/details/gtasagwopr.html

[U15] Py：高精度计时
来源：http://dali.svipenyu.cn/Article/details/gtynzvislc.html

t = time.perf_counter()
来源：http://dali.xylfe.cn/Article/details/gthipyyzbt.html

[U16] Py：命令行参数解析
来源：http://dali.yvedp.cn/Article/details/gtjthaduzc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.yj202588.top/Article/details/gtxyfjshjl.html

[U17] Py：初始化日志
来源：http://dali.zhengqikj.top/Article/details/gtikcyfkwb.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtizroobhl.html

[U18] Py：预编译正则
来源：http://dali.shanyushiyangtech.top/Article/details/gtbgwbfdtd.html

pat = re.compile(r"\d+")
来源：http://dali.nanxuanxn.top/Article/details/gtxoxpdrhi.html

[U19] Py：正则替换带回调
来源：http://dali.yueranfly.top/Article/details/gtrrqhyqup.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.jyoumei.cn/Article/details/gtmagsytol.html

[U20] Py：缓存函数结果
来源：http://dali.jianghu66.top/Article/details/gtbwxinpey.html

@functools.lru_cache(maxsize=None)
来源：http://dali.gogol.net.cn/Article/details/gttmrergtj.html

[U21] Py：自定义上下文管理器
来源：http://dali.jinqigufen.top/Article/details/gtinwtyaeh.html

@contextlib.contextmanager
来源：http://dali.mhx1999.top/Article/details/gtivwtnbrb.html

[U22] Py：矩阵转置
来源：http://dali.tanke756.top/Article/details/gtrjlufrms.html

list(zip(*m))
来源：http://dali.chenlongwang.top/Article/details/gtpethcuib.html

[U23] Py：分块读取大文件
来源：http://dali.zdqjudy.top/Article/details/gtgtnwhfir.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jqgfzy.top/Article/details/gtlmhphhne.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gtswoloczd.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.jqgfzy.top/Article/details/gtgjpcqokd.html

[U25] Py：CSV 按字典读
来源：http://dali.ydzc1.top/Article/details/gthvmsrbve.html

csv.DictReader(f)
来源：http://dali.hnqzz.top/Article/details/gtbedkslia.html

[U26] Py：并发下载
来源：http://dali.zhoulong.xyz/Article/details/gtiimenufp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.vqdsnc.cn/Article/details/gtkhqotlvx.html

[U27] Py：异步 HTTP
来源：http://dali.smart0.xyz/Article/details/gtpahxukwz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.aizwys.cn/Article/details/gtslmnjfnr.html

[U28] Py：类型别名
来源：http://dali.yj20258.top/Article/details/gtmsubsutd.html

UserId = int
来源：http://dali.gotoacloud.top/Article/details/gtocrlzrpt.html

[U29] Py：属性校验
来源：http://dali.bjfxy.top/Article/details/gtepwojdrl.html

@property 与 @x.setter 配合
来源：http://dali.svipenyu.cn/Article/details/gtqgkpjfzp.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gtooswlldw.html

@dataclass(slots=True)
来源：http://dali.shangyingyoupin.top/Article/details/gtpxwuvwjl.html

[U31] Py：单测
来源：http://dali.kuanghao11.cn/Article/details/gtmuaqjlpl.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gtytmoglsx.html

[U32] Py：代码格式化
来源：http://dali.snrcjt.cn/Article/details/gtpbcfpacb.html

ruff format . && ruff check --fix .
来源：http://dali.kuanghao11.cn/Article/details/gtcmyennga.html

[U33] Py：打包发布
来源：http://dali.mhx1999.top/Article/details/gtvxtlzhdm.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aibaodan.cn/Article/details/gtkaglzrmh.html

[U34] Py：判断编码
来源：http://dali.aizwys.cn/Article/details/gtfyuvblkd.html

chardet.detect(raw)
来源：http://dali.hongshengwenyu.top/Article/details/gtthdofhkc.html

[U35] Py：发送邮件
来源：http://dali.nwbrower.top/Article/details/gtjircoada.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.gaohongyu789.top/Article/details/gtvxcowlio.html

[U36] Py：定时任务
来源：http://dali.cashguo.top/Article/details/gtembfzyzy.html

schedule.every(10).minutes.do(job)
来源：http://dali.chenzaomai.com/Article/details/gtvglrlhnz.html

[U37] Py：读写 Excel
来源：http://dali.birdmap.top/Article/details/gtmgoikebj.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.ybcxt.top/Article/details/gtihwiaykg.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gtpnprwrmk.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtcvehhjqp.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtthvzyipn.html

sys.stdout.isatty()
来源：http://dali.ydzc1.top/Article/details/gtlmmqtbdh.html

[U40] Py：打印到标准错误
来源：http://dali.yuxming.cn/Article/details/gtlaxubxtz.html

print("err", file=sys.stderr)
来源：http://dali.bjfxy.top/Article/details/gtihscytfk.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.aibaodan.cn/Article/details/gtnrpzpjfp.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.haohaochexian.top/Article/details/gtgvbvhlwn.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cqqwz.cn/Article/details/gtvkunjzni.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.nwbrower.top/Article/details/gtynxrieou.html

[U43] PHP：声明命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtsbxskkdp.html

namespace App\Http;
来源：http://dali.sysykeji.top/Article/details/gtygxbhceo.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gtovolqafu.html

declare(strict_types=1);
来源：http://dali.aizwys.cn/Article/details/gtphtcjssp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.quarkkingdee.top/Article/details/gtmflcignq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtqobquylh.html

[U46] PHP：可空类型
来源：http://dali.sysykeji.top/Article/details/gtigbmzpes.html

?string $name = null
来源：http://dali.hysaishi.cn/Article/details/gtajtmwtlv.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtllguwjnn.html

int|string $id
来源：http://dali.0kj1m.cn/Article/details/gtcycobmca.html

[U48] PHP：纯枚举
来源：http://dali.hnxiangtu.top/Article/details/gttfycavmp.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yj202588.top/Article/details/gtmstksnpw.html

[U49] PHP：只读属性
来源：http://dali.9152youxi.cn/Article/details/gtdvbzvtil.html

public readonly string $name
来源：http://dali.tianlin.xyz/Article/details/gtucbwppwu.html

[U50] PHP：构造器属性提升
来源：http://dali.xziqi.cn/Article/details/gtcbrbnbsw.html

public function __construct(private int $id) {}
来源：http://dali.yvedp.cn/Article/details/gtgsjntxaq.html

[U51] PHP：数组解构
来源：http://dali.xylfe.cn/Article/details/gtocyxqbyd.html

[$a, $b] = $arr;
来源：http://dali.yj20258.top/Article/details/gtyiwbmuer.html

[U52] PHP：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtbluosqii.html

$double = fn($x) => $x * 2;
来源：http://dali.shzxlz.cn/Article/details/gtgxdsfjuo.html

[U53] PHP：空合并运算符
来源：http://dali.chenjidiqi.icu/Article/details/gtdjupzmgl.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnxiangtu.top/Article/details/gtnjmsoxna.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtexffleik.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gtzibfltzm.html

[U55] PHP：match 表达式
来源：http://dali.fzhhl.top/Article/details/gthbruhhre.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gtawlcyfig.html

[U56] PHP：命名参数
来源：http://dali.yongpay.top/Article/details/gtfbcvtgbz.html

f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gthhtrgatx.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtojqcgvhd.html

"值: {$a}"
来源：http://dali.c1oappe.top/Article/details/gtpwzgpgww.html

[U58] PHP：数组三件套
来源：http://dali.hnqzz.top/Article/details/gtyvsetadu.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.feifeiyinyue.top/Article/details/gtdxvpfjpd.html

[U59] PHP：自定义排序
来源：http://dali.zycfv.cn/Article/details/gtiafdmcvr.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.svipenyu.cn/Article/details/gttrzpsmlu.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtwhlyaubn.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.cdnleiting.top/Article/details/gtfegcomer.html

[U61] PHP：正则
来源：http://dali.xuetiantiany.cn/Article/details/gtfgdhhtjv.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.gogol.net.cn/Article/details/gtfmegnzwz.html

[U62] PHP：日期对象
来源：http://dali.smart0.xyz/Article/details/gtgajqmdik.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.bjfxy.top/Article/details/gtlyyvimru.html

[U63] PHP：文件读写
来源：http://dali.cheryme.top/Article/details/gtygxccdqy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tian-w.cn/Article/details/gtvjdzsrjb.html

[U64] PHP：目录遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkehwehy.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.redwolf501.top/Article/details/gtxibevotp.html

[U65] PHP：会话
来源：http://dali.yueranfly.top/Article/details/gttaqcrdlw.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqlxtmbzd.html

[U66] PHP：设置 Cookie
来源：http://dali.sysykeji.top/Article/details/gtdxmlyrxq.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhxbiftr.html

[U67] PHP：处理文件上传
来源：http://dali.yanxiufei.cn/Article/details/gtzlzjzmll.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.pengpengdd.cyou/Article/details/gtytwwnoql.html

[U68] PHP：PDO 连接
来源：http://dali.smart0.xyz/Article/details/gtqqwaafdy.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.fzhhl.top/Article/details/gtmjztbfcx.html

[U69] PHP：PDO 预处理
来源：http://dali.hnqzz.top/Article/details/gtrlngsesi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtmxxdvcrz.html

[U70] PHP：PDO 事务
来源：http://dali.yj202588.top/Article/details/gtowhuegjp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jqgufenzy.top/Article/details/gtuaphgbao.html

[U71] PHP：抛出异常
来源：http://dali.pengpengdd.cyou/Article/details/gthywzatme.html

throw new RuntimeException("失败", 500);
来源：http://dali.smart0.xyz/Article/details/gtkcyfxlle.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gtfcybpuuv.html

error_log("失败: " . $e->getMessage());
来源：http://dali.wangdashe.top/Article/details/gtsilugamo.html

[U73] PHP：读取 ini 配置
来源：http://dali.vqdsnc.cn/Article/details/gtcyorqnuu.html

parse_ini_file("config.ini", true)
来源：http://dali.daria6918.cn/Article/details/gtcdlxpdbl.html

[U74] PHP：读取环境变量
来源：http://dali.cdnleiting.top/Article/details/gteyujfqvi.html

getenv("APP_ENV") ?: "production"
来源：http://dali.chenzaomai.com/Article/details/gtusidroph.html

[U75] PHP：依赖注入
来源：http://dali.jianghu66.top/Article/details/gttggdbeoo.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gtajhuzjsh.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gtgazmkhlh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.smart0.xyz/Article/details/gtxngfovdr.html

[U77] PHP：模板渲染
来源：http://dali.chenzaomai.com/Article/details/gtvukqsoig.html

composer require twig/twig
来源：http://dali.svipenyu.cn/Article/details/gtvpaizkrf.html

[U78] PHP：单元测试
来源：http://dali.hywenlv.cn/Article/details/gtthddlkuc.html

composer require --dev phpunit/phpunit
来源：http://dali.9152youxi.cn/Article/details/gtkbusgpvt.html

[U79] PHP：静态分析
来源：http://dali.zdqjudy.top/Article/details/gthkmtjqke.html

composer require --dev phpstan/phpstan
来源：http://dali.chenlongwang.top/Article/details/gtmvwnvecb.html

[U80] PHP：代码规范修复
来源：http://dali.c1oappe.top/Article/details/gtsymatjhr.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhiwuduotai.top/Article/details/gttxjisrji.html

[U81] JS：初始化项目
来源：http://dali.tanke756.top/Article/details/gtingbqmcg.html

npm init -y;  npm i express
来源：http://dali.meibo888.top/Article/details/gtltbiixhy.html

[U82] JS：package.json 脚本
来源：http://dali.jiagoushi.top/Article/details/gthgwnccaz.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yonumen.top/Article/details/gtkxskbuwx.html

[U83] JS：ES Module 导入导出
来源：http://dali.zycfv.cn/Article/details/gtxxxiaybt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yongpay.top/Article/details/gtontespmu.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gtprkapkzx.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cqqwz.cn/Article/details/gtlolutmgq.html

[U85] JS：可选链
来源：http://dali.jinqigfzy.top/Article/details/gtecchuwip.html

a?.b?.c
来源：http://dali.tian-w.cn/Article/details/gtkxddkzwh.html

[U86] JS：空值合并
来源：http://dali.svipenyu.cn/Article/details/gtflantepp.html

a ?? b
来源：http://dali.hnxiangtu.top/Article/details/gtzmybmyzc.html

[U87] JS：解构默认值
来源：http://dali.hnqzz.top/Article/details/gtphdzjwhl.html

const { a = 1, b = 2 } = obj;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadpzkstm.html

[U88] JS：对象展开合并
来源：http://dali.nanxuanxn.top/Article/details/gtxshbdmoj.html

{ ...a, ...b }
来源：http://dali.snrcjt.cn/Article/details/gtgilkjyve.html

[U89] JS：数组去重
来源：http://dali.quarkkingdee.top/Article/details/gtxvxkxxia.html

[...new Set(arr)]
来源：http://dali.shuidangran.top/Article/details/gttxajfjwu.html

[U90] JS：数字数组排序
来源：http://dali.smart0.xyz/Article/details/gtmpzwxiyu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtlwibkkqm.html

[U91] JS：对象键值遍历
来源：http://dali.dianchejie.cn/Article/details/gtkvgeqmqh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gthpfyhxqf.html

[U92] JS：深拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdysbdjfc.html

structuredClone(obj)
来源：http://dali.gogol.net.cn/Article/details/gtpzgkffjm.html

[U93] JS：模板字符串
来源：http://dali.daria6918.cn/Article/details/gtewgnckyh.html

`共 ${n} 条`
来源：http://dali.9152youxi.cn/Article/details/gtohfmlrxn.html

[U94] JS：箭头函数
来源：http://dali.meibo888.top/Article/details/gtpvgkgvaz.html

const double = x => x * 2;
来源：http://dali.0kj1m.cn/Article/details/gtzbfegasl.html

[U95] JS：Promise 包装
来源：http://dali.jinqigufen.top/Article/details/gtajsmmbrb.html

new Promise((resolve, reject) => {})
来源：http://dali.daxiang520.top/Article/details/gtbmjexbuz.html

[U96] JS：async/await 与异常
来源：http://dali.hywenlv.cn/Article/details/gtnqpyoxga.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenqahsgv.html

[U97] JS：并发请求
来源：http://dali.hammf.cn/Article/details/gtlrjfflia.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.hywenlv.cn/Article/details/gtjjqujekr.html

[U98] JS：fetch 带 JSON
来源：http://dali.316326.xyz/Article/details/gtrogqeuzl.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsrgwreb.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquvwmiyw.html

el.addEventListener("click", e => {})
来源：http://dali.tianlin.xyz/Article/details/gtauocyuxk.html

[U100] JS：DOM 查询
来源：http://dali.dianchejie.cn/Article/details/gtctmvnnnb.html

document.querySelector(".item")
来源：http://dali.cdnleiting.top/Article/details/gthmjtchcp.html

[U101] JS：classList 操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtacblpvoa.html

el.classList.toggle("active")
来源：http://dali.yueranfly.top/Article/details/gtjsmdojwj.html

[U102] JS：本地存储
来源：http://dali.daxiang520.top/Article/details/gtzuqksnnh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gtvciitrbn.html

[U103] JS：定时器
来源：http://dali.zycfv.cn/Article/details/gtbpcquldx.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhongyouzk.top/Article/details/gtgwkmcrjv.html

[U104] JS：防抖
来源：http://dali.chenlongwang.top/Article/details/gtpeeperzx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpguexzh.html

[U105] JS：节流
来源：http://dali.316326.xyz/Article/details/gtbeqcnlhl.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.nanxinkj.top/Article/details/gtoydohahe.html

[U106] JS：日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtbldzfmud.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtokbtavia.html

[U107] JS：数字千分位
来源：http://dali.smart0.xyz/Article/details/gtwklquizt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jianghu66.top/Article/details/gtphjzfjgs.html

[U108] JS：随机整数
来源：http://dali.havefunace.top/Article/details/gthabdxira.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinghuilouyu.cn/Article/details/gtzoajmkev.html

[U109] JS：数组分组
来源：http://dali.quarkkingdee.top/Article/details/gtxhhkrdtp.html

Object.groupBy(arr, x => x.type)
来源：http://dali.guannengcc.top/Article/details/gthpthjbue.html

[U110] JS：数组分块
来源：http://dali.shzxlz.cn/Article/details/gtecfuzjdf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.hammf.cn/Article/details/gtleifykvl.html

[U111] JS：对象转 Map
来源：http://dali.daxiang520.top/Article/details/gtggixnwvp.html

new Map(Object.entries(obj))
来源：http://dali.ivvv.top/Article/details/gtvvmsauul.html

[U112] JS：字符串补位
来源：http://dali.gogol.net.cn/Article/details/gtufgnyufn.html

"7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtjwgrfqhy.html

[U113] JS：正则替换全部
来源：http://dali.redwolf501.top/Article/details/gtvxnjojoa.html

s.replaceAll("a", "b")
来源：http://dali.guowangkeji.top/Article/details/gtnaveirzm.html

[U114] JS：JSON 深比较
来源：http://dali.havefunace.top/Article/details/gtzqbzniqt.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gtlghavjyw.html

[U115] JS：生成 UUID
来源：http://dali.sweek.top/Article/details/gtlodmogwo.html

crypto.randomUUID()
来源：http://dali.meibo888.top/Article/details/gtqafjlecw.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.bjfxy.top/Article/details/gtcnmcdsod.html

/** @param {string} name */ function f(name) {}
来源：http://dali.mhx1999.top/Article/details/gtazikiuwm.html

[U117] JS：单元测试
来源：http://dali.hammf.cn/Article/details/gtythjrdxk.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakahfiei.html

[U118] JS：开发服务器
来源：http://dali.shuidangran.top/Article/details/gtfkupilon.html

npm i -D vite;  npx vite
来源：http://dali.pengpengdd.cyou/Article/details/gtzwqrncjl.html

[U119] JS：生产构建
来源：http://dali.gotoacloud.top/Article/details/gtwjassuag.html

npx vite build
来源：http://dali.yonumen.top/Article/details/gtmnkxldkg.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tian-w.cn/Article/details/gtekkjdkmi.html

import.meta.env.VITE_API_URL
来源：http://dali.xylfe.cn/Article/details/gtnnldlgxa.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtpcbtawda.html

统计汇总
来源：http://dali.dashuyun.cn/Article/details/gtcszxkett.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtuuoknfun.html

按语言统计（条）：
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccoahyzn.html

Python ......... 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdkchoua.html

PHP ............ 252
来源：http://dali.dianchejie.cn/Article/details/gtfzzhwieu.html

JavaScript ..... 252
来源：http://dali.andypj.xyz/Article/details/gtosoksvme.html

TypeScript ..... 212
来源：http://dali.wangdashe.top/Article/details/gtgexhjvue.html

Java ........... 212
来源：http://dali.yuxming.cn/Article/details/gtsqkxpzkr.html

Go ............. 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtlovcrber.html

Ruby ........... 212
来源：http://dali.pengpengdd.cyou/Article/details/gtvgrnnoyg.html

C# ............. 212
来源：http://dali.jinqigufen.top/Article/details/gtafzdndfs.html

C .............. 30
来源：http://dali.zhiwuduotai.top/Article/details/gtfbjnkmrm.html

C++ ............ 30
来源：http://dali.zhiwuduotai.top/Article/details/gtvodzblgr.html

SQL ............ 90
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfuqiwqp.html

Bash ........... 80
来源：http://dali.hammf.cn/Article/details/gtcloncnjo.html

Kotlin ......... 15
来源：http://dali.xziqi.cn/Article/details/gtbmieybjp.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gtwhotxrew.html

Lua ............ 10
来源：http://dali.aibaodan.cn/Article/details/gteypfqoig.html

Perl ........... 10
来源：http://dali.yangfankeji.com/Article/details/gtwagzpjof.html

Scala .......... 10
来源：http://dali.ppjwa.cn/Article/details/gtaluxsjrv.html

------------------------------------
来源：http://dali.sxryk.cn/Article/details/gtjgkkmplo.html

合计 ........... 2106 条
来源：http://dali.xuetiantiany.cn/Article/details/gtoshavlnm.html

按章节统计：
来源：http://dali.yonumen.top/Article/details/gtujeypgrx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtlajvtvdz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gtrqnpalia.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgqbdozru.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtkthafhxb.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pycfn.com/Article/details/gtgpcvsadv.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.xinyue.icu/Article/details/gtwtctbrke.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.iojbl.cn/Article/details/gtvugfskvr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.yj20258888.top/Article/details/gtiuzjvaub.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.dashuyun.cn/Article/details/gtwsznumyd.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.zhengqikj.top/Article/details/gticigniwi.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtgpxkqnms.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ywan-chungtsiang.top/Article/details/gthdlodoca.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gtelbfopzo.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtpodoabby.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsvrgzdj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gtowwbbsmy.html

Q SQL 专题                              90
来源：http://dali.snrcjt.cn/Article/details/gtwtgcpiko.html

R Bash 专题                             80
来源：http://dali.aibaodan.cn/Article/details/gttlhafpzo.html

S C / C++ 专题                          60
来源：http://dali.zhongyouzk.top/Article/details/gtbjoevesi.html

T 其他语言补充                          60
来源：http://dali.hammf.cn/Article/details/gtkcuczjez.html

U 高频实用片段                         120
来源：http://dali.jqgfzy.top/Article/details/gtyllqtyzn.html

------------------------------------
来源：http://dali.sweek.top/Article/details/gtmshpndmj.html

合计                                  2106 条
来源：http://dali.jiagoushi.top/Article/details/gtcizqgeks.html

--------------------------------------------------------------------------------
来源：http://dali.nanxuanxn.top/Article/details/gttmtoykdc.html

使用提醒
来源：http://dali.fzhhl.top/Article/details/gtlysginzj.html

--------------------------------------------------------------------------------
来源：http://dali.yueranfly.top/Article/details/gtgmcwvdsf.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenzaomai.com/Article/details/gtqnvafuee.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.haohaochexian.top/Article/details/gtgsefumrz.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.zhengqikj.top/Article/details/gtaxahywkb.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.wangshuangyany.cn/Article/details/gtsuqubwqb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.dianchejie.cn/Article/details/gtscrdqtlh.html

—— 文件结束 ——
来源：http://dali.fzhhl.top/Article/details/gtmufteplg.html


<!-- 参考信息 -->