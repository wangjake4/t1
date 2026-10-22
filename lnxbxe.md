代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.dianchejie.cn/Article/details/gtboeooira.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtqldsbztn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shuidangran.top/Article/details/gtnleoesce.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hywenlv.cn/Article/details/gtqqczvavb.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtyeenogvn.html

Py:   for item in arr: print(item)
来源：http://dali.aizwys.cn/Article/details/gtmjcdbuug.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gtppuqfnkt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuzfztez.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtzvmjihth.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gtgqgttery.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtiyghxjaz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sweek.top/Article/details/gtbmjxucqa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gtfszgzdsy.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gtehswlkim.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gtwuxbhkin.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtadmilbco.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gtkqudlpos.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtoocydmzh.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.meibo888.top/Article/details/gtcomuobpn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.wangshuangyany.cn/Article/details/gtjuszducs.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhengqikj.top/Article/details/gttcqymthv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gttbrpjorj.html

[B07] while 循环
来源：http://dali.yueranfly.top/Article/details/gthklgzlpm.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gtrdsqjnts.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shuidangran.top/Article/details/gtlmnrzcaj.html

JS:   while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gtalgabmcq.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtuktdjfeu.html

Java: while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtagaqgdpd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmbjydnhu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gtuvenbikt.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtmtdqfezi.html

[B08] do-while（至少执行一次）
来源：http://dali.yj202588.top/Article/details/gtbthbveez.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuetiantiany.cn/Article/details/gtiynigvup.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtkrhjfcbo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtmgkfsocq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gtmeurbahm.html

Java: do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtpbdjajki.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yuxming.cn/Article/details/gthzzjapjq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtziudjfzc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtatniuoxh.html

[B09] break 与 continue
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmwytcej.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gtsfccbqao.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtansejqin.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtzgtiezdd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtxtgkmpji.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtbllszvja.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gtnzcqocxf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtvlguknyp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtlxfagpzh.html

[B10] 遍历同时拿索引
来源：http://dali.jiagoushi.top/Article/details/gtrhowzrzt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.iojbl.cn/Article/details/gtwnwufalt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcxiusnth.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtvtgfavup.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtdidjsxkl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258888.top/Article/details/gtobszrmgc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.bjfxy.top/Article/details/gtghfwijno.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhoulong.xyz/Article/details/gtlwaooncy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yonumen.top/Article/details/gtlybevqdh.html

[B11] 生成数字序列 / 区间
来源：http://dali.hongshengwenyu.top/Article/details/gtcjnlqlbq.html

Py:   list(range(0, 10, 2))
来源：http://dali.mhx1999.top/Article/details/gtgxidizrz.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gttvjgdcvc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jlsjyb.cn/Article/details/gtseovzegl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnqzz.top/Article/details/gthhkugvai.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtdbuvaooo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jinqigfzy.top/Article/details/gtsvnqrery.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtckhrycwk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xinyue.icu/Article/details/gtojwxltxa.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtoapacwsa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigufen.top/Article/details/gtmypwphia.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gtljlrtscd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtwzftbgzv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtvwrdxwos.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlscvfxh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yangfankeji.com/Article/details/gtnxijqgtw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gzhubu.top/Article/details/gtnkgrwqwr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gtwoyiqoha.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtwfmyaiut.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtiavzxckk.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtjsckefai.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sufxvd.cn/Article/details/gtohqambjy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gtgtjdqdzv.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtlqjqqdla.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cashguo.top/Article/details/gtgifiainc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtrhiipqyq.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtygxzuqqo.html

[B14] 判断值是否在集合内
来源：http://dali.hywenlv.cn/Article/details/gtexrydsll.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhongyouzk.top/Article/details/gtvnvqxbck.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.birdmap.top/Article/details/gtedeivfrg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cucudq.cn/Article/details/gtnydveftu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtgmhxafvv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hywenlv.cn/Article/details/gtlffozedb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jqgfzy.top/Article/details/gtfqfqlpqy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenlongwang.top/Article/details/gtpdhedzji.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfgrxqza.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtyawupyqo.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtbghsdkhs.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gthcxbhxoj.html

JS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gttrjexhvc.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtkjemjugw.html

Java: a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtquzdcpum.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gttbxeyexf.html

Ruby: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtqahwwmdi.html

C#:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtvrswshcr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gtiapkjsdq.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtggtipcug.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgfzy.top/Article/details/gtqmnwbcsn.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtbwxrzsar.html

TS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtgqwekjbe.html

Java: if (data == null) return;
来源：http://dali.aibaodan.cn/Article/details/gtbvuzkscp.html

