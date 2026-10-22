代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtrtxfvkve.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gtefymlphx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.pycfn.com/Article/details/gtggujdink.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yanxiufei.cn/Article/details/gtitiliwkz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jqgfzy.top/Article/details/gtzdspcrph.html

[B06] 遍历字典 / 对象
来源：http://dali.cucudq.cn/Article/details/gtryazejkz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinqigfzy.top/Article/details/gteqglwhjd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdlnloafs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgfzy.top/Article/details/gtcbehkbzd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtchjvedwn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nwbrower.top/Article/details/gtkllrxcod.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.snrcjt.cn/Article/details/gtzgggusze.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gotoacloud.top/Article/details/gtcrnviafz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.kuanghao11.cn/Article/details/gtqopjtomj.html

[B07] while 循环
来源：http://dali.sweek.top/Article/details/gtvsgflcjg.html

Py:   while i < 10: i += 1
来源：http://dali.gzhubu.top/Article/details/gtuoivlpgr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yj20258.top/Article/details/gtlweguowl.html

JS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtopvqkcxg.html

TS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtwbpswwce.html

Java: while (i < 10) { i++; }
来源：http://dali.tian-w.cn/Article/details/gtzkyztqaa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gthcyszeyk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtbokkwosf.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtbdmrzoir.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gttucxbsqx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tanke756.top/Article/details/gtwncybxrj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gtfktjcbcc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gttuozpgwc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtilperjyv.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtewzclnyn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yangfankeji.com/Article/details/gtysaavwfz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.hnxiangtu.top/Article/details/gtkoxnpcet.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtsuvfyppt.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtpceysmsh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhongyouzk.top/Article/details/gtixtycche.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkmsmjenv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtudifkyrq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtkwzjzkac.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtlixanpop.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gthsltvhjp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gtgcehvkvd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gtvgftaxbd.html

[B10] 遍历同时拿索引
来源：http://dali.ehwqpu.com/Article/details/gtbyiyxdeh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.shangyingyoupin.top/Article/details/gtfognlphv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.meibo888.top/Article/details/gtvzktfvlx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtpybkjfgu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtlcelirec.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gtxewlcalu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtcipovmgj.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.chenzaomai.com/Article/details/gtkbyfxahj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.iojbl.cn/Article/details/gtqrbegzeb.html

[B11] 生成数字序列 / 区间
来源：http://dali.snrcjt.cn/Article/details/gtknfazngm.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangtech.top/Article/details/gtijnhturv.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258.top/Article/details/gtandgryyn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtsoyzyacc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ivvv.top/Article/details/gtgevlxgxc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtliawlvsl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.9152youxi.cn/Article/details/gtizaebdxl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aibaodan.cn/Article/details/gtemcrcock.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtzvthlzkf.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gttneevpvx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtkbozyosh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhiwuduotai.top/Article/details/gtepwulbht.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtakpfmyic.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtchjagumc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.aizwys.cn/Article/details/gtsepcgmqd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtrfipmxfz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtiiekrnqm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gtdysxqwuk.html

[B13] 判断是否为数字
来源：http://dali.jlsjyb.cn/Article/details/gtpkasmggp.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnxiangtu.top/Article/details/gtrwhogkgf.html

PHP:  is_numeric($x)
来源：http://dali.sxryk.cn/Article/details/gtvmoxpmdw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtwmacbsec.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ybcxt.top/Article/details/gtfeokuopw.html

Java: x instanceof Number
来源：http://dali.fzhhl.top/Article/details/gthpolnygq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.feifeiyinyue.top/Article/details/gthkrjeufh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258.top/Article/details/gtvdjimwne.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gtbrhbopuo.html

[B14] 判断值是否在集合内
来源：http://dali.dashuyun.cn/Article/details/gtupedmpvd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ppjwa.cn/Article/details/gtnaxtuiko.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cucudq.cn/Article/details/gteswgcevp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtvobtxumu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtqunolfrq.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yuxming.cn/Article/details/gtymfpkgin.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtnbpepctg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gtsftbnhsd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbdddhagy.html

