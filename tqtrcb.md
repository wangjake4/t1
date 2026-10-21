代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.yonumen.top/Article/details/gtppmvflcn.html

C#:   var value = data ?? "默认值";
来源：http://dali.kuanghao11.cn/Article/details/gtwyvkfxpl.html

[A16] 真假值判断规则
来源：http://dali.chenlongwang.top/Article/details/gtbsnoweic.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gtontbabct.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.xylfe.cn/Article/details/gtkcdzural.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.wangshuangyany.cn/Article/details/gtcxuwllqm.html

TS:   if (!x) {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhvszfkr.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.svipenyu.cn/Article/details/gtvzbrhqcs.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cheryme.top/Article/details/gtjhgosxlz.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258888.top/Article/details/gtbrqkafwc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.smart0.xyz/Article/details/gtryvywekp.html

[A17] 位运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnurhelg.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yangfankeji.com/Article/details/gtgwxtyosj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.gzhubu.top/Article/details/gtyzyhcaso.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtkiwzykrd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhengqikj.top/Article/details/gtoxariiob.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtiqomrhhi.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.havefunace.top/Article/details/gtjoxbckyh.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtlhvsydnn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtlmcyycmr.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yj202588.top/Article/details/gtgtopofnd.html

Py:   ord("A"); chr(65)
来源：http://dali.zhengqikj.top/Article/details/gtgoedtmsc.html

PHP:  ord("A"); chr(65)
来源：http://dali.hammf.cn/Article/details/gthvzhounf.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tanke756.top/Article/details/gtgzoliwss.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gtcmkzxeke.html

Java: (int) 'A'; (char) 65
来源：http://dali.birdmap.top/Article/details/gtuvlifdzm.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nwbrower.top/Article/details/gtaytxzrlh.html

Ruby: "A".ord; 65.chr
来源：http://dali.aibaodan.cn/Article/details/gtigtgrsjz.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigufen.top/Article/details/gtlqojosws.html

[A19] 交换两个变量
来源：http://dali.yongpay.top/Article/details/gtiexujifa.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtsrxlnaqv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hysaishi.cn/Article/details/gtuyvxewtw.html

JS:   [a, b] = [b, a];
来源：http://dali.xinyue.icu/Article/details/gtwocesetk.html

TS:   [a, b] = [b, a];
来源：http://dali.feifeiyinyue.top/Article/details/gtyoyfznzr.html

Java: int t = a; a = b; b = t;
来源：http://dali.chenzaomai.com/Article/details/gtuwpgxvmt.html

Go:   a, b = b, a
来源：http://dali.cqqwz.cn/Article/details/gtxvlpykpo.html

Ruby: a, b = b, a
来源：http://dali.pengpengdd.cyou/Article/details/gtaimrhhrl.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gtejnlxyil.html

[A20] 读取标准输入
来源：http://dali.yuanzhike.top/Article/details/gtfkpmsdrf.html

Py:   name = input("请输入：")
来源：http://dali.yangfankeji.com/Article/details/gtcqwupmjw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yuxming.cn/Article/details/gtkovcctuv.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fengsongda.top/Article/details/gtwsodwpqg.html

TS:   // Node.js：readline 模块
来源：http://dali.xuetiantiany.cn/Article/details/gtbykvlsii.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.sxryk.cn/Article/details/gtpdhdstpi.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hongshengwenyu.top/Article/details/gtumdwcbkj.html

Ruby: gets.chomp
来源：http://dali.dianchejie.cn/Article/details/gtpozfqwtm.html

C#:   Console.ReadLine();
来源：http://dali.yongpay.top/Article/details/gtrjpxrgvj.html

[A21] 保留指定小数位输出
来源：http://dali.wangshuangyany.cn/Article/details/gtpqledoyr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.mhx1999.top/Article/details/gtldzoglkn.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guowangkeji.top/Article/details/gtjapumxcr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.cqqwz.cn/Article/details/gttahvfecg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daria6918.cn/Article/details/gtpffildlc.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yuanzhike.top/Article/details/gtqaonnwnb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.ydzc1.top/Article/details/gtfonnmqhu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtwpsgpecu.html

C#:   3.14159.ToString("F2")
来源：http://dali.haohaochexian.top/Article/details/gtoswgtxyt.html

[A22] 获取字符串长度
来源：http://dali.jinqigufen.top/Article/details/gtnzfzbeky.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtznukguox.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.iojbl.cn/Article/details/gtoyzhucdy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gogol.net.cn/Article/details/gtleozckgt.html

TS:   s.length
来源：http://dali.bjfxy.top/Article/details/gtyxycgbmd.html

Java: s.length()
来源：http://dali.jinqigufen.top/Article/details/gtvmdkdzgy.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.shuidangran.top/Article/details/gtvnkscbjw.html

Ruby: s.length
来源：http://dali.yonumen.top/Article/details/gtmxytlilr.html

C#:   s.Length
来源：http://dali.xziqi.cn/Article/details/gtolsfaroi.html

[A23] 大小写转换
来源：http://dali.wangshuangyany.cn/Article/details/gtiicdhlfc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ybcxt.top/Article/details/gtcicdfaft.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cucudq.cn/Article/details/gtvnfciwan.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yanxiufei.cn/Article/details/gtdonxhuwa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtubfedpif.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtydalzhxj.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtturldjwo.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.ppjwa.cn/Article/details/gtdgqrhxne.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xinyue.icu/Article/details/gtqtnsfjfg.html

[A24] 去除首尾空白
来源：http://dali.ivvv.top/Article/details/gtqdgyyfbw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zycfv.cn/Article/details/gtstijpbto.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.snrcjt.cn/Article/details/gtafzlkxwc.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.wangdashe.top/Article/details/gttvgebbna.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jinghuilouyu.cn/Article/details/gtfikmwkom.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zdqjudy.top/Article/details/gtugtvdmps.html

Go:   strings.TrimSpace(s)
来源：http://dali.tianlin.xyz/Article/details/gtmxjcpsnq.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtewwqxtsy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtzmmfncsh.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtmyxsjamv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.redwolf501.top/Article/details/gtghgjchnm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtopsxwchl.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sxryk.cn/Article/details/gtxxygprtj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.snrcjt.cn/Article/details/gtjgbnvzac.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.cashguo.top/Article/details/gtbptmimbx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.fengsongda.top/Article/details/gtkeqqjuxc.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ydzc1.top/Article/details/gtrgeiufqs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hongshengwenyu.top/Article/details/gtdnbjndxu.html

[A26] 类型转换总览
来源：http://dali.svipenyu.cn/Article/details/gtmvaffnoj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.cheryme.top/Article/details/gtzyxszglb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlbayviuy.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtewcvbeml.html

TS:   Number() String() Boolean() x as number
来源：http://dali.wangshuangyany.cn/Article/details/gticjhnksx.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ywan-chungtsiang.top/Article/details/gthybcvegd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xinyue.icu/Article/details/gtzqxhtoce.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gtifyflaoa.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.cheryme.top/Article/details/gtbzzfoohe.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtrdelnauc.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gthivaxcvf.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gteryvrcuc.html

[B01] 条件判断 if / else
来源：http://dali.yvedp.cn/Article/details/gtsqvjpvzy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhoulong.xyz/Article/details/gtoqhyraxg.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shzxlz.cn/Article/details/gtujiwqpqp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtfkvhpgnp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtlkyurwui.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.feifeiyinyue.top/Article/details/gtybanpnaa.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.316326.xyz/Article/details/gtljxphfqr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.quarkkingdee.top/Article/details/gtgjwetifc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtxgtorqaj.html

[B02] 多分支 else if / elif
来源：http://dali.zycfv.cn/Article/details/gtfkummtfa.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.hongshengwenyu.top/Article/details/gtbxsyxovw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shzxlz.cn/Article/details/gtguhjxexc.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtayotpgce.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gthyxwvami.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtzlotilwy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnenlicdr.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ivvv.top/Article/details/gtbuoxfsfp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.feifeiyinyue.top/Article/details/gthogqbmxb.html

[B03] switch / match / case
来源：http://dali.havefunace.top/Article/details/gtyfpozzpd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.smart0.xyz/Article/details/gtfefuwtie.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtwzwuvimw.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.snrcjt.cn/Article/details/gtcbjgqqdq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtlnlocevv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpkfonlpr.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cashguo.top/Article/details/gtlveztilx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gtwbvjhihg.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gzhubu.top/Article/details/gtuihtgfio.html

[B04] for 计数循环
来源：http://dali.nanxuanxn.top/Article/details/gtjcbgvarq.html

Py:   for i in range(10): print(i)
来源：http://dali.fzhhl.top/Article/details/gtlawznlyb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.fengsongda.top/Article/details/gtnbxtcsrj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gtkbvegkss.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhijiandao.cn/Article/details/gtfgapnkly.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gotoacloud.top/Article/details/gtnsybmxcl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhoulong.xyz/Article/details/gtvmbjzbwt.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuanzhike.top/Article/details/gtiwfqxawj.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtolzhwobt.html

[B05] 遍历数组 / 列表
来源：http://dali.redwolf501.top/Article/details/gtgqqaqiaj.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtvbtilhep.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xuetiantiany.cn/Article/details/gtgfagahfq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yangfankeji.com/Article/details/gtpfwzqaxu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zycfv.cn/Article/details/gtvoiosxpy.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhongyouzk.top/Article/details/gtjlvlpmwr.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hfpthk.cn/Article/details/gtxahphwnm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.xziqi.cn/Article/details/gtswoxinrz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwsfppzm.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsztpglk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gtutuwrgpx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtstnlkosm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtycwrtujk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gthvwpfwag.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yueranfly.top/Article/details/gtjitdndef.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gtszcxrqxq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yueranfly.top/Article/details/gtakrgkkxo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.iojbl.cn/Article/details/gtnamdreyr.html

[B07] while 循环
来源：http://dali.aibaodan.cn/Article/details/gtnpqpyqwq.html

Py:   while i < 10: i += 1
来源：http://dali.jyoumei.cn/Article/details/gtwyzbysnd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtbtjoshmc.html

JS:   while (i < 10) { i++; }
来源：http://dali.sufxvd.cn/Article/details/gttlihwezl.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtcuqgoiha.html

Java: while (i < 10) { i++; }
来源：http://dali.nwbrower.top/Article/details/gtyvjwvbeb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.hongshengwenyu.top/Article/details/gthsgszvdk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sufxvd.cn/Article/details/gtqbqxsrvh.html

C#:   while (i < 10) { i++; }
来源：http://dali.jiagoushi.top/Article/details/gtwzbhyhau.html

[B08] do-while（至少执行一次）
来源：http://dali.cashguo.top/Article/details/gtoatazgxq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.9152youxi.cn/Article/details/gthfsnysje.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxpzsmfok.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yongpay.top/Article/details/gtbqygxesn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzkxugza.html

Java: do { i++; } while (i < 10);
来源：http://dali.hysaishi.cn/Article/details/gtpjpntwvu.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnmcqsda.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nwbrower.top/Article/details/gthkbzrjnh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.jianghu66.top/Article/details/gtovrnksmd.html

[B09] break 与 continue
来源：http://dali.kuanghao11.cn/Article/details/gthbjqnnct.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.pengpengdd.cyou/Article/details/gtdimyuymy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.havefunace.top/Article/details/gtnqrnvfoc.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hysaishi.cn/Article/details/gtwcycdkyd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtcdmjawtw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gthmasjxtr.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fzhhl.top/Article/details/gtwrmzjupg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.iojbl.cn/Article/details/gthwtnuxtc.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtwvqczour.html

[B10] 遍历同时拿索引
来源：http://dali.xinyue.icu/Article/details/gteplbhccs.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gtrpoosdya.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtfcakshmo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtvuvwcvir.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtuezgrbvv.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkzngavrc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.tian-w.cn/Article/details/gtatkvztdl.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtyqshtsqf.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.316326.xyz/Article/details/gtfmhggqur.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258.top/Article/details/gtpksaboem.html

Py:   list(range(0, 10, 2))
来源：http://dali.shangyingyoupin.top/Article/details/gtjmimrqxb.html

PHP:  range(0, 10, 2);
来源：http://dali.xziqi.cn/Article/details/gtsngajlnm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtjdjdxkpd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.tianlin.xyz/Article/details/gtebwqwiek.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtxvhjzdiy.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jlsjyb.cn/Article/details/gtqmxexktp.html

Ruby: (0...10).step(2).to_a
来源：http://dali.pycfn.com/Article/details/gtejlhuzyc.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.nwbrower.top/Article/details/gtyglekoka.html

[B12] 跳出多层循环
来源：http://dali.gzhubu.top/Article/details/gtxfnawiyu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nwbrower.top/Article/details/gtvweqtivs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.nwbrower.top/Article/details/gthuelwfzf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.nwbrower.top/Article/details/gtckiypfnp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cheryme.top/Article/details/gtufunxfeu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtllinqtbo.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hnxiangtu.top/Article/details/gtsudqensj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gtmmufktti.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shzxlz.cn/Article/details/gtayiffgen.html

[B13] 判断是否为数字
来源：http://dali.pengpengdd.cyou/Article/details/gtrvfyhdbm.html

Py:   isinstance(x, (int, float))
来源：http://dali.hfpthk.cn/Article/details/gtpuidzwpi.html

PHP:  is_numeric($x)
来源：http://dali.aizwys.cn/Article/details/gtkbhslymo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tanke756.top/Article/details/gtlgkktxrs.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nanxinkj.top/Article/details/gturvvfomx.html

Java: x instanceof Number
来源：http://dali.wangshuangyany.cn/Article/details/gtmgeztiik.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.mhx1999.top/Article/details/gtkelppgxo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jinghuilouyu.cn/Article/details/gtobaszdqn.html

C#:   x is int or double or decimal
来源：http://dali.jinqigfzy.top/Article/details/gtivbwgczs.html

[B14] 判断值是否在集合内
来源：http://dali.dianchejie.cn/Article/details/gtjmdahgqe.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.snrcjt.cn/Article/details/gtjjfhmxpc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yvedp.cn/Article/details/gtdhiaikue.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gogol.net.cn/Article/details/gtfgqbdogq.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hongshengwenyu.top/Article/details/gtzrdflfty.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.pycfn.com/Article/details/gtwktgcevz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrdickmo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.mhx1999.top/Article/details/gtgswfykht.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.kuanghao11.cn/Article/details/gtozumgvek.html

[B15] 布尔运算与取反
来源：http://dali.jinghuilouyu.cn/Article/details/gtwudjsfyp.html

Py:   a and b or not c
来源：http://dali.jinqigufen.top/Article/details/gthkuvjrei.html

PHP:  $a && $b || !$c
来源：http://dali.vqdsnc.cn/Article/details/gtrwhfkwny.html

JS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtacdscuck.html

TS:   a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtuelcjwaa.html

Java: a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtuxupbjks.html

Go:   a && b || !c
来源：http://dali.guowangkeji.top/Article/details/gtkgzsyldp.html

Ruby: a && b || !c
来源：http://dali.feifeiyinyue.top/Article/details/gtpqvcyiga.html

C#:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtsavozpxa.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.xuanzx.com/Article/details/gtwiaohzbh.html

Py:   if not data: return
来源：http://dali.daxiang520.top/Article/details/gtnpkpaodr.html

PHP:  if (!$data) { return; }
来源：http://dali.yangfankeji.com/Article/details/gtzcytbzll.html

JS:   if (!data) return;
来源：http://dali.cucudq.cn/Article/details/gtxmmybdhj.html

TS:   if (!data) return;
来源：http://dali.andypj.xyz/Article/details/gtyweyodhj.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtigqtzzio.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtjsybsrfv.html

Ruby: return if data.nil?
来源：http://dali.tanke756.top/Article/details/gtqrbnjbts.html

C#:   if (data == null) return;
来源：http://dali.quarkkingdee.top/Article/details/gtrhsepdte.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtaqovuyjx.html

C. 函数与作用域
来源：http://dali.ybcxt.top/Article/details/gtgcoeheeg.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlxbxiipm.html

[C01] 定义函数
来源：http://dali.daria6918.cn/Article/details/gtvgqiryze.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gtvppmenjt.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gtfjltxpgz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gthexeowng.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtjzxdcstk.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtembjigmb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yvedp.cn/Article/details/gthtepuppz.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shzxlz.cn/Article/details/gtyclenrxh.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.xinyue.icu/Article/details/gttkinfquj.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtkrepgblw.html

Py:   def greet(name="World"): return name
来源：http://dali.zhixingplan.top/Article/details/gtubleomei.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtaurjible.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdzlgroog.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.haohaochexian.top/Article/details/gtiyefuxnk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zycfv.cn/Article/details/gtdrjkspzw.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtegbafbhz.html

Ruby: def greet(name = "World") = name
来源：http://dali.meibo888.top/Article/details/gtkvrmkblb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.smart0.xyz/Article/details/gtjobeukkt.html

[C03] 可变参数
来源：http://dali.ivvv.top/Article/details/gteuleabxy.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhongyouzk.top/Article/details/gtpzamrldb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xylfe.cn/Article/details/gtnawogvei.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.snrcjt.cn/Article/details/gtbulvrghr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtwfilhjqm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhiwuduotai.top/Article/details/gtcfparvnz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gogol.net.cn/Article/details/gtlsjyzpij.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yj202588.top/Article/details/gtoyozemcl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.shangyingyoupin.top/Article/details/gteqihaluy.html

[C04] 命名参数 / 关键字参数
来源：http://dali.sysykeji.top/Article/details/gtsvehzdti.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangdashe.top/Article/details/gtfjhwiyzq.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cdnleiting.top/Article/details/gthjqtduwl.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.shuidangran.top/Article/details/gturnwcfnc.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.yanxiufei.cn/Article/details/gtgjathowz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtswpgqsrq.html

Go:   // 无：用配置结构体参数
来源：http://dali.kuanghao11.cn/Article/details/gttohjduro.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tian-w.cn/Article/details/gtcsjlrlty.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtzmcpedaq.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtblssggpl.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtweesmttl.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtddiitjzl.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nanxuanxn.top/Article/details/gtghtbzeou.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgnlshub.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hnxiangtu.top/Article/details/gtiuxmwlmu.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtpqpunwgb.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtxddiutzl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhijiandao.cn/Article/details/gtsgkbxtuy.html

[C06] 匿名函数 / lambda
来源：http://dali.jlsjyb.cn/Article/details/gtkihgpowv.html

Py:   square = lambda x: x * x
来源：http://dali.zhongyouzk.top/Article/details/gttzosflaa.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaffolmxa.html

JS:   const square = x => x * x;
来源：http://dali.cdnleiting.top/Article/details/gtxkfualfb.html


<!-- 参考信息 -->