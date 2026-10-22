代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmhovszj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gt2wwvzcscb.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yuxming.cn/Article/details/gt2xjrufmtv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258.top/Article/details/gt2qhkzpkwf.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gt2czpfyvhq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gt2geywckjn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fengsongda.top/Article/details/gt2xeyxfggd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gt2sdhmlofe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gt2dqlhnbbv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gt2dkrbhxaz.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.nwbrower.top/Article/details/gt2lydtmlnt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gotoacloud.top/Article/details/gt2uqvefmhz.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.snrcjt.cn/Article/details/gt2yyywmlmo.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rdrypoit.html

B. 流程控制
来源：http://dali.xuanzx.com/Article/details/gt2zlmpnefi.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2jymplmrn.html

[B01] 条件判断 if / else
来源：http://dali.quarkkingdee.top/Article/details/gt2wbjrlpzs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yueranfly.top/Article/details/gt2doycgzdp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.gotoacloud.top/Article/details/gt2lujdfawg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gt2ncqmgybw.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gt2kpsouxoi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gt2kylpdzgl.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sufxvd.cn/Article/details/gt2zqjvcmoi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnxiangtu.top/Article/details/gt2bvrxftey.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gt2cicpvxtk.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gt2wzvafzns.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2vxhjfzaz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fzhhl.top/Article/details/gt2qjiverzt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2fdtwrgdh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2myhoqapx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gt2onhskvme.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gt2guxjrnzq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gt2gvvbbgvw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2ovagonmc.html

[B03] switch / match / case
来源：http://dali.hongshengwenyu.top/Article/details/gt2kmxbnzwz.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.feifeiyinyue.top/Article/details/gt2fujomiud.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gt2ncoocrsg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2zdfaawpf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2aqxfemst.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gt2wtsrcheo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.vqdsnc.cn/Article/details/gt2uldqgwoa.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gt2auzwblbd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ppjwa.cn/Article/details/gt2thabauir.html

[B04] for 计数循环
来源：http://dali.cheryme.top/Article/details/gt2spftgqda.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yygvxqby.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yuxming.cn/Article/details/gt2uvdqilbx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.vqdsnc.cn/Article/details/gt2asbfvuxj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gt2kkzvkgqv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gt2ektkfnzv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.svipenyu.cn/Article/details/gt2klukkobm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nsxnikga.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gt2pwmjcvmj.html

[B05] 遍历数组 / 列表
来源：http://dali.hammf.cn/Article/details/gt2awboshsm.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gt2epxuenur.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gt2kwmxbcpu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gt2ihcgshno.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jqaqlrxm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2ouuvnefg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gt2qqpwhylq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gt2wlxfcjoe.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gt2xucgvikv.html

[B06] 遍历字典 / 对象
来源：http://dali.shuidangran.top/Article/details/gt2xzshxtwq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gt2qmhtjnqr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2podeexef.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xinyue.icu/Article/details/gt2fysynyqx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gt2apoqpcpm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gt2hpfspqxk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gt2raaagoot.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssxmoses.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tian-w.cn/Article/details/gt2bvdaqnka.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gt2zndtkoch.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gt2ytckgrhe.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2dyrunsfb.html

JS:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gt2trzpbhvo.html

TS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gt2ghjcztzn.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2gurclyfw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2ylurojlz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2irpncbbt.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gt2nwrkpgoq.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gt2gonyohwm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hammf.cn/Article/details/gt2qbredooz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2nhibtpwz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2lhqoysay.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2dnoyjfzb.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2tiiovvuz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gt2pfyczzxk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gt2azffcszr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2klvwpyil.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gt2mbvgjrom.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gt2abbvrpty.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gt2zplwcohc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2thcockmh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.316326.xyz/Article/details/gt2emnraask.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2ftpnzqhk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hysaishi.cn/Article/details/gt2qnqjlphc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2mkqidrvc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2ocqtcrru.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2jjkgojgb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gt2ixcumjmx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.9152youxi.cn/Article/details/gt2eipbbsdp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhiwuduotai.top/Article/details/gt2szxhkrnv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gt2edtwowqb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gt2fcshagdx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gt2jeukxwtx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.smart0.xyz/Article/details/gt2yrbtwhex.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhixingplan.top/Article/details/gt2banpgamt.html

[B11] 生成数字序列 / 区间
来源：http://dali.sweek.top/Article/details/gt2ajnvltjm.html

Py:   list(range(0, 10, 2))
来源：http://dali.hammf.cn/Article/details/gt2crzimeay.html

