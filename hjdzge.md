代发 wailian999

C#:   // 单行；/* 多行 */
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjapgtkwh.html

[A15] 空值判断与默认值
来源：http://dali.mhx1999.top/Article/details/gticfiqtes.html

Py:   value = data or "默认值"
来源：http://dali.0kj1m.cn/Article/details/gtrnxidpar.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.jiagoushi.top/Article/details/gtpevhetgt.html

JS:   const value = data ?? "默认值";
来源：http://dali.zhongyouzk.top/Article/details/gtwnzlbaqw.html

TS:   const value = data ?? "默认值";
来源：http://dali.ppjwa.cn/Article/details/gtharevvnv.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.hnqzz.top/Article/details/gtdgiaadvw.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.tanke756.top/Article/details/gtcdviwvwp.html

Ruby: value = data || "默认值"
来源：http://dali.9152youxi.cn/Article/details/gtyqhhrwry.html

C#:   var value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtxjhlntkf.html

[A16] 真假值判断规则
来源：http://dali.svipenyu.cn/Article/details/gtgmoxrybl.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.fzhhl.top/Article/details/gtmfibkayj.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.316326.xyz/Article/details/gtjkmhljjw.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.kuanghao11.cn/Article/details/gtheqgycff.html

TS:   if (!x) {}
来源：http://dali.pengpengdd.cyou/Article/details/gtxudkjvcc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.dashuyun.cn/Article/details/gtlpwyrxvw.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jiagoushi.top/Article/details/gtmsvtvmde.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.yongpay.top/Article/details/gtgmhuwgdc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gthwmwzrqc.html

[A17] 位运算
来源：http://dali.havefunace.top/Article/details/gtzkrxrvik.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtppasbdqs.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtsjeqktex.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.feifeiyinyue.top/Article/details/gtelqwsyjm.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gthagmrttg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tian-w.cn/Article/details/gtilwnqbjd.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtuadvfcii.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.iojbl.cn/Article/details/gtreaqeuis.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.dianchejie.cn/Article/details/gtyupguour.html

[A18] 字符与 ASCII 码互转
来源：http://dali.ybcxt.top/Article/details/gtuqoxlhya.html

Py:   ord("A"); chr(65)
来源：http://dali.gogol.net.cn/Article/details/gtnqfsqfwb.html

PHP:  ord("A"); chr(65)
来源：http://dali.ivvv.top/Article/details/gtlxqsxghk.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtnksiynhr.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhoulong.xyz/Article/details/gttoncxorx.html

Java: (int) 'A'; (char) 65
来源：http://dali.sxryk.cn/Article/details/gtmncdkvio.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhongyouzk.top/Article/details/gtzmgazdwh.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gthafavgjb.html

C#:   (int)'A'; (char)65
来源：http://dali.hammf.cn/Article/details/gtuzvzosel.html

[A19] 交换两个变量
来源：http://dali.zhixingplan.top/Article/details/gtrlygeacg.html

Py:   a, b = b, a
来源：http://dali.jiagoushi.top/Article/details/gtcbaqhspj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.guowangkeji.top/Article/details/gtisqhsokx.html

JS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtppwkntfx.html

TS:   [a, b] = [b, a];
来源：http://dali.jqgfzy.top/Article/details/gtdznygxyk.html

Java: int t = a; a = b; b = t;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuyltjml.html

Go:   a, b = b, a
来源：http://dali.aibaodan.cn/Article/details/gtjswegwpm.html

Ruby: a, b = b, a
来源：http://dali.sweek.top/Article/details/gtgbcdzjdb.html

C#:   (a, b) = (b, a);
来源：http://dali.meibo888.top/Article/details/gtkvmwxwoe.html

[A20] 读取标准输入
来源：http://dali.gaohongyu789.top/Article/details/gteiyoktvg.html

Py:   name = input("请输入：")
来源：http://dali.zycfv.cn/Article/details/gtvfnsltwm.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jqgufenzy.top/Article/details/gtdpddpoaj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.svipenyu.cn/Article/details/gtejuxskam.html

TS:   // Node.js：readline 模块
来源：http://dali.ehwqpu.com/Article/details/gthamygpav.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hywenlv.cn/Article/details/gtmrydmdqx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.ybcxt.top/Article/details/gtqrhkfgdd.html

