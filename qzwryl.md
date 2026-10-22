代发 wailian999

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.gogol.net.cn/Article/details/gt2zhfgfubo.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.yuxming.cn/Article/details/gt2bmpffkgt.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.gogol.net.cn/Article/details/gt2swatmutb.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.yj202588.top/Article/details/gt2kjsjejkx.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.0kj1m.cn/Article/details/gt2wvxfdzln.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.birdmap.top/Article/details/gt2okqomdbt.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.chenjidiqi.icu/Article/details/gt2watfimij.html

[A09] 绝对值与最大最小值
来源：http://dali.yj202588.top/Article/details/gt2lbomtlin.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.aibaodan.cn/Article/details/gt2gsvyzwrf.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.gotoacloud.top/Article/details/gt2gyrfxdub.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.sxryk.cn/Article/details/gt2vfhzayyt.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258888.top/Article/details/gt2cxhfpmtk.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.chenjidiqi.icu/Article/details/gt2onfjazmc.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.nanxinkj.top/Article/details/gt2yeguqtoo.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zrmzvwak.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gt2fvxjdwgv.html

[A10] 生成随机数
来源：http://dali.dashuyun.cn/Article/details/gt2rsgynjge.html

Py:   import random; random.randint(1, 100)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwyyxzro.html

PHP:  random_int(1, 100);
来源：http://dali.ehwqpu.com/Article/details/gt2gewbkbsx.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yj202588.top/Article/details/gt2tskhcquv.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.wangshuangyany.cn/Article/details/gt2ofefkvfo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.xziqi.cn/Article/details/gt2zzfiopan.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gzhubu.top/Article/details/gt2uuxeowuw.html

Ruby: rand(1..100)
来源：http://dali.mhx1999.top/Article/details/gt2foidfsxu.html

C#:   new Random().Next(1, 101)
来源：http://dali.smart0.xyz/Article/details/gt2shtqxwxh.html

[A11] 条件表达式（三元）
来源：http://dali.daxiang520.top/Article/details/gt2ewnqfbrr.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.9152youxi.cn/Article/details/gt2brxctvaw.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhoulong.xyz/Article/details/gt2mdjkyxhy.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.hnqzz.top/Article/details/gt2bskvaqux.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.yj20258.top/Article/details/gt2aofvzhjj.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.hywenlv.cn/Article/details/gt2sgtqoghf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.chenjidiqi.icu/Article/details/gt2iocqpahc.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.nanxuanxn.top/Article/details/gt2rzgcorzv.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.jinqigfzy.top/Article/details/gt2raedbcca.html

[A12] 字符串插值 / 格式化
来源：http://dali.cucudq.cn/Article/details/gt2ftykqdre.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azwzolvk.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gzhubu.top/Article/details/gt2iigqsqig.html

JS:   `Hello, ${name}!`
来源：http://dali.haohaochexian.top/Article/details/gt2hxbaxncg.html

TS:   `Hello, ${name}!`
来源：http://dali.xylfe.cn/Article/details/gt2tnnuclaw.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2leyafiym.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.sweek.top/Article/details/gt2pzxdcfut.html

Ruby: "Hello, #{name}!"
来源：http://dali.316326.xyz/Article/details/gt2dznwvyru.html

C#:   $"Hello, {name}!"
来源：http://dali.sweek.top/Article/details/gt2xqnfatit.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.aibaodan.cn/Article/details/gt2uyjavrul.html

Py:   "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gt2hupahnls.html

PHP:  "第一行\n第二行"
来源：http://dali.gzhubu.top/Article/details/gt2njjwamck.html

JS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gt2xhppluhs.html

TS:   "第一行\n第二行"
来源：http://dali.feifeiyinyue.top/Article/details/gt2usuixnlw.html

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2hkpabmhz.html

Go:   "第一行\n第二行"
来源：http://dali.xuetiantiany.cn/Article/details/gt2yswfjhxn.html

Ruby: "第一行\n第二行"
来源：http://dali.zycfv.cn/Article/details/gt2fmuotcfo.html

