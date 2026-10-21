代发 wailian999

Java: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.gzhubu.top/Article/details/gtolhafzjt.html

Go:   a & b; a | b; a ^ b; ^a; a << 2; a >> 1
来源：http://dali.tianlin.xyz/Article/details/gtjxqgjseu.html

Ruby: a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.vqdsnc.cn/Article/details/gtmpcurpdt.html

C#:   a & b; a | b; a ^ b; ~a; a << 2; a >> 1
来源：http://dali.xziqi.cn/Article/details/gtquvfdict.html

[A18] 字符与 ASCII 码互转
来源：http://dali.gogol.net.cn/Article/details/gtwbqcvuwe.html

Py:   ord("A"); chr(65)
来源：http://dali.chenzaomai.com/Article/details/gtvqkcdxdp.html

PHP:  ord("A"); chr(65)
来源：http://dali.jinqigfzy.top/Article/details/gtwvttakoa.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.zdqjudy.top/Article/details/gtenbpupvw.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.hongshengwenyu.top/Article/details/gtcnnjinmm.html

Java: (int) 'A'; (char) 65
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpkjrpso.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.redwolf501.top/Article/details/gtarzbasxg.html

Ruby: "A".ord; 65.chr
来源：http://dali.nwbrower.top/Article/details/gtsynfejls.html

C#:   (int)'A'; (char)65
来源：http://dali.pycfn.com/Article/details/gttanflihf.html

[A19] 交换两个变量
来源：http://dali.gogol.net.cn/Article/details/gtshnmmowd.html

Py:   a, b = b, a
来源：http://dali.shangyingyoupin.top/Article/details/gtwwawnlto.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.fzhhl.top/Article/details/gtcnqipwgc.html

JS:   [a, b] = [b, a];
来源：http://dali.wangdashe.top/Article/details/gtcrhniuda.html

TS:   [a, b] = [b, a];
来源：http://dali.hongshengwenyu.top/Article/details/gtuewcsqco.html

Java: int t = a; a = b; b = t;
来源：http://dali.sysykeji.top/Article/details/gtjvaachqr.html

Go:   a, b = b, a
来源：http://dali.tianlin.xyz/Article/details/gtxfnfvelu.html

Ruby: a, b = b, a
来源：http://dali.dianchejie.cn/Article/details/gtxdlkdkqg.html

C#:   (a, b) = (b, a);
来源：http://dali.316326.xyz/Article/details/gtvbxhyemv.html

[A20] 读取标准输入
来源：http://dali.sxryk.cn/Article/details/gtkewhokhy.html

Py:   name = input("请输入：")
来源：http://dali.svipenyu.cn/Article/details/gtpykjumwl.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.ehwqpu.com/Article/details/gtytkmgmkb.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.jyoumei.cn/Article/details/gtvqwmcawz.html

TS:   // Node.js：readline 模块
来源：http://dali.jinqigufen.top/Article/details/gtfkikqgmq.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.chenlongwang.top/Article/details/gtveiecflv.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.haohaochexian.top/Article/details/gtgyejpdst.html

Ruby: gets.chomp
来源：http://dali.daxiang520.top/Article/details/gtjxbnplta.html

C#:   Console.ReadLine();
来源：http://dali.xuetiantiany.cn/Article/details/gttnjznfrr.html

[A21] 保留指定小数位输出
来源：http://dali.shangyingyoupin.top/Article/details/gterllrkhw.html

Py:   f"{3.14159:.2f}"
来源：http://dali.iojbl.cn/Article/details/gteqimxaky.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hnxiangtu.top/Article/details/gtwrdbcecx.html

JS:   (3.14159).toFixed(2)
来源：http://dali.havefunace.top/Article/details/gttgjolvar.html

TS:   (3.14159).toFixed(2)
来源：http://dali.hfpthk.cn/Article/details/gtnvouzssq.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.gogol.net.cn/Article/details/gterjngrrb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xuetiantiany.cn/Article/details/gtkzhmbbqr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhixingplan.top/Article/details/gtwplaavch.html

