代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.cdnleiting.top/Article/details/gtumgluxzt.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jlsjyb.cn/Article/details/gtqacmqlmm.html

TS:   if (!x) {}
来源：http://dali.daria6918.cn/Article/details/gtryjpjhsi.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jianghu66.top/Article/details/gtvsbqtiln.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cashguo.top/Article/details/gtisgpjbth.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hammf.cn/Article/details/gtrulxmbha.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xuanzx.com/Article/details/gtchilnowz.html

[A17] 位运算
来源：http://dali.jinqigfzy.top/Article/details/gteateybke.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtqsgfvufh.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtgzdhvjgs.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xuanzx.com/Article/details/gtywcmcsui.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtkqykkein.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtpnsrcyuy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cheryme.top/Article/details/gtlntfoneq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zdqjudy.top/Article/details/gtueilluby.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtxtuodkwy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gotoacloud.top/Article/details/gtcfyjfngo.html

Py:   ord("A"); chr(65)
来源：http://dali.wangshuangyany.cn/Article/details/gtnlihjmob.html

PHP:  ord("A"); chr(65)
来源：http://dali.cheryme.top/Article/details/gtgatidozo.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtrfqsgqqe.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gzhubu.top/Article/details/gtynrmvpop.html

Java: (int) 'A'; (char) 65
来源：http://dali.zdqjudy.top/Article/details/gtxcajezjg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guowangkeji.top/Article/details/gtnjyttuxm.html

Ruby: "A".ord; 65.chr
来源：http://dali.hysaishi.cn/Article/details/gthwrtftyi.html

C#:   (int)'A'; (char)65
来源：http://dali.xuanzx.com/Article/details/gtijofgwzk.html

[A19] 交换两个变量
来源：http://dali.wangdashe.top/Article/details/gtqxjcrdlk.html

Py:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtrlfjwtag.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj20258.top/Article/details/gtlockscvj.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gtuxvmzfot.html

TS:   [a, b] = [b, a];
来源：http://dali.nwbrower.top/Article/details/gtuyuvdbjy.html

Java: int t = a; a = b; b = t;
来源：http://dali.andypj.xyz/Article/details/gtyvenrkzs.html

Go:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmobgyre.html

Ruby: a, b = b, a
来源：http://dali.c1oappe.top/Article/details/gtubupmwao.html

C#:   (a, b) = (b, a);
来源：http://dali.pengpengdd.cyou/Article/details/gtujtlbiju.html

[A20] 读取标准输入
来源：http://dali.yangfankeji.com/Article/details/gtqaveniyi.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtnwgjxkdx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cucudq.cn/Article/details/gtyjiuzxhq.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zdqjudy.top/Article/details/gtrzipklkx.html

TS:   // Node.js：readline 模块
来源：http://dali.cucudq.cn/Article/details/gtrubwjshq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsorrlieg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gtpzjlrbdd.html

Ruby: gets.chomp
来源：http://dali.yj20258.top/Article/details/gtnsppvbjm.html

C#:   Console.ReadLine();
来源：http://dali.shuidangran.top/Article/details/gtfuhuzyqe.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gtshqxzeql.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gtaiqmsoqp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.chenzaomai.com/Article/details/gtiilgmfcb.html

JS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtvghasjbp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtptsjnbrz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtwilxkniv.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yj20258888.top/Article/details/gtsfwcwmbz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gtoymnihcm.html

C#:   3.14159.ToString("F2")
来源：http://dali.dianchejie.cn/Article/details/gtmtmtprkl.html

[A22] 获取字符串长度
来源：http://dali.yj20258.top/Article/details/gtppjccbti.html

Py:   len(s)
来源：http://dali.zdqjudy.top/Article/details/gtwzhpwtqu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuanzhike.top/Article/details/gtmofjgbsu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhijiandao.cn/Article/details/gtdfkvnvky.html

TS:   s.length
来源：http://dali.yueranfly.top/Article/details/gtifkpvkza.html

Java: s.length()
来源：http://dali.zhoulong.xyz/Article/details/gtihkkvsci.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xziqi.cn/Article/details/gtuyeyppck.html

Ruby: s.length
来源：http://dali.chenzaomai.com/Article/details/gtwgfaedbu.html

C#:   s.Length
来源：http://dali.cashguo.top/Article/details/gtwtzvrsip.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gtxsylkret.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pycfn.com/Article/details/gttkbjaktw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.dianchejie.cn/Article/details/gtvtayflas.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gtlswfbdmd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtcxinfxji.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtpvjxuvbo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gtserijrox.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtjpgsyrfr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwdumusr.html

