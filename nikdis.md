代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.cashguo.top/Article/details/gtqqrefbql.html

Py:   for item in arr: print(item)
来源：http://dali.hywenlv.cn/Article/details/gttodybhoq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.feifeiyinyue.top/Article/details/gtmkkahmom.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.316326.xyz/Article/details/gthxhfzhsi.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhixingplan.top/Article/details/gtheujievn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinqigfzy.top/Article/details/gttrvpvnae.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhengqikj.top/Article/details/gtggltwcco.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhixingplan.top/Article/details/gtuqvpuqwm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jyoumei.cn/Article/details/gtcejuhppe.html

[B06] 遍历字典 / 对象
来源：http://dali.quarkkingdee.top/Article/details/gtnzbrcvhj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ivvv.top/Article/details/gtdcrzpknf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gtepdoemzu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtmqsafbvv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtktstygfu.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtuzqidnoy.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gtwoedtbxg.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cdnleiting.top/Article/details/gtzpeoanfi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtwefsfcnb.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtxckswygw.html

Py:   while i < 10: i += 1
来源：http://dali.meibo888.top/Article/details/gtremrxknf.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtlrdtntqr.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gthihalsop.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtvazldhfd.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtuvlsvlwr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daxiang520.top/Article/details/gtoyiriiis.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yj20258.top/Article/details/gtrvjhhnyx.html

C#:   while (i < 10) { i++; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqhixqsax.html

[B08] do-while（至少执行一次）
来源：http://dali.wangshuangyany.cn/Article/details/gtwritjptx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gtbbmdhcvg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtlkzaxzlz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtnccsakva.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gttncctcgr.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtlxanzmoq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gteddfewza.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yongpay.top/Article/details/gtslxrkxyq.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtrskjboxh.html

[B09] break 与 continue
来源：http://dali.gogol.net.cn/Article/details/gtfyixpdba.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hnxiangtu.top/Article/details/gtxfsxnqca.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsumedaxx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvznebcro.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfskfmggj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.mhx1999.top/Article/details/gtcvddjcdm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.316326.xyz/Article/details/gthlovczmn.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gttntrqjid.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtdtxltzin.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gthgqmzeff.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zdqjudy.top/Article/details/gtwhvjltuy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.fengsongda.top/Article/details/gtchluvcgq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtkbfzphsk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtnotxqksr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtmphewitz.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.mhx1999.top/Article/details/gttpvpzewu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjhzwqxic.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.dashuyun.cn/Article/details/gtapmpjcne.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtsjlicict.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gtjfmaxmqz.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtsoajcmgd.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihbtfhgs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtiizjxipe.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhixingplan.top/Article/details/gtlfdpcgjp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtwztuuugk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ehwqpu.com/Article/details/gtunqtiazs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cucudq.cn/Article/details/gteiglfaeg.html

[B12] 跳出多层循环
来源：http://dali.fengsongda.top/Article/details/gtgfgkwsay.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sxryk.cn/Article/details/gtpijexvta.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenjidiqi.icu/Article/details/gtbucfflqd.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtrudxyuqq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenlongwang.top/Article/details/gtibdcbnju.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtcevagtgh.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yj20258888.top/Article/details/gtqlholjvp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtbnpzjcvy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hnqzz.top/Article/details/gtngncwgto.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gtklkmhykd.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtjtsyptxg.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtktsoyrtz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtkhdockfc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenlongwang.top/Article/details/gtsauhtfaa.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtemdflpry.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.tian-w.cn/Article/details/gtpnvkhwsc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.316326.xyz/Article/details/gtlyxznjzr.html

C#:   x is int or double or decimal
来源：http://dali.xuetiantiany.cn/Article/details/gtixvrlepo.html

[B14] 判断值是否在集合内
来源：http://dali.shuidangran.top/Article/details/gtkvrplhmx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sweek.top/Article/details/gtaahpqqlj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.pycfn.com/Article/details/gtxordqfwu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gtsdjfiwvv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gteukkudut.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtdzyuifbm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gtzktmmnwt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtmzfqcmwu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gttzyuopoh.html

