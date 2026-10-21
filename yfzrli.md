代发 wailian999

Ruby: value = data || "默认值"
来源：http://dali.yvedp.cn/Article/details/gtihtaztov.html

C#:   var value = data ?? "默认值";
来源：http://dali.jyoumei.cn/Article/details/gtpbsuqnxk.html

[A16] 真假值判断规则
来源：http://dali.zhixingplan.top/Article/details/gtpavwncga.html

Py:   if not x:        # 0 "" [] {} None 均为假
来源：http://dali.pycfn.com/Article/details/gtwskhpnvf.html

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.hnxiangtu.top/Article/details/gtjjotibbe.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.sweek.top/Article/details/gtaqohxqsl.html

TS:   if (!x) {}
来源：http://dali.yonumen.top/Article/details/gtxzinnfqb.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.wangdashe.top/Article/details/gtvnpcmluo.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.yongpay.top/Article/details/gtcrdusgrl.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.vqdsnc.cn/Article/details/gtvgnvpbht.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.aibaodan.cn/Article/details/gtufchhptk.html

[A17] 位运算
来源：http://dali.hnqzz.top/Article/details/gthhgsngzm.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yvedp.cn/Article/details/gtgzmmkjsb.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gtemjernvp.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.jqgfzy.top/Article/details/gthzpmpqkr.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtoygxrdfl.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.mhx1999.top/Article/details/gtmgyawaoz.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.316326.xyz/Article/details/gtcpbfexwf.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yuanzhike.top/Article/details/gtdpqtgpgo.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtnvzuedsy.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cdnleiting.top/Article/details/gttadzgdro.html

Py:   ord("A"); chr(65)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljhnqiin.html

PHP:  ord("A"); chr(65)
来源：http://dali.zycfv.cn/Article/details/gtfrcjhbpc.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyrreceg.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zhongyouzk.top/Article/details/gtlvecrtvc.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhoulong.xyz/Article/details/gtitditowb.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.birdmap.top/Article/details/gttkwdamtw.html

Ruby: "A".ord; 65.chr
来源：http://dali.yueranfly.top/Article/details/gtwgmuinng.html

C#:   (int)'A'; (char)65
来源：http://dali.chenlongwang.top/Article/details/gtvmtdydyb.html

[A19] 交换两个变量
来源：http://dali.gotoacloud.top/Article/details/gtmjkdrdep.html

Py:   a, b = b, a
来源：http://dali.xinyue.icu/Article/details/gtenxsvtxj.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.yj20258888.top/Article/details/gtkssmkuep.html

JS:   [a, b] = [b, a];
来源：http://dali.cqqwz.cn/Article/details/gtbrizrnsw.html

TS:   [a, b] = [b, a];
来源：http://dali.zhijiandao.cn/Article/details/gtiptkpwwg.html

Java: int t = a; a = b; b = t;
来源：http://dali.haohaochexian.top/Article/details/gtchqucptf.html

Go:   a, b = b, a
来源：http://dali.xuetiantiany.cn/Article/details/gtbuolwcuv.html

Ruby: a, b = b, a
来源：http://dali.hongshengwenyu.top/Article/details/gtwxihixux.html

C#:   (a, b) = (b, a);
来源：http://dali.gotoacloud.top/Article/details/gtjaqwfuxi.html

[A20] 读取标准输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwrntmfre.html

Py:   name = input("请输入：")
来源：http://dali.zdqjudy.top/Article/details/gtiorslxpy.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ybcxt.top/Article/details/gttfnldrqd.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.shzxlz.cn/Article/details/gtxkpzvfqw.html

TS:   // Node.js：readline 模块
来源：http://dali.cashguo.top/Article/details/gtjvjlywsy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.xziqi.cn/Article/details/gtvgposglu.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.zhongyouzk.top/Article/details/gtsotvhwcv.html

Ruby: gets.chomp
来源：http://dali.redwolf501.top/Article/details/gtmpzvlleh.html

C#:   Console.ReadLine();
来源：http://dali.snrcjt.cn/Article/details/gtatyymvwu.html

[A21] 保留指定小数位输出
来源：http://dali.chenjidiqi.icu/Article/details/gtwdzntszv.html

Py:   f"{3.14159:.2f}"
来源：http://dali.yj20258888.top/Article/details/gtxakfmvxk.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.xuanzx.com/Article/details/gtxctepkha.html

JS:   (3.14159).toFixed(2)
来源：http://dali.jqgufenzy.top/Article/details/gtcpaknovc.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcbociss.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzstevfn.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.feifeiyinyue.top/Article/details/gtjhtypary.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.yonumen.top/Article/details/gtfmofhacx.html

