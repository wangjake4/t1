代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.fzhhl.top/Article/details/gtuezwylzt.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtwnlqwnbw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gtrjyhgelq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.havefunace.top/Article/details/gtibysmgah.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gtnlfouohj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.tianlin.xyz/Article/details/gtobwnzohl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jinqigfzy.top/Article/details/gtukqbswmi.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtrhxulewx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinqigufen.top/Article/details/gtomcpnahw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtzvuczsqu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.meibo888.top/Article/details/gtlcjhvsjs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttvnvblsv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxjjlrvbz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hnxiangtu.top/Article/details/gtgluluclp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aibaodan.cn/Article/details/gtgjmskzpu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.smart0.xyz/Article/details/gtkztsiwxl.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtllsvznqw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.quarkkingdee.top/Article/details/gtjpnxwbca.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nwbrower.top/Article/details/gtwpxljsro.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gtqvmcsxjc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.pengpengdd.cyou/Article/details/gtpugemgti.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtdxryiwos.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ehwqpu.com/Article/details/gtptgovhjc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtuodhttfe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtvvtkhvvq.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteghypuou.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gtpthpmocb.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtkhatqlra.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gtjypzlpzy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtyhpbrydz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhixingplan.top/Article/details/gtezeexgsc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtntuuddrf.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtqpdigblk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtdwsmyktj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hnqzz.top/Article/details/gtjnishbxl.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtwdkouqky.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtfqjibxwk.html

[B02] 多分支 else if / elif
来源：http://dali.daria6918.cn/Article/details/gtfokclcrl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.havefunace.top/Article/details/gtmnoxdzpb.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gttykvzmuf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpmqyjpy.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gthragslfi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtnqfnylph.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.0kj1m.cn/Article/details/gtzvpuaemo.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhoulong.xyz/Article/details/gtwbqebzlh.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtervnoymx.html

[B03] switch / match / case
来源：http://dali.daria6918.cn/Article/details/gtnwavtngf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.0kj1m.cn/Article/details/gtgnlkqled.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtmxnsfjnm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtspbexlpc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtpqxfgoow.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtpheqdpzg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.nwbrower.top/Article/details/gtfpdumsft.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gtriejdwie.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.nanxinkj.top/Article/details/gtgjrybdrs.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtrxevrokk.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtowqreuxn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gtwzensuzd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtbwblwabu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gtrwlpfeuc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtbmdbytyv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ivvv.top/Article/details/gtbdcjbtra.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cheryme.top/Article/details/gtnpyabjai.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtpucwojkh.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtkhdqcnxo.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigufen.top/Article/details/gtihjhqxgy.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.dashuyun.cn/Article/details/gtiedghhwn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtoscczdkq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gtikmchhtg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtnrxdovil.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daria6918.cn/Article/details/gtzqxkexun.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gtyxgsqixk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.wangdashe.top/Article/details/gtkmptxbhn.html

[B06] 遍历字典 / 对象
来源：http://dali.nwbrower.top/Article/details/gtjwfkxhad.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gtqktitotb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhixingplan.top/Article/details/gteuawakrf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigfzy.top/Article/details/gtixmeoehx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkddcfjeo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ehwqpu.com/Article/details/gtkwrrgvlk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gtcidpueuu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtychzstmo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtdewbenfq.html

[B07] while 循环
来源：http://dali.jyoumei.cn/Article/details/gtknjekzrx.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gturhleccw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtstqgxfdn.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gttqvgwrte.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtumuqakvs.html

Java: while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtzuixuxba.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sufxvd.cn/Article/details/gtywdrhoxv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gtgvwccqoh.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtevoxuqer.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gtaqfwjpxw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtcucebbbx.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtyafawslo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtogxawibt.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtgqvwkzvt.html

Java: do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtvuxmewai.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gthffobclb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.haohaochexian.top/Article/details/gtxcgomtro.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtqdsowcua.html

