代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.sweek.top/Article/details/gtmkwpmktu.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gtveuahlpb.html

TS:   if (!x) {}
来源：http://dali.havefunace.top/Article/details/gtpdqllhks.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gaohongyu789.top/Article/details/gtmartiokq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtlixpxbvb.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.birdmap.top/Article/details/gtlbhovzpv.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.yj20258.top/Article/details/gtsrclxide.html

[A17] 位运算
来源：http://dali.dashuyun.cn/Article/details/gtbiprcykz.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtahhlozqo.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yj20258.top/Article/details/gtvpespwdq.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gttzrzudim.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gthpjqazih.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtbsvqcjcl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xinyue.icu/Article/details/gtnlrsrrai.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtfhopcitd.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gthcqswgqk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.daxiang520.top/Article/details/gtxwpkhlth.html

Py:   ord("A"); chr(65)
来源：http://dali.yonumen.top/Article/details/gtyntikwzz.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtjlkqlchd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtrgtgevto.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhijiandao.cn/Article/details/gtvuxjjjmi.html

Java: (int) 'A'; (char) 65
来源：http://dali.aibaodan.cn/Article/details/gtdeqzbfea.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yangfankeji.com/Article/details/gtefaczztu.html

Ruby: "A".ord; 65.chr
来源：http://dali.xuanzx.com/Article/details/gttkrefphj.html

C#:   (int)'A'; (char)65
来源：http://dali.jlsjyb.cn/Article/details/gtyrfndgvc.html

[A19] 交换两个变量
来源：http://dali.jinqigufen.top/Article/details/gtxpxlsvha.html

Py:   a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtqjlrfxov.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtbxgiibhk.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtuyiaukwo.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtuexgilkf.html

Java: int t = a; a = b; b = t;
来源：http://dali.pengpengdd.cyou/Article/details/gtmjqlnnfb.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gtewiyjivj.html

Ruby: a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gtckigrcax.html

C#:   (a, b) = (b, a);
来源：http://dali.tianlin.xyz/Article/details/gtfzhmjqtg.html

[A20] 读取标准输入
来源：http://dali.aibaodan.cn/Article/details/gtfxpmzlsu.html

Py:   name = input("请输入：")
来源：http://dali.sufxvd.cn/Article/details/gtxcnlloei.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.gotoacloud.top/Article/details/gtsrjimjyb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fzhhl.top/Article/details/gtigqxwtvm.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtcrrgynee.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gtopgxyacu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jqgfzy.top/Article/details/gtaagnjbnr.html

Ruby: gets.chomp
来源：http://dali.xziqi.cn/Article/details/gtseqyancp.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gtuswlcufn.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gtwbklphix.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gtqzoyqvnn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtijwijxis.html

JS:   (3.14159).toFixed(2)
来源：http://dali.c1oappe.top/Article/details/gtrhjmjnay.html

TS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtsknynwpu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gtqtnyqxqx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.havefunace.top/Article/details/gtciutqmsv.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gthjxdijid.html

C#:   3.14159.ToString("F2")
来源：http://dali.yvedp.cn/Article/details/gtygkcqysg.html

[A22] 获取字符串长度
来源：http://dali.daria6918.cn/Article/details/gtzfcrmgwx.html

Py:   len(s)
来源：http://dali.daria6918.cn/Article/details/gtxhsmlevr.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xinyue.icu/Article/details/gttxxzvnhy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xylfe.cn/Article/details/gtakbiapyi.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gtrqzlahzt.html

Java: s.length()
来源：http://dali.ybcxt.top/Article/details/gtrhedfnao.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gttidxweaj.html

Ruby: s.length
来源：http://dali.xuanzx.com/Article/details/gtstejofgj.html

C#:   s.Length
来源：http://dali.316326.xyz/Article/details/gtrdqrnpqo.html

[A23] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtcgwhkulf.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gtjdnfkxuc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.birdmap.top/Article/details/gtxcfuzpuz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtkwdwtynu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gtwwnyudne.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtwlpusqwe.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.havefunace.top/Article/details/gtvattgmce.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtnjofvafi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.guowangkeji.top/Article/details/gtpdkdsalx.html

