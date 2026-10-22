代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.redwolf501.top/Article/details/gtimpuiwep.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjfyvoei.html

TS:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtahtlhxnt.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gttuazkdkl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.cheryme.top/Article/details/gtcjtgawfz.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yuanzhike.top/Article/details/gtofjyawjh.html

C#:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtoiiqnn.html

[B08] do-while（至少执行一次）
来源：http://dali.hammf.cn/Article/details/gtdecytoeh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangshuangyany.cn/Article/details/gtxufdjssw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtybvlnjdb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboyavinz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtlhonalbv.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtrcgvukic.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoyptwqrc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gticsmtifc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gthlhsjfwk.html

[B09] break 与 continue
来源：http://dali.jqgufenzy.top/Article/details/gtxvczbamj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtxjkbdach.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtwcrdvrad.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxjublkoh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtfdewlgry.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtvgaexhgd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gtojuxxywn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.dianchejie.cn/Article/details/gtbhpmqrhe.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtmureehdo.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gtcghrpgps.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gtanxaysvz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tianlin.xyz/Article/details/gtlrzgpyrm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gthldvknwl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtcztbmvdh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgufenzy.top/Article/details/gtcqsemvgs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdzquuce.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtmdgihezn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guannengcc.top/Article/details/gtjzxfnxbf.html

[B11] 生成数字序列 / 区间
来源：http://dali.shangyingyoupin.top/Article/details/gtesigtmke.html

Py:   list(range(0, 10, 2))
来源：http://dali.jlsjyb.cn/Article/details/gthhhymmxp.html

