代发 wailian999

Ruby: a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtwyewlnly.html

C#:   (a, b) = (b, a);
来源：http://dali.quarkkingdee.top/Article/details/gtfhhdvgtw.html

[A20] 读取标准输入
来源：http://dali.shangyingyoupin.top/Article/details/gtmadyjahz.html

Py:   name = input("请输入：")
来源：http://dali.xuanzx.com/Article/details/gtqjfzyhtn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yanxiufei.cn/Article/details/gtufxcvgiu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtjemwcufa.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gtfwdwzodr.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xylfe.cn/Article/details/gtluwxynny.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.c1oappe.top/Article/details/gtbwtoinbt.html

Ruby: gets.chomp
来源：http://dali.gotoacloud.top/Article/details/gtwjcdxeyv.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gttofxmyed.html

[A21] 保留指定小数位输出
来源：http://dali.cheryme.top/Article/details/gtfansdbdm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.gotoacloud.top/Article/details/gtkakvwgsa.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtenrebduv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhijiandao.cn/Article/details/gtevcckuqx.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cdnleiting.top/Article/details/gtonzlmzii.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtfzjucqlf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.quarkkingdee.top/Article/details/gtlytyonkl.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtkugjgoty.html

C#:   3.14159.ToString("F2")
来源：http://dali.c1oappe.top/Article/details/gtvfwvtfpg.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtzodpxtap.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtgizztunk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.yuxming.cn/Article/details/gtdjphlqtj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gtexgligjb.html

TS:   s.length
来源：http://dali.pycfn.com/Article/details/gtjpwxkxqn.html

Java: s.length()
来源：http://dali.jiagoushi.top/Article/details/gttczwkuhi.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yj20258.top/Article/details/gtmwxlmphd.html

Ruby: s.length
来源：http://dali.svipenyu.cn/Article/details/gtrmihppna.html

C#:   s.Length
来源：http://dali.nanxinkj.top/Article/details/gtnshsjoak.html

[A23] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtoulxxkrt.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.chenjidiqi.icu/Article/details/gthxpqvxeb.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jinghuilouyu.cn/Article/details/gtlqzvjjln.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuanzhike.top/Article/details/gttctedbjc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtiodsrtnn.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhengqikj.top/Article/details/gtgzgqaglq.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjesxwul.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aizwys.cn/Article/details/gtlwjssglw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gogol.net.cn/Article/details/gtolekcxza.html

[A24] 去除首尾空白
来源：http://dali.fengsongda.top/Article/details/gtmhkfvrqa.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ybcxt.top/Article/details/gtwtvepzrd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.svipenyu.cn/Article/details/gtwohuxuga.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtibwxruyz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtwhvivszh.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gtxdfdrcca.html

Go:   strings.TrimSpace(s)
来源：http://dali.pycfn.com/Article/details/gtxtrfryfo.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yangfankeji.com/Article/details/gtcziczaic.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.feifeiyinyue.top/Article/details/gtcpeyvexe.html

[A25] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtccamjqkd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jianghu66.top/Article/details/gtngtamymu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jianghu66.top/Article/details/gtprpygbmu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtldsbtnel.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zdqjudy.top/Article/details/gtftnwpbkd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yj20258888.top/Article/details/gtmmpeqpwb.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gteoolyift.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gtgfvjnjgf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtmjsajeib.html

[A26] 类型转换总览
来源：http://dali.pycfn.com/Article/details/gtdmnznlek.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.guowangkeji.top/Article/details/gtgdqcjwcc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.haohaochexian.top/Article/details/gtljtozgff.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yvedp.cn/Article/details/gtguhvyutv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jinqigufen.top/Article/details/gtiwnrheyg.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.dashuyun.cn/Article/details/gtmbccaeyf.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnwxfslu.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zycfv.cn/Article/details/gtmqvntdui.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.andypj.xyz/Article/details/gtmsftxatx.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtwhrftipc.html

B. 流程控制
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbgnfoeme.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtbnfhvhqu.html

[B01] 条件判断 if / else
来源：http://dali.yongpay.top/Article/details/gtnyesaweb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zdqjudy.top/Article/details/gtmrvtnpww.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkwbzwoay.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.aibaodan.cn/Article/details/gtrwsytixv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtkimjleml.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtkycqcndd.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yonumen.top/Article/details/gtmnhhxdek.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.tianlin.xyz/Article/details/gtcknfqwwc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtwsswfubr.html

