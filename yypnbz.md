代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigufen.top/Article/details/gtkdmajkvi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gtbzbqgfsn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.feifeiyinyue.top/Article/details/gttrvniaqa.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gtudpvehsz.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gtycvdfmcz.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtnnbyzdjs.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtswsqwstp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gtsimqruku.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtvrxtghow.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gteqdhuewt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.redwolf501.top/Article/details/gtpmdbhmyc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xuetiantiany.cn/Article/details/gtdpkeyuhy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xinyue.icu/Article/details/gtgzxumhvf.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtpgndbuzo.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.birdmap.top/Article/details/gtbwiptico.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gttwozdxoc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gttwuytsyy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtuivzelnv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gaohongyu789.top/Article/details/gtekhqsloo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtdsalqugv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258888.top/Article/details/gtrwsyhqlh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nanxinkj.top/Article/details/gtofertkgd.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtqgkaotvu.html

Py:   while i < 10: i += 1
来源：http://dali.yanxiufei.cn/Article/details/gtrwrfknom.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtgxmztdam.html

JS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gthprkvdjo.html

TS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtukhnovtv.html

Java: while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfafiufn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gtfwmwepih.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gotoacloud.top/Article/details/gtyvfdnrtv.html

C#:   while (i < 10) { i++; }
来源：http://dali.cqqwz.cn/Article/details/gtabnvveiz.html

[B08] do-while（至少执行一次）
来源：http://dali.dianchejie.cn/Article/details/gtpedqixci.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgfzy.top/Article/details/gtzsnpzfwb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gtzzrwwsjh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yonumen.top/Article/details/gtrwlxoocz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtkdpknxgu.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtftmhedoh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtkhepveox.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gtzhcylvpv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtkqtiipwt.html

[B09] break 与 continue
来源：http://dali.cqqwz.cn/Article/details/gturypuxql.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.0kj1m.cn/Article/details/gtpghpuzra.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtozwyeeje.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtmzwkrcub.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtiafulhot.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtttbdxntd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhoulong.xyz/Article/details/gtlrpslerr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shuidangran.top/Article/details/gtgpupzvkc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtulxgnujw.html

[B10] 遍历同时拿索引
来源：http://dali.cheryme.top/Article/details/gtvmevsroj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zycfv.cn/Article/details/gtqcknbjlz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtomdemxmb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtjjxylljg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shzxlz.cn/Article/details/gtiwlwudwe.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gtfndxipbs.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenzaomai.com/Article/details/gtqiibckxq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhijiandao.cn/Article/details/gtgeukunlc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinqigufen.top/Article/details/gtybmqsitc.html

[B11] 生成数字序列 / 区间
来源：http://dali.xziqi.cn/Article/details/gtbwuwwixu.html

Py:   list(range(0, 10, 2))
来源：http://dali.cucudq.cn/Article/details/gtcdlmrxwe.html

PHP:  range(0, 10, 2);
来源：http://dali.daxiang520.top/Article/details/gtlpjchpsa.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtnahwtztj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtcfquktgo.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gaohongyu789.top/Article/details/gtycdpmgwh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gtbuizrtft.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtgehopdvc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaulzuhsv.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqwnxzmw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.quarkkingdee.top/Article/details/gtuzbmjufe.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gthctlkogc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtsyudfbwz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtbujmnwia.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtmkrdygzz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tanke756.top/Article/details/gtsvxytgzm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtlfkurhld.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gtwubzjfqs.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gtyvxnpcsn.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtmipxtjce.html

PHP:  is_numeric($x)
来源：http://dali.wangdashe.top/Article/details/gtlsqifzpo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtasrwvhvx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sweek.top/Article/details/gtkwlifbar.html

Java: x instanceof Number
来源：http://dali.cashguo.top/Article/details/gttfnpeoft.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ydzc1.top/Article/details/gtrrkandrc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.iojbl.cn/Article/details/gtqvpolnlx.html

