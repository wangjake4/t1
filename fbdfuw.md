代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.gogol.net.cn/Article/details/gtfyofyljl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhijiandao.cn/Article/details/gttekreqxl.html

TS:   if (!x) {}
来源：http://dali.chenlongwang.top/Article/details/gthearxcoq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.meibo888.top/Article/details/gtmggpmehi.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.feifeiyinyue.top/Article/details/gtfmcimwau.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jyoumei.cn/Article/details/gtaaabcfse.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jqgufenzy.top/Article/details/gtfefiyceg.html

[A17] 位运算
来源：http://dali.ybcxt.top/Article/details/gtdogatgng.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtdhxewvxn.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.ywan-chungtsiang.top/Article/details/gthfulkple.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yongpay.top/Article/details/gtukvmpkhb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinghuilouyu.cn/Article/details/gtwdyiadms.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfgjvlxbr.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqjoyipia.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtykgtaxcq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtfpscwrln.html

[A18] 字符与 ASCII 码互转
来源：http://dali.guowangkeji.top/Article/details/gtkrtcllgl.html

Py:   ord("A"); chr(65)
来源：http://dali.ybcxt.top/Article/details/gtucvisqik.html

PHP:  ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtzlpjyyoz.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jyoumei.cn/Article/details/gtvgpkwefr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.xuanzx.com/Article/details/gtqinslqiq.html

Java: (int) 'A'; (char) 65
来源：http://dali.zycfv.cn/Article/details/gtvdawyveg.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.guannengcc.top/Article/details/gtqeunbctl.html

Ruby: "A".ord; 65.chr
来源：http://dali.sysykeji.top/Article/details/gtfqzzqyvn.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gtlptjseuo.html

[A19] 交换两个变量
来源：http://dali.jqgufenzy.top/Article/details/gtveiapivw.html

Py:   a, b = b, a
来源：http://dali.gogol.net.cn/Article/details/gthqsiibef.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.dashuyun.cn/Article/details/gtijzbhgym.html

JS:   [a, b] = [b, a];
来源：http://dali.0kj1m.cn/Article/details/gtywrxthbd.html

TS:   [a, b] = [b, a];
来源：http://dali.xuanzx.com/Article/details/gtgugtcwrn.html

Java: int t = a; a = b; b = t;
来源：http://dali.nwbrower.top/Article/details/gtnyjyzjqj.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtkqklfipc.html

Ruby: a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzxkhhznu.html

C#:   (a, b) = (b, a);
来源：http://dali.cashguo.top/Article/details/gtdghckfod.html

[A20] 读取标准输入
来源：http://dali.cqqwz.cn/Article/details/gtufchzwmc.html

Py:   name = input("请输入：")
来源：http://dali.redwolf501.top/Article/details/gtvllxqvvh.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zycfv.cn/Article/details/gtbmltkixf.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.mhx1999.top/Article/details/gtsxbkaudq.html

TS:   // Node.js：readline 模块
来源：http://dali.yueranfly.top/Article/details/gtxlgtsyxf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yanxiufei.cn/Article/details/gtkzduhkqc.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.xuetiantiany.cn/Article/details/gtrytrwdvk.html

Ruby: gets.chomp
来源：http://dali.smart0.xyz/Article/details/gttklrsypy.html

C#:   Console.ReadLine();
来源：http://dali.ydzc1.top/Article/details/gtpjiqvyoc.html

[A21] 保留指定小数位输出
来源：http://dali.jinqigufen.top/Article/details/gtncjqnfcm.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gtqsijrton.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gteqzsfzid.html

JS:   (3.14159).toFixed(2)
来源：http://dali.yuanzhike.top/Article/details/gtxgmigywd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tianlin.xyz/Article/details/gtqtsvpwvw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtlekgqsbh.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gthmauiicw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.tianlin.xyz/Article/details/gtqszyvihd.html

C#:   3.14159.ToString("F2")
来源：http://dali.yonumen.top/Article/details/gtgqlpiico.html

