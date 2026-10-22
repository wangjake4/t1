代发 wailian999

[U01] Py：创建虚拟环境
来源：http://dali.daxiang520.top/Article/details/gt2cdwohnyg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yangfankeji.com/Article/details/gt2urtyweyl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gt2cxierumu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gt2wkmsbgjy.html

[U03] Py：加载 .env 配置
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cyttbyec.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.nanxuanxn.top/Article/details/gt2luplxpec.html

[U04] Py：变量调试打印
来源：http://dali.zhongyouzk.top/Article/details/gt2wvpknfwk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.tian-w.cn/Article/details/gt2lfcamizv.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gt2ylabdtro.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gt2ohxynwyo.html

[U06] Py：合并两个字典
来源：http://dali.gaohongyu789.top/Article/details/gt2dbflqyss.html

{**a, **b}
来源：http://dali.cheryme.top/Article/details/gt2zctreyuk.html

[U07] Py：反转字典键值
来源：http://dali.vqdsnc.cn/Article/details/gt2hrrnhojb.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lxdckbxf.html

[U08] Py：展平二维列表
来源：http://dali.svipenyu.cn/Article/details/gt2gqzdhwid.html

[y for x in nested for y in x]
来源：http://dali.vqdsnc.cn/Article/details/gt2oiwbtsej.html

[U09] Py：字典取最大值的键
来源：http://dali.birdmap.top/Article/details/gt2ojtbmnoh.html

max(d, key=d.get)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ieoanujl.html

[U10] Py：按值排序字典
来源：http://dali.cucudq.cn/Article/details/gt2axojuruy.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.gotoacloud.top/Article/details/gt2giamqckv.html

[U11] Py：生成器表达式
来源：http://dali.aizwys.cn/Article/details/gt2nloysijs.html

(x * 2 for x in arr)
来源：http://dali.zycfv.cn/Article/details/gt2ausdlkdm.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.iojbl.cn/Article/details/gt2atkpowzj.html

Counter(arr).most_common(3)
来源：http://dali.haohaochexian.top/Article/details/gt2hkbsgnyv.html

[U13] Py：固定长度队列
来源：http://dali.cdnleiting.top/Article/details/gt2nxrdrsas.html

deque(maxlen=10)
来源：http://dali.bjfxy.top/Article/details/gt2jhmigzat.html

[U14] Py：分组收集到列表
来源：http://dali.hnxiangtu.top/Article/details/gt2nkjdffiu.html

defaultdict(list)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkcjgkjf.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rsbrnpyz.html

t = time.perf_counter()
来源：http://dali.shuidangran.top/Article/details/gt2fqcrvumm.html

[U16] Py：命令行参数解析
来源：http://dali.daxiang520.top/Article/details/gt2acqehuai.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.kuanghao11.cn/Article/details/gt2yelqwque.html

[U17] Py：初始化日志
来源：http://dali.wangshuangyany.cn/Article/details/gt2ouiyrxfd.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.guannengcc.top/Article/details/gt2vxqrxsco.html

[U18] Py：预编译正则
来源：http://dali.hnqzz.top/Article/details/gt2kkjldrhh.html

pat = re.compile(r"\d+")
来源：http://dali.yonumen.top/Article/details/gt2gbykpdby.html

[U19] Py：正则替换带回调
来源：http://dali.jyoumei.cn/Article/details/gt2peqganwh.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.meibo888.top/Article/details/gt2iwrumkav.html

[U20] Py：缓存函数结果
来源：http://dali.ivvv.top/Article/details/gt2vqkyentj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.pycfn.com/Article/details/gt2zyqqzkuc.html

[U21] Py：自定义上下文管理器
来源：http://dali.jianghu66.top/Article/details/gt2ntshznij.html

@contextlib.contextmanager
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cowimmgl.html

[U22] Py：矩阵转置
来源：http://dali.pengpengdd.cyou/Article/details/gt2ygdsnizd.html

list(zip(*m))
来源：http://dali.jlsjyb.cn/Article/details/gt2dcdyoqpq.html

[U23] Py：分块读取大文件
来源：http://dali.xylfe.cn/Article/details/gt2shnrmdzb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gt2psoiiujo.html

[U24] Py：路径操作
来源：http://dali.yj20258888.top/Article/details/gt2slzcwhdv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.daria6918.cn/Article/details/gt2lewcwbzx.html

[U25] Py：CSV 按字典读
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajxxjpkr.html

csv.DictReader(f)
来源：http://dali.xuanzx.com/Article/details/gt2loiaebzt.html

