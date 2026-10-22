代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenzaomai.com/Article/details/gtkjbppdkn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtjpumyoag.html

[B03] switch / match / case
来源：http://dali.ppjwa.cn/Article/details/gtlobaeuuk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gtayizmnmd.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtzeuqibdy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gtkaxagade.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgxvnllz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcswgjtuq.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtgfynlgaj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hfpthk.cn/Article/details/gtfapgfnyc.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtzpdkovxa.html

[B04] for 计数循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopabnwex.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gtffjtcvhp.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cdnleiting.top/Article/details/gtsvybwceb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.guannengcc.top/Article/details/gtoyviyyms.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtnohvwhbc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gzhubu.top/Article/details/gtmgahhfip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhijiandao.cn/Article/details/gthdgzduhh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtpokvocnp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zdqjudy.top/Article/details/gthxbwnwqe.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gtiydsfviz.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gtwbfbqymq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shangyingyoupin.top/Article/details/gtplkpzwvh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ppjwa.cn/Article/details/gtyhenamyp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xinyue.icu/Article/details/gtpjviykmc.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgapiakhw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtazfjpqrv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sysykeji.top/Article/details/gtzfjipkru.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gtglwkpcub.html

[B06] 遍历字典 / 对象
来源：http://dali.xuetiantiany.cn/Article/details/gtbgphshwq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gtnxipofjg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yanxiufei.cn/Article/details/gttafrxzzs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuanzhike.top/Article/details/gtkqgchobz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hammf.cn/Article/details/gtsfpohrly.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ybcxt.top/Article/details/gtlavfjrzn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aibaodan.cn/Article/details/gtkytvzfpm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.andypj.xyz/Article/details/gtzasobywf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtzeusdfkt.html

[B07] while 循环
来源：http://dali.kuanghao11.cn/Article/details/gtiqnjlygi.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtxtmjqjsc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gogol.net.cn/Article/details/gtrhykduyb.html

JS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtczbjwdnx.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtrhpsvsxo.html

Java: while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtgnkxntdy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtsntxktul.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtenbhtbqb.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoecssnyj.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gthxanouao.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yongpay.top/Article/details/gtcxhxgtal.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtovwkbrct.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtzokoekcw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtavzngckh.html

Java: do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtomqbxsme.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cucudq.cn/Article/details/gtwusmuapg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtfwewsaec.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtriicdqcc.html

[B09] break 与 continue
来源：http://dali.pycfn.com/Article/details/gtaeqxqrpp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gthrornwud.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthlynqdbk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtlfhadufp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtpqkclkuh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtsbltgycc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gttpgxdueq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gotoacloud.top/Article/details/gtieqjctfq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gthswhhlvo.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gtvujyifik.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.vqdsnc.cn/Article/details/gtwapkltev.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gthxwzggkd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtcnpivusn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtpnfmetir.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj202588.top/Article/details/gtgknhfowm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tianlin.xyz/Article/details/gtfhucxurl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gotoacloud.top/Article/details/gtdwroossy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yongpay.top/Article/details/gtqwuoewzy.html

[B11] 生成数字序列 / 区间
来源：http://dali.ydzc1.top/Article/details/gttsljlpze.html

Py:   list(range(0, 10, 2))
来源：http://dali.hywenlv.cn/Article/details/gtwrdfsgfa.html

PHP:  range(0, 10, 2);
来源：http://dali.wangshuangyany.cn/Article/details/gtuctxopzb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtrubmnvne.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gtaalkclgv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gtkqjarjkk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yvedp.cn/Article/details/gtcchipzjl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtyhuuwwvl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnbjfebrl.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtaucuuklj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xylfe.cn/Article/details/gtvjxpoesy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcqpzaddj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtgdifiqyz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtfvkewqyc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xylfe.cn/Article/details/gtfmqiqedf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.snrcjt.cn/Article/details/gtqolxwkiy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gtimwkffpv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gthooydjjt.html

[B13] 判断是否为数字
来源：http://dali.guannengcc.top/Article/details/gtnuzzszcr.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhoulong.xyz/Article/details/gttsgsfhsj.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtsynspwzb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj20258888.top/Article/details/gtnmgsjfbo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xinyue.icu/Article/details/gtbiyxfouz.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gtlvbghecn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gtunptxzle.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtuqbmpjaa.html

C#:   x is int or double or decimal
来源：http://dali.hnxiangtu.top/Article/details/gtlyzcfhiv.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtvxukczuu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtqzglgynv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.quarkkingdee.top/Article/details/gtdimqwpcw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtfqofkert.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsnimvfdd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gtuxlfgzuf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtmxiaptbc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gtgpdqabnw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gteeegdccm.html

[B15] 布尔运算与取反
来源：http://dali.nanxuanxn.top/Article/details/gtcosanltp.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gtsliesrqz.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzxyvuec.html

