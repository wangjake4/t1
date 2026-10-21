代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtlkxykmah.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gtrionbscw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtyheogtub.html

[T58] Scala：函数定义
来源：http://dali.aizwys.cn/Article/details/gtbmnyjmqg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yongpay.top/Article/details/gtzdxulmbw.html

[T59] Scala：循环
来源：http://dali.zdqjudy.top/Article/details/gtjowukolj.html

for (i <- 1 to 10) println(i)
来源：http://dali.zhongyouzk.top/Article/details/gtdhohwqre.html

[T60] Scala：折叠
来源：http://dali.mhx1999.top/Article/details/gtrounlspv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xziqi.cn/Article/details/gtqkeltzzc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtsbhwmmzi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtgxgtvycl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtnsndkwfj.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtekjsdtnz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gtpwtsokjl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yuanzhike.top/Article/details/gtxfgchvif.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenlongwang.top/Article/details/gtegtohjpu.html

[U03] Py：加载 .env 配置
来源：http://dali.9152youxi.cn/Article/details/gtsasgkyfk.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shzxlz.cn/Article/details/gtwssdgzls.html

[U04] Py：变量调试打印
来源：http://dali.nanxinkj.top/Article/details/gtwkhhitxd.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gttzlyqufp.html

[U05] Py：列表去重且保序
来源：http://dali.yj20258888.top/Article/details/gtoftzzlqn.html

list(dict.fromkeys(arr))
来源：http://dali.zhijiandao.cn/Article/details/gtonofnalh.html

[U06] Py：合并两个字典
来源：http://dali.yanxiufei.cn/Article/details/gtgptpkfih.html

{**a, **b}
来源：http://dali.yonumen.top/Article/details/gttqnolhfk.html

[U07] Py：反转字典键值
来源：http://dali.daxiang520.top/Article/details/gtzbujprif.html

{v: k for k, v in d.items()}
来源：http://dali.guannengcc.top/Article/details/gthzyuiysi.html

[U08] Py：展平二维列表
来源：http://dali.hnqzz.top/Article/details/gtpjknawqp.html

[y for x in nested for y in x]
来源：http://dali.yonumen.top/Article/details/gtfahlzvin.html

[U09] Py：字典取最大值的键
来源：http://dali.jianghu66.top/Article/details/gthmhavqhg.html

max(d, key=d.get)
来源：http://dali.9152youxi.cn/Article/details/gtnoebaxwi.html

[U10] Py：按值排序字典
来源：http://dali.vqdsnc.cn/Article/details/gtskkzbydr.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.wangdashe.top/Article/details/gtieiufidb.html

[U11] Py：生成器表达式
来源：http://dali.xuanzx.com/Article/details/gtgqcvjkak.html

(x * 2 for x in arr)
来源：http://dali.chenzaomai.com/Article/details/gttjcpvlie.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrsgjise.html

Counter(arr).most_common(3)
来源：http://dali.bjfxy.top/Article/details/gthhdussne.html

[U13] Py：固定长度队列
来源：http://dali.sxryk.cn/Article/details/gtrpgvpbpq.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtstbqlnee.html

[U14] Py：分组收集到列表
来源：http://dali.vqdsnc.cn/Article/details/gtvqdyyynu.html

defaultdict(list)
来源：http://dali.hongshengwenyu.top/Article/details/gtbdcwchhg.html

[U15] Py：高精度计时
来源：http://dali.hongshengwenyu.top/Article/details/gtxrqgyjly.html

t = time.perf_counter()
来源：http://dali.iojbl.cn/Article/details/gtfebcrzif.html

[U16] Py：命令行参数解析
来源：http://dali.316326.xyz/Article/details/gtqevjbcrc.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.wangdashe.top/Article/details/gtiyzbwvpa.html

[U17] Py：初始化日志
来源：http://dali.ybcxt.top/Article/details/gtmdwgksfq.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.316326.xyz/Article/details/gtfgfywbok.html

[U18] Py：预编译正则
来源：http://dali.yj20258.top/Article/details/gtsejuyvbu.html

pat = re.compile(r"\d+")
来源：http://dali.tian-w.cn/Article/details/gtboxvyuog.html

[U19] Py：正则替换带回调
来源：http://dali.sweek.top/Article/details/gttiublggp.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.gogol.net.cn/Article/details/gtdzwmrjzf.html

[U20] Py：缓存函数结果
来源：http://dali.wangshuangyany.cn/Article/details/gtwrbiptqh.html

