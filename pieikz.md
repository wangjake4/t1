代发 wailian999

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gtmptvhofn.html

[B02] 多分支 else if / elif
来源：http://dali.hfpthk.cn/Article/details/gtnxktsdpm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shangyingyoupin.top/Article/details/gtcgotlpsm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.haohaochexian.top/Article/details/gtqgebqbqd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtrebgzdpm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtbayreskf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtigqlreqv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guowangkeji.top/Article/details/gtsqjtjbxj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gthhrkulkj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtwzyfhxtv.html

[B03] switch / match / case
来源：http://dali.vqdsnc.cn/Article/details/gturpkmhoa.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xuanzx.com/Article/details/gtqsurmamr.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtpnfmhqva.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xuetiantiany.cn/Article/details/gthfbcykcq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtszcyqgjp.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gttamlbxcd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtylahizxm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yuxming.cn/Article/details/gtyvzaytrj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yueranfly.top/Article/details/gtqpobnqwi.html

[B04] for 计数循环
来源：http://dali.hongshengwenyu.top/Article/details/gtcvkhshhn.html

Py:   for i in range(10): print(i)
来源：http://dali.jlsjyb.cn/Article/details/gtfwfexejn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcuyrqftf.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaicrfihk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttczokpeb.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhongyouzk.top/Article/details/gtbuoazrzf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.tianlin.xyz/Article/details/gtgnbppjjy.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhiwuduotai.top/Article/details/gtdqjcohzr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.cashguo.top/Article/details/gtsgwccplc.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtpxafhpkx.html

Py:   for item in arr: print(item)
来源：http://dali.aibaodan.cn/Article/details/gtpwndpkrm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.chenzaomai.com/Article/details/gtgoqdfwtc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhoulong.xyz/Article/details/gtpoertsui.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gtsqmadwdq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmuifxnr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhijiandao.cn/Article/details/gtpqooxrjp.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shuidangran.top/Article/details/gtneuzmwcv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.mhx1999.top/Article/details/gtfoqnmzfk.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gtasvyzqgu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dashuyun.cn/Article/details/gticuwvygr.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yvedp.cn/Article/details/gtdqutgdvf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gteiwtqfog.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtbgxjqwnc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtujtlgpdb.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ehwqpu.com/Article/details/gtusavadnv.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ivvv.top/Article/details/gthcnnqkwn.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfdrfoiyp.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtqahibqmw.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gtynvlcjqb.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zdqjudy.top/Article/details/gtkxymaojb.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtxifvsgjn.html

TS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxnhirhhb.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdsqcdbtv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gtfgckqioi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jiagoushi.top/Article/details/gtrmvuirma.html

C#:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtuibpdywl.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gtkszmsbqv.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jinghuilouyu.cn/Article/details/gtwywwdrva.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sysykeji.top/Article/details/gttfpouatk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtzazwjwfc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtyqjjvdax.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtjtllbpim.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtpmbxplje.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gtobnmrfbo.html

C#:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gtdxqdompd.html

[B09] break 与 continue
来源：http://dali.mhx1999.top/Article/details/gtjydhdcln.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtxnqnozgb.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtaaucbwyx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gtxttbiuoh.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gtdbpznlkc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtagicrksc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gttvrblixf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gtrkzhpdvz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtzleeximg.html

[B10] 遍历同时拿索引
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsiynjfh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gaohongyu789.top/Article/details/gtmxwzftwb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gttjajphxl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtzlrxrclz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtggykjwvb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sweek.top/Article/details/gthxezfwsk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gtkeczqljl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.gogol.net.cn/Article/details/gtszoivwaa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtoogygjhm.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzaafgtw.html

Py:   list(range(0, 10, 2))
来源：http://dali.gaohongyu789.top/Article/details/gtiqsuigoi.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtkswysqga.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gttibxnaui.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gtnszglmcg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gtmhvkhsth.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.daria6918.cn/Article/details/gtnibnzqbc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtlrolrvzg.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnqzz.top/Article/details/gtdnsjidbn.html

[B12] 跳出多层循环
来源：http://dali.jinqigfzy.top/Article/details/gtodsvvcie.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtinzmrwaz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.chenlongwang.top/Article/details/gtlidwqrhk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gtcjobahbx.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtmottgrnu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258888.top/Article/details/gtuhkisjkm.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtmynghqzo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.daxiang520.top/Article/details/gtggiiwbrd.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gtizutqbkv.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gtddwsxwrf.html

