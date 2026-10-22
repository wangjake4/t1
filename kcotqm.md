代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gt2bdkxydnb.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gt2dprbcysk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gt2xtwvguoh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gt2gzqynsgg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gt2mygwzcjt.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gt2cwggkljb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.redwolf501.top/Article/details/gt2olcvsxaf.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gt2rosjyahn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gt2isofohlw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gaohongyu789.top/Article/details/gt2krgbvrwu.html

[B03] switch / match / case
来源：http://dali.xuetiantiany.cn/Article/details/gt2liywabgu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.iojbl.cn/Article/details/gt2imnpmpjw.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.birdmap.top/Article/details/gt2cdzyjexl.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gt2yzwpnlek.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2mqiydgpa.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gt2dscidime.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gt2kxdwccwi.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cashguo.top/Article/details/gt2axnmemjp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuetiantiany.cn/Article/details/gt2hidgrdkn.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gt2dnugexdg.html

Py:   for i in range(10): print(i)
来源：http://dali.svipenyu.cn/Article/details/gt2qwofiakz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qojonqwd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gt2ftuzerzi.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jkflvyev.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shzxlz.cn/Article/details/gt2fwhtmpsf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj202588.top/Article/details/gt2vnxieahv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gt2qotzguny.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gt2wwvylxwj.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gt2slsmubxr.html

Py:   for item in arr: print(item)
来源：http://dali.tianlin.xyz/Article/details/gt2icktxvip.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.cdnleiting.top/Article/details/gt2pzwreeok.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gt2tfvqaqfw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gt2cceefgld.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.snrcjt.cn/Article/details/gt2ommwxglf.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gt2lvhfhekr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gt2qtpygooh.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tianlin.xyz/Article/details/gt2udyacbhb.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2rwvbwahd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cdnleiting.top/Article/details/gt2wsaxglhx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.cashguo.top/Article/details/gt2tbleejxp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuanzx.com/Article/details/gt2jiwptkmh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ogkclnpp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.daria6918.cn/Article/details/gt2occfkfmk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tanke756.top/Article/details/gt2kscstdys.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.tianlin.xyz/Article/details/gt2edupirvt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhoulong.xyz/Article/details/gt2bfvamcde.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gt2mkowfshk.html

Py:   while i < 10: i += 1
来源：http://dali.cdnleiting.top/Article/details/gt2uhbuskkx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.nwbrower.top/Article/details/gt2tkbkevfy.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wbztksvj.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2vbyvdyoi.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gt2gwmvcqgy.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gt2zlmxzdkx.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gt2ddosrbjh.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gt2umberkwm.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gt2crmnqmpv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gt2zwyometw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2eecflnxc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gt2dsysksur.html

TS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wjahjuau.html

Java: do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gt2uagshggr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gt2cnsvsjqa.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangshuangyany.cn/Article/details/gt2cfybtrkl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gt2firotkeq.html

[B09] break 与 continue
来源：http://dali.shangyingyoupin.top/Article/details/gt2tbkqrgsl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gt2bjgmnbpj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2ndniahky.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gt2hrzuqyjo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2ugdtkwpv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gt2qlvlzusj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnqzz.top/Article/details/gt2rhbwzyci.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gt2krkccdvc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2zcvvkwqg.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gt2pghqafad.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ehwqpu.com/Article/details/gt2okupbnyx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sweek.top/Article/details/gt2bhiknjkk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xylfe.cn/Article/details/gt2jbmvflan.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhoulong.xyz/Article/details/gt2kdinnqne.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.guannengcc.top/Article/details/gt2wvhzvdwa.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cooeimmh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jianghu66.top/Article/details/gt2moaqdats.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cucudq.cn/Article/details/gt2xxkklyov.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhixingplan.top/Article/details/gt2hvgeesjs.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenjidiqi.icu/Article/details/gt2fgejyjge.html

PHP:  range(0, 10, 2);
来源：http://dali.nanxuanxn.top/Article/details/gt2hodqjzyu.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.aizwys.cn/Article/details/gt2ivitsttd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jyoumei.cn/Article/details/gt2yowxiigr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gt2qdloepbm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gt2lehzbuea.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhoulong.xyz/Article/details/gt2walyjdsz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.daria6918.cn/Article/details/gt2kfswytsn.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gt2lxbdnmpw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gogol.net.cn/Article/details/gt2unpwudnp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhoulong.xyz/Article/details/gt2grlbmxos.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gt2rvovvhxg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2wsxrwatv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyjjiiiz.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhongyouzk.top/Article/details/gt2ychytnad.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nwbrower.top/Article/details/gt2kjbqoigo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gt2bwiwpkag.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gt2hdczxoak.html

