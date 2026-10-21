代发 wailian999

PHP:  "Hello, {$name}!"; sprintf("Hello, %s", $name)
来源：http://dali.aibaodan.cn/Article/details/gtijxwkusr.html

JS:   `Hello, ${name}!`
来源：http://dali.yvedp.cn/Article/details/gtgoalzldn.html

TS:   `Hello, ${name}!`
来源：http://dali.tian-w.cn/Article/details/gttserrfls.html

Java: "Hello, %s!".formatted(name)
来源：http://dali.cqqwz.cn/Article/details/gttpottobw.html

Go:   fmt.Sprintf("Hello, %s!", name)
来源：http://dali.dashuyun.cn/Article/details/gtxiwhrlvr.html

Ruby: "Hello, #{name}!"
来源：http://dali.cheryme.top/Article/details/gtirquowpc.html

C#:   $"Hello, {name}!"
来源：http://dali.cdnleiting.top/Article/details/gtipthraqa.html

[A13] 多行字符串（练习 \n 转义）
来源：http://dali.9152youxi.cn/Article/details/gtzpwdxsgy.html

Py:   "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtyhgoxbat.html

PHP:  "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtwuoafesn.html

JS:   "第一行\n第二行"
来源：http://dali.xziqi.cn/Article/details/gtrcalsoyz.html

TS:   "第一行\n第二行"
来源：http://dali.yangfankeji.com/Article/details/gtxhgntuxv.html

Java: "第一行\n第二行"
来源：http://dali.316326.xyz/Article/details/gtwbodcnyk.html

Go:   "第一行\n第二行"
来源：http://dali.dianchejie.cn/Article/details/gtdvyyirij.html

Ruby: "第一行\n第二行"
来源：http://dali.gaohongyu789.top/Article/details/gtvitnfmbc.html

C#:   "第一行\n第二行"
来源：http://dali.dashuyun.cn/Article/details/gtdvztdnwi.html

[A14] 注释写法
来源：http://dali.nanxuanxn.top/Article/details/gtxcacdxfc.html

Py:   # 单行；三引号字符串可作多行说明
来源：http://dali.yj20258.top/Article/details/gtrrjgokgf.html

PHP:  // 或 # 单行；/* 多行 */
来源：http://dali.shanyushiyangtech.top/Article/details/gtrsajojci.html

JS:   // 单行；/* 多行 */
来源：http://dali.gaohongyu789.top/Article/details/gtjzbnmkug.html

TS:   // 单行；/* 多行 */
来源：http://dali.zdqjudy.top/Article/details/gtlikomnxw.html

Java: // 单行；/* 多行 */；/** 文档注释 */
来源：http://dali.hnqzz.top/Article/details/gtvwvdsulk.html

Go:   // 单行；/* 多行 */
来源：http://dali.jyoumei.cn/Article/details/gtnvagiowo.html

Ruby: # 单行；=begin 多行 =end
来源：http://dali.smart0.xyz/Article/details/gtkmwgrzvn.html

C#:   // 单行；/* 多行 */
来源：http://dali.nwbrower.top/Article/details/gtbknleppq.html

[A15] 空值判断与默认值
来源：http://dali.wangshuangyany.cn/Article/details/gthiwxfesx.html

Py:   value = data or "默认值"
来源：http://dali.ydzc1.top/Article/details/gthjwbhknu.html

PHP:  $value = $data ?? "默认值";
来源：http://dali.sysykeji.top/Article/details/gtyxgkscav.html

JS:   const value = data ?? "默认值";
来源：http://dali.chenzaomai.com/Article/details/gtweohdprj.html

TS:   const value = data ?? "默认值";
来源：http://dali.dianchejie.cn/Article/details/gtkkldhwjk.html

Java: Objects.requireNonNullElse(data, "默认值")
来源：http://dali.nwbrower.top/Article/details/gtwbddltzz.html

