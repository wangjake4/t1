代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gt2zrvtaldh.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxpismjj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gzhubu.top/Article/details/gt2xsrtpbxr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yonumen.top/Article/details/gt2rdhtuyje.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.redwolf501.top/Article/details/gt2fndeuqpq.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.meibo888.top/Article/details/gt2hwltslsv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.shuidangran.top/Article/details/gt2jweyeswo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yangfankeji.com/Article/details/gt2kqqpaiak.html

[A26] 类型转换总览
来源：http://dali.yueranfly.top/Article/details/gt2qzygfnxq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gogol.net.cn/Article/details/gt2tzmuzjnw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ydzc1.top/Article/details/gt2csgdvutu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gt2wuxvptad.html

TS:   Number() String() Boolean() x as number
来源：http://dali.ydzc1.top/Article/details/gt2wdeajmwf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gt2ygngfafu.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xziqi.cn/Article/details/gt2vvrxgiav.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cqqwz.cn/Article/details/gt2yairloox.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gt2uljgqfxn.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2dsauptlf.html

B. 流程控制
来源：http://dali.hnxiangtu.top/Article/details/gt2harlhxof.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gt2tmtomeeh.html

[B01] 条件判断 if / else
来源：http://dali.pycfn.com/Article/details/gt2iellizlw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ybcxt.top/Article/details/gt2ioteioyh.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xylfe.cn/Article/details/gt2ptdfyltt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.nanxuanxn.top/Article/details/gt2ktjgtvpv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.iojbl.cn/Article/details/gt2lqgohcmk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gt2tgxsoepa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gt2mhoeyfia.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ezhhpwcp.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gotoacloud.top/Article/details/gt2eutduvcg.html

[B02] 多分支 else if / elif
来源：http://dali.gotoacloud.top/Article/details/gt2krreeetm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhiwuduotai.top/Article/details/gt2dxitesfl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2fiacnhjt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gt2czypchid.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gt2ittlheyc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gt2hprwvbbv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.wangdashe.top/Article/details/gt2ereaaopb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hywenlv.cn/Article/details/gt2byvifjth.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nwbrower.top/Article/details/gt2fwuwnqhh.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gt2imtzbohi.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.fzhhl.top/Article/details/gt2aclnzxds.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qknqmbvz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gt2zmpafkfj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2swkzfzgi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gt2qrfdmuay.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zhixingplan.top/Article/details/gt2eixlhbib.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gzhubu.top/Article/details/gt2jjuzsmhg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sweek.top/Article/details/gt2lsromfzs.html

[B04] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2nuepeydy.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gt2jnrjqavf.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tian-w.cn/Article/details/gt2crxkelyd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aizwys.cn/Article/details/gt2xcnrtvzk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2zfhnnbom.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvkrsyrr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jiagoushi.top/Article/details/gt2unnskcun.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zdqjudy.top/Article/details/gt2gbvceuyj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.aibaodan.cn/Article/details/gt2mhobdksp.html

[B05] 遍历数组 / 列表
来源：http://dali.sysykeji.top/Article/details/gt2qcqbxack.html

Py:   for item in arr: print(item)
来源：http://dali.ydzc1.top/Article/details/gt2ooxptvcv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ctmuxeih.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gt2kcebqufg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gt2hpceunzi.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guannengcc.top/Article/details/gt2lfjhkons.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangdashe.top/Article/details/gt2jiaeudjk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.feifeiyinyue.top/Article/details/gt2vtyfilhs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinqigufen.top/Article/details/gt2bkqppyme.html

[B06] 遍历字典 / 对象
来源：http://dali.yueranfly.top/Article/details/gt2nwgbnkrp.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.guannengcc.top/Article/details/gt2zujkgott.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhongyouzk.top/Article/details/gt2ijkvbmbt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nanxuanxn.top/Article/details/gt2nhldljgm.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gt2qtuxpasr.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.aibaodan.cn/Article/details/gt2baocbpea.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oywbenxd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.0kj1m.cn/Article/details/gt2utvungar.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.smart0.xyz/Article/details/gt2rntdjrqm.html

[B07] while 循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2eslgiyso.html

Py:   while i < 10: i += 1
来源：http://dali.zycfv.cn/Article/details/gt2oqdhmgvh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vuhxciby.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gt2bgqafcti.html

TS:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gt2cmbdmrbn.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gruysdag.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yj20258.top/Article/details/gt2shjknznw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.birdmap.top/Article/details/gt2aimsvgzg.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gt2zcqlbrcu.html