[A22] 获取字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtouqzyzii.html

Py:   len(s)
来源：http://dali.ehwqpu.com/Article/details/gtqjbasjpa.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.hnxiangtu.top/Article/details/gttoyttmis.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtcsbnbmht.html

TS:   s.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtiptnfq.html

Java: s.length()
来源：http://dali.zhongyouzk.top/Article/details/gtgvxknsbb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkjgvmrwn.html

Ruby: s.length
来源：http://dali.zhixingplan.top/Article/details/gttcyqbene.html

C#:   s.Length
来源：http://dali.shuidangran.top/Article/details/gtgxdvzjyx.html

[A23] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtynrpdmmi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvoiiokk.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.vqdsnc.cn/Article/details/gtrqzkptij.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gotoacloud.top/Article/details/gtcfvgypre.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhoulong.xyz/Article/details/gtlegjyirq.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.aibaodan.cn/Article/details/gtrhqgmxdn.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.xuanzx.com/Article/details/gtvigafdud.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.andypj.xyz/Article/details/gtrhiyzlkl.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.9152youxi.cn/Article/details/gtdhlcfksv.html

[A24] 去除首尾空白
来源：http://dali.svipenyu.cn/Article/details/gtxmbwgyjc.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sxryk.cn/Article/details/gtfpwxhsqm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.haohaochexian.top/Article/details/gtqdaecnvv.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hywenlv.cn/Article/details/gtkzvdejbl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtonxqrsry.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.hysaishi.cn/Article/details/gtxyjhplkv.html

Go:   strings.TrimSpace(s)
来源：http://dali.guowangkeji.top/Article/details/gtuecrigby.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.wangshuangyany.cn/Article/details/gtbcnnivij.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yvedp.cn/Article/details/gtkhksqfsb.html

[A25] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtzcijrdmd.html

Py:   s1 == s2; s1 != s2
来源：http://dali.chenjidiqi.icu/Article/details/gtjzgdvhzk.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shangyingyoupin.top/Article/details/gtqsreaqed.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.zhengqikj.top/Article/details/gtimwsfqdx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.mhx1999.top/Article/details/gtcnylfpqn.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.316326.xyz/Article/details/gtnutunqpw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.gaohongyu789.top/Article/details/gtmzjyqvyl.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtyismnszx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.sweek.top/Article/details/gtavgqykbl.html

[A26] 类型转换总览
来源：http://dali.guannengcc.top/Article/details/gtxuczocgt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.chenzaomai.com/Article/details/gtjixopfgt.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.cucudq.cn/Article/details/gtfmnlafaw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hammf.cn/Article/details/gtaiypmhby.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cdnleiting.top/Article/details/gtyafqmeww.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xinyue.icu/Article/details/gtekcjjvqd.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gtlytzbwjo.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvrxwwmgn.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.hysaishi.cn/Article/details/gtlbddseid.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpxujyyea.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtltrzrt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlnyrcbhj.html

[B01] 条件判断 if / else
来源：http://dali.hongshengwenyu.top/Article/details/gtcfucuice.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gtrcqigvfs.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hfpthk.cn/Article/details/gtjbnnzpkd.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtlpmtpcmq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.haohaochexian.top/Article/details/gtxteeiuml.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.316326.xyz/Article/details/gtlgtzkdhz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhoulong.xyz/Article/details/gtgvahhzqm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jinqigufen.top/Article/details/gtpvpkjmvg.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtltoqbfeg.html

[B02] 多分支 else if / elif
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnbdovsz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj202588.top/Article/details/gtqedipiqz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shuidangran.top/Article/details/gtdqhwpnkg.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.fzhhl.top/Article/details/gtvmsvexna.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinqigufen.top/Article/details/gtisibqelw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtanhvwgso.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.nanxinkj.top/Article/details/gtrtfmysma.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.sweek.top/Article/details/gteggqxzvc.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtabeuokrd.html

