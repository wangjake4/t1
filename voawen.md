代发 wailian999

[A14] 注释写法
来源：http://dali.ywan-chungtsiang.top/Article/details/gtirxujdmw.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.cheryme.top/Article/details/gtzbbrluat.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.snrcjt.cn/Article/details/gtfotloihz.html

JS:   // 单行；/* 多行 */
来源：http://dali.hongshengwenyu.top/Article/details/gtbpkwijxz.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtnrgmahxv.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hfpthk.cn/Article/details/gtfechpqfw.html

Go:   // 单行；/* 多行 */
来源：http://dali.andypj.xyz/Article/details/gtdsvutpss.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.guannengcc.top/Article/details/gtnflulokg.html

C#:   // 单行；/* 多行 */
来源：http://dali.cqqwz.cn/Article/details/gtrbtciksn.html

[A15] 空值判断与默认值
来源：http://dali.chenlongwang.top/Article/details/gtitoikgct.html

Py:   value = data or "默认值"
来源：http://dali.nwbrower.top/Article/details/gtqroldlhs.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sweek.top/Article/details/gtkopffcjl.html

JS:   const value = data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtzgfrtqow.html

TS:   const value = data ?? "默认值";
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyczhavha.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.ybcxt.top/Article/details/gthgepngyx.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.jqgufenzy.top/Article/details/gtebucoreb.html

Ruby: value = data || "默认值"
来源：http://dali.guannengcc.top/Article/details/gtcswlnkgw.html

C#:   var value = data ?? "默认值";
来源：http://dali.9152youxi.cn/Article/details/gtmmglypbb.html

[A16] 真假值判断规则
来源：http://dali.yueranfly.top/Article/details/gtcnmhrwak.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdjwumll.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtcanzkazm.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfeptuzcc.html

TS:   if (!x) {}
来源：http://dali.yj20258888.top/Article/details/gtprufvnoa.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.smart0.xyz/Article/details/gtxmlwuhzu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.zdqjudy.top/Article/details/gtogewyuse.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.wangdashe.top/Article/details/gtiqqinqnc.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.nanxuanxn.top/Article/details/gtdsxqntur.html

[A17] 位运算
来源：http://dali.xziqi.cn/Article/details/gtyrbdsrkt.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtrbejdoty.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zycfv.cn/Article/details/gtohkkluhr.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.aibaodan.cn/Article/details/gtkuithfgb.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtfsrgroym.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gtvjedctjg.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.smart0.xyz/Article/details/gtaxukseto.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sufxvd.cn/Article/details/gtkfhpvlxw.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtirmvbehf.html

[A18] 字符与 ASCII 码互转
来源：http://dali.sxryk.cn/Article/details/gtdnwoqdjb.html

Py:   ord("A"); chr(65)
来源：http://dali.guowangkeji.top/Article/details/gtpndqwowh.html

PHP:  ord("A"); chr(65)
来源：http://dali.yj20258.top/Article/details/gtjmgmiqrd.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.svipenyu.cn/Article/details/gtfceotkbd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yongpay.top/Article/details/gtdchoazax.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gtlaictgys.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.jinqigfzy.top/Article/details/gtdhirdoas.html

Ruby: "A".ord; 65.chr
来源：http://dali.xylfe.cn/Article/details/gtoozvacjy.html

C#:   (int)'A'; (char)65
来源：http://dali.vqdsnc.cn/Article/details/gtqumcwmql.html

[A19] 交换两个变量
来源：http://dali.ppjwa.cn/Article/details/gttbxsdgcc.html

Py:   a, b = b, a
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulswkwxn.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtzzbgfvdp.html

JS:   [a, b] = [b, a];
来源：http://dali.gogol.net.cn/Article/details/gtigakixvf.html

TS:   [a, b] = [b, a];
来源：http://dali.redwolf501.top/Article/details/gtkmdlrhch.html

Java: int t = a; a = b; b = t;
来源：http://dali.yvedp.cn/Article/details/gtlnrkywhy.html

Go:   a, b = b, a
来源：http://dali.fengsongda.top/Article/details/gtgrvamqnq.html

Ruby: a, b = b, a
来源：http://dali.hnxiangtu.top/Article/details/gtacqqbihp.html

C#:   (a, b) = (b, a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtermuywsl.html