PHP:  range(0, 10, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtkpbshdxg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gthiyggvqo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtxoknytdy.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtceezrvtm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cqqwz.cn/Article/details/gthgzortkz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtnhxnbudx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtcyjoreev.html

[B12] 跳出多层循环
来源：http://dali.gogol.net.cn/Article/details/gtftcclrxm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shuidangran.top/Article/details/gtdxghmhhq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.bjfxy.top/Article/details/gtbfxbkjzb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtrocbgeii.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtawxmrpuk.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtknhfmwkz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shangyingyoupin.top/Article/details/gtfxlijwfd.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xziqi.cn/Article/details/gtlahiwzdp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.meibo888.top/Article/details/gtnczosbge.html

[B13] 判断是否为数字
来源：http://dali.mhx1999.top/Article/details/gtjyassdag.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtieffxcda.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtkhuntqtf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpucrnuek.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtbmkcagef.html

Java: x instanceof Number
来源：http://dali.yj20258.top/Article/details/gtmorlbehr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cqqwz.cn/Article/details/gtivcuvpmw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtvgnkictd.html

C#:   x is int or double or decimal
来源：http://dali.chenzaomai.com/Article/details/gtlskczolo.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtkfclmzhe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuetiantiany.cn/Article/details/gtoepminip.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fzhhl.top/Article/details/gtorytnafg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtinonmlgh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtlhkomiga.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gthesmztnm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.guannengcc.top/Article/details/gtksdrdrnf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhoulong.xyz/Article/details/gtoqphgxds.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxinkj.top/Article/details/gtxkipbhxp.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtykuxfqjr.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gttbrbzoks.html

PHP:  $a && $b || !$c
来源：http://dali.mhx1999.top/Article/details/gtadfyzmge.html

JS:   a && b || !c
来源：http://dali.chenlongwang.top/Article/details/gtbdapicdm.html

TS:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gtxmqybmlp.html

Java: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtuhbxpgpn.html

Go:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtkrmzyzxt.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtouthoahp.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gteywxgjuj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.quarkkingdee.top/Article/details/gtwaudndsc.html

Py:   if not data: return
来源：http://dali.yongpay.top/Article/details/gtuzkxrdnf.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gtbsrxqnom.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtxrowvyij.html

TS:   if (!data) return;
来源：http://dali.jyoumei.cn/Article/details/gtcyaayrsz.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtsnrkucfn.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtdxqnlgpk.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtdgozlogt.html

C#:   if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gttjoeqmyn.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtjgdlfhlk.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtdhwnrqxq.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gttikanfmm.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrcvsxspa.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtogorwepp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtzryyxoia.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gteqekdwgi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtorulcppq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtinhoakif.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinghuilouyu.cn/Article/details/gttrexhssk.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gtgbhijfyn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtwixnixff.html

[C02] 默认参数
来源：http://dali.cashguo.top/Article/details/gtbxqdsdoa.html

Py:   def greet(name="World"): return name
来源：http://dali.ybcxt.top/Article/details/gtnehxlbhi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtednekbqr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gtazayzgvv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtnvbguqdu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtondsusqq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gthlpglabm.html

Ruby: def greet(name = "World") = name
来源：http://dali.andypj.xyz/Article/details/gtjnwxboox.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yangfankeji.com/Article/details/gtmzuweurj.html

[C03] 可变参数
来源：http://dali.yonumen.top/Article/details/gttbhlkydl.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gtfwmktdhq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gtavvbmnam.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtgrozkjsn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtjfcmokug.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.havefunace.top/Article/details/gtfpepmorn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.guowangkeji.top/Article/details/gtuwfrmaux.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhoulong.xyz/Article/details/gtuiptxrnj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nwbrower.top/Article/details/gtdzhkhznq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yonumen.top/Article/details/gtbwlirgyt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.daria6918.cn/Article/details/gtamszqgue.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtxiwfbkwg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sufxvd.cn/Article/details/gtjwozenfc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xziqi.cn/Article/details/gtvfsaucnp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujocakmp.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtuiiuqrqp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtcdgjhdce.html

C#:   f(a: 1, b: 2)
来源：http://dali.cdnleiting.top/Article/details/gtwbrfsyhc.html

[C05] 返回多个值
来源：http://dali.chenlongwang.top/Article/details/gtxqffsszx.html

Py:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtqwtcinhl.html

PHP:  return [$a, $b];
来源：http://dali.chenzaomai.com/Article/details/gtjybqvugg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtevwaxbhy.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtkplzjjoz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yangfankeji.com/Article/details/gtcancexzu.html

Go:   return a, b
来源：http://dali.316326.xyz/Article/details/gtmzgjwxtz.html

Ruby: return a, b
来源：http://dali.quarkkingdee.top/Article/details/gtsnhrtuzq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.c1oappe.top/Article/details/gteuiqtmgl.html

[C06] 匿名函数 / lambda
来源：http://dali.hywenlv.cn/Article/details/gtiruwtvps.html

Py:   square = lambda x: x * x
来源：http://dali.jianghu66.top/Article/details/gtipxlnktq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gthfzwxitb.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtnevumdjw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtliutcsrm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tanke756.top/Article/details/gtthglyhry.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.kuanghao11.cn/Article/details/gtavqkucmn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.guowangkeji.top/Article/details/gtnujagcvi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.guowangkeji.top/Article/details/gtweeecczp.html

[C07] 把函数作为参数传入
来源：http://dali.yanxiufei.cn/Article/details/gtjzydoomx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.dashuyun.cn/Article/details/gtmmgxxamk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.snrcjt.cn/Article/details/gtshhwbmcv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shangyingyoupin.top/Article/details/gtyofgecsv.html

TS:   arr.map(String)
来源：http://dali.zhongyouzk.top/Article/details/gtmswvhdye.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xylfe.cn/Article/details/gtquwygtll.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtwrmdovnm.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gttnyyyiwh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtpgdeezdg.html

[C08] 闭包
来源：http://dali.aizwys.cn/Article/details/gtnebdcwxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtfhnbyavw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.wangdashe.top/Article/details/gtvrsgnome.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtogidvdqy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtagugibsk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sweek.top/Article/details/gtakskohxv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yonumen.top/Article/details/gtpagmgsea.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nwbrower.top/Article/details/gtyhqvpkyb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtiwpnhhsq.html

[C09] 递归
来源：http://dali.nwbrower.top/Article/details/gtcauxctru.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.andypj.xyz/Article/details/gtyuwwuvrb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xuetiantiany.cn/Article/details/gtcctnrcig.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtricxoouz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gttaiyvocb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gotoacloud.top/Article/details/gtveyysdud.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xziqi.cn/Article/details/gttvzgqmvq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtzsufyuqq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.gogol.net.cn/Article/details/gtlxisticb.html

[C10] 变量作用域
来源：http://dali.hywenlv.cn/Article/details/gtkconibbs.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.c1oappe.top/Article/details/gttpfuhrkn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulhkuwad.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gtaagjkcpj.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gtlekrbnwa.html

Java: 方法内为块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscyejgrr.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhukyinz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gttbwzdvts.html

C#:   块级作用域
来源：http://dali.meibo888.top/Article/details/gtzjlvcode.html

[C11] 模块导入与导出
来源：http://dali.xuetiantiany.cn/Article/details/gtjrtpdnfc.html

Py:   from module import func
来源：http://dali.sxryk.cn/Article/details/gtwwdbjpjo.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pengpengdd.cyou/Article/details/gthtogundo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtimwaibfd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sxryk.cn/Article/details/gtdcbjbzwz.html

Java: import java.util.List;
来源：http://dali.andypj.xyz/Article/details/gttgajauva.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtxcdkhmxv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gtlafpxekl.html

C#:   using System.Text;
来源：http://dali.jiagoushi.top/Article/details/gtcjocuzpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrarcuyyo.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtllruycuu.html

PHP:  (function () { echo "run"; })();
来源：http://dali.vqdsnc.cn/Article/details/gtjxytpwvn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtehdisdlf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtnwsitmww.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gtyhkffsem.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtdxofqrrt.html

Ruby: -> { puts "run" }.call
来源：http://dali.zdqjudy.top/Article/details/gtvbojvksd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtrhhtghfj.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnqzz.top/Article/details/gtmaybvslz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuosdlsyn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtfpqbzhef.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gtpjfolsyp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuqawjlwt.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtnkhdequl.html

Go:   func add(a, b int) int
来源：http://dali.zhoulong.xyz/Article/details/gtkobizqcj.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gtvyamonlu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinqigfzy.top/Article/details/gtswcmmozs.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gtthydbkyz.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenzaomai.com/Article/details/gtvbdpmqpu.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtllbjneqa.html

JS:   // 无泛型
来源：http://dali.meibo888.top/Article/details/gtlrzkcxxl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.c1oappe.top/Article/details/gtdwjlzvvc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xinyue.icu/Article/details/gtfapqgwlo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwkitaws.html

Ruby: # 无泛型
来源：http://dali.meibo888.top/Article/details/gtgygoutli.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtlnvnwpcy.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gtztxkfplp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gthdiqdeon.html

PHP:  [$a, $b] = $pair;
来源：http://dali.mhx1999.top/Article/details/gtwgybtpou.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.9152youxi.cn/Article/details/gtrlfwvxna.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.ybcxt.top/Article/details/gtszouaxku.html

Java: // 无解构
来源：http://dali.jianghu66.top/Article/details/gtaaberlau.html

Go:   // 无解构
来源：http://dali.yuxming.cn/Article/details/gtigcjvhxb.html

Ruby: a, b = pair
来源：http://dali.pycfn.com/Article/details/gtjhuxizvk.html

C#:   var (a, b) = pair;
来源：http://dali.nanxinkj.top/Article/details/gttaoeajoj.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gtppaesmdj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrjncnyfs.html

PHP:  // 无重载
来源：http://dali.zdqjudy.top/Article/details/gtxanxyoty.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhiwuduotai.top/Article/details/gtsxbhtpyh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hfpthk.cn/Article/details/gtyxllvvhk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jiagoushi.top/Article/details/gtahskuluq.html

Go:   // 无重载：用不同函数名
来源：http://dali.yongpay.top/Article/details/gttubdtvgn.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuolcmvdk.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtlsxqcdhb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtamwrpium.html

D. 数组 / 列表 / 集合
来源：http://dali.ydzc1.top/Article/details/gtjcizoaae.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwetlztgh.html

[D01] 创建数组 / 列表
来源：http://dali.yj20258888.top/Article/details/gtvwnpczht.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtrsaqsxzt.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.redwolf501.top/Article/details/gtippmlztx.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtkqmzgofj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.aizwys.cn/Article/details/gthvdtdvmg.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yanxiufei.cn/Article/details/gtgjumkkou.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yongpay.top/Article/details/gtxdjwyaux.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gticpzvpgs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gthmubgekb.html

[D02] 追加元素到末尾
来源：http://dali.shzxlz.cn/Article/details/gtlgdawoyp.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaxuzappb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jlsjyb.cn/Article/details/gtvnxpauhg.html

JS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtvlazrwdh.html

TS:   arr.push(4);
来源：http://dali.zhongyouzk.top/Article/details/gtnqozrrjp.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gtfyswifgk.html

Go:   arr = append(arr, 4)
来源：http://dali.feifeiyinyue.top/Article/details/gtizoesiua.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ybcxt.top/Article/details/gtsihtrbqu.html

C#:   list.Add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjnwxnxd.html

[D03] 在指定位置插入元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwjocgvp.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtuaymrwtu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtmwibmdbb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenlongwang.top/Article/details/gttceaqmic.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.gotoacloud.top/Article/details/gtcukbqpsw.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtnfuwmujw.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcappydc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gogol.net.cn/Article/details/gtfxtoduxk.html

C#:   list.Insert(0, 0);
来源：http://dali.chenjidiqi.icu/Article/details/gtrpkjonyn.html

[D04] 删除元素
来源：http://dali.gaohongyu789.top/Article/details/gtihyvptot.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxylhmku.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zhoulong.xyz/Article/details/gtiptlpuce.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtpoqyjuay.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtqmijcvbf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tianlin.xyz/Article/details/gtqzfgjwar.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.fengsongda.top/Article/details/gtdhzlnlfd.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gaohongyu789.top/Article/details/gtinmrokkl.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtaynzblhs.html

[D05] 访问与修改元素
来源：http://dali.dashuyun.cn/Article/details/gtwsiqnykw.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cashguo.top/Article/details/gtsotfffug.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gtjrodmbpk.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gtcwwgjbjd.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.sufxvd.cn/Article/details/gtjigvkgez.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.fzhhl.top/Article/details/gtkuhzsgrl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zycfv.cn/Article/details/gtcjkbdyca.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sxryk.cn/Article/details/gtabsrivnd.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.sysykeji.top/Article/details/gthngohuzm.html

[D06] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtnkbxwujf.html

Py:   len(arr)
来源：http://dali.jinqigufen.top/Article/details/gthkffuaei.html

PHP:  count($arr);
来源：http://dali.cqqwz.cn/Article/details/gtnclnxtgb.html

JS:   arr.length
来源：http://dali.jqgfzy.top/Article/details/gtxyrmxflw.html

TS:   arr.length
来源：http://dali.yanxiufei.cn/Article/details/gtyldlolbi.html

Java: list.size();
来源：http://dali.cdnleiting.top/Article/details/gthigkvgqa.html

Go:   len(arr)
来源：http://dali.zdqjudy.top/Article/details/gtwayqibro.html

Ruby: arr.length; arr.size
来源：http://dali.jinyuanbaomall.cn/Article/details/gthatyotod.html

C#:   list.Count;
来源：http://dali.chenlongwang.top/Article/details/gtaxzfauya.html

[D07] 切片 / 取子数组
来源：http://dali.jianghu66.top/Article/details/gthepghnzh.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtkgergzjq.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.hnxiangtu.top/Article/details/gtjlupkzha.html

JS:   arr.slice(1, 4);
来源：http://dali.pengpengdd.cyou/Article/details/gtqmdcpwcw.html

TS:   arr.slice(1, 4);
来源：http://dali.jinqigfzy.top/Article/details/gttnjkjmts.html

Java: list.subList(1, 4);
来源：http://dali.zycfv.cn/Article/details/gtoutnrtlo.html

Go:   arr[1:4]
来源：http://dali.yj20258.top/Article/details/gtayliirpk.html

Ruby: arr[1, 3]
来源：http://dali.feifeiyinyue.top/Article/details/gttgwwbgdn.html


<!-- 参考信息 -->