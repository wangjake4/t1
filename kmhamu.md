代发 wailian999

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.guannengcc.top/Article/details/gtqefdcwab.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yangfankeji.com/Article/details/gtgswpbgea.html

Ruby: 10.times { |i| puts i }
来源：http://dali.aibaodan.cn/Article/details/gtdjdurhqn.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.birdmap.top/Article/details/gtakostfuf.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gthabjxzig.html

Py:   for item in arr: print(item)
来源：http://dali.dianchejie.cn/Article/details/gtiwmdnqqu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtnieatcah.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hfpthk.cn/Article/details/gtezzuremz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yongpay.top/Article/details/gtpsbbmmgq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnzdsykg.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.snrcjt.cn/Article/details/gtnpbjwkgd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jiagoushi.top/Article/details/gtcfgvxczi.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ehwqpu.com/Article/details/gthddzhzyu.html

[B06] 遍历字典 / 对象
来源：http://dali.cheryme.top/Article/details/gtfgbytkhq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.haohaochexian.top/Article/details/gtycjflnug.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtbwisfbsg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtcbecvqhf.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtjaldhyir.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gtosrzcwpv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jlsjyb.cn/Article/details/gtlimobjbo.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.kuanghao11.cn/Article/details/gtpftmgiwr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tanke756.top/Article/details/gtyrdvhnuq.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gtghyubtfw.html

Py:   while i < 10: i += 1
来源：http://dali.havefunace.top/Article/details/gtopdfwgho.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fzhhl.top/Article/details/gtvijjujja.html

JS:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtuhgsdlto.html

TS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gticnwdlgl.html

Java: while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtrpjcyoai.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gtccixrwhb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhixingplan.top/Article/details/gtfrscrtto.html

C#:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtiuzelxja.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gtxtjldhrs.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hfpthk.cn/Article/details/gtyilsjacs.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtkixjvfna.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtsqvpwnlx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtaboacnjx.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgydomfb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtinfdpkcz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmhcrrpvu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtrgfjjbhc.html

[B09] break 与 continue
来源：http://dali.sxryk.cn/Article/details/gtzlnarmhz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gtfivsrmru.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtgcpngqpq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtieiwfvat.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxlmsuzxd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sxryk.cn/Article/details/gtpcbbvrmy.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxvyncky.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sufxvd.cn/Article/details/gtocowhitz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtrzvaeulz.html

[B10] 遍历同时拿索引
来源：http://dali.wangdashe.top/Article/details/gtgszzvjuo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.meibo888.top/Article/details/gtyrzvkoge.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cucudq.cn/Article/details/gtlhdkrkat.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.smart0.xyz/Article/details/gthhdpwqhb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.redwolf501.top/Article/details/gtynbvlhfv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gtghrdjbbm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258888.top/Article/details/gtvyzpvjka.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtihgswozp.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zycfv.cn/Article/details/gtrfdtfayv.html

[B11] 生成数字序列 / 区间
来源：http://dali.guannengcc.top/Article/details/gtpminxgxh.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhixingplan.top/Article/details/gtcnejjiqe.html

PHP:  range(0, 10, 2);
来源：http://dali.svipenyu.cn/Article/details/gthlbnwnfi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yueranfly.top/Article/details/gtxlnrzuuj.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngrzifem.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shuidangran.top/Article/details/gtkyluvsqn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.pycfn.com/Article/details/gtxqpnmftf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yongpay.top/Article/details/gtgzvofsbr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.guowangkeji.top/Article/details/gtydywfziy.html

[B12] 跳出多层循环
来源：http://dali.sufxvd.cn/Article/details/gtjcgxjcat.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gtgmkfuroo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gtexlrntmf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gtikvcyfxs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ehwqpu.com/Article/details/gtuopwwrsl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yangfankeji.com/Article/details/gtnesqquax.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gtyfndhfjj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.chenjidiqi.icu/Article/details/gtfsznyewc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zdqjudy.top/Article/details/gtzkosdijq.html

[B13] 判断是否为数字
来源：http://dali.hongshengwenyu.top/Article/details/gtuletueim.html

Py:   isinstance(x, (int, float))
来源：http://dali.xylfe.cn/Article/details/gtsqvcvnzy.html

PHP:  is_numeric($x)
来源：http://dali.quarkkingdee.top/Article/details/gtktlwkvvb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gtofkezrpj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtbtfxnkzo.html

Java: x instanceof Number
来源：http://dali.mhx1999.top/Article/details/gtxnzzqvjt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgxaeguij.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtwospbcsz.html

C#:   x is int or double or decimal
来源：http://dali.yangfankeji.com/Article/details/gtxeqtbdxu.html