Py:   isinstance(x, (int, float))
来源：http://dali.yueranfly.top/Article/details/gtceiytxdi.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtpeycssox.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtadqhlbtc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gogol.net.cn/Article/details/gtitgvnruu.html

Java: x instanceof Number
来源：http://dali.pycfn.com/Article/details/gtlwwlguvt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.316326.xyz/Article/details/gtuaswwsgz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cheryme.top/Article/details/gtciqwbact.html

C#:   x is int or double or decimal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuehzosdo.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtjrvatlbz.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtdzvcskue.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhiwuduotai.top/Article/details/gthmujafzz.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtqbyfcaun.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gteftdvojr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.hammf.cn/Article/details/gtvunrusmt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gtniaryius.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sysykeji.top/Article/details/gtjmicyuqh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.pycfn.com/Article/details/gtfeblalxd.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtuwhfkxkx.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtkoatjrrw.html

PHP:  $a && $b || !$c
来源：http://dali.shuidangran.top/Article/details/gtspmristn.html

JS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtnmknfybh.html

TS:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtzdjuahhu.html

Java: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtsezwtiej.html

Go:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtokymqsrt.html

Ruby: a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuprdbegf.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtrvzxuzdo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gterhfrpsj.html

Py:   if not data: return
来源：http://dali.yonumen.top/Article/details/gtdxlirknh.html

PHP:  if (!$data) { return; }
来源：http://dali.quarkkingdee.top/Article/details/gtgofodzuw.html

JS:   if (!data) return;
来源：http://dali.cashguo.top/Article/details/gtvpcyanvk.html

TS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtwxywhevw.html

Java: if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtkaxrpoya.html

Go:   if data == nil { return }
来源：http://dali.xinyue.icu/Article/details/gtferzrwgs.html

Ruby: return if data.nil?
来源：http://dali.yuanzhike.top/Article/details/gtxvgdllpk.html

C#:   if (data == null) return;
来源：http://dali.haohaochexian.top/Article/details/gtfjycdqcg.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtqufwxzcv.html

C. 函数与作用域
来源：http://dali.gaohongyu789.top/Article/details/gtzjukhniw.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtvwobeljk.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtrmqgbjtv.html

Py:   def add(a, b): return a + b
来源：http://dali.redwolf501.top/Article/details/gtnpfbvpwv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtdkmkhzff.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtibsflvfs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtunncwlnr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtchpbdwto.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.meibo888.top/Article/details/gtcgeeaowe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gtrzjzqxyn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtoiiolpyz.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtvwlsocdv.html

Py:   def greet(name="World"): return name
来源：http://dali.shanyushiyangtech.top/Article/details/gtabtrfwcq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.smart0.xyz/Article/details/gtnnsyresi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jianghu66.top/Article/details/gtprbrboja.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.c1oappe.top/Article/details/gtvdhkwauq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cheryme.top/Article/details/gtnisxbpqy.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cashguo.top/Article/details/gtgaiqehev.html

Ruby: def greet(name = "World") = name
来源：http://dali.hammf.cn/Article/details/gtxoupjnxq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtefuaaccp.html

[C03] 可变参数
来源：http://dali.cheryme.top/Article/details/gtqlqmhxrs.html

Py:   def total(*args): return sum(args)
来源：http://dali.316326.xyz/Article/details/gtyfzlxryt.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cqqwz.cn/Article/details/gtkykiqxml.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gthcmlvcix.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gthwmoedkh.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtbhqqruss.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ppjwa.cn/Article/details/gtybfbjias.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.dianchejie.cn/Article/details/gtlsrloayb.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgufenzy.top/Article/details/gtbdsekgub.html

[C04] 命名参数 / 关键字参数
来源：http://dali.feifeiyinyue.top/Article/details/gtvilxiiqg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.316326.xyz/Article/details/gtnebhqoej.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ydzc1.top/Article/details/gtovfotqoa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnxiangtu.top/Article/details/gthuszshlw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtynjlpkoe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtudnsdxub.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtjzoitelk.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtysvsopsp.html

