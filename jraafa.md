代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.ehwqpu.com/Article/details/gt2kjmsnfpt.html

Py:   ord("A"); chr(65)
来源：http://dali.sufxvd.cn/Article/details/gt2nipcpjha.html

PHP:  ord("A"); chr(65)
来源：http://dali.ehwqpu.com/Article/details/gt2esckxlur.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qopunkha.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.c1oappe.top/Article/details/gt2hkszioex.html

Java: (int) 'A'; (char) 65
来源：http://dali.cheryme.top/Article/details/gt2tfgbwbuq.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.hnqzz.top/Article/details/gt2hzdhzkzq.html

Ruby: "A".ord; 65.chr
来源：http://dali.xinyue.icu/Article/details/gt2jysdpuad.html

C#:   (int)'A'; (char)65
来源：http://dali.cashguo.top/Article/details/gt2shdrgodc.html

[A19] 交换两个变量
来源：http://dali.shuidangran.top/Article/details/gt2xphuuqbj.html

Py:   a, b = b, a
来源：http://dali.guowangkeji.top/Article/details/gt2nxcaxjlz.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.gogol.net.cn/Article/details/gt2bpbllykh.html

JS:   [a, b] = [b, a];
来源：http://dali.ydzc1.top/Article/details/gt2qzallynk.html

TS:   [a, b] = [b, a];
来源：http://dali.chenzaomai.com/Article/details/gt2lrpakcqu.html

Java: int t = a; a = b; b = t;
来源：http://dali.dianchejie.cn/Article/details/gt2mxgalbss.html

Go:   a, b = b, a
来源：http://dali.yuxming.cn/Article/details/gt2kohxqpeh.html

Ruby: a, b = b, a
来源：http://dali.hfpthk.cn/Article/details/gt2ayqmdkiq.html

C#:   (a, b) = (b, a);
来源：http://dali.tanke756.top/Article/details/gt2fjbrmmmi.html

[A20] 读取标准输入
来源：http://dali.xuetiantiany.cn/Article/details/gt2zsurmnot.html

Py:   name = input("请输入：")
来源：http://dali.zhixingplan.top/Article/details/gt2qpxgqnpv.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.zycfv.cn/Article/details/gt2dsvcrlin.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.xziqi.cn/Article/details/gt2crlfsapk.html

TS:   // Node.js：readline 模块
来源：http://dali.sysykeji.top/Article/details/gt2ikmhdeif.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.0kj1m.cn/Article/details/gt2umpcjlfj.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.nanxuanxn.top/Article/details/gt2hdflezgm.html

Ruby: gets.chomp
来源：http://dali.yj20258888.top/Article/details/gt2mgtkbbye.html

C#:   Console.ReadLine();
来源：http://dali.zdqjudy.top/Article/details/gt2dfhwsgpm.html

[A21] 保留指定小数位输出
来源：http://dali.9152youxi.cn/Article/details/gt2amkohvml.html

Py:   f"{3.14159:.2f}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2upwosltq.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.tanke756.top/Article/details/gt2ulycorbr.html

JS:   (3.14159).toFixed(2)
来源：http://dali.nanxinkj.top/Article/details/gt2bitxayln.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jlsjyb.cn/Article/details/gt2rdwloppu.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.guannengcc.top/Article/details/gt2teuvcjsb.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.xziqi.cn/Article/details/gt2gsvhfppb.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.zhijiandao.cn/Article/details/gt2euynyzbo.html

C#:   3.14159.ToString("F2")
来源：http://dali.cqqwz.cn/Article/details/gt2duswbafp.html

[A22] 获取字符串长度
来源：http://dali.andypj.xyz/Article/details/gt2nqajphxv.html

Py:   len(s)
来源：http://dali.hammf.cn/Article/details/gt2jcbbzlat.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zqflohar.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.dianchejie.cn/Article/details/gt2ihxtymsi.html

TS:   s.length
来源：http://dali.chenjidiqi.icu/Article/details/gt2idxehcep.html

