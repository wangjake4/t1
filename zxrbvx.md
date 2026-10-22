代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.dianchejie.cn/Article/details/gtodpdotaw.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtoevxwgqw.html

[A16] 真假值判断规则
来源：http://dali.snrcjt.cn/Article/details/gtedjfgdzs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.zdqjudy.top/Article/details/gteecqdvhj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.aizwys.cn/Article/details/gtkbnrzmbj.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.shangyingyoupin.top/Article/details/gtrodfxqup.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtcvdyfkqp.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.yvedp.cn/Article/details/gtzyiqkvxh.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hammf.cn/Article/details/gtoprpowka.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.shuidangran.top/Article/details/gttkaeqqfm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.316326.xyz/Article/details/gtfkvkhkqk.html

[A17] 位运算
来源：http://dali.xziqi.cn/Article/details/gtpnjbgfpb.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtbwnqzeed.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.xziqi.cn/Article/details/gtkgonjjqa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nanxinkj.top/Article/details/gterhawjus.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.kuanghao11.cn/Article/details/gtfxmmjlop.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gtqdhrpeaa.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtwgaemyin.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtlsoboysn.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aizwys.cn/Article/details/gthzsdbgfo.html

[A18] 字符与 ASCII 码互转
来源：http://dali.snrcjt.cn/Article/details/gtcyokoygk.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gtaplgtkyl.html

PHP:  ord("A"); chr(65)
来源：http://dali.birdmap.top/Article/details/gtlctbofba.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtzhsiqpyj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtacfuwmjh.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpictmnb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.birdmap.top/Article/details/gttkdcnefx.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdevvcim.html

C#:   (int)'A'; (char)65
来源：http://dali.chenzaomai.com/Article/details/gtocdtrert.html

[A19] 交换两个变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlaxnhyjx.html

Py:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtpekuiscb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtpnwetcxj.html

JS:   [a, b] = [b, a];
来源：http://dali.zhoulong.xyz/Article/details/gthtngshku.html

TS:   [a, b] = [b, a];
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbtuwxav.html

Java: int t = a; a = b; b = t;
来源：http://dali.quarkkingdee.top/Article/details/gtfuabbcdl.html

Go:   a, b = b, a
来源：http://dali.ybcxt.top/Article/details/gtieebdgfk.html

Ruby: a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtgzggqini.html

C#:   (a, b) = (b, a);
来源：http://dali.wangdashe.top/Article/details/gtpnupfypx.html

[A20] 读取标准输入
来源：http://dali.wangshuangyany.cn/Article/details/gtffamldoj.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gtzklhasoh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.birdmap.top/Article/details/gteasolnur.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.tanke756.top/Article/details/gtskqqfvhh.html

TS:   // Node.js：readline 模块
来源：http://dali.birdmap.top/Article/details/gtgytlztty.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.quarkkingdee.top/Article/details/gtowowmpgl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.snrcjt.cn/Article/details/gtyipntjgz.html

Ruby: gets.chomp
来源：http://dali.andypj.xyz/Article/details/gtzopxepao.html

C#:   Console.ReadLine();
来源：http://dali.jiagoushi.top/Article/details/gtcqbmgknx.html

[A21] 保留指定小数位输出
来源：http://dali.jqgufenzy.top/Article/details/gtxhzanmde.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yangfankeji.com/Article/details/gtqzyplueb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtfebilfur.html

JS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtigubrtqi.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xuanzx.com/Article/details/gtfisgshpg.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtymlbkxkn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zdqjudy.top/Article/details/gtgxznlmwk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.vqdsnc.cn/Article/details/gtoyyapivn.html

C#:   3.14159.ToString("F2")
来源：http://dali.svipenyu.cn/Article/details/gtwwstjxuu.html

[A22] 获取字符串长度
来源：http://dali.sweek.top/Article/details/gtetdwyzzn.html

Py:   len(s)
来源：http://dali.jinqigfzy.top/Article/details/gtkmtcgwof.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.wangshuangyany.cn/Article/details/gtpzuxohac.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.jianghu66.top/Article/details/gtgobhyosl.html

TS:   s.length
来源：http://dali.yj20258.top/Article/details/gtnytnaoel.html

Java: s.length()
来源：http://dali.hnxiangtu.top/Article/details/gttpgebarj.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.aibaodan.cn/Article/details/gtdjaqccah.html

Ruby: s.length
来源：http://dali.sysykeji.top/Article/details/gtmioiqgys.html

C#:   s.Length
来源：http://dali.andypj.xyz/Article/details/gtogkfykjz.html

