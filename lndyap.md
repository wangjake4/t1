代发 wailian999

Py:   s1 == s2; s1 != s2
来源：http://dali.yuxming.cn/Article/details/gt2guplhijz.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigfzy.top/Article/details/gt2ffjlxmlc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2emjbknqn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.svipenyu.cn/Article/details/gt2afrvuqvh.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ckigufwx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gt2lvdvjmuu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.hongshengwenyu.top/Article/details/gt2micrmvdv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zhengqikj.top/Article/details/gt2wnrjoodq.html

[A26] 类型转换总览
来源：http://dali.tianlin.xyz/Article/details/gt2ygytzwxc.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenlongwang.top/Article/details/gt2ifmkswjx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinqigfzy.top/Article/details/gt2lumjucwi.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zycfv.cn/Article/details/gt2hdspcgtu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gt2pbyzwdxi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gt2oatquvic.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jiagoushi.top/Article/details/gt2umzcwppt.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gt2zguwjatf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnxiangtu.top/Article/details/gt2hofwfsiy.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2xrtdjmpk.html

B. 流程控制
来源：http://dali.sweek.top/Article/details/gt2oyqejvim.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2eoahfelo.html

[B01] 条件判断 if / else
来源：http://dali.fzhhl.top/Article/details/gt2plhwxmoh.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.ppjwa.cn/Article/details/gt2gmmcdtrq.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kvyjafjw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.pengpengdd.cyou/Article/details/gt2dggdhglk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gt2tybdodwx.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gt2iwrgfswc.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gt2qogltduk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhiwuduotai.top/Article/details/gt2ygavlqvg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yongpay.top/Article/details/gt2tmfwqjmk.html

[B02] 多分支 else if / elif
来源：http://dali.shuidangran.top/Article/details/gt2irwcbjmi.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jyoumei.cn/Article/details/gt2tlwrsmac.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xuanzx.com/Article/details/gt2josdmohs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sweek.top/Article/details/gt2srhihmcq.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gt2dczkiqba.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gt2czscxiqv.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ydzc1.top/Article/details/gt2xvzisxbz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gt2aoowdqih.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gt2ubmmrgtd.html

[B03] switch / match / case
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pwvqjwvy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jiagoushi.top/Article/details/gt2bjktihcb.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2rmcqsgko.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.dianchejie.cn/Article/details/gt2wqfiiuyr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gt2gwnfqlvu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gt2ksyqlvog.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jlsjyb.cn/Article/details/gt2jeeattog.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.9152youxi.cn/Article/details/gt2uotxdfbz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sufxvd.cn/Article/details/gt2tucypoju.html

[B04] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2ealspnbz.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mzdztwqg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.redwolf501.top/Article/details/gt2hpvhrjoz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuanzx.com/Article/details/gt2lugwoqpq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hongshengwenyu.top/Article/details/gt2tsoiylzu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.snrcjt.cn/Article/details/gt2crgbjpwx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.snrcjt.cn/Article/details/gt2evtstbpq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gt2oxcpknry.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.smart0.xyz/Article/details/gt2bzieuhxy.html

[B05] 遍历数组 / 列表
来源：http://dali.cucudq.cn/Article/details/gt2idwngidr.html

Py:   for item in arr: print(item)
来源：http://dali.yuxming.cn/Article/details/gt2jabfoxxp.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.daxiang520.top/Article/details/gt2jjarvhzz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gt2pbzrutdm.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fengsongda.top/Article/details/gt2bectdvja.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.vqdsnc.cn/Article/details/gt2utsbsucz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hywenlv.cn/Article/details/gt2oqxyetew.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bjwhxzjg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.tian-w.cn/Article/details/gt2ivusmsif.html

[B06] 遍历字典 / 对象
来源：http://dali.tianlin.xyz/Article/details/gt2nyxcyxfs.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yanxiufei.cn/Article/details/gt2pgdijdnn.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2mdntblgu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gt2fihednvw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gt2tjygdiby.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.zhiwuduotai.top/Article/details/gt2fjuapach.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gzhubu.top/Article/details/gt2cuymkspe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pycfn.com/Article/details/gt2ozeabtmc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gt2yqurycxx.html

[B07] while 循环
来源：http://dali.jqgufenzy.top/Article/details/gt2ymxsdgrb.html

