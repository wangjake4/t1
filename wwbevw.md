代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvjobfjt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.316326.xyz/Article/details/gtqlfcjvor.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtlsnxcvhb.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtkswokocz.html

Py:   for i in range(10): print(i)
来源：http://dali.jinqigufen.top/Article/details/gttisauhze.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwgvnqhg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtqoocqagx.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtkqufuylv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.smart0.xyz/Article/details/gtpenwzzne.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtossfrsmu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hnxiangtu.top/Article/details/gtubgkkqsr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ehwqpu.com/Article/details/gtswfmvlyj.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtbrvlbgvg.html

Py:   for item in arr: print(item)
来源：http://dali.wangdashe.top/Article/details/gtrsflvizr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guannengcc.top/Article/details/gtxmsqhxua.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtftviebuz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gthyngnxpb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gotoacloud.top/Article/details/gturkpxxqt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gtdholdemo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.sxryk.cn/Article/details/gtvrimttft.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.nanxinkj.top/Article/details/gthhothgrc.html

[B06] 遍历字典 / 对象
来源：http://dali.ybcxt.top/Article/details/gtgbnjskou.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gtctgtauxw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gtuxvhaaie.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtunexrtgx.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxqrxidyv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xylfe.cn/Article/details/gtoqclajil.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jqgufenzy.top/Article/details/gtscsixcbq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gtxviqbwtu.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guowangkeji.top/Article/details/gtvzgdsamv.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gtzaftinxp.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gttiykqcco.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtjyqtchmq.html

JS:   while (i < 10) { i++; }
来源：http://dali.redwolf501.top/Article/details/gtnoauuxwl.html

TS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gtaoyfavff.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gthtfwfbnc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.bjfxy.top/Article/details/gtdgjyllmt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhoulong.xyz/Article/details/gtctsoyfwr.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtbvhvhgds.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258888.top/Article/details/gtuyzzhgfq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovqvrtck.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.xziqi.cn/Article/details/gtphngyojv.html

JS:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gthnfxubzf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.cheryme.top/Article/details/gtdjouvwgs.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtwldobgic.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj202588.top/Article/details/gtzpikkcvj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnfxwoez.html

C#:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtjxsyovsw.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gttvzltire.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.sufxvd.cn/Article/details/gtaadsgyxq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtnqvvkvfp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtuztjxksg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yanxiufei.cn/Article/details/gtlscznhzp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtgunbjmuw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtgtamiovm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hongshengwenyu.top/Article/details/gtztkxbebn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtehirjsfn.html

[B10] 遍历同时拿索引
来源：http://dali.gotoacloud.top/Article/details/gtyuspnpxi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cqqwz.cn/Article/details/gtwweilrut.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.dianchejie.cn/Article/details/gtaiybmqaa.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jlsjyb.cn/Article/details/gtcnmwbsjf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yvedp.cn/Article/details/gtduqzebko.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtivqficbc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gtfbunuieo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtleoumpgq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gtamlnnfbr.html

[B11] 生成数字序列 / 区间
来源：http://dali.jqgfzy.top/Article/details/gtqjeojylx.html

Py:   list(range(0, 10, 2))
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvvdtfgbk.html

PHP:  range(0, 10, 2);
来源：http://dali.yueranfly.top/Article/details/gtfyefprgo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtgdevrupi.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtqqfdebje.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gttwjnzevf.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gzhubu.top/Article/details/gtrhvfmygc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhixingplan.top/Article/details/gttbngvsoi.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtcdtgcdpr.html

[B12] 跳出多层循环
来源：http://dali.xuetiantiany.cn/Article/details/gtkbcxonhb.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinghuilouyu.cn/Article/details/gtevsbinrs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gtrcvphssi.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtbndlbfti.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gtjoqwtpgq.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtsoweluij.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.aizwys.cn/Article/details/gtxdtpqwlo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258888.top/Article/details/gtvdtxruxb.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yvedp.cn/Article/details/gtxetfzpmb.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtfirzuyub.html

Py:   isinstance(x, (int, float))
来源：http://dali.xuanzx.com/Article/details/gtubkubrsr.html

PHP:  is_numeric($x)
来源：http://dali.hnqzz.top/Article/details/gtebogqght.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtgaxqfxwx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gtolnvufmw.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gtbgsaqtln.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhongyouzk.top/Article/details/gtzhedxxea.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gtwdctkqsz.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gttohamkzy.html

