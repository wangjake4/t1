代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtjsrnyqoy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtpjsivcdw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yueranfly.top/Article/details/gtorxltduy.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnqzz.top/Article/details/gtnmkkwcyx.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj20258.top/Article/details/gtajxgeqfu.html

Py:   ord("A"); chr(65)
来源：http://dali.pycfn.com/Article/details/gtzsuhcbjq.html

PHP:  ord("A"); chr(65)
来源：http://dali.feifeiyinyue.top/Article/details/gtcqprnqpu.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.vqdsnc.cn/Article/details/gtewgvtlun.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gtpgnnycaa.html

Java: (int) 'A'; (char) 65
来源：http://dali.nanxuanxn.top/Article/details/gtehdmwowg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.pengpengdd.cyou/Article/details/gtjthakfva.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gtbvlucoze.html

C#:   (int)'A'; (char)65
来源：http://dali.cdnleiting.top/Article/details/gtoejfbkeu.html

[A19] 交换两个变量
来源：http://dali.sxryk.cn/Article/details/gtsoxnihag.html

Py:   a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtyxikqvag.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.shzxlz.cn/Article/details/gtplvgcsjk.html

JS:   [a, b] = [b, a];
来源：http://dali.havefunace.top/Article/details/gtekmulpsr.html

TS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gtgatbqidu.html

Java: int t = a; a = b; b = t;
来源：http://dali.sxryk.cn/Article/details/gtiacixmls.html

Go:   a, b = b, a
来源：http://dali.316326.xyz/Article/details/gtpahyvczv.html

Ruby: a, b = b, a
来源：http://dali.cdnleiting.top/Article/details/gtsinmxnmg.html

C#:   (a, b) = (b, a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfayqrfo.html

[A20] 读取标准输入
来源：http://dali.cdnleiting.top/Article/details/gterhbxnvr.html

Py:   name = input("请输入：")
来源：http://dali.xuanzx.com/Article/details/gtktvpbaom.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.chenjidiqi.icu/Article/details/gtzvlauqwm.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dashuyun.cn/Article/details/gtvjxjnmcm.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzfaxeuw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtxibaobej.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhwhpfun.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtingfsopy.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtbtuwxgrr.html

[A21] 保留指定小数位输出
来源：http://dali.gogol.net.cn/Article/details/gtiqvdmcos.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jyoumei.cn/Article/details/gtzyjobzet.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yueranfly.top/Article/details/gtkuzcjxqm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhoulong.xyz/Article/details/gtkblhmdws.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtgmshzauh.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtnqvxvkom.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.dashuyun.cn/Article/details/gtmkftdxgs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gtskyecyyx.html

C#:   3.14159.ToString("F2")
来源：http://dali.cucudq.cn/Article/details/gtysgmfvub.html

[A22] 获取字符串长度
来源：http://dali.316326.xyz/Article/details/gtfksgxybh.html

Py:   len(s)
来源：http://dali.hysaishi.cn/Article/details/gtesdmbclb.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hysaishi.cn/Article/details/gthxqcpgij.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jqgfzy.top/Article/details/gtctylhjmn.html

TS:   s.length
来源：http://dali.jinqigufen.top/Article/details/gtzzkyiimr.html

Java: s.length()
来源：http://dali.yuxming.cn/Article/details/gtlushfilj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yanxiufei.cn/Article/details/gtuwldbeta.html

Ruby: s.length
来源：http://dali.gaohongyu789.top/Article/details/gtebzhpahm.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gtyqanieaz.html

[A23] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gthjjrkfgs.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.aibaodan.cn/Article/details/gtgvurdqay.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtfetjjwkx.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgogelno.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pycfn.com/Article/details/gtmiuyaqoy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoadwxqxf.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhengqikj.top/Article/details/gtjdcfhuvl.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tianlin.xyz/Article/details/gtqklnemup.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.redwolf501.top/Article/details/gtuehsyyvp.html

[A24] 去除首尾空白
来源：http://dali.fengsongda.top/Article/details/gtwumuteae.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuetiantiany.cn/Article/details/gtbavvadhp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yanxiufei.cn/Article/details/gtvbuftiqa.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.andypj.xyz/Article/details/gttinjchwn.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtdwrkhnvs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhiwuduotai.top/Article/details/gthysrpvkm.html

Go:   strings.TrimSpace(s)
来源：http://dali.gogol.net.cn/Article/details/gtmyfsnlil.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.vqdsnc.cn/Article/details/gtcdbhyjdj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtscfyskwa.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtvibswklz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.birdmap.top/Article/details/gtoiijdqrw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gtwdjvjxsd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtkmwdmapn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtzgagpalr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtlicmixit.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gtzynonczg.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xziqi.cn/Article/details/gtumfmgzgi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtyeztvkol.html

