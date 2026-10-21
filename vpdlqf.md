代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtdxiuiyhc.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtkcbxgkiq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.0kj1m.cn/Article/details/gtycrrgfbj.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigufen.top/Article/details/gtogqdmalf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtudbmfzze.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtbrcuntiw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.0kj1m.cn/Article/details/gteutcroam.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gtqochzpsa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pycfn.com/Article/details/gtkqvywony.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtiehqpqhk.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gtdmljxvbz.html

Py:   while i < 10: i += 1
来源：http://dali.xuanzx.com/Article/details/gthzvsgjlk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gtwqeomabk.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtzxvnxouj.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtpfmtejgz.html

Java: while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtuscnrtbw.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hfpthk.cn/Article/details/gtvqdqgzdw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.dianchejie.cn/Article/details/gtqyzuasxt.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtctnhrjgj.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcmsuhq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtwerrjlmo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zycfv.cn/Article/details/gtlbimmgvi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtofuuvsvk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gthagzaixa.html

Java: do { i++; } while (i < 10);
来源：http://dali.cdnleiting.top/Article/details/gtixlagspw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtqgxgbpkz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tanke756.top/Article/details/gtcrnsanyp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtkrxiumfg.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gtvpdpvwuo.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jqgfzy.top/Article/details/gthyyfdmag.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtzbaxbxxz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gttejtzahx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtyrormehp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtjxkyjeyg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtfpctgsap.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gtwnkibutu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtoqayczlw.html

[B10] 遍历同时拿索引
来源：http://dali.hysaishi.cn/Article/details/gtedwycprd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gtogvlseuq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.quarkkingdee.top/Article/details/gtufthvbxx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnxiangtu.top/Article/details/gtkkjtjvit.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtdzawyjag.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigufen.top/Article/details/gtagmcgqyw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtegrwjhal.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gtxlfntpel.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gtgedarmlf.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtpypczgxv.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gthgdxqaes.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtwppctdee.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gttiznislo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtmwjflhpw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yongpay.top/Article/details/gtzlfgbmoc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtasnzgjxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.iojbl.cn/Article/details/gtuuftniay.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cqqwz.cn/Article/details/gtgljfdktb.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvqitvhpm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.9152youxi.cn/Article/details/gtcrjtoopi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.quarkkingdee.top/Article/details/gtgexzxznw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gtungrmpum.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtcfdtzqzu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtcbdgwdph.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtwbcwmqpy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gtrabomfsd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yj20258888.top/Article/details/gtldubkdsw.html

[B13] 判断是否为数字
来源：http://dali.zhiwuduotai.top/Article/details/gtvhfhogqc.html

Py:   isinstance(x, (int, float))
来源：http://dali.ehwqpu.com/Article/details/gtkiujylex.html

PHP:  is_numeric($x)
来源：http://dali.zycfv.cn/Article/details/gtahqcxudh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsjrthyhk.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtwokxphvv.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtopcxurws.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xuanzx.com/Article/details/gtjrubtkcw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gtvnpadmaz.html

C#:   x is int or double or decimal
来源：http://dali.meibo888.top/Article/details/gtkfctuzdv.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbtcloen.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtgdwfbwon.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sxryk.cn/Article/details/gtriuobjvs.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gtdpcwprrt.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shzxlz.cn/Article/details/gtpuqvjhnu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yvedp.cn/Article/details/gtditfujjf.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gthmfwvpvj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xylfe.cn/Article/details/gtpwikwrra.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fengsongda.top/Article/details/gtwsbzcblc.html

[B15] 布尔运算与取反
来源：http://dali.xuanzx.com/Article/details/gtpwuuawbb.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtpechurmg.html

PHP:  $a && $b || !$c
来源：http://dali.jinghuilouyu.cn/Article/details/gtcmlfohdu.html

JS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqoeexcb.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtysppycsd.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtwayvqxyi.html

Go:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gtkztkibev.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzuenbon.html

