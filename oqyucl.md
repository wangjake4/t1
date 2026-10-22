代发 wailian999

[T33] Lua：表（数组）
来源：http://dali.feifeiyinyue.top/Article/details/gtwjkcmjew.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shangyingyoupin.top/Article/details/gtwpouihvd.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtmcepczfc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.meibo888.top/Article/details/gtcjgwzgwu.html

[T35] Lua：字典表
来源：http://dali.ppjwa.cn/Article/details/gtyvpnbcyn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtsgvzkpyf.html

[T36] Lua：函数
来源：http://dali.yanxiufei.cn/Article/details/gtydrovczq.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtqwapzser.html

[T37] Lua：字符串拼接
来源：http://dali.mhx1999.top/Article/details/gtyiqjsvpn.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtbhwvugsk.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtylsixjmd.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtpsyqlcvb.html

[T39] Lua：模式匹配
来源：http://dali.zhijiandao.cn/Article/details/gtgbzececi.html

string.find(s, "%d+")
来源：http://dali.feifeiyinyue.top/Article/details/gtzzvgtjxu.html

[T40] Lua：元表
来源：http://dali.aibaodan.cn/Article/details/gtpbaplevl.html

setmetatable({}, { __index = base })
来源：http://dali.kuanghao11.cn/Article/details/gtnikwxmow.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtouvdsulu.html

print "Hello\n";
来源：http://dali.aibaodan.cn/Article/details/gtbecbjxiz.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtoqhbpxxk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjwxtegk.html

[T43] Perl：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtmhwsnltc.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtcjcmfbzu.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtewulikez.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmbrhknyo.html

[T45] Perl：数组遍历
来源：http://dali.mhx1999.top/Article/details/gtpvesjxyw.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtihdhqnor.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtxoarouan.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sufxvd.cn/Article/details/gthcgwaqhc.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gtpnetpbgx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtlbfeqcot.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpmyhwwv.html

$s =~ s/old/new/g;
来源：http://dali.aibaodan.cn/Article/details/gtanccljky.html

[T49] Perl：函数
来源：http://dali.jqgfzy.top/Article/details/gtvcveprly.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtasfwnthl.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtznuwbney.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtggujlxuy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtfvwihxqn.html

[T51] Scala：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtxejeldda.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtzmuvbipv.html

[T52] Scala：变量
来源：http://dali.wangdashe.top/Article/details/gtckntjbnt.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtefupurfj.html

[T53] Scala：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtotqzogip.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtsgteteme.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtvctcyqmz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jlsjyb.cn/Article/details/gtjwuzeojo.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtcnrjwckr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.redwolf501.top/Article/details/gtmsaorpmp.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gtaaizvyyk.html

case class User(name: String, age: Int)
来源：http://dali.vqdsnc.cn/Article/details/gtchdfymma.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtzpoenwbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhixingplan.top/Article/details/gtwahjomro.html

[T58] Scala：函数定义
来源：http://dali.xylfe.cn/Article/details/gttuaiqzro.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jiagoushi.top/Article/details/gttxwynvan.html

[T59] Scala：循环
来源：http://dali.0kj1m.cn/Article/details/gtjtqoanrc.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtijksnebw.html

[T60] Scala：折叠
来源：http://dali.aizwys.cn/Article/details/gtezvexlin.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtyhmmhhto.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gthnqrpwvv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.aizwys.cn/Article/details/gthnllhgon.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtikkrglkb.html

[U01] Py：创建虚拟环境
来源：http://dali.cucudq.cn/Article/details/gtosybjryz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jlsjyb.cn/Article/details/gtgczhtupr.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtsatwixrt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.haohaochexian.top/Article/details/gtxzgtsitz.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gttcugurrj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gtmbpdtswk.html

[U04] Py：变量调试打印
来源：http://dali.xuanzx.com/Article/details/gtyglwklku.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.iojbl.cn/Article/details/gtdqiqtzxh.html

