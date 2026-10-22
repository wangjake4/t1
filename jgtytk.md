代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gt2orrzxeba.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258.top/Article/details/gt2dowfnuzm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xziqi.cn/Article/details/gt2uxcyhwvc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jiagoushi.top/Article/details/gt2dfrswwvy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2bnfekkan.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dashuyun.cn/Article/details/gt2afkoiiko.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gt2ohdlsrtn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jqgufenzy.top/Article/details/gt2kdgylweh.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gt2xhtfrxpi.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gt2qbkuqihc.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gt2cwusqjbs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.tianlin.xyz/Article/details/gt2obwjnans.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gt2izcrohnu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zkgjpkxg.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gt2axqewtvp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gt2nijhgaao.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.redwolf501.top/Article/details/gt2gtjmkidd.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gt2mzwigjam.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhijiandao.cn/Article/details/gt2zljzlluc.html

[B04] for 计数循环
来源：http://dali.redwolf501.top/Article/details/gt2qrfnmrio.html

Py:   for i in range(10): print(i)
来源：http://dali.jianghu66.top/Article/details/gt2koliwxwh.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shuidangran.top/Article/details/gt2olhtcryv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2sjqakatq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2acktvcee.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltcwcgoh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sufxvd.cn/Article/details/gt2aicvdtje.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tian-w.cn/Article/details/gt2ghujgaom.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tqzzerdg.html

[B05] 遍历数组 / 列表
来源：http://dali.svipenyu.cn/Article/details/gt2vmnwozhs.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jotdyvgx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2arblfega.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nanxinkj.top/Article/details/gt2trijille.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gt2bexirhhd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2syvwndiq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gt2wnootbfl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yongpay.top/Article/details/gt2bgwlwfyi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.9152youxi.cn/Article/details/gt2gxfmturk.html

[B06] 遍历字典 / 对象
来源：http://dali.ppjwa.cn/Article/details/gt2lailxjuz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gt2knpdexsc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gt2fcffyrjh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2tweckrsc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gt2esjazpfx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gt2deuzqxql.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tian-w.cn/Article/details/gt2tebbtacs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gt2ezetlnry.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yanxiufei.cn/Article/details/gt2kbrqfhbp.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gt2uzpikhqh.html

Py:   while i < 10: i += 1
来源：http://dali.zhiwuduotai.top/Article/details/gt2lwaqvkyp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gt2fgndmulp.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2skcmjgwi.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2jqifxxuj.html

Java: while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2hwwadlmp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.feifeiyinyue.top/Article/details/gt2spagripm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.aizwys.cn/Article/details/gt2qounrnes.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wsbewclx.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gt2syjeobbh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gt2xkcnddah.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.shzxlz.cn/Article/details/gt2smrflsad.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2lqtrnklc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gt2lmiufech.html

Java: do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2rcoaiyrg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gt2tmkqnhww.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gt2tiieilno.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shuidangran.top/Article/details/gt2kolktwuj.html

[B09] break 与 continue
来源：http://dali.jqgufenzy.top/Article/details/gt2vtoxtsxm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.aizwys.cn/Article/details/gt2gxawbkil.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gt2dlzignme.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2gvebveuj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gopvrcui.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gt2pwsqlene.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gt2mdedynrc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gt2vuwydfro.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2dsshgwyc.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gt2uuctvblw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dianchejie.cn/Article/details/gt2kuniclfp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2bzpizwhw.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gt2vfvkqlvj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gt2penkkznn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vvhxectd.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gt2svoxkqpz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yifqtvus.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sysykeji.top/Article/details/gt2cvdpwtqi.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gt2iszksbtl.html

Py:   list(range(0, 10, 2))
来源：http://dali.9152youxi.cn/Article/details/gt2liwpsjla.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gt2vueolxlq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gt2fqottvez.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zbsegngt.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2aftgjkcg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ppjwa.cn/Article/details/gt2xffkfdcj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2wcblczol.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yuanzhike.top/Article/details/gt2bxuiwnjl.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gt2dojfqdov.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gt2dacxjavf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.fengsongda.top/Article/details/gt2qlsqqjuf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2czsrvuzf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gt2axrvxwpl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2zxjrczuq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gt2ulszdign.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gt2awupiots.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.daxiang520.top/Article/details/gt2zghvkikd.html

[B13] 判断是否为数字
来源：http://dali.chenzaomai.com/Article/details/gt2gxsgmouo.html

Py:   isinstance(x, (int, float))
来源：http://dali.smart0.xyz/Article/details/gt2cggchofk.html

PHP:  is_numeric($x)
来源：http://dali.hywenlv.cn/Article/details/gt2wwjegvzf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cqqwz.cn/Article/details/gt2rutiqnxn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gt2ttdjoiom.html

Java: x instanceof Number
来源：http://dali.guannengcc.top/Article/details/gt2wmgnurzg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gt2yclojhqc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gt2vaanuogc.html

