代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cdnleiting.top/Article/details/gtyvhrrpwg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtkqtznwfj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.svipenyu.cn/Article/details/gtknoqivjo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhixingplan.top/Article/details/gtntacsudj.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtplbxochg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sysykeji.top/Article/details/gtwiuihixb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xuanzx.com/Article/details/gtzsausgxo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xinyue.icu/Article/details/gtnlakqahe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xuanzx.com/Article/details/gttpemqykx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtasagvuqo.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.wangshuangyany.cn/Article/details/gtvyxlqlro.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxzhnczi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gtsmrenffn.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtncgyozqj.html

B. 流程控制
来源：http://dali.yongpay.top/Article/details/gtolkkqtzz.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtiogakpbr.html

[B01] 条件判断 if / else
来源：http://dali.chenzaomai.com/Article/details/gtkxzegqju.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvubfuffp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtcdkfusgq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtqljolozv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtzzwijrnh.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.meibo888.top/Article/details/gtlwiiwffb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.kuanghao11.cn/Article/details/gtefpvpbpe.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cashguo.top/Article/details/gtchgclpax.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtmxqhesbl.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtdsiimdnq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.snrcjt.cn/Article/details/gtxngiqxhs.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.daxiang520.top/Article/details/gtrwghyzch.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtttgdmchc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tian-w.cn/Article/details/gtcxslayid.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gteecrrpam.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tanke756.top/Article/details/gtxkaoghkg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangdashe.top/Article/details/gtulztottx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gtqcxgxavn.html

[B03] switch / match / case
来源：http://dali.c1oappe.top/Article/details/gtyotidufr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj202588.top/Article/details/gtfrstacmp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.0kj1m.cn/Article/details/gtnmcjbxbz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gtadnqofid.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xziqi.cn/Article/details/gtojgpvtqf.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtndcwobst.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtpdzkwqaw.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gtwowvilzg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tian-w.cn/Article/details/gtuubvkthw.html

[B04] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtcxairprr.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtryghlnot.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.andypj.xyz/Article/details/gtzhniswpv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ppjwa.cn/Article/details/gtrjrufvsk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cucudq.cn/Article/details/gtlancchmo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gtgqdjrdym.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtlgfuqzuz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xuetiantiany.cn/Article/details/gtycdmxtex.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ppjwa.cn/Article/details/gtfnhvkvwg.html

[B05] 遍历数组 / 列表
来源：http://dali.zhongyouzk.top/Article/details/gtcmskmmss.html

Py:   for item in arr: print(item)
来源：http://dali.yanxiufei.cn/Article/details/gtglhkgygb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nwbrower.top/Article/details/gtxglqtkrd.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtvdhubnqa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gtudglcrsy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.nanxuanxn.top/Article/details/gtexwtxvvr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.cashguo.top/Article/details/gtsxxkewoz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gtymmvvchm.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtccbkpgql.html

[B06] 遍历字典 / 对象
来源：http://dali.guowangkeji.top/Article/details/gtektsappn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gttmdqeqfc.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gthgjcqrbo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gtcptseyvz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sufxvd.cn/Article/details/gtbktfaqmp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jyoumei.cn/Article/details/gtpymzuaju.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtblxwoxhh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gtdtfllogz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.mhx1999.top/Article/details/gtlfxgivto.html

[B07] while 循环
来源：http://dali.xinyue.icu/Article/details/gtjykhbqfa.html

Py:   while i < 10: i += 1
来源：http://dali.chenlongwang.top/Article/details/gtnpltqjuv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jiagoushi.top/Article/details/gtjdpxxdzj.html

JS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtttvkbpms.html

TS:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gttyycikzl.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtzcpqrngd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtdynuxwup.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtktayqxup.html

C#:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtpqbkjlec.html

[B08] do-while（至少执行一次）
来源：http://dali.smart0.xyz/Article/details/gtdkvpbkhm.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.0kj1m.cn/Article/details/gtuovilltt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.guannengcc.top/Article/details/gtbazxoiod.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtmakkhgdy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gzhubu.top/Article/details/gtbqgrxhkg.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtbhwzjgzm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtrvujwkas.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gtdyciviyu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gtsfbopprb.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtxoxajvqd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.feifeiyinyue.top/Article/details/gtjwqpgpah.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gttiqthmbb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtrcghxjku.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfypwylbp.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gttpqpwtst.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.aizwys.cn/Article/details/gtdegicryy.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cdnleiting.top/Article/details/gtbdgykajp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhongyouzk.top/Article/details/gtsuhcmrce.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangtech.top/Article/details/gtvxmclzjh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guannengcc.top/Article/details/gtxffmihdq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yj20258888.top/Article/details/gtyltqigst.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj202588.top/Article/details/gtuznugaaj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtcojdqpre.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.andypj.xyz/Article/details/gtuiyketqu.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.fengsongda.top/Article/details/gtysirupdl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jlsjyb.cn/Article/details/gtffgebqho.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmplkfvze.html

