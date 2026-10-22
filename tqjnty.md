代发 wailian999

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.316326.xyz/Article/details/gt2aprygguo.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2cuwjcerd.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gt2yyrkjhlc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2uxdyiefx.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2xmgkbgcs.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.aizwys.cn/Article/details/gt2tbznowmv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tianlin.xyz/Article/details/gt2sprztsff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cdnleiting.top/Article/details/gt2anccykxa.html

[U03] Py：加载 .env 配置
来源：http://dali.pycfn.com/Article/details/gt2ylcbrnys.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgufenzy.top/Article/details/gt2mqidggii.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gt2zhensojs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gt2dueyqdtv.html

[U05] Py：列表去重且保序
来源：http://dali.gogol.net.cn/Article/details/gt2ybpgihhe.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gt2xagsyloo.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gt2zakwydfk.html

{**a, **b}
来源：http://dali.ivvv.top/Article/details/gt2jendndiy.html

[U07] Py：反转字典键值
来源：http://dali.yangfankeji.com/Article/details/gt2xhmqwjnf.html

{v: k for k, v in d.items()}
来源：http://dali.redwolf501.top/Article/details/gt2krewqewj.html

[U08] Py：展平二维列表
来源：http://dali.jqgfzy.top/Article/details/gt2wtvetbbv.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2adpnsxdm.html

[U09] Py：字典取最大值的键
来源：http://dali.cashguo.top/Article/details/gt2ndmgjgmk.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gt2hpxmvbjx.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gt2stslcmzo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.dianchejie.cn/Article/details/gt2spzrhrol.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gt2bewdkpzl.html

(x * 2 for x in arr)
来源：http://dali.jlsjyb.cn/Article/details/gt2qvzwsznv.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.tian-w.cn/Article/details/gt2rjkzuzkd.html

Counter(arr).most_common(3)
来源：http://dali.yj20258888.top/Article/details/gt2edafahlv.html

[U13] Py：固定长度队列
来源：http://dali.yvedp.cn/Article/details/gt2riytqvdu.html

deque(maxlen=10)
来源：http://dali.xziqi.cn/Article/details/gt2vayexbpt.html

[U14] Py：分组收集到列表
来源：http://dali.havefunace.top/Article/details/gt2lprvqvod.html

defaultdict(list)
来源：http://dali.xuanzx.com/Article/details/gt2vivhzakx.html

[U15] Py：高精度计时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2srxcpszl.html

t = time.perf_counter()
来源：http://dali.vqdsnc.cn/Article/details/gt2ujtgvnos.html

[U16] Py：命令行参数解析
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nnfuimkj.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gt2aksfteqr.html

[U17] Py：初始化日志
来源：http://dali.andypj.xyz/Article/details/gt2zzeyhkgg.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.fengsongda.top/Article/details/gt2skjbpdun.html

[U18] Py：预编译正则
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqobusew.html

pat = re.compile(r"\d+")
来源：http://dali.gotoacloud.top/Article/details/gt2mchlmiuu.html

[U19] Py：正则替换带回调
来源：http://dali.nanxinkj.top/Article/details/gt2xahjsosv.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.daria6918.cn/Article/details/gt2lhqobxvd.html

[U20] Py：缓存函数结果
来源：http://dali.nanxuanxn.top/Article/details/gt2lfsrywsy.html

@functools.lru_cache(maxsize=None)
来源：http://dali.guowangkeji.top/Article/details/gt2mhvcdgiw.html

[U21] Py：自定义上下文管理器
来源：http://dali.jyoumei.cn/Article/details/gt2dxumnbtx.html

@contextlib.contextmanager
来源：http://dali.nwbrower.top/Article/details/gt2fzgchbxj.html

[U22] Py：矩阵转置
来源：http://dali.jqgfzy.top/Article/details/gt2tmrizktb.html

list(zip(*m))
来源：http://dali.zhoulong.xyz/Article/details/gt2szwknwze.html

[U23] Py：分块读取大文件
来源：http://dali.xinyue.icu/Article/details/gt2rgqskvnk.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.haohaochexian.top/Article/details/gt2inxgotpl.html

[U24] Py：路径操作
来源：http://dali.xuetiantiany.cn/Article/details/gt2cnknyijt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.xinyue.icu/Article/details/gt2edpimdlp.html

[U25] Py：CSV 按字典读
来源：http://dali.bjfxy.top/Article/details/gt2gmzszwqq.html

csv.DictReader(f)
来源：http://dali.wangdashe.top/Article/details/gt2tqfmtcfd.html

