代发 wailian999

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xziqi.cn/Article/details/gtzowgqzqn.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fzhhl.top/Article/details/gtvhggaufp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtfrskwqwy.html

[B04] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtujeecell.html

Py:   for i in range(10): print(i)
来源：http://dali.aizwys.cn/Article/details/gttczcksmj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.feifeiyinyue.top/Article/details/gtitgcbvud.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cqqwz.cn/Article/details/gtlbipwoha.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.redwolf501.top/Article/details/gtwfdfrlwy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jiagoushi.top/Article/details/gtdfxavfwu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangshuangyany.cn/Article/details/gtyntolhlu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.tianlin.xyz/Article/details/gtdcbzovgi.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gttnblqolu.html

[B05] 遍历数组 / 列表
来源：http://dali.daria6918.cn/Article/details/gtiijteetq.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtzdackhjb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hfpthk.cn/Article/details/gtwbsdfoit.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gttbgjajsz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.dianchejie.cn/Article/details/gtomcqavvi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hysaishi.cn/Article/details/gtsyhyyefl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gtzknjvhdb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.vqdsnc.cn/Article/details/gtrjkimqqp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shuidangran.top/Article/details/gthlujnghz.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtdbqunhaz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtuancjqjm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtppyutvxp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtebytfidv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxinkj.top/Article/details/gtpwhxfehe.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvshzigkn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sysykeji.top/Article/details/gtqagulefn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hywenlv.cn/Article/details/gtgsxymnyb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ybcxt.top/Article/details/gtthpwooec.html

[B07] while 循环
来源：http://dali.daria6918.cn/Article/details/gtpdnxozgj.html

Py:   while i < 10: i += 1
来源：http://dali.sysykeji.top/Article/details/gtjmguywhp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.daxiang520.top/Article/details/gtgbbxstov.html

JS:   while (i < 10) { i++; }
来源：http://dali.feifeiyinyue.top/Article/details/gtpzqpjngg.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gtzjzhaxjm.html

Java: while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtobgkavsx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hywenlv.cn/Article/details/gtisncyumh.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jqgfzy.top/Article/details/gtujnisuve.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtmefhftuj.html

[B08] do-while（至少执行一次）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqetfjzuo.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gtxvxgawqa.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yueranfly.top/Article/details/gtbaolkzxe.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtrvapbbme.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gogol.net.cn/Article/details/gtggnnauta.html

Java: do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtiurjxupv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.316326.xyz/Article/details/gtfytlqwtx.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.tian-w.cn/Article/details/gtzmwfafvs.html

C#:   do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gtboicmtmw.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtqpabebml.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ydzc1.top/Article/details/gthklkbgol.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtzewbxkst.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtysicruhp.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtuczqdika.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmgcbwdb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.gzhubu.top/Article/details/gtkvgqbzrs.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtmqukcthu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtbuytlbym.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtqpbufayp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.bjfxy.top/Article/details/gtwpiruxjb.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtktzrrzsz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jyoumei.cn/Article/details/gtvxfpwsae.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtgiojwwhy.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xylfe.cn/Article/details/gtwebnncpg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtyxlumelq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnxiangtu.top/Article/details/gtdmchjcal.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.sxryk.cn/Article/details/gthlzbgnoz.html

[B11] 生成数字序列 / 区间
来源：http://dali.xylfe.cn/Article/details/gtdxcqktlk.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gteujpiblc.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gttytmrqpg.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gtmzlzbicz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guowangkeji.top/Article/details/gtcbjnttcm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jinqigufen.top/Article/details/gtpbyvmaol.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.bjfxy.top/Article/details/gtqgxnrcvf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.andypj.xyz/Article/details/gtjkgiwpzk.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jiagoushi.top/Article/details/gtcjzzmmkt.html

[B12] 跳出多层循环
来源：http://dali.jqgfzy.top/Article/details/gtuzbsodkl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtolvzzqdg.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.shzxlz.cn/Article/details/gthjqttuui.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cucudq.cn/Article/details/gtvaxgzqvc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtuiiprtfo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitjomscq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ppjwa.cn/Article/details/gtmdhgtpxu.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fzhhl.top/Article/details/gtsezuaifi.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hfpthk.cn/Article/details/gtdiqbiklp.html

