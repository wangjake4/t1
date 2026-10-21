代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtltgfondi.html

Py:   for item in arr: print(item)
来源：http://dali.nwbrower.top/Article/details/gtmgiahbaw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.wangdashe.top/Article/details/gtuuxsvkrt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hysaishi.cn/Article/details/gtagsvyshc.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtnxtukfcw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gogol.net.cn/Article/details/gtdrttxeoy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xziqi.cn/Article/details/gtbwlrkfor.html

Ruby: arr.each { |item| puts item }
来源：http://dali.redwolf501.top/Article/details/gtasozvgar.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gtxtbszvbj.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtshguuzjv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.9152youxi.cn/Article/details/gtohfyqcnd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gaohongyu789.top/Article/details/gtexomclxz.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtvccjuzie.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gthfebgncl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.svipenyu.cn/Article/details/gtparzjvqt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj20258.top/Article/details/gtyddclgou.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtekuhhoom.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tianlin.xyz/Article/details/gterfctwdg.html

[B07] while 循环
来源：http://dali.0kj1m.cn/Article/details/gtiivunozn.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gtvzuelhit.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtacoqbddz.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtzswagryx.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gthwxdhiey.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfueeiwvu.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.haohaochexian.top/Article/details/gtnahxncrv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.chenzaomai.com/Article/details/gtbvfpqhwf.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtwjkldtts.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gtzoliudyg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gtqatlpobd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtranqdnzj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtmmzprmhh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gthuhdoanx.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtvhmzkrlx.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtqjduagdg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ppjwa.cn/Article/details/gtaebffcts.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtwowofnyu.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtclelulld.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xylfe.cn/Article/details/gthwtbtyoq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjxsjenaq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtywvpczmx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtyohnnbup.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtpwvolkti.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gtuqctxhys.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.fzhhl.top/Article/details/gtswmtabyg.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtpjajckdy.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtrlkytheh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yuanzhike.top/Article/details/gthtpxsaec.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gtlouqlwqv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtggmgtspk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbhwckdjb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.havefunace.top/Article/details/gtmblndgvx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ehwqpu.com/Article/details/gtlhsabxve.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtnlyupluj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gttbuxgfmg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gtvfwprlcy.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gtwnuzxzrg.html

PHP:  range(0, 10, 2);
来源：http://dali.yj20258.top/Article/details/gtiwcybmof.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadedrbko.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuxming.cn/Article/details/gtrnfwagql.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangdashe.top/Article/details/gtihkandzp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hysaishi.cn/Article/details/gtljokwnyb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gtxuxzlenj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtkhkfrgsg.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtujegzqer.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.havefunace.top/Article/details/gtfuelhynm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtupepqqpv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guannengcc.top/Article/details/gtuwatctlo.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtjdfmggag.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtiknrpzae.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gtcsxtmxnz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.wangshuangyany.cn/Article/details/gtuizwzxkc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gtpskprblh.html

[B13] 判断是否为数字
来源：http://dali.cqqwz.cn/Article/details/gtvcwujhfa.html

Py:   isinstance(x, (int, float))
来源：http://dali.ivvv.top/Article/details/gttdkzsrar.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gtujssctty.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtbfiimvzc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.quarkkingdee.top/Article/details/gtofapfrqo.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtbooycsbt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gtqonxomwk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.guannengcc.top/Article/details/gtjpiybmjh.html

C#:   x is int or double or decimal
来源：http://dali.svipenyu.cn/Article/details/gthcsmocog.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtuehzyyfv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwxauzor.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtzsfuovgd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gthjwvnitj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yangfankeji.com/Article/details/gtllczoeik.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtemgzpgek.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtzymktzhh.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jianghu66.top/Article/details/gtanwyxayh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daria6918.cn/Article/details/gtlelgupne.html

[B15] 布尔运算与取反
来源：http://dali.ybcxt.top/Article/details/gtgghfsxoo.html

Py:   a and b or not c
来源：http://dali.chenjidiqi.icu/Article/details/gtvhmvyknq.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtsuravflf.html

