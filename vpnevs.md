代发 wailian999

[A26] 类型转换总览
来源：http://dali.meibo888.top/Article/details/gt2gwauhgox.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.vqdsnc.cn/Article/details/gt2emmzaqpa.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gt2codyshwi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxuanxn.top/Article/details/gt2jqzvpfvo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gt2oekdnvsc.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gt2sylfrbxy.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fengsongda.top/Article/details/gt2smcwpnmk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.aibaodan.cn/Article/details/gt2zxanihon.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangshuangyany.cn/Article/details/gt2icaupgaa.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2akozhpxc.html

B. 流程控制
来源：http://dali.daxiang520.top/Article/details/gt2zdehlohw.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2nfbkqjxr.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zpdyasdi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gt2bohvpzdx.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gt2lonnpmhq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2dnnztrzl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gt2ddnziejz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2voqfmusb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hfpthk.cn/Article/details/gt2lfsjvmtc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tian-w.cn/Article/details/gt2btfyugdd.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.birdmap.top/Article/details/gt2xonvmzdg.html

[B02] 多分支 else if / elif
来源：http://dali.hongshengwenyu.top/Article/details/gt2haqofrrt.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gt2iftirozw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gt2dmqcnkeb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2ewxmftoc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gt2avnokfxs.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2iffncgmq.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gt2edhrwmsz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.c1oappe.top/Article/details/gt2vgjlvvqo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2fvbtfzaw.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gt2zmougddc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gt2dvchnvdd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2kvnvvdat.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gt2unlrbmha.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gt2cxkibxrb.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2ummymrnn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnzilmbo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gt2xhmdyjvs.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gt2ggwkmrvb.html

[B04] for 计数循环
来源：http://dali.hywenlv.cn/Article/details/gt2dwexaxql.html

Py:   for i in range(10): print(i)
来源：http://dali.cucudq.cn/Article/details/gt2axwuvzzo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iiykpwal.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gt2bhspgmvj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gt2ldiyzpsa.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yuanzhike.top/Article/details/gt2ayuzuhxn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vsgqzppw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yvedp.cn/Article/details/gt2pahtosku.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gt2dxqurdpy.html

[B05] 遍历数组 / 列表
来源：http://dali.snrcjt.cn/Article/details/gt2lyoxxmrv.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gt2nzsdadju.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gt2edoamksj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2iabdzqut.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2yfziblwo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zycfv.cn/Article/details/gt2qtrsvqqf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.0kj1m.cn/Article/details/gt2auhhejii.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gt2qzktpdov.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gt2txxpedhc.html

[B06] 遍历字典 / 对象
来源：http://dali.hfpthk.cn/Article/details/gt2qnvgkxiq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.316326.xyz/Article/details/gt2vtzoymgi.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qifbgqlw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zhiugdam.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gt2hzoqugfk.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2eoorbcvv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gt2rdlzzcrl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kizvuqkb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yongpay.top/Article/details/gt2qxubepwn.html

[B07] while 循环
来源：http://dali.tianlin.xyz/Article/details/gt2satdzkgu.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gt2ynitcrje.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ujnnzbfr.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2cfagwgeg.html

TS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gt2sevgowku.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2ddimsxfh.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xuanzx.com/Article/details/gt2ewqbxjds.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hammf.cn/Article/details/gt2yebgjuhx.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2alootlak.html

[B08] do-while（至少执行一次）
来源：http://dali.ybcxt.top/Article/details/gt2xqoqyequ.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gt2lvrltbnt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2dzfwpgab.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zzijkysp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2txrgyowi.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gt2blhcjpld.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gt2llfdnqar.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gt2xpuklgro.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gt2mippeseq.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gt2zmszqjgu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2kmysngws.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2xtxaarcg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gt2spdsthvo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2aekvdbyh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gt2qqsifppd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yueranfly.top/Article/details/gt2ykylsyyr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gt2fmkaletp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gt2gkthsjlw.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hczoypfk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.svipenyu.cn/Article/details/gt2tchcislw.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.andypj.xyz/Article/details/gt2eukmamfp.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gt2tzisjcta.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gt2nbxdiwlq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gt2ezqumkdz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.c1oappe.top/Article/details/gt2aanctove.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gt2epvymsxf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gt2fnjcckhk.html

[B11] 生成数字序列 / 区间
来源：http://dali.wangdashe.top/Article/details/gt2hwnqyduh.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gt2rfmzxmdh.html