[B02] 多分支 else if / elif
来源：http://dali.snrcjt.cn/Article/details/gtsczibvdw.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuxming.cn/Article/details/gtygungmmo.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gtcudwwjbn.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdpdknsfo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtilkmfxmk.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtelwezozs.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.daxiang520.top/Article/details/gtomaqjmmm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnqzz.top/Article/details/gttscjwfos.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtbbgiffhb.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gtdheaabri.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxrfddfdu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtkdeaemis.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtmpbuicgk.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtahuaywlj.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtosvloxql.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuanzhike.top/Article/details/gthwpvmvae.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.dianchejie.cn/Article/details/gtrrnfnlnz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.mhx1999.top/Article/details/gtkmnzghaz.html

[B04] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtphaqjoyo.html

Py:   for i in range(10): print(i)
来源：http://dali.daria6918.cn/Article/details/gtbbqtfsvg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.quarkkingdee.top/Article/details/gtipejpypt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hnqzz.top/Article/details/gtoftscvuu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sysykeji.top/Article/details/gtgbwzwnbc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtjcdbimmp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ehwqpu.com/Article/details/gtdjmplffu.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtfgcoqjei.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gogol.net.cn/Article/details/gtdknlghph.html

[B05] 遍历数组 / 列表
来源：http://dali.gzhubu.top/Article/details/gtfuaagijz.html

Py:   for item in arr: print(item)
来源：http://dali.ehwqpu.com/Article/details/gtdrcnpydj.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.vqdsnc.cn/Article/details/gtlysfeafm.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtqbmscwlz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtrklsseks.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cqqwz.cn/Article/details/gtzenremmt.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.dianchejie.cn/Article/details/gtfzzusxhi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ppjwa.cn/Article/details/gtimzxgpwp.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gthsttqjxj.html

[B06] 遍历字典 / 对象
来源：http://dali.yanxiufei.cn/Article/details/gtpvkjcctr.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuxming.cn/Article/details/gtpudapizv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtrkphyrsy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.wangdashe.top/Article/details/gttifdvygo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtiomanvnl.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hongshengwenyu.top/Article/details/gtotneazuk.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.tanke756.top/Article/details/gtbtbmdprd.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hongshengwenyu.top/Article/details/gtfmribsec.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.vqdsnc.cn/Article/details/gtbeplxwoz.html

[B07] while 循环
来源：http://dali.cdnleiting.top/Article/details/gtbqmuqbdw.html

Py:   while i < 10: i += 1
来源：http://dali.chenjidiqi.icu/Article/details/gtkfokvphr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.fengsongda.top/Article/details/gtqwvrfyrr.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtzfdsmghs.html

TS:   while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtzextbdbt.html

Java: while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtmgjnjphx.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gtalrfgtfs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.tian-w.cn/Article/details/gtbzrzlsjv.html

C#:   while (i < 10) { i++; }
来源：http://dali.yj202588.top/Article/details/gteczoqrdi.html

[B08] do-while（至少执行一次）
来源：http://dali.chenzaomai.com/Article/details/gtlxpscwdl.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gthdgzweud.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtozdsctgy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtmffrjcwy.html

TS:   do { i++; } while (i < 10);
来源：http://dali.wangdashe.top/Article/details/gtzssqfskk.html

Java: do { i++; } while (i < 10);
来源：http://dali.smart0.xyz/Article/details/gtcdryvrlv.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yj20258888.top/Article/details/gtvdxatxnj.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.meibo888.top/Article/details/gttottzyrc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ydzc1.top/Article/details/gtdmdzzmjn.html

[B09] break 与 continue
来源：http://dali.dianchejie.cn/Article/details/gtpckrhvcq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gaohongyu789.top/Article/details/gtaygghseh.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtiozsurht.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtulqsaaxt.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtcwjssniz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtbsjksjjt.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gtrdyfvarf.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtzuinspyn.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgqfejadd.html

[B10] 遍历同时拿索引
来源：http://dali.kuanghao11.cn/Article/details/gtbqadewzz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.fzhhl.top/Article/details/gtvvbjahla.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ydzc1.top/Article/details/gtqokbjwyh.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtileelhet.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.jiagoushi.top/Article/details/gtwmylqcjc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtstbzitxx.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.gaohongyu789.top/Article/details/gttrqkjfok.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.hnqzz.top/Article/details/gtlpcdtpgd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yueranfly.top/Article/details/gtkcauvivu.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtdcslsnzh.html