Ruby: gets.chomp
来源：http://dali.zhongyouzk.top/Article/details/gtcnkwrnwj.html

C#:   Console.ReadLine();
来源：http://dali.xylfe.cn/Article/details/gtultcbxda.html

[A21] 保留指定小数位输出
来源：http://dali.fengsongda.top/Article/details/gtpxwdmkng.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shuidangran.top/Article/details/gtyvmclcfb.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jyoumei.cn/Article/details/gtpaxlfjsq.html

JS:   (3.14159).toFixed(2)
来源：http://dali.birdmap.top/Article/details/gtbabyiloe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtstnnlyux.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtlgusngdx.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtnahfszen.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yangfankeji.com/Article/details/gthtdmepqp.html

C#:   3.14159.ToString("F2")
来源：http://dali.aibaodan.cn/Article/details/gteqeqasst.html

[A22] 获取字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtgkwduhnw.html

Py:   len(s)
来源：http://dali.hfpthk.cn/Article/details/gtozxekmut.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.daxiang520.top/Article/details/gtjilxydlg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.shangyingyoupin.top/Article/details/gtrhjtkvww.html

TS:   s.length
来源：http://dali.aizwys.cn/Article/details/gthzxjpaed.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gtupdtgitg.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gtcqfzsitb.html

Ruby: s.length
来源：http://dali.yj20258.top/Article/details/gtkvrchdfu.html

C#:   s.Length
来源：http://dali.jinqigufen.top/Article/details/gtkgkciyru.html

[A23] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtelloprzm.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhengqikj.top/Article/details/gtxmnzlwjc.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.smart0.xyz/Article/details/gtahdogkxk.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtdbhuufka.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtnjootfyr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yonumen.top/Article/details/gtosgtvkee.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtgzolmcsz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.tanke756.top/Article/details/gtlcajmzry.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yj202588.top/Article/details/gtyknzjplj.html

[A24] 去除首尾空白
来源：http://dali.yj202588.top/Article/details/gtqlmawyeb.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.cheryme.top/Article/details/gtioecxsnd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jianghu66.top/Article/details/gtakklcret.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhoulong.xyz/Article/details/gtcnepfztm.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gtaoiemspb.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shanyushiyangtech.top/Article/details/gtonpreqsg.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gthmsdcpcj.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.shuidangran.top/Article/details/gtmklbbrum.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekakvoig.html

[A25] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtyuekujzz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gtecrtitqf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.yonumen.top/Article/details/gthxmyhfga.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hfpthk.cn/Article/details/gtixtmkwjn.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.kuanghao11.cn/Article/details/gtmkmcwbnj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gotoacloud.top/Article/details/gtepsofjzh.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.mhx1999.top/Article/details/gtrdxlnvmy.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsjwaxwpr.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.guowangkeji.top/Article/details/gthplkewxb.html

[A26] 类型转换总览
来源：http://dali.daxiang520.top/Article/details/gtwxktgytw.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yanxiufei.cn/Article/details/gttrahygzh.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrvwetlx.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtkiljaimb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.nanxuanxn.top/Article/details/gtplytdbyd.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtnbqpglta.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhengqikj.top/Article/details/gtppmhxfra.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.xuanzx.com/Article/details/gtoxmrrjui.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhengqikj.top/Article/details/gtczueemrv.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbfujzjrr.html

B. 流程控制
来源：http://dali.cqqwz.cn/Article/details/gtvhvavseu.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfknxrhj.html

[B01] 条件判断 if / else
来源：http://dali.guannengcc.top/Article/details/gtfronjrkw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.tian-w.cn/Article/details/gtdcstzqnp.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.snrcjt.cn/Article/details/gtrixszqjv.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtsidvygis.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.shuidangran.top/Article/details/gtzawggcrj.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gtfknjgtnt.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.wangshuangyany.cn/Article/details/gtlgschezc.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.smart0.xyz/Article/details/gtfsaqdwfw.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.c1oappe.top/Article/details/gtmpqjgjxa.html