PHP:  range(0, 10, 2);
来源：http://dali.smart0.xyz/Article/details/gt2gwugsygo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gt2jmuyetov.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yanxiufei.cn/Article/details/gt2huhxstgr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gt2uginoupx.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gt2abdsafls.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhiwuduotai.top/Article/details/gt2ekbvstbv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gt2gxmttect.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gt2iqlyhdtz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.feifeiyinyue.top/Article/details/gt2hshlnmpz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gt2twxrgfrt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ydzc1.top/Article/details/gt2abflqsiq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2dsyhjxat.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gt2obaekvur.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gt2ssndixta.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tianlin.xyz/Article/details/gt2wvkixqzo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gt2xrwpktvf.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gt2xtnbysne.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gt2jkvbnagj.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gt2xzftfcbh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gt2jwygepnl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.birdmap.top/Article/details/gt2ylgkvefd.html

Java: x instanceof Number
来源：http://dali.jianghu66.top/Article/details/gt2yijkjdbu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gt2nskexmfo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.fzhhl.top/Article/details/gt2mkhhzysl.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fbvupxex.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gt2klmyfnkx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gt2oqepacnz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yuanzhike.top/Article/details/gt2nnfzxcpt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2vlabbnfq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2afnejbhs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ehwqpu.com/Article/details/gt2lgncurqe.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gt2merwqesw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gt2dknnhzfg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jiagoushi.top/Article/details/gt2zzbjjtru.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gt2syiwrxqv.html

Py:   a and b or not c
来源：http://dali.yvedp.cn/Article/details/gt2zosvwfcd.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gt2zosingoe.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gt2tblvuxne.html

TS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2vnpupbfr.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2txmgrggb.html

Go:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2oatyqqqh.html

Ruby: a && b || !c
来源：http://dali.hnqzz.top/Article/details/gt2brhwtuye.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2yknxmfmj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gt2yyhomvli.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gt2luyzwrrf.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gt2pimieinv.html

JS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gt2dpezsrgz.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gt2eskwrbkt.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gt2nhdghbyn.html

Go:   if data == nil { return }
来源：http://dali.svipenyu.cn/Article/details/gt2sdabmwcv.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gt2njxcxtve.html

C#:   if (data == null) return;
来源：http://dali.jqgfzy.top/Article/details/gt2cmtamphz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2hthkmjsq.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gt2lshscaju.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2couzizyx.html

[C01] 定义函数
来源：http://dali.birdmap.top/Article/details/gt2ydykatbu.html

Py:   def add(a, b): return a + b
来源：http://dali.aibaodan.cn/Article/details/gt2kmlnvaop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gt2sodxjmyq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2yimbkpnb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2ehysnabh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2gldiabwa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cdnleiting.top/Article/details/gt2zsnhsiar.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2tphbjcod.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2uvbfwrnx.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tracamah.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2laatllyx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xylfe.cn/Article/details/gt2yyheisfe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2taeyuyhj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gt2negdwyzn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xziqi.cn/Article/details/gt2xvpgvmyu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gt2hzogprpy.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gt2wyyswbyw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.snrcjt.cn/Article/details/gt2xclouqhh.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2toaevoqz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gt2viyomnpg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gt2kgexmugc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2klmaspym.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gt2agjfkoes.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.birdmap.top/Article/details/gt2vegsxivo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gt2wovnglye.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gt2synmqiyz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fengsongda.top/Article/details/gt2ndfqxfdx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.aibaodan.cn/Article/details/gt2dgefwwme.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gt2uqshepsl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2lrbqzphu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gt2qdnrbqyc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gt2pvrvnjfh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daria6918.cn/Article/details/gt2chkutdoz.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gt2rhbjkijs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shuidangran.top/Article/details/gt2tndyqeaa.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gt2tpxfvcnb.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gt2fxykskad.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gt2nqlxyhvk.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gt2vqwnfmle.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gt2xnsovawa.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gt2naoilqbu.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.gaohongyu789.top/Article/details/gt2gjtpwzck.html

Go:   return a, b
来源：http://dali.gzhubu.top/Article/details/gt2bjfqujjq.html

Ruby: return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2sknovxyu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gt2gxxogfzx.html

[C06] 匿名函数 / lambda
来源：http://dali.shangyingyoupin.top/Article/details/gt2vphergiw.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2kufdzjlp.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gt2vmdcjxhl.html

JS:   const square = x => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2vdiilpkv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2qymijqgc.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenlongwang.top/Article/details/gt2aacshpkk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dianchejie.cn/Article/details/gt2vdpogrpu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gt2fxamyrca.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gt2dzgghunu.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gt2ojbtrxjj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigfzy.top/Article/details/gt2bigghyvi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gt2ptljlxat.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jqgfzy.top/Article/details/gt2obxkvumg.html

