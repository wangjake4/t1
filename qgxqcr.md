代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.daxiang520.top/Article/details/gtdmlatssf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.tianlin.xyz/Article/details/gtpnlxwkmy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jqgfzy.top/Article/details/gtngpykzii.html

[B04] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtxpfyqkjp.html

Py:   for i in range(10): print(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtyminwoji.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gteggjppjt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtzpnhnivc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gttrherfgu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtyjtdhazi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtllbkwjpo.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gtcyprfykf.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtlrwrcegl.html

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtbbjkdfrx.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtogxeqxwe.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdecvuscs.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gthyyttstp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.daxiang520.top/Article/details/gtaxxofjuw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gtajxwsshf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yonumen.top/Article/details/gtjssfpzwl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shanyushiyangtech.top/Article/details/gtactmvstf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gtcstptrjq.html

[B06] 遍历字典 / 对象
来源：http://dali.zycfv.cn/Article/details/gtghavhqiu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.mhx1999.top/Article/details/gtgjyasqnb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtxhlngxhx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhongyouzk.top/Article/details/gtofongbox.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gteyfucuxs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hnxiangtu.top/Article/details/gtejecpjrq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.kuanghao11.cn/Article/details/gtopexeamf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.xuanzx.com/Article/details/gtfltpqupd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hammf.cn/Article/details/gtmgiprxxu.html

[B07] while 循环
来源：http://dali.cheryme.top/Article/details/gtbvnaehdo.html

Py:   while i < 10: i += 1
来源：http://dali.316326.xyz/Article/details/gtedjupdlu.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jlsjyb.cn/Article/details/gthhjbznek.html

JS:   while (i < 10) { i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gtxzryjlmo.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtvawqofki.html

Java: while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtfjzvdssm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtrqbdodri.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gtvonoxvgl.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtsmqtjcrv.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gtmbjbjkjk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.daxiang520.top/Article/details/gtusfhpxdw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtkasfqosp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtpkxxipjn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtlmevyqeh.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtolxruijh.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtewkipdmt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xziqi.cn/Article/details/gtkxeifboz.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtxzjtugbg.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtgtajsfpc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gtfrdkqcmc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtozcsrkcw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtxyfxzwjz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtriahqkyi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtdklwtyuw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.guannengcc.top/Article/details/gtfhmhxfmc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.birdmap.top/Article/details/gtkbwojink.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gthgzbcylr.html

[B10] 遍历同时拿索引
来源：http://dali.hammf.cn/Article/details/gtxpfdgehb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtyhdrjpwl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gogol.net.cn/Article/details/gtbbkgkpct.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtnmgcugdx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gttcmtmnif.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtgjlnskqq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.guannengcc.top/Article/details/gtxjnvtkcl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbjwplfuh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.havefunace.top/Article/details/gtchzojtvu.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtkyinpbic.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtzvfbltrs.html

PHP:  range(0, 10, 2);
来源：http://dali.gzhubu.top/Article/details/gtsdrmmufx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtogqxamgd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtpemqfiyf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtsylhrerv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtidjvgloh.html

Ruby: (0...10).step(2).to_a
来源：http://dali.dianchejie.cn/Article/details/gtbvkpwyol.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ivvv.top/Article/details/gtcpqvcmhm.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtyiqzxlfu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtqrcamoef.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtqwqylqka.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtzlzkawtm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtcixmoeew.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtanitmmqa.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gtljuyxzbo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cucudq.cn/Article/details/gtcxkhlgfh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gotoacloud.top/Article/details/gtjfywdcbd.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtmulzjxak.html

Py:   isinstance(x, (int, float))
来源：http://dali.jyoumei.cn/Article/details/gtxabgxrzh.html

PHP:  is_numeric($x)
来源：http://dali.zdqjudy.top/Article/details/gtabvprjpn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtttypvbhz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtkvevkkif.html

Java: x instanceof Number
来源：http://dali.chenlongwang.top/Article/details/gtkcswqazz.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gtdroaekbu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hfpthk.cn/Article/details/gthwcurspq.html

C#:   x is int or double or decimal
来源：http://dali.sufxvd.cn/Article/details/gtsbjwnbzh.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtkvequjen.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtsmymcvbj.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.cheryme.top/Article/details/gtlnillyqa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxuanxn.top/Article/details/gtjpmzynee.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtzvpyayck.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jiagoushi.top/Article/details/gtogwlunjw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jinqigfzy.top/Article/details/gtkfrzdhfm.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ehwqpu.com/Article/details/gtlazlhlba.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgfzy.top/Article/details/gtevvebxbu.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gtplgwizhj.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gttdateklp.html

PHP:  $a && $b || !$c
来源：http://dali.sysykeji.top/Article/details/gtkehjqnju.html

JS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtvawuqknd.html

TS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtzuulykaw.html

Java: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtvokmwbjp.html

Go:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtmbeqxigd.html

Ruby: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtcyiqojmq.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtzddhwvnm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenlongwang.top/Article/details/gtinbpgpth.html

Py:   if not data: return
来源：http://dali.zhongyouzk.top/Article/details/gtozvioeci.html

PHP:  if (!$data) { return; }
来源：http://dali.9152youxi.cn/Article/details/gtrenonwje.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtdnrilrjf.html

TS:   if (!data) return;
来源：http://dali.jiagoushi.top/Article/details/gttlmiewxy.html

Java: if (data == null) return;
来源：http://dali.birdmap.top/Article/details/gtiimgmkgl.html

Go:   if data == nil { return }
来源：http://dali.hysaishi.cn/Article/details/gtwdszphin.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtcdrzqapw.html

C#:   if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtilmelequ.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtmyrmuxat.html

C. 函数与作用域
来源：http://dali.tanke756.top/Article/details/gtguxcmxxp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxnknzla.html

[C01] 定义函数
来源：http://dali.tian-w.cn/Article/details/gtiqsxddnh.html

Py:   def add(a, b): return a + b
来源：http://dali.9152youxi.cn/Article/details/gtzghpoofi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtxpalpajk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gtmvcrhygi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtmofmjmfa.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtjmpjlloa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gteyxrkbqa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.daxiang520.top/Article/details/gtctikxqaw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gtpskfkiwz.html

[C02] 默认参数
来源：http://dali.shzxlz.cn/Article/details/gtqtxawzre.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtcynddkbt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyubowvn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtgyjzdtge.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtyvetzyfk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtnnyepbdn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj202588.top/Article/details/gtorcdomkx.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtxxvczywh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtgqnmcyeh.html

[C03] 可变参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlxwalmx.html

Py:   def total(*args): return sum(args)
来源：http://dali.iojbl.cn/Article/details/gtepmccjws.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtldpdmmod.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gtvgmkiurp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gtwnqywval.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.xuanzx.com/Article/details/gtkiozdbkx.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yueranfly.top/Article/details/gtchwdexxs.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.meibo888.top/Article/details/gtatlkfjam.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yongpay.top/Article/details/gtrwvijlke.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jyoumei.cn/Article/details/gtmxxjputf.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yvedp.cn/Article/details/gtnpthstaq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.mhx1999.top/Article/details/gtstdbbwmh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtwsmrafov.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.shuidangran.top/Article/details/gtrnvyewno.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtstrdhqsk.html

Go:   // 无：用配置结构体参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvrtatdqc.html

Ruby: f(a: 1, b: 2)
来源：http://dali.vqdsnc.cn/Article/details/gtkpvekepg.html

C#:   f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtuasfuzly.html

[C05] 返回多个值
来源：http://dali.hysaishi.cn/Article/details/gtvrtbbqqc.html

Py:   return a, b
来源：http://dali.yanxiufei.cn/Article/details/gtlcbccgru.html

PHP:  return [$a, $b];
来源：http://dali.yangfankeji.com/Article/details/gtjattcwmg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtamflxkdu.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtwtgkaear.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.dianchejie.cn/Article/details/gtjrgavjvt.html

Go:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtowjvvvcw.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtaygqewza.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.mhx1999.top/Article/details/gtmnepeapd.html

[C06] 匿名函数 / lambda
来源：http://dali.ppjwa.cn/Article/details/gtndjtawbo.html

Py:   square = lambda x: x * x
来源：http://dali.yj20258888.top/Article/details/gtrltrdvft.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hammf.cn/Article/details/gtugybfzwg.html

JS:   const square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtnxrdiggi.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtpevcxhho.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwybhbdnc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gtuqpbgcqu.html

Ruby: square = ->(x) { x * x }
来源：http://dali.birdmap.top/Article/details/gtupadjppo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hfpthk.cn/Article/details/gtataaywjx.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gtyyvcknxm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenjidiqi.icu/Article/details/gtanoxlbsk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtkwyzuitr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.meibo888.top/Article/details/gtaeinxytl.html

TS:   arr.map(String)
来源：http://dali.chenlongwang.top/Article/details/gthebxchge.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yj20258888.top/Article/details/gtgyjlicrh.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.tanke756.top/Article/details/gtkcifabsi.html

Ruby: arr.map(&:upcase)
来源：http://dali.fzhhl.top/Article/details/gtiziyrvye.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtcdyzdjks.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gtyrtlagvc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.wangdashe.top/Article/details/gtysdqzmzl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jyoumei.cn/Article/details/gthpqbfpkp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhoulong.xyz/Article/details/gtziwkkudk.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtbmqtznvb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtpjdsxxwa.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.nanxinkj.top/Article/details/gtillbehzd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hysaishi.cn/Article/details/gthmpsedcb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtcllkdowb.html

[C09] 递归
来源：http://dali.guowangkeji.top/Article/details/gtgcskzrvt.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gteorhyppy.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtkvxqormo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtqofkzgoq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtpxfnpoip.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yongpay.top/Article/details/gtimjuuzaa.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sufxvd.cn/Article/details/gtmxmeyjpo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.nanxinkj.top/Article/details/gtfsuslxcw.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hysaishi.cn/Article/details/gttljtkozt.html

[C10] 变量作用域
来源：http://dali.yj202588.top/Article/details/gtnrssdktd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.chenzaomai.com/Article/details/gtsmdoadrz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cucudq.cn/Article/details/gtuapqeotu.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gtsnxypfkf.html

TS:   同 JS
来源：http://dali.ppjwa.cn/Article/details/gtwvsmiycr.html

Java: 方法内为块级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtpxzjxadk.html

Go:   花括号块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtyvueqjmj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fengsongda.top/Article/details/gtewqyueeb.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtyxmbtpbm.html

[C11] 模块导入与导出
来源：http://dali.cdnleiting.top/Article/details/gtdsfqsiqy.html

Py:   from module import func
来源：http://dali.xinyue.icu/Article/details/gtaiohuysh.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gtiavifasf.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jqgfzy.top/Article/details/gtfqginuru.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.zdqjudy.top/Article/details/gtqkhptvlw.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtwfehxocm.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.dashuyun.cn/Article/details/gtfnxhrvoj.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.guannengcc.top/Article/details/gthcbfmqqp.html

C#:   using System.Text;
来源：http://dali.feifeiyinyue.top/Article/details/gtrrbfajkl.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gthrqgwsdu.html

Py:   (lambda: print("run"))()
来源：http://dali.yueranfly.top/Article/details/gtxxtzkizf.html

PHP:  (function () { echo "run"; })();
来源：http://dali.hysaishi.cn/Article/details/gtvyeaynkp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.redwolf501.top/Article/details/gtuxzmbvkw.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gteswcppck.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gtxbkhajue.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtvdceawtx.html

Ruby: -> { puts "run" }.call
来源：http://dali.pycfn.com/Article/details/gtpeskqwpu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtmkbvbehz.html

[C13] 类型声明 / 类型注解
来源：http://dali.tanke756.top/Article/details/gtbpdipbwl.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jianghu66.top/Article/details/gtdsayhktg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtrcaxuorc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.sufxvd.cn/Article/details/gtfnfsykms.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtdzoyqjlk.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gttuisiqmo.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gtflfyppqb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gteunbepze.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zhiwuduotai.top/Article/details/gteulvpazb.html

[C14] 泛型函数
来源：http://dali.sxryk.cn/Article/details/gtaoufpdel.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gtrxtljrjw.html

PHP:  // 无泛型
来源：http://dali.mhx1999.top/Article/details/gtiuudgxld.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtteskddcd.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.pycfn.com/Article/details/gtvvjhdbwa.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gttybpmurk.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gtrpzrpoea.html

Ruby: # 无泛型
来源：http://dali.yuxming.cn/Article/details/gtuwqripwl.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.daxiang520.top/Article/details/gtowltkvfp.html

[C15] 解构 / 展开参数
来源：http://dali.dianchejie.cn/Article/details/gtquetahky.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jinqigfzy.top/Article/details/gtbnxpokyc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shuidangran.top/Article/details/gtekryngav.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.c1oappe.top/Article/details/gthuoextfc.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.smart0.xyz/Article/details/gtbsrtehhy.html

Java: // 无解构
来源：http://dali.tian-w.cn/Article/details/gtkrjremll.html

Go:   // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtozdewkwu.html

Ruby: a, b = pair
来源：http://dali.zhaomingkeji.xyz/Article/details/gtesrtmlfx.html

C#:   var (a, b) = pair;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlzjedvvi.html

[C16] 函数 / 方法重载
来源：http://dali.cucudq.cn/Article/details/gtigexifmt.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.xylfe.cn/Article/details/gttltqqlcw.html

PHP:  // 无重载
来源：http://dali.xuanzx.com/Article/details/gtrwlauxjo.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.nanxuanxn.top/Article/details/gtqxhquotv.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.quarkkingdee.top/Article/details/gtdoqmoncc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.quarkkingdee.top/Article/details/gtjmlwpiyh.html

Go:   // 无重载：用不同函数名
来源：http://dali.daria6918.cn/Article/details/gtuxwltlic.html

Ruby: # 无重载：靠动态参数
来源：http://dali.andypj.xyz/Article/details/gtzzalzkos.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hnxiangtu.top/Article/details/gtnyressqk.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtmyifmwme.html

D. 数组 / 列表 / 集合
来源：http://dali.chenzaomai.com/Article/details/gteygmsjax.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtwgmcnfui.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gthlomudzj.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.fzhhl.top/Article/details/gtdjgltvmr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.xylfe.cn/Article/details/gtmeesiydn.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.mhx1999.top/Article/details/gtydmimukz.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.cheryme.top/Article/details/gtgjdtzodj.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.zhixingplan.top/Article/details/gtmnoqbyqa.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.hywenlv.cn/Article/details/gthxaeexyd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.chenlongwang.top/Article/details/gteoccplvt.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.nanxuanxn.top/Article/details/gtjvzhxzxr.html

[D02] 追加元素到末尾
来源：http://dali.zhoulong.xyz/Article/details/gtysbcnuda.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.zhongyouzk.top/Article/details/gtvcolyqma.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gteydcezrr.html

JS:   arr.push(4);
来源：http://dali.gotoacloud.top/Article/details/gtanvwqawp.html

TS:   arr.push(4);
来源：http://dali.yuxming.cn/Article/details/gtlxapcmwk.html

Java: list.add(4);
来源：http://dali.xuanzx.com/Article/details/gtfskmjjbz.html

Go:   arr = append(arr, 4)
来源：http://dali.xinyue.icu/Article/details/gthwkruaep.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.birdmap.top/Article/details/gtqedfznvb.html

C#:   list.Add(4);
来源：http://dali.snrcjt.cn/Article/details/gtjyuzmepw.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtoxrgawzr.html

Py:   arr.insert(0, 0)
来源：http://dali.zycfv.cn/Article/details/gtwayfhmzo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtldftbiyq.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.hysaishi.cn/Article/details/gtdzzyrshn.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.hysaishi.cn/Article/details/gtjwgqbpbf.html

Java: list.add(0, 0);
来源：http://dali.xinyue.icu/Article/details/gtpyjwobho.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.guowangkeji.top/Article/details/gtgjxkvdkb.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtnnbvsnyq.html

C#:   list.Insert(0, 0);
来源：http://dali.chenlongwang.top/Article/details/gtlgxebipv.html

[D04] 删除元素
来源：http://dali.gogol.net.cn/Article/details/gtajsiurbc.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhoulong.xyz/Article/details/gtfjtitzjt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ivvv.top/Article/details/gtaubesbuz.html


<!-- 参考信息 -->