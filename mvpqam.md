代发 wailian999

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gt2ijfnbdgz.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.xuanzx.com/Article/details/gt2mkywzbuu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lmpptayd.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gt2obcrbobo.html

TS:   Number() String() Boolean() x as number
来源：http://dali.daxiang520.top/Article/details/gt2lzvfxzea.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.iojbl.cn/Article/details/gt2cbreeckg.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.9152youxi.cn/Article/details/gt2zxuszdtr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gt2awlhddqw.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jinqigufen.top/Article/details/gt2wmmwyxlq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2evzqoyzx.html

B. 流程控制
来源：http://dali.fengsongda.top/Article/details/gt2vckrngaw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2zporbhai.html

[B01] 条件判断 if / else
来源：http://dali.shangyingyoupin.top/Article/details/gt2hezfqelj.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yuanzhike.top/Article/details/gt2xnpdbgba.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.meibo888.top/Article/details/gt2lpnajjra.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2wyjbdril.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2jwocepnf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gt2hqtwodau.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gt2dkcwgvyr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenzaomai.com/Article/details/gt2yzosdawm.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gt2clhabljc.html

[B02] 多分支 else if / elif
来源：http://dali.haohaochexian.top/Article/details/gt2chxsbsoi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.quarkkingdee.top/Article/details/gt2oofhzyov.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2thhyxckj.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2fuzfrbte.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gt2dflyxuau.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sufxvd.cn/Article/details/gt2ouxrsdqe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.bjfxy.top/Article/details/gt2pwkumsft.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.daria6918.cn/Article/details/gt2doatmqlk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenjidiqi.icu/Article/details/gt2wtiembpz.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gt2pehtibso.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hongshengwenyu.top/Article/details/gt2egxwlszz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cashguo.top/Article/details/gt2mcryozfy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2qdraeigf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2nfyypsnw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.smart0.xyz/Article/details/gt2wpoydkps.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.birdmap.top/Article/details/gt2hnneyuep.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2oaghpovz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cucudq.cn/Article/details/gt2rbjuqfjr.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2kratmmnk.html

Py:   for i in range(10): print(i)
来源：http://dali.316326.xyz/Article/details/gt2covhzunz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhixingplan.top/Article/details/gt2ifwudhhb.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2nillabff.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gt2rbmeapdy.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qukyqlqd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yonumen.top/Article/details/gt2jwtmqjgz.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jlsjyb.cn/Article/details/gt2phxjbcmo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gt2mtnrhvom.html

[B05] 遍历数组 / 列表
来源：http://dali.xinyue.icu/Article/details/gt2ubmaswnx.html

Py:   for item in arr: print(item)
来源：http://dali.nanxuanxn.top/Article/details/gt2cjvaekjo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuanzx.com/Article/details/gt2zhyzybpn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sweek.top/Article/details/gt2emxnlclz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2vsgfhzcm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yonumen.top/Article/details/gt2ybqegnbd.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shzxlz.cn/Article/details/gt2jcfwqmim.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gt2iqhxzaxn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gt2nyckwqsf.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2gzycxohr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2ajkcrzcd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.sufxvd.cn/Article/details/gt2buyraioh.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zdqjudy.top/Article/details/gt2rafuypop.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tlbzztjw.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gt2ndickeij.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuanzx.com/Article/details/gt2sriskuxd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxinkj.top/Article/details/gt2obkzgjll.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.guannengcc.top/Article/details/gt2ikhksbcb.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gt2qchfndad.html

Py:   while i < 10: i += 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qwzlsnxl.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cashguo.top/Article/details/gt2diebeduc.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gt2xqqcxnst.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2mspliyuj.html

Java: while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gt2rkbzaokv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2wfgvezvw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hfpthk.cn/Article/details/gt2wdzwuohh.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2xmceevkx.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gt2uzcswlym.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gt2dbhjlhiw.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.cdnleiting.top/Article/details/gt2ranytwhp.html

JS:   do { i++; } while (i < 10);
来源：http://dali.0kj1m.cn/Article/details/gt2rjzkktoz.html

TS:   do { i++; } while (i < 10);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iumxvape.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2acmpinut.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssjcfhib.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jqgfzy.top/Article/details/gt2kelkcliu.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gt2oxygmjqb.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gt2wnrbwwlc.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gt2nsmihaos.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gt2bkeaiuyh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2ukrvbeoi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gt2auhtxqxy.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2amhqqosz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.birdmap.top/Article/details/gt2ddirwirg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tanke756.top/Article/details/gt2qbiodtjj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gt2sfbeetgk.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gt2jezwcctt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2hoglcrts.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2cagwuofk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2stdlrptr.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gt2obqgsdsh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gt2dclutsuv.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2arcdiohp.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.nwbrower.top/Article/details/gt2wrgkrafk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gt2dgtkoqwu.html

