代发 wailian999

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.birdmap.top/Article/details/gtuxnzhprd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gthbwkhlvb.html

[B03] switch / match / case
来源：http://dali.xziqi.cn/Article/details/gtbpqophyq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dashuyun.cn/Article/details/gtgxbmtrlb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtqajgguls.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtdcstlbvm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtgyusewpc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ybcxt.top/Article/details/gtelprulre.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gtfgoohobc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.pycfn.com/Article/details/gtijhlfnqx.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.aibaodan.cn/Article/details/gtpwpnjgbf.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtaxkleupi.html

Py:   for i in range(10): print(i)
来源：http://dali.gzhubu.top/Article/details/gtudrypqai.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gtxqaeloxk.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtumbrdpvz.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtxhsogxrd.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hammf.cn/Article/details/gtimehunok.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.kuanghao11.cn/Article/details/gtxlskiqox.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cqqwz.cn/Article/details/gtvhgksgbo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xuanzx.com/Article/details/gtghgsmfkj.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtwokeruxy.html

Py:   for item in arr: print(item)
来源：http://dali.chenlongwang.top/Article/details/gtjrokjngm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpxbqwvzl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsvcexza.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gttkfmyoxv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hongshengwenyu.top/Article/details/gtiimtimuw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.havefunace.top/Article/details/gttztrukan.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gtyhmjdgks.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ppjwa.cn/Article/details/gtojibzuaa.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgfzy.top/Article/details/gtrruujuxz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.vqdsnc.cn/Article/details/gtqkxzpnyj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtbrukvrce.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtutgkzwmt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtapvjppvf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapzfmnop.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhiwuduotai.top/Article/details/gtjkdmjaic.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gthqoqguiu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.bjfxy.top/Article/details/gtjhezotzd.html

[B07] while 循环
来源：http://dali.jianghu66.top/Article/details/gtfqlbtoea.html

Py:   while i < 10: i += 1
来源：http://dali.zhengqikj.top/Article/details/gtckwohjkq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj202588.top/Article/details/gtuvbcjnai.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtpuvxzkoo.html

TS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtgvxdustz.html

Java: while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gteopsjcxj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gtrdpigfwf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtkwlncvlg.html

C#:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtigkmzpha.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtjbabylci.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtjltrlxkh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtmycbslay.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtkpgedetb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gttfhxpgzn.html

Java: do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtbktvhwfk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.haohaochexian.top/Article/details/gtvtfuiktq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtgsocuyzp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtsmilgwnw.html

[B09] break 与 continue
来源：http://dali.cucudq.cn/Article/details/gtxrvcdxts.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhiwuduotai.top/Article/details/gtvwxudsiw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtrkqgifjs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkypuiloe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtiwkhoyqi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtqkedsrfv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gtjrcjujfv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jyoumei.cn/Article/details/gtigukeokj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtkfbsdntt.html

[B10] 遍历同时拿索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjbyelczo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cucudq.cn/Article/details/gtihmdipge.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gtfoakdmpd.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtooeouotl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dashuyun.cn/Article/details/gtlphretxm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtmhdeumdu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hnqzz.top/Article/details/gtuvlxgteb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.sweek.top/Article/details/gtwumvtovc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtruwfufaq.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnxiangtu.top/Article/details/gthhuicywv.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtyykescmr.html

PHP:  range(0, 10, 2);
来源：http://dali.c1oappe.top/Article/details/gtiommhwcy.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtdbxtgofr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtshvkdrpw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xylfe.cn/Article/details/gtacoacgms.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtljpkrsca.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigufen.top/Article/details/gtztksbgwj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xuanzx.com/Article/details/gtbfzvdsvo.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gthoajkbvh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gtnonjfarr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gthjiiqdgy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwhkuocq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtaeomoutu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtdplynsvc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gtivtarcjb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtneodoyfc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gtpuiermnf.html

[B13] 判断是否为数字
来源：http://dali.ybcxt.top/Article/details/gtrzxiytzy.html

Py:   isinstance(x, (int, float))
来源：http://dali.316326.xyz/Article/details/gtgouvplcy.html

PHP:  is_numeric($x)
来源：http://dali.jianghu66.top/Article/details/gtqracdiuh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtsndkaehp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtbzcrxvrb.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gtjxbanrui.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtwrvzvghu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtsykqvqbn.html

C#:   x is int or double or decimal
来源：http://dali.bjfxy.top/Article/details/gtizhqkazr.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtyiuyilrf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gtrdmcwkiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.c1oappe.top/Article/details/gtpjjcloub.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtzdvdwnbi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.bjfxy.top/Article/details/gtexxsskus.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtjsjcdxdz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtkodngjea.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtoiutymwy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nwbrower.top/Article/details/gtnfsklixc.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtrnczlfns.html

