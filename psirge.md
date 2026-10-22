代发 wailian999

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.0kj1m.cn/Article/details/gt2uhlcbphw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gt2gjbcfyfs.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fpwicjcu.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gt2mvomxmwq.html

[A26] 类型转换总览
来源：http://dali.daria6918.cn/Article/details/gt2opbospdj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gt2nhfcinxy.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.fzhhl.top/Article/details/gt2aczwafin.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nwbrower.top/Article/details/gt2wtxuotag.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hfpthk.cn/Article/details/gt2rmsvtwug.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hfpthk.cn/Article/details/gt2nbbemdxp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2qezpnfdi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yvedp.cn/Article/details/gt2qbaefzaq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhiwuduotai.top/Article/details/gt2xnclxmkt.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2xsiewgcl.html

B. 流程控制
来源：http://dali.gaohongyu789.top/Article/details/gt2qwseotfn.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gt2lifvjmvh.html

[B01] 条件判断 if / else
来源：http://dali.kuanghao11.cn/Article/details/gt2uwemsnhk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gt2fxixvocu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.wangdashe.top/Article/details/gt2ouxwfxhg.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gt2fpsvakgn.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gt2ycchbfko.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2ioghetgb.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfljmmxh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gt2flxobhke.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2clsxzgyd.html

[B02] 多分支 else if / elif
来源：http://dali.hammf.cn/Article/details/gt2ztwppcvj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gt2shdaztdw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.haohaochexian.top/Article/details/gt2nqerabmx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2aujugcog.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gt2fgsndljh.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2wbaxmgcn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258888.top/Article/details/gt2mcrjkfdn.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.chenjidiqi.icu/Article/details/gt2whxarvyn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gt2mnojvqtm.html

[B03] switch / match / case
来源：http://dali.fengsongda.top/Article/details/gt2ruasyvpn.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhiwuduotai.top/Article/details/gt2gbaprkaz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2vieijkgi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gt2tnhzoxxu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gt2ykrcqalq.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yvedp.cn/Article/details/gt2zlvyyxjt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinqigfzy.top/Article/details/gt2jxyaamur.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ppjwa.cn/Article/details/gt2jaosidyf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gt2lrvcoakh.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2qfyxcarq.html

Py:   for i in range(10): print(i)
来源：http://dali.9152youxi.cn/Article/details/gt2nmpljowr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gfwrimwc.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gt2dzhcggsb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ybcxt.top/Article/details/gt2tmuzhcyf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gdhxkxjj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gt2fueccqsh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gt2iejxofnj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jlsjyb.cn/Article/details/gt2owinhrvd.html

[B05] 遍历数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2rsatraaf.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gt2nedkcvsr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ehwqpu.com/Article/details/gt2ipgtiqey.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gt2qanbpnvz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.gaohongyu789.top/Article/details/gt2jaqojozh.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2orsxuhfe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.haohaochexian.top/Article/details/gt2qhsivvow.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhengqikj.top/Article/details/gt2gwnfzuyc.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cucudq.cn/Article/details/gt2ofishwmz.html

[B06] 遍历字典 / 对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vduypuas.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.wangshuangyany.cn/Article/details/gt2nipglkak.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guannengcc.top/Article/details/gt2doqlwvkm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gt2pcpcarcy.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gt2jrgdxryj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gt2lmpgaccs.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gt2osrktfsz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.aibaodan.cn/Article/details/gt2hblsbtgv.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yonumen.top/Article/details/gt2jwfptprf.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gt2ewbzxwtt.html

Py:   while i < 10: i += 1
来源：http://dali.xinyue.icu/Article/details/gt2grptsgdz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.tanke756.top/Article/details/gt2wgxvkntx.html

JS:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2qzzubfop.html

TS:   while (i < 10) { i++; }
来源：http://dali.gotoacloud.top/Article/details/gt2ktjqeqhh.html

Java: while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gt2lxfovesa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2ekdcpxnp.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ruumevrf.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gt2ayphltov.html

[B08] do-while（至少执行一次）
来源：http://dali.xylfe.cn/Article/details/gt2kwvexogr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gt2ndouppbb.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gt2escttnqw.html

JS:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2moxnsbgp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gt2fblkuyld.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigufen.top/Article/details/gt2jmpigqig.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ydzc1.top/Article/details/gt2bwdtrmru.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jiagoushi.top/Article/details/gt2leicioqb.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2gcgbgqls.html