[B14] 判断值是否在集合内
来源：http://dali.cashguo.top/Article/details/gtpcufslpt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtudgnrqni.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.shuidangran.top/Article/details/gtvlgdsntm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtbufnbarh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevjkgrvs.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.snrcjt.cn/Article/details/gtkzyeiwai.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.pycfn.com/Article/details/gtpnexiyjl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.smart0.xyz/Article/details/gtxhdnzzeb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.haohaochexian.top/Article/details/gtvegjygag.html

[B15] 布尔运算与取反
来源：http://dali.jianghu66.top/Article/details/gtmgdpmefw.html

Py:   a and b or not c
来源：http://dali.xuanzx.com/Article/details/gtxfouxmwc.html

PHP:  $a && $b || !$c
来源：http://dali.ybcxt.top/Article/details/gtifikzsrx.html

JS:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtxaslcbdx.html

TS:   a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtlnpoqgga.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtxkoygyvh.html

Go:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtgtyqgoah.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gtpwmpwcrx.html

C#:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxcowxtjr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtjlbwtyfo.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtuzurblce.html

PHP:  if (!$data) { return; }
来源：http://dali.snrcjt.cn/Article/details/gtzvvzxupo.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gthabudsrd.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtfkwpjuro.html

Java: if (data == null) return;
来源：http://dali.hammf.cn/Article/details/gtmfpvowvh.html

Go:   if data == nil { return }
来源：http://dali.dashuyun.cn/Article/details/gtencvguso.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangtech.top/Article/details/gtnueankbd.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtaenqjrzp.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtbnnwvagp.html

C. 函数与作用域
来源：http://dali.ivvv.top/Article/details/gtzebtxqlr.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtlotfkzad.html

[C01] 定义函数
来源：http://dali.ehwqpu.com/Article/details/gtyozuugkp.html

Py:   def add(a, b): return a + b
来源：http://dali.zhoulong.xyz/Article/details/gttpxvgjdq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtaucmmuqk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtrldfdrvz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtchdtacow.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtflptnknu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgufenzy.top/Article/details/gtrftprerv.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gtikzfdxkq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gteyvfysog.html

[C02] 默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtxoxswqdw.html

Py:   def greet(name="World"): return name
来源：http://dali.quarkkingdee.top/Article/details/gtrhdxgqlo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtojlffymq.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtkjaelcvz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj20258888.top/Article/details/gtvbgtneeh.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtrffuicsn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cdnleiting.top/Article/details/gtsgpntnqx.html

Ruby: def greet(name = "World") = name
来源：http://dali.xylfe.cn/Article/details/gtdprjapyj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yonumen.top/Article/details/gttxgkubmi.html

[C03] 可变参数
来源：http://dali.guannengcc.top/Article/details/gtigscgqas.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gtsasftgky.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtdpmolcgw.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.smart0.xyz/Article/details/gtcxhdimos.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtxidpxoot.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jlsjyb.cn/Article/details/gtxtjxxgng.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj202588.top/Article/details/gtczqrjyts.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtncrtcgxg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jlsjyb.cn/Article/details/gtiyrjqxlp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hywenlv.cn/Article/details/gteoeogmnz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shangyingyoupin.top/Article/details/gtescoxcyj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zycfv.cn/Article/details/gtvcpebkoq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtisvpbxdj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hnxiangtu.top/Article/details/gtgnuxvrri.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.andypj.xyz/Article/details/gtbpzcodjv.html

Go:   // 无：用配置结构体参数
来源：http://dali.havefunace.top/Article/details/gtcfdquouq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmukfwoxj.html

C#:   f(a: 1, b: 2)
来源：http://dali.pengpengdd.cyou/Article/details/gtfsrladyy.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtxuutliyc.html

Py:   return a, b
来源：http://dali.wangdashe.top/Article/details/gttncqxnti.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gtiapaxqyx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuxming.cn/Article/details/gtivxuamwn.html

TS:   return { a, b };
来源：http://dali.zhengqikj.top/Article/details/gtwtgvsiyr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sxryk.cn/Article/details/gtqycstkfc.html

Go:   return a, b
来源：http://dali.zycfv.cn/Article/details/gtaojmllwn.html

Ruby: return a, b
来源：http://dali.ybcxt.top/Article/details/gtqedhixee.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shangyingyoupin.top/Article/details/gtpsuzyuti.html

[C06] 匿名函数 / lambda
来源：http://dali.sxryk.cn/Article/details/gtittbszto.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtorfbpjcq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gtomnyetpd.html

JS:   const square = x => x * x;
来源：http://dali.hnxiangtu.top/Article/details/gttwlxmbaj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yj202588.top/Article/details/gtlfnbrgdo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aizwys.cn/Article/details/gtodabcity.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gtdngffivi.html

