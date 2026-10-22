代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.zhiwuduotai.top/Article/details/gtuyjstllr.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtazfznqxw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmkwtcxpu.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gogol.net.cn/Article/details/gtmnewaeir.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gtqdqfjoej.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gtpifcaqno.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyubjpncd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gtwbqjdhcx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.fengsongda.top/Article/details/gtdyozhoub.html

[B06] 遍历字典 / 对象
来源：http://dali.haohaochexian.top/Article/details/gtmcdyllja.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfyrufms.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvbuoaris.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.iojbl.cn/Article/details/gthjrzedvg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtqpyjrsjm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtmwidykvb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gtmmfyvhic.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shuidangran.top/Article/details/gtmjshoemw.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cucudq.cn/Article/details/gtgqiogsdh.html

[B07] while 循环
来源：http://dali.yj20258888.top/Article/details/gtkdtaauaq.html

Py:   while i < 10: i += 1
来源：http://dali.gotoacloud.top/Article/details/gtuvpvhcbb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.havefunace.top/Article/details/gtoertnwlu.html

JS:   while (i < 10) { i++; }
来源：http://dali.jyoumei.cn/Article/details/gtylwhqkhg.html

TS:   while (i < 10) { i++; }
来源：http://dali.vqdsnc.cn/Article/details/gtjoeveapb.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtxhgndcfz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gogol.net.cn/Article/details/gtphcphnrw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ybcxt.top/Article/details/gtujwhfsxz.html

C#:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtauuoznpg.html

[B08] do-while（至少执行一次）
来源：http://dali.wangdashe.top/Article/details/gtebkwggwd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtisjrofdw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.fzhhl.top/Article/details/gtcyiyrhhf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtifaknrix.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthawzzotl.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtznovxgcw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtyxtmplxq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gtgmsktnbd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtjmhyjkcn.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiknxaim.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gthixhkrzt.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtzptoxuuz.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zycfv.cn/Article/details/gtodljefqu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtqikahpch.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenzaomai.com/Article/details/gtnhvprmkv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gtfurxrwny.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxmamkmjf.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtgpeenmax.html

[B10] 遍历同时拿索引
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfzfofaw.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gtmefvoekz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtlrvebhcm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtbifnibxc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tian-w.cn/Article/details/gtfbqqhvvs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guowangkeji.top/Article/details/gtkevilxpw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gtzhkkgkro.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cashguo.top/Article/details/gtquwgjigl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gotoacloud.top/Article/details/gtclotpxdw.html

[B11] 生成数字序列 / 区间
来源：http://dali.yongpay.top/Article/details/gtwtosqafy.html

Py:   list(range(0, 10, 2))
来源：http://dali.guannengcc.top/Article/details/gtumuufujw.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtkzuuglcw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gtapjcsmpx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjzvajul.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yanxiufei.cn/Article/details/gtbfigfjko.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtvclqgoox.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmernowyy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtpsmhdybz.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtrevezcrw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtdfmzhdvl.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gtieiceyak.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtmanayhfh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sysykeji.top/Article/details/gtlkixihul.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtthadhjes.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtycxbkpqt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtouvexved.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gtsnlrjjub.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gtqiyvxoxm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gtzxutufpp.html

PHP:  is_numeric($x)
来源：http://dali.ehwqpu.com/Article/details/gtdzqwctpr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hywenlv.cn/Article/details/gtmwvqvacs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtttmywtjr.html

Java: x instanceof Number
来源：http://dali.jinqigfzy.top/Article/details/gtyqtrqetk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gtwrxgwvje.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtuqihiwzj.html

C#:   x is int or double or decimal
来源：http://dali.cqqwz.cn/Article/details/gtqvdxcwra.html

[B14] 判断值是否在集合内
来源：http://dali.jyoumei.cn/Article/details/gtrvnrpuaf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtxzionxuj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkfjokdb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hysaishi.cn/Article/details/gtlnurhamr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hnxiangtu.top/Article/details/gtpnhvetgj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtbqsvnuge.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gthhhanfgw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtdodsroon.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtvepdbxch.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtjbexeexh.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtqyphugwb.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtutnncpqa.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtvpeztsvs.html

