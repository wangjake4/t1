代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.mhx1999.top/Article/details/gtwmuwtmzm.html

[A15] 空值判断与默认值
来源：http://dali.gzhubu.top/Article/details/gtcqdawgoo.html

Py:   value = data or "默认值"
来源：http://dali.feifeiyinyue.top/Article/details/gtjrzwniph.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.pycfn.com/Article/details/gtlrtqplbq.html

JS:   const value = data ?? "默认值";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkauolgvy.html

TS:   const value = data ?? "默认值";
来源：http://dali.cqqwz.cn/Article/details/gtyaedvlkf.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.snrcjt.cn/Article/details/gtkokfrgwm.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.aibaodan.cn/Article/details/gtbyapijkt.html

Ruby: value = data || "默认值"
来源：http://dali.jinqigfzy.top/Article/details/gtxqnbdygf.html

C#:   var value = data ?? "默认值";
来源：http://dali.daxiang520.top/Article/details/gtvlcomzxg.html

[A16] 真假值判断规则
来源：http://dali.ehwqpu.com/Article/details/gtqopqtofr.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.chenlongwang.top/Article/details/gtbdysnecs.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xziqi.cn/Article/details/gtfpumakvx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yuanzhike.top/Article/details/gtmkmhuyes.html

TS:   if (!x) {}
来源：http://dali.guowangkeji.top/Article/details/gtusjgkkur.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.aibaodan.cn/Article/details/gtuiwglfuo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xziqi.cn/Article/details/gtebndjblu.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.hysaishi.cn/Article/details/gtekgfaurz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxinkj.top/Article/details/gtqrkhdrtn.html

[A17] 位运算
来源：http://dali.hysaishi.cn/Article/details/gtwgxwsodr.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrthvmakr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.hongshengwenyu.top/Article/details/gtrdtikmir.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtmuiibwew.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtyzqffpbg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtnnhbboka.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtoxacqivw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtdehksekn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.c1oappe.top/Article/details/gtqwnwpeae.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cheryme.top/Article/details/gtbqdersam.html

Py:   ord("A"); chr(65)
来源：http://dali.zhijiandao.cn/Article/details/gteutlfzbz.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtjtaftpns.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dashuyun.cn/Article/details/gtlfybtqgn.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.nwbrower.top/Article/details/gtcvucsnho.html

Java: (int) 'A'; (char) 65
来源：http://dali.yuanzhike.top/Article/details/gtylatpxeb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.0kj1m.cn/Article/details/gtfeltubsd.html

Ruby: "A".ord; 65.chr
来源：http://dali.haohaochexian.top/Article/details/gthllasfrx.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gthfsfhstg.html

[A19] 交换两个变量
来源：http://dali.ehwqpu.com/Article/details/gtadxxmeyu.html

Py:   a, b = b, a
来源：http://dali.hysaishi.cn/Article/details/gtgcqjsmun.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.c1oappe.top/Article/details/gtrxtwgjbn.html

JS:   [a, b] = [b, a];
来源：http://dali.yj20258888.top/Article/details/gtowjrjzit.html

TS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gtmzxftgwp.html

Java: int t = a; a = b; b = t;
来源：http://dali.yuanzhike.top/Article/details/gtrgqfjbsj.html

Go:   a, b = b, a
来源：http://dali.tanke756.top/Article/details/gtcwxrzdeo.html

Ruby: a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtovswhgvd.html

C#:   (a, b) = (b, a);
来源：http://dali.shuidangran.top/Article/details/gtohjoljiv.html

[A20] 读取标准输入
来源：http://dali.guannengcc.top/Article/details/gtrlseqyxn.html

Py:   name = input("请输入：")
来源：http://dali.zhixingplan.top/Article/details/gtdpaggahr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sxryk.cn/Article/details/gtzfjnwcli.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuewkjqxk.html

TS:   // Node.js：readline 模块
来源：http://dali.nanxinkj.top/Article/details/gtdbdjnysm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtcjjgdpqt.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xinyue.icu/Article/details/gtqjxzzijg.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gteepuriuv.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gtcckqqwhu.html

[A21] 保留指定小数位输出
来源：http://dali.mhx1999.top/Article/details/gtnoxblqdg.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinqigfzy.top/Article/details/gtfrazahwm.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.sysykeji.top/Article/details/gttmfdkurd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sysykeji.top/Article/details/gttqeckncn.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zdqjudy.top/Article/details/gtonewxmdg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtewjbuvkn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zycfv.cn/Article/details/gtihbrplmz.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtwyqdzhqp.html

C#:   3.14159.ToString("F2")
来源：http://dali.ydzc1.top/Article/details/gtaqyymigz.html

[A22] 获取字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtpsnradam.html

