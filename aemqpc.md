代发 wailian999

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gttfclgulv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.quarkkingdee.top/Article/details/gtgkhcdrfl.html

[T48] Perl：正则替换
来源：http://dali.havefunace.top/Article/details/gtpxdtoydw.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtjocfaxcd.html

[T49] Perl：函数
来源：http://dali.dashuyun.cn/Article/details/gtfstoqfsr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtyoopryrc.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtqhrtukde.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xuetiantiany.cn/Article/details/gtfddisnsz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtewbzpxof.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtfaubkdvl.html

println("Hello")
来源：http://dali.shuidangran.top/Article/details/gtcaqfnflv.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtnqeldiai.html

val a = 1;  var b = 2
来源：http://dali.ivvv.top/Article/details/gteyiotnfh.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtrhhipxff.html

s"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtbcrxdzoe.html

[T54] Scala：集合映射
来源：http://dali.ydzc1.top/Article/details/gtlugoxgcq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtroxcezdo.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtwipajbuz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gtfcfhgcrh.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtvnreycpt.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gtwyaeaqyg.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtovflfgkj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhijiandao.cn/Article/details/gtdbntzote.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtruxhmupe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gthafxjnlx.html

[T59] Scala：循环
来源：http://dali.cucudq.cn/Article/details/gttvvffoxh.html

for (i <- 1 to 10) println(i)
来源：http://dali.havefunace.top/Article/details/gtljexlcgd.html

[T60] Scala：折叠
来源：http://dali.yonumen.top/Article/details/gtzumgzkaf.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.0kj1m.cn/Article/details/gtkudwuhjv.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtjdjidvup.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnqzz.top/Article/details/gtkmcaepse.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtmdogshni.html

[U01] Py：创建虚拟环境
来源：http://dali.svipenyu.cn/Article/details/gtriakuuob.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cqqwz.cn/Article/details/gtfnssrtkz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jianghu66.top/Article/details/gtmylgapeg.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.guowangkeji.top/Article/details/gtxilkpclp.html

[U03] Py：加载 .env 配置
来源：http://dali.cheryme.top/Article/details/gtahqzucwt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtlhzdkmcn.html

[U04] Py：变量调试打印
来源：http://dali.yanxiufei.cn/Article/details/gthqhmrvdc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gtilfecibp.html

[U05] Py：列表去重且保序
来源：http://dali.xuanzx.com/Article/details/gtgdzadpyd.html

list(dict.fromkeys(arr))
来源：http://dali.shangyingyoupin.top/Article/details/gtojnnjiqt.html

[U06] Py：合并两个字典
来源：http://dali.sweek.top/Article/details/gtcdrcwfso.html

{**a, **b}
来源：http://dali.feifeiyinyue.top/Article/details/gticuzampa.html

[U07] Py：反转字典键值
来源：http://dali.yj20258.top/Article/details/gtgjysxlcp.html

{v: k for k, v in d.items()}
来源：http://dali.fengsongda.top/Article/details/gtchiywbbg.html

[U08] Py：展平二维列表
来源：http://dali.zycfv.cn/Article/details/gtxdeldumq.html

[y for x in nested for y in x]
来源：http://dali.jlsjyb.cn/Article/details/gtpvaecofc.html

[U09] Py：字典取最大值的键
来源：http://dali.shzxlz.cn/Article/details/gtzjndlecz.html

max(d, key=d.get)
来源：http://dali.pycfn.com/Article/details/gtdrawnxld.html

[U10] Py：按值排序字典
来源：http://dali.meibo888.top/Article/details/gtsnrahgtw.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jqgfzy.top/Article/details/gtgifpjzas.html

[U11] Py：生成器表达式
来源：http://dali.fzhhl.top/Article/details/gtcgnvahfv.html

(x * 2 for x in arr)
来源：http://dali.yuanzhike.top/Article/details/gtzzvfflqe.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.mhx1999.top/Article/details/gtqvyhsfia.html

Counter(arr).most_common(3)
来源：http://dali.chenlongwang.top/Article/details/gtldsakiif.html

[U13] Py：固定长度队列
来源：http://dali.316326.xyz/Article/details/gtokltfbzb.html

deque(maxlen=10)
来源：http://dali.jiagoushi.top/Article/details/gtumalofyu.html

[U14] Py：分组收集到列表
来源：http://dali.zdqjudy.top/Article/details/gtxgvqtgfr.html

defaultdict(list)
来源：http://dali.birdmap.top/Article/details/gtqijevfzd.html