[U05] Py：列表去重且保序
来源：http://dali.yvedp.cn/Article/details/gtnnwcxhfw.html

list(dict.fromkeys(arr))
来源：http://dali.316326.xyz/Article/details/gtabczxodd.html

[U06] Py：合并两个字典
来源：http://dali.aizwys.cn/Article/details/gtzvzprwda.html

{**a, **b}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhjyzbcq.html

[U07] Py：反转字典键值
来源：http://dali.andypj.xyz/Article/details/gtvwkjnwvd.html

{v: k for k, v in d.items()}
来源：http://dali.mhx1999.top/Article/details/gtqkgaklsa.html

[U08] Py：展平二维列表
来源：http://dali.cdnleiting.top/Article/details/gtspxqqiuw.html

[y for x in nested for y in x]
来源：http://dali.xuanzx.com/Article/details/gtnjwhaisg.html

[U09] Py：字典取最大值的键
来源：http://dali.shuidangran.top/Article/details/gttdffjbyf.html

max(d, key=d.get)
来源：http://dali.hywenlv.cn/Article/details/gtdppgiifj.html

[U10] Py：按值排序字典
来源：http://dali.daria6918.cn/Article/details/gtakkmpefv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gtnmgkzruf.html

[U11] Py：生成器表达式
来源：http://dali.hnqzz.top/Article/details/gtpnhqwqxg.html

(x * 2 for x in arr)
来源：http://dali.quarkkingdee.top/Article/details/gtgptgwleq.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.shuidangran.top/Article/details/gtrgerlazx.html

Counter(arr).most_common(3)
来源：http://dali.pycfn.com/Article/details/gtmozhjlsk.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gtfnoxlkzm.html

deque(maxlen=10)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtozldvllu.html

[U14] Py：分组收集到列表
来源：http://dali.yuanzhike.top/Article/details/gteajgiuuo.html

defaultdict(list)
来源：http://dali.andypj.xyz/Article/details/gtuyiifpgw.html

[U15] Py：高精度计时
来源：http://dali.zhijiandao.cn/Article/details/gtsdviyova.html

t = time.perf_counter()
来源：http://dali.wangdashe.top/Article/details/gtpqphrvut.html

[U16] Py：命令行参数解析
来源：http://dali.jqgfzy.top/Article/details/gtguqpinkd.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.hammf.cn/Article/details/gtrhzdidjk.html

[U17] Py：初始化日志
来源：http://dali.fzhhl.top/Article/details/gtgygeqhqn.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.hongshengwenyu.top/Article/details/gtseuelgqp.html

[U18] Py：预编译正则
来源：http://dali.cdnleiting.top/Article/details/gtjbagxgdx.html

pat = re.compile(r"\d+")
来源：http://dali.cheryme.top/Article/details/gtvzndixbj.html

[U19] Py：正则替换带回调
来源：http://dali.xuanzx.com/Article/details/gtjlkgkkwm.html

re.sub(r"\d+", lambda m: str(int(m.group()) * 2), s)
来源：http://dali.cashguo.top/Article/details/gtkwaphxcu.html

[U20] Py：缓存函数结果
来源：http://dali.yuxming.cn/Article/details/gtrbwyrlaj.html

@functools.lru_cache(maxsize=None)
来源：http://dali.yangfankeji.com/Article/details/gtcihjexqx.html

[U21] Py：自定义上下文管理器
来源：http://dali.shzxlz.cn/Article/details/gtcakrnrea.html

@contextlib.contextmanager
来源：http://dali.snrcjt.cn/Article/details/gtioziyrra.html

[U22] Py：矩阵转置
来源：http://dali.sufxvd.cn/Article/details/gttufzhcev.html

list(zip(*m))
来源：http://dali.ybcxt.top/Article/details/gtctopiuvg.html

[U23] Py：分块读取大文件
来源：http://dali.aibaodan.cn/Article/details/gtkcdwesrc.html

