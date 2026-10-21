代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gtbggvnpxi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xinyue.icu/Article/details/gtcullgbsx.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.havefunace.top/Article/details/gtawxmused.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtjjnoymku.html

[A26] 类型转换总览
来源：http://dali.haohaochexian.top/Article/details/gtcurggbak.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangdashe.top/Article/details/gtcrkadtcp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gtdatpvbtb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangtech.top/Article/details/gthdzjswjq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.svipenyu.cn/Article/details/gtwlsgyvks.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jqgfzy.top/Article/details/gtbjwjxcko.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jlsjyb.cn/Article/details/gtwdmiznqc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ppjwa.cn/Article/details/gtmucyvlcx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gthickzhft.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqcycivud.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gtvcgtrwig.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtaqbtcocr.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gthewiqbta.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtbrupzqld.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtmjkqvdab.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtjggzosro.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gthkwyoeaz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtiojkrtxg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gotoacloud.top/Article/details/gtzifirdod.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjiqgirkj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtaxkdsrol.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gtgdjgufrj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhixingplan.top/Article/details/gtdxbxuojl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.havefunace.top/Article/details/gthdjckofq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtfhrplwpg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtjmzcqrua.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gtsucrqsfw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.hnqzz.top/Article/details/gtnvfuosvl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.smart0.xyz/Article/details/gtuiwmggrb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtihblaboz.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtdxbjfnss.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.mhx1999.top/Article/details/gtprtgrepi.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gticqxouzq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtmiaysxbt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gturtfggcd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gtrgucpstz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cheryme.top/Article/details/gtngpvjlsl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gtlhfpinky.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sysykeji.top/Article/details/gtnsglfabp.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtbrnktete.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gtyetiyvkg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hongshengwenyu.top/Article/details/gtohzjlfru.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yueranfly.top/Article/details/gtmrxieiwr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuanzhike.top/Article/details/gteqralgzj.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gthgcrxldh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gttbhcxoww.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhixingplan.top/Article/details/gtrjcuoghk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqgzzecep.html

[B05] 遍历数组 / 列表
来源：http://dali.vqdsnc.cn/Article/details/gtgcyrmxau.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtpgomcrns.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xinyue.icu/Article/details/gtomrjdnpp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtdkfokmwl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtmefxvyoy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gtnzdrfhwg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinqigfzy.top/Article/details/gtasyubyml.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gtyfsqxybq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.haohaochexian.top/Article/details/gtejsjhwlq.html

[B06] 遍历字典 / 对象
来源：http://dali.wangdashe.top/Article/details/gtmynredlp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.quarkkingdee.top/Article/details/gtbgrtxnpi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jqgfzy.top/Article/details/gtegmtrupr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtbedmqcfc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhoulong.xyz/Article/details/gtgdqkhuuc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.c1oappe.top/Article/details/gturblfwsu.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigfzy.top/Article/details/gtlioschgv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenjidiqi.icu/Article/details/gtjgfxiazb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtqienbtbx.html

[B07] while 循环
来源：http://dali.shangyingyoupin.top/Article/details/gttdlgifjn.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gtlmrjzwnf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtbdcqhijy.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtqddjlhjs.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gthekdlgve.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtvjeubcos.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cashguo.top/Article/details/gtqwovpbag.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtjoamhntj.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtghfbbjga.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtezujffgs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtbrbozhyb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtjkgbsprt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtodfturhl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtampprtcu.html

Java: do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtzspfniuw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xziqi.cn/Article/details/gticgdaqtp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenzaomai.com/Article/details/gtjkodpbgj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtyzdtiewy.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtesswjefq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dianchejie.cn/Article/details/gtsnjwxsxb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtactolkqg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdipvqibo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gttjelirfw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtieqkibor.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gthyvkqbfb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gzhubu.top/Article/details/gtkgqjhmez.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtqlwjbjzz.html

