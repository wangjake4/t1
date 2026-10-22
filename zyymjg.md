代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cucudq.cn/Article/details/gtkxmedfgo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gtquyclfhi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cucudq.cn/Article/details/gtexknyfed.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gtnhhznxwm.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhoulong.xyz/Article/details/gtmomwqaqg.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtiydxjflx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtiukjurfa.html

[A25] 字符串比较
来源：http://dali.ivvv.top/Article/details/gtgreibwnk.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtohpjkfzl.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.tian-w.cn/Article/details/gtzaaiiakk.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsiayeyst.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gtsrrfgipt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sxryk.cn/Article/details/gtybdxaosu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xylfe.cn/Article/details/gtawvtmerk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.feifeiyinyue.top/Article/details/gtmvabhiab.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpotwzdsg.html

[A26] 类型转换总览
来源：http://dali.guowangkeji.top/Article/details/gtsskjbipd.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hfpthk.cn/Article/details/gtzekeoipd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.vqdsnc.cn/Article/details/gthyjjtwdf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gogol.net.cn/Article/details/gtifqpavam.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zdqjudy.top/Article/details/gtwlbcsefa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtodjwnmmm.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.sweek.top/Article/details/gtvqmgxbfl.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtirqocwtt.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.svipenyu.cn/Article/details/gtfaigoywd.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfejjazug.html

B. 流程控制
来源：http://dali.yonumen.top/Article/details/gtwhkofukr.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtyyyvnkqf.html

[B01] 条件判断 if / else
来源：http://dali.hammf.cn/Article/details/gtnofpqjvw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtmnzcspsq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtahwqcsus.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gttnrdyxwc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtfwqzuiby.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfuuwehn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gtdgtsjcga.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ppjwa.cn/Article/details/gtadbauuvl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunufbsjp.html

[B02] 多分支 else if / elif
来源：http://dali.tianlin.xyz/Article/details/gtejbhnhde.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guannengcc.top/Article/details/gtfqapjoic.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gttfxbalai.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtmllpvmak.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtyjooezrb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtkiglqdcc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtpjqvmlfc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gtyomaojfw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gtgmmmkxwc.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtfkggnhnq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangshuangyany.cn/Article/details/gtxfkgsomo.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtiawnwdcx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtltjyzfhl.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtkllibaxg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtztvvxpbq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxadkspwf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gtnzmrwfzb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj202588.top/Article/details/gttzumdpqa.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtqgazleaa.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtbhfxcpbq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fzhhl.top/Article/details/gtebgjybft.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zdqjudy.top/Article/details/gthwodrkga.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtyrvkivzs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj202588.top/Article/details/gtjnzfjyvr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtzvvirhif.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhoulong.xyz/Article/details/gtgfboeryc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtrimwckxg.html

[B05] 遍历数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtvlrqfwlh.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtoeopzajh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ppjwa.cn/Article/details/gtjklnsdyv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtcddhsjjk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yvedp.cn/Article/details/gtmgfogxgl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiagwesxe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.9152youxi.cn/Article/details/gtlhrrtkia.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gthkytxjxx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nwbrower.top/Article/details/gtcthgyntv.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gticpdpcmy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhiwuduotai.top/Article/details/gtkjcufroy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nwbrower.top/Article/details/gtrcrubqmb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtsclmegvp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtxnhezzrc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jlsjyb.cn/Article/details/gtchgsuoup.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtiajdvriy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gtppsmsyez.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkjluzrkk.html

[B07] while 循环
来源：http://dali.chenlongwang.top/Article/details/gtcfiukbcb.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtjxkwnmry.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.wangdashe.top/Article/details/gtjznxdhfe.html

JS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtsselmmyk.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtjyxizgmf.html

Java: while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtwrfftiyr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtpysrnlna.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zycfv.cn/Article/details/gtkssetgbr.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gteuraoefp.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvcaqytwq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtoaivfdge.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtgsbayidj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gthcpefrfp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gttnqtdpsx.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtudaneruj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gtadozcgah.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtgrlxlrec.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtyakilgcf.html

