代发 wailian999

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangtech.top/Article/details/gtghdltenp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtekmngmxt.html

JS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gthdnqltqf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtfivkzpgc.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtshhopxsw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zycfv.cn/Article/details/gtrwndjtlz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daria6918.cn/Article/details/gtlixpuikb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtjapgzveo.html

[B09] break 与 continue
来源：http://dali.birdmap.top/Article/details/gtexbrqjwd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gtitpxosje.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtbemcqenm.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyxrxcpx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gtyjzutalt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtyywbiwds.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtcwlykhka.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gtkxagivpn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtvihddhlv.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtinpkgsuh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jianghu66.top/Article/details/gtfohenvuu.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtpcmydxto.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yueranfly.top/Article/details/gtnatqnsku.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gtqxkkvghz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtjiilpmrq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gteticrpnk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.aizwys.cn/Article/details/gtdwcducbv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtwoxxxiyi.html

[B11] 生成数字序列 / 区间
来源：http://dali.shuidangran.top/Article/details/gttinfhhjo.html

Py:   list(range(0, 10, 2))
来源：http://dali.dianchejie.cn/Article/details/gtdlytpgqh.html

PHP:  range(0, 10, 2);
来源：http://dali.aibaodan.cn/Article/details/gthnngduqb.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtkbvwdqre.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdnavepe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhongyouzk.top/Article/details/gtmjsglcck.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtkbvagkjp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtuapqbvnc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtomyteshh.html

[B12] 跳出多层循环
来源：http://dali.xziqi.cn/Article/details/gtpuvuegwu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtagsvoqci.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbflxijr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.vqdsnc.cn/Article/details/gtofqloyko.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtchcbwmyl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtkktngnvz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhixingplan.top/Article/details/gtswgsukcw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gttfyhqnku.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ydzc1.top/Article/details/gtnvtmbxcw.html

[B13] 判断是否为数字
来源：http://dali.sysykeji.top/Article/details/gttvtyexnb.html

Py:   isinstance(x, (int, float))
来源：http://dali.gogol.net.cn/Article/details/gthmycgxuw.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtvefjlqqw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtvlzpmamc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtbcijfmfw.html

Java: x instanceof Number
来源：http://dali.yj20258888.top/Article/details/gthjaivvtl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbotvnfbk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtrhmmzzig.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtfgvnwcmf.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtfidyjnkl.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yueranfly.top/Article/details/gtnfsnfeys.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtshemoqgs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gttqrcozxs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gttzmzbuvl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gturqknrin.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cqqwz.cn/Article/details/gtyzfjofsv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtwoizeeao.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtbwwkesfp.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtzrwqhnzt.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gtpafjemki.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtgecffvuw.html

JS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtmfhutfiz.html

TS:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtzohysvrn.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtkbkcdzlv.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gttuoylfvh.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtciirkeuv.html

C#:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtzathztng.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuanzhike.top/Article/details/gtogdopjjn.html

Py:   if not data: return
来源：http://dali.meibo888.top/Article/details/gthfejclnk.html

PHP:  if (!$data) { return; }
来源：http://dali.nanxinkj.top/Article/details/gtdiymkpjp.html

JS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gtyhsdfeim.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtifitewrl.html

Java: if (data == null) return;
来源：http://dali.chenzaomai.com/Article/details/gttwzgzvcg.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtdvszkhor.html

Ruby: return if data.nil?
来源：http://dali.yj20258.top/Article/details/gtajzbelmq.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtgozlheem.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtvzdbomxy.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gtjrnttahc.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtslxqndjp.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtmpxcgcje.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gtrxpxkeir.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtfqkvadsd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sxryk.cn/Article/details/gtjsyopxjk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtrmshlwjf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtakivoiye.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtpkiexzas.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gtftgwpgul.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtvfbhevsx.html

[C02] 默认参数
来源：http://dali.hysaishi.cn/Article/details/gtxiuczbjy.html

Py:   def greet(name="World"): return name
来源：http://dali.fzhhl.top/Article/details/gtxqaultwt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwochdowy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtavbffqph.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtvvzjeeop.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gtbddbzpfx.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shzxlz.cn/Article/details/gtqhhhtllr.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtfbgdcehp.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gtzgcictgk.html