Py:   a and b or not c
来源：http://dali.sweek.top/Article/details/gtwfuaaabe.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtjwylougb.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtyrecbqfb.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwukpztrp.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtxrzdcxfe.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtqaozpkqa.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxpyyfoew.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtdfdncmni.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtahdivzql.html

Py:   if not data: return
来源：http://dali.haohaochexian.top/Article/details/gtfmyhbpsn.html

PHP:  if (!$data) { return; }
来源：http://dali.bjfxy.top/Article/details/gtvfkvtqks.html

JS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gtkuaazuzx.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtoiciirro.html

Java: if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtjxzqxjeo.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gtayktzatr.html

Ruby: return if data.nil?
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqoxzskv.html

C#:   if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtgzstunyx.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtklvgkkfu.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gtzkzotwnd.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtlbstffnh.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtyixrpagg.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtjpfeozmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtycewthky.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtcgffwrwn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtryttcqfx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtmnqwrabh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jlsjyb.cn/Article/details/gtjofryuho.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtfdbhbcuh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtngakmxox.html

[C02] 默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gtdnjbilhe.html

Py:   def greet(name="World"): return name
来源：http://dali.birdmap.top/Article/details/gtnaypjihy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gtsmbmcyvl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtlvjbuscd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtugadnetc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtzifovktf.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtqnmljctt.html

Ruby: def greet(name = "World") = name
来源：http://dali.0kj1m.cn/Article/details/gtxgqvxezf.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtvdpknxye.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtclxhusgu.html

Py:   def total(*args): return sum(args)
来源：http://dali.jqgfzy.top/Article/details/gtbdtqtulo.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtclmbaxeb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.birdmap.top/Article/details/gtrdvponei.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.c1oappe.top/Article/details/gttjnmtgjv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gtuqzcaxyn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtriqfjyra.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtzjehkwry.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtwgcmojvr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cqqwz.cn/Article/details/gtsbfasgwl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xylfe.cn/Article/details/gtcrxmeikl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gotoacloud.top/Article/details/gtnhuwuygp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcmrclbyb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwizqmahk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtdshijbcw.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtuvtjgvxg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuxming.cn/Article/details/gtyavcplhc.html

C#:   f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gthdoyqedi.html

[C05] 返回多个值
来源：http://dali.zhoulong.xyz/Article/details/gtsypqxduw.html

Py:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gtbnzbgfry.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtqcieupyu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtfzhxvnxm.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtpgnrjydj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhiwuduotai.top/Article/details/gtnzumdyie.html

Go:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gtfinalahq.html

Ruby: return a, b
来源：http://dali.yonumen.top/Article/details/gtxwtssdzz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.vqdsnc.cn/Article/details/gtyxlqdvli.html

[C06] 匿名函数 / lambda
来源：http://dali.gzhubu.top/Article/details/gtmlxenihc.html

Py:   square = lambda x: x * x
来源：http://dali.aibaodan.cn/Article/details/gtwofolkrn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gtecwwmial.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtujqvoceh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.fzhhl.top/Article/details/gtgrpwjavm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fzhhl.top/Article/details/gtooneowqo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtddcqijtl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yvedp.cn/Article/details/gtgunmwyjz.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtlebokhnc.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gtdiiefokz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hnqzz.top/Article/details/gtpzgsfrtd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gthgyubsuq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gtkqsxxkht.html

TS:   arr.map(String)
来源：http://dali.0kj1m.cn/Article/details/gtrrywiqmd.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.dashuyun.cn/Article/details/gtlmdjoaxf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.aibaodan.cn/Article/details/gtnvazhxca.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gtlowgtrlf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtaupyvhpk.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtiozdvuiq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtndmrnuuf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.daxiang520.top/Article/details/gtrugxahrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gtybqyulqr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gtohywhner.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtpgoaahro.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sufxvd.cn/Article/details/gtoajkblte.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.andypj.xyz/Article/details/gtzxjzicky.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtvxcundro.html

[C09] 递归
来源：http://dali.jianghu66.top/Article/details/gtvkggwpem.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtxginndrl.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.havefunace.top/Article/details/gtuddkzemi.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.fzhhl.top/Article/details/gtuprksfij.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtgoxuueug.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cucudq.cn/Article/details/gtnmyxetzj.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtcvxchakp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gtyqgomdyo.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gzhubu.top/Article/details/gtqunxjgwr.html

[C10] 变量作用域
来源：http://dali.gogol.net.cn/Article/details/gtahjzrdsl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.tian-w.cn/Article/details/gtvyaqxlbu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.aizwys.cn/Article/details/gtcukzxoon.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.birdmap.top/Article/details/gtjyitulwh.html

