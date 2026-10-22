代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.xuanzx.com/Article/details/gtmoifjgda.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gotoacloud.top/Article/details/gtezgqqbpf.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcparcejt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtigaczbpr.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.bjfxy.top/Article/details/gtacxmbrem.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtsbxeomlu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtitduibro.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shzxlz.cn/Article/details/gtxgmdyysk.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gtztqbvtew.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gtwzunlvls.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yj20258888.top/Article/details/gtkjkujkdb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jqgfzy.top/Article/details/gtphpgxeqg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hfpthk.cn/Article/details/gtyacoxpze.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tanke756.top/Article/details/gtuubeomxr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gttiyoswix.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.feifeiyinyue.top/Article/details/gtpogjogpv.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtxrdzyyjh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtasusaumx.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gtexhrjuhr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtrujdykez.html

[B01] 条件判断 if / else
来源：http://dali.yongpay.top/Article/details/gtmgtimmfx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cqqwz.cn/Article/details/gtfjvgfztc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnvxbvncc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tian-w.cn/Article/details/gtdxoychsb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtbplbalpr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtvzywpafs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gtumwqkgsz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gtbpsvvlrb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtfurcexcx.html

[B02] 多分支 else if / elif
来源：http://dali.aizwys.cn/Article/details/gtjoitqawh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.0kj1m.cn/Article/details/gtpphaunbg.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ehwqpu.com/Article/details/gtdgdbbblq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtjqxsexlc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtmwhclper.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aizwys.cn/Article/details/gtovucimtl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gtbpjijgej.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gtswshsnaq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hnxiangtu.top/Article/details/gtqmgablow.html

[B03] switch / match / case
来源：http://dali.pycfn.com/Article/details/gtwhgqnowo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctghntit.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gtwjhjvpvu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtzhcnioix.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtyammswez.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jlsjyb.cn/Article/details/gtbznegyrh.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.316326.xyz/Article/details/gthfmigbet.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtttnhrnqf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtskvzkoba.html

[B04] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtekypbcnn.html

Py:   for i in range(10): print(i)
来源：http://dali.sweek.top/Article/details/gtcnhpazsb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gturrgythu.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xinyue.icu/Article/details/gtiuljcyvm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubdguqcg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmohzvfyc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xinyue.icu/Article/details/gthtsbosqd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtigelpzuw.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.tanke756.top/Article/details/gtllnuaobu.html

[B05] 遍历数组 / 列表
来源：http://dali.jyoumei.cn/Article/details/gtjzlscasu.html

Py:   for item in arr: print(item)
来源：http://dali.cashguo.top/Article/details/gtiocmaypv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.guowangkeji.top/Article/details/gtflnddnsa.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtsbscmdgd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpkwekimv.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.chenjidiqi.icu/Article/details/gtynzhjtss.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.chenzaomai.com/Article/details/gtjurweprd.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtreoezskz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.pycfn.com/Article/details/gtznueyzkg.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtbmjrwpsd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangshuangyany.cn/Article/details/gtsbmffskl.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hfpthk.cn/Article/details/gtyhphfxzs.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gtyzqimfxw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtmrbjozdz.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtdqrrwrpi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.zdqjudy.top/Article/details/gtpxjqysrp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhiwuduotai.top/Article/details/gtqfsnlywi.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.c1oappe.top/Article/details/gtnqsfizsh.html

[B07] while 循环
来源：http://dali.gotoacloud.top/Article/details/gtbdbvpsun.html

Py:   while i < 10: i += 1
来源：http://dali.sweek.top/Article/details/gtwkzljgqh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenzaomai.com/Article/details/gtgkyiazqx.html

JS:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlgcopelz.html

TS:   while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtupxgvfjz.html

Java: while (i < 10) { i++; }
来源：http://dali.guannengcc.top/Article/details/gtudcmbohd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtwyuwkztd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.redwolf501.top/Article/details/gthgixsunp.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gtqfdxsozg.html

[B08] do-while（至少执行一次）
来源：http://dali.andypj.xyz/Article/details/gtvizszefn.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj202588.top/Article/details/gtrobrnzqt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.bjfxy.top/Article/details/gtjwovbczg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gtkyjajnmm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.daxiang520.top/Article/details/gtddaguvjz.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtvcoudhso.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.svipenyu.cn/Article/details/gtcvwfweat.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gtvhmldatn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtktfydatb.html

