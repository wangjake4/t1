代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.shangyingyoupin.top/Article/details/gtcepqxjtf.html

[A15] 空值判断与默认值
来源：http://dali.sxryk.cn/Article/details/gtfhzrgraz.html

Py:   value = data or "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtdhmafczo.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.birdmap.top/Article/details/gtcefnkhkv.html

JS:   const value = data ?? "默认值";
来源：http://dali.sxryk.cn/Article/details/gtswcsheuy.html

TS:   const value = data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtgqswqjzo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.haohaochexian.top/Article/details/gtwuyipxns.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.zhiwuduotai.top/Article/details/gtmjtzsvqc.html

Ruby: value = data || "默认值"
来源：http://dali.hammf.cn/Article/details/gtrvgehdoz.html

C#:   var value = data ?? "默认值";
来源：http://dali.yueranfly.top/Article/details/gtsbriwsul.html

[A16] 真假值判断规则
来源：http://dali.tian-w.cn/Article/details/gtwzutqxjt.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.cqqwz.cn/Article/details/gtffvgaqxt.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.shzxlz.cn/Article/details/gtbjjowrkf.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.ppjwa.cn/Article/details/gtjhkmkjbb.html

TS:   if (!x) {}
来源：http://dali.c1oappe.top/Article/details/gtnpossryv.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqwfjqlbo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.hnqzz.top/Article/details/gtbmlydjuw.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.haohaochexian.top/Article/details/gtuntaxrhz.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.ydzc1.top/Article/details/gtqnfzopcf.html

[A17] 位运算
来源：http://dali.daria6918.cn/Article/details/gtimvfryiu.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtdxemjhyc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.c1oappe.top/Article/details/gtcavddzcy.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtdzfobrmi.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.dashuyun.cn/Article/details/gtlihzcsjf.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtwbwfncac.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtotkfdiho.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xylfe.cn/Article/details/gthpitziro.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zycfv.cn/Article/details/gtreocfyjn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cashguo.top/Article/details/gtlkpejpxo.html

Py:   ord("A"); chr(65)
来源：http://dali.xuanzx.com/Article/details/gtcjgmpmfz.html

PHP:  ord("A"); chr(65)
来源：http://dali.hnqzz.top/Article/details/gtinasyyja.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gtjkrihlrj.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gtxfxgruzk.html

Java: (int) 'A'; (char) 65
来源：http://dali.gzhubu.top/Article/details/gttfmaessq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daxiang520.top/Article/details/gterjyjdkq.html

Ruby: "A".ord; 65.chr
来源：http://dali.sxryk.cn/Article/details/gtdyvuswwf.html

C#:   (int)'A'; (char)65
来源：http://dali.quarkkingdee.top/Article/details/gtvxaampgb.html

[A19] 交换两个变量
来源：http://dali.daria6918.cn/Article/details/gtxwiffbat.html

Py:   a, b = b, a
来源：http://dali.wangshuangyany.cn/Article/details/gtjzgclijv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.cucudq.cn/Article/details/gtpcidnhay.html

JS:   [a, b] = [b, a];
来源：http://dali.zhiwuduotai.top/Article/details/gtospuaykq.html

TS:   [a, b] = [b, a];
来源：http://dali.shanyushiyangtech.top/Article/details/gtkkifuvyu.html

Java: int t = a; a = b; b = t;
来源：http://dali.zycfv.cn/Article/details/gtshexxtts.html

Go:   a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtrgpkosxi.html

Ruby: a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtxaejkzse.html

C#:   (a, b) = (b, a);
来源：http://dali.c1oappe.top/Article/details/gtogciftah.html

[A20] 读取标准输入
来源：http://dali.xinyue.icu/Article/details/gtnutklnev.html

Py:   name = input("请输入：")
来源：http://dali.sweek.top/Article/details/gtfrdtbngy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.wangshuangyany.cn/Article/details/gtvfndtkqu.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hysaishi.cn/Article/details/gtrpoxlclr.html

