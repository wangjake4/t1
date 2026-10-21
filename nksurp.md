代发 wailian999

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.ivvv.top/Article/details/gtmutxocqp.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.zhongyouzk.top/Article/details/gtrijbvlvu.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.quarkkingdee.top/Article/details/gtdgfvdifa.html

[A17] 位运算
来源：http://dali.shangyingyoupin.top/Article/details/gtkeoyixcf.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.ivvv.top/Article/details/gtvwsyxtzc.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.zhoulong.xyz/Article/details/gtjkavaaof.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.daria6918.cn/Article/details/gtzzqnbwbo.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.wangshuangyany.cn/Article/details/gtadkhrjba.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtpeehdxmy.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.cucudq.cn/Article/details/gtpaficpwx.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.sxryk.cn/Article/details/gtllgttauh.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuxming.cn/Article/details/gtgvgzfjrn.html

[A18] 字符与 ASCII 码互转
来源：http://dali.yonumen.top/Article/details/gtrvmyhrvg.html

Py:   ord("A"); chr(65)
来源：http://dali.havefunace.top/Article/details/gttjxwilxr.html

PHP:  ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gtdxtbtach.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ivvv.top/Article/details/gtprsbnszv.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.daxiang520.top/Article/details/gtnenbmcdr.html

Java: (int) 'A'; (char) 65
来源：http://dali.shzxlz.cn/Article/details/gtavcvxsrs.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.sysykeji.top/Article/details/gtqywlscel.html

Ruby: "A".ord; 65.chr
来源：http://dali.9152youxi.cn/Article/details/gtbacqliyq.html

C#:   (int)'A'; (char)65
来源：http://dali.xinyue.icu/Article/details/gtevxvbpim.html

[A19] 交换两个变量
来源：http://dali.ivvv.top/Article/details/gtsuoyeshu.html

Py:   a, b = b, a
来源：http://dali.dashuyun.cn/Article/details/gtxofncgzl.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.sweek.top/Article/details/gtdtwhagwz.html

JS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gtydwfupvw.html

TS:   [a, b] = [b, a];
来源：http://dali.haohaochexian.top/Article/details/gtldmuhcws.html

Java: int t = a; a = b; b = t;
来源：http://dali.kuanghao11.cn/Article/details/gttsgcewrp.html

Go:   a, b = b, a
来源：http://dali.iojbl.cn/Article/details/gtsypodogd.html

Ruby: a, b = b, a
来源：http://dali.wangdashe.top/Article/details/gtvgudcysc.html

C#:   (a, b) = (b, a);
来源：http://dali.iojbl.cn/Article/details/gtiseeicuy.html

[A20] 读取标准输入
来源：http://dali.fzhhl.top/Article/details/gtyoknonnt.html

Py:   name = input("请输入：")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruxsfore.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuscwynh.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.gzhubu.top/Article/details/gtjnkttlne.html

TS:   // Node.js：readline 模块
来源：http://dali.shanyushiyangtech.top/Article/details/gtsqffepxf.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.guannengcc.top/Article/details/gtulxnhdlb.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.fzhhl.top/Article/details/gtdbizsiga.html

Ruby: gets.chomp
来源：http://dali.yuxming.cn/Article/details/gtewaqfbdg.html

C#:   Console.ReadLine();
来源：http://dali.zycfv.cn/Article/details/gtzxdekyqh.html

[A21] 保留指定小数位输出
来源：http://dali.vqdsnc.cn/Article/details/gtkfwlgxzk.html

Py:   f"{3.14159:.2f}"
来源：http://dali.pycfn.com/Article/details/gtizewhiag.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoroamujm.html

JS:   (3.14159).toFixed(2)
来源：http://dali.hammf.cn/Article/details/gtkxgqpqjy.html

TS:   (3.14159).toFixed(2)
来源：http://dali.zhongyouzk.top/Article/details/gtqgsarorj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.yj202588.top/Article/details/gtxbpoaqms.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.hnqzz.top/Article/details/gtzkhekoik.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.xinyue.icu/Article/details/gtylhvvmgd.html

C#:   3.14159.ToString("F2")
来源：http://dali.316326.xyz/Article/details/gtbrsokwkw.html

[A22] 获取字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtrlanhszo.html

Py:   len(s)
来源：http://dali.jinqigufen.top/Article/details/gtkawucjpe.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.bjfxy.top/Article/details/gtextcsnoj.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.aibaodan.cn/Article/details/gtljqexklq.html

