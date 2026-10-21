代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtcanqqxix.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.havefunace.top/Article/details/gtqlxzjrtv.html

[B07] while 循环
来源：http://dali.jianghu66.top/Article/details/gtwkgugsmy.html

Py:   while i < 10: i += 1
来源：http://dali.tanke756.top/Article/details/gtrjxhzyeq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gtzzdksnvy.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtbbtuutrm.html

TS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtahcureuk.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gthonsuhlp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtgsjktsio.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtqrdxrcjd.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtaqzmaaul.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gtirildeiy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.smart0.xyz/Article/details/gtwjzdkltd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yuxming.cn/Article/details/gttmlwughi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtsrjepjpm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtefevdlsx.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtlhqupmsg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.mhx1999.top/Article/details/gtjwxdwqhv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dianchejie.cn/Article/details/gtgiuqaauk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtujeiltvh.html

[B09] break 与 continue
来源：http://dali.yvedp.cn/Article/details/gtokzhafgx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ivvv.top/Article/details/gtowfvecse.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyuxmhrp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtveudywtc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gthjlhburs.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtamqbopdc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xinyue.icu/Article/details/gtqokxoykg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtsmdujroo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtucaamnff.html

[B10] 遍历同时拿索引
来源：http://dali.ppjwa.cn/Article/details/gtwpueykjn.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gtmrmyfgig.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtpmzdxzky.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtxarzetwx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtodywgbmf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.redwolf501.top/Article/details/gtqtsunndq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gtljgttsys.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtlohcgiwv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgfzy.top/Article/details/gtigkitjjc.html

[B11] 生成数字序列 / 区间
来源：http://dali.hywenlv.cn/Article/details/gtqylaujkx.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtmieibcqo.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtknovjemr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenlongwang.top/Article/details/gtkjbovwrx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtlxebjcdv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuetiantiany.cn/Article/details/gteddsxdkb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtbdessejj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtuuantcba.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtqrrjmlsv.html

[B12] 跳出多层循环
来源：http://dali.jyoumei.cn/Article/details/gtiyzdyltb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtjhfgxbdy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtmzzwplxm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtaxmdzvhn.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gthhrpxivt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtjdvikgnp.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sxryk.cn/Article/details/gtwjxftnmm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtipgqwbnk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ybcxt.top/Article/details/gtfqkthgsi.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtdopqibnd.html

Py:   isinstance(x, (int, float))
来源：http://dali.pycfn.com/Article/details/gtmskfcxtr.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gtzxjcfvmz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtfqahttgq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gtnspvqbdc.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gtnrohmlfy.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gttcxfosgb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtgtwzqemp.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtxyatfvzx.html

[B14] 判断值是否在集合内
来源：http://dali.yongpay.top/Article/details/gtuavbmlaw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yongpay.top/Article/details/gtcmscijpw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.iojbl.cn/Article/details/gtwtdyczhg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtafvwabys.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zdqjudy.top/Article/details/gtbshhrxud.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtfnvwqyco.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuxming.cn/Article/details/gtelvuoirj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtnjklvccq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtkassskxk.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtiymawozs.html

Py:   a and b or not c
来源：http://dali.cashguo.top/Article/details/gtqvpphjam.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtryzaofrx.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gthxyddium.html

TS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtdzngdprh.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtydldmscf.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtoucnodnb.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtjudostiz.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtyeppxecs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkqawlyak.html

Py:   if not data: return
来源：http://dali.zdqjudy.top/Article/details/gtonzaonlt.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gtqmsqrurl.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtqnnsadps.html

TS:   if (!data) return;
来源：http://dali.jinghuilouyu.cn/Article/details/gtelthwyrj.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtbswhbkky.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtuqoxfqoh.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gthaisrvgp.html

C#:   if (data == null) return;
来源：http://dali.yongpay.top/Article/details/gtdusdshqf.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkefglvhl.html

C. 函数与作用域
来源：http://dali.c1oappe.top/Article/details/gtsruaxugu.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtovcpgfxm.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtyohtvocr.html

Py:   def add(a, b): return a + b
来源：http://dali.tian-w.cn/Article/details/gtkyxqtblx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtbgtmtzbf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gtfktnagjm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvzzondgp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtrqpwikeo.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtrhildujk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtiadtunxg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtulgkwsnx.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gtdwnmmymb.html

Py:   def greet(name="World"): return name
来源：http://dali.tian-w.cn/Article/details/gtsvxjonps.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ybcxt.top/Article/details/gtsaedljah.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.birdmap.top/Article/details/gtpjyhjqou.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtjddjwfks.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtwdwnwbob.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtsyihddlm.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtphoaxztn.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.meibo888.top/Article/details/gtfawihmjq.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtpdkruokp.html

Py:   def total(*args): return sum(args)
来源：http://dali.dianchejie.cn/Article/details/gtjohpuhpq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtbyvfdvra.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ivvv.top/Article/details/gtbwnlwhqf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.316326.xyz/Article/details/gtkrnnwyzz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gtcwrdaknn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtwurltoph.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhixingplan.top/Article/details/gtxkmnhxjy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shzxlz.cn/Article/details/gtyerlicwc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pycfn.com/Article/details/gtwlazitps.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtlnbtslhd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gtwdgorium.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.0kj1m.cn/Article/details/gtxrjqttxa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtcxeerwdg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.haohaochexian.top/Article/details/gtwxbnmqhb.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtcexilorq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.0kj1m.cn/Article/details/gtqpdankeg.html

