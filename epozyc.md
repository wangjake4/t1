代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gtdtmjqckn.html

Java: (int) 'A'; (char) 65
来源：http://dali.yanxiufei.cn/Article/details/gtlqokdavx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sysykeji.top/Article/details/gtwgtaqfav.html

Ruby: "A".ord; 65.chr
来源：http://dali.wangshuangyany.cn/Article/details/gteyhvvgvu.html

C#:   (int)'A'; (char)65
来源：http://dali.quarkkingdee.top/Article/details/gthheuexzk.html

[A19] 交换两个变量
来源：http://dali.yj20258.top/Article/details/gtayqwsrfs.html

Py:   a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gttgjbignf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.iojbl.cn/Article/details/gthljvafxd.html

JS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtpaojndpm.html

TS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtxvcejpvg.html

Java: int t = a; a = b; b = t;
来源：http://dali.fzhhl.top/Article/details/gtryqrrfxo.html

Go:   a, b = b, a
来源：http://dali.guannengcc.top/Article/details/gtyegcjcyo.html

Ruby: a, b = b, a
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwldymvg.html

C#:   (a, b) = (b, a);
来源：http://dali.chenlongwang.top/Article/details/gtqhwvarok.html

[A20] 读取标准输入
来源：http://dali.snrcjt.cn/Article/details/gtbohoycwf.html

Py:   name = input("请输入：")
来源：http://dali.yongpay.top/Article/details/gtsckhvdyw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtlrilyjfv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.andypj.xyz/Article/details/gtondsjqbq.html

TS:   // Node.js：readline 模块
来源：http://dali.yangfankeji.com/Article/details/gtrmkvqoxo.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jqgufenzy.top/Article/details/gtoawpdffv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hammf.cn/Article/details/gtzhmybfgd.html

Ruby: gets.chomp
来源：http://dali.xuanzx.com/Article/details/gtzzropplp.html

C#:   Console.ReadLine();
来源：http://dali.feifeiyinyue.top/Article/details/gtmwdcwpzp.html

[A21] 保留指定小数位输出
来源：http://dali.redwolf501.top/Article/details/gtvxntvlkv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtjjacwnei.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.bjfxy.top/Article/details/gtonnekxos.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pycfn.com/Article/details/gtiswwdprb.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtiexetsav.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtxlnmcphi.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtcsepwggd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtrubgible.html

C#:   3.14159.ToString("F2")
来源：http://dali.xinyue.icu/Article/details/gtzvqatgfg.html

[A22] 获取字符串长度
来源：http://dali.hammf.cn/Article/details/gtxrpfpqhy.html

Py:   len(s)
来源：http://dali.9152youxi.cn/Article/details/gtgxfbflij.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.aizwys.cn/Article/details/gtpizgfayx.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zdqjudy.top/Article/details/gtkfvlynna.html

TS:   s.length
来源：http://dali.tanke756.top/Article/details/gtsqihzpui.html

Java: s.length()
来源：http://dali.kuanghao11.cn/Article/details/gtqltnmphg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zhengqikj.top/Article/details/gtpipyvppe.html

Ruby: s.length
来源：http://dali.iojbl.cn/Article/details/gtihtopmka.html

C#:   s.Length
来源：http://dali.ivvv.top/Article/details/gttoqblqzr.html

[A23] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtqoxbnfht.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhijiandao.cn/Article/details/gtmpecpzho.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yongpay.top/Article/details/gtazxxkrlb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtsydezlxi.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtopirnvbf.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.gaohongyu789.top/Article/details/gtaostxukm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yvedp.cn/Article/details/gtsargngtc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinyuanbaomall.cn/Article/details/gtludgdxme.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yuanzhike.top/Article/details/gtjhkzotqf.html

[A24] 去除首尾空白
来源：http://dali.zhoulong.xyz/Article/details/gtbmnkcnfv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.0kj1m.cn/Article/details/gtmgvcefjf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yongpay.top/Article/details/gteiebxoyu.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.meibo888.top/Article/details/gtylfnqhjs.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtybopbijj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.ivvv.top/Article/details/gtgdovkrly.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtznnkerbt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gzhubu.top/Article/details/gtspteivnj.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtdlxqmqix.html

[A25] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtkisobatd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.smart0.xyz/Article/details/gtwjunnosz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yongpay.top/Article/details/gtussbvbjb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zycfv.cn/Article/details/gtrkkfwemu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.9152youxi.cn/Article/details/gttvbvcirr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtewjlyptu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtjhwccfom.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxinkj.top/Article/details/gtbleugtnx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtilnqsjmu.html

