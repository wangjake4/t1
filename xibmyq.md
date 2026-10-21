代发 wailian999

val a = 1;  var b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtoqtyhedd.html

[T53] Scala：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtzwztgqmt.html

s"值: $b"
来源：http://dali.c1oappe.top/Article/details/gttxhfmqzo.html

[T54] Scala：集合映射
来源：http://dali.gogol.net.cn/Article/details/gtepynhegz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gtpzeontxz.html

[T55] Scala：集合过滤
来源：http://dali.sufxvd.cn/Article/details/gtfexzxamm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zdqjudy.top/Article/details/gtravyyqgb.html

[T56] Scala：样例类
来源：http://dali.ivvv.top/Article/details/gtpetbslnz.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtkwpydvyw.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtvargfzjr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jiagoushi.top/Article/details/gtztofgnrx.html

[T58] Scala：函数定义
来源：http://dali.cqqwz.cn/Article/details/gtlipnzvjy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtdkiitham.html

[T59] Scala：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtlnpfgwgc.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtfbgmevyf.html

[T60] Scala：折叠
来源：http://dali.jinqigfzy.top/Article/details/gtwjmqjdeu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gogol.net.cn/Article/details/gtsffkjysq.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqoexpgpz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtdytjvncm.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtlxtjblyv.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtmzkcdhxz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhongyouzk.top/Article/details/gtdpcfuqjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ivvv.top/Article/details/gtsihyaeih.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj202588.top/Article/details/gtcyoakqqi.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gtailbzcsw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtgzpodwze.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gtdzuaswcs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yangfankeji.com/Article/details/gtbmxerfhe.html

[U05] Py：列表去重且保序
来源：http://dali.cdnleiting.top/Article/details/gtombxgdxe.html

list(dict.fromkeys(arr))
来源：http://dali.xinyue.icu/Article/details/gtbrixvjkf.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gtmkmawtmy.html

{**a, **b}
来源：http://dali.guowangkeji.top/Article/details/gtafztnnef.html

[U07] Py：反转字典键值
来源：http://dali.nwbrower.top/Article/details/gtpufybmin.html

{v: k for k, v in d.items()}
来源：http://dali.zdqjudy.top/Article/details/gtaczpxxpn.html

[U08] Py：展平二维列表
来源：http://dali.jinqigufen.top/Article/details/gtmjzmuigi.html

[y for x in nested for y in x]
来源：http://dali.cqqwz.cn/Article/details/gtpigrdcki.html

[U09] Py：字典取最大值的键
来源：http://dali.gogol.net.cn/Article/details/gtfepinqsd.html

max(d, key=d.get)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtipbqqwce.html

[U10] Py：按值排序字典
来源：http://dali.shangyingyoupin.top/Article/details/gtnfsjaiqc.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.fzhhl.top/Article/details/gtkhzyswnh.html

[U11] Py：生成器表达式
来源：http://dali.gzhubu.top/Article/details/gtmvivpemv.html

(x * 2 for x in arr)
来源：http://dali.shzxlz.cn/Article/details/gtjqjyiudt.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtqcmlnlxy.html

Counter(arr).most_common(3)
来源：http://dali.sweek.top/Article/details/gtacjnture.html

[U13] Py：固定长度队列
来源：http://dali.ydzc1.top/Article/details/gtzaywvkmx.html

deque(maxlen=10)
来源：http://dali.feifeiyinyue.top/Article/details/gtnobtclaf.html

[U14] Py：分组收集到列表
来源：http://dali.xziqi.cn/Article/details/gtfkhiqwrp.html

defaultdict(list)
来源：http://dali.chenlongwang.top/Article/details/gtrhtvaqol.html

[U15] Py：高精度计时
来源：http://dali.jyoumei.cn/Article/details/gtyltzjkuc.html

t = time.perf_counter()
来源：http://dali.ppjwa.cn/Article/details/gtvnupcacu.html

[U16] Py：命令行参数解析
来源：http://dali.nwbrower.top/Article/details/gtdebgorqe.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.dashuyun.cn/Article/details/gtepsasjgz.html

[U17] Py：初始化日志
来源：http://dali.aizwys.cn/Article/details/gtqsvwzges.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.smart0.xyz/Article/details/gttbnpnxul.html

[U18] Py：预编译正则
来源：http://dali.havefunace.top/Article/details/gtzvgnfxjr.html

pat = re.compile(r"\d+")
来源：http://dali.iojbl.cn/Article/details/gthcexwbda.html