C#:   "第一行\n第二行"
来源：http://dali.jqgufenzy.top/Article/details/gt2rdjqclij.html

[A14] 注释写法
来源：http://dali.yj20258.top/Article/details/gt2sxmighpi.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.sufxvd.cn/Article/details/gt2cubysnga.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.zhijiandao.cn/Article/details/gt2nfsqrhye.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2ghnzurwi.html

TS:   // 单行；/* 多行 */
来源：http://dali.wangshuangyany.cn/Article/details/gt2ykbieiom.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.jianghu66.top/Article/details/gt2yopmiqey.html

Go:   // 单行；/* 多行 */
来源：http://dali.hnxiangtu.top/Article/details/gt2lqbocvvc.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.iojbl.cn/Article/details/gt2dgaimuxe.html

C#:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gt2enyxivkw.html

[A15] 空值判断与默认值
来源：http://dali.zdqjudy.top/Article/details/gt2soxulnur.html

Py:   value = data or "默认值"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bcojrdxb.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cashguo.top/Article/details/gt2srvmnnhv.html

JS:   const value = data ?? "默认值";
来源：http://dali.guowangkeji.top/Article/details/gt2kckpyhxp.html

TS:   const value = data ?? "默认值";
来源：http://dali.hfpthk.cn/Article/details/gt2ljeppmgt.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.xinyue.icu/Article/details/gt2cwhctcxu.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jlsjyb.cn/Article/details/gt2glnfhwvx.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gt2ziyjzigs.html

C#:   var value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gt2oavixuiq.html

[A16] 真假值判断规则
来源：http://dali.yvedp.cn/Article/details/gt2thqsfnae.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.aizwys.cn/Article/details/gt2nkqtjwbv.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sweek.top/Article/details/gt2prjabvcz.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.pengpengdd.cyou/Article/details/gt2hotxtwch.html

TS:   if (!x) {}
来源：http://dali.daxiang520.top/Article/details/gt2wtxpqiwb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2mvpdjode.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cheryme.top/Article/details/gt2qyzeftzq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.c1oappe.top/Article/details/gt2sqvwdmbe.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.birdmap.top/Article/details/gt2jttaaksr.html

[A17] 位运算
来源：http://dali.ybcxt.top/Article/details/gt2moaijloq.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gt2miycigwt.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.chenzaomai.com/Article/details/gt2rljzdoqy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gt2rilqxjot.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.chenlongwang.top/Article/details/gt2fqdcorwt.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2xsopsjog.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gt2pezcvzes.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gt2atrdwren.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gt2nnybzodc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqryxdwv.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gt2kgurgwyq.html

PHP:  ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gt2wvydlhjr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nanxuanxn.top/Article/details/gt2rabqrrol.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yueranfly.top/Article/details/gt2tsmojjdb.html

Java: (int) 'A'; (char) 65
来源：http://dali.iojbl.cn/Article/details/gt2bvmgvuma.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxinkj.top/Article/details/gt2rmewxyre.html

Ruby: "A".ord; 65.chr
来源：http://dali.yvedp.cn/Article/details/gt2qqmsykaj.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gt2mbyejfve.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gt2qhwjtsre.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gt2djekelob.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tianlin.xyz/Article/details/gt2kjngylpd.html

JS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gt2ufqfjlfx.html

TS:   [a, b] = [b, a];
来源：http://dali.shangyingyoupin.top/Article/details/gt2ybegyoxm.html

Java: int t = a; a = b; b = t;
来源：http://dali.svipenyu.cn/Article/details/gt2okluvbob.html

Go:   a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gt2kqkkypsw.html

Ruby: a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gt2hltwiemb.html

C#:   (a, b) = (b, a);
来源：http://dali.zdqjudy.top/Article/details/gt2nukakibu.html

[A20] 读取标准输入
来源：http://dali.yj20258.top/Article/details/gt2wxctiaib.html

Py:   name = input("请输入：")
来源：http://dali.hnxiangtu.top/Article/details/gt2tpzqurkz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.redwolf501.top/Article/details/gt2dpappohl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daxiang520.top/Article/details/gt2aevfilhr.html

