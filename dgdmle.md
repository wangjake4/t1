代发 wailian999

[T49] Perl：函数
来源：http://dali.zhixingplan.top/Article/details/gtqufsfxwa.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwcshvfqk.html

[T50] Perl：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxdgjcucx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gtvexdenhn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfenescj.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gthpyejklf.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtmybtqnev.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gtumujqecq.html

val a = 1;  var b = 2
来源：http://dali.bjfxy.top/Article/details/gtgauiqrtg.html

[T53] Scala：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtpcyfecsh.html

s"值: $b"
来源：http://dali.daria6918.cn/Article/details/gtubyjspbs.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtxwyawqxy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gteoivtphx.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtamrsslli.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gtxmqfgxgo.html

[T56] Scala：样例类
来源：http://dali.chenlongwang.top/Article/details/gtiobzlqxi.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtjetyihxy.html

[T57] Scala：模式匹配
来源：http://dali.316326.xyz/Article/details/gtcivlowvl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hnqzz.top/Article/details/gtdcgeqnhc.html

[T58] Scala：函数定义
来源：http://dali.andypj.xyz/Article/details/gtscugbmgp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ybcxt.top/Article/details/gtltdptiue.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtlvbwyjyf.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtjktujrnn.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtrxilmxbp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtisqhpiye.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtjfxsvuhj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pengpengdd.cyou/Article/details/gtdhtcggwn.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtytlqatcg.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gtsaedyolf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gtgflwaxyf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fzhhl.top/Article/details/gtwcrfgyli.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.chenzaomai.com/Article/details/gthokcibui.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gtevlatdjw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jyoumei.cn/Article/details/gtghhpmasy.html

[U04] Py：变量调试打印
来源：http://dali.c1oappe.top/Article/details/gttqyvibnr.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhiwuduotai.top/Article/details/gtnfmgcvzs.html

[U05] Py：列表去重且保序
来源：http://dali.zhiwuduotai.top/Article/details/gtmqbrhruk.html

list(dict.fromkeys(arr))
来源：http://dali.ivvv.top/Article/details/gtntxxvcnm.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtmdswxjfq.html

{**a, **b}
来源：http://dali.ydzc1.top/Article/details/gtyhamxfyq.html

[U07] Py：反转字典键值
来源：http://dali.daria6918.cn/Article/details/gtmiyhpwte.html

{v: k for k, v in d.items()}
来源：http://dali.jianghu66.top/Article/details/gtnbdlrmbw.html

[U08] Py：展平二维列表
来源：http://dali.svipenyu.cn/Article/details/gtrbrrcdav.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtutkkirir.html

[U09] Py：字典取最大值的键
来源：http://dali.xinyue.icu/Article/details/gtcvbhvvip.html

max(d, key=d.get)
来源：http://dali.quarkkingdee.top/Article/details/gtitkkqrfy.html

[U10] Py：按值排序字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmedtcuo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtejynxcdn.html

[U11] Py：生成器表达式
来源：http://dali.yvedp.cn/Article/details/gtlqruyiut.html

(x * 2 for x in arr)
来源：http://dali.sweek.top/Article/details/gtwqllzlwh.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gtnymjthtz.html

Counter(arr).most_common(3)
来源：http://dali.aizwys.cn/Article/details/gtaufswsuz.html

[U13] Py：固定长度队列
来源：http://dali.jianghu66.top/Article/details/gtxhpvdrcw.html

deque(maxlen=10)
来源：http://dali.aibaodan.cn/Article/details/gtgnshidzh.html

[U14] Py：分组收集到列表
来源：http://dali.shuidangran.top/Article/details/gtepefdmvg.html

defaultdict(list)
来源：http://dali.havefunace.top/Article/details/gtdpdqbxtb.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtygtluyzr.html

t = time.perf_counter()
来源：http://dali.c1oappe.top/Article/details/gtzxshfdkv.html

[U16] Py：命令行参数解析
来源：http://dali.sufxvd.cn/Article/details/gtsjsaxjpg.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhctqqoo.html

[U17] Py：初始化日志
来源：http://dali.cqqwz.cn/Article/details/gtikjndmui.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.quarkkingdee.top/Article/details/gtzoapgpoa.html

[U18] Py：预编译正则
来源：http://dali.sysykeji.top/Article/details/gtsscflpqh.html

pat = re.compile(r"\d+")
来源：http://dali.zdqjudy.top/Article/details/gtunpzroxi.html