[U19] Py：正则替换带回调
来源：http://dali.ivvv.top/Article/details/gtdwqjsnby.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.yuanzhike.top/Article/details/gtjprznrjb.html

[U20] Py：缓存函数结果
来源：http://dali.guowangkeji.top/Article/details/gtuystbqcm.html

@functools.lru_cache(maxsize=None)
来源：http://dali.dashuyun.cn/Article/details/gtcasxohcu.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangdashe.top/Article/details/gtvxanelow.html

@contextlib.contextmanager
来源：http://dali.sweek.top/Article/details/gtegrfcxij.html

[U22] Py：矩阵转置
来源：http://dali.nanxuanxn.top/Article/details/gtsmmwszzh.html

list(zip(*m))
来源：http://dali.andypj.xyz/Article/details/gtibkmvgtl.html

[U23] Py：分块读取大文件
来源：http://dali.gotoacloud.top/Article/details/gtnotcucqh.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.xuetiantiany.cn/Article/details/gtsbioztdq.html

[U24] Py：路径操作
来源：http://dali.zhengqikj.top/Article/details/gtrvwkwfbf.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkwierkpn.html

[U25] Py：CSV 按字典读
来源：http://dali.vqdsnc.cn/Article/details/gtwiwvmprv.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtzsfddngg.html

[U26] Py：并发下载
来源：http://dali.sufxvd.cn/Article/details/gttlbxzjqm.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.zhongyouzk.top/Article/details/gttdhlfuhc.html

[U27] Py：异步 HTTP
来源：http://dali.gotoacloud.top/Article/details/gtkgtleokg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.yj202588.top/Article/details/gtsjcfnaja.html

[U28] Py：类型别名
来源：http://dali.pycfn.com/Article/details/gtkkjdnfkb.html

UserId = int
来源：http://dali.yj20258.top/Article/details/gtvnblnvam.html

[U29] Py：属性校验
来源：http://dali.yongpay.top/Article/details/gtohkruqvu.html

@property 与 @x.setter 配合
来源：http://dali.guannengcc.top/Article/details/gtbwwkoixz.html

[U30] Py：数据类
来源：http://dali.ivvv.top/Article/details/gtjgsahqwr.html

@dataclass(slots=True)
来源：http://dali.svipenyu.cn/Article/details/gtjqtomzjq.html

[U31] Py：单测
来源：http://dali.sufxvd.cn/Article/details/gthwzcuiom.html

python -m pytest -q
来源：http://dali.hywenlv.cn/Article/details/gtbqfipxfh.html

[U32] Py：代码格式化
来源：http://dali.chenzaomai.com/Article/details/gtfvozixon.html

ruff format . && ruff check --fix .
来源：http://dali.yueranfly.top/Article/details/gtdxyummme.html

[U33] Py：打包发布
来源：http://dali.zhoulong.xyz/Article/details/gtfqrzglvo.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.gzhubu.top/Article/details/gtzhnocfut.html

[U34] Py：判断编码
来源：http://dali.316326.xyz/Article/details/gtwjvqjwcq.html

chardet.detect(raw)
来源：http://dali.9152youxi.cn/Article/details/gtalaosznx.html

[U35] Py：发送邮件
来源：http://dali.sweek.top/Article/details/gtflketiye.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fzhhl.top/Article/details/gtlhqyggxi.html

[U36] Py：定时任务
来源：http://dali.nanxinkj.top/Article/details/gtxocppemc.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangtech.top/Article/details/gtahambqmk.html

[U37] Py：读写 Excel
来源：http://dali.zhaomingkeji.xyz/Article/details/gtchmocuwn.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.jlsjyb.cn/Article/details/gtpnuiszxe.html

[U38] Py：获取脚本所在目录
来源：http://dali.dianchejie.cn/Article/details/gtzqgvloyn.html

Path(__file__).resolve().parent
来源：http://dali.yvedp.cn/Article/details/gtavetwkvu.html

[U39] Py：判断是否在交互环境
来源：http://dali.zhixingplan.top/Article/details/gtbkoemzqz.html

sys.stdout.isatty()
来源：http://dali.zhengqikj.top/Article/details/gtrahpwwla.html

[U40] Py：打印到标准错误
来源：http://dali.jyoumei.cn/Article/details/gtdcjjhlwq.html

print("err", file=sys.stderr)
来源：http://dali.meibo888.top/Article/details/gttnxwrfnc.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.kuanghao11.cn/Article/details/gtdrnrxhta.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gtpkghzqsz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xylfe.cn/Article/details/gtibfbvqca.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gtjcggkezb.html