[B11] 生成数字序列 / 区间
来源：http://dali.gaohongyu789.top/Article/details/gt2jrhijnvt.html

Py:   list(range(0, 10, 2))
来源：http://dali.fzhhl.top/Article/details/gt2tmyylqwn.html

PHP:  range(0, 10, 2);
来源：http://dali.tianlin.xyz/Article/details/gt2wekzzxwo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gt2qtwefkbx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhongyouzk.top/Article/details/gt2qboyvymr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gt2zehbqicr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gt2mucgokln.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kvngzvai.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.smart0.xyz/Article/details/gt2klmxmzfk.html

[B12] 跳出多层循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2miuatwwy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yangfankeji.com/Article/details/gt2zemjbrdc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2nuedjrwo.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.quarkkingdee.top/Article/details/gt2ajuwgcml.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.smart0.xyz/Article/details/gt2bhndrxul.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gt2jmjfqdjg.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yueranfly.top/Article/details/gt2fjsgntnn.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.andypj.xyz/Article/details/gt2xgwwcxrj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gt2twnfkjsy.html

[B13] 判断是否为数字
来源：http://dali.zycfv.cn/Article/details/gt2bsrvbgtb.html

Py:   isinstance(x, (int, float))
来源：http://dali.shangyingyoupin.top/Article/details/gt2ugkmltoj.html

PHP:  is_numeric($x)
来源：http://dali.bjfxy.top/Article/details/gt2jaedqhyf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gt2iodmaazq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikmggwkp.html

Java: x instanceof Number
来源：http://dali.yongpay.top/Article/details/gt2xvlebdjx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ivvv.top/Article/details/gt2ngcvtvuc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.snrcjt.cn/Article/details/gt2mwpstoli.html

C#:   x is int or double or decimal
来源：http://dali.zhijiandao.cn/Article/details/gt2fbmxfrtp.html

[B14] 判断值是否在集合内
来源：http://dali.yanxiufei.cn/Article/details/gt2qievzpqy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gt2frejnhfv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jlsjyb.cn/Article/details/gt2imlkesyc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yongpay.top/Article/details/gt2hplamdkf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gt2yglkzogo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shuidangran.top/Article/details/gt2ervwbirq.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nwbrower.top/Article/details/gt2lzgfkrnb.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.sweek.top/Article/details/gt2pxclnrpk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gt2pbobhwjo.html

[B15] 布尔运算与取反
来源：http://dali.hammf.cn/Article/details/gt2eoiamxto.html

Py:   a and b or not c
来源：http://dali.hysaishi.cn/Article/details/gt2ewngyxxp.html

PHP:  $a && $b || !$c
来源：http://dali.xuetiantiany.cn/Article/details/gt2aqgqribj.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gt2swzgripp.html

TS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gt2wfuszefz.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2plhdesye.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgpgadlz.html

Ruby: a && b || !c
来源：http://dali.pengpengdd.cyou/Article/details/gt2yvbefisy.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2kihgursg.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2etktbuxs.html

Py:   if not data: return
来源：http://dali.mhx1999.top/Article/details/gt2gppucojs.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gt2lfpigwsc.html

JS:   if (!data) return;
来源：http://dali.sufxvd.cn/Article/details/gt2mymzfcwk.html

TS:   if (!data) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2erzjojwz.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gt2apzxbfwd.html

Go:   if data == nil { return }
来源：http://dali.jqgfzy.top/Article/details/gt2qwvnwivf.html

Ruby: return if data.nil?
来源：http://dali.yuxming.cn/Article/details/gt2svpdoqng.html

C#:   if (data == null) return;
来源：http://dali.cqqwz.cn/Article/details/gt2mpcsqcen.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2naqwlznv.html

C. 函数与作用域
来源：http://dali.jinqigufen.top/Article/details/gt2fsqlzwzy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2ymtrhron.html

[C01] 定义函数
来源：http://dali.mhx1999.top/Article/details/gt2wfbhqjvw.html

Py:   def add(a, b): return a + b
来源：http://dali.yuxming.cn/Article/details/gt2hspwjnwe.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2ehkneazm.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2zqoffmtb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gt2dlepbqai.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hfpthk.cn/Article/details/gt2xchdpwpu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xziqi.cn/Article/details/gt2aigltpco.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuxming.cn/Article/details/gt2wjngzdvo.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gt2tzesxcib.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2betqalyx.html

