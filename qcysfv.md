代发 wailian999

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gotoacloud.top/Article/details/gtjnndcdgt.html

JS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtnnegngju.html

TS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtjjxquxph.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtgulmiiye.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtjxdvulyr.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtljjmjhle.html

C#:   while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtmvfyimnn.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gtrukrofqu.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zdqjudy.top/Article/details/gtolszhxvs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fengsongda.top/Article/details/gtateccesm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtwbmzolgw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtnlbxotwf.html

Java: do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtyriuhsfr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtwhaenoxv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtfobsemyb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gtlqdvuoup.html

[B09] break 与 continue
来源：http://dali.ppjwa.cn/Article/details/gtfpmdcmkd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gtmaqjstsp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopaszneb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtqjqbkowv.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtijtlzcdj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtpsfkjnyh.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gtfcwdqhlh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtowzfspyr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtzjppkvrn.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gtpztgbuzf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gtfhvvjxdx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtqpmnagkn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtwpwrwnin.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gtnjhxkcwb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtnywetxzz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtiascqahh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gtgzwarfrm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtojggxuwh.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgufenzy.top/Article/details/gtcynnetxi.html

Py:   list(range(0, 10, 2))
来源：http://dali.meibo888.top/Article/details/gtaobntouq.html

PHP:  range(0, 10, 2);
来源：http://dali.ybcxt.top/Article/details/gtfyagydsi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gtsixlbbxq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinqigufen.top/Article/details/gtxvvdqhxm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yj20258888.top/Article/details/gtvslsaord.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gtcaeysgfu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gtdiexrofo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.snrcjt.cn/Article/details/gtuzggbhrj.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gtifapdibl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gthyfsgbqx.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.vqdsnc.cn/Article/details/gtgcvyxply.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ivvv.top/Article/details/gtjkkfegvb.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtecohyutf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtyscvozxz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gtkkdtnbal.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhongyouzk.top/Article/details/gtbqalxocn.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtxhmnyogu.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtovdmsldp.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtyoxhzukc.html

