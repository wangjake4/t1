代发 wailian999

[A26] 类型转换总览
来源：http://dali.yangfankeji.com/Article/details/gt2bbsdsnrp.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gt2bsspuqnz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pycfn.com/Article/details/gt2zftrrver.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gt2oyubfvij.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gt2qjvshanj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.aizwys.cn/Article/details/gt2eedklzpr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhoulong.xyz/Article/details/gt2psqnwljh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gt2mqfrifjd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gt2wkpavnas.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2dsmzkjyj.html

B. 流程控制
来源：http://dali.daria6918.cn/Article/details/gt2doymplir.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jdxxyiql.html

[B01] 条件判断 if / else
来源：http://dali.yj20258.top/Article/details/gt2bzsdjitr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.nanxuanxn.top/Article/details/gt2fubgafts.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hnxiangtu.top/Article/details/gt2akiihxbr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ogjqrbon.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gt2gzadtqiv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj202588.top/Article/details/gt2pxbmscmo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.tanke756.top/Article/details/gt2jzrbdaoe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gt2qloyslze.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2ctfeoosj.html

[B02] 多分支 else if / elif
来源：http://dali.cdnleiting.top/Article/details/gt2uhighpyw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.gaohongyu789.top/Article/details/gt2ywdclgyz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gotoacloud.top/Article/details/gt2okfnjtvb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2tlbfhlzg.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2ztfdaapd.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ydzc1.top/Article/details/gt2cgizstov.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gt2ewhcczhj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jyoumei.cn/Article/details/gt2yayalpqz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gt2syamfrcg.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gt2zkuyzagu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jqgfzy.top/Article/details/gt2tbvjxyfz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gt2wojhouwq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gt2ocjsemws.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nwbrower.top/Article/details/gt2aaaiuivl.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gt2ocrkmysh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2ubdaufvl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gt2ffnwxlwy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xeoynvud.html

[B04] for 计数循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2exclnwto.html

Py:   for i in range(10): print(i)
来源：http://dali.hywenlv.cn/Article/details/gt2giqapfvy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cqqwz.cn/Article/details/gt2owgkvciw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2ujlmbhhb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nkixmboq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nelopeiw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gt2bmegucch.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gt2hbpgxlrv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj202588.top/Article/details/gt2qwjdzeaq.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gt2jboifpvb.html

Py:   for item in arr: print(item)
来源：http://dali.gotoacloud.top/Article/details/gt2taujwkbg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.svipenyu.cn/Article/details/gt2jbekuqdy.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnqzz.top/Article/details/gt2nfepfcbw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jhbupevm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gt2yvpkliic.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jiagoushi.top/Article/details/gt2kxtxhtwv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tanke756.top/Article/details/gt2anquvhnq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2hrkrdbcl.html

[B06] 遍历字典 / 对象
来源：http://dali.cqqwz.cn/Article/details/gt2rbsgxtfg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pengpengdd.cyou/Article/details/gt2wiqcjnfr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sysykeji.top/Article/details/gt2jsjxepbw.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gt2iwxoqnpw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gt2cylrpppg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gt2wsmrevgj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hongshengwenyu.top/Article/details/gt2qjqeemho.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zycfv.cn/Article/details/gt2jdtrvugh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gt2hyojdozy.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gt2jcabmley.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gt2yeeeghcg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yonumen.top/Article/details/gt2hikwhmqq.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gt2ixvjhill.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2wffkvtul.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2ycbrweqb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gt2ssqajkcu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenlongwang.top/Article/details/gt2yvjxpphw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gt2csevkidb.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gt2skkeabhg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhoulong.xyz/Article/details/gt2gwokvhcq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2izoschkc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gt2yfuzcfov.html

TS:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gt2cwlbluhl.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2odctsesb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gt2nbplhgpk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fzhhl.top/Article/details/gt2gtegkzif.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2vfjcxmfx.html

[B09] break 与 continue
来源：http://dali.9152youxi.cn/Article/details/gt2ctpndqhz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gt2yauegrug.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2gswrzlmj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2qavnmeep.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gt2sxhxikre.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2jzljshqp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2uxgyxggg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gt2kwfaazkb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2rvriyfrb.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gt2jtsqoqcu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenzaomai.com/Article/details/gt2vklgsxcp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dashuyun.cn/Article/details/gt2wzpxccfh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gt2jcovzsys.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zycfv.cn/Article/details/gt2qwzhebdu.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gt2myzbsbzk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yonumen.top/Article/details/gt2ersclahy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.havefunace.top/Article/details/gt2nnmrqbpw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gt2yxbdqwdm.html

[B11] 生成数字序列 / 区间
来源：http://dali.redwolf501.top/Article/details/gt2kptecpby.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gt2rycstfqx.html