[U15] Py：高精度计时
来源：http://dali.cdnleiting.top/Article/details/gtbalxtbxm.html

t = time.perf_counter()
来源：http://dali.dianchejie.cn/Article/details/gtqpbrwtrv.html

[U16] Py：命令行参数解析
来源：http://dali.yj202588.top/Article/details/gtbjjjbden.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.guowangkeji.top/Article/details/gtkxiwbgiq.html

[U17] Py：初始化日志
来源：http://dali.svipenyu.cn/Article/details/gtbehslrfk.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shzxlz.cn/Article/details/gtzlscmnvn.html

[U18] Py：预编译正则
来源：http://dali.wangdashe.top/Article/details/gtkevdvmwr.html

pat = re.compile(r"\d+")
来源：http://dali.shanyushiyangtech.top/Article/details/gtlirppcir.html

[U19] Py：正则替换带回调
来源：http://dali.tanke756.top/Article/details/gtpxrettee.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.zhoulong.xyz/Article/details/gtrusktnlk.html

[U20] Py：缓存函数结果
来源：http://dali.vqdsnc.cn/Article/details/gtstftmhza.html

@functools.lru_cache(maxsize=None)
来源：http://dali.aibaodan.cn/Article/details/gtelagwsqj.html

[U21] Py：自定义上下文管理器
来源：http://dali.wangshuangyany.cn/Article/details/gtxiewvyml.html

@contextlib.contextmanager
来源：http://dali.jinqigufen.top/Article/details/gtjwrmhnuw.html

[U22] Py：矩阵转置
来源：http://dali.gaohongyu789.top/Article/details/gtuspgebip.html

list(zip(*m))
来源：http://dali.ehwqpu.com/Article/details/gtcvztjdqp.html

[U23] Py：分块读取大文件
来源：http://dali.ivvv.top/Article/details/gtpwfuvdgl.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.sufxvd.cn/Article/details/gtzutbamjf.html

[U24] Py：路径操作
来源：http://dali.cqqwz.cn/Article/details/gtyrafhvdh.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.wangshuangyany.cn/Article/details/gtcxzsktuf.html

[U25] Py：CSV 按字典读
来源：http://dali.yj202588.top/Article/details/gtzwuiigpo.html

csv.DictReader(f)
来源：http://dali.bjfxy.top/Article/details/gthcrtamzq.html

[U26] Py：并发下载
来源：http://dali.xylfe.cn/Article/details/gtjtdkrwia.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.guannengcc.top/Article/details/gtuzpdueec.html

[U27] Py：异步 HTTP
来源：http://dali.guannengcc.top/Article/details/gtgvpcsjsg.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.quarkkingdee.top/Article/details/gtupriasgj.html

[U28] Py：类型别名
来源：http://dali.9152youxi.cn/Article/details/gttpeeigmy.html

UserId = int
来源：http://dali.bjfxy.top/Article/details/gtyafdvhmt.html

[U29] Py：属性校验
来源：http://dali.hongshengwenyu.top/Article/details/gtbdauevlc.html

@property 与 @x.setter 配合
来源：http://dali.birdmap.top/Article/details/gtejsrivee.html

[U30] Py：数据类
来源：http://dali.yangfankeji.com/Article/details/gtdbbulnac.html

@dataclass(slots=True)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxiwwyec.html

[U31] Py：单测
来源：http://dali.sysykeji.top/Article/details/gtmdhjfsnf.html

python -m pytest -q
来源：http://dali.xylfe.cn/Article/details/gthlubzmnf.html

[U32] Py：代码格式化
来源：http://dali.quarkkingdee.top/Article/details/gtxjklrtmx.html

ruff format . && ruff check --fix .
来源：http://dali.nanxinkj.top/Article/details/gtwufipexq.html

[U33] Py：打包发布
来源：http://dali.cashguo.top/Article/details/gtqjugtpuk.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.cheryme.top/Article/details/gtdhkthnxl.html

[U34] Py：判断编码
来源：http://dali.shuidangran.top/Article/details/gtubjfrfes.html

chardet.detect(raw)
来源：http://dali.nwbrower.top/Article/details/gtxnftlkbt.html

[U35] Py：发送邮件
来源：http://dali.chenlongwang.top/Article/details/gtzvfgdcar.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gtjnduaebd.html

[U36] Py：定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtdtgwjcji.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gttynknkzu.html

[U37] Py：读写 Excel
来源：http://dali.jinqigfzy.top/Article/details/gtazjhahot.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.chenlongwang.top/Article/details/gthjpmazut.html

