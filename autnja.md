代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqgsjhuc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pengpengdd.cyou/Article/details/gtdybomhah.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhoulong.xyz/Article/details/gtwgtueqcr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxinkj.top/Article/details/gtoiapczbt.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtfwvbbylh.html

Py:   for item in arr: print(item)
来源：http://dali.hammf.cn/Article/details/gtodhahdsk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gthekmlwon.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtsuykoolf.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbxjlxdkg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.316326.xyz/Article/details/gtzverhoqw.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gtahysydcp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtigqnmmvc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guannengcc.top/Article/details/gtpwiobmcy.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtkaguncgb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtuiyobhga.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtbgkxhhxu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtdjvpdeqq.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtxbecptvv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ivvv.top/Article/details/gtjchjqojj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gtrorzyrgz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cashguo.top/Article/details/gtkvohbtwi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pycfn.com/Article/details/gtifzrcrah.html

[B07] while 循环
来源：http://dali.nanxinkj.top/Article/details/gthdmmcrez.html

Py:   while i < 10: i += 1
来源：http://dali.nwbrower.top/Article/details/gtchakfrug.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlwfgyokh.html

JS:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtwwpjbtto.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtytbltjnb.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtigypjgzm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.guannengcc.top/Article/details/gttnccrnau.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhengqikj.top/Article/details/gtquaucbch.html

C#:   while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtjqksjqyc.html

[B08] do-while（至少执行一次）
来源：http://dali.tianlin.xyz/Article/details/gtarswurhv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pycfn.com/Article/details/gtppnyhirc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnqzz.top/Article/details/gtrfupwmdb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gthexhwitp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.kuanghao11.cn/Article/details/gtzhphsxqt.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtyskbdivv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtbfnmacvg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gtyunrqpuv.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gtpitbggtc.html

[B09] break 与 continue
来源：http://dali.zhaomingkeji.xyz/Article/details/gthzkjhejh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jianghu66.top/Article/details/gtpaggjmcx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtmfkiputk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtwapepegz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmgzofqos.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtupfyfmfb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigufen.top/Article/details/gtagiefogf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ppjwa.cn/Article/details/gtpwijtfim.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtuufwfahx.html

[B10] 遍历同时拿索引
来源：http://dali.vqdsnc.cn/Article/details/gtbgllrodx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daria6918.cn/Article/details/gtvofvpjkk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhengqikj.top/Article/details/gtmsdvcweb.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.316326.xyz/Article/details/gtytkqjvbk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtzznligyf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtydvlnwqg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gtwooejptn.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtuyrtdjop.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hfpthk.cn/Article/details/gtuagzrxpr.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdwcmgrd.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gtfvilbppu.html

PHP:  range(0, 10, 2);
来源：http://dali.316326.xyz/Article/details/gtatwzpklr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoaxvfbkh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtaynddjho.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gtzraidysh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hywenlv.cn/Article/details/gtinmjpxdz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xinyue.icu/Article/details/gtupqgvzml.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dashuyun.cn/Article/details/gtmftmazlt.html

[B12] 跳出多层循环
来源：http://dali.dianchejie.cn/Article/details/gtsatobgoo.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gtssqjitlc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.aizwys.cn/Article/details/gtajoxmque.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtuqgytkra.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtrtmjhyze.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gtlmbpmdgo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtsndcjotx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hnqzz.top/Article/details/gtzjttvciy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtzcjzpbzv.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtjxwjfaps.html

Py:   isinstance(x, (int, float))
来源：http://dali.yonumen.top/Article/details/gtvmnnwraa.html

PHP:  is_numeric($x)
来源：http://dali.nwbrower.top/Article/details/gtxjvoahga.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtgvpizfkd.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtmbjtxqae.html

Java: x instanceof Number
来源：http://dali.zycfv.cn/Article/details/gtzdcllcqn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dashuyun.cn/Article/details/gtzviuvjci.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cucudq.cn/Article/details/gtdzcuhvjk.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtqtkdasvx.html

