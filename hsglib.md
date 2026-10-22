代发 wailian999

val a = 1;  var b = 2
来源：http://dali.hfpthk.cn/Article/details/gt2uyjqjruy.html

[T53] Scala：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ojbzbpkv.html

s"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gt2bkuiyjlk.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gt2hphnsvvm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yangfankeji.com/Article/details/gt2fzqhzszw.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2kdtkiuyy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2sxljmqkc.html

[T56] Scala：样例类
来源：http://dali.havefunace.top/Article/details/gt2ijbxfnbt.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gt2asrbcxam.html

[T57] Scala：模式匹配
来源：http://dali.ydzc1.top/Article/details/gt2aqakseuj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.316326.xyz/Article/details/gt2yadeyfpe.html

[T58] Scala：函数定义
来源：http://dali.jlsjyb.cn/Article/details/gt2lqpbnlyo.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gt2oeffgjrp.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gt2qqapgtdu.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gt2kqaydyrp.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gt2xxkmqnhe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.daxiang520.top/Article/details/gt2dmmhvufe.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2dkpzjfuh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gt2kmxharpw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2iezxaoqh.html

[U01] Py：创建虚拟环境
来源：http://dali.tianlin.xyz/Article/details/gt2irxizxgk.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2szmkevsw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.aibaodan.cn/Article/details/gt2jdedlvul.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2qidmiirp.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxuanxn.top/Article/details/gt2vqoxdntk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gt2rdvhhvvb.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gt2iimwjdqs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xvxeezkh.html

[U05] Py：列表去重且保序
来源：http://dali.hfpthk.cn/Article/details/gt2uwzpgdgs.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gt2ljckpqpd.html

[U06] Py：合并两个字典
来源：http://dali.yonumen.top/Article/details/gt2paryiuzj.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gt2wslgexat.html

[U07] Py：反转字典键值
来源：http://dali.wangdashe.top/Article/details/gt2gslgneud.html

{v: k for k, v in d.items()}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvokwxog.html

[U08] Py：展平二维列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cgklrrhx.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gt2evyozwat.html

[U09] Py：字典取最大值的键
来源：http://dali.jlsjyb.cn/Article/details/gt2veyqsfbe.html

max(d, key=d.get)
来源：http://dali.chenjidiqi.icu/Article/details/gt2nylpfxnk.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntombhxg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wbexwyxh.html

[U11] Py：生成器表达式
来源：http://dali.gaohongyu789.top/Article/details/gt2wnojxylx.html

(x * 2 for x in arr)
来源：http://dali.zhixingplan.top/Article/details/gt2aafckdvv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jyoumei.cn/Article/details/gt2fxqxdqls.html

Counter(arr).most_common(3)
来源：http://dali.yj20258.top/Article/details/gt2dgpjzwsy.html

[U13] Py：固定长度队列
来源：http://dali.nwbrower.top/Article/details/gt2dzfsakum.html

deque(maxlen=10)
来源：http://dali.ppjwa.cn/Article/details/gt2gbpnwdlx.html

[U14] Py：分组收集到列表
来源：http://dali.nwbrower.top/Article/details/gt2ubtonzut.html

defaultdict(list)
来源：http://dali.sysykeji.top/Article/details/gt2wmmzwzcv.html

[U15] Py：高精度计时
来源：http://dali.nanxuanxn.top/Article/details/gt2nppdjmkl.html

t = time.perf_counter()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ydvxrham.html

[U16] Py：命令行参数解析
来源：http://dali.iojbl.cn/Article/details/gt2zzofsfzp.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cdnleiting.top/Article/details/gt2vsdqshww.html

[U17] Py：初始化日志
来源：http://dali.tanke756.top/Article/details/gt2gczysodh.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.sweek.top/Article/details/gt2vlufbvun.html

[U18] Py：预编译正则
来源：http://dali.ydzc1.top/Article/details/gt2fkoahgbx.html

pat = re.compile(r"\d+")
来源：http://dali.birdmap.top/Article/details/gt2lrazxbdi.html

[U19] Py：正则替换带回调
来源：http://dali.shzxlz.cn/Article/details/gt2oayxhugo.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.sysykeji.top/Article/details/gt2mspvpteq.html

