代发 wailian999

[U65] PHP：会话
来源：http://dali.xziqi.cn/Article/details/gtdsbjxkax.html

session_start();  $_SESSION["uid"] = 1;
来源：http://dali.guannengcc.top/Article/details/gttljueikr.html

[U66] PHP：设置 Cookie
来源：http://dali.dashuyun.cn/Article/details/gtcgtpokmp.html

setcookie("token", $v, ["httponly" => true, "samesite" => "Lax"]);
来源：http://dali.yuxming.cn/Article/details/gtzrxuvyno.html

[U67] PHP：处理文件上传
来源：http://dali.hongshengwenyu.top/Article/details/gtuivqjpvf.html

$_FILES["file"]["tmp_name"] 与 move_uploaded_file()
来源：http://dali.nanxuanxn.top/Article/details/gtegalbhfa.html

[U68] PHP：PDO 连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtivzqcklq.html

$pdo = new PDO("mysql:host=localhost;dbname=app", "root", "");
来源：http://dali.daxiang520.top/Article/details/gtshhqtzuc.html

[U69] PHP：PDO 预处理
来源：http://dali.havefunace.top/Article/details/gtbrwgbgsu.html

$stmt = $pdo->prepare("SELECT * FROM users WHERE id = ?");  $stmt->execute([$id]);
来源：http://dali.daria6918.cn/Article/details/gtwvkqjufb.html

[U70] PHP：PDO 事务
来源：http://dali.meibo888.top/Article/details/gtbdjepnll.html

$pdo->beginTransaction();  $pdo->commit();  $pdo->rollBack();
来源：http://dali.ybcxt.top/Article/details/gtgvzmthbc.html

[U71] PHP：抛出异常
来源：http://dali.zhijiandao.cn/Article/details/gtdfjclatk.html

throw new RuntimeException("失败", 500);
来源：http://dali.xuanzx.com/Article/details/gttnlmdqkh.html

[U72] PHP：写错误日志
来源：http://dali.wangshuangyany.cn/Article/details/gtrcsnlzmj.html

error_log("失败: " . $e->getMessage());
来源：http://dali.cashguo.top/Article/details/gtavaujiue.html

[U73] PHP：读取 ini 配置
来源：http://dali.yuanzhike.top/Article/details/gtkcybnzab.html

parse_ini_file("config.ini", true)
来源：http://dali.jiagoushi.top/Article/details/gtpfadvkzz.html

[U74] PHP：读取环境变量
来源：http://dali.quarkkingdee.top/Article/details/gtjqyyepws.html

getenv("APP_ENV") ?: "production"
来源：http://dali.andypj.xyz/Article/details/gttfeewaxe.html

[U75] PHP：依赖注入
来源：http://dali.wangshuangyany.cn/Article/details/gtgdjvzmgg.html

composer require psr/container
来源：http://dali.quarkkingdee.top/Article/details/gthgsmcpsz.html

[U76] PHP：简单路由
来源：http://dali.daria6918.cn/Article/details/gtznlprsir.html

$path = parse_url($_SERVER["REQUEST_URI"], PHP_URL_PATH);
来源：http://dali.tianlin.xyz/Article/details/gtjytknwhw.html

[U77] PHP：模板渲染
来源：http://dali.nwbrower.top/Article/details/gtmxformkw.html

composer require twig/twig
来源：http://dali.ehwqpu.com/Article/details/gthkwmfbvq.html

[U78] PHP：单元测试
来源：http://dali.ivvv.top/Article/details/gtzpaklhud.html

composer require --dev phpunit/phpunit
来源：http://dali.yuanzhike.top/Article/details/gtkwbiatgj.html

[U79] PHP：静态分析
来源：http://dali.tianlin.xyz/Article/details/gtstyvhsyf.html

composer require --dev phpstan/phpstan
来源：http://dali.yueranfly.top/Article/details/gtptitsmvj.html

[U80] PHP：代码规范修复
来源：http://dali.vqdsnc.cn/Article/details/gttbqmauih.html

composer require --dev friendsofphp/php-cs-fixer
来源：http://dali.zhongyouzk.top/Article/details/gtedqladuw.html

[U81] JS：初始化项目
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjfrabsgr.html

npm init -y;  npm i express
来源：http://dali.pycfn.com/Article/details/gtgelwvlow.html