JS:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmjlaxgl.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtylcbgvpv.html

Java: a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtijsbekmn.html

Go:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtjilkecup.html

Ruby: a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtnbczqlnx.html

C#:   a && b || !c
来源：http://dali.yj202588.top/Article/details/gtmmvsowmb.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gthrzgzavv.html

Py:   if not data: return
来源：http://dali.sxryk.cn/Article/details/gtyibzizcz.html

PHP:  if (!$data) { return; }
来源：http://dali.yvedp.cn/Article/details/gteyreyifa.html

JS:   if (!data) return;
来源：http://dali.gogol.net.cn/Article/details/gtvtczickb.html

TS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtflyvghje.html

Java: if (data == null) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtqdtycatm.html

Go:   if data == nil { return }
来源：http://dali.fengsongda.top/Article/details/gtdaketqqg.html

Ruby: return if data.nil?
来源：http://dali.gogol.net.cn/Article/details/gtmljvcchj.html

C#:   if (data == null) return;
来源：http://dali.ppjwa.cn/Article/details/gtbhsferof.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtgavoqoye.html

C. 函数与作用域
来源：http://dali.birdmap.top/Article/details/gtytenblna.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtdhxfujgn.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtoxezpwox.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtkvdojmad.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtwlurwrrt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtvspvtqpb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdxmbhqbj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdkvrbhhz.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.quarkkingdee.top/Article/details/gtrpddvpvo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtxmhoqyzz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtajlonepx.html

[C02] 默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtekxsxezf.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gtovyetpuu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtozyyscbc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtcexxdfad.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtnoztjycg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtjkmmozqg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtnbrpslpu.html

Ruby: def greet(name = "World") = name
来源：http://dali.haohaochexian.top/Article/details/gtlfzojiph.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhongyouzk.top/Article/details/gtbfhpcqgx.html

[C03] 可变参数
来源：http://dali.mhx1999.top/Article/details/gtxplhxzcv.html

Py:   def total(*args): return sum(args)
来源：http://dali.xziqi.cn/Article/details/gtyhrngdch.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gtmciimolm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.daxiang520.top/Article/details/gtdiqficyq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtaxwsnvks.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuetiantiany.cn/Article/details/gtnnbohzxj.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.316326.xyz/Article/details/gtmznekxoq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtutouzzml.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hammf.cn/Article/details/gtncnwcoff.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtzufbklab.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gogol.net.cn/Article/details/gtlhbewnoj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jyoumei.cn/Article/details/gtnozikhuq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yuxming.cn/Article/details/gtjvjqxlwa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.dashuyun.cn/Article/details/gtfexysrqc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ydzc1.top/Article/details/gtzrfejruh.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gthnywkgmi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtcpxowuzy.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtsvvsskkz.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtyyhpedek.html

Py:   return a, b
来源：http://dali.hfpthk.cn/Article/details/gtcpmcnuji.html

PHP:  return [$a, $b];
来源：http://dali.xinyue.icu/Article/details/gtswyujvgj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dashuyun.cn/Article/details/gteduburmo.html

TS:   return { a, b };
来源：http://dali.yangfankeji.com/Article/details/gtsecrprtf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hywenlv.cn/Article/details/gtnjbcflre.html

Go:   return a, b
来源：http://dali.pycfn.com/Article/details/gtmolyywul.html

Ruby: return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtldjjoppd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cdnleiting.top/Article/details/gttkoxcfcp.html

[C06] 匿名函数 / lambda
来源：http://dali.svipenyu.cn/Article/details/gtzmuaoaje.html

Py:   square = lambda x: x * x
来源：http://dali.zhixingplan.top/Article/details/gttioycskv.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtetuxrsxb.html

JS:   const square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtgfgacsgj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtzzgbjohq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.nwbrower.top/Article/details/gtoojfmxzp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gtlhmrdesv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtgapnoghf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtnoeurgak.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwexxagk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yvedp.cn/Article/details/gtobochmfv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenjidiqi.icu/Article/details/gtydqdgqpb.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.mhx1999.top/Article/details/gtbvauwamz.html

