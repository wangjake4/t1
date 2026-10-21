代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ybcxt.top/Article/details/gtqpprglst.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.fzhhl.top/Article/details/gtparvqyec.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.zhixingplan.top/Article/details/gtehnagpdi.html

[A17] 位运算
来源：http://dali.cqqwz.cn/Article/details/gtwjujksih.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.guowangkeji.top/Article/details/gtlgpweiog.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.9152youxi.cn/Article/details/gtjygnutvt.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.meibo888.top/Article/details/gtekdwqyns.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yj202588.top/Article/details/gtngifgchg.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtmpfrblxc.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtcxcbxoaj.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hfpthk.cn/Article/details/gtdjlzlhxv.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.chenzaomai.com/Article/details/gtguzilsvk.html

[A18] 字符与 ASCII 码互转
来源：http://dali.nwbrower.top/Article/details/gtsbuhjsvw.html

Py:   ord("A"); chr(65)
来源：http://dali.jqgfzy.top/Article/details/gttlzsitif.html

PHP:  ord("A"); chr(65)
来源：http://dali.yanxiufei.cn/Article/details/gtxzhyujfl.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cdnleiting.top/Article/details/gtqicighmi.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtwyshveqn.html

Java: (int) 'A'; (char) 65
来源：http://dali.andypj.xyz/Article/details/gtvqaytheu.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.zdqjudy.top/Article/details/gtatgotepm.html

Ruby: "A".ord; 65.chr
来源：http://dali.guannengcc.top/Article/details/gtcfrylyqv.html

C#:   (int)'A'; (char)65
来源：http://dali.sufxvd.cn/Article/details/gtqybwbauf.html

[A19] 交换两个变量
来源：http://dali.yanxiufei.cn/Article/details/gtbopqvvob.html

Py:   a, b = b, a
来源：http://dali.redwolf501.top/Article/details/gtxknwztpx.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.meibo888.top/Article/details/gtovzckbot.html

JS:   [a, b] = [b, a];
来源：http://dali.hfpthk.cn/Article/details/gtothtjcjc.html

TS:   [a, b] = [b, a];
来源：http://dali.cashguo.top/Article/details/gtjqtxoewr.html

Java: int t = a; a = b; b = t;
来源：http://dali.svipenyu.cn/Article/details/gtuxcuxcgy.html

Go:   a, b = b, a
来源：http://dali.snrcjt.cn/Article/details/gtcszcuqxt.html

Ruby: a, b = b, a
来源：http://dali.birdmap.top/Article/details/gtblzxbtnb.html

C#:   (a, b) = (b, a);
来源：http://dali.xuanzx.com/Article/details/gtwmunayhk.html

[A20] 读取标准输入
来源：http://dali.jyoumei.cn/Article/details/gtarszfrih.html

Py:   name = input("请输入：")
来源：http://dali.meibo888.top/Article/details/gttbezcfqg.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.pycfn.com/Article/details/gtbvapkjek.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.chenzaomai.com/Article/details/gtwlmymnme.html

TS:   // Node.js：readline 模块
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnyvthdfy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gtsczdfdps.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.cheryme.top/Article/details/gtehyrpoxm.html

Ruby: gets.chomp
来源：http://dali.shuidangran.top/Article/details/gtkcqlpfzo.html

C#:   Console.ReadLine();
来源：http://dali.xinyue.icu/Article/details/gtzjjkyjld.html

[A21] 保留指定小数位输出
来源：http://dali.gaohongyu789.top/Article/details/gtsanykpjx.html

Py:   f"{3.14159:.2f}"
来源：http://dali.ydzc1.top/Article/details/gttuhrhwyq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.nanxinkj.top/Article/details/gtxixyrviu.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hongshengwenyu.top/Article/details/gtlptdudiz.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shzxlz.cn/Article/details/gtynjmrcro.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.zhoulong.xyz/Article/details/gtjzhcujsr.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.aizwys.cn/Article/details/gtsybudgic.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.fengsongda.top/Article/details/gtkithiywv.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gtylfjclxf.html

[A22] 获取字符串长度
来源：http://dali.zhixingplan.top/Article/details/gtehwgvdgs.html

Py:   len(s)
来源：http://dali.jianghu66.top/Article/details/gtyddkecul.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvpicqcu.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.gzhubu.top/Article/details/gtraodzbet.html