[B09] break 与 continue
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xxqgudnb.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cdnleiting.top/Article/details/gt2wbyaipaw.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gt2pbgkkiyc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2vnpyogem.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gt2upomufho.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gt2oqsehqss.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wxxafcmb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gt2tqrvjlkq.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2msnwmgcd.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gt2gazrwoig.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yueranfly.top/Article/details/gt2blrlkoqq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gt2kcrmcoug.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.iojbl.cn/Article/details/gt2zuqrqrgt.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzsgeugk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.snrcjt.cn/Article/details/gt2ahkqsbwl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ssspbgoy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgufenzy.top/Article/details/gt2tqmvhetj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2beqqmcdq.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhoulong.xyz/Article/details/gt2fgbhtcye.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zxcgwptr.html

PHP:  range(0, 10, 2);
来源：http://dali.hnqzz.top/Article/details/gt2wuhdowym.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daria6918.cn/Article/details/gt2lhioiqlx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gt2rzaqcpcv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ehwqpu.com/Article/details/gt2hckwtqbl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gt2dfjocreo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oecslpud.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hywenlv.cn/Article/details/gt2guycbrps.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gt2luqfijdu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.chenlongwang.top/Article/details/gt2octwfsgr.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2ulgawmzh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zycfv.cn/Article/details/gt2pctkkfsg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gt2osxvxepf.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qbjcwfar.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.bjfxy.top/Article/details/gt2vskemjnr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hongshengwenyu.top/Article/details/gt2ravbemmq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.9152youxi.cn/Article/details/gt2vgizphec.html

[B13] 判断是否为数字
来源：http://dali.xuanzx.com/Article/details/gt2nikmyhlm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hnqzz.top/Article/details/gt2pmdogife.html

PHP:  is_numeric($x)
来源：http://dali.zhengqikj.top/Article/details/gt2unddfnye.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gt2hcsrmppv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gt2wqgptykm.html

Java: x instanceof Number
来源：http://dali.nwbrower.top/Article/details/gt2difcpxro.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.aibaodan.cn/Article/details/gt2itxjuegj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gt2mlujeccc.html

C#:   x is int or double or decimal
来源：http://dali.jyoumei.cn/Article/details/gt2tzjxdfzk.html

[B14] 判断值是否在集合内
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lwqyjeqt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yanxiufei.cn/Article/details/gt2uhzypqok.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gt2hbnvtosg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nwbrower.top/Article/details/gt2tanklhgw.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gt2rxzpjwcz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gt2chrbyjwv.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhixingplan.top/Article/details/gt2bwkkrkph.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zdqjudy.top/Article/details/gt2qbsxuqrt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cashguo.top/Article/details/gt2niyxuark.html

[B15] 布尔运算与取反
来源：http://dali.havefunace.top/Article/details/gt2ndtemhur.html

Py:   a and b or not c
来源：http://dali.daria6918.cn/Article/details/gt2tbhvfldn.html

PHP:  $a && $b || !$c
来源：http://dali.hysaishi.cn/Article/details/gt2golsovxc.html

JS:   a && b || !c
来源：http://dali.quarkkingdee.top/Article/details/gt2pxdlwqei.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gt2glafndgq.html

Java: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2exwuwmof.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2wymryuze.html

Ruby: a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2xtyteygv.html

C#:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gt2rheuzqij.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhongyouzk.top/Article/details/gt2ejmzdhpc.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gt2mjfuimxq.html

PHP:  if (!$data) { return; }
来源：http://dali.yj202588.top/Article/details/gt2syslkfrl.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gt2hudnrzvu.html

TS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2ciuvtyqt.html

Java: if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2bburstnc.html

Go:   if data == nil { return }
来源：http://dali.xuanzx.com/Article/details/gt2hnjrfomh.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gt2wzkpcmbx.html

C#:   if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2idjdcrss.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2gsryonnq.html

C. 函数与作用域
来源：http://dali.snrcjt.cn/Article/details/gt2rqysndaz.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2hubctwhg.html

[C01] 定义函数
来源：http://dali.yongpay.top/Article/details/gt2yamukwkb.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258888.top/Article/details/gt2wsgzfkkx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gotoacloud.top/Article/details/gt2hlhsgovk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gt2sixnpqie.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2jwwjtatu.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wruzupht.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.iojbl.cn/Article/details/gt2ryxllpou.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jqgfzy.top/Article/details/gt2ibuxaced.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cqqwz.cn/Article/details/gt2iszhxcga.html

