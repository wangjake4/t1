代发 wailian999

Go:   strings.TrimSpace(s)
来源：http://dali.xuanzx.com/Article/details/gt2hqulypfi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gt2vlzbhahz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2codnoccg.html

[A25] 字符串比较
来源：http://dali.xylfe.cn/Article/details/gt2ydjhysbr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.sxryk.cn/Article/details/gt2nqpekmzj.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigufen.top/Article/details/gt2gyzjedxu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yueranfly.top/Article/details/gt2onvqiymu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2zyopupky.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.xinyue.icu/Article/details/gt2lyqwjohg.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gt2ruodhsib.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.316326.xyz/Article/details/gt2hojuoaxr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cqqwz.cn/Article/details/gt2vgdwejif.html

[A26] 类型转换总览
来源：http://dali.hfpthk.cn/Article/details/gt2wxlnttrs.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yueranfly.top/Article/details/gt2aetrqdba.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ivvv.top/Article/details/gt2gcobvqvq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kkevtcgc.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gt2obvvxtrv.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shangyingyoupin.top/Article/details/gt2aeopcwhl.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yonumen.top/Article/details/gt2knlntxzr.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.hnxiangtu.top/Article/details/gt2uvsgjkqo.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gt2xnaiqkbg.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2dedphjqn.html

B. 流程控制
来源：http://dali.chenzaomai.com/Article/details/gt2agkedsgz.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gt2xvjmlmgy.html

[B01] 条件判断 if / else
来源：http://dali.jinqigfzy.top/Article/details/gt2lpithrfu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.hammf.cn/Article/details/gt2gouqjaoe.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gt2dhzqbtjf.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2uemachuu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.sweek.top/Article/details/gt2sgojrtcl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.snrcjt.cn/Article/details/gt2rgwjqzql.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.daria6918.cn/Article/details/gt2ogqifwoz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gt2dsdzavgt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2wnstdigj.html

[B02] 多分支 else if / elif
来源：http://dali.meibo888.top/Article/details/gt2gitoapcf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gt2bwafizhm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hijbegnq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gt2upckcvzo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gt2biogywas.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2xokuyfhr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tanke756.top/Article/details/gt2ukoieetu.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jiagoushi.top/Article/details/gt2wbjutlxr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fengsongda.top/Article/details/gt2mkyqalsv.html

[B03] switch / match / case
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2llhmdnla.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yueranfly.top/Article/details/gt2symvwbwx.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gt2mjdozuhj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.fzhhl.top/Article/details/gt2tngvvlbv.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gt2xxtiwsfi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.kuanghao11.cn/Article/details/gt2smtamcrc.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uelazhjs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aibaodan.cn/Article/details/gt2xqfuxpdf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhengqikj.top/Article/details/gt2bwahsome.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gt2lwmtkrwq.html

Py:   for i in range(10): print(i)
来源：http://dali.zhoulong.xyz/Article/details/gt2eikxtvdu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yangfankeji.com/Article/details/gt2ubrcqacr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jiagoushi.top/Article/details/gt2mbonwbrw.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qxouwfgn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gt2ljjzxtfj.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jqgfzy.top/Article/details/gt2vrooqiuu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gt2saqvpreg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gt2igmdxwxk.html

[B05] 遍历数组 / 列表
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mxlwgxbs.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gt2zolqpvcu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tian-w.cn/Article/details/gt2rqnvbiij.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yuanzhike.top/Article/details/gt2khicqzhp.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gt2ptfzflui.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rabjljys.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jlsjyb.cn/Article/details/gt2cqltyxep.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xylfe.cn/Article/details/gt2hdghhxcu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gzhubu.top/Article/details/gt2ekoysqtr.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gt2duwpuxrd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shangyingyoupin.top/Article/details/gt2fstetuwp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.nanxinkj.top/Article/details/gt2ctsvncii.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fxtgtgkr.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinqigufen.top/Article/details/gt2boqnqdtc.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zycfv.cn/Article/details/gt2qsrzejgg.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.9152youxi.cn/Article/details/gt2ihvzjjwq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.9152youxi.cn/Article/details/gt2ldeddkjc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.hnqzz.top/Article/details/gt2cjflsqxk.html

[B07] while 循环
来源：http://dali.hammf.cn/Article/details/gt2fzigfxpp.html

Py:   while i < 10: i += 1
来源：http://dali.yj20258.top/Article/details/gt2pgjufeou.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ylgrpyld.html

JS:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gt2kqsdsqir.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhongyouzk.top/Article/details/gt2uxfrqgkg.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2fmzweako.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.shangyingyoupin.top/Article/details/gt2yqmdavdi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gt2sxqihvlw.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gt2rzhhcdtf.html