PHP:  range(0, 10, 2);
来源：http://dali.guannengcc.top/Article/details/gt2svlbyqee.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2zbpmlfip.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjhzuhrk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2kikykbfb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gt2envhfika.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenzaomai.com/Article/details/gt2hzwfxewt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ehwqpu.com/Article/details/gt2bfjzpetn.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gt2ktuhivwy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gt2ucxkntqy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gt2hgdjegda.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gt2kfzkaygl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gt2cwgkrnpf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gt2hqbzaccy.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gt2yreaeduv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hfpthk.cn/Article/details/gt2hbiiyiyw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gt2ahqfrgva.html

[B13] 判断是否为数字
来源：http://dali.gaohongyu789.top/Article/details/gt2iqwelhgd.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxddczgf.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gt2aaopfpdh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gt2bequzntl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sysykeji.top/Article/details/gt2zyzboquo.html

Java: x instanceof Number
来源：http://dali.cucudq.cn/Article/details/gt2ldzosrgf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gt2izxxnoqw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aizwys.cn/Article/details/gt2zvytmxau.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gt2pedcxgrw.html

[B14] 判断值是否在集合内
来源：http://dali.yvedp.cn/Article/details/gt2dokqcaiq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2xxlqfgwt.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xylfe.cn/Article/details/gt2ynbojhpv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2rmfcwwxg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2hqnrgsxx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sxryk.cn/Article/details/gt2woxxngfe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2uialbonq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gt2efdiovvf.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kiluuvva.html

[B15] 布尔运算与取反
来源：http://dali.ydzc1.top/Article/details/gt2kvllktvk.html

Py:   a and b or not c
来源：http://dali.wangdashe.top/Article/details/gt2zqvrqvas.html

PHP:  $a && $b || !$c
来源：http://dali.aizwys.cn/Article/details/gt2qhxthbmx.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2uafiqdro.html

TS:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gt2lqnkzghd.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2jzrpmxdm.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gt2zcnjgpli.html

Ruby: a && b || !c
来源：http://dali.yonumen.top/Article/details/gt2kffkmkne.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2ykdtsgdh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2awvmjfwl.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gt2firsxsec.html

PHP:  if (!$data) { return; }
来源：http://dali.xinyue.icu/Article/details/gt2beenrhzt.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gt2ftoywrvw.html

TS:   if (!data) return;
来源：http://dali.9152youxi.cn/Article/details/gt2bovxoteh.html

Java: if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jokauyxr.html

Go:   if data == nil { return }
来源：http://dali.9152youxi.cn/Article/details/gt2nuyauymd.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gt2ofqnetgu.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2pyosgzfj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2pyfwjmzd.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gt2syewtiea.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2bcwexpkz.html

[C01] 定义函数
来源：http://dali.gotoacloud.top/Article/details/gt2bkmzahch.html

Py:   def add(a, b): return a + b
来源：http://dali.birdmap.top/Article/details/gt2epozsgyw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2adzvdyqk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2pohtrgbk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gt2fvxcjhem.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2leaxgamo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hiwgcruw.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gt2zqftngeh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2gyvfmayf.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2gghprcfg.html

Py:   def greet(name="World"): return name
来源：http://dali.hfpthk.cn/Article/details/gt2fodoshzv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wdbiovkw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhongyouzk.top/Article/details/gt2iikrfiot.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gotoacloud.top/Article/details/gt2vztybhjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kjkynzdq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jntrzzqx.html

Ruby: def greet(name = "World") = name
来源：http://dali.smart0.xyz/Article/details/gt2jneksmoz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.kuanghao11.cn/Article/details/gt2lcmtcceh.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gt2jjmfdbpw.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2oemvzgxa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yangfankeji.com/Article/details/gt2pxbfjgyx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yueranfly.top/Article/details/gt2qoeobggz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gt2sbedhgzk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xziqi.cn/Article/details/gt2uudchfvd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gt2gooqtmah.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gt2uqfnalhi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gt2xdjxmxfl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gt2gtpuflac.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gt2tkcmfdud.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.fengsongda.top/Article/details/gt2jrbvugst.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2vbivqyof.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tanke756.top/Article/details/gt2grlyopqh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.quarkkingdee.top/Article/details/gt2qpeqisyn.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pkfftwov.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gt2dmaqtvjk.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigfzy.top/Article/details/gt2jkeaweod.html

[C05] 返回多个值
来源：http://dali.zhixingplan.top/Article/details/gt2xbofmcru.html

Py:   return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2njbemfgh.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gt2debplwnx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2zeiibkyp.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2dunvsyai.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shzxlz.cn/Article/details/gt2dtpstwyz.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2zxjzjpzg.html