@functools.lru_cache(maxsize=None)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlilliixr.html

[U21] Py：自定义上下文管理器
来源：http://dali.yj20258888.top/Article/details/gtmfkzwkqm.html

@contextlib.contextmanager
来源：http://dali.redwolf501.top/Article/details/gtcprytdns.html

[U22] Py：矩阵转置
来源：http://dali.316326.xyz/Article/details/gtexaagrnq.html

list(zip(*m))
来源：http://dali.nanxuanxn.top/Article/details/gthqlsgplo.html

[U23] Py：分块读取大文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgqvcxyop.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.dianchejie.cn/Article/details/gtxbkozamh.html

[U24] Py：路径操作
来源：http://dali.cdnleiting.top/Article/details/gtcegpalnc.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.guowangkeji.top/Article/details/gtniqgdjus.html

[U25] Py：CSV 按字典读
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpzwcgnkg.html

csv.DictReader(f)
来源：http://dali.hywenlv.cn/Article/details/gtpbfwplqb.html

[U26] Py：并发下载
来源：http://dali.yj20258888.top/Article/details/gtfrzgqyol.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.iojbl.cn/Article/details/gtnyqwragx.html

[U27] Py：异步 HTTP
来源：http://dali.sysykeji.top/Article/details/gtamypflpx.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.chenlongwang.top/Article/details/gtrlvmxvwm.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gtmrvsbhmz.html

UserId = int
来源：http://dali.cqqwz.cn/Article/details/gtofrmpydj.html

[U29] Py：属性校验
来源：http://dali.chenzaomai.com/Article/details/gtjtguxncp.html

@property 与 @x.setter 配合
来源：http://dali.gotoacloud.top/Article/details/gtauxxmwuq.html

[U30] Py：数据类
来源：http://dali.fzhhl.top/Article/details/gtrhmcgphn.html

@dataclass(slots=True)
来源：http://dali.wangdashe.top/Article/details/gtwpgfgvef.html

[U31] Py：单测
来源：http://dali.hfpthk.cn/Article/details/gtsshqrisc.html

python -m pytest -q
来源：http://dali.zhongyouzk.top/Article/details/gtpllmybyu.html

[U32] Py：代码格式化
来源：http://dali.vqdsnc.cn/Article/details/gthunpjlti.html

ruff format . && ruff check --fix .
来源：http://dali.tian-w.cn/Article/details/gtvkzrcpxj.html

[U33] Py：打包发布
来源：http://dali.ppjwa.cn/Article/details/gtrahppsxi.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.nanxinkj.top/Article/details/gtezkxhdqr.html

[U34] Py：判断编码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrkirruyz.html

chardet.detect(raw)
来源：http://dali.fzhhl.top/Article/details/gtxhjatnry.html

[U35] Py：发送邮件
来源：http://dali.cashguo.top/Article/details/gtegttnqbx.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.0kj1m.cn/Article/details/gtchyjjtxo.html

[U36] Py：定时任务
来源：http://dali.yvedp.cn/Article/details/gtnnchggkk.html

schedule.every(10).minutes.do(job)
来源：http://dali.jiagoushi.top/Article/details/gtwvcrrrig.html

[U37] Py：读写 Excel
来源：http://dali.gzhubu.top/Article/details/gtvpqukuyg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xylfe.cn/Article/details/gtcbnacpug.html

[U38] Py：获取脚本所在目录
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxoenifa.html

Path(__file__).resolve().parent
来源：http://dali.hywenlv.cn/Article/details/gtslprckyu.html

[U39] Py：判断是否在交互环境
来源：http://dali.gzhubu.top/Article/details/gtxbhqijiq.html

sys.stdout.isatty()
来源：http://dali.jqgufenzy.top/Article/details/gtfmdwhplh.html

[U40] Py：打印到标准错误
来源：http://dali.yvedp.cn/Article/details/gtermzjiun.html

print("err", file=sys.stderr)
来源：http://dali.feifeiyinyue.top/Article/details/gtawzdmldo.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.zhiwuduotai.top/Article/details/gtnyedxvcv.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.0kj1m.cn/Article/details/gtunheitho.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.gzhubu.top/Article/details/gtrsajonja.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtmftvecfo.html

[U43] PHP：声明命名空间
来源：http://dali.quarkkingdee.top/Article/details/gtguegjyge.html

namespace App\Http;
来源：http://dali.guannengcc.top/Article/details/gtebmxwvsj.html

