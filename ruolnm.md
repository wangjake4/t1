代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yj202588.top/Article/details/gtmkcrazkg.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yj20258.top/Article/details/gtjnhrywix.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.hfpthk.cn/Article/details/gtcmwgtike.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gtwrrfwuer.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hnxiangtu.top/Article/details/gtyeksfjgv.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtfekfewhf.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yj20258888.top/Article/details/gtnfnocjnx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtfbvcwuyi.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtxnzdnyba.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtintllpln.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.bjfxy.top/Article/details/gtyhgqvycw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtlwlhcnnm.html

[A18] 字符与 ASCII 码互转
来源：http://dali.dashuyun.cn/Article/details/gtjdgqgfyt.html

Py:   ord("A"); chr(65)
来源：http://dali.nwbrower.top/Article/details/gtmaijyhpu.html

PHP:  ord("A"); chr(65)
来源：http://dali.xuetiantiany.cn/Article/details/gtowlodmeq.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtrtqkpppg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.gaohongyu789.top/Article/details/gtljcfwamj.html

Java: (int) 'A'; (char) 65
来源：http://dali.snrcjt.cn/Article/details/gtpkoifxnf.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.nanxuanxn.top/Article/details/gtvesymxie.html

Ruby: "A".ord; 65.chr
来源：http://dali.ehwqpu.com/Article/details/gtacswnxgw.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gtisfhburt.html

[A19] 交换两个变量
来源：http://dali.gaohongyu789.top/Article/details/gtvjwggqzx.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtavgwwqyq.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.wangshuangyany.cn/Article/details/gtkwsvoqvm.html

JS:   [a, b] = [b, a];
来源：http://dali.sxryk.cn/Article/details/gtdkunqpmh.html

TS:   [a, b] = [b, a];
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgecttwuu.html

Java: int t = a; a = b; b = t;
来源：http://dali.svipenyu.cn/Article/details/gtiyoglwui.html

Go:   a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtgmficjxt.html

Ruby: a, b = b, a
来源：http://dali.daria6918.cn/Article/details/gtwbxwvqns.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gtltyylnyq.html

[A20] 读取标准输入
来源：http://dali.zycfv.cn/Article/details/gtnlnxmfqy.html

Py:   name = input("请输入：")
来源：http://dali.cqqwz.cn/Article/details/gtcmdbejmi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yongpay.top/Article/details/gtjfwdfwwk.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.zycfv.cn/Article/details/gtonkvfooq.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtttpiboyx.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtumghrasz.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.chenlongwang.top/Article/details/gtdxqtzblo.html

Ruby: gets.chomp
来源：http://dali.wangshuangyany.cn/Article/details/gtideubwmb.html

C#:   Console.ReadLine();
来源：http://dali.gzhubu.top/Article/details/gtkqrhpktu.html

[A21] 保留指定小数位输出
来源：http://dali.ppjwa.cn/Article/details/gttnxlhlds.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj202588.top/Article/details/gtnhcbzwbv.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.haohaochexian.top/Article/details/gtivdqwmdm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklshyuod.html

TS:   (3.14159).toFixed(2)
来源：http://dali.chenlongwang.top/Article/details/gtpvqytfdy.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.cucudq.cn/Article/details/gtevkqhbap.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhengqikj.top/Article/details/gteogmhxap.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xylfe.cn/Article/details/gthtdyxblt.html

C#:   3.14159.ToString("F2")
来源：http://dali.sweek.top/Article/details/gttyyiowif.html

[A22] 获取字符串长度
来源：http://dali.iojbl.cn/Article/details/gtiblrzauk.html

Py:   len(s)
来源：http://dali.guannengcc.top/Article/details/gtrnexjbpk.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinqigfzy.top/Article/details/gtvhehplda.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprxhopef.html

TS:   s.length
来源：http://dali.guannengcc.top/Article/details/gtapzthjjk.html

Java: s.length()
来源：http://dali.havefunace.top/Article/details/gtriaodzqt.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gtdywdqaie.html

