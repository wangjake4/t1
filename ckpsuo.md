代发 wailian999

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aibaodan.cn/Article/details/gt2mukaiutn.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2rfvrmuog.html

for (i <- 1 to 10) println(i)
来源：http://dali.aibaodan.cn/Article/details/gt2qkexsfon.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gt2exuanlzi.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenlongwang.top/Article/details/gt2qfgzmcfy.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2csjkksxk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.kuanghao11.cn/Article/details/gt2vlwqjatq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2sfnicjod.html

[U01] Py：创建虚拟环境
来源：http://dali.sufxvd.cn/Article/details/gt2reyocduz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.chenjidiqi.icu/Article/details/gt2wimqynbf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gt2bbarzgub.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhengqikj.top/Article/details/gt2mqvjjvnb.html

[U03] Py：加载 .env 配置
来源：http://dali.zhixingplan.top/Article/details/gt2xbsnnnjf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sxryk.cn/Article/details/gt2hwtqgisq.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gt2qaamxayt.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yvedp.cn/Article/details/gt2zclqozoz.html

[U05] Py：列表去重且保序
来源：http://dali.jqgfzy.top/Article/details/gt2vhkyoipm.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2qkjazzqr.html

[U06] Py：合并两个字典
来源：http://dali.dianchejie.cn/Article/details/gt2iwihezec.html

{**a, **b}
来源：http://dali.wangdashe.top/Article/details/gt2fouyqkkj.html

[U07] Py：反转字典键值
来源：http://dali.zhoulong.xyz/Article/details/gt2jxmwfdde.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2dutlfqgf.html

[U08] Py：展平二维列表
来源：http://dali.sysykeji.top/Article/details/gt2bmlyeymy.html

[y for x in nested for y in x]
来源：http://dali.cheryme.top/Article/details/gt2bahkxmgi.html

[U09] Py：字典取最大值的键
来源：http://dali.zhixingplan.top/Article/details/gt2skujleeu.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gt2kvqsfcms.html

[U10] Py：按值排序字典
来源：http://dali.nwbrower.top/Article/details/gt2absgrrxd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cashguo.top/Article/details/gt2jrgmuklm.html

[U11] Py：生成器表达式
来源：http://dali.jqgufenzy.top/Article/details/gt2wjrgnnnv.html

(x * 2 for x in arr)
来源：http://dali.xylfe.cn/Article/details/gt2yqhdzgfu.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.gzhubu.top/Article/details/gt2jilggbds.html

Counter(arr).most_common(3)
来源：http://dali.yuxming.cn/Article/details/gt2kbatizkv.html

[U13] Py：固定长度队列
来源：http://dali.yueranfly.top/Article/details/gt2zysjeous.html

deque(maxlen=10)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kumlxfde.html

[U14] Py：分组收集到列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbgbvqst.html

defaultdict(list)
来源：http://dali.hammf.cn/Article/details/gt2eqbzjzrh.html

[U15] Py：高精度计时
来源：http://dali.hammf.cn/Article/details/gt2ogsublrq.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gt2slwbfkgd.html

[U16] Py：命令行参数解析
来源：http://dali.birdmap.top/Article/details/gt2uihmedho.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhengqikj.top/Article/details/gt2czuvmltz.html

[U17] Py：初始化日志
来源：http://dali.quarkkingdee.top/Article/details/gt2jdulvimv.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.birdmap.top/Article/details/gt2klflbity.html

[U18] Py：预编译正则
来源：http://dali.yvedp.cn/Article/details/gt2ezexildq.html

pat = re.compile(r"\d+")
来源：http://dali.zhongyouzk.top/Article/details/gt2psklxtob.html

[U19] Py：正则替换带回调
来源：http://dali.ybcxt.top/Article/details/gt2hczhglsj.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.guannengcc.top/Article/details/gt2pcbpbmpo.html

[U20] Py：缓存函数结果
来源：http://dali.daxiang520.top/Article/details/gt2uamlkqry.html

@functools.lru_cache(maxsize=None)
来源：http://dali.cqqwz.cn/Article/details/gt2crcnxiwr.html

[U21] Py：自定义上下文管理器
来源：http://dali.shangyingyoupin.top/Article/details/gt2oxrrjilm.html

@contextlib.contextmanager
来源：http://dali.zdqjudy.top/Article/details/gt2mhjupmxi.html

[U22] Py：矩阵转置
来源：http://dali.cashguo.top/Article/details/gt2llarvbnp.html

