代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.chenzaomai.com/Article/details/gtomjcdjfl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtuulwpgrp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.iojbl.cn/Article/details/gthxyfxjze.html

[B04] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrpvshdzy.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtqysksgqj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtrfuinnjt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtugggauhe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtftwpdknh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtxcisdgip.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.sysykeji.top/Article/details/gttthcptfy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtofmhxbtl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yangfankeji.com/Article/details/gtbhnqfmii.html

[B05] 遍历数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gtihbvelxq.html

Py:   for item in arr: print(item)
来源：http://dali.svipenyu.cn/Article/details/gtbccdpito.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.quarkkingdee.top/Article/details/gtzwgevrxe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtmuedokos.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtkhkpjjqt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtzduipwav.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtsqnssbbn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnredbnyb.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ybcxt.top/Article/details/gtrcafwsyo.html

[B06] 遍历字典 / 对象
来源：http://dali.dianchejie.cn/Article/details/gtblwqcuao.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jiagoushi.top/Article/details/gthvigduwp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gtkjadifoj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gtyrnqurqz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtxdjgfjwg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuhuhpxal.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gtugqvpzon.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.vqdsnc.cn/Article/details/gtlrcwpgwk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gtgvvktzfj.html

[B07] while 循环
来源：http://dali.jinqigfzy.top/Article/details/gtixlftotk.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gtzexukeyg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gtiuhwjdvw.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtpcskliai.html

TS:   while (i < 10) { i++; }
来源：http://dali.shuidangran.top/Article/details/gtivkjvpvb.html

Java: while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtewspqara.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenlongwang.top/Article/details/gtcxyhbcqq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gtdiuincso.html

C#:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gtxvehwcex.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gturigfyek.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sufxvd.cn/Article/details/gtmwpnpbfz.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yongpay.top/Article/details/gthsagkdpc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtmwphqvoy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtdffxkkrt.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtoqatgqjg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuanzhike.top/Article/details/gtkkplohrw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtnauoaajw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtgszdjvzr.html

[B09] break 与 continue
来源：http://dali.tian-w.cn/Article/details/gtobbcbdmy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.dashuyun.cn/Article/details/gtyuupklmz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtnisgvjrt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtdmjmlqqo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtgtlkwcbm.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjwosblb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yongpay.top/Article/details/gtwwlpgkhz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhijiandao.cn/Article/details/gtlvquiyii.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtjgrxmoxt.html

[B10] 遍历同时拿索引
来源：http://dali.yuanzhike.top/Article/details/gtuxnepdrr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gtrcvxidvn.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aizwys.cn/Article/details/gtrnpyxshl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fengsongda.top/Article/details/gthxzzxrsi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guannengcc.top/Article/details/gtpwdnlcpz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gaohongyu789.top/Article/details/gtdlbpvcfe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.haohaochexian.top/Article/details/gteaykkegy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tanke756.top/Article/details/gtgkuvwjzd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtosdnyvuf.html

[B11] 生成数字序列 / 区间
来源：http://dali.xinyue.icu/Article/details/gtdvlibhla.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtejptwnzm.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gtdmyuxzwz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtusijxfmt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtkywqefux.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.haohaochexian.top/Article/details/gtecrxyzhk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ppjwa.cn/Article/details/gttumyfrmc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtosjvobra.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtlwdguldq.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gthhmcpecn.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtxfiyctkg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gzhubu.top/Article/details/gtyhxhsfjq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gthaslhjdq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gthftzsuzh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtcmptazww.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yonumen.top/Article/details/gtnqqafivj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zycfv.cn/Article/details/gtjgecbotj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtoxftmpmi.html

[B13] 判断是否为数字
来源：http://dali.aibaodan.cn/Article/details/gtthxytjeg.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhaomingkeji.xyz/Article/details/gttifmujou.html

PHP:  is_numeric($x)
来源：http://dali.haohaochexian.top/Article/details/gttxrxqnhr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gtshlnzgbp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtzyvrphnw.html

Java: x instanceof Number
来源：http://dali.pengpengdd.cyou/Article/details/gtqdwncbgf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtsxkvdhhd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hnxiangtu.top/Article/details/gtixtkecyj.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtzwvdmcha.html

[B14] 判断值是否在集合内
来源：http://dali.xuetiantiany.cn/Article/details/gtxhjixhsu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.nanxinkj.top/Article/details/gtkqfyzruy.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gtjziipwko.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtlbmxocxu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtuzhvuoor.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtfsnrjvvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jyoumei.cn/Article/details/gtglwpwijs.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtxsaclbxl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yueranfly.top/Article/details/gtabrantfs.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtvtxrjjrm.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gtgpcwbvtn.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtvbsbsfsm.html

JS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtnlnctfhw.html

TS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtvspaiywi.html

