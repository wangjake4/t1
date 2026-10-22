代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.zhongyouzk.top/Article/details/gtoatqhdbh.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.sysykeji.top/Article/details/gtcqllhjxe.html

Go:   // 单行；/* 多行 */
来源：http://dali.zycfv.cn/Article/details/gtvspjntet.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.tianlin.xyz/Article/details/gtdzhsmwnz.html

C#:   // 单行；/* 多行 */
来源：http://dali.daxiang520.top/Article/details/gtambftofz.html

[A15] 空值判断与默认值
来源：http://dali.nanxinkj.top/Article/details/gtwpdexdzm.html

Py:   value = data or "默认值"
来源：http://dali.daxiang520.top/Article/details/gtvtfdfrwk.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnhcxegk.html

JS:   const value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtjduvyflr.html

TS:   const value = data ?? "默认值";
来源：http://dali.yj202588.top/Article/details/gtbhkqcruk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nanxinkj.top/Article/details/gtvnyjyndi.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.vqdsnc.cn/Article/details/gtklgndcul.html

Ruby: value = data || "默认值"
来源：http://dali.quarkkingdee.top/Article/details/gtpxtcxlhd.html

C#:   var value = data ?? "默认值";
来源：http://dali.shangyingyoupin.top/Article/details/gtjwlncyub.html

[A16] 真假值判断规则
来源：http://dali.daxiang520.top/Article/details/gtvjxqcfoq.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gtukqmyvpw.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dashuyun.cn/Article/details/gterekhxug.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.quarkkingdee.top/Article/details/gtplrwkhsw.html

TS:   if (!x) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtuxxctrkf.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.gotoacloud.top/Article/details/gtrioapzhf.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.cheryme.top/Article/details/gthujovzlq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yuanzhike.top/Article/details/gtjapmbusc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtyvwsjxul.html

[A17] 位运算
来源：http://dali.ivvv.top/Article/details/gtzfbvnewp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtkvbbdwof.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.sweek.top/Article/details/gtgdysnqcd.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtsyjqamcp.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtwzqhkdyy.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcpedcrhh.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtrldlafel.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtdeheskyg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtizrrnler.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dianchejie.cn/Article/details/gtlakejhcv.html

Py:   ord("A"); chr(65)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtebbjtigr.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gtfbunkkoc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.dianchejie.cn/Article/details/gtciyqbkbd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gotoacloud.top/Article/details/gtqhlbzjug.html

Java: (int) 'A'; (char) 65
来源：http://dali.ybcxt.top/Article/details/gtlsaaujph.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yvedp.cn/Article/details/gttwuwgpth.html

Ruby: "A".ord; 65.chr
来源：http://dali.hfpthk.cn/Article/details/gtclijpeyv.html

C#:   (int)'A'; (char)65
来源：http://dali.hongshengwenyu.top/Article/details/gtjvzdoebn.html

[A19] 交换两个变量
来源：http://dali.jlsjyb.cn/Article/details/gtkrovsfzu.html

Py:   a, b = b, a
来源：http://dali.haohaochexian.top/Article/details/gtypldcvbf.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dianchejie.cn/Article/details/gtgpziblal.html

JS:   [a, b] = [b, a];
来源：http://dali.yonumen.top/Article/details/gtrnzobeox.html

TS:   [a, b] = [b, a];
来源：http://dali.meibo888.top/Article/details/gtsegpvjez.html

Java: int t = a; a = b; b = t;
来源：http://dali.xinyue.icu/Article/details/gtzfcnwwbf.html

Go:   a, b = b, a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpogkcjt.html

Ruby: a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtpftwxegy.html

C#:   (a, b) = (b, a);
来源：http://dali.nwbrower.top/Article/details/gtohfuoica.html

[A20] 读取标准输入
来源：http://dali.zhongyouzk.top/Article/details/gtvqonhmgb.html

Py:   name = input("请输入：")
来源：http://dali.nanxuanxn.top/Article/details/gtrreummcw.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yonumen.top/Article/details/gtzbxrhcay.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.kuanghao11.cn/Article/details/gtcebtfnfr.html

TS:   // Node.js：readline 模块
来源：http://dali.daxiang520.top/Article/details/gtahglrjro.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hysaishi.cn/Article/details/gtgvasfvye.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.gzhubu.top/Article/details/gtdckwbbah.html

Ruby: gets.chomp
来源：http://dali.hywenlv.cn/Article/details/gtpuhuprgo.html

C#:   Console.ReadLine();
来源：http://dali.daria6918.cn/Article/details/gtvvdwkejr.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtqxrxegpn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.vqdsnc.cn/Article/details/gtltssmuil.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ppjwa.cn/Article/details/gtestyuekq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.sweek.top/Article/details/gterteknbq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.9152youxi.cn/Article/details/gtxqjvbmtb.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtjnehebnq.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.shzxlz.cn/Article/details/gtjlxgpfjb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yvedp.cn/Article/details/gtfttdgdrd.html

