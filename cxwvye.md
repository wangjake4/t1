代发 wailian999

Ruby: a, b = b, a
来源：http://dali.zhaomingkeji.xyz/Article/details/gtijnbtfrm.html

C#:   (a, b) = (b, a);
来源：http://dali.jiagoushi.top/Article/details/gtcbmegace.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtlgocfshr.html

Py:   name = input("请输入：")
来源：http://dali.ydzc1.top/Article/details/gthrenfqnu.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.nwbrower.top/Article/details/gtavwgrysg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.kuanghao11.cn/Article/details/gtkuejseyz.html

TS:   // Node.js：readline 模块
来源：http://dali.aibaodan.cn/Article/details/gtgchlzzfw.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.svipenyu.cn/Article/details/gtqgbarznx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtkvjlveit.html

Ruby: gets.chomp
来源：http://dali.tian-w.cn/Article/details/gtvjhodqwh.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gtoublkyfu.html

[A21] 保留指定小数位输出
来源：http://dali.yj20258888.top/Article/details/gtxlsmhpar.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nanxinkj.top/Article/details/gtypzrcdme.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinghuilouyu.cn/Article/details/gtylknqfma.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtovtjqtci.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtvddfuern.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtxcsqhram.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtctlnvtvd.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtgidnwfwy.html

C#:   3.14159.ToString("F2")
来源：http://dali.nanxinkj.top/Article/details/gtvxcqhvwq.html

[A22] 获取字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtiuclekwf.html

Py:   len(s)
来源：http://dali.yj20258.top/Article/details/gtkxswpyzq.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.svipenyu.cn/Article/details/gtqjkpuvgp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmvsjivhl.html

TS:   s.length
来源：http://dali.xziqi.cn/Article/details/gtshgtlbbz.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gtkmblzzma.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.quarkkingdee.top/Article/details/gtpqkimpog.html

Ruby: s.length
来源：http://dali.kuanghao11.cn/Article/details/gtmuvdnlxc.html

C#:   s.Length
来源：http://dali.sweek.top/Article/details/gttwaawvxi.html

[A23] 大小写转换
来源：http://dali.316326.xyz/Article/details/gtndsppzuo.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.pengpengdd.cyou/Article/details/gtiiiztwup.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.daxiang520.top/Article/details/gtkglvysqd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtneqjgpqz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.snrcjt.cn/Article/details/gtcpikgnvu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtdjpfctwt.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.sxryk.cn/Article/details/gtvxnebzit.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimnhscaq.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ivvv.top/Article/details/gtcrmcjuwp.html

[A24] 去除首尾空白
来源：http://dali.9152youxi.cn/Article/details/gtqhbaoiul.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.aibaodan.cn/Article/details/gttfyjlgfh.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gzhubu.top/Article/details/gtgelmqkai.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtprlnyanm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimdwhkdv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zycfv.cn/Article/details/gtvteymniy.html

Go:   strings.TrimSpace(s)
来源：http://dali.ybcxt.top/Article/details/gtoflkgikd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gotoacloud.top/Article/details/gtivotbicr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtspvkewjw.html

[A25] 字符串比较
来源：http://dali.bjfxy.top/Article/details/gtekzwlciv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gtfvcaommw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtynsvduyb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yongpay.top/Article/details/gtqtjzffko.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtodarxcyb.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258.top/Article/details/gtncbgfohp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jiagoushi.top/Article/details/gtvfkihowq.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.9152youxi.cn/Article/details/gtocmbpsrn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtflaaacoq.html

[A26] 类型转换总览
来源：http://dali.cheryme.top/Article/details/gtcfrzmwdj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cdnleiting.top/Article/details/gtsrttsgzd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.guannengcc.top/Article/details/gtklukktcm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daxiang520.top/Article/details/gtuaewjgqa.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yanxiufei.cn/Article/details/gtropfdqgd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtgevrmscc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gttciwlygi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gtakpsvpub.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gtsebxdwoh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtdfdcqdgz.html

B. 流程控制
来源：http://dali.ehwqpu.com/Article/details/gtvyrbhemo.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtirayswzs.html

[B01] 条件判断 if / else
来源：http://dali.xziqi.cn/Article/details/gtgnkmwoxd.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.sufxvd.cn/Article/details/gtzthzthzz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yueranfly.top/Article/details/gtnrnnjigp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtpokmkkhs.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gttlrztlru.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtqwayeumz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigufen.top/Article/details/gtafzirbzv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ybcxt.top/Article/details/gtjmpjvcna.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yanxiufei.cn/Article/details/gtrvrknlxo.html