Go:   if data == "" { data = "默认值" }
来源：http://dali.wangshuangyany.cn/Article/details/gtarzfivis.html

Ruby: value = data || "默认值"
来源：http://dali.hnxiangtu.top/Article/details/gtkciraadk.html

C#:   var value = data ?? "默认值";
来源：http://dali.jianghu66.top/Article/details/gtlpbentsj.html

[A16] 真假值判断规则
来源：http://dali.ydzc1.top/Article/details/gtytbiqlcf.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.ehwqpu.com/Article/details/gtwjhpjusb.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.wangdashe.top/Article/details/gtybfrcqdl.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jinghuilouyu.cn/Article/details/gtljzfifle.html

TS:   if (!x) {}
来源：http://dali.snrcjt.cn/Article/details/gtqfaskwjg.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.iojbl.cn/Article/details/gtzxdhnydp.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.guannengcc.top/Article/details/gtjlshrmsm.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.jqgfzy.top/Article/details/gtwimiqgat.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhongyouzk.top/Article/details/gtimxgdvhz.html

[A17] 位运算
来源：http://dali.chenlongwang.top/Article/details/gtgmtihwyv.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtvjqyshqq.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.yongpay.top/Article/details/gtbmmufoje.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gaohongyu789.top/Article/details/gtrggbxsaa.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtgiamswmh.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.quarkkingdee.top/Article/details/gtlurlmcjv.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.redwolf501.top/Article/details/gtoonamqvc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daxiang520.top/Article/details/gtfckglwvu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jyoumei.cn/Article/details/gtktchvfsk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cqqwz.cn/Article/details/gtfoqrzzug.html

Py:   ord("A"); chr(65)
来源：http://dali.sysykeji.top/Article/details/gtsoyipgeg.html

PHP:  ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gtmotwnelv.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.birdmap.top/Article/details/gthbidwjbd.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtyyietnmq.html

Java: (int) 'A'; (char) 65
来源：http://dali.cqqwz.cn/Article/details/gtkneugqpe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhiwuduotai.top/Article/details/gtwucyuocn.html

Ruby: "A".ord; 65.chr
来源：http://dali.jinqigufen.top/Article/details/gtwxmtbdrc.html

C#:   (int)'A'; (char)65
来源：http://dali.birdmap.top/Article/details/gtyyljxyao.html

[A19] 交换两个变量
来源：http://dali.tian-w.cn/Article/details/gtapvnfvdw.html

Py:   a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gthiuluama.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.meibo888.top/Article/details/gtlnjkiefu.html

JS:   [a, b] = [b, a];
来源：http://dali.zhixingplan.top/Article/details/gtrdjzvzpy.html

TS:   [a, b] = [b, a];
来源：http://dali.ehwqpu.com/Article/details/gtjiimwaft.html

Java: int t = a; a = b; b = t;
来源：http://dali.zhixingplan.top/Article/details/gtdyxewxai.html

Go:   a, b = b, a
来源：http://dali.nanxinkj.top/Article/details/gtyqjdmsiu.html

Ruby: a, b = b, a
来源：http://dali.andypj.xyz/Article/details/gtyhedaefx.html

C#:   (a, b) = (b, a);
来源：http://dali.hnxiangtu.top/Article/details/gtqtywblcx.html

[A20] 读取标准输入
来源：http://dali.yueranfly.top/Article/details/gtphupfxiq.html

Py:   name = input("请输入：")
来源：http://dali.wangdashe.top/Article/details/gtcmdujgsa.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.hysaishi.cn/Article/details/gtpvyjnfxr.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jiagoushi.top/Article/details/gtcbgvmqlj.html

TS:   // Node.js：readline 模块
来源：http://dali.hnqzz.top/Article/details/gtnzyxcngt.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.yj20258.top/Article/details/gtniiayssu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cdnleiting.top/Article/details/gtkdvzawoe.html