C#:   3.14159.ToString("F2")
来源：http://dali.cashguo.top/Article/details/gtfxpxddjp.html

[A22] 获取字符串长度
来源：http://dali.daxiang520.top/Article/details/gtpltdbkhc.html

Py:   len(s)
来源：http://dali.daria6918.cn/Article/details/gtifrnfdlt.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.sufxvd.cn/Article/details/gtypkrfgsg.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.tanke756.top/Article/details/gtdueiedcl.html

TS:   s.length
来源：http://dali.yongpay.top/Article/details/gthjzevhbe.html

Java: s.length()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkrboccrr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.dashuyun.cn/Article/details/gtvzjghewr.html

Ruby: s.length
来源：http://dali.316326.xyz/Article/details/gtssvycxol.html

C#:   s.Length
来源：http://dali.hnqzz.top/Article/details/gtzavqbsbc.html

[A23] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtiqtwmlbl.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.zhoulong.xyz/Article/details/gtbhybvfyf.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.meibo888.top/Article/details/gtxamxznwl.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.chenlongwang.top/Article/details/gtoqdexpeg.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtbymafgnv.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.guowangkeji.top/Article/details/gtrwreevvk.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtimmepwrn.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.gogol.net.cn/Article/details/gtoythuavf.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthqcbbce.html

[A24] 去除首尾空白
来源：http://dali.zhiwuduotai.top/Article/details/gtmalqmbyd.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhongyouzk.top/Article/details/gtbqjbfkcd.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.jlsjyb.cn/Article/details/gtlsqpthdd.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.yangfankeji.com/Article/details/gtnbsrownz.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.redwolf501.top/Article/details/gtzwyzsvop.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.daxiang520.top/Article/details/gtsinfgvwv.html

Go:   strings.TrimSpace(s)
来源：http://dali.hfpthk.cn/Article/details/gtciipfxgc.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.jinghuilouyu.cn/Article/details/gtlmniayae.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ppjwa.cn/Article/details/gtaxikuipx.html

[A25] 字符串比较
来源：http://dali.xinyue.icu/Article/details/gtrvwpduwz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xuetiantiany.cn/Article/details/gtvmpafhyf.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.jiagoushi.top/Article/details/gtthpssxjw.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.iojbl.cn/Article/details/gtgldkauwt.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.haohaochexian.top/Article/details/gtmfwlheoj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.sufxvd.cn/Article/details/gtlzdafbpz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.quarkkingdee.top/Article/details/gtzoizqaxd.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.tian-w.cn/Article/details/gtpecjaxzc.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.aizwys.cn/Article/details/gtklwagwrd.html

[A26] 类型转换总览
来源：http://dali.birdmap.top/Article/details/gtbtdsmfnf.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.birdmap.top/Article/details/gtmvireyog.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.aibaodan.cn/Article/details/gtsjkinytq.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.daria6918.cn/Article/details/gtvxcfvjpt.html

TS:   Number() String() Boolean() x as number
来源：http://dali.aibaodan.cn/Article/details/gtqgipydhr.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.yueranfly.top/Article/details/gtjflkwffn.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.yueranfly.top/Article/details/gthgcmcyui.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.iojbl.cn/Article/details/gthowghazl.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.yanxiufei.cn/Article/details/gtosyuryba.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtbxbanyft.html

B. 流程控制
来源：http://dali.bjfxy.top/Article/details/gtdotriqsf.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtqifxtezq.html

[B01] 条件判断 if / else
来源：http://dali.zhoulong.xyz/Article/details/gtrwfivjge.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zhijiandao.cn/Article/details/gtlfeaekta.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.sysykeji.top/Article/details/gtpdolktzs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.wangshuangyany.cn/Article/details/gtjhnrknhk.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.hfpthk.cn/Article/details/gtcyyqebij.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.0kj1m.cn/Article/details/gtunkkujbe.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.yuanzhike.top/Article/details/gtgfvvjeba.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.gogol.net.cn/Article/details/gtpklcrdwj.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gtfmlpzepf.html

[B02] 多分支 else if / elif
来源：http://dali.hysaishi.cn/Article/details/gtndulxoae.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yuanzhike.top/Article/details/gtrlcghnpm.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.shzxlz.cn/Article/details/gtqadwqpgk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zhixingplan.top/Article/details/gtsxyntemr.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtureayjmw.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hongshengwenyu.top/Article/details/gtmnrdlzuk.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.sxryk.cn/Article/details/gtkgojucqc.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.haohaochexian.top/Article/details/gtsfuwpkft.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.hysaishi.cn/Article/details/gtjdrnibiw.html