[B08] do-while（至少执行一次）
来源：http://dali.meibo888.top/Article/details/gt2jmaviwqa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.tianlin.xyz/Article/details/gt2rwgmgfoh.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hywenlv.cn/Article/details/gt2fbtyrzuc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gt2wwucshoh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gt2umnzvovn.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bakzoqml.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xinyue.icu/Article/details/gt2sqohecji.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.bjfxy.top/Article/details/gt2mnloxwdr.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jsfdrvaj.html

[B09] break 与 continue
来源：http://dali.yuanzhike.top/Article/details/gt2opzeonbr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2ikwjkfsa.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gt2bftidozg.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gt2xyswxbdr.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gt2oobscblb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gt2zoafkkte.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eyntlhvp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.redwolf501.top/Article/details/gt2fepwmmtv.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2ghxujjst.html

[B10] 遍历同时拿索引
来源：http://dali.zdqjudy.top/Article/details/gt2oayhcqqv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hammf.cn/Article/details/gt2vyojtzvx.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hywenlv.cn/Article/details/gt2itufclua.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gt2lbeqjmdk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gt2spsouiln.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gt2fztawiwt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gogol.net.cn/Article/details/gt2rdpmhriu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuxming.cn/Article/details/gt2nwbnfcpm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovkeirlf.html

[B11] 生成数字序列 / 区间
来源：http://dali.ehwqpu.com/Article/details/gt2zcjecjut.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gt2hhbenakd.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gt2ajcdxpqm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.haohaochexian.top/Article/details/gt2splaffvl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gt2rlgfrzfj.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.nanxinkj.top/Article/details/gt2avwbgxhn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.hfpthk.cn/Article/details/gt2uvhnizkw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.kuanghao11.cn/Article/details/gt2nwfdbopo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangshuangyany.cn/Article/details/gt2whrebrlu.html

[B12] 跳出多层循环
来源：http://dali.nanxuanxn.top/Article/details/gt2kjvnorif.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zdqjudy.top/Article/details/gt2dzjqcdco.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.iojbl.cn/Article/details/gt2iouadlgg.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hayhzntk.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2dgxponjy.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.haohaochexian.top/Article/details/gt2spshbxie.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.316326.xyz/Article/details/gt2oxqjseez.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuanzhike.top/Article/details/gt2crselbdy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fzhhl.top/Article/details/gt2hcnzikgc.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kcgsqgeu.html

Py:   isinstance(x, (int, float))
来源：http://dali.andypj.xyz/Article/details/gt2ucozgtan.html

PHP:  is_numeric($x)
来源：http://dali.dianchejie.cn/Article/details/gt2ehndcegq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2bsxewfuy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guannengcc.top/Article/details/gt2otzjeqho.html

Java: x instanceof Number
来源：http://dali.xuetiantiany.cn/Article/details/gt2xqcpgupb.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vobuubmv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xuetiantiany.cn/Article/details/gt2kratbkrm.html

C#:   x is int or double or decimal
来源：http://dali.jiagoushi.top/Article/details/gt2uswmigby.html

[B14] 判断值是否在集合内
来源：http://dali.zycfv.cn/Article/details/gt2qutjdnxv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.hnxiangtu.top/Article/details/gt2nwquzler.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.9152youxi.cn/Article/details/gt2vvzhdtvb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2swxzlgpr.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yonumen.top/Article/details/gt2dygtdhmw.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yj202588.top/Article/details/gt2crytykih.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gt2pqrjytur.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gt2xbjnpcfk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.birdmap.top/Article/details/gt2xkaokqms.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gt2ouljykwh.html

Py:   a and b or not c
来源：http://dali.daxiang520.top/Article/details/gt2jjdssecp.html

PHP:  $a && $b || !$c
来源：http://dali.jlsjyb.cn/Article/details/gt2wnsqdhrw.html

JS:   a && b || !c
来源：http://dali.yj20258888.top/Article/details/gt2eqepxnbb.html

TS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2vibrornd.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gt2ngfbootm.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gt2htuyzkja.html

Ruby: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gt2ncqcxmxj.html

C#:   a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gt2qyhxgrby.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gt2qeaxhqpd.html

Py:   if not data: return
来源：http://dali.dianchejie.cn/Article/details/gt2qodgpiml.html

PHP:  if (!$data) { return; }
来源：http://dali.ivvv.top/Article/details/gt2ugbnidpw.html

JS:   if (!data) return;
来源：http://dali.yongpay.top/Article/details/gt2qpfkkhko.html

TS:   if (!data) return;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqzlwfyj.html

Java: if (data == null) return;
来源：http://dali.sxryk.cn/Article/details/gt2huzonvcd.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gt2gidotjjd.html

Ruby: return if data.nil?
来源：http://dali.sufxvd.cn/Article/details/gt2rwzpwfff.html