[B15] 布尔运算与取反
来源：http://dali.feifeiyinyue.top/Article/details/gtlrvybnkv.html

Py:   a and b or not c
来源：http://dali.sysykeji.top/Article/details/gtbbuojjmx.html

PHP:  $a && $b || !$c
来源：http://dali.xylfe.cn/Article/details/gtepjjdmck.html

JS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtpglcrche.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtgfeltrhk.html

Java: a && b || !c
来源：http://dali.yueranfly.top/Article/details/gtansbovuk.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtwcsjhccv.html

Ruby: a && b || !c
来源：http://dali.iojbl.cn/Article/details/gtdzjfsfds.html

C#:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gtcclsfdpu.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtdwoujpub.html

Py:   if not data: return
来源：http://dali.svipenyu.cn/Article/details/gthzomiajv.html

PHP:  if (!$data) { return; }
来源：http://dali.meibo888.top/Article/details/gtndxomzsc.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtzxlpgnmc.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gtxulwsjiu.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtbxcekohm.html

Go:   if data == nil { return }
来源：http://dali.kuanghao11.cn/Article/details/gtvrnafiay.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtcavifpvy.html

C#:   if (data == null) return;
来源：http://dali.ivvv.top/Article/details/gtfillvorm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtumffxyhg.html

C. 函数与作用域
来源：http://dali.hywenlv.cn/Article/details/gtiffuhlgm.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtvddoevhx.html

[C01] 定义函数
来源：http://dali.meibo888.top/Article/details/gtvopwwtev.html

Py:   def add(a, b): return a + b
来源：http://dali.pycfn.com/Article/details/gtujytkgvn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtrfronnuw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtadiwshcg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtfwybnouf.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtncejijnb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xuanzx.com/Article/details/gteaacoyzn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtmsjhuqtr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtrswziqbf.html

[C02] 默认参数
来源：http://dali.jiagoushi.top/Article/details/gtjvzsfyqt.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gtfwzqdiyk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj202588.top/Article/details/gtlzumbzsi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtpwqsamhh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtcueaixwl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtqbfutzfh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtietsmtaz.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gtnlxdlzgu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pycfn.com/Article/details/gtkhcxxwkf.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtxcqxhrzm.html

Py:   def total(*args): return sum(args)
来源：http://dali.cqqwz.cn/Article/details/gtyjhinxxj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.svipenyu.cn/Article/details/gtjgpnwkog.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtrawqjvpn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtdkptxlpa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnxiangtu.top/Article/details/gtwjcfoura.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gtedtlbbti.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ehwqpu.com/Article/details/gtzqxechkn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hfpthk.cn/Article/details/gtnvdeoihd.html

[C04] 命名参数 / 关键字参数
来源：http://dali.mhx1999.top/Article/details/gtzsjdznma.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hammf.cn/Article/details/gtfvucofuc.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtwxxrjyny.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gthvseyjft.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtlvrpkjtj.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fengsongda.top/Article/details/gtkutsfkwo.html

Go:   // 无：用配置结构体参数
来源：http://dali.jiagoushi.top/Article/details/gtvyauawab.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtbjdsczvi.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtrpxiexfy.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtpexehwql.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gticqplllr.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtdqdtyjxi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtleulwyhp.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtmvcymabj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtgdibjqok.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtdyyouylj.html

Ruby: return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtslnlwkhi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.guowangkeji.top/Article/details/gtvovlqoyl.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxsdefue.html

Py:   square = lambda x: x * x
来源：http://dali.nwbrower.top/Article/details/gteqivjfkb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.iojbl.cn/Article/details/gtquxvklrj.html

JS:   const square = x => x * x;
来源：http://dali.9152youxi.cn/Article/details/gtfytrtufx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtrkuslama.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.dashuyun.cn/Article/details/gtogcjgyvj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sufxvd.cn/Article/details/gtidnqesjz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtyxiujpeg.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gttzuhzils.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtmeimfsvy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.vqdsnc.cn/Article/details/gtivqsfbpn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.smart0.xyz/Article/details/gtzhcxclhv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtxgojgouo.html

