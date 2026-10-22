代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtitqyoqhp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.chenlongwang.top/Article/details/gtpkudihgv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.pycfn.com/Article/details/gtnfrbygse.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gtantgtgrq.html

[B05] 遍历数组 / 列表
来源：http://dali.aizwys.cn/Article/details/gttnhyhtlv.html

Py:   for item in arr: print(item)
来源：http://dali.birdmap.top/Article/details/gtruysxgiv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gtdrdyiwwl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gtadjevuzr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtxgvcywgl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtfaidijrx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.andypj.xyz/Article/details/gtcicvfgyd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gtnwnrjbdj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gogol.net.cn/Article/details/gtimayjrdf.html

[B06] 遍历字典 / 对象
来源：http://dali.zhengqikj.top/Article/details/gtwrmeyhhw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtxnhhhsos.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtfbqrpzts.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xziqi.cn/Article/details/gtzdikwhfz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gttahenrkc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gttcfxaftv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnqzz.top/Article/details/gtlqkqtrfo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gtfqvpsepf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.wangdashe.top/Article/details/gtyfcqqzve.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gtbyxqkess.html

Py:   while i < 10: i += 1
来源：http://dali.hfpthk.cn/Article/details/gtefpkmtix.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinqigufen.top/Article/details/gtfhnqiiak.html

JS:   while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gtmawruodr.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtxeflmjid.html

Java: while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtvxwmmfsy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nwbrower.top/Article/details/gttkulajol.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gthcmcnqhq.html

C#:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gteakcfaug.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gthgtpuutf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shzxlz.cn/Article/details/gtzjnqkovy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtewnclerq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtitjvjjvv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtiezriica.html

Java: do { i++; } while (i < 10);
来源：http://dali.hywenlv.cn/Article/details/gtrmurjqqn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hammf.cn/Article/details/gtarokwojm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtdmxreqsb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtfoispnsc.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gtwemihivm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zdqjudy.top/Article/details/gtgszjuito.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtwtellxve.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtiowresbe.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtesfhcbmn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtgikejqij.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtbpunrnqy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gtxwvzluzm.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtclbhymzv.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigufen.top/Article/details/gtjnagoxcr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtxloglznp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhongyouzk.top/Article/details/gtznucwwnv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtepuhsksy.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gtbsudencl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gthpkwhcyo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gtpodrssnp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gtgeojqrkc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jqgufenzy.top/Article/details/gtwqylsijd.html

[B11] 生成数字序列 / 区间
来源：http://dali.guowangkeji.top/Article/details/gtlfvpvylk.html

Py:   list(range(0, 10, 2))
来源：http://dali.iojbl.cn/Article/details/gtgovdenpi.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtyctrzvaz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gtzbslfqdt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtaewwvncz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ppjwa.cn/Article/details/gtcahmaeog.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.havefunace.top/Article/details/gtizkmphkq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.nanxuanxn.top/Article/details/gtyrqdjbjz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtnbqzglxe.html

[B12] 跳出多层循环
来源：http://dali.shzxlz.cn/Article/details/gtuyzeivui.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtlydwvbqq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtpkfnpsge.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtknoizbin.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtopmjknfi.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtuzpkykgv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gtsukglrot.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jyoumei.cn/Article/details/gtqdgqiqwu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtcltcdhef.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtsjhxjwwt.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgfzy.top/Article/details/gttpnqgwjl.html

PHP:  is_numeric($x)
来源：http://dali.yangfankeji.com/Article/details/gtnqnasvmy.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gttljsnyrl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hammf.cn/Article/details/gtsevbbbsc.html

Java: x instanceof Number
来源：http://dali.hnxiangtu.top/Article/details/gtfcdfvckl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258.top/Article/details/gtweqiqnnn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gtjufrtyut.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevoyloie.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtbeiurnmk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.bjfxy.top/Article/details/gterisrfej.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhengqikj.top/Article/details/gtsevfpheg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtentdzxrm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ehwqpu.com/Article/details/gtoorzqmhl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pengpengdd.cyou/Article/details/gtilnnyhnd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtymeofehy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtxhbiccue.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtuzybxvac.html

[B15] 布尔运算与取反
来源：http://dali.cashguo.top/Article/details/gtdzwnjnes.html