[U26] Py：并发下载
来源：http://dali.quarkkingdee.top/Article/details/gt2tqxqdsqh.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ptzwmzea.html

[U27] Py：异步 HTTP
来源：http://dali.nanxinkj.top/Article/details/gt2fjstqmmz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.gogol.net.cn/Article/details/gt2zbncmede.html

[U28] Py：类型别名
来源：http://dali.c1oappe.top/Article/details/gt2drrqmjfg.html

UserId = int
来源：http://dali.hysaishi.cn/Article/details/gt2exhpcdmd.html

[U29] Py：属性校验
来源：http://dali.cucudq.cn/Article/details/gt2pvpeiawg.html

@property 与 @x.setter 配合
来源：http://dali.yj20258.top/Article/details/gt2vsbfakpp.html

[U30] Py：数据类
来源：http://dali.daxiang520.top/Article/details/gt2vaomumgp.html

@dataclass(slots=True)
来源：http://dali.cashguo.top/Article/details/gt2dgutryed.html

[U31] Py：单测
来源：http://dali.xuanzx.com/Article/details/gt2ibcdlfci.html

python -m pytest -q
来源：http://dali.hnqzz.top/Article/details/gt2ckpctpan.html

[U32] Py：代码格式化
来源：http://dali.haohaochexian.top/Article/details/gt2evlgfpvu.html

ruff format . && ruff check --fix .
来源：http://dali.sweek.top/Article/details/gt2vmljbgjo.html

[U33] Py：打包发布
来源：http://dali.316326.xyz/Article/details/gt2jcbfcdkw.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.svipenyu.cn/Article/details/gt2fiacmskk.html

[U34] Py：判断编码
来源：http://dali.yanxiufei.cn/Article/details/gt2bcswjwqs.html

chardet.detect(raw)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jvvtdpyt.html

[U35] Py：发送邮件
来源：http://dali.yanxiufei.cn/Article/details/gt2tjltqxrp.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhixingplan.top/Article/details/gt2xmhwepcr.html

[U36] Py：定时任务
来源：http://dali.tianlin.xyz/Article/details/gt2hcrgbfyz.html

schedule.every(10).minutes.do(job)
来源：http://dali.zdqjudy.top/Article/details/gt2kticmxzf.html

[U37] Py：读写 Excel
来源：http://dali.cheryme.top/Article/details/gt2lsivolcl.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yj202588.top/Article/details/gt2iwhtipdr.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gt2ngrtgvun.html

Path(__file__).resolve().parent
来源：http://dali.cashguo.top/Article/details/gt2isexonku.html

[U39] Py：判断是否在交互环境
来源：http://dali.nanxinkj.top/Article/details/gt2pejbywsi.html

sys.stdout.isatty()
来源：http://dali.hnxiangtu.top/Article/details/gt2xkllqdkj.html

[U40] Py：打印到标准错误
来源：http://dali.yanxiufei.cn/Article/details/gt2uyxpdduc.html

print("err", file=sys.stderr)
来源：http://dali.yueranfly.top/Article/details/gt2cysglmjn.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.dashuyun.cn/Article/details/gt2qwxiwdcd.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gt2hrrngxab.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.vqdsnc.cn/Article/details/gt2ugrpnhfq.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.mhx1999.top/Article/details/gt2ckcmmmre.html

[U43] PHP：声明命名空间
来源：http://dali.fengsongda.top/Article/details/gt2pnsphist.html

namespace App\Http;
来源：http://dali.chenzaomai.com/Article/details/gt2hxjtzhdz.html

[U44] PHP：开启严格类型
来源：http://dali.shuidangran.top/Article/details/gt2ulqojvil.html

declare(strict_types=1);
来源：http://dali.andypj.xyz/Article/details/gt2ragrzheg.html

[U45] PHP：类型声明与返回类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2cnbdxplu.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rnzkmyjb.html

[U46] PHP：可空类型
来源：http://dali.ybcxt.top/Article/details/gt2ktukmyyz.html

?string $name = null
来源：http://dali.hnqzz.top/Article/details/gt2vnvzgsmj.html

[U47] PHP：联合类型
来源：http://dali.meibo888.top/Article/details/gt2fljwifpz.html

int|string $id
来源：http://dali.meibo888.top/Article/details/gt2xmcimpxd.html

[U48] PHP：纯枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtbrdowa.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gt2dronnpgk.html

[U49] PHP：只读属性
来源：http://dali.sysykeji.top/Article/details/gt2ujcgtgiv.html