[B09] break 与 continue
来源：http://dali.zhengqikj.top/Article/details/gtkdbgglld.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cqqwz.cn/Article/details/gtpaseodrp.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtwtwkpdnv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtzzvsglpk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtilnxyxyc.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtzfkjlffz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.pengpengdd.cyou/Article/details/gtcwdoqrnf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.cashguo.top/Article/details/gtwfkvssnw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtfwuuylgr.html

[B10] 遍历同时拿索引
来源：http://dali.mhx1999.top/Article/details/gtaxwdadod.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gtdkdfoeuc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.wangdashe.top/Article/details/gtwbxhyula.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xuanzx.com/Article/details/gtudlrcjvx.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtetnncaqr.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cheryme.top/Article/details/gtqsrxlcul.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.ybcxt.top/Article/details/gthdjicvzp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jyoumei.cn/Article/details/gtbxvbhssv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtcralazoy.html

[B11] 生成数字序列 / 区间
来源：http://dali.cqqwz.cn/Article/details/gtnhxrhftc.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtnlnuponb.html

PHP:  range(0, 10, 2);
来源：http://dali.yj202588.top/Article/details/gtwhpqcbas.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtqtxqdqnk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtbpxkmoos.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hammf.cn/Article/details/gthnfvnpfm.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gogol.net.cn/Article/details/gtzuqgpxnq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gtqckiqgej.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtacknmupv.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtmogaqeeq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gzhubu.top/Article/details/gtnvygdcqj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.havefunace.top/Article/details/gtjxukgmqj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtcigciqki.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtyutnivex.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gtgzvuvxgt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xinyue.icu/Article/details/gtenjcelzs.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gtzodrowya.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jiagoushi.top/Article/details/gtsjzbrtmu.html

[B13] 判断是否为数字
来源：http://dali.yanxiufei.cn/Article/details/gtjfzbcool.html

Py:   isinstance(x, (int, float))
来源：http://dali.cqqwz.cn/Article/details/gtslkjqatv.html

PHP:  is_numeric($x)
来源：http://dali.316326.xyz/Article/details/gtfvrgemdp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtruwbinpz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhijiandao.cn/Article/details/gtcuylgowf.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtbgaqnhoa.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.havefunace.top/Article/details/gtlkjjuszw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.wangdashe.top/Article/details/gtiobulakk.html

C#:   x is int or double or decimal
来源：http://dali.nanxinkj.top/Article/details/gtlvukfxri.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gtsguqqvaa.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cdnleiting.top/Article/details/gtebsbjyay.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgfzy.top/Article/details/gtzdexownq.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtqqwjyceb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ppjwa.cn/Article/details/gtevfudriy.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.chenlongwang.top/Article/details/gtrcsqyvuj.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtleohuqzu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtlbcpwuun.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.shuidangran.top/Article/details/gtebfsxqal.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gtnmxqvyeb.html

Py:   a and b or not c
来源：http://dali.zhoulong.xyz/Article/details/gtkbalvkzw.html

PHP:  $a && $b || !$c
来源：http://dali.guowangkeji.top/Article/details/gtdxjncfss.html

JS:   a && b || !c
来源：http://dali.xuetiantiany.cn/Article/details/gtfjptacrs.html

TS:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtkxvzgbmw.html

Java: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtkcsndvem.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtkpvzxawy.html

Ruby: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtlcoxihrn.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gtamyblznf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.cashguo.top/Article/details/gtmmybnuvx.html

Py:   if not data: return
来源：http://dali.chenlongwang.top/Article/details/gtyytjdjim.html

PHP:  if (!$data) { return; }
来源：http://dali.xuetiantiany.cn/Article/details/gtphqanurv.html

JS:   if (!data) return;
来源：http://dali.svipenyu.cn/Article/details/gtyniwueul.html

TS:   if (!data) return;
来源：http://dali.yuxming.cn/Article/details/gtoyjhqrnl.html

Java: if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gtbdwgfjky.html