[U19] Py：正则替换带回调
来源：http://dali.xinyue.icu/Article/details/gtqgqsnmyr.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvfljncx.html

[U20] Py：缓存函数结果
来源：http://dali.hnqzz.top/Article/details/gtrrbnzxzf.html

@functools.lru_cache(maxsize=None)
来源：http://dali.jyoumei.cn/Article/details/gtthjuzztu.html

[U21] Py：自定义上下文管理器
来源：http://dali.chenzaomai.com/Article/details/gtjzikvazu.html

@contextlib.contextmanager
来源：http://dali.0kj1m.cn/Article/details/gtophdinyt.html

[U22] Py：矩阵转置
来源：http://dali.jyoumei.cn/Article/details/gtbzukxyup.html

list(zip(*m))
来源：http://dali.quarkkingdee.top/Article/details/gtttyzjonm.html

[U23] Py：分块读取大文件
来源：http://dali.cheryme.top/Article/details/gtfeghnsuw.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.yonumen.top/Article/details/gtbfrrpkut.html

[U24] Py：路径操作
来源：http://dali.svipenyu.cn/Article/details/gteduoeede.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.tian-w.cn/Article/details/gtmphjnhxr.html

[U25] Py：CSV 按字典读
来源：http://dali.sysykeji.top/Article/details/gtkuxyoyuy.html

csv.DictReader(f)
来源：http://dali.yanxiufei.cn/Article/details/gtetgxuwpg.html

[U26] Py：并发下载
来源：http://dali.sysykeji.top/Article/details/gtsohqwjwi.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.yangfankeji.com/Article/details/gttmiwzyhm.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtpkcclqbz.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.shangyingyoupin.top/Article/details/gtjvlgmukl.html

[U28] Py：类型别名
来源：http://dali.ybcxt.top/Article/details/gtcxhyyznn.html

UserId = int
来源：http://dali.meibo888.top/Article/details/gttugktbzv.html

[U29] Py：属性校验
来源：http://dali.smart0.xyz/Article/details/gtmopfqdhf.html

@property 与 @x.setter 配合
来源：http://dali.cdnleiting.top/Article/details/gtjpfesipk.html

[U30] Py：数据类
来源：http://dali.jianghu66.top/Article/details/gtucnxwjnl.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtsegjkdiw.html

[U31] Py：单测
来源：http://dali.chenlongwang.top/Article/details/gtafbldmjn.html

python -m pytest -q
来源：http://dali.havefunace.top/Article/details/gtbbhlwufv.html

[U32] Py：代码格式化
来源：http://dali.kuanghao11.cn/Article/details/gthfrksfdd.html

ruff format . && ruff check --fix .
来源：http://dali.smart0.xyz/Article/details/gtqslrbgaq.html

[U33] Py：打包发布
来源：http://dali.nanxinkj.top/Article/details/gtwxvbfxsr.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.wangdashe.top/Article/details/gttvesbugq.html

[U34] Py：判断编码
来源：http://dali.hywenlv.cn/Article/details/gtmicsnotr.html

chardet.detect(raw)
来源：http://dali.zhijiandao.cn/Article/details/gtcysjxysc.html

[U35] Py：发送邮件
来源：http://dali.jinqigfzy.top/Article/details/gtfwaeczec.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.ppjwa.cn/Article/details/gtwvvdkqmv.html

[U36] Py：定时任务
来源：http://dali.yuanzhike.top/Article/details/gtozffhxxg.html

schedule.every(10).minutes.do(job)
来源：http://dali.shangyingyoupin.top/Article/details/gtuczgxqhk.html

[U37] Py：读写 Excel
来源：http://dali.jqgufenzy.top/Article/details/gtlavccnef.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.sufxvd.cn/Article/details/gtnsajyxfz.html

[U38] Py：获取脚本所在目录
来源：http://dali.yonumen.top/Article/details/gtzivumufk.html

Path(__file__).resolve().parent
来源：http://dali.yj202588.top/Article/details/gtknskbrmy.html

[U39] Py：判断是否在交互环境
来源：http://dali.yuxming.cn/Article/details/gtxwyixszn.html

sys.stdout.isatty()
来源：http://dali.yangfankeji.com/Article/details/gtuqzydquy.html

[U40] Py：打印到标准错误
来源：http://dali.ehwqpu.com/Article/details/gtpdpwgrtv.html