Py:   def greet(name="World"): return name
来源：http://dali.dianchejie.cn/Article/details/gt2vjcchsge.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cheryme.top/Article/details/gt2ddfhixfz.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.snrcjt.cn/Article/details/gt2cfmclvls.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gt2zwspgspt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.tian-w.cn/Article/details/gt2rzoishpj.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gt2inqzjqwd.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenlongwang.top/Article/details/gt2beyknuea.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gt2eauqiztk.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2wvvbxaag.html

Py:   def total(*args): return sum(args)
来源：http://dali.guannengcc.top/Article/details/gt2nkgqkpxb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aizwys.cn/Article/details/gt2bpwqkltc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hfpthk.cn/Article/details/gt2ygxkurgs.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gt2pujqobjl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gotoacloud.top/Article/details/gt2zjgrdsul.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shuidangran.top/Article/details/gt2nkhfzpgj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gt2cfkboydg.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.daxiang520.top/Article/details/gt2qxouojdg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gt2gatazoyy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ppjwa.cn/Article/details/gt2qazbjiuy.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gt2hebxkeug.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ehwqpu.com/Article/details/gt2acukydij.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gt2lkqoebfx.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.c1oappe.top/Article/details/gt2pkhyypup.html

Go:   // 无：用配置结构体参数
来源：http://dali.jianghu66.top/Article/details/gt2ltdrbekx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrhfyheu.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangdashe.top/Article/details/gt2fqxdbrhl.html

[C05] 返回多个值
来源：http://dali.gaohongyu789.top/Article/details/gt2vuxhnvmv.html

Py:   return a, b
来源：http://dali.yj20258888.top/Article/details/gt2xykuoyad.html

PHP:  return [$a, $b];
来源：http://dali.xuetiantiany.cn/Article/details/gt2wbehhzqx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gt2uhtejrlb.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gt2xjfuztgf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gt2ctxcthfm.html

Go:   return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2jowwbhgx.html

Ruby: return a, b
来源：http://dali.bjfxy.top/Article/details/gt2hhumncwu.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xziqi.cn/Article/details/gt2sajojzgk.html

[C06] 匿名函数 / lambda
来源：http://dali.zycfv.cn/Article/details/gt2febuwebu.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gt2xoefvxar.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.havefunace.top/Article/details/gt2ckwsqjwn.html

JS:   const square = x => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gt2hedwldtd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2nrraeaha.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2bweoqexr.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenlongwang.top/Article/details/gt2yxskqdrl.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cashguo.top/Article/details/gt2wbtzmqco.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gt2suwekxrv.html

[C07] 把函数作为参数传入
来源：http://dali.yonumen.top/Article/details/gt2fmahphmd.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gelqqkvj.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.shuidangran.top/Article/details/gt2bxppmnar.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.vqdsnc.cn/Article/details/gt2wvfztxvz.html

TS:   arr.map(String)
来源：http://dali.cucudq.cn/Article/details/gt2hohsmrnw.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xsszlraf.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gt2frhcztle.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgfzy.top/Article/details/gt2tvxsdjog.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.aizwys.cn/Article/details/gt2lwfqrore.html

[C08] 闭包
来源：http://dali.ydzc1.top/Article/details/gt2azmlplxo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dashuyun.cn/Article/details/gt2skbpuqaf.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.aizwys.cn/Article/details/gt2cnawnutv.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gt2nfxxmasg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.sxryk.cn/Article/details/gt2jjyklgkj.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.kuanghao11.cn/Article/details/gt2lvmwnuhv.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shangyingyoupin.top/Article/details/gt2rgahjghd.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.hongshengwenyu.top/Article/details/gt2gdwplcpf.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gt2ufyzbuco.html

[C09] 递归
来源：http://dali.hysaishi.cn/Article/details/gt2glhbkppe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.dashuyun.cn/Article/details/gt2nodvavwv.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2pwtkfevm.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.daria6918.cn/Article/details/gt2fzputioy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.9152youxi.cn/Article/details/gt2qbqqsedj.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jinqigfzy.top/Article/details/gt2takqljcc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gt2jgypgugo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2bbjxqukb.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gt2fgcwmpuw.html

[C10] 变量作用域
来源：http://dali.sweek.top/Article/details/gt2ayeekxag.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gt2phavipfb.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hongshengwenyu.top/Article/details/gt2ojinyrlt.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cashguo.top/Article/details/gt2ifrmldwj.html

TS:   同 JS
来源：http://dali.pycfn.com/Article/details/gt2qqackjmm.html

Java: 方法内为块级作用域
来源：http://dali.birdmap.top/Article/details/gt2jvwktrdk.html