[B13] 判断是否为数字
来源：http://dali.jianghu66.top/Article/details/gtrzczohzu.html

Py:   isinstance(x, (int, float))
来源：http://dali.kuanghao11.cn/Article/details/gthzdakyur.html

PHP:  is_numeric($x)
来源：http://dali.shzxlz.cn/Article/details/gtnbnngbrs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtdtmothgv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yongpay.top/Article/details/gtsuttmoep.html

Java: x instanceof Number
来源：http://dali.tanke756.top/Article/details/gtfuqwncna.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.pycfn.com/Article/details/gtzhajgigm.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daxiang520.top/Article/details/gtwkgyfpup.html

C#:   x is int or double or decimal
来源：http://dali.jinghuilouyu.cn/Article/details/gtgagnvjss.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtgokwfetp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shuidangran.top/Article/details/gtcwizvxxc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.kuanghao11.cn/Article/details/gtaqteyfyh.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gturujycdj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.dianchejie.cn/Article/details/gtrjwcjvia.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.sweek.top/Article/details/gtobiwyxcs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtkgqiabxg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daxiang520.top/Article/details/gtzyrompfn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.redwolf501.top/Article/details/gtgokuzjuf.html

[B15] 布尔运算与取反
来源：http://dali.jinqigfzy.top/Article/details/gtnaxzmnhk.html

Py:   a and b or not c
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzwpdcfi.html

PHP:  $a && $b || !$c
来源：http://dali.bjfxy.top/Article/details/gtujmhvsef.html

JS:   a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gtpmbltkxr.html

TS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtnvvyqgrf.html

Java: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtxmptingg.html

Go:   a && b || !c
来源：http://dali.316326.xyz/Article/details/gtixgzaaar.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gthiyoxnnm.html

C#:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gttkwpjcov.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.gogol.net.cn/Article/details/gtmznpsrdz.html

Py:   if not data: return
来源：http://dali.xylfe.cn/Article/details/gtdgflksqc.html

PHP:  if (!$data) { return; }
来源：http://dali.jinqigfzy.top/Article/details/gtfxkouyhg.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtpokfbqkx.html

TS:   if (!data) return;
来源：http://dali.snrcjt.cn/Article/details/gtcyqmprkq.html

Java: if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gtrmlkcrql.html

Go:   if data == nil { return }
来源：http://dali.yanxiufei.cn/Article/details/gtdyjcmbvq.html

Ruby: return if data.nil?
来源：http://dali.pengpengdd.cyou/Article/details/gtceofaire.html

C#:   if (data == null) return;
来源：http://dali.nanxuanxn.top/Article/details/gthxdzoxrt.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtxdesckdv.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gthdbifzun.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgwgoyni.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gtrcligxzh.html

Py:   def add(a, b): return a + b
来源：http://dali.gotoacloud.top/Article/details/gtfikstyza.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gteuxepnyc.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtywidvdkm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtubpdjxlx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtbdidpdgl.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.wangdashe.top/Article/details/gtsfdfcjyf.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gtamqdklnp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtslovvmxe.html

[C02] 默认参数
来源：http://dali.zhixingplan.top/Article/details/gtjbaglndy.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtpqexagmo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xziqi.cn/Article/details/gtlgnzuzwa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthludxmwm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtitdrcidm.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.fzhhl.top/Article/details/gtbvqebphc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.wangshuangyany.cn/Article/details/gtvoorxpry.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtdrzgbocs.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.haohaochexian.top/Article/details/gtsysxzztd.html

[C03] 可变参数
来源：http://dali.zhongyouzk.top/Article/details/gtevvlnrje.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gtebrtpkaj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.birdmap.top/Article/details/gtoywxyfqx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.0kj1m.cn/Article/details/gtrsywulxs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtmqgcteyw.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkmbdvqzb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtyykhasxy.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gtosuurdqj.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gtnffyymmp.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nwbrower.top/Article/details/gtuasetrpg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhoulong.xyz/Article/details/gthirtzvap.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtpdcejlhb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtamlojdqy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jqgufenzy.top/Article/details/gtmclsmzpr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.cheryme.top/Article/details/gtwczgzkyr.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtwpdmamdv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yangfankeji.com/Article/details/gtzarpznjs.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnqzz.top/Article/details/gtajnzkrlm.html