PHP:  range(0, 10, 2);
来源：http://dali.hammf.cn/Article/details/gt2rcqziujo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2qbsduzwh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gt2fdkscpqf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gt2kjikqend.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.guowangkeji.top/Article/details/gt2jalnpfji.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gt2yrirlwok.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhoulong.xyz/Article/details/gt2oiingyfi.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gt2kmtsxcvu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gt2onbudnpu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gt2rpwypppf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gt2izdfwtzv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2iurybgvj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gt2iyrldsbe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.quarkkingdee.top/Article/details/gt2mtlfnovs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gt2knshztlh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gt2nrqurjbx.html

[B13] 判断是否为数字
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hwcssaqu.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2jcnshiaq.html

PHP:  is_numeric($x)
来源：http://dali.zhongyouzk.top/Article/details/gt2qrygmggq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cucudq.cn/Article/details/gt2rsgnxqjm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhixingplan.top/Article/details/gt2ksnrojwj.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcesnkzj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.9152youxi.cn/Article/details/gt2xdxlcwmr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gt2dxdwsgjy.html

C#:   x is int or double or decimal
来源：http://dali.9152youxi.cn/Article/details/gt2obedhwfw.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gt2goytgxlw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.daria6918.cn/Article/details/gt2ptxhfbkc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gt2nwsgxdkf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2nmhxrfpi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.havefunace.top/Article/details/gt2frjirnky.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zycfv.cn/Article/details/gt2sqjflnki.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ydzc1.top/Article/details/gt2lqxaeqdt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.tianlin.xyz/Article/details/gt2tpzkvkzo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yongpay.top/Article/details/gt2fjyvnegm.html

[B15] 布尔运算与取反
来源：http://dali.0kj1m.cn/Article/details/gt2gulzdlby.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gt2iskyofzx.html

PHP:  $a && $b || !$c
来源：http://dali.316326.xyz/Article/details/gt2wzxdtefa.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kghchyut.html

TS:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2aqqunrdr.html

Java: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2aebnkyil.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gt2drhzqqqd.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2mjynkbkp.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2ysupftja.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gt2jdsxmzdk.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gt2zmizofvj.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gt2fzawuhpn.html

JS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gt2cxlgzojc.html

TS:   if (!data) return;
来源：http://dali.zhijiandao.cn/Article/details/gt2pbqytsic.html

Java: if (data == null) return;
来源：http://dali.ydzc1.top/Article/details/gt2skgswcok.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gt2lqswybgq.html

Ruby: return if data.nil?
来源：http://dali.fzhhl.top/Article/details/gt2bytfxvde.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gt2xwgagjik.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gt2zzsxjytn.html

C. 函数与作用域
来源：http://dali.tian-w.cn/Article/details/gt2gxgjedwx.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2slcmgcec.html

[C01] 定义函数
来源：http://dali.quarkkingdee.top/Article/details/gt2ipgfrdav.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gt2omtgyimd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2bznpgwnz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2zoxamxfp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gt2bbolkpqk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2zaxuthnr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2ouebarqz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gt2qsmjmegz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2exgzeywi.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2kreubsyc.html

Py:   def greet(name="World"): return name
来源：http://dali.zdqjudy.top/Article/details/gt2mbhlkbxc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gt2odfvudvt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2niyvbrxu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2yrkrbpzl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ivvv.top/Article/details/gt2tvyrthnq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.snrcjt.cn/Article/details/gt2bbpeihoo.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gt2hbznccmt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.316326.xyz/Article/details/gt2ptmqhhkb.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2xsvzhxvm.html

Py:   def total(*args): return sum(args)
来源：http://dali.ehwqpu.com/Article/details/gt2shmvqmwh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.guowangkeji.top/Article/details/gt2lydrkllc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gt2xzvrrneh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gt2iuwoicnn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gt2jazjdjwv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2toddkgok.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2sahnlqkd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yvedp.cn/Article/details/gt2fgjmflul.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ppjwa.cn/Article/details/gt2euzdfyml.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cdnleiting.top/Article/details/gt2piwpihgo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gt2nrxtddol.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2swusdycl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cucudq.cn/Article/details/gt2ykwxcaru.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gt2leyvxqby.html

Go:   // 无：用配置结构体参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2frpdxhtx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gt2qrsjsddx.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gt2tjqtrsbn.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gt2fvbumxim.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gt2tyshtfuf.html

PHP:  return [$a, $b];
来源：http://dali.zhongyouzk.top/Article/details/gt2tgcsubct.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gt2sjyhhndw.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gt2jhwhpend.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gt2tgrrnges.html

Go:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2dwexmmsx.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2tjvqmrgs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2cjokyijb.html

[C06] 匿名函数 / lambda
来源：http://dali.smart0.xyz/Article/details/gt2xespwewx.html

