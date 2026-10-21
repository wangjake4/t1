代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.nwbrower.top/Article/details/gtyzclugcl.html

Py:   for item in arr: print(item)
来源：http://dali.xinyue.icu/Article/details/gtxoovldfr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjrywjddv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtieoxfhdx.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gthxjumist.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkaclxfir.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnxiangtu.top/Article/details/gtmxcvcvdd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gtgffpavat.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gtejmuettj.html

[B06] 遍历字典 / 对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtowfylcqj.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jqgfzy.top/Article/details/gtisqtpxfq.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sxryk.cn/Article/details/gticzgdfhn.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.meibo888.top/Article/details/gtuhaqjlia.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnipbrsvx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtzpkhtcef.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gtptxufsad.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.shangyingyoupin.top/Article/details/gtdsaftgaj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cashguo.top/Article/details/gtcejbazsf.html

[B07] while 循环
来源：http://dali.guowangkeji.top/Article/details/gtjjztpxel.html

Py:   while i < 10: i += 1
来源：http://dali.cucudq.cn/Article/details/gtbcsavqli.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtgjedywfp.html

JS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtiaxfzrbx.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtwpityanw.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtymysimlb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.xinyue.icu/Article/details/gtefpdtrpf.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gthgrobkwk.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtgsppxxmg.html

[B08] do-while（至少执行一次）
来源：http://dali.vqdsnc.cn/Article/details/gtinyfkgrx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yuxming.cn/Article/details/gtyettkpnh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gthggbfztp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtqyafkzlx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtydlpvaxa.html

Java: do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtzefuvhal.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.mhx1999.top/Article/details/gtjeixycig.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.smart0.xyz/Article/details/gtqrfprhmf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtdateyaij.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gterwikird.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtfoqyaohr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtwxewstjf.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtichbalee.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtbyspmghu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazlfmdck.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtchesimxz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cucudq.cn/Article/details/gtqpztjvnu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyllqwkr.html

[B10] 遍历同时拿索引
来源：http://dali.tian-w.cn/Article/details/gtbjiaysiq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gteqhvfiyf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jqgfzy.top/Article/details/gtodfurpug.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sufxvd.cn/Article/details/gtrycqyyjr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gtdspojtgr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.gogol.net.cn/Article/details/gtidgjbzzl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.0kj1m.cn/Article/details/gtnksvbgta.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtukwyegtl.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.svipenyu.cn/Article/details/gtyfwoegtl.html

[B11] 生成数字序列 / 区间
来源：http://dali.pengpengdd.cyou/Article/details/gtqxgvoorv.html

Py:   list(range(0, 10, 2))
来源：http://dali.ivvv.top/Article/details/gtqxghpppf.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtwodynwbj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tanke756.top/Article/details/gtxquapidc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtqmltmymv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.birdmap.top/Article/details/gtqbmdvuzw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuanzx.com/Article/details/gtmufjtlwo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gtyvmhqlqe.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gtjtbnpvgs.html

[B12] 跳出多层循环
来源：http://dali.zdqjudy.top/Article/details/gtwfxensvj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.iojbl.cn/Article/details/gteishpmpu.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtneivxwtu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.redwolf501.top/Article/details/gtnisytknc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtpfyyptlg.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gogol.net.cn/Article/details/gtimjlzrix.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cheryme.top/Article/details/gtmegzgxfo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.pengpengdd.cyou/Article/details/gtzimwmrsm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.chenjidiqi.icu/Article/details/gtbrgiuthq.html

[B13] 判断是否为数字
来源：http://dali.quarkkingdee.top/Article/details/gtyxpzxdku.html

Py:   isinstance(x, (int, float))
来源：http://dali.havefunace.top/Article/details/gtwlncapjn.html

PHP:  is_numeric($x)
来源：http://dali.jlsjyb.cn/Article/details/gtadyhcykr.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtgaapohtt.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtpsmlzenb.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtjuewxlnv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yj20258888.top/Article/details/gtyrwuslnb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.tianlin.xyz/Article/details/gthycffsfb.html

C#:   x is int or double or decimal
来源：http://dali.daria6918.cn/Article/details/gtppvlzaez.html

[B14] 判断值是否在集合内
来源：http://dali.mhx1999.top/Article/details/gtpejfttay.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jinyuanbaomall.cn/Article/details/gteiqorkgu.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shzxlz.cn/Article/details/gttsxuajxt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkbvtrcqv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtpsbrqqxs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtyfmeqtym.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxinkj.top/Article/details/gtbfibfphk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtpgynwlae.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtcisgvoad.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtfkuzzrle.html

