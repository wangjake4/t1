代发 wailian999

C#:   string name = "Alex"; int age = 20;
来源：http://dali.zhixingplan.top/Article/details/gt2zjitjgqm.html

[A03] 常量定义
来源：http://dali.sxryk.cn/Article/details/gt2nfiteryp.html

Py:   PI = 3.14159                       # 约定全大写，语言不强制
来源：http://dali.shuidangran.top/Article/details/gt2cxfkinoe.html

PHP:  const PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2inmuddrt.html

JS:   const PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gt2ooappzjk.html

TS:   const PI: number = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2wbdzuaqs.html

Java: static final double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahjfjmar.html

Go:   const PI = 3.14159
来源：http://dali.cqqwz.cn/Article/details/gt2yglevdnp.html

Ruby: PI = 3.14159
来源：http://dali.jlsjyb.cn/Article/details/gt2tjcfpzxe.html

C#:   const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gt2hgupemdg.html

[A04] 判断变量类型
来源：http://dali.pycfn.com/Article/details/gt2wcpnkpyp.html

Py:   type(x).__name__; isinstance(x, int)
来源：http://dali.cheryme.top/Article/details/gt2asahhbtd.html

PHP:  gettype($x); is_int($x); is_string($x)
来源：http://dali.gogol.net.cn/Article/details/gt2uggvblwt.html

JS:   typeof x; Array.isArray(x); x instanceof Date
来源：http://dali.wangshuangyany.cn/Article/details/gt2cncszeob.html

TS:   typeof x; x instanceof Date
来源：http://dali.kuanghao11.cn/Article/details/gt2oddrsjxu.html

Java: x.getClass().getSimpleName(); x instanceof String
来源：http://dali.dashuyun.cn/Article/details/gt2rmaxjqzf.html

Go:   reflect.TypeOf(x).Name()
来源：http://dali.0kj1m.cn/Article/details/gt2etoacnjj.html

Ruby: x.class; x.is_a?(Integer)
来源：http://dali.jianghu66.top/Article/details/gt2rrqawoko.html

C#:   x.GetType().Name; x is int
来源：http://dali.vqdsnc.cn/Article/details/gt2cvlygsma.html

[A05] 整数除法与取模
来源：http://dali.zhoulong.xyz/Article/details/gt2hkvfhnzl.html

Py:   7 // 2   # 3        7 % 2   # 1
来源：http://dali.ydzc1.top/Article/details/gt2yerktcqo.html

PHP:  intdiv(7, 2); 7 % 2
来源：http://dali.wangdashe.top/Article/details/gt2zgugvuun.html

JS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.redwolf501.top/Article/details/gt2frrtalju.html

TS:   Math.trunc(7 / 2); 7 % 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knbuwqrs.html

Java: 7 / 2; 7 % 2
来源：http://dali.cqqwz.cn/Article/details/gt2azypubqv.html

Go:   7 / 2; 7 % 2
来源：http://dali.chenlongwang.top/Article/details/gt2yxjzuhzo.html

Ruby: 7 / 2; 7 % 2
来源：http://dali.guannengcc.top/Article/details/gt2ctmzafow.html

C#:   7 / 2; 7 % 2
来源：http://dali.nanxinkj.top/Article/details/gt2snywcmzc.html

[A06] 字符串转数字
来源：http://dali.aizwys.cn/Article/details/gt2qfpzckef.html

Py:   int("42"); float("3.14")
来源：http://dali.9152youxi.cn/Article/details/gt2kunnitwr.html

PHP:  (int) "42"; (float) "3.14"; intval("42")
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwarpxbf.html

JS:   parseInt("42", 10); parseFloat("3.14"); Number("42")
来源：http://dali.iojbl.cn/Article/details/gt2trbtgwdr.html

TS:   parseInt("42", 10); Number("42")
来源：http://dali.havefunace.top/Article/details/gt2gzqgzgrt.html

