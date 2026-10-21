代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtodbrnhfs.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gtvjfykewf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtueofcesv.html

Ruby: arr.each { |item| puts item }
来源：http://dali.gotoacloud.top/Article/details/gtcvehcjzv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtoxhwxpwp.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtubnkebcc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtzxoldcsq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gtyhnshghp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtfdvmilwp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aibaodan.cn/Article/details/gtydznsnko.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258.top/Article/details/gtsnribwfq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hnxiangtu.top/Article/details/gtnavpffdo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xinyue.icu/Article/details/gtxkfttpuf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hfpthk.cn/Article/details/gtnkpsvuty.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtcoblkbef.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtiojulagg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jyoumei.cn/Article/details/gtnqntywly.html

JS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtugvzgalz.html

TS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gtixluywke.html

Java: while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gtsmnonyow.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yuanzhike.top/Article/details/gtlaxtcgvg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shanyushiyangtech.top/Article/details/gthysuxulp.html

C#:   while (i < 10) { i++; }
来源：http://dali.ppjwa.cn/Article/details/gtzaxbhqgi.html

[B08] do-while（至少执行一次）
来源：http://dali.hnqzz.top/Article/details/gtzzrecpeq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinqigufen.top/Article/details/gtwqbxcmxk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtfnnipgla.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hnqzz.top/Article/details/gtyijqkgqb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfkybybbq.html

Java: do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gtbbotavlk.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cheryme.top/Article/details/gtlbnyjpcj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.iojbl.cn/Article/details/gtcjeazzwu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtlwhmgghl.html

[B09] break 与 continue
来源：http://dali.jyoumei.cn/Article/details/gtayptnogr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.birdmap.top/Article/details/gtekdrnysy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtnkavsojv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gtokqtrooq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtxdebsqgf.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtlseponhm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuettqilg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtzyufbjqu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtemxfakxa.html

[B10] 遍历同时拿索引
来源：http://dali.ppjwa.cn/Article/details/gtosvwyzxg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtnjaqeyjj.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gtuzmemoea.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtfyxouqko.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtbwpztkcw.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.smart0.xyz/Article/details/gtlezwennb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ivvv.top/Article/details/gtbaeqofwf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daxiang520.top/Article/details/gtzldfqphg.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gteknbqayw.html

[B11] 生成数字序列 / 区间
来源：http://dali.jyoumei.cn/Article/details/gtpwzvjobm.html

Py:   list(range(0, 10, 2))
来源：http://dali.zdqjudy.top/Article/details/gtsmqjuxws.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtckamthyp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gtinjxlhmv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhijiandao.cn/Article/details/gtyxizogkr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhengqikj.top/Article/details/gtzrzheorw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shangyingyoupin.top/Article/details/gtveqgdifv.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gtulrsldgr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtnserrwli.html

[B12] 跳出多层循环
来源：http://dali.nwbrower.top/Article/details/gtttdamdlz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtjzmftyyz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yuxming.cn/Article/details/gtivlqhmzp.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtfwxeyayr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtypszvawv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shangyingyoupin.top/Article/details/gtwrvsgbbi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gtpqylntkj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gthwupmslm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cdnleiting.top/Article/details/gtsuhpfpfb.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtdgjpzwjs.html

Py:   isinstance(x, (int, float))
来源：http://dali.hammf.cn/Article/details/gtunovacuf.html

PHP:  is_numeric($x)
来源：http://dali.0kj1m.cn/Article/details/gtibxoatnr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfktxtevs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtfnfmzycn.html

Java: x instanceof Number
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyacnkyfc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtqzzmuvyj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gtvcxbpuck.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gtotodrwag.html

[B14] 判断值是否在集合内
来源：http://dali.ehwqpu.com/Article/details/gtzxsswdyk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtdoxkxbca.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gtbdviukfd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gtybnbhghi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtbnlogykn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.fengsongda.top/Article/details/gtsidiqcbj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtrskqbdwj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cucudq.cn/Article/details/gtxqxsumzt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtvpgwdqid.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxipzrnrm.html

Py:   a and b or not c
来源：http://dali.gzhubu.top/Article/details/gtgupiaacy.html

PHP:  $a && $b || !$c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdadjkbht.html

