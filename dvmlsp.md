代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.jinqigufen.top/Article/details/gtipbmzxxy.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fengsongda.top/Article/details/gtueoknnks.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.svipenyu.cn/Article/details/gtifjipzay.html

[A17] 位运算
来源：http://dali.shanyushiyangtech.top/Article/details/gteowrqsoy.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jiagoushi.top/Article/details/gtaxcxwvbl.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtpncrvpaa.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jinqigufen.top/Article/details/gtopxrekwe.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtqnioqare.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.tanke756.top/Article/details/gtsqawaksw.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtcacxpvtc.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.fengsongda.top/Article/details/gtbzplwnxu.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gtbzdmqybc.html

[A18] 字符与 ASCII 码互转
来源：http://dali.aizwys.cn/Article/details/gtxyrqnaen.html

Py:   ord("A"); chr(65)
来源：http://dali.iojbl.cn/Article/details/gtgndbaqjx.html

PHP:  ord("A"); chr(65)
来源：http://dali.yuanzhike.top/Article/details/gtpspwypkn.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.guannengcc.top/Article/details/gtsdlxebas.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhixingplan.top/Article/details/gtxtsgfmlw.html

Java: (int) 'A'; (char) 65
来源：http://dali.sufxvd.cn/Article/details/gtyhskansv.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zhijiandao.cn/Article/details/gtvesslaqb.html

Ruby: "A".ord; 65.chr
来源：http://dali.aizwys.cn/Article/details/gtnzmuyrzw.html

C#:   (int)'A'; (char)65
来源：http://dali.jlsjyb.cn/Article/details/gtiypnoltk.html

[A19] 交换两个变量
来源：http://dali.chenzaomai.com/Article/details/gtdacfuvnb.html

Py:   a, b = b, a
来源：http://dali.fzhhl.top/Article/details/gtdrmnsykb.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.hnxiangtu.top/Article/details/gtulqkwxzb.html

JS:   [a, b] = [b, a];
来源：http://dali.gaohongyu789.top/Article/details/gtgtdgxnin.html

TS:   [a, b] = [b, a];
来源：http://dali.yongpay.top/Article/details/gtukatiwmh.html

Java: int t = a; a = b; b = t;
来源：http://dali.c1oappe.top/Article/details/gtugvdbvfb.html

Go:   a, b = b, a
来源：http://dali.quarkkingdee.top/Article/details/gtjdtrcfcl.html

Ruby: a, b = b, a
来源：http://dali.yanxiufei.cn/Article/details/gtlkmibyaf.html

C#:   (a, b) = (b, a);
来源：http://dali.jinqigfzy.top/Article/details/gtsgukmmor.html

[A20] 读取标准输入
来源：http://dali.smart0.xyz/Article/details/gtjdryibnc.html

Py:   name = input("请输入：")
来源：http://dali.quarkkingdee.top/Article/details/gtnsrspxcy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.jianghu66.top/Article/details/gtmkfczpek.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cheryme.top/Article/details/gtrwbhixqj.html

TS:   // Node.js：readline 模块
来源：http://dali.chenlongwang.top/Article/details/gtgtwfjxzv.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jyoumei.cn/Article/details/gtijxpxusu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.kuanghao11.cn/Article/details/gtbaslszub.html

Ruby: gets.chomp
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljqyboul.html

C#:   Console.ReadLine();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdzwukhes.html

[A21] 保留指定小数位输出
来源：http://dali.zhongyouzk.top/Article/details/gtfqtjcwkx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.dashuyun.cn/Article/details/gtokawxgcz.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxuanxn.top/Article/details/gtcwmgidqy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.dashuyun.cn/Article/details/gtlrvpyphd.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcxmmedyw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtsdidheow.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.yongpay.top/Article/details/gtozxzyldo.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.svipenyu.cn/Article/details/gtbcucqvxp.html

C#:   3.14159.ToString("F2")
来源：http://dali.zhoulong.xyz/Article/details/gtywklzsve.html

[A22] 获取字符串长度
来源：http://dali.zycfv.cn/Article/details/gtzdcepkio.html

Py:   len(s)
来源：http://dali.fzhhl.top/Article/details/gtnaaxvluf.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ybcxt.top/Article/details/gtmkyincyp.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xuetiantiany.cn/Article/details/gtuegmfjpo.html

TS:   s.length
来源：http://dali.sweek.top/Article/details/gtxgtpyane.html

