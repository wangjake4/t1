代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtashbqotx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gtqtowufec.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtrsxpluiu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gtwcvehzit.html

[B05] 遍历数组 / 列表
来源：http://dali.yvedp.cn/Article/details/gtryxsgzie.html

Py:   for item in arr: print(item)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqsqerrpx.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.gotoacloud.top/Article/details/gthxzenmzr.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gthugjfevt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gtfqepomlq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtxygpoahi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gtxbqjcpim.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yuanzhike.top/Article/details/gttyytdmii.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuanzx.com/Article/details/gtmrrkiciz.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxslocizb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cashguo.top/Article/details/gtapnzfuhk.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmepiexz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtfevdylsp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.snrcjt.cn/Article/details/gtkspdlmxv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yvedp.cn/Article/details/gtoescjppo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.shuidangran.top/Article/details/gtrfzqluvl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gtmgjhdkzw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtuhydhgxt.html

[B07] while 循环
来源：http://dali.tian-w.cn/Article/details/gtabhawxzs.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gtfvmtwkqq.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gtlsgafgwu.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gttoutbtyz.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtjoftrvxp.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtnxpjstsx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gttrihbqqx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hnxiangtu.top/Article/details/gttdxkifmq.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtsbbfcpzb.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gtnxtenmhj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hywenlv.cn/Article/details/gtdipwvsym.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtabsqvjyb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtmrbfsrkb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gthhxldyzh.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtujpxivdk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtnwenowtr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.smart0.xyz/Article/details/gtksmfcose.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtufbzxioi.html

[B09] break 与 continue
来源：http://dali.fzhhl.top/Article/details/gtnctfrabr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gtzltmpntk.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gttfzidmit.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtmqonsrqj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gttgmztfuh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtehxrtahz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.meibo888.top/Article/details/gtuzecpkru.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtoassyafw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtrdybcxoo.html

[B10] 遍历同时拿索引
来源：http://dali.iojbl.cn/Article/details/gtcfyyodmh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gtksmcrtok.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigfzy.top/Article/details/gthcxmnwxq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gttyjelhpa.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtleswkuxx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sysykeji.top/Article/details/gtxugoitjk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jiagoushi.top/Article/details/gtgxljfefg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zdqjudy.top/Article/details/gtbxoqhaxg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenzaomai.com/Article/details/gtnqrqmfci.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gtqormlztn.html

Py:   list(range(0, 10, 2))
来源：http://dali.jianghu66.top/Article/details/gtruyuegnv.html

PHP:  range(0, 10, 2);
来源：http://dali.sweek.top/Article/details/gtvnlyutsu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gtjskpkceg.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhixingplan.top/Article/details/gtllfffazb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtauahdcbn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhengqikj.top/Article/details/gtvhlbprdu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtlbjemsqr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtfjvwwpus.html

[B12] 跳出多层循环
来源：http://dali.snrcjt.cn/Article/details/gthuauhatk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.bjfxy.top/Article/details/gtgkqznvkh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jqgfzy.top/Article/details/gtfarxpsgc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtxsbfxvun.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtzuadnsfm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtueylvuke.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbfzipf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.shzxlz.cn/Article/details/gtrskcresb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.snrcjt.cn/Article/details/gtorrosglh.html

[B13] 判断是否为数字
来源：http://dali.cdnleiting.top/Article/details/gtxzbqbooh.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenlongwang.top/Article/details/gtyilbxewt.html

PHP:  is_numeric($x)
来源：http://dali.jqgufenzy.top/Article/details/gtrzqqbzye.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtwxjfaars.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gttkfswaic.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtnynvbqpx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtwpxwixoj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtglraclhi.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gtkjvhttik.html

[B14] 判断值是否在集合内
来源：http://dali.shzxlz.cn/Article/details/gtqybfxzur.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gttzgukads.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtomtlafmh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtpmkyhmga.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtwbfmmmhy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gtoipsfzjq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.tianlin.xyz/Article/details/gtkfxtrecp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gtdehmwxee.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gtkuxsvnwl.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtjwtankxi.html

