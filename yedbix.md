代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gtobqnwlrb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtotgvmdbi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xylfe.cn/Article/details/gtigknruyr.html

[B04] for 计数循环
来源：http://dali.zhengqikj.top/Article/details/gtircowmej.html

Py:   for i in range(10): print(i)
来源：http://dali.wangdashe.top/Article/details/gtizxenneu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdririvd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.kuanghao11.cn/Article/details/gteuxtlbqn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtetukaodg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtygjgemkd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gttmdcqfvh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shanyushiyangtech.top/Article/details/gtfinssukg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.shangyingyoupin.top/Article/details/gtgrwujxbq.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtkckmfmgj.html

Py:   for item in arr: print(item)
来源：http://dali.yuanzhike.top/Article/details/gthemypuck.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj20258888.top/Article/details/gtbmefapem.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtijtvtbeu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtzwtadsam.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jianghu66.top/Article/details/gtnphniygt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtlxgyorvt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.guowangkeji.top/Article/details/gtgxoprjxl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yj20258.top/Article/details/gthqnunvrf.html

[B06] 遍历字典 / 对象
来源：http://dali.gogol.net.cn/Article/details/gtgpkpliry.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gtuvxyqzaw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cqqwz.cn/Article/details/gtpojkdcwu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwtvszwhp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gtzfdkrgbo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gtdjtkzfis.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxuanxn.top/Article/details/gtdbudzpjc.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aizwys.cn/Article/details/gtqjsborqo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigufen.top/Article/details/gtqyzuzjij.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtjsveuard.html

Py:   while i < 10: i += 1
来源：http://dali.cqqwz.cn/Article/details/gtcnixkozq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sxryk.cn/Article/details/gtbmismvfe.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtpesxtqtn.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtahzwaxko.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtadgteqqu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gteeiinxkk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ydzc1.top/Article/details/gtnswukvwv.html

C#:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtqpyugdjw.html

[B08] do-while（至少执行一次）
来源：http://dali.hysaishi.cn/Article/details/gtgzpirjfp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xylfe.cn/Article/details/gtetjujkqe.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtccvcuhbc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtpkzowdai.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtxoxlzvwl.html

Java: do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtuiqoclqs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.tanke756.top/Article/details/gtcqvvmhsq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtrarbxxpk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtjevdlrem.html

[B09] break 与 continue
来源：http://dali.cdnleiting.top/Article/details/gtxkpinvys.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtuurmapxy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtuwlyhkqi.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtdyqiihqs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtckryjccf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtabjpreqh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtezsstmfh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hywenlv.cn/Article/details/gttihkktix.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtaxtyyose.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtcefawciu.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.aibaodan.cn/Article/details/gtsduileqc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvqdmtgkj.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtfjvmafaf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtpwvbadsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gtxtfwmyhf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtjvbzarta.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtiskazwjt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jlsjyb.cn/Article/details/gtoqiknnip.html

[B11] 生成数字序列 / 区间
来源：http://dali.tanke756.top/Article/details/gtfzmrtluk.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gtxvsihgkw.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gtrwihxrkw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmfpjgfj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtqomyizzo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gtyaojvjqa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlouwcrb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitqsfexq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gttuphagic.html

[B12] 跳出多层循环
来源：http://dali.jianghu66.top/Article/details/gtgsioytao.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtaewhcmco.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gtskcmbkhy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtmxolqoyc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gthhcvtmkj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtwsoncapq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpmlnbigr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gttjrliyot.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhixingplan.top/Article/details/gtmqipzyxg.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtpvoajcda.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtnnhbdcui.html

PHP:  is_numeric($x)
来源：http://dali.xuanzx.com/Article/details/gtoziddhhz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtypfmywnk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtaamvyfjg.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gtujllblty.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtmvxvywms.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtmznnwojt.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gtohczerga.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtizrdoscf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gtdsycvipz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.0kj1m.cn/Article/details/gtwuvwxfmb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtrnwppxyq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtgpvocmtk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yonumen.top/Article/details/gtvspvjxno.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gtghfathjm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gtkjcavdny.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtarymnigq.html

[B15] 布尔运算与取反
来源：http://dali.chenlongwang.top/Article/details/gtvwjdxvqs.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtcckvdzma.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtxgfdkszc.html

JS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtpmamavhx.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtmqadqwfn.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtsfuotmkp.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtaqtluuck.html

Ruby: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gteyeuomfr.html

C#:   a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtdcrfwrlj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gtyzrqugwd.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtqzgmksqd.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtkygdelsy.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtpurldvxj.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtrmclepnf.html

Java: if (data == null) return;
来源：http://dali.zhijiandao.cn/Article/details/gtlgixqlkm.html