[U43] PHP：声明命名空间
来源：http://dali.tianlin.xyz/Article/details/gtwiydjzqf.html

namespace App\Http;
来源：http://dali.chenjidiqi.icu/Article/details/gtrfsyaxwx.html

[U44] PHP：开启严格类型
来源：http://dali.svipenyu.cn/Article/details/gtbstqmtvr.html

declare(strict_types=1);
来源：http://dali.cdnleiting.top/Article/details/gthfnmdhqz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.tianlin.xyz/Article/details/gtxvvypgqh.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtldaoxhri.html

[U46] PHP：可空类型
来源：http://dali.pengpengdd.cyou/Article/details/gtimwhlslo.html

?string $name = null
来源：http://dali.jianghu66.top/Article/details/gtcqmezoap.html

[U47] PHP：联合类型
来源：http://dali.zhijiandao.cn/Article/details/gteqvvpvkp.html

int|string $id
来源：http://dali.hfpthk.cn/Article/details/gtwikthylt.html

[U48] PHP：纯枚举
来源：http://dali.zhijiandao.cn/Article/details/gtdkszwjfc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.9152youxi.cn/Article/details/gtxnypdzzw.html

[U49] PHP：只读属性
来源：http://dali.dashuyun.cn/Article/details/gtpslsvbal.html

public readonly string $name
来源：http://dali.daria6918.cn/Article/details/gtagjktiwt.html

[U50] PHP：构造器属性提升
来源：http://dali.xuanzx.com/Article/details/gteaivpnfz.html

public function __construct(private int $id) {}
来源：http://dali.jyoumei.cn/Article/details/gttcryoupi.html

[U51] PHP：数组解构
来源：http://dali.hongshengwenyu.top/Article/details/gtfurcbanr.html

[$a, $b] = $arr;
来源：http://dali.gzhubu.top/Article/details/gthveoarmw.html

[U52] PHP：箭头函数
来源：http://dali.xylfe.cn/Article/details/gtcjkcnhke.html

$double = fn($x) => $x * 2;
来源：http://dali.chenlongwang.top/Article/details/gtivgeiedm.html

[U53] PHP：空合并运算符
来源：http://dali.wangshuangyany.cn/Article/details/gthqkbailg.html

$v = $a ?? $b ?? "default";
来源：http://dali.shuidangran.top/Article/details/gtdgowwdbz.html

[U54] PHP：空安全调用
来源：http://dali.cdnleiting.top/Article/details/gtpqlzpmzl.html

$obj?->method()
来源：http://dali.guannengcc.top/Article/details/gtcwheysqz.html

[U55] PHP：match 表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtyiyzeipw.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtbcpuuzav.html

[U56] PHP：命名参数
来源：http://dali.yj202588.top/Article/details/gtwiuncpbw.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtypfmxxmt.html

[U57] PHP：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtorgnpfoj.html

"值: {$a}"
来源：http://dali.yongpay.top/Article/details/gtwasoovrd.html

[U58] PHP：数组三件套
来源：http://dali.meibo888.top/Article/details/gtfgcdsifg.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.nwbrower.top/Article/details/gtqbzdmqil.html

[U59] PHP：自定义排序
来源：http://dali.pycfn.com/Article/details/gtxybxsrpi.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.yuanzhike.top/Article/details/gtwtfyvgij.html

[U60] PHP：JSON 编解码
来源：http://dali.havefunace.top/Article/details/gthuivsznr.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.hywenlv.cn/Article/details/gtfgszdhvx.html

[U61] PHP：正则
来源：http://dali.jyoumei.cn/Article/details/gtbrgorcln.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hnxiangtu.top/Article/details/gtsixpuowk.html

[U62] PHP：日期对象
来源：http://dali.cheryme.top/Article/details/gtmkyvatrk.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.wangdashe.top/Article/details/gtnvbwsoda.html

[U63] PHP：文件读写
来源：http://dali.ivvv.top/Article/details/gtkazwycog.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sufxvd.cn/Article/details/gtyeyjnnvy.html

[U64] PHP：目录遍历
来源：http://dali.wangdashe.top/Article/details/gtaidmiuat.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.shangyingyoupin.top/Article/details/gtvxkiibyg.html

[U65] PHP：会话
来源：http://dali.feifeiyinyue.top/Article/details/gtmleahtpe.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxzthula.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtkeradhze.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.cucudq.cn/Article/details/gtabjcthji.html