[U82] JS：package.json 脚本
来源：http://dali.shuidangran.top/Article/details/gtipwzogmn.html

"scripts": { "dev": "vite", "build": "vite build" }
来源：http://dali.pycfn.com/Article/details/gtxkatkmlb.html

[U83] JS：ES Module 导入导出
来源：http://dali.cucudq.cn/Article/details/gthhjcsaza.html

export const a = 1;  import { a } from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtnfzjwfgg.html

[U84] JS：CommonJS 写法
来源：http://dali.yonumen.top/Article/details/gtiupzvavr.html

module.exports = { a };  const { a } = require("./m");
来源：http://dali.jinghuilouyu.cn/Article/details/gtuvrbfeyh.html

[U85] JS：可选链
来源：http://dali.zhiwuduotai.top/Article/details/gtrezmrdwi.html

a?.b?.c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjgftiis.html

[U86] JS：空值合并
来源：http://dali.aizwys.cn/Article/details/gttzggiudf.html

a ?? b
来源：http://dali.zycfv.cn/Article/details/gthhdamuow.html

[U87] JS：解构默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtyqreihxn.html

const { a = 1, b = 2 } = obj;
来源：http://dali.yj202588.top/Article/details/gtgncnivwa.html

[U88] JS：对象展开合并
来源：http://dali.yuanzhike.top/Article/details/gtaudwysmj.html

{ ...a, ...b }
来源：http://dali.yuanzhike.top/Article/details/gtvbjirtuj.html

[U89] JS：数组去重
来源：http://dali.aibaodan.cn/Article/details/gthhrahlfx.html

[...new Set(arr)]
来源：http://dali.redwolf501.top/Article/details/gtczbzzyrl.html

[U90] JS：数字数组排序
来源：http://dali.jiagoushi.top/Article/details/gtbrvlvuqc.html

[...arr].sort((a, b) => a - b)
来源：http://dali.quarkkingdee.top/Article/details/gtbdmuwadn.html

[U91] JS：对象键值遍历
来源：http://dali.pycfn.com/Article/details/gttkihvzmg.html

Object.entries(obj).forEach(([k, v]) => {});
来源：http://dali.vqdsnc.cn/Article/details/gtplsrlgjw.html

[U92] JS：深拷贝
来源：http://dali.hysaishi.cn/Article/details/gtndbzqjxl.html

structuredClone(obj)
来源：http://dali.dashuyun.cn/Article/details/gtzjaripjw.html

[U93] JS：模板字符串
来源：http://dali.andypj.xyz/Article/details/gtpbfklxvo.html

`共 ${n} 条`
来源：http://dali.kuanghao11.cn/Article/details/gtdrbnjwhj.html

[U94] JS：箭头函数
来源：http://dali.yanxiufei.cn/Article/details/gtpzlodpud.html

const double = x => x * 2;
来源：http://dali.tian-w.cn/Article/details/gtifcrxquj.html

[U95] JS：Promise 包装
来源：http://dali.iojbl.cn/Article/details/gtdwvuwyjl.html

new Promise((resolve, reject) => {})
来源：http://dali.zhengqikj.top/Article/details/gtndwrgcff.html

[U96] JS：async/await 与异常
来源：http://dali.xuetiantiany.cn/Article/details/gtobqcaaon.html

try { const d = await f(); } catch (e) { console.error(e); }
来源：http://dali.quarkkingdee.top/Article/details/gtdjsydovb.html

[U97] JS：并发请求
来源：http://dali.haohaochexian.top/Article/details/gtrlxgvjac.html

await Promise.all(urls.map(u => fetch(u)))
来源：http://dali.cqqwz.cn/Article/details/gtmtetrjeg.html

[U98] JS：fetch 带 JSON
来源：http://dali.quarkkingdee.top/Article/details/gtkkvngruv.html

await fetch(url, { method: "POST", headers: { "Content-Type": "application/json" }, body: JSON.stringify(d) })
来源：http://dali.jinghuilouyu.cn/Article/details/gttrhnvluu.html

[U99] JS：事件监听
来源：http://dali.guowangkeji.top/Article/details/gtuakzajga.html

el.addEventListener("click", e => {})
来源：http://dali.pycfn.com/Article/details/gtepfjlety.html

