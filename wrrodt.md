代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtjrkqkexk.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.svipenyu.cn/Article/details/gtbkcxtkub.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aizwys.cn/Article/details/gterfbtpfk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.tianlin.xyz/Article/details/gtgtpurdoc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daria6918.cn/Article/details/gtaatfcffc.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gtzzbubqew.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigufen.top/Article/details/gtdkwvivpa.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.haohaochexian.top/Article/details/gtdacbavjo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gtmkuarfyt.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtqgaoetmt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gtgozkqmrv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gtofknpcyn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.iojbl.cn/Article/details/gteaexphnc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xziqi.cn/Article/details/gtuasefnbp.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtajabbdjr.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigfzy.top/Article/details/gtrqsgcmko.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ppjwa.cn/Article/details/gtwsipjruk.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtkrzabbaf.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtmgcnzbis.html

Java: while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtybyxivlv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzkmkpgh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gtwknxuews.html

C#:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtipirvunn.html

[B08] do-while（至少执行一次）
来源：http://dali.iojbl.cn/Article/details/gtzoliafiy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtrdaqvfpt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.andypj.xyz/Article/details/gtaosmcqfs.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtmskhehmb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtdsfhazdg.html

Java: do { i++; } while (i < 10);
来源：http://dali.havefunace.top/Article/details/gtqmwyarce.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtjsejsljv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtywzmulyd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtzumvyezv.html

[B09] break 与 continue
来源：http://dali.yonumen.top/Article/details/gtmtlsfxlw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fengsongda.top/Article/details/gteyiznetj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtsxeqobhb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtbobwzgwg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtxbslouny.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtddyahrnk.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daxiang520.top/Article/details/gtevkeqzou.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtqnvcytly.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttszvswzg.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gtcnktputb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.feifeiyinyue.top/Article/details/gtncqoagsm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gtanrtvtwz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtnmnsqbcm.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gtmszupitb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yangfankeji.com/Article/details/gtviwfajdw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shangyingyoupin.top/Article/details/gtpxccsgjm.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtkfoymiap.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtontrdsqq.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gtcnjqnhtu.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gthavlnbiu.html

PHP:  range(0, 10, 2);
来源：http://dali.haohaochexian.top/Article/details/gtvqqpuxth.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtldrsjsot.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtnhqsukns.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yueranfly.top/Article/details/gtzjiftldl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yuanzhike.top/Article/details/gtwycpclvb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtnndtsfts.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmembpvfm.html

[B12] 跳出多层循环
来源：http://dali.shangyingyoupin.top/Article/details/gtcsrpaosw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenzaomai.com/Article/details/gtpmgdqlyf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yangfankeji.com/Article/details/gtoojjdkzi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtdzeqlrla.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtfjdgxsor.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gtkzkmfzfq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.c1oappe.top/Article/details/gtpyxvzres.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngzxzcvt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxuanxn.top/Article/details/gtqnezllkk.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtbrsaowsi.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtaotrgnrc.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtvaywpegg.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtddbsotfe.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtmestodhl.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtalaasmnk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuetiantiany.cn/Article/details/gtjjweicwa.html

Ruby: x.is_a?(Numeric)
来源：http://dali.feifeiyinyue.top/Article/details/gtroyyvmdo.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtacijqejr.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtzczawbpi.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtvhibxkox.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gotoacloud.top/Article/details/gtbfbbutav.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtiuffurbf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuxming.cn/Article/details/gtmovhruyl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtsiphmeji.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.chenlongwang.top/Article/details/gthjljkhdu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yonumen.top/Article/details/gtfekyzkmx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgrrgayxa.html

[B15] 布尔运算与取反
来源：http://dali.snrcjt.cn/Article/details/gtqghaumvi.html

Py:   a and b or not c
来源：http://dali.zhixingplan.top/Article/details/gtmvbruxqq.html

