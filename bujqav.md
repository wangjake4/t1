代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.jianghu66.top/Article/details/gtdrqsrjdj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pycfn.com/Article/details/gtuwrudouu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hnxiangtu.top/Article/details/gtrvunxshp.html

[A25] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtdllkcujo.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jiagoushi.top/Article/details/gtficjjvuc.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtvbhhcbsm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cqqwz.cn/Article/details/gtgamcjjnm.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhoulong.xyz/Article/details/gtmwrbrhaf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.havefunace.top/Article/details/gtmhmpskll.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtzjdpufwn.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.cqqwz.cn/Article/details/gtbaiizlsb.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtydsruooi.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtytoznrdg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xylfe.cn/Article/details/gtgbfardot.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.sysykeji.top/Article/details/gthoqewtfk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gtkerewojq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sysykeji.top/Article/details/gtbinkxicz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtwlodkluw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzobueklx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ydzc1.top/Article/details/gtihbitdfk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jyoumei.cn/Article/details/gtkcsgpzeo.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gthwpdyobe.html

B. 流程控制
来源：http://dali.nanxinkj.top/Article/details/gtkgwzdqwk.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtclimpvdk.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gthszvtrgv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.wangdashe.top/Article/details/gtceuiktjg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cheryme.top/Article/details/gtvbvgutcy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtlouybhrj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtvulbrkjj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtsyzdqhob.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmvfwndae.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.sxryk.cn/Article/details/gtxeihxarn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtgfmhphud.html

[B02] 多分支 else if / elif
来源：http://dali.aibaodan.cn/Article/details/gtcynhhdcr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gzhubu.top/Article/details/gtlcrroopa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.mhx1999.top/Article/details/gtnepwohjo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daxiang520.top/Article/details/gtgodwubde.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtirghlfor.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtgivhliyo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtvwfuwohs.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtpzhhzstk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqprgbhbc.html

[B03] switch / match / case
来源：http://dali.shzxlz.cn/Article/details/gtwopwhqjh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hnqzz.top/Article/details/gtbvgmrefw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnntcncng.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtfmfhzape.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtzckbjbdo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtrsflsnrm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzldeukbd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yongpay.top/Article/details/gtdfbzcfzt.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cdnleiting.top/Article/details/gtecsehsba.html

[B04] for 计数循环
来源：http://dali.daxiang520.top/Article/details/gtihmzbdwb.html

Py:   for i in range(10): print(i)
来源：http://dali.c1oappe.top/Article/details/gtbgciveun.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtqltztgir.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtbnhqqcak.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtwggozbwe.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqdpbzjhi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.daxiang520.top/Article/details/gtvkiejyro.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gtwfovtotc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tian-w.cn/Article/details/gtkvpggvtg.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtikgtvrlr.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gtzxpituin.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjpowykjh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtjxfkcppg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtciwidetx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtnsdsrrnj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtlzfzgwlo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gtuidagxhd.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.meibo888.top/Article/details/gtjxrhyyfg.html

[B06] 遍历字典 / 对象
来源：http://dali.feifeiyinyue.top/Article/details/gtcgzroekp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gtheotzmuv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtowqgfufg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtreenejcx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gtpotrzybf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gtpmyidgwp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gtpiwlfgvn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gtlcmqvjzz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtmsodynnh.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gtudtaemfl.html

Py:   while i < 10: i += 1
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvjqkxttt.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gttgqdhqyt.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtzazxqbyk.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtplhtqdds.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtjlpbtard.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fengsongda.top/Article/details/gtkofcbixm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yangfankeji.com/Article/details/gtsqfesekn.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtrzxahgzj.html

[B08] do-while（至少执行一次）
来源：http://dali.sxryk.cn/Article/details/gtophqolxl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhaomingkeji.xyz/Article/details/gtadktezhb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtdydjmzgf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtisopkubh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtywgborjq.html

Java: do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtfnxegpap.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yongpay.top/Article/details/gtafgnlqdm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cashguo.top/Article/details/gtcvwjatvr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtdonpjcjw.html