[B02] 多分支 else if / elif
来源：http://dali.316326.xyz/Article/details/gtnpadcszj.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yonumen.top/Article/details/gtnnbkccpx.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.redwolf501.top/Article/details/gtxgqtmkux.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sysykeji.top/Article/details/gtxactdgrv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cucudq.cn/Article/details/gtecheeesz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuxming.cn/Article/details/gtdnjikksy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhengqikj.top/Article/details/gtcemcgcbg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgufenzy.top/Article/details/gtehxggemd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gtkbeswtud.html

[B03] switch / match / case
来源：http://dali.yj202588.top/Article/details/gtnyzihufw.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gtdfxqadzj.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgsuborlz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtzkefnydn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gthoppljij.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtzbvygxzn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guannengcc.top/Article/details/gtfturenhg.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cheryme.top/Article/details/gtpyyyzaeq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xuanzx.com/Article/details/gtplhrvips.html

[B04] for 计数循环
来源：http://dali.yuanzhike.top/Article/details/gtpaxnzvij.html

Py:   for i in range(10): print(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgmcwujlq.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sxryk.cn/Article/details/gtrlnavwee.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.fengsongda.top/Article/details/gttxauzgxo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.daxiang520.top/Article/details/gttvuxhdrv.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gtifcwntyn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.feifeiyinyue.top/Article/details/gtgkjmxmur.html

Ruby: 10.times { |i| puts i }
来源：http://dali.dashuyun.cn/Article/details/gtabmtghnc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hammf.cn/Article/details/gtchyjnpdc.html

[B05] 遍历数组 / 列表
来源：http://dali.dianchejie.cn/Article/details/gtstdlrxkw.html

Py:   for item in arr: print(item)
来源：http://dali.yvedp.cn/Article/details/gtyynsupol.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnyoupmpm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gtglqtsaht.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtptuzkbvz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gtypwdcvmi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.sufxvd.cn/Article/details/gtwnuuqtaz.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hnqzz.top/Article/details/gtjqcyeljg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtefeaqocv.html

[B06] 遍历字典 / 对象
来源：http://dali.yangfankeji.com/Article/details/gtquaqlxpz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yangfankeji.com/Article/details/gteoaklfkb.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tian-w.cn/Article/details/gtebdceqdd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gaohongyu789.top/Article/details/gtvfbntzsz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtbxdwlger.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenjidiqi.icu/Article/details/gtducuwrty.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cucudq.cn/Article/details/gtlgptilrd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cheryme.top/Article/details/gtdyjwqzkt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.316326.xyz/Article/details/gtscuzbvem.html

[B07] while 循环
来源：http://dali.zycfv.cn/Article/details/gtjexweqji.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtibnjzzfc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.sysykeji.top/Article/details/gttoizgaqh.html

JS:   while (i < 10) { i++; }
来源：http://dali.wangdashe.top/Article/details/gtewfmmvqe.html

TS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtovwxhipa.html

Java: while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gtvywzdtrr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.ybcxt.top/Article/details/gtajwdpian.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhengqikj.top/Article/details/gtvfjcwoec.html

C#:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtekqfdtok.html

[B08] do-while（至少执行一次）
来源：http://dali.xuanzx.com/Article/details/gthzvienmp.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnxiangtu.top/Article/details/gtnatpshan.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtoiytkqza.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aibaodan.cn/Article/details/gtfcawomod.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtzykapghk.html

Java: do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtmnibhyzi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hnxiangtu.top/Article/details/gtovwxufxv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtfsrmhclp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtogssoqdz.html

[B09] break 与 continue
来源：http://dali.tanke756.top/Article/details/gtxfhhmhkm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.hammf.cn/Article/details/gtnadbhfah.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtpamzlhli.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.andypj.xyz/Article/details/gtigmphpje.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.guannengcc.top/Article/details/gtkokeywhb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtqephaztv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gtudizqsee.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.tian-w.cn/Article/details/gtsgxrpyop.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvadrsxqz.html

[B10] 遍历同时拿索引
来源：http://dali.zhoulong.xyz/Article/details/gtjizmxtvh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtibmctrog.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhixingplan.top/Article/details/gtttvcoxla.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.kuanghao11.cn/Article/details/gtbdbvkdhl.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ybcxt.top/Article/details/gtiywwomvj.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.cdnleiting.top/Article/details/gtbjojjzbj.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.pycfn.com/Article/details/gtdkoeteob.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.xziqi.cn/Article/details/gtlbpdgtmk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssxiedyz.html

[B11] 生成数字序列 / 区间
来源：http://dali.tian-w.cn/Article/details/gtgskqkfbu.html

Py:   list(range(0, 10, 2))
来源：http://dali.bjfxy.top/Article/details/gtsvtvzmib.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gtkqpbdcut.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hysaishi.cn/Article/details/gtwenlfics.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtkdacylhl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.shzxlz.cn/Article/details/gtbwifbhwv.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.birdmap.top/Article/details/gtffvdgwph.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhijiandao.cn/Article/details/gtbcwockqj.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.dianchejie.cn/Article/details/gtqkrttfhz.html

[B12] 跳出多层循环
来源：http://dali.yuanzhike.top/Article/details/gtjtsktwsj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ppjwa.cn/Article/details/gthmfitqgb.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnvfjphsh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shzxlz.cn/Article/details/gtvtplcasd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwgaheca.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoxsfnbkf.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yuxming.cn/Article/details/gtybajymmr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfqofwjyt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.hysaishi.cn/Article/details/gttnrelfwb.html

[B13] 判断是否为数字
来源：http://dali.dianchejie.cn/Article/details/gtzpbsstxg.html

Py:   isinstance(x, (int, float))
来源：http://dali.aibaodan.cn/Article/details/gtjlcpxkcl.html

PHP:  is_numeric($x)
来源：http://dali.vqdsnc.cn/Article/details/gttwbpqsgf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yuanzhike.top/Article/details/gtomdihove.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrepfoyls.html

Java: x instanceof Number
来源：http://dali.cqqwz.cn/Article/details/gtlrnxppkx.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gtwumlfzyh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.meibo888.top/Article/details/gtzvqirpod.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gtteuecpaq.html

[B14] 判断值是否在集合内
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflnsrwzv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.sxryk.cn/Article/details/gtfkwwtbbh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtufvgfcpa.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zhongyouzk.top/Article/details/gtkxscwinj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.ivvv.top/Article/details/gtkzpxtdjv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shzxlz.cn/Article/details/gtmknnczth.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.aizwys.cn/Article/details/gtspqooukx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.chenzaomai.com/Article/details/gtudxiczjb.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gtbojblbqc.html

[B15] 布尔运算与取反
来源：http://dali.svipenyu.cn/Article/details/gtyinpfgha.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtpugrtclv.html

PHP:  $a && $b || !$c
来源：http://dali.nanxinkj.top/Article/details/gtstybpacs.html

JS:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfzkgioc.html

TS:   a && b || !c
来源：http://dali.hongshengwenyu.top/Article/details/gtitdoujsu.html

Java: a && b || !c
来源：http://dali.xylfe.cn/Article/details/gtfbpiyxrd.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtrerrdxtg.html

Ruby: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtyuizlqkx.html

C#:   a && b || !c
来源：http://dali.aibaodan.cn/Article/details/gtypwiadsi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.pycfn.com/Article/details/gtxhszyuoe.html

Py:   if not data: return
来源：http://dali.9152youxi.cn/Article/details/gtgqkrryly.html

PHP:  if (!$data) { return; }
来源：http://dali.cdnleiting.top/Article/details/gtuhziocje.html

JS:   if (!data) return;
来源：http://dali.meibo888.top/Article/details/gtrwrzbflp.html

TS:   if (!data) return;
来源：http://dali.yj20258888.top/Article/details/gtrzmpfvpm.html

Java: if (data == null) return;
来源：http://dali.wangdashe.top/Article/details/gtaekuoxuo.html

Go:   if data == nil { return }
来源：http://dali.hywenlv.cn/Article/details/gtaxhlwypk.html

Ruby: return if data.nil?
来源：http://dali.tianlin.xyz/Article/details/gtxrgemibb.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpbojogns.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtvqlgisaf.html

C. 函数与作用域
来源：http://dali.yongpay.top/Article/details/gtipukzgvq.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzpgnvmk.html

[C01] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtncvpyrfb.html

Py:   def add(a, b): return a + b
来源：http://dali.zhiwuduotai.top/Article/details/gtdnmogwqv.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ehwqpu.com/Article/details/gtylhocuaw.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtvtfiaslj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jqgufenzy.top/Article/details/gtilsozwbg.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtiinyijtr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtddmvwume.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gttmphbxrv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtxsahnciu.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gtoguwtkct.html

Py:   def greet(name="World"): return name
来源：http://dali.9152youxi.cn/Article/details/gtniskkbgu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aizwys.cn/Article/details/gtobqsyhfh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gtxftppsyq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdrgtqlk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.pengpengdd.cyou/Article/details/gtpavnhrep.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtfkiwxaru.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtccvgmeqt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuanzhike.top/Article/details/gtgwzeiqex.html

[C03] 可变参数
来源：http://dali.hysaishi.cn/Article/details/gttfcrvfds.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdnfrapat.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gtwvkeqysx.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gtprtwcvpi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gtoehvdixi.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hammf.cn/Article/details/gtqqddumck.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.svipenyu.cn/Article/details/gtjwhvslrk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.vqdsnc.cn/Article/details/gtrlquarxq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenzaomai.com/Article/details/gtdghemcus.html

[C04] 命名参数 / 关键字参数
来源：http://dali.shuidangran.top/Article/details/gtwquumlqy.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.9152youxi.cn/Article/details/gtnwltkmso.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cqqwz.cn/Article/details/gtbpvfwygt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nwbrower.top/Article/details/gtlrvdnskr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.smart0.xyz/Article/details/gtrckbogjq.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hysaishi.cn/Article/details/gtkdxmprge.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtcwsnmman.html

Ruby: f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtkxkusnxw.html

C#:   f(a: 1, b: 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtqhbrxmat.html

[C05] 返回多个值
来源：http://dali.wangdashe.top/Article/details/gtglbqdtyq.html

Py:   return a, b
来源：http://dali.shangyingyoupin.top/Article/details/gtihqylfuz.html

PHP:  return [$a, $b];
来源：http://dali.gotoacloud.top/Article/details/gtldjzgqer.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.hongshengwenyu.top/Article/details/gtdamwhxjl.html

TS:   return { a, b };
来源：http://dali.yvedp.cn/Article/details/gtawsngdrp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yanxiufei.cn/Article/details/gtsuujgmzy.html

Go:   return a, b
来源：http://dali.fzhhl.top/Article/details/gtlwtlcwvd.html

Ruby: return a, b
来源：http://dali.ydzc1.top/Article/details/gtsseveuux.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hysaishi.cn/Article/details/gtbbwqvdaw.html

[C06] 匿名函数 / lambda
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdomuvgce.html

Py:   square = lambda x: x * x
来源：http://dali.guannengcc.top/Article/details/gtaskuzcoc.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.wangshuangyany.cn/Article/details/gtpgxsphyg.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtguohtgkd.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.yonumen.top/Article/details/gtwvjlvvbz.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gtpsqyelrx.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jqgfzy.top/Article/details/gthhujujzg.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gzhubu.top/Article/details/gtxwkvzove.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtozjlvseo.html

[C07] 把函数作为参数传入
来源：http://dali.chenlongwang.top/Article/details/gtfqflnxvt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmeozqqaq.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.wangshuangyany.cn/Article/details/gthtnypjhi.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.316326.xyz/Article/details/gtaxgkirlz.html

TS:   arr.map(String)
来源：http://dali.feifeiyinyue.top/Article/details/gtczriihdl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.iojbl.cn/Article/details/gtxolxafgp.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.redwolf501.top/Article/details/gtfeepjlfa.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangdashe.top/Article/details/gtgghkeizl.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.tian-w.cn/Article/details/gtnxffiayy.html

[C08] 闭包
来源：http://dali.shuidangran.top/Article/details/gtdalsmvti.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.meibo888.top/Article/details/gtewxggzov.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.shuidangran.top/Article/details/gtmpctvxdo.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.vqdsnc.cn/Article/details/gtgronjwhx.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtthouwhja.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.sysykeji.top/Article/details/gtdwrxxdvt.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.dianchejie.cn/Article/details/gtoehpbyvz.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.nanxuanxn.top/Article/details/gthoneixlx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcolizdtc.html

[C09] 递归
来源：http://dali.yongpay.top/Article/details/gtelzuexom.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigfzy.top/Article/details/gtwlfqjgpu.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.zhoulong.xyz/Article/details/gtdidxsilo.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.chenlongwang.top/Article/details/gtysdihvfj.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.hammf.cn/Article/details/gtpoljryeb.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.nwbrower.top/Article/details/gtkfgpovse.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.cqqwz.cn/Article/details/gtaxlyzlzn.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.jyoumei.cn/Article/details/gteartrefc.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zdqjudy.top/Article/details/gtaxfhamlh.html

[C10] 变量作用域
来源：http://dali.svipenyu.cn/Article/details/gtwikxemav.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.havefunace.top/Article/details/gthlxuhnfy.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.dianchejie.cn/Article/details/gtzmlufnki.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtrlsieqib.html


<!-- 参考信息 -->