Py:   list(range(0, 10, 2))
来源：http://dali.fengsongda.top/Article/details/gtyfnalnds.html

PHP:  range(0, 10, 2);
来源：http://dali.chenlongwang.top/Article/details/gtnuxnlddi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtdpevtixo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtlsrabtfl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gthlhrgnsh.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj202588.top/Article/details/gtbxppxkpm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtginzrplr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jinqigfzy.top/Article/details/gtksbbkvxa.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtytkomwft.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtytlwlgqo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.feifeiyinyue.top/Article/details/gtogcrzcah.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtfiqiabuh.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtrukpaaxh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtfboxzytb.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jinqigufen.top/Article/details/gtwtjmsvbi.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sufxvd.cn/Article/details/gtlbvgzorl.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.svipenyu.cn/Article/details/gtqtgxkemg.html

[B13] 判断是否为数字
来源：http://dali.hammf.cn/Article/details/gtzxftgsjz.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtppieeime.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtqjpfxhej.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gaohongyu789.top/Article/details/gthbnbriot.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtudhkhcuy.html

Java: x instanceof Number
来源：http://dali.gogol.net.cn/Article/details/gttfhszfvw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jlsjyb.cn/Article/details/gtuinhgbyh.html

Ruby: x.is_a?(Numeric)
来源：http://dali.svipenyu.cn/Article/details/gtdosmaswx.html

C#:   x is int or double or decimal
来源：http://dali.hongshengwenyu.top/Article/details/gtthxnrfer.html

[B14] 判断值是否在集合内
来源：http://dali.gaohongyu789.top/Article/details/gtgkxwsfis.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtyybghnfl.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gttrxqvhcp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtpgawegez.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.iojbl.cn/Article/details/gtupywfbzh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ivvv.top/Article/details/gtmwcmqfpo.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yueranfly.top/Article/details/gtosygaojd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhixingplan.top/Article/details/gtoiddqdwm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuanzhike.top/Article/details/gtfzvcztvx.html

[B15] 布尔运算与取反
来源：http://dali.fengsongda.top/Article/details/gtqhpinont.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtkdnqraoc.html

PHP:  $a && $b || !$c
来源：http://dali.yvedp.cn/Article/details/gtqjrxjohm.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtqlxiddxe.html

TS:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtmzvguzzw.html

Java: a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtghrseduq.html

Go:   a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtfrsbsfoe.html

Ruby: a && b || !c
来源：http://dali.smart0.xyz/Article/details/gtvbdqgcjj.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtksyipllc.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.daxiang520.top/Article/details/gtcilxthka.html

Py:   if not data: return
来源：http://dali.wangdashe.top/Article/details/gtaxtgevji.html

PHP:  if (!$data) { return; }
来源：http://dali.c1oappe.top/Article/details/gtinfftquf.html

JS:   if (!data) return;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqpifccsy.html

TS:   if (!data) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjypytpov.html

Java: if (data == null) return;
来源：http://dali.zdqjudy.top/Article/details/gtlfghhcfn.html

Go:   if data == nil { return }
来源：http://dali.vqdsnc.cn/Article/details/gtdedbrscs.html

Ruby: return if data.nil?
来源：http://dali.chenjidiqi.icu/Article/details/gtkafnpyez.html

C#:   if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtdcolbrje.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtcihcbkwr.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtfupevckn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtnxmctcdq.html

[C01] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gtscsjdlqc.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gtnvnrtejf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtcvzvpxhv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gthcsteffj.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.c1oappe.top/Article/details/gttlvxzuci.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtvhlogdme.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shzxlz.cn/Article/details/gtagptlkyh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xinyue.icu/Article/details/gtlwmpknjt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.andypj.xyz/Article/details/gtfrjbmjim.html

[C02] 默认参数
来源：http://dali.jqgufenzy.top/Article/details/gtjprestla.html

Py:   def greet(name="World"): return name
来源：http://dali.havefunace.top/Article/details/gtywydoydx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhongyouzk.top/Article/details/gtmuvpmogh.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxuanxn.top/Article/details/gtzqxpwypi.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ppjwa.cn/Article/details/gtzdxtqnwf.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yongpay.top/Article/details/gtrsdxttlu.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpavenvmd.html

Ruby: def greet(name = "World") = name
来源：http://dali.gaohongyu789.top/Article/details/gtravolgkc.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.guannengcc.top/Article/details/gtqrbydghe.html