[B03] switch / match / case
来源：http://dali.yuxming.cn/Article/details/gtryokiojd.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yongpay.top/Article/details/gturyzatqh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtmcqipmlq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.bjfxy.top/Article/details/gtrxgjctfn.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yj202588.top/Article/details/gtagdfgabh.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtjuauzejm.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtdqfwrlai.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.quarkkingdee.top/Article/details/gtsgfxpiit.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.snrcjt.cn/Article/details/gtksnailnt.html

[B04] for 计数循环
来源：http://dali.yonumen.top/Article/details/gtcxcgzcaj.html

Py:   for i in range(10): print(i)
来源：http://dali.pycfn.com/Article/details/gthpsolqbu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.xziqi.cn/Article/details/gtudynhxli.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yongpay.top/Article/details/gtzzfzwjcj.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.cheryme.top/Article/details/gtzplbrmgp.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.fengsongda.top/Article/details/gttmghunoh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.gzhubu.top/Article/details/gtguwvunff.html

Ruby: 10.times { |i| puts i }
来源：http://dali.iojbl.cn/Article/details/gtcsfmpmfg.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.meibo888.top/Article/details/gtxxjzipqq.html

[B05] 遍历数组 / 列表
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisgbmpdu.html

Py:   for item in arr: print(item)
来源：http://dali.haohaochexian.top/Article/details/gtjfviayak.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.smart0.xyz/Article/details/gtfhdnifbe.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.cashguo.top/Article/details/gtiohkuiol.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtgzxnithe.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.jqgfzy.top/Article/details/gtdlvtgosn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gogol.net.cn/Article/details/gtdnbeptst.html

Ruby: arr.each { |item| puts item }
来源：http://dali.mhx1999.top/Article/details/gtuapjcmox.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.snrcjt.cn/Article/details/gtirvuhgvg.html

[B06] 遍历字典 / 对象
来源：http://dali.hysaishi.cn/Article/details/gtnwstrgtt.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.hnxiangtu.top/Article/details/gtgjnhspmm.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yongpay.top/Article/details/gtixysxttg.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cdnleiting.top/Article/details/gtvnlyxdbc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.tianlin.xyz/Article/details/gtxtprnind.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.vqdsnc.cn/Article/details/gthxfloela.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yangfankeji.com/Article/details/gttwjbvmsl.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gzhubu.top/Article/details/gtxmkchhmx.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.dianchejie.cn/Article/details/gtjmvmakop.html

[B07] while 循环
来源：http://dali.sufxvd.cn/Article/details/gtpbrgscbc.html

Py:   while i < 10: i += 1
来源：http://dali.hnxiangtu.top/Article/details/gtipyqjamd.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gtgbfxgliv.html

JS:   while (i < 10) { i++; }
来源：http://dali.9152youxi.cn/Article/details/gtfkbajdoh.html

TS:   while (i < 10) { i++; }
来源：http://dali.ydzc1.top/Article/details/gtxgekjymm.html

Java: while (i < 10) { i++; }
来源：http://dali.smart0.xyz/Article/details/gtkgkpwmtt.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.tanke756.top/Article/details/gtpvgczuox.html

Ruby: while i < 10; i += 1; end
来源：http://dali.cdnleiting.top/Article/details/gtskpxczpl.html

C#:   while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtshtzrrxl.html

[B08] do-while（至少执行一次）
来源：http://dali.yj20258.top/Article/details/gtumgiqbjy.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtpxbzzlib.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.haohaochexian.top/Article/details/gtpvcrjxwi.html

JS:   do { i++; } while (i < 10);
来源：http://dali.andypj.xyz/Article/details/gtmnzvukyq.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtvtbsfjcj.html

Java: do { i++; } while (i < 10);
来源：http://dali.ppjwa.cn/Article/details/gtuznupodb.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.ivvv.top/Article/details/gtmilhcnam.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.xuetiantiany.cn/Article/details/gtpwriudsj.html

C#:   do { i++; } while (i < 10);
来源：http://dali.guowangkeji.top/Article/details/gtsbjgwpxb.html

[B09] break 与 continue
来源：http://dali.sufxvd.cn/Article/details/gtumqccehk.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.yj20258.top/Article/details/gtqnklbqol.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gtlmtjxfni.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.smart0.xyz/Article/details/gtaeafbuff.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.fzhhl.top/Article/details/gtuqamkokg.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.birdmap.top/Article/details/gtvtmetinu.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yuxming.cn/Article/details/gtdrgylbut.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.nanxinkj.top/Article/details/gtyxxepoxx.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yj20258888.top/Article/details/gtlvlduyxw.html

