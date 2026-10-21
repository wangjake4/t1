代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.shzxlz.cn/Article/details/gtrrhbzvju.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtaxrsazfy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtbrfdfebm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnajisdu.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gtzqnzkpjp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daxiang520.top/Article/details/gtjloblenu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ppjwa.cn/Article/details/gtkvsxlmoy.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtoqlcinnj.html

[A26] 类型转换总览
来源：http://dali.iojbl.cn/Article/details/gtarvybndn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuetiantiany.cn/Article/details/gtedlcnsms.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gtqgteprur.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gttzeajmct.html

TS:   Number() String() Boolean() x as number
来源：http://dali.zhiwuduotai.top/Article/details/gtkywsbcob.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gteyczuqzh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ybcxt.top/Article/details/gtypmzhjbn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhiwuduotai.top/Article/details/gtuxgpaftu.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hywenlv.cn/Article/details/gtxeglzgoo.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtztdjmxal.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtopbghnjf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtgwuafdbb.html

[B01] 条件判断 if / else
来源：http://dali.sxryk.cn/Article/details/gttnsaqplc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.mhx1999.top/Article/details/gtvkprdtbh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyjdilan.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gthcfrmxst.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtiwfatiid.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gteldbgtix.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.nanxuanxn.top/Article/details/gtftwitxfm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.guannengcc.top/Article/details/gtycucqumt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtuxdgdfdc.html

[B02] 多分支 else if / elif
来源：http://dali.c1oappe.top/Article/details/gtxihmfhck.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangdashe.top/Article/details/gtaeuexfbz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtlpurgufr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtyngqavhb.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtxdndlltq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gttckbqqll.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtqslurznc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.iojbl.cn/Article/details/gtxwybppiv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gtoegkjijp.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gtckrcdrdc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gtonnccadx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gthzhyrquz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtvtdmlmif.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gteqilrnvc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gtcpkaefra.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gtwrqdttlw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.andypj.xyz/Article/details/gtogjzrwny.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtuedolemx.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gthvxaknzp.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtewuuwedb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwkhoqtqg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtswnkqdzc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtnyuslyic.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sysykeji.top/Article/details/gtoqyobakm.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gtnplmqifq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gogol.net.cn/Article/details/gthaiawpkz.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtpjoectsv.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtnfjpiinp.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtejdmgrar.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pycfn.com/Article/details/gtmqeeibpa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jqgufenzy.top/Article/details/gtrrihxjfq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtiknkbhbw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtynenhlrn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gtcugtidoq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cheryme.top/Article/details/gtkykfrazk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gtealjwxim.html

[B06] 遍历字典 / 对象
来源：http://dali.yvedp.cn/Article/details/gtibrmmzcv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.redwolf501.top/Article/details/gtcrwbnyag.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.9152youxi.cn/Article/details/gtdghwtieo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtpiktjkhe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtltaxzlof.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gtxfugczdc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yanxiufei.cn/Article/details/gtxppvlhym.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtcpxusntj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gturqnemyv.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gtaehrcfyk.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gtzczanevv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.c1oappe.top/Article/details/gtuugaaydf.html

JS:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtdbulhhzg.html

TS:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtvnpvnzku.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gthwshrppx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gttiapfvux.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xuanzx.com/Article/details/gtlqznitji.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gtoolzhnhv.html

[B08] do-while（至少执行一次）
来源：http://dali.shangyingyoupin.top/Article/details/gtcctonimd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtnpdeenhm.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtdvlqxnzh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gthudrwxtm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtcdvtnawj.html

Java: do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtfxkcljru.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sufxvd.cn/Article/details/gttujnmnai.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtdeminuop.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtddeesevu.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtmprdglba.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfjvmxjmz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtlvuvscfr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gteyxsykej.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcgalomdn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtgyrmprkr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtnyfxxxgy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsnypygbs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbyejsltu.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gtphvbjjwb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yonumen.top/Article/details/gtzirtjfkf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtlijncjku.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtmvsymyqi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtbutiynfa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtxsjqkknu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gthpgktddp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nanxinkj.top/Article/details/gtoruuyusq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtpquflsax.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtsxaiuibx.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gtqvuzxbad.html

