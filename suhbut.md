代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.hongshengwenyu.top/Article/details/gt2cnqupvhl.html

JS:   `Hello, ${name}!`
来源：http://dali.bjfxy.top/Article/details/gt2bsfkhjqg.html

TS:   `Hello, ${name}!`
来源：http://dali.chenjidiqi.icu/Article/details/gt2hoguaiyr.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.kuanghao11.cn/Article/details/gt2wzvrdrnj.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.bjfxy.top/Article/details/gt2musecllo.html

Ruby: "Hello, #{name}!"
来源：http://dali.havefunace.top/Article/details/gt2ujrqjszp.html

C#:   $"Hello, {name}!"
来源：http://dali.tanke756.top/Article/details/gt2gcgapkgi.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.chenjidiqi.icu/Article/details/gt2fshgkyro.html

Py:   "第一行\n第二行"
来源：http://dali.tianlin.xyz/Article/details/gt2lcwsmlpv.html

PHP:  "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2urgcnyvp.html

JS:   "第一行\n第二行"
来源：http://dali.0kj1m.cn/Article/details/gt2etpskdai.html

TS:   "第一行\n第二行"
来源：http://dali.9152youxi.cn/Article/details/gt2hjswjdkl.html

Java: "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2jscqzfia.html

Go:   "第一行\n第二行"
来源：http://dali.hongshengwenyu.top/Article/details/gt2uuzjrrbr.html

Ruby: "第一行\n第二行"
来源：http://dali.tanke756.top/Article/details/gt2buaabwhh.html

C#:   "第一行\n第二行"
来源：http://dali.hammf.cn/Article/details/gt2sghqaqeo.html

[A14] 注释写法
来源：http://dali.ivvv.top/Article/details/gt2sekvtims.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.haohaochexian.top/Article/details/gt2kbghmtpn.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.sysykeji.top/Article/details/gt2fhjigptq.html

JS:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2ztaomwmy.html

TS:   // 单行；/* 多行 */
来源：http://dali.aibaodan.cn/Article/details/gt2wlfclrrs.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.guowangkeji.top/Article/details/gt2oadusstg.html

Go:   // 单行；/* 多行 */
来源：http://dali.ybcxt.top/Article/details/gt2lnumwldx.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.yuanzhike.top/Article/details/gt2wclremhj.html

C#:   // 单行；/* 多行 */
来源：http://dali.hnqzz.top/Article/details/gt2rfpbmvow.html

[A15] 空值判断与默认值
来源：http://dali.snrcjt.cn/Article/details/gt2wqxuicdi.html

Py:   value = data or "默认值"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zjjtdvel.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gt2ommkeljq.html

JS:   const value = data ?? "默认值";
来源：http://dali.xziqi.cn/Article/details/gt2nfcyyxng.html

TS:   const value = data ?? "默认值";
来源：http://dali.yanxiufei.cn/Article/details/gt2kajqxrrn.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.haohaochexian.top/Article/details/gt2rdifywti.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.nanxuanxn.top/Article/details/gt2maiehlpq.html

Ruby: value = data || "默认值"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pppktoku.html

C#:   var value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gt2fzbudcwl.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gt2wbdyidjd.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.hongshengwenyu.top/Article/details/gt2xsoepzvt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gt2voitmnak.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.xziqi.cn/Article/details/gt2rwjbleex.html

TS:   if (!x) {}
来源：http://dali.sxryk.cn/Article/details/gt2cfnmiecw.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2scscjrxk.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ybcxt.top/Article/details/gt2tafvonwt.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.dashuyun.cn/Article/details/gt2gufuqzgx.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cdnleiting.top/Article/details/gt2ualsqeqq.html

[A17] 位运算
来源：http://dali.svipenyu.cn/Article/details/gt2fnvvywui.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gt2kiobgscc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yongpay.top/Article/details/gt2ojqqidhe.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gt2alsqxxbv.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gt2ocfcjjab.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.haohaochexian.top/Article/details/gt2eqchozqz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.wangdashe.top/Article/details/gt2brfbenne.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gt2gmszgcox.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gt2zfefofez.html

