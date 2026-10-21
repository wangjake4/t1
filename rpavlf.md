代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.yvedp.cn/Article/details/gtbyvknwxs.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ehwqpu.com/Article/details/gtkpvlvzil.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.0kj1m.cn/Article/details/gthhfvdnxd.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cucudq.cn/Article/details/gthsumikwe.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cucudq.cn/Article/details/gtpslogcho.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtwvttvzid.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.snrcjt.cn/Article/details/gtbztqiron.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj20258888.top/Article/details/gtzetkgrps.html

[A26] 类型转换总览
来源：http://dali.ppjwa.cn/Article/details/gtmqosvkhw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cdnleiting.top/Article/details/gtwcsmprti.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.316326.xyz/Article/details/gtuszdlvqv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.0kj1m.cn/Article/details/gtaqnsjbwb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.xinyue.icu/Article/details/gtheselwxf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jianghu66.top/Article/details/gtdoiybvtp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fzhhl.top/Article/details/gtwvyfryjn.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gthozwfedk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cashguo.top/Article/details/gtbmcifnzh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtmzvirswj.html

B. 流程控制
来源：http://dali.sufxvd.cn/Article/details/gtuglyzhbb.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtzpccrxle.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtdhamunku.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.svipenyu.cn/Article/details/gtkbmbgsfm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shuidangran.top/Article/details/gtuiqgkvpl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gtdereiifv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtccaikpra.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtipxdzbkn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtnyfyqrpy.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cdnleiting.top/Article/details/gtyjfbgkjn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jqgfzy.top/Article/details/gtqvgotlsv.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtidlhjfyc.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.9152youxi.cn/Article/details/gtsedkgiue.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.meibo888.top/Article/details/gtzhetancq.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtnjzplxrc.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gtahjdtzfr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtnmqksxpi.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtpiqjsqyg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shangyingyoupin.top/Article/details/gtaqzrwizg.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtuaaqxomd.html

[B03] switch / match / case
来源：http://dali.yj20258.top/Article/details/gtkaowiwoo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.meibo888.top/Article/details/gtuocjxlyu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gtluowzaxy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.9152youxi.cn/Article/details/gtmkwczptu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtipuqkxza.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtiqmfvczb.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoxqilhsj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinghuilouyu.cn/Article/details/gtxzgepxjb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jyoumei.cn/Article/details/gtlfdcoczb.html

[B04] for 计数循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gttkezaema.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtaljzgheo.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jqgufenzy.top/Article/details/gtgzcesbwr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtdwpuskxn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cashguo.top/Article/details/gtjipsesld.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yongpay.top/Article/details/gtkiqerozo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hammf.cn/Article/details/gtmzbvlkzl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtcfxrhcco.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.kuanghao11.cn/Article/details/gtyohdsrko.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtwvkeswcr.html

Py:   for item in arr: print(item)
来源：http://dali.zhiwuduotai.top/Article/details/gtshrbfsoo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnxiangtu.top/Article/details/gtnrlomgsn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtzghcugxk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.0kj1m.cn/Article/details/gtjyhoaqcp.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtvvjjmyhy.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj202588.top/Article/details/gtbulkemxa.html

Ruby: arr.each { |item| puts item }
来源：http://dali.haohaochexian.top/Article/details/gtrgwewvii.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuunrxwfd.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtpgeaygnw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.snrcjt.cn/Article/details/gtqxinhjbg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.xuanzx.com/Article/details/gttlsasjsv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.316326.xyz/Article/details/gtwggcrpbh.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtnpublqqj.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenlongwang.top/Article/details/gtflyivvkf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gogol.net.cn/Article/details/gtzrgufnxx.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ehwqpu.com/Article/details/gttaygeura.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtszxogiye.html

[B07] while 循环
来源：http://dali.sysykeji.top/Article/details/gtbpmxlciq.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gtqtxsnccc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hnqzz.top/Article/details/gtrbewjgnu.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtpbykbmlc.html

TS:   while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtolspethk.html

Java: while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtwmnhosni.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yonumen.top/Article/details/gtjtehjbtg.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tanke756.top/Article/details/gtrhjjlrfn.html

C#:   while (i < 10) { i++; }
来源：http://dali.cashguo.top/Article/details/gtbteoknnl.html

