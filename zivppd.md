代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtnmmpejef.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenlongwang.top/Article/details/gtmvjwmybr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtpmhitqxj.html

[A25] 字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluavewwe.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gtctisrlid.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtytqtocrr.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtcgxorsfw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xylfe.cn/Article/details/gtsfsoabar.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gtshwjxcfz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.shuidangran.top/Article/details/gtczfozfag.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtptxfnexk.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.dashuyun.cn/Article/details/gtwbfrgflo.html

[A26] 类型转换总览
来源：http://dali.ehwqpu.com/Article/details/gtwpdmxzth.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xziqi.cn/Article/details/gtfhvydmxb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yangfankeji.com/Article/details/gtkpasvcra.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ivvv.top/Article/details/gtitvmiuwp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gtmkpynxjn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.316326.xyz/Article/details/gtjrrznqdt.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.shuidangran.top/Article/details/gtqinwvtvg.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenzaomai.com/Article/details/gtijfdfkxq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.dianchejie.cn/Article/details/gtqwukwvmp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtyklkeocy.html

B. 流程控制
来源：http://dali.haohaochexian.top/Article/details/gtefeadwai.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtmtqomnok.html

[B01] 条件判断 if / else
来源：http://dali.dashuyun.cn/Article/details/gtkzhykbyz.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenjidiqi.icu/Article/details/gtufvtxfao.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zycfv.cn/Article/details/gtjsbxdenx.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtemieonba.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcinmznes.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gtuwdhvknr.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigfzy.top/Article/details/gtiecciakk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.svipenyu.cn/Article/details/gtdtdffvqj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtmsxynekj.html

[B02] 多分支 else if / elif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaibivit.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtmbllervx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtidwwkqyh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtswnqwnry.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtwyrsztvo.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gthixybdpe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj202588.top/Article/details/gtvagtlhhu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gtegxljkpe.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtpolkkdyb.html

[B03] switch / match / case
来源：http://dali.gogol.net.cn/Article/details/gtadjdyabc.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ivvv.top/Article/details/gtrgeyqkgv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.vqdsnc.cn/Article/details/gtwtmmwowc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtigybnvvb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtzidwczma.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtfovcutlu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.mhx1999.top/Article/details/gtofjrwvqv.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258888.top/Article/details/gtozixxzjf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtsddegvtp.html

[B04] for 计数循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtabxtxirj.html

Py:   for i in range(10): print(i)
来源：http://dali.dashuyun.cn/Article/details/gtgrzwfskm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ybcxt.top/Article/details/gtaurqdmjy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gtxhzpbtes.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtovoasjql.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtcemujrdc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guannengcc.top/Article/details/gtugyiorur.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtespzfjxp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sxryk.cn/Article/details/gtnsiavkby.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gtdaqpufvr.html

Py:   for item in arr: print(item)
来源：http://dali.redwolf501.top/Article/details/gthitfqwes.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shzxlz.cn/Article/details/gtxpkxerss.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtbbjbfihf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daria6918.cn/Article/details/gteqjnzarr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmomfnevp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtitaujrsx.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gaohongyu789.top/Article/details/gtcvzkqcct.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yvedp.cn/Article/details/gtcxswtafa.html

[B06] 遍历字典 / 对象
来源：http://dali.fzhhl.top/Article/details/gtvtuslnkf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtvkzvclab.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yangfankeji.com/Article/details/gtzmmqxwgt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gtmboinevf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtbohgvjcu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtvaoqptjo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nwbrower.top/Article/details/gthkbdwirr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gttdgzmfmx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gthxvgnxmq.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gtanhnxwuh.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtvvcggwig.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtpepikurm.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtivbnctbm.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtntqhobvs.html

Java: while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtjzsilakr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtvtwotlsk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xziqi.cn/Article/details/gtzbvlmkig.html

C#:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtymzarrle.html

[B08] do-while（至少执行一次）
来源：http://dali.gaohongyu789.top/Article/details/gtgcihrnyb.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtfuhwgxin.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtactkyfba.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gttptpqmjf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gttlcvyjby.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlfjkcyc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtxvgaepph.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yueranfly.top/Article/details/gtznpdqaox.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtfnkuyfco.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gtstgxjzcr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gtgshpfklx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gthdklwxwy.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtzzzeurse.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtebjhppkg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmvnbdecm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.9152youxi.cn/Article/details/gtzosqffaf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtaljzneyq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtxaspcocm.html

