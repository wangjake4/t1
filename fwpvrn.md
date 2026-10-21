代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.iojbl.cn/Article/details/gtxwioqnrb.html

Py:   ord("A"); chr(65)
来源：http://dali.bjfxy.top/Article/details/gtusvudwen.html

PHP:  ord("A"); chr(65)
来源：http://dali.cashguo.top/Article/details/gtzxthgueb.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.bjfxy.top/Article/details/gtitjhmlqu.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hywenlv.cn/Article/details/gtultrgyxn.html

Java: (int) 'A'; (char) 65
来源：http://dali.yangfankeji.com/Article/details/gtxeghwdat.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.yanxiufei.cn/Article/details/gtnyjrncze.html

Ruby: "A".ord; 65.chr
来源：http://dali.svipenyu.cn/Article/details/gtfctlvdgk.html

C#:   (int)'A'; (char)65
来源：http://dali.ybcxt.top/Article/details/gtzggcojdv.html

[A19] 交换两个变量
来源：http://dali.shzxlz.cn/Article/details/gtfivmjjna.html

Py:   a, b = b, a
来源：http://dali.chenzaomai.com/Article/details/gtmppurxvv.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.nanxinkj.top/Article/details/gtzfhprkjs.html

JS:   [a, b] = [b, a];
来源：http://dali.nanxuanxn.top/Article/details/gtnmoocfjh.html

TS:   [a, b] = [b, a];
来源：http://dali.yuxming.cn/Article/details/gtnxgruvga.html

Java: int t = a; a = b; b = t;
来源：http://dali.daria6918.cn/Article/details/gtlxmwankg.html

Go:   a, b = b, a
来源：http://dali.jinqigufen.top/Article/details/gtumntsxjc.html

Ruby: a, b = b, a
来源：http://dali.yonumen.top/Article/details/gtltqdpiax.html

C#:   (a, b) = (b, a);
来源：http://dali.gaohongyu789.top/Article/details/gthaobbjat.html

[A20] 读取标准输入
来源：http://dali.sysykeji.top/Article/details/gtmprlekic.html

Py:   name = input("请输入：")
来源：http://dali.kuanghao11.cn/Article/details/gtnuxofbhv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.sysykeji.top/Article/details/gtmfidnrtj.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.hammf.cn/Article/details/gtjwdemgri.html

TS:   // Node.js：readline 模块
来源：http://dali.yangfankeji.com/Article/details/gtgpkdurfy.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.svipenyu.cn/Article/details/gtkuprhovo.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.wangdashe.top/Article/details/gtsnlrlilc.html

Ruby: gets.chomp
来源：http://dali.yj202588.top/Article/details/gtgytmhifu.html

C#:   Console.ReadLine();
来源：http://dali.quarkkingdee.top/Article/details/gtotwpjmfh.html

[A21] 保留指定小数位输出
来源：http://dali.cdnleiting.top/Article/details/gtftdqnaab.html

Py:   f"{3.14159:.2f}"
来源：http://dali.chenzaomai.com/Article/details/gtciyvihyl.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.zhiwuduotai.top/Article/details/gtzktyrvvd.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gtdtbfxtna.html

TS:   (3.14159).toFixed(2)
来源：http://dali.xylfe.cn/Article/details/gturwdzlrt.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkfnatul.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gtxofqupfx.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.hfpthk.cn/Article/details/gtdoupvvle.html

C#:   3.14159.ToString("F2")
来源：http://dali.shuidangran.top/Article/details/gtryxlroji.html

[A22] 获取字符串长度
来源：http://dali.pycfn.com/Article/details/gtyjdklmdm.html