Java: s.length()
来源：http://dali.hfpthk.cn/Article/details/gt2yrsrtphl.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.snrcjt.cn/Article/details/gt2pqnhknui.html

Ruby: s.length
来源：http://dali.feifeiyinyue.top/Article/details/gt2vrnlofqc.html

C#:   s.Length
来源：http://dali.yongpay.top/Article/details/gt2rpmanvrw.html

[A23] 大小写转换
来源：http://dali.daria6918.cn/Article/details/gt2hxjshmss.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.xinyue.icu/Article/details/gt2ohvvskrj.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.aizwys.cn/Article/details/gt2fwdbfrem.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.gzhubu.top/Article/details/gt2gkxcttiq.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.xuanzx.com/Article/details/gt2lgunjchy.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oxtirqpz.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2xkbalrnm.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.meibo888.top/Article/details/gt2wopxaars.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.hysaishi.cn/Article/details/gt2bljqfvpt.html

[A24] 去除首尾空白
来源：http://dali.yj202588.top/Article/details/gt2nffldjja.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.yuanzhike.top/Article/details/gt2unsyxyqx.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.shuidangran.top/Article/details/gt2pgnwkehg.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.zhongyouzk.top/Article/details/gt2iebbotjl.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.mhx1999.top/Article/details/gt2isxxzyao.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.fzhhl.top/Article/details/gt2mwzntndm.html