C#:   if (data == null) return;
来源：http://dali.jyoumei.cn/Article/details/gt2guvtixls.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2oatdywyg.html

C. 函数与作用域
来源：http://dali.jiagoushi.top/Article/details/gt2lcueujde.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2fgtyyatp.html

[C01] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2ipjaguqn.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gt2mfeuzqin.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gt2rollpvpl.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gt2yckglmlz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2fbgvczsn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hammf.cn/Article/details/gt2uhbxhnss.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gaohongyu789.top/Article/details/gt2thgqgqvi.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigfzy.top/Article/details/gt2cgqypqpp.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gt2ivearopj.html

[C02] 默认参数
来源：http://dali.smart0.xyz/Article/details/gt2ozfxvdqe.html

Py:   def greet(name="World"): return name
来源：http://dali.sxryk.cn/Article/details/gt2upukrvwh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gaohongyu789.top/Article/details/gt2qohocyon.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uxmkchih.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gt2pzgzvdql.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.dianchejie.cn/Article/details/gt2etzzjeju.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gt2ufozzqcl.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gt2ojopteyq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.pengpengdd.cyou/Article/details/gt2zzvmbrxw.html

[C03] 可变参数
来源：http://dali.gogol.net.cn/Article/details/gt2ptqngpmx.html

Py:   def total(*args): return sum(args)
来源：http://dali.fengsongda.top/Article/details/gt2oyqeehbz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yuxming.cn/Article/details/gt2vymcxyai.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gt2iiynnijq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hywenlv.cn/Article/details/gt2pgxqtjxa.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2uilchtha.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgufenzy.top/Article/details/gt2lmpiawfo.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.shuidangran.top/Article/details/gt2fcptgtna.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cdnleiting.top/Article/details/gt2yzjldqfc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.meibo888.top/Article/details/gt2kowxipfr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mcxgmzky.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2zzaredmg.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xziqi.cn/Article/details/gt2npmgcfif.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gt2rfptqhpk.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gt2fwvdblcn.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gt2cauqjxzs.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jlsjyb.cn/Article/details/gt2bspeecbu.html

C#:   f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2cjtdvzbj.html

[C05] 返回多个值
来源：http://dali.yj20258888.top/Article/details/gt2nigmkxpt.html

Py:   return a, b
来源：http://dali.zycfv.cn/Article/details/gt2vawmrdor.html

PHP:  return [$a, $b];
来源：http://dali.sxryk.cn/Article/details/gt2aoatleaa.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2upzyiuqj.html

TS:   return { a, b };
来源：http://dali.hammf.cn/Article/details/gt2jvbirnbf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tmsyfkzz.html

Go:   return a, b
来源：http://dali.xuetiantiany.cn/Article/details/gt2gvyrdqcl.html

Ruby: return a, b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssilgjxz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hammf.cn/Article/details/gt2wkzegtcd.html

[C06] 匿名函数 / lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2nwprzmog.html

Py:   square = lambda x: x * x
来源：http://dali.pycfn.com/Article/details/gt2indhnfjy.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yueranfly.top/Article/details/gt2akzmavrx.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvivdlwp.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gt2hcftizxd.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.ehwqpu.com/Article/details/gt2niifzknd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hongshengwenyu.top/Article/details/gt2muwysbju.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uznqfgtn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2moxsnmck.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gt2jxsbubgb.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.snrcjt.cn/Article/details/gt2kbijiftx.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jyoumei.cn/Article/details/gt2oupzxoxv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hfpthk.cn/Article/details/gt2tdsjetex.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2pmxeleql.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.cqqwz.cn/Article/details/gt2piyzihgz.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gt2ucyzuvhm.html

Ruby: arr.map(&:upcase)
来源：http://dali.fengsongda.top/Article/details/gt2xujqrocb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gt2uohyqzxu.html

[C08] 闭包
来源：http://dali.haohaochexian.top/Article/details/gt2qaqkolei.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shangyingyoupin.top/Article/details/gt2gjzkgvlu.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ipccrdrc.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.nanxuanxn.top/Article/details/gt2qmvpxrtd.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rmtmpkua.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.cdnleiting.top/Article/details/gt2hvfxuwpi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.tanke756.top/Article/details/gt2tvuvfaxi.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aibaodan.cn/Article/details/gt2ukdzvlnj.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gt2fmtyfolf.html