[B02] 多分支 else if / elif
来源：http://dali.ppjwa.cn/Article/details/gtnlqesfgm.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xuanzx.com/Article/details/gtadzfhmmz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtryrxoeia.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gtzkmsctiu.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gtoarjnvbg.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gttxkoyhsg.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gtzmvxrdlm.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.yonumen.top/Article/details/gtonfdxelz.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangdashe.top/Article/details/gtvwfbyugo.html

[B03] switch / match / case
来源：http://dali.9152youxi.cn/Article/details/gtvzbtgahs.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zhijiandao.cn/Article/details/gtdqkdzdwe.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.quarkkingdee.top/Article/details/gtvhiybbeh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinqigfzy.top/Article/details/gtkzrppanh.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxfrtoca.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.shuidangran.top/Article/details/gtqqgagugn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yuxming.cn/Article/details/gtgpmuqyuc.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.jqgufenzy.top/Article/details/gtqknqjkfq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.guannengcc.top/Article/details/gtpypczbto.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtqrenejid.html

Py:   for i in range(10): print(i)
来源：http://dali.bjfxy.top/Article/details/gtgkashxvs.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yanxiufei.cn/Article/details/gtafscxbhg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.havefunace.top/Article/details/gticykgznt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yangfankeji.com/Article/details/gtvxfyiogx.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aibaodan.cn/Article/details/gtsheayzvp.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtehdfbzmq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yuxming.cn/Article/details/gtltzxelai.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yj20258.top/Article/details/gtiqmsvwmb.html

[B05] 遍历数组 / 列表
来源：http://dali.birdmap.top/Article/details/gtjsqxomis.html

Py:   for item in arr: print(item)
来源：http://dali.jianghu66.top/Article/details/gtyrgdgdus.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.redwolf501.top/Article/details/gtubznqavn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.yonumen.top/Article/details/gtbrgfvned.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj20258888.top/Article/details/gtlkwxcblo.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.yuxming.cn/Article/details/gtttjjldbp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jqgfzy.top/Article/details/gtszfwoaso.html

Ruby: arr.each { |item| puts item }
来源：http://dali.cashguo.top/Article/details/gtkpvuktdn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.zhixingplan.top/Article/details/gtkqaixbnz.html

[B06] 遍历字典 / 对象
来源：http://dali.aizwys.cn/Article/details/gtwukwoxoc.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.sysykeji.top/Article/details/gtawxnqkrx.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hnqzz.top/Article/details/gtiduqzcrf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.feifeiyinyue.top/Article/details/gtihnrfcji.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hnqzz.top/Article/details/gtbzfbektv.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtonsflafl.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sufxvd.cn/Article/details/gtkfxfnryq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yonumen.top/Article/details/gtfxebuzmj.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ivvv.top/Article/details/gtnpfeyguo.html

[B07] while 循环
来源：http://dali.yuanzhike.top/Article/details/gtrimnyxjb.html

Py:   while i < 10: i += 1
来源：http://dali.vqdsnc.cn/Article/details/gtodcpaaln.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gtnbcfhgue.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqhazhier.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtphcnhqrg.html

