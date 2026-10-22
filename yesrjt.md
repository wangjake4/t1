代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtjfnprlht.html

[B02] 多分支 else if / elif
来源：http://dali.birdmap.top/Article/details/gtoslbtmzv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gtprwfnqhj.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gtzowivxpr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtfqwgafpr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yangfankeji.com/Article/details/gtxnverkol.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gtdupiwqpj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gtiunorlos.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.zhongyouzk.top/Article/details/gtptpzpuiv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtdokqyqrb.html

[B03] switch / match / case
来源：http://dali.feifeiyinyue.top/Article/details/gtrurzydjj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cheryme.top/Article/details/gtchwolosw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gtfgqbqvun.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmfybcfoi.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtlzfdwsmh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gttaihbmvj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gtpcvljrsr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jlsjyb.cn/Article/details/gtgxrmqrnd.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gthceoowjz.html

[B04] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtoinvndmu.html

Py:   for i in range(10): print(i)
来源：http://dali.mhx1999.top/Article/details/gtkxyzraom.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sufxvd.cn/Article/details/gtsybhhpky.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sweek.top/Article/details/gtstpujuqz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtxvwtxfxw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.bjfxy.top/Article/details/gtlmdhuejf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gtfqaqepsc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ydzc1.top/Article/details/gtiofxpkua.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtnigfsgar.html

[B05] 遍历数组 / 列表
来源：http://dali.sweek.top/Article/details/gtywpkkjls.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtyholodyu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hammf.cn/Article/details/gtqopgxfgu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtxzqiuqln.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtsjjemjli.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtcclgbuwx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtwdiomqoi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gtatjgpbba.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xylfe.cn/Article/details/gtslkkeotq.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gtwfnwvfms.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gtdxdkjapd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuxming.cn/Article/details/gtggnoajdr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtbfroyxqe.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtoksorfms.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gteuwraqln.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtbgkehipn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gtgcpfselw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtrkgvbice.html

[B07] while 循环
来源：http://dali.shzxlz.cn/Article/details/gtydreoxys.html

Py:   while i < 10: i += 1
来源：http://dali.hnqzz.top/Article/details/gtbuegokuu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtrwqzgbzx.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtigdxufvo.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykeyjlwu.html

Java: while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtsidvxcip.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gtfdjtyyvz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj202588.top/Article/details/gtdlijezog.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwshfbzil.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtohrzxzjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtsewjzcdu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtsmqhhbrl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtfhglyqyy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtdnfrqfuf.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtzmrkgkgp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtvlwcwaha.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gogol.net.cn/Article/details/gtwextstax.html

C#:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtawejwlkp.html

[B09] break 与 continue
来源：http://dali.sweek.top/Article/details/gtibyafhag.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtuqquezjj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwieayrsu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtqwlnlqas.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtxpwgmomw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtckjivxpr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthxjytwjg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yuanzhike.top/Article/details/gtenisvzxj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtkwmsnlbr.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtovertvol.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtqxiosjkj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtonyrgooe.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sxryk.cn/Article/details/gtfmhaiwon.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtiymrvezh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jianghu66.top/Article/details/gttfoqiudt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtwlvrnmof.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gtjlxvxvtb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtgcqcdhys.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhongyouzk.top/Article/details/gtrgyirwqx.html

Py:   list(range(0, 10, 2))
来源：http://dali.zycfv.cn/Article/details/gtiykvzlkd.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtxjmtdxdn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtflrozdgt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtxudhxpdx.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgxixccmp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtbtvkddzl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.316326.xyz/Article/details/gthptceryo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuetiantiany.cn/Article/details/gttatgtjux.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtudizfcsb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jyoumei.cn/Article/details/gtjxzhtpok.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtywmkanxw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtltitzeij.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtevzkaxsq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtkrtvliqe.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtxjaojmzf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shangyingyoupin.top/Article/details/gtcpburrlz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cucudq.cn/Article/details/gtxteetmcm.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtnpfpssjl.html

Py:   isinstance(x, (int, float))
来源：http://dali.yanxiufei.cn/Article/details/gtrknmuynh.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gtdrmfcxim.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hnqzz.top/Article/details/gtypsljggw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.redwolf501.top/Article/details/gtkgevmrep.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtkimxmktn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangdashe.top/Article/details/gtsqgvrkvo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yanxiufei.cn/Article/details/gtewpmebxp.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtukfzkhyq.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtvnrxeqbj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtmzapejao.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtikhgwxza.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtgozlyxff.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gtdbkrqeos.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.0kj1m.cn/Article/details/gtpgvlxlqx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtctifpivi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.bjfxy.top/Article/details/gtpihpkzbb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tian-w.cn/Article/details/gtjefrddjs.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gttrluuoju.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gtmjgaebjq.html

