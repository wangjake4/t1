代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtfpmfdygh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xuanzx.com/Article/details/gtarnjliyp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hywenlv.cn/Article/details/gtaijeiuxo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtrdnfaezu.html

[A26] 类型转换总览
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdfsvvosi.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfsaemixz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gtirdsuixe.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgufenzy.top/Article/details/gtekuylobb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gtcregcqqb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtmhdbdequ.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gtqifpewys.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sysykeji.top/Article/details/gtzzopxoqv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.9152youxi.cn/Article/details/gtqklhxpuk.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtecqehhsh.html

B. 流程控制
来源：http://dali.ivvv.top/Article/details/gtrdydglqz.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtmtiyfdij.html

[B01] 条件判断 if / else
来源：http://dali.smart0.xyz/Article/details/gttieddoao.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.kuanghao11.cn/Article/details/gtritqpopr.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.daxiang520.top/Article/details/gtvbqimkro.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkovhwel.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gtikquieua.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtlsbvjnlf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtxbfqotwi.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xylfe.cn/Article/details/gtitkjacaz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtdcgisfje.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtacrzjbpy.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hysaishi.cn/Article/details/gtivvskesh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.316326.xyz/Article/details/gtraxczdks.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shuidangran.top/Article/details/gtcydvzrts.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuanzx.com/Article/details/gtlaelfjxk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtrddiwmyy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.kuanghao11.cn/Article/details/gtuzfrwgnz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.dashuyun.cn/Article/details/gtjrwxbyld.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigfzy.top/Article/details/gtimpygaag.html

[B03] switch / match / case
来源：http://dali.gzhubu.top/Article/details/gtnqzzmznx.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtfbbmarlu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtsoabhxus.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtvegffcoo.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gttpupcdxu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtgaizxcas.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.meibo888.top/Article/details/gtlqurpuru.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.c1oappe.top/Article/details/gtcfsktldn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.quarkkingdee.top/Article/details/gtiwpcrjpg.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmvubgytc.html

Py:   for i in range(10): print(i)
来源：http://dali.andypj.xyz/Article/details/gthwmdaimg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jlsjyb.cn/Article/details/gthxqlefmg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.bjfxy.top/Article/details/gtaxwqvlyr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258.top/Article/details/gthcdkzmpq.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtllyjqdfs.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xylfe.cn/Article/details/gtjcvtrhdl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gtjjsfmila.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nwbrower.top/Article/details/gtfheuynlo.html

[B05] 遍历数组 / 列表
来源：http://dali.aibaodan.cn/Article/details/gtyupyqjhd.html

Py:   for item in arr: print(item)
来源：http://dali.iojbl.cn/Article/details/gthdhfkglb.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gtjpwhqsrn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtwnjrfyjr.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gttjeozhhl.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuanzx.com/Article/details/gtdjcvywif.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yuxming.cn/Article/details/gtvcissmfr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxiycgzsv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.hysaishi.cn/Article/details/gtbrhhvwho.html

[B06] 遍历字典 / 对象
来源：http://dali.yonumen.top/Article/details/gtoaelyirr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnqzz.top/Article/details/gtihbvrvrw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtfiadwepq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtizosizju.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtqsquwicj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.guowangkeji.top/Article/details/gtwcfiaafd.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gogol.net.cn/Article/details/gthppiusuw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhixingplan.top/Article/details/gtxsxgstaz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.redwolf501.top/Article/details/gtsyksglmt.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtcngdqbqk.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258888.top/Article/details/gthbzlhhqm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtvjngypoq.html

JS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtvyhvssav.html

TS:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtzndpjrky.html

Java: while (i < 10) { i++; }
来源：http://dali.yuxming.cn/Article/details/gtbqlxexag.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yueranfly.top/Article/details/gttjvrfcwb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yonumen.top/Article/details/gtpctdliqb.html

C#:   while (i < 10) { i++; }
来源：http://dali.guowangkeji.top/Article/details/gtyzgswcza.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtomkcafzf.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.kuanghao11.cn/Article/details/gtrqfzahtg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gtkodjydqm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtekihihfz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhijiandao.cn/Article/details/gtqkzbtpqr.html