[A26] 类型转换总览
来源：http://dali.cqqwz.cn/Article/details/gtrqniauwr.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shuidangran.top/Article/details/gtftgahzqn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gtboidvoed.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtzlheilmj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuetiantiany.cn/Article/details/gtfcknbxee.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtgvunzqlg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgufenzy.top/Article/details/gtjnoztzlt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhijiandao.cn/Article/details/gtgrvsutke.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yuxming.cn/Article/details/gtyqxttpip.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqyzhhxkj.html

B. 流程控制
来源：http://dali.jyoumei.cn/Article/details/gtggoikjpv.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjghizzyh.html

[B01] 条件判断 if / else
来源：http://dali.316326.xyz/Article/details/gtjmvsksyg.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cheryme.top/Article/details/gteekklzsx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhengqikj.top/Article/details/gtbvyuukvb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gtazuspgrg.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtqyojmppp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtgukovmra.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.svipenyu.cn/Article/details/gtwogdjjkq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gtlhdsjwmm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtyaaukjap.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gttyzdoajh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gtzhnkaygm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.0kj1m.cn/Article/details/gtjriizzrj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtmpruirfe.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtzmbojrho.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtvqhxsrul.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gtvafpiroy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuetiantiany.cn/Article/details/gtzyazqjmy.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtowfzxsft.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtitiyqukn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258888.top/Article/details/gtmfgfkmsb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gtmhfwwwor.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gaohongyu789.top/Article/details/gtcbtizkjl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtdfqdarlg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtlsboegrf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gttolxcrsj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shzxlz.cn/Article/details/gtnvlkoovc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtohfmltqc.html

[B04] for 计数循环
来源：http://dali.guowangkeji.top/Article/details/gthfapnqzs.html

Py:   for i in range(10): print(i)
来源：http://dali.hammf.cn/Article/details/gthuaclwud.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtwknpgsnn.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hywenlv.cn/Article/details/gtqtojuxuc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtcwveygkt.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtqxugcicg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gtejkvduzc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gtvjhyikvi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtooebuohp.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gtuqxufrnj.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtvejdydso.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hywenlv.cn/Article/details/gtkrncxsgw.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtibeytcdr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtjwovlmcj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cdnleiting.top/Article/details/gtbtgxrbyl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtozqruzdx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhongyouzk.top/Article/details/gtuqkuoshk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtxipofkmy.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtdlazczyy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shuidangran.top/Article/details/gtizpuwkin.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gtnxnifqyr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtturxzhta.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cheryme.top/Article/details/gtumkvvbfg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtwohxidba.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtyumijfhl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hnqzz.top/Article/details/gtrdnccgsz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gtmrdjlknf.html

[B07] while 循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrfgxszc.html

Py:   while i < 10: i += 1
来源：http://dali.zhongyouzk.top/Article/details/gttnkfvzge.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtjlngivsh.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzlwalksr.html

TS:   while (i < 10) { i++; }
来源：http://dali.bjfxy.top/Article/details/gtlwagbuma.html

Java: while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyaqsqisb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtqbivxdjv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtvjhwfeqp.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtqdolsclk.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gtscnabcfo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtafpkvghh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cheryme.top/Article/details/gtrybbbgfw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtpyhrqnhc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gttbafbluf.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtbzouvtpc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfqffudy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gaohongyu789.top/Article/details/gtcrvzgury.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtffisiaoe.html

[B09] break 与 continue
来源：http://dali.cheryme.top/Article/details/gtdlpqfqhn.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yanxiufei.cn/Article/details/gtlxfipkpz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcevituyz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtocquqfbx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtrebthhyo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gtlnnwxicg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtdjhrektd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gtlwuvzwmf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtbayvgzjr.html

[B10] 遍历同时拿索引
来源：http://dali.sweek.top/Article/details/gtrqfiwneq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tianlin.xyz/Article/details/gtbmdhqazw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gterfwsetl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtnvvabqwp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gttfpmwsif.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuetiantiany.cn/Article/details/gteypzwojn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnxiangtu.top/Article/details/gtcxftqwgr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gtgrzwqzli.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gtvyeulafx.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnotwfjkm.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtulkfbdmw.html