Ruby: square = ->(x) { x * x }
来源：http://dali.c1oappe.top/Article/details/gttxsfrkhs.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gthzyqrgde.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxiestucj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xylfe.cn/Article/details/gtwiawregf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.aibaodan.cn/Article/details/gtlzvpnqwj.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hywenlv.cn/Article/details/gtlrlmnbix.html

TS:   arr.map(String)
来源：http://dali.kuanghao11.cn/Article/details/gtmoiefkaz.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hongshengwenyu.top/Article/details/gtrqhotplb.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.316326.xyz/Article/details/gtcuvzpwnn.html

Ruby: arr.map(&:upcase)
来源：http://dali.gaohongyu789.top/Article/details/gtqhafleqh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtwxpyftwb.html

[C08] 闭包
来源：http://dali.fengsongda.top/Article/details/gtizdycvam.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtmndbketl.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuyngwypj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gthehqajcf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtuarndqhi.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtvnswjxtv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.jyoumei.cn/Article/details/gtgsrjbxxp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yongpay.top/Article/details/gtjpjkcfkb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtbreqbxaa.html

[C09] 递归
来源：http://dali.jlsjyb.cn/Article/details/gtacpxqhbr.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.tanke756.top/Article/details/gtllclqoan.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.cqqwz.cn/Article/details/gtjooiatsm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gtwwqjosgc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtueacebvv.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.xylfe.cn/Article/details/gtzvekgwgv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zhongyouzk.top/Article/details/gtcvzlnxco.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hnqzz.top/Article/details/gtbkwkihrx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.sxryk.cn/Article/details/gtlnrsvgub.html

[C10] 变量作用域
来源：http://dali.zdqjudy.top/Article/details/gtrhzqicpd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhijiandao.cn/Article/details/gtdgxnytxr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.snrcjt.cn/Article/details/gtttnuiatm.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqvagmqxp.html

TS:   同 JS
来源：http://dali.xuetiantiany.cn/Article/details/gtxxrrjsxt.html

Java: 方法内为块级作用域
来源：http://dali.zdqjudy.top/Article/details/gtgqvibmnp.html

Go:   花括号块级作用域
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdwtqtymb.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhiwuduotai.top/Article/details/gthbxyaych.html

C#:   块级作用域
来源：http://dali.cdnleiting.top/Article/details/gtljlqztsg.html

[C11] 模块导入与导出
来源：http://dali.zhengqikj.top/Article/details/gtjlfcpdtr.html

Py:   from module import func
来源：http://dali.guannengcc.top/Article/details/gtdiehhujm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jianghu66.top/Article/details/gtixctdius.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.daxiang520.top/Article/details/gtxyyzrgmk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbawbpaki.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gtxjhipabp.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cashguo.top/Article/details/gtimiihtxi.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuxming.cn/Article/details/gtfwnhppeu.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gtmbwkwhnf.html

[C12] 立即执行函数 IIFE
来源：http://dali.gaohongyu789.top/Article/details/gtbcjlalna.html

Py:   (lambda: print("run"))()
来源：http://dali.iojbl.cn/Article/details/gttndjilqn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.andypj.xyz/Article/details/gtfehpqwcn.html

JS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gtykkkosnp.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zhijiandao.cn/Article/details/gtvctghvum.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gtoreudhlo.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jinghuilouyu.cn/Article/details/gtkopjgxqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuggtfuuo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.vqdsnc.cn/Article/details/gtpbulknof.html

[C13] 类型声明 / 类型注解
来源：http://dali.daxiang520.top/Article/details/gtbxyhcdcy.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.feifeiyinyue.top/Article/details/gtrndcurzi.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yonumen.top/Article/details/gtldsivslc.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.pengpengdd.cyou/Article/details/gtqaqmmhks.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtjzsysycc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtxsdfvzdz.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtkxrxukbc.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.smart0.xyz/Article/details/gtcwtpiodt.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthslmytok.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gtfvzvpesi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.mhx1999.top/Article/details/gtrxshhzie.html

PHP:  // 无泛型
来源：http://dali.feifeiyinyue.top/Article/details/gtyuymttib.html

JS:   // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gtdnpyxzia.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.fzhhl.top/Article/details/gtpmmrgdmw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pycfn.com/Article/details/gtdfkdvrzd.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.xziqi.cn/Article/details/gtxfwczstf.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtdoypixrp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gtaamanuem.html

[C15] 解构 / 展开参数
来源：http://dali.xinyue.icu/Article/details/gtcqwlmfgh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.shangyingyoupin.top/Article/details/gtidlnbthp.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbrpryxf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.gotoacloud.top/Article/details/gtxezjgncu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jlsjyb.cn/Article/details/gthqwqpbbo.html

