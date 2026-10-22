代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvotgwrim.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtjnonlhyg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yanxiufei.cn/Article/details/gtzvfcbprt.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj202588.top/Article/details/gtrblwtvyz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guowangkeji.top/Article/details/gtenwawhsc.html

[B06] 遍历字典 / 对象
来源：http://dali.andypj.xyz/Article/details/gtiitadpsq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gtteactntj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejfxmbzr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhengqikj.top/Article/details/gtyteeexzt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj202588.top/Article/details/gtkaxsoucl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tianlin.xyz/Article/details/gtafiryhhy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daria6918.cn/Article/details/gtgnykmhtt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwiycoya.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtbdyenocy.html

[B07] while 循环
来源：http://dali.xuanzx.com/Article/details/gtfnmbhzgm.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gtukmoczls.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.bjfxy.top/Article/details/gtxatooeud.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtzgwixwkp.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtnguwtamg.html

Java: while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtuiovijaa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gtckyoquyc.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258888.top/Article/details/gtyzruumko.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtzeoujzdx.html

[B08] do-while（至少执行一次）
来源：http://dali.316326.xyz/Article/details/gtqosyedrd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hongshengwenyu.top/Article/details/gtsdvkhkfp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtqgnayucj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtjtfwausz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtybbqmuwn.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttevanrll.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daxiang520.top/Article/details/gtlautonjq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtzfiltqcj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtxjhkaosh.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtkfhtfbjq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gtktmbgarg.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtsiykopjs.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gttfouxlfp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtyijrskmr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtwwpgysym.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zdqjudy.top/Article/details/gttquofjxu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.0kj1m.cn/Article/details/gtsuautzlg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtkbfphrni.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtvqqnlsvl.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtvgdhxxjj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpgkkbcfy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtqoozxfok.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.vqdsnc.cn/Article/details/gtzxozbsch.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gzhubu.top/Article/details/gtaeflswvk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtqxnmhgou.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtryvqrrue.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ppjwa.cn/Article/details/gtlqgeampd.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtwbjbflfn.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuanzhike.top/Article/details/gtzaxathht.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gtyllahjkm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aibaodan.cn/Article/details/gtzjaezcio.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cucudq.cn/Article/details/gtcmnpufvz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtxmzjhuea.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gtwaheejnc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtgtfugzld.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtbrpzrrly.html

[B12] 跳出多层循环
来源：http://dali.haohaochexian.top/Article/details/gtwtnvsbip.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.tian-w.cn/Article/details/gtdoqpmzbp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtaaxovevv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtsombmlwc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtommjkskx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gteqjrpahx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.andypj.xyz/Article/details/gtfiimmknq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtmqgvnifz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gtkmzorutl.html

[B13] 判断是否为数字
来源：http://dali.ppjwa.cn/Article/details/gtqwpkfgov.html

Py:   isinstance(x, (int, float))
来源：http://dali.9152youxi.cn/Article/details/gthbgmylyt.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gtmnzihxhg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuxming.cn/Article/details/gtregcqbtx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtiiezxhpr.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtltxbbnds.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hnxiangtu.top/Article/details/gttwndkhug.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtdsegkcql.html

C#:   x is int or double or decimal
来源：http://dali.fzhhl.top/Article/details/gtbyrdfnos.html

[B14] 判断值是否在集合内
来源：http://dali.quarkkingdee.top/Article/details/gtoyyofgpp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtmyvtiiff.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtmrxzaauf.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtuzzkrghg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkfhudyvk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtkafbmkzk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gtbegnykvz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwvpvzcmk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtkcbafmnd.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtfuyuipkr.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtjjnunsxb.html

PHP:  $a && $b || !$c
来源：http://dali.tian-w.cn/Article/details/gtlxzlfznq.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtjlpqhvef.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtjkltbiam.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtcadtecnp.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtavpxvdbb.html

Ruby: a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtrawyymfm.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtrdhttxxe.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gttfwzqiyr.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gthrljgeyn.html

PHP:  if (!$data) { return; }
来源：http://dali.yueranfly.top/Article/details/gtznphxtrq.html

JS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtockeaqxu.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtmloxsepo.html

Java: if (data == null) return;
来源：http://dali.hnqzz.top/Article/details/gtrozxjxkg.html

Go:   if data == nil { return }
来源：http://dali.wangshuangyany.cn/Article/details/gttrythekg.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtmxowgsbt.html

C#:   if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtptormqwu.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtmnxijsxe.html

C. 函数与作用域
来源：http://dali.smart0.xyz/Article/details/gtwjmpxtbx.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtzyqczfzf.html