Java: Integer.parseInt("42"); Double.parseDouble("3.14")
来源：http://dali.316326.xyz/Article/details/gt2pyvtseww.html

Go:   strconv.Atoi("42"); strconv.ParseFloat("3.14", 64)
来源：http://dali.smart0.xyz/Article/details/gt2utwqhvnj.html

Ruby: "42".to_i; "3.14".to_f
来源：http://dali.zycfv.cn/Article/details/gt2ioldhydr.html

C#:   int.Parse("42"); double.Parse("3.14")
来源：http://dali.cashguo.top/Article/details/gt2zrkvxrls.html

[A07] 数字转字符串
来源：http://dali.jinqigfzy.top/Article/details/gt2dzxdzoco.html

Py:   str(42)
来源：http://dali.shuidangran.top/Article/details/gt2jzofextw.html

PHP:  (string) 42; strval(42)
来源：http://dali.yvedp.cn/Article/details/gt2egypcadm.html

JS:   String(42); (42).toString()
来源：http://dali.yj20258888.top/Article/details/gt2oeryzybr.html

TS:   String(42)
来源：http://dali.nanxuanxn.top/Article/details/gt2mcninqdi.html

Java: String.valueOf(42); Integer.toString(42)
来源：http://dali.ppjwa.cn/Article/details/gt2dvqngine.html

Go:   strconv.Itoa(42)
来源：http://dali.zdqjudy.top/Article/details/gt2cnvxydwi.html

Ruby: 42.to_s
来源：http://dali.xylfe.cn/Article/details/gt2klpmapnk.html

C#:   42.ToString()
来源：http://dali.jianghu66.top/Article/details/gt2vfwgixho.html

[A08] 取整与四舍五入
来源：http://dali.daria6918.cn/Article/details/gt2scapdlue.html

Py:   round(3.567, 2); int(3.9); math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2kquofvmc.html

PHP:  round(3.567, 2); floor(3.9); ceil(3.1)
来源：http://dali.yuanzhike.top/Article/details/gt2biritlwa.html

JS:   Math.round(3.567 * 100) / 100; Math.floor(3.9)
来源：http://dali.meibo888.top/Article/details/gt2tmqlrhjv.html

TS:   Math.floor(3.9); Math.round(3.5)
来源：http://dali.yuxming.cn/Article/details/gt2pawihkzg.html

Java: Math.round(3.567); Math.floor(3.9)
来源：http://dali.cucudq.cn/Article/details/gt2glzvmdqk.html

Go:   math.Round(3.567); math.Floor(3.9)
来源：http://dali.haohaochexian.top/Article/details/gt2dnseufio.html

Ruby: 3.567.round(2); 3.9.floor
来源：http://dali.jinqigfzy.top/Article/details/gt2jsymagxq.html

C#:   Math.Round(3.567, 2); Math.Floor(3.9)
来源：http://dali.gzhubu.top/Article/details/gt2grtzzhyv.html

[A09] 绝对值与最大最小值
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywzkzfsv.html