PHP:  is_numeric($x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrogxkpvy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtswfzgltx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuetiantiany.cn/Article/details/gthxxrjcsx.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gtnlhfhtky.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gaohongyu789.top/Article/details/gtaeysliek.html

Ruby: x.is_a?(Numeric)
来源：http://dali.vqdsnc.cn/Article/details/gtgggyytiv.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gttklhhmus.html

[B14] 判断值是否在集合内
来源：http://dali.zhongyouzk.top/Article/details/gtqqhgcrnq.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.c1oappe.top/Article/details/gtwalbnzca.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gogol.net.cn/Article/details/gtgekpvrwy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gtlbyphimf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkvhjkoh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtvyhuwmes.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ybcxt.top/Article/details/gthbomsnyq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.pycfn.com/Article/details/gtxbspdavk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiphvqcgn.html

[B15] 布尔运算与取反
来源：http://dali.zhixingplan.top/Article/details/gtpafqppgw.html

Py:   a and b or not c
来源：http://dali.pycfn.com/Article/details/gtmvuvhupu.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtznihrzif.html

JS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtlaiaydzv.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtobhopbfo.html

Java: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtkrdunrty.html

Go:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtwrdegrkg.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtylndedig.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtbjskzdrj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzpojvngo.html

Py:   if not data: return
来源：http://dali.jyoumei.cn/Article/details/gttshgapxw.html

PHP:  if (!$data) { return; }
来源：http://dali.dashuyun.cn/Article/details/gtgswtapwp.html

JS:   if (!data) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtqiwnfyah.html

TS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtqbpveuzg.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtlqqczfmv.html

Go:   if data == nil { return }
来源：http://dali.chenjidiqi.icu/Article/details/gtppxodkoo.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gtpabwqyen.html

C#:   if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtxtplbhrb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtjktcdamz.html

C. 函数与作用域
来源：http://dali.yueranfly.top/Article/details/gtnkmovgtl.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtvgmpmarj.html

[C01] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtwlgtxxck.html

Py:   def add(a, b): return a + b
来源：http://dali.chenjidiqi.icu/Article/details/gtxnaoflzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtxpjydzmd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtujwpxwyi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cheryme.top/Article/details/gthjclwgom.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtretvcirm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ivvv.top/Article/details/gtkouoxkcz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtgqjpdspc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtjvbvjnqt.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtlaswgaga.html

Py:   def greet(name="World"): return name
来源：http://dali.hysaishi.cn/Article/details/gtspyakfqb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.9152youxi.cn/Article/details/gtotparydc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gthkgruavi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtliuvbbic.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ppjwa.cn/Article/details/gtxilghcfl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtubkjycyk.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gtknvreuzt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dianchejie.cn/Article/details/gtlcwpogjc.html

[C03] 可变参数
来源：http://dali.hongshengwenyu.top/Article/details/gtmyfzoixq.html

Py:   def total(*args): return sum(args)
来源：http://dali.snrcjt.cn/Article/details/gttvufzdfn.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtmcddenfb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtnkcdsjlu.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tianlin.xyz/Article/details/gtfqnzmbie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtbhzstoeq.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gteyptwyam.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtixbslxqi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.pycfn.com/Article/details/gtwyoxqfnu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.redwolf501.top/Article/details/gtwihjlbaw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.iojbl.cn/Article/details/gtpnjeftml.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenjidiqi.icu/Article/details/gtqrzmzjtf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtxwgfwbjg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtjhurhwul.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtehhvoosz.html

Go:   // 无：用配置结构体参数
来源：http://dali.aibaodan.cn/Article/details/gtyrlkmwuw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xziqi.cn/Article/details/gtscolrlno.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtynarzygt.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtsfldhgwv.html

Py:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtncpynoyt.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtniasjgyu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gtjqxiftoe.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtqphrzmbv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtlksequaa.html

Go:   return a, b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvlzbhimc.html

Ruby: return a, b
来源：http://dali.yuanzhike.top/Article/details/gtvgjhlyog.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtllpjdzma.html

[C06] 匿名函数 / lambda
来源：http://dali.xinyue.icu/Article/details/gtqgdvhfdi.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gtzmsfdloj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdniwqwgy.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtnhnneuas.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtcjnsroca.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhijiandao.cn/Article/details/gteefiqcbd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtgmwyipbp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhoulong.xyz/Article/details/gtmauoyntw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtoshxnxtg.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gtzaasfgtp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gzhubu.top/Article/details/gtadeiszjc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.redwolf501.top/Article/details/gtjhgptguy.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.haohaochexian.top/Article/details/gtemupatgy.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gtvalwsxgt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtsvxxhhmn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yanxiufei.cn/Article/details/gtllgzeepo.html

Ruby: arr.map(&:upcase)
来源：http://dali.c1oappe.top/Article/details/gtkhtqvsuz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhiwuduotai.top/Article/details/gtouhwxvdx.html

[C08] 闭包
来源：http://dali.dianchejie.cn/Article/details/gtlmebczfk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtteqgkvob.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.svipenyu.cn/Article/details/gtgmdpjxor.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.c1oappe.top/Article/details/gtmqddlcis.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gtmidouwnv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gtomnbmlwc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cdnleiting.top/Article/details/gtnhvizsqu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigfzy.top/Article/details/gttlmmsrix.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yuanzhike.top/Article/details/gtxundmhkq.html

[C09] 递归
来源：http://dali.zhijiandao.cn/Article/details/gtvkjbrbap.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtrkbzyrpy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jlsjyb.cn/Article/details/gtgljcaibc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jlsjyb.cn/Article/details/gtlodwpgld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtppegpxjr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.gogol.net.cn/Article/details/gtlllunhgy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gtypelypcx.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtcmvpxvqq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtwsrlvmvy.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtcyyeigaj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hammf.cn/Article/details/gtcgxjfiro.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cheryme.top/Article/details/gtkawbxpbh.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zycfv.cn/Article/details/gtlbndjtos.html

TS:   同 JS
来源：http://dali.sxryk.cn/Article/details/gtgqjmfgwt.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtxmzpozoy.html

Go:   花括号块级作用域
来源：http://dali.yuanzhike.top/Article/details/gtgnlamxio.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pengpengdd.cyou/Article/details/gtuudrhwir.html

C#:   块级作用域
来源：http://dali.aibaodan.cn/Article/details/gtngedtnhz.html

[C11] 模块导入与导出
来源：http://dali.pengpengdd.cyou/Article/details/gthdlpzxal.html

Py:   from module import func
来源：http://dali.yongpay.top/Article/details/gtlvwivuuz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yj20258888.top/Article/details/gtldpqtqzw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.vqdsnc.cn/Article/details/gtlefthlhr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.dashuyun.cn/Article/details/gtoktzneah.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gttxvglaup.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zycfv.cn/Article/details/gtqbrxhtjh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gtqhoprkep.html

C#:   using System.Text;
来源：http://dali.kuanghao11.cn/Article/details/gtykywstbg.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtibmpkbvz.html

Py:   (lambda: print("run"))()
来源：http://dali.kuanghao11.cn/Article/details/gtoycvcifk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtmbrckypj.html

JS:   (() => { console.log("run"); })();
来源：http://dali.wangdashe.top/Article/details/gtkefdwcfl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtwturkwpn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.nanxuanxn.top/Article/details/gtdjcuolyh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.guowangkeji.top/Article/details/gttdrhyykx.html

Ruby: -> { puts "run" }.call
来源：http://dali.yj20258.top/Article/details/gthuinuzjp.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.9152youxi.cn/Article/details/gttjjuzamc.html

[C13] 类型声明 / 类型注解
来源：http://dali.xziqi.cn/Article/details/gtnqtwgflc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hysaishi.cn/Article/details/gtspphpdtc.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtznlrqfct.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzjumshw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtzriksaic.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtyroaxeeq.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtiuzgchqf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtcuksmzrf.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.ybcxt.top/Article/details/gtwdnarvbc.html

[C14] 泛型函数
来源：http://dali.sweek.top/Article/details/gtgmicmgtt.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cashguo.top/Article/details/gtcwchobnl.html

PHP:  // 无泛型
来源：http://dali.hywenlv.cn/Article/details/gteocivtwj.html

JS:   // 无泛型
来源：http://dali.pycfn.com/Article/details/gtqfhmfopp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.meibo888.top/Article/details/gtdmpfakll.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.quarkkingdee.top/Article/details/gtphwtjgcy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xylfe.cn/Article/details/gtclaysitv.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtostvqswd.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.aizwys.cn/Article/details/gtfuhuvjaq.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gtadepnrjc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtyvefrefa.html

PHP:  [$a, $b] = $pair;
来源：http://dali.aizwys.cn/Article/details/gtebrfkvze.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtybxwbzls.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtznbnpoih.html

Java: // 无解构
来源：http://dali.316326.xyz/Article/details/gtsymfdmie.html

Go:   // 无解构
来源：http://dali.chenlongwang.top/Article/details/gtotmhhtnc.html

Ruby: a, b = pair
来源：http://dali.vqdsnc.cn/Article/details/gtqaahmyjn.html

C#:   var (a, b) = pair;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlkszixwi.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtdpgyqktq.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.jianghu66.top/Article/details/gtmvoovpmk.html

PHP:  // 无重载
来源：http://dali.fengsongda.top/Article/details/gtnxsrybcg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.havefunace.top/Article/details/gtxwsplmen.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yueranfly.top/Article/details/gtuafmztzi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hammf.cn/Article/details/gtsduftylo.html

Go:   // 无重载：用不同函数名
来源：http://dali.cashguo.top/Article/details/gtnncgrsnz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zycfv.cn/Article/details/gtjunergzt.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xylfe.cn/Article/details/gtgwvatcmp.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxgusyjle.html

D. 数组 / 列表 / 集合
来源：http://dali.shuidangran.top/Article/details/gtgcmkzajb.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtmelraxlf.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtlajagllr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangtech.top/Article/details/gtztqftbix.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hnxiangtu.top/Article/details/gtkfqfqslw.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.fengsongda.top/Article/details/gtqqfmyqef.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hfpthk.cn/Article/details/gthujwkeah.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbkjbqtl.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj202588.top/Article/details/gtylrxojir.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yuanzhike.top/Article/details/gtyupjaspo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.cdnleiting.top/Article/details/gtmwkdouuy.html

[D02] 追加元素到末尾
来源：http://dali.jlsjyb.cn/Article/details/gtsaazjkwi.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtziifdvbt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhixingplan.top/Article/details/gtjnjowljr.html

JS:   arr.push(4);
来源：http://dali.zhijiandao.cn/Article/details/gtszykinhg.html

TS:   arr.push(4);
来源：http://dali.sweek.top/Article/details/gtqevfnfsf.html

Java: list.add(4);
来源：http://dali.zhijiandao.cn/Article/details/gtjzaqxisk.html

Go:   arr = append(arr, 4)
来源：http://dali.sysykeji.top/Article/details/gtycruzzll.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtxncosbjc.html

C#:   list.Add(4);
来源：http://dali.gzhubu.top/Article/details/gtdzoazuvb.html

[D03] 在指定位置插入元素
来源：http://dali.andypj.xyz/Article/details/gtsbkulnmk.html

Py:   arr.insert(0, 0)
来源：http://dali.yvedp.cn/Article/details/gtsnpgwsve.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinqigufen.top/Article/details/gtepiayutj.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.pengpengdd.cyou/Article/details/gtqaowasuo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sweek.top/Article/details/gtrattgdsn.html

Java: list.add(0, 0);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqcjrmii.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yangfankeji.com/Article/details/gtxjumytmb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtxfyyyvuo.html

C#:   list.Insert(0, 0);
来源：http://dali.smart0.xyz/Article/details/gtkjamiaco.html

[D04] 删除元素
来源：http://dali.fengsongda.top/Article/details/gtrdhuqrak.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtouxyqhbc.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.iojbl.cn/Article/details/gthptraaix.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yongpay.top/Article/details/gtqdsfvyvt.html

TS:   arr.splice(0, 1);
来源：http://dali.yvedp.cn/Article/details/gtphqcxrkw.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtkgddgmdt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.andypj.xyz/Article/details/gtghcxujou.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuanzhike.top/Article/details/gthpdvhehy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtcfgjccqr.html

[D05] 访问与修改元素
来源：http://dali.chenjidiqi.icu/Article/details/gtkgqbfaen.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtywvoyliq.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gtosgdorrd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtvvnecffy.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhongyouzk.top/Article/details/gtthghfijq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.snrcjt.cn/Article/details/gtulxhoejr.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gtoaugxskv.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtsmsuvbhg.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuanzx.com/Article/details/gtetgvrzhs.html

[D06] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gtvqgqmtul.html

Py:   len(arr)
来源：http://dali.shanyushiyangtech.top/Article/details/gttsjjuyzb.html

PHP:  count($arr);
来源：http://dali.gzhubu.top/Article/details/gtlalvgfhe.html

JS:   arr.length
来源：http://dali.hysaishi.cn/Article/details/gtkreydmsb.html

TS:   arr.length
来源：http://dali.guannengcc.top/Article/details/gtlxjljrmi.html

Java: list.size();
来源：http://dali.gotoacloud.top/Article/details/gtpaqkwace.html

Go:   len(arr)
来源：http://dali.meibo888.top/Article/details/gtyuhcbchz.html

Ruby: arr.length; arr.size
来源：http://dali.hysaishi.cn/Article/details/gtiygakngh.html

C#:   list.Count;
来源：http://dali.yvedp.cn/Article/details/gtilxffjqs.html

[D07] 切片 / 取子数组
来源：http://dali.9152youxi.cn/Article/details/gtxkonfkpz.html

Py:   arr[1:4]; arr[:3]; arr[::2]
来源：http://dali.cdnleiting.top/Article/details/gthmxlpqwz.html

PHP:  array_slice($arr, 1, 3);
来源：http://dali.gotoacloud.top/Article/details/gtsirzrodn.html

JS:   arr.slice(1, 4);
来源：http://dali.zhengqikj.top/Article/details/gtxaeknujw.html

TS:   arr.slice(1, 4);
来源：http://dali.dashuyun.cn/Article/details/gtrhhpwkoz.html

Java: list.subList(1, 4);
来源：http://dali.daxiang520.top/Article/details/gtewaelxor.html

Go:   arr[1:4]
来源：http://dali.cdnleiting.top/Article/details/gtvsmgjfgg.html

Ruby: arr[1, 3]
来源：http://dali.zhengqikj.top/Article/details/gteghebyma.html


<!-- 参考信息 -->