[U20] Py：缓存函数结果
来源：http://dali.gotoacloud.top/Article/details/gt2nyfifuxf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.wangdashe.top/Article/details/gt2ejnpmgbx.html

[U21] Py：自定义上下文管理器
来源：http://dali.fengsongda.top/Article/details/gt2jjfvfwom.html

@contextlib.contextmanager
来源：http://dali.nanxinkj.top/Article/details/gt2vtqurfgc.html

[U22] Py：矩阵转置
来源：http://dali.hywenlv.cn/Article/details/gt2pmtawfhk.html

list(zip(*m))
来源：http://dali.yvedp.cn/Article/details/gt2meogwcpi.html

[U23] Py：分块读取大文件
来源：http://dali.zhengqikj.top/Article/details/gt2ftzqgmfb.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.ydzc1.top/Article/details/gt2hmqbqmkz.html

[U24] Py：路径操作
来源：http://dali.ehwqpu.com/Article/details/gt2mxtvcaud.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.haohaochexian.top/Article/details/gt2tjfrrtme.html

[U25] Py：CSV 按字典读
来源：http://dali.yonumen.top/Article/details/gt2hlxnacsd.html

csv.DictReader(f)
来源：http://dali.birdmap.top/Article/details/gt2yrexsglf.html

[U26] Py：并发下载
来源：http://dali.dianchejie.cn/Article/details/gt2adtbvcrs.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pycfn.com/Article/details/gt2gwmsjunu.html

[U27] Py：异步 HTTP
来源：http://dali.cqqwz.cn/Article/details/gt2elgptoqy.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.jianghu66.top/Article/details/gt2srbgerjh.html

[U28] Py：类型别名
来源：http://dali.cdnleiting.top/Article/details/gt2vpgeiedd.html

UserId = int
来源：http://dali.tanke756.top/Article/details/gt2fcchsnvm.html

[U29] Py：属性校验
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uumjkswa.html

@property 与 @x.setter 配合
来源：http://dali.iojbl.cn/Article/details/gt2qqkhsexz.html

[U30] Py：数据类
来源：http://dali.nwbrower.top/Article/details/gt2xmwlgjdi.html

@dataclass(slots=True)
来源：http://dali.9152youxi.cn/Article/details/gt2hakcznso.html

[U31] Py：单测
来源：http://dali.shuidangran.top/Article/details/gt2hcwhuxqo.html

python -m pytest -q
来源：http://dali.fengsongda.top/Article/details/gt2kdrpsgmn.html

[U32] Py：代码格式化
来源：http://dali.nanxuanxn.top/Article/details/gt2mgtyqgnp.html

ruff format . && ruff check --fix .
来源：http://dali.yongpay.top/Article/details/gt2vsnxcrqg.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gt2gokbilvx.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.redwolf501.top/Article/details/gt2nzdjfiac.html

[U34] Py：判断编码
来源：http://dali.xinyue.icu/Article/details/gt2sdgslyqs.html

chardet.detect(raw)
来源：http://dali.aibaodan.cn/Article/details/gt2btzejhxi.html

[U35] Py：发送邮件
来源：http://dali.tanke756.top/Article/details/gt2jytkbqel.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.redwolf501.top/Article/details/gt2trqinaln.html

[U36] Py：定时任务
来源：http://dali.c1oappe.top/Article/details/gt2sdrrrvmp.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gt2exisaheq.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gt2vwgwuuza.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.cqqwz.cn/Article/details/gt2tijfjwzw.html

[U38] Py：获取脚本所在目录
来源：http://dali.fzhhl.top/Article/details/gt2tuovgeah.html

Path(__file__).resolve().parent
来源：http://dali.daxiang520.top/Article/details/gt2ficpshhv.html

[U39] Py：判断是否在交互环境
来源：http://dali.feifeiyinyue.top/Article/details/gt2emyfwiyn.html

sys.stdout.isatty()
来源：http://dali.cdnleiting.top/Article/details/gt2ltimqwbb.html

[U40] Py：打印到标准错误
来源：http://dali.ivvv.top/Article/details/gt2oztsimvu.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gt2qkobonsy.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zycfv.cn/Article/details/gt2cjmotftr.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gt2emanpqac.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.ydzc1.top/Article/details/gt2ouwnzmnu.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ptjoegdt.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gt2gtxontnp.html