[B03] switch / match / case
来源：http://dali.316326.xyz/Article/details/gtbpilnygq.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.sweek.top/Article/details/gtncoewpmu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtigmhwxzr.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gtdwwgixgb.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gthtlrzoou.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jyoumei.cn/Article/details/gtswwimobn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ppjwa.cn/Article/details/gtlirgjuzj.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.haohaochexian.top/Article/details/gttafpmorl.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinqigufen.top/Article/details/gtwbagkoue.html

[B04] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtcronrlli.html

Py:   for i in range(10): print(i)
来源：http://dali.xylfe.cn/Article/details/gtgnfbifky.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtkhpvckcd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.quarkkingdee.top/Article/details/gtyndpbfbp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xylfe.cn/Article/details/gtsnsjhwqs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhoulong.xyz/Article/details/gtexwfgjrl.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.cqqwz.cn/Article/details/gtsunacfxn.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cdnleiting.top/Article/details/gtfbxgords.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtnnjsxtfe.html

[B05] 遍历数组 / 列表
来源：http://dali.wangdashe.top/Article/details/gtkugqmwyz.html

Py:   for item in arr: print(item)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfugqkhjr.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jqgfzy.top/Article/details/gtumhapzil.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdooqjfq.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtunqsfxxd.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtjlwbykqh.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ivvv.top/Article/details/gtldmrhllg.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ydzc1.top/Article/details/gtewptaedv.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmrrdtrdl.html

[B06] 遍历字典 / 对象
来源：http://dali.daria6918.cn/Article/details/gtukjfrddx.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.nanxuanxn.top/Article/details/gtgichqusw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.tanke756.top/Article/details/gtwhjjgumv.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pycfn.com/Article/details/gtmznjrmfv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtavxkjiyt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ppjwa.cn/Article/details/gtmmymviuv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yvedp.cn/Article/details/gtowdncnwt.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gtyvcwnwnc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenzaomai.com/Article/details/gtexltbcku.html

[B07] while 循环
来源：http://dali.vqdsnc.cn/Article/details/gtzpktihpx.html

Py:   while i < 10: i += 1
来源：http://dali.andypj.xyz/Article/details/gtjfzwbyqi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlxzeundt.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtxwdinupc.html

TS:   while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gttsvmluux.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gthwppbfkc.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.nanxuanxn.top/Article/details/gtgwovuoxe.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sysykeji.top/Article/details/gtayxrkxxn.html

C#:   while (i < 10) { i++; }
来源：http://dali.0kj1m.cn/Article/details/gtkcgcicsc.html

[B08] do-while（至少执行一次）
来源：http://dali.fengsongda.top/Article/details/gtpyrrkqov.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.snrcjt.cn/Article/details/gtobvzftoy.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gtgcrdgezh.html

JS:   do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtfhootdbm.html

TS:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gthookrfca.html

Java: do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtcagzcbub.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.meibo888.top/Article/details/gtgguquvmt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.daxiang520.top/Article/details/gtsykxnztl.html

C#:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtyxtzafzv.html

[B09] break 与 continue
来源：http://dali.shuidangran.top/Article/details/gtbwgrzccl.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.fzhhl.top/Article/details/gtcajbqayx.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtraeshvlq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xinyue.icu/Article/details/gtrozlhdxd.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yuxming.cn/Article/details/gtuekbqbqj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.0kj1m.cn/Article/details/gtlzhofsau.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuwgeggg.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.zycfv.cn/Article/details/gtbafefwir.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pycfn.com/Article/details/gtkbdtahto.html

[B10] 遍历同时拿索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtluttzaco.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tian-w.cn/Article/details/gtzsxmwqwz.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmriliyvl.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.meibo888.top/Article/details/gthoypvdpp.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.xuetiantiany.cn/Article/details/gtvqnnzoxf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.ydzc1.top/Article/details/gtcyelioux.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.zhoulong.xyz/Article/details/gtwleobsxf.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.andypj.xyz/Article/details/gtnmqdaxif.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zhijiandao.cn/Article/details/gtckjrjqsa.html