Py:   abs(-5); max(1, 2); min(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2wuyhxvfs.html

PHP:  abs(-5); max(1, 2); min(1, 2)
来源：http://dali.cucudq.cn/Article/details/gt2wfciidod.html

JS:   Math.abs(-5); Math.max(1, 2); Math.min(1, 2)
来源：http://dali.shangyingyoupin.top/Article/details/gt2ioxjuept.html

TS:   Math.abs(-5); Math.max(1, 2)
来源：http://dali.mhx1999.top/Article/details/gt2doicgcty.html

Java: Math.abs(-5); Math.max(1, 2)
来源：http://dali.yj20258.top/Article/details/gt2ubqvvbeh.html

Go:   math.Abs(-5); max(1, 2)          // max/min 为 Go 1.21 内置
来源：http://dali.sweek.top/Article/details/gt2cjrlmtpu.html

Ruby: -5.abs; [1, 2].max; [1, 2].min
来源：http://dali.birdmap.top/Article/details/gt2assbnfwn.html

C#:   Math.Abs(-5); Math.Max(1, 2)
来源：http://dali.yongpay.top/Article/details/gt2jqbmfony.html

[A10] 生成随机数
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqwlvrnh.html

Py:   import random; random.randint(1, 100)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ylinikwh.html

PHP:  random_int(1, 100);
来源：http://dali.jinqigufen.top/Article/details/gt2nkobgzva.html

JS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.yonumen.top/Article/details/gt2ldtzemvy.html

TS:   Math.floor(Math.random() * 100) + 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nwgennyo.html

Java: new Random().nextInt(100) + 1
来源：http://dali.ivvv.top/Article/details/gt2fdxvqncd.html

Go:   rand.Intn(100) + 1               // math/rand
来源：http://dali.gogol.net.cn/Article/details/gt2yrhdhabx.html

Ruby: rand(1..100)
来源：http://dali.guowangkeji.top/Article/details/gt2axiweyig.html

C#:   new Random().Next(1, 101)
来源：http://dali.daxiang520.top/Article/details/gt2tnbowukb.html

[A11] 条件表达式（三元）
来源：http://dali.sufxvd.cn/Article/details/gt2cxmastuk.html

Py:   "yes" if x > 0 else "no"
来源：http://dali.zhengqikj.top/Article/details/gt2qgfookhb.html

PHP:  $x > 0 ? "yes" : "no"
来源：http://dali.zhixingplan.top/Article/details/gt2hjfmdwwd.html

JS:   x > 0 ? "yes" : "no"
来源：http://dali.yuxming.cn/Article/details/gt2ssbtndlw.html

TS:   x > 0 ? "yes" : "no"
来源：http://dali.hfpthk.cn/Article/details/gt2lelzgqxo.html

Java: x > 0 ? "yes" : "no"
来源：http://dali.smart0.xyz/Article/details/gt2rrftgihf.html

Go:   // 无三元运算符，需用 if 语句
来源：http://dali.jqgfzy.top/Article/details/gt2vtqgrlad.html

Ruby: x > 0 ? "yes" : "no"
来源：http://dali.andypj.xyz/Article/details/gt2svdayzol.html

C#:   x > 0 ? "yes" : "no"
来源：http://dali.iojbl.cn/Article/details/gt2vahveqhi.html

[A12] 字符串插值 / 格式化
来源：http://dali.c1oappe.top/Article/details/gt2hhrmaoyz.html

Py:   f"Hello, {name}! 年龄 {age}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xehkcnbu.html

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.gaohongyu789.top/Article/details/gt2tughdwmc.html

JS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gt2zzrwnkqa.html

TS:   `Hello, ${name}!`
来源：http://dali.yanxiufei.cn/Article/details/gt2oensjhtk.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.shuidangran.top/Article/details/gt2ydjqxdre.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sumkliff.html

Ruby: "Hello, #{name}!"
来源：http://dali.shuidangran.top/Article/details/gt2drbckdda.html

C#:   $"Hello, {name}!"
来源：http://dali.tian-w.cn/Article/details/gt2xirzboem.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.ybcxt.top/Article/details/gt2btocwbyf.html

Py:   "第一行\n第二行"
来源：http://dali.birdmap.top/Article/details/gt2ynteclwo.html

PHP:  "第一行\n第二行"
来源：http://dali.gogol.net.cn/Article/details/gt2qjetdmpq.html

JS:   "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gt2tjikkxkr.html

TS:   "第一行\n第二行"
来源：http://dali.hfpthk.cn/Article/details/gt2kreyybwv.html

Java: "第一行\n第二行"
来源：http://dali.daxiang520.top/Article/details/gt2itgyhcux.html

Go:   "第一行\n第二行"
来源：http://dali.hysaishi.cn/Article/details/gt2bntyqnau.html

Ruby: "第一行\n第二行"
来源：http://dali.sysykeji.top/Article/details/gt2vrbxacfs.html

C#:   "第一行\n第二行"
来源：http://dali.hnxiangtu.top/Article/details/gt2dscjzaws.html

[A14] 注释写法
来源：http://dali.aizwys.cn/Article/details/gt2zbsbsjst.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gt2hocxqrqi.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.guowangkeji.top/Article/details/gt2lkgbinkz.html

JS:   // 单行；/* 多行 */
来源：http://dali.gotoacloud.top/Article/details/gt2iutcxnql.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gt2sdcgouzp.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.kuanghao11.cn/Article/details/gt2dorfmfkx.html

Go:   // 单行；/* 多行 */
来源：http://dali.xuetiantiany.cn/Article/details/gt2ucokkvzi.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenjidiqi.icu/Article/details/gt2pgfhtzte.html

C#:   // 单行；/* 多行 */
来源：http://dali.ppjwa.cn/Article/details/gt2ucwqmbet.html

[A15] 空值判断与默认值
来源：http://dali.tian-w.cn/Article/details/gt2tzkxunbf.html

Py:   value = data or "默认值"
来源：http://dali.pengpengdd.cyou/Article/details/gt2ydrggvzj.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.cdnleiting.top/Article/details/gt2bzvdreio.html

JS:   const value = data ?? "默认值";
来源：http://dali.cheryme.top/Article/details/gt2thpaldbc.html

TS:   const value = data ?? "默认值";
来源：http://dali.fengsongda.top/Article/details/gt2gmfvqdku.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ivvv.top/Article/details/gt2yevbcglr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yonumen.top/Article/details/gt2sxzokapo.html

Ruby: value = data || "默认值"
来源：http://dali.ivvv.top/Article/details/gt2bgvrqtcq.html

C#:   var value = data ?? "默认值";
来源：http://dali.zhixingplan.top/Article/details/gt2cxwckzwe.html

[A16] 真假值判断规则
来源：http://dali.ybcxt.top/Article/details/gt2oheavsgo.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ydzc1.top/Article/details/gt2eoooreoa.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.jqgfzy.top/Article/details/gt2btxwpdig.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.cashguo.top/Article/details/gt2hqiqwbmc.html

TS:   if (!x) {}
来源：http://dali.yuxming.cn/Article/details/gt2lbcylgvb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gaohongyu789.top/Article/details/gt2bvtosdie.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.tian-w.cn/Article/details/gt2ulrtqoro.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuanzhike.top/Article/details/gt2wbpojyyl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aibaodan.cn/Article/details/gt2mrfepohm.html

[A17] 位运算
来源：http://dali.nanxuanxn.top/Article/details/gt2lalmdfyw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gt2utzsujbi.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2jmxjhxiu.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gt2kkyrmyzu.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gt2dvabspof.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yanxiufei.cn/Article/details/gt2qcwbeazl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gt2agjimdlm.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gt2kkvimqdy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guannengcc.top/Article/details/gt2nygwehmv.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gt2zconuyip.html

Py:   ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxycqnra.html

PHP:  ord("A"); chr(65)
来源：http://dali.shangyingyoupin.top/Article/details/gt2xneehsll.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.0kj1m.cn/Article/details/gt2uwdwyjdx.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.haohaochexian.top/Article/details/gt2wqqmsxgj.html

Java: (int) 'A'; (char) 65
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qotlbgwh.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gt2egaojfnu.html

Ruby: "A".ord; 65.chr
来源：http://dali.daxiang520.top/Article/details/gt2rcenaddu.html

C#:   (int)'A'; (char)65
来源：http://dali.gogol.net.cn/Article/details/gt2owdkdmde.html

[A19] 交换两个变量
来源：http://dali.jqgufenzy.top/Article/details/gt2fxpnamkc.html

Py:   a, b = b, a
来源：http://dali.smart0.xyz/Article/details/gt2ldvswpty.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.mhx1999.top/Article/details/gt2fsvbslbq.html

JS:   [a, b] = [b, a];
来源：http://dali.chenjidiqi.icu/Article/details/gt2aioasvtk.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvllasll.html

Java: int t = a; a = b; b = t;
来源：http://dali.dashuyun.cn/Article/details/gt2gizzznij.html

Go:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gt2wprrmqoa.html

Ruby: a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hkwbqqeh.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gt2mlivtqcb.html

[A20] 读取标准输入
来源：http://dali.dashuyun.cn/Article/details/gt2mexvtpml.html

Py:   name = input("请输入：")
来源：http://dali.zhongyouzk.top/Article/details/gt2nwaimfyp.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.guannengcc.top/Article/details/gt2nbzcifaz.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dianchejie.cn/Article/details/gt2pdtxhnvb.html

TS:   // Node.js：readline 模块
来源：http://dali.quarkkingdee.top/Article/details/gt2sqkywpqx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.pycfn.com/Article/details/gt2pdjsrfiq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gt2tgqyrutk.html

Ruby: gets.chomp
来源：http://dali.chenlongwang.top/Article/details/gt2euevuivz.html

C#:   Console.ReadLine();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xfhzdfjb.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gt2gyaqvckw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jqgfzy.top/Article/details/gt2nvjszwpc.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gt2atzengqe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2nwrcdmjf.html

TS:   (3.14159).toFixed(2)
来源：http://dali.dianchejie.cn/Article/details/gt2xpzofjht.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gt2qfbswbvo.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gt2gwwezyjv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vljzgpra.html

C#:   3.14159.ToString("F2")
来源：http://dali.quarkkingdee.top/Article/details/gt2jtmwwjfh.html

[A22] 获取字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gt2gubnoxib.html

Py:   len(s)
来源：http://dali.xuanzx.com/Article/details/gt2jopecxhk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gt2trshamzj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gt2rohzhvjy.html

TS:   s.length
来源：http://dali.0kj1m.cn/Article/details/gt2wqpykydz.html

Java: s.length()
来源：http://dali.pengpengdd.cyou/Article/details/gt2luonnlvt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gt2sfxftcyf.html

Ruby: s.length
来源：http://dali.hfpthk.cn/Article/details/gt2nqxsrdwd.html

C#:   s.Length
来源：http://dali.yuxming.cn/Article/details/gt2jybyokfq.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gt2szavdnca.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jqgufenzy.top/Article/details/gt2emojxqtm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gotoacloud.top/Article/details/gt2sdzuuvnt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2ikjnkwtl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.birdmap.top/Article/details/gt2fbsacpqd.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gt2fapxcetl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gt2nxkhvfcs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gt2kjwndmhj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zdqjudy.top/Article/details/gt2hkbawkoq.html

[A24] 去除首尾空白
来源：http://dali.gogol.net.cn/Article/details/gt2mnpybzav.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhengqikj.top/Article/details/gt2quzphkpi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.kuanghao11.cn/Article/details/gt2mjgmouks.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gt2owkaktdb.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gt2ktmfsrpe.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gt2tqfmjmpi.html

Go:   strings.TrimSpace(s)
来源：http://dali.redwolf501.top/Article/details/gt2ddomplit.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gt2rydcbktw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuxming.cn/Article/details/gt2wlnviuxv.html

[A25] 字符串比较
来源：http://dali.tian-w.cn/Article/details/gt2miqasizf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgfzy.top/Article/details/gt2qxlgsynl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.quarkkingdee.top/Article/details/gt2cgssxafm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gt2qmkaflck.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gt2ewyrmtpu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yangfankeji.com/Article/details/gt2ygrdwwlg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.svipenyu.cn/Article/details/gt2cfbvgwqx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ehwqpu.com/Article/details/gt2sjdvbeqh.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gt2dpbkahxr.html

[A26] 类型转换总览
来源：http://dali.redwolf501.top/Article/details/gt2cdihbcly.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aohnjhew.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hammf.cn/Article/details/gt2nwewjwvb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenjidiqi.icu/Article/details/gt2mxryjdos.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cucudq.cn/Article/details/gt2oytvqrok.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ydzc1.top/Article/details/gt2dygurqgx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rlmdybbx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhongyouzk.top/Article/details/gt2rinnsnjy.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2mbpzpbna.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2thknklxn.html

B. 流程控制
来源：http://dali.havefunace.top/Article/details/gt2zhbsowmk.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2xcdukyok.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gt2lupbdkjg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.316326.xyz/Article/details/gt2bolrilwm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2flxwvcxj.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2lmzixjsv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pycfn.com/Article/details/gt2lqtgtswb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gt2ftsjalhm.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guowangkeji.top/Article/details/gt2wkienlch.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zycfv.cn/Article/details/gt2duqthuje.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gt2iynbtalc.html

[B02] 多分支 else if / elif
来源：http://dali.shuidangran.top/Article/details/gt2vnvkoepw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.316326.xyz/Article/details/gt2vjnckcbz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gt2tzsevgxo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2jivnuqyi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2wxveqyht.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2kkagkouz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gt2aujvjjlr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gt2rlalcdww.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gt2xfgwmwuq.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gt2bsavqcha.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gt2ilwsvjce.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gogol.net.cn/Article/details/gt2drqbmfhz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fnpglwog.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhengqikj.top/Article/details/gt2mggqlqml.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2ffnlunjs.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uilsanpq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenjidiqi.icu/Article/details/gt2ppotjaid.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gt2jxbakfyv.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gt2dunjdorv.html

Py:   for i in range(10): print(i)
来源：http://dali.cheryme.top/Article/details/gt2efqdzzkg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hnqzz.top/Article/details/gt2tqqqsqnz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gt2qrqsparr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2aolgxcvw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2makonjok.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.fzhhl.top/Article/details/gt2bbliqyvr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gt2xbyyymum.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.wangdashe.top/Article/details/gt2hpkcjxkb.html

[B05] 遍历数组 / 列表
来源：http://dali.smart0.xyz/Article/details/gt2bbdlcsgy.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gt2jyhbdrxd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.meibo888.top/Article/details/gt2rhuurkir.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.birdmap.top/Article/details/gt2rgjlgsub.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2bdokumce.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gt2dcczpmxi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gt2vlibqaop.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hammf.cn/Article/details/gt2kkokrqqk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ehlydbmh.html

[B06] 遍历字典 / 对象
来源：http://dali.xziqi.cn/Article/details/gt2wljbksqk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ocljhfsy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gt2mqgiafvv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhixingplan.top/Article/details/gt2vbygvsaq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gt2eibwjgqe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gt2vmhddpae.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2cszipkkd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xylfe.cn/Article/details/gt2tfzyzgzr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj20258888.top/Article/details/gt2rrozjpsx.html

[B07] while 循环
来源：http://dali.gogol.net.cn/Article/details/gt2njlvkais.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gt2ywyagzjw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gt2dauwlnft.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2dgcjywxk.html

TS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2fjcvcjng.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2sugerckp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shuidangran.top/Article/details/gt2qychamll.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2geuxfqum.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2ufggkxxc.html

[B08] do-while（至少执行一次）
来源：http://dali.zhongyouzk.top/Article/details/gt2kgmdtgls.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.nwbrower.top/Article/details/gt2fasznxrt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pjbhkkki.html

JS:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2zbkrldpi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2qkwbksts.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2iwaaapsm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gt2qfbcohyq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.mhx1999.top/Article/details/gt2pngbrjav.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2bqptwuln.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gt2qqselrgt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sysykeji.top/Article/details/gt2pjhoworw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.sweek.top/Article/details/gt2umjvwlqj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2vjnvqunx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gt2tnfzmhdp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2gjbhaenw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gt2ctmbtqkc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigfzy.top/Article/details/gt2lznfqtei.html


<!-- 参考信息 -->