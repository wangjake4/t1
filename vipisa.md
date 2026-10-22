代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yanxiufei.cn/Article/details/gt2zlmribgr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.smart0.xyz/Article/details/gt2iuvnxofc.html

TS:   // Node.js：readline 模块
来源：http://dali.guowangkeji.top/Article/details/gt2xcdhhuxn.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cashguo.top/Article/details/gt2ltllhqby.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubvmzvzd.html

Ruby: gets.chomp
来源：http://dali.jlsjyb.cn/Article/details/gt2mtvbcydl.html

C#:   Console.ReadLine();
来源：http://dali.9152youxi.cn/Article/details/gt2rkaqbyyq.html

[A21] 保留指定小数位输出
来源：http://dali.hnxiangtu.top/Article/details/gt2wchdgcen.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yongpay.top/Article/details/gt2wogduwus.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.snrcjt.cn/Article/details/gt2gwxlbvvd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2qvcdaunk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yj20258888.top/Article/details/gt2ehkkmvzc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gt2rhuotnhr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gt2rsihemlg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gt2qzwjvmva.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gt2mmkhylnj.html

[A22] 获取字符串长度
来源：http://dali.sysykeji.top/Article/details/gt2glcaqtvk.html

Py:   len(s)
来源：http://dali.jinqigufen.top/Article/details/gt2izxnqsqi.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gt2bvklyofb.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ydzc1.top/Article/details/gt2linvelcx.html

TS:   s.length
来源：http://dali.jianghu66.top/Article/details/gt2mhbxetid.html

Java: s.length()
来源：http://dali.feifeiyinyue.top/Article/details/gt2frxgyjfa.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gt2lcfkkrzc.html

Ruby: s.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2tiugowhm.html

C#:   s.Length
来源：http://dali.xziqi.cn/Article/details/gt2hncnqebj.html

[A23] 大小写转换
来源：http://dali.yonumen.top/Article/details/gt2ymwqjaus.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tian-w.cn/Article/details/gt2knfdkjyn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yangfankeji.com/Article/details/gt2iawfpesv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gt2bshxuogs.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2oedjrdar.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xziqi.cn/Article/details/gt2mbdkbftl.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ybcxt.top/Article/details/gt2gpusspvm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.svipenyu.cn/Article/details/gt2wmrzkwmi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hongshengwenyu.top/Article/details/gt2hstfpqie.html

[A24] 去除首尾空白
来源：http://dali.ppjwa.cn/Article/details/gt2rjckxnqa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gt2ondvgppe.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uujxkzcf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2rcapehca.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.c1oappe.top/Article/details/gt2ktymsdzc.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhoulong.xyz/Article/details/gt2mdpufget.html

Go:   strings.TrimSpace(s)
来源：http://dali.yvedp.cn/Article/details/gt2etwhpkha.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yvedp.cn/Article/details/gt2saynyovw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yangfankeji.com/Article/details/gt2ezpbfzgr.html

[A25] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gt2xwipekib.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysdxiocx.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gt2txaxgxqx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gt2iktpcxyo.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gt2ibsunuas.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gt2evjpaisi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gt2mnterhwb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.smart0.xyz/Article/details/gt2xkkzceth.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gt2nfsaxmky.html

[A26] 类型转换总览
来源：http://dali.jyoumei.cn/Article/details/gt2czoqohmm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gt2apzzjgam.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxinkj.top/Article/details/gt2knlwdmde.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvmptatb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.andypj.xyz/Article/details/gt2bdivryqi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ivvv.top/Article/details/gt2ttqnydhf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cheryme.top/Article/details/gt2bkmeknqn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shzxlz.cn/Article/details/gt2iqurocrr.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gt2tgypmzcw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2eiiwtebj.html

B. 流程控制
来源：http://dali.hfpthk.cn/Article/details/gt2tfsvnorj.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2nrwfvcnp.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gt2hpmstdmc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2vivanvfl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gaohongyu789.top/Article/details/gt2vtiuewyl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gt2swjkwsze.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gt2veuqbgrp.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2cfavwyhl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gt2yqyvrcgc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gt2ihgqxiym.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hcnrvlsv.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gt2mgcebopy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gotoacloud.top/Article/details/gt2lnpfamod.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2utepiciy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2aqayefxa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2edulcmxo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2vtguaxnc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gt2yzxxthzf.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gaohongyu789.top/Article/details/gt2uokvrczp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2csoaqspf.html

[B03] switch / match / case
来源：http://dali.nanxuanxn.top/Article/details/gt2rkwhfmwl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gt2qlthupgq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2olfqzaca.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhixingplan.top/Article/details/gt2wvpxzixi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gt2kziqficc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sweek.top/Article/details/gt2lkhejbtm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2ectyuqrs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vzyandyo.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.feifeiyinyue.top/Article/details/gt2vorselnr.html

