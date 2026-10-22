代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtfphugurj.html

Py:   for item in arr: print(item)
来源：http://dali.316326.xyz/Article/details/gtgmhgedsn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.9152youxi.cn/Article/details/gtwbwcaamg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenlongwang.top/Article/details/gtuumyqdxq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hywenlv.cn/Article/details/gtaxvyygyp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtxuzxcmwt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gtyzsuclaf.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gtxaodkkem.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.guannengcc.top/Article/details/gtmfblmqnp.html

[B06] 遍历字典 / 对象
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzshptvs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gtaytawuvw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtygbrpmxu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtrfdtxpic.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gteebvxfxq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtguehhatw.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jyoumei.cn/Article/details/gtzesgruks.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cucudq.cn/Article/details/gtkmgdmpdg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnxiangtu.top/Article/details/gtpqxakbzq.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtshpqmsuj.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtsfdqzynl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuhfwvdck.html

JS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtnjvukctf.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtoukdmluv.html

Java: while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtzukubxld.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ivvv.top/Article/details/gtuzipccda.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhengqikj.top/Article/details/gtjzepinuk.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqfktsxv.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtpskysmue.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtzovztbuj.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtsqgcvddq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gthkppqxhv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtshobcupu.html

Java: do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxghfnmlp.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cqqwz.cn/Article/details/gtkyanwjjq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgufenzy.top/Article/details/gtpjpoemmy.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtwmcsmefj.html

[B09] break 与 continue
来源：http://dali.guannengcc.top/Article/details/gtfenknofp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yonumen.top/Article/details/gtmolwhyjo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtkeyxzzos.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtmrrlaakf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gteiuobkji.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtorgihnhp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cucudq.cn/Article/details/gtfbwhrxky.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.haohaochexian.top/Article/details/gtwpktddog.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtbvlvwftp.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtjoeilkrr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuetiantiany.cn/Article/details/gtdepvplcb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvhqbrby.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtxehigvis.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.pengpengdd.cyou/Article/details/gtjsbcuini.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.c1oappe.top/Article/details/gtqfftjgmh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gtbphyacuo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xylfe.cn/Article/details/gtezvuwyky.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtqhgdenho.html

[B11] 生成数字序列 / 区间
来源：http://dali.svipenyu.cn/Article/details/gtmsgajciw.html

Py:   list(range(0, 10, 2))
来源：http://dali.smart0.xyz/Article/details/gthpbemacf.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gtbywawnvj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxuanxn.top/Article/details/gtdhxyalcd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yvedp.cn/Article/details/gtnahpkvcz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gtifhfzeyu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dashuyun.cn/Article/details/gtbflzvltm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj202588.top/Article/details/gtreqfjbia.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gtpggrmacu.html

[B12] 跳出多层循环
来源：http://dali.havefunace.top/Article/details/gtxbbyiigz.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnqzz.top/Article/details/gtopfinikj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenzaomai.com/Article/details/gtjiikfkzc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fengsongda.top/Article/details/gtcmcykiat.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtscpkyiyn.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtcotwkbyj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cashguo.top/Article/details/gtuklhqzjk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yvedp.cn/Article/details/gtpvrcmgoq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hammf.cn/Article/details/gtmdtzrhrb.html

[B13] 判断是否为数字
来源：http://dali.sweek.top/Article/details/gtjwyatkmw.html

Py:   isinstance(x, (int, float))
来源：http://dali.meibo888.top/Article/details/gtuvcjaqvj.html

PHP:  is_numeric($x)
来源：http://dali.hongshengwenyu.top/Article/details/gthvmboipo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gtgcmpnylg.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgkbvogoe.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtvbxswzdn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.quarkkingdee.top/Article/details/gtpaoplalq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtoktrlqxc.html

C#:   x is int or double or decimal
来源：http://dali.zhongyouzk.top/Article/details/gtqogmwwsa.html

[B14] 判断值是否在集合内
来源：http://dali.feifeiyinyue.top/Article/details/gtljkembmb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtepkocvpq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.sysykeji.top/Article/details/gtuveakyxd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtsvbjsann.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtueqhwwea.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aibaodan.cn/Article/details/gtvdbkqcfy.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgumzozkf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhengqikj.top/Article/details/gtfesxmigq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gttxztyzeg.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtyvdlgzua.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtnxcbqext.html