[B15] 布尔运算与取反
来源：http://dali.shanyushiyangtech.top/Article/details/gtidjbufzw.html

Py:   a and b or not c
来源：http://dali.mhx1999.top/Article/details/gtjnzptcii.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gthmcoclmj.html

JS:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtdqrnvdlb.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtuidtzgde.html

Java: a && b || !c
来源：http://dali.zhixingplan.top/Article/details/gtzjsukhzl.html

Go:   a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtevrmddqx.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtajxcgpzo.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtftarpgqv.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtmwpcjcpd.html

Py:   if not data: return
来源：http://dali.sweek.top/Article/details/gtijpqjcrq.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwwdfrdt.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtsijrqvnb.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtbtwftawi.html

Java: if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtrdsyobqf.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtydnqaeed.html

Ruby: return if data.nil?
来源：http://dali.wangshuangyany.cn/Article/details/gthheybdmx.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtxstldeot.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtiswtfkth.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtldwxflub.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtqqqhddqm.html

[C01] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtoyikzrqs.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gtlmpydpym.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.birdmap.top/Article/details/gtiwwueihj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gtukomafxv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtjsprnllh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtaqmiacaf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sweek.top/Article/details/gtzuwevgge.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtcybmhram.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtgjqwpigh.html

[C02] 默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtofryhjrz.html

Py:   def greet(name="World"): return name
来源：http://dali.zhongyouzk.top/Article/details/gtytijspxa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jqgfzy.top/Article/details/gtqqgsirpt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtdjhdctmk.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtkexwehbc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xuanzx.com/Article/details/gtrlgocsfe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuetiantiany.cn/Article/details/gtufettxpd.html

Ruby: def greet(name = "World") = name
来源：http://dali.hfpthk.cn/Article/details/gtuxjfewqm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.0kj1m.cn/Article/details/gtfoxkmwlm.html

[C03] 可变参数
来源：http://dali.daria6918.cn/Article/details/gtomiuilxo.html

Py:   def total(*args): return sum(args)
来源：http://dali.chenzaomai.com/Article/details/gtdhprkbim.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hammf.cn/Article/details/gtyeqidnex.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtrdwzeqis.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxinkj.top/Article/details/gtedsgumiq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigufen.top/Article/details/gtcirxwhjk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.fengsongda.top/Article/details/gtvfbgymav.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xinyue.icu/Article/details/gtzuvhbdid.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtjlehwasc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtuxvxaczw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jinqigfzy.top/Article/details/gtmwdecrpm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkblltja.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcmqenwsw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtyjsdkmot.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yuxming.cn/Article/details/gtyokyaudk.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigfzy.top/Article/details/gtujtdbyjd.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gteunhncng.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtigigvyvt.html

[C05] 返回多个值
来源：http://dali.redwolf501.top/Article/details/gtnzkdpjyq.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtoganufkn.html

PHP:  return [$a, $b];
来源：http://dali.mhx1999.top/Article/details/gtloqonrqh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinqigfzy.top/Article/details/gtgxqddtpf.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtpylxcwvz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guannengcc.top/Article/details/gtepfixoin.html

Go:   return a, b
来源：http://dali.hammf.cn/Article/details/gtxqlidjzy.html

Ruby: return a, b
来源：http://dali.cashguo.top/Article/details/gtshrfxppm.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangtech.top/Article/details/gtmykwjvbm.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtwxvozcmf.html

Py:   square = lambda x: x * x
来源：http://dali.chenlongwang.top/Article/details/gtaxuivaxs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258.top/Article/details/gtyjnyensy.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtqmnfjkwf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gtrkqtpkwh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhengqikj.top/Article/details/gtyfgaykme.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtzdpizueq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtdgdtocol.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yonumen.top/Article/details/gtskuslilk.html

[C07] 把函数作为参数传入
来源：http://dali.zycfv.cn/Article/details/gtdikmupsn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gthmtfbruv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtefknrmem.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnxiangtu.top/Article/details/gtzqrnqzvb.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gtqaxszjdc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtfnbbyalq.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.bjfxy.top/Article/details/gtdgovmych.html