[B14] 判断值是否在集合内
来源：http://dali.bjfxy.top/Article/details/gtpawwlraf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dianchejie.cn/Article/details/gthvzznhzx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pengpengdd.cyou/Article/details/gtpphzcuqd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtlaokdfjh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtkpgzgvql.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gtyhdnrsvp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.quarkkingdee.top/Article/details/gtwcxlymko.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gteyjzxtcg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhoulong.xyz/Article/details/gthxipjuqs.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtsscrkkku.html

Py:   a and b or not c
来源：http://dali.yuanzhike.top/Article/details/gtlcedleyl.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtwijzszag.html

JS:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtcyywejrj.html

TS:   a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtomhrbilz.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtajpaueoz.html

Go:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtgxgmaqxr.html

Ruby: a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtnlzyprvd.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtzzjyvjiy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xziqi.cn/Article/details/gttnyxecmr.html

Py:   if not data: return
来源：http://dali.shanyushiyangtech.top/Article/details/gtsiqweovm.html

PHP:  if (!$data) { return; }
来源：http://dali.sysykeji.top/Article/details/gtowmltlnp.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtiaowjczu.html

TS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtewsgsuxz.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtzpiuwtjx.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gtnqugpqdg.html

Ruby: return if data.nil?
来源：http://dali.zdqjudy.top/Article/details/gtdvniwugq.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtjqcwosuw.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgpsofkgy.html

C. 函数与作用域
来源：http://dali.gzhubu.top/Article/details/gtsdysdreh.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtnpdsmsxq.html

[C01] 定义函数
来源：http://dali.jianghu66.top/Article/details/gtfufnbjed.html

Py:   def add(a, b): return a + b
来源：http://dali.smart0.xyz/Article/details/gtltxxdtus.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtttekkbwf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmejnlce.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.smart0.xyz/Article/details/gtpdnwmnwk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtehczqlsn.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hammf.cn/Article/details/gtvzofucvn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.cashguo.top/Article/details/gtbanecbta.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtznzqfyfz.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtronztohp.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtmeclzqff.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gtzsnsqimz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxfesrhyv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtmjrzbuvf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.0kj1m.cn/Article/details/gtrgdsbpdr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtfmaxfgjc.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtxjksneme.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtyfjgnywe.html

[C03] 可变参数
来源：http://dali.chenjidiqi.icu/Article/details/gtongwvhtq.html

Py:   def total(*args): return sum(args)
来源：http://dali.tianlin.xyz/Article/details/gtpyfuzfdf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmcanngwv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtzoqljnsf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtxoeiiysd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtsnbyvomd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jianghu66.top/Article/details/gtrlgpibxp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtwfjgaskk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtufecundr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cucudq.cn/Article/details/gtaxrrfrer.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pengpengdd.cyou/Article/details/gtlfxijkcv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sufxvd.cn/Article/details/gtaoslejxu.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtbtvrpdax.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtxelqwxjp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gtwvogiisd.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenzaomai.com/Article/details/gthsuqvwea.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtrmwnhlpj.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdtillrd.html

[C05] 返回多个值
来源：http://dali.ehwqpu.com/Article/details/gttrloztvj.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtarawxxru.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gtmywyebfo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtezeqgzpq.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtdxtkkavp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhoulong.xyz/Article/details/gtbsekinmo.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtucqbnszs.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtnoyuqghx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.dashuyun.cn/Article/details/gtbwiamkds.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gtjtqijmca.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtaarqgpbh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtpwfclels.html

JS:   const square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtrdbmiauu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yueranfly.top/Article/details/gtobevozxs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hywenlv.cn/Article/details/gtqfwnfwxb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.svipenyu.cn/Article/details/gtwdfjttzy.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gtennkmdtr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtchileocj.html

[C07] 把函数作为参数传入
来源：http://dali.c1oappe.top/Article/details/gtelpvfegy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtogfozlxc.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtzzuuqocm.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zycfv.cn/Article/details/gtmiwpdecp.html