Ruby: gets.chomp
来源：http://dali.nwbrower.top/Article/details/gtcjftvwgu.html

C#:   Console.ReadLine();
来源：http://dali.cheryme.top/Article/details/gtcykmgvgp.html

[A21] 保留指定小数位输出
来源：http://dali.kuanghao11.cn/Article/details/gtcqixngyo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpmsamdbe.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hammf.cn/Article/details/gtzdeqatjr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgfzy.top/Article/details/gtlhzsnlmt.html

TS:   (3.14159).toFixed(2)
来源：http://dali.tanke756.top/Article/details/gtqyajbkan.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.hysaishi.cn/Article/details/gtqmhczotm.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtitaperfx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yuxming.cn/Article/details/gtabhagszu.html

C#:   3.14159.ToString("F2")
来源：http://dali.meibo888.top/Article/details/gtzhngzsbr.html

[A22] 获取字符串长度
来源：http://dali.yueranfly.top/Article/details/gtwndcplvw.html

Py:   len(s)
来源：http://dali.gaohongyu789.top/Article/details/gtyegcozhv.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ehwqpu.com/Article/details/gteczxevdv.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xylfe.cn/Article/details/gthhvrrcnm.html

TS:   s.length
来源：http://dali.bjfxy.top/Article/details/gtmxrpearg.html

Java: s.length()
来源：http://dali.jqgufenzy.top/Article/details/gtwiqocrgk.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gtbakxozpj.html

Ruby: s.length
来源：http://dali.xinyue.icu/Article/details/gtmgeerlwa.html

C#:   s.Length
来源：http://dali.yanxiufei.cn/Article/details/gtbkmjtxuo.html

[A23] 大小写转换
来源：http://dali.gzhubu.top/Article/details/gtcfgrsies.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.shzxlz.cn/Article/details/gtoybgojci.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.haohaochexian.top/Article/details/gtltudnnmg.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gtjegdxqjc.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.ehwqpu.com/Article/details/gtowfhexol.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqczsjvsu.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.gaohongyu789.top/Article/details/gtxblaudcc.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yongpay.top/Article/details/gtpdxxlept.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.zhengqikj.top/Article/details/gtrotqieid.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtazhelsjk.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shangyingyoupin.top/Article/details/gtgyurotdn.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.zhiwuduotai.top/Article/details/gtmhkmtlpz.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sxryk.cn/Article/details/gtxxncrbqk.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yongpay.top/Article/details/gtkvuwjlam.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.haohaochexian.top/Article/details/gtsfyxbbed.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtxvortzoc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gtgjhwbtzl.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jqgufenzy.top/Article/details/gtqkommhxj.html

[A25] 字符串比较
来源：http://dali.zycfv.cn/Article/details/gtjzwqiwas.html

Py:   s1 == s2; s1 != s2
来源：http://dali.fzhhl.top/Article/details/gteccicstt.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.gaohongyu789.top/Article/details/gtxjknvqkg.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtldlssfyx.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.tianlin.xyz/Article/details/gtfuufslwt.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gtgdrrvxmf.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxujphjsv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yvedp.cn/Article/details/gtkvbntaww.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jianghu66.top/Article/details/gteuyfmjlh.html

[A26] 类型转换总览
来源：http://dali.andypj.xyz/Article/details/gtmvnrkwpm.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.yj20258.top/Article/details/gtnvfuhuyd.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.jyoumei.cn/Article/details/gtmhxzicgv.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.fengsongda.top/Article/details/gtxirwfkqv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.hongshengwenyu.top/Article/details/gthbzixuvz.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavctwyqk.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.dianchejie.cn/Article/details/gtrulvegfk.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.gzhubu.top/Article/details/gttknsxmdd.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gtrfcqhvjm.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtzpvwqtps.html

B. 流程控制
来源：http://dali.zhoulong.xyz/Article/details/gtypntzaxb.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtwqutdkoo.html