Py:   a and b or not c
来源：http://dali.tanke756.top/Article/details/gtnzcvbode.html

PHP:  $a && $b || !$c
来源：http://dali.jianghu66.top/Article/details/gtwneecovm.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtjpifqxnr.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gttyneqkgf.html

Java: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtcnikwzwr.html

Go:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtoqfikvew.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtodctwmbj.html

C#:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtezdtwivr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtpmfokbcw.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxszyqhnl.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtmtjwitdv.html

JS:   if (!data) return;
来源：http://dali.ybcxt.top/Article/details/gtmogwisrk.html

TS:   if (!data) return;
来源：http://dali.zhixingplan.top/Article/details/gtogdzakus.html

Java: if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtbiprtblo.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtxqmuuzzg.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtalhjxiqp.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtdmpihivr.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtickdaofg.html

C. 函数与作用域
来源：http://dali.0kj1m.cn/Article/details/gtiaauinuw.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtztqckbtb.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gtrpdhvviy.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtdmjuhzxb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtgasvptka.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gthpdmivci.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtlnxogrle.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtzomultuk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cheryme.top/Article/details/gtbagwtqip.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xuetiantiany.cn/Article/details/gtbazkuhim.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtspaojtvv.html

[C02] 默认参数
来源：http://dali.iojbl.cn/Article/details/gtilftbiwq.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gtboldktbi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.birdmap.top/Article/details/gthecctzmk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.havefunace.top/Article/details/gtqghxhwue.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gtiphnamkx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.nanxinkj.top/Article/details/gtyylcabni.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhixingplan.top/Article/details/gtqzyvpozp.html

Ruby: def greet(name = "World") = name
来源：http://dali.cdnleiting.top/Article/details/gtgydrjnil.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnzgunle.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gthliahjxz.html

Py:   def total(*args): return sum(args)
来源：http://dali.yonumen.top/Article/details/gthzttjtgz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gogol.net.cn/Article/details/gtaysaemks.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cashguo.top/Article/details/gtogohnlae.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtrlcrvblg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jyoumei.cn/Article/details/gtirkolqwh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xziqi.cn/Article/details/gtwxhswpxp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmejfkfii.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtrilrfdwe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yvedp.cn/Article/details/gthmedaegj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnxiangtu.top/Article/details/gtvjttsnbj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gthfybvmgx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hywenlv.cn/Article/details/gtsbotsyaa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cdnleiting.top/Article/details/gtvkpcnaej.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtaxtosvjm.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtwdajmzwh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gtfcupgmlt.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtagqaesyk.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gtjfjhmfbx.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtlqxtwzcr.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gtkcczxehs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gttvwwbwfg.html

TS:   return { a, b };
来源：http://dali.cqqwz.cn/Article/details/gtiycexkmk.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cheryme.top/Article/details/gtuogxsivd.html

Go:   return a, b
来源：http://dali.yvedp.cn/Article/details/gtmljsieeb.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtaggeqwep.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.gotoacloud.top/Article/details/gtjnhrdqyg.html

[C06] 匿名函数 / lambda
来源：http://dali.yongpay.top/Article/details/gtknqrknmm.html

Py:   square = lambda x: x * x
来源：http://dali.yonumen.top/Article/details/gtoctqdooa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtnwqjezwg.html

JS:   const square = x => x * x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqpoeghbr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtrzcawmvh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.redwolf501.top/Article/details/gtrjljqlmo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gteecgtngu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangdashe.top/Article/details/gtfhtzovqq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gtjibbodfa.html

[C07] 把函数作为参数传入
来源：http://dali.smart0.xyz/Article/details/gtcmufmynt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.cucudq.cn/Article/details/gtseovpyve.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gtpovagtoe.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zdqjudy.top/Article/details/gttvlxsjei.html

TS:   arr.map(String)
来源：http://dali.haohaochexian.top/Article/details/gtgtxttumt.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gtcnwqvrdp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.meibo888.top/Article/details/gthfemaxpq.html