[B10] 遍历同时拿索引
来源：http://dali.redwolf501.top/Article/details/gtthdmmhao.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtknorpews.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.mhx1999.top/Article/details/gtutcvufvs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtdddqcnvo.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.quarkkingdee.top/Article/details/gtjtqyinin.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gttsqvkivq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtnqwjjmoi.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.316326.xyz/Article/details/gtqjvenvoc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.0kj1m.cn/Article/details/gtyfezhjkx.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtmkowhvpu.html

Py:   list(range(0, 10, 2))
来源：http://dali.gogol.net.cn/Article/details/gtqphbaxjs.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtakryoluq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.mhx1999.top/Article/details/gtdbytmrli.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtganxfoow.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gtqearwduy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hnqzz.top/Article/details/gtbvkbnuvu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gttxfxnbgt.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guannengcc.top/Article/details/gtiywsuqep.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtqiiwdggw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shangyingyoupin.top/Article/details/gtrphhecic.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gtgvxlbrni.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yongpay.top/Article/details/gtetnhykbd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtdrposqtf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtkxfmsugg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gttlynhwfr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gtnmrgkwuk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtzjigydxu.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtnoduyomp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gtzxqdclaw.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gthonrkhrf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtazisdofz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtuprctefm.html

Java: x instanceof Number
来源：http://dali.jqgufenzy.top/Article/details/gtwdqpnoyc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtkkwfwaof.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gtqzkitcuq.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtcydvwiqk.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gttwhfnusj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yuxming.cn/Article/details/gtanrnaqom.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxinkj.top/Article/details/gtxfwrjnzc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtobdzulvf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dashuyun.cn/Article/details/gtjrxlibgq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtrnrttxhd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gtqgsvgste.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtjouxhnsu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtcqnezzen.html

[B15] 布尔运算与取反
来源：http://dali.sxryk.cn/Article/details/gtxnlyjfmi.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtofeeekzw.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtqyytjsxr.html

JS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtagcsafkh.html

TS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gteykbmbeu.html

Java: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtiuefnzge.html

Go:   a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtfhlrpwfr.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtcnowogml.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtuhguwkth.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtcxiczitx.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gtqwgnouue.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtfcksufsz.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtejoqdtab.html

TS:   if (!data) return;
来源：http://dali.aizwys.cn/Article/details/gtbedmnjdg.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtuippeitv.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gttzfzbdjo.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtysocumyr.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gtpdhwgncj.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtiqsgxpij.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtevpckgej.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gthxenauuu.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtjsefeblt.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxinkj.top/Article/details/gteixhuafa.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gttacmhmrr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtwgaudwkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtnromijdz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtoqvmazcj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gtwlnycnun.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gaohongyu789.top/Article/details/gtxyluwwlg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtyfslqqda.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtghlpgcol.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtvdrqzxkl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtbibrzrii.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtfjaqhnyt.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtoasbshhn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gttvojmgcj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtbirjyfck.html

Ruby: def greet(name = "World") = name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrcbxacqm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gteirfeoot.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtlfzrqkbj.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gttkijlkix.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtudxlgmjg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtogmwstok.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtsoztzxrm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtiwrgrypd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtqxsltkun.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtxhphesun.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtlsjobdyt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgfzy.top/Article/details/gtchjeanqb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gthxenglca.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yangfankeji.com/Article/details/gtaxiccape.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhongyouzk.top/Article/details/gtiydhkuvo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.0kj1m.cn/Article/details/gtqbsnfxid.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtuxuxomrz.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtedgqxgcr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtwedghroz.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtetkhhkio.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtvakfgmzo.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gtptevvnlg.html

PHP:  return [$a, $b];
来源：http://dali.gogol.net.cn/Article/details/gtrlpfsuvp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuetiantiany.cn/Article/details/gtwfvgmllp.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtputwjjvg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.birdmap.top/Article/details/gtxdaawzyl.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtfaobcwvu.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gtudvnpvnt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj202588.top/Article/details/gtafcjnsrt.html

