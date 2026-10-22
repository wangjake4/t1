代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jyoumei.cn/Article/details/gt2zadyemky.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gt2klgljwyj.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.xuanzx.com/Article/details/gt2nysmdlhp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.bjfxy.top/Article/details/gt2ekkdaoci.html

[A26] 类型转换总览
来源：http://dali.sxryk.cn/Article/details/gt2lperslup.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gt2joqiiuti.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gt2yugkozbb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mpvoqiyo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hywenlv.cn/Article/details/gt2ffxvhyej.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.tian-w.cn/Article/details/gt2aflsrnnp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tian-w.cn/Article/details/gt2sblhkabx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jlsjyb.cn/Article/details/gt2bapghpic.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gt2wcxtypgs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gt2vhmpplnn.html

B. 流程控制
来源：http://dali.nwbrower.top/Article/details/gt2drhcpmlx.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2vgjxkmys.html

[B01] 条件判断 if / else
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fmqcosuv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ndcvcpfn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ghlhlqro.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2zvgpxvyk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gt2viwdtkzz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gt2zbpnfoie.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gt2uxlayupm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2zlctncgi.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2olwvbwpb.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dqcmaohx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gt2ultbhizw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.bjfxy.top/Article/details/gt2tlpplscj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gt2nlfqjxdh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.kuanghao11.cn/Article/details/gt2iwghlbur.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2exjoegoz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gt2pcivthkm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gt2njgfnlfq.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gt2xusywfvr.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gt2aygkmgdo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hfpthk.cn/Article/details/gt2ppqeavyy.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2byapsilu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zsypbuxw.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2vhxqwojc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lmkbwgfm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ivvv.top/Article/details/gt2phvwaovf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gt2zucyjrpi.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yuxming.cn/Article/details/gt2dkzfayne.html

[B04] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2mwouabcu.html

Py:   for i in range(10): print(i)
来源：http://dali.yonumen.top/Article/details/gt2ntmjvone.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gotoacloud.top/Article/details/gt2jppcuixy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gt2odsuzjax.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gt2pqnjrerg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2wmqzeadb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gt2hrqikeze.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dianchejie.cn/Article/details/gt2pxlorxnq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2clgtmxfm.html

[B05] 遍历数组 / 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oynrmypk.html

Py:   for item in arr: print(item)
来源：http://dali.cashguo.top/Article/details/gt2gyhyguvp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gt2jrezhlvq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2xbsloylq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2uxtecgma.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xziqi.cn/Article/details/gt2aewbozhe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gt2rlnuxmdr.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zycfv.cn/Article/details/gt2hdczcxxt.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigfzy.top/Article/details/gt2qkilurfz.html

[B06] 遍历字典 / 对象
来源：http://dali.0kj1m.cn/Article/details/gt2oxuoevex.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnqzz.top/Article/details/gt2mftgirek.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hysaishi.cn/Article/details/gt2zffteabt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2exkccdzd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gt2rdicwlnx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jianghu66.top/Article/details/gt2xqzhpszi.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gt2bubzqcvr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ydzc1.top/Article/details/gt2wakkdloz.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gt2qzmjxyte.html

[B07] while 循环
来源：http://dali.zhongyouzk.top/Article/details/gt2bdsvrvbz.html

Py:   while i < 10: i += 1
来源：http://dali.hysaishi.cn/Article/details/gt2ddgsuyfh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2jndyqffl.html

JS:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zpstprkk.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigfzy.top/Article/details/gt2sjuluyar.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gt2dwzccmsb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.chenjidiqi.icu/Article/details/gt2cyqjzfmi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.svipenyu.cn/Article/details/gt2dieuveqe.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2cstnujae.html

[B08] do-while（至少执行一次）
来源：http://dali.bjfxy.top/Article/details/gt2yfmvicbq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yangfankeji.com/Article/details/gt2dwedkbad.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.redwolf501.top/Article/details/gt2tmnyigaa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gt2onhoyyqw.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gt2mcxwjafh.html

Java: do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2zblmjsll.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.snrcjt.cn/Article/details/gt2joddoojk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yuanzhike.top/Article/details/gt2bstxgmlb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gt2qnlivqrz.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gt2uqqbcphh.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhoulong.xyz/Article/details/gt2ewlqqijc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2drhpctzh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yubczrpu.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xuanzx.com/Article/details/gt2czvkgxoj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2naclcito.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jiagoushi.top/Article/details/gt2qomlfvva.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2qiifvmap.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gt2qpbyhfbc.html