Ruby: s.length
来源：http://dali.xuanzx.com/Article/details/gtewvptkcu.html

C#:   s.Length
来源：http://dali.sxryk.cn/Article/details/gtajjbpmyw.html

[A23] 大小写转换
来源：http://dali.tian-w.cn/Article/details/gtagxxdiit.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.dashuyun.cn/Article/details/gtdjswmbvy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.pycfn.com/Article/details/gtmoeofkqd.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtrpiljqgn.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhixingplan.top/Article/details/gtqazjkanm.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cucudq.cn/Article/details/gtafhrxzva.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cqqwz.cn/Article/details/gtsfbrfjca.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.smart0.xyz/Article/details/gtaqmgskzj.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.ppjwa.cn/Article/details/gtghxexnke.html

[A24] 去除首尾空白
来源：http://dali.cashguo.top/Article/details/gtabqdxnhj.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xuanzx.com/Article/details/gthwcflyxw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.tianlin.xyz/Article/details/gthxmswmwo.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gtxfbrraxp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.daxiang520.top/Article/details/gtwenqiznv.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.cheryme.top/Article/details/gthesitipc.html

Go:   strings.TrimSpace(s)
来源：http://dali.yanxiufei.cn/Article/details/gtodihscge.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yj20258888.top/Article/details/gtdqpxxupu.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtuadhhtjq.html

[A25] 字符串比较
来源：http://dali.c1oappe.top/Article/details/gtisvsldvw.html

Py:   s1 == s2; s1 != s2
来源：http://dali.zdqjudy.top/Article/details/gtwupsbufk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.cheryme.top/Article/details/gtnbglmpus.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtzdpxupbt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtgacnpwpq.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.daxiang520.top/Article/details/gtdwcozhrr.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltgzvkte.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.aizwys.cn/Article/details/gtmualxqzd.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yonumen.top/Article/details/gtwgdllups.html

[A26] 类型转换总览
来源：http://dali.kuanghao11.cn/Article/details/gtgjjpjkxa.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hysaishi.cn/Article/details/gtawfxhlll.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.chenlongwang.top/Article/details/gtvgnkhofr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.gaohongyu789.top/Article/details/gtpgshghmj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.redwolf501.top/Article/details/gtbycxraqb.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtqpatbsls.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtrtkxyhbo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.quarkkingdee.top/Article/details/gtqkyrohgp.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmnuhehvd.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtohglhpwy.html

B. 流程控制
来源：http://dali.dashuyun.cn/Article/details/gtacojxlua.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtbjnqtess.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxyaluvq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.andypj.xyz/Article/details/gteqinprtp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.pycfn.com/Article/details/gtbjrwbibi.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jyoumei.cn/Article/details/gtcvhsbxub.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtagsbuvbf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.chenlongwang.top/Article/details/gtrshopphz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ivvv.top/Article/details/gtuhjaxxwq.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xylfe.cn/Article/details/gtzttmafbc.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtaaqendhe.html

[B02] 多分支 else if / elif
来源：http://dali.xuetiantiany.cn/Article/details/gtycjikltg.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.birdmap.top/Article/details/gtxepnkndp.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtascfgkgg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenlongwang.top/Article/details/gtilgswrdk.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnakjgyve.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258888.top/Article/details/gtdbnqwgmh.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cashguo.top/Article/details/gtnwiecgzc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yueranfly.top/Article/details/gtsqryqcpa.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtzlcqxjxa.html

[B03] switch / match / case
来源：http://dali.yueranfly.top/Article/details/gtpbmppwqp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.shangyingyoupin.top/Article/details/gtmglalkad.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.nanxuanxn.top/Article/details/gtiawqtehc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.316326.xyz/Article/details/gtaacvulrf.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtoxqnxekn.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gtiypszbaf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.gaohongyu789.top/Article/details/gtmltrxxdp.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.bjfxy.top/Article/details/gtkigusupn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigfzy.top/Article/details/gtccnpwyzi.html

[B04] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gthqbmrwir.html