[B14] 判断值是否在集合内
来源：http://dali.gogol.net.cn/Article/details/gtzunpwqtf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtiwsycwsv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhoulong.xyz/Article/details/gtwujqmlok.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtnyvdvbax.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shuidangran.top/Article/details/gtrxewypfw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtevtjxkui.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gtopslhzkg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yvedp.cn/Article/details/gtvczjofgz.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.tianlin.xyz/Article/details/gtgxgipbrr.html

[B15] 布尔运算与取反
来源：http://dali.hongshengwenyu.top/Article/details/gtmfuhyxul.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gthfqzbzmq.html

PHP:  $a && $b || !$c
来源：http://dali.snrcjt.cn/Article/details/gtuctkuymi.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtjderysfl.html

TS:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtvqxajyhe.html

Java: a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtcppmpncs.html

Go:   a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtujkmvkqh.html

Ruby: a && b || !c
来源：http://dali.yj20258888.top/Article/details/gttxacieee.html

C#:   a && b || !c
来源：http://dali.hnxiangtu.top/Article/details/gtosmpojud.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbeyzyaoa.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gttvxmxzln.html

PHP:  if (!$data) { return; }
来源：http://dali.yj20258888.top/Article/details/gtqhyhqrel.html

JS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtflmpxuxc.html

TS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtvcyxckcj.html

Java: if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtqnuravet.html

Go:   if data == nil { return }
来源：http://dali.snrcjt.cn/Article/details/gtipztybgg.html

Ruby: return if data.nil?
来源：http://dali.jinghuilouyu.cn/Article/details/gtwxpoiqfu.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gthsmucygr.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtlutkesgm.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtqwiwfvfh.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gthtbxqiqp.html

[C01] 定义函数
来源：http://dali.hammf.cn/Article/details/gtwaiouzcg.html

Py:   def add(a, b): return a + b
来源：http://dali.gzhubu.top/Article/details/gtwydfsjba.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jyoumei.cn/Article/details/gtdnxlcaya.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtpdtcuvkj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqcrnfslx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gtrjejbhyv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtmkzxqhih.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgsbvlql.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj202588.top/Article/details/gtbdqdlhll.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtkwchodsk.html

Py:   def greet(name="World"): return name
来源：http://dali.fengsongda.top/Article/details/gtpufehjeb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhijiandao.cn/Article/details/gtckoryuub.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovpijwwm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hammf.cn/Article/details/gtufsjlbwa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrjkdwyn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtjcrqjukb.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtitpqjdih.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gotoacloud.top/Article/details/gtgjxbvyfe.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gtlvccmmif.html

Py:   def total(*args): return sum(args)
来源：http://dali.0kj1m.cn/Article/details/gtetqlxbaj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhongyouzk.top/Article/details/gtnikvcqmu.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtrezionja.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtsmrbsovn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtmvnuutqn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hnxiangtu.top/Article/details/gtzfkiydad.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sysykeji.top/Article/details/gtuuynpzyf.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.mhx1999.top/Article/details/gtlfsbidwi.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugqaqpwn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gtdagjnuuv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtqjndcrqj.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gttphkqtdh.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ppjwa.cn/Article/details/gtrqmhumjs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbxkdywv.html

Go:   // 无：用配置结构体参数
来源：http://dali.cqqwz.cn/Article/details/gtizllegra.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yj202588.top/Article/details/gtetztwzkd.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gtpjwpfdci.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtzcengsdb.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtmjwlzuya.html

PHP:  return [$a, $b];
来源：http://dali.aibaodan.cn/Article/details/gtwgauxzvb.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtkciqukcp.html

TS:   return { a, b };
来源：http://dali.ehwqpu.com/Article/details/gtbapnldak.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jiagoushi.top/Article/details/gtjuzctccs.html

Go:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtvhjytnzg.html

Ruby: return a, b
来源：http://dali.yangfankeji.com/Article/details/gtmvlvkvdj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gttegfiosy.html

[C06] 匿名函数 / lambda
来源：http://dali.yuanzhike.top/Article/details/gtjhaxsaxx.html

Py:   square = lambda x: x * x
来源：http://dali.fengsongda.top/Article/details/gtehkmfume.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tian-w.cn/Article/details/gtzbrtmgue.html

JS:   const square = x => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gttaqredim.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gtqjfkyyjh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtikxmatvu.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.wangshuangyany.cn/Article/details/gtjgsynyvf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtwaaqwgpk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtbmwzhcmm.html