[B01] 条件判断 if / else
来源：http://dali.hnxiangtu.top/Article/details/gtxvykoeoi.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yanxiufei.cn/Article/details/gtvdavdpro.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yuxming.cn/Article/details/gtkbhqoabt.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.ydzc1.top/Article/details/gtjtprluez.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtxknzobqf.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.redwolf501.top/Article/details/gtvmpnygak.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yj20258.top/Article/details/gtrhuwkyud.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.zhixingplan.top/Article/details/gtalwptcjk.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.ppjwa.cn/Article/details/gthmsidyhw.html

[B02] 多分支 else if / elif
来源：http://dali.nwbrower.top/Article/details/gthyntfjdl.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhengqikj.top/Article/details/gtztmccyss.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.iojbl.cn/Article/details/gtjeuxrbjd.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hfpthk.cn/Article/details/gtuweijqyl.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.chenzaomai.com/Article/details/gtzgmmbila.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yueranfly.top/Article/details/gtbewfamjo.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.cheryme.top/Article/details/gtupqofjpb.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.wangdashe.top/Article/details/gtwloggcyx.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhengqikj.top/Article/details/gtzgndnkgh.html

[B03] switch / match / case
来源：http://dali.wangdashe.top/Article/details/gtpqadyhsy.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.ppjwa.cn/Article/details/gtzesjlpln.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.havefunace.top/Article/details/gthzdolmko.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvqdyylct.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.cqqwz.cn/Article/details/gtvfjhwzcw.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtslthkpnf.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.snrcjt.cn/Article/details/gtouuratxx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.vqdsnc.cn/Article/details/gttedoosgv.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.yj20258.top/Article/details/gtslzddstf.html

[B04] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtvxzvprxk.html

Py:   for i in range(10): print(i)
来源：http://dali.zhixingplan.top/Article/details/gtkletykrd.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.tanke756.top/Article/details/gtqplltsuj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.chenzaomai.com/Article/details/gtflnizadd.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.sxryk.cn/Article/details/gtslwpvcwp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.nanxinkj.top/Article/details/gtzueeofkx.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.guowangkeji.top/Article/details/gtuostohky.html

Ruby: 10.times { |i| puts i }
来源：http://dali.yvedp.cn/Article/details/gtgqvbuhrt.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.hysaishi.cn/Article/details/gtnbwvtefr.html

[B05] 遍历数组 / 列表
来源：http://dali.yj202588.top/Article/details/gtgwjhbuay.html

Py:   for item in arr: print(item)
来源：http://dali.yueranfly.top/Article/details/gtrshayyti.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hnqzz.top/Article/details/gtykkcwybv.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.kuanghao11.cn/Article/details/gtuteicidt.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.aizwys.cn/Article/details/gthyskakde.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.birdmap.top/Article/details/gttgmtrlzc.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.jianghu66.top/Article/details/gtowjmvudk.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zdqjudy.top/Article/details/gtwftaelve.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jiagoushi.top/Article/details/gtxdzskhwy.html

[B06] 遍历字典 / 对象
来源：http://dali.chenjidiqi.icu/Article/details/gtvmldltjd.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhongyouzk.top/Article/details/gttbexopqg.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj20258888.top/Article/details/gthjpseyty.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hywenlv.cn/Article/details/gtwfxbzivb.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.hfpthk.cn/Article/details/gtolvzyyud.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.sufxvd.cn/Article/details/gtbgirmdlo.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.daxiang520.top/Article/details/gtzekxjcac.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gaohongyu789.top/Article/details/gtmezkkdue.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.haohaochexian.top/Article/details/gthnnnsebi.html

[B07] while 循环
来源：http://dali.jiagoushi.top/Article/details/gtxzpcckzc.html

Py:   while i < 10: i += 1
来源：http://dali.snrcjt.cn/Article/details/gtktgymwoc.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.cucudq.cn/Article/details/gtlhehoyvz.html

