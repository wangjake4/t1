代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xuetiantiany.cn/Article/details/gtoemhhije.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtgqfsdyjs.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmcjqdwl.html

[A17] 位运算
来源：http://dali.yuanzhike.top/Article/details/gtwrpneouj.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtwiuckqiu.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ehwqpu.com/Article/details/gtctivlgtd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtjtsxtxos.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtgtkckswb.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gttqwcfsfg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtpfrrszxn.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtdmcwfyxm.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtzdbvghtr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.tian-w.cn/Article/details/gtlwzdcyjp.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gtxmekqupq.html

PHP:  ord("A"); chr(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcfpcmaes.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ehwqpu.com/Article/details/gtqqabmogm.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gtklpzingq.html

Java: (int) 'A'; (char) 65
来源：http://dali.vqdsnc.cn/Article/details/gtqewogoto.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.c1oappe.top/Article/details/gtighiojiz.html

Ruby: "A".ord; 65.chr
来源：http://dali.jianghu66.top/Article/details/gtbrpsxyou.html

C#:   (int)'A'; (char)65
来源：http://dali.cheryme.top/Article/details/gtjrzmzyuu.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gtyguqvvbe.html

Py:   a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtgffwxszq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.jqgufenzy.top/Article/details/gtcngkbldj.html

JS:   [a, b] = [b, a];
来源：http://dali.yj202588.top/Article/details/gtobegbyqn.html

TS:   [a, b] = [b, a];
来源：http://dali.hysaishi.cn/Article/details/gtcxhcvjhi.html

Java: int t = a; a = b; b = t;
来源：http://dali.shanyushiyangtech.top/Article/details/gtgijmwkzb.html

Go:   a, b = b, a
来源：http://dali.yonumen.top/Article/details/gtvqdhjiao.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtnvfmjipr.html

C#:   (a, b) = (b, a);
来源：http://dali.andypj.xyz/Article/details/gtqlwpzswe.html

[A20] 读取标准输入
来源：http://dali.nanxinkj.top/Article/details/gtomxtymqz.html

Py:   name = input("请输入：")
来源：http://dali.tanke756.top/Article/details/gtqumoawgk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gotoacloud.top/Article/details/gtgbtfpvfa.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sxryk.cn/Article/details/gtjmwhcoat.html

TS:   // Node.js：readline 模块
来源：http://dali.yuxming.cn/Article/details/gtazufsyxw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.dashuyun.cn/Article/details/gtxqbtwals.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gaohongyu789.top/Article/details/gtpxlpcabx.html

Ruby: gets.chomp
来源：http://dali.jinqigufen.top/Article/details/gtuyvtmdlk.html

C#:   Console.ReadLine();
来源：http://dali.xuanzx.com/Article/details/gtitjcobzy.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtktmaccdk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hammf.cn/Article/details/gthxbhnwyl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtmcuftfdz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.smart0.xyz/Article/details/gtcsileleo.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqmijlrdd.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtvkjompbs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jianghu66.top/Article/details/gtjhcdsdqw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtwvovkqot.html

C#:   3.14159.ToString("F2")
来源：http://dali.daria6918.cn/Article/details/gtbsyovkql.html

[A22] 获取字符串长度
来源：http://dali.tanke756.top/Article/details/gtyhsvilxi.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtqqduytey.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jqgfzy.top/Article/details/gtwppynvxs.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gtbgmchrkt.html

TS:   s.length
来源：http://dali.dashuyun.cn/Article/details/gtuzbfrfee.html

Java: s.length()
来源：http://dali.ydzc1.top/Article/details/gtrtnhvksm.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.fengsongda.top/Article/details/gtoyiksiiq.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtqxgfjrud.html

C#:   s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtlunxodwu.html

[A23] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gtxfovqwfz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtdjovpvpy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jlsjyb.cn/Article/details/gtpmmtxyzt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.quarkkingdee.top/Article/details/gtcisbkxgz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtobgkdyve.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gtdfmdkhty.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gzhubu.top/Article/details/gtauaejuft.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.wangdashe.top/Article/details/gtwuktfykx.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gtamdipxms.html

[A24] 去除首尾空白
来源：http://dali.cucudq.cn/Article/details/gtkolmiouf.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gtcrpdsnbv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.feifeiyinyue.top/Article/details/gttqagzykl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.birdmap.top/Article/details/gtlgwxzdoo.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtmcyoeagi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.chenjidiqi.icu/Article/details/gtjrhxdkgf.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxuanxn.top/Article/details/gtrfpkxvxm.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zhijiandao.cn/Article/details/gtlgkfgybj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xuanzx.com/Article/details/gttcgvvblo.html

[A25] 字符串比较
来源：http://dali.jlsjyb.cn/Article/details/gteqnkwfcn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.smart0.xyz/Article/details/gtkznlphrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtrrjmcjth.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gtzxfbwtbr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xuanzx.com/Article/details/gtkhcxgfuh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtuqarmfhp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtqfanamoh.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhijiandao.cn/Article/details/gtfqguhzyz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gtowumcbrp.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtggcqmukl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gtzprdjona.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxmzcttx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangshuangyany.cn/Article/details/gtszijzegq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aizwys.cn/Article/details/gtgbzyzgos.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gteshxnsuz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtioxkyqnu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gtokfhcfrx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcltrlgtw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gththbgkft.html

B. 流程控制
来源：http://dali.cheryme.top/Article/details/gtjfeenipc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkhvzhkk.html

[B01] 条件判断 if / else
来源：http://dali.jlsjyb.cn/Article/details/gtteaibpad.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhongyouzk.top/Article/details/gtydqoyolu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gtuthaxyob.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhdgwwps.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtuwgrjqtj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtqimkxbzr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shuidangran.top/Article/details/gtdqlprnpd.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gtgkbyithn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtepufmvcw.html

[B02] 多分支 else if / elif
来源：http://dali.wangshuangyany.cn/Article/details/gtmkdcjlcr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guannengcc.top/Article/details/gtatntpglx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoincedx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtxthraflg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtlxjyipgw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtamjgoylj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jinqigufen.top/Article/details/gtrdcpxtxz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.cucudq.cn/Article/details/gtgykozvus.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtfcwethuf.html

[B03] switch / match / case
来源：http://dali.zdqjudy.top/Article/details/gtuwjkuwib.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gtcezwlrxn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtfqxrredc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guowangkeji.top/Article/details/gtcojycvdc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtjvrvxknx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtxjhvtswt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtewdlgikk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gtkhwhltkg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jianghu66.top/Article/details/gtmtfecsrq.html

[B04] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtsmsbhaqs.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gtojvyhcys.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtcqcxxxyx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtczcbaprt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtnaufnutp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gtmucnooji.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtfunogyew.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yj20258.top/Article/details/gtudqvmtgn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gtrysvuazq.html

[B05] 遍历数组 / 列表
来源：http://dali.yongpay.top/Article/details/gtybcbeezi.html

Py:   for item in arr: print(item)
来源：http://dali.cucudq.cn/Article/details/gtwfhcthjk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gtfaanjxvx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gttgbpsroz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtlffiajxk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dashuyun.cn/Article/details/gtwiistxqz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtmnrasems.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuxming.cn/Article/details/gtxtnmtggb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gtpmjlolgq.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtbdunuqwi.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.fzhhl.top/Article/details/gtktfqgsce.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtnlxewpgm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtellzcypt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtcfikaqco.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhongyouzk.top/Article/details/gttjtkjgop.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dianchejie.cn/Article/details/gtevxhzazk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gtyqimbqhw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtgdlmrtym.html

[B07] while 循环
来源：http://dali.ybcxt.top/Article/details/gtjvjsemln.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtevruwkjw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtxsfdfuij.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtrpfvpbcq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmwmuvwwc.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtklqcjriw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gtohpmbqeo.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuetiantiany.cn/Article/details/gtzzarmffy.html

C#:   while (i < 10) { i++; }
来源：http://dali.pengpengdd.cyou/Article/details/gttweyyzvh.html

[B08] do-while（至少执行一次）
来源：http://dali.jqgfzy.top/Article/details/gtobqoyjrt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtlmrxjslx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtklpobffy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtzkeixuve.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtqekgfwjp.html

Java: do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtfzmsgick.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fengsongda.top/Article/details/gtzhooplvw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gtjasmhzqt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtyniiphjr.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtrobibtah.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.iojbl.cn/Article/details/gtyzwiispn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtdnxkbmbe.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtefcvleil.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtawpgomrh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtjpqslnnv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jqgufenzy.top/Article/details/gtehqcjslb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtpjtlwvdq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtgcnszhpf.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gtqyajrgkd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pengpengdd.cyou/Article/details/gtlaoouhsx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtohplgrwk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtadmrjrvc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzndmdon.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gteinbnjus.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.iojbl.cn/Article/details/gttcgsngdp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gtlmelixqd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtrojzdibt.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtciynfuxf.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gtnvfnfzai.html

PHP:  range(0, 10, 2);
来源：http://dali.daria6918.cn/Article/details/gtsjqtnkte.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtaakygjsk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtcnmzfzlh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tian-w.cn/Article/details/gtqckihvvu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinghuilouyu.cn/Article/details/gttynpmshp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gtgcaigoay.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtdjlofhyn.html

[B12] 跳出多层循环
来源：http://dali.zhiwuduotai.top/Article/details/gtzwpawjrl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tianlin.xyz/Article/details/gtekkmoeji.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgufenzy.top/Article/details/gtodcbkzdc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtvdhkbips.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtuuzkevtz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtmywbjwna.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.mhx1999.top/Article/details/gtibogwter.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gtkkscjsyo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtmrjsnahq.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtxnisnomw.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtuxsgxmah.html

PHP:  is_numeric($x)
来源：http://dali.yanxiufei.cn/Article/details/gtwwvfqqzi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jyoumei.cn/Article/details/gtnogwsury.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtzizvloqx.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gtpebvhdof.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.guannengcc.top/Article/details/gtjpnpusxb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtswxwbqaq.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gtjjfwsbfx.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtpbscrkkp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtfanuaebi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtmlkgaewt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtpsasipuo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtytluavde.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtccfimupi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbhcxjvhj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtignprwzw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtwcgfmcqd.html

[B15] 布尔运算与取反
来源：http://dali.ivvv.top/Article/details/gtyivhtnvr.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgzjkhudo.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtqxrqspzw.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtafmnffpy.html

TS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtxapmfpao.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtzegospvv.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtxqayhhwc.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkqvsgcjf.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gteoydoqcu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gthjjkosfh.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtmmpspdhu.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtoykuvbds.html

JS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtftjlvgyj.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gttfvsqccp.html

Java: if (data == null) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtcdopohbp.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtjketnzsf.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtyusqocct.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gtqatzjtaq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtdnlskhqz.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtuzwgjtar.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtglmngspv.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtihdtdpxt.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtdfzagnyr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenlongwang.top/Article/details/gthorlisnj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtzbnqhvtw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtaklrbocq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtxuuxrybz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtmcvgakgy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtqbcwtosu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtrjlvhpii.html

[C02] 默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtjfkoxyim.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gtgougaavl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtskcqztlo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtqilbfgyb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtvhxmnofv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shzxlz.cn/Article/details/gtujlsdnem.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gtbmjymrhf.html

Ruby: def greet(name = "World") = name
来源：http://dali.aibaodan.cn/Article/details/gttrjirbij.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.fengsongda.top/Article/details/gtezfpyqnv.html

[C03] 可变参数
来源：http://dali.zhiwuduotai.top/Article/details/gtfcudleva.html

Py:   def total(*args): return sum(args)
来源：http://dali.cashguo.top/Article/details/gtdhtcuejc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gtupzjlpvu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtotawvzjm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtkgjmrfjj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aibaodan.cn/Article/details/gtbnepipvq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ehwqpu.com/Article/details/gtfpwlckda.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.birdmap.top/Article/details/gtahpjqrqf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gthuofxysq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gthitvtijw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtogksyqmd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtlinsbxfv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtftdcwods.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hysaishi.cn/Article/details/gtxoicsrex.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtqcfcvjaj.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtftniicmu.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtlobrztfu.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtndpvisud.html

[C05] 返回多个值
来源：http://dali.jinqigfzy.top/Article/details/gtjigkeequ.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gtlxlpxxkc.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtqnlxsned.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.kuanghao11.cn/Article/details/gtvrzgejkn.html

TS:   return { a, b };
来源：http://dali.9152youxi.cn/Article/details/gtgwntwpun.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gtecbsushy.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gtvgbayxtt.html

Ruby: return a, b
来源：http://dali.zhixingplan.top/Article/details/gtjgruxqmd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zdqjudy.top/Article/details/gtwufjfanb.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtutkgejrr.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gttchtoccq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtmzdnnllb.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtasucqzvb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pycfn.com/Article/details/gtqckmqeti.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gteqorkhfc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gtzdhlgnyc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtgvmenykp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtkdupvpey.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gtglmmrvsz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gtnpcvedda.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmxrghez.html


<!-- 参考信息 -->