C#:   3.14159.ToString("F2")
来源：http://dali.sxryk.cn/Article/details/gtvdbimhcr.html

[A22] 获取字符串长度
来源：http://dali.zdqjudy.top/Article/details/gthxxakucf.html

Py:   len(s)
来源：http://dali.hywenlv.cn/Article/details/gtbcgvvqdm.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.gogol.net.cn/Article/details/gtqfvdxvgq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.sufxvd.cn/Article/details/gtqotmnrza.html

TS:   s.length
来源：http://dali.birdmap.top/Article/details/gttnhjbxfd.html

Java: s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtqgfhkdep.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.yvedp.cn/Article/details/gtoetdxvwd.html

Ruby: s.length
来源：http://dali.pycfn.com/Article/details/gttyvcxyxy.html

C#:   s.Length
来源：http://dali.xinyue.icu/Article/details/gtqvjwufrz.html

[A23] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtombuqegn.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.jiagoushi.top/Article/details/gtgbnrjatu.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbjttvxqs.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.smart0.xyz/Article/details/gtwbybtswa.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.havefunace.top/Article/details/gtasskfchg.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.haohaochexian.top/Article/details/gtecdspekw.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.hysaishi.cn/Article/details/gtancxwgyf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.zhiwuduotai.top/Article/details/gtirszefln.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.pycfn.com/Article/details/gtebdhywjj.html

[A24] 去除首尾空白
来源：http://dali.yvedp.cn/Article/details/gtzyiwigwq.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.shzxlz.cn/Article/details/gtvkikzhzm.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.c1oappe.top/Article/details/gtobriufeg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvgruzpa.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.sysykeji.top/Article/details/gtdqkxmexr.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.nanxinkj.top/Article/details/gtrptqxyfs.html

Go:   strings.TrimSpace(s)
来源：http://dali.ehwqpu.com/Article/details/gtglkwgerx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.xylfe.cn/Article/details/gtmjxtfseo.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.fzhhl.top/Article/details/gtzesnfnxd.html

[A25] 字符串比较
来源：http://dali.wangdashe.top/Article/details/gtjlcdqvcn.html

Py:   s1 == s2; s1 != s2
来源：http://dali.jinghuilouyu.cn/Article/details/gtxusfgdcm.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.sxryk.cn/Article/details/gtesaymvuz.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.wangshuangyany.cn/Article/details/gtjgpsblvj.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.hnxiangtu.top/Article/details/gtiawovdfj.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.hfpthk.cn/Article/details/gtsptgmzci.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.yj202588.top/Article/details/gtoqlwkdmu.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.jyoumei.cn/Article/details/gthfqrcfzn.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.jinqigufen.top/Article/details/gtypsycvup.html

[A26] 类型转换总览
来源：http://dali.zhoulong.xyz/Article/details/gtivbvioye.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.shzxlz.cn/Article/details/gtxmjsxlcw.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.ybcxt.top/Article/details/gtuzzwhmuk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.xuanzx.com/Article/details/gtbxaueqjz.html

TS:   Number() String() Boolean() x as number
来源：http://dali.shangyingyoupin.top/Article/details/gtjmadsewu.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.haohaochexian.top/Article/details/gtqpcudwlq.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.andypj.xyz/Article/details/gttstolprz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.zhixingplan.top/Article/details/gttkqgdeof.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.wangdashe.top/Article/details/gtverrzctf.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtjnqfoxyq.html

B. 流程控制
来源：http://dali.sysykeji.top/Article/details/gtpgkuwysn.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtrzsbmtxc.html

[B01] 条件判断 if / else
来源：http://dali.yj20258888.top/Article/details/gtjerjuivu.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.pycfn.com/Article/details/gtiebmgibm.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.cucudq.cn/Article/details/gtiyzmevzb.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.zhiwuduotai.top/Article/details/gtofqpkmnp.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cucudq.cn/Article/details/gtpaizdtjz.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.gzhubu.top/Article/details/gtkgpstxrw.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.guannengcc.top/Article/details/gthbkgkysm.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.chenlongwang.top/Article/details/gtpfrmebkl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.hnxiangtu.top/Article/details/gtdfnxcgqa.html

