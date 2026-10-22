代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.zycfv.cn/Article/details/gtsvdwwnhv.html

JS:   `Hello, ${name}!`
来源：http://dali.tanke756.top/Article/details/gtiqnwthsr.html

TS:   `Hello, ${name}!`
来源：http://dali.hnqzz.top/Article/details/gtnhlybrlz.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.316326.xyz/Article/details/gtkzuelydf.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.hongshengwenyu.top/Article/details/gtpmxdtphv.html

Ruby: "Hello, #{name}!"
来源：http://dali.jinqigufen.top/Article/details/gtloaivqfc.html

C#:   $"Hello, {name}!"
来源：http://dali.ppjwa.cn/Article/details/gtzkqxfcpv.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.guannengcc.top/Article/details/gtruowliyp.html

Py:   "第一行\n第二行"
来源：http://dali.nanxuanxn.top/Article/details/gtbfglhfwk.html

PHP:  "第一行\n第二行"
来源：http://dali.quarkkingdee.top/Article/details/gtxsrkucvb.html

JS:   "第一行\n第二行"
来源：http://dali.sufxvd.cn/Article/details/gtaxkstoeb.html

TS:   "第一行\n第二行"
来源：http://dali.yongpay.top/Article/details/gtyoieulyo.html

Java: "第一行\n第二行"
来源：http://dali.vqdsnc.cn/Article/details/gtcvrxcqnq.html

Go:   "第一行\n第二行"
来源：http://dali.zhengqikj.top/Article/details/gtcvdzrlgu.html

Ruby: "第一行\n第二行"
来源：http://dali.yonumen.top/Article/details/gtehyuppoq.html

C#:   "第一行\n第二行"
来源：http://dali.cdnleiting.top/Article/details/gtenehukqd.html

[A14] 注释写法
来源：http://dali.guannengcc.top/Article/details/gtffiotbjz.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.ydzc1.top/Article/details/gtjiciglfa.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.tian-w.cn/Article/details/gtjsbtjycd.html

JS:   // 单行；/* 多行 */
来源：http://dali.fzhhl.top/Article/details/gtkdmjsvoi.html

TS:   // 单行；/* 多行 */
来源：http://dali.jinqigufen.top/Article/details/gtqfcgoruu.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.ehwqpu.com/Article/details/gtkyzceloz.html

Go:   // 单行；/* 多行 */
来源：http://dali.gogol.net.cn/Article/details/gttknbvjry.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.chenzaomai.com/Article/details/gtcecoohfc.html

C#:   // 单行；/* 多行 */
来源：http://dali.jiagoushi.top/Article/details/gtopnbrooy.html

[A15] 空值判断与默认值
来源：http://dali.0kj1m.cn/Article/details/gtbmvuriul.html

Py:   value = data or "默认值"
来源：http://dali.jinqigufen.top/Article/details/gtvwppkdej.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.guannengcc.top/Article/details/gtybfconry.html

JS:   const value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtotpmrqks.html

TS:   const value = data ?? "默认值";
来源：http://dali.ybcxt.top/Article/details/gtkxnwgvmu.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.dianchejie.cn/Article/details/gtahetyynz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.yj20258888.top/Article/details/gtoyklndtm.html

Ruby: value = data || "默认值"
来源：http://dali.jianghu66.top/Article/details/gtaaxwbkew.html

C#:   var value = data ?? "默认值";
来源：http://dali.ivvv.top/Article/details/gtjqcixigb.html

[A16] 真假值判断规则
来源：http://dali.sxryk.cn/Article/details/gthlubsjwh.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ehwqpu.com/Article/details/gtgrvsiagb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.zhiwuduotai.top/Article/details/gtsfyliyfx.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.nanxuanxn.top/Article/details/gtzqkakxsl.html

TS:   if (!x) {}
来源：http://dali.sufxvd.cn/Article/details/gtboxpjozc.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangdashe.top/Article/details/gtcregcwwp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.nwbrower.top/Article/details/gtnnimdzic.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.c1oappe.top/Article/details/gtxaxqxefm.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.jinqigufen.top/Article/details/gtvxxkqdlp.html