public readonly string $name
来源：http://dali.jqgufenzy.top/Article/details/gt2lnaiyler.html

[U50] PHP：构造器属性提升
来源：http://dali.jiagoushi.top/Article/details/gt2wxvpoyjz.html

public function __construct(private int $id) {}
来源：http://dali.gotoacloud.top/Article/details/gt2rqtkuxvt.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gt2ruudpfuz.html

[$a, $b] = $arr;
来源：http://dali.jinqigufen.top/Article/details/gt2nkhwoyob.html

[U52] PHP：箭头函数
来源：http://dali.sxryk.cn/Article/details/gt2gxqwxmiq.html

$double = fn($x) => $x * 2;
来源：http://dali.vqdsnc.cn/Article/details/gt2thltospa.html

[U53] PHP：空合并运算符
来源：http://dali.aizwys.cn/Article/details/gt2ppifhqna.html

$v = $a ?? $b ?? "default";
来源：http://dali.bjfxy.top/Article/details/gt2tlhbmxbh.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gt2bwlbuldf.html

$obj?->method()
来源：http://dali.sweek.top/Article/details/gt2lbumhpwp.html

[U55] PHP：match 表达式
来源：http://dali.hammf.cn/Article/details/gt2vxbafbcg.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gt2pvkzagzt.html

[U56] PHP：命名参数
来源：http://dali.jinqigufen.top/Article/details/gt2jfquifrn.html

f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gt2jhsmzres.html

[U57] PHP：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gt2rzajcwol.html

"值: {$a}"
来源：http://dali.mhx1999.top/Article/details/gt2tndpctpv.html

[U58] PHP：数组三件套
来源：http://dali.pengpengdd.cyou/Article/details/gt2ybutefwi.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ojmncpxd.html

[U59] PHP：自定义排序
来源：http://dali.jqgfzy.top/Article/details/gt2apyqbjed.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qxeghzic.html

[U60] PHP：JSON 编解码
来源：http://dali.tanke756.top/Article/details/gt2eqcnvswh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nwbrower.top/Article/details/gt2mvjnranh.html

[U61] PHP：正则
来源：http://dali.zhiwuduotai.top/Article/details/gt2gqbnxeki.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2zchsegik.html

[U62] PHP：日期对象
来源：http://dali.xziqi.cn/Article/details/gt2zfhvfwbg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yuxming.cn/Article/details/gt2crivwfga.html

[U63] PHP：文件读写
来源：http://dali.fzhhl.top/Article/details/gt2siwbjbtp.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ehwqpu.com/Article/details/gt2ztlntsun.html

[U64] PHP：目录遍历
来源：http://dali.ppjwa.cn/Article/details/gt2yanuzjwr.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.ydzc1.top/Article/details/gt2ldipuebo.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gt2xcasweyf.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2vnrgeaor.html

[U66] PHP：设置 Cookie
来源：http://dali.gaohongyu789.top/Article/details/gt2uehgvrwp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.svipenyu.cn/Article/details/gt2ifcduosr.html

[U67] PHP：处理文件上传
来源：http://dali.yangfankeji.com/Article/details/gt2tabefcer.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.kuanghao11.cn/Article/details/gt2bffvkkfd.html

[U68] PHP：PDO 连接
来源：http://dali.gogol.net.cn/Article/details/gt2gwwwmais.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.yanxiufei.cn/Article/details/gt2bxudtzph.html

[U69] PHP：PDO 预处理
来源：http://dali.snrcjt.cn/Article/details/gt2agghvewp.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ybcxt.top/Article/details/gt2sqzfinlc.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cnaykzgz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yvedp.cn/Article/details/gt2yfsshgfj.html

[U71] PHP：抛出异常
来源：http://dali.yuxming.cn/Article/details/gt2hjtaukka.html

throw new RuntimeException("失败", 500);
来源：http://dali.chenlongwang.top/Article/details/gt2htobzuwu.html

[U72] PHP：写错误日志
来源：http://dali.bjfxy.top/Article/details/gt2dnhabtfr.html

error_log("失败: " . $e->getMessage());
来源：http://dali.yueranfly.top/Article/details/gt2hccdnhwf.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gt2uuahexho.html

parse_ini_file("config.ini", true)
来源：http://dali.jlsjyb.cn/Article/details/gt2yvuoxuuw.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2mtaprkkr.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jinqigfzy.top/Article/details/gt2sptarivj.html

[U75] PHP：依赖注入
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tccsgltm.html