[U26] Py：并发下载
来源：http://dali.xuanzx.com/Article/details/gt2aztzrcfx.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.gotoacloud.top/Article/details/gt2qwtjoipu.html

[U27] Py：异步 HTTP
来源：http://dali.gaohongyu789.top/Article/details/gt2vakzsdnw.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yuanzhike.top/Article/details/gt2hbkqqgpx.html

[U28] Py：类型别名
来源：http://dali.havefunace.top/Article/details/gt2xnzyrwbc.html

UserId = int
来源：http://dali.chenjidiqi.icu/Article/details/gt2lcfhrrqd.html

[U29] Py：属性校验
来源：http://dali.gogol.net.cn/Article/details/gt2tzjkezdk.html

@property 与 @x.setter 配合
来源：http://dali.xylfe.cn/Article/details/gt2qizqfwhc.html

[U30] Py：数据类
来源：http://dali.nanxuanxn.top/Article/details/gt2ddjrzgjv.html

@dataclass(slots=True)
来源：http://dali.cdnleiting.top/Article/details/gt2vfcxaowm.html

[U31] Py：单测
来源：http://dali.chenjidiqi.icu/Article/details/gt2qiuimrhe.html

python -m pytest -q
来源：http://dali.pycfn.com/Article/details/gt2eigbhcfk.html

[U32] Py：代码格式化
来源：http://dali.hnqzz.top/Article/details/gt2xphuzulo.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gt2cbfgblbb.html

[U33] Py：打包发布
来源：http://dali.haohaochexian.top/Article/details/gt2nzuysedw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.yongpay.top/Article/details/gt2adimvvlz.html

[U34] Py：判断编码
来源：http://dali.zhiwuduotai.top/Article/details/gt2nycnlcud.html

chardet.detect(raw)
来源：http://dali.kuanghao11.cn/Article/details/gt2paolnlxb.html

[U35] Py：发送邮件
来源：http://dali.xuetiantiany.cn/Article/details/gt2cekxokwk.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.jianghu66.top/Article/details/gt2waepttcz.html

[U36] Py：定时任务
来源：http://dali.andypj.xyz/Article/details/gt2sjbtfptg.html

schedule.every(10).minutes.do(job)
来源：http://dali.snrcjt.cn/Article/details/gt2aossliyg.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gt2srjogmyu.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.zdqjudy.top/Article/details/gt2hhxhisvd.html

[U38] Py：获取脚本所在目录
来源：http://dali.aizwys.cn/Article/details/gt2pygylfta.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gt2wudjwvji.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhengqikj.top/Article/details/gt2otfvpvir.html

sys.stdout.isatty()
来源：http://dali.9152youxi.cn/Article/details/gt2fiwzsmta.html

[U40] Py：打印到标准错误
来源：http://dali.meibo888.top/Article/details/gt2tcesjhju.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2kipsfyzz.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.jlsjyb.cn/Article/details/gt2mceqpdme.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.zhixingplan.top/Article/details/gt2xsbsiqhe.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gt2gzxxjqbm.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj20258.top/Article/details/gt2fjausfxc.html

[U43] PHP：声明命名空间
来源：http://dali.shuidangran.top/Article/details/gt2zdcmbusz.html

namespace App\Http;
来源：http://dali.daxiang520.top/Article/details/gt2leznnlnq.html

[U44] PHP：开启严格类型
来源：http://dali.yj202588.top/Article/details/gt2xiqcfjvm.html

declare(strict_types=1);
来源：http://dali.haohaochexian.top/Article/details/gt2ntfjhiob.html

[U45] PHP：类型声明与返回类型
来源：http://dali.hfpthk.cn/Article/details/gt2algyctgm.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2ldkcstjc.html

[U46] PHP：可空类型
来源：http://dali.yj202588.top/Article/details/gt2xpxstlja.html

?string $name = null
来源：http://dali.yongpay.top/Article/details/gt2rurgtnnc.html

[U47] PHP：联合类型
来源：http://dali.kuanghao11.cn/Article/details/gt2bulcmbmr.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gt2sylvkbgq.html

[U48] PHP：纯枚举
来源：http://dali.cqqwz.cn/Article/details/gt2mciawzsf.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uadpslxn.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gt2pkaekdqj.html

public readonly string $name
来源：http://dali.snrcjt.cn/Article/details/gt2mtxjxmpc.html

[U50] PHP：构造器属性提升
来源：http://dali.yvedp.cn/Article/details/gt2rslrtpwl.html