C#:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtphkuqtxf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhengqikj.top/Article/details/gtjyaqefrz.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gtbchhhsqr.html

PHP:  if (!$data) { return; }
来源：http://dali.shuidangran.top/Article/details/gtlcenzeiy.html

JS:   if (!data) return;
来源：http://dali.yonumen.top/Article/details/gtjtsvodnw.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gtuhrlhhrs.html

Java: if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtfbclfnlh.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtrfksqtvn.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gthlpkmgnr.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtlyebjhhz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtgxtnqqpu.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtmmxrtuue.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtxycxgtft.html

[C01] 定义函数
来源：http://dali.yueranfly.top/Article/details/gtsxxhkhdq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtbgviqvtx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hysaishi.cn/Article/details/gtzainjksm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtxcwgybfr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtmwqrpqrm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gtkppqqfdq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtnbkmbyzz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.redwolf501.top/Article/details/gtvgwmdrea.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtrbakaozm.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gthptgmfns.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gtlqzfdrqy.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtsgfcuyig.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtoseuhysd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gzhubu.top/Article/details/gtoyorjylb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjbiguix.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cheryme.top/Article/details/gtfwlofyus.html

Ruby: def greet(name = "World") = name
来源：http://dali.ivvv.top/Article/details/gtjenmlpxm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.daria6918.cn/Article/details/gttqotmeky.html

[C03] 可变参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahzoivua.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtmxhdjwbl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtfcyrmpxr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gttbtcalnn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtgxlxtbns.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.nwbrower.top/Article/details/gtourqzdap.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkqckith.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.quarkkingdee.top/Article/details/gthoevgarn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zycfv.cn/Article/details/gtciusiiag.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtgvojttvs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.c1oappe.top/Article/details/gtmhhwhups.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtdcbfuujw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gttygqfady.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuanzhike.top/Article/details/gtchrlrxze.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtpifmfuds.html

Go:   // 无：用配置结构体参数
来源：http://dali.hammf.cn/Article/details/gtpbywmhvw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtnuqmzpzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtsgllwxui.html

[C05] 返回多个值
来源：http://dali.nanxinkj.top/Article/details/gtffhbrvdk.html

Py:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtaqbvhsgl.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjuaaoro.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcytwdiw.html

TS:   return { a, b };
来源：http://dali.mhx1999.top/Article/details/gtqruuoerc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jianghu66.top/Article/details/gttpelbect.html

Go:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtrbtemwdy.html

Ruby: return a, b
来源：http://dali.dashuyun.cn/Article/details/gtdegwnejb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gturbepnam.html

[C06] 匿名函数 / lambda
来源：http://dali.guannengcc.top/Article/details/gtogolxlvj.html

Py:   square = lambda x: x * x
来源：http://dali.quarkkingdee.top/Article/details/gtfkfkdwgz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.chenjidiqi.icu/Article/details/gtbpuyxaaa.html

JS:   const square = x => x * x;
来源：http://dali.sxryk.cn/Article/details/gtkblqeync.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gtkycxmjhz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gtelgnathe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guowangkeji.top/Article/details/gtyugarube.html

Ruby: square = ->(x) { x * x }
来源：http://dali.chenzaomai.com/Article/details/gtrsradrau.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gtrluaruhb.html

[C07] 把函数作为参数传入
来源：http://dali.fengsongda.top/Article/details/gtzvgsmcbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtclcwmkco.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yanxiufei.cn/Article/details/gtworuzaqs.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gtqhshlzuw.html

TS:   arr.map(String)
来源：http://dali.zhoulong.xyz/Article/details/gtfbaefsxb.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ydzc1.top/Article/details/gthzkwohxa.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xylfe.cn/Article/details/gtpndmuwdq.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gtkrcbvuni.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtepzldkjy.html