composer require psr/container
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tnvobxcn.html

[U76] PHP：简单路由
来源：http://dali.jianghu66.top/Article/details/gt2eboozwua.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.zhongyouzk.top/Article/details/gt2qfwbkojf.html

[U77] PHP：模板渲染
来源：http://dali.tian-w.cn/Article/details/gt2jxwegyjw.html

composer require twig/twig
来源：http://dali.kuanghao11.cn/Article/details/gt2cirbexnu.html

[U78] PHP：单元测试
来源：http://dali.yangfankeji.com/Article/details/gt2oedyaoro.html

composer require --dev phpunit/phpunit
来源：http://dali.iojbl.cn/Article/details/gt2xeyddqna.html

[U79] PHP：静态分析
来源：http://dali.birdmap.top/Article/details/gt2vbeggphf.html

composer require --dev phpstan/phpstan
来源：http://dali.gotoacloud.top/Article/details/gt2vqnpvzdx.html

[U80] PHP：代码规范修复
来源：http://dali.yueranfly.top/Article/details/gt2xclzttgx.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.xuanzx.com/Article/details/gt2zrsxtjuv.html

[U81] JS：初始化项目
来源：http://dali.xinyue.icu/Article/details/gt2ynlroitq.html

npm init -y;  npm i express
来源：http://dali.vqdsnc.cn/Article/details/gt2zxfcyqji.html

[U82] JS：package.json 脚本
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vlytpwva.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.jqgufenzy.top/Article/details/gt2amxjhueo.html

[U83] JS：ES Module 导入导出
来源：http://dali.ydzc1.top/Article/details/gt2mewxekic.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ivvv.top/Article/details/gt2kqhpiuhw.html

[U84] JS：CommonJS 写法
来源：http://dali.daxiang520.top/Article/details/gt2ecqdulny.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yueranfly.top/Article/details/gt2vvrmgxwj.html

[U85] JS：可选链
来源：http://dali.c1oappe.top/Article/details/gt2cktkgskm.html

a?.b?.c
来源：http://dali.birdmap.top/Article/details/gt2eoydogev.html

[U86] JS：空值合并
来源：http://dali.meibo888.top/Article/details/gt2hfeagfvl.html

a ?? b
来源：http://dali.hongshengwenyu.top/Article/details/gt2lnevhgfc.html

[U87] JS：解构默认值
来源：http://dali.chenzaomai.com/Article/details/gt2aeotyyne.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yanxiufei.cn/Article/details/gt2qxkshlvm.html

[U88] JS：对象展开合并
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgyoctrh.html

{ ...a, ...b }
来源：http://dali.birdmap.top/Article/details/gt2ukmpamzh.html

[U89] JS：数组去重
来源：http://dali.chenlongwang.top/Article/details/gt2otzyplmx.html

[...new Set(arr)]
来源：http://dali.yongpay.top/Article/details/gt2yfuxutyd.html

[U90] JS：数字数组排序
来源：http://dali.sweek.top/Article/details/gt2abvqmnpu.html

[...arr].sort((a, b) => a - b)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ybfahazr.html

[U91] JS：对象键值遍历
来源：http://dali.sufxvd.cn/Article/details/gt2beaosiya.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.smart0.xyz/Article/details/gt2rilyukky.html

[U92] JS：深拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gt2slhtmain.html

structuredClone(obj)
来源：http://dali.sufxvd.cn/Article/details/gt2gfaxagwz.html

[U93] JS：模板字符串
来源：http://dali.guowangkeji.top/Article/details/gt2ntrfmcta.html

`共 ${n} 条`
来源：http://dali.sweek.top/Article/details/gt2fofhkkwd.html

[U94] JS：箭头函数
来源：http://dali.zhixingplan.top/Article/details/gt2cejenxyl.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gt2clnewolr.html

[U95] JS：Promise 包装
来源：http://dali.yj20258888.top/Article/details/gt2lfjhjpoz.html

new Promise((resolve, reject) => {})
来源：http://dali.bjfxy.top/Article/details/gt2kagfgaux.html

[U96] JS：async/await 与异常
来源：http://dali.316326.xyz/Article/details/gt2wloozpaz.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.andypj.xyz/Article/details/gt2kcgepljo.html

[U97] JS：并发请求
来源：http://dali.bjfxy.top/Article/details/gt2kybszzga.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ispcgkrb.html

[U98] JS：fetch 带 JSON
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ocluhpnx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sweek.top/Article/details/gt2vjhhndyp.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gt2xppgdnzt.html