[C05] 返回多个值
来源：http://dali.iojbl.cn/Article/details/gtovgslpso.html

Py:   return a, b
来源：http://dali.pycfn.com/Article/details/gtyrozlzee.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtycwsaajg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtpjlysivq.html

TS:   return { a, b };
来源：http://dali.yongpay.top/Article/details/gtjtnxbhjt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.mhx1999.top/Article/details/gtfxwphlwm.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gtbirjoddx.html

Ruby: return a, b
来源：http://dali.yj20258888.top/Article/details/gtzcstpsxi.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yanxiufei.cn/Article/details/gtojunavoa.html

[C06] 匿名函数 / lambda
来源：http://dali.bjfxy.top/Article/details/gtaqcqxeyd.html

Py:   square = lambda x: x * x
来源：http://dali.haohaochexian.top/Article/details/gtfzppzezd.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhiwuduotai.top/Article/details/gthqlzfbwc.html

JS:   const square = x => x * x;
来源：http://dali.andypj.xyz/Article/details/gtgyrieurx.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.shzxlz.cn/Article/details/gteiqjrokt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yangfankeji.com/Article/details/gtolsrqqcr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvvyitom.html

Ruby: square = ->(x) { x * x }
来源：http://dali.feifeiyinyue.top/Article/details/gtgoxzyyga.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtqaoczcsw.html

[C07] 把函数作为参数传入
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyuzxpptm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xinyue.icu/Article/details/gtuuuawfho.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xuetiantiany.cn/Article/details/gtyxgohlea.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.xylfe.cn/Article/details/gthquklpxb.html

TS:   arr.map(String)
来源：http://dali.snrcjt.cn/Article/details/gtlylxciho.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jinghuilouyu.cn/Article/details/gtmsvqgmgj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtgeqhczik.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gtlcbykoaw.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jiagoushi.top/Article/details/gtuhyavwlm.html

[C08] 闭包
来源：http://dali.yuanzhike.top/Article/details/gtgbetlayq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.nanxinkj.top/Article/details/gtwmroigmf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.sxryk.cn/Article/details/gtwxvwfgep.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtbdreswxo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhongyouzk.top/Article/details/gtwazsymet.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sxryk.cn/Article/details/gttmobcsyn.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gtomcjazve.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhixingplan.top/Article/details/gtcginuxhy.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtilnhyqjh.html

[C09] 递归
来源：http://dali.gzhubu.top/Article/details/gtgwknxqul.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.yonumen.top/Article/details/gthvukjqzh.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gtxwovxwtc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cucudq.cn/Article/details/gtwbbifxil.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.cdnleiting.top/Article/details/gtygmuzhyf.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jianghu66.top/Article/details/gtaeqnwlwe.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtkbwgfagj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtjmunkfnc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.chenlongwang.top/Article/details/gtiodrbqlt.html

[C10] 变量作用域
来源：http://dali.ppjwa.cn/Article/details/gtzgwdsbtf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guannengcc.top/Article/details/gtrelcgimm.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.jinqigufen.top/Article/details/gtwezeahov.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.fengsongda.top/Article/details/gtckpttzpc.html

TS:   同 JS
来源：http://dali.daxiang520.top/Article/details/gthzixbhke.html

Java: 方法内为块级作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtpvlnvdsp.html

Go:   花括号块级作用域
来源：http://dali.hnxiangtu.top/Article/details/gtobvrxhwh.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.shangyingyoupin.top/Article/details/gtiwvjlkbz.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gtknyzqogh.html

[C11] 模块导入与导出
来源：http://dali.hammf.cn/Article/details/gtsyrqbhgo.html

Py:   from module import func
来源：http://dali.xuetiantiany.cn/Article/details/gtiedkvwdf.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shanyushiyangtech.top/Article/details/gtrztzxihv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.sxryk.cn/Article/details/gtorlpzatd.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.nwbrower.top/Article/details/gtvroowfic.html

