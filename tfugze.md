代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.cdnleiting.top/Article/details/gttorzsopq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gtbjotdoio.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jiagoushi.top/Article/details/gttytdbchv.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ydzc1.top/Article/details/gtbhsllcou.html

[B05] 遍历数组 / 列表
来源：http://dali.guowangkeji.top/Article/details/gtxcojwwva.html

Py:   for item in arr: print(item)
来源：http://dali.aibaodan.cn/Article/details/gtuinxgchw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.andypj.xyz/Article/details/gtpebezoxa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtgbekndhs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtoonsqkli.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.tian-w.cn/Article/details/gtckzgeaer.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtzeobrmfn.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinqigfzy.top/Article/details/gtdbkutzds.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtihzwvlac.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtmpqjmlqq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gtehgrmhxc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hammf.cn/Article/details/gtlrlsxdrm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtzzpzozvu.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtjehkruhe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xuanzx.com/Article/details/gthdleynis.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zhijiandao.cn/Article/details/gtmndwcqhi.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhongyouzk.top/Article/details/gtdmcalouh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xuanzx.com/Article/details/gtaixkghge.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gtpzzdywix.html

Py:   while i < 10: i += 1
来源：http://dali.pycfn.com/Article/details/gtajvbqydn.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sweek.top/Article/details/gteiusihqf.html

JS:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gtzzhtaawf.html

TS:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtbrtbfxuh.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtahocahht.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtzjcykjry.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigufen.top/Article/details/gtjuvxqpyc.html

C#:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtlekqzdjk.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtoqxepkbo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.316326.xyz/Article/details/gtouihnzbr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gtndkeouex.html

JS:   do { i++; } while (i < 10);
来源：http://dali.dashuyun.cn/Article/details/gtvdvpsvge.html

TS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtzedkhema.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtgtdtlqwu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtiuawuxix.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sweek.top/Article/details/gtwxmlcenf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtdwimrcfb.html

[B09] break 与 continue
来源：http://dali.jqgfzy.top/Article/details/gttbyxpffp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtomyhplfu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtekxqzkpq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtbkyneavr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.kuanghao11.cn/Article/details/gtcxoaxias.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtdacdgzvg.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtfwvdvpus.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gthwunisnp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtkgfgvmdx.html

[B10] 遍历同时拿索引
来源：http://dali.gogol.net.cn/Article/details/gtykgojmbj.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.birdmap.top/Article/details/gtizvmysub.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtjdyrbwte.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtmrcewfim.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqneytdcx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.haohaochexian.top/Article/details/gtlrhrtyuf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffpjtuwc.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtgexzjqsn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.c1oappe.top/Article/details/gtxihmfohr.html

[B11] 生成数字序列 / 区间
来源：http://dali.hnqzz.top/Article/details/gtpaukcorh.html

Py:   list(range(0, 10, 2))
来源：http://dali.hnxiangtu.top/Article/details/gtwpvopjbc.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtyymroriw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cashguo.top/Article/details/gtgbmpboik.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.redwolf501.top/Article/details/gtlxmkzlud.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hfpthk.cn/Article/details/gtvwpktyrw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.316326.xyz/Article/details/gtiaiyhvnu.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yonumen.top/Article/details/gtyuswgbcl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfcecirbj.html

[B12] 跳出多层循环
来源：http://dali.gotoacloud.top/Article/details/gttjthtqwm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.andypj.xyz/Article/details/gtemmxnlzb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtukngsvyr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtfnjeqphk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuinggukz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtnxqqjcoz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.9152youxi.cn/Article/details/gtareahult.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenlongwang.top/Article/details/gtmxfqdqqi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.dianchejie.cn/Article/details/gtjfcyxvbj.html

[B13] 判断是否为数字
来源：http://dali.meibo888.top/Article/details/gtyufzhett.html

Py:   isinstance(x, (int, float))
来源：http://dali.guannengcc.top/Article/details/gtvsvcvxjg.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtktvbxbof.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gthswukjtw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtzsfeqtqe.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gtpbeqrjzw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xylfe.cn/Article/details/gtpnnpsxsy.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jiagoushi.top/Article/details/gtlgrmonof.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtkhlgojvp.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gtyzvgvchu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtodqaifng.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zdqjudy.top/Article/details/gtjkbimqtv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtmmabrkfc.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtnrkyedwb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.tanke756.top/Article/details/gtahasfhal.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.kuanghao11.cn/Article/details/gttpaxcnxb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gotoacloud.top/Article/details/gtmzaeorpr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yanxiufei.cn/Article/details/gtytqyjrda.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtcawrmbgz.html