Py:   square = lambda x: x * x
来源：http://dali.ivvv.top/Article/details/gt2oqvdqvai.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.316326.xyz/Article/details/gt2xtyebrdi.html

JS:   const square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gt2jxrjkslk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2uuqlkfsz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2ewdbxzbi.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj20258888.top/Article/details/gt2tpiwqgau.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gt2lcrwjlgq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2asiidebb.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gt2zthwjmut.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gt2bedmcusv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gt2fsgsaoui.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gt2uteccovh.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gt2ufpdtzgn.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gogol.net.cn/Article/details/gt2lxyvdlkf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangdashe.top/Article/details/gt2bcwgjhxj.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mwnyekbo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gt2wdgzxskd.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2uwtdxhaw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xinyue.icu/Article/details/gt2ctduzolm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gt2tpfanmuk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2tyqmtzyx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2hawbbxsw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gt2npflbxts.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gt2ihfwfgbo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2fvdrwxle.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gt2oioskqpq.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gt2wcefpqgy.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2xipqonzo.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2loeqhzhy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shangyingyoupin.top/Article/details/gt2dajmjdaz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gt2lwzyfwoh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tian-w.cn/Article/details/gt2uswnrdmv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hksxrvcn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gt2svgvrbpi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxuanxn.top/Article/details/gt2pawltpoa.html

[C10] 变量作用域
来源：http://dali.haohaochexian.top/Article/details/gt2uwakrrrd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xylfe.cn/Article/details/gt2pszudcug.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gt2hagoydzx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gt2vrwjdrzh.html

TS:   同 JS
来源：http://dali.quarkkingdee.top/Article/details/gt2bcckkatt.html

Java: 方法内为块级作用域
来源：http://dali.hysaishi.cn/Article/details/gt2zjpyvdtz.html

Go:   花括号块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nzkgtpjq.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.cheryme.top/Article/details/gt2athjlqds.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2xvaicero.html

[C11] 模块导入与导出
来源：http://dali.birdmap.top/Article/details/gt2kawwfcwl.html

Py:   from module import func
来源：http://dali.sweek.top/Article/details/gt2tvztivgq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gt2rwgqhtzg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gt2sxzfwafw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gt2kdnsqbzj.html

Java: import java.util.List;
来源：http://dali.daxiang520.top/Article/details/gt2ljnzaoaq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2orqlgkpa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gt2tkpndvhf.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gt2tvsyqaxf.html

[C12] 立即执行函数 IIFE
来源：http://dali.iojbl.cn/Article/details/gt2gwchdsaw.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2bhcvycub.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenlongwang.top/Article/details/gt2niqjvdqy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gotoacloud.top/Article/details/gt2nlhlyihn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jyoumei.cn/Article/details/gt2rsjumfln.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rpefwiys.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.quarkkingdee.top/Article/details/gt2ahfzwbdk.html

Ruby: -> { puts "run" }.call
来源：http://dali.hongshengwenyu.top/Article/details/gt2rdpjkede.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.316326.xyz/Article/details/gt2xlaznzkv.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2fprentiv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tanke756.top/Article/details/gt2mwkndarh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2kyixxftm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.redwolf501.top/Article/details/gt2btucxclg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gt2xfombggs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2xnglavvg.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gt2uuehnkos.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydgqigji.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.feifeiyinyue.top/Article/details/gt2quojuvlf.html

[C14] 泛型函数
来源：http://dali.0kj1m.cn/Article/details/gt2uelnbnph.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sufxvd.cn/Article/details/gt2uzeaemsa.html

PHP:  // 无泛型
来源：http://dali.zdqjudy.top/Article/details/gt2kunkebdt.html

JS:   // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gt2zengkrip.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ppjwa.cn/Article/details/gt2ctvzvvza.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2rokrqdbk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gt2hgqtfycl.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gt2jabdcuss.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yanxiufei.cn/Article/details/gt2cituvopv.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gt2hlcncfhs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gt2klqmhtsh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gt2ovfbsqze.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2fnodhvqr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zdqjudy.top/Article/details/gt2lfglmfrw.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gt2xncafkiy.html

Go:   // 无解构
来源：http://dali.shuidangran.top/Article/details/gt2ptyskyvb.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gt2cfepcukp.html

C#:   var (a, b) = pair;
来源：http://dali.sxryk.cn/Article/details/gt2sjdbsput.html

[C16] 函数 / 方法重载
来源：http://dali.yangfankeji.com/Article/details/gt2ytwgqmgv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gt2monrvfef.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gt2ywbduyrk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yueranfly.top/Article/details/gt2ufjpwdua.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.guowangkeji.top/Article/details/gt2irfysvua.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zdqjudy.top/Article/details/gt2bvpesgwd.html


<!-- 参考信息 -->