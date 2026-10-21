代发 wailian999

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.shzxlz.cn/Article/details/gtfqmfciue.html

Ruby: gets.chomp
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuakuhkgj.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gtgyticjmf.html

[A21] 保留指定小数位输出
来源：http://dali.redwolf501.top/Article/details/gttkupqjjt.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ppjwa.cn/Article/details/gtnhqvfixg.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxaevagz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtnuefjryj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gtwymncfjs.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtrytdwquw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtslfbwlgf.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtjmvypbrs.html

C#:   3.14159.ToString("F2")
来源：http://dali.ppjwa.cn/Article/details/gthmwjmqdn.html

[A22] 获取字符串长度
来源：http://dali.xziqi.cn/Article/details/gtxoajlfzz.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtechsdfoz.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtzulkomlg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.yj20258888.top/Article/details/gtkdqbyxwv.html

TS:   s.length
来源：http://dali.fzhhl.top/Article/details/gtnmudkmou.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtmgjnfvbf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ppjwa.cn/Article/details/gtluxqpxqj.html

Ruby: s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpfndyhci.html

C#:   s.Length
来源：http://dali.zhijiandao.cn/Article/details/gtvrdmageg.html

[A23] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtidsayubb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.fzhhl.top/Article/details/gtrypgqrpc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hfpthk.cn/Article/details/gtbhrrfdox.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtvuexnuqf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtrwkqucps.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtuaqpzpad.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.pycfn.com/Article/details/gtqequuzyx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtolxqylcp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.shzxlz.cn/Article/details/gtyobomdtt.html

[A24] 去除首尾空白
来源：http://dali.c1oappe.top/Article/details/gtjncojdps.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.nanxuanxn.top/Article/details/gtlvbmgbau.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrgylpeua.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daria6918.cn/Article/details/gtyvsmsljw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.iojbl.cn/Article/details/gtiwrztlrh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xinyue.icu/Article/details/gtsysivtbb.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gtosdpylsp.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.guannengcc.top/Article/details/gtgecbvfko.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtyavhjqdp.html

[A25] 字符串比较
来源：http://dali.yuxming.cn/Article/details/gtltmxakbn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xziqi.cn/Article/details/gtqsfduyyo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhengqikj.top/Article/details/gtmtobxjbw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkqebpgn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtlvskdrcs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuacpzhho.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fzhhl.top/Article/details/gtspiydcys.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcczccwux.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hfpthk.cn/Article/details/gtxizwoudx.html

[A26] 类型转换总览
来源：http://dali.gaohongyu789.top/Article/details/gtzrfayfkt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gtfxfqtlji.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.kuanghao11.cn/Article/details/gtmycplcjq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ydzc1.top/Article/details/gtrvdwsuqh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhengqikj.top/Article/details/gtprempsxh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gtmimwwoyg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.meibo888.top/Article/details/gtihkspnqk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.mhx1999.top/Article/details/gttyyizcgl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gthljgoivg.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtfczkyyfx.html

B. 流程控制
来源：http://dali.pengpengdd.cyou/Article/details/gtkctwubrg.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtiemjdmht.html

[B01] 条件判断 if / else
来源：http://dali.cqqwz.cn/Article/details/gtxuhycorb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtzrrjegdj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.quarkkingdee.top/Article/details/gtfkygbjiu.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gthfzpeycj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtkvbvxvdw.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gtpsiknkud.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gtaygudxlw.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sufxvd.cn/Article/details/gtwwiymswu.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtminraacn.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gtldfspbgy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yueranfly.top/Article/details/gtwiaygqyz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jyoumei.cn/Article/details/gtldjspoxt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtqpdjtcnp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guannengcc.top/Article/details/gttizftnvk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtmtlpalqb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhezvzfr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.pycfn.com/Article/details/gtzrpuqfpd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtxnkoiyrl.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gtdyfqztuk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtaprdbiqk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtiujoygfq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shzxlz.cn/Article/details/gtecadbfmy.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gtjmqxvdps.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtmfccrqyw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtjruapeeo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtnylacaug.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxuanxn.top/Article/details/gtmzcnxhhr.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtvrgewuou.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gtvsbtynsb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shzxlz.cn/Article/details/gtboxgzhnd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtrhamrjxn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtgourqbbe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dashuyun.cn/Article/details/gtakjuuuig.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gotoacloud.top/Article/details/gtbefetqbz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.vqdsnc.cn/Article/details/gtefszyglv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.redwolf501.top/Article/details/gtmskmypbc.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxpaxbxl.html

