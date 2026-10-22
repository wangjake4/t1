代发 wailian999

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.chenjidiqi.icu/Article/details/gtwedclqwf.html

Java: (int) 'A'; (char) 65
来源：http://dali.guannengcc.top/Article/details/gtvxszhosf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gthjyfsvbh.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gtunadgisd.html

C#:   (int)'A'; (char)65
来源：http://dali.xuetiantiany.cn/Article/details/gtmgjjhqse.html

[A19] 交换两个变量
来源：http://dali.fzhhl.top/Article/details/gttlwqntsf.html

Py:   a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtsourrkic.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.feifeiyinyue.top/Article/details/gthtzjgqzq.html

JS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gtdcyovfbg.html

TS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gtyqseoiyz.html

Java: int t = a; a = b; b = t;
来源：http://dali.sxryk.cn/Article/details/gtynxhucnf.html

Go:   a, b = b, a
来源：http://dali.9152youxi.cn/Article/details/gtwnrcporc.html

Ruby: a, b = b, a
来源：http://dali.zhixingplan.top/Article/details/gtbqxwcber.html

C#:   (a, b) = (b, a);
来源：http://dali.fengsongda.top/Article/details/gtrcvchwil.html

[A20] 读取标准输入
来源：http://dali.zhijiandao.cn/Article/details/gtbyjmbghn.html

Py:   name = input("请输入：")
来源：http://dali.gogol.net.cn/Article/details/gtzuvfeogm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.redwolf501.top/Article/details/gtpaatiwsh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.feifeiyinyue.top/Article/details/gtnemdcmos.html

TS:   // Node.js：readline 模块
来源：http://dali.shzxlz.cn/Article/details/gtmouvcehh.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.cheryme.top/Article/details/gtctghjeyq.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.iojbl.cn/Article/details/gtajfnocbp.html

Ruby: gets.chomp
来源：http://dali.iojbl.cn/Article/details/gtwxdqpydz.html

C#:   Console.ReadLine();
来源：http://dali.ivvv.top/Article/details/gtkczgeurc.html

[A21] 保留指定小数位输出
来源：http://dali.hysaishi.cn/Article/details/gtnbwwfkjh.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tianlin.xyz/Article/details/gtnzwwqivt.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtwkroecub.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aizwys.cn/Article/details/gtnvuftbdg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtnctaemzg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtggyzhbti.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtrvrajvse.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fzhhl.top/Article/details/gtvarjajzi.html

C#:   3.14159.ToString("F2")
来源：http://dali.smart0.xyz/Article/details/gttmbhuccn.html

[A22] 获取字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtqisgivpd.html

Py:   len(s)
来源：http://dali.jqgfzy.top/Article/details/gtanwjksek.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhongyouzk.top/Article/details/gtibclqihi.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.quarkkingdee.top/Article/details/gthqxprxve.html

TS:   s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtzckiexuh.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtdkvhhtwf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.smart0.xyz/Article/details/gtzdrzbhls.html

Ruby: s.length
来源：http://dali.sxryk.cn/Article/details/gtbtwwxwcw.html

C#:   s.Length
来源：http://dali.yuanzhike.top/Article/details/gtcchzhqnn.html

[A23] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtglpesmxa.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.quarkkingdee.top/Article/details/gtusqcvuxs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gtfljjsfjz.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtuyuymewq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.pengpengdd.cyou/Article/details/gtrkcvanqk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtanvizjsr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.quarkkingdee.top/Article/details/gtjhhphdkk.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvyrqhyd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj20258888.top/Article/details/gtwfwpjcja.html

[A24] 去除首尾空白
来源：http://dali.xziqi.cn/Article/details/gtlbkqgkuj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gttnyhufrs.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gtzrgrqjtv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ybcxt.top/Article/details/gthdunofum.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtkyatcpyi.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dashuyun.cn/Article/details/gtpjjznoyj.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtbiyddqey.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.zycfv.cn/Article/details/gteompaqgf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hfpthk.cn/Article/details/gttywdmgwx.html

[A25] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtwwpkjenw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtyvjxgwmf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtssliaofb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtjqxgfboe.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtnqrfcnwy.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.ehwqpu.com/Article/details/gtrymqaynr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gtszkhgrgz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tanke756.top/Article/details/gtcqvbylmv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.andypj.xyz/Article/details/gtjwlhcwno.html