C#:   f(a: 1, b: 2)
来源：http://dali.tanke756.top/Article/details/gtbogbhbur.html

[C05] 返回多个值
来源：http://dali.jinghuilouyu.cn/Article/details/gtjjzeqxxm.html

Py:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtfhzykzdo.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtooxxpwzu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtgzjwovnu.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtdvkbomdz.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gtgdiqjxxi.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtyndliftx.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gthrhqpakl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtvnqmxhqd.html

[C06] 匿名函数 / lambda
来源：http://dali.xylfe.cn/Article/details/gtithmvqgw.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtgceqczpd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sxryk.cn/Article/details/gtngnvqdyo.html

JS:   const square = x => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtsumavdlf.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtwiavtkil.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yuanzhike.top/Article/details/gtqptibfjo.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yuxming.cn/Article/details/gtjyufmmkj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnqzz.top/Article/details/gtmxhpokpe.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zycfv.cn/Article/details/gtueuvqdgq.html

[C07] 把函数作为参数传入
来源：http://dali.wangshuangyany.cn/Article/details/gtirnaohko.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.yonumen.top/Article/details/gtmrtoaeqe.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.mhx1999.top/Article/details/gtvowivkgp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhixingplan.top/Article/details/gtshsetdsh.html

TS:   arr.map(String)
来源：http://dali.andypj.xyz/Article/details/gtdgumllgj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtptnxofmu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.fzhhl.top/Article/details/gtdcqfykos.html

Ruby: arr.map(&:upcase)
来源：http://dali.havefunace.top/Article/details/gtbajshejb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yueranfly.top/Article/details/gtxvhivonm.html

[C08] 闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotqstzck.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.hywenlv.cn/Article/details/gtrcxgoeir.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtssgpeiuo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.cucudq.cn/Article/details/gtgixavtdm.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.dashuyun.cn/Article/details/gtusuqwpnt.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtnbeseppt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shuidangran.top/Article/details/gtxbzmxshw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jqgfzy.top/Article/details/gtddpadiut.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gtxhehvxkm.html

[C09] 递归
来源：http://dali.cqqwz.cn/Article/details/gtoywjnynf.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.gaohongyu789.top/Article/details/gtbnzxbfee.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtunyefbca.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenjidiqi.icu/Article/details/gtdmukvphy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hysaishi.cn/Article/details/gtsrzvivpl.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtxnlzcsfw.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.pycfn.com/Article/details/gtaeolgwzj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhongyouzk.top/Article/details/gtalttbzoe.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gtmhnhnncc.html

[C10] 变量作用域
来源：http://dali.fengsongda.top/Article/details/gtrrzyiqzi.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gtlaswfktr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.iojbl.cn/Article/details/gtgpcttynk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.yueranfly.top/Article/details/gtvpkvlcgm.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtkfwubbzj.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gtfvjjqoft.html

Go:   花括号块级作用域
来源：http://dali.aizwys.cn/Article/details/gthygoxoji.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.xuetiantiany.cn/Article/details/gtikaxpyvj.html

C#:   块级作用域
来源：http://dali.yanxiufei.cn/Article/details/gtwevsvwut.html

[C11] 模块导入与导出
来源：http://dali.zhijiandao.cn/Article/details/gtsdeezydb.html

Py:   from module import func
来源：http://dali.aibaodan.cn/Article/details/gtlxebzfah.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.xylfe.cn/Article/details/gtuxuetvdw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.quarkkingdee.top/Article/details/gtahnlaazx.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.quarkkingdee.top/Article/details/gtonxuegax.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gtrilvntjh.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.haohaochexian.top/Article/details/gtnyigfviy.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.fengsongda.top/Article/details/gtcbsrnpke.html

C#:   using System.Text;
来源：http://dali.smart0.xyz/Article/details/gtuvreiasw.html

[C12] 立即执行函数 IIFE
来源：http://dali.316326.xyz/Article/details/gtogktykys.html

Py:   (lambda: print("run"))()
来源：http://dali.aibaodan.cn/Article/details/gtvuixysne.html

PHP:  (function () { echo "run"; })();
来源：http://dali.quarkkingdee.top/Article/details/gtzvyajffu.html