[U100] JS：DOM 查询
来源：http://dali.9152youxi.cn/Article/details/gtxmeuaqee.html

document.querySelector(".item")
来源：http://dali.zhoulong.xyz/Article/details/gtjxofwzbg.html

[U101] JS：classList 操作
来源：http://dali.xinyue.icu/Article/details/gtazupenxc.html

el.classList.toggle("active")
来源：http://dali.guowangkeji.top/Article/details/gtirltjibv.html

[U102] JS：本地存储
来源：http://dali.c1oappe.top/Article/details/gthfpqfoyu.html

localStorage.setItem("k", JSON.stringify(v))
来源：http://dali.jinqigufen.top/Article/details/gtnkirbusb.html

[U103] JS：定时器
来源：http://dali.aibaodan.cn/Article/details/gtrqdrsgwl.html

setTimeout(fn, 1000);  setInterval(fn, 1000);
来源：http://dali.316326.xyz/Article/details/gtvbhabvgl.html

[U104] JS：防抖
来源：http://dali.yvedp.cn/Article/details/gtxikdmowy.html

const debounce = (fn, ms) => { let t; return (...a) => { clearTimeout(t); t = setTimeout(() => fn(...a), ms); }; };
来源：http://dali.hongshengwenyu.top/Article/details/gtrvabbllr.html

[U105] JS：节流
来源：http://dali.birdmap.top/Article/details/gthapzemxr.html

const throttle = (fn, ms) => { let last = 0; return (...a) => { const n = Date.now(); if (n - last >= ms) { last = n; fn(...a); } }; };
来源：http://dali.tanke756.top/Article/details/gtsmywfjux.html

[U106] JS：日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtaskmzg.html

new Intl.DateTimeFormat("zh-CN", { dateStyle: "medium" }).format(new Date())
来源：http://dali.pengpengdd.cyou/Article/details/gttqtfnqoo.html

[U107] JS：数字千分位
来源：http://dali.shanyushiyangkeji.top/Article/details/gthprziewt.html

new Intl.NumberFormat("en-US").format(1234567)
来源：http://dali.zycfv.cn/Article/details/gthlxlemao.html

[U108] JS：随机整数
来源：http://dali.fengsongda.top/Article/details/gtwrxiogbv.html

Math.floor(Math.random() * (max - min + 1)) + min
来源：http://dali.fzhhl.top/Article/details/gthexypyao.html

[U109] JS：数组分组
来源：http://dali.sufxvd.cn/Article/details/gtsljiyctt.html

Object.groupBy(arr, x => x.type)
来源：http://dali.feifeiyinyue.top/Article/details/gtvucooneg.html

[U110] JS：数组分块
来源：http://dali.cucudq.cn/Article/details/gtkfpkbgdy.html

arr.reduce((acc, x, i) => (i % size ? acc : [...acc, arr.slice(i, i + size)]), [])
来源：http://dali.zhixingplan.top/Article/details/gtbgtpyrql.html

[U111] JS：对象转 Map
来源：http://dali.ydzc1.top/Article/details/gtiwtfxruz.html

new Map(Object.entries(obj))
来源：http://dali.yongpay.top/Article/details/gtcsotvnvg.html

[U112] JS：字符串补位
来源：http://dali.sweek.top/Article/details/gtoaylgxft.html

"7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtsjfnmlmi.html

[U113] JS：正则替换全部
来源：http://dali.jyoumei.cn/Article/details/gtqsfgurcy.html

s.replaceAll("a", "b")
来源：http://dali.chenlongwang.top/Article/details/gtmvcleblb.html

[U114] JS：JSON 深比较
来源：http://dali.meibo888.top/Article/details/gtwjhflbea.html

JSON.stringify(a) === JSON.stringify(b)
来源：http://dali.yongpay.top/Article/details/gttvbpfpdc.html

[U115] JS：生成 UUID
来源：http://dali.aizwys.cn/Article/details/gtsvgbktot.html

crypto.randomUUID()
来源：http://dali.hongshengwenyu.top/Article/details/gtsrjghtix.html

[U116] JS：类型检查（JSDoc）
来源：http://dali.ivvv.top/Article/details/gtzuhyzqlg.html

/** @param {string} name */ function f(name) {}
来源：http://dali.xylfe.cn/Article/details/gtqsjegoqv.html