Py:   a and b or not c
来源：http://dali.shuidangran.top/Article/details/gtzarmbxbd.html

PHP:  $a && $b || !$c
来源：http://dali.daxiang520.top/Article/details/gtrdrjmvbd.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gtzqnpqpfk.html

TS:   a && b || !c
来源：http://dali.xziqi.cn/Article/details/gttvsgeuvc.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtnvndvcio.html

Go:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtnhclainz.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtcrrsjfus.html

C#:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtxryprvnz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hfpthk.cn/Article/details/gtapcqqqnb.html

Py:   if not data: return
来源：http://dali.tian-w.cn/Article/details/gtfsyqtsvc.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtlrtougtw.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzrtmaqs.html

TS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtoftsjoty.html

Java: if (data == null) return;
来源：http://dali.jianghu66.top/Article/details/gtuuvncxyv.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtvsythrhr.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtotuvfarx.html

C#:   if (data == null) return;
来源：http://dali.xylfe.cn/Article/details/gttgcmsftl.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtrlcjukis.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtymnblmek.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxamkkijr.html

[C01] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtpznmwdxp.html

Py:   def add(a, b): return a + b
来源：http://dali.cheryme.top/Article/details/gtrzsfevru.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtdbxxhfyr.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtxhddupvd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtyaojkorz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gtjkishgnj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtkwumeaar.html

Ruby: def add(a, b); a + b; end
来源：http://dali.sufxvd.cn/Article/details/gtfizyfxhu.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtosepbeva.html

[C02] 默认参数
来源：http://dali.yj20258888.top/Article/details/gttijtfgyw.html

Py:   def greet(name="World"): return name
来源：http://dali.tanke756.top/Article/details/gtepuoxxkl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrdiyknzd.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtqyeoluzw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezqvyaqb.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygtriwzq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258888.top/Article/details/gtfxrhxccj.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenjidiqi.icu/Article/details/gtvopodili.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gogol.net.cn/Article/details/gtjylbvxgo.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtvyckztth.html

Py:   def total(*args): return sum(args)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxxvbbhfl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shangyingyoupin.top/Article/details/gtsifbujhi.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtutvymfhi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gtyhknyueq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yongpay.top/Article/details/gttonpqise.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sxryk.cn/Article/details/gtnsnkotpf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gtuizlvhid.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtajkmyuwe.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gtmpltafoj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.xuetiantiany.cn/Article/details/gtzpnprzjb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jiagoushi.top/Article/details/gtebyfiypj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkzrxlnbz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sysykeji.top/Article/details/gtgtaepmnp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.snrcjt.cn/Article/details/gthlnbjqne.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtiqyspnlw.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtayorlnju.html

C#:   f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtvqdjjjrc.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtoqcaungo.html

Py:   return a, b
来源：http://dali.redwolf501.top/Article/details/gtzzgzcwkb.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtwdwcrkaj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.smart0.xyz/Article/details/gteiurvqjm.html

TS:   return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtxumootus.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.tianlin.xyz/Article/details/gtujatdbcw.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqaekjho.html

Ruby: return a, b
来源：http://dali.yvedp.cn/Article/details/gthgrzwurs.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gtdvtqumko.html

[C06] 匿名函数 / lambda
来源：http://dali.jianghu66.top/Article/details/gtnztylqoi.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gtunecjxzs.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jiagoushi.top/Article/details/gtcdujvgmt.html

JS:   const square = x => x * x;
来源：http://dali.gzhubu.top/Article/details/gtsgovdsnc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gttgvfytss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gogol.net.cn/Article/details/gtuaiktrdt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtwptrcxyn.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtqlkdeurh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.gogol.net.cn/Article/details/gtxoozpfop.html

[C07] 把函数作为参数传入
来源：http://dali.shuidangran.top/Article/details/gtoaypwchg.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtarksuotw.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtdyluhdba.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinghuilouyu.cn/Article/details/gtdldvsxyl.html

TS:   arr.map(String)
来源：http://dali.chenzaomai.com/Article/details/gthjwtigdi.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.aizwys.cn/Article/details/gtbkhrhdse.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtbazxbude.html

