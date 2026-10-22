代发 wailian999

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gt2yqrjedxx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pycfn.com/Article/details/gt2awdshwoi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.daxiang520.top/Article/details/gt2jzqtmkjp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gt2zlguuagv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxuanxn.top/Article/details/gt2qetfbgkf.html

[B06] 遍历字典 / 对象
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pconcqcb.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gt2svquilaq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xinyue.icu/Article/details/gt2pwtjueud.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gt2gztianeo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhijiandao.cn/Article/details/gt2btmsbodz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gt2nozmzecf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rsfwpltk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eehktezb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gt2azcfvwnc.html

[B07] while 循环
来源：http://dali.xziqi.cn/Article/details/gt2xsmgwoti.html

Py:   while i < 10: i += 1
来源：http://dali.daxiang520.top/Article/details/gt2monktqpy.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gt2yvxkjbsw.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2rqzrixpy.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2bdmicxfc.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2bzewkffl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gt2ouokmzmu.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gt2jovjglog.html

C#:   while (i < 10) { i++; }
来源：http://dali.hammf.cn/Article/details/gt2kvzpdyzd.html

[B08] do-while（至少执行一次）
来源：http://dali.tanke756.top/Article/details/gt2ffpescxi.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.dianchejie.cn/Article/details/gt2vlnfmshb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2egmipusl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gt2ftodzubw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.pengpengdd.cyou/Article/details/gt2enlgkwdz.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gt2ajwfkuve.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gt2lbkvpoqd.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2wufaqojo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2vabhnieb.html

[B09] break 与 continue
来源：http://dali.yueranfly.top/Article/details/gt2fcqaffko.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gt2ypqhibuw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2gjwplfsv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gt2gkhjzkco.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2osatclzi.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2ixrhpady.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ppjwa.cn/Article/details/gt2ziabsubc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258888.top/Article/details/gt2phgorwxh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gt2teewcjyj.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gt2qajrxosr.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gt2qbjdpawe.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.birdmap.top/Article/details/gt2oqxxhpjc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gt2ntgigjuz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gt2bfrldcoa.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwtegell.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sysykeji.top/Article/details/gt2hrrqnhnw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hfpthk.cn/Article/details/gt2aoknuoxq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kbkofxxz.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gt2hkwyonxg.html

Py:   list(range(0, 10, 2))
来源：http://dali.andypj.xyz/Article/details/gt2zfukaqnf.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gt2bbumgvrn.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hammf.cn/Article/details/gt2ywldduab.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gt2mhnusobk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2chpuykgp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.feifeiyinyue.top/Article/details/gt2usjhcybn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gt2xizgcjxi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shzxlz.cn/Article/details/gt2lkmvoawx.html

[B12] 跳出多层循环
来源：http://dali.iojbl.cn/Article/details/gt2ajwpwigg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjmktzfc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gt2yunktzng.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gt2xyvwkokk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gt2ypydesug.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2ptwztppm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxuanxn.top/Article/details/gt2gamlvcpu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yanxiufei.cn/Article/details/gt2jtlttyjr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hywenlv.cn/Article/details/gt2vntuscya.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gt2mpjgafzo.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gt2qeijgaxo.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gt2cyqdrjyf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2lhkrinfh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gt2lwqzgtnm.html

Java: x instanceof Number
来源：http://dali.meibo888.top/Article/details/gt2ltmkcado.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.redwolf501.top/Article/details/gt2bscxswau.html

Ruby: x.is_a?(Numeric)
来源：http://dali.smart0.xyz/Article/details/gt2tqkfuttz.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnjxshcd.html

[B14] 判断值是否在集合内
来源：http://dali.9152youxi.cn/Article/details/gt2iqqvdril.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guowangkeji.top/Article/details/gt2dkfiifwi.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gt2ogiolnfh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gt2ixefgdje.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2cfplhdoo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhixingplan.top/Article/details/gt2qgyphhzc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.svipenyu.cn/Article/details/gt2ytqffvae.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mguctloa.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.mhx1999.top/Article/details/gt2fzmqnmzc.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gt2bydlxuyn.html

Py:   a and b or not c
来源：http://dali.sxryk.cn/Article/details/gt2slqeqqkk.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gt2uukxiktc.html

JS:   a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2syicedtz.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2bgapdywh.html

Java: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2quboluwi.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gt2zusphkbm.html

Ruby: a && b || !c
来源：http://dali.aizwys.cn/Article/details/gt2ppmfzblz.html