Java: import java.util.List;
来源：http://dali.xinyue.icu/Article/details/gtuaxdrjhk.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.vqdsnc.cn/Article/details/gtsvzcsqsx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.9152youxi.cn/Article/details/gtlolwmmnx.html

C#:   using System.Text;
来源：http://dali.quarkkingdee.top/Article/details/gtairnbfyw.html

[C12] 立即执行函数 IIFE
来源：http://dali.hysaishi.cn/Article/details/gtnmzskeer.html

Py:   (lambda: print("run"))()
来源：http://dali.xziqi.cn/Article/details/gtouqbzeax.html

PHP:  (function () { echo "run"; })();
来源：http://dali.sweek.top/Article/details/gtnqmrvujr.html

JS:   (() => { console.log("run"); })();
来源：http://dali.gzhubu.top/Article/details/gtmpthziys.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gtkwoqkowv.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.zhixingplan.top/Article/details/gtmozimnxi.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.tanke756.top/Article/details/gthdbobawt.html

Ruby: -> { puts "run" }.call
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuuddtlr.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.tanke756.top/Article/details/gtxvmzumeb.html

[C13] 类型声明 / 类型注解
来源：http://dali.gaohongyu789.top/Article/details/gtrahfvxrf.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.zhongyouzk.top/Article/details/gtiyvauqjp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.guannengcc.top/Article/details/gthhvmcpxg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.tian-w.cn/Article/details/gtkqvtdkfk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtsiliwtsm.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtftnokehf.html

Go:   func add(a, b int) int
来源：http://dali.xylfe.cn/Article/details/gtvbhzlycu.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yanxiufei.cn/Article/details/gtsunvscge.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jinghuilouyu.cn/Article/details/gtdsrtpydv.html

[C14] 泛型函数
来源：http://dali.9152youxi.cn/Article/details/gtmjamkiqy.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.zycfv.cn/Article/details/gtzaqhymui.html

PHP:  // 无泛型
来源：http://dali.yvedp.cn/Article/details/gtoqnususa.html

JS:   // 无泛型
来源：http://dali.xziqi.cn/Article/details/gtiqcafdwv.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.chenlongwang.top/Article/details/gtzjgimdwb.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.yueranfly.top/Article/details/gtzldbwkiv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.zhiwuduotai.top/Article/details/gtsfyacvlc.html

Ruby: # 无泛型
来源：http://dali.chenlongwang.top/Article/details/gtksbavxzz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.jlsjyb.cn/Article/details/gtobwrmane.html

[C15] 解构 / 展开参数
来源：http://dali.cdnleiting.top/Article/details/gthdlvvwoj.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.jqgufenzy.top/Article/details/gtluegiibq.html

PHP:  [$a, $b] = $pair;
来源：http://dali.dianchejie.cn/Article/details/gtdkjdowvq.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.dashuyun.cn/Article/details/gtgaxhvwyq.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.haohaochexian.top/Article/details/gtdygoljtg.html

Java: // 无解构
来源：http://dali.jiagoushi.top/Article/details/gtiqydsmyu.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtihgtnikb.html

Ruby: a, b = pair
来源：http://dali.yueranfly.top/Article/details/gtqfzmjzdf.html

C#:   var (a, b) = pair;
来源：http://dali.kuanghao11.cn/Article/details/gtkvcloouh.html

[C16] 函数 / 方法重载
来源：http://dali.shzxlz.cn/Article/details/gtcualcnwp.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.zhongyouzk.top/Article/details/gtyqywaaxv.html

PHP:  // 无重载
来源：http://dali.fzhhl.top/Article/details/gtigfjqxae.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.chenlongwang.top/Article/details/gtftyujnwq.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.yuanzhike.top/Article/details/gtblzbaxzu.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.shangyingyoupin.top/Article/details/gteglbasoq.html

Go:   // 无重载：用不同函数名
来源：http://dali.daxiang520.top/Article/details/gtiukcfuqm.html

Ruby: # 无重载：靠动态参数
来源：http://dali.zhengqikj.top/Article/details/gtjiyhywad.html

C#:   void F(int a) {}  void F(string a) {}
来源：http://dali.ybcxt.top/Article/details/gtgzlotsms.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtkmnqmmpu.html

D. 数组 / 列表 / 集合
来源：http://dali.9152youxi.cn/Article/details/gtwdxkmrjx.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlukqovyw.html