[U44] PHP：开启严格类型
来源：http://dali.gaohongyu789.top/Article/details/gthkguuxut.html

declare(strict_types=1);
来源：http://dali.c1oappe.top/Article/details/gtqygsuihi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyajblhsc.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtekeisuyy.html

[U46] PHP：可空类型
来源：http://dali.wangdashe.top/Article/details/gttalahmzy.html

?string $name = null
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyhcpxxqi.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gtjxcdhxsr.html

int|string $id
来源：http://dali.andypj.xyz/Article/details/gtxmuzuozt.html

[U48] PHP：纯枚举
来源：http://dali.cashguo.top/Article/details/gtbsswiwsi.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.xziqi.cn/Article/details/gttwigjrqn.html

[U49] PHP：只读属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlnbpisyb.html

public readonly string $name
来源：http://dali.yangfankeji.com/Article/details/gtagaxsmhs.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gtprbigyhh.html

public function __construct(private int $id) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmwjrnchp.html

[U51] PHP：数组解构
来源：http://dali.svipenyu.cn/Article/details/gtjweadmji.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtmybdesto.html

[U52] PHP：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtropsrdjw.html

$double = fn($x) => $x * 2;
来源：http://dali.jlsjyb.cn/Article/details/gtxxhpgkgx.html

[U53] PHP：空合并运算符
来源：http://dali.sweek.top/Article/details/gtckwqfejm.html

$v = $a ?? $b ?? "default";
来源：http://dali.kuanghao11.cn/Article/details/gtrsxzlcbi.html

[U54] PHP：空安全调用
来源：http://dali.ybcxt.top/Article/details/gtgzbqwzrn.html

$obj?->method()
来源：http://dali.smart0.xyz/Article/details/gtepwxujkp.html

[U55] PHP：match 表达式
来源：http://dali.9152youxi.cn/Article/details/gthmrwtujy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.daria6918.cn/Article/details/gtdetipwre.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gthjzdihkd.html

f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtkxjubwwh.html

[U57] PHP：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtmhdwzmbm.html

"值: {$a}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhvgxagl.html

[U58] PHP：数组三件套
来源：http://dali.jinqigfzy.top/Article/details/gtjjannsoh.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.haohaochexian.top/Article/details/gtutpedriw.html

[U59] PHP：自定义排序
来源：http://dali.birdmap.top/Article/details/gtvfyvyyup.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnulxrzaa.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtgbhaqngc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.sysykeji.top/Article/details/gtnciyhglu.html

[U61] PHP：正则
来源：http://dali.chenlongwang.top/Article/details/gtmuyvjhaq.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.ybcxt.top/Article/details/gtufgumrrm.html

[U62] PHP：日期对象
来源：http://dali.hnxiangtu.top/Article/details/gtasqgkmaa.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.gogol.net.cn/Article/details/gtxmvoxtlm.html

[U63] PHP：文件读写
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjyvicqgy.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.yj20258.top/Article/details/gtvavhfrxc.html

[U64] PHP：目录遍历
来源：http://dali.mhx1999.top/Article/details/gtzgxcjdhv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.dashuyun.cn/Article/details/gtgdnxfmxo.html

[U65] PHP：会话
来源：http://dali.hongshengwenyu.top/Article/details/gtytuhrhcs.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtohjukgst.html

[U66] PHP：设置 Cookie
来源：http://dali.quarkkingdee.top/Article/details/gtveapzbqy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.zhixingplan.top/Article/details/gtxdnbncyx.html

[U67] PHP：处理文件上传
来源：http://dali.pengpengdd.cyou/Article/details/gtyenfzsvr.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.haohaochexian.top/Article/details/gtkpmwytbj.html

[U68] PHP：PDO 连接
来源：http://dali.quarkkingdee.top/Article/details/gtmztgcvgk.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.aizwys.cn/Article/details/gtmcwbqmyz.html

[U69] PHP：PDO 预处理
来源：http://dali.jlsjyb.cn/Article/details/gtajecngon.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.jqgufenzy.top/Article/details/gtjvcrjfle.html

[U70] PHP：PDO 事务
来源：http://dali.yvedp.cn/Article/details/gtonwxbtww.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jinqigfzy.top/Article/details/gtoxgptvet.html

[U71] PHP：抛出异常
来源：http://dali.jianghu66.top/Article/details/gtzfaemgry.html

throw new RuntimeException("失败", 500);
来源：http://dali.aibaodan.cn/Article/details/gtcgbmzpjt.html