TS:   arr.map(String)
来源：http://dali.zhiwuduotai.top/Article/details/gtadtxtars.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtibcaitwp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtwlkrhhhn.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gtdbojxqtd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gtgvxyijye.html

[C08] 闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtkkojdpzz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtdbsrmhct.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.chenlongwang.top/Article/details/gttjrbvnno.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtvbkqazte.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtmfrekcne.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zdqjudy.top/Article/details/gtesdzbzlc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.cqqwz.cn/Article/details/gtoyynyyix.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhiwuduotai.top/Article/details/gtqrowbcsg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtoxzzuunl.html

[C09] 递归
来源：http://dali.bjfxy.top/Article/details/gtokrvfaxh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.cheryme.top/Article/details/gtagybocij.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangdashe.top/Article/details/gthuxkctuv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gtvcyeisdw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gtsayzvxem.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yj202588.top/Article/details/gtytntmmdm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gtvuihwfjg.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtjuwtyngg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.svipenyu.cn/Article/details/gtcqkpphdt.html

[C10] 变量作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gteufnxkxg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.kuanghao11.cn/Article/details/gtmpdagtic.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtadgcadcn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.andypj.xyz/Article/details/gtzusnlwqk.html

TS:   同 JS
来源：http://dali.jinqigufen.top/Article/details/gthrslhbsg.html

Java: 方法内为块级作用域
来源：http://dali.jianghu66.top/Article/details/gtpcvrkrvd.html

Go:   花括号块级作用域
来源：http://dali.sweek.top/Article/details/gtnlozjjwu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jlsjyb.cn/Article/details/gtczgngfdq.html

C#:   块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gtbwnqcbqk.html

[C11] 模块导入与导出
来源：http://dali.yueranfly.top/Article/details/gtxjslaqvy.html

Py:   from module import func
来源：http://dali.svipenyu.cn/Article/details/gttlafecox.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.andypj.xyz/Article/details/gtjmmtidgf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.birdmap.top/Article/details/gtchtlrbjk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hammf.cn/Article/details/gthwvmuaoj.html

Java: import java.util.List;
来源：http://dali.hongshengwenyu.top/Article/details/gtfdrziqwk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenzaomai.com/Article/details/gtmlikxtha.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cdnleiting.top/Article/details/gtowykoset.html

C#:   using System.Text;
来源：http://dali.hysaishi.cn/Article/details/gtteizyjpu.html

[C12] 立即执行函数 IIFE
来源：http://dali.xylfe.cn/Article/details/gttixbrjql.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtqtgdqotj.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gtcjuncisl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tanke756.top/Article/details/gtvezdqqhi.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fzhhl.top/Article/details/gtitvuksyk.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.c1oappe.top/Article/details/gtlozymxmz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.gotoacloud.top/Article/details/gtxhhnwpiq.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtmutinsea.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.birdmap.top/Article/details/gtrrchygby.html

[C13] 类型声明 / 类型注解
来源：http://dali.0kj1m.cn/Article/details/gtcslvnvlc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.nwbrower.top/Article/details/gtnygwatsn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtcwoakdzg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.aibaodan.cn/Article/details/gtedkmjcyv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrdslqnqu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtnahrwisv.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gtvfleefzb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtogdrwbnl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtwycdvzil.html

[C14] 泛型函数
来源：http://dali.ppjwa.cn/Article/details/gtvvyglaic.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtconqfcee.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gtgmmmlbrm.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gtbpetyslh.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.cucudq.cn/Article/details/gtwxdkwhec.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtwejqjlel.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gtpmvgtsbq.html

Ruby: # 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtjedqasso.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuanzx.com/Article/details/gtjmmbclbg.html

[C15] 解构 / 展开参数
来源：http://dali.c1oappe.top/Article/details/gtczugbrgu.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtqpdpzgkv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhongyouzk.top/Article/details/gtdsslstxo.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gttlqbwiza.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gtdrpkcduz.html