[B11] 生成数字序列 / 区间
来源：http://dali.bjfxy.top/Article/details/gtisqbqrlc.html

Py:   list(range(0, 10, 2))
来源：http://dali.sxryk.cn/Article/details/gtpbfrkysr.html

PHP:  range(0, 10, 2);
来源：http://dali.ydzc1.top/Article/details/gtugmqtjmm.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gtsromxusd.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgfzy.top/Article/details/gtcbvdecwr.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.316326.xyz/Article/details/gthwqciqsa.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sufxvd.cn/Article/details/gtuporrcaz.html

Ruby: (0...10).step(2).to_a
来源：http://dali.jianghu66.top/Article/details/gtazocglsm.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jlsjyb.cn/Article/details/gtgctcmjaa.html

[B12] 跳出多层循环
来源：http://dali.hysaishi.cn/Article/details/gtghskgkwx.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yuxming.cn/Article/details/gtnjcqueya.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.jinqigufen.top/Article/details/gttixisxpu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenzaomai.com/Article/details/gtlrksdrbd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zdqjudy.top/Article/details/gtcfilubyj.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtfyytditj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.tian-w.cn/Article/details/gtqrgyccsw.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.316326.xyz/Article/details/gtemrvyquk.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.fengsongda.top/Article/details/gtoinlcgic.html

[B13] 判断是否为数字
来源：http://dali.zhoulong.xyz/Article/details/gtkofzjpes.html

Py:   isinstance(x, (int, float))
来源：http://dali.zycfv.cn/Article/details/gtepdvnjwe.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtwzdaogsn.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dianchejie.cn/Article/details/gtzlvvsxhr.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.smart0.xyz/Article/details/gtpijmkhyy.html

Java: x instanceof Number
来源：http://dali.xziqi.cn/Article/details/gtqejlethm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.cdnleiting.top/Article/details/gtjsrsisxf.html

Ruby: x.is_a?(Numeric)
来源：http://dali.hysaishi.cn/Article/details/gthzinrhdc.html

C#:   x is int or double or decimal
来源：http://dali.quarkkingdee.top/Article/details/gtqhcfrzrn.html

[B14] 判断值是否在集合内
来源：http://dali.hnxiangtu.top/Article/details/gtyqlnfogh.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtkgobvmku.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ehwqpu.com/Article/details/gtadhhhzfo.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sysykeji.top/Article/details/gtxtrqpfnb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.aibaodan.cn/Article/details/gtymyifkzb.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhiwuduotai.top/Article/details/gtzqdwgwox.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cdnleiting.top/Article/details/gtxmqhirpt.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.jiagoushi.top/Article/details/gtinacsreo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.guannengcc.top/Article/details/gtpmrdxwvr.html

[B15] 布尔运算与取反
来源：http://dali.shzxlz.cn/Article/details/gtgjymnjta.html

Py:   a and b or not c
来源：http://dali.ydzc1.top/Article/details/gtkygsrzit.html

PHP:  $a && $b || !$c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokmofjmj.html

JS:   a && b || !c
来源：http://dali.haohaochexian.top/Article/details/gtulcnkaqy.html

TS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gtkgquejpv.html

Java: a && b || !c
来源：http://dali.havefunace.top/Article/details/gtskxfsriw.html

Go:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtawthfyxv.html

Ruby: a && b || !c
来源：http://dali.hammf.cn/Article/details/gtpvufgzyr.html

C#:   a && b || !c
来源：http://dali.0kj1m.cn/Article/details/gttfbjdmrq.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.havefunace.top/Article/details/gtlrpqytac.html

Py:   if not data: return
来源：http://dali.yangfankeji.com/Article/details/gtsfryaygl.html

PHP:  if (!$data) { return; }
来源：http://dali.haohaochexian.top/Article/details/gtijftutxz.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtgwxebbuj.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gtybqfemir.html

