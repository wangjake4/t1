代发 wailian999

PHP:  if (empty($x)) {}   # 松散比较，注意 "0"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttuosjjfg.html

JS:   if (!x) {}         # 0 "" null undefined NaN false 为假
来源：http://dali.jqgfzy.top/Article/details/gtlepkvsjg.html

TS:   if (!x) {}
来源：http://dali.wangshuangyany.cn/Article/details/gtmihqqpqq.html

Java: if (!Boolean.TRUE.equals(flag)) {}
来源：http://dali.jqgfzy.top/Article/details/gtjcukykmu.html

Go:   if x == "" || x == 0 {}   # 无隐式布尔转换
来源：http://dali.vqdsnc.cn/Article/details/gtarjumrir.html

Ruby: unless x            # nil 与 false 为假
来源：http://dali.sufxvd.cn/Article/details/gtvnhduzpl.html

C#:   if (string.IsNullOrEmpty(x)) {}
来源：http://dali.cheryme.top/Article/details/gtevadpebb.html

[A17] 位运算
来源：http://dali.chenjidiqi.icu/Article/details/gtmmukxaab.html

Py:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.nwbrower.top/Article/details/gtnknoxwkd.html

PHP:  $a & $b; $a | $b; $a ^ $b; $a << 2; $a >> 1
来源：http://dali.guannengcc.top/Article/details/gtkbmovyov.html

JS:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.hysaishi.cn/Article/details/gtyshghtrz.html

TS:   a & b; a | b; a ^ b; a << 2; a >> 1
来源：http://dali.zhiwuduotai.top/Article/details/gtxbkzdubz.html

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.zhixingplan.top/Article/details/gtgvlpuazf.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.zhongyouzk.top/Article/details/gtgrwmdhjt.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.yonumen.top/Article/details/gtvcttjmko.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.pengpengdd.cyou/Article/details/gtmmvlmoix.html

[A18] 字符与 ASCII 码互转
来源：http://dali.cucudq.cn/Article/details/gthjpdapay.html

Py:   ord("A"); chr(65)
来源：http://dali.smart0.xyz/Article/details/gtldfuksjg.html

PHP:  ord("A"); chr(65)
来源：http://dali.mhx1999.top/Article/details/gtvwvhiiau.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.yj202588.top/Article/details/gtwjzrlnsw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.fengsongda.top/Article/details/gtwmxanbfc.html

Java: (int) 'A'; (char) 65
来源：http://dali.xylfe.cn/Article/details/gtjnhhprpe.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.316326.xyz/Article/details/gtjjfesexx.html

Ruby: "A".ord; 65.chr
来源：http://dali.hammf.cn/Article/details/gtkhmpxyii.html

C#:   (int)'A'; (char)65
来源：http://dali.gaohongyu789.top/Article/details/gtfpxwgnvw.html

[A19] 交换两个变量
来源：http://dali.vqdsnc.cn/Article/details/gtbulpavzm.html

Py:   a, b = b, a
来源：http://dali.0kj1m.cn/Article/details/gtqrvzetmi.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gtjqbbbqfg.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtnugjctoh.html

TS:   [a, b] = [b, a];
来源：http://dali.quarkkingdee.top/Article/details/gtianhnvki.html

Java: int t = a; a = b; b = t;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkymcyvkq.html

Go:   a, b = b, a
来源：http://dali.shanyushiyangtech.top/Article/details/gthvdreqpd.html

Ruby: a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gtanqlrpjf.html

C#:   (a, b) = (b, a);
来源：http://dali.jyoumei.cn/Article/details/gtuufyssqa.html

[A20] 读取标准输入
来源：http://dali.daria6918.cn/Article/details/gtvsvbwnev.html

Py:   name = input("请输入：")
来源：http://dali.daria6918.cn/Article/details/gtfkqokwyk.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.quarkkingdee.top/Article/details/gteobxlxte.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.daxiang520.top/Article/details/gtliidvhcg.html

TS:   // Node.js：readline 模块
来源：http://dali.jqgufenzy.top/Article/details/gtfffkwxww.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.jianghu66.top/Article/details/gtxmhwjped.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.hnqzz.top/Article/details/gtsrpkqgyz.html

Ruby: gets.chomp
来源：http://dali.dashuyun.cn/Article/details/gtvhcctdzg.html

C#:   Console.ReadLine();
来源：http://dali.cdnleiting.top/Article/details/gtsrpwyezm.html

[A21] 保留指定小数位输出
来源：http://dali.yangfankeji.com/Article/details/gtzhwvjtqo.html