[U67] PHP：处理文件上传
来源：http://dali.xylfe.cn/Article/details/gtjikflmje.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoixppmkv.html

[U68] PHP：PDO 连接
来源：http://dali.zhiwuduotai.top/Article/details/gtxqdzcuxd.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jinqigfzy.top/Article/details/gtomuhmibi.html

[U69] PHP：PDO 预处理
来源：http://dali.sysykeji.top/Article/details/gtmrcppchb.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.cashguo.top/Article/details/gtqyztmlzy.html

[U70] PHP：PDO 事务
来源：http://dali.dianchejie.cn/Article/details/gtzizfrkjg.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.gzhubu.top/Article/details/gtmlewxmaw.html

[U71] PHP：抛出异常
来源：http://dali.yj20258.top/Article/details/gtlzsqwxbb.html

throw new RuntimeException("失败", 500);
来源：http://dali.redwolf501.top/Article/details/gtztlubrxo.html

[U72] PHP：写错误日志
来源：http://dali.zycfv.cn/Article/details/gtqojwzpbr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.hfpthk.cn/Article/details/gttojnltsw.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258888.top/Article/details/gtnvelvftb.html

parse_ini_file("config.ini", true)
来源：http://dali.hnqzz.top/Article/details/gtsmiukziy.html

[U74] PHP：读取环境变量
来源：http://dali.chenzaomai.com/Article/details/gtetiaygca.html

getenv("APP_ENV") ?: "production"
来源：http://dali.guannengcc.top/Article/details/gtkdxdyjxt.html

[U75] PHP：依赖注入
来源：http://dali.sysykeji.top/Article/details/gtecbkarai.html

composer require psr/container
来源：http://dali.yangfankeji.com/Article/details/gtwdedwykv.html

[U76] PHP：简单路由
来源：http://dali.yuanzhike.top/Article/details/gtsyiwjdfy.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.ehwqpu.com/Article/details/gtxkgcjqhw.html

[U77] PHP：模板渲染
来源：http://dali.jinqigufen.top/Article/details/gtokgncpqu.html

composer require twig/twig
来源：http://dali.yvedp.cn/Article/details/gtmdylvbvb.html

[U78] PHP：单元测试
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtritsxy.html

composer require --dev phpunit/phpunit
来源：http://dali.shzxlz.cn/Article/details/gtpsgzpmfa.html

[U79] PHP：静态分析
来源：http://dali.haohaochexian.top/Article/details/gtirgwgmue.html

composer require --dev phpstan/phpstan
来源：http://dali.smart0.xyz/Article/details/gtwekncvot.html

[U80] PHP：代码规范修复
来源：http://dali.chenzaomai.com/Article/details/gtqrhfiddc.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.fzhhl.top/Article/details/gtmacrufjh.html

[U81] JS：初始化项目
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzerhdsr.html

npm init -y;  npm i express
来源：http://dali.cdnleiting.top/Article/details/gtnkqtxrfd.html

[U82] JS：package.json 脚本
来源：http://dali.ppjwa.cn/Article/details/gtheejuuce.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yj20258888.top/Article/details/gteuvxprec.html

[U83] JS：ES Module 导入导出
来源：http://dali.zhijiandao.cn/Article/details/gtwpxxhhyo.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yuanzhike.top/Article/details/gtlutmgbvx.html

[U84] JS：CommonJS 写法
来源：http://dali.ydzc1.top/Article/details/gtinzbhpqb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.nanxinkj.top/Article/details/gtohnaldfn.html

[U85] JS：可选链
来源：http://dali.316326.xyz/Article/details/gtokinvbou.html

a?.b?.c
来源：http://dali.zhixingplan.top/Article/details/gtewgwqaal.html

[U86] JS：空值合并
来源：http://dali.chenjidiqi.icu/Article/details/gtxhtokupk.html

a ?? b
来源：http://dali.pycfn.com/Article/details/gtfluuhdcr.html

[U87] JS：解构默认值
来源：http://dali.zdqjudy.top/Article/details/gtwtzotrya.html

const { a = 1, b = 2 } = obj;
来源：http://dali.wangdashe.top/Article/details/gtcajkqfsq.html

[U88] JS：对象展开合并
来源：http://dali.mhx1999.top/Article/details/gtsliiozjc.html

{ ...a, ...b }
来源：http://dali.cheryme.top/Article/details/gtechkkcum.html

[U89] JS：数组去重
来源：http://dali.316326.xyz/Article/details/gtkobnaull.html