Java: while (i < 10) { i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtijhtmjlb.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhengqikj.top/Article/details/gtjsvpouag.html

Ruby: while i < 10; i += 1; end
来源：http://dali.hongshengwenyu.top/Article/details/gtenjjoqxi.html

C#:   while (i < 10) { i++; }
来源：http://dali.haohaochexian.top/Article/details/gtuewgtdtr.html

[B08] do-while（至少执行一次）
来源：http://dali.yongpay.top/Article/details/gtbizmtsmd.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.hnqzz.top/Article/details/gtiakjdnbt.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtmshtqxvn.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtvfyruuri.html

TS:   do { i++; } while (i < 10);
来源：http://dali.9152youxi.cn/Article/details/gtjzmvrmju.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtussnepkg.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.pycfn.com/Article/details/gtxlicwxxl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtbzbmimug.html

C#:   do { i++; } while (i < 10);
来源：http://dali.ybcxt.top/Article/details/gtcnqhkuxc.html

[B09] break 与 continue
来源：http://dali.fengsongda.top/Article/details/gtdwjkvwrp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.9152youxi.cn/Article/details/gthqfhuzyq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.hfpthk.cn/Article/details/gtjyhvmwyw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gthyybkbpg.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.pengpengdd.cyou/Article/details/gtedhjvilv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtkiwjdpjd.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.jinqigfzy.top/Article/details/gtxtgfoucp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhpzdzla.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xylfe.cn/Article/details/gtaheelokl.html

[B10] 遍历同时拿索引
来源：http://dali.shangyingyoupin.top/Article/details/gtznqfwyiv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhengqikj.top/Article/details/gtzboavjne.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shzxlz.cn/Article/details/gtumyqekkk.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yangfankeji.com/Article/details/gtfbhyedbn.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.sweek.top/Article/details/gtglnzgxyo.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hnxiangtu.top/Article/details/gtovvefhin.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.quarkkingdee.top/Article/details/gtztczzqmo.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.haohaochexian.top/Article/details/gtbmenppzw.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.gzhubu.top/Article/details/gtobxklcox.html

[B11] 生成数字序列 / 区间
来源：http://dali.yj20258888.top/Article/details/gtlccnlhjd.html

Py:   list(range(0, 10, 2))
来源：http://dali.yuxming.cn/Article/details/gtgqebrear.html

PHP:  range(0, 10, 2);
来源：http://dali.tian-w.cn/Article/details/gtftuxonvo.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtqvkmwtak.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdxpanhv.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yvedp.cn/Article/details/gtwwmhrcht.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xuetiantiany.cn/Article/details/gtmstmtaus.html

Ruby: (0...10).step(2).to_a
来源：http://dali.meibo888.top/Article/details/gtmlwvvyst.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.wangdashe.top/Article/details/gtrbrnhnkc.html

[B12] 跳出多层循环
来源：http://dali.daria6918.cn/Article/details/gtbmogkgzy.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.kuanghao11.cn/Article/details/gtdcjvzqzm.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gthydsnhzb.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gtwlrmgfas.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.cashguo.top/Article/details/gtqwhhumnc.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.yuxming.cn/Article/details/gtfvfvtali.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.dianchejie.cn/Article/details/gtjxxhthho.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.ybcxt.top/Article/details/gtdpxeowqc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.zycfv.cn/Article/details/gtktewywgp.html

[B13] 判断是否为数字
来源：http://dali.svipenyu.cn/Article/details/gtnwbrtaju.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtsggrmmqj.html

PHP:  is_numeric($x)
来源：http://dali.yueranfly.top/Article/details/gtpnydmhxf.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtrhlwqzlv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jiagoushi.top/Article/details/gttyazmioo.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmnbpnuvl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.chenjidiqi.icu/Article/details/gtbaqcrvni.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cqqwz.cn/Article/details/gtxmgehqrg.html

C#:   x is int or double or decimal
来源：http://dali.sweek.top/Article/details/gtklswalqa.html

[B14] 判断值是否在集合内
来源：http://dali.gotoacloud.top/Article/details/gtknzvbdot.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.xuanzx.com/Article/details/gtrabsrsan.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj20258888.top/Article/details/gtoyrerntt.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.zycfv.cn/Article/details/gturvowosh.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.birdmap.top/Article/details/gtdyuoyywn.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.havefunace.top/Article/details/gtkugegyei.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.nanxuanxn.top/Article/details/gtlhbiyiwd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtimnnmyhx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzawyvnxs.html

[B15] 布尔运算与取反
来源：http://dali.mhx1999.top/Article/details/gtqbwjelwr.html

Py:   a and b or not c
来源：http://dali.jinqigfzy.top/Article/details/gtlfgpniqu.html

PHP:  $a && $b || !$c
来源：http://dali.ydzc1.top/Article/details/gtkuvlahcc.html

JS:   a && b || !c
来源：http://dali.yangfankeji.com/Article/details/gtzutxtxeb.html

TS:   a && b || !c
来源：http://dali.shzxlz.cn/Article/details/gtjngjcwyg.html

Java: a && b || !c
来源：http://dali.hfpthk.cn/Article/details/gtwmimzaov.html

Go:   a && b || !c
来源：http://dali.havefunace.top/Article/details/gtbacfovcv.html

Ruby: a && b || !c
来源：http://dali.zhongyouzk.top/Article/details/gtzhjbndho.html

C#:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtczmcearf.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shuidangran.top/Article/details/gtmanaajco.html

Py:   if not data: return
来源：http://dali.shzxlz.cn/Article/details/gtmjcthmuj.html

PHP:  if (!$data) { return; }
来源：http://dali.yanxiufei.cn/Article/details/gtizckrdar.html

JS:   if (!data) return;
来源：http://dali.dianchejie.cn/Article/details/gtqxcxhwyf.html

TS:   if (!data) return;
来源：http://dali.dashuyun.cn/Article/details/gtwgusnmda.html

Java: if (data == null) return;
来源：http://dali.jinqigufen.top/Article/details/gtblhlougi.html

Go:   if data == nil { return }
来源：http://dali.jyoumei.cn/Article/details/gtpenwhdys.html

Ruby: return if data.nil?
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmmmkpnh.html

C#:   if (data == null) return;
来源：http://dali.hywenlv.cn/Article/details/gtwvzxquyl.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtlhepjosv.html

C. 函数与作用域
来源：http://dali.mhx1999.top/Article/details/gtbjrohnsa.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtxtzzmhgh.html

[C01] 定义函数
来源：http://dali.jinqigfzy.top/Article/details/gtnmwfksfa.html

Py:   def add(a, b): return a + b
来源：http://dali.daxiang520.top/Article/details/gtkekjogjx.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.tian-w.cn/Article/details/gtuodwrrta.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.hnxiangtu.top/Article/details/gtgjiycgvq.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.quarkkingdee.top/Article/details/gtisoyqnos.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.pycfn.com/Article/details/gtdnpcjznv.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zhijiandao.cn/Article/details/gtbzwtampn.html

Ruby: def add(a, b); a + b; end
来源：http://dali.feifeiyinyue.top/Article/details/gtaxuzzior.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.316326.xyz/Article/details/gtzujnwrbt.html

[C02] 默认参数
来源：http://dali.guowangkeji.top/Article/details/gtungrbcme.html

Py:   def greet(name="World"): return name
来源：http://dali.guannengcc.top/Article/details/gtsavuaavx.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigfzy.top/Article/details/gthfbqnfwg.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvqrkaclh.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.hywenlv.cn/Article/details/gtojyceebe.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.yj20258888.top/Article/details/gtiiypcqwa.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jqgfzy.top/Article/details/gtqloqjotu.html

Ruby: def greet(name = "World") = name
来源：http://dali.dianchejie.cn/Article/details/gtxfanetdk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.zhengqikj.top/Article/details/gtgkbsyrwh.html

[C03] 可变参数
来源：http://dali.wangshuangyany.cn/Article/details/gtofifgbnr.html

Py:   def total(*args): return sum(args)
来源：http://dali.hysaishi.cn/Article/details/gtcqpomxdw.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.haohaochexian.top/Article/details/gtlwtjqgdn.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.sufxvd.cn/Article/details/gtevxwlqfi.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtkzsimltj.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ybcxt.top/Article/details/gtbmulbjzg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.xuetiantiany.cn/Article/details/gtnlhkqfjm.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.sweek.top/Article/details/gtpczsarxt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.guannengcc.top/Article/details/gtroevyqoq.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtwkekdslz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtivhlrovw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.nanxinkj.top/Article/details/gtjlavjaaz.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.svipenyu.cn/Article/details/gtftqqbbav.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.redwolf501.top/Article/details/gtgksxdubs.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinghuilouyu.cn/Article/details/gtythlshvv.html

Go:   // 无：用配置结构体参数
来源：http://dali.aizwys.cn/Article/details/gtjnetjlen.html

Ruby: f(a: 1, b: 2)
来源：http://dali.gogol.net.cn/Article/details/gthilpczas.html

C#:   f(a: 1, b: 2)
来源：http://dali.kuanghao11.cn/Article/details/gtxpkseodl.html

[C05] 返回多个值
来源：http://dali.haohaochexian.top/Article/details/gtwydnqhkd.html

Py:   return a, b
来源：http://dali.mhx1999.top/Article/details/gtsmfeinga.html

PHP:  return [$a, $b];
来源：http://dali.jqgfzy.top/Article/details/gtuxgoyzwo.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.gaohongyu789.top/Article/details/gthketyxic.html

TS:   return { a, b };
来源：http://dali.jiagoushi.top/Article/details/gtfglfrwfk.html


<!-- 参考信息 -->