[A24] 去除首尾空白
来源：http://dali.quarkkingdee.top/Article/details/gtjmslijik.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtbpotdmfz.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdewdemgm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtyeqxmshf.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtxjuevnpa.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gtyhctfvac.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhongyouzk.top/Article/details/gtmpfrlpfs.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.sufxvd.cn/Article/details/gtplxuqdzj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.daxiang520.top/Article/details/gtegdndvzb.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtgaqlxmtt.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigfzy.top/Article/details/gtgcorshyd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gtmzplzomn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gtaikznnmm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtxwzfbzif.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.dianchejie.cn/Article/details/gttxzcbaor.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtdoipwiac.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.fengsongda.top/Article/details/gtoixvzeku.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtgdcrbqwi.html

[A26] 类型转换总览
来源：http://dali.redwolf501.top/Article/details/gtichzweqw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xinyue.icu/Article/details/gtejibypjn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj202588.top/Article/details/gtsvtxnfzr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxinkj.top/Article/details/gtdhhvgoqa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.iojbl.cn/Article/details/gtaeunbces.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gthzldnqnu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hysaishi.cn/Article/details/gtfqyzcwvq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gtdgxgmdyn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yvedp.cn/Article/details/gtzeqlgwdz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtcascrghp.html

B. 流程控制
来源：http://dali.jianghu66.top/Article/details/gtofuubhpr.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtbspbzpal.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gtvcmaabdi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nwbrower.top/Article/details/gtbdpqejyb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gtpyyqwdue.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtumtasyza.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtujzntant.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtffxvmjze.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gtwbctzspa.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gtdguaffrv.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gtpiojiufn.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gtgftkjfjs.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtbfitnvbg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.aibaodan.cn/Article/details/gtruaqrpar.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtwhartycb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtaudmodli.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtgjlfxucn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sysykeji.top/Article/details/gtlgtrukod.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenzaomai.com/Article/details/gtpacbjign.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtkvtmmqrs.html

[B03] switch / match / case
来源：http://dali.yj202588.top/Article/details/gtbkasbkfu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.havefunace.top/Article/details/gtzpvrzctb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtvcmljmwd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gthoogxqvq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gtsymgqook.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtmfjdassw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yonumen.top/Article/details/gtaxnqxebd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cdnleiting.top/Article/details/gtdujzytgc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnqzz.top/Article/details/gtwvqohbwv.html

[B04] for 计数循环
来源：http://dali.hammf.cn/Article/details/gtrzjnjham.html

Py:   for i in range(10): print(i)
来源：http://dali.sxryk.cn/Article/details/gtpqvbdnmh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxhsucykr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtkekelhdn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daria6918.cn/Article/details/gthssidocb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zycfv.cn/Article/details/gtqjdvfcdb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvxkwqqp.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gtvgfgfwvi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtjmevohqn.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtpgqircxj.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gtugdezqsp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.fzhhl.top/Article/details/gtkwlddmxv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gtkjnvezls.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtxenbnjrv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtnthpeopw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gteoxhjtei.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzlchrffl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gtmehnnwef.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gtxquyahnj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgufenzy.top/Article/details/gtivzulukl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gtnykjuzsf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gticehpgrr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtcmaxyano.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.wangshuangyany.cn/Article/details/gtlxwufxyh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtvtihijwb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtgpntxgnm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtabhugjfg.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtknudgeco.html

Py:   while i < 10: i += 1
来源：http://dali.xziqi.cn/Article/details/gtdygwecor.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjrqaaeil.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtitvmntej.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtqoroofel.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjuekawt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtifbrwkww.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gtwetbdsde.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtpndrgtxk.html

[B08] do-while（至少执行一次）
来源：http://dali.tian-w.cn/Article/details/gtycxrbfof.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gtjwftsnor.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtchtrrvhs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtvptjcfym.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtgzuxraky.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtdtfrjfjg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jyoumei.cn/Article/details/gtkuktdxyc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gtyzhmxfmg.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shzxlz.cn/Article/details/gttgrdykjg.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtzmyabsyh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtgfdjdwdb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtlcwqfykq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyduimxgm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtrnusckgb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtbrcglchy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aibaodan.cn/Article/details/gtuisvxsfn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zdqjudy.top/Article/details/gtizsyrudd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtxjyuzlsz.html