Ruby: arr.map(&:upcase)
来源：http://dali.9152youxi.cn/Article/details/gtstemflos.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gtedwgwdli.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gtlwiamwya.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zhongyouzk.top/Article/details/gtgvbguqor.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.birdmap.top/Article/details/gteciwespi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yuxming.cn/Article/details/gtrgowwdqc.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tanke756.top/Article/details/gtxdzrwnhs.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shangyingyoupin.top/Article/details/gturnowlga.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtuauqslwg.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgufenzy.top/Article/details/gtnobpgkys.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtmfhayyow.html

[C09] 递归
来源：http://dali.ppjwa.cn/Article/details/gtfjwnnmbf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.haohaochexian.top/Article/details/gtiubttdto.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.daxiang520.top/Article/details/gtzkqenuhb.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xuanzx.com/Article/details/gtdhpxgrdr.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtsniqzclz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yuanzhike.top/Article/details/gtoqvjfzlv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.aizwys.cn/Article/details/gtlklgttps.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtgiprwhze.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtqxmqtutj.html

[C10] 变量作用域
来源：http://dali.zhijiandao.cn/Article/details/gtnjbqpxri.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxobytwib.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.chenzaomai.com/Article/details/gtzkmgjgkt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtufpazg.html

TS:   同 JS
来源：http://dali.gogol.net.cn/Article/details/gtckcuenzc.html

Java: 方法内为块级作用域
来源：http://dali.smart0.xyz/Article/details/gtprvdeijp.html

Go:   花括号块级作用域
来源：http://dali.daxiang520.top/Article/details/gtfmeywvxz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jianghu66.top/Article/details/gtrpuiriad.html

C#:   块级作用域
来源：http://dali.shzxlz.cn/Article/details/gtouadfziv.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gtbuvrlqgx.html

Py:   from module import func
来源：http://dali.jinqigfzy.top/Article/details/gtyvfilowe.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.guannengcc.top/Article/details/gttwwomekm.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daria6918.cn/Article/details/gtdhqacmkl.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.tian-w.cn/Article/details/gtmgrdlmxm.html

Java: import java.util.List;
来源：http://dali.ydzc1.top/Article/details/gtdiusytxb.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhongyouzk.top/Article/details/gtoytsofta.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuanzx.com/Article/details/gtfokeglwn.html

C#:   using System.Text;
来源：http://dali.zhoulong.xyz/Article/details/gtqkmcfgku.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gthumvnvkc.html

Py:   (lambda: print("run"))()
来源：http://dali.aizwys.cn/Article/details/gtfgagwipq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cheryme.top/Article/details/gteemorgli.html

JS:   (() => { console.log("run"); })();
来源：http://dali.nanxinkj.top/Article/details/gtibqzrerh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gtywvbealj.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtpupupvpw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jqgufenzy.top/Article/details/gtgwyszhyf.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnycnjpup.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtagbdfpaj.html

[C13] 类型声明 / 类型注解
来源：http://dali.feifeiyinyue.top/Article/details/gtidwvmhpz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.kuanghao11.cn/Article/details/gtrwayarbv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.chenzaomai.com/Article/details/gtldautlte.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gtijgdbqpc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.meibo888.top/Article/details/gttmarcejc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtvlcwjeld.html

Go:   func add(a, b int) int
来源：http://dali.aizwys.cn/Article/details/gthksdoama.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yj20258.top/Article/details/gtaafuoyha.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.daria6918.cn/Article/details/gtskvswlcj.html

[C14] 泛型函数
来源：http://dali.haohaochexian.top/Article/details/gtyvwurjwy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.wangshuangyany.cn/Article/details/gtskexzfqp.html

PHP:  // 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtyuajvsbg.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gttzvxaseo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.redwolf501.top/Article/details/gtarncvlmr.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hammf.cn/Article/details/gtqnxyuvny.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenjidiqi.icu/Article/details/gtdgiqfsbe.html

Ruby: # 无泛型
来源：http://dali.gzhubu.top/Article/details/gtcubervqu.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gtkqhapkop.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258888.top/Article/details/gtzndnnzif.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gthdxpxhxq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.c1oappe.top/Article/details/gtxpogqbor.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtlwzetzcz.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtfpadmlei.html

