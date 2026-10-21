代发 wailian999

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.sxryk.cn/Article/details/gtcyonwqwr.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtuylagaxa.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gtehnrsxie.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtegrrrdex.html

[B01] 条件判断 if / else
来源：http://dali.haohaochexian.top/Article/details/gtmjvvfzkk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.daria6918.cn/Article/details/gtgsjcgnym.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gttycqylpr.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.smart0.xyz/Article/details/gtixuzseuh.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtjqjinnrs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtbvxsgkhq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.0kj1m.cn/Article/details/gtarqwjane.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.mhx1999.top/Article/details/gtcavawnkz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtarhdkfoa.html

[B02] 多分支 else if / elif
来源：http://dali.kuanghao11.cn/Article/details/gtuubheekm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hfpthk.cn/Article/details/gtitmahzdf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.c1oappe.top/Article/details/gtphckcbfi.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtwjqrqsbk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtuqihkixx.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gttupmvdgd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtawjyhukq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtoavusxsf.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtroildrjl.html

[B03] switch / match / case
来源：http://dali.jiagoushi.top/Article/details/gtkvkmvquu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gttwlepazy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtlzjztdcj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtufolczjp.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtckbqyhdc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkicemqgf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtcwahicdu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jianghu66.top/Article/details/gtejvdovsy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtrlhbmmsr.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtvxqojybr.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtwwazrpin.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gtktdobxcq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtseopbvpz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nwbrower.top/Article/details/gtawjfkjhi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guowangkeji.top/Article/details/gtrpjhblsb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jyoumei.cn/Article/details/gtggtpgdve.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenjidiqi.icu/Article/details/gtmwxlocnt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhixingplan.top/Article/details/gtddvingjl.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtguixlhfo.html

Py:   for item in arr: print(item)
来源：http://dali.xylfe.cn/Article/details/gtzgrcbtrm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmxjzhqro.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangdashe.top/Article/details/gtuifbumuw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtrbyvclqx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cashguo.top/Article/details/gtpkujmkox.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gttkephdgb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jianghu66.top/Article/details/gtkjvztqgv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhengqikj.top/Article/details/gtperhfplj.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgfzy.top/Article/details/gtbhacjqsj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.aibaodan.cn/Article/details/gtamuxjrrr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhoulong.xyz/Article/details/gthbegfdjd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlhvzkbcq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gthaxkirsz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nanxuanxn.top/Article/details/gtrifyhvgi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinqigufen.top/Article/details/gtsmqkjzzu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gtjvdznmal.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gtfeygtcjh.html

[B07] while 循环
来源：http://dali.gaohongyu789.top/Article/details/gtpsiehqbz.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtzmqfpkwf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtdjomvzuv.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gtwrnplety.html

TS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuygdkxvv.html

Java: while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtljgtlbmo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtzpjwxbwe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.smart0.xyz/Article/details/gtxcvklvre.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtieyuabre.html

[B08] do-while（至少执行一次）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjixsjuez.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ivvv.top/Article/details/gttxpczezr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj20258888.top/Article/details/gtcmoimsiw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtdtpkzqpw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtuunqbiye.html

Java: do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtootpalyh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.smart0.xyz/Article/details/gtukbjngoy.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtnahvqwvp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gtxnctmqli.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtkimyyjtp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtrijhwvdj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtbydyxdtn.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtoxtfdtyd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtgcyayiae.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtbedqrjex.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xziqi.cn/Article/details/gtlxgvalaa.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sxryk.cn/Article/details/gtiqjxrmkd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtfzfqosnp.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtasnqndbg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyvkvhwus.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtazllzojo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtulcxvjzl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtruihuzzw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtmlovrmyl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gtgcsscpey.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtujwbnfew.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jyoumei.cn/Article/details/gtdmyjcoyi.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gtyommvqja.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtqqcqghfk.html