Py:   a and b or not c
来源：http://dali.shzxlz.cn/Article/details/gteaeczrxn.html

PHP:  $a && $b || !$c
来源：http://dali.yongpay.top/Article/details/gtehrdckqz.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtvnedjbro.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gttmawfbiy.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtvtncqawk.html

Go:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtejrsnxsq.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtsyvjcfmv.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtfvkncnvp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtcsnofzer.html

Py:   if not data: return
来源：http://dali.ivvv.top/Article/details/gtbmegjgqw.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtrocanigh.html

JS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gtmacvdshy.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtekqawdhp.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtbpwyswyz.html

Go:   if data == nil { return }
来源：http://dali.yuanzhike.top/Article/details/gtrxwvkfyt.html

Ruby: return if data.nil?
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqgofhevm.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtlewvcmyc.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtezinoxyk.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtuqhzhvkk.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjlejqfvl.html

[C01] 定义函数
来源：http://dali.gaohongyu789.top/Article/details/gtqzmdrrsz.html

Py:   def add(a, b): return a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtfhfpwxbq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gtgbqypcfo.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtqtzvrfyc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtyxwjmsxc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtxadfzcaq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gtbwvxxyfa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxinkj.top/Article/details/gtdrzyfelx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtkgaedgwh.html

[C02] 默认参数
来源：http://dali.aizwys.cn/Article/details/gtfgoddckg.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtfihysema.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jianghu66.top/Article/details/gtlpqjgcom.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigufen.top/Article/details/gtkuslrlbf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtkmxpexpr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhijiandao.cn/Article/details/gtwqujpgdj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.dashuyun.cn/Article/details/gtlsvijgre.html

Ruby: def greet(name = "World") = name
来源：http://dali.zhongyouzk.top/Article/details/gtbjuaiftm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtlgpqowgf.html

[C03] 可变参数
来源：http://dali.tian-w.cn/Article/details/gtsxqccvfw.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtdbdfiuvv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.shuidangran.top/Article/details/gtflqeygpg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtioescnji.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtbmampaam.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.c1oappe.top/Article/details/gtfmwrnhsc.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtxeovaery.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtciromlcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtmyerhbwn.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hysaishi.cn/Article/details/gtmssyxgel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtlotwjzkp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.daria6918.cn/Article/details/gtdfxzcflf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fzhhl.top/Article/details/gtjcttaayt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zycfv.cn/Article/details/gtxlsijigd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtvqmfhixg.html

Go:   // 无：用配置结构体参数
来源：http://dali.shzxlz.cn/Article/details/gtsjsqivvf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.quarkkingdee.top/Article/details/gtoaivwvid.html

C#:   f(a: 1, b: 2)
来源：http://dali.snrcjt.cn/Article/details/gtsrcqexux.html

[C05] 返回多个值
来源：http://dali.tanke756.top/Article/details/gtvznvfzhl.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtytxandgd.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtsljorqso.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqsvyauw.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtzjtgkxmn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj20258.top/Article/details/gtfqkpfaac.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtabodlrra.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsdltgiu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gtsqhffyta.html

[C06] 匿名函数 / lambda
来源：http://dali.zhiwuduotai.top/Article/details/gthrjsuipx.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gteiehcwst.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuetiantiany.cn/Article/details/gttrpdzrhz.html

JS:   const square = x => x * x;
来源：http://dali.chenzaomai.com/Article/details/gteafbljlq.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtafyvzvvg.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigufen.top/Article/details/gtgqvabnmt.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhengqikj.top/Article/details/gtuzaaftuw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtsdceiikf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtpoxozgfs.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258.top/Article/details/gttpnaajbn.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcmiftgui.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shangyingyoupin.top/Article/details/gtrgecriud.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.redwolf501.top/Article/details/gtohzcolrm.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gtgvphgmth.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yanxiufei.cn/Article/details/gtdvlmvfgx.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.kuanghao11.cn/Article/details/gtvhhyxhcg.html

Ruby: arr.map(&:upcase)
来源：http://dali.yuxming.cn/Article/details/gtcfqjgijq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenjidiqi.icu/Article/details/gtjtmudsda.html

