代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gt2iqcfdwyo.html

[T59] Scala：循环
来源：http://dali.tanke756.top/Article/details/gt2kwvuhrem.html

for (i <- 1 to 10) println(i)
来源：http://dali.yongpay.top/Article/details/gt2ilduermp.html

[T60] Scala：折叠
来源：http://dali.xylfe.cn/Article/details/gt2nmsjgvsi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gt2udfbthpu.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ihoqqwxb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cheryme.top/Article/details/gt2zrmtbkzn.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gt2pzzguvnn.html

[U01] Py：创建虚拟环境
来源：http://dali.ivvv.top/Article/details/gt2gcpoffth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.havefunace.top/Article/details/gt2ncvvzsza.html

[U02] Py：导出 / 安装依赖
来源：http://dali.svipenyu.cn/Article/details/gt2kzmnrtxq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cashguo.top/Article/details/gt2zfzmzmpx.html

[U03] Py：加载 .env 配置
来源：http://dali.shuidangran.top/Article/details/gt2jsfgnjre.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mvupybix.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2motkjeax.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gt2ozkayfex.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gt2rvwdjblk.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gt2eoyrnlou.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gt2vuvycbhf.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gt2dglcorto.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2ddrpvndq.html

{v: k for k, v in d.items()}
来源：http://dali.xuetiantiany.cn/Article/details/gt2jhqbsrie.html

[U08] Py：展平二维列表
来源：http://dali.redwolf501.top/Article/details/gt2updsritm.html

[y for x in nested for y in x]
来源：http://dali.chenzaomai.com/Article/details/gt2ysqhcqrh.html

[U09] Py：字典取最大值的键
来源：http://dali.feifeiyinyue.top/Article/details/gt2jwdccbiv.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gt2xpcazmql.html

[U10] Py：按值排序字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xjrjadau.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zhijiandao.cn/Article/details/gt2sfsjsxcs.html

[U11] Py：生成器表达式
来源：http://dali.jinqigufen.top/Article/details/gt2qgoqucca.html

(x * 2 for x in arr)
来源：http://dali.yueranfly.top/Article/details/gt2gswhiush.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.chenzaomai.com/Article/details/gt2vdujcjqg.html

Counter(arr).most_common(3)
来源：http://dali.gzhubu.top/Article/details/gt2yeffoqtq.html

[U13] Py：固定长度队列
来源：http://dali.zhongyouzk.top/Article/details/gt2bonqiymo.html

deque(maxlen=10)
来源：http://dali.xuetiantiany.cn/Article/details/gt2wpygdkfo.html

[U14] Py：分组收集到列表
来源：http://dali.yanxiufei.cn/Article/details/gt2gfbaihuh.html

defaultdict(list)
来源：http://dali.jqgufenzy.top/Article/details/gt2sumbfzvs.html

[U15] Py：高精度计时
来源：http://dali.bjfxy.top/Article/details/gt2ukqrrzjm.html

t = time.perf_counter()
来源：http://dali.shzxlz.cn/Article/details/gt2pzktpsqc.html

[U16] Py：命令行参数解析
来源：http://dali.cqqwz.cn/Article/details/gt2pncxzhea.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.pycfn.com/Article/details/gt2gqaalpkk.html

[U17] Py：初始化日志
来源：http://dali.nanxuanxn.top/Article/details/gt2czlahdcm.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.yvedp.cn/Article/details/gt2mqkgftmm.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gt2jqeqvsff.html

pat = re.compile(r"\d+")
来源：http://dali.hywenlv.cn/Article/details/gt2fwvtrspa.html

[U19] Py：正则替换带回调
来源：http://dali.316326.xyz/Article/details/gt2hrdsmitn.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gt2xycyefod.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gt2uanvmvll.html

@functools.lru_cache(maxsize=None)
来源：http://dali.sysykeji.top/Article/details/gt2ffrlljjh.html

[U21] Py：自定义上下文管理器
来源：http://dali.fzhhl.top/Article/details/gt2nfvzsxem.html

@contextlib.contextmanager
来源：http://dali.daxiang520.top/Article/details/gt2xnrvwbrd.html

[U22] Py：矩阵转置
来源：http://dali.shangyingyoupin.top/Article/details/gt2akzeymyh.html

list(zip(*m))
来源：http://dali.dianchejie.cn/Article/details/gt2qqclvcwn.html