[A26] 类型转换总览
来源：http://dali.pengpengdd.cyou/Article/details/gtzykasdga.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gtgfxblewu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtroitqfut.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtzbuvpava.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cucudq.cn/Article/details/gtgvjajrar.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gaohongyu789.top/Article/details/gtejpcwbyq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.feifeiyinyue.top/Article/details/gtbrulampv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.chenlongwang.top/Article/details/gtzpbasqhi.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtratyxhoq.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtckoyiqty.html

B. 流程控制
来源：http://dali.smart0.xyz/Article/details/gtwcntrvoo.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtmsdmnmyy.html

[B01] 条件判断 if / else
来源：http://dali.daxiang520.top/Article/details/gtjqvwesmk.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tanke756.top/Article/details/gtytnlvltw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadadqlcw.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gtdyghofoy.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtcugksxnl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dianchejie.cn/Article/details/gttvsukuvv.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.bjfxy.top/Article/details/gtjttliozf.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.daria6918.cn/Article/details/gtqctyvmkh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.sxryk.cn/Article/details/gtfhxalxyk.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxamshvdh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.guannengcc.top/Article/details/gtatvyrihe.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guannengcc.top/Article/details/gtkwytndrl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gturqoujqh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtffbuwjbp.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtcouwwthe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gaohongyu789.top/Article/details/gtxjgzzvsb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jqgfzy.top/Article/details/gtmjqqwoks.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.svipenyu.cn/Article/details/gtcedohktv.html

[B03] switch / match / case
来源：http://dali.tian-w.cn/Article/details/gtddzglkcf.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.hysaishi.cn/Article/details/gtpkdxczkt.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cucudq.cn/Article/details/gtsylkjtdj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtnmkzcxor.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj20258.top/Article/details/gtlpgiawyy.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtdqryicxd.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtqujlmqft.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.hongshengwenyu.top/Article/details/gtoecloxur.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gtkpfrtbbw.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtqsplvhgt.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtlswnnybr.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.cqqwz.cn/Article/details/gtrnwehlyj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.hfpthk.cn/Article/details/gtpbhxmdzo.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ehwqpu.com/Article/details/gtvtsqvecs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.birdmap.top/Article/details/gtayxjbsdc.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yuxming.cn/Article/details/gtkyykyzqc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtihqnblna.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.bjfxy.top/Article/details/gtlyeqksec.html

[B05] 遍历数组 / 列表
来源：http://dali.yonumen.top/Article/details/gtflkqfxra.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtfjyzfzhu.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhixingplan.top/Article/details/gtqcsichlz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.gotoacloud.top/Article/details/gtluvhfkbl.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.jlsjyb.cn/Article/details/gtdxiqgjdm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtiixfixas.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gotoacloud.top/Article/details/gtcqxmtzfu.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cqqwz.cn/Article/details/gtokxzzfgj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jianghu66.top/Article/details/gtzgmtneam.html

[B06] 遍历字典 / 对象
来源：http://dali.hnxiangtu.top/Article/details/gtowmgyjik.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtljuvrnzm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtvgjfrebx.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gterylnjna.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtwdrpiiyo.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.jqgfzy.top/Article/details/gtdmxaxrvn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtwmijwldy.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigufen.top/Article/details/gttegggcpr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jinqigfzy.top/Article/details/gtktqaufyh.html

[B07] while 循环
来源：http://dali.yonumen.top/Article/details/gtskeejmuv.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtvuzhrlki.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtabizabrx.html

JS:   while (i < 10) { i++; }
来源：http://dali.chenlongwang.top/Article/details/gtizhsixjc.html