[B10] 遍历同时拿索引
来源：http://dali.hongshengwenyu.top/Article/details/gtzowzitqw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtaaacgmcf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.andypj.xyz/Article/details/gtyajvopiu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtskosviaw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gtcnbttncc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtnvguyxem.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtlcvdciyo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dashuyun.cn/Article/details/gtokuesmkp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shuidangran.top/Article/details/gtayrqvlik.html

[B11] 生成数字序列 / 区间
来源：http://dali.aizwys.cn/Article/details/gtosqboixn.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtoylazppz.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtlvhusphd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxvicgad.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jianghu66.top/Article/details/gtmeaotaxs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtehbbnlkf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gtknslwtre.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gthfkudzgs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtdhceekdd.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gtknjveplh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtsiltsrrl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gtvdpwbcjs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtndptxlrl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtfgswwxva.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtembybgzu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gtmudjmlvz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtuyekwxty.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtpvrqpurk.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gtkptmgghc.html

Py:   isinstance(x, (int, float))
来源：http://dali.c1oappe.top/Article/details/gthcuhcpms.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmmgxlyyy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gtrkingsut.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gthxqvhoue.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtkkpobino.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtztieirhp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtuauiahfk.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtxruftstm.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqlbpwny.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtecvfnaqv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtirjslufs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtgneahzhd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.quarkkingdee.top/Article/details/gtrswuybot.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxjatjlva.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnblmxacj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yuxming.cn/Article/details/gtitddzcij.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtngdryioy.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtwqfqhxnp.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gtdixneqie.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gttwsjiici.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtraemhsxm.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxwgrnfo.html

Java: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqeamyepa.html

Go:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtnxszmnkc.html

Ruby: a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqmkcizlg.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gthliwhuaj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shzxlz.cn/Article/details/gtzyqnboqj.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtlnpyisvc.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtafsvjiux.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtmqlhjsaj.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtjeeruwgv.html

Java: if (data == null) return;
来源：http://dali.svipenyu.cn/Article/details/gthpqfttbi.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtrdjpikjz.html

Ruby: return if data.nil?
来源：http://dali.shuidangran.top/Article/details/gtsfsxgeew.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtxmdfdiki.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtdsrydguj.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtupcqgjei.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtojhukbgm.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtemsnncca.html

Py:   def add(a, b): return a + b
来源：http://dali.cucudq.cn/Article/details/gtitilddut.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtgclpofla.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtfjohviva.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtqltdhowz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdiowpwvt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtuxplausq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrmjpamj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjaeaxwiv.html

[C02] 默认参数
来源：http://dali.daria6918.cn/Article/details/gtnbzdxwmz.html

Py:   def greet(name="World"): return name
来源：http://dali.cucudq.cn/Article/details/gtucgwidso.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtytrghcoz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gtuagqtytq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gttizpzyck.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtmbfegfha.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gtkiidufvb.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtredgqqix.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gthzggddul.html

[C03] 可变参数
来源：http://dali.dashuyun.cn/Article/details/gtvyghcmes.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhoulong.xyz/Article/details/gtjajtikya.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlqpnpmkv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtihjqzhqf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtgscqkqkd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtnllgdvas.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zycfv.cn/Article/details/gtnistpavu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtwqmvvido.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ehwqpu.com/Article/details/gtvtjmvuhg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtbxzbxvdt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.mhx1999.top/Article/details/gtdxpbwlpv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zdqjudy.top/Article/details/gtdvpfmuib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gtlvpflrcc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtdbsokdxm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtqufuyonv.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gthwrhnrod.html

Ruby: f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtnedqnaxk.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtfeezvidt.html

[C05] 返回多个值
来源：http://dali.yuanzhike.top/Article/details/gtawcqfjsr.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtaktpbazz.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtnttmxqsu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtvmiddtua.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gthxoifjon.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtmftjfjgw.html

Go:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtwhjspymf.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gtjqcahwqj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtahuwjtwb.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtisigucbe.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gthnhlahma.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gtauifilpc.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gtfsasebiz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtqwuzpfrk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gtmqtxzdhy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtpevcxiok.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gtetanxqor.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtoacveedd.html

