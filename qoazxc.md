代发 wailian999

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj202588.top/Article/details/gt2uakwluwc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinqigufen.top/Article/details/gt2nzcbgqxv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gt2wlbidubj.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dianchejie.cn/Article/details/gt2mupylffn.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gt2wtjtkowx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gt2oqbcubql.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.tianlin.xyz/Article/details/gt2nlctpdjq.html

[A25] 字符串比较
来源：http://dali.sweek.top/Article/details/gt2wasggplb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zhixingplan.top/Article/details/gt2fqiiwqdq.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.guowangkeji.top/Article/details/gt2kjvubtux.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhixingplan.top/Article/details/gt2iojlbxfk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gt2astzdwns.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.wangdashe.top/Article/details/gt2nbvpxdjr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.tanke756.top/Article/details/gt2gvzomyht.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gt2szpquhpr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhhywtas.html

[A26] 类型转换总览
来源：http://dali.dashuyun.cn/Article/details/gt2hjnfsuko.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhixingplan.top/Article/details/gt2wstlnuxh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhiwuduotai.top/Article/details/gt2thjnhdif.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.andypj.xyz/Article/details/gt2npjhuzlk.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hnqzz.top/Article/details/gt2lzgarxyw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yonumen.top/Article/details/gt2rpjvxsma.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.birdmap.top/Article/details/gt2auxzskiu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gt2ihpenraw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gt2yzykmeoi.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2succqpbs.html

B. 流程控制
来源：http://dali.zhixingplan.top/Article/details/gt2tuizhwrh.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2qznelhcp.html

[B01] 条件判断 if / else
来源：http://dali.wangshuangyany.cn/Article/details/gt2sqgeelhx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gt2nirbwcmq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.316326.xyz/Article/details/gt2jxolnije.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gt2nwstjohd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cdnleiting.top/Article/details/gt2jushjxnc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gt2xisshsrk.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jianghu66.top/Article/details/gt2uhoneyxe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hysaishi.cn/Article/details/gt2qnjeuqgq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2wremurtn.html

[B02] 多分支 else if / elif
来源：http://dali.yueranfly.top/Article/details/gt2dzrnlzfl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gt2shqktzer.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gt2eacnorhn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2gosxhzxo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2jiobbgxw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdouysge.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yanxiufei.cn/Article/details/gt2mhfjnogl.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yj20258888.top/Article/details/gt2ypctzixz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2naxvyyol.html

[B03] switch / match / case
来源：http://dali.yanxiufei.cn/Article/details/gt2jdnizoxl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xziqi.cn/Article/details/gt2ephyplin.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gt2gubmylam.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jqgfzy.top/Article/details/gt2cjxrncvt.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2viococir.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2jxiiwxys.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2diyxzqhj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ehwqpu.com/Article/details/gt2hpklnfir.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yangfankeji.com/Article/details/gt2kpwsozvk.html

[B04] for 计数循环
来源：http://dali.birdmap.top/Article/details/gt2gqibsymy.html