list(zip(*m))
来源：http://dali.bjfxy.top/Article/details/gt2juiuwone.html

[U23] Py：分块读取大文件
来源：http://dali.quarkkingdee.top/Article/details/gt2rgifgrsa.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.jlsjyb.cn/Article/details/gt2qzsstwzh.html

[U24] Py：路径操作
来源：http://dali.jinqigfzy.top/Article/details/gt2pxyjbekp.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.pycfn.com/Article/details/gt2rqzoephb.html

[U25] Py：CSV 按字典读
来源：http://dali.hnxiangtu.top/Article/details/gt2rkjtokln.html

csv.DictReader(f)
来源：http://dali.daxiang520.top/Article/details/gt2dqobaehr.html

[U26] Py：并发下载
来源：http://dali.haohaochexian.top/Article/details/gt2vacabkso.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gt2chgloltb.html

[U27] Py：异步 HTTP
来源：http://dali.gogol.net.cn/Article/details/gt2uitapmsv.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shuidangran.top/Article/details/gt2quxvjpob.html

[U28] Py：类型别名
来源：http://dali.sufxvd.cn/Article/details/gt2mofemqrk.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gt2dnfvgubn.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gt2csevrwnh.html

@property 与 @x.setter 配合
来源：http://dali.jyoumei.cn/Article/details/gt2waodixbq.html

[U30] Py：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2paacsccr.html

@dataclass(slots=True)
来源：http://dali.pycfn.com/Article/details/gt2rpuuexdn.html

[U31] Py：单测
来源：http://dali.c1oappe.top/Article/details/gt2vhlzrpqk.html

python -m pytest -q
来源：http://dali.mhx1999.top/Article/details/gt2hchwtwhj.html

[U32] Py：代码格式化
来源：http://dali.jinqigfzy.top/Article/details/gt2pdcfyuei.html

ruff format . && ruff check --fix .
来源：http://dali.xylfe.cn/Article/details/gt2upxuvefb.html

[U33] Py：打包发布
来源：http://dali.jinghuilouyu.cn/Article/details/gt2szlgxuzx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxuanxn.top/Article/details/gt2vsahrpvi.html

[U34] Py：判断编码
来源：http://dali.vqdsnc.cn/Article/details/gt2skavxkbp.html

chardet.detect(raw)
来源：http://dali.guowangkeji.top/Article/details/gt2rvsgmacg.html

[U35] Py：发送邮件
来源：http://dali.gotoacloud.top/Article/details/gt2ecfkeldk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuetiantiany.cn/Article/details/gt2tpepiefd.html

[U36] Py：定时任务
来源：http://dali.xylfe.cn/Article/details/gt2xbcxyosv.html

schedule.every(10).minutes.do(job)
来源：http://dali.cqqwz.cn/Article/details/gt2dplxbcya.html

[U37] Py：读写 Excel
来源：http://dali.cdnleiting.top/Article/details/gt2cbcanvsm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jianghu66.top/Article/details/gt2egwrilsy.html

[U38] Py：获取脚本所在目录
来源：http://dali.yangfankeji.com/Article/details/gt2htinlzxh.html

Path(__file__).resolve().parent
来源：http://dali.shuidangran.top/Article/details/gt2ltfjqabl.html

[U39] Py：判断是否在交互环境
来源：http://dali.shangyingyoupin.top/Article/details/gt2jatouutl.html

sys.stdout.isatty()
来源：http://dali.svipenyu.cn/Article/details/gt2abnqmtqi.html

[U40] Py：打印到标准错误
来源：http://dali.jqgfzy.top/Article/details/gt2qxblcpsk.html

print("err", file=sys.stderr)
来源：http://dali.chenlongwang.top/Article/details/gt2uwjqycfo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.gotoacloud.top/Article/details/gt2qwcudygw.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.yvedp.cn/Article/details/gt2hiuzpmam.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.sweek.top/Article/details/gt2ayekxquk.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gt2ettveyzt.html

[U43] PHP：声明命名空间
来源：http://dali.sxryk.cn/Article/details/gt2zavioxtz.html

namespace App\Http;
来源：http://dali.aibaodan.cn/Article/details/gt2insboxfr.html

[U44] PHP：开启严格类型
来源：http://dali.yangfankeji.com/Article/details/gt2hwdbdebk.html

declare(strict_types=1);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mvowvfze.html

[U45] PHP：类型声明与返回类型
来源：http://dali.chenzaomai.com/Article/details/gt2dgccnatv.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2hwbwjsyn.html