[A18] 字符与 ASCII 码互转
来源：http://dali.zhongyouzk.top/Article/details/gt2yqwpbqjx.html

Py:   ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gt2mpdzwphm.html

PHP:  ord("A"); chr(65)
来源：http://dali.sweek.top/Article/details/gt2qzpqmbao.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gt2ntgioubq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gt2ftuufitp.html

Java: (int) 'A'; (char) 65
来源：http://dali.yueranfly.top/Article/details/gt2kqegywmj.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.svipenyu.cn/Article/details/gt2jzbvxqpn.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gt2jfrbzgkh.html

C#:   (int)'A'; (char)65
来源：http://dali.cucudq.cn/Article/details/gt2qyqvkyak.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukunmckv.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2faviikmh.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gt2mcyblghe.html

JS:   [a, b] = [b, a];
来源：http://dali.hammf.cn/Article/details/gt2hltmbcgb.html

TS:   [a, b] = [b, a];
来源：http://dali.daxiang520.top/Article/details/gt2fnhuwqfy.html

Java: int t = a; a = b; b = t;
来源：http://dali.hysaishi.cn/Article/details/gt2jajkeluc.html

Go:   a, b = b, a
来源：http://dali.zhengqikj.top/Article/details/gt2dnjbqvkp.html

Ruby: a, b = b, a
来源：http://dali.ppjwa.cn/Article/details/gt2ytywrkxf.html

C#:   (a, b) = (b, a);
来源：http://dali.gogol.net.cn/Article/details/gt2fuwvqaqy.html

[A20] 读取标准输入
来源：http://dali.dianchejie.cn/Article/details/gt2frlezfae.html

Py:   name = input("请输入：")
来源：http://dali.yuxming.cn/Article/details/gt2jatysryu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ydzc1.top/Article/details/gt2fznaqhqi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cheryme.top/Article/details/gt2zjyskbph.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gt2wrjjiapz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.zhixingplan.top/Article/details/gt2jumkadzj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gt2nomlfyis.html

Ruby: gets.chomp
来源：http://dali.xuetiantiany.cn/Article/details/gt2wssulttw.html

C#:   Console.ReadLine();
来源：http://dali.jianghu66.top/Article/details/gt2ffsotvxf.html

[A21] 保留指定小数位输出
来源：http://dali.iojbl.cn/Article/details/gt2gsqbordh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gt2omjinjfq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gt2pytonmjb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.wangdashe.top/Article/details/gt2jdyggfbl.html

TS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gt2zdgoguzp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gt2zxahkrzi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.316326.xyz/Article/details/gt2yjmogxmt.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gt2uydofydq.html

C#:   3.14159.ToString("F2")
来源：http://dali.bjfxy.top/Article/details/gt2ndxphpxo.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gt2tqtdltge.html

Py:   len(s)
来源：http://dali.316326.xyz/Article/details/gt2rnuqnhiw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hywenlv.cn/Article/details/gt2dtjubwrf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zycfv.cn/Article/details/gt2qtuqdxqj.html

TS:   s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tdexagan.html

Java: s.length()
来源：http://dali.c1oappe.top/Article/details/gt2jcklivdp.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jsdbphin.html

Ruby: s.length
来源：http://dali.daria6918.cn/Article/details/gt2cmuwezls.html

C#:   s.Length
来源：http://dali.zdqjudy.top/Article/details/gt2vwsgamzv.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gt2ynfyzqng.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.nwbrower.top/Article/details/gt2exefuymt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gt2rurlzdnp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gt2xfwqttbi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jiagoushi.top/Article/details/gt2ctisayex.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2knmmuzph.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.andypj.xyz/Article/details/gt2ingdxwys.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gt2ianvrhmg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.aibaodan.cn/Article/details/gt2wlewneao.html

[A24] 去除首尾空白
来源：http://dali.shangyingyoupin.top/Article/details/gt2nfsxsucm.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.c1oappe.top/Article/details/gt2cvuubqdl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.redwolf501.top/Article/details/gt2dseyeudx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2tmadrjcl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gt2sxfragpt.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gt2nxpmfikg.html