[C01] 定义函数
来源：http://dali.dashuyun.cn/Article/details/gtoxsgsfix.html

Py:   def add(a, b): return a + b
来源：http://dali.jiagoushi.top/Article/details/gthbgjlyfh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtuhwchgyn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtigxnngul.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yueranfly.top/Article/details/gtmaeifcfl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtzukhsybt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gttnkekryy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ppjwa.cn/Article/details/gtizmyfzua.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtxpprijid.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtiodhdqgt.html

Py:   def greet(name="World"): return name
来源：http://dali.svipenyu.cn/Article/details/gteevnbcxa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtrsmtgldf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtevunhhxn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gtugnrrsjz.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtzbcaiuzd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtxthuojjk.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gtwmnntlwk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nanxinkj.top/Article/details/gtozkqnyzs.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvgjhchye.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtlxwechgz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlinmqbad.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtkbskvbqk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gttynhedct.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtfkresryy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtywoubmqt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yuxming.cn/Article/details/gtseczaiia.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.aibaodan.cn/Article/details/gtfgivjxya.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gtquqoiyxl.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj202588.top/Article/details/gtggogqaux.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.dianchejie.cn/Article/details/gtckwwetar.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqomrzih.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtbmbiforh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.mhx1999.top/Article/details/gtvdxsarga.html

Go:   // 无：用配置结构体参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuixpidp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtjvvqsxgx.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtshieuzht.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtzazhxidt.html

Py:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gtawrxafhp.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtirqzcers.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtngbceghe.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtmsqngacw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtzqfefytf.html

Go:   return a, b
来源：http://dali.ehwqpu.com/Article/details/gtpgwhnjwz.html

Ruby: return a, b
来源：http://dali.jiagoushi.top/Article/details/gtygdlkpkd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ppjwa.cn/Article/details/gtqmtuibhg.html

[C06] 匿名函数 / lambda
来源：http://dali.sysykeji.top/Article/details/gtufkdvkib.html

Py:   square = lambda x: x * x
来源：http://dali.mhx1999.top/Article/details/gtgmuqdzxf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nwbrower.top/Article/details/gthebnphlk.html

JS:   const square = x => x * x;
来源：http://dali.jiagoushi.top/Article/details/gtcyygerbr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gtlvdonbhu.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtcgxjzqjc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtutvcdguu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.316326.xyz/Article/details/gtqnwxnlfa.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtaacxsdql.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtjfdssnvx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlhyksxr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gthmuhotky.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gtclsbkeou.html

TS:   arr.map(String)
来源：http://dali.bjfxy.top/Article/details/gtylewrwuu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gtaghlbeys.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fengsongda.top/Article/details/gtzkxdimxa.html

Ruby: arr.map(&:upcase)
来源：http://dali.birdmap.top/Article/details/gtnzmwrlhh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtufhrfkfe.html

[C08] 闭包
来源：http://dali.nanxinkj.top/Article/details/gtzewukjrb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xylfe.cn/Article/details/gtxetqusny.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gtksqzfgus.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtgkeyilhq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jiagoushi.top/Article/details/gturofzrta.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daxiang520.top/Article/details/gtfwlvhbsu.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jqgufenzy.top/Article/details/gtwdmpumfx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gtpgwsxdzp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtakaxhcjy.html

[C09] 递归
来源：http://dali.zhongyouzk.top/Article/details/gtvukvgyup.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gogol.net.cn/Article/details/gtdhcmnxrv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtremqrots.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtjvdaaaol.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zycfv.cn/Article/details/gtbjexchsd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtnisakxcq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.smart0.xyz/Article/details/gtvgjqyqob.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daxiang520.top/Article/details/gtcxaaitww.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtyisnzh.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtqhjawclg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hfpthk.cn/Article/details/gtlzjreokr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zycfv.cn/Article/details/gtbqumfdfh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gtifwqpldy.html

TS:   同 JS
来源：http://dali.yuxming.cn/Article/details/gtaoqznzmv.html

Java: 方法内为块级作用域
来源：http://dali.yueranfly.top/Article/details/gtwkfrgnpe.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtgtzoahti.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtyfatithk.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtlntlpdua.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gtqcwiljez.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtvwvbrwcl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sufxvd.cn/Article/details/gttzfwleaf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hammf.cn/Article/details/gtipbvkpkh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yanxiufei.cn/Article/details/gtohbezduq.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtxfmxqsog.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hammf.cn/Article/details/gtbqmzxdjk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhongyouzk.top/Article/details/gtuetycnyr.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtqcyccxie.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtsewurgbb.html

