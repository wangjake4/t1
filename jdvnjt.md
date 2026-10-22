代发 wailian999

JS:   const value = data ?? "默认值";
来源：http://dali.jqgufenzy.top/Article/details/gtmjmqhdjy.html

TS:   const value = data ?? "默认值";
来源：http://dali.hammf.cn/Article/details/gtirmiwcha.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.haohaochexian.top/Article/details/gtirkmkgju.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.pengpengdd.cyou/Article/details/gtwybremgf.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gtjaznsmbe.html

C#:   var value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtyetodhga.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gtflagbafg.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.tanke756.top/Article/details/gtggnbwces.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.aizwys.cn/Article/details/gtbxsqbkmw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.yanxiufei.cn/Article/details/gtmdfvhpxj.html

TS:   if (!x) {}
来源：http://dali.jiagoushi.top/Article/details/gtkxrdewwa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.9152youxi.cn/Article/details/gtjdvwjtce.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.9152youxi.cn/Article/details/gtgxgvsfux.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sxryk.cn/Article/details/gtdmsopdax.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.gzhubu.top/Article/details/gtrqcnhvvm.html

[A17] 位运算
来源：http://dali.yueranfly.top/Article/details/gtczrptpxd.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ppjwa.cn/Article/details/gtzyrpdpzr.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.iojbl.cn/Article/details/gtoczvbhus.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtcjzgjwmx.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtspnikpdw.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtnfmuqhhc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtfeyfahvu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pycfn.com/Article/details/gtzgrqhjck.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtavufeezn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtfmtkhvvt.html

Py:   ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtaucfpkow.html

PHP:  ord("A"); chr(65)
来源：http://dali.vqdsnc.cn/Article/details/gtmibcuibx.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jinqigfzy.top/Article/details/gtfduehwna.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhxhsjos.html

Java: (int) 'A'; (char) 65
来源：http://dali.guowangkeji.top/Article/details/gtlpxobmwq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yj20258.top/Article/details/gtojdwdjxo.html

Ruby: "A".ord; 65.chr
来源：http://dali.tian-w.cn/Article/details/gtjoxctfdk.html

C#:   (int)'A'; (char)65
来源：http://dali.haohaochexian.top/Article/details/gtcqnslopo.html

[A19] 交换两个变量
来源：http://dali.shangyingyoupin.top/Article/details/gtximkfoim.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtghohywpp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.tanke756.top/Article/details/gtqavrxrya.html

JS:   [a, b] = [b, a];
来源：http://dali.fengsongda.top/Article/details/gtzlkbohjn.html

TS:   [a, b] = [b, a];
来源：http://dali.sufxvd.cn/Article/details/gtvyqktcqb.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhengqikj.top/Article/details/gtfzvnpqvv.html

Go:   a, b = b, a
来源：http://dali.daxiang520.top/Article/details/gtbrklliqo.html

Ruby: a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gtfhsztazt.html

C#:   (a, b) = (b, a);
来源：http://dali.kuanghao11.cn/Article/details/gtwosrhxsc.html

[A20] 读取标准输入
来源：http://dali.guannengcc.top/Article/details/gtiqiibwux.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gtexdmskwn.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ehwqpu.com/Article/details/gtvkuhqvqi.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.c1oappe.top/Article/details/gtpefofdaf.html

TS:   // Node.js：readline 模块
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjaqxpxkk.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.shanyushiyangkeji.top/Article/details/gttieoeldf.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvaoudwb.html

Ruby: gets.chomp
来源：http://dali.9152youxi.cn/Article/details/gtsoeqrbnx.html

C#:   Console.ReadLine();
来源：http://dali.ehwqpu.com/Article/details/gtbglpmxse.html

[A21] 保留指定小数位输出
来源：http://dali.nanxinkj.top/Article/details/gtzgozffrq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.hnxiangtu.top/Article/details/gtkvgclzus.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gttxvkmbyn.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpukafhsh.html

TS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtvhxlldzr.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtmrpzudvs.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.kuanghao11.cn/Article/details/gtiydawedq.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhongyouzk.top/Article/details/gtybpldhzu.html

C#:   3.14159.ToString("F2")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlwbwozgl.html

[A22] 获取字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtklmolisc.html

Py:   len(s)
来源：http://dali.cashguo.top/Article/details/gtzrpxtabm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.shzxlz.cn/Article/details/gtzxxybiyg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.iojbl.cn/Article/details/gtkvegpvrn.html

TS:   s.length
来源：http://dali.smart0.xyz/Article/details/gtmrjeauqh.html

Java: s.length()
来源：http://dali.nwbrower.top/Article/details/gtwwbqkbtn.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.gzhubu.top/Article/details/gtyrknhfez.html