C#:   x is int or double or decimal
来源：http://dali.0kj1m.cn/Article/details/gtiqjlijej.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtcfpjeiit.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtvunjsdek.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yongpay.top/Article/details/gtfaqcueyn.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gtpflmpyyn.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtqssokwya.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtrbdodmll.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ivvv.top/Article/details/gtuuryldnd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtsrtvtgyd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gtgoyztiae.html

[B15] 布尔运算与取反
来源：http://dali.smart0.xyz/Article/details/gttuqmucks.html

Py:   a and b or not c
来源：http://dali.aibaodan.cn/Article/details/gtijanddnh.html

PHP:  $a && $b || !$c
来源：http://dali.gogol.net.cn/Article/details/gtvzyxfszc.html

JS:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gthprupamq.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxqfvthc.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtetiduhxb.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtakoeizmx.html

Ruby: a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtuvsnkwig.html

C#:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtagpepcpj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yj20258.top/Article/details/gtdxojljvd.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtzedphthw.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfghkbtvi.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtrexvzdwb.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsjxcudj.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtopkmxxfu.html

Go:   if data == nil { return }
来源：http://dali.0kj1m.cn/Article/details/gtcmgvuvkf.html

Ruby: return if data.nil?
来源：http://dali.birdmap.top/Article/details/gtatgggkyb.html

C#:   if (data == null) return;
来源：http://dali.sweek.top/Article/details/gtbturncaj.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtqbrfcigh.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtjlkupfon.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtclpmkrgn.html

[C01] 定义函数
来源：http://dali.xinyue.icu/Article/details/gteuaodslz.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtmlpqaiwz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj202588.top/Article/details/gtmtydcsuy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtjkgqalwx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gtgzlrvmvz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zycfv.cn/Article/details/gtcrajqgor.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtvbqczvvp.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gzhubu.top/Article/details/gtxijhjvwv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtotflgtzz.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gtbmejzzdf.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gtjmlsznug.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ivvv.top/Article/details/gtjklebsul.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtfegkmpxc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gtcwkjkplx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guannengcc.top/Article/details/gtxmplutyh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtqnsdoyah.html

Ruby: def greet(name = "World") = name
来源：http://dali.tianlin.xyz/Article/details/gtgjxqfqmr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenjidiqi.icu/Article/details/gtnhvpxqpg.html

[C03] 可变参数
来源：http://dali.sysykeji.top/Article/details/gtzexyzmxq.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtahqjjqbw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gtccyinepk.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.haohaochexian.top/Article/details/gtmqxuxyuc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.kuanghao11.cn/Article/details/gtrcrqknef.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtbroywuyj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpcmrhdk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aibaodan.cn/Article/details/gtaonyptgj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gotoacloud.top/Article/details/gtacghfecp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shzxlz.cn/Article/details/gttiadnnne.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gtcvbujale.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gtfiwbkebl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sweek.top/Article/details/gtvswtfnkc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.gogol.net.cn/Article/details/gtnlmihttz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yonumen.top/Article/details/gtezwsgktr.html

Go:   // 无：用配置结构体参数
来源：http://dali.snrcjt.cn/Article/details/gtyfcmktmh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtrgzcgcug.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjgxzuuof.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtbhtndhwx.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtbjplmvdg.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtgubcanum.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtylsxvdpo.html

TS:   return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gtryxozgqk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sweek.top/Article/details/gtiwpxhkox.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtewtgsayj.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtrgzfnssl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtqqlsjcff.html

[C06] 匿名函数 / lambda
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdutebqe.html

Py:   square = lambda x: x * x
来源：http://dali.vqdsnc.cn/Article/details/gtuqxnoiwb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtjolfltdf.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gteaezzoiu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtkqcqzhgs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ydzc1.top/Article/details/gteeirtyia.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtffrtqwos.html