C#:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2znyevqzs.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2sptpyfun.html

Py:   if not data: return
来源：http://dali.vqdsnc.cn/Article/details/gt2cfujjyje.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ynzvyahe.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gt2eewzazrf.html

TS:   if (!data) return;
来源：http://dali.jqgfzy.top/Article/details/gt2hgdkqedp.html

Java: if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2phdamtny.html

Go:   if data == nil { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hdvjcegd.html

Ruby: return if data.nil?
来源：http://dali.snrcjt.cn/Article/details/gt2ykwizmyi.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gt2zmmqoqrg.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gt2kfcrfnxb.html

C. 函数与作用域
来源：http://dali.ehwqpu.com/Article/details/gt2dtfbnoqv.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gt2icdoawel.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gt2ryyrizhl.html

Py:   def add(a, b): return a + b
来源：http://dali.zhijiandao.cn/Article/details/gt2hlanhglm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gt2fcyvfdrd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gt2qmwjatpx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hysaishi.cn/Article/details/gt2jvusaztq.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gt2stliwslq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gotoacloud.top/Article/details/gt2hjwzyhsf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzuztuhj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gt2tqqfdcxs.html

[C02] 默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2kfmflfty.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gt2qfladjdd.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2svaafmur.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gt2gfqhpnan.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gt2tikloccr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gt2ejwbmfzy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tianlin.xyz/Article/details/gt2hkngbgst.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gt2wkboaxkz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.shzxlz.cn/Article/details/gt2oqjnsbny.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gt2qfnpdkxp.html

Py:   def total(*args): return sum(args)
来源：http://dali.fzhhl.top/Article/details/gt2hrgljdaa.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.kuanghao11.cn/Article/details/gt2wihovawy.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hammf.cn/Article/details/gt2xvffqvwd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gt2gebnrjdc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zdqjudy.top/Article/details/gt2kpwqadhe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gt2sqjnmfrv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gt2wynigrtt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.haohaochexian.top/Article/details/gt2nhkfoxgy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gt2najjhaqs.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.bjfxy.top/Article/details/gt2lflviluy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gt2kfgiplrh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2ibmhkign.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.mhx1999.top/Article/details/gt2gmmbduup.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gt2osnosvcl.html

Go:   // 无：用配置结构体参数
来源：http://dali.gzhubu.top/Article/details/gt2yakvisil.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gt2vyhvdqnb.html

C#:   f(a: 1, b: 2)
来源：http://dali.jiagoushi.top/Article/details/gt2rcmqrcjq.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gt2rqdiphes.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gt2yvprsxhe.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gt2ctlwqiiu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258.top/Article/details/gt2fkeqfjrf.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2zoobtpti.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhengqikj.top/Article/details/gt2qmxkcqvh.html

Go:   return a, b
来源：http://dali.sufxvd.cn/Article/details/gt2yqwphbyi.html

Ruby: return a, b
来源：http://dali.nanxinkj.top/Article/details/gt2ctaicasc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.tian-w.cn/Article/details/gt2iugdltec.html

[C06] 匿名函数 / lambda
来源：http://dali.zhixingplan.top/Article/details/gt2ynyaodco.html

Py:   square = lambda x: x * x
来源：http://dali.yvedp.cn/Article/details/gt2phoadpjn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gt2novfufdh.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gt2mdhmuacr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jiagoushi.top/Article/details/gt2fgfqoqsv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fbxnjsfy.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shzxlz.cn/Article/details/gt2lukrirev.html

Ruby: square = ->(x) { x * x }
来源：http://dali.nanxuanxn.top/Article/details/gt2hafbeasm.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jyoumei.cn/Article/details/gt2loxvoevy.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pmwflbrr.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.smart0.xyz/Article/details/gt2hivebskr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2yrlwlwdg.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rruaraee.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gt2rhzuulbo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhoulong.xyz/Article/details/gt2nihfzkfr.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2owkgnfoj.html

Ruby: arr.map(&:upcase)
来源：http://dali.sweek.top/Article/details/gt2uzxpuqlb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cashguo.top/Article/details/gt2ngphcwlv.html

[C08] 闭包
来源：http://dali.jqgfzy.top/Article/details/gt2kmilwcan.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.pengpengdd.cyou/Article/details/gt2clcntsef.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2ihqehnyu.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gt2oihelvxm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lswngcqd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yuanzhike.top/Article/details/gt2lxuxzwgq.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gt2pgyioegb.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.gzhubu.top/Article/details/gt2rqnrllie.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.quarkkingdee.top/Article/details/gt2yygdumgt.html

[C09] 递归
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvveuffe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2ccwtmeew.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.9152youxi.cn/Article/details/gt2vwhjnquh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gt2oqlljjoe.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.sxryk.cn/Article/details/gt2mvgbbhnd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yvedp.cn/Article/details/gt2kbrciagi.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.sxryk.cn/Article/details/gt2sflqxcmy.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.quarkkingdee.top/Article/details/gt2rznfnngu.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hammf.cn/Article/details/gt2ntdhwlbw.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2hynkizja.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhiwuduotai.top/Article/details/gt2vhllzrta.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhijiandao.cn/Article/details/gt2advroopn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cqqwz.cn/Article/details/gt2ndbgsqpt.html

TS:   同 JS
来源：http://dali.chenjidiqi.icu/Article/details/gt2eroqiybb.html

Java: 方法内为块级作用域
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xaabsnxa.html

Go:   花括号块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jlbzudxy.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shanyushiyangtech.top/Article/details/gt2iovauxur.html

C#:   块级作用域
来源：http://dali.birdmap.top/Article/details/gt2wbngnrcy.html

[C11] 模块导入与导出
来源：http://dali.daria6918.cn/Article/details/gt2prcktrjo.html

Py:   from module import func
来源：http://dali.9152youxi.cn/Article/details/gt2rwmiofia.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.birdmap.top/Article/details/gt2qnljycmp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.guannengcc.top/Article/details/gt2gdigbryz.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ybcxt.top/Article/details/gt2iacsdpom.html

Java: import java.util.List;
来源：http://dali.hfpthk.cn/Article/details/gt2tfcqorme.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2qtzlawkh.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eybvmoea.html

C#:   using System.Text;
来源：http://dali.yvedp.cn/Article/details/gt2orjqifjx.html

[C12] 立即执行函数 IIFE
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nupxfrts.html

Py:   (lambda: print("run"))()
来源：http://dali.dianchejie.cn/Article/details/gt2vziettad.html

PHP:  (function () { echo "run"; })();
来源：http://dali.smart0.xyz/Article/details/gt2hurmrdks.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hnxiangtu.top/Article/details/gt2braodczt.html

TS:   (() => { console.log("run"); })();
来源：http://dali.fengsongda.top/Article/details/gt2rftlhsve.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.guannengcc.top/Article/details/gt2cofeqqtc.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hammf.cn/Article/details/gt2wqjcufvs.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vtbuoeve.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.yvedp.cn/Article/details/gt2qrnusejo.html

[C13] 类型声明 / 类型注解
来源：http://dali.tianlin.xyz/Article/details/gt2pxsejqsb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.snrcjt.cn/Article/details/gt2amtyywoh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xylfe.cn/Article/details/gt2botgnxkd.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shuidangran.top/Article/details/gt2cqvnakjo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gt2nmvoebrp.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2cphiezcp.html

Go:   func add(a, b int) int
来源：http://dali.yj20258.top/Article/details/gt2wynvijll.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gogol.net.cn/Article/details/gt2zeghbfgg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.andypj.xyz/Article/details/gt2lvaxxolt.html

[C14] 泛型函数
来源：http://dali.cheryme.top/Article/details/gt2grxlrolq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gogol.net.cn/Article/details/gt2iiqiqvdu.html

PHP:  // 无泛型
来源：http://dali.jianghu66.top/Article/details/gt2nlslgjai.html

JS:   // 无泛型
来源：http://dali.cucudq.cn/Article/details/gt2ktjdthlt.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jianghu66.top/Article/details/gt2bfheacws.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2easmbvhm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yvedp.cn/Article/details/gt2qbeoekmm.html

Ruby: # 无泛型
来源：http://dali.xylfe.cn/Article/details/gt2ihwpofue.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.wangshuangyany.cn/Article/details/gt2oezlvmbi.html

[C15] 解构 / 展开参数
来源：http://dali.yj20258.top/Article/details/gt2trwkqpam.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hnxiangtu.top/Article/details/gt2qfwcydyw.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sxryk.cn/Article/details/gt2mdgyziaz.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cashguo.top/Article/details/gt2kkkvkezv.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.daria6918.cn/Article/details/gt2gybhswaf.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gt2wklztbxq.html

Go:   // 无解构
来源：http://dali.cucudq.cn/Article/details/gt2fppwiieb.html

Ruby: a, b = pair
来源：http://dali.hfpthk.cn/Article/details/gt2brjgtlit.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2opazeeyh.html

[C16] 函数 / 方法重载
来源：http://dali.zhijiandao.cn/Article/details/gt2daoszpsa.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gt2tenhanhl.html

PHP:  // 无重载
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppgnbskq.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jianghu66.top/Article/details/gt2cxqtovip.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.hnxiangtu.top/Article/details/gt2jljofypb.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.havefunace.top/Article/details/gt2finwdngs.html

Go:   // 无重载：用不同函数名
来源：http://dali.jqgufenzy.top/Article/details/gt2ooevpgld.html

Ruby: # 无重载：靠动态参数
来源：http://dali.gotoacloud.top/Article/details/gt2vtryxjqp.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.aizwys.cn/Article/details/gt2qtciqjvh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2qfkgzria.html

D. 数组 / 列表 / 集合
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2piyqcjyk.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2olbbrqhs.html

[D01] 创建数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gt2fhjmoglv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shuidangran.top/Article/details/gt2booivbgp.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.cashguo.top/Article/details/gt2ljvhqcan.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yonumen.top/Article/details/gt2qjyjpqbn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qgrqixhn.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.ehwqpu.com/Article/details/gt2jcxlnezc.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xodvzasn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hammf.cn/Article/details/gt2fftrgoey.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.daxiang520.top/Article/details/gt2xbhsryhw.html

[D02] 追加元素到末尾
来源：http://dali.zhongyouzk.top/Article/details/gt2grpmhxtj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.svipenyu.cn/Article/details/gt2idiutzqb.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2yvrjbnab.html

JS:   arr.push(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxoyycwv.html

TS:   arr.push(4);
来源：http://dali.hysaishi.cn/Article/details/gt2xuhofvqq.html

Java: list.add(4);
来源：http://dali.vqdsnc.cn/Article/details/gt2ysfwcsso.html

Go:   arr = append(arr, 4)
来源：http://dali.xylfe.cn/Article/details/gt2fqjkgolb.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.tianlin.xyz/Article/details/gt2mmjocvui.html

C#:   list.Add(4);
来源：http://dali.jiagoushi.top/Article/details/gt2autgawev.html

[D03] 在指定位置插入元素
来源：http://dali.yuxming.cn/Article/details/gt2kpnebrgt.html

Py:   arr.insert(0, 0)
来源：http://dali.kuanghao11.cn/Article/details/gt2athcnycf.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.tanke756.top/Article/details/gt2upintlfc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdiobfde.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.cheryme.top/Article/details/gt2jxdnrrsp.html

Java: list.add(0, 0);
来源：http://dali.zhijiandao.cn/Article/details/gt2ggyqjqsh.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.gogol.net.cn/Article/details/gt2jgvslgkz.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.daxiang520.top/Article/details/gt2hhqfqyyk.html

C#:   list.Insert(0, 0);
来源：http://dali.hongshengwenyu.top/Article/details/gt2xjhergrs.html

[D04] 删除元素
来源：http://dali.meibo888.top/Article/details/gt2wfervmry.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zycfv.cn/Article/details/gt2titvbnmj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.cashguo.top/Article/details/gt2pclnaliu.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.ppjwa.cn/Article/details/gt2klepqltj.html

TS:   arr.splice(0, 1);
来源：http://dali.sysykeji.top/Article/details/gt2nqiohqix.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.0kj1m.cn/Article/details/gt2ztrwudpf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.cucudq.cn/Article/details/gt2zwaihiju.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.fengsongda.top/Article/details/gt2llcieled.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.hnxiangtu.top/Article/details/gt2okknfhgn.html

[D05] 访问与修改元素
来源：http://dali.tanke756.top/Article/details/gt2uamhrofa.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.quarkkingdee.top/Article/details/gt2pyxwmbjp.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tianlin.xyz/Article/details/gt2nuwrqild.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.daria6918.cn/Article/details/gt2fgfkzjmj.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.shzxlz.cn/Article/details/gt2uociyezz.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.hammf.cn/Article/details/gt2wrfxdtyp.html

Go:   arr[0]; arr[0] = 9
来源：http://dali.zhiwuduotai.top/Article/details/gt2meboahaj.html

Ruby: arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.fzhhl.top/Article/details/gt2yhbeurtx.html

C#:   list[0]; list[^1]; list[0] = 9;
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvqnryes.html

[D06] 数组长度
来源：http://dali.shuidangran.top/Article/details/gt2rzidhgqp.html


<!-- 参考信息 -->