Py:   a and b or not c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiwydvbux.html

PHP:  $a && $b || !$c
来源：http://dali.yanxiufei.cn/Article/details/gtjfetzxhw.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxvuosdqg.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtyldkzmnx.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfcogzzuf.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtvmridrsz.html

Ruby: a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtchmyvied.html

C#:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtxuvnxjzj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtzecpffxk.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtadhkzgjo.html

PHP:  if (!$data) { return; }
来源：http://dali.chenzaomai.com/Article/details/gtjzxiarwh.html

JS:   if (!data) return;
来源：http://dali.shuidangran.top/Article/details/gtmgvbjdhj.html

TS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtochkqjhh.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtkmxfvqen.html

Go:   if data == nil { return }
来源：http://dali.meibo888.top/Article/details/gtrejzajvi.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gtaglbrhci.html

C#:   if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtboygkxnt.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtfbwmfwig.html

C. 函数与作用域
来源：http://dali.chenlongwang.top/Article/details/gtizbgllsl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtggxnulqz.html

[C01] 定义函数
来源：http://dali.yj20258.top/Article/details/gtdudfiqjq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhixingplan.top/Article/details/gthwgfcxdw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtneorckgq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gtuoqoeamn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtkvqeieuo.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtdofldefd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtderfgbmg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuanzx.com/Article/details/gtjwwdraqt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtnynomdxf.html

[C02] 默认参数
来源：http://dali.aibaodan.cn/Article/details/gttmmpyzdy.html

Py:   def greet(name="World"): return name
来源：http://dali.xuetiantiany.cn/Article/details/gtmvotpoju.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtcystbepu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkwjyfdw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gtafftwmcc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cdnleiting.top/Article/details/gtdaapjasl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtpadzluip.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtvxaelpnr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gtfhpcipsl.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtgckakufx.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtkokehmiy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gotoacloud.top/Article/details/gtgvjnvllw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gthmjqnuvi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258888.top/Article/details/gtpvfthypk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtnacjmgpr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtkuwhreue.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtoplqqbre.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hywenlv.cn/Article/details/gtkfbseuoj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblowfdsk.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gtlbquwoap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xuanzx.com/Article/details/gtpshkmnus.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gtahrrcqms.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ivvv.top/Article/details/gtgscudghh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtckewiewp.html

Go:   // 无：用配置结构体参数
来源：http://dali.haohaochexian.top/Article/details/gtkiuqjlxo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gtaolxrhiy.html

C#:   f(a: 1, b: 2)
来源：http://dali.pycfn.com/Article/details/gtaofocqel.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gtmrxkjggr.html

Py:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtsulmakfk.html

PHP:  return [$a, $b];
来源：http://dali.yj20258.top/Article/details/gteslwqori.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtagxxuerm.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtytvlypna.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtakuguijt.html

Go:   return a, b
来源：http://dali.cheryme.top/Article/details/gttspybsbo.html

Ruby: return a, b
来源：http://dali.fengsongda.top/Article/details/gteysglmkn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jiagoushi.top/Article/details/gtfissatww.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gtugaetlcn.html

Py:   square = lambda x: x * x
来源：http://dali.birdmap.top/Article/details/gturdzqmqk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.svipenyu.cn/Article/details/gtlayjlmkb.html

JS:   const square = x => x * x;
来源：http://dali.chenlongwang.top/Article/details/gtnwlyvvxa.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtjkozfemn.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zycfv.cn/Article/details/gtyasvmkba.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.vqdsnc.cn/Article/details/gtseirjrsw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gttwbuivso.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtlpmhtfak.html

[C07] 把函数作为参数传入
来源：http://dali.chenjidiqi.icu/Article/details/gtmueiskbm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gtqqcxyhvq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtvogkiizq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fengsongda.top/Article/details/gthnzrowdh.html

