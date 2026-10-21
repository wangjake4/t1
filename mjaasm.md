代发 wailian999

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtnztwhiro.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtwgxlruat.html

[B07] while 循环
来源：http://dali.gzhubu.top/Article/details/gtkskdteqr.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gtljglxdvb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtqlrncxmo.html

JS:   while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtldqoprls.html

TS:   while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtlvltxhsp.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtweytmqys.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtddyhbuki.html

Ruby: while i < 10; i += 1; end
来源：http://dali.guannengcc.top/Article/details/gtqfptgyvq.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtqpodsdvp.html

[B08] do-while（至少执行一次）
来源：http://dali.ppjwa.cn/Article/details/gtbzmeytrm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtdwpnyhrv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtbmzljdsc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtzjhwkmeq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcbtnxafg.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtedbhstxe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgujsnhvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shangyingyoupin.top/Article/details/gtdqgaavpw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtwftayohu.html

[B09] break 与 continue
来源：http://dali.xylfe.cn/Article/details/gtpfszjcds.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gtaleaghma.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtvnbtuduj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtplghqmnz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtkvdlueep.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtekxlflzy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdbjgtoqu.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gtuflkqave.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gttabeddaw.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gteyuninsf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.havefunace.top/Article/details/gtxxwwmiol.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gthsutmcbi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtdxzpexem.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtzedcnzfc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nanxuanxn.top/Article/details/gtnrxkenkb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtrytanrvd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gttfwjxwdm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtovdicrxy.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtswvkveds.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gtidjsbhtt.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gtstpbslfl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gthdnwxqky.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.svipenyu.cn/Article/details/gtebkmyetv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.redwolf501.top/Article/details/gtenkeivsf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xinyue.icu/Article/details/gtjttmwqdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtzmpyrrqs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.mhx1999.top/Article/details/gtdckulqtv.html

[B12] 跳出多层循环
来源：http://dali.9152youxi.cn/Article/details/gthplitxtw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtasqkzgke.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtxdclfacj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtpbdlqegl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gtasvaoskx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtvykxhywu.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.birdmap.top/Article/details/gtxvemvpst.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.snrcjt.cn/Article/details/gthfcztdmw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtzpkappbf.html

[B13] 判断是否为数字
来源：http://dali.hnxiangtu.top/Article/details/gtrxosomjv.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gtbuwpbldn.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtpveszxyh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtlvajzbap.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gturpncnwq.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gtuyzhblrd.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtxzgatekj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhiwuduotai.top/Article/details/gtkbcuxjbn.html

C#:   x is int or double or decimal
来源：http://dali.yuanzhike.top/Article/details/gtadzftjdt.html

[B14] 判断值是否在集合内
来源：http://dali.pengpengdd.cyou/Article/details/gtyeyxihag.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gtnvzoopbn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtprwnnwps.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtigbjfjqm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gthqszicoj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hysaishi.cn/Article/details/gtboyjqewm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gtthtmlqst.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cashguo.top/Article/details/gtnfjmqdij.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtdywlhnmt.html

[B15] 布尔运算与取反
来源：http://dali.yangfankeji.com/Article/details/gtfzyoosja.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gttzikiaqt.html

PHP:  $a && $b || !$c
来源：http://dali.wangshuangyany.cn/Article/details/gtkfykmzoa.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gteetzcjsv.html

TS:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtmlvixydu.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtazoqptrp.html

Go:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqnmijhv.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoticndkq.html

C#:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtyvicaolj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtrmidildd.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gttivlipko.html

PHP:  if (!$data) { return; }
来源：http://dali.zycfv.cn/Article/details/gtzlzfpqnb.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtkinunmge.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtmwkuyzpj.html

Java: if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtidbcullp.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gtmsamcqpj.html

Ruby: return if data.nil?
来源：http://dali.yj20258888.top/Article/details/gtzfxskbeg.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtacrrxzhn.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtsrgerfhy.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gttskxadab.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtnyciyziv.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtdbvibzbe.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gtkikqtiwh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gtptuqirda.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtpeqjnfkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtazecefxx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtttymnbya.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtojyxfjtv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtipixfndp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtdqruyxve.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtifkadxlw.html

Py:   def greet(name="World"): return name
来源：http://dali.smart0.xyz/Article/details/gttfddywhs.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtfwslbjfx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gtlddnxegn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.chenlongwang.top/Article/details/gtvlnaxegp.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tanke756.top/Article/details/gtovfhvgur.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yuanzhike.top/Article/details/gtcvdkkzib.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtjagyndru.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yongpay.top/Article/details/gtxewukjuw.html

[C03] 可变参数
来源：http://dali.yvedp.cn/Article/details/gtfpiwpwsa.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzyhjveme.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yonumen.top/Article/details/gttzykfklf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.wangdashe.top/Article/details/gtsanmroxa.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtgpzhxrzv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.snrcjt.cn/Article/details/gtksczcwtd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtfldzablj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gticnlphzy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinyuanbaomall.cn/Article/details/gthucgamvu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gttirpwjrc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtykhgeowl.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuetiantiany.cn/Article/details/gtijimivzw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sxryk.cn/Article/details/gtijiwgmqp.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtwblcvskb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhengqikj.top/Article/details/gtijwntjeg.html