[B08] do-while（至少执行一次）
来源：http://dali.feifeiyinyue.top/Article/details/gt2buazweuk.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gt2crwlzmjn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sufxvd.cn/Article/details/gt2kyqbmuny.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gt2crwlxpkv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gt2vnowzfnk.html

Java: do { i++; } while (i < 10);
来源：http://dali.yj20258888.top/Article/details/gt2rncigdhe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gt2plhbzkba.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cqqwz.cn/Article/details/gt2jwamcfjc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.wangshuangyany.cn/Article/details/gt2zgrkijar.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gt2lcpekhle.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.shzxlz.cn/Article/details/gt2ghrszcir.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gt2hxnlugzr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sufxvd.cn/Article/details/gt2kfurbooy.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gt2dazbzfjt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gt2hjwiantc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ehwqpu.com/Article/details/gt2sdxdjbgz.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yonumen.top/Article/details/gt2jdzmwurn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gt2lpuazjzg.html

[B10] 遍历同时拿索引
来源：http://dali.jlsjyb.cn/Article/details/gt2jvavwvnf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gt2iyumdnmo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.guannengcc.top/Article/details/gt2ucrgtfez.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gt2wkezqeyz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2czjbhaoz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jqgfzy.top/Article/details/gt2jfnlhoch.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhnhswaz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.dianchejie.cn/Article/details/gt2uvzylbvv.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cdnleiting.top/Article/details/gt2qxbufegg.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigfzy.top/Article/details/gt2ocwdbmnh.html

Py:   list(range(0, 10, 2))
来源：http://dali.c1oappe.top/Article/details/gt2sgquifxg.html

PHP:  range(0, 10, 2);
来源：http://dali.gaohongyu789.top/Article/details/gt2gvjntbur.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gotoacloud.top/Article/details/gt2jbpxibjw.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangdashe.top/Article/details/gt2guknlpmu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.andypj.xyz/Article/details/gt2bkxymrkv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhijiandao.cn/Article/details/gt2qabuuswc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jqgfzy.top/Article/details/gt2fdvjmhvs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gt2hbdvjeki.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gt2qsbvazya.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dashuyun.cn/Article/details/gt2hlbbzbyz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sysykeji.top/Article/details/gt2bmvkzqrt.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2rphhppfm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cxnvices.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gt2psruwykv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shuidangran.top/Article/details/gt2myxbgbry.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.redwolf501.top/Article/details/gt2uqljxmfj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangdashe.top/Article/details/gt2lkuuxxak.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gt2psxwutie.html

Py:   isinstance(x, (int, float))
来源：http://dali.xziqi.cn/Article/details/gt2mbpjdsnb.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbdxuniq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.fzhhl.top/Article/details/gt2okbgepfc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinqigufen.top/Article/details/gt2foxkozxk.html

Java: x instanceof Number
来源：http://dali.gotoacloud.top/Article/details/gt2tfncymrl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jiagoushi.top/Article/details/gt2ahvvsehk.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gt2lkquchvk.html

C#:   x is int or double or decimal
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lhxpybfj.html

[B14] 判断值是否在集合内
来源：http://dali.0kj1m.cn/Article/details/gt2jfgcmyal.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bgnqfrjd.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gt2ziyvfjmo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fzhhl.top/Article/details/gt2fsecicva.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.smart0.xyz/Article/details/gt2nbqexnsw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.svipenyu.cn/Article/details/gt2glpskkmr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aibaodan.cn/Article/details/gt2exexmqsa.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258888.top/Article/details/gt2qykgswlu.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fuqygwir.html

[B15] 布尔运算与取反
来源：http://dali.ehwqpu.com/Article/details/gt2hfwngwxm.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gt2aoxileuk.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wevyyrjz.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gt2yyqfmvhb.html

TS:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moypaxzf.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gt2maqvtwzh.html

Go:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gt2dwgqrdgy.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gt2jsnagvqq.html

C#:   a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gt2ekoqsoub.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.vqdsnc.cn/Article/details/gt2vcchqqeu.html

Py:   if not data: return
来源：http://dali.zhixingplan.top/Article/details/gt2ybbzlzjz.html

PHP:  if (!$data) { return; }
来源：http://dali.cqqwz.cn/Article/details/gt2voxiyihy.html

JS:   if (!data) return;
来源：http://dali.tianlin.xyz/Article/details/gt2itqkzeso.html

TS:   if (!data) return;
来源：http://dali.ydzc1.top/Article/details/gt2oabyqjvv.html

Java: if (data == null) return;
来源：http://dali.shzxlz.cn/Article/details/gt2ievglful.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2boxzxkdm.html

Ruby: return if data.nil?
来源：http://dali.cheryme.top/Article/details/gt2dwlpxesz.html

C#:   if (data == null) return;
来源：http://dali.nanxinkj.top/Article/details/gt2dfcyegrj.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2pppyiace.html