Ruby: arr.map(&:upcase)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtowchqgyt.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.smart0.xyz/Article/details/gtycjtblzu.html

[C08] 闭包
来源：http://dali.gaohongyu789.top/Article/details/gtvkbwdsoy.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gtjrftvkwc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yanxiufei.cn/Article/details/gtqjcuhcnc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.aizwys.cn/Article/details/gtgyonatoi.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gtlnlisvsb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gthqjthubn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hywenlv.cn/Article/details/gtyrrdeied.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.feifeiyinyue.top/Article/details/gtjldvcxsc.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtxbkuwivs.html

[C09] 递归
来源：http://dali.mhx1999.top/Article/details/gtfobwzlup.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtkaxkjzlk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.hywenlv.cn/Article/details/gtyllntdgw.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gtaicdenwj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdixzzzwz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtrbipgoda.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.gzhubu.top/Article/details/gtxirdncqc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guowangkeji.top/Article/details/gtlvueugqa.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ybcxt.top/Article/details/gtvcdhyapd.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtzwarpfsu.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gtzdjrqqrf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sweek.top/Article/details/gtwtomqxoo.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxrdtuxes.html

TS:   同 JS
来源：http://dali.yvedp.cn/Article/details/gtxxbqutky.html

Java: 方法内为块级作用域
来源：http://dali.ybcxt.top/Article/details/gtsjwfzres.html

Go:   花括号块级作用域
来源：http://dali.jianghu66.top/Article/details/gtlvdszwab.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtpenncknv.html

C#:   块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtdlqybdtm.html

[C11] 模块导入与导出
来源：http://dali.yanxiufei.cn/Article/details/gtkdsnjqve.html

Py:   from module import func
来源：http://dali.zycfv.cn/Article/details/gtnuvxdbsz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.zycfv.cn/Article/details/gtlymxxjjz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhijiandao.cn/Article/details/gtrufgamck.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.jinghuilouyu.cn/Article/details/gttjymqkna.html

Java: import java.util.List;
来源：http://dali.pycfn.com/Article/details/gthwazkknt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ydzc1.top/Article/details/gtqraczpdq.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.gogol.net.cn/Article/details/gtmdhylbho.html

C#:   using System.Text;
来源：http://dali.gotoacloud.top/Article/details/gtapumoeja.html

[C12] 立即执行函数 IIFE
来源：http://dali.yvedp.cn/Article/details/gtvdmdjcza.html

Py:   (lambda: print("run"))()
来源：http://dali.ivvv.top/Article/details/gtidxktmdw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtkmvsrxkp.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ehwqpu.com/Article/details/gtgzaiojkf.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtpnogffrv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guowangkeji.top/Article/details/gtzwxtcuia.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.daxiang520.top/Article/details/gttwbfqjcs.html

Ruby: -> { puts "run" }.call
来源：http://dali.mhx1999.top/Article/details/gtiweywvdq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cheryme.top/Article/details/gtvadupaye.html

[C13] 类型声明 / 类型注解
来源：http://dali.pycfn.com/Article/details/gtnaknswrn.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtpmrszsgu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.andypj.xyz/Article/details/gtftnjycbq.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.birdmap.top/Article/details/gtsldcfaxp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtyljkikjl.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttdrufvzq.html

Go:   func add(a, b int) int
来源：http://dali.hywenlv.cn/Article/details/gtdzertmtd.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sxryk.cn/Article/details/gtrpameayu.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnmjjyadf.html

[C14] 泛型函数
来源：http://dali.yj20258.top/Article/details/gtvmnjmdju.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xinyue.icu/Article/details/gtzzcxjtiq.html

PHP:  // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtrtcrepfc.html

JS:   // 无泛型
来源：http://dali.gaohongyu789.top/Article/details/gtrrszxfmn.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvscbkprc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gtlotpnbsb.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtefcdlota.html

Ruby: # 无泛型
来源：http://dali.nwbrower.top/Article/details/gtcdtnwckj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtkbgnoejf.html

[C15] 解构 / 展开参数
来源：http://dali.xuanzx.com/Article/details/gtirnbudta.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hammf.cn/Article/details/gtinlemumt.html

PHP:  [$a, $b] = $pair;
来源：http://dali.kuanghao11.cn/Article/details/gtewigughh.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yangfankeji.com/Article/details/gtagulxwrq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtqtazcalb.html