TS:   arr.map(String)
来源：http://dali.xylfe.cn/Article/details/gtutqemsen.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinqigfzy.top/Article/details/gtilaskulx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xinyue.icu/Article/details/gtbgpxbyvn.html

Ruby: arr.map(&:upcase)
来源：http://dali.meibo888.top/Article/details/gtnvlhvmzz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.dashuyun.cn/Article/details/gtqhkdsuma.html

[C08] 闭包
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwlcxyycb.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hongshengwenyu.top/Article/details/gtandxdtlo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gticjvskmc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhixingplan.top/Article/details/gtrmudalkg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gtmvcdeixj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shzxlz.cn/Article/details/gtqhmwgvfy.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xylfe.cn/Article/details/gtmmikcscj.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.mhx1999.top/Article/details/gtmhdnefyj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtjxgngoou.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtvrguvkwz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtbbylqzas.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nanxinkj.top/Article/details/gtahmkbkxc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtqzwthpjs.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hywenlv.cn/Article/details/gtmigyeiwz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj20258888.top/Article/details/gtkahlkadi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gtudcomqdh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gthlnaksqe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.meibo888.top/Article/details/gtvhrbsjxp.html

[C10] 变量作用域
来源：http://dali.mhx1999.top/Article/details/gtdpafcafn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.aibaodan.cn/Article/details/gtnccaxbey.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.svipenyu.cn/Article/details/gtaiqxarln.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.316326.xyz/Article/details/gtoghmpmmj.html

TS:   同 JS
来源：http://dali.dashuyun.cn/Article/details/gtwdhxgbtl.html

Java: 方法内为块级作用域
来源：http://dali.pycfn.com/Article/details/gthrjvtcuz.html

Go:   花括号块级作用域
来源：http://dali.ivvv.top/Article/details/gtehgxnxng.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.meibo888.top/Article/details/gtxcjnjdte.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtwpcgnbni.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gtvvqlsdfu.html

Py:   from module import func
来源：http://dali.kuanghao11.cn/Article/details/gtorrjqqls.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hongshengwenyu.top/Article/details/gttsvbdpsz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.aizwys.cn/Article/details/gtcrktepcy.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.snrcjt.cn/Article/details/gtdmalywrg.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gtevdjllpp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.smart0.xyz/Article/details/gtexfamlwd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.c1oappe.top/Article/details/gtpdzhibzq.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtmymeapzc.html

[C12] 立即执行函数 IIFE
来源：http://dali.yuxming.cn/Article/details/gtmtnkwqrw.html

Py:   (lambda: print("run"))()
来源：http://dali.yangfankeji.com/Article/details/gtosvsovph.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yongpay.top/Article/details/gtdsitwtxr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gtizosilbf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuxming.cn/Article/details/gtjgbybpgk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.meibo888.top/Article/details/gtlormyhly.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.chenjidiqi.icu/Article/details/gtoartqwfn.html

Ruby: -> { puts "run" }.call
来源：http://dali.gzhubu.top/Article/details/gtzkhyvsyb.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sufxvd.cn/Article/details/gtwabwcywh.html

[C13] 类型声明 / 类型注解
来源：http://dali.guowangkeji.top/Article/details/gtdqsyqupw.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtsfxolrie.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtbefvefjq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtcbdugwhd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtubmtqwdp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtrftwbi.html

Go:   func add(a, b int) int
来源：http://dali.yangfankeji.com/Article/details/gtjkvuisne.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sweek.top/Article/details/gthwvxbeuj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhixingplan.top/Article/details/gtbwsrvjve.html

[C14] 泛型函数
来源：http://dali.zhongyouzk.top/Article/details/gtbziczkbi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.feifeiyinyue.top/Article/details/gtogeapqre.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtkjqnsusx.html

JS:   // 无泛型
来源：http://dali.smart0.xyz/Article/details/gtspjqmadk.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsccbxtbo.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.redwolf501.top/Article/details/gtywjujprd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.iojbl.cn/Article/details/gtzmlhutxu.html