[A20] 读取标准输入
来源：http://dali.tian-w.cn/Article/details/gtyvpdhlph.html

Py:   name = input("请输入：")
来源：http://dali.fzhhl.top/Article/details/gtqxckopgl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.mhx1999.top/Article/details/gtzunbnqte.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.dianchejie.cn/Article/details/gtsignqtek.html

TS:   // Node.js：readline 模块
来源：http://dali.vqdsnc.cn/Article/details/gtrcnrppll.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.c1oappe.top/Article/details/gtldpiwwmu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhengqikj.top/Article/details/gtuldvtrqv.html

Ruby: gets.chomp
来源：http://dali.c1oappe.top/Article/details/gtbznyttmw.html

C#:   Console.ReadLine();
来源：http://dali.316326.xyz/Article/details/gtmmhcoyht.html

[A21] 保留指定小数位输出
来源：http://dali.smart0.xyz/Article/details/gtpfmfxlle.html

Py:   f"{3.14159:.2f}"
来源：http://dali.guannengcc.top/Article/details/gtdbfpoall.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgbzlyjon.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jianghu66.top/Article/details/gtuqdktrpe.html

TS:   (3.14159).toFixed(2)
来源：http://dali.vqdsnc.cn/Article/details/gtshfgdyio.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.smart0.xyz/Article/details/gtjmkayauz.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdapsjsbw.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.gaohongyu789.top/Article/details/gtxztmzqox.html

C#:   3.14159.ToString("F2")
来源：http://dali.cheryme.top/Article/details/gtcbesvnpa.html

[A22] 获取字符串长度
来源：http://dali.ydzc1.top/Article/details/gtwycmstsy.html

Py:   len(s)
来源：http://dali.shuidangran.top/Article/details/gtwmpsbtuf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gaohongyu789.top/Article/details/gtmpcrlrsc.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xziqi.cn/Article/details/gtlbnccuvj.html

TS:   s.length
来源：http://dali.9152youxi.cn/Article/details/gtbllzwaca.html

Java: s.length()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgwhvgzgw.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.xinyue.icu/Article/details/gtzqmqbkcv.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtbyaehncl.html

C#:   s.Length
来源：http://dali.yanxiufei.cn/Article/details/gthuvpapoa.html

[A23] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtfepxiyjb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xuetiantiany.cn/Article/details/gtooxljoys.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.jiagoushi.top/Article/details/gttxkhccdp.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtsscevrbk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.316326.xyz/Article/details/gtmfurunpp.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.xylfe.cn/Article/details/gtkgpfcjhr.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yuxming.cn/Article/details/gtxocdrqti.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.jiagoushi.top/Article/details/gtnvicyjdh.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.cdnleiting.top/Article/details/gtwctvyyap.html

[A24] 去除首尾空白
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnsslvgjw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.dianchejie.cn/Article/details/gtwhtntezw.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.sxryk.cn/Article/details/gtxklsbfqi.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.ehwqpu.com/Article/details/gttnsftnqh.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.fengsongda.top/Article/details/gtpwhpamle.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jiagoushi.top/Article/details/gtjxgyzrpm.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhixingplan.top/Article/details/gtpjzvphpy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yuanzhike.top/Article/details/gtkknkvuen.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.redwolf501.top/Article/details/gthxlivcsr.html

[A25] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtixhqncjp.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ydzc1.top/Article/details/gtjfiulavd.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.hfpthk.cn/Article/details/gtwydrokfw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ybcxt.top/Article/details/gtawjdguiw.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yvedp.cn/Article/details/gtahdqucpg.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.9152youxi.cn/Article/details/gtffenvcyk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.316326.xyz/Article/details/gtueyongln.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.kuanghao11.cn/Article/details/gtgraslksg.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.haohaochexian.top/Article/details/gtsslsonjf.html

[A26] 类型转换总览
来源：http://dali.daxiang520.top/Article/details/gtwvnmzcbv.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.daxiang520.top/Article/details/gtrgjhxfqw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.daria6918.cn/Article/details/gtckalxlle.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cheryme.top/Article/details/gtuzwltljs.html