[U38] Py：获取脚本所在目录
来源：http://dali.guowangkeji.top/Article/details/gtrnlsrnrv.html

Path(__file__).resolve().parent
来源：http://dali.birdmap.top/Article/details/gtclldcogq.html

[U39] Py：判断是否在交互环境
来源：http://dali.daxiang520.top/Article/details/gtwdrpnvqm.html

sys.stdout.isatty()
来源：http://dali.yongpay.top/Article/details/gtbndizcys.html

[U40] Py：打印到标准错误
来源：http://dali.yj20258.top/Article/details/gtqrzisxne.html

print("err", file=sys.stderr)
来源：http://dali.wangdashe.top/Article/details/gtrctyocfd.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ybcxt.top/Article/details/gtsgqqluah.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.wangdashe.top/Article/details/gtsgnjlufq.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jianghu66.top/Article/details/gtuohbomyl.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hnqzz.top/Article/details/gtkxlrkhjd.html

[U43] PHP：声明命名空间
来源：http://dali.hysaishi.cn/Article/details/gtrhicossm.html

namespace App\Http;
来源：http://dali.guowangkeji.top/Article/details/gteqwpyzgu.html

[U44] PHP：开启严格类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrhzluejr.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtorrckdyv.html

[U45] PHP：类型声明与返回类型
来源：http://dali.ivvv.top/Article/details/gtovothpdq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gtzxnqhofe.html

[U46] PHP：可空类型
来源：http://dali.gzhubu.top/Article/details/gtkfxnnscu.html

?string $name = null
来源：http://dali.vqdsnc.cn/Article/details/gtwewhujzh.html

[U47] PHP：联合类型
来源：http://dali.shangyingyoupin.top/Article/details/gtxvracezv.html

int|string $id
来源：http://dali.xziqi.cn/Article/details/gtyysajkwo.html

[U48] PHP：纯枚举
来源：http://dali.gaohongyu789.top/Article/details/gtfpefuhjc.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tianlin.xyz/Article/details/gtidpiiujw.html

[U49] PHP：只读属性
来源：http://dali.snrcjt.cn/Article/details/gtdmovrdwn.html

public readonly string $name
来源：http://dali.wangshuangyany.cn/Article/details/gtjgpioudo.html

[U50] PHP：构造器属性提升
来源：http://dali.zhoulong.xyz/Article/details/gtonkycanc.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gthghibrbj.html

[U51] PHP：数组解构
来源：http://dali.sufxvd.cn/Article/details/gtabodqbac.html

[$a, $b] = $arr;
来源：http://dali.jianghu66.top/Article/details/gtmivctzyd.html

[U52] PHP：箭头函数
来源：http://dali.kuanghao11.cn/Article/details/gtyivfptux.html

$double = fn($x) => $x * 2;
来源：http://dali.zhoulong.xyz/Article/details/gtrkhgzgur.html

[U53] PHP：空合并运算符
来源：http://dali.0kj1m.cn/Article/details/gtzuevdtgi.html

$v = $a ?? $b ?? "default";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqiqrexf.html

[U54] PHP：空安全调用
来源：http://dali.bjfxy.top/Article/details/gtsxewqqbu.html

$obj?->method()
来源：http://dali.haohaochexian.top/Article/details/gtrbthevkq.html

[U55] PHP：match 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtqvbilsgy.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.cheryme.top/Article/details/gtfmqcurbn.html

[U56] PHP：命名参数
来源：http://dali.ehwqpu.com/Article/details/gtzcsmwhye.html

f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtmqkrrwqn.html

[U57] PHP：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtmcyrlbcd.html

"值: {$a}"
来源：http://dali.hongshengwenyu.top/Article/details/gtqdaugueb.html

[U58] PHP：数组三件套
来源：http://dali.redwolf501.top/Article/details/gtlhabofjc.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.xuanzx.com/Article/details/gtzjmisdyp.html

[U59] PHP：自定义排序
来源：http://dali.cucudq.cn/Article/details/gtpyjzasfn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.hnqzz.top/Article/details/gtqkbncmnt.html

[U60] PHP：JSON 编解码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtldududdj.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.yvedp.cn/Article/details/gtgbgzrhfc.html

[U61] PHP：正则
来源：http://dali.cdnleiting.top/Article/details/gtxofogvvo.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.0kj1m.cn/Article/details/gtlbjumata.html

[U62] PHP：日期对象
来源：http://dali.jianghu66.top/Article/details/gtdmvtngcg.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprxricgg.html