print("err", file=sys.stderr)
来源：http://dali.iojbl.cn/Article/details/gteqbxntcj.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.quarkkingdee.top/Article/details/gtggmnlkjb.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shzxlz.cn/Article/details/gthinfpiys.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.iojbl.cn/Article/details/gtrnrbvsar.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.yangfankeji.com/Article/details/gtpwdxuhuq.html

[U43] PHP：声明命名空间
来源：http://dali.cashguo.top/Article/details/gtqhpctdwn.html

namespace App\Http;
来源：http://dali.yj202588.top/Article/details/gtomrfuelg.html

[U44] PHP：开启严格类型
来源：http://dali.jqgfzy.top/Article/details/gtbslpofaf.html

declare(strict_types=1);
来源：http://dali.aibaodan.cn/Article/details/gterkgryxi.html

[U45] PHP：类型声明与返回类型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfelhciem.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigufen.top/Article/details/gtctkcyzmp.html

[U46] PHP：可空类型
来源：http://dali.zhiwuduotai.top/Article/details/gtgylfabdl.html

?string $name = null
来源：http://dali.tian-w.cn/Article/details/gtuqfuxpaf.html

[U47] PHP：联合类型
来源：http://dali.zhixingplan.top/Article/details/gtwbyadvzi.html

int|string $id
来源：http://dali.zhongyouzk.top/Article/details/gtmbbiniuh.html

[U48] PHP：纯枚举
来源：http://dali.316326.xyz/Article/details/gtlgilxlqm.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.hnqzz.top/Article/details/gtdgwsirnz.html

[U49] PHP：只读属性
来源：http://dali.chenlongwang.top/Article/details/gtjangynpx.html

public readonly string $name
来源：http://dali.cucudq.cn/Article/details/gthsxdwbqn.html

[U50] PHP：构造器属性提升
来源：http://dali.havefunace.top/Article/details/gtxxhurtms.html

public function __construct(private int $id) {}
来源：http://dali.hnxiangtu.top/Article/details/gtgcsjkjcj.html

[U51] PHP：数组解构
来源：http://dali.dashuyun.cn/Article/details/gtnobnkopp.html

[$a, $b] = $arr;
来源：http://dali.yongpay.top/Article/details/gtqterubkn.html

[U52] PHP：箭头函数
来源：http://dali.shangyingyoupin.top/Article/details/gtywtlmkmm.html

$double = fn($x) => $x * 2;
来源：http://dali.yj20258888.top/Article/details/gtknlmlxlg.html

[U53] PHP：空合并运算符
来源：http://dali.316326.xyz/Article/details/gtvgfmtviy.html

$v = $a ?? $b ?? "default";
来源：http://dali.c1oappe.top/Article/details/gtfpywjokl.html

[U54] PHP：空安全调用
来源：http://dali.cashguo.top/Article/details/gtqafucojf.html

$obj?->method()
来源：http://dali.dashuyun.cn/Article/details/gttlqidolb.html

[U55] PHP：match 表达式
来源：http://dali.mhx1999.top/Article/details/gtusmsapae.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtsodikqwl.html

[U56] PHP：命名参数
来源：http://dali.andypj.xyz/Article/details/gtynkipukj.html

f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtwkehkpir.html

[U57] PHP：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtseaoaxeq.html

"值: {$a}"
来源：http://dali.chenjidiqi.icu/Article/details/gtgbymrrec.html

[U58] PHP：数组三件套
来源：http://dali.sxryk.cn/Article/details/gtkwejtpco.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtregawrwv.html

[U59] PHP：自定义排序
来源：http://dali.zhengqikj.top/Article/details/gtcihhzshn.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jqgufenzy.top/Article/details/gtovooogcz.html

[U60] PHP：JSON 编解码
来源：http://dali.jianghu66.top/Article/details/gtdemjeddh.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.daria6918.cn/Article/details/gtvgzzvyxl.html

[U61] PHP：正则
来源：http://dali.9152youxi.cn/Article/details/gttrzcegmx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.cucudq.cn/Article/details/gtmoidofdr.html

[U62] PHP：日期对象
来源：http://dali.zhijiandao.cn/Article/details/gtvymntrwj.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbdgdmvu.html

[U63] PHP：文件读写
来源：http://dali.zhixingplan.top/Article/details/gtjikodhjh.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.daria6918.cn/Article/details/gtqfsmdrsw.html

[U64] PHP：目录遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtfakjwwrf.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.hnxiangtu.top/Article/details/gtflqmkwrp.html

[U65] PHP：会话
来源：http://dali.ivvv.top/Article/details/gtrbfysoez.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.sysykeji.top/Article/details/gthruskcmj.html

