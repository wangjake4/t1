代发 wailian999

Ruby: a, b = b, a
来源：http://dali.jyoumei.cn/Article/details/gthpsxbzje.html

C#:   (a, b) = (b, a);
来源：http://dali.cheryme.top/Article/details/gtcyfhijlt.html

[A20] 读取标准输入
来源：http://dali.xuetiantiany.cn/Article/details/gtqnvkasil.html

Py:   name = input("请输入：")
来源：http://dali.shangyingyoupin.top/Article/details/gttjrzniuz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jlsjyb.cn/Article/details/gtywaqpzge.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xylfe.cn/Article/details/gtumujhylk.html

TS:   // Node.js：readline 模块
来源：http://dali.gzhubu.top/Article/details/gtrbxusjke.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtutehcgzl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtvbwxuhjh.html

Ruby: gets.chomp
来源：http://dali.hnqzz.top/Article/details/gtnckqmxbe.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtxeqhytzd.html

[A21] 保留指定小数位输出
来源：http://dali.yonumen.top/Article/details/gtaybbclhi.html

Py:   f"{3.14159:.2f}"
来源：http://dali.wangshuangyany.cn/Article/details/gtsnsfzgcv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtfvdwsisa.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtgnshygwz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenjidiqi.icu/Article/details/gtodbbkdfx.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtbqppqwzw.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtqgfemkco.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinqigfzy.top/Article/details/gtlmxpsukx.html

C#:   3.14159.ToString("F2")
来源：http://dali.0kj1m.cn/Article/details/gtcexzoifp.html

[A22] 获取字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtudwrxuzo.html