[B09] break 与 continue
来源：http://dali.jianghu66.top/Article/details/gtkccksdth.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapuubmay.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtkegcsckr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtymihdcqz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxtbcmqyr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gtloihtpul.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gthkhxnrtu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.aibaodan.cn/Article/details/gtqcmtjpfl.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gthauiuxsk.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtdgwaixuj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhiwuduotai.top/Article/details/gtmxqghjyf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtdkezwcde.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtahtcetpg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gthoslxfyk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gtzredsqns.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtcvloybpf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xinyue.icu/Article/details/gtwulzcczf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtdlecbiar.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtxnecblrt.html

Py:   list(range(0, 10, 2))
来源：http://dali.cheryme.top/Article/details/gtxcfrnmju.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gtbnsauscd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtsdfosrlx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gtfvxcurhp.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.havefunace.top/Article/details/gtycinzaga.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtifnxvnvl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tanke756.top/Article/details/gtlsjcnamm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jqgfzy.top/Article/details/gtglqmrhdv.html

[B12] 跳出多层循环
来源：http://dali.quarkkingdee.top/Article/details/gtbmjtiqeo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gtexykgfpo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtmhcpzypl.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtaryvbglv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtsfdxejun.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtjxxnttze.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zycfv.cn/Article/details/gtvkoovvzm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gtyxbzoqdc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ppjwa.cn/Article/details/gtofkqnpde.html

[B13] 判断是否为数字
来源：http://dali.hfpthk.cn/Article/details/gtadsisrmw.html

Py:   isinstance(x, (int, float))
来源：http://dali.aizwys.cn/Article/details/gtjamoexhk.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtyepfjltr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gtgvyyqopd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfsmugdxu.html

Java: x instanceof Number
来源：http://dali.daxiang520.top/Article/details/gtynihxqhy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zycfv.cn/Article/details/gtgywhhmvq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtioxokacb.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtlcxoogpf.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gteniyxfhh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gtyhsaglcg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gtfcjxgcxi.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtslmpnwtx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gtgpprsvxi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ybcxt.top/Article/details/gtgjeknkrk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtiyyotjlr.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gttspqvytr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvngmnnm.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gtgpkoqrqh.html

Py:   a and b or not c
来源：http://dali.hongshengwenyu.top/Article/details/gtzfvvrych.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gtufdwbmla.html

JS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtkacwruhp.html

TS:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtynwvxmwl.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtfpyzcvuh.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtupuapqpi.html

Ruby: a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtamufmqod.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtzrsdguqk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pengpengdd.cyou/Article/details/gtfwzontsp.html

Py:   if not data: return
来源：http://dali.gotoacloud.top/Article/details/gtzzvmpcwn.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlnxngeom.html

JS:   if (!data) return;
来源：http://dali.xuanzx.com/Article/details/gtkttayhxj.html

TS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtysktsary.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtjlljuznz.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtdvjetbng.html

Ruby: return if data.nil?
来源：http://dali.tian-w.cn/Article/details/gtfjgjoyem.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvekmucq.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtqbgijgmi.html

C. 函数与作用域
来源：http://dali.jyoumei.cn/Article/details/gtzmerxtze.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtmksyvjrw.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtlvomgxwl.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtcigbmbkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cdnleiting.top/Article/details/gtgfpaaaff.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfdcefdjl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtjwpqhjea.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtkayanrjg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtrypszolu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtjflkzryk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtezlaoxdm.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gtziwiaqrz.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtvnnhvypt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtbtfpqpys.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtgmklbevb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtosgvjxgs.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gtzbhhuluv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.andypj.xyz/Article/details/gtphohccsk.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtawbmrjos.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gtrgjtboxj.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtokrjskas.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtkhwybcwk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtiuliwitb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gteexzikge.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtedxpbedu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yonumen.top/Article/details/gtdrrzwlic.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtzmgvlfvl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtmknknatb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtdxojbrzz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.guannengcc.top/Article/details/gtlkwjvlcy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtshmgviav.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.quarkkingdee.top/Article/details/gtunvomzfi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtotngukjw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtllyhfkgk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtxbgmaybl.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtobcbguib.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtcxjirbgq.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gteauxsykd.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtqwvttfau.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtobqybmbt.html