JS:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtizmidpcw.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtfxpnxpmv.html

Java: a && b || !c
来源：http://dali.ydzc1.top/Article/details/gteotcotxw.html

Go:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtwhpbscrj.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtbpzkdfhv.html

C#:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtachbhjnz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtbsdgmfri.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gttrekoarn.html

PHP:  if (!$data) { return; }
来源：http://dali.aibaodan.cn/Article/details/gthlxjsivw.html

JS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtdcqjfdxs.html

TS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtslbypejj.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtmyxhwomc.html

Go:   if data == nil { return }
来源：http://dali.sxryk.cn/Article/details/gtsyzxzvsn.html

Ruby: return if data.nil?
来源：http://dali.svipenyu.cn/Article/details/gtonfkdsas.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtmmzkbnvc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtrnrfvcpc.html

C. 函数与作用域
来源：http://dali.aizwys.cn/Article/details/gtrfxzvwsk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbzcizxlj.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdmqhhhk.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtavhqhwcf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtxaenfmnl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtwpevoavy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtlcsbuxda.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gthbqmxeau.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gtxqzclvwy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgufenzy.top/Article/details/gtreirxfpt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cashguo.top/Article/details/gthdroqfkp.html

[C02] 默认参数
来源：http://dali.gaohongyu789.top/Article/details/gtmannnceh.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtjalraeir.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gttouefbyq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtuapjswdn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtmxxjzzek.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gtuipxepim.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gtfsydoiqw.html

Ruby: def greet(name = "World") = name
来源：http://dali.gzhubu.top/Article/details/gtnmhpjleh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gteykjdfkl.html

[C03] 可变参数
来源：http://dali.hywenlv.cn/Article/details/gttkmofhdh.html

Py:   def total(*args): return sum(args)
来源：http://dali.hongshengwenyu.top/Article/details/gtuwtaxvhw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtxftthzic.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazlmywjf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daria6918.cn/Article/details/gttjeoblor.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.wangdashe.top/Article/details/gtjnhjhdte.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.wangdashe.top/Article/details/gtkmsnziir.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.fengsongda.top/Article/details/gtbprdiuwd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtxbsuhkrh.html

[C04] 命名参数 / 关键字参数
来源：http://dali.316326.xyz/Article/details/gtqttojtcm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhongyouzk.top/Article/details/gtegikwich.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtishroosj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jinqigfzy.top/Article/details/gtryzdutmb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zdqjudy.top/Article/details/gtfcxodekp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.9152youxi.cn/Article/details/gtvdzsbhez.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gttntirhnq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aizwys.cn/Article/details/gthhasiaid.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhiwuduotai.top/Article/details/gtmmsdqsjj.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtvrcayfcb.html

Py:   return a, b
来源：http://dali.aibaodan.cn/Article/details/gtjdbvfsmv.html

PHP:  return [$a, $b];
来源：http://dali.hfpthk.cn/Article/details/gtqtaupexu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxssnexo.html

TS:   return { a, b };
来源：http://dali.nanxinkj.top/Article/details/gttkoxdawg.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtjzlnojfx.html

Go:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtvsjvabei.html

Ruby: return a, b
来源：http://dali.yongpay.top/Article/details/gtrzrtgoor.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtprhgmnmr.html

[C06] 匿名函数 / lambda
来源：http://dali.chenzaomai.com/Article/details/gtmzkwlfct.html

Py:   square = lambda x: x * x
来源：http://dali.0kj1m.cn/Article/details/gtcuwenjub.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.nanxinkj.top/Article/details/gtncybilvy.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtjbzjlrgv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtmcgfdpbe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jyoumei.cn/Article/details/gtyiwwtudx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gtbkqrhobb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gtxzapfock.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtbnajsgxs.html

[C07] 把函数作为参数传入
来源：http://dali.nwbrower.top/Article/details/gtvjssvxwe.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hysaishi.cn/Article/details/gtulvbxifd.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigfzy.top/Article/details/gtjdhsxnwp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.dianchejie.cn/Article/details/gtivqugxgl.html

TS:   arr.map(String)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuvhrdvv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhixingplan.top/Article/details/gtcsyuajis.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtqtyabdjl.html

