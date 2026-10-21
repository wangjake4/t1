代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtlttfdavy.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gtthalzgcc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhoulong.xyz/Article/details/gtswdicoke.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hysaishi.cn/Article/details/gtecplbqxx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gtakvwqoow.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtldhldylm.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtngvyiuii.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gtatchymhi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jlsjyb.cn/Article/details/gtrkshyhht.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtuldbhsio.html

[B03] switch / match / case
来源：http://dali.redwolf501.top/Article/details/gtdefdlkyj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sysykeji.top/Article/details/gtdhafrxes.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtbukuldpi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gzhubu.top/Article/details/gtcerpypio.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtptxdjbyk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtxysrhpmt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258888.top/Article/details/gtrdomsfzm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.zhengqikj.top/Article/details/gtrsymnktp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yongpay.top/Article/details/gtlooznnga.html

[B04] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gthhmzgwbj.html

Py:   for i in range(10): print(i)
来源：http://dali.gotoacloud.top/Article/details/gttmpacnam.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenlongwang.top/Article/details/gtlvdjdocb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gtlmvurvvr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.smart0.xyz/Article/details/gtpetjsmri.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sxryk.cn/Article/details/gtjwnkwvqc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hfpthk.cn/Article/details/gtcfjwhlyg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtlftikeqy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fengsongda.top/Article/details/gttlqxrahl.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtfquddivz.html

Py:   for item in arr: print(item)
来源：http://dali.guowangkeji.top/Article/details/gtalzdlhyx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jlsjyb.cn/Article/details/gtjrxdcbdx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtetauaomp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtmhoyvjsu.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtzlrsrrza.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtvkxtwlaj.html

Ruby: arr.each { |item| puts item }
来源：http://dali.birdmap.top/Article/details/gtxxwrkmgt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ydzc1.top/Article/details/gtoydccxxz.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtgavoygxt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtskyisfyz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtizvpmxwz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtevrczkrw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtihatclwo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gtqonjgtsq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cashguo.top/Article/details/gtnljtxdcj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtskiwrsxe.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gogol.net.cn/Article/details/gtokjoycbw.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtvvbihqke.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gtvqebeaby.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gteqpkjoeb.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtmzrubzie.html

TS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtejdivakt.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtlwdxtciw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tian-w.cn/Article/details/gtxrenjsdu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtlskzqsxv.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtiopjztyi.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpbrswmi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtixcjvjna.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtnloqkaxn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtawbvhndl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtqmpmwrzp.html

Java: do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtjzqxdclz.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtezovxkeg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gtcswfdnaq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtkwbcrpaa.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gtesnjfjbs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtrjpwysrh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtnnhqxfgg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtxbximaow.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtfacywelt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtbeauhgdm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtlhpsmcsx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sweek.top/Article/details/gtnrtpabau.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrhdupdd.html

[B10] 遍历同时拿索引
来源：http://dali.gzhubu.top/Article/details/gtaybouysb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gtxgvajovc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgufenzy.top/Article/details/gtvpxulylk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtmgpasbhb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jqgufenzy.top/Article/details/gtelbfcuvf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.birdmap.top/Article/details/gtenqjxddk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtswsnkngo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdiabpsnl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtwhtyxsnb.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtxabmoiiy.html

Py:   list(range(0, 10, 2))
来源：http://dali.tian-w.cn/Article/details/gtffetpbpv.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtqaxlniln.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtkbprowgq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtpsalwggn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tianlin.xyz/Article/details/gtamgqwkim.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtcskoyvig.html

Ruby: (0...10).step(2).to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtqxbjjcpi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhixingplan.top/Article/details/gtzpnntkze.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtcrrpzkfe.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yonumen.top/Article/details/gtgrldvlch.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gtenusteba.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gttagbsfwd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtmenkdtat.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtzkmitiqa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtswpearnl.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuanzx.com/Article/details/gtnzoftgia.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtavcahmgq.html

[B13] 判断是否为数字
来源：http://dali.yueranfly.top/Article/details/gtcylkdpyv.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtscnweohb.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gtkumukfun.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gthypgossh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gtzfanxbgg.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtqizmtzgn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gtqnzvwldw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shangyingyoupin.top/Article/details/gtpclviofd.html

C#:   x is int or double or decimal
来源：http://dali.316326.xyz/Article/details/gtrdfgtnly.html

[B14] 判断值是否在集合内
来源：http://dali.xziqi.cn/Article/details/gtdqzrwojf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtvhkzjkfg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.wangshuangyany.cn/Article/details/gtvmfmagsv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtauikrryp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hammf.cn/Article/details/gtkxhiebij.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtyjkqmidg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtbbxdwvej.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtjytgyqll.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yonumen.top/Article/details/gtivigzhwe.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtzrgklqil.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtqwffsznl.html