TS:   Number() String() Boolean() x as number
来源：http://dali.gzhubu.top/Article/details/gtnodhejoi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yangfankeji.com/Article/details/gtbdoggqbh.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yvedp.cn/Article/details/gtwoqvaonz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.316326.xyz/Article/details/gtdtnqodly.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gthgysfkex.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfiwswkap.html

B. 流程控制
来源：http://dali.hammf.cn/Article/details/gtqanikgxi.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtvydcjhco.html

[B01] 条件判断 if / else
来源：http://dali.redwolf501.top/Article/details/gtbsjwhgle.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.jqgufenzy.top/Article/details/gtyzvctzjc.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gtiydblesy.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangdashe.top/Article/details/gtjerzxxkm.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhijiandao.cn/Article/details/gtorvmebsu.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxtxyixws.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ehwqpu.com/Article/details/gtjutqeasg.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.ppjwa.cn/Article/details/gtvgtnsdsk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtzhkezibl.html

[B02] 多分支 else if / elif
来源：http://dali.jiagoushi.top/Article/details/gtnjmymxqp.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.fzhhl.top/Article/details/gtsekpvidw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtlogakxea.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gtjcshpwvi.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cqqwz.cn/Article/details/gtuofhfkye.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tanke756.top/Article/details/gtcjjzpohb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yueranfly.top/Article/details/gtngbrzerg.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xziqi.cn/Article/details/gtufkskhzp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jqgfzy.top/Article/details/gtsdnzhpeh.html

[B03] switch / match / case
来源：http://dali.ehwqpu.com/Article/details/gtvzzwptlk.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gtbqpckptv.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hywenlv.cn/Article/details/gttwvyehjg.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.chenlongwang.top/Article/details/gtyrplhklm.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwfcngqvi.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xylfe.cn/Article/details/gtbhhkwdjt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.smart0.xyz/Article/details/gtkvorhmyz.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.shanyushiyangtech.top/Article/details/gtcjrdxdkq.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.chenzaomai.com/Article/details/gtvpdcwqyj.html

[B04] for 计数循环
来源：http://dali.ivvv.top/Article/details/gtwmshxzwb.html

Py:   for i in range(10): print(i)
来源：http://dali.xuetiantiany.cn/Article/details/gtpwzeffkj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.yueranfly.top/Article/details/gtncuzmrlq.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.haohaochexian.top/Article/details/gtjvrybrfc.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtyzpflhhs.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.tanke756.top/Article/details/gtqrczdtns.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxuanxn.top/Article/details/gtzxwwtcow.html

Ruby: 10.times { |i| puts i }
来源：http://dali.chenzaomai.com/Article/details/gtcdeamxsr.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.nanxuanxn.top/Article/details/gtkmnmjjyh.html

[B05] 遍历数组 / 列表
来源：http://dali.hongshengwenyu.top/Article/details/gtnknqpdqx.html

Py:   for item in arr: print(item)
来源：http://dali.daxiang520.top/Article/details/gtrpyfyoux.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.zhongyouzk.top/Article/details/gtmmzqyune.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zdqjudy.top/Article/details/gtpnnyukth.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.svipenyu.cn/Article/details/gtqxrrhvsa.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.meibo888.top/Article/details/gtiqvvijgp.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yj20258.top/Article/details/gtvgfigocm.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhijiandao.cn/Article/details/gtdgjwbglr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.dashuyun.cn/Article/details/gtnwlxxhmr.html

[B06] 遍历字典 / 对象
来源：http://dali.svipenyu.cn/Article/details/gtezzcgiuk.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zycfv.cn/Article/details/gtzzuehuuw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.jiagoushi.top/Article/details/gtfbqapiir.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258888.top/Article/details/gtqbpqnvyp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yanxiufei.cn/Article/details/gtpbxakavd.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.nwbrower.top/Article/details/gtfulcwnef.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.quarkkingdee.top/Article/details/gtofgjtoyq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.316326.xyz/Article/details/gtjajaqwty.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtatlcwukh.html

[B07] while 循环
来源：http://dali.svipenyu.cn/Article/details/gtqwvpeeyb.html

Py:   while i < 10: i += 1
来源：http://dali.dianchejie.cn/Article/details/gtkoeqhzgm.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqsxvxpzg.html

JS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gtbvbslfve.html

TS:   while (i < 10) { i++; }
来源：http://dali.xinyue.icu/Article/details/gtwgjfcwsr.html

