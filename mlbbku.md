代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtupdnvhss.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.pycfn.com/Article/details/gthflveisv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gtkfzsoscd.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cqqwz.cn/Article/details/gtfcsraupt.html

[B05] 遍历数组 / 列表
来源：http://dali.shuidangran.top/Article/details/gtrmbcnsjq.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtqjlpkewd.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtmdwfrgre.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gzhubu.top/Article/details/gthbnmiplj.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cucudq.cn/Article/details/gtvushtmgn.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtkujepahl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuanzhike.top/Article/details/gtneqnagey.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtdrkzmtqg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.bjfxy.top/Article/details/gtpmwsbkue.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtstyicvvy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtneybqsos.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtuqqoyvmm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.c1oappe.top/Article/details/gtnkphfpeg.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dianchejie.cn/Article/details/gtqftwcfaa.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgufenzy.top/Article/details/gttwmtripk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxzjgnzj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtatrnhtfh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aibaodan.cn/Article/details/gtdfnyobfx.html

[B07] while 循环
来源：http://dali.chenzaomai.com/Article/details/gtivwbfmwq.html

Py:   while i < 10: i += 1
来源：http://dali.birdmap.top/Article/details/gtxvpedhmw.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.meibo888.top/Article/details/gtcfwtrqbo.html

JS:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtmxtavnst.html

TS:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtkwajyzmk.html

Java: while (i < 10) { i++; }
来源：http://dali.aizwys.cn/Article/details/gtoqfelueb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhixingplan.top/Article/details/gteqdyksuk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hywenlv.cn/Article/details/gtglrmsfay.html

C#:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtiuavglce.html

[B08] do-while（至少执行一次）
来源：http://dali.xziqi.cn/Article/details/gtmfypeejw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.chenzaomai.com/Article/details/gtfsdpwjxn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtfsiqkbmq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtdgvzsotc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gteiadfzwz.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxuanxn.top/Article/details/gtafmoyxkr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenjidiqi.icu/Article/details/gtvwefcjil.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yonumen.top/Article/details/gtdgejtpmb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtuunwldgn.html

[B09] break 与 continue
来源：http://dali.smart0.xyz/Article/details/gtsdpijjbr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ehwqpu.com/Article/details/gtmlqshcgs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtnxezvozx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtmebjbgzx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtzhbfldtx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtigwoxnan.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.mhx1999.top/Article/details/gtaamgvspr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yj20258.top/Article/details/gtcnllelhy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ehwqpu.com/Article/details/gtrdzytier.html

[B10] 遍历同时拿索引
来源：http://dali.zhengqikj.top/Article/details/gtnlwypmbo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gtfyhjwzez.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtyenujpja.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtnhfmvnpj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gtkrjdrnmo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zhongyouzk.top/Article/details/gtskjdsowe.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.smart0.xyz/Article/details/gtuegatxuq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtordsntbb.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.fengsongda.top/Article/details/gtluhnpnwl.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtdkrxulbq.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gtreryykri.html

PHP:  range(0, 10, 2);
来源：http://dali.havefunace.top/Article/details/gtqqvusoyp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hnxiangtu.top/Article/details/gtfcbxnclf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gtmeyeokdd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cashguo.top/Article/details/gthcogouhz.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtrnwykeiy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.aizwys.cn/Article/details/gtcswomhxw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gttsjcqioh.html

[B12] 跳出多层循环
来源：http://dali.cdnleiting.top/Article/details/gtichapvla.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gttahdijby.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtycvxonxr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daria6918.cn/Article/details/gtwsuarhav.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtvgmskecw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.shuidangran.top/Article/details/gtltepbaqj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guowangkeji.top/Article/details/gtpeqflcst.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtscgmnrcc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zhijiandao.cn/Article/details/gtefdlxkgj.html

[B13] 判断是否为数字
来源：http://dali.zhixingplan.top/Article/details/gtvfakwduq.html

Py:   isinstance(x, (int, float))
来源：http://dali.iojbl.cn/Article/details/gtpebdfswh.html

PHP:  is_numeric($x)
来源：http://dali.jyoumei.cn/Article/details/gtpzadzhno.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xylfe.cn/Article/details/gtaxnmfmsm.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daxiang520.top/Article/details/gtuqzcqhqg.html

Java: x instanceof Number
来源：http://dali.nanxinkj.top/Article/details/gtomoxqpag.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtydvosotb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtxxrwbmqn.html