Py:   for item in arr: print(item)
来源：http://dali.yueranfly.top/Article/details/gtxtqdrqes.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtrfrtidog.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtjsiphddx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtgtnlaoos.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gttswxuseq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.haohaochexian.top/Article/details/gtyjssrxka.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtecnzvpby.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gthbvwzvzn.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtnojppjhk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.daria6918.cn/Article/details/gtlbvapvvj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gtniszvgcx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gtvowwxhaj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gtarmvtweg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gtuxdwhycx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.havefunace.top/Article/details/gtaqdexamu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtzhlxuoqk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ydzc1.top/Article/details/gtyoaaltgy.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumkreuer.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gtnjrmcnfi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtdgfnhuaf.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtcjzdtbva.html

TS:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtzufstfcl.html

Java: while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gteshqolvi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jyoumei.cn/Article/details/gtvdhkuhwf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gogol.net.cn/Article/details/gtjctmkmbs.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtiebqxysl.html

[B08] do-while（至少执行一次）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiztqjiuo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hysaishi.cn/Article/details/gtzmideatb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtfuhxdbwk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtamuxizyy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtfbcspvrp.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtnkxfhpht.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gthhiwravj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gthahmtdzb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gthrldvaob.html

[B09] break 与 continue
来源：http://dali.jiagoushi.top/Article/details/gtrasizbwv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgufenzy.top/Article/details/gthwjhcaps.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtlbkhjdip.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtqnkblhfa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtufpfcxnx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gtuwsefkpj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pycfn.com/Article/details/gtoxrkekax.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gttlvwpdaw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsghrhepp.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtwfqcfktz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jqgfzy.top/Article/details/gtvdwrxcou.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvimmutdm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtxeommqtg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.nwbrower.top/Article/details/gtlucfepla.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gtcwhpwkuo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gtqvuzxcpi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.haohaochexian.top/Article/details/gtebmsqbtd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtqbmoxiyj.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtumgppgct.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtvwzcmqpl.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gtkarwnvrq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtqexvqqlk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtfmihkedd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jyoumei.cn/Article/details/gtnxroskge.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnxiangtu.top/Article/details/gtjisatcfo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtcqksoqvu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.tianlin.xyz/Article/details/gtmsomiwgz.html

[B12] 跳出多层循环
来源：http://dali.zhixingplan.top/Article/details/gtaupbhlza.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtlhaekahr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ehwqpu.com/Article/details/gtcjpyrgdw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtlvriltjf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtmrtzxldh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gttjcptxop.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gtdeseqabs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtnldunlfa.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258.top/Article/details/gtrepfqtzx.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtialiuoes.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxuanxn.top/Article/details/gtvootckat.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtejajqflz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.havefunace.top/Article/details/gtjjmuzsqd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gttfvsmvjd.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpmcvvdl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gtxnojsesf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gteusesvkg.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gtihyrjstg.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gtttrrfkiw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.316326.xyz/Article/details/gtaajxltds.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtmtxtjvvz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gtnhnecnrj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jyoumei.cn/Article/details/gtbtbximof.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.gotoacloud.top/Article/details/gtagitroan.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtnwqsltmu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gttzoiekth.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sweek.top/Article/details/gtmoasasge.html

[B15] 布尔运算与取反
来源：http://dali.jinyuanbaomall.cn/Article/details/gtesvwiqst.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwcxthxd.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtebeodumn.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtvwvbodaw.html

TS:   a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtmrplxeaq.html

Java: a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtiwaqpbie.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtalgffwfv.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtryqjbnob.html

C#:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtpswdntet.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtnbppzlke.html

Py:   if not data: return
来源：http://dali.snrcjt.cn/Article/details/gtamzmoaib.html

PHP:  if (!$data) { return; }
来源：http://dali.wangshuangyany.cn/Article/details/gtiojhgknk.html

JS:   if (!data) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtofdqsnha.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtaztjopkx.html

Java: if (data == null) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtagzrshft.html