[B10] 遍历同时拿索引
来源：http://dali.chenlongwang.top/Article/details/gtdiyzsbsc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.redwolf501.top/Article/details/gtjthefouk.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.gzhubu.top/Article/details/gtuailsbyi.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.aibaodan.cn/Article/details/gtclkwdfso.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.gaohongyu789.top/Article/details/gtrslqxlhb.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yonumen.top/Article/details/gtkzudtgve.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.hfpthk.cn/Article/details/gtzdcaaujr.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.jiagoushi.top/Article/details/gtmkixbxia.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yvedp.cn/Article/details/gtjmbniuav.html

[B11] 生成数字序列 / 区间
来源：http://dali.pycfn.com/Article/details/gtasxltjpj.html

Py:   list(range(0, 10, 2))
来源：http://dali.gotoacloud.top/Article/details/gtzcauuqlq.html

PHP:  range(0, 10, 2);
来源：http://dali.chenzaomai.com/Article/details/gtvybugjjw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.birdmap.top/Article/details/gtzfzrgwrt.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.nwbrower.top/Article/details/gttfwlnwwl.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.xuanzx.com/Article/details/gtbvxpxjyd.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.snrcjt.cn/Article/details/gtpnocbsui.html

Ruby: (0...10).step(2).to_a
来源：http://dali.wangshuangyany.cn/Article/details/gtdcmuoqic.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.yj20258888.top/Article/details/gtffvgwtfn.html

[B12] 跳出多层循环
来源：http://dali.nanxinkj.top/Article/details/gtuhhfmdep.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.cashguo.top/Article/details/gtvmunexjo.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.pengpengdd.cyou/Article/details/gtmdxnglgc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.0kj1m.cn/Article/details/gtuyvvayut.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.tanke756.top/Article/details/gtihkyfdza.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtewbgltef.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.ehwqpu.com/Article/details/gtpucwftbo.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.zhijiandao.cn/Article/details/gtwopbbpcg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.ivvv.top/Article/details/gtvezyrmhq.html

[B13] 判断是否为数字
来源：http://dali.wangdashe.top/Article/details/gtbugnhewl.html

Py:   isinstance(x, (int, float))
来源：http://dali.tianlin.xyz/Article/details/gtyglyqdox.html

PHP:  is_numeric($x)
来源：http://dali.aibaodan.cn/Article/details/gtiksusbux.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jinghuilouyu.cn/Article/details/gtjiuqdolw.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yj202588.top/Article/details/gtvkvklvig.html

Java: x instanceof Number
来源：http://dali.9152youxi.cn/Article/details/gteoqaajvc.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.jqgfzy.top/Article/details/gtnzwgolwt.html

Ruby: x.is_a?(Numeric)
来源：http://dali.ivvv.top/Article/details/gtzmsmzeyh.html

C#:   x is int or double or decimal
来源：http://dali.jlsjyb.cn/Article/details/gtzymsiiyv.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtbnmzxrcg.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.ehwqpu.com/Article/details/gtnxzyhffh.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.yj202588.top/Article/details/gtekzokjlc.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.aizwys.cn/Article/details/gtxntqzbvv.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtzwrtuydi.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.jianghu66.top/Article/details/gtzisgeqju.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xziqi.cn/Article/details/gtkpqwlpqc.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.shzxlz.cn/Article/details/gtpvnddegd.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.chenzaomai.com/Article/details/gtegjsqpmn.html

[B15] 布尔运算与取反
来源：http://dali.zhengqikj.top/Article/details/gtckrvmlwj.html

Py:   a and b or not c
来源：http://dali.quarkkingdee.top/Article/details/gtvpwesxps.html

PHP:  $a && $b || !$c
来源：http://dali.zycfv.cn/Article/details/gtoarczcur.html

JS:   a && b || !c
来源：http://dali.aizwys.cn/Article/details/gtpdxojhqq.html

TS:   a && b || !c
来源：http://dali.svipenyu.cn/Article/details/gtrpwtkhdb.html

Java: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtbufhtqth.html

Go:   a && b || !c
来源：http://dali.hnqzz.top/Article/details/gtcbvajisu.html

Ruby: a && b || !c
来源：http://dali.c1oappe.top/Article/details/gtpkyecwka.html

C#:   a && b || !c
来源：http://dali.sweek.top/Article/details/gtlvgwbikx.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhixingplan.top/Article/details/gtcskbinps.html

Py:   if not data: return
来源：http://dali.yvedp.cn/Article/details/gtusyxdtjz.html

