代发 wailian999

[U57] PHP：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2cbbdqjrb.html

"值: {$a}"
来源：http://dali.aibaodan.cn/Article/details/gt2hcutrmnu.html

[U58] PHP：数组三件套
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvucorpz.html

array_map($f, $a);  array_filter($a, $f);  array_reduce($a, $f, 0);
来源：http://dali.jqgufenzy.top/Article/details/gt2mhfpchlj.html

[U59] PHP：自定义排序
来源：http://dali.hywenlv.cn/Article/details/gt2ihyenqdl.html

usort($arr, fn($a, $b) => $a["age"] <=> $b["age"]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ecixbcng.html

[U60] PHP：JSON 编解码
来源：http://dali.shangyingyoupin.top/Article/details/gt2kpiylrms.html

json_encode($d, JSON_UNESCAPED_UNICODE);  json_decode($s, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2inmobkby.html

[U61] PHP：正则
来源：http://dali.zhengqikj.top/Article/details/gt2qpucwhcj.html

preg_match('/(\d+)/', $s, $m);  preg_replace('/\d+/', '#', $s);
来源：http://dali.9152youxi.cn/Article/details/gt2foqdvxfq.html

[U62] PHP：日期对象
来源：http://dali.fzhhl.top/Article/details/gt2vgmfimcs.html

(new DateTimeImmutable())->format("Y-m-d");
来源：http://dali.jinqigufen.top/Article/details/gt2uzheqzqs.html

[U63] PHP：文件读写
来源：http://dali.dianchejie.cn/Article/details/gt2rmynglgf.html

file_get_contents($f);  file_put_contents($f, $data);
来源：http://dali.tanke756.top/Article/details/gt2bouenviz.html

[U64] PHP：目录遍历
来源：http://dali.zhongyouzk.top/Article/details/gt2krnclynv.html

glob("dir/*.php");  scandir("dir");
来源：http://dali.sufxvd.cn/Article/details/gt2apjuksqk.html

[U65] PHP：会话
来源：http://dali.sweek.top/Article/details/gt2ayqdhgcy.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2yecyriyo.html

[U66] PHP：设置 Cookie
来源：http://dali.aibaodan.cn/Article/details/gt2tvfspoyl.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.dianchejie.cn/Article/details/gt2hbzznymg.html

[U67] PHP：处理文件上传
来源：http://dali.smart0.xyz/Article/details/gt2eawygmkb.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.sysykeji.top/Article/details/gt2udlgcknj.html

[U68] PHP：PDO 连接
来源：http://dali.zycfv.cn/Article/details/gt2ypvxpwhu.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.gotoacloud.top/Article/details/gt2tqiszhdp.html

[U69] PHP：PDO 预处理
来源：http://dali.dashuyun.cn/Article/details/gt2mydmspmu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.yueranfly.top/Article/details/gt2dutdvcqq.html

[U70] PHP：PDO 事务
来源：http://dali.jinqigufen.top/Article/details/gt2wdsmvwvl.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.fengsongda.top/Article/details/gt2tocpeske.html

[U71] PHP：抛出异常
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tkrpjhpa.html

throw new RuntimeException("失败", 500);
来源：http://dali.yvedp.cn/Article/details/gt2cyvdjndu.html

[U72] PHP：写错误日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efkwofbm.html

error_log("失败: " . $e->getMessage());
来源：http://dali.316326.xyz/Article/details/gt2hccnbokw.html

[U73] PHP：读取 ini 配置
来源：http://dali.yj20258.top/Article/details/gt2gheqlvpo.html

parse_ini_file("config.ini", true)
来源：http://dali.yj202588.top/Article/details/gt2behisjku.html

[U74] PHP：读取环境变量
来源：http://dali.aizwys.cn/Article/details/gt2ptnrqykn.html

getenv("APP_ENV") ?: "production"
来源：http://dali.vqdsnc.cn/Article/details/gt2vazzuapz.html

[U75] PHP：依赖注入
来源：http://dali.aibaodan.cn/Article/details/gt2zhoondio.html

composer require psr/container
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mbrmaikq.html

[U76] PHP：简单路由
来源：http://dali.vqdsnc.cn/Article/details/gt2evahxiwh.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.hnxiangtu.top/Article/details/gt2ojjdvlzf.html

[U77] PHP：模板渲染
来源：http://dali.cdnleiting.top/Article/details/gt2nngbvvoh.html

composer require twig/twig
来源：http://dali.cheryme.top/Article/details/gt2fyfobfme.html

[U78] PHP：单元测试
来源：http://dali.jinqigfzy.top/Article/details/gt2qqgpdnnf.html

composer require --dev phpunit/phpunit
来源：http://dali.meibo888.top/Article/details/gt2hiclkdnw.html

[U79] PHP：静态分析
来源：http://dali.zhongyouzk.top/Article/details/gt2wzsemciy.html

composer require --dev phpstan/phpstan
来源：http://dali.meibo888.top/Article/details/gt2kqpxnhfr.html

[U80] PHP：代码规范修复
来源：http://dali.yongpay.top/Article/details/gt2mlfyvxjl.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.bjfxy.top/Article/details/gt2mbayfwii.html

[U81] JS：初始化项目
来源：http://dali.dashuyun.cn/Article/details/gt2kwqqtzze.html

npm init -y;  npm i express
来源：http://dali.yanxiufei.cn/Article/details/gt2gttfakvb.html

[U82] JS：package.json 脚本
来源：http://dali.pengpengdd.cyou/Article/details/gt2dktvejgt.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.hysaishi.cn/Article/details/gt2qmmownlq.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gt2vzagiizj.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gt2dfksbwtn.html

[U84] JS：CommonJS 写法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gaxdjimw.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.zycfv.cn/Article/details/gt2jpsxjwee.html

[U85] JS：可选链
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ggjzonzp.html

a?.b?.c
来源：http://dali.zycfv.cn/Article/details/gt2fnynumuz.html

[U86] JS：空值合并
来源：http://dali.jqgfzy.top/Article/details/gt2blhkgxxf.html

a ?? b
来源：http://dali.yonumen.top/Article/details/gt2kfmcygtn.html

[U87] JS：解构默认值
来源：http://dali.tianlin.xyz/Article/details/gt2kxdroxkt.html

const { a = 1, b = 2 } = obj;
来源：http://dali.hongshengwenyu.top/Article/details/gt2iibdftub.html

[U88] JS：对象展开合并
来源：http://dali.hammf.cn/Article/details/gt2tlbkpwgi.html

{ ...a, ...b }
来源：http://dali.tian-w.cn/Article/details/gt2tenekdmc.html

[U89] JS：数组去重
来源：http://dali.fengsongda.top/Article/details/gt2xynyogvf.html

[...new Set(arr)]
来源：http://dali.dianchejie.cn/Article/details/gt2idgynsux.html

[U90] JS：数字数组排序
来源：http://dali.9152youxi.cn/Article/details/gt2yiwnjksb.html

[...arr].sort((a, b) => a - b)
来源：http://dali.chenzaomai.com/Article/details/gt2hkzjszra.html

[U91] JS：对象键值遍历
来源：http://dali.guowangkeji.top/Article/details/gt2mimciksv.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.xinyue.icu/Article/details/gt2xededhok.html

[U92] JS：深拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2yjplsofa.html

structuredClone(obj)
来源：http://dali.ybcxt.top/Article/details/gt2kgwdbszb.html

[U93] JS：模板字符串
来源：http://dali.nanxinkj.top/Article/details/gt2ghfpvddj.html

`共 ${n} 条`
来源：http://dali.snrcjt.cn/Article/details/gt2wepujtan.html

[U94] JS：箭头函数
来源：http://dali.yuxming.cn/Article/details/gt2meecsnfb.html

const double = x => x * 2;
来源：http://dali.xuanzx.com/Article/details/gt2lspfexpc.html

[U95] JS：Promise 包装
来源：http://dali.chenlongwang.top/Article/details/gt2tcmobhhy.html

new Promise((resolve, reject) => {})
来源：http://dali.nanxinkj.top/Article/details/gt2cjynnfey.html

[U96] JS：async/await 与异常
来源：http://dali.9152youxi.cn/Article/details/gt2oeckqjwa.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.0kj1m.cn/Article/details/gt2flxuqupy.html

[U97] JS：并发请求
来源：http://dali.chenzaomai.com/Article/details/gt2lupwhfem.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.sweek.top/Article/details/gt2mcujreqe.html

[U98] JS：fetch 带 JSON
来源：http://dali.pengpengdd.cyou/Article/details/gt2rcqgzyou.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.haohaochexian.top/Article/details/gt2bjrgmosz.html

[U99] JS：事件监听
来源：http://dali.yanxiufei.cn/Article/details/gt2iziilivp.html

el.addEventListener("click", e => {})
来源：http://dali.gogol.net.cn/Article/details/gt2efhlmwoc.html

[U100] JS：DOM 查询
来源：http://dali.cdnleiting.top/Article/details/gt2wrwidmzr.html

document.querySelector(".item")
来源：http://dali.gaohongyu789.top/Article/details/gt2jdbocoyf.html

[U101] JS：classList 操作
来源：http://dali.yanxiufei.cn/Article/details/gt2zgpprsur.html

el.classList.toggle("active")
来源：http://dali.hnqzz.top/Article/details/gt2jpwioffi.html

[U102] JS：本地存储
来源：http://dali.zhongyouzk.top/Article/details/gt2zigzmxha.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jqgufenzy.top/Article/details/gt2vkohvxhq.html

[U103] JS：定时器
来源：http://dali.hysaishi.cn/Article/details/gt2fjvechjt.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.tanke756.top/Article/details/gt2iokdvfav.html

[U104] JS：防抖
来源：http://dali.sxryk.cn/Article/details/gt2hghpcseg.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.gogol.net.cn/Article/details/gt2hxvdixyz.html

[U105] JS：节流
来源：http://dali.cheryme.top/Article/details/gt2uzmcaazh.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wtolukny.html

[U106] JS：日期格式化
来源：http://dali.zhixingplan.top/Article/details/gt2qkrehfrj.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.hfpthk.cn/Article/details/gt2awrwfrfn.html

[U107] JS：数字千分位
来源：http://dali.bjfxy.top/Article/details/gt2nwvhndlo.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.cashguo.top/Article/details/gt2iepcftqy.html

[U108] JS：随机整数
来源：http://dali.zhiwuduotai.top/Article/details/gt2zuiioqmn.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.tian-w.cn/Article/details/gt2lxipmayl.html

[U109] JS：数组分组
来源：http://dali.ehwqpu.com/Article/details/gt2omvsauyj.html

Object.groupBy(arr, x => x.type)
来源：http://dali.tanke756.top/Article/details/gt2piymtbrc.html

[U110] JS：数组分块
来源：http://dali.dashuyun.cn/Article/details/gt2sagoqwzd.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.sysykeji.top/Article/details/gt2koyvrrvl.html

[U111] JS：对象转 Map
来源：http://dali.cdnleiting.top/Article/details/gt2pwdzfbgz.html

new Map(Object.entries(obj))
来源：http://dali.bjfxy.top/Article/details/gt2tvwoqvjg.html

[U112] JS：字符串补位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jaqekgpf.html

"7".padStart(3, "0")
来源：http://dali.shzxlz.cn/Article/details/gt2uowdbugw.html

[U113] JS：正则替换全部
来源：http://dali.jqgfzy.top/Article/details/gt2cxvprhgw.html

s.replaceAll("a", "b")
来源：http://dali.kuanghao11.cn/Article/details/gt2xyvtvjjk.html

[U114] JS：JSON 深比较
来源：http://dali.jinqigfzy.top/Article/details/gt2qfbvvpuy.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.0kj1m.cn/Article/details/gt2clhxtfxi.html

[U115] JS：生成 UUID
来源：http://dali.ydzc1.top/Article/details/gt2zlkdnjeu.html

crypto.randomUUID()
来源：http://dali.daxiang520.top/Article/details/gt2whicmcut.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.daria6918.cn/Article/details/gt2jdectcfv.html

/** @param {string} name */ function f(name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2sssqmoyg.html

[U117] JS：单元测试
来源：http://dali.gaohongyu789.top/Article/details/gt2zmscprma.html

npm i -D vitest;  npx vitest
来源：http://dali.cheryme.top/Article/details/gt2vcnjowut.html

[U118] JS：开发服务器
来源：http://dali.havefunace.top/Article/details/gt2nyrdcvdj.html

npm i -D vite;  npx vite
来源：http://dali.daria6918.cn/Article/details/gt2piihmvnz.html

[U119] JS：生产构建
来源：http://dali.chenlongwang.top/Article/details/gt2bykghqgt.html

npx vite build
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2homkaqyz.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iufwnwgl.html

import.meta.env.VITE_API_URL
来源：http://dali.sweek.top/Article/details/gt2jygkeise.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2blwytzcq.html

统计汇总
来源：http://dali.feifeiyinyue.top/Article/details/gt2krsyvrjt.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fpiisjoo.html

按语言统计（条）：
来源：http://dali.svipenyu.cn/Article/details/gt2bgsbedlj.html

Python ......... 252
来源：http://dali.yuxming.cn/Article/details/gt2febmntvf.html

PHP ............ 252
来源：http://dali.andypj.xyz/Article/details/gt2umigwvds.html

JavaScript ..... 252
来源：http://dali.chenzaomai.com/Article/details/gt2adyfgtfz.html

TypeScript ..... 212
来源：http://dali.jqgfzy.top/Article/details/gt2aekqngvl.html

Java ........... 212
来源：http://dali.snrcjt.cn/Article/details/gt2ambmqeqr.html

Go ............. 212
来源：http://dali.quarkkingdee.top/Article/details/gt2fuiilqtt.html

Ruby ........... 212
来源：http://dali.tianlin.xyz/Article/details/gt2kxehsbtc.html

C# ............. 212
来源：http://dali.haohaochexian.top/Article/details/gt2ivkiroqt.html

C .............. 30
来源：http://dali.jinqigfzy.top/Article/details/gt2fuclufcl.html

C++ ............ 30
来源：http://dali.yvedp.cn/Article/details/gt2wnujplof.html

SQL ............ 90
来源：http://dali.jinqigfzy.top/Article/details/gt2jqltlcws.html

Bash ........... 80
来源：http://dali.316326.xyz/Article/details/gt2zfgvchor.html

Kotlin ......... 15
来源：http://dali.hfpthk.cn/Article/details/gt2tljqemvb.html

Swift .......... 15
来源：http://dali.yonumen.top/Article/details/gt2dbgoezce.html

Lua ............ 10
来源：http://dali.aizwys.cn/Article/details/gt2iygutuku.html

Perl ........... 10
来源：http://dali.sysykeji.top/Article/details/gt2hbenumyn.html

Scala .......... 10
来源：http://dali.xuetiantiany.cn/Article/details/gt2skpimbsm.html

------------------------------------
来源：http://dali.aibaodan.cn/Article/details/gt2owzsbbyg.html

合计 ........... 2106 条
来源：http://dali.yj20258.top/Article/details/gt2muycbtxc.html

按章节统计：
来源：http://dali.nanxinkj.top/Article/details/gt2nptqwyud.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.yonumen.top/Article/details/gt2lvrdqvdu.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.316326.xyz/Article/details/gt2xzeeztyk.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.fzhhl.top/Article/details/gt2xwufptby.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.tian-w.cn/Article/details/gt2crvohtbn.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.sufxvd.cn/Article/details/gt2advbardh.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.c1oappe.top/Article/details/gt2dlkxoxjm.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.xuanzx.com/Article/details/gt2rszuzxnl.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.pengpengdd.cyou/Article/details/gt2yquyeugh.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.yuanzhike.top/Article/details/gt2machkjdz.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.svipenyu.cn/Article/details/gt2axamhavj.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.ppjwa.cn/Article/details/gt2nmunggbf.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yuxming.cn/Article/details/gt2oyzltzge.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2galfotuu.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.316326.xyz/Article/details/gt2hcjhslra.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.hammf.cn/Article/details/gt2juhulhye.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.shanyushiyangtech.top/Article/details/gt2eocqdqae.html

Q SQL 专题                              90
来源：http://dali.cucudq.cn/Article/details/gt2khocyjex.html

R Bash 专题                             80
来源：http://dali.hongshengwenyu.top/Article/details/gt2hanvnvrj.html

S C / C++ 专题                          60
来源：http://dali.xinyue.icu/Article/details/gt2zoqyvunt.html

T 其他语言补充                          60
来源：http://dali.daria6918.cn/Article/details/gt2yinwujmt.html

U 高频实用片段                         120
来源：http://dali.chenlongwang.top/Article/details/gt2ugjgpamd.html

------------------------------------
来源：http://dali.hfpthk.cn/Article/details/gt2hterkuod.html

合计                                  2106 条
来源：http://dali.jqgufenzy.top/Article/details/gt2rfnkxchb.html

--------------------------------------------------------------------------------
来源：http://dali.hnqzz.top/Article/details/gt2gxhrnstl.html

使用提醒
来源：http://dali.ydzc1.top/Article/details/gt2dphamdfw.html

--------------------------------------------------------------------------------
来源：http://dali.dianchejie.cn/Article/details/gt2rurbeldb.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.yuxming.cn/Article/details/gt2yxopfwcn.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.jlsjyb.cn/Article/details/gt2clzkmdwj.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.jqgfzy.top/Article/details/gt2rnsrhved.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.xuanzx.com/Article/details/gt2hvvsdzvn.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.xuanzx.com/Article/details/gt2nfkincxz.html

—— 文件结束 ——
来源：http://dali.birdmap.top/Article/details/gt2oibujudp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2mpkwmguv.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2caybphco.html

Common Programming Examples Cheat Book
来源：http://dali.jyoumei.cn/Article/details/gt2xyggelyw.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2dsdbwhln.html

【收录内容】
来源：http://dali.hammf.cn/Article/details/gt2graglhhq.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.ppjwa.cn/Article/details/gt2farrqnrs.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.feifeiyinyue.top/Article/details/gt2pzqyywmy.html

SQL · Bash · C · C++
来源：http://dali.jlsjyb.cn/Article/details/gt2adkbywvg.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.gaohongyu789.top/Article/details/gt2ddyoijqw.html

【使用说明】
来源：http://dali.guannengcc.top/Article/details/gt2pvmqsluj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.hysaishi.cn/Article/details/gt2olmfmthx.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.meibo888.top/Article/details/gt2jsuoozlr.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.zycfv.cn/Article/details/gt2fbndwsqq.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.haohaochexian.top/Article/details/gt2pftcorax.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.cqqwz.cn/Article/details/gt2bcypysqb.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ygwgkgad.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.wangdashe.top/Article/details/gt2iguhxrab.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.tianlin.xyz/Article/details/gt2cehvswlw.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.aizwys.cn/Article/details/gt2etgjvblc.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.xylfe.cn/Article/details/gt2oiwacckx.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.meibo888.top/Article/details/gt2ukjfvwbf.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.bjfxy.top/Article/details/gt2yiyxhpgn.html

【文件统计】
来源：http://dali.ydzc1.top/Article/details/gt2nwjqsjwe.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.yuxming.cn/Article/details/gt2rbktiugq.html

--------------------------------------------------------------------------------
来源：http://dali.zdqjudy.top/Article/details/gt2zyqvshdi.html

目  录
来源：http://dali.ybcxt.top/Article/details/gt2prhhzvmf.html

--------------------------------------------------------------------------------
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pkthbmiv.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.cucudq.cn/Article/details/gt2dgubldvl.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.zhijiandao.cn/Article/details/gt2brfkcitg.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.sweek.top/Article/details/gt2evakmejj.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.gzhubu.top/Article/details/gt2qaklsrgh.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uwmnxumy.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.jinqigufen.top/Article/details/gt2mvhdthuz.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhiwuduotai.top/Article/details/gt2qmueiyey.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2ylrsdkap.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.sweek.top/Article/details/gt2jrkdinie.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.svipenyu.cn/Article/details/gt2vvaiqhsi.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gt2xkkpfpgp.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.jinqigufen.top/Article/details/gt2naehwdep.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.cqqwz.cn/Article/details/gt2jcrklmqe.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.zhixingplan.top/Article/details/gt2tyqbaedz.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.quarkkingdee.top/Article/details/gt2xkewzxkv.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.svipenyu.cn/Article/details/gt2svgkkgso.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.ehwqpu.com/Article/details/gt2ifwphrak.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.hysaishi.cn/Article/details/gt2mxppwecp.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.andypj.xyz/Article/details/gt2wpxajlof.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gt2lvwhkofh.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2odfaeloi.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2fatsazeh.html

A. 基础语法与类型
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xpqowkbh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2gusgibmu.html

[A01] Hello World
来源：http://dali.ivvv.top/Article/details/gt2tnghxfiz.html

Py:   print("Hello, World!")
来源：http://dali.hywenlv.cn/Article/details/gt2uduppfaf.html

PHP:  echo "Hello, World!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gzaxzluw.html

JS:   console.log("Hello, World!");
来源：http://dali.yuxming.cn/Article/details/gt2karnuryk.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.yvedp.cn/Article/details/gt2atssasms.html

Java: System.out.println("Hello, World!");
来源：http://dali.cheryme.top/Article/details/gt2pabogtad.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.cashguo.top/Article/details/gt2jqtxfqad.html

Ruby: puts "Hello, World!"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhcoybvj.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gt2dvetekuv.html

[A02] 变量声明与赋值
来源：http://dali.tian-w.cn/Article/details/gt2ytzfdeyd.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.yuanzhike.top/Article/details/gt2edlkwnhp.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.gogol.net.cn/Article/details/gt2bnbbwdof.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gt2qqppgqbp.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.yanxiufei.cn/Article/details/gt2nodyfhaf.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.sweek.top/Article/details/gt2dxgutatu.html

Go:   name := "Alex"; age := 20
来源：http://dali.tianlin.xyz/Article/details/gt2meidcdyt.html

Ruby: name = "Alex"; age = 20
来源：http://dali.snrcjt.cn/Article/details/gt2zdcavhjs.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jlsjyb.cn/Article/details/gt2shycpbjj.html

[A03] 常量定义
来源：http://dali.gzhubu.top/Article/details/gt2wpupjpyq.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rpewcmeb.html

PHP:  const PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xtwfyzom.html

JS:   const PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gt2bskzqhwb.html

TS:   const PI: number = 3.14159;
来源：http://dali.yuanzhike.top/Article/details/gt2wffwfqvo.html

Java: static final double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2wfckghtq.html

Go:   const PI = 3.14159
来源：http://dali.vqdsnc.cn/Article/details/gt2httmrklf.html

Ruby: PI = 3.14159
来源：http://dali.zdqjudy.top/Article/details/gt2ilnitcfl.html

C#:   const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2wdslgzhp.html

[A04] 判断变量类型
来源：http://dali.hnxiangtu.top/Article/details/gt2itkjknje.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.quarkkingdee.top/Article/details/gt2otasbbwp.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.jlsjyb.cn/Article/details/gt2hbeppwev.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.gogol.net.cn/Article/details/gt2dutieehe.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhoulong.xyz/Article/details/gt2bbiebtvf.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.mhx1999.top/Article/details/gt2kdficjco.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.andypj.xyz/Article/details/gt2dqbwcurk.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.cashguo.top/Article/details/gt2huaxsxsf.html

C#:   x.GetType().Name; x is int
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gzhuywlx.html

[A05] 整数除法与取模
来源：http://dali.yj202588.top/Article/details/gt2huudmiyr.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.nanxuanxn.top/Article/details/gt2ldqpbfeb.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.yj20258.top/Article/details/gt2vglhcwcu.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.zhixingplan.top/Article/details/gt2cnluftju.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yj202588.top/Article/details/gt2ioipsdel.html

Java: 7 / 2; 7 % 2
来源：http://dali.zhengqikj.top/Article/details/gt2gxbcphvt.html

Go:   7 / 2; 7 % 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iwlsfyjg.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.mhx1999.top/Article/details/gt2bkczryza.html

C#:   7 / 2; 7 % 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2gyxhtcbx.html

[A06] 字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2vtcynoix.html

Py:   int("42"); float("3.14")
来源：http://dali.gogol.net.cn/Article/details/gt2vagmnuiq.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.0kj1m.cn/Article/details/gt2dhnpqjbr.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.cqqwz.cn/Article/details/gt2bjbsyotm.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nvygwhxa.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.chenzaomai.com/Article/details/gt2eyaelgws.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.9152youxi.cn/Article/details/gt2bkczwlvl.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.cucudq.cn/Article/details/gt2wcpskryb.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.yanxiufei.cn/Article/details/gt2kuzcotpz.html

[A07] 数字转字符串
来源：http://dali.ehwqpu.com/Article/details/gt2ynxykbfs.html

Py:   str(42)
来源：http://dali.hnqzz.top/Article/details/gt2qhtcqwie.html

PHP:  (string) 42; strval(42)
来源：http://dali.redwolf501.top/Article/details/gt2ghprzshd.html

JS:   String(42); (42).toString()
来源：http://dali.316326.xyz/Article/details/gt2nbnpdokq.html

TS:   String(42)
来源：http://dali.xinyue.icu/Article/details/gt2vfbcltga.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.zhongyouzk.top/Article/details/gt2omeiavmr.html

Go:   strconv.Itoa(42)
来源：http://dali.0kj1m.cn/Article/details/gt2gkkkycwe.html

Ruby: 42.to_s
来源：http://dali.yanxiufei.cn/Article/details/gt2isncifam.html

C#:   42.ToString()
来源：http://dali.chenlongwang.top/Article/details/gt2hekexqwn.html

[A08] 取整与四舍五入
来源：http://dali.bjfxy.top/Article/details/gt2txvkopfh.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.vqdsnc.cn/Article/details/gt2vqqhezwk.html


<!-- 参考信息 -->