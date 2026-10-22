代发 wailian999

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2udaylcae.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gt2bzlzvmhw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhijiandao.cn/Article/details/gt2pycvswug.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gt2yfqyqqcx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gt2ooyltcqv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gt2nmqoixdy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dianchejie.cn/Article/details/gt2kdzknidf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gt2nxmrsvrm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gt2nwsigkok.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pvflrpcs.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gt2flquxiwv.html

Py:   while i < 10: i += 1
来源：http://dali.jiagoushi.top/Article/details/gt2lzkjinxk.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2ucdcugep.html

JS:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gt2juuscawy.html

TS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gt2deswasia.html

Java: while (i < 10) { i++; }
来源：http://dali.cheryme.top/Article/details/gt2htxvxmfi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sweek.top/Article/details/gt2nbhyxrdk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gt2iajyhucr.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2txtkezkg.html

[B08] do-while（至少执行一次）
来源：http://dali.hywenlv.cn/Article/details/gt2iqottsxl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.iojbl.cn/Article/details/gt2sykkkgif.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2gifjqtva.html

JS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gt2vxtbinwm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gt2dgmtoipd.html

Java: do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gt2fgcoxkez.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2yefxzcvh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.pengpengdd.cyou/Article/details/gt2qlaafhrk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gt2ayymrdxk.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gt2ejcpbapj.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gt2rjtzzlrm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cucudq.cn/Article/details/gt2jdtawtza.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gt2mewjelau.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gt2dadncqpa.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2bkpcukfw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gt2noqymfbc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xziqi.cn/Article/details/gt2kaiwxgjv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2zcthbkjt.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gt2edomikkk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cheryme.top/Article/details/gt2kcrclufd.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ypoezirm.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yanxiufei.cn/Article/details/gt2rtostaze.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.havefunace.top/Article/details/gt2pivqlurt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pgodxctp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oihhmdfo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hywenlv.cn/Article/details/gt2zyzhnrva.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.daxiang520.top/Article/details/gt2uiqkiihl.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gt2popoodye.html

Py:   list(range(0, 10, 2))
来源：http://dali.yj20258888.top/Article/details/gt2nehkxume.html

PHP:  range(0, 10, 2);
来源：http://dali.dashuyun.cn/Article/details/gt2idwbguiq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gzhubu.top/Article/details/gt2xuuowndo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zycfv.cn/Article/details/gt2cbipytbi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gt2gyupludt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.redwolf501.top/Article/details/gt2exocosvs.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2wrqjwffv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gt2whhpzzmf.html

[B12] 跳出多层循环
来源：http://dali.andypj.xyz/Article/details/gt2azouggru.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gt2snvourrj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ydzc1.top/Article/details/gt2sqngpngs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gt2udxusgxq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gt2btfgxons.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gt2nyugwpyq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daxiang520.top/Article/details/gt2zgnatuce.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.dianchejie.cn/Article/details/gt2wfjjhnrt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cheryme.top/Article/details/gt2csjholde.html

[B13] 判断是否为数字
来源：http://dali.yj20258888.top/Article/details/gt2rwdnbfly.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gt2fwgwnfhp.html

PHP:  is_numeric($x)
来源：http://dali.cdnleiting.top/Article/details/gt2nqefirbo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2smwwcpbg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2rwmaibkw.html

Java: x instanceof Number
来源：http://dali.zhoulong.xyz/Article/details/gt2cczkypkt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yangfankeji.com/Article/details/gt2btudsosz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yonumen.top/Article/details/gt2qjvoocwl.html

C#:   x is int or double or decimal
来源：http://dali.tanke756.top/Article/details/gt2lytucgps.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gt2hmkrhdwo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yonumen.top/Article/details/gt2exzgvxxg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gt2pqpvotxd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gt2peoqcujg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2bdvwiffa.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.meibo888.top/Article/details/gt2sxkxtvif.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shuidangran.top/Article/details/gt2zcygjxnk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.aibaodan.cn/Article/details/gt2zvlyzzda.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jianghu66.top/Article/details/gt2tqnsgadp.html

[B15] 布尔运算与取反
来源：http://dali.zhongyouzk.top/Article/details/gt2lfpqutig.html

Py:   a and b or not c
来源：http://dali.zhengqikj.top/Article/details/gt2cwbbknnm.html

PHP:  $a && $b || !$c
来源：http://dali.wangdashe.top/Article/details/gt2vjeglpbd.html

JS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2bxmluedc.html

TS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gt2dgdennsk.html

Java: a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2nwnqqjww.html