[C07] 把函数作为参数传入
来源：http://dali.ybcxt.top/Article/details/gtlghvjeaf.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jyoumei.cn/Article/details/gtlkjgsqdf.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gtaksbbwgr.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jianghu66.top/Article/details/gtsraikwbi.html

TS:   arr.map(String)
来源：http://dali.hysaishi.cn/Article/details/gtrkmuyjgp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.9152youxi.cn/Article/details/gtnivcdhid.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.zycfv.cn/Article/details/gtiakavsyy.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtxapirvie.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.andypj.xyz/Article/details/gtrtamvnuw.html

[C08] 闭包
来源：http://dali.andypj.xyz/Article/details/gtmcflxgyz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenjidiqi.icu/Article/details/gtcddhtiqo.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigfzy.top/Article/details/gticvgatbj.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtlnkpzvaa.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtxefeohom.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxinkj.top/Article/details/gtwebgnfel.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guannengcc.top/Article/details/gtigyhtdui.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.smart0.xyz/Article/details/gtbcdyhxpx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtggzhvxwi.html

[C09] 递归
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcgdnmmbc.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gtwniphpxm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfoojppyj.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yanxiufei.cn/Article/details/gtgziuzeup.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtcfbxkcql.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.svipenyu.cn/Article/details/gtorufhutt.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.zycfv.cn/Article/details/gthytmwfej.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sxryk.cn/Article/details/gtzpkkgkqf.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gthwbsuykp.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gtxqpcnpld.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zhengqikj.top/Article/details/gtsigttuzq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.sysykeji.top/Article/details/gtdkzvjofz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtgehdkqku.html

TS:   同 JS
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoumvxbbp.html

Java: 方法内为块级作用域
来源：http://dali.guowangkeji.top/Article/details/gtupxostoi.html

Go:   花括号块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgscwjftr.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.zhijiandao.cn/Article/details/gtwmopgjna.html

C#:   块级作用域
来源：http://dali.jqgfzy.top/Article/details/gtqnkqxglq.html

[C11] 模块导入与导出
来源：http://dali.sxryk.cn/Article/details/gtishlvunx.html

Py:   from module import func
来源：http://dali.hnqzz.top/Article/details/gtqqnopyqy.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzoktcxp.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.hfpthk.cn/Article/details/gtnemnqjad.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gtfgtlbmbc.html

Java: import java.util.List;
来源：http://dali.feifeiyinyue.top/Article/details/gtwsbrarit.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gzhubu.top/Article/details/gtpshwqsuu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.yuanzhike.top/Article/details/gtdbooymkq.html

C#:   using System.Text;
来源：http://dali.ehwqpu.com/Article/details/gtrrfdaabg.html

[C12] 立即执行函数 IIFE
来源：http://dali.dianchejie.cn/Article/details/gtxmoxbjzm.html

Py:   (lambda: print("run"))()
来源：http://dali.ybcxt.top/Article/details/gtuadhfhoq.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ppjwa.cn/Article/details/gtutusrnpr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfsomzplu.html

TS:   (() => { console.log("run"); })();
来源：http://dali.svipenyu.cn/Article/details/gtznklgved.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.tanke756.top/Article/details/gtjlhhztlg.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yanxiufei.cn/Article/details/gtfgczbgzp.html

Ruby: -> { puts "run" }.call
来源：http://dali.xylfe.cn/Article/details/gtltmiyigu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tian-w.cn/Article/details/gtgsvixgrq.html

[C13] 类型声明 / 类型注解
来源：http://dali.gzhubu.top/Article/details/gtneqvqqhu.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtijmgaqmh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gtzcezyndt.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtrmwhuqdx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.aibaodan.cn/Article/details/gtnddayiab.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtyphyiegb.html

Go:   func add(a, b int) int
来源：http://dali.hfpthk.cn/Article/details/gtskbppqkb.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.sysykeji.top/Article/details/gtqvzvfjwb.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.nwbrower.top/Article/details/gtnxrggtcw.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtaopvmebw.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cqqwz.cn/Article/details/gtqbmxqgky.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gtfcvrnpyl.html

JS:   // 无泛型
来源：http://dali.guowangkeji.top/Article/details/gtmxzqpdtf.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.haohaochexian.top/Article/details/gtsggenpgp.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.guowangkeji.top/Article/details/gtrdibwcvi.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hywenlv.cn/Article/details/gtkpxsbrny.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gtvwcqbvfw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shangyingyoupin.top/Article/details/gtxstbcivf.html