[B10] 遍历同时拿索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dacylrmm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fengsongda.top/Article/details/gt2osznusfz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gt2lbxbqnkg.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2pagifclh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.cheryme.top/Article/details/gt2crntjapb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adfkdtzf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xinyue.icu/Article/details/gt2wqqdpgwp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.c1oappe.top/Article/details/gt2bbnbejhs.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.smart0.xyz/Article/details/gt2zrhqegrh.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gt2iwcchjzl.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenzaomai.com/Article/details/gt2tunogtpf.html

PHP:  range(0, 10, 2);
来源：http://dali.sysykeji.top/Article/details/gt2yyjaoike.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj20258.top/Article/details/gt2urggpyvb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gt2vixuswpj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sxryk.cn/Article/details/gt2kihphvpy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aizwys.cn/Article/details/gt2qkjjogkj.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gt2wcqfsaek.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.sysykeji.top/Article/details/gt2vjjwonyl.html

[B12] 跳出多层循环
来源：http://dali.gaohongyu789.top/Article/details/gt2zkckkqnu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gt2gynydltm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gt2jtasvywk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gt2vtgjerlu.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gt2fngtsxfv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gt2nsppmwiv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gt2rrzgyquz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yueranfly.top/Article/details/gt2wzkllcdt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gt2ivdefayu.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gt2nznamfpv.html

Py:   isinstance(x, (int, float))
来源：http://dali.guowangkeji.top/Article/details/gt2wbferbtk.html

PHP:  is_numeric($x)
来源：http://dali.ybcxt.top/Article/details/gt2yyeswrpl.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqxjklur.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.chenjidiqi.icu/Article/details/gt2yygnzrcf.html

Java: x instanceof Number
来源：http://dali.birdmap.top/Article/details/gt2oozjjtet.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.kuanghao11.cn/Article/details/gt2epxvkxcb.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oooosbxc.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gt2bodhajgc.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigufen.top/Article/details/gt2zbcdkojx.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.guannengcc.top/Article/details/gt2aitkuhjl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.havefunace.top/Article/details/gt2bgeblvio.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2orqiluuj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.guannengcc.top/Article/details/gt2htqihhsg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2ydiglcwr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gt2zgwermot.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2qjybefuw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gt2achrkfsl.html

[B15] 布尔运算与取反
来源：http://dali.zhoulong.xyz/Article/details/gt2nnzqmfni.html

Py:   a and b or not c
来源：http://dali.nwbrower.top/Article/details/gt2tscpycvg.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2wwunagsb.html

JS:   a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2jhvavxlt.html

TS:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2qruyrizu.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gt2ftpoijue.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bhawrbwr.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gt2ntzkhvic.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2kfuribve.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.bjfxy.top/Article/details/gt2sypmyfyz.html

Py:   if not data: return
来源：http://dali.chenzaomai.com/Article/details/gt2bxmkjkvt.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2aknlspwc.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gt2azoynzix.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gt2ynbwihco.html

Java: if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2suexefug.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gt2czsqhsta.html

Ruby: return if data.nil?
来源：http://dali.shzxlz.cn/Article/details/gt2xrzpbrba.html

C#:   if (data == null) return;
来源：http://dali.guannengcc.top/Article/details/gt2lvgptolc.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2msiiovof.html

C. 函数与作用域
来源：http://dali.cheryme.top/Article/details/gt2mabohoct.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gt2rwmjriqu.html

[C01] 定义函数
来源：http://dali.zhixingplan.top/Article/details/gt2ukfcysuy.html

Py:   def add(a, b): return a + b
来源：http://dali.ybcxt.top/Article/details/gt2vqpntrld.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2urprwhil.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sysykeji.top/Article/details/gt2qwduowkw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gt2ciorhouh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2qqoqsefv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cqqwz.cn/Article/details/gt2jgnghkqi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gt2jtpwikmp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gt2xzeuzlym.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2llqrbtkg.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258.top/Article/details/gt2upfkqjqc.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.tian-w.cn/Article/details/gt2sljqwkje.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2oauaxlrn.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ivvv.top/Article/details/gt2mmtfptwi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shuidangran.top/Article/details/gt2bbzhqyfo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gt2fseqvssq.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gt2byrskeqo.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hywenlv.cn/Article/details/gt2wwylxytv.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2escrgwrd.html