TS:   arr.map(String)
来源：http://dali.xuanzx.com/Article/details/gtkotjwlyi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.smart0.xyz/Article/details/gtmtlwywse.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqjjildc.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtucdukftn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yvedp.cn/Article/details/gtmozkipit.html

[C08] 闭包
来源：http://dali.yj20258888.top/Article/details/gtkyiiuvvn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shuidangran.top/Article/details/gtuppskrgr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zdqjudy.top/Article/details/gtbuartfyp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtlfpffnhi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gthdqujpdg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gteehhzaps.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gthrlcsgdq.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yuanzhike.top/Article/details/gtvljqiygq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtqvrgdpts.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtpdddrsgd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtitjgeevb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gtbuirmegx.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gthldthrye.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gthrjdqarg.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nanxuanxn.top/Article/details/gtwtvxocch.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zdqjudy.top/Article/details/gtdcwhckav.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gtupsufawl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yuxming.cn/Article/details/gtuntdubbo.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtickhmqhy.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtdjmuqmjd.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yj20258888.top/Article/details/gtebpmbzop.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gtpqqpmsne.html

TS:   同 JS
来源：http://dali.hammf.cn/Article/details/gtcwrwgojf.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gtmdobhlac.html

Go:   花括号块级作用域
来源：http://dali.nanxuanxn.top/Article/details/gtgkqcbkpk.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxuanxn.top/Article/details/gtdqjlaxfn.html

C#:   块级作用域
来源：http://dali.sysykeji.top/Article/details/gtftzdxtrm.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gtgfpjckss.html

Py:   from module import func
来源：http://dali.dashuyun.cn/Article/details/gtlxgqwfkr.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsubpbmu.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtttdsioge.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.aibaodan.cn/Article/details/gtqnfxjolt.html

Java: import java.util.List;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxnsiskks.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.wangshuangyany.cn/Article/details/gtljrnrugf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtogwppupa.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpxrqucba.html

[C12] 立即执行函数 IIFE
来源：http://dali.pycfn.com/Article/details/gtqkicldsw.html

Py:   (lambda: print("run"))()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmytnnwwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.c1oappe.top/Article/details/gtzrjpbmoy.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtstucckaf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gttqnjgpvb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yongpay.top/Article/details/gtdbjfoxlm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jiagoushi.top/Article/details/gtdmofutcq.html

Ruby: -> { puts "run" }.call
来源：http://dali.chenzaomai.com/Article/details/gtgsrwcops.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvnsrivnd.html

[C13] 类型声明 / 类型注解
来源：http://dali.haohaochexian.top/Article/details/gtkdpfiosj.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.chenlongwang.top/Article/details/gtztkmpeuo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gtvqpomzxc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.hammf.cn/Article/details/gtknpnmqbf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtnmljhjbl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtpvlfcako.html

Go:   func add(a, b int) int
来源：http://dali.redwolf501.top/Article/details/gtplvtthwr.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtnnsvbcne.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangdashe.top/Article/details/gtaaxfzare.html

[C14] 泛型函数
来源：http://dali.tianlin.xyz/Article/details/gtjliyzpqx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zdqjudy.top/Article/details/gtzcxfpdiv.html

PHP:  // 无泛型
来源：http://dali.sweek.top/Article/details/gtnkxzelpe.html

JS:   // 无泛型
来源：http://dali.jiagoushi.top/Article/details/gtljjsdrct.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ybcxt.top/Article/details/gtkcjvfmhs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhijiandao.cn/Article/details/gtxfwdadsi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.wangshuangyany.cn/Article/details/gtkmbknyyo.html

Ruby: # 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gtrnbheucg.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ivvv.top/Article/details/gtfstdptme.html

[C15] 解构 / 展开参数
来源：http://dali.shuidangran.top/Article/details/gtvyxzdxfk.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.vqdsnc.cn/Article/details/gtgkeclkup.html

PHP:  [$a, $b] = $pair;
来源：http://dali.snrcjt.cn/Article/details/gtwcomcufc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgufenzy.top/Article/details/gtcvczivyb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.c1oappe.top/Article/details/gtavrzvcfq.html