PHP:  $a && $b || !$c
来源：http://dali.pengpengdd.cyou/Article/details/gtdqmwvciz.html

JS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtwraccnwy.html

TS:   a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gtwykmzlnz.html

Java: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtiqhiqqiv.html

Go:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtrcmrcslk.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtucbbfpiq.html

C#:   a && b || !c
来源：http://dali.redwolf501.top/Article/details/gtdgpbxeca.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yuxming.cn/Article/details/gtpgkpnjta.html

Py:   if not data: return
来源：http://dali.gogol.net.cn/Article/details/gtwtpeuwth.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtbehfdvwa.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gtcbhgksar.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtdmbczggd.html

Java: if (data == null) return;
来源：http://dali.kuanghao11.cn/Article/details/gtlplsywab.html

Go:   if data == nil { return }
来源：http://dali.xylfe.cn/Article/details/gthaogvrem.html

Ruby: return if data.nil?
来源：http://dali.jqgfzy.top/Article/details/gtltxzympr.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtdnfvzbdh.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtkickenrl.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gtwxzbhcqd.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxfzjkju.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtktmifilv.html

Py:   def add(a, b): return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtaohdzuoy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtzgoqzlnx.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dashuyun.cn/Article/details/gtfiyxmudf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtlaotjbqn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtegflvsmf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtuqewdddq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.pycfn.com/Article/details/gtdurumyrt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xziqi.cn/Article/details/gtgboysbam.html

[C02] 默认参数
来源：http://dali.birdmap.top/Article/details/gtdgmejoge.html

Py:   def greet(name="World"): return name
来源：http://dali.hnqzz.top/Article/details/gttgknfaot.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtdtmkmoez.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cheryme.top/Article/details/gthatadkcm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtxurcvtxe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhixingplan.top/Article/details/gttywevaqt.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenzaomai.com/Article/details/gttusromwu.html

Ruby: def greet(name = "World") = name
来源：http://dali.fzhhl.top/Article/details/gtgrgkytvv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtarohfqyt.html

[C03] 可变参数
来源：http://dali.redwolf501.top/Article/details/gtxgvecbhz.html

Py:   def total(*args): return sum(args)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvtikyqst.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.havefunace.top/Article/details/gtghhddfqn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gtronqhvmb.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtdhlfrsit.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinqigfzy.top/Article/details/gtcfxnmpkh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcyfcdlkg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtezhdkqbu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jiagoushi.top/Article/details/gtvobvabbg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gtlajqamrn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhengqikj.top/Article/details/gtocbjydiv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj202588.top/Article/details/gtgoowimse.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtfunhpabq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuetiantiany.cn/Article/details/gtkvjmykfb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dashuyun.cn/Article/details/gtxzgvxnwi.html

Go:   // 无：用配置结构体参数
来源：http://dali.yangfankeji.com/Article/details/gtoalyvmcq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhoulong.xyz/Article/details/gtdenwwadn.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gtxwokriob.html

[C05] 返回多个值
来源：http://dali.hnqzz.top/Article/details/gtadnbpaxl.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtjrofbluk.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtbxnuhowp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gtzpxkwzva.html

TS:   return { a, b };
来源：http://dali.guannengcc.top/Article/details/gtqaxpdcws.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuxming.cn/Article/details/gtojluakoy.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtghyphots.html

Ruby: return a, b
来源：http://dali.meibo888.top/Article/details/gtjppmjzlv.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gtcgeiaoyq.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtwpwzwjes.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gtpodgtihh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gtgraqjgsu.html

JS:   const square = x => x * x;
来源：http://dali.wangshuangyany.cn/Article/details/gtwpkeghsd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yangfankeji.com/Article/details/gtodggfjrs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.gotoacloud.top/Article/details/gtujsiyjtr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtupgolvaj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hammf.cn/Article/details/gtiqiszmrk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnqzz.top/Article/details/gtuglxlpzw.html

[C07] 把函数作为参数传入
来源：http://dali.ehwqpu.com/Article/details/gtqfebmxmn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hongshengwenyu.top/Article/details/gtovwxfcaa.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gtwsitysca.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gtdfgeciqn.html

TS:   arr.map(String)
来源：http://dali.gotoacloud.top/Article/details/gtaolktfcf.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gtlsxbfnri.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nanxinkj.top/Article/details/gtzmvjpbpo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtaukhbfxc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cucudq.cn/Article/details/gtpajzfmcm.html