Py:   len(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtrqcjvltk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pengpengdd.cyou/Article/details/gtcwdlvnkw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aizwys.cn/Article/details/gtodifldnz.html

TS:   s.length
来源：http://dali.sufxvd.cn/Article/details/gtwqqaivqy.html

Java: s.length()
来源：http://dali.9152youxi.cn/Article/details/gteabierzu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shzxlz.cn/Article/details/gtfqwnmjfr.html

Ruby: s.length
来源：http://dali.guannengcc.top/Article/details/gtagvzlgjz.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gtrluzjlrt.html

[A23] 大小写转换
来源：http://dali.chenlongwang.top/Article/details/gtagfyrawm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shangyingyoupin.top/Article/details/gtraqvkubk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.gaohongyu789.top/Article/details/gtaeymjgvv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tianlin.xyz/Article/details/gtwdptlmir.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sweek.top/Article/details/gtzesgqaih.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtkxnduryx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxuanxn.top/Article/details/gtzkusyfmx.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yuxming.cn/Article/details/gtepqfrjki.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gaohongyu789.top/Article/details/gtpxetratz.html

[A24] 去除首尾空白
来源：http://dali.tian-w.cn/Article/details/gtnnucfmyv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hammf.cn/Article/details/gtrnvcptzd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.vqdsnc.cn/Article/details/gtnrjvubeg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhengqikj.top/Article/details/gtzczfpask.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yanxiufei.cn/Article/details/gtpaaeyihq.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.dianchejie.cn/Article/details/gtddervfwp.html

Go:   strings.TrimSpace(s)
来源：http://dali.9152youxi.cn/Article/details/gtumhczemy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuetiantiany.cn/Article/details/gtygbxnmgw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cucudq.cn/Article/details/gtnugikhvm.html

[A25] 字符串比较
来源：http://dali.hammf.cn/Article/details/gtjotantgn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.quarkkingdee.top/Article/details/gtwljejcpe.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.xuanzx.com/Article/details/gthjudyhxy.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtxacpqghc.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ydzc1.top/Article/details/gtgdxzssgd.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtzgkjlaaj.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtoahtqxox.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.quarkkingdee.top/Article/details/gtdxkrzsvo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtllrrobeo.html

[A26] 类型转换总览
来源：http://dali.quarkkingdee.top/Article/details/gtyolevyzq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cdnleiting.top/Article/details/gtihjmqpxn.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenjidiqi.icu/Article/details/gtkpxofnos.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.tianlin.xyz/Article/details/gtvncpcnuh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.sufxvd.cn/Article/details/gtgpsvlpbs.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yj20258888.top/Article/details/gtojdrfnab.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.redwolf501.top/Article/details/gtgpnabuuj.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gtgtseowfl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jiagoushi.top/Article/details/gtcmlxjrgt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzooobdru.html

B. 流程控制
来源：http://dali.feifeiyinyue.top/Article/details/gtibiceveo.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtmmpviwxr.html

[B01] 条件判断 if / else
来源：http://dali.yangfankeji.com/Article/details/gtzjnhbneo.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtntwchfco.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.guannengcc.top/Article/details/gtyekciuhl.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yvedp.cn/Article/details/gtsrfqdrzv.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gtxfcamkpr.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtuacvstan.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jianghu66.top/Article/details/gtdwbwbxty.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.nwbrower.top/Article/details/gtayadmvwj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.xziqi.cn/Article/details/gtnhytejba.html

[B02] 多分支 else if / elif
来源：http://dali.zdqjudy.top/Article/details/gthhcyznht.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hnxiangtu.top/Article/details/gtogjvlxgh.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtakrtwdcy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gtvjqhgniv.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pycfn.com/Article/details/gtttupmmhq.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgufenzy.top/Article/details/gtvzpbavrw.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gthzhcjfug.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.svipenyu.cn/Article/details/gtvbmstdvd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtwghnmuhp.html

[B03] switch / match / case
来源：http://dali.sxryk.cn/Article/details/gtjlladzov.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gtubedxvtf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.yanxiufei.cn/Article/details/gtxlbotamo.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtwrfwphto.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtygmetfdx.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtrzradslj.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gtbdwwwrdm.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gtkaqlcvln.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xinyue.icu/Article/details/gtfrggoipq.html

[B04] for 计数循环
来源：http://dali.shanyushiyangtech.top/Article/details/gtavxkotst.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gtnflravfd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtqvecqxsx.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.9152youxi.cn/Article/details/gtlmyjwfmr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtkftnaxfn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.iojbl.cn/Article/details/gtlghqhtxk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.wangdashe.top/Article/details/gttzbbirwn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.jqgfzy.top/Article/details/gtyzjjnatc.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtozxqsyye.html

[B05] 遍历数组 / 列表
来源：http://dali.xuanzx.com/Article/details/gtqktoozwv.html

Py:   for item in arr: print(item)
来源：http://dali.meibo888.top/Article/details/gtygkmptaq.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yuanzhike.top/Article/details/gtoogafecg.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xziqi.cn/Article/details/gtkxfivicg.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtwuyknxcg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.fzhhl.top/Article/details/gtfjrfklja.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.wangshuangyany.cn/Article/details/gtzivlkclk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtwutjbrcu.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.birdmap.top/Article/details/gtraxeiqza.html

[B06] 遍历字典 / 对象
来源：http://dali.jyoumei.cn/Article/details/gtxalmfrab.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtbhdirdui.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.fengsongda.top/Article/details/gtugaunotp.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gthwpfzrqs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gotoacloud.top/Article/details/gtlcqsncle.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gtjpknuxvt.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.pycfn.com/Article/details/gtoinfxcqe.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.hfpthk.cn/Article/details/gtmfufxbit.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gtufxugwrq.html

[B07] while 循环
来源：http://dali.daxiang520.top/Article/details/gtzrutagrb.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtgdjrgkba.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.dashuyun.cn/Article/details/gtvcjnobon.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gteonddepv.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gthsdghgzj.html

Java: while (i < 10) { i++; }
来源：http://dali.fzhhl.top/Article/details/gtsvymvmkj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hysaishi.cn/Article/details/gtoldbaxxs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cashguo.top/Article/details/gtjexewwmt.html

C#:   while (i < 10) { i++; }
来源：http://dali.ivvv.top/Article/details/gtnrtkzxrh.html

[B08] do-while（至少执行一次）
来源：http://dali.yuanzhike.top/Article/details/gtqagbjjaw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.meibo888.top/Article/details/gtjnsjufxd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgfzy.top/Article/details/gtywtpwzbf.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xinyue.icu/Article/details/gtlyifzwec.html

TS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtrzmuckvd.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtnrqccnpn.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.zdqjudy.top/Article/details/gtnxkkgwsv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gtymukakvp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtktvzmplk.html

[B09] break 与 continue
来源：http://dali.snrcjt.cn/Article/details/gtpzdbhvuv.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.zhijiandao.cn/Article/details/gtqllnlxiu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.nwbrower.top/Article/details/gtdysfxskt.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtiryqdqbd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtcrspwcry.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtpzkawngi.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.daria6918.cn/Article/details/gtdsndzhij.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zhongyouzk.top/Article/details/gtanpaukye.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cdnleiting.top/Article/details/gtbhrziiho.html

[B10] 遍历同时拿索引
来源：http://dali.havefunace.top/Article/details/gtcjaiqvyt.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtjezrcqaa.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ivvv.top/Article/details/gtnzpkwokf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.haohaochexian.top/Article/details/gtcctckqdw.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.daxiang520.top/Article/details/gtvatbmpun.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.quarkkingdee.top/Article/details/gtlhgifokp.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.redwolf501.top/Article/details/gtzgiazqba.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtnitllwri.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.meibo888.top/Article/details/gtzbfpbkip.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtyovmlowm.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gtfftylite.html

PHP:  range(0, 10, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtcuikwjvi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.bjfxy.top/Article/details/gtxgfdxoyz.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ybcxt.top/Article/details/gtouuiglit.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.sysykeji.top/Article/details/gtaidfytsw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sweek.top/Article/details/gtsgoemsum.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gtfpsvyntw.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.quarkkingdee.top/Article/details/gtykybphkw.html

[B12] 跳出多层循环
来源：http://dali.ybcxt.top/Article/details/gtuovmketm.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbgrpcujm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jlsjyb.cn/Article/details/gtyiqxiovk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuanzhike.top/Article/details/gtcpixlvbf.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nanxinkj.top/Article/details/gtztscqvqs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtscznypgl.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gzhubu.top/Article/details/gthvbpenqg.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.haohaochexian.top/Article/details/gtjncjzfgg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sufxvd.cn/Article/details/gtputbbafy.html

[B13] 判断是否为数字
来源：http://dali.andypj.xyz/Article/details/gtyogomlvz.html

Py:   isinstance(x, (int, float))
来源：http://dali.svipenyu.cn/Article/details/gtdvtddyeg.html

PHP:  is_numeric($x)
来源：http://dali.sysykeji.top/Article/details/gtzgcldrkz.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhoulong.xyz/Article/details/gtxxodpqnc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvcpovcai.html

Java: x instanceof Number
来源：http://dali.c1oappe.top/Article/details/gtcdjnvkzl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jinqigufen.top/Article/details/gtisivsmsu.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yj20258888.top/Article/details/gtbugavhbm.html

C#:   x is int or double or decimal
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkdokofhi.html

[B14] 判断值是否在集合内
来源：http://dali.guowangkeji.top/Article/details/gtpirmeobm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xziqi.cn/Article/details/gtxhnwcaum.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.smart0.xyz/Article/details/gtjcwieyzw.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtqwqwggcl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtnapvanot.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.ydzc1.top/Article/details/gtcxmrolir.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hammf.cn/Article/details/gtbhvscqxg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yangfankeji.com/Article/details/gtdxastrfh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtarijvngi.html

[B15] 布尔运算与取反
来源：http://dali.yueranfly.top/Article/details/gtsxoykovk.html

Py:   a and b or not c
来源：http://dali.yangfankeji.com/Article/details/gtswhgzzef.html

PHP:  $a && $b || !$c
来源：http://dali.kuanghao11.cn/Article/details/gtlzyqoreg.html

JS:   a && b || !c
来源：http://dali.cheryme.top/Article/details/gtseytnqji.html

TS:   a && b || !c
来源：http://dali.jinqigufen.top/Article/details/gthlcwmyro.html

Java: a && b || !c
来源：http://dali.jlsjyb.cn/Article/details/gtmlznpihy.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtpndmkoch.html

Ruby: a && b || !c
来源：http://dali.meibo888.top/Article/details/gtuqixpowy.html

C#:   a && b || !c
来源：http://dali.shuidangran.top/Article/details/gttdfnuwkh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.9152youxi.cn/Article/details/gtkhhjiiur.html

Py:   if not data: return
来源：http://dali.quarkkingdee.top/Article/details/gtjigmzwhl.html

PHP:  if (!$data) { return; }
来源：http://dali.xylfe.cn/Article/details/gtelohnkik.html

JS:   if (!data) return;
来源：http://dali.yj20258.top/Article/details/gtfjsfqcxb.html

TS:   if (!data) return;
来源：http://dali.chenlongwang.top/Article/details/gtyuoeedbf.html

Java: if (data == null) return;
来源：http://dali.nwbrower.top/Article/details/gtvijngpwh.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtvlmnyafm.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtypopyyjp.html

C#:   if (data == null) return;
来源：http://dali.daria6918.cn/Article/details/gtpgweaqkw.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtlgmitstf.html

C. 函数与作用域
来源：http://dali.cucudq.cn/Article/details/gtwnawnzna.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvyvxhrnw.html

[C01] 定义函数
来源：http://dali.yonumen.top/Article/details/gtfvdinmrx.html

Py:   def add(a, b): return a + b
来源：http://dali.chenlongwang.top/Article/details/gtgnvwfccx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gthxbzxxds.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtqdwnbxww.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.chenzaomai.com/Article/details/gtdyfqvbuj.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtmcaclzwc.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.hysaishi.cn/Article/details/gtpbxhwgpq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gtlfozxfcs.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtrrozebfk.html

[C02] 默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtcsymrmmz.html

Py:   def greet(name="World"): return name
来源：http://dali.xylfe.cn/Article/details/gtbeihrtbq.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtwqqkhgzm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtirrmezvm.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtdvqbtmyr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopdqcrjm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hnxiangtu.top/Article/details/gtgznxyzva.html

Ruby: def greet(name = "World") = name
来源：http://dali.birdmap.top/Article/details/gtynuvpamb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.9152youxi.cn/Article/details/gtmaaeaznv.html

[C03] 可变参数
来源：http://dali.fengsongda.top/Article/details/gtqxrhlden.html

Py:   def total(*args): return sum(args)
来源：http://dali.hnxiangtu.top/Article/details/gtspozzsnz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzwtvgrg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.nanxuanxn.top/Article/details/gtfdsrswyr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gotoacloud.top/Article/details/gtbjnoekzu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.guannengcc.top/Article/details/gtvgcaqyap.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yongpay.top/Article/details/gtdgfvllfu.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.jqgfzy.top/Article/details/gtjpiwewnn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.zhengqikj.top/Article/details/gtaukipwmk.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtxqygekfu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.havefunace.top/Article/details/gtyberrioz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtpplnrwjv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.tian-w.cn/Article/details/gtjcltnifa.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtbabulkbl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hfpthk.cn/Article/details/gtadducbrs.html

Go:   // 无：用配置结构体参数
来源：http://dali.feifeiyinyue.top/Article/details/gtxwwsmjey.html

Ruby: f(a: 1, b: 2)
来源：http://dali.haohaochexian.top/Article/details/gtwxyzoqnm.html

C#:   f(a: 1, b: 2)
来源：http://dali.bjfxy.top/Article/details/gthgyftpqf.html

[C05] 返回多个值
来源：http://dali.jiagoushi.top/Article/details/gtzrdabgrw.html

Py:   return a, b
来源：http://dali.jinqigufen.top/Article/details/gtalxqebum.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonmsondm.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtojuowvut.html

TS:   return { a, b };
来源：http://dali.jqgfzy.top/Article/details/gtkcoaxqck.html


<!-- 参考信息 -->