C#:   3.14159.ToString("F2")
来源：http://dali.smart0.xyz/Article/details/gtqvhennoj.html

[A22] 获取字符串长度
来源：http://dali.ivvv.top/Article/details/gtwgbftzox.html

Py:   len(s)
来源：http://dali.jqgfzy.top/Article/details/gtepuqttum.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shuidangran.top/Article/details/gtgdtisyia.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sysykeji.top/Article/details/gtoqibxsxs.html

TS:   s.length
来源：http://dali.yvedp.cn/Article/details/gtgtmqjnnu.html

Java: s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtucbhsoye.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jqgufenzy.top/Article/details/gtqssqyilq.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtcrlwkdon.html

C#:   s.Length
来源：http://dali.cheryme.top/Article/details/gtknkzfdau.html

[A23] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtbolvkwyh.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jyoumei.cn/Article/details/gtpsiitqyp.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.fengsongda.top/Article/details/gtqytoyogt.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jianghu66.top/Article/details/gtgfmowiaq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtxectfjzh.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtkgepfhvy.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtucrjqjtb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.shzxlz.cn/Article/details/gtzepbajmd.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yueranfly.top/Article/details/gtcddkmxdh.html

[A24] 去除首尾空白
来源：http://dali.guannengcc.top/Article/details/gtkiliugyq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.gogol.net.cn/Article/details/gtedujcmjo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xylfe.cn/Article/details/gtozdgebei.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtrqwtsmuv.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.vqdsnc.cn/Article/details/gtcqltnyis.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daria6918.cn/Article/details/gtacgoxljn.html

Go:   strings.TrimSpace(s)
来源：http://dali.hnxiangtu.top/Article/details/gtltqycrio.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gtxotwuasd.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.chenlongwang.top/Article/details/gtjnqoofsa.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gthxslxodv.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jqgufenzy.top/Article/details/gtkdnnvlqw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gtrknogefe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtssuzwsns.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sufxvd.cn/Article/details/gtxmxqksfo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.chenzaomai.com/Article/details/gteelbsltk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guannengcc.top/Article/details/gtugnpodvr.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.wangshuangyany.cn/Article/details/gttjgzdjvo.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jqgfzy.top/Article/details/gttzjrlzto.html

[A26] 类型转换总览
来源：http://dali.hnqzz.top/Article/details/gtkfhijhuq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.gotoacloud.top/Article/details/gtclixjzir.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.svipenyu.cn/Article/details/gtnlfzvnqm.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.haohaochexian.top/Article/details/gtxwcrhadx.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yvedp.cn/Article/details/gtmcpyolgj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.pengpengdd.cyou/Article/details/gtrrujpktn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hfpthk.cn/Article/details/gtcqbzyryd.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.sweek.top/Article/details/gtwjaafekx.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj20258.top/Article/details/gtuzpixpqa.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtznsvjfpa.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gtwkkwqdin.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtypdywrls.html

[B01] 条件判断 if / else
来源：http://dali.havefunace.top/Article/details/gtpmjswlbr.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gtcohzmfrb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrugrxkh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jinqigfzy.top/Article/details/gtkvenaccj.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenjidiqi.icu/Article/details/gtpchkvzqy.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtpxdqxqhw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.9152youxi.cn/Article/details/gtvorxkgde.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aizwys.cn/Article/details/gtfvsftrcg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtwdlbjthg.html

[B02] 多分支 else if / elif
来源：http://dali.dianchejie.cn/Article/details/gtxwxxihga.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gtqefswgaa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zycfv.cn/Article/details/gtpfggptez.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhijiandao.cn/Article/details/gtyusaozxu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gttcqlnmvc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtbysxrgkn.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jiagoushi.top/Article/details/gtnpyhrlcv.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.jinqigfzy.top/Article/details/gtuylvxqfo.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtklvktgyd.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtwgzriqbt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ivvv.top/Article/details/gtflmbyova.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnbxzfupg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cheryme.top/Article/details/gtprhyfnjb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtmqlylfbz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.yongpay.top/Article/details/gtviiiqbts.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.zycfv.cn/Article/details/gtzwlbgezl.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj202588.top/Article/details/gtmrwvchys.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.ydzc1.top/Article/details/gtuunagqne.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtazboeycz.html

Py:   for i in range(10): print(i)
来源：http://dali.yj20258.top/Article/details/gtbjiwmhjg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hammf.cn/Article/details/gtmojyyxxg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gtrcrpduoh.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtsgxnddva.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtsixhwwfr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgemodidv.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ivvv.top/Article/details/gtcbnutweu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.chenjidiqi.icu/Article/details/gtycarboxc.html