[U66] PHP：设置 Cookie
来源：http://dali.birdmap.top/Article/details/gtsgmufqhk.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.sufxvd.cn/Article/details/gtlauutqfa.html

[U67] PHP：处理文件上传
来源：http://dali.havefunace.top/Article/details/gtzbpevjlc.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.hnqzz.top/Article/details/gtceijfolm.html

[U68] PHP：PDO 连接
来源：http://dali.jinqigfzy.top/Article/details/gtnejkwuni.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.ydzc1.top/Article/details/gtpmuulvpw.html

[U69] PHP：PDO 预处理
来源：http://dali.daxiang520.top/Article/details/gtjejfehot.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.sxryk.cn/Article/details/gtbdrpdccq.html

[U70] PHP：PDO 事务
来源：http://dali.snrcjt.cn/Article/details/gtcqciowkz.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.chenzaomai.com/Article/details/gtoyfmrggz.html

[U71] PHP：抛出异常
来源：http://dali.jqgufenzy.top/Article/details/gtmazqyecq.html

throw new RuntimeException("失败", 500);
来源：http://dali.dianchejie.cn/Article/details/gtrbvmvbwc.html

[U72] PHP：写错误日志
来源：http://dali.ppjwa.cn/Article/details/gtdrzokbrb.html

error_log("失败: " . $e->getMessage());
来源：http://dali.nwbrower.top/Article/details/gtoauwsecu.html

[U73] PHP：读取 ini 配置
来源：http://dali.gaohongyu789.top/Article/details/gtbgqyfvxf.html