JS:   while (i < 10) { i++; }
来源：http://dali.tanke756.top/Article/details/gtiakzrvlo.html

TS:   while (i < 10) { i++; }
来源：http://dali.yanxiufei.cn/Article/details/gtrftugcnj.html

Java: while (i < 10) { i++; }
来源：http://dali.gzhubu.top/Article/details/gthrpjjnsi.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.zdqjudy.top/Article/details/gtulxisnvt.html

Ruby: while i < 10; i += 1; end
来源：http://dali.nanxinkj.top/Article/details/gtqpwtwrxh.html

C#:   while (i < 10) { i++; }
来源：http://dali.svipenyu.cn/Article/details/gtdyokjrii.html

[B08] do-while（至少执行一次）
来源：http://dali.zhengqikj.top/Article/details/gtszngwcua.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.bjfxy.top/Article/details/gtvupuiivv.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.daxiang520.top/Article/details/gtcpezopba.html

JS:   do { i++; } while (i < 10);
来源：http://dali.zhiwuduotai.top/Article/details/gtlmffugzx.html

TS:   do { i++; } while (i < 10);
来源：http://dali.tian-w.cn/Article/details/gtojvrtksh.html

Java: do { i++; } while (i < 10);
来源：http://dali.zdqjudy.top/Article/details/gtlwspujoj.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuanzx.com/Article/details/gtqcppwwyv.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.zdqjudy.top/Article/details/gtxsiqjgxw.html

C#:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlyffkwao.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtdwbiqnpg.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yuanzhike.top/Article/details/gtwkdqudio.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtpylvprjb.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.wangdashe.top/Article/details/gthzneqnmi.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sysykeji.top/Article/details/gtcxjphqqj.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtceasighw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shzxlz.cn/Article/details/gtxqqjkril.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.jianghu66.top/Article/details/gtvifsltyw.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnqzz.top/Article/details/gtkmzkpjeg.html

[B10] 遍历同时拿索引
来源：http://dali.birdmap.top/Article/details/gtlglaebwm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.sufxvd.cn/Article/details/gtxrmznozq.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.chenlongwang.top/Article/details/gtwvjraium.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhixingplan.top/Article/details/gtouoxswky.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.ehwqpu.com/Article/details/gtjydhzzed.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.xuetiantiany.cn/Article/details/gtmluplxgl.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jqgufenzy.top/Article/details/gtluvuvojz.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.0kj1m.cn/Article/details/gtepnplkgj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtinmkpjtp.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtsogmwejn.html

Py:   list(range(0, 10, 2))
来源：http://dali.zhiwuduotai.top/Article/details/gttuupimel.html

PHP:  range(0, 10, 2);
来源：http://dali.cheryme.top/Article/details/gtiqxfrowc.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhoulong.xyz/Article/details/gtluimmofn.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jqgufenzy.top/Article/details/gtutqaqwtf.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuanzhike.top/Article/details/gtfvudymwk.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.sxryk.cn/Article/details/gtlljkfjmk.html

Ruby: (0...10).step(2).to_a
来源：http://dali.mhx1999.top/Article/details/gtecsovect.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yanxiufei.cn/Article/details/gtctpwlxsl.html

[B12] 跳出多层循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyqymhoj.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.jinqigfzy.top/Article/details/gtpwqwxruw.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.dashuyun.cn/Article/details/gtejdibkoh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.sxryk.cn/Article/details/gtzboejonw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.aibaodan.cn/Article/details/gtonhfqheo.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.mhx1999.top/Article/details/gtigbegrmq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.jianghu66.top/Article/details/gttrzqvdui.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtubpwyrey.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.redwolf501.top/Article/details/gtdlrbojjn.html

[B13] 判断是否为数字
来源：http://dali.birdmap.top/Article/details/gtqnwhhwvl.html

