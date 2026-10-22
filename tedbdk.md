代发 wailian999

[U33] Py：打包发布
来源：http://dali.yuanzhike.top/Article/details/gt2kjzdicxq.html

python -m build  （依赖 pyproject.toml）
来源：http://dali.aizwys.cn/Article/details/gt2rjbwqklt.html

[U34] Py：判断编码
来源：http://dali.hnxiangtu.top/Article/details/gt2tpjrbhql.html

chardet.detect(raw)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2utptwwsw.html

[U35] Py：发送邮件
来源：http://dali.c1oappe.top/Article/details/gt2eouqqgrw.html

smtplib.SMTP_SSL(...).send_message(msg)
来源：http://dali.zhongyouzk.top/Article/details/gt2ivtqckks.html

[U36] Py：定时任务
来源：http://dali.xuanzx.com/Article/details/gt2dsbnvjrc.html

schedule.every(10).minutes.do(job)
来源：http://dali.hnxiangtu.top/Article/details/gt2xdhcotpx.html

[U37] Py：读写 Excel
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbanyvjg.html

pandas.read_excel / DataFrame.to_excel
来源：http://dali.yonumen.top/Article/details/gt2ibatyzff.html

[U38] Py：获取脚本所在目录
来源：http://dali.ppjwa.cn/Article/details/gt2ogxxjjjl.html

Path(__file__).resolve().parent
来源：http://dali.sufxvd.cn/Article/details/gt2sxflrzpg.html

[U39] Py：判断是否在交互环境
来源：http://dali.aibaodan.cn/Article/details/gt2allrfqpj.html

sys.stdout.isatty()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kjoikzfn.html

[U40] Py：打印到标准错误
来源：http://dali.yueranfly.top/Article/details/gt2fuxriyub.html

print("err", file=sys.stderr)
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhylekuf.html

[U41] PHP：初始化 Composer 项目
来源：http://dali.yj20258.top/Article/details/gt2trcpqdev.html

composer init;  composer require guzzlehttp/guzzle
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rkbocklh.html

[U42] PHP：PSR-4 自动加载
来源：http://dali.wangshuangyany.cn/Article/details/gt2xsxnrvvf.html

"autoload": { "psr-4": { "App\\": "src/" } }
来源：http://dali.hfpthk.cn/Article/details/gt2wkjmepja.html

[U43] PHP：声明命名空间
来源：http://dali.jyoumei.cn/Article/details/gt2ozchtels.html

namespace App\Http;
来源：http://dali.havefunace.top/Article/details/gt2chopsicu.html

[U44] PHP：开启严格类型
来源：http://dali.xuanzx.com/Article/details/gt2tgdfoezm.html

declare(strict_types=1);
来源：http://dali.sufxvd.cn/Article/details/gt2uwknvfmq.html

[U45] PHP：类型声明与返回类型
来源：http://dali.yonumen.top/Article/details/gt2caivrrvx.html

function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2bkxasuyx.html

[U46] PHP：可空类型
来源：http://dali.mhx1999.top/Article/details/gt2calggwpm.html

?string $name = null
来源：http://dali.yj20258.top/Article/details/gt2ixwivaag.html

[U47] PHP：联合类型
来源：http://dali.wangshuangyany.cn/Article/details/gt2ilvnnxty.html

int|string $id
来源：http://dali.dashuyun.cn/Article/details/gt2aieugbgk.html

[U48] PHP：纯枚举
来源：http://dali.zycfv.cn/Article/details/gt2cmkjlafs.html

enum Status: string { case Active = "active"; case Off = "off"; }
来源：http://dali.tian-w.cn/Article/details/gt2uicslzuu.html

[U49] PHP：只读属性
来源：http://dali.zhongyouzk.top/Article/details/gt2zyrzpevu.html

public readonly string $name
来源：http://dali.yj202588.top/Article/details/gt2iltmiyzl.html

[U50] PHP：构造器属性提升
来源：http://dali.cqqwz.cn/Article/details/gt2ozsnqrpd.html

public function __construct(private int $id) {}
来源：http://dali.zdqjudy.top/Article/details/gt2zfinoasi.html

[U51] PHP：数组解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtwnzzom.html

[$a, $b] = $arr;
来源：http://dali.sufxvd.cn/Article/details/gt2swzusoyq.html

[U52] PHP：箭头函数
来源：http://dali.dianchejie.cn/Article/details/gt2denpmisi.html

