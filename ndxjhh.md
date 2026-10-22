代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.ppjwa.cn/Article/details/gtzkysujto.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtazuedpmo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtppmninbk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtcyuwhxmt.html

Java: do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtunjangxq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gtpttknymz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gtbrppbecl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtxcsthusk.html

[B09] break 与 continue
来源：http://dali.yongpay.top/Article/details/gtkkhktwcc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.chenjidiqi.icu/Article/details/gtcdkskiqa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtwgltpjjr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtukcmofqe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gturopmqda.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjjvcmugi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtuyupyktd.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gtwjbyxdph.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtvjxevcyb.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtndiurcrf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ydzc1.top/Article/details/gtwefmparj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtrtdxsisn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtikevbblv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtaimwbpon.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daria6918.cn/Article/details/gtwrcszhjs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.birdmap.top/Article/details/gtydxzywze.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.iojbl.cn/Article/details/gtknxsakfm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.quarkkingdee.top/Article/details/gtqunwtvfp.html

[B11] 生成数字序列 / 区间
来源：http://dali.ybcxt.top/Article/details/gtkpdydogi.html

Py:   list(range(0, 10, 2))
来源：http://dali.cdnleiting.top/Article/details/gtbueobojw.html

PHP:  range(0, 10, 2);
来源：http://dali.hfpthk.cn/Article/details/gtnygouazf.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.iojbl.cn/Article/details/gtbudasfzp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtitwekjgn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gteylehrif.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gtmcbeziwl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtiokmhdgq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenzaomai.com/Article/details/gtfuryvsha.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtlkotunfy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtqrtzpkqt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuanzhike.top/Article/details/gtrdzbbhlm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbxrswfkg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gtxhchkbaa.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gtgccbijwr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtcljwxerj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqfyudbi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhongyouzk.top/Article/details/gtbhtsecbk.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtgppupjrm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtfjpsalpw.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtuipyptck.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtumfyktfr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fengsongda.top/Article/details/gtwnewlirb.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtzgyhxtec.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwdmxihp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtxkmqofnq.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gtxomowybv.html

[B14] 判断值是否在集合内
来源：http://dali.wangshuangyany.cn/Article/details/gtlmwdbgxn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtmuxzengh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazmwmikz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gttyranayq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tanke756.top/Article/details/gtbnvmixye.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sysykeji.top/Article/details/gtwijlfnbn.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.daria6918.cn/Article/details/gtsdetoqsf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.dashuyun.cn/Article/details/gtaiurjbpu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnwnhuvoo.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtcbrmwtkr.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtdroubpde.html

PHP:  $a && $b || !$c
来源：http://dali.zhengqikj.top/Article/details/gtkkourjwx.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtusfxyfio.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtaarcbonx.html

Java: a && b || !c
来源：http://dali.yj20258.top/Article/details/gtedclifpg.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqmeuqnys.html

Ruby: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gthhlcaaah.html

C#:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtqqjpvnea.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtegrdbcje.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtboeicihe.html