[B02] 多分支 else if / elif
来源：http://dali.wangdashe.top/Article/details/gtdjmvgolf.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.andypj.xyz/Article/details/gtvbgjdscz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtiytsnrxx.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yanxiufei.cn/Article/details/gtungktlmo.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.zdqjudy.top/Article/details/gtdiajmoqe.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.gogol.net.cn/Article/details/gtvcinduap.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.gotoacloud.top/Article/details/gtluehunrw.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.gogol.net.cn/Article/details/gtlfrsiejt.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.xziqi.cn/Article/details/gtskekafjh.html

[B03] switch / match / case
来源：http://dali.xuanzx.com/Article/details/gtrftywcsm.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.guowangkeji.top/Article/details/gtkqqtbuik.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.tanke756.top/Article/details/gtrxbglozj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtcdpytcqu.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.hammf.cn/Article/details/gtjgzqdtkr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.jianghu66.top/Article/details/gtkhhqrnmt.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtqpyxkusq.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.feifeiyinyue.top/Article/details/gtkqplwpsa.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.wangshuangyany.cn/Article/details/gtwjsbztha.html

[B04] for 计数循环
来源：http://dali.fengsongda.top/Article/details/gtxuzffwzm.html

Py:   for i in range(10): print(i)
来源：http://dali.zdqjudy.top/Article/details/gtmuosactz.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jiagoushi.top/Article/details/gtxqlhzoxv.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhengqikj.top/Article/details/gtjbxxshyt.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.yvedp.cn/Article/details/gtghszbopr.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.aizwys.cn/Article/details/gtrjmafqty.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtecfwmsgd.html

Ruby: 10.times { |i| puts i }
来源：http://dali.ybcxt.top/Article/details/gtrjmpilhq.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.fzhhl.top/Article/details/gtvkuzrikr.html

[B05] 遍历数组 / 列表
来源：http://dali.meibo888.top/Article/details/gteroczmkf.html

Py:   for item in arr: print(item)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtudtpyqmt.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.hfpthk.cn/Article/details/gtofyqmtue.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.sufxvd.cn/Article/details/gtgekstpeo.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.meibo888.top/Article/details/gtwdyzgpid.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.hfpthk.cn/Article/details/gtfmsldxit.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.zdqjudy.top/Article/details/gtcherleqy.html

Ruby: arr.each { |item| puts item }
来源：http://dali.zhoulong.xyz/Article/details/gtcxpchhrx.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.quarkkingdee.top/Article/details/gtvjcqfhrv.html

[B06] 遍历字典 / 对象
来源：http://dali.jqgufenzy.top/Article/details/gtztkyslrz.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.svipenyu.cn/Article/details/gtiplibikh.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.yj202588.top/Article/details/gtsxrdtjqc.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.gzhubu.top/Article/details/gtadljmhru.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.birdmap.top/Article/details/gtmdzuhcib.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.kuanghao11.cn/Article/details/gtsyeybqhx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.hammf.cn/Article/details/gtzsqxghbn.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.dashuyun.cn/Article/details/gtmdodsfpc.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.sxryk.cn/Article/details/gtxgvsmyxh.html

[B07] while 循环
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcuydcyil.html

Py:   while i < 10: i += 1
来源：http://dali.zhixingplan.top/Article/details/gtcprocgix.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.zhongyouzk.top/Article/details/gteideulqv.html

JS:   while (i < 10) { i++; }
来源：http://dali.dianchejie.cn/Article/details/gtftabgsfq.html

TS:   while (i < 10) { i++; }
来源：http://dali.hongshengwenyu.top/Article/details/gtidqxakvd.html

Java: while (i < 10) { i++; }
来源：http://dali.zycfv.cn/Article/details/gtfuebvihk.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.quarkkingdee.top/Article/details/gtnybevnql.html

Ruby: while i < 10; i += 1; end
来源：http://dali.pengpengdd.cyou/Article/details/gtzmjchpzk.html

