代发 wailian999

[A26] 类型转换总览
来源：http://dali.yuxming.cn/Article/details/gt2vwfowmun.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258888.top/Article/details/gt2wqzrbvki.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shuidangran.top/Article/details/gt2uyryfgly.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.svipenyu.cn/Article/details/gt2utnytevy.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258.top/Article/details/gt2zfmhemxx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.jinqigfzy.top/Article/details/gt2wdsxcxee.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.redwolf501.top/Article/details/gt2givtnyqi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuetiantiany.cn/Article/details/gt2giabgcdf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhixingplan.top/Article/details/gt2ifwzohiu.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gt2khepvwwh.html

B. 流程控制
来源：http://dali.meibo888.top/Article/details/gt2gtdbmwjq.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ayjrgyva.html

[B01] 条件判断 if / else
来源：http://dali.ppjwa.cn/Article/details/gt2zeknhvzd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gt2gjdqafyy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2zlvwdxgq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gt2awoitkfb.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2hxrfzcks.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gt2kvscccha.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jqgfzy.top/Article/details/gt2qayeldgt.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ivvv.top/Article/details/gt2znbgirqy.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnqzz.top/Article/details/gt2jilliueh.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gt2lnymvqwz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.mhx1999.top/Article/details/gt2pjfwbzxz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gt2gxywtvjr.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2bbbhdbsp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfsbgdfl.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2eaxyfdsu.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gt2ksxudwcm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tianlin.xyz/Article/details/gt2xuonopxo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2uyvwqfzg.html

[B03] switch / match / case
来源：http://dali.haohaochexian.top/Article/details/gt2tyqqurmq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gt2hcweygeq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2xyjavlec.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sufxvd.cn/Article/details/gt2kckoxwec.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sysykeji.top/Article/details/gt2yzavycqs.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gt2ckbtodkn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gt2hayvgtpx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.redwolf501.top/Article/details/gt2bjsvyhnb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ehwqpu.com/Article/details/gt2jbjoofrn.html

[B04] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2zkjppdms.html

Py:   for i in range(10): print(i)
来源：http://dali.aibaodan.cn/Article/details/gt2gmxvghtc.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gt2hxvryioq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.birdmap.top/Article/details/gt2ecqbivdv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gt2logkdyjn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gt2nmbzhaxg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jlsjyb.cn/Article/details/gt2isnragje.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gt2mxyeoqfh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.sweek.top/Article/details/gt2mkubcbvg.html

[B05] 遍历数组 / 列表
来源：http://dali.yanxiufei.cn/Article/details/gt2rystzlmi.html