Java: do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtlemrinyr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gttdiwnacw.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cucudq.cn/Article/details/gthctelzfk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtlpaqklej.html

[B09] break 与 continue
来源：http://dali.zhijiandao.cn/Article/details/gtgbppxopt.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhengqikj.top/Article/details/gtprerfnrl.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtjmydgtov.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtgyzberey.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cqqwz.cn/Article/details/gtuphxhmgu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtrsspvftl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.mhx1999.top/Article/details/gtqyzfgejm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.shzxlz.cn/Article/details/gthntvxyck.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtryvgogbs.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gtfrlzddxq.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gtxipmenoz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hnqzz.top/Article/details/gtcuixwvwf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jqgfzy.top/Article/details/gtmkgrlmai.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtdnnmlqcg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yj20258.top/Article/details/gtoebaupcr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgfzy.top/Article/details/gtwwrzfori.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfbsivyaj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.ivvv.top/Article/details/gtqicoccgc.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuanzx.com/Article/details/gtsotaeeor.html

Py:   list(range(0, 10, 2))
来源：http://dali.yvedp.cn/Article/details/gtjwvhdxvs.html

PHP:  range(0, 10, 2);
来源：http://dali.yuxming.cn/Article/details/gtmpfhtvgq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtaexdftsq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtnfyzyddf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jiagoushi.top/Article/details/gtrdohnrln.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.meibo888.top/Article/details/gtncncgkxq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.guowangkeji.top/Article/details/gttnxklcbs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sxryk.cn/Article/details/gtpkhfjyej.html

[B12] 跳出多层循环
来源：http://dali.bjfxy.top/Article/details/gteqtstyek.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jqgfzy.top/Article/details/gtnuklzkvp.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtvelimxmx.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtebsoeqre.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gtbqmtfbyf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yonumen.top/Article/details/gtzimhdesj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.cucudq.cn/Article/details/gtfjnggqxy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.9152youxi.cn/Article/details/gtsobypult.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtspokwkoh.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtxcsknbdu.html

Py:   isinstance(x, (int, float))
来源：http://dali.cashguo.top/Article/details/gtgznrmdrd.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gtxwiuqaui.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gtfznqloxp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtnhfzanlj.html

Java: x instanceof Number
来源：http://dali.ivvv.top/Article/details/gtbtlqfedw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtelfbmxmn.html

Ruby: x.is_a?(Numeric)
来源：http://dali.aibaodan.cn/Article/details/gtkvifqyix.html

C#:   x is int or double or decimal
来源：http://dali.sxryk.cn/Article/details/gtotopyyns.html

[B14] 判断值是否在集合内
来源：http://dali.gzhubu.top/Article/details/gturaqmfln.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gtwbcwcsoa.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.snrcjt.cn/Article/details/gtjyjosxnp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.hfpthk.cn/Article/details/gtisvuhmif.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnzsoewqj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtpqfuwwqq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.bjfxy.top/Article/details/gtrvugtjdx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ybcxt.top/Article/details/gtqgaicewg.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jyoumei.cn/Article/details/gtflghuhwg.html

[B15] 布尔运算与取反
来源：http://dali.nwbrower.top/Article/details/gtvoaenuau.html

Py:   a and b or not c
来源：http://dali.cheryme.top/Article/details/gtceqgtrzz.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gtzakzdipc.html

JS:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtyhwgxbmx.html

TS:   a && b || !c
来源：http://dali.tian-w.cn/Article/details/gtbnxjrynx.html

Java: a && b || !c
来源：http://dali.yonumen.top/Article/details/gtrvizqsaf.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gthuzwateg.html

Ruby: a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtrfaiqqgg.html

C#:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtwfevmpvg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtdntmzjbj.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtglpigihi.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzerdxmam.html

JS:   if (!data) return;
来源：http://dali.xylfe.cn/Article/details/gtmobvfmma.html

TS:   if (!data) return;
来源：http://dali.cdnleiting.top/Article/details/gtcrisgqaq.html

Java: if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtirjcwtxj.html

Go:   if data == nil { return }
来源：http://dali.nanxinkj.top/Article/details/gtsqrzqoio.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gtssyntsng.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjmoxoqk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlaeaojjg.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtjwxhwcsr.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfuyfxdwz.html