[U63] PHP：文件读写
来源：http://dali.daria6918.cn/Article/details/gtitbdcfyh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.ppjwa.cn/Article/details/gtdrbddswc.html

[U64] PHP：目录遍历
来源：http://dali.smart0.xyz/Article/details/gtnbginrdx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.zhiwuduotai.top/Article/details/gtzcrczytj.html

[U65] PHP：会话
来源：http://dali.jyoumei.cn/Article/details/gtoilitrnp.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtvkumfgif.html

[U66] PHP：设置 Cookie
来源：http://dali.mhx1999.top/Article/details/gtynqvzvjy.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gtvcribhzv.html

[U67] PHP：处理文件上传
来源：http://dali.aibaodan.cn/Article/details/gtkyzlveei.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.yanxiufei.cn/Article/details/gtkczgsawl.html

[U68] PHP：PDO 连接
来源：http://dali.zhoulong.xyz/Article/details/gtfxmksuec.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.svipenyu.cn/Article/details/gtaerhuiat.html

[U69] PHP：PDO 预处理
来源：http://dali.quarkkingdee.top/Article/details/gtiqcyxful.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtdbrsxdsr.html

[U70] PHP：PDO 事务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtexbnugux.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.yj20258.top/Article/details/gtqhdtjxfq.html

[U71] PHP：抛出异常
来源：http://dali.shzxlz.cn/Article/details/gtfvstclxi.html

throw new RuntimeException("失败", 500);
来源：http://dali.cheryme.top/Article/details/gtwxogcrvb.html

[U72] PHP：写错误日志
来源：http://dali.hysaishi.cn/Article/details/gtbvnbaygl.html

error_log("失败: " . $e->getMessage());
来源：http://dali.xylfe.cn/Article/details/gtrqhbyqdn.html

[U73] PHP：读取 ini 配置
来源：http://dali.wangdashe.top/Article/details/gtioxsvqkq.html

parse_ini_file("config.ini", true)
来源：http://dali.cucudq.cn/Article/details/gtdrloqfug.html

[U74] PHP：读取环境变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbcxngpq.html

getenv("APP_ENV") ?: "production"
来源：http://dali.dianchejie.cn/Article/details/gtwsgfjmfx.html

[U75] PHP：依赖注入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrrutfwyp.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gtvdjebauw.html

[U76] PHP：简单路由
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsafmkraa.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.andypj.xyz/Article/details/gthibqnsdd.html

[U77] PHP：模板渲染
来源：http://dali.hnqzz.top/Article/details/gtgythcmkb.html

composer require twig/twig
来源：http://dali.shangyingyoupin.top/Article/details/gtqwoxzmsn.html

[U78] PHP：单元测试
来源：http://dali.gogol.net.cn/Article/details/gtoojrsjyi.html

composer require --dev phpunit/phpunit
来源：http://dali.jinqigfzy.top/Article/details/gtctvednie.html

[U79] PHP：静态分析
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunmwjvpl.html

composer require --dev phpstan/phpstan
来源：http://dali.ivvv.top/Article/details/gtbwamawha.html

[U80] PHP：代码规范修复
来源：http://dali.jlsjyb.cn/Article/details/gtdyzvirzo.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.tanke756.top/Article/details/gtlnxixveq.html

[U81] JS：初始化项目
来源：http://dali.sweek.top/Article/details/gtpgdvwzhv.html

npm init -y;  npm i express
来源：http://dali.daria6918.cn/Article/details/gtiwhoyeta.html

[U82] JS：package.json 脚本
来源：http://dali.aibaodan.cn/Article/details/gtcsvibdzo.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.xuanzx.com/Article/details/gtzbtrucec.html

[U83] JS：ES Module 导入导出
来源：http://dali.sysykeji.top/Article/details/gtadmiuvpt.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtzwgfyapz.html

[U84] JS：CommonJS 写法
来源：http://dali.yueranfly.top/Article/details/gtfjpihmnq.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.cucudq.cn/Article/details/gtsknkxkbp.html

[U85] JS：可选链
来源：http://dali.hammf.cn/Article/details/gtbqbnldti.html

a?.b?.c
来源：http://dali.yongpay.top/Article/details/gteffzmucz.html

[U86] JS：空值合并
来源：http://dali.jinqigufen.top/Article/details/gtyspwqeyw.html

a ?? b
来源：http://dali.nanxuanxn.top/Article/details/gtefxhodnf.html