[C02] 默认参数
来源：http://dali.hfpthk.cn/Article/details/gt2qryqbizo.html

Py:   def greet(name="World"): return name
来源：http://dali.chenlongwang.top/Article/details/gt2qguropnv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gt2lnkynhbl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2qfgtzera.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2gutqaewi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cqqwz.cn/Article/details/gt2zgellqno.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gt2hlvdgzyz.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gt2jhlaklut.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2ppfyekfy.html

[C03] 可变参数
来源：http://dali.chenlongwang.top/Article/details/gt2hoghtfdd.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhiwuduotai.top/Article/details/gt2zcxpkicx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ybcxt.top/Article/details/gt2ihxrabnx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guannengcc.top/Article/details/gt2zmxkgwkx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gt2xoitimmo.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gcxzjuul.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yonumen.top/Article/details/gt2aazrvuhv.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.cucudq.cn/Article/details/gt2hvnltdjt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gt2zspjghbv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.snrcjt.cn/Article/details/gt2stvvwzah.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yj20258.top/Article/details/gt2aifudtoe.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jlsjyb.cn/Article/details/gt2arswlqhf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2jsmotcck.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxfyjoht.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.daxiang520.top/Article/details/gt2fwukvilj.html

Go:   // 无：用配置结构体参数
来源：http://dali.fengsongda.top/Article/details/gt2ghdeurie.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gt2inprmape.html

C#:   f(a: 1, b: 2)
来源：http://dali.sweek.top/Article/details/gt2ngmmcspq.html

[C05] 返回多个值
来源：http://dali.vqdsnc.cn/Article/details/gt2edjauond.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sfvcrndg.html

PHP:  return [$a, $b];
来源：http://dali.cdnleiting.top/Article/details/gt2hqhtfhyx.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.zhongyouzk.top/Article/details/gt2okreaxkq.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gt2dotmahnc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.snrcjt.cn/Article/details/gt2oxdozcps.html

Go:   return a, b
来源：http://dali.smart0.xyz/Article/details/gt2iextolux.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2idhhrthy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.sxryk.cn/Article/details/gt2hmeehlap.html

[C06] 匿名函数 / lambda
来源：http://dali.ehwqpu.com/Article/details/gt2aaavfzso.html

Py:   square = lambda x: x * x
来源：http://dali.sweek.top/Article/details/gt2pafjgodj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dianchejie.cn/Article/details/gt2luxurqrj.html

JS:   const square = x => x * x;
来源：http://dali.zdqjudy.top/Article/details/gt2fkuclibo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.kuanghao11.cn/Article/details/gt2hhixgbtt.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenzaomai.com/Article/details/gt2hdggqmcz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.meibo888.top/Article/details/gt2alllaphs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.hnxiangtu.top/Article/details/gt2kyeiwdjl.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gt2iqlwkpnm.html

[C07] 把函数作为参数传入
来源：http://dali.fzhhl.top/Article/details/gt2rnhsagfb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gt2uxsddlyb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gt2xbiwofjp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.tanke756.top/Article/details/gt2emwvvwnt.html

TS:   arr.map(String)
来源：http://dali.shuidangran.top/Article/details/gt2mirdspnr.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.fengsongda.top/Article/details/gt2yzlplngy.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gt2uyyfcwqt.html

Ruby: arr.map(&:upcase)
来源：http://dali.yanxiufei.cn/Article/details/gt2uaeaecjo.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.kuanghao11.cn/Article/details/gt2nychidwm.html

[C08] 闭包
来源：http://dali.tanke756.top/Article/details/gt2ukohyqmm.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.fzhhl.top/Article/details/gt2pukuspls.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.vqdsnc.cn/Article/details/gt2nztpcyln.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2vbnkvsok.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ydzc1.top/Article/details/gt2shvqldek.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gt2ywzpyaql.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dashuyun.cn/Article/details/gt2ndvpoqmk.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258888.top/Article/details/gt2gazlrmxt.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.yj20258888.top/Article/details/gt2usrcrdjf.html

[C09] 递归
来源：http://dali.yangfankeji.com/Article/details/gt2zpsuwtai.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.xinyue.icu/Article/details/gt2rrzcvfbf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2vvslmycr.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhoulong.xyz/Article/details/gt2lxonovoj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.wangdashe.top/Article/details/gt2flxzpnqk.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.hnqzz.top/Article/details/gt2mkgyslsm.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.daxiang520.top/Article/details/gt2dmhuqhfd.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.hysaishi.cn/Article/details/gt2ecchshrc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.bjfxy.top/Article/details/gt2vhupfxrn.html