Go:   if data == nil { return }
来源：http://dali.zhongyouzk.top/Article/details/gtzjtqaumw.html

Ruby: return if data.nil?
来源：http://dali.316326.xyz/Article/details/gtooqrvyii.html

C#:   if (data == null) return;
来源：http://dali.shuidangran.top/Article/details/gtqoxavwgi.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtvccpxnzt.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gtycvavixs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtohpiilfm.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtmkhtnmcj.html

Py:   def add(a, b): return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtlidruxuu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gtmirarvkl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtublynxay.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldkasgfx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtqvkfluoj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigufen.top/Article/details/gtatrjhqxl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shangyingyoupin.top/Article/details/gtisxzcesx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtyfrgspfc.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtdtyivnpi.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtopiulvpg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtjdhpiwzj.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtafwzkspu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.daria6918.cn/Article/details/gtyxzidvtm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.bjfxy.top/Article/details/gtnziulgnx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtqmzcatqb.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj202588.top/Article/details/gtcmyiwezt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtvrpfbzqo.html

[C03] 可变参数
来源：http://dali.guowangkeji.top/Article/details/gtunbkcbrj.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gtnxxpndcr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtkyyirgzy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gtaliftnlm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jyoumei.cn/Article/details/gtgicdjygn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtqgdlcuqh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hammf.cn/Article/details/gtacsvwbhv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtqnliwpib.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gtejfuytug.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhiwuduotai.top/Article/details/gtysarnvpz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aibaodan.cn/Article/details/gtlhbobezb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtpjsztajp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuanzhike.top/Article/details/gtywlmxgho.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xylfe.cn/Article/details/gtokqovrzc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gtkhpropil.html

Go:   // 无：用配置结构体参数
来源：http://dali.fzhhl.top/Article/details/gtbttuqaby.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqvkfyup.html

C#:   f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtbxkuyhlu.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtoiszrfjx.html

Py:   return a, b
来源：http://dali.dashuyun.cn/Article/details/gtpocxnovi.html

PHP:  return [$a, $b];
来源：http://dali.gzhubu.top/Article/details/gtusanixxc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtzdylwuig.html

TS:   return { a, b };
来源：http://dali.bjfxy.top/Article/details/gtitlhpuwp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tanke756.top/Article/details/gtvdslrqnr.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gtnjtpzsxu.html

Ruby: return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtorazuwof.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gtrdhngwsb.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtgfkjgyii.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtnpxbkoai.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtiedguyfs.html

JS:   const square = x => x * x;
来源：http://dali.guannengcc.top/Article/details/gtopshhuur.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtynojuxiz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hfpthk.cn/Article/details/gthnkynouk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yj202588.top/Article/details/gtwtzzokpf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtjisrerhh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtbdponovg.html

[C07] 把函数作为参数传入
来源：http://dali.bjfxy.top/Article/details/gtbqihjdmm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtibpiaccq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.dianchejie.cn/Article/details/gtqvbeglqp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtueuqpzyd.html

TS:   arr.map(String)
来源：http://dali.nwbrower.top/Article/details/gtgnwbldwk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.bjfxy.top/Article/details/gtjefmqqto.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jiagoushi.top/Article/details/gtzvelmpiv.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtidpaiahr.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shzxlz.cn/Article/details/gthalquicj.html

[C08] 闭包
来源：http://dali.vqdsnc.cn/Article/details/gtbiagybhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhoulong.xyz/Article/details/gtdpclywhk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoekpmhgc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtmlzisvrh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtbzesuydu.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ybcxt.top/Article/details/gtguvxwytq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cashguo.top/Article/details/gtwdnjsxes.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zdqjudy.top/Article/details/gtjbmwhlye.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gtmyzmuvhu.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtqbiycukz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gtddmbjehm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtqcljmsiv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtgqaaqzww.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ybcxt.top/Article/details/gtawjmqmkv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtmhvsjgwl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.shzxlz.cn/Article/details/gtyhqwftuk.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtamgkrucc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrfbrobnd.html

[C10] 变量作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtshgrueui.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtfpmqzdln.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yanxiufei.cn/Article/details/gtreeheyuv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gttigqnftq.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtcbzvvdef.html

Java: 方法内为块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtikntuswf.html

Go:   花括号块级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtgtlruxxw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xinyue.icu/Article/details/gttdsxcptb.html

C#:   块级作用域
来源：http://dali.cucudq.cn/Article/details/gtjyqlrvoi.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtpzevnrpu.html

Py:   from module import func
来源：http://dali.zhiwuduotai.top/Article/details/gtidwnywml.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.cheryme.top/Article/details/gtlpbukjve.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtttwwsuwp.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.mhx1999.top/Article/details/gtkvlzcsdb.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtspusmrch.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtrrgxdbvr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.hfpthk.cn/Article/details/gtzgxsgvxp.html