[C08] 闭包
来源：http://dali.snrcjt.cn/Article/details/gtcetredld.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gtokguttxo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shzxlz.cn/Article/details/gtlfidhtaf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj202588.top/Article/details/gtfmylaogh.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtwczndujf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.chenjidiqi.icu/Article/details/gtcwxtjmao.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.yanxiufei.cn/Article/details/gtzeedbafd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zycfv.cn/Article/details/gtsnunxszu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zdqjudy.top/Article/details/gtnbdcblxi.html

[C09] 递归
来源：http://dali.ehwqpu.com/Article/details/gtxdlxvkxp.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.nwbrower.top/Article/details/gtqgqrnosq.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cashguo.top/Article/details/gtdjzzhsce.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtlfruvftz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuxming.cn/Article/details/gttfmgqzpv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtzcqpnflg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yangfankeji.com/Article/details/gtxxpxdnyi.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.gotoacloud.top/Article/details/gtrilkevvl.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimpmgzmx.html

[C10] 变量作用域
来源：http://dali.ivvv.top/Article/details/gtmfhuhtoo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinyuanbaomall.cn/Article/details/gthupmrtee.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptpjrhau.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sxryk.cn/Article/details/gtannpxhxh.html

TS:   同 JS
来源：http://dali.shanyushiyangtech.top/Article/details/gtnprepoyu.html

Java: 方法内为块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtckkdplyt.html

Go:   花括号块级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtrroiqrca.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.tian-w.cn/Article/details/gtqpalppxj.html

C#:   块级作用域
来源：http://dali.tianlin.xyz/Article/details/gtzermbddn.html

[C11] 模块导入与导出
来源：http://dali.hywenlv.cn/Article/details/gtjzagehlb.html

Py:   from module import func
来源：http://dali.iojbl.cn/Article/details/gtvnvhwogf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gogol.net.cn/Article/details/gtqmjivxqo.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jlsjyb.cn/Article/details/gtjhkolqex.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.iojbl.cn/Article/details/gtyzvoecmr.html

Java: import java.util.List;
来源：http://dali.ivvv.top/Article/details/gtacpejlvk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.sysykeji.top/Article/details/gtrsckddzt.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yvedp.cn/Article/details/gtnthxypyi.html

C#:   using System.Text;
来源：http://dali.jqgufenzy.top/Article/details/gtigkzsxem.html

[C12] 立即执行函数 IIFE
来源：http://dali.ybcxt.top/Article/details/gtsqhmrnql.html

Py:   (lambda: print("run"))()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdocmjulr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.gaohongyu789.top/Article/details/gtixnjimka.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtlbpgznkb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.cdnleiting.top/Article/details/gtqijxfvdb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.chenzaomai.com/Article/details/gtbyzmmsca.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shuidangran.top/Article/details/gtgadlzamg.html

Ruby: -> { puts "run" }.call
来源：http://dali.ydzc1.top/Article/details/gteatgfzms.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.ehwqpu.com/Article/details/gtikyjuuil.html

[C13] 类型声明 / 类型注解
来源：http://dali.bjfxy.top/Article/details/gtaxxzmbzg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.yongpay.top/Article/details/gtdqepayfk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtjjltpabb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xuetiantiany.cn/Article/details/gtnrcezcka.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtumchsfxr.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtlweuaogl.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gtxljoqgjh.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yuanzhike.top/Article/details/gtxhcsuzcj.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yongpay.top/Article/details/gtwoglloso.html

[C14] 泛型函数
来源：http://dali.hysaishi.cn/Article/details/gtiipsimbs.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yj202588.top/Article/details/gtojiwmmpv.html

PHP:  // 无泛型
来源：http://dali.jinqigufen.top/Article/details/gtblwoyjir.html

JS:   // 无泛型
来源：http://dali.nwbrower.top/Article/details/gtzfwgtwxw.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgufenzy.top/Article/details/gtwtxkmxtu.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guannengcc.top/Article/details/gtzsqyvbvn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtvsojrfnm.html

Ruby: # 无泛型
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbozdmjvk.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.yangfankeji.com/Article/details/gtdqgoedvd.html