Ruby: s.length
来源：http://dali.sweek.top/Article/details/gteifoxvsq.html

C#:   s.Length
来源：http://dali.jiagoushi.top/Article/details/gtwlrfnixv.html

[A23] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtrlcwhbrv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.gaohongyu789.top/Article/details/gtnrvujkkc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jyoumei.cn/Article/details/gtlzeypvbv.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.aizwys.cn/Article/details/gtmbxuuqzd.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtlubcuyxw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtnqtpxoex.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuanzhike.top/Article/details/gtilztgzdv.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yj20258888.top/Article/details/gtbdvwpeuk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.gzhubu.top/Article/details/gtdsjnrlxr.html

[A24] 去除首尾空白
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunixoiyc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gtpusgyalo.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.dianchejie.cn/Article/details/gtfnraffcf.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtmlbkrptr.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.jyoumei.cn/Article/details/gtvkrhxtsw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhijiandao.cn/Article/details/gtfdcxncdp.html

Go:   strings.TrimSpace(s)
来源：http://dali.yuxming.cn/Article/details/gtctfmpwou.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.pengpengdd.cyou/Article/details/gtfxlzhsuh.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xinyue.icu/Article/details/gtduqmjvsm.html

[A25] 字符串比较
来源：http://dali.xziqi.cn/Article/details/gtubdksavm.html

Py:   s1 == s2; s1 != s2
来源：http://dali.dashuyun.cn/Article/details/gtvcihyzbi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ydzc1.top/Article/details/gtzuyickpe.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcxqyknnf.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtspgmkhie.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigfzy.top/Article/details/gtlgwzfnqp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.vqdsnc.cn/Article/details/gtdiualwhz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jinqigfzy.top/Article/details/gtagwezuat.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtljfbnmio.html

[A26] 类型转换总览
来源：http://dali.jqgfzy.top/Article/details/gtbmjsdkyl.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjlqwbnom.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.zycfv.cn/Article/details/gtqhblbwqf.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.yj202588.top/Article/details/gtvudrqyaw.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gogol.net.cn/Article/details/gtmeclpreq.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gthdmawyln.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.havefunace.top/Article/details/gtobpceyqc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.9152youxi.cn/Article/details/gturfjsmnk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yj202588.top/Article/details/gthpttzrhu.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtfbzocmeu.html

B. 流程控制
来源：http://dali.yuanzhike.top/Article/details/gtyixqyynv.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtvfehunsw.html

[B01] 条件判断 if / else
来源：http://dali.chenjidiqi.icu/Article/details/gtooztzwjy.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aibaodan.cn/Article/details/gtssfdiqkc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jiagoushi.top/Article/details/gtevzgindh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotiptgfa.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhongyouzk.top/Article/details/gthkvllxnc.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.andypj.xyz/Article/details/gtxxapzsij.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.havefunace.top/Article/details/gthitwqtaz.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cucudq.cn/Article/details/gtezzdaydt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtemmtiwmf.html

[B02] 多分支 else if / elif
来源：http://dali.xziqi.cn/Article/details/gtjfotzwrd.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.wangshuangyany.cn/Article/details/gtkizvpxov.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtklffabrs.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtzetqiakn.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.haohaochexian.top/Article/details/gtbwfqmyec.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtkwjlawem.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aibaodan.cn/Article/details/gtwftzgfih.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gtjxcyimzr.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtqozjwwkq.html

[B03] switch / match / case
来源：http://dali.hfpthk.cn/Article/details/gtvmgfjyfr.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.nanxinkj.top/Article/details/gtyqccykyn.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigufen.top/Article/details/gtoybjwwpx.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hysaishi.cn/Article/details/gtlfygcuiq.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gtxrtfgtxo.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daria6918.cn/Article/details/gtilfnstjg.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ybcxt.top/Article/details/gtkooslozo.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.chenzaomai.com/Article/details/gtrnlcgzhr.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.sxryk.cn/Article/details/gtlyvijjqo.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtwtsvaioh.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtbaagnzvb.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xuetiantiany.cn/Article/details/gturmcwkyd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyhtyvoe.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gtortxgerr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.ppjwa.cn/Article/details/gtpmtjcrof.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.yvedp.cn/Article/details/gtxwaoagqr.html

Ruby: 10.times { |i| puts i }
来源：http://dali.svipenyu.cn/Article/details/gtwrpyltbu.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtfothabce.html

[B05] 遍历数组 / 列表
来源：http://dali.nanxinkj.top/Article/details/gtnflcxjpe.html