[D01] 创建数组 / 列表
来源：http://dali.mhx1999.top/Article/details/gtxzduchke.html

Py:   arr = [1, 2, 3];  empty = []
来源：http://dali.cashguo.top/Article/details/gtlpughbiy.html

PHP:  $arr = [1, 2, 3];  $empty = [];
来源：http://dali.tian-w.cn/Article/details/gtuzqwllbu.html

JS:   const arr = [1, 2, 3];  const empty = [];
来源：http://dali.jiagoushi.top/Article/details/gtdjbomkoh.html

TS:   const arr: number[] = [1, 2, 3];
来源：http://dali.zhoulong.xyz/Article/details/gtxgmkkhas.html

Java: var arr = new int[]{1, 2, 3};  var list = new ArrayList<>(List.of(1, 2, 3));
来源：http://dali.shuidangran.top/Article/details/gtxueaqpgr.html

Go:   arr := []int{1, 2, 3}
来源：http://dali.yj20258888.top/Article/details/gtogiqpaua.html

Ruby: arr = [1, 2, 3]
来源：http://dali.zhongyouzk.top/Article/details/gtsjnaivfq.html

C#:   var arr = new[] { 1, 2, 3 };  var list = new List<int> { 1, 2, 3 };
来源：http://dali.dashuyun.cn/Article/details/gtbommrvlq.html

[D02] 追加元素到末尾
来源：http://dali.cqqwz.cn/Article/details/gtifbnratq.html

Py:   arr.append(4); arr.extend([5, 6])
来源：http://dali.hammf.cn/Article/details/gteqqasirj.html

PHP:  $arr[] = 4; array_push($arr, 5);
来源：http://dali.zhongyouzk.top/Article/details/gtzbmhpurf.html

JS:   arr.push(4);
来源：http://dali.bjfxy.top/Article/details/gtnlvnkczg.html

TS:   arr.push(4);
来源：http://dali.ppjwa.cn/Article/details/gtigkhdlsm.html

Java: list.add(4);
来源：http://dali.svipenyu.cn/Article/details/gtwipezutr.html

Go:   arr = append(arr, 4)
来源：http://dali.sufxvd.cn/Article/details/gtgddyzhrd.html

Ruby: arr << 4; arr.push(5)
来源：http://dali.kuanghao11.cn/Article/details/gthsqfcndn.html

C#:   list.Add(4);
来源：http://dali.pycfn.com/Article/details/gtjrlevymp.html

[D03] 在指定位置插入元素
来源：http://dali.quarkkingdee.top/Article/details/gtpeioiqpq.html

Py:   arr.insert(0, 0)
来源：http://dali.hnqzz.top/Article/details/gtcvmuegpo.html

PHP:  array_splice($arr, 0, 0, [0]);
来源：http://dali.9152youxi.cn/Article/details/gtyeevrtda.html

JS:   arr.splice(0, 0, 0);  arr.unshift(0)   // 插到头部
来源：http://dali.zhijiandao.cn/Article/details/gtcsrvgnye.html

TS:   arr.splice(0, 0, 0);
来源：http://dali.jinghuilouyu.cn/Article/details/gtskfrtpzt.html

Java: list.add(0, 0);
来源：http://dali.nanxinkj.top/Article/details/gtbgwtngas.html

Go:   arr = append([]int{0}, arr...)
来源：http://dali.jqgfzy.top/Article/details/gtkzefdwqq.html

Ruby: arr.insert(0, 0); arr.unshift(0)
来源：http://dali.yongpay.top/Article/details/gtrklfxpoy.html

C#:   list.Insert(0, 0);
来源：http://dali.nwbrower.top/Article/details/gtshbfktwb.html

[D04] 删除元素
来源：http://dali.dianchejie.cn/Article/details/gtoltfcesy.html

Py:   del arr[0]; arr.pop(); arr.remove(3)
来源：http://dali.iojbl.cn/Article/details/gttcuegdwt.html

PHP:  array_splice($arr, 0, 1); array_pop($arr);
来源：http://dali.tanke756.top/Article/details/gtzvprpqvs.html


<!-- 参考信息 -->