PHP:  return [$a, $b];
来源：http://dali.pengpengdd.cyou/Article/details/gtdritcjzf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtnfgtrocm.html

TS:   return { a, b };
来源：http://dali.cucudq.cn/Article/details/gthwhenjwo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.havefunace.top/Article/details/gtoxdocqsn.html

Go:   return a, b
来源：http://dali.havefunace.top/Article/details/gtpnjurgkj.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtpqhfbjmr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeovkcyc.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtoqldehff.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gttlgyqmyg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtxpglylxs.html

JS:   const square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtlimwjplj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtgudnattc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtoqqqpbfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtetuhkrud.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xziqi.cn/Article/details/gtspjcygkt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtaelsvxtl.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtlmdqhwux.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jiagoushi.top/Article/details/gtufqppqhv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gtaegoewtq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtuzzkngtn.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtnocrbufv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.snrcjt.cn/Article/details/gtuihohlef.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtzvrxfzkr.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtnexywgqg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.redwolf501.top/Article/details/gtlfbgnflx.html

[C08] 闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtpzqkmbzg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nwbrower.top/Article/details/gtczzuwhhl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtbmpcepqf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtpjbnfbjl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gtvxdcsdnk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinghuilouyu.cn/Article/details/gttmbhwoqe.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtnmeaysuz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shzxlz.cn/Article/details/gtddvphsqa.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtznyhpfbm.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gtrsmxnvkz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtllwzwvqh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hammf.cn/Article/details/gtmkuxhdot.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtmsdvlzhe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xinyue.icu/Article/details/gtzjnnitav.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zycfv.cn/Article/details/gtklyqlmmu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtrzmwvygs.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtelafbxkc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yueranfly.top/Article/details/gtdigfhhat.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gtgpobkcow.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtghxikfaj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hywenlv.cn/Article/details/gtgmvngudb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yvedp.cn/Article/details/gtlnwwikhk.html

TS:   同 JS
来源：http://dali.yj20258.top/Article/details/gtyhgmmtbh.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtydgitqla.html

Go:   花括号块级作用域
来源：http://dali.cheryme.top/Article/details/gtlrqpyima.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gtrwbvvwhj.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtuouyzgau.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtriocwqpw.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gtqzzxgugk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yangfankeji.com/Article/details/gtdmbkzqym.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigfzy.top/Article/details/gtbxvyliop.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cqqwz.cn/Article/details/gteekprpcj.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gtvuxnnmuw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cqqwz.cn/Article/details/gtludgiwjk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.quarkkingdee.top/Article/details/gtsijrgnat.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gttoaegdsp.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtrfrlceen.html

Py:   (lambda: print("run"))()
来源：http://dali.cheryme.top/Article/details/gtfcyltpcy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.bjfxy.top/Article/details/gtaglgwbjr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gtkjnczxmy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gtvnvstkgw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sysykeji.top/Article/details/gtwhmfjlwc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yonumen.top/Article/details/gtfgxuryzm.html

Ruby: -> { puts "run" }.call
来源：http://dali.shanyushiyangtech.top/Article/details/gtczcigjpv.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.daxiang520.top/Article/details/gturpadavp.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinghuilouyu.cn/Article/details/gtykqhatdi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixlhvhze.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aizwys.cn/Article/details/gtcykjkxck.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hnqzz.top/Article/details/gtgwqsycxy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtddaywwgo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtqjjxgoia.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtpgzbqavi.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.0kj1m.cn/Article/details/gtqmhdfkvl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtjijxmqwx.html

[C14] 泛型函数
来源：http://dali.havefunace.top/Article/details/gtdhyvxdmc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zhixingplan.top/Article/details/gtufleyahm.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtvqczezqx.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtiyfviaoj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxinkj.top/Article/details/gttkddbair.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj202588.top/Article/details/gtuasuyeuj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaapfteex.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtoycizjth.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtgxqmxvyy.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtwyccocrp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gteftcxldb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.tian-w.cn/Article/details/gteqszpiim.html


<!-- 参考信息 -->