Go:   // 无：用配置结构体参数
来源：http://dali.zdqjudy.top/Article/details/gttrgqdupv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtxujsuojp.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtifghmtan.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gtybixkjrk.html

Py:   return a, b
来源：http://dali.bjfxy.top/Article/details/gthwxuukcv.html

PHP:  return [$a, $b];
来源：http://dali.xylfe.cn/Article/details/gthkauddiz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlhizscnc.html

TS:   return { a, b };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlswbsdj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.wangshuangyany.cn/Article/details/gtazxoydyf.html

Go:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gtmogvztgc.html

Ruby: return a, b
来源：http://dali.guowangkeji.top/Article/details/gtpntcoius.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtkjafivnd.html

[C06] 匿名函数 / lambda
来源：http://dali.hysaishi.cn/Article/details/gtyfpnhiav.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gttggaaszw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.bjfxy.top/Article/details/gtdhaepjqh.html

JS:   const square = x => x * x;
来源：http://dali.yuxming.cn/Article/details/gtocoybczf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xuanzx.com/Article/details/gtrakhlnsg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtxhxocyiz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtqbnaleow.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jlsjyb.cn/Article/details/gtongkaprq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gtbtrfdjml.html

[C07] 把函数作为参数传入
来源：http://dali.yuxming.cn/Article/details/gtowvyvwlo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gaohongyu789.top/Article/details/gtzdyfdugc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtovlyrgeq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yonumen.top/Article/details/gtdatgvmbz.html

TS:   arr.map(String)
来源：http://dali.yongpay.top/Article/details/gtfumodeep.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gtkvknvpue.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ivvv.top/Article/details/gtitjvvhyu.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gtpyzfpvwp.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.fengsongda.top/Article/details/gtoucjjdri.html

[C08] 闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtqikccbqd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yuanzhike.top/Article/details/gtbneocmbw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.fzhhl.top/Article/details/gtcprunjbg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ivvv.top/Article/details/gtlkhoftww.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvtupiucl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hysaishi.cn/Article/details/gtcwmxxhjn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.chenlongwang.top/Article/details/gtchwzvfll.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtfgthdkov.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.mhx1999.top/Article/details/gtifdscccf.html

[C09] 递归
来源：http://dali.chenzaomai.com/Article/details/gtbxsqbgut.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtkqiadjxw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtqlxsaxao.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtksbcufmr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvayqgmv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdpauwzjd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigfzy.top/Article/details/gtoxkpsdpp.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtiolbqutb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.nanxinkj.top/Article/details/gteftzzkqv.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtkppehqbp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenlongwang.top/Article/details/gtqarexirk.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gtjludhfxe.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tian-w.cn/Article/details/gtffwiuayk.html

TS:   同 JS
来源：http://dali.cdnleiting.top/Article/details/gtzprdstvx.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtatnohrcc.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gtnpqyuiry.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtykqywmzw.html

C#:   块级作用域
来源：http://dali.pycfn.com/Article/details/gtpwnybakk.html

[C11] 模块导入与导出
来源：http://dali.iojbl.cn/Article/details/gtnkdwdjqx.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtchbialle.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jqgufenzy.top/Article/details/gthelrytem.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtuwvgwhzf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zhiwuduotai.top/Article/details/gtpikphgpf.html

Java: import java.util.List;
来源：http://dali.316326.xyz/Article/details/gtkavdnpnz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gtpjsfmafu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtvrzzkhww.html

C#:   using System.Text;
来源：http://dali.zhongyouzk.top/Article/details/gtvjjtczyx.html

[C12] 立即执行函数 IIFE
来源：http://dali.havefunace.top/Article/details/gtrglotvfw.html

Py:   (lambda: print("run"))()
来源：http://dali.shzxlz.cn/Article/details/gtfsxvphin.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjuvclxld.html

JS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtzomxldis.html

TS:   (() => { console.log("run"); })();
来源：http://dali.snrcjt.cn/Article/details/gtfqpaehzd.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.daxiang520.top/Article/details/gtjtdtvwxu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yongpay.top/Article/details/gtoblsvcbe.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinqigufen.top/Article/details/gtkuhenzxd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.andypj.xyz/Article/details/gtyihciihg.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtgzqgfakr.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtcrgpivzp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtykmnfgnf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinghuilouyu.cn/Article/details/gtkrdbuzsm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpshojaro.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtaanjobgw.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcgidnkg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.chenlongwang.top/Article/details/gtbutvpivt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.c1oappe.top/Article/details/gtjwvdyyzt.html

[C14] 泛型函数
来源：http://dali.chenzaomai.com/Article/details/gtwqyubfwg.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtvbeliyma.html

PHP:  // 无泛型
来源：http://dali.xuetiantiany.cn/Article/details/gtgqdpebbg.html

JS:   // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtzgnyypky.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.tanke756.top/Article/details/gtcgxamcjt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtefsdciqt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tanke756.top/Article/details/gtsbmnnmwn.html

Ruby: # 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtntgieddv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtscptqeax.html