Go:   if data == nil { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjukqabbh.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtpgyaephy.html

C#:   if (data == null) return;
来源：http://dali.gaohongyu789.top/Article/details/gtkjtfukom.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuswslmlr.html

C. 函数与作用域
来源：http://dali.guowangkeji.top/Article/details/gtjhuhypax.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcywxzhez.html

[C01] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtmlwsuncy.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtvrzggklm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwyvwkwnd.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtzlwjzpgm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtdyksguax.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtmrdvdijt.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtsajxthbt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtznuntjyk.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gtdcijhebw.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtciokjzbs.html

Py:   def greet(name="World"): return name
来源：http://dali.aibaodan.cn/Article/details/gtwbqzfwch.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtwtdygtcv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cucudq.cn/Article/details/gtxurannxm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtsqyqsgle.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtpzpcefvq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzxryznrd.html

Ruby: def greet(name = "World") = name
来源：http://dali.yonumen.top/Article/details/gtojeaobsu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.dashuyun.cn/Article/details/gtodfueysi.html

[C03] 可变参数
来源：http://dali.zhijiandao.cn/Article/details/gteirmbtqe.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhixingplan.top/Article/details/gtwbhdwnxi.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenlongwang.top/Article/details/gtlbjwfuwc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.feifeiyinyue.top/Article/details/gtlpwkbodo.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtoswwtssz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gtbgvehliz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsexciaat.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yangfankeji.com/Article/details/gtotwghlyy.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jqgfzy.top/Article/details/gtzvjpznkv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.andypj.xyz/Article/details/gteppfmyyw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hnqzz.top/Article/details/gtwnzolbzv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtlvxwesdk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtxbyuatmu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cqqwz.cn/Article/details/gtfaotfewa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.svipenyu.cn/Article/details/gtjmrgqdnp.html

Go:   // 无：用配置结构体参数
来源：http://dali.bjfxy.top/Article/details/gthpanmbus.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtruwsjlkz.html

C#:   f(a: 1, b: 2)
来源：http://dali.iojbl.cn/Article/details/gtedjbrhes.html

[C05] 返回多个值
来源：http://dali.chenjidiqi.icu/Article/details/gtyaxhjvzi.html

Py:   return a, b
来源：http://dali.gogol.net.cn/Article/details/gtpzzsbfpa.html

PHP:  return [$a, $b];
来源：http://dali.birdmap.top/Article/details/gtdzseusvy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ppjwa.cn/Article/details/gtnxmfmioq.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtonuzrsvt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yuanzhike.top/Article/details/gtwhzxaaix.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gtuwluygyc.html

Ruby: return a, b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywlvocwn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.shuidangran.top/Article/details/gtwoztnyrv.html

[C06] 匿名函数 / lambda
来源：http://dali.vqdsnc.cn/Article/details/gtoyjlwzba.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtvnhtcanq.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sysykeji.top/Article/details/gtknohlmcw.html

JS:   const square = x => x * x;
来源：http://dali.wangdashe.top/Article/details/gtpdjwwkcu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtiiaidotm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gthinsnfzd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkgkmmxh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dashuyun.cn/Article/details/gtjexjdatf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gtbnlhgedq.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtpguhvjdm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtrpsrfuvy.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.quarkkingdee.top/Article/details/gtyzpkjoxl.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yuxming.cn/Article/details/gtyyyuvirs.html

TS:   arr.map(String)
来源：http://dali.guannengcc.top/Article/details/gtbilalnsa.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.guowangkeji.top/Article/details/gtmsrgrkby.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.jinqigufen.top/Article/details/gtzmtrwfmy.html

Ruby: arr.map(&:upcase)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvjzlajvc.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.gaohongyu789.top/Article/details/gtqvempeos.html

[C08] 闭包
来源：http://dali.jqgufenzy.top/Article/details/gthdtaefhc.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.daxiang520.top/Article/details/gtptiuplhv.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkotkfzjr.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.hysaishi.cn/Article/details/gtwescvevu.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.fzhhl.top/Article/details/gtokpkjwkb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.jyoumei.cn/Article/details/gttsjsgpql.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gzhubu.top/Article/details/gtasnnttbs.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yueranfly.top/Article/details/gtxsjogzkh.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtfufiskdb.html

[C09] 递归
来源：http://dali.guannengcc.top/Article/details/gtbzozjooq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtyjbbwptn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yvedp.cn/Article/details/gtlzsqqdrz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.guannengcc.top/Article/details/gtawmdbbhi.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yvedp.cn/Article/details/gtixsaugmo.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hongshengwenyu.top/Article/details/gtxdgtsntg.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.c1oappe.top/Article/details/gtvxusfsch.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.meibo888.top/Article/details/gtbxfmyixs.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.yvedp.cn/Article/details/gtqycqaojc.html

[C10] 变量作用域
来源：http://dali.quarkkingdee.top/Article/details/gtlvumbekn.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.redwolf501.top/Article/details/gtxeuidaqr.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.pengpengdd.cyou/Article/details/gtiqzmgvtk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.dashuyun.cn/Article/details/gttgzpwdbi.html

TS:   同 JS
来源：http://dali.yonumen.top/Article/details/gtlouvyacg.html

Java: 方法内为块级作用域
来源：http://dali.daria6918.cn/Article/details/gtmgycrbns.html

Go:   花括号块级作用域
来源：http://dali.daria6918.cn/Article/details/gtohiewpxu.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.chenzaomai.com/Article/details/gtyuatqeja.html

C#:   块级作用域
来源：http://dali.jinqigufen.top/Article/details/gtqgftbwvo.html

[C11] 模块导入与导出
来源：http://dali.9152youxi.cn/Article/details/gtyttrlzgk.html

Py:   from module import func
来源：http://dali.cashguo.top/Article/details/gtekfrdirm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.gaohongyu789.top/Article/details/gtacqvphpn.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zycfv.cn/Article/details/gticwkvejw.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.pengpengdd.cyou/Article/details/gtebcbloob.html

Java: import java.util.List;
来源：http://dali.aizwys.cn/Article/details/gttjwkvwij.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.cheryme.top/Article/details/gtlkhudsau.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.kuanghao11.cn/Article/details/gtzqtchwbb.html

C#:   using System.Text;
来源：http://dali.yongpay.top/Article/details/gtxytroagv.html

[C12] 立即执行函数 IIFE
来源：http://dali.yanxiufei.cn/Article/details/gtttinqhhv.html

Py:   (lambda: print("run"))()
来源：http://dali.shuidangran.top/Article/details/gtknmsnylc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.yvedp.cn/Article/details/gtmvhufvmd.html

JS:   (() => { console.log("run"); })();
来源：http://dali.quarkkingdee.top/Article/details/gtphozzdyh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gtlymyyayn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gtpdslukhf.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.fzhhl.top/Article/details/gtnrxskafx.html

Ruby: -> { puts "run" }.call
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyfrccoq.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gtqqhcdnny.html

[C13] 类型声明 / 类型注解
来源：http://dali.316326.xyz/Article/details/gtrhsfgirh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.havefunace.top/Article/details/gtevfiymwj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gtconoxzty.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ybcxt.top/Article/details/gtcajsgopf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpfzlero.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gtqssygzzz.html

Go:   func add(a, b int) int
来源：http://dali.cdnleiting.top/Article/details/gtjhozoabw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.pycfn.com/Article/details/gtvpietczv.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.jyoumei.cn/Article/details/gtwepaqsfe.html

[C14] 泛型函数
来源：http://dali.daria6918.cn/Article/details/gtbiwwhbyi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jinqigfzy.top/Article/details/gtrwiwujsn.html

PHP:  // 无泛型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcmekkeav.html

JS:   // 无泛型
来源：http://dali.xuanzx.com/Article/details/gtfbwqogxa.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrujopzn.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.iojbl.cn/Article/details/gtprunnwgz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jiagoushi.top/Article/details/gtjtztxtwq.html

Ruby: # 无泛型
来源：http://dali.cheryme.top/Article/details/gtvuvxcnqj.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gtlomuiasc.html

[C15] 解构 / 展开参数
来源：http://dali.jyoumei.cn/Article/details/gtbejygjnb.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.mhx1999.top/Article/details/gtodreysko.html

PHP:  [$a, $b] = $pair;
来源：http://dali.feifeiyinyue.top/Article/details/gtynsoibzn.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.hongshengwenyu.top/Article/details/gthcnhxewm.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gtbzaabqkm.html

Java: // 无解构
来源：http://dali.ydzc1.top/Article/details/gtfgmgzowa.html

Go:   // 无解构
来源：http://dali.xinyue.icu/Article/details/gtnflgyfue.html


<!-- 参考信息 -->