Py:   while i < 10: i += 1
来源：http://dali.shuidangran.top/Article/details/gt2nmmcaime.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dianchejie.cn/Article/details/gt2nvowzcji.html

JS:   while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gt2nxlfbwha.html

TS:   while (i < 10) { i++; }
来源：http://dali.yj20258.top/Article/details/gt2wermvjyo.html

Java: while (i < 10) { i++; }
来源：http://dali.jianghu66.top/Article/details/gt2yhlklhhb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.andypj.xyz/Article/details/gt2urdrdlls.html

Ruby: while i < 10; i += 1; end
来源：http://dali.iojbl.cn/Article/details/gt2vlzuslkq.html

C#:   while (i < 10) { i++; }
来源：http://dali.c1oappe.top/Article/details/gt2jcslppsd.html

[B08] do-while（至少执行一次）
来源：http://dali.cheryme.top/Article/details/gt2voyuczgg.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.andypj.xyz/Article/details/gt2gantddcd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.meibo888.top/Article/details/gt2vemjtkyo.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2viytlqxj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.xziqi.cn/Article/details/gt2ahizypru.html

Java: do { i++; } while (i < 10);
来源：http://dali.vqdsnc.cn/Article/details/gt2bwmkbuzi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gt2hbnnalwk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.snrcjt.cn/Article/details/gt2oisjjute.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gt2xvnkxyki.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gt2coeeishy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.andypj.xyz/Article/details/gt2wmingson.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gt2byvntchj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2kbxhjpqx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gt2qokcuuwg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gt2rjvgjdzc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2zynpjstt.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gt2ebqlotkk.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2efdbkrsg.html

[B10] 遍历同时拿索引
来源：http://dali.nanxuanxn.top/Article/details/gt2ebrrvsab.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.dashuyun.cn/Article/details/gt2hqlfwynt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.svipenyu.cn/Article/details/gt2bghtpwkf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.sysykeji.top/Article/details/gt2erzucrmf.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.svipenyu.cn/Article/details/gt2ufynfhcm.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sufxvd.cn/Article/details/gt2odmvveio.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhijiandao.cn/Article/details/gt2zbqiuozu.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gt2piddejdm.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258.top/Article/details/gt2ozmieotw.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vkzrikje.html

Py:   list(range(0, 10, 2))
来源：http://dali.hongshengwenyu.top/Article/details/gt2lubaevmv.html

PHP:  range(0, 10, 2);
来源：http://dali.kuanghao11.cn/Article/details/gt2dwakbgim.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ftcnkxrs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gt2nxgbdumc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.iojbl.cn/Article/details/gt2ixieemtv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gt2pvsiwiva.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gt2wmgdzcpj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hnxiangtu.top/Article/details/gt2sbeacpev.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gt2oqhnjuiu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.aibaodan.cn/Article/details/gt2tpsgkxzt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jiagoushi.top/Article/details/gt2prgzunho.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhengqikj.top/Article/details/gt2aormzevv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xtzeyynw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.c1oappe.top/Article/details/gt2dtngxfsr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.nanxinkj.top/Article/details/gt2zmsyzyws.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj20258.top/Article/details/gt2lpfuupdp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aibaodan.cn/Article/details/gt2bicrqyqj.html

[B13] 判断是否为数字
来源：http://dali.fzhhl.top/Article/details/gt2xpseftto.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gt2felpmrrn.html

PHP:  is_numeric($x)
来源：http://dali.shzxlz.cn/Article/details/gt2zjwqpxgs.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zdqjudy.top/Article/details/gt2ibwnbyab.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2rybucvaq.html

Java: x instanceof Number
来源：http://dali.iojbl.cn/Article/details/gt2xuiwxqjf.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cucudq.cn/Article/details/gt2vcukybtz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhoulong.xyz/Article/details/gt2aoujoxqe.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gt2uyhjlede.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gt2nrdcjynr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gt2jwuqotar.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.fengsongda.top/Article/details/gt2gdpctalc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj202588.top/Article/details/gt2ddhebeds.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gt2lvgcaavh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.quarkkingdee.top/Article/details/gt2xkyddxvs.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gt2behsfyxv.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.0kj1m.cn/Article/details/gt2tlzirljr.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigufen.top/Article/details/gt2yxdjbgah.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gt2bmvkzjul.html