[U23] Py：分块读取大文件
来源：http://dali.ybcxt.top/Article/details/gt2liknajkx.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.hammf.cn/Article/details/gt2xdvceiea.html

[U24] Py：路径操作
来源：http://dali.zhoulong.xyz/Article/details/gt2bkcjqqaz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tpwhhcib.html

[U25] Py：CSV 按字典读
来源：http://dali.jqgfzy.top/Article/details/gt2ekjdvyfy.html

csv.DictReader(f)
来源：http://dali.jlsjyb.cn/Article/details/gt2ijclwimf.html

[U26] Py：并发下载
来源：http://dali.tianlin.xyz/Article/details/gt2kilydyrp.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.nanxuanxn.top/Article/details/gt2edvnpmuf.html

[U27] Py：异步 HTTP
来源：http://dali.jyoumei.cn/Article/details/gt2cwtsfvmj.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.cqqwz.cn/Article/details/gt2ifwfllef.html

[U28] Py：类型别名
来源：http://dali.feifeiyinyue.top/Article/details/gt2ozijemqg.html

UserId = int
来源：http://dali.jqgufenzy.top/Article/details/gt2szrkmtir.html

[U29] Py：属性校验
来源：http://dali.fengsongda.top/Article/details/gt2rixivkpo.html

@property 与 @x.setter 配合
来源：http://dali.chenlongwang.top/Article/details/gt2zmfwfvct.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gt2anpvasip.html

@dataclass(slots=True)
来源：http://dali.hywenlv.cn/Article/details/gt2kgxzncjq.html

[U31] Py：单测
来源：http://dali.zhiwuduotai.top/Article/details/gt2tbfbxnpi.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gt2umsqundn.html

[U32] Py：代码格式化
来源：http://dali.svipenyu.cn/Article/details/gt2oxwcwvtz.html

ruff format . && ruff check --fix .
来源：http://dali.yj202588.top/Article/details/gt2wnnulnmf.html

[U33] Py：打包发布
来源：http://dali.cucudq.cn/Article/details/gt2qfbmvdvp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aibaodan.cn/Article/details/gt2kmodlxru.html

[U34] Py：判断编码
来源：http://dali.yj20258.top/Article/details/gt2jgfqduyn.html

chardet.detect(raw)
来源：http://dali.jianghu66.top/Article/details/gt2vyfjtmwf.html

[U35] Py：发送邮件
来源：http://dali.yj20258888.top/Article/details/gt2rgksnkdm.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ehwqpu.com/Article/details/gt2bztiebdn.html

[U36] Py：定时任务
来源：http://dali.jinqigufen.top/Article/details/gt2qmbgooaj.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkfljynl.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gt2jcozfsns.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.dashuyun.cn/Article/details/gt2vvswirrf.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhiwuduotai.top/Article/details/gt2iyasqdna.html

Path(__file__).resolve().parent
来源：http://dali.jqgufenzy.top/Article/details/gt2ddhhoeot.html

[U39] Py：判断是否在交互环境
来源：http://dali.shanyushiyangtech.top/Article/details/gt2abmvvhxu.html

sys.stdout.isatty()
来源：http://dali.cqqwz.cn/Article/details/gt2mggxejci.html

[U40] Py：打印到标准错误
来源：http://dali.sufxvd.cn/Article/details/gt2dvbkkrht.html

print("err", file=sys.stderr)
来源：http://dali.snrcjt.cn/Article/details/gt2uajzhdwb.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yueranfly.top/Article/details/gt2inlvaope.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yongpay.top/Article/details/gt2ffigtirf.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.hnxiangtu.top/Article/details/gt2jgwzleyy.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.zhengqikj.top/Article/details/gt2gbcjkgdm.html

[U43] PHP：声明命名空间
来源：http://dali.birdmap.top/Article/details/gt2seidiewr.html

namespace App\Http;
来源：http://dali.shzxlz.cn/Article/details/gt2iaphwbhm.html

[U44] PHP：开启严格类型
来源：http://dali.yanxiufei.cn/Article/details/gt2gurrxlyh.html

declare(strict_types=1);
来源：http://dali.shzxlz.cn/Article/details/gt2qpbannnq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yanxiufei.cn/Article/details/gt2kufcmaiy.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gt2zlggdzbw.html

[U46] PHP：可空类型
来源：http://dali.cheryme.top/Article/details/gt2ajmjhgxs.html