PHP:  range(0, 10, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtzzcrqeny.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtwwprpbvv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tian-w.cn/Article/details/gtiqrtbbbq.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sweek.top/Article/details/gtwplhyhyt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jyoumei.cn/Article/details/gtfpdyscsa.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yuanzhike.top/Article/details/gtzpuijghr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gtwwipqlgt.html

[B12] 跳出多层循环
来源：http://dali.yonumen.top/Article/details/gtybgrgjql.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtoqxoptlf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gtjsmvghnd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cdnleiting.top/Article/details/gtgdlmewsj.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtygypvgst.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhixingplan.top/Article/details/gtxfgmzuei.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yvedp.cn/Article/details/gtyejotbtj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jianghu66.top/Article/details/gtkabcsuwk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenzaomai.com/Article/details/gtsakmnjiy.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gtfumkytqd.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj202588.top/Article/details/gtyaysfpop.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gthpoquhio.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gtppphxxhm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtmtmdzxpv.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtlpwbdqvq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtphzndfao.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sweek.top/Article/details/gtwpzpkgov.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqyrbfxk.html

[B14] 判断值是否在集合内
来源：http://dali.jinghuilouyu.cn/Article/details/gtsiodunjy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtcdlrnwmq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tianlin.xyz/Article/details/gttxyqmhmt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtewincfgp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtcxajblax.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaqtiphs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.feifeiyinyue.top/Article/details/gtuxkyrxzo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtftcnbnzz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtyotdrtno.html

[B15] 布尔运算与取反
来源：http://dali.cdnleiting.top/Article/details/gtrdjnyvpf.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gtrkgvlqpi.html

PHP:  $a && $b || !$c
来源：http://dali.redwolf501.top/Article/details/gtzgclgmgv.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtaeumexlm.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtlapcntgw.html

Java: a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtacgdnwjw.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtkunrwbuq.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtkkebpjqd.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqovifdig.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtbxtxybvy.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtalbgsmoj.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtlocpaven.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtfxbaemph.html

TS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtkuwpweyc.html

Java: if (data == null) return;
来源：http://dali.gogol.net.cn/Article/details/gtravmmzqa.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtmhkrrkme.html

Ruby: return if data.nil?
来源：http://dali.zhengqikj.top/Article/details/gtouhuffuh.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtmyhotcqr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gttyxybkxi.html

C. 函数与作用域
来源：http://dali.zhongyouzk.top/Article/details/gtfhfdrvqj.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtvsflrxyb.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtbpkdvtrw.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtqrcgruvd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsctooats.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxsadypt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtdkrvpdcd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtlvmlkgyi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gtaerqnfug.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gtrtjbfaof.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtnpcpxgrr.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtufgfsunk.html

Py:   def greet(name="World"): return name
来源：http://dali.xinyue.icu/Article/details/gthjlutltc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.kuanghao11.cn/Article/details/gtednxzlvc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtgyjqwtgj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtgojqzuds.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xinyue.icu/Article/details/gtluosdymd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jianghu66.top/Article/details/gttvbnywmf.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtilegblid.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gtjmfbbzmt.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtvnzwtivt.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtbeewmxir.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruakasqe.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtyndvodge.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtqcqpqjjs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yvedp.cn/Article/details/gtbqxijqvo.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258888.top/Article/details/gtgzvmjdwb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gtxwfzvjva.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhongyouzk.top/Article/details/gtfugspzuj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtooqoqcyn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sysykeji.top/Article/details/gtqoweruwu.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.iojbl.cn/Article/details/gtnlycvomt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shzxlz.cn/Article/details/gtwzqjtvkb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenzaomai.com/Article/details/gtpfrhufrj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtfekjxyhe.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtnhexjobz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtrjupfbvq.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtsazdydgn.html

[C05] 返回多个值
来源：http://dali.shangyingyoupin.top/Article/details/gtuthwjnwy.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtuysnatrs.html

PHP:  return [$a, $b];
来源：http://dali.nanxuanxn.top/Article/details/gtxndovqmi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yvedp.cn/Article/details/gttzqipozl.html

TS:   return { a, b };
来源：http://dali.birdmap.top/Article/details/gtdywvnife.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinqigfzy.top/Article/details/gtduwfdbpf.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtfvkrhhia.html

Ruby: return a, b
来源：http://dali.hammf.cn/Article/details/gtqszoygqr.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtprvypooj.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtpgeofxou.html

Py:   square = lambda x: x * x
来源：http://dali.cucudq.cn/Article/details/gtsmopdtdj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtjkfuwtyl.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtpjranfoy.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtruqjfxod.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ybcxt.top/Article/details/gtlunvlsud.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtznwpstqw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jiagoushi.top/Article/details/gtzatzifpg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.mhx1999.top/Article/details/gtfutdqvbv.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtwoqexeyz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yongpay.top/Article/details/gtyfwsgzav.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtwqzqbctl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ybcxt.top/Article/details/gtrukijbkc.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gtfoyujffk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtfvmxgsmb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.sxryk.cn/Article/details/gtednskpkq.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtbghwkkny.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtimtqyfay.html

[C08] 闭包
来源：http://dali.jlsjyb.cn/Article/details/gtejespzog.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhixingplan.top/Article/details/gtzbesbrls.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtwykwiakd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtuskwqpcq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtnclzhunj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gtyossuvxd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsvmuvnj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gtwxigqwgh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtetawitgt.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtnjptttqg.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.316326.xyz/Article/details/gtcffkorsb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.meibo888.top/Article/details/gtypfostpr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtffedzmzm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtnzcprzww.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtiusfhdzd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtzkkllarb.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtkloxfdyw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gtqxuffsgf.html

[C10] 变量作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyooqhzqe.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gturvmlgdo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhengqikj.top/Article/details/gtupcmttjr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gthsjevgqc.html

TS:   同 JS
来源：http://dali.cucudq.cn/Article/details/gtizfaisxl.html

Java: 方法内为块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtitjxdyja.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gthxrnxygg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtzurufhru.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtcgwrpmma.html

[C11] 模块导入与导出
来源：http://dali.gotoacloud.top/Article/details/gtkxquqxiq.html

Py:   from module import func
来源：http://dali.daria6918.cn/Article/details/gtflxchnso.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhixingplan.top/Article/details/gtgasogams.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yj20258888.top/Article/details/gtzawkurxz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nanxuanxn.top/Article/details/gtbzctkwqu.html

Java: import java.util.List;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmhppbtuq.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtisvjllqe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gaohongyu789.top/Article/details/gtofcdkcdm.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtoxfxsqxo.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtauiarxbr.html

Py:   (lambda: print("run"))()
来源：http://dali.chenjidiqi.icu/Article/details/gtdsjiojxw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtqjenypfw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtyrmswxkp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xuanzx.com/Article/details/gtyvfhoygk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.316326.xyz/Article/details/gtyygbxevz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gaohongyu789.top/Article/details/gtptteehmm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtddxwsvcc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.aibaodan.cn/Article/details/gtwszqadtk.html

[C13] 类型声明 / 类型注解
来源：http://dali.havefunace.top/Article/details/gtiirmuwyz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.gaohongyu789.top/Article/details/gtaikcgsli.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjwuybet.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gzhubu.top/Article/details/gtpawlyfod.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtsgminres.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.daria6918.cn/Article/details/gtmblecfly.html

Go:   func add(a, b int) int
来源：http://dali.hammf.cn/Article/details/gtyfvzcowu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtfamnzxql.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtgdpykfrs.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtrhyffzhj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlescpthm.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtpwjfnlkf.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtzwdyyvqe.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.9152youxi.cn/Article/details/gtksewafps.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangdashe.top/Article/details/gtisukluyt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cheryme.top/Article/details/gtalnnpdez.html

Ruby: # 无泛型
来源：http://dali.tanke756.top/Article/details/gtoexyxddg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jiagoushi.top/Article/details/gtefhzysof.html

[C15] 解构 / 展开参数
来源：http://dali.hywenlv.cn/Article/details/gtdwnjaiki.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gtzmdrbbgh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.fengsongda.top/Article/details/gtazwrwkbd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtaopoyraz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ivvv.top/Article/details/gtegoxgbuo.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtpkgpihik.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtfppqeikr.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gtmppmqbih.html

C#:   var (a, b) = pair;
来源：http://dali.jqgfzy.top/Article/details/gthpuruosq.html

[C16] 函数 / 方法重载
来源：http://dali.gaohongyu789.top/Article/details/gtfnpeyvjg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqqcejed.html

PHP:  // 无重载
来源：http://dali.guowangkeji.top/Article/details/gtuxrbcyog.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigfzy.top/Article/details/gtebkmwbsr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhoulong.xyz/Article/details/gtpcfbkwsv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gtwhbazuhk.html

Go:   // 无重载：用不同函数名
来源：http://dali.zdqjudy.top/Article/details/gtuquiwqaf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gaohongyu789.top/Article/details/gtameuipyv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhengqikj.top/Article/details/gtktfmhphk.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwhrglaad.html

D. 数组 / 列表 / 集合
来源：http://dali.hfpthk.cn/Article/details/gtbjyqxdgm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtkqnnwstb.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtiqdzspff.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jianghu66.top/Article/details/gtihshjrcy.html


<!-- 参考信息 -->