JS:   (() => { console.log("run"); })();
来源：http://dali.hammf.cn/Article/details/gtvguhwrhb.html

TS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvvuepya.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.gzhubu.top/Article/details/gtglkqeawa.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.hfpthk.cn/Article/details/gtamlasmbo.html

Ruby: -> { puts "run" }.call
来源：http://dali.yanxiufei.cn/Article/details/gtgocupnvw.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gogol.net.cn/Article/details/gtpiaplsll.html

[C13] 类型声明 / 类型注解
来源：http://dali.yuxming.cn/Article/details/gtqwcqssbb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.sweek.top/Article/details/gtxkfomzix.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtilecilws.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.cheryme.top/Article/details/gtymlsyiec.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtoxbtomlq.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtxsvquzho.html

Go:   func add(a, b int) int
来源：http://dali.jianghu66.top/Article/details/gtxvdlkfbg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.nanxuanxn.top/Article/details/gtuhbohsqh.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.pengpengdd.cyou/Article/details/gtvaxfwqvm.html

[C14] 泛型函数
来源：http://dali.xziqi.cn/Article/details/gtfdvbplwl.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgfzy.top/Article/details/gtoddhmcwa.html

PHP:  // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsuszuhnd.html

JS:   // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gthhganlru.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gogol.net.cn/Article/details/gtzbbntfoi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.jyoumei.cn/Article/details/gtxzxartjm.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.cdnleiting.top/Article/details/gtlkachrnq.html

Ruby: # 无泛型
来源：http://dali.jyoumei.cn/Article/details/gtdbueayfw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.guannengcc.top/Article/details/gtwggwxdwo.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtvwjxaufc.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zhiwuduotai.top/Article/details/gtuowzfjqd.html

PHP:  [$a, $b] = $pair;
来源：http://dali.daxiang520.top/Article/details/gtnushycef.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.jlsjyb.cn/Article/details/gtczbsrowe.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.hysaishi.cn/Article/details/gtubmhiitm.html

Java: // 无解构
来源：http://dali.jqgfzy.top/Article/details/gtrqqhfngb.html

Go:   // 无解构
来源：http://dali.yj202588.top/Article/details/gttbcrieeg.html

Ruby: a, b = pair
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzaixslq.html

C#:   var (a, b) = pair;
来源：http://dali.shuidangran.top/Article/details/gtsitlllsd.html

[C16] 函数 / 方法重载
来源：http://dali.gotoacloud.top/Article/details/gtkepymsak.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yueranfly.top/Article/details/gtizzhoaea.html

PHP:  // 无重载
来源：http://dali.wangshuangyany.cn/Article/details/gtuqimtzvl.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.gogol.net.cn/Article/details/gtovatxvqw.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yj20258.top/Article/details/gttnkmrgha.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtjtpeujwm.html

Go:   // 无重载：用不同函数名
来源：http://dali.tian-w.cn/Article/details/gtsuomrgks.html

Ruby: # 无重载：靠动态参数
来源：http://dali.sysykeji.top/Article/details/gtkodjlmbv.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtcuuaoabo.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtzxntxpcb.html

D. 数组 / 列表 / 集合
来源：http://dali.zhongyouzk.top/Article/details/gtfsfgwphj.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtokjxdqph.html

[D01] 创建数组 / 列表
来源：http://dali.xziqi.cn/Article/details/gtvriepsel.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvsshjxda.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.c1oappe.top/Article/details/gtmwunrumy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.cdnleiting.top/Article/details/gtkbahiclw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.chenzaomai.com/Article/details/gtifvktryd.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.0kj1m.cn/Article/details/gtplvshmnb.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yonumen.top/Article/details/gtajbqdjfd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.jinghuilouyu.cn/Article/details/gtgztfpahy.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.snrcjt.cn/Article/details/gtmjtkhzbw.html

[D02] 追加元素到末尾
来源：http://dali.0kj1m.cn/Article/details/gtawposfpn.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtqbcowkli.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.shzxlz.cn/Article/details/gtapsobwlx.html

JS:   arr.push(4);
来源：http://dali.cheryme.top/Article/details/gtpixnuvig.html

TS:   arr.push(4);
来源：http://dali.yvedp.cn/Article/details/gtaezmhtah.html


<!-- 参考信息 -->