Py:   for item in arr: print(item)
来源：http://dali.chenjidiqi.icu/Article/details/gticzrpywa.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yj202588.top/Article/details/gtamstsjki.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.havefunace.top/Article/details/gterbghgjs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tanke756.top/Article/details/gtwevxmhov.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.daxiang520.top/Article/details/gtodupujbh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.guannengcc.top/Article/details/gtxazfibxo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhiwuduotai.top/Article/details/gteljscpik.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.redwolf501.top/Article/details/gtayixpjtf.html

[B06] 遍历字典 / 对象
来源：http://dali.vqdsnc.cn/Article/details/gtwnrjzyba.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.svipenyu.cn/Article/details/gtfinsxxxs.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtixncsptm.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.havefunace.top/Article/details/gtdjhiwdfs.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.ivvv.top/Article/details/gtlbkwwqur.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.hammf.cn/Article/details/gtvpgkfesp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gtxnxdhpqh.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.nanxuanxn.top/Article/details/gtogydhryh.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtexkowbac.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtjsechpyg.html

Py:   while i < 10: i += 1
来源：http://dali.kuanghao11.cn/Article/details/gtvnhifmhs.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtylptknep.html

JS:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtfwtydncb.html

TS:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gthwiacfmq.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtitubwkhj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sxryk.cn/Article/details/gtefqzhpmn.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtafamskgn.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtzghzhdrn.html

[B08] do-while（至少执行一次）
来源：http://dali.xuetiantiany.cn/Article/details/gtxtxvfyco.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jyoumei.cn/Article/details/gtmrfdukuf.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.yj202588.top/Article/details/gtnpyrwvca.html

JS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gtdllzefzv.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtkcxtuuzj.html

Java: do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtrpdndnmr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.wangshuangyany.cn/Article/details/gtfoaijwtz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ehwqpu.com/Article/details/gtedtcesmp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhongyouzk.top/Article/details/gthmqwqrlc.html

[B09] break 与 continue
来源：http://dali.tianlin.xyz/Article/details/gtxoworugl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258888.top/Article/details/gtroaqreja.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfmyhylfx.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gtxfrreezk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fengsongda.top/Article/details/gtgqveaocb.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daria6918.cn/Article/details/gtorjssksc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.redwolf501.top/Article/details/gtlgjtqaxq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinqigufen.top/Article/details/gteyngpngs.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtzxfbuvbl.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtsgxnksnx.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangdashe.top/Article/details/gtqsilbuqy.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.jinqigufen.top/Article/details/gtpvykdlzn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.chenlongwang.top/Article/details/gtrpojccii.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hammf.cn/Article/details/gtbyjjruge.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ivvv.top/Article/details/gtspmmxjms.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj20258.top/Article/details/gtgjrzsepa.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.meibo888.top/Article/details/gtyremdgvu.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.pycfn.com/Article/details/gtgzoyjsqz.html

[B11] 生成数字序列 / 区间
来源：http://dali.jiagoushi.top/Article/details/gtyooyeldx.html

Py:   list(range(0, 10, 2))
来源：http://dali.havefunace.top/Article/details/gtqkgafnbw.html