[A26] 类型转换总览
来源：http://dali.jianghu66.top/Article/details/gtbmxbrdcj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhijiandao.cn/Article/details/gtsvdctspk.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258.top/Article/details/gtxpvsfkgg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gtxowrgdbi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekesjnnz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gttbgxxkwp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cdnleiting.top/Article/details/gtkieieoqq.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pycfn.com/Article/details/gtcrqsnkal.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nwbrower.top/Article/details/gtxeozypvu.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtgcspruvb.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gtrvjleknr.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvqswxuyw.html

[B01] 条件判断 if / else
来源：http://dali.gotoacloud.top/Article/details/gtrrgbhhpr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtqgesdhcm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cqqwz.cn/Article/details/gtpkaudqwn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtgjhylfmh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtdjctjhsy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gogol.net.cn/Article/details/gtmxfoboyz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gtpoklgmrf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.vqdsnc.cn/Article/details/gtrdbxdknc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtfhkpolvo.html

[B02] 多分支 else if / elif
来源：http://dali.yj202588.top/Article/details/gtvpijqtmx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj202588.top/Article/details/gttgnovpbd.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gtrgrxrdca.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtsbtiqqzr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtyvtjfeiz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtvkapyivt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gthwxgzwui.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daxiang520.top/Article/details/gtibtjthmz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtlgldufhs.html

[B03] switch / match / case
来源：http://dali.tanke756.top/Article/details/gtrnhrtglv.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtvgymwged.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtzmbexyio.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtkwrvbwlq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtrknayaaj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtxipnbijq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.aizwys.cn/Article/details/gtmocakhkd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gtwmiztvdr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtdrsvywaf.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtttsfotaj.html

Py:   for i in range(10): print(i)
来源：http://dali.smart0.xyz/Article/details/gtematnbck.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gtozpymjcs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hammf.cn/Article/details/gtmljmwvce.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtszyxvarg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.chenlongwang.top/Article/details/gtgxpkssgu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnqzz.top/Article/details/gtjvmyrloq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.smart0.xyz/Article/details/gtszyyfmgh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yangfankeji.com/Article/details/gtmfjwhmet.html

[B05] 遍历数组 / 列表
来源：http://dali.jianghu66.top/Article/details/gtavnkbmrf.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gtfsxkjsdm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenlongwang.top/Article/details/gtqxgspuxf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtfvvpgxpf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gthzkilpyi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gtmacvqbqi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.smart0.xyz/Article/details/gtfelaovdq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gtgpmsfwig.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gtfyvwyycl.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtovxrzvgo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gtljjixrym.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyfhaoerc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtjaowhzms.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmtdmcsk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.birdmap.top/Article/details/gtocthqmfi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gtklcdmujs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhoulong.xyz/Article/details/gtyqeuwlmb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvfbghiyn.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gtucvauztt.html

Py:   while i < 10: i += 1
来源：http://dali.sufxvd.cn/Article/details/gtvcekgdvc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ybcxt.top/Article/details/gtqjiejvxp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtdldnbwki.html

TS:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtxswvpdiy.html

Java: while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtboofauyt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gtdanrslms.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtxwijciar.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtdmivehrs.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtxpcznpvl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtnaupgnlx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtujelrmjv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gtengzzrck.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjchgmbf.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtjeqatbtc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gthfwicrwx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shuidangran.top/Article/details/gtvqangeqk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtxjyriyva.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtjacahjpr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hysaishi.cn/Article/details/gtrmpbnscv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtodenaqju.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtutnwoajx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtqbebhlhg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtnshlvtjm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gtoiupgevi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtxxwssgax.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtyjetmebg.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gtexhlcwsg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gtpzuaksfm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fzhhl.top/Article/details/gtortuhnqg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtamrockwi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtsqwgottz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuxming.cn/Article/details/gtbmigegam.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtuwbhnquo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtsbjbsszd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtauunszma.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtcsbwkswo.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtdyolydxj.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigufen.top/Article/details/gtxzogpath.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtkjhebtao.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gtbiqlesjz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.dashuyun.cn/Article/details/gtinboftaa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtgwxmtqnv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxinkj.top/Article/details/gtnxtarmas.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.fengsongda.top/Article/details/gttldhhozy.html

[B12] 跳出多层循环
来源：http://dali.sweek.top/Article/details/gtppdfeaux.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gthddyqvpb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtgjypudkn.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtzjnhcfyo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtmjckcdxu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtfmxdbqxi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gtkrhkyqoc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hywenlv.cn/Article/details/gtfnuvjhnr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gttnfkjfew.html