public function __construct(private int $id) {}
来源：http://dali.sweek.top/Article/details/gt2huhfygye.html

[U51] PHP：数组解构
来源：http://dali.pengpengdd.cyou/Article/details/gt2ahdolsnd.html

[$a, $b] = $arr;
来源：http://dali.xinyue.icu/Article/details/gt2sccacfzn.html

[U52] PHP：箭头函数
来源：http://dali.aizwys.cn/Article/details/gt2bsqdacmw.html

$double = fn($x) => $x * 2;
来源：http://dali.yueranfly.top/Article/details/gt2ncmxereo.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gt2gqkitulm.html

$v = $a ?? $b ?? "default";
来源：http://dali.hysaishi.cn/Article/details/gt2ylrqtggj.html

[U54] PHP：空安全调用
来源：http://dali.pycfn.com/Article/details/gt2owegvhlv.html

$obj?->method()
来源：http://dali.316326.xyz/Article/details/gt2qrrntjgb.html

[U55] PHP：match 表达式
来源：http://dali.cheryme.top/Article/details/gt2yqkcxnzq.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.sweek.top/Article/details/gt2ybiczmmp.html

[U56] PHP：命名参数
来源：http://dali.zhengqikj.top/Article/details/gt2tiyvfavj.html

f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gt2iqperakg.html

[U57] PHP：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pszuwgoz.html

"值: {$a}"
来源：http://dali.chenlongwang.top/Article/details/gt2hnavlhgk.html

[U58] PHP：数组三件套
来源：http://dali.nanxinkj.top/Article/details/gt2chxbeddf.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yj20258.top/Article/details/gt2wjjzuhlo.html

[U59] PHP：自定义排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2vzcikfue.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.aibaodan.cn/Article/details/gt2ebyjfbaw.html

[U60] PHP：JSON 编解码
来源：http://dali.kuanghao11.cn/Article/details/gt2bwofzzjc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hnqzz.top/Article/details/gt2wmeozujy.html

[U61] PHP：正则
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kuqkjrzz.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.wangdashe.top/Article/details/gt2gtbjglah.html

[U62] PHP：日期对象
来源：http://dali.zycfv.cn/Article/details/gt2vwzczuwh.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2unypvfns.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gt2adpwsbwa.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.nanxuanxn.top/Article/details/gt2uudvljky.html

[U64] PHP：目录遍历
来源：http://dali.svipenyu.cn/Article/details/gt2idzorqhc.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ckqirozd.html

[U65] PHP：会话
来源：http://dali.chenzaomai.com/Article/details/gt2rkohhlmc.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tkdvcqnd.html

[U66] PHP：设置 Cookie
来源：http://dali.zhiwuduotai.top/Article/details/gt2eriadwai.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lvyaeuil.html

[U67] PHP：处理文件上传
来源：http://dali.tianlin.xyz/Article/details/gt2qcirrepu.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gogol.net.cn/Article/details/gt2kktfquwb.html

[U68] PHP：PDO 连接
来源：http://dali.jianghu66.top/Article/details/gt2tmahyexp.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daria6918.cn/Article/details/gt2mpnzsuab.html

[U69] PHP：PDO 预处理
来源：http://dali.zhoulong.xyz/Article/details/gt2oibhikji.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sweek.top/Article/details/gt2sclityxq.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gt2qdqzslmn.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.zhixingplan.top/Article/details/gt2wkdlfwip.html

[U71] PHP：抛出异常
来源：http://dali.yj202588.top/Article/details/gt2bscaqkpr.html

throw new RuntimeException("失败", 500);
来源：http://dali.jinqigufen.top/Article/details/gt2vcaprhoq.html

[U72] PHP：写错误日志
来源：http://dali.jlsjyb.cn/Article/details/gt2atzcatov.html

error_log("失败: " . $e->getMessage());
来源：http://dali.sxryk.cn/Article/details/gt2tduuiylt.html

[U73] PHP：读取 ini 配置
来源：http://dali.aizwys.cn/Article/details/gt2imwdcamw.html

parse_ini_file("config.ini", true)
来源：http://dali.yvedp.cn/Article/details/gt2cbhcmish.html

[U74] PHP：读取环境变量
来源：http://dali.yj20258.top/Article/details/gt2hbgrzwxk.html

getenv("APP_ENV") ?: "production"
来源：http://dali.tanke756.top/Article/details/gt2krfhowrl.html

