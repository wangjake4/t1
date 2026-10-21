代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnxiangtu.top/Article/details/gtqzankixh.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yueranfly.top/Article/details/gtongrqydd.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.xylfe.cn/Article/details/gtqktiujdc.html

[A17] 位运算
来源：http://dali.cucudq.cn/Article/details/gtkmkezfpw.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtyvncurcj.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gttlvhtxkn.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtohfukawh.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.snrcjt.cn/Article/details/gtpsqvnnqo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtrhtlkkrj.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yj20258.top/Article/details/gtvdfrhnfw.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jlsjyb.cn/Article/details/gtbrbhelnq.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hammf.cn/Article/details/gtircjfoty.html

[A18] 字符与 ASCII 码互转
来源：http://dali.chenzaomai.com/Article/details/gtgmebucme.html

Py:   ord("A"); chr(65)
来源：http://dali.nanxuanxn.top/Article/details/gtvxygidwr.html

PHP:  ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gtyratbwsh.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.kuanghao11.cn/Article/details/gtxkygvgca.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zycfv.cn/Article/details/gtfilowxsr.html

Java: (int) 'A'; (char) 65
来源：http://dali.kuanghao11.cn/Article/details/gtgabjwgzz.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.aizwys.cn/Article/details/gtdbfyrqhq.html

Ruby: "A".ord; 65.chr
来源：http://dali.gzhubu.top/Article/details/gtxhmlloiq.html

C#:   (int)'A'; (char)65
来源：http://dali.hongshengwenyu.top/Article/details/gtfibycwnt.html

[A19] 交换两个变量
来源：http://dali.xziqi.cn/Article/details/gtuzyzehva.html

Py:   a, b = b, a
来源：http://dali.sweek.top/Article/details/gtmiuhjvtk.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtpfkasnur.html

JS:   [a, b] = [b, a];
来源：http://dali.dianchejie.cn/Article/details/gtsphoimhp.html

TS:   [a, b] = [b, a];
来源：http://dali.snrcjt.cn/Article/details/gtbvgndzrj.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gtvsmspfew.html

Go:   a, b = b, a
来源：http://dali.cheryme.top/Article/details/gtdemhvdid.html

Ruby: a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gteykwvqmq.html

C#:   (a, b) = (b, a);
来源：http://dali.yongpay.top/Article/details/gtywavkbwr.html

[A20] 读取标准输入
来源：http://dali.yj20258888.top/Article/details/gtvuiryafx.html

Py:   name = input("请输入：")
来源：http://dali.andypj.xyz/Article/details/gtuetkgxxr.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jyoumei.cn/Article/details/gtjniqulmu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.svipenyu.cn/Article/details/gtvehpwomg.html

TS:   // Node.js：readline 模块
来源：http://dali.shangyingyoupin.top/Article/details/gtfsdfvjza.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbqziqypg.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.yangfankeji.com/Article/details/gtiqezdkuj.html

Ruby: gets.chomp
来源：http://dali.ybcxt.top/Article/details/gtaiemttvf.html

C#:   Console.ReadLine();
来源：http://dali.zhaomingkeji.xyz/Article/details/gtipxtnoqy.html

[A21] 保留指定小数位输出
来源：http://dali.tian-w.cn/Article/details/gtistviycl.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gtdxufbebh.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinqigufen.top/Article/details/gtxyuhirzd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuauvdao.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpsmydsa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtnwkfhivp.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.andypj.xyz/Article/details/gttlgxcsqk.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.jqgfzy.top/Article/details/gtdrlkarkv.html

C#:   3.14159.ToString("F2")
来源：http://dali.haohaochexian.top/Article/details/gtdflrxwxh.html

[A22] 获取字符串长度
来源：http://dali.svipenyu.cn/Article/details/gtpcbhassc.html

Py:   len(s)
来源：http://dali.cqqwz.cn/Article/details/gtzqknyovd.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sweek.top/Article/details/gtbwxylatu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.mhx1999.top/Article/details/gtshxbvsjw.html

TS:   s.length
来源：http://dali.zhiwuduotai.top/Article/details/gtxwxhutfs.html