[B11] 生成数字序列 / 区间
来源：http://dali.aibaodan.cn/Article/details/gtmuyownlk.html

Py:   list(range(0, 10, 2))
来源：http://dali.xziqi.cn/Article/details/gtfkyesyuz.html

PHP:  range(0, 10, 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlfprqca.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gtvjpikbyd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nanxinkj.top/Article/details/gttkgtndvc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ybcxt.top/Article/details/gtxwrksufu.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhongyouzk.top/Article/details/gtbidndqas.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gtsxuhjkjn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.9152youxi.cn/Article/details/gtdakxzvvy.html

[B12] 跳出多层循环
来源：http://dali.dashuyun.cn/Article/details/gtuaatufpa.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aizwys.cn/Article/details/gtybsltfya.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhixingplan.top/Article/details/gtptudojhj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gteelidneh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gthxzwzegj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtxgadvcbj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ivvv.top/Article/details/gtksvuoplt.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtfagovwhw.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jianghu66.top/Article/details/gtegyxholc.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gtpylcojsl.html

Py:   isinstance(x, (int, float))
来源：http://dali.bjfxy.top/Article/details/gtyzwetsxd.html

PHP:  is_numeric($x)
来源：http://dali.hnxiangtu.top/Article/details/gtydrhdrxb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xuanzx.com/Article/details/gtjbtpfkui.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjmtxaddo.html

Java: x instanceof Number
来源：http://dali.hammf.cn/Article/details/gtjwjnxhkt.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuanzhike.top/Article/details/gtxcgjmcnz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhixingplan.top/Article/details/gttaqsekwo.html

C#:   x is int or double or decimal
来源：http://dali.wangshuangyany.cn/Article/details/gthhyelayn.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gtggzbquvk.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtqymaattc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtcqhzpvbk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtbvhcqizu.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gtepjnhwvu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gtsgrqawko.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ehwqpu.com/Article/details/gthgzxaosq.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jyoumei.cn/Article/details/gtldxuzgzj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yvedp.cn/Article/details/gtpqkwaqtu.html

[B15] 布尔运算与取反
来源：http://dali.bjfxy.top/Article/details/gtvrsqjtzi.html

Py:   a and b or not c
来源：http://dali.yonumen.top/Article/details/gtvzgrgmqv.html

PHP:  $a && $b || !$c
来源：http://dali.nwbrower.top/Article/details/gteaczjlzu.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtinxyelol.html

TS:   a && b || !c
来源：http://dali.ivvv.top/Article/details/gtaclbmnug.html

Java: a && b || !c
来源：http://dali.sweek.top/Article/details/gtzwmtywuo.html

Go:   a && b || !c
来源：http://dali.jiagoushi.top/Article/details/gtinxdzxgy.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtheatuwal.html

C#:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtkptrhnfj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.sweek.top/Article/details/gtzcnnbtyf.html

Py:   if not data: return
来源：http://dali.jlsjyb.cn/Article/details/gtngwvjsqn.html

PHP:  if (!$data) { return; }
来源：http://dali.vqdsnc.cn/Article/details/gtdfaneazv.html

JS:   if (!data) return;
来源：http://dali.shzxlz.cn/Article/details/gtrfybpetc.html

TS:   if (!data) return;
来源：http://dali.hysaishi.cn/Article/details/gtzisrpqzv.html

Java: if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtbnnypsfx.html

Go:   if data == nil { return }
来源：http://dali.yj20258.top/Article/details/gtsgjsbhxs.html

Ruby: return if data.nil?
来源：http://dali.dashuyun.cn/Article/details/gtdcpgsgcd.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gttegpxbsz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtzpbciqhe.html

C. 函数与作用域
来源：http://dali.iojbl.cn/Article/details/gttcqcjebz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtcltwnjya.html

[C01] 定义函数
来源：http://dali.zdqjudy.top/Article/details/gtfxvsnweh.html

Py:   def add(a, b): return a + b
来源：http://dali.haohaochexian.top/Article/details/gtwngeerms.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yongpay.top/Article/details/gtugcnczrv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtdgnieliu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtxfxyijay.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jiagoushi.top/Article/details/gtntllietp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtsddaphjs.html

Ruby: def add(a, b); a + b; end
来源：http://dali.meibo888.top/Article/details/gtadfvgsuf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gthgwerksj.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gtdgiznmjj.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtwcrnemsu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.shzxlz.cn/Article/details/gteyubasjm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtckvtmzlz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dashuyun.cn/Article/details/gtqgwdrlpv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jyoumei.cn/Article/details/gtfvsvpeun.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yanxiufei.cn/Article/details/gtwkvqnmbf.html

Ruby: def greet(name = "World") = name
来源：http://dali.ydzc1.top/Article/details/gtmhlfcmba.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jinqigfzy.top/Article/details/gthvueadyu.html

[C03] 可变参数
来源：http://dali.haohaochexian.top/Article/details/gtadcelfvt.html

Py:   def total(*args): return sum(args)
来源：http://dali.xinyue.icu/Article/details/gthpiudiuu.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtnbenxbkd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtafhcaomp.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtnmkwvirx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.aizwys.cn/Article/details/gtqpyyeujl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.dashuyun.cn/Article/details/gtjphbxrmq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.9152youxi.cn/Article/details/gtwlaxgjnn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.svipenyu.cn/Article/details/gtrmigtmem.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gzhubu.top/Article/details/gtcfsqnphv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.cheryme.top/Article/details/gtrbvlotcx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gteeoupzhh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jyoumei.cn/Article/details/gtmtfauxmu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yonumen.top/Article/details/gtcihgcpau.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.smart0.xyz/Article/details/gtaqxjdpjl.html

Go:   // 无：用配置结构体参数
来源：http://dali.andypj.xyz/Article/details/gthluqcadp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hysaishi.cn/Article/details/gtmajrjlbz.html

C#:   f(a: 1, b: 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtngpruohv.html

[C05] 返回多个值
来源：http://dali.jqgufenzy.top/Article/details/gttkegctwu.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gtzbehacui.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtbvyqtcll.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xylfe.cn/Article/details/gtwmxpfvil.html

TS:   return { a, b };
来源：http://dali.tian-w.cn/Article/details/gtpwdtltap.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aibaodan.cn/Article/details/gtkzbktpgp.html

Go:   return a, b
来源：http://dali.iojbl.cn/Article/details/gtdozwmovi.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfupwjqhx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpftfihi.html

[C06] 匿名函数 / lambda
来源：http://dali.yj20258888.top/Article/details/gtakodjehx.html

Py:   square = lambda x: x * x
来源：http://dali.hywenlv.cn/Article/details/gtaaivvwaa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hysaishi.cn/Article/details/gtpgsxejqz.html

JS:   const square = x => x * x;
来源：http://dali.tanke756.top/Article/details/gtthobkmon.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yvedp.cn/Article/details/gtjzodhejd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guannengcc.top/Article/details/gtleqsjgrp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yangfankeji.com/Article/details/gtxvqrpfoa.html

Ruby: square = ->(x) { x * x }
来源：http://dali.tian-w.cn/Article/details/gtvhafozfh.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gtvzgwzvwn.html

[C07] 把函数作为参数传入
来源：http://dali.jyoumei.cn/Article/details/gtjobvykze.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hfpthk.cn/Article/details/gtkfoyunfz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.iojbl.cn/Article/details/gtqodxxrsw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.quarkkingdee.top/Article/details/gtyqumrqvv.html

TS:   arr.map(String)
来源：http://dali.sweek.top/Article/details/gtayrodzte.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupdsdzfo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hysaishi.cn/Article/details/gttdzrmmky.html

Ruby: arr.map(&:upcase)
来源：http://dali.sufxvd.cn/Article/details/gtmufddzuj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.chenlongwang.top/Article/details/gttlnpqstw.html

[C08] 闭包
来源：http://dali.zhixingplan.top/Article/details/gtgwcwnmea.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yangfankeji.com/Article/details/gthzdtjkae.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gaohongyu789.top/Article/details/gtjqizyxtb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.yj20258.top/Article/details/gtwoedmdud.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hnqzz.top/Article/details/gtyodvabqh.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.havefunace.top/Article/details/gtezqmlasm.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.ivvv.top/Article/details/gtfembdwow.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtmwugmpmd.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.chenzaomai.com/Article/details/gtpcwzulrz.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gtpyvwfasv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.havefunace.top/Article/details/gtbabochcw.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gtnrqdgizc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jiagoushi.top/Article/details/gtycpqbdzf.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtvfvjpcdu.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.haohaochexian.top/Article/details/gtrlsbhegh.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.birdmap.top/Article/details/gtczwyoekr.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.yongpay.top/Article/details/gthaqueubn.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.aibaodan.cn/Article/details/gtxkwlbmpa.html

[C10] 变量作用域
来源：http://dali.jqgfzy.top/Article/details/gtgkrqosjd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.svipenyu.cn/Article/details/gttjmjtuab.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yonumen.top/Article/details/gtxpdqfnrl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guowangkeji.top/Article/details/gtdhoafxab.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsfpjlfmw.html

Java: 方法内为块级作用域
来源：http://dali.chenzaomai.com/Article/details/gtsonecuor.html

Go:   花括号块级作用域
来源：http://dali.chenjidiqi.icu/Article/details/gtdtllznwj.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.fzhhl.top/Article/details/gtmpnrfeqv.html

C#:   块级作用域
来源：http://dali.sweek.top/Article/details/gtnjnxauzj.html

[C11] 模块导入与导出
来源：http://dali.ivvv.top/Article/details/gttzwrohvp.html

Py:   from module import func
来源：http://dali.ppjwa.cn/Article/details/gtetceobzs.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.shuidangran.top/Article/details/gtmdoleift.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetvjxpcu.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvzkrybw.html

Java: import java.util.List;
来源：http://dali.fzhhl.top/Article/details/gtosogwqtu.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.chenlongwang.top/Article/details/gtkaaylnpx.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jqgfzy.top/Article/details/gtiqkwjybo.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gtwlssocss.html

[C12] 立即执行函数 IIFE
来源：http://dali.feifeiyinyue.top/Article/details/gtwjwgwmly.html

Py:   (lambda: print("run"))()
来源：http://dali.svipenyu.cn/Article/details/gtpikzaesn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.ivvv.top/Article/details/gtdihxdbph.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sxryk.cn/Article/details/gtwqwxgoxy.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtmklgeurh.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.haohaochexian.top/Article/details/gtusecfbsu.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yuanzhike.top/Article/details/gtzwtiycmy.html

Ruby: -> { puts "run" }.call
来源：http://dali.cheryme.top/Article/details/gtyvrirfqo.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtoarthdqb.html

[C13] 类型声明 / 类型注解
来源：http://dali.jianghu66.top/Article/details/gtbaqdcniz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinqigufen.top/Article/details/gtpkhdjprj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqytigmb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gaohongyu789.top/Article/details/gtfcmvjcey.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtxierydad.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtekkuemyq.html

Go:   func add(a, b int) int
来源：http://dali.xinyue.icu/Article/details/gtfexmmegz.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.svipenyu.cn/Article/details/gtfjgdtura.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.xylfe.cn/Article/details/gtiddlcexl.html

[C14] 泛型函数
来源：http://dali.quarkkingdee.top/Article/details/gtklfybkdq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.tianlin.xyz/Article/details/gtgkzdtxjt.html

PHP:  // 无泛型
来源：http://dali.daxiang520.top/Article/details/gtcfspqrge.html

JS:   // 无泛型
来源：http://dali.zhixingplan.top/Article/details/gtotubsmau.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.zhixingplan.top/Article/details/gtvwkuejdm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zycfv.cn/Article/details/gthirojsbe.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.tian-w.cn/Article/details/gtmgvgezwc.html

Ruby: # 无泛型
来源：http://dali.hnqzz.top/Article/details/gtwqgxnzlp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gtmrxzksbu.html

[C15] 解构 / 展开参数
来源：http://dali.meibo888.top/Article/details/gtfaxcrmdv.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.tianlin.xyz/Article/details/gtvcjopkvu.html

PHP:  [$a, $b] = $pair;
来源：http://dali.jinqigfzy.top/Article/details/gtwrmzchyp.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.sysykeji.top/Article/details/gtcutltwgr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.gotoacloud.top/Article/details/gtbxnypagf.html

Java: // 无解构
来源：http://dali.xziqi.cn/Article/details/gtegwiawoe.html

Go:   // 无解构
来源：http://dali.redwolf501.top/Article/details/gtsgotcszo.html

Ruby: a, b = pair
来源：http://dali.dianchejie.cn/Article/details/gtvjjqkhmo.html

C#:   var (a, b) = pair;
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlsnnxbf.html

[C16] 函数 / 方法重载
来源：http://dali.shuidangran.top/Article/details/gtwjtztejn.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.yuxming.cn/Article/details/gtrqybssbn.html


<!-- 参考信息 -->