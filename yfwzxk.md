代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.316326.xyz/Article/details/gtokpklhez.html

[A15] 空值判断与默认值
来源：http://dali.zhongyouzk.top/Article/details/gthpdtvnfk.html

Py:   value = data or "默认值"
来源：http://dali.hammf.cn/Article/details/gtksclrrsa.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aizwys.cn/Article/details/gtjssbxrwh.html

JS:   const value = data ?? "默认值";
来源：http://dali.zdqjudy.top/Article/details/gtpchjohhd.html

TS:   const value = data ?? "默认值";
来源：http://dali.feifeiyinyue.top/Article/details/gtkdqlwbuu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhaomingkeji.xyz/Article/details/gttnuastqa.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tian-w.cn/Article/details/gtpwzlzidi.html

Ruby: value = data || "默认值"
来源：http://dali.hammf.cn/Article/details/gtwbffufkp.html

C#:   var value = data ?? "默认值";
来源：http://dali.sufxvd.cn/Article/details/gtkkjmdrcx.html

[A16] 真假值判断规则
来源：http://dali.feifeiyinyue.top/Article/details/gtaznniozs.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.yj20258888.top/Article/details/gtltdvdnqm.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.dashuyun.cn/Article/details/gtetdhrfxc.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.chenzaomai.com/Article/details/gtafltavqj.html

TS:   if (!x) {}
来源：http://dali.hongshengwenyu.top/Article/details/gtedkbvsed.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.ivvv.top/Article/details/gtlolyrkiw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yanxiufei.cn/Article/details/gtmeuywjoq.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jinqigufen.top/Article/details/gtvrmbpoif.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gzhubu.top/Article/details/gthddlfetj.html

[A17] 位运算
来源：http://dali.zhiwuduotai.top/Article/details/gtgyirclxp.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtskwhxooq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtanihuezg.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gthuityifm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.shzxlz.cn/Article/details/gtfcuejibx.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtiqnwgner.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hywenlv.cn/Article/details/gtgdbwiogj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtyfaewbkg.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtfazbtnpa.html

[A18] 字符与 ASCII 码互转
来源：http://dali.jqgufenzy.top/Article/details/gtshhfxlna.html

Py:   ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtyqhikomm.html

PHP:  ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtwovgdwqy.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.tianlin.xyz/Article/details/gtoclnnlay.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtoodegyhq.html

Java: (int) 'A'; (char) 65
来源：http://dali.jinqigufen.top/Article/details/gtozhjaymx.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvmcckve.html

Ruby: "A".ord; 65.chr
来源：http://dali.svipenyu.cn/Article/details/gteabokeej.html

C#:   (int)'A'; (char)65
来源：http://dali.jianghu66.top/Article/details/gtenexnmsg.html

[A19] 交换两个变量
来源：http://dali.quarkkingdee.top/Article/details/gtqrothcyu.html

Py:   a, b = b, a
来源：http://dali.havefunace.top/Article/details/gtpicfgutr.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.aizwys.cn/Article/details/gtqabfqxua.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtiemazmar.html

TS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gtsrxzigzm.html

Java: int t = a; a = b; b = t;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuwzmbca.html

Go:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtxwiepqdh.html

Ruby: a, b = b, a
来源：http://dali.zhoulong.xyz/Article/details/gtrjyiqzhl.html

C#:   (a, b) = (b, a);
来源：http://dali.hammf.cn/Article/details/gtqqbnikqt.html

[A20] 读取标准输入
来源：http://dali.yangfankeji.com/Article/details/gtaaoqgpaq.html

Py:   name = input("请输入：")
来源：http://dali.fzhhl.top/Article/details/gtwshshtxz.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.bjfxy.top/Article/details/gttatvtuwh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gtpdkeodje.html

TS:   // Node.js：readline 模块
来源：http://dali.hnxiangtu.top/Article/details/gtkwecpvuy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shangyingyoupin.top/Article/details/gtkmvvoygz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangdashe.top/Article/details/gtifvygtwz.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gtoevfxtar.html