$double = fn($x) => $x * 2;
来源：http://dali.yuxming.cn/Article/details/gt2yufvrfis.html

[U53] PHP：空合并运算符
来源：http://dali.zhijiandao.cn/Article/details/gt2quzwtgmx.html

$v = $a ?? $b ?? "default";
来源：http://dali.ehwqpu.com/Article/details/gt2xsnzbfxz.html

[U54] PHP：空安全调用
来源：http://dali.ydzc1.top/Article/details/gt2pizmforq.html

$obj?->method()
来源：http://dali.tianlin.xyz/Article/details/gt2lkcsbnzk.html

[U55] PHP：match 表达式
来源：http://dali.tian-w.cn/Article/details/gt2ytbscbqz.html

$s = match($x) { 1 => "一", default => "其他" };
来源：http://dali.zycfv.cn/Article/details/gt2tjwoslva.html

[U56] PHP：命名参数
来源：http://dali.tanke756.top/Article/details/gt2rtuhdqmh.html

f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gt2zkpppkfy.html

[U57] PHP：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gt2ilgdijkh.html

"值: {$a}"
来源：http://dali.shuidangran.top/Article/details/gt2idqcgmhy.html

[U58] PHP：数组三件套
来源：http://dali.zhixingplan.top/Article/details/gt2mczofhqt.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.fengsongda.top/Article/details/gt2iyqezlyf.html

[U59] PHP：自定义排序
来源：http://dali.yonumen.top/Article/details/gt2zrowercz.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.havefunace.top/Article/details/gt2gdtqlloi.html

[U60] PHP：JSON 编解码
来源：http://dali.ehwqpu.com/Article/details/gt2rsorybmz.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kcduwucp.html

[U61] PHP：正则
来源：http://dali.cashguo.top/Article/details/gt2bztaeanx.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gt2eyqvnpqs.html

[U62] PHP：日期对象
来源：http://dali.hywenlv.cn/Article/details/gt2imlgvebw.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.chenlongwang.top/Article/details/gt2ezluneow.html

[U63] PHP：文件读写
来源：http://dali.nanxinkj.top/Article/details/gt2uqrmirqf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.sxryk.cn/Article/details/gt2yqolpixb.html

[U64] PHP：目录遍历
来源：http://dali.jianghu66.top/Article/details/gt2shxtarla.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.gzhubu.top/Article/details/gt2psydakig.html

[U65] PHP：会话
来源：http://dali.hnxiangtu.top/Article/details/gt2gbbodwwb.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.yj202588.top/Article/details/gt2zegggsxx.html

[U66] PHP：设置 Cookie
来源：http://dali.vqdsnc.cn/Article/details/gt2xgqucvdc.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.daria6918.cn/Article/details/gt2khhnrwqg.html

[U67] PHP：处理文件上传
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2akdjsgyi.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.gotoacloud.top/Article/details/gt2dkdkgycf.html

[U68] PHP：PDO 连接
来源：http://dali.kuanghao11.cn/Article/details/gt2plvrahhe.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.jiagoushi.top/Article/details/gt2wiplkcbx.html

[U69] PHP：PDO 预处理
来源：http://dali.wangshuangyany.cn/Article/details/gt2qvkgekzq.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.tianlin.xyz/Article/details/gt2ojkgeuui.html

[U70] PHP：PDO 事务
来源：http://dali.birdmap.top/Article/details/gt2sxavbnuw.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.smart0.xyz/Article/details/gt2pbbsknun.html

[U71] PHP：抛出异常
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ynjqidhj.html

throw new RuntimeException("失败", 500);
来源：http://dali.quarkkingdee.top/Article/details/gt2fcsmokik.html

[U72] PHP：写错误日志
来源：http://dali.zhixingplan.top/Article/details/gt2wllhkkxk.html

error_log("失败: " . $e->getMessage());
来源：http://dali.jinqigufen.top/Article/details/gt2pbcngcue.html

[U73] PHP：读取 ini 配置
来源：http://dali.jianghu66.top/Article/details/gt2gwoghnpo.html

parse_ini_file("config.ini", true)
来源：http://dali.tian-w.cn/Article/details/gt2vqpdfnqw.html

[U74] PHP：读取环境变量
来源：http://dali.cucudq.cn/Article/details/gt2zdqelzeb.html

getenv("APP_ENV") ?: "production"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udsnxglw.html

[U75] PHP：依赖注入
来源：http://dali.zhoulong.xyz/Article/details/gt2tjdqlkta.html