C#:   using System.Text;
来源：http://dali.cdnleiting.top/Article/details/gtzmebgqwg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj20258888.top/Article/details/gtbqrhnpdm.html

Py:   (lambda: print("run"))()
来源：http://dali.yonumen.top/Article/details/gtinluvwgh.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtrllwgeiv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.havefunace.top/Article/details/gtapcuacvc.html

TS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtsquuaskm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gthtljhmag.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.xziqi.cn/Article/details/gtnkrwpqym.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhijiandao.cn/Article/details/gtpwitivep.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtbanibktt.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttgtmtby.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shuidangran.top/Article/details/gtelmqyfac.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtticgqqdb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.chenlongwang.top/Article/details/gtkvnxlmdo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtstlblfpa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gttgqzpxnk.html

Go:   func add(a, b int) int
来源：http://dali.bjfxy.top/Article/details/gtyjfofugq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jinghuilouyu.cn/Article/details/gtrjwbhjzo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtbcwbgyfr.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gtroycnsnz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.bjfxy.top/Article/details/gtjbeserra.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtvrdcolbc.html

JS:   // 无泛型
来源：http://dali.sxryk.cn/Article/details/gtzoueuvki.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtwcalngoq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gtanmjmaek.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtoavbbunk.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gthobnbgmh.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.snrcjt.cn/Article/details/gtajwvtyzh.html

[C15] 解构 / 展开参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgejetykq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gaohongyu789.top/Article/details/gtvvhqwqqb.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuetiantiany.cn/Article/details/gtlveotqby.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtfklzjmup.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.cucudq.cn/Article/details/gtrohhlgkl.html

Java: // 无解构
来源：http://dali.chenjidiqi.icu/Article/details/gturvlgutd.html

Go:   // 无解构
来源：http://dali.yonumen.top/Article/details/gtzzkcnodw.html

Ruby: a, b = pair
来源：http://dali.nwbrower.top/Article/details/gtmalcndaz.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtpmobgnvt.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtkvtlenrv.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gtxvbnnpcl.html

PHP:  // 无重载
来源：http://dali.ppjwa.cn/Article/details/gtjoggohou.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gthgbybicn.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.birdmap.top/Article/details/gtqbygocdi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gtitsrabug.html

Go:   // 无重载：用不同函数名
来源：http://dali.316326.xyz/Article/details/gtngnlwkod.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sweek.top/Article/details/gtgibxmgqb.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jqgfzy.top/Article/details/gtrcinjofd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvykbioo.html

D. 数组 / 列表 / 集合
来源：http://dali.jqgfzy.top/Article/details/gtitfnamzp.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtfmbiuedq.html

[D01] 创建数组 / 列表
来源：http://dali.hnxiangtu.top/Article/details/gtoakbtscc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.wangshuangyany.cn/Article/details/gthalfcotq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.chenzaomai.com/Article/details/gtbiftwxbl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.daxiang520.top/Article/details/gtpidbqvxj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gtkfptiqkg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtlgjovfvp.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.fzhhl.top/Article/details/gtpdihkdiy.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gtxhuystvn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yonumen.top/Article/details/gtgmaeizgk.html

[D02] 追加元素到末尾
来源：http://dali.hnqzz.top/Article/details/gtgofgqzax.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shuidangran.top/Article/details/gtozcsnpkf.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.gotoacloud.top/Article/details/gtwcbnffhk.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdesirhjl.html

TS:   arr.push(4);
来源：http://dali.fengsongda.top/Article/details/gtheccrtib.html

Java: list.add(4);
来源：http://dali.jqgufenzy.top/Article/details/gtbhcbmqbk.html

Go:   arr = append(arr, 4)
来源：http://dali.yuanzhike.top/Article/details/gtaqtcjmzm.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtlkljasgw.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gtetlcoucp.html

[D03] 在指定位置插入元素
来源：http://dali.c1oappe.top/Article/details/gtddwdssbg.html

Py:   arr.insert(0, 0)
来源：http://dali.sufxvd.cn/Article/details/gtoezxhfoz.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtibdkczbk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yj20258.top/Article/details/gtakymieeo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gthdltpcnl.html

Java: list.add(0, 0);
来源：http://dali.nanxuanxn.top/Article/details/gtczkveswa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.aizwys.cn/Article/details/gtopcgubla.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtenyuklfa.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgcrtqip.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gttqrnybpk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.gzhubu.top/Article/details/gtvrxgvepv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.wangshuangyany.cn/Article/details/gtgsfpdevk.html


<!-- 参考信息 -->