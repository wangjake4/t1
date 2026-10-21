代发 wailian999

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dianchejie.cn/Article/details/gtqwpchvif.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtfjvgupou.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtcfkkiuud.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtohmdyler.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtjpflimep.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cucudq.cn/Article/details/gtktulzqjl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shangyingyoupin.top/Article/details/gteatmozmm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtxwvrwfro.html

Java: do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtorfwgxhn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.daria6918.cn/Article/details/gtwlqcuaqp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtqxvjkcus.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtquqbikhx.html

[B09] break 与 continue
来源：http://dali.zycfv.cn/Article/details/gtahbyahgj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zycfv.cn/Article/details/gtwkgonopv.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gthmyqgslu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtfwqareyn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtpdgzmvad.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtrqloxzqi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtdkfctfgn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtsexfbecc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtpjajwxcx.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gtehxhnoul.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shuidangran.top/Article/details/gtitfgfxhi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gtndqkzorl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtroryoabi.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtgstafrby.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pengpengdd.cyou/Article/details/gtvdttcboc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkarzeakd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkprbucr.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtypygiydz.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyqxpvlx.html

Py:   list(range(0, 10, 2))
来源：http://dali.haohaochexian.top/Article/details/gtcrwekvbp.html

PHP:  range(0, 10, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtczrladii.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zdqjudy.top/Article/details/gtcsnibzfy.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sysykeji.top/Article/details/gtxtuiqjqr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigfzy.top/Article/details/gtcuzgjjnz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gtbspidwgz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtgmnigdgn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gtxojafubp.html

[B12] 跳出多层循环
来源：http://dali.redwolf501.top/Article/details/gtcqfadubo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtxdfftyck.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gtgygelcdi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtfmgbbulx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtxeyopfso.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtxkfsnjsr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtqymfaoob.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtbxjppcyy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhoulong.xyz/Article/details/gteeqkmilb.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtbzgvbueb.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtoragaklm.html

PHP:  is_numeric($x)
来源：http://dali.tanke756.top/Article/details/gtaatgoppm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.vqdsnc.cn/Article/details/gtbrzxuvqn.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.c1oappe.top/Article/details/gtvowojztr.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtxqrlfavb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhengqikj.top/Article/details/gtftaqoxzc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.haohaochexian.top/Article/details/gtflaawlfz.html

C#:   x is int or double or decimal
来源：http://dali.hywenlv.cn/Article/details/gtotdcdmwz.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtyanzbtvx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinqigufen.top/Article/details/gtghuvcbez.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtmvijyrek.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gotoacloud.top/Article/details/gttebmjokx.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtkrltjngb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtbbhhvcni.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtszjtioqo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtuxdojpzl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgraktyrm.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtrpyipsgt.html

Py:   a and b or not c
来源：http://dali.jiagoushi.top/Article/details/gtyobbiqur.html

PHP:  $a && $b || !$c
来源：http://dali.0kj1m.cn/Article/details/gtcfilbofc.html

JS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtqueuefcr.html

TS:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtrgfbppad.html

Java: a && b || !c
来源：http://dali.yongpay.top/Article/details/gthjiudlrp.html

Go:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtgfhuevmy.html

Ruby: a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtlsixftwt.html

C#:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtxfyzpbsz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.iojbl.cn/Article/details/gtqscimklu.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtrwyqktcz.html

PHP:  if (!$data) { return; }
来源：http://dali.daria6918.cn/Article/details/gtuyajkgke.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtrsvycvrp.html

TS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtbusbsqty.html

Java: if (data == null) return;
来源：http://dali.yueranfly.top/Article/details/gtzffprsnp.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtouqobbju.html

Ruby: return if data.nil?
来源：http://dali.sysykeji.top/Article/details/gtyahhsaum.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtviarswzt.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtaxgciehe.html

C. 函数与作用域
来源：http://dali.jlsjyb.cn/Article/details/gttkcgxcgc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsfokgkwh.html

[C01] 定义函数
来源：http://dali.yj20258888.top/Article/details/gtwsntbiqh.html

Py:   def add(a, b): return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtpozpapss.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjojrieiu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtdymeqrin.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtcxtfpfgh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtjrzwifka.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ydzc1.top/Article/details/gtwdzvjpov.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tanke756.top/Article/details/gtycgzqjlr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmwgtxar.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtjqetmhzs.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtbtslnamz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cucudq.cn/Article/details/gtafkqyfuy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtgudhyvpx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtnhpibskt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtrkssyxno.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghghvwav.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhengqikj.top/Article/details/gtwypgoffv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtotrwrxgw.html

[C03] 可变参数
来源：http://dali.xziqi.cn/Article/details/gtpjvvnjwv.html

Py:   def total(*args): return sum(args)
来源：http://dali.9152youxi.cn/Article/details/gtaskipprd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcwnnnbip.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqriqahd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtupsdxopa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.0kj1m.cn/Article/details/gtfhdkmuus.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nanxuanxn.top/Article/details/gtsqlfeiaj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtkibuiizm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtugmocmrz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtmhknfzwi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtdmxolnpz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gtfrzprvgh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtuqthkgsk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hfpthk.cn/Article/details/gtvukqokai.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtdiqptqck.html

Go:   // 无：用配置结构体参数
来源：http://dali.9152youxi.cn/Article/details/gtaiydofwb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtqimmodpm.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gtcfphhhsb.html

[C05] 返回多个值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqdxuxpj.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtvxpwobwi.html

PHP:  return [$a, $b];
来源：http://dali.guannengcc.top/Article/details/gtjclowyas.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.snrcjt.cn/Article/details/gtcvpzrwdy.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtdlnzkzga.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gtqlfprche.html

Go:   return a, b
来源：http://dali.wangdashe.top/Article/details/gtswfqcjub.html

Ruby: return a, b
来源：http://dali.haohaochexian.top/Article/details/gthqrhcblh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cheryme.top/Article/details/gtcurygjnp.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtpbmbqnht.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gtcentpaab.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yuxming.cn/Article/details/gtktjesyhk.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtkpebtmoz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtzpbejbca.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtwempexaf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.cdnleiting.top/Article/details/gtzjiixwqd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtohqgndto.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.smart0.xyz/Article/details/gtxdzaierj.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtkbjdedoo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.ehwqpu.com/Article/details/gtibcatzsr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtcjxvbtbb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.cheryme.top/Article/details/gtsszbuzas.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtpxjsfbin.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtplsoxhkw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.cheryme.top/Article/details/gtxyfkamai.html

Ruby: arr.map(&:upcase)
来源：http://dali.shzxlz.cn/Article/details/gthhfkxfoc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.nanxinkj.top/Article/details/gtxuhmqdnu.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gtaqlrqgym.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtgzebztet.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gthiukwrcs.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.dianchejie.cn/Article/details/gthgnelovq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.guannengcc.top/Article/details/gtpkbswaoq.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtpibpnuio.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hammf.cn/Article/details/gtozitqcfz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gtplfgouvk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangdashe.top/Article/details/gtspyjxiyo.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtxocrygsn.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cdnleiting.top/Article/details/gtcavqmyny.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yj202588.top/Article/details/gtacgcynic.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.smart0.xyz/Article/details/gtpsrqoetz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yonumen.top/Article/details/gtqedgrfsq.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtcfacbksa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cashguo.top/Article/details/gtpcmqtuve.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gtpfrwnsvg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtlhyqvutl.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtyaswiaxu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtnklcsfxb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtnqzqyjma.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtrzocnsoy.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtgdqbxxjp.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtvesxycdi.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtnjniwddm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hongshengwenyu.top/Article/details/gtjfputpfg.html

C#:   块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtksrzxtkw.html

[C11] 模块导入与导出
来源：http://dali.zdqjudy.top/Article/details/gtuicsxwyb.html

Py:   from module import func
来源：http://dali.jyoumei.cn/Article/details/gtzfoiiqgk.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtruirrfdj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtplsfvyzv.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sweek.top/Article/details/gtyqoaiien.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphyzfdoo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.9152youxi.cn/Article/details/gtceykmghn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtjecdsbjb.html

C#:   using System.Text;
来源：http://dali.cucudq.cn/Article/details/gtknfydftf.html

[C12] 立即执行函数 IIFE
来源：http://dali.mhx1999.top/Article/details/gtxgqxbfsw.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtsjwfxnuf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.guannengcc.top/Article/details/gtujcqltdi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gthkjbhfue.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shangyingyoupin.top/Article/details/gtmrtxrhyy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jqgufenzy.top/Article/details/gtwsrofebm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtchnnluyk.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtvnoazvcc.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.zdqjudy.top/Article/details/gtsabjjrqo.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj202588.top/Article/details/gtnxxaxfqf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtzptlvgmw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtfxfjuajc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ivvv.top/Article/details/gtcunimysp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtvegmbwqi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtixqseqhg.html

Go:   func add(a, b int) int
来源：http://dali.zhijiandao.cn/Article/details/gtherjgsia.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xinyue.icu/Article/details/gtnapyyjsq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yueranfly.top/Article/details/gtnwdknyev.html

[C14] 泛型函数
来源：http://dali.jyoumei.cn/Article/details/gthlvoiflr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtscslkphh.html

PHP:  // 无泛型
来源：http://dali.dashuyun.cn/Article/details/gtuoctemst.html

JS:   // 无泛型
来源：http://dali.yj20258.top/Article/details/gtlitzvijr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jyoumei.cn/Article/details/gtywhljsyv.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.fzhhl.top/Article/details/gtoclkypsi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhoulong.xyz/Article/details/gtvfjilohf.html

Ruby: # 无泛型
来源：http://dali.dianchejie.cn/Article/details/gtiegxssrt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gtmjpuzbld.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtmkfbhmzi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shanyushiyangtech.top/Article/details/gtytszelcd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtoxgsfdru.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yvedp.cn/Article/details/gtuttgapsl.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtekfemlil.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gtrgzbjnzq.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtqhadfdnn.html

Ruby: a, b = pair
来源：http://dali.xuetiantiany.cn/Article/details/gtuobzqqfc.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gtmcjmvmxj.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigufen.top/Article/details/gtlqorhipr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gaohongyu789.top/Article/details/gtfkshuokk.html

PHP:  // 无重载
来源：http://dali.yongpay.top/Article/details/gtyrssrapw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sweek.top/Article/details/gtwnufnpnx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuanzx.com/Article/details/gttuhergxb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.tanke756.top/Article/details/gtjrjlrogj.html

Go:   // 无重载：用不同函数名
来源：http://dali.ehwqpu.com/Article/details/gtashmiuyf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.dashuyun.cn/Article/details/gtjqusbbwz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtvidquxrx.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtoybberbv.html

D. 数组 / 列表 / 集合
来源：http://dali.jianghu66.top/Article/details/gtdlmzlgwo.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtlcgzvurf.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtwqmlvvsc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhijiandao.cn/Article/details/gtdzcwnzot.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.dashuyun.cn/Article/details/gtsgmhwdqh.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jinyuanbaomall.cn/Article/details/gtenjnewnq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yuanzhike.top/Article/details/gtmdgkthgb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdvcirhy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.havefunace.top/Article/details/gtmfzjwmum.html

Ruby: arr = [1, 2, 3]
来源：http://dali.c1oappe.top/Article/details/gtkqsvmotl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenzaomai.com/Article/details/gtgxyxpmft.html

[D02] 追加元素到末尾
来源：http://dali.daxiang520.top/Article/details/gtndyohhgs.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.mhx1999.top/Article/details/gtglmukvid.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinqigfzy.top/Article/details/gtrjbrdcmu.html

JS:   arr.push(4);
来源：http://dali.pycfn.com/Article/details/gtxcjyfxki.html

TS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtdekorfsn.html

Java: list.add(4);
来源：http://dali.yuanzhike.top/Article/details/gtvyvjelgy.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gthptyrcnj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sysykeji.top/Article/details/gtanyytetv.html

C#:   list.Add(4);
来源：http://dali.ppjwa.cn/Article/details/gtxbywojww.html

[D03] 在指定位置插入元素
来源：http://dali.havefunace.top/Article/details/gtrehqvgyl.html

Py:   arr.insert(0, 0)
来源：http://dali.zhixingplan.top/Article/details/gtmgcoubxr.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.birdmap.top/Article/details/gtpatjekmk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.mhx1999.top/Article/details/gtrmwsrrbb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtdeygittb.html

Java: list.add(0, 0);
来源：http://dali.pengpengdd.cyou/Article/details/gtptykaqth.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tanke756.top/Article/details/gteywxsbgy.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shzxlz.cn/Article/details/gtuxpcbfyr.html

C#:   list.Insert(0, 0);
来源：http://dali.fzhhl.top/Article/details/gtlkbwygbt.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtkufdgjbz.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.cucudq.cn/Article/details/gtzhdmfycn.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hammf.cn/Article/details/gtnfgqysyb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.feifeiyinyue.top/Article/details/gtrlceavlv.html

TS:   arr.splice(0, 1);
来源：http://dali.svipenyu.cn/Article/details/gtatcwlxjf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtdprufuzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.ybcxt.top/Article/details/gttemanply.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gtnstxhecm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhoulong.xyz/Article/details/gttukdecua.html

[D05] 访问与修改元素
来源：http://dali.yj202588.top/Article/details/gtsevgaloe.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yuxming.cn/Article/details/gtpzknxvvk.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.snrcjt.cn/Article/details/gtbrzllaqa.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zycfv.cn/Article/details/gtglukbnev.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.birdmap.top/Article/details/gtmuejwgnp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjnjpoapv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.haohaochexian.top/Article/details/gtqfriveot.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.xylfe.cn/Article/details/gtxsoskcew.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.chenjidiqi.icu/Article/details/gteqtwsptv.html

[D06] 数组长度
来源：http://dali.gotoacloud.top/Article/details/gtewayghck.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gtlpxtoqps.html

PHP:  count($arr);
来源：http://dali.fzhhl.top/Article/details/gtrgdvmdtv.html

JS:   arr.length
来源：http://dali.yueranfly.top/Article/details/gtycqldfao.html

TS:   arr.length
来源：http://dali.gaohongyu789.top/Article/details/gtmjpxhmjp.html

Java: list.size();
来源：http://dali.xinyue.icu/Article/details/gtulmwapcd.html

Go:   len(arr)
来源：http://dali.pycfn.com/Article/details/gtmwomgzci.html

Ruby: arr.length; arr.size
来源：http://dali.zycfv.cn/Article/details/gtbcvngvum.html

C#:   list.Count;
来源：http://dali.gotoacloud.top/Article/details/gtztqistzs.html

[D07] 切片 / 取子数组
来源：http://dali.0kj1m.cn/Article/details/gtcttcqoyn.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.aibaodan.cn/Article/details/gtxodarsek.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.mhx1999.top/Article/details/gtlcquoaiy.html

JS:   arr.slice(1, 4);
来源：http://dali.gaohongyu789.top/Article/details/gtxmurylbh.html

TS:   arr.slice(1, 4);
来源：http://dali.zhoulong.xyz/Article/details/gthosokmri.html

Java: list.subList(1, 4);
来源：http://dali.chenlongwang.top/Article/details/gtgprkrhqb.html

Go:   arr[1:4]
来源：http://dali.hfpthk.cn/Article/details/gtqyvlpibr.html

Ruby: arr[1, 3]
来源：http://dali.bjfxy.top/Article/details/gtpnuarjiq.html

C#:   list.GetRange(1, 3);
来源：http://dali.jiagoushi.top/Article/details/gtwsmmhdey.html

[D08] 合并两个数组
来源：http://dali.yanxiufei.cn/Article/details/gtqjppyftb.html

Py:   a + b;  a.extend(b)
来源：http://dali.birdmap.top/Article/details/gtuhftvsxe.html

PHP:  array_merge($a, $b);
来源：http://dali.smart0.xyz/Article/details/gtcgrdnjst.html


<!-- 参考信息 -->