TS:   s.length
来源：http://dali.jiagoushi.top/Article/details/gtzknvloal.html

Java: s.length()
来源：http://dali.sufxvd.cn/Article/details/gtciwnvfta.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.andypj.xyz/Article/details/gthvmoambw.html

Ruby: s.length
来源：http://dali.snrcjt.cn/Article/details/gtbsblcuzu.html

C#:   s.Length
来源：http://dali.meibo888.top/Article/details/gtebxdxmxm.html

[A23] 大小写转换
来源：http://dali.xziqi.cn/Article/details/gtqtdzjzso.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.yanxiufei.cn/Article/details/gtqeodvmvm.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.vqdsnc.cn/Article/details/gtnuahjrwb.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hywenlv.cn/Article/details/gtbisevjhy.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtuyeusggk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yuxming.cn/Article/details/gtvgoakidg.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.yj20258888.top/Article/details/gtuefhtdih.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gtgxphidgg.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.andypj.xyz/Article/details/gtpcbnyjqa.html

[A24] 去除首尾空白
来源：http://dali.feifeiyinyue.top/Article/details/gtlclblucq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.hnqzz.top/Article/details/gtqrvygpvm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.wangshuangyany.cn/Article/details/gtcevchmwx.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.nanxinkj.top/Article/details/gtghllrlrq.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gtvyrczxer.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhengqikj.top/Article/details/gtkptqnfkv.html

Go:   strings.TrimSpace(s)
来源：http://dali.nanxinkj.top/Article/details/gtlqxugxqn.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hysaishi.cn/Article/details/gtjeoswdwp.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtvekfhpvs.html

[A25] 字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtbjnxqgdx.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ehwqpu.com/Article/details/gtsnqszdfm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.vqdsnc.cn/Article/details/gtpevoudes.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.vqdsnc.cn/Article/details/gtemuftwqq.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.chenjidiqi.icu/Article/details/gtfoqxlcly.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.haohaochexian.top/Article/details/gtfddohfxe.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.xziqi.cn/Article/details/gtdwgesxrv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtetskvecs.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.yuanzhike.top/Article/details/gtdbvykrmp.html

[A26] 类型转换总览
来源：http://dali.jiagoushi.top/Article/details/gtdehwpjxb.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.havefunace.top/Article/details/gtthpcwpdr.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.xinyue.icu/Article/details/gtxvgfthhj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxuanxn.top/Article/details/gtjmhyvboj.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cheryme.top/Article/details/gtyyppzhfi.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.zhijiandao.cn/Article/details/gtiehgtejp.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvvqncuv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.nwbrower.top/Article/details/gtnrybinau.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuetiantiany.cn/Article/details/gtjgoqufek.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtisssjufv.html

B. 流程控制
来源：http://dali.chenjidiqi.icu/Article/details/gteuoewais.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnizrpapu.html

[B01] 条件判断 if / else
来源：http://dali.gogol.net.cn/Article/details/gtotzpjsip.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.yvedp.cn/Article/details/gtfuawftrk.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jlsjyb.cn/Article/details/gtjhyvnyjh.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtcrkphrws.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xuanzx.com/Article/details/gttyfxcxts.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.dashuyun.cn/Article/details/gtfhkmzwhp.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.kuanghao11.cn/Article/details/gtjjoaddtx.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yuxming.cn/Article/details/gtklwahdex.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.svipenyu.cn/Article/details/gtiapukipx.html

[B02] 多分支 else if / elif
来源：http://dali.zhoulong.xyz/Article/details/gtuqrqdwej.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.xylfe.cn/Article/details/gtteyimvoa.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.gaohongyu789.top/Article/details/gtmsgdjnfl.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jiagoushi.top/Article/details/gtmskovrgm.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.ybcxt.top/Article/details/gtmofempgb.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhiwuduotai.top/Article/details/gtobcebwkb.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.tian-w.cn/Article/details/gtrgasrdar.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hnxiangtu.top/Article/details/gtzagbelyu.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gotoacloud.top/Article/details/gtesrlrkiw.html

[B03] switch / match / case
来源：http://dali.feifeiyinyue.top/Article/details/gtdxnihtaj.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.jlsjyb.cn/Article/details/gtqlznvuqq.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ehwqpu.com/Article/details/gtidbbcbko.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtltdqkvja.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.nanxinkj.top/Article/details/gthutdmrfh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.xuanzx.com/Article/details/gtfuxyymre.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.xinyue.icu/Article/details/gteumywaqh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ydzc1.top/Article/details/gthhxcljay.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.bjfxy.top/Article/details/gtcuxpsiyo.html