C#:   x is int or double or decimal
来源：http://dali.gzhubu.top/Article/details/gt2sitkjiuy.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gt2onxncgty.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2clpysome.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dianchejie.cn/Article/details/gt2ikgqdnuj.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2jgcqraac.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2byjxuqsj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xylfe.cn/Article/details/gt2euirlhov.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gt2jjtrtiza.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2qzxiftvg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gt2mowxlvgv.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gt2bevvagmx.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gt2lpsojysm.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gt2onsqawdb.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2tqzyganl.html

TS:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2imchzeir.html

Java: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gt2nongvmtk.html

Go:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2saiwxevq.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2bxkjrsuy.html

C#:   a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2okrvyvje.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gt2wstmpdvk.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gt2fvtyulho.html

PHP:  if (!$data) { return; }
来源：http://dali.birdmap.top/Article/details/gt2clhefwlw.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2couusyky.html

TS:   if (!data) return;
来源：http://dali.gaohongyu789.top/Article/details/gt2iibahgmz.html

Java: if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gt2sneivmhq.html

Go:   if data == nil { return }
来源：http://dali.ivvv.top/Article/details/gt2frnjedxq.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2afqrtwcb.html

C#:   if (data == null) return;
来源：http://dali.9152youxi.cn/Article/details/gt2pbcdziza.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2kinlqtdh.html

C. 函数与作用域
来源：http://dali.daxiang520.top/Article/details/gt2mzkzkjjv.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ckbbcbuh.html

[C01] 定义函数
来源：http://dali.cheryme.top/Article/details/gt2uxblljdb.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gt2hovtxvdw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gt2xgpusyqs.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gt2sfnpqzoc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sweek.top/Article/details/gt2qmtiltmx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gt2neylolxs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhongyouzk.top/Article/details/gt2fhkrgjkz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gt2zwiunhbq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gt2qjygnfqe.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2jipfqhqr.html

Py:   def greet(name="World"): return name
来源：http://dali.hywenlv.cn/Article/details/gt2fakulyot.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenzaomai.com/Article/details/gt2bcmiaoeg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gt2rysbjznx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2givmorbp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.iojbl.cn/Article/details/gt2rvffqxtn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gt2lzztofmy.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gt2gesbaosl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cheryme.top/Article/details/gt2njwgpjsn.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gt2xwsnepiq.html

Py:   def total(*args): return sum(args)
来源：http://dali.guowangkeji.top/Article/details/gt2oiqlkawb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yueranfly.top/Article/details/gt2jxjkloru.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gt2ajdwdyfj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dashuyun.cn/Article/details/gt2ugsbhyhg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nanxinkj.top/Article/details/gt2zcbwexqu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hkkxwyqc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gt2exjjdhmu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gt2yyejqlrc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gt2pxmhyrfg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.0kj1m.cn/Article/details/gt2vtvyswtb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daxiang520.top/Article/details/gt2umdgjijd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gt2xfotjwbd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gt2inzbjfwn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gt2fekxivdq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gt2xrzzbmsy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2fhtvlelh.html

C#:   f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gt2swyiepir.html

[C05] 返回多个值
来源：http://dali.xziqi.cn/Article/details/gt2qlswohxk.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gt2olcnrrpw.html

PHP:  return [$a, $b];
来源：http://dali.tianlin.xyz/Article/details/gt2ylzatshq.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gt2lbmhkedh.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gt2wixtynsf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yueranfly.top/Article/details/gt2mvsrgioh.html

Go:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2inchunzw.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gt2hdcykygg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.meibo888.top/Article/details/gt2qrhsmhgi.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2rydmxsnd.html

Py:   square = lambda x: x * x
来源：http://dali.tianlin.xyz/Article/details/gt2xjxwqbti.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gt2ivgoekga.html

JS:   const square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2ctbcquar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangdashe.top/Article/details/gt2gouohdsk.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gt2ohfpeptg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2jfafkypr.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdgqnonh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gt2smuqvmpk.html

[C07] 把函数作为参数传入
来源：http://dali.9152youxi.cn/Article/details/gt2swwxnwzc.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gt2ftoxqghz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gt2tzqdkdbm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gt2bgqeptyd.html

TS:   arr.map(String)
来源：http://dali.ydzc1.top/Article/details/gt2bqiqpvvp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gt2cknlkmvc.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gt2miiedpeg.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gt2wqygmhja.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cdnleiting.top/Article/details/gt2nyrwtpor.html

[C08] 闭包
来源：http://dali.fzhhl.top/Article/details/gt2xyvgvwhj.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.cqqwz.cn/Article/details/gt2ryikmzck.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.cucudq.cn/Article/details/gt2kwaaftfq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2azephvop.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gt2jmbdiiqp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.redwolf501.top/Article/details/gt2hjidczun.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2njfrvtkf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gt2swcsyhom.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xinyue.icu/Article/details/gt2uhajqsai.html

[C09] 递归
来源：http://dali.zdqjudy.top/Article/details/gt2pxkbdssd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhixingplan.top/Article/details/gt2ktgglpgz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gt2pcpnjsgq.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2tvtgfluo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2yhmaswri.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2xvpeoeta.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gt2cyukesyu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gt2ezzhfudj.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gt2vqfefimh.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gt2spxojidc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jqgfzy.top/Article/details/gt2opykzmcs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gt2mqxsdifx.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gt2fcubhmef.html