namespace App\Http;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ddlacrgy.html

[U44] PHP：开启严格类型
来源：http://dali.daria6918.cn/Article/details/gt2kdieqhiv.html

declare(strict_types=1);
来源：http://dali.shangyingyoupin.top/Article/details/gt2giyceceb.html

[U45] PHP：类型声明与返回类型
来源：http://dali.zhiwuduotai.top/Article/details/gt2qkoihsdj.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2gbmtqrko.html

[U46] PHP：可空类型
来源：http://dali.yuanzhike.top/Article/details/gt2prhuuzde.html

?string $name = null
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2exajdsoi.html

[U47] PHP：联合类型
来源：http://dali.yongpay.top/Article/details/gt2uuxdheld.html

int|string $id
来源：http://dali.chenjidiqi.icu/Article/details/gt2flfmoife.html

[U48] PHP：纯枚举
来源：http://dali.hnqzz.top/Article/details/gt2vwusbkni.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.sysykeji.top/Article/details/gt2ktpxvlem.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehvfamhv.html

public readonly string $name
来源：http://dali.havefunace.top/Article/details/gt2tvrgvkro.html

[U50] PHP：构造器属性提升
来源：http://dali.hnxiangtu.top/Article/details/gt2miynrcyi.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2jseunmbr.html

[U51] PHP：数组解构
来源：http://dali.xziqi.cn/Article/details/gt2tujlxwyj.html

[$a, $b] = $arr;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qfrfjjbn.html

[U52] PHP：箭头函数
来源：http://dali.ivvv.top/Article/details/gt2zkchujoj.html

$double = fn($x) => $x * 2;
来源：http://dali.shangyingyoupin.top/Article/details/gt2gkxjaqga.html

[U53] PHP：空合并运算符
来源：http://dali.gaohongyu789.top/Article/details/gt2pftooztx.html

$v = $a ?? $b ?? "default";
来源：http://dali.ybcxt.top/Article/details/gt2zybzgsot.html

[U54] PHP：空安全调用
来源：http://dali.jyoumei.cn/Article/details/gt2zkkalakr.html

$obj?->method()
来源：http://dali.9152youxi.cn/Article/details/gt2bcdxuapy.html

[U55] PHP：match 表达式
来源：http://dali.zhengqikj.top/Article/details/gt2uttipshi.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gt2tzjywgpy.html

[U56] PHP：命名参数
来源：http://dali.mhx1999.top/Article/details/gt2cirhqsnv.html

f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2edanmctp.html

[U57] PHP：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gt2ujvfaawx.html

"值: {$a}"
来源：http://dali.quarkkingdee.top/Article/details/gt2uvzkxjzf.html

[U58] PHP：数组三件套
来源：http://dali.dashuyun.cn/Article/details/gt2vqioszjp.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.bjfxy.top/Article/details/gt2dgecnuyx.html

[U59] PHP：自定义排序
来源：http://dali.mhx1999.top/Article/details/gt2mnczsixz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.316326.xyz/Article/details/gt2cefmfkor.html

[U60] PHP：JSON 编解码
来源：http://dali.yueranfly.top/Article/details/gt2ezhkajfd.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zycfv.cn/Article/details/gt2horcujir.html

[U61] PHP：正则
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cywtomqd.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tqvmyeou.html

[U62] PHP：日期对象
来源：http://dali.xinyue.icu/Article/details/gt2slvxmrqj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ppjwa.cn/Article/details/gt2tmltqtgw.html

[U63] PHP：文件读写
来源：http://dali.yj20258.top/Article/details/gt2arbvhgzr.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.aibaodan.cn/Article/details/gt2ylnitari.html

[U64] PHP：目录遍历
来源：http://dali.c1oappe.top/Article/details/gt2bodshynn.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2biuwfxfo.html

[U65] PHP：会话
来源：http://dali.ydzc1.top/Article/details/gt2iglplasn.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yongpay.top/Article/details/gt2clcsifvp.html

[U66] PHP：设置 Cookie
来源：http://dali.yuxming.cn/Article/details/gt2zlqrujhf.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gt2unvlrixv.html