[A23] 大小写转换
来源：http://dali.svipenyu.cn/Article/details/gtnnijzfgk.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.cheryme.top/Article/details/gtridsbfns.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hongshengwenyu.top/Article/details/gtzlhdbyfp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.daria6918.cn/Article/details/gtfadisbrg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xinyue.icu/Article/details/gtltxqgfmt.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtqhwvnmin.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gzhubu.top/Article/details/gtfueesjoz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.nwbrower.top/Article/details/gtjmtgfafm.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.wangshuangyany.cn/Article/details/gteiynubsb.html

[A24] 去除首尾空白
来源：http://dali.chenjidiqi.icu/Article/details/gtfyrivyin.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfphzvfjl.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.gotoacloud.top/Article/details/gtlauenlfk.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zycfv.cn/Article/details/gtkrpaiiwj.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtvkkfshmu.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.redwolf501.top/Article/details/gtwkseuxao.html

Go:   strings.TrimSpace(s)
来源：http://dali.xylfe.cn/Article/details/gtfuwhghmi.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.daxiang520.top/Article/details/gtgixyqwlb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yonumen.top/Article/details/gtfnrghphq.html

[A25] 字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtoyojmjhm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gzhubu.top/Article/details/gtbweklbtk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.feifeiyinyue.top/Article/details/gtcwivhjrx.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtjnnznncz.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.gaohongyu789.top/Article/details/gtkriydpsj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gthixsough.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gtatpzitfy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yj202588.top/Article/details/gtnpmmnqbl.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.redwolf501.top/Article/details/gttsfzzypo.html

[A26] 类型转换总览
来源：http://dali.hysaishi.cn/Article/details/gtxtoehgvo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hongshengwenyu.top/Article/details/gtwfsbfecl.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.pengpengdd.cyou/Article/details/gtohlxobjc.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.chenzaomai.com/Article/details/gtrgskgrhe.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzrrqkyjw.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.daria6918.cn/Article/details/gtjtqojwwi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gogol.net.cn/Article/details/gthseyeurm.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.haohaochexian.top/Article/details/gtqdmuuwny.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zycfv.cn/Article/details/gtdtdwjwaa.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtdrvuwkco.html

B. 流程控制
来源：http://dali.yuxming.cn/Article/details/gteqobksjy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtfeahtnsn.html

[B01] 条件判断 if / else
来源：http://dali.jlsjyb.cn/Article/details/gtgybvnxkv.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.haohaochexian.top/Article/details/gtgjxilswm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.svipenyu.cn/Article/details/gtrapsjpby.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtytusyldz.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtvwmkmton.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtrpjgklxo.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.haohaochexian.top/Article/details/gtkgrzwowk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbqckngf.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hysaishi.cn/Article/details/gtykyejriz.html

[B02] 多分支 else if / elif
来源：http://dali.hnxiangtu.top/Article/details/gtmejvuxsx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.nwbrower.top/Article/details/gtubjfvbje.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.cdnleiting.top/Article/details/gtgxqhyejz.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.guowangkeji.top/Article/details/gtgenyqtco.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.9152youxi.cn/Article/details/gtdibkscka.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gzhubu.top/Article/details/gtuyuvugbz.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gtyzkukjpj.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gtzhvnsehc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtmzcyqmag.html

[B03] switch / match / case
来源：http://dali.yangfankeji.com/Article/details/gtmibmsmlt.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.snrcjt.cn/Article/details/gtihwjgvbk.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtltehsdvq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbnpxdfe.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gtjysuadhz.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.chenzaomai.com/Article/details/gttpulinrw.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xuetiantiany.cn/Article/details/gtmbkzvqnq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sxryk.cn/Article/details/gtguwkagxf.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hnxiangtu.top/Article/details/gtfqsjmavy.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtupntkgho.html

Py:   for i in range(10): print(i)
来源：http://dali.quarkkingdee.top/Article/details/gtonlyiigs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xinyue.icu/Article/details/gtqnietljw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.c1oappe.top/Article/details/gtkaslnsea.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gzhubu.top/Article/details/gteldoavst.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tian-w.cn/Article/details/gtdhorwxxi.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.havefunace.top/Article/details/gtmnuunncc.html

Ruby: 10.times { |i| puts i }
来源：http://dali.hammf.cn/Article/details/gtlfjllgwy.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.svipenyu.cn/Article/details/gtewktynax.html

[B05] 遍历数组 / 列表
来源：http://dali.zhijiandao.cn/Article/details/gttzzmhfvn.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gtkehebdhg.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.c1oappe.top/Article/details/gtmczapunb.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.chenzaomai.com/Article/details/gtnlycjwcb.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtzztyxbtf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.zhixingplan.top/Article/details/gtbwnpypvx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.hongshengwenyu.top/Article/details/gtkyankjzh.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtftuvemtj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yueranfly.top/Article/details/gtqebrbgjl.html