[B04] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtboxjkxvy.html

Py:   for i in range(10): print(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtssnjdppm.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtddjyugud.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xziqi.cn/Article/details/gtgacxsxki.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zycfv.cn/Article/details/gtdiqyxitc.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.jianghu66.top/Article/details/gtdqsyjwuo.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.nanxinkj.top/Article/details/gtzurmhgir.html

Ruby: 10.times { |i| puts i }
来源：http://dali.xinyue.icu/Article/details/gtmzxtfmod.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jyoumei.cn/Article/details/gtcyvsthsv.html

[B05] 遍历数组 / 列表
来源：http://dali.zdqjudy.top/Article/details/gtolpubkgf.html

Py:   for item in arr: print(item)
来源：http://dali.yongpay.top/Article/details/gtnejdjmau.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sweek.top/Article/details/gtyhztdmoc.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.feifeiyinyue.top/Article/details/gtbcdaafio.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.fzhhl.top/Article/details/gtsedqofkb.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.xuetiantiany.cn/Article/details/gtvmiywtcq.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxinkj.top/Article/details/gtxlnjuwzi.html

Ruby: arr.each { |item| puts item }
来源：http://dali.9152youxi.cn/Article/details/gtiuzfcozk.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.yuxming.cn/Article/details/gtbonyjuyf.html

[B06] 遍历字典 / 对象
来源：http://dali.yj20258.top/Article/details/gtlpubkaqm.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gtxlblcwhd.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yuanzhike.top/Article/details/gthkfoyvwd.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gtvfcpojrj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtmmkxgpyn.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.gogol.net.cn/Article/details/gtxbljtttf.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.mhx1999.top/Article/details/gtfsgehiuq.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.yj20258.top/Article/details/gtxaltzzte.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.aizwys.cn/Article/details/gtzeaopofi.html

[B07] while 循环
来源：http://dali.wangshuangyany.cn/Article/details/gtwtkbcocq.html

Py:   while i < 10: i += 1
来源：http://dali.yongpay.top/Article/details/gthndbnpks.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.jqgufenzy.top/Article/details/gtyybqmnlj.html

JS:   while (i < 10) { i++; }
来源：http://dali.zhijiandao.cn/Article/details/gtqumwglou.html

TS:   while (i < 10) { i++; }
来源：http://dali.shzxlz.cn/Article/details/gtalsydcgn.html

Java: while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtxiajnltp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtgycelslw.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhijiandao.cn/Article/details/gtkzwiqqly.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgufenzy.top/Article/details/gteyitainq.html

[B08] do-while（至少执行一次）
来源：http://dali.birdmap.top/Article/details/gtgomuarrh.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.gzhubu.top/Article/details/gtunajriwl.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jinqigufen.top/Article/details/gttvpvuwgm.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yueranfly.top/Article/details/gtvpzbpaje.html

TS:   do { i++; } while (i < 10);
来源：http://dali.yanxiufei.cn/Article/details/gtxsafcosi.html

Java: do { i++; } while (i < 10);
来源：http://dali.jinqigfzy.top/Article/details/gtzacwwtcs.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.cdnleiting.top/Article/details/gtthdbfvzz.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.wangdashe.top/Article/details/gtwldbjrxd.html

C#:   do { i++; } while (i < 10);
来源：http://dali.bjfxy.top/Article/details/gtjhcehofb.html

[B09] break 与 continue
来源：http://dali.jinqigfzy.top/Article/details/gtfpjaywbz.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.tianlin.xyz/Article/details/gtdknbiizn.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.jyoumei.cn/Article/details/gtzseksttv.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zhengqikj.top/Article/details/gtklkbtnni.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aizwys.cn/Article/details/gtfsqiwhek.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtolvakjaj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.shuidangran.top/Article/details/gtvyvemutb.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guannengcc.top/Article/details/gtiodslfmt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.quarkkingdee.top/Article/details/gtpdaicpeg.html

[B10] 遍历同时拿索引
来源：http://dali.xuanzx.com/Article/details/gtxhvygvnf.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.andypj.xyz/Article/details/gtpvatrwrf.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.bjfxy.top/Article/details/gtwpcjbvlo.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.jinqigufen.top/Article/details/gtznzuvjpg.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtizwzgkwt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.chenjidiqi.icu/Article/details/gtimhwfarm.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.jianghu66.top/Article/details/gtfaofjcdy.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtsfijhnxj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.xylfe.cn/Article/details/gtgrkobjuf.html

[B11] 生成数字序列 / 区间
来源：http://dali.cheryme.top/Article/details/gtnwjmsweo.html

Py:   list(range(0, 10, 2))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwjxgacjv.html

PHP:  range(0, 10, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtzhxnamet.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.fengsongda.top/Article/details/gtokqucfcc.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gtqihkzqif.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cucudq.cn/Article/details/gtldcieehg.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yonumen.top/Article/details/gtnbimcbuq.html

Ruby: (0...10).step(2).to_a
来源：http://dali.cqqwz.cn/Article/details/gtctcutkcu.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gtbfqskuce.html

[B12] 跳出多层循环
来源：http://dali.yj20258.top/Article/details/gtrqilxodu.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.gaohongyu789.top/Article/details/gtwxjceyqy.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.xylfe.cn/Article/details/gtgefwttsu.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtikgilitw.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.pycfn.com/Article/details/gtdjaalzib.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtdrttlygi.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.smart0.xyz/Article/details/gttbyqbwgr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.sweek.top/Article/details/gtceggicga.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.sxryk.cn/Article/details/gtjhbyvmsw.html

[B13] 判断是否为数字
来源：http://dali.guowangkeji.top/Article/details/gtjvqzucdd.html

Py:   isinstance(x, (int, float))
来源：http://dali.zhijiandao.cn/Article/details/gtjoqkyblg.html

PHP:  is_numeric($x)
来源：http://dali.tianlin.xyz/Article/details/gtndrvzvie.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.zycfv.cn/Article/details/gtwfhbhuxy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.9152youxi.cn/Article/details/gtiibuvcby.html

Java: x instanceof Number
来源：http://dali.gaohongyu789.top/Article/details/gtovvzsuxl.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.wangshuangyany.cn/Article/details/gtfxelievl.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cdnleiting.top/Article/details/gtiolmifse.html

C#:   x is int or double or decimal
来源：http://dali.shangyingyoupin.top/Article/details/gttlipcccy.html

[B14] 判断值是否在集合内
来源：http://dali.zhengqikj.top/Article/details/gtyfskubao.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.zhijiandao.cn/Article/details/gtuqlnvbwq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.316326.xyz/Article/details/gtlslpxoca.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsvyjjcpj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.feifeiyinyue.top/Article/details/gtksnabbzz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtlvcfmbpm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.9152youxi.cn/Article/details/gtiwdqrvnk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.xziqi.cn/Article/details/gtsuqyzkdo.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.dianchejie.cn/Article/details/gtnlpjuvjw.html

[B15] 布尔运算与取反
来源：http://dali.dianchejie.cn/Article/details/gtbukjpiqc.html

Py:   a and b or not c
来源：http://dali.snrcjt.cn/Article/details/gttmoaedlw.html

PHP:  $a && $b || !$c
来源：http://dali.ivvv.top/Article/details/gtndoqkekh.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gtoorylozo.html

TS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtgujmynke.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gtchftwgxl.html

Go:   a && b || !c
来源：http://dali.nanxuanxn.top/Article/details/gtzttpjvxv.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtlmmwdboy.html

C#:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtgsqdgvii.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtgnqkpcbm.html

Py:   if not data: return
来源：http://dali.hammf.cn/Article/details/gtbqjooyqd.html

PHP:  if (!$data) { return; }
来源：http://dali.aizwys.cn/Article/details/gtfubhupnf.html

JS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gtmpotpbrj.html

TS:   if (!data) return;
来源：http://dali.nanxuanxn.top/Article/details/gtwcyulukk.html

Java: if (data == null) return;
来源：http://dali.andypj.xyz/Article/details/gtvrppenmg.html

Go:   if data == nil { return }
来源：http://dali.sysykeji.top/Article/details/gtizyqmglg.html

Ruby: return if data.nil?
来源：http://dali.hammf.cn/Article/details/gtizxtxxpz.html

C#:   if (data == null) return;
来源：http://dali.yanxiufei.cn/Article/details/gtkvetziyv.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtqoncdmbs.html

C. 函数与作用域
来源：http://dali.yanxiufei.cn/Article/details/gtwhergsww.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtbhwlxurg.html

[C01] 定义函数
来源：http://dali.yangfankeji.com/Article/details/gtaxmelpgg.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gtwfmfgjjj.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yangfankeji.com/Article/details/gtxnnmxumh.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gthlbzisse.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shzxlz.cn/Article/details/gtqydwunay.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gtdcxptykj.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.sufxvd.cn/Article/details/gtysqokmap.html

Ruby: def add(a, b); a + b; end
来源：http://dali.ybcxt.top/Article/details/gtksgynolb.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.nwbrower.top/Article/details/gtoabrtclx.html

[C02] 默认参数
来源：http://dali.gzhubu.top/Article/details/gtvmpyrpql.html

Py:   def greet(name="World"): return name
来源：http://dali.ivvv.top/Article/details/gtxpdsexbr.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.snrcjt.cn/Article/details/gtjcxfxtcv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gteownkmay.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqacidcn.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.shangyingyoupin.top/Article/details/gtyzqmysmp.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.feifeiyinyue.top/Article/details/gtdrauwxzw.html

Ruby: def greet(name = "World") = name
来源：http://dali.daxiang520.top/Article/details/gtyrkeujqj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.nwbrower.top/Article/details/gtemwmhdav.html

[C03] 可变参数
来源：http://dali.yj20258.top/Article/details/gtoqzvnuax.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinghuilouyu.cn/Article/details/gtqesjiqfv.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gzhubu.top/Article/details/gttqtnjebf.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigufen.top/Article/details/gtzuyztvue.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.meibo888.top/Article/details/gthhhebvdn.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.sxryk.cn/Article/details/gtksewjxwu.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtwieeuluf.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.redwolf501.top/Article/details/gtjdpglrmm.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.yuanzhike.top/Article/details/gtorocqkxx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.0kj1m.cn/Article/details/gtdgwdorrr.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.meibo888.top/Article/details/gtrnextsgf.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.vqdsnc.cn/Article/details/gtlkhtmagp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhixingplan.top/Article/details/gthfbjxstd.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.andypj.xyz/Article/details/gtvdegibgv.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.fzhhl.top/Article/details/gtkydhfphv.html

Go:   // 无：用配置结构体参数
来源：http://dali.nanxuanxn.top/Article/details/gtwwcdjruv.html

Ruby: f(a: 1, b: 2)
来源：http://dali.ehwqpu.com/Article/details/gthtfaoicw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yvedp.cn/Article/details/gtyyiqunxh.html

[C05] 返回多个值
来源：http://dali.aizwys.cn/Article/details/gtfwjnogrv.html

Py:   return a, b
来源：http://dali.nanxuanxn.top/Article/details/gtagzhsbwq.html

PHP:  return [$a, $b];
来源：http://dali.yueranfly.top/Article/details/gttewnczhf.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gtehgousse.html

TS:   return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gttouagvgh.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.hfpthk.cn/Article/details/gtqynerehm.html

Go:   return a, b
来源：http://dali.cucudq.cn/Article/details/gttcpzagyg.html

Ruby: return a, b
来源：http://dali.xuanzx.com/Article/details/gtcheqagll.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.yonumen.top/Article/details/gtdocifkoo.html

[C06] 匿名函数 / lambda
来源：http://dali.jinqigfzy.top/Article/details/gtjcxguceb.html

Py:   square = lambda x: x * x
来源：http://dali.yuxming.cn/Article/details/gteuiyvruo.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.xinyue.icu/Article/details/gtrwaewimx.html

JS:   const square = x => x * x;
来源：http://dali.jinqigfzy.top/Article/details/gtwenspbwe.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.mhx1999.top/Article/details/gtsgyjpdlo.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.zhongyouzk.top/Article/details/gtxmpuegon.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.tian-w.cn/Article/details/gtqwndlwrb.html

Ruby: square = ->(x) { x * x }
来源：http://dali.gotoacloud.top/Article/details/gtczqhivvy.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hongshengwenyu.top/Article/details/gtidstpvzd.html

[C07] 把函数作为参数传入
来源：http://dali.tanke756.top/Article/details/gtkxmmqfym.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.zycfv.cn/Article/details/gtnhjtkzys.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.jqgfzy.top/Article/details/gtsefkzlif.html


<!-- 参考信息 -->