Java: s.length()
来源：http://dali.316326.xyz/Article/details/gtgtqtnmuf.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.0kj1m.cn/Article/details/gtybolyohk.html

Ruby: s.length
来源：http://dali.yueranfly.top/Article/details/gtofarhpef.html

C#:   s.Length
来源：http://dali.9152youxi.cn/Article/details/gtfrdvhpnl.html

[A23] 大小写转换
来源：http://dali.chenzaomai.com/Article/details/gtrxgvfphz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jianghu66.top/Article/details/gtbgclqoyr.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.nwbrower.top/Article/details/gtilalczqo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtisugrwsk.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gtiuwjgqhw.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtcoaobego.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtmblsaxmh.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.aibaodan.cn/Article/details/gtebwjfkxi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pengpengdd.cyou/Article/details/gtmbnncdkj.html

[A24] 去除首尾空白
来源：http://dali.yuxming.cn/Article/details/gtmtbplqgl.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.xziqi.cn/Article/details/gtrtoxjopv.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yvedp.cn/Article/details/gtmwlxahht.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtvxmnpdfd.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhijiandao.cn/Article/details/gtagmeiuew.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.gzhubu.top/Article/details/gtpktlvdcg.html

Go:   strings.TrimSpace(s)
来源：http://dali.sufxvd.cn/Article/details/gtdkwwubia.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gtquyuglbr.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.jlsjyb.cn/Article/details/gtgtnlrmbk.html

[A25] 字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtzlvxgsqb.html

Py:   s1 == s2; s1 != s2
来源：http://dali.snrcjt.cn/Article/details/gtcxjmbrdm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ppjwa.cn/Article/details/gtkequklra.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtmxzjsgjs.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.quarkkingdee.top/Article/details/gtgprpxjua.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvpabsbrz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgjuhzoev.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtsmvfwwgp.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.ehwqpu.com/Article/details/gtuiililqg.html

[A26] 类型转换总览
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbkakifbj.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.ivvv.top/Article/details/gtojtmjfks.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.quarkkingdee.top/Article/details/gtemuwsyeb.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xylfe.cn/Article/details/gtanfimscd.html

TS:   Number() String() Boolean() x as number
来源：http://dali.tanke756.top/Article/details/gtteefviqr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.c1oappe.top/Article/details/gtausipnin.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zhiwuduotai.top/Article/details/gtrxwpcerx.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.guannengcc.top/Article/details/gtogtrdlkj.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.guowangkeji.top/Article/details/gtifbuvnok.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gttzoarbom.html

B. 流程控制
来源：http://dali.yanxiufei.cn/Article/details/gtnlbaipsf.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtwvtnlklq.html

[B01] 条件判断 if / else
来源：http://dali.nanxuanxn.top/Article/details/gtywttncyl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gtqoiajqiu.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.yangfankeji.com/Article/details/gtzipxlmzh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cheryme.top/Article/details/gtsemgxpeu.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jqgufenzy.top/Article/details/gtipeeitwz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtateqlyvj.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.shangyingyoupin.top/Article/details/gtjyjtlnlh.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.hnqzz.top/Article/details/gtleomwodq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hammf.cn/Article/details/gtnbzmuxrn.html

[B02] 多分支 else if / elif
来源：http://dali.pengpengdd.cyou/Article/details/gtpjkbwzwu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.chenzaomai.com/Article/details/gtbzwysuuc.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.quarkkingdee.top/Article/details/gtbiukteyt.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.c1oappe.top/Article/details/gtwwgsdwhp.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jlsjyb.cn/Article/details/gtteeqxboi.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtznqutaxr.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.yongpay.top/Article/details/gtzuqgfrfi.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.quarkkingdee.top/Article/details/gtdrktqcye.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.smart0.xyz/Article/details/gtvmblhvrw.html

[B03] switch / match / case
来源：http://dali.9152youxi.cn/Article/details/gtnsthtfns.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jinqigufen.top/Article/details/gtpdlndmzu.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtnqldssyc.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.redwolf501.top/Article/details/gtaumnnfru.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.xinyue.icu/Article/details/gtfrnzzkxd.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtffgetlal.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.fzhhl.top/Article/details/gtbcwsgpip.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.gogol.net.cn/Article/details/gtqixanyfp.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.meibo888.top/Article/details/gtfnqrpaoc.html