Ruby: arr.map(&:upcase)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwtthezbb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtuuxvxinh.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtjrdhtdva.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.iojbl.cn/Article/details/gtdlnlrpqq.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sufxvd.cn/Article/details/gtgzerdzbf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtmraoqljx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jqgufenzy.top/Article/details/gtlcboeovj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxhxrrtgb.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtmmnnywyi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.daria6918.cn/Article/details/gtmprknbwi.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtiekggwhw.html

[C09] 递归
来源：http://dali.c1oappe.top/Article/details/gtgittmfic.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yj20258888.top/Article/details/gtmxhsfoag.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtjksjyqch.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.pycfn.com/Article/details/gtlfmohrqe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtbikfbroj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.redwolf501.top/Article/details/gtyxdcyftx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gogol.net.cn/Article/details/gtrcervdax.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sweek.top/Article/details/gttcnywtgd.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.haohaochexian.top/Article/details/gtrrhgamyt.html

[C10] 变量作用域
来源：http://dali.9152youxi.cn/Article/details/gtcrkavnkq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.shanyushiyangtech.top/Article/details/gtobvpdsfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtwchkixmp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhengqikj.top/Article/details/gtwavwhdhq.html

TS:   同 JS
来源：http://dali.meibo888.top/Article/details/gtjsjjxpwp.html

Java: 方法内为块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtvuyuxnpy.html

Go:   花括号块级作用域
来源：http://dali.tian-w.cn/Article/details/gttzarfkwo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinqigufen.top/Article/details/gtyvttcuej.html

C#:   块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtzihrvyxd.html

[C11] 模块导入与导出
来源：http://dali.meibo888.top/Article/details/gtlzduxdau.html

Py:   from module import func
来源：http://dali.ybcxt.top/Article/details/gtleyyxtyc.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.0kj1m.cn/Article/details/gtodoiqnot.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.svipenyu.cn/Article/details/gtspkvtacs.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yonumen.top/Article/details/gtppeepffj.html

Java: import java.util.List;
来源：http://dali.ehwqpu.com/Article/details/gtwtvmulth.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hywenlv.cn/Article/details/gtztzdwzlk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenjidiqi.icu/Article/details/gtcziyqono.html

C#:   using System.Text;
来源：http://dali.cheryme.top/Article/details/gtnlhgybfk.html

[C12] 立即执行函数 IIFE
来源：http://dali.svipenyu.cn/Article/details/gtclwnqjqp.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gtjtwlipqx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.birdmap.top/Article/details/gtzmnhfxso.html

JS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtzwbmlopd.html

TS:   (() => { console.log("run"); })();
来源：http://dali.vqdsnc.cn/Article/details/gtdwjlmrul.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ybcxt.top/Article/details/gtkwmdaies.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.redwolf501.top/Article/details/gtsnusncvj.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtpyotddhd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ivvv.top/Article/details/gtogjefzhr.html

[C13] 类型声明 / 类型注解
来源：http://dali.ivvv.top/Article/details/gtmwsfnecy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.mhx1999.top/Article/details/gtodyzkhnq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gttklfkdnz.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jqgufenzy.top/Article/details/gtmeagwzei.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtilxswuym.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtyzjwtctp.html

Go:   func add(a, b int) int
来源：http://dali.yueranfly.top/Article/details/gtiemsmkda.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hnxiangtu.top/Article/details/gtfwwltvap.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.iojbl.cn/Article/details/gtkoihhkcz.html

[C14] 泛型函数
来源：http://dali.guannengcc.top/Article/details/gtbbugkaus.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.guannengcc.top/Article/details/gtwcqyraie.html

PHP:  // 无泛型
来源：http://dali.cheryme.top/Article/details/gtxwfkndhz.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gtencdvthp.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhongyouzk.top/Article/details/gtvpouunab.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hongshengwenyu.top/Article/details/gtbscnkxjo.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.birdmap.top/Article/details/gtlxrxasrh.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtplcofzxp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhongyouzk.top/Article/details/gtngqwhzwa.html

[C15] 解构 / 展开参数
来源：http://dali.cqqwz.cn/Article/details/gtbfctrmin.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.chenzaomai.com/Article/details/gtzciartpk.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jiagoushi.top/Article/details/gtsofillgi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xuanzx.com/Article/details/gtylmgvvth.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jiagoushi.top/Article/details/gtvshzrmhv.html

