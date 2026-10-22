代发 wailian999

[A26] 类型转换总览
来源：http://dali.jqgufenzy.top/Article/details/gt2nbpnaywu.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.0kj1m.cn/Article/details/gt2xwjxirfl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zdqjudy.top/Article/details/gt2ymlcpxue.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jutdsckq.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cucudq.cn/Article/details/gt2tpalsnoa.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gt2stndnurx.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yongpay.top/Article/details/gt2gmxzyloa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yangfankeji.com/Article/details/gt2yjkkrdvk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gt2rzixhall.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2qwmqkljb.html

B. 流程控制
来源：http://dali.mhx1999.top/Article/details/gt2zdnftany.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2fwjbdryt.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gt2gilpdtpq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yonumen.top/Article/details/gt2uiviyocs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2wpdmgvzz.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gt2dkqqnfdi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yonumen.top/Article/details/gt2mngytcba.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gt2tqodxxmu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gt2mmuzbqrn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gt2kihctifd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2sjbtespe.html

[B02] 多分支 else if / elif
来源：http://dali.yanxiufei.cn/Article/details/gt2noawxwkr.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangshuangyany.cn/Article/details/gt2pyitftxv.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.chenzaomai.com/Article/details/gt2nxatrsrq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gt2lifwlelk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2jcmbyere.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gt2aymwazbp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yvedp.cn/Article/details/gt2kjflupmd.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.havefunace.top/Article/details/gt2bobmevwz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2pwuekgdh.html

[B03] switch / match / case
来源：http://dali.zhengqikj.top/Article/details/gt2thbeefep.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.9152youxi.cn/Article/details/gt2eugypspz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yueranfly.top/Article/details/gt2fczgelmk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2lmgqzrrk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2dnfpogkq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2jbttbnvn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.sxryk.cn/Article/details/gt2ipxpgelm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258.top/Article/details/gt2tzwadciz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gt2zdvqvoly.html

[B04] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gt2llvowtwg.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gt2wdzmiwwq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2inbcgekt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2chorzlxt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jyoumei.cn/Article/details/gt2rmdoeukx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gt2fdoabrvx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gt2qfwfszqw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.gaohongyu789.top/Article/details/gt2ovjyurbb.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daria6918.cn/Article/details/gt2mbjxblsl.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2sdlzrcsf.html

Py:   for item in arr: print(item)
来源：http://dali.hfpthk.cn/Article/details/gt2lsnvbgbq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cashguo.top/Article/details/gt2wbevyytn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gt2srldkrgp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gt2othonkxa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sysykeji.top/Article/details/gt2qrnamryt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hysaishi.cn/Article/details/gt2oxrskfit.html

Ruby: arr.each { |item| puts item }
来源：http://dali.birdmap.top/Article/details/gt2tstxaprs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2sesouxrh.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gt2zbrbkquo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yvedp.cn/Article/details/gt2dafldbvt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gt2knkpdeaa.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hjqlezeo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2jlzcmeui.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gt2pxzhsoyt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xziqi.cn/Article/details/gt2irxfoqme.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tanke756.top/Article/details/gt2ipuvrnir.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gt2hiadfolx.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gt2vivecpcn.html

Py:   while i < 10: i += 1
来源：http://dali.nanxuanxn.top/Article/details/gt2wwqtghip.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gt2ypfemkoh.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ibqtrkhc.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2mrlvgmxr.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gt2rujbysex.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gt2tvnbmkef.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gt2fvspsolx.html

C#:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2zlrwfwfq.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gt2tjsdmnvl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenjidiqi.icu/Article/details/gt2gjsmaglg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2qlibszwl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2lnmyhbde.html

TS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2tudssdby.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2lxynbtsr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhongyouzk.top/Article/details/gt2tmdctrxx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gt2dpherqdo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gt2pjufulrx.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gt2zqlxvrfc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gt2xwyjtuhb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2ofrnnagc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.svipenyu.cn/Article/details/gt2ojecoxrj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2effpdljo.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2zteunono.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2mjcnkeqm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cheryme.top/Article/details/gt2usxprvov.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gt2uhzehitr.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gt2fiscfqia.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cashguo.top/Article/details/gt2cmbeelmz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2kyjbpwon.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2gcmeiayt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gt2vhnczhrt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zyavxocd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.snrcjt.cn/Article/details/gt2iaeakwew.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2zhxslwyb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gt2efwpsice.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gt2sapadzop.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gt2mdgyqflj.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gt2rmmctzxi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2xwbqewff.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gt2bqwoypvy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cbylrodh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxuanxn.top/Article/details/gt2cdwsfyvd.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gt2nvwufzsv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2sjxrrnpn.html