[C08] 闭包
来源：http://dali.tianlin.xyz/Article/details/gtsdsetukp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.mhx1999.top/Article/details/gtarqorihw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj202588.top/Article/details/gterneofda.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yongpay.top/Article/details/gtqfupxwkj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.pycfn.com/Article/details/gtsvivjtai.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.guowangkeji.top/Article/details/gtqrvkehhp.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daxiang520.top/Article/details/gtukzehrkt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.quarkkingdee.top/Article/details/gtqbrmzsqk.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtaocudkrm.html

[C09] 递归
来源：http://dali.aibaodan.cn/Article/details/gtngkztmer.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jiagoushi.top/Article/details/gtuasilaqr.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.redwolf501.top/Article/details/gttetvjbqc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nanxuanxn.top/Article/details/gtrmvnujnu.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtuvsrzgrz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.vqdsnc.cn/Article/details/gtjryjreuf.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ivvv.top/Article/details/gtqkywnvkh.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.shzxlz.cn/Article/details/gtkahskmca.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.tianlin.xyz/Article/details/gtawmifjwd.html

[C10] 变量作用域
来源：http://dali.sxryk.cn/Article/details/gthpllpgxa.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtobrahsvz.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yuanzhike.top/Article/details/gtbnubtxeq.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhiwuduotai.top/Article/details/gtqsehksac.html

TS:   同 JS
来源：http://dali.chenlongwang.top/Article/details/gtgoplldun.html

Java: 方法内为块级作用域
来源：http://dali.jyoumei.cn/Article/details/gtfhwdkbxy.html

Go:   花括号块级作用域
来源：http://dali.andypj.xyz/Article/details/gtekzvicqs.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.pycfn.com/Article/details/gtkihzrikc.html

C#:   块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtspwovtnt.html

[C11] 模块导入与导出
来源：http://dali.sweek.top/Article/details/gttgacddev.html

Py:   from module import func
来源：http://dali.wangshuangyany.cn/Article/details/gtpmkdzseq.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcqlcwtof.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.nanxuanxn.top/Article/details/gtqsszcccr.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cashguo.top/Article/details/gtraxgdcuk.html

Java: import java.util.List;
来源：http://dali.ppjwa.cn/Article/details/gtquqchnas.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yj20258.top/Article/details/gtuwdmdclf.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yj202588.top/Article/details/gthvwdyasc.html

C#:   using System.Text;
来源：http://dali.dianchejie.cn/Article/details/gtysedrmny.html

[C12] 立即执行函数 IIFE
来源：http://dali.chenjidiqi.icu/Article/details/gtcoezvctk.html

Py:   (lambda: print("run"))()
来源：http://dali.fzhhl.top/Article/details/gtavwqofsy.html

PHP:  (function () { echo "run"; })();
来源：http://dali.meibo888.top/Article/details/gtwladgjsk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gtncjbwbon.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gthdmohrjb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.xylfe.cn/Article/details/gthjzifrfv.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinqigfzy.top/Article/details/gtunolafod.html

Ruby: -> { puts "run" }.call
来源：http://dali.smart0.xyz/Article/details/gttuwrsgez.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hnqzz.top/Article/details/gtombpchdk.html

[C13] 类型声明 / 类型注解
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfpwzonjq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gtxatgoscb.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtyuxvovwu.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yonumen.top/Article/details/gttsfivilp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gticfgvmqd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gtqabhbemv.html

Go:   func add(a, b int) int
来源：http://dali.aibaodan.cn/Article/details/gtxxcyepfg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.9152youxi.cn/Article/details/gtvxxhhzst.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.wangshuangyany.cn/Article/details/gtimxssdjg.html

[C14] 泛型函数
来源：http://dali.dianchejie.cn/Article/details/gtbyjuvmew.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.gotoacloud.top/Article/details/gtrwrbnqvm.html

PHP:  // 无泛型
来源：http://dali.redwolf501.top/Article/details/gtgacviord.html

JS:   // 无泛型
来源：http://dali.0kj1m.cn/Article/details/gtfhvoagsq.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nanxuanxn.top/Article/details/gtfvrzozjy.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.ppjwa.cn/Article/details/gtrjygfhyg.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yongpay.top/Article/details/gthfjzzbvt.html

Ruby: # 无泛型
来源：http://dali.chenzaomai.com/Article/details/gtyxwackqs.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.iojbl.cn/Article/details/gtqmljqylg.html

[C15] 解构 / 展开参数
来源：http://dali.jinqigufen.top/Article/details/gtdzvzcxoz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shuidangran.top/Article/details/gtrbhibwwr.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtyivfolmi.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhengqikj.top/Article/details/gtkmdewizk.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shzxlz.cn/Article/details/gtwddibzig.html