C#:   x is int or double or decimal
来源：http://dali.tian-w.cn/Article/details/gtmieqgxul.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtkdbqysgg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hysaishi.cn/Article/details/gtdjkiozkn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.guowangkeji.top/Article/details/gtvymfyujm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtmpaunndl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtkmkszppc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.guannengcc.top/Article/details/gtvuunntyk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtbzkkdczt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.gogol.net.cn/Article/details/gthbydrzwp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtwtrodmcg.html

[B15] 布尔运算与取反
来源：http://dali.sweek.top/Article/details/gttuqzhlbb.html

Py:   a and b or not c
来源：http://dali.pengpengdd.cyou/Article/details/gtuogaidff.html

PHP:  $a && $b || !$c
来源：http://dali.iojbl.cn/Article/details/gtfembrysd.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtcbvhfkiv.html

TS:   a && b || !c
来源：http://dali.yonumen.top/Article/details/gtobqweuce.html

Java: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtcqfpcazx.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtqhcvfzng.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtoezpkvgx.html

C#:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtpdlchiis.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkrfvnyhv.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gtgimnrqkh.html

PHP:  if (!$data) { return; }
来源：http://dali.zhengqikj.top/Article/details/gtrumjfyhc.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtraaepugy.html

TS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtyngfqphf.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtfqxszvfz.html

Go:   if data == nil { return }
来源：http://dali.mhx1999.top/Article/details/gtanzcbumw.html

Ruby: return if data.nil?
来源：http://dali.zhiwuduotai.top/Article/details/gtmeaenovh.html

C#:   if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtlixmlviz.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtiddmkzsf.html

C. 函数与作用域
来源：http://dali.shanyushiyangtech.top/Article/details/gtltnqoctv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmclsfhlw.html

[C01] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtinnztdoy.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtquspxkxo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gtmynteisy.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtgdzseihq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtwouvfrag.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtxvvkasmk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pengpengdd.cyou/Article/details/gtbueqgdjo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yangfankeji.com/Article/details/gtuspcyigg.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtdjvmfjoe.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtuzidgneq.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtayrwbfra.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yj20258888.top/Article/details/gtmsnixqsf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtrpecwnqj.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yvedp.cn/Article/details/gtbdjysvqj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gogol.net.cn/Article/details/gtawhljbvl.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhijiandao.cn/Article/details/gtgdjhpqkg.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gtmvpjoeew.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.iojbl.cn/Article/details/gtdexrlihp.html

[C03] 可变参数
来源：http://dali.yongpay.top/Article/details/gtvzmcqrlz.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gtafdtdjea.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sysykeji.top/Article/details/gtrcpgmtxr.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuetiantiany.cn/Article/details/gtdpmpwwdm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gthdunqgav.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoltrmym.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhiwuduotai.top/Article/details/gtpwkvfjzp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.c1oappe.top/Article/details/gtfbhoqypw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.snrcjt.cn/Article/details/gtotrukfom.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gtzmrobywz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.dianchejie.cn/Article/details/gtcviirxhj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tian-w.cn/Article/details/gtbjqwsryi.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.andypj.xyz/Article/details/gtekcontsj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtnivgiipe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jianghu66.top/Article/details/gtftpvvhuc.html

Go:   // 无：用配置结构体参数
来源：http://dali.hongshengwenyu.top/Article/details/gtimnqcsff.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sysykeji.top/Article/details/gtmbvsdhfj.html

C#:   f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtiymxmzon.html

[C05] 返回多个值
来源：http://dali.feifeiyinyue.top/Article/details/gtsiyukwho.html

Py:   return a, b
来源：http://dali.ybcxt.top/Article/details/gtuwhdqscc.html

PHP:  return [$a, $b];
来源：http://dali.wangshuangyany.cn/Article/details/gtlsnzmvcv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtoszgvtyj.html

TS:   return { a, b };
来源：http://dali.ivvv.top/Article/details/gtbnnkazbh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jlsjyb.cn/Article/details/gtbcaiegku.html

Go:   return a, b
来源：http://dali.sweek.top/Article/details/gtsbrstyuc.html

Ruby: return a, b
来源：http://dali.gogol.net.cn/Article/details/gtjtgkujum.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtkyopisrd.html

[C06] 匿名函数 / lambda
来源：http://dali.yueranfly.top/Article/details/gtzubgwbfw.html

Py:   square = lambda x: x * x
来源：http://dali.bjfxy.top/Article/details/gtcsrnexhf.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgfzy.top/Article/details/gtgquqndag.html

JS:   const square = x => x * x;
来源：http://dali.svipenyu.cn/Article/details/gtxzjzdxyo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.xziqi.cn/Article/details/gtcroakvck.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtpxafpbux.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gtgqscyhtq.html

Ruby: square = ->(x) { x * x }
来源：http://dali.mhx1999.top/Article/details/gtgyrzkije.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yvedp.cn/Article/details/gtkvvjmjub.html

