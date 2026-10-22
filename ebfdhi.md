代发 wailian999

[A18] 字符与 ASCII 码互转
来源：http://dali.tianlin.xyz/Article/details/gt2zvzimstb.html

Py:   ord("A"); chr(65)
来源：http://dali.svipenyu.cn/Article/details/gt2jsdnqvwj.html

PHP:  ord("A"); chr(65)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nwomzcjr.html

JS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.andypj.xyz/Article/details/gt2uqsszcax.html

TS:   "A".charCodeAt(0); String.fromCharCode(65)
来源：http://dali.cucudq.cn/Article/details/gt2nntjsjde.html

Java: (int) 'A'; (char) 65
来源：http://dali.yj202588.top/Article/details/gt2oiubbxds.html

Go:   int('A'); rune(65)              // rune 是 int32
来源：http://dali.tianlin.xyz/Article/details/gt2rujnzfqx.html

Ruby: "A".ord; 65.chr
来源：http://dali.hywenlv.cn/Article/details/gt2scpfvczm.html

C#:   (int)'A'; (char)65
来源：http://dali.tianlin.xyz/Article/details/gt2imusqiof.html

[A19] 交换两个变量
来源：http://dali.hnxiangtu.top/Article/details/gt2wedgnynq.html

Py:   a, b = b, a
来源：http://dali.yongpay.top/Article/details/gt2vzmikwfa.html

PHP:  [$a, $b] = [$b, $a];
来源：http://dali.ppjwa.cn/Article/details/gt2tjhuyecf.html

JS:   [a, b] = [b, a];
来源：http://dali.svipenyu.cn/Article/details/gt2blacatcy.html

TS:   [a, b] = [b, a];
来源：http://dali.ivvv.top/Article/details/gt2fjrfcwbq.html

Java: int t = a; a = b; b = t;
来源：http://dali.mhx1999.top/Article/details/gt2snlfxnno.html

Go:   a, b = b, a
来源：http://dali.sysykeji.top/Article/details/gt2jjdynmjr.html

Ruby: a, b = b, a
来源：http://dali.aizwys.cn/Article/details/gt2xqsadbjj.html

C#:   (a, b) = (b, a);
来源：http://dali.zhijiandao.cn/Article/details/gt2utjtmrcd.html

[A20] 读取标准输入
来源：http://dali.iojbl.cn/Article/details/gt2ibwfrqmf.html

Py:   name = input("请输入：")
来源：http://dali.jqgufenzy.top/Article/details/gt2lrqwhxqx.html

PHP:  $name = trim(fgets(STDIN));
来源：http://dali.yanxiufei.cn/Article/details/gt2hweauwax.html

JS:   // Node.js：readline 模块或 process.stdin
来源：http://dali.cucudq.cn/Article/details/gt2uiycandc.html

TS:   // Node.js：readline 模块
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2hpfefohc.html

Java: new Scanner(System.in).nextLine()
来源：http://dali.hnxiangtu.top/Article/details/gt2ugfiynmx.html

Go:   fmt.Scanln(&name)               // 或 bufio.NewReader(os.Stdin)
来源：http://dali.0kj1m.cn/Article/details/gt2uasvvsko.html

Ruby: gets.chomp
来源：http://dali.ppjwa.cn/Article/details/gt2pbpqcboe.html

C#:   Console.ReadLine();
来源：http://dali.ppjwa.cn/Article/details/gt2waghbnjt.html

[A21] 保留指定小数位输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2adhfgvkr.html

Py:   f"{3.14159:.2f}"
来源：http://dali.tian-w.cn/Article/details/gt2eraagazd.html

PHP:  number_format(3.14159, 2); sprintf("%.2f", 3.14159)
来源：http://dali.hongshengwenyu.top/Article/details/gt2ngledumy.html

JS:   (3.14159).toFixed(2)
来源：http://dali.aibaodan.cn/Article/details/gt2lcepxsox.html

TS:   (3.14159).toFixed(2)
来源：http://dali.jinqigufen.top/Article/details/gt2ptrottgw.html

Java: String.format("%.2f", 3.14159)
来源：http://dali.shuidangran.top/Article/details/gt2cpmkujir.html

Go:   fmt.Sprintf("%.2f", 3.14159)
来源：http://dali.9152youxi.cn/Article/details/gt2scnzrttr.html

Ruby: format("%.2f", 3.14159)
来源：http://dali.ehwqpu.com/Article/details/gt2drhgbhyr.html

C#:   3.14159.ToString("F2")
来源：http://dali.sysykeji.top/Article/details/gt2ukntjqbf.html

[A22] 获取字符串长度
来源：http://dali.mhx1999.top/Article/details/gt2sjkodvde.html

Py:   len(s)
来源：http://dali.ydzc1.top/Article/details/gt2fbxiqhgy.html