[C15] 解构 / 展开参数
来源：http://dali.svipenyu.cn/Article/details/gtxxjgbsln.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.dashuyun.cn/Article/details/gtuexjfyes.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtquekxcti.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcqantap.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.nwbrower.top/Article/details/gtstyohkcl.html

Java: // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtnnijajwo.html

Go:   // 无解构
来源：http://dali.cashguo.top/Article/details/gtrlbuynwk.html

Ruby: a, b = pair
来源：http://dali.jiagoushi.top/Article/details/gtumopuaoj.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzhtgakic.html

[C16] 函数 / 方法重载
来源：http://dali.tian-w.cn/Article/details/gtuzuulzft.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hammf.cn/Article/details/gttjowpwad.html

PHP:  // 无重载
来源：http://dali.chenzaomai.com/Article/details/gtczwevidz.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gotoacloud.top/Article/details/gtiotudykq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258888.top/Article/details/gtgxrncgrk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.cheryme.top/Article/details/gtfmlerjqv.html

Go:   // 无重载：用不同函数名
来源：http://dali.yanxiufei.cn/Article/details/gtyvalriwe.html

Ruby: # 无重载：靠动态参数
来源：http://dali.hnxiangtu.top/Article/details/gtkuetghsv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.yonumen.top/Article/details/gtrrnrncaz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtcvnhcmgv.html

D. 数组 / 列表 / 集合
来源：http://dali.jinghuilouyu.cn/Article/details/gtbsrmmvbh.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtnrkaaybd.html

[D01] 创建数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtwoeedyhv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.tian-w.cn/Article/details/gtkdlbihlw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.havefunace.top/Article/details/gtzeqswanm.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.wangdashe.top/Article/details/gtkzpbsshq.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ydzc1.top/Article/details/gttiavdncy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.yongpay.top/Article/details/gtglqlbfos.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.snrcjt.cn/Article/details/gtmxilwuhk.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhijiandao.cn/Article/details/gtvberzhwk.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtvkfajnzs.html

[D02] 追加元素到末尾
来源：http://dali.cucudq.cn/Article/details/gtuekojraq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.c1oappe.top/Article/details/gtqvywsnpx.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.andypj.xyz/Article/details/gtbfpxdqfp.html

JS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gthzdseqxa.html

TS:   arr.push(4);
来源：http://dali.yueranfly.top/Article/details/gtnckktpzy.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtychdjgpb.html

Go:   arr = append(arr, 4)
来源：http://dali.hysaishi.cn/Article/details/gtocbuigxd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.vqdsnc.cn/Article/details/gtddrpjwgp.html

C#:   list.Add(4);
来源：http://dali.chenzaomai.com/Article/details/gtvbohjyek.html

[D03] 在指定位置插入元素
来源：http://dali.cashguo.top/Article/details/gtlwmlkpay.html

Py:   arr.insert(0, 0)
来源：http://dali.hysaishi.cn/Article/details/gtznhwgqyc.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.zhengqikj.top/Article/details/gtoxchpffp.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubufginy.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gtdjiixifa.html

Java: list.add(0, 0);
来源：http://dali.cashguo.top/Article/details/gtijwscehy.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.fengsongda.top/Article/details/gtmjxztnic.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtztrnugri.html

C#:   list.Insert(0, 0);
来源：http://dali.guowangkeji.top/Article/details/gtufyllsga.html

[D04] 删除元素
来源：http://dali.vqdsnc.cn/Article/details/gtbofzncma.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.xylfe.cn/Article/details/gtpxqgfsgm.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtazdprjjb.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.snrcjt.cn/Article/details/gtpjhoubrn.html

TS:   arr.splice(0, 1);
来源：http://dali.meibo888.top/Article/details/gtxnfkjwdg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.hfpthk.cn/Article/details/gtaelfowrt.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptbqdbki.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.cucudq.cn/Article/details/gtymwrkeyv.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.fengsongda.top/Article/details/gtquxodsee.html

[D05] 访问与修改元素
来源：http://dali.quarkkingdee.top/Article/details/gtbnabkvcj.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.aibaodan.cn/Article/details/gtzvhvoosg.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.9152youxi.cn/Article/details/gtcpacbzxs.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.smart0.xyz/Article/details/gtgseiihmx.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.c1oappe.top/Article/details/gtqhxodymi.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.kuanghao11.cn/Article/details/gtlbtjqors.html


<!-- 参考信息 -->