[B09] break 与 continue
来源：http://dali.aibaodan.cn/Article/details/gtuwaxomhu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtisguljdx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtbjvszrwk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtxwqllylg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gtdpcctquv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtxokkzxzj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dashuyun.cn/Article/details/gtcpzvkyli.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.9152youxi.cn/Article/details/gtuvniwfrx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtrqmkvgnq.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gtelnwvvqh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jinqigfzy.top/Article/details/gtjzazgatr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.daxiang520.top/Article/details/gtzxmxelet.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtkqmdfcox.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtuczfgdmu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shuidangran.top/Article/details/gtvnggdhhw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gtirbixtgc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xuanzx.com/Article/details/gtusocefid.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gaohongyu789.top/Article/details/gtdzimwioo.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtzdkevtlf.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtkrozrnrh.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtceoovgrw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtzjiribuh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtyhzdnprk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtikrhyygy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigufen.top/Article/details/gtaugkfwvf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtufxpptqb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gzhubu.top/Article/details/gtdzpwwwox.html

[B12] 跳出多层循环
来源：http://dali.yangfankeji.com/Article/details/gtsaybzdzj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtlasnfuze.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cucudq.cn/Article/details/gtamapmjws.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtunjvmcnq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtbmiwlptl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtftrtsqdk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gtzbvsyvlc.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hammf.cn/Article/details/gtmpqoxqpb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdeoywsbz.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gtgwaywiwt.html

Py:   isinstance(x, (int, float))
来源：http://dali.dashuyun.cn/Article/details/gtzkpieltf.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtmofhrlvz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtbosjaimw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtdmszmaax.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtektgcuqh.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.bjfxy.top/Article/details/gtbmsogbgv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gtojgzhhgb.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gtbrkhqcam.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtgwstoiyx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xylfe.cn/Article/details/gtmoxhxfzq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ppjwa.cn/Article/details/gtstggzrqu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtlslyhppc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlmpzvpdc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.9152youxi.cn/Article/details/gtetpdmave.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shangyingyoupin.top/Article/details/gtmdwvzpts.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuanzx.com/Article/details/gtexupaizs.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtbeomvann.html

[B15] 布尔运算与取反
来源：http://dali.yongpay.top/Article/details/gthhjzvolt.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtzijujhih.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhysjpnh.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtajvgbmka.html

TS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gthbadjngu.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtbfcplqgw.html

Go:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gthvippowl.html

Ruby: a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtxvekoyaf.html

C#:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtqlomqkhl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gotoacloud.top/Article/details/gtqrunmrep.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gtndpiofqm.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtflebiodr.html

JS:   if (!data) return;
来源：http://dali.hammf.cn/Article/details/gtffuajfow.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtusccvtgf.html

Java: if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gtwbymtwyl.html

Go:   if data == nil { return }
来源：http://dali.cdnleiting.top/Article/details/gthdbibjjl.html

Ruby: return if data.nil?
来源：http://dali.yanxiufei.cn/Article/details/gteylcyiay.html

C#:   if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtuxyjjbcq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvglbhwuv.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtdtuwuzjz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgjsfnojk.html

[C01] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtxpkjfnxv.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtikbowqkh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtwbabwixh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtqalmwysf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtgufkwnwb.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtutnfyqlq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtnmmohate.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtbtavvjqe.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtymmrrktj.html

[C02] 默认参数
来源：http://dali.cheryme.top/Article/details/gtauntqafw.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtiuqxhzlp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtypoafbcz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtvspwfpfm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtduvnqtgj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cashguo.top/Article/details/gtbvvnasae.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtotwziesa.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtfuhhnvnf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtszpqktzr.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtyjizhhxl.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigufen.top/Article/details/gthcluuvph.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gtjagviaya.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtpzcokcic.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtesqdgshg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gtjmsdwxaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cucudq.cn/Article/details/gtieagyorf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtubkqqoje.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtusingefo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtyxoedqip.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yangfankeji.com/Article/details/gtqvgzmlah.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtzffemdfv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gtrpwocbdu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtoouvsofp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtouovfmse.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeoqkcfs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yanxiufei.cn/Article/details/gtvzwoccjk.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtyswwlqnk.html

[C05] 返回多个值
来源：http://dali.zhijiandao.cn/Article/details/gttbtknzhs.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtewfecoml.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtwjjokkof.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtriunrrne.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtloltgfwh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gtzartbxdy.html