Py:   isinstance(x, (int, float))
来源：http://dali.wangdashe.top/Article/details/gt2uzhoroeb.html

PHP:  is_numeric($x)
来源：http://dali.nanxuanxn.top/Article/details/gt2dqitvkab.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yvedp.cn/Article/details/gt2bhdzgagy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2xobipegx.html

Java: x instanceof Number
来源：http://dali.hongshengwenyu.top/Article/details/gt2wabvntto.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hywenlv.cn/Article/details/gt2mjzspvlz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gt2wpmqtoly.html

C#:   x is int or double or decimal
来源：http://dali.daxiang520.top/Article/details/gt2xnxwcfqn.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gt2bgneidat.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.birdmap.top/Article/details/gt2fnmkovnr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnxiangtu.top/Article/details/gt2rihtiekv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhixingplan.top/Article/details/gt2vnaidces.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gt2blxeudeu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gt2cjqzpqpq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jqyxqdzi.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gt2njxivthm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2oxggfukl.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gt2blgacjhw.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gt2udjvglde.html

PHP:  $a && $b || !$c
来源：http://dali.yuanzhike.top/Article/details/gt2clqjeenp.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gt2eeulymzo.html

TS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2blllajvx.html

Java: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gt2znvpmzbf.html

Go:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gt2flniumrb.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2luwwpbel.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rhzhztjk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2ywmjdrsq.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gt2vwmwdydy.html

