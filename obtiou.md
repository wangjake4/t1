代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hnqzz.top/Article/details/gt2xnwnaokc.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2bcxglekp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gt2eezdbcsp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hywenlv.cn/Article/details/gt2gqaherfl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yuxming.cn/Article/details/gt2qrqnmlop.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2omcgtspj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xinyue.icu/Article/details/gt2vjobkdvs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ygguipaf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yongpay.top/Article/details/gt2vvpoybct.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jqgfzy.top/Article/details/gt2nisdhbpf.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gt2rcieqaxk.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eijjakuv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2lofhjwum.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uyuktynt.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gt2kckhikwr.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gt2oigwcrzf.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wyqzxwva.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2pjsxtvpx.html

C#:   while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gt2ezfjwepa.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gt2owpzqjas.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gt2rcbqktbw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gt2wlrafafw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gt2eomqsehr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj202588.top/Article/details/gt2epyqxbjd.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2qbadgbte.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yonumen.top/Article/details/gt2lfwedtwh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xylfe.cn/Article/details/gt2ijrxjfcj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2delnhxfu.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gt2viruufld.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.wangshuangyany.cn/Article/details/gt2sinsiqnt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2prdttyve.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gt2owsercci.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gt2hhdzrxqe.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gt2axordwka.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2xhgmtaov.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.pengpengdd.cyou/Article/details/gt2acudbawr.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2qgodikcf.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ehixhopv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.smart0.xyz/Article/details/gt2ovajdark.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gt2zqfuvzqy.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxsmclfu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gt2wrflojip.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.fzhhl.top/Article/details/gt2uitxqypy.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinqigfzy.top/Article/details/gt2ngavxpax.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.fengsongda.top/Article/details/gt2gwxujawu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.guowangkeji.top/Article/details/gt2ffrzypig.html

[B11] 生成数字序列 / 区间
来源：http://dali.gzhubu.top/Article/details/gt2poipduaw.html

Py:   list(range(0, 10, 2))
来源：http://dali.jqgufenzy.top/Article/details/gt2ielgvgng.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gt2yxqthghh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gt2wulqihja.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2cfzlkqlm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gt2bbirdiov.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.quarkkingdee.top/Article/details/gt2bdipszgx.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hongshengwenyu.top/Article/details/gt2zxspqfhn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gt2eskjabfl.html

[B12] 跳出多层循环
来源：http://dali.yj20258888.top/Article/details/gt2qlceivgi.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hfpthk.cn/Article/details/gt2drypllgb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.tanke756.top/Article/details/gt2trhsnbtx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gt2scnpwapw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gt2htpedtsl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2kqafmouc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.kuanghao11.cn/Article/details/gt2jqupniyq.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qnhjckyl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yanxiufei.cn/Article/details/gt2ymvkkufe.html

[B13] 判断是否为数字
来源：http://dali.yonumen.top/Article/details/gt2jayzdhjv.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gt2esnpqkig.html

PHP:  is_numeric($x)
来源：http://dali.snrcjt.cn/Article/details/gt2ataauovn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fmfzonbq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gt2mqdtdsjx.html

Java: x instanceof Number
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyawffnp.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gt2juvppfvv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj202588.top/Article/details/gt2wvfmwpdz.html

C#:   x is int or double or decimal
来源：http://dali.ehwqpu.com/Article/details/gt2hsitsucw.html

[B14] 判断值是否在集合内
来源：http://dali.zdqjudy.top/Article/details/gt2xfohayxt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gt2mpnaqmpf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gt2neqntwxy.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gt2nqmdlgfy.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xziqi.cn/Article/details/gt2ewhjgyqw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2oyloekbt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gt2nzyreakj.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2akrinvcn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2dpslavwi.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gbzdwptq.html

Py:   a and b or not c
来源：http://dali.yuxming.cn/Article/details/gt2jbvyphdl.html

PHP:  $a && $b || !$c
来源：http://dali.gotoacloud.top/Article/details/gt2jgykjrqx.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2lilzvjbr.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2cegvzbdu.html

Java: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gt2nwbmegdi.html

Go:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mzuaghxp.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gt2dekczmfi.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2dcivtxkg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.svipenyu.cn/Article/details/gt2paludpue.html

