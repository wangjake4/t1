代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gt2xfmfrlja.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.316326.xyz/Article/details/gt2uzxmqgon.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gt2bqjuuovt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2kcpewqba.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.svipenyu.cn/Article/details/gt2iuahinal.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ybcxt.top/Article/details/gt2krdjiwus.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gt2psombuud.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhoulong.xyz/Article/details/gt2oqqjznqw.html

[A26] 类型转换总览
来源：http://dali.zhengqikj.top/Article/details/gt2hgshdrse.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gt2klritzxp.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.nanxuanxn.top/Article/details/gt2tqheqylq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tnfprhyk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.316326.xyz/Article/details/gt2aopkocky.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gt2wntjtgeu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.guowangkeji.top/Article/details/gt2dpsbgsro.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.pengpengdd.cyou/Article/details/gt2ilbdzbui.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxfukjwm.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2msgndhpx.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gt2gevxpzlo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2kwrfordi.html

[B01] 条件判断 if / else
来源：http://dali.sufxvd.cn/Article/details/gt2vbsimnng.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tianlin.xyz/Article/details/gt2gjjtmgwj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jyoumei.cn/Article/details/gt2utojgryl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nfuzcytn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sufxvd.cn/Article/details/gt2dhctxpmd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nanxinkj.top/Article/details/gt2dpsbqjen.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenlongwang.top/Article/details/gt2qhgmjvzy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gotoacloud.top/Article/details/gt2iftrufrd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ubxrkgiq.html

[B02] 多分支 else if / elif
来源：http://dali.gogol.net.cn/Article/details/gt2doqevoyb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2bpajxlkz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnbrpmvq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gt2mdjkkkqi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gt2bglmdbjr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ehwqpu.com/Article/details/gt2chiafnvc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258.top/Article/details/gt2nadtfpnk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhixingplan.top/Article/details/gt2icrxbftq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yvedp.cn/Article/details/gt2ucmpgdie.html

[B03] switch / match / case
来源：http://dali.xuanzx.com/Article/details/gt2aosgmjwl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gt2mllvifbd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gt2avbznujw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lrlmognm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gt2kapmfusg.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2jntxeayo.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2ohonihzk.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gt2yapqsoji.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnazxqqb.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gt2csmoxegj.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gt2deizmctv.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gaohongyu789.top/Article/details/gt2cbhwugnb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gt2vrwkfgkb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2lruxpdzx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sxryk.cn/Article/details/gt2piavhbwq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xziqi.cn/Article/details/gt2zyubvpfc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gt2pllpdmyk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2yxzqxnwc.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2kfczbtgd.html

Py:   for item in arr: print(item)
来源：http://dali.fzhhl.top/Article/details/gt2myxusqqk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2axhcwzje.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2mwilvpda.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2mxrkikok.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gzhubu.top/Article/details/gt2pcrujwqw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zicjzzuh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gogol.net.cn/Article/details/gt2uclemwvq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258888.top/Article/details/gt2cbxnrwpe.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gt2goothayh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gt2vkqcnhfj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ivvv.top/Article/details/gt2hmumsvhe.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ppjwa.cn/Article/details/gt2ddccacjl.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gt2ixbvuzvv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ailimmzt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gt2ucjijwvx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.daxiang520.top/Article/details/gt2zexdnhax.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aiowafzk.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gt2lnvnugdo.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gt2ntalqkex.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.pycfn.com/Article/details/gt2hgstkytr.html

JS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gt2rbzmmojt.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gt2mlscbikn.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2gbgoqknc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shzxlz.cn/Article/details/gt2lundudia.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sxryk.cn/Article/details/gt2obnxamlm.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2omztqjxg.html

[B08] do-while（至少执行一次）
来源：http://dali.haohaochexian.top/Article/details/gt2eqkijqfz.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gt2wuzrfzsr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nwbrower.top/Article/details/gt2dyirohvj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2govdukgd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2xxlvokma.html