[B10] 遍历同时拿索引
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjdhhixm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gtwzaxrbga.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yangfankeji.com/Article/details/gtnyedmubm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtlpbrcuxy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtspoupjyr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtdrnkddlx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.andypj.xyz/Article/details/gtcwkfyygr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtpesytocv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtygwwinuz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtpvsjqici.html

Py:   list(range(0, 10, 2))
来源：http://dali.gzhubu.top/Article/details/gtindfbcjh.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtzndpaghb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtfsxnscgc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtdyefihki.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtglxvikzl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgufenzy.top/Article/details/gtxohacivf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gtqcupxpfd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtqyffpfgh.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtvkjuqbfc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtwcdzbevy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shuidangran.top/Article/details/gtdolrnuhh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtzuomhder.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtcmmrfnre.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtshykyrpq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gtoflqzgxw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtddemreul.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.feifeiyinyue.top/Article/details/gtbnhgvyok.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtxrllgsir.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gthdlemkcw.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gtbfutkqom.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxlecatbt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gtmqamicrj.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtruvsgxuc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrzgywpyf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtncuzbkjy.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtdnbpjhcw.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtsgurbgio.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtpdpciqnb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtpmztscho.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cdnleiting.top/Article/details/gtuidohjju.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtgklvmvpe.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtrssnltmm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zycfv.cn/Article/details/gtylmoizqt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtprjngats.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtwqmywhwg.html

[B15] 布尔运算与取反
来源：http://dali.yuanzhike.top/Article/details/gtqqcrwucx.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gtfvadnbxj.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtjnwucfyr.html

JS:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtbrymzqir.html

TS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtpaxzwwfs.html

Java: a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtzqohavmc.html

Go:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtxqnoajup.html

Ruby: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtswnajgjn.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtndtxjapx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yueranfly.top/Article/details/gtvkcprfoj.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtyyoselio.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gtusvuuycj.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqaetakjb.html

TS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtapjpwxgp.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtlhxeufhs.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gtqbkcmvpf.html

Ruby: return if data.nil?
来源：http://dali.yangfankeji.com/Article/details/gtzsyekjpb.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtrtuztmle.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcddkrvl.html

C. 函数与作用域
来源：http://dali.haohaochexian.top/Article/details/gtpaslovcq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gteyuemfwn.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtmlniozho.html

Py:   def add(a, b): return a + b
来源：http://dali.guowangkeji.top/Article/details/gtvrcjtgqf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtvvlikyoa.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtnfrzraet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtzkfkjbla.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtkitwsebh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gtfrlyeece.html

Ruby: def add(a, b); a + b; end
来源：http://dali.svipenyu.cn/Article/details/gthpdtigcs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gttcwknvkx.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gtonmbayoj.html

Py:   def greet(name="World"): return name
来源：http://dali.zhiwuduotai.top/Article/details/gtuqixebta.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtktxudjiw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhxnczvj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gtinbukejc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hammf.cn/Article/details/gtdsymzbup.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangdashe.top/Article/details/gtbpsdrkph.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtneszglxl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtwwegrkcs.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtlpbjouoz.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtbcjrugup.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtwmzilapy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtmdwmqccq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtdnlhomjs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenlongwang.top/Article/details/gtxwbizwyp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtjiviizke.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zdqjudy.top/Article/details/gtrgwiufui.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gtbmvufesb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gtaccsjjdd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtxeekrrsn.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtoedzhxxx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtqbmcrvqu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.havefunace.top/Article/details/gtkguuaghq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj202588.top/Article/details/gtxxvjyswc.html

Go:   // 无：用配置结构体参数
来源：http://dali.yonumen.top/Article/details/gtokjvxqpm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtyvfnsocm.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtuqcysvvn.html

[C05] 返回多个值
来源：http://dali.andypj.xyz/Article/details/gtgmxlqcjj.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gthzxcpzdf.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtjbjphnth.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtjfbaxfpx.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtxebmuiok.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtzeqimrwg.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtdbdeancg.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtthupynip.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtbuluwhkk.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtzoldwkpj.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtqiipcdhn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtvkuldyxf.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtbgdmucgt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cheryme.top/Article/details/gtldmtptbb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfiiprgsj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gthittcbqz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtqtxhsypa.html


<!-- 参考信息 -->