[B08] do-while（至少执行一次）
来源：http://dali.quarkkingdee.top/Article/details/gtfypnsqky.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gtxmzpxxfk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtundkaepg.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtokgvevmh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtzhfhkvuo.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtrrirghzo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yvedp.cn/Article/details/gtmshxqyzm.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.guowangkeji.top/Article/details/gtesgddpkk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtguwcuyis.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gtkggrwuhd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hfpthk.cn/Article/details/gtvzkmgdqs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtnmtzycvu.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gtbqzjpsmo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtwvdymmdt.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtflzuprex.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gtmhvpidyo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.snrcjt.cn/Article/details/gtpmiycsvh.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtpiniqojt.html

[B10] 遍历同时拿索引
来源：http://dali.svipenyu.cn/Article/details/gtwjjbzzon.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.nanxinkj.top/Article/details/gtlybwocez.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtdmsvyncf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.gotoacloud.top/Article/details/gtxebwqail.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtxpyqtemt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtjkydrabw.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.cashguo.top/Article/details/gtsoeugxwf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.kuanghao11.cn/Article/details/gtydfdpsel.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtxabznxhx.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gtmherldka.html

Py:   list(range(0, 10, 2))
来源：http://dali.cqqwz.cn/Article/details/gtpdelouze.html

PHP:  range(0, 10, 2);
来源：http://dali.shuidangran.top/Article/details/gtbewfipoi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.gogol.net.cn/Article/details/gtnomxltmc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gtovxedpjs.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhoulong.xyz/Article/details/gtdvxcjdym.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yongpay.top/Article/details/gtmuhxlpzo.html

Ruby: (0...10).step(2).to_a
来源：http://dali.shuidangran.top/Article/details/gteywvgxnv.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtcaafekdi.html

[B12] 跳出多层循环
来源：http://dali.xuanzx.com/Article/details/gteyjfywhl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gtjzxxndwi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ppjwa.cn/Article/details/gtrdnpiyaj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hammf.cn/Article/details/gtjucflrua.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtxydbznum.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqozflvt.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtejloyfjm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.guowangkeji.top/Article/details/gtgniflcfo.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.tian-w.cn/Article/details/gtsijpsnsp.html

[B13] 判断是否为数字
来源：http://dali.vqdsnc.cn/Article/details/gtmyiyakyd.html

Py:   isinstance(x, (int, float))
来源：http://dali.hongshengwenyu.top/Article/details/gtbhitlygi.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtvineeyej.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.0kj1m.cn/Article/details/gtxlmyihlq.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.andypj.xyz/Article/details/gtpfpcmupk.html

Java: x instanceof Number
来源：http://dali.jyoumei.cn/Article/details/gtsrymuyql.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yonumen.top/Article/details/gtndqijbxd.html

Ruby: x.is_a?(Numeric)
来源：http://dali.chenzaomai.com/Article/details/gtwrezztqz.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gtefdoxbhg.html

[B14] 判断值是否在集合内
来源：http://dali.tianlin.xyz/Article/details/gtzvqubfkj.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwsuetvxg.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ydzc1.top/Article/details/gtamrwwagk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtnrcwqjqq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jlsjyb.cn/Article/details/gtmocgrhcj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gtvzipvspd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jiagoushi.top/Article/details/gtucyvgfuy.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcazmjmix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangdashe.top/Article/details/gtnforhlfv.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtwbnqtpih.html

Py:   a and b or not c
来源：http://dali.zhijiandao.cn/Article/details/gtfortsgcw.html

PHP:  $a && $b || !$c
来源：http://dali.tanke756.top/Article/details/gtltcelhhx.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gttlmzcktg.html

TS:   a && b || !c
来源：http://dali.tanke756.top/Article/details/gtrvbtxqog.html

Java: a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtixpytcgj.html

Go:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtvtaucrnd.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuqotenle.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtqodnritr.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.nanxinkj.top/Article/details/gteyfvdziy.html

Py:   if not data: return
来源：http://dali.zycfv.cn/Article/details/gtxfrftsak.html

PHP:  if (!$data) { return; }
来源：http://dali.hongshengwenyu.top/Article/details/gtuvqtwviw.html

JS:   if (!data) return;
来源：http://dali.daxiang520.top/Article/details/gtptsmmcjs.html

TS:   if (!data) return;
来源：http://dali.nanxinkj.top/Article/details/gtgqdoafgb.html

Java: if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgssscdkc.html

Go:   if data == nil { return }
来源：http://dali.hongshengwenyu.top/Article/details/gttplajfya.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtgcprwdfz.html

C#:   if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gteidsmddc.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtpciheyyx.html

