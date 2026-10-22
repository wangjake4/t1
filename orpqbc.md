代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2etecrxil.html

Py:   for item in arr: print(item)
来源：http://dali.feifeiyinyue.top/Article/details/gt2zbrakzoh.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gt2vkgvbsaf.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2secbdojn.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gt2odymwwmh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hammf.cn/Article/details/gt2vxjtoayx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gt2pyhjuihk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gt2xehimmnl.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xziqi.cn/Article/details/gt2gxxoxgtv.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gt2fvwycbel.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yj202588.top/Article/details/gt2sltptuha.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ibfxvovb.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.bjfxy.top/Article/details/gt2uxxqzbcx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljvrztpc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jinqigufen.top/Article/details/gt2eirvatzg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.andypj.xyz/Article/details/gt2fwihxfuw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gt2egyodemc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jyoumei.cn/Article/details/gt2righdtro.html

[B07] while 循环
来源：http://dali.mhx1999.top/Article/details/gt2fwsgonis.html

Py:   while i < 10: i += 1
来源：http://dali.tian-w.cn/Article/details/gt2mswrilno.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jsjvxmux.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gt2sdvznqdt.html

TS:   while (i < 10) { i++; }
来源：http://dali.sweek.top/Article/details/gt2qwtnjllv.html

Java: while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2ziemwwgu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zycfv.cn/Article/details/gt2krmzmidl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gt2lmqakrhy.html

C#:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2xevozlyu.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2grccogwe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.sweek.top/Article/details/gt2hxdojooj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xylfe.cn/Article/details/gt2hvrrchuu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjabpdkx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.dianchejie.cn/Article/details/gt2oefhcfjg.html