PHP:  if (!$data) { return; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtezhagpau.html

JS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtlhumtiou.html

TS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtirwlljcj.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpvymzena.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsthvkudo.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtpqsvavqe.html

C#:   if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gtgskyktuk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaabygmue.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtbbndrdjv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnuhlzqcq.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtssjzmckz.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gtstixazbu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvyhovade.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtrbsaqjcq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtbdwbteos.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jianghu66.top/Article/details/gtzbqybqic.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gtwsyjoypv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtuwornqhu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtxkmsqsac.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtrszhcqut.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtrgqeglod.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtleccimqa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtkqappcvg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtokghtryv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtfunlfaey.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtfmcrmeby.html

Ruby: def greet(name = "World") = name
来源：http://dali.shzxlz.cn/Article/details/gtkwgvdyxg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtykyrtlzu.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gthyckrqdn.html

Py:   def total(*args): return sum(args)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnyebxqz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xinyue.icu/Article/details/gtilslcjeh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gtmsesinyz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtryjwrces.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guowangkeji.top/Article/details/gtgucdwylf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.feifeiyinyue.top/Article/details/gtlmhyhpcn.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfrxkmjvj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhijiandao.cn/Article/details/gtpsdraxeu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.ybcxt.top/Article/details/gthvmwpagm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtsyabalbw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gtgqimnmpi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigufen.top/Article/details/gtbuuxvzbg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtccrqgzko.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhiwuduotai.top/Article/details/gtajgwkaro.html

Go:   // 无：用配置结构体参数
来源：http://dali.tian-w.cn/Article/details/gtfbbzbomi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtfcnbcohx.html

C#:   f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtwrdbowhj.html

[C05] 返回多个值
来源：http://dali.sweek.top/Article/details/gtlpnjynci.html

Py:   return a, b
来源：http://dali.vqdsnc.cn/Article/details/gtgihhooxn.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtbhczssux.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtwicptoos.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtnudbjjng.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtefxkpznl.html

Go:   return a, b
来源：http://dali.birdmap.top/Article/details/gtscopkjqj.html

Ruby: return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtguhmsbsk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gtgudftmbq.html

[C06] 匿名函数 / lambda
来源：http://dali.gogol.net.cn/Article/details/gtrqtzcsgx.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtjauwilff.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gtbmfgoqtt.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gttsmugwgh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gthuutuhtv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gteobydnwy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqskxugq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ppjwa.cn/Article/details/gtvchiubfd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtkeapujps.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtwdshbhif.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yj20258.top/Article/details/gttrjpdpij.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhiwuduotai.top/Article/details/gtyybfabkg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sweek.top/Article/details/gtxuurtopl.html

TS:   arr.map(String)
来源：http://dali.jianghu66.top/Article/details/gtgrgnohas.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yuanzhike.top/Article/details/gtclhbflnu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ybcxt.top/Article/details/gtymbqbnfg.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gthldfucly.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xuanzx.com/Article/details/gtiinaejtv.html

[C08] 闭包
来源：http://dali.xinyue.icu/Article/details/gtunxpxmsv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtdveckrqt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gtcdnukbqo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ehwqpu.com/Article/details/gtbnhqurqa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtdbabrems.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgufenzy.top/Article/details/gtqptevpob.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtcyokulfg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ydzc1.top/Article/details/gtsgsutvyk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtxuursjmw.html

[C09] 递归
来源：http://dali.hnxiangtu.top/Article/details/gtxilalrlo.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtshkuqkjm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daria6918.cn/Article/details/gtvvduriyx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gthiayhxje.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gttqpbdnbq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtkhwpowof.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cdnleiting.top/Article/details/gtsrmrinex.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yuxming.cn/Article/details/gtvhbstuwi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gotoacloud.top/Article/details/gtuwhcxjan.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtudkzjetb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtrmldaxst.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtqmmwzpsb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xuanzx.com/Article/details/gtjhkxkmwb.html

TS:   同 JS
来源：http://dali.bjfxy.top/Article/details/gtqxijnwai.html

Java: 方法内为块级作用域
来源：http://dali.hnqzz.top/Article/details/gtiiesipsz.html

Go:   花括号块级作用域
来源：http://dali.sysykeji.top/Article/details/gtaukxcora.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigfzy.top/Article/details/gtytmkzxne.html

C#:   块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtygrlgazn.html

[C11] 模块导入与导出
来源：http://dali.hnqzz.top/Article/details/gtzavhvfll.html

Py:   from module import func
来源：http://dali.wangdashe.top/Article/details/gtqpzqvbmo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.iojbl.cn/Article/details/gtsmsmavvr.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xylfe.cn/Article/details/gtmyhquedj.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xinyue.icu/Article/details/gtgmpjxzsz.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gtpqoiofxm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinqigufen.top/Article/details/gtdjkpbnpw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhixingplan.top/Article/details/gtihawkrer.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtekipkfjr.html

[C12] 立即执行函数 IIFE
来源：http://dali.guowangkeji.top/Article/details/gtxgidwhmj.html

Py:   (lambda: print("run"))()
来源：http://dali.mhx1999.top/Article/details/gtujirqdzk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gtjamfomzu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenlongwang.top/Article/details/gtundvvbii.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtkyqbgced.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xuanzx.com/Article/details/gtytcodkve.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.havefunace.top/Article/details/gtnobxqpqs.html

Ruby: -> { puts "run" }.call
来源：http://dali.daxiang520.top/Article/details/gtlireazun.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zhixingplan.top/Article/details/gtsdjquqyf.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gtjfaozmpf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtwaiiinds.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxfcghxbd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ehwqpu.com/Article/details/gtjwgrdgui.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtcxpmdxug.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtymqnxwuu.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzwxqwwxj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtmztzkemo.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtqndiwkgr.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbyiciqdj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.pengpengdd.cyou/Article/details/gtnlnowqmw.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gthqysoopi.html

JS:   // 无泛型
来源：http://dali.aizwys.cn/Article/details/gtcmprkgkb.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shzxlz.cn/Article/details/gtouztkuuz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.tian-w.cn/Article/details/gtxpitouxj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtguwwlcgu.html

Ruby: # 无泛型
来源：http://dali.aibaodan.cn/Article/details/gtqmzbmcar.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj202588.top/Article/details/gtxpqkeuqb.html

[C15] 解构 / 展开参数
来源：http://dali.yanxiufei.cn/Article/details/gthhjfiewm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.nwbrower.top/Article/details/gtehpbomrw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gtkrqjhckq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.haohaochexian.top/Article/details/gtesawshkd.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yuxming.cn/Article/details/gtzxvodiir.html

Java: // 无解构
来源：http://dali.wangshuangyany.cn/Article/details/gtnrlarqiu.html

Go:   // 无解构
来源：http://dali.daxiang520.top/Article/details/gtfvojrfmk.html

Ruby: a, b = pair
来源：http://dali.hysaishi.cn/Article/details/gtmilepdtk.html

C#:   var (a, b) = pair;
来源：http://dali.316326.xyz/Article/details/gtnyaoyskc.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtkvgutcio.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.quarkkingdee.top/Article/details/gtzsaktbcn.html

PHP:  // 无重载
来源：http://dali.zhoulong.xyz/Article/details/gtrdfvkbfp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.dashuyun.cn/Article/details/gtbqomtoww.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.jiagoushi.top/Article/details/gtcypjlpfr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gthncejtfd.html

Go:   // 无重载：用不同函数名
来源：http://dali.sufxvd.cn/Article/details/gtqrudehfs.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hongshengwenyu.top/Article/details/gtxvwarenu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtdivwtfqk.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtftihqvky.html

D. 数组 / 列表 / 集合
来源：http://dali.jinqigufen.top/Article/details/gtqtebcrji.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtobwkrtww.html

[D01] 创建数组 / 列表
来源：http://dali.fengsongda.top/Article/details/gtmvwswskb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtenyistcq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.zycfv.cn/Article/details/gtifnucrij.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ydzc1.top/Article/details/gtbkkgfezw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.iojbl.cn/Article/details/gtuemfdrgc.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.jinqigfzy.top/Article/details/gtgazukpoq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.zhongyouzk.top/Article/details/gturlhpqao.html

Ruby: arr = [1, 2, 3]
来源：http://dali.ivvv.top/Article/details/gtkkmgpsgr.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aizwys.cn/Article/details/gtsusxigiz.html

[D02] 追加元素到末尾
来源：http://dali.tanke756.top/Article/details/gtjdmlpvlj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shzxlz.cn/Article/details/gtxongcdnb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtarziarnq.html

JS:   arr.push(4);
来源：http://dali.yj20258888.top/Article/details/gtsdmasyku.html

TS:   arr.push(4);
来源：http://dali.meibo888.top/Article/details/gtdpftkjty.html

Java: list.add(4);
来源：http://dali.gotoacloud.top/Article/details/gtvmgyasqr.html

Go:   arr = append(arr, 4)
来源：http://dali.yj20258888.top/Article/details/gtefnacqmd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwyqirbd.html

C#:   list.Add(4);
来源：http://dali.jianghu66.top/Article/details/gtoedksyab.html

[D03] 在指定位置插入元素
来源：http://dali.mhx1999.top/Article/details/gtarduotqr.html

Py:   arr.insert(0, 0)
来源：http://dali.hfpthk.cn/Article/details/gtxxuucuhe.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhongyouzk.top/Article/details/gtbkuxgoyz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtwaaawzga.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtqrgbwgpv.html

Java: list.add(0, 0);
来源：http://dali.aizwys.cn/Article/details/gtazxogjga.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.shzxlz.cn/Article/details/gtahzxswdo.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtwegwvrfg.html

C#:   list.Insert(0, 0);
来源：http://dali.gogol.net.cn/Article/details/gtwygauvzy.html

[D04] 删除元素
来源：http://dali.haohaochexian.top/Article/details/gtetmtioyw.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gtrgvrarcp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtfhzbtjsk.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yuxming.cn/Article/details/gtzizbpqur.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtdfjfskuh.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgufenzy.top/Article/details/gtojypktta.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.dashuyun.cn/Article/details/gtkqhvhhej.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.ppjwa.cn/Article/details/gtgufdmgpv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sxryk.cn/Article/details/gtelivgolv.html

[D05] 访问与修改元素
来源：http://dali.nwbrower.top/Article/details/gtgckmskcx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaoibixt.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtdyfkydmx.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtvryjauzw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cashguo.top/Article/details/gtutbuayou.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtazqkxtuf.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gtbnmgkqvf.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.feifeiyinyue.top/Article/details/gtqkpngzmx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtlmlbhhio.html

[D06] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtttgiuohp.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gtfepnlldn.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtgyejuxny.html

JS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gtfqnydrfm.html

TS:   arr.length
来源：http://dali.9152youxi.cn/Article/details/gttvfvkhwj.html

Java: list.size();
来源：http://dali.havefunace.top/Article/details/gtrktuncmw.html

Go:   len(arr)
来源：http://dali.dashuyun.cn/Article/details/gtognjqsyv.html

Ruby: arr.length; arr.size
来源：http://dali.gotoacloud.top/Article/details/gtqdlbtiuu.html

C#:   list.Count;
来源：http://dali.xuanzx.com/Article/details/gtsornyzxd.html

[D07] 切片 / 取子数组
来源：http://dali.wangshuangyany.cn/Article/details/gtrxnmdipp.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.zycfv.cn/Article/details/gturdlzpfl.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtilaacvbh.html

JS:   arr.slice(1, 4);
来源：http://dali.sxryk.cn/Article/details/gtnhvslqrl.html

TS:   arr.slice(1, 4);
来源：http://dali.jqgufenzy.top/Article/details/gttgnemnob.html

Java: list.subList(1, 4);
来源：http://dali.tanke756.top/Article/details/gtpnvskwzx.html

Go:   arr[1:4]
来源：http://dali.yuxming.cn/Article/details/gtcgxaewab.html

Ruby: arr[1, 3]
来源：http://dali.hammf.cn/Article/details/gtcvdyutqb.html

C#:   list.GetRange(1, 3);
来源：http://dali.nanxuanxn.top/Article/details/gtwqcyonee.html

[D08] 合并两个数组
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlpcrgcr.html

Py:   a + b;  a.extend(b)
来源：http://dali.0kj1m.cn/Article/details/gtqomvwdmn.html

PHP:  array_merge($a, $b);
来源：http://dali.xziqi.cn/Article/details/gtocrzanbn.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.yuanzhike.top/Article/details/gtnbhgrcyj.html

TS:   [...a, ...b];
来源：http://dali.cdnleiting.top/Article/details/gtxufqakgt.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.zhongyouzk.top/Article/details/gtkflyqkbo.html

Go:   append(a, b...)
来源：http://dali.hnqzz.top/Article/details/gtxyemqzet.html


<!-- 参考信息 -->