TS:   while (i < 10) { i++; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgvqmzdih.html

Java: while (i < 10) { i++; }
来源：http://dali.hywenlv.cn/Article/details/gtnmjutuzi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.pycfn.com/Article/details/gtftavbvwj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtpxamvwvr.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtdwhkuwth.html

[B08] do-while（至少执行一次）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsyxgqcdj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cheryme.top/Article/details/gtqhjodbla.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.sweek.top/Article/details/gtgzjqlnrl.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtnbrjcvhq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gtavnhpztv.html

Java: do { i++; } while (i < 10);
来源：http://dali.c1oappe.top/Article/details/gtizgrvndd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gaohongyu789.top/Article/details/gtwknjxxkv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.andypj.xyz/Article/details/gtzlvyfauw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhixingplan.top/Article/details/gtdajwyezb.html

[B09] break 与 continue
来源：http://dali.zhoulong.xyz/Article/details/gtgqffhcen.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.gogol.net.cn/Article/details/gtustpweyo.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.haohaochexian.top/Article/details/gtepsskyrv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtnyoclunn.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtokbgobch.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gtcwbihmll.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gtwhmpexco.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtbugjtaal.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtpwldineg.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gteohytbjp.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.guowangkeji.top/Article/details/gthxymwicv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gtbzknwwvx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ivvv.top/Article/details/gtumcnushz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zdqjudy.top/Article/details/gtawiclxra.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtbspubkkt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.chenjidiqi.icu/Article/details/gtcwnmnrld.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtyxfrtend.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.andypj.xyz/Article/details/gtjbyjswid.html

[B11] 生成数字序列 / 区间
来源：http://dali.hysaishi.cn/Article/details/gtlxkdxqok.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtcmazokwl.html

PHP:  range(0, 10, 2);
来源：http://dali.snrcjt.cn/Article/details/gtcxnrtfqh.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtfxnveauu.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xinyue.icu/Article/details/gtddrcpxlw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hnxiangtu.top/Article/details/gtlcjehtjb.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.wangshuangyany.cn/Article/details/gtnkvecsul.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtwlgnyxcn.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nanxuanxn.top/Article/details/gtirxbvete.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gtplceyiqk.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yvedp.cn/Article/details/gtwudowrtj.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.kuanghao11.cn/Article/details/gttzhojjxj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtanphqffz.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtobyirwwm.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtudttnxtv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.iojbl.cn/Article/details/gtlhmtwmow.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtboiymdmh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.iojbl.cn/Article/details/gtmmgtrmon.html

[B13] 判断是否为数字
来源：http://dali.sxryk.cn/Article/details/gtowxmwnpx.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gthpvpcjjk.html

PHP:  is_numeric($x)
来源：http://dali.yongpay.top/Article/details/gtxcuhhxfo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtlbkumvge.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtbnpelqcy.html

Java: x instanceof Number
来源：http://dali.haohaochexian.top/Article/details/gtbcbrbofe.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yuxming.cn/Article/details/gtybglhmzc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinqigfzy.top/Article/details/gtzggkfnsh.html

C#:   x is int or double or decimal
来源：http://dali.mhx1999.top/Article/details/gtiughmsxt.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtgvmtepse.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.9152youxi.cn/Article/details/gtrsazlewc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ybcxt.top/Article/details/gtxfrdrrrc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yvedp.cn/Article/details/gtwsugelwb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yanxiufei.cn/Article/details/gtgxtbmczm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.daxiang520.top/Article/details/gtypshgzvd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gtozxugpru.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cheryme.top/Article/details/gtfdrblcue.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtkbmezvin.html

[B15] 布尔运算与取反
来源：http://dali.ppjwa.cn/Article/details/gtpxuaygro.html

Py:   a and b or not c
来源：http://dali.316326.xyz/Article/details/gtivunbert.html

PHP:  $a && $b || !$c
来源：http://dali.cdnleiting.top/Article/details/gtxuilnqma.html

JS:   a && b || !c
来源：http://dali.gotoacloud.top/Article/details/gtdoufdchk.html

TS:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtvihscwss.html

Java: a && b || !c
来源：http://dali.xziqi.cn/Article/details/gtoajubuhz.html

Go:   a && b || !c
来源：http://dali.nwbrower.top/Article/details/gtmjsxdnlz.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gtiqfcifch.html

C#:   a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtfqzdpivj.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yongpay.top/Article/details/gtrnodjjzc.html

Py:   if not data: return
来源：http://dali.hnxiangtu.top/Article/details/gtgfnjowiu.html

PHP:  if (!$data) { return; }
来源：http://dali.xuanzx.com/Article/details/gtjuvvcmud.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtmlmkpbtd.html

TS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtnrpaimaz.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gtjwghnuwz.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gthnyludmk.html

Ruby: return if data.nil?
来源：http://dali.ppjwa.cn/Article/details/gtpflofrkw.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtbuxdolcr.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtycqwvjbj.html

C. 函数与作用域
来源：http://dali.nanxinkj.top/Article/details/gtivnrswev.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqsgjpwh.html

[C01] 定义函数
来源：http://dali.xylfe.cn/Article/details/gtnqbkzeiz.html

Py:   def add(a, b): return a + b
来源：http://dali.fengsongda.top/Article/details/gtoqgpqgvf.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylkarmkb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtivzcwxrn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtxzwmlvpd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtdjyitpev.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuanzhike.top/Article/details/gtsuxuojht.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnxiangtu.top/Article/details/gtphmdkwla.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtpbljewac.html

[C02] 默认参数
来源：http://dali.dianchejie.cn/Article/details/gtpsmrljgu.html

Py:   def greet(name="World"): return name
来源：http://dali.cashguo.top/Article/details/gtwjhfdykp.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.daria6918.cn/Article/details/gthxltzlzf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.ydzc1.top/Article/details/gtpjqcbywo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.sweek.top/Article/details/gtovwvhsdc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.316326.xyz/Article/details/gtrfpxajgi.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigfzy.top/Article/details/gtphfzgeig.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuetiantiany.cn/Article/details/gtrdnhmixz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gaohongyu789.top/Article/details/gtsxsqvbcc.html

[C03] 可变参数
来源：http://dali.nanxuanxn.top/Article/details/gtkgyirkkz.html

Py:   def total(*args): return sum(args)
来源：http://dali.jianghu66.top/Article/details/gtghoqqasj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.cheryme.top/Article/details/gtpdhgrjuq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangtech.top/Article/details/gteswwibzx.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jqgfzy.top/Article/details/gtwvpfofkl.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.hnqzz.top/Article/details/gtzhatygbt.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.bjfxy.top/Article/details/gtwngoazhb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daria6918.cn/Article/details/gtzyuslhmc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.0kj1m.cn/Article/details/gtqqrdmrbl.html

[C04] 命名参数 / 关键字参数
来源：http://dali.birdmap.top/Article/details/gtsmtincpb.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.pycfn.com/Article/details/gtvyjtzrhm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtmbayltbd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gteweysrsb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.tianlin.xyz/Article/details/gtrpwhghmb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.aibaodan.cn/Article/details/gtcfdwemcl.html

Go:   // 无：用配置结构体参数
来源：http://dali.ehwqpu.com/Article/details/gtkcpkjxpx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxuanxn.top/Article/details/gtutmhuuqk.html

C#:   f(a: 1, b: 2)
来源：http://dali.dianchejie.cn/Article/details/gtmjskonbw.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtmugrtyes.html

Py:   return a, b
来源：http://dali.yj202588.top/Article/details/gtjetalfbd.html

PHP:  return [$a, $b];
来源：http://dali.feifeiyinyue.top/Article/details/gttlgpymuc.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.tanke756.top/Article/details/gtoxrcxqck.html

TS:   return { a, b };
来源：http://dali.shanyushiyangtech.top/Article/details/gtnkbnchxv.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.aizwys.cn/Article/details/gtcliqkuln.html

Go:   return a, b
来源：http://dali.xylfe.cn/Article/details/gthzljerte.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtnkuorjyx.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yj20258888.top/Article/details/gtaolxycwu.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgfzy.top/Article/details/gtnuskrorl.html

Py:   square = lambda x: x * x
来源：http://dali.tanke756.top/Article/details/gtjvhhkbrr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yj20258888.top/Article/details/gtphzzcrix.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtqsoibvze.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.guannengcc.top/Article/details/gtiexdeubp.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.sufxvd.cn/Article/details/gtgbqoudax.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aibaodan.cn/Article/details/gtfjrokeva.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shangyingyoupin.top/Article/details/gtaolizuye.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.aibaodan.cn/Article/details/gtzihzzxjk.html

[C07] 把函数作为参数传入
来源：http://dali.yueranfly.top/Article/details/gtabayfojy.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zhiwuduotai.top/Article/details/gtkcbowlqk.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.svipenyu.cn/Article/details/gtqfmenylc.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtqupquhxg.html

TS:   arr.map(String)
来源：http://dali.yanxiufei.cn/Article/details/gtskzqfpgy.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.sweek.top/Article/details/gtvytfktcg.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yongpay.top/Article/details/gtipbctjem.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhijiandao.cn/Article/details/gtuuatossb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.ppjwa.cn/Article/details/gttpbqdloe.html

[C08] 闭包
来源：http://dali.jiagoushi.top/Article/details/gtechzklni.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.ivvv.top/Article/details/gthgmryqkw.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xylfe.cn/Article/details/gtrjfrtwak.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.bjfxy.top/Article/details/gtlxrtxtxo.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.tianlin.xyz/Article/details/gtxrzyzeco.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdxhowbi.html

Go:   func counter() func() int { n := 0; return func() int { n++; return n } }
来源：http://dali.daria6918.cn/Article/details/gtlzhomwvf.html

Ruby: def counter; n = 0; -> { n += 1 }; end
来源：http://dali.havefunace.top/Article/details/gtfrsxqhcq.html

C#:   static Func<int> Counter() { int n = 0; return () => ++n; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrvqmkic.html

[C09] 递归
来源：http://dali.cashguo.top/Article/details/gtxlecpqxd.html


<!-- 参考信息 -->