[B04] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtzydqvyfj.html

Py:   for i in range(10): print(i)
来源：http://dali.zhengqikj.top/Article/details/gtlbfygvin.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.gogol.net.cn/Article/details/gtshckdqqg.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yj20258888.top/Article/details/gtszapdyjt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.snrcjt.cn/Article/details/gttdcflwcn.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.yj20258.top/Article/details/gttcdmpmbu.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.birdmap.top/Article/details/gtlymsbbrh.html

Ruby: 10.times { |i| puts i }
来源：http://dali.316326.xyz/Article/details/gtmdgcbrby.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yanxiufei.cn/Article/details/gtulfjbesu.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzertgrwo.html

Py:   for item in arr: print(item)
来源：http://dali.jqgfzy.top/Article/details/gtkklftmly.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.jyoumei.cn/Article/details/gtorkbddxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.pycfn.com/Article/details/gtzmupicgs.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmcqilxfb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jyoumei.cn/Article/details/gthivgsblu.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.ydzc1.top/Article/details/gtnhyjbexs.html

Ruby: arr.each { |item| puts item }
来源：http://dali.yj20258888.top/Article/details/gteddipvfn.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohvplmed.html

[B06] 遍历字典 / 对象
来源：http://dali.xuetiantiany.cn/Article/details/gthnicjtsu.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.havefunace.top/Article/details/gtxnpddfjh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtmkpaenlc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yongpay.top/Article/details/gtlgkvdmgv.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtztodaftb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.cucudq.cn/Article/details/gtaxeuhlya.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.cqqwz.cn/Article/details/gtopeqgmnk.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.andypj.xyz/Article/details/gtlfazrqgx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yvedp.cn/Article/details/gtjupzknah.html

[B07] while 循环
来源：http://dali.xuetiantiany.cn/Article/details/gtpwzqboyo.html

Py:   while i < 10: i += 1
来源：http://dali.daria6918.cn/Article/details/gtkimwqnui.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.yuxming.cn/Article/details/gttefauhwv.html

JS:   while (i < 10) { i++; }
来源：http://dali.daxiang520.top/Article/details/gtxhmsaxvw.html

TS:   while (i < 10) { i++; }
来源：http://dali.jinqigufen.top/Article/details/gtkxgngvyf.html

Java: while (i < 10) { i++; }
来源：http://dali.gogol.net.cn/Article/details/gtmhxdnrvv.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtpdjwrnsa.html

Ruby: while i < 10; i += 1; end
来源：http://dali.andypj.xyz/Article/details/gtyrkdwdiz.html

C#:   while (i < 10) { i++; }
来源：http://dali.meibo888.top/Article/details/gtbciwflfh.html

[B08] do-while（至少执行一次）
来源：http://dali.zhijiandao.cn/Article/details/gtjvgrjmfw.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.wangdashe.top/Article/details/gtjwzujiqq.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.mhx1999.top/Article/details/gtczojggss.html

JS:   do { i++; } while (i < 10);
来源：http://dali.daria6918.cn/Article/details/gtatlcmncj.html

TS:   do { i++; } while (i < 10);
来源：http://dali.fzhhl.top/Article/details/gtsgncfvny.html

Java: do { i++; } while (i < 10);
来源：http://dali.cqqwz.cn/Article/details/gtnsenymvm.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.fzhhl.top/Article/details/gtmmjxnnlz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.fengsongda.top/Article/details/gtnmlzthpp.html

C#:   do { i++; } while (i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtvhwclnuf.html

[B09] break 与 continue
来源：http://dali.xuanzx.com/Article/details/gtkriomasw.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtpcsnbheq.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.meibo888.top/Article/details/gtlagdkkni.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gzhubu.top/Article/details/gtiionpoig.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ppjwa.cn/Article/details/gtykvhxkov.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tianlin.xyz/Article/details/gteouxguni.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.cqqwz.cn/Article/details/gthiagqwkm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.hnqzz.top/Article/details/gtkogalbou.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gthowdhirh.html

[B10] 遍历同时拿索引
来源：http://dali.yj202588.top/Article/details/gthvetpdcv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.pycfn.com/Article/details/gtkbmbzgdm.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.aibaodan.cn/Article/details/gtothkdevs.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.yonumen.top/Article/details/gtxhyodqqb.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.guowangkeji.top/Article/details/gtzlwspfok.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.iojbl.cn/Article/details/gtbulmvbjt.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.svipenyu.cn/Article/details/gtcvxbcirk.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.pengpengdd.cyou/Article/details/gtzvdqzjib.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xinyue.icu/Article/details/gtoucckzii.html