Java: a && b || !c
来源：http://dali.yuxming.cn/Article/details/gtnhbvtuly.html

Go:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtodylgsbt.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtgmaxobft.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtqmdjzkmn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cheryme.top/Article/details/gtblhddflk.html

Py:   if not data: return
来源：http://dali.fengsongda.top/Article/details/gthztfkqfj.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtcklnohsu.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtfqevzban.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gtqlpzxebp.html

Java: if (data == null) return;
来源：http://dali.xuanzx.com/Article/details/gtiszmmauy.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtahhokyqn.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtgtzmwelo.html

C#:   if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtxuniewgp.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtrgcgmxsu.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtfuzfrkow.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtxjyjpiyy.html

[C01] 定义函数
来源：http://dali.nanxuanxn.top/Article/details/gthzxkxybs.html

Py:   def add(a, b): return a + b
来源：http://dali.jinqigufen.top/Article/details/gtsbjvjadv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtchxouyjd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtmtgvyxdw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtxtaloxdz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtqtrcpdgh.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gtovhdogxd.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtogmcaips.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtfwvxvqya.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtwpyavsjg.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuoulabg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gzhubu.top/Article/details/gtaqagmoag.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hnqzz.top/Article/details/gtxjtmssxi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtxwhpbqbe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.chenlongwang.top/Article/details/gtyyuhbqfx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukedfmog.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtbhzoject.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxuanxn.top/Article/details/gtcnxbhbcm.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtxhbedbmn.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenjidiqi.icu/Article/details/gtojjcfspp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zycfv.cn/Article/details/gtjfqxpbjg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuxming.cn/Article/details/gtctwyluft.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtutlpkgfa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.meibo888.top/Article/details/gtddaktkbp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.pengpengdd.cyou/Article/details/gtrotwbuys.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtmthlkyte.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yj20258.top/Article/details/gtmspjnrpq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtqfjnuttd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtwcufvpfy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtxladfcoc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xinyue.icu/Article/details/gticwiabfv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.snrcjt.cn/Article/details/gttkrjnzpx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtldaimcga.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gtfmtxxwkk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtynlegdjm.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhongyouzk.top/Article/details/gtuvjqycbl.html

[C05] 返回多个值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbbeildhs.html

Py:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtxolhmwxr.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtlpwoqztb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gtpmlmhqyy.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtwvpczbpm.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hammf.cn/Article/details/gtufpxueeo.html

Go:   return a, b
来源：http://dali.fengsongda.top/Article/details/gtvcmcezrb.html

Ruby: return a, b
来源：http://dali.smart0.xyz/Article/details/gtpdnmcgar.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hywenlv.cn/Article/details/gthizoqwrd.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtqrvlviww.html

Py:   square = lambda x: x * x
来源：http://dali.shzxlz.cn/Article/details/gtprlnqmvq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtayhkshzd.html

JS:   const square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtdviaejet.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.meibo888.top/Article/details/gtilkivkhu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.shanyushiyangtech.top/Article/details/gteblztibz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtapvktaga.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pengpengdd.cyou/Article/details/gtthbwyixh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtbuayxamn.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtowesrrby.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtmvujhymr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.sxryk.cn/Article/details/gtqufbfbuh.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtclslstkv.html

TS:   arr.map(String)
来源：http://dali.wangdashe.top/Article/details/gtfoamkonq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shuidangran.top/Article/details/gtbixbsjjo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtflulyfsb.html

Ruby: arr.map(&:upcase)
来源：http://dali.gotoacloud.top/Article/details/gthyxnksxf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yongpay.top/Article/details/gtekgdnteg.html

[C08] 闭包
来源：http://dali.jyoumei.cn/Article/details/gtbfobmouy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aibaodan.cn/Article/details/gtkjvxomcf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gtgdhoeeqg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtupnwbdqk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtcrgubaia.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtfvtkukwy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hfpthk.cn/Article/details/gtfzkmdqer.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.tanke756.top/Article/details/gtcmxmmijo.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtndkywewg.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtaegyekry.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tianlin.xyz/Article/details/gtlzkejkds.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ybcxt.top/Article/details/gtjyrqmuzb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gthejvuqfs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtnfxnrofj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.havefunace.top/Article/details/gthjpujdqr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hnxiangtu.top/Article/details/gtzdyhrdey.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gthpeisedu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gteepogmrn.html

[C10] 变量作用域
来源：http://dali.smart0.xyz/Article/details/gtjubedcqg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.cheryme.top/Article/details/gtxvrejbyn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenlongwang.top/Article/details/gtapcowxfy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.chenlongwang.top/Article/details/gthjxrfish.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtglkpazmy.html

Java: 方法内为块级作用域
来源：http://dali.gotoacloud.top/Article/details/gtgeoqxieb.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtwcghhhqe.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gtkkxtsjor.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gtmfvclflo.html