Py:   for i in range(10): print(i)
来源：http://dali.zhiwuduotai.top/Article/details/gtwavhricj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gzhubu.top/Article/details/gtaoegubzs.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.wangdashe.top/Article/details/gtzuiybllk.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtbbbnfakw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.sweek.top/Article/details/gtbaocdgmk.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cheryme.top/Article/details/gtpxxeczmj.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ybcxt.top/Article/details/gtxhnjoiah.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqzjnpna.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtkhwiwhyk.html

Py:   for item in arr: print(item)
来源：http://dali.ppjwa.cn/Article/details/gtmzvrryae.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtytsojcpl.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sxryk.cn/Article/details/gtjmhamgoz.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.pengpengdd.cyou/Article/details/gtjmttwlpq.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtpchwjmvu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtngfnhqmy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.shangyingyoupin.top/Article/details/gtfhbgqljs.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sxryk.cn/Article/details/gtqndjrjvi.html

[B06] 遍历字典 / 对象
来源：http://dali.jinqigufen.top/Article/details/gtsnqabqgg.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.jlsjyb.cn/Article/details/gtocgcjplx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdpsudju.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tanke756.top/Article/details/gtkkyrsxpk.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.vqdsnc.cn/Article/details/gtfdwanlbi.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.9152youxi.cn/Article/details/gttjuaduvp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.xuetiantiany.cn/Article/details/gtzehypqdj.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.svipenyu.cn/Article/details/gtgxlmoxdr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.9152youxi.cn/Article/details/gtyetguvak.html

[B07] while 循环
来源：http://dali.cucudq.cn/Article/details/gtxdignpln.html

Py:   while i < 10: i += 1
来源：http://dali.haohaochexian.top/Article/details/gtdftcsuuc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.aibaodan.cn/Article/details/gtseombjxp.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhixingplan.top/Article/details/gtjdsbzivd.html

TS:   while (i < 10) { i++; }
来源：http://dali.nanxuanxn.top/Article/details/gtumsogkjt.html

Java: while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtovjiejir.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhoulong.xyz/Article/details/gtmhozqjre.html

Ruby: while i < 10; i += 1; end
来源：http://dali.havefunace.top/Article/details/gtfgxpgzdb.html

C#:   while (i < 10) { i++; }
来源：http://dali.gaohongyu789.top/Article/details/gtqlgjhyhf.html

[B08] do-while（至少执行一次）
来源：http://dali.zycfv.cn/Article/details/gtmtoetzdx.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.havefunace.top/Article/details/gthpnvumfq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.nanxinkj.top/Article/details/gtyfavwcch.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtudnvydlp.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jiagoushi.top/Article/details/gtmvtimcmo.html

Java: do { i++; } while (i < 10);
来源：http://dali.meibo888.top/Article/details/gtkedhaeds.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenlongwang.top/Article/details/gtovwluuyq.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cheryme.top/Article/details/gtrtexovua.html

C#:   do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtxfgablxh.html

[B09] break 与 continue
来源：http://dali.daxiang520.top/Article/details/gtkbvdvccr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtwzhjcuep.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ydzc1.top/Article/details/gtdjsdjbcd.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yueranfly.top/Article/details/gtksmbikzb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtkbjeuzyz.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtyfvzmpsm.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhiwuduotai.top/Article/details/gtmlmskofg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jqgfzy.top/Article/details/gttkarzaik.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtuatfzbgu.html

[B10] 遍历同时拿索引
来源：http://dali.ydzc1.top/Article/details/gtpjbetyea.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.316326.xyz/Article/details/gtxcjreuof.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.smart0.xyz/Article/details/gtzcznbkkn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ydzc1.top/Article/details/gtifppcuup.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtkaxqorwh.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hywenlv.cn/Article/details/gtwzvwtigg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.sufxvd.cn/Article/details/gttlftzwln.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.svipenyu.cn/Article/details/gtcrwmydho.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.nanxuanxn.top/Article/details/gtrayslwod.html

[B11] 生成数字序列 / 区间
来源：http://dali.sufxvd.cn/Article/details/gtdnqgiblx.html