Java: // 无解构
来源：http://dali.daria6918.cn/Article/details/gtqqqcadgg.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gtzrdsodsm.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtfkuxpmcy.html

C#:   var (a, b) = pair;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyqzciek.html

[C16] 函数 / 方法重载
来源：http://dali.jinqigfzy.top/Article/details/gtetgylbnz.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtxjsfuqaf.html

PHP:  // 无重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewwkucbn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hnqzz.top/Article/details/gtocmgpxqt.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.feifeiyinyue.top/Article/details/gtkhaummxj.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shzxlz.cn/Article/details/gtxumumgee.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gtnrmjnbks.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hywenlv.cn/Article/details/gtocxbxnkv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jianghu66.top/Article/details/gtnyqkowxg.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtaqoroobx.html

D. 数组 / 列表 / 集合
来源：http://dali.nanxinkj.top/Article/details/gtugaezqnm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtsuazxcae.html

[D01] 创建数组 / 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtjheiefxg.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zycfv.cn/Article/details/gtrdhovigb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.nanxuanxn.top/Article/details/gtoemieezi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.ybcxt.top/Article/details/gtffogzpwx.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pengpengdd.cyou/Article/details/gtyujxjpuo.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtnstbvhvc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtdnkdedzo.html

Ruby: arr = [1, 2, 3]
来源：http://dali.gaohongyu789.top/Article/details/gtelkfdynt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuanzx.com/Article/details/gtzbhbskec.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtaljhrabk.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zdqjudy.top/Article/details/gtyymecyor.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cashguo.top/Article/details/gtjmevnabt.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtpgthbxhc.html

TS:   arr.push(4);
来源：http://dali.yangfankeji.com/Article/details/gtcivcresl.html

Java: list.add(4);
来源：http://dali.tian-w.cn/Article/details/gtuezfmdpk.html

Go:   arr = append(arr, 4)
来源：http://dali.aizwys.cn/Article/details/gtpdkzztsh.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.hywenlv.cn/Article/details/gtjakjsgns.html

C#:   list.Add(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtjxxkxnvv.html

[D03] 在指定位置插入元素
来源：http://dali.shzxlz.cn/Article/details/gtfkwefodx.html

Py:   arr.insert(0, 0)
来源：http://dali.guowangkeji.top/Article/details/gtfpiqtdmq.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xuetiantiany.cn/Article/details/gtmdqtlxvk.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.guannengcc.top/Article/details/gtdwbknaqo.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.wangdashe.top/Article/details/gtmlmqqqje.html

Java: list.add(0, 0);
来源：http://dali.xylfe.cn/Article/details/gtelvukljr.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuxming.cn/Article/details/gtjhkmowrr.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.svipenyu.cn/Article/details/gtowzykwnb.html

C#:   list.Insert(0, 0);
来源：http://dali.ivvv.top/Article/details/gtdhtleeef.html

[D04] 删除元素
来源：http://dali.daxiang520.top/Article/details/gtxkrzvqfq.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.fengsongda.top/Article/details/gtnwtczodz.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cqqwz.cn/Article/details/gtkvxgyfcg.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.dianchejie.cn/Article/details/gtxrylwqzu.html

TS:   arr.splice(0, 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gtljyflhsn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtulqynvkd.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.guowangkeji.top/Article/details/gtaczayzxx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.hammf.cn/Article/details/gtvafwsvdd.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtchzfauyq.html

[D05] 访问与修改元素
来源：http://dali.cdnleiting.top/Article/details/gtpjkeyiif.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.cdnleiting.top/Article/details/gtippyloej.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.hywenlv.cn/Article/details/gtjyrkizid.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.gaohongyu789.top/Article/details/gtjlsmggre.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.guannengcc.top/Article/details/gtolucmsby.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.xuanzx.com/Article/details/gtsrvakbtv.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtzhzmquiy.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnxiangtu.top/Article/details/gtlkdscdty.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.fengsongda.top/Article/details/gtsmyeojmf.html

[D06] 数组长度
来源：http://dali.haohaochexian.top/Article/details/gtxlqukkmz.html


<!-- 参考信息 -->