Java: do { i++; } while (i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gt2bguwhfkb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gt2ppmbprru.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2oedsmozo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gt2xrexydaa.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gt2vhftmssc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zycfv.cn/Article/details/gt2dygmqmxz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2nmnwlhwj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2irmdwzqa.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2ahabudnu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gt2jkbrvmby.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.chenzaomai.com/Article/details/gt2eybevcjm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hysaishi.cn/Article/details/gt2thzpfhsu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gt2vzgjlcea.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2rufosqve.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gt2ilvkbyqc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2hdgjdmne.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenzaomai.com/Article/details/gt2mqzfqhsh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gt2shaiobbi.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.aibaodan.cn/Article/details/gt2duavppsv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gt2rxxarcyx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sweek.top/Article/details/gt2mcdjtmbp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmhzihsw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gt2hdpkmlsv.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gt2mgepolhu.html

PHP:  range(0, 10, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2tszarbjb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2klrcikab.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gt2gxinsnep.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gt2wvjeksrl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2wjlnpvsc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2ttiysmxp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2xvruffhn.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gt2rliviyjf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhixingplan.top/Article/details/gt2uslelbop.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gt2jjvlycif.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gt2ryyoqyld.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gt2btjqflvh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2nopghqya.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.redwolf501.top/Article/details/gt2lbhqsitk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2nmdobktr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gt2kuidnuay.html

[B13] 判断是否为数字
来源：http://dali.pycfn.com/Article/details/gt2mmelznbn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jlsjyb.cn/Article/details/gt2wnybuxde.html

PHP:  is_numeric($x)
来源：http://dali.iojbl.cn/Article/details/gt2hwwgjydi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ywdvmzil.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2pxzhryde.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ttfaezka.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gt2gusnslto.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2pzmpdrbj.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gt2uwuqskba.html

[B14] 判断值是否在集合内
来源：http://dali.hysaishi.cn/Article/details/gt2dkhebxml.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hongshengwenyu.top/Article/details/gt2aijyqbim.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuanzx.com/Article/details/gt2fnnogxhw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gt2fcahhhdf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzhlvcyk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2copyatlo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tanke756.top/Article/details/gt2ccqczpee.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gt2mdpvwloj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ydzc1.top/Article/details/gt2bugnvzyy.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2sxutqqkr.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gt2pyekmhjd.html

PHP:  $a && $b || !$c
来源：http://dali.zhixingplan.top/Article/details/gt2uehxkcwt.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gt2fmehrsae.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gt2mzrxetpm.html

Java: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2udaagtky.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2kvbsoekw.html

Ruby: a && b || !c
来源：http://dali.daxiang520.top/Article/details/gt2icrguqqx.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2beacqevx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qdrykljs.html

Py:   if not data: return
来源：http://dali.xziqi.cn/Article/details/gt2ylrthyjn.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxuanxn.top/Article/details/gt2novauqjb.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gt2jveswupp.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2tijgtenc.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gt2ibwecaav.html

Go:   if data == nil { return }
来源：http://dali.smart0.xyz/Article/details/gt2bskyxbfn.html

Ruby: return if data.nil?
来源：http://dali.nanxinkj.top/Article/details/gt2dbvgqalx.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gt2ccrtezib.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2ubxqksar.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gt2zdmvfsvm.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2jfmwqtlj.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gt2rzvcfezw.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gt2vhvosdgn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2libxxxbr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2aucvctjx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2zjdrwpqy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vfajfgpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.nanxuanxn.top/Article/details/gt2mivdwzor.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gt2qtopljbg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2eoikdswk.html

[C02] 默认参数
来源：http://dali.chenlongwang.top/Article/details/gt2zstvdozx.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gt2tucxzwnl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gt2ivwttlbt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wdcoovqe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gfenqrus.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.c1oappe.top/Article/details/gt2xivtdbys.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gt2qpevvnmk.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lmzzrnpp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gt2utuofqus.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gt2xjlxsmrg.html

Py:   def total(*args): return sum(args)
来源：http://dali.sxryk.cn/Article/details/gt2mqzqyukv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cashguo.top/Article/details/gt2gjfxcsks.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gt2icmnavjp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2akbpdnzz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gt2zqivyqdm.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gt2ovcdtxpd.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gt2rapueziw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gt2ovcxhhoz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gt2qstqasln.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gt2mubfjuyr.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gt2hhwzjowi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2xufefldp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.haohaochexian.top/Article/details/gt2dxruyadp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ivvv.top/Article/details/gt2dozhupug.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gt2kmirvhql.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gt2frjmipyh.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gt2ccewhhpd.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gt2olkxfxhd.html

Py:   return a, b
来源：http://dali.jianghu66.top/Article/details/gt2svofsdls.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2hbmymoip.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gt2eacojjto.html

TS:   return { a, b };
来源：http://dali.aizwys.cn/Article/details/gt2zhqegwyk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gt2ktlktwfx.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2hyxjbewp.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gt2kgovbvxl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sysykeji.top/Article/details/gt2zjkiitda.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gt2wrnksflq.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gt2inmmhapj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.birdmap.top/Article/details/gt2jmrwvqcl.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2rhrakqai.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gt2kbstqyjt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2ltqrbfif.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qkaxcdeq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.vqdsnc.cn/Article/details/gt2dzzvwpco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gt2zwtkztvn.html

[C07] 把函数作为参数传入
来源：http://dali.guannengcc.top/Article/details/gt2iumojanf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tian-w.cn/Article/details/gt2nmnavyym.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gt2etebnmsb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhengqikj.top/Article/details/gt2kvowsbmh.html

TS:   arr.map(String)
来源：http://dali.nanxuanxn.top/Article/details/gt2ewtyiekz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gt2wvklkhpp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.quarkkingdee.top/Article/details/gt2anmuurkb.html

Ruby: arr.map(&:upcase)
来源：http://dali.xziqi.cn/Article/details/gt2fmrtrumj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2osqpizet.html

[C08] 闭包
来源：http://dali.cheryme.top/Article/details/gt2ikzmukpo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gt2zjsrqvkl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jianghu66.top/Article/details/gt2pjocjpkr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gt2mahdbamd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2fxoadxao.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.mhx1999.top/Article/details/gt2zigphnrz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sweek.top/Article/details/gt2efljywrh.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cdnleiting.top/Article/details/gt2faewedmw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2xwjyqjpk.html

[C09] 递归
来源：http://dali.sxryk.cn/Article/details/gt2cjwzlqak.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gt2zakrgbsx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jinqigufen.top/Article/details/gt2dmxrccyi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gt2mgbxtssi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gt2vnvftdqk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gt2fcczljfv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gt2yxveszjc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gt2joglbvol.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gt2brtlrmgy.html

[C10] 变量作用域
来源：http://dali.redwolf501.top/Article/details/gt2nubryhdm.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gt2ntftnasn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hnqzz.top/Article/details/gt2kmnzfxjz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ybcxt.top/Article/details/gt2mhwhiric.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gt2xsrpfqui.html

Java: 方法内为块级作用域
来源：http://dali.sysykeji.top/Article/details/gt2evgdmfjd.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2kcfsecki.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cqqwz.cn/Article/details/gt2pgobagtk.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gt2gfvmrnzp.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gt2yjzaaebt.html

Py:   from module import func
来源：http://dali.jlsjyb.cn/Article/details/gt2czmoiefw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ybcxt.top/Article/details/gt2vwddsuop.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yanxiufei.cn/Article/details/gt2tazmsalr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuxming.cn/Article/details/gt2ijozrlij.html

Java: import java.util.List;
来源：http://dali.meibo888.top/Article/details/gt2pweaznrb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gt2rlwowzvn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jiagoushi.top/Article/details/gt2rozgaubw.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gt2lsndutuu.html

[C12] 立即执行函数 IIFE
来源：http://dali.guannengcc.top/Article/details/gt2mzkyvgrh.html

Py:   (lambda: print("run"))()
来源：http://dali.smart0.xyz/Article/details/gt2fociokpl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mtayewvg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qxzowhjg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gt2kbqvbosu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gt2snpnqxha.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mantrcsr.html

Ruby: -> { puts "run" }.call
来源：http://dali.tanke756.top/Article/details/gt2mdiejuhj.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jqgufenzy.top/Article/details/gt2hucqwwqe.html

[C13] 类型声明 / 类型注解
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxprejba.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gt2poqidqtu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gt2wtqpbohr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gt2vgrgcafc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2vqrfulvh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jdpbfmsk.html

Go:   func add(a, b int) int
来源：http://dali.guowangkeji.top/Article/details/gt2iawmgvpe.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.316326.xyz/Article/details/gt2fengsfmq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gt2crotdini.html

[C14] 泛型函数
来源：http://dali.cashguo.top/Article/details/gt2wyadzjzs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daria6918.cn/Article/details/gt2bhrleplj.html

PHP:  // 无泛型
来源：http://dali.c1oappe.top/Article/details/gt2nqnowsin.html

JS:   // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2guraywic.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hjtmviox.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2usjhbjkn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cqqwz.cn/Article/details/gt2cwxmqosr.html

Ruby: # 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2jxtjipct.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jianghu66.top/Article/details/gt2ltjqvuyv.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gt2bzzgzibh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gt2belcudnf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hfpthk.cn/Article/details/gt2cbmhbzwh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gt2fbkyjnko.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbtueqan.html

Java: // 无解构
来源：http://dali.gzhubu.top/Article/details/gt2sxpuwmdr.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2wscbogen.html


<!-- 参考信息 -->