[C08] 闭包
来源：http://dali.hysaishi.cn/Article/details/gtbkcbcimx.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.redwolf501.top/Article/details/gtgcakhlpr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenzaomai.com/Article/details/gtevrkeius.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gtvncotkoz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtqxparmjm.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hywenlv.cn/Article/details/gtfaukgzwd.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sysykeji.top/Article/details/gtrpgrapvz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtvxhoknsx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cqqwz.cn/Article/details/gttycpcgjo.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtibswsjas.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtyaohpbot.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdmoqpsft.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gthbytgpld.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daxiang520.top/Article/details/gtzsfzpxci.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gtybrihzem.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gteurvwybg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.cucudq.cn/Article/details/gtjcowredx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.wangshuangyany.cn/Article/details/gtthaldkoj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtpqulrxve.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ivvv.top/Article/details/gtywueobms.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtlqrbfxnz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhongyouzk.top/Article/details/gtwprhjoac.html

TS:   同 JS
来源：http://dali.sweek.top/Article/details/gtbfujerik.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtifqdhluo.html

Go:   花括号块级作用域
来源：http://dali.jqgufenzy.top/Article/details/gtzntpzzml.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.redwolf501.top/Article/details/gtzdfpcsir.html

C#:   块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtahrxvuij.html

[C11] 模块导入与导出
来源：http://dali.daxiang520.top/Article/details/gttgbtgyye.html

Py:   from module import func
来源：http://dali.vqdsnc.cn/Article/details/gtyhjjceap.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtdgvezluo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jiagoushi.top/Article/details/gtogmskrgt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gaohongyu789.top/Article/details/gtwomdavuh.html

Java: import java.util.List;
来源：http://dali.cheryme.top/Article/details/gtikxfgbyb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtsnlkoyyi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtynwoxgfg.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gthjrhpvzo.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtwprdzrar.html

Py:   (lambda: print("run"))()
来源：http://dali.hongshengwenyu.top/Article/details/gtcpcijyoo.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvglkmau.html

JS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtwmhufnzl.html

TS:   (() => { console.log("run"); })();
来源：http://dali.316326.xyz/Article/details/gtmkkltocs.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.jyoumei.cn/Article/details/gtmmrptotq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhijiandao.cn/Article/details/gtzldbmqce.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtlheeyaha.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.sysykeji.top/Article/details/gtourbygmb.html

[C13] 类型声明 / 类型注解
来源：http://dali.sufxvd.cn/Article/details/gttmlyihuk.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ybcxt.top/Article/details/gtwawkczai.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinqigfzy.top/Article/details/gtklbryntk.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtzxmqjowy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gtnwruhkhc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtmuvbuvfo.html

Go:   func add(a, b int) int
来源：http://dali.gogol.net.cn/Article/details/gtevvwvrdp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jianghu66.top/Article/details/gtjiafxokc.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.fengsongda.top/Article/details/gtcpnvsldv.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gthztlwhkq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtplderumv.html

PHP:  // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtaaggmwnb.html

JS:   // 无泛型
来源：http://dali.xinyue.icu/Article/details/gthlnoiktt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.sufxvd.cn/Article/details/gtgssnzskd.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jlsjyb.cn/Article/details/gtyykmnlnu.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.guannengcc.top/Article/details/gtdurnxmoe.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gtdnkrzcyz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gtxxnefkym.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigfzy.top/Article/details/gtemtrwuzu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tanke756.top/Article/details/gtwwaxgigi.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gaohongyu789.top/Article/details/gtzlaxmwsp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtuvteangs.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.xylfe.cn/Article/details/gtizctxyya.html

Java: // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtcajahdxk.html

Go:   // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtrdmcgghs.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsdbeuhlh.html

C#:   var (a, b) = pair;
来源：http://dali.gogol.net.cn/Article/details/gtjtpcksjg.html