PHP:  if (!$data) { return; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2cijntayy.html

JS:   if (!data) return;
来源：http://dali.jianghu66.top/Article/details/gt2xgorlxny.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gt2tdwdszbw.html

Java: if (data == null) return;
来源：http://dali.cucudq.cn/Article/details/gt2zgukustc.html

Go:   if data == nil { return }
来源：http://dali.feifeiyinyue.top/Article/details/gt2rgcqqlpm.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gt2rbxrrpus.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2ekrjelje.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2skesdjsi.html

C. 函数与作用域
来源：http://dali.daria6918.cn/Article/details/gt2urbwzomw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2eicbhsxj.html

[C01] 定义函数
来源：http://dali.zhengqikj.top/Article/details/gt2uqcxnosl.html

Py:   def add(a, b): return a + b
来源：http://dali.xinyue.icu/Article/details/gt2hpplawwv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ycbilbmf.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gt2ghpyeztg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2sgaithly.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2pbjxtxfj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gzhubu.top/Article/details/gt2keyaadtx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ehwqpu.com/Article/details/gt2shkmcymm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2epnkdzgu.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hozphduy.html

Py:   def greet(name="World"): return name
来源：http://dali.shangyingyoupin.top/Article/details/gt2kogpuqlb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2orvhomzk.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jyoumei.cn/Article/details/gt2vazjhxmz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gt2muwlmqha.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gt2lodezgyd.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.pycfn.com/Article/details/gt2tribgkpm.html

Ruby: def greet(name = "World") = name
来源：http://dali.hywenlv.cn/Article/details/gt2lpdexool.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.aizwys.cn/Article/details/gt2fulhqymk.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gt2fqwdzebz.html

Py:   def total(*args): return sum(args)
来源：http://dali.aibaodan.cn/Article/details/gt2ilgsiyge.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sweek.top/Article/details/gt2tgqwjcin.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shzxlz.cn/Article/details/gt2bdisdjfo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sweek.top/Article/details/gt2gfqnsomr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gt2wclvudjn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gt2aoeotyhq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yonumen.top/Article/details/gt2pbwvwpuw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gt2tdvtnppp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ozwnjdvo.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jzzadxvb.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhijiandao.cn/Article/details/gt2wemncsam.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gt2tdrllrmz.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2pnaunhdh.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxinkj.top/Article/details/gt2qqbtstlm.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tohcdpzv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gt2puefrpcp.html

C#:   f(a: 1, b: 2)
来源：http://dali.cqqwz.cn/Article/details/gt2vudnfgcl.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gt2scqrhhyg.html

Py:   return a, b
来源：http://dali.aizwys.cn/Article/details/gt2aytuzgqx.html

PHP:  return [$a, $b];
来源：http://dali.zdqjudy.top/Article/details/gt2jqpflsyp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2qddxtxbx.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2dtkskudy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gt2mgmoxsrw.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gt2mrczhzig.html

Ruby: return a, b
来源：http://dali.shzxlz.cn/Article/details/gt2mvujzfkj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gt2aupcvkov.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gt2nxiaxgyi.html

Py:   square = lambda x: x * x
来源：http://dali.smart0.xyz/Article/details/gt2nebokmeu.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gt2yrwlptdx.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2dsgznfmk.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gt2waqcymxq.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.cucudq.cn/Article/details/gt2ydybjsby.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shuidangran.top/Article/details/gt2fdqxjzol.html

Ruby: square = ->(x) { x * x }
来源：http://dali.jqgufenzy.top/Article/details/gt2caqgdkaw.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gt2gwgkopbe.html

[C07] 把函数作为参数传入
来源：http://dali.nanxinkj.top/Article/details/gt2pkygqioy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.tianlin.xyz/Article/details/gt2fkfxkorv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gt2yaguekxr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ahzpaili.html

TS:   arr.map(String)
来源：http://dali.pycfn.com/Article/details/gt2hkuarolr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.tianlin.xyz/Article/details/gt2cbedfkml.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2zyxkcxcp.html

Ruby: arr.map(&:upcase)
来源：http://dali.shangyingyoupin.top/Article/details/gt2bsidhhur.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yuxming.cn/Article/details/gt2pyrilpoz.html

[C08] 闭包
来源：http://dali.hnqzz.top/Article/details/gt2jiuiniil.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.feifeiyinyue.top/Article/details/gt2jawmjsnk.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.0kj1m.cn/Article/details/gt2xzztfhyp.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wznnkxeb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gt2xrkcllmj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gt2kaxleppr.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2iufakual.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj202588.top/Article/details/gt2onioxyfg.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gt2ottpzsiz.html

[C09] 递归
来源：http://dali.ybcxt.top/Article/details/gt2jopjpdzz.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dianchejie.cn/Article/details/gt2mhqzyyuk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jiagoushi.top/Article/details/gt2oapdmwod.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ivvv.top/Article/details/gt2tvtshmfv.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ydzc1.top/Article/details/gt2eoqvmdva.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.mhx1999.top/Article/details/gt2hxmefixk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bbpmfhpf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.fzhhl.top/Article/details/gt2xeujqtbt.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.hongshengwenyu.top/Article/details/gt2powskuww.html

[C10] 变量作用域
来源：http://dali.zhongyouzk.top/Article/details/gt2ohvrcyag.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.9152youxi.cn/Article/details/gt2yycvyjzy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gt2rmqcseio.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.tanke756.top/Article/details/gt2ctcurcoz.html

TS:   同 JS
来源：http://dali.aizwys.cn/Article/details/gt2dmjhwldl.html

Java: 方法内为块级作用域
来源：http://dali.yj202588.top/Article/details/gt2abyykxnw.html

Go:   花括号块级作用域
来源：http://dali.316326.xyz/Article/details/gt2rkllgtyx.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.hfpthk.cn/Article/details/gt2rylgmqrd.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gt2jbfbojgl.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gt2xbjxaejl.html

Py:   from module import func
来源：http://dali.ehwqpu.com/Article/details/gt2gacqefat.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ylysbrxp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.fengsongda.top/Article/details/gt2secoojoi.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yvedp.cn/Article/details/gt2aamfoyhq.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2tecccqsy.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jiagoushi.top/Article/details/gt2anqbyqsr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hfsbiool.html

C#:   using System.Text;
来源：http://dali.zhiwuduotai.top/Article/details/gt2chppkfrs.html

[C12] 立即执行函数 IIFE
来源：http://dali.jiagoushi.top/Article/details/gt2mrvktwtj.html

Py:   (lambda: print("run"))()
来源：http://dali.ehwqpu.com/Article/details/gt2xhwycbrx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2zfuzbicm.html

JS:   (() => { console.log("run"); })();
来源：http://dali.jinqigufen.top/Article/details/gt2vyzjrqig.html

TS:   (() => { console.log("run"); })();
来源：http://dali.sweek.top/Article/details/gt2gnojmpil.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.svipenyu.cn/Article/details/gt2mcyocqok.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jlsjyb.cn/Article/details/gt2deiphtgv.html

Ruby: -> { puts "run" }.call
来源：http://dali.dianchejie.cn/Article/details/gt2pgqrczfd.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.havefunace.top/Article/details/gt2igfpzgiu.html

[C13] 类型声明 / 类型注解
来源：http://dali.gotoacloud.top/Article/details/gt2gooukatc.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.smart0.xyz/Article/details/gt2cbnskmss.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nnzhgmhw.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dkidckzz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2vnqjjfoq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gogol.net.cn/Article/details/gt2rldjkwgd.html

Go:   func add(a, b int) int
来源：http://dali.yonumen.top/Article/details/gt2jxvcttvl.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.birdmap.top/Article/details/gt2tjnagnrv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.9152youxi.cn/Article/details/gt2xkwsgkyd.html

[C14] 泛型函数
来源：http://dali.jlsjyb.cn/Article/details/gt2mfizjixc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.aizwys.cn/Article/details/gt2rwxfbsup.html

PHP:  // 无泛型
来源：http://dali.jlsjyb.cn/Article/details/gt2shcmcbzm.html

JS:   // 无泛型
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hqnnxacv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.nwbrower.top/Article/details/gt2rbmplsiq.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.xuanzx.com/Article/details/gt2qdnvrvcv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yj20258888.top/Article/details/gt2qwzylnmj.html

Ruby: # 无泛型
来源：http://dali.gogol.net.cn/Article/details/gt2zzdspxij.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hnqzz.top/Article/details/gt2pwdtfpvv.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2tkwcfhfs.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.birdmap.top/Article/details/gt2lhskigib.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shangyingyoupin.top/Article/details/gt2mqlsyibp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2vtdxdjqh.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hywenlv.cn/Article/details/gt2kqapcyyu.html

Java: // 无解构
来源：http://dali.fengsongda.top/Article/details/gt2sumuhkht.html

Go:   // 无解构
来源：http://dali.cdnleiting.top/Article/details/gt2rbikwwfx.html

Ruby: a, b = pair
来源：http://dali.jqgufenzy.top/Article/details/gt2hbqfhdcc.html

C#:   var (a, b) = pair;
来源：http://dali.cheryme.top/Article/details/gt2iijwxoup.html

[C16] 函数 / 方法重载
来源：http://dali.nwbrower.top/Article/details/gt2lcvhzgve.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.andypj.xyz/Article/details/gt2hedvbqzy.html

PHP:  // 无重载
来源：http://dali.daxiang520.top/Article/details/gt2jbawptej.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.0kj1m.cn/Article/details/gt2kxttcgmc.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2hehjarxi.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2qfvkvsah.html

Go:   // 无重载：用不同函数名
来源：http://dali.hywenlv.cn/Article/details/gt2dzvcqyua.html

Ruby: # 无重载：靠动态参数
来源：http://dali.tanke756.top/Article/details/gt2iivtxpjz.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.hywenlv.cn/Article/details/gt2coqfsare.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2qtsydlxz.html

D. 数组 / 列表 / 集合
来源：http://dali.zhixingplan.top/Article/details/gt2fvxxgsot.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2sgolvoax.html

[D01] 创建数组 / 列表
来源：http://dali.cashguo.top/Article/details/gt2sctwsxuu.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.sufxvd.cn/Article/details/gt2racznorw.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.sxryk.cn/Article/details/gt2atowkfwy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.dianchejie.cn/Article/details/gt2ncswkffe.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.sxryk.cn/Article/details/gt2jzjxpyky.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.birdmap.top/Article/details/gt2mcjqeqpk.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sxqpdfkg.html

Ruby: arr = [1, 2, 3]
来源：http://dali.hnqzz.top/Article/details/gt2galnszqf.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yueranfly.top/Article/details/gt2yutpihbr.html

[D02] 追加元素到末尾
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xxdseuhr.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.jinqigfzy.top/Article/details/gt2wkumlbxh.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.cqqwz.cn/Article/details/gt2rhczalgw.html

JS:   arr.push(4);
来源：http://dali.snrcjt.cn/Article/details/gt2zzwwimrj.html

TS:   arr.push(4);
来源：http://dali.jianghu66.top/Article/details/gt2yxgmrxbd.html


<!-- 参考信息 -->