[U87] JS：解构默认值
来源：http://dali.nanxinkj.top/Article/details/gtaoavuwcq.html

const { a = 1, b = 2 } = obj;
来源：http://dali.meibo888.top/Article/details/gtszyfcbwm.html

[U88] JS：对象展开合并
来源：http://dali.tanke756.top/Article/details/gtpvnttqwh.html

{ ...a, ...b }
来源：http://dali.shzxlz.cn/Article/details/gtludhjgjv.html

[U89] JS：数组去重
来源：http://dali.gzhubu.top/Article/details/gtdhbembmn.html

[...new Set(arr)]
来源：http://dali.vqdsnc.cn/Article/details/gtbjpzdltm.html

[U90] JS：数字数组排序
来源：http://dali.ivvv.top/Article/details/gtaicvxaci.html

[...arr].sort((a, b) => a - b)
来源：http://dali.birdmap.top/Article/details/gtmpfehyoh.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfwkspcq.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj20258.top/Article/details/gtxuhaygme.html

[U92] JS：深拷贝
来源：http://dali.0kj1m.cn/Article/details/gtieclwaye.html

structuredClone(obj)
来源：http://dali.yj202588.top/Article/details/gtnlgsjnwm.html

[U93] JS：模板字符串
来源：http://dali.tanke756.top/Article/details/gtupknhnzd.html

`共 ${n} 条`
来源：http://dali.xinyue.icu/Article/details/gtrgytaopm.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gtsnqixgfu.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtdsvjszoi.html

[U95] JS：Promise 包装
来源：http://dali.wangshuangyany.cn/Article/details/gtjcpxphcb.html

new Promise((resolve, reject) => {})
来源：http://dali.kuanghao11.cn/Article/details/gttdmnlskw.html

[U96] JS：async/await 与异常
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwsvoyzyh.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.hfpthk.cn/Article/details/gtelocpzvc.html

[U97] JS：并发请求
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlixbkhwh.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.vqdsnc.cn/Article/details/gtadodxygg.html

[U98] JS：fetch 带 JSON
来源：http://dali.hnxiangtu.top/Article/details/gtmhzisgjj.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.chenzaomai.com/Article/details/gtqekonrgl.html

[U99] JS：事件监听
来源：http://dali.meibo888.top/Article/details/gtgznzfdqh.html

el.addEventListener("click", e => {})
来源：http://dali.dianchejie.cn/Article/details/gtlujvwins.html

[U100] JS：DOM 查询
来源：http://dali.feifeiyinyue.top/Article/details/gtfcwmedmy.html

document.querySelector(".item")
来源：http://dali.chenjidiqi.icu/Article/details/gtgiovkrki.html

[U101] JS：classList 操作
来源：http://dali.zhiwuduotai.top/Article/details/gtyekgfhau.html

el.classList.toggle("active")
来源：http://dali.xziqi.cn/Article/details/gtovaprqfm.html

[U102] JS：本地存储
来源：http://dali.cashguo.top/Article/details/gtvvmlttya.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.zhoulong.xyz/Article/details/gtgkxjciuw.html

[U103] JS：定时器
来源：http://dali.9152youxi.cn/Article/details/gtlvnspneg.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.havefunace.top/Article/details/gtzenrbfvb.html

[U104] JS：防抖
来源：http://dali.xziqi.cn/Article/details/gtkngfziwo.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtxeicko.html

[U105] JS：节流
来源：http://dali.chenzaomai.com/Article/details/gtacwktdqx.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.vqdsnc.cn/Article/details/gtjhggayss.html

[U106] JS：日期格式化
来源：http://dali.smart0.xyz/Article/details/gtjdrfxqlr.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.snrcjt.cn/Article/details/gtkpsjcvom.html

[U107] JS：数字千分位
来源：http://dali.dianchejie.cn/Article/details/gtejhdrxvv.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.kuanghao11.cn/Article/details/gtsbkttsxu.html

[U108] JS：随机整数
来源：http://dali.birdmap.top/Article/details/gteimaetva.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.quarkkingdee.top/Article/details/gtqwdcvfbk.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtwykdnnnl.html

Object.groupBy(arr, x => x.type)
来源：http://dali.ivvv.top/Article/details/gtqabhzulz.html

[U110] JS：数组分块
来源：http://dali.jinghuilouyu.cn/Article/details/gtnbkrxsnz.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.shanyushiyangtech.top/Article/details/gthhdzjxfa.html

[U111] JS：对象转 Map
来源：http://dali.jinqigufen.top/Article/details/gtqxkrsnsq.html