composer require psr/container
来源：http://dali.sxryk.cn/Article/details/gt2xpwknpla.html

[U76] PHP：简单路由
来源：http://dali.ehwqpu.com/Article/details/gt2uwoszwla.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iadrnofr.html

[U77] PHP：模板渲染
来源：http://dali.snrcjt.cn/Article/details/gt2odqodrsk.html

composer require twig/twig
来源：http://dali.pengpengdd.cyou/Article/details/gt2npzbltwe.html

[U78] PHP：单元测试
来源：http://dali.xinyue.icu/Article/details/gt2xzxveuky.html

composer require --dev phpunit/phpunit
来源：http://dali.sysykeji.top/Article/details/gt2ksrflpjf.html

[U79] PHP：静态分析
来源：http://dali.yvedp.cn/Article/details/gt2nbzynrnb.html

composer require --dev phpstan/phpstan
来源：http://dali.guannengcc.top/Article/details/gt2uwlxflcm.html

[U80] PHP：代码规范修复
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxjgbgqh.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.bjfxy.top/Article/details/gt2vfhpkmbu.html

[U81] JS：初始化项目
来源：http://dali.cdnleiting.top/Article/details/gt2mwikchod.html

npm init -y;  npm i express
来源：http://dali.shzxlz.cn/Article/details/gt2stgnburs.html

[U82] JS：package.json 脚本
来源：http://dali.xinyue.icu/Article/details/gt2pldfjnlm.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.gzhubu.top/Article/details/gt2mlnkcobw.html

[U83] JS：ES Module 导入导出
来源：http://dali.dashuyun.cn/Article/details/gt2deqkljwm.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2vpbpeksm.html

[U84] JS：CommonJS 写法
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ofqaefxg.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.yvedp.cn/Article/details/gt2ppouueeo.html

[U85] JS：可选链
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2umjhhokl.html

a?.b?.c
来源：http://dali.mhx1999.top/Article/details/gt2pesdurwl.html

[U86] JS：空值合并
来源：http://dali.cdnleiting.top/Article/details/gt2hobfzxjo.html

a ?? b
来源：http://dali.cdnleiting.top/Article/details/gt2wytzsayg.html

[U87] JS：解构默认值
来源：http://dali.zhoulong.xyz/Article/details/gt2fyqfdixf.html

const { a = 1, b = 2 } = obj;
来源：http://dali.ehwqpu.com/Article/details/gt2zvqoeslr.html

[U88] JS：对象展开合并
来源：http://dali.vqdsnc.cn/Article/details/gt2gfyeqjnv.html

{ ...a, ...b }
来源：http://dali.cheryme.top/Article/details/gt2yylakeks.html

[U89] JS：数组去重
来源：http://dali.guannengcc.top/Article/details/gt2ogxosptj.html

[...new Set(arr)]
来源：http://dali.andypj.xyz/Article/details/gt2zoqkioji.html

[U90] JS：数字数组排序
来源：http://dali.jinqigfzy.top/Article/details/gt2eirtnuym.html

[...arr].sort((a, b) => a - b)
来源：http://dali.sxryk.cn/Article/details/gt2hahegope.html

[U91] JS：对象键值遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2snumahpr.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xziqi.cn/Article/details/gt2frbsqmnw.html

[U92] JS：深拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lnguvnza.html

structuredClone(obj)
来源：http://dali.yj20258888.top/Article/details/gt2ynmwpjaj.html

[U93] JS：模板字符串
来源：http://dali.dianchejie.cn/Article/details/gt2shletxdw.html

`共 ${n} 条`
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fayxmukw.html

[U94] JS：箭头函数
来源：http://dali.jlsjyb.cn/Article/details/gt2dgwuxxkb.html

const double = x => x * 2;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qmpfwqki.html

[U95] JS：Promise 包装
来源：http://dali.feifeiyinyue.top/Article/details/gt2vbvajzpl.html

new Promise((resolve, reject) => {})
来源：http://dali.xuanzx.com/Article/details/gt2vgxxywez.html

[U96] JS：async/await 与异常
来源：http://dali.shzxlz.cn/Article/details/gt2ihlwnrbu.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.snrcjt.cn/Article/details/gt2uwwzqiic.html

[U97] JS：并发请求
来源：http://dali.nanxuanxn.top/Article/details/gt2iqddrsxd.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.smart0.xyz/Article/details/gt2vsqybtng.html