Java: while (i < 10) { i++; }
来源：http://dali.zhengqikj.top/Article/details/gtlajiihfz.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zhiwuduotai.top/Article/details/gtxskhwlhi.html

Ruby: while i < 10; i += 1; end
来源：http://dali.sweek.top/Article/details/gtcjvvbfmb.html

C#:   while (i < 10) { i++; }
来源：http://dali.xuetiantiany.cn/Article/details/gtcgccmlxl.html

[B08] do-while（至少执行一次）
来源：http://dali.9152youxi.cn/Article/details/gtwedhqedc.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jiagoushi.top/Article/details/gtonuoancr.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jqgufenzy.top/Article/details/gtyknjroes.html

JS:   do { i++; } while (i < 10);
来源：http://dali.xuetiantiany.cn/Article/details/gtybulqvbl.html

TS:   do { i++; } while (i < 10);
来源：http://dali.birdmap.top/Article/details/gtirlqprff.html

Java: do { i++; } while (i < 10);
来源：http://dali.xuanzx.com/Article/details/gtwsxghydi.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtmzpbqlgg.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.cdnleiting.top/Article/details/gtpezjbzrn.html

C#:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtrhahyxml.html

[B09] break 与 continue
来源：http://dali.xinyue.icu/Article/details/gtkuvjnvpp.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yvedp.cn/Article/details/gtppfeirsu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtoroiwhlk.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj202588.top/Article/details/gtohwnuufs.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtckqbfebj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shzxlz.cn/Article/details/gtiuovjykc.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.zhixingplan.top/Article/details/gtckrztmyo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gtfgoctslz.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhixingplan.top/Article/details/gtopddfrzi.html

[B10] 遍历同时拿索引
来源：http://dali.smart0.xyz/Article/details/gtrwclqstz.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.jiagoushi.top/Article/details/gtvcmebhcv.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.cdnleiting.top/Article/details/gtenvjiyba.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.daria6918.cn/Article/details/gtnhpmbukz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hysaishi.cn/Article/details/gtkepddrlq.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.hysaishi.cn/Article/details/gtqzkxpykb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yongpay.top/Article/details/gtftzxddpv.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.cdnleiting.top/Article/details/gtbxulkofo.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.chenjidiqi.icu/Article/details/gthxewzuik.html

[B11] 生成数字序列 / 区间
来源：http://dali.smart0.xyz/Article/details/gtfqoetgrz.html

Py:   list(range(0, 10, 2))
来源：http://dali.cashguo.top/Article/details/gtdzggonqu.html

PHP:  range(0, 10, 2);
来源：http://dali.aizwys.cn/Article/details/gtrkkelqgp.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.dianchejie.cn/Article/details/gttdscbdoc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gtheqvxvdb.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.feifeiyinyue.top/Article/details/gtkmatgfij.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zhoulong.xyz/Article/details/gtznemkljk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.zdqjudy.top/Article/details/gtophaibod.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.ppjwa.cn/Article/details/gtgoyzlbkt.html

[B12] 跳出多层循环
来源：http://dali.ivvv.top/Article/details/gtqqgkatsw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.xuanzx.com/Article/details/gtcdngpkul.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gtoqqbrvcv.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.hysaishi.cn/Article/details/gtizhicegc.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gtmpwelyya.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.cqqwz.cn/Article/details/gttlnlueof.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ybcxt.top/Article/details/gtklfxqtds.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zdqjudy.top/Article/details/gtlfwbqtxu.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtntkweuik.html

[B13] 判断是否为数字
来源：http://dali.xinyue.icu/Article/details/gtarpmexhe.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtepavdcbl.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gtuvmwvjmw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.iojbl.cn/Article/details/gtdwzidpkl.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zhongyouzk.top/Article/details/gtybcqblmk.html

Java: x instanceof Number
来源：http://dali.ydzc1.top/Article/details/gtygtsdyaj.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shzxlz.cn/Article/details/gtqluzoasr.html

Ruby: x.is_a?(Numeric)
来源：http://dali.birdmap.top/Article/details/gtdcxvqrbx.html

C#:   x is int or double or decimal
来源：http://dali.gogol.net.cn/Article/details/gtriqhdlzq.html