?string $name = null
来源：http://dali.smart0.xyz/Article/details/gt2wjcvlpku.html

[U47] PHP：联合类型
来源：http://dali.sweek.top/Article/details/gt2nigsxwcg.html

int|string $id
来源：http://dali.hnqzz.top/Article/details/gt2rwvbjyfy.html

[U48] PHP：纯枚举
来源：http://dali.nanxinkj.top/Article/details/gt2buupplst.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.yueranfly.top/Article/details/gt2umghzkbp.html

[U49] PHP：只读属性
来源：http://dali.ybcxt.top/Article/details/gt2xmourebw.html

public readonly string $name
来源：http://dali.aizwys.cn/Article/details/gt2qlzpvbyg.html

[U50] PHP：构造器属性提升
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzxcnnpg.html

public function __construct(private int $id) {}
来源：http://dali.ehwqpu.com/Article/details/gt2ocucvpok.html

[U51] PHP：数组解构
来源：http://dali.zhoulong.xyz/Article/details/gt2icvldzqk.html

[$a, $b] = $arr;
来源：http://dali.cheryme.top/Article/details/gt2amxlqioy.html

[U52] PHP：箭头函数
来源：http://dali.jiagoushi.top/Article/details/gt2sqacbrkb.html

$double = fn($x) => $x * 2;
来源：http://dali.hfpthk.cn/Article/details/gt2yjsfpmnq.html

[U53] PHP：空合并运算符
来源：http://dali.wangdashe.top/Article/details/gt2rvwvupee.html

$v = $a ?? $b ?? "default";
来源：http://dali.hnqzz.top/Article/details/gt2qniigxee.html

[U54] PHP：空安全调用
来源：http://dali.yuxming.cn/Article/details/gt2xdpcooys.html

$obj?->method()
来源：http://dali.zhixingplan.top/Article/details/gt2lgvpvfzr.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gt2okewlrnl.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zdqjudy.top/Article/details/gt2kntaanqo.html

[U56] PHP：命名参数
来源：http://dali.shzxlz.cn/Article/details/gt2ijzksczp.html

f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gt2stjojtuh.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2ussbrhig.html

"值: {$a}"
来源：http://dali.sysykeji.top/Article/details/gt2lxfiabnl.html

[U58] PHP：数组三件套
来源：http://dali.tianlin.xyz/Article/details/gt2gplmiziq.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2zspmuvzq.html

[U59] PHP：自定义排序
来源：http://dali.sxryk.cn/Article/details/gt2mxfvtpal.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jlsjyb.cn/Article/details/gt2jnglelfj.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gt2lmydsyup.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jiagoushi.top/Article/details/gt2qgppnomh.html

[U61] PHP：正则
来源：http://dali.hysaishi.cn/Article/details/gt2fxlbxevb.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.mhx1999.top/Article/details/gt2jcqfascc.html

[U62] PHP：日期对象
来源：http://dali.ydzc1.top/Article/details/gt2oztgfrzs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhengqikj.top/Article/details/gt2uafkekav.html

[U63] PHP：文件读写
来源：http://dali.yj20258888.top/Article/details/gt2mfupulpi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gt2gagfrbtc.html

[U64] PHP：目录遍历
来源：http://dali.sxryk.cn/Article/details/gt2qthqykir.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.iojbl.cn/Article/details/gt2fimosfna.html

[U65] PHP：会话
来源：http://dali.jianghu66.top/Article/details/gt2xyvffrao.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2eppbronn.html

[U66] PHP：设置 Cookie
来源：http://dali.nwbrower.top/Article/details/gt2sjpdxbel.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ehwqpu.com/Article/details/gt2vbexhtox.html

[U67] PHP：处理文件上传
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xbaepmnw.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.zhijiandao.cn/Article/details/gt2bwziacew.html

[U68] PHP：PDO 连接
来源：http://dali.zhengqikj.top/Article/details/gt2rvfxhmzn.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yj202588.top/Article/details/gt2pdwcenwl.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gt2kbtrsorq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2myofcfii.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gosmejbp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.havefunace.top/Article/details/gt2owyyncdq.html

[U71] PHP：抛出异常
来源：http://dali.jinqigfzy.top/Article/details/gt2qxeilgsq.html

throw new RuntimeException("失败", 500);
来源：http://dali.yj202588.top/Article/details/gt2pucluono.html

