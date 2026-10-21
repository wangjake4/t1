代发 wailian999

Ruby: a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtfemijwsv.html

C#:   (a, b) = (b, a);
来源：http://dali.daxiang520.top/Article/details/gtmafzqikn.html

[A20] 读取标准输入
来源：http://dali.quarkkingdee.top/Article/details/gtzsvdgrlc.html

Py:   name = input("请输入：")
来源：http://dali.shangyingyoupin.top/Article/details/gtbuayuwmm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.xylfe.cn/Article/details/gtcgqvyhpk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.sweek.top/Article/details/gtgvhexjuz.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gtossduqdf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.tian-w.cn/Article/details/gtyktiuyzk.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xinyue.icu/Article/details/gtsywkumkr.html

Ruby: gets.chomp
来源：http://dali.nanxuanxn.top/Article/details/gtwvmqnvhr.html

C#:   Console.ReadLine();
来源：http://dali.yvedp.cn/Article/details/gtyarsbxqo.html

[A21] 保留指定小数位输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcrexpzgb.html

Py:   f"{3.14159:.2f}"
来源：http://dali.nwbrower.top/Article/details/gtaszitzkp.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtejqwjqmc.html

JS:   (3.14159).toFixed(2)
来源：http://dali.gzhubu.top/Article/details/gtugyloyab.html

TS:   (3.14159).toFixed(2)
来源：http://dali.316326.xyz/Article/details/gtlkrgxurp.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtpcxihyqz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtutzcfmch.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtzcjcrjdy.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gtshlwxgbe.html

[A22] 获取字符串长度
来源：http://dali.gzhubu.top/Article/details/gttjbqttjo.html

Py:   len(s)
来源：http://dali.vqdsnc.cn/Article/details/gtnsycvmeu.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yanxiufei.cn/Article/details/gtyvwuguvf.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nwbrower.top/Article/details/gteyazuocp.html

TS:   s.length
来源：http://dali.ydzc1.top/Article/details/gtzcyuhgzi.html

Java: s.length()
来源：http://dali.jqgfzy.top/Article/details/gtrjbkuedx.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gotoacloud.top/Article/details/gtobivsceb.html

Ruby: s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvwlfvtfa.html

C#:   s.Length
来源：http://dali.yuxming.cn/Article/details/gtbkqoxfrn.html

[A23] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtmvinpepl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.sysykeji.top/Article/details/gtdzyhsjbt.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtzyduwjbz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.redwolf501.top/Article/details/gtijequnoh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cashguo.top/Article/details/gtvyfetrlu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtuhnmffpo.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gtfhelbxkt.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.havefunace.top/Article/details/gtxxhpqrjj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jlsjyb.cn/Article/details/gtypicjogk.html

[A24] 去除首尾空白
来源：http://dali.yonumen.top/Article/details/gtlioevanj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shuidangran.top/Article/details/gtisjbfzre.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gaohongyu789.top/Article/details/gtjkfaqajd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtcuhydnyz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtkajxlzvr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xuetiantiany.cn/Article/details/gtpglwdhgx.html

Go:   strings.TrimSpace(s)
来源：http://dali.jyoumei.cn/Article/details/gtqtsokhfd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.dashuyun.cn/Article/details/gtcwoavgar.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtvawmovft.html

[A25] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtsprcbnyb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.0kj1m.cn/Article/details/gtxapmlzds.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctccnqmt.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtpgmhtvpy.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnyjbirnf.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jlsjyb.cn/Article/details/gtezfgffta.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtpvayrecl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gtearidtcm.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtrvxculmj.html

[A26] 类型转换总览
来源：http://dali.fzhhl.top/Article/details/gtfhhgnepm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daria6918.cn/Article/details/gtzuecnzmd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.birdmap.top/Article/details/gtlvjarouq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenlongwang.top/Article/details/gtmgskrtcf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.birdmap.top/Article/details/gtasyupnlu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtkiodjxrf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.ybcxt.top/Article/details/gtqualnqyb.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gaohongyu789.top/Article/details/gthzufkxym.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtshvmwblf.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gthckawcvc.html

B. 流程控制
来源：http://dali.gotoacloud.top/Article/details/gthwglhfuk.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtfumhmfwx.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gtwlvbmruc.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jlsjyb.cn/Article/details/gthwiyuoxl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yvedp.cn/Article/details/gtuwzobdnm.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtkcqeyisz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtizlioght.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jlsjyb.cn/Article/details/gtvgtkkwfg.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenzaomai.com/Article/details/gtkslvzrow.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shangyingyoupin.top/Article/details/gtqfvkaxqq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtbalptpwn.html