Java: // 无解构
来源：http://dali.fzhhl.top/Article/details/gtlpdomgft.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gtbqakmxfk.html

Ruby: a, b = pair
来源：http://dali.meibo888.top/Article/details/gtbpgfcfwy.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtdjwjmgwp.html

[C16] 函数 / 方法重载
来源：http://dali.jyoumei.cn/Article/details/gtfwnmekvy.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hnqzz.top/Article/details/gtpjuiqrvy.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gttmrrxonl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jinghuilouyu.cn/Article/details/gtsfvdzhxl.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gaohongyu789.top/Article/details/gtmoannqic.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fengsongda.top/Article/details/gtlhmvutum.html

Go:   // 无重载：用不同函数名
来源：http://dali.gogol.net.cn/Article/details/gtsrredpzc.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gtxnwaofnm.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.jinqigfzy.top/Article/details/gtiqpccprl.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtjqckqlke.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtfrpgxivg.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtooihjfzj.html

[D01] 创建数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtglvltyuq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtmbrsoaal.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtrqjdfifi.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.zhijiandao.cn/Article/details/gthdyymsiq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.c1oappe.top/Article/details/gtbeutphel.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.haohaochexian.top/Article/details/gthdfsdgcq.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.c1oappe.top/Article/details/gtjgcbbrim.html

Ruby: arr = [1, 2, 3]
来源：http://dali.shuidangran.top/Article/details/gtbnntyoro.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhoulong.xyz/Article/details/gthhbzjpwi.html

[D02] 追加元素到末尾
来源：http://dali.jiagoushi.top/Article/details/gtyvgciybb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozwfwuwj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.mhx1999.top/Article/details/gtlqggnqon.html

JS:   arr.push(4);
来源：http://dali.iojbl.cn/Article/details/gtfejfqybu.html

TS:   arr.push(4);
来源：http://dali.haohaochexian.top/Article/details/gtqhvyazar.html

Java: list.add(4);
来源：http://dali.xinyue.icu/Article/details/gtucuxuovm.html

Go:   arr = append(arr, 4)
来源：http://dali.cqqwz.cn/Article/details/gtzgdnqqyx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.yuanzhike.top/Article/details/gtjsqjzamx.html

C#:   list.Add(4);
来源：http://dali.redwolf501.top/Article/details/gtdhuucpik.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtdypiggtd.html

Py:   arr.insert(0, 0)
来源：http://dali.tanke756.top/Article/details/gtguxkfbqo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtxckdqjoz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtgmoccffl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.fzhhl.top/Article/details/gtgwermflw.html

Java: list.add(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtwhidrauo.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.hywenlv.cn/Article/details/gtdwuwcakf.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.ehwqpu.com/Article/details/gtijsklapb.html

C#:   list.Insert(0, 0);
来源：http://dali.tianlin.xyz/Article/details/gtwlvqlebl.html

[D04] 删除元素
来源：http://dali.bjfxy.top/Article/details/gtuncgzcay.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.kuanghao11.cn/Article/details/gtotrzuocw.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.kuanghao11.cn/Article/details/gtmgvjmoal.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jiagoushi.top/Article/details/gtjssohrnl.html

TS:   arr.splice(0, 1);
来源：http://dali.havefunace.top/Article/details/gtvniivjrx.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmynapvi.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.hnxiangtu.top/Article/details/gtnxqabakk.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.yuxming.cn/Article/details/gtirjwbkix.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.haohaochexian.top/Article/details/gtrvzgretr.html

[D05] 访问与修改元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqylrvyf.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtbrtwbcfi.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.havefunace.top/Article/details/gtdwarchum.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.yj20258.top/Article/details/gtqxpjnuls.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.cdnleiting.top/Article/details/gtquhsnoxc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.wangshuangyany.cn/Article/details/gtigzuvsxk.html


<!-- 参考信息 -->