Py:   a and b or not c
来源：http://dali.9152youxi.cn/Article/details/gt2hsicoosh.html

PHP:  $a && $b || !$c
来源：http://dali.tianlin.xyz/Article/details/gt2hgrqievy.html

JS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gt2nimzlnqq.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gt2dcgbhqaq.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gt2uyoyuuio.html

Go:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gt2bazjwgmu.html

Ruby: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gt2lmtwhxcd.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gt2ovgeqrgz.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ydzc1.top/Article/details/gt2pmprbixu.html

Py:   if not data: return
来源：http://dali.jqgfzy.top/Article/details/gt2tzpwgjmk.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gt2bzmmhjkp.html

JS:   if (!data) return;
来源：http://dali.feifeiyinyue.top/Article/details/gt2kzcqdbsp.html

TS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gt2qhbcjysn.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2qswczibm.html

Go:   if data == nil { return }
来源：http://dali.zhengqikj.top/Article/details/gt2nxxyytej.html

Ruby: return if data.nil?
来源：http://dali.xuetiantiany.cn/Article/details/gt2eafuvhsv.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gt2aizkpxxl.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2rbszpgiu.html

C. 函数与作用域
来源：http://dali.xinyue.icu/Article/details/gt2hnjdosyi.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2rwafhrso.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2mrvhreby.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2zneaxwju.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gt2lpxvexbh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.xylfe.cn/Article/details/gt2ulvyjbdm.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gt2jeroadtt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.fengsongda.top/Article/details/gt2drngykcy.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.aizwys.cn/Article/details/gt2hryndtia.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nwbrower.top/Article/details/gt2mcnxlohs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cheryme.top/Article/details/gt2hvwzxdbx.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jtghwivu.html

Py:   def greet(name="World"): return name
来源：http://dali.shzxlz.cn/Article/details/gt2smbuafhv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yonumen.top/Article/details/gt2bljyfwch.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fzmcgeog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xltqltqy.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yueranfly.top/Article/details/gt2bthuotud.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.birdmap.top/Article/details/gt2arnqocgf.html

Ruby: def greet(name = "World") = name
来源：http://dali.sweek.top/Article/details/gt2dgviovnu.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.chenzaomai.com/Article/details/gt2nfmtzfzp.html

[C03] 可变参数
来源：http://dali.jlsjyb.cn/Article/details/gt2dmiyqrek.html

Py:   def total(*args): return sum(args)
来源：http://dali.yuxming.cn/Article/details/gt2bykqrqdl.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.dianchejie.cn/Article/details/gt2ipisokku.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gt2pjdqfizc.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.andypj.xyz/Article/details/gt2lwfycoww.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gt2dcwwcksb.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuxming.cn/Article/details/gt2irnoqlbr.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2ziermzon.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.gogol.net.cn/Article/details/gt2ialcjzjf.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhoulong.xyz/Article/details/gt2ggffufhq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gt2kjeohkfm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ehwqpu.com/Article/details/gt2momfyliq.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.chenlongwang.top/Article/details/gt2bsuadtkm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gt2amiogafe.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.bjfxy.top/Article/details/gt2opcxthqf.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj202588.top/Article/details/gt2jeazrljn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gt2pafqaypi.html

C#:   f(a: 1, b: 2)
来源：http://dali.cucudq.cn/Article/details/gt2elckoaoa.html

[C05] 返回多个值
来源：http://dali.9152youxi.cn/Article/details/gt2wkjnitjh.html

Py:   return a, b
来源：http://dali.guowangkeji.top/Article/details/gt2rnooezxs.html

PHP:  return [$a, $b];
来源：http://dali.cucudq.cn/Article/details/gt2ozwgcgrl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dgyodzpi.html

TS:   return { a, b };
来源：http://dali.zhijiandao.cn/Article/details/gt2aeowgzqn.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.guowangkeji.top/Article/details/gt2yhbbwfgr.html

Go:   return a, b
来源：http://dali.haohaochexian.top/Article/details/gt2ckhebbsi.html

Ruby: return a, b
来源：http://dali.hysaishi.cn/Article/details/gt2zuskotqj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ydzc1.top/Article/details/gt2aowvkzva.html

[C06] 匿名函数 / lambda
来源：http://dali.dashuyun.cn/Article/details/gt2xkaehuay.html