PHP:  $a && $b || !$c
来源：http://dali.yonumen.top/Article/details/gtdkgiixan.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtgidzfgxc.html

TS:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtbbwatpzz.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtbdhzpsmg.html

Go:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gteaddrrma.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtlzygellt.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtlsqbjzby.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtglsjvbuu.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtweyyxdgk.html

PHP:  if (!$data) { return; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtughzlyox.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtrslrzcbr.html

TS:   if (!data) return;
来源：http://dali.gzhubu.top/Article/details/gtkslmwvno.html

Java: if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtndktcwxk.html

Go:   if data == nil { return }
来源：http://dali.shuidangran.top/Article/details/gtrvyeauwe.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtyfbgzezy.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtjfbmuwvt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtvzykgfem.html

C. 函数与作用域
来源：http://dali.cdnleiting.top/Article/details/gtczzbykas.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtthxcwwgs.html

[C01] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtpwcfgszp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpbfkyuhj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtbpavcdfz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtfqfccndd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtyoltccwy.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtyhpsxlgq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cashguo.top/Article/details/gtgdpjmuzb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hfpthk.cn/Article/details/gtcnbeesgm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtkafcgvql.html

[C02] 默认参数
来源：http://dali.zdqjudy.top/Article/details/gtsqmmkzsx.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtaoaoejfi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gogol.net.cn/Article/details/gtmoslnozw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gtaakoxatz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.aibaodan.cn/Article/details/gtfsefffao.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuanzhike.top/Article/details/gtbuidkuvz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtewwgbzaz.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtokoreefl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yanxiufei.cn/Article/details/gtggvxwyoz.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqrkayry.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuanzhike.top/Article/details/gtvabjjpdb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtcqudbmjp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgufenzy.top/Article/details/gthjfmuxto.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.dianchejie.cn/Article/details/gtjowqfhbs.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gtvckoecxy.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gttpyzcnvs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.andypj.xyz/Article/details/gtbuwfnikq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ppjwa.cn/Article/details/gtylewjgry.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cheryme.top/Article/details/gthtrpjzgx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtebzkxoqf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterwswncy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.havefunace.top/Article/details/gtpjuquxud.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtmvaqobdf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtcvivkuji.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gtiupmlgns.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtwjhwsiqi.html

C#:   f(a: 1, b: 2)
来源：http://dali.havefunace.top/Article/details/gtogmgsidc.html

[C05] 返回多个值
来源：http://dali.nwbrower.top/Article/details/gtyrzaullk.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtrtfsnxgg.html

PHP:  return [$a, $b];
来源：http://dali.vqdsnc.cn/Article/details/gtadvevczd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenzaomai.com/Article/details/gtjpddeeml.html

TS:   return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtzvubxkxp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gtxgtlmavh.html

Go:   return a, b
来源：http://dali.shzxlz.cn/Article/details/gthnpovhkb.html

Ruby: return a, b
来源：http://dali.xinyue.icu/Article/details/gtidyningk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.svipenyu.cn/Article/details/gtusplhffa.html

[C06] 匿名函数 / lambda
来源：http://dali.xziqi.cn/Article/details/gtvqrnhilk.html

Py:   square = lambda x: x * x
来源：http://dali.c1oappe.top/Article/details/gtjkpwuwov.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gtboredunt.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtwvzqqawq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtxusnnpcs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xinyue.icu/Article/details/gtswrntnuy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtbiwqqbfd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj20258.top/Article/details/gtwaodeykd.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tian-w.cn/Article/details/gtzejsupun.html

[C07] 把函数作为参数传入
来源：http://dali.feifeiyinyue.top/Article/details/gtutnjgxlz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.fzhhl.top/Article/details/gtvwabbtwg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gthumvtxfb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dashuyun.cn/Article/details/gtwsiwewpc.html

TS:   arr.map(String)
来源：http://dali.guowangkeji.top/Article/details/gtgrzflwta.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtemmappob.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gzhubu.top/Article/details/gtdhpjadze.html

Ruby: arr.map(&:upcase)
来源：http://dali.mhx1999.top/Article/details/gtfhilgcer.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtcxhmirxa.html

[C08] 闭包
来源：http://dali.kuanghao11.cn/Article/details/gtfbvxkjpg.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtqsrcgvix.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guowangkeji.top/Article/details/gtsctcnxxg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gtsvxhvxkn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtxfmgnkwl.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gtercjponp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.wangshuangyany.cn/Article/details/gtndetydyc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.sxryk.cn/Article/details/gtnxuimmnz.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtljattwgj.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtwsyetkye.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtqlnrhfgs.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sufxvd.cn/Article/details/gtlefwvtry.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.snrcjt.cn/Article/details/gtzsbywfry.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gtspbuafas.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtgwtdtuhr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.nanxuanxn.top/Article/details/gthuhrtcpr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.pycfn.com/Article/details/gtybfjrouc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtenvopwjr.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtxtoihqmc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gtdzupobem.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gtllnrzmpr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliffwvsp.html

TS:   同 JS
来源：http://dali.shangyingyoupin.top/Article/details/gtezqcxoii.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtwljoluan.html

Go:   花括号块级作用域
来源：http://dali.cqqwz.cn/Article/details/gtvvffcyde.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtmigsfgdl.html

C#:   块级作用域
来源：http://dali.yangfankeji.com/Article/details/gtpwxssltu.html

[C11] 模块导入与导出
来源：http://dali.zhongyouzk.top/Article/details/gtnldzenmf.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtgccttppq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nwbrower.top/Article/details/gtcljdfyid.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.0kj1m.cn/Article/details/gtoyoeuhbo.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtutirpzcc.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gtlhpllvan.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.svipenyu.cn/Article/details/gthbfcfmcz.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtszevummm.html

C#:   using System.Text;
来源：http://dali.pengpengdd.cyou/Article/details/gthwoicoeo.html

[C12] 立即执行函数 IIFE
来源：http://dali.wangdashe.top/Article/details/gtqnmzjjul.html

Py:   (lambda: print("run"))()
来源：http://dali.daria6918.cn/Article/details/gtunjinhre.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gtsfmdmrqb.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtlfpetjvg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hnqzz.top/Article/details/gttekzakci.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.wangdashe.top/Article/details/gtlsfwnqdq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkljxlbi.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtpqiatohw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtthrgbjcw.html

[C13] 类型声明 / 类型注解
来源：http://dali.sweek.top/Article/details/gthybvalik.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenzaomai.com/Article/details/gtklaeftxu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtkxpvefxz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cashguo.top/Article/details/gtsclugtwx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtdjqjzhkv.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtmiiulfat.html

Go:   func add(a, b int) int
来源：http://dali.nwbrower.top/Article/details/gtpeeewrys.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cucudq.cn/Article/details/gtquqqriuc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gtupmukydx.html

[C14] 泛型函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwvrddexr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.redwolf501.top/Article/details/gtdangwzbv.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbkinnde.html

JS:   // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtinyqfnbh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtofpsxwza.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhengqikj.top/Article/details/gthjavyyri.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gtcbmvsfkg.html

Ruby: # 无泛型
来源：http://dali.fzhhl.top/Article/details/gtmzzacrbv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnznygqja.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gthqfspdkt.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xziqi.cn/Article/details/gtaqvgjczj.html

PHP:  [$a, $b] = $pair;
来源：http://dali.andypj.xyz/Article/details/gthhzofetq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtlqphdvsb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinqigufen.top/Article/details/gtjmiyeqem.html

Java: // 无解构
来源：http://dali.yanxiufei.cn/Article/details/gtpamuairy.html

Go:   // 无解构
来源：http://dali.snrcjt.cn/Article/details/gtcqxkoprl.html

Ruby: a, b = pair
来源：http://dali.chenzaomai.com/Article/details/gtydtayxfj.html

C#:   var (a, b) = pair;
来源：http://dali.yuxming.cn/Article/details/gtjfanrozo.html

[C16] 函数 / 方法重载
来源：http://dali.wangshuangyany.cn/Article/details/gtwxqmbddj.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gteyqevjvr.html

PHP:  // 无重载
来源：http://dali.cqqwz.cn/Article/details/gthabpdhgq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.pycfn.com/Article/details/gtdkgwwrcp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.bjfxy.top/Article/details/gtcqajitrm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.0kj1m.cn/Article/details/gtpllfieus.html

Go:   // 无重载：用不同函数名
来源：http://dali.shangyingyoupin.top/Article/details/gtchwsxmzp.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yangfankeji.com/Article/details/gtygrsnbdl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.9152youxi.cn/Article/details/gtkphlzaas.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gteyphihmd.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gtvcvkpjnt.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtztvevewz.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gtuoucqddz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sxryk.cn/Article/details/gtmudtaxej.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gtvlaxuxyl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yvedp.cn/Article/details/gtuyxdxlwy.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.9152youxi.cn/Article/details/gtxzjejqmn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.redwolf501.top/Article/details/gticolxomd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.wangdashe.top/Article/details/gtthzgrihn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtbntvsues.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gtvdvoyjde.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gtlmgjaqfy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtowuzceak.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yj20258.top/Article/details/gtdkcpfoos.html

JS:   arr.push(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtxuimolwc.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtgidmnqbm.html

Java: list.add(4);
来源：http://dali.ehwqpu.com/Article/details/gtkhsokrbk.html

Go:   arr = append(arr, 4)
来源：http://dali.jiagoushi.top/Article/details/gtgugqvqwo.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tian-w.cn/Article/details/gtrwnnxaoc.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gtvjlxrwri.html

[D03] 在指定位置插入元素
来源：http://dali.feifeiyinyue.top/Article/details/gtvxlxqkrm.html

Py:   arr.insert(0, 0)
来源：http://dali.hongshengwenyu.top/Article/details/gtwifdfwxf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tianlin.xyz/Article/details/gtwerzzlsi.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hywenlv.cn/Article/details/gtkscahjzv.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jlsjyb.cn/Article/details/gtcpgtpxat.html

Java: list.add(0, 0);
来源：http://dali.xziqi.cn/Article/details/gtzbvhjuli.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.feifeiyinyue.top/Article/details/gtoioffgal.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zdqjudy.top/Article/details/gtopugghds.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gtccubhrec.html

[D04] 删除元素
来源：http://dali.cqqwz.cn/Article/details/gtyixqwvyn.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.aibaodan.cn/Article/details/gtsdvyffac.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.zycfv.cn/Article/details/gtqiczbngo.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.yj20258.top/Article/details/gtwhsbzmbh.html

TS:   arr.splice(0, 1);
来源：http://dali.zdqjudy.top/Article/details/gtjrdumgxl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.bjfxy.top/Article/details/gtaejjomzi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.svipenyu.cn/Article/details/gtkbpbnxhx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.xylfe.cn/Article/details/gtkqlefaft.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shzxlz.cn/Article/details/gtldpbanqj.html

[D05] 访问与修改元素
来源：http://dali.snrcjt.cn/Article/details/gtybhxvkum.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tianlin.xyz/Article/details/gtqzwfbzcr.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.zdqjudy.top/Article/details/gtepcknakt.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jqgufenzy.top/Article/details/gtipxxupmh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.yj20258.top/Article/details/gtgmgvzqos.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.jyoumei.cn/Article/details/gtcwtcczfp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gtdxfowyob.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gaohongyu789.top/Article/details/gtszxjyctm.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.jyoumei.cn/Article/details/gtlzjhnuml.html

[D06] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtyzkviumr.html


<!-- 参考信息 -->