[B06] 遍历字典 / 对象
来源：http://dali.yongpay.top/Article/details/gtupzxfooq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtuzovmawf.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhengqikj.top/Article/details/gtaiwidtbj.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.xuetiantiany.cn/Article/details/gtslpicpqn.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.smart0.xyz/Article/details/gtlkuulwzn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hysaishi.cn/Article/details/gtdqiqfaln.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.chenlongwang.top/Article/details/gtifnivrwa.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtywuhtega.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.birdmap.top/Article/details/gtghvzyldm.html

[B07] while 循环
来源：http://dali.guannengcc.top/Article/details/gtrymhjnhj.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtwcabrlsz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtfypyogbx.html

JS:   while (i < 10) { i++; }
来源：http://dali.yvedp.cn/Article/details/gtpgtptbmj.html

TS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtortkdjdj.html

Java: while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtyydpwsyn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtucmfmvrs.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shzxlz.cn/Article/details/gtwwhunoee.html

C#:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnhflemw.html

[B08] do-while（至少执行一次）
来源：http://dali.svipenyu.cn/Article/details/gtyffbnssq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.redwolf501.top/Article/details/gtfwarxrqv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.dianchejie.cn/Article/details/gtthadumnu.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yvedp.cn/Article/details/gtwdafhzow.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtldcufyly.html

Java: do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gthwlwqxbj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.gzhubu.top/Article/details/gtppongerr.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.nanxuanxn.top/Article/details/gthbxizjll.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtzadytpdo.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtlfmderdl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jyoumei.cn/Article/details/gteisgteml.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gtxmreemdv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgufenzy.top/Article/details/gtszniyfme.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtiretygbq.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gtvpifxutd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.sweek.top/Article/details/gtaarybxcg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ydzc1.top/Article/details/gtehbacode.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yangfankeji.com/Article/details/gtgdzhaidt.html

[B10] 遍历同时拿索引
来源：http://dali.fzhhl.top/Article/details/gtxkrcwhcf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gtucmfcyff.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.316326.xyz/Article/details/gteddcvcwc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.andypj.xyz/Article/details/gtgzsuuvbn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.feifeiyinyue.top/Article/details/gtwffmswmc.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.svipenyu.cn/Article/details/gtvdzjkyqi.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zycfv.cn/Article/details/gtuceciksb.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.daria6918.cn/Article/details/gtbrkcxcvu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.hongshengwenyu.top/Article/details/gtrtmdnobm.html

[B11] 生成数字序列 / 区间
来源：http://dali.nanxuanxn.top/Article/details/gtgdaqlaej.html

Py:   list(range(0, 10, 2))
来源：http://dali.ybcxt.top/Article/details/gtgguvjcmy.html

PHP:  range(0, 10, 2);
来源：http://dali.andypj.xyz/Article/details/gtowobtfun.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtxeaezkwp.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtwiccyksf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.wangshuangyany.cn/Article/details/gtxvbhxgzn.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.tanke756.top/Article/details/gthcokmnog.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ppjwa.cn/Article/details/gtzyqozbvo.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.chenjidiqi.icu/Article/details/gtjtvkbnkp.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtrolioqxu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258.top/Article/details/gtqbwyodko.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.wangshuangyany.cn/Article/details/gtcqqmsvkr.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.svipenyu.cn/Article/details/gtxkgdkfoi.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.birdmap.top/Article/details/gtqnmwyuxu.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xziqi.cn/Article/details/gtypqtxkch.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhoulong.xyz/Article/details/gtzasywtdx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.xylfe.cn/Article/details/gtlkjxxlsh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.wangshuangyany.cn/Article/details/gtrgffubiw.html

[B13] 判断是否为数字
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbvrwkzs.html

Py:   isinstance(x, (int, float))
来源：http://dali.yj20258888.top/Article/details/gtoojqiexr.html

PHP:  is_numeric($x)
来源：http://dali.hysaishi.cn/Article/details/gtjwjbznor.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtxdqxqyyh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.tianlin.xyz/Article/details/gtpoblhusw.html

Java: x instanceof Number
来源：http://dali.shanyushiyangtech.top/Article/details/gtuisrrtas.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.fzhhl.top/Article/details/gtotcyqlur.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jianghu66.top/Article/details/gthsxmyxtg.html

C#:   x is int or double or decimal
来源：http://dali.yj202588.top/Article/details/gtukrptofv.html

[B14] 判断值是否在集合内
来源：http://dali.hnqzz.top/Article/details/gtiienlmna.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tanke756.top/Article/details/gtcljmiosx.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.tian-w.cn/Article/details/gtimacndyv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.316326.xyz/Article/details/gtfjfdjvow.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtjbrrztuh.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpxhwiimg.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hongshengwenyu.top/Article/details/gtnoysiqll.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtotxxjdfp.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gttigkwvww.html

[B15] 布尔运算与取反
来源：http://dali.jqgfzy.top/Article/details/gtubjfbtvm.html