[C01] 定义函数
来源：http://dali.zhongyouzk.top/Article/details/gtefgrjaku.html

Py:   def add(a, b): return a + b
来源：http://dali.tanke756.top/Article/details/gteifbaeki.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gtfvyljwdh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gtbuuolnsd.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gttojnyici.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gtgezkolpa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yueranfly.top/Article/details/gtvnovgmma.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guowangkeji.top/Article/details/gtvouthysr.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtifbdfojk.html

[C02] 默认参数
来源：http://dali.svipenyu.cn/Article/details/gtfpzuoqfz.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtbsfhoodt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gtixdykitt.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.hongshengwenyu.top/Article/details/gthaalftay.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtvyxaebpk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gthiraslyr.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtomaiajef.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcilsfhm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.xylfe.cn/Article/details/gtnlgszrhu.html

[C03] 可变参数
来源：http://dali.shuidangran.top/Article/details/gthnvkavfi.html

Py:   def total(*args): return sum(args)
来源：http://dali.sufxvd.cn/Article/details/gtuntvirfl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtlaygopms.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrwrturmk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gtuunvgmak.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtgvcrjstk.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.9152youxi.cn/Article/details/gtkffnnahk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nwbrower.top/Article/details/gtgvdorhuk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtyjnulppu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtkzqjqmcg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.aizwys.cn/Article/details/gtsaqzkcib.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gaohongyu789.top/Article/details/gtpyfbibcx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtkkzzawkt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtftwcytif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jyoumei.cn/Article/details/gtuufygwco.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gteacwjpve.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtyrizickq.html

C#:   f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtivxgqkoi.html

[C05] 返回多个值
来源：http://dali.svipenyu.cn/Article/details/gtycvkkqal.html

Py:   return a, b
来源：http://dali.tanke756.top/Article/details/gtisgxjkuy.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gttuhgrhsk.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtfvfyinif.html

TS:   return { a, b };
来源：http://dali.yj202588.top/Article/details/gtbyqqovqn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtadbdkdrq.html

Go:   return a, b
来源：http://dali.hywenlv.cn/Article/details/gtxbxldske.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtmtbhctze.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.snrcjt.cn/Article/details/gtrdacscho.html

[C06] 匿名函数 / lambda
来源：http://dali.cqqwz.cn/Article/details/gtmdifqtle.html

Py:   square = lambda x: x * x
来源：http://dali.yongpay.top/Article/details/gtoresfzoz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gzhubu.top/Article/details/gtvnhnpgse.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtuqiqzzqc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ppjwa.cn/Article/details/gtdegtwvon.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.guowangkeji.top/Article/details/gtzhknxjbg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xylfe.cn/Article/details/gtehadpvcz.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yj202588.top/Article/details/gtwgyoubwk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.nwbrower.top/Article/details/gttiynzcky.html

[C07] 把函数作为参数传入
来源：http://dali.daxiang520.top/Article/details/gtpgotcikk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.hywenlv.cn/Article/details/gtnkwkdbvn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsdxhzmaw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.zhiwuduotai.top/Article/details/gtvjbhozii.html

TS:   arr.map(String)
来源：http://dali.sxryk.cn/Article/details/gtwwictyae.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.jlsjyb.cn/Article/details/gtmxeobsyg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtnlomyxts.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtbtkfcdds.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tianlin.xyz/Article/details/gtewaxrgmp.html

[C08] 闭包
来源：http://dali.daxiang520.top/Article/details/gtjmomxsgk.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gtsgvnbquu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.zhengqikj.top/Article/details/gthvddwwmd.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nwbrower.top/Article/details/gtqatyhxdj.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gthwngxuzx.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jqgfzy.top/Article/details/gtmrbfqsif.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gogol.net.cn/Article/details/gtwmrrfoqu.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pycfn.com/Article/details/gtaryfenwr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.guowangkeji.top/Article/details/gtdhkellfq.html

[C09] 递归
来源：http://dali.shangyingyoupin.top/Article/details/gtdbyiefys.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.hfpthk.cn/Article/details/gtfgmenwdb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.ydzc1.top/Article/details/gtwtakwjfg.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yuanzhike.top/Article/details/gtbcwanocq.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gtlilugluj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.ivvv.top/Article/details/gtdokfwudl.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.chenlongwang.top/Article/details/gtoydnfsbw.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.chenlongwang.top/Article/details/gtsojkvofc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtmxboamfz.html