PHP:  $a && $b || !$c
来源：http://dali.svipenyu.cn/Article/details/gtxdxskecy.html

JS:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtvrrkagax.html

TS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gteubsngix.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbtkmodxn.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtryjnnbka.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcbpbusda.html

C#:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtuuureezm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtxachgctu.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtvrypganu.html

PHP:  if (!$data) { return; }
来源：http://dali.cqqwz.cn/Article/details/gtvwpafeuf.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtiquepqjc.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtfretbxdy.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtdhowkxgs.html

Go:   if data == nil { return }
来源：http://dali.zhijiandao.cn/Article/details/gtqmajfzxx.html

Ruby: return if data.nil?
来源：http://dali.chenzaomai.com/Article/details/gtdchwwkol.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtmhxpuvyv.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtkgubncty.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtoznigjat.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtfpjshfbu.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtrwxbcjah.html

Py:   def add(a, b): return a + b
来源：http://dali.bjfxy.top/Article/details/gtyuyqyjrb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtokbakvtj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtyvnlxgfw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtfxyzultm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gttyfmfqvi.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gthpiuokxj.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ivvv.top/Article/details/gtfgwzycaj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtlltjhlpt.html

[C02] 默认参数
来源：http://dali.ehwqpu.com/Article/details/gtenuvlblj.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtnctcfwmz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtexqohuhb.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gtjshqcbpf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hfpthk.cn/Article/details/gtaipkwqne.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gtsvmjwifj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtazgaxteg.html

Ruby: def greet(name = "World") = name
来源：http://dali.hnxiangtu.top/Article/details/gtnqkrqqdr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtaawupxay.html

[C03] 可变参数
来源：http://dali.yangfankeji.com/Article/details/gtnnjpqybh.html

Py:   def total(*args): return sum(args)
来源：http://dali.xylfe.cn/Article/details/gtggbohoqz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.snrcjt.cn/Article/details/gtovqxzmfs.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtyjlrkiip.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fengsongda.top/Article/details/gtcjblvkpa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcrgtwcbd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtirwdrzce.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtzrotybdw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtwomhvxhj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gotoacloud.top/Article/details/gtxtuoouqe.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtmekokrau.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtdflrvhbl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtmlwqhpnm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.chenlongwang.top/Article/details/gtcmqchvwi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtdsghrbzp.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysclhhik.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxvgukdil.html

C#:   f(a: 1, b: 2)
来源：http://dali.shangyingyoupin.top/Article/details/gtmnpjtebi.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gttuperupw.html

Py:   return a, b
来源：http://dali.9152youxi.cn/Article/details/gtjvirgdsk.html

PHP:  return [$a, $b];
来源：http://dali.zycfv.cn/Article/details/gtswzbkdrf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gteuywtlpn.html

TS:   return { a, b };
来源：http://dali.gotoacloud.top/Article/details/gtdioyhgnm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzfvhisz.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gthvwlscuf.html

Ruby: return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtexfwbzpt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtdpmedvkw.html

[C06] 匿名函数 / lambda
来源：http://dali.iojbl.cn/Article/details/gtceepoyiy.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtndyelsua.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hywenlv.cn/Article/details/gtynpouczy.html

JS:   const square = x => x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoxifgrk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtuhdgshze.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtnpjkbmnp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gtjmplznwb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hywenlv.cn/Article/details/gtwhbunnng.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtkbzwlcjb.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gtpevuwdvl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gtmwvoxybd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhongyouzk.top/Article/details/gtwcluypgk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj20258.top/Article/details/gtxnhtqcuj.html

TS:   arr.map(String)
来源：http://dali.jinghuilouyu.cn/Article/details/gtezfwjdrs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cashguo.top/Article/details/gtytsgwtiv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gtadteintw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jianghu66.top/Article/details/gtvcqhbrhs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hfpthk.cn/Article/details/gtqtomxgvs.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gttsuyezqs.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shzxlz.cn/Article/details/gtpvlhfbnz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yuxming.cn/Article/details/gtfaexanas.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtqgnspblh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.iojbl.cn/Article/details/gtbxpknxkq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xinyue.icu/Article/details/gthqsoyusg.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cheryme.top/Article/details/gtpimzyflc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.xylfe.cn/Article/details/gtfoiofkkx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gtyebyahjw.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gtpavxlsti.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aizwys.cn/Article/details/gtaqrgxqnp.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtukdnneyx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgfzy.top/Article/details/gtmxfyjuah.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtxgizomno.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtxeqyaxgz.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yanxiufei.cn/Article/details/gtmvzdrqvo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfujucqjh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtmgbgeqaz.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gtmncajfnt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jianghu66.top/Article/details/gtojzgqgkd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtkrmttojh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangdashe.top/Article/details/gtpdsbohts.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtdgsepvhr.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gtkfumqecd.html