[U75] PHP：依赖注入
来源：http://dali.tanke756.top/Article/details/gt2txrmtyws.html

composer require psr/container
来源：http://dali.guannengcc.top/Article/details/gt2pmqeznul.html

[U76] PHP：简单路由
来源：http://dali.jinqigufen.top/Article/details/gt2eqwblyfp.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yj202588.top/Article/details/gt2yepwjjbl.html

[U77] PHP：模板渲染
来源：http://dali.smart0.xyz/Article/details/gt2ictnokaf.html

composer require twig/twig
来源：http://dali.havefunace.top/Article/details/gt2rudjgrba.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2cthkwvur.html

composer require --dev phpunit/phpunit
来源：http://dali.ehwqpu.com/Article/details/gt2ibessvrp.html

[U79] PHP：静态分析
来源：http://dali.daxiang520.top/Article/details/gt2qmqcfnmi.html

composer require --dev phpstan/phpstan
来源：http://dali.guowangkeji.top/Article/details/gt2ohvisgsh.html

[U80] PHP：代码规范修复
来源：http://dali.yj20258888.top/Article/details/gt2iohefqun.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gt2yqkgqthj.html

[U81] JS：初始化项目
来源：http://dali.yongpay.top/Article/details/gt2exfbehqb.html

npm init -y;  npm i express
来源：http://dali.xylfe.cn/Article/details/gt2btwytawm.html

[U82] JS：package.json 脚本
来源：http://dali.kuanghao11.cn/Article/details/gt2ojjvireg.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yueranfly.top/Article/details/gt2ljgbzprk.html

[U83] JS：ES Module 导入导出
来源：http://dali.svipenyu.cn/Article/details/gt2ftlujboz.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gt2xjahnkpo.html

[U84] JS：CommonJS 写法
来源：http://dali.svipenyu.cn/Article/details/gt2cxvtppxn.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cashguo.top/Article/details/gt2aecscgyb.html

[U85] JS：可选链
来源：http://dali.sufxvd.cn/Article/details/gt2usoalpty.html

a?.b?.c
来源：http://dali.tianlin.xyz/Article/details/gt2mlvzbpvs.html

[U86] JS：空值合并
来源：http://dali.havefunace.top/Article/details/gt2hznhekpj.html

a ?? b
来源：http://dali.aizwys.cn/Article/details/gt2mnoeylwa.html

[U87] JS：解构默认值
来源：http://dali.ybcxt.top/Article/details/gt2aucmcsia.html

const { a = 1, b = 2 } = obj;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2japbgpnf.html

[U88] JS：对象展开合并
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wgvipccq.html

{ ...a, ...b }
来源：http://dali.jyoumei.cn/Article/details/gt2iccyxjav.html

[U89] JS：数组去重
来源：http://dali.hfpthk.cn/Article/details/gt2hrokluth.html

[...new Set(arr)]
来源：http://dali.jianghu66.top/Article/details/gt2qqbaeibp.html

[U90] JS：数字数组排序
来源：http://dali.hywenlv.cn/Article/details/gt2jwgbgzko.html

[...arr].sort((a, b) => a - b)
来源：http://dali.wangshuangyany.cn/Article/details/gt2vxgwdfdd.html

[U91] JS：对象键值遍历
来源：http://dali.tian-w.cn/Article/details/gt2loiibrbz.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.meibo888.top/Article/details/gt2lrrfoyss.html

[U92] JS：深拷贝
来源：http://dali.316326.xyz/Article/details/gt2ctzwhjfm.html

structuredClone(obj)
来源：http://dali.svipenyu.cn/Article/details/gt2qstymiye.html

[U93] JS：模板字符串
来源：http://dali.zhoulong.xyz/Article/details/gt2tzgdmybf.html

`共 ${n} 条`
来源：http://dali.hammf.cn/Article/details/gt2agbtojcd.html

[U94] JS：箭头函数
来源：http://dali.pycfn.com/Article/details/gt2tvhwqdvk.html

const double = x => x * 2;
来源：http://dali.wangdashe.top/Article/details/gt2gldyjsij.html

[U95] JS：Promise 包装
来源：http://dali.snrcjt.cn/Article/details/gt2ysebyddg.html

new Promise((resolve, reject) => {})
来源：http://dali.nwbrower.top/Article/details/gt2bfousstk.html

[U96] JS：async/await 与异常
来源：http://dali.yvedp.cn/Article/details/gt2mpctoddh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.havefunace.top/Article/details/gt2xdbmuqtc.html