new Map(Object.entries(obj))
来源：http://dali.jinqigfzy.top/Article/details/gtnbosvyfq.html

[U112] JS：字符串补位
来源：http://dali.havefunace.top/Article/details/gtmqfrprvx.html

"7".padStart(3, "0")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyafdyfl.html

[U113] JS：正则替换全部
来源：http://dali.ppjwa.cn/Article/details/gtwpymigqj.html

s.replaceAll("a", "b")
来源：http://dali.xinyue.icu/Article/details/gtqlqgqbcb.html

[U114] JS：JSON 深比较
来源：http://dali.jqgufenzy.top/Article/details/gtcoxxywfv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.tian-w.cn/Article/details/gtisltsmar.html

[U115] JS：生成 UUID
来源：http://dali.zhixingplan.top/Article/details/gtfexacwvl.html

crypto.randomUUID()
来源：http://dali.xinyue.icu/Article/details/gthchuotft.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.gzhubu.top/Article/details/gtoyjkxbrv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.hfpthk.cn/Article/details/gtmdvfhxwm.html

[U117] JS：单元测试
来源：http://dali.yongpay.top/Article/details/gtoppifjxi.html

npm i -D vitest;  npx vitest
来源：http://dali.bjfxy.top/Article/details/gtjwzvwplz.html

[U118] JS：开发服务器
来源：http://dali.xylfe.cn/Article/details/gtglktcbns.html

npm i -D vite;  npx vite
来源：http://dali.hfpthk.cn/Article/details/gttdopcwxc.html

[U119] JS：生产构建
来源：http://dali.gaohongyu789.top/Article/details/gtvjwllckw.html

npx vite build
来源：http://dali.hongshengwenyu.top/Article/details/gtidzvkuip.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.ywan-chungtsiang.top/Article/details/gteawozsbp.html

import.meta.env.VITE_API_URL
来源：http://dali.ydzc1.top/Article/details/gtzudbvkdo.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtprjbsksp.html

统计汇总
来源：http://dali.yanxiufei.cn/Article/details/gtvbfhdzrg.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtdajdccci.html

按语言统计（条）：
来源：http://dali.zhiwuduotai.top/Article/details/gtvnmafbrb.html

Python ......... 252
来源：http://dali.sxryk.cn/Article/details/gtbtnoddoi.html

PHP ............ 252
来源：http://dali.316326.xyz/Article/details/gtyvymjcbn.html

JavaScript ..... 252
来源：http://dali.yvedp.cn/Article/details/gtirmlrywk.html

TypeScript ..... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmypzqsi.html

Java ........... 212
来源：http://dali.ivvv.top/Article/details/gtsyktgpzs.html

Go ............. 212
来源：http://dali.fzhhl.top/Article/details/gtzcfzbpgz.html

Ruby ........... 212
来源：http://dali.jlsjyb.cn/Article/details/gtcenasqlq.html

C# ............. 212
来源：http://dali.jinyuanbaomall.cn/Article/details/gtijwnkxku.html

C .............. 30
来源：http://dali.jianghu66.top/Article/details/gtmmmbxohe.html

C++ ............ 30
来源：http://dali.cheryme.top/Article/details/gtmljqshni.html

SQL ............ 90
来源：http://dali.jqgfzy.top/Article/details/gtdxdfocrl.html

Bash ........... 80
来源：http://dali.shuidangran.top/Article/details/gtrphhbktx.html

Kotlin ......... 15
来源：http://dali.nanxuanxn.top/Article/details/gtcmuzcvzc.html

Swift .......... 15
来源：http://dali.meibo888.top/Article/details/gtujhneyzj.html

Lua ............ 10
来源：http://dali.cheryme.top/Article/details/gtofllgzzh.html

Perl ........... 10
来源：http://dali.jlsjyb.cn/Article/details/gtupzlmrfo.html

Scala .......... 10
来源：http://dali.shzxlz.cn/Article/details/gtpzymcber.html

------------------------------------
来源：http://dali.sufxvd.cn/Article/details/gtnstdynxf.html

合计 ........... 2106 条
来源：http://dali.haohaochexian.top/Article/details/gtmrcddxus.html

按章节统计：
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsbixnga.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.nanxuanxn.top/Article/details/gtqisdwtsz.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtbtjcexdi.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.jlsjyb.cn/Article/details/gtgpekelfg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.pycfn.com/Article/details/gtedxlrlje.html


<!-- 参考信息 -->