PHP:  range(0, 10, 2);
来源：http://dali.xylfe.cn/Article/details/gtdklklmij.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtryrqnkzd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtslchviel.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtbjrsajer.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gtsmmbtyos.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gtlssgohwf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtvibuozrt.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtaamqwqwi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtgxgamaot.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcgajopf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtnbsouecu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtjivmgilm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtqywlqmxr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tianlin.xyz/Article/details/gtsytyckge.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gtssphrjyk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtdhprczgm.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gtkrcwstjk.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtofwgvxbz.html

PHP:  is_numeric($x)
来源：http://dali.chenzaomai.com/Article/details/gtamzwdkyi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtmqwkiown.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtyavcmnff.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gtcmwfgnjb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gthtmiyxzv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yuxming.cn/Article/details/gttmrkxvjr.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gthpwkcqeh.html

[B14] 判断值是否在集合内
来源：http://dali.haohaochexian.top/Article/details/gtnlswaxfi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.haohaochexian.top/Article/details/gtgacsaswc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtxivselaz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtqltcymim.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtpnwvczwv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.wangdashe.top/Article/details/gtywqyrjtf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jlsjyb.cn/Article/details/gtrlmqvqbb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ppjwa.cn/Article/details/gtbxznfjoz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxryzzym.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtjhdxdsec.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gtrsiffxhj.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtsqffxbxd.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtzihbhhpj.html

TS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtqrhdyxst.html

Java: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gthvsrudtt.html

Go:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtphhroran.html

Ruby: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtwpibylkh.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtlcitvuum.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cucudq.cn/Article/details/gtbsuiwjhm.html

Py:   if not data: return
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrtwumje.html

PHP:  if (!$data) { return; }
来源：http://dali.mhx1999.top/Article/details/gtxutxhrfj.html

JS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtjmbynwxu.html

TS:   if (!data) return;
来源：http://dali.jinqigfzy.top/Article/details/gtiqddxwvm.html

Java: if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtwbabyqpq.html

Go:   if data == nil { return }
来源：http://dali.guowangkeji.top/Article/details/gtlwdnfrng.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtkbkfzais.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtlvvworrn.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtyvssauru.html

C. 函数与作用域
来源：http://dali.hnxiangtu.top/Article/details/gtumbjrgjg.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtelqtciqz.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtllnjcmin.html

Py:   def add(a, b): return a + b
来源：http://dali.shangyingyoupin.top/Article/details/gtpyoblwwk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dianchejie.cn/Article/details/gtruhqdnvf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtnijqqnnn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtwqhujdss.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtwtiwwssf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtfvcjegml.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangshuangyany.cn/Article/details/gtpdfidljz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdwabyexg.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbwnoeqc.html

Py:   def greet(name="World"): return name
来源：http://dali.gogol.net.cn/Article/details/gtbfptlgek.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtnisyiiwk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zdqjudy.top/Article/details/gtroorkoss.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gttsubuntd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.andypj.xyz/Article/details/gtpsxcvhdg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.sweek.top/Article/details/gttxaexuyo.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtabsxnsvv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shangyingyoupin.top/Article/details/gtexlqxdkx.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gttgbfqcgg.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtgtkdnfev.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhixingplan.top/Article/details/gtrsnekwdi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtxpdasdvn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtdtandegy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gzhubu.top/Article/details/gtbtxeqhxe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtdqohyvcr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtlvxvoctl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtbtfpfwbs.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtarqbonag.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtilssacga.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtpsduzzds.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtwskvylsi.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtxciepymk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gtbryyvbkj.html

Go:   // 无：用配置结构体参数
来源：http://dali.pengpengdd.cyou/Article/details/gtyhtkaunl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtybqhvsin.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtpsmpfcvc.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtzljlsykz.html

Py:   return a, b
来源：http://dali.yuxming.cn/Article/details/gtngnbzvck.html

PHP:  return [$a, $b];
来源：http://dali.ybcxt.top/Article/details/gtqlogvyzk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtrblioiit.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtrtelgqpl.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ivvv.top/Article/details/gtgeznnhaw.html