TS:   arr.map(String)
来源：http://dali.sysykeji.top/Article/details/gtckzvjygs.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgufenzy.top/Article/details/gtmujnzudn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.birdmap.top/Article/details/gtzxzakdxn.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtfvibqbci.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jqgfzy.top/Article/details/gtrbsadahb.html

[C08] 闭包
来源：http://dali.xylfe.cn/Article/details/gtqjqheyvw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtlowetura.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.c1oappe.top/Article/details/gtjtfpqboc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ybcxt.top/Article/details/gtmoirzjzy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnxiangtu.top/Article/details/gteeiwsbwr.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.iojbl.cn/Article/details/gtomokgqco.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gtkkwbfrec.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtmorerrph.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gtpbgesgll.html

[C09] 递归
来源：http://dali.xylfe.cn/Article/details/gtjmgqnzhv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbavsgrjc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gtjlwaotcr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yj20258.top/Article/details/gtwgxiqgqw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuetiantiany.cn/Article/details/gtvvhxllqa.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtzkdjspxy.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gtgzfnwugf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gthplztmkf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jiagoushi.top/Article/details/gtbitcourd.html

[C10] 变量作用域
来源：http://dali.sufxvd.cn/Article/details/gtvkmpwqdt.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gtxiwjjhas.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tanke756.top/Article/details/gtfylnhzvf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnrkiuwgj.html

TS:   同 JS
来源：http://dali.yangfankeji.com/Article/details/gtaqjlkvww.html

Java: 方法内为块级作用域
来源：http://dali.c1oappe.top/Article/details/gtgmfqiiyo.html

Go:   花括号块级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtrmfonpvf.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.aizwys.cn/Article/details/gtussqntev.html

C#:   块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gthzbcepuk.html

[C11] 模块导入与导出
来源：http://dali.gzhubu.top/Article/details/gtmihispml.html

Py:   from module import func
来源：http://dali.redwolf501.top/Article/details/gtcitumnnw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.316326.xyz/Article/details/gtrsmlunso.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.pycfn.com/Article/details/gtluzzucmr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sufxvd.cn/Article/details/gtoffxqavu.html

Java: import java.util.List;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpuwswybu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtasfnmtxa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gtbgydcmsq.html

C#:   using System.Text;
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvraxhis.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtjghzbaxe.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gtvsqxxupy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.dashuyun.cn/Article/details/gtuibrzjwq.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtxubschbq.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtvwdebilw.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xziqi.cn/Article/details/gtvpjhqpfp.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fengsongda.top/Article/details/gtvlimspmc.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gthkyqofnf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gtyopjyrfx.html

[C13] 类型声明 / 类型注解
来源：http://dali.shuidangran.top/Article/details/gtfcngwbfp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cashguo.top/Article/details/gtydlbtwtx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtfcabldvf.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.wangdashe.top/Article/details/gtuexmkpsa.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtxjwvbyxs.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gteibdshcb.html

Go:   func add(a, b int) int
来源：http://dali.jlsjyb.cn/Article/details/gtxxmvuihl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtjboghplv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtwsxkzhlm.html

[C14] 泛型函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdctkkss.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.snrcjt.cn/Article/details/gtqwbuhvzl.html

PHP:  // 无泛型
来源：http://dali.jinqigfzy.top/Article/details/gtghuayaoj.html

JS:   // 无泛型
来源：http://dali.andypj.xyz/Article/details/gtzwppsbbq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtnobovjrz.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.gogol.net.cn/Article/details/gtnrlvujgp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtvyqfymtg.html

Ruby: # 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtmlegyygv.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtjlwircgs.html

[C15] 解构 / 展开参数
来源：http://dali.sweek.top/Article/details/gtrgatsydo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhixingplan.top/Article/details/gtzupxhsbl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhijiandao.cn/Article/details/gtgjpepbhn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtxdcgfnjj.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtjmhbmmxj.html

