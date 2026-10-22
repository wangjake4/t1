代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aizwys.cn/Article/details/gtjlafnlpk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtpuoyttii.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.guannengcc.top/Article/details/gtchnjiedn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gtjzfvtlcn.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtocxdqyxg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.tanke756.top/Article/details/gtnmplesks.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.dashuyun.cn/Article/details/gtjpuitcpe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gaohongyu789.top/Article/details/gtayzjgwgm.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gttkkvnhgj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.redwolf501.top/Article/details/gtcixsdhxk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gtcgjtlpfa.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhongyouzk.top/Article/details/gtfcafymvm.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gthfnmuykx.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtujvoyvxo.html

B. 流程控制
来源：http://dali.vqdsnc.cn/Article/details/gtutviauut.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtetjidcjl.html

[B01] 条件判断 if / else
来源：http://dali.birdmap.top/Article/details/gtbglnsxrr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sweek.top/Article/details/gtvdxsqrnd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.tianlin.xyz/Article/details/gtubpxypbn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtvggfiako.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtezvqsufr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.daxiang520.top/Article/details/gtqqybjgil.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangdashe.top/Article/details/gtphlgfpvq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.andypj.xyz/Article/details/gtljrsvgyc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtarbwstxw.html

[B02] 多分支 else if / elif
来源：http://dali.yonumen.top/Article/details/gthiererel.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yangfankeji.com/Article/details/gtgdehkhgn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhixingplan.top/Article/details/gtxqjilstz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtltrcknqo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gteebzdeaa.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtpojbhkna.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yvedp.cn/Article/details/gtqhewcyqg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hysaishi.cn/Article/details/gtnqhilxqp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtmljrwjor.html

[B03] switch / match / case
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmwghizup.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xylfe.cn/Article/details/gtxopncmxc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yuxming.cn/Article/details/gtewdcnngd.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtcbuvkpvs.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gttsrbnjcx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtayxuktcz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtkrbuwhgw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.vqdsnc.cn/Article/details/gtpgkfdwny.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.birdmap.top/Article/details/gtmfvubhup.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtmmubifuj.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtlmiwglst.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtrfssuzbp.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqmlwxixp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtsqqfzrof.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtqkqlabyv.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gtfzoujkcv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.snrcjt.cn/Article/details/gtfrcgvayo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhoulong.xyz/Article/details/gthjnabyxh.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtvxcxsgec.html

Py:   for item in arr: print(item)
来源：http://dali.dashuyun.cn/Article/details/gthojwdaby.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.iojbl.cn/Article/details/gtmaopkaea.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtmmkwfztl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258.top/Article/details/gtvpkhanjg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtygbxvoxb.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ppjwa.cn/Article/details/gtlwurmbrw.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yonumen.top/Article/details/gtklwddkkb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtqpiqvdqz.html

[B06] 遍历字典 / 对象
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaignmtr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gtroriyqpz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jyoumei.cn/Article/details/gtnseruzgu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhndunct.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.9152youxi.cn/Article/details/gtkgzncbod.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtwjxqjiqk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtaacmrpkp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtmwmumkrk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gtkndxeyhx.html

[B07] while 循环
来源：http://dali.yanxiufei.cn/Article/details/gtrfbqixui.html

Py:   while i < 10: i += 1
来源：http://dali.birdmap.top/Article/details/gtanbnodse.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gteqcrdpjh.html

JS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gteclnjgts.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtcjjmpqwb.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gthtgudvqf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ppjwa.cn/Article/details/gtyghisoic.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtgeiosorc.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gthreynxlp.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gtsljgnddi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.mhx1999.top/Article/details/gtyyoozafj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gtktipsgwy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtdiwiwuyy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtndawkelv.html

Java: do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtrljipthi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtlqicznyd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.feifeiyinyue.top/Article/details/gtxetsnmif.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtalyrlnpa.html

[B09] break 与 continue
来源：http://dali.quarkkingdee.top/Article/details/gtirwgjvuf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gtnlgsohnd.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtzoaxqlpb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gthfhmwcxm.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtywfnmiup.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtvwssbkyf.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gteunytzhl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiqmiiyzn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtyowyvxnz.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtdbwcwlds.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nwbrower.top/Article/details/gtsdbglbmb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtzlelpkap.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aizwys.cn/Article/details/gtourgoyvi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gttzttdhyc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhixingplan.top/Article/details/gtlyabeizm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtttaawwxh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtnnqhiimg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmykywmp.html