TS:   // Node.js：readline 模块
来源：http://dali.yj202588.top/Article/details/gtlelhztdi.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.fengsongda.top/Article/details/gtizjtjlsy.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.tianlin.xyz/Article/details/gtwqhbfnnc.html

Ruby: gets.chomp
来源：http://dali.snrcjt.cn/Article/details/gtnkvyvpza.html

C#:   Console.ReadLine();
来源：http://dali.iojbl.cn/Article/details/gtccyqoslk.html

[A21] 保留指定小数位输出
来源：http://dali.aizwys.cn/Article/details/gtduttdqcq.html

Py:   f"{3.14159:.2f}"
来源：http://dali.aizwys.cn/Article/details/gtiikxxdbd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtndtdzijv.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtjbxljbtq.html

TS:   (3.14159).toFixed(2)
来源：http://dali.daxiang520.top/Article/details/gtabaesrxa.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gtpibsoxpl.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.chenlongwang.top/Article/details/gtndtyyimu.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gtgweezdcv.html

C#:   3.14159.ToString("F2")
来源：http://dali.birdmap.top/Article/details/gttcpogqpq.html

[A22] 获取字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtxvlahefa.html

Py:   len(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtsohrfxvf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.quarkkingdee.top/Article/details/gtvejxaeuy.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.cdnleiting.top/Article/details/gtpisdbnrt.html

TS:   s.length
来源：http://dali.nanxinkj.top/Article/details/gtjmvikoyr.html

Java: s.length()
来源：http://dali.zhixingplan.top/Article/details/gtzfoziwww.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jlsjyb.cn/Article/details/gtxwmvqtzd.html

Ruby: s.length
来源：http://dali.sweek.top/Article/details/gtnpicsjex.html

C#:   s.Length
来源：http://dali.chenjidiqi.icu/Article/details/gteenxtqbl.html

[A23] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gtkmpklabq.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xinyue.icu/Article/details/gtlhwyzsbs.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jqgfzy.top/Article/details/gtybukmoch.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ydzc1.top/Article/details/gtnorzlfde.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.sxryk.cn/Article/details/gtylwkdkpz.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.andypj.xyz/Article/details/gtvfqyysar.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.wangdashe.top/Article/details/gtxvfaarjp.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtvjrxhhoy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.0kj1m.cn/Article/details/gtkhozzrdn.html

[A24] 去除首尾空白
来源：http://dali.xylfe.cn/Article/details/gtzjtljklw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinqigufen.top/Article/details/gtirhuojke.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.mhx1999.top/Article/details/gtjgbnfeef.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.aizwys.cn/Article/details/gtacifybsi.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtwszxvagw.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gaohongyu789.top/Article/details/gtkqeogequ.html

Go:   strings.TrimSpace(s)
来源：http://dali.c1oappe.top/Article/details/gtpyxougaa.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.andypj.xyz/Article/details/gtgummimen.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.wangshuangyany.cn/Article/details/gtuhahwrso.html

[A25] 字符串比较
来源：http://dali.sweek.top/Article/details/gttviawjpf.html

Py:   s1 == s2; s1 != s2
来源：http://dali.cucudq.cn/Article/details/gtnqsnnean.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.andypj.xyz/Article/details/gtfreadkgj.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hammf.cn/Article/details/gthvfxhhxa.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtxxznlxxk.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtopiavbgd.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtyvnonxwa.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.pengpengdd.cyou/Article/details/gtgmdbgnmi.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gtsecolekj.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gtpcijdaxn.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj202588.top/Article/details/gtthgrwupu.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yvedp.cn/Article/details/gtjvpjyejo.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.meibo888.top/Article/details/gtbbcxebdz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.yuanzhike.top/Article/details/gtxrlmomgk.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.hnqzz.top/Article/details/gttjoxfvqe.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.fzhhl.top/Article/details/gtchzkllrv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.shangyingyoupin.top/Article/details/gtlmbdozau.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.aibaodan.cn/Article/details/gtqxqrhpbj.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtpohptxgf.html

B. 流程控制
来源：http://dali.dianchejie.cn/Article/details/gticizurcu.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtogezydbi.html

[B01] 条件判断 if / else
来源：http://dali.kuanghao11.cn/Article/details/gtogcsvose.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.cashguo.top/Article/details/gtjpgbaozw.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.chenlongwang.top/Article/details/gtvblpijcv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtzdiphkga.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gthkbfjvcl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvqztpsq.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zycfv.cn/Article/details/gttplewqpk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.aibaodan.cn/Article/details/gtoxosknji.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtobvdwcir.html

[B02] 多分支 else if / elif
来源：http://dali.daxiang520.top/Article/details/gtankawgya.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.ybcxt.top/Article/details/gtalypdrpr.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.zdqjudy.top/Article/details/gtyyunhhlf.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtmcperdwp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cdnleiting.top/Article/details/gtunlutdrz.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtayujxzbe.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yuxming.cn/Article/details/gtogduvjnq.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yvedp.cn/Article/details/gthrnxlqnd.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shzxlz.cn/Article/details/gtsskjspai.html

[B03] switch / match / case
来源：http://dali.mhx1999.top/Article/details/gtcmzuslwh.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.svipenyu.cn/Article/details/gtrqvjrtln.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtroeitcdt.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gthoshmrog.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtbqrbrfdu.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtpaudving.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.cucudq.cn/Article/details/gtflrsntrr.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jinqigufen.top/Article/details/gtjxfnkprn.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkaqrugsr.html

[B04] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtyqufgupo.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbvzvxja.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.chenzaomai.com/Article/details/gtjvasnnwv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gthqohynge.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.gotoacloud.top/Article/details/gtseyiwxuo.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvcemvtgb.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdnqskvdg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yongpay.top/Article/details/gttvqhvvmk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.guowangkeji.top/Article/details/gtieszdnin.html

[B05] 遍历数组 / 列表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzxjcaiqd.html

Py:   for item in arr: print(item)
来源：http://dali.yj202588.top/Article/details/gtggjizotm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.0kj1m.cn/Article/details/gtwflywxlx.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.guannengcc.top/Article/details/gtzilizlfu.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.snrcjt.cn/Article/details/gtuuzkysmz.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtvyxcgdgx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.bjfxy.top/Article/details/gthhcqubmb.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gteoktbgde.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.vqdsnc.cn/Article/details/gtytvzasup.html

[B06] 遍历字典 / 对象
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxesaabhv.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.xziqi.cn/Article/details/gtgwvdfzyv.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.bjfxy.top/Article/details/gtwnqgkjnq.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fzhhl.top/Article/details/gtzahwjzco.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.aizwys.cn/Article/details/gtpkczntmm.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.iojbl.cn/Article/details/gtipehvpai.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cheryme.top/Article/details/gtfhzrmpbp.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yvedp.cn/Article/details/gtzlhvgfeo.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xinyue.icu/Article/details/gtsdushuka.html

[B07] while 循环
来源：http://dali.birdmap.top/Article/details/gtsbpadffy.html

Py:   while i < 10: i += 1
来源：http://dali.pengpengdd.cyou/Article/details/gtvbavcibi.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgfzy.top/Article/details/gtsrurjdke.html

JS:   while (i < 10) { i++; }
来源：http://dali.yonumen.top/Article/details/gtruspvwfn.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqzzubnii.html

Java: while (i < 10) { i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsoduhhl.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtssflmsge.html

Ruby: while i < 10; i += 1; end
来源：http://dali.jlsjyb.cn/Article/details/gtpkhicnaa.html

C#:   while (i < 10) { i++; }
来源：http://dali.dashuyun.cn/Article/details/gtsfpduxpl.html

[B08] do-while（至少执行一次）
来源：http://dali.gzhubu.top/Article/details/gtmpchhlne.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gaohongyu789.top/Article/details/gtbbddjtpk.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtlcfqafog.html

JS:   do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtcbupclfc.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yj20258.top/Article/details/gtrsjnmqcr.html

Java: do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gttgozkejq.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hywenlv.cn/Article/details/gtuzjvoymt.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gtbscipvyc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtyzomnkfj.html

[B09] break 与 continue
来源：http://dali.guowangkeji.top/Article/details/gtprygrhkw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tanke756.top/Article/details/gtkbsurdmm.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtzbmkmsfj.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jianghu66.top/Article/details/gtzmzipskw.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyjnbqotr.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.redwolf501.top/Article/details/gtrzawwlfx.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.nwbrower.top/Article/details/gtacshmwiq.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.andypj.xyz/Article/details/gtpadnkjxp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtvkfvcgaz.html

[B10] 遍历同时拿索引
来源：http://dali.yangfankeji.com/Article/details/gthxhqxgru.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.cdnleiting.top/Article/details/gtevsnpati.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xziqi.cn/Article/details/gtyaqhktes.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnyletqu.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gtgtcoruso.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.pycfn.com/Article/details/gtzchlblfg.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.xziqi.cn/Article/details/gtrufbzrnk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gtuvnmxyet.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.snrcjt.cn/Article/details/gtccfqrwzo.html

[B11] 生成数字序列 / 区间
来源：http://dali.meibo888.top/Article/details/gttngpebfx.html

Py:   list(range(0, 10, 2))
来源：http://dali.dashuyun.cn/Article/details/gtfrywuqqr.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtxwshusfl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.wangshuangyany.cn/Article/details/gttgnqnyjv.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemjfcyae.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtjovlvpem.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.andypj.xyz/Article/details/gtiyyncvtw.html

Ruby: (0...10).step(2).to_a
来源：http://dali.snrcjt.cn/Article/details/gtntmbcvcq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhengqikj.top/Article/details/gtfjtsxmuu.html

[B12] 跳出多层循环
来源：http://dali.hnqzz.top/Article/details/gtvdeomtti.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.316326.xyz/Article/details/gtajqowfrh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.daria6918.cn/Article/details/gtnipxjrrf.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.316326.xyz/Article/details/gtyzbxodbp.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtjokqulms.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtyhzwuedn.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtjjebzgzy.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.mhx1999.top/Article/details/gthxttxyso.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.yangfankeji.com/Article/details/gtqrnphwee.html

[B13] 判断是否为数字
来源：http://dali.dashuyun.cn/Article/details/gtcjmafiiy.html

Py:   isinstance(x, (int, float))
来源：http://dali.jinqigfzy.top/Article/details/gtmxkwsirt.html

PHP:  is_numeric($x)
来源：http://dali.gogol.net.cn/Article/details/gtxkjjhcdf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gtpuyxgkut.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cheryme.top/Article/details/gthkknriel.html

Java: x instanceof Number
来源：http://dali.hfpthk.cn/Article/details/gtkxizrnhc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ybcxt.top/Article/details/gtpmwvlcub.html

Ruby: x.is_a?(Numeric)
来源：http://dali.pycfn.com/Article/details/gtplpvktbh.html

C#:   x is int or double or decimal
来源：http://dali.yvedp.cn/Article/details/gtywioujbn.html

[B14] 判断值是否在集合内
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtizbeolyv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.yj20258.top/Article/details/gtljphayek.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.ivvv.top/Article/details/gtjcvrncen.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xinyue.icu/Article/details/gtjzttzdih.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.hywenlv.cn/Article/details/gtkmjowulf.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtslvnkoky.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yanxiufei.cn/Article/details/gtfgoxhmqz.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoyjtsyk.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hfpthk.cn/Article/details/gtmuqkodwn.html

[B15] 布尔运算与取反
来源：http://dali.316326.xyz/Article/details/gthyjisfsm.html

Py:   a and b or not c
来源：http://dali.dianchejie.cn/Article/details/gtygljtvbf.html

PHP:  $a && $b || !$c
来源：http://dali.smart0.xyz/Article/details/gtrsjhpmba.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtzmkacptk.html

TS:   a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtnamwzguc.html

Java: a && b || !c
来源：http://dali.zhoulong.xyz/Article/details/gtdgnsoxox.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjxbvgadl.html

Ruby: a && b || !c
来源：http://dali.yanxiufei.cn/Article/details/gtwszndztd.html

C#:   a && b || !c
来源：http://dali.shanyushiyangtech.top/Article/details/gtvzerpbgi.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shangyingyoupin.top/Article/details/gtwotfosba.html

Py:   if not data: return
来源：http://dali.jinqigufen.top/Article/details/gtctpoadvt.html

PHP:  if (!$data) { return; }
来源：http://dali.iojbl.cn/Article/details/gtjxensonn.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gtavuacbll.html

TS:   if (!data) return;
来源：http://dali.nwbrower.top/Article/details/gtkjqkgfte.html

Java: if (data == null) return;
来源：http://dali.daxiang520.top/Article/details/gtlogmaffq.html

Go:   if data == nil { return }
来源：http://dali.wangdashe.top/Article/details/gtybnuseos.html

Ruby: return if data.nil?
来源：http://dali.jinqigfzy.top/Article/details/gtgtagpfof.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtusxmgpem.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtpejbmifo.html

C. 函数与作用域
来源：http://dali.chenzaomai.com/Article/details/gtfbjabyyf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtojhmtmag.html

[C01] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gtboamcivt.html

Py:   def add(a, b): return a + b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmnuzjdet.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtbaownxlu.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.jyoumei.cn/Article/details/gtngjpqwiq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvnoxmolz.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtqsjvpjrx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.dashuyun.cn/Article/details/gtvlhuwnxm.html

Ruby: def add(a, b); a + b; end
来源：http://dali.smart0.xyz/Article/details/gthwuceekm.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtbtfkkspr.html

[C02] 默认参数
来源：http://dali.fzhhl.top/Article/details/gtagihmoyk.html

Py:   def greet(name="World"): return name
来源：http://dali.andypj.xyz/Article/details/gtuiequfau.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.redwolf501.top/Article/details/gtsylxmloc.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.shuidangran.top/Article/details/gtvydkubks.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.wangdashe.top/Article/details/gtoxqgjcfv.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yuxming.cn/Article/details/gttfyktmbe.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.yangfankeji.com/Article/details/gtnfoegeoh.html

Ruby: def greet(name = "World") = name
来源：http://dali.gotoacloud.top/Article/details/gtulfdxeyh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.gzhubu.top/Article/details/gtmscmpsst.html

[C03] 可变参数
来源：http://dali.shangyingyoupin.top/Article/details/gtmecyfcwi.html

Py:   def total(*args): return sum(args)
来源：http://dali.jyoumei.cn/Article/details/gthtguwiol.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.zdqjudy.top/Article/details/gtweazbfig.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmeeievob.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbqhbpxb.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.kuanghao11.cn/Article/details/gtzijamtlr.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.snrcjt.cn/Article/details/gtkncpaeut.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.daxiang520.top/Article/details/gtysigdhls.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hysaishi.cn/Article/details/gtkfizfoyr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigfzy.top/Article/details/gtwbdzxdzu.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.vqdsnc.cn/Article/details/gtzfqiztas.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.xziqi.cn/Article/details/gtyrertliv.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gtjhglojak.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfvgsmnl.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.sxryk.cn/Article/details/gtabsihyxl.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtpfjvvobz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.xuanzx.com/Article/details/gtbsharwmp.html

C#:   f(a: 1, b: 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqjfcfhfc.html

[C05] 返回多个值
来源：http://dali.zhengqikj.top/Article/details/gtzrlltdfr.html

Py:   return a, b
来源：http://dali.gaohongyu789.top/Article/details/gtoewskcqd.html

PHP:  return [$a, $b];
来源：http://dali.yj202588.top/Article/details/gtegdkcgvh.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.sxryk.cn/Article/details/gtprvqsnov.html

TS:   return { a, b };
来源：http://dali.jinghuilouyu.cn/Article/details/gtkvrhyqwh.html


<!-- 参考信息 -->