[U117] JS：单元测试
来源：http://dali.haohaochexian.top/Article/details/gtqkdoxwmu.html

npm i -D vitest;  npx vitest
来源：http://dali.shanyushiyangtech.top/Article/details/gtgrtemrgk.html

[U118] JS：开发服务器
来源：http://dali.yongpay.top/Article/details/gthxcejspe.html

npm i -D vite;  npx vite
来源：http://dali.zhoulong.xyz/Article/details/gtqoxnucyj.html

[U119] JS：生产构建
来源：http://dali.redwolf501.top/Article/details/gtahrqacqg.html

npx vite build
来源：http://dali.zycfv.cn/Article/details/gtldbndblu.html

[U120] JS：读取环境变量（Vite）
来源：http://dali.zhoulong.xyz/Article/details/gtzoqyreid.html

import.meta.env.VITE_API_URL
来源：http://dali.jqgfzy.top/Article/details/gtzsbowbyv.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtyzrifwwp.html

统计汇总
来源：http://dali.hnxiangtu.top/Article/details/gtakalyzrz.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtvrxyvgvf.html

按语言统计（条）：
来源：http://dali.sweek.top/Article/details/gtrzwaujae.html

Python ......... 252
来源：http://dali.wangshuangyany.cn/Article/details/gtmmtylznp.html

PHP ............ 252
来源：http://dali.fengsongda.top/Article/details/gtnyshgbpu.html

JavaScript ..... 252
来源：http://dali.nanxinkj.top/Article/details/gtztkoumqd.html

TypeScript ..... 212
来源：http://dali.yuxming.cn/Article/details/gtqdwzhist.html

Java ........... 212
来源：http://dali.gogol.net.cn/Article/details/gtajawpbct.html

Go ............. 212
来源：http://dali.wangshuangyany.cn/Article/details/gtswmbyrwc.html

Ruby ........... 212
来源：http://dali.gaohongyu789.top/Article/details/gtxijvixig.html

C# ............. 212
来源：http://dali.meibo888.top/Article/details/gthhwhgebd.html

C .............. 30
来源：http://dali.fengsongda.top/Article/details/gtnclmyqjf.html

C++ ............ 30
来源：http://dali.xziqi.cn/Article/details/gtmlsykgop.html

SQL ............ 90
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbzdwial.html

Bash ........... 80
来源：http://dali.nanxinkj.top/Article/details/gttizhjgbw.html

Kotlin ......... 15
来源：http://dali.yueranfly.top/Article/details/gtiqymbiec.html

Swift .......... 15
来源：http://dali.xziqi.cn/Article/details/gtvpihrfgi.html

Lua ............ 10
来源：http://dali.chenlongwang.top/Article/details/gtjiyenyre.html

Perl ........... 10
来源：http://dali.ivvv.top/Article/details/gtosyjfwwg.html

Scala .......... 10
来源：http://dali.bjfxy.top/Article/details/gtkqvxervw.html

------------------------------------
来源：http://dali.guannengcc.top/Article/details/gtalyuwrkq.html

合计 ........... 2106 条
来源：http://dali.guowangkeji.top/Article/details/gtumxhcupg.html

按章节统计：
来源：http://dali.yvedp.cn/Article/details/gtsciexigx.html

A 基础语法与类型       26 个任务 × 8 语言 =  208
来源：http://dali.aizwys.cn/Article/details/gttdsmerte.html

B 流程控制             16 个任务 × 8 语言 =  128
来源：http://dali.feifeiyinyue.top/Article/details/gtggpfdflb.html

C 函数与作用域         16 个任务 × 8 语言 =  128
来源：http://dali.yangfankeji.com/Article/details/gtysmitqpw.html

D 数组 / 列表 / 集合   26 个任务 × 8 语言 =  208
来源：http://dali.cashguo.top/Article/details/gtpnqxtjew.html

E 字符串处理           22 个任务 × 8 语言 =  176
来源：http://dali.gaohongyu789.top/Article/details/gtahvzrjoc.html

F 文件与目录           12 个任务 × 8 语言 =   96
来源：http://dali.dashuyun.cn/Article/details/gtbnevmlql.html

G 面向对象             16 个任务 × 8 语言 =  128
来源：http://dali.redwolf501.top/Article/details/gtuydpwipk.html