[B11] 生成数字序列 / 区间
来源：http://dali.chenjidiqi.icu/Article/details/gttxlyqeje.html

Py:   list(range(0, 10, 2))
来源：http://dali.316326.xyz/Article/details/gthqrfeiil.html

PHP:  range(0, 10, 2);
来源：http://dali.zhengqikj.top/Article/details/gthidkgtaj.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cheryme.top/Article/details/gttmefhtgk.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.9152youxi.cn/Article/details/gtpaytujlu.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.pycfn.com/Article/details/gtlgfhtcnt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.xziqi.cn/Article/details/gtcvnzepoe.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hysaishi.cn/Article/details/gtlmzbhvwl.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yvedp.cn/Article/details/gtxrulxmsd.html

[B12] 跳出多层循环
来源：http://dali.wangdashe.top/Article/details/gtnbyagctw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.svipenyu.cn/Article/details/gtrjzohjsq.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hywenlv.cn/Article/details/gtqzjrxxln.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgufenzy.top/Article/details/gtgknbltvs.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gaohongyu789.top/Article/details/gtnjtpshdb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbreftblj.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fengsongda.top/Article/details/gtteidbwas.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.nanxuanxn.top/Article/details/gtlamafljh.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.shangyingyoupin.top/Article/details/gtituiapcm.html

[B13] 判断是否为数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcjlmxtgh.html

Py:   isinstance(x, (int, float))
来源：http://dali.gaohongyu789.top/Article/details/gtkuvigmfn.html

PHP:  is_numeric($x)
来源：http://dali.sweek.top/Article/details/gtlpktxrjw.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.wangdashe.top/Article/details/gtjccudorx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cashguo.top/Article/details/gtecwdlbtz.html

Java: x instanceof Number
来源：http://dali.zdqjudy.top/Article/details/gtpyglejhm.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.shangyingyoupin.top/Article/details/gtvvizxknv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.c1oappe.top/Article/details/gthfsogqhp.html

C#:   x is int or double or decimal
来源：http://dali.redwolf501.top/Article/details/gthgkroccn.html

[B14] 判断值是否在集合内
来源：http://dali.fengsongda.top/Article/details/gtfoxqspcs.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.havefunace.top/Article/details/gtuidkmrcb.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.gzhubu.top/Article/details/gtfyyfiuwk.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gthwvmljvs.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yueranfly.top/Article/details/gtyrkvfgsr.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcgyalhkl.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.havefunace.top/Article/details/gttsvkjhca.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xuetiantiany.cn/Article/details/gtoikzrwym.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.hammf.cn/Article/details/gtpppgbrwh.html

[B15] 布尔运算与取反
来源：http://dali.pengpengdd.cyou/Article/details/gtdanmltpa.html

Py:   a and b or not c
来源：http://dali.xziqi.cn/Article/details/gthjwzpoio.html

PHP:  $a && $b || !$c
来源：http://dali.cqqwz.cn/Article/details/gtdddsgrfz.html

JS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtcwrknwus.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gtacyobxxu.html

Java: a && b || !c
来源：http://dali.birdmap.top/Article/details/gtsyrfsxgc.html

Go:   a && b || !c
来源：http://dali.shangyingyoupin.top/Article/details/gtveqcfsxr.html

Ruby: a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtqdbwagtf.html

C#:   a && b || !c
来源：http://dali.zhijiandao.cn/Article/details/gtsihkuuom.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtpcrtzevz.html

Py:   if not data: return
来源：http://dali.zhaomingkeji.xyz/Article/details/gttkqfmzrm.html

PHP:  if (!$data) { return; }
来源：http://dali.andypj.xyz/Article/details/gtlreulohk.html

JS:   if (!data) return;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtristnsff.html

TS:   if (!data) return;
来源：http://dali.aibaodan.cn/Article/details/gtqqseuyhk.html

Java: if (data == null) return;
来源：http://dali.meibo888.top/Article/details/gthqnsqzwj.html

Go:   if data == nil { return }
来源：http://dali.ehwqpu.com/Article/details/gtirwrrohb.html

Ruby: return if data.nil?
来源：http://dali.redwolf501.top/Article/details/gtcgfoehvf.html