[C03] 可变参数
来源：http://dali.jinqigufen.top/Article/details/gtmbyslbpf.html

Py:   def total(*args): return sum(args)
来源：http://dali.xuanzx.com/Article/details/gtkuihwawp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtzzbwzbgl.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shuidangran.top/Article/details/gtetcdegmm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xuanzx.com/Article/details/gtnxrbmzsf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yuanzhike.top/Article/details/gtbpnyimin.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ivvv.top/Article/details/gtvszijfkm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.bjfxy.top/Article/details/gtsiafjmry.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.dashuyun.cn/Article/details/gtheqcbuhq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sxryk.cn/Article/details/gteqehrtnv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jianghu66.top/Article/details/gtwovribhd.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.redwolf501.top/Article/details/gtujecixgf.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daxiang520.top/Article/details/gtzueogqud.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.daria6918.cn/Article/details/gtincwchfl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gthsnyhxwl.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gtkrvwlcmt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gtnvfirjoo.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtujkckyxe.html

[C05] 返回多个值
来源：http://dali.jianghu66.top/Article/details/gtnlsrtoet.html

Py:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtihhwbmla.html

PHP:  return [$a, $b];
来源：http://dali.redwolf501.top/Article/details/gtlfffrgqd.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.svipenyu.cn/Article/details/gtefptpzlh.html

TS:   return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtskgyxeex.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.zhijiandao.cn/Article/details/gtvimiaqdm.html

Go:   return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gtgurpfisc.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtcgsywppg.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jianghu66.top/Article/details/gtabdxctyn.html

[C06] 匿名函数 / lambda
来源：http://dali.andypj.xyz/Article/details/gtsoohyqbf.html

Py:   square = lambda x: x * x
来源：http://dali.9152youxi.cn/Article/details/gtkvjfjcjg.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jyoumei.cn/Article/details/gtgrlvarsc.html

JS:   const square = x => x * x;
来源：http://dali.fengsongda.top/Article/details/gtoxnobgkr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtxdwnjuyp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.smart0.xyz/Article/details/gtsecsoiih.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gtfhqrptrx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.xuetiantiany.cn/Article/details/gtpvupbgyr.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yueranfly.top/Article/details/gttztdjlef.html

[C07] 把函数作为参数传入
来源：http://dali.daria6918.cn/Article/details/gtabcqraxp.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.guowangkeji.top/Article/details/gtmlblzqmb.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.yueranfly.top/Article/details/gtvczhpfeq.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aizwys.cn/Article/details/gtyicjtvrb.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gtsnrxhxjg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtgnbdljzd.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.shuidangran.top/Article/details/gtehxlcyfq.html

Ruby: arr.map(&:upcase)
来源：http://dali.svipenyu.cn/Article/details/gtfohyimsd.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.hywenlv.cn/Article/details/gtjqploqba.html

[C08] 闭包
来源：http://dali.xziqi.cn/Article/details/gtttndkpvv.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkmxvfce.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxfannsy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtvdrypszq.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.jianghu66.top/Article/details/gtuscrkqzg.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.pycfn.com/Article/details/gtiariwmqj.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.birdmap.top/Article/details/gtzufygwhr.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.pengpengdd.cyou/Article/details/gtvcfxjwrb.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.kuanghao11.cn/Article/details/gtoxnfrkqi.html

[C09] 递归
来源：http://dali.gogol.net.cn/Article/details/gtgjgoandu.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.shangyingyoupin.top/Article/details/gthxdspebk.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.yueranfly.top/Article/details/gtaisugzgh.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtoytpfzcy.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.kuanghao11.cn/Article/details/gtrmkodwnz.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.shangyingyoupin.top/Article/details/gtwhbsdhez.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.yongpay.top/Article/details/gtnfmahkkc.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.ybcxt.top/Article/details/gtvzmgixqp.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.zycfv.cn/Article/details/gtgwjbnlvp.html

[C10] 变量作用域
来源：http://dali.xuanzx.com/Article/details/gtuwfhwcep.html

Py:   函数内赋值即局部；改外层需 global / nonlocal
来源：http://dali.zdqjudy.top/Article/details/gtyefjetbt.html

PHP:  函数内默认看不到外部变量，需 global 或 use
来源：http://dali.yvedp.cn/Article/details/gtxmwhxsya.html

JS:   let/const 块级作用域，var 函数级作用域
来源：http://dali.bjfxy.top/Article/details/gtxttzqwcc.html


<!-- 参考信息 -->