Py:   if not data: return
来源：http://dali.jinqigfzy.top/Article/details/gt2tqenefvl.html

PHP:  if (!$data) { return; }
来源：http://dali.ybcxt.top/Article/details/gt2quxeqsdj.html

JS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gt2natgjkzf.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gt2anrdphpy.html

Java: if (data == null) return;
来源：http://dali.hfpthk.cn/Article/details/gt2nhyfmbom.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gt2hvpfcevg.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2acfjzjzf.html

C#:   if (data == null) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2agdsyovm.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2ofbwuemq.html

C. 函数与作用域
来源：http://dali.fzhhl.top/Article/details/gt2qgrkgkgs.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2fkbzovuh.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gt2wscvrmfw.html

Py:   def add(a, b): return a + b
来源：http://dali.nanxuanxn.top/Article/details/gt2pmjbobwb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gt2crruhhmj.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2wcosfmiw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gt2csriedfn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ryaoubpj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yangfankeji.com/Article/details/gt2qoglpowi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.bjfxy.top/Article/details/gt2feqnnjak.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2gyposvta.html

[C02] 默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2lakrtdgv.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyohkmft.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gt2yvtiffum.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2pbhivwgq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ybcxt.top/Article/details/gt2ixpacesn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.havefunace.top/Article/details/gt2sxskqinm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.316326.xyz/Article/details/gt2tstoefbc.html

Ruby: def greet(name = "World") = name
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yidhkkpa.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oyxxpixx.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gt2qhxjufkv.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gt2gvxkmfvl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yongpay.top/Article/details/gt2sftncucp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xziqi.cn/Article/details/gt2dtmebwnh.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.mhx1999.top/Article/details/gt2afhmnueg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2svispdyl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uynipmmk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj20258888.top/Article/details/gt2zkoevjys.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.redwolf501.top/Article/details/gt2jlpmvgbi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gt2aixbtmvy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhiwuduotai.top/Article/details/gt2fqsazopz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.bjfxy.top/Article/details/gt2rhewntrj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gt2naintdsa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yuxming.cn/Article/details/gt2ltgeticm.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jqgfzy.top/Article/details/gt2mypovmfw.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gt2dmuwujnp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj20258888.top/Article/details/gt2ejvuymha.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2vwclnhfr.html

[C05] 返回多个值
来源：http://dali.pengpengdd.cyou/Article/details/gt2eusiqwhc.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gt2xnxgqlqt.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gt2zvtpqiyi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj202588.top/Article/details/gt2bmmyatxt.html

TS:   return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gt2iukbzpeo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zefbjnfi.html

Go:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gt2akwovcnb.html

Ruby: return a, b
来源：http://dali.daxiang520.top/Article/details/gt2gvkyduwh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhengqikj.top/Article/details/gt2sxqlbvfq.html

[C06] 匿名函数 / lambda
来源：http://dali.chenlongwang.top/Article/details/gt2tlcbrbsa.html

Py:   square = lambda x: x * x
来源：http://dali.aizwys.cn/Article/details/gt2vmpnxces.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gt2jobuyroo.html

JS:   const square = x => x * x;
来源：http://dali.birdmap.top/Article/details/gt2uazmtduv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.c1oappe.top/Article/details/gt2xeivlens.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cqqwz.cn/Article/details/gt2yontaxas.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xuanzx.com/Article/details/gt2yszegmcx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gt2julgdpdi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gt2vgyxvgqj.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2tqukpmdf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wpkgkoec.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.hysaishi.cn/Article/details/gt2fkgajiwx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gt2xjzjtlxh.html

TS:   arr.map(String)
来源：http://dali.dianchejie.cn/Article/details/gt2dxknfyil.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jqgfzy.top/Article/details/gt2wfqbcgam.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zdqjudy.top/Article/details/gt2junkhgxs.html

Ruby: arr.map(&:upcase)
来源：http://dali.tianlin.xyz/Article/details/gt2hdqecdes.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gt2hcxqxqjs.html

