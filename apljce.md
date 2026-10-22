代发 wailian999

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtuepnrjkk.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtprqgncps.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuxming.cn/Article/details/gtygkrnfes.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtluwnlynq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtxplwqtkx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.redwolf501.top/Article/details/gtaykpgwil.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifscdgtm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtxlpufxgi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtrofyvmzb.html

[B06] 遍历字典 / 对象
来源：http://dali.gaohongyu789.top/Article/details/gtvrpmhzhc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.cheryme.top/Article/details/gtmkzkimfl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gtcszhcexy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoncgkmgf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jiagoushi.top/Article/details/gtuvikuwwf.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xinyue.icu/Article/details/gtmksgnrwh.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gtyvobuvqy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dianchejie.cn/Article/details/gtszsfhabq.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtgntvsbbc.html

[B07] while 循环
来源：http://dali.jianghu66.top/Article/details/gtcaynihzx.html

Py:   while i < 10: i += 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoyuudzos.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yangfankeji.com/Article/details/gtjjtmjexy.html

JS:   while (i < 10) { i++; }
来源：http://dali.cdnleiting.top/Article/details/gtvjwyuvhk.html

TS:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtreldhqti.html

Java: while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxnrghkeo.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtubfkufhn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jyoumei.cn/Article/details/gtgifzthrq.html

C#:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gtyzywqnrq.html

[B08] do-while（至少执行一次）
来源：http://dali.sysykeji.top/Article/details/gtlygscsjt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhiwuduotai.top/Article/details/gtylzslbtv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.wangdashe.top/Article/details/gtgaqdsnop.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gthsaqgmoi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtvexcwulf.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gteptcucsb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtgawqvlgl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.gotoacloud.top/Article/details/gttuouhykn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtwcptjhgl.html

[B09] break 与 continue
来源：http://dali.hywenlv.cn/Article/details/gtmithhrbm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cheryme.top/Article/details/gtcbrfwvsh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtopanwlii.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.9152youxi.cn/Article/details/gtjjfwjcpq.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtieiqigji.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guowangkeji.top/Article/details/gtxiinnnml.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtzxdumcth.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.xuanzx.com/Article/details/gthtuszolb.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvsesabuw.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtpgsmdzul.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258888.top/Article/details/gtqespadvl.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgahlzynv.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yongpay.top/Article/details/gtvouwfutu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gtjutqvcrg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yvedp.cn/Article/details/gtvidytqty.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cdnleiting.top/Article/details/gtzphhfual.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhengqikj.top/Article/details/gttumorxkn.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shzxlz.cn/Article/details/gtetyfextb.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhengqikj.top/Article/details/gtcnybwxjo.html

Py:   list(range(0, 10, 2))
来源：http://dali.tianlin.xyz/Article/details/gtkvjujclz.html