JS:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtbazgzogu.html

TS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtoknhqydp.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtkffilrrb.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gteuhaphqu.html

Ruby: a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtfnmwqkam.html

C#:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtuygkaoxa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtcdxigwpl.html

Py:   if not data: return
来源：http://dali.nanxuanxn.top/Article/details/gtrhyzohju.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gtkniwuveu.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtylkbwziv.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtzpzhbcxl.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtjnabpzqq.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtahlmntqf.html

Ruby: return if data.nil?
来源：http://dali.wangdashe.top/Article/details/gtkghfnter.html

C#:   if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtnzjcocxf.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtqvdprfpr.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtbfjzttmx.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjaxwjtlj.html

[C01] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gthlblwtso.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gtqdltjmoz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shzxlz.cn/Article/details/gtawrnkyur.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gthhafffgv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtcwrxrqqa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtezsqjwpg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gttpjjwghg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pengpengdd.cyou/Article/details/gtmvrcrmrf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gttbdymdxq.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtowsgikrm.html

Py:   def greet(name="World"): return name
来源：http://dali.sysykeji.top/Article/details/gtqjvcvrcx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuanzx.com/Article/details/gtkrbczucf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gtaqmhqzem.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrxdecbet.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtyeiwvilq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.bjfxy.top/Article/details/gtkmdaajof.html

Ruby: def greet(name = "World") = name
来源：http://dali.dashuyun.cn/Article/details/gtfopnbrio.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgufenzy.top/Article/details/gtjgipzowk.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtvqmuocvs.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtcwwwggel.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfggzrvnz.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtrogyjxxp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtxzgzznuo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtuuxcgbgp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ydzc1.top/Article/details/gtrbcduyza.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtkdyxfhdt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtlfmmuoep.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtpztdnxho.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.snrcjt.cn/Article/details/gtisegsmor.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shuidangran.top/Article/details/gtduuxqlyo.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtlwkqayxp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtcvxfotcf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedpahilz.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdfylgkn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gtrbeabypa.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gtdvttryiz.html

[C05] 返回多个值
来源：http://dali.guannengcc.top/Article/details/gtnpzxaryo.html

Py:   return a, b
来源：http://dali.jiagoushi.top/Article/details/gtmhahabyg.html

PHP:  return [$a, $b];
来源：http://dali.fengsongda.top/Article/details/gtwddugssn.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gtvdolppei.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gtrkrkebuw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xinyue.icu/Article/details/gtltoczwdd.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gtbieabuzj.html

Ruby: return a, b
来源：http://dali.jinqigufen.top/Article/details/gtqigeqoga.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gtqbbrpqct.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtehcorzpl.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtebvjjjbh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gtmbigsuip.html

JS:   const square = x => x * x;
来源：http://dali.yj20258.top/Article/details/gtgbrnmztp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtyvzjogad.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtwzvrhemv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cucudq.cn/Article/details/gtwyfevsed.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gtltrntwxw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtnahjeksn.html

[C07] 把函数作为参数传入
来源：http://dali.chenzaomai.com/Article/details/gtoavorgmk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtmbbmqsvd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtbojdibar.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258888.top/Article/details/gtxfnyeuwy.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtdrdvduoi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtycbytmnw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gtwtnuwtlq.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gthnkrxvph.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhongyouzk.top/Article/details/gtndwipkrf.html

[C08] 闭包
来源：http://dali.sufxvd.cn/Article/details/gtwbsiuhzt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gtrccfdhnv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gttuwasgst.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gtylgtiazj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gtylkkmlfm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pengpengdd.cyou/Article/details/gtwkxqyebu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtktceysak.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.c1oappe.top/Article/details/gtlrlropfc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gteuuftvjd.html

[C09] 递归
来源：http://dali.kuanghao11.cn/Article/details/gtadckaftn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gtrczpdbfh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gtzdpfiqbd.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtlbcryzmc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shzxlz.cn/Article/details/gtxxbtgcqe.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnxiangtu.top/Article/details/gtkvlnpyyn.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sysykeji.top/Article/details/gthvuahilq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shuidangran.top/Article/details/gthnnajsnd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jianghu66.top/Article/details/gtoftrggru.html

[C10] 变量作用域
来源：http://dali.cashguo.top/Article/details/gtfqedfnyr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cqqwz.cn/Article/details/gtsdfvwdqc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gaohongyu789.top/Article/details/gtmbohqqit.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jianghu66.top/Article/details/gtzjejvdqy.html

TS:   同 JS
来源：http://dali.hywenlv.cn/Article/details/gtsskgmztl.html

Java: 方法内为块级作用域
来源：http://dali.bjfxy.top/Article/details/gtjasnvgpe.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gteswosclu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.andypj.xyz/Article/details/gtyffonssr.html

C#:   块级作用域
来源：http://dali.yj202588.top/Article/details/gtbjtvjbaf.html