[U72] PHP：写错误日志
来源：http://dali.feifeiyinyue.top/Article/details/gt2szyxoler.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xuetiantiany.cn/Article/details/gt2yewtthmj.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gt2pourejba.html

parse_ini_file("config.ini", true)
来源：http://dali.quarkkingdee.top/Article/details/gt2otsbspfs.html

[U74] PHP：读取环境变量
来源：http://dali.ppjwa.cn/Article/details/gt2kpkittjc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.c1oappe.top/Article/details/gt2xqpnpzoa.html

[U75] PHP：依赖注入
来源：http://dali.zhongyouzk.top/Article/details/gt2dmqcikmj.html

composer require psr/container
来源：http://dali.svipenyu.cn/Article/details/gt2wuozjetk.html

[U76] PHP：简单路由
来源：http://dali.svipenyu.cn/Article/details/gt2yijqivsp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gt2ujcclxwz.html

[U77] PHP：模板渲染
来源：http://dali.feifeiyinyue.top/Article/details/gt2jpurocyi.html

composer require twig/twig
来源：http://dali.ivvv.top/Article/details/gt2dgeavjhb.html

[U78] PHP：单元测试
来源：http://dali.birdmap.top/Article/details/gt2apkwsfli.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gt2kzxkjjwm.html

[U79] PHP：静态分析
来源：http://dali.pengpengdd.cyou/Article/details/gt2oqujcdgw.html

composer require --dev phpstan/phpstan
来源：http://dali.tianlin.xyz/Article/details/gt2omwsoczr.html

[U80] PHP：代码规范修复
来源：http://dali.tian-w.cn/Article/details/gt2umilhtvi.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.sufxvd.cn/Article/details/gt2bpyhvofh.html

[U81] JS：初始化项目
来源：http://dali.xuanzx.com/Article/details/gt2oxgnqnmd.html

npm init -y;  npm i express
来源：http://dali.ydzc1.top/Article/details/gt2fbpoknsx.html

[U82] JS：package.json 脚本
来源：http://dali.zhongyouzk.top/Article/details/gt2optgbebg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.vqdsnc.cn/Article/details/gt2wuiopffl.html

[U83] JS：ES Module 导入导出
来源：http://dali.xziqi.cn/Article/details/gt2xphujnpv.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nehwmeyh.html

[U84] JS：CommonJS 写法
来源：http://dali.xuanzx.com/Article/details/gt2xvalzbag.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.xuetiantiany.cn/Article/details/gt2xaswyznd.html

[U85] JS：可选链
来源：http://dali.jqgufenzy.top/Article/details/gt2ogspvxdb.html

a?.b?.c
来源：http://dali.hysaishi.cn/Article/details/gt2brjaosrc.html

[U86] JS：空值合并
来源：http://dali.daxiang520.top/Article/details/gt2fjylfcnc.html

a ?? b
来源：http://dali.shzxlz.cn/Article/details/gt2zgnqsrdr.html

[U87] JS：解构默认值
来源：http://dali.xinyue.icu/Article/details/gt2zdosfkpd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.mhx1999.top/Article/details/gt2qpdxmttk.html

[U88] JS：对象展开合并
来源：http://dali.shuidangran.top/Article/details/gt2jtqrbvhf.html

{ ...a, ...b }
来源：http://dali.xziqi.cn/Article/details/gt2atxoazgh.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gt2prkdifhj.html

[...new Set(arr)]
来源：http://dali.haohaochexian.top/Article/details/gt2bavyurft.html

[U90] JS：数字数组排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2ntpujgkb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.xylfe.cn/Article/details/gt2awacfcyw.html

[U91] JS：对象键值遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2jbmobeir.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gt2wwuwonma.html

[U92] JS：深拷贝
来源：http://dali.zycfv.cn/Article/details/gt2atgpdxqv.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2kaeliwfy.html

[U93] JS：模板字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oapgakzy.html

`共 ${n} 条`
来源：http://dali.shangyingyoupin.top/Article/details/gt2leucrxaf.html

[U94] JS：箭头函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2gwolkigk.html

const double = x => x * 2;
来源：http://dali.tanke756.top/Article/details/gt2cnededis.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gt2lnlrdfva.html

new Promise((resolve, reject) => {})
来源：http://dali.snrcjt.cn/Article/details/gt2uldpoyic.html