Py:   f"{3.14159:.2f}"
来源：http://dali.xylfe.cn/Article/details/gtwocvkohw.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.yanxiufei.cn/Article/details/gthuzoyawz.html

JS:   (3.14159).toFixed(2)
来源：http://dali.0kj1m.cn/Article/details/gtjetqdtau.html

TS:   (3.14159).toFixed(2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobrrarfj.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.pycfn.com/Article/details/gtrzushwon.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gtxgdtiggg.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gtslczhwny.html

C#:   3.14159.ToString("F2")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzskiuzue.html

[A22] 获取字符串长度
来源：http://dali.cucudq.cn/Article/details/gttqtbhqqp.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gtizehyhgl.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.pycfn.com/Article/details/gttrslsbjw.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.nwbrower.top/Article/details/gtpmqzhwut.html

TS:   s.length
来源：http://dali.yj202588.top/Article/details/gtzxtlztsh.html

Java: s.length()
来源：http://dali.nanxinkj.top/Article/details/gtdnxjbmtq.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.zdqjudy.top/Article/details/gtltfdijyr.html

Ruby: s.length
来源：http://dali.hnqzz.top/Article/details/gtihzghggd.html

C#:   s.Length
来源：http://dali.zdqjudy.top/Article/details/gtnnbttmlq.html

[A23] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtnepdjujb.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklvzawyy.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.yanxiufei.cn/Article/details/gtxuxtsqmo.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yvedp.cn/Article/details/gtupbyfhno.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.yangfankeji.com/Article/details/gtmyscnxlo.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.9152youxi.cn/Article/details/gtqhwwxtdm.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.ybcxt.top/Article/details/gtxfgjpfbb.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.sweek.top/Article/details/gtzwenxdvy.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xuetiantiany.cn/Article/details/gtresnefqx.html

[A24] 去除首尾空白
来源：http://dali.tianlin.xyz/Article/details/gtvpsxydra.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhijiandao.cn/Article/details/gtexsedqfp.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.9152youxi.cn/Article/details/gtrjqtedfp.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gttzlhgjaw.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.xziqi.cn/Article/details/gtckekfuob.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.shangyingyoupin.top/Article/details/gtnhzwvqxp.html

Go:   strings.TrimSpace(s)
来源：http://dali.cucudq.cn/Article/details/gtzefigfmk.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.nanxuanxn.top/Article/details/gtvpiuhoqw.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.snrcjt.cn/Article/details/gtlvnrkldl.html

[A25] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtgbvrdtei.html

Py:   s1 == s2; s1 != s2
来源：http://dali.xinyue.icu/Article/details/gtzccewtqi.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdmgdifi.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.c1oappe.top/Article/details/gtigsshkbk.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.daria6918.cn/Article/details/gtczyklacs.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.jinqigufen.top/Article/details/gtczvouizi.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gthryhqwts.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.gzhubu.top/Article/details/gtzfvtxzsz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.zycfv.cn/Article/details/gtugyvmlfm.html

[A26] 类型转换总览
来源：http://dali.gotoacloud.top/Article/details/gtqrhkovqx.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pycfn.com/Article/details/gtpimkkgrv.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.9152youxi.cn/Article/details/gtoaaztkbw.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.cucudq.cn/Article/details/gtikuljxpv.html

TS:   Number() String() Boolean() x as number
来源：http://dali.guannengcc.top/Article/details/gtvrdpojrn.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gtedkumama.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.zdqjudy.top/Article/details/gtteeylwcc.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.daxiang520.top/Article/details/gtzpvitymg.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.birdmap.top/Article/details/gtcmcwpcqd.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtyojfkptq.html

B. 流程控制
来源：http://dali.jinghuilouyu.cn/Article/details/gtrvnccstm.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtlwozhhae.html

[B01] 条件判断 if / else
来源：http://dali.cucudq.cn/Article/details/gtljrllhcl.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.chenzaomai.com/Article/details/gtjszaqmrz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.jinqigfzy.top/Article/details/gthbpnsmsk.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtqvhqkuzi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhoulong.xyz/Article/details/gtqjahjpyk.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gtijlabstu.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.hongshengwenyu.top/Article/details/gtqoahzdes.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.redwolf501.top/Article/details/gthgsxmqdz.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.quarkkingdee.top/Article/details/gtwgyluzxl.html

[B02] 多分支 else if / elif
来源：http://dali.nanxinkj.top/Article/details/gtwybdxwec.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.pengpengdd.cyou/Article/details/gtonxdstav.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.dianchejie.cn/Article/details/gtktqnlfwm.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtafttlzgx.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.andypj.xyz/Article/details/gtsokikojc.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jyoumei.cn/Article/details/gtbgamxwrj.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.aizwys.cn/Article/details/gttpxufaib.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.tianlin.xyz/Article/details/gtqfqlxkkv.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtslutgvta.html

[B03] switch / match / case
来源：http://dali.iojbl.cn/Article/details/gtrwomxaxl.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.chenlongwang.top/Article/details/gtvskyzgni.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.zhongyouzk.top/Article/details/gtvsdltdzh.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.sxryk.cn/Article/details/gtqumajopu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.yuanzhike.top/Article/details/gteivultlv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.aizwys.cn/Article/details/gtmzdazscn.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgrpzeiiu.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.xziqi.cn/Article/details/gtnnenemhj.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gogol.net.cn/Article/details/gteaskcalr.html

[B04] for 计数循环
来源：http://dali.gzhubu.top/Article/details/gtgvffhect.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gtsygioqzn.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.meibo888.top/Article/details/gtbhvujxol.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtxextrghq.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.xuetiantiany.cn/Article/details/gtbmhftgtm.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.gogol.net.cn/Article/details/gtmcausorh.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.haohaochexian.top/Article/details/gtcoqkztwg.html

Ruby: 10.times { |i| puts i }
来源：http://dali.shangyingyoupin.top/Article/details/gtsfewjtwh.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.daxiang520.top/Article/details/gtuejbutms.html

[B05] 遍历数组 / 列表
来源：http://dali.yangfankeji.com/Article/details/gthmxqryme.html

Py:   for item in arr: print(item)
来源：http://dali.zdqjudy.top/Article/details/gtwsdgongv.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.tianlin.xyz/Article/details/gtzaonlaxq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnynseuuw.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.yj202588.top/Article/details/gtfzacnksj.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.wangshuangyany.cn/Article/details/gtamitgbgx.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.yangfankeji.com/Article/details/gtjaytwrif.html

Ruby: arr.each { |item| puts item }
来源：http://dali.daxiang520.top/Article/details/gtjlzunykr.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.shangyingyoupin.top/Article/details/gtmsspibtf.html

[B06] 遍历字典 / 对象
来源：http://dali.jianghu66.top/Article/details/gtueggndif.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.iojbl.cn/Article/details/gtloylyutw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.vqdsnc.cn/Article/details/gtdlimzahf.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.yonumen.top/Article/details/gtlhcnkdyp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.guannengcc.top/Article/details/gtnhjniwll.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.chenzaomai.com/Article/details/gtayzmwnsv.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.sweek.top/Article/details/gtqjrzvkhr.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.gogol.net.cn/Article/details/gtzfrhdwzt.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.yj202588.top/Article/details/gtccyobvcl.html

[B07] while 循环
来源：http://dali.chenjidiqi.icu/Article/details/gtsmrchmqv.html

Py:   while i < 10: i += 1
来源：http://dali.jinqigufen.top/Article/details/gtvkuxhizh.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdswjrtcf.html

JS:   while (i < 10) { i++; }
来源：http://dali.daria6918.cn/Article/details/gtcbgcuywj.html

TS:   while (i < 10) { i++; }
来源：http://dali.jlsjyb.cn/Article/details/gtdmassfzl.html

Java: while (i < 10) { i++; }
来源：http://dali.yangfankeji.com/Article/details/gtuntzlizp.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.9152youxi.cn/Article/details/gtyffltkrv.html

Ruby: while i < 10; i += 1; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzwpbpuw.html

C#:   while (i < 10) { i++; }
来源：http://dali.jqgfzy.top/Article/details/gttkwfvqnk.html

[B08] do-while（至少执行一次）
来源：http://dali.jinqigufen.top/Article/details/gtcfuzjqyq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.cdnleiting.top/Article/details/gtqtkoiaac.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hammf.cn/Article/details/gtmvjzljcq.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtldizunmo.html

TS:   do { i++; } while (i < 10);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqazafzgg.html

Java: do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtyvdrfdcy.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.yueranfly.top/Article/details/gtooovtpgp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.yvedp.cn/Article/details/gttljqbmie.html

C#:   do { i++; } while (i < 10);
来源：http://dali.nwbrower.top/Article/details/gtspkboyck.html

[B09] break 与 continue
来源：http://dali.hfpthk.cn/Article/details/gtzucwdpft.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtswevpqma.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.snrcjt.cn/Article/details/gtjyhgecgp.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.tanke756.top/Article/details/gtcfchmeqk.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.gaohongyu789.top/Article/details/gtxyigoypw.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shangyingyoupin.top/Article/details/gtucsryjmj.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.yanxiufei.cn/Article/details/gtanfdqyzm.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.guowangkeji.top/Article/details/gtbunisnpo.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.daxiang520.top/Article/details/gthrsjmere.html

[B10] 遍历同时拿索引
来源：http://dali.hnxiangtu.top/Article/details/gtaroqcvfc.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.wangshuangyany.cn/Article/details/gtrsgyjzlo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.sysykeji.top/Article/details/gtehrpbrit.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.ppjwa.cn/Article/details/gtefbqhdra.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.hfpthk.cn/Article/details/gtburopssl.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.mhx1999.top/Article/details/gtfwuplxtc.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.316326.xyz/Article/details/gtbwvbttln.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.shzxlz.cn/Article/details/gtgogwybgz.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.zdqjudy.top/Article/details/gtpkabitwv.html

[B11] 生成数字序列 / 区间
来源：http://dali.vqdsnc.cn/Article/details/gtbebfdqsv.html

Py:   list(range(0, 10, 2))
来源：http://dali.yonumen.top/Article/details/gtfhazbtvk.html

PHP:  range(0, 10, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtmeukwxbx.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtaogwvtjo.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.0kj1m.cn/Article/details/gtahjqwcfm.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.yuxming.cn/Article/details/gtsvlstsos.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.nanxinkj.top/Article/details/gtpyejlxck.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenjidiqi.icu/Article/details/gtsohuausb.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.shuidangran.top/Article/details/gtblbftcmq.html

[B12] 跳出多层循环
来源：http://dali.sxryk.cn/Article/details/gtohoajcgq.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yongpay.top/Article/details/gtrylnuxbz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.ybcxt.top/Article/details/gtekfhnjwa.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.jinqigfzy.top/Article/details/gtkrggomml.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gtmagcxvfs.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.meibo888.top/Article/details/gtnrtgtvoc.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.xylfe.cn/Article/details/gtxxcakema.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.aizwys.cn/Article/details/gtivwojyrm.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.xuanzx.com/Article/details/gttbpqywup.html

[B13] 判断是否为数字
来源：http://dali.xuetiantiany.cn/Article/details/gtzfxurokm.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gtnjelibmr.html

PHP:  is_numeric($x)
来源：http://dali.svipenyu.cn/Article/details/gtgmofdgcv.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.gzhubu.top/Article/details/gtkzgdrqha.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yueranfly.top/Article/details/gtbveynrgy.html

Java: x instanceof Number
来源：http://dali.zhongyouzk.top/Article/details/gtwhmiosad.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gtqjkhbnys.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zycfv.cn/Article/details/gtkslekuvj.html

C#:   x is int or double or decimal
来源：http://dali.cashguo.top/Article/details/gtencgiagk.html

[B14] 判断值是否在集合内
来源：http://dali.kuanghao11.cn/Article/details/gtvlrlmymy.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.vqdsnc.cn/Article/details/gtcpiidwuf.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.dashuyun.cn/Article/details/gtypdjwgap.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.vqdsnc.cn/Article/details/gtupdsgybl.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.snrcjt.cn/Article/details/gtheenodor.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.zhengqikj.top/Article/details/gtebwqjekd.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.hfpthk.cn/Article/details/gtdrlsgxhg.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.hywenlv.cn/Article/details/gtyldksqul.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jinqigfzy.top/Article/details/gtsltdacmv.html

[B15] 布尔运算与取反
来源：http://dali.xinyue.icu/Article/details/gtfrkdddhg.html

Py:   a and b or not c
来源：http://dali.haohaochexian.top/Article/details/gttfambqbn.html

PHP:  $a && $b || !$c
来源：http://dali.cashguo.top/Article/details/gtlporrjdn.html

JS:   a && b || !c
来源：http://dali.cashguo.top/Article/details/gtctinauhn.html

TS:   a && b || !c
来源：http://dali.9152youxi.cn/Article/details/gtyiporiea.html

Java: a && b || !c
来源：http://dali.andypj.xyz/Article/details/gtazguzcgw.html

Go:   a && b || !c
来源：http://dali.xuanzx.com/Article/details/gttwbzwkbd.html

Ruby: a && b || !c
来源：http://dali.guannengcc.top/Article/details/gtjnoijnxv.html

C#:   a && b || !c
来源：http://dali.daria6918.cn/Article/details/gtxykzfkzo.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtjxshxhzj.html

Py:   if not data: return
来源：http://dali.cashguo.top/Article/details/gtxnjmaknr.html

PHP:  if (!$data) { return; }
来源：http://dali.chenlongwang.top/Article/details/gtrydrrjvq.html

JS:   if (!data) return;
来源：http://dali.xziqi.cn/Article/details/gtarvwwxfa.html

TS:   if (!data) return;
来源：http://dali.hfpthk.cn/Article/details/gtvrjlllst.html

Java: if (data == null) return;
来源：http://dali.hysaishi.cn/Article/details/gtkzrkaeql.html

Go:   if data == nil { return }
来源：http://dali.nwbrower.top/Article/details/gtsyyoqbrk.html

Ruby: return if data.nil?
来源：http://dali.guannengcc.top/Article/details/gthbhqpgxi.html

C#:   if (data == null) return;
来源：http://dali.chenlongwang.top/Article/details/gtwfoixyro.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtjjybaruz.html

C. 函数与作用域
来源：http://dali.zhoulong.xyz/Article/details/gtvgwyfqbz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkvqncakw.html

[C01] 定义函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrlnnwcj.html

Py:   def add(a, b): return a + b
来源：http://dali.0kj1m.cn/Article/details/gtmsgoxvaz.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtnegdujjz.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.nanxinkj.top/Article/details/gtnvsltead.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.snrcjt.cn/Article/details/gtvjevhyjc.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.jqgfzy.top/Article/details/gtaiowykjr.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.daria6918.cn/Article/details/gtxuxnnstq.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hnqzz.top/Article/details/gtjmzpitkf.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.yuxming.cn/Article/details/gthcbygrum.html

[C02] 默认参数
来源：http://dali.zhoulong.xyz/Article/details/gtbylfibwk.html

Py:   def greet(name="World"): return name
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtruhzottg.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.guannengcc.top/Article/details/gtymkbiohx.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.nanxinkj.top/Article/details/gtpyvlvpfc.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcrdcxycr.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.kuanghao11.cn/Article/details/gtuilxrhpo.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.redwolf501.top/Article/details/gtdpeymvei.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtvybcirrk.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtxgctxpqo.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gthhgeknqh.html

Py:   def total(*args): return sum(args)
来源：http://dali.ppjwa.cn/Article/details/gttywxbpjp.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.bjfxy.top/Article/details/gtmqhbxxrv.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.xylfe.cn/Article/details/gtfzwybogj.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cheryme.top/Article/details/gtizdvstqu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgixenmyz.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yuanzhike.top/Article/details/gtdscvxupg.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.yvedp.cn/Article/details/gtcskztcnv.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.chenjidiqi.icu/Article/details/gtudaulpwj.html

[C04] 命名参数 / 关键字参数
来源：http://dali.hongshengwenyu.top/Article/details/gtdqsnrkoc.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.chenjidiqi.icu/Article/details/gtjvjnwnax.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.chenzaomai.com/Article/details/gtvoqrjcov.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.zhiwuduotai.top/Article/details/gtyuqbggqs.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.bjfxy.top/Article/details/gttkbpwhps.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.ehwqpu.com/Article/details/gtcvpigmll.html

Go:   // 无：用配置结构体参数
来源：http://dali.jinqigufen.top/Article/details/gtfmnihhnx.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gtsswyppik.html

C#:   f(a: 1, b: 2)
来源：http://dali.svipenyu.cn/Article/details/gtbmfjlabl.html

[C05] 返回多个值
来源：http://dali.yuxming.cn/Article/details/gtbhtmxfma.html

Py:   return a, b
来源：http://dali.dianchejie.cn/Article/details/gtzgjrslkp.html

PHP:  return [$a, $b];
来源：http://dali.ivvv.top/Article/details/gtwotpurky.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.yuanzhike.top/Article/details/gtwmukqlms.html

TS:   return { a, b };
来源：http://dali.fengsongda.top/Article/details/gtwzfynvpf.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.iojbl.cn/Article/details/gtwseofvsg.html

Go:   return a, b
来源：http://dali.sysykeji.top/Article/details/gtkwhbhljz.html

Ruby: return a, b
来源：http://dali.ppjwa.cn/Article/details/gtmnxdutkt.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.xuetiantiany.cn/Article/details/gttrlucgtx.html

[C06] 匿名函数 / lambda
来源：http://dali.c1oappe.top/Article/details/gtcweacncd.html

Py:   square = lambda x: x * x
来源：http://dali.daria6918.cn/Article/details/gtoejkpffk.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.andypj.xyz/Article/details/gttltmpxtm.html

JS:   const square = x => x * x;
来源：http://dali.zhiwuduotai.top/Article/details/gtdvpmvnzn.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtfxgcbtob.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.yanxiufei.cn/Article/details/gtsevbvfcp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.chenzaomai.com/Article/details/gtojonmjzp.html

Ruby: square = ->(x) { x * x }
来源：http://dali.sweek.top/Article/details/gttlyvopup.html


<!-- 参考信息 -->