C. 函数与作用域
来源：http://dali.sufxvd.cn/Article/details/gtxakdpcjn.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtelxvxzqj.html

[C01] 定义函数
来源：http://dali.yvedp.cn/Article/details/gtzzeoaxxf.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtbrueqdcx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhijiandao.cn/Article/details/gtzrjwgwsw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtngocsgew.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtchsuxbdn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbduoutne.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.mhx1999.top/Article/details/gtplmbinbe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.tian-w.cn/Article/details/gtzhfzksqx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcbukfti.html

[C02] 默认参数
来源：http://dali.zhengqikj.top/Article/details/gtddlbcqdg.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gtfjuwwyoa.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.chenlongwang.top/Article/details/gtyedtkwlw.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jiagoushi.top/Article/details/gtwgnhzvoi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.dianchejie.cn/Article/details/gtciuefibx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtucflctnv.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtpfaaezxa.html

Ruby: def greet(name = "World") = name
来源：http://dali.bjfxy.top/Article/details/gtfcgrvvuj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gtrqvnacdo.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gtgfnwhruf.html

Py:   def total(*args): return sum(args)
来源：http://dali.shzxlz.cn/Article/details/gtvllpiddq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.tanke756.top/Article/details/gtawawljcp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyxttpaq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hysaishi.cn/Article/details/gtdozrhajq.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtgcmgkttn.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.haohaochexian.top/Article/details/gtzkexmqri.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtvuvjemmd.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yonumen.top/Article/details/gtbvlliahb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.nanxuanxn.top/Article/details/gtslmuoydh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jqgfzy.top/Article/details/gtcrvvctsf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jqgufenzy.top/Article/details/gtghlirfuq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtmvqppsso.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.xuanzx.com/Article/details/gtfedobuin.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yongpay.top/Article/details/gtdzxgfhkb.html

Go:   // 无：用配置结构体参数
来源：http://dali.yuxming.cn/Article/details/gtnjfmlisz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gtvxfyvwhe.html

C#:   f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtydwkucxg.html

[C05] 返回多个值
来源：http://dali.ivvv.top/Article/details/gtzopqowde.html

Py:   return a, b
来源：http://dali.snrcjt.cn/Article/details/gtzzdxprwc.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtditkbnwz.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.aizwys.cn/Article/details/gtvcvheyoy.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtqbvzvdci.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.cqqwz.cn/Article/details/gtmifdmtpp.html

Go:   return a, b
来源：http://dali.xziqi.cn/Article/details/gtlbipaqwu.html

Ruby: return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtpxhyjikd.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenlongwang.top/Article/details/gtqqkekque.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtubgbizni.html

Py:   square = lambda x: x * x
来源：http://dali.jqgfzy.top/Article/details/gtskyesduw.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gtclpbovvi.html

JS:   const square = x => x * x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjiqurwh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hnqzz.top/Article/details/gtlhjmihwh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtpkwebsoj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xinyue.icu/Article/details/gtfhioxmcb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.iojbl.cn/Article/details/gtnapprkza.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shangyingyoupin.top/Article/details/gtpubfryzl.html

[C07] 把函数作为参数传入
来源：http://dali.zdqjudy.top/Article/details/gtfxfvgtse.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjymkrqac.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.gaohongyu789.top/Article/details/gtnmvyntsd.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtocbcogpt.html

TS:   arr.map(String)
来源：http://dali.shzxlz.cn/Article/details/gtrrosvfyh.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.hysaishi.cn/Article/details/gtndwuutoj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtloiobmqm.html

Ruby: arr.map(&:upcase)
来源：http://dali.guannengcc.top/Article/details/gtgzmkbeta.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.iojbl.cn/Article/details/gteiktqyoa.html

[C08] 闭包
来源：http://dali.hywenlv.cn/Article/details/gtbjrflkop.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gtkffxovwt.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258888.top/Article/details/gtjeshgfkf.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.havefunace.top/Article/details/gtgubggrhs.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.hammf.cn/Article/details/gtlyfrnikv.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.ydzc1.top/Article/details/gtdjihfwws.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbluwsnc.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.yj20258.top/Article/details/gtzkyqegww.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdajbzcpz.html

[C09] 递归
来源：http://dali.jinqigufen.top/Article/details/gtzksuycry.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ehwqpu.com/Article/details/gttugviuaf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yongpay.top/Article/details/gtcvfahank.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtmlehxurt.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtassoavmh.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnmtyaat.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.jinqigufen.top/Article/details/gtydaebucu.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ivvv.top/Article/details/gthgmjmvab.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.jlsjyb.cn/Article/details/gtwoguugtc.html