[B04] for 计数循环
来源：http://dali.havefunace.top/Article/details/gt2kpflwoek.html

Py:   for i in range(10): print(i)
来源：http://dali.ivvv.top/Article/details/gt2ykixherj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hysaishi.cn/Article/details/gt2tfbylmcx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2vypmpbgc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2qrklhgli.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2vsovftjl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.316326.xyz/Article/details/gt2icpuvgwe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwniiqsg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.c1oappe.top/Article/details/gt2apkdfisp.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2mfhgaqpp.html

Py:   for item in arr: print(item)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jktiesso.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.316326.xyz/Article/details/gt2mrnuqoda.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ldsdgfsc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2ohsglcfw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2onzjdzwi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gt2aejuhxpz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gt2tlwwhedm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gt2jparrkoi.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gt2ramfdzmg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gt2glqtadqc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ehwqpu.com/Article/details/gt2kbvsbcfz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2timmrchw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sxryk.cn/Article/details/gt2honvypcj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2lbqyefch.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shuidangran.top/Article/details/gt2ybszpeyc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ppjwa.cn/Article/details/gt2tqwtbaym.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gt2bzuhjiyw.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gt2aeffrryb.html

Py:   while i < 10: i += 1
来源：http://dali.chenzaomai.com/Article/details/gt2ypilfloz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gt2uvagrmfc.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2gzgrxraw.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gt2qdkavrqu.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2kmwdmjmk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gt2okkkiygu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gt2nlrimnds.html

C#:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ytxhzrke.html

[B08] do-while（至少执行一次）
来源：http://dali.jlsjyb.cn/Article/details/gt2ounyuvor.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gt2yiimewos.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2bgcyxqrr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2wnxefsec.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysaurnuo.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gt2zpxqdocu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2puoiqfgq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gt2xfezwhhj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2fwuunaoi.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gt2pjaxtvnu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjfvzamy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2bbhljejx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2fwstevls.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dngudxex.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gt2hpfambmp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gt2nvabugbi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gt2fdnpivcs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2naraqzkj.html

[B10] 遍历同时拿索引
来源：http://dali.hfpthk.cn/Article/details/gt2coispxbq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pxzqijeu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2urlvilpd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cashguo.top/Article/details/gt2tiakankg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gt2mtrgxrtr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gt2fzqslhtk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gt2spgxnfsl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gaohongyu789.top/Article/details/gt2ipuyschs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fzhhl.top/Article/details/gt2lvlukwyp.html

[B11] 生成数字序列 / 区间
来源：http://dali.andypj.xyz/Article/details/gt2ilkauqrb.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gt2oyohlxsr.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gt2lscxobsk.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2oyxoqkqy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gt2amqbbmmp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gt2wzccgkcr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.kuanghao11.cn/Article/details/gt2phvomtaw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2kclmvise.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mxglpmrp.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lbmbyhgq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hysaishi.cn/Article/details/gt2qwcasgdm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gt2kjelrysw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gt2ejisbxib.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gt2gzopgwky.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2rvclqvcu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gt2enqwmdmu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkbabjd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2varnkthg.html

[B13] 判断是否为数字
来源：http://dali.yongpay.top/Article/details/gt2xpffpgjq.html

Py:   isinstance(x, (int, float))
来源：http://dali.0kj1m.cn/Article/details/gt2rfzxkxnm.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2hmmlahrm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gt2hjbszcpi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2amnijxrw.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gt2nlmjyudv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhixingplan.top/Article/details/gt2ctdcjbow.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ydzc1.top/Article/details/gt2aiijmnzn.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gt2qaxmrhrz.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gt2zijivvoi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hfpthk.cn/Article/details/gt2rgsphptk.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gt2gzxjrlmn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.chenlongwang.top/Article/details/gt2sxtjjayk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gt2zyuxprre.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guowangkeji.top/Article/details/gt2enaowzye.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shzxlz.cn/Article/details/gt2djlupzsi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gt2uakvlqvt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2orfrmfdr.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gt2swuwdpny.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gt2hvsdclhp.html

PHP:  $a && $b || !$c
来源：http://dali.chenlongwang.top/Article/details/gt2douoktsd.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zycnwsoi.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gt2awxnkdbg.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2wwyrbxmw.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2lpnljbiq.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2kvgdfdus.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2muuiqayd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2vcraofyq.html

Py:   if not data: return
来源：http://dali.birdmap.top/Article/details/gt2oyddwgui.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gt2kfjasqlw.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2caqdevwj.html