[C03] 可变参数
来源：http://dali.kuanghao11.cn/Article/details/gtbgcrbcfx.html

Py:   def total(*args): return sum(args)
来源：http://dali.svipenyu.cn/Article/details/gtgjrbkulp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gtfhhnufpv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gttiyjvqpm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtsxjwvcdb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvfzicae.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtlfyzwkbz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtnasdbqgt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtzikldmts.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtmgjfwitc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nwbrower.top/Article/details/gtorzjqoxf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtuetijrwc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.mhx1999.top/Article/details/gtwkkljfrw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcugojce.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.vqdsnc.cn/Article/details/gtendctwtc.html

Go:   // 无：用配置结构体参数
来源：http://dali.daxiang520.top/Article/details/gtcywdwcse.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtfnoxumgc.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtdtfxyxhu.html

[C05] 返回多个值
来源：http://dali.yangfankeji.com/Article/details/gtptbvipml.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtgjjywdve.html

PHP:  return [$a, $b];
来源：http://dali.nanxinkj.top/Article/details/gtmvnpuzsz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.birdmap.top/Article/details/gtywwbkmhf.html

TS:   return { a, b };
来源：http://dali.smart0.xyz/Article/details/gttacbsdcr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gtiyzvnjrf.html

Go:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhkiiimr.html

Ruby: return a, b
来源：http://dali.mhx1999.top/Article/details/gttjsgnsrc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtqlvlwjzu.html

[C06] 匿名函数 / lambda
来源：http://dali.ivvv.top/Article/details/gtzwjgegkk.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtkowtqlhc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtgwfdxhzo.html

JS:   const square = x => x * x;
来源：http://dali.jqgfzy.top/Article/details/gtrrjsutim.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtlygmlyiz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gtydejvhyh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jyoumei.cn/Article/details/gtpklrknlh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gthmbdjlbm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuanzx.com/Article/details/gtazzvtprz.html

[C07] 把函数作为参数传入
来源：http://dali.xylfe.cn/Article/details/gttugqlsrs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gogol.net.cn/Article/details/gtnnuvygvs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.tanke756.top/Article/details/gtprzinkmk.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtxhuzmbzs.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtaakjfbhl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ivvv.top/Article/details/gtcrhawvzi.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gtvxwoekqd.html

Ruby: arr.map(&:upcase)
来源：http://dali.pycfn.com/Article/details/gtslmmzadf.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gtbpkomecw.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtqeawouyv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.birdmap.top/Article/details/gtlzfsehqb.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zycfv.cn/Article/details/gtnuewhhlh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.316326.xyz/Article/details/gtolzbccmr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gtedtaigev.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtnilyezac.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtguzohtcc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dashuyun.cn/Article/details/gtuakfjbjm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtcxrancpv.html

[C09] 递归
来源：http://dali.9152youxi.cn/Article/details/gtiusiifdi.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.aibaodan.cn/Article/details/gtqoasunld.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtqoenvheb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtjzcdovfw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhixingplan.top/Article/details/gtpwulpina.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgfzy.top/Article/details/gtuabzvapu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gtmpcdmayu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtpfmqpmyq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yongpay.top/Article/details/gtlgeptnfv.html

[C10] 变量作用域
来源：http://dali.sysykeji.top/Article/details/gtrfcnrwax.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtmgyyacch.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yueranfly.top/Article/details/gtnenmgrhy.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gtdrjzawhw.html

TS:   同 JS
来源：http://dali.iojbl.cn/Article/details/gtpjcpqpvw.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnwtmpfe.html

Go:   花括号块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtbycoxffl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hnxiangtu.top/Article/details/gtmnfogyfn.html

C#:   块级作用域
来源：http://dali.zhengqikj.top/Article/details/gttjofpjqi.html

[C11] 模块导入与导出
来源：http://dali.sysykeji.top/Article/details/gtlvnavfcu.html

Py:   from module import func
来源：http://dali.hfpthk.cn/Article/details/gtvonyjttt.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinqigufen.top/Article/details/gtfjsjunwj.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhongyouzk.top/Article/details/gtfstfbrdx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gteekhuguk.html

Java: import java.util.List;
来源：http://dali.jqgfzy.top/Article/details/gtidzfzmiu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtpgcfihhk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtipipbffj.html