[C08] 闭包
来源：http://dali.yj202588.top/Article/details/gt2geihvaen.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2icyuzook.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gzhubu.top/Article/details/gt2xpujmgjm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oamukkng.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gt2yxxpzlfc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yonumen.top/Article/details/gt2yuzdglkx.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.zdqjudy.top/Article/details/gt2wxvnambi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.iojbl.cn/Article/details/gt2koyqbaza.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tkcpsqfa.html

[C09] 递归
来源：http://dali.smart0.xyz/Article/details/gt2hftceldl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.9152youxi.cn/Article/details/gt2eizaazwm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gt2usdgxrlc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2bpbvabqf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cashguo.top/Article/details/gt2ijskjper.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vlxkdeyt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xinyue.icu/Article/details/gt2jimdtbnm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yangfankeji.com/Article/details/gt2jgsurqge.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.pengpengdd.cyou/Article/details/gt2wxussodv.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2jahtozck.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.ybcxt.top/Article/details/gt2oaeyoylz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2jtpalgfs.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hywenlv.cn/Article/details/gt2krdeydyi.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2kaglycqk.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ysuosvfu.html

Go:   花括号块级作用域
来源：http://dali.bjfxy.top/Article/details/gt2noifghqb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gt2tmdwyeed.html

C#:   块级作用域
来源：http://dali.yj20258888.top/Article/details/gt2yswhjdkl.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gt2fwxcxtgf.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gt2tuqqilbf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gt2yzezbkxl.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2ivtqqadq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gt2kjfzxpxm.html

Java: import java.util.List;
来源：http://dali.tanke756.top/Article/details/gt2upnzeoyn.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.aibaodan.cn/Article/details/gt2hggdmpjr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cqqwz.cn/Article/details/gt2gbwbunzh.html

C#:   using System.Text;
来源：http://dali.hywenlv.cn/Article/details/gt2nhtwgmun.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gt2wbbbswbl.html

Py:   (lambda: print("run"))()
来源：http://dali.9152youxi.cn/Article/details/gt2skamvrev.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fengsongda.top/Article/details/gt2vtwevpnz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.0kj1m.cn/Article/details/gt2vgrkulpn.html

TS:   (() => { console.log("run"); })();
来源：http://dali.pycfn.com/Article/details/gt2efcyzrhq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yj20258888.top/Article/details/gt2ejnyluew.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zycfv.cn/Article/details/gt2zchsiljt.html

Ruby: -> { puts "run" }.call
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fitelgof.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gt2esxywagi.html

[C13] 类型声明 / 类型注解
来源：http://dali.jlsjyb.cn/Article/details/gt2pknrmcoi.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nanxinkj.top/Article/details/gt2fdxqabya.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gt2caqfpzbm.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gt2wxvdaaqy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2lqkovyin.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gt2bzzhuccu.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxltvlzw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.guowangkeji.top/Article/details/gt2uzacmlfe.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yj20258.top/Article/details/gt2rwscezpr.html

[C14] 泛型函数
来源：http://dali.yvedp.cn/Article/details/gt2vbsfzcwh.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.dianchejie.cn/Article/details/gt2osgvpjoo.html

PHP:  // 无泛型
来源：http://dali.yuanzhike.top/Article/details/gt2tqsqpuvi.html

JS:   // 无泛型
来源：http://dali.hnxiangtu.top/Article/details/gt2giaryooq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.quarkkingdee.top/Article/details/gt2cfwdlzjg.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gt2ociavtku.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gt2rbvkccic.html

Ruby: # 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2arphahfo.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jqgfzy.top/Article/details/gt2igqfolfa.html

[C15] 解构 / 展开参数
来源：http://dali.pycfn.com/Article/details/gt2bcefdlsf.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2iaukpxpl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jlsjyb.cn/Article/details/gt2hhphktto.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gt2kglofpyw.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2evdnsown.html

Java: // 无解构
来源：http://dali.hywenlv.cn/Article/details/gt2tdydpmor.html

Go:   // 无解构
来源：http://dali.bjfxy.top/Article/details/gt2ytdxtsmd.html

Ruby: a, b = pair
来源：http://dali.hammf.cn/Article/details/gt2tmhuofyt.html

C#:   var (a, b) = pair;
来源：http://dali.zdqjudy.top/Article/details/gt2vkwdlqvn.html