parse_ini_file("config.ini", true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibdpecus.html

[U74] PHP：读取环境变量
来源：http://dali.jyoumei.cn/Article/details/gtnjqqotqo.html

getenv("APP_ENV") ?: "production"
来源：http://dali.haohaochexian.top/Article/details/gtftsxkdvu.html

[U75] PHP：依赖注入
来源：http://dali.guannengcc.top/Article/details/gttrbkhdua.html

composer require psr/container
来源：http://dali.zhongyouzk.top/Article/details/gtvxgdusza.html

[U76] PHP：简单路由
来源：http://dali.chenlongwang.top/Article/details/gtazhljobo.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.xylfe.cn/Article/details/gtsgiayeps.html

[U77] PHP：模板渲染
来源：http://dali.zdqjudy.top/Article/details/gtadjrusnu.html

composer require twig/twig
来源：http://dali.gotoacloud.top/Article/details/gtjpxzgxuj.html

[U78] PHP：单元测试
来源：http://dali.zycfv.cn/Article/details/gttgvwdufn.html

composer require --dev phpunit/phpunit
来源：http://dali.hywenlv.cn/Article/details/gtjfpfgqsm.html

[U79] PHP：静态分析
来源：http://dali.jinqigufen.top/Article/details/gtbfhjvcau.html

composer require --dev phpstan/phpstan
来源：http://dali.nwbrower.top/Article/details/gtjtwaalyt.html

[U80] PHP：代码规范修复
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogpapstv.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.wangshuangyany.cn/Article/details/gtwpobqryn.html

[U81] JS：初始化项目
来源：http://dali.ppjwa.cn/Article/details/gttrwtuwzx.html

npm init -y;  npm i express
来源：http://dali.mhx1999.top/Article/details/gtqbrmfhgz.html

[U82] JS：package.json 脚本
来源：http://dali.zycfv.cn/Article/details/gtudxrafqf.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.yuxming.cn/Article/details/gthpwfravz.html

[U83] JS：ES Module 导入导出
来源：http://dali.nanxuanxn.top/Article/details/gttprninyj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycfopszr.html

[U84] JS：CommonJS 写法
来源：http://dali.c1oappe.top/Article/details/gtxjqpgvsu.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zhijiandao.cn/Article/details/gtryyizisf.html

[U85] JS：可选链
来源：http://dali.zhixingplan.top/Article/details/gtaxjynyrl.html

a?.b?.c
来源：http://dali.meibo888.top/Article/details/gtljfavzyr.html

[U86] JS：空值合并
来源：http://dali.c1oappe.top/Article/details/gtiwkdalex.html

a ?? b
来源：http://dali.zhoulong.xyz/Article/details/gtvffarovs.html

[U87] JS：解构默认值
来源：http://dali.nanxuanxn.top/Article/details/gtbunvctqd.html

const { a = 1, b = 2 } = obj;
来源：http://dali.guowangkeji.top/Article/details/gtsmovcphj.html

[U88] JS：对象展开合并
来源：http://dali.wangshuangyany.cn/Article/details/gtkzdralxh.html

{ ...a, ...b }
来源：http://dali.mhx1999.top/Article/details/gtdhqogddb.html

[U89] JS：数组去重
来源：http://dali.zycfv.cn/Article/details/gtvfpglepy.html

[...new Set(arr)]
来源：http://dali.hnqzz.top/Article/details/gtbquwixuq.html

[U90] JS：数字数组排序
来源：http://dali.hysaishi.cn/Article/details/gtfszhhwrf.html

[...arr].sort((a, b) => a - b)
来源：http://dali.ybcxt.top/Article/details/gtjxulspgu.html

[U91] JS：对象键值遍历
来源：http://dali.ivvv.top/Article/details/gtyetfuyoc.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.yj202588.top/Article/details/gtmzupimcg.html

[U92] JS：深拷贝
来源：http://dali.hywenlv.cn/Article/details/gtwwaprnbj.html

structuredClone(obj)
来源：http://dali.redwolf501.top/Article/details/gtxjkdtwar.html

[U93] JS：模板字符串
来源：http://dali.yonumen.top/Article/details/gtjljvjuxg.html

`共 ${n} 条`
来源：http://dali.feifeiyinyue.top/Article/details/gtvsnhhrku.html

[U94] JS：箭头函数
来源：http://dali.c1oappe.top/Article/details/gtmqescbst.html

const double = x => x * 2;
来源：http://dali.snrcjt.cn/Article/details/gtsdzffhhy.html

[U95] JS：Promise 包装
来源：http://dali.jqgufenzy.top/Article/details/gtmrhahrve.html

new Promise((resolve, reject) => {})
来源：http://dali.sweek.top/Article/details/gtfjxggewx.html

[U96] JS：async/await 与异常
来源：http://dali.tianlin.xyz/Article/details/gtbqhpegdk.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.zdqjudy.top/Article/details/gtlzqfrckc.html

[U97] JS：并发请求
来源：http://dali.daria6918.cn/Article/details/gtkrfypldo.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.c1oappe.top/Article/details/gtlmisimvg.html

[U98] JS：fetch 带 JSON
来源：http://dali.jianghu66.top/Article/details/gtedgopdqo.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.sxryk.cn/Article/details/gtsiazywfy.html

[U99] JS：事件监听
来源：http://dali.cheryme.top/Article/details/gthgqkrwbi.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangtech.top/Article/details/gtebmabgxd.html

[U100] JS：DOM 查询
来源：http://dali.316326.xyz/Article/details/gtmkeuunqh.html

document.querySelector(".item")
来源：http://dali.feifeiyinyue.top/Article/details/gtyjnnmcyx.html

[U101] JS：classList 操作
来源：http://dali.xziqi.cn/Article/details/gtodkocwpz.html

el.classList.toggle("active")
来源：http://dali.0kj1m.cn/Article/details/gtwvbwkpsk.html

[U102] JS：本地存储
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndohdmdw.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.9152youxi.cn/Article/details/gtoecjjddx.html

[U103] JS：定时器
来源：http://dali.mhx1999.top/Article/details/gtemqnjnhk.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjjkemir.html

[U104] JS：防抖
来源：http://dali.nanxuanxn.top/Article/details/gtrntiotyx.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.shangyingyoupin.top/Article/details/gtzjnahaxt.html

[U105] JS：节流
来源：http://dali.gogol.net.cn/Article/details/gtjkyuefee.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.9152youxi.cn/Article/details/gtlwldbqda.html

[U106] JS：日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gteectitoz.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.jyoumei.cn/Article/details/gtbjwldsjy.html

[U107] JS：数字千分位
来源：http://dali.xuetiantiany.cn/Article/details/gtnphxobly.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.shuidangran.top/Article/details/gtxqxmlxua.html

[U108] JS：随机整数
来源：http://dali.hfpthk.cn/Article/details/gtfshvwtte.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.cucudq.cn/Article/details/gtvuouxqas.html

[U109] JS：数组分组
来源：http://dali.tanke756.top/Article/details/gtfogcssei.html

Object.groupBy(arr, x => x.type)
来源：http://dali.shzxlz.cn/Article/details/gtgkhtccgt.html

[U110] JS：数组分块
来源：http://dali.hnxiangtu.top/Article/details/gtcmwxvxaw.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.xylfe.cn/Article/details/gtprlwifdl.html

[U111] JS：对象转 Map
来源：http://dali.kuanghao11.cn/Article/details/gtpfyyczff.html

new Map(Object.entries(obj))
来源：http://dali.meibo888.top/Article/details/gtvapeaclw.html

[U112] JS：字符串补位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykqlwiex.html

"7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtpgvvxocg.html

[U113] JS：正则替换全部
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzudjoglk.html

s.replaceAll("a", "b")
来源：http://dali.zhengqikj.top/Article/details/gtluqkafgd.html

[U114] JS：JSON 深比较
来源：http://dali.316326.xyz/Article/details/gtokvohtcl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.gotoacloud.top/Article/details/gtalswcbgs.html

[U115] JS：生成 UUID
来源：http://dali.yj20258888.top/Article/details/gtqzomkxpl.html

crypto.randomUUID()
来源：http://dali.zhoulong.xyz/Article/details/gtyjbebbhl.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.birdmap.top/Article/details/gtrrnqzsoy.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtewxwoctn.html

[U117] JS：单元测试
来源：http://dali.iojbl.cn/Article/details/gtavjrcfcj.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gtmnscarxl.html

[U118] JS：开发服务器
来源：http://dali.daria6918.cn/Article/details/gtssfsqycb.html

npm i -D vite;  npx vite
来源：http://dali.birdmap.top/Article/details/gtccnkclrq.html

[U119] JS：生产构建
来源：http://dali.yongpay.top/Article/details/gtuqywmbvu.html

npx vite build
来源：http://dali.xuetiantiany.cn/Article/details/gthzuifjsl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.c1oappe.top/Article/details/gtifpicpvt.html

import.meta.env.VITE_API_URL
来源：http://dali.jlsjyb.cn/Article/details/gthajeowrk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttrukeuz.html

统计汇总
来源：http://dali.yj20258888.top/Article/details/gtmcvjlhee.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtwrhtolgh.html

按语言统计（条）：
来源：http://dali.dashuyun.cn/Article/details/gtsqaxgbgm.html

Python ......... 252
来源：http://dali.kuanghao11.cn/Article/details/gtteplzfsm.html

PHP ............ 252
来源：http://dali.jianghu66.top/Article/details/gttcxkdmmi.html

JavaScript ..... 252
来源：http://dali.xuanzx.com/Article/details/gtdnmtcrzr.html

TypeScript ..... 212
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlyimsgma.html

Java ........... 212
来源：http://dali.tianlin.xyz/Article/details/gtfttofbso.html

Go ............. 212
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbjzkpxq.html

Ruby ........... 212
来源：http://dali.daria6918.cn/Article/details/gtyhklfzcx.html

C# ............. 212
来源：http://dali.hammf.cn/Article/details/gtqhushjzc.html

C .............. 30
来源：http://dali.chenjidiqi.icu/Article/details/gtbgwlrmyt.html

C++ ............ 30
来源：http://dali.feifeiyinyue.top/Article/details/gttanjcypc.html

SQL ............ 90
来源：http://dali.zhiwuduotai.top/Article/details/gtukzxxgvk.html

Bash ........... 80
来源：http://dali.guowangkeji.top/Article/details/gtihsplonl.html

Kotlin ......... 15
来源：http://dali.ehwqpu.com/Article/details/gttakrraje.html

Swift .......... 15
来源：http://dali.hnxiangtu.top/Article/details/gtnvhzwted.html

Lua ............ 10
来源：http://dali.gotoacloud.top/Article/details/gttekeucyk.html

Perl ........... 10
来源：http://dali.haohaochexian.top/Article/details/gtgcxrcjnm.html

Scala .......... 10
来源：http://dali.iojbl.cn/Article/details/gtmomsvdha.html

------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gtowiwqnmc.html

合计 ........... 2106 条
来源：http://dali.havefunace.top/Article/details/gttkvhytlg.html

按章节统计：
来源：http://dali.iojbl.cn/Article/details/gtzjcmgknd.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauzhudcf.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gtsdkhwygl.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.xziqi.cn/Article/details/gtgjrosbnw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.andypj.xyz/Article/details/gtklphzrsy.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.meibo888.top/Article/details/gtxxcvjkte.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.andypj.xyz/Article/details/gtmtbohjnp.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.guowangkeji.top/Article/details/gtwfkfxvku.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.jlsjyb.cn/Article/details/gtpbwrhbam.html


<!-- 参考信息 -->