[...new Set(arr)]
来源：http://dali.daxiang520.top/Article/details/gtovazqwdz.html

[U90] JS：数字数组排序
来源：http://dali.hnqzz.top/Article/details/gthdxvdnkt.html

[...arr].sort((a, b) => a - b)
来源：http://dali.gaohongyu789.top/Article/details/gtljakycwv.html

[U91] JS：对象键值遍历
来源：http://dali.haohaochexian.top/Article/details/gtxlwgpcnh.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.0kj1m.cn/Article/details/gtfimiwidu.html

[U92] JS：深拷贝
来源：http://dali.jyoumei.cn/Article/details/gtctiqfzdf.html

structuredClone(obj)
来源：http://dali.gzhubu.top/Article/details/gtfgdaugvy.html

[U93] JS：模板字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapxzqwaf.html

`共 ${n} 条`
来源：http://dali.birdmap.top/Article/details/gtzgvigbaq.html

[U94] JS：箭头函数
来源：http://dali.gzhubu.top/Article/details/gtnyyljvme.html

const double = x => x * 2;
来源：http://dali.jiagoushi.top/Article/details/gtsgfykghg.html

[U95] JS：Promise 包装
来源：http://dali.ybcxt.top/Article/details/gtunwdzkpt.html

new Promise((resolve, reject) => {})
来源：http://dali.hnxiangtu.top/Article/details/gtacurgzea.html

[U96] JS：async/await 与异常
来源：http://dali.yuanzhike.top/Article/details/gtkhjkijju.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrjsszqvl.html

[U97] JS：并发请求
来源：http://dali.jinqigufen.top/Article/details/gtvkzkbvkq.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.daxiang520.top/Article/details/gthjkuhyaa.html

[U98] JS：fetch 带 JSON
来源：http://dali.meibo888.top/Article/details/gtksztmlcc.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jianghu66.top/Article/details/gtwukgfjjy.html

[U99] JS：事件监听
来源：http://dali.yj20258.top/Article/details/gtmstfjanz.html

el.addEventListener("click", e => {})
来源：http://dali.yuxming.cn/Article/details/gtinwdbykw.html

[U100] JS：DOM 查询
来源：http://dali.zdqjudy.top/Article/details/gtkutqzbhn.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtwelcslxm.html

[U101] JS：classList 操作
来源：http://dali.shuidangran.top/Article/details/gtacndvlgc.html

el.classList.toggle("active")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuplbjrbn.html

[U102] JS：本地存储
来源：http://dali.yangfankeji.com/Article/details/gtbobxcplh.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.ydzc1.top/Article/details/gtrzzrynmg.html

[U103] JS：定时器
来源：http://dali.dashuyun.cn/Article/details/gtmkotyaxp.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yonumen.top/Article/details/gtyejfhwjr.html

[U104] JS：防抖
来源：http://dali.aizwys.cn/Article/details/gtvmepnove.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.sufxvd.cn/Article/details/gtexddnwot.html

[U105] JS：节流
来源：http://dali.yj202588.top/Article/details/gtjlfhqhdk.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinqigfzy.top/Article/details/gtbwbcwkwf.html

[U106] JS：日期格式化
来源：http://dali.xuanzx.com/Article/details/gtbkazadsd.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.mhx1999.top/Article/details/gtignfkbcc.html

[U107] JS：数字千分位
来源：http://dali.sxryk.cn/Article/details/gtwvbuksti.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gtgzfrtndo.html

[U108] JS：随机整数
来源：http://dali.sysykeji.top/Article/details/gtiguhhyrg.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jinyuanbaomall.cn/Article/details/gttgsixuzk.html

[U109] JS：数组分组
来源：http://dali.fzhhl.top/Article/details/gtfoozxdlq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtyvyenxmn.html

[U110] JS：数组分块
来源：http://dali.xuanzx.com/Article/details/gtujsjdudf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhiwuduotai.top/Article/details/gtfhulgqpa.html

[U111] JS：对象转 Map
来源：http://dali.0kj1m.cn/Article/details/gtbwwbozut.html

new Map(Object.entries(obj))
来源：http://dali.jyoumei.cn/Article/details/gtxrxideeo.html

[U112] JS：字符串补位
来源：http://dali.daxiang520.top/Article/details/gtevtxlhzh.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gtgerhwnww.html

[U113] JS：正则替换全部
来源：http://dali.dashuyun.cn/Article/details/gtkyrovkyf.html