H 异常与错误处理       10 个任务 × 8 语言 =   80
来源：http://dali.zhixingplan.top/Article/details/gtmrlecvgm.html

I 正则表达式            8 个任务 × 8 语言 =   64
来源：http://dali.snrcjt.cn/Article/details/gtdggtodjf.html

J 日期与时间           10 个任务 × 8 语言 =   80
来源：http://dali.hnxiangtu.top/Article/details/gtfdlzqoay.html

K JSON 与序列化         8 个任务 × 8 语言 =   64
来源：http://dali.hywenlv.cn/Article/details/gtcgijufwn.html

L 网络请求              8 个任务 × 8 语言 =   64
来源：http://dali.yj20258888.top/Article/details/gtwhnqtemr.html

M 命令行 / 进程         8 个任务 × 8 语言 =   64
来源：http://dali.cdnleiting.top/Article/details/gtyewkkkij.html

N 数据结构与算法       12 个任务 × 8 语言 =   96
来源：http://dali.yuanzhike.top/Article/details/gtlnuroykc.html

O 并发与异步            6 个任务 × 8 语言 =   48
来源：http://dali.birdmap.top/Article/details/gtqspzitxq.html

P 常用工具函数          8 个任务 × 8 语言 =   64
来源：http://dali.cheryme.top/Article/details/gtufjdxfdt.html

Q SQL 专题                              90
来源：http://dali.xinyue.icu/Article/details/gtxqnhwpab.html

R Bash 专题                             80
来源：http://dali.ywan-chungtsiang.top/Article/details/gtktjjhtrk.html

S C / C++ 专题                          60
来源：http://dali.ppjwa.cn/Article/details/gtdjbqvfwe.html

T 其他语言补充                          60
来源：http://dali.ybcxt.top/Article/details/gthtwbaifz.html

U 高频实用片段                         120
来源：http://dali.sweek.top/Article/details/gtclsvkcvm.html

------------------------------------
来源：http://dali.ydzc1.top/Article/details/gtcqcxzbek.html

合计                                  2106 条
来源：http://dali.daria6918.cn/Article/details/gtaexnarqz.html

--------------------------------------------------------------------------------
来源：http://dali.gaohongyu789.top/Article/details/gtafupcdhm.html

使用提醒
来源：http://dali.jqgfzy.top/Article/details/gtffyljdhj.html

--------------------------------------------------------------------------------
来源：http://dali.daxiang520.top/Article/details/gtuuydrewk.html

1. 示例追求"最小可用"，正式项目中请补齐导入、错误处理与边界判断。
来源：http://dali.mhx1999.top/Article/details/gtdzetuvjo.html

2. 涉及文件、网络、数据库的示例，注意资源释放与异常捕获。
来源：http://dali.hfpthk.cn/Article/details/gtbiqwtiwl.html

3. 语言版本差异较大（如 Python 3.10 的 match、Java 17 的 record/switch 箭头），
来源：http://dali.mhx1999.top/Article/details/gtqxaliwgt.html

在旧版本上使用前请先确认语法支持情况。
来源：http://dali.haohaochexian.top/Article/details/gthvyeeiuq.html

4. 标注"手写"的条目是因为该语言缺少对应内置能力，实际项目中可引入成熟库。
来源：http://dali.gzhubu.top/Article/details/gtzpfclnrl.html

—— 文件结束 ——
来源：http://dali.havefunace.top/Article/details/gtwhjkdmqc.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtivpunvzd.html

程序语言常见例子速查手册（2024 版）
来源：http://dali.guowangkeji.top/Article/details/gtbuzucdzd.html

Common Programming Examples Cheat Book
来源：http://dali.gotoacloud.top/Article/details/gtetxfcyhe.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtblcrxtoq.html

【收录内容】
来源：http://dali.zhiwuduotai.top/Article/details/gtxxwzhtje.html

覆盖 12 种语言 / 语法与常见 API：
来源：http://dali.jlsjyb.cn/Article/details/gtozrtslap.html

Python · PHP · JavaScript · TypeScript · Java · Go · Ruby · C#
来源：http://dali.xuetiantiany.cn/Article/details/gtytbzgfgh.html

SQL · Bash · C · C++
来源：http://dali.gzhubu.top/Article/details/gtiynkoury.html

按「任务」分组：每个任务下按语言各给出一条最小可用示例。
来源：http://dali.wangshuangyany.cn/Article/details/gtpgejvhia.html