[A24] 去除首尾空白
来源：http://dali.wangshuangyany.cn/Article/details/gtkxxtzkwj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gtygwcrgpw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gturljsnnp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtqrttbidr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtzvvvpcmb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xziqi.cn/Article/details/gtmkxbkqvl.html

Go:   strings.TrimSpace(s)
来源：http://dali.fengsongda.top/Article/details/gtbqdzjfgi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenjidiqi.icu/Article/details/gtmpcxknbg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xziqi.cn/Article/details/gtitajucsy.html

[A25] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gtsdsjcnzi.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtolnauarj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocowvsko.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jyoumei.cn/Article/details/gtggwszsyd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtqqaznxax.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yueranfly.top/Article/details/gtajyerhkm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gtdsaimpfi.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtxaewimhu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gogol.net.cn/Article/details/gtzrdwxdzi.html

[A26] 类型转换总览
来源：http://dali.wangdashe.top/Article/details/gtbtwktutn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtlosmavzj.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dianchejie.cn/Article/details/gtosobtvpk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gtljtddwwm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ivvv.top/Article/details/gtokflgecg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gtkkyrlcbl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.aizwys.cn/Article/details/gtfujlgzgc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jyoumei.cn/Article/details/gtcltajrni.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtinledsax.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtnqaiosxp.html

B. 流程控制
来源：http://dali.redwolf501.top/Article/details/gtjsykatya.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtkxwmfbbj.html

[B01] 条件判断 if / else
来源：http://dali.guowangkeji.top/Article/details/gtebrkrtaf.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yj20258.top/Article/details/gtjplrxhnu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yj20258888.top/Article/details/gtjuhuvcvq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtsbyglyof.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtavbdwvcl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hongshengwenyu.top/Article/details/gtjgxmpoif.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtptiwctma.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ehwqpu.com/Article/details/gtznrucukd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtcztffgaj.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gtagtxzvgr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.kuanghao11.cn/Article/details/gthombycgl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvellojj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtdmkncdia.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtfqwuratd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtirldiwdx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sweek.top/Article/details/gtahjdogyj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gtkzgfzfxx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpddxyakj.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gtcxxbpwhr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gttfvhybka.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtgufvhhbv.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gthtjlxlhk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdfeihbzw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtlgfsrzmw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nanxinkj.top/Article/details/gtybdxyjdn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guannengcc.top/Article/details/gtmppzqrvt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.haohaochexian.top/Article/details/gtewyyrepm.html

[B04] for 计数循环
来源：http://dali.ybcxt.top/Article/details/gtrqeotump.html

Py:   for i in range(10): print(i)
来源：http://dali.vqdsnc.cn/Article/details/gtxkjpjgbu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hywenlv.cn/Article/details/gtjcudlvxh.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkgwjrxtr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jianghu66.top/Article/details/gtcymwlqce.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtxuckdawr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sweek.top/Article/details/gtrsnflwcz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtbkxenoza.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtgenevraf.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgygoktbb.html

Py:   for item in arr: print(item)
来源：http://dali.daria6918.cn/Article/details/gtbgxsqxoc.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.haohaochexian.top/Article/details/gtwvmclfpb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtfxkeyusz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtpmtgdqak.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fzhhl.top/Article/details/gtlwgvqyth.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gtjgfdnegj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gtmhhlqwlq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuanzhike.top/Article/details/gtcxhdaycx.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtzkkmzsoz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtefzroeiu.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jlsjyb.cn/Article/details/gtuwwwidkq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.quarkkingdee.top/Article/details/gtaipttgeu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gthwbmhztz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gtkaynrwoo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dianchejie.cn/Article/details/gtkkljzbeo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hammf.cn/Article/details/gtvkubzfgc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gtivagbssg.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gtcpuzwgwp.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gtisxqthsb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gtwmrtqdeo.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtjfycwzax.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtcqutsoqs.html

Java: while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtckywvwok.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cucudq.cn/Article/details/gtitayozgz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfpoqzgnh.html

C#:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtuhcubfxk.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gtrzzdpchl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtbjvrzxai.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gttojxidvj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtrrzhgbhv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtklnrairc.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtnxrxnuny.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtexbculfx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrzkdqroo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtmfoogtge.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtmkuthvpu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shangyingyoupin.top/Article/details/gtdpdxkqzw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtctgahjah.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtfmgvrtsi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtaemdqnqy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtunoxuptg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gtkothkxej.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtlllsqyro.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpnnvfcd.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtwcwqjyah.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtkyfwrnnh.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtljekuljb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gtmifakqdi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtwrqkahrk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtpdqvddgg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zdqjudy.top/Article/details/gttzyzhkwc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sysykeji.top/Article/details/gtskaweqrl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtgwrigxdh.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtgfeiaewt.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtkauwvvqw.html