TS:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkpimnqoa.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtckzghcmf.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtjvnqhbdv.html

Ruby: a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrpbnhaq.html

C#:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtnnscespr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jiagoushi.top/Article/details/gtlughhglb.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gttjrrbrkf.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtyphxidas.html

JS:   if (!data) return;
来源：http://dali.hnxiangtu.top/Article/details/gtvcgptagb.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gturmmphjy.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtbvmngivl.html

Go:   if data == nil { return }
来源：http://dali.yonumen.top/Article/details/gtewchawhz.html

Ruby: return if data.nil?
来源：http://dali.cqqwz.cn/Article/details/gtzrotqepb.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gtkxjemmxw.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtmunbaqpw.html

C. 函数与作用域
来源：http://dali.dianchejie.cn/Article/details/gtotashxuz.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkialbgt.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtvbszdbhi.html

Py:   def add(a, b): return a + b
来源：http://dali.nwbrower.top/Article/details/gtrhaqhrzy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtafswauin.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtbgtrmdxu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtgipprqor.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmjquwbd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcuejrbqc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhoulong.xyz/Article/details/gtxhyhbhjy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtzqfvqwex.html

[C02] 默认参数
来源：http://dali.snrcjt.cn/Article/details/gtqwufregy.html

Py:   def greet(name="World"): return name
来源：http://dali.jlsjyb.cn/Article/details/gtwfrtciar.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiykvujlo.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yueranfly.top/Article/details/gtibcdcxsq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtylruefhu.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzkkoeaxm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.xuanzx.com/Article/details/gtajfgdmvm.html

Ruby: def greet(name = "World") = name
来源：http://dali.yj20258888.top/Article/details/gtvlpcrrqr.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtkepzrwlh.html

[C03] 可变参数
来源：http://dali.yueranfly.top/Article/details/gtcekuwvpk.html

Py:   def total(*args): return sum(args)
来源：http://dali.yj20258.top/Article/details/gtjnxworzj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtqlvlcdro.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.bjfxy.top/Article/details/gtkdauzdkm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gttfzrvaeb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtrlyamsmw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.nwbrower.top/Article/details/gtsgxtlbyo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtheqjhmfu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.fzhhl.top/Article/details/gtpcscmwkf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtupbgztsx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gzhubu.top/Article/details/gtqhhsxsib.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guowangkeji.top/Article/details/gtylgtyyoy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtfvmiyesk.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gtwidruzux.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhongyouzk.top/Article/details/gtmzqnxcsq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gtthmrbzmo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gtuwtacdbd.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gtguwqwghy.html

[C05] 返回多个值
来源：http://dali.sufxvd.cn/Article/details/gtavybshhp.html

Py:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtvnsxvrky.html

PHP:  return [$a, $b];
来源：http://dali.yanxiufei.cn/Article/details/gttkaofvvs.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtzpecnhih.html

TS:   return { a, b };
来源：http://dali.vqdsnc.cn/Article/details/gtitontzoq.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fzhhl.top/Article/details/gtvrctfzjh.html

Go:   return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtxppshxoc.html

Ruby: return a, b
来源：http://dali.aizwys.cn/Article/details/gttkxrnymn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258.top/Article/details/gtmbjikdym.html

[C06] 匿名函数 / lambda
来源：http://dali.aibaodan.cn/Article/details/gtkdhwfzbh.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtqoeeeevz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gtjdlwedzd.html

JS:   const square = x => x * x;
来源：http://dali.snrcjt.cn/Article/details/gtbckiihtk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtuyyennol.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gttahxgapw.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gtpdqjectf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shuidangran.top/Article/details/gtdjeprxra.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yj20258888.top/Article/details/gtugnmijaj.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gtknmywvbb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxgvssswq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtfaovvtna.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtgvyhrqyq.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gtnrdneslk.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xinyue.icu/Article/details/gtmgyhvuhj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.0kj1m.cn/Article/details/gtcfyohlaq.html

Ruby: arr.map(&:upcase)
来源：http://dali.jinqigfzy.top/Article/details/gtvqsesuki.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtbbarhxgg.html