for chunk in iter(lambda: f.read(8192), b""):
来源：http://dali.tian-w.cn/Article/details/gtlwgtjapb.html

[U24] Py：路径操作
来源：http://dali.zhongyouzk.top/Article/details/gttxifnbnt.html

Path("a/b.txt").parent.mkdir(parents=True, exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gthuqgblxt.html

[U25] Py：CSV 按字典读
来源：http://dali.hammf.cn/Article/details/gtzystnltw.html

csv.DictReader(f)
来源：http://dali.cheryme.top/Article/details/gtmbtxnbhy.html

[U26] Py：并发下载
来源：http://dali.ybcxt.top/Article/details/gthimmnays.html

ThreadPoolExecutor(max_workers=8).map(fetch, urls)
来源：http://dali.pengpengdd.cyou/Article/details/gtsuqpaiwo.html

[U27] Py：异步 HTTP
来源：http://dali.hammf.cn/Article/details/gtntlzgvda.html

aiohttp.ClientSession() 配合 async with
来源：http://dali.dashuyun.cn/Article/details/gtstjyulau.html

[U28] Py：类型别名
来源：http://dali.cucudq.cn/Article/details/gtzgumkqfh.html

UserId = int
来源：http://dali.guowangkeji.top/Article/details/gtoivdubzt.html

[U29] Py：属性校验
来源：http://dali.aibaodan.cn/Article/details/gtfxdlsmay.html

@property 与 @x.setter 配合
来源：http://dali.jqgfzy.top/Article/details/gtgmruvjrf.html

[U30] Py：数据类
来源：http://dali.jiagoushi.top/Article/details/gtjktnlazg.html

@dataclass(slots=True)
来源：http://dali.jqgufenzy.top/Article/details/gtueaekciu.html

[U31] Py：单测
来源：http://dali.zdqjudy.top/Article/details/gtekkznqdp.html

python -m pytest -q
来源：http://dali.shuidangran.top/Article/details/gtlcxpunac.html

[U32] Py：代码格式化
来源：http://dali.iojbl.cn/Article/details/gtebvickug.html

ruff format . && ruff check --fix .
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszwkzeua.html

[U33] Py：打包发布
来源：http://dali.pengpengdd.cyou/Article/details/gtmpbccuoy.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrixzqssz.html

[U34] Py：判断编码
来源：http://dali.zhengqikj.top/Article/details/gtcpgixpir.html

chardet.detect(raw)
来源：http://dali.haohaochexian.top/Article/details/gtkrkanxhe.html

[U35] Py：发送邮件
来源：http://dali.svipenyu.cn/Article/details/gtopyzdafn.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.fengsongda.top/Article/details/gtwdamqfwm.html

[U36] Py：定时任务
来源：http://dali.cqqwz.cn/Article/details/gtnvaopmfw.html

schedule.every(10).minutes.do(job)
来源：http://dali.wangdashe.top/Article/details/gtbaucidtr.html

[U37] Py：读写 Excel
来源：http://dali.tian-w.cn/Article/details/gthnrhebgq.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.shzxlz.cn/Article/details/gtlphbmeam.html

[U38] Py：获取脚本所在目录
来源：http://dali.zhongyouzk.top/Article/details/gtsdeszrvu.html

Path(__file__).resolve().parent
来源：http://dali.cheryme.top/Article/details/gtvhxjzstr.html

[U39] Py：判断是否在交互环境
来源：http://dali.guowangkeji.top/Article/details/gtbqgvtoln.html

sys.stdout.isatty()
来源：http://dali.pycfn.com/Article/details/gtntbtdodx.html

[U40] Py：打印到标准错误
来源：http://dali.daria6918.cn/Article/details/gtnfigogdf.html

print("err", file=sys.stderr)
来源：http://dali.aibaodan.cn/Article/details/gtoszevcbt.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.snrcjt.cn/Article/details/gtzweyafti.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.cdnleiting.top/Article/details/gtnswzcvrc.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.jinqigufen.top/Article/details/gtpnkxycyz.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.guannengcc.top/Article/details/gttuwfwumi.html

[U43] PHP：声明命名空间
来源：http://dali.xziqi.cn/Article/details/gtkxeblkit.html

namespace App\Http;
来源：http://dali.hysaishi.cn/Article/details/gttjeyxiye.html

[U44] PHP：开启严格类型
来源：http://dali.0kj1m.cn/Article/details/gtlyhwowez.html

declare(strict_types=1);
来源：http://dali.0kj1m.cn/Article/details/gtvpjyqklj.html

[U45] PHP：类型声明与返回类型
来源：http://dali.cdnleiting.top/Article/details/gtggogfeyr.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gttnaezoud.html

[U46] PHP：可空类型
来源：http://dali.shzxlz.cn/Article/details/gtrregumve.html

?string $name = null
来源：http://dali.aizwys.cn/Article/details/gtjimesail.html

[U47] PHP：联合类型
来源：http://dali.yonumen.top/Article/details/gtnfewgbeg.html

int|string $id
来源：http://dali.jinghuilouyu.cn/Article/details/gtlxzvubaq.html

[U48] PHP：纯枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtqzswwbnb.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.fzhhl.top/Article/details/gtqosgmuwl.html

[U49] PHP：只读属性
来源：http://dali.jianghu66.top/Article/details/gtobjtxjyy.html

public readonly string $name
来源：http://dali.aibaodan.cn/Article/details/gtpyqtomwp.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gtaualrowb.html

public function __construct(private int $id) {}
来源：http://dali.c1oappe.top/Article/details/gtfxafvkdz.html

[U51] PHP：数组解构
来源：http://dali.yvedp.cn/Article/details/gtthlzmffq.html

[$a, $b] = $arr;
来源：http://dali.zhiwuduotai.top/Article/details/gtrekletfu.html

[U52] PHP：箭头函数
来源：http://dali.snrcjt.cn/Article/details/gtljjvqypg.html

$double = fn($x) => $x * 2;
来源：http://dali.smart0.xyz/Article/details/gttsxxxxhb.html

[U53] PHP：空合并运算符
来源：http://dali.hnxiangtu.top/Article/details/gtfsgdcryu.html

$v = $a ?? $b ?? "default";
来源：http://dali.zhongyouzk.top/Article/details/gtsztlskbb.html

[U54] PHP：空安全调用
来源：http://dali.shuidangran.top/Article/details/gtrarrenhy.html

$obj?->method()
来源：http://dali.aizwys.cn/Article/details/gtbnjdmfsl.html

[U55] PHP：match 表达式
来源：http://dali.ivvv.top/Article/details/gtlvvczrvp.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.c1oappe.top/Article/details/gtqzmxuwwu.html

[U56] PHP：命名参数
来源：http://dali.kuanghao11.cn/Article/details/gteaapupma.html

f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtwidrumit.html

[U57] PHP：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtydmsrohb.html

"值: {$a}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqfjfhcs.html

[U58] PHP：数组三件套
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsyfqyks.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtjzctwkxe.html

[U59] PHP：自定义排序
来源：http://dali.yangfankeji.com/Article/details/gtdgculauc.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.xziqi.cn/Article/details/gtykvdbmme.html

[U60] PHP：JSON 编解码
来源：http://dali.zhiwuduotai.top/Article/details/gtjmdjzzfs.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.nanxinkj.top/Article/details/gtdaggjbod.html

[U61] PHP：正则
来源：http://dali.guannengcc.top/Article/details/gtltvpklsi.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.daxiang520.top/Article/details/gtkfshxaef.html

[U62] PHP：日期对象
来源：http://dali.nanxuanxn.top/Article/details/gtvgvayuxx.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.yj202588.top/Article/details/gtqsoccaeu.html

[U63] PHP：文件读写
来源：http://dali.shuidangran.top/Article/details/gtfbrzogbc.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.shangyingyoupin.top/Article/details/gtjzdjpxts.html

[U64] PHP：目录遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqlvlkyx.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.9152youxi.cn/Article/details/gtytnbjnmn.html

[U65] PHP：会话
来源：http://dali.sxryk.cn/Article/details/gtjemhuwyu.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtxlqtnext.html

[U66] PHP：设置 Cookie
来源：http://dali.wangdashe.top/Article/details/gtahytnaao.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yonumen.top/Article/details/gtxedmesjc.html

[U67] PHP：处理文件上传
来源：http://dali.cdnleiting.top/Article/details/gtdzdgdylg.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.tanke756.top/Article/details/gtlkbxgrax.html

[U68] PHP：PDO 连接
来源：http://dali.hongshengwenyu.top/Article/details/gtjaoonujc.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfgfgvyt.html

[U69] PHP：PDO 预处理
来源：http://dali.cashguo.top/Article/details/gtthzaduhq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.ppjwa.cn/Article/details/gtfqavbyps.html

[U70] PHP：PDO 事务
来源：http://dali.guannengcc.top/Article/details/gtuwriafwu.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.cheryme.top/Article/details/gtoaovpued.html

[U71] PHP：抛出异常
来源：http://dali.hywenlv.cn/Article/details/gtbddtpjre.html

throw new RuntimeException("失败", 500);
来源：http://dali.kuanghao11.cn/Article/details/gtioewmxbd.html

[U72] PHP：写错误日志
来源：http://dali.zhijiandao.cn/Article/details/gtnyxufbco.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jiagoushi.top/Article/details/gtfonzkogv.html

[U73] PHP：读取 ini 配置
来源：http://dali.xinyue.icu/Article/details/gtmhqlyzgp.html

parse_ini_file("config.ini", true)
来源：http://dali.xinyue.icu/Article/details/gtvjsmrbjl.html

[U74] PHP：读取环境变量
来源：http://dali.haohaochexian.top/Article/details/gtowvuogss.html

getenv("APP_ENV") ?: "production"
来源：http://dali.jqgfzy.top/Article/details/gtmcorislg.html

[U75] PHP：依赖注入
来源：http://dali.quarkkingdee.top/Article/details/gtyxbifits.html

composer require psr/container
来源：http://dali.yuxming.cn/Article/details/gtimrwnkbv.html

[U76] PHP：简单路由
来源：http://dali.dianchejie.cn/Article/details/gtlnvpagjv.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.nanxuanxn.top/Article/details/gtyiazfwhx.html

[U77] PHP：模板渲染
来源：http://dali.hnxiangtu.top/Article/details/gtbtxvuwsc.html

composer require twig/twig
来源：http://dali.mhx1999.top/Article/details/gtutsycmgz.html

[U78] PHP：单元测试
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgqntkio.html

composer require --dev phpunit/phpunit
来源：http://dali.sxryk.cn/Article/details/gtzfbrrezl.html

[U79] PHP：静态分析
来源：http://dali.cdnleiting.top/Article/details/gtwiwjible.html

composer require --dev phpstan/phpstan
来源：http://dali.aizwys.cn/Article/details/gtyoedghvk.html

[U80] PHP：代码规范修复
来源：http://dali.hnqzz.top/Article/details/gtjfjfbtod.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.c1oappe.top/Article/details/gtefnkugqe.html

[U81] JS：初始化项目
来源：http://dali.nanxuanxn.top/Article/details/gtkxtyxcjo.html

npm init -y;  npm i express
来源：http://dali.nwbrower.top/Article/details/gtfaflonwr.html

[U82] JS：package.json 脚本
来源：http://dali.gaohongyu789.top/Article/details/gtrxvhkkoc.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.quarkkingdee.top/Article/details/gtvjommcmw.html

[U83] JS：ES Module 导入导出
来源：http://dali.guowangkeji.top/Article/details/gtfvtueorn.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtwtwxycwv.html

[U84] JS：CommonJS 写法
来源：http://dali.aizwys.cn/Article/details/gtfkeohzki.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.smart0.xyz/Article/details/gtwpzhraxe.html

[U85] JS：可选链
来源：http://dali.gotoacloud.top/Article/details/gtkiuhwwej.html

a?.b?.c
来源：http://dali.tanke756.top/Article/details/gtzwbcsqky.html

[U86] JS：空值合并
来源：http://dali.zhongyouzk.top/Article/details/gtfevqnzvc.html

a ?? b
来源：http://dali.cucudq.cn/Article/details/gtpjihuxcg.html

[U87] JS：解构默认值
来源：http://dali.yj20258888.top/Article/details/gtlrwfxawc.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yangfankeji.com/Article/details/gtycmuhbas.html

[U88] JS：对象展开合并
来源：http://dali.gogol.net.cn/Article/details/gtsehkfnrz.html

{ ...a, ...b }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkqmmcdm.html

[U89] JS：数组去重
来源：http://dali.tian-w.cn/Article/details/gtgofigsmf.html

[...new Set(arr)]
来源：http://dali.zhongyouzk.top/Article/details/gtotusbdro.html

[U90] JS：数字数组排序
来源：http://dali.shzxlz.cn/Article/details/gtlemymfgh.html

[...arr].sort((a, b) => a - b)
来源：http://dali.jianghu66.top/Article/details/gtnjijppfz.html

[U91] JS：对象键值遍历
来源：http://dali.hywenlv.cn/Article/details/gtfhlqpqlo.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.dianchejie.cn/Article/details/gtkwugpssf.html

[U92] JS：深拷贝
来源：http://dali.cdnleiting.top/Article/details/gtmvdmtvnc.html

structuredClone(obj)
来源：http://dali.hnqzz.top/Article/details/gtmjekdzao.html

[U93] JS：模板字符串
来源：http://dali.jinqigfzy.top/Article/details/gtexqsxtev.html

`共 ${n} 条`
来源：http://dali.tian-w.cn/Article/details/gternldcby.html

[U94] JS：箭头函数
来源：http://dali.ydzc1.top/Article/details/gtqxrkdqte.html

const double = x => x * 2;
来源：http://dali.xinyue.icu/Article/details/gtywvxkgex.html

[U95] JS：Promise 包装
来源：http://dali.pengpengdd.cyou/Article/details/gtscfwrsck.html

new Promise((resolve, reject) => {})
来源：http://dali.svipenyu.cn/Article/details/gtggncjren.html

[U96] JS：async/await 与异常
来源：http://dali.pengpengdd.cyou/Article/details/gtmgvgndar.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.meibo888.top/Article/details/gtnrvfklpe.html

[U97] JS：并发请求
来源：http://dali.guowangkeji.top/Article/details/gtadftboyl.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.aizwys.cn/Article/details/gtlgwesoxy.html

[U98] JS：fetch 带 JSON
来源：http://dali.ppjwa.cn/Article/details/gtdrpvslna.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.xuetiantiany.cn/Article/details/gtjrgnmffo.html

[U99] JS：事件监听
来源：http://dali.smart0.xyz/Article/details/gtugwrryew.html

el.addEventListener("click", e => {})
来源：http://dali.nanxuanxn.top/Article/details/gtxkalkesi.html

[U100] JS：DOM 查询
来源：http://dali.gotoacloud.top/Article/details/gtiqmyggkl.html

document.querySelector(".item")
来源：http://dali.gotoacloud.top/Article/details/gtnlmmsflu.html

[U101] JS：classList 操作
来源：http://dali.ehwqpu.com/Article/details/gtjcxteokk.html

el.classList.toggle("active")
来源：http://dali.zycfv.cn/Article/details/gtaikbjlhh.html

[U102] JS：本地存储
来源：http://dali.aizwys.cn/Article/details/gtmnbyfshr.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.yj202588.top/Article/details/gtxofeklov.html

[U103] JS：定时器
来源：http://dali.birdmap.top/Article/details/gtcgxdeowd.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.yj20258888.top/Article/details/gtwumtqkxk.html

[U104] JS：防抖
来源：http://dali.yueranfly.top/Article/details/gtqnghrpvp.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.guowangkeji.top/Article/details/gtgdtxjlew.html

[U105] JS：节流
来源：http://dali.aibaodan.cn/Article/details/gtvqnbzghj.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.cdnleiting.top/Article/details/gtdluhabom.html

[U106] JS：日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnbracoa.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.shanyushiyangtech.top/Article/details/gtqejdoxbs.html

[U107] JS：数字千分位
来源：http://dali.yj20258.top/Article/details/gtxogpuvjq.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.jqgufenzy.top/Article/details/gtvbkxnjju.html

[U108] JS：随机整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtauqmakoi.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.dashuyun.cn/Article/details/gtmdrdgyer.html

[U109] JS：数组分组
来源：http://dali.jinqigufen.top/Article/details/gtyudehvua.html

Object.groupBy(arr, x => x.type)
来源：http://dali.chenlongwang.top/Article/details/gtoefkxjxt.html

[U110] JS：数组分块
来源：http://dali.yj202588.top/Article/details/gtvljrcbsf.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.redwolf501.top/Article/details/gtvavzvkmk.html

[U111] JS：对象转 Map
来源：http://dali.jinqigfzy.top/Article/details/gtzsjriiwg.html

new Map(Object.entries(obj))
来源：http://dali.cqqwz.cn/Article/details/gtwerqzvfg.html

[U112] JS：字符串补位
来源：http://dali.xziqi.cn/Article/details/gtrqhzowdd.html

"7".padStart(3, "0")
来源：http://dali.jinqigufen.top/Article/details/gtflagygwi.html

[U113] JS：正则替换全部
来源：http://dali.daria6918.cn/Article/details/gtqrrdhpcr.html

s.replaceAll("a", "b")
来源：http://dali.zhiwuduotai.top/Article/details/gtvzjoxits.html

[U114] JS：JSON 深比较
来源：http://dali.snrcjt.cn/Article/details/gthfoduxas.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.chenlongwang.top/Article/details/gtaoskrcli.html

[U115] JS：生成 UUID
来源：http://dali.quarkkingdee.top/Article/details/gtykrzkgwi.html

crypto.randomUUID()
来源：http://dali.jinqigfzy.top/Article/details/gtrcvdwysc.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.hammf.cn/Article/details/gtsalqwoql.html

/** @param {string} name */ function f(name) {}
来源：http://dali.cdnleiting.top/Article/details/gtwbdsocyh.html

[U117] JS：单元测试
来源：http://dali.hnxiangtu.top/Article/details/gtefszhoxw.html

npm i -D vitest;  npx vitest
来源：http://dali.wangdashe.top/Article/details/gtckrkzvto.html

[U118] JS：开发服务器
来源：http://dali.sufxvd.cn/Article/details/gtyyifynsi.html

npm i -D vite;  npx vite
来源：http://dali.yj20258.top/Article/details/gtvmyzigoc.html

[U119] JS：生产构建
来源：http://dali.pycfn.com/Article/details/gtnxpkdrrk.html

npx vite build
来源：http://dali.ppjwa.cn/Article/details/gtkiqyrdrk.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.chenjidiqi.icu/Article/details/gtxpgbnknf.html

import.meta.env.VITE_API_URL
来源：http://dali.ivvv.top/Article/details/gtlfmcnuwk.html


<!-- 参考信息 -->