[A17] 位运算
来源：http://dali.yj20258888.top/Article/details/gttrutmedx.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtwercycrx.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.cqqwz.cn/Article/details/gtjtiyrkhl.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.shuidangran.top/Article/details/gtpvbwfaze.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.sysykeji.top/Article/details/gthknbmbpo.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gotoacloud.top/Article/details/gtmpfqdkos.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.jianghu66.top/Article/details/gtqgwwqkkg.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.svipenyu.cn/Article/details/gtiscgstai.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtvqodqjau.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtjhbuugkk.html

Py:   ord("A"); chr(65)
来源：http://dali.0kj1m.cn/Article/details/gthvcrkuww.html

PHP:  ord("A"); chr(65)
来源：http://dali.gotoacloud.top/Article/details/gtbatvphng.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.jiagoushi.top/Article/details/gtnoabuhmq.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hysaishi.cn/Article/details/gtmrbfnrxn.html

Java: (int) 'A'; (char) 65
来源：http://dali.redwolf501.top/Article/details/gttkyqsaec.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.daria6918.cn/Article/details/gtrukdqqrn.html

Ruby: "A".ord; 65.chr
来源：http://dali.chenjidiqi.icu/Article/details/gtxclxpvmw.html

C#:   (int)'A'; (char)65
来源：http://dali.nanxuanxn.top/Article/details/gtfxhisfws.html

[A19] 交换两个变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsaldgmyu.html

Py:   a, b = b, a
来源：http://dali.cashguo.top/Article/details/gtskcsdhtp.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yanxiufei.cn/Article/details/gtkrmkaymd.html

JS:   [a, b] = [b, a];
来源：http://dali.316326.xyz/Article/details/gtgyzeqcau.html

TS:   [a, b] = [b, a];
来源：http://dali.yueranfly.top/Article/details/gtupwlbtqc.html

Java: int t = a; a = b; b = t;
来源：http://dali.sufxvd.cn/Article/details/gtdoherzcz.html

Go:   a, b = b, a
来源：http://dali.sxryk.cn/Article/details/gtmqoiohcf.html

Ruby: a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gtotoxsfgl.html

C#:   (a, b) = (b, a);
来源：http://dali.dashuyun.cn/Article/details/gtqshjtlse.html

[A20] 读取标准输入
来源：http://dali.yuxming.cn/Article/details/gtvfuekubd.html

Py:   name = input("请输入：")
来源：http://dali.yongpay.top/Article/details/gtltnckxfi.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ehwqpu.com/Article/details/gtklodvosl.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvqgtddo.html

TS:   // Node.js：readline 模块
来源：http://dali.mhx1999.top/Article/details/gthbnsxouz.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.wangshuangyany.cn/Article/details/gtgehncemv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hfpthk.cn/Article/details/gtiffgxkff.html

Ruby: gets.chomp
来源：http://dali.gzhubu.top/Article/details/gthtjkeqqq.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtctgfnfbe.html

[A21] 保留指定小数位输出
来源：http://dali.wangdashe.top/Article/details/gtoozgqqbu.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xziqi.cn/Article/details/gtcglmetdk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hywenlv.cn/Article/details/gtmkbyrhpe.html

JS:   (3.14159).toFixed(2)
来源：http://dali.pengpengdd.cyou/Article/details/gtpwxdzszv.html

TS:   (3.14159).toFixed(2)
来源：http://dali.kuanghao11.cn/Article/details/gtmpvjndba.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgetjiwf.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtydbwvrmb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtsrueieic.html

C#:   3.14159.ToString("F2")
来源：http://dali.jinqigfzy.top/Article/details/gtwkduqrer.html

[A22] 获取字符串长度
来源：http://dali.iojbl.cn/Article/details/gtbmvgpmva.html

Py:   len(s)
来源：http://dali.iojbl.cn/Article/details/gtwhasgcdl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jianghu66.top/Article/details/gtthzrkegv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gtzjfsqzad.html

TS:   s.length
来源：http://dali.ybcxt.top/Article/details/gtsgtoxiyu.html

Java: s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gttulgksdc.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hnxiangtu.top/Article/details/gtliqvkxzd.html

Ruby: s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gtigqdcpfo.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtkskjiwli.html

[A23] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtzxqxwgws.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.tianlin.xyz/Article/details/gtxruhizsy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.shzxlz.cn/Article/details/gtobwfpadq.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.wangdashe.top/Article/details/gtsvpnelob.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinqigufen.top/Article/details/gtnqarhmyr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.feifeiyinyue.top/Article/details/gtujugqfql.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.nanxinkj.top/Article/details/gtaktdfdoz.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sweek.top/Article/details/gthkabgugw.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigufen.top/Article/details/gtgspailtn.html

