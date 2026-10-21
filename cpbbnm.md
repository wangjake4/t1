代发 wailian999

[T49] Perl：函数
来源：http://dali.yvedp.cn/Article/details/gtyvlfgafr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtbudcydud.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtenhxkglt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jlsjyb.cn/Article/details/gttgrqsmbb.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtbqlmfebj.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gthedutlys.html

println("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtnbaoxesp.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtmsavoxyk.html

val a = 1;  var b = 2
来源：http://dali.yuxming.cn/Article/details/gtwpnepdjj.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gtyhqortwh.html

s"值: $b"
来源：http://dali.ydzc1.top/Article/details/gtnipyyktu.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtegfuzslk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtoggarpvy.html

[T55] Scala：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtxcvwwaxn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gzhubu.top/Article/details/gteowphupi.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtsrrqawki.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gtkqzqtjtd.html

[T57] Scala：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtaptlmvwr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.c1oappe.top/Article/details/gtaqsvuysp.html

[T58] Scala：函数定义
来源：http://dali.zycfv.cn/Article/details/gtglfahxrm.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtkipjabcf.html

[T59] Scala：循环
来源：http://dali.gzhubu.top/Article/details/gtnbifxxhx.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtcnmrmiwz.html

[T60] Scala：折叠
来源：http://dali.havefunace.top/Article/details/gtoqhgltlx.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gtmwlpqoxa.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcevhqhjq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtevptblzs.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtqqnomznn.html

[U01] Py：创建虚拟环境
来源：http://dali.fzhhl.top/Article/details/gtraqihdvi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258.top/Article/details/gtrwudvouo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.vqdsnc.cn/Article/details/gtixbyftkq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nanxuanxn.top/Article/details/gtdbyvnxhf.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gtdnbfxwgy.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zycfv.cn/Article/details/gtgieoffaq.html

[U04] Py：变量调试打印
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykjyqlpc.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenlongwang.top/Article/details/gtfbkecdty.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtmnirkrtw.html

list(dict.fromkeys(arr))
来源：http://dali.aibaodan.cn/Article/details/gtzqrulsfk.html

[U06] Py：合并两个字典
来源：http://dali.dashuyun.cn/Article/details/gtqgexnnuj.html

{**a, **b}
来源：http://dali.zhijiandao.cn/Article/details/gtnuumoajj.html

[U07] Py：反转字典键值
来源：http://dali.sysykeji.top/Article/details/gtgbcysrls.html

{v: k for k, v in d.items()}
来源：http://dali.yj20258888.top/Article/details/gtzgnnxyaz.html

[U08] Py：展平二维列表
来源：http://dali.xylfe.cn/Article/details/gtqblioswv.html

[y for x in nested for y in x]
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwxjyumgq.html

[U09] Py：字典取最大值的键
来源：http://dali.andypj.xyz/Article/details/gtjopyqrfe.html

max(d, key=d.get)
来源：http://dali.xuanzx.com/Article/details/gtenwytqgg.html

[U10] Py：按值排序字典
来源：http://dali.sufxvd.cn/Article/details/gtgisvnbsk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.sweek.top/Article/details/gtwmzjedjj.html

[U11] Py：生成器表达式
来源：http://dali.guowangkeji.top/Article/details/gtpkqdewqc.html

(x * 2 for x in arr)
来源：http://dali.zhongyouzk.top/Article/details/gtahuascin.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shzxlz.cn/Article/details/gteyciwlmr.html

Counter(arr).most_common(3)
来源：http://dali.xylfe.cn/Article/details/gtxzddxiij.html

[U13] Py：固定长度队列
来源：http://dali.iojbl.cn/Article/details/gtmffnwysp.html

deque(maxlen=10)
来源：http://dali.jinqigfzy.top/Article/details/gtjucydxlr.html

[U14] Py：分组收集到列表
来源：http://dali.tanke756.top/Article/details/gtcbekheld.html

defaultdict(list)
来源：http://dali.quarkkingdee.top/Article/details/gtyawglxlj.html

[U15] Py：高精度计时
来源：http://dali.gotoacloud.top/Article/details/gthxtewtdw.html

t = time.perf_counter()
来源：http://dali.yongpay.top/Article/details/gtwmwyccdg.html

[U16] Py：命令行参数解析
来源：http://dali.tanke756.top/Article/details/gtjuuucwse.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.cqqwz.cn/Article/details/gttytlzctf.html

[U17] Py：初始化日志
来源：http://dali.shuidangran.top/Article/details/gtpgapxjqw.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.ybcxt.top/Article/details/gtwsmxexpt.html

[U18] Py：预编译正则
来源：http://dali.chenlongwang.top/Article/details/gtixhcticp.html

pat = re.compile(r"\d+")
来源：http://dali.yangfankeji.com/Article/details/gtffsrphiq.html

[U19] Py：正则替换带回调
来源：http://dali.yj20258888.top/Article/details/gtosdfegpu.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.dashuyun.cn/Article/details/gtpezbqrkz.html

[U20] Py：缓存函数结果
来源：http://dali.jinghuilouyu.cn/Article/details/gtkdnukubg.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jqgufenzy.top/Article/details/gtvywvldnh.html

[U21] Py：自定义上下文管理器
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlgaffww.html

@contextlib.contextmanager
来源：http://dali.ppjwa.cn/Article/details/gtuxwzatnm.html

[U22] Py：矩阵转置
来源：http://dali.jianghu66.top/Article/details/gtbmzigurp.html

list(zip(*m))
来源：http://dali.yj20258888.top/Article/details/gtlcyrbast.html

[U23] Py：分块读取大文件
来源：http://dali.jyoumei.cn/Article/details/gtvlhyjfpo.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.shzxlz.cn/Article/details/gtqnqaamcv.html

[U24] Py：路径操作
来源：http://dali.shuidangran.top/Article/details/gtsxpwitpv.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.cheryme.top/Article/details/gtsbnhflkz.html

[U25] Py：CSV 按字典读
来源：http://dali.316326.xyz/Article/details/gtplpkyqpj.html

csv.DictReader(f)
来源：http://dali.316326.xyz/Article/details/gtprypfzot.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtbmynzfgk.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.c1oappe.top/Article/details/gtdjlvwmxo.html

[U27] Py：异步 HTTP
来源：http://dali.316326.xyz/Article/details/gtupvobtaq.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.fengsongda.top/Article/details/gtgfquhbhp.html

[U28] Py：类型别名
来源：http://dali.cqqwz.cn/Article/details/gtoihpzhpo.html

UserId = int
来源：http://dali.nanxuanxn.top/Article/details/gtbmrgcuxq.html

[U29] Py：属性校验
来源：http://dali.dianchejie.cn/Article/details/gtivlicszu.html

@property 与 @x.setter 配合
来源：http://dali.zhaomingkeji.xyz/Article/details/gtglwydmof.html

[U30] Py：数据类
来源：http://dali.zhengqikj.top/Article/details/gtdwxpfeps.html

@dataclass(slots=True)
来源：http://dali.hammf.cn/Article/details/gtnecamoka.html

[U31] Py：单测
来源：http://dali.jiagoushi.top/Article/details/gtqusfkxkv.html

python -m pytest -q
来源：http://dali.gzhubu.top/Article/details/gtdtjvdpfq.html

[U32] Py：代码格式化
来源：http://dali.yuanzhike.top/Article/details/gtddpcvzal.html

ruff format . && ruff check --fix .
来源：http://dali.cheryme.top/Article/details/gtitmwrqdj.html

[U33] Py：打包发布
来源：http://dali.jqgfzy.top/Article/details/gtvgyqxwvp.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.chenlongwang.top/Article/details/gtovqsyykd.html

[U34] Py：判断编码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsdkhklnt.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcumfesp.html

[U35] Py：发送邮件
来源：http://dali.wangshuangyany.cn/Article/details/gtlplrkkdc.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.yanxiufei.cn/Article/details/gteptffukh.html

[U36] Py：定时任务
来源：http://dali.jqgufenzy.top/Article/details/gterbsuhyt.html

schedule.every(10).minutes.do(job)
来源：http://dali.jqgufenzy.top/Article/details/gtzgjehmwf.html

[U37] Py：读写 Excel
来源：http://dali.yj20258.top/Article/details/gtpuydknke.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.xuetiantiany.cn/Article/details/gtvokfzpdk.html

[U38] Py：获取脚本所在目录
来源：http://dali.bjfxy.top/Article/details/gtqebmkdlr.html

Path(__file__).resolve().parent
来源：http://dali.shzxlz.cn/Article/details/gtvgobnmnx.html

[U39] Py：判断是否在交互环境
来源：http://dali.ehwqpu.com/Article/details/gtvlgtxlnk.html

sys.stdout.isatty()
来源：http://dali.yvedp.cn/Article/details/gtaoicahah.html

[U40] Py：打印到标准错误
来源：http://dali.yangfankeji.com/Article/details/gtpoflginh.html

print("err", file=sys.stderr)
来源：http://dali.redwolf501.top/Article/details/gtqsewgveq.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.ppjwa.cn/Article/details/gtowxkqkuc.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.xylfe.cn/Article/details/gtuvphyxzk.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.xziqi.cn/Article/details/gtfhegcqea.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yj202588.top/Article/details/gtdjaepylt.html

[U43] PHP：声明命名空间
来源：http://dali.yj202588.top/Article/details/gtllxwmjgg.html

namespace App\Http;
来源：http://dali.pengpengdd.cyou/Article/details/gtjcptzrjj.html

[U44] PHP：开启严格类型
来源：http://dali.jianghu66.top/Article/details/gtcfxijcvn.html

declare(strict_types=1);
来源：http://dali.guowangkeji.top/Article/details/gtqcvkukqz.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtnaauoezq.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtsrcqpxns.html

[U46] PHP：可空类型
来源：http://dali.zycfv.cn/Article/details/gtuesmmwfo.html

?string $name = null
来源：http://dali.chenjidiqi.icu/Article/details/gtiyjnvsrr.html

[U47] PHP：联合类型
来源：http://dali.feifeiyinyue.top/Article/details/gtqmnaszzd.html

int|string $id
来源：http://dali.yanxiufei.cn/Article/details/gtklvahgkv.html

[U48] PHP：纯枚举
来源：http://dali.ydzc1.top/Article/details/gtoflfqctg.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.gotoacloud.top/Article/details/gtyauslnqz.html

[U49] PHP：只读属性
来源：http://dali.xziqi.cn/Article/details/gtfheonpai.html

public readonly string $name
来源：http://dali.yanxiufei.cn/Article/details/gtzvmkwgmm.html

[U50] PHP：构造器属性提升
来源：http://dali.fzhhl.top/Article/details/gtfchgnrmk.html

public function __construct(private int $id) {}
来源：http://dali.daria6918.cn/Article/details/gtmrnebsph.html

[U51] PHP：数组解构
来源：http://dali.jqgufenzy.top/Article/details/gtbkorzwze.html

[$a, $b] = $arr;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxwgdrgyb.html

[U52] PHP：箭头函数
来源：http://dali.hnxiangtu.top/Article/details/gtmmvrvbvu.html

$double = fn($x) => $x * 2;
来源：http://dali.yonumen.top/Article/details/gtikollugj.html

[U53] PHP：空合并运算符
来源：http://dali.nwbrower.top/Article/details/gtxnjqzlhe.html

$v = $a ?? $b ?? "default";
来源：http://dali.yangfankeji.com/Article/details/gtisoakpgq.html

[U54] PHP：空安全调用
来源：http://dali.hysaishi.cn/Article/details/gtryuqtmwi.html

$obj?->method()
来源：http://dali.tian-w.cn/Article/details/gtcimmryhp.html

[U55] PHP：match 表达式
来源：http://dali.ehwqpu.com/Article/details/gtbfrypikv.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.pycfn.com/Article/details/gtoygqxmga.html

[U56] PHP：命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gthfozikql.html

f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxeyosiwa.html

[U57] PHP：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtreyjqjhl.html

"值: {$a}"
来源：http://dali.yuxming.cn/Article/details/gtklcygsun.html

[U58] PHP：数组三件套
来源：http://dali.ydzc1.top/Article/details/gtagoenqkw.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.yuanzhike.top/Article/details/gtcjvuuzei.html

[U59] PHP：自定义排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgxgzmkf.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinqigufen.top/Article/details/gtqkrkmxca.html

[U60] PHP：JSON 编解码
来源：http://dali.mhx1999.top/Article/details/gtezuzpkud.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinqigufen.top/Article/details/gtmsptdobi.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gtbzpvpnmy.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.chenzaomai.com/Article/details/gtcycdtwvq.html

[U62] PHP：日期对象
来源：http://dali.quarkkingdee.top/Article/details/gtyzsltzem.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.mhx1999.top/Article/details/gtfeqwoilx.html

[U63] PHP：文件读写
来源：http://dali.yj202588.top/Article/details/gtxtbsbywn.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.gzhubu.top/Article/details/gtrodizqvm.html

[U64] PHP：目录遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyzwjjrt.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.0kj1m.cn/Article/details/gtrvtubhtb.html

[U65] PHP：会话
来源：http://dali.zdqjudy.top/Article/details/gtjytzkeyl.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtifxbsbiq.html

[U66] PHP：设置 Cookie
来源：http://dali.jyoumei.cn/Article/details/gtvgwcoofp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.andypj.xyz/Article/details/gtrgagfzep.html

[U67] PHP：处理文件上传
来源：http://dali.wangdashe.top/Article/details/gtgoguaxvg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.meibo888.top/Article/details/gtcwwkfhlw.html

[U68] PHP：PDO 连接
来源：http://dali.yuxming.cn/Article/details/gtsskewenj.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.sweek.top/Article/details/gtrifgwgib.html

[U69] PHP：PDO 预处理
来源：http://dali.redwolf501.top/Article/details/gthmgzjysj.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tanke756.top/Article/details/gtonfrazjh.html

[U70] PHP：PDO 事务
来源：http://dali.zhongyouzk.top/Article/details/gtpbxanpat.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.tanke756.top/Article/details/gtjazxlzaz.html

[U71] PHP：抛出异常
来源：http://dali.cashguo.top/Article/details/gtlschxtbx.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gtyrjfivyp.html

[U72] PHP：写错误日志
来源：http://dali.meibo888.top/Article/details/gtvriqshpy.html

error_log("失败: " . $e->getMessage());
来源：http://dali.pycfn.com/Article/details/gtkrybvolt.html

[U73] PHP：读取 ini 配置
来源：http://dali.sxryk.cn/Article/details/gtxygatjpg.html

parse_ini_file("config.ini", true)
来源：http://dali.gzhubu.top/Article/details/gtaifhcyaq.html

[U74] PHP：读取环境变量
来源：http://dali.0kj1m.cn/Article/details/gtfzhtpnjp.html

getenv("APP_ENV") ?: "production"
来源：http://dali.yangfankeji.com/Article/details/gtnvudnabu.html

[U75] PHP：依赖注入
来源：http://dali.xylfe.cn/Article/details/gtvivzaevc.html

composer require psr/container
来源：http://dali.tanke756.top/Article/details/gtrkzwnruz.html

[U76] PHP：简单路由
来源：http://dali.wangshuangyany.cn/Article/details/gtkbjulduv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xinyue.icu/Article/details/gtyndmztkg.html

[U77] PHP：模板渲染
来源：http://dali.vqdsnc.cn/Article/details/gtbyecxpfm.html

composer require twig/twig
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzploupyy.html

[U78] PHP：单元测试
来源：http://dali.hongshengwenyu.top/Article/details/gtrjfomhqm.html

composer require --dev phpunit/phpunit
来源：http://dali.xylfe.cn/Article/details/gtyafmnrhi.html

[U79] PHP：静态分析
来源：http://dali.gzhubu.top/Article/details/gtbhcyrbqu.html

composer require --dev phpstan/phpstan
来源：http://dali.feifeiyinyue.top/Article/details/gtumzbsqlo.html

[U80] PHP：代码规范修复
来源：http://dali.aibaodan.cn/Article/details/gtvoxhytkh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.cucudq.cn/Article/details/gtaklukelg.html

[U81] JS：初始化项目
来源：http://dali.xziqi.cn/Article/details/gtkrpnzltx.html

npm init -y;  npm i express
来源：http://dali.jqgufenzy.top/Article/details/gtdpqkjlyq.html

[U82] JS：package.json 脚本
来源：http://dali.yj20258.top/Article/details/gtsvlwbksr.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.tanke756.top/Article/details/gtzlfstvqb.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxinkj.top/Article/details/gthjgvfyan.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.316326.xyz/Article/details/gtpwidfepr.html

[U84] JS：CommonJS 写法
来源：http://dali.hongshengwenyu.top/Article/details/gtthhcqsjg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yuxming.cn/Article/details/gtlblbgrme.html

[U85] JS：可选链
来源：http://dali.snrcjt.cn/Article/details/gtkclkqkec.html

a?.b?.c
来源：http://dali.daxiang520.top/Article/details/gtrsmyjkod.html

[U86] JS：空值合并
来源：http://dali.tianlin.xyz/Article/details/gtyesuuwaz.html

a ?? b
来源：http://dali.snrcjt.cn/Article/details/gtapojkvnr.html

[U87] JS：解构默认值
来源：http://dali.tanke756.top/Article/details/gtmlqewjid.html

const { a = 1, b = 2 } = obj;
来源：http://dali.chenzaomai.com/Article/details/gtwkouviah.html

[U88] JS：对象展开合并
来源：http://dali.xylfe.cn/Article/details/gtfagnvrlx.html

{ ...a, ...b }
来源：http://dali.cqqwz.cn/Article/details/gtuujvzbnp.html

[U89] JS：数组去重
来源：http://dali.shuidangran.top/Article/details/gttmhusdxc.html

[...new Set(arr)]
来源：http://dali.tianlin.xyz/Article/details/gtewsgjhrd.html

[U90] JS：数字数组排序
来源：http://dali.bjfxy.top/Article/details/gtwgsjscob.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sweek.top/Article/details/gtvtihwdrf.html

[U91] JS：对象键值遍历
来源：http://dali.nanxinkj.top/Article/details/gtfyibssvb.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.c1oappe.top/Article/details/gtjibqsdww.html

[U92] JS：深拷贝
来源：http://dali.hfpthk.cn/Article/details/gtgcfzwdce.html

structuredClone(obj)
来源：http://dali.dianchejie.cn/Article/details/gtknaredvx.html

[U93] JS：模板字符串
来源：http://dali.316326.xyz/Article/details/gtdxunflst.html

`共 ${n} 条`
来源：http://dali.jyoumei.cn/Article/details/gtfitylpes.html

[U94] JS：箭头函数
来源：http://dali.hfpthk.cn/Article/details/gtpdpgaaiz.html

const double = x => x * 2;
来源：http://dali.sweek.top/Article/details/gtxzqvqofi.html

[U95] JS：Promise 包装
来源：http://dali.gotoacloud.top/Article/details/gtbleqcfrf.html

new Promise((resolve, reject) => {})
来源：http://dali.hongshengwenyu.top/Article/details/gtmavrqral.html

[U96] JS：async/await 与异常
来源：http://dali.fzhhl.top/Article/details/gtxcqbvytm.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.cashguo.top/Article/details/gtqpqzmzda.html

[U97] JS：并发请求
来源：http://dali.tanke756.top/Article/details/gtmpnxzaso.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.shangyingyoupin.top/Article/details/gtyshekbvp.html

[U98] JS：fetch 带 JSON
来源：http://dali.smart0.xyz/Article/details/gtgjklcelx.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.havefunace.top/Article/details/gtbvvllmpf.html

[U99] JS：事件监听
来源：http://dali.feifeiyinyue.top/Article/details/gtnqwpdsdf.html

el.addEventListener("click", e => {})
来源：http://dali.jinqigfzy.top/Article/details/gtespvstok.html

[U100] JS：DOM 查询
来源：http://dali.zhongyouzk.top/Article/details/gtdoazhigr.html

document.querySelector(".item")
来源：http://dali.nwbrower.top/Article/details/gtcfkppsti.html

[U101] JS：classList 操作
来源：http://dali.ppjwa.cn/Article/details/gtmqohabto.html

el.classList.toggle("active")
来源：http://dali.chenjidiqi.icu/Article/details/gtafkfcppx.html

[U102] JS：本地存储
来源：http://dali.havefunace.top/Article/details/gteaaxpear.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.316326.xyz/Article/details/gtblehruml.html

[U103] JS：定时器
来源：http://dali.meibo888.top/Article/details/gtwnmuxpnc.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhixingplan.top/Article/details/gtcmtjrpax.html

[U104] JS：防抖
来源：http://dali.zhongyouzk.top/Article/details/gtowdjnxpl.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guannengcc.top/Article/details/gturevgqkr.html

[U105] JS：节流
来源：http://dali.jinghuilouyu.cn/Article/details/gtexohkxuj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.aibaodan.cn/Article/details/gtvyexbfgi.html

[U106] JS：日期格式化
来源：http://dali.nwbrower.top/Article/details/gtoqgewyif.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawcvwmkr.html

[U107] JS：数字千分位
来源：http://dali.wangdashe.top/Article/details/gtvkvhxjzm.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.hnqzz.top/Article/details/gtocztyeyt.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gtmgtypvfn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.mhx1999.top/Article/details/gtjjhnnlpu.html

[U109] JS：数组分组
来源：http://dali.vqdsnc.cn/Article/details/gtyabgcduo.html

Object.groupBy(arr, x => x.type)
来源：http://dali.hnqzz.top/Article/details/gtxgurixnx.html

[U110] JS：数组分块
来源：http://dali.jlsjyb.cn/Article/details/gtyzflitfr.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.svipenyu.cn/Article/details/gtfbtscxas.html

[U111] JS：对象转 Map
来源：http://dali.xylfe.cn/Article/details/gtasdvsyig.html

new Map(Object.entries(obj))
来源：http://dali.cheryme.top/Article/details/gtenaupglb.html

[U112] JS：字符串补位
来源：http://dali.zdqjudy.top/Article/details/gtehsajcuv.html

"7".padStart(3, "0")
来源：http://dali.chenzaomai.com/Article/details/gtkshktnso.html

[U113] JS：正则替换全部
来源：http://dali.sufxvd.cn/Article/details/gtcyeeecvu.html

s.replaceAll("a", "b")
来源：http://dali.ydzc1.top/Article/details/gtwbqlaboo.html

[U114] JS：JSON 深比较
来源：http://dali.xziqi.cn/Article/details/gtofjtjnuv.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gtbqafvdee.html

[U115] JS：生成 UUID
来源：http://dali.sufxvd.cn/Article/details/gtivokxrvm.html

crypto.randomUUID()
来源：http://dali.yueranfly.top/Article/details/gtaghciahy.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cheryme.top/Article/details/gtahbwrmij.html

/** @param {string} name */ function f(name) {}
来源：http://dali.havefunace.top/Article/details/gthnfvjbdj.html

[U117] JS：单元测试
来源：http://dali.guannengcc.top/Article/details/gtwqpwxtdu.html

npm i -D vitest;  npx vitest
来源：http://dali.jiagoushi.top/Article/details/gthdgqmsqu.html

[U118] JS：开发服务器
来源：http://dali.hnxiangtu.top/Article/details/gtmldhgxgx.html

npm i -D vite;  npx vite
来源：http://dali.dashuyun.cn/Article/details/gtrkztxptl.html

[U119] JS：生产构建
来源：http://dali.hysaishi.cn/Article/details/gterkwakpp.html

npx vite build
来源：http://dali.zhixingplan.top/Article/details/gtvsrqpsvf.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.hammf.cn/Article/details/gtrbpfpmpe.html

import.meta.env.VITE_API_URL
来源：http://dali.zhengqikj.top/Article/details/gtcfzfzqki.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtmovegttu.html

统计汇总
来源：http://dali.jiagoushi.top/Article/details/gtoxyqdfzn.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtuqgxkvce.html

按语言统计（条）：
来源：http://dali.yonumen.top/Article/details/gtnwjxuyqe.html

Python ......... 252
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaqaxmnhe.html

PHP ............ 252
来源：http://dali.ydzc1.top/Article/details/gtuascvbuj.html

JavaScript ..... 252
来源：http://dali.jinghuilouyu.cn/Article/details/gtfyxybhpa.html

TypeScript ..... 212
来源：http://dali.svipenyu.cn/Article/details/gtmtkrwoxa.html

Java ........... 212
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjwhqezcj.html

Go ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtjtqjlqbs.html

Ruby ........... 212
来源：http://dali.jinghuilouyu.cn/Article/details/gtujbqonfp.html

C# ............. 212
来源：http://dali.zdqjudy.top/Article/details/gtfeuvqbyt.html

C .............. 30
来源：http://dali.yangfankeji.com/Article/details/gtmgmibbpg.html

C++ ............ 30
来源：http://dali.zdqjudy.top/Article/details/gtyzbowmfz.html

SQL ............ 90
来源：http://dali.gogol.net.cn/Article/details/gtlnfasnpg.html

Bash ........... 80
来源：http://dali.yueranfly.top/Article/details/gtjnvelzyg.html

Kotlin ......... 15
来源：http://dali.sufxvd.cn/Article/details/gtduaqgrkm.html

Swift .......... 15
来源：http://dali.xuanzx.com/Article/details/gtgelfazvv.html

Lua ............ 10
来源：http://dali.wangshuangyany.cn/Article/details/gtomhznhvl.html

Perl ........... 10
来源：http://dali.kuanghao11.cn/Article/details/gtkjokfqsv.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gtfqbvntcr.html

------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtkkuezxgm.html

合计 ........... 2106 条
来源：http://dali.chenlongwang.top/Article/details/gtjorptbwj.html

按章节统计：
来源：http://dali.aibaodan.cn/Article/details/gtuljrkvjh.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.xinyue.icu/Article/details/gtawhqupnw.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.shzxlz.cn/Article/details/gtkygqxwmo.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.bjfxy.top/Article/details/gtdvyeokhs.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.c1oappe.top/Article/details/gtrsyycidc.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.316326.xyz/Article/details/gtcslvazip.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.nwbrower.top/Article/details/gtqjhbmlah.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.chenjidiqi.icu/Article/details/gtwppfgrls.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.sufxvd.cn/Article/details/gtwtznjjjc.html


<!-- 参考信息 -->