el.addEventListener("click", e => {})
来源：http://dali.fzhhl.top/Article/details/gt2glpclgmi.html

[U100] JS：DOM 查询
来源：http://dali.zycfv.cn/Article/details/gt2xduczxsc.html

document.querySelector(".item")
来源：http://dali.nanxinkj.top/Article/details/gt2klmwhpgj.html

[U101] JS：classList 操作
来源：http://dali.zhoulong.xyz/Article/details/gt2jprbnxdn.html

el.classList.toggle("active")
来源：http://dali.nanxinkj.top/Article/details/gt2borjszxu.html

[U102] JS：本地存储
来源：http://dali.shangyingyoupin.top/Article/details/gt2crgsjxql.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zdqjudy.top/Article/details/gt2frljtkpw.html

[U103] JS：定时器
来源：http://dali.svipenyu.cn/Article/details/gt2kcyekzst.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.nanxinkj.top/Article/details/gt2uqogffqi.html

[U104] JS：防抖
来源：http://dali.guannengcc.top/Article/details/gt2mnbxbukq.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.aizwys.cn/Article/details/gt2nvhoqbbw.html

[U105] JS：节流
来源：http://dali.bjfxy.top/Article/details/gt2lsxgrncj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.gotoacloud.top/Article/details/gt2euhklkdz.html

[U106] JS：日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gt2qdmfjfeu.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.cqqwz.cn/Article/details/gt2apopomvb.html

[U107] JS：数字千分位
来源：http://dali.cqqwz.cn/Article/details/gt2imhwghjj.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.316326.xyz/Article/details/gt2hxzeatow.html

[U108] JS：随机整数
来源：http://dali.smart0.xyz/Article/details/gt2mijqrodl.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.zhiwuduotai.top/Article/details/gt2duhjxuht.html

[U109] JS：数组分组
来源：http://dali.gzhubu.top/Article/details/gt2ibowsslq.html

Object.groupBy(arr, x => x.type)
来源：http://dali.mhx1999.top/Article/details/gt2rapymjkt.html

[U110] JS：数组分块
来源：http://dali.xylfe.cn/Article/details/gt2unhiegsb.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.vqdsnc.cn/Article/details/gt2yrezosbd.html

[U111] JS：对象转 Map
来源：http://dali.ybcxt.top/Article/details/gt2xyfirtab.html

new Map(Object.entries(obj))
来源：http://dali.yj202588.top/Article/details/gt2gbfwwoxa.html

[U112] JS：字符串补位
来源：http://dali.tian-w.cn/Article/details/gt2zzgpgmcb.html

"7".padStart(3, "0")
来源：http://dali.jiagoushi.top/Article/details/gt2muwhbyqn.html

[U113] JS：正则替换全部
来源：http://dali.birdmap.top/Article/details/gt2pdvotodi.html

s.replaceAll("a", "b")
来源：http://dali.pycfn.com/Article/details/gt2smflkkay.html

[U114] JS：JSON 深比较
来源：http://dali.c1oappe.top/Article/details/gt2hkhdyggj.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zhongyouzk.top/Article/details/gt2iymufddz.html

[U115] JS：生成 UUID
来源：http://dali.jiagoushi.top/Article/details/gt2zwrglrjj.html

crypto.randomUUID()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxvgmwhz.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ehwqpu.com/Article/details/gt2hgxhdogv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2alnlccje.html

[U117] JS：单元测试
来源：http://dali.tian-w.cn/Article/details/gt2tiubswdl.html

npm i -D vitest;  npx vitest
来源：http://dali.aibaodan.cn/Article/details/gt2srdtoezf.html

[U118] JS：开发服务器
来源：http://dali.iojbl.cn/Article/details/gt2figqploi.html

npm i -D vite;  npx vite
来源：http://dali.shuidangran.top/Article/details/gt2ztfszjzq.html

[U119] JS：生产构建
来源：http://dali.bjfxy.top/Article/details/gt2qetkdajt.html

npx vite build
来源：http://dali.yongpay.top/Article/details/gt2vqklejtw.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.sweek.top/Article/details/gt2gpgypihx.html

import.meta.env.VITE_API_URL
来源：http://dali.vqdsnc.cn/Article/details/gt2httuybkg.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2fblzxtmk.html

统计汇总
来源：http://dali.daxiang520.top/Article/details/gt2mlumezgi.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gt2tioviktn.html

按语言统计（条）：
来源：http://dali.shuidangran.top/Article/details/gt2mfarinzz.html