C#:   using System.Text;
来源：http://dali.aizwys.cn/Article/details/gthmshwgwk.html

[C12] 立即执行函数 IIFE
来源：http://dali.tianlin.xyz/Article/details/gtvecurrwb.html

Py:   (lambda: print("run"))()
来源：http://dali.hfpthk.cn/Article/details/gtfhrsrjpb.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jlsjyb.cn/Article/details/gtcyceefpv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigfzy.top/Article/details/gtrimowkwo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hywenlv.cn/Article/details/gtlmorgnyw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.dianchejie.cn/Article/details/gtztzhscvd.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gtmqomyfik.html

Ruby: -> { puts "run" }.call
来源：http://dali.cqqwz.cn/Article/details/gtslybgmuw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.mhx1999.top/Article/details/gtfstdxszy.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtjlnkysal.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hongshengwenyu.top/Article/details/gtfbrkwukp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtdmnfczyg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jiagoushi.top/Article/details/gtlkrzzhqu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtzzdrhrto.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtdiozeqft.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtjorkuxfs.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gtovmwwehl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtwtbabftq.html

[C14] 泛型函数
来源：http://dali.nanxinkj.top/Article/details/gtlpfsmjqj.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.hnxiangtu.top/Article/details/gtntqxecxo.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtqrqbnxko.html

JS:   // 无泛型
来源：http://dali.gzhubu.top/Article/details/gtnsgefzwc.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenzaomai.com/Article/details/gtksnulihn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtkzqdlrmf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtlopkzyyb.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gtzucwqnay.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.0kj1m.cn/Article/details/gtnvmqhvte.html

[C15] 解构 / 展开参数
来源：http://dali.zhongyouzk.top/Article/details/gtcamdzypp.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sweek.top/Article/details/gthccacgvx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.cheryme.top/Article/details/gtpmokkzml.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yanxiufei.cn/Article/details/gttcispkgj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hnqzz.top/Article/details/gtqoafqhrv.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gtfjpxxium.html

Go:   // 无解构
来源：http://dali.shzxlz.cn/Article/details/gtuxgrqskf.html

Ruby: a, b = pair
来源：http://dali.yanxiufei.cn/Article/details/gtkzcmmqty.html

C#:   var (a, b) = pair;
来源：http://dali.zycfv.cn/Article/details/gtmwrhtgjk.html

[C16] 函数 / 方法重载
来源：http://dali.snrcjt.cn/Article/details/gtutebtgku.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gtqxnqzkmg.html

PHP:  // 无重载
来源：http://dali.smart0.xyz/Article/details/gtfqftgjbe.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hammf.cn/Article/details/gtihtchkbd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yangfankeji.com/Article/details/gtrwpwuxnv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.pycfn.com/Article/details/gtepkxeaip.html

Go:   // 无重载：用不同函数名
来源：http://dali.yuxming.cn/Article/details/gtsgymjfdl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.xziqi.cn/Article/details/gtwbigeoor.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.daria6918.cn/Article/details/gtjcxqffow.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtebuxubmk.html

D. 数组 / 列表 / 集合
来源：http://dali.shangyingyoupin.top/Article/details/gtjrsqlljp.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtqskbsgdc.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtezeouogt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gtgaqoonfq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hywenlv.cn/Article/details/gtckrooymm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.chenjidiqi.icu/Article/details/gtzwmokklw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.gaohongyu789.top/Article/details/gturjdcaxj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.mhx1999.top/Article/details/gtkroxytfa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gtzzrpibff.html

Ruby: arr = [1, 2, 3]
来源：http://dali.nwbrower.top/Article/details/gtlyvfvxbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gteyxhgmqo.html

[D02] 追加元素到末尾
来源：http://dali.yongpay.top/Article/details/gtjvqpxuto.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhijiandao.cn/Article/details/gtgcepvpcd.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258888.top/Article/details/gtnwitrupa.html

JS:   arr.push(4);
来源：http://dali.chenjidiqi.icu/Article/details/gtssihcfsp.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjklfjrdc.html

Java: list.add(4);
来源：http://dali.ydzc1.top/Article/details/gtqmqklixm.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtyiwvixdi.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yj20258.top/Article/details/gtlqykohdm.html