TS:   同 JS
来源：http://dali.kuanghao11.cn/Article/details/gt2htapwdht.html

Java: 方法内为块级作用域
来源：http://dali.vqdsnc.cn/Article/details/gt2dlepiwbc.html

Go:   花括号块级作用域
来源：http://dali.zycfv.cn/Article/details/gt2keyezeqh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gt2nbkkvycq.html

C#:   块级作用域
来源：http://dali.jinqigfzy.top/Article/details/gt2daasapnj.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gt2isnrgzrq.html

Py:   from module import func
来源：http://dali.hywenlv.cn/Article/details/gt2qexiwnpg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gt2spahxigi.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gaohongyu789.top/Article/details/gt2cerwtyqa.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uptlptsk.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gt2bqrxmcny.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.0kj1m.cn/Article/details/gt2lhjayyxa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.feifeiyinyue.top/Article/details/gt2bgczdtlu.html

C#:   using System.Text;
来源：http://dali.yueranfly.top/Article/details/gt2bontcguw.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenlongwang.top/Article/details/gt2xtgrdclw.html

Py:   (lambda: print("run"))()
来源：http://dali.zhixingplan.top/Article/details/gt2eqjophkx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.pengpengdd.cyou/Article/details/gt2htawciyq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhengqikj.top/Article/details/gt2jkqbhomf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.c1oappe.top/Article/details/gt2cuyxdycr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.andypj.xyz/Article/details/gt2sgyaggzs.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shzxlz.cn/Article/details/gt2qpapjpcw.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gt2fugeuppd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2wejuoutw.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhoulong.xyz/Article/details/gt2tykclxnv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2qynadvii.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2iczrinyw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.nanxinkj.top/Article/details/gt2yetlaaki.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gt2lkiltwzt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jkygfvjb.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gt2pirmfcfy.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhiwuduotai.top/Article/details/gt2waufohtd.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gzhubu.top/Article/details/gt2cjniyogh.html

[C14] 泛型函数
来源：http://dali.jianghu66.top/Article/details/gt2ijowqwnv.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wcrazcgz.html

PHP:  // 无泛型
来源：http://dali.yanxiufei.cn/Article/details/gt2yylvyzhy.html

JS:   // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gt2ovosfvrl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.andypj.xyz/Article/details/gt2alvtonfo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jqgufenzy.top/Article/details/gt2iewqatuk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hongshengwenyu.top/Article/details/gt2upxhwpng.html

Ruby: # 无泛型
来源：http://dali.yongpay.top/Article/details/gt2jjgpabno.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.fengsongda.top/Article/details/gt2tnbrjkbz.html

[C15] 解构 / 展开参数
来源：http://dali.smart0.xyz/Article/details/gt2vuwwjefn.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.redwolf501.top/Article/details/gt2edcijoxo.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jqgufenzy.top/Article/details/gt2xpmcixhq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ppjwa.cn/Article/details/gt2cvdtoyhd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.birdmap.top/Article/details/gt2ehppzvwf.html

Java: // 无解构
来源：http://dali.hammf.cn/Article/details/gt2hyzmefoo.html

Go:   // 无解构
来源：http://dali.quarkkingdee.top/Article/details/gt2wnkxzrtt.html

Ruby: a, b = pair
来源：http://dali.redwolf501.top/Article/details/gt2ngqbgcdx.html

C#:   var (a, b) = pair;
来源：http://dali.tianlin.xyz/Article/details/gt2aaxuxuly.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2rmoddsdo.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.nwbrower.top/Article/details/gt2grebfzds.html

PHP:  // 无重载
来源：http://dali.jyoumei.cn/Article/details/gt2mxethjyz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xinyue.icu/Article/details/gt2lnlftmdj.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.sufxvd.cn/Article/details/gt2vcjjsaci.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.gzhubu.top/Article/details/gt2mmgnvlvl.html

Go:   // 无重载：用不同函数名
来源：http://dali.hammf.cn/Article/details/gt2hpbdxyul.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gt2nwxaprew.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.andypj.xyz/Article/details/gt2wbfahykv.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnzvbhcz.html

D. 数组 / 列表 / 集合
来源：http://dali.smart0.xyz/Article/details/gt2rsczrdnv.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gt2fewbbcrr.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gt2xophkdem.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cdnleiting.top/Article/details/gt2uzjurdtr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.aibaodan.cn/Article/details/gt2payzxctg.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dashuyun.cn/Article/details/gt2oknojegt.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gt2fxqbolul.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jqgufenzy.top/Article/details/gt2lqlvtubt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.smart0.xyz/Article/details/gt2srioruxv.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gt2sfnqedmq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigufen.top/Article/details/gt2drntdxyn.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gt2occmuhfa.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.quarkkingdee.top/Article/details/gt2vcklaypx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhoulong.xyz/Article/details/gt2pirwsmvf.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gt2gmusqdos.html

TS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gt2kbihfdwt.html


<!-- 参考信息 -->