s.replaceAll("a", "b")
来源：http://dali.jinqigufen.top/Article/details/gthdtyiyni.html

[U114] JS：JSON 深比较
来源：http://dali.hongshengwenyu.top/Article/details/gtoswvqpiv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsdlrhsc.html

[U115] JS：生成 UUID
来源：http://dali.wangdashe.top/Article/details/gtqaipscoe.html

crypto.randomUUID()
来源：http://dali.gotoacloud.top/Article/details/gthhesikmv.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gaohongyu789.top/Article/details/gtjvpczdok.html

/** @param {string} name */ function f(name) {}
来源：http://dali.chenzaomai.com/Article/details/gtvudcyafd.html

[U117] JS：单元测试
来源：http://dali.yuxming.cn/Article/details/gtzpzrxsxb.html

npm i -D vitest;  npx vitest
来源：http://dali.yanxiufei.cn/Article/details/gthlkggbkj.html

[U118] JS：开发服务器
来源：http://dali.cqqwz.cn/Article/details/gtbukyqofh.html

npm i -D vite;  npx vite
来源：http://dali.cdnleiting.top/Article/details/gtcsaduluj.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gttfxhhkxe.html

npx vite build
来源：http://dali.zhongyouzk.top/Article/details/gtyaxlcxaa.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.jianghu66.top/Article/details/gtmuhmaifx.html

import.meta.env.VITE_API_URL
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvjzspbo.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlmnkhdda.html

统计汇总
来源：http://dali.chenjidiqi.icu/Article/details/gtlloofuhz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gttpysztye.html

按语言统计（条）：
来源：http://dali.meibo888.top/Article/details/gtzqcmjysx.html

Python ......... 252
来源：http://dali.gotoacloud.top/Article/details/gtgvtvwgwn.html

PHP ............ 252
来源：http://dali.sweek.top/Article/details/gtklqfrrue.html

JavaScript ..... 252
来源：http://dali.jlsjyb.cn/Article/details/gtougdlgrw.html

TypeScript ..... 212
来源：http://dali.zhengqikj.top/Article/details/gtugrycxci.html

Java ........... 212
来源：http://dali.iojbl.cn/Article/details/gtxtnlezwy.html

Go ............. 212
来源：http://dali.shangyingyoupin.top/Article/details/gtgpqupxnw.html

Ruby ........... 212
来源：http://dali.chenjidiqi.icu/Article/details/gtizhjqgfs.html

C# ............. 212
来源：http://dali.mhx1999.top/Article/details/gtoahsomfw.html

C .............. 30
来源：http://dali.yj20258.top/Article/details/gtjnikxlyy.html

C++ ............ 30
来源：http://dali.snrcjt.cn/Article/details/gtjahfosqc.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtjdaldiqo.html

Bash ........... 80
来源：http://dali.hfpthk.cn/Article/details/gthmgllyfj.html

Kotlin ......... 15
来源：http://dali.yj20258.top/Article/details/gtsyosisey.html

Swift .......... 15
来源：http://dali.316326.xyz/Article/details/gtgcztreed.html

Lua ............ 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtryozaymf.html

Perl ........... 10
来源：http://dali.zhiwuduotai.top/Article/details/gtjqimdhij.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtfzmoawnb.html

------------------------------------
来源：http://dali.9152youxi.cn/Article/details/gtmcmnnhkt.html

合计 ........... 2106 条
来源：http://dali.tianlin.xyz/Article/details/gtxbllevma.html

按章节统计：
来源：http://dali.yanxiufei.cn/Article/details/gtedrxqvou.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhoulong.xyz/Article/details/gtuzijxpnt.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.ydzc1.top/Article/details/gtmnswffgs.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ppjwa.cn/Article/details/gtzsyhgxam.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.jinghuilouyu.cn/Article/details/gteusheoax.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gtsoqccpnn.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.yongpay.top/Article/details/gtvnvefpyb.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.pycfn.com/Article/details/gtqqakcsmb.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.hysaishi.cn/Article/details/gtdkmqfkxw.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.kuanghao11.cn/Article/details/gtgumhmezp.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.tian-w.cn/Article/details/gtweyvxrdl.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtphosluwz.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.zhixingplan.top/Article/details/gtegrvxrqb.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.sxryk.cn/Article/details/gtvlvbhgxl.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.guowangkeji.top/Article/details/gtzcpjcder.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.xylfe.cn/Article/details/gtinjqlqhl.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.nanxinkj.top/Article/details/gtqxtpclsg.html


<!-- 参考信息 -->