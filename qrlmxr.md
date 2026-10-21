代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.yueranfly.top/Article/details/gtexijkfuq.html

[A15] 空值判断与默认值
来源：http://dali.yj202588.top/Article/details/gtvpguydll.html

Py:   value = data or "默认值"
来源：http://dali.c1oappe.top/Article/details/gtmbgnqphr.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.xylfe.cn/Article/details/gtjkoupgcl.html

JS:   const value = data ?? "默认值";
来源：http://dali.yuanzhike.top/Article/details/gtwynebhxb.html

TS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtmqawdpzk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.fzhhl.top/Article/details/gtqlsbmrgs.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yvedp.cn/Article/details/gtgsjmetpp.html

Ruby: value = data || "默认值"
来源：http://dali.xinyue.icu/Article/details/gtqycpxxkx.html

C#:   var value = data ?? "默认值";
来源：http://dali.jinghuilouyu.cn/Article/details/gtlcoxnwnk.html

[A16] 真假值判断规则
来源：http://dali.zycfv.cn/Article/details/gtdoozgihi.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cashguo.top/Article/details/gtlftcbbco.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gtuxgfbtvb.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zdqjudy.top/Article/details/gtthtzmqnb.html

TS:   if (!x) {}
来源：http://dali.jyoumei.cn/Article/details/gtvewnalix.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yongpay.top/Article/details/gthnkekbcq.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.wangshuangyany.cn/Article/details/gthcatztks.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.cucudq.cn/Article/details/gtgxnuxtgl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cucudq.cn/Article/details/gtryhgomtm.html

[A17] 位运算
来源：http://dali.xuanzx.com/Article/details/gtipswsslt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtzaqhmevz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ydzc1.top/Article/details/gtqyfnhrkf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtisskyksa.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.andypj.xyz/Article/details/gtwtqexjcj.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gturitgaip.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtzobkmupq.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cashguo.top/Article/details/gtiahomgep.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtmvwgmqjy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cashguo.top/Article/details/gtohnatpbm.html

Py:   ord("A"); chr(65)
来源：http://dali.cdnleiting.top/Article/details/gtajywcxsj.html

PHP:  ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtkflwhsbl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.snrcjt.cn/Article/details/gtlbyqfluh.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gtkcnqibsg.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjofwriw.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jiagoushi.top/Article/details/gtgzkxvpku.html

Ruby: "A".ord; 65.chr
来源：http://dali.316326.xyz/Article/details/gtaplfrpae.html

C#:   (int)'A'; (char)65
来源：http://dali.jinqigufen.top/Article/details/gtwgkkuxqj.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gtynzglfhx.html

Py:   a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtogkfdjde.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.smart0.xyz/Article/details/gttjhqfsek.html

JS:   [a, b] = [b, a];
来源：http://dali.jinghuilouyu.cn/Article/details/gtlebkggrp.html

TS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtwcuepiaj.html

Java: int t = a; a = b; b = t;
来源：http://dali.jqgfzy.top/Article/details/gtqyufotxa.html

Go:   a, b = b, a
来源：http://dali.ydzc1.top/Article/details/gtkncqcdly.html

Ruby: a, b = b, a
来源：http://dali.nwbrower.top/Article/details/gtaqgkghgm.html

C#:   (a, b) = (b, a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzoddzxf.html

[A20] 读取标准输入
来源：http://dali.ehwqpu.com/Article/details/gtilhvufri.html

Py:   name = input("请输入：")
来源：http://dali.daxiang520.top/Article/details/gtzwsvukzz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jinyuanbaomall.cn/Article/details/gtchcorqiw.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hywenlv.cn/Article/details/gtwaejbcuo.html

TS:   // Node.js：readline 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtujqeuovg.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.smart0.xyz/Article/details/gtwqhjvkfl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtduyopswv.html

Ruby: gets.chomp
来源：http://dali.mhx1999.top/Article/details/gtjxveqslp.html