Java: // 无解构
来源：http://dali.hnxiangtu.top/Article/details/gtvgipffon.html

Go:   // 无解构
来源：http://dali.ppjwa.cn/Article/details/gtaxeteiah.html

Ruby: a, b = pair
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiewevjzx.html

C#:   var (a, b) = pair;
来源：http://dali.yueranfly.top/Article/details/gtjkfyueaa.html

[C16] 函数 / 方法重载
来源：http://dali.hfpthk.cn/Article/details/gtlxajjtth.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtepkmmyzu.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtjrykryyl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sxryk.cn/Article/details/gtpcxwikrb.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.tianlin.xyz/Article/details/gtmimbcchj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.zhijiandao.cn/Article/details/gtcqvoujln.html

Go:   // 无重载：用不同函数名
来源：http://dali.hfpthk.cn/Article/details/gtweohcvtb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtkzhqprcm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gthuxfyrsa.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtojtzrllr.html

D. 数组 / 列表 / 集合
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxmelatpa.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtvfnjypkh.html

[D01] 创建数组 / 列表
来源：http://dali.9152youxi.cn/Article/details/gttgepixbr.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.chenlongwang.top/Article/details/gtdzgnrvrn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.birdmap.top/Article/details/gtxcndswgn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ivvv.top/Article/details/gtvsbytzhl.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ehwqpu.com/Article/details/gtqataccis.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.iojbl.cn/Article/details/gtznrjcyoi.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sweek.top/Article/details/gtofpubxil.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dianchejie.cn/Article/details/gtazesofdv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guannengcc.top/Article/details/gtipfplccy.html

[D02] 追加元素到末尾
来源：http://dali.svipenyu.cn/Article/details/gtccycnsgt.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.gaohongyu789.top/Article/details/gtfrrxklaq.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guannengcc.top/Article/details/gtxuddddje.html

JS:   arr.push(4);
来源：http://dali.yj20258.top/Article/details/gtxchlrmmo.html

TS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbpqisonc.html

Java: list.add(4);
来源：http://dali.yueranfly.top/Article/details/gtdhmjlgdx.html

Go:   arr = append(arr, 4)
来源：http://dali.yj202588.top/Article/details/gtqlulepob.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yueranfly.top/Article/details/gtnusxtwfo.html

C#:   list.Add(4);
来源：http://dali.jqgfzy.top/Article/details/gtylttyhgm.html

[D03] 在指定位置插入元素
来源：http://dali.fengsongda.top/Article/details/gtbbndhufd.html

Py:   arr.insert(0, 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtvdgmmamw.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhoulong.xyz/Article/details/gtgiexoyka.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shzxlz.cn/Article/details/gtxvyyxjkw.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gtglhhixba.html

Java: list.add(0, 0);
来源：http://dali.yonumen.top/Article/details/gtzylmzmny.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jinqigufen.top/Article/details/gtznatqrvb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.hnqzz.top/Article/details/gtvaomrldl.html

C#:   list.Insert(0, 0);
来源：http://dali.wangshuangyany.cn/Article/details/gtagqedgaf.html

[D04] 删除元素
来源：http://dali.chenlongwang.top/Article/details/gtzglobtmo.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqsrtpgph.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.nanxuanxn.top/Article/details/gtjsfkmrew.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.c1oappe.top/Article/details/gtiwfaplwz.html

TS:   arr.splice(0, 1);
来源：http://dali.ybcxt.top/Article/details/gtetolaaiz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.cucudq.cn/Article/details/gtpfogailn.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xziqi.cn/Article/details/gtsxmbytgp.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.kuanghao11.cn/Article/details/gtcscwxwmy.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtdnrcgreb.html

[D05] 访问与修改元素
来源：http://dali.jianghu66.top/Article/details/gtidrwvybv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.shangyingyoupin.top/Article/details/gtrvulymiv.html


<!-- 参考信息 -->