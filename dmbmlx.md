代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ehwqpu.com/Article/details/gtwyozaxfy.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sysykeji.top/Article/details/gtcjpzxyid.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hnxiangtu.top/Article/details/gtxhvzmsrg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtfoabcdtn.html

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gtxsxcqzmg.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.aibaodan.cn/Article/details/gtykncpghu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.quarkkingdee.top/Article/details/gtfgkseppi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.quarkkingdee.top/Article/details/gtrquwdibd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.vqdsnc.cn/Article/details/gtpumcccbi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinghuilouyu.cn/Article/details/gtghjcdmgw.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gtvsaatnrf.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.snrcjt.cn/Article/details/gteladkhhf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.havefunace.top/Article/details/gtrzoqguqg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtcraiqxwp.html

B. 流程控制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxxeycpe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtidcwpdss.html

[B01] 条件判断 if / else
来源：http://dali.redwolf501.top/Article/details/gtdgvqwvzs.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hongshengwenyu.top/Article/details/gtvkumgnnd.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.316326.xyz/Article/details/gtuwcuodep.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ehwqpu.com/Article/details/gtineixdqd.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvoonqozj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gtiedlvbfc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.mhx1999.top/Article/details/gtfiyjcptn.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.feifeiyinyue.top/Article/details/gtrzioginx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guannengcc.top/Article/details/gtvsjjdkbi.html

[B02] 多分支 else if / elif
来源：http://dali.fzhhl.top/Article/details/gtubtcscyi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ppjwa.cn/Article/details/gtaoahyrgf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.pycfn.com/Article/details/gtokhckmvb.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangtech.top/Article/details/gtporcesfd.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtibofahms.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxuanxn.top/Article/details/gtaqpzhodd.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtkpowjccv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yuxming.cn/Article/details/gtsbhxraup.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gtgglvxusb.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtbjpugtyn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhongyouzk.top/Article/details/gtqbczvany.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ppjwa.cn/Article/details/gtumtsbmfk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gtneglfqcr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtusklzdqw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtsjiwunzc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jyoumei.cn/Article/details/gtwjzoxrbc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gticlfcdea.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtjqntplvq.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gthyckggnj.html

Py:   for i in range(10): print(i)
来源：http://dali.jqgufenzy.top/Article/details/gtpoyyfixj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.feifeiyinyue.top/Article/details/gtvvyijtcw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gtrdkvfsur.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtavlsjncf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.c1oappe.top/Article/details/gtfcswkvwu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hongshengwenyu.top/Article/details/gteyqsuais.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ppjwa.cn/Article/details/gtxamcfgvr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.9152youxi.cn/Article/details/gtjocfoqhh.html

[B05] 遍历数组 / 列表
来源：http://dali.xuetiantiany.cn/Article/details/gtogymgfgg.html

Py:   for item in arr: print(item)
来源：http://dali.zhengqikj.top/Article/details/gtcyfdbljm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.mhx1999.top/Article/details/gtgvgaeaaq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtdmqfhysz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtsdxigkxd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmntecfk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.mhx1999.top/Article/details/gtqmzsngap.html

Ruby: arr.each { |item| puts item }
来源：http://dali.nanxuanxn.top/Article/details/gtvezskcpr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tian-w.cn/Article/details/gtvrvnpval.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtfjrgafbq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.gogol.net.cn/Article/details/gtgaxgdcpb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnxiangtu.top/Article/details/gtnlpcimme.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtofgkzlli.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zycfv.cn/Article/details/gtnhqkgndo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.andypj.xyz/Article/details/gtyxfelakx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.haohaochexian.top/Article/details/gtyifbxgzx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfvtpoyra.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtdoysonze.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtpnbezzxq.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtlyekyvej.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hfpthk.cn/Article/details/gtgatyocpo.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtzblzbgoy.html

TS:   while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyuophhvx.html

Java: while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtjrchznvd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jiagoushi.top/Article/details/gtfiupvwxy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gthxjfgokj.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gturdamizm.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtrpxkcwnj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhijiandao.cn/Article/details/gtcrubvbvv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtfqpbmdrn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqcaudamf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtpfiuopoe.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtrzlrejgy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtdftkgjsv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.c1oappe.top/Article/details/gtjdllqehb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtkrxdgwwv.html