Go:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtevovghzg.html

Ruby: return a, b
来源：http://dali.yueranfly.top/Article/details/gtzlvyhphz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwswyern.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtblaqefgj.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gtseugmarh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenzaomai.com/Article/details/gtoaqtlmch.html

JS:   const square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtlcityljs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtrxpwgwng.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtujrevxtg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtnzzzqyby.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtrzrxdrij.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtwkvzxeck.html

[C07] 把函数作为参数传入
来源：http://dali.gaohongyu789.top/Article/details/gtnniruqsq.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtzifsmzus.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtekwdtwek.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yueranfly.top/Article/details/gtzkhubtyx.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gttigdzltb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtvgxuxrof.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtckecdvdh.html

Ruby: arr.map(&:upcase)
来源：http://dali.tian-w.cn/Article/details/gtmblqfjuq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtpktajkmb.html

[C08] 闭包
来源：http://dali.redwolf501.top/Article/details/gtqnhmkfyr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jqgufenzy.top/Article/details/gtfwmsljxs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jqgufenzy.top/Article/details/gttbiuqodq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtxsdpwuub.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hongshengwenyu.top/Article/details/gttqseqkhm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258.top/Article/details/gtgpgzkzbt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuxming.cn/Article/details/gtochryjca.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrqdzwwj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtsrlkvqsx.html

[C09] 递归
来源：http://dali.chenlongwang.top/Article/details/gtacaepvlv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtyscjbyjq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvynehlj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtulcnjpsq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.mhx1999.top/Article/details/gtawofcgyo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtqyaepubi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuetiantiany.cn/Article/details/gtgvohhpqz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gtknrfawkd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.daria6918.cn/Article/details/gtuntaixsf.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gtakghatmz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yonumen.top/Article/details/gtzizqhlvm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gtalkifuzg.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtsujdkpcr.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdoimoqsp.html

Java: 方法内为块级作用域
来源：http://dali.316326.xyz/Article/details/gtallwrjel.html

Go:   花括号块级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtjtcskhai.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtlvdwoarf.html

C#:   块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtzgkriiyo.html

[C11] 模块导入与导出
来源：http://dali.redwolf501.top/Article/details/gtgqafgaow.html

Py:   from module import func
来源：http://dali.xylfe.cn/Article/details/gtxsvimtcm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gtvulbwwcm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtnnuvtare.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gtahjhpdlk.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtiiceotpj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.shanyushiyangtech.top/Article/details/gtevlqofpl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtiijmmfdc.html

C#:   using System.Text;
来源：http://dali.yuxming.cn/Article/details/gttgnvhove.html

[C12] 立即执行函数 IIFE
来源：http://dali.redwolf501.top/Article/details/gtesmknvgv.html

Py:   (lambda: print("run"))()
来源：http://dali.jinqigufen.top/Article/details/gtvvgylmym.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtebagkdzm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxuanxn.top/Article/details/gtnfhfeivy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gtqlaqjjkb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gttrpbvjrg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.316326.xyz/Article/details/gtjxsgdaoz.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtstgjhlck.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.guowangkeji.top/Article/details/gtvztdkeuy.html

[C13] 类型声明 / 类型注解
来源：http://dali.hongshengwenyu.top/Article/details/gtqlejwglf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gtpfwrciqb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtddklzmtc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtntdumtly.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtslkghakd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gthacaqbig.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gtyhsfwjuc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gtotxqquuz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhoulong.xyz/Article/details/gtxsnnjtow.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gtyrohpjoj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtdjmiwxvv.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttmvghpz.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtxgxwtvxj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.havefunace.top/Article/details/gtcrhavdmy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtfmpjqxfz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gtgeyxldlg.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgifawkgp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtgeuoiezw.html

[C15] 解构 / 展开参数
来源：http://dali.zdqjudy.top/Article/details/gtxrmmpafr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtzsfgphiy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xylfe.cn/Article/details/gtjtmxhzst.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtpayavbeh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtvdjebuwp.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtrnvwigln.html

Go:   // 无解构
来源：http://dali.hysaishi.cn/Article/details/gtcujmmjks.html


<!-- 参考信息 -->