C#:   f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtdoyfyilx.html

[C05] 返回多个值
来源：http://dali.316326.xyz/Article/details/gtdlzzvkgb.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtcfodzftm.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtyieitluf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jlsjyb.cn/Article/details/gtiemxihyq.html

TS:   return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtjiyohmqn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtublebvmv.html

Go:   return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwvbrrqqh.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtccasyfbw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.andypj.xyz/Article/details/gtcebwdyjf.html

[C06] 匿名函数 / lambda
来源：http://dali.hongshengwenyu.top/Article/details/gtkdhdlhwc.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtvdhkiste.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.snrcjt.cn/Article/details/gtwskerkro.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtnshqagot.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtlxzbrznl.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtgfzfsgdd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.dashuyun.cn/Article/details/gtmpuqhgya.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tanke756.top/Article/details/gtbdtelftb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtixbjmqfx.html

[C07] 把函数作为参数传入
来源：http://dali.dianchejie.cn/Article/details/gtrbwyhuuj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cashguo.top/Article/details/gttujcgogb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gzhubu.top/Article/details/gtkdspjdqu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtzacrswbz.html

TS:   arr.map(String)
来源：http://dali.cashguo.top/Article/details/gtvgdmxidu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.chenjidiqi.icu/Article/details/gtswzexekr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.dashuyun.cn/Article/details/gtxavapezk.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtalsnhdvs.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtdchsebfi.html

[C08] 闭包
来源：http://dali.aibaodan.cn/Article/details/gtsfwfidvt.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hammf.cn/Article/details/gtzvyycwdm.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gtqyrhhags.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtpbnmoshh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtbvluhmbt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenzaomai.com/Article/details/gtyfbuyzil.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jinqigufen.top/Article/details/gtqbbpcvcb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.meibo888.top/Article/details/gtmkrfbvpx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtebixjewe.html

[C09] 递归
来源：http://dali.zycfv.cn/Article/details/gtbkkxxeno.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtgveqtfmn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtewcgprrv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangshuangyany.cn/Article/details/gttbyydnmo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pengpengdd.cyou/Article/details/gtnymtyrkv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ppjwa.cn/Article/details/gtaerayocp.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenzaomai.com/Article/details/gthcnyezqh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtwpjotpwi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ivvv.top/Article/details/gtqnplodwm.html

[C10] 变量作用域
来源：http://dali.pycfn.com/Article/details/gtjwhkecln.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtmwpxxmyl.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gotoacloud.top/Article/details/gtdsxvllvu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.aizwys.cn/Article/details/gtoquuvyxs.html

TS:   同 JS
来源：http://dali.nwbrower.top/Article/details/gttsavwhkh.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gtmzwulbbk.html

Go:   花括号块级作用域
来源：http://dali.yuxming.cn/Article/details/gtvwjcwwzu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.haohaochexian.top/Article/details/gtfdmoskfl.html

C#:   块级作用域
来源：http://dali.fengsongda.top/Article/details/gtgwlhbjan.html

[C11] 模块导入与导出
来源：http://dali.dashuyun.cn/Article/details/gtctbwtsdk.html

Py:   from module import func
来源：http://dali.cheryme.top/Article/details/gtmwskcplt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guowangkeji.top/Article/details/gtkqcpuoxo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtxkxseugr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gtjvxwtisl.html

Java: import java.util.List;
来源：http://dali.wangdashe.top/Article/details/gtvrwxrcky.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtsxtktzmw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gteckdotqh.html

C#:   using System.Text;
来源：http://dali.daria6918.cn/Article/details/gtaxrwskkd.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuanzhike.top/Article/details/gtgzfejgul.html

Py:   (lambda: print("run"))()
来源：http://dali.chenzaomai.com/Article/details/gttojraxhr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtosoeqgvq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yueranfly.top/Article/details/gtqrrfkxlf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gtygaocfnw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.hongshengwenyu.top/Article/details/gtrqwzlwot.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.mhx1999.top/Article/details/gtzmeeycqw.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gtbwguuawe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtyynkvurw.html

[C13] 类型声明 / 类型注解
来源：http://dali.shanyushiyangtech.top/Article/details/gtxdujvzqk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtszafuctv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gtceasrhkq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.9152youxi.cn/Article/details/gtqxwcmjxw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtgtofgsuw.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtoxchwaxh.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gtopwczmgn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangtech.top/Article/details/gttgzcqcmu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zycfv.cn/Article/details/gtsdkslcoz.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtucvqzogq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.andypj.xyz/Article/details/gtgmmqezrq.html

PHP:  // 无泛型
来源：http://dali.yangfankeji.com/Article/details/gtniadozjn.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gtofbcpzmw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hysaishi.cn/Article/details/gtzqcgzmpq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gtqmglegeh.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xinyue.icu/Article/details/gtrjdoiarh.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gtpqdxsfde.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.tian-w.cn/Article/details/gtjlhtrdvn.html

