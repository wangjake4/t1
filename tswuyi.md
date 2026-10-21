代发 wailian999

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtapfucjdi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxuanxn.top/Article/details/gtypljwald.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtpgufni.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jinqigufen.top/Article/details/gtshgstpbl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.aibaodan.cn/Article/details/gtzqmovduj.html

Ruby: gets.chomp
来源：http://dali.guannengcc.top/Article/details/gtibrfjfft.html

C#:   Console.ReadLine();
来源：http://dali.aizwys.cn/Article/details/gtkkbvcvcb.html

[A21] 保留指定小数位输出
来源：http://dali.zycfv.cn/Article/details/gtfjichzyn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gtzadhxhzb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtqeccnadk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yonumen.top/Article/details/gtqhawegrq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yuxming.cn/Article/details/gtivyvnxju.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtqtuiztbh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.gzhubu.top/Article/details/gtjhvhygis.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.redwolf501.top/Article/details/gtlnkhqgxm.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gtlbvbztfy.html

[A22] 获取字符串长度
来源：http://dali.shangyingyoupin.top/Article/details/gtrxamiklo.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gtoxubzbbh.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shanyushiyangtech.top/Article/details/gtezkcztwh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.feifeiyinyue.top/Article/details/gtfmuovshy.html

TS:   s.length
来源：http://dali.316326.xyz/Article/details/gtwsgneivz.html

Java: s.length()
来源：http://dali.daxiang520.top/Article/details/gtfxxjppdv.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ivvv.top/Article/details/gtfhmznrmj.html

Ruby: s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtctvbluyh.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gtqhlvzxlw.html

[A23] 大小写转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgcygswtn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ppjwa.cn/Article/details/gtvlrofvbu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xziqi.cn/Article/details/gtwxjgkpyd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gtrzkrbtyl.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinghuilouyu.cn/Article/details/gtirziqkkv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jqgfzy.top/Article/details/gtymimwchc.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ybcxt.top/Article/details/gtupetsmhp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gtiockhqep.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj202588.top/Article/details/gthgikqqwp.html

[A24] 去除首尾空白
来源：http://dali.svipenyu.cn/Article/details/gtmcntzevc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.havefunace.top/Article/details/gtmvpqilgb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.havefunace.top/Article/details/gtkwaaojhn.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dianchejie.cn/Article/details/gthhpduemp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtoikewimo.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.vqdsnc.cn/Article/details/gtvrufgtku.html

Go:   strings.TrimSpace(s)
来源：http://dali.quarkkingdee.top/Article/details/gtppdkvrpt.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.fengsongda.top/Article/details/gteyegnhnp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hywenlv.cn/Article/details/gttqfoimqe.html

[A25] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtpijoignr.html

Py:   s1 == s2; s1 != s2
来源：http://dali.316326.xyz/Article/details/gttozvvjxd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yj20258888.top/Article/details/gtibsdugsl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gtpsjklfvw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtdnguzkda.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guowangkeji.top/Article/details/gtizawnnia.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gthmikaopk.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tianlin.xyz/Article/details/gtmyngigdp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtrxxahoda.html

[A26] 类型转换总览
来源：http://dali.zdqjudy.top/Article/details/gtzuujsoyt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hnxiangtu.top/Article/details/gtiidmfphl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.andypj.xyz/Article/details/gtwgvrpiwg.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gtttlvghnt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.smart0.xyz/Article/details/gthyornabg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.feifeiyinyue.top/Article/details/gtwfbwvmpf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hnqzz.top/Article/details/gtxtoymcku.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gtjbvctgfp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xziqi.cn/Article/details/gtrqxphbnu.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtidfhndiu.html

B. 流程控制
来源：http://dali.c1oappe.top/Article/details/gtlsfbemex.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtlruekdrw.html

[B01] 条件判断 if / else
来源：http://dali.hywenlv.cn/Article/details/gtwkhschti.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.gzhubu.top/Article/details/gtbbtdhwwl.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aizwys.cn/Article/details/gtwjunwqnq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtxivofezl.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtcnhlsdjy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gtwxldgwxu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gtyxumpnvo.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daxiang520.top/Article/details/gtlfxcckyz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtzjokmniv.html