[U46] PHP：可空类型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfvtodwn.html

?string $name = null
来源：http://dali.hywenlv.cn/Article/details/gt2dnltvfgt.html

[U47] PHP：联合类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwhldqym.html

int|string $id
来源：http://dali.gzhubu.top/Article/details/gt2kjhkagly.html

[U48] PHP：纯枚举
来源：http://dali.zhongyouzk.top/Article/details/gt2gvjggrkr.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.svipenyu.cn/Article/details/gt2pcfvuhcp.html

[U49] PHP：只读属性
来源：http://dali.hammf.cn/Article/details/gt2akswjggz.html

public readonly string $name
来源：http://dali.xuanzx.com/Article/details/gt2fvflhxmg.html

[U50] PHP：构造器属性提升
来源：http://dali.aizwys.cn/Article/details/gt2olyihyst.html

public function __construct(private int $id) {}
来源：http://dali.sysykeji.top/Article/details/gt2fymsgexd.html

[U51] PHP：数组解构
来源：http://dali.meibo888.top/Article/details/gt2ejsrvyon.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gt2hcjrivug.html

[U52] PHP：箭头函数
来源：http://dali.chenzaomai.com/Article/details/gt2ilqhxhkd.html

$double = fn($x) => $x * 2;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bdabtknj.html

[U53] PHP：空合并运算符
来源：http://dali.9152youxi.cn/Article/details/gt2mwvraskw.html

$v = $a ?? $b ?? "default";
来源：http://dali.iojbl.cn/Article/details/gt2jrnllqmj.html

[U54] PHP：空安全调用
来源：http://dali.vqdsnc.cn/Article/details/gt2znkojqnn.html

$obj?->method()
来源：http://dali.gotoacloud.top/Article/details/gt2keiquffg.html

[U55] PHP：match 表达式
来源：http://dali.yuxming.cn/Article/details/gt2sovaqndj.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.yj202588.top/Article/details/gt2zqljuigl.html

[U56] PHP：命名参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2qpvrceuu.html

f(a: 1, b: 2)
来源：http://dali.jqgfzy.top/Article/details/gt2xaxaucmh.html

[U57] PHP：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2nhiykwmg.html

"值: {$a}"
来源：http://dali.guannengcc.top/Article/details/gt2vwtyagwt.html

[U58] PHP：数组三件套
来源：http://dali.snrcjt.cn/Article/details/gt2wyaloevf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.ydzc1.top/Article/details/gt2rubolhqx.html

[U59] PHP：自定义排序
来源：http://dali.daxiang520.top/Article/details/gt2tsgrfypn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.cucudq.cn/Article/details/gt2ctiqplxn.html

[U60] PHP：JSON 编解码
来源：http://dali.zycfv.cn/Article/details/gt2cytoieji.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2dtopxtee.html

[U61] PHP：正则
来源：http://dali.svipenyu.cn/Article/details/gt2nmjdepym.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jianghu66.top/Article/details/gt2vyjeozia.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2nfdhmwbg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zycfv.cn/Article/details/gt2jtjfnqnt.html

[U63] PHP：文件读写
来源：http://dali.guannengcc.top/Article/details/gt2oadrfhtq.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.cdnleiting.top/Article/details/gt2qtgzhgoy.html

[U64] PHP：目录遍历
来源：http://dali.sweek.top/Article/details/gt2sonhzoax.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.svipenyu.cn/Article/details/gt2pslnudmr.html

[U65] PHP：会话
来源：http://dali.zhoulong.xyz/Article/details/gt2wmxxsxql.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gt2wyruwftm.html

[U66] PHP：设置 Cookie
来源：http://dali.yonumen.top/Article/details/gt2twjtusvx.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.tian-w.cn/Article/details/gt2gpfudlfa.html

[U67] PHP：处理文件上传
来源：http://dali.tanke756.top/Article/details/gt2buqatnsj.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tanke756.top/Article/details/gt2jubyrwhw.html

[U68] PHP：PDO 连接
来源：http://dali.cashguo.top/Article/details/gt2bzszdolg.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuxgqrfw.html

[U69] PHP：PDO 预处理
来源：http://dali.mhx1999.top/Article/details/gt2mdswquad.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.wangshuangyany.cn/Article/details/gt2yraaicdk.html

[U70] PHP：PDO 事务
来源：http://dali.sxryk.cn/Article/details/gt2rfpejmtx.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhoulong.xyz/Article/details/gt2hnqwjdvq.html