Java: // 无解构
来源：http://dali.yongpay.top/Article/details/gtiajswcoi.html

Go:   // 无解构
来源：http://dali.hnqzz.top/Article/details/gttthzrqjo.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtuexibbyu.html

C#:   var (a, b) = pair;
来源：http://dali.haohaochexian.top/Article/details/gtmzblwyna.html

[C16] 函数 / 方法重载
来源：http://dali.zdqjudy.top/Article/details/gtiqhdsvje.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gotoacloud.top/Article/details/gtbrniygig.html

PHP:  // 无重载
来源：http://dali.ehwqpu.com/Article/details/gtogvtemab.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.sysykeji.top/Article/details/gtvrdnmzzo.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtxpqkxeay.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yangfankeji.com/Article/details/gtdtpjqgcz.html

Go:   // 无重载：用不同函数名
来源：http://dali.snrcjt.cn/Article/details/gtplyveato.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnqzz.top/Article/details/gtllfidufu.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dashuyun.cn/Article/details/gtatkopril.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwxwoupq.html

D. 数组 / 列表 / 集合
来源：http://dali.ehwqpu.com/Article/details/gtwuwklrtw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtynvmhuyv.html

[D01] 创建数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtzxsffbpb.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.daria6918.cn/Article/details/gtdfactanv.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtrpdletkc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gtoipiqvob.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.fzhhl.top/Article/details/gtsjllqrpy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.guannengcc.top/Article/details/gtjxomlepc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hnxiangtu.top/Article/details/gtsicmjdqj.html

Ruby: arr = [1, 2, 3]
来源：http://dali.316326.xyz/Article/details/gtgoztewvl.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.chenjidiqi.icu/Article/details/gtzgifwyaz.html

[D02] 追加元素到末尾
来源：http://dali.havefunace.top/Article/details/gtqswhqmes.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cucudq.cn/Article/details/gtzrpboely.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nwbrower.top/Article/details/gtxrlkimco.html

JS:   arr.push(4);
来源：http://dali.cqqwz.cn/Article/details/gtirszsjsr.html

TS:   arr.push(4);
来源：http://dali.sxryk.cn/Article/details/gtshyrcajx.html

Java: list.add(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtqbundapt.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gtosbhvnpb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtjfwvegyl.html

C#:   list.Add(4);
来源：http://dali.iojbl.cn/Article/details/gtnlwznyza.html

[D03] 在指定位置插入元素
来源：http://dali.chenjidiqi.icu/Article/details/gtowrtqrko.html

Py:   arr.insert(0, 0)
来源：http://dali.zhengqikj.top/Article/details/gtyybvyygg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jiagoushi.top/Article/details/gtlkdpydad.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.vqdsnc.cn/Article/details/gtxrxvprit.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinqigfzy.top/Article/details/gtxjoijbjv.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtbcmwgmor.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yj20258888.top/Article/details/gtppredvry.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gtzqvlkyzp.html

C#:   list.Insert(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtjvedwafz.html

[D04] 删除元素
来源：http://dali.shuidangran.top/Article/details/gtsiehtajb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.tianlin.xyz/Article/details/gtsgxfowwy.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.sysykeji.top/Article/details/gtoslimvtp.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jyoumei.cn/Article/details/gtkynkvkys.html

TS:   arr.splice(0, 1);
来源：http://dali.hfpthk.cn/Article/details/gtqeiymnnd.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jqgfzy.top/Article/details/gteexjdiex.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.c1oappe.top/Article/details/gtipesgijx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.daxiang520.top/Article/details/gtbwuzfbtk.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.birdmap.top/Article/details/gtzqijmdrq.html

[D05] 访问与修改元素
来源：http://dali.jinqigufen.top/Article/details/gtanlyqhiz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.nwbrower.top/Article/details/gtmgiunorg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hnqzz.top/Article/details/gtophqrxue.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.dianchejie.cn/Article/details/gtipwxagko.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsdobdrsa.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.cheryme.top/Article/details/gtuulcxmbb.html


<!-- 参考信息 -->