[C08] 闭包
来源：http://dali.zdqjudy.top/Article/details/gtevyyqqhk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtcaigbfwf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gthxyalpfq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteoclunly.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gthtamfwiw.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cashguo.top/Article/details/gttybbutvi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gthswmcvdd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.dianchejie.cn/Article/details/gtarumwhpq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbdtkwla.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtuolsewsh.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtennfaumn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gtldfvaxhf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sysykeji.top/Article/details/gtfcnsifdg.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gtbybuehom.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gtcskiljxl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ybcxt.top/Article/details/gtcdbczsbd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gtykmvlwyl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shzxlz.cn/Article/details/gtaavjkopw.html

[C10] 变量作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtezncytjq.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.snrcjt.cn/Article/details/gtllpwdxyu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.andypj.xyz/Article/details/gtpnnxbqwb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.smart0.xyz/Article/details/gtoehjfxix.html

TS:   同 JS
来源：http://dali.jyoumei.cn/Article/details/gtmeogazyg.html

Java: 方法内为块级作用域
来源：http://dali.svipenyu.cn/Article/details/gtlonpwmtd.html

Go:   花括号块级作用域
来源：http://dali.yonumen.top/Article/details/gtoavdufgn.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.wangshuangyany.cn/Article/details/gtxelgegxc.html

C#:   块级作用域
来源：http://dali.snrcjt.cn/Article/details/gthjfvswor.html

[C11] 模块导入与导出
来源：http://dali.feifeiyinyue.top/Article/details/gtbkcmtxxd.html

Py:   from module import func
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzdjpfjf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.kuanghao11.cn/Article/details/gtfolllpkn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yangfankeji.com/Article/details/gttuiodsqt.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gtxoxnrnin.html

Java: import java.util.List;
来源：http://dali.shuidangran.top/Article/details/gtdlgwrabo.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.daxiang520.top/Article/details/gtqhfuofvk.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinqigufen.top/Article/details/gtpbrijvex.html

C#:   using System.Text;
来源：http://dali.dashuyun.cn/Article/details/gtqinhqayx.html

[C12] 立即执行函数 IIFE
来源：http://dali.birdmap.top/Article/details/gthiztritw.html

Py:   (lambda: print("run"))()
来源：http://dali.pengpengdd.cyou/Article/details/gtnvfnqjlk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ydzc1.top/Article/details/gttvjppuwf.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shzxlz.cn/Article/details/gtocimgrmh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtwkgtmqod.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhoulong.xyz/Article/details/gthyehcuoz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tianlin.xyz/Article/details/gtqcesiskl.html

Ruby: -> { puts "run" }.call
来源：http://dali.gaohongyu789.top/Article/details/gtkrbujrxw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jyoumei.cn/Article/details/gtvfhhvlnz.html

[C13] 类型声明 / 类型注解
来源：http://dali.hnxiangtu.top/Article/details/gtlxxhkemb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.tianlin.xyz/Article/details/gtykgjyvjr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtzawkhuba.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sweek.top/Article/details/gtbrgufkzn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gtzurjgfir.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtkvtmyxch.html

Go:   func add(a, b int) int
来源：http://dali.shanyushiyangtech.top/Article/details/gtrednkklq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yueranfly.top/Article/details/gtrvjqcies.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.chenzaomai.com/Article/details/gtuzrvovgl.html

[C14] 泛型函数
来源：http://dali.xuanzx.com/Article/details/gtiqmwsphl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jlsjyb.cn/Article/details/gtrjanjwxu.html

PHP:  // 无泛型
来源：http://dali.yuxming.cn/Article/details/gtfaazzrej.html

JS:   // 无泛型
来源：http://dali.yongpay.top/Article/details/gticonfsgn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.daria6918.cn/Article/details/gtikyxovui.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtunnogtea.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hnxiangtu.top/Article/details/gtzxtdomzw.html

Ruby: # 无泛型
来源：http://dali.guannengcc.top/Article/details/gteshfsfov.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yj20258.top/Article/details/gtucoznfdk.html