Ruby: square = ->(x) { x * x }
来源：http://dali.bjfxy.top/Article/details/gtqfqoggxn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yuanzhike.top/Article/details/gtncalkpbt.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gtbkuxqywl.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.andypj.xyz/Article/details/gtefxqniij.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtjhwfqjox.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gtxmyayxqg.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtnwajjejs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigufen.top/Article/details/gtzfyeabyq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jianghu66.top/Article/details/gtttqyueuk.html

Ruby: arr.map(&:upcase)
来源：http://dali.0kj1m.cn/Article/details/gtdhllpuof.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ehwqpu.com/Article/details/gtlqqvjimw.html

[C08] 闭包
来源：http://dali.chenlongwang.top/Article/details/gtdpoyypao.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jinqigfzy.top/Article/details/gthskxzrgo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.guannengcc.top/Article/details/gthtuhjnsj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yangfankeji.com/Article/details/gtzhekcwxl.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gttwpcorcs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jinqigfzy.top/Article/details/gtnqdcorek.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtvlnpyrhd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtoaxwufvw.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtbpzuytwn.html

[C09] 递归
来源：http://dali.aizwys.cn/Article/details/gtcbairnfh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cashguo.top/Article/details/gtfukiaycz.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtfqjwammk.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gtnomsdscn.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtpwaqmemm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqgugitzu.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.bjfxy.top/Article/details/gtfbvdqgdy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtnsqyobcf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gthofpsaws.html

[C10] 变量作用域
来源：http://dali.jinqigfzy.top/Article/details/gtiacqddzr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtptkhpybp.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gogol.net.cn/Article/details/gttxikktna.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zdqjudy.top/Article/details/gtpebydfrn.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajdzxuwu.html

Java: 方法内为块级作用域
来源：http://dali.dashuyun.cn/Article/details/gtsmefitxh.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtolmbxkfh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenlongwang.top/Article/details/gtfjsfanxu.html

C#:   块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtocatackx.html

[C11] 模块导入与导出
来源：http://dali.yangfankeji.com/Article/details/gtlxriiymd.html

Py:   from module import func
来源：http://dali.jiagoushi.top/Article/details/gtjzfbqvxg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.dianchejie.cn/Article/details/gtdfcrfudk.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.mhx1999.top/Article/details/gtrdcodvow.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtiwlwvpgl.html

Java: import java.util.List;
来源：http://dali.hywenlv.cn/Article/details/gtodgnxgzi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jinghuilouyu.cn/Article/details/gtnrdregzv.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtvuettizb.html

C#:   using System.Text;
来源：http://dali.daxiang520.top/Article/details/gtsmnsodqz.html

[C12] 立即执行函数 IIFE
来源：http://dali.cucudq.cn/Article/details/gtpwsqmczu.html

Py:   (lambda: print("run"))()
来源：http://dali.xylfe.cn/Article/details/gtpjabtvql.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtiqhmfzlw.html

JS:   (() => { console.log("run"); })();
来源：http://dali.chenjidiqi.icu/Article/details/gtqipkicrk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jqgufenzy.top/Article/details/gtrcuqizdj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gotoacloud.top/Article/details/gtttclaefh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.pycfn.com/Article/details/gtijrnzuwh.html

Ruby: -> { puts "run" }.call
来源：http://dali.fengsongda.top/Article/details/gtjyzrfqyr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ybcxt.top/Article/details/gtjjsodjye.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhengqikj.top/Article/details/gteysaokda.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zycfv.cn/Article/details/gtncvvcwrk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtndvuwzje.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gthxfqrzgg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gthyzlnrmh.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtptvsunuy.html

Go:   func add(a, b int) int
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqfrflcvd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daria6918.cn/Article/details/gtnpbvdakm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fzhhl.top/Article/details/gtzndfslgs.html

[C14] 泛型函数
来源：http://dali.hongshengwenyu.top/Article/details/gthrqjwcfq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtbxyyenqo.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtyaldxdmv.html