[A24] 去除首尾空白
来源：http://dali.ivvv.top/Article/details/gtwryuboyw.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jianghu66.top/Article/details/gtxnjfrukb.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.hnqzz.top/Article/details/gtziurntif.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtxupungxp.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hfpthk.cn/Article/details/gtxowlljji.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.jqgufenzy.top/Article/details/gtqtczktyo.html

Go:   strings.TrimSpace(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtxlcvksey.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jyoumei.cn/Article/details/gthpaxfxrg.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.yueranfly.top/Article/details/gttnzvqwdb.html

[A25] 字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtltctokja.html

Py:   s1 == s2; s1 != s2
来源：http://dali.andypj.xyz/Article/details/gtwznzhofb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gtryagwrbc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtzrnjrrur.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ehwqpu.com/Article/details/gtxhbwrtlm.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.gzhubu.top/Article/details/gtbwndupvc.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.chenzaomai.com/Article/details/gtegsaxbuu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ydzc1.top/Article/details/gtbzvatdma.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.nanxuanxn.top/Article/details/gtpqyycvkg.html

[A26] 类型转换总览
来源：http://dali.cashguo.top/Article/details/gtwlsdttmh.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.wangshuangyany.cn/Article/details/gtnjmhenux.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.hysaishi.cn/Article/details/gtxjlfhfsk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.sweek.top/Article/details/gtgarrszae.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gtzdxvadyi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.chenjidiqi.icu/Article/details/gtderdiyug.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.hongshengwenyu.top/Article/details/gthlxukrdx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guowangkeji.top/Article/details/gtmsscecfq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.mhx1999.top/Article/details/gthyuqndxz.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtdniafqih.html

B. 流程控制
来源：http://dali.wangdashe.top/Article/details/gtjuipftpe.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxcqsgoxr.html

[B01] 条件判断 if / else
来源：http://dali.zdqjudy.top/Article/details/gtrvyidyxq.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.aizwys.cn/Article/details/gtgbnbbbyb.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.ehwqpu.com/Article/details/gtpinipblc.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gttktixvxq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtmdzjypnd.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtbicnojxs.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zdqjudy.top/Article/details/gtrnrwayio.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtqbqymcjh.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hywenlv.cn/Article/details/gtnbdomdnv.html

[B02] 多分支 else if / elif
来源：http://dali.shanyushiyangtech.top/Article/details/gtbhwvcsuz.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.jiagoushi.top/Article/details/gtejubmbiw.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yj20258.top/Article/details/gtkqydebow.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ivvv.top/Article/details/gtcuwebefx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gttvhhgzff.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtqtixegfk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.andypj.xyz/Article/details/gtdrmoomuz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gzhubu.top/Article/details/gtqbnlwlbw.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.aibaodan.cn/Article/details/gtwpljligm.html

[B03] switch / match / case
来源：http://dali.yuanzhike.top/Article/details/gtjxwrfbxd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigfzy.top/Article/details/gtwefdksym.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.cdnleiting.top/Article/details/gtbfnxdedh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtnxjtpjas.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtvayqkrrv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zdqjudy.top/Article/details/gtwfnnagbn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.dashuyun.cn/Article/details/gtrtgnvowf.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.nanxinkj.top/Article/details/gtetctrypj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.hysaishi.cn/Article/details/gtzmbvsrcn.html

[B04] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtmunjnoqd.html

Py:   for i in range(10): print(i)
来源：http://dali.shuidangran.top/Article/details/gtqltqgcgj.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.zhengqikj.top/Article/details/gtasmqxpaw.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.dianchejie.cn/Article/details/gthqrjyoew.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj202588.top/Article/details/gtquiivazw.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlcojeuar.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.aizwys.cn/Article/details/gtjhwtbdio.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhongyouzk.top/Article/details/gtljhugnxs.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yueranfly.top/Article/details/gtryxvxwjc.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gtbmawrclp.html

Py:   for item in arr: print(item)
来源：http://dali.sysykeji.top/Article/details/gthjvxjfcz.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.yueranfly.top/Article/details/gtzlcxgsms.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdurkqwkk.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtgnfivbaf.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hnqzz.top/Article/details/gtzjrvjwke.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.vqdsnc.cn/Article/details/gtxeolswse.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yangfankeji.com/Article/details/gtqlgqnboa.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.daxiang520.top/Article/details/gtktxixqla.html

[B06] 遍历字典 / 对象
来源：http://dali.pengpengdd.cyou/Article/details/gtqceavbmw.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.ppjwa.cn/Article/details/gtvnubckfy.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.chenzaomai.com/Article/details/gtrfzlxcxg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yueranfly.top/Article/details/gtthfeqxcd.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.pengpengdd.cyou/Article/details/gtqvehcxxy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.tanke756.top/Article/details/gtsltmsnqp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.gotoacloud.top/Article/details/gtndyoqiat.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmxhbojxc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.chenlongwang.top/Article/details/gtpvzlytaj.html

[B07] while 循环
来源：http://dali.316326.xyz/Article/details/gtogqgonrc.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gthsnfbyun.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zycfv.cn/Article/details/gtxxymcojf.html

JS:   while (i < 10) { i++; }
来源：http://dali.ybcxt.top/Article/details/gtlxxplbmo.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtslgpxpgn.html

Java: while (i < 10) { i++; }
来源：http://dali.xziqi.cn/Article/details/gtzgumfoso.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.sysykeji.top/Article/details/gtoofmhont.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhengqikj.top/Article/details/gtobykqfnm.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtnvuzdteb.html

[B08] do-while（至少执行一次）
来源：http://dali.cqqwz.cn/Article/details/gtxcbbhpmj.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.svipenyu.cn/Article/details/gtkscwoigo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.zhoulong.xyz/Article/details/gtflsfokbb.html

JS:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtlbveehup.html

TS:   do { i++; } while (i < 10);
来源：http://dali.sufxvd.cn/Article/details/gtdfubptuw.html

Java: do { i++; } while (i < 10);
来源：http://dali.quarkkingdee.top/Article/details/gtrygydfqw.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.chenzaomai.com/Article/details/gtdpppywxk.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.ybcxt.top/Article/details/gttondbnok.html

C#:   do { i++; } while (i < 10);
来源：http://dali.zhengqikj.top/Article/details/gtksrzklfl.html

[B09] break 与 continue
来源：http://dali.wangdashe.top/Article/details/gtuqvbkhtr.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.redwolf501.top/Article/details/gtxjxusfhe.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.gogol.net.cn/Article/details/gtwsyivyle.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnadxlxkf.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtlbpmijya.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtghqffcbb.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hammf.cn/Article/details/gthoixljdo.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nwbrower.top/Article/details/gtcdorazui.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.dashuyun.cn/Article/details/gtkcpdhdlu.html

[B10] 遍历同时拿索引
来源：http://dali.cucudq.cn/Article/details/gtccymgfjk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.xuanzx.com/Article/details/gtwoycpqgo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.ybcxt.top/Article/details/gtbjgfsnon.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.bjfxy.top/Article/details/gtayaiojto.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.yuxming.cn/Article/details/gtytymvzie.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.tanke756.top/Article/details/gtoyvczuif.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtcesqdxtq.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yvedp.cn/Article/details/gtnmfixsxa.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfzwnjgbz.html

[B11] 生成数字序列 / 区间
来源：http://dali.xuetiantiany.cn/Article/details/gtpmtndfsp.html

Py:   list(range(0, 10, 2))
来源：http://dali.yongpay.top/Article/details/gtjxphqfqi.html

PHP:  range(0, 10, 2);
来源：http://dali.jianghu66.top/Article/details/gtvkkcxtqi.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtmyuhtpkk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.shangyingyoupin.top/Article/details/gthtdmrfhl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.svipenyu.cn/Article/details/gtzbcisreq.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.dianchejie.cn/Article/details/gtkzmqlrae.html

Ruby: (0...10).step(2).to_a
来源：http://dali.xuanzx.com/Article/details/gtgtkyvkqf.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.zhongyouzk.top/Article/details/gtrdkzbmle.html

[B12] 跳出多层循环
来源：http://dali.ppjwa.cn/Article/details/gtbnlrneku.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.shanyushiyangtech.top/Article/details/gtdxtbxmtk.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.zhengqikj.top/Article/details/gtuqtaoren.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gzhubu.top/Article/details/gtxdmwiucm.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jiagoushi.top/Article/details/gtjppmacbt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hfpthk.cn/Article/details/gtruaxneks.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgdzgwpj.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.smart0.xyz/Article/details/gtvnbjrzgc.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.andypj.xyz/Article/details/gtojoehzlz.html

[B13] 判断是否为数字
来源：http://dali.jinqigfzy.top/Article/details/gtrkkcvxse.html

Py:   isinstance(x, (int, float))
来源：http://dali.cdnleiting.top/Article/details/gtmnqtvook.html

PHP:  is_numeric($x)
来源：http://dali.yonumen.top/Article/details/gtuujxpdxi.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.nwbrower.top/Article/details/gtrnnjhrqv.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.aizwys.cn/Article/details/gtfejofahm.html

Java: x instanceof Number
来源：http://dali.shanyushiyangkeji.top/Article/details/gteqhidtzg.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.birdmap.top/Article/details/gtpclguabw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yvedp.cn/Article/details/gtifyrbndx.html

C#:   x is int or double or decimal
来源：http://dali.jqgufenzy.top/Article/details/gtjyuqpgni.html

[B14] 判断值是否在集合内
来源：http://dali.aibaodan.cn/Article/details/gtkrgtteyo.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cqqwz.cn/Article/details/gtnozblped.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.aibaodan.cn/Article/details/gtgkpbemtx.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.wangdashe.top/Article/details/gtxplxomep.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yj20258.top/Article/details/gtkdjtbtfz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.birdmap.top/Article/details/gtyfizzzcx.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.vqdsnc.cn/Article/details/gtcdtxgykd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtcuvwpord.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.xuanzx.com/Article/details/gtvkecnfgb.html

[B15] 布尔运算与取反
来源：http://dali.hfpthk.cn/Article/details/gtjmyvqfdh.html

Py:   a and b or not c
来源：http://dali.zhongyouzk.top/Article/details/gtiurnbgfw.html

PHP:  $a && $b || !$c
来源：http://dali.fengsongda.top/Article/details/gtlpzjdlgb.html

JS:   a && b || !c
来源：http://dali.snrcjt.cn/Article/details/gtyrbmwgcp.html

TS:   a && b || !c
来源：http://dali.jyoumei.cn/Article/details/gtduuwnekl.html

Java: a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtguyrixnr.html

Go:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtupcftnzf.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtrshmsumh.html

C#:   a && b || !c
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgqiinci.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.redwolf501.top/Article/details/gtqmvikwkh.html

Py:   if not data: return
来源：http://dali.yanxiufei.cn/Article/details/gtwjfldfgx.html

PHP:  if (!$data) { return; }
来源：http://dali.smart0.xyz/Article/details/gtdyjotloi.html

JS:   if (!data) return;
来源：http://dali.jinqigufen.top/Article/details/gtrcqaetoo.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gtkqslmkdr.html

Java: if (data == null) return;
来源：http://dali.cashguo.top/Article/details/gtdrtvtbbo.html

Go:   if data == nil { return }
来源：http://dali.pycfn.com/Article/details/gtldinfpxy.html

Ruby: return if data.nil?
来源：http://dali.zhoulong.xyz/Article/details/gtbqcropnl.html

C#:   if (data == null) return;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpqfacewo.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmbbzecgd.html

C. 函数与作用域
来源：http://dali.wangshuangyany.cn/Article/details/gtnclruiny.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtrvbmqlck.html

[C01] 定义函数
来源：http://dali.andypj.xyz/Article/details/gtirojlwwj.html

Py:   def add(a, b): return a + b
来源：http://dali.yanxiufei.cn/Article/details/gtkhhunyoo.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdxrmpcp.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtucvhqwve.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtbnoxyqon.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtjcjvzcoa.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.svipenyu.cn/Article/details/gtlniozitt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.iojbl.cn/Article/details/gtrdochada.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnyvvkrze.html

[C02] 默认参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbwrsltpt.html

Py:   def greet(name="World"): return name
来源：http://dali.tianlin.xyz/Article/details/gtjqdmdibh.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hysaishi.cn/Article/details/gtpvmfajpm.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.fengsongda.top/Article/details/gtssnmuslw.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtoatpyhaa.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ehwqpu.com/Article/details/gtwyvnzkrz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jlsjyb.cn/Article/details/gtarcypgfs.html

Ruby: def greet(name = "World") = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtienbvomb.html


<!-- 参考信息 -->