[U98] JS：fetch 带 JSON
来源：http://dali.tian-w.cn/Article/details/gt2dykrxhsd.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jqgfzy.top/Article/details/gt2gmfmputr.html

[U99] JS：事件监听
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uvekwsot.html

el.addEventListener("click", e => {})
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bumnwtsx.html

[U100] JS：DOM 查询
来源：http://dali.nanxinkj.top/Article/details/gt2ztxwswqn.html

document.querySelector(".item")
来源：http://dali.ppjwa.cn/Article/details/gt2gkoqozdk.html

[U101] JS：classList 操作
来源：http://dali.hywenlv.cn/Article/details/gt2jyivdnml.html

el.classList.toggle("active")
来源：http://dali.jianghu66.top/Article/details/gt2ixdqtqto.html

[U102] JS：本地存储
来源：http://dali.hywenlv.cn/Article/details/gt2saxdjaoo.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgfzy.top/Article/details/gt2mkuhtmbc.html

[U103] JS：定时器
来源：http://dali.yj20258888.top/Article/details/gt2ifcdtrfs.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxcbkcg.html

[U104] JS：防抖
来源：http://dali.nwbrower.top/Article/details/gt2qmiagswh.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.yj202588.top/Article/details/gt2ulijirrg.html

[U105] JS：节流
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtqqvaan.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.pengpengdd.cyou/Article/details/gt2fjuaoauw.html

[U106] JS：日期格式化
来源：http://dali.guowangkeji.top/Article/details/gt2mdebxpej.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.yj20258888.top/Article/details/gt2upuizodm.html

[U107] JS：数字千分位
来源：http://dali.xuanzx.com/Article/details/gt2oxveario.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.smart0.xyz/Article/details/gt2imbgbthj.html

[U108] JS：随机整数
来源：http://dali.shzxlz.cn/Article/details/gt2zdjjmgaj.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ocpxsrfz.html

[U109] JS：数组分组
来源：http://dali.shanyushiyangtech.top/Article/details/gt2soziauoy.html

Object.groupBy(arr, x => x.type)
来源：http://dali.quarkkingdee.top/Article/details/gt2ijtquuzz.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gt2laanzmrp.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2brudnfub.html

[U111] JS：对象转 Map
来源：http://dali.hysaishi.cn/Article/details/gt2iqwdsigf.html

new Map(Object.entries(obj))
来源：http://dali.9152youxi.cn/Article/details/gt2fxpjifdr.html

[U112] JS：字符串补位
来源：http://dali.xylfe.cn/Article/details/gt2sxvrynfj.html

"7".padStart(3, "0")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bsnzfeih.html

[U113] JS：正则替换全部
来源：http://dali.hnqzz.top/Article/details/gt2yvmoudnk.html

s.replaceAll("a", "b")
来源：http://dali.jqgfzy.top/Article/details/gt2dhkxmvlh.html

[U114] JS：JSON 深比较
来源：http://dali.xuanzx.com/Article/details/gt2bsggaohl.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.xinyue.icu/Article/details/gt2dfnhaypr.html

[U115] JS：生成 UUID
来源：http://dali.yonumen.top/Article/details/gt2zhwhnzyn.html

crypto.randomUUID()
来源：http://dali.svipenyu.cn/Article/details/gt2ackgkybe.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.cdnleiting.top/Article/details/gt2icfvhusk.html

/** @param {string} name */ function f(name) {}
来源：http://dali.tanke756.top/Article/details/gt2juemawgw.html

[U117] JS：单元测试
来源：http://dali.hnqzz.top/Article/details/gt2bgnqoqgw.html

npm i -D vitest;  npx vitest
来源：http://dali.yueranfly.top/Article/details/gt2oelhmreh.html

[U118] JS：开发服务器
来源：http://dali.cashguo.top/Article/details/gt2xzwgolky.html

npm i -D vite;  npx vite
来源：http://dali.hammf.cn/Article/details/gt2lkyqxzha.html

[U119] JS：生产构建
来源：http://dali.jqgfzy.top/Article/details/gt2wrmxynpy.html

npx vite build
来源：http://dali.mhx1999.top/Article/details/gt2jqhhjedl.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.tianlin.xyz/Article/details/gt2betzijto.html

import.meta.env.VITE_API_URL
来源：http://dali.yuanzhike.top/Article/details/gt2xcmdcrbu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2irywmrun.html

统计汇总
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzwtwhxm.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2breupwbq.html

