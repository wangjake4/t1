代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtomkdybji.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenjidiqi.icu/Article/details/gtcgekzray.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xziqi.cn/Article/details/gtegcqkfkg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hnxiangtu.top/Article/details/gtoweexibv.html

[B05] 遍历数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtmiysqzlb.html

Py:   for item in arr: print(item)
来源：http://dali.jinqigfzy.top/Article/details/gtnjpclvyo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtdbydflgn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtgxahmlkm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtxmcyabip.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigufen.top/Article/details/gtdwxmnqto.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtlytmndmk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shzxlz.cn/Article/details/gtzalijxzw.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtrluutlcz.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtqjejxfyh.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gthhntipxb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gttmbgzwhg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtqtfakmjs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtqkqcvhmp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jiagoushi.top/Article/details/gtmvnctrfo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yongpay.top/Article/details/gtmzclsxgo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.redwolf501.top/Article/details/gttzwvdpxp.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yueranfly.top/Article/details/gtipfjofrr.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gtblysaaoi.html

Py:   while i < 10: i += 1
来源：http://dali.jlsjyb.cn/Article/details/gthiqcxbta.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtavseihjh.html

JS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtwftrwpkl.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtotkudrqd.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gtqroxfxvn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdesgxdts.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtrifdswrf.html

C#:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtgkbhkjta.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gthbzgsxyi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtqyyqiwmp.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtafbxeeqn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtxxywybxv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtlfpnttxy.html

Java: do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtyhudxuab.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangdashe.top/Article/details/gtmvsdlzzf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtrnfyjftl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtqiixrufx.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtvjkastin.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ppjwa.cn/Article/details/gtoofxnnaz.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtoanfarvg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtilzzhbhe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtkpqvvklw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhiwuduotai.top/Article/details/gtwdoytvli.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzszsdqi.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gttenpjlcw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtdlyyxynj.html

[B10] 遍历同时拿索引
来源：http://dali.zhoulong.xyz/Article/details/gtylosvyec.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.chenjidiqi.icu/Article/details/gtxklzgztl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hysaishi.cn/Article/details/gtpzdpurfs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtizeckleu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtteqlcnlh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtztllcrsm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtlaqaqusj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenjidiqi.icu/Article/details/gtptmqdgld.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gtujertwxm.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtuutzomjs.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gtbhkstzza.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtxgltvkmu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtbkwwexxo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtqujnqvsn.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nwbrower.top/Article/details/gtpquhlhpm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ivvv.top/Article/details/gtnhjsvwdm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.gaohongyu789.top/Article/details/gtxtjpfgpf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtkqmeyxwf.html

[B12] 跳出多层循环
来源：http://dali.yongpay.top/Article/details/gtownchalk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gotoacloud.top/Article/details/gtlzmpvvhz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtxzicndoa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtjxhtrzlw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtiblmpnzh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtaqbelaxx.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hammf.cn/Article/details/gtzfkydusr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xinyue.icu/Article/details/gtdrbwvixs.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gttymmkfix.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gthciuicwo.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangshuangyany.cn/Article/details/gtpoyobbhr.html

PHP:  is_numeric($x)
来源：http://dali.jinqigufen.top/Article/details/gturbcfctv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gtjphuyhcs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.sxryk.cn/Article/details/gtrxowodvh.html

Java: x instanceof Number
来源：http://dali.dashuyun.cn/Article/details/gtgbtsszrg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj202588.top/Article/details/gtaegnqimt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtxedgzznj.html

C#:   x is int or double or decimal
来源：http://dali.yuxming.cn/Article/details/gtieyommwx.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gtcitgqsei.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sysykeji.top/Article/details/gtneoedoon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtstuvpteq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkdezwexf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtronyahrz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gthsoxsgsm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtatjuqtlz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gtdrkxyyhn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtptcpdbms.html

[B15] 布尔运算与取反
来源：http://dali.chenjidiqi.icu/Article/details/gtxlvmphkg.html