[U97] JS：并发请求
来源：http://dali.zhiwuduotai.top/Article/details/gt2oecgutiv.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qnvtjbhw.html

[U98] JS：fetch 带 JSON
来源：http://dali.yuanzhike.top/Article/details/gt2mnqzarjx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jlsjyb.cn/Article/details/gt2wgihzisb.html

[U99] JS：事件监听
来源：http://dali.ehwqpu.com/Article/details/gt2bkskazfg.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vvitkzqm.html

[U100] JS：DOM 查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2biltwhew.html

document.querySelector(".item")
来源：http://dali.wangdashe.top/Article/details/gt2ucaxxbpy.html

[U101] JS：classList 操作
来源：http://dali.jianghu66.top/Article/details/gt2mqwucjiq.html

el.classList.toggle("active")
来源：http://dali.chenlongwang.top/Article/details/gt2lbhaynpr.html

[U102] JS：本地存储
来源：http://dali.mhx1999.top/Article/details/gt2ptzewuqa.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yangfankeji.com/Article/details/gt2bommwkkl.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2wtfmabsy.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xziqi.cn/Article/details/gt2qepkfcif.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gt2fbbapwae.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.wangshuangyany.cn/Article/details/gt2miiipqdg.html

[U105] JS：节流
来源：http://dali.zhengqikj.top/Article/details/gt2sqxsgvbd.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2dwkqxody.html

[U106] JS：日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2uwtmxkyw.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shzxlz.cn/Article/details/gt2zcwynshm.html

[U107] JS：数字千分位
来源：http://dali.iojbl.cn/Article/details/gt2cutbmrzj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2gxrhgxzz.html

[U108] JS：随机整数
来源：http://dali.wangdashe.top/Article/details/gt2dewidywz.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hzmryqmh.html

[U109] JS：数组分组
来源：http://dali.shzxlz.cn/Article/details/gt2mptlvsxi.html

Object.groupBy(arr, x => x.type)
来源：http://dali.redwolf501.top/Article/details/gt2ksnwjknt.html

[U110] JS：数组分块
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zvvbjyrs.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gt2iphvivst.html

[U111] JS：对象转 Map
来源：http://dali.nanxuanxn.top/Article/details/gt2ancscggo.html

new Map(Object.entries(obj))
来源：http://dali.iojbl.cn/Article/details/gt2ewkiihdw.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangtech.top/Article/details/gt2knqruoql.html

"7".padStart(3, "0")
来源：http://dali.sysykeji.top/Article/details/gt2bpgwdixi.html

[U113] JS：正则替换全部
来源：http://dali.kuanghao11.cn/Article/details/gt2oxtsgdst.html

s.replaceAll("a", "b")
来源：http://dali.yanxiufei.cn/Article/details/gt2yxqnvhtn.html

[U114] JS：JSON 深比较
来源：http://dali.jyoumei.cn/Article/details/gt2jbzjetwv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.hywenlv.cn/Article/details/gt2ycsodrsq.html

[U115] JS：生成 UUID
来源：http://dali.yvedp.cn/Article/details/gt2julwnzse.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2jcvpuwht.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.fengsongda.top/Article/details/gt2juxxqbat.html