Go:   花括号块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtedyjovwi.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtdisufwql.html

C#:   块级作用域
来源：http://dali.316326.xyz/Article/details/gtcviktwhv.html

[C11] 模块导入与导出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwozhhsc.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtjpctedke.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtgneglqxq.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xuanzx.com/Article/details/gtlwhalsvy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yangfankeji.com/Article/details/gtohnkdtnh.html

Java: import java.util.List;
来源：http://dali.dianchejie.cn/Article/details/gtprvwpvuz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gtdjrqlhpo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.0kj1m.cn/Article/details/gtvixhmqtr.html

C#:   using System.Text;
来源：http://dali.ybcxt.top/Article/details/gtofbzsnpr.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gtclbzkkeh.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtvxavarcg.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gtahxczhul.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gogol.net.cn/Article/details/gtbzdbwfub.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtyvudfvym.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.smart0.xyz/Article/details/gtakobsdte.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtbzbkbfna.html

Ruby: -> { puts "run" }.call
来源：http://dali.wangshuangyany.cn/Article/details/gtmazzqobh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gtyndkpjiq.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtdyxkfsgf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhengqikj.top/Article/details/gtjlvzdhbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ppjwa.cn/Article/details/gtgstgdelg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.guowangkeji.top/Article/details/gtwdvfjmrg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tanke756.top/Article/details/gtrmkaocqy.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtnziueczs.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gteumdhwyl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hongshengwenyu.top/Article/details/gtterllwkd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ehwqpu.com/Article/details/gtmzdgveey.html

[C14] 泛型函数
来源：http://dali.zhengqikj.top/Article/details/gtvlpgzesr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ppjwa.cn/Article/details/gtlynejusk.html

PHP:  // 无泛型
来源：http://dali.yueranfly.top/Article/details/gtbawrqrbs.html

JS:   // 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtyvelydgy.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyckjvjad.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jinqigufen.top/Article/details/gtuagdelmc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ybcxt.top/Article/details/gthvglxdwi.html

Ruby: # 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtliyontma.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinqigufen.top/Article/details/gtxxlhqydr.html

[C15] 解构 / 展开参数
来源：http://dali.daria6918.cn/Article/details/gtzwnnqzpj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xylfe.cn/Article/details/gtljkgyecj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gterukhaoh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtczyrdbrz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtiimlunaw.html

Java: // 无解构
来源：http://dali.mhx1999.top/Article/details/gtrbmjdzyb.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gtqynjefyb.html

Ruby: a, b = pair
来源：http://dali.wangshuangyany.cn/Article/details/gthlsexgov.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtujnvvtty.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtbmebezqu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yongpay.top/Article/details/gtyzkzkati.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtshutcwjw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinqigufen.top/Article/details/gteahsuebp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorwgwdnh.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.c1oappe.top/Article/details/gtfilqluxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxinkj.top/Article/details/gtvcvgtpno.html

Ruby: # 无重载：靠动态参数
来源：http://dali.0kj1m.cn/Article/details/gtjnfsusif.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.mhx1999.top/Article/details/gtathgfodm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtctieqdmt.html

D. 数组 / 列表 / 集合
来源：http://dali.wangshuangyany.cn/Article/details/gtxwjprpcr.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gttgvqjyvv.html

[D01] 创建数组 / 列表
来源：http://dali.zhoulong.xyz/Article/details/gtfmmafvnk.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.pycfn.com/Article/details/gtkgmwyhtu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtazruesub.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tian-w.cn/Article/details/gthkzwkyke.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgfzy.top/Article/details/gtqlvzkrnv.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hongshengwenyu.top/Article/details/gtedeywxhh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.aizwys.cn/Article/details/gtdzzhging.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinqigfzy.top/Article/details/gtrxayfcja.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gtvowwutcq.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtnzocwftd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.nanxinkj.top/Article/details/gtxmrymycy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtqqaldnxr.html

JS:   arr.push(4);
来源：http://dali.gaohongyu789.top/Article/details/gtfkkmwazk.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gthgqxoyjz.html


<!-- 参考信息 -->