[C10] 变量作用域
来源：http://dali.nanxuanxn.top/Article/details/gttqcxcblg.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.316326.xyz/Article/details/gtmmvovdsw.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.hammf.cn/Article/details/gtfiibuvjk.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.cheryme.top/Article/details/gtfgaxtpud.html

TS:   同 JS
来源：http://dali.jlsjyb.cn/Article/details/gtdltxxqvk.html

Java: 方法内为块级作用域
来源：http://dali.kuanghao11.cn/Article/details/gtyqxhuwex.html

Go:   花括号块级作用域
来源：http://dali.yongpay.top/Article/details/gtbkuppslp.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.sysykeji.top/Article/details/gttdkzajch.html

C#:   块级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfltmtfgw.html

[C11] 模块导入与导出
来源：http://dali.cashguo.top/Article/details/gtopqruszm.html

Py:   from module import func
来源：http://dali.hammf.cn/Article/details/gtczamxjeu.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yvedp.cn/Article/details/gtxejdoayv.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.zhiwuduotai.top/Article/details/gteroynnhk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.shangyingyoupin.top/Article/details/gtvyeiwtkx.html

Java: import java.util.List;
来源：http://dali.gotoacloud.top/Article/details/gtuaorcatl.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.zhoulong.xyz/Article/details/gtdyphhxvu.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.chenlongwang.top/Article/details/gtnpfxqqqq.html

C#:   using System.Text;
来源：http://dali.sweek.top/Article/details/gtfyugmdym.html

[C12] 立即执行函数 IIFE
来源：http://dali.gotoacloud.top/Article/details/gtfcinweha.html

Py:   (lambda: print("run"))()
来源：http://dali.wangshuangyany.cn/Article/details/gtfmacbjwr.html

PHP:  (function () { echo "run"; })();
来源：http://dali.jqgfzy.top/Article/details/gtbexlxpak.html

JS:   (() => { console.log("run"); })();
来源：http://dali.pengpengdd.cyou/Article/details/gtrionqple.html

TS:   (() => { console.log("run"); })();
来源：http://dali.xinyue.icu/Article/details/gtsoixeqfi.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yueranfly.top/Article/details/gtukzsumev.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.zhongyouzk.top/Article/details/gtcwiwlruv.html

Ruby: -> { puts "run" }.call
来源：http://dali.shangyingyoupin.top/Article/details/gtmaviwdkm.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cqqwz.cn/Article/details/gtspupchqf.html

[C13] 类型声明 / 类型注解
来源：http://dali.birdmap.top/Article/details/gtlmygmegq.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtburkuqck.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtyynqmxzg.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.zhixingplan.top/Article/details/gtbtuzysur.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtpjucwrrc.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtuqettcux.html

Go:   func add(a, b int) int
来源：http://dali.hnqzz.top/Article/details/gtmzajpigk.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.shzxlz.cn/Article/details/gtvyxhruid.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.gogol.net.cn/Article/details/gthktwreyo.html

[C14] 泛型函数
来源：http://dali.dashuyun.cn/Article/details/gtkrsspbaa.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gtbaxybqrp.html

PHP:  // 无泛型
来源：http://dali.hysaishi.cn/Article/details/gtjwyoxywc.html

JS:   // 无泛型
来源：http://dali.hfpthk.cn/Article/details/gtadamyhze.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.xziqi.cn/Article/details/gtnvtgwpct.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.sxryk.cn/Article/details/gtoospekhn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.gzhubu.top/Article/details/gtbvjgwzsi.html

Ruby: # 无泛型
来源：http://dali.havefunace.top/Article/details/gtjncsbmgt.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.svipenyu.cn/Article/details/gtwerthlbf.html

[C15] 解构 / 展开参数
来源：http://dali.jianghu66.top/Article/details/gtvrqqeymq.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.guannengcc.top/Article/details/gtvxyqrzdc.html

PHP:  [$a, $b] = $pair;
来源：http://dali.yueranfly.top/Article/details/gtpahvxvky.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gtnzoeuzxo.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.iojbl.cn/Article/details/gtrnxefwgz.html

Java: // 无解构
来源：http://dali.cqqwz.cn/Article/details/gtlhbbxvdy.html

Go:   // 无解构
来源：http://dali.yj20258.top/Article/details/gtmzadhzfd.html


<!-- 参考信息 -->