PHP:  range(0, 10, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtqdzioqxw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xuanzx.com/Article/details/gtgxmozgkz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtvkrjzikj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.tanke756.top/Article/details/gthpszxqtc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ybcxt.top/Article/details/gtscskqbke.html

Ruby: (0...10).step(2).to_a
来源：http://dali.redwolf501.top/Article/details/gtxdpdfvps.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.vqdsnc.cn/Article/details/gtxunubkhn.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtgjdzbwsf.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cdnleiting.top/Article/details/gtjqalistd.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cdnleiting.top/Article/details/gtycgzafyw.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtcnjzcbpv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtnfeazxze.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yueranfly.top/Article/details/gtoaltklmo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.daxiang520.top/Article/details/gtcofvgred.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yongpay.top/Article/details/gtmtyonykg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hongshengwenyu.top/Article/details/gtqxestabf.html

[B13] 判断是否为数字
来源：http://dali.gzhubu.top/Article/details/gteaqclwfu.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhixingplan.top/Article/details/gtvtsqdjcr.html

PHP:  is_numeric($x)
来源：http://dali.xuetiantiany.cn/Article/details/gtjcxcphgz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtpzrviwxy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtpdpqzruj.html

Java: x instanceof Number
来源：http://dali.sufxvd.cn/Article/details/gtmudojhbk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.hysaishi.cn/Article/details/gtpnpwrzmu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hammf.cn/Article/details/gtouiuckrj.html

C#:   x is int or double or decimal
来源：http://dali.ppjwa.cn/Article/details/gtwhlroggg.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtvsteqjxu.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbdcelr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtmmatuzvq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcbvyfkxk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gthsbplekc.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gtdagqgrhl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.0kj1m.cn/Article/details/gtwzhlxcsq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ivvv.top/Article/details/gtazbpsqva.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzdczyaw.html

[B15] 布尔运算与取反
来源：http://dali.gaohongyu789.top/Article/details/gtucepwvmp.html

Py:   a and b or not c
来源：http://dali.zdqjudy.top/Article/details/gtscrzhtun.html

PHP:  $a && $b || !$c
来源：http://dali.ehwqpu.com/Article/details/gtwhtupqen.html

JS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtevwabppy.html

TS:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtbambzyfu.html

Java: a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gtlezggdrc.html

Go:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtuknthfhc.html

Ruby: a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtxcuoqjcx.html

C#:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtpdglhtoq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtvnkkuzwj.html

Py:   if not data: return
来源：http://dali.feifeiyinyue.top/Article/details/gtzgcabhqp.html

PHP:  if (!$data) { return; }
来源：http://dali.yongpay.top/Article/details/gtftlozbge.html

JS:   if (!data) return;
来源：http://dali.sysykeji.top/Article/details/gtonfagopd.html

TS:   if (!data) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtnjktiask.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gthfpmfosb.html

Go:   if data == nil { return }
来源：http://dali.yangfankeji.com/Article/details/gtxiysxhqi.html

Ruby: return if data.nil?
来源：http://dali.zhijiandao.cn/Article/details/gtgvgwmdiq.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtukhzgcvv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtgyukcwgh.html

C. 函数与作用域
来源：http://dali.yvedp.cn/Article/details/gtbyvrpycg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtqagqkafm.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gtpvyjbeag.html

Py:   def add(a, b): return a + b
来源：http://dali.sweek.top/Article/details/gtpoefjcvt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yueranfly.top/Article/details/gtvscesquc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsdzhippw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtqnucjgka.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtyowpcskv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtsjyyjysx.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtqyhsksgn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.guannengcc.top/Article/details/gtngqlvoal.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtkyfwqvat.html

Py:   def greet(name="World"): return name
来源：http://dali.yangfankeji.com/Article/details/gtglbcprfv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.0kj1m.cn/Article/details/gtwpeyqdtv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.chenzaomai.com/Article/details/gtpvzzhcdd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtffqtnrwe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtbwhkcbzp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.c1oappe.top/Article/details/gtkqvjjrbz.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtbstrmzit.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ppjwa.cn/Article/details/gtwrublkeb.html

[C03] 可变参数
来源：http://dali.gaohongyu789.top/Article/details/gtoyhyhqbv.html

Py:   def total(*args): return sum(args)
来源：http://dali.yanxiufei.cn/Article/details/gtmzgfnqkl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fzhhl.top/Article/details/gtrtggxrok.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhiwuduotai.top/Article/details/gthiogpemw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtbqkqncrj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daxiang520.top/Article/details/gtyblbmgee.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.daxiang520.top/Article/details/gtcunguspl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jyoumei.cn/Article/details/gtrpnpqzcn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.c1oappe.top/Article/details/gtswsjnjkg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hnxiangtu.top/Article/details/gturryfqzj.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gthvdigekg.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.tianlin.xyz/Article/details/gtyjfbgffa.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.quarkkingdee.top/Article/details/gtpgitabzs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xinyue.icu/Article/details/gtobomuxvu.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtticqpyrl.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gtwvpzgaxf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfptugwpx.html

C#:   f(a: 1, b: 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrafiioxl.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gtthvkhstc.html

Py:   return a, b
来源：http://dali.jqgfzy.top/Article/details/gtwnyzsydf.html

PHP:  return [$a, $b];
来源：http://dali.tanke756.top/Article/details/gtqahshokf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yj20258888.top/Article/details/gtdwjwjqmu.html

TS:   return { a, b };
来源：http://dali.c1oappe.top/Article/details/gtioubajdd.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtcyqfgvtb.html

Go:   return a, b
来源：http://dali.chenjidiqi.icu/Article/details/gtntmaagad.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gtbhtlmdlz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.cashguo.top/Article/details/gtnuawpsfg.html

[C06] 匿名函数 / lambda
来源：http://dali.mhx1999.top/Article/details/gtgvgfeetx.html

Py:   square = lambda x: x * x
来源：http://dali.hnqzz.top/Article/details/gttbtazhso.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gtgozqnkaj.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjrmuryj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.andypj.xyz/Article/details/gtvxfoswxs.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tian-w.cn/Article/details/gtcmvzthlf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ydzc1.top/Article/details/gthqhjvuyw.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtflhwhyyb.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gtnuuhevxr.html

[C07] 把函数作为参数传入
来源：http://dali.snrcjt.cn/Article/details/gtcekihnvh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.kuanghao11.cn/Article/details/gtwxiiuyzo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gteemojker.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gtcoibrjsz.html

TS:   arr.map(String)
来源：http://dali.hfpthk.cn/Article/details/gtcbblhloc.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cdnleiting.top/Article/details/gtvivnypwe.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ydzc1.top/Article/details/gtqguejygl.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gtfvghgcrq.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.wangdashe.top/Article/details/gtztbogeuo.html

[C08] 闭包
来源：http://dali.cucudq.cn/Article/details/gtmvqzsmqw.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.aizwys.cn/Article/details/gtggispaoc.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhoulong.xyz/Article/details/gtwehoaroh.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtxlghitez.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gtxigeyrwb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shuidangran.top/Article/details/gtzrwvzubj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gttbzekmgo.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtnnknbhdn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.nanxinkj.top/Article/details/gtuovvnoqo.html

[C09] 递归
来源：http://dali.fengsongda.top/Article/details/gtdejnalns.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.redwolf501.top/Article/details/gtgrminhos.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cheryme.top/Article/details/gtxfmouphp.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenzaomai.com/Article/details/gtgpaemhkz.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhijiandao.cn/Article/details/gtftpjdxlo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtkrnhrnhc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jqgfzy.top/Article/details/gteckazrur.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.vqdsnc.cn/Article/details/gtnltxpitg.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.mhx1999.top/Article/details/gtociweqsb.html

[C10] 变量作用域
来源：http://dali.snrcjt.cn/Article/details/gtyedxiafp.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.dashuyun.cn/Article/details/gteviiwrmo.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.fzhhl.top/Article/details/gtxczacqcb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtkyoujupk.html

TS:   同 JS
来源：http://dali.yongpay.top/Article/details/gtgkycontw.html

Java: 方法内为块级作用域
来源：http://dali.zycfv.cn/Article/details/gtagpkabcz.html

Go:   花括号块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtjylplehv.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ivvv.top/Article/details/gtolbpwyqt.html

C#:   块级作用域
来源：http://dali.wangdashe.top/Article/details/gttnbdtkhg.html

[C11] 模块导入与导出
来源：http://dali.smart0.xyz/Article/details/gtcgfgtesj.html

Py:   from module import func
来源：http://dali.yuanzhike.top/Article/details/gtqhewrrps.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sxryk.cn/Article/details/gtmugnscpy.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hongshengwenyu.top/Article/details/gtocfpwgkq.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cheryme.top/Article/details/gtmekkqnpz.html

Java: import java.util.List;
来源：http://dali.dashuyun.cn/Article/details/gttwizodar.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.jyoumei.cn/Article/details/gtetqyfkml.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.tianlin.xyz/Article/details/gtziedxpzt.html

C#:   using System.Text;
来源：http://dali.fzhhl.top/Article/details/gthfzmcogy.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtnrvumkdm.html

Py:   (lambda: print("run"))()
来源：http://dali.ydzc1.top/Article/details/gtcgjtvyec.html

PHP:  (function () { echo "run"; })();
来源：http://dali.fzhhl.top/Article/details/gttcprarjh.html

JS:   (() => { console.log("run"); })();
来源：http://dali.dashuyun.cn/Article/details/gtufhnksgk.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jianghu66.top/Article/details/gtociudgud.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.feifeiyinyue.top/Article/details/gtrjzcaksn.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yueranfly.top/Article/details/gtjupctivh.html

Ruby: -> { puts "run" }.call
来源：http://dali.hfpthk.cn/Article/details/gtqgsfmcri.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.jianghu66.top/Article/details/gttwprivbg.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhiwuduotai.top/Article/details/gttiihysiv.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ehwqpu.com/Article/details/gtudzibwau.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtjklaxpee.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.meibo888.top/Article/details/gtlbxxzyfz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtihanqgdn.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gttnjfycyk.html

Go:   func add(a, b int) int
来源：http://dali.guannengcc.top/Article/details/gtztswqlat.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtrddczawm.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.zdqjudy.top/Article/details/gtpqizmbxy.html

[C14] 泛型函数
来源：http://dali.mhx1999.top/Article/details/gtgxxwxymn.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.havefunace.top/Article/details/gtxdkdsofb.html

PHP:  // 无泛型
来源：http://dali.tianlin.xyz/Article/details/gtdsummial.html

JS:   // 无泛型
来源：http://dali.jqgfzy.top/Article/details/gtmvcqgffx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.hnqzz.top/Article/details/gttgymivbn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yj20258888.top/Article/details/gtmsyuwiln.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.kuanghao11.cn/Article/details/gtyqzcqsyk.html

Ruby: # 无泛型
来源：http://dali.sxryk.cn/Article/details/gtwayujnyn.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xuetiantiany.cn/Article/details/gtmaefwtqw.html

[C15] 解构 / 展开参数
来源：http://dali.yj202588.top/Article/details/gtmarrpbyo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.cashguo.top/Article/details/gtyvfpuffh.html

PHP:  [$a, $b] = $pair;
来源：http://dali.ppjwa.cn/Article/details/gtpmugqlit.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.vqdsnc.cn/Article/details/gtavtanqzg.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.kuanghao11.cn/Article/details/gthysejqkr.html

Java: // 无解构
来源：http://dali.sxryk.cn/Article/details/gtdbrpkbya.html

Go:   // 无解构
来源：http://dali.mhx1999.top/Article/details/gtuvkldvxd.html

Ruby: a, b = pair
来源：http://dali.mhx1999.top/Article/details/gtaauvzuot.html

C#:   var (a, b) = pair;
来源：http://dali.redwolf501.top/Article/details/gtaeaywqhv.html

[C16] 函数 / 方法重载
来源：http://dali.xuetiantiany.cn/Article/details/gtaouojkgr.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.haohaochexian.top/Article/details/gtdgldrang.html

PHP:  // 无重载
来源：http://dali.sufxvd.cn/Article/details/gtsmaapwyt.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.xylfe.cn/Article/details/gtajpuicup.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.meibo888.top/Article/details/gthxvrcqhw.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.316326.xyz/Article/details/gtzuwhwtxp.html

Go:   // 无重载：用不同函数名
来源：http://dali.hnxiangtu.top/Article/details/gthqwavosw.html

Ruby: # 无重载：靠动态参数
来源：http://dali.daxiang520.top/Article/details/gtvhyukjfh.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.redwolf501.top/Article/details/gtekgtckol.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtajknhzhq.html

D. 数组 / 列表 / 集合
来源：http://dali.tanke756.top/Article/details/gttnkxsgrd.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtzrsfyfpa.html

[D01] 创建数组 / 列表
来源：http://dali.yuxming.cn/Article/details/gtcradyyfy.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.ehwqpu.com/Article/details/gtdktcvzmb.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtyqwhrpxy.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.xuanzx.com/Article/details/gtgipjdrfn.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnmhinrvy.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aizwys.cn/Article/details/gthjzzpyxx.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.dashuyun.cn/Article/details/gtgplqdrum.html

Ruby: arr = [1, 2, 3]
来源：http://dali.yangfankeji.com/Article/details/gtqqzjmbgs.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.sysykeji.top/Article/details/gtzjkrqfzx.html

[D02] 追加元素到末尾
来源：http://dali.sweek.top/Article/details/gtmeuzurvq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.snrcjt.cn/Article/details/gtbkmymhkj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.jiagoushi.top/Article/details/gtvodpafsc.html

JS:   arr.push(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjkdiuzb.html

TS:   arr.push(4);
来源：http://dali.shzxlz.cn/Article/details/gtjousqyfq.html

Java: list.add(4);
来源：http://dali.sufxvd.cn/Article/details/gtxvhlphav.html

Go:   arr = append(arr, 4)
来源：http://dali.svipenyu.cn/Article/details/gtrkstdifs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.guannengcc.top/Article/details/gthmazpoah.html

C#:   list.Add(4);
来源：http://dali.yangfankeji.com/Article/details/gtjkcawgzq.html

[D03] 在指定位置插入元素
来源：http://dali.tanke756.top/Article/details/gtiehrkiht.html

Py:   arr.insert(0, 0)
来源：http://dali.svipenyu.cn/Article/details/gtiedwpsfy.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.wangshuangyany.cn/Article/details/gttjwtbcbc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.0kj1m.cn/Article/details/gtiwwhxtzu.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ehwqpu.com/Article/details/gtrgcmwznd.html

Java: list.add(0, 0);
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmydafxj.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.cheryme.top/Article/details/gtmgrpqkix.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.shuidangran.top/Article/details/gtivimxubd.html

C#:   list.Insert(0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthcbljusp.html

[D04] 删除元素
来源：http://dali.sxryk.cn/Article/details/gtupxcxjay.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.smart0.xyz/Article/details/gtdpqtynuf.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.hysaishi.cn/Article/details/gtskudauto.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.sysykeji.top/Article/details/gtadrcudzq.html

TS:   arr.splice(0, 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtcpegtwij.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.dianchejie.cn/Article/details/gtupwuqpku.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.pengpengdd.cyou/Article/details/gtycemhfbn.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.gzhubu.top/Article/details/gtxykgdznr.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjiqgsbw.html

[D05] 访问与修改元素
来源：http://dali.aizwys.cn/Article/details/gtrxhjaqpg.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jyoumei.cn/Article/details/gtsmckgchu.html

PHP:  $arr[0]; end($arr); $arr[0] = 9;
来源：http://dali.cucudq.cn/Article/details/gttvmiujrd.html

JS:   arr[0]; arr.at(-1); arr[0] = 9;
来源：http://dali.bjfxy.top/Article/details/gtnctinmba.html

TS:   arr[0]; arr.at(-1);
来源：http://dali.9152youxi.cn/Article/details/gtesrkslfr.html

Java: list.get(0); list.set(0, 9);
来源：http://dali.yj202588.top/Article/details/gtwohisauy.html


<!-- 参考信息 -->