Java: s.length()
来源：http://dali.c1oappe.top/Article/details/gtlrnjuhlc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.tian-w.cn/Article/details/gtmbuphvtt.html

Ruby: s.length
来源：http://dali.fzhhl.top/Article/details/gtkahqvxfq.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gtdzzmyonx.html

[A23] 大小写转换
来源：http://dali.9152youxi.cn/Article/details/gtnttmtluc.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yuanzhike.top/Article/details/gtxsrhtxxn.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yvedp.cn/Article/details/gtdrenryuk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hysaishi.cn/Article/details/gtudmdthbh.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtoxkkggoj.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gtkoeejcok.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258.top/Article/details/gttpcuxhgn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jqgfzy.top/Article/details/gtbowtmmmr.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.sysykeji.top/Article/details/gtylixluyx.html

[A24] 去除首尾空白
来源：http://dali.xuanzx.com/Article/details/gtaaknunqg.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.haohaochexian.top/Article/details/gtgqnxmrgv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhongyouzk.top/Article/details/gtkrhxojgl.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtpdszzhwe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xylfe.cn/Article/details/gtqzvmzbhk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.redwolf501.top/Article/details/gtvtrskxgt.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangdashe.top/Article/details/gtelxthskd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cdnleiting.top/Article/details/gtmvegyayf.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.meibo888.top/Article/details/gtsvkvbvov.html

[A25] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gtksivpbyn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.shuidangran.top/Article/details/gtlblydhcg.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtwvekngdd.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.dashuyun.cn/Article/details/gtqqnuurup.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.jqgufenzy.top/Article/details/gtdvfrsbsc.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.guannengcc.top/Article/details/gtnqjuzbbm.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.daria6918.cn/Article/details/gteiiomrvp.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhongyouzk.top/Article/details/gtisragkbx.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ppjwa.cn/Article/details/gtwawvqfoc.html

[A26] 类型转换总览
来源：http://dali.cucudq.cn/Article/details/gtcswhgmqt.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.hammf.cn/Article/details/gtcpltzaoc.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqgwocss.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hywenlv.cn/Article/details/gtjtnmwdfh.html

TS:   Number() String() Boolean() x as number
来源：http://dali.snrcjt.cn/Article/details/gtmqkwbecj.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.ybcxt.top/Article/details/gtkcrnepbc.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.daxiang520.top/Article/details/gtunxadbil.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrspzmmjh.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.jlsjyb.cn/Article/details/gtlrcpxhpj.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtdgwheayv.html

B. 流程控制
来源：http://dali.yvedp.cn/Article/details/gtnnrbmxbq.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtsvigiiys.html

[B01] 条件判断 if / else
来源：http://dali.nanxuanxn.top/Article/details/gtijrjqtih.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhixingplan.top/Article/details/gtbqadjhtw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtbgzrjfxy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ybcxt.top/Article/details/gtjsxifdra.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtexnhvemn.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.yueranfly.top/Article/details/gtkpzpsfaw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.chenjidiqi.icu/Article/details/gtzboqknlk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.haohaochexian.top/Article/details/gtfbemlavx.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsbyrcxev.html

[B02] 多分支 else if / elif
来源：http://dali.cheryme.top/Article/details/gtxzuiwbbx.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.cqqwz.cn/Article/details/gtillzqyit.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.guowangkeji.top/Article/details/gtweskrptw.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.pengpengdd.cyou/Article/details/gtvkcafemw.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xuetiantiany.cn/Article/details/gtesnihfmb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shangyingyoupin.top/Article/details/gtbwpwkclj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yj20258888.top/Article/details/gtzldnycgb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tian-w.cn/Article/details/gtvqnoaxxw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtaajwhmhz.html

[B03] switch / match / case
来源：http://dali.shzxlz.cn/Article/details/gttpyxyygp.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gtplxgiczu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tian-w.cn/Article/details/gtludbnlxu.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtfihpeizu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sweek.top/Article/details/gtsjhvlmdr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gtukqaatma.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xylfe.cn/Article/details/gtyhlbagtb.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.cucudq.cn/Article/details/gtzivfgufy.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.cashguo.top/Article/details/gtjgshvnbc.html