[B12] 跳出多层循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ruwslrpt.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gt2niexhykg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gaohongyu789.top/Article/details/gt2ntgnscps.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2fsicbtrg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gt2rmhjmokf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gt2dehyscpt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gt2wxmpfsap.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jqgufenzy.top/Article/details/gt2btnrybav.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gt2mwlrhcla.html

[B13] 判断是否为数字
来源：http://dali.xylfe.cn/Article/details/gt2bcckhnvs.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gt2hwnglbkb.html

PHP:  is_numeric($x)
来源：http://dali.mhx1999.top/Article/details/gt2vkagnyia.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2dhowmsqb.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gdvrtcxq.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gt2jwdbzymt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xziqi.cn/Article/details/gt2cafyvypx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sufxvd.cn/Article/details/gt2iqxghsjl.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gt2kynwrjdk.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gt2kqizjqay.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gt2jksaqtwm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzvwqyth.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2madyubdr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lhswgrwc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cucudq.cn/Article/details/gt2cscnuwem.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gt2udxxmval.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.andypj.xyz/Article/details/gt2edmtkgaz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2upvshdkq.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gt2bzumvhwt.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2dueeiydw.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigufen.top/Article/details/gt2aooyuxbx.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2qdpgfjxd.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2qwymkgfm.html

Java: a && b || !c
来源：http://dali.nanxinkj.top/Article/details/gt2mfpidrdw.html

Go:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2qgcjtsew.html

Ruby: a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gt2fvburuhx.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2idxovlbz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2iriaadqd.html

Py:   if not data: return
来源：http://dali.hysaishi.cn/Article/details/gt2qtmsvzjy.html

PHP:  if (!$data) { return; }
来源：http://dali.fengsongda.top/Article/details/gt2cndtmzfz.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2pimlnpzp.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2lnnnsgvi.html

Java: if (data == null) return;
来源：http://dali.dianchejie.cn/Article/details/gt2wpyipqmn.html

Go:   if data == nil { return }
来源：http://dali.dianchejie.cn/Article/details/gt2xatthzha.html

Ruby: return if data.nil?
来源：http://dali.aibaodan.cn/Article/details/gt2zqfgvzuz.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zzhsgvcr.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2xltqakyw.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2ynrrbcbc.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2odfgsvbl.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gt2waexmgqm.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gt2dfijojna.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gt2ckpgegtm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2kysuvmtn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2aowrgsqf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zlackwog.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.tian-w.cn/Article/details/gt2khjszjkx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cqqwz.cn/Article/details/gt2amkzhptr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2djtmowdj.html

[C02] 默认参数
来源：http://dali.chenzaomai.com/Article/details/gt2iyuevroz.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pmcnejmd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ydzc1.top/Article/details/gt2uaqkbflh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2xjnzjzgk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yonumen.top/Article/details/gt2bhtjskux.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gt2nchufnlf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.fengsongda.top/Article/details/gt2rfanwjrf.html

Ruby: def greet(name = "World") = name
来源：http://dali.ppjwa.cn/Article/details/gt2aebqtchv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gt2mmundxiz.html

[C03] 可变参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2riwnekxt.html

Py:   def total(*args): return sum(args)
来源：http://dali.cdnleiting.top/Article/details/gt2oamudpzx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gt2oehtlzcw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gt2wdffrihb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2bhxfuoqb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhijiandao.cn/Article/details/gt2joorkqoj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gt2xuaxzobe.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gt2oudgqcdr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daria6918.cn/Article/details/gt2gojryinx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.chenlongwang.top/Article/details/gt2hmzdqcwu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gt2odrooddw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gt2gooeklam.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gzhubu.top/Article/details/gt2grrxling.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzngxuwv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gt2anuiuivh.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gt2rhixzzdt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2whdecvos.html

C#:   f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gt2gzphnajt.html

[C05] 返回多个值
来源：http://dali.ybcxt.top/Article/details/gt2kvzbcsuo.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gt2oyasrxka.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cmjhwilq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hnqzz.top/Article/details/gt2grmgyzua.html

TS:   return { a, b };
来源：http://dali.wangshuangyany.cn/Article/details/gt2eorzvmgt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gt2xrpkitek.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2yrjctyyu.html

Ruby: return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gt2wfjydspj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gt2uuytkpid.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gt2hchandgd.html

Py:   square = lambda x: x * x
来源：http://dali.dianchejie.cn/Article/details/gt2vbxaoysl.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gt2jdtgzslb.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2ysqtqoul.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gt2pankeltq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2ysrwgwux.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gt2swrinrzx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cqqwz.cn/Article/details/gt2bcbrdejg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2pumpxzbf.html