TS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2rznyrvgn.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2uxhbsjnm.html

Go:   if data == nil { return }
来源：http://dali.aibaodan.cn/Article/details/gt2qursbnzi.html

Ruby: return if data.nil?
来源：http://dali.0kj1m.cn/Article/details/gt2yysskgsy.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gt2rvihyavw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2nlkqmsxn.html

C. 函数与作用域
来源：http://dali.svipenyu.cn/Article/details/gt2ypxjlyis.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2qzduylzr.html

[C01] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2olhesaga.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2qvnenbdh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhebfloy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2gbmwgqnm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ymhnkuhy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2eagtijzd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gt2uxmqgoko.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gt2qyswwony.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2hpdpqxqx.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2fcfmwiwj.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2givdrxxx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gt2wajgdcnu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gt2wkmbhfog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gt2ryocbdeu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gt2cvclrdjh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ehwqpu.com/Article/details/gt2exjwaszj.html

Ruby: def greet(name = "World") = name
来源：http://dali.iojbl.cn/Article/details/gt2xigyzxsc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gt2fpkvwifc.html

[C03] 可变参数
来源：http://dali.yj202588.top/Article/details/gt2whelroyj.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgufenzy.top/Article/details/gt2nnjbmtrf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2nmftabbs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gt2veyyepjo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tfglcukq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ydzc1.top/Article/details/gt2kbujmvom.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gt2tapwlfkq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.haohaochexian.top/Article/details/gt2hyfmiayb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.vqdsnc.cn/Article/details/gt2qjdxocyk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2ifyfknla.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gt2nftyvofw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2notmtzhe.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tanke756.top/Article/details/gt2owqcheiy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yj20258.top/Article/details/gt2kbycjfur.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gt2orpavctr.html

Go:   // 无：用配置结构体参数
来源：http://dali.quarkkingdee.top/Article/details/gt2iygvopjn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gt2kfgxcuti.html

C#:   f(a: 1, b: 2)
来源：http://dali.cashguo.top/Article/details/gt2qjigyfdo.html

[C05] 返回多个值
来源：http://dali.cdnleiting.top/Article/details/gt2bazyzwsj.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2qphsdqwv.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gt2jhlvlgaa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gt2kjjowwpr.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gt2fzlvzzjn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.haohaochexian.top/Article/details/gt2fwkutdtk.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2gobyofji.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2izligtoa.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yangfankeji.com/Article/details/gt2gptunskx.html

[C06] 匿名函数 / lambda
来源：http://dali.cdnleiting.top/Article/details/gt2ngsnrmmx.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gt2bawoahwl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2uywwxrfb.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gt2kzvkxghb.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2toomailr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.daria6918.cn/Article/details/gt2dwlpzall.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gt2dzlavsyq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cdnleiting.top/Article/details/gt2xrblochd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sweek.top/Article/details/gt2hnuvpcyg.html

[C07] 把函数作为参数传入
来源：http://dali.hammf.cn/Article/details/gt2fdbfedjg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dianchejie.cn/Article/details/gt2qpsfpack.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.daria6918.cn/Article/details/gt2ocybhbbn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gt2krinywrv.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gt2qpirpvxx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ybcxt.top/Article/details/gt2tkucdgro.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.snrcjt.cn/Article/details/gt2zbjcxbgd.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2hfilieqk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nwbrower.top/Article/details/gt2bbovkimw.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gt2igrprypn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gt2zejppmta.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gt2bxhnnijp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gt2hlwcxhht.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gt2ifiriawo.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yongpay.top/Article/details/gt2irxkqxhx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.quarkkingdee.top/Article/details/gt2zxhhxvwm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gt2hebyufmb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xylfe.cn/Article/details/gt2htasfodh.html

[C09] 递归
来源：http://dali.0kj1m.cn/Article/details/gt2tspmjgtm.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2jewixnoq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2weckvjmq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2qauqbqxw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhengqikj.top/Article/details/gt2gaanpswh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gt2waidnjac.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jyoumei.cn/Article/details/gt2hnihlife.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2zcqrpemh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daxiang520.top/Article/details/gt2qwjztbbw.html

[C10] 变量作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2tqjngqrr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.iojbl.cn/Article/details/gt2xnmxjmor.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jqgufenzy.top/Article/details/gt2mhnhbcff.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenzaomai.com/Article/details/gt2dhzktngv.html

TS:   同 JS
来源：http://dali.yj20258888.top/Article/details/gt2jbwsepdi.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eiojubgi.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gt2vkvhwfeq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gt2thrtapne.html


<!-- 参考信息 -->