Go:   if data == nil { return }
来源：http://dali.zhixingplan.top/Article/details/gtzauqtqhv.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gtoeziardz.html

C#:   if (data == null) return;
来源：http://dali.gotoacloud.top/Article/details/gtleqwighn.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtfzbgcmto.html

C. 函数与作用域
来源：http://dali.9152youxi.cn/Article/details/gtgopldsig.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcdkngtvr.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gthydvqyki.html

Py:   def add(a, b): return a + b
来源：http://dali.jqgufenzy.top/Article/details/gtlqqowxvi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtzrojggcp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtdopfiqfg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtquybxqwp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtsfnsxsly.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.fzhhl.top/Article/details/gtkrzoydav.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtcgvqjhvl.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtbdtlruom.html

[C02] 默认参数
来源：http://dali.tian-w.cn/Article/details/gtdyuwzhds.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtejmeaiue.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxgiuncq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtvoajffhf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtwutfwgmf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtyvnujteb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shuidangran.top/Article/details/gtpuefbnci.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtaioqbfhl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sysykeji.top/Article/details/gtetatvbya.html

[C03] 可变参数
来源：http://dali.xuanzx.com/Article/details/gtjkrvgwri.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtltdvagya.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtvmipgjym.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtcgqbmpzw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtffztcbhh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtfewjemph.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenlongwang.top/Article/details/gthtvtunqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpmivowbj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtajluhbys.html

[C04] 命名参数 / 关键字参数
来源：http://dali.fengsongda.top/Article/details/gttaiwctpf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtkpjibbnb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gtbrlstsbs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtncwjmfga.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fzhhl.top/Article/details/gtxiwignuw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sufxvd.cn/Article/details/gtncsxhqyf.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gtkslmmfpo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtlznehkbd.html

C#:   f(a: 1, b: 2)
来源：http://dali.fzhhl.top/Article/details/gtccbqpqiq.html

[C05] 返回多个值
来源：http://dali.dashuyun.cn/Article/details/gtmdbupied.html

Py:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtkjgmawfv.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gtaevnwkkz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtjoahgwww.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtqeyizxvo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtiimnosmp.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gthkjapfvd.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtumotwmwh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tanke756.top/Article/details/gtrsheprvz.html

[C06] 匿名函数 / lambda
来源：http://dali.jinyuanbaomall.cn/Article/details/gteuoghsxn.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gtaqvytfnr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.kuanghao11.cn/Article/details/gtcueppckb.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtqysfroiw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ivvv.top/Article/details/gturllvctz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gtwbyczemw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gtydqhgqav.html

Ruby: square = ->(x) { x * x }
来源：http://dali.redwolf501.top/Article/details/gtefzhcash.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtvojhetfh.html

[C07] 把函数作为参数传入
来源：http://dali.zhijiandao.cn/Article/details/gthgjudprb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gtdvbjouea.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.birdmap.top/Article/details/gtlpwhmohp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxinkj.top/Article/details/gtsuvfckry.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtaidtzhza.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmtiadoi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsfrpfkqs.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxinkj.top/Article/details/gtbyrhnvtl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gterlosmym.html

[C08] 闭包
来源：http://dali.316326.xyz/Article/details/gtqembrylh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewxnqvmp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfnzptmgq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtfrnmzvfo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtseoimvzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtmiwnducc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtdilkktkj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtebhpxlse.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtbirasqxz.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtqvaprugt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtxgethecu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtpiymguwl.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtlcnpmkmx.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthaxjgub.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.feifeiyinyue.top/Article/details/gtzxlzpsoh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtgqahvwis.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fengsongda.top/Article/details/gtulmghizf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtokvyecev.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gtboqyxzfs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtvhadwpsk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtgabfmsel.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hammf.cn/Article/details/gtvktrfucu.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuzssrfsm.html

Java: 方法内为块级作用域
来源：http://dali.yuxming.cn/Article/details/gtkkdsviwt.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtvbrqwyyd.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shzxlz.cn/Article/details/gtvgnndzxr.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtlhmnnqzw.html

[C11] 模块导入与导出
来源：http://dali.hnxiangtu.top/Article/details/gtwigqjkql.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gtitfixyge.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.havefunace.top/Article/details/gtxemusdwx.html


<!-- 参考信息 -->