Py:   len(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbnahwzrw.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkempwjq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sweek.top/Article/details/gtltepxpbn.html

TS:   s.length
来源：http://dali.aibaodan.cn/Article/details/gtrtjhlqgm.html

Java: s.length()
来源：http://dali.hywenlv.cn/Article/details/gtjrynvsyb.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.nanxinkj.top/Article/details/gtejqxkoug.html

Ruby: s.length
来源：http://dali.gotoacloud.top/Article/details/gtnyrceasy.html

C#:   s.Length
来源：http://dali.0kj1m.cn/Article/details/gtvktwjvdd.html

[A23] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gtyhulhkdn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jlsjyb.cn/Article/details/gtbvxkdpso.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.cdnleiting.top/Article/details/gtlgymmihr.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtxaqvmaay.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.fzhhl.top/Article/details/gtnmesaebk.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.yj20258888.top/Article/details/gttpcxnxft.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.cdnleiting.top/Article/details/gtgnfskhir.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.yueranfly.top/Article/details/gttwiabzgi.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.xziqi.cn/Article/details/gtnrkbliqt.html

[A24] 去除首尾空白
来源：http://dali.dianchejie.cn/Article/details/gtuoqkyfgs.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.sweek.top/Article/details/gtyfwuhkik.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.0kj1m.cn/Article/details/gtmqbffwee.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gteyzmnbjg.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.dashuyun.cn/Article/details/gtxqoszpbk.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.zhongyouzk.top/Article/details/gtvxjjgjex.html

Go:   strings.TrimSpace(s)
来源：http://dali.yongpay.top/Article/details/gtykjyoika.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hammf.cn/Article/details/gtjpwjpxkz.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.zhiwuduotai.top/Article/details/gtxexesoty.html

[A25] 字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtyilcmpyj.html

Py:   s1 == s2; s1 != s2
来源：http://dali.ybcxt.top/Article/details/gtdkuutsei.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gtiwaphxnb.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hywenlv.cn/Article/details/gtffilqkiu.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxfkffbzv.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.fzhhl.top/Article/details/gtautypiyk.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.0kj1m.cn/Article/details/gtfcswqfsv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.0kj1m.cn/Article/details/gtvzpvkyiz.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.hysaishi.cn/Article/details/gtfflqdwre.html

[A26] 类型转换总览
来源：http://dali.nanxinkj.top/Article/details/gtoxsdmtbq.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.pengpengdd.cyou/Article/details/gthwcsayjo.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.tanke756.top/Article/details/gtlyhdqmoj.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.hnqzz.top/Article/details/gtamxsgosr.html

TS:   Number() String() Boolean() x as number
来源：http://dali.jiagoushi.top/Article/details/gtkuteuxyf.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.fzhhl.top/Article/details/gtxtwugzbv.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.gaohongyu789.top/Article/details/gtcwoxhwsw.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.yanxiufei.cn/Article/details/gthmstnhwk.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.bjfxy.top/Article/details/gtpahbxxuf.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtewgnecfn.html

B. 流程控制
来源：http://dali.hysaishi.cn/Article/details/gtswnqzlqb.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtsstmkdww.html

[B01] 条件判断 if / else
来源：http://dali.9152youxi.cn/Article/details/gteidfuikp.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.xuetiantiany.cn/Article/details/gtcxeucxyn.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqjzeaslp.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.tianlin.xyz/Article/details/gthyarruik.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yuxming.cn/Article/details/gtdpihiudl.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.aizwys.cn/Article/details/gttzdozbdi.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.ybcxt.top/Article/details/gtjzradyzj.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkrjqdse.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.chenzaomai.com/Article/details/gtaawbymhm.html

[B02] 多分支 else if / elif
来源：http://dali.aizwys.cn/Article/details/gtvhhkudra.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.yj20258.top/Article/details/gtdqttjgwz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ydzc1.top/Article/details/gthidtleyk.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yuanzhike.top/Article/details/gtvfdxypaa.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.snrcjt.cn/Article/details/gtnheqykop.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.wangshuangyany.cn/Article/details/gtgunokbpt.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.xziqi.cn/Article/details/gtxcmbbzwe.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xylfe.cn/Article/details/gtlzcttnwb.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.cashguo.top/Article/details/gtnxeetafk.html

[B03] switch / match / case
来源：http://dali.aizwys.cn/Article/details/gtaxgxtfxo.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.yuanzhike.top/Article/details/gtanhnukln.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtysyzrimq.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.ivvv.top/Article/details/gtornzvhal.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hfpthk.cn/Article/details/gtihvmgppv.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtzqvfaiev.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.ybcxt.top/Article/details/gtuqwryrgy.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.sweek.top/Article/details/gtzhyndmug.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.jinghuilouyu.cn/Article/details/gtaamusgxg.html

[B04] for 计数循环
来源：http://dali.jlsjyb.cn/Article/details/gtzpgwfinl.html

Py:   for i in range(10): print(i)
来源：http://dali.iojbl.cn/Article/details/gtysvcpoer.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtieunlxcj.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.aibaodan.cn/Article/details/gthgxralze.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yonumen.top/Article/details/gtjjcrgmrh.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.havefunace.top/Article/details/gtlyiuisxg.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzndiaqgs.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sweek.top/Article/details/gtuytekrve.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.ivvv.top/Article/details/gtscphbsxk.html

[B05] 遍历数组 / 列表
来源：http://dali.daxiang520.top/Article/details/gtzzlecgvp.html

Py:   for item in arr: print(item)
来源：http://dali.havefunace.top/Article/details/gtciomtlmw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwqlwodsq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.ehwqpu.com/Article/details/gtjvyvcdvd.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhijiandao.cn/Article/details/gtnsrjdszg.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.mhx1999.top/Article/details/gtoqerwtfz.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtnhyzuhsq.html

Ruby: arr.each { |item| puts item }
来源：http://dali.c1oappe.top/Article/details/gtdkfzpzhy.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.cheryme.top/Article/details/gtpzwdkpks.html

[B06] 遍历字典 / 对象
来源：http://dali.hongshengwenyu.top/Article/details/gtbcjueuus.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.yuanzhike.top/Article/details/gtqzhqbsac.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.316326.xyz/Article/details/gtdfvekapk.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.redwolf501.top/Article/details/gthpbdcdmc.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.dashuyun.cn/Article/details/gtuvmexgfq.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.xziqi.cn/Article/details/gttudmgirp.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.ydzc1.top/Article/details/gthldkxlhf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.cqqwz.cn/Article/details/gtvvstntcg.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.xylfe.cn/Article/details/gtongtgflx.html

[B07] while 循环
来源：http://dali.bjfxy.top/Article/details/gtenndlvir.html

Py:   while i < 10: i += 1
来源：http://dali.ivvv.top/Article/details/gtvhuosbbg.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwyektkvs.html

JS:   while (i < 10) { i++; }
来源：http://dali.aibaodan.cn/Article/details/gtxlzxlivj.html

TS:   while (i < 10) { i++; }
来源：http://dali.hnxiangtu.top/Article/details/gtyleuctfj.html

Java: while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gtpjfqltao.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.kuanghao11.cn/Article/details/gtdgnqpmms.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pycfn.com/Article/details/gtugsujkzg.html

C#:   while (i < 10) { i++; }
来源：http://dali.andypj.xyz/Article/details/gtldkupckz.html

[B08] do-while（至少执行一次）
来源：http://dali.daria6918.cn/Article/details/gtvnbgrfwq.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.ehwqpu.com/Article/details/gtqiswlsor.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jlsjyb.cn/Article/details/gthsyzmsxy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.chenzaomai.com/Article/details/gtfumlipoa.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gaohongyu789.top/Article/details/gtpbajoaxj.html

Java: do { i++; } while (i < 10);
来源：http://dali.sweek.top/Article/details/gtpakmgfhd.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthxgcnbph.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.jinghuilouyu.cn/Article/details/gtqasxmayi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.iojbl.cn/Article/details/gtrdccivgq.html

[B09] break 与 continue
来源：http://dali.daria6918.cn/Article/details/gtglkgplwy.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.jinqigfzy.top/Article/details/gtepcytttu.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.bjfxy.top/Article/details/gtlfxpdhnr.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jqgfzy.top/Article/details/gtbeywrolx.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ybcxt.top/Article/details/gteqejmtyu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinqigfzy.top/Article/details/gtffzogxmw.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.ydzc1.top/Article/details/gtptkfrwhh.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.quarkkingdee.top/Article/details/gtfyzqcmln.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtmlsyyedo.html

[B10] 遍历同时拿索引
来源：http://dali.cqqwz.cn/Article/details/gtbbelancm.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhoulong.xyz/Article/details/gtwcphsscp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.hfpthk.cn/Article/details/gtdylarsvx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.hywenlv.cn/Article/details/gttddaxdof.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.tanke756.top/Article/details/gttbmeqenf.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.meibo888.top/Article/details/gtsrupxoea.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yj202588.top/Article/details/gtctihvass.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtilxfdywy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.bjfxy.top/Article/details/gtcslcgsqy.html

[B11] 生成数字序列 / 区间
来源：http://dali.yuxming.cn/Article/details/gtgrcsqvhj.html

Py:   list(range(0, 10, 2))
来源：http://dali.sufxvd.cn/Article/details/gtybmwbaef.html

PHP:  range(0, 10, 2);
来源：http://dali.fengsongda.top/Article/details/gtgkurgprz.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.pycfn.com/Article/details/gttgxcnexl.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.vqdsnc.cn/Article/details/gtdgyjuvaw.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.zdqjudy.top/Article/details/gtyabfyivt.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.gaohongyu789.top/Article/details/gtyfxalgdr.html

Ruby: (0...10).step(2).to_a
来源：http://dali.0kj1m.cn/Article/details/gthlizpdex.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthjimdvw.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedrskdix.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.hnxiangtu.top/Article/details/gtwmnuhudc.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.hongshengwenyu.top/Article/details/gtqmpvukkz.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.havefunace.top/Article/details/gtkgjxtpet.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnvimppng.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.hywenlv.cn/Article/details/gtcstjohlq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.hysaishi.cn/Article/details/gtlzwuubjr.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.hysaishi.cn/Article/details/gtvfgzerqg.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.havefunace.top/Article/details/gtoykywcic.html

[B13] 判断是否为数字
来源：http://dali.tianlin.xyz/Article/details/gtoolemiwp.html

Py:   isinstance(x, (int, float))
来源：http://dali.tanke756.top/Article/details/gtgkreqtwq.html

PHP:  is_numeric($x)
来源：http://dali.chenjidiqi.icu/Article/details/gthaekvbni.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbqxcbbh.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.cdnleiting.top/Article/details/gtkapntjgn.html

Java: x instanceof Number
来源：http://dali.yonumen.top/Article/details/gtosfvxccr.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.sweek.top/Article/details/gtybxmybbv.html

Ruby: x.is_a?(Numeric)
来源：http://dali.xylfe.cn/Article/details/gtftysfthh.html

C#:   x is int or double or decimal
来源：http://dali.ydzc1.top/Article/details/gtachcdfrb.html

[B14] 判断值是否在集合内
来源：http://dali.jqgufenzy.top/Article/details/gtdpwfjaww.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.kuanghao11.cn/Article/details/gtvqzmjbjc.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.hnqzz.top/Article/details/gtfinxhycv.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.pycfn.com/Article/details/gtfgazencj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.yuanzhike.top/Article/details/gtahvyxxgl.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.cdnleiting.top/Article/details/gtzgxdmlsr.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.zhiwuduotai.top/Article/details/gtoqvhjinu.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.cdnleiting.top/Article/details/gteibgqeqx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.nanxuanxn.top/Article/details/gtgniyzbnd.html

[B15] 布尔运算与取反
来源：http://dali.zhijiandao.cn/Article/details/gtubmfhfcp.html

Py:   a and b or not c
来源：http://dali.c1oappe.top/Article/details/gtmpelaqpp.html

PHP:  $a && $b || !$c
来源：http://dali.pycfn.com/Article/details/gtsuyyrttr.html

JS:   a && b || !c
来源：http://dali.fzhhl.top/Article/details/gtiglqcjju.html

TS:   a && b || !c
来源：http://dali.yongpay.top/Article/details/gtcebzydib.html

Java: a && b || !c
来源：http://dali.yuanzhike.top/Article/details/gtefuwdiyv.html

Go:   a && b || !c
来源：http://dali.zycfv.cn/Article/details/gtsgfvamon.html

Ruby: a && b || !c
来源：http://dali.pycfn.com/Article/details/gttbddjfhs.html

C#:   a && b || !c
来源：http://dali.zhiwuduotai.top/Article/details/gtmohnhgek.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.zycfv.cn/Article/details/gtjiapysiq.html

Py:   if not data: return
来源：http://dali.bjfxy.top/Article/details/gtvpwqvbns.html

PHP:  if (!$data) { return; }
来源：http://dali.redwolf501.top/Article/details/gtzpwtybxw.html

JS:   if (!data) return;
来源：http://dali.ehwqpu.com/Article/details/gtdradxjic.html

TS:   if (!data) return;
来源：http://dali.0kj1m.cn/Article/details/gttthnobqo.html

Java: if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gttiuwbfee.html

Go:   if data == nil { return }
来源：http://dali.hammf.cn/Article/details/gtiuxowdoi.html

Ruby: return if data.nil?
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjxmwliar.html

C#:   if (data == null) return;
来源：http://dali.redwolf501.top/Article/details/gtdhvptqlj.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtjoievucl.html

C. 函数与作用域
来源：http://dali.yj20258888.top/Article/details/gtackyfyuq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtrikpxzzm.html

[C01] 定义函数
来源：http://dali.snrcjt.cn/Article/details/gtzcfkqpwn.html

Py:   def add(a, b): return a + b
来源：http://dali.hywenlv.cn/Article/details/gttqygogmy.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.zhoulong.xyz/Article/details/gtpfhhglii.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.svipenyu.cn/Article/details/gtccczhscu.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.kuanghao11.cn/Article/details/gtpegmqmky.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.iojbl.cn/Article/details/gtvxgzlvof.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.gogol.net.cn/Article/details/gtbcxxvheb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.hongshengwenyu.top/Article/details/gtndxksnns.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.dianchejie.cn/Article/details/gtrmukdpfq.html

[C02] 默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtavveodun.html

Py:   def greet(name="World"): return name
来源：http://dali.yanxiufei.cn/Article/details/gtkhsodgcv.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jlsjyb.cn/Article/details/gtnzplotwy.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.tanke756.top/Article/details/gtmtemfxrd.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwwqmttgi.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jqgufenzy.top/Article/details/gtwgdoepac.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.haohaochexian.top/Article/details/gtohfnuprl.html

Ruby: def greet(name = "World") = name
来源：http://dali.wangdashe.top/Article/details/gtjmxfaltl.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.sweek.top/Article/details/gtrlasbyjw.html

[C03] 可变参数
来源：http://dali.gotoacloud.top/Article/details/gtawzlsfqd.html

Py:   def total(*args): return sum(args)
来源：http://dali.wangshuangyany.cn/Article/details/gtrargovpq.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.yj20258888.top/Article/details/gttvkuuzmg.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenlongwang.top/Article/details/gthkqxjpns.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.chenjidiqi.icu/Article/details/gtmmkvjlva.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.cucudq.cn/Article/details/gtaadyffhg.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.kuanghao11.cn/Article/details/gtrgpnyxhx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.havefunace.top/Article/details/gtchlqwwfw.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.quarkkingdee.top/Article/details/gtdmijjavt.html

[C04] 命名参数 / 关键字参数
来源：http://dali.xinyue.icu/Article/details/gtixotgwch.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.jiagoushi.top/Article/details/gtvxwmzyao.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gtmwhcqogd.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.gogol.net.cn/Article/details/gtnzvovrqb.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.wangshuangyany.cn/Article/details/gtzuytzqtw.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.hywenlv.cn/Article/details/gtvfyikyry.html

Go:   // 无：用配置结构体参数
来源：http://dali.chenlongwang.top/Article/details/gtaoymlgzt.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nwbrower.top/Article/details/gtnxayllaz.html

C#:   f(a: 1, b: 2)
来源：http://dali.cheryme.top/Article/details/gtvvngowhk.html

[C05] 返回多个值
来源：http://dali.jqgfzy.top/Article/details/gtkdgjjxql.html

Py:   return a, b
来源：http://dali.shuidangran.top/Article/details/gtobsdpyuj.html

PHP:  return [$a, $b];
来源：http://dali.c1oappe.top/Article/details/gtqwcieqqj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.dianchejie.cn/Article/details/gtmneuwsvf.html

TS:   return { a, b };
来源：http://dali.guowangkeji.top/Article/details/gtqtyekvzr.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.xuetiantiany.cn/Article/details/gtlmgzxvwo.html

Go:   return a, b
来源：http://dali.jqgufenzy.top/Article/details/gtpdbtpqvg.html

Ruby: return a, b
来源：http://dali.chenlongwang.top/Article/details/gtvlwquosw.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.zhiwuduotai.top/Article/details/gtficjhero.html

[C06] 匿名函数 / lambda
来源：http://dali.pycfn.com/Article/details/gtdrvsllsk.html

Py:   square = lambda x: x * x
来源：http://dali.jyoumei.cn/Article/details/gtoqqohobr.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.gaohongyu789.top/Article/details/gtoohteocf.html

JS:   const square = x => x * x;
来源：http://dali.dashuyun.cn/Article/details/gtdcgosatt.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hammf.cn/Article/details/gtxfcwlfpb.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.chenjidiqi.icu/Article/details/gtoksaaqfp.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.zdqjudy.top/Article/details/gtpsztoudd.html

Ruby: square = ->(x) { x * x }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthgrrkewk.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.xuetiantiany.cn/Article/details/gtileprvkg.html

[C07] 把函数作为参数传入
来源：http://dali.yuanzhike.top/Article/details/gtuqgskrnh.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shangyingyoupin.top/Article/details/gtzkjahijo.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.ppjwa.cn/Article/details/gttgesrxfv.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.nanxuanxn.top/Article/details/gtqovfpfct.html

TS:   arr.map(String)
来源：http://dali.mhx1999.top/Article/details/gtgohqthkl.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shzxlz.cn/Article/details/gtidqdwiuo.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.xuetiantiany.cn/Article/details/gtllbupnlo.html

Ruby: arr.map(&:upcase)
来源：http://dali.zhoulong.xyz/Article/details/gteufuuuol.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.xinyue.icu/Article/details/gtnzrwdfld.html

[C08] 闭包
来源：http://dali.9152youxi.cn/Article/details/gtelhwurtr.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.xuanzx.com/Article/details/gtnpsqjjie.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gttvoohbbe.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.birdmap.top/Article/details/gtcuwxfoeb.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.svipenyu.cn/Article/details/gtzqgdpmhk.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.zhengqikj.top/Article/details/gtumvneeuf.html


<!-- 参考信息 -->