Java: // 无解构
来源：http://dali.jinqigfzy.top/Article/details/gtrdzhfvgb.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gtqrxbzqgo.html

Ruby: a, b = pair
来源：http://dali.haohaochexian.top/Article/details/gtyqnhxxuy.html

C#:   var (a, b) = pair;
来源：http://dali.zhengqikj.top/Article/details/gtgjebjlpe.html

[C16] 函数 / 方法重载
来源：http://dali.ivvv.top/Article/details/gtzvjwjwbm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.cqqwz.cn/Article/details/gtoxatgssx.html

PHP:  // 无重载
来源：http://dali.chenlongwang.top/Article/details/gtdjaykwyg.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.smart0.xyz/Article/details/gtjnnzpdzu.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.kuanghao11.cn/Article/details/gtgpwtvgse.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.fzhhl.top/Article/details/gtixdoasmd.html

Go:   // 无重载：用不同函数名
来源：http://dali.c1oappe.top/Article/details/gtcvoduvvj.html

Ruby: # 无重载：靠动态参数
来源：http://dali.shuidangran.top/Article/details/gtazpnagtg.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.pycfn.com/Article/details/gtdvwcvfum.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrtgusmxk.html

D. 数组 / 列表 / 集合
来源：http://dali.quarkkingdee.top/Article/details/gtalsjpwxm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtnjbniuxl.html

[D01] 创建数组 / 列表
来源：http://dali.0kj1m.cn/Article/details/gthvemgsyt.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.jinghuilouyu.cn/Article/details/gtaouwcceq.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.pycfn.com/Article/details/gtpobbupfz.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.sysykeji.top/Article/details/gtpldlgykw.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.nwbrower.top/Article/details/gtaajyqrsu.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.aibaodan.cn/Article/details/gtloqeuvgy.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.feifeiyinyue.top/Article/details/gtogofmkzh.html

Ruby: arr = [1, 2, 3]
来源：http://dali.daria6918.cn/Article/details/gtckcrisnb.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.yuanzhike.top/Article/details/gtjpefrvgq.html

[D02] 追加元素到末尾
来源：http://dali.ybcxt.top/Article/details/gtjlssjmhj.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cqqwz.cn/Article/details/gthywramuc.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhiwuduotai.top/Article/details/gtkocvokaf.html

JS:   arr.push(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlemztnnk.html

TS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtklfbdgrq.html

Java: list.add(4);
来源：http://dali.zhengqikj.top/Article/details/gtrzcrtfeb.html

Go:   arr = append(arr, 4)
来源：http://dali.gzhubu.top/Article/details/gtsjnhzbbl.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.xziqi.cn/Article/details/gtkfspblsb.html

C#:   list.Add(4);
来源：http://dali.zhengqikj.top/Article/details/gtmvehckhc.html

[D03] 在指定位置插入元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkamuvbv.html

Py:   arr.insert(0, 0)
来源：http://dali.316326.xyz/Article/details/gtmwmwkfou.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.yanxiufei.cn/Article/details/gtdokqkjkc.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.haohaochexian.top/Article/details/gtqflydrek.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpavadxiv.html

Java: list.add(0, 0);
来源：http://dali.gzhubu.top/Article/details/gtxsokqvbk.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.yuanzhike.top/Article/details/gtahcvmaai.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkhqozkj.html

C#:   list.Insert(0, 0);
来源：http://dali.9152youxi.cn/Article/details/gtlxcwbtbp.html

[D04] 删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtuzktovvh.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.zhixingplan.top/Article/details/gtpzyrzhvj.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.dianchejie.cn/Article/details/gthuggqlmr.html

JS:   arr.splice(0, 1); arr.pop(); arr.shift();
来源：http://dali.xylfe.cn/Article/details/gtymhjuhnq.html

TS:   arr.splice(0, 1);
来源：http://dali.dashuyun.cn/Article/details/gtvpaedukn.html

Java: list.remove(0); list.removeIf(x -> x == 3);
来源：http://dali.wangdashe.top/Article/details/gtwupslqlf.html

Go:   arr = append(arr[:0], arr[1:]...)
来源：http://dali.0kj1m.cn/Article/details/gtntouobzj.html

Ruby: arr.delete_at(0); arr.delete(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtmavabavh.html

C#:   list.RemoveAt(0); list.Remove(3);
来源：http://dali.guannengcc.top/Article/details/gtvlcgwyya.html

[D05] 访问与修改元素
来源：http://dali.chenlongwang.top/Article/details/gtbjnshxoi.html

Py:   arr[0]; arr[-1]; arr[0] = 9
来源：http://dali.jqgfzy.top/Article/details/gtatpskgrj.html


<!-- 参考信息 -->