Java: do { i++; } while (i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gt2yordwpht.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gt2ynbnfkbn.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gt2ycgrbusi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gt2pfutgnzh.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dnzdjamf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ybcxt.top/Article/details/gt2gjetjdsq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jiagoushi.top/Article/details/gt2pgxgwrry.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2kbymezek.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yonumen.top/Article/details/gt2kuhdfkbh.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2jkltlxtm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hywenlv.cn/Article/details/gt2bwjxcivx.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gt2wpltwdal.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gt2rjulkouu.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gt2zpgmjmnt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gt2nravxacs.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gt2ckqyjryz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gogol.net.cn/Article/details/gt2qonbjtxg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gt2ghhrmocl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2mgwgvufl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gt2kbrcvugv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhixingplan.top/Article/details/gt2xklfmciy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnxiangtu.top/Article/details/gt2xvlzbusc.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gt2zvqkabje.html

Py:   list(range(0, 10, 2))
来源：http://dali.ehwqpu.com/Article/details/gt2omabfmoi.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gt2gsqzhzau.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2rcgcibjq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gt2wnqglvkj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gzhubu.top/Article/details/gt2azhifbpg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gt2ypirlggt.html

Ruby: (0...10).step(2).to_a
来源：http://dali.svipenyu.cn/Article/details/gt2pkclkzvp.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.meibo888.top/Article/details/gt2yjvrlddw.html

[B12] 跳出多层循环
来源：http://dali.jqgufenzy.top/Article/details/gt2zugmabrj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cheryme.top/Article/details/gt2wavmazbw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2inonmldf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wimgnldx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2ykeinvso.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gt2rtrdmcse.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gt2fvblluet.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gt2yxubvyzw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gt2emndfria.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gt2vqpkzwxl.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gt2bklisopv.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gt2qdfzsbsl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2maclxvah.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egybzimc.html

Java: x instanceof Number
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2eqgmpqic.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenzaomai.com/Article/details/gt2yvghnthl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.nanxuanxn.top/Article/details/gt2yxyrfytz.html

C#:   x is int or double or decimal
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lubrhwlp.html

[B14] 判断值是否在集合内
来源：http://dali.ydzc1.top/Article/details/gt2uvpuwqej.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hywenlv.cn/Article/details/gt2kwmilzcd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yanxiufei.cn/Article/details/gt2gbbyystq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gt2ivwqieyq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gt2htzzkwqo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gt2oiqymctd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yuanzhike.top/Article/details/gt2eghbqdfd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.fzhhl.top/Article/details/gt2hdrptvpl.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yosuwrki.html

[B15] 布尔运算与取反
来源：http://dali.redwolf501.top/Article/details/gt2pklnoyak.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gt2fzubqpav.html

PHP:  $a && $b || !$c
来源：http://dali.fzhhl.top/Article/details/gt2uvuyshiu.html

JS:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gt2ebmgcmbf.html

TS:   a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2mcpznsfd.html

Java: a && b || !c
来源：http://dali.cashguo.top/Article/details/gt2twxtbfiz.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2xamzrjxu.html

Ruby: a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2gmxrfiuk.html

C#:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2ttcygcso.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gt2mmxikptk.html

Py:   if not data: return
来源：http://dali.dashuyun.cn/Article/details/gt2lzzbmljq.html

PHP:  if (!$data) { return; }
来源：http://dali.dianchejie.cn/Article/details/gt2abjjfqem.html

JS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2askgrdrw.html

TS:   if (!data) return;
来源：http://dali.pycfn.com/Article/details/gt2vqgzhhmk.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gt2hnfqiqpn.html

Go:   if data == nil { return }
来源：http://dali.sufxvd.cn/Article/details/gt2wtplraim.html

Ruby: return if data.nil?
来源：http://dali.ydzc1.top/Article/details/gt2ffpwlkvg.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gt2hfpxqtzz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2ulxlitbl.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2mawcntgl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ichidrxq.html

[C01] 定义函数
来源：http://dali.xuanzx.com/Article/details/gt2lrehzylh.html

Py:   def add(a, b): return a + b
来源：http://dali.jlsjyb.cn/Article/details/gt2isxavzny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2emmjoaub.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2cdvncdrh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2rcgtpelu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2yvnoibkm.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.vqdsnc.cn/Article/details/gt2ekhtlpab.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tejqpwwi.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2oeuveghz.html

[C02] 默认参数
来源：http://dali.xylfe.cn/Article/details/gt2qppskurk.html

Py:   def greet(name="World"): return name
来源：http://dali.yuanzhike.top/Article/details/gt2ymxgibzi.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.mhx1999.top/Article/details/gt2ywdqfvgr.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.mhx1999.top/Article/details/gt2mhesxtes.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gt2obwlwpbc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.mhx1999.top/Article/details/gt2tvlnxgse.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gt2zsereqlv.html

Ruby: def greet(name = "World") = name
来源：http://dali.gogol.net.cn/Article/details/gt2bumfised.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2aiimmgoi.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gt2pwetkmca.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhengqikj.top/Article/details/gt2lagzudii.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gt2bvxkjvow.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yonumen.top/Article/details/gt2iljyizyl.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gt2utlglran.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.fzhhl.top/Article/details/gt2yhcddxht.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hfpthk.cn/Article/details/gt2jhgwvmzp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ybcxt.top/Article/details/gt2uppdnxog.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gt2rzvgbxca.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yueranfly.top/Article/details/gt2qnpibbzc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gt2yoogsfoz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigufen.top/Article/details/gt2jbkjtdcc.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2hncthtyk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gt2nhtknupt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gt2ghksobtf.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnqzz.top/Article/details/gt2umufdmql.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jianghu66.top/Article/details/gt2nvovatwm.html

C#:   f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gt2zivirmuu.html

[C05] 返回多个值
来源：http://dali.zdqjudy.top/Article/details/gt2tishfapp.html

Py:   return a, b
来源：http://dali.cheryme.top/Article/details/gt2kseokvzu.html

PHP:  return [$a, $b];
来源：http://dali.9152youxi.cn/Article/details/gt2szfqduot.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gt2oztpxyzu.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gt2flifbizj.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cucudq.cn/Article/details/gt2fhqyfbyv.html

Go:   return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2lyfzkzlx.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gt2jhhkpbgh.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.fengsongda.top/Article/details/gt2hdgxuxvs.html

[C06] 匿名函数 / lambda
来源：http://dali.guowangkeji.top/Article/details/gt2xklpqsxn.html

Py:   square = lambda x: x * x
来源：http://dali.hongshengwenyu.top/Article/details/gt2khnpokel.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jinqigufen.top/Article/details/gt2ceigvumc.html

JS:   const square = x => x * x;
来源：http://dali.nanxuanxn.top/Article/details/gt2vayvpqfn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.316326.xyz/Article/details/gt2zeblptfp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2rukbluhq.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gt2fjcqfxyg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fengsongda.top/Article/details/gt2cvybmmbp.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gt2rvyjcpea.html

[C07] 把函数作为参数传入
来源：http://dali.havefunace.top/Article/details/gt2zhbefvjy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jlsjyb.cn/Article/details/gt2nvwhzibm.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuanzx.com/Article/details/gt2dlgigvjj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gt2knwcvpqj.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gt2ogsdujun.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.birdmap.top/Article/details/gt2slquvsyh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yonumen.top/Article/details/gt2msxalbdj.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2conusjuz.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gt2rgypudte.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gt2vuzqfpyz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gt2czfrumal.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.hnqzz.top/Article/details/gt2nmvaiaiw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuanzx.com/Article/details/gt2nmcbdqhn.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2xdmpxdal.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhiwuduotai.top/Article/details/gt2yfiovenk.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.xziqi.cn/Article/details/gt2wxlcbsdm.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.svipenyu.cn/Article/details/gt2hnfwjmwm.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mspxabyh.html

[C09] 递归
来源：http://dali.zhoulong.xyz/Article/details/gt2gmemhuzb.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.snrcjt.cn/Article/details/gt2nqcxymcb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2zvjtdaip.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2pkiplogl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gogol.net.cn/Article/details/gt2uvvvdwuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.c1oappe.top/Article/details/gt2tzcmowbg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.316326.xyz/Article/details/gt2pgloiuho.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hywenlv.cn/Article/details/gt2hbamklco.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2bwfnpovn.html

[C10] 变量作用域
来源：http://dali.zycfv.cn/Article/details/gt2yhjkyjvw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hywenlv.cn/Article/details/gt2nyrfsjig.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2hrhaoscf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.ivvv.top/Article/details/gt2wdhltdoa.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gt2etcqcrgu.html

Java: 方法内为块级作用域
来源：http://dali.sufxvd.cn/Article/details/gt2bemynviz.html

Go:   花括号块级作用域
来源：http://dali.pycfn.com/Article/details/gt2ruhmaebo.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yvedp.cn/Article/details/gt2flgevkmh.html

C#:   块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzgqctdd.html

[C11] 模块导入与导出
来源：http://dali.jqgfzy.top/Article/details/gt2gtzuzmpu.html

Py:   from module import func
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2trupckub.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lxrvmrvd.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.chenlongwang.top/Article/details/gt2zgvatjxi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.chenjidiqi.icu/Article/details/gt2lgilgemy.html

Java: import java.util.List;
来源：http://dali.iojbl.cn/Article/details/gt2xceyznfw.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yuanzhike.top/Article/details/gt2fbynjffa.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fzhhl.top/Article/details/gt2jxdnqeys.html

C#:   using System.Text;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hmoqzbks.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gt2hrpifqij.html

Py:   (lambda: print("run"))()
来源：http://dali.zdqjudy.top/Article/details/gt2utjrlbwv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jinqigufen.top/Article/details/gt2hifmuvpf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ivvv.top/Article/details/gt2vdaerxlj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.ppjwa.cn/Article/details/gt2vuvapuyx.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.quarkkingdee.top/Article/details/gt2rkmsnicf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gt2nblgptch.html

Ruby: -> { puts "run" }.call
来源：http://dali.yonumen.top/Article/details/gt2adfgjeku.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gt2abxtaiqt.html

[C13] 类型声明 / 类型注解
来源：http://dali.hfpthk.cn/Article/details/gt2dblyqnib.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yonumen.top/Article/details/gt2irozqskn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2bogbrbcb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.svipenyu.cn/Article/details/gt2lxutnpgt.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2mmftjnrb.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gt2vecyhpzj.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2tegizyey.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.zhengqikj.top/Article/details/gt2bdbprtbq.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gt2jencivev.html

[C14] 泛型函数
来源：http://dali.cqqwz.cn/Article/details/gt2znjuqgzx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jianghu66.top/Article/details/gt2dxtqrexw.html

PHP:  // 无泛型
来源：http://dali.shzxlz.cn/Article/details/gt2zwpzmenj.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gt2oentkivs.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gt2evljanzs.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gt2mstvlugi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.bjfxy.top/Article/details/gt2fxoogmuv.html

Ruby: # 无泛型
来源：http://dali.shuidangran.top/Article/details/gt2djhknbty.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.birdmap.top/Article/details/gt2iwxgzskw.html

[C15] 解构 / 展开参数
来源：http://dali.guannengcc.top/Article/details/gt2gbjcfsrz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hysaishi.cn/Article/details/gt2jmryltjg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.meibo888.top/Article/details/gt2nmsbagku.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenzaomai.com/Article/details/gt2mdtwskin.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2vvopwekh.html

Java: // 无解构
来源：http://dali.0kj1m.cn/Article/details/gt2bnlqoigx.html

Go:   // 无解构
来源：http://dali.jianghu66.top/Article/details/gt2lhsbchgc.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gt2ebkidgua.html

C#:   var (a, b) = pair;
来源：http://dali.hysaishi.cn/Article/details/gt2mkzczsjf.html

[C16] 函数 / 方法重载
来源：http://dali.nanxinkj.top/Article/details/gt2wxsqiaey.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.guowangkeji.top/Article/details/gt2uovemnir.html

PHP:  // 无重载
来源：http://dali.jqgfzy.top/Article/details/gt2cctgcclt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxinkj.top/Article/details/gt2xzsqaiqe.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gt2higmcfkl.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.xuanzx.com/Article/details/gt2jlwbwodx.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gt2vlffznsl.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jianghu66.top/Article/details/gt2baelcoqw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.0kj1m.cn/Article/details/gt2wrwofhjp.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dqxajzca.html

D. 数组 / 列表 / 集合
来源：http://dali.xziqi.cn/Article/details/gt2qhcljviw.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gt2rvsrvltk.html

[D01] 创建数组 / 列表
来源：http://dali.shangyingyoupin.top/Article/details/gt2yruzgihy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.zhengqikj.top/Article/details/gt2yltqtdyr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xinyue.icu/Article/details/gt2szbxhgzt.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2cwetrjli.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.pycfn.com/Article/details/gt2thzhkfat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gt2sbfxuwmr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.iojbl.cn/Article/details/gt2unfcfhay.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2iprvnphs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gt2cwpqchxq.html

[D02] 追加元素到末尾
来源：http://dali.nanxinkj.top/Article/details/gt2zlouesmd.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hongshengwenyu.top/Article/details/gt2rnlrtvfg.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.ydzc1.top/Article/details/gt2susjnjxi.html

JS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2lxveggnm.html

TS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ltonvuty.html

Java: list.add(4);
来源：http://dali.daxiang520.top/Article/details/gt2pvzifelu.html

Go:   arr = append(arr, 4)
来源：http://dali.andypj.xyz/Article/details/gt2fyjyfnhf.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.chenzaomai.com/Article/details/gt2kviuyapk.html

C#:   list.Add(4);
来源：http://dali.zdqjudy.top/Article/details/gt2vawftwqu.html

[D03] 在指定位置插入元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cipzgciy.html

Py:   arr.insert(0, 0)
来源：http://dali.yangfankeji.com/Article/details/gt2qdrnieam.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ehwqpu.com/Article/details/gt2dwiwvcdc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hongshengwenyu.top/Article/details/gt2wjxrcklk.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.sxryk.cn/Article/details/gt2ismszbcv.html

Java: list.add(0, 0);
来源：http://dali.wangdashe.top/Article/details/gt2xaritlec.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gt2mneapysx.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.pycfn.com/Article/details/gt2nqifirti.html

C#:   list.Insert(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2clzfdwrw.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gt2ttmvkjln.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.pengpengdd.cyou/Article/details/gt2vcysqksh.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.quarkkingdee.top/Article/details/gt2rtrtetko.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.havefunace.top/Article/details/gt2byjshhgx.html

TS:   arr.splice(0, 1);
来源：http://dali.yj20258888.top/Article/details/gt2nebdnkar.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yvedp.cn/Article/details/gt2eaikvwow.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.chenjidiqi.icu/Article/details/gt2mkrpyrfb.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gt2ivatmlhv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.ybcxt.top/Article/details/gt2ubjunvxr.html

[D05] 访问与修改元素
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sqovrgcc.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.hnqzz.top/Article/details/gt2rotcckae.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.yanxiufei.cn/Article/details/gt2qbkkotuj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhengqikj.top/Article/details/gt2kwxuacbh.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.snrcjt.cn/Article/details/gt2harbvzzp.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.guannengcc.top/Article/details/gt2xnkgykqf.html


<!-- 参考信息 -->