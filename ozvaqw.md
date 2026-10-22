代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtwlyumopl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj20258888.top/Article/details/gtettjioau.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xinyue.icu/Article/details/gtrcysscdc.html

Ruby: arr.each { |item| puts item }
来源：http://dali.meibo888.top/Article/details/gtvhcpkscq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gtophcmcgs.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtdlcpnswa.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkcpedfdr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cdnleiting.top/Article/details/gtoxztpsil.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xylfe.cn/Article/details/gtvshfudor.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.svipenyu.cn/Article/details/gtkodjluwq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj202588.top/Article/details/gtqlkapgtj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuxming.cn/Article/details/gtfuvunhdv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gteedesznd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jlsjyb.cn/Article/details/gthmrwttmc.html

[B07] while 循环
来源：http://dali.zhixingplan.top/Article/details/gtwizsnfxy.html

Py:   while i < 10: i += 1
来源：http://dali.yonumen.top/Article/details/gtnzihyitp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gtmfwwgqxs.html

JS:   while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gttdnmmbfc.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gtlcykmhcp.html

Java: while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtceggjofj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gtqhsvxoip.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gtkyuukqru.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtmyyneibz.html

[B08] do-while（至少执行一次）
来源：http://dali.tianlin.xyz/Article/details/gtwwtcqycg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gogol.net.cn/Article/details/gtsmmaxtzp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.havefunace.top/Article/details/gtsqguepgl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtdookssue.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtmsjjdknz.html