[C15] 解构 / 展开参数
来源：http://dali.tanke756.top/Article/details/gtuliiundi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aizwys.cn/Article/details/gtxrpkkiln.html

PHP:  [$a, $b] = $pair;
来源：http://dali.quarkkingdee.top/Article/details/gtszdsawyr.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gtgipiyfai.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtmfeacnil.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtjiytmeas.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtwwthqblc.html

Ruby: a, b = pair
来源：http://dali.cheryme.top/Article/details/gtvbwczzez.html

C#:   var (a, b) = pair;
来源：http://dali.c1oappe.top/Article/details/gtzgkwcwes.html

[C16] 函数 / 方法重载
来源：http://dali.shangyingyoupin.top/Article/details/gtndzmngob.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtivglfxou.html

PHP:  // 无重载
来源：http://dali.sxryk.cn/Article/details/gteavvlvpp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtemxbsnqx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtctwkyuei.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gtijvvjzuf.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtnkxheupc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.quarkkingdee.top/Article/details/gtbgvkjjie.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxinkj.top/Article/details/gtlzytpyax.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxokvwdtn.html

D. 数组 / 列表 / 集合
来源：http://dali.aizwys.cn/Article/details/gtucbdgtwr.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtbkojxoqc.html

[D01] 创建数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtytdykxpt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtjzcyycay.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jinqigufen.top/Article/details/gtxlnmyixm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.tianlin.xyz/Article/details/gtbfqlgflz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtvjxesjcf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtlizmnhix.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaqefpkaq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.haohaochexian.top/Article/details/gtrjjbluao.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.hysaishi.cn/Article/details/gtwxlfrcjy.html

[D02] 追加元素到末尾
来源：http://dali.haohaochexian.top/Article/details/gtfvbirzzo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.0kj1m.cn/Article/details/gtijyobxxz.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtruznxndq.html

JS:   arr.push(4);
来源：http://dali.daxiang520.top/Article/details/gtoaavamjc.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gtxrkwgipf.html

Java: list.add(4);
来源：http://dali.yongpay.top/Article/details/gtwmadbjze.html

Go:   arr = append(arr, 4)
来源：http://dali.guannengcc.top/Article/details/gtkpflizgs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.zhengqikj.top/Article/details/gtfiadxgbg.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtflekqdfk.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtjaqetctp.html

Py:   arr.insert(0, 0)
来源：http://dali.jlsjyb.cn/Article/details/gtqokmsfbc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jlsjyb.cn/Article/details/gtzrpykvcs.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yuxming.cn/Article/details/gtnjniivze.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gthslwtxmb.html

Java: list.add(0, 0);
来源：http://dali.zhongyouzk.top/Article/details/gtevfieycp.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.pengpengdd.cyou/Article/details/gterbmsfme.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pengpengdd.cyou/Article/details/gtfdvarclj.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtosguvzqw.html

[D04] 删除元素
来源：http://dali.havefunace.top/Article/details/gttqelzint.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aizwys.cn/Article/details/gtpjqqfadp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtquyknfom.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.gotoacloud.top/Article/details/gtvfnrywpy.html

TS:   arr.splice(0, 1);
来源：http://dali.xziqi.cn/Article/details/gtkimcdbys.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.c1oappe.top/Article/details/gtrcmzyiix.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.shuidangran.top/Article/details/gteqbdjhlc.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtpjqhhctz.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.quarkkingdee.top/Article/details/gtkkblqkpo.html

[D05] 访问与修改元素
来源：http://dali.nanxuanxn.top/Article/details/gtuczihgbx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.kuanghao11.cn/Article/details/gtnrzysqkf.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yvedp.cn/Article/details/gtmrnjgkyt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jinqigufen.top/Article/details/gtzyozgsfc.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hfpthk.cn/Article/details/gthuujocxn.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtvrzeipio.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtcmosgyie.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtjwydkthd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.316326.xyz/Article/details/gtvxyzvhva.html

[D06] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtcedzhxtc.html

Py:   len(arr)
来源：http://dali.pengpengdd.cyou/Article/details/gttimtaxsa.html

PHP:  count($arr);
来源：http://dali.havefunace.top/Article/details/gtbcdgtsko.html

JS:   arr.length
来源：http://dali.sxryk.cn/Article/details/gtnzatjsta.html

TS:   arr.length
来源：http://dali.yj20258.top/Article/details/gtvixtvcvs.html

Java: list.size();
来源：http://dali.nanxinkj.top/Article/details/gtqwieymwh.html

Go:   len(arr)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgngfwlhe.html

Ruby: arr.length; arr.size
来源：http://dali.nwbrower.top/Article/details/gtmjlucwao.html

C#:   list.Count;
来源：http://dali.snrcjt.cn/Article/details/gteigypaio.html

[D07] 切片 / 取子数组
来源：http://dali.vqdsnc.cn/Article/details/gtqiuqjcgi.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.hammf.cn/Article/details/gtwswjgzck.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnqzz.top/Article/details/gtlygndfyy.html

JS:   arr.slice(1, 4);
来源：http://dali.ivvv.top/Article/details/gtyyxovfki.html


<!-- 参考信息 -->