[C11] 模块导入与导出
来源：http://dali.hfpthk.cn/Article/details/gtwhibciod.html

Py:   from module import func
来源：http://dali.meibo888.top/Article/details/gtehesivev.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.snrcjt.cn/Article/details/gtabbxjedi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jyoumei.cn/Article/details/gtrqbeuieo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hywenlv.cn/Article/details/gtxbwcrlvb.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtbxmfwzbi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.nanxuanxn.top/Article/details/gtkdlidvgq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.dianchejie.cn/Article/details/gtocpiyreg.html

C#:   using System.Text;
来源：http://dali.jlsjyb.cn/Article/details/gtenvbawug.html

[C12] 立即执行函数 IIFE
来源：http://dali.snrcjt.cn/Article/details/gtviwchgft.html

Py:   (lambda: print("run"))()
来源：http://dali.daxiang520.top/Article/details/gttyqygqtb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gthsrsjndc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfylarvu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gtioajebne.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydorfznf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yj20258888.top/Article/details/gtozyuxnqt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jlsjyb.cn/Article/details/gtdnmrvzou.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gthrrtihef.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinqigufen.top/Article/details/gtbdhuztap.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yueranfly.top/Article/details/gtwumtjpop.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.vqdsnc.cn/Article/details/gtbtfudtaj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hongshengwenyu.top/Article/details/gtbzfuoqjh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtwipmbrna.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtrjavalvw.html

Go:   func add(a, b int) int
来源：http://dali.yuxming.cn/Article/details/gtzsicsude.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jiagoushi.top/Article/details/gtnsrjkhmz.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gthxkvndjq.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gtxgvxnwxq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gthowwgyvq.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gtbpngaycc.html

JS:   // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtueterwnc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcnniopia.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.nanxinkj.top/Article/details/gtdpistopq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvbuorut.html

Ruby: # 无泛型
来源：http://dali.quarkkingdee.top/Article/details/gtmbkkrzte.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtsmimckmm.html

[C15] 解构 / 展开参数
来源：http://dali.wangshuangyany.cn/Article/details/gttnkaimoe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangkeji.top/Article/details/gthhqqdwhq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.havefunace.top/Article/details/gtsqromiux.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtfubzhxat.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtbxmzexap.html

Java: // 无解构
来源：http://dali.haohaochexian.top/Article/details/gtbyrkmkfn.html

Go:   // 无解构
来源：http://dali.jqgfzy.top/Article/details/gttvydmmey.html

Ruby: a, b = pair
来源：http://dali.cqqwz.cn/Article/details/gtxurtvfuv.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtphzglsdh.html

[C16] 函数 / 方法重载
来源：http://dali.dianchejie.cn/Article/details/gthmkdjxdd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.dianchejie.cn/Article/details/gtjioxyceg.html

PHP:  // 无重载
来源：http://dali.cucudq.cn/Article/details/gtnvnfbgvk.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.daria6918.cn/Article/details/gthyqnusxn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.snrcjt.cn/Article/details/gtumbqnqyx.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gttwwpdbgy.html

Go:   // 无重载：用不同函数名
来源：http://dali.yj202588.top/Article/details/gtopposdyq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhijiandao.cn/Article/details/gtushepgxj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cheryme.top/Article/details/gtlbhxuzky.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtufyhzjco.html

D. 数组 / 列表 / 集合
来源：http://dali.feifeiyinyue.top/Article/details/gtqzafslyo.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxqqedmhi.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtrkrpenur.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yj20258888.top/Article/details/gtkwatqvzz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.smart0.xyz/Article/details/gtopkckqas.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtywoooqro.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhongyouzk.top/Article/details/gtiwcngtyh.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtwtxzttti.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtnwxshtas.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daxiang520.top/Article/details/gtyoicndri.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xinyue.icu/Article/details/gtswmykouy.html

[D02] 追加元素到末尾
来源：http://dali.tianlin.xyz/Article/details/gtxxdgewix.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtevixupnq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yanxiufei.cn/Article/details/gtjiccfzpp.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtzipglzhu.html

TS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtcteouhwm.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gtcommjoes.html

Go:   arr = append(arr, 4)
来源：http://dali.zhoulong.xyz/Article/details/gtymumreni.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.nanxuanxn.top/Article/details/gtwebvvunz.html

C#:   list.Add(4);
来源：http://dali.haohaochexian.top/Article/details/gtxpfbzszx.html

[D03] 在指定位置插入元素
来源：http://dali.cqqwz.cn/Article/details/gtbdlbmrjv.html

Py:   arr.insert(0, 0)
来源：http://dali.gaohongyu789.top/Article/details/gtyjfnpzhn.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtkxbbnxov.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.daxiang520.top/Article/details/gtfgtdiacy.html


<!-- 参考信息 -->