Java: do { i++; } while (i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtyyctnlwv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258.top/Article/details/gtypkecewq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hfpthk.cn/Article/details/gtruxeifjt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtpqnlxziv.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtveksdfnv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gteduyjaoq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpzitewf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtvudkgufc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258.top/Article/details/gtqpxsuaof.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtvbruirzy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zycfv.cn/Article/details/gtxjwfujbv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xylfe.cn/Article/details/gtnkziedtj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtjkrlvjwq.html

[B10] 遍历同时拿索引
来源：http://dali.zycfv.cn/Article/details/gtplayuavc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtwqwcsksi.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tanke756.top/Article/details/gtrbsnxayy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtwrgkwkni.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gttjjjjwxn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtssmcghpo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jlsjyb.cn/Article/details/gtvtiymuit.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtvpnqawey.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gthhjnwiab.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtqvfqldxt.html

Py:   list(range(0, 10, 2))
来源：http://dali.hfpthk.cn/Article/details/gtadkkossz.html

PHP:  range(0, 10, 2);
来源：http://dali.cqqwz.cn/Article/details/gtrpmbslxx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtwgcnzola.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dashuyun.cn/Article/details/gthbfyqevn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtgdzyrape.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pengpengdd.cyou/Article/details/gtlwbvecun.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtqdoedmxl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zycfv.cn/Article/details/gtoadhjgmf.html

[B12] 跳出多层循环
来源：http://dali.chenlongwang.top/Article/details/gtlzxtwhcd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gtfbkicnjz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtazshblal.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jianghu66.top/Article/details/gtqrqxfyvl.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtmzbumxog.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnukikdni.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnkypvhik.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pycfn.com/Article/details/gtlqdqkpse.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gthpvwgerd.html

[B13] 判断是否为数字
来源：http://dali.gotoacloud.top/Article/details/gtnduvxjml.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gtohxqxtdp.html

PHP:  is_numeric($x)
来源：http://dali.nanxinkj.top/Article/details/gttffwdjct.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtufdrbtjw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtctdglqak.html

Java: x instanceof Number
来源：http://dali.zhengqikj.top/Article/details/gtpoziuvoq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gttojoslhv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.sysykeji.top/Article/details/gtkjldayoo.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtmairxybd.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtfjllzzjw.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yangfankeji.com/Article/details/gttiuxpxfg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gtsjfrogox.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jianghu66.top/Article/details/gtdpeokclm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtrhszyxrq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtlghzkfkm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.fengsongda.top/Article/details/gtbplswedh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.andypj.xyz/Article/details/gtzloykzgh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gttcvrrrvs.html

[B15] 布尔运算与取反
来源：http://dali.shuidangran.top/Article/details/gtubabxped.html

Py:   a and b or not c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtduzdrkik.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtrsfitswy.html

JS:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtqghjsgjg.html

TS:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtqejorshw.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtdccqcrtu.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtczvnotnb.html

Ruby: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtxiwvibqi.html

C#:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gttvbhmrbi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtzmjzawyz.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gtixczpicr.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtklzmyzbz.html

JS:   if (!data) return;
来源：http://dali.redwolf501.top/Article/details/gtytmfqygp.html

TS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gthgxftqvx.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtmozjplko.html

Go:   if data == nil { return }
来源：http://dali.guannengcc.top/Article/details/gtfnyercnm.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtavuuguam.html

C#:   if (data == null) return;
来源：http://dali.smart0.xyz/Article/details/gtodfpfrve.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtlzkhzppd.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtmbzxkpoe.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gthzemxkmt.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtvzwiqnhc.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtafzayodd.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtzkmvjgrk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yvedp.cn/Article/details/gtezdarsas.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtbtyvfach.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtuoqfqspc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtvlaeawfi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sysykeji.top/Article/details/gtbuqdvnwh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtspvnuknt.html

[C02] 默认参数
来源：http://dali.yuxming.cn/Article/details/gtrwkfmzcr.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gtxciwanjv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtsxxfpnbk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gtwpwcipwl.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgtswzwq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gtfwaumqzj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtvkoidxsp.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtoqqyrqlk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtlyykyiqo.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtikkrteyw.html

Py:   def total(*args): return sum(args)
来源：http://dali.yvedp.cn/Article/details/gtvshthrcd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.meibo888.top/Article/details/gtiybgvyyj.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtnswzobmy.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhixingplan.top/Article/details/gtpwqydsby.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sysykeji.top/Article/details/gtrvzpvlta.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.quarkkingdee.top/Article/details/gtngujebcx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cashguo.top/Article/details/gtjixgdzbt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gttquxwqld.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gttiludkvw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtfzwldexj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gtsgyajoxv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.bjfxy.top/Article/details/gthhlkbxbg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.iojbl.cn/Article/details/gtfqwrdyin.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhijiandao.cn/Article/details/gttlknhbdu.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtcxyjusdl.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gteeslhsow.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtiebatqrj.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtvnpbwbfx.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtxfjaxpmo.html

PHP:  return [$a, $b];
来源：http://dali.zhiwuduotai.top/Article/details/gtjvfpovns.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtjqgfrtac.html

TS:   return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtxuftgnxg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahrjlgrv.html

Go:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtttmenpnj.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtjqxjlbiu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sweek.top/Article/details/gthmjzfekc.html

[C06] 匿名函数 / lambda
来源：http://dali.kuanghao11.cn/Article/details/gtykfdlkgt.html

Py:   square = lambda x: x * x
来源：http://dali.yueranfly.top/Article/details/gtevdyznrz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gttjwbxcwp.html

JS:   const square = x => x * x;
来源：http://dali.hywenlv.cn/Article/details/gtiwatvvyz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gthettwcss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gtywsihulq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tianlin.xyz/Article/details/gtglnfkgxq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.aizwys.cn/Article/details/gtduwevedp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtjadkagrh.html

[C07] 把函数作为参数传入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiegpoigg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtlhmaxyki.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhoulong.xyz/Article/details/gtnkbhxdwg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.fzhhl.top/Article/details/gtwkuekaxi.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtjhcoviwq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sufxvd.cn/Article/details/gtkdrwmphe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zhijiandao.cn/Article/details/gttfzhfejb.html

Ruby: arr.map(&:upcase)
来源：http://dali.cashguo.top/Article/details/gtmvmszffq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sufxvd.cn/Article/details/gtufribtcx.html

[C08] 闭包
来源：http://dali.0kj1m.cn/Article/details/gtcptclbot.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtwznelfrs.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sweek.top/Article/details/gtldklzpox.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.gaohongyu789.top/Article/details/gtxbqwrtnx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtzwnqapbj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.xziqi.cn/Article/details/gtqhgthxwb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.9152youxi.cn/Article/details/gtumrqphvx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ehwqpu.com/Article/details/gtzvwahdkd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtomqrtczk.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gtjvdnmmub.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.birdmap.top/Article/details/gtqleucqxj.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hysaishi.cn/Article/details/gtkucgwnya.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xylfe.cn/Article/details/gtuubehuct.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigufen.top/Article/details/gtcyjyvuwr.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjdjljo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gticsopuxn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gtljkenpxy.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtbrvruior.html

[C10] 变量作用域
来源：http://dali.yueranfly.top/Article/details/gtexarbfer.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.wangdashe.top/Article/details/gtamrlrvpc.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nanxinkj.top/Article/details/gtcsgvdadc.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yj202588.top/Article/details/gtofmrnoyv.html

TS:   同 JS
来源：http://dali.zhaomingkeji.xyz/Article/details/gtotphmayb.html

Java: 方法内为块级作用域
来源：http://dali.cashguo.top/Article/details/gtzuyskxsd.html

Go:   花括号块级作用域
来源：http://dali.xuanzx.com/Article/details/gtmcfyhurm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhixingplan.top/Article/details/gtgjqhhfxi.html

C#:   块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtabiqpwxl.html

[C11] 模块导入与导出
来源：http://dali.shangyingyoupin.top/Article/details/gtubzmabti.html

Py:   from module import func
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhlnuken.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yonumen.top/Article/details/gtboutkzef.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.9152youxi.cn/Article/details/gtkawpsrbx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gtvrgzjgzg.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtxbqeurub.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuxming.cn/Article/details/gtsvgqtzaf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnzjxmxv.html

C#:   using System.Text;
来源：http://dali.guowangkeji.top/Article/details/gtlsxbtath.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtmykopjop.html

Py:   (lambda: print("run"))()
来源：http://dali.zycfv.cn/Article/details/gttjuqfhqr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xylfe.cn/Article/details/gtkvkiuiye.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtnhhkguku.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gteezxsxvg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cdnleiting.top/Article/details/gtpgcnxyyb.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhiwuduotai.top/Article/details/gtgiwbfcta.html

Ruby: -> { puts "run" }.call
来源：http://dali.cdnleiting.top/Article/details/gtrkwqtiez.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gzhubu.top/Article/details/gtmtbspzxf.html

[C13] 类型声明 / 类型注解
来源：http://dali.cdnleiting.top/Article/details/gtajylwsln.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtzbzronak.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtmmokbzpv.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.dashuyun.cn/Article/details/gtneftclhp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtlgdjthcm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtxxbgngbq.html

Go:   func add(a, b int) int
来源：http://dali.feifeiyinyue.top/Article/details/gtwnatqqaz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtmjrrnnue.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pycfn.com/Article/details/gtnxeugzdg.html

[C14] 泛型函数
来源：http://dali.jqgufenzy.top/Article/details/gtvojtanlp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gtewdpnacq.html

PHP:  // 无泛型
来源：http://dali.ppjwa.cn/Article/details/gtpnmhleoe.html

JS:   // 无泛型
来源：http://dali.sysykeji.top/Article/details/gtojnlyxgf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtcdonfmqu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.shzxlz.cn/Article/details/gtcznetxsp.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gotoacloud.top/Article/details/gtsewifscr.html

Ruby: # 无泛型
来源：http://dali.ybcxt.top/Article/details/gthpidzkel.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hysaishi.cn/Article/details/gttafzwzin.html

[C15] 解构 / 展开参数
来源：http://dali.xylfe.cn/Article/details/gtqsjvdbml.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.aibaodan.cn/Article/details/gtdbehcwza.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gtxyvdamcm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gtzvjvhsvb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtpddhgxvq.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gtfofjffav.html

Go:   // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtqpmowizc.html

Ruby: a, b = pair
来源：http://dali.ydzc1.top/Article/details/gthuolrryy.html

C#:   var (a, b) = pair;
来源：http://dali.aizwys.cn/Article/details/gtcmhbkqcx.html

[C16] 函数 / 方法重载
来源：http://dali.hnqzz.top/Article/details/gtyhubbzhp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shzxlz.cn/Article/details/gtbproiniu.html

PHP:  // 无重载
来源：http://dali.9152youxi.cn/Article/details/gttzwrpcpp.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gttafjswoc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zdqjudy.top/Article/details/gtbbcaodhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtrcjsecfd.html

Go:   // 无重载：用不同函数名
来源：http://dali.chenjidiqi.icu/Article/details/gtznaqnyyz.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtfvxfaxli.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.kuanghao11.cn/Article/details/gtpvmumyba.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtblpdiquv.html

D. 数组 / 列表 / 集合
来源：http://dali.yuanzhike.top/Article/details/gtkshiikyj.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtujjrywxd.html

[D01] 创建数组 / 列表
来源：http://dali.wangshuangyany.cn/Article/details/gtqewnmhep.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hywenlv.cn/Article/details/gtrwrgeyac.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.ppjwa.cn/Article/details/gtojctfpgp.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtecvlaiav.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaytwehb.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtzqcfvxow.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.cqqwz.cn/Article/details/gtlyzwsxbc.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnxiangtu.top/Article/details/gtclhergvo.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gthukbzetw.html

[D02] 追加元素到末尾
来源：http://dali.feifeiyinyue.top/Article/details/gtrbpmbbku.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zycfv.cn/Article/details/gtaqtsqmhi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtatiqqgfv.html

JS:   arr.push(4);
来源：http://dali.havefunace.top/Article/details/gtezdrwtnu.html

TS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtfbwmrubo.html

Java: list.add(4);
来源：http://dali.hysaishi.cn/Article/details/gtwwwpougj.html

Go:   arr = append(arr, 4)
来源：http://dali.shuidangran.top/Article/details/gtfpbqsuev.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gzhubu.top/Article/details/gtdlydxqze.html

C#:   list.Add(4);
来源：http://dali.hfpthk.cn/Article/details/gtpwvrkrtn.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gtnwkbhnei.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtmjtezenm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.gaohongyu789.top/Article/details/gtegfmzcad.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.shanyushiyangkeji.top/Article/details/gtiwokmhte.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.0kj1m.cn/Article/details/gtktozocsn.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtcuumufoc.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.daria6918.cn/Article/details/gtgbjssmiz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.meibo888.top/Article/details/gtwbfeabvr.html

C#:   list.Insert(0, 0);
来源：http://dali.shzxlz.cn/Article/details/gtgutanncj.html

[D04] 删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtojnabqnd.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.mhx1999.top/Article/details/gtaskoxlva.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tianlin.xyz/Article/details/gtranltklm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.cdnleiting.top/Article/details/gtisgxgiug.html

TS:   arr.splice(0, 1);
来源：http://dali.hnqzz.top/Article/details/gtjiopbncu.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shzxlz.cn/Article/details/gtqvnuhyzd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.9152youxi.cn/Article/details/gtmwqstuhe.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.sweek.top/Article/details/gtscwrhrkb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.andypj.xyz/Article/details/gtvzujqutg.html

[D05] 访问与修改元素
来源：http://dali.zdqjudy.top/Article/details/gtcnclxxbm.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gtppbgxzcc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gtfvsrkbxl.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gtlyugceii.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.gzhubu.top/Article/details/gtamgondyq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhixingplan.top/Article/details/gtxgecutdk.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yvedp.cn/Article/details/gthzmtqgth.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtfaiatjzt.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.zhixingplan.top/Article/details/gtiujxsaqp.html

[D06] 数组长度
来源：http://dali.sufxvd.cn/Article/details/gtmtysuljs.html


<!-- 参考信息 -->