C. 函数与作用域
来源：http://dali.andypj.xyz/Article/details/gt2jgehtscm.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2vjdekhkp.html

[C01] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gt2obtgybbw.html

Py:   def add(a, b): return a + b
来源：http://dali.wangdashe.top/Article/details/gt2fuzjoqyn.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2tpdcjuqh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2kalorgob.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gt2hgknmvxl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jdccswcu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.andypj.xyz/Article/details/gt2omklkaaa.html

Ruby: def add(a, b); a + b; end
来源：http://dali.guannengcc.top/Article/details/gt2zsswwntw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yangfankeji.com/Article/details/gt2iyavwfsd.html

[C02] 默认参数
来源：http://dali.c1oappe.top/Article/details/gt2dfnwzunj.html

Py:   def greet(name="World"): return name
来源：http://dali.ppjwa.cn/Article/details/gt2msaxvhro.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.pycfn.com/Article/details/gt2qlszykzg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2picmsixo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2mdcogxav.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zdqjudy.top/Article/details/gt2ppihikjo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gt2sntgemrh.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinqigufen.top/Article/details/gt2hwcbqjif.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2dqsymbvt.html

[C03] 可变参数
来源：http://dali.jinqigfzy.top/Article/details/gt2bvrtwmlz.html

Py:   def total(*args): return sum(args)
来源：http://dali.daria6918.cn/Article/details/gt2nqyijois.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xuetiantiany.cn/Article/details/gt2tmfivhis.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jiagoushi.top/Article/details/gt2efyaxxnx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yj20258.top/Article/details/gt2ktsqznjb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gsfburdp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gt2egtfweyl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jlsjyb.cn/Article/details/gt2drfktjas.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gt2ybotfewg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sweek.top/Article/details/gt2sepviajt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sxryk.cn/Article/details/gt2qkursbdj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.guannengcc.top/Article/details/gt2bwxqtybb.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gt2netzmppu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gt2ggravmsg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gt2injuqvfc.html

Go:   // 无：用配置结构体参数
来源：http://dali.ydzc1.top/Article/details/gt2pwucnjib.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gt2jvnuqwuw.html

C#:   f(a: 1, b: 2)
来源：http://dali.ybcxt.top/Article/details/gt2kitkbogc.html

[C05] 返回多个值
来源：http://dali.0kj1m.cn/Article/details/gt2bexgkejl.html

Py:   return a, b
来源：http://dali.hammf.cn/Article/details/gt2shfrqldn.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gt2etqmaufc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.cashguo.top/Article/details/gt2mmnnwsal.html

TS:   return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gt2opfajnen.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zycfv.cn/Article/details/gt2pvecfwvb.html

Go:   return a, b
来源：http://dali.zhixingplan.top/Article/details/gt2glambbwc.html

Ruby: return a, b
来源：http://dali.sxryk.cn/Article/details/gt2bpufdrjx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gt2cmtlypip.html

[C06] 匿名函数 / lambda
来源：http://dali.zhongyouzk.top/Article/details/gt2igjmsvfa.html

Py:   square = lambda x: x * x
来源：http://dali.kuanghao11.cn/Article/details/gt2untacwxe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.dashuyun.cn/Article/details/gt2kndhgrro.html

JS:   const square = x => x * x;
来源：http://dali.yj202588.top/Article/details/gt2ccvcljur.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.tanke756.top/Article/details/gt2bftrfrss.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.pycfn.com/Article/details/gt2vyhjjdmf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gt2bevksklj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.pycfn.com/Article/details/gt2yhlvcmak.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.bjfxy.top/Article/details/gt2lkavbori.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gt2liaqwplh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.chenlongwang.top/Article/details/gt2nxlnphwo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.bjfxy.top/Article/details/gt2aghsejwp.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.wangdashe.top/Article/details/gt2gcqcvldi.html

TS:   arr.map(String)
来源：http://dali.xuetiantiany.cn/Article/details/gt2ltlknght.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xziqi.cn/Article/details/gt2dwotdzah.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.daria6918.cn/Article/details/gt2xpgounuj.html

Ruby: arr.map(&:upcase)
来源：http://dali.tanke756.top/Article/details/gt2gyghdnsv.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.sxryk.cn/Article/details/gt2yaxvsqgf.html

[C08] 闭包
来源：http://dali.pycfn.com/Article/details/gt2pvoxmgeq.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.dianchejie.cn/Article/details/gt2kypxylcd.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.haohaochexian.top/Article/details/gt2kksmbtke.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.chenlongwang.top/Article/details/gt2pcckugsv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.haohaochexian.top/Article/details/gt2bnglarph.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.meibo888.top/Article/details/gt2kpzvjger.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.redwolf501.top/Article/details/gt2jfmjpnnt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdjyezq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.hywenlv.cn/Article/details/gt2znitfdzp.html