Py:   square = lambda x: x * x
来源：http://dali.shangyingyoupin.top/Article/details/gt2xbztoiwz.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.sweek.top/Article/details/gt2umorsibg.html

JS:   const square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mkwhxvna.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhongyouzk.top/Article/details/gt2npukuifi.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.aibaodan.cn/Article/details/gt2euuomloj.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ehwqpu.com/Article/details/gt2cxduthbh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gt2cddumhwi.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.shzxlz.cn/Article/details/gt2fqenujkj.html

[C07] 把函数作为参数传入
来源：http://dali.sufxvd.cn/Article/details/gt2zbcngzvj.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.wangdashe.top/Article/details/gt2bamymjtp.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.cucudq.cn/Article/details/gt2dmnzvgof.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.snrcjt.cn/Article/details/gt2ylbwdswe.html

TS:   arr.map(String)
来源：http://dali.dashuyun.cn/Article/details/gt2rfpindrx.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.ppjwa.cn/Article/details/gt2uweyhook.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.ppjwa.cn/Article/details/gt2cyythuiw.html

Ruby: arr.map(&:upcase)
来源：http://dali.cucudq.cn/Article/details/gt2sbjzxinj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.snrcjt.cn/Article/details/gt2swvykfwo.html

[C08] 闭包
来源：http://dali.zhengqikj.top/Article/details/gt2riqjjqyp.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ehwqpu.com/Article/details/gt2flznbrmr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2eprfvrqi.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jyoumei.cn/Article/details/gt2cflmhbdp.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2hswlodis.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.yj20258888.top/Article/details/gt2syovpbew.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.svipenyu.cn/Article/details/gt2huifzsps.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.aizwys.cn/Article/details/gt2oggnabwu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.smart0.xyz/Article/details/gt2fcfrlkwv.html

[C09] 递归
来源：http://dali.gotoacloud.top/Article/details/gt2ozpuelpe.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gt2bxnofltu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhengqikj.top/Article/details/gt2xvtdbite.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gt2vzjhjsnm.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jqgufenzy.top/Article/details/gt2wlxosyyt.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.tanke756.top/Article/details/gt2pkojobyk.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yonumen.top/Article/details/gt2kdvuokmm.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gt2ismithlm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zhiwuduotai.top/Article/details/gt2xulrlqnk.html

[C10] 变量作用域
来源：http://dali.nanxinkj.top/Article/details/gt2uqarcwpo.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.hongshengwenyu.top/Article/details/gt2isjxzwvs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ppjwa.cn/Article/details/gt2hpyxtthi.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.sweek.top/Article/details/gt2gzjdeokh.html

TS:   同 JS
来源：http://dali.guowangkeji.top/Article/details/gt2kcjxbnwf.html

Java: 方法内为块级作用域
来源：http://dali.hongshengwenyu.top/Article/details/gt2htuimlwc.html

Go:   花括号块级作用域
来源：http://dali.zdqjudy.top/Article/details/gt2frxcttim.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.9152youxi.cn/Article/details/gt2okmylixe.html

C#:   块级作用域
来源：http://dali.daria6918.cn/Article/details/gt2smpewbwn.html

[C11] 模块导入与导出
来源：http://dali.hysaishi.cn/Article/details/gt2grmiffmx.html

Py:   from module import func
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fbtwhtkm.html

PHP:  require "file.php";  或 use App\Service;
来源：http://dali.jlsjyb.cn/Article/details/gt2lpzyywsc.html

JS:   export default function f() {};  import f from "./m.js";
来源：http://dali.shzxlz.cn/Article/details/gt2vogybsjk.html

TS:   export function f(): void {};  import { f } from "./m";
来源：http://dali.redwolf501.top/Article/details/gt2pwvhgish.html

Java: import java.util.List;
来源：http://dali.guowangkeji.top/Article/details/gt2dguugwyt.html

Go:   import "fmt"          // 之后用 fmt.Println
来源：http://dali.hnqzz.top/Article/details/gt2hskcimhr.html

Ruby: require "json"; require_relative "./util"
来源：http://dali.ivvv.top/Article/details/gt2uhsfeuya.html

C#:   using System.Text;
来源：http://dali.hnxiangtu.top/Article/details/gt2cajiwgpw.html

[C12] 立即执行函数 IIFE
来源：http://dali.jqgufenzy.top/Article/details/gt2ukcsuwjl.html