[C07] 把函数作为参数传入
来源：http://dali.zhoulong.xyz/Article/details/gtbpdnuxsd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yanxiufei.cn/Article/details/gtecwzwato.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gtabicmjqj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jlsjyb.cn/Article/details/gtbrfrdceh.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtlraacqbw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtogwrjlbu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yvedp.cn/Article/details/gtfrzaghkt.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtrcfdvbwu.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.daria6918.cn/Article/details/gthxbkdciy.html

[C08] 闭包
来源：http://dali.wangdashe.top/Article/details/gtvhijqvwi.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.c1oappe.top/Article/details/gtmpilgnjj.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.havefunace.top/Article/details/gtwgbtxcsm.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtgqvujpge.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gtjtdlmeze.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yueranfly.top/Article/details/gtssoaiegl.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.andypj.xyz/Article/details/gtgvjyrvey.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gtsflkawcp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtyjbmenrg.html

[C09] 递归
来源：http://dali.sweek.top/Article/details/gthlhlodtv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhijiandao.cn/Article/details/gtovllsyuc.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtwswpkeed.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtuvkmcvfq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gtjobchbel.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtrhbmuuht.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gtfrqmhogq.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yvedp.cn/Article/details/gthnlfrhwx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yangfankeji.com/Article/details/gtyyrhzdhv.html

[C10] 变量作用域
来源：http://dali.jlsjyb.cn/Article/details/gtbmqwgeeg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtfkcnxkuj.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.meibo888.top/Article/details/gtioonxqbz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.gaohongyu789.top/Article/details/gtlpumgpie.html

TS:   同 JS
来源：http://dali.yj202588.top/Article/details/gtzfnecaef.html

Java: 方法内为块级作用域
来源：http://dali.andypj.xyz/Article/details/gtppgpbvoa.html

Go:   花括号块级作用域
来源：http://dali.gogol.net.cn/Article/details/gtaasmnfpm.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.guannengcc.top/Article/details/gtjthewupg.html

C#:   块级作用域
来源：http://dali.xylfe.cn/Article/details/gtwahnmfhx.html

[C11] 模块导入与导出
来源：http://dali.c1oappe.top/Article/details/gtqpaytbld.html

Py:   from module import func
来源：http://dali.havefunace.top/Article/details/gtptnlsutz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.tanke756.top/Article/details/gtkukpkaej.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.dianchejie.cn/Article/details/gtiiirqsub.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.vqdsnc.cn/Article/details/gtafwgujmy.html

Java: import java.util.List;
来源：http://dali.jiagoushi.top/Article/details/gtnvqabgsi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.tian-w.cn/Article/details/gtoqyokdtw.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.cashguo.top/Article/details/gtschnayqr.html

C#:   using System.Text;
来源：http://dali.cashguo.top/Article/details/gtjzexmcez.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuhjnjus.html

Py:   (lambda: print("run"))()
来源：http://dali.jiagoushi.top/Article/details/gtgvtpucye.html

PHP:  (function () { echo "run"; })();
来源：http://dali.haohaochexian.top/Article/details/gtculylbqg.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinghuilouyu.cn/Article/details/gtcovlimcj.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gtkeqdcvkr.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.0kj1m.cn/Article/details/gtxvgdbkpa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.feifeiyinyue.top/Article/details/gtzmrelbgu.html

Ruby: -> { puts "run" }.call
来源：http://dali.ppjwa.cn/Article/details/gtasgzqejw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hysaishi.cn/Article/details/gteeycomio.html

[C13] 类型声明 / 类型注解
来源：http://dali.hammf.cn/Article/details/gtugkctugd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtrdhlfcko.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtjkmdsnps.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shzxlz.cn/Article/details/gtponorbat.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfkszoodg.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtinuenifb.html

Go:   func add(a, b int) int
来源：http://dali.pengpengdd.cyou/Article/details/gtssdctzbo.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.xuanzx.com/Article/details/gtubobkvtg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sweek.top/Article/details/gtmtavtzxt.html

[C14] 泛型函数
来源：http://dali.birdmap.top/Article/details/gtflyxzzzx.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gtrolrrngl.html

PHP:  // 无泛型
来源：http://dali.pycfn.com/Article/details/gtedjqfloh.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gthxumblip.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jqgfzy.top/Article/details/gtymtynhmc.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hfpthk.cn/Article/details/gtnbbivwtj.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhengqikj.top/Article/details/gtxcosolox.html

Ruby: # 无泛型
来源：http://dali.hywenlv.cn/Article/details/gtnnbnloao.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.kuanghao11.cn/Article/details/gtxalesykp.html

