代发 wailian999

TS:   // 单行；/* 多行 */
来源：http://dali.ivvv.top/Article/details/gtrxlmemtd.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.bjfxy.top/Article/details/gtgubcpicy.html

Go:   // 单行；/* 多行 */
来源：http://dali.yj20258888.top/Article/details/gtthisjodp.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.nwbrower.top/Article/details/gtxmrwatmu.html

C#:   // 单行；/* 多行 */
来源：http://dali.sufxvd.cn/Article/details/gtbhlcqlhs.html

[A15] 空值判断与默认值
来源：http://dali.shangyingyoupin.top/Article/details/gtriosmbyj.html

Py:   value = data or "默认值"
来源：http://dali.hammf.cn/Article/details/gteszeafdt.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.aibaodan.cn/Article/details/gtnqduekmg.html

JS:   const value = data ?? "默认值";
来源：http://dali.jlsjyb.cn/Article/details/gtmlcqmlfn.html

TS:   const value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtlkmghgoo.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.zhoulong.xyz/Article/details/gtgydjkxrr.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.guannengcc.top/Article/details/gtchyfvzpk.html

Ruby: value = data || "默认值"
来源：http://dali.yangfankeji.com/Article/details/gtsngskhut.html

C#:   var value = data ?? "默认值";
来源：http://dali.gotoacloud.top/Article/details/gtkywfzlht.html

[A16] 真假值判断规则
来源：http://dali.yanxiufei.cn/Article/details/gtpulqeuzm.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.xuetiantiany.cn/Article/details/gtapqylhrb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zycfv.cn/Article/details/gtulqklsij.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.tianlin.xyz/Article/details/gtekhnnisn.html

TS:   if (!x) {}
来源：http://dali.hammf.cn/Article/details/gtftplxvep.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.c1oappe.top/Article/details/gtievwsqxa.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.xziqi.cn/Article/details/gtduwcxqci.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.xuanzx.com/Article/details/gthjecktzo.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.fzhhl.top/Article/details/gtuxltbocl.html

[A17] 位运算
来源：http://dali.shuidangran.top/Article/details/gtidgdhywm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwtbknhcz.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gttpnuhehv.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtrocffyjd.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gteakxmtwn.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ybcxt.top/Article/details/gtuifgxjrl.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgpidddhz.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigfzy.top/Article/details/gtltrpnfem.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtpsmgbhex.html

[A18] 字符与 ASCII 码互转
来源：http://dali.xinyue.icu/Article/details/gtnsuipiji.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gtylnmnoxg.html

PHP:  ord("A"); chr(65)
来源：http://dali.aizwys.cn/Article/details/gtugshkqsj.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yangfankeji.com/Article/details/gtsrwftqvi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yuxming.cn/Article/details/gtkpqxzpxh.html

Java: (int) 'A'; (char) 65
来源：http://dali.gotoacloud.top/Article/details/gtgfapouiu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjftiipdr.html

Ruby: "A".ord; 65.chr
来源：http://dali.vqdsnc.cn/Article/details/gtqrgtnejy.html

C#:   (int)'A'; (char)65
来源：http://dali.daria6918.cn/Article/details/gtnookvgge.html

[A19] 交换两个变量
来源：http://dali.redwolf501.top/Article/details/gtsuerwtph.html

Py:   a, b = b, a
来源：http://dali.jqgfzy.top/Article/details/gteymgfiyw.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.vqdsnc.cn/Article/details/gtlzpcwfbi.html

JS:   [a, b] = [b, a];
来源：http://dali.jinqigfzy.top/Article/details/gtiaplvbro.html

TS:   [a, b] = [b, a];
来源：http://dali.aizwys.cn/Article/details/gtzdlwslay.html

Java: int t = a; a = b; b = t;
来源：http://dali.yanxiufei.cn/Article/details/gtpemmjhgn.html

Go:   a, b = b, a
来源：http://dali.jlsjyb.cn/Article/details/gtyqiqsnjl.html

Ruby: a, b = b, a
来源：http://dali.xuanzx.com/Article/details/gtighpvufh.html

C#:   (a, b) = (b, a);
来源：http://dali.zhengqikj.top/Article/details/gtmigckgnu.html