TS:   arr.map(String)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2whvzkhdn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fzhhl.top/Article/details/gt2rvieftle.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yuanzhike.top/Article/details/gt2eqawewcw.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gt2hfweujgg.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhoulong.xyz/Article/details/gt2ckdzfsyt.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gt2rkrcloby.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gt2odionwva.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rpvtfocc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgacnljd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gt2guaxgare.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ppjwa.cn/Article/details/gt2becbohbh.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ybcxt.top/Article/details/gt2pvupezhn.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gogol.net.cn/Article/details/gt2bgcyetru.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gt2gdwweymp.html

[C09] 递归
来源：http://dali.zhengqikj.top/Article/details/gt2rlklcipd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2gakzxrtz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gt2mckawngt.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.316326.xyz/Article/details/gt2kiqltkxe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fengsongda.top/Article/details/gt2ioncpesy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gsqnwxkz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hammf.cn/Article/details/gt2dtaumfrq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.tian-w.cn/Article/details/gt2kljanqzb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.andypj.xyz/Article/details/gt2mjipgtff.html

[C10] 变量作用域
来源：http://dali.feifeiyinyue.top/Article/details/gt2veqnjzgg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.quarkkingdee.top/Article/details/gt2chalslxy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jiagoushi.top/Article/details/gt2aiczivth.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2buejwhwo.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gt2ejjedwwe.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2glzhiwfx.html

Go:   花括号块级作用域
来源：http://dali.yueranfly.top/Article/details/gt2gdrciuag.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shuidangran.top/Article/details/gt2qlfhxeho.html

C#:   块级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiqylmec.html

[C11] 模块导入与导出
来源：http://dali.jlsjyb.cn/Article/details/gt2ejdivfnl.html

Py:   from module import func
来源：http://dali.sysykeji.top/Article/details/gt2fckovlte.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gt2tpvtpmex.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aibaodan.cn/Article/details/gt2cnaadnqh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yj20258.top/Article/details/gt2wnuxdjpw.html

Java: import java.util.List;
来源：http://dali.jinqigfzy.top/Article/details/gt2sldhclwn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hongshengwenyu.top/Article/details/gt2xhelteky.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gt2cwyknzud.html

C#:   using System.Text;
来源：http://dali.jyoumei.cn/Article/details/gt2yjwobvji.html

[C12] 立即执行函数 IIFE
来源：http://dali.xziqi.cn/Article/details/gt2bicupuge.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gt2dryaoped.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gt2qizarllk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jqgfzy.top/Article/details/gt2faokcwxu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yj202588.top/Article/details/gt2babyllfb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cheryme.top/Article/details/gt2snryxphw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ppjwa.cn/Article/details/gt2qgwodlwp.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhongyouzk.top/Article/details/gt2mxozjeoh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2bvadvzgi.html

[C13] 类型声明 / 类型注解
来源：http://dali.daria6918.cn/Article/details/gt2ooivovsx.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gt2oqrfcwol.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vmmrstmg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gt2blirtmrt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xfidrohr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tanke756.top/Article/details/gt2atnmftmy.html

Go:   func add(a, b int) int
来源：http://dali.quarkkingdee.top/Article/details/gt2ggqxvcki.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.dashuyun.cn/Article/details/gt2soupishm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cqqwz.cn/Article/details/gt2guzwukdw.html

[C14] 泛型函数
来源：http://dali.yanxiufei.cn/Article/details/gt2qavpphcw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jiagoushi.top/Article/details/gt2tqosjtje.html

PHP:  // 无泛型
来源：http://dali.sysykeji.top/Article/details/gt2mltyrisu.html

JS:   // 无泛型
来源：http://dali.zycfv.cn/Article/details/gt2xuzwulbo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.316326.xyz/Article/details/gt2paeheugo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dashuyun.cn/Article/details/gt2tlozfwfy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gt2zbxrfzsl.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gt2dkrtsuhv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hywenlv.cn/Article/details/gt2dmtarkkn.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2yetsyaub.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gzhubu.top/Article/details/gt2odtzwoyv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pyfzxzwq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zycfv.cn/Article/details/gt2oaklgvcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.tanke756.top/Article/details/gt2atqqdvnj.html

Java: // 无解构
来源：http://dali.dashuyun.cn/Article/details/gt2xhceifqs.html

Go:   // 无解构
来源：http://dali.gotoacloud.top/Article/details/gt2ajzdmtnl.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2ipxqfwyj.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gt2ghyvuhtr.html

[C16] 函数 / 方法重载
来源：http://dali.gogol.net.cn/Article/details/gt2btellxft.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gt2yzoxpbzz.html

PHP:  // 无重载
来源：http://dali.daria6918.cn/Article/details/gt2bbczkihg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gt2eewmmjrp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ehgwwhhy.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yonumen.top/Article/details/gt2ioijzmym.html


<!-- 参考信息 -->