[U71] PHP：抛出异常
来源：http://dali.zhixingplan.top/Article/details/gt2ehwzkbja.html

throw new RuntimeException("失败", 500);
来源：http://dali.feifeiyinyue.top/Article/details/gt2kboqtjbd.html

[U72] PHP：写错误日志
来源：http://dali.svipenyu.cn/Article/details/gt2gpsggghm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.daxiang520.top/Article/details/gt2akrnxfnl.html

[U73] PHP：读取 ini 配置
来源：http://dali.dianchejie.cn/Article/details/gt2pamkxgpg.html

parse_ini_file("config.ini", true)
来源：http://dali.zhengqikj.top/Article/details/gt2yoyeqkhj.html

[U74] PHP：读取环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2avupfovm.html

getenv("APP_ENV") ?: "production"
来源：http://dali.redwolf501.top/Article/details/gt2utyfrsgl.html

[U75] PHP：依赖注入
来源：http://dali.jqgfzy.top/Article/details/gt2smmtyuqi.html

composer require psr/container
来源：http://dali.ybcxt.top/Article/details/gt2zfgbptub.html

[U76] PHP：简单路由
来源：http://dali.yangfankeji.com/Article/details/gt2rsegcdkh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gt2nxyzctli.html

[U77] PHP：模板渲染
来源：http://dali.9152youxi.cn/Article/details/gt2rmiaqitn.html

composer require twig/twig
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2idsdrfgk.html

[U78] PHP：单元测试
来源：http://dali.hysaishi.cn/Article/details/gt2dthobwpi.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gt2dnuammih.html

[U79] PHP：静态分析
来源：http://dali.hnqzz.top/Article/details/gt2yvutjurl.html

composer require --dev phpstan/phpstan
来源：http://dali.gogol.net.cn/Article/details/gt2loufilgp.html

[U80] PHP：代码规范修复
来源：http://dali.zhongyouzk.top/Article/details/gt2hzvzwqlq.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.yuanzhike.top/Article/details/gt2lhchvmkx.html

[U81] JS：初始化项目
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2elnvljso.html

npm init -y;  npm i express
来源：http://dali.wangshuangyany.cn/Article/details/gt2chkqtfce.html

[U82] JS：package.json 脚本
来源：http://dali.hongshengwenyu.top/Article/details/gt2rlesuyis.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.sufxvd.cn/Article/details/gt2iabprnpw.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gt2gjcscddc.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fpoobjsw.html

[U84] JS：CommonJS 写法
来源：http://dali.bjfxy.top/Article/details/gt2mfznwyza.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nwbrower.top/Article/details/gt2cjcqhncu.html

[U85] JS：可选链
来源：http://dali.guowangkeji.top/Article/details/gt2nkmoqmzj.html

a?.b?.c
来源：http://dali.jqgfzy.top/Article/details/gt2nwpthzqc.html

[U86] JS：空值合并
来源：http://dali.ppjwa.cn/Article/details/gt2xfcffpaa.html

a ?? b
来源：http://dali.birdmap.top/Article/details/gt2nfwhtztw.html

[U87] JS：解构默认值
来源：http://dali.snrcjt.cn/Article/details/gt2yhvzplgp.html

const { a = 1, b = 2 } = obj;
来源：http://dali.9152youxi.cn/Article/details/gt2tclkmgps.html

[U88] JS：对象展开合并
来源：http://dali.havefunace.top/Article/details/gt2dzpjcznl.html

{ ...a, ...b }
来源：http://dali.guannengcc.top/Article/details/gt2trgmeyqq.html

[U89] JS：数组去重
来源：http://dali.c1oappe.top/Article/details/gt2ulldxifc.html

[...new Set(arr)]
来源：http://dali.zhiwuduotai.top/Article/details/gt2yjzsksxj.html

[U90] JS：数字数组排序
来源：http://dali.cheryme.top/Article/details/gt2kveiskaa.html

[...arr].sort((a, b) => a - b)
来源：http://dali.bjfxy.top/Article/details/gt2csasjoij.html

[U91] JS：对象键值遍历
来源：http://dali.shangyingyoupin.top/Article/details/gt2shjuioct.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.quarkkingdee.top/Article/details/gt2ufhdaltu.html

[U92] JS：深拷贝
来源：http://dali.yuxming.cn/Article/details/gt2erzeqtrq.html

structuredClone(obj)
来源：http://dali.xuanzx.com/Article/details/gt2ufmjeazt.html

[U93] JS：模板字符串
来源：http://dali.zhengqikj.top/Article/details/gt2vauydkcz.html