Py:   isinstance(x, (int, float))
来源：http://dali.yuxming.cn/Article/details/gtyewtfhmj.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtfdynyslo.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangshuangyany.cn/Article/details/gtoduttlca.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpocwudfk.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtiudfvthu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.yanxiufei.cn/Article/details/gtixhiiwja.html

Ruby: x.is_a?(Numeric)
来源：http://dali.daria6918.cn/Article/details/gtopypqimu.html

C#:   x is int or double or decimal
来源：http://dali.sysykeji.top/Article/details/gtnlwyreqf.html

[B14] 判断值是否在集合内
来源：http://dali.zhiwuduotai.top/Article/details/gtdgindfzs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.iojbl.cn/Article/details/gtxwecsimc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.chenjidiqi.icu/Article/details/gtxsunvexp.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtttjulfhb.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.svipenyu.cn/Article/details/gtbgyvgrxm.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.nwbrower.top/Article/details/gtkhvhhlvr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hysaishi.cn/Article/details/gtbvfbamdc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.9152youxi.cn/Article/details/gtqxvnkmiw.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.cqqwz.cn/Article/details/gtvubnaaqi.html

[B15] 布尔运算与取反
来源：http://dali.yonumen.top/Article/details/gtcflqmgyt.html

Py:   a and b or not c
来源：http://dali.vqdsnc.cn/Article/details/gtepuldpjd.html

PHP:  $a && $b || !$c
来源：http://dali.sufxvd.cn/Article/details/gteevwzrqk.html

JS:   a && b || !c
来源：http://dali.cdnleiting.top/Article/details/gtocjgfbiy.html

TS:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gtsqjcuqtp.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtbtvutntz.html

Go:   a && b || !c
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfellmzyn.html

Ruby: a && b || !c
来源：http://dali.shuidangran.top/Article/details/gtftwlxtjx.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtglfomsle.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.smart0.xyz/Article/details/gtlzvhskdq.html

Py:   if not data: return
来源：http://dali.nanxinkj.top/Article/details/gthjnsbktj.html

PHP:  if (!$data) { return; }
来源：http://dali.jyoumei.cn/Article/details/gtheafdoea.html

JS:   if (!data) return;
来源：http://dali.hnqzz.top/Article/details/gtbedxzuvm.html

TS:   if (!data) return;
来源：http://dali.zycfv.cn/Article/details/gtiwwouksi.html

Java: if (data == null) return;
来源：http://dali.xziqi.cn/Article/details/gtudtnpksr.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtpxwemufu.html

Ruby: return if data.nil?
来源：http://dali.gzhubu.top/Article/details/gtfatpxpcm.html

C#:   if (data == null) return;
来源：http://dali.fengsongda.top/Article/details/gtvqmyuaeu.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtdrbcostu.html

C. 函数与作用域
来源：http://dali.ydzc1.top/Article/details/gtuwnqfowc.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtbznsfibt.html

[C01] 定义函数
来源：http://dali.ppjwa.cn/Article/details/gtprkwkoza.html

Py:   def add(a, b): return a + b
来源：http://dali.zhengqikj.top/Article/details/gtafbkqoiy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.gaohongyu789.top/Article/details/gtbgxlevrn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gtrxcyiimp.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.0kj1m.cn/Article/details/gtnrvcogns.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtoerwadmq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jyoumei.cn/Article/details/gttbxcbeis.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gtcehinmxz.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.ppjwa.cn/Article/details/gtzwsjwnki.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gtwgbexdxo.html

Py:   def greet(name="World"): return name
来源：http://dali.feifeiyinyue.top/Article/details/gtbvtwwine.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.svipenyu.cn/Article/details/gttitpywwe.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.sxryk.cn/Article/details/gtvkeehmmy.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgjemrutw.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtnovxuvwq.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.jinqigufen.top/Article/details/gtlyjqjtse.html

Ruby: def greet(name = "World") = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwaunedsp.html


<!-- 参考信息 -->