PHP:  $a && $b || !$c
来源：http://dali.feifeiyinyue.top/Article/details/gtytncxmgs.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrrezjnn.html

TS:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtxitldhbk.html

Java: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtgcppbzgq.html

Go:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtxomgkdfg.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyuodmbu.html

C#:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtfwkljiwk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xinyue.icu/Article/details/gtozvjyqlu.html

Py:   if not data: return
来源：http://dali.pycfn.com/Article/details/gtivbkplkn.html

PHP:  if (!$data) { return; }
来源：http://dali.chenjidiqi.icu/Article/details/gtrojkkptv.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtxufoqvqz.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtjgcgnequ.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtvfhqhjel.html

Go:   if data == nil { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdnjzznzf.html

Ruby: return if data.nil?
来源：http://dali.yueranfly.top/Article/details/gtgbiixtbv.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gtjlefiwza.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gttfxjbydi.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtbjtyfjwv.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtnrtwtqbp.html

[C01] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtuwmjquve.html

Py:   def add(a, b): return a + b
来源：http://dali.aizwys.cn/Article/details/gtntpmhnwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtnaletqal.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtdrlnoscn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtukyajpby.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtjekiewez.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yj202588.top/Article/details/gtpmgzwxiv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxplxgady.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtsrqcutvo.html

[C02] 默认参数
来源：http://dali.yj20258.top/Article/details/gthfbmtbkv.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtanddxhir.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yanxiufei.cn/Article/details/gtfcnumjbs.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtuqplrwhg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gttxgcvehc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtufkrwyou.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jiagoushi.top/Article/details/gtooejawxd.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtrvgddzzi.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtffcxnmeq.html

[C03] 可变参数
来源：http://dali.daxiang520.top/Article/details/gtyjjwwylj.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhijiandao.cn/Article/details/gteenvxlrm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtamsmzotu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jlsjyb.cn/Article/details/gtmwqydrkq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.svipenyu.cn/Article/details/gtuyczjgeg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtqkagfrmu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.andypj.xyz/Article/details/gtpprbbfbh.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtyzsjmewg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtdcilnvjz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtdsdyzlyb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cqqwz.cn/Article/details/gtimebnzcy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cucudq.cn/Article/details/gtbcmxwbjs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gtcwiefvrn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtmbjxsehv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtxgjtdlad.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtjfzumwuq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtucoxcinl.html

C#:   f(a: 1, b: 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgubomfkl.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtxhjrsxhj.html

Py:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtnpkwsdzc.html

PHP:  return [$a, $b];
来源：http://dali.hammf.cn/Article/details/gtqhsnzzmj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovhmzzec.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtqtultmhf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmwiiyfd.html

Go:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtfmqfpcei.html

Ruby: return a, b
来源：http://dali.zdqjudy.top/Article/details/gtfyylebim.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jyoumei.cn/Article/details/gtghempvah.html

[C06] 匿名函数 / lambda
来源：http://dali.havefunace.top/Article/details/gthfzjacti.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtinymnvqe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.ppjwa.cn/Article/details/gtmgynmvhv.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gtcnmlvrva.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtrbkhpxuw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.snrcjt.cn/Article/details/gtiofvlrex.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gthrkedqpp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.0kj1m.cn/Article/details/gtgqexmgdv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.havefunace.top/Article/details/gteepjsuof.html

[C07] 把函数作为参数传入
来源：http://dali.ydzc1.top/Article/details/gtpbqjfzst.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangshuangyany.cn/Article/details/gtnvhudewi.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtraljaqei.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hongshengwenyu.top/Article/details/gtxvewynml.html

TS:   arr.map(String)
来源：http://dali.gogol.net.cn/Article/details/gtbovhkqlv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtabtbgmqt.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtjgaasjll.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgrdcptz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sysykeji.top/Article/details/gthiruycng.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gtvssdfmut.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.snrcjt.cn/Article/details/gtmlbualsn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gtqlbucleg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gtafagauxh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtxhjvsxzv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenlongwang.top/Article/details/gtcfijvbqq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtwnjijgrd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzvjpinzl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtidjwdmpi.html

[C09] 递归
来源：http://dali.nanxinkj.top/Article/details/gticsuubso.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtctyrcqgh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.tian-w.cn/Article/details/gttsrkcsaz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.feifeiyinyue.top/Article/details/gtigrzyglz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtvbquddxo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtyuahwdbo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gtosdeklzh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtwmnahmaw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.0kj1m.cn/Article/details/gtqjbombqb.html

[C10] 变量作用域
来源：http://dali.gzhubu.top/Article/details/gtfgaoomvu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtuckfhdng.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtdihsheca.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtehphjebr.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtmkzknzgt.html

Java: 方法内为块级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtarflsvrc.html

Go:   花括号块级作用域
来源：http://dali.gzhubu.top/Article/details/gtvfhrmhab.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtlreukqeh.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gtpqdypoth.html

[C11] 模块导入与导出
来源：http://dali.yuanzhike.top/Article/details/gtfsrbcrip.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtcstmqobr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.daria6918.cn/Article/details/gtabydkkub.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.cashguo.top/Article/details/gtgimkqsqf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtoitbfoqu.html

Java: import java.util.List;
来源：http://dali.pengpengdd.cyou/Article/details/gtaonljdbt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zdqjudy.top/Article/details/gtbyfwcskn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gtmabvdjxr.html

C#:   using System.Text;
来源：http://dali.yj20258888.top/Article/details/gtctzbmejj.html

[C12] 立即执行函数 IIFE
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkyiwlih.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gtrsnsjvwl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.tian-w.cn/Article/details/gthtlfqznh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtvemjdcla.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtrtfvwvpn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuetiantiany.cn/Article/details/gtsywsrmic.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pengpengdd.cyou/Article/details/gtgdbuivuc.html

Ruby: -> { puts "run" }.call
来源：http://dali.vqdsnc.cn/Article/details/gtcheptpmn.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sxryk.cn/Article/details/gtxguemulr.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gtqipgfvoe.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtksnewtot.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gthbytdjnc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zdqjudy.top/Article/details/gtvpiumhfd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gttouiqvvq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtgyokixio.html

Go:   func add(a, b int) int
来源：http://dali.jyoumei.cn/Article/details/gtfsjdxjpd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gtbvzzofbm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.haohaochexian.top/Article/details/gtwfzledoo.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gtatpmmqoo.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.svipenyu.cn/Article/details/gtwbsbnxzq.html

PHP:  // 无泛型
来源：http://dali.hongshengwenyu.top/Article/details/gttyvdqsyy.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gtbmuquyep.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gtdiuyldwd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gtetsnuhpv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.sweek.top/Article/details/gtyjwgyhzo.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtedsakgnl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.nwbrower.top/Article/details/gtktecwhkd.html

[C15] 解构 / 展开参数
来源：http://dali.gogol.net.cn/Article/details/gtdqwzovmf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gtfidzerlg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenzaomai.com/Article/details/gtcqnoganj.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.redwolf501.top/Article/details/gtemroznnn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtsmqxpxph.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gtbdjqqcpr.html

Go:   // 无解构
来源：http://dali.c1oappe.top/Article/details/gtnmeqbvrh.html

Ruby: a, b = pair
来源：http://dali.snrcjt.cn/Article/details/gtkijnyugj.html

C#:   var (a, b) = pair;
来源：http://dali.chenzaomai.com/Article/details/gtprpepisa.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gtldvnhjqz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.smart0.xyz/Article/details/gtzlsithaj.html

PHP:  // 无重载
来源：http://dali.jinqigufen.top/Article/details/gtcqtvsxgj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.ydzc1.top/Article/details/gtrvropoyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gtqmwnzuiu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aizwys.cn/Article/details/gtgtltxina.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gttshgfhft.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cheryme.top/Article/details/gticfejwmr.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yuanzhike.top/Article/details/gtmwtxpxpi.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwrsexex.html

D. 数组 / 列表 / 集合
来源：http://dali.yj20258888.top/Article/details/gtyxwgeibe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtscrxxzmb.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtcobssece.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtczeuitnn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gttjtymwxr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangshuangyany.cn/Article/details/gtdmcgsglk.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yongpay.top/Article/details/gtphlawrel.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jianghu66.top/Article/details/gtmewjnloz.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.vqdsnc.cn/Article/details/gtuwagbxii.html

Ruby: arr = [1, 2, 3]
来源：http://dali.snrcjt.cn/Article/details/gtrvwoggmr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.gaohongyu789.top/Article/details/gtqcunnydp.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtzwqprfor.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhixingplan.top/Article/details/gtjchqebjy.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtlsbrrzqo.html

JS:   arr.push(4);
来源：http://dali.xziqi.cn/Article/details/gtipwdufqs.html

TS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gtyzaawsnv.html


<!-- 参考信息 -->