[B13] 判断是否为数字
来源：http://dali.jyoumei.cn/Article/details/gtvkrekzjp.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtodqwceht.html

PHP:  is_numeric($x)
来源：http://dali.gaohongyu789.top/Article/details/gtezajjaqx.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258.top/Article/details/gtprrdyomy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkgylaso.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtuttfsmbd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtmdhowpjb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gtkybqhwld.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gttmwxjgso.html

[B14] 判断值是否在集合内
来源：http://dali.hammf.cn/Article/details/gtmdpdhujf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shzxlz.cn/Article/details/gtmrziqabz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtfewlnyez.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtiucafkzg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtxhxifltu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtzsuozxjj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yongpay.top/Article/details/gtdvpfojyx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtdhlehvql.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gthslozlqi.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqwnmhxmw.html

Py:   a and b or not c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdhfdoyuk.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgnvtwdv.html

JS:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtxyuhmimk.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtrjwdcxhd.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtkxdijaiz.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtabpyqjmr.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfsozkhc.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtbuhynndx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtqfajvqhr.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gttkvolmmh.html

PHP:  if (!$data) { return; }
来源：http://dali.fzhhl.top/Article/details/gtdkkfxsts.html

JS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtrgbwxchf.html

TS:   if (!data) return;
来源：http://dali.xuetiantiany.cn/Article/details/gtagihjrol.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtnzruszwp.html

Go:   if data == nil { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtcldmuwxw.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gtdeeahbhd.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gttoymmltb.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtbmpmdczx.html

C. 函数与作用域
来源：http://dali.cashguo.top/Article/details/gtddogsbgd.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtsmfyihvf.html

[C01] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtwyitiaav.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gtwuoxzjra.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtmotctemm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtlavaxenc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtokbkrgdd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtcqrzaynn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtwbuxcwmf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.birdmap.top/Article/details/gtpetqimqi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtkfnxldwv.html

[C02] 默认参数
来源：http://dali.guannengcc.top/Article/details/gtttluerkm.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gtomyojovz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtohusxsbv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtatnxivwi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtefecaqxo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtpgvmdtwv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sxryk.cn/Article/details/gttzzcuaba.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gtaxlzotyq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuwxvhdxz.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdqvwrkhl.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnqzz.top/Article/details/gtwqyzekvb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nanxinkj.top/Article/details/gtpqfxhwfn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtjmsnmvoi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtnjgjcwud.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtfzegzmax.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.birdmap.top/Article/details/gtnymwueni.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtvxhkdvpz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sufxvd.cn/Article/details/gtpyklhlek.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shangyingyoupin.top/Article/details/gttlzsyvfv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtkctbhggu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtcyewhozr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtjaquecth.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gtpdhyxxtu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtygwmrhfr.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtumncjgip.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gtnaowafqf.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtpjgbzmde.html

[C05] 返回多个值
来源：http://dali.hywenlv.cn/Article/details/gtujpvshop.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtcdklxfcs.html

PHP:  return [$a, $b];
来源：http://dali.shuidangran.top/Article/details/gteiouscqf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtvkqcopsg.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtmvdrjauy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnqzz.top/Article/details/gtleewxjlb.html

Go:   return a, b
来源：http://dali.xinyue.icu/Article/details/gthhplxptr.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtonlhzbft.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtksbfrrrz.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtiurexmzn.html

Py:   square = lambda x: x * x
来源：http://dali.feifeiyinyue.top/Article/details/gtnjjorncu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gtfgvmtiha.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtvfdvokmt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtqvycxmao.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtobtxabxh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gtcmbjwefi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtcgdwprea.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtctdocvkc.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gtgnlkfigu.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtlvqsqyes.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yongpay.top/Article/details/gtdinpblju.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sxryk.cn/Article/details/gtelyhmlao.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gtlgoxpise.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zdqjudy.top/Article/details/gttesdxgql.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhixingplan.top/Article/details/gtppdwvuoi.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtylnzjmdq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtmptufqxn.html

[C08] 闭包
来源：http://dali.ybcxt.top/Article/details/gtqhfqjbdw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtwtqsrljo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gthsltrfef.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtrnnsvswc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtdvagwxae.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtrpqalkvm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gtdotcvpaq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.kuanghao11.cn/Article/details/gtxusvdobp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtlurmdlir.html

[C09] 递归
来源：http://dali.ydzc1.top/Article/details/gtdtwddupk.html


<!-- 参考信息 -->