[B02] 多分支 else if / elif
来源：http://dali.hnqzz.top/Article/details/gtyfiztqsq.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.vqdsnc.cn/Article/details/gtrxueiena.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.kuanghao11.cn/Article/details/gtgztyvdnu.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtruhsxuqx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yonumen.top/Article/details/gteuwvnhrf.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtuopweoag.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.havefunace.top/Article/details/gtxwikurpk.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gtsgrxzrxb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zycfv.cn/Article/details/gtnwzeqkqr.html

[B03] switch / match / case
来源：http://dali.zhixingplan.top/Article/details/gtrqhpfmys.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.kuanghao11.cn/Article/details/gtybyviueg.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtxwmxnevn.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtmseblfcc.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtehfodzeo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtomaievqu.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hysaishi.cn/Article/details/gtrsftmndj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sufxvd.cn/Article/details/gtrcbdgbml.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtmfojhqjl.html

[B04] for 计数循环
来源：http://dali.chenzaomai.com/Article/details/gtpvwolwpx.html

Py:   for i in range(10): print(i)
来源：http://dali.hnxiangtu.top/Article/details/gtobwtjuky.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nwbrower.top/Article/details/gtrkvzfbbl.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gtmgrfoqzm.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigufen.top/Article/details/gtgnyouyzi.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ybcxt.top/Article/details/gtrvgpfeew.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.0kj1m.cn/Article/details/gtqegisjdl.html

Ruby: 10.times { |i| puts i }
来源：http://dali.quarkkingdee.top/Article/details/gtlziymced.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hfpthk.cn/Article/details/gtsykakgxh.html

[B05] 遍历数组 / 列表
来源：http://dali.yueranfly.top/Article/details/gtwwkqztmq.html

Py:   for item in arr: print(item)
来源：http://dali.yangfankeji.com/Article/details/gtszlshbms.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkuyiznyh.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xuanzx.com/Article/details/gtyulonrky.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yanxiufei.cn/Article/details/gtuiysuhwx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aizwys.cn/Article/details/gtwbfbwlcu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.feifeiyinyue.top/Article/details/gtzdwfxhnl.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtohststef.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhiwuduotai.top/Article/details/gtyulvefno.html

[B06] 遍历字典 / 对象
来源：http://dali.dashuyun.cn/Article/details/gtnzemkzti.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gtysaxjwby.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.wangdashe.top/Article/details/gtygxgmity.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtaegrofyp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shzxlz.cn/Article/details/gttpfdxwto.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cashguo.top/Article/details/gtwwcenaza.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.nanxinkj.top/Article/details/gtzqyvyocm.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gtkksvvbqb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.zhixingplan.top/Article/details/gtdhqbqqzf.html

[B07] while 循环
来源：http://dali.ivvv.top/Article/details/gtzfycxihi.html

Py:   while i < 10: i += 1
来源：http://dali.redwolf501.top/Article/details/gtzhsezvya.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cheryme.top/Article/details/gthxjfaptd.html

JS:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtxzqvaawv.html

TS:   while (i < 10) { i++; }
来源：http://dali.yongpay.top/Article/details/gtxkkwotct.html

Java: while (i < 10) { i++; }
来源：http://dali.chenzaomai.com/Article/details/gtlkoxuqwa.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.316326.xyz/Article/details/gtquozijsq.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtzhtftdus.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtgfdiabja.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gtgdnldssa.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.zhengqikj.top/Article/details/gtuhbjgfls.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtednzqdfi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtomjnjnyp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtbljscoqs.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtxcijndgf.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hongshengwenyu.top/Article/details/gtqheolhap.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gthwmjjrts.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtmbeilruh.html

[B09] break 与 continue
来源：http://dali.bjfxy.top/Article/details/gtbxfnjyrv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtehfdvpzj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtdndopsjc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtfqipgckc.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtlwijtsnw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtfvpfrngm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtbhzmruvk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yvedp.cn/Article/details/gtmkfiqjgw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtbpqavzxf.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gthlgoprnp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.gzhubu.top/Article/details/gtcwcwfnzv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sufxvd.cn/Article/details/gtwpbuqcqz.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtuzlecfhg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.c1oappe.top/Article/details/gtqocsoxqp.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yuanzhike.top/Article/details/gtytnuyhml.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyyqtvcx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yj202588.top/Article/details/gtrtlsbvlj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hnqzz.top/Article/details/gtrftgzfsh.html

