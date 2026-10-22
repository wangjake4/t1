代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.cheryme.top/Article/details/gt2ghucvtrp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.birdmap.top/Article/details/gt2iwkyiylu.html

TS:   // Node.js：readline 模块
来源：http://dali.andypj.xyz/Article/details/gt2vjnmbqis.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hammf.cn/Article/details/gt2nkkkuhjg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lxquobqa.html

Ruby: gets.chomp
来源：http://dali.cqqwz.cn/Article/details/gt2ejwqyenm.html

C#:   Console.ReadLine();
来源：http://dali.zhongyouzk.top/Article/details/gt2rbwwycpp.html

[A21] 保留指定小数位输出
来源：http://dali.cqqwz.cn/Article/details/gt2dnqsziuv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.fzhhl.top/Article/details/gt2pvbircso.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.cashguo.top/Article/details/gt2yabgidbp.html

JS:   (3.14159).toFixed(2)
来源：http://dali.guowangkeji.top/Article/details/gt2gdyvfzmp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.gotoacloud.top/Article/details/gt2lvnyjkga.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hncvnurx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gt2ojmkcfzs.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.0kj1m.cn/Article/details/gt2keqyxmjn.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gt2ahqkonlc.html

[A22] 获取字符串长度
来源：http://dali.wangdashe.top/Article/details/gt2malixlat.html