[C06] 匿名函数 / lambda
来源：http://dali.sufxvd.cn/Article/details/gtcehlwmpx.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtchgvtfll.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cqqwz.cn/Article/details/gteldmfvhl.html

JS:   const square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gtrgrjxlip.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gttmagrseb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.andypj.xyz/Article/details/gtalpqwrvm.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tanke756.top/Article/details/gtxfzvutpx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtmfumgtfz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtellfoban.html

[C07] 把函数作为参数传入
来源：http://dali.meibo888.top/Article/details/gtmzkdahjw.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gthkvlslfk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtioigtbti.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.c1oappe.top/Article/details/gtokaxfklj.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtowiznwfz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuanzx.com/Article/details/gtucmuotlx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtueroumgz.html

Ruby: arr.map(&:upcase)
来源：http://dali.316326.xyz/Article/details/gtzqmrhbzh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtvshpgfnk.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtpycdpvoq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hnqzz.top/Article/details/gtnxjzxgwc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gtxnqxiglk.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtpwbmaphy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtmislbcpv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuhergbpm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tianlin.xyz/Article/details/gtaxszioww.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.wangdashe.top/Article/details/gthduznzdt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtvibgbmoz.html

[C09] 递归
来源：http://dali.cucudq.cn/Article/details/gthskylvdj.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gtoicnagro.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gtgsjepclc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtfrqwsimd.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtqrwntmzc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtcedjvauy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cheryme.top/Article/details/gtwuypspvw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtpexvkmlq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhoulong.xyz/Article/details/gtpxijrkbe.html

[C10] 变量作用域
来源：http://dali.dianchejie.cn/Article/details/gtzzulahml.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgjwzpznn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtcznwtsct.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtmnjxnkre.html

TS:   同 JS
来源：http://dali.0kj1m.cn/Article/details/gtgpjfbdvy.html

Java: 方法内为块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtkwcnmdnc.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gtttzrmett.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.0kj1m.cn/Article/details/gtehcghlaw.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gtdjfyopvg.html

[C11] 模块导入与导出
来源：http://dali.nwbrower.top/Article/details/gtretestls.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gttcqqzjif.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xinyue.icu/Article/details/gtnustuvda.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ivvv.top/Article/details/gthrqltnus.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.c1oappe.top/Article/details/gtnsdzampv.html

Java: import java.util.List;
来源：http://dali.ybcxt.top/Article/details/gtdmkowibh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sweek.top/Article/details/gtwivftkxs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.redwolf501.top/Article/details/gtnhqfvpuy.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmegyath.html

[C12] 立即执行函数 IIFE
来源：http://dali.sweek.top/Article/details/gtkozagukp.html

Py:   (lambda: print("run"))()
来源：http://dali.hnqzz.top/Article/details/gtbzaybxsf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlcamaezn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtqrptolll.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtutzeukye.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayeezqlq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258.top/Article/details/gtgoyyiedy.html

Ruby: -> { puts "run" }.call
来源：http://dali.hnqzz.top/Article/details/gtitmuitpl.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gtskvkihbq.html

[C13] 类型声明 / 类型注解
来源：http://dali.ydzc1.top/Article/details/gtelzejipo.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtrvimybha.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtogsmzcnk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gtfcthvasw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtrwmpnrno.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtsfalouhu.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtdpozijna.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gtzaonxjiy.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.redwolf501.top/Article/details/gtxeanateh.html

[C14] 泛型函数
来源：http://dali.shangyingyoupin.top/Article/details/gtpcgwxvgo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aibaodan.cn/Article/details/gtgpyrbaxz.html

PHP:  // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtzarbduaz.html

JS:   // 无泛型
来源：http://dali.guannengcc.top/Article/details/gtjbwmautj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gttesolilr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtwttdjoju.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gtumtmbnso.html

Ruby: # 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtviiyhnrz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtyaposzdo.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtbmikdlej.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.ehwqpu.com/Article/details/gtejihmpyh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yj20258.top/Article/details/gtrukyorqx.html


<!-- 参考信息 -->