[B04] for 计数循环
来源：http://dali.pycfn.com/Article/details/gthklbgldr.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtbdjgradl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yj202588.top/Article/details/gtoxgjdksd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtcesthmvp.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.meibo888.top/Article/details/gtsaasvuiz.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.316326.xyz/Article/details/gtmszcmlxq.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.dianchejie.cn/Article/details/gtjkasrxkw.html

Ruby: 10.times { |i| puts i }
来源：http://dali.cashguo.top/Article/details/gtksncydeo.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.vqdsnc.cn/Article/details/gtknvdwcre.html

[B05] 遍历数组 / 列表
来源：http://dali.chenzaomai.com/Article/details/gtgfxaylls.html

Py:   for item in arr: print(item)
来源：http://dali.quarkkingdee.top/Article/details/gtzvugjhtk.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfbczuztp.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jianghu66.top/Article/details/gtmysenwga.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.tianlin.xyz/Article/details/gtijnihtmm.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.guowangkeji.top/Article/details/gtbykwsgih.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.tian-w.cn/Article/details/gtsswckcts.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hywenlv.cn/Article/details/gtvcyzkfwz.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yangfankeji.com/Article/details/gtonrbtncl.html

[B06] 遍历字典 / 对象
来源：http://dali.xylfe.cn/Article/details/gtpiwbmoqk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.bjfxy.top/Article/details/gtxrlgmoxt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gtyaytiisy.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.nwbrower.top/Article/details/gtqdmcfvmo.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtdznqnmyt.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.shangyingyoupin.top/Article/details/gtbijlwrfn.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hywenlv.cn/Article/details/gtfjrlrvvp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinqigfzy.top/Article/details/gtfufunbwr.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.nwbrower.top/Article/details/gtehuuutmr.html

[B07] while 循环
来源：http://dali.ehwqpu.com/Article/details/gtypvbggoz.html

Py:   while i < 10: i += 1
来源：http://dali.smart0.xyz/Article/details/gtrsgtdgwr.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.9152youxi.cn/Article/details/gtyajfevfy.html

JS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtkyzuvuim.html

TS:   while (i < 10) { i++; }
来源：http://dali.snrcjt.cn/Article/details/gtemcymotm.html

Java: while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjaovpdpj.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.yangfankeji.com/Article/details/gtyhjckdsd.html

Ruby: while i < 10; i += 1; end
来源：http://dali.gaohongyu789.top/Article/details/gtrpharsek.html

C#:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtoptposwx.html

[B08] do-while（至少执行一次）
来源：http://dali.hfpthk.cn/Article/details/gthzixtekq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.xuanzx.com/Article/details/gtnmidswdu.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ydzc1.top/Article/details/gtfdxhhjav.html

JS:   do { i++; } while (i < 10);
来源：http://dali.tanke756.top/Article/details/gtzgxzcjuk.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gtyblpmcwk.html

Java: do { i++; } while (i < 10);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshxxmjgi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ybcxt.top/Article/details/gtrmnbsxgu.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.chenjidiqi.icu/Article/details/gtsfeffuka.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gtbebuhoeu.html

[B09] break 与 continue
来源：http://dali.ybcxt.top/Article/details/gtdecxrwpq.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtroawphpi.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.ivvv.top/Article/details/gttkhpftvp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.cheryme.top/Article/details/gtnhtyrkpz.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtjsqtqtde.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtgsqbsbmq.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtbmysefeb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvmhjxsy.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtmdhjleqt.html

[B10] 遍历同时拿索引
来源：http://dali.nanxinkj.top/Article/details/gtoubjzfeg.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.9152youxi.cn/Article/details/gtjaevvvvr.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.havefunace.top/Article/details/gtgeeqeeaf.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.wangdashe.top/Article/details/gtsrqvfhkj.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yj20258888.top/Article/details/gtqvlrmcrs.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtzwsfrcva.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jyoumei.cn/Article/details/gtwmurgvlq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.tianlin.xyz/Article/details/gtmyrdooyh.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj20258888.top/Article/details/gtcefbrwcm.html