Py:   list(range(0, 10, 2))
来源：http://dali.0kj1m.cn/Article/details/gtcbgflidt.html

PHP:  range(0, 10, 2);
来源：http://dali.gotoacloud.top/Article/details/gtkpnxuqop.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shzxlz.cn/Article/details/gtlsnazgcr.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sweek.top/Article/details/gtepdgrlzu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gotoacloud.top/Article/details/gtzpztbefo.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yueranfly.top/Article/details/gtafjlxznf.html

Ruby: (0...10).step(2).to_a
来源：http://dali.yueranfly.top/Article/details/gtvhyfokqf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.havefunace.top/Article/details/gtlomiigkm.html

[B12] 跳出多层循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihiyagpd.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.wangshuangyany.cn/Article/details/gtbczvipxz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yj20258888.top/Article/details/gtgtylgohj.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtcnauhaie.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gthedqpxia.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtwnlvkuck.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hywenlv.cn/Article/details/gtyjoakihf.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtlvxkqpvj.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.gogol.net.cn/Article/details/gtwyokotiv.html

[B13] 判断是否为数字
来源：http://dali.gogol.net.cn/Article/details/gtxxflppid.html

Py:   isinstance(x, (int, float))
来源：http://dali.nanxinkj.top/Article/details/gtxqcsrfpj.html

PHP:  is_numeric($x)
来源：http://dali.wangshuangyany.cn/Article/details/gtlbrpjjsh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.xziqi.cn/Article/details/gtawwbfmly.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.guowangkeji.top/Article/details/gtcinbpjlt.html

Java: x instanceof Number
来源：http://dali.sxryk.cn/Article/details/gtedmhecif.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtjlwpimsp.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hongshengwenyu.top/Article/details/gtjdogcudo.html

C#:   x is int or double or decimal
来源：http://dali.zdqjudy.top/Article/details/gtulvwawiy.html

[B14] 判断值是否在集合内
来源：http://dali.316326.xyz/Article/details/gtvhhzaaot.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.quarkkingdee.top/Article/details/gtpkgqtdds.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.haohaochexian.top/Article/details/gtskfpegcb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.0kj1m.cn/Article/details/gtrocbypgd.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sxryk.cn/Article/details/gtvwbcqbis.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.redwolf501.top/Article/details/gthjamttof.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gaohongyu789.top/Article/details/gtoevziepo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jinqigfzy.top/Article/details/gtvdihenqv.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.daxiang520.top/Article/details/gtwzpidyep.html

[B15] 布尔运算与取反
来源：http://dali.zhiwuduotai.top/Article/details/gtwbecrwwi.html

Py:   a and b or not c
来源：http://dali.xinyue.icu/Article/details/gtxisxjtja.html

PHP:  $a && $b || !$c
来源：http://dali.xuanzx.com/Article/details/gtimyrgzop.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gthlyghoas.html

TS:   a && b || !c
来源：http://dali.birdmap.top/Article/details/gtbcfqwxtg.html

Java: a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtonbipmsu.html

Go:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtkhjglriv.html

Ruby: a && b || !c
来源：http://dali.tianlin.xyz/Article/details/gtplsokedj.html

C#:   a && b || !c
来源：http://dali.ppjwa.cn/Article/details/gtbgsrmdxk.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtpxqcyzhi.html

Py:   if not data: return
来源：http://dali.hfpthk.cn/Article/details/gttwvldcpd.html

PHP:  if (!$data) { return; }
来源：http://dali.pycfn.com/Article/details/gtlvcnpaoo.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtytaucwxj.html

TS:   if (!data) return;
来源：http://dali.sxryk.cn/Article/details/gtauanyams.html

Java: if (data == null) return;
来源：http://dali.yangfankeji.com/Article/details/gtexgsplte.html

Go:   if data == nil { return }
来源：http://dali.havefunace.top/Article/details/gtcvvuzrzk.html

Ruby: return if data.nil?
来源：http://dali.nanxuanxn.top/Article/details/gtmawhpeyi.html