[C15] 解构 / 展开参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtertnbqwx.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhongyouzk.top/Article/details/gtwehjzbjl.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ehwqpu.com/Article/details/gtvaoccemx.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jianghu66.top/Article/details/gtxhoizisy.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.316326.xyz/Article/details/gtacnowqqs.html

Java: // 无解构
来源：http://dali.vqdsnc.cn/Article/details/gthlfwtlyj.html

Go:   // 无解构
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlyntqtzl.html

Ruby: a, b = pair
来源：http://dali.ybcxt.top/Article/details/gtynahgkps.html

C#:   var (a, b) = pair;
来源：http://dali.dashuyun.cn/Article/details/gtbldqlwem.html

[C16] 函数 / 方法重载
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtafhavpkl.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sweek.top/Article/details/gtpccdvgjb.html

PHP:  // 无重载
来源：http://dali.yangfankeji.com/Article/details/gtnchjjpgv.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.cdnleiting.top/Article/details/gtfeifnjjf.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yanxiufei.cn/Article/details/gtdwegzhmw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gtorhtzhex.html

Go:   // 无重载：用不同函数名
来源：http://dali.nwbrower.top/Article/details/gtlfqqoqcy.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cucudq.cn/Article/details/gtasbfivqq.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtpicmrawb.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtspxosgug.html

D. 数组 / 列表 / 集合
来源：http://dali.jiagoushi.top/Article/details/gtuwwbckup.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtdcdtluox.html

[D01] 创建数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtxwhkkpxl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.bjfxy.top/Article/details/gtpzxhswrx.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtsvdkumse.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xinyue.icu/Article/details/gtumvbyyqf.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shuidangran.top/Article/details/gtdynslgak.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yuanzhike.top/Article/details/gtmhkkkooy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.daxiang520.top/Article/details/gtzduguwbh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.sufxvd.cn/Article/details/gtczuimqyq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.jlsjyb.cn/Article/details/gtguwbdrwf.html

[D02] 追加元素到末尾
来源：http://dali.nanxuanxn.top/Article/details/gtrfgwpycn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj20258.top/Article/details/gtpbsqqkzt.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxgcnyfe.html

JS:   arr.push(4);
来源：http://dali.xylfe.cn/Article/details/gtlbsmdbwk.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gtbkpuiarm.html

Java: list.add(4);
来源：http://dali.nwbrower.top/Article/details/gtnnklmtlc.html

Go:   arr = append(arr, 4)
来源：http://dali.nanxuanxn.top/Article/details/gtzpzjtvie.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.jiagoushi.top/Article/details/gtqvzsxujr.html

C#:   list.Add(4);
来源：http://dali.yanxiufei.cn/Article/details/gthpcurnqc.html

[D03] 在指定位置插入元素
来源：http://dali.sxryk.cn/Article/details/gtvymiiedj.html

Py:   arr.insert(0, 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtczayuabl.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yj20258888.top/Article/details/gtuorkvwzy.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.ywan-chungtsiang.top/Article/details/gttpibcapn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllcnbmqd.html

Java: list.add(0, 0);
来源：http://dali.zycfv.cn/Article/details/gtxfeuztsn.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.andypj.xyz/Article/details/gtclhmvshp.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.redwolf501.top/Article/details/gtwcynpdiq.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gtxcxiwjre.html

[D04] 删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtqojmersg.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.ydzc1.top/Article/details/gtebtmpjif.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.vqdsnc.cn/Article/details/gtzzdtkdtm.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.jianghu66.top/Article/details/gtzajbtrwb.html

TS:   arr.splice(0, 1);
来源：http://dali.nanxinkj.top/Article/details/gtxjxspizo.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.jinqigfzy.top/Article/details/gtrehtlleb.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.sufxvd.cn/Article/details/gtidlopvpx.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jlsjyb.cn/Article/details/gtakfueljx.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtsvpibsee.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gtpdtevrkk.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jiagoushi.top/Article/details/gtdiyzmvti.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gtgrgcoqhp.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssakfvlo.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.dianchejie.cn/Article/details/gtxkasooea.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yonumen.top/Article/details/gtcyhfbnxb.html


<!-- 参考信息 -->