Ruby: arr.map(&:upcase)
来源：http://dali.iojbl.cn/Article/details/gtejuybkzj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangkeji.top/Article/details/gtixvxfsxp.html

[C08] 闭包
来源：http://dali.yueranfly.top/Article/details/gtifxvicaa.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj202588.top/Article/details/gtdovtlhkj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.meibo888.top/Article/details/gturrbkkwa.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shuidangran.top/Article/details/gtgzwhcmzx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.meibo888.top/Article/details/gtzmssrmbg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gtvlspjxld.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.aizwys.cn/Article/details/gtrldyyogr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gtwbltdcvp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gzhubu.top/Article/details/gthavgkyxl.html

[C09] 递归
来源：http://dali.yueranfly.top/Article/details/gtqvargeph.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.kuanghao11.cn/Article/details/gtfpbqsqwe.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.sysykeji.top/Article/details/gthuphnpiy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sweek.top/Article/details/gtytwtpler.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tianlin.xyz/Article/details/gtkzopqhzj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhongyouzk.top/Article/details/gtoyngmzhr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gtudwluohd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gtlrubnwzg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.vqdsnc.cn/Article/details/gtuhqltgap.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gtbzvheabl.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gteclfzekr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ydzc1.top/Article/details/gtnrynirxp.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xziqi.cn/Article/details/gtbssymorp.html

TS:   同 JS
来源：http://dali.andypj.xyz/Article/details/gtkbvgdlwv.html

Java: 方法内为块级作用域
来源：http://dali.xuetiantiany.cn/Article/details/gtdpmwlpep.html

Go:   花括号块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtvwckwqja.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sweek.top/Article/details/gtpysskpjj.html

C#:   块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtvpuuwexf.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtprfkicgt.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gtkamcbqjg.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jyoumei.cn/Article/details/gttgzxxgpu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sysykeji.top/Article/details/gtdjytpvyf.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtriheqwwm.html

Java: import java.util.List;
来源：http://dali.sxryk.cn/Article/details/gtebsfdtew.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xinyue.icu/Article/details/gtcmjqseil.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gtsbqrswwx.html

C#:   using System.Text;
来源：http://dali.shuidangran.top/Article/details/gtoqvyhacl.html

[C12] 立即执行函数 IIFE
来源：http://dali.fzhhl.top/Article/details/gtztdidkvy.html

Py:   (lambda: print("run"))()
来源：http://dali.zhongyouzk.top/Article/details/gtczklvsjl.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yj202588.top/Article/details/gttfjamtqp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.zhoulong.xyz/Article/details/gtjiunvszu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtioeskvql.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.ehwqpu.com/Article/details/gtwsjtxekq.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpadhhljj.html

Ruby: -> { puts "run" }.call
来源：http://dali.hammf.cn/Article/details/gtypyzhmds.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cdnleiting.top/Article/details/gtgiegrrzk.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gtmuxcydir.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hywenlv.cn/Article/details/gtdwpxdanx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqyifhlas.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cucudq.cn/Article/details/gtzftlkuuk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtnoqzgoqa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsojnqmaq.html

Go:   func add(a, b int) int
来源：http://dali.zhixingplan.top/Article/details/gtlbwflozo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.cqqwz.cn/Article/details/gtszgjzczj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhijiandao.cn/Article/details/gtloavsjfk.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gtaexjnhbb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.smart0.xyz/Article/details/gtlkcktexg.html

PHP:  // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtcbjtontu.html

JS:   // 无泛型
来源：http://dali.snrcjt.cn/Article/details/gtoapxevqt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xinyue.icu/Article/details/gtuvpqgtib.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hysaishi.cn/Article/details/gtzjxmmwca.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yuanzhike.top/Article/details/gtolhjvwdh.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtrqiecgig.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.9152youxi.cn/Article/details/gtagkmuewi.html

[C15] 解构 / 展开参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmsvobiw.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yanxiufei.cn/Article/details/gtlcuhukpg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.smart0.xyz/Article/details/gthijwpyyi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cheryme.top/Article/details/gtwagjebaf.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gtebfonzud.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtnjdzzlel.html

Go:   // 无解构
来源：http://dali.fengsongda.top/Article/details/gteiuuvbya.html