[B02] 多分支 else if / elif
来源：http://dali.xuanzx.com/Article/details/gtyxfjsmti.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.svipenyu.cn/Article/details/gtvsvrapdq.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.fzhhl.top/Article/details/gtsoejdwyh.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtcqtggvil.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.quarkkingdee.top/Article/details/gtgjervfmr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtrbdnjwbl.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsjbajiea.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.guowangkeji.top/Article/details/gtnokuupfa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtmzoofbdg.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtkhqcvgzb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxuanxn.top/Article/details/gtwszfherz.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.aibaodan.cn/Article/details/gtcpdugqbt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzmepcldj.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtytazybac.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gtjudewhqf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtrbgzjgan.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gttwmjjcol.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.havefunace.top/Article/details/gtqagjvvmi.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtglsrnery.html

Py:   for i in range(10): print(i)
来源：http://dali.cashguo.top/Article/details/gtgeuvbqtx.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.sweek.top/Article/details/gtkhvbzdoj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gtizlucsqj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtgxguokrn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtxbisingn.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yj20258.top/Article/details/gtvabrxzhe.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jinqigufen.top/Article/details/gtyxqqovhp.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwtwdrgk.html

[B05] 遍历数组 / 列表
来源：http://dali.jiagoushi.top/Article/details/gtshmdtahp.html

Py:   for item in arr: print(item)
来源：http://dali.c1oappe.top/Article/details/gticdezxwm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yonumen.top/Article/details/gtodunofii.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gtkjwtzmuz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jyoumei.cn/Article/details/gtvwvkqiev.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.dianchejie.cn/Article/details/gtmnssksbe.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hnqzz.top/Article/details/gtafolzwek.html

Ruby: arr.each { |item| puts item }
来源：http://dali.snrcjt.cn/Article/details/gttfyzfhdk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyshcean.html

[B06] 遍历字典 / 对象
来源：http://dali.316326.xyz/Article/details/gtlokfajzn.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxinkj.top/Article/details/gtqtuhxdlv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.0kj1m.cn/Article/details/gtavkgpobx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yangfankeji.com/Article/details/gtbzmrabzw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtwwxlfnev.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.fengsongda.top/Article/details/gtukygmsnr.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.iojbl.cn/Article/details/gtojmkddww.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.quarkkingdee.top/Article/details/gtbiqugfmk.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.andypj.xyz/Article/details/gtyhvggpkr.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtolkbxjsf.html

Py:   while i < 10: i += 1
来源：http://dali.bjfxy.top/Article/details/gtsivejbax.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gzhubu.top/Article/details/gtcnzunawm.html

JS:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtxyoxysmg.html

TS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtyxefwbfg.html

Java: while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtifxbxiox.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gtgljyeuue.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxuanxn.top/Article/details/gtmzekoozh.html

C#:   while (i < 10) { i++; }
来源：http://dali.hysaishi.cn/Article/details/gtvqljksur.html

[B08] do-while（至少执行一次）
来源：http://dali.pengpengdd.cyou/Article/details/gtraqccnxe.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yanxiufei.cn/Article/details/gtczcydaep.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.c1oappe.top/Article/details/gtxzfkwgzz.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gthcrppgjh.html

TS:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtqknechpm.html

Java: do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtbqcbqcdi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.nanxuanxn.top/Article/details/gtkvquenyl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shanyushiyangtech.top/Article/details/gtwsnuwahw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenjidiqi.icu/Article/details/gtywugjksw.html

[B09] break 与 continue
来源：http://dali.0kj1m.cn/Article/details/gtoaqiifet.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtvopszaqc.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtglmpkual.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkgpwsgls.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cashguo.top/Article/details/gtlhxeypav.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dianchejie.cn/Article/details/gtuheqrlbl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yvedp.cn/Article/details/gtpdojoplr.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yangfankeji.com/Article/details/gtiqczsbtz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gttxeldvqa.html

[B10] 遍历同时拿索引
来源：http://dali.ppjwa.cn/Article/details/gtoyxblofb.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.ybcxt.top/Article/details/gthdhdsuip.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jiagoushi.top/Article/details/gtpyhbzihq.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.tianlin.xyz/Article/details/gtebquobir.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shanyushiyangtech.top/Article/details/gtwuttqofx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.daxiang520.top/Article/details/gtwzzxblky.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xylfe.cn/Article/details/gtewhjpfru.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtygthfgbt.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtbknkkeca.html

[B11] 生成数字序列 / 区间
来源：http://dali.iojbl.cn/Article/details/gthmcjoksx.html

Py:   list(range(0, 10, 2))
来源：http://dali.wangdashe.top/Article/details/gtzxczcopn.html