C#:   Console.ReadLine();
来源：http://dali.jinghuilouyu.cn/Article/details/gtckolvmkr.html

[A21] 保留指定小数位输出
来源：http://dali.feifeiyinyue.top/Article/details/gtdshxvdsw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gtawwpzsaj.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shangyingyoupin.top/Article/details/gtpkejwnfu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.iojbl.cn/Article/details/gtyjdecauj.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gttgpnwluz.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.daria6918.cn/Article/details/gtsdzwmopr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtmifmmrhj.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.chenjidiqi.icu/Article/details/gtctjtngtx.html

C#:   3.14159.ToString("F2")
来源：http://dali.andypj.xyz/Article/details/gttlxoeydu.html

[A22] 获取字符串长度
来源：http://dali.smart0.xyz/Article/details/gtvjblefqe.html

Py:   len(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqvuqdqbp.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gtxacdalnp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.chenzaomai.com/Article/details/gtitwulbgi.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gtqymypvyi.html

Java: s.length()
来源：http://dali.yj20258888.top/Article/details/gtujaqwilf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hywenlv.cn/Article/details/gtzfevvngg.html

Ruby: s.length
来源：http://dali.redwolf501.top/Article/details/gtmoknrpnz.html

C#:   s.Length
来源：http://dali.zhiwuduotai.top/Article/details/gtokfpaeqq.html

[A23] 大小写转换
来源：http://dali.sysykeji.top/Article/details/gthvtftqua.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtuwwedcgn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xuetiantiany.cn/Article/details/gtsuworwqj.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtvvkvebby.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.tian-w.cn/Article/details/gtwdexsnmr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.0kj1m.cn/Article/details/gtynwwjpui.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yangfankeji.com/Article/details/gtfxihzihz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.chenzaomai.com/Article/details/gtivsnmjpc.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hywenlv.cn/Article/details/gtijnbgceb.html

[A24] 去除首尾空白
来源：http://dali.yanxiufei.cn/Article/details/gtrretditp.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.316326.xyz/Article/details/gtpslfpwmi.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangdashe.top/Article/details/gthlvvoyak.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.0kj1m.cn/Article/details/gtcpfklmxt.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cdnleiting.top/Article/details/gtlpvcdllw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cashguo.top/Article/details/gthtqdjzuu.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtdmuvfpjx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.gaohongyu789.top/Article/details/gtdcvljacg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.hongshengwenyu.top/Article/details/gtsxshydns.html

[A25] 字符串比较
来源：http://dali.jianghu66.top/Article/details/gtrdsfgupp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yueranfly.top/Article/details/gtlfrzrvjf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.fzhhl.top/Article/details/gtbcsxwjjw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.cheryme.top/Article/details/gtitfaazub.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhiwuduotai.top/Article/details/gtkfiipgdk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhongyouzk.top/Article/details/gtudlbmvhx.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gtdeyiunek.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jianghu66.top/Article/details/gtyborrhhj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzocllnkw.html

[A26] 类型转换总览
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpsgfpfj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinqigufen.top/Article/details/gtgqzdkowt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.wangdashe.top/Article/details/gtvcbefckj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xziqi.cn/Article/details/gtjfpvlwxt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jiagoushi.top/Article/details/gthsbpgtva.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.nanxuanxn.top/Article/details/gtkdwvakdc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhixingplan.top/Article/details/gtvnlvlxsz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nanxinkj.top/Article/details/gtsulogqwe.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtrbvejlir.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtyrmazhaz.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gtsntanlwb.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtpxwoytko.html

[B01] 条件判断 if / else
来源：http://dali.mhx1999.top/Article/details/gtsonaqtip.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.bjfxy.top/Article/details/gtfdavvdiy.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.aizwys.cn/Article/details/gtkwccskpq.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuanzhike.top/Article/details/gtglipgfor.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.mhx1999.top/Article/details/gtcpdckvyv.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gttxdsavyz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.sysykeji.top/Article/details/gtswvxavrv.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtkqvhcdre.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.guowangkeji.top/Article/details/gtjqgccmfn.html

[B02] 多分支 else if / elif
来源：http://dali.jinqigfzy.top/Article/details/gtjlxvrxpz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fengsongda.top/Article/details/gtovddukwr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jlsjyb.cn/Article/details/gttynpiokx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.iojbl.cn/Article/details/gtzqopnebu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cheryme.top/Article/details/gtoraqkgbr.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.daria6918.cn/Article/details/gtjesvywet.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.guannengcc.top/Article/details/gtyzkzmfml.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xinyue.icu/Article/details/gtatxabzvb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtxbfcdouk.html

[B03] switch / match / case
来源：http://dali.ydzc1.top/Article/details/gtcccxqieb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.aibaodan.cn/Article/details/gtqudshcdf.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ydzc1.top/Article/details/gtlantcywz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtqcnygkln.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tianlin.xyz/Article/details/gtnrijluer.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtiqcfudvx.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.hammf.cn/Article/details/gtvznnwhtq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yueranfly.top/Article/details/gtvmvuknmq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.xziqi.cn/Article/details/gtgeyouynq.html

[B04] for 计数循环
来源：http://dali.quarkkingdee.top/Article/details/gtysetkdyu.html

Py:   for i in range(10): print(i)
来源：http://dali.gaohongyu789.top/Article/details/gtownxcrkm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.pycfn.com/Article/details/gtyuloxjwt.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gtbulhfjcu.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jinqigfzy.top/Article/details/gtwhdtziod.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xuanzx.com/Article/details/gtpnsbnhzg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gtbirwwqed.html

Ruby: 10.times { |i| puts i }
来源：http://dali.daria6918.cn/Article/details/gtewvyvewo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jianghu66.top/Article/details/gttqjuyuym.html

[B05] 遍历数组 / 列表
来源：http://dali.quarkkingdee.top/Article/details/gtbsvyizvi.html

Py:   for item in arr: print(item)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjzdaqzts.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.ydzc1.top/Article/details/gtvnrmchbz.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.c1oappe.top/Article/details/gtvmcdxyri.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yueranfly.top/Article/details/gtfpklxkfx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.c1oappe.top/Article/details/gtghuldess.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqwbxxqut.html

Ruby: arr.each { |item| puts item }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtataikqnn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.chenlongwang.top/Article/details/gtaxueflhf.html

[B06] 遍历字典 / 对象
来源：http://dali.hywenlv.cn/Article/details/gttvlgtkfm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgftkyykp.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyqfmgcu.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jyoumei.cn/Article/details/gtbqbfucbw.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gogol.net.cn/Article/details/gtamiokgvg.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sweek.top/Article/details/gtxhevctiq.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.fengsongda.top/Article/details/gtlsduurgq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gttescraql.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.gotoacloud.top/Article/details/gtsegpvjrh.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtyqbfewke.html

Py:   while i < 10: i += 1
来源：http://dali.hongshengwenyu.top/Article/details/gtybleqluv.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ehwqpu.com/Article/details/gtehhdpacs.html

JS:   while (i < 10) { i++; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgeoargqu.html

TS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtzjlrbiay.html

Java: while (i < 10) { i++; }
来源：http://dali.xuanzx.com/Article/details/gtrmplnwdv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.daria6918.cn/Article/details/gtcwecilxb.html

Ruby: while i < 10; i += 1; end
来源：http://dali.shuidangran.top/Article/details/gtrnvymizo.html

C#:   while (i < 10) { i++; }
来源：http://dali.cucudq.cn/Article/details/gtczstmpzb.html

[B08] do-while（至少执行一次）
来源：http://dali.yanxiufei.cn/Article/details/gtapricbyx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtviwvhrku.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtxwzenlbc.html

JS:   do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtdvsrnzkf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yangfankeji.com/Article/details/gtahtzfcis.html

Java: do { i++; } while (i < 10);
来源：http://dali.cucudq.cn/Article/details/gtmbpoxvlq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jlsjyb.cn/Article/details/gtacffhspq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yangfankeji.com/Article/details/gtfrldqmvj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.chenlongwang.top/Article/details/gteeabquxq.html

[B09] break 与 continue
来源：http://dali.redwolf501.top/Article/details/gtcguzqxie.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgrtigpf.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtlwqesjly.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfexepewf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tian-w.cn/Article/details/gtzrhxiido.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuanzhike.top/Article/details/gtvhvxsxgd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtdlazxtuo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenzaomai.com/Article/details/gtqkxnryyo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkzzgvlqk.html

[B10] 遍历同时拿索引
来源：http://dali.316326.xyz/Article/details/gtkuinbara.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gthbanjalv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zdqjudy.top/Article/details/gtmdwznxvc.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gtazdycxtn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gthshyxzdb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenlongwang.top/Article/details/gtgcdecgwk.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.aizwys.cn/Article/details/gtmyiwzpre.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhongyouzk.top/Article/details/gtfrubnshk.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.cheryme.top/Article/details/gtgvunkakl.html

[B11] 生成数字序列 / 区间
来源：http://dali.sysykeji.top/Article/details/gtwwqvmhpc.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtocciyoce.html

PHP:  range(0, 10, 2);
来源：http://dali.9152youxi.cn/Article/details/gtgjuohkud.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shuidangran.top/Article/details/gtvhpxdzam.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.316326.xyz/Article/details/gtblbvtsbf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.hywenlv.cn/Article/details/gtwtmfinte.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sysykeji.top/Article/details/gtkfxkbabl.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yj20258888.top/Article/details/gtmiuzxgyu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtphpiwlkg.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtocobxusl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxuanxn.top/Article/details/gtrthgscay.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigfzy.top/Article/details/gtbgqitndy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.xuanzx.com/Article/details/gtuuqvddvp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.yvedp.cn/Article/details/gtanpdynib.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhongyouzk.top/Article/details/gtuarftinc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.gotoacloud.top/Article/details/gtxbcwnsmy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.quarkkingdee.top/Article/details/gthmypqsxt.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.birdmap.top/Article/details/gtdiexkulr.html

[B13] 判断是否为数字
来源：http://dali.shuidangran.top/Article/details/gteqvyjoec.html

Py:   isinstance(x, (int, float))
来源：http://dali.cheryme.top/Article/details/gtbnhslkmv.html

PHP:  is_numeric($x)
来源：http://dali.xziqi.cn/Article/details/gtblsrhxvp.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtvxqfofzo.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yangfankeji.com/Article/details/gteuqfrtlf.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtgvkciooq.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cheryme.top/Article/details/gtrysopvrz.html

Ruby: x.is_a?(Numeric)
来源：http://dali.gogol.net.cn/Article/details/gtqwpofvbk.html

C#:   x is int or double or decimal
来源：http://dali.zhengqikj.top/Article/details/gtfbnhqibc.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gtdjzrehno.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.wangshuangyany.cn/Article/details/gtidsrjslr.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinghuilouyu.cn/Article/details/gtelzysznr.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.tian-w.cn/Article/details/gttzdgaywf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.jqgfzy.top/Article/details/gtdeiwcaet.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.316326.xyz/Article/details/gttlkvnzaz.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuetiantiany.cn/Article/details/gttflbhmnx.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtjctlnjuh.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.316326.xyz/Article/details/gtnvpfekeb.html

[B15] 布尔运算与取反
来源：http://dali.c1oappe.top/Article/details/gtbyzzqfhp.html

Py:   a and b or not c
来源：http://dali.ywan-chungtsiang.top/Article/details/gthiwcpqbx.html

PHP:  $a && $b || !$c
来源：http://dali.yj20258888.top/Article/details/gtsfsygset.html

JS:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtbijfjvlv.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtmjznjlfm.html

Java: a && b || !c
来源：http://dali.yj202588.top/Article/details/gtdcckumvp.html

Go:   a && b || !c
来源：http://dali.yueranfly.top/Article/details/gthvwjzcym.html

Ruby: a && b || !c
来源：http://dali.gzhubu.top/Article/details/gtffhjhykq.html

C#:   a && b || !c
来源：http://dali.sxryk.cn/Article/details/gteaclkkxw.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenjidiqi.icu/Article/details/gtlmuiwkhi.html

Py:   if not data: return
来源：http://dali.aibaodan.cn/Article/details/gtwaneydsf.html

PHP:  if (!$data) { return; }
来源：http://dali.guannengcc.top/Article/details/gtofonifpt.html

JS:   if (!data) return;
来源：http://dali.fengsongda.top/Article/details/gtjtsydpjp.html

TS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gtjxilrbzs.html

Java: if (data == null) return;
来源：http://dali.iojbl.cn/Article/details/gtzhtlpoyp.html

Go:   if data == nil { return }
来源：http://dali.yongpay.top/Article/details/gtrzptcxrj.html

Ruby: return if data.nil?
来源：http://dali.hnqzz.top/Article/details/gtcfvlchxh.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtuozssneb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtliszfuga.html

C. 函数与作用域
来源：http://dali.shuidangran.top/Article/details/gtuztwtmry.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtqtsgfyce.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtebqjgxoq.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtjkzslvhq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gogol.net.cn/Article/details/gtolqsxgai.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.9152youxi.cn/Article/details/gtiybgbqsu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.tianlin.xyz/Article/details/gtxooshtkx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtxkgscawe.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dianchejie.cn/Article/details/gtwhtvxhwe.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yueranfly.top/Article/details/gtpliqfuii.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.aizwys.cn/Article/details/gtnqvmzdjw.html

[C02] 默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtjwrqapta.html

Py:   def greet(name="World"): return name
来源：http://dali.pycfn.com/Article/details/gtmwazvncb.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.nanxinkj.top/Article/details/gtpozzkqsl.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sysykeji.top/Article/details/gtloahqbxf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ehwqpu.com/Article/details/gtiybhsfwk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.sxryk.cn/Article/details/gtcbgemukc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.tian-w.cn/Article/details/gtrhuwuhuw.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtkpoankmb.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hongshengwenyu.top/Article/details/gtparpnnud.html

[C03] 可变参数
来源：http://dali.aibaodan.cn/Article/details/gtmbdouneu.html

Py:   def total(*args): return sum(args)
来源：http://dali.yueranfly.top/Article/details/gtjxjdvtqx.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.ydzc1.top/Article/details/gtnfibwnyd.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yangfankeji.com/Article/details/gtxrcvaejr.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zycfv.cn/Article/details/gtpocjmikf.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtryitnbac.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.sufxvd.cn/Article/details/gteczbjbct.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.zhongyouzk.top/Article/details/gtmotlbrdn.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cheryme.top/Article/details/gtfusucswu.html

[C04] 命名参数 / 关键字参数
来源：http://dali.yj20258888.top/Article/details/gthrtzmyel.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.sweek.top/Article/details/gteozkubic.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhixingplan.top/Article/details/gthvtpnvie.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhoulong.xyz/Article/details/gtstvpbujl.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.kuanghao11.cn/Article/details/gtkfpqierz.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.xuetiantiany.cn/Article/details/gtvtichpim.html

Go:   // 无：用配置结构体参数
来源：http://dali.zhengqikj.top/Article/details/gttpikasgv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtbsilglbt.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gtqzacnwxe.html

[C05] 返回多个值
来源：http://dali.sysykeji.top/Article/details/gtvxlbloio.html

Py:   return a, b
来源：http://dali.meibo888.top/Article/details/gtuwsxbadr.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtxtgdqpqt.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.andypj.xyz/Article/details/gtogzdagny.html

TS:   return { a, b };
来源：http://dali.yj20258.top/Article/details/gtrrrfskdd.html


<!-- 参考信息 -->