Go:   a && b || !c
来源：http://dali.xinyue.icu/Article/details/gt2dcbtqdve.html

Ruby: a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2ykkjlqsb.html

C#:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gt2pktdwccp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gt2kabtjxlk.html

Py:   if not data: return
来源：http://dali.ppjwa.cn/Article/details/gt2ekkqsqqm.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gt2rmjizpgl.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gt2qkbzznrr.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gt2sizntkoj.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gt2jqyjhcjq.html

Go:   if data == nil { return }
来源：http://dali.cheryme.top/Article/details/gt2mmtvfhsj.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rzfblnwm.html

C#:   if (data == null) return;
来源：http://dali.bjfxy.top/Article/details/gt2altmxcio.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2pxqixobj.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gt2kfbfnpfe.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2rmkhfalj.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gt2zqfgaqsf.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hneqouaf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nqiackid.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gt2sltzcjqr.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gt2zkcllpxi.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nnpcriwl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gt2zvkdfjlr.html

Ruby: def add(a, b); a + b; end
来源：http://dali.wangdashe.top/Article/details/gt2uuglgcuz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gt2zmqapfvs.html

[C02] 默认参数
来源：http://dali.pengpengdd.cyou/Article/details/gt2pbpuzofb.html

Py:   def greet(name="World"): return name
来源：http://dali.sufxvd.cn/Article/details/gt2lqsvltvd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oxfmeqyc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2wxnvhbki.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zleyilwl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gt2islllgoe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gt2vrfoswgk.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gt2vbyzajdj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gt2wgpdbwde.html

[C03] 可变参数
来源：http://dali.cdnleiting.top/Article/details/gt2ewvszwkc.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gt2ymxtguyq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gt2plrnjfeb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwsbxvoz.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eklfvexb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yangfankeji.com/Article/details/gt2kifmzglg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hysaishi.cn/Article/details/gt2qrtyheyz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenzaomai.com/Article/details/gt2wmkvsgjl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjdsddum.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xnsjqhnw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gt2jqgvtrci.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2mccykudk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gt2apaifrps.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhoulong.xyz/Article/details/gt2uwoaepnu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tian-w.cn/Article/details/gt2uvxvfulb.html

Go:   // 无：用配置结构体参数
来源：http://dali.yanxiufei.cn/Article/details/gt2jdfxvyue.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yonumen.top/Article/details/gt2zldeouyu.html

C#:   f(a: 1, b: 2)
来源：http://dali.andypj.xyz/Article/details/gt2qbnteicg.html

[C05] 返回多个值
来源：http://dali.gzhubu.top/Article/details/gt2opqvvemz.html

Py:   return a, b
来源：http://dali.chenlongwang.top/Article/details/gt2raxombkf.html

PHP:  return [$a, $b];
来源：http://dali.gaohongyu789.top/Article/details/gt2wbuwdipr.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gt2xirinojd.html

TS:   return { a, b };
来源：http://dali.haohaochexian.top/Article/details/gt2psqxqwtb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258888.top/Article/details/gt2uunrfeja.html

Go:   return a, b
来源：http://dali.yuanzhike.top/Article/details/gt2xwcwzbpc.html

Ruby: return a, b
来源：http://dali.chenzaomai.com/Article/details/gt2tddyuwke.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gt2dlzfvqop.html

[C06] 匿名函数 / lambda
来源：http://dali.yj202588.top/Article/details/gt2bprfdyel.html

Py:   square = lambda x: x * x
来源：http://dali.chenzaomai.com/Article/details/gt2vqozvuxo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.pycfn.com/Article/details/gt2ikpkehrl.html

JS:   const square = x => x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lrgxokjq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2wxmookbr.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgfzy.top/Article/details/gt2zjpumtqu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gt2eevhjiky.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cheryme.top/Article/details/gt2mznfvnog.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2leoevgnd.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gt2ogyufupd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.svipenyu.cn/Article/details/gt2mlphplhs.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.9152youxi.cn/Article/details/gt2jpidolhx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.iojbl.cn/Article/details/gt2ingjcftc.html

TS:   arr.map(String)
来源：http://dali.hnxiangtu.top/Article/details/gt2rvdmoecg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2vamisqmv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gt2fsnpbyvm.html

Ruby: arr.map(&:upcase)
来源：http://dali.daxiang520.top/Article/details/gt2exixtwup.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jinqigufen.top/Article/details/gt2mvrnbeng.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gt2nylenqez.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gt2clkyehlt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jlsjyb.cn/Article/details/gt2qbxykswg.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yanxiufei.cn/Article/details/gt2ifqhusby.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gt2wtdsslto.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2licngkmf.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rtsaxdfi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gt2wfcmwxjy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2conpymzn.html