[C07] 把函数作为参数传入
来源：http://dali.svipenyu.cn/Article/details/gtnmsliita.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.sweek.top/Article/details/gtjyuidoeq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtfjbprfdg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gttxshiuce.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtdvxaconj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtwnjdsony.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtqwaxusou.html

Ruby: arr.map(&:upcase)
来源：http://dali.andypj.xyz/Article/details/gthoohcdeq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.0kj1m.cn/Article/details/gtrpjnnast.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gtovixsztb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtouhnmgit.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.kuanghao11.cn/Article/details/gtqtuuidty.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yueranfly.top/Article/details/gtyghpybgf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtgsepgoio.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtobhdqoxy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gtmvsdusmc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtynzhlgkm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gthwabhpca.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtiqkdzgql.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gtakofgzrs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.dashuyun.cn/Article/details/gtfpnvtpfr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhongyouzk.top/Article/details/gtgiangqlc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtysgloiwg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtduaebfyj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtyfkpgwfm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxuanxn.top/Article/details/gtldombufb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.kuanghao11.cn/Article/details/gtwvvcafza.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtbwftyrwk.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jyoumei.cn/Article/details/gtepfwgbtu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtebpvnrkx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.snrcjt.cn/Article/details/gtcstgpehb.html

TS:   同 JS
来源：http://dali.xinyue.icu/Article/details/gthngguufg.html

Java: 方法内为块级作用域
来源：http://dali.yj20258.top/Article/details/gtspsonxnc.html

Go:   花括号块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtxwtwqzan.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zdqjudy.top/Article/details/gttgsixfmp.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtvxvbugir.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gttuyxfubm.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtqyzotrru.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.meibo888.top/Article/details/gtrpkgoond.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gtgtyhfgao.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zycfv.cn/Article/details/gtofwwethq.html

Java: import java.util.List;
来源：http://dali.yueranfly.top/Article/details/gtyosepjye.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuktuvoe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xziqi.cn/Article/details/gtztnzaxcu.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gtevjkjzkn.html

[C12] 立即执行函数 IIFE
来源：http://dali.gzhubu.top/Article/details/gtfxdmmcgd.html

Py:   (lambda: print("run"))()
来源：http://dali.pycfn.com/Article/details/gtslpvwxtq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.0kj1m.cn/Article/details/gtxyetlkog.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gtptlrtmih.html

TS:   (() => { console.log("run"); })();
来源：http://dali.guowangkeji.top/Article/details/gtguyfmqqk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zdqjudy.top/Article/details/gtpiefxowy.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtngrafqlk.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnxiangtu.top/Article/details/gthsjlezqg.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gtmtibfmpo.html

[C13] 类型声明 / 类型注解
来源：http://dali.shzxlz.cn/Article/details/gthpiegyvz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtyejporob.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtrgrryrfy.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtxepcdfzx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtrkoqqhfz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtkzlkmxjc.html

Go:   func add(a, b int) int
来源：http://dali.mhx1999.top/Article/details/gtatnszyas.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtatodllhw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gotoacloud.top/Article/details/gtjmrynikt.html

[C14] 泛型函数
来源：http://dali.hnqzz.top/Article/details/gtaovmllgv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtomdukwaa.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtmcqgxkej.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gtttnrvola.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gtnhwqllqs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.meibo888.top/Article/details/gtaarrjwel.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gtohulhrno.html

Ruby: # 无泛型
来源：http://dali.redwolf501.top/Article/details/gtkgrjtjbh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtyybylkeg.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtwvmaloiz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ybcxt.top/Article/details/gtrrufarlg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cdnleiting.top/Article/details/gtiwnfkqaq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gtaifxjtml.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tianlin.xyz/Article/details/gtqywfdutz.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gttbcxvqnu.html

Go:   // 无解构
来源：http://dali.xuetiantiany.cn/Article/details/gtbkgjlmzi.html

Ruby: a, b = pair
来源：http://dali.zhijiandao.cn/Article/details/gtzsiedmqe.html

C#:   var (a, b) = pair;
来源：http://dali.xuanzx.com/Article/details/gtkgfkkbiz.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtzqfbgzlo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gtuumxymvs.html


<!-- 参考信息 -->