Ruby: return a, b
来源：http://dali.ehwqpu.com/Article/details/gt2lkukdjhm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gt2fykminck.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gt2ukigfhbm.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gt2lrtggwpr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gt2mxnfvcms.html

JS:   const square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gt2tkkhbltx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gotoacloud.top/Article/details/gt2gnvsszbf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2wnjfjoki.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258.top/Article/details/gt2wedsmjbm.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2xpkmqwpw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gt2qhimljkn.html

[C07] 把函数作为参数传入
来源：http://dali.ivvv.top/Article/details/gt2nxntkkxd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gt2djcfazul.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2cmgatidf.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guowangkeji.top/Article/details/gt2jtgydrnl.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2lprsmvun.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gt2lsielbej.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gt2cvjcpybx.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigufen.top/Article/details/gt2lteziqvl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gt2voqgsglo.html

[C08] 闭包
来源：http://dali.nwbrower.top/Article/details/gt2wzvrmzcb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.0kj1m.cn/Article/details/gt2myuaukkl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yvedp.cn/Article/details/gt2biabxwwu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2mvboehgp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gt2pomhxdsb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gt2trvfgtvq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gt2zmmllijd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhoulong.xyz/Article/details/gt2hevltclm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gt2tdulerzu.html

[C09] 递归
来源：http://dali.xuanzx.com/Article/details/gt2xupobxty.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2sanshutm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2ptlitasi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.iojbl.cn/Article/details/gt2jqxhebyw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gt2ycvfajyg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.daria6918.cn/Article/details/gt2rhbrlufl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.vqdsnc.cn/Article/details/gt2vecxkzmy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gt2phldgqls.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sysykeji.top/Article/details/gt2jbofvabm.html

[C10] 变量作用域
来源：http://dali.shangyingyoupin.top/Article/details/gt2npgromxn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgufenzy.top/Article/details/gt2stbdjlnz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gt2jhhftkfb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2ciuozexe.html

TS:   同 JS
来源：http://dali.316326.xyz/Article/details/gt2oficdfqo.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2ugvgdros.html

Go:   花括号块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gt2mjsjroiy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ehwqpu.com/Article/details/gt2ctjjcuhg.html

C#:   块级作用域
来源：http://dali.guannengcc.top/Article/details/gt2gdexveij.html

[C11] 模块导入与导出
来源：http://dali.xinyue.icu/Article/details/gt2hfmfecen.html

Py:   from module import func
来源：http://dali.bjfxy.top/Article/details/gt2qjpahcor.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenjidiqi.icu/Article/details/gt2knuijtin.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wznwqjld.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yueranfly.top/Article/details/gt2hxaosfcg.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gt2snpudnnr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gt2wnlnpclm.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.bjfxy.top/Article/details/gt2nnkynpcp.html

C#:   using System.Text;
来源：http://dali.tian-w.cn/Article/details/gt2nadirhvs.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gt2axhnovgy.html

Py:   (lambda: print("run"))()
来源：http://dali.gogol.net.cn/Article/details/gt2cttlmqny.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gt2fjxppctl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gt2bkkdfueh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yvedp.cn/Article/details/gt2vzhqnkip.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigfzy.top/Article/details/gt2abmkoxlk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2dvouqxuy.html

Ruby: -> { puts "run" }.call
来源：http://dali.ybcxt.top/Article/details/gt2lmbinqsa.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aizwys.cn/Article/details/gt2bdjflybu.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2shibwmns.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2ejxuvvcj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2pcxvfsmp.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hysaishi.cn/Article/details/gt2tklyncih.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2yzkgrbeh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gt2ksqknkuf.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ktiwkkig.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gt2ozkxzwzq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigufen.top/Article/details/gt2dwkefgbb.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdaglwad.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gt2uxgzoncb.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hrdyypyc.html

JS:   // 无泛型
来源：http://dali.tanke756.top/Article/details/gt2swagedtc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yonumen.top/Article/details/gt2ofyronif.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkvyhquf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.nanxuanxn.top/Article/details/gt2alblwske.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2nxdkqyif.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnxiangtu.top/Article/details/gt2sjlmzoph.html

[C15] 解构 / 展开参数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ypdkmrie.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gt2uhuplmws.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gnuksina.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.guannengcc.top/Article/details/gt2jlxzfqet.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.fzhhl.top/Article/details/gt2rmdiumvu.html

Java: // 无解构
来源：http://dali.smart0.xyz/Article/details/gt2cnqwbouc.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gt2psomlldf.html

Ruby: a, b = pair
来源：http://dali.ppjwa.cn/Article/details/gt2udljiocs.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gt2fzzrmksw.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gt2gduwzdfo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dashuyun.cn/Article/details/gt2wvlccxnr.html


<!-- 参考信息 -->