Py:   (lambda: print("run"))()
来源：http://dali.nwbrower.top/Article/details/gtxoatofev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhengqikj.top/Article/details/gtlhmeeqho.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gaohongyu789.top/Article/details/gtfqnwalfs.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtkorkbuyq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tian-w.cn/Article/details/gtmewzqvzg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtshlccuih.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtwmezniqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtsopljslo.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gtpjjekbpg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.andypj.xyz/Article/details/gtsquaosov.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gtobloxtbw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hfpthk.cn/Article/details/gtxcjgpswb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupthjlgb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtkdisuzau.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gtslwcfivs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.feifeiyinyue.top/Article/details/gttlbxuozl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtzstxqwhu.html

[C14] 泛型函数
来源：http://dali.sysykeji.top/Article/details/gthxbmlqyn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtcgkjtoax.html

PHP:  // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtqrdyalzj.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtehxwgbve.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258.top/Article/details/gtwascgsns.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gzhubu.top/Article/details/gtbjzfctjb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ppjwa.cn/Article/details/gtqblgeoyi.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtublevdtt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsudomsj.html

[C15] 解构 / 展开参数
来源：http://dali.sxryk.cn/Article/details/gtzbpjwdwt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.fzhhl.top/Article/details/gtzfwfgngy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangtech.top/Article/details/gtouywsfay.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtmzktkmbe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtsdqjkpgm.html

Java: // 无解构
来源：http://dali.andypj.xyz/Article/details/gttijknmzz.html

Go:   // 无解构
来源：http://dali.aizwys.cn/Article/details/gteiowtvsj.html

Ruby: a, b = pair
来源：http://dali.fengsongda.top/Article/details/gtwijunvzl.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gttiavubnv.html

[C16] 函数 / 方法重载
来源：http://dali.guowangkeji.top/Article/details/gtgqbfeori.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkmqjemjo.html

PHP:  // 无重载
来源：http://dali.nwbrower.top/Article/details/gtetxaqpqb.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.aibaodan.cn/Article/details/gtgonubmew.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yvedp.cn/Article/details/gtxmyplwvw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gtaisqfqcn.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtwlisrcxm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.smart0.xyz/Article/details/gtfszzmhlt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvzxedcac.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtphvarqqr.html

D. 数组 / 列表 / 集合
来源：http://dali.zycfv.cn/Article/details/gtjqzhpoxj.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtuagzggck.html

[D01] 创建数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtszzyiflo.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtilgqywkv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.feifeiyinyue.top/Article/details/gtowscorlr.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gtjrwgtoas.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xinyue.icu/Article/details/gtbdngqdsj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hysaishi.cn/Article/details/gtcbfjzjco.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtijrzgkqc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ppjwa.cn/Article/details/gtrldomfzz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ivvv.top/Article/details/gtzjywnayq.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtqypaqofx.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtqoawfnzv.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gthtimjxtq.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtchmknojo.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gttdimfusj.html

Java: list.add(4);
来源：http://dali.zhongyouzk.top/Article/details/gtjyaxkatm.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gthwiarvpv.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.cucudq.cn/Article/details/gtlepwoahy.html

C#:   list.Add(4);
来源：http://dali.cucudq.cn/Article/details/gthkcnjyar.html

[D03] 在指定位置插入元素
来源：http://dali.tianlin.xyz/Article/details/gtoehmvdii.html

Py:   arr.insert(0, 0)
来源：http://dali.yuanzhike.top/Article/details/gtadvbfywb.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.c1oappe.top/Article/details/gtzszqxhmf.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtqzlwzmzq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtqcezqrmb.html

Java: list.add(0, 0);
来源：http://dali.yj202588.top/Article/details/gtbjigdlnz.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtejmobeyp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.chenlongwang.top/Article/details/gtaonvnpvn.html

C#:   list.Insert(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtcuzsvofa.html

[D04] 删除元素
来源：http://dali.hnqzz.top/Article/details/gtfbbbsrns.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtadtbsdnq.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yuxming.cn/Article/details/gtoyxwigrr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtntvixsmv.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtgyzhueah.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gthsqzimow.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtqxsoddop.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.wangshuangyany.cn/Article/details/gtzpkqnlse.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.c1oappe.top/Article/details/gtvfcugosg.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtpwihzaik.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.guowangkeji.top/Article/details/gtprtwwjix.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gttqrhpmwv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtyguzwlxk.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtvbpbihxn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.nwbrower.top/Article/details/gtyvjfnxsn.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.meibo888.top/Article/details/gtxjsqzawr.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtahxvmssp.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtnnqiexuk.html

[D06] 数组长度
来源：http://dali.hongshengwenyu.top/Article/details/gtwfvowotw.html


<!-- 参考信息 -->