[C09] 递归
来源：http://dali.316326.xyz/Article/details/gt2whakofjd.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rsdvrvwx.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xylfe.cn/Article/details/gt2dyqptfvz.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.nwbrower.top/Article/details/gt2yaeukjyj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.tanke756.top/Article/details/gt2shyqmhhy.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.snrcjt.cn/Article/details/gt2kpplkctx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yj20258888.top/Article/details/gt2zvskhbee.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.xziqi.cn/Article/details/gt2pceffily.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.redwolf501.top/Article/details/gt2nvalehpd.html

[C10] 变量作用域
来源：http://dali.yuxming.cn/Article/details/gt2yakrqtjw.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gt2bnpshpgf.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.wangdashe.top/Article/details/gt2cavxriwr.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.pengpengdd.cyou/Article/details/gt2ezmbmtat.html

TS:   同 JS
来源：http://dali.aibaodan.cn/Article/details/gt2eqhzfpol.html

Java: 方法内为块级作用域
来源：http://dali.aizwys.cn/Article/details/gt2agylausp.html

Go:   花括号块级作用域
来源：http://dali.xinyue.icu/Article/details/gt2oiddfncg.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.iojbl.cn/Article/details/gt2xlichrlz.html

C#:   块级作用域
来源：http://dali.gogol.net.cn/Article/details/gt2ckkzmajl.html

[C11] 模块导入与导出
来源：http://dali.dianchejie.cn/Article/details/gt2aefjcnhp.html

Py:   from module import func
来源：http://dali.shzxlz.cn/Article/details/gt2wbrzyyyv.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.aibaodan.cn/Article/details/gt2ussugjsz.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.wangdashe.top/Article/details/gt2mzyscaew.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.yuanzhike.top/Article/details/gt2qimkgtnh.html

Java: import java.util.List;
来源：http://dali.snrcjt.cn/Article/details/gt2nybetiqr.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.gogol.net.cn/Article/details/gt2fqludjoe.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gt2pzmuuzlp.html

C#:   using System.Text;
来源：http://dali.guannengcc.top/Article/details/gt2ivpbqifp.html

[C12] 立即执行函数 IIFE
来源：http://dali.vqdsnc.cn/Article/details/gt2lrziajjo.html

Py:   (lambda: print("run"))()
来源：http://dali.guowangkeji.top/Article/details/gt2vmcvhxym.html

PHP:  (function () { echo "run"; })();
来源：http://dali.feifeiyinyue.top/Article/details/gt2brniddfs.html

JS:   (() => { console.log("run"); })();
来源：http://dali.sysykeji.top/Article/details/gt2ghhfswio.html

TS:   (() => { console.log("run"); })();
来源：http://dali.hongshengwenyu.top/Article/details/gt2jnwxarqb.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.yonumen.top/Article/details/gt2cxlbswmz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.yangfankeji.com/Article/details/gt2yagennli.html

Ruby: -> { puts "run" }.call
来源：http://dali.ivvv.top/Article/details/gt2sjpugpxu.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2ontxfqlf.html

[C13] 类型声明 / 类型注解
来源：http://dali.yvedp.cn/Article/details/gt2fzkwurqp.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.bjfxy.top/Article/details/gt2lhowwuce.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gt2snghtfct.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yuxming.cn/Article/details/gt2dauvgccu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2rseenekf.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gt2xrycnxkw.html

Go:   func add(a, b int) int
来源：http://dali.jqgufenzy.top/Article/details/gt2oinjldhp.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.yangfankeji.com/Article/details/gt2zvhrryur.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.dashuyun.cn/Article/details/gt2rmyctswa.html

[C14] 泛型函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hihicpeu.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gt2bxfxjhtx.html

PHP:  // 无泛型
来源：http://dali.pengpengdd.cyou/Article/details/gt2yfgotrzu.html

JS:   // 无泛型
来源：http://dali.gotoacloud.top/Article/details/gt2dzjutvcr.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ydzc1.top/Article/details/gt2ldkdsmny.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2taqpizkv.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.jyoumei.cn/Article/details/gt2jbtdfuet.html

Ruby: # 无泛型
来源：http://dali.daxiang520.top/Article/details/gt2dclnxpcm.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.316326.xyz/Article/details/gt2fmvdwftb.html

[C15] 解构 / 展开参数
来源：http://dali.yueranfly.top/Article/details/gt2ehbgfoer.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.yuxming.cn/Article/details/gt2jvtsldxf.html

PHP:  [$a, $b] = $pair;
来源：http://dali.shzxlz.cn/Article/details/gt2weusndhm.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibvetayu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.jqgfzy.top/Article/details/gt2whqfckka.html

Java: // 无解构
来源：http://dali.xuanzx.com/Article/details/gt2kendtcsw.html

Go:   // 无解构
来源：http://dali.zhiwuduotai.top/Article/details/gt2mkssrfla.html


<!-- 参考信息 -->