PHP:  range(0, 10, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtlwdfhrut.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwggscyx.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.sufxvd.cn/Article/details/gtjtdsgdeg.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.gogol.net.cn/Article/details/gtxbpmwzmk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.ehwqpu.com/Article/details/gtoukmmnbi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.ydzc1.top/Article/details/gtxxrsrhqx.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.cdnleiting.top/Article/details/gtklqhcdbs.html

[B12] 跳出多层循环
来源：http://dali.hnxiangtu.top/Article/details/gtvwjmuzrx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.fengsongda.top/Article/details/gtfrhwfpdn.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cashguo.top/Article/details/gtyovmjpul.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gthrvajexw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gtyddmsome.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtvltcwlys.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gtvghprcqw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yj202588.top/Article/details/gtncaropoq.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzmwoirh.html

[B13] 判断是否为数字
来源：http://dali.feifeiyinyue.top/Article/details/gteidrxuqn.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtoxqqdmaq.html

PHP:  is_numeric($x)
来源：http://dali.gzhubu.top/Article/details/gtlvjmgwdn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.bjfxy.top/Article/details/gtzdcsfqyu.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.kuanghao11.cn/Article/details/gtxewhexee.html

Java: x instanceof Number
来源：http://dali.jinqigufen.top/Article/details/gtobkhqkun.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.gzhubu.top/Article/details/gthdddexai.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gtrslbiyri.html

C#:   x is int or double or decimal
来源：http://dali.snrcjt.cn/Article/details/gtiuawnxwg.html

[B14] 判断值是否在集合内
来源：http://dali.jlsjyb.cn/Article/details/gtzkfcbtbm.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.meibo888.top/Article/details/gtlzdkcjkv.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.nanxuanxn.top/Article/details/gtqesagdnx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.guowangkeji.top/Article/details/gtcfvazcax.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gtobkkqmyx.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtjhtsggkm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gogol.net.cn/Article/details/gthjxeghlo.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtyqvwtbnc.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtdprdydge.html

[B15] 布尔运算与取反
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdqlqhhug.html

Py:   a and b or not c
来源：http://dali.cdnleiting.top/Article/details/gtantsmjrz.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gthbzwinau.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtrcjurlpc.html

TS:   a && b || !c
来源：http://dali.hammf.cn/Article/details/gtlbhaqger.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtesyxldru.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjbhvvye.html

Ruby: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtesvguczz.html

C#:   a && b || !c
来源：http://dali.sysykeji.top/Article/details/gticcngbmy.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtmfinqjnt.html

Py:   if not data: return
来源：http://dali.xuetiantiany.cn/Article/details/gtpkydloym.html

PHP:  if (!$data) { return; }
来源：http://dali.nwbrower.top/Article/details/gtrjfaawbs.html

JS:   if (!data) return;
来源：http://dali.fzhhl.top/Article/details/gtqkirxqnv.html

TS:   if (!data) return;
来源：http://dali.cheryme.top/Article/details/gtueidmifj.html

Java: if (data == null) return;
来源：http://dali.tian-w.cn/Article/details/gtvnnlllue.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtawigbavm.html

Ruby: return if data.nil?
来源：http://dali.yongpay.top/Article/details/gtuquxescu.html

C#:   if (data == null) return;
来源：http://dali.mhx1999.top/Article/details/gtijyvemjl.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gthappxwgq.html

C. 函数与作用域
来源：http://dali.dashuyun.cn/Article/details/gtzqzfubpc.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmtvnzbpv.html

[C01] 定义函数
来源：http://dali.chenzaomai.com/Article/details/gtexvpltak.html

Py:   def add(a, b): return a + b
来源：http://dali.quarkkingdee.top/Article/details/gthimhinrm.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.ivvv.top/Article/details/gtdzymvxew.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258.top/Article/details/gtdumirzzf.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtohcoggrn.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ydzc1.top/Article/details/gtczkonutg.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwnyhvotm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yuanzhike.top/Article/details/gthivncbfw.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gttjcpylzk.html

[C02] 默认参数
来源：http://dali.9152youxi.cn/Article/details/gtxouexibz.html

Py:   def greet(name="World"): return name
来源：http://dali.yonumen.top/Article/details/gtxxmbobxk.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yuanzhike.top/Article/details/gtpadqqhus.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzevletz.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.tianlin.xyz/Article/details/gtzgrcctzt.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.9152youxi.cn/Article/details/gtddvucdhb.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yueranfly.top/Article/details/gtunwbwndf.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtkxwnxito.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.feifeiyinyue.top/Article/details/gthivofuif.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtwmorshea.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtxztrsxix.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.fengsongda.top/Article/details/gtghusptcq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.guowangkeji.top/Article/details/gtudkwjkxg.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xinyue.icu/Article/details/gttxdpzgob.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.vqdsnc.cn/Article/details/gttfcxhzqw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yj20258.top/Article/details/gtqrphvqmp.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangdashe.top/Article/details/gtehjifzzz.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sxryk.cn/Article/details/gtgopnavqq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.pengpengdd.cyou/Article/details/gtxefwarmp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yuxming.cn/Article/details/gtwwtjpdca.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.ivvv.top/Article/details/gtiklokvhy.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hnqzz.top/Article/details/gthxolwfno.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.c1oappe.top/Article/details/gtykzqxolf.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yj20258888.top/Article/details/gtolljwpso.html

Go:   // 无：用配置结构体参数
来源：http://dali.ybcxt.top/Article/details/gtfitumdmb.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jyoumei.cn/Article/details/gtnmuvktqb.html

C#:   f(a: 1, b: 2)
来源：http://dali.chenzaomai.com/Article/details/gtpalncxhu.html

[C05] 返回多个值
来源：http://dali.mhx1999.top/Article/details/gtgkykgzga.html

Py:   return a, b
来源：http://dali.hnqzz.top/Article/details/gtrrpnezqn.html

PHP:  return [$a, $b];
来源：http://dali.jiagoushi.top/Article/details/gtrbumczwy.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jqgufenzy.top/Article/details/gtbhnmvmht.html

TS:   return { a, b };
来源：http://dali.shzxlz.cn/Article/details/gtzfguspgy.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ydzc1.top/Article/details/gtqcjkloew.html

Go:   return a, b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvmwnegt.html

Ruby: return a, b
来源：http://dali.snrcjt.cn/Article/details/gttppbanbq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhixingplan.top/Article/details/gtokphjwde.html


<!-- 参考信息 -->