Py:   a and b or not c
来源：http://dali.hnqzz.top/Article/details/gtnvkhvsgn.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtcswtdiwn.html

JS:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvqufdnj.html

TS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwfyowwiz.html

Java: a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gttpjxeqsy.html

Go:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtbttijzpj.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqzpcfkc.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gteosdgzsq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtnfqokgix.html

Py:   if not data: return
来源：http://dali.c1oappe.top/Article/details/gtthnyzveh.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gtcxjhjkwj.html

JS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtjwgvuqlh.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtppidtvlh.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gthuqefeoq.html

Go:   if data == nil { return }
来源：http://dali.zhoulong.xyz/Article/details/gtmxondihk.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtskfugdzy.html

C#:   if (data == null) return;
来源：http://dali.zycfv.cn/Article/details/gttdmadtff.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtnsxecobz.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gttndskeyb.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtitsfghjc.html

[C01] 定义函数
来源：http://dali.bjfxy.top/Article/details/gtxaxaydrh.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtfxkghhuv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtzybynwey.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtwtgdotvp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gtwpineqpr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtgutnyprs.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.chenjidiqi.icu/Article/details/gtkzqwgvde.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtqhvfyihh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtifumybfk.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtaabihixh.html

Py:   def greet(name="World"): return name
来源：http://dali.hongshengwenyu.top/Article/details/gtbzlqzmeb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gttfgdltrp.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtagqwhdwh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtiaxpmgpb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.hnxiangtu.top/Article/details/gtdtwrshqy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.svipenyu.cn/Article/details/gtzrayjnzk.html

Ruby: def greet(name = "World") = name
来源：http://dali.guowangkeji.top/Article/details/gtzcuyztsr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tanke756.top/Article/details/gtsmovjfmk.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtotcaraur.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtlbbbsxrd.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.c1oappe.top/Article/details/gtkxftfpjq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhongyouzk.top/Article/details/gtwkdjsuue.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtaljwshtv.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cheryme.top/Article/details/gtndbiuwql.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.0kj1m.cn/Article/details/gtfnbpvtuf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtqhdsjvox.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shanyushiyangtech.top/Article/details/gtxidjabnt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.c1oappe.top/Article/details/gtjgncwaty.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigufen.top/Article/details/gtmeycaeyv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtvdrfqtmy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfrigftsl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtpgwcoqtp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtmqyqwjev.html

Go:   // 无：用配置结构体参数
来源：http://dali.c1oappe.top/Article/details/gthifebwho.html

Ruby: f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtzlhawmmh.html

C#:   f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtcdcsqufl.html

[C05] 返回多个值
来源：http://dali.birdmap.top/Article/details/gtrqrroncw.html

Py:   return a, b
来源：http://dali.jinqigfzy.top/Article/details/gtwcuvobbr.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtjfqzxsne.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtswyfphxn.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtdgyyokzj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.redwolf501.top/Article/details/gtrcctaigo.html

Go:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gtuhxgypbe.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtrykcifkk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cucudq.cn/Article/details/gthibpfkps.html

[C06] 匿名函数 / lambda
来源：http://dali.sweek.top/Article/details/gtzoutrjpo.html

Py:   square = lambda x: x * x
来源：http://dali.gaohongyu789.top/Article/details/gtjuopfzmi.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gtbueftjks.html

JS:   const square = x => x * x;
来源：http://dali.sweek.top/Article/details/gtygqxypkh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtcddtdmdw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xylfe.cn/Article/details/gtgbbejkzh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtmjwpcuoe.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gttcqgkjzt.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtxzmndtpj.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gttcikcebs.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtrjesnuzy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gttnddzvvt.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yanxiufei.cn/Article/details/gtijtvhlwl.html

TS:   arr.map(String)
来源：http://dali.meibo888.top/Article/details/gtzxffzjnu.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yvedp.cn/Article/details/gtfcgvhhbb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.smart0.xyz/Article/details/gtgahkokrd.html