[B11] 生成数字序列 / 区间
来源：http://dali.zhiwuduotai.top/Article/details/gtebtqsmit.html

Py:   list(range(0, 10, 2))
来源：http://dali.svipenyu.cn/Article/details/gtbwamgjvi.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtqqzxymof.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fzhhl.top/Article/details/gtzlgjxsxs.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtliigskzu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yangfankeji.com/Article/details/gtlezfcrni.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.jqgfzy.top/Article/details/gtfnjpydhm.html

Ruby: (0...10).step(2).to_a
来源：http://dali.tianlin.xyz/Article/details/gtrdjwosdf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gaohongyu789.top/Article/details/gtxhzdqond.html

[B12] 跳出多层循环
来源：http://dali.hfpthk.cn/Article/details/gtiwvugtkg.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.nanxinkj.top/Article/details/gtcfhiffov.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xuetiantiany.cn/Article/details/gtviyhtahy.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.guowangkeji.top/Article/details/gtbfgqglma.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhoulong.xyz/Article/details/gtacjiskdv.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtfogxznoi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jqgfzy.top/Article/details/gtprokwjxm.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gtdvtizbrr.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.haohaochexian.top/Article/details/gtovjokdey.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtgraghszq.html

Py:   isinstance(x, (int, float))
来源：http://dali.chenzaomai.com/Article/details/gthugrxsdt.html

PHP:  is_numeric($x)
来源：http://dali.yj202588.top/Article/details/gtepovclhm.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhengqikj.top/Article/details/gtmzdzuqyj.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jqgfzy.top/Article/details/gtefreqbms.html

Java: x instanceof Number
来源：http://dali.sysykeji.top/Article/details/gtittgjila.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtsisvjfda.html

Ruby: x.is_a?(Numeric)
来源：http://dali.jqgufenzy.top/Article/details/gtkkomuomq.html

C#:   x is int or double or decimal
来源：http://dali.zycfv.cn/Article/details/gtbsbbkxzb.html

[B14] 判断值是否在集合内
来源：http://dali.smart0.xyz/Article/details/gtncjbysxd.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.chenzaomai.com/Article/details/gtqksrrotp.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtxnumqnip.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gtzwhcvepa.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtuayivslv.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.mhx1999.top/Article/details/gttwblgljt.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.mhx1999.top/Article/details/gtwhsiutfw.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.ydzc1.top/Article/details/gtcofrbacx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dashuyun.cn/Article/details/gtjgbukuim.html

[B15] 布尔运算与取反
来源：http://dali.kuanghao11.cn/Article/details/gtqnbnqcpw.html

Py:   a and b or not c
来源：http://dali.andypj.xyz/Article/details/gtshljtroc.html

PHP:  $a && $b || !$c
来源：http://dali.zhoulong.xyz/Article/details/gtahoynbnu.html

JS:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gtapxqelpy.html

TS:   a && b || !c
来源：http://dali.yvedp.cn/Article/details/gtdcdvvecn.html

Java: a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtjimjwjpp.html

Go:   a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtyluyaebu.html

Ruby: a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gthlfybfqe.html

C#:   a && b || !c
来源：http://dali.jqgfzy.top/Article/details/gtithyouqh.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.feifeiyinyue.top/Article/details/gtnggmzifq.html

Py:   if not data: return
来源：http://dali.xuanzx.com/Article/details/gtviftazeb.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjahfiwv.html

JS:   if (!data) return;
来源：http://dali.ivvv.top/Article/details/gtavchkcbc.html

TS:   if (!data) return;
来源：http://dali.tanke756.top/Article/details/gtfjucbqmp.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtxxlejluo.html

Go:   if data == nil { return }
来源：http://dali.tian-w.cn/Article/details/gttdoatvou.html

Ruby: return if data.nil?
来源：http://dali.sweek.top/Article/details/gtxmizpnfj.html