Py:   for i in range(10): print(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zmlrfxlx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gt2qpbddfri.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bwtdbthn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gt2rvtnpuwp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhengqikj.top/Article/details/gt2lvexmkrw.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yanxiufei.cn/Article/details/gt2tqzwoxds.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gt2hcezdiiq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gt2wodjjjjp.html

[B05] 遍历数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2wcbhesru.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gt2pcrhnmou.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.snrcjt.cn/Article/details/gt2qnmaetoc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shzxlz.cn/Article/details/gt2eyjlukis.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2gmxqhupf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sweek.top/Article/details/gt2uydfundt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gotoacloud.top/Article/details/gt2cnkxczhe.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vrstezuu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2xhakxvic.html

[B06] 遍历字典 / 对象
来源：http://dali.guannengcc.top/Article/details/gt2iuqnheyu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nwbrower.top/Article/details/gt2nbcszmeg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tianlin.xyz/Article/details/gt2eigokdsc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sftkplup.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cqqwz.cn/Article/details/gt2qknjgqjv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.mhx1999.top/Article/details/gt2udrfydwe.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gt2ufjjjgyr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gt2krmgqxuu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gt2bbnqkryx.html

[B07] while 循环
来源：http://dali.yongpay.top/Article/details/gt2ecwjjtkn.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gt2fofsxrua.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gt2stewkrij.html

JS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gt2wprahcst.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2owjcqzyx.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2qszfpilz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gt2mkwmikem.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gt2icwobpvl.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2mxasedld.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gt2wwgfguwp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gt2eeeqbdyu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gt2ckukldsr.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2ytahqfzf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2etcggmct.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gt2mdpfqjfx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2nldzrokj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aizwys.cn/Article/details/gt2teqjkztv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gt2jbpjvoju.html

[B09] break 与 continue
来源：http://dali.dashuyun.cn/Article/details/gt2ysuiqzhk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gt2cvepvhnn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2relhjrek.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gt2zsjrwzud.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2djcqakbw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2lsstymkj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2dbtdnqyf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gt2hvezatjy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gt2ccusnmdf.html

[B10] 遍历同时拿索引
来源：http://dali.xziqi.cn/Article/details/gt2cwuclnmr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucncymio.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2prffnsit.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gt2gdoclpnq.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gt2rjgwtqat.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gt2trrakxzn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gt2kuczxzxf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gt2becnhztl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gt2kntfqmqb.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gt2tiuwynlo.html

Py:   list(range(0, 10, 2))
来源：http://dali.shuidangran.top/Article/details/gt2duekrdov.html

PHP:  range(0, 10, 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ofnljlaf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pdqggjjc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2ljuwaqyk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hkhnbtkl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohqjmpbw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2raontpio.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gt2flxyhgbw.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2ifeesktm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zxywukur.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sdrtyzoy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2vxbrnysf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vvixxrvj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.9152youxi.cn/Article/details/gt2nfxojhll.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nwbrower.top/Article/details/gt2tapmoubw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnxiangtu.top/Article/details/gt2eipubbwx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnxiangtu.top/Article/details/gt2shscsmmv.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gt2gdsicikl.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gt2nkkdgfco.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gt2ddhdfvcb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2dfbgkupk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2iedkqjow.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gt2ircdczfz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gt2qjrmgycj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2clhwymgo.html

C#:   x is int or double or decimal
来源：http://dali.yonumen.top/Article/details/gt2lfkdtcbd.html

[B14] 判断值是否在集合内
来源：http://dali.sweek.top/Article/details/gt2ovskyqus.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gt2nzwriadp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gt2jhujqxao.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gt2szoxzbga.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jiagoushi.top/Article/details/gt2rgvwhlic.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.haohaochexian.top/Article/details/gt2ylxuxwrq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tcsdrxgl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gt2uaqficlz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.sysykeji.top/Article/details/gt2gxjsrjcu.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gt2ixzteoex.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gt2pxjfspcs.html

PHP:  $a && $b || !$c
来源：http://dali.yangfankeji.com/Article/details/gt2wzudktsb.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gt2jnnsbktw.html

TS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gt2kqkvcrzk.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gt2rvecyxov.html

Go:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gt2jmstnskt.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2csbmlxkg.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gt2gqlhqjyz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gzhubu.top/Article/details/gt2ifsdjjhu.html

Py:   if not data: return
来源：http://dali.nwbrower.top/Article/details/gt2aopjzbhy.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gt2npgekmqs.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gt2gwytakle.html

TS:   if (!data) return;
来源：http://dali.yangfankeji.com/Article/details/gt2wwupzlal.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gt2jqkckesx.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fnamkiup.html

Ruby: return if data.nil?
来源：http://dali.jyoumei.cn/Article/details/gt2uizslgvc.html

C#:   if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2itlcayct.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2siyxoloc.html

C. 函数与作用域
来源：http://dali.wangdashe.top/Article/details/gt2zxmwbdvw.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vqkgrnzg.html

[C01] 定义函数
来源：http://dali.sweek.top/Article/details/gt2hdwaoioc.html

Py:   def add(a, b): return a + b
来源：http://dali.zdqjudy.top/Article/details/gt2kfamcydc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ockmmcsz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clgxszjl.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2bnjbpslt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2exmjmmsf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dlhlluee.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gt2vudyawxf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2rdisauqz.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2sznmhsvp.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2entxwsfp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tteptkyp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cashguo.top/Article/details/gt2mbtyswcr.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gt2gmcervnn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2fyyvrhls.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gt2kguewegi.html

Ruby: def greet(name = "World") = name
来源：http://dali.jianghu66.top/Article/details/gt2tlronlwn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gt2owegdhnr.html

[C03] 可变参数
来源：http://dali.zhoulong.xyz/Article/details/gt2qajhjsso.html

Py:   def total(*args): return sum(args)
来源：http://dali.dashuyun.cn/Article/details/gt2hshbaslj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gt2tmtjihcg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2uinnpfck.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2setspogi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pjrzxfaf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jiagoushi.top/Article/details/gt2fkaawsmh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jiagoushi.top/Article/details/gt2zkzpmjfi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zdqjudy.top/Article/details/gt2lhfwtjga.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj202588.top/Article/details/gt2ytniwdbk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.guannengcc.top/Article/details/gt2mhhpbenc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2mvxgjiah.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.meibo888.top/Article/details/gt2yotjofyf.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qxoyfgga.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gt2fnhhdsoe.html

Go:   // 无：用配置结构体参数
来源：http://dali.gaohongyu789.top/Article/details/gt2cchwzjcn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hfpthk.cn/Article/details/gt2kljrctxa.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gt2dehwhxag.html

[C05] 返回多个值
来源：http://dali.yongpay.top/Article/details/gt2qigowdzr.html

Py:   return a, b
来源：http://dali.havefunace.top/Article/details/gt2fqonjpqe.html

PHP:  return [$a, $b];
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvhqrryf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2nrtnkiaa.html

TS:   return { a, b };
来源：http://dali.yueranfly.top/Article/details/gt2vcfjreno.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenlongwang.top/Article/details/gt2zqqchsqb.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2yolxfeyy.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gt2lnxcfuby.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gt2gkrtpbbl.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gt2ljigdsnx.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2vnhbokka.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenlongwang.top/Article/details/gt2nthwvihh.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bumiomyt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yqioylbj.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gt2osbihbpn.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gt2nktkjbkd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jcbezybd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2hjhepysk.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gt2qpmyfqte.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gt2rsgtfydb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.vqdsnc.cn/Article/details/gt2maluopwo.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ppjwa.cn/Article/details/gt2iivviyfu.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gt2halktuoe.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gt2jgewsryt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tianlin.xyz/Article/details/gt2waffiyxu.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2bbecbekx.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gt2pvhoupmx.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gt2agjghequ.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gt2rrwrprua.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2snjbghml.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2fzsrjvba.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gt2mlvzhmwg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gt2djnvomzr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.vqdsnc.cn/Article/details/gt2qyxhrlvr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gt2zcffrzwn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2erjdolfp.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gt2uovrotqa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2pjszxocm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.fzhhl.top/Article/details/gt2ptvktogx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sufxvd.cn/Article/details/gt2eedqkirw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2mxdkgplg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.dianchejie.cn/Article/details/gt2nftuxxwr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.dianchejie.cn/Article/details/gt2ttnzpqtf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gt2ijvtrtxm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gt2xjvdeksk.html

[C10] 变量作用域
来源：http://dali.nwbrower.top/Article/details/gt2qlpmrcyj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gt2sasiakky.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gt2scexjfil.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yuanzhike.top/Article/details/gt2gwuydesr.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gt2ujixagsb.html

Java: 方法内为块级作用域
来源：http://dali.shuidangran.top/Article/details/gt2qnwnmwsi.html

Go:   花括号块级作用域
来源：http://dali.dashuyun.cn/Article/details/gt2akhkzrpw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuanzhike.top/Article/details/gt2gxxkxjso.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2frkcrdfu.html

[C11] 模块导入与导出
来源：http://dali.xziqi.cn/Article/details/gt2pxljkrme.html

Py:   from module import func
来源：http://dali.yj202588.top/Article/details/gt2alxzlgjh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gt2ohfxtmmg.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.smart0.xyz/Article/details/gt2fjfddawy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pycfn.com/Article/details/gt2ibmnqacr.html

Java: import java.util.List;
来源：http://dali.gzhubu.top/Article/details/gt2ypecbfab.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2bckbbwmf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gzhubu.top/Article/details/gt2zsjhmddw.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gt2jnzlcoej.html

[C12] 立即执行函数 IIFE
来源：http://dali.ivvv.top/Article/details/gt2uzdcrzie.html

Py:   (lambda: print("run"))()
来源：http://dali.c1oappe.top/Article/details/gt2zqkgbbur.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gt2skeweryp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gt2ihlypvlq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gt2igatymrs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gt2qjmjumzk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgfzy.top/Article/details/gt2llbkebqz.html

Ruby: -> { puts "run" }.call
来源：http://dali.nwbrower.top/Article/details/gt2nneymrsx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhijiandao.cn/Article/details/gt2qafqegvx.html

[C13] 类型声明 / 类型注解
来源：http://dali.quarkkingdee.top/Article/details/gt2tnmhekyk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2frxuwque.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2vnimmckq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinqigufen.top/Article/details/gt2vvjcwkti.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2nenogfaz.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gt2qeqrxkcp.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gt2wadcdkdj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxinkj.top/Article/details/gt2jtwfthpp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.cdnleiting.top/Article/details/gt2ebitiffr.html

[C14] 泛型函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yhnweogr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gt2rzroyjpf.html

PHP:  // 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2bpnxxvpm.html

JS:   // 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2zvrzdnxo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cqqwz.cn/Article/details/gt2qayqbeow.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tanke756.top/Article/details/gt2oyxtzqyd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jinqigufen.top/Article/details/gt2hvrfonkr.html

Ruby: # 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2btsxbobr.html


<!-- 参考信息 -->