Java: if (data == null) return;
来源：http://dali.tanke756.top/Article/details/gtyvepzymm.html

Go:   if data == nil { return }
来源：http://dali.xziqi.cn/Article/details/gtlohiardz.html

Ruby: return if data.nil?
来源：http://dali.haohaochexian.top/Article/details/gtejyninoe.html

C#:   if (data == null) return;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfvuomab.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gthwichccp.html

C. 函数与作用域
来源：http://dali.quarkkingdee.top/Article/details/gtbmwvpznj.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtdzclcicv.html

[C01] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtuhaubahd.html

Py:   def add(a, b): return a + b
来源：http://dali.yangfankeji.com/Article/details/gtseamumuy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zycfv.cn/Article/details/gtwzhkzzpv.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtkbzantpo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.yonumen.top/Article/details/gtdmshzgpr.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.chenlongwang.top/Article/details/gtysxhxihp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.pycfn.com/Article/details/gtrrxebclh.html

Ruby: def add(a, b); a + b; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfonoanv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.hywenlv.cn/Article/details/gtmzarpsux.html

[C02] 默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtqyiaasef.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtnnzacwpw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtjbucafpn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.cdnleiting.top/Article/details/gtxvprrhvx.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gthqhnkryj.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtfolyaxse.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yj20258.top/Article/details/gtjjyntzts.html

Ruby: def greet(name = "World") = name
来源：http://dali.chenzaomai.com/Article/details/gtysevjkjk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.bjfxy.top/Article/details/gtqaaytkak.html

[C03] 可变参数
来源：http://dali.jianghu66.top/Article/details/gtomgughtb.html

Py:   def total(*args): return sum(args)
来源：http://dali.pengpengdd.cyou/Article/details/gtvfpibqsg.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.nwbrower.top/Article/details/gtzfwttheh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.iojbl.cn/Article/details/gtzhywbyqi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtaxppgpxd.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.daria6918.cn/Article/details/gtruljiape.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtgyfabkkb.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtpzbtexuq.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yueranfly.top/Article/details/gtaytrfewb.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jlsjyb.cn/Article/details/gtkyjpuyky.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.wangshuangyany.cn/Article/details/gtbrfanagt.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.cashguo.top/Article/details/gtjtcyqino.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.wangdashe.top/Article/details/gtbamwtczt.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhengqikj.top/Article/details/gtiqezhrjn.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.chenlongwang.top/Article/details/gtfvlgdcow.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtzzehoovn.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ppjwa.cn/Article/details/gtbrsslzun.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtdgcypvnf.html

[C05] 返回多个值
来源：http://dali.havefunace.top/Article/details/gtrbfrtbnr.html

Py:   return a, b
来源：http://dali.cqqwz.cn/Article/details/gtgnlanntl.html

PHP:  return [$a, $b];
来源：http://dali.havefunace.top/Article/details/gtjrdhgivi.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtsdhtmlis.html

TS:   return { a, b };
来源：http://dali.daria6918.cn/Article/details/gtxfsloiup.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.smart0.xyz/Article/details/gthggxiyog.html

Go:   return a, b
来源：http://dali.wangshuangyany.cn/Article/details/gtitvjpfpl.html

Ruby: return a, b
来源：http://dali.redwolf501.top/Article/details/gtjpqtdqqc.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtlomuilzk.html

[C06] 匿名函数 / lambda
来源：http://dali.yvedp.cn/Article/details/gtvffoaqxh.html

Py:   square = lambda x: x * x
来源：http://dali.jinqigufen.top/Article/details/gtnfkaqlwn.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xuanzx.com/Article/details/gtjlrjsmzn.html

JS:   const square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtetbguyhr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtqxkffved.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.tianlin.xyz/Article/details/gtcdjosggd.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yongpay.top/Article/details/gtohhxxvjh.html

Ruby: square = ->(x) { x * x }
来源：http://dali.dianchejie.cn/Article/details/gthwlrkfdv.html


<!-- 参考信息 -->