[C11] 模块导入与导出
来源：http://dali.gaohongyu789.top/Article/details/gtesppberm.html

Py:   from module import func
来源：http://dali.xuanzx.com/Article/details/gtctaucker.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtkgbdmgpt.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ehwqpu.com/Article/details/gtvamffjlv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinqigufen.top/Article/details/gtuffmjtzi.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtljiehqqr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.fzhhl.top/Article/details/gtwrudbsdp.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.svipenyu.cn/Article/details/gtkbbpgmzb.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtdrzbeegn.html

[C12] 立即执行函数 IIFE
来源：http://dali.bjfxy.top/Article/details/gtlmixcvby.html

Py:   (lambda: print("run"))()
来源：http://dali.yvedp.cn/Article/details/gthaodhgca.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtwfugzefp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.daxiang520.top/Article/details/gtittgmtwn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cheryme.top/Article/details/gtotbggjxh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gttassphvg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.cheryme.top/Article/details/gtcrxwjbcv.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodpfxezx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gtpiyroqin.html

[C13] 类型声明 / 类型注解
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyydvlld.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yuanzhike.top/Article/details/gtlkwrvsfx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.sxryk.cn/Article/details/gthnazvfoj.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yueranfly.top/Article/details/gtsdtcbmqf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtqzwfejqk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.guowangkeji.top/Article/details/gtoabfwapp.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gttzgmywlm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhijiandao.cn/Article/details/gtlhyvywfk.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtcroeymhy.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtioicujfp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtmhwurfmc.html

PHP:  // 无泛型
来源：http://dali.shuidangran.top/Article/details/gtnafsrfor.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gtwkhtznpi.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jlsjyb.cn/Article/details/gtkvqmfrkh.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cdnleiting.top/Article/details/gtvialdgrr.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yangfankeji.com/Article/details/gtwlmarkdy.html

Ruby: # 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gtwpyvphwu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.dianchejie.cn/Article/details/gtifgznhoe.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtzcerrmqx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yueranfly.top/Article/details/gtgdkdilrp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gtsrprsymy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtxzjghogy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtaeswwmuk.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtpvxdcajh.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtfzcivhjy.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtbbpvfvxc.html

C#:   var (a, b) = pair;
来源：http://dali.iojbl.cn/Article/details/gtxlxyyzhz.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtmvemqcfb.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.chenjidiqi.icu/Article/details/gtmyetobst.html

PHP:  // 无重载
来源：http://dali.gzhubu.top/Article/details/gtqrhsepsu.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xuanzx.com/Article/details/gtftpwvhfy.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daria6918.cn/Article/details/gtnpninuat.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxinkj.top/Article/details/gtukzmjpxe.html

Go:   // 无重载：用不同函数名
来源：http://dali.redwolf501.top/Article/details/gtabiuyuie.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yueranfly.top/Article/details/gtltpjjjcq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyaayrkd.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtipqakorh.html

D. 数组 / 列表 / 集合
来源：http://dali.havefunace.top/Article/details/gtxuezdcig.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtczejfbuf.html

[D01] 创建数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtnvkdhfxa.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.dashuyun.cn/Article/details/gtwzqhvgmd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.0kj1m.cn/Article/details/gtnygxeeei.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tanke756.top/Article/details/gtpbktzeqv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.0kj1m.cn/Article/details/gtfmgsnoze.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.daxiang520.top/Article/details/gtolegipsg.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gtvkzfipmo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gotoacloud.top/Article/details/gtdmxradrg.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zdqjudy.top/Article/details/gtcahqdjdz.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gtxvsuzzio.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gtenuqkxzx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gteuzaipyy.html

JS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtrtjpujug.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtcmuaryor.html

Java: list.add(4);
来源：http://dali.jiagoushi.top/Article/details/gtpwyberjw.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxinkj.top/Article/details/gtvxozqqvh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jyoumei.cn/Article/details/gtssgfdhya.html

C#:   list.Add(4);
来源：http://dali.cdnleiting.top/Article/details/gtxmgkfjhh.html

[D03] 在指定位置插入元素
来源：http://dali.jinqigfzy.top/Article/details/gtivauqghy.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gticoyzqpf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtbegjpymj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.havefunace.top/Article/details/gtwdkrmklq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.yvedp.cn/Article/details/gtiftewwcj.html

Java: list.add(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtysqgqlpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenlongwang.top/Article/details/gtytelagad.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtbpiyrsnw.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtfyziluio.html

[D04] 删除元素
来源：http://dali.yanxiufei.cn/Article/details/gthnvilfzy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj202588.top/Article/details/gttgxwogfo.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.guowangkeji.top/Article/details/gtdtsumkxi.html


<!-- 参考信息 -->