Java: // 无解构
来源：http://dali.shangyingyoupin.top/Article/details/gtchvkzcce.html

Go:   // 无解构
来源：http://dali.yj20258888.top/Article/details/gthqldvyxo.html

Ruby: a, b = pair
来源：http://dali.tanke756.top/Article/details/gtmirsngxm.html

C#:   var (a, b) = pair;
来源：http://dali.bjfxy.top/Article/details/gtxgbrkmka.html

[C16] 函数 / 方法重载
来源：http://dali.xinyue.icu/Article/details/gteivasius.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.ydzc1.top/Article/details/gtndpulbmb.html

PHP:  // 无重载
来源：http://dali.meibo888.top/Article/details/gtxabiogfy.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tian-w.cn/Article/details/gtjcoldqha.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.pycfn.com/Article/details/gtoarukxdm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.birdmap.top/Article/details/gtixpjhwgc.html

Go:   // 无重载：用不同函数名
来源：http://dali.xuetiantiany.cn/Article/details/gtxklxbkml.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zdqjudy.top/Article/details/gtkcjcwnyz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.chenzaomai.com/Article/details/gtrhgkypdf.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtfidvjsog.html

D. 数组 / 列表 / 集合
来源：http://dali.sxryk.cn/Article/details/gtbulvsmxo.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfrjimcnx.html

[D01] 创建数组 / 列表
来源：http://dali.hfpthk.cn/Article/details/gtklxeitgf.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.birdmap.top/Article/details/gtymdrzneh.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.wangdashe.top/Article/details/gtpfrvpave.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gotoacloud.top/Article/details/gtcjfoigyr.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.smart0.xyz/Article/details/gtknvgatmj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtfmijegpx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.tianlin.xyz/Article/details/gtckkktmgt.html

Ruby: arr = [1, 2, 3]
来源：http://dali.redwolf501.top/Article/details/gtmyudzcwb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gtxzvwvlwe.html

[D02] 追加元素到末尾
来源：http://dali.xylfe.cn/Article/details/gtmghrjdgd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.xuanzx.com/Article/details/gtvjwvtube.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.sysykeji.top/Article/details/gthwvtrqzp.html

JS:   arr.push(4);
来源：http://dali.ivvv.top/Article/details/gtzncetolp.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtishfnfph.html

Java: list.add(4);
来源：http://dali.nanxuanxn.top/Article/details/gtpfyuivfh.html

Go:   arr = append(arr, 4)
来源：http://dali.zycfv.cn/Article/details/gthhxxskzg.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaeaeosha.html

C#:   list.Add(4);
来源：http://dali.daxiang520.top/Article/details/gtftwltqfy.html

[D03] 在指定位置插入元素
来源：http://dali.shangyingyoupin.top/Article/details/gtobyiecbo.html

Py:   arr.insert(0, 0)
来源：http://dali.smart0.xyz/Article/details/gtmcrwvlrt.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnktcfzx.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yonumen.top/Article/details/gttgkcesnh.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtkrsubwgl.html

Java: list.add(0, 0);
来源：http://dali.yueranfly.top/Article/details/gtxokxsnpa.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgufenzy.top/Article/details/gtdhmxvnhn.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ydzc1.top/Article/details/gtvysnhfmo.html

C#:   list.Insert(0, 0);
来源：http://dali.yvedp.cn/Article/details/gtomnuddqt.html

[D04] 删除元素
来源：http://dali.hammf.cn/Article/details/gtgvpvkikc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yj20258888.top/Article/details/gttpdrbtzs.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dashuyun.cn/Article/details/gtiyyxrqle.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtofotlbcc.html

TS:   arr.splice(0, 1);
来源：http://dali.yanxiufei.cn/Article/details/gtpirdzezf.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.ivvv.top/Article/details/gtdyesjade.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnqzz.top/Article/details/gtggslwhcn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.tian-w.cn/Article/details/gtvrvxdxmn.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhixingplan.top/Article/details/gtccjtjbhr.html

[D05] 访问与修改元素
来源：http://dali.dianchejie.cn/Article/details/gtvzgrbsoz.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.tanke756.top/Article/details/gtpcmvlecx.html


<!-- 参考信息 -->