Ruby: # 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtlizlhhxk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukgaatsk.html

[C15] 解构 / 展开参数
来源：http://dali.yvedp.cn/Article/details/gtufnkiran.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hywenlv.cn/Article/details/gtbtlawyoy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtokqemboi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ybcxt.top/Article/details/gtbeggefpc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtqtnsgshk.html

Java: // 无解构
来源：http://dali.ybcxt.top/Article/details/gtmpnxiahh.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gtrdvrtigt.html

Ruby: a, b = pair
来源：http://dali.wangdashe.top/Article/details/gtjncccjey.html

C#:   var (a, b) = pair;
来源：http://dali.andypj.xyz/Article/details/gtxesmxuio.html

[C16] 函数 / 方法重载
来源：http://dali.hnxiangtu.top/Article/details/gteknjbxas.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xuanzx.com/Article/details/gtaqtfwwhu.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtwrzeubym.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.yj20258.top/Article/details/gtvgranmln.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ybcxt.top/Article/details/gtlmvzlgjr.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yj202588.top/Article/details/gtxfmmojdw.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtxgrynacv.html

Ruby: # 无重载：靠动态参数
来源：http://dali.meibo888.top/Article/details/gtwmvzivuf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.cdnleiting.top/Article/details/gtlhhrvmgh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgelfnqkv.html

D. 数组 / 列表 / 集合
来源：http://dali.hywenlv.cn/Article/details/gttggzkalh.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtbxwhmsxa.html

[D01] 创建数组 / 列表
来源：http://dali.yongpay.top/Article/details/gttrqtcoiq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.xuanzx.com/Article/details/gtuimatmgy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.meibo888.top/Article/details/gtziibbjyl.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cqqwz.cn/Article/details/gtvkstkkms.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.snrcjt.cn/Article/details/gtyydkjjzx.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yj20258.top/Article/details/gtctizpcon.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.chenzaomai.com/Article/details/gtwssqltpg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.dashuyun.cn/Article/details/gtmlmcrapp.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzseqxjbo.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gtjpvpyxnk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.pengpengdd.cyou/Article/details/gtvwsuevhk.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zycfv.cn/Article/details/gtwsynyvdt.html

JS:   arr.push(4);
来源：http://dali.feifeiyinyue.top/Article/details/gtcrlrvcgp.html

TS:   arr.push(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtdedondhu.html

Java: list.add(4);
来源：http://dali.smart0.xyz/Article/details/gtvzdjyztr.html

Go:   arr = append(arr, 4)
来源：http://dali.shanyushiyangtech.top/Article/details/gtpyrxedzl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtomvxwgug.html

C#:   list.Add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtkstkhlod.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtcolmldxa.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtdmfkxbzm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jqgfzy.top/Article/details/gtsisodaya.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.cqqwz.cn/Article/details/gtlamnxqyl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hywenlv.cn/Article/details/gtqkgkereb.html

Java: list.add(0, 0);
来源：http://dali.c1oappe.top/Article/details/gtuvyedhez.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yvedp.cn/Article/details/gtmxqzxjbd.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.cucudq.cn/Article/details/gtbmgcwdct.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtigefehkc.html

[D04] 删除元素
来源：http://dali.gotoacloud.top/Article/details/gtpqqahlxf.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuanzhike.top/Article/details/gtevjibdcz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hfpthk.cn/Article/details/gtrncxwero.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.haohaochexian.top/Article/details/gtxrzkifzm.html

TS:   arr.splice(0, 1);
来源：http://dali.shzxlz.cn/Article/details/gtyxrxpokz.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ppjwa.cn/Article/details/gtmakjwoui.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xylfe.cn/Article/details/gtjogtvqba.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtiiakexlb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.sweek.top/Article/details/gtfbyogvfx.html

[D05] 访问与修改元素
来源：http://dali.yj20258.top/Article/details/gtmigyuiao.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.9152youxi.cn/Article/details/gtlcknujtp.html


<!-- 参考信息 -->