Py:   def total(*args): return sum(args)
来源：http://dali.jlsjyb.cn/Article/details/gt2nwrqqqlb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.jqgfzy.top/Article/details/gt2fzgxmiph.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yanxiufei.cn/Article/details/gt2ajpznlld.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gt2mpduzjog.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenjidiqi.icu/Article/details/gt2icmbifze.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2xytwgmeq.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.nanxuanxn.top/Article/details/gt2potnxops.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gzhubu.top/Article/details/gt2zleiuksr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gt2sprrtrmv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shuidangran.top/Article/details/gt2jiogoeqx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhongyouzk.top/Article/details/gt2kjisytgr.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hfpthk.cn/Article/details/gt2zcpeelvw.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gt2myafiwhs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.gogol.net.cn/Article/details/gt2txswnbed.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2drjkmqaz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2frrtkkjy.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gt2bvpngnex.html

[C05] 返回多个值
来源：http://dali.shzxlz.cn/Article/details/gt2olgzwxwq.html

Py:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2endighex.html

PHP:  return [$a, $b];
来源：http://dali.dashuyun.cn/Article/details/gt2akqylseg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hywenlv.cn/Article/details/gt2qbtbghnp.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gt2pqjppynt.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hysaishi.cn/Article/details/gt2scohaahh.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gt2yvemgvff.html

Ruby: return a, b
来源：http://dali.yj202588.top/Article/details/gt2zbuqifdn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gt2zwnyfegb.html

[C06] 匿名函数 / lambda
来源：http://dali.fengsongda.top/Article/details/gt2zkzzjhcd.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2mabqehxt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhongyouzk.top/Article/details/gt2lrmvpkns.html

JS:   const square = x => x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2yqblrwbv.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.cashguo.top/Article/details/gt2udfwxdpf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhoulong.xyz/Article/details/gt2ydyksthe.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.sysykeji.top/Article/details/gt2wquxzwvk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.yongpay.top/Article/details/gt2afoftoot.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.redwolf501.top/Article/details/gt2jmraxxza.html

[C07] 把函数作为参数传入
来源：http://dali.pycfn.com/Article/details/gt2zieojxjm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.redwolf501.top/Article/details/gt2eiwwjxyz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yuxming.cn/Article/details/gt2sjenmlql.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.sysykeji.top/Article/details/gt2dlmjfpts.html

TS:   arr.map(String)
来源：http://dali.jinqigfzy.top/Article/details/gt2rmbdromv.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2gwqwhxbv.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj20258888.top/Article/details/gt2syhofdaj.html

Ruby: arr.map(&:upcase)
来源：http://dali.quarkkingdee.top/Article/details/gt2ckhedpao.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.jlsjyb.cn/Article/details/gt2lknfmcqj.html

[C08] 闭包
来源：http://dali.iojbl.cn/Article/details/gt2ikxrwoka.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gt2xcgdwyfp.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuanzx.com/Article/details/gt2vcikapuq.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gt2riajhdwb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.daxiang520.top/Article/details/gt2bqmdqwcc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sufxvd.cn/Article/details/gt2ejaqhgzw.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.hnxiangtu.top/Article/details/gt2ccwnhzqp.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.ivvv.top/Article/details/gt2vedzlzvr.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2pgwqhggg.html

[C09] 递归
来源：http://dali.yuanzhike.top/Article/details/gt2siidymnq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.sysykeji.top/Article/details/gt2tzpjfgoi.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hpcjfpqf.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.vqdsnc.cn/Article/details/gt2tyuskbio.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rwekxqbw.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shzxlz.cn/Article/details/gt2hzkqbnko.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.hywenlv.cn/Article/details/gt2qhohkpqn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jianghu66.top/Article/details/gt2ungsikhh.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ppjwa.cn/Article/details/gt2hbosznba.html

[C10] 变量作用域
来源：http://dali.wangdashe.top/Article/details/gt2sodhukcj.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yj20258.top/Article/details/gt2wjojjivu.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.c1oappe.top/Article/details/gt2wexmknhn.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.guannengcc.top/Article/details/gt2wnxlinsz.html