Ruby: arr.map(&:upcase)
来源：http://dali.haohaochexian.top/Article/details/gtffuycifd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jianghu66.top/Article/details/gtnqmxdpmq.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtvlmwuxht.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtfisbmjpq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gtmpikiokw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gtduublscd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gteahwahbe.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtakpdcjly.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zhongyouzk.top/Article/details/gtxbjtpnrq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinqigufen.top/Article/details/gtoipinjmh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvageybd.html

[C09] 递归
来源：http://dali.cdnleiting.top/Article/details/gthjmbayyw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yuanzhike.top/Article/details/gtjudsztnm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.kuanghao11.cn/Article/details/gtpwfewqlm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.haohaochexian.top/Article/details/gtqdiszdhs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hnqzz.top/Article/details/gtkbjjeapd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gthinugcro.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hfpthk.cn/Article/details/gtlyibqzmd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ydzc1.top/Article/details/gthjligwyl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtxopyykkl.html

[C10] 变量作用域
来源：http://dali.316326.xyz/Article/details/gtwdrxvpeb.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jlsjyb.cn/Article/details/gtawhjbyvn.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtbnzntizf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixhpvifg.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtsdvwupel.html

Java: 方法内为块级作用域
来源：http://dali.sweek.top/Article/details/gtfcvfbzis.html

Go:   花括号块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnwkrcviy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gaohongyu789.top/Article/details/gtqqvjnxrx.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtgdelxzsl.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gtkkxltgjm.html

Py:   from module import func
来源：http://dali.yanxiufei.cn/Article/details/gtwkigmbpp.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.pycfn.com/Article/details/gtuyltvkpo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhixingplan.top/Article/details/gtewsqwneh.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.fengsongda.top/Article/details/gtqfanttdj.html

Java: import java.util.List;
来源：http://dali.zhiwuduotai.top/Article/details/gtgyzshmjm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtrjlcsboo.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yongpay.top/Article/details/gtxvpzyeaz.html

C#:   using System.Text;
来源：http://dali.zhijiandao.cn/Article/details/gtnychnvsj.html

[C12] 立即执行函数 IIFE
来源：http://dali.yongpay.top/Article/details/gtcjqmqiij.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtfomvdoio.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtzkzyfgpi.html

JS:   (() => { console.log("run"); })();
来源：http://dali.guannengcc.top/Article/details/gtluttfrrx.html

TS:   (() => { console.log("run"); })();
来源：http://dali.birdmap.top/Article/details/gtrdrovlpn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jinqigufen.top/Article/details/gtuuyyzzgl.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtmodlksvg.html

Ruby: -> { puts "run" }.call
来源：http://dali.yvedp.cn/Article/details/gtvbwkvowh.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtarwojbyr.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gtovwmdckp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.xylfe.cn/Article/details/gtydnwuymn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtgwdfpatl.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtohdhnjxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtizrctmgp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtgwnvsmlw.html

Go:   func add(a, b int) int
来源：http://dali.tianlin.xyz/Article/details/gtowpcitis.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.tianlin.xyz/Article/details/gtpuucruby.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jqgfzy.top/Article/details/gtdtjpqqnb.html

[C14] 泛型函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxcnqnvqu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.chenjidiqi.icu/Article/details/gtnyvypzts.html

PHP:  // 无泛型
来源：http://dali.xylfe.cn/Article/details/gtsocbeozr.html

JS:   // 无泛型
来源：http://dali.ydzc1.top/Article/details/gtkippluyv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtounyokjt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.mhx1999.top/Article/details/gtkvdnpvfx.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.redwolf501.top/Article/details/gtqstuavjc.html

Ruby: # 无泛型
来源：http://dali.xziqi.cn/Article/details/gtbjihybei.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xinyue.icu/Article/details/gtpgldmmrd.html