[U96] JS：async/await 与异常
来源：http://dali.feifeiyinyue.top/Article/details/gt2ernetasv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.ybcxt.top/Article/details/gt2nskgjsxe.html

[U97] JS：并发请求
来源：http://dali.yj202588.top/Article/details/gt2ncnaddbk.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xzzpzjtv.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gt2cdscmcpa.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.gaohongyu789.top/Article/details/gt2hthvxxwe.html

[U99] JS：事件监听
来源：http://dali.gotoacloud.top/Article/details/gt2gskmsmeo.html

el.addEventListener("click", e => {})
来源：http://dali.zhixingplan.top/Article/details/gt2sbxatlxd.html

[U100] JS：DOM 查询
来源：http://dali.shzxlz.cn/Article/details/gt2wodhlazo.html

document.querySelector(".item")
来源：http://dali.tianlin.xyz/Article/details/gt2nybrkmew.html

[U101] JS：classList 操作
来源：http://dali.jlsjyb.cn/Article/details/gt2xsyuezhy.html

el.classList.toggle("active")
来源：http://dali.bjfxy.top/Article/details/gt2terziosm.html

[U102] JS：本地存储
来源：http://dali.iojbl.cn/Article/details/gt2dcoczcyp.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.quarkkingdee.top/Article/details/gt2nfivphgr.html

[U103] JS：定时器
来源：http://dali.0kj1m.cn/Article/details/gt2kjwedigq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhengqikj.top/Article/details/gt2jfmrmjub.html

[U104] JS：防抖
来源：http://dali.dianchejie.cn/Article/details/gt2mprvfojp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hnqzz.top/Article/details/gt2leggsqgg.html

[U105] JS：节流
来源：http://dali.jinqigufen.top/Article/details/gt2grgvdeys.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.ydzc1.top/Article/details/gt2epkuzghs.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2lgoyyovh.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.chenlongwang.top/Article/details/gt2royqijmr.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2xiiljsie.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.sxryk.cn/Article/details/gt2tmiuowlp.html

[U108] JS：随机整数
来源：http://dali.nwbrower.top/Article/details/gt2mmhpsycq.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.yuanzhike.top/Article/details/gt2erysoazr.html

[U109] JS：数组分组
来源：http://dali.dianchejie.cn/Article/details/gt2fiiqsmrb.html

Object.groupBy(arr, x => x.type)
来源：http://dali.zhiwuduotai.top/Article/details/gt2qafycsli.html

[U110] JS：数组分块
来源：http://dali.gogol.net.cn/Article/details/gt2epoaajmd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yangfankeji.com/Article/details/gt2wmqsfato.html

[U111] JS：对象转 Map
来源：http://dali.xziqi.cn/Article/details/gt2ccenzmop.html

new Map(Object.entries(obj))
来源：http://dali.hongshengwenyu.top/Article/details/gt2vyyjsdkn.html

[U112] JS：字符串补位
来源：http://dali.jiagoushi.top/Article/details/gt2rhhskhmg.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gt2indjmfmj.html

[U113] JS：正则替换全部
来源：http://dali.yuxming.cn/Article/details/gt2vvgmznvp.html

s.replaceAll("a", "b")
来源：http://dali.guannengcc.top/Article/details/gt2tfaickgy.html

[U114] JS：JSON 深比较
来源：http://dali.ivvv.top/Article/details/gt2kkekplig.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.316326.xyz/Article/details/gt2yjiegroj.html

[U115] JS：生成 UUID
来源：http://dali.nanxinkj.top/Article/details/gt2ubarfnec.html

crypto.randomUUID()
来源：http://dali.316326.xyz/Article/details/gt2kmdyybmj.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cucudq.cn/Article/details/gt2xafglznd.html

/** @param {string} name */ function f(name) {}
来源：http://dali.ydzc1.top/Article/details/gt2pwwcmcbk.html

[U117] JS：单元测试
来源：http://dali.xziqi.cn/Article/details/gt2kekkytox.html

npm i -D vitest;  npx vitest
来源：http://dali.yonumen.top/Article/details/gt2irpeyodp.html

[U118] JS：开发服务器
来源：http://dali.zhoulong.xyz/Article/details/gt2uygkigfq.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gt2mjiioqcd.html

[U119] JS：生产构建
来源：http://dali.daxiang520.top/Article/details/gt2mvcpzlsd.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2bqofzwly.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hvlelejd.html