[C15] 解构 / 展开参数
来源：http://dali.zhengqikj.top/Article/details/gtjdzpyzsq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yvedp.cn/Article/details/gtjmcxiybv.html

PHP:  [$a, $b] = $pair;
来源：http://dali.chenlongwang.top/Article/details/gtryxlyxaa.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.316326.xyz/Article/details/gtrdupasac.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtjcyvnoek.html

Java: // 无解构
来源：http://dali.dianchejie.cn/Article/details/gtkbzduwrt.html

Go:   // 无解构
来源：http://dali.jqgufenzy.top/Article/details/gtnhdqhhxi.html

Ruby: a, b = pair
来源：http://dali.gzhubu.top/Article/details/gthhnxbcom.html

C#:   var (a, b) = pair;
来源：http://dali.hongshengwenyu.top/Article/details/gtlidmftcm.html

[C16] 函数 / 方法重载
来源：http://dali.smart0.xyz/Article/details/gtoowjehhu.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.sufxvd.cn/Article/details/gtfupxqimy.html

PHP:  // 无重载
来源：http://dali.shzxlz.cn/Article/details/gtuaoeptcn.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.hongshengwenyu.top/Article/details/gtaryklkdi.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gogol.net.cn/Article/details/gtceeqcfhs.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.hnqzz.top/Article/details/gtovlayqmg.html

Go:   // 无重载：用不同函数名
来源：http://dali.hongshengwenyu.top/Article/details/gtzhrjjjbb.html

Ruby: # 无重载：靠动态参数
来源：http://dali.cdnleiting.top/Article/details/gtswglnuth.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.nanxuanxn.top/Article/details/gtnkwdzmxa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkzpbrcaj.html

D. 数组 / 列表 / 集合
来源：http://dali.yvedp.cn/Article/details/gtmzqsfggp.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtjbqtueav.html

[D01] 创建数组 / 列表
来源：http://dali.zhixingplan.top/Article/details/gtncdiwfkx.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.hnxiangtu.top/Article/details/gtjipubdgy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tanke756.top/Article/details/gtbavhsxkk.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jlsjyb.cn/Article/details/gtnztzaduu.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.xylfe.cn/Article/details/gtowawfcae.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.c1oappe.top/Article/details/gtkeyqglnt.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yangfankeji.com/Article/details/gthnfrepjd.html

Ruby: arr = [1, 2, 3]
来源：http://dali.xziqi.cn/Article/details/gtvljlzhcz.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.xuetiantiany.cn/Article/details/gtgjcrhocn.html

[D02] 追加元素到末尾
来源：http://dali.zhijiandao.cn/Article/details/gtfsjilots.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.cheryme.top/Article/details/gtuhktgbwn.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.nanxuanxn.top/Article/details/gtxxtyswmb.html

JS:   arr.push(4);
来源：http://dali.smart0.xyz/Article/details/gtnidegnpt.html

TS:   arr.push(4);
来源：http://dali.svipenyu.cn/Article/details/gtaqhropkn.html

Java: list.add(4);
来源：http://dali.andypj.xyz/Article/details/gtfpudrpac.html

Go:   arr = append(arr, 4)
来源：http://dali.fengsongda.top/Article/details/gtdldqlwzs.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.sweek.top/Article/details/gtgrnogmqv.html

C#:   list.Add(4);
来源：http://dali.quarkkingdee.top/Article/details/gtejeyyhth.html

[D03] 在指定位置插入元素
来源：http://dali.xylfe.cn/Article/details/gtjplcdwmu.html

Py:   arr.insert(0, 0)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyqwpbnlm.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.hongshengwenyu.top/Article/details/gtwymflust.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.jqgfzy.top/Article/details/gtzfavhmkb.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.ivvv.top/Article/details/gtgilwsrac.html

Java: list.add(0, 0);
来源：http://dali.iojbl.cn/Article/details/gtmcyhkyij.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.ivvv.top/Article/details/gtmbllqckv.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.fengsongda.top/Article/details/gtnrgvbmys.html

C#:   list.Insert(0, 0);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvzbisjl.html

[D04] 删除元素
来源：http://dali.tanke756.top/Article/details/gtxjpgrjqr.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.yuxming.cn/Article/details/gtxnwcrjgt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.ppjwa.cn/Article/details/gtlkuurfdc.html


<!-- 参考信息 -->