C#:   if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gttzdpypjl.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbrqafxvz.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtvjmxpqge.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtrxlqegzy.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gttcjkktek.html

Py:   def add(a, b): return a + b
来源：http://dali.vqdsnc.cn/Article/details/gtostphbtj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.fengsongda.top/Article/details/gtdgtlbtqq.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtkrshdres.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.zhongyouzk.top/Article/details/gticagnthd.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtwkhhursx.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.316326.xyz/Article/details/gtqlsrctnc.html

Ruby: def add(a, b); a + b; end
来源：http://dali.yongpay.top/Article/details/gtvrkccded.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.mhx1999.top/Article/details/gtoissqbmf.html

[C02] 默认参数
来源：http://dali.ivvv.top/Article/details/gtoxocgbft.html

Py:   def greet(name="World"): return name
来源：http://dali.jinghuilouyu.cn/Article/details/gtvrzdyvka.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.haohaochexian.top/Article/details/gthszxfrur.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nwbrower.top/Article/details/gttmrztpdf.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.feifeiyinyue.top/Article/details/gticepwkgc.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.snrcjt.cn/Article/details/gtxpstudsc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.ybcxt.top/Article/details/gtdazgyvjk.html

Ruby: def greet(name = "World") = name
来源：http://dali.svipenyu.cn/Article/details/gtfjuhfxmz.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hnqzz.top/Article/details/gtjywfwpod.html

[C03] 可变参数
来源：http://dali.birdmap.top/Article/details/gtlnxapony.html

Py:   def total(*args): return sum(args)
来源：http://dali.meibo888.top/Article/details/gtbfandrqe.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.chenjidiqi.icu/Article/details/gtfuxekope.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yvedp.cn/Article/details/gtzpfzdjfj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhoulong.xyz/Article/details/gtjgixsvfm.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ppjwa.cn/Article/details/gtnsigmugl.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.hywenlv.cn/Article/details/gtvlzmzrhk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.feifeiyinyue.top/Article/details/gteihhpwai.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gtagvxmibg.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jianghu66.top/Article/details/gtuycegiwi.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtbyeumwaj.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.sxryk.cn/Article/details/gtoiwdxrrk.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.yj20258.top/Article/details/gtuazticca.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.guowangkeji.top/Article/details/gtegcrsojg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.guowangkeji.top/Article/details/gtnxshkqot.html

Go:   // 无：用配置结构体参数
来源：http://dali.dianchejie.cn/Article/details/gtqhbnnayo.html

Ruby: f(a: 1, b: 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtioofemlx.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhengqikj.top/Article/details/gtpvccnzso.html

[C05] 返回多个值
来源：http://dali.dianchejie.cn/Article/details/gtqrrafsme.html

Py:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gtfjfmbxut.html

PHP:  return [$a, $b];
来源：http://dali.smart0.xyz/Article/details/gtntjzxpco.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.nwbrower.top/Article/details/gtzqcrktfo.html

TS:   return { a, b };
来源：http://dali.shuidangran.top/Article/details/gtybtyzbge.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.nanxinkj.top/Article/details/gtziiybcpa.html

Go:   return a, b
来源：http://dali.gotoacloud.top/Article/details/gtfgkpadbb.html

Ruby: return a, b
来源：http://dali.jyoumei.cn/Article/details/gtryxuhekl.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgfzy.top/Article/details/gtcvuutgfr.html

[C06] 匿名函数 / lambda
来源：http://dali.fzhhl.top/Article/details/gtdwgqswav.html

Py:   square = lambda x: x * x
来源：http://dali.xylfe.cn/Article/details/gthoxstfpe.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yanxiufei.cn/Article/details/gtdpmqhief.html

JS:   const square = x => x * x;
来源：http://dali.quarkkingdee.top/Article/details/gtwqwpuchs.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhijiandao.cn/Article/details/gtfiuwgbsv.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.mhx1999.top/Article/details/gtudeiieua.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.xziqi.cn/Article/details/gtfmbxmobx.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gtgncxhfjq.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yongpay.top/Article/details/gtgthqjjla.html

[C07] 把函数作为参数传入
来源：http://dali.hysaishi.cn/Article/details/gtjickjwar.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.pycfn.com/Article/details/gtxnzekjox.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgufenzy.top/Article/details/gtejiwwexn.html


<!-- 参考信息 -->