/** @param {string} name */ function f(name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dznhrfra.html

[U117] JS：单元测试
来源：http://dali.yanxiufei.cn/Article/details/gt2crlvvarn.html

npm i -D vitest;  npx vitest
来源：http://dali.mhx1999.top/Article/details/gt2hvadhcsq.html

[U118] JS：开发服务器
来源：http://dali.c1oappe.top/Article/details/gt2fwnskwoo.html

npm i -D vite;  npx vite
来源：http://dali.hammf.cn/Article/details/gt2etgkruka.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2kflongmv.html

npx vite build
来源：http://dali.bjfxy.top/Article/details/gt2bugbrlyh.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.yj20258.top/Article/details/gt2gbatmyev.html

import.meta.env.VITE_API_URL
来源：http://dali.cqqwz.cn/Article/details/gt2utgziuor.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2vnzzgmln.html

统计汇总
来源：http://dali.svipenyu.cn/Article/details/gt2fjnqkxel.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2tojbzlbf.html

按语言统计（条）：
来源：http://dali.havefunace.top/Article/details/gt2rryntysh.html

Python ......... 252
来源：http://dali.chenzaomai.com/Article/details/gt2braumbey.html

PHP ............ 252
来源：http://dali.cashguo.top/Article/details/gt2gxmrawfh.html

JavaScript ..... 252
来源：http://dali.tianlin.xyz/Article/details/gt2xlbabosu.html

TypeScript ..... 212
来源：http://dali.chenjidiqi.icu/Article/details/gt2qfiiezhy.html

Java ........... 212
来源：http://dali.haohaochexian.top/Article/details/gt2dzjaiwej.html

Go ............. 212
来源：http://dali.zhongyouzk.top/Article/details/gt2ejfuaaty.html

Ruby ........... 212
来源：http://dali.jianghu66.top/Article/details/gt2ibqjvyhs.html

C# ............. 212
来源：http://dali.cheryme.top/Article/details/gt2wqvhpdcq.html

C .............. 30
来源：http://dali.nanxinkj.top/Article/details/gt2ozrahhbu.html

C++ ............ 30
来源：http://dali.xuanzx.com/Article/details/gt2gcipqhun.html

SQL ............ 90
来源：http://dali.sufxvd.cn/Article/details/gt2glfllhvi.html

Bash ........... 80
来源：http://dali.zycfv.cn/Article/details/gt2hgmoxrtc.html

Kotlin ......... 15
来源：http://dali.smart0.xyz/Article/details/gt2jqxwozat.html

Swift .......... 15
来源：http://dali.nwbrower.top/Article/details/gt2puchrjmw.html

Lua ............ 10
来源：http://dali.yvedp.cn/Article/details/gt2nyivpcxd.html

Perl ........... 10
来源：http://dali.zhengqikj.top/Article/details/gt2wdoztupr.html

Scala .......... 10
来源：http://dali.zycfv.cn/Article/details/gt2bpovtwxv.html

------------------------------------
来源：http://dali.jiagoushi.top/Article/details/gt2wwolqcqw.html

合计 ........... 2106 条
来源：http://dali.ehwqpu.com/Article/details/gt2bhyyuzhi.html

按章节统计：
来源：http://dali.hnqzz.top/Article/details/gt2xtydvyjh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gt2cmaiafau.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.guannengcc.top/Article/details/gt2jvvrltkp.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.svipenyu.cn/Article/details/gt2kgowpkyi.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.shuidangran.top/Article/details/gt2yotiikac.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.zhongyouzk.top/Article/details/gt2aaqklbra.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hammf.cn/Article/details/gt2lcdpivjv.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.nanxinkj.top/Article/details/gt2oomppohy.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hfpthk.cn/Article/details/gt2tspojtuy.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2qxgtdelb.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnqzz.top/Article/details/gt2agkvbzdj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.aibaodan.cn/Article/details/gt2bzskeoen.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.chenlongwang.top/Article/details/gt2cjfmiaeo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.jyoumei.cn/Article/details/gt2dscmpijn.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gt2ouwjwvmz.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.shuidangran.top/Article/details/gt2mpgylvfm.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2usvamxdp.html

Q SQL 专题                              90
来源：http://dali.ehwqpu.com/Article/details/gt2wpzdieam.html

R Bash 专题                             80
来源：http://dali.cheryme.top/Article/details/gt2dynhjczq.html

S C / C++ 专题                          60
来源：http://dali.tian-w.cn/Article/details/gt2gtqukfds.html

T 其他语言补充                          60
来源：http://dali.jiagoushi.top/Article/details/gt2xfvdxzun.html

U 高频实用片段                         120
来源：http://dali.yvedp.cn/Article/details/gt2epupyloc.html

------------------------------------
来源：http://dali.cqqwz.cn/Article/details/gt2mbxhngfy.html

合计                                  2106 条
来源：http://dali.chenzaomai.com/Article/details/gt2hyjdkyah.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2snprcosq.html

使用提醒
来源：http://dali.tian-w.cn/Article/details/gt2qgofsymo.html

--------------------------------------------------------------------------------
来源：http://dali.xuetiantiany.cn/Article/details/gt2zrckdffx.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.chenjidiqi.icu/Article/details/gt2qjlthcuo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.yangfankeji.com/Article/details/gt2uvenezph.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.redwolf501.top/Article/details/gt2ufrqpfhs.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gt2wigkymxu.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.nanxinkj.top/Article/details/gt2evyxwqos.html

—— 文件结束 ——
来源：http://dali.yueranfly.top/Article/details/gt2royfgrqc.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2avedcpne.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.svipenyu.cn/Article/details/gt2kaioalrt.html

Common Programming Examples Cheat Book
来源：http://dali.hywenlv.cn/Article/details/gt2akktwtpq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2ajatyhml.html


<!-- 参考信息 -->