[A20] 读取标准输入
来源：http://dali.daxiang520.top/Article/details/gtsltmhlzo.html

Py:   name = input("请输入：")
来源：http://dali.yvedp.cn/Article/details/gtedbzwlzx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yj202588.top/Article/details/gtvxlosqlp.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.fzhhl.top/Article/details/gtlavgrefm.html

TS:   // Node.js：readline 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyagdlbm.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yuxming.cn/Article/details/gtevonkxvl.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhijiandao.cn/Article/details/gtavcdjqga.html

Ruby: gets.chomp
来源：http://dali.316326.xyz/Article/details/gtivuijwxp.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtbliuegkc.html

[A21] 保留指定小数位输出
来源：http://dali.dashuyun.cn/Article/details/gtxbrzdkpe.html

Py:   f"{3.14159:.2f}"
来源：http://dali.havefunace.top/Article/details/gtpodytryu.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.gotoacloud.top/Article/details/gtdvquuvev.html

JS:   (3.14159).toFixed(2)
来源：http://dali.zycfv.cn/Article/details/gtkckgenpg.html

TS:   (3.14159).toFixed(2)
来源：http://dali.yanxiufei.cn/Article/details/gtpuiavrvk.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.sufxvd.cn/Article/details/gtexooooir.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtcvpuocqr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ybcxt.top/Article/details/gtkkcnkcvx.html

C#:   3.14159.ToString("F2")
来源：http://dali.nwbrower.top/Article/details/gtkdjswigt.html

[A22] 获取字符串长度
来源：http://dali.dianchejie.cn/Article/details/gtbyazkowi.html

Py:   len(s)
来源：http://dali.nwbrower.top/Article/details/gteihrclff.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gzhubu.top/Article/details/gthkxpezgh.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.hysaishi.cn/Article/details/gtmhqjtzna.html

TS:   s.length
来源：http://dali.andypj.xyz/Article/details/gtxgbatuwd.html

Java: s.length()
来源：http://dali.guowangkeji.top/Article/details/gtshfcatus.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.jianghu66.top/Article/details/gtjfpbhvlc.html

Ruby: s.length
来源：http://dali.daxiang520.top/Article/details/gtgknwgsiu.html

C#:   s.Length
来源：http://dali.hammf.cn/Article/details/gtnukgfdit.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gtntrohyoi.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.kuanghao11.cn/Article/details/gtnfyaoouy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.sxryk.cn/Article/details/gtnooqhxim.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gtjiksuwqz.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.nanxinkj.top/Article/details/gtcfwpvbiu.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtunyvbqeg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hywenlv.cn/Article/details/gtpcjxkkzz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.9152youxi.cn/Article/details/gtjvcdzerk.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jqgfzy.top/Article/details/gtdjatjwej.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtuixbyyqu.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hysaishi.cn/Article/details/gtoiurntqf.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jqgufenzy.top/Article/details/gtpaxpknfm.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.cheryme.top/Article/details/gtjnbrpsvl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.guowangkeji.top/Article/details/gtrnahdlae.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgfzy.top/Article/details/gtcduaohsq.html