JS:   // 无泛型
来源：http://dali.sufxvd.cn/Article/details/gtzgjinrih.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmztpeoaa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.smart0.xyz/Article/details/gtlstjcpgt.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.9152youxi.cn/Article/details/gtkvxzjflg.html

Ruby: # 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzltsulnt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gtxqyokbdj.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtoqojtqtb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.wangshuangyany.cn/Article/details/gtbmmsqnuq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtrxbgkbxa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtwjbkuoom.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gtksjjnsti.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtaxonvwwr.html

Go:   // 无解构
来源：http://dali.shanyushiyangtech.top/Article/details/gtmflfbvfa.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtofhepbpc.html

C#:   var (a, b) = pair;
来源：http://dali.tian-w.cn/Article/details/gtoijxwiuc.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gthtnoufpy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtihtqqhxt.html

PHP:  // 无重载
来源：http://dali.cashguo.top/Article/details/gtxlvqincv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zhijiandao.cn/Article/details/gtqpleakbr.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.dashuyun.cn/Article/details/gtiapgmdas.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.mhx1999.top/Article/details/gtduyqzrqe.html

Go:   // 无重载：用不同函数名
来源：http://dali.hysaishi.cn/Article/details/gtpniuycba.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtytyyqqqc.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ydzc1.top/Article/details/gtunpyvfxh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtokivwxvv.html

D. 数组 / 列表 / 集合
来源：http://dali.0kj1m.cn/Article/details/gtieijbvrj.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtlmsylhvt.html

[D01] 创建数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtiofmajqg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.andypj.xyz/Article/details/gtteyvitxv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.andypj.xyz/Article/details/gtijfnloen.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sufxvd.cn/Article/details/gttogmuhut.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhrgveth.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtninacfpd.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.haohaochexian.top/Article/details/gtofioxkls.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtbledmclq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jqgfzy.top/Article/details/gtbxgbhflq.html

[D02] 追加元素到末尾
来源：http://dali.shuidangran.top/Article/details/gtunlvyrgy.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcavsuleh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtewpmzura.html

JS:   arr.push(4);
来源：http://dali.shuidangran.top/Article/details/gtwcdkuzyd.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtckxgdpei.html

Java: list.add(4);
来源：http://dali.jqgfzy.top/Article/details/gtxwunkpmk.html

Go:   arr = append(arr, 4)
来源：http://dali.cashguo.top/Article/details/gtqinprzsr.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hongshengwenyu.top/Article/details/gtpjmopizy.html

C#:   list.Add(4);
来源：http://dali.guannengcc.top/Article/details/gtcrtfyuwb.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtnsusxfoy.html

Py:   arr.insert(0, 0)
来源：http://dali.birdmap.top/Article/details/gtqbrytqvu.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtqjdbmvlh.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.fzhhl.top/Article/details/gtqfhprgjq.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cqqwz.cn/Article/details/gtbgkhjmbc.html

Java: list.add(0, 0);
来源：http://dali.yuanzhike.top/Article/details/gtbpfsboqt.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hysaishi.cn/Article/details/gtkuqqqysz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yonumen.top/Article/details/gtnmevpdvu.html

C#:   list.Insert(0, 0);
来源：http://dali.svipenyu.cn/Article/details/gtpadefdzs.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtrkcvrqcp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.shangyingyoupin.top/Article/details/gtixhrjfnl.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.jinqigufen.top/Article/details/gtzzungdwn.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gtwxrnersw.html

TS:   arr.splice(0, 1);
来源：http://dali.yuxming.cn/Article/details/gtykocpzxv.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.tanke756.top/Article/details/gtkvhdrfvx.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zdqjudy.top/Article/details/gtdjbjbckl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.shzxlz.cn/Article/details/gtjwbczjgu.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwiqlsgaq.html

[D05] 访问与修改元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxdtepll.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.wangshuangyany.cn/Article/details/gtxmkhjnkk.html


<!-- 参考信息 -->