[B05] 遍历数组 / 列表
来源：http://dali.cheryme.top/Article/details/gtlmsxbnmv.html

Py:   for item in arr: print(item)
来源：http://dali.chenzaomai.com/Article/details/gttewhrglv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yvedp.cn/Article/details/gtaptwzlup.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.nwbrower.top/Article/details/gtzhsverth.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtzdtaqgav.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.ehwqpu.com/Article/details/gtaixxplyl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.aibaodan.cn/Article/details/gtuiwracep.html

Ruby: arr.each { |item| puts item }
来源：http://dali.fengsongda.top/Article/details/gtyuowcpin.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxdtiaqei.html

[B06] 遍历字典 / 对象
来源：http://dali.shanyushiyangtech.top/Article/details/gtqhgebbls.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.tanke756.top/Article/details/gttsegasjo.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtfielgdnr.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.haohaochexian.top/Article/details/gtvbgxklgo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtasdygkru.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.birdmap.top/Article/details/gtecpckpex.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.jiagoushi.top/Article/details/gtsachpnuw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.feifeiyinyue.top/Article/details/gtldkxgixd.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gtofzeozdl.html

[B07] while 循环
来源：http://dali.hywenlv.cn/Article/details/gtdqbrgepr.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtoehkibaa.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.0kj1m.cn/Article/details/gtadcjvnuz.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimzimtul.html

TS:   while (i < 10) { i++; }
来源：http://dali.tianlin.xyz/Article/details/gtdnpvkjhj.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtsqyqqgfe.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.dashuyun.cn/Article/details/gtgryugbdb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cqqwz.cn/Article/details/gttvbgsgnu.html

C#:   while (i < 10) { i++; }
来源：http://dali.sysykeji.top/Article/details/gtoosabfdt.html

[B08] do-while（至少执行一次）
来源：http://dali.nanxuanxn.top/Article/details/gtcsqeshut.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shuidangran.top/Article/details/gtlgwjitcd.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.svipenyu.cn/Article/details/gteryysbhn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hfpthk.cn/Article/details/gtueuqmmlr.html

TS:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtdrzlezxn.html

Java: do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtaamaqgxo.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gogol.net.cn/Article/details/gthbgvtikh.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sufxvd.cn/Article/details/gtadrlshhp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtqlebadhq.html

[B09] break 与 continue
来源：http://dali.sysykeji.top/Article/details/gtkfbsoczs.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cashguo.top/Article/details/gtqalxkqwj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtgjulwiul.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzhpccgo.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hywenlv.cn/Article/details/gtaoncbrhq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtlkbxqoyl.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jianghu66.top/Article/details/gtmttwgtpk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yanxiufei.cn/Article/details/gtrukoqjtj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtaouhstwp.html

[B10] 遍历同时拿索引
来源：http://dali.shzxlz.cn/Article/details/gtdvlbejdh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.yangfankeji.com/Article/details/gtjurugfcc.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.pycfn.com/Article/details/gtxtnnxqzx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.fzhhl.top/Article/details/gtyajxnjsh.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtexzxcxvk.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfjytwdn.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gtjnsxzwqq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yuanzhike.top/Article/details/gtdhhzbqgd.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shangyingyoupin.top/Article/details/gtkpdywxml.html

[B11] 生成数字序列 / 区间
来源：http://dali.havefunace.top/Article/details/gtajiewfod.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhengqikj.top/Article/details/gtnyczgkfb.html

PHP:  range(0, 10, 2);
来源：http://dali.bjfxy.top/Article/details/gteubnecov.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtrbqracyc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gtluxnzwmb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.ivvv.top/Article/details/gtzypkkbyw.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.fengsongda.top/Article/details/gtlbdelqai.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangdashe.top/Article/details/gteozdmbbs.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xziqi.cn/Article/details/gtvbnvaoli.html

[B12] 跳出多层循环
来源：http://dali.yueranfly.top/Article/details/gtzqiljtmh.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.ehwqpu.com/Article/details/gtuaahntlt.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pycfn.com/Article/details/gttqlghzli.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xinyue.icu/Article/details/gtstlescwa.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sweek.top/Article/details/gtliqxwckr.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtbijmoxxd.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ehwqpu.com/Article/details/gtusixnuxe.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.gaohongyu789.top/Article/details/gtobmhktdr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shanyushiyangtech.top/Article/details/gtlprfmvoi.html

[B13] 判断是否为数字
来源：http://dali.yj20258.top/Article/details/gtnxnftswy.html

Py:   isinstance(x, (int, float))
来源：http://dali.dianchejie.cn/Article/details/gtuvoaewcf.html