【使用说明】
来源：http://dali.nwbrower.top/Article/details/gtdusudjgj.html

1. 每个任务形如 "[编号] 任务名"，下面每行以语言标记开头：
来源：http://dali.dianchejie.cn/Article/details/gtzdinlwyo.html

Py:    Python        PHP:   PHP           JS:    JavaScript
来源：http://dali.chenlongwang.top/Article/details/gttrkychww.html

TS:    TypeScript    Java:  Java          Go:    Go
来源：http://dali.wangdashe.top/Article/details/gtlhhentte.html

Ruby:  Ruby          C#:    C#            SQL:   SQL
来源：http://dali.shuidangran.top/Article/details/gtbqisqnvl.html

Bash:  Shell         C:     C             C++:   C++
来源：http://dali.sxryk.cn/Article/details/gtzhxousua.html

2. 示例只展示核心写法，刻意省略 import / require / include / using 等样板代码。
来源：http://dali.tianlin.xyz/Article/details/gtombfyycg.html

需要完整可运行文件时，请自行补齐当前语言的导入语句。
来源：http://dali.zhengqikj.top/Article/details/gtboemddsl.html

3. 语法基准：Python 3.10+ / PHP 8.1+ / ES2020+ / TypeScript 5 / Java 17 /
来源：http://dali.xylfe.cn/Article/details/gtkoqtzlir.html

Go 1.21+ / Ruby 3.x / C# 10+ / C17 / C++17。
来源：http://dali.pengpengdd.cyou/Article/details/gtbeeegztq.html

4. 检索建议：用编辑器或浏览器 Ctrl+F 搜关键词，如 "排序" "读取文件" "正则"。
来源：http://dali.ppjwa.cn/Article/details/gtpnvmkstd.html

5. 标记为 "// 无" 表示该语言没有对应的一等语法，需用替代写法（示例给出替代方案）。
来源：http://dali.sxryk.cn/Article/details/gtchogqhjv.html

6. 符号 "⏎" 表示代码在此处换行（主要用于 Python 等强制缩进、无法压成一行的结构）。
来源：http://dali.jinyuanbaomall.cn/Article/details/gthzergwxf.html

【文件统计】
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeeqsgcc.html

语言示例共 2106 条，分布见本文末尾的「统计汇总」。
来源：http://dali.sufxvd.cn/Article/details/gtdmpmntgl.html

--------------------------------------------------------------------------------
来源：http://dali.xinyue.icu/Article/details/gtzgzobnvf.html

目  录
来源：http://dali.jqgufenzy.top/Article/details/gttwdrmioc.html

--------------------------------------------------------------------------------
来源：http://dali.gogol.net.cn/Article/details/gttuzrzbkf.html

A. 基础语法与类型              （第 1 节，26 个任务，208 条）
来源：http://dali.nwbrower.top/Article/details/gteeklkxlo.html

B. 流程控制                    （第 2 节，16 个任务，128 条）
来源：http://dali.xuanzx.com/Article/details/gthikubibz.html

C. 函数与作用域                （第 3 节，16 个任务，128 条）
来源：http://dali.jiagoushi.top/Article/details/gtdqojhyzy.html

D. 数组 / 列表 / 集合          （第 4 节，26 个任务，208 条）
来源：http://dali.shanyushiyangtech.top/Article/details/gtztexzurf.html

E. 字符串处理                  （第 5 节，22 个任务，176 条）
来源：http://dali.chenjidiqi.icu/Article/details/gttirqbjie.html

F. 文件与目录                  （第 6 节，12 个任务，96 条）
来源：http://dali.aibaodan.cn/Article/details/gtxfulvdlj.html

G. 面向对象                    （第 7 节，16 个任务，128 条）
来源：http://dali.zhongyouzk.top/Article/details/gtbkjlqvkc.html

H. 异常与错误处理              （第 8 节，10 个任务，80 条）
来源：http://dali.cdnleiting.top/Article/details/gtzmobbvit.html

I. 正则表达式                  （第 9 节，8 个任务，64 条）
来源：http://dali.redwolf501.top/Article/details/gtrutngkfm.html

J. 日期与时间                  （第 10 节，10 个任务，80 条）
来源：http://dali.zhengqikj.top/Article/details/gtaqibnlai.html