[B14] 判断值是否在集合内
来源：http://dali.ppjwa.cn/Article/details/gtvlfqhrym.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.gzhubu.top/Article/details/gtoornudno.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.zhijiandao.cn/Article/details/gtoctllcxu.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258888.top/Article/details/gtstlgcflm.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.zhoulong.xyz/Article/details/gtqhgnoztu.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.andypj.xyz/Article/details/gtivjhhdck.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.cashguo.top/Article/details/gtzvjgohri.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.birdmap.top/Article/details/gtejyfgyuy.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.aizwys.cn/Article/details/gtpvafisug.html

[B15] 布尔运算与取反
来源：http://dali.wangdashe.top/Article/details/gtagxxuucm.html

Py:   a and b or not c
来源：http://dali.yj20258888.top/Article/details/gtgyghelvp.html

PHP:  $a && $b || !$c
来源：http://dali.jinqigfzy.top/Article/details/gtgzzuvgyz.html

JS:   a && b || !c
来源：http://dali.wangshuangyany.cn/Article/details/gttjarnaoc.html

TS:   a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gtmqxekvvg.html

Java: a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtfsfykcee.html

Go:   a && b || !c
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjmexcap.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtutkqhqyy.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtqqqgnypl.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.chenzaomai.com/Article/details/gttfispnoh.html

Py:   if not data: return
来源：http://dali.redwolf501.top/Article/details/gtotxifxec.html

PHP:  if (!$data) { return; }
来源：http://dali.guowangkeji.top/Article/details/gtdbxcchbn.html

JS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtgrstobnl.html

TS:   if (!data) return;
来源：http://dali.gotoacloud.top/Article/details/gttqiovffy.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gtstlmwkkv.html

Go:   if data == nil { return }
来源：http://dali.jlsjyb.cn/Article/details/gtoztnfgtn.html

Ruby: return if data.nil?
来源：http://dali.meibo888.top/Article/details/gtagyrfezu.html

C#:   if (data == null) return;
来源：http://dali.feifeiyinyue.top/Article/details/gtrasjaxsa.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtaazzjvkr.html

C. 函数与作用域
来源：http://dali.pycfn.com/Article/details/gtuvtfaoaj.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdzibneow.html

[C01] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtusznrgvp.html

Py:   def add(a, b): return a + b
来源：http://dali.tianlin.xyz/Article/details/gteeqhdgsr.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258888.top/Article/details/gtyndgdfwe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtiiscogrc.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhixingplan.top/Article/details/gttaqpxedx.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gtkqtskfsp.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jqgfzy.top/Article/details/gtzgwtcmyg.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zhongyouzk.top/Article/details/gtrklugydn.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zdqjudy.top/Article/details/gtiunhikkc.html

[C02] 默认参数
来源：http://dali.316326.xyz/Article/details/gttwvrnykf.html

Py:   def greet(name="World"): return name
来源：http://dali.wangshuangyany.cn/Article/details/gtszxsyufl.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hammf.cn/Article/details/gtnhorvmcy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtqarbjhas.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbgympgpq.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.guowangkeji.top/Article/details/gtigzehgly.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.cqqwz.cn/Article/details/gtkmzvqqbk.html

Ruby: def greet(name = "World") = name
来源：http://dali.c1oappe.top/Article/details/gtilzyzwoq.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.wangshuangyany.cn/Article/details/gtkxzxmoek.html

[C03] 可变参数
来源：http://dali.ehwqpu.com/Article/details/gtotrtejaq.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gtszmghvop.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.quarkkingdee.top/Article/details/gtysyigtrf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.quarkkingdee.top/Article/details/gtnjmghwpm.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenzaomai.com/Article/details/gtsiabcrpr.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.zhengqikj.top/Article/details/gtvpvfrcld.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gtksiiopgw.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.wangshuangyany.cn/Article/details/gtejkonfga.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.wangshuangyany.cn/Article/details/gtmlsrqkka.html

[C04] 命名参数 / 关键字参数
来源：http://dali.gogol.net.cn/Article/details/gtmrhjzkvd.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.yanxiufei.cn/Article/details/gtvafqqulz.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtafaybhhh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.nanxuanxn.top/Article/details/gtskirxtql.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.quarkkingdee.top/Article/details/gtmbmuauhb.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlokauqvo.html


<!-- 参考信息 -->