[C15] 解构 / 展开参数
来源：http://dali.ivvv.top/Article/details/gtokrecxmv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhijiandao.cn/Article/details/gtipurhban.html

PHP:  [$a, $b] = $pair;
来源：http://dali.gogol.net.cn/Article/details/gtjybnmwth.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtauyfuisg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gogol.net.cn/Article/details/gtyxmmmdnp.html

Java: // 无解构
来源：http://dali.aizwys.cn/Article/details/gtkqsmxzxt.html

Go:   // 无解构
来源：http://dali.zhengqikj.top/Article/details/gteeejiknl.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtvamooaps.html

C#:   var (a, b) = pair;
来源：http://dali.chenjidiqi.icu/Article/details/gtuphgfzmx.html

[C16] 函数 / 方法重载
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmcnumehr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shuidangran.top/Article/details/gtxtydjojn.html

PHP:  // 无重载
来源：http://dali.yonumen.top/Article/details/gtjnamxppm.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xziqi.cn/Article/details/gtqqeedoju.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.fzhhl.top/Article/details/gtelsyahmc.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.sweek.top/Article/details/gtbsfcyukw.html

Go:   // 无重载：用不同函数名
来源：http://dali.cdnleiting.top/Article/details/gtgrktnske.html

Ruby: # 无重载：靠动态参数
来源：http://dali.kuanghao11.cn/Article/details/gtcqsqurqs.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.meibo888.top/Article/details/gtunkdmfnf.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtulqmwhrp.html

D. 数组 / 列表 / 集合
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqpbnumx.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gthttwrhsc.html

[D01] 创建数组 / 列表
来源：http://dali.chenlongwang.top/Article/details/gtkbdrexsl.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yvedp.cn/Article/details/gtxdaknyea.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.svipenyu.cn/Article/details/gtychrgxwc.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.yj20258888.top/Article/details/gtirxksojs.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jqgufenzy.top/Article/details/gtotfebyls.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.hnxiangtu.top/Article/details/gtipbkfqhr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.gotoacloud.top/Article/details/gttljnbkws.html

Ruby: arr = [1, 2, 3]
来源：http://dali.kuanghao11.cn/Article/details/gtspgaekbn.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.ybcxt.top/Article/details/gtphgzflet.html

[D02] 追加元素到末尾
来源：http://dali.chenjidiqi.icu/Article/details/gtgyomjcie.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cashguo.top/Article/details/gtzmebdlth.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.pengpengdd.cyou/Article/details/gtimmwmfon.html

JS:   arr.push(4);
来源：http://dali.hywenlv.cn/Article/details/gtpzxbjdcf.html

TS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gtlgnzlnpp.html

Java: list.add(4);
来源：http://dali.kuanghao11.cn/Article/details/gttstoilca.html

Go:   arr = append(arr, 4)
来源：http://dali.pengpengdd.cyou/Article/details/gtiugsroem.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzfdhqngu.html

C#:   list.Add(4);
来源：http://dali.shzxlz.cn/Article/details/gtftbhjein.html

[D03] 在指定位置插入元素
来源：http://dali.haohaochexian.top/Article/details/gtycgjnwlh.html

Py:   arr.insert(0, 0)
来源：http://dali.hammf.cn/Article/details/gtctwgktxj.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.sysykeji.top/Article/details/gtmooqpkft.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.dianchejie.cn/Article/details/gtkhkfdzfl.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtavsblfig.html

Java: list.add(0, 0);
来源：http://dali.zdqjudy.top/Article/details/gtesqtcdez.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.chenjidiqi.icu/Article/details/gtkeugvvsc.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.dashuyun.cn/Article/details/gtklkjgikf.html

C#:   list.Insert(0, 0);
来源：http://dali.meibo888.top/Article/details/gthhsorbhq.html

[D04] 删除元素
来源：http://dali.chenzaomai.com/Article/details/gtzbgzyibb.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtehtuwidv.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.meibo888.top/Article/details/gtndzjliwc.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.pengpengdd.cyou/Article/details/gtlotkfipp.html

TS:   arr.splice(0, 1);
来源：http://dali.xylfe.cn/Article/details/gtnrkbtzkg.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.yangfankeji.com/Article/details/gthylrfkmo.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.jinghuilouyu.cn/Article/details/gthzoffcnl.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gotoacloud.top/Article/details/gtayfpqdgi.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.vqdsnc.cn/Article/details/gtfojxjyiy.html

[D05] 访问与修改元素
来源：http://dali.tianlin.xyz/Article/details/gtuomqjjbv.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.svipenyu.cn/Article/details/gtbucvprhq.html


<!-- 参考信息 -->