K. JSON 与序列化               （第 11 节，8 个任务，64 条）
来源：http://dali.smart0.xyz/Article/details/gtvfpkazyq.html

L. 网络请求                    （第 12 节，8 个任务，64 条）
来源：http://dali.aizwys.cn/Article/details/gtkmzqsnhf.html

M. 命令行 / 进程 / 环境        （第 13 节，8 个任务，64 条）
来源：http://dali.jlsjyb.cn/Article/details/gtrgtygsaa.html

N. 数据结构与算法              （第 14 节，12 个任务，96 条）
来源：http://dali.c1oappe.top/Article/details/gtghyqxjoh.html

O. 并发与异步                  （第 15 节，6 个任务，48 条）
来源：http://dali.zhongyouzk.top/Article/details/gttsyafyli.html

P. 常用工具函数                （第 16 节，8 个任务，64 条）
来源：http://dali.jqgfzy.top/Article/details/gtsuzioniw.html

Q. SQL 专题                    （第 17 节，90 条）
来源：http://dali.wangdashe.top/Article/details/gtcmtcikiu.html

R. Bash 专题                   （第 18 节，80 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjekxfxvu.html

S. C / C++ 专题                （第 19 节，60 条）
来源：http://dali.chenzaomai.com/Article/details/gtveuhvvts.html

T. 其他语言补充                （第 20 节，60 条：Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhongyouzk.top/Article/details/gtsydideju.html

U. 高频实用片段                （第 21 节，120 条：Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtcoqoikdr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtwptdpijf.html

A. 基础语法与类型
来源：http://dali.ivvv.top/Article/details/gtynjyxoto.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtisxnckfh.html

[A01] Hello World
来源：http://dali.hnqzz.top/Article/details/gtrpikgzxw.html

Py:   print("Hello, World!")
来源：http://dali.pengpengdd.cyou/Article/details/gtfhsiwsdb.html

PHP:  echo "Hello, World!";
来源：http://dali.shzxlz.cn/Article/details/gtuayncgdn.html

JS:   console.log("Hello, World!");
来源：http://dali.hnxiangtu.top/Article/details/gtgqcwriqb.html

TS:   const msg: string = "Hello, World!"; console.log(msg);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzzmnkiwd.html

Java: System.out.println("Hello, World!");
来源：http://dali.feifeiyinyue.top/Article/details/gtxdfdieor.html

Go:   fmt.Println("Hello, World!")
来源：http://dali.havefunace.top/Article/details/gtrcchagly.html

Ruby: puts "Hello, World!"
来源：http://dali.cheryme.top/Article/details/gtwhncydsc.html

C#:   Console.WriteLine("Hello, World!");
来源：http://dali.quarkkingdee.top/Article/details/gtmrnpyolj.html

[A02] 变量声明与赋值
来源：http://dali.jinghuilouyu.cn/Article/details/gtxwdvzlke.html

Py:   name = "Alex"; age = 20            # 动态类型，无需声明
来源：http://dali.daxiang520.top/Article/details/gtgiyuvskw.html

PHP:  $name = "Alex"; $age = 20;
来源：http://dali.kuanghao11.cn/Article/details/gttkqkgajb.html

JS:   let name = "Alex"; const age = 20;
来源：http://dali.yueranfly.top/Article/details/gtunqrtesn.html

TS:   let name: string = "Alex"; const age: number = 20;
来源：http://dali.cqqwz.cn/Article/details/gtfzfxkaez.html

Java: String name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gtxhwzyzby.html

Go:   name := "Alex"; age := 20
来源：http://dali.9152youxi.cn/Article/details/gtrgzlywlu.html

Ruby: name = "Alex"; age = 20
来源：http://dali.hysaishi.cn/Article/details/gtgbvepquc.html

C#:   string name = "Alex"; int age = 20;
来源：http://dali.jyoumei.cn/Article/details/gteuummags.html

[A03] 常量定义
来源：http://dali.aibaodan.cn/Article/details/gtewijhmnh.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.nwbrower.top/Article/details/gtglfuijsq.html

PHP:  const PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtzxctyjwm.html

JS:   const PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtzrtgjquw.html

TS:   const PI: number = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtzindzwac.html

Java: static final double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtnpmvemrz.html