`共 ${n} 条`
来源：http://dali.haohaochexian.top/Article/details/gt2avmjazbp.html

[U94] JS：箭头函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2loveclzy.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gt2noeetjin.html

[U95] JS：Promise 包装
来源：http://dali.fzhhl.top/Article/details/gt2drhygrnb.html

new Promise((resolve, reject) => {})
来源：http://dali.smart0.xyz/Article/details/gt2elpejmqn.html

[U96] JS：async/await 与异常
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkaupnhy.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gt2kiylbrex.html

[U97] JS：并发请求
来源：http://dali.jianghu66.top/Article/details/gt2iejqvmin.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.iojbl.cn/Article/details/gt2yjvlyxyr.html

[U98] JS：fetch 带 JSON
来源：http://dali.hfpthk.cn/Article/details/gt2txbvmgfx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.yanxiufei.cn/Article/details/gt2mpwzjmnu.html

[U99] JS：事件监听
来源：http://dali.jqgufenzy.top/Article/details/gt2dgllqxjd.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2twcdojbh.html

[U100] JS：DOM 查询
来源：http://dali.andypj.xyz/Article/details/gt2figwczks.html

document.querySelector(".item")
来源：http://dali.bjfxy.top/Article/details/gt2fdbgteam.html

[U101] JS：classList 操作
来源：http://dali.birdmap.top/Article/details/gt2gubvkahc.html

el.classList.toggle("active")
来源：http://dali.tanke756.top/Article/details/gt2rykzkzep.html

[U102] JS：本地存储
来源：http://dali.xylfe.cn/Article/details/gt2lnayydof.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yueranfly.top/Article/details/gt2wyjecgzn.html

[U103] JS：定时器
来源：http://dali.fzhhl.top/Article/details/gt2bpbmdjad.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.pycfn.com/Article/details/gt2lgpbxazb.html

[U104] JS：防抖
来源：http://dali.gaohongyu789.top/Article/details/gt2dwkumjop.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.jlsjyb.cn/Article/details/gt2jkndhkov.html

[U105] JS：节流
来源：http://dali.yonumen.top/Article/details/gt2qrwzpisi.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tianlin.xyz/Article/details/gt2gigndaxt.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2abjpbbwe.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hnxiangtu.top/Article/details/gt2ocgmkfmp.html

[U107] JS：数字千分位
来源：http://dali.yanxiufei.cn/Article/details/gt2laeidflj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.pengpengdd.cyou/Article/details/gt2oleyucyu.html

[U108] JS：随机整数
来源：http://dali.dashuyun.cn/Article/details/gt2tgehgmxy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2erwnfcem.html

[U109] JS：数组分组
来源：http://dali.ppjwa.cn/Article/details/gt2fzvyvcpl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2khatmzaf.html

[U110] JS：数组分块
来源：http://dali.pengpengdd.cyou/Article/details/gt2armdxfow.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gt2vymqqlbq.html

[U111] JS：对象转 Map
来源：http://dali.hfpthk.cn/Article/details/gt2mgwhvdhg.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gt2dpkiviiv.html

[U112] JS：字符串补位
来源：http://dali.nanxuanxn.top/Article/details/gt2rjiikraq.html

"7".padStart(3, "0")
来源：http://dali.fzhhl.top/Article/details/gt2smesdbys.html

[U113] JS：正则替换全部
来源：http://dali.xuanzx.com/Article/details/gt2ampoisyu.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gt2jppbqnya.html

[U114] JS：JSON 深比较
来源：http://dali.yuxming.cn/Article/details/gt2ueemqwxd.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.wangdashe.top/Article/details/gt2cbcuoevt.html

[U115] JS：生成 UUID
来源：http://dali.haohaochexian.top/Article/details/gt2vrsykbcu.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gt2rxfosjli.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjoeieip.html

/** @param {string} name */ function f(name) {}
来源：http://dali.snrcjt.cn/Article/details/gt2kiditmyi.html

[U117] JS：单元测试
来源：http://dali.hfpthk.cn/Article/details/gt2kzaxzqkh.html

npm i -D vitest;  npx vitest
来源：http://dali.aizwys.cn/Article/details/gt2fcikyiei.html

[U118] JS：开发服务器
来源：http://dali.zhiwuduotai.top/Article/details/gt2obqiumoo.html

npm i -D vite;  npx vite
来源：http://dali.tianlin.xyz/Article/details/gt2jrcmnxut.html