[C15] 解构 / 展开参数
来源：http://dali.wangdashe.top/Article/details/gtitfodaik.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.daxiang520.top/Article/details/gtziqqdaiq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.xuanzx.com/Article/details/gtjjhhjdov.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtivqxajed.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtzrtttuic.html

Java: // 无解构
来源：http://dali.guannengcc.top/Article/details/gtfupqlkhe.html

Go:   // 无解构
来源：http://dali.andypj.xyz/Article/details/gtoyeyocil.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtvzoqsbaz.html

C#:   var (a, b) = pair;
来源：http://dali.yj20258888.top/Article/details/gtitulzfdg.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtsapnfate.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zycfv.cn/Article/details/gtheqccany.html

PHP:  // 无重载
来源：http://dali.jiagoushi.top/Article/details/gtnonvuoff.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.fengsongda.top/Article/details/gttwwhaovd.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtuqgsaeod.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sysykeji.top/Article/details/gtlmipgjtb.html

Go:   // 无重载：用不同函数名
来源：http://dali.shzxlz.cn/Article/details/gtnqozjzdw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.ybcxt.top/Article/details/gtocptcxml.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gtulvmqudo.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtuonbxgbs.html

D. 数组 / 列表 / 集合
来源：http://dali.yonumen.top/Article/details/gtdfjwknbs.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtweigteld.html

[D01] 创建数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtsmswoouc.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.havefunace.top/Article/details/gtezgfaldd.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xuetiantiany.cn/Article/details/gtyyxaoogq.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtaowmnldo.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gtatgrwplf.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtnsouyzze.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.sufxvd.cn/Article/details/gtrrlrqymw.html

Ruby: arr = [1, 2, 3]
来源：http://dali.mhx1999.top/Article/details/gtvdyopnxv.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.aibaodan.cn/Article/details/gtyrgnepbw.html

[D02] 追加元素到末尾
来源：http://dali.guannengcc.top/Article/details/gtocbcbnnc.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cdnleiting.top/Article/details/gtzodjlnmu.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.guowangkeji.top/Article/details/gtqwuwgwqx.html

JS:   arr.push(4);
来源：http://dali.daria6918.cn/Article/details/gtekvxizun.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtxkqnjtbt.html

Java: list.add(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtkdyyymcp.html

Go:   arr = append(arr, 4)
来源：http://dali.jqgufenzy.top/Article/details/gtuhawwhoc.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.gotoacloud.top/Article/details/gtsoozzmhe.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gttbnvrbov.html

[D03] 在指定位置插入元素
来源：http://dali.316326.xyz/Article/details/gtuaqpyahn.html

Py:   arr.insert(0, 0)
来源：http://dali.jinqigfzy.top/Article/details/gtdpzmchki.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhiwuduotai.top/Article/details/gtzfxpveyo.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtxiyivjcx.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.dashuyun.cn/Article/details/gtrtndixge.html

Java: list.add(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuofmalqs.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cucudq.cn/Article/details/gtfunktllv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqkrdnleu.html

C#:   list.Insert(0, 0);
来源：http://dali.fengsongda.top/Article/details/gtqgbziepb.html

[D04] 删除元素
来源：http://dali.xylfe.cn/Article/details/gtqajwgbsh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.hfpthk.cn/Article/details/gthulycuzh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.aizwys.cn/Article/details/gtoxalrtlj.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.tanke756.top/Article/details/gtgiamziru.html

TS:   arr.splice(0, 1);
来源：http://dali.gotoacloud.top/Article/details/gtysgpvrpf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhengqikj.top/Article/details/gtacpxkxgk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jqgfzy.top/Article/details/gttrrefjmq.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.0kj1m.cn/Article/details/gtkuyrvboe.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gtrwmxxlez.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtgaascuku.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cheryme.top/Article/details/gttdxzrzet.html


<!-- 参考信息 -->