[B11] 生成数字序列 / 区间
来源：http://dali.c1oappe.top/Article/details/gtoxmfqfbh.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtsmsmsdbq.html

PHP:  range(0, 10, 2);
来源：http://dali.ppjwa.cn/Article/details/gtiudjmdqr.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrxiyeemv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.daxiang520.top/Article/details/gtwwltldwc.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yonumen.top/Article/details/gtfenhuxsp.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.cdnleiting.top/Article/details/gtsrlgiefy.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hammf.cn/Article/details/gtlicftkyw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.andypj.xyz/Article/details/gtbbdjpfqu.html

[B12] 跳出多层循环
来源：http://dali.yj202588.top/Article/details/gtmhgfadtc.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.meibo888.top/Article/details/gtahwshyet.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.birdmap.top/Article/details/gtixtwvzsc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtqsyjbocz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj202588.top/Article/details/gtofsemkoz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtegxeusab.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gogol.net.cn/Article/details/gtcthxggos.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.svipenyu.cn/Article/details/gtcnwmlrvq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.aizwys.cn/Article/details/gtzkfectgc.html

[B13] 判断是否为数字
来源：http://dali.9152youxi.cn/Article/details/gtaxqarded.html

Py:   isinstance(x, (int, float))
来源：http://dali.quarkkingdee.top/Article/details/gtrohgpmur.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtxnmzqkhw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtumisgxst.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtpexxwqay.html

Java: x instanceof Number
来源：http://dali.chenjidiqi.icu/Article/details/gtgxnicpno.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtneoldggu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhengqikj.top/Article/details/gtlwvvxnvu.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxkritvi.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtblhmakoh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258888.top/Article/details/gtnpashzsp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hywenlv.cn/Article/details/gtwmvikvku.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtqsphmcdi.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtqcqkjuxj.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtxxgnfafb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gtzjfjdjdd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.daria6918.cn/Article/details/gtwqhnfzmc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hnxiangtu.top/Article/details/gteowrrrzr.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gtsyzhxajd.html

Py:   a and b or not c
来源：http://dali.nanxuanxn.top/Article/details/gtugjoyvzf.html

PHP:  $a && $b || !$c
来源：http://dali.ppjwa.cn/Article/details/gtdjpoizjq.html

JS:   a && b || !c
来源：http://dali.cucudq.cn/Article/details/gtavnklbjk.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtlsdhtjos.html

Java: a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtctsamwfq.html

Go:   a && b || !c
来源：http://dali.pycfn.com/Article/details/gtqpyxdvpl.html

Ruby: a && b || !c
来源：http://dali.316326.xyz/Article/details/gtfsfksfwz.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyfknfwd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ybcxt.top/Article/details/gtsvbmaqba.html

Py:   if not data: return
来源：http://dali.fzhhl.top/Article/details/gtzeyaenro.html

