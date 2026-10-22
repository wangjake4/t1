代发 wailian999

JS:   [a, b] = [b, a];
来源：http://dali.chenlongwang.top/Article/details/gtatkcxzzv.html

TS:   [a, b] = [b, a];
来源：http://dali.cheryme.top/Article/details/gtywholhwi.html

Java: int t = a; a = b; b = t;
来源：http://dali.birdmap.top/Article/details/gttozacnxw.html

Go:   a, b = b, a
来源：http://dali.hammf.cn/Article/details/gtpzfzdjxk.html

Ruby: a, b = b, a
来源：http://dali.cucudq.cn/Article/details/gttxxfttty.html

C#:   (a, b) = (b, a);
来源：http://dali.yj20258.top/Article/details/gtjnpbbakd.html

[A20] 读取标准输入
来源：http://dali.zhengqikj.top/Article/details/gtahfuxbci.html

Py:   name = input("请输入：")
来源：http://dali.wangshuangyany.cn/Article/details/gttgsnrfnq.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj20258.top/Article/details/gtrrzakqfg.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.nanxuanxn.top/Article/details/gtkrmpdbdq.html

TS:   // Node.js：readline 模块
来源：http://dali.gogol.net.cn/Article/details/gtegnfurop.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gtyjusigeg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.sysykeji.top/Article/details/gtrmevpkbh.html

Ruby: gets.chomp
来源：http://dali.dashuyun.cn/Article/details/gtaljoxdfx.html

C#:   Console.ReadLine();
来源：http://dali.zhiwuduotai.top/Article/details/gtgeurmjim.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gtyyvnqbol.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gtvvkxywir.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtrthxqavq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtzjxoxxuk.html

TS:   (3.14159).toFixed(2)
来源：http://dali.redwolf501.top/Article/details/gtnbtvxbvu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtfesgcite.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gtgbolwrkk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.birdmap.top/Article/details/gtsxrbhlin.html

C#:   3.14159.ToString("F2")
来源：http://dali.gaohongyu789.top/Article/details/gtbtfvjsrm.html

[A22] 获取字符串长度
来源：http://dali.bjfxy.top/Article/details/gtnmywflht.html

Py:   len(s)
来源：http://dali.yanxiufei.cn/Article/details/gtzuredpvm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhiwuduotai.top/Article/details/gtdaqxjdxu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ppjwa.cn/Article/details/gtkgpkssaz.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtwfnfwfmt.html

Java: s.length()
来源：http://dali.xylfe.cn/Article/details/gthvtwigfd.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtzkpzlvjh.html

Ruby: s.length
来源：http://dali.cheryme.top/Article/details/gtkhkrbipn.html

C#:   s.Length
来源：http://dali.andypj.xyz/Article/details/gteukmlvfy.html

[A23] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gtajdhdlao.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.snrcjt.cn/Article/details/gthpofqohj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.guowangkeji.top/Article/details/gtseofnzdn.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtnvbsdrhp.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.cdnleiting.top/Article/details/gtivsczxsz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtujmyyxog.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hnxiangtu.top/Article/details/gtttetyhze.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ydzc1.top/Article/details/gtfsnulxbj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ydzc1.top/Article/details/gtqfamnwei.html

[A24] 去除首尾空白
来源：http://dali.hysaishi.cn/Article/details/gtcfdfskrt.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.ppjwa.cn/Article/details/gtjtzmdjnj.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.cheryme.top/Article/details/gtcxqdoayp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.chenjidiqi.icu/Article/details/gthogppdsq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yj202588.top/Article/details/gtcpzmmvwy.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.yonumen.top/Article/details/gtxooefljs.html