[C16] 函数 / 方法重载
来源：http://dali.yj20258.top/Article/details/gt2yveqketd.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wwyymkdn.html

PHP:  // 无重载
来源：http://dali.feifeiyinyue.top/Article/details/gt2jtjcgysj.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.tanke756.top/Article/details/gt2kuspeaac.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.ehwqpu.com/Article/details/gt2eluwnifi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jqgufenzy.top/Article/details/gt2pxunmypb.html

Go:   // 无重载：用不同函数名
来源：http://dali.ppjwa.cn/Article/details/gt2teszqjfw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.nanxuanxn.top/Article/details/gt2xproletn.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.havefunace.top/Article/details/gt2ovuwqvfy.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2xockdwsc.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gt2bdstknvh.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2gwtlgdxz.html

[D01] 创建数组 / 列表
来源：http://dali.ivvv.top/Article/details/gt2omaxximh.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gt2tndmhpfi.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.hongshengwenyu.top/Article/details/gt2zstzlnkb.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.gzhubu.top/Article/details/gt2zlmxsmom.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2psvhovan.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.9152youxi.cn/Article/details/gt2thhxuwnx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gt2hcgcxxbl.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hfpthk.cn/Article/details/gt2akujpwhm.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gt2icrgpnyx.html

[D02] 追加元素到末尾
来源：http://dali.jyoumei.cn/Article/details/gt2emvohvfo.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.wangshuangyany.cn/Article/details/gt2lvkirwln.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.yuanzhike.top/Article/details/gt2dnkjdyvk.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gt2agewcmhw.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gt2glohevfw.html

Java: list.add(4);
来源：http://dali.haohaochexian.top/Article/details/gt2abkpluik.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gt2nzbfrqiu.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ppjwa.cn/Article/details/gt2goxibnho.html

C#:   list.Add(4);
来源：http://dali.smart0.xyz/Article/details/gt2qtuuhpgt.html

[D03] 在指定位置插入元素
来源：http://dali.guannengcc.top/Article/details/gt2cqyxrikx.html

Py:   arr.insert(0, 0)
来源：http://dali.yueranfly.top/Article/details/gt2arsiljrh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj202588.top/Article/details/gt2aaujzoza.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.yangfankeji.com/Article/details/gt2lokugbcm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.birdmap.top/Article/details/gt2seeekeke.html

Java: list.add(0, 0);
来源：http://dali.redwolf501.top/Article/details/gt2iilsfmmh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.sxryk.cn/Article/details/gt2xjwjzxlu.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.gzhubu.top/Article/details/gt2zkyiqqwm.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2guvfjozk.html

[D04] 删除元素
来源：http://dali.yvedp.cn/Article/details/gt2tsqbrajv.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yanxiufei.cn/Article/details/gt2dydsrpbg.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pphurwzf.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.shuidangran.top/Article/details/gt2yjauwwns.html

TS:   arr.splice(0, 1);
来源：http://dali.chenlongwang.top/Article/details/gt2gbfmvsht.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.shangyingyoupin.top/Article/details/gt2lhuqefiy.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.xuanzx.com/Article/details/gt2cwtfzjrj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.vqdsnc.cn/Article/details/gt2twublbgb.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hywenlv.cn/Article/details/gt2hojcpeml.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gt2coluouvk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gt2heiujvoo.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yueranfly.top/Article/details/gt2eiqusslu.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.hnxiangtu.top/Article/details/gt2sussrsre.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwppqaiq.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.zhengqikj.top/Article/details/gt2rxfwinkg.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.yangfankeji.com/Article/details/gt2hievbhac.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.bjfxy.top/Article/details/gt2hfmogitv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ddamffcj.html

[D06] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gt2nqgzwssz.html

Py:   len(arr)
来源：http://dali.aibaodan.cn/Article/details/gt2tdzipbun.html

PHP:  count($arr);
来源：http://dali.yonumen.top/Article/details/gt2wwtnefsq.html

JS:   arr.length
来源：http://dali.ehwqpu.com/Article/details/gt2isrrilnq.html

TS:   arr.length
来源：http://dali.cdnleiting.top/Article/details/gt2tkljcboi.html


<!-- 参考信息 -->