[C15] 解构 / 展开参数
来源：http://dali.havefunace.top/Article/details/gtuhsuwkfl.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fengsongda.top/Article/details/gtadglivcv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ivvv.top/Article/details/gtcmjuwfsh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtvlcyxnbn.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbvwwsnix.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtroxxezuq.html

Go:   // 无解构
来源：http://dali.xuanzx.com/Article/details/gtmdorleue.html

Ruby: a, b = pair
来源：http://dali.c1oappe.top/Article/details/gtistpmyjj.html

C#:   var (a, b) = pair;
来源：http://dali.zhongyouzk.top/Article/details/gtjzrxfuev.html

[C16] 函数 / 方法重载
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghtcaaen.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gtikydwolm.html

PHP:  // 无重载
来源：http://dali.xinyue.icu/Article/details/gtimwefdhe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.shuidangran.top/Article/details/gtjgrhrsbe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gtlmjuvply.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtdlitruap.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtqbdgifdt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtotdmjwai.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.shzxlz.cn/Article/details/gtoxnxqzdh.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtfukcuiyu.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtwpnwwdpj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtaggavlzt.html

[D01] 创建数组 / 列表
来源：http://dali.sweek.top/Article/details/gtugzrjmle.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuanzhike.top/Article/details/gtyxbthofh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtmufwjovx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhixingplan.top/Article/details/gtlpjgahcu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hongshengwenyu.top/Article/details/gtfbrpzhfx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xuanzx.com/Article/details/gtksqtbklq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtomhxcdqr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.iojbl.cn/Article/details/gtmchiswre.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuxming.cn/Article/details/gtvigwiqbq.html

[D02] 追加元素到末尾
来源：http://dali.gzhubu.top/Article/details/gtbqoxzsab.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258888.top/Article/details/gtuhdxwief.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxinkj.top/Article/details/gtkpqrkxqd.html

JS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtamkhmpav.html

TS:   arr.push(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrakivms.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtcjpzpvob.html

Go:   arr = append(arr, 4)
来源：http://dali.yonumen.top/Article/details/gtctkfyutw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cashguo.top/Article/details/gtdngxgtyc.html

C#:   list.Add(4);
来源：http://dali.hysaishi.cn/Article/details/gtvocwtjeb.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gtfyknpmyf.html

Py:   arr.insert(0, 0)
来源：http://dali.jqgfzy.top/Article/details/gtnmejtdix.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yangfankeji.com/Article/details/gtahmqkqot.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.tanke756.top/Article/details/gtopgoncmk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guannengcc.top/Article/details/gtjzrtzvbo.html

Java: list.add(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtjqwykimv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtvcaektxj.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.haohaochexian.top/Article/details/gtjcmnvdxb.html

C#:   list.Insert(0, 0);
来源：http://dali.zhengqikj.top/Article/details/gtuoqpoghy.html

[D04] 删除元素
来源：http://dali.jiagoushi.top/Article/details/gtbvjgrxul.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuzqaczp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.andypj.xyz/Article/details/gttqjxnyfd.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.zhengqikj.top/Article/details/gttsryyuue.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtanxsqwmq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuxming.cn/Article/details/gtdjvlceip.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ivvv.top/Article/details/gtwbtjshwz.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtuoiooyip.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ehwqpu.com/Article/details/gtbuawirch.html

[D05] 访问与修改元素
来源：http://dali.sysykeji.top/Article/details/gtjghpfwut.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.iojbl.cn/Article/details/gtlxcrnanp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtvticfcnh.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yuxming.cn/Article/details/gtpvjyqije.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.xziqi.cn/Article/details/gtguxbykzo.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.gogol.net.cn/Article/details/gtxdhdnynw.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtkklwgybi.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.redwolf501.top/Article/details/gtsbwzwxhg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtqtlqgdry.html

[D06] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtsaodmase.html

Py:   len(arr)
来源：http://dali.zhijiandao.cn/Article/details/gttnbihtfm.html

PHP:  count($arr);
来源：http://dali.bjfxy.top/Article/details/gtdycfqnjv.html

JS:   arr.length
来源：http://dali.hnqzz.top/Article/details/gtqakftdyz.html

TS:   arr.length
来源：http://dali.chenlongwang.top/Article/details/gtyzirpint.html

Java: list.size();
来源：http://dali.ehwqpu.com/Article/details/gtyfvdtoqs.html

Go:   len(arr)
来源：http://dali.jqgfzy.top/Article/details/gtlsxkcquh.html

Ruby: arr.length; arr.size
来源：http://dali.andypj.xyz/Article/details/gtjypwdcxw.html

C#:   list.Count;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifwjlgez.html

[D07] 切片 / 取子数组
来源：http://dali.daxiang520.top/Article/details/gtwjsarult.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtnyvaqvnu.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.redwolf501.top/Article/details/gttrhbfoqw.html

JS:   arr.slice(1, 4);
来源：http://dali.shangyingyoupin.top/Article/details/gtpofaclrg.html


<!-- 参考信息 -->