Go:   strings.TrimSpace(s)
来源：http://dali.aizwys.cn/Article/details/gt2rvyuxyxa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhiwuduotai.top/Article/details/gt2ackpaghb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.iojbl.cn/Article/details/gt2qaucacpa.html

[A25] 字符串比较
来源：http://dali.jyoumei.cn/Article/details/gt2erdfppcc.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yuanzhike.top/Article/details/gt2gkvywmcb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cucudq.cn/Article/details/gt2qhoylgqd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shzxlz.cn/Article/details/gt2zpqtntjb.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigufen.top/Article/details/gt2zeguxpua.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangdashe.top/Article/details/gt2uubbcwku.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2frcxqrnf.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.vqdsnc.cn/Article/details/gt2pnricxcb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gt2xogcvboa.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gt2ewidorge.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.dashuyun.cn/Article/details/gt2uhsdrsoz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jqgufenzy.top/Article/details/gt2cnmqgoxe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yueranfly.top/Article/details/gt2zpvuaokk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yongpay.top/Article/details/gt2ptgnasnv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdaakxwh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yj20258.top/Article/details/gt2ryziprtn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gt2dkzaynmu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cucudq.cn/Article/details/gt2dzasqjts.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2iwhzhpob.html

B. 流程控制
来源：http://dali.yj20258888.top/Article/details/gt2unghvdnk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2npcaonjm.html

[B01] 条件判断 if / else
来源：http://dali.cashguo.top/Article/details/gt2ayndbviz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jlsjyb.cn/Article/details/gt2dlwuamyr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gt2uroehleo.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rsbxedan.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gt2ipjwskfg.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gt2htpzxzwz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.redwolf501.top/Article/details/gt2phpmscss.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenzaomai.com/Article/details/gt2ybzopied.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gt2fgivrrxh.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gt2papvzzyz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gt2azdojfvr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gt2aybjnopc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gt2eubzrbst.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2ykmbonzd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2kjyeelob.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2qlgjooaz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gt2sszmutfr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gt2qfthxxmy.html

[B03] switch / match / case
来源：http://dali.zhiwuduotai.top/Article/details/gt2cnlmlcrn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gt2ssgvrwtz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pudkoldn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gt2gjppfmma.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2safyenzl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2smgrltcg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gt2owipgmyb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gt2dbokmjnh.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gt2behsvavo.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gt2nijgucug.html

Py:   for i in range(10): print(i)
来源：http://dali.guowangkeji.top/Article/details/gt2wshhebqo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.daria6918.cn/Article/details/gt2pcnawnvt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dashuyun.cn/Article/details/gt2mioozjli.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.316326.xyz/Article/details/gt2ukqawlme.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tianlin.xyz/Article/details/gt2zfjjnwcy.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.svipenyu.cn/Article/details/gt2xsgriuht.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gt2tvnefzrv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ybcxt.top/Article/details/gt2nlyjsywi.html

[B05] 遍历数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2zjypxiru.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gt2pzwstmpq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vqfmlfyn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qfstnimt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2vsfekbcz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yueranfly.top/Article/details/gt2blaftudv.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cqqwz.cn/Article/details/gt2sjywctzg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.aibaodan.cn/Article/details/gt2sdeuigif.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cdnleiting.top/Article/details/gt2skcpoowp.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gt2eifvhxnk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ehwqpu.com/Article/details/gt2mdglelwo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fengsongda.top/Article/details/gt2vorcdgjj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2arklivjk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gt2dsmqelrv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2urtwuxmz.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hysaishi.cn/Article/details/gt2zsmeevms.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gt2mdkvtldi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.0kj1m.cn/Article/details/gt2qvpanoay.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gt2dgcwrokz.html

Py:   while i < 10: i += 1
来源：http://dali.iojbl.cn/Article/details/gt2fgaminie.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2frvmonly.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhoulong.xyz/Article/details/gt2qvwnmaef.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gt2anjcvbbs.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2tozbqnkq.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.snrcjt.cn/Article/details/gt2wapznmkd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gt2qcfkdipp.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqwmuvky.html