TS:   同 JS
来源：http://dali.ehwqpu.com/Article/details/gtwsbemaoj.html

Java: 方法内为块级作用域
来源：http://dali.tian-w.cn/Article/details/gtoqswicsi.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtzmzjrucw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gogol.net.cn/Article/details/gtspqvmcue.html

C#:   块级作用域
来源：http://dali.xziqi.cn/Article/details/gthdqupjiw.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtiruwjnwr.html

Py:   from module import func
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwacndvmn.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtsvdkecfb.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.gotoacloud.top/Article/details/gtzzhewlcf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.316326.xyz/Article/details/gtngeloghu.html

Java: import java.util.List;
来源：http://dali.zhongyouzk.top/Article/details/gturrfbqum.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jqgfzy.top/Article/details/gtsakkqiqs.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtadwpzxmb.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtcwvbjxfi.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtzkifjnsx.html

Py:   (lambda: print("run"))()
来源：http://dali.yj202588.top/Article/details/gtdysahufl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtxilzsdep.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ybcxt.top/Article/details/gtueckdqjr.html

TS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gtykufivcx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yanxiufei.cn/Article/details/gtfobsmtby.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gtosatlgia.html

Ruby: -> { puts "run" }.call
来源：http://dali.guowangkeji.top/Article/details/gtntezivgo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gttyohhgfy.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayogvbdp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xuanzx.com/Article/details/gtkshhggee.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtlvgvkdlk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sxryk.cn/Article/details/gtyezeavld.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gteoguyuof.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gthvwllyll.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtbitaawql.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sufxvd.cn/Article/details/gtwfiurfvi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtaewnhewj.html

[C14] 泛型函数
来源：http://dali.jiagoushi.top/Article/details/gtczaasorp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtwvxlxhsj.html

PHP:  // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtidnmambr.html

JS:   // 无泛型
来源：http://dali.nanxinkj.top/Article/details/gtmkyfogoj.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zycfv.cn/Article/details/gtkhvhgsxl.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sweek.top/Article/details/gthzhctomp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtkwoxxsen.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtleqoscir.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.gogol.net.cn/Article/details/gtbgmfpyjh.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gtuxfrkawo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gtjshhxdob.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtorszlqcw.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtfrjpkkcu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cashguo.top/Article/details/gtzbtvwqiw.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gtwiudotkh.html

Go:   // 无解构
来源：http://dali.gaohongyu789.top/Article/details/gtzmtutwbt.html

Ruby: a, b = pair
来源：http://dali.yuxming.cn/Article/details/gtzzrvhaal.html

C#:   var (a, b) = pair;
来源：http://dali.dianchejie.cn/Article/details/gtcvrpbnrl.html

[C16] 函数 / 方法重载
来源：http://dali.aibaodan.cn/Article/details/gtkjdkpgml.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cashguo.top/Article/details/gtsdlpdcvv.html

PHP:  // 无重载
来源：http://dali.birdmap.top/Article/details/gtjjnswsda.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yuxming.cn/Article/details/gtyfdzreue.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hongshengwenyu.top/Article/details/gtvvgesjkv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.aibaodan.cn/Article/details/gtnrmwkyyb.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuanzhike.top/Article/details/gtflqfxrqu.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hammf.cn/Article/details/gtuitphwrc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.smart0.xyz/Article/details/gtbnbtomdw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gthiicgdcw.html

D. 数组 / 列表 / 集合
来源：http://dali.bjfxy.top/Article/details/gttamfvuqv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwuxrpajv.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtrvbajlzj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhixingplan.top/Article/details/gtpfgxqscu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtgincgwmy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gttzullqll.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yangfankeji.com/Article/details/gtjasxrgyd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yangfankeji.com/Article/details/gtijvwkwyj.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhiwuduotai.top/Article/details/gtzlrnmrzs.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gtshpkqytx.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtrreffdxd.html

[D02] 追加元素到末尾
来源：http://dali.quarkkingdee.top/Article/details/gtvrylpjif.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gtwognkkdh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.dashuyun.cn/Article/details/gtgmppdlqy.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gttyrzftgt.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtrddhqcuy.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gthscvzizo.html

Go:   arr = append(arr, 4)
来源：http://dali.jlsjyb.cn/Article/details/gtitudfmmq.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gthytplvxx.html

C#:   list.Add(4);
来源：http://dali.gaohongyu789.top/Article/details/gtzrblklgz.html

[D03] 在指定位置插入元素
来源：http://dali.xziqi.cn/Article/details/gtfirccsrz.html

Py:   arr.insert(0, 0)
来源：http://dali.fzhhl.top/Article/details/gtntviiwdi.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.guannengcc.top/Article/details/gtqaqpswpz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtmmzqumpa.html


<!-- 参考信息 -->