TS:   s.length
来源：http://dali.shzxlz.cn/Article/details/gtcyefoljf.html

Java: s.length()
来源：http://dali.hysaishi.cn/Article/details/gtbcybzrtu.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.hfpthk.cn/Article/details/gtdgtycmlh.html

Ruby: s.length
来源：http://dali.yonumen.top/Article/details/gtkgxchwqm.html

C#:   s.Length
来源：http://dali.ydzc1.top/Article/details/gtpbxjnucp.html

[A23] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtziwghvrz.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.daxiang520.top/Article/details/gtaxriyiin.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.hnqzz.top/Article/details/gtslijhrbc.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenjidiqi.icu/Article/details/gthsivllgf.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.hnxiangtu.top/Article/details/gthkejcqzr.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.cheryme.top/Article/details/gtjdwotvcb.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zycfv.cn/Article/details/gtbqrndxua.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtkonzrxsp.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.yvedp.cn/Article/details/gtlzpizhzd.html

[A24] 去除首尾空白
来源：http://dali.hongshengwenyu.top/Article/details/gtzvlzjawv.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtangfktpy.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.yj202588.top/Article/details/gtfmdemwma.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.svipenyu.cn/Article/details/gtcykysnfe.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.hysaishi.cn/Article/details/gteoevzpab.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxuanxn.top/Article/details/gtthzeicsb.html

Go:   strings.TrimSpace(s)
来源：http://dali.sysykeji.top/Article/details/gtaynvkdvy.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xuanzx.com/Article/details/gtppsyjqbx.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtdcnrqskf.html

[A25] 字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtqgkhnoip.html

Py:   s1 == s2; s1 != s2
来源：http://dali.wangshuangyany.cn/Article/details/gtbcovszfu.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sysykeji.top/Article/details/gthcrirrsm.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.nanxinkj.top/Article/details/gtzwbhhhmr.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.sysykeji.top/Article/details/gtibkhqllo.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hysaishi.cn/Article/details/gtwpyafayp.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.jlsjyb.cn/Article/details/gtkpkbiqsu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.ybcxt.top/Article/details/gtqnzvtuew.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpwepkrb.html

[A26] 类型转换总览
来源：http://dali.gogol.net.cn/Article/details/gtzgodjdlq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jinghuilouyu.cn/Article/details/gtrbtlufou.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.snrcjt.cn/Article/details/gttashxyup.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gtmkarvehi.html

TS:   Number() String() Boolean() x as number
来源：http://dali.quarkkingdee.top/Article/details/gtcrqnqwjh.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtytqvdzuj.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gttfmwedak.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yuanzhike.top/Article/details/gtaaiaqmbf.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.zdqjudy.top/Article/details/gtzmjuqbyv.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtpwznrxui.html

B. 流程控制
来源：http://dali.xinyue.icu/Article/details/gteeiixojl.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtijcwhyeb.html

[B01] 条件判断 if / else
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxrmbczb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.c1oappe.top/Article/details/gtqiehojoj.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.fengsongda.top/Article/details/gtnswjhuct.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtwonqiiaq.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.xinyue.icu/Article/details/gtyaldnlhs.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.nwbrower.top/Article/details/gteojybtrz.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.cqqwz.cn/Article/details/gtynpdoadk.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.yongpay.top/Article/details/gtqdfnugkj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.cashguo.top/Article/details/gtoiinrlvi.html

[B02] 多分支 else if / elif
来源：http://dali.guannengcc.top/Article/details/gtigqiowxh.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.316326.xyz/Article/details/gtfrlhwhhf.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.yanxiufei.cn/Article/details/gtqsydtdmm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.dianchejie.cn/Article/details/gtlsualzid.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtjabxsivt.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gthcobtgma.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.zhongyouzk.top/Article/details/gtbppqrkjy.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.hfpthk.cn/Article/details/gtqhqawxfs.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.tianlin.xyz/Article/details/gtvyvpcqdw.html

[B03] switch / match / case
来源：http://dali.zhijiandao.cn/Article/details/gtnmubmgky.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.wangdashe.top/Article/details/gteivpzbcc.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gthgbsrpqy.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.iojbl.cn/Article/details/gtybqqlhvu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.haohaochexian.top/Article/details/gtvbhgppus.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.hnxiangtu.top/Article/details/gtioenxahl.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtgknivjrs.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.ybcxt.top/Article/details/gtlizrwvkw.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.redwolf501.top/Article/details/gtzfoqlekx.html