Py:   for item in arr: print(item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dncvvypf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.nanxuanxn.top/Article/details/gt2apibuquj.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.aibaodan.cn/Article/details/gt2njtikhzl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gt2ippecjhr.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.quarkkingdee.top/Article/details/gt2tepatkbj.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gt2dlysijom.html

Ruby: arr.each { |item| puts item }
来源：http://dali.chenjidiqi.icu/Article/details/gt2gclswqaq.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.kuanghao11.cn/Article/details/gt2idsphswp.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gt2zyzngqzf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctwgkgiw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yueranfly.top/Article/details/gt2ajdldmck.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gt2kvlyqwkn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gt2owyidbvs.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gt2qkrwegou.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jianghu66.top/Article/details/gt2awfwjjax.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jqgfzy.top/Article/details/gt2jnmvzjwf.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yuanzhike.top/Article/details/gt2erymfghn.html

[B07] while 循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ffzmfrnd.html

Py:   while i < 10: i += 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xqzteoxv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.snrcjt.cn/Article/details/gt2cqupjkaz.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2patnpwfn.html

TS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gt2dngashps.html

Java: while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dmmvqvhm.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gt2jqfprwkq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.xinyue.icu/Article/details/gt2hpymmcdo.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2knkvjmsa.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gt2ipvjtlpq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhongyouzk.top/Article/details/gt2ueoxyory.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gt2rofmmwwa.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gt2cijsuapx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2qqtpvgru.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gt2gofxyjpc.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.quarkkingdee.top/Article/details/gt2qphvbjwb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.aibaodan.cn/Article/details/gt2ktaamxbt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gt2yguyryif.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gt2ctbfhuhv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gt2vyiugxsy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2cfmdayub.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gt2xyeppljz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gt2jtdgrsxv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2moeqjsrd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.dianchejie.cn/Article/details/gt2xrcgexja.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gt2qoohkinu.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gt2lteyeolm.html

[B10] 遍历同时拿索引
来源：http://dali.ivvv.top/Article/details/gt2kyupmunp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ivvv.top/Article/details/gt2wxxbvpkq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuxming.cn/Article/details/gt2wrexplnh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2qhasjnxl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gt2ipogdwki.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.nwbrower.top/Article/details/gt2wsutvmrq.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gt2ycsixybh.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jqgfzy.top/Article/details/gt2kajsksyc.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhongyouzk.top/Article/details/gt2ceikrzjt.html

[B11] 生成数字序列 / 区间
来源：http://dali.jinqigufen.top/Article/details/gt2horzarub.html

Py:   list(range(0, 10, 2))
来源：http://dali.aizwys.cn/Article/details/gt2vsmwvlhi.html

PHP:  range(0, 10, 2);
来源：http://dali.jiagoushi.top/Article/details/gt2lixjmdea.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ydzc1.top/Article/details/gt2nyvpvhrf.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xylfe.cn/Article/details/gt2fyhfkmej.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shangyingyoupin.top/Article/details/gt2rbrzfwrr.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shuidangran.top/Article/details/gt2hzkeeitb.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jinqigfzy.top/Article/details/gt2xeqolvgd.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gt2kieyyqcx.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oeffvhyl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.guowangkeji.top/Article/details/gt2tcghgcec.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.mhx1999.top/Article/details/gt2goceudum.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yanxiufei.cn/Article/details/gt2cmojixma.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnxiangtu.top/Article/details/gt2kjaglcse.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2pslwkewk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jiagoushi.top/Article/details/gt2gkvcbdsk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.birdmap.top/Article/details/gt2qqqfbyjy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gt2uxhfxxdt.html

[B13] 判断是否为数字
来源：http://dali.aizwys.cn/Article/details/gt2suqkxjil.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gt2whwkpntc.html

PHP:  is_numeric($x)
来源：http://dali.pycfn.com/Article/details/gt2tqjkvfep.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yonumen.top/Article/details/gt2hhskwdzs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hfpthk.cn/Article/details/gt2ejfulclg.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gt2aaxipsvs.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhoulong.xyz/Article/details/gt2ozksblmu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lallbvzj.html

C#:   x is int or double or decimal
来源：http://dali.dianchejie.cn/Article/details/gt2cqaglclc.html

[B14] 判断值是否在集合内
来源：http://dali.xuanzx.com/Article/details/gt2gnueyomn.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jiagoushi.top/Article/details/gt2vbqhxohe.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.meibo888.top/Article/details/gt2goxehwzl.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gt2yxqfegjp.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2zijazsvh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2kcerhuly.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xinyue.icu/Article/details/gt2xlmqepgl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.nanxuanxn.top/Article/details/gt2ihllorix.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ppjwa.cn/Article/details/gt2bhcrmaen.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gt2uvitsefl.html

Py:   a and b or not c
来源：http://dali.gotoacloud.top/Article/details/gt2zmtcclen.html

PHP:  $a && $b || !$c
来源：http://dali.hongshengwenyu.top/Article/details/gt2vokzhlfo.html

JS:   a && b || !c
来源：http://dali.guannengcc.top/Article/details/gt2lagqichg.html

TS:   a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gt2lvtgkmmo.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gt2zkcjzkvq.html

Go:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gt2cwcvzxhq.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gt2ofpabxrz.html

C#:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gt2vheydimj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.tian-w.cn/Article/details/gt2zjldzyuc.html

Py:   if not data: return
来源：http://dali.ydzc1.top/Article/details/gt2abjjuigl.html

PHP:  if (!$data) { return; }
来源：http://dali.jqgufenzy.top/Article/details/gt2tozqagdg.html

JS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gt2vmtunihd.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gt2afvfnqcq.html

Java: if (data == null) return;
来源：http://dali.cheryme.top/Article/details/gt2psafoaxy.html

Go:   if data == nil { return }
来源：http://dali.jinqigufen.top/Article/details/gt2jsqindiu.html

Ruby: return if data.nil?
来源：http://dali.jinqigufen.top/Article/details/gt2yxkcjhue.html

C#:   if (data == null) return;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zysxgvrm.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2xpdmcahr.html

C. 函数与作用域
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxmgxfk.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2bzbbqosk.html

[C01] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2yeqnptrb.html

Py:   def add(a, b): return a + b
来源：http://dali.gaohongyu789.top/Article/details/gt2gizmprys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gt2skgkwqut.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pmrhqxct.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gt2iuuwgokk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2pphlwonf.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gt2fioywusy.html

Ruby: def add(a, b); a + b; end
来源：http://dali.0kj1m.cn/Article/details/gt2pshvmrvx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ehwqpu.com/Article/details/gt2srebnnqt.html

[C02] 默认参数
来源：http://dali.bjfxy.top/Article/details/gt2vstoainc.html

Py:   def greet(name="World"): return name
来源：http://dali.yj20258.top/Article/details/gt2urpehdmo.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gt2sjpndefi.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xdamijzv.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gt2cgcuruwv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258.top/Article/details/gt2ltwmbwqh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ivvv.top/Article/details/gt2tqopqadh.html

Ruby: def greet(name = "World") = name
来源：http://dali.tanke756.top/Article/details/gt2jrdzjfxy.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhiwuduotai.top/Article/details/gt2bjbysclz.html

[C03] 可变参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ftvdajwf.html

Py:   def total(*args): return sum(args)
来源：http://dali.cheryme.top/Article/details/gt2ijwirsbh.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2adseeeng.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gt2whycnabq.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gt2xgsuvbjd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sufxvd.cn/Article/details/gt2oufgycce.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojcbmnhx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hnxiangtu.top/Article/details/gt2dnndawhh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.tian-w.cn/Article/details/gt2pmztntdm.html

[C04] 命名参数 / 关键字参数
来源：http://dali.iojbl.cn/Article/details/gt2uqcndzcz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.gaohongyu789.top/Article/details/gt2imzcoebi.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cheryme.top/Article/details/gt2qyhstvib.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yonumen.top/Article/details/gt2btrodzen.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tian-w.cn/Article/details/gt2veiysxpr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.havefunace.top/Article/details/gt2ccosnljm.html

Go:   // 无：用配置结构体参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqucneif.html

Ruby: f(a: 1, b: 2)
来源：http://dali.daria6918.cn/Article/details/gt2nggwtycw.html

C#:   f(a: 1, b: 2)
来源：http://dali.meibo888.top/Article/details/gt2lihzcflv.html

[C05] 返回多个值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xlkaspvh.html

Py:   return a, b
来源：http://dali.feifeiyinyue.top/Article/details/gt2csrdujls.html

PHP:  return [$a, $b];
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bctsbpxy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gt2dhcfmjwc.html

TS:   return { a, b };
来源：http://dali.zhoulong.xyz/Article/details/gt2rcmoyqmb.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.sysykeji.top/Article/details/gt2ndpdqhtn.html

Go:   return a, b
来源：http://dali.bjfxy.top/Article/details/gt2ihsztazt.html

Ruby: return a, b
来源：http://dali.daria6918.cn/Article/details/gt2sscgboaz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuanzx.com/Article/details/gt2avisatcm.html

[C06] 匿名函数 / lambda
来源：http://dali.daxiang520.top/Article/details/gt2otmhemct.html

Py:   square = lambda x: x * x
来源：http://dali.xinyue.icu/Article/details/gt2aczkcdoj.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.tianlin.xyz/Article/details/gt2uqyxquhs.html

JS:   const square = x => x * x;
来源：http://dali.316326.xyz/Article/details/gt2zdhvdldh.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.9152youxi.cn/Article/details/gt2jjepbuab.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jqgufenzy.top/Article/details/gt2xecmqjiz.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2glsfmycs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.fzhhl.top/Article/details/gt2ccogdkhn.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gt2cdbdcqte.html

[C07] 把函数作为参数传入
来源：http://dali.iojbl.cn/Article/details/gt2bpbfjoft.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangdashe.top/Article/details/gt2lfxgaxdb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jiagoushi.top/Article/details/gt2mgrodkwx.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.feifeiyinyue.top/Article/details/gt2mjnrjziy.html

TS:   arr.map(String)
来源：http://dali.smart0.xyz/Article/details/gt2kavzifku.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.zhijiandao.cn/Article/details/gt2ybludpie.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.wangshuangyany.cn/Article/details/gt2elabrasy.html

Ruby: arr.map(&:upcase)
来源：http://dali.jqgufenzy.top/Article/details/gt2keyhvqfh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hysaishi.cn/Article/details/gt2wfepwnga.html

[C08] 闭包
来源：http://dali.ehwqpu.com/Article/details/gt2mqlftzmo.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yueranfly.top/Article/details/gt2oqqsbbqn.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.yj20258.top/Article/details/gt2qlildsjz.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.andypj.xyz/Article/details/gt2rwhptvkf.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.cheryme.top/Article/details/gt2oeaegekf.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.svipenyu.cn/Article/details/gt2muhsjkoj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.gotoacloud.top/Article/details/gt2sgfdgfdx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gt2eaihqgyn.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shzxlz.cn/Article/details/gt2oedkzztm.html

[C09] 递归
来源：http://dali.chenjidiqi.icu/Article/details/gt2hnmlqxqv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.zhiwuduotai.top/Article/details/gt2sfujlbft.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gt2wtjkiyyc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shuidangran.top/Article/details/gt2fkmhimmm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.c1oappe.top/Article/details/gt2ggnoaiwp.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.yangfankeji.com/Article/details/gt2wgengkvx.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ehwqpu.com/Article/details/gt2koxztoyj.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gt2bpjmvuej.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.ehwqpu.com/Article/details/gt2wqwyhziv.html

[C10] 变量作用域
来源：http://dali.zhoulong.xyz/Article/details/gt2gjbltvea.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uiuvumif.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.zhiwuduotai.top/Article/details/gt2pyduevhd.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jyoumei.cn/Article/details/gt2qjbmhqlw.html

TS:   同 JS
来源：http://dali.ivvv.top/Article/details/gt2qqfxzazm.html

Java: 方法内为块级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xetpgzuk.html

Go:   花括号块级作用域
来源：http://dali.zhengqikj.top/Article/details/gt2axalyuzz.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.jinghuilouyu.cn/Article/details/gt2caifizwe.html

C#:   块级作用域
来源：http://dali.hammf.cn/Article/details/gt2ikdediww.html

[C11] 模块导入与导出
来源：http://dali.jinqigufen.top/Article/details/gt2fbnvzqav.html

Py:   from module import func
来源：http://dali.gaohongyu789.top/Article/details/gt2jebkrllw.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.yueranfly.top/Article/details/gt2inxagvih.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.yonumen.top/Article/details/gt2ejwclxtk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.gzhubu.top/Article/details/gt2brnyvucd.html

Java: import java.util.List;
来源：http://dali.quarkkingdee.top/Article/details/gt2epuygpmi.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.ivvv.top/Article/details/gt2qyfbbhpd.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.havefunace.top/Article/details/gt2wpggsdsy.html

C#:   using System.Text;
来源：http://dali.yangfankeji.com/Article/details/gt2tbrtfslo.html

[C12] 立即执行函数 IIFE
来源：http://dali.nanxuanxn.top/Article/details/gt2nddkvemg.html

Py:   (lambda: print("run"))()
来源：http://dali.haohaochexian.top/Article/details/gt2nniutrdc.html

PHP:  (function () { echo "run"; })();
来源：http://dali.nanxinkj.top/Article/details/gt2cvlvliyc.html

JS:   (() => { console.log("run"); })();
来源：http://dali.aibaodan.cn/Article/details/gt2dowehjoa.html

TS:   (() => { console.log("run"); })();
来源：http://dali.smart0.xyz/Article/details/gt2qmjifafu.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.kuanghao11.cn/Article/details/gt2frjzknaz.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.meibo888.top/Article/details/gt2gfdpsygk.html

Ruby: -> { puts "run" }.call
来源：http://dali.zhixingplan.top/Article/details/gt2emhmdafx.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.nwbrower.top/Article/details/gt2wpvomcod.html

[C13] 类型声明 / 类型注解
来源：http://dali.hysaishi.cn/Article/details/gt2jlzchcek.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.fengsongda.top/Article/details/gt2llhnvsgq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gt2qetnsykr.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.yj20258888.top/Article/details/gt2ujnwxxic.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gt2qckljkre.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.tian-w.cn/Article/details/gt2znfkckpt.html

Go:   func add(a, b int) int
来源：http://dali.sxryk.cn/Article/details/gt2paxxoaqn.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.daxiang520.top/Article/details/gt2vybnflgl.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.kuanghao11.cn/Article/details/gt2eooxmtuf.html

[C14] 泛型函数
来源：http://dali.jinqigufen.top/Article/details/gt2rwiyzcxp.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.xziqi.cn/Article/details/gt2anszhvot.html

PHP:  // 无泛型
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqccrmub.html

JS:   // 无泛型
来源：http://dali.vqdsnc.cn/Article/details/gt2ylzkxxks.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.ehwqpu.com/Article/details/gt2xdpipmej.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.svipenyu.cn/Article/details/gt2yvytpgox.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.ydzc1.top/Article/details/gt2lzpdtwhm.html

Ruby: # 无泛型
来源：http://dali.smart0.xyz/Article/details/gt2xzyhyslp.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.ydzc1.top/Article/details/gt2mjwekkit.html

[C15] 解构 / 展开参数
来源：http://dali.jlsjyb.cn/Article/details/gt2ctywbsuz.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.snrcjt.cn/Article/details/gt2jctgsafx.html

PHP:  [$a, $b] = $pair;
来源：http://dali.sysykeji.top/Article/details/gt2yuptqohy.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.pycfn.com/Article/details/gt2majhaksr.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.yonumen.top/Article/details/gt2bkdgqfct.html

Java: // 无解构
来源：http://dali.sysykeji.top/Article/details/gt2pvuhpxge.html

Go:   // 无解构
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdcxzpy.html

Ruby: a, b = pair
来源：http://dali.ivvv.top/Article/details/gt2qhsnhjiu.html

C#:   var (a, b) = pair;
来源：http://dali.cqqwz.cn/Article/details/gt2gnqjnhqv.html

[C16] 函数 / 方法重载
来源：http://dali.yanxiufei.cn/Article/details/gt2mknpctta.html

Py:   # 无重载：用默认参数或 *args 变通
来源：http://dali.tanke756.top/Article/details/gt2pfpztszl.html

PHP:  // 无重载
来源：http://dali.hnqzz.top/Article/details/gt2qnvefsqh.html

JS:   // 无重载：靠 arguments.length 分支
来源：http://dali.jiagoushi.top/Article/details/gt2idbhrnql.html

TS:   // 用联合类型或重载签名声明
来源：http://dali.nanxuanxn.top/Article/details/gt2ilwzzont.html

Java: void f(int a) {}  void f(String a) {}
来源：http://dali.yuxming.cn/Article/details/gt2wpvbpres.html


<!-- 参考信息 -->