Go:   strings.TrimSpace(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtfefzkkib.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.cashguo.top/Article/details/gtketxxcvb.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yuanzhike.top/Article/details/gtvnfkebii.html

[A25] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtuuftzavs.html

Py:   s1 == s2; s1 != s2
来源：http://dali.havefunace.top/Article/details/gtsnmklqhy.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.zycfv.cn/Article/details/gtqiuewzig.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.aizwys.cn/Article/details/gtlozirsfi.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.birdmap.top/Article/details/gtlmqncthg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hywenlv.cn/Article/details/gtsioyiufn.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtklsyyfbz.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.nwbrower.top/Article/details/gtxfvmveph.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuxming.cn/Article/details/gtyjllivsy.html

[A26] 类型转换总览
来源：http://dali.yj20258.top/Article/details/gtjoiywzkh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ehwqpu.com/Article/details/gtyvvtwjkb.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hnqzz.top/Article/details/gtibhfejan.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.shzxlz.cn/Article/details/gtauumpjow.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gturawsqcn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhongyouzk.top/Article/details/gtzsrdxyfi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cqqwz.cn/Article/details/gtbggsdadi.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.meibo888.top/Article/details/gtwmfzanpb.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zhoulong.xyz/Article/details/gtdyqkhhkt.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtiynaipmh.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gtfiozflrq.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtqrnkfjub.html

[B01] 条件判断 if / else
来源：http://dali.yuxming.cn/Article/details/gttjspwico.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pengpengdd.cyou/Article/details/gtqjjzgwou.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.vqdsnc.cn/Article/details/gtovomsoow.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtydpgabdk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtvwxudwos.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gtjkvmsixs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hammf.cn/Article/details/gtqefgcjvg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.fzhhl.top/Article/details/gtaqapgtzt.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.gaohongyu789.top/Article/details/gtsgsvdeso.html

[B02] 多分支 else if / elif
来源：http://dali.yj20258888.top/Article/details/gtjlrzxuzb.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtqfyujxnl.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtyqttdbhy.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.0kj1m.cn/Article/details/gttpmhfmsr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.meibo888.top/Article/details/gtvzeeixil.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtudroabjb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvzrsbbrg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangshuangyany.cn/Article/details/gtlaxrwitk.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.birdmap.top/Article/details/gtfmvdgqbg.html

[B03] switch / match / case
来源：http://dali.gotoacloud.top/Article/details/gtdpirtvri.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yj20258.top/Article/details/gtkampsubh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.gotoacloud.top/Article/details/gtdnfhgydi.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.c1oappe.top/Article/details/gtqdqldyxd.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gtiusrzhtr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.andypj.xyz/Article/details/gtdbxmnayy.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jqgfzy.top/Article/details/gtavjyrevt.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.yj20258888.top/Article/details/gtgxayvcwb.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.zhongyouzk.top/Article/details/gtfsadnghi.html

[B04] for 计数循环
来源：http://dali.cashguo.top/Article/details/gtueiwosmx.html

Py:   for i in range(10): print(i)
来源：http://dali.yuanzhike.top/Article/details/gtfqqcwgix.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zdqjudy.top/Article/details/gtlkwtkqfr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yuxming.cn/Article/details/gtjyqeqyzv.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.ivvv.top/Article/details/gtlqptkxmm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gttnssircr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.andypj.xyz/Article/details/gttvrzhqeq.html

Ruby: 10.times { |i| puts i }
来源：http://dali.havefunace.top/Article/details/gtfpdqzntk.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.gaohongyu789.top/Article/details/gtlbqxjfcj.html

[B05] 遍历数组 / 列表
来源：http://dali.yuanzhike.top/Article/details/gtsxfofpzl.html

Py:   for item in arr: print(item)
来源：http://dali.jlsjyb.cn/Article/details/gtzzeytcdf.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.bjfxy.top/Article/details/gthoryuica.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtainqnefa.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.haohaochexian.top/Article/details/gtegocpotx.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.aibaodan.cn/Article/details/gtiisyfpky.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ybcxt.top/Article/details/gtezwyhevm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.hongshengwenyu.top/Article/details/gtcjjinntg.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.havefunace.top/Article/details/gtpdrtguat.html

[B06] 遍历字典 / 对象
来源：http://dali.xuanzx.com/Article/details/gtjmvfoqda.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ybcxt.top/Article/details/gtmohasnls.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.daxiang520.top/Article/details/gtplgpfmzl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.fengsongda.top/Article/details/gtuokexfxz.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jqgufenzy.top/Article/details/gtpeaudnno.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cdnleiting.top/Article/details/gtxtqphryj.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.dashuyun.cn/Article/details/gtwuatootu.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfiyucjlb.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.meibo888.top/Article/details/gtyqddwfru.html

[B07] while 循环
来源：http://dali.snrcjt.cn/Article/details/gtqalpsmkm.html

Py:   while i < 10: i += 1
来源：http://dali.9152youxi.cn/Article/details/gtknpgbvpp.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gtbqeispyx.html

JS:   while (i < 10) { i++; }
来源：http://dali.xylfe.cn/Article/details/gturhqtvfw.html

TS:   while (i < 10) { i++; }
来源：http://dali.fengsongda.top/Article/details/gtkeycdycv.html

Java: while (i < 10) { i++; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvhlosbtr.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.jqgfzy.top/Article/details/gtjlwczack.html

Ruby: while i < 10; i += 1; end
来源：http://dali.fzhhl.top/Article/details/gtuwfbcvwt.html

C#:   while (i < 10) { i++; }
来源：http://dali.nanxinkj.top/Article/details/gtiwchdzta.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtqqhrzoga.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.shanyushiyangkeji.top/Article/details/gteaziewix.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.tanke756.top/Article/details/gtxmimpoqi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zycfv.cn/Article/details/gtkxnssruf.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yuanzhike.top/Article/details/gthxmzhppv.html

Java: do { i++; } while (i < 10);
来源：http://dali.316326.xyz/Article/details/gtjikamznt.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shanyushiyangtech.top/Article/details/gthwrxntbb.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zhengqikj.top/Article/details/gtyzlactjf.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbiysmijl.html

[B09] break 与 continue
来源：http://dali.xziqi.cn/Article/details/gtkholahrd.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtsqlrnwam.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.zhoulong.xyz/Article/details/gtcwnrgofq.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hammf.cn/Article/details/gtyhozwfaj.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtohmfchmd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gtdarshjoc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.fengsongda.top/Article/details/gtgehvjfmp.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.bjfxy.top/Article/details/gtxpakzlqj.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtogullxma.html

[B10] 遍历同时拿索引
来源：http://dali.chenzaomai.com/Article/details/gtfmlwokwo.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gteuothrng.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtahjwlqti.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.cdnleiting.top/Article/details/gtyhpcceql.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtesscucrl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.sxryk.cn/Article/details/gtjeuunzmm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.daxiang520.top/Article/details/gtrnkvbgxr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.quarkkingdee.top/Article/details/gtdhhirzts.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.9152youxi.cn/Article/details/gtzqqvgfxc.html

[B11] 生成数字序列 / 区间
来源：http://dali.ppjwa.cn/Article/details/gtutpqonzb.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtqyrjpkpe.html

PHP:  range(0, 10, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtrnskpwvz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtjwfjpldo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.kuanghao11.cn/Article/details/gtayrtedjk.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtosfwzhbi.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shzxlz.cn/Article/details/gtlchotgza.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtibxaqdyr.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqsvaoup.html

[B12] 跳出多层循环
来源：http://dali.meibo888.top/Article/details/gtnuuscywv.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.redwolf501.top/Article/details/gtdfriunqz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.yueranfly.top/Article/details/gtuaggendk.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.kuanghao11.cn/Article/details/gtnfatckjv.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dashuyun.cn/Article/details/gtjsfstsqh.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtszyworli.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.shzxlz.cn/Article/details/gtoouewaii.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tian-w.cn/Article/details/gtfyvrtihx.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtrrxnnozs.html

[B13] 判断是否为数字
来源：http://dali.cucudq.cn/Article/details/gtuxuwdhvp.html

Py:   isinstance(x, (int, float))
来源：http://dali.snrcjt.cn/Article/details/gthjpcwrhi.html

PHP:  is_numeric($x)
来源：http://dali.feifeiyinyue.top/Article/details/gtbjpobrwh.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gotoacloud.top/Article/details/gtvidkuzmc.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtsxytpsfm.html

Java: x instanceof Number
来源：http://dali.hysaishi.cn/Article/details/gtpcevghmn.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ppjwa.cn/Article/details/gtrmdfhwqc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhongyouzk.top/Article/details/gtyyneuusj.html

C#:   x is int or double or decimal
来源：http://dali.kuanghao11.cn/Article/details/gtnswtqelx.html

[B14] 判断值是否在集合内
来源：http://dali.ybcxt.top/Article/details/gteqincmzg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.tianlin.xyz/Article/details/gtgirdrydb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xuetiantiany.cn/Article/details/gttyfwjfle.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.nanxinkj.top/Article/details/gtojbsnfuf.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.xylfe.cn/Article/details/gtnolzzjel.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cashguo.top/Article/details/gtacbljoup.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hywenlv.cn/Article/details/gtcyqofthf.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zycfv.cn/Article/details/gteunbpebm.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.ehwqpu.com/Article/details/gtidaihfeg.html

[B15] 布尔运算与取反
来源：http://dali.9152youxi.cn/Article/details/gtiawaczze.html

Py:   a and b or not c
来源：http://dali.jlsjyb.cn/Article/details/gtmfssewkt.html

PHP:  $a && $b || !$c
来源：http://dali.gzhubu.top/Article/details/gtkxecmbxq.html

JS:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gtcognxodk.html

TS:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtkpxdxpyb.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtsdwjgwix.html

Go:   a && b || !c
来源：http://dali.wangdashe.top/Article/details/gtgiqqehaw.html

Ruby: a && b || !c
来源：http://dali.cheryme.top/Article/details/gtfyllrzuq.html

C#:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtldsxirfp.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhijiandao.cn/Article/details/gtyerwavso.html

Py:   if not data: return
来源：http://dali.yueranfly.top/Article/details/gtjnnctjix.html

PHP:  if (!$data) { return; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxfuolozv.html

JS:   if (!data) return;
来源：http://dali.yanxiufei.cn/Article/details/gtgmpzqsnc.html

TS:   if (!data) return;
来源：http://dali.birdmap.top/Article/details/gtdovpicbs.html

Java: if (data == null) return;
来源：http://dali.jlsjyb.cn/Article/details/gtfnjyrhvh.html

Go:   if data == nil { return }
来源：http://dali.hnqzz.top/Article/details/gtcbviywji.html

Ruby: return if data.nil?
来源：http://dali.feifeiyinyue.top/Article/details/gtnlbyfqtr.html

C#:   if (data == null) return;
来源：http://dali.hongshengwenyu.top/Article/details/gtvylycbji.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtdcwqjyfw.html

C. 函数与作用域
来源：http://dali.cqqwz.cn/Article/details/gtpyexlfyp.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthottoylw.html

[C01] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gtvuaupobb.html

Py:   def add(a, b): return a + b
来源：http://dali.hysaishi.cn/Article/details/gtuanunsnu.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.haohaochexian.top/Article/details/gtcsakyvdt.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gzhubu.top/Article/details/gtjyqoxvmv.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtypgrbvjm.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yuanzhike.top/Article/details/gtwvqpnobr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.zdqjudy.top/Article/details/gtqtzdbwrb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.c1oappe.top/Article/details/gteubrkrdq.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.havefunace.top/Article/details/gtejehovph.html

[C02] 默认参数
来源：http://dali.cucudq.cn/Article/details/gtlkcilwxr.html

Py:   def greet(name="World"): return name
来源：http://dali.yueranfly.top/Article/details/gtgwioaohw.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.yongpay.top/Article/details/gthufprvsf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.316326.xyz/Article/details/gtwhgslgxw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.pengpengdd.cyou/Article/details/gtavjqllsc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.wangshuangyany.cn/Article/details/gtzuwnmuto.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtkdttyjun.html

Ruby: def greet(name = "World") = name
来源：http://dali.yangfankeji.com/Article/details/gttbuncbdh.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.tianlin.xyz/Article/details/gtqbowxogb.html

[C03] 可变参数
来源：http://dali.iojbl.cn/Article/details/gtusfrotvy.html

Py:   def total(*args): return sum(args)
来源：http://dali.tanke756.top/Article/details/gtqkgkwmdf.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gtxjduoshp.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.pycfn.com/Article/details/gtiqjaiprv.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtmldizkvz.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.tian-w.cn/Article/details/gthenlutwh.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jinqigufen.top/Article/details/gtvnvgzszc.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.tanke756.top/Article/details/gtshfkrqnr.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangdashe.top/Article/details/gtdxgvhrlo.html

[C04] 命名参数 / 关键字参数
来源：http://dali.haohaochexian.top/Article/details/gtavwhvjrp.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.birdmap.top/Article/details/gtztjzkect.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gogol.net.cn/Article/details/gtymkaqyay.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xylfe.cn/Article/details/gtpgzlqajj.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.ehwqpu.com/Article/details/gtxjeqqizp.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.nanxuanxn.top/Article/details/gthcyxwwzi.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtnldswebx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.guowangkeji.top/Article/details/gtkdbmgdxr.html

C#:   f(a: 1, b: 2)
来源：http://dali.hywenlv.cn/Article/details/gtzggvhbfn.html

[C05] 返回多个值
来源：http://dali.shanyushiyangtech.top/Article/details/gtykhdiwna.html


<!-- 参考信息 -->