PHP:  if (!$data) { return; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmhzhwvec.html

JS:   if (!data) return;
来源：http://dali.316326.xyz/Article/details/gtqiwbcsgk.html

TS:   if (!data) return;
来源：http://dali.chenjidiqi.icu/Article/details/gttmpflwdb.html

Java: if (data == null) return;
来源：http://dali.yj20258.top/Article/details/gtwuerxwuv.html

Go:   if data == nil { return }
来源：http://dali.c1oappe.top/Article/details/gthizklrwd.html

Ruby: return if data.nil?
来源：http://dali.hfpthk.cn/Article/details/gtaggdcvzc.html

C#:   if (data == null) return;
来源：http://dali.zhongyouzk.top/Article/details/gtllguufoz.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtodcbdvwo.html

C. 函数与作用域
来源：http://dali.shangyingyoupin.top/Article/details/gtmmoompxr.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtkyiddvbv.html

[C01] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gtqyfgnrut.html

Py:   def add(a, b): return a + b
来源：http://dali.yj20258.top/Article/details/gtohcsenwt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhvhnroh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtkioobvyj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.ivvv.top/Article/details/gtomoqsfgl.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtrtjjyoqu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hongshengwenyu.top/Article/details/gtovvlvims.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtvkmijiky.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtrfxhrymc.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgktnjrzu.html

Py:   def greet(name="World"): return name
来源：http://dali.jianghu66.top/Article/details/gtbnzaoerq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sxryk.cn/Article/details/gtvnbshowc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtorfprqyh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xziqi.cn/Article/details/gtkxoxelhx.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gtttsubrkk.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.quarkkingdee.top/Article/details/gtzwecgrcu.html

Ruby: def greet(name = "World") = name
来源：http://dali.sysykeji.top/Article/details/gtrrstupwm.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.birdmap.top/Article/details/gtzeowvcxa.html

[C03] 可变参数
来源：http://dali.zhixingplan.top/Article/details/gtbjqhpmki.html

Py:   def total(*args): return sum(args)
来源：http://dali.hammf.cn/Article/details/gtlyezrusy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yanxiufei.cn/Article/details/gtbzdtyndb.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtkyeokpso.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtprswiebj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.andypj.xyz/Article/details/gteyefhzun.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtztbwbryj.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtbppcuhcw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jyoumei.cn/Article/details/gtowltwija.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xuetiantiany.cn/Article/details/gttvzzggqm.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tanke756.top/Article/details/gtkeywsrhz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuanzhike.top/Article/details/gtrctgmibw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtkvmeohfm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.9152youxi.cn/Article/details/gtxfqvfnlc.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinqigufen.top/Article/details/gtdpvfbdef.html

Go:   // 无：用配置结构体参数
来源：http://dali.vqdsnc.cn/Article/details/gttawjbbob.html

Ruby: f(a: 1, b: 2)
来源：http://dali.aibaodan.cn/Article/details/gtkdouvkuv.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtkjvkfj.html

[C05] 返回多个值
来源：http://dali.jlsjyb.cn/Article/details/gtaynyeopo.html

Py:   return a, b
来源：http://dali.guannengcc.top/Article/details/gtqllnempj.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtbttfkimc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtmwbsftxk.html

TS:   return { a, b };
来源：http://dali.gogol.net.cn/Article/details/gtoumvlklh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pycfn.com/Article/details/gtnedwmssb.html

Go:   return a, b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyuovnvc.html

Ruby: return a, b
来源：http://dali.hnxiangtu.top/Article/details/gtlbwgqydg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ehwqpu.com/Article/details/gtwgcekgyy.html

[C06] 匿名函数 / lambda
来源：http://dali.zhijiandao.cn/Article/details/gtitrcteuw.html

Py:   square = lambda x: x * x
来源：http://dali.guowangkeji.top/Article/details/gtxeamgdsx.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cucudq.cn/Article/details/gtngdgwfsn.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtixfdzrrc.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhoulong.xyz/Article/details/gtvkgjaszm.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sweek.top/Article/details/gtygodijhl.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigfzy.top/Article/details/gtbfmzvbxv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtdkyfhdvj.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtjsmittms.html

[C07] 把函数作为参数传入
来源：http://dali.jqgfzy.top/Article/details/gtwmmvooid.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.jinqigufen.top/Article/details/gtkxxztmyg.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jinqigufen.top/Article/details/gtlkvrslue.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.yj202588.top/Article/details/gtvgeqfhac.html

TS:   arr.map(String)
来源：http://dali.zhixingplan.top/Article/details/gtgjwyjvuq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.gaohongyu789.top/Article/details/gtfwmcyvhu.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.gaohongyu789.top/Article/details/gtkshjjkpb.html

Ruby: arr.map(&:upcase)
来源：http://dali.ydzc1.top/Article/details/gtgjpvzgga.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.cqqwz.cn/Article/details/gtzkfwlgcs.html

[C08] 闭包
来源：http://dali.mhx1999.top/Article/details/gtgzdlaxer.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.chenlongwang.top/Article/details/gtbioulkml.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrljclupn.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xziqi.cn/Article/details/gtthvzidyg.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.ppjwa.cn/Article/details/gtfayjlaxd.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.bjfxy.top/Article/details/gtyytjddbj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.guowangkeji.top/Article/details/gtrylyjjui.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.cucudq.cn/Article/details/gthmxybbxx.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.cdnleiting.top/Article/details/gtftyislmb.html

[C09] 递归
来源：http://dali.cheryme.top/Article/details/gtdjkufgyl.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.jinqigufen.top/Article/details/gtazajoisf.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.316326.xyz/Article/details/gtdvezgadh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkhfbekxl.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.xziqi.cn/Article/details/gtpwqoaekc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.chenzaomai.com/Article/details/gtqczwvvuq.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.9152youxi.cn/Article/details/gtofuiqcqz.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.zdqjudy.top/Article/details/gtqjeevnul.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.guannengcc.top/Article/details/gtqazbusmc.html

[C10] 变量作用域
来源：http://dali.c1oappe.top/Article/details/gttgzkydps.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.jinghuilouyu.cn/Article/details/gtfmscauev.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.xziqi.cn/Article/details/gtowvbhgfv.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.zhoulong.xyz/Article/details/gtooisxjrg.html


<!-- 参考信息 -->