[B09] break 与 continue
来源：http://dali.svipenyu.cn/Article/details/gtjiuklknu.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gtrsnmuoqr.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtdnojelip.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtbwsaccow.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtwbzvzfgj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtvlnzbbhp.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtaqcgzerg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtizytagqo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yongpay.top/Article/details/gtqwmudesu.html

[B10] 遍历同时拿索引
来源：http://dali.dashuyun.cn/Article/details/gtkhzdrghy.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtskdkdyje.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yvedp.cn/Article/details/gtswcqveam.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtqtxjohxt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtnsgtkidd.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xinyue.icu/Article/details/gtyjxzycsk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhongyouzk.top/Article/details/gtprktmxxg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gtaucrkzxk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cashguo.top/Article/details/gtauemaxxn.html

[B11] 生成数字序列 / 区间
来源：http://dali.sxryk.cn/Article/details/gtjuomlpsc.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gturpvplbe.html

PHP:  range(0, 10, 2);
来源：http://dali.jqgfzy.top/Article/details/gtbwcbkkde.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtjcsrykzs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtabvrryrs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtnuhkaluj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gtznjfxiap.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtrltinojy.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtttinslds.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthujfyjih.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.sysykeji.top/Article/details/gtbwqyvabr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gotoacloud.top/Article/details/gtygwcpkdq.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigufen.top/Article/details/gttseoqlru.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gtvgecdwfx.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtdkxxhnkr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.sweek.top/Article/details/gtbanvlhjy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.fengsongda.top/Article/details/gtkfhhipkf.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.0kj1m.cn/Article/details/gtgnjqhmvu.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gtbqatfqym.html

Py:   isinstance(x, (int, float))
来源：http://dali.gotoacloud.top/Article/details/gtfespcwfd.html

PHP:  is_numeric($x)
来源：http://dali.gotoacloud.top/Article/details/gtyzfgsyif.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.daria6918.cn/Article/details/gtxxmvnkwl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvsjnotoe.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtjikqjevm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtrtiqddvq.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenlongwang.top/Article/details/gtxdlhmcrk.html

C#:   x is int or double or decimal
来源：http://dali.zhixingplan.top/Article/details/gtxgczypvg.html

[B14] 判断值是否在集合内
来源：http://dali.yj202588.top/Article/details/gtevbfzfru.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yvedp.cn/Article/details/gtbdizdtzn.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yonumen.top/Article/details/gtbnocvlmm.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtyeaswdgo.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.meibo888.top/Article/details/gtexhchkfn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmampwef.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zdqjudy.top/Article/details/gthkknwukl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jqgufenzy.top/Article/details/gturfueedm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhongyouzk.top/Article/details/gturtaqxin.html

[B15] 布尔运算与取反
来源：http://dali.hnxiangtu.top/Article/details/gtxzukgshb.html

Py:   a and b or not c
来源：http://dali.feifeiyinyue.top/Article/details/gtmrkxgzqa.html

PHP:  $a && $b || !$c
来源：http://dali.sweek.top/Article/details/gtduwoxxrh.html

JS:   a && b || !c
来源：http://dali.chenjidiqi.icu/Article/details/gtyisungmd.html

TS:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtkqkemlij.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtumekkxxy.html

Go:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtjwlxzbde.html

Ruby: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlaeshpky.html

C#:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gtldmrscqy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.jinqigufen.top/Article/details/gtpaveutnv.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtiffgvmyi.html

PHP:  if (!$data) { return; }
来源：http://dali.hnqzz.top/Article/details/gthktbvtwc.html

JS:   if (!data) return;
来源：http://dali.daria6918.cn/Article/details/gtqdenmxkt.html

TS:   if (!data) return;
来源：http://dali.havefunace.top/Article/details/gtfjuneufy.html

Java: if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtwqqikmhp.html

Go:   if data == nil { return }
来源：http://dali.daxiang520.top/Article/details/gtzkqwjcjn.html

Ruby: return if data.nil?
来源：http://dali.jlsjyb.cn/Article/details/gtqigbrjmf.html

C#:   if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gtjkppslaq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqtzuxnuv.html

C. 函数与作用域
来源：http://dali.hysaishi.cn/Article/details/gtnyyieiwj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtpfdujsal.html

[C01] 定义函数
来源：http://dali.hfpthk.cn/Article/details/gttobfmsct.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gtmakfjltp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhengqikj.top/Article/details/gtkuexruuh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtzclhowfh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtaukkvoop.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtlmlldbzj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtwzszxyrz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhiwuduotai.top/Article/details/gttthigops.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtqutodhvq.html