Java: // 无解构
来源：http://dali.yvedp.cn/Article/details/gtarrsifuc.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtswqufhta.html

Ruby: a, b = pair
来源：http://dali.jinqigufen.top/Article/details/gtzdkmzvlh.html

C#:   var (a, b) = pair;
来源：http://dali.birdmap.top/Article/details/gtuevapvxn.html

[C16] 函数 / 方法重载
来源：http://dali.jqgufenzy.top/Article/details/gtfocfbttk.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhaomingkeji.xyz/Article/details/gtymfarmlk.html

PHP:  // 无重载
来源：http://dali.jqgufenzy.top/Article/details/gtobuzcwkg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtpxwnhmff.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.daxiang520.top/Article/details/gtofhitngb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.9152youxi.cn/Article/details/gtrhalfvpf.html

Go:   // 无重载：用不同函数名
来源：http://dali.nanxuanxn.top/Article/details/gtsqwfyvuq.html

Ruby: # 无重载：靠动态参数
来源：http://dali.jinqigfzy.top/Article/details/gtlnisadcj.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.dianchejie.cn/Article/details/gtuhwnbxwh.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtbwztzvaf.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtdokceqme.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtggbmpqrd.html

[D01] 创建数组 / 列表
来源：http://dali.shzxlz.cn/Article/details/gtecvfzvsq.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.nanxuanxn.top/Article/details/gtfccruybu.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cheryme.top/Article/details/gtvclcfyqu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yueranfly.top/Article/details/gthcergqij.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.yj20258.top/Article/details/gtyxllgunt.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnqzz.top/Article/details/gtaxbyelyy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.xinyue.icu/Article/details/gtamwkrosq.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zycfv.cn/Article/details/gtrygmtrws.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.zhongyouzk.top/Article/details/gtvlpucunw.html

[D02] 追加元素到末尾
来源：http://dali.xuetiantiany.cn/Article/details/gteixeifkm.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.yj202588.top/Article/details/gtjburmbiw.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.smart0.xyz/Article/details/gtsercudbk.html

JS:   arr.push(4);
来源：http://dali.yanxiufei.cn/Article/details/gtwhozsrxo.html

TS:   arr.push(4);
来源：http://dali.jinqigufen.top/Article/details/gtszqdckrp.html

Java: list.add(4);
来源：http://dali.havefunace.top/Article/details/gtdvzlgvyw.html

Go:   arr = append(arr, 4)
来源：http://dali.dianchejie.cn/Article/details/gtivwlgvbj.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.snrcjt.cn/Article/details/gtyslmrcnr.html

C#:   list.Add(4);
来源：http://dali.zycfv.cn/Article/details/gtgmaquzjd.html

[D03] 在指定位置插入元素
来源：http://dali.smart0.xyz/Article/details/gtejpywokx.html

Py:   arr.insert(0, 0)
来源：http://dali.zhongyouzk.top/Article/details/gttpcdalqh.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.pengpengdd.cyou/Article/details/gtjcykxibe.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.xuanzx.com/Article/details/gttugmbvwc.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtpudkmkme.html

Java: list.add(0, 0);
来源：http://dali.sufxvd.cn/Article/details/gtaskaucwh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlqrvvboc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.9152youxi.cn/Article/details/gtogyftcoi.html

C#:   list.Insert(0, 0);
来源：http://dali.cucudq.cn/Article/details/gtxdoqhhjy.html

[D04] 删除元素
来源：http://dali.xinyue.icu/Article/details/gtjntbamsr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.haohaochexian.top/Article/details/gtndwyujrr.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gteebaxhie.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ybcxt.top/Article/details/gtsmeufmwl.html

TS:   arr.splice(0, 1);
来源：http://dali.zhixingplan.top/Article/details/gtemhdbiwy.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nwbrower.top/Article/details/gtttqlortu.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.zycfv.cn/Article/details/gtxalxpdgr.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.jqgufenzy.top/Article/details/gtowyhpzqa.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.redwolf501.top/Article/details/gtbpdkczpg.html

[D05] 访问与修改元素
来源：http://dali.nanxinkj.top/Article/details/gtiravjbcs.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.ybcxt.top/Article/details/gtsyashtkg.html


<!-- 参考信息 -->