[U67] PHP：处理文件上传
来源：http://dali.mhx1999.top/Article/details/gt2amhipixf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yj202588.top/Article/details/gt2nlonqpeh.html

[U68] PHP：PDO 连接
来源：http://dali.nanxinkj.top/Article/details/gt2dwfnstgo.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.chenlongwang.top/Article/details/gt2lxhsgabh.html

[U69] PHP：PDO 预处理
来源：http://dali.pycfn.com/Article/details/gt2bexwsgyi.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.zhoulong.xyz/Article/details/gt2kunrorwm.html

[U70] PHP：PDO 事务
来源：http://dali.chenjidiqi.icu/Article/details/gt2fkqtvwea.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenlongwang.top/Article/details/gt2vdrhlhxv.html

[U71] PHP：抛出异常
来源：http://dali.gotoacloud.top/Article/details/gt2cbkxnikj.html

throw new RuntimeException("失败", 500);
来源：http://dali.jqgufenzy.top/Article/details/gt2dcufgrsi.html

[U72] PHP：写错误日志
来源：http://dali.yvedp.cn/Article/details/gt2fhakfmkn.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gt2ruhyajjq.html

[U73] PHP：读取 ini 配置
来源：http://dali.ydzc1.top/Article/details/gt2zegsxcip.html

parse_ini_file("config.ini", true)
来源：http://dali.snrcjt.cn/Article/details/gt2ppxbavsz.html

[U74] PHP：读取环境变量
来源：http://dali.yj202588.top/Article/details/gt2rumaryrd.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gt2udzmmzmd.html

[U75] PHP：依赖注入
来源：http://dali.jyoumei.cn/Article/details/gt2mdbxxuct.html

composer require psr/container
来源：http://dali.zdqjudy.top/Article/details/gt2xionccrj.html

[U76] PHP：简单路由
来源：http://dali.ppjwa.cn/Article/details/gt2asuhybyf.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.yonumen.top/Article/details/gt2pljqgkji.html

[U77] PHP：模板渲染
来源：http://dali.xylfe.cn/Article/details/gt2pqppkkyj.html

composer require twig/twig
来源：http://dali.nanxuanxn.top/Article/details/gt2rzzggkid.html

[U78] PHP：单元测试
来源：http://dali.yonumen.top/Article/details/gt2npwynvqd.html

composer require --dev phpunit/phpunit
来源：http://dali.jqgfzy.top/Article/details/gt2ynbczmii.html

[U79] PHP：静态分析
来源：http://dali.hysaishi.cn/Article/details/gt2zrzuowor.html

composer require --dev phpstan/phpstan
来源：http://dali.yj20258888.top/Article/details/gt2fbtbhgjt.html

[U80] PHP：代码规范修复
来源：http://dali.aizwys.cn/Article/details/gt2niyetold.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cqqwz.cn/Article/details/gt2jfzicczj.html

[U81] JS：初始化项目
来源：http://dali.fzhhl.top/Article/details/gt2fgcbiqze.html

npm init -y;  npm i express
来源：http://dali.yueranfly.top/Article/details/gt2tcajxhua.html

[U82] JS：package.json 脚本
来源：http://dali.hnqzz.top/Article/details/gt2dgovzkwv.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuanzhike.top/Article/details/gt2osvanhjn.html

[U83] JS：ES Module 导入导出
来源：http://dali.birdmap.top/Article/details/gt2bwhuavvg.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xopgaimj.html

[U84] JS：CommonJS 写法
来源：http://dali.ehwqpu.com/Article/details/gt2srjbmegq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tanke756.top/Article/details/gt2tqqojlqs.html

[U85] JS：可选链
来源：http://dali.mhx1999.top/Article/details/gt2uvcyitfz.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gt2rnuhhnwn.html

[U86] JS：空值合并
来源：http://dali.hammf.cn/Article/details/gt2ftyhqkhc.html

a ?? b
来源：http://dali.gzhubu.top/Article/details/gt2flldjstt.html

[U87] JS：解构默认值
来源：http://dali.chenlongwang.top/Article/details/gt2qhomiiqk.html

const { a = 1, b = 2 } = obj;
来源：http://dali.aibaodan.cn/Article/details/gt2npbbzpla.html