C#:   if (data == null) return;
来源：http://dali.ybcxt.top/Article/details/gtqotwillg.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtjrgehnng.html

C. 函数与作用域
来源：http://dali.gotoacloud.top/Article/details/gtifkumgvq.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtyazmudku.html

[C01] 定义函数
来源：http://dali.nanxinkj.top/Article/details/gtamhvptwx.html

Py:   def add(a, b): return a + b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrwmyhfk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqbpmpmxb.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.sweek.top/Article/details/gtecynuaxo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuxftxhs.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtqdlzroir.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtriffabyq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.9152youxi.cn/Article/details/gtmgmcdsmv.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.gaohongyu789.top/Article/details/gthkxmmqhv.html

[C02] 默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlmjfjlbq.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtjkvewvwe.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.sysykeji.top/Article/details/gthyibekbm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.bjfxy.top/Article/details/gtkfozwjmg.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtplcidxjk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtytqmqefm.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.chenlongwang.top/Article/details/gtraphduzb.html

Ruby: def greet(name = "World") = name
来源：http://dali.xuanzx.com/Article/details/gtvihxizir.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ivvv.top/Article/details/gtvjwcaizt.html

[C03] 可变参数
来源：http://dali.nanxinkj.top/Article/details/gtokkzxgiy.html

Py:   def total(*args): return sum(args)
来源：http://dali.shuidangran.top/Article/details/gtajprubio.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.smart0.xyz/Article/details/gtlscsoidf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwopestn.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtrdizvuvk.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.iojbl.cn/Article/details/gtzcpmmwbf.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.ybcxt.top/Article/details/gtrieuycfl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.chenjidiqi.icu/Article/details/gtpqbeouxu.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.cashguo.top/Article/details/gtsizlypid.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jiagoushi.top/Article/details/gtxuphxhet.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jlsjyb.cn/Article/details/gtvixiwija.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nwbrower.top/Article/details/gtqzgtwqwh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.hysaishi.cn/Article/details/gtrlhsybms.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.cashguo.top/Article/details/gtsldoykfi.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.yvedp.cn/Article/details/gthwohxgxf.html

Go:   // 无：用配置结构体参数
来源：http://dali.316326.xyz/Article/details/gtpeyibylh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ivvv.top/Article/details/gtqyzsqyhs.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinqigufen.top/Article/details/gtvwdivcxs.html

[C05] 返回多个值
来源：http://dali.ydzc1.top/Article/details/gtspkupbbs.html

Py:   return a, b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwozrda.html

PHP:  return [$a, $b];
来源：http://dali.hnxiangtu.top/Article/details/gtfcpkoqym.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.jianghu66.top/Article/details/gtximwpizc.html

TS:   return { a, b };
来源：http://dali.316326.xyz/Article/details/gtedxnjilw.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.jyoumei.cn/Article/details/gtowjshrpe.html

Go:   return a, b
来源：http://dali.yangfankeji.com/Article/details/gtcjpztgyb.html

Ruby: return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtbpgejlux.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xylfe.cn/Article/details/gtbvsnzqqf.html

[C06] 匿名函数 / lambda
来源：http://dali.birdmap.top/Article/details/gtcphjuatn.html

Py:   square = lambda x: x * x
来源：http://dali.ydzc1.top/Article/details/gtwolzpwdo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.jlsjyb.cn/Article/details/gtaabspsxl.html

JS:   const square = x => x * x;
来源：http://dali.zhixingplan.top/Article/details/gtobqrwbhr.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.aizwys.cn/Article/details/gtiiipqsgo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.xuanzx.com/Article/details/gtikuahnbs.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.aizwys.cn/Article/details/gtwobbpdxo.html

Ruby: square = ->(x) { x * x }
来源：http://dali.cucudq.cn/Article/details/gtxhpigmyv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.daria6918.cn/Article/details/gtvcbdqiyt.html

[C07] 把函数作为参数传入
来源：http://dali.zhiwuduotai.top/Article/details/gtpexsrjnm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtfidrnnca.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.chenzaomai.com/Article/details/gtevimvsum.html


<!-- 参考信息 -->