[B09] break 与 continue
来源：http://dali.hammf.cn/Article/details/gtrszvljqk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.mhx1999.top/Article/details/gtrrvrqyqp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtdlopxayz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjwprjbu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gthsqumuxl.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtnvijjixo.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtzzembgjr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtqkahrfna.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtujbknxpt.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtxttyyvco.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dianchejie.cn/Article/details/gtbivwhyhf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.snrcjt.cn/Article/details/gtgininhwf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xziqi.cn/Article/details/gttluckpwm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtwbktxuqj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gtammzfesd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.nanxinkj.top/Article/details/gturxulloi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtrdjrjzvp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtihoaqlei.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gttiieyfkx.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhijiandao.cn/Article/details/gtuxixnzlb.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gttmdizzwt.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yangfankeji.com/Article/details/gttnenghnt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sxryk.cn/Article/details/gtwdkmjxat.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.chenzaomai.com/Article/details/gtltgblnjz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtyuqppwgg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nwbrower.top/Article/details/gtdrsvjmfd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hfpthk.cn/Article/details/gtihswgkyw.html

[B12] 跳出多层循环
来源：http://dali.cqqwz.cn/Article/details/gtpxezufyb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhongyouzk.top/Article/details/gtppeymnti.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dianchejie.cn/Article/details/gttmjdfajx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtlliaredt.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtkzfqjcsw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtupjqotcn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xziqi.cn/Article/details/gtobsdwuet.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gtxpnnvwjn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gttrptpoas.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtirplqxqm.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtytvaeuwm.html

PHP:  is_numeric($x)
来源：http://dali.yvedp.cn/Article/details/gtbjbsgnjw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtuhlxnajy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtgxoltfit.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gtzrtdwrnr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sxryk.cn/Article/details/gtsfjrfhgw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gtjnkbcapl.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtagjnncat.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtzrqsghug.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sufxvd.cn/Article/details/gtchmdapsj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuxming.cn/Article/details/gtlphjkpga.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gttapvuquq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozxmobga.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtyjvfbtek.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gtnxfqhhsp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dianchejie.cn/Article/details/gtftsoxlws.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtwvedksch.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtwidwxbcu.html

Py:   a and b or not c
来源：http://dali.tian-w.cn/Article/details/gtluatloyp.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtqmzsivxs.html

JS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtablnxkiq.html

TS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtfpsxwjyx.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtbcgyhlvq.html

Go:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gteoueavcu.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtnkyjexqz.html

C#:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtveztbhzc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.c1oappe.top/Article/details/gtxyowohjs.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gtxwvugidi.html

PHP:  if (!$data) { return; }
来源：http://dali.gotoacloud.top/Article/details/gtqqzesccf.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtluxacqgn.html

TS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtgcjhdurq.html

Java: if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gtspamvosb.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gtocrubblu.html

Ruby: return if data.nil?
来源：http://dali.daria6918.cn/Article/details/gtouetkpeg.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtvukwgfwa.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtlfnuerbz.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gtbmiapqie.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcedfioc.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtixnyesyd.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gtvfljefoe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtctewgbsg.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtibpflkyb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtxweeudck.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtfxrgnysq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtzmjpszwy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cdnleiting.top/Article/details/gttuldrhef.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtbijwpghd.html

[C02] 默认参数
来源：http://dali.redwolf501.top/Article/details/gtiecnrmsh.html

Py:   def greet(name="World"): return name
来源：http://dali.jinqigufen.top/Article/details/gtpmtnmyep.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cdnleiting.top/Article/details/gtuwauimsg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtorwpwiay.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gtgqruwdoj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtfnyiqrdb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtkyypqtxr.html

Ruby: def greet(name = "World") = name
来源：http://dali.sufxvd.cn/Article/details/gtdnpjhrpd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtopzksbvw.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtpvggwpvt.html