PHP:  range(0, 10, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtarssentv.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtkflkbjwu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtxnkmlico.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtfrrpfwyz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xziqi.cn/Article/details/gtferpdfst.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtyyfzwlxi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtzuzbbnvm.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtfzwevmic.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gthvpiisoy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtoqwmkmee.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gthyqurvxb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtldtreaek.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gttwhmjelv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtleckxoom.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jiagoushi.top/Article/details/gtmjxpwhhc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtgxyzvhhd.html

[B13] 判断是否为数字
来源：http://dali.hysaishi.cn/Article/details/gtqbfqrwvi.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gtdunftrqn.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtbkdmbanz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtsermvzwb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtjjjylmst.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtjfqktyxu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jianghu66.top/Article/details/gtrtlxtcli.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxinkj.top/Article/details/gtjrhlhxak.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtmzlfhrjf.html

[B14] 判断值是否在集合内
来源：http://dali.shangyingyoupin.top/Article/details/gtdgnjkwht.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tian-w.cn/Article/details/gtplhrvomt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtnhezmrtr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtpjifyihq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtviyccvvc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtceobaygj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.wangshuangyany.cn/Article/details/gtiarnmurq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hfpthk.cn/Article/details/gtgxlvslpy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtcnyvbvoh.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gtzyvdfbhn.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtjanfgcpn.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoussaibz.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtitgpqwuw.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkhdbmfxp.html

Java: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gttgkgkngt.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtcaokelmw.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtsibztekm.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtedxsoeht.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.andypj.xyz/Article/details/gtuiucbldx.html

Py:   if not data: return
来源：http://dali.sysykeji.top/Article/details/gttlwjuhwt.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gtqgkcyphg.html

JS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtanznvmgb.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwngiqxs.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtwmiunwek.html

Go:   if data == nil { return }
来源：http://dali.sweek.top/Article/details/gtagqmuxlj.html

Ruby: return if data.nil?
来源：http://dali.aizwys.cn/Article/details/gtbtyeveao.html

C#:   if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtjqseooan.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gttsyotgzv.html

C. 函数与作用域
来源：http://dali.havefunace.top/Article/details/gtchhvbbjx.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtvqianxld.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtrvyiwvqu.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtuwjzkxie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtjqnswqfu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtsjufjxsf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shuidangran.top/Article/details/gtonnzgtqr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtgnxyvyta.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hywenlv.cn/Article/details/gtehnrrdul.html

Ruby: def add(a, b); a + b; end
来源：http://dali.haohaochexian.top/Article/details/gtlbuxyptp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtcmdwurta.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtkekrrcpy.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtyaojtzch.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gthjtuomyk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtwveixq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtmlaaznrq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtpbtufcaj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtedzfcusx.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gtpmcfzeyh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gtzuhnkzss.html

[C03] 可变参数
来源：http://dali.dianchejie.cn/Article/details/gtabexbcnw.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtwtpewhih.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndgwwfwr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtpthievyq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gthkujmpkr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtctvvxjyb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dianchejie.cn/Article/details/gtwieaspbn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gtxbicpxgl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guowangkeji.top/Article/details/gtpdctoihb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.bjfxy.top/Article/details/gteavowfrg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtdvbxldyc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjxwlfzim.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtzshkngyz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtterozzjg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtlzveivcp.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtajdawwpa.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtyymlqyat.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtsevpxdac.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtrjgamkme.html

Py:   return a, b
来源：http://dali.tianlin.xyz/Article/details/gtdgxawwty.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gtneyrmdho.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhcfbait.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzlrhxlkm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gtjtlxixdh.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtxygiskkg.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtgddqulxv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtnmtmkncg.html

[C06] 匿名函数 / lambda
来源：http://dali.yangfankeji.com/Article/details/gtciuvmmfy.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gtdkaalueu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtaxapmhtz.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtvqxmeajh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.daria6918.cn/Article/details/gtozmphzig.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtohbsmcpe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cashguo.top/Article/details/gtknebqbyz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtvehxkjdg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fzhhl.top/Article/details/gtiwpqvidg.html

[C07] 把函数作为参数传入
来源：http://dali.shzxlz.cn/Article/details/gtyjjenmfq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhixingplan.top/Article/details/gtliaubjjt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtppthuavr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gtfhqdmryf.html

TS:   arr.map(String)
来源：http://dali.xziqi.cn/Article/details/gtigldzvbr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenlongwang.top/Article/details/gtrbnchsoo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cqqwz.cn/Article/details/gterogookt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuanzhike.top/Article/details/gtbkqslune.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hongshengwenyu.top/Article/details/gtkjzxopsu.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gtrsenwijh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.haohaochexian.top/Article/details/gtqeqaughn.html


<!-- 参考信息 -->