[U72] PHP：写错误日志
来源：http://dali.xuanzx.com/Article/details/gtdhpdzazd.html

error_log("失败: " . $e->getMessage());
来源：http://dali.kuanghao11.cn/Article/details/gtfzkyediw.html

[U73] PHP：读取 ini 配置
来源：http://dali.fengsongda.top/Article/details/gtnvxdhoxs.html

parse_ini_file("config.ini", true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffryvbcl.html

[U74] PHP：读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtdsjznids.html

getenv("APP_ENV") ?: "production"
来源：http://dali.hongshengwenyu.top/Article/details/gtythzqsri.html

[U75] PHP：依赖注入
来源：http://dali.daria6918.cn/Article/details/gtxcifogwy.html

composer require psr/container
来源：http://dali.jyoumei.cn/Article/details/gtjmktuywm.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtbusljkpu.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.daxiang520.top/Article/details/gtrdstywlw.html

[U77] PHP：模板渲染
来源：http://dali.jqgfzy.top/Article/details/gtgorvdkvx.html

composer require twig/twig
来源：http://dali.chenlongwang.top/Article/details/gtehjebodi.html

[U78] PHP：单元测试
来源：http://dali.jiagoushi.top/Article/details/gtejmngjjp.html

composer require --dev phpunit/phpunit
来源：http://dali.gaohongyu789.top/Article/details/gttylfssgt.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gtnjtbzpnp.html

composer require --dev phpstan/phpstan
来源：http://dali.chenjidiqi.icu/Article/details/gtaxmqzzno.html

[U80] PHP：代码规范修复
来源：http://dali.xylfe.cn/Article/details/gtduamzsqt.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.nwbrower.top/Article/details/gtynmrmfnk.html

[U81] JS：初始化项目
来源：http://dali.shanyushiyangtech.top/Article/details/gtuygjumlc.html

npm init -y;  npm i express
来源：http://dali.tanke756.top/Article/details/gtguncscaa.html

[U82] JS：package.json 脚本
来源：http://dali.dashuyun.cn/Article/details/gtpjnqfvij.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jlsjyb.cn/Article/details/gtbrvfapyt.html

[U83] JS：ES Module 导入导出
来源：http://dali.ppjwa.cn/Article/details/gtchqneull.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtcszfcayp.html

[U84] JS：CommonJS 写法
来源：http://dali.xinyue.icu/Article/details/gtdtvvzieb.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.tian-w.cn/Article/details/gtavujctuz.html

[U85] JS：可选链
来源：http://dali.aizwys.cn/Article/details/gtpjcfraow.html

a?.b?.c
来源：http://dali.xuetiantiany.cn/Article/details/gthujatevy.html

[U86] JS：空值合并
来源：http://dali.316326.xyz/Article/details/gtctzzbphr.html

a ?? b
来源：http://dali.nanxinkj.top/Article/details/gtoqdyeujw.html

[U87] JS：解构默认值
来源：http://dali.gogol.net.cn/Article/details/gteuqfeuaw.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gtmkcnriwe.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtlkdvlgpu.html

{ ...a, ...b }
来源：http://dali.0kj1m.cn/Article/details/gtqvcmajdp.html

[U89] JS：数组去重
来源：http://dali.yj20258.top/Article/details/gtagryuyjm.html

[...new Set(arr)]
来源：http://dali.ybcxt.top/Article/details/gtyqmzttkg.html

[U90] JS：数字数组排序
来源：http://dali.yj20258888.top/Article/details/gtmqzwhhxx.html

[...arr].sort((a, b) => a - b)
来源：http://dali.cucudq.cn/Article/details/gtptbflfmj.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtjchirtqx.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.zhiwuduotai.top/Article/details/gtgivyunev.html

[U92] JS：深拷贝
来源：http://dali.pengpengdd.cyou/Article/details/gtrlzfcrsu.html

structuredClone(obj)
来源：http://dali.jqgufenzy.top/Article/details/gtvsmnqhzl.html

[U93] JS：模板字符串
来源：http://dali.yongpay.top/Article/details/gtaepnvjii.html

`共 ${n} 条`
来源：http://dali.havefunace.top/Article/details/gtxtfemthj.html

[U94] JS：箭头函数
来源：http://dali.yj20258888.top/Article/details/gtcbgxenzg.html

const double = x => x * 2;
来源：http://dali.dianchejie.cn/Article/details/gtiqfmtmwe.html

[U95] JS：Promise 包装
来源：http://dali.chenjidiqi.icu/Article/details/gtdtmeuxsa.html

new Promise((resolve, reject) => {})
来源：http://dali.jqgfzy.top/Article/details/gtsukfiecp.html

[U96] JS：async/await 与异常
来源：http://dali.wangshuangyany.cn/Article/details/gtbdtdkzvz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.haohaochexian.top/Article/details/gtalyegafq.html

[U97] JS：并发请求
来源：http://dali.yueranfly.top/Article/details/gtsfenowue.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjvvebvx.html

[U98] JS：fetch 带 JSON
来源：http://dali.jlsjyb.cn/Article/details/gtjvdunxht.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.shzxlz.cn/Article/details/gtmykiqynw.html

[U99] JS：事件监听
来源：http://dali.gaohongyu789.top/Article/details/gtwqsphcvz.html

el.addEventListener("click", e => {})
来源：http://dali.hongshengwenyu.top/Article/details/gticfiypfx.html

[U100] JS：DOM 查询
来源：http://dali.bjfxy.top/Article/details/gtfdhzgodu.html

document.querySelector(".item")
来源：http://dali.chenzaomai.com/Article/details/gtdragkuql.html

[U101] JS：classList 操作
来源：http://dali.gotoacloud.top/Article/details/gtxfgrdfls.html

el.classList.toggle("active")
来源：http://dali.sxryk.cn/Article/details/gtcqhcikgt.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gttacspgbl.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.pengpengdd.cyou/Article/details/gtaaiintzg.html

[U103] JS：定时器
来源：http://dali.gzhubu.top/Article/details/gtvasihujq.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.dianchejie.cn/Article/details/gtzsynqunm.html

[U104] JS：防抖
来源：http://dali.yuanzhike.top/Article/details/gtuaptllxb.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.snrcjt.cn/Article/details/gtbogvumhk.html

[U105] JS：节流
来源：http://dali.hnxiangtu.top/Article/details/gtvcnqshzh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.shzxlz.cn/Article/details/gtdztjrnev.html

[U106] JS：日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtwspeyjov.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jiagoushi.top/Article/details/gtnhtikidi.html

[U107] JS：数字千分位
来源：http://dali.snrcjt.cn/Article/details/gtvlnslrtb.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.yj202588.top/Article/details/gtylosnrzy.html

[U108] JS：随机整数
来源：http://dali.meibo888.top/Article/details/gtlufbbgzi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.redwolf501.top/Article/details/gtvzuizqon.html

[U109] JS：数组分组
来源：http://dali.snrcjt.cn/Article/details/gtyiolhahk.html

Object.groupBy(arr, x => x.type)
来源：http://dali.aibaodan.cn/Article/details/gtjzjpnuxc.html

[U110] JS：数组分块
来源：http://dali.sxryk.cn/Article/details/gtojfqppko.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.gogol.net.cn/Article/details/gtzzwfkjec.html

[U111] JS：对象转 Map
来源：http://dali.guannengcc.top/Article/details/gtwhjzflgn.html

new Map(Object.entries(obj))
来源：http://dali.zhixingplan.top/Article/details/gtwgbyuidb.html

[U112] JS：字符串补位
来源：http://dali.shzxlz.cn/Article/details/gtonsafqce.html

"7".padStart(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtifafcluu.html

[U113] JS：正则替换全部
来源：http://dali.chenlongwang.top/Article/details/gtselltiyz.html

s.replaceAll("a", "b")
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnzagbza.html

[U114] JS：JSON 深比较
来源：http://dali.nanxinkj.top/Article/details/gtiwbbqfcz.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yj20258888.top/Article/details/gtluthxtqk.html

[U115] JS：生成 UUID
来源：http://dali.havefunace.top/Article/details/gtqmuhrktj.html

crypto.randomUUID()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkzpjqlfm.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.yongpay.top/Article/details/gtgkzngykc.html

/** @param {string} name */ function f(name) {}
来源：http://dali.redwolf501.top/Article/details/gtvnfobgum.html

[U117] JS：单元测试
来源：http://dali.feifeiyinyue.top/Article/details/gtutceljks.html

npm i -D vitest;  npx vitest
来源：http://dali.chenzaomai.com/Article/details/gtjijqoiff.html

[U118] JS：开发服务器
来源：http://dali.jiagoushi.top/Article/details/gtpvzpzgai.html

npm i -D vite;  npx vite
来源：http://dali.9152youxi.cn/Article/details/gtimowudwg.html

[U119] JS：生产构建
来源：http://dali.snrcjt.cn/Article/details/gtjnequsdp.html

npx vite build
来源：http://dali.meibo888.top/Article/details/gtjjtdvupx.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.aizwys.cn/Article/details/gttihvfrzc.html

import.meta.env.VITE_API_URL
来源：http://dali.xuetiantiany.cn/Article/details/gtvrydgarm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtjtzhhaxt.html

统计汇总
来源：http://dali.zhiwuduotai.top/Article/details/gtxgrzcupz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtsvbyroyv.html

按语言统计（条）：
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwijhmnex.html

Python ......... 252
来源：http://dali.yuanzhike.top/Article/details/gtlvphtieo.html

PHP ............ 252
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatypspca.html

JavaScript ..... 252
来源：http://dali.jianghu66.top/Article/details/gthkneyrcg.html

TypeScript ..... 212
来源：http://dali.cucudq.cn/Article/details/gtvxcywrug.html

Java ........... 212
来源：http://dali.zhixingplan.top/Article/details/gtfjgobhko.html

Go ............. 212
来源：http://dali.ybcxt.top/Article/details/gtyqahzpbu.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gtqvoeqdkv.html

C# ............. 212
来源：http://dali.chenzaomai.com/Article/details/gtdwvspxvw.html

C .............. 30
来源：http://dali.tian-w.cn/Article/details/gtdwxaqhpn.html

C++ ............ 30
来源：http://dali.mhx1999.top/Article/details/gtnwpeqtcv.html

SQL ............ 90
来源：http://dali.daria6918.cn/Article/details/gtsexidjur.html

Bash ........... 80
来源：http://dali.tanke756.top/Article/details/gtilykwitb.html

Kotlin ......... 15
来源：http://dali.feifeiyinyue.top/Article/details/gtbaujysvu.html

Swift .......... 15
来源：http://dali.daria6918.cn/Article/details/gtholhvtnb.html

Lua ............ 10
来源：http://dali.cucudq.cn/Article/details/gtaqopikhz.html

Perl ........... 10
来源：http://dali.daria6918.cn/Article/details/gtwmnoboac.html

Scala .......... 10
来源：http://dali.havefunace.top/Article/details/gtvpnlblhh.html

------------------------------------
来源：http://dali.c1oappe.top/Article/details/gtbnbblktt.html

合计 ........... 2106 条
来源：http://dali.gotoacloud.top/Article/details/gtkxhugfmw.html

按章节统计：
来源：http://dali.shuidangran.top/Article/details/gtwzfozezb.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yanxiufei.cn/Article/details/gtincuawtg.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.cdnleiting.top/Article/details/gtuodckbau.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.ivvv.top/Article/details/gtusyavgfy.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hysaishi.cn/Article/details/gtdjqgauyj.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.haohaochexian.top/Article/details/gthuhstepu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.shangyingyoupin.top/Article/details/gtznjvlity.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gtjwlsqoqq.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.bjfxy.top/Article/details/gtxymwmjos.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtrxejcsxx.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ppjwa.cn/Article/details/gthtgmobav.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtjnynxwxi.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.haohaochexian.top/Article/details/gtdjjuomup.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gzhubu.top/Article/details/gtbotnuckk.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.shanyushiyangkeji.top/Article/details/gtujlrzggj.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.pycfn.com/Article/details/gtoiglfcue.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.hongshengwenyu.top/Article/details/gtmoeprbqe.html

Q SQL 专题                              90
来源：http://dali.sweek.top/Article/details/gtqtlsfvmp.html

R Bash 专题                             80
来源：http://dali.svipenyu.cn/Article/details/gtgxmkmrsf.html

S C / C++ 专题                          60
来源：http://dali.yuanzhike.top/Article/details/gtrrvfcttm.html

T 其他语言补充                          60
来源：http://dali.smart0.xyz/Article/details/gtfjhphzmq.html

U 高频实用片段                         120
来源：http://dali.ppjwa.cn/Article/details/gtqvefvrul.html

------------------------------------
来源：http://dali.yongpay.top/Article/details/gtcvqilxxr.html

合计                                  2106 条
来源：http://dali.xziqi.cn/Article/details/gtyzjitorc.html

--------------------------------------------------------------------------------
来源：http://dali.yuanzhike.top/Article/details/gtrlqfyywj.html


<!-- 参考信息 -->