TS:   同 JS
来源：http://dali.redwolf501.top/Article/details/gt2omuaojua.html

Java: 方法内为块级作用域
来源：http://dali.aibaodan.cn/Article/details/gt2clhoutyl.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2kjzhiqmp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jqgufenzy.top/Article/details/gt2ehvefyqd.html

C#:   块级作用域
来源：http://dali.yuxming.cn/Article/details/gt2uxdciuhk.html

[C11] 模块导入与导出
来源：http://dali.svipenyu.cn/Article/details/gt2iccrwlxk.html

Py:   from module import func
来源：http://dali.pengpengdd.cyou/Article/details/gt2quyssxeb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.ivvv.top/Article/details/gt2uwczecfw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2avqazqpg.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.0kj1m.cn/Article/details/gt2tiydijcv.html

Java: import java.util.List;
来源：http://dali.yj20258888.top/Article/details/gt2jdogmdka.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2dmcnpqth.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tbcocigd.html

C#:   using System.Text;
来源：http://dali.xylfe.cn/Article/details/gt2oxbsclau.html

[C12] 立即执行函数 IIFE
来源：http://dali.yueranfly.top/Article/details/gt2xurgkvwj.html

Py:   (lambda: print("run"))()
来源：http://dali.xinyue.icu/Article/details/gt2ntcawtyw.html

PHP:  (function () { echo "run"; })();
来源：http://dali.xuanzx.com/Article/details/gt2sowfrtfo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.kuanghao11.cn/Article/details/gt2pzckdmct.html

TS:   (() => { console.log("run"); })();
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2olsepuwz.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.sweek.top/Article/details/gt2gicnfmos.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.sweek.top/Article/details/gt2vanmyqyr.html

Ruby: -> { puts "run" }.call
来源：http://dali.nanxinkj.top/Article/details/gt2tqzkbkko.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2insoshpy.html

[C13] 类型声明 / 类型注解
来源：http://dali.guannengcc.top/Article/details/gt2culfludg.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.cdnleiting.top/Article/details/gt2zbsiqdtu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2ldtuksle.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.xinyue.icu/Article/details/gt2movfubaw.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2badkmctc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mnhwpypg.html

Go:   func add(a, b int) int
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltamtpyt.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.ivvv.top/Article/details/gt2ctgqntad.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yuanzhike.top/Article/details/gt2fsoqvfzu.html

[C14] 泛型函数
来源：http://dali.xylfe.cn/Article/details/gt2rofybvqc.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.yonumen.top/Article/details/gt2jsjmnmhe.html

PHP:  // 无泛型
来源：http://dali.zhoulong.xyz/Article/details/gt2nsfrswai.html

JS:   // 无泛型
来源：http://dali.daria6918.cn/Article/details/gt2sjnymkta.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.snrcjt.cn/Article/details/gt2kaocusxm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2wvlpzsut.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daria6918.cn/Article/details/gt2gobtfzxr.html

Ruby: # 无泛型
来源：http://dali.0kj1m.cn/Article/details/gt2tneoqyhw.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.sweek.top/Article/details/gt2muhxygyq.html

[C15] 解构 / 展开参数
来源：http://dali.zhixingplan.top/Article/details/gt2zaiqcrtr.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.xinyue.icu/Article/details/gt2fvfzeonc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.hnxiangtu.top/Article/details/gt2elovexqf.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.tianlin.xyz/Article/details/gt2oxgdmtup.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.bjfxy.top/Article/details/gt2dxdbfejt.html

Java: // 无解构
来源：http://dali.meibo888.top/Article/details/gt2ehnsfbgu.html

Go:   // 无解构
来源：http://dali.316326.xyz/Article/details/gt2ezyyhhuv.html

Ruby: a, b = pair
来源：http://dali.bjfxy.top/Article/details/gt2hcjetzmm.html

C#:   var (a, b) = pair;
来源：http://dali.quarkkingdee.top/Article/details/gt2olrsljpn.html

[C16] 函数 / 方法重载
来源：http://dali.cqqwz.cn/Article/details/gt2htqoxzhi.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.wangdashe.top/Article/details/gt2ugajsprb.html


<!-- 参考信息 -->