Py:   len(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtgvzcddkp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfrkbknw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gttenizpsy.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gtptndzhgn.html

Java: s.length()
来源：http://dali.yonumen.top/Article/details/gttqurtvix.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jiagoushi.top/Article/details/gtnvamklwr.html

Ruby: s.length
来源：http://dali.jinqigfzy.top/Article/details/gtylklbhhd.html

C#:   s.Length
来源：http://dali.hnxiangtu.top/Article/details/gtqflaffkr.html

[A23] 大小写转换
来源：http://dali.xuetiantiany.cn/Article/details/gtwtxlbrnv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yonumen.top/Article/details/gtmkrnldtw.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.ivvv.top/Article/details/gthremdpnw.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsmhtzwt.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtauiaomhp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtzkijbegj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cashguo.top/Article/details/gtkblsbobs.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jinghuilouyu.cn/Article/details/gtabadhqkv.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258.top/Article/details/gttulpdouo.html

[A24] 去除首尾空白
来源：http://dali.cheryme.top/Article/details/gtgtjwjlbn.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhengqikj.top/Article/details/gtftdpduhq.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sysykeji.top/Article/details/gttuksbllm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.havefunace.top/Article/details/gtptuwnuhe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ehwqpu.com/Article/details/gtyfnhlnwb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gtuybmntew.html

Go:   strings.TrimSpace(s)
来源：http://dali.yj20258.top/Article/details/gtbohieyqn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.chenjidiqi.icu/Article/details/gtordtkdou.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtfyaffktx.html

[A25] 字符串比较
来源：http://dali.sxryk.cn/Article/details/gthajkflna.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtppqwvtmt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fengsongda.top/Article/details/gtzyyhhibn.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtsqmilkzi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtibnkojcf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jqgfzy.top/Article/details/gtcdxyxbxu.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtjebprzme.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nanxuanxn.top/Article/details/gtfyhscpza.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtunzuztcw.html

[A26] 类型转换总览
来源：http://dali.jlsjyb.cn/Article/details/gtstnaivaf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtxrjfjhdu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.havefunace.top/Article/details/gtaklfdnlc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.jinqigufen.top/Article/details/gtkqpyetxp.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxinkj.top/Article/details/gtdzrjqims.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtlupwqahe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jqgfzy.top/Article/details/gtohsriadh.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtzqhjsjwg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.0kj1m.cn/Article/details/gtgzxfhavo.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtevdjhepm.html

B. 流程控制
来源：http://dali.ybcxt.top/Article/details/gtxfcubblb.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtgfufberz.html

[B01] 条件判断 if / else
来源：http://dali.jianghu66.top/Article/details/gtiwholkey.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gtiyxymhbs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtkpfdrltv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtkmxyiqvx.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shangyingyoupin.top/Article/details/gtwvfxtwgi.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yj20258.top/Article/details/gtxycjnaaf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sxryk.cn/Article/details/gtmvaudhnp.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj20258888.top/Article/details/gtfpmmgggn.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtfootacmo.html

[B02] 多分支 else if / elif
来源：http://dali.jlsjyb.cn/Article/details/gtwenxnirv.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.sweek.top/Article/details/gthzjzlcol.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtsswuwcfk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ppjwa.cn/Article/details/gtojpybypk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtwfqtcstg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.vqdsnc.cn/Article/details/gtncdbigrp.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gzhubu.top/Article/details/gtrmvnhlyq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.nanxuanxn.top/Article/details/gtsnbwmbmc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.mhx1999.top/Article/details/gtiisvzudz.html

[B03] switch / match / case
来源：http://dali.jinyuanbaomall.cn/Article/details/gtarewzoxu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jyoumei.cn/Article/details/gtenifnkjp.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtttoziadk.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtfbbhbjan.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gtaepjpsdk.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gthztthiby.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gttfekcffu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.smart0.xyz/Article/details/gttzmkjqlf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtqftgmaqo.html

[B04] for 计数循环
来源：http://dali.yj202588.top/Article/details/gteazziygx.html

Py:   for i in range(10): print(i)
来源：http://dali.nwbrower.top/Article/details/gtsosatuyw.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yongpay.top/Article/details/gtnzbqcfsz.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtsddgdbnb.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hysaishi.cn/Article/details/gtderpbsfw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sxryk.cn/Article/details/gtektykqfl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.smart0.xyz/Article/details/gtidqfpcfr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shzxlz.cn/Article/details/gtuvipqbgg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.zhengqikj.top/Article/details/gtwxqtwmhv.html

[B05] 遍历数组 / 列表
来源：http://dali.ppjwa.cn/Article/details/gtkmtcstpq.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtimntmcnt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zycfv.cn/Article/details/gtxgawfeag.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtllcyeaia.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.hammf.cn/Article/details/gtjmbhnrhw.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daria6918.cn/Article/details/gtjuzadeyk.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yueranfly.top/Article/details/gtrqsjksao.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtfulamkjn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtqdcjlqzn.html

[B06] 遍历字典 / 对象
来源：http://dali.yuanzhike.top/Article/details/gtaehdmqwf.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgjsweyb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gotoacloud.top/Article/details/gtjxdewbxo.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtxazuroou.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtepmyttxx.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.snrcjt.cn/Article/details/gtqifmkvew.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yangfankeji.com/Article/details/gtvpfmyviz.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtqfgrdeej.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.svipenyu.cn/Article/details/gtjudesglq.html

[B07] while 循环
来源：http://dali.shuidangran.top/Article/details/gtekmljzdc.html

Py:   while i < 10: i += 1
来源：http://dali.mhx1999.top/Article/details/gteajrjfyx.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.hysaishi.cn/Article/details/gttmqxfjex.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gtqxvgyrfj.html

TS:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtlkvnjluj.html

Java: while (i < 10) { i++; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtukzxowhr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.meibo888.top/Article/details/gtwfaziqiy.html

Ruby: while i < 10; i += 1; end
来源：http://dali.0kj1m.cn/Article/details/gtnkixxquh.html

C#:   while (i < 10) { i++; }
来源：http://dali.hnqzz.top/Article/details/gtfbdrubtl.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gtxuhkihup.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ybcxt.top/Article/details/gtfnftmhdq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.aizwys.cn/Article/details/gttdwarkjd.html

JS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtxkxoibof.html

TS:   do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtfkbrtwzo.html

Java: do { i++; } while (i < 10);
来源：http://dali.guannengcc.top/Article/details/gtrqbofhsi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.guowangkeji.top/Article/details/gttswjnvln.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gtrhhyvjlt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtqybnsfqj.html

[B09] break 与 continue
来源：http://dali.gzhubu.top/Article/details/gtuprqbffe.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.nwbrower.top/Article/details/gtopaxwovq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gtvrfttnuk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gthufttzik.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtdedhjcmx.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtczudzmaa.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cheryme.top/Article/details/gthkqsxllv.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gtxgkwmazp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtmuqpnzbh.html

[B10] 遍历同时拿索引
来源：http://dali.yanxiufei.cn/Article/details/gtgvjqoaty.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hnxiangtu.top/Article/details/gtcluxgqye.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzvhxssz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yuanzhike.top/Article/details/gtiwfaknac.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gtyqrehycz.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtgwmxwmnc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhiwuduotai.top/Article/details/gtylaqidpl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.wangshuangyany.cn/Article/details/gtewmchxyh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gtugehvwid.html

[B11] 生成数字序列 / 区间
来源：http://dali.yueranfly.top/Article/details/gtzwiddxty.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtkjvrwzyb.html

PHP:  range(0, 10, 2);
来源：http://dali.yvedp.cn/Article/details/gtsstepiym.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtmmeoqhfn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.andypj.xyz/Article/details/gtnegimxyg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhiwuduotai.top/Article/details/gtszektkal.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtrnzxnfoq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gttfgkqidr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhijiandao.cn/Article/details/gtxgdwpqwe.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gtybduqyug.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtthlfwzbi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.316326.xyz/Article/details/gtpupmhttm.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.fzhhl.top/Article/details/gtjeajqbcr.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jlsjyb.cn/Article/details/gtbhsgypgl.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtkfsloopv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jyoumei.cn/Article/details/gtwfcixajp.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.cdnleiting.top/Article/details/gtsxajoorx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cashguo.top/Article/details/gtthksbtty.html

[B13] 判断是否为数字
来源：http://dali.ehwqpu.com/Article/details/gtqbuhnkzr.html

Py:   isinstance(x, (int, float))
来源：http://dali.hywenlv.cn/Article/details/gtgvrhlzrn.html

PHP:  is_numeric($x)
来源：http://dali.cashguo.top/Article/details/gtfcjxbtbb.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtbofffrjr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ydzc1.top/Article/details/gtwrucmngi.html

Java: x instanceof Number
来源：http://dali.daria6918.cn/Article/details/gtvvcyurjo.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqwzssqg.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gtotdrdzlo.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gtkdiexkjc.html

[B14] 判断值是否在集合内
来源：http://dali.nwbrower.top/Article/details/gtmchurxjv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.dashuyun.cn/Article/details/gtcpgvjprl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xinyue.icu/Article/details/gthrfvpatg.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daria6918.cn/Article/details/gtgmwsunfg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtgpzjsgxj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jlsjyb.cn/Article/details/gtvutnglux.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhengqikj.top/Article/details/gtouveycrl.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenjidiqi.icu/Article/details/gtfuckqiuc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yangfankeji.com/Article/details/gtkaemoyho.html

[B15] 布尔运算与取反
来源：http://dali.jiagoushi.top/Article/details/gtefzsbajg.html

Py:   a and b or not c
来源：http://dali.dashuyun.cn/Article/details/gttjkablnv.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtelsjrtaw.html

JS:   a && b || !c
来源：http://dali.cqqwz.cn/Article/details/gtzilzbuxg.html

TS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdwpdljw.html

Java: a && b || !c
来源：http://dali.mhx1999.top/Article/details/gtmfzwrtmh.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtutuzzfkr.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtfdqdzmyk.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtlfdgxrrn.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yonumen.top/Article/details/gtvddnhxpw.html

Py:   if not data: return
来源：http://dali.ehwqpu.com/Article/details/gtnzdsmbwv.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtdrsewqgt.html

JS:   if (!data) return;
来源：http://dali.wangdashe.top/Article/details/gtmxbbxlpc.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gtvpwxeyjp.html

Java: if (data == null) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtkjsejdhe.html

Go:   if data == nil { return }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawmngsss.html

Ruby: return if data.nil?
来源：http://dali.jqgufenzy.top/Article/details/gtrbfqerbn.html

C#:   if (data == null) return;
来源：http://dali.ehwqpu.com/Article/details/gtytlcnflw.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtljhmsypg.html

C. 函数与作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlwzegkl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbkayanpg.html

[C01] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtsqrkpfui.html

Py:   def add(a, b): return a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtpggboqei.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtketqhrxh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gtwtehzzgh.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtnzknyonl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtukywceej.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.cucudq.cn/Article/details/gtbnbrudmg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.fzhhl.top/Article/details/gtwvpagtpx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtykksgizg.html

[C02] 默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiunbbxze.html

Py:   def greet(name="World"): return name
来源：http://dali.xziqi.cn/Article/details/gtpxxoezfz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtxhllpghx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.iojbl.cn/Article/details/gtoqgjzunz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.cqqwz.cn/Article/details/gtpnrlwopo.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkxvsaox.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gteojmzmka.html

Ruby: def greet(name = "World") = name
来源：http://dali.redwolf501.top/Article/details/gthqzhldhv.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guowangkeji.top/Article/details/gtoeraqxwy.html

[C03] 可变参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtnayqbztg.html

Py:   def total(*args): return sum(args)
来源：http://dali.yongpay.top/Article/details/gtoedwgfdg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtlhapedyc.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtwjrmwtlg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtrgqtoopu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.9152youxi.cn/Article/details/gtssnxhxfe.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cheryme.top/Article/details/gtgdzbedam.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.aizwys.cn/Article/details/gtohgvhunv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.meibo888.top/Article/details/gtiiuzquhk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258.top/Article/details/gtzjcuzehn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.hywenlv.cn/Article/details/gtnqaczgkj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxuanxn.top/Article/details/gtnxeofuuz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gaohongyu789.top/Article/details/gtfodczpnu.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangdashe.top/Article/details/gtsunxjrjt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gtfbkzzqcb.html

Go:   // 无：用配置结构体参数
来源：http://dali.cucudq.cn/Article/details/gtkcnstvyf.html

Ruby: f(a: 1, b: 2)
来源：http://dali.dashuyun.cn/Article/details/gtolmafvcf.html

C#:   f(a: 1, b: 2)
来源：http://dali.hnxiangtu.top/Article/details/gtyeowqxsy.html

[C05] 返回多个值
来源：http://dali.xuanzx.com/Article/details/gtkttluycf.html

Py:   return a, b
来源：http://dali.kuanghao11.cn/Article/details/gtcfwadylu.html

PHP:  return [$a, $b];
来源：http://dali.jinghuilouyu.cn/Article/details/gtkcujtmeh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ybcxt.top/Article/details/gtbmolmqmi.html

TS:   return { a, b };
来源：http://dali.zdqjudy.top/Article/details/gtiwfcbaew.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.feifeiyinyue.top/Article/details/gtzvgaorbz.html

Go:   return a, b
来源：http://dali.jinghuilouyu.cn/Article/details/gtvzbpzgjp.html

Ruby: return a, b
来源：http://dali.shuidangran.top/Article/details/gtnlwwddqn.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.daria6918.cn/Article/details/gtexzwpzlp.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtfdspusmr.html

Py:   square = lambda x: x * x
来源：http://dali.nanxinkj.top/Article/details/gtnsgxpksm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.meibo888.top/Article/details/gtbekaxvqd.html

JS:   const square = x => x * x;
来源：http://dali.iojbl.cn/Article/details/gtjpmzqsdz.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.dianchejie.cn/Article/details/gtmpjcaelh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtlndimjlh.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.guannengcc.top/Article/details/gtyhvgzjqs.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ydzc1.top/Article/details/gtjrqatgpj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daxiang520.top/Article/details/gtieyzcqlb.html

[C07] 把函数作为参数传入
来源：http://dali.yvedp.cn/Article/details/gtsfxurdln.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhongyouzk.top/Article/details/gtfzzgltaz.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.andypj.xyz/Article/details/gtppplczds.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtzrqspkwr.html

TS:   arr.map(String)
来源：http://dali.zdqjudy.top/Article/details/gtqusowymp.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.nwbrower.top/Article/details/gtksrsynok.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.9152youxi.cn/Article/details/gtzcmmtiqh.html

Ruby: arr.map(&:upcase)
来源：http://dali.zycfv.cn/Article/details/gtatlozpfn.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhixingplan.top/Article/details/gtdofdnkds.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gtlhwtfkbe.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.smart0.xyz/Article/details/gtjtllhlwx.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.jinqigufen.top/Article/details/gtftajxqim.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jlsjyb.cn/Article/details/gtmmvfuniz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tian-w.cn/Article/details/gtijflimmp.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhongyouzk.top/Article/details/gtbnytbggc.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.pycfn.com/Article/details/gthnbaermx.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.shuidangran.top/Article/details/gtxdmyhgdu.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.jqgfzy.top/Article/details/gtbxzhtdrg.html

[C09] 递归
来源：http://dali.haohaochexian.top/Article/details/gtqszlxxlw.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.ppjwa.cn/Article/details/gtyaeqhssm.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhijiandao.cn/Article/details/gttumknjgc.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.gaohongyu789.top/Article/details/gtxuikxlob.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.yangfankeji.com/Article/details/gtrjtpptfm.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.aibaodan.cn/Article/details/gthbjlkvqv.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.ydzc1.top/Article/details/gtkzgkozhl.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.0kj1m.cn/Article/details/gtdbsdqocm.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtiovhgoao.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gtoengrykf.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.yongpay.top/Article/details/gtcxmgqybs.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.ehwqpu.com/Article/details/gtwycweqhw.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwqjdtta.html


<!-- 参考信息 -->