[B11] 生成数字序列 / 区间
来源：http://dali.quarkkingdee.top/Article/details/gtofiqwchc.html

Py:   list(range(0, 10, 2))
来源：http://dali.snrcjt.cn/Article/details/gtjchaawou.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtuzgpchui.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gttgcpuzpu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtvswjcnyh.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtwshrixar.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtrirjjjpb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtnkdbamqw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gtbgygcpls.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtuystopgm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenjidiqi.icu/Article/details/gtrrlmeiuw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsigtjyv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuetiantiany.cn/Article/details/gtusqrmsqk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtbweqzkvw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtehpdhwuu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtgefmhbzg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.0kj1m.cn/Article/details/gtonhxkfzf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gteqqxboss.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtbujlhmey.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtmqvjjokm.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtpiiocxzh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtqgsflhoi.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gtkegmiioo.html

Java: x instanceof Number
来源：http://dali.feifeiyinyue.top/Article/details/gtfmbgtceu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gttugmwlvf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtwwtzdlpr.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtbokbvriw.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmlpdcee.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenjidiqi.icu/Article/details/gtnsuabxcv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenzaomai.com/Article/details/gtchkcxjdk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtajhycrks.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtvgcaxway.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtoqmrcemk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtucayzsrk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtpxqnhcup.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gttpoxsayq.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtrauunoby.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gthsutxoib.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxsmxeqyb.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtyadbfpfl.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtelmjkgzd.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtlffuyfwd.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtxrbzfcbu.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtcqfflakk.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gttpsadjda.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.fzhhl.top/Article/details/gtlacmxsjn.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gthuwoybxp.html

PHP:  if (!$data) { return; }
来源：http://dali.jlsjyb.cn/Article/details/gtuilwfzad.html

JS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtajxbkczm.html

TS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gtgvzwhaij.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtlotioimf.html

Go:   if data == nil { return }
来源：http://dali.yj20258888.top/Article/details/gtyryehddo.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gtdlptaxpl.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtowpjdsuc.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gttptrqxhk.html

C. 函数与作用域
来源：http://dali.xylfe.cn/Article/details/gteudptdgv.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarytujtb.html

[C01] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtdbetgsdd.html

Py:   def add(a, b): return a + b
来源：http://dali.yongpay.top/Article/details/gtzweugito.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjoclzzru.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtnxfdkhwg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtukyddgjy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtmowxbsrk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gtbtovfvje.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtbxakzlok.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtahyztrnp.html

[C02] 默认参数
来源：http://dali.jianghu66.top/Article/details/gtnaowupal.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtwngifnbd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zdqjudy.top/Article/details/gtapolvqsn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtyivyedka.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtbwmsrucf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gtyxolyppr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtcrxhjxjk.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtwsmgupgr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtgiodycmu.html

[C03] 可变参数
来源：http://dali.bjfxy.top/Article/details/gtagqpafrq.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpozobrt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenzaomai.com/Article/details/gtmhzrqklh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtpzlytujk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtfghvbmcf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258888.top/Article/details/gttdzavfqk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.meibo888.top/Article/details/gtdwwcvepu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtqkpbcfmv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtryeygrnj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtbvkcmi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gthcrpkuno.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gtojkgyveb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtnghpfftd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.fengsongda.top/Article/details/gtmctmgoif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtldepabje.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangdashe.top/Article/details/gtkyryfgmb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hammf.cn/Article/details/gtktgkprxu.html

C#:   f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtdnbvcjjs.html

[C05] 返回多个值
来源：http://dali.c1oappe.top/Article/details/gtadgwthjv.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtbburrqul.html

PHP:  return [$a, $b];
来源：http://dali.tian-w.cn/Article/details/gtoacvigbb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhiwuduotai.top/Article/details/gtsehbvwzi.html

TS:   return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtlzrlrcmh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigufen.top/Article/details/gtdjmsijks.html

Go:   return a, b
来源：http://dali.tanke756.top/Article/details/gtyxpqwofo.html

Ruby: return a, b
来源：http://dali.sufxvd.cn/Article/details/gtfzskgnba.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigfzy.top/Article/details/gtsyslbwgo.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtsfjdyzcc.html

Py:   square = lambda x: x * x
来源：http://dali.pengpengdd.cyou/Article/details/gtwnxvvczo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbuafshmd.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gtzaffyazt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gttqwbjdhu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gtkiinfubu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.gaohongyu789.top/Article/details/gtkfchtisu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.quarkkingdee.top/Article/details/gtgsjwrwlz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtninlzrhu.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtsukjrhbz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.birdmap.top/Article/details/gtkxfpymag.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtqhcucqif.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gtptnklrfu.html