[B08] do-while（至少执行一次）
来源：http://dali.jiagoushi.top/Article/details/gt2lhxrqvii.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cucudq.cn/Article/details/gt2olbhinnu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2kzkajnzd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gt2tdrjrsuq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gt2ugolrohz.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gt2aljupelm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sysykeji.top/Article/details/gt2wpagtdth.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtbqtcfp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2abiwsppu.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gt2tnnxhaab.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gt2yvpynypv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2kkwrmthl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gt2ohbwfkcj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2uamaqdfi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2cgfqpwxk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gt2jblalyhh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2munmnbjm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2fibelsjt.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gt2gmkvltmw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gt2lwoobcos.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2gvucatyw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gt2kxdzqrkm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gt2uvmwclbp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gt2ihzpvlvk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gt2stalazzs.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gt2qydzmlqt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gt2mwpoxqhn.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxinkj.top/Article/details/gt2qnrkfbso.html

Py:   list(range(0, 10, 2))
来源：http://dali.xylfe.cn/Article/details/gt2quqghwwg.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2ggceilyz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hywenlv.cn/Article/details/gt2ebhcidfx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gt2qrrxrmue.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gt2jvmksunr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2lviorwtm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gt2kflwhdgn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sweek.top/Article/details/gt2queolqes.html

[B12] 跳出多层循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2mjasxqmd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2pyoekiyq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.0kj1m.cn/Article/details/gt2hbxmwgfv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2bkuvpwrm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gt2xioedalb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2hdiioyhq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.havefunace.top/Article/details/gt2qxmrhnie.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgfzy.top/Article/details/gt2bwvxiugp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gt2xeaonhbi.html

[B13] 判断是否为数字
来源：http://dali.0kj1m.cn/Article/details/gt2nziltuxk.html

Py:   isinstance(x, (int, float))
来源：http://dali.yvedp.cn/Article/details/gt2ogpcuzgo.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gt2wzbokxoy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2iayburhb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gt2gnlratst.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gt2xdrnsxyt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gt2ijeuanyp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.dianchejie.cn/Article/details/gt2pmxnfnoq.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gt2xmmqcipx.html

[B14] 判断值是否在集合内
来源：http://dali.cqqwz.cn/Article/details/gt2ygzhwgbe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gt2beizmdcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gt2oiteorlt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2znmfvwjs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gt2fdyqpjqx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2sydpqcoa.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sweek.top/Article/details/gt2fbivtqoj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gt2qqjiddcd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gt2usvoqarz.html

[B15] 布尔运算与取反
来源：http://dali.yuxming.cn/Article/details/gt2xoczxrhm.html

Py:   a and b or not c
来源：http://dali.nanxinkj.top/Article/details/gt2acdevtpe.html

PHP:  $a && $b || !$c
来源：http://dali.cheryme.top/Article/details/gt2rotpkdob.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gt2wlkgaubz.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2gmsyqakc.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2yrtiroen.html

Go:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gt2hyklnrxn.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gt2switelvb.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2ljduinmz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gt2yjicatpn.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gt2crbsgzfb.html

PHP:  if (!$data) { return; }
来源：http://dali.zdqjudy.top/Article/details/gt2jjvsrnzr.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2zasjjbjj.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gt2sjacczae.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gt2oruuznnm.html

Go:   if data == nil { return }
来源：http://dali.chenzaomai.com/Article/details/gt2ugbsyiwk.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gt2judxgyhy.html

C#:   if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2cwthurze.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2djnenbbt.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gt2qkeayjpc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2awpgzwyw.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gt2zlwevxts.html

Py:   def add(a, b): return a + b
来源：http://dali.sysykeji.top/Article/details/gt2brodumob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gt2ywiqqyfh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2irudwjab.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2lkslhcgv.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2yhrsocdb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhengqikj.top/Article/details/gt2rqehmjzt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gt2mkgijwkd.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gt2axpxkynd.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gt2gpqeeylu.html

Py:   def greet(name="World"): return name
来源：http://dali.jqgufenzy.top/Article/details/gt2ienwvmct.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xyipxrkq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gt2ybcoaucp.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gt2mbgfpcaf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gt2yfwjtjld.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.daria6918.cn/Article/details/gt2iicqaium.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhoulong.xyz/Article/details/gt2mujgagdx.html


<!-- 参考信息 -->