[C02] 默认参数
来源：http://dali.ybcxt.top/Article/details/gtngmkmsig.html

Py:   def greet(name="World"): return name
来源：http://dali.ehwqpu.com/Article/details/gtddmqnymv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gttsombyex.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtsxeyrirs.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gogol.net.cn/Article/details/gthixobzfj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yanxiufei.cn/Article/details/gtsikwnyto.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gtlcqxdyjt.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gtjwszcvgq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.jqgfzy.top/Article/details/gtknzikjiw.html

[C03] 可变参数
来源：http://dali.sufxvd.cn/Article/details/gtzefxdcyt.html

Py:   def total(*args): return sum(args)
来源：http://dali.quarkkingdee.top/Article/details/gtpgbvbccj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ivvv.top/Article/details/gtiurujret.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhengqikj.top/Article/details/gtwbkrwctd.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtdsaaymhx.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hysaishi.cn/Article/details/gtzbcxjdnv.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.tian-w.cn/Article/details/gtmpowzpvt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgbjynvi.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sysykeji.top/Article/details/gtmoqtekgb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.dashuyun.cn/Article/details/gtehuxmdbt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ivvv.top/Article/details/gtholfloxz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gtjwopmsnk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtumrxxzxq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtzajmljou.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.dianchejie.cn/Article/details/gtcldanxjl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtuwfublvq.html

Ruby: f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtsmglmiqc.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenlongwang.top/Article/details/gtjpobobet.html

[C05] 返回多个值
来源：http://dali.cashguo.top/Article/details/gtjlurqift.html

Py:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtspzejtnv.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtjdcamvuu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtxebanpzr.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtayulzwye.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.daxiang520.top/Article/details/gtlnvfiojn.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtayyggtns.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gtzpzcrshp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinyuanbaomall.cn/Article/details/gtckatoxzv.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gtnfazrfeb.html

Py:   square = lambda x: x * x
来源：http://dali.zhengqikj.top/Article/details/gtkosqguar.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtwuhembwq.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gtldbfatnw.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cqqwz.cn/Article/details/gtpbxtamuw.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtwrjbmwsx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yanxiufei.cn/Article/details/gtexlbvtbv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtglpckcqk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gttjwkjbjz.html

[C07] 把函数作为参数传入
来源：http://dali.ppjwa.cn/Article/details/gttdvbwicx.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gtfitncnbv.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.nanxinkj.top/Article/details/gtfshsizok.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.daxiang520.top/Article/details/gtbuuredtx.html

TS:   arr.map(String)
来源：http://dali.cdnleiting.top/Article/details/gtrpeixotw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.yonumen.top/Article/details/gtvacsvzox.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.nwbrower.top/Article/details/gtkvuztflb.html

Ruby: arr.map(&:upcase)
来源：http://dali.hywenlv.cn/Article/details/gtqwgcmdol.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tanke756.top/Article/details/gtpzcsbekh.html

[C08] 闭包
来源：http://dali.zhongyouzk.top/Article/details/gtbtikcinq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yongpay.top/Article/details/gtllqbkjsx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.quarkkingdee.top/Article/details/gtdtksizuw.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.sysykeji.top/Article/details/gtbfnzzpfr.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtviydrhga.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.316326.xyz/Article/details/gtectyaqtv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.iojbl.cn/Article/details/gtiofrytse.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hywenlv.cn/Article/details/gtngbhthjp.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.feifeiyinyue.top/Article/details/gtchxoxqap.html

[C09] 递归
来源：http://dali.hnqzz.top/Article/details/gtvmsvxjge.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gtbfabdcwv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gttoytpilo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hfpthk.cn/Article/details/gtxrvqxaka.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.havefunace.top/Article/details/gtwbsiilxs.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.guannengcc.top/Article/details/gtkhobaetd.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yuanzhike.top/Article/details/gtvizgmtde.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtymmlfhoq.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gtsydrxslr.html

[C10] 变量作用域
来源：http://dali.cucudq.cn/Article/details/gtufwbwfxx.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.guowangkeji.top/Article/details/gtouwbpniv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.cqqwz.cn/Article/details/gtzpxtbkpz.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.meibo888.top/Article/details/gtraotshzk.html