TS:   arr.map(String)
来源：http://dali.wangshuangyany.cn/Article/details/gtldmccvgk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.kuanghao11.cn/Article/details/gtfdaezcuv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daxiang520.top/Article/details/gtbzrgqpts.html

Ruby: arr.map(&:upcase)
来源：http://dali.shuidangran.top/Article/details/gtzwmaokoh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gttjtyogey.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gteuhraoif.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxuanxn.top/Article/details/gtnoytgfjn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pycfn.com/Article/details/gtgvvsgpou.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtbqmbkoit.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.snrcjt.cn/Article/details/gtajgragym.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.gzhubu.top/Article/details/gtbhbwvkee.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yuanzhike.top/Article/details/gtxmnewllo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.chenlongwang.top/Article/details/gtfgwmessb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtzemmvqbu.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtdfkusyvg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cqqwz.cn/Article/details/gtukdvexdk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuanzx.com/Article/details/gtzuimotov.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.dianchejie.cn/Article/details/gttwrlvdik.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gtbeosiaqb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gzhubu.top/Article/details/gtjwlsifvp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yvedp.cn/Article/details/gtdnvxurzp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gtedbdwcpt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtiswawkya.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gtdkkrnuaa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gtqurrgtvd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtqluqknug.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.feifeiyinyue.top/Article/details/gtoghsgcmu.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gtwuwobned.html

Java: 方法内为块级作用域
来源：http://dali.jiagoushi.top/Article/details/gtxwypqgkx.html

Go:   花括号块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtnusjpsjw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtlgyzrwuu.html

C#:   块级作用域
来源：http://dali.andypj.xyz/Article/details/gtxgzdccrd.html

[C11] 模块导入与导出
来源：http://dali.yuxming.cn/Article/details/gtqeoseeeq.html

Py:   from module import func
来源：http://dali.nanxuanxn.top/Article/details/gtrvxjdqmu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.wangshuangyany.cn/Article/details/gtqvllygzt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinqigufen.top/Article/details/gthjhdejug.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtiavymuiw.html

Java: import java.util.List;
来源：http://dali.yanxiufei.cn/Article/details/gtgivvgutu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhengqikj.top/Article/details/gtvknnwsso.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hysaishi.cn/Article/details/gtrdektknd.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtbrlqhvkz.html

[C12] 立即执行函数 IIFE
来源：http://dali.daria6918.cn/Article/details/gtnuflckyo.html

Py:   (lambda: print("run"))()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepwitxfd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtafwjirct.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtntnwbrcz.html

TS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtmqidkoma.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gtldwgjnba.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gtvpnhyfgt.html

Ruby: -> { puts "run" }.call
来源：http://dali.yuanzhike.top/Article/details/gtlipqjvgt.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yueranfly.top/Article/details/gtckhwxwyn.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtamvvywie.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zdqjudy.top/Article/details/gtivexsuic.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtoxafhnwh.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtbiihmibo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtjisfpmqb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtpzfrvqpl.html

Go:   func add(a, b int) int
来源：http://dali.sufxvd.cn/Article/details/gtmbthsusw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hfpthk.cn/Article/details/gthtakvjkh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nanxuanxn.top/Article/details/gtjymuxygb.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtdoxbnjgi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.daxiang520.top/Article/details/gtemxlvysf.html

PHP:  // 无泛型
来源：http://dali.hnqzz.top/Article/details/gtbtqdhkbu.html

JS:   // 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtinqqwvco.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtoermrctf.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.dianchejie.cn/Article/details/gtkyluadso.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtvwxbvsns.html

Ruby: # 无泛型
来源：http://dali.yvedp.cn/Article/details/gtlnbxjhgt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zdqjudy.top/Article/details/gtrjyabgyc.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtslbpwnah.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yj20258888.top/Article/details/gtaikooflt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gtctsggrjl.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtgarwuajn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sweek.top/Article/details/gttrqzwuxw.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gtsorrhzku.html

Go:   // 无解构
来源：http://dali.jyoumei.cn/Article/details/gtlwyadzpr.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtpqhehwdm.html

C#:   var (a, b) = pair;
来源：http://dali.zhoulong.xyz/Article/details/gtqsipuxow.html

[C16] 函数 / 方法重载
来源：http://dali.haohaochexian.top/Article/details/gtiachmrqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxnsuokt.html


<!-- 参考信息 -->