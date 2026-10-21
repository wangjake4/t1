代发 wailian999

case class User(name: String, age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtyomaleun.html

[T57] Scala：模式匹配
来源：http://dali.zycfv.cn/Article/details/gthdvfrwcu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtlruryvkv.html

[T58] Scala：函数定义
来源：http://dali.guowangkeji.top/Article/details/gtfxdxiflr.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dashuyun.cn/Article/details/gteikjzznu.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtrxajysdw.html

for (i <- 1 to 10) println(i)
来源：http://dali.hammf.cn/Article/details/gtbyzrnjwz.html

[T60] Scala：折叠
来源：http://dali.jiagoushi.top/Article/details/gtzqflgfld.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jiagoushi.top/Article/details/gtvijisrix.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gttsukjrwl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.nanxinkj.top/Article/details/gtybyewwfe.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtychjckqb.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gtlgrkiqzl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gteucmzsgv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtjzgqvvkd.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtmahslmhu.html

[U03] Py：加载 .env 配置
来源：http://dali.dianchejie.cn/Article/details/gtopkoxefe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sysykeji.top/Article/details/gtyurncsre.html

[U04] Py：变量调试打印
来源：http://dali.shuidangran.top/Article/details/gtybtkawxv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjvwpnie.html

[U05] Py：列表去重且保序
来源：http://dali.zdqjudy.top/Article/details/gtruupmxps.html

list(dict.fromkeys(arr))
来源：http://dali.hongshengwenyu.top/Article/details/gtsgysygrt.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtbqpbyhgh.html

{**a, **b}
来源：http://dali.xuetiantiany.cn/Article/details/gtgsydvqwd.html

[U07] Py：反转字典键值
来源：http://dali.fzhhl.top/Article/details/gtcvvgwshp.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtvzvydcyc.html

[U08] Py：展平二维列表
来源：http://dali.aibaodan.cn/Article/details/gtuucdwuqz.html

[y for x in nested for y in x]
来源：http://dali.ydzc1.top/Article/details/gtlfmeyido.html

[U09] Py：字典取最大值的键
来源：http://dali.mhx1999.top/Article/details/gtjtaksdhn.html

max(d, key=d.get)
来源：http://dali.guowangkeji.top/Article/details/gtfhlkqqno.html

[U10] Py：按值排序字典
来源：http://dali.zhoulong.xyz/Article/details/gtagawrwbd.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.cucudq.cn/Article/details/gtexlukflf.html

[U11] Py：生成器表达式
来源：http://dali.hysaishi.cn/Article/details/gtofsfampr.html

(x * 2 for x in arr)
来源：http://dali.redwolf501.top/Article/details/gtsavohwpj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jiagoushi.top/Article/details/gtudairwfc.html

Counter(arr).most_common(3)
来源：http://dali.dashuyun.cn/Article/details/gtdnukbvay.html

[U13] Py：固定长度队列
来源：http://dali.bjfxy.top/Article/details/gtjtxliovv.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtzxxjrmxo.html

[U14] Py：分组收集到列表
来源：http://dali.quarkkingdee.top/Article/details/gtmrjoyvrz.html

defaultdict(list)
来源：http://dali.zhixingplan.top/Article/details/gtdvikaohk.html

[U15] Py：高精度计时
来源：http://dali.yuanzhike.top/Article/details/gtphdfsaaq.html

t = time.perf_counter()
来源：http://dali.chenlongwang.top/Article/details/gtjhlexgeg.html

[U16] Py：命令行参数解析
来源：http://dali.yongpay.top/Article/details/gtpyobnfyl.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.jianghu66.top/Article/details/gtxlhajkxc.html

[U17] Py：初始化日志
来源：http://dali.zhixingplan.top/Article/details/gtumtuhejr.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.cucudq.cn/Article/details/gtgxuipoqm.html

[U18] Py：预编译正则
来源：http://dali.chenzaomai.com/Article/details/gtqnalhpbp.html

pat = re.compile(r"\d+")
来源：http://dali.yj20258.top/Article/details/gtumtgizpi.html

[U19] Py：正则替换带回调
来源：http://dali.nanxuanxn.top/Article/details/gtkwvkodex.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwvgcliqd.html

[U20] Py：缓存函数结果
来源：http://dali.quarkkingdee.top/Article/details/gtbvinhafb.html

@functools.lru_cache(maxsize=None)
来源：http://dali.chenjidiqi.icu/Article/details/gtmfmkazwb.html

[U21] Py：自定义上下文管理器
来源：http://dali.daxiang520.top/Article/details/gtymvkwmrj.html

@contextlib.contextmanager
来源：http://dali.yj202588.top/Article/details/gtnuzffqbk.html

[U22] Py：矩阵转置
来源：http://dali.hfpthk.cn/Article/details/gtaenuimes.html

list(zip(*m))
来源：http://dali.zycfv.cn/Article/details/gtuhgcitbj.html

[U23] Py：分块读取大文件
来源：http://dali.hammf.cn/Article/details/gthdknscty.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.zycfv.cn/Article/details/gtqhbbymil.html

[U24] Py：路径操作
来源：http://dali.wangshuangyany.cn/Article/details/gttwajzmrz.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtnrxmwyei.html

[U25] Py：CSV 按字典读
来源：http://dali.gogol.net.cn/Article/details/gtttipzbhj.html

csv.DictReader(f)
来源：http://dali.zhixingplan.top/Article/details/gtdjsmyqxp.html

[U26] Py：并发下载
来源：http://dali.xinyue.icu/Article/details/gtzhybpxyd.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.redwolf501.top/Article/details/gtomthlahh.html

[U27] Py：异步 HTTP
来源：http://dali.yonumen.top/Article/details/gtsvigbdcg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.guowangkeji.top/Article/details/gtrhdskvxt.html

[U28] Py：类型别名
来源：http://dali.hysaishi.cn/Article/details/gthsaauuny.html

UserId = int
来源：http://dali.yanxiufei.cn/Article/details/gtywxvijut.html

[U29] Py：属性校验
来源：http://dali.quarkkingdee.top/Article/details/gtsfytwemu.html

@property 与 @x.setter 配合
来源：http://dali.yj202588.top/Article/details/gtbmrrupmv.html

[U30] Py：数据类
来源：http://dali.xziqi.cn/Article/details/gthdhvjtej.html

@dataclass(slots=True)
来源：http://dali.yj202588.top/Article/details/gtrckvbwtx.html

[U31] Py：单测
来源：http://dali.mhx1999.top/Article/details/gteduuuzjp.html

python -m pytest -q
来源：http://dali.ppjwa.cn/Article/details/gtbuydpfzw.html

[U32] Py：代码格式化
来源：http://dali.316326.xyz/Article/details/gtqgsiqhdr.html

ruff format . && ruff check --fix .
来源：http://dali.yj20258.top/Article/details/gtydajwese.html

[U33] Py：打包发布
来源：http://dali.aizwys.cn/Article/details/gtpnyehfbn.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.dianchejie.cn/Article/details/gtsyjkvodj.html

[U34] Py：判断编码
来源：http://dali.ivvv.top/Article/details/gtkspmbzjo.html

chardet.detect(raw)
来源：http://dali.jlsjyb.cn/Article/details/gtjqbpjvfh.html

[U35] Py：发送邮件
来源：http://dali.dianchejie.cn/Article/details/gthueafhng.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.xuetiantiany.cn/Article/details/gtulgyuhbj.html

[U36] Py：定时任务
来源：http://dali.smart0.xyz/Article/details/gtgjvftnye.html

schedule.every(10).minutes.do(job)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkirvrue.html

[U37] Py：读写 Excel
来源：http://dali.fzhhl.top/Article/details/gtzwnfxadm.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.nwbrower.top/Article/details/gtwooxptht.html

[U38] Py：获取脚本所在目录
来源：http://dali.nanxuanxn.top/Article/details/gtiipwoaqg.html

Path(__file__).resolve().parent
来源：http://dali.xziqi.cn/Article/details/gtlpxsiclr.html

[U39] Py：判断是否在交互环境
来源：http://dali.birdmap.top/Article/details/gtjgdaahan.html

sys.stdout.isatty()
来源：http://dali.sweek.top/Article/details/gteecpdpdh.html

[U40] Py：打印到标准错误
来源：http://dali.dianchejie.cn/Article/details/gtdtdzftor.html

print("err", file=sys.stderr)
来源：http://dali.guannengcc.top/Article/details/gtliuzdros.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.tanke756.top/Article/details/gtdgqriifj.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xuanzx.com/Article/details/gtongesikz.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.cdnleiting.top/Article/details/gtotubdoxp.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.redwolf501.top/Article/details/gtsiftcwpl.html

[U43] PHP：声明命名空间
来源：http://dali.haohaochexian.top/Article/details/gtbwhdxenc.html

namespace App\Http;
来源：http://dali.yongpay.top/Article/details/gtrxxetfvd.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtuoeswjqr.html

declare(strict_types=1);
来源：http://dali.jqgfzy.top/Article/details/gtgnasxvzp.html

[U45] PHP：类型声明与返回类型
来源：http://dali.pycfn.com/Article/details/gtdvbvrfny.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gthjsdmnqs.html

[U46] PHP：可空类型
来源：http://dali.jiagoushi.top/Article/details/gtvrgplolw.html

?string $name = null
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcguusell.html

[U47] PHP：联合类型
来源：http://dali.zhoulong.xyz/Article/details/gtwncosgfu.html

int|string $id
来源：http://dali.pycfn.com/Article/details/gtiyajezoq.html

[U48] PHP：纯枚举
来源：http://dali.dashuyun.cn/Article/details/gtoayqhhfe.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.nanxinkj.top/Article/details/gthmydaezv.html

[U49] PHP：只读属性
来源：http://dali.hywenlv.cn/Article/details/gtdwcsbvlm.html

public readonly string $name
来源：http://dali.feifeiyinyue.top/Article/details/gtvbzstajo.html

[U50] PHP：构造器属性提升
来源：http://dali.wangshuangyany.cn/Article/details/gtjssoabpz.html

public function __construct(private int $id) {}
来源：http://dali.daxiang520.top/Article/details/gtlpqlugui.html

[U51] PHP：数组解构
来源：http://dali.hammf.cn/Article/details/gtzhenkjzm.html

[$a, $b] = $arr;
来源：http://dali.nanxuanxn.top/Article/details/gtagfjvubm.html

[U52] PHP：箭头函数
来源：http://dali.hnqzz.top/Article/details/gtkndjeemn.html

$double = fn($x) => $x * 2;
来源：http://dali.yj202588.top/Article/details/gtlewaueui.html

[U53] PHP：空合并运算符
来源：http://dali.ywan-chungtsiang.top/Article/details/gtskfdeptl.html

$v = $a ?? $b ?? "default";
来源：http://dali.yueranfly.top/Article/details/gtyysvemjg.html

[U54] PHP：空安全调用
来源：http://dali.pengpengdd.cyou/Article/details/gtveffflqs.html

$obj?->method()
来源：http://dali.havefunace.top/Article/details/gtfwqflhue.html

[U55] PHP：match 表达式
来源：http://dali.jyoumei.cn/Article/details/gtgaaexxit.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.jqgufenzy.top/Article/details/gtwfarfhml.html

[U56] PHP：命名参数
来源：http://dali.yangfankeji.com/Article/details/gtawojkjto.html

f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtipugewpw.html

[U57] PHP：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtgonrmjcp.html

"值: {$a}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtkuxopwyy.html

[U58] PHP：数组三件套
来源：http://dali.sweek.top/Article/details/gttyzljwib.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.c1oappe.top/Article/details/gtnwlsvonn.html

[U59] PHP：自定义排序
来源：http://dali.shangyingyoupin.top/Article/details/gtyxkfnoio.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xuetiantiany.cn/Article/details/gtrdhwxqkx.html

[U60] PHP：JSON 编解码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttuxdackc.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpcafmubh.html

[U61] PHP：正则
来源：http://dali.jianghu66.top/Article/details/gtwysrwrfg.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.jqgufenzy.top/Article/details/gtiowanydq.html

[U62] PHP：日期对象
来源：http://dali.guowangkeji.top/Article/details/gtbssrjhij.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.hnqzz.top/Article/details/gtursqhbvl.html

[U63] PHP：文件读写
来源：http://dali.hysaishi.cn/Article/details/gtbmjsesvi.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.xinyue.icu/Article/details/gtpbtivaxb.html

[U64] PHP：目录遍历
来源：http://dali.tian-w.cn/Article/details/gtvbbhoyye.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sysykeji.top/Article/details/gtoousbsnt.html

[U65] PHP：会话
来源：http://dali.fengsongda.top/Article/details/gtfpgegpos.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtgkhzzzuk.html

[U66] PHP：设置 Cookie
来源：http://dali.yj20258888.top/Article/details/gtszkzvbdt.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.c1oappe.top/Article/details/gtrerfflma.html

[U67] PHP：处理文件上传
来源：http://dali.9152youxi.cn/Article/details/gttkaavsvb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.xuetiantiany.cn/Article/details/gtlcnsbmym.html

[U68] PHP：PDO 连接
来源：http://dali.cheryme.top/Article/details/gterulgguu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.redwolf501.top/Article/details/gtrftbleuq.html

[U69] PHP：PDO 预处理
来源：http://dali.tianlin.xyz/Article/details/gthmcgmwrr.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ydzc1.top/Article/details/gtwuxapniq.html

[U70] PHP：PDO 事务
来源：http://dali.jinghuilouyu.cn/Article/details/gtmtpvoqvp.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.jyoumei.cn/Article/details/gtzvwsufkj.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtoiigpyqk.html

throw new RuntimeException("失败", 500);
来源：http://dali.guannengcc.top/Article/details/gtrgsjrdhk.html

[U72] PHP：写错误日志
来源：http://dali.sweek.top/Article/details/gtvddimwdb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.quarkkingdee.top/Article/details/gtedqawqsa.html

[U73] PHP：读取 ini 配置
来源：http://dali.316326.xyz/Article/details/gthmlxbcgz.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtbrzmtmyo.html

[U74] PHP：读取环境变量
来源：http://dali.pycfn.com/Article/details/gtkpiaykqc.html

getenv("APP_ENV") ?: "production"
来源：http://dali.gotoacloud.top/Article/details/gttaxzfmiy.html

[U75] PHP：依赖注入
来源：http://dali.zdqjudy.top/Article/details/gtprwgindk.html

composer require psr/container
来源：http://dali.wangdashe.top/Article/details/gtzjrmfifm.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtneapnxdn.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.dashuyun.cn/Article/details/gtkmrtrhjc.html

[U77] PHP：模板渲染
来源：http://dali.cucudq.cn/Article/details/gtmcogekho.html

composer require twig/twig
来源：http://dali.cdnleiting.top/Article/details/gtvhqjyvin.html

[U78] PHP：单元测试
来源：http://dali.ybcxt.top/Article/details/gtowbazrgb.html

composer require --dev phpunit/phpunit
来源：http://dali.ybcxt.top/Article/details/gtkvjucttk.html

[U79] PHP：静态分析
来源：http://dali.sufxvd.cn/Article/details/gtzunrtgew.html

composer require --dev phpstan/phpstan
来源：http://dali.fengsongda.top/Article/details/gtlypbfsov.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvthohbwm.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zdqjudy.top/Article/details/gtojikfnil.html

[U81] JS：初始化项目
来源：http://dali.hongshengwenyu.top/Article/details/gtducdwzvt.html

npm init -y;  npm i express
来源：http://dali.quarkkingdee.top/Article/details/gtxwjpgvih.html

[U82] JS：package.json 脚本
来源：http://dali.jlsjyb.cn/Article/details/gtufxrqtvw.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.zhongyouzk.top/Article/details/gtwzrzpxhr.html

[U83] JS：ES Module 导入导出
来源：http://dali.sweek.top/Article/details/gtecnrsbme.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gttcbyqalr.html

[U84] JS：CommonJS 写法
来源：http://dali.iojbl.cn/Article/details/gtvmmssgcw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.andypj.xyz/Article/details/gtkwkdrlro.html

[U85] JS：可选链
来源：http://dali.cashguo.top/Article/details/gtzkieiaqo.html

a?.b?.c
来源：http://dali.xinyue.icu/Article/details/gtmkmfmlct.html

[U86] JS：空值合并
来源：http://dali.haohaochexian.top/Article/details/gtpstvqcfa.html

a ?? b
来源：http://dali.jiagoushi.top/Article/details/gtwqkvnqli.html

[U87] JS：解构默认值
来源：http://dali.shuidangran.top/Article/details/gtcvccytis.html

const { a = 1, b = 2 } = obj;
来源：http://dali.zycfv.cn/Article/details/gtvwbiqlde.html

[U88] JS：对象展开合并
来源：http://dali.pycfn.com/Article/details/gtqjqwxmcj.html

{ ...a, ...b }
来源：http://dali.xuetiantiany.cn/Article/details/gtmzptthim.html

[U89] JS：数组去重
来源：http://dali.cucudq.cn/Article/details/gtzagqkxtj.html

[...new Set(arr)]
来源：http://dali.yanxiufei.cn/Article/details/gttnaugkbg.html

[U90] JS：数字数组排序
来源：http://dali.jqgfzy.top/Article/details/gtueclzzvr.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gthvpltygu.html

[U91] JS：对象键值遍历
来源：http://dali.dashuyun.cn/Article/details/gtvibvmcnf.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.andypj.xyz/Article/details/gtzxxyrxwx.html

[U92] JS：深拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvmjjoxvd.html

structuredClone(obj)
来源：http://dali.daria6918.cn/Article/details/gtgpvavvch.html

[U93] JS：模板字符串
来源：http://dali.hnqzz.top/Article/details/gtofgyvqju.html

`共 ${n} 条`
来源：http://dali.yvedp.cn/Article/details/gtzgkqdxtp.html

[U94] JS：箭头函数
来源：http://dali.aizwys.cn/Article/details/gtpyohajlb.html

const double = x => x * 2;
来源：http://dali.yj20258.top/Article/details/gtcbyrcxdp.html

[U95] JS：Promise 包装
来源：http://dali.bjfxy.top/Article/details/gtwxeijhst.html

new Promise((resolve, reject) => {})
来源：http://dali.guannengcc.top/Article/details/gtgetrmvcs.html

[U96] JS：async/await 与异常
来源：http://dali.guowangkeji.top/Article/details/gtebrflolv.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtvyphugea.html

[U97] JS：并发请求
来源：http://dali.shuidangran.top/Article/details/gtmatesnwb.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gtiicxafqe.html

[U98] JS：fetch 带 JSON
来源：http://dali.zhongyouzk.top/Article/details/gtpjgjpzzw.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xylfe.cn/Article/details/gtosfhgjts.html

[U99] JS：事件监听
来源：http://dali.aibaodan.cn/Article/details/gtlvrkrurh.html

el.addEventListener("click", e => {})
来源：http://dali.daria6918.cn/Article/details/gttekjcekk.html

[U100] JS：DOM 查询
来源：http://dali.yuanzhike.top/Article/details/gtamnqoick.html

document.querySelector(".item")
来源：http://dali.sxryk.cn/Article/details/gtwfdakzvo.html

[U101] JS：classList 操作
来源：http://dali.sweek.top/Article/details/gtabebzuxa.html

el.classList.toggle("active")
来源：http://dali.pycfn.com/Article/details/gtkimubdyj.html

[U102] JS：本地存储
来源：http://dali.hammf.cn/Article/details/gtlbfivyzb.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.hammf.cn/Article/details/gtzqciumru.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gtixchvlsu.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmqslqwfn.html

[U104] JS：防抖
来源：http://dali.havefunace.top/Article/details/gtpatfxavm.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gotoacloud.top/Article/details/gthtidsznq.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gthyjvstah.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.zhongyouzk.top/Article/details/gtidlxmfpt.html

[U106] JS：日期格式化
来源：http://dali.daxiang520.top/Article/details/gtpmyjqpir.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.smart0.xyz/Article/details/gtndhsvvkr.html

[U107] JS：数字千分位
来源：http://dali.guannengcc.top/Article/details/gtghibkzib.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.ivvv.top/Article/details/gthflooeyu.html

[U108] JS：随机整数
来源：http://dali.yvedp.cn/Article/details/gtkgbtkwgy.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.jianghu66.top/Article/details/gtpoqlswwe.html

[U109] JS：数组分组
来源：http://dali.c1oappe.top/Article/details/gtdukuliod.html

Object.groupBy(arr, x => x.type)
来源：http://dali.c1oappe.top/Article/details/gtzbydnauv.html

[U110] JS：数组分块
来源：http://dali.pycfn.com/Article/details/gtvyackgiv.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.yuanzhike.top/Article/details/gtrsynthrn.html

[U111] JS：对象转 Map
来源：http://dali.yuxming.cn/Article/details/gtnhmcgrok.html

new Map(Object.entries(obj))
来源：http://dali.nanxuanxn.top/Article/details/gtmzbsbnmc.html

[U112] JS：字符串补位
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmaaofzi.html

"7".padStart(3, "0")
来源：http://dali.yj20258888.top/Article/details/gtwrvjrqee.html

[U113] JS：正则替换全部
来源：http://dali.xziqi.cn/Article/details/gtgbsvfmgo.html

s.replaceAll("a", "b")
来源：http://dali.jyoumei.cn/Article/details/gtnaanajcu.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gthxxqclvg.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.zdqjudy.top/Article/details/gtostnrwkv.html

[U115] JS：生成 UUID
来源：http://dali.smart0.xyz/Article/details/gtfmelcekj.html

crypto.randomUUID()
来源：http://dali.hnxiangtu.top/Article/details/gtviyrdvko.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsijyyqvf.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtbpeidebu.html

[U117] JS：单元测试
来源：http://dali.pycfn.com/Article/details/gtqfxdfssc.html

npm i -D vitest;  npx vitest
来源：http://dali.chenlongwang.top/Article/details/gtqwgndkza.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gtrqjegwvk.html

npm i -D vite;  npx vite
来源：http://dali.yj20258888.top/Article/details/gtkykrsgle.html

[U119] JS：生产构建
来源：http://dali.dianchejie.cn/Article/details/gtbnfsovrn.html

npx vite build
来源：http://dali.cdnleiting.top/Article/details/gthbaibhar.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.cheryme.top/Article/details/gtypwmrxuz.html

import.meta.env.VITE_API_URL
来源：http://dali.pycfn.com/Article/details/gtbboexyng.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtfujjtrvd.html

统计汇总
来源：http://dali.chenzaomai.com/Article/details/gtyhoxjtyr.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtiyvxcrsx.html

按语言统计（条）：
来源：http://dali.xuanzx.com/Article/details/gtosdvmoat.html

Python ......... 252
来源：http://dali.shuidangran.top/Article/details/gtcrlncnlk.html

PHP ............ 252
来源：http://dali.wangdashe.top/Article/details/gtcqxqabtc.html

JavaScript ..... 252
来源：http://dali.ppjwa.cn/Article/details/gtuhvnhall.html

TypeScript ..... 212
来源：http://dali.yueranfly.top/Article/details/gtphasfsdd.html

Java ........... 212
来源：http://dali.shangyingyoupin.top/Article/details/gtwnujdick.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gtapccybaz.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtldeyauti.html

C# ............. 212
来源：http://dali.jyoumei.cn/Article/details/gtspdmfxzm.html

C .............. 30
来源：http://dali.iojbl.cn/Article/details/gtgpixohrl.html

C++ ............ 30
来源：http://dali.vqdsnc.cn/Article/details/gthdjzunnl.html

SQL ............ 90
来源：http://dali.aibaodan.cn/Article/details/gtpxpcjmgo.html

Bash ........... 80
来源：http://dali.hongshengwenyu.top/Article/details/gttvwuxved.html

Kotlin ......... 15
来源：http://dali.xylfe.cn/Article/details/gtjvaxutij.html

Swift .......... 15
来源：http://dali.dianchejie.cn/Article/details/gtthutwdom.html

Lua ............ 10
来源：http://dali.hongshengwenyu.top/Article/details/gtamecrvbn.html

Perl ........... 10
来源：http://dali.shuidangran.top/Article/details/gtgimjhktj.html

Scala .......... 10
来源：http://dali.zhijiandao.cn/Article/details/gtyujemygu.html

------------------------------------
来源：http://dali.cheryme.top/Article/details/gtgosujvlb.html

合计 ........... 2106 条
来源：http://dali.zdqjudy.top/Article/details/gtinpxbdeu.html

按章节统计：
来源：http://dali.jiagoushi.top/Article/details/gtoycvnvny.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nwbrower.top/Article/details/gtmyqzhymj.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.mhx1999.top/Article/details/gtqmmtriji.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.shanyushiyangkeji.top/Article/details/gtplmuzrbo.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.ppjwa.cn/Article/details/gtnfjvhzkx.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.jlsjyb.cn/Article/details/gtmrfnisyy.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.zhixingplan.top/Article/details/gtenxzfbmx.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.yuanzhike.top/Article/details/gttnpqxrsi.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtflewphbn.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.hnxiangtu.top/Article/details/gtyuhvhnjz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.jqgufenzy.top/Article/details/gtqnkczvoo.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ybcxt.top/Article/details/gtsgozhzcq.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.ehwqpu.com/Article/details/gtdoqtxdxo.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.hysaishi.cn/Article/details/gtsejykicq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.9152youxi.cn/Article/details/gtmbnivfjo.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.sxryk.cn/Article/details/gtsbdyikjf.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gtnqqahvtf.html

Q SQL 专题                              90
来源：http://dali.svipenyu.cn/Article/details/gtwqyoqjdm.html

R Bash 专题                             80
来源：http://dali.jinqigfzy.top/Article/details/gtndamrthq.html

S C / C++ 专题                          60
来源：http://dali.yj20258888.top/Article/details/gtlkzvwcok.html

T 其他语言补充                          60
来源：http://dali.shzxlz.cn/Article/details/gtryeabhpf.html

U 高频实用片段                         120
来源：http://dali.c1oappe.top/Article/details/gtmwpkmvsl.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gtlywcgrhh.html

合计                                  2106 条
来源：http://dali.jinghuilouyu.cn/Article/details/gtsyjsqcwp.html

--------------------------------------------------------------------------------
来源：http://dali.aizwys.cn/Article/details/gtzbqmesex.html


<!-- 参考信息 -->