Py:   def total(*args): return sum(args)
来源：http://dali.vqdsnc.cn/Article/details/gtdomaxvwu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gtkqmveerv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gtucjcntuz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtgxuxfftb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj202588.top/Article/details/gtgaqeoecc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtbcdgdeza.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sxryk.cn/Article/details/gtpqzgwxzp.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gttyojcljp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnqzz.top/Article/details/gtvhoygkse.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gtufncraio.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xylfe.cn/Article/details/gtwszxtaal.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvkhigqo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shzxlz.cn/Article/details/gtvrrikzug.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtojqgscsv.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtvpgggofw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtgdhqkvqw.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtuudycikx.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtgegryevd.html

Py:   return a, b
来源：http://dali.cdnleiting.top/Article/details/gtwbtcjapn.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtrayyijir.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtvajdozkh.html

TS:   return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtmqftvmdx.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtrplphgih.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtgrcrcosv.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gtulmsptxs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yongpay.top/Article/details/gtwzripaad.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtewospupd.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gttffbgzep.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtysrsnsfn.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gtpprrckix.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.bjfxy.top/Article/details/gtacsqkoim.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtilmxfkpy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtvahsqark.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gttijlosmi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtttputbqs.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtqvdylkni.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.c1oappe.top/Article/details/gtkcbstumm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.fzhhl.top/Article/details/gtfmjuqdgp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gtpygxyaxm.html

TS:   arr.map(String)
来源：http://dali.birdmap.top/Article/details/gtlepzfjcj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.0kj1m.cn/Article/details/gtyieegvmw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtgrbaqeej.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtmanyfwas.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtcljfowuo.html

[C08] 闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtpcheymaj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yanxiufei.cn/Article/details/gtgvgyzbaz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gtvbxkmkdz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtjwnkbysj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtfkmzocqs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.0kj1m.cn/Article/details/gtwffgtqaj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yangfankeji.com/Article/details/gtwvfuccbb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtcvxyyqjn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtkhyedxbr.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gteyaqkpsx.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jqgfzy.top/Article/details/gtoupzhmmx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yonumen.top/Article/details/gtauixitva.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhbxlrsr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ehwqpu.com/Article/details/gttewajexf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cheryme.top/Article/details/gtnulwrghd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ppjwa.cn/Article/details/gtjvzeqdqp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtvmfahflt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gtzaopcyfl.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtiefscmwc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtjvtofmzh.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cashguo.top/Article/details/gtnwmrobsf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gtmyrcrssx.html

TS:   同 JS
来源：http://dali.zdqjudy.top/Article/details/gtzckcwepx.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtxdzosohx.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtkpctjiwq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gteuzqvxdj.html

C#:   块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilwnhlnv.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtbefxwbwh.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gtjmanmpop.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gotoacloud.top/Article/details/gtqgprprvm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkcloxhl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gtmdrvwrlz.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gtjskyhvat.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gteawffjrd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgufenzy.top/Article/details/gtwqdsuygg.html

C#:   using System.Text;
来源：http://dali.bjfxy.top/Article/details/gtwytjmibt.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gtndeidlmz.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gtnikhpcql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtwduytkrh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtfryaysqu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yongpay.top/Article/details/gtgefesjlo.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hfpthk.cn/Article/details/gtpzekeheg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbctdjxdr.html

Ruby: -> { puts "run" }.call
来源：http://dali.meibo888.top/Article/details/gthslkoada.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gtywtzxfuj.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhixingplan.top/Article/details/gtdozfrqgw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hammf.cn/Article/details/gtvpqikulj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxarisaqy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gtlfsibzko.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtyqkjyupo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtcmlgnugk.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtbwhezzgf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yonumen.top/Article/details/gtkrzsbilg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.guannengcc.top/Article/details/gtjhuzisml.html

[C14] 泛型函数
来源：http://dali.svipenyu.cn/Article/details/gtlfsovjeu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.fengsongda.top/Article/details/gtztaraisp.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtzldwvepk.html

JS:   // 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtodepvomk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinqigufen.top/Article/details/gteqymplwg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtzhklxixn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gtteyddsei.html

Ruby: # 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtenwbtrnc.html


<!-- 参考信息 -->