按语言统计（条）：
来源：http://dali.smart0.xyz/Article/details/gt2xvekrrww.html

Python ......... 252
来源：http://dali.ppjwa.cn/Article/details/gt2kudnztom.html

PHP ............ 252
来源：http://dali.yueranfly.top/Article/details/gt2bxlyvhen.html

JavaScript ..... 252
来源：http://dali.9152youxi.cn/Article/details/gt2wgbriugx.html

TypeScript ..... 212
来源：http://dali.jlsjyb.cn/Article/details/gt2rkxiufpv.html

Java ........... 212
来源：http://dali.hnxiangtu.top/Article/details/gt2fwabakeq.html

Go ............. 212
来源：http://dali.pycfn.com/Article/details/gt2znbmpguf.html

Ruby ........... 212
来源：http://dali.zhixingplan.top/Article/details/gt2qkkgxibx.html

C# ............. 212
来源：http://dali.gogol.net.cn/Article/details/gt2bgxzuiln.html

C .............. 30
来源：http://dali.yanxiufei.cn/Article/details/gt2izlzxeah.html

C++ ............ 30
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cuqhapaj.html

SQL ............ 90
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2udqyskpj.html

Bash ........... 80
来源：http://dali.cashguo.top/Article/details/gt2zeiahnxq.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2bxjxxqvg.html

Swift .......... 15
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ropnpxfz.html

Lua ............ 10
来源：http://dali.xinyue.icu/Article/details/gt2dbakhzsm.html

Perl ........... 10
来源：http://dali.gogol.net.cn/Article/details/gt2nbdcmbuu.html

Scala .......... 10
来源：http://dali.cashguo.top/Article/details/gt2hjmpuciw.html

------------------------------------
来源：http://dali.aizwys.cn/Article/details/gt2iekbsmut.html

合计 ........... 2106 条
来源：http://dali.jqgfzy.top/Article/details/gt2asjxibwj.html

按章节统计：
来源：http://dali.wangdashe.top/Article/details/gt2yqmvkwtx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.jlsjyb.cn/Article/details/gt2sdsqygnr.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.meibo888.top/Article/details/gt2wytmebds.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.hongshengwenyu.top/Article/details/gt2bomzbkeg.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.hywenlv.cn/Article/details/gt2smajiqhr.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.ybcxt.top/Article/details/gt2zzuoqzzu.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.hongshengwenyu.top/Article/details/gt2tnluepwf.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.vqdsnc.cn/Article/details/gt2cwlphlni.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.9152youxi.cn/Article/details/gt2jpeicrog.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yueranfly.top/Article/details/gt2mdnifems.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.ivvv.top/Article/details/gt2zuttuctb.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.yj202588.top/Article/details/gt2wvqkhbzy.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ovxisfdv.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.yvedp.cn/Article/details/gt2jzwbnuaq.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.xylfe.cn/Article/details/gt2qbavcrxf.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.gotoacloud.top/Article/details/gt2zckzumag.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cucudq.cn/Article/details/gt2aiogtwbg.html

Q SQL 专题                              90
来源：http://dali.gotoacloud.top/Article/details/gt2upxjjmrx.html

R Bash 专题                             80
来源：http://dali.nanxinkj.top/Article/details/gt2onmhztjo.html

S C / C++ 专题                          60
来源：http://dali.pengpengdd.cyou/Article/details/gt2qtzgenax.html

T 其他语言补充                          60
来源：http://dali.havefunace.top/Article/details/gt2cicingvd.html

U 高频实用片段                         120
来源：http://dali.xinyue.icu/Article/details/gt2cuygpctc.html

------------------------------------
来源：http://dali.tian-w.cn/Article/details/gt2fsrmhgpd.html

合计                                  2106 条
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fwzxxgsj.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2ogrneira.html

使用提醒
来源：http://dali.jiagoushi.top/Article/details/gt2ewlblpsu.html

--------------------------------------------------------------------------------
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeopflsu.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ckinlyoo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.snrcjt.cn/Article/details/gt2mayyybta.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.tianlin.xyz/Article/details/gt2fcdecopl.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.bjfxy.top/Article/details/gt2rqmjpylb.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.pengpengdd.cyou/Article/details/gt2oblzdrqo.html

—— 文件结束 ——
来源：http://dali.tanke756.top/Article/details/gt2xqykmmdt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2pwifzvbf.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guowangkeji.top/Article/details/gt2gwbknizk.html