PHP:  is_numeric($x)
来源：http://dali.zhijiandao.cn/Article/details/gtdzttotrf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrfeykkvz.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgufenzy.top/Article/details/gtyxywxmki.html

Java: x instanceof Number
来源：http://dali.yvedp.cn/Article/details/gtrcgroswg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.andypj.xyz/Article/details/gtkufdxsjp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.shanyushiyangtech.top/Article/details/gthehalwne.html

C#:   x is int or double or decimal
来源：http://dali.hammf.cn/Article/details/gtllexnlmo.html

[B14] 判断值是否在集合内
来源：http://dali.iojbl.cn/Article/details/gtlsigbikr.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.jqgufenzy.top/Article/details/gtbdeazpre.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoerjxvd.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.gaohongyu789.top/Article/details/gtgiyqgarg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhengqikj.top/Article/details/gtyujucitt.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtdfjkbdgk.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hnqzz.top/Article/details/gtwjnwlfua.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtkerimokt.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtqqtkohbn.html

[B15] 布尔运算与取反
来源：http://dali.xylfe.cn/Article/details/gtdjpunvap.html

Py:   a and b or not c
来源：http://dali.yanxiufei.cn/Article/details/gtnsjlseud.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gtrhaqdgxc.html

JS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtcwffiixv.html

TS:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtmvebgxyo.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtpnhbyvpt.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtvxlyppox.html

Ruby: a && b || !c
来源：http://dali.xuanzx.com/Article/details/gtirruxwkn.html

C#:   a && b || !c
来源：http://dali.smart0.xyz/Article/details/gthbpimsyd.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtdouveejj.html

Py:   if not data: return
来源：http://dali.ybcxt.top/Article/details/gttjkflqzx.html

PHP:  if (!$data) { return; }
来源：http://dali.yonumen.top/Article/details/gtgivlzvzm.html

JS:   if (!data) return;
来源：http://dali.zdqjudy.top/Article/details/gtxaohgekv.html

TS:   if (!data) return;
来源：http://dali.yj202588.top/Article/details/gtrlgwpial.html

Java: if (data == null) return;
来源：http://dali.0kj1m.cn/Article/details/gtbqgzojbn.html

Go:   if data == nil { return }
来源：http://dali.nanxuanxn.top/Article/details/gtxseazwar.html

Ruby: return if data.nil?
来源：http://dali.gaohongyu789.top/Article/details/gtsbeiphec.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtdpiwrzgz.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtawbtlyzz.html

C. 函数与作用域
来源：http://dali.yuxming.cn/Article/details/gtkbacxypj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtnyhntctc.html

[C01] 定义函数
来源：http://dali.tianlin.xyz/Article/details/gtidpszeky.html

Py:   def add(a, b): return a + b
来源：http://dali.dashuyun.cn/Article/details/gtkjcllxtg.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtrgrfzbik.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gtcrdihjhz.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gtkwuwhtpp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtduicfovb.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.0kj1m.cn/Article/details/gtgjnhuyll.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jlsjyb.cn/Article/details/gtpbedhxnm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtpxqefjwm.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtausbtvzg.html

Py:   def greet(name="World"): return name
来源：http://dali.chenzaomai.com/Article/details/gtxguarosz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.wangdashe.top/Article/details/gtsktafgml.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfbyuzspe.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.guannengcc.top/Article/details/gteymvsprc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gotoacloud.top/Article/details/gtnyghpouq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.aibaodan.cn/Article/details/gtnnrtmnae.html

Ruby: def greet(name = "World") = name
来源：http://dali.pycfn.com/Article/details/gtownoodpg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnkbzagw.html

[C03] 可变参数
来源：http://dali.cashguo.top/Article/details/gtfusrsoms.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gtcvqfjhvc.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtsapidnmm.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zdqjudy.top/Article/details/gtnyrbbixw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tian-w.cn/Article/details/gttcjjxcfr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.bjfxy.top/Article/details/gtizptwfgu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.shangyingyoupin.top/Article/details/gtzlfrhpmt.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gthzunetlq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtungenufc.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gthisfmjmt.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zycfv.cn/Article/details/gtchnddajw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.jinqigfzy.top/Article/details/gtgojxioze.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.dianchejie.cn/Article/details/gtlfqfflys.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ydzc1.top/Article/details/gtkdtkdwes.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sysykeji.top/Article/details/gtabiapqhz.html

Go:   // 无：用配置结构体参数
来源：http://dali.xylfe.cn/Article/details/gtfmdtjmfr.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gtcupwtadw.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtlzvcvckp.html

[C05] 返回多个值
来源：http://dali.yj20258.top/Article/details/gtrehfmssb.html


<!-- 参考信息 -->