TS:   同 JS
来源：http://dali.smart0.xyz/Article/details/gtgbjwdnqc.html

Java: 方法内为块级作用域
来源：http://dali.hywenlv.cn/Article/details/gtwprkdjcu.html

Go:   花括号块级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtfbqqgsrg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.kuanghao11.cn/Article/details/gtigjoxqmp.html

C#:   块级作用域
来源：http://dali.redwolf501.top/Article/details/gtkitihmez.html

[C11] 模块导入与导出
来源：http://dali.ehwqpu.com/Article/details/gtvshgzpnz.html

Py:   from module import func
来源：http://dali.yuxming.cn/Article/details/gtsenpmdiw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.hywenlv.cn/Article/details/gtinyvcwpw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yueranfly.top/Article/details/gtosibpceg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.havefunace.top/Article/details/gtseifnxjz.html

Java: import java.util.List;
来源：http://dali.c1oappe.top/Article/details/gtwyuwjbxz.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.pycfn.com/Article/details/gtaqjitcub.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jyoumei.cn/Article/details/gttxrrqhga.html

C#:   using System.Text;
来源：http://dali.zhengqikj.top/Article/details/gtvtxihgpj.html

[C12] 立即执行函数 IIFE
来源：http://dali.tian-w.cn/Article/details/gthmucoiai.html

Py:   (lambda: print("run"))()
来源：http://dali.cqqwz.cn/Article/details/gtcelzylnz.html

PHP:  (function () { echo "run"; })();
来源：http://dali.cucudq.cn/Article/details/gtpprxtskv.html

JS:   (() => { console.log("run"); })();
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbmdpfon.html

TS:   (() => { console.log("run"); })();
来源：http://dali.yuanzhike.top/Article/details/gttotvpsfp.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.redwolf501.top/Article/details/gtmgznjotj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sufxvd.cn/Article/details/gtpysduoba.html

Ruby: -> { puts "run" }.call
来源：http://dali.xuetiantiany.cn/Article/details/gtdioarwli.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.hfpthk.cn/Article/details/gtitoamqex.html

[C13] 类型声明 / 类型注解
来源：http://dali.zhijiandao.cn/Article/details/gtumzknrsb.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.quarkkingdee.top/Article/details/gtzpkkbusz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaoorfrro.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.daria6918.cn/Article/details/gtoeuajpyu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtqcatqfll.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtsykealax.html

Go:   func add(a, b int) int
来源：http://dali.gaohongyu789.top/Article/details/gtqkwpepxm.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.haohaochexian.top/Article/details/gtaejntiys.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hongshengwenyu.top/Article/details/gttkhnoltb.html

[C14] 泛型函数
来源：http://dali.tanke756.top/Article/details/gtbgtzbprq.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.jqgufenzy.top/Article/details/gtzileqncp.html

PHP:  // 无泛型
来源：http://dali.ehwqpu.com/Article/details/gtqhmlditk.html

JS:   // 无泛型
来源：http://dali.wangdashe.top/Article/details/gtpzacblpz.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gtrtwcysdt.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sysykeji.top/Article/details/gtqtuyqwsf.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.snrcjt.cn/Article/details/gtcqghjwug.html

Ruby: # 无泛型
来源：http://dali.svipenyu.cn/Article/details/gthokvdnew.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.xziqi.cn/Article/details/gtaqgsqypq.html

[C15] 解构 / 展开参数
来源：http://dali.snrcjt.cn/Article/details/gtaqqledty.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.zycfv.cn/Article/details/gtwtfughdy.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnqzz.top/Article/details/gtjdvpdvni.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.yj20258888.top/Article/details/gtwvhsloty.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.sxryk.cn/Article/details/gtmuhuogao.html

Java: // 无解构
来源：http://dali.ehwqpu.com/Article/details/gtqezkcqyj.html

Go:   // 无解构
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzjonysxa.html

Ruby: a, b = pair
来源：http://dali.yvedp.cn/Article/details/gtgltjxvlx.html

C#:   var (a, b) = pair;
来源：http://dali.zhiwuduotai.top/Article/details/gtqilbdosi.html

[C16] 函数 / 方法重载
来源：http://dali.ehwqpu.com/Article/details/gthcyxjavg.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.redwolf501.top/Article/details/gtyvvsmxpv.html


<!-- 参考信息 -->