C#:   while (i < 10) { i++; }
来源：http://dali.yueranfly.top/Article/details/gtyojuynzf.html

[B08] do-while（至少执行一次）
来源：http://dali.guannengcc.top/Article/details/gtgszdoilr.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.pengpengdd.cyou/Article/details/gtqaekbxkg.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.jyoumei.cn/Article/details/gtpwrykzle.html

JS:   do { i++; } while (i < 10);
来源：http://dali.hongshengwenyu.top/Article/details/gtlkozypto.html

TS:   do { i++; } while (i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gtawqrxxef.html

Java: do { i++; } while (i < 10);
来源：http://dali.xylfe.cn/Article/details/gtdofpogie.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.jianghu66.top/Article/details/gtiqcwngku.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.dashuyun.cn/Article/details/gttsdiqlqc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.sxryk.cn/Article/details/gtwrxewtut.html

[B09] break 与 continue
来源：http://dali.hnqzz.top/Article/details/gtoxaujvqx.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.quarkkingdee.top/Article/details/gtulsvkjgs.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.xuetiantiany.cn/Article/details/gtuwwhhlpl.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.xziqi.cn/Article/details/gtykwqzfia.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hongshengwenyu.top/Article/details/gthchgrtqu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzyqhuevz.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.tian-w.cn/Article/details/gtszrvggpl.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.yongpay.top/Article/details/gtdwriatco.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.sweek.top/Article/details/gtfrbedvni.html

[B10] 遍历同时拿索引
来源：http://dali.jinqigfzy.top/Article/details/gtkjbdgvlk.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.daxiang520.top/Article/details/gtoxmopvav.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.tian-w.cn/Article/details/gtvbrfnhjx.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.xinyue.icu/Article/details/gtbqccrfjk.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.wangshuangyany.cn/Article/details/gtwhtywlwx.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.jinqigfzy.top/Article/details/gtxvrtkmpo.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gtnownniti.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.yanxiufei.cn/Article/details/gtmyvphuxy.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.yj202588.top/Article/details/gtqemxqevx.html

[B11] 生成数字序列 / 区间
来源：http://dali.9152youxi.cn/Article/details/gtscitqtjg.html

Py:   list(range(0, 10, 2))
来源：http://dali.chenlongwang.top/Article/details/gtyefgzrjw.html

PHP:  range(0, 10, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtindfjmnl.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.yuanzhike.top/Article/details/gtjcscgngq.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwyehaiis.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.mhx1999.top/Article/details/gtygalfspj.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.yj20258888.top/Article/details/gtyiwftywi.html

Ruby: (0...10).step(2).to_a
来源：http://dali.hfpthk.cn/Article/details/gtskebqxim.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.gotoacloud.top/Article/details/gteqtfvlhw.html

[B12] 跳出多层循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxquqawcl.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.yj20258888.top/Article/details/gttgcmeeiz.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.snrcjt.cn/Article/details/gterxslswc.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.gotoacloud.top/Article/details/gtopnbivik.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwbajdzhb.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.jqgfzy.top/Article/details/gtfwzxxxwk.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.zhengqikj.top/Article/details/gtpgmqbicx.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.vqdsnc.cn/Article/details/gtvsnziurz.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.smart0.xyz/Article/details/gtmhhjvcgz.html

[B13] 判断是否为数字
来源：http://dali.kuanghao11.cn/Article/details/gteqclljpe.html

Py:   isinstance(x, (int, float))
来源：http://dali.feifeiyinyue.top/Article/details/gtqlytjfsp.html

PHP:  is_numeric($x)
来源：http://dali.zhiwuduotai.top/Article/details/gtkpgppvax.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtpibpffjx.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.dashuyun.cn/Article/details/gtxxnuqiho.html

Java: x instanceof Number
来源：http://dali.vqdsnc.cn/Article/details/gtkcjllxeu.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.dianchejie.cn/Article/details/gtanssxouw.html

Ruby: x.is_a?(Numeric)
来源：http://dali.cashguo.top/Article/details/gtpejzealn.html

C#:   x is int or double or decimal
来源：http://dali.yj20258.top/Article/details/gtwldhurdd.html

[B14] 判断值是否在集合内
来源：http://dali.jinqigfzy.top/Article/details/gtqhtsbplf.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwqlxmdiq.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.svipenyu.cn/Article/details/gtkqymakes.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.jinqigfzy.top/Article/details/gtojebyrhk.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.shangyingyoupin.top/Article/details/gtnniogjzz.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gtatbsbbxc.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.jianghu66.top/Article/details/gttmdtshwd.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.wangdashe.top/Article/details/gtwokucphx.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.svipenyu.cn/Article/details/gtapxwaqso.html

[B15] 布尔运算与取反
来源：http://dali.pycfn.com/Article/details/gtwmcnhkrj.html

Py:   a and b or not c
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdmbncfcw.html

PHP:  $a && $b || !$c
来源：http://dali.hnxiangtu.top/Article/details/gtbqwdqrdf.html

JS:   a && b || !c
来源：http://dali.daxiang520.top/Article/details/gtdxkpvsmo.html

TS:   a && b || !c
来源：http://dali.yj20258.top/Article/details/gtaraovalr.html

Java: a && b || !c
来源：http://dali.dashuyun.cn/Article/details/gtprvbtofq.html

Go:   a && b || !c
来源：http://dali.sufxvd.cn/Article/details/gttnfwgrnx.html

Ruby: a && b || !c
来源：http://dali.yongpay.top/Article/details/gtigqbuval.html

C#:   a && b || !c
来源：http://dali.jqgufenzy.top/Article/details/gtoxfpvmet.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.ivvv.top/Article/details/gtalyhsaxj.html

Py:   if not data: return
来源：http://dali.jqgufenzy.top/Article/details/gtarhrsquf.html

PHP:  if (!$data) { return; }
来源：http://dali.yuanzhike.top/Article/details/gtlintmazu.html

JS:   if (!data) return;
来源：http://dali.kuanghao11.cn/Article/details/gtjdrpfmec.html

TS:   if (!data) return;
来源：http://dali.quarkkingdee.top/Article/details/gttxgkzjzr.html

Java: if (data == null) return;
来源：http://dali.shangyingyoupin.top/Article/details/gtohqexnav.html

Go:   if data == nil { return }
来源：http://dali.gzhubu.top/Article/details/gtclquqwww.html

Ruby: return if data.nil?
来源：http://dali.xuanzx.com/Article/details/gtspscobnj.html

C#:   if (data == null) return;
来源：http://dali.zhixingplan.top/Article/details/gtvippjoxt.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthickpoxt.html

C. 函数与作用域
来源：http://dali.yangfankeji.com/Article/details/gtutsxrumo.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtdlythlig.html

[C01] 定义函数
来源：http://dali.vqdsnc.cn/Article/details/gtqllftwuf.html

Py:   def add(a, b): return a + b
来源：http://dali.svipenyu.cn/Article/details/gttxeyvvhk.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.daria6918.cn/Article/details/gtosozcqzn.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.meibo888.top/Article/details/gtrnjjvwkn.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.feifeiyinyue.top/Article/details/gthfwtzojp.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.bjfxy.top/Article/details/gtcsgzpwqd.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.xinyue.icu/Article/details/gtmhqufltt.html

Ruby: def add(a, b); a + b; end
来源：http://dali.zycfv.cn/Article/details/gtubmkrexc.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtdhwtxrgo.html

[C02] 默认参数
来源：http://dali.dashuyun.cn/Article/details/gtrweuoljd.html

Py:   def greet(name="World"): return name
来源：http://dali.daxiang520.top/Article/details/gtdffengko.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jiagoushi.top/Article/details/gtsrtzlwyn.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.yuxming.cn/Article/details/gtmtqcktqb.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.andypj.xyz/Article/details/gtwqohhikk.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.gzhubu.top/Article/details/gtdatgzchc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.zdqjudy.top/Article/details/gtwxdemucn.html

Ruby: def greet(name = "World") = name
来源：http://dali.nanxuanxn.top/Article/details/gtgrqolore.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yuxming.cn/Article/details/gtmiutlemq.html

[C03] 可变参数
来源：http://dali.tanke756.top/Article/details/gtalgdckss.html

Py:   def total(*args): return sum(args)
来源：http://dali.jinqigfzy.top/Article/details/gtrkxqomku.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.gaohongyu789.top/Article/details/gtwekszsen.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yuanzhike.top/Article/details/gtmajuclaw.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.zhijiandao.cn/Article/details/gtlnzebizy.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.316326.xyz/Article/details/gtckcsuqsd.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.yangfankeji.com/Article/details/gtwjifivwx.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.hammf.cn/Article/details/gtdarakphl.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.andypj.xyz/Article/details/gtzgeklkje.html

[C04] 命名参数 / 关键字参数
来源：http://dali.zhixingplan.top/Article/details/gtelkirqcz.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.nanxuanxn.top/Article/details/gtsbfthpve.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yongpay.top/Article/details/gtgtfjxffp.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.xuetiantiany.cn/Article/details/gtxhigtseo.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.zhijiandao.cn/Article/details/gttkyekjif.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tianlin.xyz/Article/details/gtebmvpuia.html

Go:   // 无：用配置结构体参数
来源：http://dali.guannengcc.top/Article/details/gtlfckdrry.html

Ruby: f(a: 1, b: 2)
来源：http://dali.shzxlz.cn/Article/details/gtmcsvjhno.html

C#:   f(a: 1, b: 2)
来源：http://dali.daxiang520.top/Article/details/gtshkjnxkq.html

[C05] 返回多个值
来源：http://dali.zhongyouzk.top/Article/details/gtprkcmien.html

Py:   return a, b
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwowdgycb.html

PHP:  return [$a, $b];
来源：http://dali.yuanzhike.top/Article/details/gtlelqrsep.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gtagwwbfzw.html

TS:   return { a, b };
来源：http://dali.yanxiufei.cn/Article/details/gtifrxotes.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yj202588.top/Article/details/gtdvauwikc.html

Go:   return a, b
来源：http://dali.zhoulong.xyz/Article/details/gtwmtjikfz.html

Ruby: return a, b
来源：http://dali.fzhhl.top/Article/details/gtjyybjuyb.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jinqigufen.top/Article/details/gtnghtesdt.html

[C06] 匿名函数 / lambda
来源：http://dali.zhengqikj.top/Article/details/gtgadngcjm.html

Py:   square = lambda x: x * x
来源：http://dali.hysaishi.cn/Article/details/gteonnzbyb.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.yangfankeji.com/Article/details/gtovnybgkl.html

JS:   const square = x => x * x;
来源：http://dali.xziqi.cn/Article/details/gtwnsmqbar.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.hysaishi.cn/Article/details/gtlnokauko.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.fengsongda.top/Article/details/gtmpttsodv.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.yonumen.top/Article/details/gtjsrpajdf.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtenzwiloc.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.meibo888.top/Article/details/gthijpqrpo.html

[C07] 把函数作为参数传入
来源：http://dali.zhixingplan.top/Article/details/gtzxidiszm.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.gotoacloud.top/Article/details/gtoxghuynt.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.zycfv.cn/Article/details/gtquziinle.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.hysaishi.cn/Article/details/gtowwitlwx.html

TS:   arr.map(String)
来源：http://dali.yuxming.cn/Article/details/gthvpcdtjg.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjnaapuw.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.guannengcc.top/Article/details/gtycasgevw.html

Ruby: arr.map(&:upcase)
来源：http://dali.gzhubu.top/Article/details/gtvndwjbuh.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.yonumen.top/Article/details/gtkzbgahmd.html

[C08] 闭包
来源：http://dali.zycfv.cn/Article/details/gtlqijlbxh.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.jianghu66.top/Article/details/gtrhoqyqzm.html


<!-- 参考信息 -->