Go:   花括号块级作用域
来源：http://dali.xziqi.cn/Article/details/gt2tvsasjau.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yj20258888.top/Article/details/gt2ostzbnmz.html

C#:   块级作用域
来源：http://dali.yj20258.top/Article/details/gt2fiobupeb.html

[C11] 模块导入与导出
来源：http://dali.ybcxt.top/Article/details/gt2tbauqkcf.html

Py:   from module import func
来源：http://dali.ivvv.top/Article/details/gt2natzcctz.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.sweek.top/Article/details/gt2xveaatao.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zdqjudy.top/Article/details/gt2qfucbbrn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.ppjwa.cn/Article/details/gt2lovlbntr.html

Java: import java.util.List;
来源：http://dali.jlsjyb.cn/Article/details/gt2bnjbpkah.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnxiangtu.top/Article/details/gt2jmvfrjed.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.nanxuanxn.top/Article/details/gt2gdusidzm.html

C#:   using System.Text;
来源：http://dali.nwbrower.top/Article/details/gt2tbtcgahl.html

[C12] 立即执行函数 IIFE
来源：http://dali.fengsongda.top/Article/details/gt2pdvcknga.html

Py:   (lambda: print("run"))()
来源：http://dali.quarkkingdee.top/Article/details/gt2ttynuxbk.html

PHP:  (function () { echo "run"; })();
来源：http://dali.havefunace.top/Article/details/gt2yqkxxrxl.html

JS:   (() => { console.log("run"); })();
来源：http://dali.xziqi.cn/Article/details/gt2smppyteh.html

TS:   (() => { console.log("run"); })();
来源：http://dali.9152youxi.cn/Article/details/gt2qvqdhaqg.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.havefunace.top/Article/details/gt2swksgefm.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.aizwys.cn/Article/details/gt2ueiyqoqq.html

Ruby: -> { puts "run" }.call
来源：http://dali.shzxlz.cn/Article/details/gt2ekzmrzon.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrcowfeb.html

[C13] 类型声明 / 类型注解
来源：http://dali.yj20258.top/Article/details/gt2rukoqfnh.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.9152youxi.cn/Article/details/gt2uxotxtup.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.meibo888.top/Article/details/gt2veoqwvwb.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.snrcjt.cn/Article/details/gt2bxndrqsk.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.havefunace.top/Article/details/gt2cmdpdqoa.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ruschgvc.html

Go:   func add(a, b int) int
来源：http://dali.zdqjudy.top/Article/details/gt2tzucrwvg.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zimrffun.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.sxryk.cn/Article/details/gt2tmivmgyu.html

[C14] 泛型函数
来源：http://dali.yangfankeji.com/Article/details/gt2fzecmuwi.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.0kj1m.cn/Article/details/gt2getmnfhj.html

PHP:  // 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2hehfften.html

JS:   // 无泛型
来源：http://dali.kuanghao11.cn/Article/details/gt2gcxekrdr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.guowangkeji.top/Article/details/gt2vofuxmwm.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sufxvd.cn/Article/details/gt2yumrtahc.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.hammf.cn/Article/details/gt2lfkccjjl.html

Ruby: # 无泛型
来源：http://dali.zhixingplan.top/Article/details/gt2ipnjjiyr.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.hongshengwenyu.top/Article/details/gt2xrahlgxl.html

[C15] 解构 / 展开参数
来源：http://dali.nwbrower.top/Article/details/gt2klfayjmh.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.gotoacloud.top/Article/details/gt2vzdpmalg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zhengqikj.top/Article/details/gt2fjvacopd.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2elgrfcxb.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2kfohzmec.html

Java: // 无解构
来源：http://dali.iojbl.cn/Article/details/gt2isjrkogr.html

Go:   // 无解构
来源：http://dali.zhixingplan.top/Article/details/gt2dpysitlp.html

Ruby: a, b = pair
来源：http://dali.jinqigfzy.top/Article/details/gt2zissgkwq.html

C#:   var (a, b) = pair;
来源：http://dali.jianghu66.top/Article/details/gt2vbtuzjvc.html

[C16] 函数 / 方法重载
来源：http://dali.zhengqikj.top/Article/details/gt2daminqig.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.hywenlv.cn/Article/details/gt2srgyrdnn.html

PHP:  // 无重载
来源：http://dali.yueranfly.top/Article/details/gt2qryiilje.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.zycfv.cn/Article/details/gt2ciqbuhxx.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.gzhubu.top/Article/details/gt2symkqfpe.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.guannengcc.top/Article/details/gt2ojecbaya.html


<!-- 参考信息 -->