PHP:  if (!$data) { return; }
来源：http://dali.hywenlv.cn/Article/details/gtnruvjfiw.html

JS:   if (!data) return;
来源：http://dali.zhoulong.xyz/Article/details/gtsnggyphj.html

TS:   if (!data) return;
来源：http://dali.tian-w.cn/Article/details/gtbwizhqtr.html

Java: if (data == null) return;
来源：http://dali.pycfn.com/Article/details/gtaefsvlxl.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gtlycftgnk.html

Ruby: return if data.nil?
来源：http://dali.ivvv.top/Article/details/gtnihgcjcb.html

C#:   if (data == null) return;
来源：http://dali.yj202588.top/Article/details/gtqpnvxqsw.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtobgxedvl.html

C. 函数与作用域
来源：http://dali.kuanghao11.cn/Article/details/gtbqkctzos.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzewwrbvm.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gtuckrmenv.html

Py:   def add(a, b): return a + b
来源：http://dali.dianchejie.cn/Article/details/gtjefjksys.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.shuidangran.top/Article/details/gtrlwxnmnz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.daxiang520.top/Article/details/gtjfphelet.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.xuanzx.com/Article/details/gtvqbosbrh.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.hnqzz.top/Article/details/gtzbuncvfq.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtaymabtkl.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zdqjudy.top/Article/details/gtujuamaim.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.haohaochexian.top/Article/details/gtqokwdpdv.html

[C02] 默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdziybqge.html

Py:   def greet(name="World"): return name
来源：http://dali.guowangkeji.top/Article/details/gtbamvfzbu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.zycfv.cn/Article/details/gtojajmtvu.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yongpay.top/Article/details/gtgmgrphvu.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gtjecmtvcl.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.zhiwuduotai.top/Article/details/gtzrfocits.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.nanxinkj.top/Article/details/gtjzazhxvd.html

Ruby: def greet(name = "World") = name
来源：http://dali.xinyue.icu/Article/details/gtncgzrxxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.cdnleiting.top/Article/details/gtlklevnsk.html

[C03] 可变参数
来源：http://dali.jyoumei.cn/Article/details/gtszhwcgpl.html

Py:   def total(*args): return sum(args)
来源：http://dali.sysykeji.top/Article/details/gtktbtnezz.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daria6918.cn/Article/details/gtxfaaebjv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gtuieevqko.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jinqigfzy.top/Article/details/gtwcxzcdie.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.chenzaomai.com/Article/details/gtydxaepry.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.chenzaomai.com/Article/details/gtcsykapil.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.iojbl.cn/Article/details/gteyrpiawt.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.jinghuilouyu.cn/Article/details/gtydhvozvz.html

[C04] 命名参数 / 关键字参数
来源：http://dali.quarkkingdee.top/Article/details/gtwrpnygfn.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.zhijiandao.cn/Article/details/gtxaarrkzx.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.gzhubu.top/Article/details/gtggobdsul.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.jqgfzy.top/Article/details/gtphtlllwv.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.aibaodan.cn/Article/details/gtzthaiqdg.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gtyssyufpu.html

Go:   // 无：用配置结构体参数
来源：http://dali.sweek.top/Article/details/gticzrwaoh.html

Ruby: f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmfinqqqf.html

C#:   f(a: 1, b: 2)
来源：http://dali.zhijiandao.cn/Article/details/gtywuxecpf.html

[C05] 返回多个值
来源：http://dali.cqqwz.cn/Article/details/gtzcroaqcj.html

Py:   return a, b
来源：http://dali.zhongyouzk.top/Article/details/gtnjjzwyma.html

PHP:  return [$a, $b];
来源：http://dali.zhoulong.xyz/Article/details/gtlxffaqlv.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yongpay.top/Article/details/gtnisqbjfb.html

TS:   return { a, b };
来源：http://dali.aibaodan.cn/Article/details/gtmcksiuec.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.ppjwa.cn/Article/details/gtgsvaraeb.html

Go:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtgkvltfeg.html

Ruby: return a, b
来源：http://dali.xziqi.cn/Article/details/gtistzizid.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.aibaodan.cn/Article/details/gtexoldfxa.html

[C06] 匿名函数 / lambda
来源：http://dali.jqgufenzy.top/Article/details/gtvbquddvn.html

Py:   square = lambda x: x * x
来源：http://dali.andypj.xyz/Article/details/gtnbkhdman.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.zhoulong.xyz/Article/details/gttqhvohtx.html

JS:   const square = x => x * x;
来源：http://dali.zhengqikj.top/Article/details/gtheraongg.html


<!-- 参考信息 -->