Py:   (lambda: print("run"))()
来源：http://dali.dashuyun.cn/Article/details/gt2xsvhlwpn.html

PHP:  (function () { echo "run"; })();
来源：http://dali.chenzaomai.com/Article/details/gt2fxhqcquo.html

JS:   (() => { console.log("run"); })();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eutklcxg.html

TS:   (() => { console.log("run"); })();
来源：http://dali.tian-w.cn/Article/details/gt2kpzeojza.html

Java: // 无 IIFE：用 static { } 静态初始化块
来源：http://dali.aibaodan.cn/Article/details/gt2nkliarzj.html

Go:   func() { fmt.Println("run") }()
来源：http://dali.jianghu66.top/Article/details/gt2fsneafzo.html

Ruby: -> { puts "run" }.call
来源：http://dali.redwolf501.top/Article/details/gt2sjrzcsll.html

C#:   // 无 IIFE：用静态构造函数
来源：http://dali.cucudq.cn/Article/details/gt2olwgqfmh.html

[C13] 类型声明 / 类型注解
来源：http://dali.nanxinkj.top/Article/details/gt2aeqtngac.html

Py:   def add(a: int, b: int) -> int: return a + b
来源：http://dali.c1oappe.top/Article/details/gt2kusnxlso.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gt2rcbaapfn.html

JS:   // 无类型（可用 JSDoc 注释）
来源：http://dali.shangyingyoupin.top/Article/details/gt2czfmiikn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.cdnleiting.top/Article/details/gt2szcgfwmu.html

Java: int add(int a, int b) { return a + b; }
来源：http://dali.zhengqikj.top/Article/details/gt2vxzvcyag.html

Go:   func add(a, b int) int
来源：http://dali.cheryme.top/Article/details/gt2qnsclmwf.html

Ruby: # 无类型（可选用 Sorbet / RBS）
来源：http://dali.wangdashe.top/Article/details/gt2bntjsgrp.html

C#:   int Add(int a, int b) => a + b;
来源：http://dali.hnxiangtu.top/Article/details/gt2qvtrpjlc.html

[C14] 泛型函数
来源：http://dali.hammf.cn/Article/details/gt2jybmkejb.html

Py:   from typing import TypeVar; T = TypeVar("T"); def first(items: list[T]) -> T: ...
来源：http://dali.cheryme.top/Article/details/gt2lbfkueio.html

PHP:  // 无泛型
来源：http://dali.fzhhl.top/Article/details/gt2ektksryg.html

JS:   // 无泛型
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2trugwpyo.html

TS:   function first<T>(items: T[]): T | undefined { return items[0]; }
来源：http://dali.bjfxy.top/Article/details/gt2nzxgcmnw.html

Java: static <T> T first(List<T> items) { return items.get(0); }
来源：http://dali.cashguo.top/Article/details/gt2szmxzojn.html

Go:   func First[T any](items []T) T { return items[0] }
来源：http://dali.vqdsnc.cn/Article/details/gt2zgocvkec.html

Ruby: # 无泛型
来源：http://dali.shangyingyoupin.top/Article/details/gt2sdbasivx.html

C#:   static T First<T>(List<T> items) => items[0];
来源：http://dali.cashguo.top/Article/details/gt2tcnrodhf.html

[C15] 解构 / 展开参数
来源：http://dali.xziqi.cn/Article/details/gt2aoemmnxo.html

Py:   def f(a, b): ...;  f(*[1, 2]);  f(**{"a": 1, "b": 2})
来源：http://dali.iojbl.cn/Article/details/gt2pbujejxg.html

PHP:  [$a, $b] = $pair;
来源：http://dali.zdqjudy.top/Article/details/gt2erqywtks.html

JS:   const { a, b } = obj;  function f({ a, b }) {}
来源：http://dali.cdnleiting.top/Article/details/gt2onpdmscu.html

TS:   function f({ a, b }: { a: number; b: number }) {}
来源：http://dali.guowangkeji.top/Article/details/gt2lvcpmyis.html

Java: // 无解构
来源：http://dali.yj20258.top/Article/details/gt2lqsoctlq.html

Go:   // 无解构
来源：http://dali.jlsjyb.cn/Article/details/gt2zeozmjog.html


<!-- 参考信息 -->