Java: // 无解构
来源：http://dali.chenzaomai.com/Article/details/gtixxehrqy.html

Go:   // 无解构
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvgwspkip.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtijvcfcyu.html

C#:   var (a, b) = pair;
来源：http://dali.pycfn.com/Article/details/gtyubuzpge.html

[C16] 函数 / 方法重载
来源：http://dali.chenjidiqi.icu/Article/details/gtuimvckcf.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.shangyingyoupin.top/Article/details/gtfyhuzkky.html

PHP:  // 无重载
来源：http://dali.0kj1m.cn/Article/details/gtvjulaqai.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.guannengcc.top/Article/details/gtbeypdokp.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.shuidangran.top/Article/details/gtzocodygk.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtnutwapvp.html

Go:   // 无重载：用不同函数名
来源：http://dali.fzhhl.top/Article/details/gtwcwdfmtt.html

Ruby: # 无重载：靠动态参数
来源：http://dali.316326.xyz/Article/details/gtfyrdmpyl.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtxupnylpc.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtvojwuhcu.html

D. 数组 / 列表 / 集合
来源：http://dali.andypj.xyz/Article/details/gtwjyfsntx.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtclpikgnk.html

[D01] 创建数组 / 列表
来源：http://dali.ehwqpu.com/Article/details/gtmwsqaydv.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.yuxming.cn/Article/details/gtuwujintr.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pengpengdd.cyou/Article/details/gtmqmbclvf.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.hnqzz.top/Article/details/gttyfhluzj.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.jyoumei.cn/Article/details/gtblfyjmat.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.pengpengdd.cyou/Article/details/gtbbnmfkeb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.meibo888.top/Article/details/gtupjizcjn.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhoulong.xyz/Article/details/gthqwsgqdi.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sxryk.cn/Article/details/gtxdehwwqz.html

[D02] 追加元素到末尾
来源：http://dali.sxryk.cn/Article/details/gtotyscwki.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxivxqbs.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.bjfxy.top/Article/details/gtzmvyymww.html

JS:   arr.push(4);
来源：http://dali.zdqjudy.top/Article/details/gtfqacridc.html

TS:   arr.push(4);
来源：http://dali.guannengcc.top/Article/details/gtrmdeyqyj.html

Java: list.add(4);
来源：http://dali.jinqigufen.top/Article/details/gtnoqamjsw.html

Go:   arr = append(arr, 4)
来源：http://dali.nwbrower.top/Article/details/gtgwbckezx.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sxryk.cn/Article/details/gtsekqwzzv.html

C#:   list.Add(4);
来源：http://dali.xziqi.cn/Article/details/gtvgphryvt.html

[D03] 在指定位置插入元素
来源：http://dali.yonumen.top/Article/details/gtmacimjnu.html

Py:   arr.insert(0, 0)
来源：http://dali.nanxuanxn.top/Article/details/gtvvauytrg.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.shangyingyoupin.top/Article/details/gtgeqloepb.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.svipenyu.cn/Article/details/gtxewvxetm.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.shuidangran.top/Article/details/gtccmvsjbw.html

Java: list.add(0, 0);
来源：http://dali.chenzaomai.com/Article/details/gtdhcsqsmu.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.nanxuanxn.top/Article/details/gtylrfiddh.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.havefunace.top/Article/details/gtrxevqvfu.html

C#:   list.Insert(0, 0);
来源：http://dali.cheryme.top/Article/details/gtyylcoblq.html

[D04] 删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtcpptguqt.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.jinghuilouyu.cn/Article/details/gtrhuorbcp.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.yueranfly.top/Article/details/gtwtsgqhoh.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.iojbl.cn/Article/details/gtlhgbxcgn.html

TS:   arr.splice(0, 1);
来源：http://dali.quarkkingdee.top/Article/details/gtnvvhkawq.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.nanxinkj.top/Article/details/gtsgqeeekq.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.aibaodan.cn/Article/details/gtjfznrodm.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.quarkkingdee.top/Article/details/gtfmcttnpm.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.feifeiyinyue.top/Article/details/gtrlzqpegp.html

[D05] 访问与修改元素
来源：http://dali.0kj1m.cn/Article/details/gtqaqafgeo.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.gotoacloud.top/Article/details/gtblwyecst.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.tian-w.cn/Article/details/gtcoeyjfwj.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.jianghu66.top/Article/details/gtqkzezzue.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjppwcifc.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj20258.top/Article/details/gtatbbdtpd.html


<!-- 参考信息 -->