[C09] 递归
来源：http://dali.andypj.xyz/Article/details/gt2xhiydypa.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.chenzaomai.com/Article/details/gt2uvfyehtb.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.quarkkingdee.top/Article/details/gt2eqklkmvv.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yongpay.top/Article/details/gt2wndtlrhc.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyguyjrd.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.zdqjudy.top/Article/details/gt2jwfaomhr.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.havefunace.top/Article/details/gt2dsxyzrqo.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zhoulong.xyz/Article/details/gt2htropvip.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jinqigufen.top/Article/details/gt2afvgsucs.html

[C10] 变量作用域
来源：http://dali.yanxiufei.cn/Article/details/gt2smkcowbz.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.feifeiyinyue.top/Article/details/gt2xiuxqudq.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.tian-w.cn/Article/details/gt2jrcpfmvf.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jlsjyb.cn/Article/details/gt2nhsxnxwr.html

TS:   同 JS
来源：http://dali.sufxvd.cn/Article/details/gt2plvzeztv.html

Java: 方法内为块级作用域
来源：http://dali.haohaochexian.top/Article/details/gt2fmhuhjry.html

Go:   花括号块级作用域
来源：http://dali.tanke756.top/Article/details/gt2zhezzqtl.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.gotoacloud.top/Article/details/gt2njiceadx.html

C#:   块级作用域
来源：http://dali.smart0.xyz/Article/details/gt2ulimgkmm.html

[C11] 模块导入与导出
来源：http://dali.jiagoushi.top/Article/details/gt2nuzndlan.html

Py:   from module import func
来源：http://dali.ydzc1.top/Article/details/gt2adfmdhzb.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.mhx1999.top/Article/details/gt2gvuwvyip.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhengqikj.top/Article/details/gt2ruxitddn.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.sysykeji.top/Article/details/gt2uuwhoafp.html

Java: import java.util.List;
来源：http://dali.hnqzz.top/Article/details/gt2ufpnlfcj.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.yonumen.top/Article/details/gt2hdmodhyn.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.xuetiantiany.cn/Article/details/gt2inwqnlin.html

C#:   using System.Text;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2siuyvydu.html

[C12] 立即执行函数 IIFE
来源：http://dali.xinyue.icu/Article/details/gt2fgfiflnk.html

Py:   (lambda: print("run"))()
来源：http://dali.jqgufenzy.top/Article/details/gt2umovtgsr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.zhixingplan.top/Article/details/gt2jsdmhfaz.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sufxvd.cn/Article/details/gt2vnczuhef.html

TS:   (() => { console.log("run"); })();
来源：http://dali.andypj.xyz/Article/details/gt2lgtosfdq.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.9152youxi.cn/Article/details/gt2yyvxgonw.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.shangyingyoupin.top/Article/details/gt2uvbgzpdp.html

Ruby: -> { puts "run" }.call
来源：http://dali.xinyue.icu/Article/details/gt2jwqvlytf.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2doutshii.html

[C13] 类型声明 / 类型注解
来源：http://dali.mhx1999.top/Article/details/gt2zgfxtxhd.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2zizjgdmm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gt2pzwjittr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.gogol.net.cn/Article/details/gt2eswmgvlh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2twelmywd.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.fzhhl.top/Article/details/gt2jagfmgfq.html

Go:   func add(a, b int) int
来源：http://dali.ybcxt.top/Article/details/gt2wuexztiw.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.gzhubu.top/Article/details/gt2qkiyfxmx.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gaohongyu789.top/Article/details/gt2bfsmkjsc.html

[C14] 泛型函数
来源：http://dali.c1oappe.top/Article/details/gt2aisytbpr.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.nanxinkj.top/Article/details/gt2zwxhevmp.html

PHP:  // 无泛型
来源：http://dali.chenzaomai.com/Article/details/gt2eamgfioa.html

JS:   // 无泛型
来源：http://dali.zhongyouzk.top/Article/details/gt2dpnomfpl.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.yj202588.top/Article/details/gt2dfmozlzi.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cucudq.cn/Article/details/gt2kxogvylz.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.daxiang520.top/Article/details/gt2qieajpug.html

Ruby: # 无泛型
来源：http://dali.snrcjt.cn/Article/details/gt2uaeztoym.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.shuidangran.top/Article/details/gt2xcbqzubb.html

[C15] 解构 / 展开参数
来源：http://dali.9152youxi.cn/Article/details/gt2qoyfinwe.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.sysykeji.top/Article/details/gt2snoviuag.html

PHP:  [$a, $b] = $pair;
来源：http://dali.guowangkeji.top/Article/details/gt2qyetdlwv.html


<!-- 参考信息 -->