[C10] 变量作用域
来源：http://dali.ydzc1.top/Article/details/gt2wfmhabsc.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.gotoacloud.top/Article/details/gt2vgvbbfzv.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.nwbrower.top/Article/details/gt2znyvvcjl.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.xinyue.icu/Article/details/gt2fivgjmlo.html

TS:   同 JS
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2azapwcft.html

Java: 方法内为块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2ckhoncal.html

Go:   花括号块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eltavnix.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.yuxming.cn/Article/details/gt2xkingakw.html

C#:   块级作用域
来源：http://dali.ydzc1.top/Article/details/gt2mfeijefr.html

[C11] 模块导入与导出
来源：http://dali.mhx1999.top/Article/details/gt2tsecpuwa.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2slfjifwl.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2ssfjzgsw.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2qdsjyizb.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.xylfe.cn/Article/details/gt2irqejnow.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2tijqcvgs.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.meibo888.top/Article/details/gt2uuyzextl.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.zhengqikj.top/Article/details/gt2lugmrosu.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2zvvigzwe.html

[C12] 立即执行函数 IIFE
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2anxbajog.html

Py:   (lambda: print("run"))()
来源：http://dali.fengsongda.top/Article/details/gt2ganodwqd.html

PHP:  (function () { echo "run"; })();
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jnejelhk.html

JS:   (() => { console.log("run"); })();
来源：http://dali.tianlin.xyz/Article/details/gt2fztowafo.html

TS:   (() => { console.log("run"); })();
来源：http://dali.zycfv.cn/Article/details/gt2crtduwbn.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.bjfxy.top/Article/details/gt2hoirkaob.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2xzjasjcd.html

Ruby: -> { puts "run" }.call
来源：http://dali.yueranfly.top/Article/details/gt2xgvhwcwe.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.dianchejie.cn/Article/details/gt2dhsxmwds.html

[C13] 类型声明 / 类型注解
来源：http://dali.jqgufenzy.top/Article/details/gt2czmelmlz.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.daxiang520.top/Article/details/gt2ptrfgjzx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.wangdashe.top/Article/details/gt2wlvvjjtx.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.ydzc1.top/Article/details/gt2dfcticxg.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.wangdashe.top/Article/details/gt2egtedmjc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2vgqmdaaf.html

Go:   func add(a, b int) int
来源：http://dali.daxiang520.top/Article/details/gt2ooqgogns.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.jqgufenzy.top/Article/details/gt2rwoslsth.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.yonumen.top/Article/details/gt2rttitmvg.html

[C14] 泛型函数
来源：http://dali.zycfv.cn/Article/details/gt2jhmtrune.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.sxryk.cn/Article/details/gt2qrcsvrzx.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gt2xbszvroq.html

JS:   // 无泛型
来源：http://dali.wangshuangyany.cn/Article/details/gt2jetkmucx.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jqqvzntx.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.hnqzz.top/Article/details/gt2ovqamzmq.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.yanxiufei.cn/Article/details/gt2hhoowxrd.html

Ruby: # 无泛型
来源：http://dali.cqqwz.cn/Article/details/gt2fqmjgdpz.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.haohaochexian.top/Article/details/gt2zrcawhbg.html

[C15] 解构 / 展开参数
来源：http://dali.bjfxy.top/Article/details/gt2hgzrwgmi.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.hfpthk.cn/Article/details/gt2dsoshpys.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2hdryjflc.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cucudq.cn/Article/details/gt2sjhenefu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.svipenyu.cn/Article/details/gt2bkietpwm.html

Java: // 无解构
来源：http://dali.yj202588.top/Article/details/gt2dycqdicg.html

Go:   // 无解构
来源：http://dali.ydzc1.top/Article/details/gt2axhjbpds.html

Ruby: a, b = pair
来源：http://dali.pengpengdd.cyou/Article/details/gt2azjzutce.html

C#:   var (a, b) = pair;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zxtdsyjn.html

[C16] 函数 / 方法重载
来源：http://dali.9152youxi.cn/Article/details/gt2wwbaipqh.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.9152youxi.cn/Article/details/gt2epbxjhde.html


<!-- 参考信息 -->