Go:   const PI = 3.14159
来源：http://dali.gotoacloud.top/Article/details/gttydiakei.html

Ruby: PI = 3.14159
来源：http://dali.pengpengdd.cyou/Article/details/gtubqojgsl.html

C#:   const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtxzbhzcar.html

[A04] 判断变量类型
来源：http://dali.cashguo.top/Article/details/gtazuybmwb.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cheryme.top/Article/details/gtwroekyie.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.tian-w.cn/Article/details/gtfnbjxhxa.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.ydzc1.top/Article/details/gtmjjxyucp.html

TS:   typeof x; x instanceof Date
来源：http://dali.zhijiandao.cn/Article/details/gtjudhunpm.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.aizwys.cn/Article/details/gtnwhfbivi.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.hammf.cn/Article/details/gtmjozcfth.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.gzhubu.top/Article/details/gtofqfqevc.html

C#:   x.GetType().Name; x is int
来源：http://dali.ppjwa.cn/Article/details/gtrxngkgmn.html

[A05] 整数除法与取模
来源：http://dali.gogol.net.cn/Article/details/gtxcrryaqt.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.dashuyun.cn/Article/details/gtwtfyfupa.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.vqdsnc.cn/Article/details/gthusqogth.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.hywenlv.cn/Article/details/gthbjoyviz.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.yonumen.top/Article/details/gtlbfasngs.html

Java: 7 / 2; 7 % 2
来源：http://dali.havefunace.top/Article/details/gtzadhzoev.html

Go:   7 / 2; 7 % 2
来源：http://dali.sweek.top/Article/details/gtwiotitqi.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.dashuyun.cn/Article/details/gtsllftwcv.html

C#:   7 / 2; 7 % 2
来源：http://dali.cheryme.top/Article/details/gtygokkftl.html

[A06] 字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiojmcpdq.html

Py:   int("42"); float("3.14")
来源：http://dali.guowangkeji.top/Article/details/gtlttermge.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.snrcjt.cn/Article/details/gtcnhlfcfz.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.fengsongda.top/Article/details/gtxdxtbfca.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.zhengqikj.top/Article/details/gtldldauji.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.shuidangran.top/Article/details/gtvnulqmkw.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.jqgufenzy.top/Article/details/gtjcnezchn.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.hongshengwenyu.top/Article/details/gtfumvmajc.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.meibo888.top/Article/details/gtbhsilxqi.html

[A07] 数字转字符串
来源：http://dali.tanke756.top/Article/details/gtbxzljlyx.html

Py:   str(42)
来源：http://dali.snrcjt.cn/Article/details/gtraevcxan.html

PHP:  (string) 42; strval(42)
来源：http://dali.yj20258888.top/Article/details/gtsoyqevgh.html

JS:   String(42); (42).toString()
来源：http://dali.zhixingplan.top/Article/details/gtjqzkouki.html

TS:   String(42)
来源：http://dali.guowangkeji.top/Article/details/gtokycjagz.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.dashuyun.cn/Article/details/gtjpacijbl.html

Go:   strconv.Itoa(42)
来源：http://dali.cashguo.top/Article/details/gtzjryyjsl.html

Ruby: 42.to_s
来源：http://dali.cqqwz.cn/Article/details/gtfazpdcaz.html

C#:   42.ToString()
来源：http://dali.sxryk.cn/Article/details/gtpwwgoeef.html

[A08] 取整与四舍五入
来源：http://dali.ybcxt.top/Article/details/gtjvojvmdr.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.tianlin.xyz/Article/details/gtqeflldko.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.daxiang520.top/Article/details/gtwawyuqxj.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.xylfe.cn/Article/details/gtnxozejye.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.andypj.xyz/Article/details/gtsrfzdixy.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.jyoumei.cn/Article/details/gtujweryem.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gttcgsbwnl.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.yj202588.top/Article/details/gtcvdqquov.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.mhx1999.top/Article/details/gtoxcnxskw.html

[A09] 绝对值与最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtiksglhts.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtxhnxtnxi.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.havefunace.top/Article/details/gtckztawab.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtzuetpyin.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrigzsfvc.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.meibo888.top/Article/details/gtbkxxxhbi.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.mhx1999.top/Article/details/gtinjdwbfu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.svipenyu.cn/Article/details/gtreijwiyl.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtphwcqfyj.html


<!-- 参考信息 -->