[C07] 把函数作为参数传入
来源：http://dali.gogol.net.cn/Article/details/gt2xzigmhvj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gt2rdqjkxsg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gt2zaiwxwqm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.guannengcc.top/Article/details/gt2qawmqddd.html

TS:   arr.map(String)
来源：http://dali.aibaodan.cn/Article/details/gt2fhvpsjhu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gt2vshaktcn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2rhcywyjo.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gt2rkkoinzi.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.guowangkeji.top/Article/details/gt2prwizzlt.html

[C08] 闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rtaerobw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2dkjerfav.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.ehwqpu.com/Article/details/gt2cfcekbbx.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gt2wdayheng.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2rvdulzfn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.quarkkingdee.top/Article/details/gt2wdgiueng.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.fengsongda.top/Article/details/gt2buifzxzi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gt2tkqgjxwi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gt2esrzwfhl.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gt2spxjyqfw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xylfe.cn/Article/details/gt2ojbhmmjp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj20258.top/Article/details/gt2fpmhgojb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2nqtqoiym.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnxiangtu.top/Article/details/gt2llwzycmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcdecwvw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2ounuyqfh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2qjbofrea.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqpybsnc.html

[C10] 变量作用域
来源：http://dali.meibo888.top/Article/details/gt2xlvcycyz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gt2rlxsxsbo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gt2wqsgfhpa.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.kuanghao11.cn/Article/details/gt2nhzbxxjb.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gt2pxlttiyp.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2eabdlqvm.html

Go:   花括号块级作用域
来源：http://dali.cashguo.top/Article/details/gt2ltsfszve.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangdashe.top/Article/details/gt2brjiieol.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2muwunjwg.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmdienjj.html

Py:   from module import func
来源：http://dali.jinqigufen.top/Article/details/gt2djaimnff.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.chenzaomai.com/Article/details/gt2kffmtzey.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.meibo888.top/Article/details/gt2oqsuuqjh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gt2sefmyqxa.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gt2rcrkckis.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gt2wzibfhws.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gt2pbnlwrzg.html

C#:   using System.Text;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xsrlzsbr.html

[C12] 立即执行函数 IIFE
来源：http://dali.nwbrower.top/Article/details/gt2fvrajizi.html

Py:   (lambda: print("run"))()
来源：http://dali.birdmap.top/Article/details/gt2ilsmfalr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenjidiqi.icu/Article/details/gt2gvnaknpf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pnvrsuzm.html

TS:   (() => { console.log("run"); })();
来源：http://dali.dianchejie.cn/Article/details/gt2krhmeuxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gt2zmifastr.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xuetiantiany.cn/Article/details/gt2annefokj.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gt2wohrxowl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xbvsmiyz.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gt2tmmxebbl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gt2kwsaoyvf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qrdxpmwh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gotoacloud.top/Article/details/gt2gkswigxq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2cbwnkxlo.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2wpfeuwov.html

Go:   func add(a, b int) int
来源：http://dali.nanxinkj.top/Article/details/gt2pmlxnjct.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tanke756.top/Article/details/gt2jdndjdrb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gt2riudccmo.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gt2dkxjzxif.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2xldqclia.html

PHP:  // 无泛型
来源：http://dali.chenlongwang.top/Article/details/gt2hdbtbyps.html

JS:   // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhkhsldl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hywenlv.cn/Article/details/gt2zxzyfqhp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shuidangran.top/Article/details/gt2djxhwkty.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jqgufenzy.top/Article/details/gt2njpadckf.html

Ruby: # 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2pioskawf.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guowangkeji.top/Article/details/gt2eysqnqnz.html

[C15] 解构 / 展开参数
来源：http://dali.haohaochexian.top/Article/details/gt2aoimkavs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.0kj1m.cn/Article/details/gt2zihxvqwp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.0kj1m.cn/Article/details/gt2vapdjufx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncvkijki.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gt2mtddfrvx.html

Java: // 无解构
来源：http://dali.gogol.net.cn/Article/details/gt2kxodmhhw.html

Go:   // 无解构
来源：http://dali.yvedp.cn/Article/details/gt2wubbsvun.html

Ruby: a, b = pair
来源：http://dali.iojbl.cn/Article/details/gt2oaeyurvt.html

C#:   var (a, b) = pair;
来源：http://dali.yangfankeji.com/Article/details/gt2dqhbgwfi.html

[C16] 函数 / 方法重载
来源：http://dali.yvedp.cn/Article/details/gt2lijgyxwr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guannengcc.top/Article/details/gt2kgqvwbmx.html

PHP:  // 无重载
来源：http://dali.nanxuanxn.top/Article/details/gt2wraamzve.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hysaishi.cn/Article/details/gt2pcmerspx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gt2bziihmel.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2ueqrtjiq.html


<!-- 参考信息 -->