TS:   // Node.js：readline 模块
来源：http://dali.9152youxi.cn/Article/details/gt2mxuiegee.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.gogol.net.cn/Article/details/gt2cailcnnw.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.9152youxi.cn/Article/details/gt2pohcuwaj.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gt2bbxkjxkj.html

C#:   Console.ReadLine();
来源：http://dali.yj20258888.top/Article/details/gt2zvrubdsp.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gt2ddmrwtug.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gt2ajtehuly.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.aibaodan.cn/Article/details/gt2pdmhsdzn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hnxiangtu.top/Article/details/gt2dxuhvkkr.html

TS:   (3.14159).toFixed(2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2spgrzuvv.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gt2lbgyyied.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gt2nyvqvoym.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gt2qmzwianb.html

C#:   3.14159.ToString("F2")
来源：http://dali.haohaochexian.top/Article/details/gt2qpahdkya.html

[A22] 获取字符串长度
来源：http://dali.yj20258888.top/Article/details/gt2czjeswly.html

Py:   len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ekiitvcz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.fzhhl.top/Article/details/gt2gkjwsdpa.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jinqigufen.top/Article/details/gt2rtrouuse.html

TS:   s.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zuvlsegu.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2tpjyyxqj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2bujlufpr.html

Ruby: s.length
来源：http://dali.sufxvd.cn/Article/details/gt2ilozikdw.html

C#:   s.Length
来源：http://dali.hywenlv.cn/Article/details/gt2rpibwqbd.html

[A23] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iulbrfjw.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lrzsipxv.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cheryme.top/Article/details/gt2bzxbsrup.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guannengcc.top/Article/details/gt2dnldaazs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gt2uximvjyg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shuidangran.top/Article/details/gt2gufrpczj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gogol.net.cn/Article/details/gt2fborhunu.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.snrcjt.cn/Article/details/gt2ovkboeyq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yongpay.top/Article/details/gt2cgjcehha.html

[A24] 去除首尾空白
来源：http://dali.jqgufenzy.top/Article/details/gt2xtdwzywc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sweek.top/Article/details/gt2vvuikrmt.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2xqxvcfud.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yonumen.top/Article/details/gt2zvstyppl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gt2akdwgprd.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jianghu66.top/Article/details/gt2vneieamj.html

Go:   strings.TrimSpace(s)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jroqhugl.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gt2ewewngqk.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhixingplan.top/Article/details/gt2kcautmfs.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2czxlxymk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2akjlslsl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2nklplkfp.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2lapmcycl.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2ahtukqrc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gt2jxeilfkg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sufxvd.cn/Article/details/gt2vjkeyyss.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gt2etirqxsa.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gt2ghpbgygs.html

[A26] 类型转换总览
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xfrgkqtf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gt2gkypbstf.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ehwqpu.com/Article/details/gt2nmulordd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ybcxt.top/Article/details/gt2gbkqgsln.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gt2pecuxarn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gt2twgjgqdv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2omyerujp.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zycfv.cn/Article/details/gt2dxqbfcqo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2kslxmtgr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2ipeljzvr.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gt2leelnarv.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2fzrielfz.html

[B01] 条件判断 if / else
来源：http://dali.havefunace.top/Article/details/gt2jdasojix.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gt2vjqbmmmp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gt2ninxtgfe.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gt2cftomqyu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2sbkrgtnc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2xenqfzve.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.vqdsnc.cn/Article/details/gt2rvbgoxhf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gt2ozwklkql.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwasxjqu.html

[B02] 多分支 else if / elif
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tdhlfteh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.daxiang520.top/Article/details/gt2vmtcqpra.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yuxming.cn/Article/details/gt2fonqaogg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gt2qjajdkjv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gt2plccptvu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2iwlyshdd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zycfv.cn/Article/details/gt2bcqxvqyi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gt2dqpxbukk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnqzz.top/Article/details/gt2armtqzpc.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gt2ufqraedl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhoulong.xyz/Article/details/gt2zpztcxqz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2aeboocbt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2ilprxpfw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2qzjzhgbb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tvzwxqfe.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2vqttveiy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gt2opbpubtw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gt2lytaxqfo.html

[B04] for 计数循环
来源：http://dali.jiagoushi.top/Article/details/gt2kccianlq.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gt2hwqcnyfk.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgufenzy.top/Article/details/gt2iaoqjylw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2kwrqgppj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shuidangran.top/Article/details/gt2xtebeutq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gt2krshgvab.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gt2oncstdyk.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenjidiqi.icu/Article/details/gt2czxmxrdf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2axoexhtx.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2oknlzabd.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gt2gyietkcy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gt2usbdgktk.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gt2omtxxkws.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.smart0.xyz/Article/details/gt2ieuvwwdr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2qdddzbzd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.svipenyu.cn/Article/details/gt2itbvqpfj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gt2bsusihvh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pycfn.com/Article/details/gt2afuzxikn.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigfzy.top/Article/details/gt2uezlzwdj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bayvwthv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ydzc1.top/Article/details/gt2nkttpedp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guowangkeji.top/Article/details/gt2wucjvkjg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gt2bqbnrzgz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sysykeji.top/Article/details/gt2uybmbixm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.vqdsnc.cn/Article/details/gt2esccrpjz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.fengsongda.top/Article/details/gt2mckkupqs.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.quarkkingdee.top/Article/details/gt2flllgyoa.html

[B07] while 循环
来源：http://dali.fengsongda.top/Article/details/gt2lclnuoav.html

Py:   while i < 10: i += 1
来源：http://dali.shzxlz.cn/Article/details/gt2fnubvkpr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sufxvd.cn/Article/details/gt2ftglscwk.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2pcbvwcgb.html

TS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2kgkgjjte.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gt2tkhdyhsi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hammf.cn/Article/details/gt2dmdkvdbn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gt2xslawyfe.html

C#:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gt2fzzhyehv.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gt2lnhumbnw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jianghu66.top/Article/details/gt2rfuflcrn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2dystuqvn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gt2baupyixt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gt2bygwabnu.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2rvxcontk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2afawbrzk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gt2wscmxaks.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2ndbwoflm.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gt2vdauqgmy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gt2kzepbnwq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gt2yoyyyqzg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gt2datwoyev.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2qarcuqie.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztttvtdh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gt2ouupxwag.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.mhx1999.top/Article/details/gt2phnkzklg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gt2pvpqolme.html

[B10] 遍历同时拿索引
来源：http://dali.tanke756.top/Article/details/gt2yisnhtgn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gt2lrnoneph.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gt2jhmwebav.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gt2rgmlrlnb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gt2uvuhzncb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gt2wjvkcjmj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gt2ersnpswc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gt2gesxazti.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jianghu66.top/Article/details/gt2rjdzgovh.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gt2wvcubcgk.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vtenjply.html

PHP:  range(0, 10, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2kcxrbbsj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2dgvbscfs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2fbcgougz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jnuwcnyd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gt2ndizcooa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gzhubu.top/Article/details/gt2txdtxirf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ybcxt.top/Article/details/gt2rzmojrcg.html

[B12] 跳出多层循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ppvwbgbf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gt2hivxendc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gt2gwckupbk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2srputkzz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2fehbtrbt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2yrntlqpe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gt2wiwolbuu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.bjfxy.top/Article/details/gt2leegzmav.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gt2edwcdokl.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gt2mkvtjycv.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gt2gwuyyzwe.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gt2plevufbi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2ribqnjmv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2vwxcqmjk.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gt2qowhzrag.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tjiesywd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigufen.top/Article/details/gt2cvhescez.html

C#:   x is int or double or decimal
来源：http://dali.birdmap.top/Article/details/gt2gopxvzde.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2fxokgqoc.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gt2ozntvlpd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gt2rvrjmpqu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gt2fltqtbrq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2pkkrrebn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2ctrtjpou.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gt2rvkqynkx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gt2pmbxzbta.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gt2hmmmwadj.html

[B15] 布尔运算与取反
来源：http://dali.hnqzz.top/Article/details/gt2mdxcdqpy.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eirvjiyl.html


<!-- 参考信息 -->