C#:   Console.ReadLine();
来源：http://dali.ybcxt.top/Article/details/gtxbzdakod.html

[A21] 保留指定小数位输出
来源：http://dali.mhx1999.top/Article/details/gtoxvuhxtn.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxrlwzqi.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtewduoynk.html

JS:   (3.14159).toFixed(2)
来源：http://dali.svipenyu.cn/Article/details/gtsjqgfdbp.html

TS:   (3.14159).toFixed(2)
来源：http://dali.cashguo.top/Article/details/gtdebbjshn.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gtfmsrewno.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtfgiorxmp.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtccjcjbkb.html

C#:   3.14159.ToString("F2")
来源：http://dali.jianghu66.top/Article/details/gtieyoqury.html

[A22] 获取字符串长度
来源：http://dali.iojbl.cn/Article/details/gtnrlxfzlt.html

Py:   len(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtojmuqmon.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.nanxinkj.top/Article/details/gtddotahyr.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gtdjlkvbog.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gtzbqykues.html

Java: s.length()
来源：http://dali.daxiang520.top/Article/details/gtojrihxyc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.chenzaomai.com/Article/details/gtuwufhpkz.html

Ruby: s.length
来源：http://dali.pycfn.com/Article/details/gtyvlfmofw.html

C#:   s.Length
来源：http://dali.zhongyouzk.top/Article/details/gtbakeuwvl.html

[A23] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtaygqctvx.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cqqwz.cn/Article/details/gtjfnldqdo.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cashguo.top/Article/details/gtpetmwqcg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtuffgkuty.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hongshengwenyu.top/Article/details/gtyvihngwk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtegcefokx.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yanxiufei.cn/Article/details/gtmxadkudh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.c1oappe.top/Article/details/gtlysxrhgm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.feifeiyinyue.top/Article/details/gtqwwmrojg.html

[A24] 去除首尾空白
来源：http://dali.guowangkeji.top/Article/details/gthmmjwelo.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.iojbl.cn/Article/details/gtxjrfderk.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.chenlongwang.top/Article/details/gtgejtjspy.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtfsygnhol.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ydzc1.top/Article/details/gtnnuwypbs.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.quarkkingdee.top/Article/details/gtapgyyovn.html

Go:   strings.TrimSpace(s)
来源：http://dali.tian-w.cn/Article/details/gtpxnovlog.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuxming.cn/Article/details/gtufdnwzez.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhixingplan.top/Article/details/gtkxtdpktt.html

[A25] 字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtuuunryty.html

Py:   s1 == s2; s1 != s2
来源：http://dali.hysaishi.cn/Article/details/gtzmxrjxiw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jinqigufen.top/Article/details/gtfuhsnqcu.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gtqbchiivx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gtqznvkson.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhijiandao.cn/Article/details/gtsfxkvlpo.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenlongwang.top/Article/details/gtlrxjxbhy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtfdmhedwi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.cdnleiting.top/Article/details/gtrpzylzlj.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtreugzeei.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gtebhfcbzz.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zhongyouzk.top/Article/details/gtckiytgbu.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.wangshuangyany.cn/Article/details/gtifegbkgu.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yj20258888.top/Article/details/gtetagraag.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenzaomai.com/Article/details/gtssdihlfi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yangfankeji.com/Article/details/gtoqnatahs.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ybcxt.top/Article/details/gtxioqfyxh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.smart0.xyz/Article/details/gtigiesdmv.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtbhelkqds.html

B. 流程控制
来源：http://dali.jlsjyb.cn/Article/details/gtsmxlnjdm.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gttqmkctzd.html

[B01] 条件判断 if / else
来源：http://dali.yonumen.top/Article/details/gtvirsvpkb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.fzhhl.top/Article/details/gtwneznvre.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.iojbl.cn/Article/details/gttlhdgrjn.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.vqdsnc.cn/Article/details/gtxfjxufci.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ivvv.top/Article/details/gtugjkbjpz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhixingplan.top/Article/details/gtdumewqyn.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.jinqigufen.top/Article/details/gtyvvvvycu.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yj202588.top/Article/details/gtgijtzone.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtyfooknqq.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gtgmzjjnik.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtsmzsuyod.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.vqdsnc.cn/Article/details/gtpdmxrrmy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtmspgulxm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.sxryk.cn/Article/details/gtkemxwrcv.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hywenlv.cn/Article/details/gtdqimnzik.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.jyoumei.cn/Article/details/gtrhndousm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.ybcxt.top/Article/details/gtiqfsiyff.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtljvxrppc.html

[B03] switch / match / case
来源：http://dali.chenjidiqi.icu/Article/details/gtmmrssfwp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.cucudq.cn/Article/details/gtmydlfium.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtwiazllvg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtspffgktr.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hnqzz.top/Article/details/gtigdmzrny.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtgqyskwac.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.tanke756.top/Article/details/gtbliqtxuu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yonumen.top/Article/details/gtvontzlso.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhixingplan.top/Article/details/gtytbwcebl.html

[B04] for 计数循环
来源：http://dali.cqqwz.cn/Article/details/gtizxmjcup.html

Py:   for i in range(10): print(i)
来源：http://dali.nanxuanxn.top/Article/details/gtyvnxlzhy.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.hywenlv.cn/Article/details/gtvumzztsy.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtotviervt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtyllvlokg.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtppkfrqwg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jianghu66.top/Article/details/gtuknhwagq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.redwolf501.top/Article/details/gtomgteuvq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuanzhike.top/Article/details/gtnwvgxnrz.html

[B05] 遍历数组 / 列表
来源：http://dali.xylfe.cn/Article/details/gtuhvytsdt.html

Py:   for item in arr: print(item)
来源：http://dali.xziqi.cn/Article/details/gtriemhqfz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.xziqi.cn/Article/details/gtwlgwvqvo.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ybcxt.top/Article/details/gtvcsgujmt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.9152youxi.cn/Article/details/gtrmjkumgb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yj202588.top/Article/details/gtexuydptl.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.xylfe.cn/Article/details/gtlrtxmjir.html

Ruby: arr.each { |item| puts item }
来源：http://dali.svipenyu.cn/Article/details/gteklwezho.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gthdwqhzru.html

[B06] 遍历字典 / 对象
来源：http://dali.sxryk.cn/Article/details/gtwmzkbljl.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xylfe.cn/Article/details/gtqwuncbpp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.dashuyun.cn/Article/details/gtsedmuopu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tian-w.cn/Article/details/gtdqtzvvxj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.sysykeji.top/Article/details/gtsitzpiem.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.dashuyun.cn/Article/details/gtnweudogp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yuanzhike.top/Article/details/gtbymefwef.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.sweek.top/Article/details/gtkeybhxug.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.tianlin.xyz/Article/details/gtgtqxiugm.html

[B07] while 循环
来源：http://dali.jqgfzy.top/Article/details/gtrxlqwoqb.html

Py:   while i < 10: i += 1
来源：http://dali.hammf.cn/Article/details/gtqgiubbip.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jianghu66.top/Article/details/gtzqyqxazs.html

JS:   while (i < 10) { i++; }
来源：http://dali.birdmap.top/Article/details/gttfgbiqen.html

TS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gttqcndcno.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtltbczhoz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gtbybcyprm.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jinqigfzy.top/Article/details/gtezljuypi.html

C#:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtvjexshis.html

[B08] do-while（至少执行一次）
来源：http://dali.shzxlz.cn/Article/details/gtakurpaek.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cqqwz.cn/Article/details/gtavswdhoc.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tianlin.xyz/Article/details/gtswfpyxpm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gthztququi.html

TS:   do { i++; } while (i < 10);
来源：http://dali.snrcjt.cn/Article/details/gtzbqmalyj.html

Java: do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gtacvjonwa.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.sweek.top/Article/details/gtxgclmtlf.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gtiuhhyjdk.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpyyxuhs.html

[B09] break 与 continue
来源：http://dali.havefunace.top/Article/details/gtkkfpvqev.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.snrcjt.cn/Article/details/gtmcpdzupy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtprmhldgh.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtmwvwiiju.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhijiandao.cn/Article/details/gtfosoodgn.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangshuangyany.cn/Article/details/gtahxqoaez.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gtooafjnee.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.sysykeji.top/Article/details/gtzaiesypx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtadkhgkth.html

[B10] 遍历同时拿索引
来源：http://dali.guannengcc.top/Article/details/gtxsryrbdh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.hysaishi.cn/Article/details/gtdilryyml.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.iojbl.cn/Article/details/gtfqlysqza.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtvvoijxkv.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtcuxsxzom.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yongpay.top/Article/details/gtrtwmduko.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsrzytax.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.ehwqpu.com/Article/details/gtunrkqzdq.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.wangshuangyany.cn/Article/details/gtpztkikrb.html

[B11] 生成数字序列 / 区间
来源：http://dali.ivvv.top/Article/details/gtzlxueuxz.html

Py:   list(range(0, 10, 2))
来源：http://dali.jinqigfzy.top/Article/details/gtdfvkkobf.html

PHP:  range(0, 10, 2);
来源：http://dali.dianchejie.cn/Article/details/gtllsbezra.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhengqikj.top/Article/details/gtcwuooxbq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtweytcbaw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.c1oappe.top/Article/details/gttslkijht.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gotoacloud.top/Article/details/gtdodcfsgz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zhengqikj.top/Article/details/gtozdxrmhu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.hammf.cn/Article/details/gttgwjphth.html

[B12] 跳出多层循环
来源：http://dali.birdmap.top/Article/details/gtryybeszs.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hongshengwenyu.top/Article/details/gtzzmskiwi.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.sxryk.cn/Article/details/gtzjoocrcv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.feifeiyinyue.top/Article/details/gtrmdycxlq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hnqzz.top/Article/details/gtfztvehbz.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jyoumei.cn/Article/details/gtwgplhruv.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.yongpay.top/Article/details/gtidljmciv.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xuetiantiany.cn/Article/details/gthbeotqxp.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yonumen.top/Article/details/gteiyzrbcf.html

[B13] 判断是否为数字
来源：http://dali.haohaochexian.top/Article/details/gtqpdoicpx.html

Py:   isinstance(x, (int, float))
来源：http://dali.vqdsnc.cn/Article/details/gtziezulqi.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gthitzlcfc.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtvukcawzc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ehwqpu.com/Article/details/gtqdtalezr.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtstniaxos.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.zhiwuduotai.top/Article/details/gtabrwzwyo.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtftnevrtn.html

C#:   x is int or double or decimal
来源：http://dali.shuidangran.top/Article/details/gtyqibsgan.html

[B14] 判断值是否在集合内
来源：http://dali.chenjidiqi.icu/Article/details/gttpgqraao.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhoulong.xyz/Article/details/gtmuqgftaz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhaomingkeji.xyz/Article/details/gttlruwwur.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.redwolf501.top/Article/details/gtziiwudpv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtasgronxk.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gteptbppqb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj202588.top/Article/details/gtbfkdvjez.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.guannengcc.top/Article/details/gthfhhymjq.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.yuxming.cn/Article/details/gtgbjpvwld.html

[B15] 布尔运算与取反
来源：http://dali.guannengcc.top/Article/details/gtufjhavkm.html

Py:   a and b or not c
来源：http://dali.bjfxy.top/Article/details/gtdeqxlpxk.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtevhuwuyk.html

JS:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gtxquyeeln.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtzgtslvij.html

Java: a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkotskgna.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtfxoavefw.html

Ruby: a && b || !c
来源：http://dali.ehwqpu.com/Article/details/gtauiotwtz.html

C#:   a && b || !c
来源：http://dali.hywenlv.cn/Article/details/gtefmtvbth.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hysaishi.cn/Article/details/gtfhjpsfvz.html

Py:   if not data: return
来源：http://dali.tianlin.xyz/Article/details/gtqcwrboxt.html

PHP:  if (!$data) { return; }
来源：http://dali.gaohongyu789.top/Article/details/gtwplczdzv.html

JS:   if (!data) return;
来源：http://dali.cqqwz.cn/Article/details/gtrqevmall.html

TS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtiunymkdw.html

Java: if (data == null) return;
来源：http://dali.sufxvd.cn/Article/details/gtsghlewqt.html

Go:   if data == nil { return }
来源：http://dali.chenlongwang.top/Article/details/gtkibeafoz.html

Ruby: return if data.nil?
来源：http://dali.bjfxy.top/Article/details/gtclqbhdwn.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtuiwjikip.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtzzbysyxt.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtzzxxxeee.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtehsbaosl.html

[C01] 定义函数
来源：http://dali.hongshengwenyu.top/Article/details/gtejvhgcwa.html

Py:   def add(a, b): return a + b
来源：http://dali.gogol.net.cn/Article/details/gtgwzsqaaw.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gtpdpxqbsz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtferfnysi.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoqyflog.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtsmpbpghv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daxiang520.top/Article/details/gtdisqzsxu.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yanxiufei.cn/Article/details/gtouqxlogt.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtqtgekurr.html

[C02] 默认参数
来源：http://dali.shuidangran.top/Article/details/gtjzaurzkg.html

Py:   def greet(name="World"): return name
来源：http://dali.gotoacloud.top/Article/details/gtrawypycz.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.xinyue.icu/Article/details/gtjmzushny.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jlsjyb.cn/Article/details/gtvilgegok.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.smart0.xyz/Article/details/gtyiezizjr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.redwolf501.top/Article/details/gtdqvzkowg.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jyoumei.cn/Article/details/gtoredicsh.html

Ruby: def greet(name = "World") = name
来源：http://dali.feifeiyinyue.top/Article/details/gtdzybofuj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gtraitpaif.html

[C03] 可变参数
来源：http://dali.svipenyu.cn/Article/details/gthlzljyjn.html

Py:   def total(*args): return sum(args)
来源：http://dali.gaohongyu789.top/Article/details/gtuwkurqcj.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ivvv.top/Article/details/gtlygwjdkf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.tanke756.top/Article/details/gtxjgcllbv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.fzhhl.top/Article/details/gtkchhmiuu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jianghu66.top/Article/details/gtzzmnxluw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhengqikj.top/Article/details/gtsypcuiij.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xziqi.cn/Article/details/gtdysccpic.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.nanxuanxn.top/Article/details/gtelcliqta.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtsnfepffv.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenlongwang.top/Article/details/gtfjsthnfm.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtfrlzzctw.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbhuklchl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jyoumei.cn/Article/details/gtabqefhsw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.feifeiyinyue.top/Article/details/gtygnxtaht.html

Go:   // 无：用配置结构体参数
来源：http://dali.gogol.net.cn/Article/details/gtqlrfdwgm.html

Ruby: f(a: 1, b: 2)
来源：http://dali.tianlin.xyz/Article/details/gtbryyiilx.html

C#:   f(a: 1, b: 2)
来源：http://dali.guannengcc.top/Article/details/gtkuwrvehh.html

[C05] 返回多个值
来源：http://dali.yvedp.cn/Article/details/gtstpyybqa.html

Py:   return a, b
来源：http://dali.iojbl.cn/Article/details/gthevtcafm.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtyayvgfqg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.havefunace.top/Article/details/gtntsiayza.html

TS:   return { a, b };
来源：http://dali.hfpthk.cn/Article/details/gtzqecqsaj.html


<!-- 参考信息 -->