PHP:  range(0, 10, 2);
来源：http://dali.hywenlv.cn/Article/details/gtwqunowpr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtsboezawg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtiezlxhnr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnuxfxwtg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenlongwang.top/Article/details/gtrovwzulm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gotoacloud.top/Article/details/gtnlhrbjat.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtiygnpyri.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gthtnahmqg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdreqjwz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtxeigtkyu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gttxhbikic.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gttsuwpzba.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtonboliiv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtbyekyzgl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gthtxoaaqw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtarqzfbbo.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtlhtensmk.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtxueropqx.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtpmzbtvsj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtouatboyr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtamfteepm.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtqjcurgxx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteljjnngh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtlaouwppk.html

C#:   x is int or double or decimal
来源：http://dali.cucudq.cn/Article/details/gtpecmahgq.html

[B14] 判断值是否在集合内
来源：http://dali.chenlongwang.top/Article/details/gtvbrjwrch.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhiwuduotai.top/Article/details/gthlerdmgr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlygwwapb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtwecsngew.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtqyyodwfd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtirgdutnf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpstkdotw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gzhubu.top/Article/details/gtytruydfn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gtmdvpzzfd.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcdfsrfm.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtmpoiahyo.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtfpnyqiuy.html

JS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtglxxwpzc.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtjynswush.html

Java: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtgujbndub.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtecocfhgq.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtfwnhwuxj.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtntfseujp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigfzy.top/Article/details/gtctddlpat.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gtltqszcps.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtmrwaptvd.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtvdlwjkgk.html

TS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwfmhmjp.html

Java: if (data == null) return;
来源：http://dali.fzhhl.top/Article/details/gtcgrbdbus.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtsfxnirev.html

Ruby: return if data.nil?
来源：http://dali.hywenlv.cn/Article/details/gtwsljdasp.html

C#:   if (data == null) return;
来源：http://dali.jinqigfzy.top/Article/details/gtpyywjftl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtpysdtoua.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtaggglvqo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqghtaqxm.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtyeszmvnd.html

Py:   def add(a, b): return a + b
来源：http://dali.yonumen.top/Article/details/gtytufnjqr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtczxjbcdl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtoxqmgksc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtztwwvluk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtlslejhdv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yonumen.top/Article/details/gtygxcnknf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gogol.net.cn/Article/details/gtwknajjif.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gtlfntthto.html

[C02] 默认参数
来源：http://dali.tanke756.top/Article/details/gtdpytklah.html

Py:   def greet(name="World"): return name
来源：http://dali.ydzc1.top/Article/details/gtmdataesa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gthyzqmcmp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtenlwllqu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtczteippi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jiagoushi.top/Article/details/gtldqpqcxg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cucudq.cn/Article/details/gtexmrejbo.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangshuangyany.cn/Article/details/gtfeffhhox.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xinyue.icu/Article/details/gtgbakwxur.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtkmvjxsrx.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gttefccqnv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtqgfenpsw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtqeubrntm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtntnymcgu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtqawjjjmo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gtmzgxzhxz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yongpay.top/Article/details/gtapoyejeg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.feifeiyinyue.top/Article/details/gtkkkkciaf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhongyouzk.top/Article/details/gtefubnwhn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtpwsgcdvd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tanke756.top/Article/details/gtqyhzgecp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtzszlzunl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtqezfrdma.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cashguo.top/Article/details/gtqtbiymrc.html

Go:   // 无：用配置结构体参数
来源：http://dali.xinyue.icu/Article/details/gthakidyeb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtfzfxecub.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtpbbelccz.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gtuzwdshid.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gtrudfghxs.html

PHP:  return [$a, $b];
来源：http://dali.yvedp.cn/Article/details/gtjubhhwwa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gttybllntm.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gtaxphxswc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shangyingyoupin.top/Article/details/gtvqucuukz.html

Go:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gthqpnfanc.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtkofsepsg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtaslypnrg.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtknkljwbz.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gtxzvoueur.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gotoacloud.top/Article/details/gthfrtdwpr.html

JS:   const square = x => x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gttrzgtyso.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtawcrgfhb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cashguo.top/Article/details/gtmslqbaoh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtzbsezvpb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtltqntfeu.html


<!-- 参考信息 -->