PHP:  strlen($s); mb_strlen($s, "UTF-8")   # 中文要用 mb_
来源：http://dali.xuanzx.com/Article/details/gt2pqfpydaq.html

JS:   s.length                          # 按 UTF-16 单元计
来源：http://dali.xinyue.icu/Article/details/gt2zmfjarim.html

TS:   s.length
来源：http://dali.hysaishi.cn/Article/details/gt2dkbvpxei.html

Java: s.length()
来源：http://dali.zhengqikj.top/Article/details/gt2kxocdicr.html

Go:   len(s); utf8.RuneCountInString(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbdiawqc.html

Ruby: s.length
来源：http://dali.ppjwa.cn/Article/details/gt2iwmteghq.html

C#:   s.Length
来源：http://dali.yangfankeji.com/Article/details/gt2kujmvtru.html

[A23] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2jwjecbcv.html

Py:   s.upper(); s.lower(); s.title()
来源：http://dali.316326.xyz/Article/details/gt2spcevogq.html

PHP:  strtoupper($s); strtolower($s); ucfirst($s)
来源：http://dali.tianlin.xyz/Article/details/gt2bonlxcya.html

JS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.vqdsnc.cn/Article/details/gt2ztgjrcxu.html

TS:   s.toUpperCase(); s.toLowerCase()
来源：http://dali.zhongyouzk.top/Article/details/gt2moqjyffa.html

Java: s.toUpperCase(); s.toLowerCase()
来源：http://dali.ybcxt.top/Article/details/gt2hucgacht.html

Go:   strings.ToUpper(s); strings.ToLower(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2bnlbiggf.html

Ruby: s.upcase; s.downcase; s.capitalize
来源：http://dali.xinyue.icu/Article/details/gt2ppibmbtz.html

C#:   s.ToUpper(); s.ToLower()
来源：http://dali.jinqigfzy.top/Article/details/gt2twxpwbbb.html

[A24] 去除首尾空白
来源：http://dali.yj20258.top/Article/details/gt2xnydaczi.html

Py:   s.strip(); s.lstrip(); s.rstrip()
来源：http://dali.zhoulong.xyz/Article/details/gt2dprhydym.html

PHP:  trim($s); ltrim($s); rtrim($s)
来源：http://dali.xziqi.cn/Article/details/gt2njuhhkgj.html

JS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.kuanghao11.cn/Article/details/gt2lhnurqpa.html

TS:   s.trim(); s.trimStart(); s.trimEnd()
来源：http://dali.gzhubu.top/Article/details/gt2cvpinxos.html

Java: s.trim(); s.strip()             # strip 支持 Unicode
来源：http://dali.xylfe.cn/Article/details/gt2wypnkvtj.html

Go:   strings.TrimSpace(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cgbmvcsd.html

Ruby: s.strip; s.lstrip; s.rstrip
来源：http://dali.yanxiufei.cn/Article/details/gt2dnqlnias.html

C#:   s.Trim(); s.TrimStart(); s.TrimEnd()
来源：http://dali.ivvv.top/Article/details/gt2bgmoskrz.html

[A25] 字符串比较
来源：http://dali.cucudq.cn/Article/details/gt2wuiolwov.html

Py:   s1 == s2; s1 != s2
来源：http://dali.yanxiufei.cn/Article/details/gt2fxfbwowb.html

PHP:  $s1 === $s2; strcmp($s1, $s2)
来源：http://dali.316326.xyz/Article/details/gt2kgxyztux.html

JS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.ivvv.top/Article/details/gt2jhewrbke.html

TS:   s1 === s2; s1.localeCompare(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2hjwgnqki.html

Java: s1.equals(s2); s1.compareTo(s2)
来源：http://dali.yanxiufei.cn/Article/details/gt2zljzyxuw.html

Go:   s1 == s2; strings.Compare(s1, s2)
来源：http://dali.nwbrower.top/Article/details/gt2blwrdxta.html

Ruby: s1 == s2; s1 <=> s2
来源：http://dali.yanxiufei.cn/Article/details/gt2whjycioj.html

C#:   s1 == s2; string.Compare(s1, s2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2hmtpvlij.html

[A26] 类型转换总览
来源：http://dali.yongpay.top/Article/details/gt2leqgrnmo.html

Py:   int() float() str() bool() list() dict() tuple()
来源：http://dali.jqgfzy.top/Article/details/gt2vfuhipxx.html

PHP:  (int) (float) (string) (bool) (array) (object)
来源：http://dali.yuxming.cn/Article/details/gt2sjgepwwk.html

JS:   Number() String() Boolean() parseInt() parseFloat()
来源：http://dali.zhixingplan.top/Article/details/gt2cznkytfb.html

TS:   Number() String() Boolean() x as number
来源：http://dali.chenlongwang.top/Article/details/gt2fyugsosp.html

Java: Integer.parseInt() String.valueOf() (int) (double)
来源：http://dali.gzhubu.top/Article/details/gt2qdcvmvsr.html

Go:   int() float64() string() []byte()   // 需显式转换
来源：http://dali.cucudq.cn/Article/details/gt2jmgnodmz.html

Ruby: to_i to_f to_s to_sym to_a
来源：http://dali.fzhhl.top/Article/details/gt2fkntpcfq.html

C#:   Convert.ToInt32() Convert.ToString() (int) (double)
来源：http://dali.fengsongda.top/Article/details/gt2rlavueer.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2rgvzhvgb.html

B. 流程控制
来源：http://dali.shuidangran.top/Article/details/gt2thmmdbqh.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gt2bblatbkt.html

[B01] 条件判断 if / else
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ismhalvw.html

Py:   result = "正" if x > 0 else "非正"
来源：http://dali.zycfv.cn/Article/details/gt2avmjiysz.html

PHP:  if ($x > 0) { $r = "正"; } else { $r = "非正"; }
来源：http://dali.mhx1999.top/Article/details/gt2dgwbynti.html

JS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.cqqwz.cn/Article/details/gt2ljfaqwtc.html

TS:   const r = x > 0 ? "正" : "非正";
来源：http://dali.kuanghao11.cn/Article/details/gt2klcjjehb.html

Java: String r = x > 0 ? "正" : "非正";
来源：http://dali.tanke756.top/Article/details/gt2lwssnwbx.html

Go:   if x > 0 { r = "正" } else { r = "非正" }
来源：http://dali.gaohongyu789.top/Article/details/gt2hpeegtzr.html

Ruby: r = x > 0 ? "正" : "非正"
来源：http://dali.cheryme.top/Article/details/gt2fnwebrhq.html

C#:   var r = x > 0 ? "正" : "非正";
来源：http://dali.zdqjudy.top/Article/details/gt2wxeznmhx.html

[B02] 多分支 else if / elif
来源：http://dali.chenzaomai.com/Article/details/gt2aqrhjlro.html

Py:   s = "正" if x > 0 else ("负" if x < 0 else "零")
来源：http://dali.zhongyouzk.top/Article/details/gt2upvlxquz.html

PHP:  if ($x > 0) { $s = "正"; } elseif ($x < 0) { $s = "负"; } else { $s = "零"; }
来源：http://dali.xylfe.cn/Article/details/gt2govvfhqo.html

JS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.yj202588.top/Article/details/gt2wfuwtxjh.html

TS:   x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.nanxinkj.top/Article/details/gt2crrdejvn.html

Java: x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.bjfxy.top/Article/details/gt2fitpodgy.html

Go:   if x > 0 { s = "正" } else if x < 0 { s = "负" } else { s = "零" }
来源：http://dali.9152youxi.cn/Article/details/gt2paqvcvah.html

Ruby: s = if x > 0 then "正" elsif x < 0 then "负" else "零" end
来源：http://dali.xuanzx.com/Article/details/gt2nseiibnn.html

C#:   var s = x > 0 ? "正" : x < 0 ? "负" : "零";
来源：http://dali.jianghu66.top/Article/details/gt2hvqiiyog.html

[B03] switch / match / case
来源：http://dali.yj20258888.top/Article/details/gt2nyjavnsb.html

Py:   {"a": 1, "b": 2}.get(key, 0)         # 3.10+ 也可用 match
来源：http://dali.dianchejie.cn/Article/details/gt2ofvlidfl.html

PHP:  switch ($x) { case 1: $r = "一"; break; default: $r = "其他"; }
来源：http://dali.guannengcc.top/Article/details/gt2izaqpgsz.html

JS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.jiagoushi.top/Article/details/gt2acjltfem.html

TS:   switch (x) { case 1: r = "一"; break; default: r = "其他"; }
来源：http://dali.zycfv.cn/Article/details/gt2igdrxrke.html

Java: switch (x) { case 1 -> r = "一"; default -> r = "其他"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2gmvtlvrz.html

Go:   switch x { case 1: r = "一"; default: r = "其他" }
来源：http://dali.yj20258.top/Article/details/gt2ljpeymxh.html

Ruby: case x when 1 then r = "一" else r = "其他" end
来源：http://dali.fengsongda.top/Article/details/gt2mgqaafyz.html

C#:   var r = x switch { 1 => "一", _ => "其他" };
来源：http://dali.gotoacloud.top/Article/details/gt2emwcbjoa.html

[B04] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gt2tpsdgpud.html

Py:   for i in range(10): print(i)
来源：http://dali.snrcjt.cn/Article/details/gt2pkchlczu.html

PHP:  for ($i = 0; $i < 10; $i++) { echo $i; }
来源：http://dali.jyoumei.cn/Article/details/gt2ssixvpac.html

JS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.nanxinkj.top/Article/details/gt2rjowzkzn.html

TS:   for (let i = 0; i < 10; i++) { console.log(i); }
来源：http://dali.zhixingplan.top/Article/details/gt2uyypohui.html

Java: for (int i = 0; i < 10; i++) { System.out.println(i); }
来源：http://dali.hnqzz.top/Article/details/gt2ardhuzgr.html

Go:   for i := 0; i < 10; i++ { fmt.Println(i) }
来源：http://dali.hnxiangtu.top/Article/details/gt2xxnqcjpm.html

Ruby: 10.times { |i| puts i }
来源：http://dali.sysykeji.top/Article/details/gt2cfnkvenl.html

C#:   for (int i = 0; i < 10; i++) { Console.WriteLine(i); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2iguekfih.html

[B05] 遍历数组 / 列表
来源：http://dali.ybcxt.top/Article/details/gt2mzstlvnd.html

Py:   for item in arr: print(item)
来源：http://dali.vqdsnc.cn/Article/details/gt2jqsqyttn.html

PHP:  foreach ($arr as $item) { echo $item; }
来源：http://dali.sysykeji.top/Article/details/gt2tjvbdzdn.html

JS:   for (const item of arr) { console.log(item); }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2stzzlrew.html

TS:   for (const item of arr) { console.log(item); }
来源：http://dali.cheryme.top/Article/details/gt2lnerbany.html

Java: for (var item : arr) { System.out.println(item); }
来源：http://dali.sxryk.cn/Article/details/gt2idcthdse.html

Go:   for _, item := range arr { fmt.Println(item) }
来源：http://dali.svipenyu.cn/Article/details/gt2umcqdsip.html

Ruby: arr.each { |item| puts item }
来源：http://dali.0kj1m.cn/Article/details/gt2cwgibbgj.html

C#:   foreach (var item in arr) { Console.WriteLine(item); }
来源：http://dali.sufxvd.cn/Article/details/gt2hbrqfccf.html

[B06] 遍历字典 / 对象
来源：http://dali.havefunace.top/Article/details/gt2twmdpmyq.html

Py:   for k, v in d.items(): print(k, v)
来源：http://dali.zhixingplan.top/Article/details/gt2vmitvuyw.html

PHP:  foreach ($d as $k => $v) { echo "$k=$v"; }
来源：http://dali.guowangkeji.top/Article/details/gt2famklmsl.html

JS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.kuanghao11.cn/Article/details/gt2dwkbkgkp.html

TS:   for (const [k, v] of Object.entries(obj)) { console.log(k, v); }
来源：http://dali.cucudq.cn/Article/details/gt2cbwguqay.html

Java: for (var e : map.entrySet()) { System.out.println(e.getKey() + "=" + e.getValue()); }
来源：http://dali.redwolf501.top/Article/details/gt2pnwkfejx.html

Go:   for k, v := range m { fmt.Println(k, v) }
来源：http://dali.smart0.xyz/Article/details/gt2ptkstrtb.html

Ruby: d.each { |k, v| puts "#{k}=#{v}" }
来源：http://dali.chenzaomai.com/Article/details/gt2kfmetvsy.html

C#:   foreach (var (k, v) in dict) { Console.WriteLine($"{k}={v}"); }
来源：http://dali.jiagoushi.top/Article/details/gt2drgazhym.html

[B07] while 循环
来源：http://dali.yvedp.cn/Article/details/gt2wlzzovvx.html

Py:   while i < 10: i += 1
来源：http://dali.yueranfly.top/Article/details/gt2mfgtttdj.html

PHP:  while ($i < 10) { $i++; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jsecxjpc.html

JS:   while (i < 10) { i++; }
来源：http://dali.yj20258888.top/Article/details/gt2jzxzxhqh.html

TS:   while (i < 10) { i++; }
来源：http://dali.sxryk.cn/Article/details/gt2gkeobsuh.html

Java: while (i < 10) { i++; }
来源：http://dali.quarkkingdee.top/Article/details/gt2ncpoolbn.html

Go:   for i < 10 { i++ }              # Go 没有 while，用单条件 for
来源：http://dali.c1oappe.top/Article/details/gt2xjvjelfl.html

Ruby: while i < 10; i += 1; end
来源：http://dali.zhongyouzk.top/Article/details/gt2qxrbrtkw.html

C#:   while (i < 10) { i++; }
来源：http://dali.iojbl.cn/Article/details/gt2adicgxrh.html

[B08] do-while（至少执行一次）
来源：http://dali.yvedp.cn/Article/details/gt2igkeeeit.html

Py:   # 无 do-while：用 while True + break
来源：http://dali.feifeiyinyue.top/Article/details/gt2udhwwvdi.html

PHP:  do { $i++; } while ($i < 10);
来源：http://dali.gzhubu.top/Article/details/gt2bmqaqhqy.html

JS:   do { i++; } while (i < 10);
来源：http://dali.yuxming.cn/Article/details/gt2lrdvsccn.html

TS:   do { i++; } while (i < 10);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nvvyddfh.html

Java: do { i++; } while (i < 10);
来源：http://dali.nanxinkj.top/Article/details/gt2enklgiyr.html

Go:   for { i++; if i >= 10 { break } }
来源：http://dali.9152youxi.cn/Article/details/gt2bmrghbsl.html

Ruby: begin; i += 1; end while i < 10
来源：http://dali.sxryk.cn/Article/details/gt2kibawkfi.html

C#:   do { i++; } while (i < 10);
来源：http://dali.fengsongda.top/Article/details/gt2lwdymavc.html

[B09] break 与 continue
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lbxprart.html

Py:   for x in arr: if x < 0: continue     # break 直接退出循环
来源：http://dali.guannengcc.top/Article/details/gt2jngwocok.html

PHP:  foreach ($arr as $x) { if ($x < 0) continue; if ($x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2mhwudyru.html

JS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.aibaodan.cn/Article/details/gt2ktkhxpic.html

TS:   for (const x of arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qpcwhrzv.html

Java: for (int x : arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wfjyqzja.html

Go:   for _, x := range arr { if x < 0 { continue }; if x > 9 { break } }
来源：http://dali.andypj.xyz/Article/details/gt2jytuqmpk.html

Ruby: arr.each { |x| next if x < 0; break if x > 9 }
来源：http://dali.svipenyu.cn/Article/details/gt2gubzrltp.html

C#:   foreach (var x in arr) { if (x < 0) continue; if (x > 9) break; }
来源：http://dali.chenlongwang.top/Article/details/gt2cxewkvyt.html

[B10] 遍历同时拿索引
来源：http://dali.quarkkingdee.top/Article/details/gt2onzwbyvd.html

Py:   for i, item in enumerate(arr): print(i, item)
来源：http://dali.zhongyouzk.top/Article/details/gt2fnnsmboo.html

PHP:  foreach ($arr as $i => $item) { echo "$i: $item"; }
来源：http://dali.yuanzhike.top/Article/details/gt2husrcssn.html

JS:   arr.forEach((item, i) => console.log(i, item));
来源：http://dali.zhijiandao.cn/Article/details/gt2euzrsioz.html

TS:   arr.forEach((item: string, i: number) => console.log(i, item));
来源：http://dali.shuidangran.top/Article/details/gt2tahybcgt.html

Java: for (int i = 0; i < arr.size(); i++) { System.out.println(i + ":" + arr.get(i)); }
来源：http://dali.zycfv.cn/Article/details/gt2xvnmzkpb.html

Go:   for i, item := range arr { fmt.Println(i, item) }
来源：http://dali.9152youxi.cn/Article/details/gt2tnzjsnxd.html

Ruby: arr.each_with_index { |item, i| puts "#{i}: #{item}" }
来源：http://dali.bjfxy.top/Article/details/gt2ezmlslkj.html

C#:   for (int i = 0; i < arr.Length; i++) { Console.WriteLine($"{i}:{arr[i]}"); }
来源：http://dali.redwolf501.top/Article/details/gt2zvbzeysm.html

[B11] 生成数字序列 / 区间
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jrzjyaed.html

Py:   list(range(0, 10, 2))
来源：http://dali.quarkkingdee.top/Article/details/gt2ujxpgaff.html

PHP:  range(0, 10, 2);
来源：http://dali.nwbrower.top/Article/details/gt2lpsispye.html

JS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.guannengcc.top/Article/details/gt2sukdmyev.html

TS:   Array.from({ length: 5 }, (_, i) => i * 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fximtosi.html

Java: IntStream.range(0, 10).boxed().toList()
来源：http://dali.kuanghao11.cn/Article/details/gt2cmbueuel.html

Go:   for i := 0; i < 10; i += 2 { }   // 无区间生成器
来源：http://dali.zycfv.cn/Article/details/gt2nrtespmn.html

Ruby: (0...10).step(2).to_a
来源：http://dali.chenlongwang.top/Article/details/gt2rmfpgcie.html

C#:   Enumerable.Range(0, 10).Where(i => i % 2 == 0)
来源：http://dali.birdmap.top/Article/details/gt2grlanoaw.html

[B12] 跳出多层循环
来源：http://dali.yuxming.cn/Article/details/gt2tmucfoih.html

Py:   # 无标签跳转：抽成函数用 return
来源：http://dali.dianchejie.cn/Article/details/gt2rpjcrjcs.html

PHP:  # 无标签：用 goto 或函数返回
来源：http://dali.cqqwz.cn/Article/details/gt2ntvzqjkh.html

JS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2zedtdfig.html

TS:   outer: for (...) { for (...) { break outer; } }
来源：http://dali.iojbl.cn/Article/details/gt2dxoljdcw.html

Java: outer: for (...) { for (...) { break outer; } }
来源：http://dali.sufxvd.cn/Article/details/gt2izsgpsyr.html

Go:   # 无标签：用布尔标志或抽成函数
来源：http://dali.meibo888.top/Article/details/gt2fsnirgyz.html

Ruby: # 无标签：用 catch/throw 或方法返回
来源：http://dali.feifeiyinyue.top/Article/details/gt2egazwxxy.html

C#:   # 无标签：用 goto label 或布尔标志
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jvpeouhi.html

[B13] 判断是否为数字
来源：http://dali.shangyingyoupin.top/Article/details/gt2jmromhhy.html

Py:   isinstance(x, (int, float))
来源：http://dali.sufxvd.cn/Article/details/gt2qzstjfzq.html

PHP:  is_numeric($x)
来源：http://dali.daria6918.cn/Article/details/gt2kznrwopj.html

JS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.316326.xyz/Article/details/gt2hdoktmql.html

TS:   typeof x === "number" && !Number.isNaN(x)
来源：http://dali.snrcjt.cn/Article/details/gt2tyfmjznk.html

Java: x instanceof Number
来源：http://dali.nanxuanxn.top/Article/details/gt2xzszntth.html

Go:   if _, err := strconv.Atoi(s); err == nil { ok = true }
来源：http://dali.ehwqpu.com/Article/details/gt2lyzkzfsc.html

Ruby: x.is_a?(Numeric)
来源：http://dali.zhijiandao.cn/Article/details/gt2uozlviuk.html

C#:   x is int or double or decimal
来源：http://dali.yueranfly.top/Article/details/gt2aarrlciv.html

[B14] 判断值是否在集合内
来源：http://dali.tian-w.cn/Article/details/gt2hwttqxyp.html

Py:   x in [1, 2, 3]; x in {"a", "b"}
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmqqrtpz.html

PHP:  in_array($x, [1, 2, 3], true)
来源：http://dali.xziqi.cn/Article/details/gt2vzpgsmff.html

JS:   [1, 2, 3].includes(x)
来源：http://dali.mhx1999.top/Article/details/gt2ufphifsj.html

TS:   [1, 2, 3].includes(x)
来源：http://dali.fengsongda.top/Article/details/gt2dspzvnbd.html

Java: List.of(1, 2, 3).contains(x)
来源：http://dali.yongpay.top/Article/details/gt2taazcmnw.html

Go:   slices.Contains([]int{1, 2, 3}, x)
来源：http://dali.yj20258888.top/Article/details/gt2wjkqkxel.html

Ruby: [1, 2, 3].include?(x)
来源：http://dali.havefunace.top/Article/details/gt2zynmewtn.html

C#:   new[] { 1, 2, 3 }.Contains(x)
来源：http://dali.jqgufenzy.top/Article/details/gt2kyknhhxp.html

[B15] 布尔运算与取反
来源：http://dali.jinqigufen.top/Article/details/gt2fwukruhc.html

Py:   a and b or not c
来源：http://dali.kuanghao11.cn/Article/details/gt2ofmmdihx.html

PHP:  $a && $b || !$c
来源：http://dali.dashuyun.cn/Article/details/gt2hesmscwa.html

JS:   a && b || !c
来源：http://dali.zhengqikj.top/Article/details/gt2wlubqbty.html

TS:   a && b || !c
来源：http://dali.hysaishi.cn/Article/details/gt2awfpultn.html

Java: a && b || !c
来源：http://dali.chenzaomai.com/Article/details/gt2zgjhchzj.html

Go:   a && b || !c
来源：http://dali.meibo888.top/Article/details/gt2yaaxelss.html

Ruby: a && b || !c
来源：http://dali.tanke756.top/Article/details/gt2ipujvcti.html

C#:   a && b || !c
来源：http://dali.jinqigfzy.top/Article/details/gt2fbtltxff.html

[B16] 卫语句：不满足条件提前返回
来源：http://dali.dianchejie.cn/Article/details/gt2ooweittn.html

Py:   if not data: return
来源：http://dali.havefunace.top/Article/details/gt2fcfjfgji.html

PHP:  if (!$data) { return; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2nmpcbukb.html

JS:   if (!data) return;
来源：http://dali.hywenlv.cn/Article/details/gt2loneshpc.html

TS:   if (!data) return;
来源：http://dali.guowangkeji.top/Article/details/gt2yxquxnjf.html

Java: if (data == null) return;
来源：http://dali.dashuyun.cn/Article/details/gt2evyiazko.html

Go:   if data == nil { return }
来源：http://dali.daria6918.cn/Article/details/gt2lmkayiiy.html

Ruby: return if data.nil?
来源：http://dali.quarkkingdee.top/Article/details/gt2noqqipzy.html

C#:   if (data == null) return;
来源：http://dali.yuxming.cn/Article/details/gt2bsgmxgnb.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2mehkvwwf.html

C. 函数与作用域
来源：http://dali.shzxlz.cn/Article/details/gt2aglitqxl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2ylxnhoma.html

[C01] 定义函数
来源：http://dali.cqqwz.cn/Article/details/gt2vmhwvmko.html

Py:   def add(a, b): return a + b
来源：http://dali.shzxlz.cn/Article/details/gt2lgyiwcxp.html

PHP:  function add(int $a, int $b): int { return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gt2lkigptoe.html

JS:   function add(a, b) { return a + b; }
来源：http://dali.yj20258888.top/Article/details/gt2uctubkxs.html

TS:   function add(a: number, b: number): number { return a + b; }
来源：http://dali.jinqigufen.top/Article/details/gt2xpsuoide.html

Java: static int add(int a, int b) { return a + b; }
来源：http://dali.zhijiandao.cn/Article/details/gt2vymaxjdk.html

Go:   func add(a, b int) int { return a + b }
来源：http://dali.yuxming.cn/Article/details/gt2cttojgoo.html

Ruby: def add(a, b); a + b; end
来源：http://dali.jinqigufen.top/Article/details/gt2wbxtlkyy.html

C#:   static int Add(int a, int b) { return a + b; }
来源：http://dali.vqdsnc.cn/Article/details/gt2ghyipgft.html

[C02] 默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2pnekmtfw.html

Py:   def greet(name="World"): return name
来源：http://dali.redwolf501.top/Article/details/gt2htlkwyiu.html

PHP:  function greet($name = "World") { return $name; }
来源：http://dali.hywenlv.cn/Article/details/gt2lxupecgf.html

JS:   function greet(name = "World") { return name; }
来源：http://dali.xylfe.cn/Article/details/gt2tuqypmpo.html

TS:   function greet(name: string = "World") { return name; }
来源：http://dali.yj202588.top/Article/details/gt2qixvfsfd.html

Java: // 无默认参数：方法重载或 Optional
来源：http://dali.jianghu66.top/Article/details/gt2wpiktvkz.html

Go:   // 无默认参数：传零值或另写一个包装函数
来源：http://dali.smart0.xyz/Article/details/gt2mkxleamx.html

Ruby: def greet(name = "World") = name
来源：http://dali.cqqwz.cn/Article/details/gt2qbljrcjg.html

C#:   string Greet(string name = "World") => name;
来源：http://dali.ydzc1.top/Article/details/gt2wnivkesh.html

[C03] 可变参数
来源：http://dali.pycfn.com/Article/details/gt2fwyzuskx.html

Py:   def total(*args): return sum(args)
来源：http://dali.gotoacloud.top/Article/details/gt2sgdjbyvb.html

PHP:  function total(...$nums) { return array_sum($nums); }
来源：http://dali.daxiang520.top/Article/details/gt2wfpbjtlq.html

JS:   function total(...nums) { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.cdnleiting.top/Article/details/gt2jfwgoszf.html

TS:   function total(...nums: number[]): number { return nums.reduce((a, b) => a + b, 0); }
来源：http://dali.ehwqpu.com/Article/details/gt2tixtnsbg.html

Java: static int total(int... nums) { return Arrays.stream(nums).sum(); }
来源：http://dali.smart0.xyz/Article/details/gt2upbdbpbp.html

Go:   func total(nums ...int) int { s := 0; for _, n := range nums { s += n }; return s }
来源：http://dali.jqgfzy.top/Article/details/gt2sfecvwpl.html

Ruby: def total(*nums); nums.sum; end
来源：http://dali.xylfe.cn/Article/details/gt2fajeagtc.html

C#:   static int Total(params int[] nums) => nums.Sum();
来源：http://dali.sweek.top/Article/details/gt2spqqyxtr.html

[C04] 命名参数 / 关键字参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kiyelxdh.html

Py:   def f(a, b, *, c=0): ...    # 调用 f(1, 2, c=3)
来源：http://dali.ehwqpu.com/Article/details/gt2fkscmown.html

PHP:  f(a: 1, b: 2)             // PHP 8 命名参数
来源：http://dali.wangdashe.top/Article/details/gt2djtqtsmx.html

JS:   // 无命名参数：传配置对象 function f({ a, b }) {}
来源：http://dali.fengsongda.top/Article/details/gt2shnpkhbr.html

TS:   f({ a: 1, b: 2 })          // 同上
来源：http://dali.sweek.top/Article/details/gt2nfmuboij.html

Java: // 无：用 Builder 模式或 record
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcmnfggi.html

Go:   // 无：用配置结构体参数
来源：http://dali.jqgfzy.top/Article/details/gt2brrtsmfy.html

Ruby: f(a: 1, b: 2)
来源：http://dali.nanxinkj.top/Article/details/gt2tbdkdqiw.html

C#:   f(a: 1, b: 2)
来源：http://dali.yueranfly.top/Article/details/gt2ckinwgnx.html

[C05] 返回多个值
来源：http://dali.tianlin.xyz/Article/details/gt2djluqfnr.html

Py:   return a, b
来源：http://dali.jlsjyb.cn/Article/details/gt2yipuwnbt.html

PHP:  return [$a, $b];
来源：http://dali.hywenlv.cn/Article/details/gt2csxosnjj.html

JS:   return [a, b];             // 或 return { a, b };
来源：http://dali.wangdashe.top/Article/details/gt2moixktjc.html

TS:   return { a, b };
来源：http://dali.pengpengdd.cyou/Article/details/gt2rawwqiza.html

Java: record Pair(int a, int b) {}  // 或 return new int[]{a, b};
来源：http://dali.9152youxi.cn/Article/details/gt2nwrfuesz.html

Go:   return a, b
来源：http://dali.zhijiandao.cn/Article/details/gt2ygyrcmfa.html

Ruby: return a, b
来源：http://dali.gzhubu.top/Article/details/gt2ribfqfdp.html

C#:   return (a, b);              // ValueTuple
来源：http://dali.jqgufenzy.top/Article/details/gt2msfutcew.html

[C06] 匿名函数 / lambda
来源：http://dali.meibo888.top/Article/details/gt2lsuepqjm.html

Py:   square = lambda x: x * x
来源：http://dali.316326.xyz/Article/details/gt2cfcrebnh.html

PHP:  $square = fn($x) => $x * $x;
来源：http://dali.hongshengwenyu.top/Article/details/gt2ferpnzzy.html

JS:   const square = x => x * x;
来源：http://dali.xylfe.cn/Article/details/gt2zhwlbopo.html

TS:   const square = (x: number): number => x * x;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tycaraeh.html

Java: Function<Integer, Integer> sq = x -> x * x;
来源：http://dali.havefunace.top/Article/details/gt2nfhgdoqc.html

Go:   sq := func(x int) int { return x * x }
来源：http://dali.jinqigufen.top/Article/details/gt2cdxvjkhj.html

Ruby: square = ->(x) { x * x }
来源：http://dali.zycfv.cn/Article/details/gt2iwubacmv.html

C#:   Func<int, int> square = x => x * x;
来源：http://dali.hammf.cn/Article/details/gt2jyzfqsja.html

[C07] 把函数作为参数传入
来源：http://dali.jianghu66.top/Article/details/gt2dynghsmk.html

Py:   list(map(str.upper, arr)); sorted(arr, key=len)
来源：http://dali.shzxlz.cn/Article/details/gt2seqybkcn.html

PHP:  array_map("strtoupper", $arr);
来源：http://dali.meibo888.top/Article/details/gt2ydvrzljw.html

JS:   arr.map(String).sort((a, b) => a.length - b.length)
来源：http://dali.shuidangran.top/Article/details/gt2dplwjawu.html

TS:   arr.map(String)
来源：http://dali.daria6918.cn/Article/details/gt2hmyeqhmj.html

Java: arr.stream().map(String::toUpperCase).toList()
来源：http://dali.xuetiantiany.cn/Article/details/gt2lysvvgpn.html

Go:   // 无 map 内置：手写循环或用 golang.org/x/exp/slices
来源：http://dali.yj202588.top/Article/details/gt2yjarfmec.html

Ruby: arr.map(&:upcase)
来源：http://dali.jyoumei.cn/Article/details/gt2lhekafos.html

C#:   arr.Select(s => s.ToUpper())
来源：http://dali.316326.xyz/Article/details/gt2mliuyevx.html

[C08] 闭包
来源：http://dali.birdmap.top/Article/details/gt2sdsrlttz.html

Py:   from itertools import count; inc = lambda c=count(1): next(c)   # 计数器
来源：http://dali.tianlin.xyz/Article/details/gt2djnwmyfr.html

PHP:  function counter() { $n = 0; return function () use (&$n) { return ++$n; }; }
来源：http://dali.xziqi.cn/Article/details/gt2giersfpl.html

JS:   function counter() { let n = 0; return () => ++n; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2grlbkhej.html

TS:   function counter(): () => number { let n = 0; return () => ++n; }
来源：http://dali.aibaodan.cn/Article/details/gt2txkrrdzb.html

Java: // 只能捕获 effectively final：用 int[] 或 AtomicInteger
来源：http://dali.hnxiangtu.top/Article/details/gt2ybqfviop.html


<!-- 参考信息 -->