Python ......... 252
来源：http://dali.yj202588.top/Article/details/gt2kpleuwvm.html

PHP ............ 252
来源：http://dali.haohaochexian.top/Article/details/gt2vumphfxo.html

JavaScript ..... 252
来源：http://dali.jqgfzy.top/Article/details/gt2anefmvjp.html

TypeScript ..... 212
来源：http://dali.mhx1999.top/Article/details/gt2yxfxdsfl.html

Java ........... 212
来源：http://dali.redwolf501.top/Article/details/gt2shopopuh.html

Go ............. 212
来源：http://dali.chenzaomai.com/Article/details/gt2cpzrztay.html

Ruby ........... 212
来源：http://dali.ppjwa.cn/Article/details/gt2dfayjylf.html

C# ............. 212
来源：http://dali.birdmap.top/Article/details/gt2ilzqrzek.html

C .............. 30
来源：http://dali.jqgfzy.top/Article/details/gt2yxyevybr.html

C++ ............ 30
来源：http://dali.hnqzz.top/Article/details/gt2yzmvefbq.html

SQL ............ 90
来源：http://dali.birdmap.top/Article/details/gt2ipuckeki.html

Bash ........... 80
来源：http://dali.xziqi.cn/Article/details/gt2nwjukwwf.html

Kotlin ......... 15
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ofgqaeas.html

Swift .......... 15
来源：http://dali.fengsongda.top/Article/details/gt2aysfhvml.html

Lua ............ 10
来源：http://dali.9152youxi.cn/Article/details/gt2nezvqywd.html

Perl ........... 10
来源：http://dali.nanxinkj.top/Article/details/gt2gfglilnr.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gt2eyovbbsz.html

------------------------------------
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pmjpguvf.html

合计 ........... 2106 条
来源：http://dali.kuanghao11.cn/Article/details/gt2lpdjawgd.html

按章节统计：
来源：http://dali.ppjwa.cn/Article/details/gt2jfndfvbz.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.sxryk.cn/Article/details/gt2lwszrkom.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.nwbrower.top/Article/details/gt2twhrplyg.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.dianchejie.cn/Article/details/gt2qqryapvg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.havefunace.top/Article/details/gt2wdyvcoof.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.dianchejie.cn/Article/details/gt2kflsubff.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.chenjidiqi.icu/Article/details/gt2gavrzhol.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yonumen.top/Article/details/gt2naogfwhc.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.cashguo.top/Article/details/gt2aaxijbfa.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.iojbl.cn/Article/details/gt2cscmdzgl.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.aizwys.cn/Article/details/gt2bivzsgin.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.nanxuanxn.top/Article/details/gt2eubgrklq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2xbmxbull.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.gogol.net.cn/Article/details/gt2yqkglnjv.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.jyoumei.cn/Article/details/gt2uhootusc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.quarkkingdee.top/Article/details/gt2ziknbyud.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.tanke756.top/Article/details/gt2efuzrssi.html

Q SQL 专题                              90
来源：http://dali.xuetiantiany.cn/Article/details/gt2vgwkytcd.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnnzujem.html

S C / C++ 专题                          60
来源：http://dali.haohaochexian.top/Article/details/gt2mykusvsd.html

T 其他语言补充                          60
来源：http://dali.xuanzx.com/Article/details/gt2nkynyxvs.html

U 高频实用片段                         120
来源：http://dali.xuanzx.com/Article/details/gt2udovqtwb.html

------------------------------------
来源：http://dali.hysaishi.cn/Article/details/gt2yezxjuew.html

合计                                  2106 条
来源：http://dali.sweek.top/Article/details/gt2rpulrxdz.html

--------------------------------------------------------------------------------
来源：http://dali.yj20258.top/Article/details/gt2mikaqmxy.html

使用提醒
来源：http://dali.yongpay.top/Article/details/gt2ibygkilt.html

--------------------------------------------------------------------------------
来源：http://dali.zhijiandao.cn/Article/details/gt2yivojnhe.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.cheryme.top/Article/details/gt2ehwhrehr.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.mhx1999.top/Article/details/gt2ndqmgvdp.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.guannengcc.top/Article/details/gt2aqdhprwe.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.ybcxt.top/Article/details/gt2cimkdufa.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gogol.net.cn/Article/details/gt2pnonjedc.html

—— 文件结束 ——
来源：http://dali.yuxming.cn/Article/details/gt2yllwzdpn.html


<!-- 参考信息 -->