import.meta.env.VITE_API_URL
来源：http://dali.quarkkingdee.top/Article/details/gt2iujotntu.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2eytxpkug.html

统计汇总
来源：http://dali.shangyingyoupin.top/Article/details/gt2jrmjkdww.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zhexkqbx.html

按语言统计（条）：
来源：http://dali.zycfv.cn/Article/details/gt2zguluasu.html

Python ......... 252
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qkaoasbj.html

PHP ............ 252
来源：http://dali.ybcxt.top/Article/details/gt2qlrjmary.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gt2xzezqjfl.html

TypeScript ..... 212
来源：http://dali.ehwqpu.com/Article/details/gt2yrypxgcf.html

Java ........... 212
来源：http://dali.c1oappe.top/Article/details/gt2lbtzbbdy.html

Go ............. 212
来源：http://dali.shzxlz.cn/Article/details/gt2mwejnkzz.html

Ruby ........... 212
来源：http://dali.zhongyouzk.top/Article/details/gt2jrqeedkf.html

C# ............. 212
来源：http://dali.tanke756.top/Article/details/gt2wbjcyupl.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gt2rudkotwb.html

C++ ............ 30
来源：http://dali.zhoulong.xyz/Article/details/gt2dcqzwffo.html

SQL ............ 90
来源：http://dali.fzhhl.top/Article/details/gt2bzgtfinp.html

Bash ........... 80
来源：http://dali.jianghu66.top/Article/details/gt2bflqhkmm.html

Kotlin ......... 15
来源：http://dali.hnqzz.top/Article/details/gt2mptmgrvf.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gt2fwkjmbrz.html

Lua ............ 10
来源：http://dali.gzhubu.top/Article/details/gt2tsztuiit.html

Perl ........... 10
来源：http://dali.aibaodan.cn/Article/details/gt2sotprqip.html

Scala .......... 10
来源：http://dali.ivvv.top/Article/details/gt2fnvdvuld.html

------------------------------------
来源：http://dali.daria6918.cn/Article/details/gt2icjhxnab.html

合计 ........... 2106 条
来源：http://dali.quarkkingdee.top/Article/details/gt2wncuixsv.html

按章节统计：
来源：http://dali.yj20258888.top/Article/details/gt2ifyvtvxk.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ynmckkbq.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2ojxiuyxc.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.tanke756.top/Article/details/gt2lvhznoxe.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.sweek.top/Article/details/gt2hmyxmfaz.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.cqqwz.cn/Article/details/gt2uhyvnjoz.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.gzhubu.top/Article/details/gt2nrnjbbka.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.shangyingyoupin.top/Article/details/gt2mouzqgff.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pycfn.com/Article/details/gt2rdkbrgjt.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.gotoacloud.top/Article/details/gt2kfyiexmt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gt2vmsqgfnu.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.tianlin.xyz/Article/details/gt2dkrpekwv.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2mdxjuumm.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.svipenyu.cn/Article/details/gt2oflzdsvv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.zhoulong.xyz/Article/details/gt2xtlzfrml.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.vqdsnc.cn/Article/details/gt2lbhxemeb.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kqqzzyzl.html

Q SQL 专题                              90
来源：http://dali.pycfn.com/Article/details/gt2yptwukrs.html

R Bash 专题                             80
来源：http://dali.chenlongwang.top/Article/details/gt2xtdimoyo.html

S C / C++ 专题                          60
来源：http://dali.yj202588.top/Article/details/gt2ytyeilkm.html

T 其他语言补充                          60
来源：http://dali.vqdsnc.cn/Article/details/gt2alwvktye.html

U 高频实用片段                         120
来源：http://dali.yj20258888.top/Article/details/gt2oqiomeqj.html

------------------------------------
来源：http://dali.jinqigufen.top/Article/details/gt2nqrjssgt.html

合计                                  2106 条
来源：http://dali.tanke756.top/Article/details/gt2mxyrdcxe.html

--------------------------------------------------------------------------------
来源：http://dali.gzhubu.top/Article/details/gt2aoiffipw.html

使用提醒
来源：http://dali.nanxuanxn.top/Article/details/gt2gvsbovik.html

--------------------------------------------------------------------------------
来源：http://dali.yuxming.cn/Article/details/gt2lupuslvh.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.smart0.xyz/Article/details/gt2mlxovcdb.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.xuanzx.com/Article/details/gt2eptnhrkl.html


<!-- 参考信息 -->