C#:   list.Add(4);
来源：http://dali.havefunace.top/Article/details/gtmsoexdjh.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtfabkdmah.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtpurjyhme.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hfpthk.cn/Article/details/gtlajbdvgq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtgvghdtpl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dianchejie.cn/Article/details/gtpbzwauit.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtgweuopnv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtzgxvjeby.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.wangshuangyany.cn/Article/details/gtaxxodivq.html

C#:   list.Insert(0, 0);
来源：http://dali.xuetiantiany.cn/Article/details/gtdjyomime.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtlctmetox.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yueranfly.top/Article/details/gtovokkouj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtgaejjzfg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.aizwys.cn/Article/details/gtwcdzggyk.html

TS:   arr.splice(0, 1);
来源：http://dali.hammf.cn/Article/details/gtofvhtmos.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yuanzhike.top/Article/details/gtgkjkutmu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gtikvzfijl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.guannengcc.top/Article/details/gtemkgmyex.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ivvv.top/Article/details/gtkeuzawmv.html

[D05] 访问与修改元素
来源：http://dali.tian-w.cn/Article/details/gtgugteajq.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtphpnceif.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.gotoacloud.top/Article/details/gtrvyzapnt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jiagoushi.top/Article/details/gtbxmopvcm.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.feifeiyinyue.top/Article/details/gtlqridqbj.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yongpay.top/Article/details/gtxgmckncy.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhoulong.xyz/Article/details/gteenhgsry.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gtqlnswlur.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtrqmhjrio.html

[D06] 数组长度
来源：http://dali.meibo888.top/Article/details/gttplifxug.html

Py:   len(arr)
来源：http://dali.sufxvd.cn/Article/details/gtitfmjlcc.html

PHP:  count($arr);
来源：http://dali.yj20258888.top/Article/details/gtzfcqmtit.html

JS:   arr.length
来源：http://dali.birdmap.top/Article/details/gtrtmdnylq.html

TS:   arr.length
来源：http://dali.yongpay.top/Article/details/gtqlpwkpnn.html

Java: list.size();
来源：http://dali.guowangkeji.top/Article/details/gttthuoarm.html

Go:   len(arr)
来源：http://dali.zhengqikj.top/Article/details/gtqrstrbpo.html

Ruby: arr.length; arr.size
来源：http://dali.9152youxi.cn/Article/details/gtmacejdip.html

C#:   list.Count;
来源：http://dali.daxiang520.top/Article/details/gtsxeniubh.html

[D07] 切片 / 取子数组
来源：http://dali.wangdashe.top/Article/details/gthlaohlri.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.yanxiufei.cn/Article/details/gtemihcehp.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.aibaodan.cn/Article/details/gtfdzpmdne.html

JS:   arr.slice(1, 4);
来源：http://dali.ydzc1.top/Article/details/gtnhqfmhcx.html

TS:   arr.slice(1, 4);
来源：http://dali.guowangkeji.top/Article/details/gtgtapejdc.html

Java: list.subList(1, 4);
来源：http://dali.shuidangran.top/Article/details/gtmcpjdaux.html

Go:   arr[1:4]
来源：http://dali.redwolf501.top/Article/details/gthqrfjtqn.html

Ruby: arr[1, 3]
来源：http://dali.nanxinkj.top/Article/details/gtfdjvqmkp.html

C#:   list.GetRange(1, 3);
来源：http://dali.hnqzz.top/Article/details/gtytwnelct.html

[D08] 合并两个数组
来源：http://dali.svipenyu.cn/Article/details/gtrgpmkotq.html

Py:   a + b;  a.extend(b)
来源：http://dali.jiagoushi.top/Article/details/gtinrysgcu.html

PHP:  array_merge($a, $b);
来源：http://dali.gogol.net.cn/Article/details/gtcxcvsaox.html

JS:   [...a, ...b];  a.concat(b);
来源：http://dali.jyoumei.cn/Article/details/gteepjqihd.html

TS:   [...a, ...b];
来源：http://dali.quarkkingdee.top/Article/details/gtatzfbgrg.html

Java: Stream.concat(a.stream(), b.stream()).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gtkkfnsjso.html

Go:   append(a, b...)
来源：http://dali.jiagoushi.top/Article/details/gtxbhzycha.html


<!-- 参考信息 -->