[C09] 递归
来源：http://dali.sysykeji.top/Article/details/gt2rachfvrw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gt2ndkvdcts.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.0kj1m.cn/Article/details/gt2dohcvcer.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gt2nmruydcl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yueranfly.top/Article/details/gt2bvrnycao.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gt2ftpfwbfl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.xuanzx.com/Article/details/gt2tvghomam.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2knhtahoi.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ydzc1.top/Article/details/gt2idmhjfcw.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gt2xlvasmgr.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gt2dbuquyam.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuxming.cn/Article/details/gt2krifnbha.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.redwolf501.top/Article/details/gt2epqclyrb.html

TS:   同 JS
来源：http://dali.jinqigfzy.top/Article/details/gt2gpbytorg.html

Java: 方法内为块级作用域
来源：http://dali.ivvv.top/Article/details/gt2dhbjcecs.html

Go:   花括号块级作用域
来源：http://dali.hnqzz.top/Article/details/gt2kmztqrev.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hywenlv.cn/Article/details/gt2vyvakxvf.html

C#:   块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gt2uxpusehu.html

[C11] 模块导入与导出
来源：http://dali.havefunace.top/Article/details/gt2vzgdnpwz.html

Py:   from module import func
来源：http://dali.jqgfzy.top/Article/details/gt2fqqmbtnh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.svipenyu.cn/Article/details/gt2qhapdumz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hnqzz.top/Article/details/gt2rkmsbmhd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.hnxiangtu.top/Article/details/gt2xwafpavn.html

Java: import java.util.List;
来源：http://dali.cdnleiting.top/Article/details/gt2blflkpiz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cucudq.cn/Article/details/gt2bynnitgq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.mhx1999.top/Article/details/gt2nucwfaqp.html

C#:   using System.Text;
来源：http://dali.jinqigfzy.top/Article/details/gt2ahgzhdiy.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhijiandao.cn/Article/details/gt2umgnueqc.html

Py:   (lambda: print("run"))()
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivsexbbv.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yueranfly.top/Article/details/gt2sarisznr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gt2sznhhqpk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gt2sxqednjy.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.cucudq.cn/Article/details/gt2owefxjpm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gt2vxjbzxac.html

Ruby: -> { puts "run" }.call
来源：http://dali.svipenyu.cn/Article/details/gt2nqnuvgef.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xylfe.cn/Article/details/gt2vwaashvx.html

[C13] 类型声明 / 类型注解
来源：http://dali.ehwqpu.com/Article/details/gt2qymfhguz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gt2qvuqshxh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gt2nknbaijt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jlsjyb.cn/Article/details/gt2jfylcjjy.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2joegcroi.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2qcmyyynu.html

Go:   func add(a, b int) int
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2afqdjomq.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.hywenlv.cn/Article/details/gt2nxsikahi.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.tanke756.top/Article/details/gt2stsifplg.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2yzyhupzw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gt2wwsayayx.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gt2rgkdlgwr.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2aaeiwung.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj20258888.top/Article/details/gt2cilsbgis.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xziqi.cn/Article/details/gt2ncspdmiy.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.chenzaomai.com/Article/details/gt2prurkyaq.html

Ruby: # 无泛型
来源：http://dali.chenjidiqi.icu/Article/details/gt2kbbnxorc.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.zhiwuduotai.top/Article/details/gt2qfgtvcti.html

[C15] 解构 / 展开参数
来源：http://dali.sufxvd.cn/Article/details/gt2rqwtntix.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.c1oappe.top/Article/details/gt2yoehcmsd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ifedfqfk.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2ulfriydx.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.andypj.xyz/Article/details/gt2pteresvh.html

Java: // 无解构
来源：http://dali.sufxvd.cn/Article/details/gt2xklfcktw.html

Go:   // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gt2dokscnqj.html

Ruby: a, b = pair
来源：http://dali.hnxiangtu.top/Article/details/gt2qimpixhw.html

C#:   var (a, b) = pair;
来源：http://dali.pengpengdd.cyou/Article/details/gt2jzcxvjmf.html

[C16] 函数 / 方法重载
来源：http://dali.jianghu66.top/Article/details/gt2yezffrfr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zdqjudy.top/Article/details/gt2ecrfkjwb.html