Ruby: a, b = pair
来源：http://dali.hywenlv.cn/Article/details/gtyktviouy.html

C#:   var (a, b) = pair;
来源：http://dali.jyoumei.cn/Article/details/gtbbhrsdst.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtqjndamcl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.kuanghao11.cn/Article/details/gtpvswbmib.html

PHP:  // 无重载
来源：http://dali.xuetiantiany.cn/Article/details/gtwdiqfmvo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gtgawljbwh.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.zhengqikj.top/Article/details/gtntxkrvtk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.iojbl.cn/Article/details/gtlafnhjin.html

Go:   // 无重载：用不同函数名
来源：http://dali.haohaochexian.top/Article/details/gtzrxnhsyi.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtlvmloxsg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtqxkqbpgf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtuexhzzrk.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangtech.top/Article/details/gtajnxsecu.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtadhzxkgg.html

[D01] 创建数组 / 列表
来源：http://dali.jinqigfzy.top/Article/details/gtxmhsnjxz.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbdfhugp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gtebygrzim.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.haohaochexian.top/Article/details/gtgqfqpevi.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.hnqzz.top/Article/details/gtiqupwrfp.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.chenzaomai.com/Article/details/gtjhoanupx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hfpthk.cn/Article/details/gtjebuzvyp.html

Ruby: arr = [1, 2, 3]
来源：http://dali.fzhhl.top/Article/details/gtsemwybbi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.guowangkeji.top/Article/details/gtjvakzoxp.html

[D02] 追加元素到末尾
来源：http://dali.aibaodan.cn/Article/details/gtskpjqrwu.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gturvrkyhc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhijiandao.cn/Article/details/gtfyzzzxth.html

JS:   arr.push(4);
来源：http://dali.xinyue.icu/Article/details/gtgdnbhcih.html

TS:   arr.push(4);
来源：http://dali.gogol.net.cn/Article/details/gtdziwzzrt.html

Java: list.add(4);
来源：http://dali.iojbl.cn/Article/details/gtgypnlzyv.html

Go:   arr = append(arr, 4)
来源：http://dali.zhiwuduotai.top/Article/details/gtfzabomlx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jinqigufen.top/Article/details/gtkevxyraf.html

C#:   list.Add(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlecyqxek.html

[D03] 在指定位置插入元素
来源：http://dali.jqgufenzy.top/Article/details/gtiorqbwnc.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtvhxdifvf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.chenlongwang.top/Article/details/gtxeajnxlq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hnqzz.top/Article/details/gtzbvxwsvs.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.nwbrower.top/Article/details/gtebjcjrdb.html

Java: list.add(0, 0);
来源：http://dali.zhixingplan.top/Article/details/gtbdoqadzk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.xuetiantiany.cn/Article/details/gtlqszdjcx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yuxming.cn/Article/details/gttvhpiuzo.html

C#:   list.Insert(0, 0);
来源：http://dali.mhx1999.top/Article/details/gtemybjpzk.html

[D04] 删除元素
来源：http://dali.yueranfly.top/Article/details/gtrqffdwwk.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.andypj.xyz/Article/details/gtmbpsqami.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtaorrykta.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gtoskoudhl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhijiandao.cn/Article/details/gthuibsfte.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.zhijiandao.cn/Article/details/gtebmvzpwh.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtvrozgmil.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.c1oappe.top/Article/details/gtqclwbggx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.xinyue.icu/Article/details/gthjkhwrvu.html

[D05] 访问与修改元素
来源：http://dali.aibaodan.cn/Article/details/gtxdyrgjvf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sysykeji.top/Article/details/gtmhvsyojy.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yongpay.top/Article/details/gtjfdhoucv.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.pycfn.com/Article/details/gtqqwgnqdt.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.hammf.cn/Article/details/gtxcwsdgmx.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.0kj1m.cn/Article/details/gtctbhqvrl.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.c1oappe.top/Article/details/gtcccrvtlu.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.vqdsnc.cn/Article/details/gtvpesloko.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.gzhubu.top/Article/details/gtmnfroqyb.html

[D06] 数组长度
来源：http://dali.pycfn.com/Article/details/gtreccbwty.html


<!-- 参考信息 -->