[B04] for 计数循环
来源：http://dali.tanke756.top/Article/details/gtbmeulnff.html

Py:   for i in range(10): print(i)
来源：http://dali.jyoumei.cn/Article/details/gtsjzsxpeg.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.nanxuanxn.top/Article/details/gthgqbfmzr.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.0kj1m.cn/Article/details/gtilyaidnr.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxuanxn.top/Article/details/gttijyboaf.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.zhiwuduotai.top/Article/details/gtpcjpepbz.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhengqikj.top/Article/details/gtapmzvwem.html

Ruby: 10.times { |i| puts i }
来源：http://dali.mhx1999.top/Article/details/gtxlqfwggx.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gtuulvjjsx.html

[B05] 遍历数组 / 列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnstdeoal.html

Py:   for item in arr: print(item)
来源：http://dali.sufxvd.cn/Article/details/gtlwlwnazm.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrqyhmdar.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.xylfe.cn/Article/details/gtffjjmrup.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.shuidangran.top/Article/details/gtkakervps.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.cheryme.top/Article/details/gtxnjnttdi.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.nanxuanxn.top/Article/details/gtyshzerjo.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtwtenwhpf.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.gaohongyu789.top/Article/details/gtdyqyqmhr.html

[B06] 遍历字典 / 对象
来源：http://dali.aibaodan.cn/Article/details/gthlaaovfy.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.dianchejie.cn/Article/details/gtqfoausmz.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtspaljgxt.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtufpugbav.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yj20258.top/Article/details/gtfgfvzgyb.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.smart0.xyz/Article/details/gtjzvbdqog.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.316326.xyz/Article/details/gtklabgngw.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.birdmap.top/Article/details/gtbqukxhua.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.cheryme.top/Article/details/gtffsxhtue.html

[B07] while 循环
来源：http://dali.dianchejie.cn/Article/details/gtwqcekpam.html

Py:   while i < 10: i += 1
来源：http://dali.yj202588.top/Article/details/gtdqhkhgvd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gtgozmcqcc.html

JS:   while (i < 10) { i++; }
来源：http://dali.zdqjudy.top/Article/details/gtoywvxewa.html

TS:   while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gtnrjnvniq.html