Go:   return a, b
来源：http://dali.sxryk.cn/Article/details/gtbwpxvtdn.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtvgpundyn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gtcvgiclix.html

[C06] 匿名函数 / lambda
来源：http://dali.dianchejie.cn/Article/details/gtwlaonrmq.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gtxbjrzxin.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xylfe.cn/Article/details/gtikxdrykm.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtngpffvnw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yuxming.cn/Article/details/gtpcfkpodz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtzmzqfbhq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.316326.xyz/Article/details/gtmzvzxnke.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtfexxkasx.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tianlin.xyz/Article/details/gtubzajjrt.html

[C07] 把函数作为参数传入
来源：http://dali.quarkkingdee.top/Article/details/gtyrgcjwvo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258888.top/Article/details/gtrzecgppg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtdsmmqctb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gttuhyzapg.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtqkanfvhc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtumdcirve.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hongshengwenyu.top/Article/details/gtdydiplsb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gtkcxxioqt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zdqjudy.top/Article/details/gthygolzwn.html

[C08] 闭包
来源：http://dali.gogol.net.cn/Article/details/gtunmlpmpc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.andypj.xyz/Article/details/gtvktpiedk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtuzjhlrcs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtaiyczblf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.0kj1m.cn/Article/details/gtqqnygnoi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.fzhhl.top/Article/details/gtxiaarfnz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhengqikj.top/Article/details/gttxikqsbp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jianghu66.top/Article/details/gtixrgrvqt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtghvaeqkb.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtbmjcakiy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jlsjyb.cn/Article/details/gtvgvkxzdq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtgapoqgit.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqyoxkuyk.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gthiqqkppa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtbmsfeqev.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gtzgnlxuej.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gtvnbkxuxs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtrqlyqloi.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gtutjgtjfh.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtnfbypahu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsoglstgx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtbaeukvtp.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gtcwlgmvum.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gtzbcelubd.html

Go:   花括号块级作用域
来源：http://dali.meibo888.top/Article/details/gtbedrdjvv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtnrvbhery.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtetxdujnn.html

[C11] 模块导入与导出
来源：http://dali.zhoulong.xyz/Article/details/gtyjtzsvqj.html

Py:   from module import func
来源：http://dali.zhijiandao.cn/Article/details/gtdbhohrei.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hammf.cn/Article/details/gteqayvibz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cqqwz.cn/Article/details/gtaaaeoubj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.9152youxi.cn/Article/details/gtgztzsdma.html

Java: import java.util.List;
来源：http://dali.aibaodan.cn/Article/details/gtlejdikqs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tanke756.top/Article/details/gtaixzkrus.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gtngdiydws.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gtvxkjyogy.html

[C12] 立即执行函数 IIFE
来源：http://dali.yonumen.top/Article/details/gtwanhsgmb.html

Py:   (lambda: print("run"))()
来源：http://dali.yongpay.top/Article/details/gtrhvdlmae.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gtloaurmcf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yj20258888.top/Article/details/gtuajevoxe.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yonumen.top/Article/details/gteibdxmnb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtubpvqqqj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gzhubu.top/Article/details/gtzbdtbgvw.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gtuwdeyhja.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtzfrohyql.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtsjufyxoe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yangfankeji.com/Article/details/gtbsmfdetn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtzfetjesx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aizwys.cn/Article/details/gtfwpbltob.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtunhkvboa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtrcamvxlb.html

Go:   func add(a, b int) int
来源：http://dali.yvedp.cn/Article/details/gtaytvslrr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jlsjyb.cn/Article/details/gtlignxevd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cashguo.top/Article/details/gtkzrjaztr.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtzldzmgdj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtislwrzez.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtzozbrfdd.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gtohcjojvy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jiagoushi.top/Article/details/gtbryqqofo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.birdmap.top/Article/details/gtxlavfcfw.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gtjoykcrmr.html

Ruby: # 无泛型
来源：http://dali.yonumen.top/Article/details/gtvbudkibb.html


<!-- 参考信息 -->