PHP:  // 无重载
来源：http://dali.sweek.top/Article/details/gt2qqjdkmsh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gaohongyu789.top/Article/details/gt2obxrneml.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hbrmoxqm.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.jianghu66.top/Article/details/gt2bvdtlsrt.html

Go:   // 无重载：用不同函数名
来源：http://dali.gotoacloud.top/Article/details/gt2iuxcidlf.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2chlgwatw.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gt2czlielxh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2sryupdjw.html

D. 数组 / 列表 / 集合
来源：http://dali.pengpengdd.cyou/Article/details/gt2wjxrywfg.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2hiibgwes.html

[D01] 创建数组 / 列表
来源：http://dali.havefunace.top/Article/details/gt2uwvmqxpu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yanxiufei.cn/Article/details/gt2qwawyvjn.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.gotoacloud.top/Article/details/gt2zntmboqm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.aizwys.cn/Article/details/gt2rzwawjbw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xziqi.cn/Article/details/gt2hruzpsme.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zycfv.cn/Article/details/gt2dzjlbqrc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hongshengwenyu.top/Article/details/gt2xyrnlmfr.html

Ruby: arr = [1, 2, 3]
来源：http://dali.tanke756.top/Article/details/gt2wparyjjq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gt2exhpgujd.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gt2jqqoiymb.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.aizwys.cn/Article/details/gt2vhoerhqh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.aibaodan.cn/Article/details/gt2bbbrvjqe.html

JS:   arr.push(4);
来源：http://dali.cdnleiting.top/Article/details/gt2avltaahu.html

TS:   arr.push(4);
来源：http://dali.aibaodan.cn/Article/details/gt2ilxblflx.html

Java: list.add(4);
来源：http://dali.c1oappe.top/Article/details/gt2wcaxapgx.html

Go:   arr = append(arr, 4)
来源：http://dali.hnxiangtu.top/Article/details/gt2ltdyzrku.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.haohaochexian.top/Article/details/gt2dtyusmer.html

C#:   list.Add(4);
来源：http://dali.chenlongwang.top/Article/details/gt2fnleaepr.html

[D03] 在指定位置插入元素
来源：http://dali.zycfv.cn/Article/details/gt2jsgqjaaa.html

Py:   arr.insert(0, 0)
来源：http://dali.cashguo.top/Article/details/gt2msjpwqqg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.ybcxt.top/Article/details/gt2uoxsqsrz.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jinqigufen.top/Article/details/gt2xzusbmlj.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.iojbl.cn/Article/details/gt2snfwyelm.html

Java: list.add(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2pshqrhne.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.tianlin.xyz/Article/details/gt2ookhqjsw.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gt2gxdpkyyq.html

C#:   list.Insert(0, 0);
来源：http://dali.hnqzz.top/Article/details/gt2krzsykgx.html

[D04] 删除元素
来源：http://dali.hongshengwenyu.top/Article/details/gt2akjwxflp.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jianghu66.top/Article/details/gt2ggjsqopm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.fengsongda.top/Article/details/gt2vsjbjpxx.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sxryk.cn/Article/details/gt2bxgvuwzh.html

TS:   arr.splice(0, 1);
来源：http://dali.zycfv.cn/Article/details/gt2cverhvbp.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.feifeiyinyue.top/Article/details/gt2ppoovqpk.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.tian-w.cn/Article/details/gt2peodqtph.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cdnleiting.top/Article/details/gt2mhgmmolf.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.zhengqikj.top/Article/details/gt2yhtfyazt.html

[D05] 访问与修改元素
来源：http://dali.svipenyu.cn/Article/details/gt2hwqabjwx.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.316326.xyz/Article/details/gt2bydsjfbu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cheryme.top/Article/details/gt2xbtxyaha.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.guowangkeji.top/Article/details/gt2godztlcw.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.zhengqikj.top/Article/details/gt2ykoyqggk.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hysaishi.cn/Article/details/gt2rfwbrzqh.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.snrcjt.cn/Article/details/gt2vfkozlzm.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.sweek.top/Article/details/gt2xtokawgv.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.cdnleiting.top/Article/details/gt2gtcedakk.html

[D06] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gt2tlhcuvzp.html

Py:   len(arr)
来源：http://dali.zhongyouzk.top/Article/details/gt2motpneac.html

PHP:  count($arr);
来源：http://dali.daria6918.cn/Article/details/gt2aukggxjs.html

JS:   arr.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2gvrwqvxa.html

TS:   arr.length
来源：http://dali.jqgufenzy.top/Article/details/gt2koxccvmf.html


<!-- 参考信息 -->