Py:   len(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqdnkjtm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ppjwa.cn/Article/details/gt2rexwsdtp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.iojbl.cn/Article/details/gt2jvvylcwa.html

TS:   s.length
来源：http://dali.316326.xyz/Article/details/gt2ohldwcul.html

Java: s.length()
来源：http://dali.shuidangran.top/Article/details/gt2jhksbtmc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uambuozd.html

Ruby: s.length
来源：http://dali.meibo888.top/Article/details/gt2mytctsnu.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gt2sumvztwj.html

[A23] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gt2zowcvanx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xylfe.cn/Article/details/gt2ophyjjyn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gt2xtpujhsk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gt2ldstinsm.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zycfv.cn/Article/details/gt2xxymafhw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jlsjyb.cn/Article/details/gt2yzuhmdeu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.fengsongda.top/Article/details/gt2wdsbhcqw.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zycfv.cn/Article/details/gt2lbcjkbac.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cucudq.cn/Article/details/gt2npbefqlp.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gt2oxxrrrpq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gt2dwrxzbry.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jiagoushi.top/Article/details/gt2lheyyvdx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yvedp.cn/Article/details/gt2mbwayubr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.bjfxy.top/Article/details/gt2flofvqfk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.meibo888.top/Article/details/gt2lycamunh.html

Go:   strings.TrimSpace(s)
来源：http://dali.shuidangran.top/Article/details/gt2rrcxuxty.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cashguo.top/Article/details/gt2sgjubmkh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yongpay.top/Article/details/gt2uujtgupm.html

[A25] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2ltdanbse.html

Py:   s1 == s2; s1 != s2
来源：http://dali.kuanghao11.cn/Article/details/gt2eqvodkrl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jqgufenzy.top/Article/details/gt2roxnlszg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jlsjyb.cn/Article/details/gt2gwtnbqxg.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhijiandao.cn/Article/details/gt2bptizkna.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gt2uigbziyb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gt2rohyisjj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gt2xiyminxb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2oklzstvf.html

[A26] 类型转换总览
来源：http://dali.gzhubu.top/Article/details/gt2bfgbjoia.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.nanxinkj.top/Article/details/gt2iwbbmvii.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gt2qzranrco.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuetiantiany.cn/Article/details/gt2vyxghkij.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhixingplan.top/Article/details/gt2pncfrfmh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gt2yxrumnct.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gt2ueizlprz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gt2gktzctsc.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gt2jyuvlmuz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2vttyngxq.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gt2wzdafcpv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2ygcrvwtu.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iqgjaubb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xziqi.cn/Article/details/gt2ekynujfn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gt2xgxuyjwt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xylfe.cn/Article/details/gt2elvvhaqv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2vwwppmmc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2gugfdebl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gogol.net.cn/Article/details/gt2bjpfqsgm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guowangkeji.top/Article/details/gt2tyazzueu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2erjzobeb.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2okdqgxpx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gt2kajijiar.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ivvv.top/Article/details/gt2frnlqvps.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gt2rkrwlxgk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2etevkxir.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2vxbkmtla.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gt2yadbfwyn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sufxvd.cn/Article/details/gt2zwxvlvbf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gt2thkmrood.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gt2eyqwmika.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gt2gnhbrdmf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2okzbccur.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2mgaluumx.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2lnqzvodv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.meibo888.top/Article/details/gt2dfsdtsud.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cqqwz.cn/Article/details/gt2zphmmypk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gt2phreyaec.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hywenlv.cn/Article/details/gt2ugrorhax.html

[B04] for 计数循环
来源：http://dali.jqgufenzy.top/Article/details/gt2igohztfg.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2irtihvxj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gfgxacdw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2ptolwhbm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2ogusjenz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gt2rtfabmrz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gt2huxxsrkx.html

Ruby: 10.times { |i| puts i }
来源：http://dali.c1oappe.top/Article/details/gt2nwfspknd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gt2cgaiwlof.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gt2fjkcupyw.html

Py:   for item in arr: print(item)
来源：http://dali.tanke756.top/Article/details/gt2jphkgvhz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gt2cryzpsup.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdnymnay.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2qhkxodkk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fengsongda.top/Article/details/gt2vdneamlp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gt2kxqvqcgu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gt2ccjttkvx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gt2sisktnpq.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gt2pktndhlu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2imqpmerw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2vobupaxm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ehwqpu.com/Article/details/gt2bpwinksu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.andypj.xyz/Article/details/gt2akgplmqg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gt2yqdumcbm.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmoszxnc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sufxvd.cn/Article/details/gt2lajwxwsm.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gt2sernveee.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gt2wukkhwfb.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gt2norwqoqq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2qagkiefz.html

JS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gt2klmghhfi.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gkufcnky.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fvgkrsbu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gt2qwfnwecf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.smart0.xyz/Article/details/gt2fvtilokm.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jwmgquqx.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gt2shswmkdb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258.top/Article/details/gt2hvbngejm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2xfocbtfy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2eayjbvbb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2digwfcfp.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gt2uluqwqof.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2qkaukmbu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gt2zpxpthnw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2plwjhwdd.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gt2ybhqahcr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenlongwang.top/Article/details/gt2whzzvoju.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gt2eqqvhjzv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2dsweourk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2vmotrbjb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gt2clfnjqww.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gt2klmpijmx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ajclcrgg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gt2armujxqj.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gt2uxolfbax.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gt2qkoadxpm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zycfv.cn/Article/details/gt2xwkapliz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2dpeptmbx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wrsuipsp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.wangdashe.top/Article/details/gt2mhjvxcxr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2akfgnhjt.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gt2jvojmswe.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gt2vvpoeomt.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gt2tqtvvfgt.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2oumzmpwp.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2cuyqyqri.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2steexvsd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2kjgceaxn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.aibaodan.cn/Article/details/gt2trewgeot.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gt2ujsuiths.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gt2bzcimiho.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gt2loppwxaj.html

[B12] 跳出多层循环
来源：http://dali.yvedp.cn/Article/details/gt2auehlnif.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gt2zhocurul.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gt2ggzcconr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2mvamwehw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2nqfdpfax.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edmafxql.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gt2awhlhbco.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ivvv.top/Article/details/gt2ceppaxtk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gt2otxgxspn.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fuieqxym.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gt2hkqpcoyi.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlktrcy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gt2daotifyd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shuidangran.top/Article/details/gt2lkpqyegs.html

Java: x instanceof Number
来源：http://dali.hnqzz.top/Article/details/gt2xtowqsut.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.svipenyu.cn/Article/details/gt2ifyfdhmt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gt2ulmqtnue.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gt2nrqivkex.html

[B14] 判断值是否在集合内
来源：http://dali.c1oappe.top/Article/details/gt2kejrlfqz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuanzhike.top/Article/details/gt2xrfmsjuk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gt2tvgadeic.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gt2ymvgrevw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2ntqxxenh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gt2qviocryr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gt2ecwbtcoi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2mmkonvvv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2zvurvaso.html

[B15] 布尔运算与取反
来源：http://dali.daxiang520.top/Article/details/gt2lobygvvc.html

Py:   a and b or not c
来源：http://dali.ybcxt.top/Article/details/gt2qfrioqrp.html

PHP:  $a && $b || !$c
来源：http://dali.zhijiandao.cn/Article/details/gt2ysrcgcas.html

JS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2zwnpuefk.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2texzigov.html

Java: a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2ljyxrqhc.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2fwbclkds.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bfpjvhbf.html

C#:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2bncgqnsy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gt2rximqvat.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gt2aecfzull.html

PHP:  if (!$data) { return; }
来源：http://dali.sufxvd.cn/Article/details/gt2azckngdf.html

JS:   if (!data) return;
来源：http://dali.mhx1999.top/Article/details/gt2twfbfhmx.html

TS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gt2aeeqyljf.html

Java: if (data == null) return;
来源：http://dali.yonumen.top/Article/details/gt2bdbiogpl.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gt2tivemvwa.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2fpncbpka.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gt2fmyjmdno.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxdzayd.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gt2jbpkkjek.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ewvkylcd.html

[C01] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gt2quobqftp.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gt2zrjnxekv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svaxjnar.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rtxowvln.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2mmydpjvp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gt2wusmsbnq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gt2sgmalhnu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hysaishi.cn/Article/details/gt2aboysidk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tikqtotm.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2ttougssy.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gt2kgqrntkr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gt2mtvnoqme.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rbzfccvr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2ezxgylal.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gt2atkopxzp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gt2kfdpmynz.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2dgdhuiom.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gt2wqpocmsv.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gt2uwxvuzdo.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gt2jwispiks.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tian-w.cn/Article/details/gt2leddzxrw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pyiujbzl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gt2mjaznmze.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jqgfzy.top/Article/details/gt2ccyoufkb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gt2gugdtomo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgufenzy.top/Article/details/gt2xorsutre.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzrlfwx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2hgevhczo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yonumen.top/Article/details/gt2xhnmlont.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.hnxiangtu.top/Article/details/gt2apfgfrnb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gt2lemdbfjm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gt2pwthmubq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xylfe.cn/Article/details/gt2mgrqojwx.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gt2bpfqcvvl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gt2xluuyyrp.html

C#:   f(a: 1, b: 2)
来源：http://dali.c1oappe.top/Article/details/gt2gnhectxn.html

[C05] 返回多个值
来源：http://dali.jinqigufen.top/Article/details/gt2cbsmliyt.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2plqqqkxs.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2pgwjoqun.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2omicavrk.html

TS:   return { a, b };
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ezmgknfw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tian-w.cn/Article/details/gt2aooxtfzn.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gt2tonbdccd.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2ythyxstr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.redwolf501.top/Article/details/gt2wwmnyvqt.html

[C06] 匿名函数 / lambda
来源：http://dali.yonumen.top/Article/details/gt2afqiqnbi.html

Py:   square = lambda x: x * x
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuvlfigb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gt2xjuyaghj.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gt2cpmxkjgj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gt2pgmpzoel.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2jvzbfrvf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hywenlv.cn/Article/details/gt2ajacdtzk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gt2bwuwswkg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gt2rwudpzny.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gt2tofplpey.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gt2vcyhnris.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jlsjyb.cn/Article/details/gt2fewogwnm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daria6918.cn/Article/details/gt2wqmjtrgp.html

TS:   arr.map(String)
来源：http://dali.yueranfly.top/Article/details/gt2tumprkfu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gt2ijlsvyng.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cucudq.cn/Article/details/gt2hafucfwg.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2onkvbclj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2tjatxavk.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gt2nstkinys.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gt2grsqsqvg.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mytvtorg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.fengsongda.top/Article/details/gt2dobmjwjn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2djtcqtqg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fengsongda.top/Article/details/gt2cjoqpfdc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gt2hbetyhsj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gt2vvwbydfb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sweek.top/Article/details/gt2scuwhwij.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gt2egpfwivy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gt2giufxwpx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.guannengcc.top/Article/details/gt2pvssiaqq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gt2dpqnavmw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.birdmap.top/Article/details/gt2lcnhcosw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dzuvzatq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gt2jxerqcnb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gt2qhrkjypb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gt2qxffqgmh.html

[C10] 变量作用域
来源：http://dali.shuidangran.top/Article/details/gt2nqeupmlj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gt2ohekxqcx.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gt2hktjfxix.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jiagoushi.top/Article/details/gt2yvqxxwta.html

TS:   同 JS
来源：http://dali.xziqi.cn/Article/details/gt2mwklkhjs.html

Java: 方法内为块级作用域
来源：http://dali.yongpay.top/Article/details/gt2wevhcorj.html

Go:   花括号块级作用域
来源：http://dali.jinqigufen.top/Article/details/gt2jqaryanf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yangfankeji.com/Article/details/gt2dylzfjje.html


<!-- 参考信息 -->