[U119] JS：生产构建
来源：http://dali.sweek.top/Article/details/gt2becwjjtt.html

npx vite build
来源：http://dali.ehwqpu.com/Article/details/gt2cdtolmuy.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shuidangran.top/Article/details/gt2dwgvehpz.html

import.meta.env.VITE_API_URL
来源：http://dali.chenjidiqi.icu/Article/details/gt2lbvcvvre.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2jlheiugv.html

统计汇总
来源：http://dali.yvedp.cn/Article/details/gt2yddbkcrl.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2klqewtne.html

按语言统计（条）：
来源：http://dali.vqdsnc.cn/Article/details/gt2kfrpiezv.html

Python ......... 252
来源：http://dali.wangdashe.top/Article/details/gt2rthbabpu.html

PHP ............ 252
来源：http://dali.zhiwuduotai.top/Article/details/gt2fnfvsegb.html

JavaScript ..... 252
来源：http://dali.smart0.xyz/Article/details/gt2vlsdtecz.html

TypeScript ..... 212
来源：http://dali.ppjwa.cn/Article/details/gt2aviaznne.html

Java ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gt2edbsyrax.html

Go ............. 212
来源：http://dali.mhx1999.top/Article/details/gt2lukvsizp.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gt2ywsezvgu.html

C# ............. 212
来源：http://dali.ybcxt.top/Article/details/gt2dachxeif.html

C .............. 30
来源：http://dali.ybcxt.top/Article/details/gt2mchnarfc.html

C++ ............ 30
来源：http://dali.316326.xyz/Article/details/gt2zmlaszxg.html

SQL ............ 90
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cnwqgeje.html

Bash ........... 80
来源：http://dali.daria6918.cn/Article/details/gt2toifhfve.html

Kotlin ......... 15
来源：http://dali.yvedp.cn/Article/details/gt2ngwnrfcx.html

Swift .......... 15
来源：http://dali.chenzaomai.com/Article/details/gt2piupovgq.html

Lua ............ 10
来源：http://dali.yonumen.top/Article/details/gt2roucqmng.html

Perl ........... 10
来源：http://dali.gzhubu.top/Article/details/gt2rvxjdixa.html

Scala .......... 10
来源：http://dali.hammf.cn/Article/details/gt2lyxfjjnz.html

------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gt2kjmpiplc.html

合计 ........... 2106 条
来源：http://dali.jyoumei.cn/Article/details/gt2aojmeftf.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gt2oenuxkpr.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.316326.xyz/Article/details/gt2zexxpvip.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gt2pxzadtom.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2qulfhfqi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gt2kpjjkega.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ppjwa.cn/Article/details/gt2wtxjipsj.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gt2pafysdvi.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenzaomai.com/Article/details/gt2tlzjjvpg.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.wangdashe.top/Article/details/gt2lwaudwti.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.cqqwz.cn/Article/details/gt2dpmvppwt.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gobpkxrb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.c1oappe.top/Article/details/gt2xfxprfit.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ydzc1.top/Article/details/gt2mwipqlhy.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hnqzz.top/Article/details/gt2lbfducgu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gt2cpbpkcke.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.wangdashe.top/Article/details/gt2uqpzdfbs.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.ivvv.top/Article/details/gt2duuuchyo.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gt2byctfpdp.html

R Bash 专题                             80
来源：http://dali.cdnleiting.top/Article/details/gt2xuyaiqvf.html

S C / C++ 专题                          60
来源：http://dali.quarkkingdee.top/Article/details/gt2cnxxipaq.html

T 其他语言补充                          60
来源：http://dali.chenjidiqi.icu/Article/details/gt2wklvdzbi.html

U 高频实用片段                         120
来源：http://dali.cqqwz.cn/Article/details/gt2gnroohmd.html

------------------------------------
来源：http://dali.xziqi.cn/Article/details/gt2lyoxavru.html

合计                                  2106 条
来源：http://dali.nanxuanxn.top/Article/details/gt2tlwfhhcb.html

--------------------------------------------------------------------------------
来源：http://dali.jinqigfzy.top/Article/details/gt2hynubjuh.html

使用提醒
来源：http://dali.chenjidiqi.icu/Article/details/gt2lujpulte.html

--------------------------------------------------------------------------------
来源：http://dali.cheryme.top/Article/details/gt2zlkpvtba.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.xylfe.cn/Article/details/gt2aqmxfihm.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.tianlin.xyz/Article/details/gt2tffayijo.html


<!-- 参考信息 -->