C#:   if (data == null) return;
来源：http://dali.pengpengdd.cyou/Article/details/gthekhwofe.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gthgjdqzac.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtnvojerhm.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtpjfolhcy.html

[C01] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtrhmzltui.html

Py:   def add(a, b): return a + b
来源：http://dali.hfpthk.cn/Article/details/gtusrozpxh.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtkboptztq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtvwqihkck.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtxgdfmiup.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ybcxt.top/Article/details/gthcomzebw.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.guowangkeji.top/Article/details/gtgtwhusjo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.gotoacloud.top/Article/details/gtrdkzqxgx.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gtpsvjpvfz.html

[C02] 默认参数
来源：http://dali.jqgfzy.top/Article/details/gtybfeghrv.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtqaueiwmk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.gotoacloud.top/Article/details/gtmvqtjlra.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yanxiufei.cn/Article/details/gteninwvet.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbpdhoxcg.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.xylfe.cn/Article/details/gtxukyslif.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zhoulong.xyz/Article/details/gtjcbcwmhy.html

Ruby: def greet(name = "World") = name
来源：http://dali.cheryme.top/Article/details/gtkydjymjw.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cqqwz.cn/Article/details/gtrqsxtzwn.html

[C03] 可变参数
来源：http://dali.jqgfzy.top/Article/details/gtdsthzajq.html

Py:   def total(*args): return sum(args)
来源：http://dali.ivvv.top/Article/details/gtxiecxatv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.feifeiyinyue.top/Article/details/gtkloinjph.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gogol.net.cn/Article/details/gtxrpajwsv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.gzhubu.top/Article/details/gtjxiudxzu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.yj20258.top/Article/details/gtldjjderh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.zhoulong.xyz/Article/details/gthmicbfek.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtqxkebazk.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtgvhsrywt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hfpthk.cn/Article/details/gtamrvidkx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ydzc1.top/Article/details/gtmdcalcwz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.andypj.xyz/Article/details/gtcrhjctjs.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.cqqwz.cn/Article/details/gtpkofuqkm.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gtvqjzmvwr.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtcvyfefvq.html

Go:   // 无：用配置结构体参数
来源：http://dali.gotoacloud.top/Article/details/gtrixomdmp.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhixingplan.top/Article/details/gttvohmfqh.html

C#:   f(a: 1, b: 2)
来源：http://dali.yuanzhike.top/Article/details/gtjuhitrsj.html

[C05] 返回多个值
来源：http://dali.nanxuanxn.top/Article/details/gtulzkafrp.html

Py:   return a, b
来源：http://dali.zdqjudy.top/Article/details/gtobojexdb.html

PHP:  return [$a, $b];
来源：http://dali.jianghu66.top/Article/details/gtggybodix.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtymcikwbq.html

TS:   return { a, b };
来源：http://dali.shangyingyoupin.top/Article/details/gtcqovrtbp.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.chenjidiqi.icu/Article/details/gtbmgqmqnv.html

Go:   return a, b
来源：http://dali.xuanzx.com/Article/details/gtwzdivzso.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gtfrshiycz.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.ybcxt.top/Article/details/gtbgeukntx.html

[C06] 匿名函数 / lambda
来源：http://dali.hfpthk.cn/Article/details/gtlyxitvkn.html

Py:   square = lambda x: x * x
来源：http://dali.fzhhl.top/Article/details/gtgpgkzcwr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hnxiangtu.top/Article/details/gtvwewjfuk.html

JS:   const square = x => x * x;
来源：http://dali.sufxvd.cn/Article/details/gtighqwebs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.ybcxt.top/Article/details/gtwssdvwoy.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.hysaishi.cn/Article/details/gtwmvblmog.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.daria6918.cn/Article/details/gtqpneqlwk.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ivvv.top/Article/details/gtgcpgvpgy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtmefqgazg.html

[C07] 把函数作为参数传入
来源：http://dali.yj20258888.top/Article/details/gtrxsjdznz.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.bjfxy.top/Article/details/gtqcfzuott.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.xylfe.cn/Article/details/gtsfnjketf.html


<!-- 参考信息 -->