Go:   if data == nil { return }
来源：http://dali.jqgufenzy.top/Article/details/gtazbwtdpo.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtwasuttgd.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtviavjsjt.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtbtiejihb.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtgxewysip.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtwhvfynxs.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtedfzriwa.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjwehexz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtjzmyuvzf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtdrhjtoaj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gtmtwzkcqk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gtnyktovxk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtbdspfwlf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yj202588.top/Article/details/gtdhqsnpss.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtkofsmzff.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtfblpsiwf.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtxfeijjjj.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gtixfwfpsi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhengqikj.top/Article/details/gtkhzxgecf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtjasywnre.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtyoixiwba.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hammf.cn/Article/details/gtimxbbrki.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtduikocgd.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zdqjudy.top/Article/details/gtgbnyizhz.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtbvbzlcpn.html

Py:   def total(*args): return sum(args)
来源：http://dali.shangyingyoupin.top/Article/details/gtxijixdda.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.iojbl.cn/Article/details/gtkxtwsplo.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtczlcdfau.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtgvpogwua.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtfcwwskdr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenjidiqi.icu/Article/details/gtesokehyk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtcwoqdoho.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhiwuduotai.top/Article/details/gtnkhrbgcz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.smart0.xyz/Article/details/gtuhvaklsj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtomzwmxne.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtnfkbyyxs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtylgpxppw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gaohongyu789.top/Article/details/gtjvqvvvkg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gzhubu.top/Article/details/gtszdinvvh.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgufenzy.top/Article/details/gtbizfiwpg.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgedvijqj.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtzazoacuy.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtldlktnnj.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtryrqjlgp.html

PHP:  return [$a, $b];
来源：http://dali.dianchejie.cn/Article/details/gtnbwmriif.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtfoqiqtdo.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gttqgjchrz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtwfrmfjex.html

Go:   return a, b
来源：http://dali.jyoumei.cn/Article/details/gtwijxkrkl.html

Ruby: return a, b
来源：http://dali.yuxming.cn/Article/details/gtsiqzlplt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtvtiogknz.html

[C06] 匿名函数 / lambda
来源：http://dali.chenjidiqi.icu/Article/details/gtpobrrgcc.html

Py:   square = lambda x: x * x
来源：http://dali.ehwqpu.com/Article/details/gtyeuhhcwt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pengpengdd.cyou/Article/details/gtxfohjbte.html

JS:   const square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtgtnrtyex.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.nwbrower.top/Article/details/gtllsilcjb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.wangdashe.top/Article/details/gttuzqmblk.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtknrpzxow.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aibaodan.cn/Article/details/gtkmmvohye.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtiokpktef.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtinknjfwa.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tanke756.top/Article/details/gteplnfser.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtnakeboqz.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.chenlongwang.top/Article/details/gtlznbskia.html

TS:   arr.map(String)
来源：http://dali.ehwqpu.com/Article/details/gtzyqogdja.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ehwqpu.com/Article/details/gtjfdlgtgd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtxyuuzvbw.html

Ruby: arr.map(&:upcase)
来源：http://dali.jiagoushi.top/Article/details/gtzjwwjdxh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hammf.cn/Article/details/gtioxoscnx.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtlwqhjsth.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.quarkkingdee.top/Article/details/gtsrqaqrqy.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhixingplan.top/Article/details/gttxluafjv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtwczsfthf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtdrgvrfhn.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gtdrubofab.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xinyue.icu/Article/details/gtilnerlxl.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yonumen.top/Article/details/gtwfqczczh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtykblfdkc.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtkqbqjwmu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gtklhlqddm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gtmpmxcobb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtfjzbliae.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtgqhvcsvy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gtdjalhmqa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.guannengcc.top/Article/details/gtvlacqgue.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.svipenyu.cn/Article/details/gtsayfoklm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtzkejbdta.html

[C10] 变量作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtwuntpbbi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinqigufen.top/Article/details/gtriprixag.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumuzeybv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gthdwhayzf.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtygklrius.html

Java: 方法内为块级作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcobjibak.html

Go:   花括号块级作用域
来源：http://dali.nanxinkj.top/Article/details/gteeehjcel.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtuuzuogth.html

C#:   块级作用域
来源：http://dali.zhixingplan.top/Article/details/gtqclixwjg.html

[C11] 模块导入与导出
来源：http://dali.yj202588.top/Article/details/gtiyzwfbyz.html

Py:   from module import func
来源：http://dali.cucudq.cn/Article/details/gtxogfvylv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yongpay.top/Article/details/gtjokquofv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sufxvd.cn/Article/details/gteflyuids.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cdnleiting.top/Article/details/gtbskdqbnk.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtzfbrazaz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.c1oappe.top/Article/details/gtqezqahcn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gthfioglmv.html

C#:   using System.Text;
来源：http://dali.jianghu66.top/Article/details/gtgkjfrlfo.html