Go:   strings.TrimSpace(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtgzksnqqb.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.ydzc1.top/Article/details/gtldujvnks.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.andypj.xyz/Article/details/gtlalqymeq.html

[A25] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtcqdxivfp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gtrwhllzpo.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yangfankeji.com/Article/details/gtxtfbtbrq.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sweek.top/Article/details/gtcvxucrfn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yuanzhike.top/Article/details/gtpxjiyapa.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.aizwys.cn/Article/details/gtpsjptpjo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.wangdashe.top/Article/details/gtuugiphtz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jlsjyb.cn/Article/details/gtkdgypfkf.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.kuanghao11.cn/Article/details/gtrwmxqmhu.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtohlsszau.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.sufxvd.cn/Article/details/gtgqljkcux.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnrdsgwoh.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hysaishi.cn/Article/details/gtahijxovf.html

TS:   Number() String() Boolean() x as number
来源：http://dali.fzhhl.top/Article/details/gtsdobvwyr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtghhxvfhi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.tanke756.top/Article/details/gttjfssapm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yonumen.top/Article/details/gtsytcwnsh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.ppjwa.cn/Article/details/gtttrxkydw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtaoqxeeos.html

B. 流程控制
来源：http://dali.shzxlz.cn/Article/details/gtdbiuenvy.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtqhilsgrp.html

[B01] 条件判断 if / else
来源：http://dali.hysaishi.cn/Article/details/gtfflxtigx.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnmhrexrv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.nanxuanxn.top/Article/details/gthsutksau.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwfnkyhiq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtcvaijszs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gtrfyverdf.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jiagoushi.top/Article/details/gtwtwslebm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.0kj1m.cn/Article/details/gtvklhwpbb.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkpelpjb.html

[B02] 多分支 else if / elif
来源：http://dali.zhijiandao.cn/Article/details/gtdjogezgk.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.shzxlz.cn/Article/details/gtlfnckezn.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.svipenyu.cn/Article/details/gtafvaddhp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhongyouzk.top/Article/details/gtcjrpqbpz.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtjeqlyyuu.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtyfyouavx.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.dianchejie.cn/Article/details/gtrscdybso.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.kuanghao11.cn/Article/details/gtayxacuwj.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtwunubfac.html

[B03] switch / match / case
来源：http://dali.shuidangran.top/Article/details/gtnsmfmbty.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.pycfn.com/Article/details/gtxbvpfcum.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jqgufenzy.top/Article/details/gtmwqcrsvm.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yonumen.top/Article/details/gtukutapna.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtjzrnnrrc.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtpalyctux.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuanzx.com/Article/details/gtpftseyic.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.guowangkeji.top/Article/details/gtdldzvlcr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.0kj1m.cn/Article/details/gtmucnptus.html

[B04] for 计数循环
来源：http://dali.sweek.top/Article/details/gtcpikelgh.html

Py:   for i in range(10): print(i)
来源：http://dali.zhijiandao.cn/Article/details/gtdpkasjby.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yvedp.cn/Article/details/gtwplysbrd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gtdttuqgcu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtnzertveu.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlpwtsxjd.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yueranfly.top/Article/details/gttylgffbd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.haohaochexian.top/Article/details/gtsbbsxzeg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.316326.xyz/Article/details/gtpbbdfued.html

[B05] 遍历数组 / 列表
来源：http://dali.jqgfzy.top/Article/details/gtpqqfxleq.html

Py:   for item in arr: print(item)
来源：http://dali.xuetiantiany.cn/Article/details/gtjtipqymo.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtbfvzthyt.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.hnxiangtu.top/Article/details/gtobittfru.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.sysykeji.top/Article/details/gtbnqivyjx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.0kj1m.cn/Article/details/gtuidnzrcp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gtqxzdqmit.html

Ruby: arr.each { |item| puts item }
来源：http://dali.dashuyun.cn/Article/details/gtbtecdihs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sysykeji.top/Article/details/gtwhwblcbt.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gtxuuzltll.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.andypj.xyz/Article/details/gtaretndsf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.shzxlz.cn/Article/details/gtleejmpug.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtphyqxxqa.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkysiwjsp.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.316326.xyz/Article/details/gtvlxxebgc.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.aizwys.cn/Article/details/gtxojqpcts.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.wangdashe.top/Article/details/gtkmocfiom.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.pengpengdd.cyou/Article/details/gtdxlmbsqb.html

[B07] while 循环
来源：http://dali.dashuyun.cn/Article/details/gtqkxiwtsx.html

Py:   while i < 10: i += 1
来源：http://dali.c1oappe.top/Article/details/gtwvgdscan.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ivvv.top/Article/details/gtpkasmvle.html

JS:   while (i < 10) { i++; }
来源：http://dali.yuanzhike.top/Article/details/gtvbfloyuv.html

TS:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gtixnmjnhm.html

Java: while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtwlzspmmn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.gaohongyu789.top/Article/details/gtkusysrck.html

Ruby: while i < 10; i += 1; end
来源：http://dali.9152youxi.cn/Article/details/gtpsnpqyjv.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gtthintcve.html

[B08] do-while（至少执行一次）
来源：http://dali.havefunace.top/Article/details/gtidriqvmj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.aibaodan.cn/Article/details/gthmaifazn.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtdnrhnbkj.html

JS:   do { i++; } while (i < 10);
来源：http://dali.redwolf501.top/Article/details/gtzruijutq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtdplzghdn.html

Java: do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtnxfekfvw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gotoacloud.top/Article/details/gtfsgmyxwf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.shzxlz.cn/Article/details/gtqibkfrmt.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sysykeji.top/Article/details/gtsjbuhykm.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtoiqihefm.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yueranfly.top/Article/details/gtmxnsbmsm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtxmminwqc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxuanxn.top/Article/details/gtwolddyba.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtshebqrtj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtwxzpyijv.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtgoxtgotk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gaohongyu789.top/Article/details/gtzrgzroiz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtjutlzrta.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gtblwnbgwi.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yj20258.top/Article/details/gttqqdxjzt.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gtchntrwqs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.mhx1999.top/Article/details/gtikmryykn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.chenjidiqi.icu/Article/details/gtcowdawjh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtcvtaxvvh.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shzxlz.cn/Article/details/gtguejzggx.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yueranfly.top/Article/details/gtmqdzasnx.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yangfankeji.com/Article/details/gtsapfgjlj.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuanzhike.top/Article/details/gtlckepear.html

Py:   list(range(0, 10, 2))
来源：http://dali.kuanghao11.cn/Article/details/gtdnmkvklu.html

PHP:  range(0, 10, 2);
来源：http://dali.yuanzhike.top/Article/details/gtpaexgzis.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtbkefwkeo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ppjwa.cn/Article/details/gtdauxwqfd.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ivvv.top/Article/details/gtdqazqmyo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.aibaodan.cn/Article/details/gtljaptvjc.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cashguo.top/Article/details/gtbikktsdq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hysaishi.cn/Article/details/gtcitfixul.html

[B12] 跳出多层循环
来源：http://dali.chenjidiqi.icu/Article/details/gtucmxjbxl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xziqi.cn/Article/details/gtkmftzvwf.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hfpthk.cn/Article/details/gtpwskmfsa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtkvgrkqlg.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtluaekadb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.andypj.xyz/Article/details/gtctbpwcjr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.guannengcc.top/Article/details/gtxtmwezhw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtvjmrgbro.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtznmllezy.html

[B13] 判断是否为数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfaesarn.html

Py:   isinstance(x, (int, float))
来源：http://dali.jqgufenzy.top/Article/details/gtoiikpypj.html

PHP:  is_numeric($x)
来源：http://dali.kuanghao11.cn/Article/details/gtvrlzmhmf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aibaodan.cn/Article/details/gtxyabkypl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.hysaishi.cn/Article/details/gtxvmjcbrs.html

Java: x instanceof Number
来源：http://dali.shangyingyoupin.top/Article/details/gtplkqdddk.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sysykeji.top/Article/details/gtddgnymkj.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xziqi.cn/Article/details/gtjsgvujvh.html

C#:   x is int or double or decimal
来源：http://dali.pengpengdd.cyou/Article/details/gtedwjlars.html

[B14] 判断值是否在集合内
来源：http://dali.chenzaomai.com/Article/details/gtidszflrb.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.svipenyu.cn/Article/details/gtjebxeepp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jiagoushi.top/Article/details/gtsqhuwqvt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.daxiang520.top/Article/details/gtohourwor.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgufenzy.top/Article/details/gtzznxkjgk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.iojbl.cn/Article/details/gtjsducjhp.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.sxryk.cn/Article/details/gtykoiuwog.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cqqwz.cn/Article/details/gtsaegbmtk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhixingplan.top/Article/details/gtrkhbclxd.html

[B15] 布尔运算与取反
来源：http://dali.daria6918.cn/Article/details/gtaewpigue.html

Py:   a and b or not c
来源：http://dali.xylfe.cn/Article/details/gtrdldtjzr.html

PHP:  $a && $b || !$c
来源：http://dali.zhongyouzk.top/Article/details/gtfzftmhoy.html

JS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gtflmgigfw.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gthwvupzau.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtejwudghv.html

Go:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtpbjfkqhz.html

Ruby: a && b || !c
来源：http://dali.bjfxy.top/Article/details/gtmwdybnau.html

C#:   a && b || !c
来源：http://dali.gaohongyu789.top/Article/details/gthuyyzyrd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yangfankeji.com/Article/details/gtydyrvvnd.html

Py:   if not data: return
来源：http://dali.hnqzz.top/Article/details/gtkqtefqse.html

PHP:  if (!$data) { return; }
来源：http://dali.0kj1m.cn/Article/details/gtyixkxgkg.html

JS:   if (!data) return;
来源：http://dali.haohaochexian.top/Article/details/gtkxknvtaq.html

TS:   if (!data) return;
来源：http://dali.zhiwuduotai.top/Article/details/gthnkgzksa.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtxozkbnmp.html

Go:   if data == nil { return }
来源：http://dali.andypj.xyz/Article/details/gtilhhifpu.html

Ruby: return if data.nil?
来源：http://dali.havefunace.top/Article/details/gtsofqgywr.html

C#:   if (data == null) return;
来源：http://dali.hnxiangtu.top/Article/details/gtkvvtqdpp.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtjtvzovhq.html

C. 函数与作用域
来源：http://dali.nwbrower.top/Article/details/gtovoldgfn.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtyqvdwroz.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtskvcaale.html

Py:   def add(a, b): return a + b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzdbkmrba.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gtaynunkdk.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtlzcxxvvb.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.hammf.cn/Article/details/gtotmpsmbz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtywshvmkk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.c1oappe.top/Article/details/gthggxuojt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtncketbfj.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.cucudq.cn/Article/details/gtqfptekqz.html

[C02] 默认参数
来源：http://dali.daxiang520.top/Article/details/gtuygnnzcj.html

Py:   def greet(name="World"): return name
来源：http://dali.jyoumei.cn/Article/details/gtrujqvnnq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zhiwuduotai.top/Article/details/gttrmzbmoa.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmkiesnfu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.meibo888.top/Article/details/gtfdimqfda.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtnjyuebml.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtgufufdsp.html

Ruby: def greet(name = "World") = name
来源：http://dali.quarkkingdee.top/Article/details/gtlutnxwat.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258888.top/Article/details/gtfjjdqfng.html

[C03] 可变参数
来源：http://dali.xuetiantiany.cn/Article/details/gtpjjsypeh.html

Py:   def total(*args): return sum(args)
来源：http://dali.havefunace.top/Article/details/gtjppbtckm.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hysaishi.cn/Article/details/gtxeuqnmne.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtxkorajhk.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sxryk.cn/Article/details/gtzcipsfem.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.gogol.net.cn/Article/details/gtonpngkvp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cashguo.top/Article/details/gtrcuoiryl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.guowangkeji.top/Article/details/gtxaeoxvky.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.xylfe.cn/Article/details/gtufjjlwcz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cashguo.top/Article/details/gtqoepillq.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlrqharwo.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yueranfly.top/Article/details/gtukqkyswv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gtehuzvdqq.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.hywenlv.cn/Article/details/gtxoesrqku.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shuidangran.top/Article/details/gtpliebeda.html

Go:   // 无：用配置结构体参数
来源：http://dali.hnxiangtu.top/Article/details/gtwpwzqexp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ydzc1.top/Article/details/gtxmvlrbtl.html

C#:   f(a: 1, b: 2)
来源：http://dali.xylfe.cn/Article/details/gtgupaaptx.html

[C05] 返回多个值
来源：http://dali.meibo888.top/Article/details/gtaxcyrmqr.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtcctlnqxv.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gtjqextssu.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrmzdnour.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtivinsbeo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuanzx.com/Article/details/gtusgayzty.html

Go:   return a, b
来源：http://dali.yongpay.top/Article/details/gtmxpbtvdq.html

Ruby: return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtaecrfhjk.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.nanxinkj.top/Article/details/gtwnqwvysw.html

[C06] 匿名函数 / lambda
来源：http://dali.jyoumei.cn/Article/details/gtupqjnxhv.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gtbyieqskm.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cdnleiting.top/Article/details/gtujvuqqck.html

JS:   const square = x => x * x;
来源：http://dali.jinqigufen.top/Article/details/gtwyzmquan.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.birdmap.top/Article/details/gtkwcmxgjo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtegfsocjg.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yvedp.cn/Article/details/gtfatzsbad.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhiwuduotai.top/Article/details/gttughbxxf.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.cucudq.cn/Article/details/gtkxvxazzz.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtpyirpduo.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zdqjudy.top/Article/details/gthniwhekr.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenlongwang.top/Article/details/gtizkdalbu.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hnqzz.top/Article/details/gtgilzfsfz.html

TS:   arr.map(String)
来源：http://dali.tanke756.top/Article/details/gtamarvpda.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sysykeji.top/Article/details/gtasqsapep.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.mhx1999.top/Article/details/gtotvtamkt.html

Ruby: arr.map(&:upcase)
来源：http://dali.wangshuangyany.cn/Article/details/gtmohdvfjj.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvrlzqdm.html

[C08] 闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrrnqoeql.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoezkmmxz.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xinyue.icu/Article/details/gtkvzochuy.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.xuetiantiany.cn/Article/details/gtahzzwwyy.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.yvedp.cn/Article/details/gtwjiallkc.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.nanxuanxn.top/Article/details/gtyeyfmssz.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.sxryk.cn/Article/details/gtlucfoznw.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.zhijiandao.cn/Article/details/gtalrotecl.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.zhengqikj.top/Article/details/gtoywqeqvc.html

[C09] 递归
来源：http://dali.tian-w.cn/Article/details/gtfxuqpasq.html

Py:   def fact(n): return 1 if n <= 1 else n * fact(n - 1)
来源：http://dali.daria6918.cn/Article/details/gtdanzfeon.html

PHP:  function fact(int $n): int { return $n <= 1 ? 1 : $n * fact($n - 1); }
来源：http://dali.xziqi.cn/Article/details/gtqkdkyoik.html

JS:   const fact = n => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.aizwys.cn/Article/details/gtptckdxgw.html

TS:   const fact = (n: number): number => (n <= 1 ? 1 : n * fact(n - 1));
来源：http://dali.zdqjudy.top/Article/details/gtddbslmit.html

Java: static int fact(int n) { return n <= 1 ? 1 : n * fact(n - 1); }
来源：http://dali.jqgufenzy.top/Article/details/gtiaoufboc.html

Go:   func fact(n int) int { if n <= 1 { return 1 }; return n * fact(n-1) }
来源：http://dali.wangdashe.top/Article/details/gthejdtzem.html

Ruby: def fact(n) = n <= 1 ? 1 : n * fact(n - 1)
来源：http://dali.sufxvd.cn/Article/details/gtzkljtmsx.html

C#:   static int Fact(int n) => n <= 1 ? 1 : n * Fact(n - 1);
来源：http://dali.cheryme.top/Article/details/gtqhtyujya.html


<!-- 参考信息 -->