Java: while (i < 10) { i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtsbalxcko.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.aizwys.cn/Article/details/gtujkdqcdk.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gthlzszonr.html

C#:   while (i < 10) { i++; }
来源：http://dali.hfpthk.cn/Article/details/gtgoiczmaf.html

[B08] do-while（至少执行一次）
来源：http://dali.guowangkeji.top/Article/details/gtjighqogt.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.jqgufenzy.top/Article/details/gtwvoofvzo.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.ehwqpu.com/Article/details/gtjdygcedk.html

JS:   do { i++; } while (i < 10);
来源：http://dali.pycfn.com/Article/details/gtefqitkxb.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtgoedpyvl.html

Java: do { i++; } while (i < 10);
来源：http://dali.svipenyu.cn/Article/details/gtndruzvgb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.hysaishi.cn/Article/details/gtnfdbfdoc.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinqigfzy.top/Article/details/gtuthskemh.html

C#:   do { i++; } while (i < 10);
来源：http://dali.aizwys.cn/Article/details/gtuipaaocm.html

[B09] break 与 continue
来源：http://dali.jinghuilouyu.cn/Article/details/gtwaebgltf.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.cucudq.cn/Article/details/gtrpazxqgj.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.c1oappe.top/Article/details/gtvwaxrebr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.nanxinkj.top/Article/details/gthirkljnb.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.zdqjudy.top/Article/details/gtvlsagufd.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gotoacloud.top/Article/details/gtavucxsxs.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yonumen.top/Article/details/gtsrvydfcw.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.gogol.net.cn/Article/details/gtgpvwqkrt.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gtdfofbhcs.html

[B10] 遍历同时拿索引
来源：http://dali.chenjidiqi.icu/Article/details/gtmypqfkkv.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.tanke756.top/Article/details/gtsviepail.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.xuanzx.com/Article/details/gtzegikisn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hnqzz.top/Article/details/gtsuzhdmcc.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.dianchejie.cn/Article/details/gtvixfmdfg.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.dashuyun.cn/Article/details/gtidxrsjnr.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.meibo888.top/Article/details/gtqwnzwrdg.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.vqdsnc.cn/Article/details/gtaugqhnbj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gtxjhujifu.html

[B11] 生成数字序列 / 区间
来源：http://dali.cdnleiting.top/Article/details/gtrhwcarpl.html

Py:   list(range(0, 10, 2))
来源：http://dali.sysykeji.top/Article/details/gtdbpysalt.html

PHP:  range(0, 10, 2);
来源：http://dali.vqdsnc.cn/Article/details/gttyesnedx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.chenzaomai.com/Article/details/gtqjcsnqeb.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.meibo888.top/Article/details/gtqxbelofl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zhijiandao.cn/Article/details/gtvtismfcd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxwpmszg.html

Ruby: (0...10).step(2).to_a
来源：http://dali.sufxvd.cn/Article/details/gtxnrrxqbq.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.jianghu66.top/Article/details/gtdfbllvbq.html

[B12] 跳出多层循环
来源：http://dali.ehwqpu.com/Article/details/gtdktrlugw.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhiwuduotai.top/Article/details/gtoqwfdvjh.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtlibgpexs.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpvygrkvd.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.dianchejie.cn/Article/details/gtqtrfxtch.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.tianlin.xyz/Article/details/gttgvyjcad.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtcbfsphbk.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.tanke756.top/Article/details/gtqguzdvth.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.cqqwz.cn/Article/details/gtcwjllkgo.html

[B13] 判断是否为数字
来源：http://dali.cheryme.top/Article/details/gtdtypqjop.html

Py:   isinstance(x, (int, float))
来源：http://dali.daxiang520.top/Article/details/gtjzouavml.html

PHP:  is_numeric($x)
来源：http://dali.dashuyun.cn/Article/details/gtidmapscq.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.meibo888.top/Article/details/gtjaaooddp.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.ivvv.top/Article/details/gtapaozgwq.html

Java: x instanceof Number
来源：http://dali.ppjwa.cn/Article/details/gtcptdebdw.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.daria6918.cn/Article/details/gtbntjoatx.html

Ruby: x.is_a?(Numeric)
来源：http://dali.bjfxy.top/Article/details/gtsbcuntfg.html

C#:   x is int or double or decimal
来源：http://dali.wangdashe.top/Article/details/gtxrqnnqcw.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gttqpbokpt.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.cashguo.top/Article/details/gtiaphyvdo.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jinqigfzy.top/Article/details/gtavnvokgb.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.cqqwz.cn/Article/details/gtzlbfkrph.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtzyyiihup.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.aizwys.cn/Article/details/gtnhmqrpmm.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.gotoacloud.top/Article/details/gtblyrjqsp.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.yj20258.top/Article/details/gtdoregshj.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.fzhhl.top/Article/details/gttxhzzlhs.html

[B15] 布尔运算与取反
来源：http://dali.aibaodan.cn/Article/details/gtlmlkjrqr.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gtktxfymsu.html

PHP:  $a && $b || !$c
来源：http://dali.c1oappe.top/Article/details/gtnaxzdpgb.html

JS:   a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gtgsrqnfme.html

TS:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gttxojhocx.html

Java: a && b || !c
来源：http://dali.kuanghao11.cn/Article/details/gthjztgpir.html

Go:   a && b || !c
来源：http://dali.jianghu66.top/Article/details/gtrdznbbqj.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gttzbxgytn.html

C#:   a && b || !c
来源：http://dali.jinghuilouyu.cn/Article/details/gtnflsmznm.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.hywenlv.cn/Article/details/gtjavdmofb.html

Py:   if not data: return
来源：http://dali.yuanzhike.top/Article/details/gtvfoqaeyy.html

PHP:  if (!$data) { return; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqblfbva.html

JS:   if (!data) return;
来源：http://dali.wangshuangyany.cn/Article/details/gtiffwmzui.html

TS:   if (!data) return;
来源：http://dali.smart0.xyz/Article/details/gtmunjnnqg.html

Java: if (data == null) return;
来源：http://dali.guowangkeji.top/Article/details/gtjrjoguul.html

Go:   if data == nil { return }
来源：http://dali.birdmap.top/Article/details/gtdgnuywvn.html

Ruby: return if data.nil?
来源：http://dali.9152youxi.cn/Article/details/gthjzwmlgi.html

C#:   if (data == null) return;
来源：http://dali.316326.xyz/Article/details/gtohvymanc.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtyhqitiez.html

C. 函数与作用域
来源：http://dali.yj202588.top/Article/details/gtcmfholgg.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtrjsrfaqq.html

[C01] 定义函数
来源：http://dali.jqgufenzy.top/Article/details/gtjmwnsfix.html

Py:   def add(a, b): return a + b
来源：http://dali.fzhhl.top/Article/details/gtovnynawq.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtucpqsoul.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.gotoacloud.top/Article/details/gtxsrmxhal.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.nanxuanxn.top/Article/details/gtewcliqtt.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttevorxal.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.ehwqpu.com/Article/details/gtklqfgsns.html

Ruby: def add(a, b); a + b; end
来源：http://dali.xylfe.cn/Article/details/gtxrtbyeem.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhoulong.xyz/Article/details/gtilzgukdv.html

[C02] 默认参数
来源：http://dali.gotoacloud.top/Article/details/gteucbsbeh.html

Py:   def greet(name="World"): return name
来源：http://dali.c1oappe.top/Article/details/gtncbvxsbn.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.aibaodan.cn/Article/details/gtfapqskma.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.9152youxi.cn/Article/details/gtinlyjiil.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zycfv.cn/Article/details/gtpgchflck.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.ydzc1.top/Article/details/gthrobjgtn.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.9152youxi.cn/Article/details/gtvlsgepky.html

Ruby: def greet(name = "World") = name
来源：http://dali.ybcxt.top/Article/details/gtxcwciwkg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.hysaishi.cn/Article/details/gttatpkmoz.html

[C03] 可变参数
来源：http://dali.zhengqikj.top/Article/details/gtincpksiv.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangdashe.top/Article/details/gtjyouqjqk.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.hnqzz.top/Article/details/gtfihfkzxh.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.9152youxi.cn/Article/details/gtcsamueid.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.hnqzz.top/Article/details/gtktceujng.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.dashuyun.cn/Article/details/gtenpzigbg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtorsljxop.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hongshengwenyu.top/Article/details/gtywpkhkui.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.hnqzz.top/Article/details/gthlkicccx.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinqigufen.top/Article/details/gtbswzttyx.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.tian-w.cn/Article/details/gtbtjyhrnw.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258888.top/Article/details/gtnxegnouh.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.ivvv.top/Article/details/gtandagmze.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhixingplan.top/Article/details/gttaxpcopw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.wangdashe.top/Article/details/gtomuxgjwc.html

Go:   // 无：用配置结构体参数
来源：http://dali.xuanzx.com/Article/details/gtlmwqbrvx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.yongpay.top/Article/details/gtmfdtukno.html

C#:   f(a: 1, b: 2)
来源：http://dali.birdmap.top/Article/details/gtldtxunbs.html

[C05] 返回多个值
来源：http://dali.hfpthk.cn/Article/details/gtnxegyyil.html

Py:   return a, b
来源：http://dali.xinyue.icu/Article/details/gtcwpqkooq.html

PHP:  return [$a, $b];
来源：http://dali.fzhhl.top/Article/details/gtqmpyzcin.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.feifeiyinyue.top/Article/details/gtjrkdccmv.html

TS:   return { a, b };
来源：http://dali.chenjidiqi.icu/Article/details/gtffmtujbc.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ybcxt.top/Article/details/gtfkpziihy.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtupwtllxt.html

Ruby: return a, b
来源：http://dali.gotoacloud.top/Article/details/gtzkhvtezj.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.hnqzz.top/Article/details/gtaxmdllgh.html

[C06] 匿名函数 / lambda
来源：http://dali.aizwys.cn/Article/details/gtcezgrgcj.html

Py:   square = lambda x: x * x
来源：http://dali.shanyushiyangtech.top/Article/details/gttbfzbxif.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtnleyalbv.html

JS:   const square = x => x * x;
来源：http://dali.jianghu66.top/Article/details/gtgxmicliu.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtiilhqbqe.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yongpay.top/Article/details/gtftwhrnwf.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenjidiqi.icu/Article/details/gtwmnnjgbv.html

Ruby: square = ->(x) { x * x }
来源：http://dali.ybcxt.top/Article/details/gtdxyogzjo.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnccehggi.html

[C07] 把函数作为参数传入
来源：http://dali.mhx1999.top/Article/details/gtolqkfxbt.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.nanxuanxn.top/Article/details/gtpyqizeda.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zhengqikj.top/Article/details/gtpzdlwkvo.html


<!-- 参考信息 -->