[C16] 函数 / 方法重载
来源：http://dali.andypj.xyz/Article/details/gtrnnaucii.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gtnmxpclih.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtjudmbyzw.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.c1oappe.top/Article/details/gttbgmedxw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gtckhxwbcv.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.daria6918.cn/Article/details/gtiaybmden.html

Go:   // 无重载：用不同函数名
来源：http://dali.0kj1m.cn/Article/details/gttjsaxxgr.html

Ruby: # 无重载：靠动态参数
来源：http://dali.yuxming.cn/Article/details/gtsboldwvf.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyxjbvxf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtnwvdmdnj.html

D. 数组 / 列表 / 集合
来源：http://dali.birdmap.top/Article/details/gtvohqcdyq.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtcolldjes.html

[D01] 创建数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtbbzlnctl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.aibaodan.cn/Article/details/gtetasdess.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtejmjywbe.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.snrcjt.cn/Article/details/gtyvgfbqwd.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gtrlcnyvpd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yueranfly.top/Article/details/gtkmmfapxx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.pengpengdd.cyou/Article/details/gtmzdkruwa.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtcclpxsxb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtkfkijsmt.html

[D02] 追加元素到末尾
来源：http://dali.yj202588.top/Article/details/gtkzlfsxlu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gtnqxsirsi.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sweek.top/Article/details/gtzrtfmsxb.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksskzele.html

TS:   arr.push(4);
来源：http://dali.hnxiangtu.top/Article/details/gtcwjfdoev.html

Java: list.add(4);
来源：http://dali.hnxiangtu.top/Article/details/gtiuaeksvn.html

Go:   arr = append(arr, 4)
来源：http://dali.meibo888.top/Article/details/gtmvlpygpw.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.daxiang520.top/Article/details/gtdxmzbtzn.html

C#:   list.Add(4);
来源：http://dali.tanke756.top/Article/details/gtegmqlflm.html

[D03] 在指定位置插入元素
来源：http://dali.gogol.net.cn/Article/details/gtzwtmyoip.html

Py:   arr.insert(0, 0)
来源：http://dali.haohaochexian.top/Article/details/gtezoktgvx.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.nanxuanxn.top/Article/details/gtllqndnls.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.meibo888.top/Article/details/gtylzzmofm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtfbhgbali.html

Java: list.add(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzdcyfnxv.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.snrcjt.cn/Article/details/gtufnczaij.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhoulong.xyz/Article/details/gtizoxdfpg.html

C#:   list.Insert(0, 0);
来源：http://dali.redwolf501.top/Article/details/gtdtalpvdc.html

[D04] 删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtyccpfbcm.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumwugkig.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.snrcjt.cn/Article/details/gtisjgzdxw.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtfebpvyqb.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwpvqndl.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ybcxt.top/Article/details/gttblmwrtt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sweek.top/Article/details/gteanmkndo.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtosixmfon.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hysaishi.cn/Article/details/gtiketlska.html

[D05] 访问与修改元素
来源：http://dali.iojbl.cn/Article/details/gtwptmoqvz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.daria6918.cn/Article/details/gtfzspfqbc.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hfpthk.cn/Article/details/gtiywpqusn.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj202588.top/Article/details/gtjmcafksl.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinqigfzy.top/Article/details/gtsvdstxdx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xylfe.cn/Article/details/gtksianeyv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtlcfnbmcg.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cucudq.cn/Article/details/gtihnvpqvj.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gtnyftfmgi.html

[D06] 数组长度
来源：http://dali.mhx1999.top/Article/details/gteacxefxu.html

Py:   len(arr)
来源：http://dali.jlsjyb.cn/Article/details/gtxvukiyzz.html

PHP:  count($arr);
来源：http://dali.ehwqpu.com/Article/details/gtbikodusa.html

JS:   arr.length
来源：http://dali.dashuyun.cn/Article/details/gtrllmuaoi.html

TS:   arr.length
来源：http://dali.haohaochexian.top/Article/details/gtpjkrbmuv.html


<!-- 参考信息 -->