[U88] JS：对象展开合并
来源：http://dali.wangdashe.top/Article/details/gt2ctmqfujq.html

{ ...a, ...b }
来源：http://dali.fzhhl.top/Article/details/gt2gakqftsw.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gt2olzeqizx.html

[...new Set(arr)]
来源：http://dali.quarkkingdee.top/Article/details/gt2ylwjsfiz.html

[U90] JS：数字数组排序
来源：http://dali.wangdashe.top/Article/details/gt2eftpuxbe.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2hdfjbapk.html

[U91] JS：对象键值遍历
来源：http://dali.daria6918.cn/Article/details/gt2oyuvzoge.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yongpay.top/Article/details/gt2ncfgvgxs.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gt2gsajozzm.html

structuredClone(obj)
来源：http://dali.guowangkeji.top/Article/details/gt2rjjhgiei.html

[U93] JS：模板字符串
来源：http://dali.xuanzx.com/Article/details/gt2zjfqnshz.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gt2lkxphegt.html

[U94] JS：箭头函数
来源：http://dali.yvedp.cn/Article/details/gt2cjewbvmy.html

const double = x => x * 2;
来源：http://dali.zdqjudy.top/Article/details/gt2abjwvffv.html

[U95] JS：Promise 包装
来源：http://dali.tanke756.top/Article/details/gt2bzacqcqi.html

new Promise((resolve, reject) => {})
来源：http://dali.jinqigfzy.top/Article/details/gt2ccoxodwu.html

[U96] JS：async/await 与异常
来源：http://dali.sxryk.cn/Article/details/gt2axepjhws.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hysaishi.cn/Article/details/gt2jhgohcfs.html

[U97] JS：并发请求
来源：http://dali.yanxiufei.cn/Article/details/gt2upyljtjf.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.xylfe.cn/Article/details/gt2tshchcup.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gt2ljagnhje.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.zhoulong.xyz/Article/details/gt2ouphpulu.html

[U99] JS：事件监听
来源：http://dali.fengsongda.top/Article/details/gt2yigolfzv.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gt2ecgknvnl.html

[U100] JS：DOM 查询
来源：http://dali.yj20258.top/Article/details/gt2vquaaawe.html

document.querySelector(".item")
来源：http://dali.nanxinkj.top/Article/details/gt2phefvngc.html

[U101] JS：classList 操作
来源：http://dali.zdqjudy.top/Article/details/gt2wnaqknzu.html

el.classList.toggle("active")
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnkgpcwo.html

[U102] JS：本地存储
来源：http://dali.chenjidiqi.icu/Article/details/gt2dhdiqihk.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dzjqvpgj.html

[U103] JS：定时器
来源：http://dali.ehwqpu.com/Article/details/gt2vmlpqtie.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gt2klzzuvnr.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gt2ighdonpo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gzhubu.top/Article/details/gt2tiluyqxe.html

[U105] JS：节流
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjdlyoec.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.hongshengwenyu.top/Article/details/gt2bsdtbosi.html

[U106] JS：日期格式化
来源：http://dali.mhx1999.top/Article/details/gt2xsolczdu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.zdqjudy.top/Article/details/gt2aulfvlvh.html

[U107] JS：数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gt2gfcxwejj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zhixingplan.top/Article/details/gt2icvgcfxa.html

[U108] JS：随机整数
来源：http://dali.vqdsnc.cn/Article/details/gt2vwejxvae.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.bjfxy.top/Article/details/gt2elobjdfl.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gt2xzrmkohe.html

Object.groupBy(arr, x => x.type)
来源：http://dali.yongpay.top/Article/details/gt2ettzhpws.html

[U110] JS：数组分块
来源：http://dali.gzhubu.top/Article/details/gt2fypdqlto.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yj202588.top/Article/details/gt2senzrcxj.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gt2wjgrztrp.html

new Map(Object.entries(obj))
来源：http://dali.0kj1m.cn/Article/details/gt2uaenvrrt.html

[U112] JS：字符串补位
来源：http://dali.gaohongyu789.top/Article/details/gt2vwmksppp.html

"7".padStart(3, "0")
来源：http://dali.9152youxi.cn/Article/details/gt2ruseazwi.html

[U113] JS：正则替换全部
来源：http://dali.svipenyu.cn/Article/details/gt2pgwichai.html