[C12] 立即执行函数 IIFE
来源：http://dali.yj202588.top/Article/details/gtphnkkedl.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gtzosbokns.html

PHP:  (function () { echo "run"; })();
来源：http://dali.snrcjt.cn/Article/details/gtwoxibkdi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtisqahpjp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.bjfxy.top/Article/details/gthnrchxac.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtkxytkbzk.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gtgpsvtpph.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gtjfiundqf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtodxotkiu.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gttvuyjqhm.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhixingplan.top/Article/details/gttesgddqy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtanmmnirz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tianlin.xyz/Article/details/gtspksbded.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtxxxacsud.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtcbkbmwrt.html

Go:   func add(a, b int) int
来源：http://dali.chenjidiqi.icu/Article/details/gtazapwvif.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gtcfqcdjvw.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gtpzpaosun.html

[C14] 泛型函数
来源：http://dali.wangshuangyany.cn/Article/details/gtakozzpgd.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yuxming.cn/Article/details/gtehpuuuzf.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtrbhzwoxt.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgjumubx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.vqdsnc.cn/Article/details/gtylockzsk.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtlcuhjnff.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cucudq.cn/Article/details/gtacjelzjv.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtusjqxqxl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gtsjrfbglf.html

[C15] 解构 / 展开参数
来源：http://dali.cheryme.top/Article/details/gttjeemoei.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtbddoinoc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cashguo.top/Article/details/gtffosuvrn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtkyuqkyeq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtjjzqrcuq.html

Java: // 无解构
来源：http://dali.hnqzz.top/Article/details/gtagchgmov.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gtlpwzjesy.html

Ruby: a, b = pair
来源：http://dali.nanxinkj.top/Article/details/gtfbygnwod.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvqrsrtqf.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtlzeflnfu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinghuilouyu.cn/Article/details/gtgsbgcaia.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtjhpkmxby.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.svipenyu.cn/Article/details/gtabsneiws.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtrirpeuov.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cqqwz.cn/Article/details/gtevzjhjup.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtncqhilre.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hysaishi.cn/Article/details/gtsmuqubby.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfnnnoiqh.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtwovgdgdv.html

D. 数组 / 列表 / 集合
来源：http://dali.zhoulong.xyz/Article/details/gtlxsmxtfz.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtptwysdnz.html

[D01] 创建数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtobxjknrd.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tianlin.xyz/Article/details/gtfvuoeapz.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.yvedp.cn/Article/details/gtozhxjaoy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yuanzhike.top/Article/details/gtzwcsavtv.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtjwxunjbn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhiwuduotai.top/Article/details/gtojmfztjh.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtjtdtszcf.html

Ruby: arr = [1, 2, 3]
来源：http://dali.guowangkeji.top/Article/details/gtclsoasnp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jinqigfzy.top/Article/details/gtrfwdqfsi.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gteljolyel.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pycfn.com/Article/details/gtwpplrscj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jqgfzy.top/Article/details/gtvjujgczv.html

JS:   arr.push(4);
来源：http://dali.andypj.xyz/Article/details/gtxlnsrvna.html

TS:   arr.push(4);
来源：http://dali.dashuyun.cn/Article/details/gtxqcdjiwy.html

Java: list.add(4);
来源：http://dali.wangdashe.top/Article/details/gttsmcjmxy.html

Go:   arr = append(arr, 4)
来源：http://dali.pycfn.com/Article/details/gtcehyjfeb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtpstqhnsl.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtjuclxnub.html

[D03] 在指定位置插入元素
来源：http://dali.zhixingplan.top/Article/details/gtvdoavebo.html

Py:   arr.insert(0, 0)
来源：http://dali.cheryme.top/Article/details/gtdnhizfua.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtcwgjalmc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtlpuewpfn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtukiydgjc.html

Java: list.add(0, 0);
来源：http://dali.pycfn.com/Article/details/gtgepdddfi.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cashguo.top/Article/details/gttnhndmzy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhengqikj.top/Article/details/gtzvfgzwku.html

C#:   list.Insert(0, 0);
来源：http://dali.snrcjt.cn/Article/details/gtvduhlowb.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtnaqoctcl.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.nanxinkj.top/Article/details/gtzaarutun.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhongyouzk.top/Article/details/gthwypkrsl.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gthzghadtr.html

TS:   arr.splice(0, 1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlezbwxkl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.meibo888.top/Article/details/gtuqugczjq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtzvkftqwx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.chenzaomai.com/Article/details/gthbvxjskr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.daria6918.cn/Article/details/gtxsaloylp.html

[D05] 访问与修改元素
来源：http://dali.yuanzhike.top/Article/details/gtfnttyomg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xinyue.icu/Article/details/gthgucpzbb.html


<!-- 参考信息 -->