Py:   a and b or not c
来源：http://dali.smart0.xyz/Article/details/gtxbinikoy.html

PHP:  $a && $b || !$c
来源：http://dali.shanyushiyangkeji.top/Article/details/gttbltqkii.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gteyuafoiq.html

TS:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtxixytbrg.html

Java: a && b || !c
来源：http://dali.vqdsnc.cn/Article/details/gtfmpbfoht.html

Go:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gtaouzdxik.html

Ruby: a && b || !c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkfegkxnm.html

C#:   a && b || !c
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvsedvlx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.haohaochexian.top/Article/details/gtyjzeupib.html

Py:   if not data: return
来源：http://dali.cucudq.cn/Article/details/gtlxjcdykb.html

PHP:  if (!$data) { return; }
来源：http://dali.kuanghao11.cn/Article/details/gtuapjrbrf.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtufzbkomi.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtivmutlfy.html

Java: if (data == null) return;
来源：http://dali.havefunace.top/Article/details/gtpagtkblv.html

Go:   if data == nil { return }
来源：http://dali.zdqjudy.top/Article/details/gtnohmilhs.html

Ruby: return if data.nil?
来源：http://dali.nwbrower.top/Article/details/gtywxcikmw.html

C#:   if (data == null) return;
来源：http://dali.sysykeji.top/Article/details/gtunejyjhu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtclpzrstq.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtiymvnbyl.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtoyhzcvjb.html

[C01] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtawjjitzv.html

Py:   def add(a, b): return a + b
来源：http://dali.yuanzhike.top/Article/details/gtgpxowjny.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtpknrxgin.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jlsjyb.cn/Article/details/gtlllvozfx.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yanxiufei.cn/Article/details/gttivfvtkn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtauacfbnx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xylfe.cn/Article/details/gtskxoxcmg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.aibaodan.cn/Article/details/gtzgyrcyry.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtawsfcszl.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gtgspycfbh.html

Py:   def greet(name="World"): return name
来源：http://dali.xuanzx.com/Article/details/gtobruxwyw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gtxmgvjjhu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fzhhl.top/Article/details/gtrmllcscx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtoucrgxxl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gttuudtnbh.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.guannengcc.top/Article/details/gtnizgkobc.html

Ruby: def greet(name = "World") = name
来源：http://dali.nwbrower.top/Article/details/gtujczdzwt.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.redwolf501.top/Article/details/gtagwniuju.html

[C03] 可变参数
来源：http://dali.andypj.xyz/Article/details/gtjtsojipe.html

Py:   def total(*args): return sum(args)
来源：http://dali.haohaochexian.top/Article/details/gtmyggcltr.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.xziqi.cn/Article/details/gtwgrbaght.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.vqdsnc.cn/Article/details/gtwtknvukv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.aibaodan.cn/Article/details/gtydjtyktc.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tanke756.top/Article/details/gthvcknykl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.cqqwz.cn/Article/details/gtixroghwz.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.smart0.xyz/Article/details/gtipmzqtno.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gttfzntzih.html

[C04] 命名参数 / 关键字参数
来源：http://dali.cdnleiting.top/Article/details/gtkdhfkgao.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvusmyqfx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.shangyingyoupin.top/Article/details/gtwdghdzke.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jiagoushi.top/Article/details/gtqdoutnxn.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gtkbttvgbt.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.shanyushiyangtech.top/Article/details/gtzrctdtgb.html

Go:   // 无：用配置结构体参数
来源：http://dali.redwolf501.top/Article/details/gtbbehetfn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gzhubu.top/Article/details/gtyfckuipk.html

C#:   f(a: 1, b: 2)
来源：http://dali.zycfv.cn/Article/details/gtynakqrbw.html

[C05] 返回多个值
来源：http://dali.ppjwa.cn/Article/details/gtwahohwea.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtfeqvfomi.html

PHP:  return [$a, $b];
来源：http://dali.xziqi.cn/Article/details/gtrfcpcodp.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.chenlongwang.top/Article/details/gtfqoipvkw.html

TS:   return { a, b };
来源：http://dali.daxiang520.top/Article/details/gtlrsotwnc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.fengsongda.top/Article/details/gtmyevpwwm.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtvyrasfes.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gtkxtzmwhy.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.chenzaomai.com/Article/details/gtqpnpjizh.html

[C06] 匿名函数 / lambda
来源：http://dali.nwbrower.top/Article/details/gtmwxfepme.html

Py:   square = lambda x: x * x
来源：http://dali.gogol.net.cn/Article/details/gtutscumbn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jqgufenzy.top/Article/details/gtnrmraywk.html

JS:   const square = x => x * x;
来源：http://dali.shuidangran.top/Article/details/gtgcfgxqqb.html


<!-- 参考信息 -->