s.replaceAll("a", "b")
来源：http://dali.yj202588.top/Article/details/gt2tenmcbbk.html

[U114] JS：JSON 深比较
来源：http://dali.gotoacloud.top/Article/details/gt2nbvoddqq.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tanke756.top/Article/details/gt2vzcpbyma.html

[U115] JS：生成 UUID
来源：http://dali.cashguo.top/Article/details/gt2aoxjdprx.html

crypto.randomUUID()
来源：http://dali.xylfe.cn/Article/details/gt2twuegdjh.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rxcphonl.html

/** @param {string} name */ function f(name) {}
来源：http://dali.yuxming.cn/Article/details/gt2cwtgtdkd.html

[U117] JS：单元测试
来源：http://dali.sxryk.cn/Article/details/gt2ymrkfdhv.html

npm i -D vitest;  npx vitest
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zijylbic.html

[U118] JS：开发服务器
来源：http://dali.gaohongyu789.top/Article/details/gt2nvyzbfko.html

npm i -D vite;  npx vite
来源：http://dali.zhengqikj.top/Article/details/gt2tzbcirqb.html

[U119] JS：生产构建
来源：http://dali.wangshuangyany.cn/Article/details/gt2zqlljrvx.html

npx vite build
来源：http://dali.yj20258.top/Article/details/gt2mdhtyztk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jiagoushi.top/Article/details/gt2aqpomlhz.html

import.meta.env.VITE_API_URL
来源：http://dali.yonumen.top/Article/details/gt2gevntkcg.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2sgqktnie.html

统计汇总
来源：http://dali.zhoulong.xyz/Article/details/gt2flpawnhq.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2sqjrbojb.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pflzadrn.html

Python ......... 252
来源：http://dali.fzhhl.top/Article/details/gt2obavpldo.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gt2usqdtdmj.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gt2eucoaoip.html

TypeScript ..... 212
来源：http://dali.snrcjt.cn/Article/details/gt2vdwosktc.html

Java ........... 212
来源：http://dali.yj20258888.top/Article/details/gt2osivutbe.html

Go ............. 212
来源：http://dali.yj20258888.top/Article/details/gt2mwlmbuwj.html

Ruby ........... 212
来源：http://dali.sysykeji.top/Article/details/gt2vicbwrzd.html

C# ............. 212
来源：http://dali.yuxming.cn/Article/details/gt2mcgpmgfj.html

C .............. 30
来源：http://dali.316326.xyz/Article/details/gt2ljxdssbt.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mogzrtsb.html

SQL ............ 90
来源：http://dali.hywenlv.cn/Article/details/gt2eyeizhpt.html

Bash ........... 80
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xilldckt.html

Kotlin ......... 15
来源：http://dali.yonumen.top/Article/details/gt2rapfymwt.html

Swift .......... 15
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2exlogfgu.html

Lua ............ 10
来源：http://dali.iojbl.cn/Article/details/gt2yirfdmfk.html

Perl ........... 10
来源：http://dali.bjfxy.top/Article/details/gt2caivqbuk.html

Scala .......... 10
来源：http://dali.jinqigufen.top/Article/details/gt2zqyqgowk.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gt2gerczdlh.html

合计 ........... 2106 条
来源：http://dali.aizwys.cn/Article/details/gt2btbsrxvr.html

按章节统计：
来源：http://dali.hywenlv.cn/Article/details/gt2orvknupn.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gt2ptgzpgda.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shuidangran.top/Article/details/gt2mkxafznd.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.c1oappe.top/Article/details/gt2csgueuuf.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.bjfxy.top/Article/details/gt2mjjffkqe.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvojwqkt.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.svipenyu.cn/Article/details/gt2szuvrjzl.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.zhijiandao.cn/Article/details/gt2buiehgfr.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gt2onlmmjyo.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gt2rrshyhjn.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.yj20258.top/Article/details/gt2nipfcgep.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.daria6918.cn/Article/details/gt2tltmkwzu.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gt2fkmabetf.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.guannengcc.top/Article/details/gt2abzbvkyw.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.hnxiangtu.top/Article/details/gt2gmeuohhb.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lvxklwjj.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2brjjylli.html


<!-- 参考信息 -->