Common Programming Examples Cheat Book
来源：http://dali.shangyingyoupin.top/Article/details/gt2qneqbnrk.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nqjbmfss.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2sqadtcms.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rmcjjbha.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.cashguo.top/Article/details/gt2lztklrcs.html

SQL · Bash · C · C++
来源：http://dali.316326.xyz/Article/details/gt2zxfucely.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.yanxiufei.cn/Article/details/gt2cwmocmrf.html

【使用说明】
来源：http://dali.zycfv.cn/Article/details/gt2qaxzusdp.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.9152youxi.cn/Article/details/gt2dwsjgeoj.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vmvxlxqg.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.bjfxy.top/Article/details/gt2benqkbzj.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.hammf.cn/Article/details/gt2wrmmyoaw.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xpccanqz.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.cheryme.top/Article/details/gt2qtwxyfek.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.aizwys.cn/Article/details/gt2aiwabtwn.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.yongpay.top/Article/details/gt2vlyrfkoa.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pycfn.com/Article/details/gt2gowxcsyt.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijfgpnsi.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.0kj1m.cn/Article/details/gt2auchhhdp.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.hammf.cn/Article/details/gt2trrzclse.html

【文件统计】
来源：http://dali.fengsongda.top/Article/details/gt2xazwfloq.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.zhixingplan.top/Article/details/gt2zhvoznne.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2qarmosvk.html

目  录
来源：http://dali.ehwqpu.com/Article/details/gt2pyqrpufj.html

--------------------------------------------------------------------------------
来源：http://dali.chenzaomai.com/Article/details/gt2genyaeme.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2fvewsfpf.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixemyzuq.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.chenlongwang.top/Article/details/gt2rfixcvmu.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.hongshengwenyu.top/Article/details/gt2kiczdbmq.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.haohaochexian.top/Article/details/gt2guwsovzy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2qqllpmlt.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gt2byrrzgel.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.yj20258.top/Article/details/gt2rnmylaqa.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.pengpengdd.cyou/Article/details/gt2cvavshho.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zycfv.cn/Article/details/gt2hzlclfmy.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.snrcjt.cn/Article/details/gt2vnzehcui.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.xylfe.cn/Article/details/gt2kegmutna.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.zhoulong.xyz/Article/details/gt2xicjplnn.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.pycfn.com/Article/details/gt2qollsxjv.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.hnqzz.top/Article/details/gt2btlesbno.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.316326.xyz/Article/details/gt2cpdzcrjo.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.zdqjudy.top/Article/details/gt2dqvetdoh.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.yj20258888.top/Article/details/gt2tmqxwpyp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.feifeiyinyue.top/Article/details/gt2hrytygcm.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yangfankeji.com/Article/details/gt2akhwuass.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gt2hbdohqhy.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2tclmuukf.html

A. 基础语法与类型
来源：http://dali.jinqigufen.top/Article/details/gt2rocklwmn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gt2guzsndjl.html

[A01] Hello World
来源：http://dali.fengsongda.top/Article/details/gt2khlxcdoa.html

Py:   print("Hello, World!")
来源：http://dali.andypj.xyz/Article/details/gt2imejxuvq.html

PHP:  echo "Hello, World!";
来源：http://dali.xziqi.cn/Article/details/gt2zdaefhjs.html

JS:   console.log("Hello, World!");
来源：http://dali.ybcxt.top/Article/details/gt2ekisfdrf.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.jiagoushi.top/Article/details/gt2fgyzfwym.html

Java: System.out.println("Hello, World!");
来源：http://dali.yangfankeji.com/Article/details/gt2ygtpibam.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cdnleiting.top/Article/details/gt2rjpfwlba.html

Ruby: puts "Hello, World!"
来源：http://dali.ybcxt.top/Article/details/gt2eoldewcm.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gtbkfwif.html

[A02] 变量声明与赋值
来源：http://dali.zhengqikj.top/Article/details/gt2gdgeowzp.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlwuhmry.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.havefunace.top/Article/details/gt2hfvyeakd.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.gaohongyu789.top/Article/details/gt2njzyzwdy.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.vqdsnc.cn/Article/details/gt2omcaioyq.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fyqhogxk.html

Go:   name := "Alex"; age := 20
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgktkfis.html

Ruby: name = "Alex"; age = 20
来源：http://dali.chenlongwang.top/Article/details/gt2yqzxyqvp.html


<!-- 参考信息 -->