Go:   strings.TrimSpace(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zdplnimx.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.hnqzz.top/Article/details/gt2yohwygqy.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.cheryme.top/Article/details/gt2hafjjsrq.html

[A25] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gt2obdsmjpz.html

Py:   s1 == s2; s1 != s2
来源：http://dali.gotoacloud.top/Article/details/gt2tskpumzw.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.9152youxi.cn/Article/details/gt2tzcbatoc.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2qaxeknia.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.feifeiyinyue.top/Article/details/gt2rdwbirai.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.snrcjt.cn/Article/details/gt2pqhmdbjz.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.zhongyouzk.top/Article/details/gt2lzfoohcv.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.bjfxy.top/Article/details/gt2ldgjzwrv.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.birdmap.top/Article/details/gt2wptfhhwb.html

[A26] 类型转换总览
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gszmjzlk.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gt2vslvbftm.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.shangyingyoupin.top/Article/details/gt2foxhguxr.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.nanxuanxn.top/Article/details/gt2jxfhrslg.html

TS:   Number() String() Boolean() x as number
来源：http://dali.cashguo.top/Article/details/gt2neduqunl.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.havefunace.top/Article/details/gt2vdohqbfi.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.jiagoushi.top/Article/details/gt2uzsyofgv.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.cdnleiting.top/Article/details/gt2hmcqktpq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.xuanzx.com/Article/details/gt2edaypesa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gt2pkhqiemz.html

B. 流程控制
来源：http://dali.yangfankeji.com/Article/details/gt2vdvcbgeq.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2lkncxbhg.html

[B01] 条件判断 if / else
来源：http://dali.jqgfzy.top/Article/details/gt2awybyatb.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.9152youxi.cn/Article/details/gt2nkwpqbfv.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.hammf.cn/Article/details/gt2niyzmrgs.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.yangfankeji.com/Article/details/gt2suystusi.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.jiagoushi.top/Article/details/gt2xugdetny.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.fengsongda.top/Article/details/gt2fgldrvkx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.zhengqikj.top/Article/details/gt2tmekjput.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.jyoumei.cn/Article/details/gt2wthmuykl.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.jianghu66.top/Article/details/gt2etupthxr.html

[B02] 多分支 else if / elif
来源：http://dali.aizwys.cn/Article/details/gt2qtlvsfgu.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.bjfxy.top/Article/details/gt2dcqlceok.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zeipvunp.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2exnjjnen.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.316326.xyz/Article/details/gt2wtahftfn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj20258.top/Article/details/gt2onxjxxjc.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.ybcxt.top/Article/details/gt2xcsgkhhz.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.shanyushiyangtech.top/Article/details/gt2alfyoklp.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eamezhir.html

[B03] switch / match / case
来源：http://dali.jqgufenzy.top/Article/details/gt2irfrqoeu.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.zycfv.cn/Article/details/gt2wmwkmbdh.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.mhx1999.top/Article/details/gt2nzrkdudj.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uipmbhap.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.daxiang520.top/Article/details/gt2jvgzqxfr.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.svipenyu.cn/Article/details/gt2ftvexlvp.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.bjfxy.top/Article/details/gt2lppecvmx.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.aizwys.cn/Article/details/gt2wfjoknfk.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.tanke756.top/Article/details/gt2seuokowx.html

[B04] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gt2frphhtmh.html

Py:   for i in range(10): print(i)
来源：http://dali.gogol.net.cn/Article/details/gt2woxzwthl.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.guannengcc.top/Article/details/gt2zntrfnrd.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.pengpengdd.cyou/Article/details/gt2dpyaqdte.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.jqgufenzy.top/Article/details/gt2cqmxabca.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.meibo888.top/Article/details/gt2mbkmausf.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.ybcxt.top/Article/details/gt2rwhjbnec.html

Ruby: 10.times { |i| puts i }
来源：http://dali.zhiwuduotai.top/Article/details/gt2llanmpye.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.yuxming.cn/Article/details/gt2vtwslxlm.html

[B05] 遍历数组 / 列表
来源：http://dali.tian-w.cn/Article/details/gt2gbajtivf.html

Py:   for item in arr: print(item)
来源：http://dali.svipenyu.cn/Article/details/gt2lpnshjmw.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2ozkjhhbq.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.zhengqikj.top/Article/details/gt2mrkqtrur.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.ivvv.top/Article/details/gt2nnjluvwt.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.gaohongyu789.top/Article/details/gt2whpxnjfn.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.gaohongyu789.top/Article/details/gt2hutapbei.html

Ruby: arr.each { |item| puts item }
来源：http://dali.ybcxt.top/Article/details/gt2kkikmuct.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sxwpyzio.html

[B06] 遍历字典 / 对象
来源：http://dali.bjfxy.top/Article/details/gt2rydzfjki.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.pycfn.com/Article/details/gt2zdqfohqt.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.gzhubu.top/Article/details/gt2ochwczfl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.shuidangran.top/Article/details/gt2yjotrwoj.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2creieudy.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.yj20258888.top/Article/details/gt2gynegeia.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.yj202588.top/Article/details/gt2brerjltf.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.ybcxt.top/Article/details/gt2yqdwpiki.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.ppjwa.cn/Article/details/gt2owlkivzs.html

[B07] while 循环
来源：http://dali.zhoulong.xyz/Article/details/gt2teuipbaa.html

Py:   while i < 10: i += 1
来源：http://dali.hywenlv.cn/Article/details/gt2eufqbtmz.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.ydzc1.top/Article/details/gt2bgbtlzkr.html

JS:   while (i < 10) { i++; }
来源：http://dali.havefunace.top/Article/details/gt2tykgcpap.html

TS:   while (i < 10) { i++; }
来源：http://dali.pycfn.com/Article/details/gt2exqbdwhp.html

Java: while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2hcebpmtd.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.fzhhl.top/Article/details/gt2vmexvjbj.html

Ruby: while i < 10; i += 1; end
来源：http://dali.yongpay.top/Article/details/gt2ivsbcmmm.html

C#:   while (i < 10) { i++; }
来源：http://dali.ehwqpu.com/Article/details/gt2esoetbyo.html

[B08] do-while（至少执行一次）
来源：http://dali.ydzc1.top/Article/details/gt2vwhdclra.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.yj20258888.top/Article/details/gt2mmdaocag.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.hnxiangtu.top/Article/details/gt2ngkgpeck.html

JS:   do { i++; } while (i < 10);
来源：http://dali.ivvv.top/Article/details/gt2glzqjmcd.html

TS:   do { i++; } while (i < 10);
来源：http://dali.gotoacloud.top/Article/details/gt2lbrxuigb.html

Java: do { i++; } while (i < 10);
来源：http://dali.hammf.cn/Article/details/gt2tdkqpwoe.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.xuetiantiany.cn/Article/details/gt2ppewzrrp.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2kbmbfblc.html

C#:   do { i++; } while (i < 10);
来源：http://dali.mhx1999.top/Article/details/gt2jpuxmvcd.html

[B09] break 与 continue
来源：http://dali.wangshuangyany.cn/Article/details/gt2otkgmzca.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.daria6918.cn/Article/details/gt2sccuzygy.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.shuidangran.top/Article/details/gt2kjkzkfnw.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jlsjyb.cn/Article/details/gt2selozocl.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.iojbl.cn/Article/details/gt2stlvwocu.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.yvedp.cn/Article/details/gt2nlfxvcet.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.hfpthk.cn/Article/details/gt2xswsarqc.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2slcmotfd.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.hnxiangtu.top/Article/details/gt2truhoppg.html

[B10] 遍历同时拿索引
来源：http://dali.yuxming.cn/Article/details/gt2zdrrikeh.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.mhx1999.top/Article/details/gt2tgrtrzxp.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.shuidangran.top/Article/details/gt2jtpsgzyu.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xkqywmaz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.zhongyouzk.top/Article/details/gt2fnvbrkqn.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.yueranfly.top/Article/details/gt2doqrgzrf.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.yueranfly.top/Article/details/gt2urqdehtw.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.guowangkeji.top/Article/details/gt2dacacttj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.tianlin.xyz/Article/details/gt2dezowjkg.html

[B11] 生成数字序列 / 区间
来源：http://dali.yonumen.top/Article/details/gt2wddluwij.html

Py:   list(range(0, 10, 2))
来源：http://dali.pycfn.com/Article/details/gt2robihusa.html

PHP:  range(0, 10, 2);
来源：http://dali.shangyingyoupin.top/Article/details/gt2kqhiyblw.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cdnleiting.top/Article/details/gt2yrkoyuua.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.cqqwz.cn/Article/details/gt2xjauagyz.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.cqqwz.cn/Article/details/gt2zmksyufl.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.chenjidiqi.icu/Article/details/gt2wdmmhwzn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2hgxiwzul.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gt2hlkdcxai.html

[B12] 跳出多层循环
来源：http://dali.pycfn.com/Article/details/gt2blcdcgan.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.zhoulong.xyz/Article/details/gt2qxovuhml.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.meibo888.top/Article/details/gt2ddbmznev.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.snrcjt.cn/Article/details/gt2tgrnmqsq.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.ybcxt.top/Article/details/gt2hlsdphbt.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.ppjwa.cn/Article/details/gt2xprfiolq.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.fzhhl.top/Article/details/gt2joowfngb.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.yuxming.cn/Article/details/gt2xrkzyyte.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.vqdsnc.cn/Article/details/gt2jrbjvjgl.html

[B13] 判断是否为数字
来源：http://dali.xziqi.cn/Article/details/gt2nodmmevy.html

Py:   isinstance(x, (int, float))
来源：http://dali.haohaochexian.top/Article/details/gt2semdgync.html

PHP:  is_numeric($x)
来源：http://dali.fengsongda.top/Article/details/gt2npgymenj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.jianghu66.top/Article/details/gt2xtjcrxfy.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.yanxiufei.cn/Article/details/gt2ojucjdsx.html

Java: x instanceof Number
来源：http://dali.hywenlv.cn/Article/details/gt2xgnqmkot.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.xinyue.icu/Article/details/gt2zwltknai.html

Ruby: x.is_a?(Numeric)
来源：http://dali.yangfankeji.com/Article/details/gt2yohhbijq.html

C#:   x is int or double or decimal
来源：http://dali.yanxiufei.cn/Article/details/gt2rwgkjmoi.html

[B14] 判断值是否在集合内
来源：http://dali.daria6918.cn/Article/details/gt2cpgoqxkv.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.aibaodan.cn/Article/details/gt2gjqufyiw.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.jqgufenzy.top/Article/details/gt2gjmkvnes.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.sufxvd.cn/Article/details/gt2tdlkaffg.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.tianlin.xyz/Article/details/gt2mezgcnyo.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.xuetiantiany.cn/Article/details/gt2dcxettpb.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.xuanzx.com/Article/details/gt2wunrrvkk.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.zhijiandao.cn/Article/details/gt2zkmadmor.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.vqdsnc.cn/Article/details/gt2wkmykwiu.html

[B15] 布尔运算与取反
来源：http://dali.nanxinkj.top/Article/details/gt2mayxvheg.html

Py:   a and b or not c
来源：http://dali.chenzaomai.com/Article/details/gt2fjbwfqyg.html

PHP:  $a && $b || !$c
来源：http://dali.xinyue.icu/Article/details/gt2aoimnzhg.html

JS:   a && b || !c
来源：http://dali.yuxming.cn/Article/details/gt2cxotqeot.html

TS:   a && b || !c
来源：http://dali.ydzc1.top/Article/details/gt2eifixsma.html

Java: a && b || !c
来源：http://dali.fengsongda.top/Article/details/gt2hjhsnyie.html

Go:   a && b || !c
来源：http://dali.ybcxt.top/Article/details/gt2phphcidt.html

Ruby: a && b || !c
来源：http://dali.gogol.net.cn/Article/details/gt2acrjjdsf.html

C#:   a && b || !c
来源：http://dali.dianchejie.cn/Article/details/gt2fminiaab.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.yanxiufei.cn/Article/details/gt2zzdsjgdv.html

Py:   if not data: return
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vacersjc.html

PHP:  if (!$data) { return; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2xqgthvmc.html

JS:   if (!data) return;
来源：http://dali.jqgufenzy.top/Article/details/gt2vvljfkhq.html

TS:   if (!data) return;
来源：http://dali.bjfxy.top/Article/details/gt2reorfxbd.html

Java: if (data == null) return;
来源：http://dali.tianlin.xyz/Article/details/gt2alagedwi.html

Go:   if data == nil { return }
来源：http://dali.haohaochexian.top/Article/details/gt2ebmmdwhs.html

Ruby: return if data.nil?
来源：http://dali.andypj.xyz/Article/details/gt2ftmkifbg.html

C#:   if (data == null) return;
来源：http://dali.xinyue.icu/Article/details/gt2jsjfkmzu.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gt2ehvfaedq.html

C. 函数与作用域
来源：http://dali.tianlin.xyz/Article/details/gt2zwjpeivh.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2xmxhvdph.html

[C01] 定义函数
来源：http://dali.sysykeji.top/Article/details/gt2iwdoxqan.html

Py:   def add(a, b): return a + b
来源：http://dali.wangshuangyany.cn/Article/details/gt2txhqpoka.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2dzqzsjve.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.birdmap.top/Article/details/gt2csqhytgo.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2xzsvlxst.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.redwolf501.top/Article/details/gt2pvxpohdu.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.jianghu66.top/Article/details/gt2exyzbxrb.html

Ruby: def add(a, b); a + b; end
来源：http://dali.chenzaomai.com/Article/details/gt2gptkznat.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jggrceqd.html

[C02] 默认参数
来源：http://dali.sxryk.cn/Article/details/gt2gwsrvlvz.html

Py:   def greet(name="World"): return name
来源：http://dali.haohaochexian.top/Article/details/gt2hqatcqlt.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.jinqigufen.top/Article/details/gt2tjbbaxvv.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.jinqigfzy.top/Article/details/gt2zlwpivhq.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yuanzhike.top/Article/details/gt2wxrduial.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.cucudq.cn/Article/details/gt2wwvhvcoc.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.hongshengwenyu.top/Article/details/gt2ltbfjdzx.html

Ruby: def greet(name = "World") = name
来源：http://dali.kuanghao11.cn/Article/details/gt2wweqvxxj.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.yj20258.top/Article/details/gt2sotsswqn.html

[C03] 可变参数
来源：http://dali.fzhhl.top/Article/details/gt2hbhouicg.html

Py:   def total(*args): return sum(args)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lmyyenjs.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.sufxvd.cn/Article/details/gt2uijcwuup.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.jianghu66.top/Article/details/gt2nrvtslpt.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.yongpay.top/Article/details/gt2dqjrpbbu.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.jiagoushi.top/Article/details/gt2lkmoiwkw.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.gzhubu.top/Article/details/gt2dcskazxk.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.gaohongyu789.top/Article/details/gt2kwckoyso.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.bjfxy.top/Article/details/gt2kkdiwetv.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jqgufenzy.top/Article/details/gt2azpaqoeg.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pwmcugnp.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.yj20258.top/Article/details/gt2lzwgrrwt.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.daria6918.cn/Article/details/gt2ytgdrhfy.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.nanxuanxn.top/Article/details/gt2bcscoppa.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.tanke756.top/Article/details/gt2tyqaczzx.html

Go:   // 无：用配置结构体参数
来源：http://dali.yj20258.top/Article/details/gt2fpdrakfz.html

Ruby: f(a: 1, b: 2)
来源：http://dali.sxryk.cn/Article/details/gt2gfzibawu.html

C#:   f(a: 1, b: 2)
来源：http://dali.sufxvd.cn/Article/details/gt2gjpbokej.html

[C05] 返回多个值
来源：http://dali.tian-w.cn/Article/details/gt2relngsib.html

Py:   return a, b
来源：http://dali.cucudq.cn/Article/details/gt2oeoakfdk.html

PHP:  return [$a, $b];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fsqnbqvg.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.xuanzx.com/Article/details/gt2grvkngpe.html

TS:   return { a, b };
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wgaomklo.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.yonumen.top/Article/details/gt2auxrdkcs.html

Go:   return a, b
来源：http://dali.yuxming.cn/Article/details/gt2zyvkdgig.html

Ruby: return a, b
来源：http://dali.zhiwuduotai.top/Article/details/gt2lyhrdatq.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.wangshuangyany.cn/Article/details/gt2qfzxovcr.html

[C06] 匿名函数 / lambda
来源：http://dali.gotoacloud.top/Article/details/gt2yfcmbmgw.html

Py:   square = lambda x: x * x
来源：http://dali.meibo888.top/Article/details/gt2dhfexgpt.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.cashguo.top/Article/details/gt2zoijtqcd.html

JS:   const square = x => x * x;
来源：http://dali.vqdsnc.cn/Article/details/gt2rbuxjisj.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.jianghu66.top/Article/details/gt2nfayfalf.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.feifeiyinyue.top/Article/details/gt2vgnvrrrb.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.hammf.cn/Article/details/gt2eppjqgzc.html

Ruby: square = ->(x) { x * x }
来源：http://dali.havefunace.top/Article/details/gt2wxohohxv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.yanxiufei.cn/Article/details/gt2twxmblua.html

[C07] 把函数作为参数传入
来源：http://dali.wangdashe.top/Article/details/gt2abznqeio.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.316326.xyz/Article/details/gt2nzxxcsha.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.316326.xyz/Article/details/gt2mrvipeyn.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.aibaodan.cn/Article/details/gt2eoeqqjqw.html

TS:   arr.map(String)
来源：http://dali.yuanzhike.top/Article/details/gt2ouemeieo.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.redwolf501.top/Article/details/gt2ydvctyfk.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.feifeiyinyue.top/Article/details/gt2jmetulid.html

Ruby: arr.map(&:upcase)
来源：http://dali.nanxuanxn.top/Article/details/gt2judecblb.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.zhijiandao.cn/Article/details/gt2eypcxukn.html

[C08] 闭包
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxniokcd.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.zycfv.cn/Article/details/gt2pfxaesuh.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2quvyhtub.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gmzkzbbz.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2pobemqox.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.daria6918.cn/Article/details/gt2wlngpaau.html


<!-- 参考信息 -->