PHP:  range(0, 10, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtpaqpwzhq.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yj202588.top/Article/details/gtbucazcyh.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jiagoushi.top/Article/details/gtdatuwuia.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.jianghu66.top/Article/details/gtumdrcavc.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tian-w.cn/Article/details/gtryrypqys.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtichujgkz.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtfzmzhvai.html

[B12] 跳出多层循环
来源：http://dali.vqdsnc.cn/Article/details/gtlbwkgrog.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hammf.cn/Article/details/gtfupkwzvs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.gogol.net.cn/Article/details/gtesrpspke.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.daxiang520.top/Article/details/gtuaecptja.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtaprjyfcw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yj20258.top/Article/details/gtfgqwzvgj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhijiandao.cn/Article/details/gtlqjtvoim.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtbpijyltv.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.nanxinkj.top/Article/details/gtswuxucms.html

[B13] 判断是否为数字
来源：http://dali.yj202588.top/Article/details/gtjpiomadd.html

Py:   isinstance(x, (int, float))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtolkorvwt.html

PHP:  is_numeric($x)
来源：http://dali.pengpengdd.cyou/Article/details/gtjkdpzvcw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.pycfn.com/Article/details/gttrfloonx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhaomingkeji.xyz/Article/details/gteinxoypo.html

Java: x instanceof Number
来源：http://dali.ydzc1.top/Article/details/gtyhwcdiwv.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yueranfly.top/Article/details/gtfotjltqe.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtddoiulms.html

C#:   x is int or double or decimal
来源：http://dali.cdnleiting.top/Article/details/gtdsnknrow.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtkbvsoeup.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.fzhhl.top/Article/details/gtaoimubxm.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gtdrrgedrd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.ydzc1.top/Article/details/gtlqekuxsg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.chenzaomai.com/Article/details/gtyknnrbmg.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtazyodphi.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.meibo888.top/Article/details/gtkvfgxfas.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtjljravcj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.smart0.xyz/Article/details/gtlmvjqors.html

[B15] 布尔运算与取反
来源：http://dali.xziqi.cn/Article/details/gthopoyetu.html

Py:   a and b or not c
来源：http://dali.aizwys.cn/Article/details/gtmhvzhcob.html

PHP:  $a && $b || !$c
来源：http://dali.jyoumei.cn/Article/details/gtnjqqkyfp.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtpjryzmlh.html

TS:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gthhezktaa.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtmklrpzav.html

Go:   a && b || !c
来源：http://dali.zdqjudy.top/Article/details/gtwfhhiikr.html

Ruby: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtzcendmdk.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gtlnjkicld.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtzjjxfnlq.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtexoxbaqq.html

PHP:  if (!$data) { return; }
来源：http://dali.tanke756.top/Article/details/gtdecqdaye.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtyzfducvd.html

TS:   if (!data) return;
来源：http://dali.ppjwa.cn/Article/details/gtukkzqqes.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtjzqdinyq.html

Go:   if data == nil { return }
来源：http://dali.ydzc1.top/Article/details/gtihomlrux.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtjaicrbam.html

C#:   if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtixkzykuy.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlqujyiyy.html

C. 函数与作用域
来源：http://dali.sxryk.cn/Article/details/gtjmlccxdr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtcjrmahol.html

[C01] 定义函数
来源：http://dali.havefunace.top/Article/details/gtkarjawod.html

Py:   def add(a, b): return a + b
来源：http://dali.yj202588.top/Article/details/gtqznuycgr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdolyghrz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwrudtdx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yongpay.top/Article/details/gtdevbdazk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtnmvkfmai.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.snrcjt.cn/Article/details/gtxoxupklg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.nanxuanxn.top/Article/details/gttsgfcgbf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gtibywmpju.html

[C02] 默认参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpjqbqpbq.html

Py:   def greet(name="World"): return name
来源：http://dali.nwbrower.top/Article/details/gtkkefrukp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.cqqwz.cn/Article/details/gtosxlywah.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtzmqunbwf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.kuanghao11.cn/Article/details/gtgrkrvvrt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtuqzowyua.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtszzxdxjq.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtawbvukmw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sxryk.cn/Article/details/gtcwwjtlhb.html

[C03] 可变参数
来源：http://dali.vqdsnc.cn/Article/details/gtjlgpoybq.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtvvmsemsy.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.aibaodan.cn/Article/details/gtekwzjbst.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnxiangtu.top/Article/details/gtsfxkxdlr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtnidmduxl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.pycfn.com/Article/details/gtgmjpbrhg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zdqjudy.top/Article/details/gtopqyaebl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ydzc1.top/Article/details/gtcmqxrpxh.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtjbxtbxtr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gttuarmvtw.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.feifeiyinyue.top/Article/details/gtzckhbdcv.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yuxming.cn/Article/details/gtmoawqcse.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.smart0.xyz/Article/details/gtbguzitmg.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aizwys.cn/Article/details/gtkulsgikd.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gthfwpofbj.html

Go:   // 无：用配置结构体参数
来源：http://dali.sufxvd.cn/Article/details/gtmdoncwmi.html

Ruby: f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtgclrvqft.html

C#:   f(a: 1, b: 2)
来源：http://dali.gotoacloud.top/Article/details/gtujqwsivb.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gteyevlgrx.html

Py:   return a, b
来源：http://dali.tian-w.cn/Article/details/gthyyzjugt.html

PHP:  return [$a, $b];
来源：http://dali.chenjidiqi.icu/Article/details/gtrleotyem.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.ivvv.top/Article/details/gtqzeahjnb.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtwlmagyju.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.pengpengdd.cyou/Article/details/gtveexehfn.html

Go:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtsmufqjvl.html

Ruby: return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycmjzniw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.pengpengdd.cyou/Article/details/gtekmyphne.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtwgrfodtc.html

Py:   square = lambda x: x * x
来源：http://dali.nanxuanxn.top/Article/details/gtfdkzfxja.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.shanyushiyangtech.top/Article/details/gtdweopyyd.html

JS:   const square = x => x * x;
来源：http://dali.ybcxt.top/Article/details/gtldquonqm.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zycfv.cn/Article/details/gtafsybxrv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.bjfxy.top/Article/details/gtpibxigof.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.ppjwa.cn/Article/details/gtrdiiewyf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.meibo888.top/Article/details/gtfqzmsqlk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xinyue.icu/Article/details/gttofxdqzo.html

[C07] 把函数作为参数传入
来源：http://dali.tianlin.xyz/Article/details/gtobqprxgv.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtrktsvxpr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jianghu66.top/Article/details/gtydjdzlli.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.ehwqpu.com/Article/details/gtgvsdiclo.html

TS:   arr.map(String)
来源：http://dali.hnqzz.top/Article/details/gthvejggjq.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtciwezbpj.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.hnqzz.top/Article/details/gtjepfaxxm.html

Ruby: arr.map(&:upcase)
来源：http://dali.smart0.xyz/Article/details/gteuebdxyk.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.9152youxi.cn/Article/details/gtbouwnwle.html

[C08] 闭包
来源：http://dali.tian-w.cn/Article/details/gttexjncsn.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.yj20258.top/Article/details/gtfwesutkr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.gogol.net.cn/Article/details/gthgqjkswb.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfdgfiqzv.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.gotoacloud.top/Article/details/gtwysqarhk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.andypj.xyz/Article/details/gtzggeuura.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.0kj1m.cn/Article/details/gtssubfpzt.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.jinghuilouyu.cn/Article/details/gtdmbehsia.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gtzunezozq.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtzvphktsv.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.iojbl.cn/Article/details/gtmepgvvgn.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.shuidangran.top/Article/details/gthagkpchy.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.jinqigfzy.top/Article/details/gtixlcydbo.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.ppjwa.cn/Article/details/gterpxtwuc.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpwofltfo.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.redwolf501.top/Article/details/gtyqwsqvaf.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.guannengcc.top/Article/details/gteurndhlp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.316326.xyz/Article/details/gtnxzycioo.html

[C10] 变量作用域
来源：http://dali.zhengqikj.top/Article/details/gtmdcapkba.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.haohaochexian.top/Article/details/gtiqhtrqsi.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.gzhubu.top/Article/details/gttjomeaox.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdplsgdm.html

TS:   同 JS
来源：http://dali.zhoulong.xyz/Article/details/gtbkggfguh.html

Java: 方法内为块级作用域
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfpctltc.html

Go:   花括号块级作用域
来源：http://dali.9152youxi.cn/Article/details/gtvhgyqmjt.html

Ruby: 局部变量 / @实例 / @@类 / $全局
来源：http://dali.ydzc1.top/Article/details/gtciwkmcuj.html


<!-- 参考信息 -->