[C10] 变量作用域
来源：http://dali.ywan-chungtsiang.top/Article/details/gtebudjddd.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hnxiangtu.top/Article/details/gteffxvkic.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.guowangkeji.top/Article/details/gtpaiaxavb.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sufxvd.cn/Article/details/gtcfvzuwml.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gtlvhosfmt.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmlhlkoe.html

Go:   花括号块级作用域
来源：http://dali.chenlongwang.top/Article/details/gtironwvyw.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.nanxinkj.top/Article/details/gtwxodmjyu.html

C#:   块级作用域
来源：http://dali.daxiang520.top/Article/details/gtvxghoawj.html

[C11] 模块导入与导出
来源：http://dali.tian-w.cn/Article/details/gtsktvzbxb.html

Py:   from module import func
来源：http://dali.guowangkeji.top/Article/details/gtbuflczyb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.nanxuanxn.top/Article/details/gtmupxfpen.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhoulong.xyz/Article/details/gtxodfyaaw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.cucudq.cn/Article/details/gtdtpocazv.html

Java: import java.util.List;
来源：http://dali.yuxming.cn/Article/details/gtraimkiqr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.xylfe.cn/Article/details/gthqwlckam.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhoulong.xyz/Article/details/gtuqjeazxa.html

C#:   using System.Text;
来源：http://dali.yuanzhike.top/Article/details/gthiaxogwb.html

[C12] 立即执行函数 IIFE
来源：http://dali.xuetiantiany.cn/Article/details/gtaktupvqn.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gtzfttbrjx.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yangfankeji.com/Article/details/gtobzykcao.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtnwfsiics.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jlsjyb.cn/Article/details/gtcmvckkxm.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yvedp.cn/Article/details/gtzlsxzlgh.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.ehwqpu.com/Article/details/gthcqjuslm.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhoulong.xyz/Article/details/gtinqyuuso.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.meibo888.top/Article/details/gtdvbzysef.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpjqvwpb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.hnqzz.top/Article/details/gtuygkvofx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtravifuws.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.feifeiyinyue.top/Article/details/gtxpkycvxc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtoyxpsjur.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtvqmfotmg.html

Go:   func add(a, b int) int
来源：http://dali.jinqigfzy.top/Article/details/gtofxaahup.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.havefunace.top/Article/details/gtqgwiwadg.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.snrcjt.cn/Article/details/gtcbikcees.html

[C14] 泛型函数
来源：http://dali.ybcxt.top/Article/details/gtnrrrikiq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.ehwqpu.com/Article/details/gtvfvdvmdu.html

PHP:  // 无泛型
来源：http://dali.fengsongda.top/Article/details/gthirgaqmc.html

JS:   // 无泛型
来源：http://dali.jqgufenzy.top/Article/details/gtsqukwfru.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.gzhubu.top/Article/details/gtebjaqnxt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.pengpengdd.cyou/Article/details/gtaoyeesbz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yueranfly.top/Article/details/gtgurvilan.html

Ruby: # 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtmtezxzom.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sufxvd.cn/Article/details/gtumldykqs.html

[C15] 解构 / 展开参数
来源：http://dali.daxiang520.top/Article/details/gtsagcanbm.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zdqjudy.top/Article/details/gtnwosyodc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yvedp.cn/Article/details/gtogeiuair.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtwoakxzlu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jinghuilouyu.cn/Article/details/gttumcusmj.html

Java: // 无解构
来源：http://dali.yuanzhike.top/Article/details/gtspbeyxmx.html

Go:   // 无解构
来源：http://dali.havefunace.top/Article/details/gtqyijkdie.html

Ruby: a, b = pair
来源：http://dali.xinyue.icu/Article/details/gtfvragljp.html

C#:   var (a, b) = pair;
来源：http://dali.yvedp.cn/Article/details/gtyuxyxkhq.html

[C16] 函数 / 方法重载
来源：http://dali.sweek.top/Article/details/gtdpuosogm.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.gzhubu.top/Article/details/gtcoyqsksc.html


<!-- 参考信息 -->